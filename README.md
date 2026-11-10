# VaultCord for Claude

VaultCord connects your AI assistant to your [VaultCord](https://vaultcord.com) account so it can
manage your protected Discord servers: servers and settings, verification, members,
allow/block lists, backups and restores, custom bots, and orders.

- **Server:** `https://ai.vaultcord.com/mcp` (Streamable HTTP)
- **Auth:** OAuth 2.0 with dynamic client registration. No API key or client ID needed. You sign
  in to VaultCord the first time a tool is used.
- **Permissions:** every call runs with your own VaultCord permissions.
- **Docs:** https://docs.vaultcord.com · **Privacy:** https://vaultcord.com/privacy-policy · **Terms:** https://vaultcord.com/terms-of-service · **Support:** abuse@vaultcord.com

## Install

**Claude.ai / Desktop / Cowork:** find **VaultCord** in the Directory (Customize → Connectors / Plugins), click **Add**, then **Connect** and sign in.

**Claude Code:**
```bash
claude plugin marketplace add VaultCord/vaultcord-claude-plugin
claude plugin install vaultcord@vaultcord
```
Then run `/mcp`, select `vaultcord` and sign in.

## What's inside
- `.mcp.json` — points Claude at the VaultCord MCP server
- `skills/vaultcord/SKILL.md` — teaches Claude how to use the tools safely (confirmations before destructive actions)
