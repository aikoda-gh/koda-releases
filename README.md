# Koda Releases

Public binary distribution for **[Koda Desktop](https://koda.aikoda.dev)** — the autonomous engineering operator from [aiKODA](https://aikoda.dev).

> **Source code is private.** This repo only mirrors release binaries + checksums for direct download and electron-updater consumption.

## Latest release

The latest build is always at:

**https://github.com/aikoda-gh/koda-releases/releases/latest**

## Download

Visit https://koda.aikoda.dev for the gated landing page (email capture, then download), or grab the binary directly from the [Releases page](https://github.com/aikoda-gh/koda-releases/releases) above.

### Verify integrity

Each release publishes a `SHA256SUMS.txt` alongside the artifacts. Verify with:

```bash
# Linux / macOS / WSL
sha256sum -c SHA256SUMS.txt

# Windows PowerShell
Get-FileHash Koda-*-win-x64.zip -Algorithm SHA256
```

## Platforms

| Platform | Status |
|---|---|
| Windows x64 | ✅ alpha |
| macOS (Apple Silicon) | 🔜 |
| macOS (Intel) | 🔜 |
| Linux x64 | 🔜 |

## License

Koda is proprietary. © 2026 Carlos Mundim and aiKODA. See [LICENSE](https://aikoda.dev) for terms — by downloading you agree to use Koda only as permitted.

## Issues

If Koda crashes or misbehaves, file an issue here or contact `cmundim@solunai.co.jp`. Crash reports also flow automatically to our Sentry dashboard so we usually see them before you have to write them up.

— Tiger / aiKODA
