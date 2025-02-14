# This repository is an online backup of all files related to servers that I (templeofshadow) run personally.
### This is public for general readability of users (generally personal friends). Please don't contact me about whitelisting or anything; you will NOT recieve a response and all issues regarding this will initially be closed.
No, I will not post public IP addresses here. The servers are whitelisted but they are hosted on-prem.
IF YOU ARE WHITELISTED AND DON'T WANT TO BE: Either contact me via the Discord server that you should be a part of, or create an issue/PR here.

---

## Pertinent servers:
### Minecraft (via https://github.com/itzg/docker-minecraft-server)
- Vanilla Minecraft Latest instance
- Custom 1.21.1 NeoForge Modpack instance (I am not going to publicly distribute this.)
- Modified ATM9 instance (YOU ARE IN THIS BRANCH)

---

## Server-specific FAQ/PSA/Install Guide
### For this Branch (Modified ATM9)
This server runs a slightly modified version of All the Mods 9 (https://www.curseforge.com/minecraft/modpacks/all-the-mods-9). I have added Simple Voice Chat and Sound Physics Remastered.

Technically, it isn't required to install these, but it is recommended.

For the added mods, go to these links and download the file:
- https://modrinth.com/plugin/simple-voice-chat/version/forge-1.20.1-2.5.26
- https://modrinth.com/mod/sound-physics-remastered/version/forge-1.20.1-1.4.8

You can install the pack several ways. The most mainstream option is via the **Curseforge launcher**, which is fairly straightforward. You may also use a third-party instance manager such as **PolyMC** or **ATLauncher**. Alternatively, the modlist is public on the Curseforge page so you could also manually install the mods into a custom forge instance if you so wish (although I don't believe any of us are that masochistic).

Any client-side mods can be added or removed at will. As long as you aren't blatantly cheating, I won't police it. However, some mods that are usually client-side have integrations on the server that make them required. These are:
- **Journeymap** (via the chunk claiming addon)

I personally reccomend running any modpack with Distant Horizons, as it is more immersive. As with the custom server, DH isn't installed in server since the multiplayer functionality hasn't been implemented in a production version yet. I will add it when the multiplayer functionality has been added to a release.

For clarity, server mods added by me:
- Bluemap
- Simple Voice Chat
- Sound Physics Remastered
- Chunky (this one is just for servers, don't install it)
- EMI Ores (only install if you have EMI on client)

**PSA: EMI currently doesn't display some recipes. I made an issue (see https://github.com/emilyploszaj/emi/issues/860), so we'll see if it's an actual problem or not. Will update this upon fix.**

Bluemap is at http://\[REDACTED\]:50702/.

---
