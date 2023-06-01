//[core](../../../../index.md)/[eu.epicompany.mobile.core.network.model.wallet](../../index.md)/[EmbeddedPaymentSourceProfileResource](../index.md)/[PaymentSourceProxyResource](index.md)

# PaymentSourceProxyResource

@Serializable

sealed class [PaymentSourceProxyResource](index.md)

#### Inheritors

| |
|---|
| [PhoneNumberPaymentSourceProxyResource](-phone-number-payment-source-proxy-resource/index.md) |
| [EmailAddressPaymentSourceProxyResource](-email-address-payment-source-proxy-resource/index.md) |
| [EpiTagPaymentSourceProxyResource](-epi-tag-payment-source-proxy-resource/index.md) |

## Types

| Name | Summary |
|---|---|
| [EmailAddressPaymentSourceProxyResource](-email-address-payment-source-proxy-resource/index.md) | [androidJvm]<br>@Serializable<br>data class [EmailAddressPaymentSourceProxyResource](-email-address-payment-source-proxy-resource/index.md)(val id: [UUID4](../../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [EmbeddedPaymentSourceProfileResource.PaymentSourceProxyResource](index.md) |
| [EpiTagPaymentSourceProxyResource](-epi-tag-payment-source-proxy-resource/index.md) | [androidJvm]<br>@Serializable<br>data class [EpiTagPaymentSourceProxyResource](-epi-tag-payment-source-proxy-resource/index.md)(val id: [UUID4](../../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [EmbeddedPaymentSourceProfileResource.PaymentSourceProxyResource](index.md) |
| [PhoneNumberPaymentSourceProxyResource](-phone-number-payment-source-proxy-resource/index.md) | [androidJvm]<br>@Serializable<br>data class [PhoneNumberPaymentSourceProxyResource](-phone-number-payment-source-proxy-resource/index.md)(val id: [UUID4](../../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [EmbeddedPaymentSourceProfileResource.PaymentSourceProxyResource](index.md) |

## Properties

| Name | Summary |
|---|---|
| [id](id.md) | [androidJvm]<br>abstract val [id](id.md): [UUID4](../../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556) |
