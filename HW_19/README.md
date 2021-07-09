# HW_19 Wallet - It's Mildly Functional!


## Quotes from our Creator
---
### "I wouldn't use it, but you can if you want."
### "Go store your cryptocurrency somewhere else that is secure and can actually transfer the tokens."
### "Seriously people, I can't emphasize it enough, this is a bad product."
### "Don't associate my name with this."


### Wallet Description
---
This wallet was designed to be a multi-token wallet that could transfer BTCTEST and ETH currency on their respective test networks. It is built in python and utilizes primarily the bit and web3 libraries to funciton. 

In it's current state, it is theoretically functional, but could not be tested due to issues funding the wallet with test currency. The best software engineers at this one-man operation have not yet figured out a solution to this issue and are frankly out of ideas.


### How to Use It
---
The first step to use HW_19 Wallet is to uninstall the wallet and find a better one.  However, if you choose to skip this step, there are other steps you can take to use this wallet.

You will first need to set up an Ethereum development environment and include the following libraries:
* web3
* bit
* eth_account
* hd-wallet-derive (found on github)
    * Note: This library is written in PHP. To use it, PHP must be installed on your device.
* Go Ethereum (geth)

Once you have created this environment, you will need to download this github repository.  

The wallet can be interfaced with by using the command line in Git-Bash. Open up a new terminal, activate your Ethereum environment and then create a Python shell command after you use cd to navigate to the wallet folder. 

Interact with the wallet.py file and create your wallet. Make sure to generate your unique mnemonic key word prior to creating the wallet. This mnemonic key will need to be stored in a .env file that sets mnemonic = "Your_Mnemonic_Phrase_Here".

Once the wallet is created, you will need to hook it up to your desired cryptocurrency network.  It is currently functional for BTCTEST, so start there.

Fund one of your addresses with some BTCTEST currency.  Once this is done, you can test a transaction using the send_tx function found in wallet.py and send the currency from one address to another.  It is recommended to use the BTCTEST network to check on the status of your transaction. 

Once the currency changes hands, you know your wallet is up and working. It is still recommended at this point that you delete this wallet and find another more fleshed out product.  Good luck!