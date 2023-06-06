//[core](../../../index.md)/[eu.epicompany.mobile.core.network.datasource](../index.md)/[PaymentSourceProfileNetworkDataSource](index.md)/[validateOtp](validate-otp.md)

# validateOtp

[androidJvm]\
abstract fun [validateOtp](validate-otp.md)(url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), otp: [ProxyOtpPayload](../../eu.epicompany.mobile.core.network.model.proxy/-proxy-otp-payload/index.md)): [ContactItemResource](../../eu.epicompany.mobile.core.network.internal.retrofit/index.md#-1206844945%2FClasslikes%2F-1060529556)

Validates a proxy OTP (One-Time Password) at the specified URL

#### Return

The contact item resource.

#### Parameters

androidJvm

| | |
|---|---|
| url | The URL where OTP validation is sent. |
| otp | The OTP payload to validate. |
