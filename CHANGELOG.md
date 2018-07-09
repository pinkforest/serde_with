# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

* `unwrap_or_skip` allows to transparently serialize the inner part of a `Some(T)`

## [0.2.1]

### Added

* Double Option pattern to differentiate between missing, unset, or existing value
* `with_prefix!` macro, which puts a prefix on every struct field

## [0.2.0]

### Added

* Add chrono support: Deserialize timestamps from int, float, and string
* Serialization of embedded JSON strings
* De/Serialization using `Display` and `FromStr` implementations
* String-based collections using `Display` and `FromStr`, allows to deserialize "#foo,#bar"

## [0.1.0]

### Added

* Reserve name on crates.io