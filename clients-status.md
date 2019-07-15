# Clients Protocol Compatibility

## Table of contents

- [Abstract](#abstract)
- [Client Applications](#client-applications)
- [Features Compatibilities](#features-compatibilities)
  - [Icon Status Attribution](#icon-status-attribution)
  - [Browser Extension Wallet](#browser-extension-wallet)
  - [Desktop Wallet](#desktop-wallet)
  - [Mobile Wallet](#mobile-wallet)
  - [Hardware Wallets](#hardware-wallets)
  - [Explorer](#explorer)
  - [Faucet](#faucet)
  - [Command Line Interface](#command-line-interface)
- [History](#history)	

## Abstract

This document aims to group technical features of Milestones in the Catapult Protocol Development project and assess/update status reports about specific **Clients** compatibility.

The document should provide with an easy aggregation of all features addressed in the protocol project during milestones development and should provide a clear compatibility table for individual protocol features / or changes.

## Client Applications

Following client applications are taken into account for this compatibility status update:

| Deliverable | Package Name | Codename | Repository URL |
| :-: | :-: | :-: | :-: |
| **Wallets** | | | |
| Browser Extension Wallet | nem2-wallet-browserextension | W_Ext | [nem2-wallet-browserextension][wallet-extension] |
| Desktop Wallet | nem2-desktop-wallet | W_Desk | [nem2-desktop-wallet][wallet-desktop] |
| Mobile Wallet | nem2-mobile-wallet | W_Mob | [nem2-mobile-wallet][wallet-mobile]
| Hatio RFP (iOS + Android) | nem2-wallet-mobile | W_RFP | N/A |
| Hardware Wallets Integrations | nem2-wallet-hardware | W_Hardware | N/A |
| **Explorers** | | | |
| Node/Block Explorer | nem2-explorer | Explorer | [nem2-explorer][explorer] |
| **Faucet** | | | |
| Catapult Faucet | nem2-faucet | Faucet | [nem2-faucet][faucet] |
| **Command Line** | | | |
| NEM2 CLI | nem2-cli | CLI | [nem2-cli][cli] |
| **Documentation** | | | |
| NEM Academy | nem2-curricular-framework | Academy | [nem2-curricular-framework][doc-curricular] |
| NEM Developer Center | nem2-docs | DevCenter | [nem2-docs][doc-devcenter] |

## Features Compatibilities

### Icon Status Attribution

Following table describes the status attributions for each of the icons that will be used in the protocol features compatibility tables:

| Icon | Status |
| :-: | :-: |
| :question: | Investigation/Research is currently in progress. |
| :white_check_mark: | Feature is available. |
| :o: | Work in Progress (WIP) |
| :stop_sign: | Feature is not available. |
| :negative_squared_cross_mark: | Feature is **not needed**. |

### Browser Extension Wallet

The Browser Extension Wallet project is the object of [NIP-5][nip-5]. The source code for this Software Package can be found at:

    [nem2-wallet-browserextension][wallet-extension]

#### Stories

| User Story | Integration Status |
| :-: | :-: |
| **Accounts** | |
| User can create new account | :white_check_mark: |
| User can create new HD account | :stop_sign: |
| User can create multiple accounts | :white_check_mark: |
| User can name accounts | :white_check_mark: |
| User can import private key | :white_check_mark: |
| User can import pass phrase | :stop_sign: |
| User can export private key | :white_check_mark: |
| User can export pass phrase | :stop_sign: |
| User can link account (harvesting) | :white_check_mark: |
| Private key / Pass phrase storage is secure | :stop_sign: |
| | |
| **Data Services** | |
| User can view mosaic balances | :white_check_mark: |
| User can view transaction history | :white_check_mark: |
| User can view transaction details | :white_check_mark: |
| User can view mosaic alias info | :white_check_mark: |
| User can view account alias info | :stop_sign: |
| User can view block data | :stop_sign: |
| User can view receipts data | :stop_sign: |
| User is notified about transactions | :white_check_mark: |
| User is notified about pending co-sigs | :stop_sign: |
| User can export transaction history | :stop_sign: |
| User can switch network _node_ | :white_check_mark: |
| User can switch _network_ | :white_check_mark: |
| | |
| **Usability** | |
| User can read QR Code | :stop_sign: |
| User can export Account with QR Code | :white_check_mark: |
| User can export Transaction with QR Code (Invoices) | :stop_sign: |
| User can switch _language_ | :stop_sign: |
| User can use aliases for Mosaics | :stop_sign: |
| User can use aliases for Accounts | :stop_sign: |
| | |
| **Transactions** | |
| _User can issue Transaction URI*_ | :white_check_mark: |
| User can specify transaction MAX_FEE | :white_check_mark: |
| User can issue Transfer without message | :white_check_mark: |
| User can issue Transfer with message | :white_check_mark: |
| User can issue Transfer with encrypted message | :o: |
| User can issue Alias for mosaic | :white_check_mark: |
| User can issue Alias for account | :stop_sign: |
| User can issue Aggregate Complete with multiple transfers | :stop_sign: |
| User can issue Aggregate Complete with custom transactions | :stop_sign: |
| User can issue Cosignature | :stop_sign: |
| User can issue Register Namespace | :stop_sign: |
| User can issue Mosaic Definition | :stop_sign: |
| User can issue Mosaic Supply Change | :stop_sign: |
| User can issue Secret Lock | :stop_sign: |
| User can issue Secret Proof | :stop_sign: |
| User can issue Hash Lock | :stop_sign: |
| User can issue Secret Lock | :stop_sign: |
| User can issue Multisig Account Modification | :white_check_mark: |
| User can issue Multisig Cosignatory Modification | :white_check_mark: |
| Multisig Account Modification requires opt-in | :stop_sign: |
| Multisig Cosignatory Modification requires opt-in | :stop_sign: |
| User can issue Account Address Restriction | :white_check_mark: |
| User can issue Account Mosaic Restriction | :white_check_mark: |
| User can issue Account Operation Restriction | :white_check_mark: |

* **Due to the possibility of issuing Transaction URI, in fact any transaction type can be issued. Each transaction type is listed as to determine whether there is _screen to prepare_ said transaction types.**

### Desktop Wallet

The Desktop Wallet project is being worked on by a team in the foundation. The source code for this Software Package can be found at:

    [nem2-desktop-wallet][wallet-desktop]

#### Stories

| User Story | Integration Status |
| :-: | :-: |
| **Accounts** | |
| User can create new account | :stop_sign: |
| User can create new HD account | :stop_sign: |
| User can create multiple accounts | :stop_sign: |
| User can name accounts | :stop_sign: |
| User can import private key | :stop_sign: |
| User can import pass phrase | :stop_sign: |
| User can export private key | :stop_sign: |
| User can export pass phrase | :stop_sign: |
| User can link account (harvesting) | :stop_sign: |
| Private key / Pass phrase storage is secure | :stop_sign: |
| | |
| **Data Services** | |
| User can view mosaic balances | :stop_sign: |
| User can view transaction history | :stop_sign: |
| User can view transaction details | :stop_sign: |
| User can view mosaic alias info | :stop_sign: |
| User can view account alias info | :stop_sign: |
| User can view block data | :stop_sign: |
| User can view receipts data | :stop_sign: |
| User is notified about transactions | :stop_sign: |
| User is notified about pending co-sigs | :stop_sign: |
| User can export transaction history | :stop_sign: |
| User can switch network _node_ | :stop_sign: |
| User can switch _network_ | :stop_sign: |
| | |
| **Usability** | |
| User can read QR Code | :stop_sign: |
| User can export Account with QR Code | :stop_sign: |
| User can export Transaction with QR Code (Invoices) | :stop_sign: |
| User can switch _language_ | :stop_sign: |
| User can use aliases for Mosaics | :stop_sign: |
| User can use aliases for Accounts | :stop_sign: |
| | |
| **Transactions** | |
| _User can issue Transaction URI*_ | :stop_sign: |
| User can specify transaction MAX_FEE | :stop_sign: |
| User can issue Transfer without message | :stop_sign: |
| User can issue Transfer with message | :stop_sign: |
| User can issue Transfer with encrypted message | :stop_sign: |
| User can issue Alias for mosaic | :stop_sign: |
| User can issue Alias for account | :stop_sign: |
| User can issue Aggregate Complete with multiple transfers | :stop_sign: |
| User can issue Aggregate Complete with custom transactions | :stop_sign: |
| User can issue Cosignature | :stop_sign: |
| User can issue Register Namespace | :stop_sign: |
| User can issue Mosaic Definition | :stop_sign: |
| User can issue Mosaic Supply Change | :stop_sign: |
| User can issue Secret Lock | :stop_sign: |
| User can issue Secret Proof | :stop_sign: |
| User can issue Hash Lock | :stop_sign: |
| User can issue Secret Lock | :stop_sign: |
| User can issue Multisig Account Modification | :stop_sign: |
| User can issue Multisig Cosignatory Modification | :stop_sign: |
| Multisig Account Modification requires opt-in | :stop_sign: |
| Multisig Cosignatory Modification requires opt-in | :stop_sign: |
| User can issue Account Address Restriction | :stop_sign: |
| User can issue Account Mosaic Restriction | :stop_sign: |
| User can issue Account Operation Restriction | :stop_sign: |

### Mobile Wallet

The Mobile Wallet project is being worked on by a team in the foundation. The source code for this Software Package can be found at:

    [nem2-mobile-wallet][wallet-mobile]

#### Stories

| User Story | Integration Status |
| :-: | :-: |
| **Accounts** | |
| User can create new account | :stop_sign: |
| User can create new HD account | :stop_sign: |
| User can create multiple accounts | :stop_sign: |
| User can name accounts | :stop_sign: |
| User can import private key | :stop_sign: |
| User can import pass phrase | :stop_sign: |
| User can export private key | :stop_sign: |
| User can export pass phrase | :stop_sign: |
| User can link account (harvesting) | :stop_sign: |
| Private key / Pass phrase storage is secure | :stop_sign: |
| | |
| **Data Services** | |
| User can view mosaic balances | :stop_sign: |
| User can view transaction history | :stop_sign: |
| User can view transaction details | :stop_sign: |
| User can view mosaic alias info | :stop_sign: |
| User can view account alias info | :stop_sign: |
| User can view block data | :stop_sign: |
| User can view receipts data | :stop_sign: |
| User is notified about transactions | :stop_sign: |
| User is notified about pending co-sigs | :stop_sign: |
| User can export transaction history | :stop_sign: |
| User can switch network _node_ | :stop_sign: |
| User can switch _network_ | :stop_sign: |
| | |
| **Usability** | |
| User can read QR Code | :stop_sign: |
| User can export Account with QR Code | :stop_sign: |
| User can export Transaction with QR Code (Invoices) | :stop_sign: |
| User can switch _language_ | :stop_sign: |
| User can use aliases for Mosaics | :stop_sign: |
| User can use aliases for Accounts | :stop_sign: |
| | |
| **Transactions** | |
| _User can issue Transaction URI*_ | :stop_sign: |
| User can specify transaction MAX_FEE | :stop_sign: |
| User can issue Transfer without message | :stop_sign: |
| User can issue Transfer with message | :stop_sign: |
| User can issue Transfer with encrypted message | :stop_sign: |
| User can issue Alias for mosaic | :stop_sign: |
| User can issue Alias for account | :stop_sign: |
| User can issue Aggregate Complete with multiple transfers | :stop_sign: |
| User can issue Aggregate Complete with custom transactions | :stop_sign: |
| User can issue Cosignature | :stop_sign: |
| User can issue Register Namespace | :stop_sign: |
| User can issue Mosaic Definition | :stop_sign: |
| User can issue Mosaic Supply Change | :stop_sign: |
| User can issue Secret Lock | :stop_sign: |
| User can issue Secret Proof | :stop_sign: |
| User can issue Hash Lock | :stop_sign: |
| User can issue Secret Lock | :stop_sign: |
| User can issue Multisig Account Modification | :stop_sign: |
| User can issue Multisig Cosignatory Modification | :stop_sign: |
| Multisig Account Modification requires opt-in | :stop_sign: |
| Multisig Cosignatory Modification requires opt-in | :stop_sign: |
| User can issue Account Address Restriction | :stop_sign: |
| User can issue Account Mosaic Restriction | :stop_sign: |
| User can issue Account Operation Restriction | :stop_sign: |

### Hardware Wallets

The Hardware Wallets project is **currently not assigned**. There is no resources available for this project as of time of writing.

#### Stories

| User Story | Integration Status |
| :-: | :-: |
| **Accounts** | |
| User can create new account | :stop_sign: |
| User can create new HD account | :stop_sign: |
| User can create multiple accounts | :stop_sign: |
| User can name accounts | :stop_sign: |
| User can import private key | :stop_sign: |
| User can import pass phrase | :stop_sign: |
| User can export private key | :stop_sign: |
| User can export pass phrase | :stop_sign: |
| User can link account (harvesting) | :stop_sign: |
| Private key / Pass phrase storage is secure | :stop_sign: |
| | |
| **Data Services** | |
| User can view mosaic balances | :stop_sign: |
| User can view transaction history | :stop_sign: |
| User can view transaction details | :stop_sign: |
| User can view mosaic alias info | :stop_sign: |
| User can view account alias info | :stop_sign: |
| User can view block data | :stop_sign: |
| User can view receipts data | :stop_sign: |
| User is notified about transactions | :stop_sign: |
| User is notified about pending co-sigs | :stop_sign: |
| User can export transaction history | :stop_sign: |
| User can switch network _node_ | :stop_sign: |
| User can switch _network_ | :stop_sign: |
| | |
| **Usability** | |
| User can read QR Code | :stop_sign: |
| User can export Account with QR Code | :stop_sign: |
| User can export Transaction with QR Code (Invoices) | :stop_sign: |
| User can switch _language_ | :stop_sign: |
| User can use aliases for Mosaics | :stop_sign: |
| User can use aliases for Accounts | :stop_sign: |
| | |
| **Transactions** | |
| _User can issue Transaction URI*_ | :stop_sign: |
| User can specify transaction MAX_FEE | :stop_sign: |
| User can issue Transfer without message | :stop_sign: |
| User can issue Transfer with message | :stop_sign: |
| User can issue Transfer with encrypted message | :stop_sign: |
| User can issue Alias for mosaic | :stop_sign: |
| User can issue Alias for account | :stop_sign: |
| User can issue Aggregate Complete with multiple transfers | :stop_sign: |
| User can issue Aggregate Complete with custom transactions | :stop_sign: |
| User can issue Cosignature | :stop_sign: |
| User can issue Register Namespace | :stop_sign: |
| User can issue Mosaic Definition | :stop_sign: |
| User can issue Mosaic Supply Change | :stop_sign: |
| User can issue Secret Lock | :stop_sign: |
| User can issue Secret Proof | :stop_sign: |
| User can issue Hash Lock | :stop_sign: |
| User can issue Secret Lock | :stop_sign: |
| User can issue Multisig Account Modification | :stop_sign: |
| User can issue Multisig Cosignatory Modification | :stop_sign: |
| Multisig Account Modification requires opt-in | :stop_sign: |
| Multisig Cosignatory Modification requires opt-in | :stop_sign: |
| User can issue Account Address Restriction | :stop_sign: |
| User can issue Account Mosaic Restriction | :stop_sign: |
| User can issue Account Operation Restriction | :stop_sign: |

### Explorer

The Explorer project is being worked on by a team in the foundation. The source code for this Software Package can be found at:

    [nem2-explorer][explorer]

#### Stories

| User Story | Integration Status |
| :-: | :-: |
| User can view account balances | :stop_sign: |
| User can view transaction history | :stop_sign: |
| User can view transaction details | :stop_sign: |
| User can view mosaic alias info | :stop_sign: |
| User can view account alias info | :stop_sign: |
| User can view block history | :stop_sign: |
| User can view receipts data | :stop_sign: |
| User can export transaction history | :stop_sign: |
| User can view network nodes | :stop_sign: |
| User can view node version | :stop_sign: |
| User can view beneficiary info | :stop_sign: |
| | |
| **Transactions** | |
| User can view Transfer without message | :stop_sign: |
| User can view Transfer with message | :stop_sign: |
| User can view Transfer with encrypted message | :stop_sign: |
| User can view Alias for mosaic | :stop_sign: |
| User can view Alias for account | :stop_sign: |
| User can view Aggregate Complete with multiple transfers | :stop_sign: |
| User can view Aggregate Complete with custom transactions | :stop_sign: |
| User can view Cosignature | :stop_sign: |
| User can view Register Namespace | :stop_sign: |
| User can view Mosaic Definition | :stop_sign: |
| User can view Mosaic Supply Change | :stop_sign: |
| User can view Secret Lock | :stop_sign: |
| User can view Secret Proof | :stop_sign: |
| User can view Hash Lock | :stop_sign: |
| User can view Secret Lock | :stop_sign: |
| User can view Multisig Account Modification | :stop_sign: |
| User can view Multisig Cosignatory Modification | :stop_sign: |
| User can view Account Address Restriction | :stop_sign: |
| User can view Account Mosaic Restriction | :stop_sign: |
| User can view Account Operation Restriction | :stop_sign: |

### Faucet

The Faucet project was released by a community member. The source code for this Software Package can be found at:

    [nem2-faucet][faucet]

#### Stories

| User Story | Integration Status |
| :-: | :-: |
| User can request **currency** mosaic amount | :white_check_mark: |
| User can request custom mosaic amount | :white_check_mark: |
| User can install faucet on owned server | :white_check_mark: |
| User can specify custom mosaic faucet | :white_check_mark: |
| User can specify custom network faucet | :white_check_mark: |
| User can change amount settings | :white_check_mark: |
| User is confirmed with Captcha (no-bots) | :white_check_mark: |
| User can send link to send faucet coins | :stop_sign: |
| User can specify transaction MAX_FEE | :stop_sign: |

### Command Line Interface

The nem2-cli project is being worked on by a team in the foundation. The source code for this Software Package can be found at:

    [nem2-cli][cli]

#### Stories

| User Story | Integration Status |
| :-: | :-: |
| **Accounts** | |
| User can create new account | :white_check_mark: |
| User can create new HD account | :stop_sign: |
| User can create multiple accounts | :white_check_mark: |
| User can name accounts | :white_check_mark: |
| User can import private key | :white_check_mark: |
| User can import pass phrase | :stop_sign: |
| User can export private key | :stop_sign: |
| User can export pass phrase | :stop_sign: |
| User can link account (harvesting) | :stop_sign: |
| Private key / Pass phrase storage is secure | :stop_sign: |
| | |
| **Data Services** | |
| User can view mosaic balances | :white_check_mark: |
| User can view transaction history | :white_check_mark: |
| User can view transaction details | :white_check_mark: |
| User can view mosaic alias info | :white_check_mark: |
| User can view account alias info | :white_check_mark: |
| User can view block data | :white_check_mark: |
| User can view receipts data | :stop_sign: |
| User is notified about transactions | :stop_sign: |
| User is notified about pending co-sigs | :stop_sign: |
| User can export transaction history | :stop_sign: |
| User can switch network _node_ | :stop_sign: |
| User can switch _network_ | :white_check_mark: |
| | |
| **Usability** | |
| User can read QR Code | :stop_sign: |
| User can export Account with QR Code | :stop_sign: |
| User can export Transaction with QR Code (Invoices) | :stop_sign: |
| User can switch _language_ | :stop_sign: |
| User can use aliases for Mosaics | :white_check_mark: |
| User can use aliases for Accounts | :white_check_mark: |
| | |
| **Transactions** | |
| _User can issue Transaction URI*_ | :white_check_mark: |
| User can specify transaction MAX_FEE | :stop_sign: |
| User can issue Transfer without message | :white_check_mark: |
| User can issue Transfer with message | :white_check_mark: |
| User can issue Transfer with encrypted message | :stop_sign: |
| User can issue Alias for mosaic | :white_check_mark: |
| User can issue Alias for account | :white_check_mark: |
| User can issue Aggregate Complete with multiple transfers | :stop_sign: |
| User can issue Aggregate Complete with custom transactions | :stop_sign: |
| User can issue Cosignature | :white_check_mark: |
| User can issue Register Namespace | :white_check_mark: |
| User can issue Mosaic Definition | :white_check_mark: |
| User can issue Mosaic Supply Change | :white_check_mark: |
| User can issue Secret Lock | :stop_sign: |
| User can issue Secret Proof | :stop_sign: |
| User can issue Hash Lock | :stop_sign: |
| User can issue Secret Lock | :stop_sign: |
| User can issue Multisig Account Modification | :stop_sign: |
| User can issue Multisig Cosignatory Modification | :stop_sign: |
| Multisig Account Modification requires opt-in | :stop_sign: |
| Multisig Cosignatory Modification requires opt-in | :stop_sign: |
| User can issue Account Address Restriction | :stop_sign: |
| User can issue Account Mosaic Restriction | :stop_sign: |
| User can issue Account Operation Restriction | :stop_sign: |

* **Due to the possibility of issuing Transaction URI, in fact any transaction type can be issued. Each transaction type is listed as to determine whether there is _screen to prepare_ said transaction types.**

## History

| **Date**      | **Version**     |
| ------------- | --------------- |
| Jul 14 2019   | Initial Draft   |

[server-0501]: https://github.com/nemtech/catapult-server/releases/tag/v0.5.0.1
[server-0401]: https://github.com/nemtech/catapult-server/releases/tag/v0.4.0.1
[server-0302]: https://github.com/nemtech/catapult-server/releases/tag/v0.3.0.2
[wallet-extension]: https://github.com/nemfoundation/nem2-wallet-browserextension
[wallet-desktop]: https://github.com/NemTechCN/NEM2_Desktop_Wallet_CN
[wallet-mobile]: https://github.com/NemTechCN/nem2-mwallet-CN
[wallet-rfp]: #
[wallet-hardware]: #
[explorer]: https://gitlab.com/joegeorge/explorer.nem.io/tree/master/server
[faucet]: https://github.com/44uk/nem2-faucet
[cli]: https://github.com/nemtech/nem2-cli
[doc-curricular]: https://github.com/nemtech/nem2-curricular-framework
[doc-devcenter]: https://github.com/nemtech/nem2-docs
[nip-5]: https://github.com/nemtech/NIP/blob/master/NIPs/nip-0005.md
