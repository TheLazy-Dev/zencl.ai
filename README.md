# 🌿 Zenclai (Coming soon)

[![Build](https://img.shields.io/badge/build-passing-brightgreen?style=flat-square)](https://github.com/denishgoklani/zenclai/actions)
[![License](https://img.shields.io/github/license/denishgoklani/zenclai?style=flat-square)](LICENSE)
[![Homebrew](https://img.shields.io/badge/homebrew-install-blue?style=flat-square)](https://brew.sh)
[![Version](https://img.shields.io/badge/version-v0.0.1-orange?style=flat-square)](https://github.com/denishgoklani/zenclai/releases)
---

> Minimal. Local. Smart. Your personal AI architect, developer, and mentor — right from your terminal.

Zenclai is a blazing-fast, Homebrew-installable CLI for talking to local LLMs (like Gemma, Phi, etc.) using [Ollama](https://ollama.com).  
It wraps your AI assistant in a **Zen-like workflow**: no cloud, no noise, just you and your machine.  

---

## 🚀 Features

✅ **Plug & Play AI** — instant conversations with local models  
✅ **Personas** — switch between Architect, Mentor, LazyAI, etc.  
✅ **File-aware** — analyze code/files directly from terminal  
✅ **Context Memory** *(coming soon)* — remember your last chats  
✅ **System Smartness** — add system info, timestamps to prompts  
✅ **Voice-ready** *(planned)* — mic input + TTS output  
✅ **Lightweight** — cross-platform binary (<10MB)  
✅ **Private** — 100% local, no API keys required  

---

## 📦 Installation

### 🛠 Homebrew (macOS/Linux)
```bash
brew tap denishgoklani/zenclai
brew install zenclai
```
### 📥 Manual Download
Download from Releases, then:

```bash
chmod +x zenclai
sudo mv zenclai /usr/local/bin/
```
### 💻 Usage
#### 🗨 Start Chatting
```bash
zenclai "Hey, refactor this Flutter app for scalability."
```
### 🎭 Switch Persona
``` bash
zenclai --persona arch "Design a modular monolith architecture."
```
### 📂 Analyze File
```bash
zenclai --file main.dart "Review this file for code smells."
```
### 🖥 Add System Context
```bash
zenclai --sysinfo "Optimize current system performance for Flutter builds."
```
🔥 Verbose Mode
```bash
zenclai --verbose "Walk me through dependency injection in Flutter."
```
### 📂 Features in Detail

| Feature             | Description                                    |
| ------------------- | ---------------------------------------------- |
| 🔥 Multi-persona    | Architect, Mentor, LazyAI, and custom personas |
| 📁 File analysis    | Send code or text files as part of your prompt |
| 🧠 Context memory   | Optional session memory for ongoing chats      |
| 🖥 System awareness | Adds timestamp/system status into prompt       |
| 🎙 Voice-ready      | (Planned) Microphone + TTS integration         |
### ⚙ Requirements
Ollama installed

At least one LLM downloaded locally (e.g., Gemma3:4b)

macOS, Linux, or WSL2 (Windows native coming soon)

### 🏎 Example Session
``` bash
zenclai --persona arch --file app.dart "Suggest architecture improvements for this Flutter app."
```
### 📦 Output:
```yaml
📂 File: app.dart
👔 Persona: Senior Software Architect

Big Picture: The app follows a tightly-coupled architecture. I recommend refactoring into feature modules with clear API boundaries.

Actionable Steps:
1. Introduce Clean Architecture layers.
2. Use Provider or Riverpod for state management.
3. Decouple business logic from UI components.

Trade-offs: Slight upfront complexity, but massive long-term maintainability.
```
### 🗺 Roadmap
| Version | Features                                   | Status         |
| ------- | ------------------------------------------ | -------------- |
| v0.1.0  | Basic CLI, multi-persona, file support     | ✅ Released     |
| v0.2.0  | Homebrew formula, ARM builds               | 🔄 In Progress |
| v0.3.0  | Voice I/O (Whisper + TTS)                  | ⏳ Planned      |
| v0.4.0  | Companion mobile app (Wi-Fi bridge)        | ⏳ Planned      |
| v1.0.0  | Full “Zen” assistant with memory & plugins | ⏳ Planned      |

### 🧑‍💻 Contributing
I love contributions! ❤️
Fork this repo
Create your feature branch (git checkout -b feature/my-new-feature)
Commit your changes (git commit -am 'Add new feature')
Push to the branch (git push origin feature/my-new-feature)
Create a new Pull Request
### 📜 License
MIT © Denish Goklani
### 🌿 Why Zenclai?
Because your AI should feel calm, private, and local — not like shouting across the cloud.
