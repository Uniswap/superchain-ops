# 008-Unpause the SuperchainConfig

Status: [EXECUTED](https://sepolia.etherscan.io/tx/0x651997781b3e74e73cfa63eefab506c086799c5017b23abf146dd7c211215359)

## Objective

This would be part of the unpausing of sepolia following the pause of the superchain since we are testing that U13 upgrade for the Pause mechanism is working as expected.
This task **unpause** the SuperchainConfig contract. This will first check if the Superchain is `paused`. If this is not `paused` we will skip the execution of this task.
If this is the SuperchainConfig is `paused` we will unpause the SuperchainConfig.
This task, is a single task and has to be signed by the **FondationOperationsSafe**.

<img width="1131" alt="image" src="https://github.com/user-attachments/assets/e9ff041e-07e1-4ae7-8cb0-de86c3e601fc" />

### Timing

- Expected to be executed on or around 2025-04-11 or 12.

## Transaction creation

The transaction is generated by the UnPauseSuperchainConfig template script, which reads the inputs from the config.toml file.

## Signing and execution

When simulating, ensure the logs say: `Using script src/improvements/template/UnPauseSuperchainConfig.sol` \
Navigate to the correct task directory then run the simulate command:

```bash
cd sep/008-unpause-superchain-config \
SIMULATE_WITHOUT_LEDGER=1 just \
   --dotenv-path $(pwd)/.env \
   --justfile ../../../single.just \
   simulate \
   0
```
