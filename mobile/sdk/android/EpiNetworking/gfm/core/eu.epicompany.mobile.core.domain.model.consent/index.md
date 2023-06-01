//[core](../../index.md)/[eu.epicompany.mobile.core.domain.model.consent](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [Modification](-modification/index.md) | [androidJvm]<br>@Serializable<br>data class [Modification](-modification/index.md)(val cycleIndexes: [IntRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-int-range/index.html), val constraint: [PaymentConstraint](-payment-constraint/index.md)) |
| [PaymentConstraint](-payment-constraint/index.md) | [androidJvm]<br>@Serializable<br>sealed class [PaymentConstraint](-payment-constraint/index.md) |
| [PaymentRules](-payment-rules/index.md) | [androidJvm]<br>@Serializable<br>@[JvmInline](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-inline/index.html)<br>value class [PaymentRules](-payment-rules/index.md)(val windowDefinitions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[WindowDefinition](-window-definition/index.md)&gt;) : [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[WindowDefinition](-window-definition/index.md)&gt; |
| [Repetition](-repetition/index.md) | [androidJvm]<br>enum [Repetition](-repetition/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[Repetition](-repetition/index.md)&gt; |
| [WindowDefinition](-window-definition/index.md) | [androidJvm]<br>@Serializable<br>sealed class [WindowDefinition](-window-definition/index.md) |

## Functions

| Name | Summary |
|---|---|
| [forOneOffPayment](for-one-off-payment.md) | [androidJvm]<br>fun &lt;Error class: unknown class&gt;.[forOneOffPayment](for-one-off-payment.md)(amount: [MoneyAmount](../eu.epicompany.mobile.core.domain.model/-money-amount/index.md)): [PaymentRules](-payment-rules/index.md) |
| [forRecurringPayments](for-recurring-payments.md) | [androidJvm]<br>fun &lt;Error class: unknown class&gt;.[forRecurringPayments](for-recurring-payments.md)(amount: [MoneyAmount](../eu.epicompany.mobile.core.domain.model/-money-amount/index.md), repetition: [Repetition](-repetition/index.md)): [PaymentRules](-payment-rules/index.md) |

## Properties

| Name | Summary |
|---|---|
| [oneOffPaymentWindowDuration](one-off-payment-window-duration.md) | [androidJvm]<br>val [oneOffPaymentWindowDuration](one-off-payment-window-duration.md): [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html)<br>A one-off payment defines this duration as allowed payment window. |
| [startToleranceDuration](start-tolerance-duration.md) | [androidJvm]<br>val [startToleranceDuration](start-tolerance-duration.md): [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html)<br>This duration is added as offset before the payment window to allow for short clock differences between clients and the epi backend. |
