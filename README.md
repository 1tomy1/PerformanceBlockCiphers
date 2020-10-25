# PerformanceBlockCiphers

This is my M.Eng. master's thesis. Because I want to support my local language it's written in Slovene. Written in LaTeX.

## Performance analysis of symmetric block ciphers

Data encryption is the most common way to secure data during transmission over public channels. Mostly used is standard AES, which is a symmetric block cipher. To provide data confidentiality, integrity and authentication block ciphers use modes of operation. In the scope of the thesis statistical methods were used to compare the performance of different implementations of symmetric block ciphers and modes of operation. We have found hardware accelerated AES to be 11.1 and 14.9 times faster than non-accelerated for encryption and decryption respectfully. Non-accelerated AES was the fastest compared to other comparable ciphers. The fastest AEAD mode of operation is OCB, while CTR and CBC are the fastest common modes for encryption and decryption respectfully.
