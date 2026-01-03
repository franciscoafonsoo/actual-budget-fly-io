# Actual Budget Server on Fly.io

This repository contains the configuration for deploying [Actual Budget](https://actualbudget.org/) server to [Fly.io](https://fly.io/).

## Getting Started

To launch a new app:
```bash
fly launch
```
Modify region and app name as needed.

## Updates

To update to latest version:
```bash
fly deploy
```

## Cost Notes

Costs are kept below $5, which should be free within Fly.io limits. Machines up to 1GB should be within free tier.
