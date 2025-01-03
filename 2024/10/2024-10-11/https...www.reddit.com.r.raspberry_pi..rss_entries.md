# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## SPI Pressure Sensor Struggles
 - [https://www.reddit.com/r/raspberry_pi/comments/1g1hv9d/spi_pressure_sensor_struggles](https://www.reddit.com/r/raspberry_pi/comments/1g1hv9d/spi_pressure_sensor_struggles)
 - RSS feed: $source
 - date published: 2024-10-11T19:24:38+00:00

<!-- SC_OFF --><div class="md"><p>I have been learning python on and off for a while and have started tinkering with a Raspberry Pi and peripherals. I&#39;m trying to communicated with a SPI pressure sensor and am getting readings but unable to get positive pressure readings from the senor, it reached 0 Pa and won&#39;t go any higher. Per the user manual I am to send the sensor 3 bytes to engage it and then 16 clock pulses for the returning reading. The returning bytes are then converted to either positive or negative values based on two&#39;s compliment and that value is divided by 1200 to convert the pressure to Pa. For some reason I can&#39;t figure out the pressure reading will only return negative readings. When the pressure should be positive it will read at maximum zero though the sensor seems to read correctly in the negative direction. I feel like this code should work but it&#39;s not checking out. I&#39;m wondering if there is something obvious I&#39;m missing with regards 

## More Powerful Hailo-8 powered Raspberry Pi AI Kit On The Way?
 - [https://www.reddit.com/r/raspberry_pi/comments/1g1gf2y/more_powerful_hailo8_powered_raspberry_pi_ai_kit](https://www.reddit.com/r/raspberry_pi/comments/1g1gf2y/more_powerful_hailo8_powered_raspberry_pi_ai_kit)
 - RSS feed: $source
 - date published: 2024-10-11T18:19:45+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1g1gf2y/more_powerful_hailo8_powered_raspberry_pi_ai_kit/"> <img src="https://external-preview.redd.it/pIeeEq7V0M2b9mEFnRh3KrTIv127Mk0jC-nNQfX-nOM.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=c3ef9bfcc85a7e41bbc6b8b496b9305c3fa4a64b" alt="More Powerful Hailo-8 powered Raspberry Pi AI Kit On The Way?" title="More Powerful Hailo-8 powered Raspberry Pi AI Kit On The Way?" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/fmbret"> /u/fmbret </a> <br/> <span><a href="https://bret.dk/more-powerful-raspberry-pi-hailo-8-hat-incoming/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1g1gf2y/more_powerful_hailo8_powered_raspberry_pi_ai_kit/">[comments]</a></span> </td></tr></table>

## Camera Module 3 not working with waveshare 3.5inch gpio touch display. Error -> fd22
 - [https://www.reddit.com/r/raspberry_pi/comments/1g1f6xk/camera_module_3_not_working_with_waveshare_35inch](https://www.reddit.com/r/raspberry_pi/comments/1g1f6xk/camera_module_3_not_working_with_waveshare_35inch)
 - RSS feed: $source
 - date published: 2024-10-11T17:26:14+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://www.waveshare.com/wiki/3.5inch_RPi_LCD_(B">https://www.waveshare.com/wiki/3.5inch_RPi_LCD_(B)_Manual_Configuration</a>_Manual_Configuration)</p> <p><a href="https://www.waveshare.com/wiki/Raspberry_Pi_Camera_Module_3#Video_Recording_Image_Setting_Parameters">https://www.waveshare.com/wiki/Raspberry_Pi_Camera_Module_3#Video_Recording_Image_Setting_Parameters</a></p> <p>Hello i use piOS bookworm 64bit and the 3.5inch LCD display (link above).</p> <p>Problem is: The display works fine, but i cant use it together with the Camera Module 3 (link above)</p> <p>My setting are For Bookworm System</p> <h1>For Raspberry Pi 4 &amp; Raspberry Pi 5 (look here: <a href="https://www.waveshare.com/wiki/3.5inch_RPi_LCD_(B">https://www.waveshare.com/wiki/3.5inch_RPi_LCD_(B)_Manual_Configuration</a>_Manual_Configuration) )</h1> <p>When i try <code>sudo libcamera-hello -t 0 --camera 0</code> and a similar command: <code>rpicam-hello -t 0</code> i get the 

## Problem: failed to import fd22 ->using waveshare camv3 together with 3.5inch gpio B touch display
 - [https://www.reddit.com/r/raspberry_pi/comments/1g1ezdm/problem_failed_to_import_fd22_using_waveshare](https://www.reddit.com/r/raspberry_pi/comments/1g1ezdm/problem_failed_to_import_fd22_using_waveshare)
 - RSS feed: $source
 - date published: 2024-10-11T17:16:49+00:00

<!-- SC_OFF --><div class="md"><p>Hey, </p> <p>i succesfully installed/configurated the waveshare 3.5inch touch ips display (B).</p> <p>I use bookworm 64 bit on pi4b 4gb </p> <p><a href="https://www.waveshare.com/wiki/3.5inch_RPi_LCD_(B">https://www.waveshare.com/wiki/3.5inch_RPi_LCD_(B)_Manual_Configuration</a>_Manual_Configuration)</p> <p>However i can not use it togehter with the cam v3 module from waveshare.</p> <pre><code>libcamera-hello -t 0 </code></pre> <p>or</p> <pre><code>rpicamrpicam-hello -t 0 </code></pre> <p>both result in error &quot;failed to import fd22.</p> <p>If i change the overlay dtoverlay=waveshare35b-v2 the camera does work, BUT the 3.5 display doesnt work anymore.</p> <p>I need both touchdisplay and camera.</p> <p><a href="https://www.waveshare.com/wiki/Raspberry_Pi_Camera_Module_3#Video_Recording_Image_Setting_Parameters">https://www.waveshare.com/wiki/Raspberry_Pi_Camera_Module_3#Video_Recording_Image_Setting_Parameters</a></p> <p>Does someone know how the g

## I made PiSlide OS to make displaying images as a slideshow as easy as possible
 - [https://www.reddit.com/r/raspberry_pi/comments/1g1ehk7/i_made_pislide_os_to_make_displaying_images_as_a](https://www.reddit.com/r/raspberry_pi/comments/1g1ehk7/i_made_pislide_os_to_make_displaying_images_as_a)
 - RSS feed: $source
 - date published: 2024-10-11T16:55:17+00:00

<!-- SC_OFF --><div class="md"><p>I made <a href="https://github.com/JarvyJ/pislide-os">PiSlide OS</a> that makes it as easy as possible to display images on a Raspberry Pi. You just need to flash the SD image, then load up images, and you&#39;re good to go!</p> <p>It supports a bunch of image formats, including more modern ones: JPG, PNG, WEBP, AVIF, JXL, HEIF, HEIC, SVG, BMP, and TIFF. I&#39;m planning to add animated GIFs soon and have plans for HW accelerated video down the line.</p> <p>It supports all Raspberry Pis, so even if you have an old one sitting in a drawer somewhere, you can give it a try!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JarvyJ"> /u/JarvyJ </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1g1ehk7/i_made_pislide_os_to_make_displaying_images_as_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1g1ehk7/i_made_pislide_os_to_make_displaying_images_as_a/">[com

## It's Turns out I joined the Raspberry Pi family!
 - [https://www.reddit.com/r/raspberry_pi/comments/1g1deue/its_turns_out_i_joined_the_raspberry_pi_family](https://www.reddit.com/r/raspberry_pi/comments/1g1deue/its_turns_out_i_joined_the_raspberry_pi_family)
 - RSS feed: $source
 - date published: 2024-10-11T16:08:35+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1g1deue/its_turns_out_i_joined_the_raspberry_pi_family/"> <img src="https://b.thumbs.redditmedia.com/vnV9XIAuOvsp8DVhvDEnXYC0M1C4U7JuiHuEEEKtnCk.jpg" alt="It's Turns out I joined the Raspberry Pi family! " title="It's Turns out I joined the Raspberry Pi family! " /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sech1p"> /u/sech1p </a> <br/> <span><a href="https://www.reddit.com/gallery/1g1deue">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1g1deue/its_turns_out_i_joined_the_raspberry_pi_family/">[comments]</a></span> </td></tr></table>

## DIY Linux Router with Raspberry Pi OS
 - [https://www.reddit.com/r/raspberry_pi/comments/1g17cza/diy_linux_router_with_raspberry_pi_os](https://www.reddit.com/r/raspberry_pi/comments/1g17cza/diy_linux_router_with_raspberry_pi_os)
 - RSS feed: $source
 - date published: 2024-10-11T11:16:39+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1g17cza/diy_linux_router_with_raspberry_pi_os/"> <img src="https://external-preview.redd.it/YGReUdNdswvl9McUBdoGltzrVUd2QI-9FNUx4ZHOJkY.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=4657a539b2b352ae2880340b56dcf81f0e685785" alt="DIY Linux Router with Raspberry Pi OS" title="DIY Linux Router with Raspberry Pi OS" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/KRGLabs"> /u/KRGLabs </a> <br/> <span><a href="https://www.youtube.com/watch?v=6dkg_QdV-uQ">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1g17cza/diy_linux_router_with_raspberry_pi_os/">[comments]</a></span> </td></tr></table>

## Vivarium control system with Raspberry Pi
 - [https://www.reddit.com/r/raspberry_pi/comments/1g160hg/vivarium_control_system_with_raspberry_pi](https://www.reddit.com/r/raspberry_pi/comments/1g160hg/vivarium_control_system_with_raspberry_pi)
 - RSS feed: $source
 - date published: 2024-10-11T09:44:19+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1g160hg/vivarium_control_system_with_raspberry_pi/"> <img src="https://external-preview.redd.it/Bap8zdl5B3-1PcYdDvkn-toAIrqc1MpIXouuIWFnARg.jpg?width=216&amp;crop=smart&amp;auto=webp&amp;s=577340d72d1749ac315f31b79c46e8aabddff3e8" alt="Vivarium control system with Raspberry Pi" title="Vivarium control system with Raspberry Pi" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I&#39;m using Raspberry Pi to develop the <a href="https://github.com/Freya-Vivariums">Freya Vivarium Control System</a>. It is an open source control system for vivariums/terrariums/... .</p> <p><a href="https://preview.redd.it/qdsywo35l3ud1.jpg?width=4080&amp;format=pjpg&amp;auto=webp&amp;s=dfaa155620082bcd7c54c9f5d06f45e789b4c716">Vivarium test setup</a></p> <p><a href="https://preview.redd.it/ycpb020ml3ud1.png?width=1356&amp;format=png&amp;auto=webp&amp;s=4202c109e1b6e4cee1ab34ed1fec1f6ab7f5d410">Freya Vivarium Control System dashboard

