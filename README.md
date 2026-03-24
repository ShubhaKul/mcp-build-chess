Install this MCP server by adding the following JSON code to your JSON config file

'''json
{
    "mcpchessserver": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/ShubhaKul/mcp-build-chess.git",
        "chess"
      ]
    }
}

'''
