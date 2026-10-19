# ArtCraft portable Scoop bucket

Official Windows x64 portable releases from github.com/storytold, pinned and SHA-256 verified on 19 October 2026. Contains all 13 Craft apps and ArtCraft Launcher. No binaries were rebuilt or modified.

## Install

```powershell
scoop bucket add artcraft https://github.com/glubifedalt/artcraft-bucket
scoop install artcraft/photocraft
```

To install the complete suite, including the launcher:

```powershell
scoop import https://raw.githubusercontent.com/glubifedalt/artcraft-bucket/main/scoopfile.json
```

The manifests download directly from official GitHub releases and include Start menu shortcuts and command shims. Run `scoop update` followed by `scoop update <app>` to receive manifest versions published in this bucket. Upstream version checks and autoupdate rules are included for maintainers; new upstream versions require refreshing and committing the manifests before Scoop users receive them.

Portable data folders are persisted for PhotoCraft, VectorCraft, FilmCraft, LightCraft, PdfCraft, EffectCraft, DesignCraft and the launcher. Other apps retain their upstream settings behavior, which may use your Windows user profile. Avoid the launcher's own install/update controls when managing the apps with Scoop.

Application code is upstream MIT OR Apache-2.0; bundled assets and ArtCraft trademarks retain their own terms. Keep the licenses, notices and attribution files provided in every portable archive.
