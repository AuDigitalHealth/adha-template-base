# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.3.0] - 2026-03-02

### Added

- introduced a mechanism to allow a collapsible plain language description (PLD) section to be rendered at the top of the IG's home page. This required copying the template file `template-page-md.html`from the [HL7 base template](https://github.com/HL7/ig-template-base) in order to insert the PLD section at the appropriate location. The implementation includes a new CSS class for styling the collapsible section.
- added HL7's standard IG build tooling scripts

### Changed

- changed the license from Apache 2.0 to Creative Commons Attribution 4.0 International (CC-BY-4.0)

## [0.2.0] - 2024-11-14

### Changed
- refactored the files in the includes directory for improved template structure
- updated the CSS in the ADHA.css file for improved branding conformance

## [0.1.2] - 2023-12-19

### Added
- a link to the empty fhir.js file so that it is generated on every html page, and therefore made available for use in downstream platforms such as the Developer Portal

## [0.1.1] - 2023-12-12

### Added
- a class attribute was added into a footer paragraph containing corporate information to facilitate its conditional rendering

## [0.1.0] - 2023-09-12

### Changed
- CSS completely reworked by web styling Comms Digital team to comply with latest corporate styling standards

## [0.0.2] - 2023-06-22

### Added
- Add colour setting for the header's central colour (light grey to match existing template)
- Add footer links for version history and proposing a change
- Add empty ini file so that autobuilder works

### Changed
- Revise footer hyperlink colour to align with existing template

## [0.0.1] - 2023-06-09

### Added
- First draft for team review
