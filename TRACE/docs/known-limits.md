# Known limits

- Trace v1.5.7 is a portable x86 Windows desktop application built on .NET Framework 4.0.
- The v1.5.7 release is not Authenticode-signed. SmartScreen behavior can vary by system reputation and organization policy.
- Release acceptance was completed on 64-bit Windows 11. Windows 10 is a target platform but was not part of the recorded v1.5.7 acceptance run.
- Third-party receiver compatibility depends on a usable Windows serial port, supported NMEA output, and RTCM3 correction input. Compatibility is not implied for every receiver or firmware.
- Trace reports the solution state supplied by the receiver; it does not calculate RTK, replace receiver firmware, or certify positioning accuracy.
- Trace does not provide terminal command sending, receiver configuration writing, steering control, or PANDA validation.
- Password protection uses Windows DPAPI for the current Windows user. A password encrypted under one Windows account cannot be decrypted by another account.
- WinGet installation creates and manages a portable-app entry; user settings and logs remain in LocalAppData when the package is removed unless the user deletes them separately.

