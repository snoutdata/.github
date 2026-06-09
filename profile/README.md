<p align="center">
  <img src="https://raw.githubusercontent.com/snoutdata/.github/main/assets/logo.png" alt="SnoutData" width="180" />
</p>

**SnoutData** is an AI-driven SQL IDE for people who live in databases.

It is a standalone desktop app (not a browser tab, not a VSCode extension) that pairs a
full-featured SQL workbench with an AI assistant that actually understands your schema.
Ask a question in plain English, get SQL grounded in your real tables and foreign keys,
and drop it straight into the editor.

## See it in action

### Ask in plain English, get schema-grounded SQL

The assistant reads your live schema (tables, columns, foreign keys) and writes real,
runnable SQL, then explains its reasoning. One click drops it into the editor or a new tab.

<img src="https://raw.githubusercontent.com/snoutdata/.github/main/assets/screenshots/agent-build-report.png" alt="The AI assistant building a multi-table sales report grounded in the real schema" width="100%" />

### Paste a failing query, get the fix

Hand the assistant an error and the SQL that produced it. It diagnoses the cause against
your actual schema (a wrong table name, a missing column) and returns corrected SQL.

<img src="https://raw.githubusercontent.com/snoutdata/.github/main/assets/screenshots/agent-query-fixing.png" alt="The AI assistant diagnosing and correcting a failed query" width="100%" />

### Know your tables at a glance

Every table gets a telemetry view: storage and index sizes, schema facts (keys, indexes,
engine, collation), and the queries that recently touched it.

<img src="https://raw.githubusercontent.com/snoutdata/.github/main/assets/screenshots/table-telemetry.png" alt="The per-table telemetry view showing storage, schema, and recent queries" width="100%" />

### Connect securely

MySQL / Aurora, PostgreSQL, and SQL Server, with optional SSH tunneling and AWS Secrets
Manager. Credentials are encrypted by your OS keychain, never stored in plain text.

<img src="https://raw.githubusercontent.com/snoutdata/.github/main/assets/screenshots/connection-settings.png" alt="The connection editor with SSH tunnel and AWS Secrets Manager options" width="60%" />

### Pick the model that fits the question

Fast models for everyday SQL, more capable ones for the hard questions. Toggle which
models show in the picker.

<img src="https://raw.githubusercontent.com/snoutdata/.github/main/assets/screenshots/ai-chat-settings.png" alt="The AI model picker with fast, balanced, and powerful options" width="100%" />

### Light and dark

<img src="https://raw.githubusercontent.com/snoutdata/.github/main/assets/screenshots/themes.png" alt="SnoutData in its light theme" width="100%" />

## What you get

- **Multi-tab SQL editor** with schema-aware autocompletion, hover, and optional AI
  ghost-text completion, powered by a real language server.
- **Connect to your databases** — MySQL / Aurora, PostgreSQL, and SQL Server, with
  optional SSH tunneling and AWS Secrets Manager. Credentials are encrypted by your OS
  keychain, never in plain text.
- **A results grid** with DBeaver-style cell editing, filtering, and ordering.
- **An AI assistant** that reads your live schema and proposes SQL into your editor, with
  a chat panel, markdown replies, and per-conversation token accounting.
- **Table insights** — per-table telemetry, schema facts, and recent-query history.
- **A workspace** of `.sql` scripts on disk, plus query history and saved queries.
- **Cross-platform** desktop builds with seamless auto-update.

## Get it

👉 **[snoutdata.com](https://snoutdata.com)** — downloads, plans, and account.

## Repositories

- **[snoutdata/db](https://github.com/snoutdata/db)** — the SnoutData desktop app.
- **[snoutdata/apt](https://github.com/snoutdata/apt)** — the Debian/Ubuntu apt
  repository that powers Linux auto-updates.
