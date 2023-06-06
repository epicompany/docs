//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.serialization](../index.md)/[LocalDateSerializer](index.md)

# LocalDateSerializer

[androidJvm]\
@Serializer(forClass = [LocalDate::class](https://developer.android.com/reference/kotlin/java/time/LocalDate.html))

object [LocalDateSerializer](index.md) : KSerializer&lt;[LocalDate](https://developer.android.com/reference/kotlin/java/time/LocalDate.html)&gt;

## Functions

| Name | Summary |
|---|---|
| [deserialize](deserialize.md) | [androidJvm]<br>open override fun [deserialize](deserialize.md)(decoder: Decoder): [LocalDate](https://developer.android.com/reference/kotlin/java/time/LocalDate.html) |
| [serialize](serialize.md) | [androidJvm]<br>open override fun [serialize](serialize.md)(encoder: Encoder, value: [LocalDate](https://developer.android.com/reference/kotlin/java/time/LocalDate.html)) |

## Properties

| Name | Summary |
|---|---|
| [descriptor](descriptor.md) | [androidJvm]<br>open override val [descriptor](descriptor.md): SerialDescriptor |
