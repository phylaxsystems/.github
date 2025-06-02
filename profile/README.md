![Phylax Logo](./phylax-logo.png)

Phylax was founded in the aftermath of the $200mm Nomad hack and is backed by $4.5mm from Nascent, Figment Capital, Robot Ventures, and other leading investors and angels.

Adoption requires trust, and trust requires security.

The Credible Layer is a network extension that enables apps to define security rules and prevents transactions from violating them. These rules are defined in Solidity, executed off-chain, and enforced on-chain.

Since these rules are verifiable, apps can turn implicit security assumptions into an explicit security posture so that users can trust the apps they use.

## Key Repositories

This organization hosts Phylax Systems' open-source components. Key repositories include:

* **[`assertion-da`](https://github.com/phylaxsystems/assertion-da)**: Assertion DA functions as a temporary data availability layer for the Phylax Credible layer. It stores and makes assertions publicly available via a JSON-RPC interface.
* **[`assertion-examples`](https://github.com/phylaxsystems/assertion-examples)**: Contains an extensive collection of assertion examples for different use cases as well as concrete examples of previous hacks that could have been prevented with the Credible Layer.
* **[`assertion-executor`](https://github.com/phylaxsystems/assertion-executor)**: The executor for the Phylax Credible Layer, responsible for validating assertions against transactions.
* **[`credible-layer-contracts`](https://github.com/phylaxsystems/credible-layer-contracts)**: The on-chain contracts for the Credible Layer
* **[`credible-layer-starter`](https://github.com/phylaxsystems/credible-layer-starter)**: A repository that contains a couple of starter projects that work out of the box.
* **[`credible-std`](https://github.com/phylaxsystems/credible-std)**: The standard library for the Phylax Credible Layer, providing utilities and "cheatcodes" for writing assertions.
* **[`OP-Talos`](https://github.com/phylaxsystems/OP-Talos)**: An OP Stack block builder that builds Credible Blocks.
* **[`pcl`](https://github.com/phylaxsystems/pcl)**: A command line tool used for testing, authenticating, storing and submitting assertions.
* **[`phoundry`](https://github.com/phylaxsystems/phoundry)**: A modified version of Foundry that supports the Credible Layer.

For a comprehensive overview of the Credible Layer, please refer to the [Credible Layer documentation](https://docs.phylax.systems/).

> Follow us on [X](https://twitter.com/phylaxsystems)
