# Distributed ledgers or [blockchain frameworks](https://www.igvita.com/2014/05/05/minimum-viable-block-chain/) supporting smart contracts:

##Ethereum
1. [Ethereum](https://github.com/ethereum/go-ethereum) - Decentralized application platform with consensus by Proof of Work; will change to Proof of Stake. Primarily implementation, Geth, is written in Go. 
> Smart contract language: Solidity; [example1](https://github.com/ethereum/solidity-examples), [example2](https://www.ethereum.org/greeter). See [Truffle](http://truffleframework.com/). 

##Quorum
2. [Quorum, JPMorgan](https://github.com/jpmorganchase/quorum) - Based on Ethereum and introducing encrypted P2P messaging, privacy preserving. Majority voting, Raft-based or Practical Byzantine Fault Tolerance like consensus. 
> Smart contract language: Solidity

##Hyperledger Fabric
3. [Hyperledger Fabric](https://github.com/hyperledger/fabric) - Pluggable, private and permissioned network requiring enrollment via a Membership Service Provider (MSP). Consensus based on Practical Byzantine Fault Tolerance, moving to Raft and pluggable consensus mechanisms. Written in Go. 
> Smart contract language: Go; [example](https://developer.ibm.com/tv/hyperledger-composer-build-execute-smart-contract/). See [Composer](https://www.hyperledger.org/projects/composer)

##Hyperledger Sawtooth
4. [Hyperledger Sawtooth](https://github.com/hyperledger/sawtooth-core) - Cryptographically verfiable DB (global state agreement to ensure nodes have identical copies) with parallel transaction execution for high throughput, and consensus based on Proof of Elapsed Time (attestation of specified elapsed time), Byzantine Fault Tolerant options. Can integrate with Ethereum. Written in Python. 
> Smart contract languagse: Python, Go or JavaScript; Solidity with Seth

##Corda
5. [R3 Corda](https://github.com/corda/corda) - Pluggable consensus with a semi-private network, enforces rules provided by nodes and includes a mandatory KYC process. 
> Smart contract language: Kotlin; [examples](https://github.com/corda/corda/blob/master/docs/source/tutorial-contract.rst)

##Wanchain
6. [Wanchain Go](https://github.com/wanchain/go-wanchain) - 
> Smart contract language: Soliday; [examples](https://github.com/wanchain/go-wanchain/wiki/How--to-deploy-smart-contracts-on-Wanchain)

##Sequence/Chain
7. [Sequence](https://chain.com/sequence/) - Cloud/ledger-as-a-service system of record to manage any value type or balance using a token-based data model. [Chain](https://chain.com) discontinued [Chain Core](https://github.com/chain/chain) development and support so it can focus on Sequence. 
> Chain Core was a platform supporting multiple and independent secured blockchain networks written in Go. Enables issuance, ownership, and control of digital assets issued, transferred and exchanged by posting transactions to the Chain network. 
>> Preferred smart contract language: Ivy





