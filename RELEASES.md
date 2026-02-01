# Releases (Canonical, Citable)

## Rule
Canonical content is considered stable only when shipped as a tagged release.

## Version format
- Major monthly: YYYY.MM (example: 2026.02)
- Patch: YYYY.MM.X (example: 2026.02.1)

## Release bundle
Each release should include:
- MANIFEST.json updated
- checksums in `integrity/CHECKSUMS.sha256`
- DOI placeholders (until minted)
- schema validation status (if you run CI)