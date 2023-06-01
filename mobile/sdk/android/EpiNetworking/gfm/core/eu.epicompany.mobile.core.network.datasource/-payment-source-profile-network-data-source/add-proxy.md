//[core](../../../index.md)/[eu.epicompany.mobile.core.network.datasource](../index.md)/[PaymentSourceProfileNetworkDataSource](index.md)/[addProxy](add-proxy.md)

# addProxy

[androidJvm]\
abstract suspend fun [addProxy](add-proxy.md)(consumerId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), paymentSourceProfileID: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), payload: [AddProxyRequest](../../eu.epicompany.mobile.core.network.model.proxy/-add-proxy-request/index.md)): [AddProxyResource](../../eu.epicompany.mobile.core.network.model.proxy/-add-proxy-resource/index.md)

Adds a proxy to a payment source.

#### Return

The payment source profile resource.

#### Parameters

androidJvm

| | |
|---|---|
| consumerId | The consumer ID. |
| paymentSourceProfileID | The payment source profile ID. |
| payload | The payload containing the proxy details to add. |
