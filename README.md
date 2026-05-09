# Validus testbounty 001

Throwaway repo for testing the Validus Franklin plugin against a real
Base Sepolia USDC payout. Bounties live in `bounties.json`.

## How it works

1. Maintainer commits `bounties.json` with one entry per fundable issue
2. Contributor opens a PR that says `closes #N`
3. Contributor posts a comment with their payout wallet:
   `validus-payout: 0xYOUR_BASE_SEPOLIA_ADDRESS`
4. Maintainer (or anyone) submits the PR URL via Validus
5. Validus reviews it across smart-routing tiers and signs the USDC payout
