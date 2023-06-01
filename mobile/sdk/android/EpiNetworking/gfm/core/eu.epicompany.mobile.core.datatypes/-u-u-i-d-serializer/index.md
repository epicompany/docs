//[core](../../../index.md)/[eu.epicompany.mobile.core.datatypes](../index.md)/[UUIDSerializer](index.md)

# UUIDSerializer

[androidJvm]\
@Serializer(forClass = [UUID::class](https://developer.android.com/reference/kotlin/java/util/UUID.html))

object [UUIDSerializer](index.md) : KSerializer&lt;[UUID](https://developer.android.com/reference/kotlin/java/util/UUID.html)&gt;

## Functions

| Name | Summary |
|---|---|
| [deserialize](deserialize.md) | [androidJvm]<br>open override fun [deserialize](deserialize.md)(decoder: Decoder): [UUID](https://developer.android.com/reference/kotlin/java/util/UUID.html) |
| [serialize](serialize.md) | [androidJvm]<br>open override fun [serialize](serialize.md)(encoder: Encoder, value: [UUID](https://developer.android.com/reference/kotlin/java/util/UUID.html)) |

## Properties

| Name | Summary |
|---|---|
| [descriptor](descriptor.md) | [androidJvm]<br>open override val [descriptor](descriptor.md): SerialDescriptor |
