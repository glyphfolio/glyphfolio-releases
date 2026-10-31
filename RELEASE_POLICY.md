# Publication policy

Status: **Apple Silicon 0.1.4 publication authorized2026-10-30. Other platforms remain unpublished.**

Do not upload development, migration, preview, local-signature, or qualification builds as public installers. Do not commit binary installers or credentials to Git history.

Before publishing a release:

1. Record the exact application source revision and clean build provenance.
2. Pass required correctness, security, data migration/recovery, plugin isolation, performance, and native operating-system acceptance checks for every advertised platform.
3. Resolve blocking dependency security findings; retain all intentionally unexecuted or deferred checks explicitly.
4. The owner narrowed the first public release to qualified macOS Apple Silicon. Physical Intel qualification remains pending; do not publish an Intel installer. macOS 26 is qualified; older macOS runtime behavior is explicitly unverified. Windows 11 x64 and Ubuntu 24.04 x64 follow later and must remain unavailable until independently qualified. Verify helper inclusion and exclusion of test fixtures and secret material.
5. Complete Developer ID signing/notarization for macOS and the approved Windows signing/distribution policy. Verify Linux package contents and installation behavior.
6. Verify each installer and generate SHA256SUMS from the actual final uploaded bytes. Retain platform signatures and release evidence.
7. Obtain final owner approval for public release. Preparation of this repository is not that approval.
8. Only then publish the reviewed release and activate the matching website download links. Do not route users to arbitrary latest assets or draft releases.

Native automatic updates require their own qualified artifact formats, authenticated metadata, anti-downgrade checks, and explicit feed activation. They must not use the old Electron feed or equate installer publication with updater qualification.

The initial website deliberately has disabled download controls. Changes to this policy or website must not silently convert failed or unexecuted checks into passing results.

Apple Silicon 0.1.5 was separately authorized and published on 2026-10-30 with the Sync and Save icon changes. The historic 0.1.4 release remains available; platform scope is unchanged.
