//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.internal.retrofit](../index.md)/[RetrofitPaymentSourceProfileNetworkApi](index.md)/[addProxy](add-proxy.md)

# addProxy

[androidJvm]\

@POST(value = &quot;/api/consumers/{consumerId}/payment-source-profiles/{paymentSourceProfileId}/proxies&quot;)

abstract suspend fun [addProxy](add-proxy.md)(@Path(value = &quot;consumerId&quot;)consumerId: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), @Path(value = &quot;paymentSourceProfileId&quot;)paymentSourceProfileID: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), @Bodypayload: [AddProxyRequest](../../eu.epicompany.mobile.sdk.network.model.proxy/-add-proxy-request/index.md)): [AddProxyResource](../../eu.epicompany.mobile.sdk.network.model.proxy/-add-proxy-resource/index.md)
