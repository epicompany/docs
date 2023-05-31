//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.model.consumer](../index.md)/[ConsumerProfileResource](index.md)

# ConsumerProfileResource

[androidJvm]\
@Serializable

data class [ConsumerProfileResource](index.md)(val displayName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, val proxyValue: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, val profileImage: [ProfileImageResource](../../eu.epicompany.mobile.sdk.network.model/-profile-image-resource/index.md)?) : [HalResource](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [ConsumerProfileResource](-consumer-profile-resource.md) | [androidJvm]<br>constructor(displayName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, proxyValue: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, profileImage: [ProfileImageResource](../../eu.epicompany.mobile.sdk.network.model/-profile-image-resource/index.md)?) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_embedded.md) | [androidJvm]<br>open val [_embedded](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_embedded.md): [EmbeddedHalResources](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-embedded-hal-resources/index.md)? |
| [_links](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_links.md) | [androidJvm]<br>open val [_links](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/_links.md): [HalLinks](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-links/index.md)? |
| [displayName](display-name.md) | [androidJvm]<br>val [displayName](display-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [profileImage](profile-image.md) | [androidJvm]<br>val [profileImage](profile-image.md): [ProfileImageResource](../../eu.epicompany.mobile.sdk.network.model/-profile-image-resource/index.md)? |
| [proxyValue](proxy-value.md) | [androidJvm]<br>val [proxyValue](proxy-value.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
