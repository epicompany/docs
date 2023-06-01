//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.wallet](../index.md)/[PaymentMeansResource](index.md)

# PaymentMeansResource

[androidJvm]\
@Serializable

data class [PaymentMeansResource](index.md)(val id: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val paymentSourceId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val externalId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val consumerPspId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val publicKey: [JWK](../../eu.epicompany.mobile.core.domain.model.authentication/-j-w-k/index.md), val paymentSourceType: [PaymentMeansTypeResource](../-payment-means-type-resource/index.md), val paymentSourceDisplayName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val paymentSourceDisplayDigits: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val _embedded: [PaymentMeansResourceEmbeds](../-payment-means-resource-embeds/index.md) = PaymentMeansResourceEmbeds(), val _links: [PaymentMeansResourceLinks](../-payment-means-resource-links/index.md) = PaymentMeansResourceLinks()) : [HalResource](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [PaymentMeansResource](-payment-means-resource.md) | [androidJvm]<br>constructor(id: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), paymentSourceId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), externalId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), consumerPspId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), publicKey: [JWK](../../eu.epicompany.mobile.core.domain.model.authentication/-j-w-k/index.md), paymentSourceType: [PaymentMeansTypeResource](../-payment-means-type-resource/index.md), paymentSourceDisplayName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), paymentSourceDisplayDigits: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), _embedded: [PaymentMeansResourceEmbeds](../-payment-means-resource-embeds/index.md) = PaymentMeansResourceEmbeds(), _links: [PaymentMeansResourceLinks](../-payment-means-resource-links/index.md) = PaymentMeansResourceLinks()) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](_embedded.md) | [androidJvm]<br>open override val [_embedded](_embedded.md): [PaymentMeansResourceEmbeds](../-payment-means-resource-embeds/index.md) |
| [_links](_links.md) | [androidJvm]<br>open override val [_links](_links.md): [PaymentMeansResourceLinks](../-payment-means-resource-links/index.md) |
| [consumerPspId](consumer-psp-id.md) | [androidJvm]<br>val [consumerPspId](consumer-psp-id.md): [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556) |
| [externalId](external-id.md) | [androidJvm]<br>val [externalId](external-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [id](id.md) | [androidJvm]<br>val [id](id.md): [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556) |
| [paymentSourceDisplayDigits](payment-source-display-digits.md) | [androidJvm]<br>val [paymentSourceDisplayDigits](payment-source-display-digits.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [paymentSourceDisplayName](payment-source-display-name.md) | [androidJvm]<br>val [paymentSourceDisplayName](payment-source-display-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [paymentSourceId](payment-source-id.md) | [androidJvm]<br>val [paymentSourceId](payment-source-id.md): [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556) |
| [paymentSourceType](payment-source-type.md) | [androidJvm]<br>val [paymentSourceType](payment-source-type.md): [PaymentMeansTypeResource](../-payment-means-type-resource/index.md) |
| [publicKey](public-key.md) | [androidJvm]<br>val [publicKey](public-key.md): [JWK](../../eu.epicompany.mobile.core.domain.model.authentication/-j-w-k/index.md) |
