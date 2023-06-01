//[core](../../../index.md)/[eu.epicompany.mobile.core.network.internal.retrofit](../index.md)/[RetrofitProxyApi](index.md)

# RetrofitProxyApi

[androidJvm]\
interface [RetrofitProxyApi](index.md)

Proxy api.

## Functions

| Name | Summary |
|---|---|
| [customer](customer.md) | [androidJvm]<br>@GET(value = &quot;/api/proxies/{proxyHash}&quot;)<br>abstract suspend fun [customer](customer.md)(@Path(value = &quot;proxyHash&quot;)proxyHash: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [EpiConsumerResponse](../../eu.epicompany.mobile.core.network.model.proxy/-epi-consumer-response/index.md) |
| [proxyIndicators](proxy-indicators.md) | [androidJvm]<br>@POST(value = &quot;/api/proxy-indicators&quot;)<br>abstract suspend fun [proxyIndicators](proxy-indicators.md)(@Bodyproxies: [RetrieveProxyIndicatorsPayload](../../eu.epicompany.mobile.core.network.model.proxy/-retrieve-proxy-indicators-payload/index.md)): [ProxyIndicatorsResponse](../../eu.epicompany.mobile.core.network.model.proxy/-proxy-indicators-response/index.md) |
