//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.proxy](../index.md)/[AddProxyResource](index.md)

# AddProxyResource

[androidJvm]\
@Serializable

data class [AddProxyResource](index.md)(val type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val _links: [AddProxyResponseLinks](../-add-proxy-response-links/index.md)) : [HalResource](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [AddProxyResource](-add-proxy-resource.md) | [androidJvm]<br>constructor(type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), _links: [AddProxyResponseLinks](../-add-proxy-response-links/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [asDomainModel](../as-domain-model.md) | [androidJvm]<br>fun [AddProxyResource](index.md).[asDomainModel](../as-domain-model.md)(): [AddProxyResource](index.md) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/_embedded.md) | [androidJvm]<br>open val [_embedded](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/_embedded.md): [EmbeddedHalResources](../../eu.epicompany.mobile.core.network.hypermedia/-embedded-hal-resources/index.md)? |
| [_links](_links.md) | [androidJvm]<br>open override val [_links](_links.md): [AddProxyResponseLinks](../-add-proxy-response-links/index.md) |
| [id](id.md) | [androidJvm]<br>val [id](id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [type](type.md) | [androidJvm]<br>val [type](type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [value](value.md) | [androidJvm]<br>val [value](value.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
