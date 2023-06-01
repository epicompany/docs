//[core](../../../index.md)/[eu.epicompany.mobile.core.network.datasource](../index.md)/[P2PPaymentNetworkDataSource](index.md)/[approveIncomingRequest](approve-incoming-request.md)

# approveIncomingRequest

[androidJvm]\
abstract suspend fun [approveIncomingRequest](approve-incoming-request.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), request: [CreateP2PIncomingRequestRequest](../../eu.epicompany.mobile.core.network.model.p2ppayment/-create-p2-p-incoming-request-request/index.md)): [P2PRequestResource](../../eu.epicompany.mobile.core.network.model.p2ppayment/-p2-p-request-resource/index.md)

Approves an incoming P2P (Person-to-Person) request.

#### Return

The P2P request resource.

#### Parameters

androidJvm

| | |
|---|---|
| id | The P2P request ID. |
| request | The request. |
