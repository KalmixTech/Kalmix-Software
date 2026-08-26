# Compatibility matrix

Compatibility statements apply only to the listed software, operating-system, receiver, firmware, interface, and test conditions.

| Trace | Test date | Windows | Receiver | Interface | Result | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| 1.5.7 | 2026-08-26 | Windows 11, 64-bit | KALMIX SCOUT PRO | COM17, 115200 baud | Verified | Serial opened; live NMEA displayed; 13 satellites and HDOP 1.8 observed; NTRIP/RTCM connected; RTK Float observed; transient network failure automatically reconnected. |

Additional receivers may work when they expose a Windows serial port, output supported NMEA sentences, and accept RTCM3 input. Submit a compatibility report with the exact receiver model, firmware, Windows version, interface, and observed result.

