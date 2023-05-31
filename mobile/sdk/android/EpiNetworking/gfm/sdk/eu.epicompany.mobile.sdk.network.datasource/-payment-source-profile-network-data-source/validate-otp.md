//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.datasource](../index.md)/[PaymentSourceProfileNetworkDataSource](index.md)/[validateOtp](validate-otp.md)

# validateOtp

[androidJvm]\
abstract suspend fun [validateOtp](validate-otp.md)(url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), otp: [ProxyOtpPayload](../../eu.epicompany.mobile.sdk.network.model.proxy/-proxy-otp-payload/index.md)): Response&lt;[ContactItemResource](../../eu.epicompany.mobile.sdk.network.internal.retrofit/index.md#-1834010870%2FClasslikes%2F462465411)&gt;

Validates a proxy OTP (One-Time Password) at the specified URL

#### Return

The contact item resource.

#### Parameters

androidJvm

| | |
|---|---|
| url | The URL where OTP validation is sent. |
| otp | The OTP payload to validate. |
