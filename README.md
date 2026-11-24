# Roadworthy for Android

The native Android app for [Roadworthy](https://stayroadworthy.co.uk) — UK MOT history, DVLA road-tax status, a garage and service-history tracker, fuel and EV prices, Clean Air Zones, live traffic and MOT statistics.

This repository is the **public distribution point** for the signed Android app. It contains no source code: every release here is built and signed automatically from the private source repository.

![1795546761103](image/README/1795546761103.png)

## Install

### Direct download

1. Open [Releases](../../releases/latest).
2. Download `roadworthy-vX.Y.Z.apk`.
3. Optionally verify it against the `apk.sha256` asset:

   ```bash
   sha256sum roadworthy-vX.Y.Z.apk
   ```

4. Open the APK and allow installs from your browser or file manager when prompted.

Requires Android 7.0 (API 24) or newer. The APK is universal — the same file works on every supported device.

### Obtainium (automatic updates)

[Obtainium](https://github.com/ImranR98/Obtainium) tracks this repository and installs each new release for you:

1. Install Obtainium.
2. **Add App** → paste `https://github.com/Double77x/roadworthy-app`.
3. Install, and let Obtainium check for updates.

## What's inside

- MOT history, with MOT and road-tax reminders
- DVLA road-tax status and renewal dates
- Garage tracker with service history and spend charts
- Fuel prices, per-station price history and EV chargers
- Clean Air Zone checks and live traffic
- MOT statistics by model, age, mileage, fuel and engine
- Guides, and the same account and garage as the website

## Updates

- **In-app updates**: website-side fixes ship as signed bundles that install on the next launch.
- **Releases**: native changes arrive as a new GitHub release. The signing key never changes, so upgrades install in place over the previous version.
- **Version codes** increase strictly with every release; downgrades are never published.

## Privacy and security

Roadworthy's policies live on the site: [privacy](https://stayroadworthy.co.uk/information/privacy) · [terms](https://stayroadworthy.co.uk/information/terms) · [security](https://stayroadworthy.co.uk/information/security).

Feedback and bug reports: [stayroadworthy.co.uk/information/feature-request](https://stayroadworthy.co.uk/information/feature-request).

## Licence

Roadworthy is proprietary software. The APKs here are provided for personal use on devices you own; no source licence is granted and modified builds must not be redistributed. See [NOTICE.md](NOTICE.md).
