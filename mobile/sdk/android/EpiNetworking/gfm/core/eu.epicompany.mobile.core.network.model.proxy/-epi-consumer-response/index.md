//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.proxy](../index.md)/[EpiConsumerResponse](index.md)

# EpiConsumerResponse

[androidJvm]\
@Serializable

data class [EpiConsumerResponse](index.md)(val proxyValue: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val displayName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val profileImage: [ProfileImageResource](../../eu.epicompany.mobile.core.network.model/-profile-image-resource/index.md))

Represents the verified data about an epi customer to be shown to another epi customer e.g. when initiating a money transfer.

## Constructors

| | |
|---|---|
| [EpiConsumerResponse](-epi-consumer-response.md) | [androidJvm]<br>constructor(proxyValue: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), displayName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), profileImage: [ProfileImageResource](../../eu.epicompany.mobile.core.network.model/-profile-image-resource/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [displayName](display-name.md) | [androidJvm]<br>val [displayName](display-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The name of the identity belonging to the requested proxy. &quot;Paulina&quot; in the Figma example screen. |
| [profileImage](profile-image.md) | [androidJvm]<br>val [profileImage](profile-image.md): [ProfileImageResource](../../eu.epicompany.mobile.core.network.model/-profile-image-resource/index.md)<br>The profile image of the epi customer. |
| [proxyValue](proxy-value.md) | [androidJvm]<br>val [proxyValue](proxy-value.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The proxy value associated with the given hash value |
