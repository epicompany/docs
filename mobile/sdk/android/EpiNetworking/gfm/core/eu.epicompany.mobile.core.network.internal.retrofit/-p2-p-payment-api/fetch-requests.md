//[core](../../../index.md)/[eu.epicompany.mobile.core.network.internal.retrofit](../index.md)/[P2PPaymentApi](index.md)/[fetchRequests](fetch-requests.md)

# fetchRequests

[androidJvm]\

@GET(value = &quot;/api/p2p-requests&quot;)

abstract suspend fun [fetchRequests](fetch-requests.md)(@Query(value = &quot;direction&quot;)direction: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), @Query(value = &quot;status&quot;)status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), @Query(value = &quot;sort&quot;)sort: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), @Query(value = &quot;page&quot;)page: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), @Query(value = &quot;size&quot;)size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [PagedCollectionResource](../../eu.epicompany.mobile.core.network.hypermedia/-paged-collection-resource/index.md)&lt;[P2PRequestCollectionResourceEmbed](../../eu.epicompany.mobile.core.network.model.p2ppayment/-p2-p-request-collection-resource-embed/index.md)&gt;
