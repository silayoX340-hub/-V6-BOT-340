# 🤖 SilayoX-MD – WhatsApp Multi-Device Bot

**SilayoX-MD** is a powerful WhatsApp bot built with **Baileys v6**. It supports both **QR scanning** and **pairing code** login, auto‑reconnects, and includes a standalone **pairing site** to easily generate session credentials for cloud deployment (Railway, Heroku, Koyeb, etc.).

---

## ✨ Features

- ✅ Multi‑device support (Baileys MD)
- 🔑 Two login methods: **QR code** (terminal or web) and **Pairing Code** (8‑digit)
- 🔄 Auto‑reconnect on disconnect
- 📁 Session saved locally (can be copied to cloud env)
- 💬 Commands: `.menu`, `.ping`, `.alive`
- 🌐 Web‑based pairing site to get session ID for Railway/Heroku
- 🧩 Modular command structure

---

## 📦 Commands

| Command | Description |
|---------|-------------|
| `.menu` | Show all available commands |
| `.ping` | Check bot latency (response time) |
| `.alive` | Show bot status and uptime |

Prefix is configurable in `.env` (default: `.`)

---

## 🛠️ Installation & Local Run

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/SilayoX-MD.git
cd SilayoX-MD
