# RelayDesk for Cursor

RelayDesk connects Cursor agents to Windows, macOS, and Linux computers, servers, and VMs that you explicitly pair.

The plugin uses RelayDesk's hosted Streamable HTTP MCP endpoint:

`https://getrelaydesk.space/mcp`

On first connection, RelayDesk uses OAuth in the browser. Once connected, Cursor can use the permitted RelayDesk tools to read files, run commands, inspect logs, troubleshoot systems, and return real machine output through the MCP connection.

## Setup

1. Install the RelayDesk plugin in Cursor.
2. Connect the RelayDesk MCP server when Cursor prompts you.
3. Sign in to RelayDesk and authorize the connection.
4. Pair the computer, server, or VM you want your AI assistant to use.

Learn more: https://getrelaydesk.space/how-it-works

The open-source files in this repository are only the Cursor marketplace integration package. The RelayDesk hosted service and product source are distributed separately.
