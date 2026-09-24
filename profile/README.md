# Narrate

Narrate is a small suite of voice tools for people who build with CLI agents.
Turn a document into narrated audio, or let an agent speak concise updates at
meaningful milestones.

## Projects

- [Narrate CLI](https://github.com/narrate-it/narrate) turns documents into
  spoken scripts and audio, with Pocket TTS, local macOS speech, and verified
  release downloads.
- [Narrate for Codex](https://github.com/narrate-it/narrate-codex) adds concise
  and streaming progress prompts.
- [Narrate for Cursor](https://github.com/narrate-it/narrate-cursor) adds
  project commands for phase-aware narration.
- [Narrate for Claude Code](https://github.com/narrate-it/narrate-claude-code)
  adds narration prompts through a plugin.

## Install the CLI and plugins

**Copy this prompt into your coding agent to install Narrate and the
integrations that match your environment:**

```text
Install or update the Narrate CLI and its official coding-agent plugin(s).

1. Detect my operating system, architecture, and which of Codex, Cursor, and Claude Code I use in this environment. If you cannot tell which integrations I want, ask me before installing plugins.
2. Follow the CLI's official install guide: https://github.com/narrate-it/narrate#install. Prefer the supported native package manager. If an apt feed is not enabled, use the matching .deb from https://github.com/narrate-it/narrate/releases/latest and explain that unattended apt updates require the signed feed.
3. Install the matching official integration(s), following each repository's README:
   - Codex: https://github.com/narrate-it/narrate-codex
   - Cursor: https://github.com/narrate-it/narrate-cursor
   - Claude Code: https://github.com/narrate-it/narrate-claude-code
4. Verify `narrate --version` and confirm each selected plugin or command is available.
5. Set up the documented update method for the chosen CLI install: native package-manager updates for Homebrew/apt, or Narrate's self-updating launcher for a standalone install. Never layer the self-updater onto a package-managed install.

Use only these official Narrate repositories. Preserve existing settings and files; ask before overwriting files, using sudo, adding package sources, or scheduling background updates. Do not configure AI credentials or run a narration. Report what was installed, how it updates, and anything that still needs setup.
```

Manual CLI options:

- **Homebrew:** `brew install narrate-it/narrate/narrate`
- **Debian and Ubuntu:** download the matching `.deb` from the
  [latest release](https://github.com/narrate-it/narrate/releases/latest) and
  install it with `sudo apt install ./narrate_*.deb`. For unattended apt
  upgrades, see the [signed feed setup](https://github.com/narrate-it/narrate/blob/main/docs/package-release-setup.md).

Use `--verbatim` to speak text without sending it for AI rewriting. On
macOS, `--tts=native` synthesizes speech locally.
