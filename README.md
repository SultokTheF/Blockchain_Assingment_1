# MyToken (Aitu_Sultaniyar)

## Usage

This project is an Ethereum ERC-20 token created using Remix and OpenZeppelin. It provides basic functionalities for an ERC-20 token and includes additional features like retrieving transaction information.

### Prerequisites

Before you start, make sure you have the following:

- [Remix IDE](https://remix.ethereum.org/) or your preferred Ethereum development environment.

### Deployment

1. Open Remix and load the `AITU_Sultaniyar.sol` file.
2. Compile the contract and deploy it using the Metamask wallet.
3. Interact with the contract using the provided functions.

### Functions

#### `getLatestTransactionTimestamp()`

Returns the block timestamp of the latest transaction in a human-readable format.

#### `getTransactionSender()`

Returns the address of the transaction sender.

#### `getTransactionReceiver()`

Returns the address of the transaction receiver.

## Examples

### Demo Screenshots



![image](https://github.com/SultokTheF/Blockchain_Assingment_1/blob/main/images/Demo.jpg)


![image](https://github.com/SultokTheF/Blockchain_Assingment_1/blob/main/images/Demo_2.jpg)

### Examples

function getTransactionReceiver() public view returns (address) {
        return address(0);
    }
