# Setting Up Codex with Node.js on WSL (Ubuntu)

This guide walks you through installing Ubuntu via WSL on Windows, setting up Node.js, and installing the OpenAI Codex CLI.

---

## 🧰 Prerequisites

* **Windows 10 or 11**
* **Administrator privileges** (for installing WSL)

---

## 1. 🔧 Install Ubuntu via WSL

Open **PowerShell as Administrator**, then run:

```powershell
wsl --install -d Ubuntu
```

This installs Ubuntu as your WSL distribution. When done, Ubuntu will launch in a new terminal window.

---

## 2. 📦 Update Ubuntu and Install Node.js

Now you're inside the Ubuntu terminal. Run the following commands to update your system and install Node.js 22:

```bash
sudo apt update && sudo apt upgrade -y
```

Install Node.js from NodeSource:

```bash
curl -fsSL https://deb.nodesource.com/setup_22.x | sudo -E bash -
sudo apt install -y nodejs
```

Check that Node.js is installed correctly:

```bash
node --version  # Should return v22.x.x
npm --version   # Ensure npm is installed
```

---

## 3. 🚀 Install OpenAI Codex CLI

Now install the Codex CLI globally using `npm`:

```bash
sudo npm install -g @openai/codex
```

Verify the installation:

```bash
codex --version
```

---

## 4. 🔐 Log in to OpenAI Codex

Run the login command to authenticate:

```bash
codex login
```

> ⚠️ You should see a **non-localhost link** where you can log in to authorize the CLI with your work account.

Once authenticated, you're ready to use Codex!

---

## ✅ Done!

You’ve now:

* Installed Ubuntu via WSL
* Installed Node.js 22 and npm
* Installed and logged into the OpenAI Codex CLI

You're all set to start coding with Codex! 🧠💻

---

Let me know if you’d like this exported to a file or expanded with troubleshooting steps.
