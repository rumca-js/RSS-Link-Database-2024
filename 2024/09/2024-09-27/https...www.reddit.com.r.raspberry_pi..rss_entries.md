# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Raspberry pi can't ping gateway
 - [https://www.reddit.com/r/raspberry_pi/comments/1fqtkec/raspberry_pi_cant_ping_gateway](https://www.reddit.com/r/raspberry_pi/comments/1fqtkec/raspberry_pi_cant_ping_gateway)
 - RSS feed: $source
 - date published: 2024-09-27T17:44:20+00:00

<!-- SC_OFF --><div class="md"><p>He everyone,<br/> I have weird bug on my pi model 3 since I had to restart my router. My installation include a pi-hole, a VPN server and a Plex server. My raspberry pi is connected by wire to my router and have a static IP adress that has been set using dhcpcd.conf. I can see it is connected to my home network on my router settings and I can access it through SSH. </p> <p>However, since the router got restarted, the pihole stopped working. When I set the DNS adress to my pihole on my devices, internet stops working because the devices are not able to do any name resolution queries to the pihole. It looks like the source of the problem is that the raspberry pi isn&#39;t able to forward filtered DNS queries to any upstream DNS server through the gateway. When I connect to it through SSH and I try to ping the gateway I received that error message : </p> <pre><code>From 192.168.2.80 icmp_seq=9 Destination Host Unreachable </code></pre> <p>The error messa

## What could consistently start to crash a Pi under heavy external drive useage that has worked fine for months?
 - [https://www.reddit.com/r/raspberry_pi/comments/1fqrm52/what_could_consistently_start_to_crash_a_pi_under](https://www.reddit.com/r/raspberry_pi/comments/1fqrm52/what_could_consistently_start_to_crash_a_pi_under)
 - RSS feed: $source
 - date published: 2024-09-27T16:19:12+00:00

<!-- SC_OFF --><div class="md"><p>Ive gone bananas the last few days trying to figure out why Plex Media server when scanning files crashes my 8GB Pi 5. It worked beautfully for at least 6 months then one day out of the blue it started having issues when 2 different computers were copying and retreiving files off the 18 TB WD Easystore external HD (formatted NTFS) that has all of my Plex media on it. To eliminate it as a possibility I purchased the Raspberry Pi 5 official plug. Worked for a few days then Plex server wouldn&#39;t be able to start without crashing as per journalctl. </p> <p>I eventually gave up and pulled out another microsd card (both are 128 sandisk extremes), format it, and started all over again with a fresh install of Raspbian. I mounted the external drive, setup samba, installed Plexmediaserver, had some issues with getting Plex to run when copying over too many files from the old /var/lib/plexmediaserver and then finally it worked. I setup the new server and afte

## My project for "recreating" a radio from the 50s
 - [https://www.reddit.com/r/raspberry_pi/comments/1fqr5fw/my_project_for_recreating_a_radio_from_the_50s](https://www.reddit.com/r/raspberry_pi/comments/1fqr5fw/my_project_for_recreating_a_radio_from_the_50s)
 - RSS feed: $source
 - date published: 2024-09-27T15:59:46+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1fqr5fw/my_project_for_recreating_a_radio_from_the_50s/"> <img src="https://external-preview.redd.it/YJOWpKHpgYSM6MfI0NXHBLoVuh_IjAn7oJ9dWvkCLbg.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=9c6619d57159a80b6577f7fe1774dc159eb852b7" alt="My project for &quot;recreating&quot; a radio from the 50s" title="My project for &quot;recreating&quot; a radio from the 50s" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/joshschmitton"> /u/joshschmitton </a> <br/> <span><a href="https://github.com/mboyers/retro-radio">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fqr5fw/my_project_for_recreating_a_radio_from_the_50s/">[comments]</a></span> </td></tr></table>

## How can convert "vmlinuz-6.6.47+rpt-rpi-v8" to "Image" ? Because "vmlinuz-6.6.47+rpt-rpi-v8" is not able to boot from qemu.
 - [https://www.reddit.com/r/raspberry_pi/comments/1fqnhhe/how_can_convert_vmlinuz6647rptrpiv8_to_image](https://www.reddit.com/r/raspberry_pi/comments/1fqnhhe/how_can_convert_vmlinuz6647rptrpiv8_to_image)
 - RSS feed: $source
 - date published: 2024-09-27T13:16:52+00:00

<!-- SC_OFF --><div class="md"><p>Hello to everyone.</p> <p>I&#39;ve emulated RaspiOS based on Debian Bookworm on Ubuntu 24.04 X64 bit using this script assembled by me :</p> <p><code>if ping -c 1</code> <a href="http://192.168.1.9"><code>192.168.1.9</code></a> <code>&amp;&gt; /dev/null then</code><br/> <code>echo &quot;success&quot;</code><br/> <code>sleep 1</code></p> <p> <code>qemu-system-aarch64 -machine virt-9.0,virtualization=on,gic_version=3 -cpu max -smp 8 -m 8G -kernel /mnt/zroot-133/zroot-133/_A_OS/Linux/RaspiOS/Image -append &quot;root=/dev/vda2 rootfstype=ext4 rw panic=0 console=ttyAMA0 kvm-arm.mode=nested&quot; -drive format=raw,file=/mnt/zroot-133/zroot-133/_A_OS/Linux/RaspiOS/2024-07-04-raspios-bookworm-arm64-big.img,if=none,id=hd0 -device virtio-blk,drive=hd0,bootindex=0 -netdev tap,id=mynet0,ifname=tap0,script=no,downscript=no -device virtio-net-pci,netdev=mynet0,mac=52:55:00:d1:55:01 -device usb-ehci -device usb-kbd -device virtio-tablet-pci -usb -device virtio-seria

## MicroSD Corruption After Power Outages with PoE HAT – Anyone Else?
 - [https://www.reddit.com/r/raspberry_pi/comments/1fqluae/microsd_corruption_after_power_outages_with_poe](https://www.reddit.com/r/raspberry_pi/comments/1fqluae/microsd_corruption_after_power_outages_with_poe)
 - RSS feed: $source
 - date published: 2024-09-27T11:50:42+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I’m using a Raspberry Pi Model 4 with a PoE HAT, and I’ve been running into an issue where my microSD card gets corrupted after a power outage. I do have my switch protected with a UPS, but the Pi still seems to lose power, and every time this happens, I end up having to buy a new microSD card and reinstall the system, which is getting pretty frustrating.</p> <p>Has anyone else experienced this with the PoE HAT? I’m thinking the issue might be related to the power delivery from the PoE, so I’m going to try powering the Pi with a USB-C source instead and see what happens after the next outage.</p> <p>Any advice or similar experiences would be really appreciated!</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/juanpavergara"> /u/juanpavergara </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fqluae/microsd_corruption_after_power_outages_with_poe/">[link]</a></sp

## Tic80 baremetal build available for every pi (minus the pico)
 - [https://www.reddit.com/r/raspberry_pi/comments/1fqjq02/tic80_baremetal_build_available_for_every_pi](https://www.reddit.com/r/raspberry_pi/comments/1fqjq02/tic80_baremetal_build_available_for_every_pi)
 - RSS feed: $source
 - date published: 2024-09-27T09:26:03+00:00

<!-- SC_OFF --><div class="md"><p>I updated tic80&#39;s baremetal builds to support more boards, community testing would be helpful to the project.</p> <p>All pi&#39;s should work (from 1-5) minus the pico.</p> <p>Installation is easy, download your board&#39;s build, extract the zip and copy the files to the sdcard of your choice.</p> <p>Make a folder named tic80 and copy the carts of your liking, here&#39;s a cart search tool: <a href="https://n0fa.de/tic80/search/">https://n0fa.de/tic80/search/</a></p> <p>Link to the builds: <a href="https://github.com/Miguel-hrvs/TIC-80/actions/runs/11067585583">https://github.com/Miguel-hrvs/TIC-80/actions/runs/11067585583</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Terrible-Quality-292"> /u/Terrible-Quality-292 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fqjq02/tic80_baremetal_build_available_for_every_pi/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r

## raspberry pi - mediapipe
 - [https://www.reddit.com/r/raspberry_pi/comments/1fqbh78/raspberry_pi_mediapipe](https://www.reddit.com/r/raspberry_pi/comments/1fqbh78/raspberry_pi_mediapipe)
 - RSS feed: $source
 - date published: 2024-09-27T00:38:10+00:00

<!-- SC_OFF --><div class="md"><p>Hello, im creating a project about pose recognition but im newbie with all this things, so i have a lot of questions. </p> <p>Im trying to use a raspberry pi 4 with the raspberry pi camera, to do that im using libraries like picamera2, libcamera, and others. But when i tried mediapipe, i couldnt install it, so to fix it, i created a virtual environment where i installed all libraries and finally mediapipe worked. But it doesnt show anything when i define &quot;ret&quot; and &quot;frame&quot;. So i wonder if picamera hasnt compatibility with opencv, someone could confirm this?, and if it is, how i know which cameras support it?. </p> <p>At the same time, i tried picamera2 to replace some parts of the code. but im having issues using libcamera. It works from the TERMINAL, but it doesnt from the virtual environment.</p> <p>I&#39;ll really apreciatte your help, thanks!.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user

