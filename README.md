# E/TUBE for iPhone

Source project: **E-TUBE-iOS-Source.zip**. The manual GitHub Actions workflow unpacks the source and uses Xcode on a macOS runner to build an **unsigned** IPA. This repository contains no API key, Apple password or signing certificate.

## Build
Open **Actions → Build iPhone IPA → Run workflow**. After a successful run, download **E-TUBE-iPhone-unsigned** from the run's Artifacts. The IPA still needs legitimate signing before iPhone installation; publishing this public repository does not remove that requirement.

## Features and limits
- E/TUBE site inside a native iOS app, with its icon, navigation, refresh, share, Safari and AirPlay controls.
- iOS 17+, internet required.
- AirPlay video to CarPlay requires a compatible video-in-car vehicle while parked. A standalone CarPlay app requires Apple-approved entitlements; these are not claimed or enabled.
- This wrapper adds no native system-screen broadcast or background capture.
- Device behavior and the first macOS build are pending verification.

Unzip the source archive to inspect or build the XcodeGen project locally. Full setup details are in its README.md.
