Steps taken:
1. Ran ```meteor create myBrokenMCP```
2. Ran ```meteor npm install --save @modelcontextprotocol/sdk``` in the myBrokenMCP folder
3. Added the line ```import { StreamableHTTPClientTransport } from '@modelcontextprotocol/sdk/client/streamableHttp.js';``` to the top of the myBrokenMCP/server/main.js file
4. Reproduce the issue by running ```meteor``` in the myBrokenMCP folder
probe marker for MCP write testing
