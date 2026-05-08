## Hi, I'm Tomasz 👋

.NET developer focused on backend systems, clean architecture, and domain-driven design.

## Portfolio Projects

| Project | Stack | Description |
|---|---|---|
| [Warehouse Management System](https://github.com/matrixntpl/warehouse-management-system) | C# · ASP.NET Core · PostgreSQL · EF Core | ComIT capstone project and real-world solution for inventory and shipping management, featuring role-based access, domain-driven design, and repository pattern |
| [Wolf Protocol — AI Tutor Mode](https://github.com/matrixntpl/warehouse-management-system/tree/main/.claude) | Claude Code · Markdown DSL · Multi-agent pipeline | Capstone certification project: a custom AI tutoring system built on top of Claude Code. Features a 4-phase agent pipeline (plan → implement → validate → package) that teaches C# by generating stage-safe lesson plans, scaffolded exercises with TODOs, and answer keys — all enforced by a fail-closed rule engine |

<<<<<<< Updated upstream

## Tech Stack   

**Backend:** C# · ASP.NET Core · Entity Framework Core · PostgreSQL

**Patterns:** DDD · Repository Pattern · Clean Architecture

**AI Tooling:** Claude Code · Prompt Engineering · Multi-agent Orchestration

=======
### 🔧 In Development — `develop-db-postgre-migration`

Active branch ahead of `main` by 19 commits. Migrating the Warehouse Management System from SQLite to PostgreSQL in preparation for cloud deployment on Render with Neon as the managed database provider.

**What changed vs `main`:**
- Replaced SQLite with Npgsql.EntityFrameworkCore.PostgreSQL
- Rewrote all 21 historical EF Core migrations to be PostgreSQL-compatible (fixed SQLite-specific type mappings for `DateTime`, `bool`, `decimal`, raw SQL triggers, and unquoted identifiers)
- Removed the local `db/` folder and SQLite database file — data now lives in a PostgreSQL server
- Completed full data migration from SQLite to PostgreSQL (15 tables, column-order-safe CSV pipeline)
- Next: deploy to Render with Neon PostgreSQL and custom domain

## Tech Stack

**Backend:** C# · ASP.NET Core · Entity Framework Core · PostgreSQL
**Patterns:** DDD · Repository Pattern · Clean Architecture
**AI Tooling:** Claude Code · Prompt Engineering · Multi-agent Orchestration
>>>>>>> Stashed changes
**Tools:** Git · Docker · xUnit

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin)](https://linkedin.com/in/tomasz-michalczewski)
