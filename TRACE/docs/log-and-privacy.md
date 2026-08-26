# Logs and privacy

Trace can create three log types:

- NMEA text logs containing receiver output and timestamps.
- Raw RTCM3 correction logs.
- Application event logs containing connection and runtime events.

Application event logs use English technical messages in v1.5.7 and do not record correction server or mountpoint values. NMEA and RTCM data may still reveal location, timing, equipment behavior, or correction-service details.

Before attaching logs to a public GitHub Issue:

1. Make a copy of the original log.
2. Remove NTRIP usernames, passwords, tokens, private caster details, customer names, device serial numbers, and precise coordinates.
3. Trim the file to the shortest interval needed to reproduce the problem.
4. State whether the remaining position data is synthetic, rounded, or otherwise safe to publish.

Send sensitive evidence to service@kalmixtech.com only after support confirms an appropriate private transfer method.

