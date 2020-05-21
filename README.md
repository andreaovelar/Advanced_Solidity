# Advanced_Solidity

###  Advanced_Solidity_HW
####  Background
Your company has decided to crowdsale their PupperCoin token in order to help fund the network development.
This network will be used to track the dog breeding activity across the globe in a decentralized way, and allow humans to track the genetic trail of their pets. You have already worked with the necessary legal bodies and have the green light on creating a crowdsale open to the public. However, you are required to enable refunds if the crowdsale is successful and the goal is met, and you are only allowed to raise a maximum of 300 Ether. The crowdsale will run for 24 weeks.

You will need to create an ERC20 token that will be minted through a Crowdsale contract that you can leverage from the OpenZeppelin Solidity library.

This crowdsale contract will manage the entire process, allowing users to send ETH and get back PUP (PupperCoin).
This contract will mint the tokens automatically and distribute them to buyers in one transaction.
It will need to inherit Crowdsale, CappedCrowdsale, TimedCrowdsale, RefundableCrowdsale, and MintedCrowdsale.
You will conduct the crowdsale on the Kovan or Ropsten testnet in order to get a real-world pre-production test in.

## Steps  
* Connect Metamask on Kovan network with at least two prefunded wallet accounts 
* Compile Crowdsale and Puppercoin file
* Deploy PupperCoinSaleDeployer first 
* Deploy PupperCoinSale second 
* Deploy PupperCoin last 
* Start raising funds by sending PUP coins 
* Check transactions on Etherscan to confirm crowdsale 


## Deployment 

Please find below screenshot in which we show the deployment in remix for PupperCoinSaleDeployer file using kovan network. please note input values in the box (Puppercoin, PUP, wallet, goal to raise)

![table](https://github.com/andreaovelar/Advanced_Solidity/blob/master/images/Capture3.PNG "CLOSE")

Please find below screenshot in which we show the deployment cost of the contract 

![table](https://github.com/andreaovelar/Advanced_Solidity/blob/master/images/Capture4.PNG "CLOSE")

Please find below screenshot after contract deployment in which we see the blockchain address of the contract (Token sale address)

![table](https://github.com/andreaovelar/Advanced_Solidity/blob/master/images/Capture5.PNG "CLOSE")

We use that address to deploy the second contract PupperCoinSale and click on At address 

![table](https://github.com/andreaovelar/Advanced_Solidity/blob/master/images/Capture6.PNG "CLOSE")

Now we need the token address from the first contract deploy in order to deploy the PupperCoin contract by clicking on at address 

![table](https://github.com/andreaovelar/Advanced_Solidity/blob/master/images/Capture7.PNG "CLOSE")


## Fundraising

Please find below screenshot for initial flags for the PupperCoinSale 

![table](https://github.com/andreaovelar/Advanced_Solidity/blob/master/images/Capture9.PNG "CLOSE")

Please find below screenshot for PupperCoinSale contract in which we enter the second prefunded wallet address in order to raise coins we click on BuyTokens and specify the amount of wei or Ether we want to send  

![table](https://github.com/andreaovelar/Advanced_Solidity/blob/master/images/Capture8.PNG "CLOSE")

Please find below screenshot of confirmation using etherscan

![table](https://github.com/andreaovelar/Advanced_Solidity/blob/master/images/Capture10.PNG "CLOSE")

## File TieredProfitSplitter

Please find below screenshot for initial balances from account 1 to 4 

![table](https://github.com/andreaovelar/Advanced_Solidity/blob/master/images/Capture11.PNG "CLOSE")

Please find below screenshot for initial balances from account 1 to 4 

![table](https://github.com/andreaovelar/Advanced_Solidity/blob/master/images/Capture12.PNG "CLOSE")

Please find below screenshot for initial balances from account 1 to 4 

![table](https://github.com/andreaovelar/Advanced_Solidity/blob/master/images/Capture13.PNG "CLOSE")

Please find below screenshot for initial balances from account 1 to 4 

![table](https://github.com/andreaovelar/Advanced_Solidity/blob/master/images/Capture14.PNG "CLOSE")

Please find below screenshot for initial balances from account 1 to 4 

![table](https://github.com/andreaovelar/Advanced_Solidity/blob/master/images/Capture15.PNG "CLOSE")


## Useful links and info 
* https://kovan.etherscan.io/
* https://remix.ethereum.org/
* address used to deploy contracts 0x30B7C972578985dD504Cd6E1846d55faF25CF37E'

## Conclusions 
* We were able to use Ganache, Metamask, and remix for smart contract development 
* We use our local network as well as Kovan testnet 
