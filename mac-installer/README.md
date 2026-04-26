# mac-installer

This folder is the separate macOS build track for the Offline AI Workstation.

It is intentionally isolated from the root website and Windows delivery files.

## What is here

- `src/` - standalone workstation app source
- `model-presets/` - bundled model preset JSON files
- `build-mac.sh` - macOS build script
- `MAC-BUILD.md` - local Mac build notes
- `BUILD-ON-GITHUB.md` - no-Mac cloud build instructions

## What is not here yet

Mac-native runtime assets are still optional and need to be added before a fully working release:

- `runtime-bin-mac/`
- `image-backend-bin-mac/`
- `ocr-bin-mac/`
- `assets/app.icns`

Without those folders, GitHub Actions can still build the app shell, but bundled runtime/OCR features will be unavailable on macOS.
