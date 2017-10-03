# Changelog

## [0.5.3] - 03.10.2017
### Changed
- change default node mirror to nodejs.org

## [0.5.2] - 24.09.2017
### Changed
- rename .meta to .adone and add adone.conf.json for adone activator

## [0.5.1] - 23.08.2017
### Added
- add latest flag for node upload

### Changed
- node upload function fixes

## [0.5.0] - 23.08.2017
### Added
- functions for uploading node and avm

## [0.4.0] - 21.08.2017
### Added
- info command
- prefix option for adone install
- patch for FreeBSD Node.js building
- libvirt dep
- v alias for version

### Changed
- install command starts/stops omnitron
- now adone's installation path is ~/.adone by default
- now adone runs under the original user
- rm can remove the current version
- rm can remove all the node/adone versions

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