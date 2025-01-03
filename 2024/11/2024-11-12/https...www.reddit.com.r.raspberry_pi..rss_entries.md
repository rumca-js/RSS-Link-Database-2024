# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Official 7" touchscreen on Pi 4 with POE hat not accepting touch input.
 - [https://www.reddit.com/r/raspberry_pi/comments/1gppzke/official_7_touchscreen_on_pi_4_with_poe_hat_not](https://www.reddit.com/r/raspberry_pi/comments/1gppzke/official_7_touchscreen_on_pi_4_with_poe_hat_not)
 - RSS feed: $source
 - date published: 2024-11-12T17:21:27+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to build a kiosk for a business application, so am trying to minimize one-off, unsupported hacks. I am using as much official hardware as possible--Pi 4, official 7&quot; touchscreen, POE+ hat from adafruit. I had the kiosk application working in dev with the touchscreen on a Pi 3, but POE is a requirement for actual deployment. Upgraded to Pi 4 with the POE+ hat, which powers everything up, but the touchscreen functionality is not working. dmesg shows:</p> <p>[ 9.406504] edt_ft5x06 10-0038: touchscreen probe failed</p> <p>[ 9.406997] edt_ft5x06: probe of 10-0038 failed with error -5</p> <p>Googling shows an I2C driver conflict from 2021, and an extremely current memory error. There is a github pull from Linus from 2024 11 03 (a week ago) into v6.12-rc5:</p> <p><a href="https://code.googlesource.com/linux/torvalds/linux/+/295ba6501d2e83b2e66729dc3a7726f80893c920%5E1..295ba6501d2e83b2e66729dc3a7726f80893c920/">https://code.googlesource.com

## RPI 4, after reboot goes mental
 - [https://www.reddit.com/r/raspberry_pi/comments/1gpju7y/rpi_4_after_reboot_goes_mental](https://www.reddit.com/r/raspberry_pi/comments/1gpju7y/rpi_4_after_reboot_goes_mental)
 - RSS feed: $source
 - date published: 2024-11-12T12:42:41+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1gpju7y/rpi_4_after_reboot_goes_mental/"> <img src="https://a.thumbs.redditmedia.com/oQt9oSt271GjiJN3ytTDAuqRetM_cl5xN5unsqDijp8.jpg" alt="RPI 4, after reboot goes mental" title="RPI 4, after reboot goes mental" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/zsu26l07ug0e1.jpg?width=4096&amp;format=pjpg&amp;auto=webp&amp;s=08a3032b1fe8a1810feb5f2181a2214095abcc2f">https://preview.redd.it/zsu26l07ug0e1.jpg?width=4096&amp;format=pjpg&amp;auto=webp&amp;s=08a3032b1fe8a1810feb5f2181a2214095abcc2f</a></p> <p>Hi, after apt full-upgrade and reboot my rpi4B goes mental. it does FS check and then starts dropping these. Tho sometimes it is able to boot for the first time (I do configure it and so on, then reboot, and...). is it my SD card broken or wtf?</p> <p>First time I had issues with removal of X and upgrade at the same aptitude command :D but then I got Kernel Panic... so I did re

## Button activated videoplayer
 - [https://www.reddit.com/r/raspberry_pi/comments/1gpjd63/button_activated_videoplayer](https://www.reddit.com/r/raspberry_pi/comments/1gpjd63/button_activated_videoplayer)
 - RSS feed: $source
 - date published: 2024-11-12T12:16:12+00:00

<!-- SC_OFF --><div class="md"><p>Dear Reddit,</p> <p>I am trying to make a button driven videoplayer. The scrypt should start when the pi boots. I have taken all the steps in tutorials and doing research, but I cant get the srypt started when booted.</p> <p>If i check &#39;&#39;sudo systemctl status vlc_gpio_trigger.service&#39;&#39; It is running, but when the button is pushed nothing happens. If i manually start the scrypt everything works fine.</p> <p>The error I see is that VLC shoud not be run as root. To get this working I tried the following:</p> <p>I created: sudo nano /etc/systemd/system/vlc_gpio_trigger.service</p> <p>In there i have put: </p> <p>[Unit]</p> <p>Description=VLC Video Player via GPIO 17 Trigger</p> <p>After=multi-user.target</p> <p>[Service]</p> <p>ExecStart=/usr/bin/python3 /home/jcd/start1.py</p> <p>User=jcd</p> <p>Group=jcd</p> <p>Restart=always</p> <p>[Install]</p> <p>WantedBy=multi-user.target</p> <p>Although the steps above, it is not working. I am a no

## Issues with Booting RPi4 from USB in 2.0 Port
 - [https://www.reddit.com/r/raspberry_pi/comments/1gpf4oq/issues_with_booting_rpi4_from_usb_in_20_port](https://www.reddit.com/r/raspberry_pi/comments/1gpf4oq/issues_with_booting_rpi4_from_usb_in_20_port)
 - RSS feed: $source
 - date published: 2024-11-12T07:09:20+00:00

<!-- SC_OFF --><div class="md"><p>To prepare, I updated the RPi’s firmware using `rpi-eeprom-update`, selected the &#39;NVMe/USB boot option&#39; in `raspi-config`, and confirmed that `vcgencmd bootloader_config` shows `BOOT_ORDER=0xf14`.</p> <p>The issue is that booting works well when I plug the USB into 3.0 ports, but not in 2.0 ports. I initially tried booting the RPi with the USB inserted in a 2.0 port, and after about 10 minutes, I tried connecting via SSH, only to see a &#39;No route to host&#39; error. Then, when I switched the USB to a 3.0 port, the SSH connection worked immediately. So far, I haven’t noticed any issues with the 3.0 ports.</p> <p>The most frustrating part is that after multiple attempts, I found that booting sometimes works with the USB in the 2.0 ports.</p> <p>I may need more testing to clarify the issue, but what could be causing this? Could it be poor USB port or drive quality, or perhaps a software-related issue? Or could it just be temporary?</p> </div>

## RPI 4B w/Wayland, VNC and TigerVNC client, the | (pipe) shows up as ~ (Tilda)
 - [https://www.reddit.com/r/raspberry_pi/comments/1gp8vcd/rpi_4b_wwayland_vnc_and_tigervnc_client_the_pipe](https://www.reddit.com/r/raspberry_pi/comments/1gp8vcd/rpi_4b_wwayland_vnc_and_tigervnc_client_the_pipe)
 - RSS feed: $source
 - date published: 2024-11-12T01:14:41+00:00

<!-- SC_OFF --><div class="md"><p>In the USA. </p> <p>If I ssh into my RPI 4B, everything works perfectly.</p> <p>But when I use a VNC (TigerVNC client), pressing &quot;|&quot; key causes a &quot;~&quot; to show up.</p> <p>I&#39;ve dig into this, there&#39;s several posts but non help. I&#39;ve got my locate set correctly.</p> <p>altan@retriever:~ $ localectl status</p> <p><code>System Locale: LANG=en_US.UTF-8</code></p> <p><code>VC Keymap: (unset)</code> </p> <p><code>X11 Layout: gb</code></p> <p><code>X11 Model: pc105</code></p> <p>But I see the X11 layout is gb -- nothing seems to change that . Not sure if it&#39;s the cause. Yes, I&#39;ve used the RPI config and set the local.</p> <p>Any tips?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/madmyersreal"> /u/madmyersreal </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gp8vcd/rpi_4b_wwayland_vnc_and_tigervnc_client_the_pipe/">[link]</a></span> &#32; <span><a href="ht

## 2024 Nov 11 Stickied -FAQ- & -HELPDESK- thread - Boot problems? Power supply problems? Display problems? Networking problems? Need ideas? Get help with these and other questions!
 - [https://www.reddit.com/r/raspberry_pi/comments/1gp86xd/2024_nov_11_stickied_faq_helpdesk_thread_boot](https://www.reddit.com/r/raspberry_pi/comments/1gp86xd/2024_nov_11_stickied_faq_helpdesk_thread_boot)
 - RSS feed: $source
 - date published: 2024-11-12T00:42:23+00:00

<!-- SC_OFF --><div class="md"><h3><a href="http://f2z.net/RPi-Helpdesk-FAQ.png">Welcome to the r/raspberry_pi Helpdesk and Frequently Asked Questions!</a></h3> <p><a href="https://www.reddit.com/r/raspberry_pi/comments/1gjtqt7/2024_nov_4_stickied_faq_helpdesk_thread_boot/">Link to last week&#39;s thread</a></p> <p>Having a hard time searching for answers to your Raspberry Pi questions? Let the <a href="/r/raspberry_pi">r/raspberry_pi</a> community members search for answers <em>for you</em>!<sup>†</sup> Looking for help getting started with a project? Have a question that you need answered? Was it not answered last week? Did not get a satisfying answer? A question that you&#39;ve only done basic research for? Maybe something you think everyone but you knows? <strong>Ask your question in the comments on this page,</strong> operators are standing by!</p> <p>This helpdesk and idea thread is here so that the front page won&#39;t be filled with these same questions day in and day out:</p

