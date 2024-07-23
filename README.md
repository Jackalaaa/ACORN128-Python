# ACORN128-Python
A recreation in Python of ACORN-128 created by Hongjun Wu.

----------

https://competitions.cr.yp.to/round3/acornv3.pdf

ACORN is a lightweight authenticated stream cipher designed by Hongjun Wu as part of
the CAESAR Encryption competition. ACORN operates to satisfy three main features:
simplicity, efficiency, and security. It uses a 128-bit key and 128-bit initialization vector to
produce a keystream which is then XORed with either plaintext for encryption or ciphertext
for decryption. ACORN is structured to iterate through linear feedback shift registers
(LFSRs) to improve security by creating a pseudorandom pattern of 0s and 1s. ACORN’s
design allows for well-suited implementations in software environments that have limited
computational capabilities.

----------

This was created for my Mathematics and Computer Science project at Loughborough University which led to me achieving a 1:1 for the module it was created for.
