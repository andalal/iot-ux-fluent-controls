# CHANGELOG

## v4.0.7
### Fixed
- InlinePopup should be disableable

## v4.0.6
### Fixed
- remove cancel button when input is readonly

## v4.0.5
### Fixed
- hover background for alert close button was incorrect on all browsers except firefox

## v4.0.4
### Fixed
- add padding to fix select dropdown component where selected text overlaps with the icon

## v4.0.2
### Fixed
- fix crawling ant color for light and dark theme
- update documentation backgrounds for loaders

## v4.0.1
### Fixed
- remove publish restriction
- fix bugs url

## v4.0.0
### Changed
- move to @microsoft npm scope

## v3.0.4
### Fixed
- toggle controls need switch role for screen readers
- prevent default and stop propagation for tooltip keyboard shortcut in form field

## v3.0.3
### Fixed
- screen reader support for calendar
- take in props to override browser locale for calendar

## v3.0.2
### Fixed
- expose callback for clicking calendar icon in date picker. includes next visible state.
- blur handler for form field tooltip so it will close when focus leaves the field

## v3.0.1
### Fixed
- blur listener for datepicker was too greedy.
- shrink calendar
- move date picker window listers to component mounting events

## v3.0.0
### Changed
- calendar api changed. no longer extends drop down
### Fixed
- calendar in datepicker is now reachable via keyboard

## v2.0.5
### Fixed
- date picker should not open when input receives focus

## v2.0.4
### Fixed
- add outline for danger button
- upgrade fluent css version

## v2.0.3
### Fixed
- add outline for primary button
- upgrade fluent css version

## v2.0.2
migrating to private package registry and changing package scope.
update references to fluent css

## v2.0.1
### Fixed
- alert close button hover colors didn't work across themes. updated to newer version of fluent-colors
- update git ignore to include static folder

## v2.0.0
### Changed
- Alert close button changed from Icon to ActionTriggerButton

### Removed
- Alert.attr.closeIcon

### Added
- Alert.attr.closeButtonTitle
