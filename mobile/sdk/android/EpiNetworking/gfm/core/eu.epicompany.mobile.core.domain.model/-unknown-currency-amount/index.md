//[core](../../../index.md)/[eu.epicompany.mobile.core.domain.model](../index.md)/[UnknownCurrencyAmount](index.md)

# UnknownCurrencyAmount

[androidJvm]\
@Serializable

object [UnknownCurrencyAmount](index.md) : [MoneyAmount](../-money-amount/index.md)

## Functions

| Name | Summary |
|---|---|
| [compareTo](compare-to.md) | [androidJvm]<br>open operator override fun [compareTo](compare-to.md)(other: [MoneyAmount](../-money-amount/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isPositive](../-money-amount/is-positive.md) | [androidJvm]<br>fun [isPositive](../-money-amount/is-positive.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isZeroAmount](../-money-amount/is-zero-amount.md) | [androidJvm]<br>fun [isZeroAmount](../-money-amount/is-zero-amount.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [minus](minus.md) | [androidJvm]<br>open operator override fun [minus](minus.md)(other: [MoneyAmount](../-money-amount/index.md)): [MoneyAmount](../-money-amount/index.md) |
| [plus](plus.md) | [androidJvm]<br>open operator override fun [plus](plus.md)(other: [MoneyAmount](../-money-amount/index.md)): [MoneyAmount](../-money-amount/index.md) |
| [toDisplayableAmount](../to-displayable-amount.md) | [androidJvm]<br>fun [MoneyAmount](../-money-amount/index.md).[toDisplayableAmount](../to-displayable-amount.md)(locale: [Locale](https://developer.android.com/reference/kotlin/java/util/Locale.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [unaryMinus](unary-minus.md) | [androidJvm]<br>open operator override fun [unaryMinus](unary-minus.md)(): [MoneyAmount](../-money-amount/index.md) |
| [zeroAmount](zero-amount.md) | [androidJvm]<br>open override fun [zeroAmount](zero-amount.md)(): [MoneyAmount](../-money-amount/index.md) |

## Properties

| Name | Summary |
|---|---|
| [amount](../amount.md) | [androidJvm]<br>val [MoneyAmount](../-money-amount/index.md).[amount](../amount.md): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
