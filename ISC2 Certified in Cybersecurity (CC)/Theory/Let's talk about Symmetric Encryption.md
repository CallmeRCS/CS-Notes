The main characteristic of a symmetric algorithm is that it uses the same key in both the encryption and the decryption processes. It could be said that the decryption process is a mirror image of the encryption process.
>The same key is used for both the encryption and decryption processes. This means that the 2 parties communicating need to share knowledge of the same key.
#### Challenges of this approach

1. If 2 parties suspect a specific communication path between them is compromised, they obviously can't share the key material along the path. It could be the key intercept.
2. Distribution of the key is difficult, because the key cannot be sent in the same channel as the encrypted message, or the man-in-the-middle would have access to the key. ==Sending the key through a different channel (band) the encrypted message is called "out-of-band key distribution"==.
3. Any party with knowledge of the key can access and therefore change the message.
4. In term of scalability, as more users wants to communicate; ==the number of keys needed grows quickly as the number of different users or groups increase==.
#### Primary uses of symmetric algorithms

- Encrypting bulk data (backups, hard drives, portable media).
- Encrypting messages traversing communications channels (IPsec, TLS).
- Streaming large scale, time sensitive data.
#### Other names of this technique

- Same key
- Single key
- Shared key
- Secret key
- Session key
#### Example of symmetric encryption via decoding ring

An example of **symmetric encryption** is a substitution cipher, which involves the simple process of substituting letters for other letters, or more appropriately, substituting bits for other bits based upon a crypto variable. These ciphers involve replacing each letter of the plaintext with another that may be further down the alphabet.

![[Pasted image 20240909162536.png]]

