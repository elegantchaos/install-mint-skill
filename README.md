# Install Mint

This repository contains the `install-mint` agent skill.

## Purpose

Install or update Mint so the `mint` command is available. Use when a workflow depends on Mint and `which mint` fails, or when a user asks to install, reinstall, refresh, or update Mint.

## Compatibility

- Agent hosts: Codex-compatible skill hosts
- Publication class: `portable`

## Prerequisites

Homebrew

## Shared Baseline

This skill does not require the shared agents baseline.

## Relationship To `agents`

On machines using the shared agents control-plane repository, this skill is typically checked out under `~/.local/share/skills/` and linked into `~/.agents/skills` or `~/.codex/skills`.
This repository is the public repo-per-skill source used for sharing, maintenance, and refresh workflows.

## Contents

- `SKILL.md`
- `agents/openai.yaml` when host metadata is needed
- optional support folders such as `references/`, `assets/`, or `scripts/`

## Local Notes

Packaged here and seeded to the public repo.
