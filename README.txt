CrazyTVWorld — Final Artplayer Edition

Included playlists:
- Kids (287 entries)
- Comedy (215 entries)
- General (1,041 entries)
- Movies (527 entries)

The website merges duplicate name+URL entries into 2,057 unique channel entries and lets visitors filter by All, Kids, Comedy, General, or Movies. Search and channel playback stay on the same page.

Files:
- index.html — single-page website with Artplayer + HLS.js integration.
- all-channels.m3u — merged playlist for editing/importing elsewhere.

Run:
- For best results, deploy the folder to an HTTPS static host (e.g. Netlify) and open the site.
- Artplayer and HLS.js load from a CDN, so an internet connection is required.
- Some playlist entries use HTTP. Browsers can block HTTP video on an HTTPS site as mixed content; replace those with official HTTPS stream URLs where available.
- Some streams may be offline, region-restricted, blocked by CORS, or require permission from the broadcaster. Playlist inclusion does not establish permission to rebroadcast.
