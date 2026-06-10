# scoop-bucket

[Scoop](https://scoop.sh) bucket for the [Sinew](https://github.com/sinew-mocap) mocap clusters (Windows).

```powershell
scoop bucket add sinew https://github.com/sinew-mocap/scoop-bucket
scoop install sinew-tui     # the slim driver (rebocap -> /sinew OSC + TUI)
```

Manifests point at the static `.exe` binaries published in each cluster's GitHub
release.  macOS/Linux users: see the Homebrew tap `sinew-mocap/homebrew-sinew`.
