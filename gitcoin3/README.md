# Gitcoin: 3) Issue A Smart Contract Call To The Deployed Smart Contract

This is a screenshot of the console output immediately after I have successfully issued a smart contract call.

![screenshot of the console output](https://github.com/nicky-ru/nervos/blob/c416f55bb30eb3cde6ec14fce01da68daacaf2ec/gitcoin3/console_screenshot.png)

This is the transaction hash from the console output:

### 0xa988a10fc038e7bba0b1e06b7c9bffe6b85a0f426df2fe1945e8249bddb0c8fe

This is the contract address that I called:

### 0x8d0E013e3445b370814B3b743721d5d40949Db62

This is the ABI for contract I made a call on:


```json
[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]
```