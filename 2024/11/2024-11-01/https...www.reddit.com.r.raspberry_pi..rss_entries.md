# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Empty files created automatically in home directory
 - [https://www.reddit.com/r/raspberry_pi/comments/1ghc7sh/empty_files_created_automatically_in_home](https://www.reddit.com/r/raspberry_pi/comments/1ghc7sh/empty_files_created_automatically_in_home)
 - RSS feed: $source
 - date published: 2024-11-01T18:23:58+00:00

<!-- SC_OFF --><div class="md"><p>I have a raspberry pi 5 with bookworm installed, and in the last two days it has been creating some strange files with $ backslash and numbers in the home directory (ls output below) </p> <pre><code>&#39;&#39;$&#39;\231\377\177&#39; configs mysocatscript.sh socat-init &#39;&#39;$&#39;\215\377\177&#39; Desktop mysocatscript.sh~ some_job.err &#39;&#39;$&#39;\377\177&#39; docker Pictures take_photo.py &#39;&#39;$&#39;\b\377\177&#39; Documents Public temp2domoticz.py &#39;&#39;$&#39;\025\377\177&#39; domoticz &#39;s&#39;$&#39;\377\177&#39; temp2domoticz.py~ Bookshelf Downloads servo1.py Templates Capture_photo_old.py dynudns servo2.py test.jpg Capture_photo.py keys servo_arm_old.py Videos Capture_photo.py~ Music servo_arm.py zigbee2mqtt </code></pre> <p>The files have no size and are empty; I&#39;ve opened one file and had nothing in it. I&#39;m only bothered in the sense that it could be masking some other/larger issue... ls -ltr indicates that these fi

## Help with Pi-16 ADC by alchemy power
 - [https://www.reddit.com/r/raspberry_pi/comments/1gha2qd/help_with_pi16_adc_by_alchemy_power](https://www.reddit.com/r/raspberry_pi/comments/1gha2qd/help_with_pi16_adc_by_alchemy_power)
 - RSS feed: $source
 - date published: 2024-11-01T16:52:32+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone. I&#39;m trying to use a Pi-16 ADC to read out a the voltage across a resistor. I have no trouble reading the output from a power supply, either in single ended mode or in differential mode, but, when I try to actually use it for the readout that I need, the reading is completely messed up (I&#39;m reading 2 volts across a resistor through which no current is passing). </p> <p>I reckon it might be some issue with ground loops, but I can&#39;t really seem to eliminate it.</p> <p>Reading with a multimeter the voltage between the positive and negative input and ground, the one between positive and ground is correct, and there is about a 200 mV offset between negative and ground. I tried providing a path from negative to ground, but it has solved nothing.</p> <p>For more context, I&#39;m using a power supply to pass a current through something, and I want to monitor it continuously by reading the voltage drop across a resistor. The negative i

## RPI5 HAT - MiniPCIe Signalling
 - [https://www.reddit.com/r/raspberry_pi/comments/1gh82g6/rpi5_hat_minipcie_signalling](https://www.reddit.com/r/raspberry_pi/comments/1gh82g6/rpi5_hat_minipcie_signalling)
 - RSS feed: $source
 - date published: 2024-11-01T15:28:21+00:00

<!-- SC_OFF --><div class="md"><p>Hi Folks,</p> <p>I have a use case where I&#39;m using an RPI5 2GB as a wireless client in my camper van. I have an antenna mounted to the roof and an RPI inside. I&#39;m having some difficulties making another wireless card work properly.</p> <p>I&#39;ve gone the route of purchasing a Mini PCIe card from ASIA RF. Specifically, the <a href="https://asiarf.com/product/wi-fi-6-11ax-2x2-dbdc-1800mbps-mini-pcie-module-mt7915-aw7915-npd/">AW7915-NPD</a>. It&#39;s 2T2R like my antenna, supports AP/station mode and the like in OpenWRT. That&#39; and it has great transmit power.</p> <p>I purchased a <a href="https://www.waveshare.com/pcie-to-minipcie-gbe-usb3.2-hat-plus.htm">HAT</a> from Waveshare to house this card. The documentation on this HAT is a little shaky at best. Ultimately, I think this was a mistake. From what I read, MiniPCIe can be setup with either PCI or USB signaling. I believe this HAT is wired up with the latter(USB) and thus incompatible.

## Here's my Raspberry PI case
 - [https://www.reddit.com/r/raspberry_pi/comments/1gh7sb9/heres_my_raspberry_pi_case](https://www.reddit.com/r/raspberry_pi/comments/1gh7sb9/heres_my_raspberry_pi_case)
 - RSS feed: $source
 - date published: 2024-11-01T15:16:02+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1gh7sb9/heres_my_raspberry_pi_case/"> <img src="https://b.thumbs.redditmedia.com/rM7V7NcCRiCO5UFFUAavPn3l4DrsXNm-4zmGgzJz4cs.jpg" alt="Here's my Raspberry PI case" title="Here's my Raspberry PI case" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Minimum_Tradition701"> /u/Minimum_Tradition701 </a> <br/> <span><a href="https://www.reddit.com/gallery/1gh7sb9">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gh7sb9/heres_my_raspberry_pi_case/">[comments]</a></span> </td></tr></table>

## Raspberry Pi 5 screen showing incorrect colors after reboot - any ideas?
 - [https://www.reddit.com/r/raspberry_pi/comments/1gh2aic/raspberry_pi_5_screen_showing_incorrect_colors](https://www.reddit.com/r/raspberry_pi/comments/1gh2aic/raspberry_pi_5_screen_showing_incorrect_colors)
 - RSS feed: $source
 - date published: 2024-11-01T10:32:47+00:00

<!-- SC_OFF --><div class="md"><p>Having an odd issue with my display (HyperPixel 4.0) on a Raspberry Pi 5. As you can see in the image, the colors are completely wrong on the physical screen (right) compared to the VNC viewer (left). The standard color bars should show the same colors on both displays, but the screen is displaying different colors - for example, the red bar is showing as orange, and the magenta appears as purple.</p> <p>Everything was working fine initially, but this started happening after a few reboots. I haven&#39;t made any changes to the configuration. I&#39;ve tested with a couple other displays I have around and they all show the same incorrect colors on this Pi, so it seems to be a system-wide issue rather than a problem with one specific screen. Interestingly, when I tested the same HyperPixel 4.0 on a different Pi 5, the colors displayed normally, which suggests the issue might be with this specific Pi unit.</p> <p>Has anyone encountered this issue or know

## Piezo knock sensor readings all over the place?
 - [https://www.reddit.com/r/raspberry_pi/comments/1gh06cc/piezo_knock_sensor_readings_all_over_the_place](https://www.reddit.com/r/raspberry_pi/comments/1gh06cc/piezo_knock_sensor_readings_all_over_the_place)
 - RSS feed: $source
 - date published: 2024-11-01T07:46:50+00:00

<!-- SC_OFF --><div class="md"><p>Hello all, I&#39;m having quite alot of trouble with a recent project I&#39;m working on, I&#39;m trying to make an electronic drum using a piezo as a knock sensor. I&#39;ve ran into an issue where the piezo readings make absolutely no sense at all. When i look at the readings it seems that they climb to max, stick there for a while then go down to 0, stick there for a while and repeat, all of this happens without me going anywhere near the piezo or touching it. I should add I&#39;ve tried connecting the piezo with a 1M ohm resistor in parallel and that has not changed much. Any help is much appreciated as this has gotten me pulling my hair out.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ReQTeCH"> /u/ReQTeCH </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gh06cc/piezo_knock_sensor_readings_all_over_the_place/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberr

## Geerling’s like “ I remember my first beer”
 - [https://www.reddit.com/r/raspberry_pi/comments/1ggviul/geerlings_like_i_remember_my_first_beer](https://www.reddit.com/r/raspberry_pi/comments/1ggviul/geerlings_like_i_remember_my_first_beer)
 - RSS feed: $source
 - date published: 2024-11-01T02:29:33+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1ggviul/geerlings_like_i_remember_my_first_beer/"> <img src="https://preview.redd.it/zvqosqrdb7yd1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=a92ec6cacf581ec92a844fe34692355c90a9bc30" alt="Geerling’s like “ I remember my first beer”" title="Geerling’s like “ I remember my first beer”" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Low_Kick_626"> /u/Low_Kick_626 </a> <br/> <span><a href="https://i.redd.it/zvqosqrdb7yd1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ggviul/geerlings_like_i_remember_my_first_beer/">[comments]</a></span> </td></tr></table>

