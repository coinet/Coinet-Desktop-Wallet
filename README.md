[![Travis CI status](https://www.travis-ci.org/stellarchat/desktop-client.svg?branch=master)](https://travis-ci.org/stellarchat/desktop-client)

# Coinet Wallet (A Desktop Client for Stellar)

Coinet Wallet allows you to encrypt your secret key and store it as a file locally on your computer. You can use it on Windows, Linux and Mac.

## Key Features

- No registration. Secret key and login information stored locally.
- Offline transaction signing. Protect the secret key from exposure to the Internet.
- Send/receive/convert lumens, assets and tokens.
- Buy/sell lumens, assets and tokens.
- Merge account.
- Create your own tokens.
- View balances and history.
- Manage trust lines, account data, inflation destination.
- Federation protocol support.
- Contacts support.
- Deposit/withdraw COT, BTC.
- Participate ICO

## Build

You should have Node.js (4.8.x recommended) installed. If not, install it ([Node version manager](https://github.com/creationix/nvm) is recommended).

You need to install [nwjs](https://nwjs.io) if you want to do development.  

- Run `npm install`
- You need to create a softlink under the src folder, so it can find the node_modules files. You can run `ln -s ../node_modules ./src/node_modules`. In windows, you can run `mklink /d d:\ProjectName\src\node_modules d:\ProjectName\node_modules`
- Run `nw src` to develop or run `node build-nw.js` to build


