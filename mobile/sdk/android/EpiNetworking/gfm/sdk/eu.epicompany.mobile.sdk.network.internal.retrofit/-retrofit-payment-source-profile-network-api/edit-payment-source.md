//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.internal.retrofit](../index.md)/[RetrofitPaymentSourceProfileNetworkApi](index.md)/[editPaymentSource](edit-payment-source.md)

# editPaymentSource

[androidJvm]\

@PUT(value = &quot;/api/consumers/{consumerId}/payment-source-profiles/{paymentSourceProfileId}&quot;)

abstract suspend fun [editPaymentSource](edit-payment-source.md)(@Path(value = &quot;consumerId&quot;)consumerId: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), @Path(value = &quot;paymentSourceProfileId&quot;)paymentSourceProfileID: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), @Bodypayload: [EditPaymentSourceRequest](../../eu.epicompany.mobile.sdk.network.model.proxy/-edit-payment-source-request/index.md)): [EditPaymentSourceResource](../../eu.epicompany.mobile.sdk.network.model.proxy/-edit-payment-source-resource/index.md)
