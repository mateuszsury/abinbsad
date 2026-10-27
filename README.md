# Historical Wireless Security Experiments

This repository preserves early Python/MicroPython research scripts maintained
by Mateusz Sury. The historical repository name `abinbsad` is retained so existing
links keep working. The maintained, documented continuation is
[IoT Wireless Penetration Testing and Security Improvements](https://github.com/mateuszsury/IoT-Wireless-Penetration-Testing-Security-Improvements).

`src/` exposes the scripts originally distributed in `archive/kody.rar`, so their
changes can be reviewed directly. The original archive is retained as historical
material. The extracted ESP-NOW example has a corrected `try/except` indentation.

These are separate research experiments, not a single installable application.
Files using `network`/`espnow` require ESP32 MicroPython firmware; desktop network
experiments require their explicitly imported desktop dependencies and an
authorized, isolated lab. See the continuation's runtime guide for current setup.

CI parses the extracted sources without executing network experiments. No
production readiness, hardware support or defensive efficacy is claimed here.
Original source is MIT licensed; retain genuine third-party notices.

## Project overview

Inspectable historical Python experiments for IoT and network research.

![IoT research archive — Archive overview. Syntax validation does not reproduce the original network experiments.](docs/assets/presentation/overview.svg)

Archive overview. Syntax validation does not reproduce the original network experiments.
