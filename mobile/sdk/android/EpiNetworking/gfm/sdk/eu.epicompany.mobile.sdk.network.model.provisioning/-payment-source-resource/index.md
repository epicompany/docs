//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.model.provisioning](../index.md)/[PaymentSourceResource](index.md)

# PaymentSourceResource

@Serializable

sealed class [PaymentSourceResource](index.md) : [HalResource](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/index.md)

#### Inheritors

| |
|---|
| [PaymentAccount](-payment-account/index.md) |

## Types

| Name | Summary |
|---|---|
| [PaymentAccount](-payment-account/index.md) | [androidJvm]<br>@Serializable<br>data class [PaymentAccount](-payment-account/index.md)(val id: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), val consumerPspId: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), val externalId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val currency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val iban: [IBAN](../../eu.epicompany.mobile.android.datatypes/-i-b-a-n/index.md), val accountHolder: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [PaymentSourceResource](index.md) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_embedded.md) | [androidJvm]<br>open val [_embedded](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_embedded.md): [EmbeddedHalResources](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-embedded-hal-resources/index.md)? |
| [_links](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_links.md) | [androidJvm]<br>open val [_links](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_links.md): [HalLinks](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-links/index.md)? |
| [consumerPspId](consumer-psp-id.md) | [androidJvm]<br>abstract val [consumerPspId](consumer-psp-id.md): [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411) |
| [currency](currency.md) | [androidJvm]<br>abstract val [currency](currency.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [externalId](external-id.md) | [androidJvm]<br>abstract val [externalId](external-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [id](id.md) | [androidJvm]<br>abstract val [id](id.md): [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411) |
