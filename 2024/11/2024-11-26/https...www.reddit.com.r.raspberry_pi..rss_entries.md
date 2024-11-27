# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Controlling Model Lighting - Simultaneous animation
 - [https://www.reddit.com/r/raspberry_pi/comments/1h0f3xx/controlling_model_lighting_simultaneous_animation](https://www.reddit.com/r/raspberry_pi/comments/1h0f3xx/controlling_model_lighting_simultaneous_animation)
 - RSS feed: $source
 - date published: 2024-11-26T15:55:03+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to add lighting to a miniature scale project in a scifi diorama but everything feels really linear and rigid. For example, i have one line cycling using PWM up and down in brightness like an alarm and I want another light that flickers simulating blasters or broken wires. However, right now when the second light goes through its flicker animation, the first led pauses at the set brightness and resumes when the flicker is over. I&#39;m using random number generators to trigger the timing so it is random but I would like to get rid of the obvious pause. </p> <p>I am on a pico so I know it will run as a loop but how do I make this feel more organic?</p> <p>the switch is just setting the upper and lower bound</p> <p>brightness is the pulsing LED</p> <p>stutter pattern is a function to add some randomness to the blink pattern based on each letter</p> <pre><code>while True: while switch == 1: brightness += 30 pwm.duty_u16(brightness) sleep(0

## Portable Arcade Machine
 - [https://www.reddit.com/r/raspberry_pi/comments/1h0c4y0/portable_arcade_machine](https://www.reddit.com/r/raspberry_pi/comments/1h0c4y0/portable_arcade_machine)
 - RSS feed: $source
 - date published: 2024-11-26T13:41:50+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1h0c4y0/portable_arcade_machine/"> <img src="https://b.thumbs.redditmedia.com/L1YBqYOx4ByjB5k3uPTs8VruhcWlkaB3vMGCT2hQVeo.jpg" alt="Portable Arcade Machine" title="Portable Arcade Machine" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Completed 2 Cyberdeck&#39;s, each running a Lakka ROM Emulator for portable retro gaming that can be slung around the body using a modular Orbit Gear sling⚡️⚡️ (my personal is sticker bombed and the other is a comission for a friend)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/_kniives"> /u/_kniives </a> <br/> <span><a href="https://www.reddit.com/gallery/1h0c4y0">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1h0c4y0/portable_arcade_machine/">[comments]</a></span> </td></tr></table>

## Customized and reproducible OS images (not Yocto)
 - [https://www.reddit.com/r/raspberry_pi/comments/1h09gqc/customized_and_reproducible_os_images_not_yocto](https://www.reddit.com/r/raspberry_pi/comments/1h09gqc/customized_and_reproducible_os_images_not_yocto)
 - RSS feed: $source
 - date published: 2024-11-26T11:14:12+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I am working on a small app that&#39;s a bunch of Python, C, and JS files that get bundled together on a 4b device and sent to a potential customer for testing. These files are in different locations: the Python packages are in your traditional <code>site-packages</code> folder, the JS and C stuff is in the home folder (<code>pi</code>). Then I create an image of my SD card and hand it to the customer with a script that mounts the image and places the files in the right locations, since I can&#39;t flash the pi while it&#39;s running. Finally I flash my SD card to our version of <code>bookworm</code> and do the whole thing again.</p> <p>Now I want to find a nice and more elegant way of creating these images so that I can put them on some sort of CI pipeline. Yocto is a pain with Python - the packages I use aren&#39;t available in <code>meta-python</code> so I haven&#39;t even gotten past that yet and I am not sure if the JS files

