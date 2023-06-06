//[core](../../../index.md)/[eu.epicompany.mobile.core.network.internal.retrofit](../index.md)/[RetrofitPaymentSourceProfileNetworkApi](index.md)/[addProxy](add-proxy.md)

# addProxy

[androidJvm]\

@POST(value = &quot;/api/consumers/{consumerId}/payment-source-profiles/{paymentSourceProfileId}/proxies&quot;)

abstract fun [addProxy](add-proxy.md)(@Path(value = &quot;consumerId&quot;)consumerId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), @Path(value = &quot;paymentSourceProfileId&quot;)paymentSourceProfileID: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), @Bodypayload: [AddProxyRequest](../../eu.epicompany.mobile.core.network.model.proxy/-add-proxy-request/index.md)): Call&lt;[AddProxyResource](../../eu.epicompany.mobile.core.network.model.proxy/-add-proxy-resource/index.md)&gt;
