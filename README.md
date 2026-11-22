# SeamDrop releases

SeamDrop moves files and your clipboard between your computers, Macs and Windows PCs, on the same home network.

This repository holds only SeamDrop's release files: the installers, the update packages, `latest.json` (which the app reads to find updates) and `beta.json` (the same for test builds). Every update package is signed, and SeamDrop refuses one whose signature doesn't match. The source code is at https://github.com/andrew2grand-lang/portal.

## Download

Open **Releases** (right) and pick the latest. Test builds are marked **Pre-release**.

- **Mac** (Apple Silicon and Intel): `SeamDrop_<version>_universal.dmg`
- **Windows 10 / 11** (x64): `SeamDrop_<version>_x64-setup.exe`

The other files (`.app.tar.gz`, `.sig`, `latest.json`, `beta.json`) are for automatic updates; you don't need them.
