//[core](../../../index.md)/[eu.epicompany.mobile.core.network.datasource](../index.md)/[WalletProvisioningNetworkDataSource](index.md)/[fetchProvisionings](fetch-provisionings.md)

# fetchProvisionings

[androidJvm]\
abstract suspend fun [fetchProvisionings](fetch-provisionings.md)(walletId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[ProvisioningResource](../../eu.epicompany.mobile.core.network.model.provisioning/-provisioning-resource/index.md)&gt;

Retrieves all provisionings for the provided wallet ID.

#### Return

The provisioning resource.

#### Parameters

androidJvm

| | |
|---|---|
| walletId | The wallet ID. |
