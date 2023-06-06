//[core](../../../index.md)/[eu.epicompany.mobile.core.network.datasource](../index.md)/[PaymentSourceProfileNetworkDataSource](index.md)/[editPaymentSource](edit-payment-source.md)

# editPaymentSource

[androidJvm]\
abstract fun [editPaymentSource](edit-payment-source.md)(consumerId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), paymentSourceProfileID: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), payload: [EditPaymentSourceRequest](../../eu.epicompany.mobile.core.network.model.proxy/-edit-payment-source-request/index.md)): [EditPaymentSourceResource](../../eu.epicompany.mobile.core.network.model.proxy/-edit-payment-source-resource/index.md)

Updates a payment source profile for the specified consumer.

#### Return

The payment source profile resource.

#### Parameters

androidJvm

| | |
|---|---|
| consumerId | The consumer ID. |
| paymentSourceProfileID | The payment source profile ID. |
| payload | The payload containing the updated payment source details. |
