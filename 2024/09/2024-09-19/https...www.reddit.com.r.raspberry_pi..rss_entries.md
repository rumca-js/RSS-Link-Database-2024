# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## I Made a Robotic Head Based on Pico and a Tutorial How to Build Your Own!
 - [https://www.reddit.com/r/raspberry_pi/comments/1fkvpr0/i_made_a_robotic_head_based_on_pico_and_a](https://www.reddit.com/r/raspberry_pi/comments/1fkvpr0/i_made_a_robotic_head_based_on_pico_and_a)
 - RSS feed: $source
 - date published: 2024-09-19T21:30:33+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1fkvpr0/i_made_a_robotic_head_based_on_pico_and_a/"> <img src="https://external-preview.redd.it/zUtY-FQr56K5ZC3pGD2Blz9N6iRCrZVrcM1d2-yU70w.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=b19aace3c139776e40c591d46d48fa5055c806cc" alt="I Made a Robotic Head Based on Pico and a Tutorial How to Build Your Own!" title="I Made a Robotic Head Based on Pico and a Tutorial How to Build Your Own!" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>It has a camera with a mic (USB) and is controlled over UART. It is supposed to be used in projects with Raspberry Pi or something similar.</p> <p><a href="https://reddit.com/link/1fkvpr0/video/5dwwhnn43upd1/player">https://reddit.com/link/1fkvpr0/video/5dwwhnn43upd1/player</a></p> <ul> <li>Build manual: <a href="https://www.hackster.io/an-dr/remotion-robotic-platform-0e8301">https://www.hackster.io/an-dr/remotion-robotic-platform-0e8301</a></li> <li>Blog: <a href="https://hac

## Whenever Raspberry is connected via WiFi I can't ping nor SSH
 - [https://www.reddit.com/r/raspberry_pi/comments/1fkswiv/whenever_raspberry_is_connected_via_wifi_i_cant](https://www.reddit.com/r/raspberry_pi/comments/1fkswiv/whenever_raspberry_is_connected_via_wifi_i_cant)
 - RSS feed: $source
 - date published: 2024-09-19T19:11:44+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, as the title suggests I am experiencing network issues with my raspberry pi model 3 B.<br/> Whenever I connect it via Wired ethernet to my home network it works fine, i can ping from another PC even SSH to it with no problems, but whenever I connect it via WiFi I can&#39;t ping it nor SSH to it.<br/> My raspberry pi network connection works fine with WiFi meaning I can ping to <a href="http://8.8.8.8">8.8.8.8</a> and even seeing it in the routher admin panel (connected via WiFi) but I cannot ping to it from another PC nor SSH.</p> <p>any ideas ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mindcalc"> /u/mindcalc </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fkswiv/whenever_raspberry_is_connected_via_wifi_i_cant/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fkswiv/whenever_raspberry_is_connected_via_wifi_i_cant/">[comments]</a>

## Wondering if I can use PCA and ADC for servos at the same time
 - [https://www.reddit.com/r/raspberry_pi/comments/1fknvi0/wondering_if_i_can_use_pca_and_adc_for_servos_at](https://www.reddit.com/r/raspberry_pi/comments/1fknvi0/wondering_if_i_can_use_pca_and_adc_for_servos_at)
 - RSS feed: $source
 - date published: 2024-09-19T15:39:09+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to use an ADC1115 to convert joystick analog signal into digital ones since the Pl doesn&#39;t take in analog inputs, but I also want to use a PCA9685 as a hardware pwm to reduce the jittering I get when using the joystick. I am wondering if I can use both of these modules simultaneously, since the pi only has one SCL and one SDA gpio pins. Any feedback is welcome. Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TShippy"> /u/TShippy </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fknvi0/wondering_if_i_can_use_pca_and_adc_for_servos_at/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1fknvi0/wondering_if_i_can_use_pca_and_adc_for_servos_at/">[comments]</a></span>

## 4 wire Resistive Touch Panel with Pi 5
 - [https://www.reddit.com/r/raspberry_pi/comments/1fkd7s7/4_wire_resistive_touch_panel_with_pi_5](https://www.reddit.com/r/raspberry_pi/comments/1fkd7s7/4_wire_resistive_touch_panel_with_pi_5)
 - RSS feed: $source
 - date published: 2024-09-19T05:07:04+00:00

<!-- SC_OFF --><div class="md"><p>4 wire Resistive Touch Panel with Pi 5</p> <p>I had a spare 10.1 inch lcd screen lying so i wanted to use it in a project with Pi Pico. But the project needed a touch display. So i bought a 4 wire resistive touch panel to make the lcd screen touch enabled.</p> <p>During my research I came across <a href="https://github.com/adafruit/Adafruit_CircuitPython_Touchscreen/tree/main">this adafruit circuitpython</a> library that can make it easier to setup the 4 pin resistive touch panel. </p> <p>Here is the simple test code the library provides :</p> <p><code>import board</code></p> <p><code>import adafruit_touchscreen</code></p> <p><code># These pins are used as both analog and digital! XL, XR and YU must be analog</code></p> <p><code># and digital capable. YD just need to be digital</code></p> <p><code>ts = adafruit_touchscreen.Touchscreen(</code></p> <p><code>board.TOUCH_XL,</code></p> <p><code>board.TOUCH_XR,</code></p> <p><code>board.TOUCH_YD,</code></p

