# 059-U18-uni

Status: [READY TO SIGN]

## Objective

U18 on Unichain Sepolia.

## Simulation & Signing

### For Signers

```bash
# Change directory to the correct task
cd src/tasks/sep/059-U18-uni

# Command to simulate
just simulate-stack sep 059-U18-uni

# Command to sign
just sign-stack sep 059-U18-uni
```

### For Facilitators, after signatures have been collected

```bash
# Change directory to the correct task
cd src/tasks/sep/059-U18-uni

# Command to approve
SIGNATURES=0x just approve

export SIGNATURES=0xc5335acad4965a898ca3f230affd95128ed06efdda38d5f1ae302dc723b8e9c52bebc096f155840c231f56c8d2592ef64ae8b84f7e96e21117192f010b406a2f1bf8e1f20182b2c6736155430786e8fe6cde007c357caba8fdbf525c5fdccf1cec2090a7e128cac3d70d4dbede048c2e04f19dd14f609637f805744d57fd6a67a31b

# Command to execute
just execute

# Add USE_KEYSTORE=1 to the above if you are using a local keystore instead of a connected Ledger
```
