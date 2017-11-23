# ethereum_home(Linux)

It is the home for easing the private network (Ethereum) setup. This initiate 5 ethereum nodes with 10 ethers and two accounts each. The mining will run on demand. i.e If there is a pending transaction in a node, it will start mining it to form a block and stop it by itself.

## Prerequisite Installation:
[npm and NodeJS](https://docs.npmjs.com/getting-started/installing-node)

[Geth](https://github.com/ethereum/go-ethereum)

## Setup:
1. edit the /etc/environment to append
###### ethereum_home="/path/to/cloned/directory/ethereum_home"
2. run 'cd /etc' && './environment'(sudo if required)
3. restart the terminal and check the effect by running '$ethereum_home'
4. cd $ethereum_home

## Run:
1. In terminal, run './cleanAndBuild', a five terminal window will open up, wait till the clean and build end. Then close those 5 terminals.
2. check if all node folders have static-nodes.json file. Those are the peers.
3. Run './runMiners'. Then your can see similar 5 terminal window with five nodes running.

The RPC listening ports: 8545, 8546, 8547, 8548 and 8549
