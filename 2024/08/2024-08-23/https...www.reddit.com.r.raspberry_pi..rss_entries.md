# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Accelerometer not found in Adafruit but in spidev
 - [https://www.reddit.com/r/raspberry_pi/comments/1ezer9f/accelerometer_not_found_in_adafruit_but_in_spidev](https://www.reddit.com/r/raspberry_pi/comments/1ezer9f/accelerometer_not_found_in_adafruit_but_in_spidev)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-08-23T14:52:46+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1ezer9f/accelerometer_not_found_in_adafruit_but_in_spidev/"> <img alt="Accelerometer not found in Adafruit but in spidev" src="https://b.thumbs.redditmedia.com/SJUbo-UYGPcfVPTwMXNYl2Aolx1BcvCev2EmhYu0Iqo.jpg" title="Accelerometer not found in Adafruit but in spidev" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello, im trying to read data from a lis3dh accelerometer and used the Code that was given from the Adafruit site<br /> <code>import time</code></p> <p><code>import board</code></p> <p><code>import digitalio</code></p> <p><code>import adafruit_lis3dh</code></p> <p><code>spi = board.SPI()</code></p> <p><code>cs = digitalio.DigitalInOut(board.D8)</code></p> <p><code>while True:</code></p> <p><code>try:</code></p> <p><code>lis3dh = adafruit_lis3dh.LIS3DH_SPI(spi, cs)</code></p> <p><code>x, y, z = lis3dh.acceleration</code></p> <p><code>print(x, y, z)</code></p> <p><code>break</code></p> <p><code>except 

## Raspberrypi5 , how do i clean install? I am having ssh connection issues now.
 - [https://www.reddit.com/r/raspberry_pi/comments/1ez90ph/raspberrypi5_how_do_i_clean_install_i_am_having](https://www.reddit.com/r/raspberry_pi/comments/1ez90ph/raspberrypi5_how_do_i_clean_install_i_am_having)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-08-23T10:08:42+00:00

<!-- SC_OFF --><div class="md"><p>I had the raspberry working fine for a couple days. And i connected back to my pc to verify settings due to a delay in speed. So the ssh connection started timing out so i decided to do a clean install. Now it has become a nightmare for me. I did the clean install then it will not accept the password, then if it does, it times out before i could set the settings. </p> <p>I am trying a clean install but i have been unsuccessful. As the raspberry pi program pulls up old username and password, which lead me to think that this is the reason for the conflict when i try to ssh connect to it. </p> <p>Please help, this is my first RP5.</p> <p>I reformatted my micro sd card. I uninstalled raspberry installer using iobit uninstaller from my pc before downloading the installer from the website again. I made sure to select enable ssh in advanced settings when reinstalling. I make sure i select the RP5 with 64x OS. I have tried removing ssh host keys from registry

