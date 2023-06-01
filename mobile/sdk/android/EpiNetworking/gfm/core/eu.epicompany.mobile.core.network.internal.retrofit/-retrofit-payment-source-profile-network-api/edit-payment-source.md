//[core](../../../index.md)/[eu.epicompany.mobile.core.network.internal.retrofit](../index.md)/[RetrofitPaymentSourceProfileNetworkApi](index.md)/[editPaymentSource](edit-payment-source.md)

# editPaymentSource

[androidJvm]\

@PUT(value = &quot;/api/consumers/{consumerId}/payment-source-profiles/{paymentSourceProfileId}&quot;)

abstract suspend fun [editPaymentSource](edit-payment-source.md)(@Path(value = &quot;consumerId&quot;)consumerId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), @Path(value = &quot;paymentSourceProfileId&quot;)paymentSourceProfileID: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), @Bodypayload: [EditPaymentSourceRequest](../../eu.epicompany.mobile.core.network.model.proxy/-edit-payment-source-request/index.md)): [EditPaymentSourceResource](../../eu.epicompany.mobile.core.network.model.proxy/-edit-payment-source-resource/index.md)
