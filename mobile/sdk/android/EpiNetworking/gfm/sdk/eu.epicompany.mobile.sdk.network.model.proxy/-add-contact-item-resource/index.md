//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.model.proxy](../index.md)/[AddContactItemResource](index.md)

# AddContactItemResource

[androidJvm]\
@Serializable

data class [AddContactItemResource](index.md)(val contactItemId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val type: [PaymentSourceProxyType](../../eu.epicompany.mobile.sdk.domain.model.proxy/-payment-source-proxy-type/index.md), val value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val createdAt: [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html), val verified: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), val _links: [PaymentSourceProxyLinks](../-payment-source-proxy-links/index.md)?, val verifiedAt: [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html)?, val nextChallengeNotBefore: [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html)?, val linkedPaymentSourceID: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [HalResource](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [AddContactItemResource](-add-contact-item-resource.md) | [androidJvm]<br>constructor(contactItemId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [PaymentSourceProxyType](../../eu.epicompany.mobile.sdk.domain.model.proxy/-payment-source-proxy-type/index.md), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), createdAt: [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html), verified: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), _links: [PaymentSourceProxyLinks](../-payment-source-proxy-links/index.md)?, verifiedAt: [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html)?, nextChallengeNotBefore: [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html)?, linkedPaymentSourceID: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_embedded.md) | [androidJvm]<br>open val [_embedded](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_embedded.md): [EmbeddedHalResources](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-embedded-hal-resources/index.md)? |
| [_links](_links.md) | [androidJvm]<br>open override val [_links](_links.md): [PaymentSourceProxyLinks](../-payment-source-proxy-links/index.md)? |
| [contactItemId](contact-item-id.md) | [androidJvm]<br>val [contactItemId](contact-item-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [createdAt](created-at.md) | [androidJvm]<br>val [createdAt](created-at.md): [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html) |
| [linkedPaymentSourceID](linked-payment-source-i-d.md) | [androidJvm]<br>val [linkedPaymentSourceID](linked-payment-source-i-d.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [nextChallengeNotBefore](next-challenge-not-before.md) | [androidJvm]<br>val [nextChallengeNotBefore](next-challenge-not-before.md): [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html)? |
| [state](state.md) | [androidJvm]<br>val [state](state.md): [ContactItemState](../-contact-item-state/index.md) |
| [type](type.md) | [androidJvm]<br>val [type](type.md): [PaymentSourceProxyType](../../eu.epicompany.mobile.sdk.domain.model.proxy/-payment-source-proxy-type/index.md) |
| [value](value.md) | [androidJvm]<br>val [value](value.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [verified](verified.md) | [androidJvm]<br>val [verified](verified.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [verifiedAt](verified-at.md) | [androidJvm]<br>val [verifiedAt](verified-at.md): [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html)? |
