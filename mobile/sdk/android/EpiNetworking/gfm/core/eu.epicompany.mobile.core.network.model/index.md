//[core](../../index.md)/[eu.epicompany.mobile.core.network.model](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [ImageType](-image-type/index.md) | [androidJvm]<br>@Serializable<br>enum [ImageType](-image-type/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[ImageType](-image-type/index.md)&gt; |
| [ProfileImageResource](-profile-image-resource/index.md) | [androidJvm]<br>@Serializable<br>data class [ProfileImageResource](-profile-image-resource/index.md)(val contentBase64: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val type: [ImageType](-image-type/index.md)) |
| [TokenResource](-token-resource/index.md) | [androidJvm]<br>@Serializable<br>data class [TokenResource](-token-resource/index.md)(val accessToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val expiresIn: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), val consumerId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val tokenType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val _links: [TokenResourceLinks](-token-resource-links/index.md) = TokenResourceLinks()) : [HalResource](../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/index.md) |
| [TokenResourceLinks](-token-resource-links/index.md) | [androidJvm]<br>@Serializable<br>data class [TokenResourceLinks](-token-resource-links/index.md)(val refresh: [LinkDataModel](../eu.epicompany.mobile.core.network.hypermedia/-link-data-model/index.md)? = null) : [HalLinks](../eu.epicompany.mobile.core.network.hypermedia/-hal-links/index.md) |
