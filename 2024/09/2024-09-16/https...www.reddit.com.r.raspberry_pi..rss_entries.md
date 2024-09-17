# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## 2024 Sep 16 Stickied -FAQ- & -HELPDESK- thread - Boot problems? Power supply problems? Display problems? Networking problems? Need ideas? Get help with these and other questions!
 - [https://www.reddit.com/r/raspberry_pi/comments/1fihd52/2024_sep_16_stickied_faq_helpdesk_thread_boot](https://www.reddit.com/r/raspberry_pi/comments/1fihd52/2024_sep_16_stickied_faq_helpdesk_thread_boot)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-16T22:00:49+00:00

<!-- SC_OFF --><div class="md"><h3><a href="http://f2z.net/RPi-Helpdesk-FAQ.png">Welcome to the r/raspberry_pi Helpdesk and Frequently Asked Questions!</a></h3> <p><a href="https://www.reddit.com/r/raspberry_pi/comments/1fd2pvn/2024_sep_9_stickied_faq_helpdesk_thread_boot/">Link to last week&#39;s thread</a></p> <p>Having a hard time searching for answers to your Raspberry Pi questions? Let the <a href="/r/raspberry_pi">r/raspberry_pi</a> community members search for answers <em>for you</em>!<sup>†</sup> Looking for help getting started with a project? Have a question that you need answered? Was it not answered last week? Did not get a satisfying answer? A question that you&#39;ve only done basic research for? Maybe something you think everyone but you knows? <strong>Ask your question in the comments on this page,</strong> operators are standing by!</p> <p>This helpdesk and idea thread is here so that the front page won&#39;t be filled with these same questions day in and day out:</p>

## Setting up CAN freezes terminal and needs hard reboot.
 - [https://www.reddit.com/r/raspberry_pi/comments/1fi47xk/setting_up_can_freezes_terminal_and_needs_hard](https://www.reddit.com/r/raspberry_pi/comments/1fi47xk/setting_up_can_freezes_terminal_and_needs_hard)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-16T13:10:05+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m having an issue setting up the dual can hat on my Raspberry Pi 3 A+. This issue hasn&#39;t occured before but now it seems when adding this command into terminal &quot;<code>sudo</code> <code>/sbin/ip</code> <code>link set</code> <code>can0 up type</code> <code>can bitrate 500000</code>&quot; it completely freezes the RPi. Even opening another terminal won&#39;t let me enter any command, therefor a hard reboot happens and I start again. I have tried on 3 Raspberry Pi&#39;s all with the same Can hat and I get the same results.</p> <p>This is very weird considering I setup multiple RPi&#39;s a few weeks ago with the exact same steps and didn&#39;t get any issues.</p> <p>Has anyone had this issue before and if so what was the fix?</p> <p>MCP2515, both can0 and can1 are succesffuly initialized when entering &quot;dmesg | grep can0&quot;</p> <p>The steps I follow can be found here: <a href="https://copperhilltech.com/blog/pican2-pican3-and-picanm-d

## Question regardin the Yahboom case for the Raspberry Pi 5
 - [https://www.reddit.com/r/raspberry_pi/comments/1fi30z4/question_regardin_the_yahboom_case_for_the](https://www.reddit.com/r/raspberry_pi/comments/1fi30z4/question_regardin_the_yahboom_case_for_the)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-16T12:13:57+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1fi30z4/question_regardin_the_yahboom_case_for_the/"> <img src="https://b.thumbs.redditmedia.com/sRHj928rYIu59NcLjZKRW2aeQ6uirruh5q8FecHfNUc.jpg" alt="Question regardin the Yahboom case for the Raspberry Pi 5 " title="Question regardin the Yahboom case for the Raspberry Pi 5 " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>One question regardin the Yahboom case for the Raspberry Pi 5:</p> <p>Did I put inside correctly the RP5 into the case? I am not quite sure, vbecause of the spaces on the microHDMI and Type C power supply-ports.</p> <p><a href="https://preview.redd.it/0argrrfox5pd1.png?width=1433&amp;format=png&amp;auto=webp&amp;s=103dcca32f2faf40b7e24340cac162f323ae2986">https://preview.redd.it/0argrrfox5pd1.png?width=1433&amp;format=png&amp;auto=webp&amp;s=103dcca32f2faf40b7e24340cac162f323ae2986</a></p> <p>Here is the link to the product page:</p> <p><a href="https://category.yahboom.net/products/pi5-si

## Kiosk Mode stops after roughly 6 or 7 hours
 - [https://www.reddit.com/r/raspberry_pi/comments/1fhrfba/kiosk_mode_stops_after_roughly_6_or_7_hours](https://www.reddit.com/r/raspberry_pi/comments/1fhrfba/kiosk_mode_stops_after_roughly_6_or_7_hours)
 - RSS feed: https://www.reddit.com/r/raspberry_pi/.rss
 - date published: 2024-09-16T00:19:02+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone. I just bought my first Rasberry pi few days ago and I set it up about 2 days ago to work as a little kiosk in my room for some grafana dashboards and prayer times.</p> <p>I followed this [url]<a href="https://www.raspberrypi.com/tutorials/how-to-use-a-raspberry-pi-in-kiosk-mode/%5C%5B/url%5C%5D">https://www.raspberrypi.com/tutorials/how-to-use-a-raspberry-pi-in-kiosk-mode/\[/url\]</a> tutorial with the help of this video [url]<a href="https://www.youtube.com/watch?v=J3gOWauVjwM&amp;t=62s%5C%5B/url%5C%5D">https://www.youtube.com/watch?v=J3gOWauVjwM&amp;t=62s\[/url\]</a></p> <p>Every thing is work perfect after a boot but when left running for few hours, the kiosk mode stops and only the desktop is showing.</p> <p>[b]these are my rasberry pi specs[/b]</p> <p>[code]Linux kiosk1 6.6.47+rpt-rpi-v8 #1 SMP PREEMPT Debian 1:6.6.47-1+rpt1 (2024-09-02) aarch64 GNU/Linux</p> <p>Raspberry Pi 4 Model B Rev 1.5</p> <p>Debian GNU/Linux 12 (bookworm)</p>

