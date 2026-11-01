# Gosset MCP

Gosset connects AI assistants to pharmaceutical intelligence across drugs,
clinical trials, results, patents, companies and deals, with links to supporting
sources.

## Connect

Use this hosted MCP endpoint in an MCP client with OAuth support:

```text
https://mcp.gosset.ai/mcp
```

Sign in to your Gosset account when prompted. See the
[official setup guide](https://docs.gosset.ai/guide/claude-connector) for connection
instructions, including the legacy SSE endpoint for older clients.

Gosset is also available through the
[Claude connector directory](https://claude.ai/directory/mcp-gosset-ai) and
[ChatGPT Apps](https://chatgpt.com/plugins/plugin_asdk_app_6ab5a244643481918d26269ab1c2facc).

## Research examples

- Map a target's competitive landscape by asset, company, modality and stage.
- Find clinical trials and their reported results, then follow the supporting sources.
- Explore patent portfolios and pharmaceutical licensing deals.

See [Gosset's product page](https://gosset.ai/mcp-api),
[example research](https://gosset.ai/examples) and
[pricing](https://gosset.ai/pricing).

## Registry metadata

This repository maintains the public connection documentation and `server.json`
listing for the provider-hosted Gosset service. The service implementation is
maintained by Gosset, Inc.

The publishing workflow validates the metadata and publishes
`io.github.gosset-ai/gosset` to the
[official MCP Registry](https://registry.modelcontextprotocol.io/) using GitHub
Actions OIDC. It runs only when manually dispatched, downloads a pinned publisher
release, and verifies the release's Sigstore signature before execution.
