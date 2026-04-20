# AGENTS.md

## Mandatory Development Checklist
Run this before opening a PR or marking work complete.

- [ ] Lint: uv run ruff check .
- [ ] Build: uv sync
- [ ] Test: uv run pytest

## Purpose
This repository is a small FastAPI + Jinja2 + HTMX app used in the Soc Ops workshop. Use this file as the fast path for safe, consistent changes.

## First 60 Seconds
1. Verify toolchain: Python 3.13+ and uv.
2. Install dependencies: uv sync.
3. Run quality checks before finishing any code change:
   - uv run ruff check .
   - uv run pytest
4. Run app locally when UI behavior is involved:
   - uv run uvicorn app.main:app --reload --host 0.0.0.0 --port 8000

## Working Rules For Agents
1. Do not use VS Code Simple Browser for this app. Open http://localhost:8000 in an external browser.
2. Treat .solutions/ as reference material only. Do not copy from it unless the user explicitly asks.
3. Prefer minimal, focused edits; keep route, service, and game-logic responsibilities separated.
4. Preserve existing behavior unless the task explicitly asks for a behavior change.

## Architecture At A Glance
- app/main.py: FastAPI app setup, session middleware, static mount, HTMX endpoints.
- app/game_service.py: session-scoped GameSession state transitions and orchestration.
- app/game_logic.py: pure bingo rules (board generation, toggles, win detection).
- app/models.py: Pydantic models and game state enums.
- app/data.py: question bank and free-space constant.
- app/templates/: Jinja templates and HTMX partials.
- app/static/css/app.css: custom utility-class system used by templates.
- tests/test_api.py: endpoint and HTML behavior tests.
- tests/test_game_logic.py: unit tests for game rules.

## Feature Implementation Conventions
1. Game rules belong in app/game_logic.py and should stay pure/testable.
2. Stateful session behavior belongs in app/game_service.py.
3. Route handlers in app/main.py should coordinate services and return template partials.
4. If you add or change behavior, update or add tests in tests/.
5. Keep templates HTMX-driven: interactions use hx-post and replace #game-container.

## Styling Conventions
1. Reuse existing utility classes from app/static/css/app.css.
2. If a new utility is needed, add it to app/static/css/app.css and apply it in templates.
3. Follow project styling instructions in .github/instructions/css-utilities.instructions.md.
4. For redesign or visual tasks, follow .github/instructions/frontend-design.instructions.md.

## Canonical References
- Project overview: README.md
- Workshop flow and tasks: workshop/GUIDE.md
- Setup walkthrough: workshop/01-setup.md
- Shared repository policy: CONTRIBUTING.md
- Global instruction rule (no Simple Browser): .github/instructions/general.instructions.md

