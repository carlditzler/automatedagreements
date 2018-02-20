# Distributed ledgers or [blockchain frameworks](https://www.igvita.com/2014/05/05/minimum-viable-block-chain/) supporting smart contracts:

1. [Ethereum](https://github.com/ethereum/go-ethereum) - Decentralized application platform with consensus by Proof of Work; will change to Proof of Stake. Preferred smart contract language: Solidity

2. [Quorum, JPMorgan](https://github.com/jpmorganchase/quorum) - Based on Ethereum and introducing encrypted P2P messaging, privacy preserving. Majority voting, Raft-based or Practical Byzantine Fault Tolerance like consensus. Preferred smart contract language: Solidity

3. [Hyperledger Fabric](https://github.com/hyperledger/fabric) - Pluggable, private and permissioned network requiring enrollment via a Membership Service Provider (MSP). Consensus based on Practical Byzantine Fault Tolerance, moving to Raft and pluggable consensus mechanisms. Written in Go. Preferred smart contract language: Go

4. [Hyperledger Sawtooth](https://github.com/hyperledger/sawtooth-core) - Cryptographically verfiable DB (global state agreement to ensure nodes have identical copies) with parallel transaction execution for high throughput, and consensus based on Proof of Elapsed Time (attestation of specified elapsed time), Byzantine Fault Tolerant options. Can integrate with Ethereum. Written in Python. Preferred smart contract language: Python, Go or JavaScript; Solidity with Seth
 
5. [R3 Corda](https://github.com/corda/corda) - Pluggable consensus with a semi-private network, enforces rules provided by nodes and includes a mandatory KYC process. Preferred smart contract language: Kotlin

6. [Chain](https://github.com/chain/chain) - Platform supporting multiple and independent secured blockchain networks written in Go. Enables issuance, ownership, and control of digital assets issued, transferred and exchanged by posting transactions to the Chain network. Preferred smart contract language: Ivy
