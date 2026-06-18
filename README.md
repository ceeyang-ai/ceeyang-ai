# 👋 Welcome to ceeyang-ai

> **MCP Server Suite** — Building production-grade Model Context Protocol servers for AI agents.

---

## 📦 Our Products

A curated suite of **MCP servers** — install, configure, and give your AI agent superpowers.

| Server | Tools | Category | Install |
|--------|:-----:|:--------:|:--------|
| **[freqtrade-mcp-server](https://github.com/ceeyang-ai/freqtrade-mcp-server)** ⭐ | 15 | Crypto Trading | `pip install freqtrade-mcp-server` |
| **[doc-mcp-server](https://github.com/ceeyang-ai/doc-mcp-server)** | 8 | Document Processing | `pip install doc-mcp-server` |
| **[viz-mcp-server](https://github.com/ceeyang-ai/viz-mcp-server)** | 5 | Data Visualization | `pip install viz-mcp-server` |
| **[webx-mcp-server](https://github.com/ceeyang-ai/webx-mcp-server)** | 4 | Web Extraction | `pip install webx-mcp-server` |

### 🌟 Freqtrade MCP — Our Flagship
**[15 tools](https://github.com/ceeyang-ai/freqtrade-mcp-server)** for cryptocurrency trading via the Freqtrade bot:

- 💰 Account balance & profit tracking
- 📊 Open trades, trade history, per-pair performance
- 🎮 Force enter/exit, start/stop bot, reload config
- 📈 Backtesting & strategy management
- 🔧 Whitelist/blacklist, pair management

Requires a running [Freqtrade](https://github.com/freqtrade/freqtrade) instance with API server enabled.

---

## 🚀 Quick Start

### All-in-one MCP Config

```yaml
mcp_servers:
  trade:
    command: "freqtrade-mcp-server"
  doc:
    command: "doc-mcp-server"
  viz:
    command: "viz-mcp-server"
  webx:
    command: "webx-mcp-server"
```

### Install from GitHub

```bash
pip install git+https://github.com/ceeyang-ai/freqtrade-mcp-server.git
pip install git+https://github.com/ceeyang-ai/doc-mcp-server.git
pip install git+https://github.com/ceeyang-ai/viz-mcp-server.git
pip install git+https://github.com/ceeyang-ai/webx-mcp-server.git
```

## 📄 License

All projects are MIT licensed — free for personal and commercial use.

---

*Built with Python + FastMCP*
