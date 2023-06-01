//[core](../../index.md)/[eu.epicompany.mobile.core.network.hypermedia](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [CollectionResource](-collection-resource/index.md) | [androidJvm]<br>@Serializable<br>data class [CollectionResource](-collection-resource/index.md)&lt;[T](-collection-resource/index.md) : [EmbeddedHalResources](-embedded-hal-resources/index.md)&gt;(val _links: [SelfLinkOnly](-self-link-only/index.md), val _embedded: [T](-collection-resource/index.md)) : [HalResource](-hal-resource/index.md) |
| [EmbeddedHalResources](-embedded-hal-resources/index.md) | [androidJvm]<br>interface [EmbeddedHalResources](-embedded-hal-resources/index.md) |
| [HalLinks](-hal-links/index.md) | [androidJvm]<br>interface [HalLinks](-hal-links/index.md) |
| [HalResource](-hal-resource/index.md) | [androidJvm]<br>interface [HalResource](-hal-resource/index.md) |
| [LinkDataModel](-link-data-model/index.md) | [androidJvm]<br>@Serializable<br>data class [LinkDataModel](-link-data-model/index.md)(val href: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val templated: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, val name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |
| [Page](-page/index.md) | [androidJvm]<br>@Serializable<br>data class [Page](-page/index.md)(val size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val totalElements: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val totalPages: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val number: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val requestedPageSize: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [PagedCollectionResource](-paged-collection-resource/index.md) | [androidJvm]<br>@Serializable<br>data class [PagedCollectionResource](-paged-collection-resource/index.md)&lt;[T](-paged-collection-resource/index.md) : [EmbeddedHalResources](-embedded-hal-resources/index.md)&gt;(val _links: [PagedCollectionResourceLinks](-paged-collection-resource-links/index.md), val _embedded: [T](-paged-collection-resource/index.md), val page: [Page](-page/index.md)) : [HalResource](-hal-resource/index.md) |
| [PagedCollectionResourceLinks](-paged-collection-resource-links/index.md) | [androidJvm]<br>@Serializable<br>data class [PagedCollectionResourceLinks](-paged-collection-resource-links/index.md)(val self: [LinkDataModel](-link-data-model/index.md), val next: [LinkDataModel](-link-data-model/index.md)? = null, val prev: [LinkDataModel](-link-data-model/index.md)? = null, val first: [LinkDataModel](-link-data-model/index.md), val last: [LinkDataModel](-link-data-model/index.md)) : [HalLinks](-hal-links/index.md) |
| [SelfLinkOnly](-self-link-only/index.md) | [androidJvm]<br>@Serializable<br>data class [SelfLinkOnly](-self-link-only/index.md)(val self: [LinkDataModel](-link-data-model/index.md)) : [HalLinks](-hal-links/index.md) |
