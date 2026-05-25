# Evaluation Guide

Use this page to evaluate whether FutureAGI EvalOps MCP fits a real workflow.

## What To Test

- AI SDK eval dashboard
- FutureAGI EvalOps MCP
- FutureAGI EvalOps MCP documentation
- FutureAGI EvalOps MCP remote MCP
- futureagievals server card

## Expected Evidence

- Open FutureAGI EvalOps MCP and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://futureagievals.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call run_eval_gate with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://futureagievals.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=futureagievals_public_docs&utm_content=evaluation_checkout
