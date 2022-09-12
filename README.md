# Savings Account
 

## Background
automate the creation of joint savings accounts, you’ll create a Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account. Your smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

### Installation Guide
Please import and use the following libraries and dependencies in order to use this program:
```
pragma solidity ^0.5.0;
```

### Usage
The program will run most efficiently with the help of the following code blocks.

```
contract JointSavings {

    address payable accountOne;
    address payable accountTwo;
    address public lastToWithdraw;
    uint public lastWithdrawAmount;
    uint public contractBalance;
    
    ```
### Results
The results of our Joint Savings smart contract are displayed in the following medium.
