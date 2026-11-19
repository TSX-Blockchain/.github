# Contributing to TSX

Thank you for your interest in TSX. These guidelines apply across the [TSX-Blockchain](https://github.com/TSX-Blockchain) organization unless a repository says otherwise.

## Code of conduct

Please read and follow the [Code of Conduct](./CODE_OF_CONDUCT.md). Reports of unacceptable behavior can be sent to hello@tsx.network.

## Security issues

Do not file a public issue for a vulnerability.

If you find a flaw in a TSX chain, the sale or bridge contracts, the explorer, the website, or any repository in this organization, write to **security@tsx.network**, in English or Polish, before you tell anyone else. See [SECURITY.md](./SECURITY.md) for what to include.

- Say what is affected: the chain, the contract address, the repository, or the page, and the steps that show the problem.
- Try things on TSX Testnet, where coins have no value. Do not move or hold anyone else's coins to prove a point.
- Give the TSX team time to fix it before you publish the details.

The sale and bridge contracts have not been audited.

## Questions, builders, and Bastion access

- **builders@tsx.network** — building on Horizon or Bastion, deploy access on Bastion, coins for a launch, or a technical question
- **hello@tsx.network** — general enquiries
- **Website:** [tsx.network](https://tsx.network)
- **Discord:** [discord.gg/sKusT7FA3](https://discord.gg/sKusT7FA3)

## Reporting bugs and requesting features

Use the issue templates in the relevant repository:

- A bug in a published RPC, explorer listing, or contract address belongs in [TSX-Blockchain/networks](https://github.com/TSX-Blockchain/networks), or on the product that is actually wrong.
- Please include the network (Horizon 455, Bastion 454, or Testnet 445), the contract address or RPC URL, and a transaction hash when you have one.
- Do not include private keys, seed phrases, or passwords.

## Pull requests

1. Open an issue first if the change is substantial, so the TSX team can discuss the approach.
2. Keep the pull request focused on one change.
3. Describe what changed and why. Link the issue if there is one.
4. Do not invent or hard-code unpublished contract addresses, RPC URLs, or chain parameters. Use the official values in [TSX-Blockchain/networks](https://github.com/TSX-Blockchain/networks) and the live list at [tsx.network/networks.json](https://tsx.network/networks.json).
5. Public copy in this organization is signed by the TSX team.

The TSX team will review pull requests as time allows.

## Network and contract data

[TSX-Blockchain/networks](https://github.com/TSX-Blockchain/networks) holds official chain configurations and verified contract addresses. "Verified" means the chain's explorer has matched the published source code to the bytecode at that address. It is not a security review. Until an explorer confirms a contract, it is not listed there.

---

By the TSX team.
