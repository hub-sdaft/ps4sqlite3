# Change Log

All notable changes to the "ps4sqlite3" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## 1.0.0

Initial release of Python Snippets for SQLite3

### Added

Code snippet for starting quick sqlite3 scripts.

```python
import sqlite3

conn = sqlite3.connect("database_name")
cur = conn.cursor()
with conn:
    conn.commit()
```