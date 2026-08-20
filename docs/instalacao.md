# Instalação detalhada

Controladoria-Geral da União: Certidão Negativa Correcional - Agentes Públicos (ePAD, CGU-PAD e Banco de Sanções) é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_cgu_cnc_tipo2`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_cgu_cnc_tipo2` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_cgu_cnc_tipo2` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_cgu_cnc_tipo2` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.cgu_cnc_tipo2` (ou `servers.cgu_cnc_tipo2` no VS Code) do config do cliente e reinicie.
