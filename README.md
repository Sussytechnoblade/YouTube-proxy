# Playroom

A simple, responsive site for watching YouTube videos without the extra clutter.
The page's styles and playback logic are all contained in `youtube.html`.

## Run locally

Serve this folder over HTTP (don't open the HTML file directly, because YouTube's
player needs a web origin). For example:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000/youtube.html`.

Paste a YouTube video URL, Shorts link, playlist URL, or 11-character video ID
into the input to play it. Playback uses YouTube's privacy-enhanced embedded
player, so videos that don't allow embedding must be watched on YouTube.
