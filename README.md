# Project 18 Homework - Proof of Authority Development Chain
## Jeff Myers
---
### Steps to start the network:

1. Activate the Ethereum environment in terminal: `conda activate ethereum`

2. Navigate into the project file. For this purpose the file's name is "Blockchain-Homework"

3. Open the first terminal and run the command `./geth --datadir node1 --unlock "768B72D0048dAf07b88F4c492a08eD5c2Bfa5275" --mine --rpc --allow-insecure-unlock`

4. Enter your password when prompted 

5. Open a second terminal and run the command `./geth --datadir node2 --unlock "9AB31e8413283fc83D148D5a8e1C3bB13B230A05" --mine --port 30304 --bootnodes "enode://e5090dc1892e1bf3811b3a6498ad7d2d6fa5c78534ee326a87412fecc551ad95ee65deb99061ef745480f399fec741ce70e4c7e81ed340d0b394d6297f796ced@127.0.0.1:30303" --ipcdisable --allow-insecure-unlock`

6. Enter your password when prompted 

7. Open the MyCrypto application

8. Navigate to the keystore file from the node1/keystore directory into MyCrypto

9. Send a transaction from the first node to the second node with the test Ethereum
---
### The screenshot file shows the `puppeth code` and the screenshot from the successful transaction.