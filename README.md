# MCP Server Deployment

To install the `add_tool` MCP server, add the following configuration to your MCP server config:

```json
{
  "mcpServers": {
    "add_tool": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/amsidhu/mcpserevertest.git",
        "mcp-server"
      ]
    }
  }
}
```

This package exposes the `mcp-server` entrypoint defined in the project configuration.