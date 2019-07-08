# Projects & SDK Protocol Compatibility

## Table of contents

- [Abstract](#abstract)
- [Protocol Version Compatibilities](#protocol-version-compatibilities)
  - [Icon Status Attribution](#icon-status-attribution)
  - [Elephant: Protocol v0.5.?.?](#elephant-protocol-v05)
  - [Dragon: Protocol v0.4.?.?](#dragon-protocol-v04)
  - [Cow: Protocol v0.3.0.2](#cow-protocol-v0302)
- [Projects Status Updates](#projects-status-updates)
- [History](#history)	

## Abstract

This document aims to group technical features of Milestones in the Catapult Protocol Development project and assess/update status reports about specific Software Development Kits compatibility.

The document should provide with an easy aggregation of all features addressed in the protocol project during milestones development and should provide a clear compatibility table for individual protocol features / or changes.

## Protocol Version Compatibilities

### Icon Status Attribution

Following table describes the status attributions for each of the icons that will be used in the protocol features compatibility tables:

| Icon | Status |
| :-: | :-: |
| :question: | Investigation/Research is currently in progress. |
| :white_check_mark: | Feature is available. |
| :o: | Work in Progress (WIP) |
| :stop_sign: | Feature is not available. |

### Elephant: [Protocol v0.5.0.1](https://github.com/nemtech/catapult-server/releases/tag/v0.5.0.1)

| feature | [server@0.5.0.1](https://github.com/nemtech/catapult-server/releases/tag/v0.5.0.1) | [rest@0.7.15](https://github.com/nemtech/catapult-rest/releases/tag/v0.7.15) | [sdk-js@0.13.0](https://github.com/nemtech/nem2-sdk-typescript-javascript/releases/tag/v0.13.0) | sdk-java@? | sdk-python@? | sdk-unity@? | sdk-php@? |
| :-: |:-: | :-: | :-: | :-: | :-: | :-: | :-: |
| reset transaction version | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| rename properties to restrictions | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| consensus update PoS+ | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| mosaic restrictions| :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| enhanced delegated harvesting | :o:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| metadata key-value| :o:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |

### Dragon: [Protocol v0.4.0.1](https://github.com/nemtech/catapult-server/releases/tag/v0.4.0.1)

| feature | [server@0.4.0.1](https://github.com/nemtech/catapult-server/releases/tag/v0.4.0.1) | [rest@0.7.15](https://github.com/nemtech/catapult-rest/releases/tag/v0.7.15) | [sdk-js@0.12.4](https://github.com/nemtech/nem2-sdk-typescript-javascript/releases/tag/v0.12.4) | sdk-java@? | sdk-python@? | sdk-unity@? | sdk-php@? |
| :-: |:-: | :-: | :-: | :-: | :-: | :-: | :-: |
| hashlock with alias | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign: | :stop_sign: | :stop_sign: |
| optin cosigners | :white_check_mark: | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign: | :stop_sign: | :stop_sign: |
| lightning network | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| consensus PoS+ | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |
| generation hash | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign: | :stop_sign: | :stop_sign: |
| dragon DTOs | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign: | :stop_sign: | :stop_sign: |
| secret proof recipient | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign: | :stop_sign: | :stop_sign: |

### Cow: [Protocol v0.3.0.2](https://github.com/nemtech/catapult-server/releases/tag/v0.3.0.2)

| feature | [server@0.3.0.2](https://github.com/nemtech/catapult-server/releases/tag/v0.3.0.2) | [rest@0.7.14](https://github.com/nemtech/catapult-rest/releases/tag/v0.7.14) | [sdk-js@0.11.6](https://github.com/nemtech/nem2-sdk-typescript-javascript/releases/tag/v0.11.6) | [sdk-java@0.11-alpha](https://github.com/nemtech/nem2-sdk-java/releases/tag/v0.11-alpha) | sdk-python@? | sdk-unity@? | sdk-php@? |
| :-: |:-: | :-: | :-: | :-: | :-: | :-: | :-: |
| catbuffer | :white_check_mark:  | :stop_sign:  | :o:  |  :white_check_mark: | :stop_sign: | :stop_sign: | :stop_sign: |
| mosaic/namespace split | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark: | :stop_sign: | :stop_sign: |
| aliases | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark: | :stop_sign: | :stop_sign: |
| receipts | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark: | :stop_sign: | :stop_sign: | :stop_sign: |
| account props | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign: | :stop_sign: | :stop_sign: |
| fees | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark: | :o: | :stop_sign: | :stop_sign: |
| delegated harvesting | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign: | :stop_sign: | :stop_sign: |
| cow DTOs | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  |  :o: | :stop_sign: | :stop_sign: |
| secret locks hash algos | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign: | :stop_sign: | :stop_sign: |
| hashlock | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :o: | :stop_sign: | :stop_sign: |
| merkle proofs | :white_check_mark:  | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: |

## Projects Status Updates

Following table describes status updates of Projects grouped in different _special interest groups_ as defined in following repository:

  - https://github.com/nemtech/community

| Project | Milestone | Version Tag |
| :-:  | :-: | :-: |
|**SIG-api** | | |
| [catapult-server](https://github.com/nemtech/catapult-server) | Dragon | [v0.4.0.1](https://github.com/nemtech/catapult-server/releases/tag/v0.4.0.1) |
| [catapult-rest](https://github.com/nemtech/catapult-server) | Dragon | [v0.7.15](https://github.com/nemtech/catapult-rest/releases/tag/v0.7.15) |
| [catbuffer](https://github.com/nemtech/catbuffer) | Cow | N/A |
| [nem2-library-js](https://github.com/nemtech/nem2-library-js) | Cow+, **Deprecated** | [v0.10.2](https://github.com/nemtech/nem2-library-js/releases/tag/v0.10.2) |
| [nem2-sdk-typescript-javascript](https://github.com/nemtech/nem2-sdk-typescript-javascript) | Elephant | [v0.13.0](https://github.com/nemtech/nem2-sdk-typescript-javascript/releases/tag/v0.13.0) |
| [nem2-sdk-java](https://github.com/nemtech/nem2-sdk-java) | Cow | [v0.11-alpha](https://github.com/nemtech/nem2-sdk-java/releases/tag/v0.11-alpha) |
| [nem2-sdk-csharp](https://github.com/nemtech/nem2-sdk-csharp) | Alpaca | N/A |
|**SIG-client** | | |
| [nem2-cli](https://github.com/nemtech/nem2-cli) | Dragon | [v0.12.1](https://github.com/nemtech/nem2-cli/releases/tag/v0.12.1) |
| [nem2-prototyping-tool](https://github.com/nemtech/nem2-prototyping-tool) | Alpaca | N/A | Depends on SDK update.|
|**SIG-docs** | | |
| [nem2-docs](https://github.com/nemtech/nem2-docs) | Dragon | [v0.17.6](https://github.com/nemtech/nem2-docs/releases/tag/v0.17.6) |
| [nem2-curricular-framework](https://github.com/nemtech/nem2-curricular-framework) | Alpaca | N/A|
| [nem2-workshop-nem-applied-to-supply-chain](https://github.com/nemtech/nem2-workshop-nem-applied-to-supply-chain) | Cow | N/A |
| [nem2-workshop-document-notarization](https://github.com/nemtech/nem2-workshop-document-notarization) | Cow |  N/A |
|**SIG-testing** | | |
| [nem2-scenarios](https://github.com/nemtech/nem2-scenarios) | Cow | N/A |
| [test-vectors](https://github.com/nemtech/test-vectors) | N/A | N/A |
|**SIG-tooling-infra** | | |
| [catapult-service-bootstrap](https://github.com/nemtech/catapult-service-bootstrap) | Cow | [v0.3.0](https://github.com/tech-bureau/catapult-service-bootstrap/releases/tag/v0.3.0) |
| [nem2-camel](https://github.com/nemtech/nem2-camel) | N/A | N/A |
| [nf-catapult-testnet-node](https://github.com/nemfoundation/nf-catapult-testnet-node/tree/testnet-node) | Elephant | [latest](https://github.com/nemfoundation/nf-catapult-testnet-node/tree/elephant) |

## History

| **Date**      | **Version**     |
| ------------- | --------------- |
| Apr 25 2019   | Initial Draft   |
| Jun 06 2019   | Dragon Update   |
| Jul 03 2019   | Elephant Update |
