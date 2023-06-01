//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.proxy](../index.md)/[PaymentSourceUpdateResource](index.md)

# PaymentSourceUpdateResource

[androidJvm]\
@Serializable

data class [PaymentSourceUpdateResource](index.md)(val paymentSourceId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val displayName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val _links: [PaymentSourceUpdateLinks](../-payment-source-update-links/index.md)) : [HalResource](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [PaymentSourceUpdateResource](-payment-source-update-resource.md) | [androidJvm]<br>constructor(paymentSourceId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), displayName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), _links: [PaymentSourceUpdateLinks](../-payment-source-update-links/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/_embedded.md) | [androidJvm]<br>open val [_embedded](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/_embedded.md): [EmbeddedHalResources](../../eu.epicompany.mobile.core.network.hypermedia/-embedded-hal-resources/index.md)? |
| [_links](_links.md) | [androidJvm]<br>open override val [_links](_links.md): [PaymentSourceUpdateLinks](../-payment-source-update-links/index.md) |
| [displayName](display-name.md) | [androidJvm]<br>val [displayName](display-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [paymentSourceId](payment-source-id.md) | [androidJvm]<br>val [paymentSourceId](payment-source-id.md): [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556) |
