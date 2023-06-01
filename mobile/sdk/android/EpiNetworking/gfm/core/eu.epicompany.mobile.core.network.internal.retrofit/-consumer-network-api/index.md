//[core](../../../index.md)/[eu.epicompany.mobile.core.network.internal.retrofit](../index.md)/[ConsumerNetworkApi](index.md)

# ConsumerNetworkApi

[androidJvm]\
interface [ConsumerNetworkApi](index.md)

## Functions

| Name | Summary |
|---|---|
| [consumer](consumer.md) | [androidJvm]<br>@GET(value = &quot;/api/consumers/{id}&quot;)<br>abstract suspend fun [consumer](consumer.md)(@Path(value = &quot;id&quot;)id: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556)): [ConsumerResource](../-consumer-resource/index.md) |
| [paymentSourceProfiles](payment-source-profiles.md) | [androidJvm]<br>@GET<br>abstract suspend fun [paymentSourceProfiles](payment-source-profiles.md)(@Urlurl: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
