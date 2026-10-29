# tsugi

A personal anime tracker and launcher

This repository only hosts releases.

## Install

You need [Node.js](https://nodejs.org) 18 or newer (the Windows installer can set it up for you).

- **Windows:** download `install.ps1` from the latest release, right-click it → *Run with PowerShell*.
- **Linux / macOS:** download `install.sh` from the latest release and run `bash install.sh`.

The installer asks for an AniList client ID (create one at <https://anilist.co/settings/developer> with redirect URL `http://127.0.0.1:5173/auth/anilist`) and, optionally, a MyAnimeList client ID for MAL scores. Then open <http://127.0.0.1:5173>.

## Use

```
tsugi update     # get the latest release
tsugi start      # also: stop, restart, status, open
```
