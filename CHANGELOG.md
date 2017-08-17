# Changelog

## [0.3.0] - 17.08.2017
### Added
- adone downloader/activator now uses the currently used node.js version

### Changed
- adone ls output

## [0.2.2] - 11.08.2017
### Added
- add libssl-dev dependency

## [0.2.1] - 08.08.2017
### Changed
- add checks if node/adone/avm downloading is not failed
- use resolved versions in node/adone links

## [0.2.0] - 06.08.2017
### Added
- add libcurl4-openssl-dev dependency to deps

### Changed
- deps listing

## [0.1.0] - 02.08.2017
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