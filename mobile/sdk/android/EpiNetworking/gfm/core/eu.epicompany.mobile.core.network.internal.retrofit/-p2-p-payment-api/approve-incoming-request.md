//[core](../../../index.md)/[eu.epicompany.mobile.core.network.internal.retrofit](../index.md)/[P2PPaymentApi](index.md)/[approveIncomingRequest](approve-incoming-request.md)

# approveIncomingRequest

[androidJvm]\

@POST(value = &quot;/api/p2p-requests/{id}/approval&quot;)

abstract fun [approveIncomingRequest](approve-incoming-request.md)(@Path(value = &quot;id&quot;)id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), @Bodyrequest: [CreateP2PIncomingRequestRequest](../../eu.epicompany.mobile.core.network.model.p2ppayment/-create-p2-p-incoming-request-request/index.md)): Call&lt;[P2PRequestResource](../../eu.epicompany.mobile.core.network.model.p2ppayment/-p2-p-request-resource/index.md)&gt;
