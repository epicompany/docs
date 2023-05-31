//[sdk](../../../../index.md)/[eu.epicompany.mobile.sdk.network.model.provisioning](../../index.md)/[PaymentSourceResource](../index.md)/[PaymentAccount](index.md)

# PaymentAccount

[androidJvm]\
@Serializable

data class [PaymentAccount](index.md)(val id: [UUID4](../../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), val consumerPspId: [UUID4](../../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), val externalId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val currency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val iban: [IBAN](../../../eu.epicompany.mobile.android.datatypes/-i-b-a-n/index.md), val accountHolder: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [PaymentSourceResource](../index.md)

## Constructors

| | |
|---|---|
| [PaymentAccount](-payment-account.md) | [androidJvm]<br>constructor(id: [UUID4](../../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), consumerPspId: [UUID4](../../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), externalId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), currency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), iban: [IBAN](../../../eu.epicompany.mobile.android.datatypes/-i-b-a-n/index.md), accountHolder: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](../../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_embedded.md) | [androidJvm]<br>open val [_embedded](../../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_embedded.md): [EmbeddedHalResources](../../../eu.epicompany.mobile.android.data.network.model.hypermedia/-embedded-hal-resources/index.md)? |
| [_links](../../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_links.md) | [androidJvm]<br>open val [_links](../../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_links.md): [HalLinks](../../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-links/index.md)? |
| [accountHolder](account-holder.md) | [androidJvm]<br>val [accountHolder](account-holder.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [consumerPspId](consumer-psp-id.md) | [androidJvm]<br>open override val [consumerPspId](consumer-psp-id.md): [UUID4](../../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411) |
| [currency](currency.md) | [androidJvm]<br>open override val [currency](currency.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [externalId](external-id.md) | [androidJvm]<br>open override val [externalId](external-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [iban](iban.md) | [androidJvm]<br>val [iban](iban.md): [IBAN](../../../eu.epicompany.mobile.android.datatypes/-i-b-a-n/index.md) |
| [id](id.md) | [androidJvm]<br>open override val [id](id.md): [UUID4](../../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411) |
