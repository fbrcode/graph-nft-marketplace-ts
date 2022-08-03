# TheGraph Subgraph Studio

This is **just a generator step** to not install TheGraph CLI globally.

The subgraph code will be at **`../graph-subgraph-nft-marketplace`**

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

✔ Protocol · **`ethereum`**
✔ Subgraph slug › **`nft-marketplace`**
✔ Directory to create the subgraph in › **`../graph-subgraph-nft-marketplace`**

> Notice that we are creating outside of the current repository because it is a different repository.

✔ Ethereum network · **`rinkeby`**
✔ Contract address · **`0xe088bD8Bb7e0aDcEB50D302bDF49763fD008ABBc`**

✔ **Fetching ABI from Etherscan**
`-- or --`
✖ Failed to fetch ABI from Etherscan: ABI not found, try loading it from a local file
✔ ABI file (path) · **`../hardhat-nft-marketplace-ts/deployments/rinkeby/NftMarketplace.json`**

✔ Contract Name · **`NftMarketplace`**

`———`
✔ Install dependencies with **`yarn`**
✔ Generate ABI and schema types with **`yarn codegen`**
✔ Add another contract? (y/N) · **`false`**

Subgraph **nft-marketplace** created in **`../graph-subgraph-nft-marketplace`**

Next steps:

1. Run `graph auth` to authenticate with your deploy key.

2. Type `cd ../../graph-subgraph-nft-marketplace` to enter the subgraph.

3. Run `yarn deploy` to deploy the subgraph.

Make sure to visit the documentation on <https://thegraph.com/docs/> for further information.

Now shift to the subgraph generated directory: **`graph-subgraph-nft-marketplace`**
