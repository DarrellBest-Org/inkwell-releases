# Inkwell releases

Installers and update feeds for **Inkwell**, a local-first AI fiction writing studio. The source is private; this repository only publishes builds.

## Download

Get the latest version from [Releases](https://github.com/DarrellBest-Org/inkwell-releases/releases/latest).

| Platform | File |
|---|---|
| Windows 10/11 | `Inkwell-Setup-<version>.exe` |
| macOS (Apple silicon and Intel) | `Inkwell-<version>-arm64.dmg` or `Inkwell-<version>.dmg` |
| Linux | `Inkwell-<version>-x86_64.AppImage` (make it executable, then run it) |

Inkwell updates itself from this repository. It downloads new versions in the background, checks each file against the SHA-512 in the release's update manifest, and installs when you choose **Restart to update** or the next time you quit.

Builds are not yet code-signed, so Windows SmartScreen and macOS Gatekeeper warn on first launch. On Windows choose **More info > Run anyway**. On macOS, right-click the app and choose **Open**.

## Report a bug or request a feature

In Inkwell, use **Help > Report a Bug** or **Help > Request a Feature**, or the feedback button next to Settings. Inkwell fills in the report and your version details, then opens GitHub so you can submit it from your account. From a terminal: `inkwell report bug "<title>" -m "<what happened>"`.

You can also [open an issue here](https://github.com/DarrellBest-Org/inkwell-releases/issues/new/choose). Issues are public, so leave out manuscript text you want to keep private.
