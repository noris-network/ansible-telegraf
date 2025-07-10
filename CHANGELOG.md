# Changelog

## [0.12.0](https://github.com/noris-network/ansible-telegraf/tree/0.12.0) (2019-03-12)

[Full Changelog](https://github.com/dj-wasabi/ansible-telegraf/compare/0.14.2...HEAD)

**Merged pull requests:**

- Better sub inputs handling [\#193](https://github.com/dj-wasabi/ansible-telegraf/pull/193) ([lisuml](https://github.com/lisuml))
- Bump ansible-core from 2.18.0 to 2.18.1 [\#192](https://github.com/dj-wasabi/ansible-telegraf/pull/192) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible-core from 2.16.8 to 2.18.0 [\#191](https://github.com/dj-wasabi/ansible-telegraf/pull/191) ([dependabot[bot]](https://github.com/apps/dependabot))

## [0.14.2](https://github.com/dj-wasabi/ansible-telegraf/tree/0.14.2) (2024-11-26)

[Full Changelog](https://github.com/dj-wasabi/ansible-telegraf/compare/0.14.1...0.14.2)

## [0.11.0](https://github.com/noris-network/ansible-telegraf/tree/0.11.0) (2018-12-11)

[Full Changelog](https://github.com/noris-network/ansible-telegraf/compare/0.10.0...0.11.0)

## [0.10.0](https://github.com/noris-network/ansible-telegraf/tree/0.10.0) (2018-08-12)

[Full Changelog](https://github.com/noris-network/ansible-telegraf/compare/0.9.0...0.10.0)

## [0.9.0](https://github.com/noris-network/ansible-telegraf/tree/0.9.0) (2018-05-06)

- amazon.aws.ec2\_tag\_info [\#177](https://github.com/dj-wasabi/ansible-telegraf/issues/177)
- Failing on Debian Bookwork, telegraf recomends stable main rather than specific release [\#175](https://github.com/dj-wasabi/ansible-telegraf/issues/175)
- Unable to run against linux machines \(redhat\) [\#159](https://github.com/dj-wasabi/ansible-telegraf/issues/159)
- How to add the sub inputs into the same config file using telegraf\_plugin\_extra  [\#149](https://github.com/dj-wasabi/ansible-telegraf/issues/149)

**Merged pull requests:**

- Updating the Python packages to make Molecule work [\#190](https://github.com/dj-wasabi/ansible-telegraf/pull/190) ([dj-wasabi](https://github.com/dj-wasabi))
- fix: add missing tasks for RedHat distro \(rpm install\) [\#189](https://github.com/dj-wasabi/ansible-telegraf/pull/189) ([vfreitassentient](https://github.com/vfreitassentient))
- Bump ansible-core from 2.15.9 to 2.17.6 [\#188](https://github.com/dj-wasabi/ansible-telegraf/pull/188) ([dependabot[bot]](https://github.com/apps/dependabot))
- Use `rhel` within yum url for almalinux  [\#187](https://github.com/dj-wasabi/ansible-telegraf/pull/187) ([kuhball](https://github.com/kuhball))
- Add Archlinux OS [\#186](https://github.com/dj-wasabi/ansible-telegraf/pull/186) ([Frankkkkk](https://github.com/Frankkkkk))
- Fixes Role for Almalinux 8.8, Closes \#172 [\#183](https://github.com/dj-wasabi/ansible-telegraf/pull/183) ([mira-miracoli](https://github.com/mira-miracoli))

## [0.14.1](https://github.com/dj-wasabi/ansible-telegraf/tree/0.14.1) (2024-02-17)

[Full Changelog](https://github.com/dj-wasabi/ansible-telegraf/compare/0.14.0...0.14.1)

**Implemented enhancements:**

- Fix check-mode failures [\#168](https://github.com/dj-wasabi/ansible-telegraf/pull/168) ([pieterlexis-tomtom](https://github.com/pieterlexis-tomtom))

**Fixed bugs:**

- Fix molecule tests so that PR's can properly validated [\#180](https://github.com/dj-wasabi/ansible-telegraf/pull/180) ([dj-wasabi](https://github.com/dj-wasabi))
- Replace apt\_key with get\_url [\#170](https://github.com/dj-wasabi/ansible-telegraf/pull/170) ([danclough](https://github.com/danclough))

**Closed issues:**

- Failure due to apt-key when run against newer Debian/Ubuntu releases [\#169](https://github.com/dj-wasabi/ansible-telegraf/issues/169)

**Merged pull requests:**

- Bump ansible-core from 2.15.2 to 2.15.9 [\#182](https://github.com/dj-wasabi/ansible-telegraf/pull/182) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ansible from 8.2.0 to 8.5.0 [\#181](https://github.com/dj-wasabi/ansible-telegraf/pull/181) ([dependabot[bot]](https://github.com/apps/dependabot))
- Change Debian repo location [\#179](https://github.com/dj-wasabi/ansible-telegraf/pull/179) ([danclough](https://github.com/danclough))
- replace depracted aws module [\#178](https://github.com/dj-wasabi/ansible-telegraf/pull/178) ([daparm](https://github.com/daparm))
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
- Fix the molecule run as part of CI process [\#166](https://github.com/dj-wasabi/ansible-telegraf/pull/166) ([dj-wasabi](https://github.com/dj-wasabi))
- update influxdata GPG key after rotation [\#165](https://github.com/dj-wasabi/ansible-telegraf/pull/165) ([Tetha](https://github.com/Tetha))
- Fixed issues with Windows paths containing spaces [\#162](https://github.com/dj-wasabi/ansible-telegraf/pull/162) ([KlettIT](https://github.com/KlettIT))

**Closed issues:**

- Influxdata key rotation causing failure [\#164](https://github.com/dj-wasabi/ansible-telegraf/issues/164)
- Influxdb2 output [\#158](https://github.com/dj-wasabi/ansible-telegraf/issues/158)

## [0.13.3](https://github.com/dj-wasabi/ansible-telegraf/tree/0.13.3) (2022-03-21)

[Full Changelog](https://github.com/noris-network/ansible-telegraf/compare/0.6.0...0.7.0)

## [0.6.0](https://github.com/noris-network/ansible-telegraf/tree/0.6.0) (2017-01-02)

[Full Changelog](https://github.com/dj-wasabi/ansible-telegraf/compare/0.13.0...0.13.1)

**Implemented enhancements:**

- Added GH Action to automatically update CHANGELOG.md [\#141](https://github.com/dj-wasabi/ansible-telegraf/pull/141) ([dj-wasabi](https://github.com/dj-wasabi))

**Fixed bugs:**

- adjustments for Windows \>= 1.15 [\#139](https://github.com/dj-wasabi/ansible-telegraf/pull/139) ([billabongrob](https://github.com/billabongrob))

**Closed issues:**

- Newer versions of Telegraf fail on Windows [\#138](https://github.com/dj-wasabi/ansible-telegraf/issues/138)

**Merged pull requests:**

- Added property telegraf\_agent\_docker\_image\_version for using a specific version of the Docker image [\#137](https://github.com/dj-wasabi/ansible-telegraf/pull/137) ([dj-wasabi](https://github.com/dj-wasabi))
- Apply ansible-lint in pre-commit hook and fix changes [\#136](https://github.com/dj-wasabi/ansible-telegraf/pull/136) ([dj-wasabi](https://github.com/dj-wasabi))
- Using version as version\_compare is deprecated [\#135](https://github.com/dj-wasabi/ansible-telegraf/pull/135) ([dj-wasabi](https://github.com/dj-wasabi))
- Using command instead of shell module [\#134](https://github.com/dj-wasabi/ansible-telegraf/pull/134) ([dj-wasabi](https://github.com/dj-wasabi))

## [0.13.0](https://github.com/dj-wasabi/ansible-telegraf/tree/0.13.0) (2020-10-16)

[Full Changelog](https://github.com/dj-wasabi/ansible-telegraf/compare/0.12.0...0.13.0)

**Implemented enhancements:**

- Setup the system for individual plugins [\#125](https://github.com/dj-wasabi/ansible-telegraf/issues/125)
- Logparser configuration [\#111](https://github.com/dj-wasabi/ansible-telegraf/issues/111)
- ansible\_fqdn problematic for getting hostname [\#105](https://github.com/dj-wasabi/ansible-telegraf/issues/105)
- FreeBSD support [\#99](https://github.com/dj-wasabi/ansible-telegraf/issues/99)
- Proxy not taken into consideration when using 'online' [\#96](https://github.com/dj-wasabi/ansible-telegraf/issues/96)

**Closed issues:**

- telegraf\_agent\_aws\_tags creates an invalid Telegraf configuration [\#128](https://github.com/dj-wasabi/ansible-telegraf/issues/128)
- Broken on Ubuntu 20.04 [\#121](https://github.com/dj-wasabi/ansible-telegraf/issues/121)
- Broken on RedHat [\#119](https://github.com/dj-wasabi/ansible-telegraf/issues/119)

**Merged pull requests:**

- corrected "Example Docker configuration" to make it work by default [\#132](https://github.com/dj-wasabi/ansible-telegraf/pull/132) ([NotDead](https://github.com/NotDead))
- Removing requirements file and use it from ci-base repo [\#131](https://github.com/dj-wasabi/ansible-telegraf/pull/131) ([dj-wasabi](https://github.com/dj-wasabi))
- Going to Github Actions [\#130](https://github.com/dj-wasabi/ansible-telegraf/pull/130) ([dj-wasabi](https://github.com/dj-wasabi))
- quote aws ec2 global tags [\#129](https://github.com/dj-wasabi/ansible-telegraf/pull/129) ([Puneeth-n](https://github.com/Puneeth-n))
- made service status configurable [\#127](https://github.com/dj-wasabi/ansible-telegraf/pull/127) ([DEvil0000](https://github.com/DEvil0000))
- Plugin dependencies are installed and configured [\#126](https://github.com/dj-wasabi/ansible-telegraf/pull/126) ([carlba](https://github.com/carlba))
- fix debian packagename on state latest [\#124](https://github.com/dj-wasabi/ansible-telegraf/pull/124) ([dwerder](https://github.com/dwerder))
- MacOS support [\#123](https://github.com/dj-wasabi/ansible-telegraf/pull/123) ([carlba](https://github.com/carlba))
- gpgkey yum repo fix [\#122](https://github.com/dj-wasabi/ansible-telegraf/pull/122) ([marcinwito](https://github.com/marcinwito))
- Fix RedHat task list [\#120](https://github.com/dj-wasabi/ansible-telegraf/pull/120) ([rohit-gohri](https://github.com/rohit-gohri))
- added installation method manual - skip installation [\#117](https://github.com/dj-wasabi/ansible-telegraf/pull/117) ([DEvil0000](https://github.com/DEvil0000))
- Support postgresql\_extensible queries [\#116](https://github.com/dj-wasabi/ansible-telegraf/pull/116) ([rlex](https://github.com/rlex))
- Added extra filtering possibilities for a plugin [\#113](https://github.com/dj-wasabi/ansible-telegraf/pull/113) ([dj-wasabi](https://github.com/dj-wasabi))
- Minor changes to get Travis working again [\#112](https://github.com/dj-wasabi/ansible-telegraf/pull/112) ([dj-wasabi](https://github.com/dj-wasabi))
- Download from influxdb [\#109](https://github.com/dj-wasabi/ansible-telegraf/pull/109) ([dj-wasabi](https://github.com/dj-wasabi))
- Don't override package name unless "latest" [\#108](https://github.com/dj-wasabi/ansible-telegraf/pull/108) ([matttrach](https://github.com/matttrach))
- Adding support for arm64 systems [\#106](https://github.com/dj-wasabi/ansible-telegraf/pull/106) ([remkade](https://github.com/remkade))
- Use items\(\) instead of iteritems\(\) [\#104](https://github.com/dj-wasabi/ansible-telegraf/pull/104) ([diego1q2w](https://github.com/diego1q2w))
- Fix: ensure apt-cache is updated before install [\#103](https://github.com/dj-wasabi/ansible-telegraf/pull/103) ([asfaltboy](https://github.com/asfaltboy))
- on FreeBSD the telegeraf.conf is in root of /usr/local/etc. [\#102](https://github.com/dj-wasabi/ansible-telegraf/pull/102) ([langerma](https://github.com/langerma))
- Some changes for fixing FreeBSD [\#101](https://github.com/dj-wasabi/ansible-telegraf/pull/101) ([dj-wasabi](https://github.com/dj-wasabi))
- basic FreeBSD support [\#100](https://github.com/dj-wasabi/ansible-telegraf/pull/100) ([langerma](https://github.com/langerma))
- Added the use\_proxy argument to use a proxy \(or not\) [\#98](https://github.com/dj-wasabi/ansible-telegraf/pull/98) ([dj-wasabi](https://github.com/dj-wasabi))

## [0.12.0](https://github.com/dj-wasabi/ansible-telegraf/tree/0.12.0) (2019-03-12)

[Full Changelog](https://github.com/dj-wasabi/ansible-telegraf/compare/0.11.0...0.12.0)

**Implemented enhancements:**

- Install telegraf from package file instead of repository [\#89](https://github.com/dj-wasabi/ansible-telegraf/issues/89)

**Closed issues:**

- Docker container support [\#82](https://github.com/dj-wasabi/ansible-telegraf/issues/82)

**Merged pull requests:**

- Various small changes for molecule [\#97](https://github.com/dj-wasabi/ansible-telegraf/pull/97) ([dj-wasabi](https://github.com/dj-wasabi))
- Add processors section in Telegraf config [\#94](https://github.com/dj-wasabi/ansible-telegraf/pull/94) ([ph4r5h4d](https://github.com/ph4r5h4d))
- Updated to Telegraf 1.10.0;Different installation methods [\#93](https://github.com/dj-wasabi/ansible-telegraf/pull/93) ([dj-wasabi](https://github.com/dj-wasabi))
- Updating Telegraf default to 1.9.5 [\#92](https://github.com/dj-wasabi/ansible-telegraf/pull/92) ([sdurrheimer](https://github.com/sdurrheimer))
- Updating Telegraf default to 1.9.4 [\#90](https://github.com/dj-wasabi/ansible-telegraf/pull/90) ([sdurrheimer](https://github.com/sdurrheimer))
- Docker enhancements [\#88](https://github.com/dj-wasabi/ansible-telegraf/pull/88) ([jgeusebroek](https://github.com/jgeusebroek))
- Updating Telegraf default to 1.9.3 [\#87](https://github.com/dj-wasabi/ansible-telegraf/pull/87) ([sdurrheimer](https://github.com/sdurrheimer))
- Added register for installation of packages [\#86](https://github.com/dj-wasabi/ansible-telegraf/pull/86) ([dj-wasabi](https://github.com/dj-wasabi))
- Add Docker container support [\#85](https://github.com/dj-wasabi/ansible-telegraf/pull/85) ([jgeusebroek](https://github.com/jgeusebroek))
- Remove legacy options [\#84](https://github.com/dj-wasabi/ansible-telegraf/pull/84) ([jgeusebroek](https://github.com/jgeusebroek))
- Fix tagpass and tagdrop [\#83](https://github.com/dj-wasabi/ansible-telegraf/pull/83) ([jgeusebroek](https://github.com/jgeusebroek))
- \[bug\] debian - add cache\_valid\_time [\#81](https://github.com/dj-wasabi/ansible-telegraf/pull/81) ([pad92](https://github.com/pad92))
- Updating Telegraf default to 1.9.2 [\#80](https://github.com/dj-wasabi/ansible-telegraf/pull/80) ([sdurrheimer](https://github.com/sdurrheimer))
- Add Yum repo support for Amazon Linux [\#79](https://github.com/dj-wasabi/ansible-telegraf/pull/79) ([anthonysr](https://github.com/anthonysr))
- Fix to work with Fedora Linux [\#78](https://github.com/dj-wasabi/ansible-telegraf/pull/78) ([ikke-t](https://github.com/ikke-t))
- Updating to newer version of Telegraf [\#77](https://github.com/dj-wasabi/ansible-telegraf/pull/77) ([dj-wasabi](https://github.com/dj-wasabi))
- Add support for extra win\_perf\_counters and prevent python u'' strings [\#76](https://github.com/dj-wasabi/ansible-telegraf/pull/76) ([jdivy](https://github.com/jdivy))

## [0.11.0](https://github.com/dj-wasabi/ansible-telegraf/tree/0.11.0) (2018-12-11)

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
