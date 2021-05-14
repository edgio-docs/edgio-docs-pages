# Response Headers

This guide covers the headers that {{ PRODUCT_NAME }} injects into responses making them visible to your client code.

## General headers

- `{{ HEADER_PREFIX }}-version`: version fingerprint that includes {{ PRODUCT_NAME }} version number, site build number and UTC timestamp of the build
- `{{ HEADER_PREFIX }}-t`: timings of all the components in {{ PRODUCT_NAME }} critical path that served your request
- `{{ HEADER_PREFIX }}-request-id`: the unique ID of the request on {{ PRODUCT_NAME }} infrastructure
- `{{ HEADER_PREFIX }}-hit-request-id`: the unique ID of the request whose cached response is being returned (not present if cache miss)
- `{{ HEADER_PREFIX }}-caching-status`: indicates why a response was or was not cached. See [Caching](/guides/caching#section_why_is_my_response_not_being_cached_).
- `{{ HEADER_PREFIX }}-surrogate-key`: a space separated list of secondary cache keys used for [cache clearing](/guides/caching#section_clearing_the_cache)

### Structure of `{{ HEADER_PREFIX }}-t`

The format is `{{ HEADER_PREFIX }}-t: <id>=<time>[,<id2>=<time2>...]`

`{{ HEADER_PREFIX }}-t` is an order list of timings: values are prepended at response time. Thus reading them left to right goes from the outermost edge component to the innermost cloud component that handled the request.

The components are:

- Level 1 Edge POP = `o`
- Level 2 Shield POP = `s`
- Custom {{ PRODUCT_NAME }} Proxy = `p`
- JavaScript Compute Workers = `w`

All times are in milliseconds.

| Name | Description                                                                                                                                                                           |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ot   | The total time spent processing the request                                                                                                                                           |
| or   | The time spent matching routes at the edge pop                                                                                                                                        |
| of   | The time spent fetching the response at the edge pop, either from the shield pop or from the serverless backend or origin                                                             |
| oc   | The caching status for the edge pop                                                                                                                                                   |
| ow   | The free memory in bytes on the edge pop after processing the request                                                                                                                 |
| oq   | The time spent at the edge pop in fetch queue during the request coalescing                                                                                                           |
| st   | The time spent processing the request at the shield pop                                                                                                                               |
| sr   | The time spent matching routes at the shield pop                                                                                                                                      |
| sf   | The time spent waiting for a response from the serverless backend or origin, including request queueing                                                                               |
| sc   | The caching status for the shield pop                                                                                                                                                 |
| sw   | The free memory in bytes on the shield pop after processing the request                                                                                                               |
| sq   | The time spent at the shield pop in fetch queue during the request coalescing                                                                                                         |
| bf   | The time spent waiting for a response from the serverless backend or origin, including request queueing                                                                               |
| pc   | The number of times the request was scheduled to execute. If it's present it is normally `1`, if not your account is under significant pressure and you should consider upgrading it. |
| pf   | The time spent waiting for a response from the JavaScript worker                                                                                                                      |
| wm   | The amount of memory used in MB by the JavaScript worker to process the request                                                                                                       |
| wt   | The JavaScript worker execution time                                                                                                                                                  |
| wr   | The time spent matching routes in the JavaScript worker                                                                                                                               |
| wa   | The time spent transforming the request in JavaScript worker. Will only be provided if the request was transformed.                                                                   |
| wp   | The time spent waiting for your application (Next, Nuxt, Sapper, Angular, etc...) or origin to respond                                                                                |
| wz   | The time spent transforming the response in JavaScript worker. Will only be provided if the response was transformed.                                                                 |

## server-timing

{{ PRODUCT_NAME }} adds the following values to the standard [server-timing](https://www.w3.org/TR/server-timing/) response header:

- layer0-cache: desc=`value` - value will be one of:
  - `HIT-L1` - The page was served from the edge cache
  - `HIT-L2` - The page was served from the shield cache
  - `MISS` - The page could not be served from the cache
- country: desc=`country_code` - where country_code is the two letter code of the country from which the request was sent.
- xrj: desc=`route` - where route is the matched route serialized as JSON.

## Troubleshooting headers

The following headers are used internally by {{ PRODUCT_NAME }} staff to troubleshoot issues with requests.

- `{{ HEADER_PREFIX }}-status`: statuses of different components in {{ PRODUCT_NAME }} critical path that serviced your request
- `{{ HEADER_PREFIX }}-components`: versions of different components in {{ PRODUCT_NAME }} critical path that serviced your request
