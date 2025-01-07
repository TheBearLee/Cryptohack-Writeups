# Great Snakes

This challenge involves downloading a Python file named `greatsnakes.py` and running it locally.

It involves making sure that your version of Python is Python 3, as that is the version that is required for this course.

Within the file is an array of numbers that form an unreadable message that you can only assume is the flag. Once run, each number passes through `chr(o ^ 0x32) for o in ords` which XORs each number with the hexadecimal number representing 50. This decrypts the cipher and produces the flag needed to pass the challenge.