# Ahoj.Token

Ahoj.Token is a decentralized elastic supply protocol. It is forked from Ampleforth which operates under the codename "uFragments". This monetary protocol maintains a stable unit price by adjusting supply directly to and from wallet holders.

This repository is a collection of smart contracts that implement the Ahoj.Token protocol on Avalanche.

The challenge with the Ahoj.Token protocol is to coordinate the balance of the Ahoj assets issued on the X-chain and exported to the C-chain. The first approach adopted is that in the original Ampleforth / uFragment protocol the "gnos" can be considered the existing Ahoj assets in the C-chain.

Ahoj is a Czech word from English ahoy. The word Ahoj is used to say *Hello* (informal greeting said when meeting someone) or inclusive to say *Bye* (informal farewell).

## Mainnet
The official Avalanche mainnet addresses are:
### X-chain
- Asset Id: TBD

### C-chain
- ERC-20 Token: TBD
- Supply Policy: TBD
- Orchestrator: TBD
- Market Oracle: TBD
- CPI Oracle: TBD

## Testnet
There is a testnet deployment on Avalanche Fuji.
### X-chain
- Ahoj Token (Asset Id): 2pGHaiML1aAPtV5x9H5TNEYFJPK4DeJgBAT8C784U6WTfBd6VF

### C-chain
- Ahoj Token (ERC-20): TBD
- Supply Policy: TBD
- Orchestrator: TBD
- Market Oracle: TBD
- CPI Oracle: TBD

## Table of Contents

- [Install](#install)
- [Testing](#testing)
- [Contribute](#contribute)
- [License](#license)


## Install

```bash
# Install project dependencies
npm install

# Install ethereum local blockchain(s) and associated dependencies
npx setup-local-chains
```

## Testing

``` bash
# You can use the following command to start a local blockchain instance
npx start-chain [ganacheUnitTest|gethUnitTest]

# Run all unit tests
npm test

# Run unit tests in isolation
npx truffle --network ganacheUnitTest test test/unit/ahoj.js
```

## Contribute

To report bugs within this package, create an issue in this repository.
For security issues, please contact hello@bayro.io.
When submitting code ensure that it is free of lint errors and has 100% test coverage.

``` bash
# Lint code
npm run lint

# View code coverage
npm run coverage
```

## License

[GNU General Public License v3.0 (c) 2020 Bayro](./LICENSE)
