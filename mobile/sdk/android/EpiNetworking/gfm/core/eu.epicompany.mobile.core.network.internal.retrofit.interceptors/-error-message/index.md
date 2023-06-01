//[core](../../../index.md)/[eu.epicompany.mobile.core.network.internal.retrofit.interceptors](../index.md)/[ErrorMessage](index.md)

# ErrorMessage

[androidJvm]\
@Serializable

data class [ErrorMessage](index.md)(val message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val _embedded: [ErrorMessageEmbedded](../-error-message-embedded/index.md)?) : [HalResource](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [ErrorMessage](-error-message.md) | [androidJvm]<br>constructor(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), _embedded: [ErrorMessageEmbedded](../-error-message-embedded/index.md)?) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](_embedded.md) | [androidJvm]<br>open override val [_embedded](_embedded.md): [ErrorMessageEmbedded](../-error-message-embedded/index.md)? |
| [_links](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/_links.md) | [androidJvm]<br>open val [_links](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/_links.md): [HalLinks](../../eu.epicompany.mobile.core.network.hypermedia/-hal-links/index.md)? |
| [message](message.md) | [androidJvm]<br>val [message](message.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
