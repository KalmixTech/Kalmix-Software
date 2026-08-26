# KALMIX Trace quick start

## 1. Download and verify

Download the version-specific EXE or ZIP from the official [Trace v1.5.7 release](https://github.com/KalmixTech/Kalmix-Software/releases/tag/trace-v1.5.7). Compare its SHA-256 checksum with the value published in the release.

## 2. Start the application

Run `KALMIX Trace.exe`. Trace is portable and does not require a traditional installation or administrator privileges.

## 3. Open the receiver stream

1. Connect the GNSS receiver to Windows.
2. Select its COM port and baud rate.
3. Select **Open serial port**.
4. Confirm that live NMEA data and the NMEA rate are updating.

## 4. Connect corrections

1. Enter the NTRIP caster, port, mountpoint, username, and password supplied by the correction service.
2. Keep periodic terminal GGA enabled when required by the service.
3. Select **Connect correction service**.
4. Confirm that the RTCM rate increases and that corrections are forwarded to the receiver.

Trace displays the solution state reported by the connected receiver. It does not calculate the RTK solution.

## 5. Review logs

Settings are stored at `%LOCALAPPDATA%\KALMIX\Trace\KALMIX Trace.config.xml`. Logs are stored by default in `%LOCALAPPDATA%\KALMIX\Trace\Logs`.

Before sharing a log publicly, follow [Logs and privacy](log-and-privacy.md).

