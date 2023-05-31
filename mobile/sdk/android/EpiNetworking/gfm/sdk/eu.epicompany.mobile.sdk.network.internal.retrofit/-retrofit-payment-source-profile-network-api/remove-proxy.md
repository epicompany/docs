//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.internal.retrofit](../index.md)/[RetrofitPaymentSourceProfileNetworkApi](index.md)/[removeProxy](remove-proxy.md)

# removeProxy

[androidJvm]\

@DELETE(value = &quot;/api/consumers/{consumerId}/payment-source-profiles/{paymentSourceProfileId}/proxies/{proxyId}&quot;)

abstract suspend fun [removeProxy](remove-proxy.md)(@Path(value = &quot;consumerId&quot;)consumerId: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), @Path(value = &quot;paymentSourceProfileId&quot;)paymentSourceProfileID: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), @Path(value = &quot;proxyId&quot;)proxyId: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411)): Response&lt;[Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)&gt;
