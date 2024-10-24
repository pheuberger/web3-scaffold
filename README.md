# To Get Started

## Frontend

### setup frontend

You need to obtain API keys from [Infura](https://app.infura.io/) and [Alchemy](https://www.alchemy.com/).

To support WalletConnect (./reown), you need to obtain a project id from [./reown Cloud](https://cloud.reown.com/). This is absolutely free and only takes a few minutes.
All of this needs to go into `.env.local`.

Just FYI, the rainbowkit docs are [here](https://www.rainbowkit.com/docs/installation).

```

pnpm install && cp .env.example .env.local

```

### run local

```
pnpm dev
```

### build

```
pnpm build
```

## Smart Contract

### compile

```

npm run compile:hardhat

or
npm run compile:foundry

```

### test

```
npm run test:hardhat

or

npm run test:foundry
```
