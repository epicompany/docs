//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.serialization](../index.md)/[DurationSerializer](index.md)

# DurationSerializer

[androidJvm]\
@Serializer(forClass = [Duration::class](https://developer.android.com/reference/kotlin/java/time/Duration.html))

object [DurationSerializer](index.md) : KSerializer&lt;[Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html)&gt;

## Functions

| Name | Summary |
|---|---|
| [deserialize](deserialize.md) | [androidJvm]<br>open override fun [deserialize](deserialize.md)(decoder: Decoder): [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html) |
| [serialize](serialize.md) | [androidJvm]<br>open override fun [serialize](serialize.md)(encoder: Encoder, value: [Duration](https://developer.android.com/reference/kotlin/java/time/Duration.html)) |

## Properties

| Name | Summary |
|---|---|
| [descriptor](descriptor.md) | [androidJvm]<br>open override val [descriptor](descriptor.md): SerialDescriptor |
