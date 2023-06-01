//[core](../../../index.md)/[eu.epicompany.mobile.core.domain.jose](../index.md)/[JWTPayload](index.md)

# JWTPayload

[androidJvm]\
@Serializable

data class [JWTPayload](index.md)(val issuer: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val subject: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val audience: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;? = null, val expirationTime: [NumericDate](../-numeric-date/index.md)? = null, val notBefore: [NumericDate](../-numeric-date/index.md)? = null, val issuedAt: [NumericDate](../-numeric-date/index.md)? = null, val jwtId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null)

This type defines the payload of a JSON Web Token (JWT) data structure according to [RFC 7519](https://www.rfc-editor.org/rfc/rfc7519). A JWT is a JWS with a specific payload and purpose. It describes claims for claim-based identity management.

## Constructors

| | |
|---|---|
| [JWTPayload](-j-w-t-payload.md) | [androidJvm]<br>constructor(issuer: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, subject: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, audience: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;? = null, expirationTime: [NumericDate](../-numeric-date/index.md)? = null, notBefore: [NumericDate](../-numeric-date/index.md)? = null, issuedAt: [NumericDate](../-numeric-date/index.md)? = null, jwtId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |

## Properties

| Name | Summary |
|---|---|
| [audience](audience.md) | [androidJvm]<br>val [audience](audience.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;? = null |
| [expirationTime](expiration-time.md) | [androidJvm]<br>val [expirationTime](expiration-time.md): [NumericDate](../-numeric-date/index.md)? = null |
| [issuedAt](issued-at.md) | [androidJvm]<br>val [issuedAt](issued-at.md): [NumericDate](../-numeric-date/index.md)? = null |
| [issuer](issuer.md) | [androidJvm]<br>val [issuer](issuer.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [jwtId](jwt-id.md) | [androidJvm]<br>val [jwtId](jwt-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [notBefore](not-before.md) | [androidJvm]<br>val [notBefore](not-before.md): [NumericDate](../-numeric-date/index.md)? = null |
| [subject](subject.md) | [androidJvm]<br>val [subject](subject.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
