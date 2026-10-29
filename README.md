# Mods

| Mod | Versions and downloads |
| --- | --- |
| [HELLSLIDERS / Slidedivers – Tribes](slidedivers-tribes/README.md) | [Original (OG) and Faster](https://github.com/RojoMojo666/mods/releases/tag/slidedivers-tribes-v1.0-build26251122) |
| [Fire & Fall](https://github.com/RojoMojo666/mods/releases/tag/fire-and-fall-v1.1-build26251122) | Fire/fall protection variants; full guide below |

---

# Fire & Fall

**Give fire and gravity the finger.**

Fire & Fall sets the Helldiver’s fire and fall damage settings multipliers to zero, providing a fixed **100% fire protection\* / 100% fall protection\*** preset.

\*You will still take tiny burn damage, you can still die from seriously hard impacts. but it's a lot more fun than the games current damage rates.

## Requirements

- Helldivers 2 Steam build **26251122**
- HD2 Arsenal
- [Chef Shared Loader 1.4.0](https://github.com/Th3chef/Chef-Shared-Loader/releases/tag/v1.4.0) — download `Chef-Shared-Loader-1.4.0.zip`, not the source-code archive.

## Updating after the game has already updated

Close the game. In Arsenal, disable the older Fire & Fall package and any older All-in-One or other mod that replaces `generated_entities.dl_bin`, then **Purge and Deploy** before importing a new ZIP.

**Do not restore an old-build `.original` backup over the updated game.** The installer refreshes an outdated backup from recognised current stock automatically; do not delete state or backup files by hand.

## Installation with Chef

1. **Close the game.** If switching packages on this game build, restore and remove the previous package first using the uninstall steps below. If the game has already updated, use the update steps above.
2. Import one **Fire & Fall 1.1 ZIP** and the **Chef Shared Loader ZIP** separately into Arsenal.
3. Enable **Chef Shared Loader**, then enable both **Fire & Fall** and **Uninstall helper** inside the Fire & Fall package.
4. Give **Chef the highest priority**. With Arsenal’s **Last mod highest priority** setting, put Chef last/bottom. With **First mod highest priority**, put Chef first/top. See [Chef’s installation guide](https://github.com/Th3chef/Chef-Shared-Loader#readme).
5. Purge and Deploy.
6. Launch to the main menu, then **exit normally through the game’s menu**.
7. Open `HD2FileMods.log` in the game folder. Look for **APPLIED** or **OK … in place** for `data/game/generated_entities.dl_bin`.
8. Relaunch the game.

**The first launch and normal exit are part of installation. The settings take effect on the following launch.**

If the log reports **REFUSE**, **ERR** or **FATAL**, retain the log and follow the restoration steps below.

## Uninstalling

**Restore the original settings before removing the package.**

1. Close the game.
2. Disable **Fire & Fall**, but keep **Uninstall helper** and **Chef Shared Loader** enabled.
3. Keep Chef at the highest priority, then Purge and Deploy.
4. Launch to the main menu and exit normally.
5. Check `HD2FileMods.log` and confirm the original settings have been restored.
6. Only then remove the Fire & Fall package and its helper, then deploy again.

Follow these restoration steps before replacing the package, switching to a conflicting mod or updating the game.

## Variants

| Fire protection | Fall protection | Download |
| --- | --- | --- |
| 0% | 25% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-0-Fall-25.zip) |
| 0% | 50% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-0-Fall-50.zip) |
| 0% | 75% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-0-Fall-75.zip) |
| 0% | 100% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-0-Fall-100.zip) |
| 25% | 0% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-25-Fall-0.zip) |
| 25% | 25% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-25-Fall-25.zip) |
| 25% | 50% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-25-Fall-50.zip) |
| 25% | 75% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-25-Fall-75.zip) |
| 25% | 100% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-25-Fall-100.zip) |
| 50% | 0% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-50-Fall-0.zip) |
| 50% | 25% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-50-Fall-25.zip) |
| 50% | 50% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-50-Fall-50.zip) |
| 50% | 75% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-50-Fall-75.zip) |
| 50% | 100% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-50-Fall-100.zip) |
| 75% | 0% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-75-Fall-0.zip) |
| 75% | 25% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-75-Fall-25.zip) |
| 75% | 50% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-75-Fall-50.zip) |
| 75% | 75% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-75-Fall-75.zip) |
| 75% | 100% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-75-Fall-100.zip) |
| 100% | 0% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-100-Fall-0.zip) |
| 100% | 25% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-100-Fall-25.zip) |
| 100% | 50% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-100-Fall-50.zip) |
| 100% | 75% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1-Fire-100-Fall-75.zip) |
| 100% | 100% | [Download](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.1-build26251122/Fire-and-Fall-v1.1.zip) |
