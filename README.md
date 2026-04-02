# 🌍 Minecraft SMP Server Information

## 🧬 World Details
- **Seed:** `-8819708250424460379`
- **Live Map:** https://map.scaredkitty.net

---

## 🔧 Server Mods

| Mod | Link |
|-----|------|
| Krypton | https://modrinth.com/mod/krypton |
| Slime Checker | https://modrinth.com/mod/slime |
| Factions | https://modrinth.com/mod/factions |
| Voice Chat | https://modrinth.com/plugin/simple-voice-chat/versions |
| Live Chat | https://modrinth.com/plugin/dcintegration |
| Carpet | https://www.curseforge.com/minecraft/mc-mods/carpet |
| Essential Commands | https://modrinth.com/mod/essential-commands |
| Image2Map | https://modrinth.com/mod/image2map |
| Universal Shop | https://modrinth.com/mod/universal-shops |
| Inventory Sorting | https://www.curseforge.com/minecraft/mc-mods/inventory-sorting |
| Lithium | https://modrinth.com/mod/lithium |
| AntiXray | https://modrinth.com/mod/anti-xray |
| Luck Perms | https://modrinth.com/plugin/luckperms |
| Chunky | https://modrinth.com/plugin/chunky |
| Spark | https://modrinth.com/mod/spark |
| Styled Player List | https://modrinth.com/mod/styledplayerlist |
| Plan | https://www.curseforge.com/minecraft/mc-mods/plan-player-analytics |
| Axes are Weapons | https://modrinth.com/mod/axes-are-weapons |
| Perfect Accuracy | https://modrinth.com/mod/perfect-accuracy |
| Universal Graves | https://modrinth.com/mod/universal-graves |
| Squaremap | https://modrinth.com/plugin/squaremap |
| Hey That's Mine | https://modrinth.com/mod/htm |

---

## ⚙️ Server Commands

### Essentials

| Command | Description |
|--------|------------|
| `/spawn` | Teleports you to spawn |
| `/tpa <target-player>` | Sends a TPA request to a user to TP to |
| `/tpahere <target-player>` | Sends a TPA request for a user to TP to you |
| `/tpaccept <target-player>` | Accepts the TPA request |
| `/tpdeny <target-player>` | Denies the TPA request |
| `/home set <home-name>` | Sets a home for the user |
| `/home tp <home-name>` | TP's to the home |
| `/home delete <home-name>` | Deletes the home |
| `/warp tp <warp-name>` | TP's to an Admin sanctioned warp point |
| `/back` | Brings you back to your previous location pre-tp |
| `/rtp` | Randomly telports you in the world, useful for exploring |

---

### Hey That's Mine

| Command | Description |
|--------|------------|
| `/htm set PUBLIC` | Allows everyone to access the container |
| `/htm set PRIVATE` | Allows only the owner and those with permissions to access the container |
| `/htm set KEY` | Allows only those with a key to access the container |
| `/htm trust <player>` | Allows a player to access that container if private |
| `/htm untrust <player>` | Revokes a player's access to the container |
| `/htm remove` | Removes all protections from a container |
| `/htm transfer <player>` | Transfers ownership to another player |

---

### Slime

| Command | Description |
|--------|------------|
| `/slime` | Checks the chunk to see if it is a Slime chunk |

---

### Image2Map

| Command | Description |
|--------|------------|
| `/image2map create <WIDTH> <HEIGHT> <[dither/none]> <URL>` | Creates map of specified size (in pixels, single map is 128x128), with/without dither, using provided image |
| `/image2map create <[dither/none]> <URL>` | Creates map with/without dither, using provided image |
| `/image2map preview <URL>` | Creates dynamic preview before saving the map as item |

#### Preview Mode Commands

| Command | Description |
|--------|------------|
| `/dither <[dither/none]>` | Changes dither mode |
| `/size` | Displays current size |
| `/size <WIDTH> <HEIGHT>` | Changes size of map to specified one (in pixels, single map is 128x128) |
| `/grid` | Toggles visibility of map grid |
| `/save` | Exits preview and saves map as items |
| `/exit` | Exits preview without saving |

---

### Faction

| Command | Description |
|--------|------------|
| `/factions create <faction name>` | Creates a faction with the given name |
| `/factions join <faction name>` | Joins a faction with that name given it's open or you're invited |
| `/factions leave` | Leaves your current faction, given that you're not the current owner |
| `/factions info [<faction>]` | Displays your/another faction's description, members and power levels |
| `/factions list` | Displays faction members and power levels for every faction. |
| `/factions disband` | Disbands your current faction, given that you're the owner |
| `/factions safe` | Opens your faction's safe |

---

### Faction User Settings

| Command | Description |
|--------|------------|
| `/factions settings chat [global|faction|focus]` | Changes which chat you're currently sending and receiving from. |
| `/factions settings radar` | Toggles displaying the faction of the chunk you're currently standing inside on the hud |
| `/factions settings sound [all|warnings|factions|none]` | Changes what type of sounds the mod will play |

---

### Faction Management (COMMANDER OR ABOVE)

| Command | Description |
|--------|------------|
| `/factions claim list` | Lists all your faction claims |
| `/factions claim add [<size>]` | Claims the chunk you're standing in, or a radius around it. |
| `/factions claim remove [<size>|all]` | Removes the claim on the chunk you're standing in, or a radius around it. |

---

### Faction Homes (COMMANDER OR ABOVE)

| Command | Description |
|--------|------------|
| `/factions home` | Warps you to your designated faction home. |
| `/factions home set` | Sets your faction home to your current position |

---

### Faction Invites (COMMANDER OR ABOVE)

| Command | Description |
|--------|------------|
| `/factions invite add <player name>` | Invites that player to join your faction. |
| `/factions invite list` | Lists all your faction's outgoing invites. |
| `/factions invite remove <player name>` | Removes that player's invite to your faction. |

---

### Faction Ranks (LEADER)

| Command | Description |
|--------|------------|
| `/factions rank promote <player name>` | Promotes a player in your faction. |
| `/factions rank demote <player name>` | Demotes a player in your faction. |
| `/factions rank transfer <player name>` | Transfers the ownership of the faction to another player. |
| `/factions kick <player name>` | Kicks a player out of your faction. |

---

### Faction Settings (LEADER)

| Command | Description |
|--------|------------|
| `/f modify open <true|false>` | Sets your faction to public (true) or invite only (false). |
| `/f modify description <faction description>` | Sets your faction description. |
| `/f modify color <color>` | Sets your faction color. |
| `/f modify motd <motd>` | Sets your faction motd. |
| `/f modify name <name>` | Sets your faction name. |

---

### Faction Relationships (LEADER)

| Command | Description |
|--------|------------|
| `/f declare ally <faction name>` | Declares a faction as an ally. |
| `/f declare neutral <faction name>` | Declares a faction as neutral. |
| `/f declare enemy <faction name>` | Declares a faction as an enemy. |

---

### Faction Relationship Permissions (LEADER)

| Command | Description |
|--------|------------|
| `/f permissions [add | remove] <permission name> faction <faction name>` | Adds or removes a permission from a faction |
| `/f permissions [add | remove] <permission name> guest` | Adds or removes a permission from all guests in your faction |

---

## 📌 Notes
- Use `/rtp` to quickly explore new areas.
- Protect valuables using **Hey That's Mine**.
- Use the live map to plan builds and locate players.
- Factions provide land protection, teamwork, and PvP dynamics.
