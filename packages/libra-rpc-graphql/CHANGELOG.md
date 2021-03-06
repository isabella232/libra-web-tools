# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

<!-- ## [Unreleased] -->

## [2.6.0]

### Changed

- `server` is no longer available in this package, it can now be imported through `@shopify/libra-rpc-graphql-server` ([#25][https://github.com/shopify/libra-web-tools/pull/25])

## [2.5.2]

### Fixed

- RPC metadata now only appended to non-null results ([#20](https://github.com/Shopify/libra-web-tools/pull/20))

## [2.5.0]

### Fixed

- Fixed some core RPC API naming issues (i.e., `get_account_state` -> `get_account`) ([#19](https://github.com/Shopify/libra-web-tools/pull/19))

## [2.4.0]

### Added

- Adding account state to test query ([#18](https://github.com/Shopify/libra-web-tools/pull/18))

## [2.3.1]

### Fixed

- Resolver address injection on null payloads and some misc server fixes ([#17](https://github.com/Shopify/libra-web-tools/pull/17))

## [2.3.0]

### Changed

- Added ability to inject a express app to enable custom configuration ([#16](https://github.com/Shopify/libra-web-tools/pull/16))

## [2.2.0]

### Added

- Added a new `server` module to simplify creating a playground server with `startExpress()` ([#14](https://github.com/Shopify/libra-web-tools/pull/14))

## [2.1.0]

### Changed

- Adding all the missing exports (`client`, `link`, `types`) ([#13](https://github.com/Shopify/libra-web-tools/pull/13))

## [2.0.0]

### Changed

- Now using node v10 ([#12](https://github.com/Shopify/libra-web-tools/pull/12))

## [1.0.0]

### Added

- `@shopify/libra-rpc-graphql` package
