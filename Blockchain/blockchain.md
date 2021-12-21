![](./OIP.jpg)

## 1. What is Blockchain ?
Blockchain ia a system of recording information in a way that makes it difficut or impossible to change , hack or cheat the system. a blockchain is essentially a digital ledger of transactions that is duplicated and distributed across the entire network of computer system on the blockchain.

## 2. Why do we need Blockchain ?
Blockchain helps in the verification and traceability of multistep transactions needing verification and traceability. it can provide secure transaction , reduce compliance costs , and speed up data transfer processing, blockchain technology can help contract managment and audit the origin of a product.

### i) Byzantine generals

the byzantine generals problem is a game theory , which describes the difficulty decentralized parties have in arriving at consensus without relying on a trusted central party. in a network where no member can verify the identity of other members, how can members ,  how can members collectively agree on a certain truth.

![](./Bzyntine.png)


## 3. What is Consensus ? 

It is basically the agreement on a single data value or a single state of the network among distributed processes or multi-agent .

## 4. What are Consensus Algorithms ?
1. POW
2. POS
3. DPOS,DPS

![](./Comparison-between-consensus-algorithms.png)

###  i) POW
The algorithm is used to confirm the transaction secure and creates a new block to chain . in this algorithm minors (group of peoples) compete the transaction on the network. as soon valid block created by the minors it get into the ledger

### ii) POS
A Proof of Stake (PoS) consensus algorithm is a set of rules governing a blockchain network and the creation of its native coin, that is, it has the same objective as a Proof of Work (PoW) algorithm in the sense that it is an instrument to achieve consensus. Unlike PoW, there are no miners involved in the process.

### iii) DPOS
Delegated Proof of Stake (DPoS) is a consensus algorithm developed to secure a blockchain by ensuring representation of transactions within it. DPoS is designed as an implementation of technology-based democracy, using voting and election process to protect blockchain from centralization and malicious usage.

## 5. What Are the KEY Differences Between BTC and ETH? 
1. Supply Limiting. While BTC has a fixed supply of 21 million coins, ETH has a current supply of around 107 million...
2. Acceptability. BTC can be spent in many more places than ETH. BTC is accepted by 36% of small-to-medium businesses in...
3. Global functionality. In addition to being accepted in many places, BTC has begun to serve as national legal tender,...
4. Technology. ETH and BTC rely on different kinds of blockchain technology. ETH uses its own Proof-of-Work...


## 6. What Are the KEY Differences Between Polygon and ETH? 
Ethereum is a much more decentralized blockchain than Polygon and thus more secure. Polygon intends to become a layer 2 solution where it would derive its security from Ethereum mainnet. Currently however, Polygon’s architecture is defined as a side chain.

## 7. List of Major Blockchains ?

### i) Terra ($LUNA)
Terra is a blockchain protocol that uses fiat-pegged stablecoins to power price-stable global payments systems. According to its white paper, Terra combines the price stability and wide adoption of fiat currencies with the censorship-resistance of Bitcoin (BTC) and offers fast and affordable settlements.

### ii) Solana
Solana has a healthy ecosystem, and its value as a blockchain in terms of how fast it is and how cheap it is to use compared to Ethereum will keep it extremely relevant in the near future.

### iii) Polygon
Polygon effectively transforms Ethereum into a full-fledged multi-chain system (aka Internet of Blockchains). This multi-chain system is akin to other ones such as Polkadot, Cosmos, Avalanche etc. with the advantages of Ethereum’s security, vibrant ecosystem and openness

### iv) Ethereum ($ETH)
Ethereum is a decentralized open-source blockchain system that features its own cryptocurrency, Ether. ETH works as a platform for numerous other cryptocurrencies, as well as for the execution of decentralized smart contracts.




## What are technologies used in Blockchain ?

Keywords -

### 1. Encryption and Decryption

Encryption is the process of converting normal message (plaintext) into meaningless message (Ciphertext). Whereas Decryption is the process of converting meaningless message (Ciphertext) into its original form (Plaintext).

```
from cryptography.fernet import Fernet
key = Fernet.generate_key()
print(key)
msg = "Welcome to Channel".encode()
f_obj = Fernet(key)
encrypted_msg = f_obj.encrypt(msg)
print(encryted_msg)
decryted_msg = f_obj.decrypt(encrpted_msg)
print(decryted_msg)

```

### 2. Brute force

In cryptography, a brute-force attack consists of an attacker submitting many passwords or passphrases with the hope of eventually guessing correctly. The attacker systematically checks all possible passwords and passphrases until the correct one is found. Alternatively, the attacker can attempt to guess the key which is typically created from the password using a key derivation function. This is known as an exhaustive key search.

