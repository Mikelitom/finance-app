
# Development Guidelines

## Project

Offline-first finance application for two users.

## Architecture

- Monorepo architecture.
- FastAPI backend.
- React and TypeScript frontend.
- PostgreSQL central database.
- IndexedDB local database.
- iOS-first PWA.

## Backend

- Python 3.12.
- FastAPI.
- SQLAlchemy 2.
- Alembic.
- Pydantic.
- pytest.
- Ruff.

## Frontend

- React.
- TypeScript.
- Vite.
- Dexie.
- Tailwind CSS.
- shadcn/ui.

## Development Rules

- Follow existing architecture.
- Keep modules independent.
- Write maintainable code.
- Add tests for business logic.
- Use Decimal for financial calculations.
- Never commit secrets.
- Do not modify unrelated files.
- Do not change API contracts without approval.

## AI Agents

- Codex: backend development.
- Cursor: frontend development.
- Explain architectural decisions.
- Prefer simple solutions.
- Review changes before committing.

