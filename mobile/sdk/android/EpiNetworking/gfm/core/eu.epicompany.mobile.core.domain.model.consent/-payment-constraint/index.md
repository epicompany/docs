//[core](../../../index.md)/[eu.epicompany.mobile.core.domain.model.consent](../index.md)/[PaymentConstraint](index.md)

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
| [Multiple](-multiple/index.md) | [androidJvm]<br>@Serializable<br>data class [Multiple](-multiple/index.md)(val maxAmount: [MoneyAmount](../../eu.epicompany.mobile.core.domain.model/-money-amount/index.md)) : [PaymentConstraint](index.md) |
| [Single](-single/index.md) | [androidJvm]<br>@Serializable<br>data class [Single](-single/index.md)(val maxAmount: [MoneyAmount](../../eu.epicompany.mobile.core.domain.model/-money-amount/index.md)) : [PaymentConstraint](index.md) |
