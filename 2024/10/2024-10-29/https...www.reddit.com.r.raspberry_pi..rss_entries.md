# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Very slow Pi 400 (Fresh Install)
 - [https://www.reddit.com/r/raspberry_pi/comments/1gf7m0b/very_slow_pi_400_fresh_install](https://www.reddit.com/r/raspberry_pi/comments/1gf7m0b/very_slow_pi_400_fresh_install)
 - RSS feed: $source
 - date published: 2024-10-29T22:38:04+00:00

<!-- SC_OFF --><div class="md"><p>I have a old Pi 400 4G, And installed Pi OS (Bookworm X64) on a new (brand new) Verbatim 32GB USB. It takes half a minute or more to start Firefox, And the rest is slow too. Pi Menu opens fast and fine, And no mouse lag. I&#39;m using the official power adapter and I&#39;m using a old Philips SMART TV. Dont know if that matters. My CPU Usage is at 100% while all apps say &quot;0%&quot;. I don&#39;t know why it&#39;s this slow. Please help :/</p> <p>Note: not overloading it. No other apps are open, and I&#39;m simply trying to use a PPPWN loader to automatically re-add GoldHen to my PS4 each time it starts. I have no fans, coolers, just a standard Pi 400. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Correct_Surprise2049"> /u/Correct_Surprise2049 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gf7m0b/very_slow_pi_400_fresh_install/">[link]</a></span> &#32; <span><a href="https://www.r

## I made a Voice Controlled Bartender Robot with A Pi 4
 - [https://www.reddit.com/r/raspberry_pi/comments/1get9kf/i_made_a_voice_controlled_bartender_robot_with_a](https://www.reddit.com/r/raspberry_pi/comments/1get9kf/i_made_a_voice_controlled_bartender_robot_with_a)
 - RSS feed: $source
 - date published: 2024-10-29T12:22:29+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1get9kf/i_made_a_voice_controlled_bartender_robot_with_a/"> <img src="https://external-preview.redd.it/qamKA62PX9Uomg3_6GjAHL3nta6c_6zE6opicWBvBnc.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=98eb0e11b8b2237d0b74cab69a887a64861789d6" alt="I made a Voice Controlled Bartender Robot with A Pi 4" title="I made a Voice Controlled Bartender Robot with A Pi 4" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/-2811"> /u/-2811 </a> <br/> <span><a href="https://www.youtube.com/watch?v=Akv8ZLIwzus&amp;t=8s&amp;ab_channel=TerenceGrover">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1get9kf/i_made_a_voice_controlled_bartender_robot_with_a/">[comments]</a></span> </td></tr></table>

## Any tips for low latency video streaming using v4l2h264enc?
 - [https://www.reddit.com/r/raspberry_pi/comments/1geq4ym/any_tips_for_low_latency_video_streaming_using](https://www.reddit.com/r/raspberry_pi/comments/1geq4ym/any_tips_for_low_latency_video_streaming_using)
 - RSS feed: $source
 - date published: 2024-10-29T09:01:34+00:00

<!-- SC_OFF --><div class="md"><p>Hello. Just doing a project, where I need the latency as low as possible. The idea is to stream the video from a raspberry pi (currently using zero 2 w) to a pc in the local network via UDP. Would appreciate any tips of getting low latency. The latency I currently get is glass to glass 130ms. Is there any way to make it lower? Some of the settings of the pipeline:</p> <ul> <li> h264_profile: 1 (Main profile)</li> <li>h264_level: 4 (Level 4.0)</li> <li>h264_i_frame_period: 60 (I-frame every 60 frames = 2 seconds at 30fps)</li> <li>h264_slice_mode: 0 (Single slice per frame)</li> <li>video_b_frames: 0 (No B-frames)</li> <li>h264_entropy_mode: 0 (CAVLC encoding)</li> <li>rtp parameters: config-interval: 1</li> <li>rtp parameters: pt (payload type): 96</li> <li>udp sink parameters: sync = false, async = false, buffer-size = buffer-size: 2097152</li> <li>video_bitrate: 3000000 (3 Mbps)</li> <li>video_bitrate_mode: 0 (Constant bitrate mode)</li> </ul> <p>T

