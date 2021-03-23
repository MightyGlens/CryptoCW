# CryptoCW
This is a program that encodes and decodes using the Affine Cipher.

Encryption:
This uses the maths ciphertext = (alpha times message) + beta or c = am + b

This code will allow alpha keys that won't work for decryption. Acceptable alpha keys are (1, 3 , 5 , 7 , 9, 11, 15 , 17, 19, 21, 23, 25)

Decryption (with keys):
This uses the maths message = the inverse of a times ciphertext - beta or m = (a' x c) - b
The inverse is calculated using the pow() function in Python 3.8+

Decryption (using bruteforce):
This does the decrypt function with every available key pairing. Also included is a dictionary check which sorts by most likely option for the key pairing instead of displaying 312 plaintexts

