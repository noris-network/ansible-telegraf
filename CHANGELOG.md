# Changelog

## [0.12.0](https://github.com/noris-network/ansible-telegraf/tree/0.12.0) (2019-03-12)

[Full Changelog](https://github.com/dj-wasabi/ansible-telegraf/compare/0.14.1...HEAD)

**Implemented enhancements:**

- Repo installation fails for Almalinux [\#172](https://github.com/dj-wasabi/ansible-telegraf/issues/172)
- Support for sub\_inputs in extra plugins [\#184](https://github.com/dj-wasabi/ansible-telegraf/pull/184) ([lisuml](https://github.com/lisuml))

**Fixed bugs:**

- Add default repository handling for SUSE releases [\#154](https://github.com/dj-wasabi/ansible-telegraf/issues/154)
- Fix Python package dependencies on SUSE releases [\#153](https://github.com/dj-wasabi/ansible-telegraf/issues/153)

**Closed issues:**

- amazon.aws.ec2\_tag\_info [\#177](https://github.com/dj-wasabi/ansible-telegraf/issues/177)
- Failing on Debian Bookwork, telegraf recomends stable main rather than specific release [\#175](https://github.com/dj-wasabi/ansible-telegraf/issues/175)
- Unable to run against linux machines \(redhat\) [\#159](https://github.com/dj-wasabi/ansible-telegraf/issues/159)

**Merged pull requests:**

- Fixes Role for Almalinux 8.8, Closes \#172 [\#183](https://github.com/dj-wasabi/ansible-telegraf/pull/183) ([mira-miracoli](https://github.com/mira-miracoli))

## [0.14.1](https://github.com/dj-wasabi/ansible-telegraf/tree/0.14.1) (2024-02-17)

[Full Changelog](https://github.com/dj-wasabi/ansible-telegraf/compare/0.14.0...0.14.1)

**Implemented enhancements:**

- Fix check-mode failures [\#168](https://github.com/dj-wasabi/ansible-telegraf/pull/168) ([pieterlexis-tomtom](https://github.com/pieterlexis-tomtom))

**Fixed bugs:**

- Fix molecule tests so that PR's can properly validated [\#180](https://github.com/dj-wasabi/ansible-telegraf/pull/180) ([dj-wasabi](https://github.com/dj-wasabi))

**Closed issues:**

- Failure due to apt-key when run against newer Debian/Ubuntu releases [\#169](https://github.com/dj-wasabi/ansible-telegraf/issues/169)

**Merged pull requests:**

- Bump ansible-core from 2.15.2 to 2.15.9 [\#182](https://github.com/dj-wasabi/ansible-telegraf/pull/182) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible from 8.2.0 to 8.5.0 [\#181](https://github.com/dj-wasabi/ansible-telegraf/pull/181) ([dependabot[bot]](https://github.com/apps/dependabot))
- Change Debian repo location [\#179](https://github.com/dj-wasabi/ansible-telegraf/pull/179) ([danclough](https://github.com/danclough))
- replace depracted aws module [\#178](https://github.com/dj-wasabi/ansible-telegraf/pull/178) ([ThorstenHeck](https://github.com/ThorstenHeck))
- added yaml 1.2.2 compatibility [\#176](https://github.com/dj-wasabi/ansible-telegraf/pull/176) ([DEvil0000](https://github.com/DEvil0000))
- Migrate from io to diskio to fix deprecation warning [\#173](https://github.com/dj-wasabi/ansible-telegraf/pull/173) ([mprasil](https://github.com/mprasil))

## [0.14.0](https://github.com/dj-wasabi/ansible-telegraf/tree/0.14.0) (2023-01-30)

[Full Changelog](https://github.com/dj-wasabi/ansible-telegraf/compare/0.13.3...0.14.0)

**Implemented enhancements:**

- Added/removed OS'es for Molecule CI testing [\#167](https://github.com/dj-wasabi/ansible-telegraf/pull/167) ([dj-wasabi](https://github.com/dj-wasabi))
- Ensure check-mode works [\#163](https://github.com/dj-wasabi/ansible-telegraf/pull/163) ([pieterlexis-tomtom](https://github.com/pieterlexis-tomtom))
- Downgrade support [\#160](https://github.com/dj-wasabi/ansible-telegraf/pull/160) ([maxnasonov](https://github.com/maxnasonov))

**Fixed bugs:**

- Don't install init script on SUSE/openSUSE systems running systemd [\#152](https://github.com/dj-wasabi/ansible-telegraf/issues/152)
- Replace apt\_key with get\_url [\#170](https://github.com/dj-wasabi/ansible-telegraf/pull/170) ([danclough](https://github.com/danclough))
- Fix the molecule run as part of CI process [\#166](https://github.com/dj-wasabi/ansible-telegraf/pull/166) ([dj-wasabi](https://github.com/dj-wasabi))
- update influxdata GPG key after rotation [\#165](https://github.com/dj-wasabi/ansible-telegraf/pull/165) ([Tetha](https://github.com/Tetha))
- Fixed issues with Windows paths containing spaces [\#162](https://github.com/dj-wasabi/ansible-telegraf/pull/162) ([KlettIT](https://github.com/KlettIT))

**Closed issues:**

- Influxdata key rotation causing failure [\#164](https://github.com/dj-wasabi/ansible-telegraf/issues/164)
- Influxdb2 output [\#158](https://github.com/dj-wasabi/ansible-telegraf/issues/158)

## [0.13.3](https://github.com/dj-wasabi/ansible-telegraf/tree/0.13.3) (2022-03-21)

[Full Changelog](https://github.com/dj-wasabi/ansible-telegraf/compare/0.13.2...0.13.3)

## [0.11.0](https://github.com/noris-network/ansible-telegraf/tree/0.11.0) (2018-12-11)

[Full Changelog](https://github.com/noris-network/ansible-telegraf/compare/0.10.0...0.11.0)

## [0.10.0](https://github.com/noris-network/ansible-telegraf/tree/0.10.0) (2018-08-12)

[Full Changelog](https://github.com/noris-network/ansible-telegraf/compare/0.9.0...0.10.0)

## [0.9.0](https://github.com/noris-network/ansible-telegraf/tree/0.9.0) (2018-05-06)

[Full Changelog](https://github.com/noris-network/ansible-telegraf/compare/0.8.0...0.9.0)

## [0.8.0](https://github.com/noris-network/ansible-telegraf/tree/0.8.0) (2017-10-30)

[Full Changelog](https://github.com/noris-network/ansible-telegraf/compare/0.7.0...0.8.0)

## [0.7.0](https://github.com/noris-network/ansible-telegraf/tree/0.7.0) (2017-02-23)

[Full Changelog](https://github.com/noris-network/ansible-telegraf/compare/0.6.0...0.7.0)

## [0.6.0](https://github.com/noris-network/ansible-telegraf/tree/0.6.0) (2017-01-02)

[Full Changelog](https://github.com/noris-network/ansible-telegraf/compare/0.5.1...0.6.0)

## [0.5.1](https://github.com/noris-network/ansible-telegraf/tree/0.5.1) (2016-08-24)

[Full Changelog](https://github.com/noris-network/ansible-telegraf/compare/0.5.0...0.5.1)

## [0.5.0](https://github.com/noris-network/ansible-telegraf/tree/0.5.0) (2016-07-17)

[Full Changelog](https://github.com/noris-network/ansible-telegraf/compare/0.4.0...0.5.0)

## [0.4.0](https://github.com/noris-network/ansible-telegraf/tree/0.4.0) (2016-02-05)

[Full Changelog](https://github.com/noris-network/ansible-telegraf/compare/0.3.0...0.4.0)

## [0.3.0](https://github.com/noris-network/ansible-telegraf/tree/0.3.0) (2016-01-13)

[Full Changelog](https://github.com/noris-network/ansible-telegraf/compare/0.2.0...0.3.0)

## [0.2.0](https://github.com/noris-network/ansible-telegraf/tree/0.2.0) (2015-11-14)

[Full Changelog](https://github.com/noris-network/ansible-telegraf/compare/0.1.0...0.2.0)

## [0.1.0](https://github.com/noris-network/ansible-telegraf/tree/0.1.0) (2015-09-23)

[Full Changelog](https://github.com/noris-network/ansible-telegraf/compare/0.0.2...0.1.0)

## [0.0.2](https://github.com/noris-network/ansible-telegraf/tree/0.0.2) (2015-09-20)

[Full Changelog](https://github.com/noris-network/ansible-telegraf/compare/0.0.1...0.0.2)

## [0.0.1](https://github.com/noris-network/ansible-telegraf/tree/0.0.1) (2015-09-20)

[Full Changelog](https://github.com/noris-network/ansible-telegraf/compare/03adb259af33123c917cdc960d23aeee07e01fef...0.0.1)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
