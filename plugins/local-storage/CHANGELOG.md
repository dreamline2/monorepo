# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [8.0.0](https://github.com/verdaccio/monorepo/compare/v8.0.0-next.4...v8.0.0) (2019-08-22)

**Note:** Version bump only for package @verdaccio/local-storage





# [8.0.0-next.4](https://github.com/verdaccio/monorepo/compare/v8.0.0-next.3...v8.0.0-next.4) (2019-08-18)

**Note:** Version bump only for package @verdaccio/local-storage





# [8.0.0-next.3](https://github.com/verdaccio/monorepo/compare/v8.0.0-next.2...v8.0.0-next.3) (2019-08-16)


### Bug Fixes

* restore closure ([32b9d7e](https://github.com/verdaccio/monorepo/commit/32b9d7e))
* **build:** error on types for fs callback ([cc35acb](https://github.com/verdaccio/monorepo/commit/cc35acb))
* Add DATE and VERSION in search result ([e352b75](https://github.com/verdaccio/monorepo/commit/e352b75))
* avoid open write stream if resource exist [#1191](https://github.com/verdaccio/monorepo/issues/1191) ([f041d3f](https://github.com/verdaccio/monorepo/commit/f041d3f))
* bug fixing integration ([6c75ac8](https://github.com/verdaccio/monorepo/commit/6c75ac8))
* build before publish ([cd6c7ff](https://github.com/verdaccio/monorepo/commit/cd6c7ff))
* check whether path exist before return result ([a4d2af1](https://github.com/verdaccio/monorepo/commit/a4d2af1))
* flow issues ([f42a284](https://github.com/verdaccio/monorepo/commit/f42a284))
* ignore flow on this one, we need it ([c8e0b2b](https://github.com/verdaccio/monorepo/commit/c8e0b2b))
* local storage requires package.json file for read, save and create all the time ([33c847b](https://github.com/verdaccio/monorepo/commit/33c847b))
* migration from main repository merge [#306](https://github.com/verdaccio/monorepo/issues/306) ([8fbe86e](https://github.com/verdaccio/monorepo/commit/8fbe86e))
* missing callback ([abfc422](https://github.com/verdaccio/monorepo/commit/abfc422))
* missing error code ([7121939](https://github.com/verdaccio/monorepo/commit/7121939))
* move to local storage the fs location handler ([3b12083](https://github.com/verdaccio/monorepo/commit/3b12083))
* mtimeMs is not backward compatible ([c6f74eb](https://github.com/verdaccio/monorepo/commit/c6f74eb))
* remove temp file whether is emtpy and fails ([655102f](https://github.com/verdaccio/monorepo/commit/655102f))
* remove uncessary async ([3e3e3a6](https://github.com/verdaccio/monorepo/commit/3e3e3a6))
* remove unused parameters ([554e301](https://github.com/verdaccio/monorepo/commit/554e301))
* restore build path ([4902042](https://github.com/verdaccio/monorepo/commit/4902042))
* return time as milliseconds ([15467ba](https://github.com/verdaccio/monorepo/commit/15467ba))
* sync after set secret ([2abae4f](https://github.com/verdaccio/monorepo/commit/2abae4f))
* temp files are written into the storage ([89a1dc8](https://github.com/verdaccio/monorepo/commit/89a1dc8))
* unit test ([995a27c](https://github.com/verdaccio/monorepo/commit/995a27c))
* update @verdaccio/file-locking@1.0.0 ([9bd36f0](https://github.com/verdaccio/monorepo/commit/9bd36f0))
* update lodash types ([184466c](https://github.com/verdaccio/monorepo/commit/184466c))


### Features

* token support with level.js ([#168](https://github.com/verdaccio/monorepo/issues/168)) ([ca877ff](https://github.com/verdaccio/monorepo/commit/ca877ff))
* **build:** standardize build ([33fe090](https://github.com/verdaccio/monorepo/commit/33fe090))
* change new db name to verdaccio ([#83](https://github.com/verdaccio/monorepo/issues/83)) ([edfca9f](https://github.com/verdaccio/monorepo/commit/edfca9f))
* drop node v6 support ([664f288](https://github.com/verdaccio/monorepo/commit/664f288))
* implement search ([2e2bb32](https://github.com/verdaccio/monorepo/commit/2e2bb32))
* migrate to typescript ([c439d25](https://github.com/verdaccio/monorepo/commit/c439d25))
* update database method with callbacks ([ef202a9](https://github.com/verdaccio/monorepo/commit/ef202a9))
* update minor dependencies ([007b026](https://github.com/verdaccio/monorepo/commit/007b026))





# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [2.3.0](https://github.com/verdaccio/local-storage/compare/v2.2.1...v2.3.0) (2019-08-13)


### Bug Fixes

* restore closure ([8ec27f2](https://github.com/verdaccio/local-storage/commit/8ec27f2))


### Features

* add logging for each method ([3c915c7](https://github.com/verdaccio/local-storage/commit/3c915c7))
* token support with level.js ([#168](https://github.com/verdaccio/local-storage/issues/168)) ([16727bd](https://github.com/verdaccio/local-storage/commit/16727bd))

### [2.2.1](https://github.com/verdaccio/local-storage/compare/v2.2.0...v2.2.1) (2019-06-30)


### Bug Fixes

* **build:** error on types for fs callback ([774d808](https://github.com/verdaccio/local-storage/commit/774d808))



## [2.2.0](https://github.com/verdaccio/local-storage/compare/v2.1.0...v2.2.0) (2019-06-30)


### Features

* **build:** standardize build ([eba832e](https://github.com/verdaccio/local-storage/commit/eba832e))



# [2.1.0](https://github.com/verdaccio/local-storage/compare/v2.0.0...v2.1.0) (2019-03-29)


### Bug Fixes

* remove uncessary async ([23a09f3](https://github.com/verdaccio/local-storage/commit/23a09f3))


### Features

* drop node v6 support ([ef548e0](https://github.com/verdaccio/local-storage/commit/ef548e0))



# [2.0.0](https://github.com/verdaccio/local-storage/compare/v2.0.0-beta.3...v2.0.0) (2019-03-29)



<a name="2.0.0-beta.3"></a>
# [2.0.0-beta.3](https://github.com/verdaccio/local-storage/compare/v2.0.0-beta.2...v2.0.0-beta.3) (2019-02-24)


### Bug Fixes

* update [@verdaccio](https://github.com/verdaccio)/file-locking@1.0.0 ([587245d](https://github.com/verdaccio/local-storage/commit/587245d))



<a name="2.0.0-beta.2"></a>
# [2.0.0-beta.2](https://github.com/verdaccio/local-storage/compare/v2.0.0-beta.1...v2.0.0-beta.2) (2019-02-24)


### Bug Fixes

* avoid open write stream if resource exist [#1191](https://github.com/verdaccio/local-storage/issues/1191) ([b13904a](https://github.com/verdaccio/local-storage/commit/b13904a))
* package.json to reduce vulnerabilities ([97e9dc3](https://github.com/verdaccio/local-storage/commit/97e9dc3))



<a name="2.0.0-beta.1"></a>
# [2.0.0-beta.1](https://github.com/verdaccio/local-storage/compare/v2.0.0-beta.0...v2.0.0-beta.1) (2019-02-03)



<a name="2.0.0-beta.0"></a>
# [2.0.0-beta.0](https://github.com/verdaccio/local-storage/compare/v1.2.0...v2.0.0-beta.0) (2019-02-01)


### Bug Fixes

* **deps:** update dependency lodash to v4.17.11 ([682616a](https://github.com/verdaccio/local-storage/commit/682616a))


### Features

* custom storage location ([b1423cd](https://github.com/verdaccio/local-storage/commit/b1423cd))
* migrate to typescript ([fe8344b](https://github.com/verdaccio/local-storage/commit/fe8344b))


### BREAKING CHANGES

* we change from boolean value to string within the config file



<a name="1.2.0"></a>
# [1.2.0](https://github.com/verdaccio/local-storage/compare/v1.1.3...v1.2.0) (2018-08-25)


### Features

* change new db name to verdaccio ([#83](https://github.com/verdaccio/local-storage/issues/83)) ([143977d](https://github.com/verdaccio/local-storage/commit/143977d))



<a name="1.1.3"></a>
## [1.1.3](https://github.com/verdaccio/local-storage/compare/v1.1.2...v1.1.3) (2018-07-15)


### Bug Fixes

* remove unused parameters ([3ce374a](https://github.com/verdaccio/local-storage/commit/3ce374a))



<a name="1.1.2"></a>
## [1.1.2](https://github.com/verdaccio/local-storage/compare/v1.1.1...v1.1.2) (2018-06-09)


### Bug Fixes

* return time as milliseconds ([c98be85](https://github.com/verdaccio/local-storage/commit/c98be85))



<a name="1.1.1"></a>
## [1.1.1](https://github.com/verdaccio/local-storage/compare/v1.1.0...v1.1.1) (2018-06-08)


### Bug Fixes

* check whether path exist before return result ([cb5d4ef](https://github.com/verdaccio/local-storage/commit/cb5d4ef))



<a name="1.1.0"></a>
# [1.1.0](https://github.com/verdaccio/local-storage/compare/v1.0.3...v1.1.0) (2018-06-08)


### Bug Fixes

* **deps:** update dependency async to v2.6.1 ([487b095](https://github.com/verdaccio/local-storage/commit/487b095))


### Features

* implement search ([f884a24](https://github.com/verdaccio/local-storage/commit/f884a24))



<a name="0.2.0"></a>
# [0.2.0](https://github.com/verdaccio/local-storage/compare/v0.1.4...v0.2.0) (2018-01-17)


### Features

* update minor dependencies ([92daa81](https://github.com/verdaccio/local-storage/commit/92daa81))



<a name="0.1.4"></a>
## [0.1.4](https://github.com/verdaccio/local-storage/compare/v0.1.3...v0.1.4) (2018-01-17)


### Bug Fixes

* remove temp file whether is emtpy and fails ([593e162](https://github.com/verdaccio/local-storage/commit/593e162))
* unit test ([2573f30](https://github.com/verdaccio/local-storage/commit/2573f30))