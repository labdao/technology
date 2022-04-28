# LabDAO Tech Priorities (till end of May)

## Web3

### 0 Gnosis Chain deployment 
* Done: https://blockscout.com/xdai/mainnet/address/0xdE677961f2a802DF105d014B8D7042914bb780cf/contracts

### 1 Security
* **Testing** - load Hardhat suite into Foundry and build Solidity tests. **Everything** needs to be tested and patched prior to a mainnet launch
* **Upgradeable Contracts** - this will be our temporary solution prior to a full audit

### 2 NFT Subgraph
* New subgraph built for OpenLab NFTs. This should incorporate learnings from Hackathon (build business logic using js-ipfs directly into graph to pull relevant data). Needs to be usable for anyone looking at data generated
* Frontend that allows for searching, querying, and exporting data pinned to IPFS

### 4 IPFS Gateway - probably comes before encryption
* host own estuary node
* do we need to host our own gateway? alternative is to incentivize or require providers to host our data on their nodes

### 3 A Plan for Encrypted Data
* I think this is lower priority, but willing to be convinced otherwise :D 
* encryption on client side 
* stake to be truthful around the encryption status (flag in the metadata - )
    * slashed when you lie as a client
        * slashed as a provider if you don't respect the client's wish
    * refund of fees when you don't and its not encrypted
* KPI during Alpha release is Exchange volume and/or NFTs minted... Focusing on encrypted data too early will distract us from this
* Reimbursement of fee based on encrypted/unencrypted, staking/unstaking LAB tokens
* Keep our protocols minimal but extensible


## Non-Web3

### 1 CLI
* Fully functional
* Estuary integration healthy
* Wrap smart contract function calls into `openlab job submit` and `openlab job close`
* UX polishes
* Allowing people to contribute and use the CLI

### 3 Green-lit Pipelines
* What's our Alpha list of services offered?
* Combination of core-team driven work + community-built pipelines seems ideal
* 3-5 pipelines to choose from
** AlphaFold
** RNA seq
** ^ Community group to 
** ...what else?
* Diligence Working Group could slot in here

### 2 Docs
* Scope out everything for Alpha release and have documentation ready for it

## Concepts which deserve serious attention

### 1 Metadata structure and data standards - meeting on Wednesday
* Needs to be general-purpose (recursive loop maybe?) Ideally we should have something to present at DeSci Berlin
* This will impact our broader data strategy. Example: if we shard a large piece of data on IPFS, we need all shards to be easily retrievable by a subgraph
* MVP implementation (*Note: I think we can implement any draft within our MVP since the metadata logic and structure is not defined in smart contracts but rather in our off-chain tools like Graph Protocol*)
* Identify key partners to work with (Molecule, DeSci Labs, OrangeDAO, etc)

### Regenify our Data Ecosystem
* **Goal:** Unencrypted data generated is a public good. **Problem:** How do we make this self-sustaining? A difficult, but crucial existential challenge... take a basis point, manage float, charge the downstream and upstream funders

* 

## Nice to have, but lower priority

### Generative artwork for each NFT minted

### Application for whitelisted providers
* Providers who run green-lit pipelines
* Should this be integrated with outside lab exchange proposals?



## Roll-out

Closed alpha with public visibility
* 10ish "Clients"
* "Providers"
* 