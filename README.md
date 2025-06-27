# Installation Steps

To install the `add_tool` MCP server, run the following command:

```json
{
  "mcpServers": {
    "add_tool": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/goutham-nivass/MCP_Server_Example.git",
        "mcp-server"
      ]
    }
  }
}
```

This will fetch and set up the `mcp-server` from the specified GitHub repository.
