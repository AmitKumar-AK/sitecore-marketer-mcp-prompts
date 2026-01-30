# Sitecore Marketer MCP Prompts & VS Code Integration

This repository provides ready-to-use `mcp.json` configuration and a collection of practical prompts for integrating Sitecore Marketer MCP with Visual Studio Code and GitHub Copilot. Use these resources to automate content management, marketing workflows, and personalization in Sitecore Headless, SitecoreAI, and JSS environments.

## Features

- Example `mcp.json` for quick VS Code setup
- Curated prompt library for common Sitecore Marketer MCP use cases
- AI-driven content creation, updates, and personalization
- Works with SitecoreAI, Copilot, and Experience Edge

## Getting Started

1. Copy the provided `mcp.json` to your project’s `.vscode` folder.
2. Use the sample prompts in Copilot Chat or your preferred AI tool.
3. Customize prompts for your Sitecore environment and business needs.

## Example `mcp.json`

```json
{
  "servers": {
    "sitecore-marketer-mcp": {
      "url": "https://edge-platform.sitecorecloud.io/mcp/marketer-mcp-prod",
      "auth": {
        "type": "external"
      },
      "type": "http"
    }
  }
}
```

## Prompts Folder Reference

All prompt files are located in the [docs/prompts](docs/prompts/README.md) folder. Browse this directory for ready-to-use examples and guides for Sitecore Marketer MCP operations.
