//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.model.proxy](../index.md)/[RequestOTPResource](index.md)

# RequestOTPResource

[androidJvm]\
@Serializable

data class [RequestOTPResource](index.md)(val type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val contactItemId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val createdAt: [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html), val verified: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), val nextChallengeNotBefore: [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html), val _links: [RequestOTPLinks](../-request-o-t-p-links/index.md)?) : [HalResource](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [RequestOTPResource](-request-o-t-p-resource.md) | [androidJvm]<br>constructor(type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), contactItemId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), createdAt: [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html), verified: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), nextChallengeNotBefore: [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html), _links: [RequestOTPLinks](../-request-o-t-p-links/index.md)?) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_embedded.md) | [androidJvm]<br>open val [_embedded](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_embedded.md): [EmbeddedHalResources](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-embedded-hal-resources/index.md)? |
| [_links](_links.md) | [androidJvm]<br>open override val [_links](_links.md): [RequestOTPLinks](../-request-o-t-p-links/index.md)? |
| [contactItemId](contact-item-id.md) | [androidJvm]<br>val [contactItemId](contact-item-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [createdAt](created-at.md) | [androidJvm]<br>val [createdAt](created-at.md): [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html) |
| [nextChallengeNotBefore](next-challenge-not-before.md) | [androidJvm]<br>val [nextChallengeNotBefore](next-challenge-not-before.md): [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html) |
| [type](type.md) | [androidJvm]<br>val [type](type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [value](value.md) | [androidJvm]<br>val [value](value.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [verified](verified.md) | [androidJvm]<br>val [verified](verified.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
