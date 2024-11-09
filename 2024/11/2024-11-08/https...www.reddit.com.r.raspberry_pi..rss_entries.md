# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Can't use PyAudio in a service
 - [https://www.reddit.com/r/raspberry_pi/comments/1gmnvks/cant_use_pyaudio_in_a_service](https://www.reddit.com/r/raspberry_pi/comments/1gmnvks/cant_use_pyaudio_in_a_service)
 - RSS feed: $source
 - date published: 2024-11-08T17:23:38+00:00

<!-- SC_OFF --><div class="md"><p>I have Python code that uses PyAudio to listen to the sound from the microphone on my Raspberry Pi. It runs fine in terminal in python3.</p> <p>But when I try to run my program as a startup service, it fails while trying to execute:</p> <p>pa = pyaudio.PyAudio()</p> <p>_stream = pa.open(format=pyaudio.paInt16,</p> <p>channels=1, rate=SAMPLING_RATE,</p> <p>input=True,</p> <p>frames_per_buffer=NUM_SAMPLES)</p> <p>The error message is: </p> <p>Nov 08 10:59:11 raspberrypi python3[7262]: File &quot;/home/pi/laundry_alarm/laundry_alarm.py&quot;, line 125, in &lt;module&gt;</p> <p>Nov 08 10:59:11 raspberrypi python3[7262]: _stream = pa.open(format=pyaudio.paInt16,</p> <p>Nov 08 10:59:11 raspberrypi python3[7262]: File &quot;/usr/lib/python3/dist-packages/pyaudio.py&quot;, line 750, in open</p> <p>Nov 08 10:59:11 raspberrypi python3[7262]: stream = Stream(self, *args, **kwargs)</p> <p>Nov 08 10:59:11 raspberrypi python3[7262]: File &quot;/usr/lib/python3/dis

## Half-Life running on RPI 4B (Tiny11 arm64)
 - [https://www.reddit.com/r/raspberry_pi/comments/1gmmwb6/halflife_running_on_rpi_4b_tiny11_arm64](https://www.reddit.com/r/raspberry_pi/comments/1gmmwb6/halflife_running_on_rpi_4b_tiny11_arm64)
 - RSS feed: $source
 - date published: 2024-11-08T16:42:52+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1gmmwb6/halflife_running_on_rpi_4b_tiny11_arm64/"> <img src="https://preview.redd.it/voptkwc0ipzd1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=7e5f47c50d28afac6fdf57e713c431b909e9d1c6" alt="Half-Life running on RPI 4B (Tiny11 arm64) " title="Half-Life running on RPI 4B (Tiny11 arm64) " /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ZTE2976"> /u/ZTE2976 </a> <br/> <span><a href="https://i.redd.it/voptkwc0ipzd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gmmwb6/halflife_running_on_rpi_4b_tiny11_arm64/">[comments]</a></span> </td></tr></table>

## A project for my boat
 - [https://www.reddit.com/r/raspberry_pi/comments/1gml2f7/a_project_for_my_boat](https://www.reddit.com/r/raspberry_pi/comments/1gml2f7/a_project_for_my_boat)
 - RSS feed: $source
 - date published: 2024-11-08T15:25:14+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1gml2f7/a_project_for_my_boat/"> <img src="https://b.thumbs.redditmedia.com/ipXWq_1LywrPXawsCKSYiHR_RPKRI9vZwNbhFBNRt6Y.jpg" alt="A project for my boat" title="A project for my boat" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/dbjyf4yx2pzd1.jpg?width=4000&amp;format=pjpg&amp;auto=webp&amp;s=09dac8933a83e7d12421352f080252169b451289">https://preview.redd.it/dbjyf4yx2pzd1.jpg?width=4000&amp;format=pjpg&amp;auto=webp&amp;s=09dac8933a83e7d12421352f080252169b451289</a></p> <p><a href="https://preview.redd.it/ait3izwx2pzd1.jpg?width=4000&amp;format=pjpg&amp;auto=webp&amp;s=e3e2c7f2c1d1362dd1f7fb7c7f89cc773f3e1e71">https://preview.redd.it/ait3izwx2pzd1.jpg?width=4000&amp;format=pjpg&amp;auto=webp&amp;s=e3e2c7f2c1d1362dd1f7fb7c7f89cc773f3e1e71</a></p> <p><a href="https://preview.redd.it/twhrhzwx2pzd1.jpg?width=4000&amp;format=pjpg&amp;auto=webp&amp;s=2d48d775f052d93bea173d99936717

## We wanted to save some money on GitHub Actions, so now we run builders on a Kubernetes cluster of Raspberry Pis alongside our main cloud infrastructure. I think we're onto something! Is anyone interested in trying it out and giving some feedback?
 - [https://www.reddit.com/r/raspberry_pi/comments/1gmidna/we_wanted_to_save_some_money_on_github_actions_so](https://www.reddit.com/r/raspberry_pi/comments/1gmidna/we_wanted_to_save_some_money_on_github_actions_so)
 - RSS feed: $source
 - date published: 2024-11-08T13:21:49+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1gmidna/we_wanted_to_save_some_money_on_github_actions_so/"> <img src="https://b.thumbs.redditmedia.com/aXVV5u_qIKyjNcXEdHI1Lu_n9v9xkxhstfyEbrGGE7k.jpg" alt="We wanted to save some money on GitHub Actions, so now we run builders on a Kubernetes cluster of Raspberry Pis alongside our main cloud infrastructure. I think we're onto something! Is anyone interested in trying it out and giving some feedback?" title="We wanted to save some money on GitHub Actions, so now we run builders on a Kubernetes cluster of Raspberry Pis alongside our main cloud infrastructure. I think we're onto something! Is anyone interested in trying it out and giving some feedback?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi all! I have an interesting story to share! 😊 I’m working as a software developer on a fairly large project that takes ages to build. We run GitHub Actions on every push, and some time ago, we were surprised by

## Using Raspberry Pi's for my AI Smart Scale Project!
 - [https://www.reddit.com/r/raspberry_pi/comments/1gmcvo6/using_raspberry_pis_for_my_ai_smart_scale_project](https://www.reddit.com/r/raspberry_pi/comments/1gmcvo6/using_raspberry_pis_for_my_ai_smart_scale_project)
 - RSS feed: $source
 - date published: 2024-11-08T07:09:26+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1gmcvo6/using_raspberry_pis_for_my_ai_smart_scale_project/"> <img src="https://external-preview.redd.it/zE-dgFKU-L1TVc7MwcetojQabXNaDKvj3iHlgwLn4Tc.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=6264a7949addca547f901691ecfe5f879cfc755d" alt="Using Raspberry Pi's for my AI Smart Scale Project! " title="Using Raspberry Pi's for my AI Smart Scale Project! " /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Engineering_Dad"> /u/Engineering_Dad </a> <br/> <span><a href="https://youtu.be/VKnfQoW93vo?si=srKb-nEXmrYN5n2s">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1gmcvo6/using_raspberry_pis_for_my_ai_smart_scale_project/">[comments]</a></span> </td></tr></table>

## Dollar Bill Acceptor (pulse) to Raspberrypi
 - [https://www.reddit.com/r/raspberry_pi/comments/1gm9s6r/dollar_bill_acceptor_pulse_to_raspberrypi](https://www.reddit.com/r/raspberry_pi/comments/1gm9s6r/dollar_bill_acceptor_pulse_to_raspberrypi)
 - RSS feed: $source
 - date published: 2024-11-08T03:57:30+00:00

<!-- SC_OFF --><div class="md"><p>Has anyone been successful rigging up a dollar bill acceptor to a pi? I see there are some pi hats available but is really like to not have to work with a hat if not needed. I’ve been working on this for the better part of the day and nothing I do with my python script seems to be helping. I think the issue is the speed of the pulse - probably under 5-6ms - the pulse is 12vdc - witch I have an adjustable step down set up to it stepping it down to 3.2v which the pi should handle from what I’ve read. Normally open to gpio pin and common ground to ground.</p> <p>The real hitter is my script starts when unplugging and plugging back in the gpio, but not from the pulse of the dba when a dollar is inserted. </p> <p>If anyone’s had any success with this could you please point me in the right direction? I’ve seen cereal usb set ups but don’t quite understand how I would go about using one.</p> <p>Thank you</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a 

