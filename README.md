# Pylon Releases

Downloads and auto-update feed for **Pylon**, an open-source GUI for coding agents.

Grab the latest build from the [Releases page](https://github.com/pylon-code/pylon-releases/releases).

| Platform | File |
| --- | --- |
| macOS (Apple Silicon) | `Pylon-*-arm64.dmg` |
| macOS (Intel) | `Pylon-*-x64.dmg` |
| Linux | `Pylon-*.AppImage` |
| Windows | `Pylon-*.exe` |

Two channels are published. **Stable** releases are marked as the latest release.
**Nightly** builds are published as prereleases and carry a `-nightly.` version
suffix; the desktop app can follow either channel and updates itself in place.

## Why this repository exists

Pylon's desktop app checks for updates over the public GitHub API. This
repository hosts the release artifacts and the `latest*.yml` / `nightly*.yml`
update manifests that the updater reads, so installed apps can find new versions.

It holds no source code — only published builds. Issues and pull requests belong
on the main Pylon repository.
