//[core](../../index.md)/[eu.epicompany.mobile.core.datatypes](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [IBAN](-i-b-a-n/index.md) | [androidJvm]<br>@Serializable<br>@[JvmInline](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-inline/index.html)<br>value class [IBAN](-i-b-a-n/index.md)(val iban: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [UUID4](index.md#545543244%2FClasslikes%2F-1060529556) | [androidJvm]<br>typealias [UUID4](index.md#545543244%2FClasslikes%2F-1060529556) = @Serializable(with = [UUIDSerializer::class](-u-u-i-d-serializer/index.md))[UUID](https://developer.android.com/reference/kotlin/java/util/UUID.html)<br>Use this typealias for serializable classes.<br>Provided for convenience so that not every type needs to have the proper `@Serializable(...)` annotation.<br>The java.util.UUID is not serializable by default by the KotlinX Serialization package, so in order to use the UUID type at the REST API level declaring a custom serializer type is required. |
| [UUIDSerializer](-u-u-i-d-serializer/index.md) | [androidJvm]<br>@Serializer(forClass = [UUID::class](https://developer.android.com/reference/kotlin/java/util/UUID.html))<br>object [UUIDSerializer](-u-u-i-d-serializer/index.md) : KSerializer&lt;[UUID](https://developer.android.com/reference/kotlin/java/util/UUID.html)&gt; |

## Functions

| Name | Summary |
|---|---|
| [UUID4](-u-u-i-d4.md) | [androidJvm]<br>fun [UUID4](-u-u-i-d4.md)(): [UUID4](index.md#545543244%2FClasslikes%2F-1060529556) |

## Properties

| Name | Summary |
|---|---|
| [ibanReplacement](iban-replacement.md) | [androidJvm]<br>const val [ibanReplacement](iban-replacement.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
