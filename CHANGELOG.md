# CHANGELOG

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/) and [Keep a Changelog](http://keepachangelog.com/).



## Unreleased
---

### New

### Changes

### Fixes

### Breaks


## 0.4.0 - (2020-12-16)
---

### New
* Maintain a `CHANGELOG.md` file.
* Include `generichide` field in `UrlSpecificResources`.

### Fixes
* Include `Cargo.lock` in source control, fixing incorrect dependency resolution [#15](https://github.com/ArniDagur/python-adblock/issues/15).

### Breaks
* Remove `explicit_cancel` field from `BlockerResult`, as it has been removed upstream.


## 0.3.2 - (2020-09-22)
---

### New
* Build Python 3.9 wheels.

### Changes
* Updated PyO3 to version `0.12`.

### Fixes
* Don't use star imports in `__init__.py` to give linters and type checkers more information.