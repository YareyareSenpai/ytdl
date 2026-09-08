# ytdl

A `yt-dlp` wrapper with an interactive `fzf` format picker, tuned for music downloads.

## Dependencies

- [`yt-dlp`](https://github.com/yt-dlp/yt-dlp)
- [`fzf`](https://github.com/junegunn/fzf)

## Install

```bash
sudo cp ytdl /usr/local/bin/ytdl
```

Downloads land in `~/Music/`. m4a is the default; hit Enter to grab it or scroll to pick any format in the list.

## Usage

ytdl <URL> # Single track — fzf picks format
ytdl <URL> -p # Full playlist
ytdl --help
