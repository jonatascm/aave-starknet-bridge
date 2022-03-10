# L2 AAVE rewards

A staticAToken bridge to Starknet for cheap AAVE rewards collection and token
exchange.

## Architecture

<!-- insert architecture image -->

## Testing

The project is tested using [hardhat](https://hardhat.org/), the [starknet
hardhat plugin](https://github.com/Shard-Labs/starknet-hardhat-plugin),
[starknet-devnet](https://github.com/Shard-Labs/starknet-devnet), and
[ganache](https://trufflesuite.com/ganache/index.html).

### Prerequisites

```bash
yarn global add ganache

python3.7 -m venv .venv
source .venv/bin/activate
pip install starknet-devnet
```

### Start the testnets

It's wise to do this in two separate shells

```bash
ganache
```

```bash
starknet-devnet
```

### Run the tests

```
yarn test
```
