//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.p2ppayment](../index.md)/[CreateP2PPaymentRequest](index.md)

# CreateP2PPaymentRequest

[androidJvm]\
@Serializable

data class [CreateP2PPaymentRequest](index.md)(val amount: [MoneyAmount](../../eu.epicompany.mobile.core.domain.model/-money-amount/index.md), val message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val payerPaymentMeansId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val payeeProxyHash: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

## Constructors

| | |
|---|---|
| [CreateP2PPaymentRequest](-create-p2-p-payment-request.md) | [androidJvm]<br>constructor(amount: [MoneyAmount](../../eu.epicompany.mobile.core.domain.model/-money-amount/index.md), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, payerPaymentMeansId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), payeeProxyHash: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [amount](amount.md) | [androidJvm]<br>val [amount](amount.md): [MoneyAmount](../../eu.epicompany.mobile.core.domain.model/-money-amount/index.md) |
| [message](message.md) | [androidJvm]<br>val [message](message.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [payeeProxyHash](payee-proxy-hash.md) | [androidJvm]<br>val [payeeProxyHash](payee-proxy-hash.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [payerPaymentMeansId](payer-payment-means-id.md) | [androidJvm]<br>val [payerPaymentMeansId](payer-payment-means-id.md): [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556) |
