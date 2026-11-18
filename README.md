# CCURE Check-In downloads

Installer downloads for CCURE Check-In. This repository holds release files only.

**Latest installer:** https://github.com/josiah-nelson/ccure-checkin-releases/releases/latest/download/CcureCheckinSetup.exe

Run it as an administrator on the C·CURE 9000 server. It installs a Windows Service; there is
no web site and IIS is not needed. Running it over an earlier version upgrades it.

The same installer is also published as `CcureCheckin.msi`, for deployment tooling that wants
an MSI.

After installing:

- What setup did: `C:\Program Files (x86)\Tyco\CcureCheckin\logs\install.log`
- Service log: `C:\Program Files (x86)\Tyco\CcureCheckin\logs\ccure-checkin-<date>.log`
- Change settings: run `C:\Program Files (x86)\Tyco\CcureCheckin\server\CcureCheckinSettings.exe`
- Health: `http://localhost:5220/health` (on the server itself)

All versions: [Releases](https://github.com/josiah-nelson/ccure-checkin-releases/releases)
