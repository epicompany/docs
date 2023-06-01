//[core](../../../../index.md)/[eu.epicompany.mobile.core.domain.model.consent](../../index.md)/[WindowDefinition](../index.md)/[Cyclic](index.md)

# Cyclic

[androidJvm]\
@Serializable

data class [Cyclic](index.md)(val constraint: [PaymentConstraint](../../-payment-constraint/index.md), val startOffset: [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html), val windowDuration: [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html), val repetition: [Repetition](../../-repetition/index.md), val modifications: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Modification](../../-modification/index.md)&gt; = emptyList()) : [WindowDefinition](../index.md)

## Constructors

| | |
|---|---|
| [Cyclic](-cyclic.md) | [androidJvm]<br>constructor(constraint: [PaymentConstraint](../../-payment-constraint/index.md), startOffset: [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html), windowDuration: [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html), repetition: [Repetition](../../-repetition/index.md), modifications: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Modification](../../-modification/index.md)&gt; = emptyList()) |

## Properties

| Name | Summary |
|---|---|
| [constraint](constraint.md) | [androidJvm]<br>open override val [constraint](constraint.md): [PaymentConstraint](../../-payment-constraint/index.md) |
| [modifications](modifications.md) | [androidJvm]<br>val [modifications](modifications.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Modification](../../-modification/index.md)&gt; |
| [repetition](repetition.md) | [androidJvm]<br>val [repetition](repetition.md): [Repetition](../../-repetition/index.md) |
| [startOffset](start-offset.md) | [androidJvm]<br>val [startOffset](start-offset.md): [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html) |
| [windowDuration](window-duration.md) | [androidJvm]<br>val [windowDuration](window-duration.md): [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html) |
