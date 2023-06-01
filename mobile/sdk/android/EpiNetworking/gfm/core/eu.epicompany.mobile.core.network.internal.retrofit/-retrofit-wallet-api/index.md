//[core](../../../index.md)/[eu.epicompany.mobile.core.network.internal.retrofit](../index.md)/[RetrofitWalletApi](index.md)

# RetrofitWalletApi

[androidJvm]\
interface [RetrofitWalletApi](index.md)

Wallet api.

## Functions

| Name | Summary |
|---|---|
| [fetchWallet](fetch-wallet.md) | [androidJvm]<br>@GET(value = &quot;/api/wallets/{walletId}&quot;)<br>abstract suspend fun [fetchWallet](fetch-wallet.md)(@Path(value = &quot;walletId&quot;)walletId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556)): [WalletResource](../../eu.epicompany.mobile.core.network.model.wallet/-wallet-resource/index.md) |
