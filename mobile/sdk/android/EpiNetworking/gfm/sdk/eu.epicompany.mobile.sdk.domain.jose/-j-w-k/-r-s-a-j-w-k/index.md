//[sdk](../../../../index.md)/[eu.epicompany.mobile.sdk.domain.jose](../../index.md)/[JWK](../index.md)/[RSAJWK](index.md)

# RSAJWK

[androidJvm]\
@Serializable

data class [RSAJWK](index.md)(val publicKeyUse: [PublicKeyUse](../../-public-key-use/index.md)? = null, val keyOperations: [KeyOperations](../../-key-operations/index.md)? = null, val algorithm: [Algorithm](../../-algorithm/index.md)? = null, val keyId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val x509Url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val x509CertificateChain: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;? = null, val x509CertificateSHA1Thumbprint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val x509CertificateSHA256Thumbprint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val modulus: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val exponent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val privateExponent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val firstPrimeFactor: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val secondPrimeFactor: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val firstFactorCRTExponent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val secondFactorCRTExponent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val firstCRTCoefficient: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) : [JWK](../index.md)

## Constructors

| | |
|---|---|
| [RSAJWK](-r-s-a-j-w-k.md) | [androidJvm]<br>constructor(publicKeyUse: [PublicKeyUse](../../-public-key-use/index.md)? = null, keyOperations: [KeyOperations](../../-key-operations/index.md)? = null, algorithm: [Algorithm](../../-algorithm/index.md)? = null, keyId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, x509Url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, x509CertificateChain: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;? = null, x509CertificateSHA1Thumbprint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, x509CertificateSHA256Thumbprint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, modulus: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), exponent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), privateExponent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, firstPrimeFactor: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, secondPrimeFactor: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, firstFactorCRTExponent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, secondFactorCRTExponent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, firstCRTCoefficient: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |

## Functions

| Name | Summary |
|---|---|
| [toPublicKey](to-public-key.md) | [androidJvm]<br>fun [toPublicKey](to-public-key.md)(): [JWK.RSAJWK](index.md)<br>Returns a copy of this JWK without the data related to the private key, if the JWK contains a private key. The remaining data, if present, only represents the public key. |

## Properties

| Name | Summary |
|---|---|
| [algorithm](algorithm.md) | [androidJvm]<br>open override val [algorithm](algorithm.md): [Algorithm](../../-algorithm/index.md)? = null |
| [exponent](exponent.md) | [androidJvm]<br>val [exponent](exponent.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [firstCRTCoefficient](first-c-r-t-coefficient.md) | [androidJvm]<br>val [firstCRTCoefficient](first-c-r-t-coefficient.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [firstFactorCRTExponent](first-factor-c-r-t-exponent.md) | [androidJvm]<br>val [firstFactorCRTExponent](first-factor-c-r-t-exponent.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [firstPrimeFactor](first-prime-factor.md) | [androidJvm]<br>val [firstPrimeFactor](first-prime-factor.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [keyId](key-id.md) | [androidJvm]<br>open override val [keyId](key-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [keyOperations](key-operations.md) | [androidJvm]<br>open override val [keyOperations](key-operations.md): [KeyOperations](../../-key-operations/index.md)? = null |
| [keyType](key-type.md) | [androidJvm]<br>open override val [keyType](key-type.md): [KeyType](../../-key-type/index.md) |
| [modulus](modulus.md) | [androidJvm]<br>val [modulus](modulus.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [privateExponent](private-exponent.md) | [androidJvm]<br>val [privateExponent](private-exponent.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [publicKeyUse](public-key-use.md) | [androidJvm]<br>open override val [publicKeyUse](public-key-use.md): [PublicKeyUse](../../-public-key-use/index.md)? = null |
| [secondFactorCRTExponent](second-factor-c-r-t-exponent.md) | [androidJvm]<br>val [secondFactorCRTExponent](second-factor-c-r-t-exponent.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [secondPrimeFactor](second-prime-factor.md) | [androidJvm]<br>val [secondPrimeFactor](second-prime-factor.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [x509CertificateChain](x509-certificate-chain.md) | [androidJvm]<br>open override val [x509CertificateChain](x509-certificate-chain.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;? = null |
| [x509CertificateSHA1Thumbprint](x509-certificate-s-h-a1-thumbprint.md) | [androidJvm]<br>open override val [x509CertificateSHA1Thumbprint](x509-certificate-s-h-a1-thumbprint.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [x509CertificateSHA256Thumbprint](x509-certificate-s-h-a256-thumbprint.md) | [androidJvm]<br>open override val [x509CertificateSHA256Thumbprint](x509-certificate-s-h-a256-thumbprint.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [x509Url](x509-url.md) | [androidJvm]<br>open override val [x509Url](x509-url.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
