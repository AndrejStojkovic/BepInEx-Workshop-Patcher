# BepInEx Workshop Patcher

The **BepInEx Workshop Patcher** allows you to load mods directly from the Steam Workshop without needing to manually copy files into your `BepInEx/plugins` folder.
Once this patcher is configured, subscribing to compatible Workshop mods in Steam will automatically make them available in your game.

---

## Prerequisites

**This item requires BepInEx to be installed first.**

If you have not set up BepInEx yet, you must download and install the base BepInEx loader into your root game directory:

* [BepInEx GitHub Releases (v6.0.0-pre.2)](https://github.com/BepInEx/BepInEx/releases#release-v6.0.0-pre.2) (Stable Release)
* [BepInEx Bleeding Edge Builds](https://builds.bepinex.dev/projects/bepinex_be) (Latest experimental builds)

Refer to the base BepInEx guide for initial loader setup instructions.

---

## How It Works

Normally, BepInEx only scans the local `BepInEx/plugins` directory for mods. This patcher hooks into the loader at startup, detects your subscribed Steam Workshop directories for this game, and dynamically loads any valid plugins directly from your Steam library.

---

## Installation & Setup

1. Make sure BepInEx is already installed and verified working.
2. Subscribe to this Workshop item.
3. Locate the downloaded patcher file inside your Steam Workshop directory, or if you cannot find it, download the patcher directly from GitHub:  
   [Direct Download (GitHub Releases)](https://github.com/AndrejStojkovic/BepInEx-Workshop-Patcher/releases/tag/Release)
4. Place the patcher `.dll` into your game's `BepInEx/patchers` directory.
5. Subscribe to any supported Workshop mods and launch the game.

---

## IMPORTANT DISCLAIMER - READ BEFORE MODDING

**Mod at your own risk.** Modifying game files and running custom code carries inherent risks to your game, your saved progress, and your computer security.

* **User Responsibility:** Modding is entirely unsupported by the game developers and Valve. Any modifications you make are done at your own discretion and expense. Always back up your save files and original game directory before adding mods.
* **Save Corruption & Instability:** Mods can cause crashes, performance drops, broken quests, game updates breaking functionality, or permanent corruption of save data.
* **Security Warning & Unknown Sources:** BepInEx executes compiled `.dll` code directly on your system with full user permissions. Malicious third parties can package malware, keyloggers, or spyware as game mods. **Never download or run mods from untrusted, obscure, or unverified websites or Discord servers.** Stick strictly to verified sources and reputable modding communities where code is reviewed.

> **Notice & Disclaimer of Ownership:**  
> I am not the creator or developer of BepInEx. This workshop item is purely an unofficial community installation guide and pointer to help players configure modding for this game. All credit and rights belong to the BepInEx Team.

## Credits & Acknowledgements

* **BepInEx:** Created by the BepInEx Team. Licensed under LGPL-2.1. ([GitHub Repository](https://github.com/BepInEx/BepInEx))
