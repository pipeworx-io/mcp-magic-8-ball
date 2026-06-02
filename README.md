# mcp-magic-8-ball

magic-8-ball MCP — wraps StupidAPIs (requires X-API-Key)

Part of [Pipeworx](https://pipeworx.io) — an MCP gateway connecting AI agents to 673+ live data sources.

## Tools

| Tool | Description |
|------|-------------|
| `magic_8_ball_ask` | Ask a yes-or-no question and get a mystical answer. Returns response text. Supports cynical mode for negative-weighted answers or corporate mode for business jargon. Use when you need a random decision, tie-breaker, or humorous perspective. |

## Quick Start

Add to your MCP client (Claude Desktop, Cursor, Windsurf, etc.):

```json
{
  "mcpServers": {
    "magic-8-ball": {
      "url": "https://gateway.pipeworx.io/magic-8-ball/mcp"
    }
  }
}
```

Or connect to the full Pipeworx gateway for access to all 673+ data sources:

```json
{
  "mcpServers": {
    "pipeworx": {
      "url": "https://gateway.pipeworx.io/mcp"
    }
  }
}
```

## Using with ask_pipeworx

Instead of calling tools directly, you can ask questions in plain English:

```
ask_pipeworx({ question: "your question about Magic 8 Ball data" })
```

The gateway picks the right tool and fills the arguments automatically.

## More

- [All tools and guides](https://github.com/pipeworx-io/examples)
- [pipeworx.io](https://pipeworx.io)

## License

MIT
