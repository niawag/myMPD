---
layout: post
title: "myMPD"
date: 2019-12-16 09:26:00 -0100
categories: common
---

myMPD is a lightweight MPD web client that runs without a dedicated webserver or interpreter. 
It's tuned for minimal resource usage and requires only very few dependencies.

myMPD is a fork of ympd (https://github.com/notandy/ympd).
This fork provides a reworked ui based on Bootstrap 4, a modernized backend and many new features while having the same small footprint as ympd.

**Design principles:**
 - Keep it small and simple
 - Uses only mpd as source of truth
 - Mobile first UI
 - Keep security in mind

**Featurelist:**
 - Control mpd functions (play, pause, etc.)
 - Set mpd settings (repeat, random, etc.)
 - Browse mpd database by tags
 - Browse filesystem and playlists
 - Bookmarks for directories
 - Queue management
 - Playlist management
 - Advanced search (requires mpd >= 0.21.x and libmpdclient >= 2.17)
 - Jukebox mode (add's random songs / albums from database or playlists to queue)
 - AutoPlay - add song to (empty) queue and mpd starts playing
 - Smart playlists and saved searches
 - Play statistics and song voting (requires mpd stickers)
 - Local coverart support (Albums and Streams)
 - Support for embedded albumart (requires libmediainfo)
 - HTTP stream support
 - Local playback of mpd http stream (html5 audio api)
 - Progressiv Web App enabled
 - Embedded Webserver (mongoose)
 - Love message for scrobbling clients
 - Localized user interface

myMPD is work in progress. Feedback, bug reportes and feature requests are very welcome.
 - https://github.com/jcorporation/myMPD/issues
