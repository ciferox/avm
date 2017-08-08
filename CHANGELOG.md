# Changelog

## [0.2.1] - 08.07.2017
## Changed
- add checks if node/adone/avm downloading is not failed
- use resolved versions in node/adone links

## [0.2.0] - 06.07.2017
### Added
- add libcurl4-openssl-dev dependency to deps

### Changed
- deps listing

## [0.1.0] - 02.07.2017
### Added
- adone link command
- adone rm-link command
- node/adone download command
- delete target directory before downloading
- force flag
- install adone as a global node module to require adone from everywhere

### Changed
- install = download + activate

### Removed
- force-install/force-activate/download flags