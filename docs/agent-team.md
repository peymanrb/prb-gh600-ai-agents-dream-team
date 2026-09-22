# Agent team

This project uses a coordinated multi-agent setup to build Mona's Project Pulse dashboard with GitHub Copilot CLI in a Codespace orchestrating the work.

- Orchestrator — Model: Opus 4.7 — Oversees the overall workflow, coordinates tasks across agents, tracks progress, and ensures the dashboard requirements are met. Definition: .github/agents/orchestrator.agent.md
- Planner — Model: Opus 4.7 — Breaks the feature work into milestones, dependencies, and execution steps for the Project Pulse dashboard. Definition: .github/agents/planner.agent.md
- Coder — Model: GPT-5.5 — Implements the application logic, API integrations, and front-end behavior required by the dashboard. Definition: .github/agents/coder.agent.md
- Designer — Model: Gemini 3.1 Pro — Designs the user experience, layout, visual hierarchy, and interaction patterns for the dashboard. Definition: .github/agents/designer.agent.md

The agent definitions live under the repository agent folder at .github/agents, and the team is aligned around Mona's Project Pulse dashboard goals.
