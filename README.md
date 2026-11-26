# Ataraxia – releases

Signed builds and the update feeds of the Ataraxia browser for macOS.

- **Install:** see [INSTALL.md](INSTALL.md) (beta: signed, not notarized; Apple silicon, macOS 26 or later).
- **Download:** [Releases](https://github.com/William0310/Ataraxia-Releases/releases). Each release has a DMG for manual installation and the archive the built-in updater uses.
- **Updates:** Ataraxia checks `https://william0310.github.io/Ataraxia-Releases/appcast.xml` (Sparkle 2). Updates and the feed itself are signed with Ataraxia's EdDSA key and verified before anything is installed.
- `staging/appcast.xml` is for testing release candidates and is never used by released builds.
- `ReleaseNotes/` holds the notes of each version.

Ataraxia is signed with an Apple Development certificate and is not notarized, so macOS asks for confirmation the first time a downloaded copy is opened.

The source code is not published here.
