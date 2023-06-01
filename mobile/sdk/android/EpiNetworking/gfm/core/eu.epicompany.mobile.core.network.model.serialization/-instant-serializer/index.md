//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.serialization](../index.md)/[InstantSerializer](index.md)

# InstantSerializer

[androidJvm]\
@Serializer(forClass = [Instant::class](https://developer.android.com/reference/kotlin/java/time/Instant.html))

object [InstantSerializer](index.md) : KSerializer&lt;[Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html)&gt;

## Functions

| Name | Summary |
|---|---|
| [deserialize](deserialize.md) | [androidJvm]<br>open override fun [deserialize](deserialize.md)(decoder: Decoder): [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html) |
| [serialize](serialize.md) | [androidJvm]<br>open override fun [serialize](serialize.md)(encoder: Encoder, value: [Instant](https://developer.android.com/reference/kotlin/java/time/Instant.html)) |

## Properties

| Name | Summary |
|---|---|
| [descriptor](descriptor.md) | [androidJvm]<br>open override val [descriptor](descriptor.md): SerialDescriptor |
