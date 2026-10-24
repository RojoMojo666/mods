# Mods

## Fire & Fall 1.0

**Give fire and gravity the finger.**

![Fire & Fall cover](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.0-build26088801/Fire-and-Fall-cover.png)

Fixed fire and fall protection presets for **Helldivers 2 Steam build 26088801**.

### Downloads

Download the installable mod ZIPs from [the Fire & Fall release](https://github.com/RojoMojo666/mods/releases/tag/fire-and-fall-v1.0-build26088801). GitHub's automatic **Source code** archives are documentation snapshots, not installable mods.

| Fire protection | Fall protection | Download |
| --- | --- | --- |
| 100% | 100% | [Main release, new cover and Arsenal feather](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.0-build26088801/Fire-and-Fall-v1.0.zip) |
| 50% | 50% | [Individual variant](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.0-build26088801/Fire-and-Fall-v1.0-Fire-50-Fall-50.zip) |
| 50% | 100% | [Individual variant](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.0-build26088801/Fire-and-Fall-v1.0-Fire-50-Fall-100.zip) |
| 100% | 50% | [Individual variant](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.0-build26088801/Fire-and-Fall-v1.0-Fire-100-Fall-50.zip) |
| 100% | 100% | [Individual variant, earlier artwork](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.0-build26088801/Fire-and-Fall-v1.0-Fire-100-Fall-100.zip) |

The main release and the individual 100%/100% variant use identical gameplay data. All packages have the same mod identity: **install one at a time**.

[Cover image](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.0-build26088801/Fire-and-Fall-cover.png) · [Arsenal feather](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.0-build26088801/Fire-and-Fall-Arsenal.png) · [SHA-256 checksums](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.0-build26088801/SHA256SUMS.txt)

### What the settings do

Protection scales the regular Helldiver settings. A 50% preset halves the mapped values; a 100% preset sets them to zero.

Fire protection affects the Fire damage element. Fall protection changes minimum and maximum ragdoll/fall damage. Falling can still cause ragdolls; kill zones and other damage types are not covered. These are fixed presets without in-game sliders.

### Requirements

- HD2 Arsenal
- [Chef Shared Loader 1.1.0](https://github.com/Th3chef/Chef-Shared-Loader/releases/tag/v1.1.0), imported separately. Download `Chef-Shared-Loader-1.1.0.zip`, not its source-code archive.

### Install with Chef

1. Close the game. Restore and remove any previous Fire & Fall package or conflicting settings mod before importing.
2. Import one Fire & Fall ZIP and the Chef ZIP separately into Arsenal.
3. Enable Chef, then enable both **Fire & Fall** and **Uninstall helper** inside the Fire & Fall package.
4. Give Chef **highest priority**. With **Last mod highest priority**, put Chef last/bottom. With **First mod highest priority**, put Chef first/top.
5. Purge and Deploy.
6. Launch to the main menu, then exit normally through the game's menu.
7. Check `HD2FileMods.log` in the game folder for **APPLIED** or **OK ... in place** for `data/game/generated_entities.dl_bin`.
8. Relaunch for the settings to take effect.

The first launch and normal exit are part of installation. If the log reports **REFUSE**, **ERR** or **FATAL**, retain it and restore using the steps below.

### Uninstall, switch variant or update the game

1. Close the game.
2. Disable **Fire & Fall**, keeping **Uninstall helper** and Chef enabled.
3. Keep Chef at highest priority, then Purge and Deploy.
4. Launch to the main menu and exit normally.
5. Confirm stock restoration in `HD2FileMods.log`.
6. Only then remove the Fire & Fall package/helper and deploy again.

Restore before importing another variant, replacing the package or updating the game. If the helper or original backup was removed too early, restore game files through Steam.

### Compatibility and status

Fire & Fall, JAR-5, Slidedivers and MG-206 replace `generated_entities.dl_bin`. Use one replacement at a time; Chef does not merge these whole files.

The presets edit the shared Helldiver template. Packaging was checked offline. Arsenal import, applied damage, armor interactions and multiplayer behaviour have not been validated in-game.

Chef Shared Loader is by [Th3chef](https://github.com/Th3chef/Chef-Shared-Loader). The new cover and feather artwork were generated with the built-in image tool; the release includes the prompts.
