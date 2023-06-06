//[core](../../../index.md)/[eu.epicompany.mobile.core.network.internal.retrofit](../index.md)/[RetrofitPaymentSourceProfileNetworkApi](index.md)/[addContactItem](add-contact-item.md)

# addContactItem

[androidJvm]\

@POST(value = &quot;/api/consumers/{consumerId}/contact-items&quot;)

abstract fun [addContactItem](add-contact-item.md)(@Path(value = &quot;consumerId&quot;)consumerId: [UUID4](../../eu.epicompany.mobile.core.datatypes/index.md#545543244%2FClasslikes%2F-1060529556), @Bodypayload: [AddContactItemRequest](../../eu.epicompany.mobile.core.network.model.proxy/-add-contact-item-request/index.md)): Call&lt;[AddContactItemResource](../../eu.epicompany.mobile.core.network.model.proxy/-add-contact-item-resource/index.md)&gt;
