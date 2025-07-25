# mcp-server-client-builder

This repo provides code base and scripts to build and set up an MCP server. The most important part is the trader module.

# changes

With new changes in OpenAI APIs there is no need to build client for MCP server, unless you use resouces api.

# to run trader ui in folder trader_with_mcps

```bash
uv run app.py
```

# to run trader backend in folder trader_with_mcps

```bash
uv run trading_floor.py
```


# environment variables

- OPENAI_API_KEY
