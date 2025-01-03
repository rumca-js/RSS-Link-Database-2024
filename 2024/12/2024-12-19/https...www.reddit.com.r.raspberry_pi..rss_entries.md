# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## KMS and FKMS Overscan Breaking with Composite Output
 - [https://www.reddit.com/r/raspberry_pi/comments/1hi1ey8/kms_and_fkms_overscan_breaking_with_composite](https://www.reddit.com/r/raspberry_pi/comments/1hi1ey8/kms_and_fkms_overscan_breaking_with_composite)
 - RSS feed: $source
 - date published: 2024-12-19T19:50:53+00:00

<!-- SC_OFF --><div class="md"><p>Im currently trying to use a Raspberry Pi Model B+ to stream SD video to an old RCA TruFlat CRT TV. However, when I use KMS or FKMS drivers the overscan settings, that I NEED to see the TV properly, stop applying after about 1 to 2 minutes (see video). Additionally, when I don&#39;t explicitly force KMS or FKMS in the config the overscan stays applied forever, but I cannot load into the GUI using &quot;startx&quot; because it then says I have no devices found. My current config settings are as follows: </p> <p><code>dtparam=audio=on</code></p> <p><code>display_auto_detect=1</code></p> <p><code>#dtoverlay=vc4-kms-v3d,composite=1</code></p> <p><code>#dtoverlay=vc4-fkms-v3d,composite=1</code></p> <p><code>enable_tvout=1</code></p> <p><code>sdtv_mode=0</code></p> <p><code>sdtv_aspect=1</code></p> <p><code>overscan_bottom=10</code></p> <p><code>overscan_top=10</code></p> <p><code>overscan_left=20</code></p> <p><code>overscan_right=20</code></p> <p><code>h

## Screen Issues with LineageOS 22 (Android 15) Raspberry Pi 5
 - [https://www.reddit.com/r/raspberry_pi/comments/1hhxwi9/screen_issues_with_lineageos_22_android_15](https://www.reddit.com/r/raspberry_pi/comments/1hhxwi9/screen_issues_with_lineageos_22_android_15)
 - RSS feed: $source
 - date published: 2024-12-19T17:19:48+00:00

<!-- SC_OFF --><div class="md"><p>Hi!</p> <p>Currently working on a project using [KonstaKANG&#39;s Build of LineageOS 22 for the Raspberry Pi 5](<a href="https://konstakang.com/devices/rpi5/LineageOS22/">https://konstakang.com/devices/rpi5/LineageOS22/</a>) and I am running into a game-breaking issue.</p> <p>When I boot, it randomly switches from seeing the whole screen to it randomly zooming into the upper half, and I have to wait for it to zoom out temporarily to pick any options. I originally tried it on the 70&quot; Touchscreen I&#39;m working on, but then I tried a fresh copy on a LG monitor with the same issue, so I feel it might be an issue with the build of LineageOS or possibly a setting I missed.</p> <p>However, when trying to enable ADB Debugging via Developer Options, the Build Number clicking is impossible, even with a mouse and keyboard. It&#39;s like build number is grayed out and unclickable, so I am unable to get to Developer Options to possible SSH via ADB to possi

## trying to install inky 7" on zero 2 w.
 - [https://www.reddit.com/r/raspberry_pi/comments/1hhwu95/trying_to_install_inky_7_on_zero_2_w](https://www.reddit.com/r/raspberry_pi/comments/1hhwu95/trying_to_install_inky_7_on_zero_2_w)
 - RSS feed: $source
 - date published: 2024-12-19T16:34:00+00:00

<!-- SC_OFF --><div class="md"><p>Hey Everyone, </p> <p>I am trying to get an inky 7&quot; running on my Pi zero 2 W and keep getting the following error even after adding <code>dtoverlay=spi0-0cs</code> to <code>/boot/firmware/config.txt</code>.</p> <p>Woah there, some pins we need are in use!</p> <p>⚠️ Chip Select: (line 8, SPI_CE0_N) currently claimed by spi-bcm2835</p> <p>I have searched far and wide, new installs, different pi software (Bookworm and Bullseye) but I continue to get that error. I am trying to get this up and running as a Christmas gift and I&#39;m pulling out my hair over here. This is the project I am trying to do as well</p> <p><a href="https://github.com/dylski/PaperPiAI">https://github.com/dylski/PaperPiAI</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rotian28"> /u/rotian28 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hhwu95/trying_to_install_inky_7_on_zero_2_w/">[link]</a></span> &#32; 

## Can't find NVMe in the installer via Waveshare PoE M.2 HAT+
 - [https://www.reddit.com/r/raspberry_pi/comments/1hhvhog/cant_find_nvme_in_the_installer_via_waveshare_poe](https://www.reddit.com/r/raspberry_pi/comments/1hhvhog/cant_find_nvme_in_the_installer_via_waveshare_poe)
 - RSS feed: $source
 - date published: 2024-12-19T15:34:17+00:00

<!-- SC_OFF --><div class="md"><p>I have bought a Raspberry Pi 5 and I am trying to use the Waveshare PoE M.2 HAT+. I also bought Raspberry Pis own 256 GB NVMe M.2 drive with it.</p> <p>When I connect it all together, the PoE parts works fine since it starts up. It downloads the installer so it has a network connection and I find the device and OS I want, but it can&#39;t find the NVMe drive I installed on the HAT.</p> <p>I have tried reseating the drive and rebooting, but it is not recognized yet. </p> <p>Do I need to do something so the drive beforehand or should it work of the bat?<br/> For referance I am trying to use it for Home Assistant so I am not going to install any other &quot;regular&quot; OS&#39;s.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rgjertsen"> /u/rgjertsen </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hhvhog/cant_find_nvme_in_the_installer_via_waveshare_poe/">[link]</a></span> &#32; <span><a

## Which external drive are you using?
 - [https://www.reddit.com/r/raspberry_pi/comments/1hhttgg/which_external_drive_are_you_using](https://www.reddit.com/r/raspberry_pi/comments/1hhttgg/which_external_drive_are_you_using)
 - RSS feed: $source
 - date published: 2024-12-19T14:15:46+00:00

<!-- SC_OFF --><div class="md"><p>Hi there, </p> <p>I&#39;ve been running my Raspberry Pi 4B on an <a href="https://www.amazon.com/SanDisk-128GB-Ultra%C2%AE-microSDXC-120MB/dp/B08L5DBMMS">Sandisk SD Card</a> for over a year now, mainly for a dockerized home assistant, but now that I&#39;d like to add some media server features, I&#39;ll need some more space. </p> <p>Naturally, I&#39;ve been reading through a lot of posts to see if it&#39;s worth switching to a proper SSD...and ho boy! was I not surprised to see the ongoing war about the pros and cons of each solution.</p> <p>So, instead of re-asking the same question, let&#39;s get some real-world data with this community by answering these questions : </p> <p>1 - What storage solution are you currently using ? (type and model)<br/> 2 - For external hard drive users, what connector/case are you using?<br/> 3 - How long have you been using it? Did you have any issues or warning with it?<br/> 4 - What read/write speeds are you acheivin

## Pico wont start with Customer application
 - [https://www.reddit.com/r/raspberry_pi/comments/1hhsbn1/pico_wont_start_with_customer_application](https://www.reddit.com/r/raspberry_pi/comments/1hhsbn1/pico_wont_start_with_customer_application)
 - RSS feed: $source
 - date published: 2024-12-19T12:57:54+00:00

<!-- SC_OFF --><div class="md"><p>Currently I am trying to start a Programm on Raspberry Pico. When I Flash the sw, the Pico dies not reboot and Execute the Programm. (I toggled the Internal LED for verification) Is it correct, to link the _Start adress simply to the start of the ROM? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AutomaticBase5964"> /u/AutomaticBase5964 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hhsbn1/pico_wont_start_with_customer_application/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hhsbn1/pico_wont_start_with_customer_application/">[comments]</a></span>

## RP5 as a network video stream capture source?
 - [https://www.reddit.com/r/raspberry_pi/comments/1hhn6ba/rp5_as_a_network_video_stream_capture_source](https://www.reddit.com/r/raspberry_pi/comments/1hhn6ba/rp5_as_a_network_video_stream_capture_source)
 - RSS feed: $source
 - date published: 2024-12-19T06:57:49+00:00

<!-- SC_OFF --><div class="md"><p>I have a program that uses spout to stream video out. There is a Spout to NDI (<a href="https://leadedge.github.io/">https://leadedge.github.io/</a>) package out there that will send Spout to a network source via NDI. I&#39;d like to run OBS and capture the NDI stream on an RP5 using an NVME/M.2 hat and record the data over the PCIe 3.0 bus (per Jeff Geerling&#39;s report, <a href="https://www.jeffgeerling.com/blog/2023/forcing-pci-express-gen-30-speeds-on-pi-5">https://www.jeffgeerling.com/blog/2023/forcing-pci-express-gen-30-speeds-on-pi-5</a>)</p> <p>I&#39;d like to get 1080p60 over the network onto the RP5. My devices will be on a wired 1GB Ethernet network. I won&#39;t really need audio, and I&#39;m not sure if I can send just a video stream only to the RP5 (to possibly reduce bandwidth)</p> <p>Does anyone see any flaws or disadvantages or impossibilities in this hypothetical setup?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="http

## Need Help with correct resolution on RPI5
 - [https://www.reddit.com/r/raspberry_pi/comments/1hhmeqc/need_help_with_correct_resolution_on_rpi5](https://www.reddit.com/r/raspberry_pi/comments/1hhmeqc/need_help_with_correct_resolution_on_rpi5)
 - RSS feed: $source
 - date published: 2024-12-19T06:06:02+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I am using an RPI5 with the RPI-OS, and I have connected it to a flatscreen 4k tv, but the only options for changing the resolution in the display configuration is upto 1024x768.</p> <p>When I booted for the first time during the setup phase the RPI was giving a proper 4k output. </p> <p>How do I correct this? </p> <p>Please help!! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/uNcLePsYcO"> /u/uNcLePsYcO </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hhmeqc/need_help_with_correct_resolution_on_rpi5/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hhmeqc/need_help_with_correct_resolution_on_rpi5/">[comments]</a></span>

## Connection between raspberry pi 3 and windows text box to simulate keyboard
 - [https://www.reddit.com/r/raspberry_pi/comments/1hhfw9m/connection_between_raspberry_pi_3_and_windows](https://www.reddit.com/r/raspberry_pi/comments/1hhfw9m/connection_between_raspberry_pi_3_and_windows)
 - RSS feed: $source
 - date published: 2024-12-19T00:12:35+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone. I&#39;m looking for help on a project that I haven&#39;t been able to make much progress on.<br/> I have a raspberry pi 3 with Raspberry Pi OS and the task I am looking to accomplish is a connection between the raspberry and a windows text box, so that when I type something on the raspberry, the text appears in the windows cursor and is Add the text to a text box, such as a search engine or notepad.<br/> I&#39;ve tried python libraries like &quot;paramiko&quot; and &quot;pyperclip&quot;, both for a network solution, but no luck. I also tried using the raspberry as HID but apparently Windows does not recognize it.<br/> I&#39;m just looking for a quick and effective solution, so that it can be done easily and without having to install too many things on both the raspberry pi 3 and my Windows 11 computer.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mediocre-Camera7355"> /u/Mediocre-Camera7355 </

