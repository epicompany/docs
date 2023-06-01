//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.p2ppayment](../index.md)/[PaymentRulesResource](index.md)

# PaymentRulesResource

[androidJvm]\
@Serializable

data class [PaymentRulesResource](index.md)(val paymentRules: [PaymentRules](../../eu.epicompany.mobile.core.domain.model.consent/-payment-rules/index.md), val _links: [SelfLinkOnly](../../eu.epicompany.mobile.core.network.hypermedia/-self-link-only/index.md)) : [HalResource](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [PaymentRulesResource](-payment-rules-resource.md) | [androidJvm]<br>constructor(paymentRules: [PaymentRules](../../eu.epicompany.mobile.core.domain.model.consent/-payment-rules/index.md), _links: [SelfLinkOnly](../../eu.epicompany.mobile.core.network.hypermedia/-self-link-only/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/_embedded.md) | [androidJvm]<br>open val [_embedded](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/_embedded.md): [EmbeddedHalResources](../../eu.epicompany.mobile.core.network.hypermedia/-embedded-hal-resources/index.md)? |
| [_links](_links.md) | [androidJvm]<br>open override val [_links](_links.md): [SelfLinkOnly](../../eu.epicompany.mobile.core.network.hypermedia/-self-link-only/index.md) |
| [paymentRules](payment-rules.md) | [androidJvm]<br>val [paymentRules](payment-rules.md): [PaymentRules](../../eu.epicompany.mobile.core.domain.model.consent/-payment-rules/index.md) |
