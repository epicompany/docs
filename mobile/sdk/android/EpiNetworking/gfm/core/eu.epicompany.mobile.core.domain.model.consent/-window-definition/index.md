//[core](../../../index.md)/[eu.epicompany.mobile.core.domain.model.consent](../index.md)/[WindowDefinition](index.md)

# WindowDefinition

@Serializable

sealed class [WindowDefinition](index.md)

#### Inheritors

| |
|---|
| [Fixed](-fixed/index.md) |
| [Cyclic](-cyclic/index.md) |
| [Sliding](-sliding/index.md) |

## Types

| Name | Summary |
|---|---|
| [Cyclic](-cyclic/index.md) | [androidJvm]<br>@Serializable<br>data class [Cyclic](-cyclic/index.md)(val constraint: [PaymentConstraint](../-payment-constraint/index.md), val startOffset: [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html), val windowDuration: [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html), val repetition: [Repetition](../-repetition/index.md), val modifications: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Modification](../-modification/index.md)&gt; = emptyList()) : [WindowDefinition](index.md) |
| [Fixed](-fixed/index.md) | [androidJvm]<br>@Serializable<br>data class [Fixed](-fixed/index.md)(val constraint: [PaymentConstraint](../-payment-constraint/index.md), val startOffset: [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html), val windowDuration: [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html)) : [WindowDefinition](index.md) |
| [Sliding](-sliding/index.md) | [androidJvm]<br>@Serializable<br>data class [Sliding](-sliding/index.md)(val constraint: [PaymentConstraint](../-payment-constraint/index.md), val duration: [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html)) : [WindowDefinition](index.md) |

## Properties

| Name | Summary |
|---|---|
| [constraint](constraint.md) | [androidJvm]<br>abstract val [constraint](constraint.md): [PaymentConstraint](../-payment-constraint/index.md) |
