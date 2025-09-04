As the main concept, this technique uses one key to encrypt and a different key to decrypt the input plaintext. This is stark contrast to symmetric encryption, which uses the same key to encrypt and decrypt.
> For most security professionals, the math of asymmetric encryption can be left to the cryptanalysts and cryptographers to know.
#### Now, let's see how it really works out

First the user that wish to communicate using an asymmetric algorithm would first generate a keypair. To ensure the strength of the key generation process, this is usually done by the cryptographic application or the public key infrastructure (PKI) implementation without user involvement. One half of the key pair is kept secret; only the key holder knows that key (this is the private key). 
>The public key (the other half of the equation) can be given freely to anyone who wants a copy. In many companies, it may be available through the corporate websites or access to a key server. There, this second half of the key pair is referred to as the public key. Anyone can encrypt something using the recipient's public key, but only the recipient with their private key can decrypt it.
#### Issues that asymmetric approach has against symmetric

- It solves the problem of key distribution by allowing a message to be sent across an untrusted medium in a secure manner without the overhead of prior key exchange or key material distribution.
- It also solves the problem of scalability. It does scale well as numbers increase, as each party only requires a key pair, the private and public keys. 
	>An organization with 100000 employees would only need a total of 200000 keys (one private and one public for each employee). This is less than half of the number of keys that would be required for symmetric encryption.

The one problem, however, has been that asymmetric cryptography is extremely slow compared with its symmetric counterpart.
>This is because asymmetric key cryptography handles much larger keys and is mathematically intensive, thereby reducing the speed significantly.
