//[core](../../../index.md)/[eu.epicompany.mobile.core.network.datasource](../index.md)/[PaymentSourceProfileNetworkDataSource](index.md)/[removeProxy](remove-proxy.md)

# removeProxy

[androidJvm]\
abstract suspend fun [removeProxy](remove-proxy.md)(consumerId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), paymentSourceProfileID: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), proxyId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556)): Response&lt;[Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)&gt;

Removes a proxy from a payment source.

#### Return

The payment source profile resource.

#### Parameters

androidJvm

| | |
|---|---|
| consumerId | The consumer ID. |
| paymentSourceProfileID | The payment source profile ID. |
| proxyId | The proxy ID to remove. |
