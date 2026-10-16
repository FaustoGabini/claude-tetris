# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Running

No build, package manager, tests or linter. Open `index.html` directly, or serve it with `python3 -m http.server 8000`.

## Gotchas

- `COLS`, `ROWS` and `BLOCK` in `game.js` must stay in sync with the `width`/`height` of `<canvas id="board">` in `index.html` (`COLS * BLOCK` x `ROWS * BLOCK`).
- Vanilla JS only (`'use strict'`, no modules, no dependencies). `game.js` is loaded as a plain `<script>`.
- README and user-facing UI text are in Spanish; keep new UI text consistent with that.
