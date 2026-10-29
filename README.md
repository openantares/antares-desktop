# Antares desktop downloads

Signed installers of the Antares desktop app and the update feed the installed
app reads (`latest.json` on the latest release).

- **macOS:** the notarized `.dmg` (universal: Apple silicon and Intel).
- **Windows:** the signed `*-setup.exe` installer.

Every update package is signed with the Antares release key; the app verifies
the signature before it installs an update, and refuses one that does not
match. `SHA256SUMS` on each release lists every published file.

This repository holds release files only. The app's source is not here.
