# 🐧 WSL Installation Guide (Start from CMD)

Complete step-by-step guide to install Windows Subsystem for Linux (WSL) using Command Prompt (CMD) until it is ready for development.

---

## 📌 What is WSL?

WSL (Windows Subsystem for Linux) allows you to run a Linux environment directly inside Windows without using a virtual machine.

It is commonly used for:

- Web Development
- Laravel
- Docker
- Node.js
- Backend Development
- DevOps Practice

---

## 📋 System Requirements

- Windows 10 (Version 2004 and above) or Windows 11
- Administrator access
- Internet connection

To check your Windows version:

```bash
winver
```

---

## 🖥️ Step 1 — Open CMD as Administrator

1. Click **Start**
2. Type `cmd`
3. Right-click **Command Prompt**
4. Choose **Run as Administrator**

Or use shortcut:

1. Press `Windows + R`
2. Type `cmd`
3. Press `Ctrl + Shift + Enter`

---

## ⚙️ Step 2 — Install WSL

Inside CMD (Administrator), run:

```bash
wsl --install
```

Press Enter and wait until the installation completes.

This command will automatically:

- Enable Windows Subsystem for Linux
- Enable Virtual Machine Platform
- Install Ubuntu (default Linux distribution)

---

## 🔄 Step 3 — Restart Your Computer

After installation finishes, restart your PC.

---

## 🐧 Step 4 — Setup Ubuntu

After restarting:

1. Ubuntu will open automatically
2. Wait for installation to finish
3. Create a Linux username
4. Create a Linux password

⚠️ Password will NOT appear while typing. This is normal.

If successful, you will see:

```bash
username@DESKTOP-XXXX:~$
```

This means WSL is successfully installed.

---

## 🔎 Step 5 — Verify WSL Version

Check installed distributions:

```bash
wsl -l -v
```

Expected output:

```bash
NAME      STATE   VERSION
Ubuntu    Running 2
```

Make sure VERSION is **2**.

If it is not version 2, run:

```bash
wsl --set-version Ubuntu 2
```

To make WSL 2 default:

```bash
wsl --set-default-version 2
```

---

## 📂 Step 6 — Access Windows Files from WSL

Windows drives are mounted under `/mnt`.

Examples:

Access Drive C:

```bash
cd /mnt/c
```

Access Drive D:

```bash
cd /mnt/d
```

Access a project folder:

```bash
cd /mnt/d/ProjectName
```

---

## 🧪 Step 7 — Test WSL

Run:

```bash
ls
pwd
whoami
```

If commands work correctly, WSL is ready.

---

## 🔄 Optional — Update Ubuntu

After installation, update packages:

```bash
sudo apt update && sudo apt upgrade -y
```

Enter your Linux password when prompted.

---

## 🛠️ Useful WSL Commands

| Command | Description |
|----------|------------|
| `wsl` | Start WSL |
| `exit` | Exit Linux |
| `wsl --shutdown` | Stop all WSL instances |
| `wsl -l -v` | List installed distributions |
| `wsl --update` | Update WSL |

---

## 🗑️ Uninstall WSL (Optional)

Remove Ubuntu:

```bash
wsl --unregister Ubuntu
```

Remove WSL completely:

```bash
wsl --uninstall
```

---

## 🚀 Next Recommended Setup

After installing WSL, you can install development tools:

Install Git:

```bash
sudo apt install git -y
```

Install PHP:

```bash
sudo apt install php -y
```

Install Composer:

```bash
sudo apt install composer -y
```

Install Node.js:

```bash
sudo apt install nodejs npm -y
```

---

## ✅ Installation Complete

You now have a fully working Linux environment inside Windows.

Ready for:

- Laravel Development
- Docker
- Node.js
- Backend Projects
- DevOps Practice

---

Happy Coding 🚀
