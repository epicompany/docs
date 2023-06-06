//[core](../../../index.md)/[eu.epicompany.mobile.core.network.datasource](../index.md)/[ProxyNetworkDataSource](index.md)/[fetchProxyIndicators](fetch-proxy-indicators.md)

# fetchProxyIndicators

[androidJvm]\
abstract fun [fetchProxyIndicators](fetch-proxy-indicators.md)(payload: [RetrieveProxyIndicatorsPayload](../../eu.epicompany.mobile.core.network.model.proxy/-retrieve-proxy-indicators-payload/index.md)): [ProxyIndicatorsResponse](../../eu.epicompany.mobile.core.network.model.proxy/-proxy-indicators-response/index.md)

Retrieves the proxy indicators for the provided local proxy hash list.

#### Return

Only epi known proxy hashes, may be empty if none.

#### Parameters

androidJvm

| | |
|---|---|
| payload | The local proxy hashes to be verified against epi services. |
