//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.domain.model.authentication](../index.md)/[JWK](index.md)

# JWK

[androidJvm]\
@Serializable

data class [JWK](index.md)(val keyId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val keyType: [KeyType](../../eu.epicompany.mobile.sdk.domain.jose/-key-type/index.md), val publicKeyUse: [PublicKeyUse](../../eu.epicompany.mobile.sdk.domain.jose/-public-key-use/index.md) = Signature, val algorithm: [Algorithm](../../eu.epicompany.mobile.sdk.domain.jose/-algorithm/index.md), val modulus: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val exponent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val xCoordinate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val yCoordinate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val curve: [EllipticCurve](../../eu.epicompany.mobile.sdk.domain.jose/-elliptic-curve/index.md)? = null)

## Constructors

| | |
|---|---|
| [JWK](-j-w-k.md) | [androidJvm]<br>constructor(keyId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), keyType: [KeyType](../../eu.epicompany.mobile.sdk.domain.jose/-key-type/index.md), publicKeyUse: [PublicKeyUse](../../eu.epicompany.mobile.sdk.domain.jose/-public-key-use/index.md) = Signature, algorithm: [Algorithm](../../eu.epicompany.mobile.sdk.domain.jose/-algorithm/index.md), modulus: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, exponent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, xCoordinate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, yCoordinate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, curve: [EllipticCurve](../../eu.epicompany.mobile.sdk.domain.jose/-elliptic-curve/index.md)? = null) |

## Properties

| Name | Summary |
|---|---|
| [algorithm](algorithm.md) | [androidJvm]<br>val [algorithm](algorithm.md): [Algorithm](../../eu.epicompany.mobile.sdk.domain.jose/-algorithm/index.md) |
| [curve](curve.md) | [androidJvm]<br>val [curve](curve.md): [EllipticCurve](../../eu.epicompany.mobile.sdk.domain.jose/-elliptic-curve/index.md)? = null |
| [exponent](exponent.md) | [androidJvm]<br>val [exponent](exponent.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [keyId](key-id.md) | [androidJvm]<br>val [keyId](key-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [keyType](key-type.md) | [androidJvm]<br>val [keyType](key-type.md): [KeyType](../../eu.epicompany.mobile.sdk.domain.jose/-key-type/index.md) |
| [modulus](modulus.md) | [androidJvm]<br>val [modulus](modulus.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [publicKeyUse](public-key-use.md) | [androidJvm]<br>val [publicKeyUse](public-key-use.md): [PublicKeyUse](../../eu.epicompany.mobile.sdk.domain.jose/-public-key-use/index.md) |
| [xCoordinate](x-coordinate.md) | [androidJvm]<br>val [xCoordinate](x-coordinate.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [yCoordinate](y-coordinate.md) | [androidJvm]<br>val [yCoordinate](y-coordinate.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
