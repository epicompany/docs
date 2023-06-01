//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.p2ppayment](../index.md)/[CreateP2PRequestRequest](index.md)

# CreateP2PRequestRequest

[androidJvm]\
@Serializable

data class [CreateP2PRequestRequest](index.md)(val amount: [MoneyAmount](../../eu.epicompany.mobile.core.domain.model/-money-amount/index.md), val message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val payeePaymentMeansId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val payerProxyHash: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

## Constructors

| | |
|---|---|
| [CreateP2PRequestRequest](-create-p2-p-request-request.md) | [androidJvm]<br>constructor(amount: [MoneyAmount](../../eu.epicompany.mobile.core.domain.model/-money-amount/index.md), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, payeePaymentMeansId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), payerProxyHash: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [amount](amount.md) | [androidJvm]<br>val [amount](amount.md): [MoneyAmount](../../eu.epicompany.mobile.core.domain.model/-money-amount/index.md) |
| [message](message.md) | [androidJvm]<br>val [message](message.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [payeePaymentMeansId](payee-payment-means-id.md) | [androidJvm]<br>val [payeePaymentMeansId](payee-payment-means-id.md): [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556) |
| [payerProxyHash](payer-proxy-hash.md) | [androidJvm]<br>val [payerProxyHash](payer-proxy-hash.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
