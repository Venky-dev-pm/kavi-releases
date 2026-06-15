# KAVI – OFFLINE MEETING INTELLIGENCE

**Your proactive AI Chief of Staff.** Runs 100% locally on your laptop — no cloud, no subscriptions, no data leaving your machine.

![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Privacy](https://img.shields.io/badge/privacy-100%25%20local-brightgreen)

---

## What is KAVI?

KAVI is an always-on desktop AI companion designed to run entirely on CPU-only laptops — no GPU required. It acts as your personal Chief of Staff: managing tasks, tracking your calendar, recording and summarizing meetings, and delivering daily and weekly reports — all with a voice-first interface that responds in under 600ms.

**Key highlights:**
- **100% private** — your data never leaves your machine
- **Voice-first** — speak naturally, KAVI listens and responds in real time
- **CPU-optimized** — runs on standard laptops without any GPU
- **Multi-persona** — adapts to developers, managers, product owners, and more

---

## System Requirements

| | Minimum |
|---|---|
| **OS** | Windows 10+, macOS 12+ (Apple Silicon), Ubuntu 22.04+ |
| **RAM** | 4 GB (8 GB recommended) |
| **Storage** | 2 GB free (for app + AI models) |
| **CPU** | Any modern x64 or ARM64 processor |

---

## Installation

### Windows

1. Download `Kavi_<version>_x64-setup.exe` from the [latest release](../../releases/latest)
2. Run the installer and follow the prompts
3. Launch **KAVI** from the Start Menu

### macOS (Apple Silicon)

1. Download `Kavi_<version>_aarch64.dmg` from the [latest release](../../releases/latest)
2. Open the `.dmg` file and drag **KAVI** to your Applications folder
3. On first launch, right-click → **Open** to bypass Gatekeeper

### Linux (Debian / Ubuntu)

1. Download `Kavi_<version>_amd64.deb` from the [latest release](../../releases/latest)
2. Install via terminal: `sudo dpkg -i Kavi_<version>_amd64.deb`
3. Or double-click the `.deb` file in your file manager

---

## Download AI Models

KAVI requires local AI model files to function. After installing the app:

1. Open KAVI
2. Go to **Settings → Models**
3. Click **Download Models** — KAVI will fetch and place them automatically

| Model | File | Size |
|-------|------|------|
| Speech-to-text | `whisper-tiny-q4.gguf` | ~75 MB |
| Language model | `qwen2.5-1.5b-q4.gguf` | ~900 MB |
| Text-to-speech | `en_US-amy-medium.onnx` | ~50 MB |

---

## Features

- **Voice assistant** — wake word detection, voice commands, spoken responses
- **Task management** — Kanban board, reminders, due dates
- **Calendar** — Google and Outlook integration (OAuth2)
- **Meeting recorder** — auto-transcription and AI summaries
- **Daily / weekly reports** — generated and optionally emailed to you
- **Memory** — vector search over your past conversations and notes

---

## Changelog

See [Releases](../../releases) for full version history and release notes.

---

Made with ♥ for people who want AI that respects their privacy.
