# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

Single-file static HTML countdown to Diwali 2026 (`index.html`) — no build system, no dependencies, no tests. Inline CSS and a small inline `<script>` handle styling and the per-second tick.

## Running

Open directly in a browser:

```
open index.html
```

No server, package manager, or build step is involved. Edits to `index.html` are live on browser refresh.

## Target date

The countdown target is hardcoded as `2026-11-08T00:00:00` (local time) — the main Diwali (Lakshmi Puja) day in 2026. If the target needs to change, update the single `new Date(...)` call inside the inline script.
