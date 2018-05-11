## How to create a Ethereum Network

### Instructions

01. Run remove-test-net-blockchain-data.sh to ensure there is no dirty data lying about
02. Create a new account using "geth account new --datadir /path/to/test-net-blockchain"
03. Copy the address and paste it into the CustomGenesis.json file
04. Run init-genesis.block.sh to create the genesis block
05. Connect to the test chain using connect-to-test-chain.sh
06. Validate the account has a value using "web3.fromWei(eth.getBalance(eth.accounts[0]), “ether”)"
07. Start mining on test chain
08. Validate account value has increased using step 6

#### To-do
Expand the commentary above with more explanation
 
