//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.wallet](../index.md)/[MobileHostResource](index.md)

# MobileHostResource

[androidJvm]\
@Serializable

data class [MobileHostResource](index.md)(val type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;Mobile&quot;, val device: [MobileHostResource.DeviceResource](-device-resource/index.md), val app: [MobileHostResource.AppResource](-app-resource/index.md))

## Constructors

| | |
|---|---|
| [MobileHostResource](-mobile-host-resource.md) | [androidJvm]<br>constructor(type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;Mobile&quot;, device: [MobileHostResource.DeviceResource](-device-resource/index.md), app: [MobileHostResource.AppResource](-app-resource/index.md)) |

## Types

| Name | Summary |
|---|---|
| [AppResource](-app-resource/index.md) | [androidJvm]<br>@Serializable<br>data class [AppResource](-app-resource/index.md)(val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [DeviceResource](-device-resource/index.md) | [androidJvm]<br>@Serializable<br>class [DeviceResource](-device-resource/index.md)(val id: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val model: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) |

## Properties

| Name | Summary |
|---|---|
| [app](app.md) | [androidJvm]<br>val [app](app.md): [MobileHostResource.AppResource](-app-resource/index.md) |
| [device](device.md) | [androidJvm]<br>val [device](device.md): [MobileHostResource.DeviceResource](-device-resource/index.md) |
| [type](type.md) | [androidJvm]<br>val [type](type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
