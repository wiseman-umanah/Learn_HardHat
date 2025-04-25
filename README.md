# Learn Hat: Exploring Hardhat

Welcome to **Learn Hat**, a repository dedicated to learning and experimenting with [Hardhat](https://hardhat.org/), a powerful Ethereum development environment. This project contains structured examples, configurations, and tests to help you understand and utilize Hardhat for blockchain development.

## Project Structure

```
learn_hat/
├── .gitignore          # Global gitignore for the repository
├── README.md           # Root project documentation
├── hardhat_tutorial/   # Additional tutorials and examples
└── intro_to_hardhat/   # Main Hardhat project


## About Hardhat

Hardhat is a development environment designed for Ethereum smart contract developers. It provides tools for compiling, testing, debugging, and deploying smart contracts. This repository demonstrates how to use Hardhat effectively, including:

- Writing and testing Solidity contracts.
- Deploying contracts using Hardhat Ignition.
- Configuring networks for deployment (e.g., Sepolia testnet).

## Getting Started

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or later)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Hardhat](https://hardhat.org/)

### Setup

1. Navigate to the `intro_to_hardhat` directory:
   ```bash
   cd intro_to_hardhat
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the `intro_to_hardhat` directory with the following variables, for safe keeping. These keys will actually be added to hardhat configuration:
   ```env
   ETHERSCAN_API_KEY=your_etherscan_api_key
   SEPOLIA_PRIVATE_KEY=your_sepolia_private_key
   SEPOLIA_RPC=https://sepolia.infura.io/v3/your_project_id
   ```

## Key Features

- **Sample Contracts**: Includes `Lock.sol` and `Token.sol` for learning and experimentation.
- **Testing**: Demonstrates how to write tests using Hardhat's testing utilities.
- **Deployment**: Automates contract deployment with Hardhat Ignition.
- **TypeScript Support**: Provides type-safe contract interactions using TypeChain.

## Usage

### Compile Contracts
To compile the smart contracts, run:
```bash
npx hardhat compile
```

### Run Tests
To execute the tests, run:
```bash
npx hardhat test
```

### Deploy Contracts
To deploy contracts using Hardhat Ignition, run:
```bash
npx hardhat ignition deploy ./ignition/modules/Token.ts
```

### Start a Local Node
To start a local Hardhat network, run:
```bash
npx hardhat node
```

## Resources

- [Hardhat Documentation](https://hardhat.org/docs)
- [Ethers.js Documentation](https://docs.ethers.io/)
- [Solidity Documentation](https://docs.soliditylang.org/)

## License

This project is licensed under the [ISC License](intro_to_hardhat/LICENSE).

---

Happy learning! 🚀
