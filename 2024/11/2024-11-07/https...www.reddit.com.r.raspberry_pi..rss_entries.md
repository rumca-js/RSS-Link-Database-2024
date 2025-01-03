# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Trouble adding USB Wifi Adapter to Pi 4
 - [https://www.reddit.com/r/raspberry_pi/comments/1gm46n0/trouble_adding_usb_wifi_adapter_to_pi_4](https://www.reddit.com/r/raspberry_pi/comments/1gm46n0/trouble_adding_usb_wifi_adapter_to_pi_4)
 - RSS feed: $source
 - date published: 2024-11-07T23:18:09+00:00

<!-- SC_OFF --><div class="md"><p>I need to connect my Pi 4 to two separate Wi-Fi networks at the same time so if I read everything correctly, I need to add a USB Wi-Fi adapter to it. </p> <p>I need to run a Tailscale connection on the internal wifi adapter wlan0 which is connecting to tailscale. </p> <p>When I plug in the new adapter lsusb shows it as</p> <p>Bus 001 Device 007: ID 0bda:818b Realtek Semiconductor Corp. RTL8192EU 802.11b/g/n WLAN Adapter which brings me to an old post at <a href="https://community.roonlabs.com/t/realtek-rtl8192eu-wifi-drivers-for-raspbian/15287/2">Realtek RTL8192EU WiFi drivers for Raspbian - Audio Gear Talk / Raspberry Pi - Roon Labs Community</a> that leads to a dead link.</p> <p>I then found <a href="https://forums.linuxmint.com/viewtopic.php?t=379012">[SOLVED] RTL8192EU 802.11b/g/n WLAN Adapter will not connect LM 21 - Linux Mint Forums</a> and started instructions found on it and it fails with the following</p> <p>Building module:</p> <p>cleaning

## Pi NAS transfer speed issue
 - [https://www.reddit.com/r/raspberry_pi/comments/1gm2i2f/pi_nas_transfer_speed_issue](https://www.reddit.com/r/raspberry_pi/comments/1gm2i2f/pi_nas_transfer_speed_issue)
 - RSS feed: $source
 - date published: 2024-11-07T22:03:50+00:00

<!-- SC_OFF --><div class="md"><p>Hello all, im having an issue with the transfer speeds of my raspberry pi 5 with OMV. On OMV I’m only getting 100 mb/s. The pi itself is downloading 350 mb/s and uploading around 50 from a test. OMV sees both eth1 or eth0 and eth1 is seen as 1000 mb/s capable through ethtool. I’m getting 1GB/s through my switch to my pi so do not mention “it’s the cable”. </p> <p>Help is appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Twigzywik"> /u/Twigzywik </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gm2i2f/pi_nas_transfer_speed_issue/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gm2i2f/pi_nas_transfer_speed_issue/">[comments]</a></span>

## Is my SD Card the bottleneck?
 - [https://www.reddit.com/r/raspberry_pi/comments/1gm1upa/is_my_sd_card_the_bottleneck](https://www.reddit.com/r/raspberry_pi/comments/1gm1upa/is_my_sd_card_the_bottleneck)
 - RSS feed: $source
 - date published: 2024-11-07T21:35:53+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1gm1upa/is_my_sd_card_the_bottleneck/"> <img src="https://b.thumbs.redditmedia.com/CC2nCxqOeik24PB6X8QxR8tKpLlBceGNt8xNLvWx02g.jpg" alt="Is my SD Card the bottleneck?" title="Is my SD Card the bottleneck?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/zat1akpxsjzd1.png?width=1888&amp;format=png&amp;auto=webp&amp;s=fa415958cd390c5766acc41b01ba031b07c59b33">https://preview.redd.it/zat1akpxsjzd1.png?width=1888&amp;format=png&amp;auto=webp&amp;s=fa415958cd390c5766acc41b01ba031b07c59b33</a></p> <p>Having the following issue where my raspberry pi 5s load is really high but the cpu is really low, so i just wanted to ask, is my SD Card potentially the bottleneck.</p> <p>I&#39;m using my raspberry pi to self host a few things like Home Assistant, Immich and a dns server.</p> <p>I often have times where the Pi goes unresponsive over ssh, however on glances i can see that the cpu is r

## Raspberry Pi USB 3 Hub on sale now at $12
 - [https://www.reddit.com/r/raspberry_pi/comments/1glvohd/raspberry_pi_usb_3_hub_on_sale_now_at_12](https://www.reddit.com/r/raspberry_pi/comments/1glvohd/raspberry_pi_usb_3_hub_on_sale_now_at_12)
 - RSS feed: $source
 - date published: 2024-11-07T17:18:33+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/KillAllTheThings"> /u/KillAllTheThings </a> <br/> <span><a href="https://www.raspberrypi.com/news/raspberry-pi-usb-3-hub-on-sale-now-at-12/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1glvohd/raspberry_pi_usb_3_hub_on_sale_now_at_12/">[comments]</a></span>

## How to upgrade to new version
 - [https://www.reddit.com/r/raspberry_pi/comments/1glkw5m/how_to_upgrade_to_new_version](https://www.reddit.com/r/raspberry_pi/comments/1glkw5m/how_to_upgrade_to_new_version)
 - RSS feed: $source
 - date published: 2024-11-07T07:14:38+00:00

<!-- SC_OFF --><div class="md"><p>I am currently on the following version</p> <ul> <li>PRETTY_NAME=&quot;Raspbian GNU/Linux 10 (buster)&quot;</li> <li>NAME=&quot;Raspbian GNU/Linux&quot;</li> <li>VERSION_ID=&quot;10&quot;</li> <li>VERSION=&quot;10 (buster)&quot;</li> <li>VERSION_CODENAME=buster</li> </ul> <p>I executed the following statements</p> <ul> <li>sudo apt update</li> <li>sudo apt remove npm nodejs nodejs-doc node-* </li> <li>sudo apt full-upgrade</li> </ul> <p>It seems to upgrade, but I always stay on Version 10 buster, although there are newer ones. What am I doing wrong?</p> <p>I have a Raspberry Pi 4 Model B 8GB in case that matters.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BlueDecoy"> /u/BlueDecoy </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1glkw5m/how_to_upgrade_to_new_version/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1glkw5m/how_to_upgrade_to_new_ve

## How to prevent DOSing my raspberry
 - [https://www.reddit.com/r/raspberry_pi/comments/1gldioj/how_to_prevent_dosing_my_raspberry](https://www.reddit.com/r/raspberry_pi/comments/1gldioj/how_to_prevent_dosing_my_raspberry)
 - RSS feed: $source
 - date published: 2024-11-07T00:19:22+00:00

<!-- SC_OFF --><div class="md"><p>I am running heavy loads on my raspberry 4B, and sometimes it becomes unresponsive and I have to unplug and plug it again. The service is immich and its running in docker. This could just as well be a docker and/or immich problem. But is there anyway I can 1. find out and analyse what is causing this and 2. possible prevent such from happening.</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gilfslayer666"> /u/gilfslayer666 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gldioj/how_to_prevent_dosing_my_raspberry/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gldioj/how_to_prevent_dosing_my_raspberry/">[comments]</a></span>

