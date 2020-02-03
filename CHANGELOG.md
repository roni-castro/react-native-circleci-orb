## [2.3.5](https://github.com/roni-castro/react-native-circleci-orb/compare/v2.3.4...v2.3.5) (2020-02-03)


### Bug Fixes

* allow to pass different xcode version to macos executor ([48dcbcc](https://github.com/roni-castro/react-native-circleci-orb/commit/48dcbcc))

## [2.3.4](https://github.com/roni-castro/react-native-circleci-orb/compare/v2.3.3...v2.3.4) (2020-02-01)


### Bug Fixes

* install nvm before node ([96fdd9a](https://github.com/roni-castro/react-native-circleci-orb/commit/96fdd9a))

## [2.3.3](https://github.com/roni-castro/react-native-circleci-orb/compare/v2.3.2...v2.3.3) (2020-02-01)


### Bug Fixes

* Use specific script to install node using nvm ([a28d7f6](https://github.com/roni-castro/react-native-circleci-orb/commit/a28d7f6))

## [2.3.2](https://github.com/roni-castro/react-native-circleci-orb/compare/v2.3.1...v2.3.2) (2020-02-01)


### Bug Fixes

* Allow update brew ([0afdb3c](https://github.com/roni-castro/react-native-circleci-orb/commit/0afdb3c))

## [2.3.1](https://github.com/roni-castro/react-native-circleci-orb/compare/v2.3.0...v2.3.1) (2020-01-31)


### Bug Fixes

* Unlink node version to be able to update it ([3d23c4a](https://github.com/roni-castro/react-native-circleci-orb/commit/3d23c4a))

# [2.2.0](https://github.com/roni-castro/react-native-circleci-orb/compare/v2.1.1...v2.2.0) (2020-01-17)


### Bug Fixes

* Use node 10 ([a133f53](https://github.com/roni-castro/react-native-circleci-orb/commit/a133f53))


### Features

* Update node to version 12 ([bdb6c46](https://github.com/roni-castro/react-native-circleci-orb/commit/bdb6c46))
* Update node version to the latest and add parameters ([e2f9579](https://github.com/roni-castro/react-native-circleci-orb/commit/e2f9579))


## [2.1.1](https://github.com/roni-castro/react-native-circleci-orb/compare/v2.1.0...v2.1.1) (2020-01-16)


### Bug Fixes

* Use node 10 ([6971173](https://github.com/roni-castro/react-native-circleci-orb/commit/6971173))

# [2.1.0](https://github.com/roni-castro/react-native-circleci-orb/compare/v2.0.0...v2.1.0) (2020-01-16)


### Features

* Update node to version 12 ([7bfd28f](https://github.com/roni-castro/react-native-circleci-orb/commit/7bfd28f))

# [2.0.0](https://github.com/roni-castro/react-native-circleci-orb/compare/v1.4.4...v2.0.0) (2020-01-16)


### Bug Fixes

* Removed the unused `build_threads` parameter in the `linux_android` executor ([97720b9](https://github.com/roni-castro/react-native-circleci-orb/commit/97720b9)), closes [#19](https://github.com/roni-castro/react-native-circleci-orb/issues/19)


### Features

* Add `on_after_initialize` parameter to the jobs ([#26](https://github.com/roni-castro/react-native-circleci-orb/issues/26) by [@compojoom](https://github.com/compojoom)) ([0ff6621](https://github.com/roni-castro/react-native-circleci-orb/commit/0ff6621))
* Add a `bundle` command ([#8](https://github.com/roni-castro/react-native-circleci-orb/issues/8) by [@sunilchalla](https://github.com/sunilchalla)) ([464d661](https://github.com/roni-castro/react-native-circleci-orb/commit/464d661))
* Added the `--frozen-lockfile` flag to the `yarn_install` command ([e4676c4](https://github.com/roni-castro/react-native-circleci-orb/commit/e4676c4)), closes [#28](https://github.com/roni-castro/react-native-circleci-orb/issues/28)
* Update node version to the latest and add parameters ([073689c](https://github.com/roni-castro/react-native-circleci-orb/commit/073689c))
* **ios:** Added an `ios_build` job ([#30](https://github.com/roni-castro/react-native-circleci-orb/issues/30) by [@roni-castro](https://github.com/roni-castro)) ([b607782](https://github.com/roni-castro/react-native-circleci-orb/commit/b607782))


### BREAKING CHANGES

* The `yarn_install` command will now fail if there need to be changes made to your `yarn.lock` file. See [the Yarn documentation](https://yarnpkg.com/en/docs/cli/install#toc-yarn-install-frozen-lockfile) for details on this flag.

## [1.4.4](https://github.com/roni-castro/react-native-circleci-orb/compare/v1.4.3...v1.4.4) (2020-01-03)


### Bug Fixes

* Update releaserc and Readme links ([586463e](https://github.com/roni-castro/react-native-circleci-orb/commit/586463e))

# [1.3.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v1.2.1...v1.3.0) (2019-11-20)


### Bug Fixes

* **android:** Update gradle cache keys to match on save and restore ([#17](https://github.com/react-native-community/react-native-circleci-orb/issues/17)) ([6e52052](https://github.com/react-native-community/react-native-circleci-orb/commit/6e52052))
* **docs:** include the code repo link in the orb description ([6d97ca9](https://github.com/react-native-community/react-native-circleci-orb/commit/6d97ca9))
* Remove FBSimulatorControl ([#24](https://github.com/react-native-community/react-native-circleci-orb/issues/24) by [@compojoom](https://github.com/compojoom)) ([7c5b51a](https://github.com/react-native-community/react-native-circleci-orb/commit/7c5b51a))
* remove haxm the lack hardware acceleration support causes a crash ([9d0bb42](https://github.com/react-native-community/react-native-circleci-orb/commit/9d0bb42))
* remove haxm the lack hardware acceleration support causes a crash ([38ef88e](https://github.com/react-native-community/react-native-circleci-orb/commit/38ef88e)), closes [#3](https://github.com/react-native-community/react-native-circleci-orb/issues/3)


### Features

* Minor release ([5f401d7](https://github.com/react-native-community/react-native-circleci-orb/commit/5f401d7))

## [1.2.2](https://github.com/react-native-community/react-native-circleci-orb/compare/v1.2.1...v1.2.2) (2019-10-25)


### Bug Fixes

* remove haxm the lack hardware acceleration support causes a crash ([9d0bb42](https://github.com/react-native-community/react-native-circleci-orb/commit/9d0bb42))
* remove haxm the lack hardware acceleration support causes a crash ([38ef88e](https://github.com/react-native-community/react-native-circleci-orb/commit/38ef88e)), closes [#3](https://github.com/react-native-community/react-native-circleci-orb/issues/3)

## [1.2.1](https://github.com/react-native-community/react-native-circleci-orb/compare/v1.2.0...v1.2.1) (2019-06-03)


### Bug Fixes

* Use project_type in ios_build_and_test job ([25c7948](https://github.com/react-native-community/react-native-circleci-orb/commit/25c7948))

# [1.2.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v1.1.2...v1.2.0) (2019-05-14)


### Features

* Allow the metro packager to be started from the test jobs ([68846df](https://github.com/react-native-community/react-native-circleci-orb/commit/68846df))

## [1.1.2](https://github.com/react-native-community/react-native-circleci-orb/compare/v1.1.1...v1.1.2) (2019-05-14)


### Bug Fixes

* Correct the Android java environment variables ([917129a](https://github.com/react-native-community/react-native-circleci-orb/commit/917129a))

## [1.1.1](https://github.com/react-native-community/react-native-circleci-orb/compare/v1.1.0...v1.1.1) (2019-05-14)


### Bug Fixes

* Increase the amount of memory for Android builds ([22e8279](https://github.com/react-native-community/react-native-circleci-orb/commit/22e8279))

# [1.1.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v1.0.0...v1.1.0) (2019-04-25)


### Features

* Add parameters to configure the executors ([7c044cb](https://github.com/react-native-community/react-native-circleci-orb/commit/7c044cb))
