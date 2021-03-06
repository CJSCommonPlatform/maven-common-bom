# Change Log
All notable changes to this project will be documented in this file, which follows the guidelines
on [Keep a CHANGELOG](http://keepachangelog.com/). This project adheres to
[Semantic Versioning](http://semver.org/).

## [Unreleased]
## [11.0.0-M3] - 2021-02-04
### Changed
- Update to JEE 8
- Update maven-parent-pom to 11.0.0-M2  
- Update deltaspike version to 1.9.4
- Update guava version to 30.1-jre

- Bumped version to 11.0.0 to match new framework version
## [11.0.0-M2] - 2021-01-25
### Added
- Added dependency for deltaspike-test-control-module-impl
### Changed
- Bumped version to 11.0.0 to match new framework version

## [8.0.0-M5] - 2021-01-06
### Fixed 
- Move from xbean-asm5 to xbean-asm7

## [8.0.0-M4] - 2021-01-06
### Added
- Added dependency for deltaspike-test-control-module-impl
### Changed
- Bumped version to 11.0.0-M1 to match new framework version

## [8.0.0-M4] - 2021-01-06
### Added
- Added dependency for xbean-asm7-shaded version 4.11
### Changed
- Update deltaspike version to 1.9.1

## [8.0.0-M3] - 2020-12-11
### Changed
- Update maven-parent-pom to 8.0.0-M3 

## [8.0.0-M1] - 2020-12-09
### Changed
- Update to Java 11
    - Update maven-parent-pom version to 8.0.0-M1
    - Update jsonpath version to 2.4.0
    - Update restassured version to 2.9.0
    - Update jaxb-core version to 2.3.0.1
    - Update jaxb version to 2.3.1
    - Update glassfish-json version to 1.1.4
    - Jaxb libraries needed for java 11 as they're no longer included by default -->
        - com.sun.xml.bind:jaxb-core
        - javax.xml.bind:jaxb-api
        - com.sun.xml.bind:jaxb-impl
    - Added classgraph as a replacement for reflections.org

## [7.1.1] - 2020-10-14
### Changed
- Updated various library dependencies to fix security vulnerabilities: 
    - junit:                4.12    ->   4.13.1      https://github.com/advisories/GHSA-269g-pwp5-87pp      
    - commons.beanutils:    1.9.2   ->   1.9.4       https://github.com/advisories/GHSA-6phf-73q6-gh87
    - commons.guava:        19.0    ->   29.0-jre    https://github.com/advisories/GHSA-mvr2-9pj6-7w5j
    - apache.tika:          1.20    ->   1.22        https://github.com/advisories/GHSA-mm7m-xg4h-6m52

## [7.1.0] - 2020-09-23
### Changed
- Updated parent maven-parent-pom to version 2.0.0
- Moved to new Cloudsmith.io repository for hosting maven artifacts
- Updated encrypted properties in travis.yaml to point to cloudsmith

## [7.0.3] - 2020-06-02
### Changed
- Update Drools to 6.5.0.Final

## [7.0.2] - 2020-05-27
### Added
- Cucumber version and dependencies

## [7.0.1] - 2020-05-21
### Changed
- added dependencies required by Embedded Artemis in framework-libraries

## [7.0.0] - 2020-05-20
### Added
- Added diff.utils version 1.3.0
- Added jolt version 0.1.1
### Changed
- Jumped version to 7.0.0 to match Framework and associated libraries

## [2.5.0] - 2020-02-17
### Removed
- 1.5.1 of org.everit.json.schema dependency, this is causing conflicts

## [2.4.0] - 2019-07-11
### Added
- Added commons.cli version 1.2
### Changed
- wildfly-client-all now has default exclusions to allow for running Jmx Clients

## [2.3.0] - 2019-06-25
### Changed
- Revert jackson version 2.9.8 to 2.8.11
- Update jackson.databind to version 2.8.11.3
- Update jackson-dataformat-csv to version 2.8.11

## [2.2.0] - 2019-05-13

### Changed
- Updated apache tika to version 1.20

## [2.1.0] - 2019-05-13

### Changed
- Update jackson to version 2.9.8

## [2.0.2] - 2019-05-01

### Changed
- Revert Deltaspike version to 1.6.1, due to issues with Deltaspike when testing

## [2.0.1] - 2019-05-01

### Changed
- Revert Deltaspike version to 1.6.1, due to issues with Deltaspike when testing

## [1.31.0] - 2019-04-30

## Removed
- org.elasticsearch.client:rest:5.2.2
- org.elasticsearch:elasticsearch:5.2.2
- org.elasticsearch.plugin:transport-netty4-client:5.2.2

## [1.30.0] - 2019-02-07
               
## Added
- io.github.classgraph:classgraph:4.6.32

## [1.29.0] - 2019-02-01
               
## Changed
- Update Deltaspike version 1.7.0

## [1.28.0] - 2018-07-25

### Changed
- Update Jackson dataformat YAML to Jackson version 2.8.11

## [1.27.0] - 2018-06-20

### Changed
- Upgrade Apache Tika to 1.18

## [1.26.0] - 2018-05-16

### Changed
- Downgraded Jackson version to 2.8.11 to fix bug with single argument constructors

## [1.25.0] - 2018-05-15

### Changed
- Updated Jackson version to 2.9.5

## [1.24.0] - 2018-04-13

### Added
- jackson-dataformat-yaml 2.8.7 

## [1.23.0] - 2018-04-09

### Added
- jglue-cdi-unit version 4.0.1
- jboss.weld.se version 2.4.5.Final

## [1.22.0] - 2017-11-06

### Added
- javax.mail version 1.5.0 

## [1.21.0] - 2017-11-01

### Changed
- Updates to fix OWASP vulnerabilities
    - Exclude johnzon-core from artemis-jms-client
    
### Added
- Updates to fix OWASP vulnerabilities
    - johnzon-core version 1.0.0 dependency

## [1.20.0] - 2017-10-31

### Changed
- Updates to fix OWASP vulnerabilities
    - Update artemis-jms to 1.5.5
    - glassfish-json to 1.0.4

## [1.19.0] - 2017-10-18

### Changed
- org.json:json to version 20170516

## [1.18.0] - 2017-09-26

### Added
- jboss-vfs 
- github repo based everit

## [1.17.0] - 2017-07-28

### Changed
- Updated to use parent POM [1.6.0](https://github.com/CJSCommonPlatform/maven-parent-pom/releases/tag/release-1.6.0)
- Use bintray for releases
- Improve Travis build process (use common one)


## [1.16.0] - 2017-06-14

### Changed
- Upgrade to use parent POM [1.5.0](https://github.com/CJSCommonPlatform/maven-parent-pom/releases/tag/release-1.5.0)
- Revert Wiremock to 1.x for backwards compatibility
- Upgrade JSON Schema library to 1.5.1 so forked version is no longer required
- Upgrade RAML parser to 0.8.18
- Exclude logging dependencies where appropriate

## [1.15.0] - 2017-04-28

### Changed
- Upgrade to use parent POM [1.4.1](https://github.com/CJSCommonPlatform/maven-parent-pom/releases/tag/release-1.4.1)
- Uplift wiremock to the forked version

## [1.14.0] - 2017-03-15
### Added
- add Http Mime

## [1.13.0] - 2017-03-10
### Added
- Add Apache Tika

## [1.12.0] - 2017-03-02

### Removed
- Remove JBoss exclusions

## [1.11.0] - 2017-03-02
- Failed release; do not use

## [1.10.0] - 2017-02-22
### Added 
- Uplift RESTEasy version and exclude conflicting dependencies

## [1.9.0] - 2017-02-14
### Added
- Add maven-plugin-annotations

## [1.8.0] - 2017-02-13

### Added 
- dependency on rest easy-multipart
- dependencies used by raml maven plugin

## [1.7.0] - 2017-02-10

### Added
- maven-plugin-testing-harness
- maven-compat
- maven-core

## [1.6.0] - 2017-01-19

### Added
- Postgres driver, apache.commons-dbcp2 and hamcrest library versions

## [1.5.1] - 2016-12-15

### Changed
- Update org.json version to 20160810

## [1.5.0] - 2016-12-01

### Changed
- Depend on MoJ forked json schema library as it has fix for date-time format

## [1.4.0] - 2016-11-14

### Added
- Add hamcrest regex library

### Changed
- Resolved logging transitive dependency conflicts

## [1.3.0] - 2016-11-02

### Added
- Add jolokia dependencies

### Changed
- Dependencies to resolve maven enforcer conflicts
- Property ordering and removing duplicate declarations

## [1.2.0] - 2016-10-05

### Changed

- Changed artemis.jms.client.version from 1.2.0 to 1.3.0

### Added

- Add artemis.jms.version 1.3.0
- Add artemis-ra library
- Add artemis-jms-server library
- Add artemis-service-extensions library
- Add wildfly-client-all library
- Add javassist version
- Add hamcrest date library
- Dropwizard metrics core
- Weld 2.4.0.Final
- JCommander 1.48


## [1.1.0] - 2016-08-18

### Added

- Add java 8 matchers version


## [1.0.0] - 2016-07-28

### Added

- Initial release of common BOM

[Unreleased]: https://github.com/CJSCommonPlatform/maven-common-bom/compare/release-1.14.0...HEAD
[1.14.0]: https://github.com/CJSCommonPlatform/maven-common-bom/compare/release-1.13.0...release-1.14.0
[1.13.0]: https://github.com/CJSCommonPlatform/maven-common-bom/compare/release-1.12.0...release-1.13.0
[1.12.0]: https://github.com/CJSCommonPlatform/maven-common-bom/compare/release-1.11.0...release-1.12.0
[1.11.0]: https://github.com/CJSCommonPlatform/maven-common-bom/compare/release-1.0.0...release-1.11.0
[1.10.0]: https://github.com/CJSCommonPlatform/maven-common-bom/compare/release-1.9.0...release-1.10.0
[1.9.0]: https://github.com/CJSCommonPlatform/maven-common-bom/compare/release-1.8.0...release-1.9.0
[1.8.0]: https://github.com/CJSCommonPlatform/maven-common-bom/compare/release-1.7.0...release-1.8.0
[1.7.0]: https://github.com/CJSCommonPlatform/maven-common-bom/compare/release-1.6.0...release-1.7.0
[1.6.0]: https://github.com/CJSCommonPlatform/maven-common-bom/compare/release-1.5.0...release-1.6.0
[1.5.1]: https://github.com/CJSCommonPlatform/maven-common-bom/compare/release-1.5.0...release-1.5.1
[1.5.0]: https://github.com/CJSCommonPlatform/maven-common-bom/compare/release-1.4.0...release-1.5.0
[1.4.0]: https://github.com/CJSCommonPlatform/maven-common-bom/compare/release-1.3.0...release-1.4.0
[1.3.0]: https://github.com/CJSCommonPlatform/maven-common-bom/compare/release-1.2.0...release-1.3.0
[1.2.0]: https://github.com/CJSCommonPlatform/maven-common-bom/compare/release-1.1.0...release-1.2.0
[1.1.0]: https://github.com/CJSCommonPlatform/maven-common-bom/compare/release-1.0.0...release-1.1.0
[1.0.0]: https://github.com/CJSCommonPlatform/maven-common-bom/commits/release-1.0.0
