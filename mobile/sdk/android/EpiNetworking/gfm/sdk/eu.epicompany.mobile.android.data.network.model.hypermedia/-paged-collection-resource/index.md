//[sdk](../../../index.md)/[eu.epicompany.mobile.android.data.network.model.hypermedia](../index.md)/[PagedCollectionResource](index.md)

# PagedCollectionResource

[androidJvm]\
@Serializable

data class [PagedCollectionResource](index.md)&lt;[T](index.md) : [EmbeddedHalResources](../-embedded-hal-resources/index.md)&gt;(val _links: [PagedCollectionResourceLinks](../-paged-collection-resource-links/index.md), val _embedded: [T](index.md), val page: [Page](../-page/index.md)) : [HalResource](../-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [PagedCollectionResource](-paged-collection-resource.md) | [androidJvm]<br>constructor(_links: [PagedCollectionResourceLinks](../-paged-collection-resource-links/index.md), _embedded: [T](index.md), page: [Page](../-page/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](_embedded.md) | [androidJvm]<br>open override val [_embedded](_embedded.md): [T](index.md) |
| [_links](_links.md) | [androidJvm]<br>open override val [_links](_links.md): [PagedCollectionResourceLinks](../-paged-collection-resource-links/index.md) |
| [page](page.md) | [androidJvm]<br>val [page](page.md): [Page](../-page/index.md) |
