# sk-smp

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
| Live Chat (Discord Integration) | https://modrinth.com/plugin/dcintegration |
| Carpet | https://www.curseforge.com/minecraft/mc-mods/carpet |
| Essential Commands | https://modrinth.com/mod/essential-commands |
| Image2Map | https://modrinth.com/mod/image2map |
| Universal Shop | https://modrinth.com/mod/universal-shops |
| Inventory Sorting | https://www.curseforge.com/minecraft/mc-mods/inventory-sorting |
| Lithium | https://modrinth.com/mod/lithium |
| AntiXray | https://modrinth.com/mod/anti-xray |
| LuckPerms | https://modrinth.com/plugin/luckperms |
| Chunky | https://modrinth.com/plugin/chunky |
| Spark | https://modrinth.com/mod/spark |
| Styled Player List | https://modrinth.com/mod/styledplayerlist |
| Plan (Player Analytics) | https://www.curseforge.com/minecraft/mc-mods/plan-player-analytics |
| Axes are Weapons | https://modrinth.com/mod/axes-are-weapons |
| Perfect Accuracy | https://modrinth.com/mod/perfect-accuracy |
| Universal Graves | https://modrinth.com/mod/universal-graves |
| Squaremap | https://modrinth.com/plugin/squaremap |
| Hey That's Mine | https://modrinth.com/mod/htm |

---

## ⚙️ Server Commands

### 🏠 Essentials
| Command | Description |
|--------|------------|
| `/spawn` | Teleports you to spawn |
| `/tpa <player>` | Request to teleport to a player |
| `/tpahere <player>` | Request player to teleport to you |
| `/tpaccept <player>` | Accept teleport request |
| `/tpdeny <player>` | Deny teleport request |
| `/home set <name>` | Set a home |
| `/home tp <name>` | Teleport to a home |
| `/home delete <name>` | Delete a home |
| `/warp tp <name>` | Teleport to a warp |
| `/back` | Return to previous location |
| `/rtp` | Random teleport |

---

### 🔐 Hey That's Mine (Container Protection)
| Command | Description |
|--------|------------|
| `/htm set PUBLIC` | Public container access |
| `/htm set PRIVATE` | Owner-only access |
| `/htm set KEY` | Key-based access |
| `/htm trust <player>` | Grant access |
| `/htm untrust <player>` | Revoke access |
| `/htm remove` | Remove protection |
| `/htm transfer <player>` | Transfer ownership |

---

### 🟢 Slime Checker
| Command | Description |
|--------|------------|
| `/slime` | Check if chunk is slime chunk |

---

### 🖼️ Image2Map

#### Main Commands
| Command | Description |
|--------|------------|
| `/image2map create <W> <H> <dither/none> <URL>` | Create custom map |
| `/image2map create <dither/none> <URL>` | Create default map |
| `/image2map preview <URL>` | Preview before saving |

#### Preview Mode
| Command | Description |
|--------|------------|
| `/dither <mode>` | Toggle dithering |
| `/size` | Show current size |
| `/size <W> <H>` | Change size |
| `/grid` | Toggle grid |
| `/save` | Save map |
| `/exit` | Exit without saving |

---

### ⚔️ Factions

#### Basic Commands
| Command | Description |
|--------|------------|
| `/factions create <name>` | Create faction |
| `/factions join <name>` | Join faction |
| `/factions leave` | Leave faction |
| `/factions info` | View faction info |
| `/factions list` | List all factions |
| `/factions disband` | Disband faction |
| `/factions safe` | Open faction safe |

---

#### User Settings
| Command | Description |
|--------|------------|
| `/factions settings chat [global|faction|focus]` | Chat mode |
| `/factions settings radar` | Toggle HUD radar |
| `/factions settings sound [all|warnings|factions|none]` | Sound settings |

---

#### Management (Commander+)
| Command | Description |
|--------|------------|
| `/factions claim list` | View claims |
| `/factions claim add [size]` | Claim land |
| `/factions claim remove [size|all]` | Unclaim land |

---

#### Homes (Commander+)
| Command | Description |
|--------|------------|
| `/factions home` | Teleport home |
| `/factions home set` | Set home |

---

#### Invites (Commander+)
| Command | Description |
|--------|------------|
| `/factions invite add <player>` | Invite player |
| `/factions invite list` | List invites |
| `/factions invite remove <player>` | Remove invite |

---

#### Leader Commands
| Command | Description |
|--------|------------|
| `/factions rank promote <player>` | Promote |
| `/factions rank demote <player>` | Demote |
| `/factions rank transfer <player>` | Transfer ownership |
| `/factions kick <player>` | Kick player |

---

#### Faction Settings (Leader)
| Command | Description |
|--------|------------|
| `/f modify open <true/false>` | Public/private |
| `/f modify description <text>` | Set description |
| `/f modify color <color>` | Set color |
| `/f modify motd <text>` | Set MOTD |
| `/f modify name <name>` | Rename faction |

---

#### Relationships (Leader)
| Command | Description |
|--------|------------|
| `/f declare ally <faction>` | Ally |
| `/f declare neutral <faction>` | Neutral |
| `/f declare enemy <faction>` | Enemy |

---

#### Permissions (Leader)
| Command | Description |
|--------|------------|
| `/f permissions add/remove <perm> faction <name>` | Set faction perms |
| `/f permissions add/remove <perm> guest` | Set guest perms |

---

## 📌 Notes
- Use `/rtp` to quickly explore new areas.
- Protect valuables using **Hey That's Mine**.
- Use the live map to plan builds and locate players.
- Factions provide land protection, teamwork, and PvP dynamics.

---

Enjoy your SMP experience!
