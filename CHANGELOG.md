# Change Log

## [0.4.4] - 2018-09-01

### Fixed

- Fixed performances issues while parsing on Python 2.7.


## [0.4.3] - 2018-08-28

### Fixed

- Fixed handling of characters that need escaping when inserting/modifying a string element.
- Fixed missing newline after table header.
- Fixed dict-like behavior for tables and documents.


## [0.4.2] - 2018-08-06

### Fixed

- Fixed insertion of an element after deletion.


## [0.4.1] - 2018-08-06

### Fixed

- Fixed adding an element after another element without a new line.
- Fixed parsing of dotted keys inside tables.
- Fixed parsing of array of tables with same prefix.


## [0.4.0] - 2018-07-23

### Added

- `dumps()` now also accepts a raw dictionary.

### Changed

- `add()`/`append()`/`remove()` now return the current `Container`/`Table` to provide a fluent interface.
- Most items not behave like their native counterparts.

### Fixed

- Fixed potential new lines inside an inline table.


## [0.3.0] - 2018-07-20

### Changed

- Make new dicts automatically sorted when dumped.
- Improved new elements placement when building.
- Automatically convert lists of dicts to arrays of tables.
- No longer add a new line before standalone tables.
- Make arrays behave (mostly) like lists.

### Fixed

- Fixed string parsing when before last char is a backslash character.
- Fixed handling of array of tables after sub tables.
- Fixed table display order.
- Fixed handling of super tables with different sections.
- Fixed raw strings escaping.


[Unreleased]: https://github.com/sdispater/tomlkit/compare/0.4.4...master
[0.4.4]: https://github.com/sdispater/tomlkit/releases/tag/0.4.4
[0.4.3]: https://github.com/sdispater/tomlkit/releases/tag/0.4.3
[0.4.2]: https://github.com/sdispater/tomlkit/releases/tag/0.4.2
[0.4.1]: https://github.com/sdispater/tomlkit/releases/tag/0.4.1
[0.4.0]: https://github.com/sdispater/tomlkit/releases/tag/0.4.0
[0.3.0]: https://github.com/sdispater/tomlkit/releases/tag/0.3.0
[0.2.0]: https://github.com/sdispater/tomlkit/releases/tag/0.2.0