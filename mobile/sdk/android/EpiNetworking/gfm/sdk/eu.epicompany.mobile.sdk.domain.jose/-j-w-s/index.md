//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.domain.jose](../index.md)/[JWS](index.md)

# JWS

[androidJvm]\
@Serializable

@[JvmInline](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-inline/index.html)

value class [JWS](index.md)(val token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

This type defines a JSON Web Signature (JWS) data structure in its compact serialization format according to [RFC 7515](https://www.rfc-editor.org/rfc/rfc7515). A JWS is a JSON object that contains an arbitrary payload, a cryptographic signature over that payload, and a metadata header describing the cryptographic method used to compute and verify the signature. It has the following format:

```kotlin
BASE64URL || '.' || BASE64URL || '.' || BASE64URL
```

## Constructors

| | |
|---|---|
| [JWS](-j-w-s.md) | [androidJvm]<br>constructor(token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Properties

| Name | Summary |
|---|---|
| [token](token.md) | [androidJvm]<br>val [token](token.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
