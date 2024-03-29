#### **XDN Packages** - [v2.53.6](https://github.com/moovweb/xdn/releases/tag/v2.53.6) (2022-01-11)
* Bump version 2.53.6 (#1195) @KaarelKelk* Fixed Error: Unexpected keyword 'routeJson' in '.destinations' (#1194) @KaarelKelk---
#### **XDN Packages** - [v2.53.5](https://github.com/moovweb/xdn/releases/tag/v2.53.5) (2022-01-05)
* Fix cache disabled validation (#1176) @KaarelKelk---
#### **XDN Packages** - [v3.17.7](https://github.com/moovweb/xdn/releases/tag/v3.17.7) (2022-01-01)
* Remap BWI and DCA to IAD; add IAD (#1169) @ierceg---
#### **Layer0 Developer Console** - [v1.57.2](https://github.com/moovweb/le-deployer/releases/tag/v1.57.2) (2021-06-22)
- Use google dns @leotoll (#1042)---
#### **Layer0 Developer Console** - [v1.57.1](https://github.com/moovweb/le-deployer/releases/tag/v1.57.1) (2021-06-22)
- More Responsive Work @dijs (#1036)- Fixed React warnings around Avatar Tooltip @dijs (#1037)- Fix TLS for staff @leotoll (#1040)---
#### **Layer0 Packages** - [v3.16.0](https://github.com/moovweb/xdn/releases/tag/v3.16.0) (2021-06-21)
* XDN-12560 - Allow non-fallback routes after router.use() (#965) @markbrocato---
#### **Layer0 Developer Console** - [v1.57.0](https://github.com/moovweb/le-deployer/releases/tag/v1.57.0) (2021-06-21)
## 🚀 New Features- [MIGRATIONS] BYO Fastly @leotoll (#1022)- Added optional tooltip to user avatar. @dijs (#1030)## ✨ Enhancements- BYOF polishing @leotoll (#1034)- add email to deploy identify @leotoll (#1033)## 🐛 Bug Fixes- Fix header items being cut off, empty team page responsive layout @kevhender (#1032)- Invalid metrics query will not be executed when no fastly\_service\_id @MarkusTarn (#1024)---
#### **Layer0 Packages** - [v3.15.0](https://github.com/moovweb/xdn/releases/tag/v3.15.0) (2021-06-18)
* XDN-12520 - Next.js: support rewrites to 3rd party origins (#963) @markbrocato---
#### **Layer0 Packages** - [v3.14.0](https://github.com/moovweb/xdn/releases/tag/v3.14.0) (2021-06-17)
* Validated Layer0 support for Next.js 11. Updated Layer0's Next.js examples to Next.js 11.
* XDN-12516 - Next.js: rewrites.fallback loaded in the wrong order (#962) @markbrocato
* XDN-12514 - Next.js: Static pages with revalidate return 404 status w… (#961) @markbrocato
* Added new prefetch query param (#955) @dijs
* Reworded customer facing error message for domain already taken (#959) @dijs
* [XDN-11746] Warn if deploying to private space if site exists on another team (#938) @tristanlee85
---
#### **Layer0 Developer Console** - [v1.56.10](https://github.com/moovweb/le-deployer/releases/tag/v1.56.10) (2021-06-16)
## ✨ Enhancements
- Http logging enhancements @MarkusTarn (#1023)
- feat(Metrics) Support .catch error page routes in metrics @KaarelKelk (#1029)
- Fixed Layer0 messaging in 1 click deploy @dijs (#1027)
---
#### **Layer0 Packages** - [v3.13.3](https://github.com/moovweb/xdn/releases/tag/v3.13.3) (2021-06-11)
* Next.js: Fix bug where static pages with dynamic routes and no getStaticProps are not routed correctly @markbrocato
---
#### **Layer0 Packages** - [v3.13.2](https://github.com/moovweb/xdn/releases/tag/v3.13.2) (2021-06-09)
* Add req.connection.encrypted flag (#951) @ierceg
---
#### **Layer0 Packages** - [v3.13.1](https://github.com/moovweb/xdn/releases/tag/v3.13.1) (2021-06-08)
* Improve reliability of certificate activation (#953) @leotoll
* Fix a bug where deployments are marked as failed if the user quits the CLI while waiting for the release to propagate to the nearest global POP (#952) @KaarelKelk
---
#### **Layer0 Developer Console** - [v1.56.8](https://github.com/moovweb/le-deployer/releases/tag/v1.56.8) (2021-06-08)
## 🐛 Bug Fixes
- Added Domain query @MarkusTarn (#1021)
- More mobile-friendly responsiveness fixes - Support form, My Account, others @kevhender (#1019)
---
#### **Layer0 Packages** - [v3.12.2](https://github.com/moovweb/xdn/releases/tag/v3.12.2) (2021-06-07)
* Fix setting headers to array broken in production mode (#941) @ierceg
---
#### **Layer0 Developer Console** - [v1.56.7](https://github.com/moovweb/le-deployer/releases/tag/v1.56.7) (2021-06-07)
## ✨ Enhancements
- Mobile-friendly header/menu and login page @kevhender (#979)
- Added information about 15s delay on server logs @MarkusTarn (#1009)
- Remove nowrap from DateValue @KaarelKelk (#1020)
- Using 1 commit to clone for 1 click deploy @dijs (#1016)
- Fix background of some code tags @kevhender (#1006)
---
#### **Layer0 Packages** - [v3.12.1](https://github.com/moovweb/xdn/releases/tag/v3.12.1) (2021-06-04)
* Next.js: Fix regression in 3.12.0 where deploys fail with a message a… (#945) @markbrocato
---
#### **Layer0 Packages** - [v3.12.0](https://github.com/moovweb/xdn/releases/tag/v3.12.0) (2021-06-04)
* Next.js: Fixes a bug where a statically built homepage is never revalidated. (#944) @markbrocato
* Add connector for nuxt/nitro (#927) @markbrocato
---
#### **Layer0 Packages** - [v3.11.0](https://github.com/moovweb/xdn/releases/tag/v3.11.0) (2021-06-03)
* Log AWS region (#935) @dijs
* XDN-11818 - Improve type annotations (#930) @markbrocato 
* Add new worker metrics (#932) @ierceg 
---
#### **XDN Packages** - [v2.53.3](https://github.com/moovweb/xdn/releases/tag/v2.53.3) (2021-06-02)
* Fix provisioning page may be served on already activated services (#942) @ierceg
---
#### **Layer0 Developer Console** - [v1.56.6](https://github.com/moovweb/le-deployer/releases/tag/v1.56.6) (2021-06-02)
## ✨ Enhancements
- Added option to search for both, server logs and deployment logs. @MarkusTarn (#1012)
- Added statuspage embed code @KaarelKelk (#1014)
## 🐛 Bug Fixes
- Query variable now overrides the selectedRoute from withQueryNavigati… @MarkusTarn (#1000)
---
#### **Layer0 Developer Console** - [v1.56.5](https://github.com/moovweb/le-deployer/releases/tag/v1.56.5) (2021-06-01)
## 🚀 New Features
- feat(BuildSnapshot) Implemented snapshot model [MIGRATION][CF] @KaarelKelk (#959)
## 🐛 Bug Fixes
- Added robots noindex to provisioning page @KaarelKelk (#1004)
- Fixed local env not having RELEASE\_NR env var breaks console @MarkusTarn (#1008)
---
#### **Layer0 Packages** - [v3.10.1](https://github.com/moovweb/xdn/releases/tag/v3.10.1) (2021-05-27)
* Remove console.log from NextRoutes when processing rewrites (#936) @markbrocato
* XDN-11105 - Spartacus - Prefetching Header size issue (reapply #877 to 3.x) (#928) @ierceg
---
#### **Layer0 Developer Console** - [v1.56.4](https://github.com/moovweb/le-deployer/releases/tag/v1.56.4) (2021-05-25)
## ✨ Enhancements
- Removed environment limit for free tier @KaarelKelk (#998)
- Fixed metrics service returning criteria string not parsable @MarkusTarn (#999)
- Add "Copy as cURL" button to requests on full-stack debugger @kevhender (#992)
- Allow unauthenticated Layer0 support ticket form, add reCAPTCHA @kevhender (#990)
- Set min width for MenuItem to be same as Button @dijs (#997)
- Added information about whitelisting domains @dijs (#978)
- Change cert renewal to 40 days @leotoll (#996)
---
#### **Layer0 Developer Console** - [v1.56.3](https://github.com/moovweb/le-deployer/releases/tag/v1.56.3) (2021-05-24)
## ✨ Enhancements
- XDN-11726 - Add tooltips to status codes on Traffic tab @kevhender (#994)
- Change from CWV -> Regular site when deploying @kevhender (#995)
- Add Wildcard support for Layer0 SSL Certificate @Th0masL (#993)
- Fix background color for CWV labels @kevhender (#991)
---
#### **Layer0 Packages** - [v3.10.0](https://github.com/moovweb/xdn/releases/tag/v3.10.0) (2021-05-21)
* XDN-11436 - Next.js support rewrites.has (#915) @markbrocato
* Add edge ping built-in route (#918) @ierceg
---
#### **Layer0 Packages** - [v3.9.0](https://github.com/moovweb/xdn/releases/tag/v3.9.0) (2021-05-20)
* [XDN-9763] Request logging (#868) @ierceg
* [Snyk] Upgrade ts-loader from 8.0.18 to 8.2.0 (#921) @MEGrimshaw
* Always force pass on disabled caching (#924) @ierceg
---
#### **Layer0 Developer Console** - [v1.56.2](https://github.com/moovweb/le-deployer/releases/tag/v1.56.2) (2021-05-20)
## ✨ Enhancements
- Full-stack debugger: Fix fullscreen, auto-pause when messages stop coming @kevhender (#987)
- Correct XDN text for github deploy steps @tristanlee85 (#984)
## 🧰 Maintenance
- [MIGRATION] TLS fixes @leotoll (#980)
---
#### **Layer0 Developer Console** - [v1.56.1](https://github.com/moovweb/le-deployer/releases/tag/v1.56.1) (2021-05-19)
- Temporarily remove recaptcha for help form @kevhender (#986)
---
#### **Layer0 Packages** - [v3.8.1](https://github.com/moovweb/xdn/releases/tag/v3.8.1) (2021-05-18)
* XDN-11658 - Routers that use #dir and build on windows can fail in th… (#920) @markbrocato
---
#### **XDN Packages** - [v2.53.2](https://github.com/moovweb/xdn/releases/tag/v2.53.2) (2021-05-18)
* Always force pass on disabled caching (#922) @ierceg
---
#### **Layer0 Developer Console** - [v1.55.0](https://github.com/moovweb/le-deployer/releases/tag/v1.55.0) (2021-05-17)
## 🚀 New Features
- Spotlight Search @MarkusTarn (#901)
---
#### **Layer0 Packages** - [v3.8.0](https://github.com/moovweb/xdn/releases/tag/v3.8.0) (2021-05-14)
* Allow setting of a wider set of CDN headers through the router (#917) @ierceg
---
#### **Layer0 Packages** - [v3.7.0](https://github.com/moovweb/xdn/releases/tag/v3.7.0) (2021-05-14)
* Xdn 11512 error messaging when route entry isn't valid is not helpful mark brocato (#911) @markbrocato
* XDN-11530 - Write build manifest after successful deployment to .layer0 (#912) @markbrocato
* XDN-11522 - Support specifying token via an env var (#913) @markbrocato
---
#### **Layer0 Developer Console** - [v1.54.6](https://github.com/moovweb/le-deployer/releases/tag/v1.54.6) (2021-05-14)
## ✨ Enhancements
- Router info clickable @MarkusTarn (#955)
- Use traffic percentage instead of route percentage for donut chart @kevhender (#957)
- Improve TLS @leotoll (#954)
## 🐛  Bug Fixes
- Date/time display fixes @kevhender (#922)
- One click deploy fixes @dijs (#960)
---
#### **Layer0 Packages** - [v3.6.1](https://github.com/moovweb/xdn/releases/tag/v3.6.1) (2021-05-13)
* Fix bad default route JSON (#914) @ierceg
* Next.js: Fix TypeError: Cannot read property 'static' of undefined when running Layer0 in dev without router.use(nextRoutes) (#909) @markbrocato
---
#### **Layer0 Packages** - [v3.6.0](https://github.com/moovweb/xdn/releases/tag/v3.6.0) (2021-05-10)
* Allow transforming of requests and responses when using renderWithApp. (#908) @markbrocato
* [Snyk] Upgrade: @babel/parser, @babel/traverse (#906) @MEGrimshaw
---
#### **Layer0 Packages** - [v3.5.1](https://github.com/moovweb/xdn/releases/tag/v3.5.1) (2021-05-07)
* Add Node version check to CLI (#905) @ierceg
* Remove dependency on fs.watch (#902) @ierceg
---
#### **Layer0 Packages** - [v3.5.0](https://github.com/moovweb/xdn/releases/tag/v3.5.0) (2021-05-06)
* XDN-11397 - Support Next.js beforeFiles, afterFiles, and fallback rew… (#903) @markbrocato
* Update the engines property for @layer0/cli to Node 14. (#901) @markbrocato
---
#### **Layer0 Developer Console** - [v1.54.5](https://github.com/moovweb/le-deployer/releases/tag/v1.54.5) (2021-05-05)
## 🐛 Bug Fixes
- Notificaiton fixes @MarkusTarn (#953)
---
#### **Layer0 Packages** - [v3.4.0](https://github.com/moovweb/xdn/releases/tag/v3.4.0) (2021-05-04)
* Update the first byte timeout limit algo to fit 60s practical limit (#879) @ierceg
* build(deps): bump ssri from 6.0.1 to 6.0.2 (#870) @dependabot
* [Snyk] Security upgrade next from 10.0.7 to 10.2.0 (#890) @MEGrimshaw
* [Snyk] Security upgrade next from 10.0.9 to 10.2.0 (#889) @MEGrimshaw
* [Snyk] Security upgrade next from 10.0.7 to 10.2.0 (#893) @MEGrimshaw
* [Snyk] Security upgrade lodash from 4.17.19 to 4.17.21 (#896) @MEGrimshaw
* [Snyk] Security upgrade lodash from 4.17.19 to 4.17.21 (#899) @MEGrimshaw
* Fix cli use workspaces (#900) @markbrocato
* Use ESBuild for bundling the router, config, and browser assets to improve build times. (#894) @markbrocato
* fix(CLI): Ctrl+C not exiting in early deploy phases (before "deploying...") (#891) @adrien-k
---
#### **Layer0 Developer Console** - [v1.54.4](https://github.com/moovweb/le-deployer/releases/tag/v1.54.4) (2021-05-04)
## ✨ Enhancements
- feat(Staff) Added teams to accounts table @KaarelKelk (#950)
- fix empty tooltip @KaarelKelk (#951)
## 🐛 Bug Fixes
- Show more deployments should keep the scroll position @kevhender (#952)
- Alerts multiple emails @MarkusTarn (#949)
- Made rendering of really long lines better @MarkusTarn (#947)
---
#### **Layer0 Packages** - [v3.3.1](https://github.com/moovweb/xdn/releases/tag/v3.3.1) (2021-05-03)
* Fix an bug that occurs when lerna.json does not have a packages field. (#897) @markbrocato
* chore(build-lambda): increase deploy-lambda http timeout (#887) @adrien-k
---
#### **Layer0 Developer Console** - [v1.54.3](https://github.com/moovweb/le-deployer/releases/tag/v1.54.3) (2021-04-30)
## 🚀 New Features
- XDN-11228 - Make CWV filters default to "mobile" device type @kevhender (#938)
- XDN-11222 - Make it more obvious when table has more columns @kevhender (#936)
- XDN-11236 - Add a summation row at the top of the traffic table @kevhender (#941)
## ✨ Enhancements
- Change upgrade flow @ierceg (#946)
- chore(Security): add CSP and HSTS headers @adrien-k (#944)
## 🐛 Bug Fixes
- Fix CWV threshold lines @kevhender (#935)
- XDN-11212 - Fix sorting for traffic routes to account for 0s @kevhender (#937)
- Hide the CWV percentage change when not enough data @kevhender (#940)
- XDN-11221 - Include offline builds when showing deployments on graphs @kevhender (#945)
---
#### **Layer0 Developer Console** - [v1.54.1](https://github.com/moovweb/le-deployer/releases/tag/v1.54.1) (2021-04-29)
## 🐛 Bug Fixes
- Fix site settings conflict for double ssl and deploytoken @leotoll (#939)
## ✨ Enhancements
- chore(RouterInfoInConsole) Implemented useMemo on matching routes @MarkusTarn (#942)
- chore(RouterInfoInConsole) Significally reduced the number of renderings @MarkusTarn (#934)
- feat(LargeStatic): allow builds up to 1GB compressed @adrien-k (#933)
---
#### **Layer0 Packages** - [v2.53.1](https://github.com/moovweb/xdn/releases/tag/v2.53.1) (2021-04-28)
- (2.x) [XDN-10308] Use webpack-merge for applying config options (#865) @tristanlee85
---
#### **Layer0 Packages** - [v3.3.0](https://github.com/moovweb/xdn/releases/tag/v3.3.0) (2021-04-27)
- (3.x) [XDN-10308] Use webpack-merge for applying config options (#864) @tristanlee85
- Improve terminal output and coloring for layer0 run. (#883) @markbrocato
- Nuxt.js support custom dynamic 404 pages. (#886) @markbrocato
- Nuxt: Fix a bug where custom 404 pages not being show in dev and prod… (#882) @markbrocato
- XDN-11095 - Nuxt.js: Fix bug where 404.html isn't rendered as the fallback. (#878) @markbrocato
- Fix status code and message not sent on proxy to static (#880) @ierceg
- Relax JSON validation on cache data (#875) @ierceg
---
#### **Layer0 Packages** - [v2.53.0](https://github.com/moovweb/xdn/releases/tag/v2.53.0) (2021-04-22)
- Spartacus - Prefetching Header size issue (#877)
---
#### **Layer0 Developer Console** - [v1.54.0](https://github.com/moovweb/le-deployer/releases/tag/v1.54.0) (2021-04-26)
## ✨ Enhancements
- feat(Sessions) move all sessions to db store @KaarelKelk (#925)
- XDN-11049 - Fix unexpected back button behavior @kevhender (#927)
## 🧰 Maintenance
- Skip maintenance on sessions migration @KaarelKelk (#931)
- Add load user gtm event @leotoll (#921)
- chore(Release): reduce maintenance window @adrien-k (#928)
- fix(RouterInConsole) Added min XDN version @MarkusTarn (#926)
- fix tracking tests for arrays @leotoll (#929)
---
#### **Layer0 Packages** - [v3.2.0](https://github.com/moovweb/xdn/releases/tag/v3.2.0) (2021-04-22)
- feat(CLI): run initialize and build/zip in parallel (#863) @adrien-k
- CLI support for monorepos (#876) @leotoll
- Add router introspection. (#476) @markbrocato
- Clean up some brand naming. (#872) @markbrocato
- fix(devtools): allow enabling devtools (#873) @adrien-k
- Downgrade @types/cheerio to 0.22.18 (#871) @tristanlee85
- Return an error code when the connector declared in layer0.config.js … (#869) @markbrocato
---
#### **Layer0 Developer Console** - [v1.53.0](https://github.com/moovweb/le-deployer/releases/tag/v1.53.0) (2021-04-22)
✨ Enhancements
- Internal API: GET /internal/v1/aws-accounts @adrien-k (#920)
🐛 Bug Fixes
- Replace moovweb.com references left in e-mails @adrien-k (#923)
---
#### **Layer0 Developer Console** - [v1.52.1](https://github.com/moovweb/le-deployer/releases/tag/v1.52.1) (2021-04-21)
✨ Enhancements
- Handle empty CWV stats better @dijs (#878)
- updates to seeds and maintenance template @KaarelKelk (#918)
- Added redis service to test-with-integration @KaarelKelk (#906)
🐛 Bug Fixes
- Publish changelog to correct repo @tristanlee85 (#917)
- Fix selection of cache hit/miss filters for CWV @kevhender (#915)
- feat(RouterInfoInConsole): Added router location to router info @MarkusTarn (#914)
- Fix overview CWV tab for when current period has no data @kevhender (#916)
---
#### **Layer0 Developer Console** - [v1.52.1](https://github.com/moovweb/le-deployer/releases/tag/v1.52.1) (2021-04-21)
✨ Enhancements
- Handle empty CWV stats better @dijs (#878)
- updates to seeds and maintenance template @KaarelKelk (#918)
- Added redis service to test-with-integration @KaarelKelk (#906)
🐛 Bug Fixes
- Publish changelog to correct repo @tristanlee85 (#917)
- Fix selection of cache hit/miss filters for CWV @kevhender (#915)
- feat(RouterInfoInConsole): Added router location to router info @MarkusTarn (#914)
- Fix overview CWV tab for when current period has no data @kevhender (#916)
---
#### **Layer0 Developer Console** - [v1.52.0](https://github.com/moovweb/le-deployer/releases/tag/v1.52.0) (2021-04-20)
🚀 New Features
- The router code is now displayed in the site and deployment views with overlaid caching stats. @MarkusTarn (#841)
- The new alerts feature allows users to subscribe to email alerts for caching, core web vitals, deployments, and more. @MarkusTarn (#818)
✨ Enhancements
- Renaming updates slug and subdomains @adrien-k (#896)
- Preserve overridden metrics values @KaarelKelk (#907)
- Show deployments and cache purges in all graphs @kevhender (#892)
🐛 Bug Fixes
- Show correct env name instead of production on current production deployment card. @KaarelKelk (#911)
- Fix some brand naming. @markbrocato (#909)
---
#### **Layer0 Developer Console** - [v1.51.1](https://github.com/moovweb/le-deployer/releases/tag/v1.51.1) (2021-04-19)
- L0-10892 - CWV tab stats should update when filters are changed @kevhender (#900)
- L0-10816 - Force refresh when user changes dark mode setting @kevhender (#903)
---
#### **Layer0 Developer Console** - [v1.51.0](https://github.com/moovweb/le-deployer/releases/tag/v1.51.0) (2021-04-19)
- feat(LambdaJob) store logs in redis until archive (Step 1) @KaarelKelk (#899)
- [MIGRATION SKIP-MAINTENANCE] feat(Starter): set team edge region separately @adrien-k (#890)
- fix(Activity) Fixed showing API cache purges @KaarelKelk (#904)
- fix(Layer0) renamed version on build overview @KaarelKelk (#902)
- feat(RDNSupport): change logo and layout @adrien-k (#898)
- Delete button text fix @leotoll (#895)
- add version to deploy tracking @leotoll (#897)
- Fixed scope on xdn => layer0 package @KaarelKelk (#894)
---
#### **Layer0 Developer Console** - [v1.50.1](https://github.com/moovweb/le-deployer/releases/tag/v1.50.1) (2021-04-13)
- fix(Overview) fixed race conditions for chart data @KaarelKelk (#893)
---
#### **Layer0 Developer Console** - [v1.50.0](https://github.com/moovweb/le-deployer/releases/tag/v1.50.0) (2021-04-13)
- fix(CI/ecs-utils): show logs on failure @adrien-k (#891)
- feat(Staff): layer0/moovforge emails flagged internal @adrien-k (#888)
- docs: Release operations @adrien-k (#889)
- Fixing layout shift of site overview page @dijs (#881)
- [GO-LIVE] Rebrand to app.layer0.co console @adrien-k (#828)
- chore(deps): bump y18n from 3.2.1 to 3.2.2 @dependabot (#864)
- feat(Admin/Teams): filter personal teams out @adrien-k (#887)
- Restrict domains to 64 chars @leotoll (#886)
- Default to OS dark setting @dijs (#885)
- Removed localhost from site cards @dijs (#874)
- Updated link to docs @dijs (#873)
- Added stage env to CF and updated comments/readme about sandbox to in… @KaarelKelk (#884)
- Added support for staging domains @Th0masL (#869)
- Push LD to stage on push/merge to master @KaarelKelk (#883)
---
#### **Layer0 Packages** - [v3.0.3](https://github.com/moovweb/xdn/releases/tag/v3.0.3) (2021-04-13)
- [Snyk] Upgrade webpack from 5.26.3 to 5.27.0 (#825) @MEGrimshaw
- feat(CLI) Added warning message about newer package version (#829) @KaarelKelk
- [Snyk] Security upgrade next from 10.0.6 to 10.0.7 (#836) @MEGrimshaw
- [Snyk] Security upgrade next from 10.0.6 to 10.0.7 (#835) @MEGrimshaw
- [L0-10773] Update org name for layer0-docs publish action (#832) @tristanlee85
- [Snyk] Security upgrade bootstrap from 4.2.1 to 4.3.1 (#823) @MEGrimshaw
---
#### **Layer0 Packages** - [v3.0.2](https://github.com/moovweb/xdn/releases/tag/v3.0.2) (2021-04-13)
- feat(Devtools/branding): change logo to Layer0 (#831) @adrien-k
---
#### **Layer0 Packages** - [v3.0.1](https://github.com/moovweb/xdn/releases/tag/v3.0.1) (2021-04-12)
- Allow surrogate key to be set through the router (#833) @ierceg
---
#### **Layer0 Packages** - [v3.0.0](https://github.com/moovweb/xdn/releases/tag/v3.0.0) (2021-04-09)
- Breaking change in v3: disable watching attribute changes when using @xdn/prefetch watchLinks (#824) @ierceg
---
#### **Layer0 Developer Console** - [v1.49.4](https://github.com/moovweb/le-deployer/releases/tag/v1.49.4) (2021-04-07)
- L0-10507 - Improve the release notes template @markbrocato (#880)
- Make caa valid when empty @leotoll (#879)
---
#### **Layer0 Developer Console** - [v1.49.3](https://github.com/moovweb/le-deployer/releases/tag/v1.49.3) (2021-04-06)
- [MIGRATION SKIP-MAINTENANCE] chore(GithubDeploy): remove non-encrypt tokens from DB (#875) @adrien-k
---
#### **Layer0 Developer Console** - [v1.49.2](https://github.com/layer0/le-deployer/releases/tag/v1.49.2) (2021-04-05)
- Added back default value for context (#877) @KaarelKelk
---
#### **Layer0 Developer Console** - [v1.49.1](https://github.com/layer0/le-deployer/releases/tag/v1.49.1) (2021-04-05)
- fix(CVW) Fixed default selected host on CWV page (#876) @KaarelKelk
---
#### **Layer0 Developer Console** - [v1.49.0](https://github.com/layer0/le-deployer/releases/tag/v1.49.0) (2021-04-05)
- fix(GithubDeploy): Github race condition + token encryption (#868) @adrien-k
---
#### **Layer0 Developer Console** - [v1.48.2](https://github.com/layer0/le-deployer/releases/tag/v1.48.2) (2021-04-03)
- Added timeframe to hosts endpoint (#871) @dijs
- CWV Filter fix (#867) @dijs
- Core Web Vitals Tabs host fix (#870) @dijs
---
#### **Layer0 Packages** - [v2.52.0](https://github.com/layer0/layer0/releases/tag/v2.52.0) (2021-04-09)
- (2.x) [L0-10692] Make prefetch observer configurable to exclude watching attribute changes (#821) @tristanlee85
---
#### **Layer0 Packages** - [v2.51.0](https://github.com/layer0/layer0/releases/tag/v2.51.0) (2021-04-09)
- Fix bundle size (#819) @ierceg
- Add label to routeJson for static files (#799) @leotoll
- [Snyk] Upgrade path-to-regexp from 6.1.0 to 6.2.0 (#814) @MEGrimshaw
- [Snyk] Upgrade ts-loader from 8.0.17 to 8.0.18 (#816) @MEGrimshaw
- [Snyk] Upgrade webpack from 5.26.2 to 5.26.3 (#817) @MEGrimshaw
- [Snyk] Upgrade tcp-port-used from 1.0.1 to 1.0.2 (#815) @MEGrimshaw
- [L0-10331] Correct directory name for default Gatsby files (#812) @tristanlee85
- [Snyk] Upgrade globby from 11.0.1 to 11.0.2 (#808) @MEGrimshaw
- [Snyk] Upgrade webpack from 5.24.1 to 5.26.2 (#806) @MEGrimshaw
- [Snyk] Upgrade next from 10.0.8 to 10.0.9 (#805) @MEGrimshaw
- [Snyk] Upgrade pino from 6.11.0 to 6.11.2 (#807) @MEGrimshaw
- feat(Prerender) Added lowerConcurrency flip when server is returning … (#782) @KaarelKelk
---
#### **Layer0 Packages** - [v2.50.0](https://github.com/layer0/layer0/releases/tag/v2.50.0) (2021-04-07)
- feat(edge-redirect): allow full url as 'from' (#798) @adrien-k
- Deploy XDN lambdas to stage environment (#809) @KaarelKelk
- [Snyk] Upgrade @nuxt/core from 2.14.12 to 2.15.3 (#795) @MEGrimshaw
- Bump y18n from 4.0.0 to 4.0.1 in /packages/build-lambda (#793) @dependabot
- [Snyk] Upgrade next from 10.0.7 to 10.0.8 (#796) @MEGrimshaw
- Bump y18n from 4.0.0 to 4.0.1 in /packages/cli (#792) @dependabot
- [Snyk] Upgrade bootstrap from 4.2.1 to 4.6.0 (#777) @MEGrimshaw
- [Snyk] Upgrade webpack from 5.21.2 to 5.24.1 (#759) @MEGrimshaw
---
#### **Layer0 Packages** - [v2.49.4](https://github.com/layer0/layer0/releases/tag/v2.49.4) (2021-04-02)
- L0-10553 - Next.js: Homepage with getStaticProps fails to serve json… (#801) @markbrocato
---
#### **Layer0 Packages** - [v2.49.3](https://github.com/layer0/layer0/releases/tag/v2.49.3) (2021-04-01)
- Fix issue compiling TypeScript routes file when TypeScript errors exi… (#800) @markbrocato
- Use Node12 with Layer0 v2 (#794) @ierceg
---
#### **Layer0 Developer Console** - [v1.48.1](https://github.com/layer0/le-deployer/releases/tag/v1.48.1) (2021-04-01)
- fix deploy github route (#866) @adrien-k
---
#### **Layer0 Developer Console** - [v1.48.0](https://github.com/layer0/le-deployer/releases/tag/v1.48.0) (2021-04-01)
- feat(edge-redirect): allow URL as 'from' (#865) @adrien-k
- [MIGRATION SKIP-MAINTENANCE] Add Deploy to Layer0 Button (#626) @dijs
---
#### **Layer0 Packages** - [v2.49.2](https://github.com/layer0/layer0/releases/tag/v2.49.2) (2021-03-31)
- Bump y18n from 4.0.0 to 4.0.1 (#791) @dependabot
- [Snyk] Upgrade i18next from 19.8.4 to 19.9.1 (#778) @MEGrimshaw
- [Snyk] Upgrade lodash from 4.17.19 to 4.17.21 (#776) @MEGrimshaw
- [Snyk] Upgrade ts-loader from 8.0.14 to 8.0.17 (#774) @MEGrimshaw
- [Snyk] Upgrade ajv from 6.12.3 to 6.12.6 (#775) @MEGrimshaw
- [Snyk] Upgrade rxjs from 6.5.5 to 6.6.6 (#779) @MEGrimshaw
- [Snyk] Upgrade mime-types from 2.1.27 to 2.1.29 (#780) @MEGrimshaw
- Fix default redirect response body (#790) @ierceg
---
#### **Layer0 Developer Console** - [v1.47.2](https://github.com/layer0/le-deployer/releases/tag/v1.47.2) (2021-03-31)
- Fix error on CLS tab in Core Web Vitals page (#863) @markbrocato
---
#### **Layer0 Packages** - [v2.49.1](https://github.com/layer0/layer0/releases/tag/v2.49.1) (2021-03-31)
- Add Ember Fastboot detection to layer0 init. (#789) @markbrocato
---
#### **Layer0 Packages** - [v2.49.0](https://github.com/layer0/layer0/releases/tag/v2.49.0) (2021-03-31)
- L0-10455 - Ember Fastboot Connector (#788) @markbrocato
- Log the size of the generated VCL code (#787) @ierceg
- Treat empty excludeAllQueryParametersExcept as excludeAllQueryParameters (#786) @ierceg
---
#### **Layer0 Developer Console** - [v1.47.1](https://github.com/layer0/le-deployer/releases/tag/v1.47.1) (2021-03-31)
- More conspicuous selection model for Traffic tab routes table (#860) @kevhender
- Show tooltip on all charts when hovering on one (#855) @kevhender
- Clean up param misses load message, revert ILS sort (#861) @kevhender
- L0-10384 - Fix z-index issues on CWV page (#862) @kevhender
- Fix color of radios (#857) @kevhender
- L0-10380 - Fix cache hit rate chart tooltip and data dropoff (#852) @kevhender
- L0-10378 - Add sorting for ILS table (#851) @kevhender
- L0-10377 - A loading message to query param misses table (#853) @kevhender
- L0-10376 - Scroll to top when changing routes (#854) @kevhender
- Change Traffic Trend chart legend to be checkboxes (#856) @kevhender
- Change duration label to always be "28 days" (#858) @kevhender
---
#### **Layer0 Developer Console** - [v1.47.0](https://github.com/layer0/le-deployer/releases/tag/v1.47.0) (2021-03-29)
- Fix default export for missingDataUtils (#850) @KaarelKelk
- Delay prerendering after build (#840) @KaarelKelk
- fix(CI): docker cache (#839) @adrien-k
- Implemented new rum endpoint for top hosts (#800) @KaarelKelk
- Use full cname validation (#849) @leotoll
- Add traffic tab to environment page (#832) @kevhender
- Segment pardot attribution fix + mimemagic version update (#848) @leotoll
- Standardize the look of cancel buttonsin dialogs and improve their lo… (#843) @markbrocato
- Removed weighted % and replaced with traffic (#842) @KaarelKelk
- fix(Activity) Fixed showing "show all" when there's all records shown (#845) @KaarelKelk
- Fixed environment name on airbrake (#844) @KaarelKelk
---
#### **Layer0 Packages** - [v2.48.4](https://github.com/layer0/layer0/releases/tag/v2.48.4) (2021-03-25)
- Add route JSON for fallback to routes injected by Layer0 (#784) @ierceg
---
#### **Layer0 Packages** - [v2.48.3](https://github.com/layer0/layer0/releases/tag/v2.48.3) (2021-03-25)
- Set HSTS header conditionally (#783) @ierceg
- Enable redirects following for WebSockets (#771) @KaarelKelk
---
#### **Layer0 Developer Console** - [v1.45.0](https://github.com/layer0/le-deployer/releases/tag/v1.45.0) (2021-03-24)
- Navigation Fixes (#836) @dijs
- Wrap RUM configuration instructions in a card (#838) @kevhender
- Use subheading for CWV overview card (#835) @kevhender
- Fix closing of purging window (#834) @kevhender
---
#### **Layer0 Packages** - [v2.48.2](https://github.com/layer0/layer0/releases/tag/v2.48.2) (2021-03-24)
- [Snyk] Upgrade next from 10.0.6 to 10.0.7 (#756) @MEGrimshaw
- [Snyk] Upgrade babel-loader from 8.1.0 to 8.2.2 (#760) @MEGrimshaw
- L0-10101 - Next plugins: Only return functions when passed functions. (#773) @markbrocato
- L0-10098 - Exclude @layer0/rum from layer0 use command. (#772) @markbrocato
---
#### **Layer0 Developer Console** - [v1.44.2](https://github.com/layer0/le-deployer/releases/tag/v1.44.2) (2021-03-23)
- Added check for environment (#833) @KaarelKelk
---
#### **Layer0 Developer Console** - [v1.44.1](https://github.com/layer0/le-deployer/releases/tag/v1.44.1) (2021-03-23)
- Query navigation state is now saved in context (#831) @dijs
- CWV tracking + small fixes (#821) @leotoll
---
#### **Layer0 Developer Console** - [v1.43.2](https://github.com/layer0/le-deployer/releases/tag/v1.43.2) (2021-03-19)
- Fix crash on Admin page (#820) @leotoll
---
#### **Layer0 Packages** - [v2.48.1](https://github.com/layer0/layer0/releases/tag/v2.48.1) (2021-03-19)
- L0-10012 - Fix error when running layer0 dev before initial nuxt build (#770) @markbrocato
---
#### **Layer0 Developer Console** - [v1.43.2](https://github.com/layer0/le-deployer/releases/tag/v1.43.2) (2021-03-19)
- Fix crash on Admin page (#820) @leotoll
---
#### **Layer0 Developer Console** - [v1.43.1](https://github.com/layer0/le-deployer/releases/tag/v1.43.1) (2021-03-19)
- Domain caa validation fix (#820) @leotoll
---
#### **Layer0 Packages** - [v2.48.0](https://github.com/layer0/layer0/releases/tag/v2.48.0) (2021-03-19)
- L0-9946 - Next.js: Allow withLayer0 and withServiceWorker to accept fu… (#764) @markbrocato
- Increased build-lambda-timeout (#751) @KaarelKelk
- L0-9941 - Next.js: Support optional catch-all parameters (#763) @markbrocato
- Ignore routes with headers and cookie matching in the cache manifest (#765) @ierceg
---
#### **Layer0 Packages** - [v2.47.2](https://github.com/layer0/layer0/releases/tag/v2.47.2) (2021-03-19)
- _Really_ fix req and resp cookie comparison not ignoring cookie attributes (#768) @ierceg
- Fix req and resp cookie comparison not ignoring cookie attributes (#767) @ierceg
---
#### **Layer0 Packages** - [v2.47.1](https://github.com/layer0/layer0/releases/tag/v2.47.1) (2021-03-19)
- Fix director names outside of Virginia US shielding (#766) @ierceg
- Enable back starter tests (#762) @ierceg
---
#### **Layer0 Packages** - [v2.47.0](https://github.com/layer0/layer0/releases/tag/v2.47.0) (2021-03-17)
- Fix gti prerendering (#754) @KaarelKelk
- Add debug caching status (#757) @ierceg
- Retry to get user edge config until build lambda times out (#742) @ierceg
- Porting/cherry-picking/adapting code from v3 branch to v2 (#717) @ierceg
- Bump elliptic from 6.5.3 to 6.5.4 in /integration-tests/edge (#748) @dependabot
- [Snyk] Upgrade react-merge-refs from 1.0.0 to 1.1.0 (#735) @MEGrimshaw
- [Snyk] Upgrade webpack from 5.18.0 to 5.21.2 (#738) @MEGrimshaw
- [Snyk] Upgrade pino from 6.5.1 to 6.11.0 (#737) @MEGrimshaw
- [Snyk] Upgrade uuid from 8.3.0 to 8.3.2 (#739) @MEGrimshaw
- Moved internal backends to VCL (#716) @KaarelKelk
---
#### **Layer0 Developer Console** - [v1.43.0](https://github.com/layer0/le-deployer/releases/tag/v1.43.0) (2021-03-17)
- [MIGRATION] Time Preferences (#799) @dijs
- Skip maintenance mode for dark mode (#813) @dijs
- Clear error boundaries after navigation. (#812) @markbrocato
- [MIGRATION] Dark Mode (#801) @dijs
- Fix % rounding display and staff mode error when no CWV data (#807) @kevhender
- Remove viewport (#810) @leotoll
---
#### **Layer0 Developer Console** - [v1.42.4](https://github.com/layer0/le-deployer/releases/tag/v1.42.4) (2021-03-15)
- fix team search (#811) @adrien-k
---
#### **Layer0 Developer Console** - [v1.42.3](https://github.com/layer0/le-deployer/releases/tag/v1.42.3) (2021-03-15)
- Fix acme challenge typo (#808) @leotoll
- DNS validation fix (#809) @leotoll
---
#### **Layer0 Developer Console** - [v1.42.2](https://github.com/layer0/le-deployer/releases/tag/v1.42.2) (2021-03-15)
- Revert back: New UX for RUM filters - L0-9451, L0-9665, L0-9450… (#806) @adrien-k
---
#### **Layer0 Developer Console** - [v1.42.1](https://github.com/layer0/le-deployer/releases/tag/v1.42.1) (2021-03-15)
- fix(Build) remove use of PageContext (#805) @adrien-k
---
#### **Layer0 Developer Console** - [v1.41.2](https://github.com/layer0/le-deployer/releases/tag/v1.41.2) (2021-03-10)
- Fixed ordering purge history. (#788) @KaarelKelk
- Visual Improvements (#787) @dijs
---
#### **Layer0 Packages** - [v2.46.11](https://github.com/layer0/layer0/releases/tag/v2.46.11) (2021-03-09)
- fix(Devtools): edge hit flag ignoring re-entering x-xdn-t values (#745) @adrien-k
- Changelog script updates for cleaner output and entry title (#746) @tristanlee85
- L0-9547 - Fix issue with matching excluded paths with serveStatic on… (#747) @markbrocato
- Fix for updating cert with fewer domains (#740) @leotoll
---
#### **Layer0 Developer Console** - [v1.41.0](https://github.com/layer0/le-deployer/releases/tag/v1.41.0) (2021-03-09)
- RUM v1 (#655) @kevhender
- Ssl get old domains view + rename site ui tweak (#755) @leotoll
- increase metrics client timeout to 5mins (#747) @KaarelKelk
---
#### **Layer0 Packages** - [v2.46.10](https://github.com/layer0/layer0/releases/tag/v2.46.10) (2021-03-03)
- Fixed a bug where the Layer0 CLI doesn't output the server URL on startu… (#743) @markbrocato
- fix(UserLambdaLogStreamer): Moved end user lambda log stream to deplo… (#741) @MarkusTarn
---
#### **Layer0 Packages** - [v2.46.9](https://github.com/layer0/layer0/releases/tag/v2.46.9) (2021-02-26)
- L0-8956 - [@layer0/starter] service-worker.js: “process” is not defined… (#734) @markbrocato
- Adds typings for @layer0/devtools
---
#### **Layer0 Packages** - [v2.46.7](https://github.com/layer0/layer0/releases/tag/v2.46.7) (2021-02-23)
- fix(StremingUserLambdaLogs) Added try catch for ensureAppStarted to i… (#726) @MarkusTarn
---
#### **Layer0 Packages** - [v2.46.6](https://github.com/layer0/layer0/releases/tag/v2.46.6) (2021-02-23)
- L0-8963 - @layer0/vue-storefront lambda fails to start (#731) @markbrocato
- L0-8955 - Fix layer0 init for frontity (#730) @markbrocato
---
#### **Layer0 Packages** - [v2.46.4](https://github.com/layer0/layer0/releases/tag/v2.46.4) (2021-02-18)
- Validate Nuxt dependencies on build (#714) @tristanlee85
---
#### **Layer0 Packages** - [v2.46.3](https://github.com/layer0/layer0/releases/tag/v2.46.3) (2021-02-17)
- L0-8410 - Suggest users go to the forums to get help when a deployme… (#729) @markbrocato
---
#### **Layer0 Packages** - [v2.46.2](https://github.com/layer0/layer0/releases/tag/v2.46.2) (2021-02-17)
- Add service worker and prefetch support to @layer0/frontity. (#727) @markbrocato
- Fix regression that caused --site option to be ignored when deploying. (#728) @markbrocato
---
#### **Layer0 Packages** - [v2.46.1](https://github.com/layer0/layer0/releases/tag/v2.46.1) (2021-02-16)
- Improve support for Webpack 4 and 5 on Next.js (#722) @markbrocato
---
#### **Layer0 Packages** - [v2.46.0](https://github.com/layer0/layer0/releases/tag/v2.46.0) (2021-02-16)
- L0-8788 - Provide a connector for frontity (#725) @markbrocato
---
#### **Layer0 Packages** - [v2.45.0](https://github.com/layer0/layer0/releases/tag/v2.45.0) (2021-02-11)
- L0-8749 - TypeError: prompts is not a function (#719) @markbrocato
- L0-8205_Capture-console-output-of-user-lambda-during-deployment-and-prerendering-in-build-logs_Markus-Tarn (#713) @MarkusTarn
---
#### **Layer0 Packages** - [v2.44.2](https://github.com/layer0/layer0/releases/tag/v2.44.2) (2021-02-09)
- Add encoding as a dependency of @layer0/next so that create-next-app wor… (#715) @markbrocato
---
#### **Layer0 Packages** - [v2.44.0](https://github.com/layer0/layer0/releases/tag/v2.44.0) (2021-02-08)
- L0-8466 - Add @layer0/starter connector (#702) @markbrocato
---
#### **Layer0 Packages** - [v2.44.0](https://github.com/layer0/layer0/releases/tag/v2.44.0) (2021-02-08)
- L0-8466 - Add @layer0/starter connector (#702) @markbrocato
---
#### **Layer0 Packages** - [v2.43.0](https://github.com/layer0/layer0/releases/tag/v2.43.0) (2021-02-05)
- L0-8650 - Add --disable-permanent-assets deploy option (#710) @markbrocato
- Prerender top (#620) @KaarelKelk
---
#### **Layer0 Packages** - [v2.42.1](https://github.com/layer0/layer0/releases/tag/v2.42.1) (2021-02-04)
- Make NextRoutes.render404 public. (#709) @markbrocato
- Add Webpack 5 support to Next.js apps. (#708) @markbrocato
---
#### **Layer0 Packages** - [v2.42.0](https://github.com/layer0/layer0/releases/tag/v2.42.0) (2021-02-03)
- tests(ConsoleRedirect/ForwardQS): enable integration test (#687) @adrien-k
- feat: CLI/layer0 env pull (#700) @adrien-k
- Add xdn_eid cookie and related RUM server timings (#704) @ierceg
- fix(BrokenSnapshot): Added missing json.escape() (#705) @MarkusTarn
- L0-6660_Do-not-log-to-s3-access-logs-on-free-tier_Markus-Tarn (#688) @MarkusTarn
- L0-8464_Build-fails-schema-validation-when-setting-sources-in-layer0configjs_Markus-Tarn (#703) @MarkusTarn
---
#### **Layer0 Packages** - [v2.41.1](https://github.com/layer0/layer0/releases/tag/v2.41.1) (2021-01-29)
- Next.js rewrites: Don't add additional route to rewrite json data URLs. (#698) @markbrocato
- Don't flush on Layer0 version upgrade (#699) @ierceg
---
#### **Layer0 Packages** - [v2.41.0](https://github.com/layer0/layer0/releases/tag/v2.41.0) (2021-01-25)
- L0-8397 - Add support for Next.js running in an nx monorepo (#695) @markbrocato
- fix(devtools/style): isolate style a bit more (#692) @adrien-k
---
#### **Layer0 Packages** - [v2.40.2](https://github.com/layer0/layer0/releases/tag/untagged-cd7d16304b488fbdc279) (2021-01-21)
- Fix bug in url logging where field was not escaped (#694) @phdunham
- Don't populate geo/UA headers when behind edge (#693) @ierceg
---
#### **Layer0 Packages** - [v2.40.1](https://github.com/layer0/layer0/releases/tag/v2.40.1) (2021-01-18)
- Add image optimizer (#686) @markbrocato
- Copy over includeFiles and nodeModules before loading the router at b… (#689) @markbrocato
- Preserve colors in output when running "layer0 dev" (#690) @markbrocato
---
#### **Layer0 Packages** - [v2.40.0](https://github.com/layer0/layer0/releases/tag/v2.40.0) (2021-01-13)
- feat(ConsoleRedirect): trim qs option + match with sorted qs (#682) @adrien-k
---
#### **Layer0 Packages** - [v2.39.3](https://github.com/layer0/layer0/releases/tag/v2.39.3) (2021-01-11)
- bump version (#685) @KaarelKelk
- fix(Axios) Fix failing deploymnts due to maxBodyLength (#684) @KaarelKelk
---
#### **Layer0 Packages** - [v2.39.2](https://github.com/layer0/layer0/releases/tag/v2.39.2) (2021-01-11)
- L0-8150 - Wrong route being run when proxy is used with path and tra… (#683) @markbrocato
---
#### **Layer0 Packages** - [v2.39.1](https://github.com/layer0/layer0/releases/tag/v2.39.1) (2021-01-11)
- fix(Build): double logs on build fail + external messages (#681) @adrien-k
---
#### **Layer0 Packages** - [v2.39.0](https://github.com/layer0/layer0/releases/tag/v2.39.0) (2021-01-08)
- Add support for nuxt generate and static pages which fall back to SSR. (#671) @markbrocato
---
#### **Layer0 Packages** - [v2.38.1](https://github.com/layer0/layer0/releases/tag/v2.38.1) (2021-01-08)
- Fixing VSF (#676) @dijs
---
#### **Layer0 Packages** - [v2.38.0](https://github.com/layer0/layer0/releases/tag/v2.38.0) (2021-01-08)
- L0-8116_L0-cli-process-should-reflect-same-exit-code-as-its-child-process_Markus-Tarn (#680) @MarkusTarn
- Adds a --connector option to layer0 init. (#679) @markbrocato
- Don't allow built-in envvars to be overriden through dev console (#677) @ierceg
---
#### **Layer0 Packages** - [v2.37.2](https://github.com/layer0/layer0/releases/tag/v2.37.2) (2021-01-07)
- [L0-7802] Republish connectors to public repo (#665) @tristanlee85
- Fix local permanent asset support in dev and prod modes. (#678) @markbrocato
---
#### **Layer0 Packages** - [v2.37.1](https://github.com/layer0/layer0/releases/tag/v2.37.1) (2021-01-06)
- Increase default header size to 64kb (#669) @ierceg
- layer0 7974 fix include files (#670) @markbrocato
- Fix regression in 2.34 where renderNextPage with rewritten path fails to render in dev mode. (#667) @markbrocato
---
#### **Layer0 Packages** - [v2.37.0](https://github.com/layer0/layer0/releases/tag/v2.37.0) (2021-01-06)
- Bump axios from 0.19.0 to 0.21.1 in /packages/cli (#675) @dependabot
- Bump axios from 0.19.2 to 0.21.1 in /packages/build-lambda (#674) @dependabot
- feat: Preserve Cache + permanent assets (#645) @adrien-k
- Don't cache fallback route for Angular/Spartacus (#672) @kevhender
- fix x-xdn-destination destinationName escape in edge_recv_evaluate_de… (#673) @KaarelKelk
- fix(Prerender) fix types (#668) @KaarelKelk
- User lambda errors during deployment are not reported to CLI (#648) @MarkusTarn
---
#### **Layer0 Packages** - [v2.36.1](https://github.com/layer0/layer0/releases/tag/v2.36.1) (2020-12-30)
- Fix redirects with queries (#666) @ierceg
---
#### **Layer0 Packages** - [v2.36.0](https://github.com/layer0/layer0/releases/tag/v2.36.0) (2020-12-30)
- core API docs update (#663) @ianand
- Use layer0 dev (#660) @markbrocato
---
#### **Layer0 Packages** - [v2.35.2](https://github.com/layer0/layer0/releases/tag/v2.35.2) (2020-12-24)
- layer0 7579 layer0 init doesnt create dependency files mark brocato (#656) @markbrocato
---
#### **Layer0 Packages** - [v2.35.1](https://github.com/layer0/layer0/releases/tag/v2.35.1) (2020-12-23)
- Fix caching manifest generation issue (#661) @ierceg
- fix(proxy/edge): path with no / + fix(proxy/cloud) query-string forwarding (#662) @adrien-k
- fix(Prerendering) fix retry (#655) @KaarelKelk
- Bump ini from 1.3.5 to 1.3.8 in /packages/build-lambda (#659) @dependabot
---
#### **Layer0 Packages** - [v2.35.0](https://github.com/layer0/layer0/releases/tag/v2.35.0) (2020-12-22)
- L0-7844 - Issues with Next Commerce support (#658) @markbrocato
- L0-7849 - serveStatic does not support nested paths (#657) @markbrocato
- Introduce a formal Layer0 connectors API (#637) @markbrocato
---
#### **Layer0 Packages** - [v2.34.2](https://github.com/layer0/layer0/releases/tag/v2.34.2) (2020-12-22)
- Add checks before using endsWith (#651) @ierceg
---
#### **Layer0 Packages** - [v2.34.1](https://github.com/layer0/layer0/releases/tag/v2.34.1) (2020-12-21)
- Fastly cert update + multiple domain activation fix (#653) @leotoll
---
#### **Layer0 Packages** - [v2.34.0](https://github.com/layer0/layer0/releases/tag/v2.34.0) (2020-12-21)
- Improved error message if project fails due to missing @layer0/next build plugins (#652) @ianand
- L0-7810 - Add support for fallback: 'blocking' in getStaticPaths() (#654) @markbrocato
---
#### **Layer0 Packages** - [v2.33.4](https://github.com/layer0/layer0/releases/tag/v2.33.4) (2020-12-18)
- Remove content-length setting on unzipping (#601) @ierceg
---
#### **Layer0 Packages** - [v2.33.3](https://github.com/layer0/layer0/releases/tag/v2.33.3) (2020-12-17)
- Added missing appShell (#649) @ierceg
---
#### **Layer0 Packages** - [v2.33.2](https://github.com/layer0/layer0/releases/tag/v2.33.2) (2020-12-17)
- fix(Redirect): bug in initialise build (#647) @adrien-k
- test(ConsoleRedirect): enable integration test (#646) @adrien-k
- Do not reenable clustering and shielding on ISG+deployment restarts (#643) @ierceg
---
#### **Layer0 Packages** - [v2.33.1](https://github.com/layer0/layer0/releases/tag/v2.33.1) (2020-12-16)
- L0-7693 - Next: SSG static data paths are not correctly prerendered (#644) @markbrocato
- fix(core/redirect): query params (fixes the devtools docs redirect) (#608) @adrien-k
---
#### **Layer0 Packages** - [v2.33.0](https://github.com/layer0/layer0/releases/tag/v2.33.0) (2020-12-16)
- Localized rewrites not working in next commerce app (#641) @markbrocato
- feat(redirects): implement global redirects (#627) @adrien-k
---
#### **Layer0 Packages** - [v2.32.2](https://github.com/layer0/layer0/releases/tag/v2.32.2) (2020-12-15)
- Don't set long TTL on revalidated assets (#640) @ierceg
- L0-7650 - Route for /**layer0**/cache-manifest.js fails if route is de… (#639) @markbrocato
- L0-7592 - Build fails when serveStatic points to a non-existing asset. (#633) @markbrocato
---
#### **Layer0 Packages** - [v2.32.1](https://github.com/layer0/layer0/releases/tag/v2.32.1) (2020-12-11)
- Log AWS subaccount ID to our Sumo access logs (#638) @ierceg
- Prohibit the manipulation of content-length header directly from the router (#635) @ierceg
- feat(Prerender) dump body on 534 (#636) @KaarelKelk
---
#### **Layer0 Packages** - [v2.32.0](https://github.com/layer0/layer0/releases/tag/v2.32.0) (2020-12-11)
- Adds renderWithApp ResponseWriter method. (#634) @markbrocato
- Fix decoding of params for prefetch when values already have a % sign (#630) @kevhender
---
#### **Layer0 Packages** - [v2.31.0](https://github.com/layer0/layer0/releases/tag/v2.31.0) (2020-12-10)
- Fix integration tests (#631) @ierceg
- Enable ISG (#600) @ierceg
- fix(Actions) test new workflow env variable (#629) @KaarelKelk
---
#### **Layer0 Packages** - [v2.30.1](https://github.com/layer0/layer0/releases/tag/v2.30.1) (2020-11-16)
- Fix another cache poisoning (#611) @ierceg
---
#### **Layer0 Packages** - [v2.30.0](https://github.com/layer0/layer0/releases/tag/v2.30.0) (2020-11-16)
- @layer0/apollo now supports converting queries to GETs by operation and compressing them. (#560) @markbrocato
- The @layer0/next plugin now supports webpack 5. (#603) @markbrocato
- layer0 init now supports TypeScript (#607) @markbrocato
- L0-6813 - Webpack fails on importing of @layer0/core (#605) @markbrocato
---
#### **Layer0 Packages** - [v2.29.0](https://github.com/layer0/layer0/releases/tag/v2.29.0) (2020-11-10)
- [L0-6213] Spartacus integration improvement - first steps (#598) @kevhender
---
#### **Layer0 Packages** - [v2.28.0](https://github.com/layer0/layer0/releases/tag/v2.28.0) (2020-11-06)
- L0-6756 - Support distDir in next.config.js (#599) @markbrocato
---
#### **Layer0 Packages** - [v2.27.4](https://github.com/layer0/layer0/releases/tag/v2.27.4) (2020-11-04)
- Fix Module decode-uri-component not found (#595) @markbrocato
---
#### **Layer0 Packages** - [v2.27.3](https://github.com/layer0/layer0/releases/tag/v2.27.3) (2020-11-04)
- Always log user agent in user facing logs (#594) @ierceg
- Add **dev**getCompleteEdgeConfig job (#593) @ierceg
- Fix using custom servers in development. (#589) @markbrocato
---
#### **Layer0 Packages** - [v2.27.2](https://github.com/layer0/layer0/releases/tag/v2.27.2) (2020-11-04)
- L0-6589 Fix browser.maxAge: 0 interfering with edge caching (#590) @ierceg
---
#### **Layer0 Packages** - [v2.27.1](https://github.com/layer0/layer0/releases/tag/v2.27.1) (2020-11-04)
- Bump version to 2.27.1 (#591) @KaarelKelk
- L0-6513_Edge-config-validation-errors-are-not-properly-shown-to-the-user_Markus-Tarn (#587) @MarkusTarn
- feat(Prerendering) log response (#582) @KaarelKelk
- Fix `browser.maxAge: 0` interfering with edge caching (#588) @ierceg
---
#### **Layer0 Packages** - [v2.27.0](https://github.com/layer0/layer0/releases/tag/v2.27.0) (2020-11-03)
- Allow users to run downloaded deployments. (#576) @markbrocato
- fix(Devtools): preserve original req (#586) @adrien-k
- chore(build-lambda): remove secrets from logs + remove altHostnames +… (#584) @adrien-k
- L0-6217_Raise-an-error-durring-deployment-if-any-of-the-backends-use-one-of-the-sites-domains-as-domainOrIp_Markus-Tarn (#573) @MarkusTarn
- L0-6397 - Add source maps to router bundle to making debugging easie… (#580) @markbrocato
---
#### **Layer0 Packages** - [v2.26.3](https://github.com/layer0/layer0/releases/tag/v2.26.3) (2020-10-28)
- Log x-xdn-hit-request-id (#583) @ierceg
---
#### **Layer0 Packages** - [v2.26.2](https://github.com/layer0/layer0/releases/tag/v2.26.2) (2020-10-28)
- Fix watching of links for prefetching (#585) @kevhender
---
#### **Layer0 Packages** - [v2.26.1](https://github.com/layer0/layer0/releases/tag/v2.26.1) (2020-10-27)
- fix(Prefetcher): check origin (#581) @adrien-k
---
#### **Layer0 Packages** - [v2.26.0](https://github.com/layer0/layer0/releases/tag/v2.26.0) (2020-10-26)
- Add more logging on edge signature check (#571) @ierceg
- feat(FastlyClient): retry on clone 409 (#579) @adrien-k
- chore(lint): cover and fix ts files (#561) @adrien-k
- L0-5841_Allow-string-for-headercookiequery-matching-not-just-Regex_Markus-Tarn (#558) @MarkusTarn
---
#### **Layer0 Packages** - [v2.25.0](https://github.com/layer0/layer0/releases/tag/v2.25.0) (2020-10-23)
- Emulate edge locally by adding parameter interpolation in response.setHeader (#467) @phdunham
- Update @layer0/prefetcher to check query parameters (CU-L0-514) (CU-L0-5937) (#539) @kevhender
---
#### **Layer0 Packages** - [v2.24.2](https://github.com/layer0/layer0/releases/tag/v2.24.2) (2020-10-23)
- Fix logo (#574) @ierceg
- fix(Devtools): isolate Devtools style + fix reload + add clear btns (#570) @adrien-k
- Raise 500 when router path matching is bad including partial splats (#556) @ierceg
---
#### **Layer0 Packages** - [v2.24.1](https://github.com/layer0/layer0/releases/tag/v2.24.1) (2020-10-21)
- Preloading logs (#566) @KaarelKelk
---
#### **Layer0 Packages** - [v2.24.0](https://github.com/layer0/layer0/releases/tag/v2.24.0) (2020-10-21)
- fix(withLayer0): try fixing integration tests (#569) @adrien-k
- fix(Preloading) when no requests are sent back to le-deployer (#563) @KaarelKelk
- Fix Layer0 reentry when clients forward all the headers including Fastly-FF (#567) @ierceg
- feat(Devtools): Allow enabling/disabling the devtools (#554) @adrien-k
- Adds layer0.config.js to the src directory in the uploaded bundle. (#568) @markbrocato
- Fix the bad header name in Spartacus package (#565) @ierceg
---
#### **Layer0 Packages** - [v2.23.1](https://github.com/layer0/layer0/releases/tag/v2.23.1) (2020-10-19)
- fix(Build-lambda): override stable-2 (#564) @adrien-k
---
#### **Layer0 Packages** - [v2.22.0](https://github.com/layer0/layer0/releases/tag/v2.22.0) (2020-10-19)
- Bump version to 2.22.0 (#562) @KaarelKelk
- feat(Preloading) Adds a static prerendering option to Router (#458) @markbrocato
- L0-5390_Validate-domain-names_Markus-Tarn (#553) @MarkusTarn
- Update readme to reflect spartacus integration tests required maintenance work (#538) @leotoll
- Fix next peerDependency in @layer0 and automatically add @layer0/svelte whe… (#535) @markbrocato
- chore(prettier): harmonize prettier and format more file types (#547) @adrien-k
- fix(Fastly): expose invalid backend domain error (#550) @adrien-k
- Remove xdn_pref_headers param (#518) @kevhender
- feat(Devtools/Visualizer) (#509) @adrien-k
---
#### **Layer0 Packages** - [v2.21.0](https://github.com/layer0/layer0/releases/tag/v2.21.0) (2020-10-14)
- Add req.protocol (#551) @ierceg
---
#### **Layer0 Packages** - [v2.20.3](https://github.com/layer0/layer0/releases/tag/v2.20.3) (2020-10-13)
- Do not leak auth header upstream (#549) @ierceg
- fix(CallbackApi): fix awaitFlushed, add timeout and retry + unit tests (#543) @adrien-k
---
#### **Layer0 Packages** - [v2.20.2](https://github.com/layer0/layer0/releases/tag/v2.20.2) (2020-10-07)
- Fix trailing query string in lambda (#546) @ierceg
- Make `createGroups` param of `addCookie` optional (#540) @kevhender
---
#### **Layer0 Packages** - [v2.20.1](https://github.com/layer0/layer0/releases/tag/v2.20.1) (2020-10-06)
- fix(CallbackLogger) fixed message flush race condition (#542) @KaarelKelk
- Fix initialization build problem (#544) @ierceg
---
#### **Layer0 Packages** - [v2.20.0](https://github.com/layer0/layer0/releases/tag/v2.20.0) (2020-10-06)
- Allow opt-in support for HTTP protocol (#533) @ierceg
---
#### **Layer0 Packages** - [v2.19.0](https://github.com/layer0/layer0/releases/tag/v2.19.0) (2020-10-05)
- L0-5643 - Environment variables from the Layer0 Developer Console are now accessible at build time when using a deploy token (#526) @markbrocato
---
#### **Layer0 Packages** - [v2.18.1](https://github.com/layer0/layer0/releases/tag/v2.18.1) (2020-10-05)
- Fix error with babel-loader not being found in Next.js apps starting … (#536) @markbrocato
---
#### **Layer0 Packages** - [v2.18.0](https://github.com/layer0/layer0/releases/tag/v2.18.0) (2020-10-02)
- Add --includeSources CLI option. (#523) @markbrocato
- L0-5761 - Add @layer0/react when running layer0 init in gatsby app (#534) @markbrocato
- L0-5749 - Improve Layer0 install time by removing serverless (#531) @markbrocato
- L0-5753 - Fix issue with websocket requests failing during local dev… (#532) @markbrocato
---
#### **Layer0 Packages** - [v2.17.0](https://github.com/layer0/layer0/releases/tag/v2.17.0) (2020-10-01)
- L0-5686 - Minimize Nuxt.js serverless bundle size (#528) @markbrocato
- Minimize router bundle size (#529) @markbrocato
- Send custom message for Fastly 500 errors (#524) @ierceg
---
#### **Layer0 Packages** - [v2.16.1](https://github.com/layer0/layer0/releases/tag/v2.16.1) (2020-09-30)
- Enable build lambda deploys to sandbox (#527) @ierceg
- Nuxt: static routes should take precedence over dynamic routes. (#525) @markbrocato
- Use random fastly API tokens provided by LD, if available (#508) @ierceg
- Fix console output to JSON doesn't capture all args (#521) @ierceg
- L0-5466 - Embed the router in the uploaded build (#514) @markbrocato
---
#### **Layer0 Packages** - [v2.16.0](https://github.com/layer0/layer0/releases/tag/v2.16.0) (2020-09-28)
- L0-3005 - Support for basic auth (#519) @markbrocato
- L0-5587 - Fix issue where catch-all routes incorrectly take preceden… (#520) @markbrocato
- Improve error message that is shown when deployment fails due to an error in the user's application code. (#517) @markbrocato
- Improve user errors on edge deploy (#502) @MarkusTarn
- Add integration tests for force-private-caching override (#513) @ierceg
---
#### **Layer0 Packages** - [v2.15.0](https://github.com/layer0/layer0/releases/tag/v2.15.0) (2020-09-25)
- Added paths config support (#515) @dijs
- Allow backends to have custom ports at and above 443 (#516) @ierceg
---
#### **Layer0 Packages** - [v2.14.0](https://github.com/layer0/layer0/releases/tag/v2.14.0) (2020-09-24)
- Allow for not-present matching for headers, cookies and query parameters (#511) @ierceg
- Fix header name comparison to be case-insensitive (#511) @ierceg
---
#### **Layer0 Packages** - [v2.13.4](https://github.com/layer0/layer0/releases/tag/v2.13.4) (2020-09-24)
- Reset private caching to false only if explicitly requested in the router (#512) @ierceg
---
#### **Layer0 Packages** - [v2.13.3](https://github.com/layer0/layer0/releases/tag/v2.13.3) (2020-09-24)
- L0-5528 - Support hardcoded paths in Next.js rewrites (#510) @markbrocato
---
#### **Layer0 Packages** - [v2.13.2](https://github.com/layer0/layer0/releases/tag/v2.13.2) (2020-09-23)
- Improve CLI output: Add a clearer deployment complete message. (#505) @markbrocato
---
#### **Layer0 Packages** - [v2.13.1](https://github.com/layer0/layer0/releases/tag/v2.13.1) (2020-09-23)
- Don't add default router and service worker to the user's app on ever… (#507) @markbrocato
---
#### **Layer0 Packages** - [v2.13.0](https://github.com/layer0/layer0/releases/tag/v2.13.0) (2020-09-22)
- [L0-5422] Ensure that manual edits to the changelog are preserved (#506) @tristanlee85
- L0-5414 - Use --standalone to bundle dependencies when running nuxt … (#501) @markbrocato
---
#### **Layer0 Packages** - [v2.12.1](https://github.com/layer0/layer0/releases/tag/v2.12.1) (2020-09-22)
- Update Sapper integration test to match the docs and not include node… (#504) @markbrocato
- Remove obsolete domain check to enable wildcard reverse proxy in edge (#503) @ierceg
- Allow relative paths when deep fetching from JSON (#498) @kevhender
---
#### **Layer0 Packages** - [v2.12.0](https://github.com/layer0/layer0/releases/tag/v2.12.0) (2020-09-21)
- Apollo prefetching now uses GETs for all queries. (#500) @markbrocato
---
#### **Layer0 Packages** - [v2.11.2](https://github.com/layer0/layer0/releases/tag/v2.11.2) (2020-09-21)
- Fix L0-5364 - Next.js redirect to remove trailing slash prevents fal… (#496) @markbrocato
- feat(CLI): Require node version: 12 or newer (#495) @adrien-k
- [L0-5258] Generate changelog when publishing release (#497) @tristanlee85
- docs(README): add link to docs (#499) @adrien-k
---
#### **Layer0 Packages** - [v2.11.1](https://github.com/layer0/layer0/releases/tag/v2.11.1) (2020-09-16)
- Update integration tests for POST/GET&xdn_prefetch=1 caching (#494) @phdunham
- Next.js: Fix layer0 build on windows (#492) @markbrocato
- Fix coverage of nextRoutes (#493) @leotoll
---
#### **Layer0 Packages** - [v2.11.0](https://github.com/layer0/layer0/releases/tag/v2.11.0) (2020-09-16)
- feat(frameworks): add Gatsby support + serve static root document (#474) @adrien-k
---
#### **Layer0 Packages** - [v2.10.3](https://github.com/layer0/layer0/releases/tag/v2.10.3) (2020-09-15)
- Sapper: Remove extra service-worker route from the default routes.js file add… (#491) @markbrocato
---
#### **Layer0 Packages** - [v2.10.2](https://github.com/layer0/layer0/releases/tag/v2.10.2) (2020-09-15)
- Next.js: pages/404.js now properly functions as the default fallback (#478) @leotoll
- Fix bug in @layer0/sapper where the service worker would not be loaded i… (#490) @markbrocato
---
#### **Layer0 Packages** - [v2.10.1](https://github.com/layer0/layer0/releases/tag/v2.10.1) (2020-09-14)
- Fix issue where pages/api/index.js was not being resolved by the Layer0 … (#488) @markbrocato
---
#### **Layer0 Packages** - [v2.10.0](https://github.com/layer0/layer0/releases/tag/v2.10.0) (2020-09-14)
- feat(Errors): enhance user-facing fastly errors (#480) @adrien-k
- Fix bug when using proxy with path option and a catch-all or optional… (#482) @markbrocato
- Run request/response header manipulation in compute/trasnform (#483) @ierceg
- Add functionality for prefetching GQL requests. (CU-a6axpw) (#451) @markbrocato
- Add x-xdn-user-t to server-timing response header (#484) @ierceg
- Bump node-fetch from 2.6.0 to 2.6.1 in /integration-tests/edge (#487) @dependabot
- Bump node-fetch from 2.6.0 to 2.6.1 in /packages/core (#486) @dependabot
- Add support for running Sapper apps with layer0 run --production (#481) @markbrocato
- Log 503 errors generated by shield (not just edge) (#479) @phdunham
---
#### **Layer0 Packages** - [v2.9.0](https://github.com/layer0/layer0/releases/tag/v2.9.0) (2020-09-09)
- Fix Layer0-on-Layer0 caching issues (#431) @ierceg
- fix(MatchQuery) added edge config tests (#477) @KaarelKelk
---
#### **Layer0 Packages** - [v2.8.0](https://github.com/layer0/layer0/releases/tag/v2.8.0) (2020-09-08)
- Adds support for the Sapper framework (#462) @markbrocato
- feat(CLI): log failed build output in LD (#452) @adrien-k
- Bump yargs-parser from 15.0.0 to 15.0.1 in /packages/cli (#475) @dependabot
---
#### **Layer0 Packages** - [v2.7.0](https://github.com/layer0/layer0/releases/tag/v2.7.0) (2020-09-07)
- feat(MatchQuery) added criteria.query to match query params - L0-533 (#461) @KaarelKelk
- Optimize router loop unrolling by using equivalency chains (#472) @ierceg
- fix(handler/logs): wrap console AND streams + remove globals (#471) @adrien-k
- fix(Route) Matching headers returned true for single header match (#469) @KaarelKelk
---
#### **Layer0 Packages** - [v2.6.4](https://github.com/layer0/layer0/releases/tag/v2.6.4) (2020-09-04)
- Lower the ACL limit to 900 to avoid Fastly's spurious API errors (#473) @ierceg
---
#### **Layer0 Packages** - [v2.6.3](https://github.com/layer0/layer0/releases/tag/v2.6.3) (2020-09-03)
- Move static method to RouteGroup (#465) @markbrocato
---
#### **Layer0 Packages** - [v2.6.2](https://github.com/layer0/layer0/releases/tag/v2.6.2) (2020-09-02)
- Fix bug where layer0 init fails if a supported web framework is not dete… (#470) @markbrocato
- Ignore query params when watching links to prefetch (#444) @kevhender
---
#### **Layer0 Packages** - [v2.6.1](https://github.com/layer0/layer0/releases/tag/v2.6.1) (2020-09-02)
- Optimize x-xdn-original-qs to be injected only when qs are changed (#468) @ierceg
---
#### **Layer0 Packages** - [v2.6.0](https://github.com/layer0/layer0/releases/tag/v2.6.0) (2020-09-01)
- Fix caching of static pages in NextRoutes. (#464) @markbrocato
- Fix memory overconsumption in moov_hash (#463) @ierceg
- Router static implementation for next (#428) @leotoll
- Improve ci time (#447) @leotoll
- Inject example x-xdn-geo- headers when running locally for easier testing. (#460) @phdunham
- Emulate edge by injecting headers based on user-agent (#457) @phdunham
---
#### **Layer0 Packages** - [v2.5.0](https://github.com/layer0/layer0/releases/tag/v2.5.0) (2020-08-28)
- feat(core/Router): prevent adding routes after fallback statement (#453) @adrien-k
- fix(consoleWrapper): shim stdout/stderr to encapsulate in json (#432) @adrien-k
- L0-1438 - Fix bug where using an async callback in compute() results… (#456) @markbrocato
- fix(@layer0/angular) Fix link command (#436) @KaarelKelk
- Update the color scheme of the logo in the CLI. (#455) @markbrocato
- Emulate edge's x-xdn-client-ip header when running locally (#454) @phdunham
---
#### **Layer0 Packages** - [v2.4.2](https://github.com/layer0/layer0/releases/tag/v2.4.2) (2020-08-26)
- Corrected API documentation comment (#450) @ianand
- Order predefined routes before dynamic routes (#440) @dijs
- Angular fixups (#446) @tonylepmets
---
#### **Layer0 Packages** - [v2.4.1](https://github.com/layer0/layer0/releases/tag/v2.4.1) (2020-08-26)
- PC-2330 - add Fastly API retry on 500 or 503 errors (#441) @phdunham
- Disable request coalesing on shield (#448) @ierceg
---
#### **Layer0 Packages** - [v1.48.1](https://github.com/layer0/layer0/releases/tag/v1.48.1) (2020-08-26)
- [v1 back port] Disable request coalescing on shield (#449) @ierceg
---
#### **Layer0 Packages** - [v2.4.0](https://github.com/layer0/layer0/releases/tag/v2.4.0) (2020-08-26)
- Fix bug where context.params was undefined in getServerSideProps and getInitialProps in development when using layer0 run. (#443) @dijs
- Adds a `compute()` function to `ResponseWriter` to compute responses in t… (#442) @markbrocato
- Support service workers and prefetching in Nuxt apps when running in … (#445) @markbrocato
---
#### **Layer0 Packages** - [v1.48.0](https://github.com/layer0/layer0/releases/tag/v1.48.0) (2020-08-24)
- v1: Add ability to completely turn off edge/browser caching for a route (back port of #435 to v1) (#437) @ierceg
- Don't use latest tag any more (#434) @ierceg
---
#### **Layer0 Packages** - [v2.3.1](https://github.com/layer0/layer0/releases/tag/v2.3.1) (2020-08-23)
- No changes - releasing as the previous release went out incorrectly as 2.2.1
---
#### **Layer0 Packages** - [v2.3.0](https://github.com/layer0/layer0/releases/tag/v2.3.0) (2020-08-22)
- Add ability to completely turn off edge/browser caching for a route (#435) @ierceg
---
#### **Layer0 Packages** - [v1.47.0](https://github.com/layer0/layer0/releases/tag/v1.47.0) (2020-08-21)
- [1.x] Adds a new timing API to allow users to track the performance of thei… (#430) (#433) @ierceg
---
#### **Layer0 Packages** - [v2.2.0](https://github.com/layer0/layer0/releases/tag/v2.2.0) (2020-08-20)
- Adds a new timing API to allow users to track the performance of thei… (#430) @markbrocato
- Upgrade next tests to 9.5 (#429) @ierceg
- Fix issue during layer0 build with Next.js apps that use source maps. (#423) @markbrocato
- Add service worker to new Nuxt.js apps. (#427) @markbrocato
- Fix bug when Next.js rewrites and redirects functions are async. (#425) @markbrocato
---
#### **Layer0 Packages** - [v2.1.0](https://github.com/layer0/layer0/releases/tag/v2.1.0) (2020-08-18)
- Install @layer0/vue as a runtime dependency. (#421) @markbrocato
- Make cors config optional for prefetch options (#424) @kevhender
- Fix VCL code generation with conditions containing double quotes (#426) @ierceg
- Add spartacus tests (#415) @leotoll
- Make cors config optional for prefetch options (#420) @kevhender
- Update "current" folder with latest when pushing new docs (#422) @kevhender
---
#### **Layer0 Packages** - [v2.0.4](https://github.com/layer0/layer0/releases/tag/v2.0.4) (2020-08-17)
- Add NODE_ENV production to build lambdas (#419) @ierceg
- Add appShell method to ResponseWriter. (#413) @markbrocato
- PC-2313 - Fix nuxt es6 prod (#418) @markbrocato
---
#### **Layer0 Packages** - [v2.0.3](https://github.com/layer0/layer0/releases/tag/v2.0.3) (2020-08-15)
- Support src/pages in Next.js apps. (#417) @markbrocato