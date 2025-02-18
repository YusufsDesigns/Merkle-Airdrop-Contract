# Airdrop Contract

This project implements an Ethereum-based airdrop contract that utilizes Merkle trees and Merkle proofs to verify eligibility for the airdrop efficiently. It incorporates a gas-optimized signature-based system for claim delegation and transaction fee sponsorship, ensuring minimal gas costs for participants while supporting secure claim delegation. The contract leverages OpenZeppelin libraries for standard security practices.

## Features
- **Merkle Trees & Merkle Proofs**: Efficient eligibility verification for airdrop participants.
- **Gas-Optimized**: Signature-based system for transaction fee sponsorship and claim delegation.
- **Security**: Utilizes OpenZeppelin's contracts for standard security.
- **Flexible Claiming**: Delegates claims and handles transaction fees efficiently.

## Setup

### Requirements:
- [Foundry](https://book.getfoundry.sh/) for building and testing contracts.
- [OpenZeppelin](https://openzeppelin.com/contracts/) for secure, community-vetted smart contracts.
- [Chainlink](https://chain.link/) for off-chain data feeds and automation.

### Installation:
Clone the repository:
```bash
git clone https://github.com/YusufsDesigns/airdrop-contract.git
cd airdrop-contract
```

Install dependencies:
```bash
forge install
```

### Testing:
To build the contract:
```bash
forge build
```

To run tests:
```bash
forge test
```

### Deploy:
To deploy the contract to a test network or mainnet:
```bash
forge script script/Deploy.s.sol:DeployScript --rpc-url <rpc_url> --private-key <your_private_key>
```

### Interact with the Contract:
Use Remix or `cast` for interacting with the deployed contract after deployment.

## Contribution:
Feel free to contribute to the project by forking and submitting pull requests with new features, bug fixes, or improvements.

---

This README provides a detailed look at the project, with setup, testing, and deployment instructions. Let me know if you'd like any changes!
