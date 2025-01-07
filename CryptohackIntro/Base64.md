# Base64

This challenge introduces the Base64 encoding scheme. Base64 is covered in detail in another file, featuring how it works and was built. For this challenge, I will skip over the underlying implications of how it works.

To solve this challenge, we must take the hex number that is given to us and decode it into bytes. This can be done using the same Python function ```
``` ```bytes.fromhex()``` that was used in the Hex challenge. Using these bytes, we can feed it into a Base64 encoder using ```base64.b64encode()``` assuming that the base64 module is imported into your file. This will return the flag that can then be uploaded.
