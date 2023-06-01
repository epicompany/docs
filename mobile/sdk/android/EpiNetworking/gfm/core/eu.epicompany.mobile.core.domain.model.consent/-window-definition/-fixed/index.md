//[core](../../../../index.md)/[eu.epicompany.mobile.core.domain.model.consent](../../index.md)/[WindowDefinition](../index.md)/[Fixed](index.md)

# Fixed

[androidJvm]\
@Serializable

data class [Fixed](index.md)(val constraint: [PaymentConstraint](../../-payment-constraint/index.md), val startOffset: [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html), val windowDuration: [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html)) : [WindowDefinition](../index.md)

## Constructors

| | |
|---|---|
| [Fixed](-fixed.md) | [androidJvm]<br>constructor(constraint: [PaymentConstraint](../../-payment-constraint/index.md), startOffset: [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html), windowDuration: [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html)) |

## Properties

| Name | Summary |
|---|---|
| [constraint](constraint.md) | [androidJvm]<br>open override val [constraint](constraint.md): [PaymentConstraint](../../-payment-constraint/index.md) |
| [startOffset](start-offset.md) | [androidJvm]<br>val [startOffset](start-offset.md): [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html) |
| [windowDuration](window-duration.md) | [androidJvm]<br>val [windowDuration](window-duration.md): [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html) |
