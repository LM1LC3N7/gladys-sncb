# Changelog

All notable changes to this integration are documented in this file. The format
follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) and the project
uses [semantic versioning](https://semver.org/).

Describe each change under `## [Unreleased]` as you make it. The Release
workflow moves that section under the version it ships, and the section becomes
the notes of the version's GitHub Release.

## [Unreleased]

### Fixed

- Docs: the outputs of the scene actions come from the variable list
  (`{{<step>.<action>.<key>}}`), not `{{<key>}}`.

## [0.1.1] - 2026-10-13

### Added

- One device per watched station (typed in the configuration, with an
  optional destination filter and custom name, or suggested from the
  stations closest to the house): next departure countdown, delayed and
  canceled counts, and per departure the countdown, the delay and a text
  line (train, destination, platform, delay).
- An "SNCB network" device: disturbances and planned works counts, latest
  disturbance.
- Scene triggers "train approaching" (1 to 15 minutes), "train delayed,
  canceled or moved" and "disturbance published".
- Scene actions "next departures" and "disturbances".
- Dashboard widgets "SNCB departures" and "SNCB disturbances".
- "Test iRail" and "Search stations" buttons.

[Unreleased]: https://github.com/LM1LC3N7/gladys-sncb/compare/v0.1.1...HEAD
[0.1.1]: https://github.com/LM1LC3N7/gladys-sncb/releases/tag/v0.1.1
