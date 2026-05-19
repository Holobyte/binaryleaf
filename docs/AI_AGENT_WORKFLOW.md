# AI Agent Workflow for Binary Leaf

This document defines how Echo, Claude Code, Codex, and future automation tools should work together inside the Binary Leaf GitHub workspace.

## Purpose

Binary Leaf is the central technical workspace for software, automation, app development, WordPress systems, and AI-assisted production tools connected to Tony Holobyte's companies and projects.

## Working roles

### Echo / ChatGPT
Echo acts as the producer, architect, documentation lead, and review partner.

Echo helps with:

- Turning ideas into technical plans
- Creating clear GitHub Issues
- Reviewing pull requests
- Explaining technical work in plain English
- Designing automation workflows
- Preparing prompts and task instructions for other tools
- Keeping the technology aligned with the business goal

### Claude Code
Claude Code acts as a repo-level coding assistant.

Claude Code helps with:

- Editing project files
- Building features from GitHub Issues
- Refactoring code
- Running checks when available
- Opening pull requests
- Summarizing changed files

### Codex
Codex acts as an OpenAI coding agent.

Codex helps with:

- Implementing focused tasks
- Fixing bugs
- Creating scripts and utilities
- Reviewing code
- Building small prototypes

### Zapier or Make
Zapier or Make can act as automation runners.

They can help route content between:

- Gmail
- Google Drive
- Google Docs
- WordPress
- Calendar tools
- Task systems
- Other approved business tools

## Recommended collaboration pattern

1. Echo helps define the task.
2. The task becomes a GitHub Issue.
3. One coding agent works on a separate branch.
4. The coding agent opens a Pull Request.
5. Echo reviews the Pull Request.
6. Tony tests and approves.
7. The work is merged after review.

## Operating rules

- One agent should own one task at a time.
- Major changes should go through Pull Requests.
- The repo should keep a visible record of work.
- Drafts should stay review-ready until Tony approves publishing.
- Automations should start in review mode before becoming fully automatic.

## Suggested labels

- Echo Spec
- Claude Build
- Codex Build
- Needs Review
- Ready to Test
- Automation
- WordPress
- NotebookLM
- Fiduci
- Vollywood
- Bug
- Documentation

## First priority workflows

1. Daily AI Film Brief
2. WordPress draft-post automation
3. NotebookLM podcast source-packet workflow
4. Vollywood AI Newsroom
5. Fiduci app support and documentation
