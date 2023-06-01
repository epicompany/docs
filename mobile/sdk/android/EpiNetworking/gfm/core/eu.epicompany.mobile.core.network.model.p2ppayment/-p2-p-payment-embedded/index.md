//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.p2ppayment](../index.md)/[P2PPaymentEmbedded](index.md)

# P2PPaymentEmbedded

[androidJvm]\
@Serializable

data class [P2PPaymentEmbedded](index.md)(val paymentRules: [PaymentRulesResource](../-payment-rules-resource/index.md)? = null, val payeeContact: [ConsumerProfileResource](../../eu.epicompany.mobile.core.network.model.consumer/-consumer-profile-resource/index.md)? = null, val payerContact: [ConsumerProfileResource](../../eu.epicompany.mobile.core.network.model.consumer/-consumer-profile-resource/index.md)? = null, val p2pRequest: [P2PRequestResource](../-p2-p-request-resource/index.md)? = null) : [EmbeddedHalResources](../../eu.epicompany.mobile.core.network.hypermedia/-embedded-hal-resources/index.md)

## Constructors

| | |
|---|---|
| [P2PPaymentEmbedded](-p2-p-payment-embedded.md) | [androidJvm]<br>constructor(paymentRules: [PaymentRulesResource](../-payment-rules-resource/index.md)? = null, payeeContact: [ConsumerProfileResource](../../eu.epicompany.mobile.core.network.model.consumer/-consumer-profile-resource/index.md)? = null, payerContact: [ConsumerProfileResource](../../eu.epicompany.mobile.core.network.model.consumer/-consumer-profile-resource/index.md)? = null, p2pRequest: [P2PRequestResource](../-p2-p-request-resource/index.md)? = null) |

## Properties

| Name | Summary |
|---|---|
| [p2pRequest](p2p-request.md) | [androidJvm]<br>val [p2pRequest](p2p-request.md): [P2PRequestResource](../-p2-p-request-resource/index.md)? = null |
| [payeeContact](payee-contact.md) | [androidJvm]<br>val [payeeContact](payee-contact.md): [ConsumerProfileResource](../../eu.epicompany.mobile.core.network.model.consumer/-consumer-profile-resource/index.md)? = null |
| [payerContact](payer-contact.md) | [androidJvm]<br>val [payerContact](payer-contact.md): [ConsumerProfileResource](../../eu.epicompany.mobile.core.network.model.consumer/-consumer-profile-resource/index.md)? = null |
| [paymentRules](payment-rules.md) | [androidJvm]<br>val [paymentRules](payment-rules.md): [PaymentRulesResource](../-payment-rules-resource/index.md)? = null |
