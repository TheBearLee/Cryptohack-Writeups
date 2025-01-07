# Understanding Base64

Base64 is a common encoding scheme that splits binary digits into groups of 6 bits rather than a full 8-bit byte. These six bits are then translated to an ASCII string using an alphabet of 64 characters. Although this lengthens the binary data, it helps hide it from plain sight.

Here is an example to walk through the process of encoding in Base64:

Plaintext: abcdef
Decimal:
$$ 97,98,99,100,101,102$$
Binary Bytes: $$01100001, 01100010, 01100011, 01100100, 01100101, 01100110$$
Binary in 6 bit chunks: $$011000,010110,001001,100011,011001,000110,010101,100110$$
Back into full 8-bit bytes (add 00 padding): $$00011000,00010110,00001001,00100011,00011001,00000110,00010101,00100110$$
Back into decimal: $$24,22,9,35,25,6,21,38$$
Base64 Alphabet Representation: YMJjZGVm

The Base64 alphabet representation is linked for reference [Base64 Characters | Learn | Base64](https://base64.guru/learn/base64-characters)