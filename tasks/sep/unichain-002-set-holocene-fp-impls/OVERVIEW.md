# Holocene Hardfork - Proof Contract Upgrades
Upgrades the `MIPS.sol`, `FaultDisputeGame.sol`, and `PermissionedDisputeGame.sol` contracts for Holocene.

The batch will be executed on chain ID `11155111`, and contains `2` transactions.

## Tx #1: Upgrade `PERMISSIONED_CANNON` game type in `DisputeGameFactory`
Upgrades the `PERMISSIONED_CANNON` game type to the new Holocene deployment, with an updated version of `op-program` as the absolute prestate hash.

**Function Signature:** `setImplementation(uint32,address)`

**To:** `0xeff73e5aa3B9AEC32c659Aa3E00444d20a84394b`

**Value:** `0 WEI`

**Raw Input Data:** `0x14f6b1a30000000000000000000000000000000000000000000000000000000000000001000000000000000000000000a83353016019cc8153c6abea91f7989a5b1d4569`

### Inputs
**_impl:** `0xa83353016019cc8153C6AbEA91f7989a5B1d4569`

**_gameType:** `1`


## Tx #2: Upgrade `CANNON` game type in `DisputeGameFactory`
Upgrades the `CANNON` game type to the new Holocene deployment, with an updated version of `op-program` as the absolute prestate hash.

**Function Signature:** `setImplementation(uint32,address)`

**To:** `0xeff73e5aa3B9AEC32c659Aa3E00444d20a84394b`

**Value:** `0 WEI`

**Raw Input Data:** `0x14f6b1a30000000000000000000000000000000000000000000000000000000000000000000000000000000000000000b3ec5385110879ac592fc06de30479f688340dd2`

### Inputs
**_impl:** `0xB3ec5385110879AC592FC06De30479F688340DD2`

**_gameType:** `0`

