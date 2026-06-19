# Endpoint Forge

Endpoint Forge is a portable endpoint build, remediation, offboarding, and runbook repository for IT professionals.

## Current version

v8.0.1

## Deployment

For GitHub Pages, copy the contents of this package to the repository root:

```text
index.html
README.md
CHANGELOG.md
docs/AGPL-COMPLIANCE-NOTES.md
samples/endpoint-forge-sample.eforge
```

The outer release ZIP is versioned, but deployable filenames are stable so updating the site is an overwrite operation.

## Storage model

Endpoint Forge v8 uses a portable `.eforge` project container. The container is currently a ZIP-based portable project file containing project data. It is not encrypted yet. Do not store real client secrets until encryption/login support is added.

## Save model

Browser autosave/recovery storage is intentionally not used in v8. Use the Save Project buttons after making changes. The top-right indicator shows Saved or Unsaved.
