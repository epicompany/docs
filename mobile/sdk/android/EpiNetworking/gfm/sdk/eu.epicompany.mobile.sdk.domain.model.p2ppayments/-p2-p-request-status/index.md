//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.domain.model.p2ppayments](../index.md)/[P2PRequestStatus](index.md)

# P2PRequestStatus

@Serializable

sealed class [P2PRequestStatus](index.md)

#### Inheritors

| |
|---|
| [Pending](-pending/index.md) |
| [Rejected](-rejected/index.md) |
| [Approved](-approved/index.md) |
| [Canceled](-canceled/index.md) |

## Types

| Name | Summary |
|---|---|
| [Approved](-approved/index.md) | [androidJvm]<br>@Serializable<br>object [Approved](-approved/index.md) : [P2PRequestStatus](index.md)<br>Payer has accepted to pay the P2P Request nd the corresponding p2p-payment is Accepted by the consumer-psp. |
| [Canceled](-canceled/index.md) | [androidJvm]<br>@Serializable<br>object [Canceled](-canceled/index.md) : [P2PRequestStatus](index.md)<br>Payee has canceled the P2P Request |
| [Pending](-pending/index.md) | [androidJvm]<br>@Serializable<br>object [Pending](-pending/index.md) : [P2PRequestStatus](index.md)<br>P2P Request initial status. |
| [Rejected](-rejected/index.md) | [androidJvm]<br>@Serializable<br>object [Rejected](-rejected/index.md) : [P2PRequestStatus](index.md)<br>Payer has rejected the P2P Request |
