# Changelog

## [v0.4.0](https://github.com/runapi-ai/midjourney-mcp/releases/tag/v0.4.0) - 2026-09-30

### Changed
- Send tool arguments to the service without local model, enum, range, required-field, or cross-field validation. Tool descriptions still list declared types and known values.
  Migration: Invalid arguments now return the service's error, including its message, instead of a local tool-input rejection.


## [v0.3.1](https://github.com/runapi-ai/midjourney-mcp/releases/tag/v0.3.1) - 2026-07-31

### Changed
- Resolve MCP prices from the RunAPI Price Schedule API instead of embedded package data.


## [v0.3.0](https://github.com/runapi-ai/midjourney-mcp/releases/tag/v0.3.0) - 2026-07-22

### Added
- Add an extend_video tool with contract validation, task polling, and pricing lookup.


## [v0.2.0](https://github.com/runapi-ai/midjourney-mcp/releases/tag/v0.2.0) - 2026-07-20

### Added
- Add the synchronous `shorten_prompt` MCP tool and refresh the Midjourney contract and pricing data slices.


## [v0.1.0](https://github.com/runapi-ai/midjourney-mcp/releases/tag/v0.1.0) - 2026-07-17

### Added
- Add the Midjourney MCP server for image generation, editing, image-to-video, image-to-prompt, and seed lookup workflows.
- Ship refreshed Midjourney pricing data, including seed lookup pricing.
