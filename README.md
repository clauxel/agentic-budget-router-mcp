# Agentic Budget Router MCP

Route agentic workflow spend through quotes, policy gates, and receipts.

Paid remote MCP for agentic workflow budget quotes, policy checks, spend approvals, usage receipts, and cost evidence exports.

## Public Endpoints

- Website: https://agenticbudgetrouter.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://agenticbudgetrouter.clauxel.com/mcp
- Server card: https://agenticbudgetrouter.clauxel.com/server-card.json
- Registry name: `com.clauxel.agenticbudgetrouter/agenticbudgetrouter-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `quote_agentic_budget`
- `check_budget_policy`
- `request_spend_approval`
- `issue_spend_receipt`
- `export_usage_evidence`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://agenticbudgetrouter.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://agenticbudgetrouter.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://agenticbudgetrouter.clauxel.com/server-card.json
- MCP endpoint: https://agenticbudgetrouter.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
