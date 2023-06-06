//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.proxy](../index.md)/[PaymentSourceProfileResource](index.md)

# PaymentSourceProfileResource

[androidJvm]\
@Serializable

data class [PaymentSourceProfileResource](index.md)(val paymentSourceId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val displayName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val _links: [PaymentSourceProfileResponseLinks](../-payment-source-profile-response-links/index.md), val _embedded: [PaymentSourceProfileEmbeds](../-payment-source-profile-embeds/index.md)) : [HalResource](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [PaymentSourceProfileResource](-payment-source-profile-resource.md) | [androidJvm]<br>constructor(paymentSourceId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), displayName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), _links: [PaymentSourceProfileResponseLinks](../-payment-source-profile-response-links/index.md), _embedded: [PaymentSourceProfileEmbeds](../-payment-source-profile-embeds/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](_embedded.md) | [androidJvm]<br>open override val [_embedded](_embedded.md): [PaymentSourceProfileEmbeds](../-payment-source-profile-embeds/index.md) |
| [_links](_links.md) | [androidJvm]<br>open override val [_links](_links.md): [PaymentSourceProfileResponseLinks](../-payment-source-profile-response-links/index.md) |
| [displayName](display-name.md) | [androidJvm]<br>val [displayName](display-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [paymentSourceId](payment-source-id.md) | [androidJvm]<br>val [paymentSourceId](payment-source-id.md): [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556) |
