# Unit-20-Homework
## Joint Savings Account
![20-5-challenge-image](https://user-images.githubusercontent.com/93611442/162860418-57def762-7359-4900-bd22-4a3a4ee2da9a.png)  
### Background
Let's say I work for a fintech startup company. This company is disrupting the finance industry with its own cross-border, Ethereum-compatible blockchain that connects financial institutions. Currently, the team is building smart contracts to automate many of the institutions’ financial processes and features, such as hosting joint savings accounts.

To automate the creation of joint savings accounts, I created a Solidity smart contract that accepts two user addresses. These addresses are able to control a joint savings account. This smart contract uses ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features consist of the ability to deposit and withdraw funds from the account.  

#### Step 1: Creating a Joint Savings Account Contract in Solidity  
![Step 1_1](https://user-images.githubusercontent.com/93611442/163310050-c9344cfb-c1b8-45ee-80c0-4181775083d1.jpg)  
![Step 1_2](https://user-images.githubusercontent.com/93611442/163310077-b8a6ff6d-d026-4e6e-9fbd-55818633f869.jpg)  

#### Step 2: Compiling and Deploying the Contract in the JavaScript VM  
After reviewing the code and making the necessary changes, I compiled my smart contract. Then I navigated to the “Deploy & Run Transactions” pane and deployed it successfully.  

#### Step 3: Interacting with My Deployed Smart Contract  
Now that my contract is deployed, it’s time to test its functionality!  
I used the "setAccounts" function in order to define the authorized Ethereum address that would be able to withdraw funds from my contract and then used the following dummy Ethereum addresses as account1 address and account2 address:  

![Dummy accounts](https://user-images.githubusercontent.com/93611442/163311389-b8602e59-5feb-479d-964a-41b6aa4377b8.jpg)  

![Setting_Accounts](https://user-images.githubusercontent.com/93611442/163312672-7749dd8c-6234-4f41-850b-2a8ffd762c21.jpg)


##### Execution Results  
*Transaction 1: Send 1 ether as wei*  
![Transaction_1](https://user-images.githubusercontent.com/93611442/163311588-bc5b4725-a23d-4781-bc36-1926c93e16b9.jpg)  

*Transaction 2: Send 10 ether as wei*  
![Transaction_2](https://user-images.githubusercontent.com/93611442/163311632-ef16fc9d-2dad-4ca1-9ca3-30761ad13de0.jpg)  

*Transaction 3: Send 5 ether*  
![Transaction_3](https://user-images.githubusercontent.com/93611442/163311700-06c6afd3-8710-47c8-9ac3-66bdb38e2276.jpg)  

*Withdrawal 1: Withdraw 5 ether into "accountOne"*  
![Withdrawal_1](https://user-images.githubusercontent.com/93611442/163311861-38da1c53-ed83-48fb-9b6a-c050cc4f3c47.jpg)  

*Withdrawal 2: Withdraw 10 ether into "accountTwo"*  
![Withdrawal_2](https://user-images.githubusercontent.com/93611442/163311929-caf6c579-ab19-4b3f-b776-fad292e85c11.jpg)





