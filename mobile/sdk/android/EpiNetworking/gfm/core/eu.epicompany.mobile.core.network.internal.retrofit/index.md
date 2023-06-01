//[core](../../index.md)/[eu.epicompany.mobile.core.network.internal.retrofit](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [ConsumerNetworkApi](-consumer-network-api/index.md) | [androidJvm]<br>interface [ConsumerNetworkApi](-consumer-network-api/index.md) |
| [ConsumerResource](-consumer-resource/index.md) | [androidJvm]<br>@Serializable<br>data class [ConsumerResource](-consumer-resource/index.md)(val _links: [ConsumerResourceLinks](-consumer-resource-links/index.md)) : [HalResource](../eu.epicompany.mobile.core.network.hypermedia/-hal-resource/index.md) |
| [ConsumerResourceLinks](-consumer-resource-links/index.md) | [androidJvm]<br>@Serializable<br>data class [ConsumerResourceLinks](-consumer-resource-links/index.md)(val self: [LinkDataModel](../eu.epicompany.mobile.core.network.hypermedia/-link-data-model/index.md), val paymentSourceProfiles: [LinkDataModel](../eu.epicompany.mobile.core.network.hypermedia/-link-data-model/index.md)? = null, val contactItems: [LinkDataModel](../eu.epicompany.mobile.core.network.hypermedia/-link-data-model/index.md)? = null) : [HalLinks](../eu.epicompany.mobile.core.network.hypermedia/-hal-links/index.md) |
| [ContactItemResource](index.md#-1206844945%2FClasslikes%2F-1060529556) | [androidJvm]<br>typealias [ContactItemResource](index.md#-1206844945%2FClasslikes%2F-1060529556) = [AddContactItemResource](../eu.epicompany.mobile.core.network.model.proxy/-add-contact-item-resource/index.md) |
| [P2PPaymentApi](-p2-p-payment-api/index.md) | [androidJvm]<br>interface [P2PPaymentApi](-p2-p-payment-api/index.md)<br>P2P payment api. |
| [RetrofitAuthenticationApi](-retrofit-authentication-api/index.md) | [androidJvm]<br>interface [RetrofitAuthenticationApi](-retrofit-authentication-api/index.md)<br>Authentication api. |
| [RetrofitPaymentSourceProfileNetworkApi](-retrofit-payment-source-profile-network-api/index.md) | [androidJvm]<br>interface [RetrofitPaymentSourceProfileNetworkApi](-retrofit-payment-source-profile-network-api/index.md)<br>PaymentSourceProfile api. |
| [RetrofitProxyApi](-retrofit-proxy-api/index.md) | [androidJvm]<br>interface [RetrofitProxyApi](-retrofit-proxy-api/index.md)<br>Proxy api. |
| [RetrofitWalletApi](-retrofit-wallet-api/index.md) | [androidJvm]<br>interface [RetrofitWalletApi](-retrofit-wallet-api/index.md)<br>Wallet api. |
| [RetrofitWalletProvisioningApi](-retrofit-wallet-provisioning-api/index.md) | [androidJvm]<br>interface [RetrofitWalletProvisioningApi](-retrofit-wallet-provisioning-api/index.md)<br>Wallet provisioning api. |
