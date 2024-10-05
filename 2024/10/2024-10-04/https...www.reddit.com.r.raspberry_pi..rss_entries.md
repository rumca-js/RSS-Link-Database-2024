# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## How can I tell if the RPi Zero 2 is wireless or not?
 - [https://www.reddit.com/r/raspberry_pi/comments/1fwawm6/how_can_i_tell_if_the_rpi_zero_2_is_wireless_or](https://www.reddit.com/r/raspberry_pi/comments/1fwawm6/how_can_i_tell_if_the_rpi_zero_2_is_wireless_or)
 - RSS feed: $source
 - date published: 2024-10-04T21:53:29+00:00

<!-- SC_OFF --><div class="md"><p>This is the <a href="https://imgur.com/a/XqapRh8">unit</a>. The model states that it&#39;s a &quot;Raspberry Pi Zero 2&quot;, which suggests that it&#39;s not wireless. But then on the bottom it states: &quot;Uses antenna technology...&quot; which, to me, means that the unit has a radio in it.</p> <p>How can I (without spinning up SD card, finding proper cables and setting up SSH, etc...) identify whether this RPi Zero is a wireless one?</p> <p><a href="https://imgur.com/a/pU963gZ">This</a> is the other side of it.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SophieTheCat"> /u/SophieTheCat </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fwawm6/how_can_i_tell_if_the_rpi_zero_2_is_wireless_or/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fwawm6/how_can_i_tell_if_the_rpi_zero_2_is_wireless_or/">[comments]</a></span>

## Raspberry Pi Zero W not Finding any Wifi Networks
 - [https://www.reddit.com/r/raspberry_pi/comments/1fw0mh5/raspberry_pi_zero_w_not_finding_any_wifi_networks](https://www.reddit.com/r/raspberry_pi/comments/1fw0mh5/raspberry_pi_zero_w_not_finding_any_wifi_networks)
 - RSS feed: $source
 - date published: 2024-10-04T14:34:09+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I&#39;ve recently dug out a Pi Zero W out of a drawer, where it probably laid for four years at least. I created a boot image using the official imager and set all the networking/ssh config as I&#39;d hoped I could just use it without ever connecting physical peripherals to it.</p> <p>My troubles began.</p> <p>It boots fine to a desktop, the wifi options are available (in the taskbar it shows two blue arrows in opposite directions) but no networks are there to be connected to. The default connection set during the imaging process also doesn&#39;t connect. I&#39;ve validated this both from my router&#39;s control panel as well as the various utilities I could think of (nmcli, ip link, the GUI).</p> <p>My country code is set to DE.</p> <p><code>rfkill list</code> shows a wlan device called phy.</p> <p>iwlist also doesn&#39;t show anything.</p> <p><code> $ iwlist wlan0 scan wlan0 No scan results </code></p> <p><code>dmesg | grep wlan0</code> r

