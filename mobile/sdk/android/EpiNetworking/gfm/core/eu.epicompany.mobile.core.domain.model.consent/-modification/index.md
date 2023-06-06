//[core](../../../index.md)/[eu.epicompany.mobile.core.domain.model.consent](../index.md)/[Modification](index.md)

# Modification

[androidJvm]\
@Serializable

data class [Modification](index.md)(val cycleIndexes: [IntRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-int-range/index.html), val constraint: [PaymentConstraint](../-payment-constraint/index.md))

A modification of a cyclic payment window, it replaces one or more cylces definitions.

Allows to model subscriptions that e.g. start with a free trial period, or have reduced price at the beginning.

## Constructors

| | |
|---|---|
| [Modification](-modification.md) | [androidJvm]<br>constructor(cycleIndexes: [IntRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-int-range/index.html), constraint: [PaymentConstraint](../-payment-constraint/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [constraint](constraint.md) | [androidJvm]<br>val [constraint](constraint.md): [PaymentConstraint](../-payment-constraint/index.md)<br>The new constraint that holds for the given `cycleIndexes`. |
| [cycleIndexes](cycle-indexes.md) | [androidJvm]<br>val [cycleIndexes](cycle-indexes.md): [IntRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-int-range/index.html)<br>The index of the cycle that is modified/replaced. |
