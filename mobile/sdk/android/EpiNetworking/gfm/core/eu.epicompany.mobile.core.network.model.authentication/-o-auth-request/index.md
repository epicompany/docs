//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.authentication](../index.md)/[OAuthRequest](index.md)

# OAuthRequest

[androidJvm]\
@Serializable

data class [OAuthRequest](index.md)(val grantType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;urn:ietf:params:oauth:grant-type:jwt-bearer&quot;, val assertion: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val scope: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;wallet:provisioning p2p:transferMoney&quot;)

The OAuth request.

## Constructors

| | |
|---|---|
| [OAuthRequest](-o-auth-request.md) | [androidJvm]<br>constructor(grantType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;urn:ietf:params:oauth:grant-type:jwt-bearer&quot;, assertion: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), scope: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;wallet:provisioning p2p:transferMoney&quot;) |

## Properties

| Name | Summary |
|---|---|
| [assertion](assertion.md) | [androidJvm]<br>val [assertion](assertion.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [grantType](grant-type.md) | [androidJvm]<br>val [grantType](grant-type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [scope](scope.md) | [androidJvm]<br>val [scope](scope.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
