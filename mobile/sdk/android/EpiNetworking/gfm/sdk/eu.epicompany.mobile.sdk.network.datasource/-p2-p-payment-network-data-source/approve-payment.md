//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.datasource](../index.md)/[P2PPaymentNetworkDataSource](index.md)/[approvePayment](approve-payment.md)

# approvePayment

[androidJvm]\
abstract suspend fun [approvePayment](approve-payment.md)(paymentId: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), request: [P2PConsentApprovalRequest](../../eu.epicompany.mobile.sdk.network.model.p2ppayment/-p2-p-consent-approval-request/index.md)): Response&lt;[Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)&gt;

Approves a P2P (Person-to-Person) payment.

#### Return

The response.

#### Parameters

androidJvm

| | |
|---|---|
| paymentId | The payment ID. |
| request | The request. |
