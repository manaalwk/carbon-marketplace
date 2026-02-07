# Carbon Marketplace — Tokenized Carbon Credits (Creditcoin)

A decentralized marketplace concept to **buy, sell, and retire tokenized carbon credits**, with transparent tracking of environmental impact on-chain.

## What it does
- **Issuer** mints carbon credit tokens for verified projects
- **Buyers** purchase credits to offset emissions or invest
- **Sellers/Project owners** list credits they earned
- **Retire** credits to permanently mark them as used (impact accounting)

## Tech Stack
- `contracts/` — smart contracts for credit tokens + marketplace flow
- `frontend/` — UI for listing, buying, and retiring credits
- `docs/` — notes/specs

## Run Locally

### Contracts
```bash
cd contracts
# install & run depending on your tooling
```
## Frontend
cd frontend
npm install
npm run dev

## Repo Structure
contracts/ — token + marketplace contracts
frontend/ — user-facing app
docs/ — scope/spec notes

## Roadmap
 1.Standardize token model (ERC20/1155-like)
 2.Add retirement certificate / proof
 3.Indexing layer (events → UI)
 4.Access control + issuer verification flow
