This is a demo to build an ETH <=> ERC20 tokens exchange app with the Uniswap exchange protocol.

In each mjs file, make sure you replace `[PROJECT_ID]` with your Infura project id, `[YOUR_ADDRESS]` with your Ethereum address and `[YOUR_PRIVATE_KEY]` with your private key.

The code imports the "Web3" library, which is a JavaScript library for interacting with the Ethereum blockchain. It provides functions to connect to an Ethereum node, send transactions, and interact with smart contracts.

It also imports the "ethereumjs-tx" library, which is a JavaScript library for constructing and signing Ethereum transactions.

The code then declares two constant variables: daiExchangeAddress and daiExchangeAbi. These variables store the address and ABI (Application Binary Interface) of a Dai exchange contract. The ABI is a JSON-encoded interface definition that describes the functions and events of the smart contract.

By using the Web3 library and the imported ABI, this code can be used to interact with the Dai exchange contract. It allows you to perform various operations such as token purchases, liquidity addition and removal, and token swaps.
