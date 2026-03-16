<div align="center">
  <img src="logo.png" width="200" alt="Ghostty Runner Logo" style="margin-bottom: 20px;"/>
  
  # Ghostty Runner
  
  > Run commands directly in [Ghostty](https://ghostty.org/) terminal via Alfred.

  [![License](https://img.shields.io/badge/License-Apache%202.0-blue?logo=apache&logoColor=white)](LICENSE)
  [![Release](https://img.shields.io/github/v/release/islgl/ghostty-runner?logo=github&logoColor=white&color=green)](https://github.com/islgl/ghostty-runner/releases)
  [![Alfred](https://img.shields.io/badge/Alfred-5%2B-7537D2?logo=alfred&logoColor=white)](https://www.alfredapp.com/)
  [![macOS](https://img.shields.io/badge/macOS-13%2B-000000?logo=apple&logoColor=white)](https://www.apple.com/macos/)

  ---
  
  [![Install](https://img.shields.io/badge/📦_Install_Workflow-7537D2?style=for-the-badge&logo=alfred&logoColor=white)](https://github.com/islgl/ghostty-runner/raw/main/Ghostty%20Runner.alfredworkflow)
</div>

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🚀 **Fast** | Quick command execution in Ghostty |
| ⌨️ **Simple** | Just type `>` followed by your command |
| 🎨 **Clean** | Minimalist and intuitive interface |
| ⚡ **Instant** | No delay, immediate activation |

---

## 📦 Installation

### Option 1: One-Click Install ⭐ (Recommended)

Click the **Install Workflow** badge above to download and install automatically.

### Option 2: Manual Installation

1. Download the latest `.alfredworkflow` file from [Releases](https://github.com/islgl/ghostty-runner/releases)
2. Double-click the file to import into Alfred
3. Ensure you have the [Alfred Powerpack](https://www.alfredapp.com/shop/) installed

---

## 🚀 Usage

1. **Activate Alfred** (default: `⌥ + Space`)
2. **Type** `>` followed by your command:

```bash
> ls -la
> git status
> npm install
> cargo build
> python3 script.py
```

3. **Press `Enter`** to execute in Ghostty

---

## 🎯 Examples

| Command | Description |
|---------|-------------|
| `> ls -la` | List directory contents |
| `> git log --oneline` | View git history |
| `> npm run dev` | Start development server |
| `> cargo test` | Run Rust tests |
| `> docker ps` | List running containers |

---

## ⚙️ Configuration

| Setting | Value |
|---------|-------|
| **Keyword** | `>` |
| **Category** | Productivity |
| **Bundle ID** | `cc.lglgl.alfred` |
| **Version** | 1.0.1 |

### Change Keyword

1. Open **Alfred Preferences**
2. Go to **Workflows** → **Ghostty Runner**
3. Click the keyword trigger (`>`)
4. Modify to your preferred keyword

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | macOS 13.0+ |
| **Terminal** | [Ghostty](https://ghostty.org/) (latest) |
| **Alfred** | Alfred 5.0+ with Powerpack |
| **Permissions** | Accessibility (System Events) |

---

## 🛠️ Development

### Build from Source

```bash
# Clone repository
git clone https://github.com/islgl/ghostty-runner.git
cd ghostty-runner

# Open in Alfred
open "Ghostty Runner.alfredworkflow"
```

### Project Structure

```
ghostty-runner/
├── Ghostty Runner.alfredworkflow  # Alfred workflow
├── logo.png                        # Project logo
├── LICENSE                         # Apache 2.0 License
├── README.md                       # Documentation
└── .gitignore
```

---

## 📄 License

This project is licensed under the [Apache License 2.0](LICENSE).

[![License](https://img.shields.io/badge/License-Apache%202.0-blue?logo=apache&logoColor=white&style=for-the-badge)](http://www.apache.org/licenses/LICENSE-2.0)

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

## 📚 Acknowledgments

- [Ghostty](https://ghostty.org/) - Fast, feature-rich terminal emulator by [Mitchell Hashimoto](https://github.com/mitchellh)
- [Alfred](https://www.alfredapp.com/) - Productivity app for macOS
- [Simple Icons](https://simpleicons.org/) - SVG icons for popular brands

---

<div align="center">

**Made with ❤️ by [islgl](https://github.com/islgl)**

[![Star](https://img.shields.io/github/stars/islgl/ghostty-runner?style=social)](https://github.com/islgl/ghostty-runner/stargazers)
[![Fork](https://img.shields.io/github/forks/islgl/ghostty-runner?style=social)](https://github.com/islgl/ghostty-runner/fork)

---

[⭐ Star this repo](https://github.com/islgl/ghostty-runner/stargazers) · [🍴 Fork](https://github.com/islgl/ghostty-runner/fork) · [📢 Share](https://twitter.com/intent/tweet?text=Check%20out%20Ghostty%20Runner%20for%20Alfred!&url=https://github.com/islgl/ghostty-runner)

</div>
