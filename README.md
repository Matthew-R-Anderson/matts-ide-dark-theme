# Matt's IDE Dark

A simple and clean dark-mode theme for VSCode style editors, with high contrast colours for text highlighting.

## Install (one click)
1. Open the Extensions view (`Cmd+Shift+X`).
2. Click the `...` menu (top-right of the panel) → **Install from VSIX...**.
3. Select `matts-ide-dark-<version>.vsix`.
4. Apply the theme: `Cmd+K Cmd+T` → choose **Matt's IDE Dark**.

No settings.json editing required, the custom find/selection colors are baked in.

## Build the VSIX

Requires [Node.js](https://nodejs.org) (provides `npx`).

```
npx @vscode/vsce package --no-dependencies --allow-missing-repository
```

Run from the repo root. This reads `package.json` and writes `matts-ide-dark-<version>.vsix`.
Bump the `version` in `package.json` before building a new release.
