# Blockchain Session Reference

## Installing
<i>Make sure you have nodejs installed</i>
```
npm install ethereumjs-testrpc -g
npm install truffle -g
```

## Development

```
mkdir mycoin
cd mycoin
truffle unbox tutorialtoken
npm install zeppelin-solidity
```

**Edit truffle.js and replace port 7545 by 8545**
Now write your token contract in `contracts/TutorialToken.sol` file. <br/>
Create the file `2_deploy_contracts.js` in `migrations` folder. <br/>

## Running test network

`testrpc -m <your seed words from metamask>`

## Running you DAPP!!
Run this inside the project folder
```
truffle migrate --reset
npm run dev
```

Now open http://localhost:3000 in your browser.

## Links
https://github.com/mdakram28/blockchain-session

https://github.com/mdakram28/blockchain-session/blob/master/Ethereum%20Explained.ipynb


