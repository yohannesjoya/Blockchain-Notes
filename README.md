# Blockchain-Notes
Blockchain Notes

NOTE 1
# Blockchain
#### Explanation
<img src='https://i.imgur.com/OFWjRQ3.jpg'/>
A blockchain is an ever-growing list of data entries called blocks that are linked together to form an unchangeable chain using cryptography. Blockchains are typically managed by a permissionless peer-to-peer network. The participants of the network (nodes) store the data of the blockchain.Interactions that change the data in the blockchain are called transactions. They are sent to the peer-to-peer network and grouped into blocks of transactions. Special nodes in the network called miners, add new blocks of transactions to the blockchain and receive rewards in the native cryptocurrency for that.The most innovative part of blockchain technology is the consensus mechanism that decides how miners can add new data in the form of blocks of transactions to the blockchain. Bitcoin use a consensus mechanism called proof-of-work (POW). In POW miners need to spend computing power for the chance of being able to add a new block to the blockchain. Needing to spend energy on adding new data to the blockchain, prevents attackers from false entries because it is more profitable to add correct entries.The revolutionary innovation of blockchain technology is the ability to store data publicly in a permanent way, not being dependent on a central decision-maker that could change the data.


<h4>NOTE 2</h4>

# Ethereum
#### Explanation
<img src='https://i.imgur.com/7Oe4uJC.jpg'/>
Ethereum is a decentralized blockchain-based computing infrastructure that executes programs called smart contracts and enables developers to create decentralized applications (dapps). Ethereum has a native cryptocurrency called Ether.

Bitcoin has a very limited scripting language and is not designed to be programmed for anything else than peer-to-peer money.

Ethereum's language is designed to execute arbitrary code and enable developers to create all kinds of applications on top of blockchain technology.

Ethereum is sometimes described as a world computer because it uses blockchain technology as a global data storage, that can store code and data, and execute programs on one globally distributed machine. This virtual computer, whose state all participants in the network share is called the Ethereum Virtual Machine (EVM).

Because the execution of programs and storing of data on Ethereum must be done by all the nodes in the network, performing computational tasks and making changes to the state of the data needs to be paid for to prevent abuse. Computational work is measured in Gas and is paid in Ether. Changes in the state are submitted via transactions.

The idea of Ethereum is to apply the benefits of blockchain technology to code and applications in general. Enabling developers to create applications with built-in economic functions that are transparent, immutable (unchangeable), and accessible.

But like Bitcoin, Ethereum struggles among other things with, energy efficiency, high transaction costs, and poor user experience.


<h4>NOTE 3</h4>


# Celo

#### Explanation
<img src='https://i.imgur.com/LTMQciu.jpg'/>
Celo is a mobile-first blockchain that focuses on creating an accessible, environmentally friendly financial system. The Celo blockchain was developed in response to the many challenges that popular blockchains like Bitcoin and Ethereum are facing.Stable Value CurrenciesA crucial challenge for accessibility and large-scale adoption of cryptocurrencies as a medium of exchange is their price volatility. Celo provides a growing family of stablecoins like cUSD, cEUR, cREAL, USDC, with a stable value that can even be used to pay transaction fees.Proof-of-Stake Bitcoin is using the proof-of-work consensus mechanisms, which costs a lot of energy and leads to expensive and often slower transactions. Celo uses a proof-of-stake consensus algorithm that enables fast, affordable, and carbon-negative transactions.Phone Number MappingAnother barrier to the accessibility of cryptocurrencies is their poor user experience. Users need to generate a private/public key pair to receive a payment, and they need to know a user's address in order to send them a payment. Celo allows users to send cryptocurrencies just via phone numbers by mapping their phone numbers to public keys.Full EVM CompatibilityCelo is fully EVM compatible and lets developers write code in the popular Solidity smart contract language. This means that the Celo ecosystem can make use of Ethereum tooling, contracts, and token standards like ERC-20 or ERC721 (NFT).



<h3>Note 4 </h3>

# Smart Contracts
#### Explanation
<img src='https://i.imgur.com/oOYJBy8.jpg' />

A smart contract is a computer program that runs on a blockchain.

Because smart contracts run (store code and state) on a blockchain, they are dependable and cannot be changed in ways that they weren't intended to by anybody after they are published.

While smart contracts are computer programs, the name refers to the fact that, because of their dependability, they can be used to handle agreements between multiple parties, like traditional legal contracts.

