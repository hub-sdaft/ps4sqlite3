# ps4sqlite3 README

The **Python Snippets for SQLite3** extension is a simple extension that provides Python code snippets using the sqlite3 module.

## Features

This extension just provides simple code snippets if you need to program with Python and sqlite3.

- If you write `psq/start` and tab, the extension will write the following code:

```python
import sqlite3

connection = sqlite3.connect("filename")
cursor = connection.cursor()
with connection:
    # Code
    connection.commit()
```

- There are also many other code snippets for SQL queries using the `execute()` method.

## Requirements

- Python 3 interpreter
- VSCode 1.46.0 

## Known Issues

None, for now.

## Release Notes

Here are the extension's Release Notes. More details [here](./CHANGELOG.md)

### [0.1.0](./CHANGELOG.md#0.1.0)

Initial release of Python Snippets for SQLite 3 (ps4sqlite3).
**Added** quick start code snippets and SQL snippets.
