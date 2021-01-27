# Iwi Whitepaper
Eric Donner

Bitcoin and Ethereum are great cryptocurrencies but they are slow and are not meant for people to use them for daily transactions like buying a coffee.
Bitcoin can only do around 4 per second (tx/s). Ethereum can do around 15 tx/s but it's still really slow compared to visa's reportedly 24,000 tx/s.
Therefore you could argue that you should just use a fiat currency but the whole point of cryptocurrencies is so that we don't have to rely on currencies that are controlled by a government.

Other cryptocurrencies have gotten higher transaction speeds but aren't that popular and don't have that much value like Bitcoin and Ethereum.
Combining a delegated proof of stake algorithm, with sidechains and beta genesis, Iwi is made for everyday people making transactions on the blockchain.

## Introduction
Blockchains work by creating a random number from the last block connecting the blocks together in a chain, each transaction is then recorded on the blockchain.
People can then solve difficult puzzles then get rewarded in the currency that runs on the blockchain, this is called mining.
Bitcoin was the first and biggest cryptocurrency and is the one with most value.
Ethereum is the second largest blockchain and allows people to code apps on their blockchain called decentralized apps or DApps.
If you want to mine on the Bitcoin and Ethereum blockchains, it's difficult because of their large size and the number of people that are a part of them.

## Iwi
Iwi hopes to solve these problems that Bitcoin and Ethereum have, among others:

* Size of the blockchain
* Blockchain mining
* Sidechains

### Size of the Blockchain
Because of how blockchains are designed and made, the more computers in the network, the size of the blockchain becomes bigger.
Bitcoin's blockchain is now 316 GBs big at the time of writing.
If we are making a blockchain that millions of people will use for everyday life, they shouldn't have to bring their computer everywhere they go.
Using Beta geneses, people will be able to store the blockchain on their phone without taking up a lot of space. Beta geneses basically taking away part of the blockchain and creating a beta genesis block on the blockchain.
Every X number of blocks, a special block called a beta genesis block will be created and added to the blockchain.
Note, this will only be used by a node who is storing the blockchain on their phone.
If the node for some reason needs to check a past transaction, they will then send a request to another node who is storing the whole blockchain on their computer or system with more storage.
Nodes that are mobile or on phones are called beta nodes. Nodes that are desktop computers or similar, are called alpha nodes. If the alpha node is requested a certain block and sends the block to the beta node, it will be rewarded because that's part of it's job.

```
Beta node asking alpha node for certain block.

Beta Node -> Alpha Node

Alpha node sending block to beta node.

Beta Node <- Alpha Node

```
[Mode info on beta genesis and alpha and beta nodes](docs/betagenesis.md)

### Blockchain mining
Blockchains that use the proof of work algorithm take to much energy up and lead to more centralization of the network as more miners leave or join a mining pool.
Also with a pow blockchain, they can't increase their transaction speeds which are way to slow for a cryptocurrency for everyday transactions.
To solve these problems we can just use a different algorithm. Ethereum 2.0 will use a proof of stake algorithm (PoS) which will use less energy and will be faster.
But to increase our speeds even more, we can use a delegated proof of stake algorithm (DPoS).
This algorithm is like proof of stake, you have to stake your coins and run a node but has a certain number of validators that are elected.
By having less validators which are elected by users themselves, we can further increase the speed and efficiency of the network.

### Sidechains
With sidechains we can then increase performance even further by splitting up different transactions between different chain.
