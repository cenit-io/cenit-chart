# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

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

[1.1.0]: https://github.com/cenit-io/cenit-chart/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/cenit-io/cenit-chart/releases/tag/v1.0.0