//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.domain.jose](../index.md)/[JWK](index.md)

# JWK

@Serializable

interface [JWK](index.md)

This type defines a JSON Web Key (JWK) data structure according to [RFC 7517](https://www.rfc-editor.org/rfc/rfc7517). A JWK is a JSON object that represents a cryptographic key.

#### Inheritors

| |
|---|
| [ESJWK](-e-s-j-w-k/index.md) |
| [RSAJWK](-r-s-a-j-w-k/index.md) |
| [OctJWK](-oct-j-w-k/index.md) |

## Types

| Name | Summary |
|---|---|
| [ESJWK](-e-s-j-w-k/index.md) | [androidJvm]<br>@Serializable<br>data class [ESJWK](-e-s-j-w-k/index.md)(val publicKeyUse: [PublicKeyUse](../-public-key-use/index.md)? = null, val keyOperations: [KeyOperations](../-key-operations/index.md)? = null, val algorithm: [Algorithm](../-algorithm/index.md)? = null, val keyId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val x509Url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val x509CertificateChain: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;? = null, val x509CertificateSHA1Thumbprint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val x509CertificateSHA256Thumbprint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val curve: [EllipticCurve](../-elliptic-curve/index.md), val xCoordinate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val yCoordinate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val privateKey: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) : [JWK](index.md) |
| [OctJWK](-oct-j-w-k/index.md) | [androidJvm]<br>@Serializable<br>data class [OctJWK](-oct-j-w-k/index.md)(val publicKeyUse: [PublicKeyUse](../-public-key-use/index.md)? = null, val keyOperations: [KeyOperations](../-key-operations/index.md)? = null, val algorithm: [Algorithm](../-algorithm/index.md)? = null, val keyId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val x509Url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val x509CertificateChain: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;? = null, val x509CertificateSHA1Thumbprint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val x509CertificateSHA256Thumbprint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val symmetricKey: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [JWK](index.md) |
| [RSAJWK](-r-s-a-j-w-k/index.md) | [androidJvm]<br>@Serializable<br>data class [RSAJWK](-r-s-a-j-w-k/index.md)(val publicKeyUse: [PublicKeyUse](../-public-key-use/index.md)? = null, val keyOperations: [KeyOperations](../-key-operations/index.md)? = null, val algorithm: [Algorithm](../-algorithm/index.md)? = null, val keyId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val x509Url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val x509CertificateChain: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;? = null, val x509CertificateSHA1Thumbprint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val x509CertificateSHA256Thumbprint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val modulus: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val exponent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val privateExponent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val firstPrimeFactor: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val secondPrimeFactor: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val firstFactorCRTExponent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val secondFactorCRTExponent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val firstCRTCoefficient: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) : [JWK](index.md) |

## Properties

| Name | Summary |
|---|---|
| [algorithm](algorithm.md) | [androidJvm]<br>abstract val [algorithm](algorithm.md): [Algorithm](../-algorithm/index.md)? |
| [keyId](key-id.md) | [androidJvm]<br>abstract val [keyId](key-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [keyOperations](key-operations.md) | [androidJvm]<br>abstract val [keyOperations](key-operations.md): [KeyOperations](../-key-operations/index.md)? |
| [keyType](key-type.md) | [androidJvm]<br>abstract val [keyType](key-type.md): [KeyType](../-key-type/index.md) |
| [publicKeyUse](public-key-use.md) | [androidJvm]<br>abstract val [publicKeyUse](public-key-use.md): [PublicKeyUse](../-public-key-use/index.md)? |
| [x509CertificateChain](x509-certificate-chain.md) | [androidJvm]<br>abstract val [x509CertificateChain](x509-certificate-chain.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;? |
| [x509CertificateSHA1Thumbprint](x509-certificate-s-h-a1-thumbprint.md) | [androidJvm]<br>abstract val [x509CertificateSHA1Thumbprint](x509-certificate-s-h-a1-thumbprint.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [x509CertificateSHA256Thumbprint](x509-certificate-s-h-a256-thumbprint.md) | [androidJvm]<br>abstract val [x509CertificateSHA256Thumbprint](x509-certificate-s-h-a256-thumbprint.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [x509Url](x509-url.md) | [androidJvm]<br>abstract val [x509Url](x509-url.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
