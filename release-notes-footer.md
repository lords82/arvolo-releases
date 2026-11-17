
---

### macOS: signed and notarized

The `.dmg` is signed with an Apple Developer ID (CryCatch S.r.l.)
and notarized by Apple — it opens like any other download.

### Windows: the .msi is unsigned

SmartScreen will say it protected your PC. Choose **More info**, then
**Run anyway**. The installer is not signed with a code-signing
certificate — a separate purchase from Apple's, and from a different
kind of authority.

The `.tar.gz` archives are the command-line tools (`arvolo`,
`arvolo-relay`) and are affected by neither.

### macOS: one download for every Mac

There is no separate Intel build to choose. Both the `.dmg` and the
macOS `.tar.gz` are universal — each binary inside carries both
architectures, so the same file runs on Apple Silicon and on Intel.
