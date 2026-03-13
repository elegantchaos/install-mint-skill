# Install Mint Workflow

## Commands

Check whether Homebrew exists:

```bash
which brew
```

Capture pre-install state:

```bash
which mint
mint --version
```

Install or update Mint:

```bash
brew install mint
```

Capture post-install state:

```bash
which mint
mint --version
```

## Status Line Rules

Emit exactly one final status line:

- If Mint was not installed before install and is installed after:
  `Mint <version> installed.`
- If Mint was installed before install and the version changed:
  `Mint <old_version> updated to <new_version>.`
- If Mint was installed before install and the version is unchanged:
  `Mint <version> already installed.`

If installation fails, report actionable Homebrew error details and do not emit one of the success status lines.

## Notes

- `brew install mint` is the canonical command for both install and update in this workflow.
- Parse `<version>` from `mint --version` output by extracting the version token from the command output.
- Do not modify shell startup files in this skill. If PATH issues appear, report them and ask the user before making environment changes.
