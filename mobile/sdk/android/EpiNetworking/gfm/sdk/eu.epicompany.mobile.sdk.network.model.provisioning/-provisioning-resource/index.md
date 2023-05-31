//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.model.provisioning](../index.md)/[ProvisioningResource](index.md)

# ProvisioningResource

[androidJvm]\
@Serializable

data class [ProvisioningResource](index.md)(val id: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), val consumerPspId: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), val paymentSources: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[PaymentSourceResource](../-payment-source-resource/index.md)&gt;, val _embedded: [ProvisioningResource.Embeds](-embeds/index.md) = Embeds(), val _links: [ProvisioningResource.Links](-links/index.md) = Links()) : [HalResource](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [ProvisioningResource](-provisioning-resource.md) | [androidJvm]<br>constructor(id: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), consumerPspId: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), paymentSources: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[PaymentSourceResource](../-payment-source-resource/index.md)&gt;, _embedded: [ProvisioningResource.Embeds](-embeds/index.md) = Embeds(), _links: [ProvisioningResource.Links](-links/index.md) = Links()) |

## Types

| Name | Summary |
|---|---|
| [Embeds](-embeds/index.md) | [androidJvm]<br>@Serializable<br>data class [Embeds](-embeds/index.md)(val consumerPsp: [EmbeddedConsumerPspResource](../../eu.epicompany.mobile.sdk.network.model.wallet/-embedded-consumer-psp-resource/index.md)? = null) : [EmbeddedHalResources](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-embedded-hal-resources/index.md) |
| [Links](-links/index.md) | [androidJvm]<br>@Serializable<br>data class [Links](-links/index.md)(val self: [LinkDataModel](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-link-data-model/index.md)? = null, val redirect: [LinkDataModel](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-link-data-model/index.md)? = null, val provisionPaymentSources: [LinkDataModel](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-link-data-model/index.md)? = null, val paymentMeans: [LinkDataModel](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-link-data-model/index.md)? = null) : [HalLinks](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-links/index.md) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](_embedded.md) | [androidJvm]<br>open override val [_embedded](_embedded.md): [ProvisioningResource.Embeds](-embeds/index.md) |
| [_links](_links.md) | [androidJvm]<br>open override val [_links](_links.md): [ProvisioningResource.Links](-links/index.md) |
| [consumerPspId](consumer-psp-id.md) | [androidJvm]<br>val [consumerPspId](consumer-psp-id.md): [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411) |
| [id](id.md) | [androidJvm]<br>val [id](id.md): [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411) |
| [paymentSources](payment-sources.md) | [androidJvm]<br>val [paymentSources](payment-sources.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[PaymentSourceResource](../-payment-source-resource/index.md)&gt; |
