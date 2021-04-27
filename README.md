# spells

Staging repo for HotDAO's executive spells.

### Getting Started

```
$ git clone https://github.com/HOT-Protocol/spells.git
$ dapp update
```

### Build

```
$ make
```

### Test

Set `ETH_RPC_URL` to a ethereum node.

```
$ export ETH_RPC_URL=<ETH RPC URL>
$ make test
```

### Deploy

Set `ETH_RPC_URL` to a ethereum node and ensure `ETH_GAS` is set to a high enough number to deploy the contract.

```
$ export ETH_RPC_URL=<ETH RPC URL>
$ export ETH_GAS=8000000
$ export ETH_GAS_PRICE=$(seth --to-wei 3 "gwei")
$ make deploy

```
