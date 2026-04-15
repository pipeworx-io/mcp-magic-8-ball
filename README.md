# mcp-magic-8-ball

magic-8-ball MCP — wraps StupidAPIs (requires X-API-Key)

Part of the [Pipeworx](https://pipeworx.io) open MCP gateway.

## Tools

| Tool | Description |
|------|-------------|
| `magic_8_ball_ask` | Ask the Magic 8-Ball a yes-or-no question. Supports cynical mode (weighted toward negative) and corporate mode (all answers in business speak). |

## Quick Start

Add to your MCP client config:

```json
{
  "mcpServers": {
    "magic-8-ball": {
      "url": "https://gateway.pipeworx.io/magic-8-ball/mcp"
    }
  }
}
```

Or use the CLI:

```bash
npx pipeworx use magic-8-ball
```

## License

MIT
