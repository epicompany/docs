//[core](../../../index.md)/[eu.epicompany.mobile.core.domain.jose](../index.md)/[EllipticCurve](index.md)

# EllipticCurve

[androidJvm]\
@Serializable

enum [EllipticCurve](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[EllipticCurve](index.md)&gt; 

This enum defines a list of elliptic curves as specified by [RFC 7518](https://www.rfc-editor.org/rfc/rfc7518).

## Entries

| | |
|---|---|
| [P256](-p256/index.md) | [androidJvm]<br>[P256](-p256/index.md)<br>This curve has different names in standards. `P-256` is the name defined by NIST. `secp256r1` is the name defined by SECG. `prime256v1` is the name defined by ANSI X9.62. All these names refer to the same curve. See [RFC 4492](https://www.rfc-editor.org/rfc/rfc4492). |
| [P384](-p384/index.md) | [androidJvm]<br>[P384](-p384/index.md) |
| [P521](-p521/index.md) | [androidJvm]<br>[P521](-p521/index.md) |

## Functions

| Name | Summary |
|---|---|
| [valueOf](value-of.md) | [androidJvm]<br>fun [valueOf](value-of.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [EllipticCurve](index.md)<br>Returns the enum constant of this type with the specified name. The string must match exactly an identifier used to declare an enum constant in this type. (Extraneous whitespace characters are not permitted.) |
| [values](values.md) | [androidJvm]<br>fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[EllipticCurve](index.md)&gt;<br>Returns an array containing the constants of this enum type, in the order they're declared. |

## Properties

| Name | Summary |
|---|---|
| [name](../../eu.epicompany.mobile.core.network.model.wallet/-payment-means-type-resource/-account/index.md#-372974862%2FProperties%2F-1060529556) | [androidJvm]<br>val [name](../../eu.epicompany.mobile.core.network.model.wallet/-payment-means-type-resource/-account/index.md#-372974862%2FProperties%2F-1060529556): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ordinal](../../eu.epicompany.mobile.core.network.model.wallet/-payment-means-type-resource/-account/index.md#-739389684%2FProperties%2F-1060529556) | [androidJvm]<br>val [ordinal](../../eu.epicompany.mobile.core.network.model.wallet/-payment-means-type-resource/-account/index.md#-739389684%2FProperties%2F-1060529556): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [value](value.md) | [androidJvm]<br>val [value](value.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
