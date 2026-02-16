##⚠️ Repository Archived
**This repository is no longer maintained and has been set to read-only.**

# PVC Discord Bot  

A powerful and polished Discord bot that lets your community create and manage **private temporary voice channels (PVCs)** with ease.  
Built with `discord.js v14` and modern **V2 Components UI**, it gives server owners a smooth, customizable, and interactive experience.  

![Bot Preview Card](src/assets/GitHubCard.png)  
![PVC Controls](src/assets/pvc-controls.png)  

---

## ✨ Features

- **Private Voice Channels** – Members can instantly create their own PVCs.  
- **Automatic Cleanup** – Channels are deleted when empty, keeping your server clean.  
- **Full Channel Control:**  
  - Lock / Unlock access  
  - Hide / Unhide visibility  
  - Rename channel  
  - Set user limit  
  - Adjust bitrate & region  
  - Disconnect users  
  - Delete channel instantly  
- **Interactive Setup** – Easy `/setup` process with a modern UI.  
- **Slash Commands** – Simple commands for configuration and management.  
- **Sharding Support** – Built to scale for large communities.  

---

## 🛠️ Commands

### Slash Commands
- `/about` – Shows info about the bot (version, creator, GitHub link).
- `/uptime` – Displays how long the bot has been running.
- `/invite` – Gives an invite link to add the bot to other servers.
- `/support` – Provides a link to your support server (Zarco HQ).
- `/stats` – Shows bot statistics (guild count, users, channels, memory usage).
- `/ping` – Check bot latency and uptime.  
- `/setup` – Launches PVC interactive setup.  
- `/remove` – Removes PVC configuration from the server.  
- `/setup` - Initialize the Temporary Voice Channel (PVC) system on this server.
- `remove` - Remove the Temporary Voice Channel (PVC) system configuration from this server.
- `/ping` - Check the app latency and status

### PVC Controls (Button UI)
- 🔒 Lock / Unlock  
- 👁️ Hide / Unhide  
- ✏️ Rename  
- 👥 User Limit  
- 🎵 Bitrate  
- 🌍 Region  
- ⛔ Disconnect Users  
- 🗑️ Delete Channel  

---

## 📷 Previews

### Control Panel UI  
![Control Panel](src/assets/pvc-controls.png)

### Interactive Setup Example  
![Setup Example](src/assets/command-demo.png)  

---

## 🚀 Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/ZarCodeX/pvc-discord-app-with-v2-components.git
   cd pvc-discord-app-with-v2-components
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Setup environment**
   Create `.env` in root:
   ```env
   TOKEN=YOUR_BOT_TOKEN
   CLIENTID=YOUR_BOT_CLIENT_ID
   ```

4. **Run the bot**
   ```bash
   npm start
   ```

---

## ⚙️ Configuration

**⚠️ Important Note:** The data is stored in `.json`, so it is not recommended if bot is on large number of servers. You can change this to whatever you want.

- Bot global config: `src/config/config.json`  
- Per-server PVC setup: `data/{guild_id}/PVC/pvc.json`  

---

## 🙌 Credits  

Developed by **[ZarScape](https://github.com/ZarScape)**  

- 🎥 [YouTube](https://www.youtube.com/@ZarCodeX)  
- 💬 [Discord Server (Zarco HQ)](https://discord.gg/6YVmxA4Qsf)  
- 🧑‍💻 [GitHub](https://github.com/ZarCodeX)  

---

## 📜 License  
Licensed under the [MIT License](LICENSE).
