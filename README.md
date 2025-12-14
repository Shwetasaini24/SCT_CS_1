# Caesar Cipher in Python

This project implements the Caesar Cipher algorithm, one of the earliest and simplest encryption techniques. The program encrypts and decrypts a given message by shifting each alphabetic character by a fixed number of positions defined by the user.

## How It Works
- Each letter is converted to its ASCII value.
- A fixed shift value (key) is added or subtracted.
- Modulo 26 arithmetic is used to handle wrap-around from Z to A.
- Uppercase and lowercase letters are preserved.
- Numbers, spaces, and symbols remain unchanged.

## Features
- User input for message and shift value
- Encryption and decryption functionality
- Case-sensitive handling of characters
- Simple and readable Python implementation

## Usage
Run the program and enter the message and shift value when prompted:
