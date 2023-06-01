//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.proxy](../index.md)/[ContactItemState](index.md)

# ContactItemState

sealed class [ContactItemState](index.md)

#### Inheritors

| |
|---|
| [Verified](-verified/index.md) |
| [Unverified](-unverified/index.md) |
| [AssignedToPaymentSource](-assigned-to-payment-source/index.md) |
| [InvalidState](-invalid-state/index.md) |

## Types

| Name | Summary |
|---|---|
| [AssignedToPaymentSource](-assigned-to-payment-source/index.md) | [androidJvm]<br>data class [AssignedToPaymentSource](-assigned-to-payment-source/index.md)(val linkedPaymentSourceID: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [ContactItemState](index.md) |
| [InvalidState](-invalid-state/index.md) | [androidJvm]<br>object [InvalidState](-invalid-state/index.md) : [ContactItemState](index.md) |
| [Unverified](-unverified/index.md) | [androidJvm]<br>data class [Unverified](-unverified/index.md)(val verification: [ContactItemVerification](../-contact-item-verification/index.md)) : [ContactItemState](index.md) |
| [Verified](-verified/index.md) | [androidJvm]<br>object [Verified](-verified/index.md) : [ContactItemState](index.md) |
