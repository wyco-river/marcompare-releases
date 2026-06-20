# Marcompare releases

Public distribution channel for **Marcompare** (macOS legal-document comparison app).

- **`appcast.xml`** — the Sparkle auto-update feed. The app's `SUFeedURL` points at
  `https://raw.githubusercontent.com/LegalMarc/marcompare-releases/main/appcast.xml`.
- **Releases** — notarized `.dmg` builds are published as GitHub Releases on this repo;
  their download URLs are referenced from `appcast.xml`.

Source code lives in the private Marcompare repository. This repo carries only the
public update feed and signed release artifacts.
