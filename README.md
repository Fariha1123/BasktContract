# BsktContract

BsktContract is the implementation of popular bskt smart contract for creation of decentralized token portfolios. Find whitepaper here:
https://github.com/cryptofinlabs/bskt-whitepaper/blob/master/bskt-whitepaper-v1.0.0.pdf. The white paper is also included in the repo. 

## Details:
The bskt contract is is designed to be based on three erc20 tokens:
1. T1  https://ropsten.etherscan.io/address/0x16fba9f1129dab9fc1f1264a854971ccb6a083b9
2. T2  https://ropsten.etherscan.io/address/0x959025298a9bc8111d15b342f0f5e25d3a6b8b95
3. T3  https://ropsten.etherscan.io/address/0x1e97d9b459cfb2a9ca7548a6f6a6dd0d6242a066
Each bskt is using 2 T1, 4 T2, 6 T3 for a single bskt. 

## pre-requisities
1. The bskt creator should own three of the above mentioned tokens
2. Allow the contract address to use the relevant number of tokens from your account
3. Hit create to generate a bskt of your tokens


### The contract is right now in development phases and is deployed on ropsten test network. Contract address: https://ropsten.etherscan.io/address/0x0618a291c826370ce10da5995f5947492dcef59e
