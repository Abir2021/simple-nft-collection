# SimpleNFT - Basic NFT Collection

A basic ERC-721 NFT collection built with Solidity and OpenZeppelin. This project demonstrates NFT minting, metadata, and ownership management.

## 🌟 Features

- ✅ ERC-721 standard implementation
- ✅ Public minting with ETH payment
- ✅ Owner can mint for free
- ✅ Configurable mint price
- ✅ Max supply cap (10,000 NFTs)
- ✅ Metadata URI support
- ✅ Withdraw functionality for contract owner

## 🛠️ Tech Stack

- Solidity ^0.8.20
- OpenZeppelin Contracts (ERC-721)
- Hardhat / Foundry
- IPFS (for metadata storage)

## 📦 Installation

```bash
git clone https://github.com/Abir2021/simple-nft-collection.git
cd simple-nft-collection
npm install
🚀 Usage
Compile
npx hardhat compile
Test
npx hardhat test
Deploy
npx hardhat run scripts/deploy.js --network sepolia
📝 Contract Details
Name: SimpleNFT
Symbol: SNFT
Max Supply: 10,000 NFTs
Mint Price: 0.01 ETH (adjustable)
Standard: ERC-721
🎯 Functions
mint() - Public minting function (requires payment)
ownerMint(address) - Free mint for contract owner
setMintPrice(uint256) - Update mint price
setBaseURI(string) - Update metadata URI
withdraw() - Withdraw contract funds
🔐 Security
Built on audited OpenZeppelin ERC-721 implementation
Owner-only administrative functions
Supply cap prevents oversupply
Safe transfer mechanisms
📄 License
MIT License
🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first.
📬 Contact
Twitter: @DabidWm
GitHub: @Abir2021
⭐ Star this repo if you're learning NFT development!
