[![GitHub license](https://img.shields.io/github/license/amitkumar-ak/sitecore-marketer-mcp-prompts.svg?style=for-the-badge)](https://github.com/amitkumar-ak/sitecore-marketer-mcp-prompts/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/amitkumar-ak/sitecore-marketer-mcp-prompts.svg?style=for-the-badge)](https://GitHub.com/amitkumar-ak/sitecore-marketer-mcp-prompts/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/amitkumar-ak/sitecore-marketer-mcp-prompts.svg?style=for-the-badge)](https://GitHub.com/amitkumar-ak/sitecore-marketer-mcp-prompts/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/amitkumar-ak/sitecore-marketer-mcp-prompts.svg?style=for-the-badge)](https://GitHub.com/amitkumar-ak/sitecore-marketer-mcp-prompts/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](http://makeapullrequest.com)
[![GitHub Stars](https://img.shields.io/github/stars/amitkumar-ak/sitecore-marketer-mcp-prompts?label=GitHub%20Stars&style=for-the-badge)](https://github.com/amitkumar-ak/sitecore-marketer-mcp-prompts/stargazers)
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2FAmitKumar-AK%2Fsitecore-marketer-mcp-prompts&label=Visitors&countColor=%23263759&style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/amitkumar-ak/sitecore-marketer-mcp-prompts.svg?style=for-the-badge)
![GitHub repo size](https://img.shields.io/github/repo-size/amitkumar-ak/sitecore-marketer-mcp-prompts.svg?style=for-the-badge)
![GitHub commit activity](https://img.shields.io/github/commit-activity/y/amitkumar-ak/sitecore-marketer-mcp-prompts?style=for-the-badge)

[![GitHub watchers](https://img.shields.io/github/watchers/amitkumar-ak/sitecore-marketer-mcp-prompts.svg?style=social&label=Watch&maxAge=2592000)](https://GitHub.com/amitkumar-ak/sitecore-marketer-mcp-prompts/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/amitkumar-ak/sitecore-marketer-mcp-prompts.svg?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/amitkumar-ak/sitecore-marketer-mcp-prompts/network/)
[![GitHub stars](https://img.shields.io/github/stars/amitkumar-ak/sitecore-marketer-mcp-prompts.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/amitkumar-ak/sitecore-marketer-mcp-prompts/stargazers/)


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
