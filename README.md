# 🎮 Panaland Minecraft Server 🌍
An optimized Minecraft Survival 1.16.5 server with custom plugins and maps.

![PanalandWallpaper](https://github.com/Ivanobix/Panaland/assets/56084434/eac933f4-0bb1-4fcd-accd-d07a294245db)

## 📜 Overview
Panaland is a custom Minecraft server (version 1.16.5) tailored for survival multiplayer gameplay. It's designed for intimate player experiences, ideally accommodating up to 20 players at once.

The server is optimized to run even on low-resource devices like the **Raspberry Pi 4 Model B (4GB RAM)**. Here's what we've done to ensure a smooth experience:
- ⚙ Carefully tuned configuration files.
- 🚀 Plugins focused on enhancing server performance.
- 🎒 Features including user control, economy, backpacks, customized mobs, and more.
- 🗺 A vast custom map that offers an enriched gameplay experience beyond the base game.

## 🚀 Getting Started

### 🔧 Installation
The server requires at least **Java Version 11**. You may try using a newer version like 1.16, but compatibility isn't guaranteed.

### 🎮 Launching the Server
Everything's set up! Just clone this repo and launch:
- **Windows**: Navigate to the repo's directory and run "run.cmd" as administrator.
- **Linux**: Navigate to the repo's directory, then execute the "run.sh" file using the command `sudo bash run.sh`.

After you initiate the server, it might take a few minutes to load, depending on your device. **Note**: There's no message indicating the server's completion of loading, so rely on the terminal messages as a guide.

⚠ **Important**: To shut down the server safely, use the "stop" command within the console. Don't close the console directly as this may damage the server.

## 📘 User Guide

The server is ready to play right out of the box! But if you're feeling adventurous:
- 🛠 Dive in and see the myriad of ways to customize and enhance your server further.
- 💡 Who knows? Your server might just become the next big thing in the Minecraft world!

### 🖥️ How to Connect
- Local Network: Add the server in Minecraft using the address "localhost".
- Friends' Access: You'll need to configure your router to point to your server. This varies across routers, but many YouTube tutorials can guide you.

### 🎚 Performance Tuning
By default, the server consumes 2GB of RAM. If your device can handle it, you might want to allocate more. Adjust the following properties in the boot file (`run.cmd` for Windows or `run.sh` for Linux):
- Xmx2G (Max RAM)
- Xms2G (Starting RAM)

💡 Tip: Don't go below 2GB or allow the server to consume more than 50% of your available RAM.

### 🔄 Updates
It's normal for update messages to appear for certain plugins during server startup. I've ensured that all included plugins are stable versions, but if you're keen to stay updated, follow the console's instructions. Remember to back up first!

## 🔍 Additional Information:
- 🛠 Modify or remove plugins and maps simply by replacing or deleting them.
- ⚙ All configurations are customizable. Feel free to experiment!

## 🗺 Map Preview
![mapa](https://user-images.githubusercontent.com/56084434/135663307-3aaa903e-c9fe-4cce-91aa-783947b5a691.png)

## 🆘 Need Help?
[Open an Issue](https://github.com/Ivanobix/Panaland/issues)

## 👏 Credits
- [Custom Overworld Map](https://www.planetminecraft.com/project/drehmal-v2-prim-rdial-12k-x-12k-survival-adventure-map/)

## 📜 License
- [License Summary](https://creativecommons.org/licenses/by-nc/4.0/deed.es)
- [Full License](https://creativecommons.org/licenses/by-nc/4.0/legalcode.es)
