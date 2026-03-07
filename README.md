# CliRelay

AI CLI Proxy - Unified API for Gemini CLI, Claude Code, OpenAI Codex and more.

## Description

CliRelay lets you proxy requests from AI coding tools (Claude Code, Gemini CLI, OpenAI Codex, Amp CLI, etc.) through a single local endpoint. Authenticate once with OAuth, add your API keys — or both — and CliRelay handles the rest.

This is the LazyCat Auto-build version, automatically built from the upstream [kittors/CliRelay](https://github.com/kittors/CliRelay) repository.

## Features

- Advanced API Key Management with CRUD operations
- Precision Tracking with latency tracking
- Multi-Provider Support (OpenAI, Gemini, Claude, Codex, Qwen, iFlow, Vertex)
- Load Balancing & Failover
- Redis Data Persistence
- Management Dashboard

## Usage

After installation, access the service at: `http://clirelay:8317`

### Configuration

Edit the config file at: `/lzcapp/var/data/clirelay/config.yaml`

### Ports

| Port | Description |
|------|-------------|
| 8317 | Main API port |

## License

MIT License - See [LICENSE](LICENSE) for details.
