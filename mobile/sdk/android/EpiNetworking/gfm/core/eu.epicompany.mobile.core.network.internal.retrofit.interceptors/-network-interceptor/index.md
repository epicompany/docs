//[core](../../../index.md)/[eu.epicompany.mobile.core.network.internal.retrofit.interceptors](../index.md)/[NetworkInterceptor](index.md)

# NetworkInterceptor

class [NetworkInterceptor](index.md)(accessTokenProvider: [AccessTokenProvider](../../eu.epicompany.mobile.core.network.authentication/-access-token-provider/index.md)) : Interceptor

The network interceptor for adding the authorization header.

#### Parameters

androidJvm

| | |
|---|---|
| accessTokenProvider | The access token provider. |

## Constructors

| | |
|---|---|
| [NetworkInterceptor](-network-interceptor.md) | [androidJvm]<br>constructor(accessTokenProvider: [AccessTokenProvider](../../eu.epicompany.mobile.core.network.authentication/-access-token-provider/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [intercept](intercept.md) | [androidJvm]<br>open override fun [intercept](intercept.md)(chain: Interceptor.Chain): Response |
