//[core](../../../index.md)/[eu.epicompany.mobile.core.domain.jose](../index.md)/[JWKSet](index.md)

# JWKSet

[androidJvm]\
@Serializable

data class [JWKSet](index.md)(val keys: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[JWK](../-j-w-k/index.md)&gt;)

This type defines a JSON Web Key Set (JWKS) data structure according to [RFC 7517](https://www.rfc-editor.org/rfc/rfc7517). A JWKS is a collection of JWKs.

## Constructors

| | |
|---|---|
| [JWKSet](-j-w-k-set.md) | [androidJvm]<br>constructor(keys: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[JWK](../-j-w-k/index.md)&gt;) |

## Properties

| Name | Summary |
|---|---|
| [keys](keys.md) | [androidJvm]<br>val [keys](keys.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[JWK](../-j-w-k/index.md)&gt; |
