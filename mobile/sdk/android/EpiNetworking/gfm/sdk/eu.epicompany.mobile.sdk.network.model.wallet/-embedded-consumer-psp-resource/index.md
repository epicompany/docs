//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.model.wallet](../index.md)/[EmbeddedConsumerPspResource](index.md)

# EmbeddedConsumerPspResource

[androidJvm]\
@Serializable

data class [EmbeddedConsumerPspResource](index.md)(val id: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), val name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val countryCodeList: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, val _links: [SelfLinkOnly](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-self-link-only/index.md)? = null, val _embedded: [EmbeddedConsumerPspResourceEmbeds](../-embedded-consumer-psp-resource-embeds/index.md) = EmbeddedConsumerPspResourceEmbeds()) : [HalResource](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [EmbeddedConsumerPspResource](-embedded-consumer-psp-resource.md) | [androidJvm]<br>constructor(id: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), countryCodeList: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, _links: [SelfLinkOnly](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-self-link-only/index.md)? = null, _embedded: [EmbeddedConsumerPspResourceEmbeds](../-embedded-consumer-psp-resource-embeds/index.md) = EmbeddedConsumerPspResourceEmbeds()) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](_embedded.md) | [androidJvm]<br>open override val [_embedded](_embedded.md): [EmbeddedConsumerPspResourceEmbeds](../-embedded-consumer-psp-resource-embeds/index.md) |
| [_links](_links.md) | [androidJvm]<br>open override val [_links](_links.md): [SelfLinkOnly](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-self-link-only/index.md)? = null |
| [countryCodeList](country-code-list.md) | [androidJvm]<br>val [countryCodeList](country-code-list.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [id](id.md) | [androidJvm]<br>val [id](id.md): [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411) |
| [name](name.md) | [androidJvm]<br>val [name](name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
