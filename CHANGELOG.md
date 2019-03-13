# ha-sensor-sl

Changelog of this repo.

The format is based on [Keep a Changelog][keep-a-changelog]
<!-- and this project adheres to [Semantic Versioning][semantic-versioning]. -->

## Unreleased

- No work items present

## [v0.0.8] (2019-03-13)

### Added
- Added boolean parameter adjust_times, when set to true it recalculates time to departure to real time and not what was when latest updated.
- Added boolean parameter hide_departured, when set to true already departed connections are hidden. Requires adjust_times to be set to true.

### Changed
- Rendering strategy

## [v0.0.7] (2018-12-13)

### Added
- Rendering of deviances
- Parameters to customize card

### Changed
- Rendering strategy

## [v0.0.6] (2018-11-16)

### Added
- Added output of icons

### Changed
- Buggfixes in lookup
- Changed rendering in lovelace card

## [v0.0.5] (2018-11-16)

### Added
- Dependency for new https://www.trafiklab.se/api/sl-storningsinformation-2
- Lovelace card

### Changed
- Logging strings changed to indicate which api failed
- User Agent String conforms to standard
- Now renders the next hour of departures

### Removed
- JavaScript output

## [v0.0.4] (2018-09-30)

[Full Changelog][v0.0.0-v0.0.4]

### Added
- Use a binary_sensor to enable/disable API-calls
- Log error code and message once in case of error at API call
- Support for custom_updater

### Changed
- Log error message instead of just reporting failure.

[keep-a-changelog]: http://keepachangelog.com/en/1.0.0/
[v0.0.7]: https://github.com/dsorlov/ha-sensor-sl/tree/v0.0.7
[v0.0.6]: https://github.com/dsorlov/ha-sensor-sl/tree/v0.0.6
[v0.0.5]: https://github.com/dsorlov/ha-sensor-sl/tree/v0.0.5
[v0.0.4]: https://github.com/fredrikbaberg/ha-sensor-sl/tree/v0.0.4
