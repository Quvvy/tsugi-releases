# tsugi

A local anime tracker and launcher

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

Streaming links are sourced from Kuroiru. tsugi is an independent project and is not affiliated with Kuroiru. It's designed to minimize requests to the site:

- Each show is looked up at most once per day, with results cached locally on your computer.

- Cached results are reused between lookups, including when Kuroiru is unavailable.

- Every request identifies itself with tsugi/0.1 for easy identification.

- tsugi does not host, download, or redistribute videos. It only provides links to sources listed by Kuroiru.

Thanks to Kuroiru for making this possible. If you're affiliated with Kuroiru and have concerns, suggestions, or would like tsugi to stop accessing the site, please open an issue on this repository. I'll be happy to address them.
