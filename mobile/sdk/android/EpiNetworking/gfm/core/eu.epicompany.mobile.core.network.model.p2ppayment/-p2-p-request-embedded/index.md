//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.p2ppayment](../index.md)/[P2PRequestEmbedded](index.md)

# P2PRequestEmbedded

[androidJvm]\
@Serializable

data class [P2PRequestEmbedded](index.md)(val payeeContact: [ConsumerProfileResource](../../eu.epicompany.mobile.core.network.model.consumer/-consumer-profile-resource/index.md)? = null, val payerContact: [ConsumerProfileResource](../../eu.epicompany.mobile.core.network.model.consumer/-consumer-profile-resource/index.md)? = null, val p2pPayment: [P2PPaymentResource](../-p2-p-payment-resource/index.md)? = null) : [EmbeddedHalResources](../../eu.epicompany.mobile.core.network.hypermedia/-embedded-hal-resources/index.md)

## Constructors

| | |
|---|---|
| [P2PRequestEmbedded](-p2-p-request-embedded.md) | [androidJvm]<br>constructor(payeeContact: [ConsumerProfileResource](../../eu.epicompany.mobile.core.network.model.consumer/-consumer-profile-resource/index.md)? = null, payerContact: [ConsumerProfileResource](../../eu.epicompany.mobile.core.network.model.consumer/-consumer-profile-resource/index.md)? = null, p2pPayment: [P2PPaymentResource](../-p2-p-payment-resource/index.md)? = null) |

## Properties

| Name | Summary |
|---|---|
| [p2pPayment](p2p-payment.md) | [androidJvm]<br>val [p2pPayment](p2p-payment.md): [P2PPaymentResource](../-p2-p-payment-resource/index.md)? = null |
| [payeeContact](payee-contact.md) | [androidJvm]<br>val [payeeContact](payee-contact.md): [ConsumerProfileResource](../../eu.epicompany.mobile.core.network.model.consumer/-consumer-profile-resource/index.md)? = null |
| [payerContact](payer-contact.md) | [androidJvm]<br>val [payerContact](payer-contact.md): [ConsumerProfileResource](../../eu.epicompany.mobile.core.network.model.consumer/-consumer-profile-resource/index.md)? = null |
