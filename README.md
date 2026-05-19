# Binary Leaf Tech Workspace

Binary Leaf is the technical workspace for Tony Holobyte's software, automation, AI-agent, WordPress, app, and production-technology projects.

This repository is intended to act as a shared workbench for:

- Echo / ChatGPT planning, architecture, documentation, and review
- Claude Code or other coding agents for repo-level implementation
- GitHub Issues for task tracking
- Pull Requests for safe code review
- Zapier, Make, WordPress REST API, Gmail, Google Drive, and other automation integrations

## Core rule

No AI agent should silently overwrite major systems. Work should move through issues, branches, pull requests, and review notes.

## Initial workspace areas

- `docs/` — strategy, workflow, specs, automation plans
- `.github/ISSUE_TEMPLATE/` — task templates for AI-agent work
- `.github/pull_request_template.md` — review checklist for changes

## Recommended working model

1. Echo writes or refines the task spec.
2. The task is saved as a GitHub Issue.
3. A coding agent works on a separate branch.
4. The agent opens a Pull Request.
5. Echo reviews the PR and explains the changes.
6. Tony approves, tests, and merges when ready.

## First target projects

- Vollywood AI Newsroom automation
- WordPress draft-post pipeline
- NotebookLM podcast source-packet workflow
- Fiduci app support utilities
- Vollywood.org technical maintenance
