//[core](../../../index.md)/[eu.epicompany.mobile.core.network.datasource](../index.md)/[PaymentSourceProfileNetworkDataSource](index.md)/[addContactItem](add-contact-item.md)

# addContactItem

[androidJvm]\
abstract suspend fun [addContactItem](add-contact-item.md)(consumerId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), payload: [AddContactItemRequest](../../eu.epicompany.mobile.core.network.model.proxy/-add-contact-item-request/index.md)): [AddContactItemResource](../../eu.epicompany.mobile.core.network.model.proxy/-add-contact-item-resource/index.md)

Adds a contact item for the specified consumer.

#### Return

The payment source profile resource.

#### Parameters

androidJvm

| | |
|---|---|
| consumerId | The consumer ID. |
| payload | The payload containing the contact item details to add. |
