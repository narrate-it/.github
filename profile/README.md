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

## Install the CLI

- **Homebrew:** `brew install narrate-it/narrate/narrate`
- **Debian and Ubuntu:** download the matching `.deb` from the
  [latest release](https://github.com/narrate-it/narrate/releases/latest) and
  install it with `sudo apt install ./narrate_*.deb`. For unattended apt
  upgrades, see the [signed feed setup](https://github.com/narrate-it/narrate/blob/main/docs/package-release-setup.md).
- **Coding agent:** follow the
  [online install instructions](https://github.com/narrate-it/narrate#install).

Use `--verbatim` to speak text without sending it for AI rewriting. On
macOS, `--tts=native` synthesizes speech locally.
