# Class 18

[Back to home page](../README.md)

## Cryptography

Q. What is the basic principle behind the Caesar Cipher, and how was it used historically?

- The ceasar cipher was an early form of encription where letters of the alphabet are shifted left a right how ever many places (for example 3. Meaning D is replaced by A, E is replaced by B, so on...). It was one of the earliest ciphers of ever and was primarely used to send secret messages.

Q. What are the key differences between symmetric and asymmetric encryption? How is asymmetric used in secure communication today?

- The main differences are practicality and key numbers. Symmetric encryption is when data is transfered over a secure channel along with a key to access the message. However if you have a secure channel, why not just send the message as well. Asymmetric is slightly different, as there is a key for decryption, and encryption, meaning access to one is only 50 percent of the way to the data. This is still used today in urls and email file transfers to keep yur data safe.

Q. How do computers generate random numbers, and what are the differences between true random number generation (TRNG) and pseudo-random number generation (PRNG)? Discuss their use cases in cryptography.

- TRNG is truely random, and has no way of tracing how it got its numbers. This could be done throught the use physical phenomenon, like key strokes. Unlike an algorithm, a human is not predictable, so it is truely random. PRNG however is when a computer runs an algorithm or uses a seed to create random numbers. The problem with this is if a hacker knows the seed/algorithm, then its easy for them to crack the applications security.

Q. What’s the difference between encryption and decryption? Explain with an analogy.

- Encryption is the act of scrammbling data so that it is much harder to decipher than normal. Decryption on the other handis the process of recovering the data. A good example of this is learning a new language, you use your primary language as reference to understand the new one, or decypher the new language as you learn.
