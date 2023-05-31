//[sdk](../../../index.md)/[eu.epicompany.mobile.sdk.network.model.wallet](../index.md)/[PaymentMeansCollectionResource](index.md)

# PaymentMeansCollectionResource

[androidJvm]\
@Serializable

data class [PaymentMeansCollectionResource](index.md)(val paymentMeans: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[PaymentMeansResource](../-payment-means-resource/index.md)&gt;, val _embedded: [PaymentMeansCollectionResource.Embeds](-embeds/index.md) = Embeds(), val _links: [PaymentMeansCollectionResource.Links](-links/index.md) = Links()) : [HalResource](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-resource/index.md)

## Constructors

| | |
|---|---|
| [PaymentMeansCollectionResource](-payment-means-collection-resource.md) | [androidJvm]<br>constructor(paymentMeans: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[PaymentMeansResource](../-payment-means-resource/index.md)&gt;, _embedded: [PaymentMeansCollectionResource.Embeds](-embeds/index.md) = Embeds(), _links: [PaymentMeansCollectionResource.Links](-links/index.md) = Links()) |

## Types

| Name | Summary |
|---|---|
| [Embeds](-embeds/index.md) | [androidJvm]<br>@Serializable<br>data class [Embeds](-embeds/index.md)(val wallet: [WalletResource](../-wallet-resource/index.md)? = null) : [EmbeddedHalResources](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-embedded-hal-resources/index.md) |
| [Links](-links/index.md) | [androidJvm]<br>@Serializable<br>data class [Links](-links/index.md)(val self: [LinkDataModel](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-link-data-model/index.md)? = null, val wallet: [LinkDataModel](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-link-data-model/index.md)? = null) : [HalLinks](../../eu.epicompany.mobile.android.data.network.model.hypermedia/-hal-links/index.md) |

## Properties

| Name | Summary |
|---|---|
| [_embedded](_embedded.md) | [androidJvm]<br>open override val [_embedded](_embedded.md): [PaymentMeansCollectionResource.Embeds](-embeds/index.md) |
| [_links](_links.md) | [androidJvm]<br>open override val [_links](_links.md): [PaymentMeansCollectionResource.Links](-links/index.md) |
| [paymentMeans](payment-means.md) | [androidJvm]<br>val [paymentMeans](payment-means.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[PaymentMeansResource](../-payment-means-resource/index.md)&gt; |
