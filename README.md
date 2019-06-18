# XOR-Crypt-Python

A simple XOR string encryption library based on the JavaScript library [XOR-Crypt](https://github.com/RobLoach/xor-crypt) by [RobLoach](https://github.com/RobLoach) but in Python.

## Usage

Works exactly like the JavaScript version. The same function encrypts and descripts a string using a given key.

```python
import xorCryptPy

encrypted = xorCryptPy('Hello World')
# Outputs: Ncjji&Qitjb

decrypted = xorCryptPy(encrypted)
# Outputs: Hello World

# Use your own XOR Key.
encrypted = xorCryptPy('Hello World', 9)
decrypted = xorCryptPy(encrypted, 9)
```

_(The default key is the same as the one from the JavaScript version!)_

## License

Licensed under the [MIT license](https://opensource.org/licenses/MIT)
