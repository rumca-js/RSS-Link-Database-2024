# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Run Android 15 on Raspberry Pi 5 with Emteria OS
 - [https://www.reddit.com/r/raspberry_pi/comments/1h60tqz/run_android_15_on_raspberry_pi_5_with_emteria_os](https://www.reddit.com/r/raspberry_pi/comments/1h60tqz/run_android_15_on_raspberry_pi_5_with_emteria_os)
 - RSS feed: $source
 - date published: 2024-12-03T22:56:57+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1h60tqz/run_android_15_on_raspberry_pi_5_with_emteria_os/"> <img src="https://external-preview.redd.it/g7yKXxwEmujmzIBeRAp1bFNwnN4wO60Dw0N5PRBYxHA.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=86879bfc76d70256e7709553e72a92df3c0cc4ce" alt="Run Android 15 on Raspberry Pi 5 with Emteria OS" title="Run Android 15 on Raspberry Pi 5 with Emteria OS" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tamhanna"> /u/tamhanna </a> <br/> <span><a href="https://www.youtube.com/watch?v=PonpDU1vEoU">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1h60tqz/run_android_15_on_raspberry_pi_5_with_emteria_os/">[comments]</a></span> </td></tr></table>

## Docker configuration for Caddy, pihole, and other containers
 - [https://www.reddit.com/r/raspberry_pi/comments/1h5ytyk/docker_configuration_for_caddy_pihole_and_other](https://www.reddit.com/r/raspberry_pi/comments/1h5ytyk/docker_configuration_for_caddy_pihole_and_other)
 - RSS feed: $source
 - date published: 2024-12-03T21:33:13+00:00

<!-- SC_OFF --><div class="md"><p>I setup monitoring for my Starlink connection on a raspberry pi, I have Grafana running in a docker stack with the monitoring configs and did not change the default username/pw. </p> <p>Starlink monitoring setup - <a href="https://github.com/danopstech/starlink">https://github.com/danopstech/starlink</a></p> <p>Everything was working great until I installed searxng and caddy for reverse proxy in a separate docker stack. I can access the grafana login page, but login credentials are rejected. I&#39;ve reset the admin password via the CLI, but still get &quot;invalid username or password&quot;, even after restarting the container or the entire stack. Shutting down the searxng stack with caddy does not resolve the issue either, so it may be a red herring. I&#39;ve followed all the documentation I can find re: changing the grafana admin password, but no luck.</p> <p>Docker setup for searxng - <a href="https://github.com/searxng/searxng-docker">https://gi

## Trying to shutdown Vmware using powercli on PI via NUT UPS
 - [https://www.reddit.com/r/raspberry_pi/comments/1h5y803/trying_to_shutdown_vmware_using_powercli_on_pi](https://www.reddit.com/r/raspberry_pi/comments/1h5y803/trying_to_shutdown_vmware_using_powercli_on_pi)
 - RSS feed: $source
 - date published: 2024-12-03T21:08:12+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1h5y803/trying_to_shutdown_vmware_using_powercli_on_pi/"> <img src="https://a.thumbs.redditmedia.com/70PS5cOMHpar4c5rAnDBSjpSODZwJnWCPCgi3cw4hX8.jpg" alt="Trying to shutdown Vmware using powercli on PI via NUT UPS" title="Trying to shutdown Vmware using powercli on PI via NUT UPS" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi</p> <p>I currently have a Raspberry Pi 4B running the latest PI OS (bookworm) I have installed the nut server and connected my UPS via a USB to the PI. In addition to this I have PowerShell installed along with the VMWare Power CLI modules.</p> <p>I have created a PowerShell script which connects to my Vcenter and shuts down all the VMs and then the hosts. I call this script via a bash shell script. Calling this locally via the terminal, it works fine. The bash shell also has an email script within it, which appears to be the only part of this bash shell script that works when I pu

## Raspberry Pi 5 (8GB) and Waveshare 4.3inch DSI LCD Display Issue
 - [https://www.reddit.com/r/raspberry_pi/comments/1h5twtg/raspberry_pi_5_8gb_and_waveshare_43inch_dsi_lcd](https://www.reddit.com/r/raspberry_pi/comments/1h5twtg/raspberry_pi_5_8gb_and_waveshare_43inch_dsi_lcd)
 - RSS feed: $source
 - date published: 2024-12-03T18:12:35+00:00

<!-- SC_OFF --><div class="md"><p>Hello Raspberry Pi Community,</p> <p>I’m encountering an issue with my Raspberry Pi 5 (8GB) and the Waveshare 4.3inch DSI LCD display. Despite following the configuration guidelines, the display isn’t working as expected. Below, I’ve included my debug outputs and configuration file for reference.</p> <p>Issue Overview</p> <p>The DSI display is not initializing properly.</p> <p>Errors related to the DSI display appear in dmesg.</p> <p>The display shows up in xrandr, but there are significant initialization errors in the logs.</p> <p>When I use the original Raspberry Pi DSI cable, the device doesn&#39;t detect anything. When I use the DSI cable included in the Waveshare kit, the output is as follows:</p> <p><strong>dmesg | grep -i dsi and xrandr</strong></p> <p><code>hasloadmin@admin:~ $ dmesg | grep -i dsi</code></p> <p><code>[ 0.530692] platform 1f00118000.dsi: Fixed dependency cycle(s) with /axi/pcie@120000/rp1/dsi@110000/bridge@0</code></p> <p><cod

## Breaking "while: True" loops through shell
 - [https://www.reddit.com/r/raspberry_pi/comments/1h5tqdc/breaking_while_true_loops_through_shell](https://www.reddit.com/r/raspberry_pi/comments/1h5tqdc/breaking_while_true_loops_through_shell)
 - RSS feed: $source
 - date published: 2024-12-03T18:05:15+00:00

<!-- SC_OFF --><div class="md"><p>So, I have a problem programing.</p> <p>I have this code that should loop infinitely and as fast as possible monitoring a sensor. For this I’m using a “while True:” statement kept orderly by a “time.sleep_ms(20)”. I’m controlling it through an application and need to end it when I want sending a command through serial port.</p> <p>Is there a way to do so?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Obher0n"> /u/Obher0n </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1h5tqdc/breaking_while_true_loops_through_shell/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1h5tqdc/breaking_while_true_loops_through_shell/">[comments]</a></span>

## Raspberry PI I2C in Rust
 - [https://www.reddit.com/r/raspberry_pi/comments/1h5th9i/raspberry_pi_i2c_in_rust](https://www.reddit.com/r/raspberry_pi/comments/1h5th9i/raspberry_pi_i2c_in_rust)
 - RSS feed: $source
 - date published: 2024-12-03T17:55:27+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1h5th9i/raspberry_pi_i2c_in_rust/"> <img src="https://external-preview.redd.it/oPHkFlgR6hIMssOP6h4ne3zRabvCRMbpqxMomz3Dsdc.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=edbb6ff84d90bea5da3fbae615d1a7765e5b66de" alt="Raspberry PI I2C in Rust" title="Raspberry PI I2C in Rust" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>With a little (a lot) of help from an AI programming tool I&#39;ve written a small Rust [program](<a href="https://github.com/jamie0walton/pymscada-rust">https://github.com/jamie0walton/pymscada-rust</a>) that reads data from an ADS1115 over I2C. It sits at around 5% CPU, continuously collects data at 737SPS into a rolling buffer. A second coroutine calculates the RMS current and harmonics up to the 7th and submits this to an ethernet message bus.</p> <p>Some interesting challenges. Using the TI datasheet to guide the tool on the correct commands helped avoid a __lot__ of errors.</p> <p><

## Network mount wont survive reboot (RPI5, Raspbian Bookworm)
 - [https://www.reddit.com/r/raspberry_pi/comments/1h5pv28/network_mount_wont_survive_reboot_rpi5_raspbian](https://www.reddit.com/r/raspberry_pi/comments/1h5pv28/network_mount_wont_survive_reboot_rpi5_raspbian)
 - RSS feed: $source
 - date published: 2024-12-03T15:22:48+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, RPI5 running Raspbian Bookworm. I have a network drive mount that wont survive a reboot. I have added the following to my /etc/fstab</p> <pre><code>//192.168.1.212/PlexMedia /media/pishare cifs _netdev,user=realusername,password=realpassword,uid=1000,gid=1000 0 0 </code></pre> <p>What am I missing? Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Necessary_Ad_238"> /u/Necessary_Ad_238 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1h5pv28/network_mount_wont_survive_reboot_rpi5_raspbian/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1h5pv28/network_mount_wont_survive_reboot_rpi5_raspbian/">[comments]</a></span>

## Short-circuit On Rpi 4B Usb-A 2.0 Port
 - [https://www.reddit.com/r/raspberry_pi/comments/1h5mhjn/shortcircuit_on_rpi_4b_usba_20_port](https://www.reddit.com/r/raspberry_pi/comments/1h5mhjn/shortcircuit_on_rpi_4b_usba_20_port)
 - RSS feed: $source
 - date published: 2024-12-03T12:39:59+00:00

<!-- SC_OFF --><div class="md"><p>As you can understand from the title, I caused a short circuit in one of the Rpi 4B usb 2.0 ports. When I measured between the D+ D- pins of the other 2.0 port with a multimeter in the diode test position, I saw a value of 1300, while I cannot see any value on the port where the short circuit occurred. All other ports work without any problems, so I think the fault is in the usb protection chips, but I don&#39;t know which chips are these and how to determine the faulty one. I am waiting for your help.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Inevitable_Ferret266"> /u/Inevitable_Ferret266 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1h5mhjn/shortcircuit_on_rpi_4b_usba_20_port/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1h5mhjn/shortcircuit_on_rpi_4b_usba_20_port/">[comments]</a></span>

## GPIO display not working correct
 - [https://www.reddit.com/r/raspberry_pi/comments/1h5kbys/gpio_display_not_working_correct](https://www.reddit.com/r/raspberry_pi/comments/1h5kbys/gpio_display_not_working_correct)
 - RSS feed: $source
 - date published: 2024-12-03T10:19:12+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1h5kbys/gpio_display_not_working_correct/"> <img src="https://b.thumbs.redditmedia.com/MDW2DFN-J_DYGk11G_ZBiDBdQ-NRIP1CUCw-K0gWCOg.jpg" alt="GPIO display not working correct" title="GPIO display not working correct" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey guy,</p> <p>I got myself a Waveshare 7&quot; RGB LCD display which gets connected to the pi via GPIO. My problem is that the picture shown at the display looks like this.</p> <p><a href="https://preview.redd.it/qsm2nvhkzl4e1.jpg?width=4000&amp;format=pjpg&amp;auto=webp&amp;s=8b3489cbc09047297070a74eedfccdf342b66e7a">https://preview.redd.it/qsm2nvhkzl4e1.jpg?width=4000&amp;format=pjpg&amp;auto=webp&amp;s=8b3489cbc09047297070a74eedfccdf342b66e7a</a></p> <p>You can see here that the shown picture is &quot;to much left&quot; and the problem occurs both on my pi 1B+ and my pi 4B.</p> <p>Any advice what I could try out to fix this and move it &quot;mo

## Let people control your 3D printer over TikTok Live chat commands!
 - [https://www.reddit.com/r/raspberry_pi/comments/1h5j87l/let_people_control_your_3d_printer_over_tiktok](https://www.reddit.com/r/raspberry_pi/comments/1h5j87l/let_people_control_your_3d_printer_over_tiktok)
 - RSS feed: $source
 - date published: 2024-12-03T08:55:41+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1h5j87l/let_people_control_your_3d_printer_over_tiktok/"> <img src="https://external-preview.redd.it/JI3iqZ6e6blwybEpCWske-OY8W34PwLnlxhFiPumbo0.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=6925b55fc39da226625d4dbeb84a61ca776ff8e1" alt="Let people control your 3D printer over TikTok Live chat commands!" title="Let people control your 3D printer over TikTok Live chat commands!" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>The code running on a Raspberry Pi uses an unofficial API to scrape the comment commands and turns them into gcode to send to the printer over usb.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MrSirLRD"> /u/MrSirLRD </a> <br/> <span><a href="https://youtu.be/vHK_7evPgTA">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1h5j87l/let_people_control_your_3d_printer_over_tiktok/">[comments]</a></span> </td></tr>

## Touch screen not detected but works fine on windows
 - [https://www.reddit.com/r/raspberry_pi/comments/1h5iwwp/touch_screen_not_detected_but_works_fine_on](https://www.reddit.com/r/raspberry_pi/comments/1h5iwwp/touch_screen_not_detected_but_works_fine_on)
 - RSS feed: $source
 - date published: 2024-12-03T08:30:51+00:00

<!-- SC_OFF --><div class="md"><p>Raspberry pi will output HDMI fine to a <a href="https://www.amazon.com/dp/B0D66J1GVD">touchscreen</a> case i bought on amazon but im not seeing any touch input. When plugged into a windows computer via USB-C it works immediately. I tried the supplied USB to 3 pin cable, as well as the USB-C cable with no luck. When either option is used im not seeing anything with lsusb, just my keyboard and 4 &quot;linux foundation root hubs&quot;. Tried other ports, and cables. Any help would be appreciated, its probably some small thing i have to enable but i have been unable to find it through much googling. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kapaskae"> /u/kapaskae </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1h5iwwp/touch_screen_not_detected_but_works_fine_on/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1h5iwwp/touch_screen_not_detected_bu

## Sending images from Pi Pico W to PC using UDP
 - [https://www.reddit.com/r/raspberry_pi/comments/1h5bq1x/sending_images_from_pi_pico_w_to_pc_using_udp](https://www.reddit.com/r/raspberry_pi/comments/1h5bq1x/sending_images_from_pi_pico_w_to_pc_using_udp)
 - RSS feed: $source
 - date published: 2024-12-03T01:26:48+00:00

<!-- SC_OFF --><div class="md"><p>Title. I’m doing a Computer Vision project and want a Pi Pico W to send images it takes with a camera to a computer where I can do some CV operations on it. However I’m stuck on the encoding portion. Normally OpenCV has a function that does it. But in this case OpenCV would be too big. Are there alternatives for the Pico. I am using MicroPython via Thonny. The images are fairly small</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/toadx60"> /u/toadx60 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1h5bq1x/sending_images_from_pi_pico_w_to_pc_using_udp/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1h5bq1x/sending_images_from_pi_pico_w_to_pc_using_udp/">[comments]</a></span>

## 2024 Dec 2 Stickied -FAQ- & -HELPDESK- thread - Boot problems? Power supply problems? Display problems? Networking problems? Need ideas? Get help with these and other questions!
 - [https://www.reddit.com/r/raspberry_pi/comments/1h5b77t/2024_dec_2_stickied_faq_helpdesk_thread_boot](https://www.reddit.com/r/raspberry_pi/comments/1h5b77t/2024_dec_2_stickied_faq_helpdesk_thread_boot)
 - RSS feed: $source
 - date published: 2024-12-03T01:01:58+00:00

<!-- SC_OFF --><div class="md"><h3><a href="http://f2z.net/RPi-Helpdesk-FAQ.png">Welcome to the r/raspberry_pi Helpdesk and Frequently Asked Questions!</a></h3> <p><a href="https://www.reddit.com/r/raspberry_pi/comments/1gzxz1w/2024_nov_25_stickied_faq_helpdesk_thread_boot/">Link to last week&#39;s thread</a></p> <p>Having a hard time searching for answers to your Raspberry Pi questions? Let the <a href="/r/raspberry_pi">r/raspberry_pi</a> community members search for answers <em>for you</em>!<sup>†</sup> Looking for help getting started with a project? Have a question that you need answered? Was it not answered last week? Did not get a satisfying answer? A question that you&#39;ve only done basic research for? Maybe something you think everyone but you knows? <strong>Ask your question in the comments on this page,</strong> operators are standing by!</p> <p>This helpdesk and idea thread is here so that the front page won&#39;t be filled with these same questions day in and day out:</

