//[core](../../index.md)/[eu.epicompany.mobile.core.domain.jose](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [Algorithm](-algorithm/index.md) | [androidJvm]<br>@Serializable<br>enum [Algorithm](-algorithm/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[Algorithm](-algorithm/index.md)&gt; <br>This enum defines a list of cryptographic algorithms as specified by [RFC 7518](https://www.rfc-editor.org/rfc/rfc7518). Currently, this list does not cover all algorithms specified by the RFC. |
| [EllipticCurve](-elliptic-curve/index.md) | [androidJvm]<br>@Serializable<br>enum [EllipticCurve](-elliptic-curve/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[EllipticCurve](-elliptic-curve/index.md)&gt; <br>This enum defines a list of elliptic curves as specified by [RFC 7518](https://www.rfc-editor.org/rfc/rfc7518). |
| [JWK](-j-w-k/index.md) | [androidJvm]<br>@Serializable<br>interface [JWK](-j-w-k/index.md)<br>This type defines a JSON Web Key (JWK) data structure according to [RFC 7517](https://www.rfc-editor.org/rfc/rfc7517). A JWK is a JSON object that represents a cryptographic key. |
| [JWKSet](-j-w-k-set/index.md) | [androidJvm]<br>@Serializable<br>data class [JWKSet](-j-w-k-set/index.md)(val keys: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[JWK](-j-w-k/index.md)&gt;)<br>This type defines a JSON Web Key Set (JWKS) data structure according to [RFC 7517](https://www.rfc-editor.org/rfc/rfc7517). A JWKS is a collection of JWKs. |
| [JWS](-j-w-s/index.md) | [androidJvm]<br>@Serializable<br>@[JvmInline](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-inline/index.html)<br>value class [JWS](-j-w-s/index.md)(val token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>This type defines a JSON Web Signature (JWS) data structure in its compact serialization format according to [RFC 7515](https://www.rfc-editor.org/rfc/rfc7515). A JWS is a JSON object that contains an arbitrary payload, a cryptographic signature over that payload, and a metadata header describing the cryptographic method used to compute and verify the signature. It has the following format: |
| [JWT](index.md#-2125418932%2FClasslikes%2F-1060529556) | [androidJvm]<br>typealias [JWT](index.md#-2125418932%2FClasslikes%2F-1060529556) = [JWS](-j-w-s/index.md)<br>This type defines a JSON Web Token (JWT) data structure in its compact serialization format according to [RFC 7519](https://www.rfc-editor.org/rfc/rfc7519). A JWT is a JWS with a specific payload and purpose. It describes claims for claim-based identity management. |
| [JWTPayload](-j-w-t-payload/index.md) | [androidJvm]<br>@Serializable<br>data class [JWTPayload](-j-w-t-payload/index.md)(val issuer: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val subject: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val audience: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;? = null, val expirationTime: [NumericDate](-numeric-date/index.md)? = null, val notBefore: [NumericDate](-numeric-date/index.md)? = null, val issuedAt: [NumericDate](-numeric-date/index.md)? = null, val jwtId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null)<br>This type defines the payload of a JSON Web Token (JWT) data structure according to [RFC 7519](https://www.rfc-editor.org/rfc/rfc7519). A JWT is a JWS with a specific payload and purpose. It describes claims for claim-based identity management. |
| [KeyOperations](-key-operations/index.md) | [androidJvm]<br>@Serializable<br>enum [KeyOperations](-key-operations/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[KeyOperations](-key-operations/index.md)&gt; <br>This type defines a list of key operations as defined by to [RFC 7517](https://www.rfc-editor.org/rfc/rfc7517). |
| [KeyType](-key-type/index.md) | [androidJvm]<br>@Serializable<br>enum [KeyType](-key-type/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[KeyType](-key-type/index.md)&gt; <br>This enum defines a list of key types as specified by [RFC 7518](https://www.rfc-editor.org/rfc/rfc7518). |
| [NumericDate](-numeric-date/index.md) | [androidJvm]<br>@Serializable<br>@[JvmInline](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-inline/index.html)<br>value class [NumericDate](-numeric-date/index.md)(val value: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>This type defines a timestamp as the number of seconds since Epoch according to [RFC 7519](https://www.rfc-editor.org/rfc/rfc7519). |
| [PublicKeyUse](-public-key-use/index.md) | [androidJvm]<br>@Serializable<br>enum [PublicKeyUse](-public-key-use/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[PublicKeyUse](-public-key-use/index.md)&gt; <br>This type defines a list of public key use cases as defined by to [RFC 7517](https://www.rfc-editor.org/rfc/rfc7517). |