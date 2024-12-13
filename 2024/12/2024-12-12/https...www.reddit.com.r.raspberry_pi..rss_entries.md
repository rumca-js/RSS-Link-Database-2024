# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Inky What non-stop errors
 - [https://www.reddit.com/r/raspberry_pi/comments/1hcpgtn/inky_what_nonstop_errors](https://www.reddit.com/r/raspberry_pi/comments/1hcpgtn/inky_what_nonstop_errors)
 - RSS feed: $source
 - date published: 2024-12-12T16:53:46+00:00

<!-- SC_OFF --><div class="md"><p>Hi folks, I&#39;m pretty new to Pi. I have a zero with the header running the most recent (12/13/24) PiOS. I followed the instructions on pimoroni website for setting up the wHAT got thrown error after error after error including the font they called for not existing (fredoka). Eventually, somehow got it to clear the default image, but have had no luck running anything since that.</p> <p>I finally tried just writing my own python script in the included complier, again following the guide on pimoroni&#39;s website. The code doesn&#39;t even make it past the first line </p> <p>from inky.auto import auto</p> <p>Says no such directory exists.</p> <p>Thinking I might just wipe the SD card and start over. Any help is welcome!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FuzzHeadsFuzz"> /u/FuzzHeadsFuzz </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hcpgtn/inky_what_nonstop_errors/">[link]

## I setup a Pi in a remote part of the building to run on a precise timer
 - [https://www.reddit.com/r/raspberry_pi/comments/1hcmtu4/i_setup_a_pi_in_a_remote_part_of_the_building_to](https://www.reddit.com/r/raspberry_pi/comments/1hcmtu4/i_setup_a_pi_in_a_remote_part_of_the_building_to)
 - RSS feed: $source
 - date published: 2024-12-12T14:56:00+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1hcmtu4/i_setup_a_pi_in_a_remote_part_of_the_building_to/"> <img src="https://b.thumbs.redditmedia.com/iNAdk2qKoxnEjSfwcg9LcoGauuTG997hBr5hlELnoYM.jpg" alt="I setup a Pi in a remote part of the building to run on a precise timer" title="I setup a Pi in a remote part of the building to run on a precise timer" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Good day,</p> <p>I have a USB monitoring device that I am collecting readings every 15min. I decided that Im going to use POE and an RTC. I have done this with a Pi4 and a Pi3.</p> <p><a href="https://preview.redd.it/dt7s0dj7mf6e1.png?width=691&amp;format=png&amp;auto=webp&amp;s=2668ffbb6fd9cfdc78683a0fef59e9e278981e32">https://preview.redd.it/dt7s0dj7mf6e1.png?width=691&amp;format=png&amp;auto=webp&amp;s=2668ffbb6fd9cfdc78683a0fef59e9e278981e32</a></p> <p><a href="https://preview.redd.it/wly8rfj7mf6e1.png?width=691&amp;format=png&amp;auto=webp&amp;s=9924fa

## pigpio acts oddly when used in a system service and asked to stop. Here's the workaround.
 - [https://www.reddit.com/r/raspberry_pi/comments/1hcmin1/pigpio_acts_oddly_when_used_in_a_system_service](https://www.reddit.com/r/raspberry_pi/comments/1hcmin1/pigpio_acts_oddly_when_used_in_a_system_service)
 - RSS feed: $source
 - date published: 2024-12-12T14:40:43+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m posting this as an FYI, but also to sanity-check my results.</p> <p>I&#39;m using pigpio to control some lighting with a Pi Zero W, and it works fine. I made it into a system service and it continued to work fine - but when a did a <em>sudo system xxx stop</em>, the stop command would <em>almost</em> always hang for a long time (presumably 90 seconds, the default &quot;Just SIGKILL it&quot; timer) and then return.</p> <p>systemd uses SIGTERM when you issue a stop. In my code, I used </p> <pre><code>gpioSetSignalFunc(SIGTERM, exiting); </code></pre> <p>where exiting() is a function that just posts to a semaphore. I had another thread (my exit handler) waiting on that semaphore, which would then proceed to clean up a little, shut down pigpio, and call exit(0). This is the &quot;one true way&quot; to shut down a threaded process, since it avoids doing anything sketchy in the signal handler. Note that I use a mutex around all my calls to pigpio s

## Raspberry Pi 5 IBSS AD-HOC Wifi network using nmcli or nmtui (no graphic interface)
 - [https://www.reddit.com/r/raspberry_pi/comments/1hch3zg/raspberry_pi_5_ibss_adhoc_wifi_network_using](https://www.reddit.com/r/raspberry_pi/comments/1hch3zg/raspberry_pi_5_ibss_adhoc_wifi_network_using)
 - RSS feed: $source
 - date published: 2024-12-12T09:04:04+00:00

<!-- SC_OFF --><div class="md"><p>Hi!</p> <p>I need to create an ad-hoc network with several Raspberry Pi 5. No DHCP required (each will have an static IP) and also no default route (I need IBSS mode, as the wifi network will be used just to interconnect the raspberrys) All examples I find are for older hardware and OS. How can I do that in Bookworm Raspberry OS? I have tried using nmtui shell tool but no success. I am getting auth errors: When I use nmcli as in</p> <pre><code>nmcli connection modify adhoc-network ipv4.method manual ipv4.addresses 192.168.1.1/24 </code></pre> <p>but I get:</p> <pre><code>802.1X supplicant took too long to authenticate </code></pre> <p>Then I modify it to ensure it does not use 802.1x doing</p> <pre><code>nmcli connection modify adhoc-network 802-11-wireless-security.key-mgmt none </code></pre> <p>getting</p> <pre><code>Passwords or encryption keys are required to access the wireless network &#39;adhoc-network&#39; </code></pre> <p>So I try:</p> <pre>

## First Project with a raspberry Pi 3.
 - [https://www.reddit.com/r/raspberry_pi/comments/1hceyoc/first_project_with_a_raspberry_pi_3](https://www.reddit.com/r/raspberry_pi/comments/1hceyoc/first_project_with_a_raspberry_pi_3)
 - RSS feed: $source
 - date published: 2024-12-12T06:23:02+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1hceyoc/first_project_with_a_raspberry_pi_3/"> <img src="https://b.thumbs.redditmedia.com/UWDRMzMnMMnr7l-xJaJsZ63_RqWeUUM_Xwcir8cMpFg.jpg" alt="First Project with a raspberry Pi 3." title="First Project with a raspberry Pi 3." /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Made a family calendar. I am currently using the free version of Dakboard. On a Black Friday deal 32&quot; tv. I need to clean up the screen cord.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Zaphod07"> /u/Zaphod07 </a> <br/> <span><a href="https://www.reddit.com/gallery/1hceyoc">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hceyoc/first_project_with_a_raspberry_pi_3/">[comments]</a></span> </td></tr></table>

## Lock the Taskbar in Rasberry Pi OS.
 - [https://www.reddit.com/r/raspberry_pi/comments/1hcczui/lock_the_taskbar_in_rasberry_pi_os](https://www.reddit.com/r/raspberry_pi/comments/1hcczui/lock_the_taskbar_in_rasberry_pi_os)
 - RSS feed: $source
 - date published: 2024-12-12T04:21:17+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I&#39;m new to the whole RaspPi OS and I&#39;ve searched everywhere for this answer and can&#39;t find one, but is there a way to &quot;lock&quot; or disable the ability to edit the applets on the taskbar? I accidentally removed some applets when I right clicked on the task bar and it was a struggle putting them back and I&#39;d like to lock down the task bar so it doesn&#39;t happen again. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FoxDieDM"> /u/FoxDieDM </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hcczui/lock_the_taskbar_in_rasberry_pi_os/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hcczui/lock_the_taskbar_in_rasberry_pi_os/">[comments]</a></span>

## Cannot ssh over USB to Pi Zero V1.3 MacOS Sequoia 15.2
 - [https://www.reddit.com/r/raspberry_pi/comments/1hc9vvh/cannot_ssh_over_usb_to_pi_zero_v13_macos_sequoia](https://www.reddit.com/r/raspberry_pi/comments/1hc9vvh/cannot_ssh_over_usb_to_pi_zero_v13_macos_sequoia)
 - RSS feed: $source
 - date published: 2024-12-12T01:33:48+00:00

<!-- SC_OFF --><div class="md"><p>Wondering if anyone else is having problems with this, one day it was working and now I can&#39;t ssh into any of my pi zeroes over USB.</p> <p>MacOS Sequoia 15.2 Beta, firewall disabled</p> <p>Pi Zero V1.3, running Debian Bullseye Lite</p> <p>The following process used to work, but no longer does... I don&#39;t think my computer auto-updated the beta but could have. The RNDIS gadget shows up but cannot ping or ssh the pi... thoughts?</p> <p><code>modules-load=dwc2,g_ether</code> added after rootwait, <code>dtoverlay=dwc2</code> added to config, empty ssh file, userconf file specified</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kylejmorrison"> /u/kylejmorrison </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hc9vvh/cannot_ssh_over_usb_to_pi_zero_v13_macos_sequoia/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hc9vvh/cannot_ssh_over_usb_to_pi_

## Pico 2W + OLED 1.3 display from waveshare
 - [https://www.reddit.com/r/raspberry_pi/comments/1hc8qqt/pico_2w_oled_13_display_from_waveshare](https://www.reddit.com/r/raspberry_pi/comments/1hc8qqt/pico_2w_oled_13_display_from_waveshare)
 - RSS feed: $source
 - date published: 2024-12-12T00:37:16+00:00

<!-- SC_OFF --><div class="md"><p>Pico 2W with OLED 1.3 driver </p> <p>Hi, </p> <p>Can you spot any issue with my soldering?</p> <p><a href="https://imgur.com/a/Jrv3wnP">https://imgur.com/a/Jrv3wnP</a></p> <p>I tried setting up my Pico with the OLED driver from waveshare (<a href="https://www.berrybase.de/1.3-64-128-oled-display-modul-fuer-raspberry-pi-pico">https://www.berrybase.de/1.3-64-128-oled-display-modul-fuer-raspberry-pi-pico</a>). Someone wrote a review that the I2C example from the vendor doesn’t work. <a href="https://www.waveshare.com/wiki/Pico-OLED-1.3">https://www.waveshare.com/wiki/Pico-OLED-1.3</a></p> <p>Well, I tried both examples, SPI and I2C and they don’t work for me. Screen stays black. </p> <p>I can’t spot the issue. I believe it’s an issue with the hardware since I used the official test code (SPI) from the vendor assuming that the code that the vendor provided works…</p> <p>How can I make sure that the OLED display driver is fine? Is it possible that the hea

