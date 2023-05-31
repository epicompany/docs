//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.datasource](../index.md)/[PaymentSourceProfileNetworkDataSource](index.md)/[editPaymentSource](edit-payment-source.md)

# editPaymentSource

[androidJvm]\
abstract suspend fun [editPaymentSource](edit-payment-source.md)(consumerId: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), paymentSourceProfileID: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), payload: [EditPaymentSourceRequest](../../eu.epicompany.mobile.sdk.network.model.proxy/-edit-payment-source-request/index.md)): [EditPaymentSourceResource](../../eu.epicompany.mobile.sdk.network.model.proxy/-edit-payment-source-resource/index.md)

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
