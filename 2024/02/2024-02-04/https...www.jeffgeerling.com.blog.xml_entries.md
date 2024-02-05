# Source:Jeff Geerling's Blog, URL:https://www.jeffgeerling.com/blog.xml, language:en

## Resolving 'Temporary failure in name resolution' on Pi OS 12 Bookworm
 - [https://www.jeffgeerling.com/blog/2024/resolving-temporary-failure-name-resolution-on-pi-os-12-bookworm](https://www.jeffgeerling.com/blog/2024/resolving-temporary-failure-name-resolution-on-pi-os-12-bookworm)
 - RSS feed: https://www.jeffgeerling.com/blog.xml
 - date published: 2024-02-04T03:51:21+00:00

<span class="field field--name-title field--type-string field--label-hidden">Resolving 'Temporary failure in name resolution' on Pi OS 12 Bookworm</span>

            <div class="clearfix text-formatted field field--name-body field--type-text-with-summary field--label-hidden field__item"><p>Raspberry Pi OS version 12 (based on Debian 12 Bookworm) uses NetworkManager instead of dhcpcd for managing network connections, DNS resolution settings, DHCP, etc.</p>

<p>I've already mentioned <a href="https://www.jeffgeerling.com/blog/2023/nmcli-wifi-on-raspberry-pi-os-12-bookworm">using <code>nmcli</code> and <code>nmtui</code> for managing WiFi settings</a>, but I ran into a strange issue after installing Docker on a fresh Raspberry Pi OS installation today. Suddenly DNS stopped working.</p>

<p>Trying to ping anything on the Internet gave me:</p>

<pre><code>$ ping www.google.com
ping: www.google.com: Temporary failure in name resolution
</code></pre>

<p>As always, <a href="https:/

