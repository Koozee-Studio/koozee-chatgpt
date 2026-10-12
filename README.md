# Koozee for ChatGPT

Create fashion workflows on a free canvas. Batch-generate fashion images and videos.

This repository is the [Agent Plugins 1.0](https://agent-plugins.org) package for ChatGPT: `plugin.json`, `mcp.json`, and `skills/` at the repo root.

- Product: [koozee.ai](https://koozee.ai)
- MCP: `https://koozee.ai/business-api/mcp` (`streamable-http`)
- License: MIT

## Install

Clone this repository. The clone root is the plugin root (do not nest it under a `chatgpt/` folder).

OpenAI display metadata lives in `plugin.json` under `extensions.com.openai`. Connect the remote MCP server; the first connection uses OAuth. Calls without login return 401.

Credits match the Koozee canvas. After the canvas changes, open the project URL Koozee returns.

## Support

- Website: https://koozee.ai
- Contact: https://koozee.ai/contact-us
- Privacy: https://koozee.ai/privacy-policy
- Terms: https://koozee.ai/terms-of-service
