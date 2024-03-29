# ScreenTransitions Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).
**For 1.2.2 release and previous ones, this is a copy/paste from FredericRP's Standard Assets changelog, filtered for this sub package (that's why some version have no content here).**

## Unreleased

## [1.3.3] - 2022-10-18

### Fixed
- Missing InputSystem asmdef references

## [1.3.2] - 2022-04-06

### Fixed
- Auto dependencies in package

## [1.3.1] - 2021-10-12

### Added
- A black 4x4 pixel texture

### Changed
- Using the black texture for the cutOff transition to demonstrate a kind-of Animal Crossing transition.

## [1.3.0] - 2021-09-15

### Changed
- Use its own repository
- Do not use GUIDs for assembly references to make it clearer if an assembly is not found

### Fixed
- ScreenTransitions: Debug messages are enabled only when UNITY_EDITOR and DEBUG are defined
- links to images for Transition sub package on README

## [1.2.2] - 2021-07-30

### Changed
- MOD: Transition namespace has been renamed to ScreenTransitions to prevent namespace conflicting with Transition class
**Breaking change**: use only GameEvent (Raise, Listen, Delete) methods instead of EventHandler (Trigger, Add, Remove), that was always meant to be that way.

### Fixed
- FIX: Editor platform only for editor assemblies on asset bundle tool, event management and object pool
- FIX: transition animations for 16/9 ratio

## [1.2.1] - 2020-07-30

### Added
- NEW: Installation guidelines for both package and submodule.

### Changed
- MOD: transition supports both legacy and new input system
- MOD: make package manager compatible
- MOD: transition is no more a singleton to allow multiple instances. Get the right one from its name.

### Fixed
- FIX: changelog meta files
- FIX: correct MIT license for every package
- FIX: readme file with updated Documentation folder

## [1.2.0] - 2019-11-19

### Changed
- MOD: updated readme files for each plugin
- MOD: updated readme file for full instructions

### Fixed
- FIX: transition animator call when exiting play mode caused a null ref exception

## [1.1.0] - 2019-10-27

## [1.0.1] - 2019-10-16

### Added
- NEW: github social preview
- NEW: transition demo gif

### Changed
- MOD: pictures to illustrate transition and object pool
- MOD: all previous readme.txt changed to markdown format

### Removed
- DEL: removed first package export

## [1.0.0] - 2019-08-08

### Added
- first public release: a generic event handler to trigger and subscribe game events in your game in a minute.

### Changed

### Deprecated

### Removed

### Fixed

### Security
