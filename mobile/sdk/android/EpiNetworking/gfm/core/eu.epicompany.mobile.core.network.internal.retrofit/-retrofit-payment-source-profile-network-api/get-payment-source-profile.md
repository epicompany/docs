//[core](../../../index.md)/[eu.epicompany.mobile.core.network.internal.retrofit](../index.md)/[RetrofitPaymentSourceProfileNetworkApi](index.md)/[getPaymentSourceProfile](get-payment-source-profile.md)

# getPaymentSourceProfile

[androidJvm]\

@GET(value = &quot;/api/consumers/{consumerId}/payment-source-profiles/{paymentSourceProfileId}&quot;)

abstract suspend fun [getPaymentSourceProfile](get-payment-source-profile.md)(@Path(value = &quot;consumerId&quot;)consumerId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), @Path(value = &quot;paymentSourceProfileId&quot;)paymentSourceProfileID: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556)): [PaymentSourceProfileResource](../../eu.epicompany.mobile.core.network.model.proxy/-payment-source-profile-resource/index.md)
