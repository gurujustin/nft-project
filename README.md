# nft-tutorial
A very basic NFT tutorial repository for absolute beginners in the world of Web3 and smart contracts

The completed version of the code developed by following our tutorial for NFT beginners [here](https://docs.opensea.io/docs/creating-an-nft-contract)

You'll need to update the environment variables `ALCHEMY_KEY` and `ACCOUNT_PRIVATE_KEY` in order to compile hardhat. You can learn more about where to get them [here](https://docs.alchemy.com/alchemy/tutorials/sending-txs).

[![Run on Repl.it](https://repl.it/badge/github/plibither8/2048.cpp)](https://replit.com/@openseaofficial/nft-tutorial)

> npx hardhat compile
Compiling 11 files with 0.8.0
Compilation finished successfully

> npx hardhat deploy
Contract deployed to address: 0xEC98C68b96e8D89D17C99a742CC37b5b2298dB41


Set your NFT_CONTRACT_ADDRESS env variable and source your .env file
> . .env
> npx hardhat set-base-token-uri --base-url "https://bafybeif6iuokmmcuwj7jgscybx3gvlcwkb6ybspwcduivl7mbqmgmmxubi.ipfs.dweb.link/metadata/"
Transaction Hash: 0xdd9a44d4131ee48db493d0484b0b294bff8135b678fa0e029677d04e3683eca8

> npx hardhat mint --address 0xb9720BE63Ea8896956A06d2dEd491De125fD705E
Transaction Hash: 0x99b09300643f6e95563a6f54b94366f79daef835969a53933b1dc43208341a18

> npx hardhat mint --address 0xb9720BE63Ea8896956A06d2dEd491De125fD705E
Transaction Hash: 0x661c48b2e306210fde28765786116a6dc4f955f2d44f09dee2ed66f9c9c4f79a

> npx hardhat token-uri --token-id 1
Metadata URL: https://bafybeif6iuokmmcuwj7jgscybx3gvlcwkb6ybspwcduivl7mbqmgmmxubi.ipfs.dweb.link/metadata/1
Metadata fetch response: {
  "description": "Friendly OpenSea Creature that enjoys long swims in the ocean.",
  "external_url": "https://example.com/?token_id=1",
  "image": "https://bafybeihslhol5draa26unhhe7j2crwedr4tyfrvmba5qt3kyxbvb5olk4i.ipfs.dweb.link/images/1.png",
  "name": "Sprinkles Fisherton"
}

> npx hardhat token-uri --token-id 2
Metadata URL: https://bafybeif6iuokmmcuwj7jgscybx3gvlcwkb6ybspwcduivl7mbqmgmmxubi.ipfs.dweb.link/metadata/2
Metadata fetch response: {
  "description": "Friendly OpenSea Creature that enjoys long swims in the ocean.",
  "external_url": "https://example.com/?token_id=1",
  "image": "https://bafybeihslhol5draa26unhhe7j2crwedr4tyfrvmba5qt3kyxbvb5olk4i.ipfs.dweb.link/images/2.png",
  "name": "Boris McCoy"
}
