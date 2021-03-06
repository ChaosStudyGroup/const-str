# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

[Unreleased]: https://github.com/Nugine/const-str/compare/v0.1.2...HEAD

### Added

+ `regex_assert_match` (requires the feature `verify-regex`)
+ `len!`
+ `as_bytes!`
+ `from_bytes!`

## [0.1.2] - 2020-09-11

[0.1.2]: https://github.com/Nugine/const-str/tree/v0.1.2

### Added

+ `no_std` support

### Changed

+ rename feature `regex` to `verify-regex`
+ rename feature `http` to `verify-http`

## [0.1.1] - 2020-09-10

[0.1.1]: https://github.com/Nugine/const-str/tree/v0.1.1

### Added

+ `verified_regex!` (requires the feature `regex`)
+ `verified_header_name!` (requires the feature `http`)

## [0.1.0] - 2020-09-10

[0.1.0]: https://github.com/Nugine/const-str/tree/v0.1.0

### Added

+ `to_lowercase!`
+ `to_uppercase!`
+ `replace!`

