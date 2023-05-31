//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.model](../index.md)/[TokenResource](index.md)

# TokenResource

[androidJvm]\
@Serializable

data class [TokenResource](index.md)(val accessToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val expiresIn: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), val consumerId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val tokenType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val _links: [TokenResourceLinks](../-token-resource-links/index.md) = TokenResourceLinks()) : [HalResource](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [TokenResource](-token-resource.md) | [androidJvm]<br>constructor(accessToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), expiresIn: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), consumerId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), tokenType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), _links: [TokenResourceLinks](../-token-resource-links/index.md) = TokenResourceLinks()) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_embedded.md) | [androidJvm]<br>open val [_embedded](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_embedded.md): [EmbeddedHalResources](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-embedded-hal-resources/index.md)? |
| [_links](_links.md) | [androidJvm]<br>open override val [_links](_links.md): [TokenResourceLinks](../-token-resource-links/index.md) |
| [accessToken](access-token.md) | [androidJvm]<br>val [accessToken](access-token.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [consumerId](consumer-id.md) | [androidJvm]<br>val [consumerId](consumer-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [expiresIn](expires-in.md) | [androidJvm]<br>val [expiresIn](expires-in.md): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [tokenType](token-type.md) | [androidJvm]<br>val [tokenType](token-type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
