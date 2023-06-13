# Bank Smart Contract
This is a simple Solidity smart contract that represents a basic banking system. The contract allows users to deposit and withdraw funds, check their balance, view their address, and transfer funds to other addresses.

## Features
### Deposit
 * ```deposit()``` function allows users to deposit funds into their account.
 * Requires that the deposited value is higher than zero.
### Withdraw
* ```withdraw(uint amount)``` function allows users to withdraw funds from their account.
* Requires that the user has a sufficient balance to cover the withdrawal amount.
* Transfers the requested amount to the user's address.
### Check Balance
* ```checkBalance()``` function allows users to view their current balance.
* Returns the balance associated with the user's address.
### View Sender
* ```viewSender()``` function allows users to retrieve their address.
* Returns the address of the sender.
### Transfer
* ```transfer(uint amount, address to)``` function allows users to transfer funds to another address.
* Requires that the user has a sufficient balance to cover the transfer amount.
* Deducts the transfer amount from the sender's balance and adds it to the recipient's balance.
### Usage
1) Deploy the ```bank.sol``` contract to a compatible Ethereum network.
2) Interact with the contract using a compatible Ethereum wallet or a smart contract interaction tool.

### Example Interaction using Remix IDE
1) Deploy the ```bank.sol``` contract in the Remix IDE environment.

2) Select the contract instance from the "Deployed Contracts" section.

3) Use the provided functions to interact with the contract:
  * To deposit funds, call the ```deposit()``` function and specify the amount you want to deposit.
  * To withdraw funds, call the ```withdraw(uint amount)``` function and specify the amount you want to withdraw.
  * To check your balance, call the ```checkBalance()``` function.
  * To view your address, call the ```viewSender()``` function.
  * To transfer funds to another address, call the ```transfer(uint amount, address to)``` function and specify the amount and the recipient's address.
  * Please note that when interacting with the contract, you should ensure you have sufficient funds in your Ethereum address to cover any desired transactions.
