//[core](../../../index.md)/[eu.epicompany.mobile.core.network.internal.retrofit.interceptors](../index.md)/[ErrorInterceptor](index.md)

# ErrorInterceptor

class [ErrorInterceptor](index.md)(networkErrorCallback: [NetworkErrorCallback](../../eu.epicompany.mobile.core.network.error/-network-error-callback/index.md), json: Json) : Interceptor

The error interceptor for handling the error responses.

#### Parameters

androidJvm

| | |
|---|---|
| networkErrorCallback | The network error callback. |
| json | The json serializer. |

## Constructors

| | |
|---|---|
| [ErrorInterceptor](-error-interceptor.md) | [androidJvm]<br>constructor(networkErrorCallback: [NetworkErrorCallback](../../eu.epicompany.mobile.core.network.error/-network-error-callback/index.md), json: Json) |

## Functions

| Name | Summary |
|---|---|
| [intercept](intercept.md) | [androidJvm]<br>open override fun [intercept](intercept.md)(chain: Interceptor.Chain): Response |
