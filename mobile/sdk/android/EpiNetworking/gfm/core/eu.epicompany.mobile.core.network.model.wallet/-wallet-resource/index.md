//[core](../../../index.md)/[eu.epicompany.mobile.core.network.model.wallet](../index.md)/[WalletResource](index.md)

# WalletResource

[androidJvm]\
@Serializable

data class [WalletResource](index.md)(val id: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val walletName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val consumerId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), val host: [MobileHostResource](../-mobile-host-resource/index.md), val walletPublicKey: [JWK](../../eu.epicompany.mobile.core.domain.model.authentication/-j-w-k/index.md), val _links: [WalletResourceLinks](../-wallet-resource-links/index.md) = WalletResourceLinks(), val _embedded: [WalletResourceEmbeds](../-wallet-resource-embeds/index.md) = WalletResourceEmbeds()) : [HalResource](../../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [WalletResource](-wallet-resource.md) | [androidJvm]<br>constructor(id: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), walletName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), consumerId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), host: [MobileHostResource](../-mobile-host-resource/index.md), walletPublicKey: [JWK](../../eu.epicompany.mobile.core.domain.model.authentication/-j-w-k/index.md), _links: [WalletResourceLinks](../-wallet-resource-links/index.md) = WalletResourceLinks(), _embedded: [WalletResourceEmbeds](../-wallet-resource-embeds/index.md) = WalletResourceEmbeds()) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](_embedded.md) | [androidJvm]<br>open override val [_embedded](_embedded.md): [WalletResourceEmbeds](../-wallet-resource-embeds/index.md) |
| [_links](_links.md) | [androidJvm]<br>open override val [_links](_links.md): [WalletResourceLinks](../-wallet-resource-links/index.md) |
| [consumerId](consumer-id.md) | [androidJvm]<br>val [consumerId](consumer-id.md): [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556) |
| [host](host.md) | [androidJvm]<br>val [host](host.md): [MobileHostResource](../-mobile-host-resource/index.md) |
| [id](id.md) | [androidJvm]<br>val [id](id.md): [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556) |
| [walletName](wallet-name.md) | [androidJvm]<br>val [walletName](wallet-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [walletPublicKey](wallet-public-key.md) | [androidJvm]<br>val [walletPublicKey](wallet-public-key.md): [JWK](../../eu.epicompany.mobile.core.domain.model.authentication/-j-w-k/index.md) |