### 3. Hashing (sha 256)

SHA-256 is a patented cryptographic hash function that outputs a value that is 256 bits long. What is hashing? In encryption, data is transformed into a secure format that is unreadable unless the recipient has a key. In its encrypted form, the data may be of unlimited size, often just as long as when unencrypted.

-keywords
1. search key
2. hash table 
3. hash function

## Tools and Technologies used in Blockchain development. 

0. Smart Contracts and evaluation tools - 
    -- Solidity (contracts)
    #### Solidity is an object-oriented programming language for writing smart contracts. It is used for implementing smart contracts on various blockchain platforms, most notably, Ethereum. ... The programs compiled by the Solidity are intended to be run on Ethereum Virtual Machine.

    -- Viper (contract)
    #### Virtual Incident Procurement (VIPR) is a web-based Forest Service application designed to administer preseason Incident Blanket Purchase Agreements (I-BPAs - formerly referred to as Emergency Equipment Rental Agreements or EERAs).

    -- Ganache (A local blockchain)
    #### Ganache is used for setting up a personal Ethereum Blockchain for testing your Solidity contracts. It provides more features when compared to Remix. ... Before you begin using Ganache, you must first download and install the Blockchain on your local machine.

1. Python
    -- web3.py
    #### Web3.py is a Python library for interacting with Ethereum. It's commonly found in decentralized apps (dapps) to help with sending transactions, interacting with smart contracts, reading block data, and a variety of other use cases.

    -- Brownie
    #### Brownie is a Python-based development and testing framework for smart contracts targeting the Ethereum Virtual Machine. All code starting with $ is meant to be run on your terminal. Code starting with >>> is meant to run inside the Brownie console.

2. Javascript

    -- Truffle
    #### Truffle is a development environment, testing framework and asset pipeline for Ethereum, aiming to make life as an Ethereum developer easier. With Truffle, you get: Built-in smart contract compilation, linking, deployment and binary management. ... Scriptable deployment & migrations framework

    -- Hardhat
    #### Hardhat is a development environment to compile, deploy, test, and debug your Ethereum software. Get Solidity stack traces & console. log. Actions. Packages

differences between the above technologies (eg, hardhat vs brownie, web3.py vs truffle, solidity vs viper)
![](./OIP.jpg)

## 1. What is Blockchain ?
Blockchain ia a system of recording information in a way that makes it difficut or impossible to change , hack or cheat the system. a blockchain is essentially a digital ledger of transactions that is duplicated and distributed across the entire network of computer system on the blockchain.

## 2. Why do we need Blockchain ?
Blockchain helps in the verification and traceability of multistep transactions needing verification and traceability. it can provide secure transaction , reduce compliance costs , and speed up data transfer processing, blockchain technology can help contract managment and audit the origin of a product.

### i) Byzantine generals

the byzantine generals problem is a game theory , which describes the difficulty decentralized parties have in arriving at consensus without relying on a trusted central party. in a network where no member can verify the identity of other members, how can members ,  how can members collectively agree on a certain truth.

![](./Bzyntine.png)


## 3. What is Consensus ? 

It is basically the agreement on a single data value or a single state of the network among distributed processes or multi-agent .

## 4. What are Consensus Algorithms ?
1. POW
2. POS
3. DPOS,DPS

![](./Comparison-between-consensus-algorithms.png)

###  i) POW
The algorithm is used to confirm the transaction secure and creates a new block to chain . in this algorithm minors (group of peoples) compete the transaction on the network. as soon valid block created by the minors it get into the ledger

### ii) POS
A Proof of Stake (PoS) consensus algorithm is a set of rules governing a blockchain network and the creation of its native coin, that is, it has the same objective as a Proof of Work (PoW) algorithm in the sense that it is an instrument to achieve consensus. Unlike PoW, there are no miners involved in the process.

### iii) DPOS
Delegated Proof of Stake (DPoS) is a consensus algorithm developed to secure a blockchain by ensuring representation of transactions within it. DPoS is designed as an implementation of technology-based democracy, using voting and election process to protect blockchain from centralization and malicious usage.

## 5. What Are the KEY Differences Between BTC and ETH? 
1. Supply Limiting. While BTC has a fixed supply of 21 million coins, ETH has a current supply of around 107 million...
2. Acceptability. BTC can be spent in many more places than ETH. BTC is accepted by 36% of small-to-medium businesses in...
3. Global functionality. In addition to being accepted in many places, BTC has begun to serve as national legal tender,...
4. Technology. ETH and BTC rely on different kinds of blockchain technology. ETH uses its own Proof-of-Work...


