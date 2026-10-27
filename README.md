<div align="center">

<img src="assets/terminal.svg" alt="AS terminal" width="100%" />

</div>

&nbsp;

## The Pitch

Python. Linux. Packaging. Scripts that save you an hour.
Nobody had a Linux build, so I made one and put it on six package formats.
I use Arch, btw.

## The Stack

<img src="https://skillicons.dev/icons?i=py,linux,bash,nix,git,githubactions&theme=dark" />

## The Main Move rn: [HaramMute-Linux](https://github.com/AS-Offical/HaramMute-Linux)

Linux build of the local server behind the HaramMute browser extension. Unofficial, no ties to the Windows devs.

```bash
curl -fsSL https://raw.githubusercontent.com/AS-Offical/HaramMute-Linux/main/install-release.sh | bash
```

The installer checks the file, picks the package for your distro, and installs it.

| distro | package |
|---|---|
| Debian / Ubuntu | `.deb` |
| Fedora 44 | `.rpm` |
| openSUSE Tumbleweed | `.rpm` |
| Arch | `.pkg.tar.zst` |
| NixOS | flake + package |
| any other glibc distro | AppImage |

91 commits. CI on the packages. Docs in Arabic and English. MIT.
x86_64 and CPU only, no ARM, no Alpine. It's all in the README.

[![CI](https://img.shields.io/github/actions/workflow/status/AS-Offical/HaramMute-Linux/linux-package-checks.yml?branch=main&label=CI&logo=github&logoColor=white&style=flat-square)](https://github.com/AS-Offical/HaramMute-Linux/actions/workflows/linux-package-checks.yml)
[![Release](https://img.shields.io/github/v/release/AS-Offical/HaramMute-Linux?style=flat-square&logo=github&logoColor=white&color=7c3aed)](https://github.com/AS-Offical/HaramMute-Linux/releases/latest)
![Stars](https://img.shields.io/github/stars/AS-Offical/HaramMute-Linux?style=flat-square&logo=github&color=black)

## After Dark

<img src="assets/bats.svg" alt="bats flying across a night sky" width="100%" />
