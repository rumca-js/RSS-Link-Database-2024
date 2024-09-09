# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Cleanest raspberry pi battlestation ~$100
 - [https://www.reddit.com/r/raspberry_pi/comments/1fcawxw/cleanest_raspberry_pi_battlestation_100](https://www.reddit.com/r/raspberry_pi/comments/1fcawxw/cleanest_raspberry_pi_battlestation_100)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-08T23:04:12+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1fcawxw/cleanest_raspberry_pi_battlestation_100/"> <img src="https://preview.redd.it/zsnytzjn1ond1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=d4114d15fbc9feaedb91b2864955b032c89e5aa1" alt="Cleanest raspberry pi battlestation ~$100 " title="Cleanest raspberry pi battlestation ~$100 " /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/beanlord564"> /u/beanlord564 </a> <br/> <span><a href="https://i.redd.it/zsnytzjn1ond1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fcawxw/cleanest_raspberry_pi_battlestation_100/">[comments]</a></span> </td></tr></table>

## Button to Stop System Not Working When Using Timers
 - [https://www.reddit.com/r/raspberry_pi/comments/1fca28j/button_to_stop_system_not_working_when_using](https://www.reddit.com/r/raspberry_pi/comments/1fca28j/button_to_stop_system_not_working_when_using)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-08T22:23:48+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;m trying to perform the following activity:</p> <p>Create an Alarm System using your Raspberry Pi with the following features:</p> <ul> <li>Use a motion sensor to activate a buzzer and a sequence of LEDs.</li> <li>There should be at least 5 LEDs.</li> <li>The user should be able to choose the sequence in which the LEDs light up using buttons, and it is preferable to use 2 or more different colors of LEDs.</li> <li>The buzzer should turn on intermittently, meaning it should be on for 5 seconds, off for 2 seconds, then turn back on for 5 seconds, and repeat this sequence until a button is pressed to turn it off.</li> </ul> <p>The problem is that I can&#39;t get the button to turn off the system to work. What can I do? Curiously, the button only stops working when the LED sequence has some kind of timer, whether it&#39;s <code>sleep</code> or any other variant.</p> <p>Here is my code:</p> <p><code>from gpiozero import LED, Button, MotionSensor<

## Rpi5 with LiPo battery
 - [https://www.reddit.com/r/raspberry_pi/comments/1fc185i/rpi5_with_lipo_battery](https://www.reddit.com/r/raspberry_pi/comments/1fc185i/rpi5_with_lipo_battery)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-08T16:02:24+00:00

<!-- SC_OFF --><div class="md"><p>Hi all</p> <p>I guess this has been asked a thousand times by now; &quot;how do I power my Rpi with a Lipo battery?&quot;. It sort of relates to Q3 in the FAQ, but with a battery. I have found information, i.e. convert to 5V via e.g. a buck/boost converter and then supply the board with that, but I&#39;m still unsure about what the Rpi &quot;thinks of its input voltage&quot;. When it receives 5V input, how does it &quot;check&quot; it? Is it only going to low-power mode if it notices that its input voltage is decreasing as the current draw increases?</p> <p>How do I make sure that it doesn&#39;t go into low-power mode? Is there some functionality going on when using the standard 27W PSU such that the board knows how much current can be supplied, or is it just a &quot;good 5V supply&quot;? Is there a way to force the &quot;Rpi into standard power mode&quot;? As long as I select a buck converter suitable for the currents (5A+) and maybe add some big cap

## Can't boot on NVMe drive
 - [https://www.reddit.com/r/raspberry_pi/comments/1fbsfrr/cant_boot_on_nvme_drive](https://www.reddit.com/r/raspberry_pi/comments/1fbsfrr/cant_boot_on_nvme_drive)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-08T07:44:05+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1fbsfrr/cant_boot_on_nvme_drive/"> <img src="https://b.thumbs.redditmedia.com/u7Ev8kRErp5V0c8joWa2eFVWsVFsisiHboohOxHR4mk.jpg" alt="Can't boot on NVMe drive" title="Can't boot on NVMe drive" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Trying to boot a raspberry pi 5 on an NVMe ssd connected with the 52Pi M.2 Adapter N04, I did all the recommended config for boot and I prepared the drive with Pi Imager from the Pi OS installed on the SD Card. After changing the boot order in the eeprom and restarting, the Pi hangs for some time and then displays the following screen from BusyBox.. </p> <p>Anyone knows how to fix that?<br/> I&#39;ll buy you a beer! :D</p> <p><a href="https://preview.redd.it/465nlyarhjnd1.jpg?width=3547&amp;format=pjpg&amp;auto=webp&amp;s=d491df7eca64964271a3a1144feeb19071191dca">BusyBox error</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/polanri"

## Pico and ili9341 without gnd connected to display
 - [https://www.reddit.com/r/raspberry_pi/comments/1fbran4/pico_and_ili9341_without_gnd_connected_to_display](https://www.reddit.com/r/raspberry_pi/comments/1fbran4/pico_and_ili9341_without_gnd_connected_to_display)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-08T06:22:06+00:00

<!-- SC_OFF --><div class="md"><p>Hi I have a TFT connected to my pico, but it have no bl pin to control brightness and software commands don&#39;t work... But, I have noticed that if I disconnect the ground pin from the display it I still works fine, but with much less bright and using much less current, the pico and the display is using 10ma vs 24ma with ground connected without sleep My question is,</p> <ol> <li>this can damage the pico or the display?</li> <li>Can I connect the gnd to a MOSFET to pwm the bridge?</li> </ol> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/staltux"> /u/staltux </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fbran4/pico_and_ili9341_without_gnd_connected_to_display/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fbran4/pico_and_ili9341_without_gnd_connected_to_display/">[comments]</a></span>

## Pi 4 with hdmi monitor
 - [https://www.reddit.com/r/raspberry_pi/comments/1fbmbrr/pi_4_with_hdmi_monitor](https://www.reddit.com/r/raspberry_pi/comments/1fbmbrr/pi_4_with_hdmi_monitor)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-08T01:18:21+00:00

<!-- SC_OFF --><div class="md"><p>tldr; If my desktop is asleep and not using the monitor, I can connect the pi over hdmi. If my desktop is awake, my monitor does not even see a signal from the pi and I cannot toggle from display port to hdmi. </p> <p>First time dipping my toes into Raspberry Pi. I have a Pi 4, installed, I can SSH into it, I can VNC into it. I am trying to connect to the monitor my desktop pc uses, which has a display port and 2 hdmi inputs. </p> <p>my desktop uses the displayport. i have the pi using hdmi 0, closest to the usb c power input. </p> <p>I&#39;ve done this with other devices, such as a laptop connected to HDMI, so I can toggle between laptop using the monitor or desktop using the monitor. </p> <p>I&#39;m kind of stuck on what to try. I&#39;ve tried a bunch of combinations of config.txt if that&#39;s still the right place to be trying. Here is where I am now. </p> <p><code>dtoverlay=vc4-kms-v3d</code><br/> <code>max_framebuffers=2</code><br/> <code>hdmi_f

## Is it normal to have missing options in the raspi-config when running a pi5 with the lite version of raspios?
 - [https://www.reddit.com/r/raspberry_pi/comments/1fblda5/is_it_normal_to_have_missing_options_in_the](https://www.reddit.com/r/raspberry_pi/comments/1fblda5/is_it_normal_to_have_missing_options_in_the)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-08T00:27:16+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I noticed that with a clean install of Raspberry Pi OS Lite (64-bit), my Raspberry Pi 5 loses a lot of options from raspi-config, and worse, the fan from the cooling addon doesn&#39;t seem to turn on. I thought I messed up my installation earlier, but I did a new clean install and checked raspi-config, and yes, lots of options were missing, like fan/overclock/etc. in the performance section. I did the usual upgrade and updates, and they still aren&#39;t there.<br/> Do I really need to download a version with the desktop environment if I want those options?</p> <p>Edit, installed a desktop version (32 bit) and the performance section still only shows p2 and p4 options, no fan, overclock, etc.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Rubfer"> /u/Rubfer </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fblda5/is_it_normal_to_have_missing_options_in_the/">[link]</a></span> &#32; 