After the conditions of a traditional contract are met, the involved parties need to rely on each other to behave as stated in the contract or enforce further legal actions if they don't. Creating and enforcing traditional legal contracts is very time-consuming, expensive, and often biased toward parties with more financial resources.

Smart contracts specify the terms of agreements in computer code that executes instructions automatically once terms are met, without being able to be changed or stopped.

As a simple example, one could create a child trust fund that automatically withdraws funds to a child at a specific date, without the need for the involvement of anybody after the publication of the contract.

The difference between smart contracts to traditional computer programs is that the execution of the code of smart contracts is guaranteed. Smart contracts can not be modified in unintended ways, stopped, or deleted after they are published.



<h3>Note 5</h3>

# Dapps
#### Explanation
<img src='https://i.imgur.com/k9ztbB2.jpg' />
A decentralized application (dapp) is an application that runs on a decentralized network and not a centralized server.

Dapps consist of:

- Data - That is stored on a blockchain.
- Backend code - That is written as smart contracts, running on a blockchain.
- Frontend code - The user interface can be written as for a traditional application, only making calls to a smart contract instead of a centralized backend.
##### Trust
Dapps are censorship-resistant and have no owners. Once the backend code is deployed to the blockchain, nobody can take it down, change it in unintended ways, block users, or get hacked. This also means that dapps have zero downtime.

##### Privacy and Transparency
Dapps can be anonymously deployed (created). Interactions with dapps happen via an anonymous login through a user's wallet and their blockchain account. What data is shared and collected is transparent, as well as the logic of the code.

##### Interoperability
The smart contract code of a dapp is publically accessible in the blockchain and compatible with other smart contract code. This enables developers to build upon each other's work, leading to more and faster innovation.

##### Challenges
But dapps also face some challenges. Since the backend code is immutable, the maintenance of a dapp can be difficult because the code cannot be easily updated. Interactions with dapps that lead to changes in the data can also be expensive and slow.



<h3>Note 6</h3>

# Accounts
#### Explanation

<img src='https://i.imgur.com/0sJoaZN.jpg'/>
Celo accounts have a Celo balance and can send and receive Celo transactions.

There are two types of accounts: Externally-owned accounts and contract accounts.

##### Externally-owned accounts
Externally-owned accounts (EOAs) are human-controlled user accounts.

They consist of a cryptographic pair of keys: A public key (that can be shared with others) and a private key (that should only be known to the owner).

The owner of a private key uses it to create a digital signature that is attached to a transaction, to authenticate that it was sent by them.

##### Contract accounts
A contract account consists of smart contract code that is deployed to the blockchain. It does not have a private key and is only controlled by the logic of the smart contract code.

Like EOAs, contract accounts can send and receive Celo and interact with other contracts. Only EOAs can initiate a transaction, but contract accounts can react to a transaction and call other contracts.

##### Addresses
Accounts can be identified via addresses. EOAs and contract accounts both have addresses that can be used to receive transactions.

To better understand externally-owned accounts, we can compare them to email accounts. Email accounts have an address that can be shared and is used to send them a message, but only the owner can send messages by authenticating via a password. Similar to the EAOs private key.


<h3>Note 7</h3>

# Wallets
#### Explanation
<img src='https://i.imgur.com/PU9Fg0X.jpg'/>
A cryptocurrency wallet is a device that stores public/private key pairs to manage cryptocurrency accounts. A user can sign transactions and transfer cryptocurrency or execute smart contracts with a wallet.

The wallet is the primary user interface for Celo. It shows the Celo balance and transaction history, allows one to sign messages and transactions, and log in to Celo applications (dapps).

A wallet can handle multiple Celo accounts. It can also create new accounts and import old ones via their private keys.

There are two main types of wallet devices: software wallets and hardware wallets.

  - Software wallets - Sometimes, also called hot wallets, are usually connected to the internet. They come in the form of mobile, desktop, or web applications. Because they are connected to the internet, they are not as secure as hardware wallets.
  - Hardware wallets - Sometimes, also called cold wallets or cold storage, aren't connected to the internet. It is a physical device that holds your private keys and keeps them offline; this makes them more secure from attackers.
#### Seed phrase
Wallets have a seed phrase, also called the secret recovery phrase or mnemonic. It is a human-readable version of the private key that consists of a list of 12 or more dictionary words.
With the seed phrase, the user can recover a wallet and all accounts created with it, even if the software or hardware device that stored the wallet is not accessible anymore.

The terminology of a wallet is misleading; a wallet does not store tokens but pairs of private and public keys. It is more accurate to think of a cryptocurrency wallet as a keychain.
