<div align="center">

# 🦞 Awesome Claw [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

**A curated list of efficient, open-source, OpenClaw-inspired AI assistant agents.**

<br />

![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge)

---

*The open-source personal AI assistant space is evolving fast. Inspired by [OpenClaw](https://github.com/openclaw/openclaw), a growing wave of projects is emerging — each reimagining what a personal AI agent should look like: leaner, faster, more portable, and more secure. This repository tracks that movement and provides a comprehensive directory of these projects.*

</div>

<br />

## 🌊 Why Awesome Claw?

The **Claw ecosystem** represents a growing trend of efficient, open-source, AI-powered personal assistants. It started with **OpenClaw** — a full-featured, multi-channel AI assistant that runs on your own hardware. Since then, a wave of inspired projects has emerged, each optimizing for different goals:

| Goal | Description |
|------|-------------|
| 🪶 **Efficiency** | Run on minimal hardware — from $10 boards to old Android phones |
| 🔒 **Security** | Sandbox agents in real containers instead of relying on application-level checks |
| 🧩 **Simplicity** | Small, understandable codebases that you can audit in minutes |
| 🌍 **Portability** | Single-binary deploys across ARM, x86, and RISC-V architectures |
| 🔌 **Extensibility** | Swappable providers, channels, tools, and memory backends |

This repository serves as a **central directory** for discovering, comparing, and contributing to these projects.

<br />

## 🗂️ Projects

### 📋 Project Overview

| Project | Description | Channels | Repo | Contributors |
|:--------|:------------|:---------|:----:|:------------:|
| <img src="https://raw.githubusercontent.com/openclaw/openclaw/main/docs/assets/openclaw-logo-text.png" height="40"> <br> **OpenClaw** | The original full-featured personal AI assistant — multi-agent routing, voice wake, live canvas, companion apps, and 15+ messaging channels | WhatsApp, Telegram, Slack, Discord, Signal, iMessage, Teams, Google Chat, WebChat, + more | [openclaw/openclaw](https://github.com/openclaw/openclaw) | 685+ |
| <img src="https://raw.githubusercontent.com/sipeed/picoclaw/main/assets/logo.jpg" height="40"> <br> **PicoClaw** | Ultra-efficient Go assistant for $10 hardware — AI-bootstrapped migration, single binary, runs on old Android phones | WhatsApp, Telegram, Discord, WebChat | [sipeed/picoclaw](https://github.com/sipeed/picoclaw) | 58+ |
| <img src="https://raw.githubusercontent.com/zeroclaw-labs/zeroclaw/main/zeroclaw.png" height="40"> <br> **ZeroClaw** | 100% Rust, trait-driven, zero-overhead AI infrastructure — fully swappable core, deploys anywhere | WhatsApp, Telegram, Discord, Slack | [zeroclaw-labs/zeroclaw](https://github.com/zeroclaw-labs/zeroclaw) | 64+ |
| <img src="https://raw.githubusercontent.com/HKUDS/nanobot/main/nanobot_logo.png" height="40"> <br> **nanobot** | Ultra-lightweight OpenClaw in ~4,000 lines of Python — research-ready, one-click deploy, MCP support, agent social network | Telegram, Discord, WhatsApp, Slack, Email, Feishu, QQ, MoChat | [HKUDS/nanobot](https://github.com/HKUDS/nanobot) | 50+ |
| <img src="https://raw.githubusercontent.com/jlia0/tinyclaw/main/docs/images/tinyclaw.png" height="40"> <br> **TinyClaw** | Multi-agent, multi-team, multi-channel assistant — agents collaborate via chain execution and fan-out with isolated workspaces | Discord, WhatsApp, Telegram | [jlia0/tinyclaw](https://github.com/jlia0/tinyclaw) | 8+ |
| <img src="https://raw.githubusercontent.com/memovai/mimiclaw/refs/heads/main/assets/banner.png" height="40"> <br> **MimiClaw** | Pocket AI assistant on a $5 ESP32-S3 chip — pure C, no OS, 0.5W, local-first memory on flash, runs 24/7 on USB power | Telegram, WebSocket | [memovai/mimiclaw](https://github.com/memovai/mimiclaw) | 3+ |
| <img src="https://raw.githubusercontent.com/qwibitai/nanoclaw/main/assets/nanoclaw-logo.png" height="40"> <br> **NanoClaw** | Lightweight alternative you can understand in 8 minutes — agents run in real containers with filesystem isolation | WhatsApp (extensible via skills) | [qwibitai/nanoclaw](https://github.com/qwibitai/nanoclaw) | 15+ |

<br />

### 📊 Benchmarks

| Project | Language | Memory | Startup | Architecture | Security Model |
|:--------|:--------:|:------:|:-------:|:-------------|:---------------|
| **OpenClaw** | TypeScript | ~400MB+ | Moderate | Multi-module Gateway + Agent runtime | Application-level allowlists & pairing |
| **PicoClaw** | Go | <10MB | ~1s | Single static binary | Configurable sandbox |
| **ZeroClaw** | Rust | <5MB | Near-instant | Trait-driven, fully swappable | Strict sandboxing + explicit allowlists |
| **nanobot** | Python | Low | Fast | Modular agent loop + message bus + skills | Workspace restriction + channel allowlists |
| **TinyClaw** | Shell / TypeScript | Low | Fast | File-based queue + parallel agent processing | Isolated agent workspaces |
| **MimiClaw** | C | <520KB RAM | Near-instant | Dual-core ESP32-S3 bare-metal agent loop | Local-only flash storage + network allowlists |
| **NanoClaw** | TypeScript | Low | Fast | Single process + Container isolation | OS-level container sandboxing |

<br />

---

## 🤝 Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to:

- 🆕 Submit a new project to the list
- ✏️ Improve existing descriptions
- 🐛 Report broken links or outdated information
- 💡 Suggest new categories or features

<br />

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

This is a curated list. Projects listed here are created and maintained by their respective authors and teams. We do not audit, endorse, or guarantee the security or correctness of listed projects. Please review each project individually before production use.

---

<div align="center">

**If you find this list useful, please consider giving it a ⭐**

*Inspired by the [awesome](https://github.com/sindresorhus/awesome) list community.*

</div>
