//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.datasource](../index.md)/[ProxyNetworkDataSource](index.md)/[fetchProxyIndicators](fetch-proxy-indicators.md)

# fetchProxyIndicators

[androidJvm]\
abstract suspend fun [fetchProxyIndicators](fetch-proxy-indicators.md)(payload: [RetrieveProxyIndicatorsPayload](../../eu.epicompany.mobile.sdk.network.model.proxy/-retrieve-proxy-indicators-payload/index.md)): [ProxyIndicatorsResponse](../../eu.epicompany.mobile.sdk.network.model.proxy/-proxy-indicators-response/index.md)

Retrieves the proxy indicators for the provided local proxy hash list.

#### Return

Only epi known proxy hashes, may be empty if none.

#### Parameters

androidJvm

| | |
|---|---|
| payload | The local proxy hashes to be verified against epi services. |
