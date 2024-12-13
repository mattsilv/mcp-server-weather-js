# Simple Weather MCP Server example from Quickstart

An example explained MCP Quickstart: https://modelcontextprotocol.io/quickstart

## How to build

```bash
npm install
npm run build
```

## Claude for Desktop configuration

```bash
cursor ~/Library/Application\ Support/Claude/claude_desktop_config.json
```

```json
{
    "mcpServers": {
        "weather": {
            "command": "node",
            "args": [
                "/ABSOLUTE/PATH/TO/PARENT/FOLDER/weather/build/index.js"
            ]
        }
    }
}
```
