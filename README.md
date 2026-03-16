# Ghostty Runner

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![GitHub release](https://img.shields.io/github/v/release/islgl/ghostty-runner)](https://github.com/islgl/ghostty-runner/releases)
[![Version](https://img.shields.io/badge/version-1.0.1-blue)](https://github.com/islgl/ghostty-runner/releases/tag/v1.0.1)
[![Alfred](https://img.shields.io/badge/Alfred-5%2B-3786d4)](https://www.alfredapp.com/)

> Run commands directly in [Ghostty](https://ghostty.org/) terminal via Alfred.

[![Install Workflow](https://img.shields.io/badge/📦-Install%20Workflow-3786d4?style=for-the-badge)](https://github.com/islgl/ghostty-runner/raw/main/Ghostty%20Runner.alfredworkflow)

![Logo](logo.png)

---

## ✨ Features

- 🚀 Quick command execution in Ghostty
- ⌨️ Simple keyword trigger (`>`)
- 🎨 Clean and intuitive interface
- ⚡ Instant activation with Alfred

---

## 📦 Installation

### Option 1: Click to Install (Recommended)

Click the badge button above to download and install automatically.

### Option 2: Manual Installation

1. Download the latest `.alfredworkflow` file from [Releases](https://github.com/islgl/ghostty-runner/releases)
2. Double-click the file to import into Alfred
3. Ensure you have the [Alfred Powerpack](https://www.alfredapp.com/shop/) installed

---

## 🚀 Usage

1. Activate Alfred (default: `⌥ + Space`)
2. Type `>` followed by your command:

```
> ls -la
> git status
> npm install
> cargo build
```

3. Press `Enter` to execute in Ghostty

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | macOS 13.0+ |
| **Terminal** | [Ghostty](https://ghostty.org/) (latest version) |
| **Alfred** | Alfred 5.0+ with Powerpack |
| **Permissions** | Accessibility (for System Events) |

---

## 🔧 Configuration

| Setting | Value |
|---------|-------|
| **Keyword** | `>` |
| **Category** | Productivity |
| **Bundle ID** | `cc.lglgl.alfred` |

To change the keyword:
1. Open Alfred Preferences
2. Go to Workflows → Ghostty Runner
3. Click the keyword trigger and modify

---

## 📸 Preview

![Preview](icon.png)

---

## 🛠️ Development

### Build Workflow

```bash
# Clone repository
git clone https://github.com/islgl/ghostty-runner.git
cd ghostty-runner

# Open in Alfred
open "Ghostty Runner.alfredworkflow"
```

### Structure

```
ghostty-runner/
├── Ghostty Runner.alfredworkflow  # Alfred workflow file
├── icon.png                        # Workflow icon
├── info.plist                      # Workflow configuration
└── README.md                       # This file
```

---

## 📝 License

This project is licensed under the [Apache License 2.0](LICENSE).

```
Copyright 2026 islgl

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

---

## 🙋 Support

- **Issues**: [GitHub Issues](https://github.com/islgl/ghostty-runner/issues)
- **Email**: hi@lglgl.cc
- **Website**: lglgl.cc

---

## 📄 Acknowledgments

- [Ghostty](https://ghostty.org/) - Fast, feature-rich terminal emulator
- [Alfred](https://www.alfredapp.com/) - Productivity app for macOS

---

<div align="center">

**Made with ❤️ by [islgl](https://github.com/islgl)**

[⭐ Star this repo](https://github.com/islgl/ghostty-runner/stargazers) | [🍴 Fork](https://github.com/islgl/ghostty-runner/fork) | [📢 Share](https://twitter.com/intent/tweet?text=Check%20out%20Ghostty%20Runner%20for%20Alfred!&url=https://github.com/islgl/ghostty-runner)

</div>
