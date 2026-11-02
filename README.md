# Hi, I'm Stefan 👋

Senior IT manager with **20+ years in software engineering**, from driver and systems development (C, C++, Linux, Windows)
through software architecture to leading software development and architecture teams.
Today I'm responsible for **software development, enterprise architecture, process mining, automation and integration**
(API-first, SAP S/4HANA, SAP TM, SAP Ariba, Celonis, UiPath) and I drive **AI across the software lifecycle**:
AI-assisted development processes, CI/CD and agentic coding. On my own hardware I run local LLMs on an NVIDIA DGX Spark
and build agent tooling (MCP servers, RAG, LLM benchmarking).

Master's degree in computer science (TU Wien, with distinction), thesis in Linux kernel development
on fast startup of large programs (C, assembler).

## What I'm building on the side: an AI development team

In [**StefanOOEOrg**](https://github.com/StefanOOEOrg) a small team of AI agents develops software under a real Scrum process – I act as product owner and architect: I set the direction, review concepts and architecture, and give the final approval.

| Role | Account | Does |
|---|---|---|
| Lead | `StefanOOELeadBot` | refines features into tasks, estimates, reviews every PR, merges |
| Developer | `StefanOOEDevBot` | picks up *Ready* tasks, works test-first in its own worktree, opens the PR |
| Product owner & architect | me | plans sprints, reviews concepts and architecture, gives the second approval |

**How it works**

- One org-wide GitHub Project as backlog and sprint board – *Feature → Task/Bug*, two-week iterations, story points.
- Parallel developer instances, dispatched from the board; no chat-ops, GitHub is the single source of truth.
- Two-stage review enforced by an org ruleset: Lead approval **and** my approval before any merge.
- Quality gates: CI on every PR, coverage, linting, mutation probes against "false green" tests.
- Runs on a small self-hosted box (Nous Hermes agents, cloud and local LLMs).

📄 Full process: [PROCESS.md](https://github.com/StefanOOEOrg/.github/blob/main/PROCESS.md)

## Selected projects

All projects are open source (MIT) and self-hosted first. Common threads: my own AI-agent infrastructure (agents + MCP servers, local LLM/GPU, LLM routing), personal health and sports data, local-first tools.

**Apps and tools**

| Project | What it does | Stack |
|---|---|---|
| [newsT](https://github.com/StefanOOEOrg/newsT) | Monitors financial news and congressional trades and derives trading signals with an LLM – currently being rebuilt by the agent team | Python, PostgreSQL, Docker |
| [routeproof](https://github.com/StefanOOEOrg/routeproof) | LiteLLM proxy plugin: routes every prompt to the cheapest model that solves it well enough and measures whether the routing was right (concept phase) | Python, LiteLLM |
| [flux-workbench](https://github.com/StefanOOEOrg/flux-workbench) | Local-first workbench for FLUX image rendering: projects as folders, render queue, image comparison | Angular, FastAPI |
| [nutrition-dashboard](https://github.com/StefanOOEOrg/nutrition-dashboard) | Daily dashboard: calorie budget, macros vs. goals, meal timeline | Angular, FastAPI, PostgreSQL |

**MCP servers** – connecting AI assistants to real-world data (Python)

| Server | Connects to |
|---|---|
| [mcp-garmin](https://github.com/StefanOOEOrg/mcp-garmin) | Garmin Connect: sleep, HRV, readiness, activities, calories, weight |
| [mcp-eightsleep](https://github.com/StefanOOEOrg/mcp-eightsleep) | Eight Sleep: nightly sleep scores, stages, HRV, heart rate, temperatures |
| [mcp-nutrition](https://github.com/StefanOOEOrg/mcp-nutrition) | Food diary: meals, water, daily goals, daily and weekly reports |
| [mcp-food](https://github.com/StefanOOEOrg/mcp-food) | Nutrition database: own foods, Open Food Facts, BLS 4.0, recipes |
| [mcp-calendar](https://github.com/StefanOOEOrg/mcp-calendar) | Calendars via ICS share links (e.g. Proton Calendar) |
| [mcp-scotty](https://github.com/StefanOOEOrg/mcp-scotty) | Real-time public transport via HAFAS: ÖBB, DB, SBB, NS and more |
| [mcp-nhl](https://github.com/StefanOOEOrg/mcp-nhl) | NHL scores, standings, schedules, rosters, box scores, playoffs, draft |
| [mcp-anythingllm](https://github.com/StefanOOEOrg/mcp-anythingllm) | AnythingLLM knowledge bases (RAG over PDFs, docs, web pages) |
| [mcp-rendering](https://github.com/StefanOOEOrg/mcp-rendering) | Image generation on my own GPU server (ComfyUI / FLUX) |
| [mcp-tirepressure](https://github.com/StefanOOEOrg/mcp-tirepressure) | Bicycle tire pressure calculator, weather-aware |

## Off the keyboard

Tennis, padel, cycling, ski touring and hiking in the Austrian Alps. 🏔️
