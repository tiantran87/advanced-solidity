# Crowdsale with Solidity - PupperCoin

## **Overview**
Crowd-selling PupperCoin smart-contracts coded using Solidity. The 2 smart contracts are developed and deployed on Remix.

* The _ENVIRONMENT_ on Remix is set to _**INJECTED WEB3**_
* The MetaMask is set to _**LOCALHOST(8545)**_ for testing purpose and latter deployed on Kovan Network.

##
    * Token Name: PupperCoin
    * Token Symbol: PUPCOIN
    * Rate : 1 Ether = 10 PUPCOIN
    * Goal: 1 Ether
    * Cap: 1.5 Ether
    * Closing: July 5th, 2020
    * Deployer contract Address: 0x504c81D9bf9AA5532bdFd311b67014E39Bc55C65
    * Crowd Sale Address: 0x665B3bbeA7b9C16266401a74ddDD1D5Fe50aB734
    * Token Address: 0x875a25300507D72CaF57096358a3F6f713070BbA
    * Contract Deployed on Etherscan: https://kovan.etherscan.io/address/0x665b3bbea7b9c16266401a74dddd1d5fe50ab734

## My Steps and Screen-Shots:

1) Compile PupperCoin.SOL:
    ![CompilePUP](Images/1-compilePupperCoin.png)

2) Compile CrownSale.SOL:
    ![CompileCS](Images/2-compileCrowSale.png)

3) Deploy PupperCoinSaleDeployer contract using Company Wallet as benefactor wallet:
    ![Deploy PupperCoinSaleDeployer](Images/3-DeployPupperCoinSaleDeployer.png)
    ![Noted Token_Address and Token_Sale_Address](Images/3.1-NotedToken_AddressandToken_Sale_Address.png)
    
4) Deploy PupperCoinSale Contract with Token_sale_address in the At_Address section:
   ![Deploy PupperCoinSale Contract with Token_sale_address in the At_Address section](Images/4 - Deploy PupperCoinSale Contract with Token_sale_address in the At_Address section.png) 
   
5) Import PUPCOIN Token in Purchase Wallet:
    ![Import PUPCOIN Token in Purchase Wallet](Images/5-ImportPUPCOINTokeninPurchaseWallet.png)    
    ![Import PUPCOIN Token in Purchase Wallet](Images/5.2-ImportPUPCOINTokeninPurchaserWallet2.png)    
    ![Import PUPCOIN Token in Purchase Wallet](Images/5.3-ImportPUPCOINTokeninPurchaserWallet2.png)
    
6) Buy Token From ANOTHER wallet (Called Empolyee 1 wallet):
    ![Buy Token From Employee 1 wallet.png](Images/6-BuyTokenFromEmployee1wallet.png)    
    ![Buy Token From Employee 1 wallet.png](Images/6.2-BuyTokenFromEmployee1wallet.png)    
    ![Check the transaction and GOAL](Images/6.3-RaisedandGoal.png)

_**From here we have 2 scenarios - If the sale of the contract time out and the goal was not reached within the timeframe:**_ All ETH raised will be returned to the original purchase address (Employee 1 wallet):
    
   ![Buy Token From Employee 1 wallet.png](Images/6.4-contracttimeout.png)
    
7) Finalise the timed out contract:
    ![Finalize contract](Images/7.1-Finalizecontractandclaimrefund.png)    
    ![Claim refund](Images/7.2-Finalizecontractandclaimrefund.png)    
    ![Ether goes back to Employee 1 Wallet due to unsuccess crowd sale](Images/7.3-Ethergoesbacktoemployeeduetounsuccesscrowsale.png)

_**If the goal was not reached within the timeframe:**_

8) Buy Token on a new contract:    
    ![Buy Token on a new contract](Images/8.1-BuyTokenonanewcontract.png)    
    ![Buy More Token on a new contract](Images/8.2-BuyMoreTokenonanewcontract.png)
    
9) The goal this time is reached for the crowd sale:
    ![Goal Reached](Images/9-GoalReached.png)

10) Finalise the successful crowd sale contract:
    ![Finalise Contract](Images/10-Finalisecontract.png)

11) We can now withdraw the token to the purchaser wallet (Employee 1):
    ![Widthraw token](Images/11-Widthrawtoken.png)
    ![Token In purchase wallet](Images/12-TokenWithdrawtothewalletofemployee.png)
 
 







