# BlinkChain - Blockchain console application in java

### Introduction
The `src` folder consists of basic classes required to implement a blockchain application in java.

### Prerequisites
+ An IDE/Editor (I used Intellij)
+ Java/JDK 1.7
+ The `lib` folder contains `google-gson:2.8.5` (external library) for parsing JSON.

  That's all to get you running.

### Output

```
Trying to mine block 1...
Block Mined!!! : 188c02cba5ccea0ddddee0bf177a1904764466586838d4705946090d991096d6
Trying to mine block 2...
Block Mined!!! : 467075984118919f11abba12e8a865791ce5b89678bb865e29f2dab163d8dbb6
Trying to mine block 3...
Block Mined!!! : 677738e5345dcf0a5ad952fb28dd2aef07b633a1d5458f59b304f5d9a92e9295
Blockchain is valid : true

[
  {
    "hash": "188c02cba5ccea0ddddee0bf177a1904764466586838d4705946090d991096d6",
    "previousHash": "0",
    "data": "Hi im the first block",
    "timeStamp": 1550415653273,
    "nonce": 0
  },
  {
    "hash": "467075984118919f11abba12e8a865791ce5b89678bb865e29f2dab163d8dbb6",
    "previousHash": "188c02cba5ccea0ddddee0bf177a1904764466586838d4705946090d991096d6",
    "data": "Yo im the second block",
    "timeStamp": 1550415653288,
    "nonce": 0
  },
  {
    "hash": "677738e5345dcf0a5ad952fb28dd2aef07b633a1d5458f59b304f5d9a92e9295",
    "previousHash": "467075984118919f11abba12e8a865791ce5b89678bb865e29f2dab163d8dbb6",
    "data": "Hey im the third block",
    "timeStamp": 1550415653288,
    "nonce": 0
  }
]
```
Your's output will be different because of a different timestamp.
