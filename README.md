# Claude Project Template
Template repository for new projects with Claude Code web VM support.
## Features
- Pre-configured SessionStart hooks for web VM provisioning
- Automatic git configuration for commit attribution
- Personal skills and global instructions loaded from `rplsmn/claude-config`
- Ready-to-use project structure
## Usage
1. Click "Use this template" on GitHub
2. Clone your new project
3. Update `CLAUDE.md` with project-specific instructions
4. Start coding in Claude Code web!
## What Happens on Session Start
1. VM is provisioned with git config (web VM attribution)
2. Personal Claude config is fetched from `rplsmn/claude-config`
3. Skills are installed to `~/.claude/skills/`
4. Global instructions loaded to `~/.claude/docs/`
5. GitHub hooks set up via `gh-setup-hooks`
All of this happens automatically - you just need to start a session!
