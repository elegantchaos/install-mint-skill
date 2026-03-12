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

The canonical packaged copy used on this machine lives in the shared agents repository under `codex/skills/install-mint/`.
This repository is the public repo-per-skill source used for sharing, maintenance, and refresh workflows.

## Contents

- `SKILL.md`
- `agents/openai.yaml` when host metadata is needed
- optional support folders such as `references/`, `assets/`, or `scripts/`

## Local Notes

Packaged in this repo; public repo not created yet.
