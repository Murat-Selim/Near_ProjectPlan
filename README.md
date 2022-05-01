# https://app.patika.dev/Murat-Selim

# Travel Guide APP

### Travel Guide app on NEAR blockchain, it will help people to make travel choices.

## Usage

- Current version of [Node.js](https://nodejs.org/) <=v16.14.2
- Install dependencies: `yarn install`
- [near-cli] is a command line interface (CLI) for interacting with the NEAR blockchain. 
```npm install -g near-cli``` 

### Getting started

1. clone this repo to a local folder
2. run `yarn build:release` to build the app
3. run `yarn deploy` to deploy the app to the NEAR testnet
4. run `export CONTRACT=YOUR_DEV_ACCOUNT_HERE` 

### Functions

### **createTravel**<br>

* This function creates travel guide on the NEAR blockchain.

### **updateTravel**<br>

* This function updates travel guide on the NEAR blockchain. all information can be updated.

### **deleteTravelById**<br>

* This function deletes travel guide by id on the NEAR blockchain.


### **getTravels**<br>

* This function returns all travel guide on the NEAR blockchain.

### **getTravelById**<br>

* This function returns travel guide by id on the NEAR blockchain.

### **getTravelByOwner**<br>

* This function returns travel guide by ownerId on the NEAR blockchain.
