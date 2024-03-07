# Source:Jeff Geerling's Blog, URL:https://www.jeffgeerling.com/blog.xml, language:en

## Set a static IP address with nmtui on Raspberry Pi OS 12 'Bookworm'
 - [https://www.jeffgeerling.com/blog/2024/set-static-ip-address-nmtui-on-raspberry-pi-os-12-bookworm](https://www.jeffgeerling.com/blog/2024/set-static-ip-address-nmtui-on-raspberry-pi-os-12-bookworm)
 - RSS feed: https://www.jeffgeerling.com/blog.xml
 - date published: 2024-03-06T23:24:33+00:00

<span class="field field--name-title field--type-string field--label-hidden">Set a static IP address with nmtui on Raspberry Pi OS 12 'Bookworm'</span>

            <div class="clearfix text-formatted field field--name-body field--type-text-with-summary field--label-hidden field__item"><p>Old advice for setting a Raspberry Pi IP address to a static IP on the Pi itself said to edit the <code>/etc/dhcpcd.conf</code> file, and add it there.</p>

<p>But on Raspberry Pi OS 12 and later, <code>dhcpcd</code> is no longer used, everything goes through Network Manager, which is configured via <code>nmcli</code> or <code>nmtui</code>.</p>

<p>So setting a static IP via the command line is a little different.</p>

<p>First, get the interface information—you can get a list of all interfaces with <code>nmcli device status</code>:</p>

<pre><code>$ nmcli device status
DEVICE         TYPE      STATE                   CONNECTION         
eth0           ethernet  connected               Wired

