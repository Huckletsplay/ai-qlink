# The AI Qlink

A local-first desktop app for working with AI: local models via LM Studio, plus Claude and
Codex on your existing subscriptions - single chats, multi-model councils, and file agents,
in one window.

## Download

Grab the latest **AI-Qlink-Setup.exe** from
[**Releases**](https://github.com/Huckletsplay/ai-qlink/releases/latest).

- Windows 10 (2004+) or 11, 64-bit.
- Per-user install - no admin needed. Uninstall from Add/Remove Programs (keeps your data).
- Windows SmartScreen may warn on first run ("unknown publisher") - **More info -> Run anyway**.
- First launch runs a short setup checklist (sign in to Claude, optional LM Studio).

The app checks this page for updates; **Settings -> Check for updates** installs a new build in place.

## What's inside

This repo holds only the installers and a version manifest. The app itself is a thin
launcher over an editable PowerShell backend - nothing here phones home except the update
check (a plain request to this page).
