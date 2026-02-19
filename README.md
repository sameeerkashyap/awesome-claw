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
| **OpenClaw** | The original full-featured personal AI assistant — multi-agent routing, voice wake, live canvas, companion apps, and 15+ messaging channels | WhatsApp, Telegram, Slack, Discord, Signal, iMessage, Teams, Google Chat, WebChat, + more | [openclaw/openclaw](https://github.com/openclaw/openclaw) | 685+ |
| **NanoClaw** | Lightweight alternative you can understand in 8 minutes — agents run in real containers with filesystem isolation | WhatsApp (extensible via skills) | [qwibitai/nanoclaw](https://github.com/qwibitai/nanoclaw) | 15+ |
| **PicoClaw** | Ultra-efficient Go assistant for $10 hardware — AI-bootstrapped migration, single binary, runs on old Android phones | WhatsApp, Telegram, Discord, WebChat | [sipeed/picoclaw](https://github.com/sipeed/picoclaw) | 58+ |
| **ZeroClaw** | 100% Rust, trait-driven, zero-overhead AI infrastructure — fully swappable core, deploys anywhere | WhatsApp, Telegram, Discord, Slack | [zeroclaw-labs/zeroclaw](https://github.com/zeroclaw-labs/zeroclaw) | 64+ |

<br />

### 📊 Benchmarks

| Project | Language | Memory | Startup | Architecture | Security Model |
|:--------|:--------:|:------:|:-------:|:-------------|:---------------|
| **OpenClaw** | TypeScript | ~400MB+ | Moderate | Multi-module Gateway + Agent runtime | Application-level allowlists & pairing |
| **NanoClaw** | TypeScript | Low | Fast | Single process + Container isolation | OS-level container sandboxing |
| **PicoClaw** | Go | <10MB | ~1s | Single static binary | Configurable sandbox |
| **ZeroClaw** | Rust | <5MB | Near-instant | Trait-driven, fully swappable | Strict sandboxing + explicit allowlists |

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
