//[sdk](../../../../index.md)/[eu.epicompany.mobile.sdk.domain.jose](../../index.md)/[JWK](../index.md)/[ESJWK](index.md)

# ESJWK

[androidJvm]\
@Serializable

data class [ESJWK](index.md)(val publicKeyUse: [PublicKeyUse](../../-public-key-use/index.md)? = null, val keyOperations: [KeyOperations](../../-key-operations/index.md)? = null, val algorithm: [Algorithm](../../-algorithm/index.md)? = null, val keyId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val x509Url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val x509CertificateChain: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;? = null, val x509CertificateSHA1Thumbprint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val x509CertificateSHA256Thumbprint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val curve: [EllipticCurve](../../-elliptic-curve/index.md), val xCoordinate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val yCoordinate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val privateKey: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) : [JWK](../index.md)

## Constructors

| | |
|---|---|
| [ESJWK](-e-s-j-w-k.md) | [androidJvm]<br>constructor(publicKeyUse: [PublicKeyUse](../../-public-key-use/index.md)? = null, keyOperations: [KeyOperations](../../-key-operations/index.md)? = null, algorithm: [Algorithm](../../-algorithm/index.md)? = null, keyId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, x509Url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, x509CertificateChain: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;? = null, x509CertificateSHA1Thumbprint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, x509CertificateSHA256Thumbprint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, curve: [EllipticCurve](../../-elliptic-curve/index.md), xCoordinate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), yCoordinate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), privateKey: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |

## Functions

| Name | Summary |
|---|---|
| [toPublicKey](to-public-key.md) | [androidJvm]<br>fun [toPublicKey](to-public-key.md)(): [JWK.ESJWK](index.md)<br>Returns a copy of this JWK without the data related to the private key, if the JWK contains a private key. The remaining data, if present, only represents the public key. |

## Properties

| Name | Summary |
|---|---|
| [algorithm](algorithm.md) | [androidJvm]<br>open override val [algorithm](algorithm.md): [Algorithm](../../-algorithm/index.md)? = null |
| [curve](curve.md) | [androidJvm]<br>val [curve](curve.md): [EllipticCurve](../../-elliptic-curve/index.md) |
| [keyId](key-id.md) | [androidJvm]<br>open override val [keyId](key-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [keyOperations](key-operations.md) | [androidJvm]<br>open override val [keyOperations](key-operations.md): [KeyOperations](../../-key-operations/index.md)? = null |
| [keyType](key-type.md) | [androidJvm]<br>open override val [keyType](key-type.md): [KeyType](../../-key-type/index.md) |
| [privateKey](private-key.md) | [androidJvm]<br>val [privateKey](private-key.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [publicKeyUse](public-key-use.md) | [androidJvm]<br>open override val [publicKeyUse](public-key-use.md): [PublicKeyUse](../../-public-key-use/index.md)? = null |
| [x509CertificateChain](x509-certificate-chain.md) | [androidJvm]<br>open override val [x509CertificateChain](x509-certificate-chain.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;? = null |
| [x509CertificateSHA1Thumbprint](x509-certificate-s-h-a1-thumbprint.md) | [androidJvm]<br>open override val [x509CertificateSHA1Thumbprint](x509-certificate-s-h-a1-thumbprint.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [x509CertificateSHA256Thumbprint](x509-certificate-s-h-a256-thumbprint.md) | [androidJvm]<br>open override val [x509CertificateSHA256Thumbprint](x509-certificate-s-h-a256-thumbprint.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [x509Url](x509-url.md) | [androidJvm]<br>open override val [x509Url](x509-url.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [xCoordinate](x-coordinate.md) | [androidJvm]<br>val [xCoordinate](x-coordinate.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [yCoordinate](y-coordinate.md) | [androidJvm]<br>val [yCoordinate](y-coordinate.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
