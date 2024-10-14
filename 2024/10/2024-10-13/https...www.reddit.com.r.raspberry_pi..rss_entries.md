# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Airport using a raspberry pi and powerpoint for anouncements
 - [https://www.reddit.com/r/raspberry_pi/comments/1g324z9/airport_using_a_raspberry_pi_and_powerpoint_for](https://www.reddit.com/r/raspberry_pi/comments/1g324z9/airport_using_a_raspberry_pi_and_powerpoint_for)
 - RSS feed: $source
 - date published: 2024-10-13T22:57:50+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Sjoerd2006Daal"> /u/Sjoerd2006Daal </a> <br/> <span><a href="https://youtube.com/shorts/DTsfyxrVFWA?si=O6p3tpFSwtUZxJ38">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1g324z9/airport_using_a_raspberry_pi_and_powerpoint_for/">[comments]</a></span>

## I used a Pi Zero W (BlueSCSI) to emulate an Ethernet adapter and surf the web on a 1986 Macintosh Plus
 - [https://www.reddit.com/r/raspberry_pi/comments/1g2x0z1/i_used_a_pi_zero_w_bluescsi_to_emulate_an](https://www.reddit.com/r/raspberry_pi/comments/1g2x0z1/i_used_a_pi_zero_w_bluescsi_to_emulate_an)
 - RSS feed: $source
 - date published: 2024-10-13T19:01:09+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1g2x0z1/i_used_a_pi_zero_w_bluescsi_to_emulate_an/"> <img src="https://external-preview.redd.it/N5Nq7kVOIa52Kz4O6SZnpBt3SQh9uC3qCZUhVgSQ6QI.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=868835681e0d08e8086f8d3467d637f2bee2cc14" alt="I used a Pi Zero W (BlueSCSI) to emulate an Ethernet adapter and surf the web on a 1986 Macintosh Plus" title="I used a Pi Zero W (BlueSCSI) to emulate an Ethernet adapter and surf the web on a 1986 Macintosh Plus" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/troutyogurtmachine"> /u/troutyogurtmachine </a> <br/> <span><a href="https://youtu.be/f1v1gWLHcOk">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1g2x0z1/i_used_a_pi_zero_w_bluescsi_to_emulate_an/">[comments]</a></span> </td></tr></table>

## Speaker noise interference problem
 - [https://www.reddit.com/r/raspberry_pi/comments/1g2wekl/speaker_noise_interference_problem](https://www.reddit.com/r/raspberry_pi/comments/1g2wekl/speaker_noise_interference_problem)
 - RSS feed: $source
 - date published: 2024-10-13T18:34:04+00:00

<!-- SC_OFF --><div class="md"><p>I am using a MAX98306 and Pi Zero to play audio through 4ohm 3W speakers. There’s a constant hissing and crackling if I connect the amp input to the PWM pins on the pi. Audio will play as expected but not without this constant volume interference. When I connect both the L- and L+ to ground I don&#39;t get any noise so I don&#39;t think the amp is borked.</p> <p>When it’s connected to the Pi, the electrical feedback / noise spikes when SD card or WiFi activity happens. I have tried separate power sources for the amp + connecting ground of both to no avail.</p> <p>My next steps ideas is to try using ferrite beads on the PWM output wires or adding a low pass filter?</p> <p>Do you think the jumpers are the cause and I should be using shielded cables?</p> <p>Am I missing something? New to electronics, I appreciate your time!</p> <p>Wiring: <a href="https://imgur.com/a/e0FFkNE">https://imgur.com/a/e0FFkNE</a></p> <p>Video of noise: <a href="https://imgur.c

## Sticking With PiOS Bookworm On RPi5 and ROS 2 Humble in Docker - October 2024
 - [https://www.reddit.com/r/raspberry_pi/comments/1g2tetd/sticking_with_pios_bookworm_on_rpi5_and_ros_2](https://www.reddit.com/r/raspberry_pi/comments/1g2tetd/sticking_with_pios_bookworm_on_rpi5_and_ros_2)
 - RSS feed: $source
 - date published: 2024-10-13T16:22:33+00:00

<!-- SC_OFF --><div class="md"><p>A year ago, I got my first Pi5 to upgrade my GoPiGo3 ROS 2 Humble robot&#39;s Pi4. At that time, only Ubuntu 23 was available for the Pi5 which was not a supported ROS 2 platform, and with the Pi5 being so new, I decided the PiOS 64-bit Bookworm Desktop would be the best supported OS for the Pi5. </p> <p>I rebuilt my robot with PiOS for the Pi5, and put ROS 2 Humble / Ubuntu 22 in a Docker container. Other than Docker being a total configuration nightmare, I got it all working - the RTC, sleeping, WiFi, and VNC Server in PiOS, with my ROS 2 nodes in Docker able to access shared disk, audio, wireless, joystick, USB, WiFi, and my robot&#39;s hardware through the GPIO SPI and I2C devices. </p> <p>My robot has been &quot;living&quot; well in this configuration for the last year, docking when needed and going out to play for 2.8 hours after the battery has been recharged. </p> <p>With the release of ROS 2 Jazzy and Ubuntu 24.04 for the Raspberry Pi, I wond

## How do I use PyAuotGUI on my Pi 5?
 - [https://www.reddit.com/r/raspberry_pi/comments/1g2rivl/how_do_i_use_pyauotgui_on_my_pi_5](https://www.reddit.com/r/raspberry_pi/comments/1g2rivl/how_do_i_use_pyauotgui_on_my_pi_5)
 - RSS feed: $source
 - date published: 2024-10-13T14:58:46+00:00

<!-- SC_OFF --><div class="md"><p>So I got past installation, and I wrote this code to repeatedly carry out a Discord command:</p> <pre><code>import pyautogui as pg from time import sleep as s s(10) for i in range (11): for i in range(50): pg.typewrite(&#39;/roll&#39;) pg.press(&#39;enter&#39;) pg.press(&#39;enter&#39;) </code></pre> <p>However, when I go to the entry field on Discord, nothing happens. In fact, the programs doesn&#39;t type anything anywhere, other than in Thonny. I spent several hours trying to figure out what&#39;s wrong. Can anyone help?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kingmudbeard"> /u/kingmudbeard </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1g2rivl/how_do_i_use_pyauotgui_on_my_pi_5/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1g2rivl/how_do_i_use_pyauotgui_on_my_pi_5/">[comments]</a></span>

## Raspberrry Pi HAT with 7 Segment Display and STM32 MCU
 - [https://www.reddit.com/r/raspberry_pi/comments/1g2om2c/raspberrry_pi_hat_with_7_segment_display_and](https://www.reddit.com/r/raspberry_pi/comments/1g2om2c/raspberrry_pi_hat_with_7_segment_display_and)
 - RSS feed: $source
 - date published: 2024-10-13T12:32:24+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/sinnaaann"> /u/sinnaaann </a> <br/> <span><a href="https://www.reddit.com/gallery/1g2om2c">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1g2om2c/raspberrry_pi_hat_with_7_segment_display_and/">[comments]</a></span>

## Putting together my Raspberry Pi based handheld console PiGo in under 5 minutes. (Video is sped up)
 - [https://www.reddit.com/r/raspberry_pi/comments/1g2nkmq/putting_together_my_raspberry_pi_based_handheld](https://www.reddit.com/r/raspberry_pi/comments/1g2nkmq/putting_together_my_raspberry_pi_based_handheld)
 - RSS feed: $source
 - date published: 2024-10-13T11:28:59+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1g2nkmq/putting_together_my_raspberry_pi_based_handheld/"> <img src="https://external-preview.redd.it/emtkZmd5eTBlaXVkMQ0HXadIo3nFl6HRW_TEnXjLHN4EkTPOt_ovPPTrKoQg.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=1a6af9cb84af8b2bf236e63b36c080b679a709a2" alt="Putting together my Raspberry Pi based handheld console PiGo in under 5 minutes. (Video is sped up)" title="Putting together my Raspberry Pi based handheld console PiGo in under 5 minutes. (Video is sped up)" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/daviel32"> /u/daviel32 </a> <br/> <span><a href="https://v.redd.it/ejmgwwy0eiud1">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1g2nkmq/putting_together_my_raspberry_pi_based_handheld/">[comments]</a></span> </td></tr></table>

## Shutdowns and undervolting with raspberry pi 3B
 - [https://www.reddit.com/r/raspberry_pi/comments/1g2fl7l/shutdowns_and_undervolting_with_raspberry_pi_3b](https://www.reddit.com/r/raspberry_pi/comments/1g2fl7l/shutdowns_and_undervolting_with_raspberry_pi_3b)
 - RSS feed: $source
 - date published: 2024-10-13T02:13:21+00:00

<!-- SC_OFF --><div class="md"><p>is this a common issue and how do i fix it? tried every cable and brick, does it need a specific cable or brick? what&#39;s recommended?</p> <p>the best I have is no undervolting when I get into RetroPie but undervolting in games.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/EpicAppraiser"> /u/EpicAppraiser </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1g2fl7l/shutdowns_and_undervolting_with_raspberry_pi_3b/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1g2fl7l/shutdowns_and_undervolting_with_raspberry_pi_3b/">[comments]</a></span>

