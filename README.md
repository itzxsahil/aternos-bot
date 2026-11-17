<h1 align="center">⛏️ Aternos 24/7 Minecraft AFK Bot</h1>

<p align="center">
  <a href="https://github.com/itzxsahil">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=2EA043&center=true&vCenter=true&width=900&lines=24%2F7+Mineflayer+AFK+Bot+for+Aternos+%26+PaperMC;Auto+Leave+%26+Rejoin+on+Kick+%7C+Pathfinder+Movement;Built-in+HTTP+Health+Server+for+24%2F7+Uptime;Crafted+by+itzxsahil" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Minecraft-Mineflayer-2EA043?style=for-the-badge&logo=minecraft&logoColor=white"> <img src="https://img.shields.io/badge/Node.js-v18%2B-339933?style=for-the-badge&logo=node.js&logoColor=white"> <img src="https://img.shields.io/badge/24%2F7-Infinite%20Uptime-orange?style=for-the-badge">
</p>

---

## 📸 Project Preview

<p align="center">
  <img src="assets/project-banner.svg" width="100%" alt="Project Preview" />
</p>

---

# 🚀 Overview

A robust, automated AFK client for Minecraft and Aternos servers built with **Mineflayer**. Features automated anti-AFK pathfinding, auto-reconnect on server restart, and an embedded web keepalive server for 24/7 cloud hosts.

---

# 🏗️ System Architecture & Data Flow

<p align="center">
  <img src="assets/architecture.svg" width="100%" alt="System Architecture &amp; Data Flow" />
</p>

<br>

The Node.js Mineflayer client connects to the Minecraft server protocol, executing randomized micro-movements with the Pathfinder library while Express handles HTTP keepalive probes.

---

# ✨ Features

✅ **Auto Leave & Rejoin**: Detects restarts and kicks to reconnect automatically.\n✅ **Anti-AFK Movement**: Randomized jumping, walking, and looking via `mineflayer-pathfinder`.\n✅ **HTTP Keepalive Server**: Embedded web server prevents free cloud hosts from sleeping.\n✅ **Customizable Config**: Server IP, port, and bot username configured via `settings.json`.

---

# 📦 Installation & Quickstart

```bash
git clone https://github.com/itzxsahil/aternos-bot.git
cd aternos-bot
npm install
# Edit server IP and port in settings.json
npm start
```

---

# 👤 Author & Support
- Built with ❤️ by [@itzxsahil](https://github.com/itzxsahil)
- Star ⭐ this repository if you find it helpful!
