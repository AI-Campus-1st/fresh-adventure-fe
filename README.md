# fresh-adventure-fe

Frontend repository of fresh-adventure (public).

## Purpose and Scope

- User interface and user experience
- Dashboard presentation and data visualization
- Integration with the backend API (`fresh-adventure-be`)

## Directory (provisional)

```text
public/         static images, icons, fonts
src/
├── app/        application entry and providers
├── pages/      page-level views
├── layouts/    shared layouts
├── components/ common, charts, dashboard, feedback
├── features/   feature modules
├── services/api/ backend API clients
├── hooks/ types/ utils/ constants/ styles/
tests/          unit, integration, e2e
docs/           local documentation
```

This structure is provisional until the frontend technology stack is approved.

## Planned Screens

Planned (not implemented): weekly briefing, demand trends, cost and profitability (MVP);
target customers, season and promotion calendar, AI marketing assistant (later stages).

## Related Repositories

| Repository | Visibility | Responsibility |
| --- | --- | --- |
| [fresh-adventure](https://github.com/AI-Campus-1st/fresh-adventure) | Public | Project documentation, management, shared contracts, deliverables |
| [fresh-adventure-data](https://github.com/AI-Campus-1st/fresh-adventure-data) | Private | Data ingestion, preprocessing, analytics, validation, loading |
| [fresh-adventure-fe](https://github.com/AI-Campus-1st/fresh-adventure-fe) | Public | User interface, dashboard, data visualization |
| [fresh-adventure-be](https://github.com/AI-Campus-1st/fresh-adventure-be) | Private | API services, database access, business logic, AI/LLM integration |

Private repositories are accessible to team members only.

## Current Status

- Phase 01 — directory structure only. No framework has been initialized and no dependencies are installed.

## Security

This is a **public** repository. Never place API keys, LLM keys, or database information in code or environment files.
Frontend environment variables are embedded in build output, so only values that are safe to publish may be used.

## Documentation

- Local: [docs/README.md](docs/README.md)
- Shared: https://github.com/AI-Campus-1st/fresh-adventure/tree/main/docs
