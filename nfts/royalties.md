> :arrow_left: [back to menu](../README.md)

# **Royalties**

Sqwid NFTs follow the **[EIP-2981 for NFT royalties](https://eips.ethereum.org/EIPS/eip-2981)**. This EIP facilitates the payment of royalties to artists and creators for every NFT sale.

Sqwid NFTs can have a royaltie value that ranges from 0 (no royalties) to the 50%.

The value of the royalties is calculated over the gross amount of the sale. Thus, the marketplace service fees will not be applied over the royalties paid to the creator.

_E.g._

```
An NFT that has associated a roalty value of 10% is sold by 100,000 Reef, with a service fee of 2.5%.

The royalties are substracted from the gross amount of 100,000 Reef and paid to the creator. That is, the creator will receive 10,000 Reef for the sale.

A service fee is applied over the net amount of 90,000 Reef (100,000 Reef - 10,000 Reef), resulting in a total of 2,250 Reef (90,000 * 2.5%).

The seller will be receive a total of 87,750 Reef (90,000 - 2,250).
```

Note that the service fee will however be applied over the royalties value if the seller and the royalties recipient is the same address.

You can check the royalties value for a given NFT in its detail page.

> TODO image

> :arrow_left: [back to menu](../README.md)
