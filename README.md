# Pulzee — Legal

Public hosting for Pulzee (hit4F Games) legal pages.

- `privacy.html` — Privacy Policy (TR/EN)
- `terms.html` — Terms of Service (TR/EN)
- `delete-account.html` — Account deletion instructions (TR/EN)

## ⚠️ Do not edit here

These files are **generated copies**. The source of truth is the private
`dailyapp` repo under `docs/`. Edits made directly in this repo will be
overwritten on the next publish — change the source, then copy it across.

The app links to these pages at runtime (`apps/mobile/src/lib/legal.ts`), and
the Play Console "Data safety" form points at `delete-account.html`. A broken
or missing file here is a store-facing failure, not a cosmetic one.
