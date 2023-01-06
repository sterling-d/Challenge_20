# Smart Contract Using Solidity 

## Overview 

This application is based on a Solidity smart contract that automates the financial process and features of joint saving accounts. This smart contract accepts two user addresses that controls a joint savings account by using ether management function to implement financial institutions requirements for providing the ability to deposit and withdraw the funds from the account.

## Technology 

This project leverages Solidity and Remix IDE.

## Usage 

To use this application first open the Remix IDE https://remix.ethereum.org/#optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.7+commit.e28d00a7.js. In the Featured Plugins area,click the Solidity button.

Now execute the following steps:

* In the IDE click the "File explorers" button.
* In the File Explorers pane, on the toolbar,click the Create New File button and create a file named joint_saving.sol.
* Next, clone the repo and copy the code from joint_savings.sol file.Navigate to the “Deploy & run transactions” pane and select Remix VM(London) execution environment.
* Now click the Deploy button to deploy the smart contract, and then confirm that it successfully deployed.

## Interact with Your Deployed Smart Contract

To interact with your deployed smart contract, complete the following steps:

1. Use the setAccounts function to define the authorized Ethereum address that will be able to withdraw funds from your contract.

   You can create new, dummy addresses on the Vanity-ETH https://vanity-eth.tk website, which includes an Ethereum vanity address generator.

2. Test the deposit functionality of your smart contract by sending the some amounts of ether. After each transaction, use the contractBalance function to verify that the funds were added to your contract.

3. Once you’ve successfully deposited funds into your contract, test the contract’s withdrawal functionality by withdrawing some ether into accountOne and accountTwo. After each transaction, use the contractBalance function to verify that the funds were withdrawn from your contract. Also, use the lastToWithdraw and lastWithdrawAmount functions to verify that the address and amount were correct.


## Execution Results: 


<img width="1440" alt="today" src="https://user-images.githubusercontent.com/105071493/203686136-e1a4cb86-a356-40bd-9a0a-84ba1badcd42.png">

## Deployed Contract

<img width="1440" alt="Screenshot 2022-11-23 at 7 39 16 PM" src="https://user-images.githubusercontent.com/105071493/203688814-78c014fb-de31-4126-b5cb-46840da98482.png">

## 1st Transaction: Depositing 1 Ether 

<img width="1074" alt="Screenshot 2022-11-23 at 7 43 54 PM" src="https://user-images.githubusercontent.com/105071493/203689273-5aeb21df-1b32-40ef-bb44-88940bfe8036.png">

## Balance after depositing 1st ether:

<img width="363" alt="Screenshot 2022-11-23 at 7 44 52 PM" src="https://user-images.githubusercontent.com/105071493/203689373-27901c71-0293-49c4-a082-747ff1837c64.png">

## 2nd Transaction: Depositing 10 Ether 

<img width="1071" alt="Screenshot 2022-11-23 at 7 46 07 PM" src="https://user-images.githubusercontent.com/105071493/203689493-3631f858-1294-4cae-83c7-d8096e450f97.png">

## Balance after depositing 10 ether:

<img width="303" alt="Screenshot 2022-11-23 at 7 47 14 PM" src="https://user-images.githubusercontent.com/105071493/203689592-13b10e46-fb3d-4661-9abd-2e56f1c2e6b8.png">

## 3rd Transaction: Depositing 5 Ether: 

<img width="1073" alt="Screenshot 2022-11-23 at 7 48 51 PM" src="https://user-images.githubusercontent.com/105071493/203689784-2d6dd0b9-539d-457a-bdd6-ad503d9b43b6.png">

## Balance after depositing 10 ether: 

<img width="366" alt="Screenshot 2022-11-23 at 7 49 38 PM" src="https://user-images.githubusercontent.com/105071493/203689888-598e6ff3-61b2-4d71-8e87-ffb14d6a67de.png">

## Using our withdraw function between Account 1 and Account 2: 

### Withdrawing 5 ether into Account 1:

<img width="1071" alt="Screenshot 2022-11-23 at 7 52 07 PM" src="https://user-images.githubusercontent.com/105071493/203690192-a2e5ebb7-464b-43e4-9fd1-248194968f8c.png">

### Withdrawing 10 ether into Account 2: 

<img width="1075" alt="Screenshot 2022-11-23 at 7 54 20 PM" src="https://user-images.githubusercontent.com/105071493/203690393-a0d5c129-286b-4b2a-90a5-51c6087ad041.png">












