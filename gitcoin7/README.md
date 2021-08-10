# Gitcoin: 7) Port An Existing Ethereum DApp To Polyjuice

## [DEMO (VIDEO)](https://youtu.be/raUOXnUkxrk)

Screenshot of my application running on Godwoken:

![Screenshot of my application running on Godwoken](https://github.com/nicky-ru/nervos/blob/7a62a24bf4e456dd4e3047b2ee0677cf4ffff9ce/gitcoin7/Screen%20Shot%202021-08-10%20at%206.32.53%20PM.png)

### [Link to the GitHub repository with your application which has been ported to Godwoken.](https://github.com/nicky-ru/blockchain-workshop)

Deployed contract address: 0x9b03179b41f3ab51863aD9E3734Ff4a66887bC10
Deploy transaction hash: 0x5a2d17515a29aac604ec0b152b04e7470fa74af3582dfbee2ae4bdfcfbd3df3c

```json
"abi": [
    {
      "stateMutability": "payable",
      "type": "receive"
    },
    {
      "inputs": [],
      "name": "DynamicPyramid",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "receiveCoins",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "init",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "address payable",
          "name": "_owner",
          "type": "address"
        }
      ],
      "name": "changeOwner",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "_mult",
          "type": "uint256"
        }
      ],
      "name": "changeMultiplier",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "_fee",
          "type": "uint256"
        }
      ],
      "name": "changeFeePercentage",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "currentMultiplier",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "multiplier",
          "type": "uint256"
        },
        {
          "internalType": "string",
          "name": "info",
          "type": "string"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "currentFeePercentage",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "fee",
          "type": "uint256"
        },
        {
          "internalType": "string",
          "name": "info",
          "type": "string"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "currentPyramidBalanceApproximately",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "pyramidBalance",
          "type": "uint256"
        },
        {
          "internalType": "string",
          "name": "info",
          "type": "string"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "nextPayoutWhenPyramidBalanceTotalsApproximately",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "balancePayout",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "feesSeperateFromBalanceApproximately",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "fees",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "totalParticipants",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "count",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "numberOfParticipantsWaitingForPayout",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "count",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]
```