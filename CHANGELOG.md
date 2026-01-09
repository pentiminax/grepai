# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Initial release of grepai
- `grepai init` command for project initialization
- `grepai watch` command for real-time file indexing
- `grepai search` command for semantic code search
- `grepai agent-setup` command for AI agent integration
- Ollama embedding provider (local, privacy-first)
- OpenAI embedding provider
- GOB file storage backend (default)
- PostgreSQL with pgvector storage backend
- Gitignore support
- Binary file detection and exclusion
- Configurable chunk size and overlap
- Debounced file watching
- Cross-platform support (macOS, Linux, Windows)

### Security
- Privacy-first design with local embedding option
- No telemetry or data collection

## [0.1.0] - 2026-01-09

### Added
- Initial public release

[Unreleased]: https://github.com/yoanbernabeu/grepai/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/yoanbernabeu/grepai/releases/tag/v0.1.0
