# Solana NFT 

This repo contains the code, for creating a new NFT Collection on the Solana Devnet, which accepts a custom SPL token as the price, for minting the NFTs.
It has a limit of 10 NFTs as of now, and the price of each NFT is 1 SPL token.

## Description

This repository contains code to create a distinct NFT Collection on Solana Devnet. It utilizes a custom SPL token as the minting price, set at 1 SPL token per NFT. With a current cap of 10 NFTs, this code is a practical guide for developers diving into Solana-based NFT creation, offering a unique pricing mechanism for exploration within the Devnet environment.

### Getting Started

To interact with the project, you can start on a gitpod, by clicking on this link 
[Gitpod](https://gitpod.io/new/#https://github.com/Metacrafters/Module3-Candymachine)

or by cloning this repo and installing 

[git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git): to clone the starter project;
[node](https://nodejs.org/en/download/): Javascript runtime environment;
[yarn](https://classic.yarnpkg.com/lang/en/docs/install/#mac-stable): package manager for installing the required dependencies;
[ts-node](https://www.npmjs.com/package/ts-node#installation): Typescript execution environment;
[solana cli[(https://docs.solana.com/cli/install-solana-cli-tools): to interact with the Solana Blockchain;
[sugar cli](https://docs.metaplex.com/developer-tools/sugar/overview/installation#recommended-installation-method): to setup and operate our Candy Machine;

and then running the following commands

To create a new wallet:

```
solana-keygen new --outfile ./wallet.json
```
Then this command will associate it with your Solana and Sugar CLIs:
```
 solana config set --keypair ./wallet.json

```

Make sure you’re on the devnet:

```
solana config set --url https://api.devnet.solana.com

```

and then finally fund your wallet with some SOL

```
solana airdrop 1
```

Then Set your config file and run 

```
sugar validate
```

To verify all the assets 

```
sugar upload
```

To upload the assets on Arweave, and then to deploy your candy machine, run 

```
sugar deploy
```

For the final check

```
sugar verify
```

and now, to finally mint 

```
sugar mint

```

This is the link for Solscan, where you can find all the addresses:


[SolScan](https://explorer.solana.com/?cluster=devnet)


The Candy Machine ID is:

```
317rNqcnzXUFTRQBEYoajW6yLhBkvHgHRS7mQAny2wY1
```

Collection Mint Id: 

```
7wD2iZLsGkwd9gp6PJG2PXE1fyiQBLyZLzhFVP2HPVZ2
```

Token Repo Github link

[Token](https://github.com/ethParth/Sol_Beg_Mod_3_Token)

### Author

Parth Verma
