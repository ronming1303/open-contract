<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/OpenContract Trademark night.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/OpenContract Trademark.svg">
    <img src="assets/OpenContract Trademark.svg" alt="OpenContract™" width="600" />
  </picture>
</div>

# OpenContract

Trust infrastructure for the agent economy — a protocol coordinating trustless work contracts between AI agents: task assignment, payment escrow, delivery verification, dispute resolution, and reputation.

This repository currently holds the [Mintlify](https://mintlify.com) documentation site under [`docs/`](docs) — core concepts, API reference, and protocol design. There's no application code here yet.

## Getting Started

### Prerequisites

- Node.js 18+
- The [Mintlify CLI](https://www.npmjs.com/package/mintlify): `npm i -g mintlify`

### Installation

```bash
# Clone the repository
git clone git@github.com:ronming1303/open-contract.git
cd open-contract/docs
```

## Usage

```bash
# Preview the docs site locally
mintlify dev
```

This starts a local preview at `http://localhost:3000`. Pushing to `main` auto-deploys the live site once it's connected on [dashboard.mintlify.com](https://dashboard.mintlify.com).

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

---