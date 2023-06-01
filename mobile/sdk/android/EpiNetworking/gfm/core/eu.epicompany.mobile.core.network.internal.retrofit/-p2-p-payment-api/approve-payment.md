//[core](../../../index.md)/[eu.epicompany.mobile.core.network.internal.retrofit](../index.md)/[P2PPaymentApi](index.md)/[approvePayment](approve-payment.md)

# approvePayment

[androidJvm]\

@PUT(value = &quot;/api/p2p-payments/{paymentId}/approval&quot;)

abstract suspend fun [approvePayment](approve-payment.md)(@Path(value = &quot;paymentId&quot;)paymentId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), @Bodyrequest: [P2PConsentApprovalRequest](../../eu.epicompany.mobile.core.network.model.p2ppayment/-p2-p-consent-approval-request/index.md)): Response&lt;[Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)&gt;
