![Fire & Fall cover](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.0-build26088801/Fire-and-Fall-cover.png)

# Fire & Fall

**Give fire and gravity the finger.**

Fire & Fall sets the Helldiver’s fire and fall damage settings multipliers to zero, providing a fixed **100% fire protection\* / 100% fall protection\*** preset.

\*You will still take tiny burn damage, you can still die from seriously hard impacts. but it's a lot more fun than the games current damage rates.

## Requirements

- HD2 Arsenal
- [Chef Shared Loader 1.1.0](https://github.com/Th3chef/Chef-Shared-Loader/releases/tag/v1.1.0) — download `Chef-Shared-Loader-1.1.0.zip`, not the source-code archive.

## Installation with Chef

1. **Close the game.** If replacing an older Fire & Fall package or another conflicting settings mod, restore and remove it first using the uninstall steps below.
2. Import the **Fire & Fall ZIP** and **Chef Shared Loader ZIP** separately into Arsenal.
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

---

## GitHub downloads

Description above copied from [Fire & Fall on AyakaMods](https://ayakamods.com/mods/fire-fall.5603/). The main package below is the 100%/100% release described there. The other files provide the requested 50%/100% settings combinations for **Steam build 26088801**.

| Fire protection | Fall protection | ZIP |
| --- | --- | --- |
| 100% | 100% | [Main release with the new cover and Arsenal feather](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.0-build26088801/Fire-and-Fall-v1.0.zip) |
| 50% | 50% | [Individual variant](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.0-build26088801/Fire-and-Fall-v1.0-Fire-50-Fall-50.zip) |
| 50% | 100% | [Individual variant](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.0-build26088801/Fire-and-Fall-v1.0-Fire-50-Fall-100.zip) |
| 100% | 50% | [Individual variant](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.0-build26088801/Fire-and-Fall-v1.0-Fire-100-Fall-50.zip) |
| 100% | 100% | [Individual variant with earlier artwork](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.0-build26088801/Fire-and-Fall-v1.0-Fire-100-Fall-100.zip) |

Install **one ZIP at a time**. These are alternative downloads of the same mod identity. The two 100%/100% packages use identical gameplay data. GitHub’s automatic **Source code** archives are documentation snapshots, not installable mods.

[Cover](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.0-build26088801/Fire-and-Fall-cover.png) · [Arsenal feather](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.0-build26088801/Fire-and-Fall-Arsenal.png) · [SHA-256 checksums](https://github.com/RojoMojo666/mods/releases/download/fire-and-fall-v1.0-build26088801/SHA256SUMS.txt)

### Package notes

Fire & Fall, JAR-5, Slidedivers and MG-206 replace `generated_entities.dl_bin`; Chef does not merge those whole-file replacements. Restore before switching.

The presets edit the shared Helldiver template. This upload reuses the existing package bytes and adds no new gameplay or multiplayer validation.
