# Shared-Wallet-v1
A simple shared wallet functionality implemented using Solidity.

> ## Coming soon
> - User interface to facilitate effective interaction between smart contract and user.
> - Hosting on website for effective user interaction.

## Development Goals:
- On-chain wallet smart contract.
- Wallet contract can store funds and let users withdraw again.
- Owner of the contract can give "allowance" to other specific user-addresses.
- Restrict the functions to user-specific roles.
- Re-use the existing smart contracts which are already audited to the greatest extent.

## Real World Use cases:
- Allowance for Children per day/week/month to be able to spend a certain amount of funds.
- Employers give employees an allowance for their travel expenses.
- Businesses give contractors an allowance to spend a certain budget.

## How to Run?
- Open https://remix.ethereum.org/
- Create two solidity files with the same name and copy-paste these contents.
- Compile the files with appropriate version changes.
- Deploy the smart contract.
- Use the following functions of deployed contract to interact:

![alt text](https://github.com/pps-19012/Shared-Wallet-v1/blob/main/sharedwallet.png)
