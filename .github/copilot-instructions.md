# Copilot Workspace Instructions

## Project Overview

This repository is a small FastAPI + Jinja2 + HTMX app for Social Bingo. Preserve the current route, service, and game-logic split:

- `app/main.py` handles FastAPI routes and template rendering
- `app/game_service.py` owns session-scoped state changes
- `app/game_logic.py` contains pure bingo rules
- `app/templates/` and `app/static/css/app.css` define the UI

## Design Guide

- Treat redesign work as presentation-layer changes unless the request explicitly calls for gameplay changes.
- Keep the UI HTMX-driven: interactions should continue to post back and replace `#game-container`.
- Reuse and extend the custom styles in `app/static/css/app.css` instead of introducing external UI frameworks.
- Maintain strong contrast for all interactive states, especially board squares, badges, and overlays.
- For Montreal Canadiens-themed work, favor a bold red, deep blue, ice-white palette, hockey-inspired language, and arena atmosphere without relying on direct logo artwork.
- Preserve readability over decoration: text on light surfaces should use dark ink tones, and text on dark or saturated surfaces should use light foreground colors.
- When adding new visual treatments, verify the start screen, board states, bingo banner, and modal remain visually coherent together.

## Validation

For code changes, run:

- `uv sync`
- `uv run ruff check .`
- `uv run pytest`
