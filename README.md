# mcp-could-have-been-email

could-have-been-email MCP — wraps StupidAPIs (requires X-API-Key)

Part of the [Pipeworx](https://pipeworx.io) open MCP gateway.

## Tools

| Tool | Description |
|------|-------------|
| `could_have_been_email_analyze` | Analyze a meeting transcript to determine if it could have been an email. Counts filler, decisions, action items, and generates the email that should have been sent instead. |

## Quick Start

Add to your MCP client config:

```json
{
  "mcpServers": {
    "could-have-been-email": {
      "url": "https://gateway.pipeworx.io/could-have-been-email/mcp"
    }
  }
}
```

Or use the CLI:

```bash
npx pipeworx use could-have-been-email
```

## License

MIT
