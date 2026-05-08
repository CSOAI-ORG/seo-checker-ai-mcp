<div align="center">

# Seo Checker Ai MCP

**SEO Checker AI MCP Server**

[![PyPI](https://img.shields.io/pypi/v/meok-seo-checker-ai-mcp)](https://pypi.org/project/meok-seo-checker-ai-mcp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![MEOK AI Labs](https://img.shields.io/badge/MEOK_AI_Labs-MCP_Server-purple)](https://meok.ai)

</div>

## Overview

SEO Checker AI MCP Server
SEO analysis and optimization tools powered by MEOK AI Labs.

## Tools

| Tool | Description |
|------|-------------|
| `analyze_title` | Analyze a page title for SEO best practices. |
| `check_meta_description` | Check a meta description for SEO best practices. |
| `validate_schema_markup` | Validate JSON-LD structured data/schema markup. |
| `heading_analysis` | Analyze heading structure for SEO optimization. |

## Installation

```bash
pip install meok-seo-checker-ai-mcp
```

## Usage with Claude Desktop

Add to your Claude Desktop MCP config (`claude_desktop_config.json`):

```json
{
  "mcpServers": {
    "seo-checker-ai": {
      "command": "python",
      "args": ["-m", "meok_seo_checker_ai_mcp.server"]
    }
  }
}
```

## Usage with FastMCP

```python
from mcp.server.fastmcp import FastMCP

# This server exposes 4 tool(s) via MCP
# See server.py for full implementation
```

## License

MIT © [MEOK AI Labs](https://meok.ai)
