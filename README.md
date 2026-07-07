# SourceVault Issue Tracker

This is the **public bug and feature tracker** for
[SourceVault](https://sourcevault.ai) — private, local code memory for AI.
The source repository is private, so confirmed bugs and feature requests are
tracked here where every customer can file, search, and subscribe to them.

## Before you file

**Is it a question or an install problem?** Start in our
[Discord](https://discord.gg/tq88MVQjSn) — the `#install-help` and
`#troubleshooting` forums are the fastest way to get help, and most setup
issues are resolved there without needing a tracker issue.

**Is it about licensing, billing, or a security vulnerability?** Email
[support@sourcevault.ai](mailto:support@sourcevault.ai). **Never post license
keys, tokens, or security reports publicly.**

## Filing a good bug report

Use the bug report template and include:

- Your OS: macOS, WSL2, Ubuntu/Debian, or the Docker Compose deploy
- Your SourceVault version (`sourcevault --version` or the dashboard footer)
- The output of `npm run doctor`, **with any tokens or secrets redacted**
- What you expected vs. what happened, and steps to reproduce

## What happens to your issue

We triage new issues regularly. Confirmed bugs are linked to internal work
items in the private repository; when a fix ships, the issue is closed with a
comment naming the release that contains it.
