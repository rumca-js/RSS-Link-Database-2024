# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Pi5Neo: Easy NeoPixel Control for Raspberry Pi 5
 - [https://www.reddit.com/r/raspberry_pi/comments/1fgys7y/pi5neo_easy_neopixel_control_for_raspberry_pi_5](https://www.reddit.com/r/raspberry_pi/comments/1fgys7y/pi5neo_easy_neopixel_control_for_raspberry_pi_5)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-14T23:18:32+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1fgys7y/pi5neo_easy_neopixel_control_for_raspberry_pi_5/"> <img src="https://external-preview.redd.it/MoP6enMQ2Q6o4o23d5xCmvlBtpeCXWiqxc63UVCX5Rk.jpg?width=216&amp;crop=smart&amp;auto=webp&amp;s=cfd7f76ac4c13cdc287edd9856ef0430dbc862a5" alt="Pi5Neo: Easy NeoPixel Control for Raspberry Pi 5" title="Pi5Neo: Easy NeoPixel Control for Raspberry Pi 5" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/q4tpiystxuod1.jpg?width=3024&amp;format=pjpg&amp;auto=webp&amp;s=066763acce2dd14c9f71750a6136eceb59c33902">RPI 5 with NeoPixel</a></p> <p>Hello everyone! I just released <a href="https://pypi.org/project/Pi5Neo/">Pi5Neo</a> , a Python library to control <strong>NeoPixel LED strips</strong> via the Raspberry Pi 5&#39;s SPI interface. With just a few lines of code, you can create amazing lighting effects like rainbow cycles, loading bars, and more ...</p> <p>This is my first Lib as i was j

## Confused AF, Scl pins not detecing.
 - [https://www.reddit.com/r/raspberry_pi/comments/1fguuxl/confused_af_scl_pins_not_detecing](https://www.reddit.com/r/raspberry_pi/comments/1fguuxl/confused_af_scl_pins_not_detecing)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-14T20:12:26+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1fguuxl/confused_af_scl_pins_not_detecing/"> <img src="https://b.thumbs.redditmedia.com/8mKHO6qvBfWkTNJbs73Kb_CWuywyko3E2wV5nT5YIFo.jpg" alt="Confused AF, Scl pins not detecing." title="Confused AF, Scl pins not detecing." /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Title, I am trying to wire a raspberry pi pico with a mpu6050 on a perfboard. I have checked over and over again. No short circuits, all direct connections, etc. Yet when running code for the mpu6050, it gives me the bad scl pin error. </p> <p><code>from time import sleep</code></p> <p><code>import utime</code></p> <p><code>from imu import MPU6050</code></p> <p><code>from machine import Pin, I2C, PWM</code></p> <p><code>sleep(1)</code></p> <p><code># Initialize I2C and MPU6050</code></p> <p><code>i2c = I2C(0, sda=machine.Pin(11), scl=machine.Pin(10), freq=40000)</code></p> <p><code>imu = MPU6050(i2c)</code></p> <p><code>while True:</code></p> 

## Pi OS: Lock Mouse/Cursor To Window?
 - [https://www.reddit.com/r/raspberry_pi/comments/1fgq4db/pi_os_lock_mousecursor_to_window](https://www.reddit.com/r/raspberry_pi/comments/1fgq4db/pi_os_lock_mousecursor_to_window)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-14T16:33:10+00:00

<!-- SC_OFF --><div class="md"><p>Is it possible to lock the cursor inside a window or lock it to the middle of the screen on a Pi 400 (64bit OS)?</p> <p>I&#39;m trying to play DOS games (in windowed and full screen modes) but the cursor keeps leaving the game window when I move the mouse/cursor towards the edge of the window. Even in full screen mode, the mouse stops responding when the cursor is at the edge of the screen (for example, in first person games) because the cursor still moves behind the game window (and consequently stops at the edge of the game screen in full screen mode or leaves the window in windowed mode).</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AdelmarGames"> /u/AdelmarGames </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fgq4db/pi_os_lock_mousecursor_to_window/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fgq4db/pi_os_lock_mousecursor_to_window/">[co

## What are the best options to make a pi home server stable for the long term.
 - [https://www.reddit.com/r/raspberry_pi/comments/1fgpnci/what_are_the_best_options_to_make_a_pi_home](https://www.reddit.com/r/raspberry_pi/comments/1fgpnci/what_are_the_best_options_to_make_a_pi_home)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-14T16:12:16+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been running home servers on old computers and lately raspberry pis for years. Occasionally, the OS breaks and while I like to tinker it can take time to get everything working again. My current setup includes a pi 4 8GB + 2TB USB SSD running Raspberry Pi OS with: pihole (with a backup on a pi zero W), home assistant, jellyfin, photoprism, tailscale, nextcloud (barely using it) and some custom scripts on cron jobs. In recent years my pis have died after power outages or sometimes just randomly.</p> <p>In your opinion, where should I focus my next stability enhancing project:</p> <ol> <li>better quality SD cards (I buy brand-name cards but those could be counterfeit)</li> <li>boot from USB SSD.</li> <li>UPS</li> <li>scheduled mirroring of the OS partitions (i.e. backup)</li> <li>scheduled replacement of the SD card (yearly?) </li> </ol> <p>I see pros can cons for each, and the options are not exclusive. I&#39;m already using a 2TB USB SSD and 

## Pi Zero W wifi making me go crazy
 - [https://www.reddit.com/r/raspberry_pi/comments/1fgms3z/pi_zero_w_wifi_making_me_go_crazy](https://www.reddit.com/r/raspberry_pi/comments/1fgms3z/pi_zero_w_wifi_making_me_go_crazy)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-14T14:03:01+00:00

<!-- SC_OFF --><div class="md"><p>I have 2 RPi zero w and I cannot get it connected to my wifi in headless setup. I insert same SD card in my Pi 4B and it works fine but not Pi Zero W.</p> <p>Issue started happening when I flashed OS again few hours back. Anyone knows the reason? (I am using same OS I was using before, just flashed for fresh start, I am using pi imager).</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Siddharth1India"> /u/Siddharth1India </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fgms3z/pi_zero_w_wifi_making_me_go_crazy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fgms3z/pi_zero_w_wifi_making_me_go_crazy/">[comments]</a></span>

## Pi HQ camera Aurora Detection/Timelapse
 - [https://www.reddit.com/r/raspberry_pi/comments/1fgmpwe/pi_hq_camera_aurora_detectiontimelapse](https://www.reddit.com/r/raspberry_pi/comments/1fgmpwe/pi_hq_camera_aurora_detectiontimelapse)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-14T14:00:17+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1fgmpwe/pi_hq_camera_aurora_detectiontimelapse/"> <img src="https://b.thumbs.redditmedia.com/o1u312Ofh9eMxGMU1yPOOw6C2D15B-vhGqNo1vWJ94I.jpg" alt="Pi HQ camera Aurora Detection/Timelapse" title="Pi HQ camera Aurora Detection/Timelapse" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I built this app as the northern lights have been visible frequently at my home over the last 12 months and I wanted to be able to accurately identify when they were visible so I could get my camera equipment out and get some photos. The traditional detection methods work well but don&#39;t take cloud and local light pollution into account so are often unreliable. The camera consists of a Pi4+HQ camera and takes an image for Al analysis every 15 minutes. It takes an image for time lapsing every 2 minutes. The images are pushed to a x86 server running the web application and tensorflow for the Al part of the detection. The model wa

## Spotted in the decaying wastelands of the Düsseldorf shopping area.
 - [https://www.reddit.com/r/raspberry_pi/comments/1fgjfpj/spotted_in_the_decaying_wastelands_of_the](https://www.reddit.com/r/raspberry_pi/comments/1fgjfpj/spotted_in_the_decaying_wastelands_of_the)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-14T10:52:02+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1fgjfpj/spotted_in_the_decaying_wastelands_of_the/"> <img src="https://preview.redd.it/7dhedmv09rod1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=76e77535c48aacdb3920126cb6c1b4837823f987" alt="Spotted in the decaying wastelands of the Düsseldorf shopping area." title="Spotted in the decaying wastelands of the Düsseldorf shopping area." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SneerfulToaster"> /u/SneerfulToaster </a> <br/> <span><a href="https://i.redd.it/7dhedmv09rod1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fgjfpj/spotted_in_the_decaying_wastelands_of_the/">[comments]</a></span> </td></tr></table>

## LCD Display Cursor Blinking with Raspberry PI 3
 - [https://www.reddit.com/r/raspberry_pi/comments/1fgirgl/lcd_display_cursor_blinking_with_raspberry_pi_3](https://www.reddit.com/r/raspberry_pi/comments/1fgirgl/lcd_display_cursor_blinking_with_raspberry_pi_3)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-14T10:02:44+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, seeing a strange issue. I have a 3.5 Inch LCD Display <a href="http://www.lcdwiki.com/3.5inch_RPi_Display">http://www.lcdwiki.com/3.5inch_RPi_Display</a></p> <p>the problem is im able to get it working with a Raspberry PI 4 But when i use the same SD Card in Raspberry PI 3 it gets stuck with blinking cursor in top left corner. Pressing Ctrl + Alt + F2 gets me into terminal but not Desktop Mode. I&#39;m using standard Raspberry Power Adapter so there should not be any power issues. Please help</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mrgtaraja"> /u/Mrgtaraja </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fgirgl/lcd_display_cursor_blinking_with_raspberry_pi_3/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fgirgl/lcd_display_cursor_blinking_with_raspberry_pi_3/">[comments]</a></span>

## I made a device to reduce my own Tourette's tics using raspberry pi pico w (hope this is allowed)
 - [https://www.reddit.com/r/raspberry_pi/comments/1fgesxa/i_made_a_device_to_reduce_my_own_tourettes_tics](https://www.reddit.com/r/raspberry_pi/comments/1fgesxa/i_made_a_device_to_reduce_my_own_tourettes_tics)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-14T05:12:25+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1fgesxa/i_made_a_device_to_reduce_my_own_tourettes_tics/"> <img src="https://external-preview.redd.it/8ioKVfwRr0YewUKYvP_Oq5Tnbb3MdClU_BUMue3uUi0.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=0cb053bc29b7efa99576a89f4f2c6aab32f3795f" alt="I made a device to reduce my own Tourette's tics using raspberry pi pico w (hope this is allowed)" title="I made a device to reduce my own Tourette's tics using raspberry pi pico w (hope this is allowed)" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/import_torch-nn"> /u/import_torch-nn </a> <br/> <span><a href="https://www.youtube.com/watch?v=8PB1z6ypj0o">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fgesxa/i_made_a_device_to_reduce_my_own_tourettes_tics/">[comments]</a></span> </td></tr></table>

## headless pi - how to get graphical line characters instead of lowercase letters?
 - [https://www.reddit.com/r/raspberry_pi/comments/1fge8nt/headless_pi_how_to_get_graphical_line_characters](https://www.reddit.com/r/raspberry_pi/comments/1fge8nt/headless_pi_how_to_get_graphical_line_characters)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-14T04:37:51+00:00

<!-- SC_OFF --><div class="md"><p>Linux rpi20 6.1.21-v7+ #1642 SMP Mon Apr 3 17:20:52 BST 2023 armv7l</p> <p>Model B+, running headless, accessing via putty (version 0.8).</p> <p>When I run cgps I have &quot;lqqqqqkxxxxxjm&quot; characters instead of line drawing characters to define the border as seen at:</p> <p><a href="https://miro.medium.com/v2/resize:fit:4800/format:webp/1*hbfmLOtYdHdBT9cJcTjYhw.png">https://miro.medium.com/v2/resize:fit:4800/format:webp/1*hbfmLOtYdHdBT9cJcTjYhw.png</a></p> <p>Very low-stakes post, but what do I need to change so I get ASCII graphical line drawing characters instead of lowercase letters?</p> <p>Inside the putty config, there&#39;s an option under Windows\Translation to &quot;Copy and paste line drawing characters as lqqqk&quot; -- that option is NOT selected.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gruesse98604"> /u/gruesse98604 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments

## 540x960 display over composite from Pi?
 - [https://www.reddit.com/r/raspberry_pi/comments/1fgb325/540x960_display_over_composite_from_pi](https://www.reddit.com/r/raspberry_pi/comments/1fgb325/540x960_display_over_composite_from_pi)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-14T01:32:13+00:00

<!-- SC_OFF --><div class="md"><p>I found a rather oddball <a href="https://www.aliexpress.us/item/3256804532738216.html?spm=a2g0o.detail.pcDetailTopMoreOtherSeller.9.59afBReeBReeQL&amp;gps-id=pcDetailTopMoreOtherSeller&amp;scm=1007.40000.327270.0&amp;scm_id=1007.40000.327270.0&amp;scm-url=1007.40000.327270.0&amp;pvid=58283b9b-7b36-4e11-8cfa-d414348638bc&amp;_t=gps-id:pcDetailTopMoreOtherSeller,scm-url:1007.40000.327270.0,pvid:58283b9b-7b36-4e11-8cfa-d414348638bc,tpp_buckets:668%232846%238113%231998&amp;pdp_npi=4%40dis%21USD%2143.52%2139.60%21%21%21308.00%21280.28%21%402101f08717262765725271260e4886%2112000030222268318%21rec%21US%21174697649%21X&amp;utparam-url=scene%3ApcDetailTopMoreOtherSeller%7Cquery_from%3A">tiny EVF on aliexpress</a> that has a 540x960 resolution over a composite video connection. I&#39;d assumed that this was upscaled from 240p, but a review on another website suggests: </p> <p>&quot;Fantastic little screens! Very clear, work great with the Raspberry Pi CM4 Comp

## Transistor staying open?
 - [https://www.reddit.com/r/raspberry_pi/comments/1fgavq7/transistor_staying_open](https://www.reddit.com/r/raspberry_pi/comments/1fgavq7/transistor_staying_open)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-14T01:21:30+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1fgavq7/transistor_staying_open/"> <img src="https://b.thumbs.redditmedia.com/aj7ETe2oQIh7wEoje5teYuJfXm8Lz8y6cesQjGiHCjY.jpg" alt="Transistor staying open? " title="Transistor staying open? " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I am trying to use a transistor to act as a pwm between a single color passive led strips , to fluctuate current delivered to the led strips in effect altering brightness on command.</p> <p>I am trying to use a transistor to act as a pwm between a single color passive led strips , to fluctuate current delivered to the led strips in effect altering brightness on command,</p> <p>this is pretty much the wiring in the schematic, picture shows it as well. Schematic isn&#39;t the best but it gives a good idea of how transistor pins are rigged up</p> <p>But with everything hooked up I am getting no control , just an open circuit where the led strips stays on until i disconnect ju

