<div align="center">

# `📜 Genesis contracts`

> Dusk genesis contracts
</div>

## Overview

The Dusk genesis contracts are part of the genesis state and provide core functionality to the Dusk protocol. Other parts of the protocol are implemented largely in [Rusk](https://github.com/dusk-network/rusk/tree/master).

There are two genesis contracts:

### [Transfer contract](https://github.com/dusk-network/genesis-contracts/tree/main/contracts/transfer)

The transfer contract acts as the entrypoint for any transaction happening on the network and manages the native Dusk token.

The on-chain ContractId for the transfer contract is:

`0100000000000000000000000000000000000000000000000000000000000000`

### [stake](https://github.com/dusk-network/genesis-contracts/tree/main/contracts/stake)

The stake contract tracks public key stakes. It allows users to stake Dusk tokens subject to a maturation period before becoming eligible for consensus participation.

The on-chain ContractId for the stake contract is:

`0200000000000000000000000000000000000000000000000000000000000000`
