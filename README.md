# CryptoSoccer

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/34b094f8f6f449d1ba2d636bc18e4e4b)](https://app.codacy.com/app/rtre84/crypto-soccer?utm_source=github.com&utm_medium=referral&utm_content=rtre84/crypto-soccer&utm_campaign=Badge_Grade_Dashboard)

Work in Progress.  

## 💡[Document](./DOCUMENT.md)

### Technical stack

#### Frontend
- React
- Redux
- Saga
- Web3(MetaMask)

#### UI
- Sass
- Material-UI

#### Smart contract/Solidity
- [Truffle](./TRUFFLE.md)

#### Database
- [Bluzelle](./BLUZELLE.md) 
- IPFS Infura (https://infura.io/) npm package ipfs-api


### Install flow

#### Clone repo

```
git clone https://github.com/gwenf/crypto-soccer
cd react-truffle-metamask
```

#### Install ganache

```
npm install -g ganache-cli
```

#### Install truffle

```
npm install -g truffle
```

#### Build repo

```
yarn install
truffle compile
```

#### Start repo

Open a new console
```
ganache-cli
```

```
truffle migrate
yarn start
```

## Reference
- react-truffle-metamask https://github.com/PhyrexTsai/react-truffle-metamask
- ganache-cli: https://github.com/trufflesuite/ganache-cli
- truffle: https://github.com/trufflesuite/truffle

## Parsa Ba