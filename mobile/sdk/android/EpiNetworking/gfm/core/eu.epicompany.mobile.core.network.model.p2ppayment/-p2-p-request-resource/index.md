//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.p2ppayment](../index.md)/[P2PRequestResource](index.md)

# P2PRequestResource

[androidJvm]\
@Serializable

data class [P2PRequestResource](index.md)(val id: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val amount: [MoneyAmount](../../eu.epicompany.mobile.core.domain.model/-money-amount/index.md), val message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, val status: [P2PRequestStatus](../../eu.epicompany.mobile.core.domain.model.p2ppayments/-p2-p-request-status/index.md), val created: [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html), val payeePaymentMeansId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556)? = null, val payerProxyHash: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val _embedded: [P2PRequestEmbedded](../-p2-p-request-embedded/index.md) = P2PRequestEmbedded(), val _links: [P2PRequestLinks](../-p2-p-request-links/index.md) = P2PRequestLinks()) : [HalResource](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [P2PRequestResource](-p2-p-request-resource.md) | [androidJvm]<br>constructor(id: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), amount: [MoneyAmount](../../eu.epicompany.mobile.core.domain.model/-money-amount/index.md), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, status: [P2PRequestStatus](../../eu.epicompany.mobile.core.domain.model.p2ppayments/-p2-p-request-status/index.md), created: [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html), payeePaymentMeansId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556)? = null, payerProxyHash: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, _embedded: [P2PRequestEmbedded](../-p2-p-request-embedded/index.md) = P2PRequestEmbedded(), _links: [P2PRequestLinks](../-p2-p-request-links/index.md) = P2PRequestLinks()) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](_embedded.md) | [androidJvm]<br>open override val [_embedded](_embedded.md): [P2PRequestEmbedded](../-p2-p-request-embedded/index.md) |
| [_links](_links.md) | [androidJvm]<br>open override val [_links](_links.md): [P2PRequestLinks](../-p2-p-request-links/index.md) |
| [amount](amount.md) | [androidJvm]<br>val [amount](amount.md): [MoneyAmount](../../eu.epicompany.mobile.core.domain.model/-money-amount/index.md) |
| [created](created.md) | [androidJvm]<br>val [created](created.md): [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html) |
| [id](id.md) | [androidJvm]<br>val [id](id.md): [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556) |
| [message](message.md) | [androidJvm]<br>val [message](message.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [payeePaymentMeansId](payee-payment-means-id.md) | [androidJvm]<br>val [payeePaymentMeansId](payee-payment-means-id.md): [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556)? = null |
| [payerProxyHash](payer-proxy-hash.md) | [androidJvm]<br>val [payerProxyHash](payer-proxy-hash.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [status](status.md) | [androidJvm]<br>val [status](status.md): [P2PRequestStatus](../../eu.epicompany.mobile.core.domain.model.p2ppayments/-p2-p-request-status/index.md) |
