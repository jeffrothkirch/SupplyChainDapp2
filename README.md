# Project6 - Blockchain Supply Chain Project

## Installation

#### Install project dependencies:

```
$ npm install -g truffle@4.1.15
$ npm install --save truffle-hdwallet-provider@1.0.17

npm install webpack-dev-server -g
npm install web3

$ npm build
```
## Deployed to Rinkeby:

#### Transaction Hash:

0xff1381a874476b36410e050c45d36aca5c111e2971364f01ae01cce6c2d3c662

#### Contract

0xd248575517C76D61Fd6d5e4505DC9fe57fca4B2a


## Other Rubric Requirements:

#### Is IPFS Used:
No

#### Node Version:
v14.16.1

#### Truffle Version:
v5.3.9

Truffle provides much of the functionality possible of this app. Truffle facilitates testing, deployment, and development. Furthermore, it helps to 
provide a fully integrated test environment so that it does not need to be done manually. It is used in this project specifically to create a development 
enironment so that I can test the application functionality. It is also used to run the test cases.

#### Web3 Version:
v1.3.6

Web3 is a collection of javascript libraries that allow an application to interact with an ethereum network. It is being used extensively in this application to 
encapsulate much of the logic around the etherum blocchain. For example, it is used to convert wei to ethereum and back, it is used to encapsulate logic of big numbers, 
and also allows us to interact with Metamask.

#### How To Run Tests:

```
$ truffle develop
$ truffle test
```


#### How To Run Front End:

I use the Live Server Visual Studio extension. Install the extension, select the index.html file, and click 'Go-Live' in the bottom right

#### How To Use the Front End:

I have already set the wallet addresses the following items below. These are from my personal Metamask, you can change this if you would like.
1. Current Ownser ID
2. Farmer ID
3. Distributor ID
4. Retailer ID
5. Distributor ID

You will also need to enter a SKU, UPC, Farm Name, Farm Info, and Product Price in the fields on the website. You can also enter data for Farm Information, latitude, and longitude if you would like.

Once this is done, you can invoke the workflow at any time by clicking the following buttons IN ORDER.
1. Harvest
2. Process
3. Pack
4. For Sale
5. Buy
6. Sell
7. Receive
8. Purchase

At any time, you can use the 'Fetch Data 1' and 'Fatch Data 2' buttons to get data from the blockchain.

