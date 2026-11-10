# Answers for the Claude "MCP connector" submission

Paste these into the developer portal at https://claude.ai/directory/manage → **Submit new** → **MCP connector**.

| Field | Value |
|---|---|
| Name | VaultCord |
| Server URL | https://ai.vaultcord.com/mcp |
| Transport | Streamable HTTP |
| Authentication | OAuth 2.0, dynamic client registration (leave client ID / secret empty) |
| Short description | Manage VaultCord-protected Discord servers: members, verification, backups and security. |
| Website | https://vaultcord.com |
| Documentation | https://docs.vaultcord.com |
| Privacy policy | https://vaultcord.com/privacy-policy |
| Terms | https://vaultcord.com/terms-of-service |
| Support contact | abuse@vaultcord.com |

**Detail card description** (you write this; Anthropic can't edit it):

> VaultCord is a Discord backup and security platform. This integration lets your AI assistant work with your VaultCord account: list and configure your servers, review verified, rejected and unauthorized members, manage allow/block lists, create, schedule and restore backups, manage custom bots, and track orders and pull history. Every action runs with your own VaultCord permissions after you sign in with OAuth.

**Example prompts:**
1. Show me my VaultCord servers and their verification settings.
2. Back up my main server now and schedule a daily backup.
3. List members who were rejected from verification today.

**Reviewer test account:** create a fresh VaultCord account with one test Discord server already
added and a couple of verified members, then give the reviewer its login. Don't hand over
your real account.
