# 045-U17-uni

Status: [READY TO SIGN]

## Objective

This task upgrades Unichain Alphanet to U17.

## Simulation & Signing

Simulation commands for each safe:
```bash
cd src/tasks/sep/045-U17-uni-alphanet
just simulate-stack sep 045-U17-uni-alphanet
```

Signing commands for each safe:
```bash
cd src/tasks/sep/045-U17-uni-alphanet
just --dotenv-path $(pwd)/.env sign
```
