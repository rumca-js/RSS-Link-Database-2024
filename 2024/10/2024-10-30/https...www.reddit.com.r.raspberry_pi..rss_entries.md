# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Weird ACT led behaviour on Pi3
 - [https://www.reddit.com/r/raspberry_pi/comments/1gfzsqy/weird_act_led_behaviour_on_pi3](https://www.reddit.com/r/raspberry_pi/comments/1gfzsqy/weird_act_led_behaviour_on_pi3)
 - RSS feed: $source
 - date published: 2024-10-30T22:54:26+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve got a Pi4 home server. Usually, it boots from an sdcard, but sometimes I boot it from usb. In the latter case, when there is no sdcard inserted, the green ACT led blinks regularly, like if there is some activity. I figured out it was due to sdcard polling (each 2 secs or so). To make it not blink, I use <code>dtparam=sd_poll_once</code> in my config.txt.</p> <p>Another home server is Pi3. The issue is <code>dtparam=sd_poll_once</code> makes the ACT led behave weird. On disk activity, it turns ON and keeps that way until there is no activity for like 30s. Like, if there is a cooldown to turn it off. When &quot;on cooldown&quot;, <code>iostat -d 2</code> shows no disk activity, but the led is ON.</p> <p>I noticed it after installing a fresh copy of armbian and setting things up, like I did on my Pi4, including <code>dtparam=sd_poll_once</code>. As soon as I commented out the sd_poll_once line in config.txt and rebooted, the led started blinkin

## Recent geekworm x1202 ups does not work with current software
 - [https://www.reddit.com/r/raspberry_pi/comments/1gfy9u3/recent_geekworm_x1202_ups_does_not_work_with](https://www.reddit.com/r/raspberry_pi/comments/1gfy9u3/recent_geekworm_x1202_ups_does_not_work_with)
 - RSS feed: $source
 - date published: 2024-10-30T21:47:21+00:00

<!-- SC_OFF --><div class="md"><p>I have developed working software to shutdown and reboot an rpi with the geekworm x1202 hat. I am testing on a newly assembled device and something has changed. The i2c address is no 0x48 and not 0x36. Furthermore, the capacity and voltage readings using the geekworm example scripts on github and my own code based of these scripts are significantly off, seemingly by a factor of 2. Anyone have some insights? I have set the eeprom, etc. and this same code worked in the past.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Tricky_Condition_279"> /u/Tricky_Condition_279 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gfy9u3/recent_geekworm_x1202_ups_does_not_work_with/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gfy9u3/recent_geekworm_x1202_ups_does_not_work_with/">[comments]</a></span>

## Arducam Mega Framerate
 - [https://www.reddit.com/r/raspberry_pi/comments/1gfna5m/arducam_mega_framerate](https://www.reddit.com/r/raspberry_pi/comments/1gfna5m/arducam_mega_framerate)
 - RSS feed: $source
 - date published: 2024-10-30T14:03:31+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>Has anybody tried to capture frames from the Arducam Mega and knows how fast its possible? the SPI speed is 8Mhz, so in theory with JPEG compression a framerate of &gt;10fps@1MP should not by a problem. Is this correct?</p> <p>thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Responsible-Kiwi-629"> /u/Responsible-Kiwi-629 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gfna5m/arducam_mega_framerate/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gfna5m/arducam_mega_framerate/">[comments]</a></span>

## Raspberry Pi 5 wifi problem
 - [https://www.reddit.com/r/raspberry_pi/comments/1gfmin3/raspberry_pi_5_wifi_problem](https://www.reddit.com/r/raspberry_pi/comments/1gfmin3/raspberry_pi_5_wifi_problem)
 - RSS feed: $source
 - date published: 2024-10-30T13:28:12+00:00

<!-- SC_OFF --><div class="md"><p>Raspberry Pi OS can&#39;t connect to wifi</p> <p>Hello</p> <p>(pi 5) It&#39;s been 4 hours that i&#39;m trying to connect via wifi to my custom access point from my smartphone.</p> <p>Here are the specs : WPA2/3 2,4 GHz</p> <p>It does manage to find it but is unable to connect. </p> <p>I have tried on multiple OS (pi and ubuntu) and got the same problem. </p> <p>I have tried connecting via ethernet to my wifi and it works perfectly. </p> <p>So the problem come from the wifi.</p> <p>I power it up without the official adapter.</p> <p>Can anyone help ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Tony_Fuzz"> /u/Tony_Fuzz </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gfmin3/raspberry_pi_5_wifi_problem/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gfmin3/raspberry_pi_5_wifi_problem/">[comments]</a></span>

## E-Ink Family Calendar: a Raspberry Pi project
 - [https://www.reddit.com/r/raspberry_pi/comments/1gflfii/eink_family_calendar_a_raspberry_pi_project](https://www.reddit.com/r/raspberry_pi/comments/1gflfii/eink_family_calendar_a_raspberry_pi_project)
 - RSS feed: $source
 - date published: 2024-10-30T12:34:24+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1gflfii/eink_family_calendar_a_raspberry_pi_project/"> <img src="https://external-preview.redd.it/C8SK1KfihDvN2obj8C7kVv6Mhj6cBADiL33_VBWkpmc.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=3281100c53cac3a3e3199d4a81949f4b813d96b7" alt="E-Ink Family Calendar: a Raspberry Pi project" title="E-Ink Family Calendar: a Raspberry Pi project" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Based on great work by <a href="/u/speedyg0nz">u/speedyg0nz</a> (for example, his <a href="https://www.reddit.com/r/raspberry_pi/comments/12joara/maginkdash_magic_eink_dashboard_project_full/">MagInkDash</a>), I created an E-Ink Family Calendar as my first Raspberry Pi project.</p> <p><a href="https://preview.redd.it/7x1azbn81wxd1.jpg?width=2560&amp;format=pjpg&amp;auto=webp&amp;s=4a1b60a6e686582c1a546dfb97e9138d3278780d">https://preview.redd.it/7x1azbn81wxd1.jpg?width=2560&amp;format=pjpg&amp;auto=webp&amp;s=4a1b60a6e686582c1a5

## Diagonal Screen, Please help
 - [https://www.reddit.com/r/raspberry_pi/comments/1gffhtt/diagonal_screen_please_help](https://www.reddit.com/r/raspberry_pi/comments/1gffhtt/diagonal_screen_please_help)
 - RSS feed: $source
 - date published: 2024-10-30T05:34:46+00:00

<!-- SC_OFF --><div class="md"><p>I am working on a Raspberry Pi 4B 4GB using this monitor,</p> <p><a href="https://www.amazon.com/gp/product/B0BY1QWMJY/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&amp;psc=1">https://www.amazon.com/gp/product/B0BY1QWMJY/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&amp;psc=1</a></p> <p>The developer says to add this to the config file, however when trying to work it with ubuntu, no matter how I add it into the config file, I permanently get a diagonal screen where it is split down the middle.</p> <p>When connecting an 11.6-inch display to the Raspberry Pi, please set the Add Resolution parameter in the Config.txt file of the Raspberry Pi to avoid diagonal problems, as follows:</p> <p>[all]</p> <p>#dtoverlay=vc4-fkms-v3d</p> <p>#framebuffer_width=1366</p> <p>#framebuffer_height=768</p> <p>max_usb_current=1</p> <p>hdmi_force_hotplug=1</p> <p>config_hdmi_boost=7</p> <p>hdmi_group=2</p> <p>hdmi_mode=1</p> <p>hdmi_mode=87</p> <p>hdmi_drive=1</p> <p>display_rotat

## Local WiFi Devices Have Intermittent Connection with PiVPN Enabled
 - [https://www.reddit.com/r/raspberry_pi/comments/1gfd9q0/local_wifi_devices_have_intermittent_connection](https://www.reddit.com/r/raspberry_pi/comments/1gfd9q0/local_wifi_devices_have_intermittent_connection)
 - RSS feed: $source
 - date published: 2024-10-30T03:15:45+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone!</p> <p>I am new to the PiVPN scene and have watched several YouTube videos now on how to configure a raspberry to run PiVPN.</p> <p>My main purpose was to connect to my network so I could send WoL packet to my main PC so the I could use RDP programs such as AnyDesk or TeamViewer. (I know, it has a paid feature to do WoL but that feature ain’t worth the dollars)</p> <p>My issue is, when the Raspberry Pi is connected to my router via Ethernet and then just running without any devices directly connected to PiVPN, other wireless devices on my network are dropping connections. For instance, I was watching Netflix shortly after successfully installing PiVPN and it was buffering which was odd considering, 1.) I have 3Gbps D&amp;U speeds and 2.) Never experience any issues prior to installing the PiVPN. I unplugged the Pi and the issue was resolved. Also would like to mention, the TV <strong>was not connected</strong> to the VPN, just to clarify

## I made a giant creepy eye that tracks people walking on the sidewalk. Built with 24 7-segment flipdigit panels and YOLOv8.
 - [https://www.reddit.com/r/raspberry_pi/comments/1gf9q37/i_made_a_giant_creepy_eye_that_tracks_people](https://www.reddit.com/r/raspberry_pi/comments/1gf9q37/i_made_a_giant_creepy_eye_that_tracks_people)
 - RSS feed: $source
 - date published: 2024-10-30T00:15:37+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1gf9q37/i_made_a_giant_creepy_eye_that_tracks_people/"> <img src="https://external-preview.redd.it/anRmbXV2ZW5kc3hkMX1JzZcKRXShkzUwBjmMGTYNvU-DCJ5Te3H8JniX0CHB.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=52f31b27b3dc096e6636a00afb8734ebb16fa8fb" alt="I made a giant creepy eye that tracks people walking on the sidewalk. Built with 24 7-segment flipdigit panels and YOLOv8. " title="I made a giant creepy eye that tracks people walking on the sidewalk. Built with 24 7-segment flipdigit panels and YOLOv8. " /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/beatboxrevival"> /u/beatboxrevival </a> <br/> <span><a href="https://v.redd.it/beodurindsxd1">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gf9q37/i_made_a_giant_creepy_eye_that_tracks_people/">[comments]</a></span> </td></tr></table>

