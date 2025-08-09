# Dawn DePIN

A bootstrapped repository template for the Dawn DePIN network — a decentralized physical infrastructure network focused on [describe: e.g., sensor deployment, connectivity, charging stations].

## About

Dawn is a modular DePIN stack combining on-chain governance, an off-chain data indexer, and an optional dashboard for operators and token holders.

### Components
- `contracts/` — Smart contracts (token, staking, rewards, registry)
- `backend/` — Indexer, relayer, reward calculation microservices
- `frontend/` — Dashboard / dApp for node operators and users
- `infra/` — Deployment manifests and infra-as-code definitions
- `docs/` — Architecture, tokenomics, and governance docs

## Quick start (local)

```bash
# clone
git clone <your-repo-url>
cd Dawn-DePIN

# install (example for monorepo with npm workspaces)
cd frontend && npm install
cd ../backend && npm install

# run locally (frontend)
cd frontend && npm run dev

# run backend
cd backend && npm run dev
