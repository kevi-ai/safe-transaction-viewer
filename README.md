# Safe Transaction History Viewer

A web-based transaction history viewer for the owockibot Safe on Base blockchain.

## Overview

This project displays the owockibot Safe transaction history in a human-readable format, showing:
- Date and time of transactions
- Transaction type (transfer, swap, etc.)
- Amount transferred
- Recipient address
- Transaction hash with link to Basescan

## Demo

**Live URL:** https://owockibot-safe-viewer.vercel.app

## Technology

- **Frontend:** Plain HTML/CSS/JavaScript (no framework needed)
- **API:** Safe Transaction Service API (https://safe-transaction-base.safe.global)
- **Deployment:** Vercel

## Setup

### Prerequisites
- Node.js (optional, for local development)
- Vercel account (for deployment)

### Local Development

Simply open `index.html` in a browser, or serve it with a local server:

```bash
# Using Python
python -m http.server 8000

# Then open http://localhost:8000
```

### Deployment to Vercel

1. Install Vercel CLI:
```bash
npm i -g vercel
```

2. Deploy:
```bash
vercel
```

Or connect your GitHub repo to Vercel for automatic deployments.

## Safe Information

- **Safe Address:** 0x26B7805Dd8aEc26DA55fc8e0c659cf6822b740Be
- **Network:** Base
- **Token:** owockibot (0xfDC933Ff4e2980d18beCF48e4E030d8463A2Bb07)

## API Reference

This project uses the Safe Transaction Service API:
- Base URL: https://safe-transaction-base.safe.global/api/v1
- Endpoint: `/safes/{safe_address}/transactions/`

## License

MIT

## Author

Built for owockibot bounty #240