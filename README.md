
[![banner](https://raw.githubusercontent.com/oceanprotocol/art/master/github/repo-banner%402x.png)](https://oceanprotocol.com)

<h1 align="center">ocean.py</h1>

> Python library to privately & securely publish, exchange, and consume data.

With ocean.py, you can:
- **Publish** data services: downloadable files or compute-to-data. 
Ocean creates a new [ERC20](https://github.com/ethereum/EIPs/blob/7f4f0377730f5fc266824084188cc17cf246932e/EIPS/eip-20.md) 
datatoken for each dataset / data service.
- **Mint** datatokens for the service
- **Sell** datatokens via an OCEAN-datatoken Balancer pool (for auto price discovery), or for a fixed price
- **Stake** OCEAN on datatoken pools
- **Consume** datatokens, to access the service
- **Transfer** datatokens to another owner, and **all other ERC20 actions** 
using [web3.py](https://web3py.readthedocs.io/en/stable/examples.html#working-with-an-erc20-token-contract) etc.

ocean.py is part of the [Ocean Protocol](https://www.oceanprotocol.com) toolset.

This is in beta state and you can expect running into problems. If you run into them, please open up a [new issue](/issues).

- [🏗 Installation](#-installation)
- [🏄 Quickstart](#-quickstart)
  - [Simple Flow](#simple-flow)
  - [Learn more](#learn-more)
  - [Marketplace Flow](#marketplace-flow)
- [🦑 Development](#-development)
- [🏛 License](#-license)

## 🏗 Installation

```pip install ocean-lib```

## 🏄 Quickstart

### Simple Flow

[Publish your first datatoken](READMEs/datatokens_flow.md) - connect to Ethereum, create an Ocean instance, and publish.

### Learn more

- [Get test OCEAN](READMEs/get_test_OCEAN.md) - from rinkeby
- [Understand config parameters](READMEs/parameters.md) - envvars vs files 
- [Learn about off-chain services](READMEs/services.md) - Ocean Provider for data services, Aquarius metadata store
- [Learn about wallets](READMEs/wallets.md) - on generating, storing, and accessing private keys
- [Get an overview of ocean-lib](READMEs/overview.md) - key modules and functions

### Marketplace flow

[Create a marketplace and sell data](READMEs/marketplace_flow.md) - batteries-included flow including using off-chain services for metadata and consuming datasets.

## 🦑 Development

If you want to further develop ocean.py, then [please go here](READMEs/developers.md).

## 🏛 License

```
Copyright ((C)) 2021 Ocean Protocol Foundation

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
