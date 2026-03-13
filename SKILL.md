---
name: install-mint
description: Install or update Mint so the `mint` command is available. Use when a workflow depends on Mint and `which mint` fails, or when a user asks to install, reinstall, refresh, or update Mint.
---

# Install Mint

Install or update Mint with Homebrew and confirm that `mint` is available.

Read `references/workflow.md` before running commands.

## Use This Skill When

- a workflow depends on `mint` and `which mint` fails
- the user asks to install, reinstall, refresh, or update Mint

## Workflow

1. Check whether Homebrew exists.
2. If Homebrew is missing, stop and tell the user Homebrew is required before installing Mint.
3. Follow the install/update workflow in `references/workflow.md`.
4. Emit exactly one final status line using the wording rules in `references/workflow.md`.

## References

- `references/workflow.md`: full install/update workflow, command list, status-line rules, and failure handling
