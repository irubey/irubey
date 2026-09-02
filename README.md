## Isaac Rubey

Founder and engineer in Denver, CO. I build data-heavy web applications and the pipelines behind them.

**[SendSage](https://sendsage.ai)** is my main project: a climbing logbook and analytics platform. It imports the logbook you already have (Mountain Project today) and then gives you things the source platform doesn't: natural language logging across 10+ activity types, multi-discipline tracking, and visualizations built to actually teach you something about your own climbing history rather than just display it.

I built it end to end. Next.js and TypeScript on the front, FastAPI and Python on the back, Postgres on Supabase, in a pnpm and Turbo monorepo. Two pieces I'm particularly happy with: a LangGraph enrichment agent that resolves imported ticks to real routes, areas, and grades, and a natural language logging pipeline that maps free-form session notes onto per-discipline data structures.

I also take on fractional technical work: architecture, data pipelines, and analytics for small teams.

### Open source

- **[gqlgen](https://github.com/99designs/gqlgen)**: added the `@inlineArguments` directive, which lets clients pass flat arguments while resolvers receive a single bundled parameter ([#3924](https://github.com/99designs/gqlgen/pull/3924))
- **[gqlgen](https://github.com/99designs/gqlgen)**: migrated the project off the archived go-yaml onto goccy/go-yaml ([#3913](https://github.com/99designs/gqlgen/pull/3913))
- **[genqlient](https://github.com/Khan/genqlient)**: added a `--version` flag that prints build info ([#411](https://github.com/Khan/genqlient/pull/411))
- **[PUDL](https://github.com/catalyst-cooperative/pudl)**: integrated EIA Form 191 underground natural gas storage data into the ETL ([#5058](https://github.com/catalyst-cooperative/pudl/pull/5058))

### Tools

TypeScript, Python, Go, React, Next.js, FastAPI, Postgres, Supabase, LangGraph, Docker, D3.

### Elsewhere

[sendsage.ai](https://sendsage.ai) · [LinkedIn](https://www.linkedin.com/in/isaac-rubey-511789143/)
