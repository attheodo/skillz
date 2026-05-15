# skillz
[![skills.sh](https://skills.sh/b/attheodo/skillz)](https://skills.sh/attheodo/skillz)
A personal collection of AI agent capabilities I frequently use in my SDLC. Curated by [attheodo](https://attheo.do)

## What are Skills?
Skills are markdown files that give AI agents specialized knowledge and workflows for specific tasks. When you add these to your project, your agent can recognize when you're working on a specific task and apply the right frameworks and best practices.

## Available Skills
<!-- SKILLS:START -->
| Skill | Description |
|-------|-------------|
| [create-prd](skills/create-prd/) | When the user needs help formulating a PRD for a new feature or refactor |
<!-- SKILLS:END -->

## Installation

### Option 1: CLI Install (Recommended)

Use [npx skills](https://github.com/vercel-labs/skills) to install skills directly:

```bash
# Install all skills
npx skills add attheodo/skillz

# Install specific skills
npx skills add attheodo/skillz --skill create-prd <other skill>

# List available skills
npx skills add attheodo/skillz --list
```

This automatically installs to your `.agents/skills/` directory (and symlinks into `.claude/skills/` for Claude Code compatibility).

### Option 2: Claude Code Plugin

Install via Claude Code's built-in plugin system:

```bash
# Add the marketplace
/plugin marketplace add attheodo/skillz

# Install all marketing skills
/plugin install skillz
```

### Option 3: Clone and Copy

Clone the entire repo and copy the skills folder:

```bash
git clone https://github.com/attheodo/skillz.git
cp -r skillz/skills/* .agents/skills/
```


