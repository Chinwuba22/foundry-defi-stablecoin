# Foundry DeFi Stablecoin

# About

This project is meant to be a stablecoin where users can deposit WETH and WBTC in exchange for a token that will be pegged to the USD.

## Quickstart

```
git clone https://github.com/chinwuba22/foundry-defi-stablecoin
cd foundry-defi-stablecoin
forge build
```

# Usage

## Start a local node

```
make anvil
```

## Deploy

This will default to your local node. You need to have it running in another terminal in order for it to deploy.

```
make deploy
```

## Testing

This only covers two types of test

1. Unit
2. Fuzz

```
forge test
```

### Test Coverage

```
forge coverage
```

and for coverage based testing:

```
forge coverage --report debug
```
