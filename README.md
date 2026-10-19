# ArtCraft portable Scoop bucket

Official Windows x64 portable releases from github.com/storytold, pinned and SHA-256 verified on 19 October 2026. Contains all 13 Craft apps and ArtCraft Launcher. No binaries were rebuilt or modified.

The manifests download directly from official GitHub releases, include Start menu shortcuts and command shims, and describe upstream version checks and automatic manifest updates. The bucket itself is local: `scoop update` cannot automatically publish new manifests into it. Future versions require refreshing these manifests (for example with Scoop's standard checkver tooling), committing the changes in this repository, then running `scoop update`.

Portable data folders are persisted for PhotoCraft, VectorCraft, FilmCraft, LightCraft, PdfCraft, EffectCraft, DesignCraft and the launcher. Other apps retain their upstream settings behavior, which may use your Windows user profile. Avoid the launcher's own install/update controls when managing the apps with Scoop.

Application code is upstream MIT OR Apache-2.0; bundled assets and ArtCraft trademarks retain their own terms. Keep the licenses, notices and attribution files provided in every portable archive.
