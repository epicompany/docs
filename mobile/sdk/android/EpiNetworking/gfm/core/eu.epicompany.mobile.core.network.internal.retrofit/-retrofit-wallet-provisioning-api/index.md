//[core](../../../index.md)/[eu.epicompany.mobile.core.network.internal.retrofit](../index.md)/[RetrofitWalletProvisioningApi](index.md)

# RetrofitWalletProvisioningApi

[androidJvm]\
interface [RetrofitWalletProvisioningApi](index.md)

Wallet provisioning api.

## Functions

| Name | Summary |
|---|---|
| [fetchProvisionings](fetch-provisionings.md) | [androidJvm]<br>@GET(value = &quot;/api/wallets/{walletId}/provisionings&quot;)<br>abstract fun [fetchProvisionings](fetch-provisionings.md)(@Path(value = &quot;walletId&quot;)walletId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556)): Call&lt;[CollectionResource](../../eu.epicompany.mobile.core.network.hypermedia/-collection-resource/index.md)&lt;[ProvisioningCollectionResourceEmbed](../../eu.epicompany.mobile.core.network.model.provisioning/-provisioning-collection-resource-embed/index.md)&gt;&gt; |
