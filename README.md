# ⚔️ Level Up My Mobs

![Minecraft](https://img.shields.io/badge/Minecraft-1.21.1-brightgreen?logo=minecraft)
![NeoForge](https://img.shields.io/badge/Modloader-NeoForge-orange?logo=neoforge)
![License](https://img.shields.io/badge/License-MIT-yellow)

A Minecraft mod for **NeoForge** that makes gameplay more dynamic and challenging! Mobs dynamically scale over time or based on specific conditions—gaining more health, dealing increased damage, and rewarding players with better loot.

---

## 🌟 Features

* 📈 **Dynamic Scaling:** Mobs scale over time, distance from spawn, or player progression.
* ❤️ **Increased Health & Damage:** Stronger mob attributes to keep the late game challenging.
* 🏆 **Better Rewards:** Defeating tougher mobs yields higher-tier loot and extra experience points.
* ⚙️ **Fully Configurable:** Fine-tune scaling multipliers, stat caps, and mechanics to suit your playstyle.

---

## 📥 Installation

1. Download and install [NeoForge](https://neoforged.net/) for your target Minecraft version.
2. Download the latest release of **Level Up My Mobs** from [Modrinth](#) or [CurseForge](#).
3. Place the downloaded `.jar` file into your `.minecraft/mods` directory.
4. Launch the game and customize the configuration file as needed!

---

## ⚙️ Configuration

This mod utilizes the native NeoForge configuration system. Upon the first launch, a configuration file will be generated at:

`.minecraft/config/levelupmymobs-common.toml`

Example configuration snippet:

```toml
[scaling]
# Multiplier applied to max health
healthMultiplier = 1.5

# Multiplier applied to attack damage
damageMultiplier = 1.2

# Additional experience dropped (e.g., 0.25 = +25% XP)
xpBonus = 0.25
