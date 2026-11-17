# CCURE Check-In downloads

Installer downloads for CCURE Check-In. This repository holds release files only.

**Latest installer:** https://github.com/josiah-nelson/ccure-checkin-releases/releases/latest/download/CcureCheckinSetup.exe

| File | Use it when |
|---|---|
| `CcureCheckinSetup.exe` | Normally. Enables IIS, installs URL Rewrite and Application Request Routing if they are missing, then installs CCURE Check-In. |
| `CcureCheckin-<version>.msi` | The server already has IIS, URL Rewrite and ARR, or your deployment tooling wants an MSI. |

Run the installer as an administrator on the C·CURE 9000 server. It records what it did in
`C:\Program Files (x86)\Tyco\CcureCheckin\logs\install.log`.

All versions: [Releases](https://github.com/josiah-nelson/ccure-checkin-releases/releases)
