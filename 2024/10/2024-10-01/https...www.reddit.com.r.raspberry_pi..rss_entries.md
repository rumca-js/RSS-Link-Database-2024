# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## RPI 5 doesn't fill my projector screen, shows black bars on top and bottom instead.
 - [https://www.reddit.com/r/raspberry_pi/comments/1fu0sc8/rpi_5_doesnt_fill_my_projector_screen_shows_black](https://www.reddit.com/r/raspberry_pi/comments/1fu0sc8/rpi_5_doesnt_fill_my_projector_screen_shows_black)
 - RSS feed: $source
 - date published: 2024-10-01T22:18:19+00:00

<!-- SC_OFF --><div class="md"><p>Hi, i&#39;m trying to solve this so i can watch films on it, but as it is right now, whatever aspect ratio the raspberry pi is doesn&#39;t quite match that of my projector, as a result films have a black box around them, it&#39;s not massive but it makes enough of a difference that i&#39;ll switch to my laptop, even though thats not the set up i want.</p> <p>I&#39;ve read a few old suggestions saying to go to Raspberry Pi Configuration / Display and then click on some option that no longer exists. The current version only has 3 options and none of them seem to help. Underscan makes it worse, so i&#39;ve got it unchecked. Headless resolution is on 1920x1080, my projector is 1920x1200. There must be a way to make it fit. Any ideas?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/iosu"> /u/iosu </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fu0sc8/rpi_5_doesnt_fill_my_projector_screen_show

## Plex Media Server Trouble
 - [https://www.reddit.com/r/raspberry_pi/comments/1ftz00d/plex_media_server_trouble](https://www.reddit.com/r/raspberry_pi/comments/1ftz00d/plex_media_server_trouble)
 - RSS feed: $source
 - date published: 2024-10-01T21:01:05+00:00

<!-- SC_OFF --><div class="md"><p>Hi All,</p> <p>I&#39;d rate myself above &quot;novice&quot; but below &quot;good&quot; in my Linux knowledge, but I&#39;ll try to provide as much info as possible, &amp; thanks in advance. I&#39;ve had a Plex Server running on my RPi4 (Debian buster) for years, playing shows &amp; movies locally with no problems.</p> <p>A few months ago, I had a slight issue and the HDD got unmounted while still downloading files via Deluge. I&#39;m not sure if this is relevant, but I remounted it and everything continued working as usual. Plex tells me that my server was last online 9 days ago, which is the same day I downloaded and watched my most recent movie, again without problems. However, now it shows my server is offline on all of my devices (which are all on my network). I can ping the Pi no problem, and can access and use my Deluge Web UI on the same IP address &amp; port as before. I can also watch the movies stored on the HDD on my computer (without transf

## Wifi Adapter Configuration Issues
 - [https://www.reddit.com/r/raspberry_pi/comments/1ftx93n/wifi_adapter_configuration_issues](https://www.reddit.com/r/raspberry_pi/comments/1ftx93n/wifi_adapter_configuration_issues)
 - RSS feed: $source
 - date published: 2024-10-01T19:49:07+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone and sorry to bother, I try to do everything myself but I&#39;m not coming up with a solution with this one. </p> <p>I have a Raspberry Pi2B and a TP-Link TL-WN823N V2 wireless adapter I&#39;m trying to make work. </p> <p>I followed a few guides and configured the network interfaces file like this:</p> <p>Code: <a href="https://forums.raspberrypi.com/viewtopic.php?p=2257094#">Select all</a></p> <pre><code>source /etc/network/interfaces.d/* auto lo iface lo inet loopback auto wlan0 allow-hotplug wlan0 iface wlan0 inet manual wpa-roam /etc/wpa_supplicant/wpa_supplicant.conf </code></pre> <p>Note: I removed this line &quot;iface eth0 inet manual&quot; because it stopped my ethernet connection. </p> <p>And the WPA Supplicant File:</p> <p>Code: <a href="https://forums.raspberrypi.com/viewtopic.php?p=2257094#">Select all</a></p> <pre><code>ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev update_config=1 country=IT network={ ssid=”myssid” p

## Looking for a USB-SPI bridge with linux spidev driver support
 - [https://www.reddit.com/r/raspberry_pi/comments/1ftn2sv/looking_for_a_usbspi_bridge_with_linux_spidev](https://www.reddit.com/r/raspberry_pi/comments/1ftn2sv/looking_for_a_usbspi_bridge_with_linux_spidev)
 - RSS feed: $source
 - date published: 2024-10-01T12:40:07+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I&#39;m currently facing challenges in finding a suitable USB-SPI bridge that offers native Linux support/drivers for the <code>/dev/spidevB.D</code> interface. The main issue is that many available USB bridges are designed for UART/I2C/SPI/GPIO interfaces, typically with drivers that support just UART over <code>ttyUSB/ACM</code>. However, I have not found any chips that provide native <code>spidev</code> driver support and instead relying on <code>libusb</code> for SPI/I2C communication.</p> <p>For a prototype project, we are developing a LoRa Gateway module for a Raspberry Pi CM4. Unfortunately, we cannot utilize the native SPI interface on the Pi, necessitating the use of a USB bridge. Given that the LoRa gateway software is configured to directly use an SPI interface, rewriting the software and creating a new driver would be overly complex. Thus, we are looking for a simpler solution. Due to lack of oversight we currently using the <

## Helllllp! insmod error(raspberry pi noob)
 - [https://www.reddit.com/r/raspberry_pi/comments/1ftn1lk/helllllp_insmod_errorraspberry_pi_noob](https://www.reddit.com/r/raspberry_pi/comments/1ftn1lk/helllllp_insmod_errorraspberry_pi_noob)
 - RSS feed: $source
 - date published: 2024-10-01T12:38:24+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I wrote a simple linux device driver and I am trying to load that module, but when I try to insmod this makes error:<br/> `insmod: ERROR: could not insert module file.ko: Operation not permitted`</p> <p>I didn&#39;t see this error when rpi OS was based on buster(oldoldstable)..</p> <p>tried sudo, and I checked if secure boot enabled(new feature), and I checked selinux policy in advance(default value was not set...). On internet there are some answers for UEFI-based boards but not for RPi(yup this was about MOK). Which can be a problem?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Whole-Low-2995"> /u/Whole-Low-2995 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ftn1lk/helllllp_insmod_errorraspberry_pi_noob/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ftn1lk/helllllp_insmod_errorraspberry_pi_noob/">[comments]</a></span>

## Silly question about Q BitTorrent
 - [https://www.reddit.com/r/raspberry_pi/comments/1ftiqt7/silly_question_about_q_bittorrent](https://www.reddit.com/r/raspberry_pi/comments/1ftiqt7/silly_question_about_q_bittorrent)
 - RSS feed: $source
 - date published: 2024-10-01T07:55:34+00:00

<!-- SC_OFF --><div class="md"><p>I’m new to pi and Linux so be gentle. I see v5 of qbittorrent has come out. I have done an update but see I still have v4.5.2 installed. That wasn’t even the last version before v5. Do things take a while to filter through to the pi? I guess they need recompiling and testing.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ConclusionDifficult"> /u/ConclusionDifficult </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ftiqt7/silly_question_about_q_bittorrent/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ftiqt7/silly_question_about_q_bittorrent/">[comments]</a></span>

