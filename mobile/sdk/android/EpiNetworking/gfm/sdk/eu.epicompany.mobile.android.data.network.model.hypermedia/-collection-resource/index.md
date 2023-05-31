//[sdk](../../../index.md)/[eu.epicompany.mobile.android.data.network.model.hypermedia](../index.md)/[CollectionResource](index.md)

# CollectionResource

[androidJvm]\
@Serializable

data class [CollectionResource](index.md)&lt;[T](index.md) : [EmbeddedHalResources](../-embedded-hal-resources/index.md)&gt;(val _links: [SelfLinkOnly](../-self-link-only/index.md), val _embedded: [T](index.md)) : [HalResource](../-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [CollectionResource](-collection-resource.md) | [androidJvm]<br>constructor(_links: [SelfLinkOnly](../-self-link-only/index.md), _embedded: [T](index.md)) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](_embedded.md) | [androidJvm]<br>open override val [_embedded](_embedded.md): [T](index.md) |
| [_links](_links.md) | [androidJvm]<br>open override val [_links](_links.md): [SelfLinkOnly](../-self-link-only/index.md) |
