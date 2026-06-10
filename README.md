# Team-Facing Claude Agent Fleet

Practical guide to building a team-facing fleet of Claude Code agents (Analytics, CMO, CFO, CPO, etc.) on a dedicated Mac mini host.

📖 **[Read the guide →](https://madjunkov.github.io/team-fleet-guide/)**

## Topics covered

- Why a dedicated fleet host instead of your personal machine
- Three-tier architecture (Slack-side + non-LLM router + per-user workers)
- Mac mini hardware sizing
- Slack app bootstrap via Manifest API (script-driven)
- The non-LLM router daemon pattern — and why it's mandatory
- Per-Slack-user access model
- Operations: starting, stopping, observing the fleet
- Common failure modes and their fixes
- Recipe: adding a new persona in 30 minutes

## Based on production lessons

Distilled from running a 6-persona fleet (safety, analytics, dashboard, workflow, research, genome) across Telegram and Slack. The lessons here are the ones we paid for, not theoretical.
