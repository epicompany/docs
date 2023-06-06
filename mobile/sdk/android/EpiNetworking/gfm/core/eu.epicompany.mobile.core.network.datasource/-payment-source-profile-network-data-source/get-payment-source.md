//[core](../../../index.md)/[eu.epicompany.mobile.core.network.datasource](../index.md)/[PaymentSourceProfileNetworkDataSource](index.md)/[getPaymentSource](get-payment-source.md)

# getPaymentSource

[androidJvm]\
abstract suspend fun [getPaymentSource](get-payment-source.md)(consumerId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), paymentSourceProfileID: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556)): [PaymentSourceProfileResource](../../eu.epicompany.mobile.core.network.model.proxy/-payment-source-profile-resource/index.md)

Fetches a payment source profile for the specified consumer.

#### Return

The payment source profile resource.

#### Parameters

androidJvm

| | |
|---|---|
| consumerId | The consumer ID. |
| paymentSourceProfileID | The payment source profile ID. |
