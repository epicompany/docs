//[sdk](../../index.md)/[eu.epicompany.mobile.sdk.domain.model](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [EuroAmount](-euro-amount/index.md) | [androidJvm]<br>@Serializable<br>data class [EuroAmount](-euro-amount/index.md)(val euroCents: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) : [MoneyAmount](-money-amount/index.md) |
| [MoneyAmount](-money-amount/index.md) | [androidJvm]<br>@Serializable(with = [MoneyValueSerializer::class](-money-value-serializer/index.md))<br>sealed class [MoneyAmount](-money-amount/index.md) |
| [MoneyValueSerializer](-money-value-serializer/index.md) | [androidJvm]<br>@Serializer(forClass = [MoneyAmount::class](-money-amount/index.md))<br>object [MoneyValueSerializer](-money-value-serializer/index.md) : JsonContentPolymorphicSerializer&lt;[MoneyAmount](-money-amount/index.md)&gt; <br>MoneyValueSerializer serializes MoneyAmounts with a single property containing the numerical value of the amount with the property name corresponding to the property of the concrete MoneyValue type. e.g.: 10 EUR is represented as: { &quot;euroCents&quot;: 1000 } |
| [UnknownCurrencyAmount](-unknown-currency-amount/index.md) | [androidJvm]<br>@Serializable<br>object [UnknownCurrencyAmount](-unknown-currency-amount/index.md) : [MoneyAmount](-money-amount/index.md) |
| [ZlotyAmount](-zloty-amount/index.md) | [androidJvm]<br>@Serializable<br>data class [ZlotyAmount](-zloty-amount/index.md)(val grosz: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) : [MoneyAmount](-money-amount/index.md) |

## Functions

| Name | Summary |
|---|---|
| [filterInvalidAmountCharacters](filter-invalid-amount-characters.md) | [androidJvm]<br>fun [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html).[filterInvalidAmountCharacters](filter-invalid-amount-characters.md)(decimalSeparator: [Char](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char/index.html) = &quot;.&quot;.single()): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [formatCurrencyAmount](format-currency-amount.md) | [androidJvm]<br>fun [formatCurrencyAmount](format-currency-amount.md)(amountString: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), numberOfDecimals: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), currency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), symbols: [DecimalFormatSymbols](https://developer.android.com/reference/kotlin/java/text/DecimalFormatSymbols.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [toCurrencyAmount](to-currency-amount.md) | [androidJvm]<br>fun [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html).[toCurrencyAmount](to-currency-amount.md)(currency: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), locale: [Locale](https://developer.android.com/reference/kotlin/java/util/Locale.html) = Locale.getDefault(FORMAT)): [MoneyAmount](-money-amount/index.md) |
| [toDisplayableAmount](to-displayable-amount.md) | [androidJvm]<br>fun [MoneyAmount](-money-amount/index.md).[toDisplayableAmount](to-displayable-amount.md)(locale: [Locale](https://developer.android.com/reference/kotlin/java/util/Locale.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

## Properties

| Name | Summary |
|---|---|
| [amount](amount.md) | [androidJvm]<br>val [MoneyAmount](-money-amount/index.md).[amount](amount.md): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
