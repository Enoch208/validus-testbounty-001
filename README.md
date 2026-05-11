# Validus testbounty 001

Throwaway repo for testing the Validus Franklin plugin against a real
Base Sepolia USDC payout. Bounties live in `bounties.json`.

## What This Repo Is For

This repository exists to exercise a minimal bounty flow in a low-risk
setting:

- open an issue
- make a small contribution
- submit a pull request that closes the issue
- verify payout metadata stored in the repository

## Bounty Metadata Format

Each object in `bounties.json` maps a GitHub issue to payout details:

- `issue`: GitHub issue number
- `amount`: bounty amount
- `token`: payout token
- `chain`: payout network
- `description`: short human-readable summary

## Current Test Bounty

Issue `#1` is the active test bounty in this repository. It currently offers
`0.05` `USDC` on `base-sepolia` for a README update that closes the issue.
