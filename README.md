# Codex SDK for Go

Go client library for the [Codex CLI](https://github.com/openai/codex) `app-server` JSON-RPC v2 protocol. Spawns `codex app-server` as a subprocess and provides a typed Go API for sending requests and receiving notifications.

Architecture: [agynd-cli — Agent Communication Protocol](https://github.com/agynio/architecture/blob/main/architecture/agynd-cli.md#agent-communication-protocol)

## Installation

    go get github.com/agynio/codex-sdk-go@latest

## Protocol

This SDK implements the Codex `app-server` JSON-RPC v2 protocol over JSONL stdio. Types are derived from the [machine-readable JSON Schema](https://github.com/openai/codex/blob/main/codex-rs/app-server-protocol/schema/json/codex_app_server_protocol.v2.schemas.json).
