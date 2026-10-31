# GlyphFolio releases

The official distribution repository for GlyphFolio desktop installers and release notes.

**GlyphFolio 0.1.5 for Mac Apple Silicon is available.** Download the signed/notarized installer and SHA-256 checksums from [the current versioned release](https://github.com/glyphfolio/glyphfolio-releases/releases/tag/v0.1.5). Application source and signing keys are not distributed in this repository.

Visit [glyphfolio.com/download](https://glyphfolio.com/download) for availability.

## First release: Mac

| Platform | Architecture | Installer |
| --- | --- | --- |
| macOS 26 qualified | Apple Silicon | [0.1.5 .dmg](https://github.com/glyphfolio/glyphfolio-releases/releases/download/v0.1.5/GlyphFolio-0.1.5-macOS-Apple-Silicon.dmg) |
| macOS | Intel | Not yet available |

Windows 11 x64 (.exe) and Ubuntu 24.04 x64 (.deb/AppImage) are planned after the Mac public release. They remain unavailable until their own release checks pass. Windows ARM64 is not in the current scope. Additional operating-system requirements will be recorded with the qualified release rather than assumed here.

## Release safety

The owner approved the first Apple Silicon publication on 2026-10-30. Runtime qualification was performed on macOS 26.6.2; older macOS versions remain unverified. Intel, Windows and Linux must pass their own remaining checks before publication. There is no automatic publication workflow in this repository. Drafts and private qualification artifacts are not public releases.

Each approved release must include release notes, exact platform/architecture labels, and SHA-256 checksums. Checksums detect byte changes; they do not replace platform code signing or authenticated updater metadata.

This repository is not an automatic updater feed. Creating a GitHub release alone must not enable or redirect application updates.

See [RELEASE_POLICY.md](RELEASE_POLICY.md) for the publication checklist. No license to GlyphFolio application source is granted by this distribution repository.

Previous release [0.1.4](https://github.com/glyphfolio/glyphfolio-releases/releases/tag/v0.1.4) remains available with its original installers and checksums.
