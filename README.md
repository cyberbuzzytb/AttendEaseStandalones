<div align="center">
  <img
    src="https://raw.githubusercontent.com/cyberbuzzytb/AttendEaseStandalones/main/AttendEase%20bg%20rem.png"
    alt="AttendEase"
    width="150"
  />

  # AttendEase Standalones

  **Official standalone Android releases for AttendEase**

  [![Latest Release](https://img.shields.io/badge/latest-v2.0.9-2785FE?style=for-the-badge)](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/latest)
  [![Android](https://img.shields.io/badge/platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases)
  [![Main Project](https://img.shields.io/badge/main-AttendEase-0C1323?style=for-the-badge)](https://github.com/cyberbuzzytb/AttendEase)

  <br />

  [**Download AttendEase v2.0.9 APK**](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/download/v2.0.9/AttendEase-v2.0.9.apk)
</div>

---

## What Is This Repository?

This repository is the public download home for AttendEase standalone Android builds.

The main AttendEase source code, web app, database migrations, and development history live in the [AttendEase repository](https://github.com/cyberbuzzytb/AttendEase). This repo keeps APK delivery separate, stable, and easy to share with selected Android testers.

## Latest Android Release

### AttendEase v2.0.9

- Added hybrid Google sign-in routing: website and PWA logins return to the website, while Android APK logins return directly to the app.
- Added Android deep-link handling for Supabase OAuth callbacks.
- Improved Android report printing and Save as PDF through the native Android print screen.
- Improved report rendering so summary tables fit better on desktop, mobile, and printable PDF layouts.
- Cleaned report date ranges and metadata formatting for clearer exported attendance reports.
- Added extra Android auth callback safeguards to avoid duplicate callback handling.

| Download | Version | Package |
| --- | --- | --- |
| [AttendEase-v2.0.9.apk](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases/download/v2.0.9/AttendEase-v2.0.9.apk) | `2.0.9` | `com.cyberbuzzytb.attendease` |

**SHA256**

```text
204DCEEA3358443726EBA5815303FF03B0545C8DDB683D7A3A2D7B3DA6CA0C83
```

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

## Who Should Install This?

Use this APK for AttendEase Android testers, admins, and employees who need stronger background notifications than a browser-only PWA can provide.

For iPhone users and users who do not need native Android notifications, the AttendEase web/PWA experience remains available at:

```text
https://attendease-3cm3.onrender.com
```

## Release Safety

- Download APKs only from this repository's [GitHub Releases](https://github.com/cyberbuzzytb/AttendEaseStandalones/releases).
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
