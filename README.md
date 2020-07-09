# ps4sqlite3 README

## If you want to install and use this extension, **[go here](#Installation)**.

The **Python Snippets for SQLite3** (ps4sqlite3) extension is a simple VSCode extension that provides Python code snippets for the sqlite3 module.

## Features

This extension just provides simple code snippets if you need to program with Python and sqlite3.

- All the snippets start with the prefix `psq/`
  - For example if you write `psq/start` and press tab, the extension will write the following code:

```python
import sqlite3

connection = sqlite3.connect("filename")
cursor = connection.cursor()
with connection:
    # Code
    connection.commit()
```

- There are also many other code snippets for SQL queries using the `execute()` method for the Cursor object.

## Requirements

- Python 3 interpreter
- VSCode 1.46.0
- It is recommended to have the **Editor: Tab Completion** option set to ON.

## Installation

- You can download the Latest Release **[here](releases)**;
- Then, you can put the extracted folder on the following folders: 
  - **Windows**: `%USERPROFILE%\.vscode\extensions`
  - **macOS**: `~/.vscode/extensions`
  - **Linux**: `~/.vscode/extensions`

(More information *[here](extensions)*)

## Known Issues

- There are issues with the `psq/table` and `psq/table-key` commands, where declaring a field as `NOT NULL`
and `UNIQUE`. As of writing this, there's not really an immediate fix.

## Release Notes

Here are the extension's Release Notes. More details [here](./CHANGELOG.md)

### **[0.2.0-pre1](./CHANGELOG.md#0.2.0-pre1)**

**Added** new SQL queries for creating tables and connections to DBs in memory.
Now table and field names have double quotes around them.

### **[0.1.1](./CHANGELOG.md#0.1.1)**

**Fixed** bug.

### **[0.1.0](./CHANGELOG.md#0.1.0)**

Initial release of Python Snippets for SQLite 3 (ps4sqlite3).
**Added** quick start code snippets and SQL snippets.

[releases]: https://github.com/hub-sdaft/ps4sqlite3/releases/tag/v0.1.1
[extensions]: https://code.visualstudio.com/docs/editor/extension-gallery#_where-are-extensions-installed