# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in the Vibe Patent plugin or MCP server, please report it privately. **Do not open a public GitHub issue.**

- **Email:** security@vibepatent.ai
- **Subject line:** `[Vibe Patent Security] <short summary>`
- Include: affected component, reproduction steps, impact assessment, and any proof-of-concept.

## Scope

In scope:
- The plugin in this repository (`plugins/vibe-patent-cursor`)
- The hosted Vibe Patent MCP server (`https://api.vibepatent.ai/functions/v1/api-v1-mcp-server`) and its sign-in server (`https://oauth.vibepatent.ai`)

Out of scope:
- Third-party AI providers and clients (for example Anthropic, OpenAI, Cursor). Report those to the respective vendor.
- Issues requiring a compromised user device or a stolen account credential or OAuth token.

## Sensitive Disclosure Content

Technical disclosures are confidential. If a vulnerability could expose disclosure content, account credentials or OAuth tokens, mark the report **CRITICAL** in the subject line.
