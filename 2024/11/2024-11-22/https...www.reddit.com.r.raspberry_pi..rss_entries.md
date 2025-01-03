# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Trouble with custom OS I2C LCD screen loading
 - [https://www.reddit.com/r/raspberry_pi/comments/1gxi0yl/trouble_with_custom_os_i2c_lcd_screen_loading](https://www.reddit.com/r/raspberry_pi/comments/1gxi0yl/trouble_with_custom_os_i2c_lcd_screen_loading)
 - RSS feed: $source
 - date published: 2024-11-22T20:50:38+00:00

<!-- SC_OFF --><div class="md"><p>For a computer science project, I figured it would be a fun idea to try and make a simple operating system for raspberry pi with I/O and file management capabilities. My main systems for output are the GPIO pins (of course), but I&#39;m also trying to get a LCD screen to display text through the I2C (BSC) peripheral. I&#39;ve been able to get the GPIO to function just as expected, but the main problem has been getting the LCD to display any text. My main ask is, do you see any errors with my code or setup that may be preventing the LCD from displaying the text? I&#39;ve gone through the datasheets that I could find, and even asked Chat GPT for help if the code looked correct, but I honestly cannot find anywhere I may have messed up. The main issue that may possibly be happening is that I don&#39;t have the right address for the LCD screen - I&#39;ve put it as 0x27 (in function I2CInitialize writing to the I2C_A (address) register), but I&#39;ve seen 

## problems with camera module 3 and v4l2|opencv
 - [https://www.reddit.com/r/raspberry_pi/comments/1gxfh2x/problems_with_camera_module_3_and_v4l2opencv](https://www.reddit.com/r/raspberry_pi/comments/1gxfh2x/problems_with_camera_module_3_and_v4l2opencv)
 - RSS feed: $source
 - date published: 2024-11-22T19:01:26+00:00

<!-- SC_OFF --><div class="md"><p>Hello! I have a problem: I can not capture image or video via v4l2, or internal methods of opencv(but RaspiCam can).<br/> opencv(code from <a href="https://docs.opencv.org/4.x/dd/d43/tutorial_py_video_display.html">doc</a>):</p> <pre><code>import numpy as np import cv2 as cv cap = cv.VideoCapture(0) # Define the codec and create VideoWriter object fourcc = cv.VideoWriter_fourcc(*&#39;XVID&#39;) out = cv.VideoWriter(&#39;output.avi&#39;, fourcc, 20.0, (1536, 864)) while cap.isOpened(): ret, frame = cap.read() if not ret: print(&quot;Can&#39;t receive frame (stream end?). Exiting ...&quot;) break frame = cv.flip(frame, 0) # write the flipped frame out.write(frame) cv.imshow(&#39;frame&#39;, frame) if cv.waitKey(1) == ord(&#39;q&#39;): break # Release everything if job is finished cap.release() out.release() cv.destroyAllWindows() </code></pre> <p>I get output:</p> <pre><code>[WARN:0@0.021] global ./modules/videoio/src/cap_gstreamer.cpp (862) isPipeline

## Raspberry Pi to Apple Cinema Display - Help
 - [https://www.reddit.com/r/raspberry_pi/comments/1gxa3z3/raspberry_pi_to_apple_cinema_display_help](https://www.reddit.com/r/raspberry_pi/comments/1gxa3z3/raspberry_pi_to_apple_cinema_display_help)
 - RSS feed: $source
 - date published: 2024-11-22T15:15:55+00:00

<!-- SC_OFF --><div class="md"><p>Hey all! I have an old 30” Apple Cinema HD Display that I am hoping to use with my raspberry pi 4B. I have a <a href="https://www.amazon.com/dp/B0CDCDRX6M">duel-link DVI to HDMI adapter</a> plugged into an HDMI to micro HDMI to connect the display to the pi. (see picture one) on unfortunately it does not seem to work. </p> <p>I have double checked that 1) the adapter is duel link to support the monitor 2) the adapter works - I plugged it into my 2012 MacBook Pro and I got a signal 3) I am using the 1st port on the Pi. 4) I have also tried enable/disabling 4k 60 video (I have no clue if that would do anything just trying all the possibilities)</p> <p>When I try to connect it the display backlight will flash on and off. Also the LED indicator light on the display will flash three times fast. I looked it up and the error code means &quot;The display is detecting either a wrong video format, or an unsupported resolution.&quot; </p> <p>Is there a way to g

