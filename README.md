# Claude Code Global Config Template

A curated, production-ready global `CLAUDE.md` configuration for [Claude Code](https://claude.ai/code) - Anthropic's official AI coding assistant CLI.

## What is CLAUDE.md?

`CLAUDE.md` is a configuration file that Claude Code automatically loads into every conversation. It provides persistent context about your coding standards, workflow preferences, and project conventions.

**Global config location:** `~/.claude/CLAUDE.md`

## Features

- **Clean Architecture & Clean Code** principles enforced
- **Type-safe** coding with type hints requirement
- **Smart workflow** - explore before implementing, plan before coding
- **Git best practices** - clear commits, no credential leaks
- **Readability first** - clarity over cleverness

## Quick Start

```bash
# Clone to your .claude folder
git clone https://github.com/coelhoxyz/claude-code-global-config.git ~/.claude

# Or just copy the CLAUDE.md
curl -o ~/.claude/CLAUDE.md https://raw.githubusercontent.com/coelhoxyz/claude-code-global-config/main/CLAUDE.md
```

## Configuration

```markdown
# Global Coding Standards

## Code Style
- Always follow Clean Architecture and Clean Code principles
- Use type hints on all functions
- Prefer readability over cleverness
- Destructure imports when possible

## Workflow
- Explore codebase before implementing changes
- Plan before coding on complex tasks
- Run tests after making code changes
- Prefer single test runs over full suite for performance

## Git Conventions
- Write clear, concise commit messages
- Never commit sensitive data (API keys, credentials)

## Communication
- Ask clarifying questions before architectural changes
- Explain reasoning for non-obvious decisions
```

## Customization

Feel free to fork and customize for your needs:

- Add language-specific conventions
- Include team standards
- Add project-specific commands
- Use `@~/.claude/filename.md` to split into modules

## Resources

- [Claude Code Best Practices - Anthropic](https://www.anthropic.com/engineering/claude-code-best-practices)
- [Using CLAUDE.MD Files - Official Guide](https://claude.com/blog/using-claude-md-files)
- [Claude Code Documentation](https://docs.anthropic.com/claude-code)

## License

MIT - Use freely, customize endlessly.

---

**Keywords:** claude code, claude.md, claude code config, anthropic claude, ai coding assistant, claude code template, global config, claude code setup, agentic coding, claude cli
