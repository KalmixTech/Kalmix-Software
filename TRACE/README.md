# KALMIX Trace

KALMIX Trace is a portable Windows GNSS serial monitor and NTRIP correction client. It opens a receiver COM port, displays live NMEA and receiver-reported solution status, forwards RTCM3 corrections, and records session logs.

## Current release

- Version: 1.5.7
- Platform: Windows desktop
- Architecture: x86 application; tested on 64-bit Windows 11
- Package: portable EXE; no traditional installer and no administrator privilege required to run the application
- License: proprietary; free to download and use
- Authenticode: not digitally signed

Download: [KALMIX Trace v1.5.7](https://github.com/KalmixTech/Kalmix-Software/releases/tag/trace-v1.5.7)

## Install with WinGet

On Windows, install the current release from the WinGet community repository:

```powershell
winget install --id KALMIX.Trace -e
```

The package installs as a portable app for the current user. No administrator privilege is required. After installation, start **KALMIX Trace** from the Start menu or run `kalmix-trace` in a new terminal session.

## Verify the download

Official WinGet/direct EXE:

`KALMIX.Trace.1.5.7.Windows.x86.exe`

SHA-256:

`F2005A3B2F56941A10DA652F2242022A26DD85B5A89799987AC5277AAB2861C8`

Manual ZIP package:

`KALMIX.Trace.1.5.7.Windows.x86.zip`

SHA-256:

`DE37CCC70A03A949A71077C4B4A42786EBC49C86AC924A887D09286FB1B67497`

This release is not Authenticode-signed. Windows SmartScreen may show an Unknown Publisher warning on some systems. Download only from the official KalmixTech organization or a link on kalmixtech.com, and verify the SHA-256 checksum before running. Do not disable Windows Defender or SmartScreen globally.

## Start using Trace

See [Quick start](docs/quick-start.md) and the full [TRACE for Windows User Guide](https://www.kalmixtech.com/blogs/doc-trace/trace-for-windows).

Trace is designed around the KALMIX SCOUT Series workflow and can also work with compatible receivers that expose a Windows serial port, output supported NMEA sentences, and accept RTCM3 corrections. Trace displays the solution state reported by the receiver; it does not calculate an RTK solution.

## Documentation

- [Quick start](docs/quick-start.md)
- [Known limits](docs/known-limits.md)
- [Logs and privacy](docs/log-and-privacy.md)
- [Compatibility matrix](docs/compatibility-matrix.md)
- [Changelog](CHANGELOG.md)
- [Software license notice](EULA.md)

For public bug reports and compatibility feedback, use GitHub Issues. For sensitive logs or account-related support, email service@kalmixtech.com.

