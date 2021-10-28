# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.8.2] - 2021-10-27

### Fix

- Add SKIP_DB_INITIALIZATION environment variable to frontend

## [1.8.1] - 2021-10-26

### Fix

- Delete name of storageclass

## [1.8.0] - 2021-10-26

### Added

- Add SKIP_DB_INITIALIZATION environment variable
- Add check csi drive

## [1.7.0] - 2021-10-24

### Added

- Add support for "switch" deploy of backend and fronted
- Add support for EBS CSI Drive

## [1.6.0] - 2021-10-21

### Added

- Add replica specification

## [1.5.2] - 2021-10-21

### Fixed

- Fix TENANT_CREATION_DISABLED environment variable in template

## [1.5.1] - 2021-08-10

### Fixed

- Add svc to UI

## [1.5.0] - 2021-08-10

### Added

- Mongo UI

### Fixed

- Fix bug about secret key


## [1.4.0] - 2021-07-21

### Added

- Custom images
- Private repository

## [1.3.0] - 2021-06-21

### Changed

- Update Docker image references values

## [1.2.1] - 2021-05-26

### Removed

-Duplicated values

## [1.2.0] - 2021-05-25

### Added

- Add support to configure smtp protocol
- Add support to specify docker image version

### Changed

- Reorder MongoDB services configurations
- Sustitute Gmail configuration by smtp configurations

## [1.1.0] - 2021-05-6

### Added

- Add support to use ClusterIp service to publish service

## [1.0.0] - 2021-05-5

### Added

- An an stable orchestration of containers:
  - MongoDB
  - RabbitMQ
  - Redis
  - Cenit
- Export service using LoadBalancer
- Default values if not specified by user

[1.8.2]: https://github.com/cenit-io/cenit-chart/compare/v1.8.1...v1.8.2
[1.8.1]: https://github.com/cenit-io/cenit-chart/compare/v1.8.0...v1.8.1
[1.8.0]: https://github.com/cenit-io/cenit-chart/compare/v1.7.0...v1.8.0
[1.7.0]: https://github.com/cenit-io/cenit-chart/compare/v1.6.0...v1.7.0
[1.6.0]: https://github.com/cenit-io/cenit-chart/compare/v1.5.2...v1.6.0
[1.5.2]: https://github.com/cenit-io/cenit-chart/compare/v1.5.1...v1.5.2
[1.5.1]: https://github.com/cenit-io/cenit-chart/compare/v1.5.0...v1.5.1
[1.5.0]: https://github.com/cenit-io/cenit-chart/compare/v1.4.0...v1.5.0
[1.4.0]: https://github.com/cenit-io/cenit-chart/compare/v1.3.0...v1.4.0
[1.3.0]: https://github.com/cenit-io/cenit-chart/compare/v1.2.1...v1.3.0
[1.2.1]: https://github.com/cenit-io/cenit-chart/compare/v1.2.0...v1.2.1
[1.2.0]: https://github.com/cenit-io/cenit-chart/compare/v1.2.0...v1.1.0
[1.1.0]: https://github.com/cenit-io/cenit-chart/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/cenit-io/cenit-chart/releases/tag/v1.0.0