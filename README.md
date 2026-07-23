# Roll20 Chat Macro Generators

Multilingual GitHub Pages package containing:

- `discord.html` — Discord DM Macro Assembler v20
- `line.html` — LINE Message Macro Generator v5
- `cinematic.html` — Cinematic Card Generator v1
- `index.html` — multilingual launcher

## Languages

- Japanese
- Korean
- English
- Automatic browser-language detection

The initial language mode is **Browser language**. Japanese is used when the browser language is not Japanese, Korean, or English. The selected mode is saved under `r20MacroLanguageV1` and is shared across all pages on the same GitHub Pages origin.

## Deploy

Upload all files to the repository root, then configure:

- Settings → Pages
- Source: Deploy from a branch
- Branch: `main`
- Folder: `/(root)`
