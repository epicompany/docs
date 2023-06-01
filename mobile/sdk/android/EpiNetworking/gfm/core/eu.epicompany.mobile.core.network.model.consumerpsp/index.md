//[core](../../index.md)/[eu.epicompany.mobile.core.network.model.consumerpsp](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [ConsumerPspCollectionResourceEmbed](-consumer-psp-collection-resource-embed/index.md) | [androidJvm]<br>@Serializable<br>data class [ConsumerPspCollectionResourceEmbed](-consumer-psp-collection-resource-embed/index.md)(val consumerPsps: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[ConsumerPspResource](-consumer-psp-resource/index.md)&gt;) : [EmbeddedHalResources](../eu.epicompany.mobile.core.network.hypermedia/-embedded-hal-resources/index.md) |
| [ConsumerPspResource](-consumer-psp-resource/index.md) | [androidJvm]<br>@Serializable<br>data class [ConsumerPspResource](-consumer-psp-resource/index.md)(val id: [UUID4](../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val countryCodeList: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, val redirectTemplate: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, val _embedded: [ConsumerPspResourceEmbeds](-consumer-psp-resource-embeds/index.md)? = ConsumerPspResourceEmbeds()) : [HalResource](../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/index.md) |
| [ConsumerPspResourceEmbeds](-consumer-psp-resource-embeds/index.md) | [androidJvm]<br>@Serializable<br>data class [ConsumerPspResourceEmbeds](-consumer-psp-resource-embeds/index.md)(val meta: [ConsumerPspResourceEmbeds.MetaData](-consumer-psp-resource-embeds/-meta-data/index.md)? = null) : [EmbeddedHalResources](../eu.epicompany.mobile.core.network.hypermedia/-embedded-hal-resources/index.md) |
| [ImageData](-image-data/index.md) | [androidJvm]<br>@Serializable<br>data class [ImageData](-image-data/index.md)(val contentBase64: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
