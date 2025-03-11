# BrowserTools Chrome Extension

This is the Chrome extension component of BrowserTools. It captures browser data and sends it to the BrowserTools server.

## Installation

1. Download the latest version of the extension:
   [v1.2.0 BrowserToolsMCP Chrome Extension](https://github.com/AgentDeskAI/browser-tools-mcp/releases/download/v1.2.0/BrowserTools-1.2.0-extension.zip)

2. Unzip the downloaded file

3. Open Chrome and navigate to `chrome://extensions/`

4. Enable "Developer mode" in the top-right corner

5. Click "Load unpacked" and select the unzipped extension folder

## Features

- Monitors XHR requests/responses and console logs
- Tracks selected DOM elements
- Sends all logs and current element to the BrowserTools Connector
- Connects to Websocket server to capture/send screenshots
- Allows user to configure token/truncation limits + screenshot folder path

## Usage

1. Open Chrome DevTools
2. Navigate to the "BrowserTools" panel
3. Configure settings as needed
4. Logs will automatically be sent to the BrowserTools server