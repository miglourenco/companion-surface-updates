# Companion Surface updates

Downloads and the update manifest for **Companion Surface**, the eMotion LV1 control-surface driver that lets Bitfocus Companion control a Waves LV1 over the network.

- **Installers:** see [Releases](https://github.com/miglourenco/companion-surface-updates/releases): `CompanionSurface-Setup.exe` (Windows) and `CompanionSurface-Setup.pkg` (macOS).
- **Online updates:** when the LV1 computer has internet, the driver reads [`latest.json`](latest.json) a minute after eMotion starts and every 6 hours. A newer version shows in the driver's settings window (eMotion > Controls > Companion Surface), with **Download and install**. The installer checks nothing by itself; the driver checks its SHA-256 first.
- **Installing an update closes eMotion LV1.** Start it again afterwards; nothing else changes. Not during a show.
