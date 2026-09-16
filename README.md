# Slogger — wearable data collection

Slogger is the data collection application developed for this group. It records
raw sensor data — accelerometer, gyroscope, heart rate and wear detection — on
the participant's device, and uploads completed files to the study server.

It has been built for two device platforms over time. The recording logic and
the server are the same across both.

| Version | Platform | Period | Source |
|---|---|---|---|
| Slog | Fitbit Sense | 2022–2023 | https://github.com/zfzhong/Slog |
| Slogger | Wear OS watches and Android tablets | 2024– | https://github.com/zfzhong/slogger |

The Fitbit version was built first and is named **Slog** in its source
repository; the Wear OS version was briefly called WearSlog and renamed Slogger
in January 2024. Both upload to the same file server:
https://github.com/zfzhong/slog-file-server

Documentation: [Slogger Manual](https://github.com/ACOI-UofSC/Slog_HR/blob/main/docs/slogger-manual.pdf)

---

## Source code

This repository holds the manual. The application source is in the
repositories linked above — use **Slog** for studies that collected on the
Fitbit Sense, and **Slogger** for Wear OS watches and Android tablets.
