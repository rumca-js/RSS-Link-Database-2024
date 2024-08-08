# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## How to mirror two screens - Raspberry Pi 4
 - [https://www.reddit.com/r/raspberry_pi/comments/1emivpq/how_to_mirror_two_screens_raspberry_pi_4](https://www.reddit.com/r/raspberry_pi/comments/1emivpq/how_to_mirror_two_screens_raspberry_pi_4)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-08-07T18:07:32+00:00

<!-- SC_OFF --><div class="md"><p>I tried going to the screen settings and overlaping the HDMI1 and HDMI2, but it doesnt work, the windows only appear on the second screen when i click and hold them</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/_Blue1999"> /u/_Blue1999 </a> <br /> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1emivpq/how_to_mirror_two_screens_raspberry_pi_4/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1emivpq/how_to_mirror_two_screens_raspberry_pi_4/">[comments]</a></span>

## Serial companion application for Raspberry Pi Pico
 - [https://www.reddit.com/r/raspberry_pi/comments/1emhw70/serial_companion_application_for_raspberry_pi_pico](https://www.reddit.com/r/raspberry_pi/comments/1emhw70/serial_companion_application_for_raspberry_pi_pico)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-08-07T17:29:12+00:00

<!-- SC_OFF --><div class="md"><p>So I am working on an EEPROM programmer for a 6502 computer that I am building and I want to use the Raspberry Pi Pico to do it. I have everything else done on the project, I can read and write to the EEPROM over a normal serial monitor such as Minicom. My problem is that I don't want to just enter every single byte of my 32k EEPROM one at a time. So I want to design a C program on the computer that communicates to my Pico and outputs the binary files to the Pico to flash. Here is the issue, I am following <a href="https://blog.mbedded.ninja/programming/operating-systems/linux/linux-serial-ports-using-c-cpp/">this</a> tutorial on how to do serial comms but I can't seem to get any connection. My code for the computer is this:</p> <pre><code>#include &lt;stdio.h&gt; #include &lt;string.h&gt; #include &lt;fstream&gt; // Linux headers #include &lt;fcntl.h&gt; // Contains file controls like O_RDWR #include &lt;errno.h&gt; // Error integer and strerror() fu

## Help with configuring a WiFi hotspot using USB Modem and Network Manager
 - [https://www.reddit.com/r/raspberry_pi/comments/1emhq64/help_with_configuring_a_wifi_hotspot_using_usb](https://www.reddit.com/r/raspberry_pi/comments/1emhq64/help_with_configuring_a_wifi_hotspot_using_usb)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-08-07T17:22:36+00:00

<!-- SC_OFF --><div class="md"><p>I'm trying to update one of my remote always-on Raspi systems and have hit a roadblock. My system uses a usb modem for the WAN interface. While rebuilding from scratch (using these instructions: <a href="https://raspberrytips.com/access-point-setup-raspberry-pi/">https://raspberrytips.com/access-point-setup-raspberry-pi/</a>) with &quot;Bullseye&quot;, I discovered that this OS uses &quot;network manager&quot; and not the prior hostspd and dnsmasq. I cannot figure out how to change this command line of the instructions &quot;sudo nmcli con modify hotspot 802-11-wireless.mode ap 802-11-wireless.band bg ipv4.method shared&quot; to &quot;share&quot; the eth1 (modem) instead of the eth0 (wired) that this command line instruction configures. Maybe there is a line entry in a config file somewhere where I can make this edit from eth0 to eth1? So far I cannot find any documentation on where config file(s) for network manager may be located in the file system.

## Trouble switching to external antenna on CM4
 - [https://www.reddit.com/r/raspberry_pi/comments/1emg63i/trouble_switching_to_external_antenna_on_cm4](https://www.reddit.com/r/raspberry_pi/comments/1emg63i/trouble_switching_to_external_antenna_on_cm4)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-08-07T16:21:57+00:00

<!-- SC_OFF --><div class="md"><p>According to guides online, just adding dtparam=ant2 to config.txt should switch to external antenna. But no matter what the setting is, the signal is exactly the same.</p> <p>Setting dtparam=noant doesn't do anything either.</p> <p>I'm using legacy raspbian (bullseye) because of HDMI compatibility issues. And yes, I'm rebooting after every change to config :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MrNiceThings"> /u/MrNiceThings </a> <br /> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1emg63i/trouble_switching_to_external_antenna_on_cm4/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1emg63i/trouble_switching_to_external_antenna_on_cm4/">[comments]</a></span>

## Waveshare spi lcd not working with rpi 5
 - [https://www.reddit.com/r/raspberry_pi/comments/1emf07z/waveshare_spi_lcd_not_working_with_rpi_5](https://www.reddit.com/r/raspberry_pi/comments/1emf07z/waveshare_spi_lcd_not_working_with_rpi_5)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-08-07T15:37:39+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone! Been a long time fan of the pi's and owned a 3b plus a while back, but now I decided to back in making a offline ai assistant using a pi 5 and the ai kit. Today l've been trying to get the waveshare 1.44 inch lcd with buttons to work, following the instructions on their site. Whilst the screen turns on white and it does show the demo, it just won't work as the system screen, getting many errors and simply things that won't work. Read things about needing to use kms drivers for the pi 5, not old ones, and getting fbop errors. I've only tried the pi os 64 and 32 bit versions. Here's the wiki link btw: <a href="https://www.waveshare.com/wiki/1.44inch_LCD_HAT">https://www.waveshare.com/wiki/1.44inch_LCD_HAT</a> Any suggestions how to get it to work would be highly appreciated! I'm getting very desperate...</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Gohro"> /u/Gohro </a> <br /> <span><a href="https:/

## Vilros fan setup, I'm very confused
 - [https://www.reddit.com/r/raspberry_pi/comments/1emdi1e/vilros_fan_setup_im_very_confused](https://www.reddit.com/r/raspberry_pi/comments/1emdi1e/vilros_fan_setup_im_very_confused)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-08-07T14:39:36+00:00

<!-- SC_OFF --><div class="md"><p>I bought the vilros starter kit for raspberry pi4. So I've been trying to get the fan to work, but have not been able to do so yet. The instructions were not super clear, it says to use the 3.3v pin with a ground on pin 14. The only problem is that it comes with the red and black combined, and a control blue, which the instruction never talked about. Anyways, I've set it up on the 5v with ground because that made sense since they are combined. But it doesn't work. So what do I do, since it seems like it should be on the 3.3v but I can't put the black on the ground because of them being together. This is just a hobby, so I'm still nieve to using the rpi. Thanks for any help you all can give.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/peace_it_out"> /u/peace_it_out </a> <br /> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1emdi1e/vilros_fan_setup_im_very_confused/">[link]</a></span> &#32; <span

## Auto start Bronos client upon boot
 - [https://www.reddit.com/r/raspberry_pi/comments/1em8l8j/auto_start_bronos_client_upon_boot](https://www.reddit.com/r/raspberry_pi/comments/1em8l8j/auto_start_bronos_client_upon_boot)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-08-07T10:44:38+00:00

<!-- SC_OFF --><div class="md"><p>So I installed the great Jishi’s Sonos HTTP API on my rpi to create an intercom. </p> <p>I also set up the Bronos client to use the intercom when I’m not connected to my WiFi. This works really well. </p> <p>I start this client by going to its folder and then enter npm start</p> <p>How do I auto start this Bronos Client with every reboot? I did use Google but I can’t get my head around it. </p> <p>Your help is much appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bk-12"> /u/bk-12 </a> <br /> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1em8l8j/auto_start_bronos_client_upon_boot/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1em8l8j/auto_start_bronos_client_upon_boot/">[comments]</a></span>

## Raspberry Pi won't detect Stream deck
 - [https://www.reddit.com/r/raspberry_pi/comments/1em6ry5/raspberry_pi_wont_detect_stream_deck](https://www.reddit.com/r/raspberry_pi/comments/1em6ry5/raspberry_pi_wont_detect_stream_deck)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-08-07T08:45:07+00:00

<!-- SC_OFF --><div class="md"><p>I have installed Companion Pi on my Raspberry Pi 5 and configured everything but the Pi won't detect that the Stream deck is connected. I am certain that the problem isn't with the Stream Deck because it runs flawlessly with the Companion installed on my PC. So what shall I do to try and fix it? I unfortunately couldn't find anything online until now so I shall ask you, the swarm intelligence of Reddit for help</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FallingPancake"> /u/FallingPancake </a> <br /> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1em6ry5/raspberry_pi_wont_detect_stream_deck/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1em6ry5/raspberry_pi_wont_detect_stream_deck/">[comments]</a></span>

## My systemd process keeps stopping when I exit the SSH session. (Zero 2W)
 - [https://www.reddit.com/r/raspberry_pi/comments/1em0elr/my_systemd_process_keeps_stopping_when_i_exit_the](https://www.reddit.com/r/raspberry_pi/comments/1em0elr/my_systemd_process_keeps_stopping_when_i_exit_the)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-08-07T02:24:54+00:00

<!-- SC_OFF --><div class="md"><p>So I'm hosting my python Discord bot on my Pi Zero 2 W, and the bot works perfectly fine and responds to commands when I'm in the SSH session, but as soon as I exit the session, the discord bot goes offline meaning the systemd process stopped. I ran some tests and troubleshooted a bit, and I can confidently say that the following things are not the issue:</p> <ol> <li><p>Throttling. The temperature capped at 36.5 degrees Celsius when a command is used.</p></li> <li><p>CPU. The usage capped at ~3% when a command is used.</p></li> <li><p>RAM. RAM usage capped at 10.5% when a command is used + I set up extra 2GB of swap.</p></li> <li><p>Network. The Pi doesn't disconnect from the WiFi network since I can SSH into the Pi right after I exit the last SSH session.</p></li> </ol> <p>If none of these are the issue, what could it be? Can someone help?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SavalioDoesTechStuff"> /

## Pi Zero 2 W wifi won't connect issue Bullseye
 - [https://www.reddit.com/r/raspberry_pi/comments/1elzt9n/pi_zero_2_w_wifi_wont_connect_issue_bullseye](https://www.reddit.com/r/raspberry_pi/comments/1elzt9n/pi_zero_2_w_wifi_wont_connect_issue_bullseye)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-08-07T01:55:53+00:00

<!-- SC_OFF --><div class="md"><p>Hey all. I've been working on a project using a zero 2 w and am pretty confident in my ability to set it up (using pi imager). I've given one of my projects to a buddy and for the life of me, cannot get it to connect to his wifi. He has an airport extreme and I've spent quite some time on the phone connecting to the pi using <a href="https://www.raspberryconnect.com/projects/65-raspberrypi-hotspot-accesspoints/203-automated-switching-accesspoint-wifi-network">THIS PROJECT</a>. He's able to SSH into the the pi and we've added the network using 'sudo nmtui'. I've also duplicated his wifi network (SSID and password) using my network setup (ubiquity equipment) and it connects, where 2.4Ghz and 5Ghz are broadcast simultaneously. </p> <p>I'm really at the end of what I know. I don't know much about the airport extreme and maybe it's the issue? When searching for nearby networks (sudo iwlist wlan0 scan) his network shows up so it's being recognized. </p> <p>

## WAVLINK USB3.0 to HDMI Adapter Not Working With Pi 5
 - [https://www.reddit.com/r/raspberry_pi/comments/1elyuih/wavlink_usb30_to_hdmi_adapter_not_working_with_pi](https://www.reddit.com/r/raspberry_pi/comments/1elyuih/wavlink_usb30_to_hdmi_adapter_not_working_with_pi)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-08-07T01:09:42+00:00

<!-- SC_OFF --><div class="md"><p>I'm attempting to use <a href="https://www.amazon.com/dp/B08HN2X88P">https://www.amazon.com/dp/B08HN2X88P</a> with my Pi 5. This StackExchange <a href="https://raspberrypi.stackexchange.com/questions/138089/raspberry-pi-4-with-raspbian-fails-to-load-desktop-on-usb-displaylink-screens/138090#138090">https://raspberrypi.stackexchange.com/questions/138089/raspberry-pi-4-with-raspbian-fails-to-load-desktop-on-usb-displaylink-screens/138090#138090</a> pointed me to this article <a href="https://blog.aaronbieber.com/2020/01/06/raspberry-pi-on-displaylink.html">https://blog.aaronbieber.com/2020/01/06/raspberry-pi-on-displaylink.html</a> . I tried following the instructions with no success. One thing I noticed is that when I run dmesg, I get the same output as in the article, except without the line &quot;fb1 is DisplayLink USB device (800x480, 1504K framebuffer memory)&quot;. Also, running &quot;ls /dev/fb*&quot; only ever shows one path, fb0 (the other HDMI

