# XOR-Crypt-Python

A simple XOR string encryption library based on the Javascript library [XOR-Crypt](https://github.com/RobLoach/xor-crypt) by [RobLoach](https://github.com/RobLoach) but in Python

## Usage

Works exactly like the Javascript version. The same function encrypts and descripts a string using a given key.

```python
encrypted = xorCrypt('Hello World')
# Outputs: Ncjji&Qitjb

decrypted = xorCrypt(encrypted)
# Outputs: Hello World

# Use your own XOR Key.
var encrypted = xorCrypt('Hello World', 9)
var decrypted = xorCrypt(encrypted, 9)
```

_(The default key is the same as the one from the Javascript version!)_

## License

Licensed under the [MIT license](https://opensource.org/licenses/MIT)
