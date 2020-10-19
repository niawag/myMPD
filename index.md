---
layout: page
permalink: /
---

myMPD is a standalone and lightweight web-based MPD client. It's tuned for minimal resource usage and requires only very few dependencies. Therefore myMPD is ideal for raspberry pis and similar devices.

![image](/assets/myMDPv6.7.0.gif)

The backend ist written in C and has no dependencies to external databases or webservers. The configuration is stored in plain text files and all the data is pulled on demand from MPD. The MPD database is the only source of truth for myMPD.

The frontend is mobile friendly, written as a PWA and offers on all devices the same functionality. It communicates over AJAX and websockets using the json-rpc 2 protocol.

myMPD also integrates extended features like an advanced jukebox mode, timers and smart playlists. With the integrated lua interpreter myMPD functions can also be scripted.

<a id="forkme_banner" href="https://github.com/jcorporation/myMPD">View on GitHub</a>
