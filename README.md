# Robin Star Rail Codex Pet

Robin Star Rail is a free, open-source animated pet for Codex.

![Robin contact sheet](https://raw.githubusercontent.com/ybm1005/robin-star-rail-codex-pet/main/preview/contact-sheet.png?v=20260802-jumping-saturation-v2)

![Robin look directions](https://raw.githubusercontent.com/ybm1005/robin-star-rail-codex-pet/main/preview/look-directions.png?v=20260802-jumping-saturation-v2)

## 中文说明

Robin Star Rail 是一个免费、开源的 Codex 动态宠物。

安装方法：把 `pets/robin` 目录里的 `pet.json` 和 `spritesheet.webp` 复制到你的 Codex 宠物目录，然后重启 Codex 并选择 `Robin`。

### Windows PowerShell

```powershell
New-Item -ItemType Directory -Force "$env:USERPROFILE\.codex\pets\robin"
Copy-Item ".\pets\robin\*" "$env:USERPROFILE\.codex\pets\robin" -Force
```

### macOS / Linux

```bash
mkdir -p ~/.codex/pets/robin
cp pets/robin/* ~/.codex/pets/robin/
```

## English

Robin Star Rail is a Codex-compatible v2 animated pet. It includes the standard action rows and 16 look-direction cells.

## Install

Copy the pet files into your Codex pets directory, then restart Codex and select `Robin`.

### Windows PowerShell

```powershell
New-Item -ItemType Directory -Force "$env:USERPROFILE\.codex\pets\robin"
Copy-Item ".\pets\robin\*" "$env:USERPROFILE\.codex\pets\robin" -Force
```

### macOS / Linux

```bash
mkdir -p ~/.codex/pets/robin
cp pets/robin/* ~/.codex/pets/robin/
```

## Files

- `pets/robin/pet.json`
- `pets/robin/spritesheet.webp`
- `preview/contact-sheet.png`
- `preview/look-directions.png`
- `qa/validation-extended.json`

## Latest Sync

- Jumping saturation repair synced: `2026-08-02`
- Published spritesheet: `pets/robin/spritesheet.webp`
- Spritesheet SHA-256: `02D33FF1F7F752B28843BD261830422554DC900A04F61CC4AA0EA995BC3A90E7`
- Validation target: published WebP package
- Validation status: passed, no errors, no warnings

## Compatibility

- Codex pet sprite version: `2`
- Sprite sheet: `1536x2288`
- Cell size: `192x208`
- Layout: `8` columns by `11` rows

## Validation

This package includes the generated validation report at `qa/validation-extended.json`.

Current validation status: passed.

## License

The Robin Star Rail pet artwork and package files are licensed under Creative Commons Attribution 4.0 International.

This is an unofficial community pet and is not affiliated with OpenAI or any official Star Rail team.
