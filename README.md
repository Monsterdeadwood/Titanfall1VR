> [!IMPORTANT]
> **[TEST BUILDS & DISCUSSION · FLAT2VR DISCORD](https://discord.gg/P4q9zt7ek)**
> Testing, build requests, feedback and discussion happen in the **Flat2VR Modding Discord**. Join the server and find the **Titanfall 1 VR** thread.

![Titanfall 1 VR — Monsterdeadwood VR mods](assets/vr-banner.svg)

# Titanfall 1 VR

[English](README.md) · [Русский](README_RU.md) · [Flat2VR Discord](https://discord.gg/P4q9zt7ek) · [All projects](PORTFOLIO.md)

![Project status](assets/vr-status.svg)

A VR development branch for Titanfall 1 on supported R1Delta builds, combining stereo viewing, pilot weapon aiming and Titan cockpit work. Thanks to the [R1Delta team](https://r1delta.net/) for their community platform.

**Current documented branch: R1Delta 3.0.5 stereo-camera/loadout test; separate weapon-direction candidate.**

## Installation

| Component | Download / source | Version / selection |
| --- | --- | --- |
| **R1Delta launcher** | [R1DeltaSetup.exe — direct download](https://github.com/r1delta/r1delta/releases/download/v3.0.5/R1DeltaSetup.exe) · [release page](https://github.com/r1delta/r1delta/releases/tag/v3.0.5) | R1Delta 3.0.5, matching the current documented VR candidate. |
| **VR test package** | [Request the matching package on Flat2VR](https://discord.gg/P4q9zt7ek) | Titanfall 1 VR stereo-camera/loadout test. The launcher installer above does not include this VR package. |

1. Download **R1DeltaSetup.exe 3.0.5** using the link above and install the community launcher. The upstream project is [r1delta/r1delta](https://github.com/r1delta/r1delta); [r1delta.net](https://r1delta.net/) links to the same launcher family.
2. Prepare your supported Titanfall 1 installation in R1Delta. Run the normal game once, then close it. Locate its **t1** game-data folder containing **bin**, **r1** and **vpk**.
3. Request the matching **Titanfall 1 VR / R1Delta 3.0.5** package in the game’s Flat2VR thread. The current documented camera/loadout candidate is a local experimental build, not a general community release.
4. Copy the complete **PUT_ME_IN_GAME_FOLDER** folder into **t1**, beside bin, r1 and vpk. Keep **RUN_TITANFALL_VR.bat** beside the package’s **TF1VR** folder. Use the game-data directory, not the R1Delta application directory.
5. Connect PC VR, select your OpenXR runtime and run **RUN_TITANFALL_VR.bat**. Keep its console open. First launch may download a pinned dependency once.
6. The original game menu opens. Follow the agreed local test scenario; the current candidate does not establish populated public-server compatibility. Controls are in **TF1VR/assets/controls/TOUCH_LAYOUT.json**.
7. After testing, send the newest session ZIP from **SEND_ME_TO_DISCORD** to the Flat2VR thread. If a session was interrupted, **RUN_TITANFALL_VR.bat --restore** restores the known original files.

Current test-package availability is coordinated in Discord. Use the complete package for your supported game build; this project page is separate from a release download.

## What this project brings to VR

- Stereo VR and head-tracked pilot/Titan camera work in the experimental branch.
- Controller-directed weapon aiming with native game weapon behavior.
- Dedicated work on native client/server shot-direction agreement.
- Latest controlled weapon-coverage checks exercised 16 weapon classes, including Titan weapons.

<details>
<summary><b>Controller quick reference</b></summary>

| Input | Action |
| --- | --- |
| Right trigger | Fire |
| A | Pilot: jump / double jump; Titan: dash |
| B | Crouch toggle |
| X tap / hold | Reload / use, hacking or embark; Titan hold: disembark |
| Y tap / hold | Cycle weapon / pick up weapon |
| Left trigger | Pilot: anti-Titan weapon; Titan: defensive ability / Vortex Shield |
| Left grip / right grip | Ordnance / tactical ability |
| Left stick click / right stick click | Melee / sprint |
| Right stick down tap | Pilot: call Titan / follow-guard; Titan: core ability |
| Right stick down hold 0.4 s, in Titan | Arm eject, then press X three times |
| Right stick up | Scoreboard |
| Left Menu tap / hold 0.4 s | Recenter / game menu |

The complete package control sheet takes precedence for its version and interaction profile.

</details>

## Current status

**Local test candidate.** The R1Delta 3.0.5 stereo-camera/loadout candidate passed local native-game/XR Sim pilot and Titan checks. It is a distinct candidate from the 16-weapon native-direction investigation.

- Latest aim-coverage tests do not establish physical-headset acceptance or populated public PvP compatibility.
- Server shot origin remains native/player-based in the latest coverage candidate. Full impact parity, every weapon and ability remain open.
- The SteamVR inversion report still needs physical-headset confirmation. Vortex uses a stock server origin; full positional left-hand shield physics is not finished.

Native shot prediction, cockpit behavior and broader weapon coverage are developed in separate controlled candidates.

[Detailed status and validation scope](docs/PROJECT_STATUS.md)

## Testing & feedback

Post in the game’s [Flat2VR thread](https://discord.gg/P4q9zt7ek) with your **mod version, game/store version, headset, OpenXR runtime, GPU, reproduction steps and the package’s diagnostic ZIP**. A short video is helpful for visual or handling problems.

## Other VR mods by Monsterdeadwood

| Game / project | Focus | Visibility |
| --- | --- | --- |
| [Assassin’s Creed VR](https://github.com/Monsterdeadwood/AC1VR) | First-person exploration, climbing and sword interaction | Private |
| [Crysis 2 VR](https://github.com/Monsterdeadwood/C2VR) | Nanosuit combat, physical interaction and spatial UI | Private |
| [NOVA · CS:GO Legacy VR](https://github.com/Monsterdeadwood/CSGOVR) | CS:GO Legacy local matches with motion controls | Private |
| [TimeShift VR](https://github.com/Monsterdeadwood/TimeShiftVR) | Time powers, nine weapons and roomscale posture | Private |
| [You Are Empty: Absolute Edition VR](https://github.com/Monsterdeadwood/YouAreEmptyAEVR) | Absolute Edition VR, weapons and hand interaction | Public |
| [Alone in the Dark 2008 VR](https://github.com/Monsterdeadwood/AloneInTheDark2008VR) | Survival-horror VR and held-item interaction | Public |
| [Rainbow Six Siege VR](https://github.com/Monsterdeadwood/SiegeVR) | Legacy Siege stereo and tracked weapon handling | Public |
| [Burnout Paradise Remastered VR](https://github.com/Monsterdeadwood/BUrnOutPvr) | Stereo driving, vehicle menus and native effects | Private |
| [Metro 2033 VR](https://github.com/Monsterdeadwood/Metro2033VR) | Original Metro VR and native physics experiments | Public |
| [Insurgency VR](https://github.com/Monsterdeadwood/InsurgencyVR) | Early VR integration research | Private |
| [Counter-Strike: Source VR](https://github.com/Monsterdeadwood/CSSVR) | Counter-Strike: Source VR development | Private |

Private repository links are available to invited collaborators. Public project pages are marked above.

## Credits & development notes

Project maintained by [Monsterdeadwood](https://github.com/Monsterdeadwood). This is an independent fan VR project; you need your own supported copy of the original game.

R1Delta platform credit: [R1Delta team](https://r1delta.net/).

[Previous repository overview, preserved as history](README_RESEARCH_ARCHIVE.md).

Documentation reviewed: **14 November 2026**.
