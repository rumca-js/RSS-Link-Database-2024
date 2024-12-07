# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Official HAILO8 HAT not working on Pi5 8GB - "Link Down"
 - [https://www.reddit.com/r/raspberry_pi/comments/1h7y5at/official_hailo8_hat_not_working_on_pi5_8gb_link](https://www.reddit.com/r/raspberry_pi/comments/1h7y5at/official_hailo8_hat_not_working_on_pi5_8gb_link)
 - RSS feed: $source
 - date published: 2024-12-06T10:07:22+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I am scratching my head because I have no clue whats wrong here.<br/> I&#39;m no noob. That&#39;s not the first Pi I am working with.</p> <p>However.. going after the most straight forward installation guide, it anyway seems that I am unable to get that HAT working</p> <p>The guides I followed:<br/> <a href="https://www.raspberrypi.com/documentation/accessories/m2-hat-plus.html#m2-hat-plus-installation">https://www.raspberrypi.com/documentati ... stallation</a><br/> <a href="https://github.com/hailo-ai/hailo-rpi5-examples/blob/main/doc/install-raspberry-pi5.md#pcie-troubleshooting">https://github.com/hailo-ai/hailo-rpi5- ... leshooting</a></p> <p>Right after upgrading the OS, making raspi-config, shutting down, installing the AI Kit I dont see it connecting.<br/> It&#39;s the 26 TOPS version by the way.</p> <p>Code: <a href="https://forums.raspberrypi.com/viewtopic.php?t=380559#">Select all</a></p> <pre><code>odin@aifred:~ $ lspci 00:0

## Any attempt to use the camera via picamera2 appears blurry and zoomed in despite rpicam-hello working fine
 - [https://www.reddit.com/r/raspberry_pi/comments/1h7xf8r/any_attempt_to_use_the_camera_via_picamera2](https://www.reddit.com/r/raspberry_pi/comments/1h7xf8r/any_attempt_to_use_the_camera_via_picamera2)
 - RSS feed: $source
 - date published: 2024-12-06T09:12:36+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone -- I have a problem that has been absolutely driving me crazy and if anyone is able to help I would greatly appreciate it.</p> <p>I have an rpi4 running the latest Raspberry Pi OS (bookworm) and I am trying to set up a very basic camera app. The problem is, when I try to do this in python, the images and previews always show up as if they are incredibly blurry and zoomed in. What is extra confusing though, is that rpicam-hello and rpicam-still work fine and grab high quality images and previews. So there is no hardware issue, and the pi is perfectly capable of accessing the camera correctly, it just seems that rpicam-apps are doing some extra setup step that I am unaware of, and it is a step that is missing in every beginners camera tutorial that I try out. </p> <p>Here is the base code that I am using (though I have tried all sorts of variants of it):</p> <pre><code>from picamera2 import Picamera2, Preview import time picam2 = Picamera2(

## Conflicting info between LCD controller and module datasheets
 - [https://www.reddit.com/r/raspberry_pi/comments/1h7uzae/conflicting_info_between_lcd_controller_and](https://www.reddit.com/r/raspberry_pi/comments/1h7uzae/conflicting_info_between_lcd_controller_and)
 - RSS feed: $source
 - date published: 2024-12-06T06:17:11+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to interface a <a href="https://www.alibaba.com/product-detail/2-4-inch-222-480-Bar_1601271408770.html">TT240TFN01A</a> LCD with a Raspberry Pi Zero and have run into a confusing situation regarding how this display actually needs to be controlled.</p> <p>The confusion stems from three sources:</p> <ol> <li>The LCD&#39;s datasheet (TT240TFN01A)</li> <li>The controller&#39;s datasheet (<a href="https://focuslcds.com/wp-content/uploads/Drivers/ST7796U.pdf?srsltid=AfmBOoq9JwIDbnhKWgcR9RRFneAaiLn0U2MKJVdvdZIZMOLsBBVRmjm6">ST7796U</a>)</li> <li>A similar display from Adafruit (<a href="https://www.adafruit.com/product/5797">TL032FWV01CT-I1440A</a>)</li> </ol> <p>The LCD module uses an ST7796U controller, and according to that controller&#39;s datasheet, it should support both 3-wire and 4-wire SPI modes for full display control. </p> <p>However, the LCD module&#39;s implementation raises some questions:</p> <ul> <li>The interface is listed 

## Rasberry Pi 3B+ No Audio
 - [https://www.reddit.com/r/raspberry_pi/comments/1h7p3hz/rasberry_pi_3b_no_audio](https://www.reddit.com/r/raspberry_pi/comments/1h7p3hz/rasberry_pi_3b_no_audio)
 - RSS feed: $source
 - date published: 2024-12-06T00:59:28+00:00

<!-- SC_OFF --><div class="md"><p>I recently picked up a Raspberry Pi 3B+ to try to run Steam Link. Steam Link wasn&#39;t streaming any sound, and after some troubleshooting I got the sound to work on on a secondary device (steamlink on my phone), but it seems the pi itself still has some audio issues. I haven&#39;t gotten sound over headphones or HDMI on two different devices. I&#39;ll list all the info I can here and what I&#39;ve tried, but I&#39;m not sure what I can do next.</p> <p>TV: Sansui S55VAUG<br/> OS: Raspberry Pi 64-bit Lite, Debian Bookworm 12</p> <p>/boot/firmware/config.txt includes<br/> <code>dtparams=audio=on</code><br/> <code>dtoverlay=vc4-kms-v3d</code></p> <p>alsamixer<br/> <code>Card: vc4-hdmi</code><br/> <code>This sound device does not have any controls</code></p> <p>amixer cset numid=3 x<br/> <code>amixer: Control default element write error: Operation not permitted</code></p> <p>aplay -l<br/> <code>**** LIst of PLAYBACK Hardware Devices ****</code><br/> <co

