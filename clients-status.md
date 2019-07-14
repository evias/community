# Clients Protocol Compatibility

## Table of contents

- [Abstract](#abstract)
- [Client Applications](#client-applications)
- [Protocol Version Compatibilities](#protocol-version-compatibilities)
  - [Icon Status Attribution](#icon-status-attribution)
  - [Elephant: Protocol v0.5.?.?](#elephant-protocol-v05)
  - [Dragon: Protocol v0.4.?.?](#dragon-protocol-v04)
  - [Cow: Protocol v0.3.0.2](#cow-protocol-v0302)
- [History](#history)	

## Abstract

This document aims to group technical features of Milestones in the Catapult Protocol Development project and assess/update status reports about specific **Clients** compatibility.

The document should provide with an easy aggregation of all features addressed in the protocol project during milestones development and should provide a clear compatibility table for individual protocol features / or changes.

## Client Applications

Following client applications are taken into account for this compatibility status update:

| Deliverable | Package Name | Codename | Repository URL |
| :-: | :-: | :-: | :-: |
| **Wallets** | | | |
| Browser Extension Wallet | nem2-wallet-browserextension | W_Ext | https://github.com/nemfoundation/nem2-wallet-browserextension |
| Hatio RFP (iOS + Android) | nem2-wallet-mobile | W_Mob | N/A |
| Hardware Wallets Integrations | nem2-wallet-hardware | W_Hardware | N/A |
| **Explorers** | | | |
| Node/Block Explorer | nem2-explorer | Explorer | https://gitlab.com/joegeorge/explorer.nem.io/tree/master/server |
| **Faucet** | | | |
| Catapult Faucet | nem2-faucet | Faucet | https://github.com/44uk/nem2-faucet |
| **Command Line** | | | |
| NEM2 CLI | nem2-cli | CLI | https://github.com/nemtech/nem2-cli |
| NEM2 Prototypes | nem2-prototyping-tool | CLI | https://github.com/nemtech/nem2-cli |
| **Documentation** | | | |
| NEM Academy | nem2-curricular-framework | Academy | https://github.com/nemtech/nem2-curricular-framework |
| NEM Developer Center | nem2-docs | DevCenter | https://github.com/nemtech/nem2-docs |

## Protocol Version Compatibilities

### Icon Status Attribution

Following table describes the status attributions for each of the icons that will be used in the protocol features compatibility tables:

| Icon | Status |
| :-: | :-: |
| :question: | Investigation/Research is currently in progress. |
| :white_check_mark: | Feature is available. |
| :o: | Work in Progress (WIP) |
| :stop_sign: | Feature is not available. |
| :negative_squared_cross_mark: | Feature is **not needed**. |

### Elephant: [Protocol v0.5.0.1][server-0501]

| feature | [server@0.5.0.1][server-0501] | [W_Ext@?][wallet-ext] | [W_Mob@?][wallet-mob] | [W_Hardware@?][wallet-hardware] | [Explorer@?][explorer] | [Faucet@?][faucet] | [CLI@?][cli] |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| reset transaction version | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| rename properties to restrictions | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| consensus update PoS+ | :question:  | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| enhanced delegated harvesting | :o:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| metadata key-value| :question: | :o:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |

### Dragon: [Protocol v0.4.0.1][server-0401]

| feature | [server@0.4.0.1][server-0401] | [W_Ext@?][wallet-ext] | [W_Mob@?][wallet-mob] | [W_Hardware@?][wallet-hardware] | [Explorer@?][explorer] | [Faucet@?][faucet] | [CLI@?][cli] |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| hashlock with alias | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| optin cosigners | :white_check_mark: | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| lightning network | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| consensus PoS+ | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| generation hash | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |

### Cow: [Protocol v0.3.0.2][server-0302]

| feature | [server@0.3.0.2][server-0302] | [W_Ext@?][wallet-ext] | [W_Mob@?][wallet-mob] | [W_Hardware@?][wallet-hardware] | [Explorer@?][explorer] | [Faucet@?][faucet] | [CLI@?][cli] |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| catbuffer | :white_check_mark:  | :stop_sign:  | :stop_sign:  |  :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| mosaic/namespace split | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| aliases | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| receipts | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| account props | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| fees | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| delegated harvesting | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| cow DTOs | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign:  |  :stop_sign: | :stop_sign: | :stop_sign: |
| secret locks hash algos | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| hashlock | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| merkle proofs | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |

## History

| **Date**      | **Version**     |
| ------------- | --------------- |
| Jul 14 2019   | Initial Draft   |

[server-0501]: https://github.com/nemtech/catapult-server/releases/tag/v0.5.0.1
[server-0401]: https://github.com/nemtech/catapult-server/releases/tag/v0.4.0.1
[server-0302]: https://github.com/nemtech/catapult-server/releases/tag/v0.3.0.2
[wallet-extension]: https://github.com/nemfoundation/nem2-wallet-browserextension
[wallet-mobile]: #
[wallet-hardware]: #
[explorer]: https://gitlab.com/joegeorge/explorer.nem.io/tree/master/server
[faucet]: https://github.com/44uk/nem2-faucet
[cli]: https://github.com/nemtech/nem2-cli
