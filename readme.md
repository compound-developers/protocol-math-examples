# Compound Math Questions

Code answers to commonly asked math calculations when developing with the Compound Protocol.

## What is Compound?
Compound is an open-source, autonomous protocol built for developers, to unlock a universe of new financial applications. Interest and borrowing, for the open financial system. Learn more on the website:

<a href="https://compound.finance/?ref=github&user=ajb413&repo=compound-supply-examples">
    <img alt="Compound Finance" src="https://raw.githubusercontent.com/ajb413/compound-interest-alerts/master/compound-finance-logo.png" width=260 height=60/>
</a>

## Setup
If you haven't already, install [Node.js](https://nodejs.org/) LTS. Clone this repository, `cd` to the root directory of the project, and run:
```bash
git clone git@github.com:compound-developers/protocol-math-examples.git
cd protocol-math-examples
npm install
```

To access the blockchain, each of the scripts use [Infura](https://infura.io). Add your Infura project key (it's free) as an environment variable. Or run each script on the command line like this: `infuraApiKey="_key_here_" node someScript.js`

Each of the hard coded main net contract addresses and ABIs can be found here: https://compound.finance/docs#networks

## Questions and Answers

### How many decimals are in a cToken contract?

```
node decimals.js
```

### How Do I Calculate the Exchange Rate of a cToken to its Underlying?

```
node exchangeRate-cTokenToUnderlying.js
```

### How Do I Calculate the Exchange Rate of an Underlying to its cToken?

```
node exchangeRate-underlyingToCToken.js
```

### How Do I Calculate APY from the Rate Per Block?

```
node apy.js
```
