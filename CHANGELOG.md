# Change log

All notable changes to this project will be documented in this file. The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](http://semver.org).

## [v6.0.0](https://github.com/puppetlabs/puppetlabs-wsus_client/tree/v6.0.0) (2023-04-20)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-wsus_client/compare/v5.0.1...v6.0.0)

### Changed

- \(CONT-804\) Add Support for Puppet 8 / Drop Support for Puppet 6 [\#204](https://github.com/puppetlabs/puppetlabs-wsus_client/pull/204) ([david22swan](https://github.com/david22swan))

## [v5.0.1](https://github.com/puppetlabs/puppetlabs-wsus_client/tree/v5.0.1) (2023-04-20)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-wsus_client/compare/v5.0.0...v5.0.1)

### Fixed

- \(CONT-860\) Update registry dependency [\#202](https://github.com/puppetlabs/puppetlabs-wsus_client/pull/202) ([LukasAud](https://github.com/LukasAud))

## [v5.0.0](https://github.com/puppetlabs/puppetlabs-wsus_client/tree/v5.0.0) (2023-03-09)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-wsus_client/compare/v4.0.0...v5.0.0)

### Changed

- \(gh-cat-9\) Add specific data types [\#181](https://github.com/puppetlabs/puppetlabs-wsus_client/pull/181) ([LukasAud](https://github.com/LukasAud))

### Added

- pdksync - \(FM-8922\) - Add Support for Windows 2022 [\#175](https://github.com/puppetlabs/puppetlabs-wsus_client/pull/175) ([david22swan](https://github.com/david22swan))

### Fixed

- \(MAINT\) Drop support for Windows 7, 8, 2008 \(Server\) and 2008 R2 \(Server\) [\#185](https://github.com/puppetlabs/puppetlabs-wsus_client/pull/185) ([jordanbreen28](https://github.com/jordanbreen28))
- adjusted upper limit [\#184](https://github.com/puppetlabs/puppetlabs-wsus_client/pull/184) ([prolixalias](https://github.com/prolixalias))

## [v4.0.0](https://github.com/puppetlabs/puppetlabs-wsus_client/tree/v4.0.0) (2021-03-01)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-wsus_client/compare/v3.2.0...v4.0.0)

### Changed

- pdksync - Remove Puppet 5 from testing and bump minimal version to 6.0.0 [\#148](https://github.com/puppetlabs/puppetlabs-wsus_client/pull/148) ([carabasdaniel](https://github.com/carabasdaniel))

## [v3.2.0](https://github.com/puppetlabs/puppetlabs-wsus_client/tree/v3.2.0) (2021-02-18)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-wsus_client/compare/v3.1.0...v3.2.0)

### Added

- pdksync - \(IAC-973\) - Update travis/appveyor to run on new default branch `main` [\#134](https://github.com/puppetlabs/puppetlabs-wsus_client/pull/134) ([david22swan](https://github.com/david22swan))

## [v3.1.0](https://github.com/puppetlabs/puppetlabs-wsus_client/tree/v3.1.0) (2020-01-06)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-wsus_client/compare/v3.0.0...v3.1.0)

### Added

- Update metadata.json [\#114](https://github.com/puppetlabs/puppetlabs-wsus_client/pull/114) ([sootysec](https://github.com/sootysec))

## [v3.0.0](https://github.com/puppetlabs/puppetlabs-wsus_client/tree/v3.0.0) (2019-10-18)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-wsus_client/compare/v2.0.0...v3.0.0)

### Fixed

- \(maint\) - Fixes to HISTORY.md and metadata.json [\#110](https://github.com/puppetlabs/puppetlabs-wsus_client/pull/110) ([david22swan](https://github.com/david22swan))

## v2.0.0

### Summary

Major release which removes support for older versions of Puppet-Agent.

### Features

- Add Puppet Strings docs [MODULES-9421](https://tickets.puppetlabs.com/browse/MODULES-9421)

### Bugfixes

- Update acceptance tests to improve the quality and efficiency [MODULES-9411](https://tickets.puppetlabs.com/browse/MODULES-9411)

### Changed

- Raise lower Puppet bound to 5.5.10 [MODULES-9414](https://tickets.puppetlabs.com/browse/MODULES-9414)

## 2018-10-31 - Supported Release 1.1.0
### Summary

A feature release for Puppet 5, Puppet6, Windows Server 2016, and Windows Desktop Operating Systems

### Bugfixes

- Allow module to be used with Stdlib v6 - [MODULES-7705](https://tickets.puppetlabs.com/browse/MODULES-7705)

### Features

- Add support for Puppet 5 - [MODULES-5144](https://tickets.puppetlabs.com/browse/MODULES-5144)
- Add support for Puppet 6 - [MODULES-7833](https://tickets.puppetlabs.com/browse/MODULES-7833)
- Add Testmode Switcher for acceptance testing - [MODULES-6735](https://tickets.puppetlabs.com/browse/MODULES-6735)
- Add support for Windows Server 2016 and Windows Desktop Operating Systems - [MODULES-4271](https://tickets.puppetlabs.com/browse/MODULES-4271)
- Convert module to PDK format - [MODULES-7407](https://tickets.puppetlabs.com/browse/MODULES-7407)
- Add PowerShell task to get Update History - [MODULES-7761](https://tickets.puppetlabs.com/browse/MODULES-7761)

## 2016-12-13 - Supported Release 1.0.3
### Summary

Small release supporting Always Automatically Reboot at Scheduled Time setting.

### Bugfixes

- Ensure wuaserv service is idempotent - [MODULES-2420](https://tickets.puppetlabs.com/browse/MODULES-2420)

### Features

- Support AlwaysAutoRebootAtScheduledTimeMinutes - [MODULES-3475](https://tickets.puppetlabs.com/browse/MODULES-3475)
- Support AlwaysAutoRebootAtScheduledTime - [MODULES-3016](https://tickets.puppetlabs.com/browse/MODULES-3016)

## 2016-05-03 - Supported Release 1.0.2
### Summary

Small release with monior bugfixes

### Bugfixes
- Fix links and dependencies in metadata.json
- Fix acceptance tests

## 2015-12-08 - Supported Release 1.0.1
### Summary

Small release for support of newer PE versions.

## 2015-09-02 - Supported release 1.0.0
### Summary

First supported release

### Features
- Add metadata for Puppet 4 and PE 2015.2.0
- Update documentation

## 2015-07-02 - Unsupported release 0.1.3
### Summary

Fix the max value of RebootRelaunchTimeout

### Features
- Increase RebootRelaunchTimeout to 1440 instead of 440

## 2015-06-25 - Unsupported release 0.1.2
### Summary

Readme fix, metadata addition of puppet versions, and add of CHANGELOG

## 2015-06-18 - Unsupported release 0.1.1
### Summary

Update metadata for project and source urls

## 2015-06-18 - Initial Release 0.1.0
### Summary

Initial release to provide user the ability to manage registry keys pertaining to windows update service


\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
