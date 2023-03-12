# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [0.2.0](https://github.com/capawesome-team/sponsorware/compare/v0.1.0...v0.2.0) (2023-03-12)


### ⚠ BREAKING CHANGES

* The following receiver must be added to your `AndroidManifest.xml` **in** the `application` tag: `<receiver android:name="io.capawesome.capacitorjs.plugins.foregroundservice.NotificationActionBroadcastReceiver" />`

### Features

* support notification buttons ([#3](https://github.com/capawesome-team/sponsorware/issues/3)) ([46f448c](https://github.com/capawesome-team/sponsorware/commit/46f448ce737ab5b8355e5adc9483c355343f7040))

## [0.1.0](https://github.com/capawesome-team/sponsorware/compare/v0.0.2...v0.1.0) (2022-12-09)


### ⚠ BREAKING CHANGES

* The following permission must be added to your `AndroidManifest.xml` before the `application` tag: `<uses-permission android:name="android.permission.WAKE_LOCK" />`

### Features

* keep the CPU on ([#2](https://github.com/capawesome-team/sponsorware/issues/2)) ([f92453d](https://github.com/capawesome-team/sponsorware/commit/f92453dc9594ae622e2745731187ad8dd5fdf2ff))

### [0.0.2](https://github.com/capawesome-team/sponsorware/compare/v0.0.1...v0.0.2) (2022-09-25)


### Features

* open app on notification click ([#1](https://github.com/capawesome-team/sponsorware/issues/1)) ([5754816](https://github.com/capawesome-team/sponsorware/commit/57548161aced2ceac89021c74936c84977875977))

## 0.0.1 (2022-09-05)

Initial release 🎉
