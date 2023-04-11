# Unit 20 - "Joint Savings Account"

![alt=“”](Images/20-5-challenge-image.png)

### Background

This is a Solidity smart contract that implements a joint savings account. The smart contract accepts two user addresses that are then able to control the account. It uses ether management functions to implement various requirements from the financial institution to provide the features of the joint savings account.

### Usage

The JointSavings smart contract has four variables:

1. accountOne and accountTwo: Two variables of type address payable that represent the two user addresses that control the 2. joint savings account.
2. lastToWithdraw: A variable of type address public that tracks the last user who made a withdrawal from the account.
3. lastWithdrawAmount: A variable of type uint public that tracks the amount of the last withdrawal made from the account.
4. contractBalance: A variable of type uint public that represents the current balance of the joint savings account.

## Deployment

### Set accounts

![Accounts](Execuction_Results/setaccount.png)

### Transaction 1

Deposit 1 Ether as Wei

![1ether](Execuction_Results/1ether.png) ![deposit1](Execuction_Results/transaction1.png)

### Transaction 2

Deposit 10 Ether as Wei

![10ether](Execuction_Results/10ether.png) ![deposit2](Execuction_Results/transaction2.png)

### Transaction 3

Deposit 5 Ether

![5ether](Execuction_Results/5ether.png) ![deposit3](Execuction_Results/transaction3.png)

### Withdrawal 1

Withdraw 5 Ether into AccountOne

![withdraw1](Execuction_Results/withdraw1.png)
![withdrawverify](Execuction_Results/withdraw1function.png)

### Withdrawl 2

Withdraw 10 Ether into AccountTwo

![withdraw2](Execuction_Results/withdraw2.png)
![withdrawverify2](Execuction_Results/withdraw2function.png)
