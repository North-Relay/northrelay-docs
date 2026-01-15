# NorthRelay Documentation

This repository contains the public documentation for NorthRelay.

**Live Site:** [docs.northrelay.ca](https://docs.northrelay.ca)

---

## ⚠️ Do Not Edit Directly

This repository is **automatically synced** from [northrelay-platform](https://github.com/North-Relay/northrelay-platform).

All documentation edits should be made in the main platform repository:
- **Source:** `northrelay-platform/docs/public/`
- **Build:** `northrelay-platform/apps/docs/`

Changes pushed to the platform repo trigger an automatic build and sync to this repository.

## How It Works

```
northrelay-platform (private)
├── docs/public/           ← Edit markdown here
└── apps/docs/             ← Fumadocs builds static HTML
        ↓
    GitHub Actions
        ↓
northrelay-docs (public)   ← You are here
        ↓
    GitHub Pages
        ↓
docs.northrelay.ca         ← Live documentation
```

## License

Documentation content © 2026 NorthRelay. All rights reserved.
