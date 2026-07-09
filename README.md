# YouMind Shortcuts Data

Public text data packages for the YouMind Prompt Shortcuts Chrome extension.

## Manifest URL

```text
https://raw.githubusercontent.com/lucky-asd/youmind-shortcuts-data/main/manifest.json
```

Use this URL in the extension's remote sync mode.

## Contents

- `manifest.json`: package manifest and chunk index
- `categories.json`: category metadata
- `chunks/<source>/*.json.gz`: gzipped prompt shortcut chunks split by source and source id range
- `latest.json`: lightweight pointer to the latest manifest

This repository intentionally does **not** include cover image files. Each item keeps `thumbnailUrl` / `imageUrl`; the extension caches viewed covers locally in Chrome Cache Storage.

