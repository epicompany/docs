//[core](../../index.md)/[eu.epicompany.mobile.core.network.model.provisioning](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [PaymentSourceResource](-payment-source-resource/index.md) | [androidJvm]<br>@Serializable<br>sealed class [PaymentSourceResource](-payment-source-resource/index.md) : [HalResource](../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/index.md) |
| [ProvisioningCollectionResourceEmbed](-provisioning-collection-resource-embed/index.md) | [androidJvm]<br>@Serializable<br>data class [ProvisioningCollectionResourceEmbed](-provisioning-collection-resource-embed/index.md)(val provisionings: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[ProvisioningResource](-provisioning-resource/index.md)&gt;) : [EmbeddedHalResources](../eu.epicompany.mobile.core.network.hypermedia/-embedded-hal-resources/index.md) |
| [ProvisioningResource](-provisioning-resource/index.md) | [androidJvm]<br>@Serializable<br>data class [ProvisioningResource](-provisioning-resource/index.md)(val id: [UUID4](../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val consumerPspId: [UUID4](../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val paymentSources: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[PaymentSourceResource](-payment-source-resource/index.md)&gt;, val _embedded: [ProvisioningResource.Embeds](-provisioning-resource/-embeds/index.md) = Embeds(), val _links: [ProvisioningResource.Links](-provisioning-resource/-links/index.md) = Links()) : [HalResource](../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/index.md) |
