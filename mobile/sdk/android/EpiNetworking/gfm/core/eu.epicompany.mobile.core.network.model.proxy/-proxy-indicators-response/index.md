//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.proxy](../index.md)/[ProxyIndicatorsResponse](index.md)

# ProxyIndicatorsResponse

[androidJvm]\
@Serializable

data class [ProxyIndicatorsResponse](index.md)(val indicators: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)&lt;[ProxyIndicator](../-proxy-indicator/index.md)&gt;, val expiresAt: [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html), val truncated: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)

## Constructors

| | |
|---|---|
| [ProxyIndicatorsResponse](-proxy-indicators-response.md) | [androidJvm]<br>constructor(indicators: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)&lt;[ProxyIndicator](../-proxy-indicator/index.md)&gt;, expiresAt: [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html), truncated: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false) |

## Properties

| Name | Summary |
|---|---|
| [expiresAt](expires-at.md) | [androidJvm]<br>val [expiresAt](expires-at.md): [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html) |
| [indicators](indicators.md) | [androidJvm]<br>val [indicators](indicators.md): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)&lt;[ProxyIndicator](../-proxy-indicator/index.md)&gt; |
| [truncated](truncated.md) | [androidJvm]<br>val [truncated](truncated.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
