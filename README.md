# SysMDC
Native macOS app to create, organize, and execute cross-platform system commands (Windows, Linux, macOS). Streamline terminal workflows with secure execution, smart categorization, and iCloud sync.

# 🖥️ CmdHub
> A native macOS app to create, organize, and execute system commands across Windows, Linux, and macOS.

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Swift](https://img.shields.io/badge/Swift-5.9-orange.svg)](https://swift.org)
[![macOS](https://img.shields.io/badge/macOS-13%2B-black.svg)]()
[![Platform](https://img.shields.io/badge/Target-Win%20%7C%20Linux%20%7C%20macOS-lightgrey.svg)]()

## 📖 Overview
**CmdHub** is a lightweight, native macOS application designed to streamline your system administration and automation workflow. Stop juggling terminal snippets across different operating systems. Create, categorize, and manage cross-platform commands (Windows CMD/PowerShell, Linux Bash/Zsh, macOS Terminal) from a single, unified interface.

Whether you're maintaining a personal command library, automating deployments, or managing remote infrastructure, CmdHub keeps your workflow organized, secure, and efficient.

## ✨ Features
- 🌍 **Cross-Platform Command Management** – Store and generate OS-specific commands with automatic syntax highlighting
- 📂 **Smart Organization** – Categorize by project, OS, or tags. Full-text search, filters, and smart folders
-  **One-Click Execution** – Run commands locally or via SSH with real-time stdout/stderr output and execution history
- 🔒 **Secure & Safe** – Environment variable injection, dry-run mode, sandboxed execution, and explicit sudo confirmation
- ☁️ **Sync & Backup** – Local SQLite storage with optional iCloud sync or Git-based versioning
-  **Native macOS Experience** – Built with SwiftUI, optimized for Apple Silicon, supports Dark Mode, keyboard shortcuts, and Services integration
-  **Logging & Analytics** – Track execution times, success/failure rates, and command usage frequency


## 🚀 Installation
### Option 1: Download Pre-built
1. Go to the [Releases](../../releases) page
2. Download the latest `.dmg` or `.zip`
3. Drag `CmdHub.app` to your Applications folder

### Option 2: Build from Source
```bash
git clone https://github.com/yourusername/cmdhub.git
cd cmdhub
open CmdHub.xcodeproj
# Build & run in Xcode (requires macOS 13+ & Swift 5.9+)
