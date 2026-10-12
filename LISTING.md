# Directory listing text (Smithery, Glama, mcp.so, PulseMCP)

Name: Afriref — cited government reference data (7 regions)
Short (≤100 chars): Official tax, VAT, CPI, policy rates, wages, holidays & FX for 128 countries plus the EU, cited to source.
Category: Finance / Data / Compliance
Tags: tax, vat, gst, inflation, cpi, central-bank, policy-rate, minimum-wage, public-holidays, business-days, exchange-rates, payroll, compliance, x402
Transport: Streamable HTTP (remote). Auth: none required; optional api_key.
Endpoints: https://afriref.dev/mcp (also euroref.dev, asiaref.dev, latamref.dev, usaref.dev, mearef.dev, ausref.dev)

Long description:
Afriref serves official government reference data as clean JSON, with every value cited to the gazette, revenue notice or central-bank instrument it came from, plus effective date, last-confirmed date and a stale flag. It covers 128 countries plus the EU across seven regional servers: income and corporate tax, VAT/GST bands, CPI inflation, policy rates, minimum wages, public holidays, business days, official exchange rates, statutory interest and social contributions, plus computed answers such as VAT breakdowns, minimum-wage checks, working days, income tax and payroll. Out-of-scope questions are refused free rather than guessed. Try it free on each region's evaluation country and with 3 free computed answers a day; then pay per call over x402 (USDC on Base) or with prepaid card credit at the same price.

Submission notes:
- Smithery: needs a public GitHub repo containing README.md + smithery.yaml; choose remote/URL deployment pointing at https://afriref.dev/mcp.
- Glama: indexes public GitHub MCP repos automatically; add README + LICENSE, then claim the server.
- mcp.so: submit form with GitHub URL and endpoint.
- PulseMCP: submit form; it also ingests the official MCP registry (dev.afriref/reference-data already published).
- Logo: a 512x512 square PNG is still needed.
