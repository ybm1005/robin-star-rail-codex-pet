# Publishing Checklist

## Local Package

- [x] `pets/robin/pet.json` exists.
- [x] `pets/robin/spritesheet.webp` exists.
- [x] Preview image exists at `preview/contact-sheet.png`.
- [x] Direction preview exists at `preview/look-directions.png`.
- [x] Validation report exists at `qa/validation-extended.json`.
- [x] README image URLs include the `20260801-color-loss-fix` cache-busting version.
- [x] Generated build folders are ignored by `.gitignore`.

## Review

- [x] `pet.json` uses `spriteVersionNumber: 2`.
- [x] `pet.json` references `spritesheet.webp`.
- [x] Validation report has `ok: true`.
- [x] Validation report targets the published WebP package.
- [x] Validation report has no errors.
- [x] Validation report has no warnings.

## Before GitHub Publish

- [x] Confirm the public repository name: `robin-star-rail-codex-pet`.
- [x] Confirm the license choice: CC BY 4.0.
- [x] Confirm the GitHub account or organization: `YBM1005`.
- [x] Create the GitHub repository.
- [x] Push the local repository to GitHub.
- [ ] Create the first release, recommended tag: `v1.0.0`.
