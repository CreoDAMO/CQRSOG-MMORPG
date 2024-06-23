# CryptoQuest: The Shards of Genesis

**SEO Meta Description:** Discover CryptoQuest: The Shards of Genesis, a blockchain-based MMORPG developed with Unity and Unreal Engine 5. Learn how to leverage NFTs, smart contracts, and decentralized economies to create an immersive gaming experience.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Game Overview](#game-overview)
- [Contracts](#contracts)
- [Installation](#installation)
- [Creating a Front-end DApp](#creating-a-front-end-dapp)
- [Developing CryptoQuest in Unity](#developing-cryptoquest-in-unity)
- [Developing CryptoQuest in Unreal Engine 5](#developing-cryptoquest-in-unreal-engine-5)
- [FAQs](#faqs)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [License](#license)
- [Repository Structure](#repository-structure)

![CryptoQuest Logo](https://github.com/CreoDAMO/Crypto-Quest/assets/151800081/8be79371-7f2e-4fe5-a8f5-158031748d2b)

## Introduction

Welcome to **CryptoQuest: The Shards of Genesis**, an ambitious blockchain-based MMORPG where players embark on an epic journey through the realm of Cryptonia. This open-world universe leverages blockchain technology to provide true ownership of in-game assets through NFTs.

## Features

- **True Ownership**: In *CryptoQuest*, each in-game asset is a unique NFT.
- **Decentralized Economy**: A decentralized marketplace for trading assets.
- **Player Governance**: Zones governed by player-elected councils.
- **Crafting & Enchanting**: Unique item crafting and enchanting.
- **Quests & Adventures**: Dynamic quest system with smart contracts.
- **Cross-Chain Interactions**: Support for multiple blockchains.

## Game Overview

In *CryptoQuest: The Shards of Genesis*, players explore the mythical realm of Cryptonia, uncovering secrets and battling creatures in a quest to reunify the shards of Genesis.


## Contracts

### Verified Contracts Linked On Polygonscan & Tenderly

Explore the various contracts that power *CryptoQuest*:

- **Polygonscan**: [View Contracts](https://polygonscan.com/address/0xcc380fd8bfbdf0c020de64075b86c84c2bb0ae79)
- **Tenderly**: [View Contracts](https://dashboard.tenderly.co/CreoDAMO/cryptoquesttheshardsofgenesismmorpg)

| **Contract Name**                                | **Address**                                | **Network** | **Tags**  | **Visibility** | **Verification** |
|--------------------------------------------------|--------------------------------------------|-------------|-----------|----------------|------------------|
| CryptoQuestTheShardsOfGenesisToken               | 0xb30837f54924b88294f524d3e13667396d3f3c8a | Polygon     | Visible   | Public         | Verified         |
| ERC1967Proxy (CQT)                               | 0xb30837f54924b88294f524d3e13667396d3f3c8a | Polygon     | Visible   | Public         | Verified         |
| CryptoQuestTheShardsOfGenesisNFT                 | 0xc641573148e62d88a2374ffe97391f849cea8ff5 | Polygon     | Visible   | Public         | Verified         |
| ERC1967Proxy                                     | 0xc641573148e62d88a2374ffe97391f849cea8ff5 | Polygon     | Visible   | Public         | Verified         |
| CryptoQuestTheShardsOfGenesisCollectionNFT       | 0x5ce6de14eaa1906163c5de4e57302fee8f5d2812 | Polygon     | Visible   | Public         | Verified         |
| ERC1967Proxy                                     | 0x5ce6de14eaa1906163c5de4e57302fee8f5d2812 | Polygon     | Visible   | Public         | Verified         |
| TimelockControllerUpgradeable                    | 0x2b5949f0540884c67c1f169b9f535571656e6695 | Polygon     | Visible   | Public         | Verified         |
| CryptoQuestTheShardsOfGenesisDAO                 | 0x7c3dddd47c29d213458abf9eb23fe50d95fa5205 | Polygon     | Visible   | Public         | Verified         |
| ERC1967Proxy                                     | 0x7c3dddd47c29d213458abf9eb23fe50d95fa5205 | Polygon     | Visible   | Public         | Verified         |
| CryptoQuestTheShardsOfGenesisMarketplace         | 0xef805704fd13b0122477211895e418cb9c22e103 | Polygon     | Visible   | Public         | Verified         |
| ERC1967Proxy                                     | 0xef805704fd13b0122477211895e418cb9c22e103 | Polygon     | Visible   | Public         | Verified         |
| CryptoQuestTheShardsOfGenesisStaking             | 0x7ffc728c30192bf6f2f1448e395a8c9f751bc039 | Polygon     | Visible   | Public         | Verified         |
| ERC1967Proxy                                     | 0x7ffc728c30192bf6f2f1448e395a8c9f751bc039 | Polygon     | Visible   | Public         | Verified         |
| CryptoQuestTheShardsOfGenesisFarming             | 0x822475be2d1b53680ceb3da287a7c608fed591a4 | Polygon     | Visible   | Public         | Verified         |
| ERC1967Proxy                                     | 0x822475be2d1b53680ceb3da287a7c608fed591a4 | Polygon     | Visible   | Public         | Verified         |
| CryptoQuestTheShardsOfGenesisMMORPG              | 0x251ace49f2b106e0746702986e879e404a76f290 | Polygon     | Visible   | Public         | Verified         |
| ERC1967Proxy                                     | 0x251ace49f2b106e0746702986e879e404a76f290 | Polygon     | Visible   | Public         | Verified         |
| CryptoQuestTheShardsOfGenesisWallet              | 0xf60d96cfa71c6fe7fe18ca028041ca7f42b543bd | Polygon     | Visible   | Public         | Verified         |
| ERC1967Proxy                                     | 0xf60d96cfa71c6fe7fe18ca028041ca7f42b543bd | Polygon     | Visible   | Public         | Verified         |
| CryptoQuestSwap                                  | 0x7132367941b5f058dc68cee2dbcd356fbaa7d5b4 | Polygon     | Visible   | Public         | Verified         |
| ERC1967Proxy                                     | 0x7132367941b5f058dc68cee2dbcd356fbaa7d5b4 | Polygon     | Visible   | Public         | Verified         |
| CryptoQuestTheShardsOfGenesisBookNFT             | 0x545Ace061A1b64B14641B50CfE317017b01A667b | Polygon     | Visible   | Public         | Verified         |
| ERC1967Proxy                                     | 0x6b07aD60b1d448D0e1cE9dCB24A85B3ab18b9b1E | Polygon     | Visible   | Public         | Verified         |
| CQTTokenSaleContract                             | 0x126D0A70E6413EC44D977C41024A76d84CEDB4A4 | Polygon     | Visible   | Public         | Verified         |
| ERC1967Proxy                                     | 0xc36fc9872Bd271BD80365517958e6F48D3b4FA91 | Polygon     | Visible   | Public         | Verified         |
## Installation

To install and run *CryptoQuest* locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your_username/cryptoquest.git
    cd cryptoquest
    ```

2. **Navigate to the project directory**:
    ```bash
    cd cryptoquest
    ```

3. **Install dependencies**:
    ```bash
    npm install
    ```

4. **Run the development server**:
    ```bash
    npm start
    ```

## Creating a Front-end DApp

Creating a front-end DApp using React to interact with all 21 smart contracts in this project is a crucial step. See the detailed guide in the `dapp/` directory.

For more detailed instructions, visit the [Creating a Front-end DApp using React Guide](https://github.com/CreoDAMO/CryptoQuestTheShardsOfGenesisMMORPG/wiki/Creating-a-front%E2%80%90end-DApp-using-React).


## Developing CryptoQuest in Unity

Follow the steps in the documentation to develop CryptoQuest using Unity, including blockchain integration, NFT management, and game mechanics.

For detailed instructions, visit the [CQTSOG Unity Guide](https://github.com/CreoDAMO/CryptoQuestTheShardsOfGenesisMMORPG/wiki/CQTSOG-Unity).

## Developing CryptoQuest in Unreal Engine 5

Refer to the guide in the documentation for creating CryptoQuest with Unreal Engine 5, covering topics like decentralized economy and player governance.

For detailed instructions, visit the [CQTSOG Unreal Engine 5 Guide](https://github.com/CreoDAMO/CryptoQuestTheShardsOfGenesisMMORPG/wiki/CQTSOG-Unreal-Engine-5).

## Documentation

You can find the detailed project documentation in the `docs/` directory. This includes the PDF version of the book:

- [CryptoQuest: The Shards of Genesis PDF](docs/CryptoQuest_TheShardsOfGenesis.pdf)

## Metadata

The metadata JSON file, including blockchain publication details, is located in the `metadata/` directory:

- [CryptoQuest Metadata JSON](metadata/CryptoQuest_Metadata.json)

## FAQs

**What is CryptoQuest: The Shards of Genesis?**  
*CryptoQuest* is a blockchain-based MMORPG where players own in-game assets as NFTs.

## Conclusion

Developing *Crypto

Quest: The Shards of Genesis* in Unity or Unreal Engine 5 merges traditional game development with blockchain technology, creating a unique and immersive gaming experience.

## Contributing

We welcome contributions! Follow the guidelines in the `CONTRIBUTING.md` file.

## License

*CryptoQuest: The Shards of Genesis* is licensed under the [MIT License](link_to_license).

### Mind Map
```
- contracts-upgradeable
  - access
    - AccessControlUpgradeable.sol
    - OwnableUpgradeable.sol
  - governance
    - artifacts
      - build-info
        - *.json
    - extensions
      - GovernorCountingSimpleUpgradeable.sol
      - GovernorSettingsUpgradeable.sol
      - GovernorStorageUpgradeable.sol
      - GovernorTimelockControlUpgradeable.sol
      - GovernorVotesQuorumFractionUpgradeable.sol
      - GovernorVotesUpgradeable.sol
    - utils
      - VotesUpgradeable.sol
      - GovernorUpgradeable.sol
      - TimelockControllerUpgradeable.sol
  - proxy
    - utils
      - Initializable.sol
      - UUPSUpgradeable.sol
  - security
    - PausableUpgradeable.sol
  - token
    - ERC1155
      - extensions
        - ERC1155BurnableUpgradeable.sol
        - ERC1155PausableUpgradeable.sol
        - ERC1155SupplyUpgradeable.sol
      - utils
        - ERC1155HolderUpgradeable.sol
        - ERC1155Upgradeable.sol
        - IERC1155Upgradeable.sol
    - ERC20
      - extensions
        - ERC20BurnableUpgradeable.sol
        - ERC20FlashMintUpgradeable.sol
        - ERC20PausableUpgradeable.sol
        - ERC20PermitUpgradeable.sol
        - ERC20VotesUpgradeable.sol
      - ERC20Upgradeable.sol
      - IERC20Upgradeable.sol
    - ERC721
      - extensions
        - ERC721BurnableUpgradeable.sol
        - ERC721EnumerableUpgradeable.sol
        - ERC721PausableUpgradeable.sol
        - ERC721URIStorageUpgradeable.sol
      - utils
        - ERC721HolderUpgradeable.sol
        - ERC721Upgradeable.sol
        - IERC721Upgradeable.sol
  - utils
    - cryptography
      - EIP712Upgradeable.sol
    - introspection
      - ERC165Upgradeable.sol
      - IERC165Upgradeable.sol
    - AddressUpgradeable.sol
    - ContextUpgradeable.sol
    - CountersUpgradeable.sol
    - NoncesUpgradeable.sol
    - PausableUpgradeable.sol
- contracts
  - access
    - IAccessControl.sol
  - governance
    - utils
      - IVotes.sol
      - IGovernor.sol
  - interfaces
    - IERC1271.sol
    - IERC165.sol
    - IERC3156FlashBorrower.sol
    - IERC3156FlashLender.sol
    - IERC4906.sol
    - IERC5267.sol
    - IERC5805.sol
    - IERC6372.sol
    - IERC721.sol
    - draft-IERC1822.sol
    - draft-IERC6093.sol
  - proxy
    - ERC1967
      - ERC1967Utils.sol
    - beacon
      - IBeacon.sol
  - token
    - utils
      - cryptography
        - ECDSA.sol
        - MessageHashUtils.sol
        - SignatureChecker.sol
      - introspection
        - IERC165.sol
      - math
        - Math.sol
        - SafeCast.sol
        - SignedMath.sol
      - structs
        - Checkpoints.sol
        - DoubleEndedQueue.sol
      - types
        - Time.sol
      - Address.sol
      - Arrays.sol
      - StorageSlot.sol
      - Strings.sol
- cryptoquest-dapp
  - public
    - CQTSOG-Logo.svg
  - src
    - components
      - Game.js
    - contexts
      - Web3Context.js
    - contracts
      - index.js
      - web3Modal.js
    - pages
      - Home.js
      - Marketplace.js
      - Staking.js
    - styles
      - global.css
    - utils
      - contracts.js
    - App.css
    - App.jsx
    - index.css
    - main.jsx
  - smartcontracts
    - artifacts
      - build-info
        - *.json
    - CQTTokenSaleContractsol.sol
    - CryptoQuestSwap.sol
    - CryptoQuestTheShardsOfGenesisBookNFT.sol
    - CryptoQuestTheShardsOfGenesisCollectionNFTs.sol
    - CryptoQuestTheShardsOfGenesisDAO.sol
    - CryptoQuestTheShardsOfGenesisMMORPG.sol
    - CryptoQuestTheShardsOfGenesisMarketplace.sol
    - CryptoQuestTheShardsOfGenesisNFT.sol
    - CryptoQuestTheShardsOfGenesisStaking.sol
    - CryptoQuestTheShardsOfGenesisToken.sol
    - CryptoQuestTheShardsOfGenesisWallet.sol
    - CryptoQueststTheShardsOfGenesisFarming.sol
  - .eslintrc.cjs
  - .gitignore
  - README.md
  - index.html
  - package-lock.json
  - package.json
  - vite.config.js
  - .replit
  - LICENSE
  - Makefile
```

### Optimized Directory Structure

```plaintext
cryptoquest-dapp/
├── public/
│   └── CQTSOG-Logo.svg
├── src/
│   ├── components/
│   │   ├── Game.js
│   │   └── ...
│   ├── contexts/
│   │   └── Web3Context.js
│   ├── contracts/
│   │   ├── index.js
│   │   └── web3Modal.js
│   ├── pages/
│   │   ├── Home.js
│   │   ├── Marketplace.js
│   │   ├── Staking.js
│   │   └── ...
│   ├── styles/
│   │   ├── global.css
│   │   └── ...
│   ├── utils/
│   │   ├── contracts.js
│   │   └── ...
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── smartcontracts/
│   ├── artifacts/
│   │   └── build-info/
│   │       └── *.json
│   ├── CQTTokenSaleContractsol.sol
│   ├── CryptoQuestSwap.sol
│   ├── CryptoQuestTheShardsOfGenesisBookNFT.sol
│   ├── CryptoQuestTheShardsOfGenesisCollectionNFTs.sol
│   ├── CryptoQuestTheShardsOfGenesisDAO.sol
│   ├── CryptoQuestTheShardsOfGenesisMMORPG.sol
│   ├── CryptoQuestTheShardsOfGenesisMarketplace.sol
│   ├── CryptoQuestTheShardsOfGenesisNFT.sol
│   ├── CryptoQuestTheShardsOfGenesisStaking.sol
│   ├── CryptoQuestTheShardsOfGenesisToken.sol
│   ├── CryptoQuestTheShardsOfGenesisWallet.sol
│   └── CryptoQueststTheShardsOfGenesisFarming.sol
├── .eslintrc.cjs
├── .gitignore
├── README.md
├── index.html
├── package-lock.json
├── package.json
└── vite.config.js
```

### Structure Explanation

1. **public/**: For static files.
2. **src/**: Main React application directory.
   - **components/**: Reusable React components.
   - **contexts/**: Global state management.
   - **contracts/**: Smart contract interactions.
   - **pages/**: Main application pages.
   - **styles/**: Global CSS styles.
   - **utils/**: Utility functions or helper modules.
   - **App.css**, **App.jsx**, **index.css**, **main.jsx**: Main entry points and configuration.
3. **smartcontracts/**: Solidity smart contract files and artifacts.
4. **Project-level files**: Configuration and project files.
