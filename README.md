# XOR-Crypt-Python

[![PyPI Version](https://img.shields.io/pypi/v/xorCryptPy.svg)](https://pypi.python.org/pypi/xorCryptPy/)
[![Python Versions](https://img.shields.io/pypi/pyversions/xorCryptPy.svg)](https://pypi.python.org/pypi/xorCryptPy/)
[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](LICENSE)

A simple XOR string encryption library based on the JavaScript library [XOR-Crypt](https://github.com/RobLoach/xor-crypt) by [RobLoach](https://github.com/RobLoach) but in Python.

## Installation

```bash
pip install xorCryptPy
```

You can also download the package manually from [PyPI](https://pypi.org/project/xorCryptPy/).

## Usage

Works exactly like the JavaScript version. The same function encrypts and descripts a string using a given key.

```python
from xorCryptPy import xorCrypt

encrypted = xorCrypt('Hello World')
# Outputs: Ncjji&Qitjb

decrypted = xorCrypt(encrypted)
# Outputs: Hello World

# Use your own XOR Key.
encrypted = xorCrypt('Hello World', 9)
decrypted = xorCrypt(encrypted, 9)
```

_(The default key is the same as the one from the JavaScript version!)_

## License

Licensed under the [MIT license](https://opensource.org/licenses/MIT)
