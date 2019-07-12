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

### Elephant: [Protocol v0.5.0.1][server-0501]

| feature | [server@0.5.0.1][server-0501] | [rest@0.7.15][rest-0715] | [sdk-js@0.13.0][sdk-ts-0130] | [sdk-java@?][sdk-java] | [sdk-python@?][sdk-python] | [sdk-unity@?][sdk-unity] | [sdk-php@?][sdk-php] | [sdk-swift@?][sdk-swift] |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| reset transaction version | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| rename properties to restrictions | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| consensus update PoS+ | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| mosaic restrictions| :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| enhanced delegated harvesting | :o:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| metadata key-value| :o:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |

### Dragon: [Protocol v0.4.0.1][server-0401]

| feature | [server@0.4.0.1][server-0401] | [rest@0.7.15][rest-0715] | [sdk-js@0.12.4][sdk-ts-0124] | [sdk-java@?][sdk-java] | [sdk-python@?][sdk-python] | [sdk-unity@?][sdk-unity] | [sdk-php@?][sdk-php] | [sdk-swift@?][sdk-swift] |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| hashlock with alias | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| optin cosigners | :white_check_mark: | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| lightning network | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| consensus PoS+ | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| generation hash | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| dragon DTOs | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| secret proof recipient | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |

### Cow: [Protocol v0.3.0.2][server-0302]

| feature | [server@0.3.0.2][server-0302] | [rest@0.7.14][rest-0714] | [sdk-js@0.11.6][sdk-ts-0116] | [sdk-java@0.11-alpha][sdk-java-0110] | [sdk-python@?][sdk-python] | [sdk-unity@?][sdk-unity] | [sdk-php@?][sdk-php] | [sdk-swift@?][sdk-swift] |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| catbuffer | :white_check_mark:  | :stop_sign:  | :o:  |  :white_check_mark: | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| mosaic/namespace split | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark: | :stop_sign: | :stop_sign: | :stop_sign: |
| aliases | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark: | :stop_sign: | :stop_sign: | :stop_sign: |
| receipts | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark: | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| account props | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| fees | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark: | :o: | :stop_sign: | :stop_sign: | :stop_sign: |
| delegated harvesting | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| cow DTOs | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  |  :o: | :stop_sign: | :stop_sign: | :stop_sign: |
| secret locks hash algos | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |
| hashlock | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :white_check_mark:  | :o: | :stop_sign: | :stop_sign: | :stop_sign: |
| merkle proofs | :white_check_mark:  | :white_check_mark:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: |

## Projects Status Updates

Following table describes status updates of Projects grouped in different _special interest groups_ as defined in following repository:

  - https://github.com/nemtech/community

| Project | Milestone | Version Tag |
| :-:  | :-: | :-: |
|**SIG-api** | | |
| [catapult-server][git-server] | Elephant | [v0.5.0.1][server-0501] |
| [catapult-rest][git-rest] | Elephant | [v0.7.15][rest-0715] |
| [catbuffer][git-catbuffer] | Elephant | [`master`][git-catbuffer] |
| [nem2-sdk-typescript-javascript][sdk-ts] | Elephant | [v0.13.0][sdk-ts-0130] |
| [nem2-sdk-java][sdk-java] | Cow | [v0.11-alpha][sdk-java-0110] |
| [nem2-sdk-csharp][sdk-csharp] | Alpaca | [`master`][sdk-csharp] |
| [nem2-sdk-python][sdk-python] | Cow | [`master`][sdk-python] |
| [nem2-sdk-php][sdk-php] | Cow | [`master`][sdk-php] |
| [nem2-sdk-unity][sdk-unity] | Cow | [`master`][sdk-unity] |
| [nem2-sdk-swift][sdk-swift] | Dragon | [`master`][sdk-swift] |
|**SIG-client** | | |
| [nem2-cli][git-cli] | Elephant | [v0.13.0][git-cli-0130] |
| [nem2-prototyping-tool][git-prototyping] | Alpaca | N/A | Depends on SDK update. |
|**SIG-docs** | | |
| [nem2-docs][git-docs] | Dragon | [v0.17.6][git-docs-0176] |
| [nem2-curricular-framework][git-curricular] | Alpaca | N/A|
| [nem2-workshop-nem-applied-to-supply-chain][workshop-supplychain] | Cow | N/A |
| [nem2-workshop-document-notarization][workshop-notary] | Cow |  N/A |
|**SIG-testing** | | |
| [nem2-scenarios][git-scenarios] | Cow | N/A |
| [test-vectors][test-vectors] | N/A | N/A |
|**SIG-tooling-infra** | | |
| [catapult-service-bootstrap][git-bootstrap] | Elephant | [`master`][git-bootstrap] |
| [nem2-camel][git-camel] | N/A | N/A |
| [nem2-library-js][git-library] | Dragon | :warning: **Deprecated** [v0.10.2][git-library-0102] |
| [nf-catapult-testnet-node][git-nf-testnet] | Elephant | [latest][git-nf-testnet] |

