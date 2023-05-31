//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.internal.retrofit](../index.md)/[RetrofitWalletApi](index.md)/[fetchWallet](fetch-wallet.md)

# fetchWallet

[androidJvm]\

@GET(value = &quot;/api/wallets/{walletId}&quot;)

abstract suspend fun [fetchWallet](fetch-wallet.md)(@Path(value = &quot;walletId&quot;)walletId: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411)): [WalletResource](../../eu.epicompany.mobile.sdk.network.model.wallet/-wallet-resource/index.md)
