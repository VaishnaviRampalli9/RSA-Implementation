#RSA Encryption/Decryption with CRT Decryption

This project implements RSA encryption and decryption using Chinese Remainder Theorem (CRT) for efficient decryption. It also demonstrates key generation, encryption, and decryption with random prime numbers, using a small public exponent e and handling small private exponent d.

#Project Background

This project was created as part of the "Information Theory, Coding and Cryptography" course during my graduation. As part of the course, we were tasked with doing a literature analysis of the research paper: "Dual RSA and Its Security Analysis" by Hung-Min Sun, Mu-En Wu, Wei-Chi Ting, and M. Jason Hinek.
The paper discusses a variant of the traditional RSA cryptosystem called Dual RSA, which introduces a method for more efficient encryption and decryption using two pairs of keys (public and private), providing the cryptographic community with alternatives for improving the performance and security of RSA-based systems. We were required to understand the concepts from the paper and implement them.

#Security Considerations

This implementation is educational and may not be secure for real-world applications.
For production systems, it is recommended to use cryptographic libraries like PyCryptodome or Cryptography that provide secure implementations of RSA.