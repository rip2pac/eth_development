# eth_development
Developing on ethereum using Solidity and Node.js

## Environment Setup 

### Installing virtual blockchain environment:

Modelling a full working blockchain envrionment is inefficient and unecessary. 
Setting up an in-memory virtual blockchain envrionment is more appropriate for testing eth applications.
Install a virtual blockchain called <b>testrpc</b>:

```
npm install ethereumjs-testrpc web3@0.20.1
```

### Installing Solidity compiler:

Solidity is a common language used to develop eth applications. 
Solidity codes can be compiled using solc, and they can be ran over the node console:

```
npm install solc 
```
