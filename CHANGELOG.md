# Change Log

All notable changes to the "ps4sqlite3" extension will be documented in this file.

This file is structured according to the [Keep a Changelog standard](http://keepachangelog.com/).

## [Unreleased]

## **0.2.0-pre1**

### Added

- CREATE TABLE SQLs:
  - For Normal tables
  - For tables with the `PRIMARY KEY` field
- Quick start snippet that connects to a DB in memory.

### Fixed

- Now *table* and *field* names have double quotes surrounding them to avoid errors.

### Changed

Changed CHANGELOG.md and [README.md](./README.md)

## **0.1.1**

### Fixed

Fixed "bug" where you would have to tab after changing the last placeholder.

## **0.1.0**

Initial release of Python Snippets for SQLite3!

### Added

- Code snippet for starting quick sqlite3 scripts.
- SQL queries snippets for:
  - INSERT SQLs:
    - INSERT INTO SQLs
    - INSERT INTO SQLs with `?` parameters
  - SELECT SQLs:
    - SELECT WHERE SQLs
    - SELECT WHERE LIKE SQLs
