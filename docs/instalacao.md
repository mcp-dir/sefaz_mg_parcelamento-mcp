# Instalação detalhada

SEFAZ MG: Consulta Parcelamento é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_sefaz_mg_parcelamento`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_sefaz_mg_parcelamento` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_sefaz_mg_parcelamento` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_sefaz_mg_parcelamento` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.sefaz_mg_parcelamento` (ou `servers.sefaz_mg_parcelamento` no VS Code) do config do cliente e reinicie.
