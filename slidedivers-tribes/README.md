# HELLSLIDERS / Slidedivers – Tribes

![HELLSLIDERS – Tribes Mode Only](https://github.com/RojoMojo666/mods/releases/download/slidedivers-tribes-v1.0-build26251122/HELLSLIDERS-Tribes-cover.png)

**For when spreading democracy on foot starts to feel unnecessarily upright.**

HELLSLIDERS brings its original Tribes setup to a fixed slide preset: carry farther across flat ground, build more speed downhill and spend less stamina sliding. Terrain, collisions and normal movement interruptions can still stop a slide.

This file-mod edition applies movement settings directly, removing the earlier repeated Lua polling and avatar-memory reads. It has no settings menu.

[HELLSLIDERS on AyakaMods](https://ayakamods.com/mods/hellsliders-sliding-mod.4349/)

**Version 1.0 · Helldivers 2 Steam build 26251122**

## Choose your version

| Version | Flat speed | Downhill speed | Uphill speed | Download |
| --- | --- | --- | --- | --- |
| **Original Tribes (OG)** | 1.7× | 2.2× | 1.15× | [Download Original](https://github.com/RojoMojo666/mods/releases/download/slidedivers-tribes-v1.0-build26251122/Slidedivers-Tribes-v1.0-build26251122-Chef-Compatible.zip) |
| **Tribes Faster** | 2.0× | 4.2× | 1.15× | [Download Faster](https://github.com/RojoMojo666/mods/releases/download/slidedivers-tribes-v1.0-build26251122/Slidedivers-Tribes-Faster-v1.0-build26251122-Chef-Compatible.zip) |

Multipliers are relative to stock settings. Faster changes only flat and downhill slide speed. Uphill and all other Tribes gameplay settings are identical to Original.

Both versions share:

- Slide duration: **4× flat**, **1.75× uphill**, **5.2× downhill**.
- Slide stamina cost: **35% of normal**.
- Steep slopes: quicker slide entry, faster automatic sliding and stronger downhill pull.
- Dirt buildup while sliding: **75% of normal**.

## Requirements

- HD2 Arsenal or HD2 Mod Manager.
- [Chef Shared Loader 1.1.0](https://github.com/Th3chef/Chef-Shared-Loader/releases/tag/v1.1.0): download `Chef-Shared-Loader-1.1.0.zip`.

## Installation with Chef

1. **Close the game.** Restore and remove any existing Tribes version or conflicting settings mod using the uninstall steps below.
2. Import **one Tribes ZIP** and the **Chef Shared Loader ZIP** separately into your mod manager.
3. Enable **Slidedivers - Tribes** for Original, or **Slidedivers - Tribes Faster** for Faster. Also enable that package’s **Uninstall helper** and **Chef Shared Loader**.
4. Give **Chef the highest priority**. In Arsenal, use last/bottom when **Last mod highest priority** is selected, or first/top when **First mod highest priority** is selected. See [Chef’s installation guide](https://github.com/Th3chef/Chef-Shared-Loader#readme).
5. Deploy the enabled mods.
6. Launch to the main menu, then **exit normally through the game’s menu**.
7. Check `HD2FileMods.log` in the game folder for **APPLIED** or **OK … in place** for `data/game/generated_entities.dl_bin`.
8. Relaunch the game.

**The first launch and normal exit are part of installation. The preset takes effect on the following launch.**

If the log reports **REFUSE**, **ERR** or **FATAL**, retain the log and follow the restoration steps below.

## Uninstalling, updating or switching versions

**Restore the original settings before removing the package.**

1. Close the game.
2. Disable **Slidedivers - Tribes** or **Slidedivers - Tribes Faster**, whichever you installed. Keep its **Uninstall helper** and **Chef Shared Loader** enabled.
3. Keep Chef at the highest priority, then deploy.
4. Launch to the main menu and exit normally.
5. Confirm restoration of `generated_entities.dl_bin` in `HD2FileMods.log`.
6. Only after restoration is confirmed, disable/remove the Tribes package and its helper, then deploy again. Keep Chef enabled for other mods using it.

Complete restoration before replacing the package, switching presets or updating the game. If the helper or original backup was removed too soon, restore the game files through Steam. For a replacement ZIP with the same package ID, restore and remove the existing library entry first, then import the replacement.

## Compatibility

Use **one overlapping preset at a time**. Original Tribes, Tribes Faster, JAR-5, MG-206, Fire & Fall and other mods that replace `generated_entities.dl_bin` cannot be applied together as complete file replacements. Chef does not merge them. Restore the active preset before switching.

[Release and downloads](https://github.com/RojoMojo666/mods/releases/tag/slidedivers-tribes-v1.0-build26251122) · [Checksums](https://github.com/RojoMojo666/mods/releases/download/slidedivers-tribes-v1.0-build26251122/SHA256SUMS.txt)
