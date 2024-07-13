# Source:Jeff Geerling's Blog, URL:https://www.jeffgeerling.com/blog.xml, language:en

## NUMA Emulation speeds up Pi 5 (and other improvements)
 - [https://www.jeffgeerling.com/blog/2024/numa-emulation-speeds-pi-5-and-other-improvements](https://www.jeffgeerling.com/blog/2024/numa-emulation-speeds-pi-5-and-other-improvements)
 - RSS feed: https://www.jeffgeerling.com/blog.xml
 - date published: 2024-07-12T14:01:15+00:00

<span class="field field--name-title field--type-string field--label-hidden">NUMA Emulation speeds up Pi 5 (and other improvements)</span>

            <div class="clearfix text-formatted field field--name-body field--type-text-with-summary field--label-hidden field__item"><p>Recently an Igalia engineer posted a <a href="https://lore.kernel.org/lkml/20240625125803.38038-1-tursulin@igalia.com/">NUMA Emulation patch</a> for the Pi 5 to the Linux Kernel mailing list. He said it could improve performance of Geekbench 6 scores up to 6% for single-core, and 18% for multicore.</p>

<p>My testing didn't quite match those numbers, but I did see a significant and consistent performance increase across both Geekbench 6:</p>

<p><img alt="Raspberry Pi 5 Geekbench 6 Score comparison with NUMA Emulation enabled" class="insert-image" height="auto" src="https://www.jeffgeerling.com/sites/default/files/images/pi-5-geekbench-numa-emulation-patch-faster.jpg" width="700" /></p>

<p>And High Performance L

