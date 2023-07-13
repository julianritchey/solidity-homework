# solidity-homework
Module 20 Challenge: Joint Savings Account

## Contract description
The contract contained herein allows two addresses to control a joint savings account. Functions of the contract include
- funds deposit;
- funds withdrawal.

For the purpose of this demonstration, the contract will be deployed in the [Remix Ethereum IDE](https://remix.ethereum.org/). All tasks listed below were performed on the *DEPLOY & RUN TRANSACTIONS* page.

## Deploy contract
![Deploy contract](Execution_Results/deploy_contract.png)  
The contract was deployed using the `Deploy` function.

## Set accounts
![Set accounts](Execution_Results/set_accounts.png)  
The two accounts that were assigned control of the joint account were set using the `setAccounts` function. The addresses were assigned as follows:
- **Account 1:** 0x0c0669Cd5e60a6F4b8ce437E4a4A007093D368Cb
- **Account 2:** 0x7A1f3dFAa0a4a19844B606CD6e91d693083B12c0

The function was processed by clicking the `transact` button.

## Deposit 1 ether as wei
### Deposit ether
![Deposit 1 ether as wei](Execution_Results/deposit_1_ether_as_wei.png)  
The deposit of 1 ether as wei into the joint account was performed by setting the `VALUE` inputs to `1000000000000000000` and `Wei`, and using the `deposit` function.

### Confirm contract balance
![Deposit 1 ether as wei - contractBalance](Execution_Results/deposit_1_ether_as_wei_contractBalance.png)  
The balance of the contract was confirmed using the `contractBalance` function.

## Deposit 10 ether as wei
### Deposit ether
![Deposit 10 ether as wei](Execution_Results/deposit_10_ether_as_wei.png)  
The deposit of 10 ether as wei into the joint account was performed by setting the `VALUE` inputs to `10000000000000000000` and `Wei`, and using the `deposit` function.

### Confirm contract balance
![Deposit 10 ether as wei - contractBalance](Execution_Results/deposit_10_ether_as_wei_contractBalance.png)  
The balance of the contract was confirmed using the `contractBalance` function.

## Deposit 5 ether
### Deposit ether
![Deposit 5 ether](Execution_Results/deposit_5_ether.png)  
The deposit of 5 ether into the joint account was performed by setting the `VALUE` input to `5 Ether` and using the `deposit` function.

### Confirm contract balance
![Deposit 5 ether - contractBalance](Execution_Results/deposit_5_ether_contractBalance.png)  
The balance of the contract was confirmed using the `contractBalance` function.

## Withdraw 5 ether into `accountOne`
### Withdraw ether
![Withdraw 5 ether into accountOne](Execution_Results/withdraw_5_ether_accountOne.png)  
The withdrawal of 5 ether into `accountOne` was performed using the `withdraw` function. The `amount` input was set to `5000000000000000000` and the `recipient` input was set to the address for `accountOne`. The function was processed by clicking the `transact` button.

### Confirm contract balance
![Withdraw 5 ether into accountOne - contractBalance](Execution_Results/withdraw_5_ether_accountOne_contractBalance.png)  
The balance of the contract was confirmed using the `contractBalance` function.

### Confirm last address to withdraw
![Withdraw 5 ether into accountOne - lastToWithdraw](Execution_Results/withdraw_5_ether_accountOne_lastToWithdraw.png)  
The last address to withdraw was confirmed using the `lastToWithdraw` function.

### Confirm last amount withdrawn
![Withdraw 5 ether into accountOne - lastWithdrawAmount](Execution_Results/withdraw_5_ether_accountOne_lastWithdrawAmount.png)  
The last amount withdrawn was confirmed using the `lastWithdrawAmount` function.

## Withdraw 10 ether into `accountTwo`
### Withdraw ether
![Withdraw 10 ether into accountOne](Execution_Results/withdraw_10_ether_accountTwo.png)  
The withdrawal of 10 ether into `accountTwo` was performed using the `withdraw` function. The `amount` input was set to `10000000000000000000` and the `recipient` input was set to the address for `accountTwo`. The function was processed by clicking the `transact` button.

### Confirm contract balance
![Withdraw 10 ether into accountTwo - contractBalance](Execution_Results/withdraw_10_ether_accountTwo_contractBalance.png)  
The balance of the contract was confirmed using the `contractBalance` function.

### Confirm last address to withdraw
![Withdraw 10 ether into accountTwo - lastToWithdraw](Execution_Results/withdraw_10_ether_accountTwo_lastToWithdraw.png)  
The last address to withdraw was confirmed using the `lastToWithdraw` function.

### Confirm last amount withdrawn
![Withdraw 10 ether into accountTwo - lastWithdrawAmount](Execution_Results/withdraw_10_ether_accountTwo_lastWithdrawAmount.png)  
The last amount withdrawn was confirmed using the `lastWithdrawAmount` function.

## Other information
- All work for the contract can be found in the [joint_savings.sol](https://github.com/julianritchey/solidity-homework/blob/main/joint_savings.sol) file.
- All screenshots used in this assignment can be found in the [Execution_Results](https://github.com/julianritchey/solidity-homework/tree/main/Execution_Results) folder.