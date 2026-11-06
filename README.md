# Scrap for Mac — releases

This repository hosts only the release builds of **Scrap for Mac** and its update feed. Scrap's
source code is private and lives elsewhere.

- **Downloads:** each version's notarised `Scrap-<version>.zip` is attached to its
  [release](https://github.com/jaydenk/scrap-releases/releases).
- **Update feed:** Scrap checks `https://apps.jaydenkerr.net/scrap/appcast.xml`, which redirects
  to this repository's GitHub Pages copy of `appcast.xml`. Every update is signed with Scrap's
  own EdDSA key, and Scrap refuses one that isn't.
- **Support:** https://apps.jaydenkerr.net/scrap
