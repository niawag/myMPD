---
layout: page
permalink: /
---

myMPD is a standalone and lightweight web-based MPD client. It's tuned for minimal resource usage and requires only very few dependencies. Therefore myMPD is ideal for raspberry pis and similar devices.

The backend ist written in C and has no dependencies to external databases or webservers. The configuration is stored in plain text files and all the data is pulled on demand from MPD. The MPD database is the only source of truth for myMPD.

The frontend is mobile friendly, written as a PWA and offers on all devices the same functionality. It communicates over AJAX and websockets using the json-rpc 2 protocol.

myMPD also integrates extended features like an advanced jukebox mode, timers and smart playlists. With the integrated lua interpreter myMPD functions can also be scripted.

![image](/assets/myMDPv6.0.0.gif)

## Features
- Control mpd functions (play, pause, etc.)
- Set mpd options (repeat, random, etc.)
- MPD mount and neighbors support
- MPD partition support
- MPD output attributes
- Browse mpd database by tags
- Albumart grid
- Browse filesystem
- Queue management
- Playlist management
- Advanced search
- Jukebox mode (add's random songs to queue)
- [Smart playlists and saved searches](https://github.com/jcorporation/myMPD/wiki/Smart-playlists)
- Play statistics and song voting
- [Local albumart support: embedded and image per folder](https://github.com/jcorporation/myMPD/wiki/Albumart)
- [Local lyrics (textfile per song or embedded)](https://github.com/jcorporation/myMPD/wiki/Lyrics)
- Local booklet support (per album folder)
- HTTP stream support
- Local playback of mpd http stream (html5 audio api)
- Timers and Triggers
- [System commands](https://github.com/jcorporation/myMPD/wiki/System-Commands)
- [Lua scripting](https://github.com/jcorporation/myMPD/wiki/Scripting)
- Scrobbler integration
- Embedded Webserver (mongoose)
- [Localized user interface](https://github.com/jcorporation/myMPD/wiki/Translating)
- Themeing
- [Publishing of mpd and myMPD directories via http and webdav](https://github.com/jcorporation/myMPD/wiki/Publishing-directories)
- Progressiv Web App enabled
- Support of Media Session API


myMPD is in active development. If you like myMPD, you can help to improve it (no programming skills are required).
- [Help to improve myMPD](https://github.com/jcorporation/myMPD/issues/167)

Wiki
----
For further information on installation and configuration, see the [myMPD wiki](https://github.com/jcorporation/myMPD/wiki).
