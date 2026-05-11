# GitKB Desktop Releases

Public release mirror for GitKB Desktop.

The private `gitkb/harmony-desktop` repository builds the macOS Desktop DMG, creates a private release, and dispatches `child-release-created` to this repository. This repository downloads the private release assets and republishes them as public GitHub Release assets.

Expected public assets:

- `GitKB_universal.dmg`
- `GitKB_universal.dmg.sha256`
- `checksums.txt`

GitKB Desktop is free to download and use locally. The first public macOS builds are labeled public beta and require the external `git-kb` CLI.
