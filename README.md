# Multicall 

Utility repository for deploying Multicall to the Autobahn Network Canary. Requires [hardhat](https://hardhat.org/). 

## Install dependencies

`npm install`

## Compile

`npm run compile`

## Deploy

Set your private key as an env and make sure to delete the env and your shell history afterwards:

`export PRIVATE_KEY=<your-private-key>`

Run the deploy command:

`npm run deploy -- --network autobahn-canary`