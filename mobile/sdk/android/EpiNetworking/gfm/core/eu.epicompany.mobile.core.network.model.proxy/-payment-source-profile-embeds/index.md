//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.proxy](../index.md)/[PaymentSourceProfileEmbeds](index.md)

# PaymentSourceProfileEmbeds

[androidJvm]\
@Serializable

data class [PaymentSourceProfileEmbeds](index.md)(val consumerPsp: [EmbeddedConsumerPspResource](../../eu.epicompany.mobile.core.network.model.wallet/-embedded-consumer-psp-resource/index.md)? = null, val paymentSourceProxies: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[EmbeddedPaymentSourceProfileResource.PaymentSourceProxyResource](../../eu.epicompany.mobile.core.network.model.wallet/-embedded-payment-source-profile-resource/-payment-source-proxy-resource/index.md)&gt;) : [EmbeddedHalResources](../../eu.epicompany.mobile.core.network.hypermedia/-embedded-hal-resources/index.md)

## Constructors

| | |
|---|---|
| [PaymentSourceProfileEmbeds](-payment-source-profile-embeds.md) | [androidJvm]<br>constructor(consumerPsp: [EmbeddedConsumerPspResource](../../eu.epicompany.mobile.core.network.model.wallet/-embedded-consumer-psp-resource/index.md)? = null, paymentSourceProxies: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[EmbeddedPaymentSourceProfileResource.PaymentSourceProxyResource](../../eu.epicompany.mobile.core.network.model.wallet/-embedded-payment-source-profile-resource/-payment-source-proxy-resource/index.md)&gt;) |

## Properties

| Name | Summary |
|---|---|
| [consumerPsp](consumer-psp.md) | [androidJvm]<br>val [consumerPsp](consumer-psp.md): [EmbeddedConsumerPspResource](../../eu.epicompany.mobile.core.network.model.wallet/-embedded-consumer-psp-resource/index.md)? = null |
| [paymentSourceProxies](payment-source-proxies.md) | [androidJvm]<br>val [paymentSourceProxies](payment-source-proxies.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[EmbeddedPaymentSourceProfileResource.PaymentSourceProxyResource](../../eu.epicompany.mobile.core.network.model.wallet/-embedded-payment-source-profile-resource/-payment-source-proxy-resource/index.md)&gt; |
