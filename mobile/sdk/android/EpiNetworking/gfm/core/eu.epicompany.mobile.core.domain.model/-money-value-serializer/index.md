//[core](../../../index.md)/[eu.epicompany.mobile.core.domain.model](../index.md)/[MoneyValueSerializer](index.md)

# MoneyValueSerializer

[androidJvm]\
@Serializer(forClass = [MoneyAmount::class](../-money-amount/index.md))

object [MoneyValueSerializer](index.md) : JsonContentPolymorphicSerializer&lt;[MoneyAmount](../-money-amount/index.md)&gt; 

MoneyValueSerializer serializes MoneyAmounts with a single property containing the numerical value of the amount with the property name corresponding to the property of the concrete MoneyValue type. e.g.: 10 EUR is represented as: { &quot;euroCents&quot;: 1000 }

This format is intended to be used in the api.

## Functions

| Name | Summary |
|---|---|
| [deserialize](index.md#73238086%2FFunctions%2F-1060529556) | [androidJvm]<br>override fun [deserialize](index.md#73238086%2FFunctions%2F-1060529556)(decoder: Decoder): [MoneyAmount](../-money-amount/index.md) |
| [serialize](index.md#-1341933355%2FFunctions%2F-1060529556) | [androidJvm]<br>override fun [serialize](index.md#-1341933355%2FFunctions%2F-1060529556)(encoder: Encoder, value: [MoneyAmount](../-money-amount/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [descriptor](index.md#2129062728%2FProperties%2F-1060529556) | [androidJvm]<br>open override val [descriptor](index.md#2129062728%2FProperties%2F-1060529556): SerialDescriptor |