## Waveshare 3.5 RPI (B) on Raspberry Pi 4 Kali - NOT VALID DRIVERS
 - [https://www.reddit.com/r/raspberry_pi/comments/1gx829n/waveshare_35_rpi_b_on_raspberry_pi_4_kali_not](https://www.reddit.com/r/raspberry_pi/comments/1gx829n/waveshare_35_rpi_b_on_raspberry_pi_4_kali_not)
 - RSS feed: $source
 - date published: 2024-11-22T13:39:29+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1gx829n/waveshare_35_rpi_b_on_raspberry_pi_4_kali_not/"> <img src="https://external-preview.redd.it/G2pWudthPfx9d1SAO5AODsQrQETGaW3oL6zVTvlmofQ.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=1b3697f8e8849b77dee31a9aa90c97d13ee9f7be" alt="Waveshare 3.5 RPI (B) on Raspberry Pi 4 Kali - NOT VALID DRIVERS" title="Waveshare 3.5 RPI (B) on Raspberry Pi 4 Kali - NOT VALID DRIVERS" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Have an issue with my touchscreen</p> <p>Have: </p> <p>Raspberry Pi 4b 8gb 64bt (arm64)</p> <p>Waveshare 3.5 RPi LCD (B) rev.2 </p> <p><a href="https://preview.redd.it/xae39zuefg2e1.png?width=960&amp;format=png&amp;auto=webp&amp;s=d112ca5a50f546b8f7d5c96cd3198a3b880ae0b1">https://preview.redd.it/xae39zuefg2e1.png?width=960&amp;format=png&amp;auto=webp&amp;s=d112ca5a50f546b8f7d5c96cd3198a3b880ae0b1</a></p> <p>Its been a while, since I&#39;am trying to make this screen to work.</p> <p>Before

## Troubles with I2C Connection Between Pico and Pi 5
 - [https://www.reddit.com/r/raspberry_pi/comments/1gwyd3s/troubles_with_i2c_connection_between_pico_and_pi_5](https://www.reddit.com/r/raspberry_pi/comments/1gwyd3s/troubles_with_i2c_connection_between_pico_and_pi_5)
 - RSS feed: $source
 - date published: 2024-11-22T03:21:57+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, I&#39;ve been working on a robotics project and I need my Raspberry Pi 5 to send commands to a Pico via I2C. </p> <p>Another subteam within my project got this working by connecting GP3 and GP2 of the Pi 5 to GP1 and GP2 of the Pico, respectively. They also shared ground pins between the two devices. Their pico was still powered via USB during their testing and it worked. </p> <p>I cannot for the life of me get my Pico and Pi to communicate in any way at all. <code>i2cdetect -y 1</code> gives me a bunch of dashed lines whenever I try this configuration. I repeated this across three different Pi boards (including a 3B+) to no avail. I&#39;ve also tried different I2C bus&#39;s and haven&#39;t gotten anything to read. When running the program the subteam designed to communicate between them, I keep getting <code>[Errno 5] Input/Output error</code>- which I assume is since it&#39;s not connected. </p> <p>If anyone has any ideas or suggestio

## Having some composite troubles
 - [https://www.reddit.com/r/raspberry_pi/comments/1gwwxan/having_some_composite_troubles](https://www.reddit.com/r/raspberry_pi/comments/1gwwxan/having_some_composite_troubles)
 - RSS feed: $source
 - date published: 2024-11-22T02:08:30+00:00

<!-- SC_OFF --><div class="md"><p>I have a 3B+ (with Raspberry Pi OS) that I&#39;ve been trying to get composite working for my CRT, the closest thing that has help was doing the dtoverlay=vc4-kms-v3d,composite=1 to the config file. </p> <p>I&#39;ll get the rainbow boot screen, then the OS welcome screen, but after it finishes, it&#39;ll go black, and then nothing but black on screen. </p> <p>Ssh and VNC work fine and I was able to try and mess with some of the video setting that way with neither helping.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Crabman8321"> /u/Crabman8321 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gwwxan/having_some_composite_troubles/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gwwxan/having_some_composite_troubles/">[comments]</a></span>

## Using NoMachine to connect remotely to my pi, but for some reason it's whitescreen
 - [https://www.reddit.com/r/raspberry_pi/comments/1gwv4ek/using_nomachine_to_connect_remotely_to_my_pi_but](https://www.reddit.com/r/raspberry_pi/comments/1gwv4ek/using_nomachine_to_connect_remotely_to_my_pi_but)
 - RSS feed: $source
 - date published: 2024-11-22T00:38:58+00:00

<!-- SC_OFF --><div class="md"><p>Hello I&#39;ll go into more detail on the problem here. I am trying to set up my RaspberryPi4 running the latest version of Raspberry Pi OS with a desktop interface (installed today freshly from original source) to be able to be connected to remotely via NoMachine. For now I am only trying to make it work on my local network. I followed many tutorials, got the right version of NoMachine for my hardware. After setting everything up, my pi is visible on local network, however, after connecting, I can only see a whitescreen. This will stay like this for a period then start to reconnect and white screen again.</p> <p>Anyone witnessed something familiar? What causes this and how could I fix it? Any answer is appreciated.</p> <p>P.S I am stubborn on using Nomachine for other reasons, I&#39;ve been able to use other desktop remote controls for my pi in the past, like VNC successfully, but this time I would really want to use NoMachine if possible.</p> </div

