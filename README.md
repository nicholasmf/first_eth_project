# first_eth_project
First etherium contract project - class from https://www.udemy.com/ethereum-and-solidity-the-complete-developers-guide

# Libraries
Web3 - Contract interface<br/>
Ganache - Local test network used for tests (process almost instantainely)

# Files
inbox.sol - Contract code
compile.js - Reads inbox.sol contract and exports the compiled contract<br/>
deploy.js - Uses HDWalletProvider to connect to a real test network (Rinkeby) and uses an Infura node (real node instead of a local node setup)
test/inbox.test.js - Executes a test using ganache network to check if the contract is working as expected
