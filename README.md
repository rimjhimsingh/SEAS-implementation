# SEAS-implementation
Implementation of Simplified AES.


Explanation of code, functions used and output is included in SimplifiedAES.pdf file. Executable code is in the file named seas.java


About SEAS: Simplified AES (S-AES) was developed by Professor Edward Schaefer of Santa Clara 
University and several of his students. It is an educational rather than a secure encryption 
algorithm. It has similar properties and structure to AES with much smaller parameters. 

The encryption algorithm takes a 16-bit block of plaintext as input and a 16-bit key 
and produces a 16-bit block of ciphertext as output. The S-AES decryption algorithm takes a
16-bit block of ciphertext and the same 16-bit key used to produce that ciphertext as input and 
produces the original 16-bit block of plaintext as output. The encryption algorithm involves the 
use of four different functions, or transformations: add key, nibble substitution (NS), shift row 
(SR), and mix column (MC)

![image](https://user-images.githubusercontent.com/54510650/213914781-7cf53214-d030-49af-b943-99596cb3ac4d.png)

![image](https://user-images.githubusercontent.com/54510650/213914806-e88e6fa9-6ec4-4791-beec-bafdcdfdbbbc.png)

