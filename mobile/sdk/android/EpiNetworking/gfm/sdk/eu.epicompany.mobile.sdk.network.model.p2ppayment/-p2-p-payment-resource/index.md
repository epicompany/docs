//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.model.p2ppayment](../index.md)/[P2PPaymentResource](index.md)

# P2PPaymentResource

[androidJvm]\
@Serializable

data class [P2PPaymentResource](index.md)(val id: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), val amount: [MoneyAmount](../../eu.epicompany.mobile.sdk.domain.model/-money-amount/index.md), val message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val payerPaymentMeansId: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411)?, val payeeProxyHash: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, val status: [P2PPaymentStatus](../../eu.epicompany.mobile.sdk.domain.model.p2ppayments/-p2-p-payment-status/index.md), val _embedded: [P2PPaymentEmbedded](../-p2-p-payment-embedded/index.md) = P2PPaymentEmbedded(), val _links: [P2PPaymentResourceLinks](../-p2-p-payment-resource-links/index.md) = P2PPaymentResourceLinks()) : [HalResource](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [P2PPaymentResource](-p2-p-payment-resource.md) | [androidJvm]<br>constructor(id: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), amount: [MoneyAmount](../../eu.epicompany.mobile.sdk.domain.model/-money-amount/index.md), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), payerPaymentMeansId: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411)?, payeeProxyHash: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, status: [P2PPaymentStatus](../../eu.epicompany.mobile.sdk.domain.model.p2ppayments/-p2-p-payment-status/index.md), _embedded: [P2PPaymentEmbedded](../-p2-p-payment-embedded/index.md) = P2PPaymentEmbedded(), _links: [P2PPaymentResourceLinks](../-p2-p-payment-resource-links/index.md) = P2PPaymentResourceLinks()) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](_embedded.md) | [androidJvm]<br>open override val [_embedded](_embedded.md): [P2PPaymentEmbedded](../-p2-p-payment-embedded/index.md) |
| [_links](_links.md) | [androidJvm]<br>open override val [_links](_links.md): [P2PPaymentResourceLinks](../-p2-p-payment-resource-links/index.md) |
| [amount](amount.md) | [androidJvm]<br>val [amount](amount.md): [MoneyAmount](../../eu.epicompany.mobile.sdk.domain.model/-money-amount/index.md) |
| [id](id.md) | [androidJvm]<br>val [id](id.md): [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411) |
| [message](message.md) | [androidJvm]<br>val [message](message.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [payeeProxyHash](payee-proxy-hash.md) | [androidJvm]<br>val [payeeProxyHash](payee-proxy-hash.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [payerPaymentMeansId](payer-payment-means-id.md) | [androidJvm]<br>val [payerPaymentMeansId](payer-payment-means-id.md): [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411)? |
| [status](status.md) | [androidJvm]<br>val [status](status.md): [P2PPaymentStatus](../../eu.epicompany.mobile.sdk.domain.model.p2ppayments/-p2-p-payment-status/index.md) |
