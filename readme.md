# dig

[![Software Release](https://github.com/notional-labs/dig/actions/workflows/release.yml/badge.svg)](https://github.com/notional-labs/dig/actions/workflows/release.yml)
[![dig blockchain](https://github.com/notional-labs/dig/actions/workflows/build.yml/badge.svg)](https://github.com/notional-labs/dig/actions/workflows/build.yml)
[![Android](https://github.com/notional-labs/dig/actions/workflows/flutter.yml/badge.svg)](https://github.com/notional-labs/dig/actions/workflows/flutter.yml)
[![Raspberry Pi](https://github.com/notional-labs/dig/actions/workflows/pi.yml/badge.svg)](https://github.com/notional-labs/dig/actions/workflows/pi.yml)
[![Security Check](https://github.com/notional-labs/dig/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/notional-labs/dig/actions/workflows/codeql-analysis.yml)

Dig is a hub blockchain that interconnects physical plots of land, which will each be governed by a locally operated blockchain.  Due to the regulatory challenges involved, dig splits itself up into many chains which can each follow appropriate legislation.  This is the beginning of the "Dig Network."


Here's a little light background reading:

* https://blurt.blog/blurt/@jacobgadikian/baby-blockchains
* https://blurt.blog/blurt/@jacobgadikian/blockchain-application-tco
* https://1729.com/miami/
* https://podclips.com/ct/gBhDsq
* https://twitter.com/gadikian/status/1424392074078523397


## Status
Testnet two launched August 15-16.

We will need a testnet three becuase we'd like to use sign-mode EIP and that will require testing.  It will allow ethereum formatted addresses to be used natively on dig.



## [Join Testnet](networks/testnet-3)



## Design

**form**
* Software-wise, dig is a monorepo.  All of its essential code lives in this repository:
  * Genesis
  * Go App Code
  * Javascript Front End Code
  * Mobile App
  * Block explorer

**function**
* The dig mainnet is as minimal as possible.  While we may add a few things before mainnet, it's our preference to remove things.  The dig mainnet is for coordinating the efforts of like-minded people who'd like to see:
  * Liquid Land: Blockchain style real estate investing
  * Charter Cities: Land where the rules are laid out on the chain that constitutes them
  * Hierarchical transparent governance: The trouble with hierarchical orgs is opacity, not hierarchy itself.
  * Research and development of blockchain governance in physical and virtual spaces.    


* Chains in the dig network will launch from the code in this repository, as well.   


## Financing

We're comitted to transparency in all matters, including the composition of genesis allocations.  Dig has raised $0.  Adam has funded development work.  If we take funding, informaiton on that will go right here.  We will only accept funding from parties who are aligned with the long-term vision of the project and willing to have their tokens on exactly the same terms as those who get them in an airdrop.

## Roadmap

- [x] Concept development by Jacob Gadikian and Adam Christopher Chaplin
- [x] Prototype
- [x] Airdrop Prototype code and OpenAPI spec
- [x] Testnet-1:  Results showed that we needed to work on the genesis parameters in Testnet-2
- [x] Omniflix Testnet-1: Participating in the OmniFlix testnet proved the viablity of a large validator set.  Testnet-2 allows 500 validators.
- [x] Upgrade to Cosmos SDK 0.43.0
- [x] IBC Testing
- [x] NFT Implementation by Khanh Nguyen (not included in testnet-2)
- [x] Genesis transactions for testnet-2: Completed August 14, 2021
- [x] Keplr integration
- [x] Akash-based Bus bar
- [x] Launch testnet-2
- [x] IPFS-based genesis hosting and download
- [x] Configuration overrides
- [x] Clean airdrop code https://github.com/notional-labs/c17 and https://github.com/notional-labs/staking-data-collection
  - [ ] Test airdrop code for ethereum-style addresses using the Osmosis Cosmos SDK fork
  - [ ] Refactor airdrop if this works
- [ ] Community Security Audit: 0.1% of Dig tokens reserved for community members who provide a detailed, contextual audit
- [x] Block explorers
  - [x] gex
  - [x] big dipper
- [ ] Ionization 
- [ ] Mainnet Launch
- [ ] IBC Integration via Notional and Chandra Station Relayers
  - [ ] Osmosis Integration
  - [ ] Emeris Integration
  - [ ] Microtick Integration
- [ ] Announcement of candidate Real Estate development sites and their regulatory requirements


- [ ] DFY Integration
- [ ] Blurt Integration
- [ ] First update to dig mainnet
- [ ] First launch of a chain adjacent to dig with live real estate, governed and developed by the chain.
