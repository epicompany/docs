//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.internal.retrofit](../index.md)/[RetrofitPaymentSourceProfileNetworkApi](index.md)/[createPaymentSource](create-payment-source.md)

# createPaymentSource

[androidJvm]\

@POST(value = &quot;/api/consumers/{consumerId}/payment-source-profiles&quot;)

abstract suspend fun [createPaymentSource](create-payment-source.md)(@Path(value = &quot;consumerId&quot;)consumerId: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), @Bodypayload: [PaymentSourceUpdateRequest](../../eu.epicompany.mobile.sdk.network.model.proxy/-payment-source-update-request/index.md)): [PaymentSourceUpdateResource](../../eu.epicompany.mobile.sdk.network.model.proxy/-payment-source-update-resource/index.md)
