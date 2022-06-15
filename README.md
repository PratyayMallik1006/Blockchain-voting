# Blockchain-voting
![alt text](https://github.com/PratyayMallik1006/Blockchain-voting/blob/main/ss.PNG?raw=true)

## Usage

1. Install npm package manager and node : `sudo apt install nodejs` , `sudo apt install npm`
2. Install truffle : `npm install -g truffle`
3. Install Ganache : https://www.trufflesuite.com/ganache
4. Run `truffle compile` from the project directory in terminal
5. Start the Ganache and choose `Quickstart Ethereum`
6. Make sure that the local host url on Ganache and in `truffle-config.js` is same.
6. Then on terminal run `truffle test`
6. Then run `truffle migrate --reset`
7. Then run `npm run dev`. This will start the project in the browser
8. Make sure that your metamask is connected to the site (Import accounts from Ganache blockchain into metamask).

