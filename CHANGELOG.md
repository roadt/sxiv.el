# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.4.1] - 2021-05-14
### Fixed
* Use unique buffer name for process output.

## [0.4.0] - 2021-04-06
### Added
* When launching from a text file, open sxiv with the image at point (using `-n`)

## [0.3.3] - 2020-08-03
### Fixed
* Error with selected files in a subdirectory (issue #1)

## [0.3.2] - 2020-05-08
### Fixed
* Workaround for crash in certain cases

## [0.3.1] - 2020-03-25
### Added
* Marking files now works recursively, too.
* Show message when starting sxiv

## [0.3.0] - 2020-01-14
### Added
* Open sxiv at the image at point

## [0.2.0] - 2020-01-13
### Added
* `sxiv-arguments` to hold argument list
* `sxiv-exclude-strings` to exclude files by matching paths
### Fixed
* Slow startup/freezing on large directories
* `package-lint` fixes

## [0.1.0] - 2020-01-12
