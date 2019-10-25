# blockchainExample
Basic Blockchain

#Console log for a blockchanin create operation 
Trying to Mine Genesis block ... 
Block Mined!!! : 0000081174c30fe2ed672377363979b4d244a0186de8f7e913cf085281984b24
Trying to Mine block 2... 
Block Mined!!! : 000001607e36f8ec9aa100b7ce50f4d591f492f9e7fd7bc7400211fd4f0dbb8e
Trying to Mine block 3... 
Block Mined!!! : 000009e4324fe70f7de4880fc1cc5b321119304a26a7e448e4d5052b606a40c7

Blockchain is Valid: true

The block chain: 
[
  {
    "hash": "0000081174c30fe2ed672377363979b4d244a0186de8f7e913cf085281984b24",
    "previousHash": "0",
    "data": "Hi im the first block",
    "timeStamp": 1571988364966,
    "nonce": 16854
  },
  {
    "hash": "000001607e36f8ec9aa100b7ce50f4d591f492f9e7fd7bc7400211fd4f0dbb8e",
    "previousHash": "0000081174c30fe2ed672377363979b4d244a0186de8f7e913cf085281984b24",
    "data": "Yo im the second block",
    "timeStamp": 1571988365146,
    "nonce": 863522
  },
  {
    "hash": "000009e4324fe70f7de4880fc1cc5b321119304a26a7e448e4d5052b606a40c7",
    "previousHash": "000001607e36f8ec9aa100b7ce50f4d591f492f9e7fd7bc7400211fd4f0dbb8e",
    "data": "Hey im the third block",
    "timeStamp": 1571988370110,
    "nonce": 1579784
  }
]