# Manual bank transfer

Accept bank transfer payments in PeltyCMS checkout

Official payment gateway for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS).

## Why this addon

Hosts who want customers to pay invoices without leaving Pelty checkout.

## Features

- Take invoice and checkout payments through **bank transfer**
- Signed webhook handling so paid invoices mark paid automatically
- Fits Pelty tax, credits, refunds and multi-currency
- Runs as sandboxed WASM — no custom PHP on your panel
- Keys live in Pelty secrets, not in theme code

## How it works

1. Install **Manual bank transfer** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/gateway-manual) inside Pelty Admin → Addons.
2. Open Pelty Admin → Payments, add your bank transfer keys, and enable the gateway on the products you sell.
3. Customers hit checkout / login / order flow as usual — bank transfer runs in the background.

## Requirements

- PeltyCMS with WASM addons enabled
- Working bank transfer credentials
- Outbound HTTPS from your panel

## Get it

**[Manual bank transfer on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/gateway-manual)**

## Support

Bugs and questions for this addon → Issues on this repo.  
PeltyCMS core → https://github.com/MythicalLTD/PeltyCMS
