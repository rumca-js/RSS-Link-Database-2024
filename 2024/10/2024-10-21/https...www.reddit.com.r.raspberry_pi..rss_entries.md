# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Snake Eyes Bonnet - My first Project and its already frustrating :)
 - [https://www.reddit.com/r/raspberry_pi/comments/1g8tcfw/snake_eyes_bonnet_my_first_project_and_its](https://www.reddit.com/r/raspberry_pi/comments/1g8tcfw/snake_eyes_bonnet_my_first_project_and_its)
 - RSS feed: $source
 - date published: 2024-10-21T16:05:04+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>so i tried the <a href="https://learn.adafruit.com/animated-snake-eyes-bonnet-for-raspberry-pi/">Snake Eyes</a> Project and i kind of hit a dead end, since the Software stops with an Error.</p> <p>But first let me tell you what i tried:</p> <p>Installed the 32bit OS Lite on a Raspberry Pi5 (as stated in the manual)</p> <p>Downloaded the Script via </p> <pre><code>cd curl https://raw.githubusercontent.com/adafruit/Raspberry-Pi-Installer-Scripts/master/pi-eyes.sh &gt;pi-eyes.sh sudo bash pi-eyes.sh </code></pre> <p>Rebooted - this then caused an Error telling me that pi3d is not installed.</p> <p>I fiddled around a bit, realized i needed</p> <pre><code>sudo apt-get install python-imaging python-imaging-tk </code></pre> <p>and</p> <pre><code>sudo pip3 install --break-system-packages adafruit-blinka </code></pre> <p>to at least get rid of the pip3 and pi3d errors (i was also missing some &quot;board&quot; module) but everything sorted out, a

## Investment Platform hosted on a Pi 3
 - [https://www.reddit.com/r/raspberry_pi/comments/1g8sdd0/investment_platform_hosted_on_a_pi_3](https://www.reddit.com/r/raspberry_pi/comments/1g8sdd0/investment_platform_hosted_on_a_pi_3)
 - RSS feed: $source
 - date published: 2024-10-21T15:25:56+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys!</p> <p>I&#39;ve recently created a platform for backtesting asset allocations (<a href="https://InvestTester.com">https://InvestTester.com</a>), and recently I&#39;ve implemented some improvements from feedback of the community:</p> <ul> <li>Algo trading simulation with JavaScript;</li> <li>Addition of new cryptocurrency assets (BTC, ETH, USDT, etc);</li> <li>Multi-language support (en, pt-BR, pt, es, fr, ja, zh);</li> <li>Performance optimizations – simulations that used to take over 60 seconds now run in about 5 to 10 seconds.</li> </ul> <p>The platform is hosted on a Raspberry Pi 3 Model B, which was suffering a bit when running multiple simulations at the same time, but got much better after the performance optimization</p> <p>This is the first project of this scale that I’ve launched, so I&#39;d love any feedback or suggestions for improvement!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pessia

## SongPi - Continuous song recognition app written in Python
 - [https://www.reddit.com/r/raspberry_pi/comments/1g8q2ms/songpi_continuous_song_recognition_app_written_in](https://www.reddit.com/r/raspberry_pi/comments/1g8q2ms/songpi_continuous_song_recognition_app_written_in)
 - RSS feed: $source
 - date published: 2024-10-21T13:46:22+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1g8q2ms/songpi_continuous_song_recognition_app_written_in/"> <img src="https://b.thumbs.redditmedia.com/Zf11rgS_xuExqPK3Mb8NbbYC_6dUk3y1-smvhz5bbVY.jpg" alt="SongPi - Continuous song recognition app written in Python" title="SongPi - Continuous song recognition app written in Python" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mildywot"> /u/mildywot </a> <br/> <span><a href="/r/RASPBERRY_PI_PROJECTS/comments/1g8q0j0/songpi_continuous_song_recognition_app_written_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1g8q2ms/songpi_continuous_song_recognition_app_written_in/">[comments]</a></span> </td></tr></table>

## I2S on Raspberry Pi 5
 - [https://www.reddit.com/r/raspberry_pi/comments/1g8pug5/i2s_on_raspberry_pi_5](https://www.reddit.com/r/raspberry_pi/comments/1g8pug5/i2s_on_raspberry_pi_5)
 - RSS feed: $source
 - date published: 2024-10-21T13:35:40+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m currently trying to understand how to make the I2S work on the Raspberry Pi 5. I don&#39;t see much documentation online on how to make it work. Since the RP1 documentation is still at the Draft state which only state that their is a I2S 4 bi-directionnal channel clock consummer, I&#39;m a little bit lock in the process.</p> <p>I have see ways of making it work on the Raspberry Pi 4 with enable i2s-mmap overlays in the config.txt. The curious thing is that I don&#39;t see this overlays in /boot/overlays. I only see those following : i2s-dac.dtbo, i2s-gpio28-31.dtbo and i2s-master-dac.dtbo.</p> <p>To give more detail, my goal is to make the reception of a sinus waveform comming from the teensy 4.1 on the i2s1 pins. Any help would be appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/WilliamBumbre123"> /u/WilliamBumbre123 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1g8

## Rust code keeps using HDMI audio instead of AV
 - [https://www.reddit.com/r/raspberry_pi/comments/1g8nzqm/rust_code_keeps_using_hdmi_audio_instead_of_av](https://www.reddit.com/r/raspberry_pi/comments/1g8nzqm/rust_code_keeps_using_hdmi_audio_instead_of_av)
 - RSS feed: $source
 - date published: 2024-10-21T12:02:36+00:00

<!-- SC_OFF --><div class="md"><p>I am running a Rust script on my Pi running Raspbian, and it keep using the screen&#39;s speaker instead of the AV Jack, no matter what I do.</p> <p>When I disconnect the screen and reboot the Pi, it plays audio through AV as expected, but when the screen is connected, I can&#39;t get it to play on the AV speaker. Sound I play manually, like clicking an mp3 file, does play through AV, just not the audio that is played by the Rust code. I&#39;m using Soloud for the sound in Rust btw.</p> <p>I tried the following things already:</p> <ul> <li><p>changing the audio settings at the top of the screen, switching from hdmi to av jack</p></li> <li><p>going into the raspi-config menu and changing audio from pulseaudio to pipewire and back</p></li> <li><p>disabling HDMI audio by typing &quot;hdmi_ignore_edid_audio=1&quot;, or </p></li> </ul> <p>&quot;hdmi_drive=1</p> <p>dtparam=audio=on&quot;, or &quot;hdmi_ignore_audio=1&quot; in the /boot/firmware/config.txt f

