# HR AI Agent — Unified System

A comprehensive HR automation system with integrated Google Calendar scheduling.
Team - Ozark

## Repository Layout

This repo contains two ways to run the same HR agent:

| Folder | What it is | Use this when... |
|---|---|---|
| [`main`](./main) | Standalone FastAPI app with a web dashboard (JD generation, resume screening, email drafting, calendar scheduling, onboarding, helpdesk) | You want to run the full system locally with a UI |
| [`hr-ai-agent/`](./hr-ai-agent) | The same HR skillset packaged as an A2A (Agent-to-Agent) protocol agent for the Nasiko platform | You want to deploy the agent behind the A2A JSON-RPC interface |

See each folder's own README for setup and usage instructions.

## Core Features

- **Job Description Generator** — AI-powered JD creation
- **Job Posting** — Multi-platform job posting (Telegram, etc.)
- **Resume Screening** — Automated candidate screening with semantic similarity
- **Email Agent** — Draft and send interview emails
- **Interview Scheduler** — Smart, Google Calendar-based scheduling (timezone + holiday aware)
- **Interview Questions** — Generate role-specific interview questions
- **Helpdesk** — Knowledge-base Q&A for HR policies
- **Onboarding** — Automated onboarding document generation



## License

This project is provided as-is for hackathon/educational purposes.
