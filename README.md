# ReadShore

Save an article now and find it later in your own words. Connect your ReadShore library to see how many items you have saved, find articles by topic or tag, and open the original source. Ask about a saved passage, its summary or your notes. Create your library on the web or on iPhone.

[Connection guide](https://readshore.app/connect-ai-assistants/?utm_source=claude-marketplace&utm_medium=mcp-package) · [Privacy](https://readshore.app/privacy/) · [Terms](https://readshore.app/terms/) · [Support](https://readshore.app/support/)

## Connect

Claude Code: `/plugin install readshore --marketplace flsteven87/readshore-mcp`.

Kiro: [![Add to Kiro](https://kiro.dev/images/add-to-kiro.svg)](https://kiro.dev/launch/mcp/add?name=readshore&config=%7B%22url%22%3A%22https%3A%2F%2Freadshore.app%2Fmcp%22%2C%22disabled%22%3Afalse%2C%22autoApprove%22%3A%5B%5D%7D)

Gemini CLI: `gemini extensions install https://github.com/flsteven87/readshore-mcp`.

Other MCP clients that support remote servers and OAuth:

```json
{
  "mcpServers": {
    "readshore": {
      "url": "https://readshore.app/mcp"
    }
  }
}
```

Install the plugin, then sign in when your assistant opens readshore.app/connect: use the sign-in method of the Account holding your library (Apple or Google) and choose Allow. Create an Account in the web app at https://readshore.app/app/. The remote endpoint is https://readshore.app/mcp; no API key or local server is needed. Disconnect at https://readshore.app/connect/ or in the app under Settings › Your agents.

Contact: steven@aithentic.tw
