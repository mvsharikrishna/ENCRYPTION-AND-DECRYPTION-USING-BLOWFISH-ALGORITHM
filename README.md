# ENCRYPTION-AND-DECRYPTION-USING-BLOWFISH-ALGORITHM
In the fields of information security and cryptography, encryption is the process of encoding a message or information in a way that only authorized parties can access it and those who are not authorized cannot. In this project, data is encrypted and decrypted using BLOWFISH ALGORITHM.

Blowfish is a symmetric encryption algorithm, meaning that it uses the same secret key to both encrypt and decrypt messages. Blowfish is also a block cipher, meaning that it divides a message up into fixed length blocks during encryption and decryption. The block length for Blowfish is 64 bits; messages that aren't a multiple of eight bytes in size must be padded.

Blowfish is an encryption technique designed by Bruce Schneier in 1993 as an alternative to DES Encryption Technique. It is significantly faster than DES and provides a good encryption rate. It is one of the first, secure block ciphers not subjects to any patents and hence freely available for anyone to use.

In general there are some requirements to implement Blowfish Algorithm,
•	Block Size: 64 bits
•	Key Size: 32 bits to 448 bits variable size
•	Number of subkeys: 18 [P- array]
•	Number of rounds: 16
•	Number of substitution boxes: 4 [each having 256 entries of 32 bits each]
