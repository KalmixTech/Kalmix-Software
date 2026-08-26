# KALMIX Trace changelog

## 1.5.7 — 2026-08-26

### Changed

- Store settings and logs under the current user's LocalAppData directory.
- Protect the saved NTRIP password with Windows DPAPI for the current Windows user.
- Use English technical messages in application event log files regardless of interface language.
- Show categorized dialogs for correction account rejection, missing mountpoints, timeouts, invalid responses, and network failures.
- Stop automatic retries for account, mountpoint, and server-rejection configuration errors while retaining reconnect behavior for transient network failures.
- Remove correction server and mountpoint values from application log files.
- Update application, file, and product version to 1.5.7.

### Unchanged

- Serial NMEA monitoring and receiver-reported positioning status.
- NTRIP connection, GGA sending, RTCM3 forwarding, and transient-failure reconnection.
- NMEA, RTCM3, and application logging.
- Skyplot and scatter views.

This release does not add terminal command sending or PANDA validation.

