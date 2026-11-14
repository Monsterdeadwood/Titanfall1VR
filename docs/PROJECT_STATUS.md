# Titanfall 1 VR — project status

[← Project page](../README.md) · [Flat2VR testing & discussion](https://discord.gg/P4q9zt7ek)

Reviewed **14 November 2026**. Documented branch: **R1Delta 3.0.5 stereo-camera/loadout test; separate weapon-direction candidate**.

## What has been checked

- The R1Delta 3.0.5 stereo-camera/loadout candidate passed local native-game/XR Sim pilot and Titan checks. It is a distinct candidate from the 16-weapon native-direction investigation.
- The native weapon-direction candidate was tested in the actual game with XR Sim and an owned private server, including pilot movement/jumps and 16 weapon classes.

## Current limits

- Latest aim-coverage tests do not establish physical-headset acceptance or populated public PvP compatibility.
- Server shot origin remains native/player-based in the latest coverage candidate. Full impact parity, every weapon and ability remain open.
- The SteamVR inversion report still needs physical-headset confirmation. Vortex uses a stock server origin; full positional left-hand shield physics is not finished.

## Separate experimental work

- Native shot prediction, cockpit behavior and broader weapon coverage are developed in separate controlled candidates.

## Build access

Ask for the current complete test package in the game’s Flat2VR thread. A local build record does not by itself mean a file has been uploaded to this repository’s Releases.

## Documentation basis

This overview was reconciled against the project’s recorded package notes and validation records. The following names identify the records reviewed; they are not download links:

- `TITANFALL1VR_R1_305_CURRENT.json`
- `TITANFALL1VR_STEREO_TEST_20261111/READ_ME_FIRST.txt`
- `TF1VR/assets/controls/TOUCH_LAYOUT.json`
- `TF1VR_WEAPON_COVERAGE_20261111.txt`
- `tf1_weapon_coverage_20261111/QUALIFICATION.json`

Game execution, simulator validation and physical-headset feedback are reported separately above. Features from a separate experimental branch are identified explicitly.

## Кратко по-русски

VR-ветка Titanfall 1 для поддерживаемых сборок R1Delta: стереообзор, прицеливание пилота и работа с кабинами титанов. Спасибо команде [R1Delta](https://r1delta.net/) за общественную платформу.

- Последние проверки прицеливания не подтверждают принятие в физическом шлеме и совместимость публичного PvP с людьми.
- В последнем кандидате серверная точка выстрела остаётся штатной, от игрока. Совпадение конечных попаданий, всё оружие и способности ещё требуют проверки.
- Сообщение о перевороте SteamVR ещё требует подтверждения в физическом шлеме. Vortex использует штатную серверную точку; полная позиционная физика левого щита не завершена.
