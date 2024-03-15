# Source:Jeff Geerling's Blog, URL:https://www.jeffgeerling.com/blog.xml, language:en

## Raspberry Pi 5 *can* overclock to 3.14 GHz
 - [https://www.jeffgeerling.com/blog/2024/raspberry-pi-5-can-overclock-314-ghz](https://www.jeffgeerling.com/blog/2024/raspberry-pi-5-can-overclock-314-ghz)
 - RSS feed: https://www.jeffgeerling.com/blog.xml
 - date published: 2024-03-14T22:20:38+00:00

<span class="field field--name-title field--type-string field--label-hidden">Raspberry Pi 5 *can* overclock to 3.14 GHz</span>

            <div class="clearfix text-formatted field field--name-body field--type-text-with-summary field--label-hidden field__item"><p>...and it's not just for Pi Day.</p>

<p><img alt="Raspberry Pi 5 with THRML tower cooler" class="insert-image" height="auto" src="https://www.jeffgeerling.com/sites/default/files/images/pi-5-with-tower-cooler-thrml.jpg" width="700" /></p>

<p>After posting <a href="https://www.youtube.com/watch?v=WKrt1E5fxLg">my deep-dive into the Pi 5's new BCM2712 and RP1 silicon</a> this morning, someone linked me to this GitHub issue: <a href="https://github.com/raspberrypi/firmware/issues/1876">Raspberry Pi 5 cannot overclock beyond 3.0GHz due to firmware limit(?)</a>.</p>

<p>For the past few weeks, a few blog readers (most notably, tkaiser—thanks!) commented on PLLs, OPP tables, and DVFS and how something seemed a little off

## Die shots and transistor-level debugging on Raspberry Pi 5
 - [https://www.jeffgeerling.com/blog/2024/die-shots-and-transistor-level-debugging-on-raspberry-pi-5](https://www.jeffgeerling.com/blog/2024/die-shots-and-transistor-level-debugging-on-raspberry-pi-5)
 - RSS feed: https://www.jeffgeerling.com/blog.xml
 - date published: 2024-03-14T14:00:37+00:00

<span class="field field--name-title field--type-string field--label-hidden">Die shots and transistor-level debugging on Raspberry Pi 5</span>

            <div class="clearfix text-formatted field field--name-body field--type-text-with-summary field--label-hidden field__item"><p>Ever since I <a href="https://www.jeffgeerling.com/blog/2023/raspberry-pi-5-and-rp1-x-ray-scans">X-rayed the Raspberry Pi 5</a> to see inside the BCM2712 and RP1 chip packages, I've wanted <a href="https://en.wikipedia.org/wiki/Die_shot">die shots</a> of both chips. Why? Mostly out of curiosity, since I'm not a silicon expert by any means.</p>

<p>I also ran into some weird overclocking issues after writing about my experience <a href="https://www.jeffgeerling.com/blog/2023/overclocking-and-underclocking-raspberry-pi-5">overclocking and <em>underclocking</em> the Raspberry Pi 5</a>, and probably spent an unhealthy amount of time (and money) to learn about the clocks, PLLs, and chips on the latest ver

