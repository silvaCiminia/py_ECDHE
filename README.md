# py_ECDHE
## Synopsis
An Elliptical Curve algorithm optimized for Diffie-Hellman key exchanges

## Usage

Returns a 64 byte private key and a 128 byte public key.

* To generate a keypair:

    `(myPublicKey, myPrivateKey) = ecdhe.make_keypair()`

* To generate a shared secret:

    `sharedSecret = ecdhe.scalar_mult(myPrivateKey, theirPublicKey)`
    
