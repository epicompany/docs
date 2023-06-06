//[core](../../../index.md)/[eu.epicompany.mobile.core.network.internal.retrofit](../index.md)/[RetrofitPaymentSourceProfileNetworkApi](index.md)/[createPaymentSource](create-payment-source.md)

# createPaymentSource

[androidJvm]\

@POST(value = &quot;/api/consumers/{consumerId}/payment-source-profiles&quot;)

abstract fun [createPaymentSource](create-payment-source.md)(@Path(value = &quot;consumerId&quot;)consumerId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), @Bodypayload: [PaymentSourceUpdateRequest](../../eu.epicompany.mobile.core.network.model.proxy/-payment-source-update-request/index.md)): Call&lt;[PaymentSourceUpdateResource](../../eu.epicompany.mobile.core.network.model.proxy/-payment-source-update-resource/index.md)&gt;