## 6. What Are the KEY Differences Between Polygon and ETH? 
Ethereum is a much more decentralized blockchain than Polygon and thus more secure. Polygon intends to become a layer 2 solution where it would derive its security from Ethereum mainnet. Currently however, Polygon’s architecture is defined as a side chain.

## 7. List of Major Blockchains ?

### i) Terra ($LUNA)
Terra is a blockchain protocol that uses fiat-pegged stablecoins to power price-stable global payments systems. According to its white paper, Terra combines the price stability and wide adoption of fiat currencies with the censorship-resistance of Bitcoin (BTC) and offers fast and affordable settlements.

### ii) Solana
Solana has a healthy ecosystem, and its value as a blockchain in terms of how fast it is and how cheap it is to use compared to Ethereum will keep it extremely relevant in the near future.

### iii) Polygon
Polygon effectively transforms Ethereum into a full-fledged multi-chain system (aka Internet of Blockchains). This multi-chain system is akin to other ones such as Polkadot, Cosmos, Avalanche etc. with the advantages of Ethereum’s security, vibrant ecosystem and openness

### iv) Ethereum ($ETH)
Ethereum is a decentralized open-source blockchain system that features its own cryptocurrency, Ether. ETH works as a platform for numerous other cryptocurrencies, as well as for the execution of decentralized smart contracts.




## What are technologies used in Blockchain ?

Keywords -

### 1. Encryption and Decryption

Encryption is the process of converting normal message (plaintext) into meaningless message (Ciphertext). Whereas Decryption is the process of converting meaningless message (Ciphertext) into its original form (Plaintext).

```
from cryptography.fernet import Fernet
key = Fernet.generate_key()
print(key)
msg = "Welcome to Channel".encode()
f_obj = Fernet(key)
encrypted_msg = f_obj.encrypt(msg)
print(encryted_msg)
decryted_msg = f_obj.decrypt(encrpted_msg)
print(decryted_msg)

```

### 2. Brute force

In cryptography, a brute-force attack consists of an attacker submitting many passwords or passphrases with the hope of eventually guessing correctly. The attacker systematically checks all possible passwords and passphrases until the correct one is found. Alternatively, the attacker can attempt to guess the key which is typically created from the password using a key derivation function. This is known as an exhaustive key search.

### 3. Hashing (sha 256)

SHA-256 is a patented cryptographic hash function that outputs a value that is 256 bits long. What is hashing? In encryption, data is transformed into a secure format that is unreadable unless the recipient has a key. In its encrypted form, the data may be of unlimited size, often just as long as when unencrypted.

-keywords
1. search key
2. hash table 
3. hash function

## Tools and Technologies used in Blockchain development. 

0. Smart Contracts and evaluation tools - 
    -- Solidity (contracts)
    #### Solidity is an object-oriented programming language for writing smart contracts. It is used for implementing smart contracts on various blockchain platforms, most notably, Ethereum. ... The programs compiled by the Solidity are intended to be run on Ethereum Virtual Machine.

    -- Viper (contract)
    #### Virtual Incident Procurement (VIPR) is a web-based Forest Service application designed to administer preseason Incident Blanket Purchase Agreements (I-BPAs - formerly referred to as Emergency Equipment Rental Agreements or EERAs).

    -- Ganache (A local blockchain)
    #### Ganache is used for setting up a personal Ethereum Blockchain for testing your Solidity contracts. It provides more features when compared to Remix. ... Before you begin using Ganache, you must first download and install the Blockchain on your local machine.

1. Python
    -- web3.py
    #### Web3.py is a Python library for interacting with Ethereum. It's commonly found in decentralized apps (dapps) to help with sending transactions, interacting with smart contracts, reading block data, and a variety of other use cases.

    -- Brownie
    #### Brownie is a Python-based development and testing framework for smart contracts targeting the Ethereum Virtual Machine. All code starting with $ is meant to be run on your terminal. Code starting with >>> is meant to run inside the Brownie console.

2. Javascript

    -- Truffle
    #### Truffle is a development environment, testing framework and asset pipeline for Ethereum, aiming to make life as an Ethereum developer easier. With Truffle, you get: Built-in smart contract compilation, linking, deployment and binary management. ... Scriptable deployment & migrations framework

    -- Hardhat
    #### Hardhat is a development environment to compile, deploy, test, and debug your Ethereum software. Get Solidity stack traces & console. log. Actions. Packages

differences between the above technologies (eg, hardhat vs brownie, web3.py vs truffle, solidity vs viper)
