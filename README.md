# humanify

[![GitHub license](https://img.shields.io/github/license/ef4203/humanify.svg)](https://github.com/ef4203/humanify/blob/master/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/ef4203/humanify.svg)](https://github.com/ef4203/humanify/issues)
[![Build Status](https://api.travis-ci.org/ef4203/humanify.svg?branch=master)](https://travis-ci.com/ef4203/humanify)

Python library to convert a timestamp object into a human readable string

## Examples

```python
#!/usr/bin/env python3
import humanify
import datetime

current_date = datetime.datetime.now()

print(humanify.time_only(current_date))
print(humanify.date(current_date))
print(humanify.datetime(current_date))
```

## Installation

Directly with `pip`:

```bash
pip install -U https://github.com/ef4203/humanify/archive/master.zip
```

With [Pipenv](https://pipenv.pypa.io/en/latest/):

```bash
pipenv install -e git+https://github.com/ef4203/humanify/archive/master.zip
```

## Further Documentation

You may find more information about humanify in the [documentation](docs/index.md) files.
