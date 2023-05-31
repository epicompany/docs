//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.domain.model](../index.md)/[ZlotyAmount](index.md)

# ZlotyAmount

[androidJvm]\
@Serializable

data class [ZlotyAmount](index.md)(val grosz: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) : [MoneyAmount](../-money-amount/index.md)

## Constructors

| | |
|---|---|
| [ZlotyAmount](-zloty-amount.md) | [androidJvm]<br>constructor(grosz: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [compareTo](compare-to.md) | [androidJvm]<br>open operator override fun [compareTo](compare-to.md)(other: [MoneyAmount](../-money-amount/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isPositive](../-money-amount/is-positive.md) | [androidJvm]<br>fun [isPositive](../-money-amount/is-positive.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isZeroAmount](../-money-amount/is-zero-amount.md) | [androidJvm]<br>fun [isZeroAmount](../-money-amount/is-zero-amount.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [minus](minus.md) | [androidJvm]<br>open operator override fun [minus](minus.md)(other: [MoneyAmount](../-money-amount/index.md)): [ZlotyAmount](index.md) |
| [plus](plus.md) | [androidJvm]<br>open operator override fun [plus](plus.md)(other: [MoneyAmount](../-money-amount/index.md)): [ZlotyAmount](index.md) |
| [toDisplayableAmount](../to-displayable-amount.md) | [androidJvm]<br>fun [MoneyAmount](../-money-amount/index.md).[toDisplayableAmount](../to-displayable-amount.md)(locale: [Locale](https://developer.android.com/reference/kotlin/java/util/Locale.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [unaryMinus](unary-minus.md) | [androidJvm]<br>open operator override fun [unaryMinus](unary-minus.md)(): [ZlotyAmount](index.md) |
| [zeroAmount](zero-amount.md) | [androidJvm]<br>open override fun [zeroAmount](zero-amount.md)(): [MoneyAmount](../-money-amount/index.md) |

## Properties

| Name | Summary |
|---|---|
| [amount](../amount.md) | [androidJvm]<br>val [MoneyAmount](../-money-amount/index.md).[amount](../amount.md): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [grosz](grosz.md) | [androidJvm]<br>val [grosz](grosz.md): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
