# Noema · AKO Node

Self-hostable binary for the [AKO](https://noema-agi.com) epistemic knowledge graph.

## Download

Grab the latest binary for your platform from [Releases](../../releases).

| Platform | Binary |
|----------|--------|
| Linux (x86-64) | `ako-node-linux-amd64` |
| macOS (Intel) | `ako-node-mac-amd64` |
| macOS (Apple Silicon) | `ako-node-mac-arm64` |
| Windows (x86-64) | `ako-node-windows-amd64.exe` |

## Requirements

- PostgreSQL 16

## Quickstart

```sh
# Set environment variables
export AKO_POSTGRES_URL="postgres://user:pass@localhost:5432/akodb"
export CLAUDE_API_KEY="sk-ant-..."        # optional: extraction pipeline
export UNPAYWALL_EMAIL="you@example.com"  # optional: extraction pipeline

# Run
./ako-node-linux-amd64
# Listening on :8080
```

Full environment reference and self-hosting guide: [noema-agi.com](https://noema-agi.com)

## What is AKO?

AKO (Atomic Knowledge Object) is a Bitcoin-native attribution protocol for preserving credit for human insight under LLM reuse. Published claims are bonded with BTC, arranged in a typed connector DAG, and attributed dynamically via fixed-point activation propagation.
