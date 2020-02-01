# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


# [Unreleased]
## Features
* Add `CHANGELOG.md` which follow Keep a Changelog format
* Officially adopt to Semantic Versioning

## Fixes
* None

## Breaking Changes
* None


# [2.7.0] 2020-01-25
## Features
* Update pipfile.lock to use appdaemon 4.0.1
* Use 'automation_fixture' in integration tests

## Fixed
* Fix bug with appdaemon >= 4.0.0

## Breaking Changes
* Deprecate direct use of `hass_functions` in favor of new `hass_mocks`


# [2.6.1] 2019-12-23
## Features
* Add support for kwargs in 'turned_off' - Contributed by @snjoetw

## Fixes
* Fix bug when turning on/off via service - Contributed by @snjoetw

## Breaking Changes
* None


# [2.6.0] 2019-11-21
## Features
* 'get_state' support call w/o args (get all state) + more mocked functions - Contributed by @foxcris
* Support for new functions run_at, entity_exists, extended support for function get_state
* Add name attribute to mock hass object

# [2.5.1] 2019-09-20
## Features
* Add various `run_*` functions to `hass_mocks`
* Add sunrise/sunset scheduler

## Fixues
* None

## Breaking Changes
* None


# [2.5.0] 2019-09-11
## Features
* Add cancel timer to time_travel

## Fixes
* None

## Breaking Changes
* None



# [2.4.0] 2019-08-13
## Features
* Add 'run_minutely' to callback - Contributed by @jshridha

## Fixes
* None

## Breaking Changes
* None


# [2.3.3] 2019-08-05
## Features
* None

## Fixes
* Register pytest custom marks to remove warnings
* Update deps to fix security vulnerability
* Fix get_state to match appdaemon's api - Contributed by @jshridha

## Breaking Changes
* None


# [2.3.2] 2019-08-03
## Features
* Patch `notify` and add test for extra patched functions
* Update PyCharm configs
* Use @automation_fixture

## Fixes
* None

## Breaking Changes
* None


# [2.3.1] 2019-04-11
## Features
* Add complex code example in `README.md`
* Update documentation with 'attribute' in `get_state`

## Fixes
* Remove useless dependencies

## Breaking Changes
* None


# [2.3.0] 2019-04-11
## Features
* Support for passing 'attribute' argument to get_state

## Fixes
* None

## Breaking Changes
* None


# [2.2.0] 2019-04-11
## Features
* Mock Hass 'self.log()/error()' with native python logging
* Move pytester config fixture to conftest

## Fixes
* None

## Breaking Changes
* None


# [2.1.1] 2019-04-10
## Features
* Refactor framework initialization

## Fixes
* None

## Breaking Changes
* Patched 'hass_functions' now return 'None' by default


# [2.1.0] 2019-04-10
## Features
* Assert callbacks were registered during 'initialize()'

## Fixes
* None

## Breaking Changes
* None


# [2.0.2] 2019-04-09
## Features
* Update description on PyPi

## Fixes
* None

## Breaking Changes
* None


# [2.0.1] 2019-04-09
## Features
* None

## Fixes
* Update deps to prevent security vulnerabilities

## Breaking Changes
* None


# [2.0.0] 2019-04-09
## Features
* Added `@automation_fixture`

## Fixes
* None

## Breaking Changes
* None


# [1.2.5] 2018-12-24
## Features
* Undocumented

## Fixes
* Undocumented

## Breaking Changes
* Undocumented


# [1.2.4] 2018-12-06
## Features
* Undocumented

## Fixes
* Undocumented

## Breaking Changes
* Undocumented


# [1.2.3] 2018-12-06
## Features
* Undocumented

## Fixes
* Undocumented

## Breaking Changes
* Undocumented


# [1.2.2] 2018-08-12
## Features
* Undocumented

## Fixes
* Undocumented

## Breaking Changes
* Undocumented


# [1.2.1] 2018-08-04
## Features
* Undocumented

## Fixes
* Undocumented

## Breaking Changes
* Undocumented


# [1.2.0] 2018-08-04
## Features
* Undocumented

## Fixes
* Undocumented

## Breaking Changes
* Undocumented


# [1.1.1] 2018-07-23
## Features
* Undocumented

## Fixes
* Undocumented

## Breaking Changes
* Undocumented


# [1.1.0] 2018-07-23
## Features
* Undocumented

## Fixes
* Undocumented

## Breaking Changes
* Undocumented


# [1.0.0] 2018-07-16
## Features
* Initial release

## Fixes
* None

## Breaking Changes
* None