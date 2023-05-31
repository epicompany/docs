//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.internal.retrofit](../index.md)/[RetrofitWalletProvisioningApi](index.md)

# RetrofitWalletProvisioningApi

[androidJvm]\
interface [RetrofitWalletProvisioningApi](index.md)

Wallet provisioning api.

## Functions

| Name | Summary |
|---|---|
| [fetchProvisionings](fetch-provisionings.md) | [androidJvm]<br>@GET(value = &quot;/api/wallets/{walletId}/provisionings&quot;)<br>abstract suspend fun [fetchProvisionings](fetch-provisionings.md)(@Path(value = &quot;walletId&quot;)walletId: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411)): [CollectionResource](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-collection-resource/index.md)&lt;[ProvisioningCollectionResourceEmbed](../../eu.epicompany.mobile.sdk.network.model.provisioning/-provisioning-collection-resource-embed/index.md)&gt; |
