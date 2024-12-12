# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## My first Pico build!
 - [https://www.reddit.com/r/raspberry_pi/comments/1hc4uis/my_first_pico_build](https://www.reddit.com/r/raspberry_pi/comments/1hc4uis/my_first_pico_build)
 - RSS feed: $source
 - date published: 2024-12-11T21:38:59+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1hc4uis/my_first_pico_build/"> <img src="https://a.thumbs.redditmedia.com/EiLfOGbNTNMA30ozG9vBlWGbNDnjhEsdAjM8EHqmMs4.jpg" alt="My first Pico build!" title="My first Pico build!" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/1p5m4h8ega6e1.png?width=921&amp;format=png&amp;auto=webp&amp;s=cf0974daa80a152607df5a34f89e5d79aa349470">https://preview.redd.it/1p5m4h8ega6e1.png?width=921&amp;format=png&amp;auto=webp&amp;s=cf0974daa80a152607df5a34f89e5d79aa349470</a></p> <p>Running on a Pi Pico W, it monitors an LED header on a motherboard in a coin machine in a laundromat. When the LED turns on it sends a text to the owner to refill the coin machine. My first time playing with resistors as I had to step down the 14v from the header to 3.3v that the Pico could use.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RobertDCBrown"> /u/RobertDCBrown 

## dev-dri-card0.device and dev-dri-renderD128.device errors, and a ton more fun!
 - [https://www.reddit.com/r/raspberry_pi/comments/1hc38pg/devdricard0device_and_devdrirenderd128device](https://www.reddit.com/r/raspberry_pi/comments/1hc38pg/devdricard0device_and_devdrirenderd128device)
 - RSS feed: $source
 - date published: 2024-12-11T20:30:45+00:00

<!-- SC_OFF --><div class="md"><p>As the title said, I am getting &quot;dev-dri-card0.device&quot; load error, and &quot;dev-dri-renderD128.device&quot; load error. Now, right before this, I was messing around with <a href="http://koboldcpp.py">koboldcpp.py</a>, and when I maximized the browser window, the taskbar disappeared. I figured something just got toggled wrong, and it was either just out of site, (Not the case), or maybe my screen size got changed in the settings somehow, (not the case), so I figured I&#39;d reboot. Then I started getting those errors on reboot. So I figured I&#39;d check the rpi-eeprom-config... It was missing. Tried raspi-config... missing. Luckily when it rebooted, it was booting to a command prompt, so I did the old,</p> <p><code>sudo apt update</code></p> <p>then</p> <p><code>sudo apt upgrade</code></p> <p>Still didn&#39;t fix anything, so I reinstalled raspi-config, was able to get in there. Everything looked okay, still was booting in the order SD, SS

## I created a stand to have my raspberry pi 5 on my new Raspberry pi Monitor... and you can too if you have a 3d printer
 - [https://www.reddit.com/r/raspberry_pi/comments/1hc36ii/i_created_a_stand_to_have_my_raspberry_pi_5_on_my](https://www.reddit.com/r/raspberry_pi/comments/1hc36ii/i_created_a_stand_to_have_my_raspberry_pi_5_on_my)
 - RSS feed: $source
 - date published: 2024-12-11T20:28:09+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1hc36ii/i_created_a_stand_to_have_my_raspberry_pi_5_on_my/"> <img src="https://preview.redd.it/xqbijygf3a6e1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=4b703d8ecb60678d9f7a9792fa75e87612525049" alt="I created a stand to have my raspberry pi 5 on my new Raspberry pi Monitor... and you can too if you have a 3d printer" title="I created a stand to have my raspberry pi 5 on my new Raspberry pi Monitor... and you can too if you have a 3d printer" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/eracoon"> /u/eracoon </a> <br/> <span><a href="https://i.redd.it/xqbijygf3a6e1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hc36ii/i_created_a_stand_to_have_my_raspberry_pi_5_on_my/">[comments]</a></span> </td></tr></table>

## Picamera2 Total Blackout?
 - [https://www.reddit.com/r/raspberry_pi/comments/1hbx5vu/picamera2_total_blackout](https://www.reddit.com/r/raspberry_pi/comments/1hbx5vu/picamera2_total_blackout)
 - RSS feed: $source
 - date published: 2024-12-11T16:19:23+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1hbx5vu/picamera2_total_blackout/"> <img src="https://b.thumbs.redditmedia.com/UaW8X48ooI_xfN_cuD3OjrVAzo_Fjcecka_9Put2Hdg.jpg" alt="Picamera2 Total Blackout? " title="Picamera2 Total Blackout? " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><em>TL;DR; - my picams all suddenly stopped being detectable at once, even for new hardware. Does anyone know of an external &quot;thing&quot; (like a signal) that could interfere with a picam being detected by the RP?</em></p> <p>So I have been working on a project for a while involving a Raspberry Pi 4 Model B and a Picamera module v2.1. Had no issues installing the camera initially several months ago and everything worked great since.</p> <p>Recently I loaded up my program for the first time in a week, <strong>but the camera wasn&#39;t found</strong>. </p> <p>After some fiddling, I figured that the camera got broke and replaced it with a new out-of-the-box picamera2

## Have to reconnect hdmi from projector to RPi for it to work
 - [https://www.reddit.com/r/raspberry_pi/comments/1hbtdr9/have_to_reconnect_hdmi_from_projector_to_rpi_for](https://www.reddit.com/r/raspberry_pi/comments/1hbtdr9/have_to_reconnect_hdmi_from_projector_to_rpi_for)
 - RSS feed: $source
 - date published: 2024-12-11T13:24:38+00:00

<!-- SC_OFF --><div class="md"><p>I have an aiptek i70 projector. If I power it and after 20 seconds (or more) connect my RPi it works.</p> <p>But if they power on at the same time or reverse order, then the projector doesn&#39;t register it and displays its default pic. </p> <p>Then I have to reconnect the hdmi on one of them to make it work, but I don&#39;t want to do this. I want automatic recognition in whatever order I power them.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/salehrayan246"> /u/salehrayan246 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hbtdr9/have_to_reconnect_hdmi_from_projector_to_rpi_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hbtdr9/have_to_reconnect_hdmi_from_projector_to_rpi_for/">[comments]</a></span>

## Raspberry Pi 4 B TouchScreen not working
 - [https://www.reddit.com/r/raspberry_pi/comments/1hbilwk/raspberry_pi_4_b_touchscreen_not_working](https://www.reddit.com/r/raspberry_pi/comments/1hbilwk/raspberry_pi_4_b_touchscreen_not_working)
 - RSS feed: $source
 - date published: 2024-12-11T01:57:27+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1hbilwk/raspberry_pi_4_b_touchscreen_not_working/"> <img src="https://b.thumbs.redditmedia.com/ilHu9JVKTd_m9KT1Tv7NZTA0wHVzd2zFKXcmGDC3JwI.jpg" alt="Raspberry Pi 4 B TouchScreen not working" title="Raspberry Pi 4 B TouchScreen not working" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I&#39;ve been working on this all day. The touchscreen doesnt not work.</p> <p>I&#39;ve tried different techniques.<br/> 1. I added some script into my config.txt file</p> <pre><code>max_usb_current=1 hdmi_force_hotplug=1 config_hdmi_boost=7 hdmi_group=2 hdmi_mode=1 hdmi_mode=87 hdmi_drive=1 display_rotate=0 hdmi_cvt 1024 600 60 6 0 0 0 </code></pre> <ol> <li>I&#39;ve added the 64 bit Raspberry OS, and then did step 1 again.</li> </ol> <p>Nothing worked not sure what to do.</p> <p><a href="https://preview.redd.it/v7xjf78xl46e1.jpg?width=4656&amp;format=pjpg&amp;auto=webp&amp;s=2032237fa25ee14f1b9771f555a2f08fb0b62f53">https:/

