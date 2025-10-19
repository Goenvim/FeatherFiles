# FeatherFiles OS

A lightweight, CLI-first developer operating system built on Alpine Linux.  
Designed for speed, simplicity, and deep productivity — no desktop clutter, just tools that work.
Currently in progress, will publish any work i make!

---

## Overview

**FeatherFiles OS** is a minimal Linux distribution for developers who want a focused environment without the noise.  
It boots directly into a clean terminal workspace with a curated toolset designed for efficiency and flow.

### Included Tools
- **Neovim** — fast, extensible text editor
- **LazyGit** — intuitive terminal-based Git UI
- **Docker** — containerized development made simple
- **Tmux** — multitasking in one terminal window
- **Htop** — quick system monitoring
- **Apk** — Alpine’s lightweight package manager

FeatherFiles is built to give you a minimal, portable development experience — the system is yours to shape.

---
Package Management

FeatherFiles uses Alpine’s apk package manager for fast, lightweight installations.
**sudo apk update
sudo apk add <package>
sudo apk del <package>**

You can also use the interactive Feather Menu:
**featherpkg**
This allows users to browse and install preselected developer tools through a CLI interface.
Philosophy
FeatherFiles is built on three core principles:
**Speed** — every command runs instantly, no visual overhead
**Simplicity** — clean CLI workflow, minimal dependencies
**Focus** — tools that matter, nothing else

It’s a dev environment stripped to its essentials — fast, portable, and reliable.

Repository Structure

FeatherFiles-OS/
 ├─ build/
 │    ├─ base/
 │    ├─ scripts/
 │    │    ├─ feather-install.sh
 │    │    └─ post-install.sh
 │    └─ configs/
 │         ├─ .zshrc
 │         ├─ .vimrc
 │         └─ .tmux.conf
 ├─ README.md
 └─ LICENSE
Built On
**Alpine Linux
Neovim
LazyGit
Docker
Tmux**
