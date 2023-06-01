//[core](../../../../index.md)/[eu.epicompany.mobile.core.domain.jose](../../index.md)/[JWK](../index.md)/[RSAJWK](index.md)/[toPublicKey](to-public-key.md)

# toPublicKey

[androidJvm]\
fun [toPublicKey](to-public-key.md)(): [JWK.RSAJWK](index.md)

Returns a copy of this JWK without the data related to the private key, if the JWK contains a private key. The remaining data, if present, only represents the public key.
