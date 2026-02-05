# Synergy Alert Bot

A professional Telegram bot built for real-time price monitoring and alerts across Deriv markets. It supports automated subscription management and multi-network crypto payments.

## Core Features
- **Real-time Price Alerts**: Support for Volatility Indices (Synthetics), Forex, Commodities, Cryptocurrencies, and Stock Indices.
- **Subscription Levels**: Tiered access system (Trial, Basic, Premium) with varying alert limits and market coverage.
- **Multi-Network Payments**: Integrated with NowPayments to support USDT (TRC20, BEP20, SOL), USDC, BNB, ETH, and native SOL.
- **Automated Activation**: Real-time IPN webhook handling for instant account upgrades upon payment confirmation.
- **Service Architecture**: Separate processes for the bot interface and the backend price-monitoring worker.

## Details
- **Bot**: [Take on the 7-Days trial](https://t.me/synergyalertbot)
- **Framework**: `python-telegram-bot` (v20.x, Async/Await)
- **Database**: MongoDB (via `motor` for async I/O)
- **APIs**: Deriv WebSocket API (Market data), NowPayments API (Finance)
