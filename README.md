> [!IMPORTANT]
> **[TEST BUILDS & DISCUSSION · FLAT2VR DISCORD](https://discord.gg/P4q9zt7ek)**
> Testing, build requests, feedback and discussion happen in the **Flat2VR Modding Discord**. Join the server and find the **Titanfall 1 VR** thread.

![Titanfall 1 VR — Monsterdeadwood VR mods](assets/vr-banner.svg)

# Titanfall 1 VR

[English](README.md) · [Русский](README_RU.md) · [Flat2VR Discord](https://discord.gg/P4q9zt7ek) · [All projects](PORTFOLIO.md)

![Project status](assets/vr-status.svg)

A VR development branch for Titanfall 1 on supported R1Delta builds, combining stereo viewing, pilot weapon aiming and Titan cockpit work. Thanks to the [R1Delta team](https://r1delta.net/) for their community platform.

**Current documented branch: R1Delta VR development branch.**

## Installation

1. Get the matching **Titanfall 1 VR / R1Delta** test package in the game’s Flat2VR thread. Verify ordinary R1Delta launches correctly first.
2. Follow the supplied package layout: place the complete mod folder inside **t1**, beside **bin**, **r1** and **vpk**.
3. Connect PC VR, choose its OpenXR runtime and open **RUN_TITANFALL_VR.bat**. Keep the console open.
4. Use the package’s CONTROLS.txt and read its supported R1Delta/game-build requirements before testing.

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
| RUN_TITANFALL_VR.bat | Start the package |
| CONTROLS.txt in the package | Use the action map for that exact candidate |
| Ctrl+C in the launcher | Close the owned test session |

The complete package control sheet takes precedence for its version and interaction profile.

</details>

## Current status

**Experimental preview.** The native weapon-direction candidate was tested in the actual game with XR Sim and an owned private server, including pilot movement/jumps and 16 weapon classes.

- Latest aim-coverage tests do not establish physical-headset acceptance or populated public PvP compatibility.
- Server shot origin remains native/player-based in the latest coverage candidate. Full impact parity, every weapon and ability remain open.

Native shot prediction, cockpit behavior and broader weapon coverage are developed in separate controlled candidates.

[Detailed status and validation scope](docs/PROJECT_STATUS.md)

## Testing & feedback

Post in the game’s [Flat2VR thread](https://discord.gg/P4q9zt7ek) with your **mod version, game/store version, headset, OpenXR runtime, GPU, reproduction steps and the package’s diagnostic ZIP**. A short video is helpful for visual or handling problems.

## Other VR mods by Monsterdeadwood

| Game / project | Focus | Visibility |
| --- | --- | --- |
| [Battlefield 3 VR](https://github.com/Monsterdeadwood/BF3VR) | Campaign, tracked weapons and hands | Private |
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
