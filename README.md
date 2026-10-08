<div align="center">
  <img
    src="https://raw.githubusercontent.com/cyberbuzzytb/AttendEaseStandalones/main/AttendEase%20bg%20rem.png"
    alt="AttendEase"
    width="150"
  />

  # AttendEase Standalones

  **Official Android and Windows companion releases for AttendEase**

  [![Latest Release](https://img.shields.io/badge/latest-v3.1.0-2785FE?style=for-the-badge)](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/latest)
  [![Android](https://img.shields.io/badge/platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases)
  [![Windows](https://img.shields.io/badge/companion-Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/tag/connect-v3.0.2)
  [![Main Project](https://img.shields.io/badge/main-AttendEase-0C1323?style=for-the-badge)](https://github.com/cyberbuzzytb/AttendEase)

  <br />

  [**Download AttendEase v3.1.0 APK**](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/download/v3.1.0/AttendEase-v3.1.0.apk)
  &nbsp;&nbsp;|&nbsp;&nbsp;
  [**Download AttendEase Connect v3.0.2**](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/download/connect-v3.0.2/AttendEase-Connect-Setup-3.0.2.exe)
</div>

---

## What Is This Repository?

This repository is the public download home for the AttendEase Android application and AttendEase Connect Windows companion.

The main AttendEase source code, web app, database migrations, and development history live in the [AttendEase repository](https://github.com/cyberbuzzytb/AttendEase). This repo keeps APK delivery separate, stable, and easy to share with selected Android testers.

## Latest Android Release

### AttendEase v3.1.0

- Adds First-Half and Second-Half Leave with clear combined leave and attendance states.
- Warns before GPS or QR attendance during a leave-covered period while preserving approved Leave.
- Improves the Android home, attendance, Connect, Assets, Profile, Settings, forms, and responsive layouts.
- Includes current Asset Management, Employee Connect Sessions, contact information, notifications, and reporting updates.
- Preserves online-only attendance mutations and the existing security and retention boundaries.

| Download | Version | Build | Package |
| --- | --- | --- | --- |
| [AttendEase-v3.1.0.apk](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/download/v3.1.0/AttendEase-v3.1.0.apk) | `3.1.0` | `310` | `com.cyberbuzzytb.attendease` |

**SHA-256:** `F2C14BCE1ACA3128DBE6B5284B7FF1A87A776F482FCE10E6F611282DE4390747`

## AttendEase Connect For Windows

AttendEase Connect securely introduces a physical Windows computer to the AttendEase Assets workspace. It creates a protected device identity, displays a short-lived registration QR, reports online health, and refreshes hardware inventory without replacing the permanent Asset ID.

- Starts quietly with Windows and continues from the notification area.
- Sends a lightweight health heartbeat every 15 minutes after registration.
- Refreshes hardware and network inventory at startup or on administrator request.
- Checks for checksum-verified updates at startup and every six hours.
- Requires the user to confirm every Windows installer update.

| Download | Version | Platform |
| --- | --- | --- |
| [AttendEase-Connect-Setup-3.0.2.exe](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/download/connect-v3.0.2/AttendEase-Connect-Setup-3.0.2.exe) | `3.0.2` | Windows x64 |

**SHA-256:** `E46261AB9AEC4765FC752B6CF69816793A79F40D9B42A2DA589994596ADAA32B`

Version 3.0.2 adds bounded diagnostics, explainable health and compliance checks, typed remote actions, update awareness, maintenance mode, failure reporting, and service-history integration while retaining the 15-minute heartbeat behavior.

### Connect 3.0.2

[Download the unsigned Connect 3.0.2 installer](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/download/connect-v3.0.2/AttendEase-Connect-Setup-3.0.2.exe). Windows may show **Unknown publisher** because the installer is not code-signed.

**SHA-256:** `E46261AB9AEC4765FC752B6CF69816793A79F40D9B42A2DA589994596ADAA32B`

Connect 3.0.2 keeps legacy registration compatibility while adding privacy-bounded diagnostics, typed command acknowledgements, maintenance and recovery controls, peripheral inventory, and authoritative combined leave/attendance display. It does not add arbitrary shell access, forced PC restart, surveillance, or an active offline-attendance producer.

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
