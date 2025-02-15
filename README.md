# This repository is an online backup of all files related to servers that I (templeofshadow) run personally.
### This is public for general readability of users (generally personal friends). Please don't contact me about whitelisting or anything; you will NOT recieve a response and all issues regarding this will initially be closed.
No, I will not post public IP addresses here. The servers are whitelisted but they are hosted on-prem.
IF YOU ARE WHITELISTED AND DON'T WANT TO BE: Either contact me via the Discord server that you should be a part of, or create an issue/PR here.

---

## Pertinent servers:
### Minecraft (via https://github.com/itzg/docker-minecraft-server)
- Vanilla Minecraft Latest instance
- Custom 1.21.1 NeoForge Modpack instance (I am not going to publicly distribute the raw file for this) (YOU ARE IN THIS BRANCH)
- Modified ATM9 instance (See branch https://github.com/templeofshadow/mc-server-fileshare/tree/ATM9-Server-Instance)

---

## Server-specific FAQ/PSA/Install Guide
### For this Branch (Custom NeoForge Modpack)

To get the modpack either use the mod list mentioned below or use the Modrinth app (or any other minecraft modded instance manager that supports .mrpack files).
**Modrinth App Instructions:**
1. Go to https://modrinth.com/app and take the necessary steps for your system to install the app. *(if you wish to use an existing instance manager, skip this step)*
2. Open the file attached to this message with the Modrinth app. *(if using another instance manager, use the managers "import from file" function)*

   *2.1. Do not click "Update all" in the Modrinth instance, as of writing this message [2025-01-08] the mod Supplementaries has a fatal bug in its latest posted version on Modrinth.*

4. Click "Play" and then play the game as normal.
5. To connect to the server, refer to the IP in this channel's description, or the IP at #lists-of-servers .

FYI's:

i. This modpack has a voice chat mod called "Simple Voice Chat", so try not to use the modded-1 voice channel if you can. I can't really stop you though.

ii. This modpack requires ~6-8gb of memory allocated to the game in order to properly function. Keep this in mind while configuring Modrinth (or otherwise making your modpack).

iii. This modpack has Distant Horizons installed in the client instance, but not in the server, which means that the DH LODs will only generate and render for chunks you have visited (that is-chunks that have entered your vanilla render distance). For now, there isn't a way around this for this server instance, but the DH developers have an open issue (https://gitlab.com/distant-horizons-team/distant-horizons/-/issues/19) whose last comment refers to the feature being enabled in the testing branches, so I personally think that the feature will be added in the not-so-distant future. For us right now, though, we just need to deal with it. I'll remove this FYI section when I see the update pushed to stable.

**PSA**: PolyMC now supports .mrpack import. See https://github.com/PolyMC/PolyMC/pull/1659

---

(FYI: The above was copied from the Discord)
