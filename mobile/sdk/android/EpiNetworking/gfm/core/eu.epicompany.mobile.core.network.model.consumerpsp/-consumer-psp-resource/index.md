//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.consumerpsp](../index.md)/[ConsumerPspResource](index.md)

# ConsumerPspResource

[androidJvm]\
@Serializable

data class [ConsumerPspResource](index.md)(val id: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val countryCodeList: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, val redirectTemplate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, val _embedded: [ConsumerPspResourceEmbeds](../-consumer-psp-resource-embeds/index.md)? = ConsumerPspResourceEmbeds()) : [HalResource](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [ConsumerPspResource](-consumer-psp-resource.md) | [androidJvm]<br>constructor(id: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), countryCodeList: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, redirectTemplate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, _embedded: [ConsumerPspResourceEmbeds](../-consumer-psp-resource-embeds/index.md)? = ConsumerPspResourceEmbeds()) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](_embedded.md) | [androidJvm]<br>open override val [_embedded](_embedded.md): [ConsumerPspResourceEmbeds](../-consumer-psp-resource-embeds/index.md)? |
| [_links](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/_links.md) | [androidJvm]<br>open val [_links](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/_links.md): [HalLinks](../../eu.epicompany.mobile.core.network.hypermedia/-hal-links/index.md)? |
| [countryCodeList](country-code-list.md) | [androidJvm]<br>val [countryCodeList](country-code-list.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [id](id.md) | [androidJvm]<br>val [id](id.md): [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556) |
| [name](name.md) | [androidJvm]<br>val [name](name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [redirectTemplate](redirect-template.md) | [androidJvm]<br>val [redirectTemplate](redirect-template.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [standaloneProvisionable](standalone-provisionable.md) | [androidJvm]<br>val [standaloneProvisionable](standalone-provisionable.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates whether this consumer psp allows the provisioning of payment sources through the standalone app. |
