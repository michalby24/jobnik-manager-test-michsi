# Changelog

## [1.0.0-rc.118](https://github.com/michalby24/jobnik-manager-test-michsi/compare/jobnik-manager-v0.1.0-rc.113...jobnik-manager-v1.0.0-rc.118) (2026-01-07)


### ⚠ BREAKING CHANGES

* test
* test

### Features

* test ([5c980dc](https://github.com/michalby24/jobnik-manager-test-michsi/commit/5c980dc1d8d3fa56a9aca3795b4e95a06c40c16f))
* test ([08b1b96](https://github.com/michalby24/jobnik-manager-test-michsi/commit/08b1b96316ff35dec11144f306d079033e136965))
* test ([d436711](https://github.com/michalby24/jobnik-manager-test-michsi/commit/d43671197d0438d9000b2bd94d5e61b00de3beb7))


### Bug Fixes

* test ([b274208](https://github.com/michalby24/jobnik-manager-test-michsi/commit/b274208826255c6adbf028005e295c5a3ba1d7df))


### Miscellaneous Chores

* enforce correct rc version ([519497b](https://github.com/michalby24/jobnik-manager-test-michsi/commit/519497ba1fcd1b30d270909202e4a9704deb7db8))
* enforce correct rc version ([721c42d](https://github.com/michalby24/jobnik-manager-test-michsi/commit/721c42da1c98d1e8c28fa5034bf7da2c26ade97b))
* enforce correct rc version ([3bb47f4](https://github.com/michalby24/jobnik-manager-test-michsi/commit/3bb47f4230ccb0c0a2f1c663026ac08bc7b02129))
* enforce correct rc version ([7c1b12a](https://github.com/michalby24/jobnik-manager-test-michsi/commit/7c1b12a090ad409485c3ad64e9b64ea6602ec91b))
* enforce correct rc version ([b667954](https://github.com/michalby24/jobnik-manager-test-michsi/commit/b6679540d47d6ffa7f7151ee105d07733c3b2a9d))

## [0.1.0-rc.113](https://github.com/michalby24/jobnik-manager-test-michsi/compare/jobnik-manager-v0.1.0...jobnik-manager-v0.1.0-rc.113) (2026-01-07)


### Features

* add comprehensive error handling from OpenAPI spec (MAPCO-7927) ([#89](https://github.com/michalby24/jobnik-manager-test-michsi/issues/89)) ([225789d](https://github.com/michalby24/jobnik-manager-test-michsi/commit/225789d6f16a96df96d7a92fe07a055557aad0e2))
* add cron job functionality for task cleanup (MAPCO-8350) ([#94](https://github.com/michalby24/jobnik-manager-test-michsi/issues/94)) ([8de6cca](https://github.com/michalby24/jobnik-manager-test-michsi/commit/8de6cca114ca076470663b10be037f95c43df02c))
* add isWaiting flag to stage creation for conditional status handling (MAPCO-7905) ([#40](https://github.com/michalby24/jobnik-manager-test-michsi/issues/40)) ([e92d6a0](https://github.com/michalby24/jobnik-manager-test-michsi/commit/e92d6a0efb8bb1127d1f473f2e0e3b05c04af218))
* add metrics for tracking in-progress jobs, stages, and tasks MAPCO-8206 ([#119](https://github.com/michalby24/jobnik-manager-test-michsi/issues/119)) ([4105597](https://github.com/michalby24/jobnik-manager-test-michsi/commit/4105597bfa229a7d233fe780a2a060de374466a8))
* add order field to stages for maintaining execution sequence and update related logic (MAPCO-7897) ([#72](https://github.com/michalby24/jobnik-manager-test-michsi/issues/72)) ([1667e27](https://github.com/michalby24/jobnik-manager-test-michsi/commit/1667e27a73c0512884cbf5be831069544b059936))
* add Prisma instrumentation for enhanced tracing and update related logic ([#76](https://github.com/michalby24/jobnik-manager-test-michsi/issues/76)) ([b35aff9](https://github.com/michalby24/jobnik-manager-test-michsi/commit/b35aff9c55963c770478091c7a8c8f2d97ee63de))
* add startTime and endTime fields to task model (MAPCO-8349) ([#93](https://github.com/michalby24/jobnik-manager-test-michsi/issues/93)) ([2c17e42](https://github.com/michalby24/jobnik-manager-test-michsi/commit/2c17e426aec4c9c56730d8985d7c4710a3846014))
* add userMetadata, creationTime, and updateTime to task and stage schemas as mandatory MAPCO-8576 ([#170](https://github.com/michalby24/jobnik-manager-test-michsi/issues/170)) ([f26268e](https://github.com/michalby24/jobnik-manager-test-michsi/commit/f26268e68d0196aff546a6c2dc0aa2507f4d2627))
* enhance job, stage and task status update descriptions and validations in OpenAPI spec  MAPCO-8783 ([#171](https://github.com/michalby24/jobnik-manager-test-michsi/issues/171)) ([bd1c50b](https://github.com/michalby24/jobnik-manager-test-michsi/commit/bd1c50bebc4a654a7d2b855ac6dea547e397c968))
* enhance tracing attributes in job, stage and task managers  MAPCO-8341 ([#169](https://github.com/michalby24/jobnik-manager-test-michsi/issues/169)) ([3107027](https://github.com/michalby24/jobnik-manager-test-michsi/commit/3107027db577bc277225e95d47c6247d6b4fc23a))
* enhance tracing support with traceparent and tracestate fields in jobs, stages, and tasks (MAPCO-8340) ([#78](https://github.com/michalby24/jobnik-manager-test-michsi/issues/78)) ([b1c78f5](https://github.com/michalby24/jobnik-manager-test-michsi/commit/b1c78f5ca15a2731d1554d9037241fddbc6190b4))
* implement automatic status propagation across job-stage-task hierarchy MAPCO-8785  MAPCO-8784 ([#153](https://github.com/michalby24/jobnik-manager-test-michsi/issues/153)) ([7f80168](https://github.com/michalby24/jobnik-manager-test-michsi/commit/7f8016811d65adeaa75f2491ca5c0a51b55a6fd2))
* implement stage status transition validation and update logic (MAPCO-8803) ([#146](https://github.com/michalby24/jobnik-manager-test-michsi/issues/146)) ([1201f90](https://github.com/michalby24/jobnik-manager-test-michsi/commit/1201f90dd0f7d6c6ec3bd738f2520583afcf70d0))
* integrate jobnik manager with config manager & schemas (MAPCO-7924) ([#116](https://github.com/michalby24/jobnik-manager-test-michsi/issues/116)) ([4c3e716](https://github.com/michalby24/jobnik-manager-test-michsi/commit/4c3e716a12edf020c6c8f6982d514cd46fee9a42))
* introduce v1 API structure with jobs, stages, and tasks endpoints MAPCO-8959 ([#205](https://github.com/michalby24/jobnik-manager-test-michsi/issues/205)) ([dad0bd3](https://github.com/michalby24/jobnik-manager-test-michsi/commit/dad0bd3b7844346dad9754ed77ec2af42728890a))
* Jobnik Manager: project skeleton & core functions ([#34](https://github.com/michalby24/jobnik-manager-test-michsi/issues/34)) ([099bc8d](https://github.com/michalby24/jobnik-manager-test-michsi/commit/099bc8d12c81b18f1d8f76d7658b23bed561e976))


### Bug Fixes

* remove unused previewFeatures from prisma client generator ([2159346](https://github.com/michalby24/jobnik-manager-test-michsi/commit/2159346088de43d409472bcd018f115245798e43))


### Miscellaneous Chores

* enforce correct rc version ([d5f55e6](https://github.com/michalby24/jobnik-manager-test-michsi/commit/d5f55e6e986bfcf6d181797c328073c8e7781a17))

## 0.1.0 (2025-11-16)


### Features

* add comprehensive error handling from OpenAPI spec (MAPCO-7927) ([#89](https://github.com/MapColonies/jobnik-manager/issues/89)) ([225789d](https://github.com/MapColonies/jobnik-manager/commit/225789d6f16a96df96d7a92fe07a055557aad0e2))
* add cron job functionality for task cleanup (MAPCO-8350) ([#94](https://github.com/MapColonies/jobnik-manager/issues/94)) ([8de6cca](https://github.com/MapColonies/jobnik-manager/commit/8de6cca114ca076470663b10be037f95c43df02c))
* add isWaiting flag to stage creation for conditional status handling (MAPCO-7905) ([#40](https://github.com/MapColonies/jobnik-manager/issues/40)) ([e92d6a0](https://github.com/MapColonies/jobnik-manager/commit/e92d6a0efb8bb1127d1f473f2e0e3b05c04af218))
* add metrics for tracking in-progress jobs, stages, and tasks MAPCO-8206 ([#119](https://github.com/MapColonies/jobnik-manager/issues/119)) ([4105597](https://github.com/MapColonies/jobnik-manager/commit/4105597bfa229a7d233fe780a2a060de374466a8))
* add order field to stages for maintaining execution sequence and update related logic (MAPCO-7897) ([#72](https://github.com/MapColonies/jobnik-manager/issues/72)) ([1667e27](https://github.com/MapColonies/jobnik-manager/commit/1667e27a73c0512884cbf5be831069544b059936))
* add Prisma instrumentation for enhanced tracing and update related logic ([#76](https://github.com/MapColonies/jobnik-manager/issues/76)) ([b35aff9](https://github.com/MapColonies/jobnik-manager/commit/b35aff9c55963c770478091c7a8c8f2d97ee63de))
* add startTime and endTime fields to task model (MAPCO-8349) ([#93](https://github.com/MapColonies/jobnik-manager/issues/93)) ([2c17e42](https://github.com/MapColonies/jobnik-manager/commit/2c17e426aec4c9c56730d8985d7c4710a3846014))
* add userMetadata, creationTime, and updateTime to task and stage schemas as mandatory MAPCO-8576 ([#170](https://github.com/MapColonies/jobnik-manager/issues/170)) ([f26268e](https://github.com/MapColonies/jobnik-manager/commit/f26268e68d0196aff546a6c2dc0aa2507f4d2627))
* enhance job, stage and task status update descriptions and validations in OpenAPI spec  MAPCO-8783 ([#171](https://github.com/MapColonies/jobnik-manager/issues/171)) ([bd1c50b](https://github.com/MapColonies/jobnik-manager/commit/bd1c50bebc4a654a7d2b855ac6dea547e397c968))
* enhance tracing attributes in job, stage and task managers  MAPCO-8341 ([#169](https://github.com/MapColonies/jobnik-manager/issues/169)) ([3107027](https://github.com/MapColonies/jobnik-manager/commit/3107027db577bc277225e95d47c6247d6b4fc23a))
* enhance tracing support with traceparent and tracestate fields in jobs, stages, and tasks (MAPCO-8340) ([#78](https://github.com/MapColonies/jobnik-manager/issues/78)) ([b1c78f5](https://github.com/MapColonies/jobnik-manager/commit/b1c78f5ca15a2731d1554d9037241fddbc6190b4))
* implement automatic status propagation across job-stage-task hierarchy MAPCO-8785  MAPCO-8784 ([#153](https://github.com/MapColonies/jobnik-manager/issues/153)) ([7f80168](https://github.com/MapColonies/jobnik-manager/commit/7f8016811d65adeaa75f2491ca5c0a51b55a6fd2))
* implement stage status transition validation and update logic (MAPCO-8803) ([#146](https://github.com/MapColonies/jobnik-manager/issues/146)) ([1201f90](https://github.com/MapColonies/jobnik-manager/commit/1201f90dd0f7d6c6ec3bd738f2520583afcf70d0))
* integrate jobnik manager with config manager & schemas (MAPCO-7924) ([#116](https://github.com/MapColonies/jobnik-manager/issues/116)) ([4c3e716](https://github.com/MapColonies/jobnik-manager/commit/4c3e716a12edf020c6c8f6982d514cd46fee9a42))
* Jobnik Manager: project skeleton & core functions ([#34](https://github.com/MapColonies/jobnik-manager/issues/34)) ([099bc8d](https://github.com/MapColonies/jobnik-manager/commit/099bc8d12c81b18f1d8f76d7658b23bed561e976))


### Bug Fixes

* remove unused previewFeatures from prisma client generator ([2159346](https://github.com/MapColonies/jobnik-manager/commit/2159346088de43d409472bcd018f115245798e43))
