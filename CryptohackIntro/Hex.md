# Hex

This challenge uses hexadecimal, which is a number system I have already discussed in a separate file. 

When using an encryption algorithm, the resulting ciphertext often has bytes that cannot be converted into ASCII characters which is why using a number system that is more portable is necessary.

To solve the challenge, we must take the given hex string and change it back into ASCII to find the flag. This can be done very simply using Python and can even be solved in one line. Use the ```bytes.fromhex()``` function to extract this ASCII flag.


