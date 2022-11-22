# YS-OTP
Yeap-Shannon One-Time-Pad Cryptographic Method and System (YS-OTP)

1. Definition of perfect security (Boneh & Shoup, 2020):
Let ε = (E,D) be a Shannon cipher defined over (K,M,C). Consider a probabilistic experiment in which the random variable k is uniformly distributed over K. If for all m₀, m₁ ∈ M, and all c ∈ C, we have:Pr[E(k,m₀) = c] = Pr[E(k,m₁) = c]then we say that ε is a perfectly secure Shannon cipher.

2. "The theory behind the OTP is that the encryption-key has at least the same length as the message (the plaintext) and consists of truely random numbers. Each letter of the plaintext is 'mixed' with one element from the OTP. This results in a ciphertext that has no relation with the plaintext when the key is unknown. At the receiving end, the same OTP is used to retrieve the original plaintext. For this to work, the following rules are mandatory:

     o The OTP should consist of truely random numbers (noise).

     o Precisely two copies of the OTP should exist.

     o The OTP should only be used once.

     o Both copies of the OTP are destroyed immediately after use. 

     Only if the above rules are strictly obeyed, the OTP is absolutely safe. Adding numbers to the plaintext manually, is a time-consuming task. It is therefore sometimes thought that OTPs are no longer considered practical. However, with modern computer technology, the entire task of mixing and unmixing plaintext with the key, can easily be automated." (Reuvers & Simons, 2014)

3. YS-OTP is a novel attempt to implement the Shannon cipher (Yeap, 2022).

References:

Boneh, D. and Shoup, V. 2020. A Graduate Course in Applied Cryptography

Reuvers, P. & Simons, M. 2014. One-Time Pad (OTP): The unbreakable code, Crypto Museum, 14 March 2014.

Yeap, R. 2022. Yeap-Shannon One-Time-Pad Cryptographic Method and System, IP Blockchain, 7B5020CCD10033BF9A3A9B8C0DB294232E1951F7449A3E81DC113F9F00E5C66D, 2022-11-21.