## History

| **Date**      | **Version**     |
| ------------- | --------------- |
| Apr 25 2019   | Initial Draft   |
| Jun 06 2019   | Dragon Update   |
| Jul 03 2019   | Elephant Update |
| Jul 12 2019   | Projects Update |

[server-0501]: https://github.com/nemtech/catapult-server/releases/tag/v0.5.0.1
[server-0401]: https://github.com/nemtech/catapult-server/releases/tag/v0.4.0.1
[server-0302]: https://github.com/nemtech/catapult-server/releases/tag/v0.3.0.2
[rest-0715]: https://github.com/nemtech/catapult-rest/releases/tag/v0.7.15
[rest-0714]: https://github.com/nemtech/catapult-rest/releases/tag/v0.7.14
[sdk-ts]: https://github.com/nemtech/nem2-sdk-typescript-javascript
[sdk-ts-0130]: https://github.com/nemtech/nem2-sdk-typescript-javascript/releases/tag/v0.13.0
[sdk-ts-0124]: https://github.com/nemtech/nem2-sdk-typescript-javascript/releases/tag/v0.12.4
[sdk-ts-0116]: https://github.com/nemtech/nem2-sdk-typescript-javascript/releases/tag/v0.11.6
[sdk-java]: https://github.com/nemtech/nem2-sdk-java
[sdk-java-0110]: https://github.com/nemtech/nem2-sdk-java/releases/tag/v0.11-alpha
[sdk-python]: https://gitlab.com/Alexhuszagh/nem2-sdk-python/tree/master
[sdk-unity]: #
[sdk-php]: https://github.com/VistResearch/nem2-sdk-php
[sdk-swift]: https://github.com/ryuta46/nem2-sdk-swift
[sdk-csharp]: https://github.com/nemtech/nem2-sdk-csharp
[git-server]: https://github.com/nemtech/catapult-server
[git-rest]: https://github.com/nemtech/catapult-rest
[git-catbuffer]: https://github.com/nemtech/catbuffer
[git-cli]: https://github.com/nemtech/nem2-cli
[git-cli-0130]: https://github.com/nemtech/nem2-cli/releases/tag/v0.13.0
[git-prototyping]: https://github.com/nemtech/nem2-prototyping-tool
[git-docs]: https://github.com/nemtech/nem2-docs
[git-docs-0176]: https://github.com/nemtech/nem2-docs/releases/tag/v0.17.6
[git-curricular]: https://github.com/nemtech/nem2-curricular-framework
[git-scenarios]: https://github.com/nemtech/nem2-scenarios
[git-bootstrap]: https://github.com/nemtech/catapult-service-bootstrap
[git-camel]: https://github.com/nemtech/nem2-camel
[git-nf-testnet]: https://github.com/nemfoundation/nf-catapult-testnet-node/tree/testnet-node
[git-library]: https://github.com/nemtech/nem2-library-js
[git-library-0102]: https://github.com/nemtech/nem2-library-js/releases/tag/v0.10.2
[test-vectors]: https://github.com/nemtech/test-vectors
[workshop-supplychain]: https://github.com/nemtech/nem2-workshop-nem-applied-to-supply-chain
[workshop-notary]: https://github.com/nemtech/nem2-workshop-document-notarization
