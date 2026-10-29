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

## Credits

Streaming links come from [Kuroiru](https://kuroiru.co). tsugi isn't affiliated with Kuroiru, and it's built to go easy on the site:

- Each show is looked up at most once a day, and the result is saved on your computer. If Kuroiru is down, tsugi keeps using the saved copy.
- Every request names itself (`tsugi/0.1`), so it's easy to spot.
- tsugi doesn't host or copy any videos. It only links to the sites that Kuroiru lists.

Thanks to Kuroiru for making this possible. If you run Kuroiru and want changes, or want tsugi to stop using the site, open an issue here and it'll be done.
