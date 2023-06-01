//[core](../../../index.md)/[eu.epicompany.mobile.core.network.datasource](../index.md)/[WalletProvisioningNetworkDataSource](index.md)

# WalletProvisioningNetworkDataSource

[androidJvm]\
interface [WalletProvisioningNetworkDataSource](index.md)

An interface for managing wallet provisioning operations.

## Functions

| Name | Summary |
|---|---|
| [fetchProvisionings](fetch-provisionings.md) | [androidJvm]<br>abstract suspend fun [fetchProvisionings](fetch-provisionings.md)(walletId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[ProvisioningResource](../../eu.epicompany.mobile.core.network.model.provisioning/-provisioning-resource/index.md)&gt;<br>Retrieves all provisionings for the provided wallet ID. |
