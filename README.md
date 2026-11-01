# Vibe Patent

Turn your code into a U.S. provisional patent application, and request review and filing by a registered patent attorney.

[Vibe Patent](https://vibepatent.ai) turns a conversation, technical document, or code repository into a U.S. provisional patent application. It works in the web app, as a connector in Claude, in Cursor and other MCP clients, and through a developer API, all on one account.

This repository holds the Vibe Patent plugin for Cursor.

## Connect

All clients connect to the same MCP server and sign in with a free Vibe Patent account:

```
https://api.vibepatent.ai/functions/v1/api-v1-mcp-server
```

Setup guides for Claude, Cursor and other MCP clients: https://vibepatent.ai/docs

## Cursor plugin

[`plugins/vibe-patent-cursor`](plugins/vibe-patent-cursor) connects Cursor to Vibe Patent and adds a `code-to-patent` skill. Cursor's agent reads your repository on your machine and sends Vibe Patent the assembled software specification text, not the repository.

After installing, open your project and ask the agent, in Agent mode:

> Prepare a patent disclosure from this repo with Vibe Patent.

## Pricing

AI analysis and drafting are free during the pilot program, subject to daily usage limits. Attorney review, filing, and government fees are separate and are shown at checkout on vibepatent.ai.

AI outputs are preliminary drafts for information only and for the purpose of seeking further legal advice from a registered patent practitioner. Use of Vibe Patent alone does not create an attorney-client relationship.

## About

Vibe Patent is a service of Patrick IP Law, 134 N 4th St, Brooklyn, NY 11249. Responsible attorney: Christopher R. Patrick, Esq.

Support: support@vibepatent.ai

## License

You may install and use this plugin to access the Vibe Patent service. All other rights reserved. See [LICENSE](LICENSE).
