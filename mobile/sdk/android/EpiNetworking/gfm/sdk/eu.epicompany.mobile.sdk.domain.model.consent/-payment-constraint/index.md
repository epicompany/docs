//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.domain.model.consent](../index.md)/[PaymentConstraint](index.md)

# PaymentConstraint

@Serializable

sealed class [PaymentConstraint](index.md)

#### Inheritors

| |
|---|
| [Single](-single/index.md) |
| [Multiple](-multiple/index.md) |

## Types

| Name | Summary |
|---|---|
| [Multiple](-multiple/index.md) | [androidJvm]<br>@Serializable<br>data class [Multiple](-multiple/index.md)(val maxAmount: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) : [PaymentConstraint](index.md) |
| [Single](-single/index.md) | [androidJvm]<br>@Serializable<br>data class [Single](-single/index.md)(val maxAmount: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) : [PaymentConstraint](index.md) |
