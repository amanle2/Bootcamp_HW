## Sample Blockchain Network - How to Set Up and Use
---
This blockchain network is both simple and easy to use.  Follow the steps below and you can begin sending mock ETH around in no time.

1. The first step to using this network is to download and install the necessary software packages.  You will need both Geth and Puppeth installed to you dev environment.

2. Once the proper softare is installed, it is time to create some node accounts for the network.  You can do this via the ./geth --datadir node_name_here account new. Once this is complete, the beginnings of your node are ready. Make sure to keep a record of your node's password, public address, and private key.

3. The next step is to initialize your account (your node) with the already created genesis block, which is part of the round5hw18net downpackage.  When you have downloaded the network via round5hw18net, the genesis block will be ready to go. Type the command ./geth --datadir node_name_here init round5hw18net.json and the node will be ready for the next step.

4. To activate your account fully, you must set your node to begin mining blocks.  To do this, run the command ./geth --datadir node_name_here --unlock "public_address" --mine --rpc --allow-insecure-unlock.  After running this command, type in your password and you will begin mining blocks.

5. You will then connect your account to a crypto wallet, such as MyCrypto.  Once in MyCrypto, you will need to add a custom node to connect to round5hw18net.  To do this, go to the Change Network function, and add round5hw18net as a custom node.

6. Once connected to the network, the last step is to test that your on the blockchain. You can do this by transferring some ETH to another public address.  If you don't want to randomly give away your hard earned round5hw18net bucks, simply repeat the steps above and create a second node and transfer the funds between the two nodes yourself.

7. All done! Enjoy your blockchain and valueless ETH.