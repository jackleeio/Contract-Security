# Smart Contract Security Guide

A comprehensive collection of smart contract security vulnerabilities, real-world examples, and prevention strategies.

## Core Vulnerabilities

### Access Control & Authentication
- [Access Control Vulnerabilities](docs/access-control-exploit.md) - Poly Network ($611M) and ShadowFi ($300K) incidents
- [Bypass Contract Check](docs/bypass-contract-check.md) - Exploiting contract detection mechanisms
- [Transaction Origin Attacks](docs/tx-origin.md) - Phishing attacks using tx.origin
- [Signature Replay Attacks](docs/signature-replay.md) - Wintermute's Optimism incident ($20M)

### Financial Logic
- [Price Manipulation](docs/price-manipulation.md) - Mango Markets incident ($115M)
- [Flashloan Governance Attacks](docs/flashloan-governance-attack.md) - Fei Protocol incident ($80M)
- [Reentrancy Attacks](docs/reentrancy-attack.md) - The DAO hack and Fei Protocol incidents
- [Mixed Balance Accounting](docs/mixed-accounting.md) - Balance tracking vulnerabilities

### Implementation Issues
- [Integer Overflow](docs/overflow.md) - BeautyChain (BEC) token incident
- [Unchecked Low-Level Calls](docs/unchecked-call.md) - King of Ether incident
- [Bad Randomness](docs/bad-randomness.md) - Meebits, Loots, and Wolf Game vulnerabilities
- [Downcasting Issues](docs/downcasting.md) - Safe type conversion practices
- [ERC20 Transfer Issues](docs/erc20-token-transfer.md) - Token transfer implementation risks
- [Selector Collision](docs/selector-collisiion.md) - Poly Network cross-chain bridge hack

### Design Flaws
- [Denial of Service (DoS)](docs/dos-attack.md) - Akutar NFT incident
- [Excessive Restrictions](docs/excessive-restriction.md) - Akutars NFT $34M lock incident
- [msg.value in Loops](docs/msg-value-in-loop.md) - Reuse of msg.value vulnerabilities
- [Input Validation](docs/input-validation.md) - Sushiswap's $3.3M exploit

## General Resources
- [Smart Contract Security Overview](docs/contract-security.md) - Best practices and guidelines

## Contributing

Feel free to submit pull requests to add new vulnerabilities, update existing content, or improve documentation.
