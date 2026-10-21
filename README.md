# sec-ai skill (`@lkcair/sec`)

**Thousands of downloads on ClawHub.** The OpenClaw skill for [sec-finance-ai](https://github.com/lkcair/sec-finance-ai): 23 SEC EDGAR functions straight on the official sec.gov APIs, for 10-K, 10-Q, 8-K, proxies and IPOs, 13D/13G, Form 4 insiders, 13F holdings, XBRL financials, full-text search and reading or searching inside any filing.

## Install

```bash
openclaw skills install @lkcair/sec
```

Skill page: [clawhub.ai/lkcair/sec](https://clawhub.ai/lkcair/sec). The agent follows [SKILL.md](SKILL.md): a one-time setup in its own virtual environment (hash-pinned `requirements.txt`), then every function runs with one command through `scripts/cli.py`. Set `SEC_USER_AGENT="Your Name you@example.com"` to identify yourself to the SEC; a default is sent otherwise.

## Also available

- **MCP server** (Claude, Cursor, VS Code, any MCP client): `uvx sec-finance-ai@latest`, see [sec-ai-mcp](https://github.com/lkcair/sec-ai-mcp)
- **OpenWebUI tool**, thousands of downloads: see [sec-finance-ai](https://github.com/lkcair/sec-finance-ai)
- **Stocks and crypto skill**: `openclaw skills install @lkcair/stocks`

Powered by [sec-finance-ai](https://github.com/lkcair/sec-finance-ai). MIT-0. Not affiliated with the U.S. Securities and Exchange Commission.
