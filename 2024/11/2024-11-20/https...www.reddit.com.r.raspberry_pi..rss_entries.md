# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Ethernet dongle not working for Pi Zero 2 W
 - [https://www.reddit.com/r/raspberry_pi/comments/1gvx2oh/ethernet_dongle_not_working_for_pi_zero_2_w](https://www.reddit.com/r/raspberry_pi/comments/1gvx2oh/ethernet_dongle_not_working_for_pi_zero_2_w)
 - RSS feed: $source
 - date published: 2024-11-20T18:55:29+00:00

<!-- SC_OFF --><div class="md"><p>I bought the <a href="https://www.amazon.de/dp/B01LXP5TXI?ref=ppx_yo2ov_dt_b_fed_asin_title">Amazon Fire ethernet adapter</a>, to connect my Pi Zero 2 via ethernet and powering it on via the same port. When I connect it to my Pi, it turns on but then nothing happens, it never comes online. The Pi is not connecting even to the WiFi, so I have no way to check what is breaking.</p> <p>What I have noticed, through <code>sudo journalctl</code>, is that there are no logs whatsoever when I connect it via this adapter. I can only see logs when I power it to the PWR port and let it connect via WiFi. So <strong>I suppose that actually the guy is not even booting.</strong></p> <p>What is the problem here? Is the dongle not working or is it not compatible?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/giamboscaro"> /u/giamboscaro </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gvx2oh/ethernet_don

## p5.speech and raspberry pi 3B+
 - [https://www.reddit.com/r/raspberry_pi/comments/1gvdu3o/p5speech_and_raspberry_pi_3b](https://www.reddit.com/r/raspberry_pi/comments/1gvdu3o/p5speech_and_raspberry_pi_3b)
 - RSS feed: $source
 - date published: 2024-11-20T01:27:01+00:00

<!-- SC_OFF --><div class="md"><p>Hi! I&#39;m trying to use raspberry pi b+ and a small LCD screen to display some p5 code that implements p5.speech recognition but haven&#39;t been able to get it to work.</p> <p>I&#39;ve tried on chromium and firefox, both unable to hear anything! I&#39;m running 2022 bullseye on it per the screen manufacturers instructions</p> <p>other p5 sketches with sound have been totally fine but the speech recognition hasn&#39;t been loading at all. I&#39;ve looked in other forums but there doesn&#39;t seem to be a direct answer about anything! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/abandonmenttrauma"> /u/abandonmenttrauma </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gvdu3o/p5speech_and_raspberry_pi_3b/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gvdu3o/p5speech_and_raspberry_pi_3b/">[comments]</a></span>

## Server does not have extension for dpms option
 - [https://www.reddit.com/r/raspberry_pi/comments/1gvc6pt/server_does_not_have_extension_for_dpms_option](https://www.reddit.com/r/raspberry_pi/comments/1gvc6pt/server_does_not_have_extension_for_dpms_option)
 - RSS feed: $source
 - date published: 2024-11-20T00:09:05+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I found an interesting conundrum while trying to get my rPi4 + official rPi 7&quot; LCD (connected via flex cable) working as an alarm clock. I need to have the ability to turn off the backlight via a tkinter button, but also have the alarm wake the screen programmatically, and ensure touching the screen also wakes the backlight.</p> <p>So, the standard way to deal with this is using:</p> <p><code>xset -display :0 dpms force onxset -display :0 dpms force on</code></p> <p>However, when I use it, I get the error: <em>Server does not have extension for dpms option</em></p> <p>I was stuck for a long time. Then, I was messing around with starting up in the terminal first, then using &quot;startx&quot; to get into the WM. Low and behold, the xset comand just started working, with no error, and the backlight control was perfect!</p> <p>So, when the rPi4 is setup to boot to GUI, xset dpms does NOT work. However, when it is setup to boot to termina

