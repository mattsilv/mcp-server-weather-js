# Simple Weather MCP Server Example

Ref: https://modelcontextprotocol.io/quickstart

## How to build

```bash
npm install
npm run build
```

## Claude for Desktop configuration

```bash
yourEditor ~/Library/Application\ Support/Claude/claude_desktop_config.json
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
