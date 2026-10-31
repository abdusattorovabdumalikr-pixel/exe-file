# Hotiralar muzeyi

Windows desktop application built with Electron.

## Run locally

```bash
npm install
npm start
```

## Build Windows installer

```bash
npm install
npm run dist:win
```

The installer is created in `dist/`. The build command uses `--publish never`, so GitHub Actions does not require a `GH_TOKEN` or GitHub release configuration.

## Build on GitHub

1. Upload the **contents of this folder** to the root of a GitHub repository (the `.github` folder must be at the repository root).
2. Open the repository's **Actions** tab.
3. Run **Build Windows EXE** or push to `main` / `master`.
4. Download `Hotiralar-muzeyi-Windows-Installer` from the completed workflow's **Artifacts** section.
