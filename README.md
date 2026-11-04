# Glimpse for Claude Code

Connects Claude Code to [Glimpse](https://tryglimpse.cc), the on-device dictation and transcription app for Mac and Windows. Everything runs on your computer.

Claude can:

- Search and read your Library: meetings, recordings and imported files
- Read your recent dictations
- Follow a recording in progress, like a lecture or meeting, as it happens, and bookmark moments
- Transcribe audio and video files
- Ask you a question and get your spoken answer

## Setup

1. Install [Glimpse](https://tryglimpse.cc/download/).
2. In Glimpse, open Settings, About, and click Install CLI. Or install with Homebrew: `brew install --cask glimpse-hq/tap/glimpse`.
3. In Claude Code:

```
/plugin marketplace add glimpse-hq/Glimpse-Plugin
/plugin install glimpse@glimpse
```

If Claude Code can't find `glimpse`, see [troubleshooting](https://tryglimpse.cc/mcp/).
