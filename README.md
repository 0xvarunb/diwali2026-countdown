# diwali2026-countdown

A tiny, single-file countdown timer to **Diwali 2026** — Sunday, **November 8, 2026** (Lakshmi Puja).

## What it does

Shows a live countdown — days, hours, minutes, seconds — ticking once per second until the target moment, at which point it displays a "Happy Diwali!" greeting.

## Stack

- One file: `index.html`
- Inline CSS for the warm, festive gradient and tile layout
- A small inline `<script>` that recomputes the remaining time each second
- No build step, no dependencies, no server

## Running

Open it directly in any modern browser:

```
open index.html
```

Edits to `index.html` are live on refresh.

## Changing the target date

The target is hardcoded in the inline script as:

```js
new Date("2026-11-08T00:00:00")
```

Update that single line to point at a different moment (e.g., Choti Diwali, Govardhan Puja, or a different year).
