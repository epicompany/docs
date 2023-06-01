//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.wallet](../index.md)/[EmbeddedPaymentSourceProfileResource](index.md)

# EmbeddedPaymentSourceProfileResource

[androidJvm]\
@Serializable

data class [EmbeddedPaymentSourceProfileResource](index.md)(val id: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556)? = null, val displayName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val paymentSourceProxies: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[EmbeddedPaymentSourceProfileResource.PaymentSourceProxyResource](-payment-source-proxy-resource/index.md)&gt; = emptyList()) : [HalResource](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [EmbeddedPaymentSourceProfileResource](-embedded-payment-source-profile-resource.md) | [androidJvm]<br>constructor(id: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556)? = null, displayName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), paymentSourceProxies: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[EmbeddedPaymentSourceProfileResource.PaymentSourceProxyResource](-payment-source-proxy-resource/index.md)&gt; = emptyList()) |

## Types

| Name | Summary |
|---|---|
| [PaymentSourceProxyResource](-payment-source-proxy-resource/index.md) | [androidJvm]<br>@Serializable<br>sealed class [PaymentSourceProxyResource](-payment-source-proxy-resource/index.md) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/_embedded.md) | [androidJvm]<br>open val [_embedded](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/_embedded.md): [EmbeddedHalResources](../../eu.epicompany.mobile.core.network.hypermedia/-embedded-hal-resources/index.md)? |
| [_links](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/_links.md) | [androidJvm]<br>open val [_links](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/_links.md): [HalLinks](../../eu.epicompany.mobile.core.network.hypermedia/-hal-links/index.md)? |
| [displayName](display-name.md) | [androidJvm]<br>val [displayName](display-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [id](id.md) | [androidJvm]<br>val [id](id.md): [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556)? = null |
| [paymentSourceProxies](payment-source-proxies.md) | [androidJvm]<br>val [paymentSourceProxies](payment-source-proxies.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[EmbeddedPaymentSourceProfileResource.PaymentSourceProxyResource](-payment-source-proxy-resource/index.md)&gt; |
