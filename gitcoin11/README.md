# Gitcoin: 11) Use A Tron Wallet To Execute A Smart Contract Call

A screenshot of the accounts I created in ckb-cli.

![Screenshot of the console output](PUTLINKHERE)

[A link to the Layer 1 address I funded on the Testnet Explorer.](https://explorer.nervos.org/aggron/address/ckt1qyqfsfpm67mgre4jdn4gx2ptnrh2ylvpxdkqhmxy7r)

A screenshot of the console output immediately after I have successfully submitted a CKByte deposit to my Tron account on Layer 2.

![Screenshot of the console output](PUTLINKHERE)

A screenshot of the console output immediately after I have successfully issued a smart contract calls on Layer 2.

![Screenshot of the console output](PUTLINKHERE)

### Write call tx: 0x57bbfa381ff2369150be8e1f0fdff94b372d4682303f3b3f580d57557d522e64

### Contract address: 0x8d0E013e3445b370814B3b743721d5d40949Db62

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

### Tron address: TQuCZdWho17BSek2nk3W2NBtkmheVTa7Lj