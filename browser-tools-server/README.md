# BrowserTools Server

This is the server component of BrowserTools. It acts as middleware between the Chrome extension and MCP server.

## Installation

```bash
npm install @agentdeskai/browser-tools-server
```

Or run directly with npx:

```bash
npx @agentdeskai/browser-tools-server@1.2.0
```

## Features

- Receives logs and currently selected element from Chrome extension
- Processes requests from MCP server to capture logs, screenshot or current element
- Sends Websocket command to the Chrome extension for capturing a screenshot
- Intelligently truncates strings and # of duplicate objects in logs to avoid token limits
- Removes cookies and sensitive headers to avoid sending to LLMs in MCP clients

## Usage

Make sure you have the Chrome extension installed and enabled in your browser before running this server.