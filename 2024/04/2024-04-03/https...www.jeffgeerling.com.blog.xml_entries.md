# Source:Jeff Geerling's Blog, URL:https://www.jeffgeerling.com/blog.xml, language:en

## macOS Finder is still bad at network file copies
 - [https://www.jeffgeerling.com/blog/2024/macos-finder-still-bad-network-file-copies](https://www.jeffgeerling.com/blog/2024/macos-finder-still-bad-network-file-copies)
 - RSS feed: https://www.jeffgeerling.com/blog.xml
 - date published: 2024-04-03T21:56:51+00:00

<span class="field field--name-title field--type-string field--label-hidden">macOS Finder is still bad at network file copies</span>

            <div class="clearfix text-formatted field field--name-body field--type-text-with-summary field--label-hidden field__item"><p>In what is becoming a kind of hobby for me, I've just finished testing another tiny NAS—more on that tomorrow.</p>

<p>But as I was testing, I started getting frustrated with the fact I've never been able to get a Raspberry Pi—regardless of internal storage speeds, even with 800+ MB/sec PCIe-based storage—to consistently <em>write</em> more than around 100 MB/sec write speeds over the network, with either Samba or NFS.</p>

<p>NFS would be more consistent... but it ran around 82 MB/sec:</p>

<p><img alt="NFS file copy to Raspberry Pi 5 stalled at 80 MB per second" class="insert-image" height="auto" src="https://www.jeffgeerling.com/sites/default/files/images/nfs-file-copy-to-pi-5-macos.png" width="398" /></p>

<p>Samba

