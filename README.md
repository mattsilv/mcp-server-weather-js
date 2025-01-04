# Simple Weather MCP Server example from Quickstart

Node.js server implementing Model Context Protocol (MCP) for accessing weather information.

This is an example explained in [MCP Quickstart](https://modelcontextprotocol.io/quickstart).

## Original Author and License

This example is based on the code explained in [MCP Quickstart](https://modelcontextprotocol.io/quickstart)
([github](https://github.com/modelcontextprotocol/docs)),
whose license is [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/deed.en).
Since any other license is specified, the same license is applied,
even though it is said not to be suitable for software.

## How to build

```bash
npm install
npm run build
```

## Claude for Desktop configuration

```
# MacOS/Linux
code ~/Library/Application\ Support/Claude/claude_desktop_config.json
# Windows
code $env:AppData\Claude\claude_desktop_config.json
```

```json
{
  "mcpServers": {
    "weather": {
      "command": "node",
      "args": [
        "/ABSOLUTE/PATH/TO/THIS/FOLDER/dist/index.js"
      ]
    }
  }
}
```
