NFText cw smart contracts
---
These contracts are used to deploy and run [NFText](https://github.com/wotori-studio/NFText) dApp to [Archway](https://archway.io/) Torii test-net.


cw20-bonding, cw721 and cw721-meta-onchain 
---

cloned from [CosmWasm](https://github.com/CosmWasm/cosmwasm)
- [cw-plus](https://github.com/CosmWasm/cw-plus) 
- [cw-nfts](https://github.com/CosmWasm/cw-nfts)

cw-marketplace 
---
The [fork](https://github.com/wotori-studio/cw-marketplace) from original authors with updated dependencies.
cw-marketplace also copied here for future updates in conjunction with other contracts.

# How to
setup NFT marketplace
1st - deploy cw-marketplace
2nd - deploy cw721 as a comunity contract with marketplace as admin
3rd - deploy cw20
4th - deploy [instantiator](https://github.com/wotori/instantiator)