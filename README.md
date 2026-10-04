<div align="center">
  <img
    src="https://raw.githubusercontent.com/cyberbuzzytb/AttendEaseStandalones/main/AttendEase%20bg%20rem.png"
    alt="AttendEase"
    width="150"
  />

  # AttendEase Standalones

  **Official Android and Windows companion releases for AttendEase**

  [![Latest Release](https://img.shields.io/badge/latest-v3.0.0-2785FE?style=for-the-badge)](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/latest)
  [![Android](https://img.shields.io/badge/platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases)
  [![Windows](https://img.shields.io/badge/companion-Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/tag/connect-v1.0.1)
  [![Main Project](https://img.shields.io/badge/main-AttendEase-0C1323?style=for-the-badge)](https://github.com/cyberbuzzytb/AttendEase)

  <br />

  [**Download AttendEase v3.0.0 APK**](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/download/v3.0.0/AttendEase-v3.0.0.apk)
  &nbsp;&nbsp;|&nbsp;&nbsp;
  [**Download AttendEase Connect v1.0.1**](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/download/connect-v1.0.1/AttendEase-Connect-Setup-1.0.1.exe)
</div>

---

## What Is This Repository?

This repository is the public download home for the AttendEase Android application and AttendEase Connect Windows companion.

The main AttendEase source code, web app, database migrations, and development history live in the [AttendEase repository](https://github.com/cyberbuzzytb/AttendEase). This repo keeps APK delivery separate, stable, and easy to share with selected Android testers.

## Latest Android Release

### AttendEase v3.0.0

- Added employee leave requests, administrator reviews, private evidence, decisions, and history.
- Fixed Leave and Leave Management navigation and added complete Leave details to Telegram and branded Gmail notifications.
- Added the live Work Calendar to employee views and made approved leave consistent across reports and reminders.
- Improved offline behavior while keeping attendance and approval mutations online-only.
- Added administrator-requested PC inventory refresh and 15-minute Connect health heartbeats.
- Strengthened employee role, approval, company, access, and employment-status protection.

| Download | Version | Build | Package |
| --- | --- | --- | --- |
| [AttendEase-v3.0.0.apk](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/download/v3.0.0/AttendEase-v3.0.0.apk) | `3.0.0` | `302` | `com.cyberbuzzytb.attendease` |

**SHA-256:** `B2BA6250BCB69E35B281511F535A9460791528D0DC0301D41971D04EB8C3E287`

## AttendEase Connect For Windows

AttendEase Connect securely introduces a physical Windows computer to the AttendEase Assets workspace. It creates a protected device identity, displays a short-lived registration QR, reports online health, and refreshes hardware inventory without replacing the permanent Asset ID.

- Starts quietly with Windows and continues from the notification area.
- Sends a lightweight health heartbeat every 15 minutes after registration.
- Refreshes hardware and network inventory at startup or on administrator request.
- Checks for checksum-verified updates at startup and every six hours.
- Requires the user to confirm every Windows installer update.

| Download | Version | Platform |
| --- | --- | --- |
| [AttendEase-Connect-Setup-1.0.1.exe](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/download/connect-v1.0.1/AttendEase-Connect-Setup-1.0.1.exe) | `1.0.1` | Windows x64 |

**SHA-256:** `D544706C86912315E2B4D63A6CAAF605DB854D340CD87A21D3C79B208BA6CD5F`

Version 1.0.1 adds a clearer animated onboarding flow, fixes premature broken QR placeholders, and improves registration, connection, and device-status feedback.

### Connect 3.0.0

[Download the unsigned Connect 3.0.0 installer](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/download/connect-v3.0.0/AttendEase-Connect-Setup-3.0.0.exe). Windows may show **Unknown publisher** because the installer is not code-signed.

**SHA-256:** `B756A55142181EE8497534EB912614B264B4694DDEA3A34CC2D47EBA47DAE44B`

Connect 3.0.0 keeps legacy registration compatibility while adding 15-minute lightweight heartbeats, startup/on-demand inventory refresh, improved Windows startup verification, and safer retry behavior.

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
