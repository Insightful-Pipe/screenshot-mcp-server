# Screenshot MCP Server by Insightful Pipe

[![MCP Compatible](https://img.shields.io/badge/MCP-Compatible-blue)](https://insightfulpipe.com/mcp-servers/screenshot)
[![Insightful Pipe](https://img.shields.io/badge/Insightful_Pipe-MCP_Servers-purple)](https://insightfulpipe.com/mcp-servers)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> **Capture high-quality website screenshots with AI through MCP.**

Part of the [Insightful Pipe MCP Server Collection](https://insightfulpipe.com/mcp-servers) — The Screenshot MCP server enables Claude, ChatGPT, Cursor, and other AI assistants to capture screenshots of web pages. Generate visual documentation, compare designs, and analyze page layouts.

[![Explore All MCP Servers](https://img.shields.io/badge/Explore_All-MCP_Servers-blue?style=for-the-badge)](https://insightfulpipe.com/mcp-servers)

![Screenshot MCP Server](https://insightfulpipe.com/images/ip-logo.png)

## MCP Server URL

```
https://screenshots.insightfulmcp.com/
```

## What is Screenshot MCP?

Screenshot MCP is a **remote Model Context Protocol server** that provides AI assistants with web page screenshot capabilities. This visual capture integration allows you to:

- Capture full-page and viewport screenshots
- Generate screenshots at various resolutions
- Capture mobile and desktop views
- Create visual documentation

## Installation

### Claude

1. Copy the MCP Server URL: `https://screenshots.insightfulmcp.com/`
2. Open [Claude Connectors Settings](https://claude.ai/settings/connectors)
3. Scroll to the bottom and click **Add custom connector**
4. Paste the URL and click **Add**
5. Click **Connect** on the connector to start authorization
6. Click **Authorize access** in the browser to complete the connection

### ChatGPT

Custom MCP servers are added through ChatGPT's **Developer mode**. Availability depends on your ChatGPT plan, and workspace admins may need to allow it.

1. Turn on **Developer mode** in ChatGPT settings
2. Create a new app for a remote MCP server and paste the URL: `https://screenshots.insightfulmcp.com/`
3. Authorize with your InsightfulPipe account

See OpenAI's guide: [Developer mode and MCP apps in ChatGPT](https://help.openai.com/en/articles/12584461-developer-mode-and-mcp-apps-in-chatgpt)

### Claude Code

```bash
claude mcp add --transport http screenshot https://screenshots.insightfulmcp.com/
```

### Cursor

Add the server to `~/.cursor/mcp.json` (all projects) or `.cursor/mcp.json` (one project):

```json
{
  "mcpServers": {
    "screenshot": {
      "url": "https://screenshots.insightfulmcp.com/"
    }
  }
}
```

Then authorize the connection when Cursor prompts you.

## Available Actions

1 actions: 1 read, 0 write.

### Read Actions (1)

| Action | Description |
|--------|-------------|
| `capture` | Capture website screenshots and receive signed public URLs |

## Usage Examples

### Basic Screenshot

```
"Take a screenshot of https://example.com"
```

### Full Page Capture

```
"Capture a full-page screenshot of this landing page"
```

### Mobile Screenshot

```
"Take a mobile screenshot of this website"
```

### Documentation

```
"Screenshot this page for our documentation"
```

### Competitive Analysis

```
"Capture screenshots of these competitor websites"
```

## Features

- **Full page scrolling** - Capture long pages
- **JavaScript rendering** - Handle dynamic content
- **Custom viewports** - Any screen size
- **Device emulation** - Mobile/tablet simulation

## Why Screenshot MCP?

### For Designers
- **Design review** - Capture design implementations
- **Comparison** - Before/after screenshots
- **Documentation** - Visual design archives

### For QA Teams
- **Visual testing** - Capture for comparison
- **Bug documentation** - Screenshot issues
- **Cross-browser testing** - Different viewports

### For Marketers
- **Competitor monitoring** - Screenshot competitor sites
- **Campaign documentation** - Capture landing pages
- **Social proof** - Website screenshots for content

## Security & Privacy

- **Public URLs only** - By default
- **Data encryption** - Secure transmission

## Explore More MCP Servers by Insightful Pipe

Visit **[insightfulpipe.com/mcp-servers](https://insightfulpipe.com/mcp-servers)** to discover our full collection of MCP servers for marketing and analytics.

### Web Tools MCP Servers
- [Web Crawler MCP](https://insightfulpipe.com/mcp-servers/crawler) - Web crawling
- [PageSpeed MCP](https://insightfulpipe.com/mcp-servers/pagespeed) - Performance

### SEO MCP Servers
- [Google Search Console MCP](https://insightfulpipe.com/mcp-servers/google-search-console) - SEO
- [Google My Business MCP](https://insightfulpipe.com/mcp-servers/google-my-business) - Local SEO

**[View All MCP Servers →](https://insightfulpipe.com/mcp-servers)**

## Resources

- [Documentation](https://insightfulpipe.com/docs/connectors-screenshots)
- [Video Tutorial](https://www.youtube.com/playlist?list=PLJNzvjxzI5Xwe__BJJLAelSF0ewO3mEFk)
- [InsightfulPipe Blog](https://insightfulpipe.com/blog)

## Support

- **Documentation**: [insightfulpipe.com/docs](https://insightfulpipe.com/docs)
- **All MCP Servers**: [insightfulpipe.com/mcp-servers](https://insightfulpipe.com/mcp-servers)
- **Email**: support@insightfulpipe.com

---

**[Insightful Pipe](https://insightfulpipe.com)** — AI-powered marketing analytics through MCP servers. [Explore all integrations →](https://insightfulpipe.com/mcp-servers)

## License

MIT License - see [LICENSE](LICENSE) for details.
