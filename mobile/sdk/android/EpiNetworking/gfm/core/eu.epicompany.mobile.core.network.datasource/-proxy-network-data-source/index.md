//[core](../../../index.md)/[eu.epicompany.mobile.core.network.datasource](../index.md)/[ProxyNetworkDataSource](index.md)

# ProxyNetworkDataSource

[androidJvm]\
interface [ProxyNetworkDataSource](index.md)

An interface for managing proxy related operations.

## Functions

| Name | Summary |
|---|---|
| [fetchProxyIndicators](fetch-proxy-indicators.md) | [androidJvm]<br>abstract fun [fetchProxyIndicators](fetch-proxy-indicators.md)(payload: [RetrieveProxyIndicatorsPayload](../../eu.epicompany.mobile.core.network.model.proxy/-retrieve-proxy-indicators-payload/index.md)): [ProxyIndicatorsResponse](../../eu.epicompany.mobile.core.network.model.proxy/-proxy-indicators-response/index.md)<br>Retrieves the proxy indicators for the provided local proxy hash list. |
| [fetchProxyInfo](fetch-proxy-info.md) | [androidJvm]<br>abstract fun [fetchProxyInfo](fetch-proxy-info.md)(proxyHash: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [EpiConsumerResponse](../../eu.epicompany.mobile.core.network.model.proxy/-epi-consumer-response/index.md)<br>Retrieves the proxy information for the provided proxy hash. |
