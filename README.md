# AI DB Agent

Natural-language business intelligence over your databases — ask questions in plain language, get answers and reports.

> **Note:** This repository is a public portfolio showcase. Source code is private.

## Problem

Business users often need answers from SQL databases but shouldn't have to write queries, manage BI tools, or wait on analysts for every question.

## What I built

- Chat-style interface to ask questions about company data
- AI-assisted querying against connected databases
- Multi-tenant app with auth, admin, and role-based access
- Embeddable dashboards/reports
- Billing integration (Paddle) for plans/trials
- Deployable stack (Docker / production-oriented setup)

## Tech stack

- **Backend:** Python, FastAPI
- **Data:** PostgreSQL
- **AI:** OpenAI APIs / embeddings for data Q&A
- **Frontend:** HTML/JS app UI + marketing landing
- **Infra:** Docker Compose, migrations, webhook integrations

## Architecture (high level)

``text
User → Web UI → FastAPI API → AI layer → Tenant DB(s)
                      ↓
              Control DB (users, orgs, config)
``

## Demo

- Live demo: https://app.dbeespot.com
- Screenshots: 

## My role

Solo builder — product design, backend, AI integration, auth/billing, and deployment.

## Contact

- GitHub: https://github.com/reroig
- Email: reroig@gmail.com
