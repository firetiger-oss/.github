# Firetiger OSS

Open source projects from [Firetiger](https://firetiger.com).

## Projects

### Libraries

- **[tigerblock](https://github.com/firetiger-oss/tigerblock)** - Go package to interact with cloud object storage providers.
- **[go-duckfs](https://github.com/firetiger-oss/go-duckfs)** - DuckDB virtual file system based on `io/fs`. Mount any Go filesystem (cloud storage, HTTP, etc.) as a DuckDB backend.
- **[concurrent](https://github.com/firetiger-oss/concurrent)** - Structured concurrency for Go. Composable pipelines, worker pools, and ordered result collection built on `iter.Seq`.
- **[otelnet](https://github.com/firetiger-oss/otelnet)** - OpenTelemetry instrumentation for Go's `net` package.

### RPC

- **[aip](https://github.com/firetiger-oss/aip)** - Go utilities for Google AIP-compliant services: AIP-160 filters → parameterized SQL, AIP-132 ordering.
- **[connect-aip](https://github.com/firetiger-oss/connect-aip)** - Connect RPC → Google AIP REST codegen (Go/TS/Python plugins).
- **[connect-sse](https://github.com/firetiger-oss/connect-sse)** - SSE transport for connect-go.

### CLI

- **[stripes](https://github.com/firetiger-oss/stripes)** - Streaming pretty-printer for JSON, YAML, XML, HTML, CSV, protobuf, and text — Go library and CLI.
- **[lambdahttp-go](https://github.com/firetiger-oss/lambdahttp-go)** - Bridge AWS Lambda and Go's `net/http`: serve Lambda events (ALB, API Gateway, Function URLs) with any `http.Handler`, or invoke Lambda as an `http.RoundTripper`.

### Plugins

- **[claude-plugin](https://github.com/firetiger-oss/claude-plugin)** - Claude Code plugin for Firetiger.
- **[cursor-plugin](https://github.com/firetiger-oss/cursor-plugin)** - Firetiger plugin for Cursor.
