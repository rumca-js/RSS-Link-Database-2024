# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## A new release of Raspberry Pi OS
 - [https://www.reddit.com/r/raspberry_pi/comments/1ge8qq1/a_new_release_of_raspberry_pi_os](https://www.reddit.com/r/raspberry_pi/comments/1ge8qq1/a_new_release_of_raspberry_pi_os)
 - RSS feed: $source
 - date published: 2024-10-28T18:03:42+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/phattmatt"> /u/phattmatt </a> <br/> <span><a href="https://www.raspberrypi.com/news/a-new-release-of-raspberry-pi-os/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ge8qq1/a_new_release_of_raspberry_pi_os/">[comments]</a></span>

## Why the readings from an input pin are wrong until I use an external pull-up resistor?
 - [https://www.reddit.com/r/raspberry_pi/comments/1ge2jhy/why_the_readings_from_an_input_pin_are_wrong](https://www.reddit.com/r/raspberry_pi/comments/1ge2jhy/why_the_readings_from_an_input_pin_are_wrong)
 - RSS feed: $source
 - date published: 2024-10-28T13:51:02+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone!</p> <p>This is my first post on reddit :)</p> <p>I am a software engineer, but I only started playing with the Raspberry recently for a simple projects we have with some friends. We&#39;re building a water cleaning system that pumps dirty water from a well into a large tank (tank1), were some filters clean it, then the cleaned water is pumped into a smaller tank (tank2) from where it can be used inside the house.</p> <p>The code for the system is at <a href="https://github.com/etamponi/dolianova">https://github.com/etamponi/dolianova</a>.</p> <p>The interesting bit is the &quot;Button&quot; inputs:</p> <pre><code> self.sensor_pins = { &#39;tank1_min_level&#39;: Button(26), &#39;tank1_max_level&#39;: Button(16), &#39;tank2_min_level&#39;: Button(6), &#39;tank2_max_level&#39;: Button(12), } </code></pre> <p>A &quot;Button&quot; is an input that is wired with a pull-up resistor, so when the &quot;button&quot; is pressed, the input is LOW. I

## Picture frame instead of RPi case
 - [https://www.reddit.com/r/raspberry_pi/comments/1ge0qko/picture_frame_instead_of_rpi_case](https://www.reddit.com/r/raspberry_pi/comments/1ge0qko/picture_frame_instead_of_rpi_case)
 - RSS feed: $source
 - date published: 2024-10-28T12:26:47+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1ge0qko/picture_frame_instead_of_rpi_case/"> <img src="https://b.thumbs.redditmedia.com/bs2wh8eWSWS7ZhgXHe9yxONVPkIZrx9sup3xfOA3OhE.jpg" alt="Picture frame instead of RPi case" title="Picture frame instead of RPi case" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Using RPi4 as a internet radio receiver and remote network access point. Kept it loose on the desk with bunch of wires tangling around it. Decided to frame it and have it on display instead. $4 frame with glass front.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mattcabb"> /u/mattcabb </a> <br/> <span><a href="https://www.reddit.com/gallery/1ge0qko">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ge0qko/picture_frame_instead_of_rpi_case/">[comments]</a></span> </td></tr></table>

## VLC Playback in full screen with a Pi 5 doesnt work well.
 - [https://www.reddit.com/r/raspberry_pi/comments/1gdtx2o/vlc_playback_in_full_screen_with_a_pi_5_doesnt](https://www.reddit.com/r/raspberry_pi/comments/1gdtx2o/vlc_playback_in_full_screen_with_a_pi_5_doesnt)
 - RSS feed: $source
 - date published: 2024-10-28T04:29:19+00:00

<!-- SC_OFF --><div class="md"><p>I have the following script:</p> <pre><code>def start_vlc(): media_files = get_media_files() if media_files: create_playlist(media_files) # Prepare command to play videos and images in VLC using the playlist with hardware decoding command = [ &#39;cvlc&#39;, &#39;--one-instance&#39;, &#39;--no-embedded-video&#39;, &#39;--playlist-autostart&#39;, &#39;--loop&#39;, &#39;--no-video-title-show&#39;, &#39;--fullscreen&#39;, &#39;--image-duration=5&#39;, playlist_file ] print(f&quot;Starting VLC with command: {command}&quot;) # Start VLC with the playlist subprocess.Popen(command, stdout=subprocess.DEVNULL, stderr=subprocess.DEVNULL) else: print(&quot;No media files found to play.&quot;) </code></pre> <p>It works quite well when the vlc command does not include &#39;--fullscreen&#39;. Even when I manually put it in full screen, playback is flawless. However, when I use the fullscreen command, some of the image files play black, and the video files are so s

## Help with driver for ReSpeaker 2-Mics Pi HAT
 - [https://www.reddit.com/r/raspberry_pi/comments/1gdpvjl/help_with_driver_for_respeaker_2mics_pi_hat](https://www.reddit.com/r/raspberry_pi/comments/1gdpvjl/help_with_driver_for_respeaker_2mics_pi_hat)
 - RSS feed: $source
 - date published: 2024-10-28T00:44:42+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1gdpvjl/help_with_driver_for_respeaker_2mics_pi_hat/"> <img src="https://b.thumbs.redditmedia.com/ZDBjDVteMjDKbq4JEAbr5iZrOwBzX6R_nuvfsvhMGAw.jpg" alt="Help with driver for ReSpeaker 2-Mics Pi HAT" title="Help with driver for ReSpeaker 2-Mics Pi HAT" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey, I&#39;m trying to create jarvis, when trying to install the drivers for the ReSpeaker 2-Mics Pi HAT I get an error saying I&#39;m not on the updated kernel. I go to check and I am. Not to sure how to solve this issue. I&#39;m using the raspberry pi 5 and ReSpeaker 2-Mics Pi HAT. Using the most up to date OS. Any help would be appreciated!</p> <p><a href="https://preview.redd.it/57vebt8x8exd1.png?width=834&amp;format=png&amp;auto=webp&amp;s=ef9b47be3fdfbf123b0bba9a830c4049255a5f45">https://preview.redd.it/57vebt8x8exd1.png?width=834&amp;format=png&amp;auto=webp&amp;s=ef9b47be3fdfbf123b0bba9a830c4049255a5f45</a>

