//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.model.proxy](../index.md)/[EditPaymentSourceResource](index.md)

# EditPaymentSourceResource

[androidJvm]\
@Serializable

data class [EditPaymentSourceResource](index.md)(val paymentSourceID: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val displayName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val _links: [EditPaymentSourceResponseLinks](../-edit-payment-source-response-links/index.md)) : [HalResource](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [EditPaymentSourceResource](-edit-payment-source-resource.md) | [androidJvm]<br>constructor(paymentSourceID: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), displayName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), _links: [EditPaymentSourceResponseLinks](../-edit-payment-source-response-links/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_embedded.md) | [androidJvm]<br>open val [_embedded](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_embedded.md): [EmbeddedHalResources](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-embedded-hal-resources/index.md)? |
| [_links](_links.md) | [androidJvm]<br>open override val [_links](_links.md): [EditPaymentSourceResponseLinks](../-edit-payment-source-response-links/index.md) |
| [displayName](display-name.md) | [androidJvm]<br>val [displayName](display-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [paymentSourceID](payment-source-i-d.md) | [androidJvm]<br>val [paymentSourceID](payment-source-i-d.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
