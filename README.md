<div align="center">
  <img
    src="https://raw.githubusercontent.com/cyberbuzzytb/AttendEaseStandalones/main/AttendEase%20bg%20rem.png"
    alt="AttendEase"
    width="150"
  />

  # AttendEase Standalones

  **Official Android and Windows companion releases for AttendEase**

  [![Latest Release](https://img.shields.io/badge/latest-v2.2.0-2785FE?style=for-the-badge)](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/latest)
  [![Android](https://img.shields.io/badge/platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases)
  [![Windows](https://img.shields.io/badge/companion-Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/tag/connect-v1.0.0)
  [![Main Project](https://img.shields.io/badge/main-AttendEase-0C1323?style=for-the-badge)](https://github.com/cyberbuzzytb/AttendEase)

  <br />

  [**Download AttendEase v2.2.0 APK**](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/download/v2.2.0/AttendEase-v2.2.0.apk)
  &nbsp;&nbsp;|&nbsp;&nbsp;
  [**Download AttendEase Connect v1.0.0**](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/download/connect-v1.0.0/AttendEase-Connect-Setup-1.0.0.exe)
</div>

---

## What Is This Repository?

This repository is the public download home for the AttendEase Android application and AttendEase Connect Windows companion.

The main AttendEase source code, web app, database migrations, and development history live in the [AttendEase repository](https://github.com/cyberbuzzytb/AttendEase). This repo keeps APK delivery separate, stable, and easy to share with selected Android testers.

## Latest Android Release

### AttendEase v2.2.0

- Added a complete Assets workspace for company computer registration and lifecycle management.
- Added live device health, readable last-seen information, onboarding checklists, and registration countdowns.
- Added guided asset replacement, retirement history, and reviewable hardware-change alerts.
- Added secure AttendEase Connect pairing and background device health support.
- Added private phone and WhatsApp contact completion.
- Improved responsive layouts, authorization, realtime refreshes, and version accuracy.

| Download | Version | Package |
| --- | --- | --- |
| [AttendEase-v2.2.0.apk](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/download/v2.2.0/AttendEase-v2.2.0.apk) | `2.2.0` | `com.cyberbuzzytb.attendease` |

**SHA-256:** `B990460D1400DD53E683F53325D3B3A0D92113C93A5BDB0B65BF2B297505FDE8`

## AttendEase Connect For Windows

AttendEase Connect securely introduces a physical Windows computer to the AttendEase Assets workspace. It creates a protected device identity, displays a short-lived registration QR, reports online health, and refreshes hardware inventory without replacing the permanent Asset ID.

- Starts quietly with Windows and continues from the notification area.
- Sends a lightweight health heartbeat every 30 seconds.
- Refreshes hardware and network inventory every 15 minutes.
- Checks for checksum-verified updates at startup and every six hours.
- Requires the user to confirm every Windows installer update.

| Download | Version | Platform |
| --- | --- | --- |
| [AttendEase-Connect-Setup-1.0.0.exe](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/download/connect-v1.0.0/AttendEase-Connect-Setup-1.0.0.exe) | `1.0.0` | Windows x64 |

**SHA-256:** `F4A76CF4F3F1540D6E81597672473669D5E864C30D4D45AA5939E8D44CE36D2E`

## Install On Android

1. Download the latest APK using the button above.
2. Open the downloaded file.
3. If Android asks, allow your browser or file manager to install unknown apps.
4. Review the installation prompt and tap **Install**.
5. Open AttendEase and sign in normally.

Android always asks the user to confirm installation. AttendEase does not silently install or replace apps.

## In-App Updates

AttendEase can check for newer Android releases from inside the app.

When an update is available:

1. AttendEase shows the installed and latest versions.
2. The user taps **Update Now**.
3. AttendEase downloads the APK from this repository's GitHub Release.
4. Android opens its installer for user confirmation.

The update manifest is served from:

```text
https://attendease-3cm3.onrender.com/app-update.json
```

The manifest points to the latest APK URL in this repository's releases, so the app always checks one stable update location.

AttendEase Connect uses its own verified installer manifest:

```text
https://attendease-3cm3.onrender.com/connect-update.json
```

## Who Should Install This?

Use this APK for AttendEase Android testers, admins, and employees who need stronger background notifications than a browser-only PWA can provide.

For iPhone users and users who do not need native Android notifications, the AttendEase web/PWA experience remains available at:

```text
https://attendease-3cm3.onrender.com
```

## Release Safety

- Download APKs and Windows installers only from this repository's [GitHub Releases](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases).
- Do not install files sent from unofficial mirrors or renamed third-party links.
- Updating preserves the installed app's AttendEase package identity.
- Android notification, location, and battery settings remain controlled by the device owner.

## Related Links

- [AttendEase Main Repository](https://github.com/cyberbuzzytb/AttendEase)
- [AttendEase Web App](https://attendease-3cm3.onrender.com)
- [All Android Releases](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases)
- [Report An Issue](https://github.com/cyberbuzzytb/AttendEase/issues)

---

<div align="center">
  <sub>AttendEase standalone releases are distributed directly through GitHub Releases.</sub>
</div>
