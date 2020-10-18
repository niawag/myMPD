---
layout: page
permalink: /mympdos
---

myMPDos is a Raspberry Pi image (aarch64) based on Alpine Linux. It is running entirely in RAM and it does not write to the sd-card unless you want to save settings. Therefore, myMPDos is very robust and you can simply turn off the power without any risk of corruption of your sd-card.

myMPDos is a turnkey music playback solution and is designed arround [MPD](https://www.musicpd.org/) and [myMPD](https://github.com/jcorporation/myMPD). After startup you can access the myMPD webinterface, copy music to the sd-card data partition, mount a music share or simply plugin an usb storage and you can start enjoying your music.

The initial configuration is done through a simple bootstrap file, that has sane default values preconfigured. Setting up myMPDos takes only a few minutes. Experts can use the advanced bootstrap file to customize the installation further.

<a id="forkme_banner" href="https://github.com/jcorporation/myMPDos">View on GitHub</a>