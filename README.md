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
```

Now you can write and save your contracts in 'contracts' folder.

## Running test network

`testrpc -m <your seed words from metamask>`

## Running you DAPP!!
Run this inside the project folder
```
truffle migrate
npm run dev
```

Now open http://localhost:8080 in your browser.