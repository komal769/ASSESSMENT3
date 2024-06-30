# ErrorHandlingExample Smart Contract

## Overview

ErrorHandlingExample is a Solidity smart contract demonstrating error handling techniques (`require`, `assert`, `revert`) and basic functionalities like depositing, withdrawing, transferring Ether, and contract destruction.

## Smart Contract Functions

### `constructor()`

- Initializes the contract owner upon deployment.

### `transfer(address to, uint256 amount)`

- Allows transferring a specified amount of Ether from the caller's balance to another address.

### `deposit()`

- Allows users to deposit Ether into the contract.

### `withdraw(uint256 amount)`

- Allows users to withdraw a specified amount of Ether from their balance in the contract.

### `assertExample(uint256 x, uint256 y)`

- Example function that uses `assert` to demonstrate assertion failure.

### `revertExample(uint256 amount)`

- Example function that uses `revert` to revert the transaction with a custom error message if `amount` equals 42.

### `destroy()`

- Self-destruct function that transfers all remaining Ether in the contract to the owner and destroys the contract.

### `getBalance()`

- Retrieves the current Ether balance of the contract.

## Usage

### Prerequisites

- Remix IDE or another Ethereum development environment.
- MetaMask or another compatible Ethereum wallet for interacting with the contract.

### Deployment

1. Copy the Solidity code into Remix IDE.
2. Compile and deploy the contract on your desired Ethereum environment (e.g., Remix VM, local node, testnet).

### Interacting with the Contract

- **Deposit**: Use `deposit()` to add Ether to the contract.
- **Withdraw**: Use `withdraw(uint256 amount)` to withdraw Ether from the contract.
- **Transfer**: Use `transfer(address to, uint256 amount)` to send Ether to another address.
- **Error Handling**: Explore `assertExample(uint256 x, uint256 y)` and `revertExample(uint256 amount)` for error handling scenarios.
- **Destroy**: Call `destroy()` to withdraw all Ether and destroy the contract.

## Contributing

Contributions are welcome! Fork the repository, make your changes, and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or support, contact [Komal](jangrakomal06@gmail.com).
