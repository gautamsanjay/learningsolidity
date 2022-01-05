# Learning Solidity

Remix is an integrated development environment,IDE, to create contract in Solidity language. It is written in Javascript and supports Solidity and Vyper. Remix IDE allows developing, deploying and administering smart contracts for Ethereum like blockchains.

# ABI vs Bytecode
The Ethereum Virtual Machine, EVM, is a multipurpose machine that understands and executes a machine language. This machine language is the bytecode. A complete bytecode may look like: 0x616061604052346000575b6060806100166000396000f360606040526000357c01000000000000
When a solidity code, a file with .sol extension, is compiled it generates two artifacts, ABI(Application Binary Interface) and Bytecode. EMV Bytecode is an executable code on EVM and Contract ABI is an interface to interact with EVM bytecode. For example, if you want to call a function in a smart contract with your JavaScript code, ABI plays a role as an intermediary between your JavaScript code and EVM bytecode to interact with each other. EVM bytecode is a low-level programming language which is compiled from a high-level programming language such as solidity. EVM is a virtual machine which places between OS and application layer to mitigate OS dependency. Thankfully to EVM, Ethereum smart contract can be run on almost any of computers.

# Mainnet vs Testnet
Mainnet – short for main network – is the original and functional blockchain where actual transactions take place in the distributed ledger and the native cryptocurrency possesses real economic value.It is like production environment of any entrerprise software. Mainnets enable dApps to be launched for public use. 

Testnet – short for test network – is an alternative Ethereum blockchain, to be used for testing. It is an experimental network where developers can test, create, or modify functionalities and monitor the blockchain network performance. They fix bugs and other kinds of network failures. They reuse test files ensure the accurate comparison between test runs. This sandbox environment enables the developers to take risks, experiment, and find out the best possible model, a stable version, to be implemented in the Mainnet. All these happen at scale in a controlled manner. Testnets ensure that Mainnet deployments happen faster.
