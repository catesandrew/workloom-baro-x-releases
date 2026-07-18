# workloom-baro-x-releases

![License](https://img.shields.io/github/license/catesandrew/workloom-baro-x-releases)
![Latest Release](https://img.shields.io/github/v/release/catesandrew/workloom-baro-x-releases)
![Downloads](https://img.shields.io/github/downloads/catesandrew/workloom-baro-x-releases/total)

Public release binaries + installer for the Workloom CLI (`wl`) and desktop app. Source lives in
the private `workloom-baro-x` repo — this repo exists only so the install script and prebuilt
binaries are reachable without a private-repo token.

Nothing here is hand-edited: `scripts/install.sh` and `docs/unsigned-builds.md` are synced, and
release assets are published, by `.github/workflows/release.yml` in the source repo on every `v*`
tag.

Install:

```bash
curl -fsSL https://raw.githubusercontent.com/catesandrew/workloom-baro-x-releases/main/scripts/install.sh | bash
```
