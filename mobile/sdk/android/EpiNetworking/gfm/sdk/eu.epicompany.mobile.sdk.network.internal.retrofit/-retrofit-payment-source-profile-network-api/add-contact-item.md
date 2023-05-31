//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.internal.retrofit](../index.md)/[RetrofitPaymentSourceProfileNetworkApi](index.md)/[addContactItem](add-contact-item.md)

# addContactItem

[androidJvm]\

@POST(value = &quot;/api/consumers/{consumerId}/contact-items&quot;)

abstract suspend fun [addContactItem](add-contact-item.md)(@Path(value = &quot;consumerId&quot;)consumerId: [UUID4](../../eu.epicompany.mobile.android.datatypes/index.md#229649042%2FClasslikes%2F462465411), @Bodypayload: [AddContactItemRequest](../../eu.epicompany.mobile.sdk.network.model.proxy/-add-contact-item-request/index.md)): [AddContactItemResource](../../eu.epicompany.mobile.sdk.network.model.proxy/-add-contact-item-resource/index.md)
