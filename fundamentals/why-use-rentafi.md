# Why Use RentaFi

NFT contains a variety of utilities, including proof of community participation, game items, and avatars in the metaverse. In addition, the one-of-a-kind nature of NFTs makes many of them highly valuable assets, and they are bought and sold in the marketplace at high prices. In addition to these developments, the rise of NFT-Fi (NFT x De-Fi), in which NFTs are used as collateral for token borrowing and other operations, has begun to develop many ways to utilize NFTs as assets.

However, it is suggested that sometimes high asset quality may reduce the functionality of NFTs. For example,

* A situation in which one person owns multiple NFTs of the same collection.
* A situation in which you do not use NFT utilities but are psychologically reluctant to give up NFTs that have become so popular and expensive.
* A situation in which an expensive NFT is deposited as collateral and the NFT is dysfunctioning.

and others, and these can make NFTs dysfunctional. Furthermore, the high asset value of the NFT is a major barrier to newcomers; many users who cannot become NFT holders may never know what the world is really like. We believe this is also a lost opportunity on the part of the community.

RentaFi is an NFT rental platform that solves these issues. In a rental platform, the lender retains ownership but can gain another revenue opportunity by having the utility used by another user, and the borrower can easily experience and use the utility of NFT without the initial investment in skyrocketing NFT costs.

Among the rental platforms, RentaFi shows features that make it a valuable NFT rental platform.

*   **Make NFTs available for rent on a non-collateral basis**

    Many NFT rental services require collateral as insurance in the event of default. With RentaFi, however, default never occurs because instead of the original NFT, the borrower receives a WrappedNFT, which is a wrapped version of the locked NFT. This minimizes the risk of NFT run-off to the lender.

{% content-ref url="../use-cases/wrappednft.md" %}
[wrappednft.md](../use-cases/wrappednft.md)
{% endcontent-ref %}

****

*   **Borrowers have access to utilities with little capital**

    WrappedNFT holds its own utilities for any NFT that has partnered with RentaFi in a partnership. They can use that utility to play games and participate in the community, and can get started with little capital.



*   **Borrowers do not have to pay return costs**

    WrappedNFT automatically returns the loan to the protocol at the end of the loan period, reducing the cost of the return transaction to zero for the borrower.



*   **Lenders can operate outside services with substantial ownership of the original NFT**

    When a lender deposits an NFT into the contract, an OwnershipNFT is minted; the owner of the OwnershipNFT can receive the original NFT by burning the NFT after the lock period has expired. In other words, this OwnershipNFT indicates ownership of the original NFT, allowing it to be operated by an external service. This effectively separates Use Value and Exchange Value.

{% content-ref url="../use-cases/ownershipnft.md" %}
[ownershipnft.md](../use-cases/ownershipnft.md)
{% endcontent-ref %}

****

*   **Lenders can operate the real future value of the original NFT with outside services**

    This is the most important feature of RentaFi. As mentioned earlier, an OwnershipNFT is minted when the lender locks an NFT into the contract. In addition, another type of NFT is minted, the YieldNFT, which is used to earn back the rental proceeds; the OwnershipNFT represents the current value of the NFT, whereas the YieldNFT represents the future value of the NFT that was locked. This is because the increase in revenue earned during the lock period indicates that more people are continuously looking for that NFT during the lock period. The purpose of having a lock period in our protocol is to achieve this separation of value. The lock period makes it possible to calculate the future value of the NFT in question and enhances composability with external protocols.

{% content-ref url="../use-cases/yieldnft.md" %}
[yieldnft.md](../use-cases/yieldnft.md)
{% endcontent-ref %}
