---
id: overview
sidebar_position: 1
title: Overview
---
## Uniswap APIs
Welcome to the Uniswap API documentation. Uniswap provides several APIs and data sources to help developers integrate with and build on top of the Uniswap protocol.
## Available APIs
### Trading API
The Uniswap Trading API is a production-ready solution for institutional and professional integrations, providing access to swapping and liquidity provision features.
- **Swapping & Trading** - Swap tokens, bridge across chains, and access limit orders
- **Liquidity Provision** - Create, modify, and remove liquidity positions across protocol versions
- **UniswapX Integration** - Access to intent-based RFQ swap mechanisms (UniswapX_V2 and UniswapX_V3)
- **Multi-Chain Support** - Available across 14+ blockchains including Ethereum, Arbitrum, Base, Optimism, Polygon, Solana, Unichain, and more
- **Deep Liquidity Access** - Connect to public, private, and off-chain liquidity with MEV protection
- **Smart Features** - Support for batched actions (EIP-5792), smart wallets (EIP-7702), and Permit2 token approvals
**Getting Started**: Visit [hub.uniswap.org](https://hub.uniswap.org) to request API access
### Subgraph API
The Uniswap Subgraph provides a GraphQL API for querying historical and real-time data from the Uniswap protocol, supporting v2, v3, and v4.
- **[Subgraph Documentation](./subgraph/overview)** - Learn how to query Uniswap data using GraphQL
- **[Subgraph Examples](./subgraph/guides/v4-subgraph-example)** - Practical examples and queries
- **[v3 Subgraph Guide](./subgraph/guides/v3-subgraph-example)** - Legacy v3 protocol queries
### Protocol Versions
Uniswap currently supports multiple protocol versions, each with unique features:
- **Uniswap v4** (Launched January 2025) - Introduces customizable hooks, native ETH support, gas optimizations, and singleton architecture
- **Uniswap v3** - Features concentrated liquidity and multiple fee tiers (0.05%, 0.30%, 1%)
- **Uniswap v2** - Classic constant product market maker
- **Uniswap v1** - Original ETH-paired automated market maker
## Getting Started
### For Developers
Choose the right API based on your needs:
- **Production Trading & LP Integration** → Use the **Trading API** (requires API key from hub.uniswap.org)
- **Historical Data & Analytics** → Use the **Subgraph API**
- **Price Data & Market Information** → Use the **Subgraph API**
### For Data Analysis
The Subgraph API is perfect for:
- Analytics dashboards
- Trading strategy research
- Protocol metrics and insights
- DeFi research and analysis
### For Institutional Users
The Trading API offers:
- Competitive pricing with an average 4.6 basis point price improvement
- Simplified DeFi trading with automated gas estimates and routing
- Secure, production-ready infrastructure trusted by Ledger, Talos, OKX, Anchorage Digital, and more
- Access to thousands of tokens across 14+ blockchains
## Key Features (2025-2026)
### Uniswap v4 Innovations
- **Hooks System** - Over 150 hooks developed, enabling custom AMM features like dynamic fees, time-weighted average market makers (TWAMM), and automated liquidity management
- **99.99% Gas Savings** - Creating new pools is up to 99.99% cheaper than previous versions
- **Native ETH Support** - Direct ETH trading without wrapping, reducing gas fees by ~15%
- **Singleton Architecture** - All pools managed in a single contract for efficient routing
### Protocol Governance Updates
As of late 2025, Uniswap governance approved the UNIfication proposal, which:
- Activated protocol fees across v2 and v3 pools
- Introduced a deflationary UNI token mechanism through fee-driven burns
- Burned 100 million UNI from the treasury
## API Access & Rate Limits
- **Trading API**: Requires API key - apply at [hub.uniswap.org](https://hub.uniswap.org)
- **Subgraph API**: Publicly accessible via The Graph with generous rate limits
- **Production Support**: Enterprise-grade infrastructure used by millions of users
## Support and Resources
- **API Documentation**: [api-docs.uniswap.org](https://api-docs.uniswap.org)
- **Discord**: Join the Uniswap developer community
- **GitHub**: Explore code examples and integrations
- **Twitter/X**: Follow [@Uniswap](https://twitter.com/Uniswap) for updates
Ready to start building? Choose the API that fits your needs from the navigation menu or visit hub.uniswap.org to get started with the Trading API.
