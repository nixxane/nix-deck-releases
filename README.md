# NIX Deck

A multi-account launcher for [OpenSRO](https://opensro.online/): run several accounts in one program,
each with its own login, with the [NIX bot](https://nixbot.lol/) built in, shared game files,
light mode for background accounts, chat, stats, a live map and Discord alerts.

This repository only hosts the downloads. **NIX Deck is in private beta and needs a beta key**:
ask on the [NIX Discord](https://discord.gg/Y5H5ZyfQ7u). One key works on one PC.

## Install

1. Download `NixDeck-x.y.z.zip` from the [latest release](../../releases/latest).
2. Extract the **whole** zip anywhere (for example `C:\Games\NixDeck`).
3. Start `NixDeck.exe` and enter your key once.

Nothing else to install: .NET and the Visual C++ runtime are included.

### "Windows protected your PC"

NIX Deck is not code-signed, so Windows SmartScreen may warn the first time you start a new version.
Click **More info → Run anyway**. Only do this for files downloaded from this page.

### Check your download

Each release lists the zip's SHA-256 checksum. In PowerShell:

```powershell
Get-FileHash .\NixDeck-0.1.0.zip -Algorithm SHA256
```

The result must match the checksum in the release notes.

## Updates

NIX Deck tells you when a new version is available (Help → Update available). Download the new
zip and extract it over the old folder, or into a new one: your accounts and settings are kept in
`%LOCALAPPDATA%\NixDeck`, not in the program folder.

---

