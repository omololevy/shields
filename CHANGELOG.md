# Changelog

Note: this changelog is for the shields.io server. The changelog for the badge-maker NPM package is at https://github.com/badges/shields/blob/master/badge-maker/CHANGELOG.md

---

## server-2023-12-01

- Changelog for Release server-2023-02-01 [#8871](https://github.com/badges/shields/issues/8871)
- skip danger on repo ranger commits [#8866](https://github.com/badges/shields/issues/8866)
- Add ESLint checks for IcedFrisby exclusive/skipped tests [#8839](https://github.com/badges/shields/issues/8839)
- build docker images with buildkit v0.9.1 [#8862](https://github.com/badges/shields/issues/8862)
- replace [twitter] badge with static fallback [#8842](https://github.com/badges/shields/issues/8842)
- add a note about fine-grained PATs in the docs [#8823](https://github.com/badges/shields/issues/8823)
- migrate service tests to GH actions [#8421](https://github.com/badges/shields/issues/8421)
- remove danger-plugin-no-test-shortcuts [#8815](https://github.com/badges/shields/issues/8815)
- Add various [Polymart] badges [#8811](https://github.com/badges/shields/issues/8811)
- update [githubpipenv] tests/examples [#8797](https://github.com/badges/shields/issues/8797)
- fix service test loader on windows, add tests [#8786](https://github.com/badges/shields/issues/8786)
- Add docstrings for pipenv helpers [#8787](https://github.com/badges/shields/issues/8787)
- migrate danger CI job to GHA [#8477](https://github.com/badges/shields/issues/8477)
- deprecate [apm] service [#8773](https://github.com/badges/shields/issues/8773)
- Docstrings for php-version service [#8766](https://github.com/badges/shields/issues/8766)
- deprecate lgtm; lgtm service tests should be passing [#8771](https://github.com/badges/shields/issues/8771)
- Changelog for Release server-2023-01-01 [#8765](https://github.com/badges/shields/issues/8765)
- migrate frontend tests to GHA [#8541](https://github.com/badges/shields/issues/8541)
- Send `X-GitHub-Api-Version` when calling [GitHub] v3 API [#8669](https://github.com/badges/shields/issues/8669)
- add [VpmVersion] badge [#8755](https://github.com/badges/shields/issues/8755)
- Add [modrinth] game versions [#8673](https://github.com/badges/shields/issues/8673)
- don't try to call .entries on null or undefined [#8757](https://github.com/badges/shields/issues/8757)
- fix debug logging of undefined query params [#8540](https://github.com/badges/shields/issues/8540)
- run close-bot on node 16 [#8740](https://github.com/badges/shields/issues/8740)
- allow all numeric branch names in [githubactionsworkflowstatus] [#8734](https://github.com/badges/shields/issues/8734)
- switch [GithubActionsWorkflowStatus] to SVG scraper [#8738](https://github.com/badges/shields/issues/8738)
- handle workflow runs that do not have a conclusion [#8717](https://github.com/badges/shields/issues/8717)
- add a clarifying comment to [pypi] getLicenses [#8718](https://github.com/badges/shields/issues/8718)
- switch from github workflows to github actions workflows; test [githubactionsworkflowstatus githubworkflowstatus] [#8475](https://github.com/badges/shields/issues/8475)
- fall back to classifiers if license text is really long [#8690](https://github.com/badges/shields/issues/8690)
- docs/issue template improvements for badge requests [#8668](https://github.com/badges/shields/issues/8668)
- allow passing key to [stackexchange] [#8539](https://github.com/badges/shields/issues/8539)
- Changelog for Release server-2022-12-01 [#8670](https://github.com/badges/shields/issues/8670)
- fix: support logoColor to shield icons. [#8263](https://github.com/badges/shields/issues/8263)
- migrate e2e tests to GHA [#8562](https://github.com/badges/shields/issues/8562)
- handle missing properties array in [VisualStudioMarketplaceVersion] [#8603](https://github.com/badges/shields/issues/8603)
- don't call external services in core tests [#8643](https://github.com/badges/shields/issues/8643)
- add a missing redirect to coveralls [#8644](https://github.com/badges/shields/issues/8644)
- deprecate [wercker] service [#8642](https://github.com/badges/shields/issues/8642)
- Add [Coincap] Cryptocurrency badges [#8623](https://github.com/badges/shields/issues/8623)
- Add [modrinth] version [#8604](https://github.com/badges/shields/issues/8604)
- [factorio-mod-portal] services [#8625](https://github.com/badges/shields/issues/8625)
- [Coveralls] for GitLab [#8584](https://github.com/badges/shields/issues/8584)
- Remove 'suggest badges' feature [#8311](https://github.com/badges/shields/issues/8311)
- Add [modrinth] followers [#8601](https://github.com/badges/shields/issues/8601)
- Update the [modrinth] API to v2 [#8600](https://github.com/badges/shields/issues/8600)
- bump actions/setup-node to v3 [#8542](https://github.com/badges/shields/issues/8542)
- tidy up [GitHubGist] routes [#8510](https://github.com/badges/shields/issues/8510)
- fix [flathub] version error handling [#8500](https://github.com/badges/shields/issues/8500)
- fix [tas] private project test [#8514](https://github.com/badges/shields/issues/8514)
- Changelog for Release server-2022-11-01 [#8588](https://github.com/badges/shields/issues/8588)
- [Ansible] Add collection badge [#8578](https://github.com/badges/shields/issues/8578)
- fix [githubpullrequestcheckstate] service tests [#8548](https://github.com/badges/shields/issues/8548)
- require array to have at least 1 item in [githublastcommit] [#8563](https://github.com/badges/shields/issues/8563)
- [VisualStudioMarketplace] Add support to prerelease extensions version (Issue #8207) [#8561](https://github.com/badges/shields/issues/8561)
- feat: add [GitlabLastCommit] service [#8508](https://github.com/badges/shields/issues/8508)
- fix [swagger] service tests (allow 0 items in array) [#8564](https://github.com/badges/shields/issues/8564)
- fix codecov badge for non-default branch [#8565](https://github.com/badges/shields/issues/8565)
- fixes for integration test rate limit issues [#8538](https://github.com/badges/shields/issues/8538)
- remove failing [lgtm] test case [#8547](https://github.com/badges/shields/issues/8547)
- Add [GitHubLastCommit] by committer badge [#8537](https://github.com/badges/shields/issues/8537)
- [GitHubReleaseDate] - published_at field [#8543](https://github.com/badges/shields/issues/8543)
- Fix [Testspace] with new "untested" value in case_counts array [#8544](https://github.com/badges/shields/issues/8544)
- fix: Support WAITING status for GitHub deployments [#8521](https://github.com/badges/shields/issues/8521)
- update [bitbucket] private repo test [#8520](https://github.com/badges/shields/issues/8520)
- update [powershellgallery] platform example [#8518](https://github.com/badges/shields/issues/8518)
- fix [myget] downloads (tenant) test [#8513](https://github.com/badges/shields/issues/8513)
- [Whatpulse] badge for a user and for a team [#8466](https://github.com/badges/shields/issues/8466)
- increase timeout for [reuse] not found test [#8519](https://github.com/badges/shields/issues/8519)
- update [JenkinsPluginInstalls] test example [#8511](https://github.com/badges/shields/issues/8511)
- migrate integration tests to GH actions [#8423](https://github.com/badges/shields/issues/8423)
- deprecate [pkgreview] service [#8499](https://github.com/badges/shields/issues/8499)
- Changelog for Release server-2022-10-08 [#8507](https://github.com/badges/shields/issues/8507)
- deprecate [criterion] service [#8501](https://github.com/badges/shields/issues/8501)
- fix [wordpress] php version not set test [#8496](https://github.com/badges/shields/issues/8496)
- fix formatRelativeDate error handling; run [date] [#8497](https://github.com/badges/shields/issues/8497)
- allow/validate bitbucket_username / bitbucket_password in private config schema [#8472](https://github.com/badges/shields/issues/8472)
- fix [pub] points badge test and example [#8498](https://github.com/badges/shields/issues/8498)
- feat: add [GitlabLanguageCount] service [#8377](https://github.com/badges/shields/issues/8377)
- docs: update wording and url for freecodecamp usernames [#8480](https://github.com/badges/shields/issues/8480)
- [GitHubGistStars] add GitHub Gist Stars [#8471](https://github.com/badges/shields/issues/8471)
- fix display/search of CII badge examples [#8473](https://github.com/badges/shields/issues/8473)
- feat: add 2022 support to GitHub Hacktoberfest [#8468](https://github.com/badges/shields/issues/8468)
- [GitLabCoverage] subgroup bug [#8401](https://github.com/badges/shields/issues/8401)
- implement ruby gems-specific version sort/color functions [#8434](https://github.com/badges/shields/issues/8434)
- Add `rc` to pre-release identifiers [#8435](https://github.com/badges/shields/issues/8435)
- [GitHub] Number of commits between branches/tags/commits [#8394](https://github.com/badges/shields/issues/8394)
- [Packagist] dependency version [#8371](https://github.com/badges/shields/issues/8371)
- return string instead of object from getDependencyVersion function [#8396](https://github.com/badges/shields/issues/8396)
- conform to standard js quote rules [#8395](https://github.com/badges/shields/issues/8395)
- fix Docker build status invalid response data bug [#8392](https://github.com/badges/shields/issues/8392)
- use Joi type for Joi schemas [#8380](https://github.com/badges/shields/issues/8380)
- Docstrings for package json helpers [#8373](https://github.com/badges/shields/issues/8373)
- migrate package tests to GHA [#8351](https://github.com/badges/shields/issues/8351)
- improve workflow job names [#8376](https://github.com/badges/shields/issues/8376)
- feat: add [gitlab]-helper for encapsulate docs and err [#8295](https://github.com/badges/shields/issues/8295)
- Changelog for Release server-2022-09-04 [#8374](https://github.com/badges/shields/issues/8374)
- get the tests passing on windows [#8350](https://github.com/badges/shields/issues/8350)
- [DockerSize] Docker image size multi arch [#8290](https://github.com/badges/shields/issues/8290)
- migrate 'main' tests to GH actions [#8332](https://github.com/badges/shields/issues/8332)
- upgrade gatsby [#8334](https://github.com/badges/shields/issues/8334)
- Custom domains for [JitPack] artifacts [#8333](https://github.com/badges/shields/issues/8333)
- fix [dockerstars] service [#8316](https://github.com/badges/shields/issues/8316)
- Fix: Broken Badge generation for decimal activity values [#8315](https://github.com/badges/shields/issues/8315)
- feat: add [gitlabmergerequests] service [#8166](https://github.com/badges/shields/issues/8166)
- Fix variable naming for [ROS] version service [#8292](https://github.com/badges/shields/issues/8292)
- feat: add [GitlabStars] service [#8209](https://github.com/badges/shields/issues/8209)
- Fix invalid `rst` format when `alt` or `target` is present [#8275](https://github.com/badges/shields/issues/8275)
- [GithubGistLastCommit] GitHub gist last commit [#8272](https://github.com/badges/shields/issues/8272)
- chore: fix typo in badge request template [#8254](https://github.com/badges/shields/issues/8254)
- [GitHub] GitHub file size for a specific branch [#8262](https://github.com/badges/shields/issues/8262)
- Changelog for Release server-2022-08-01 [#8268](https://github.com/badges/shields/issues/8268)
- [pypi] Add Framework Version Badges support [#8261](https://github.com/badges/shields/issues/8261)
- feat: add [GitlabForks] server [#8208](https://github.com/badges/shields/issues/8208)
- Update PyPI api according to https://warehouse.pypa.io/api-reference/json.html [#8251](https://github.com/badges/shields/issues/8251)
- Add [galaxytoolshed] Activity [#8164](https://github.com/badges/shields/issues/8164)
- Fix wording in code-walkthrough.md [#8240](https://github.com/badges/shields/issues/8240)
- Fix typo in service-tests.md [#8239](https://github.com/badges/shields/issues/8239)
- [greasyfork] Add Greasy Fork rating badges [#8087](https://github.com/badges/shields/issues/8087)
- Fix heroku review apps (sort of) [#8213](https://github.com/badges/shields/issues/8213)
- Fix missing `dayjs` -> `moment` [#8204](https://github.com/badges/shields/issues/8204)
- refactor(deps): Replace moment with dayjs [#8192](https://github.com/badges/shields/issues/8192)
- add spaces round pipe in [conda] badge [#8189](https://github.com/badges/shields/issues/8189)
- Add [ROS] version service [#8169](https://github.com/badges/shields/issues/8169)
- feat: add [gitlabissues] service [#8108](https://github.com/badges/shields/issues/8108)
- add docs on nouns in route [#8141](https://github.com/badges/shields/issues/8141)
- Changelog for Release server-2022-07-03 [#8163](https://github.com/badges/shields/issues/8163)
- moar fixes for [gitlab] auth [#8162](https://github.com/badges/shields/issues/8162)
- Add [galaxytoolshed] services [#8114](https://github.com/badges/shields/issues/8114)
- Docstrings for licenses service [#8160](https://github.com/badges/shields/issues/8160)
- fix [gitlab] auth [#8145](https://github.com/badges/shields/issues/8145)
- change routes for [gitlab] license and contributors badges [#8140](https://github.com/badges/shields/issues/8140)
- ci: support new circle PR url variable [#8135](https://github.com/badges/shields/issues/8135)
- increase cache length on AUR version badge, run [AUR] [#8110](https://github.com/badges/shields/issues/8110)
- Use GraphQL to fix GitHub file count badges [github] [#8112](https://github.com/badges/shields/issues/8112)
- update targets for [bower] service tests [#8107](https://github.com/badges/shields/issues/8107)
- accept version with suffix in [ore] service tests [#8106](https://github.com/badges/shields/issues/8106)
- style: unified self-managed gitlab instance name [#8105](https://github.com/badges/shields/issues/8105)
- feat: add [gitlab] contributors service [#8084](https://github.com/badges/shields/issues/8084)
- fix: display greasy fork dd correctly [#8088](https://github.com/badges/shields/issues/8088)
- [greasyfork] Add Greasy Fork service badges [#8080](https://github.com/badges/shields/issues/8080)
- Fix typos in endpoint badge docs [#8085](https://github.com/badges/shields/issues/8085)
- fix: gitlab licence service docs and example [#8083](https://github.com/badges/shields/issues/8083)
- add docstrings for endpoint-common service [#8079](https://github.com/badges/shields/issues/8079)
- fix(gitlab service test): fix gitlab pipeline & tag(nested group) service test, run [gitlabtag gitlabpipeline] [#8076](https://github.com/badges/shields/issues/8076)
- Add [gitlablicense] services [#8024](https://github.com/badges/shields/issues/8024)
- [Spack] Package Manager: Update Domain [#8046](https://github.com/badges/shields/issues/8046)
- Docstrings for dynamic-common service [#8027](https://github.com/badges/shields/issues/8027)
- switch [jitpack] to use latestOk endpoint [#8041](https://github.com/badges/shields/issues/8041)
- Changelog for Release server-2022-06-01 [#8025](https://github.com/badges/shields/issues/8025)
- Docstrings for contributor-count and deprecation-helpers services [#8003](https://github.com/badges/shields/issues/8003)
- docs: update SVGO usage instruction [#8001](https://github.com/badges/shields/issues/8001)
- Add docstrings for color formatter service [#8000](https://github.com/badges/shields/issues/8000)
- Update GitLab logo (2022) [#7984](https://github.com/badges/shields/issues/7984)
- add docstrings for build-status service [#7999](https://github.com/badges/shields/issues/7999)
- [GitHub] Added milestone property to GitHub issue details service [#7864](https://github.com/badges/shields/issues/7864)
- simplify NPM strict checks [#7973](https://github.com/badges/shields/issues/7973)
- update docs on production hosting [#7976](https://github.com/badges/shields/issues/7976)
- Update node images [#7972](https://github.com/badges/shields/issues/7972)
- [Flathub] Relabel new download badge [#7958](https://github.com/badges/shields/issues/7958)
- [Spack] Package Manager: Update Endpoint [#7957](https://github.com/badges/shields/issues/7957)
- Update Chocolatey API endpoint URL [#7952](https://github.com/badges/shields/issues/7952)
- [Flathub]Add downloads badge [#7724](https://github.com/badges/shields/issues/7724)
- replace the outdated Telegram logo with the newest [#7831](https://github.com/badges/shields/issues/7831)
- chore: Included githubactions in the dependabot config [#7932](https://github.com/badges/shields/issues/7932)
- Change lukesampson/scoop to ScoopInstaller/Scoop [#7933](https://github.com/badges/shields/issues/7933)
- add [PUB] points badge [#7918](https://github.com/badges/shields/issues/7918)
- add [PUB] popularity badge [#7920](https://github.com/badges/shields/issues/7920)
- update actions checkout step version [#7927](https://github.com/badges/shields/issues/7927)
- add [PUB] likes badge [#7916](https://github.com/badges/shields/issues/7916)
- chore: Set permissions for GitHub actions [#7928](https://github.com/badges/shields/issues/7928)
- Changelog for Release server-2022-05-03 [#7923](https://github.com/badges/shields/issues/7923)
- fix [pub] service tests [#7921](https://github.com/badges/shields/issues/7921)
- move all public production config into yaml [#7885](https://github.com/badges/shields/issues/7885)
- [OSSFScorecard] Create scorecard badge service [#7687](https://github.com/badges/shields/issues/7687)
- Stringify [githublanguagecount] message [#7881](https://github.com/badges/shields/issues/7881)
- Stringify and trim whitespace from a few services [#7880](https://github.com/badges/shields/issues/7880)
- Reclassify test for versionColorForWordpressVersion as an integration test [#7879](https://github.com/badges/shields/issues/7879)
- Remove obsolete monitor.html [#7878](https://github.com/badges/shields/issues/7878)
- add labels to Dockerfile [#7862](https://github.com/badges/shields/issues/7862)
- fix: various sonar service tests [#7836](https://github.com/badges/shields/issues/7836)
- fix: bitrise example & service test [#7837](https://github.com/badges/shields/issues/7837)
- add dependency review action [#7816](https://github.com/badges/shields/issues/7816)
- handle missing 'fly-client-ip' [#7814](https://github.com/badges/shields/issues/7814)
- note ioredis breaking change in changelog [#7813](https://github.com/badges/shields/issues/7813)
- Changelog for Release server-2022-04-03 [#7812](https://github.com/badges/shields/issues/7812)
- downgrade eslint-plugin-promise to 5.2.0 [#7809](https://github.com/badges/shields/issues/7809)
- two fixes for [packagist] schemas [#7782](https://github.com/badges/shields/issues/7782)
- allow requireCloudflare setting to work when hosted on fly.io [#7781](https://github.com/badges/shields/issues/7781)
- fix [pypi] badges when package has null license [#7761](https://github.com/badges/shields/issues/7761)
- Use new CircleCI "convenience" images [#7726](https://github.com/badges/shields/issues/7726)
- cache [pub] publisher badge for an hour [#7762](https://github.com/badges/shields/issues/7762)
- Add a [pub] publisher badge [#7715](https://github.com/badges/shields/issues/7715)
- Update number of badges served each month [#7723](https://github.com/badges/shields/issues/7723)
- Switch Steam file size badge to informational color [#7722](https://github.com/badges/shields/issues/7722)
- Make W3C and Youtube documentation links clickable [#7721](https://github.com/badges/shields/issues/7721)
- Improve Wercker examples [#7720](https://github.com/badges/shields/issues/7720)
- Improve Cirrus CI examples [#7719](https://github.com/badges/shields/issues/7719)
- Support [CodeClimate] responses with multiple data items [#7716](https://github.com/badges/shields/issues/7716)
- Delete [TeamCityCoverage] and [BowerVersion] redirectors [#7718](https://github.com/badges/shields/issues/7718)
- Deprecate [Shippable] service [#7717](https://github.com/badges/shields/issues/7717)
- fix: restore version comparison updates from #4173 [#4254](https://github.com/badges/shields/issues/4254)
- [piwheels], filter out versions with no files [#7696](https://github.com/badges/shields/issues/7696)
- set a longer cacheLength on [librariesio] badges [#7692](https://github.com/badges/shields/issues/7692)
- improve python version formatting [#7682](https://github.com/badges/shields/issues/7682)
- Clarify GitHub All Contributors badge [#7690](https://github.com/badges/shields/issues/7690)
- Fix GitHub Deployments example color [#7691](https://github.com/badges/shields/issues/7691)
- Support [HexPM] packages with no stable release [#7685](https://github.com/badges/shields/issues/7685)
- Fix [SnykVulnerability] test [#7686](https://github.com/badges/shields/issues/7686)
- Support for Test at Scale Badge, run [TAS] [#7612](https://github.com/badges/shields/issues/7612)
- [packagist] api v2 support [#7681](https://github.com/badges/shields/issues/7681)
- Add [piwheels] version badge [#7656](https://github.com/badges/shields/issues/7656)
- Changelog for Release server-2022-03-01 [#7659](https://github.com/badges/shields/issues/7659)
- Add [Conan] version service [#7460](https://github.com/badges/shields/issues/7460)
- remove suspended [github] tokens from the pool [#7654](https://github.com/badges/shields/issues/7654)
- generate links without trailing : if port not set [#7655](https://github.com/badges/shields/issues/7655)
- note in SECURITY.md that svg-to-image-proxy is deprecated [#7653](https://github.com/badges/shields/issues/7653)
- tests(snyk): fix github manifest target [#7629](https://github.com/badges/shields/issues/7629)
- fix: github pipenv service test [#7627](https://github.com/badges/shields/issues/7627)
- Use the latest build status when checking docs.rs [#7613](https://github.com/badges/shields/issues/7613)
- tests(securityheaders): increase timeout [#7628](https://github.com/badges/shields/issues/7628)
- Remove no download handling and add API warning to [Wordpress] badges [#7606](https://github.com/badges/shields/issues/7606)
- set a higher default cacheLength on rating/star category [#7587](https://github.com/badges/shields/issues/7587)
- Update [amo] to use v4 API, set custom `cacheLength`s [#7586](https://github.com/badges/shields/issues/7586)
- fix(amo): include trailing slash in API call [#7585](https://github.com/badges/shields/issues/7585)
- fix docker image user agent [#7582](https://github.com/badges/shields/issues/7582)
- Delete deprecated Codetally and continuousphp services [#7572](https://github.com/badges/shields/issues/7572)
- Deprecate [Requires] service [#7571](https://github.com/badges/shields/issues/7571)
- [AUR] Fix RPC URL [#7570](https://github.com/badges/shields/issues/7570)
- Changelog for Release server-2022-02-01 [#7550](https://github.com/badges/shields/issues/7550)
- Fix [Drone] tests and examples [#7549](https://github.com/badges/shields/issues/7549)
- Fix [GitlabCoverage] self-hosted test and example [#7548](https://github.com/badges/shields/issues/7548)
- Fix [Nexus] test [#7547](https://github.com/badges/shields/issues/7547)
- [Depfu] Add support for Gitlab [#7475](https://github.com/badges/shields/issues/7475)
- remove heroku from sponsors [#7517](https://github.com/badges/shields/issues/7517)
- replace label in hn-user-karma with U/ [#7500](https://github.com/badges/shields/issues/7500)
- Support [Feedz] response with multiple pages without items [#7476](https://github.com/badges/shields/issues/7476)
- Fix [CodacyCoverage] tests and examples [#7470](https://github.com/badges/shields/issues/7470)
- Fix [CodeFactor] tests and example [#7471](https://github.com/badges/shields/issues/7471)
- Fix [Nexus] tests [#7472](https://github.com/badges/shields/issues/7472)
- Fix c8 coverage [#7468](https://github.com/badges/shields/issues/7468)
- revert decamelize and humanize-string to old versions [#7449](https://github.com/badges/shields/issues/7449)
- Changelog for Release server-2022-01-01 [#7444](https://github.com/badges/shields/issues/7444)
- minor [reddit] improvements [#7436](https://github.com/badges/shields/issues/7436)
- [HackerNews] Show User Karma [#7411](https://github.com/badges/shields/issues/7411)
- ignore @types/node updates (for now) [#7430](https://github.com/badges/shields/issues/7430)
- chore: remove old email from package.json [#7413](https://github.com/badges/shields/issues/7413)
- [YouTube] Drop support for removed dislikes [#7410](https://github.com/badges/shields/issues/7410)
- check engine and peer deps before installing [#7403](https://github.com/badges/shields/issues/7403)
- deps: remove unused babel-plugin-istanbul [#7414](https://github.com/badges/shields/issues/7414)
- change closed GitHub issue color to purple [#7374](https://github.com/badges/shields/issues/7374)
- fix: update filtering logic for useless dep bumps [#7376](https://github.com/badges/shields/issues/7376)
- update [codacy] tests/examples [#7355](https://github.com/badges/shields/issues/7355)
- throw on unexpected keys in `expectBadge()` [#7354](https://github.com/badges/shields/issues/7354)
- restore cors header injection from #4171, run [npm travis] [#4255](https://github.com/badges/shields/issues/4255)
- [GithubPackageJson] Get version from monorepo subfolder package.json [#7350](https://github.com/badges/shields/issues/7350)
- update raster proxy docs [#7348](https://github.com/badges/shields/issues/7348)
- tests: fix Jenkins Coverage service test [#7323](https://github.com/badges/shields/issues/7323)
- tests: fix GitLab Tag service test [#7322](https://github.com/badges/shields/issues/7322)
- tests: increase timeout for tokei gitlab tests [#7275](https://github.com/badges/shields/issues/7275)
- Dependency updates

## server-2023-02-01

- replace [twitter] badge with static fallback [#8842](https://github.com/badges/shields/issues/8842)
- Add various [Polymart] badges [#8811](https://github.com/badges/shields/issues/8811)
- update [githubpipenv] tests/examples [#8797](https://github.com/badges/shields/issues/8797)
- deprecate [apm] service [#8773](https://github.com/badges/shields/issues/8773)
- deprecate lgtm [#8771](https://github.com/badges/shields/issues/8771)
- Dependency updates

## server-2023-01-01

- Breaking change: Routes for GitHub workflows badge have changed. See https://github.com/badges/shields/issues/8671 for more details
- Behaviour change: In this release we fixed a long standing bug. GitHub badges were previously not reading the base URL from the `config.service.baseUri`.
  This release fixes that bug, bringing the code into line with the documented behaviour. This should not cause a behaviour change for most users,
  but users who had previously set a value in `config.service.baseUri` which was previously ignored could see this now have an effect.
  Users who configure their instance using env vars rather than yaml should see no change.
- Send `X-GitHub-Api-Version` when calling [GitHub] v3 API [#8669](https://github.com/badges/shields/issues/8669)
- add [VpmVersion] badge [#8755](https://github.com/badges/shields/issues/8755)
- Add [modrinth] game versions [#8673](https://github.com/badges/shields/issues/8673)
- fix debug logging of undefined query params [#8540](https://github.com/badges/shields/issues/8540), [#8757](https://github.com/badges/shields/issues/8757)
- fall back to classifiers if [pypi] license text is really long [#8690](https://github.com/badges/shields/issues/8690)
- allow passing key to [stackexchange] [#8539](https://github.com/badges/shields/issues/8539)
- Dependency updates

## server-2022-12-01

- fix: support logoColor to shield icons. [#8263](https://github.com/badges/shields/issues/8263)
- handle missing properties array in [VisualStudioMarketplaceVersion] [#8603](https://github.com/badges/shields/issues/8603)
- deprecate [wercker] service [#8642](https://github.com/badges/shields/issues/8642)
- Add [Coincap] Cryptocurrency badges [#8623](https://github.com/badges/shields/issues/8623)
- Add [modrinth] version [#8604](https://github.com/badges/shields/issues/8604)
- [factorio-mod-portal] services [#8625](https://github.com/badges/shields/issues/8625)
- [Coveralls] for GitLab [#8584](https://github.com/badges/shields/issues/8584), [#8644](https://github.com/badges/shields/issues/8644)
- Remove 'suggest badges' feature [#8311](https://github.com/badges/shields/issues/8311)
- Add [modrinth] followers [#8601](https://github.com/badges/shields/issues/8601)
- Update the [modrinth] API to v2 [#8600](https://github.com/badges/shields/issues/8600)
- tidy up [GitHubGist] routes [#8510](https://github.com/badges/shields/issues/8510)
- fix [flathub] version error handling [#8500](https://github.com/badges/shields/issues/8500)
- Dependency updates

## server-2022-11-01

- [Ansible] Add collection badge [#8578](https://github.com/badges/shields/issues/8578)
- [VisualStudioMarketplace] Add support to prerelease extensions version (Issue #8207) [#8561](https://github.com/badges/shields/issues/8561)
- feat: add [GitlabLastCommit] service [#8508](https://github.com/badges/shields/issues/8508)
- fix [swagger] service tests (allow 0 items in array) [#8564](https://github.com/badges/shields/issues/8564)
- fix codecov badge for non-default branch [#8565](https://github.com/badges/shields/issues/8565)
- Add [GitHubLastCommit] by committer badge [#8537](https://github.com/badges/shields/issues/8537)
- [GitHubReleaseDate] - published_at field [#8543](https://github.com/badges/shields/issues/8543)
- Fix [Testspace] with new "untested" value in case_counts array [#8544](https://github.com/badges/shields/issues/8544)
- fix: Support WAITING status for GitHub deployments [#8521](https://github.com/badges/shields/issues/8521)
- [Whatpulse] badge for a user and for a team [#8466](https://github.com/badges/shields/issues/8466)
- deprecate [pkgreview] service [#8499](https://github.com/badges/shields/issues/8499)
- Dependency updates

## server-2022-10-08

- deprecate [criterion] service [#8501](https://github.com/badges/shields/issues/8501)
- fix formatRelativeDate error handling; run [date] [#8497](https://github.com/badges/shields/issues/8497)
- allow/validate bitbucket_username / bitbucket_password in private config schema [#8472](https://github.com/badges/shields/issues/8472)
- fix [pub] points badge test and example [#8498](https://github.com/badges/shields/issues/8498)
- feat: add [GitlabLanguageCount] service [#8377](https://github.com/badges/shields/issues/8377)
- [GitHubGistStars] add GitHub Gist Stars [#8471](https://github.com/badges/shields/issues/8471)
- fix display/search of CII badge examples [#8473](https://github.com/badges/shields/issues/8473)
- feat: add 2022 support to GitHub Hacktoberfest [#8468](https://github.com/badges/shields/issues/8468)
- fix [GitLabCoverage] subgroup bug [#8401](https://github.com/badges/shields/issues/8401)
- implement ruby gems-specific version sort/color functions [#8434](https://github.com/badges/shields/issues/8434)
- Add `rc` to pre-release identifiers [#8435](https://github.com/badges/shields/issues/8435)
- add [GitHub] Number of commits between branches/tags/commits [#8394](https://github.com/badges/shields/issues/8394)
- add [Packagist] dependency version [#8371](https://github.com/badges/shields/issues/8371)
- fix Docker build status invalid response data bug [#8392](https://github.com/badges/shields/issues/8392)
- Dependency updates

## server-2022-09-04

- fix frontend compile for users running on Windows [#8350](https://github.com/badges/shields/issues/8350)
- [DockerSize] Docker image size multi arch [#8290](https://github.com/badges/shields/issues/8290)
- upgrade gatsby [#8334](https://github.com/badges/shields/issues/8334)
- Custom domains for [JitPack] artifacts [#8333](https://github.com/badges/shields/issues/8333)
- fix [dockerstars] service [#8316](https://github.com/badges/shields/issues/8316)
- [BountySource] Fix: Broken Badge generation for decimal activity values [#8315](https://github.com/badges/shields/issues/8315)
- feat: add [gitlabmergerequests] service [#8166](https://github.com/badges/shields/issues/8166)
- Fix terminology for [ROS] version service [#8292](https://github.com/badges/shields/issues/8292)
- feat: add [GitlabStars] service [#8209](https://github.com/badges/shields/issues/8209)
- Fix invalid `rst` format when `alt` or `target` is present [#8275](https://github.com/badges/shields/issues/8275)
- [GithubGistLastCommit] GitHub gist last commit [#8272](https://github.com/badges/shields/issues/8272)
- [GitHub] GitHub file size for a specific branch [#8262](https://github.com/badges/shields/issues/8262)
- Dependency updates

## server-2022-08-01

- [pypi] Add Framework Version Badges support [#8261](https://github.com/badges/shields/issues/8261)
- feat: add [GitlabForks] server [#8208](https://github.com/badges/shields/issues/8208)
- Update PyPI api according to https://warehouse.pypa.io/api-reference/json.html [#8251](https://github.com/badges/shields/issues/8251)
- Add [galaxytoolshed] Activity [#8164](https://github.com/badges/shields/issues/8164)
- [greasyfork] Add Greasy Fork rating badges [#8087](https://github.com/badges/shields/issues/8087)
- refactor(deps): Replace moment with dayjs [#8192](https://github.com/badges/shields/issues/8192)
- add spaces round pipe in [conda] badge [#8189](https://github.com/badges/shields/issues/8189)
- Add [ROS] version service [#8169](https://github.com/badges/shields/issues/8169)
- feat: add [gitlabissues] service [#8108](https://github.com/badges/shields/issues/8108)
- Dependency updates

## server-2022-07-03

- Add [galaxytoolshed] services [#8114](https://github.com/badges/shields/issues/8114)
- fix [gitlab] auth [#8145](https://github.com/badges/shields/issues/8145) [#8162](https://github.com/badges/shields/issues/8162)
- increase cache length on AUR version badge, run [AUR] [#8110](https://github.com/badges/shields/issues/8110)
- Use GraphQL to fix GitHub file count badges [github] [#8112](https://github.com/badges/shields/issues/8112)
- feat: add [gitlab] contributors service [#8084](https://github.com/badges/shields/issues/8084)
- [greasyfork] Add Greasy Fork service badges [#8080](https://github.com/badges/shields/issues/8080)
- Add [gitlablicense] services [#8024](https://github.com/badges/shields/issues/8024)
- [Spack] Package Manager: Update Domain [#8046](https://github.com/badges/shields/issues/8046)
- switch [jitpack] to use latestOk endpoint [#8041](https://github.com/badges/shields/issues/8041)
- Dependency updates

## server-2022-06-01

- Update GitLab logo (2022) [#7984](https://github.com/badges/shields/issues/7984)
- [GitHub] Added milestone property to GitHub issue details service [#7864](https://github.com/badges/shields/issues/7864)
- [Spack] Package Manager: Update Endpoint [#7957](https://github.com/badges/shields/issues/7957)
- Update Chocolatey API endpoint URL [#7952](https://github.com/badges/shields/issues/7952)
- [Flathub]Add downloads badge [#7724](https://github.com/badges/shields/issues/7724)
- replace the outdated Telegram logo with the newest [#7831](https://github.com/badges/shields/issues/7831)
- add [PUB] points badge [#7918](https://github.com/badges/shields/issues/7918)
- add [PUB] popularity badge [#7920](https://github.com/badges/shields/issues/7920)
- add [PUB] likes badge [#7916](https://github.com/badges/shields/issues/7916)
- Dependency updates

## server-2022-05-03

- [OSSFScorecard] Create scorecard badge service [#7687](https://github.com/badges/shields/issues/7687)
- Stringify [githublanguagecount] message [#7881](https://github.com/badges/shields/issues/7881)
- Stringify and trim whitespace from a few services [#7880](https://github.com/badges/shields/issues/7880)
- add labels to Dockerfile [#7862](https://github.com/badges/shields/issues/7862)
- handle missing 'fly-client-ip' [#7814](https://github.com/badges/shields/issues/7814)
- Dependency updates

## server-2022-04-03

- Breaking change: This release updates ioredis from v4 to v5.
  If you are using redis for GitHub token pooling, redis connection strings of the form
  `redis://junkusername:authpassword@example.com:1234` will need to be updated to
  `redis://:authpassword@example.com:1234`. See the
  [ioredis upgrade guide](https://github.com/luin/ioredis/wiki/Upgrading-from-v4-to-v5)
  for further details.
- fix installation issue on npm >= 8.5.5 [#7809](https://github.com/badges/shields/issues/7809)
- two fixes for [packagist] schemas [#7782](https://github.com/badges/shields/issues/7782)
- allow requireCloudflare setting to work when hosted on fly.io [#7781](https://github.com/badges/shields/issues/7781)
- fix [pypi] badges when package has null license [#7761](https://github.com/badges/shields/issues/7761)
- Add a [pub] publisher badge [#7715](https://github.com/badges/shields/issues/7715)
- Switch Steam file size badge to informational color [#7722](https://github.com/badges/shields/issues/7722)
- Make W3C and Youtube documentation links clickable [#7721](https://github.com/badges/shields/issues/7721)
- Improve Wercker examples [#7720](https://github.com/badges/shields/issues/7720)
- Improve Cirrus CI examples [#7719](https://github.com/badges/shields/issues/7719)
- Support [CodeClimate] responses with multiple data items [#7716](https://github.com/badges/shields/issues/7716)
- Delete [TeamCityCoverage] and [BowerVersion] redirectors [#7718](https://github.com/badges/shields/issues/7718)
- Deprecate [Shippable] service [#7717](https://github.com/badges/shields/issues/7717)
- fix: restore version comparison updates from #4173 [#4254](https://github.com/badges/shields/issues/4254)
- [piwheels], filter out versions with no files [#7696](https://github.com/badges/shields/issues/7696)
- set a longer cacheLength on [librariesio] badges [#7692](https://github.com/badges/shields/issues/7692)
- improve python version formatting [#7682](https://github.com/badges/shields/issues/7682)
- Clarify GitHub All Contributors badge [#7690](https://github.com/badges/shields/issues/7690)
- Support [HexPM] packages with no stable release [#7685](https://github.com/badges/shields/issues/7685)
- Add Test at Scale Badge [#7612](https://github.com/badges/shields/issues/7612)
- [packagist] api v2 support [#7681](https://github.com/badges/shields/issues/7681)
- Add [piwheels] version badge [#7656](https://github.com/badges/shields/issues/7656)
- Dependency updates

## server-2022-03-01

- Add [Conan] version service (#7460)
- remove suspended [github] tokens from the pool [#7654](https://github.com/badges/shields/issues/7654)
- generate links without trailing : if port not set [#7655](https://github.com/badges/shields/issues/7655)
- Use the latest build status when checking docs.rs [#7613](https://github.com/badges/shields/issues/7613)
- Remove no download handling and add API warning to [Wordpress] badges [#7606](https://github.com/badges/shields/issues/7606)
- set a higher default cacheLength on rating/star category [#7587](https://github.com/badges/shields/issues/7587)
- Update [amo] to use v4 API, set custom `cacheLength`s [#7586](https://github.com/badges/shields/issues/7586)
- fix(amo): include trailing slash in API call [#7585](https://github.com/badges/shields/issues/7585)
- fix docker image user agent [#7582](https://github.com/badges/shields/issues/7582)
- Delete deprecated Codetally and continuousphp services [#7572](https://github.com/badges/shields/issues/7572)
- Deprecate [Requires] service [#7571](https://github.com/badges/shields/issues/7571)
- [AUR] Fix RPC URL [#7570](https://github.com/badges/shields/issues/7570)
- Dependency updates

## server-2022-02-01

- [Depfu] Add support for Gitlab [#7475](https://github.com/badges/shields/issues/7475)
- replace label in hn-user-karma with U/ [#7500](https://github.com/badges/shields/issues/7500)
- Support [Feedz] response with multiple pages without items [#7476](https://github.com/badges/shields/issues/7476)
- revert decamelize and humanize-string to old versions [#7449](https://github.com/badges/shields/issues/7449)
- Dependency updates

## server-2022-01-01

- minor [reddit] improvements [#7436](https://github.com/badges/shields/issues/7436)
- [HackerNews] Show User Karma [#7411](https://github.com/badges/shields/issues/7411)
- [YouTube] Drop support for removed dislikes [#7410](https://github.com/badges/shields/issues/7410)
- change closed GitHub issue color to purple [#7374](https://github.com/badges/shields/issues/7374)
- restore cors header injection from #4171 [#4255](https://github.com/badges/shields/issues/4255)
- [GithubPackageJson] Get version from monorepo subfolder package.json [#7350](https://github.com/badges/shields/issues/7350)
- Dependency updates

## server-2021-12-01

- Send better user-agent values [#7309](https://github.com/badges/shields/issues/7309)
  Self-hosting users now send a user agent which indicates the server version and starts `shields (self-hosted)/` by default.
  This can be configured using the env var `USER_AGENT_BASE`
- upgrade to node 16 [#7271](https://github.com/badges/shields/issues/7271)
- feat: deprecate dependabot badges [#7274](https://github.com/badges/shields/issues/7274)
- fix: npmversion tagged service test [#7269](https://github.com/badges/shields/issues/7269)
- feat: create new Test Results category [#7218](https://github.com/badges/shields/issues/7218)
- Migration from Request to Got for all HTTP requests is completed in this release
- Dependency updates

## server-2021-11-04

- migrate regularUpdate() from request-->got [#7215](https://github.com/badges/shields/issues/7215)
- migrate github badges to use got instead of request; affects [github librariesio] [#7212](https://github.com/badges/shields/issues/7212)
- deprecate David badges [#7197](https://github.com/badges/shields/issues/7197)
- fix: ensure libraries.io header values are processed numerically [#7196](https://github.com/badges/shields/issues/7196)
- Add authentication for Libraries.io-based badges, run [Libraries Bower] [#7080](https://github.com/badges/shields/issues/7080)
- fixes and tests for pipenv helpers [#7194](https://github.com/badges/shields/issues/7194)
- add GitLab Release badge, run all [GitLab] [#7021](https://github.com/badges/shields/issues/7021)
- set content-length header on badge responses [#7179](https://github.com/badges/shields/issues/7179)
- fix [github] release/tag/download schema [#7170](https://github.com/badges/shields/issues/7170)
- Supported nested groups on [GitLabPipeline] badge [#7159](https://github.com/badges/shields/issues/7159)
- Support nested groups on [GitLabTag] badge [#7158](https://github.com/badges/shields/issues/7158)
- Fixing incorrect JetBrains Plugin rating values for [JetBrainsRating] [#7140](https://github.com/badges/shields/issues/7140)
- support using release or tag name in [GitHub] Release version badge [#7075](https://github.com/badges/shields/issues/7075)
- feat: support branches in sonar badges [#7065](https://github.com/badges/shields/issues/7065)
- Add [Modrinth] total downloads badge [#7132](https://github.com/badges/shields/issues/7132)
- remove [github] admin routes [#7105](https://github.com/badges/shields/issues/7105)
- Dependency updates

## server-2021-10-04

- feat: add 2021 support to GitHub Hacktoberfest [#7086](https://github.com/badges/shields/issues/7086)
- Add [ClearlyDefined] service [#6944](https://github.com/badges/shields/issues/6944)
- handle null licenses in crates.io response schema, run [crates] [#7074](https://github.com/badges/shields/issues/7074)
- [OBS] add Open Build Service service-badge [#6993](https://github.com/badges/shields/issues/6993)
- Correction of badges url in self-hosting configuration with a custom port. Issue 7025 [#7036](https://github.com/badges/shields/issues/7036)
- fix: support gitlab token via env var [#7023](https://github.com/badges/shields/issues/7023)
- Add API-based support for [GitLab] badges, add new GitLab Tag badge [#6988](https://github.com/badges/shields/issues/6988)
- [freecodecamp]: allow + symbol in username [#7016](https://github.com/badges/shields/issues/7016)
- Rename Riot to Element in Matrix badge help [#6996](https://github.com/badges/shields/issues/6996)
- Fixed Reddit Negative Karma Issue [#6992](https://github.com/badges/shields/issues/6992)
- Dependency updates

## server-2021-09-01

- use multi-stage build to reduce size of docker images [#6938](https://github.com/badges/shields/issues/6938)
- remove disableStrictSsl param from [jenkins] [#6887](https://github.com/badges/shields/issues/6887)
- refactor(GitHubCommitActivity): switch to v4/GraphQL API [#6959](https://github.com/badges/shields/issues/6959)
- feat: add freecodecamp badge [#6958](https://github.com/badges/shields/issues/6958)
- use the right version of NPM in docker build [#6941](https://github.com/badges/shields/issues/6941)
- [TwitchExtensionVersion] New badge [#6900](https://github.com/badges/shields/issues/6900)
- enforce strict SSL checking for [coverity] [#6886](https://github.com/badges/shields/issues/6886)
- Update self hosting docs [#6877](https://github.com/badges/shields/issues/6877)
- Support optionalDependencies in [GithubPackageJson] [#6749](https://github.com/badges/shields/issues/6749)
- Dependency updates

## server-2021-08-01

- use v5 API for [AUR] badges [#6836](https://github.com/badges/shields/issues/6836)
- [Sonar] Fix invalid fetch query to sonarqube >=6.6 [#6636](https://github.com/badges/shields/issues/6636)
- Delegate discord logo to simple-icons, which matches the current branding [#6764](https://github.com/badges/shields/issues/6764)
- Re-apply 'Migrate request to got (part 1)' [#6755](https://github.com/badges/shields/issues/6755)
- Delete old deprecated badges [#6756](https://github.com/badges/shields/issues/6756)
- Replace opn-cli with open-cli [#6747](https://github.com/badges/shields/issues/6747)
- Verify that Node 14 is installed in development [#6748](https://github.com/badges/shields/issues/6748)
- Migrate from CommonJS to ESM [#6651](https://github.com/badges/shields/issues/6651)
- Add Wikiapiary Extension Badge [WikiapiaryInstalls] [#6678](https://github.com/badges/shields/issues/6678)
- deprecate [beerpay] [#6708](https://github.com/badges/shields/issues/6708)
- deprecate [microbadger] [#6709](https://github.com/badges/shields/issues/6709)
- [npmsioscore] Support npm score [#6630](https://github.com/badges/shields/issues/6630)
- Add [Weblate] badges [#6677](https://github.com/badges/shields/issues/6677)
- Dependency updates

## server-2021-07-01

- improve [MavenCentral], [MavenMetadata], and [GradlePluginPortal] [#6628](https://github.com/badges/shields/issues/6628)
- fix: fix regex to match [codecov]'s flags [#6655](https://github.com/badges/shields/issues/6655)
- fix usage style [#6638](https://github.com/badges/shields/issues/6638)
- update simple-icons to v5 with by-name lookup backwards compatibility [#6591](https://github.com/badges/shields/issues/6591)
- [GradlePluginPortal] add gradle plugin portal [#6449](https://github.com/badges/shields/issues/6449)
- upgrade some vulnerable packages [#6569](https://github.com/badges/shields/issues/6569)
- increase max-age for download and social badges [#6567](https://github.com/badges/shields/issues/6567)
- Dependency updates

## server-2021-06-01

- Changed creating badges to open a new Window/Tab [#6536](https://github.com/badges/shields/issues/6536)
- Make for-the-badge letter spacing more predictable, and rewrite layout logic [#5754](https://github.com/badges/shields/issues/5754)
- deprecate DockerBuild service [#6529](https://github.com/badges/shields/issues/6529)
- Remove rate limiting functionality [#6513](https://github.com/badges/shields/issues/6513)
- [GitHub] Move to 'funding' category [#5846](https://github.com/badges/shields/issues/5846)
- Add GitHub discussions total badge [GithubTotalDiscussions] [#6472](https://github.com/badges/shields/issues/6472)
- Add optional query parameter (include_prereleases) to [GemVersion] [#6451](https://github.com/badges/shields/issues/6451)
- Add [PingPong] Service [#6327](https://github.com/badges/shields/issues/6327)
- Dependency updates

## server-2021-05-01

- Add setting which allows setting a timeout on HTTP requests
  This is configured with the new `REQUEST_TIMEOUT_SECONDS` setting. If a request takes longer
  than this number of seconds a `408 Request Timeout` response will be returned.
- Deprecate [Bintray] service [#6423](https://github.com/badges/shields/issues/6423)
- Support git hash in [nexus] SNAPSHOT version [#6369](https://github.com/badges/shields/issues/6369)
- Replace 4183C4 with blue [#6366](https://github.com/badges/shields/issues/6366)
- [Youtube] Added channel view count and subscriber count badges [#6333](https://github.com/badges/shields/issues/6333)
- Fix Netlify badge by adding new color schema [#6340](https://github.com/badges/shields/issues/6340)
- [REUSE] Add service badges [#6330](https://github.com/badges/shields/issues/6330)
- Dependency updates

## server-2021-04-01

- Use NPM packages to provide fonts instead of Google Fonts [#6274](https://github.com/badges/shields/issues/6274)
- Prevent duplication of parameters in badge examples [#6272](https://github.com/badges/shields/issues/6272)
- Add docs for all types of releases [#6210](https://github.com/badges/shields/issues/6210)
- refresh self-hosting docs [#6273](https://github.com/badges/shields/issues/6273)
- allow missing 'goal' key in [liberapay] badges [#6258](https://github.com/badges/shields/issues/6258)
- use got to push influx metrics [#6257](https://github.com/badges/shields/issues/6257)
- Dependency updates

## server-2021-03-01

- ensure redirect target path is correctly encoded [#6229](https://github.com/badges/shields/issues/6229)
- [SecurityHeaders] Added a possibility for no follow redirects [#6212](https://github.com/badges/shields/issues/6212)
- catch URL parse error in [endpoint] badge [#6214](https://github.com/badges/shields/issues/6214)
- [Homebrew] Add homebrew downloads badge [#6209](https://github.com/badges/shields/issues/6209)
- update [pkgreview] url [#6189](https://github.com/badges/shields/issues/6189)
- Make [Twitch] a social badge [#6183](https://github.com/badges/shields/issues/6183)
- update [flathub] error handling [#6185](https://github.com/badges/shields/issues/6185)
- Add [Testspace] badges [#6162](https://github.com/badges/shields/issues/6162)
- Dependency updates

## server-2021-02-01

- Docs.rs badge (#6098)
- Fix feedz service in case the package page gets paginated (#6101)
- [Bitbucket] Server Adding Auth Tokens and Resolving Pull Request api … (#6076)
- Dependency updates

## server-2021-01-18

- Gotta start somewhere
