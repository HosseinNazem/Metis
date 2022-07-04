# Metis Overview

### Metis Overview <a href="#_jzl9elbcstow" id="_jzl9elbcstow"></a>

Welcome to the Metis overview section. This overview explains how you can get started with the Metis platform and gives you a basic concept of Metis technologies and solutions.

#### Table of Contents <a href="#_qzydoco7kjm9" id="_qzydoco7kjm9"></a>

* What is a smart contract in blockchain?
* Programming languages we need for developing smart contracts
* A simple example of smart contracts
* What is blockchain deployment?
* How do we deploy projects on test platforms?
* What is an Oracle in the blockchain network?
* The role of Graphs and nodes in the blockchain
* What is Remix?
* What is Metamask?

### What is a Smart Contract in Blockchain? <a href="#_60qbiew0z9hy" id="_60qbiew0z9hy"></a>

Smart contracts on the blockchain platform are like computer programs that run when a condition is met. Broadly speaking, a smart contract is some lines of code that are typically used to automate the process of execution. Smart contracts in the blockchain network make it easy to get immediate outputs according to conditions, and they help users and developers design time-efficient and precise processes.

Typical smart contracts have some limitations and that’s why we need hybrid smart contracts that connect the blockchain’s on-chain code to off-chain data. So we can do more complex processes using hybrid smart contracts and with the help of Oracles.

### Programming Languages We Need for Developing Smart Contracts <a href="#_qziedxv9yoh9" id="_qziedxv9yoh9"></a>

As a blockchain developer, you can use a broad range of programming languages for developing and writing smart contracts. Among the most popular programming languages, Solidity is used as the main language for writing smart contract codes. It looks similar to Python, C++, and JavaScript and it runs on the Ethereum Virtual Machine (EVM).

You can install and configure Remix IDE as an open source development environment that supports Solidity. Also, C++, Golang, Java, JavaScript, and Rust are used to develop smart contracts for the Ethereum network.

### A Simple Example of Smart Contracts <a href="#_h21iuc8if9hm" id="_h21iuc8if9hm"></a>

Contracts in Solidity are similar to classes in object-oriented languages like JavaScript. Each contract can have declarations of functions, events, state variables, and so on. You can use the Remix IDE to write, run, and deploy smart contracts.

_// SPDX-License-Identifier: GPL-3.0_

_pragma solidity 0.8.7;_

_contract SimpleStorage {_

_uint storedData;_

_function set(uint x) public {_

_storedData = x;_

_}_

_function get() public view returns (uint) {_

_return storedData;_

_}_

_}_

#### Solidity Versions <a href="#_lkmu8a2pwu01" id="_lkmu8a2pwu01"></a>

The first line that is essentially needed in every Solidity code defines the Solidity version. The code above uses version 0.8.7 which is defined using pragma solidity 0.8.7;

#### Variables <a href="#_pskyp991jeh" id="_pskyp991jeh"></a>

Like in JavaScript, Solidity uses state variables and local variables. State variables are permanently stored, but local variables are present when the function is executing.

There are different types of variables, including the following ones:

* string
* uint256
* uint8

#### State Variables <a href="#_pde73yqzu8ku" id="_pde73yqzu8ku"></a>

State variables are variables whose values are permanently stored in contract storage.

_pragma solidity >=0.4.16 <0.9.0;_

_contract SimpleStorage {_

_uint storedData; // State variable_

_}_

#### Functions <a href="#_f7m5714086wu" id="_f7m5714086wu"></a>

Functions are lines of code that can be executed in case you call them. Functions in Solidity are usually defined inside contracts.

_// SPDX-License-Identifier: GPL-3.0_

_pragma solidity >=0.4.16 <0.9.0;_

_contract SimpleStorage {_

_uint storedData;_

_function set(uint x) public {_

_storedData = x;_

_}_

#### Contracts <a href="#_pt20ynauqio3" id="_pt20ynauqio3"></a>

A contract in Solidity is like a class in JavaScript that can hold lines of code and functions, and can return a specific type of processed data.

### What is Blockchain Deployment? <a href="#_906m30wgpdch" id="_906m30wgpdch"></a>

Blockchain deployment is a process of writing smart contracts, compiling code, and pushing the code to the blockchain network. You should first understand the Ethereum network, transactions, and the structure of the smart contracts to use the most popular deployment environments like Hardhat to perform the deployment process.

For a successful deployment, you need a smart contract, ETH for gas fees, a deployment environment, and you need to access an Ethereum node. So, after blockchain deployment, you will get an Ethereum address.

### How Do We Deploy Projects on Test Platforms? <a href="#_mw3hw2fwatoe" id="_mw3hw2fwatoe"></a>

Testnets allow developers to deploy their projects on a test platform before the mainnet deployment. The process gives an opportunity to run projects completely and check potential issues. Metis Testnet allows you to start your project by deploying on a test environment. It doesn’t cost anything and it needs a few clicks.

### What is an Oracle in the Blockchain Network? <a href="#_nwqsq0ya19b0" id="_nwqsq0ya19b0"></a>

Blockchain Oracles help developers to use external data and they enable smart contracts to be executed based on the information that comes from the outside world. Oracles act as a bridge between the real world and the blockchain network and play an important role in performing advanced transactions.

### The Role of a Graph and Node in the Blockchain <a href="#_kk1u7torpo0k" id="_kk1u7torpo0k"></a>

The graph is software that helps developers collect, process, and store data to easily manage and organize information retrieval. GraphQL is a good language for dealing with data that comes from different sources. We use the Graph to analyze blockchain data before storing it in Subgraphs.

A node in the blockchain network works as a network stakeholder whose primary role is to confirm a batch network of transactions. A crypto node is a critical participant of blockchain security as it stores a complete copy and history of transactions.

### What is Remix? <a href="#_ygaapdnbq3m8" id="_ygaapdnbq3m8"></a>

Remix or Remix IDE is an open-source Ethereum project that provides developers with a highly reliable environment to write, compile, and debug Solidity codes. Remix is an essential tool when speaking about Ethereum blockchain and smart contracts and it lets us develop codes in a GUI based environment.

Remix can be used as an online-based IDE and it’s integrated with some essential tools like MetaMask and JavaScript Virtual Machine.

### What is Metamask? <a href="#_risfz3pc7vdn" id="_risfz3pc7vdn"></a>

MetaMask is a useful tool that serves as an Ethereum wallet and gives you an address. You need an address to deploy your smart contract and MetaMask allows you to create an account and store, swap, and send value based on the Ethereum blockchain.

Going the Developer tools needed to start development on Metis

* &#x20;[Link to Connection Details](../resources/metis-connection-details.md)
* [ Link to Metamask Setting](../resources/metamask-setting-how-to-connect-your-metamask-crypto-wallet-to-metis-platform.md)
* &#x20;[Link to how to get Test Tokens](../resources/getting-test-tokens-on-layer1-and-transferring-them-to-metis.md)

#### What’s next? <a href="#_z2mynn3dg9l8" id="_z2mynn3dg9l8"></a>

* Your First Deployment on Metis
* Verify Contracts