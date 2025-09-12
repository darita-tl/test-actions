# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [0.12.1](https://github.com/businessinsider/cms-apis-monorepo/compare/cms-stories-api-v0.12.0...cms-stories-api-v0.12.1) (2025-09-09)


### Bug Fixes

* DC-8343: Update dockerfile to copy over the missing grpc proto files ([#51](https://github.com/businessinsider/cms-apis-monorepo/issues/51)) ([9167095](https://github.com/businessinsider/cms-apis-monorepo/commit/9167095ec1fee3094b5b50bdc8c08b165f6d6099))

## [0.12.0](https://github.com/businessinsider/cms-apis-monorepo/compare/cms-stories-api-v0.11.0...cms-stories-api-v0.12.0) (2025-09-09)


### Features

* DC-8343: Migrate publishing into cms-stories-api ([#44](https://github.com/businessinsider/cms-apis-monorepo/issues/44)) ([6c3a55b](https://github.com/businessinsider/cms-apis-monorepo/commit/6c3a55bc267cad83dc7fa4215f153f69437a3588)), closes [#43](https://github.com/businessinsider/cms-apis-monorepo/issues/43)


### Bug Fixes

* DC-9999: simpler encoding check for theme.meta ([#49](https://github.com/businessinsider/cms-apis-monorepo/issues/49)) ([498f3e4](https://github.com/businessinsider/cms-apis-monorepo/commit/498f3e4b40c1ece21921247ecc09ed1b78080f2b))

## [0.11.0](https://github.com/businessinsider/cms-apis-monorepo/compare/cms-stories-api-v0.10.0...cms-stories-api-v0.11.0) (2025-09-08)


### Bug Fixes

* DC-8442 and DC-8443 -  Fix to allow collection pages theme and fix unscheduled logic ([#46](https://github.com/businessinsider/cms-apis-monorepo/issues/46)) ([3fc7bd6](https://github.com/businessinsider/cms-apis-monorepo/commit/3fc7bd665287030679276556987df4d626d512f5))

## [0.10.0](https://github.com/businessinsider/cms-apis-monorepo/compare/cms-stories-api-v0.9.0...cms-stories-api-v0.10.0) (2025-09-03)

## [0.9.0](https://github.com/businessinsider/cms-apis-monorepo/compare/cms-stories-api-v0.8.0...cms-stories-api-v0.9.0) (2025-09-03)


### Bug Fixes

* DC-8411 - Set unused to be false for normal updates ([#38](https://github.com/businessinsider/cms-apis-monorepo/issues/38)) ([41d2b9a](https://github.com/businessinsider/cms-apis-monorepo/commit/41d2b9ad1c2793c4cfcd0de6bda7da54acdde2cd))

## [0.8.0](https://github.com/businessinsider/cms-apis-monorepo/compare/cms-stories-api-v0.7.0...cms-stories-api-v0.8.0) (2025-09-02)


### Features

* Base setup for using tests with Mongo ([#31](https://github.com/businessinsider/cms-apis-monorepo/issues/31)) ([6e9b4a8](https://github.com/businessinsider/cms-apis-monorepo/commit/6e9b4a82fcd375eda0de8dc061017de0d420cd8d))
* DC-8321 - Add scheduler with status tracking ([#33](https://github.com/businessinsider/cms-apis-monorepo/issues/33)) ([5b7df74](https://github.com/businessinsider/cms-apis-monorepo/commit/5b7df74cc1bc6739d35981e075403e2a19f28f60))
* DC-8405:  Add tests for different services & e2e test for story workflow ([#34](https://github.com/businessinsider/cms-apis-monorepo/issues/34)) ([b54a55f](https://github.com/businessinsider/cms-apis-monorepo/commit/b54a55f7ed695226136284e79c17de0fdbf8a13e))

## [0.7.0](https://github.com/businessinsider/cms-apis-monorepo/compare/cms-stories-api-v0.6.0...cms-stories-api-v0.7.0) (2025-08-21)


### Bug Fixes

* DC-8356: add missing snapshots for update story actions ([#29](https://github.com/businessinsider/cms-apis-monorepo/issues/29)) ([3c12cf2](https://github.com/businessinsider/cms-apis-monorepo/commit/3c12cf22f501336c9f48e946311c847e62bb2c1e))

## [0.6.0](https://github.com/businessinsider/cms-apis-monorepo/compare/cms-stories-api-v0.5.0...cms-stories-api-v0.6.0) (2025-08-20)


### Features

* DC-8342: Implement Copy Story Endpoint ([#25](https://github.com/businessinsider/cms-apis-monorepo/issues/25)) ([ce2f363](https://github.com/businessinsider/cms-apis-monorepo/commit/ce2f3636f2c781421bd692e751edfc315f54f178))
* DC-8356: Migrate the update story endpoint ([#24](https://github.com/businessinsider/cms-apis-monorepo/issues/24)) ([2a90e43](https://github.com/businessinsider/cms-apis-monorepo/commit/2a90e4387d027c6619557363246e9082e54c7ae5))

## [0.5.0](https://github.com/businessinsider/cms-apis-monorepo/compare/cms-stories-api-v0.4.0...cms-stories-api-v0.5.0) (2025-08-18)


### Features

* DC-8342: Add Event schema and implement on Create Story ([#20](https://github.com/businessinsider/cms-apis-monorepo/issues/20)) ([2787019](https://github.com/businessinsider/cms-apis-monorepo/commit/278701923d343ddbe082511f0777c2e9e4e29c4b))
* DC-8342: Adds the Delete Story endpoint ([#22](https://github.com/businessinsider/cms-apis-monorepo/issues/22)) ([e4f9e15](https://github.com/businessinsider/cms-apis-monorepo/commit/e4f9e1560dbcbcbbedddbee011c0b2998b8564eb))


### Bug Fixes

* DC-8342 - Change how nanos are calculated and fill update event on create story ([#21](https://github.com/businessinsider/cms-apis-monorepo/issues/21)) ([c95a771](https://github.com/businessinsider/cms-apis-monorepo/commit/c95a7716384387629f51c3b5fb0b140802ff170e))

## [0.4.0](https://github.com/businessinsider/cms-apis-monorepo/compare/cms-stories-api-v0.3.0...cms-stories-api-v0.4.0) (2025-08-13)


### Features

* DC-8318: Add new endpoints for Preview, Compare Versions & Wire Downloads ([#16](https://github.com/businessinsider/cms-apis-monorepo/issues/16)) ([eff0ca6](https://github.com/businessinsider/cms-apis-monorepo/commit/eff0ca6e9ec8fb7b609876bf54519f39305b573a))

## [0.3.0](https://github.com/businessinsider/cms-apis-monorepo/compare/cms-stories-api-v0.2.0...cms-stories-api-v0.3.0) (2025-08-13)


### Features

* DC-8320: Migrate the gRPC story read endpoints and add JWT auth strategy ([#12](https://github.com/businessinsider/cms-apis-monorepo/issues/12)) ([9ed8474](https://github.com/businessinsider/cms-apis-monorepo/commit/9ed847413214bc93aaa1bfdebcaa94197f3b0387))


### Bug Fixes

* DC-8352: Standardize story payload by removing extra fields and normalizing popular videos ([#15](https://github.com/businessinsider/cms-apis-monorepo/issues/15)) ([5f18388](https://github.com/businessinsider/cms-apis-monorepo/commit/5f18388ba39c65a54e978fe0337a53002dcab7bb))
* DC-8352: Update timestamp format to match what Muse expects ([#17](https://github.com/businessinsider/cms-apis-monorepo/issues/17)) ([1c23d0b](https://github.com/businessinsider/cms-apis-monorepo/commit/1c23d0b538a8a274f41f0463fc415dd574b6757e))

## [0.2.0](https://github.com/businessinsider/cms-apis-monorepo/compare/cms-stories-api-v0.1.0...cms-stories-api-v0.2.0) (2025-08-05)

## [0.1.0](https://github.com/businessinsider/cms-apis-monorepo/compare/cms-stories-api-v0.0.3...cms-stories-api-v0.1.0) (2025-07-31)


### Features

* DC-8293: Add base entities needed for Stories ([#6](https://github.com/businessinsider/cms-apis-monorepo/issues/6)) ([489e62d](https://github.com/businessinsider/cms-apis-monorepo/commit/489e62daabecc161ca7ecc91af25207922128ed2))
* DC-8319: Stories Search Endpoint ([#4](https://github.com/businessinsider/cms-apis-monorepo/issues/4)) ([0d1bea8](https://github.com/businessinsider/cms-apis-monorepo/commit/0d1bea85f2feb4c1996f4491aae677f46b2eef30))

### [0.0.3](https://github.com/businessinsider/cms-apis-monorepo/compare/cms-stories-api-v0.0.2...cms-stories-api-v0.0.3) (2025-07-24)


### Features

* DC-8317: Enable new logging and tracing utils to share between apps ([#3](https://github.com/businessinsider/cms-apis-monorepo/issues/3)) ([35b9882](https://github.com/businessinsider/cms-apis-monorepo/commit/35b9882aada100b805ef163de07a5250d7336127))


### Bug Fixes

* add changelog link on current tag to keep it consistent ([23d753d](https://github.com/businessinsider/cms-apis-monorepo/commit/23d753df866d03cf7295fdba076f302d30b8d2f6))

### [0.0.2](https://github.com/businessinsider/cms-apis-monorepo/releases/tag/cms-stories-api-v0.0.2) (2025-07-22)


### Features

* DC-8301 - Add release workflow with conventional commit support ([#2](https://github.com/businessinsider/cms-apis-monorepo/issues/2)) ([332abcb](https://github.com/businessinsider/cms-apis-monorepo/commit/332abcbcc3853a7172879373e3cb656f31432085))
