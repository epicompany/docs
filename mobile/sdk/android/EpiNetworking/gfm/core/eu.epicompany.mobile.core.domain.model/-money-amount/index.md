//[core](../../../index.md)/[eu.epicompany.mobile.core.domain.model](../index.md)/[MoneyAmount](index.md)

# MoneyAmount

@Serializable(with = [MoneyValueSerializer::class](../-money-value-serializer/index.md))

sealed class [MoneyAmount](index.md)

#### Inheritors

| |
|---|
| [EuroAmount](../-euro-amount/index.md) |
| [ZlotyAmount](../-zloty-amount/index.md) |
| [UnknownCurrencyAmount](../-unknown-currency-amount/index.md) |

## Functions

| Name | Summary |
|---|---|
| [compareTo](compare-to.md) | [androidJvm]<br>abstract operator fun [compareTo](compare-to.md)(other: [MoneyAmount](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isPositive](is-positive.md) | [androidJvm]<br>fun [isPositive](is-positive.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isZeroAmount](is-zero-amount.md) | [androidJvm]<br>fun [isZeroAmount](is-zero-amount.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [minus](minus.md) | [androidJvm]<br>abstract operator fun [minus](minus.md)(other: [MoneyAmount](index.md)): [MoneyAmount](index.md) |
| [plus](plus.md) | [androidJvm]<br>abstract operator fun [plus](plus.md)(other: [MoneyAmount](index.md)): [MoneyAmount](index.md) |
| [toDisplayableAmount](../to-displayable-amount.md) | [androidJvm]<br>fun [MoneyAmount](index.md).[toDisplayableAmount](../to-displayable-amount.md)(locale: [Locale](https://developer.android.com/reference/kotlin/java/util/Locale.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [unaryMinus](unary-minus.md) | [androidJvm]<br>abstract operator fun [unaryMinus](unary-minus.md)(): [MoneyAmount](index.md) |
| [zeroAmount](zero-amount.md) | [androidJvm]<br>abstract fun [zeroAmount](zero-amount.md)(): [MoneyAmount](index.md) |

## Properties

| Name | Summary |
|---|---|
| [amount](../amount.md) | [androidJvm]<br>val [MoneyAmount](index.md).[amount](../amount.md): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
