# GlyphFolio releases

The official distribution repository for GlyphFolio desktop installers and release notes.

**No public downloads are available yet.** The first release is undergoing qualification. This repository contains release documentation only; it does not contain application source, development builds, signing keys, or installers.

Visit [glyphfolio.com/download](https://glyphfolio.com/download) for availability.

## First release: Mac

| Platform | Architecture | Installer |
| --- | --- | --- |
| macOS | Apple Silicon | .dmg |
| macOS | Intel | .dmg |

Windows 11 x64 (.exe) and Ubuntu 24.04 x64 (.deb/AppImage) are planned after the Mac public release. They remain unavailable until their own release checks pass. Windows ARM64 is not in the current scope. Additional operating-system requirements will be recorded with the qualified release rather than assumed here.

## Release safety

Installers will only appear after the remaining release checks pass and the owner approves publication. There is no automatic publication workflow in this repository. Drafts and private qualification artifacts are not public releases.

Each approved release must include release notes, exact platform/architecture labels, and SHA-256 checksums. Checksums detect byte changes; they do not replace platform code signing or authenticated updater metadata.

This repository is not an automatic updater feed. Creating a GitHub release alone must not enable or redirect application updates.

See [RELEASE_POLICY.md](RELEASE_POLICY.md) for the publication checklist. No license to GlyphFolio application source is granted by this distribution repository.
