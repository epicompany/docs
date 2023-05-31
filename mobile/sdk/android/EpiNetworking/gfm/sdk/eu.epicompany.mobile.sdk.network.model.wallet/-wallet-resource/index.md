//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.model.wallet](../index.md)/[WalletResource](index.md)

# WalletResource

[androidJvm]\
@Serializable

data class [WalletResource](index.md)(val id: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), val walletName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val consumerId: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), val host: [MobileHostResource](../-mobile-host-resource/index.md), val walletPublicKey: [JWK](../../eu.epicompany.mobile.sdk.domain.model.authentication/-j-w-k/index.md), val _links: [WalletResourceLinks](../-wallet-resource-links/index.md) = WalletResourceLinks(), val _embedded: [WalletResourceEmbeds](../-wallet-resource-embeds/index.md) = WalletResourceEmbeds()) : [HalResource](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [WalletResource](-wallet-resource.md) | [androidJvm]<br>constructor(id: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), walletName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), consumerId: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), host: [MobileHostResource](../-mobile-host-resource/index.md), walletPublicKey: [JWK](../../eu.epicompany.mobile.sdk.domain.model.authentication/-j-w-k/index.md), _links: [WalletResourceLinks](../-wallet-resource-links/index.md) = WalletResourceLinks(), _embedded: [WalletResourceEmbeds](../-wallet-resource-embeds/index.md) = WalletResourceEmbeds()) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](_embedded.md) | [androidJvm]<br>open override val [_embedded](_embedded.md): [WalletResourceEmbeds](../-wallet-resource-embeds/index.md) |
| [_links](_links.md) | [androidJvm]<br>open override val [_links](_links.md): [WalletResourceLinks](../-wallet-resource-links/index.md) |
| [consumerId](consumer-id.md) | [androidJvm]<br>val [consumerId](consumer-id.md): [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411) |
| [host](host.md) | [androidJvm]<br>val [host](host.md): [MobileHostResource](../-mobile-host-resource/index.md) |
| [id](id.md) | [androidJvm]<br>val [id](id.md): [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411) |
| [walletName](wallet-name.md) | [androidJvm]<br>val [walletName](wallet-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [walletPublicKey](wallet-public-key.md) | [androidJvm]<br>val [walletPublicKey](wallet-public-key.md): [JWK](../../eu.epicompany.mobile.sdk.domain.model.authentication/-j-w-k/index.md) |
