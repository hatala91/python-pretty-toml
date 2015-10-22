# Pretty TOML for Python

[![Build Status](https://travis-ci.org/Jumpscale/python-pretty-toml.svg?branch=master)](https://travis-ci.org/Jumpscale/python-pretty-toml)
[![Python Versions](https://img.shields.io/pypi/pyversions/prettytoml.svg)](https://pypi.python.org/pypi/prettytoml)
[![Release](https://img.shields.io/pypi/v/prettytoml.svg)](https://pypi.python.org/pypi/prettytoml)
![Wheel](https://img.shields.io/pypi/wheel/prettytoml.svg)


A formatter for [TOML](https://github.com/toml-lang/toml) files.

## Installation ##
```bash
pip install --upgrade prettytoml
```

## Usage ##

```python
>>> import prettytoml
>>> prettified_content = prettytoml.prettify_from_file('sample.toml')
>>> with open('sample-prettified.toml', 'w') as fp:
      fp.write(prettified_content)
```
