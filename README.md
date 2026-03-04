# Context Terminal

A modern Linux terminal that remembers **command history and working directory per tab**, organized by projects.

Designed for developers who work on multiple projects simultaneously and need **true context isolation**.

![Demo](https://github.com/stanislavliannyk/context-terminal-releases/blob/main/demo.gif?raw=true)

---

## ✨ Features

- 🧠 Per-tab command history  
- 📁 Per-tab working directory  
- 🗂 Project-based tab organization
- 🐳 Per-container history (Docker)
- ♻️ Context preserved across restarts  
- 🐧 Native Linux packages (.deb / .rpm)  
- ⚡ Lightweight and fast  

---

## 🧩 How It Works

Context Terminal introduces **Projects**.

Each project:

- Contains its own tabs  
- Each tab has its own working directory  
- Each tab stores its own command history  
- All state is restored after restart  

No shared history.  
No mixed contexts.  
No confusion between repositories.

---

## 📦 Download

Download the latest package from Releases:

https://github.com/stanislavliannyk/context-terminal-releases/releases

Available formats:

- `Context.Terminal-0.1.0-1.x86_64.rpm`
- `Context.Terminal_0.1.0_amd64.deb`

---

## 🐧 Installation

### Fedora / RHEL / CentOS (RPM)

```bash
sudo rpm -Uvh Context.Terminal-0.1.2-1.x86_64.rpm
```
Or:
```bash
sudo dnf install Context.Terminal-0.1.2-1.x86_64.rpm
```

### Ubuntu / Debian (DEB)
```bash
sudo dpkg -i Context.Terminal_0.1.2_amd64.deb
```
Or:
```bash
sudo apt install ./Context.Terminal_0.1.2_amd64.deb
```

Your existing projects/tabs remain intact. New in 0.1.2: container history is now isolated per container.

### ▶️ Launch

After installation, launch from:

Application menu

Or terminal:
```bash
context-terminal
```
