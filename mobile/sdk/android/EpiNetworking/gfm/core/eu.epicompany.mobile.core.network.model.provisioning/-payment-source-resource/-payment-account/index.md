//[core](../../../../index.md)/[eu.epicompany.mobile.core.network.model.provisioning](../../index.md)/[PaymentSourceResource](../index.md)/[PaymentAccount](index.md)

# PaymentAccount

[androidJvm]\
@Serializable

data class [PaymentAccount](index.md)(val id: [UUID4](../../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val consumerPspId: [UUID4](../../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val externalId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val currency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val iban: [IBAN](../../../eu.epicompany.mobile.core.datatypes/-i-b-a-n/index.md), val accountHolder: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [PaymentSourceResource](../index.md)

## Constructors

| | |
|---|---|
| [PaymentAccount](-payment-account.md) | [androidJvm]<br>constructor(id: [UUID4](../../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), consumerPspId: [UUID4](../../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), externalId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), currency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), iban: [IBAN](../../../eu.epicompany.mobile.core.datatypes/-i-b-a-n/index.md), accountHolder: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](../../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/_embedded.md) | [androidJvm]<br>open val [_embedded](../../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/_embedded.md): [EmbeddedHalResources](../../../eu.epicompany.mobile.core.network.hypermedia/-embedded-hal-resources/index.md)? |
| [_links](../../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/_links.md) | [androidJvm]<br>open val [_links](../../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/_links.md): [HalLinks](../../../eu.epicompany.mobile.core.network.hypermedia/-hal-links/index.md)? |
| [accountHolder](account-holder.md) | [androidJvm]<br>val [accountHolder](account-holder.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [consumerPspId](consumer-psp-id.md) | [androidJvm]<br>open override val [consumerPspId](consumer-psp-id.md): [UUID4](../../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556) |
| [currency](currency.md) | [androidJvm]<br>open override val [currency](currency.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [externalId](external-id.md) | [androidJvm]<br>open override val [externalId](external-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [iban](iban.md) | [androidJvm]<br>val [iban](iban.md): [IBAN](../../../eu.epicompany.mobile.core.datatypes/-i-b-a-n/index.md) |
| [id](id.md) | [androidJvm]<br>open override val [id](id.md): [UUID4](../../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556) |
