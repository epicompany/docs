//[sdk](../../index.md)/[eu.epicompany.mobile.sdk.network.internal.retrofit.interceptors](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [EpiWSError](-epi-w-s-error/index.md) | [androidJvm]<br>data class [EpiWSError](-epi-w-s-error/index.md)(val message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val code: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [IOException](https://developer.android.com/reference/kotlin/java/io/IOException.html) |
| [Error](-error/index.md) | [androidJvm]<br>@Serializable<br>data class [Error](-error/index.md)(val message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [ErrorInterceptor](-error-interceptor/index.md) | [androidJvm]<br>class [ErrorInterceptor](-error-interceptor/index.md)(networkErrorCallback: [NetworkErrorCallback](../eu.epicompany.mobile.sdk.network.error/-network-error-callback/index.md), json: Json) : Interceptor<br>The error interceptor for handling the error responses. |
| [ErrorMessage](-error-message/index.md) | [androidJvm]<br>@Serializable<br>data class [ErrorMessage](-error-message/index.md)(val message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val _embedded: [ErrorMessageEmbedded](-error-message-embedded/index.md)?) : [HalResource](../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/index.md) |
| [ErrorMessageEmbedded](-error-message-embedded/index.md) | [androidJvm]<br>@Serializable<br>data class [ErrorMessageEmbedded](-error-message-embedded/index.md)(val errors: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Error](-error/index.md)&gt;) : [EmbeddedHalResources](../eu.epicompany.mobile.android.data.network.model.hypermedia/-embedded-hal-resources/index.md) |
| [LoggingInterceptor](-logging-interceptor/index.md) | [androidJvm]<br>class [LoggingInterceptor](-logging-interceptor/index.md) : Interceptor<br>The logging interceptor for logging the request and response. |
| [NetworkInterceptor](-network-interceptor/index.md) | [androidJvm]<br>class [NetworkInterceptor](-network-interceptor/index.md)(accessTokenProvider: [AccessTokenProvider](../eu.epicompany.mobile.sdk.network.authentication/-access-token-provider/index.md)) : Interceptor<br>The network interceptor for adding the authorization header. |
