<h3>Hill Cipher</h3>

Given: Correspondence between plaintext and number modulo 31 are as follows:
A ↔ 0,B ↔ 1,C ↔ 2, ... Z ↔ 25,“,”↔ 26,“.”↔ 27,“?”↔ 28, “!”↔ 29and“ ”(space)↔ 30

<strong>Description</strong>

This code is to find the key(K) and then decrypt the given ciphertext. 

<strong>Steps</strong>

Firstly, based on the given ciphertext and plaintext blocks, C = K * P mod 31 can help us find out the key.

Then, according to the P = C * K'(K' is the inverse of K), the plaintext can be computed.
