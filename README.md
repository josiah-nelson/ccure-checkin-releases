# CCURE Check-In downloads

Installer downloads for CCURE Check-In. This repository holds release files only.

**Latest installer:** https://github.com/josiah-nelson/ccure-checkin-releases/releases/latest/download/CcureCheckin.msi

Run it as an administrator on the C·CURE 9000 server. It installs a Windows Service; there is
no web site and IIS is not needed.

After installing:

- What setup did: `C:\Program Files (x86)\Tyco\CcureCheckin\logs\install.log`
- Service log: `C:\Program Files (x86)\Tyco\CcureCheckin\logs\ccure-checkin-<date>.log`
- Change settings: run `C:\Program Files (x86)\Tyco\CcureCheckin\server\CcureCheckinSettings.exe`
- Health: `http://localhost:5220/health` (on the server itself)

Versions before 1.1.0 were installed with `CcureCheckinSetup.exe`. Uninstall one of those from
Apps & features before installing 1.1.0 or later.

All versions: [Releases](https://github.com/josiah-nelson/ccure-checkin-releases/releases)
