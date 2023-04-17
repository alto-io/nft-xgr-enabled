# NFT - XGR

### Starting the App

Running the app

1. install your dependencies, `open a new command prompt`

   ```bash
   yarn install
   ```

2. start a local hardhat node (chain)

   ```bash
   anvil
   ```

4. Run the app, `open a new command prompt terminal`

   ```bash
   # in a new terminal
   # compile your contracts
   yarn compile
   # deploy your hardhat contracts
   yarn deploy
   # start the next-js app
   yarn start
   ```

5. Open http://localhost:3000 to see your front end


### Foundry

Make sure you install foundry

1. Make sure you install foundry first. Use `curl -L https://foundry.paradigm.xyz | bash` to install foundryup

   > You can see more details here. https://book.getfoundry.sh/getting-started/installation

2. Run `yarn install:foundry` to install or update foundry in the right folder. It will also run _forge install_ automatically with the right context.

You can use foundry commands with the right context

```bash
yarn forge
yarn anvil
yarn cast
```