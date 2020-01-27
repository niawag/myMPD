---
layout: posts
title: "MPD Partitions"
date: 2020-01-27 19:45:00 +0100
categories: mpd
---

MPD partitions are one of the new features of the upcoming MPD 0.22. The client library libmpdclient2 supports the new partition
commands since the 2.18 release. The ncmpc 0.37 release supports partitions also.

I think partitions are an absolutely killer feature and thats why myMPD will support it in the next myMPD 6.2.0 release.

**What is a MPD partition?**

A partition is one frontend of a multi-player MPD process: it has separate queue, player and outputs.
A client is assigned to one partition at a time.
