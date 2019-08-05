# Projects & SDK Protocol Compatibility

## Table of contents

- [Abstract](#abstract)
- [Protocol Version Compatibilities](#protocol-version-compatibilities)
  - [Icon Status Attribution](#icon-status-attribution)
  - [Elephant: Protocol v0.5.?.?](#elephant-protocol-v0501)
  - [Dragon: Protocol v0.4.?.?](#dragon-protocol-v0401)
  - [Cow: Protocol v0.3.0.2](#cow-protocol-v0302)
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
| enhanced delegated harvesting | :o:  | :stop_sign:  | :stop_sign:  | :stop_sign:  | :stop_sign: | :stop_sign: | :stop_sign: | :stop_sign: 
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
