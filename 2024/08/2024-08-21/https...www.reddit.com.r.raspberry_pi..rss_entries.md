# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Camera module 3 WIDE - Manual focus
 - [https://www.reddit.com/r/raspberry_pi/comments/1exs4ie/camera_module_3_wide_manual_focus](https://www.reddit.com/r/raspberry_pi/comments/1exs4ie/camera_module_3_wide_manual_focus)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-08-21T15:11:38+00:00

<!-- SC_OFF --><div class="md"><p>Hell everyone!<br /> I am new to RaspberryPi and I am currently using a RaspberryPi 5 with a cemerr amodule 3 WIDE.<br /> So here is the code that I have in order to save an image with the configurations I establish:</p> <p><code>from gpiozero import Button</code><br /> <code>import time</code><br /> <code>import os</code><br /> <code>from picamera2 import Picamera2</code><br /> <code>from libcamera import controls</code> </p> <p><code>camera = Picamera2()</code> </p> <p><code>preview_config = camera.create_preview_configuration()</code><br /> <code>capture_config = camera.create_still_configuration()</code><br /> <code>camera.configure(preview_config)</code> </p> <p><code>camera.start(show_preview=True)</code> </p> <p><code>output_folder = f&quot;/home/company/Documents&quot;</code><br /> <code>os.makedirs(output_folder, exist_ok=True)</code> </p> <p><code># Set exposure time</code><br /> <code>camera.set_controls({'ExposureTime': 5000}) # Example: 5

