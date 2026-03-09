# Privacy Policy — RSS Feeds MCP Server

**Last updated:** March 2026

## Overview

The RSS Feeds MCP Server (`rss-feeds-mcp`) is a local MCP server that fetches, filters, and searches RSS feeds. It runs entirely on your machine.

## Data Collection

This MCP server **does not collect, store, or transmit any user data** to third parties. Specifically:

- **No analytics or telemetry** is collected
- **No usage data** is sent to the developer or any third party
- **No personal information** is gathered
- **No API keys or authentication** is required

## Data Processing

- RSS feeds are fetched **directly from your machine** to the feed URLs you configure
- Feed content is parsed locally and returned to your MCP client (e.g., Claude Desktop)
- Feed configuration is stored locally in `feeds.json` in the server directory
- No data is sent to any server operated by the developer

## Third-Party Services

This server communicates only with the **RSS feed URLs you configure** — standard public RSS/Atom endpoints. No other third-party services are contacted.

## Data Retention

- This server does not maintain any database or persistent data storage
- Feed content exists only in memory during your session
- Your feed list is stored locally in `feeds.json` and can be edited or deleted at any time

## Open Source

This server is fully open source under the MIT license. You can audit the complete source code at [github.com/lionkiii/rss-feeds-mcp](https://github.com/lionkiii/rss-feeds-mcp).

## Contact

If you have questions about this privacy policy, please open an issue on the [GitHub repository](https://github.com/lionkiii/rss-feeds-mcp/issues).
