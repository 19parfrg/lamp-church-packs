# lamp-church-packs

Downloadable sermon-content packs for [Lamp](https://19parfrg.github.io/lamp/)'s
church editions. Each pack pairs a `church.sqlite` (sermon metadata, transcript
chunks with timestamps, full-text index) with a `chunks.bin` (embedding index).

- Pack binaries live on **GitHub Releases** (tag: `<church-code>-<version>`),
  so old versions never bloat this repo's history.
- `manifest.json` on `main` is what the app polls: per church, the latest
  version, download URLs, byte sizes, and SHA-256 checksums.

Packs are built by `tools/churchpack/` in the Lamp repo. All sermon content
belongs to the churches that preached it and is redistributed with their
blessing; the sources are their public websites, podcast feeds, and channels.
