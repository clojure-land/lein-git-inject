# Change Log
All notable changes to this project will be documented in this file. This change log follows the conventions of [keepachangelog.com](http://keepachangelog.com/).

## [Unreleased]

## [0.0.11] - 2020-01-15

#### Added

- Add support for environment variables as values of ignore-dirty? config

## [0.0.10] - 2020-01-13

#### Fixed

- Fix support for multiple tags on a single commit. 

## [0.0.9] - 2020-01-09

#### Added

- Add ignore-dirty? config

## [0.0.8] - 2020-01-09

#### Fixed

- Fix support for unusual git histories; i.e. more than result for
  `git rev-list --max-parents=0 HEAD`

## [0.0.7] - 2020-01-07

### Breaking 

Changed the default tag structure from `version/N.N.N` to `vN.N.N`
