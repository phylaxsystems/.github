![Phylax Logo](./phylax-logo.png)

# Phylax Systems

Phylax was founded in the aftermath of the $200mm Nomad hack and is backed by $4.5mm from Nascent, Figment Capital, Robot Ventures, and other leading investors and angels.

**Adoption requires trust, and trust requires security.**

## The Credible Layer

The Credible Layer is a network extension that enables apps to define security rules and prevents transactions from violating them. These rules—called **assertions**—are defined in Solidity, executed off-chain, and enforced on-chain.

### How It Works

1. **Define rules in Solidity** — Write assertions that specify states your protocol should never reach. No contract modifications required.
2. **Network validation** — The network checks each transaction against your assertions before block inclusion.
3. **Transaction blocking** — Violating transactions are dropped and never execute.

### Key Benefits

- **Pre-execution prevention** — Exploits are blocked before they execute, not detected after
- **No contract changes** — Protect any contract, including immutable ones
- **Transparent & verifiable** — All rules are public Solidity code, auditable by anyone
- **Zero false positives** — Binary enforcement based on rules, not probabilistic methods

## Key Repositories

### Core Tools

| Repository | Description |
|------------|-------------|
| [**pcl**](https://github.com/phylaxsystems/pcl) | CLI tool for testing, authenticating, storing and submitting assertions |
| [**phoundry**](https://github.com/phylaxsystems/phoundry) | Modified Foundry with Credible Layer support—a drop-in replacement for `dapp` and `seth` |
| [**credible-layer-dapp**](https://github.com/phylaxsystems/credible-layer-dapp) | Web interface for viewing and managing Phylax projects and assertions |

### Libraries & SDKs

| Repository | Description |
|------------|-------------|
| [**credible-std**](https://github.com/phylaxsystems/credible-std) | Standard library providing utilities and cheatcodes for writing assertions |
| [**credible-sdk**](https://github.com/phylaxsystems/credible-sdk) | SDK for integrating with the Credible Layer |

### Infrastructure

| Repository | Description |
|------------|-------------|
| [**credible-layer-contracts**](https://github.com/phylaxsystems/credible-layer-contracts) | On-chain smart contracts for the Credible Layer |

### Examples & Getting Started

| Repository | Description |
|------------|-------------|
| [**credible-layer-starter**](https://github.com/phylaxsystems/credible-layer-starter) | Starter templates that work out of the box |
| [**assertion-examples**](https://github.com/phylaxsystems/assertion-examples) | Collection of assertion examples including real-world hacks that could have been prevented |

## Get Started

Install the CLI and write your first assertion in minutes:

```bash
# Install pcl via Homebrew
brew install phylaxsystems/pcl/pcl
```

Visit our [documentation](https://docs.phylax.systems/) for comprehensive guides on writing assertions, testing, and deployment.

## Connect

- [Documentation](https://docs.phylax.systems/)
- [X (Twitter)](https://twitter.com/phylaxsystems)
