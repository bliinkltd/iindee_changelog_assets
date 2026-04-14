# iindee Changelog Assets

Static image hosting for the **iindee UI Design Changelog** on Notion.

Screenshots captured from Figma during each `update changelog` run are stored here and referenced in Notion via `raw.githubusercontent.com` URLs.

## Structure

```
screenshots/
  YYYY-MM-DD/
    HHMM/
      <frame-slug>-truoc.png
      <frame-slug>-sau.png
```

- `YYYY-MM-DD/HHMM/` groups all images from one changelog run together.
- Filenames are ASCII-only (`truoc`, `sau`) to avoid URL-encoding issues.
- `<frame-slug>` is the Figma frame name lowercased with dashes.

## Raw URL format

```
https://raw.githubusercontent.com/bliinkltd/iindee_changelog_assets/main/screenshots/YYYY-MM-DD/HHMM/<filename>.png
```

## Related

- Main repo: https://github.com/<owner>/iindee (private)
- Changelog page: https://www.notion.so/UI-Design-Changelog-3420cd91e560800eae49db3a7022e3a8
