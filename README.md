# py_ECDHE
## Synopsis
An Elliptical Curve algorithm optimized for Diffie-Hellman key exchanges

## Usage

Returns a 64 byte private key and a 128 byte public key.

* To generate a keypair:

    `(myPublicKey, myPrivateKey) = py_ECDHE.make_keypair()`

* To generate a shared secret:

    `sharedSecret = scalar_mult(myPrivateKey, theirPublicKey)`
    
