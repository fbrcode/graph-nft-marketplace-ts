# TheGraph Subgraph Studio

Repository to code the subgraph specification and push to studio.

- <https://thegraph.com/studio/>
- <https://thegraph.com/docs/en/>

## Init

- `git init`
- `yarn init -y`

## Install and Initialize Graph CLI

- `yarn add @graphprotocol/graph-cli`
- `yarn graph init --studio nft-marketplace`

Fill the options (since it's verified, the ABI is fetched from Etherscan):

✔ Ethereum network · **`rinkeby`**
✔ Contract address · **`0xe088bD8Bb7e0aDcEB50D302bDF49763fD008ABBc`**
✔ **Fetching ABI from Etherscan**
✔ Contract Name · **`NftMarketplace`**
✔ Generate ABI and schema types with **`yarn codegen`**
✔ Add another contract? (y/N) · **`false`**

Subgraph **nft-marketplace** created in **nft-marketplace**

Next steps:

1. Run `graph auth` to authenticate with your deploy key.
2. Type `cd nft-marketplace` to enter the subgraph.
3. Run `yarn deploy` to deploy the subgraph.

Make sure to visit the documentation on <https://thegraph.com/docs/> for further information.
