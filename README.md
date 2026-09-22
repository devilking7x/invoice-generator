# Invoice Generator

[![Live demo](https://devilking7x.github.io/invoice-generator/badge.svg)](https://devilking7x.github.io/invoice-generator/) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> Create a clean invoice without a subscription.

Invoice Generator is a client-side utility for independent workers and small teams. Add a client, line items, tax, and discount, then print or save a clean invoice as PDF from the browser.

## Features

- Editable sender and client fields.
- Add or remove line items.
- Quantity and price calculations.
- Tax and discount controls.
- Live preview with total due.
- Print and browser PDF export.
- No account, backend, or payment integration.

## Getting started

```bash
git clone https://github.com/devilking7x/invoice-generator.git
cd invoice-generator
pnpm install
pnpm dev
```

```bash
pnpm check
pnpm build
```

## Privacy

Invoice values are kept in browser memory and are not intentionally uploaded. Use your browser's print dialog to save a PDF locally.

## License

MIT — see [LICENSE](LICENSE).

## Demo

Try the live app: https://devilking7x.github.io/invoice-generator/

## Who it is for

This project is designed for **freelancers and small businesses**. Its narrow first release focuses on helping them create a printable invoice without a billing backend. The interface uses realistic synthetic fixtures so the value is understandable without connecting a production account.

## Privacy and safety

The default experience is local-first: inputs are processed in the browser or in the user's own development environment, with no required account, API key, payment flow, or remote storage. Fixtures contain synthetic data only. Review a fork's hosting and analytics configuration before using it with sensitive information.

## Validation

The release workflow is intentionally reproducible. Run `pnpm install --frozen-lockfile`, `pnpm check`, and `pnpm build` before submitting a change. Manual review should cover keyboard operation, visible focus, mobile layout, empty states, and both successful and error paths.

## Limitations

This is a focused open-source MVP rather than a hosted replacement for a production system. It does not guarantee business, legal, financial, medical, accessibility, or security compliance by itself. Validate outputs against the context in which you plan to use them.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for setup, code style, privacy expectations, and pull-request guidance.

## License

Released under the [MIT License](LICENSE).
