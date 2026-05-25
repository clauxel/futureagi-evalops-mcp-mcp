# FutureAGI EvalOps MCP

FutureAGI EvalOps MCP is a hosted remote MCP for AI SDK eval dashboard.

This repository is a public documentation project for FutureAGI EvalOps MCP. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://futureagievals.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=futureagievals_public_docs&utm_content=readme_home
- Pricing: https://futureagievals.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=futureagievals_public_docs&utm_content=readme_pricing
- Checkout: https://futureagievals.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=futureagievals_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://futureagievals.clauxel.com/mcp
- Server card: https://futureagievals.clauxel.com/server-card.json
- Registry name: `com.clauxel.futureagievals/futureagievals-mcp`
- Tools: `run_eval_gate`, `summarize_trace_failures`, `compare_eval_versions`, `issue_eval_receipt`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: run_eval_gate
- MCP tool: summarize_trace_failures
- MCP tool: compare_eval_versions
- MCP tool: issue_eval_receipt

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
