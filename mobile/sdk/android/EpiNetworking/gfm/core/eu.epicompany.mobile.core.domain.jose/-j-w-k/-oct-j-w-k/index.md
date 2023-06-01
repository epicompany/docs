//[core](../../../../index.md)/[eu.epicompany.mobile.core.domain.jose](../../index.md)/[JWK](../index.md)/[OctJWK](index.md)

# OctJWK

[androidJvm]\
@Serializable

data class [OctJWK](index.md)(val publicKeyUse: [PublicKeyUse](../../-public-key-use/index.md)? = null, val keyOperations: [KeyOperations](../../-key-operations/index.md)? = null, val algorithm: [Algorithm](../../-algorithm/index.md)? = null, val keyId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val x509Url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val x509CertificateChain: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;? = null, val x509CertificateSHA1Thumbprint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val x509CertificateSHA256Thumbprint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val symmetricKey: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [JWK](../index.md)

## Constructors

| | |
|---|---|
| [OctJWK](-oct-j-w-k.md) | [androidJvm]<br>constructor(publicKeyUse: [PublicKeyUse](../../-public-key-use/index.md)? = null, keyOperations: [KeyOperations](../../-key-operations/index.md)? = null, algorithm: [Algorithm](../../-algorithm/index.md)? = null, keyId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, x509Url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, x509CertificateChain: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;? = null, x509CertificateSHA1Thumbprint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, x509CertificateSHA256Thumbprint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, symmetricKey: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [algorithm](algorithm.md) | [androidJvm]<br>open override val [algorithm](algorithm.md): [Algorithm](../../-algorithm/index.md)? = null |
| [keyId](key-id.md) | [androidJvm]<br>open override val [keyId](key-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [keyOperations](key-operations.md) | [androidJvm]<br>open override val [keyOperations](key-operations.md): [KeyOperations](../../-key-operations/index.md)? = null |
| [keyType](key-type.md) | [androidJvm]<br>open override val [keyType](key-type.md): [KeyType](../../-key-type/index.md) |
| [publicKeyUse](public-key-use.md) | [androidJvm]<br>open override val [publicKeyUse](public-key-use.md): [PublicKeyUse](../../-public-key-use/index.md)? = null |
| [symmetricKey](symmetric-key.md) | [androidJvm]<br>val [symmetricKey](symmetric-key.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [x509CertificateChain](x509-certificate-chain.md) | [androidJvm]<br>open override val [x509CertificateChain](x509-certificate-chain.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;? = null |
| [x509CertificateSHA1Thumbprint](x509-certificate-s-h-a1-thumbprint.md) | [androidJvm]<br>open override val [x509CertificateSHA1Thumbprint](x509-certificate-s-h-a1-thumbprint.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [x509CertificateSHA256Thumbprint](x509-certificate-s-h-a256-thumbprint.md) | [androidJvm]<br>open override val [x509CertificateSHA256Thumbprint](x509-certificate-s-h-a256-thumbprint.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [x509Url](x509-url.md) | [androidJvm]<br>open override val [x509Url](x509-url.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
