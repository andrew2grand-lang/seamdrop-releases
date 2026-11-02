# SeamDrop releases

SeamDrop moves files and your clipboard between a Mac and a Windows PC on the same home network.

This repository holds only SeamDrop's release files: the installers, the update packages and `latest.json`, which the app reads to find updates. Every update package is signed, and SeamDrop refuses one whose signature doesn't match. The app's source code is not here.

## Download

Open **Releases** (right) and pick the latest:

- **Mac** (Apple Silicon and Intel): `SeamDrop_<version>_universal.dmg`
- **Windows 10 / 11** (x64): `SeamDrop_<version>_x64-setup.exe`

The other files (`.app.tar.gz`, `.sig`, `latest.json`) are for automatic updates; you don't need them.
