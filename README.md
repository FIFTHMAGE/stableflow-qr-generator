# StableFlow — Merchant Graphic Generator

A lightweight, browser-based web application to dynamically generate branded crypto payment QR graphics for merchants.

## Features

- **High-Resolution Canvas Export**: Generates 1080x1125 PNG merchant posters formatted for display or printing.
- **Custom Merchant Branding**:
  - Upload custom business logos (PNG/SVG).
  - Fallback business name rendering in Gold Serif or Navy Sans typography.
- **Dynamic Wallet Encoding**: Encodes crypto wallet addresses into styled, scannable QR codes with center branding logos.
- **Asset & Network Badge Displays**: Displays supported cryptocurrencies (USDC, USDT) and blockchain networks (Base, Ethereum, BNB Chain, Polygon, Optimism, Avalanche, Arbitrum).
- **One-Click PNG Download**: Exports graphics with clean filename formatting (`stableflow-<merchant-name>.png`).

## Getting Started

Simply open `index.html` in any web browser. No build steps or server dependencies required!

## Tech Stack

- HTML5 Canvas
- Tailwind CSS
- [qr-code-styling](https://github.com/kozakdenys/qr-code-styling) library
