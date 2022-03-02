# Emi's Wave Portal 
This project is based on https://app.buildspace.so/ introductory project for learning solidity and Ethereum. 

*How do you actually run this?* <br />
<br />
The best way to run this project on the `rinkeby` test network is done by running: 
<br />
    `npx hardhat run scripts/deploy.js --network rinkeby`
<br />
<br />
For it to work, you need to create an alchemy account, get your key, and use Metamask and get your private key. 
<br /> 
With that information, you would create a `.env` file and put it there: 
<br />
```shell
STAGING_ALCHEMY_KEY=BLAHBLAH
PROD_ALCHEMY_KEY=BLAHBLAH
PRIVATE_KEY=BLAHBLAH
```
<br /> 
Hardhat basic commands: 

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```
<br />
*Sample UI, currently lives in Rinkeby network at: `0x55E0456a107F70b24C4107c25101651B42F1ED09`
<br />

![demo](https://user-images.githubusercontent.com/92827957/156304225-bfddaf9d-c40b-4d5c-9ccc-433ed850304c.png)
