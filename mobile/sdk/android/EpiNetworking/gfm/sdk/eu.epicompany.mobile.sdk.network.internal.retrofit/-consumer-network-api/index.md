//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.internal.retrofit](../index.md)/[ConsumerNetworkApi](index.md)

# ConsumerNetworkApi

[androidJvm]\
interface [ConsumerNetworkApi](index.md)

## Functions

| Name | Summary |
|---|---|
| [consumer](consumer.md) | [androidJvm]<br>@GET(value = &quot;/api/consumers/{id}&quot;)<br>abstract suspend fun [consumer](consumer.md)(@Path(value = &quot;id&quot;)id: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411)): [ConsumerResource](../-consumer-resource/index.md) |
| [paymentSourceProfiles](payment-source-profiles.md) | [androidJvm]<br>@GET<br>abstract suspend fun [paymentSourceProfiles](payment-source-profiles.md)(@Urlurl: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
