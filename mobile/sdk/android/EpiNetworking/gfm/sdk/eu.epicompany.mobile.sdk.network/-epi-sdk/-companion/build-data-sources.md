//[sdk](../../../../index.md)/[eu.epicompany.mobile.sdk.network](../../index.md)/[EpiSdk](../index.md)/[Companion](index.md)/[buildDataSources](build-data-sources.md)

# buildDataSources

[androidJvm]\
fun [buildDataSources](build-data-sources.md)(baseUrl: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), accessTokenProvider: [AccessTokenProvider](../../../eu.epicompany.mobile.sdk.network.authentication/-access-token-provider/index.md), networkErrorCallback: [NetworkErrorCallback](../../../eu.epicompany.mobile.sdk.network.error/-network-error-callback/index.md), isDebug: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false): [EpiDataSource](../../../eu.epicompany.mobile.sdk.network.api/-epi-data-source/index.md)

Builds and configures an instance of [EpiDataSource](../../../eu.epicompany.mobile.sdk.network.api/-epi-data-source/index.md) with the given parameters.

#### Return

The created instance of [EpiDataSource](../../../eu.epicompany.mobile.sdk.network.api/-epi-data-source/index.md).

#### Parameters

androidJvm

| | |
|---|---|
| baseUrl | The base URL of the API. |
| accessTokenProvider | The access token provider. |
| networkErrorCallback | The network error callback. |
| isDebug | Whether the SDK is in debug mode. |
