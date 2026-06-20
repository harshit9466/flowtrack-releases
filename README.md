<div align="center">

# ⏱ FlowTrack

### AI-Powered Desktop Time Tracker for Engineers

*Track your work effortlessly. Jira integration. Smart nudges. Auto meeting detection.*

[![Latest Release](https://img.shields.io/github/v/release/harshit9466/flowtrack-releases?style=flat-square&color=5C6BC0)](https://github.com/harshit9466/flowtrack-releases/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-blue?style=flat-square)](https://github.com/harshit9466/flowtrack-releases/releases/latest)

---

[**📥 Download Latest**](https://github.com/harshit9466/flowtrack-releases/releases/latest) · [Features](#features) · [Install](#installation) · [How It Works](#how-it-works)

</div>

---

## Features

### ⏱ Smart Time Tracking
- **Quick Capture** — Start timers instantly with `Ctrl+Shift+Space`
- **Multiple concurrent timers** — work on several tasks at once
- **System tray** — see active timers without opening the app
- **Auto-stop at end of day** — never leave a timer running overnight

### 🔗 Jira Integration
- **OAuth 2.0 connection** — secure, no password stored
- **Ticket autocomplete** — search and link as you type
- **Auto worklog push** — time logged to Jira automatically on timer stop
- **Sprint sync** — import your active tickets
- **Create tickets from tasks** — turn ad-hoc work into Jira issues

### 🤖 AI Assistant
- **Work description generation** — AI writes your log entry from ticket context
- **EOD Summary** — one-click standup bullet points
- **Morning Plan** — plan your day from yesterday's work + open tickets
- **6 providers** — Claude, Gemini, OpenAI, Ollama, Claude CLI, Gemini CLI

### 💤 Smart Detection
- **Idle detection** — prompts you to log time when you return from being away
- **Meeting detection** — auto-detects Teams, Zoom, Google Meet calls via audio API
- **Activity tracking** — nudges when you're working but forgot to start a timer
- **Break tracking** — separate break time from work time

### 📊 Dashboard
- **Daily stats** — tracked time, sessions, streak, goal progress
- **Search & filter** — find any past session by date, ticket, text
- **Task grouping** — sessions grouped by ticket or title
- **Compact UI** — everything visible without scrolling

### 🔄 Auto Updates
- **Silent auto-update** — new versions install automatically
- **Progress bar** — see download progress when updating manually
- **Configurable** — turn off auto-update if you prefer manual control

---

## Installation

### System Requirements
- Windows 10 or Windows 11
- 100 MB disk space
- Internet connection (for backend sync)

### Download & Install

1. **Download** the latest MSI from [Releases](https://github.com/harshit9466/flowtrack-releases/releases/latest)
2. **Run** `FlowTrack_x.x.x_x64_en-US.msi`
3. **Launch** FlowTrack from Start Menu or system tray
4. **Create account** or sign in

That's it. Future updates install automatically.

---

## How It Works

FlowTrack runs as a desktop app with a lightweight system tray icon. Your data syncs to a secure cloud backend.

```
Desktop App (Windows)
   ├── Quick Capture overlay (Ctrl+Shift+Space)
   ├── Dashboard with stats + sessions
   ├── System tray with active timers
   ├── Smart detection (idle, meetings, activity)
   └── Auto-updater
         │
         ▼
Cloud Backend
   ├── Session & task storage
   ├── Jira OAuth + API integration
   ├── AI provider routing
   ├── Smart nudge scheduler
   └── User settings sync
```

---

## Settings

Configure in **Settings** (gear icon):

| Tab | What |
|-----|------|
| **Profile** | Display name, timezone, work hours, daily goal, time/date format |
| **Integrations** | Jira OAuth connect, sprint sync, worklog toggle |
| **AI** | Provider selection, model, API key |
| **Nudge** | Morning plan, idle reminder, EOD summary, meeting detection, activity tracking |

---

## Privacy & Security

- 🔒 All data encrypted in transit (HTTPS) and at rest (AES-256-GCM)
- 🔑 Jira tokens encrypted, never stored in plain text
- 👁 Activity tracking is LOCAL only — window titles never leave your machine
- 🚫 No telemetry, no analytics, no tracking
- 📱 Your data belongs to you

---

## Support

Having issues? [Open an issue](https://github.com/harshit9466/flowtrack-releases/issues) on this repository.

---

<div align="center">
<sub>Built with Tauri + React + Spring Boot • © 2026 FlowTrack</sub>
</div>