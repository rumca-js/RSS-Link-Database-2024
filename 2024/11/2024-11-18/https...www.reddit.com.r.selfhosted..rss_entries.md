# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Home Assistant teases new fully open source voice assistant hardware
 - [https://www.reddit.com/r/selfhosted/comments/1guiun2/home_assistant_teases_new_fully_open_source_voice](https://www.reddit.com/r/selfhosted/comments/1guiun2/home_assistant_teases_new_fully_open_source_voice)
 - RSS feed: $source
 - date published: 2024-11-18T23:25:57+00:00

<!-- SC_OFF --><div class="md"><p>This section of the latest announcement from Home Assistant sounded very exciting: <a href="https://www.home-assistant.io/blog/2024/11/15/roadmap-2024h2/#voice-assistants">https://www.home-assistant.io/blog/2024/11/15/roadmap-2024h2/#voice-assistants</a></p> <blockquote> <p>However, this is changing - over the past 6 months, we have built our own hardware! It will be the first voice assistant hardware built from the ground up to work with Home Assistant, fully open source (firmware and hardware), and it is going to be released very soon. It is truly the missing hardware piece to a more approachable voice experience in Home Assistant, and we cannot wait to see what you will build with it.</p> </blockquote> <p>Very much looking forward to being able to get rid of my Alexa devices! I&#39;ve been playing around with the voice functionality of Home Assistant via the Android app, and it seems really promising on the software side. I&#39;ve been on the look

## Tool to securely execute ssh commands in my non-publicly-accessible computers
 - [https://www.reddit.com/r/selfhosted/comments/1guiovk/tool_to_securely_execute_ssh_commands_in_my](https://www.reddit.com/r/selfhosted/comments/1guiovk/tool_to_securely_execute_ssh_commands_in_my)
 - RSS feed: $source
 - date published: 2024-11-18T23:18:34+00:00

<!-- SC_OFF --><div class="md"><p>Hi there, I’ve been working on this for some time now: the tool uses a two step process, one to request access and if access is given, a second where a port is exposed for a one-time execution of a command.</p> <p>To make this work it relies on a publicly accessible computer to act as the “rendezvous” server.</p> <p>So, via the internet, Alice requests access to Bob’s computer (signed http request) to an endpoint in the rendezvous server, the request is forwarded to Bob’s computer, where Bob’s computer can verify the signature and allow access. If access is granted the rendezvous server will open up a port and listen in for tcp connections on it (expecting the ssh request), when the request arrives it is proxies directly to Bob’s computer. Bob’s computer has an active tcp connection to the rendezvous server, which is used to forward/proxy the different calls (http and ssh) - for this, the tool does stream multiplexing via the active connection.</p> <

## Anyone got any experience with bracket tournament hoster
 - [https://www.reddit.com/r/selfhosted/comments/1gui2f1/anyone_got_any_experience_with_bracket_tournament](https://www.reddit.com/r/selfhosted/comments/1gui2f1/anyone_got_any_experience_with_bracket_tournament)
 - RSS feed: $source
 - date published: 2024-11-18T22:51:15+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, this is driving me nuts, ive managed to get it up and running (kinda?). When I try to log in I get internal server errors and can&#39;t get it to do anything but that. Also if there is a better swiss style tournament manager I&#39;m more than willing to stop trying to fix this 😭😭😭</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kevman289"> /u/kevman289 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gui2f1/anyone_got_any_experience_with_bracket_tournament/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gui2f1/anyone_got_any_experience_with_bracket_tournament/">[comments]</a></span>

## Endurain v0.6.0 - Garmin Connect integration is here
 - [https://www.reddit.com/r/selfhosted/comments/1guhr9k/endurain_v060_garmin_connect_integration_is_here](https://www.reddit.com/r/selfhosted/comments/1guhr9k/endurain_v060_garmin_connect_integration_is_here)
 - RSS feed: $source
 - date published: 2024-11-18T22:37:52+00:00

<!-- SC_OFF --><div class="md"><p>Hello its me again talking about Endurain, a fitness activity tracker that you can self host. A new version is out and here are some highlights:</p> <ul> <li>Garmin Connect integration.</li> <li>Strava unlink functionality.</li> <li>User can now input his/hers height.</li> <li>Docs page available at <a href="https://docs.endurain.com/">https://docs.endurain.com</a> hosted using GitHub Pages.</li> <li>Some general bug fixes.</li> </ul> <p><a href="https://github.com/jonasoreland/runnerup/pull/1193">RunnerUp</a> now supports Endurain activity import directly from Android devices but is currently broke for the new version. An <a href="https://github.com/jonasoreland/runnerup/issues/1205">issue</a> is open to fix this.<br/> For iOS still no news.</p> <p>For the next version(s) I will focus on more or less in order:</p> <ul> <li>Blood glucose data from Abbott Freestyle CGM</li> <li>BMI in the new health zone</li> <li>Add some additional Strava functionali

## macOS wireguard local DNS issues
 - [https://www.reddit.com/r/selfhosted/comments/1guhiqf/macos_wireguard_local_dns_issues](https://www.reddit.com/r/selfhosted/comments/1guhiqf/macos_wireguard_local_dns_issues)
 - RSS feed: $source
 - date published: 2024-11-18T22:27:41+00:00

<!-- SC_OFF --><div class="md"><p>MacOS can&#39;t ping when connected to local DNS and Wireguard</p> <p>I have a DNS Sinkhole (AdGuard Plus) and VPN (Wireguard) which works perfectly on my Android phone, but doesn&#39;t work on my MacBook for some reason. My MacBoook is able to connect to my Sinkhole but can&#39;t ping anything for some reason so I can&#39;t access any internal or external webiste.</p> <p>Is this a known issue in the macOS?</p> <p>I can confirm that the MacBook is indeed connected to the sinkhole as a `dig` to a domain I DNS rewrote (agamserver.io) gives me my Sinkhole IP.</p> <pre><code>agamkohli@Agams-MacBook-Pro ~&gt; sudo /usr/sbin/networksetup -setdnsservers Wi-Fi 192.168.1.237 Password: agamkohli@Agams-MacBook-Pro ~&gt; dig agamserver.io ; &lt;&lt;&gt;&gt; DiG 9.10.6 &lt;&lt;&gt;&gt; agamserver.io ;; global options: +cmd ;; Got answer: ;; -&gt;&gt;HEADER&lt;&lt;- opcode: QUERY, status: NOERROR, id: 32602 ;; flags: qr rd ra; QUERY: 1, ANSWER: 1, AUTHORITY: 0, AD

## Home server security
 - [https://www.reddit.com/r/selfhosted/comments/1guhgb9/home_server_security](https://www.reddit.com/r/selfhosted/comments/1guhgb9/home_server_security)
 - RSS feed: $source
 - date published: 2024-11-18T22:24:50+00:00

<!-- SC_OFF --><div class="md"><p>So I am still in the everlasting process of building my home server and self-hosting stuff.</p> <p>My new concern now is, obviously, security.</p> <p>Since I am kind of new to networking and stuff, is there a way to &quot;check&quot; whether my home server is &quot;secure&quot;? By secure I mean if it&#39;s, well, (somehow) accessible outside my network (might sound dumb, but I tried using my phone and what not). </p> <p>I am also using Tailscale as a VPN so I can access the server outside my home when I am away and was wondering if I should switch to something else or selfhost a VPN (wireguard/wgeasy?).</p> <p>I have heard things about nginx reverse proxy, cloudflare stuff, just not sure if I have enough time and willpower to learn how to set them up.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/seekingadvice331"> /u/seekingadvice331 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1guh

## App for keeping licenses?
 - [https://www.reddit.com/r/selfhosted/comments/1guh5c9/app_for_keeping_licenses](https://www.reddit.com/r/selfhosted/comments/1guh5c9/app_for_keeping_licenses)
 - RSS feed: $source
 - date published: 2024-11-18T22:12:04+00:00

<!-- SC_OFF --><div class="md"><p>I have a couple of licenses for software, mostly plugins and themes which I use for myself or Clients. Every now and then I buy some more because there is a good Ltd and I think I will use the software in the future. </p> <p>All these licenses come from various places. </p> <p>Does anyone know for a good app to keep track of these licenses? Preferably with the option to add the plugin/theme file directly to it? I would like to enter some info with it like purchase date, where I bought it, how many users and so on. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DutchTee86"> /u/DutchTee86 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1guh5c9/app_for_keeping_licenses/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1guh5c9/app_for_keeping_licenses/">[comments]</a></span>

## Just started a YT channel on selfhost/homelabs
 - [https://www.reddit.com/r/selfhosted/comments/1guguxv/just_started_a_yt_channel_on_selfhosthomelabs](https://www.reddit.com/r/selfhosted/comments/1guguxv/just_started_a_yt_channel_on_selfhosthomelabs)
 - RSS feed: $source
 - date published: 2024-11-18T22:00:06+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m not quite sure I can share this, but I wasn&#39;t able to open self-promotion rules, it&#39;s simply not working, sorry if this violates the rules.</p> <p>I&#39;ve just started a YT channel on selfhost/homelabs and thought it might be interesting, otherwise I&#39;d love to hear the critique.</p> <p><a href="https://www.youtube.com/@thedevtoss">TossTheDev - YouTube</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gpskwlkr"> /u/gpskwlkr </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1guguxv/just_started_a_yt_channel_on_selfhosthomelabs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1guguxv/just_started_a_yt_channel_on_selfhosthomelabs/">[comments]</a></span>

## Qestion about Temperature
 - [https://www.reddit.com/r/selfhosted/comments/1gugqt1/qestion_about_temperature](https://www.reddit.com/r/selfhosted/comments/1gugqt1/qestion_about_temperature)
 - RSS feed: $source
 - date published: 2024-11-18T21:55:26+00:00

<!-- SC_OFF --><div class="md"><p>I run a Synology Nas and sometimes i want to check the temperature when its under heavy load. </p> <p>For some stats i have installed a docker image called beszel, which seems to work great BUT!! </p> <p>when i compare the temp from beszel, pihole and the system info in the settings itself, the readings are completely different. while in beszel the cpu in average seems to hover at around 45 to 50°, pihole shows the temp at about 60° and the system itself measures at around 57°</p> <p>so is there a tool, which is reliable and measures the temp as it really is?<br/> I think that maybe the synology internal sensor readings may be the &quot;most reliable ones&quot;?? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Odd_Astronomer_9279"> /u/Odd_Astronomer_9279 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gugqt1/qestion_about_temperature/">[link]</a></span> &#32; <span><a href="https://www.r

## WeddingShare - A basic selfhosted drop box and gallery
 - [https://www.reddit.com/r/selfhosted/comments/1gugnku/weddingshare_a_basic_selfhosted_drop_box_and](https://www.reddit.com/r/selfhosted/comments/1gugnku/weddingshare_a_basic_selfhosted_drop_box_and)
 - RSS feed: $source
 - date published: 2024-11-18T21:51:48+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m not sure how many of you will be interested in this but my wedding day is coming up soon and I&#39;ve not been able to find a clean solution that ticked all my boxes so being a dev I created my own. Now that it&#39;s in some sort of usable state I&#39;m releasing it for others to use. The long and short of it is, it&#39;s a site that allows both you and your guests to both view and share their own images. The idea is the wedding party upload pictures of their journey to the big day such as dress/suit shopping, food tastings, the morning prep, etc. Then when guest get seated at their dinner tables they can scan a QR code that allows them to view these pictures as well as share their own. </p> <p>Keep in mind this is version 1.0.2 so it&#39;s basic but functional. Later down the line if I get more time I plan to add an admin area with a review area in case someone accidentally uploads the wrong image of say a cucumber if you get what I mean but

## Simple, lightweight file upload page recommendations?
 - [https://www.reddit.com/r/selfhosted/comments/1gug11w/simple_lightweight_file_upload_page](https://www.reddit.com/r/selfhosted/comments/1gug11w/simple_lightweight_file_upload_page)
 - RSS feed: $source
 - date published: 2024-11-18T21:26:03+00:00

<!-- SC_OFF --><div class="md"><p>Could anyone recommend a service I can run that just hosts a very simple file upload page while using minimal resources? Ideally it should support large files and have a progress bar. </p> <p>I just need something where I can drop files into my browser and have them end up in the server directory. It doesn&#39;t need to support sharing, browsing, downloading, or editing the uploaded files.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/throwaway277252"> /u/throwaway277252 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gug11w/simple_lightweight_file_upload_page/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gug11w/simple_lightweight_file_upload_page/">[comments]</a></span>

## Identity "honeypots"
 - [https://www.reddit.com/r/selfhosted/comments/1gufmg3/identity_honeypots](https://www.reddit.com/r/selfhosted/comments/1gufmg3/identity_honeypots)
 - RSS feed: $source
 - date published: 2024-11-18T21:09:03+00:00

<!-- SC_OFF --><div class="md"><p>Had a fun idea. People can find you by searching stuff easily. What about creating like 20 websites in your name with random data, emails, phone numbers and pictures?</p> <p>All would list different AI generated data and seem legit, with different themes. Someone with basic technical skill would still be able to see through it, but people that might just know your name and have some bad intentions might not have an easy time. It would not protect you perfectly, but it would be a nice distraction.</p> <p>You could tell all your loved ones your website where you have the more &quot;private&quot; stuff and not have everyone find it as soon as they know you.</p> <p>I&#39;m interested to hear what everyone thinks of this, making it shouldn&#39;t be a huge burden, just buying a bunch of domains and letting an LLM create a bunch of websites.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hallo545403"> /u/hallo545403 <

## Completely lost deciding how to host
 - [https://www.reddit.com/r/selfhosted/comments/1gufcm6/completely_lost_deciding_how_to_host](https://www.reddit.com/r/selfhosted/comments/1gufcm6/completely_lost_deciding_how_to_host)
 - RSS feed: $source
 - date published: 2024-11-18T20:58:05+00:00

<!-- SC_OFF --><div class="md"><p>Hey folks. Basically, I&#39;m working in a project using Django+ react. So far I&#39;ve beenn working locally with the sqlite file, but I&#39;m ready to move to postgres.</p> <p>I have no clue how to get this done. In terms of cost, is creating the DB myself on a VPS reasonable? Or a managed postgres somewhere else? I have the same question for hosting the app but I&#39;ll get to that later.</p> <p>I do not require a huge DB. The project will ultimately be for a small family business. 2-3 users, but most of what they do queries the DB. </p> <p>Sorry if this question is inadequate for this sub, I am truly lost on hosting, there&#39;s a million options</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sunblaze1480"> /u/sunblaze1480 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gufcm6/completely_lost_deciding_how_to_host/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfh

## Self hosted media server with audio and video collection - which solution is the most optimal?
 - [https://www.reddit.com/r/selfhosted/comments/1gufcb3/self_hosted_media_server_with_audio_and_video](https://www.reddit.com/r/selfhosted/comments/1gufcb3/self_hosted_media_server_with_audio_and_video)
 - RSS feed: $source
 - date published: 2024-11-18T20:57:45+00:00

<!-- SC_OFF --><div class="md"><p>I want to configure a dedicated server for the videos I watch on YouTube and for which I already have dozens of playlists, but the videos periodically disappear, and the problem with ads and click interruptions/pauses is annoying. The server will be hosted in my own network and I can access it remotely when I need it.</p> <p>I have chosen a list of potential &quot;candidate&quot; solutions, but I am in a dilemma, what to choose, which will be the most useful and reliable for me in the long term!?</p> <ul> <li>YoutubeDL-Material</li> <li>tubearchivist</li> <li>tubesync</li> <li>Pinchflat</li> <li>ytdl-sub</li> <li>MeTube</li> </ul> <p>What I want:</p> <ul> <li>download playlists and individual videos </li> <li>have an integrated player </li> <li>a friendly, simple interface/GUI </li> <li>family can also use it, but not with configuration rights (to be able to add users) </li> <li>there should be a search engine for what is downloaded </li> <li>audio a

## What URL to use for mobile access to FreshRSS?
 - [https://www.reddit.com/r/selfhosted/comments/1guesvz/what_url_to_use_for_mobile_access_to_freshrss](https://www.reddit.com/r/selfhosted/comments/1guesvz/what_url_to_use_for_mobile_access_to_freshrss)
 - RSS feed: $source
 - date published: 2024-11-18T20:34:59+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve followed the guides from the FreshRSS github page, and maybe I&#39;m losing my mind, but I can&#39;t seem to find the proper url to use for access via a mobile app (e.g. Reeder). Is it just &lt;FreshRSS base url&gt;/api? </p> <p>From the logs, it looks like Reeder is looking for /api/rss and /api/feed both of which return 404. </p> <p>What did I miss?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BurnedHamSandwich"> /u/BurnedHamSandwich </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1guesvz/what_url_to_use_for_mobile_access_to_freshrss/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1guesvz/what_url_to_use_for_mobile_access_to_freshrss/">[comments]</a></span>

## Generic remote-access photo / video / folder viewer that DOESNT run on docker?
 - [https://www.reddit.com/r/selfhosted/comments/1gue6tl/generic_remoteaccess_photo_video_folder_viewer](https://www.reddit.com/r/selfhosted/comments/1gue6tl/generic_remoteaccess_photo_video_folder_viewer)
 - RSS feed: $source
 - date published: 2024-11-18T20:09:28+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a tool that will simply share a folder, allow me to have folders in said folder, and allow viewing of any photos or videos in any of those folders remotely from my phone..</p> <p>Preferably not a web-based client, but not against those either. </p> <p>I know that jellyfin has photo support but its speed and handling of photos is kinda... terrible. Its slow and buggy and you cant even download photos on mobile jellyfin clients </p> <p>As far as the server, I dont have one. My only option is to host via windows, and Id prefer to avoid using docker if possible, but Im not sure if something that fits my needs is out there.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SkylerSpark"> /u/SkylerSpark </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gue6tl/generic_remoteaccess_photo_video_folder_viewer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhoste

## Immich Webinterface wont open, do i need to backup /root/immich-app/library for a reinstall?
 - [https://www.reddit.com/r/selfhosted/comments/1gue3l0/immich_webinterface_wont_open_do_i_need_to_backup](https://www.reddit.com/r/selfhosted/comments/1gue3l0/immich_webinterface_wont_open_do_i_need_to_backup)
 - RSS feed: $source
 - date published: 2024-11-18T20:05:43+00:00

<!-- SC_OFF --><div class="md"><p>Immich Webinterface wont open, do i need to backup /root/immich-app/library for a reinstall? Tried to repull - seems like I broke my installation because docker images used all my space. after cleaning up, I cant access the webinterface, allthough all containers are &quot;running&quot;. seems like the postgres container is broken as it takes ages to start and then it still does not work.</p> <p>Whats the easiest way to reinstall? And can I go without backuping /root/immich-app/library or will this be deleted on a reinstallation?</p> <p>In case your wondering:</p> <pre><code>PostgreSQL Database directory appears to contain a database; Skipping initialization 2024-11-13 13:38:19.059 UTC [1] LOG: redirecting log output to logging collector process 2024-11-13 13:38:19.059 UTC [1] HINT: Future log output will appear in directory &quot;log&quot;. PostgreSQL Database directory appears to contain a database; Skipping initialization 2024-11-18 20:00:38.151 UT

## What features would you want in a Frontend CMS built for developers?
 - [https://www.reddit.com/r/selfhosted/comments/1gue159/what_features_would_you_want_in_a_frontend_cms](https://www.reddit.com/r/selfhosted/comments/1gue159/what_features_would_you_want_in_a_frontend_cms)
 - RSS feed: $source
 - date published: 2024-11-18T20:02:51+00:00

<!-- SC_OFF --><div class="md"><p>Hey folks! 👋</p> <p>So, I’ve been working on this open-source CMS project and got hit with this thought…</p> <p>Do WYSIWYG editors even make sense for devs? Like, yeah, they’re cool for non-tech teams to drag/drop stuff and update content. But as devs, would you rather just have control through code or APIs instead?</p> <p>Here’s what I’m curious about:</p> <ol> <li>Do WYSIWYG editors add any real value for developers? Or do they just get in the way?</li> <li>Would you prefer working with a CLI/low-code workflow over some editor UI?</li> <li>If you were building the <em>ultimate</em> CMS for devs, what would it look like?</li> </ol> <p>Trying to figure out how much focus should go into this vs making it more dev-centric. I’m building <a href="https://github.com/slingbiz/sling">Sling</a>, an open-source, dev-friendly CMS—think <a href="http://builder.io/">Builder.io</a> but with full control for developers. Would love to hear your thoughts!</p> <p><st

## Selfhosted development IDE "partnered" with LLM...
 - [https://www.reddit.com/r/selfhosted/comments/1gudqz2/selfhosted_development_ide_partnered_with_llm](https://www.reddit.com/r/selfhosted/comments/1gudqz2/selfhosted_development_ide_partnered_with_llm)
 - RSS feed: $source
 - date published: 2024-11-18T19:51:21+00:00

<!-- SC_OFF --><div class="md"><p>Hi All</p> <p>Last week I came across a new tool from Codium (a competitor to Github Copilot) called WindSurf - I&#39;ve been testing it to write some Python scripts, and its blown my mind.</p> <p>Its basically a fork of VSCode with an integrated LLM, that not only makes code suggestions.. if you give it permission, it will write and manage the whole code-base for you, even removing unused code, fixing errors, suggestion new features.. I&#39;m aware of 1 other product similar to this, called &quot;Cursor&quot;.</p> <p>The only downside I&#39;ve found is the speed, it can take 15-20 seconds before it starts to respond, and then it takes another 20+ seconds to complete the operation - Which is frustrating, especially when I have enough resources in my lab, to run something similar, and get better performance.</p> <p>So I was wondering, does anybody knew of something self-hostable along these lines? Or, do you have some kind of half-baked solution that 

## Linux server keeps deleting CUDA driver randomly
 - [https://www.reddit.com/r/selfhosted/comments/1gudn2q/linux_server_keeps_deleting_cuda_driver_randomly](https://www.reddit.com/r/selfhosted/comments/1gudn2q/linux_server_keeps_deleting_cuda_driver_randomly)
 - RSS feed: $source
 - date published: 2024-11-18T19:46:51+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m still a novice to this IT stuff, but this keeps happening during production and I can&#39;t figure it out. I operate a few AIs off some home servers, however every now and then, one of them decides that the CUDA driver must go and it disappears. Happened to each of the servers already over the past few months, no idea why. Is there a way I can prevent this from happening? What could even be causing it? Running on the latest free version of ubuntu server.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Great-Investigator30"> /u/Great-Investigator30 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gudn2q/linux_server_keeps_deleting_cuda_driver_randomly/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gudn2q/linux_server_keeps_deleting_cuda_driver_randomly/">[comments]</a></span>

## Combination of CloudFlare Tunnels and WireGuard for remote access?
 - [https://www.reddit.com/r/selfhosted/comments/1gud8g0/combination_of_cloudflare_tunnels_and_wireguard](https://www.reddit.com/r/selfhosted/comments/1gud8g0/combination_of_cloudflare_tunnels_and_wireguard)
 - RSS feed: $source
 - date published: 2024-11-18T19:30:02+00:00

<!-- SC_OFF --><div class="md"><p>Hi all. I&#39;ve been hosting Plex for a long time, but the set up is just sad and inconvenient. I&#39;ve had it running on my main Windows laptop, and it just sucks. I&#39;m upgrading to a linux server, and the change is coming with a bunch of other services I plan to host as well. I only have a basic understanding of networking, so I wanted to spell out my plan here and see if it makes sense, if there&#39;s any major security risks with it, or if there&#39;s anything I could do better/instead. Essentially:</p> <p>I will have 2 linux servers, each running headless Debian 12 Bookworm. Chosen for simplicity and wide support. For server 1, let&#39;s call it htpc. It&#39;s a bit beefier than my other old computer I&#39;m using, so it&#39;ll host all my entertainment. All services running on htpc will be remotely accessible via CloudFlare Tunnels. That&#39;s pretty much all there is to that server.</p> <p>On my other server, I&#39;ll call it labs, I&#39;

## How feasible is a self hosted LLM server for a school?
 - [https://www.reddit.com/r/selfhosted/comments/1gud3xj/how_feasible_is_a_self_hosted_llm_server_for_a](https://www.reddit.com/r/selfhosted/comments/1gud3xj/how_feasible_is_a_self_hosted_llm_server_for_a)
 - RSS feed: $source
 - date published: 2024-11-18T19:24:49+00:00

<!-- SC_OFF --><div class="md"><p>We&#39;ve been dabbling with the idea of bringing on some kind of AI tool like Gemini or ChatGPT for the administrator&#39;s in our district but a big concern is the privacy aspect of these tools. While we were talking about options, building our own local server for processing requests came up between me and a couple others in the tech team. We have kind of narrowed it down to a few key positive points and a couple negatives and I would just like to get some opinions on the feasibility of this project. </p> <p>Pros:</p> <ol> <li>Privacy. We control which models we use, we control who has access, we know where the data is going at all times.</li> <li>Potential Cost savings. Paid options we have looked at are in the $5-10k/year range for the base license for the staff we would like to license, we could spend a good chunk of that on building a server out and come out ahead. Depending on what kind of hardware we need we could save money in the long term

## Games on whales with wolf pin not working
 - [https://www.reddit.com/r/selfhosted/comments/1gucpmm/games_on_whales_with_wolf_pin_not_working](https://www.reddit.com/r/selfhosted/comments/1gucpmm/games_on_whales_with_wolf_pin_not_working)
 - RSS feed: $source
 - date published: 2024-11-18T19:08:52+00:00

<!-- SC_OFF --><div class="md"><p>hello everbody,</p> <p>I have installed games on whales wolf on a proxmox lxc container. I am currently entering the pin in moonlight. When entering the pin on the wolf website I get the error &quot;key not found&quot; does anyone know what the problem could be.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Raiderr22"> /u/Raiderr22 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gucpmm/games_on_whales_with_wolf_pin_not_working/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gucpmm/games_on_whales_with_wolf_pin_not_working/">[comments]</a></span>

## Should I self host discourse?
 - [https://www.reddit.com/r/selfhosted/comments/1guc3tt/should_i_self_host_discourse](https://www.reddit.com/r/selfhosted/comments/1guc3tt/should_i_self_host_discourse)
 - RSS feed: $source
 - date published: 2024-11-18T18:44:50+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m thinking about self-hosting Discourse for a small community with a few thousand requests per day. Installation seems manageable, but I have a few concerns about ongoing maintenance and performance:</p> <ul> <li>How easy is it to keep up with regular updates? Are applying updates well documented? How much downtime will be there for updates?</li> <li>Have you encountered latency issues or challenges with using a CDN for asset delivery?</li> <li>What size of VM would you recommend for handling a couple of thousand daily requests comfortably? Will a 2 core 2GB VM do?</li> </ul> <p>Would love to hear your insights and experiences. Thanks in advance! It will be a forum for <a href="https://pinggy.io">https://pinggy.io</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bishakhghosh_"> /u/bishakhghosh_ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1guc3tt/should_i_self_host_discourse/">

## Chromecasting on LAN
 - [https://www.reddit.com/r/selfhosted/comments/1guc3g0/chromecasting_on_lan](https://www.reddit.com/r/selfhosted/comments/1guc3g0/chromecasting_on_lan)
 - RSS feed: $source
 - date published: 2024-11-18T18:44:24+00:00

<!-- SC_OFF --><div class="md"><p>Has anyone here had success getting chrome casting to work on their local network?</p> <p>I’m fully able to access my network and media from outside via VPN. Works beautifully, but only on my devices. When I’m home, I’d like to chrome cast content, but because of Google’s hard coding of DNS, even my local DNS rewrites seem ineffective. </p> <p>I have a domain, it’s all set up for subdomains, everything is behind a reverse proxy. Using Jellyfin as my streaming source. Looking for those of you who have been able to make it work. </p> <p>Added note: I have considered getting a shield or other dedicated streaming device, but I already have the chrome casts and I like the idea of being able to throw up a movie using my phone. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/abuettner93"> /u/abuettner93 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1guc3g0/chromecasting_on_lan/">[link]</a></sp

## am i setting up my reverse proxy right?
 - [https://www.reddit.com/r/selfhosted/comments/1gubsb9/am_i_setting_up_my_reverse_proxy_right](https://www.reddit.com/r/selfhosted/comments/1gubsb9/am_i_setting_up_my_reverse_proxy_right)
 - RSS feed: $source
 - date published: 2024-11-18T18:32:00+00:00

<!-- SC_OFF --><div class="md"><p>I posted a couple weeks back about what was the best way to run a reverse proxy and got a ton of good feedback so decided to move forward on it.</p> <p>to do some testing i got a linode box running ubuntu, setup a wireguard config for the linode box to have to connect back to my house. i then installed docker on the linode box and installed nginx proxy manager. i have a domain for this which i set the a record to the linode ip and cname records to the services i was trying to hit. i also have proxy enabled in Cloudflare. from what ive found online this seems like the right way to do it since i no longer resolve my home ip just the proxy box ip.</p> <p>i know i need to lock down the vps. im going to add fail2ban as well as ip tables rules since docker is a pia with the networking and fw rules since i dont want any of it to be open to the public for the admin stuff</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/c

## Is there a wiki that uses something like tags?
 - [https://www.reddit.com/r/selfhosted/comments/1gub4zr/is_there_a_wiki_that_uses_something_like_tags](https://www.reddit.com/r/selfhosted/comments/1gub4zr/is_there_a_wiki_that_uses_something_like_tags)
 - RSS feed: $source
 - date published: 2024-11-18T18:05:49+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to set up a data/documentation organization structure for my offline network. I would preferably like for this to be able to use AD permissions, but if that&#39;s not possible then oh well.</p> <p>One of the big things I want to be done though, is have a way to tag different pages. For example, let&#39;s say I had System groups A, B, and C, and hardware types 1, 2, and 3. If a device was part of system A, but hardware type, I would like to go to the page for either system A or hardware type 3 and see that device. </p> <p>Of course, this could be done manually, but my hope is to make this easy to update so that my coworkers (2 of them) stick with it to keep everything documented.</p> <p>Is there a wiki out there that has a sort of tagging organization system like that that I can use?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AerialSnack"> /u/AerialSnack </a> <br/> <span><a href="https://www.r

## I'm curious if anyone has set up a self-hosted NAS system fully in the cloud that is cheaper per month than the big cloud storage options?
 - [https://www.reddit.com/r/selfhosted/comments/1gub4gp/im_curious_if_anyone_has_set_up_a_selfhosted_nas](https://www.reddit.com/r/selfhosted/comments/1gub4gp/im_curious_if_anyone_has_set_up_a_selfhosted_nas)
 - RSS feed: $source
 - date published: 2024-11-18T18:05:13+00:00

<!-- SC_OFF --><div class="md"><p>Obviously, in the long run, self-hosting on your own hardware can be a much better alternative to cloud storage. I&#39;m curious if anyone has a NAS OS set up on DO, Linode, AWS, Azure, etc, and made it more cost efficient?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/-ThatGingerKid-"> /u/-ThatGingerKid- </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gub4gp/im_curious_if_anyone_has_set_up_a_selfhosted_nas/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gub4gp/im_curious_if_anyone_has_set_up_a_selfhosted_nas/">[comments]</a></span>

## OVH IP Updater - my first selfhosted project
 - [https://www.reddit.com/r/selfhosted/comments/1gub3w3/ovh_ip_updater_my_first_selfhosted_project](https://www.reddit.com/r/selfhosted/comments/1gub3w3/ovh_ip_updater_my_first_selfhosted_project)
 - RSS feed: $source
 - date published: 2024-11-18T18:04:36+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone!</p> <p>I&#39;ve been selfhosting for 4 years now and it&#39;s time to contribute to the selfhosted &amp; opensource world. Recently, as you may know, GoDaddy changed its policies and disabled the use of API with no extra cost. So I migrate my domains to OVH. When I was looking methods and existing programs for updating, I realised that all were using DynHost (a duckdns-look-alike of OVH, that you will create and associate with your subdomains) instead of the official API, that easily allows you to update your ip.</p> <p>So I created ovh-ip-updater, a Docker container that allows you to update the IP of your subdomains (and also create the subdomain if it does not exist!) using the API instead of your dynhost user. </p> <p><a href="https://github.com/myanesp/ovh-ip-updater">GitHub repo</a></p> <p>Please, open an issue (or leave it here) if you want a feature that is missing and star the repo if it is useful!<br/> Thanks, glad to make a li

## Error when adding block list to Adguard Home
 - [https://www.reddit.com/r/selfhosted/comments/1gub0m9/error_when_adding_block_list_to_adguard_home](https://www.reddit.com/r/selfhosted/comments/1gub0m9/error_when_adding_block_list_to_adguard_home)
 - RSS feed: $source
 - date published: 2024-11-18T18:01:02+00:00

<!-- SC_OFF --><div class="md"><p>I am getting the following error when trying to add the blocklist referenced below even thought the file is in plain text. Any ideas?</p> <p>Error: control/filtering/add_url | Couldn&#39;t fetch filter from URL &quot;<a href="https://github.com/xRuffKez/NRD/blob/main/lists/14-day/adblock/nrd-14day_adblock.txt">https://github.com/xRuffKez/NRD/blob/main/lists/14-day/adblock/nrd-14day_adblock.txt</a>&quot;: data is HTML, not plain text | 400</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rubeo_O"> /u/rubeo_O </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gub0m9/error_when_adding_block_list_to_adguard_home/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gub0m9/error_when_adding_block_list_to_adguard_home/">[comments]</a></span>

## To people who both selfhost and use a VPN, what's your setup?
 - [https://www.reddit.com/r/selfhosted/comments/1guahrb/to_people_who_both_selfhost_and_use_a_vpn_whats](https://www.reddit.com/r/selfhosted/comments/1guahrb/to_people_who_both_selfhost_and_use_a_vpn_whats)
 - RSS feed: $source
 - date published: 2024-11-18T17:39:41+00:00

<!-- SC_OFF --><div class="md"><p>I currently use Tailscale to access all my services when outside my home and pretty much just leave it active 24/7 on my phone and laptop.</p> <p>But with privacy busting corpo&#39;s leading the FCC for an another term I&#39;m looking into finally trying VPNs. The only problem is I&#39;ve discovered running a VPN with Tailscale is highly problematic since Tailscale is also a VPN technically.</p> <p>So you selfhosters running VPNs, what is your setup?</p> <p><em>edit</em></p> <p>Wow you guys provided some great options, thanks for all the responses. Got a lot to research now.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rectal_rocket"> /u/rectal_rocket </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1guahrb/to_people_who_both_selfhost_and_use_a_vpn_whats/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1guahrb/to_people_who_both_selfhost_and_use_a_vpn

## Let's Encrypt Certificate alongside Cloudflare Tunnel
 - [https://www.reddit.com/r/selfhosted/comments/1guag3q/lets_encrypt_certificate_alongside_cloudflare](https://www.reddit.com/r/selfhosted/comments/1guag3q/lets_encrypt_certificate_alongside_cloudflare)
 - RSS feed: $source
 - date published: 2024-11-18T17:37:41+00:00

<!-- SC_OFF --><div class="md"><p>Hi there</p> <p>I have the following setup:</p> <p><strong>Cloudflare Tunnel (cloudflared)</strong> → <strong>Traefik</strong> → <strong>Service</strong></p> <p>This configuration works well when traffic is coming through the Cloudflare Tunnel.</p> <p><strong>Local LAN Access:</strong></p> <p>To bypass the 100 MB upload limit of the Cloudflare free plan in my LAN, i created a local DNS entry:</p> <p><strong>Local DNS Entry</strong> → <strong>Traefik</strong> → <strong>Service</strong></p> <p>This way, I can directly access the services within the LAN without using the Cloudflare Tunnel.</p> <h1>Problem:</h1> <p>In order to use HTTPS within the LAN, I need a valid Let&#39;s Encrypt certificate via ACME. However, when trying to obtain the ACME certificate, I receive the following error:</p> <pre><code>logCode kopieren2024-11-18T17:09:48+01:00 ERR github.com/traefik/traefik/v3/pkg/provider/acme/provider.go:457 &gt; Unable to obtain ACME certificate for 

## SSO + AD?
 - [https://www.reddit.com/r/selfhosted/comments/1guabjg/sso_ad](https://www.reddit.com/r/selfhosted/comments/1guabjg/sso_ad)
 - RSS feed: $source
 - date published: 2024-11-18T17:32:34+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;d like to consolidate my Windows accounts across a couple of devices to a Domain Controller and allow the ability for other family members to use my Windows PC with their own accounts.</p> <p>I&#39;ve also started self-hosting some apps with a view to adding more (as soon as I&#39;ve got an SSO solution in place) and would like to be able to use SSO for as many of those as possible.</p> <p>I found this series of articles which shows how to set up a Samba DC and use it as a backend for Authelia: <a href="https://helgeklein.com/blog/samba-active-directory-in-a-docker-container-installation-guide/">https://helgeklein.com/blog/samba-active-directory-in-a-docker-container-installation-guide/</a></p> <p>I was wondering if there are any alternatives to this method. From my research so far there don&#39;t seem to be any *nix implementations of Windows AD outside of Samba?</p> <p>There seem to be plenty of SSO solutions but they don&#39;t seem to advert

## Could you recommend me an OS?
 - [https://www.reddit.com/r/selfhosted/comments/1gu9v7b/could_you_recommend_me_an_os](https://www.reddit.com/r/selfhosted/comments/1gu9v7b/could_you_recommend_me_an_os)
 - RSS feed: $source
 - date published: 2024-11-18T17:14:50+00:00

<!-- SC_OFF --><div class="md"><p>Hello!</p> <p>Self hosting enthusiast here with little time to fiddle with Linux, nor do I have the skills for it. </p> <p>I&#39;m looking for something that&#39;s as easy to use like umbrel but with relevant functionality. I&#39;m looking mostly for file backups and photo sync. So nextcloud/photoprism with extra points if I could connect jellyfin. My main issue with umbrel is that it&#39;s http and not accessible from an outside network. I can&#39;t connect my devices via wireguard either. This is a must for me because I&#39;m rarely at the physical location of my network. </p> <p>Based on these criteria, what would be your preferred OS choice?</p> <p>Many thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Visible-Feeling-8018"> /u/Visible-Feeling-8018 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu9v7b/could_you_recommend_me_an_os/">[link]</a></span> &#32; <span><a href="https:/

## unstable ubuntu server in k3s cluster
 - [https://www.reddit.com/r/selfhosted/comments/1gu9u85/unstable_ubuntu_server_in_k3s_cluster](https://www.reddit.com/r/selfhosted/comments/1gu9u85/unstable_ubuntu_server_in_k3s_cluster)
 - RSS feed: $source
 - date published: 2024-11-18T17:13:44+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,<br/> I have a k3s cluster with 3 node named ubuntu2 ubuntu3 and ubuntu4. </p> <p>I&#39;m writing here because unbutu2 seems pretty unstable. The command last reboot give me different reboot on today and in the past days:</p> <pre><code>reboot system boot 6.8.0-48-generic Mon Nov 18 15:38 still running reboot system boot 6.8.0-48-generic Mon Nov 18 15:30 still running reboot system boot 6.8.0-48-generic Mon Nov 18 14:37 still running reboot system boot 6.8.0-48-generic Mon Nov 18 05:32 still running reboot system boot 6.8.0-48-generic Mon Nov 18 03:14 still running reboot system boot 6.8.0-48-generic Sun Nov 17 22:45 still running reboot system boot 6.8.0-48-generic Sun Nov 17 18:23 still running reboot system boot 6.8.0-48-generic Sun Nov 17 12:18 still running reboot system boot 6.8.0-48-generic Sun Nov 17 10:07 still running reboot system boot 6.8.0-48-generic Sun Nov 17 07:34 still running reboot system boot 6.8.0-48-generic Sun Nov 1

## rgit - A blazingly fast web frontend for git repositories
 - [https://www.reddit.com/r/selfhosted/comments/1gu9qqs/rgit_a_blazingly_fast_web_frontend_for_git](https://www.reddit.com/r/selfhosted/comments/1gu9qqs/rgit_a_blazingly_fast_web_frontend_for_git)
 - RSS feed: $source
 - date published: 2024-11-18T17:09:49+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gu9qqs/rgit_a_blazingly_fast_web_frontend_for_git/"> <img src="https://external-preview.redd.it/cN7fo20GwH4ldpGbY15okcacugf4m5LgAIKef_o5dy4.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=88263aee18f7f3c078efdaed08ed1b344c88584a" alt="rgit - A blazingly fast web frontend for git repositories" title="rgit - A blazingly fast web frontend for git repositories" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jorda_n"> /u/jorda_n </a> <br/> <span><a href="https://github.com/w4/rgit">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu9qqs/rgit_a_blazingly_fast_web_frontend_for_git/">[comments]</a></span> </td></tr></table>

## HomeLab migration / update with old PC
 - [https://www.reddit.com/r/selfhosted/comments/1gu99vx/homelab_migration_update_with_old_pc](https://www.reddit.com/r/selfhosted/comments/1gu99vx/homelab_migration_update_with_old_pc)
 - RSS feed: $source
 - date published: 2024-11-18T16:51:00+00:00

<!-- SC_OFF --><div class="md"><p>My brother has some old desktop parts that I&#39;d like to repurpose. I currently have a raspberry pi running docker to manage samba, a foundryvtt instance, reverse proxy and ssl via LSIO&#39;s swag container, a nextcloud instance, and dns using duckdns. </p> <p>I don&#39;t have all of the specs of the PC except that it has 16gb of ram, needs a power supply and some drives. I am considering migrating my containers on the pi over to this desktop, but I would also like to replace my samba container with something more fully fleshed out to be a NAS to store mostly family photos, and I would like a *simple* solution to automatically upload photos from mobile devices to help my wife with the transition.</p> <p>I would like the desktop to have some availability to play around with. I&#39;m on the fence about messing around with Jellyfin as well.</p> <p>I&#39;d really like to get some opinions about what the *right* way to set this up would be. I&#39;m torn

## Display SNMP data in Homer dashboard?
 - [https://www.reddit.com/r/selfhosted/comments/1gu826s/display_snmp_data_in_homer_dashboard](https://www.reddit.com/r/selfhosted/comments/1gu826s/display_snmp_data_in_homer_dashboard)
 - RSS feed: $source
 - date published: 2024-11-18T16:01:22+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I&#39;m trying to put together a dashboard that is useful and not just a bookmarks page, and I can&#39;t figure if Homer dasboard has some way to retrieve SNMP data, so that I could instal &quot;RPI-Monitor&quot; in a few Pis and monitor them fron a central view.</p> <p>I&#39;m mostly concerned with Temperatures, CPU load, and being light. Aesthetics are not so relevant.</p> <p>If not Homer I&#39;m looking at Homarr or dashdot (and actually dashdot seems to be required to do the real job anyway if I wanted to use Homarr??)</p> <p>Any advice you could share? Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AngryByDefault"> /u/AngryByDefault </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu826s/display_snmp_data_in_homer_dashboard/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu826s/display_snmp_data_in_homer_dashboard/">[comments]

## Backing up NAS - suggestions?
 - [https://www.reddit.com/r/selfhosted/comments/1gu8212/backing_up_nas_suggestions](https://www.reddit.com/r/selfhosted/comments/1gu8212/backing_up_nas_suggestions)
 - RSS feed: $source
 - date published: 2024-11-18T16:01:12+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;m looking for suggestions based on what others are doing in similar situations.</p> <p>I have a fairly large home lab/self-hosted environment, which includes a variety of services. The majority of my services are hosted on an HP ProLiant server running Proxmox, with a sizable ZFS pool totaling around 100TB.</p> <p>I also have a secondary ProLiant server with similar storage capacity that I want to use specifically for backing up my Plex library, which is about 40TB.</p> <p>Ideally, I&#39;d like to keep the backup server offline as much as possible for power conservation, only turning it on once a week to perform a backup of any new movies or episodes. It would need to be capable of either running the backup based on a schedule, agent, or trigger such as “on boot”.</p> <p>My question is: What backup solution would you recommend? I was initially planning to use Proxmox Backup Server and set up an rsync cron job to back up the movies and TV sh

## How to self host omnivore. its shutting down. i dunno coding but this app is very useful for me and
 - [https://www.reddit.com/r/selfhosted/comments/1gu6xqn/how_to_self_host_omnivore_its_shutting_down_i](https://www.reddit.com/r/selfhosted/comments/1gu6xqn/how_to_self_host_omnivore_its_shutting_down_i)
 - RSS feed: $source
 - date published: 2024-11-18T15:13:02+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Difficult-Ad3490"> /u/Difficult-Ad3490 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu6xqn/how_to_self_host_omnivore_its_shutting_down_i/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu6xqn/how_to_self_host_omnivore_its_shutting_down_i/">[comments]</a></span>

## Network Structure Question - Server Managment
 - [https://www.reddit.com/r/selfhosted/comments/1gu6n0w/network_structure_question_server_managment](https://www.reddit.com/r/selfhosted/comments/1gu6n0w/network_structure_question_server_managment)
 - RSS feed: $source
 - date published: 2024-11-18T15:00:05+00:00

<!-- SC_OFF --><div class="md"><p>What is everyone&#39;s opinion on management VLANs? Is it worth it in the Homelab? </p> <p>I&#39;d like to set up say VLAN 20 as &quot;management&quot; so I can SSH all the hardware and patch in updates and deploy services etc. Then the services would be accessed via VLAN 30 or other. So, with bare metal PiHole on a raspberry Pi. I would access the hardware on VLAN 20 but the admin panel would be accessible on VLAN 30 and the IP address for the server would be on VLAN 30.</p> <p>I understand this may be overkill in a homelab, but I am using this journey as a learning platform for industry &quot;best practices&quot;.</p> <p>Thanks for any feedback!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hatmcgat1370"> /u/hatmcgat1370 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu6n0w/network_structure_question_server_managment/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/s

## Migrating from Unraid
 - [https://www.reddit.com/r/selfhosted/comments/1gu60iw/migrating_from_unraid](https://www.reddit.com/r/selfhosted/comments/1gu60iw/migrating_from_unraid)
 - RSS feed: $source
 - date published: 2024-11-18T14:31:17+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I&#39;ve been running an Unraid server for home use for the past 2 years, and I&#39;m looking to move on to something else that allows me more flexibility since I feel very limited by the way docker operates on Unraid. Specifically, the use of &quot;apps&quot; and the limited docker compose running on Unraid.</p> <p>Was thinking of switching to a Proxmox machine running an ubuntu VM. If possible, I would like to keep all my data and export somehow my containers so that I can recreate them with little the adjustments required.</p> <p>Does anybody have an idea from where I could start?</p> <p>Thanks :D</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gottoesplosivo"> /u/gottoesplosivo </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu60iw/migrating_from_unraid/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu60iw/migrating_from_unraid/">[

## *Sonic music server woes
 - [https://www.reddit.com/r/selfhosted/comments/1gu5hie/sonic_music_server_woes](https://www.reddit.com/r/selfhosted/comments/1gu5hie/sonic_music_server_woes)
 - RSS feed: $source
 - date published: 2024-11-18T14:06:52+00:00

<!-- SC_OFF --><div class="md"><h4>The Problem</h4> <p>I have been trying to run my own airsonic server for a while, but I keep running into the same issues no matter what I am running - I always end up having an issue adding more music to my library at some point, and the only fix seems to be to start over from scratch, or close to it - I have to remove my music library , clean up the db &amp; then rescan. Right now I only have 9704 tracks in my library. </p> <h4>Servers I have Tried</h4> <p>So far I have tried the following *sonic servers * Airsonic * Airsonic Advanced * Gonic</p> <h4>My Setup</h4> <ul> <li>OS - Debian 11 (OpenMediaVault) </li> <li>*sonic server running in docker </li> <li>my music library lives on unionfs, which is mounted at /media/Storage/Storage/Music</li> <li><p>In my Docker compose file I have the following volume mapping </p> <p>volumes:</p> <ul> <li>/media/Storage/Storage/Docker/airsonic:/config</li> <li>/media/Storage/Storage/Music:/music</li> </ul></li> <

## Mayan EDMS - Anyone know how to setup mirroring_mount_cabinet?
 - [https://www.reddit.com/r/selfhosted/comments/1gu546h/mayan_edms_anyone_know_how_to_setup_mirroring](https://www.reddit.com/r/selfhosted/comments/1gu546h/mayan_edms_anyone_know_how_to_setup_mirroring)
 - RSS feed: $source
 - date published: 2024-11-18T13:49:34+00:00

<!-- SC_OFF --><div class="md"><p>I wanted to test the mirroring mount for a cabinet. I can see the feature was added but I don&#39;t know how to use it. The only instructions I can find are from a google AI overview which says to navigate to the &quot;system&quot; and &quot;storage&quot; settings but I don&#39;t see anything listed in the tools or settings that match the instructions. I have clicked just about every button available and I can&#39;t figure this out. Any help or breadcrumbs would be appreciated. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/guitarman181"> /u/guitarman181 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu546h/mayan_edms_anyone_know_how_to_setup_mirroring/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu546h/mayan_edms_anyone_know_how_to_setup_mirroring/">[comments]</a></span>

## Advice needed on design proposal....
 - [https://www.reddit.com/r/selfhosted/comments/1gu4k6u/advice_needed_on_design_proposal](https://www.reddit.com/r/selfhosted/comments/1gu4k6u/advice_needed_on_design_proposal)
 - RSS feed: $source
 - date published: 2024-11-18T13:22:06+00:00

<!-- SC_OFF --><div class="md"><p>Hi all - just starting out on my self hosting journey and curious on how you would set things up.</p> <p>I currently have separated VLANs. I plan to stick a reverse proxy in an isolated VLAN (probably nginx proxy manager). I will have firewall rules that allow the NPM to communicate with servers in a different VLAN, exposing only the specific ports needed.</p> <p>First question &gt; is this basic premise relatively secure? The server running the proxy will have no access to anything else, other than via the ports allowed.</p> <p>Second question &gt; I&#39;m thinking about adding Authentik, fail2ban or CrowdSec into the mix, but I am unsure where I should be running these. If the proxy is proxying traffic to another host running docker, should I stick Authentik on the host that actually runs all my internal services or is it better being on the proxy itself? Same question for fail2ban. </p> <p>I think CrowdSec should be on the proxy. I then would just

## Docker Registry + Authelia + Nginx.... has anyone figured it out?
 - [https://www.reddit.com/r/selfhosted/comments/1gu3k31/docker_registry_authelia_nginx_has_anyone_figured](https://www.reddit.com/r/selfhosted/comments/1gu3k31/docker_registry_authelia_nginx_has_anyone_figured)
 - RSS feed: $source
 - date published: 2024-11-18T12:27:16+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone :)</p> <p>I wanna set up my own Docker registry on my server. I&#39;m using nginx for my reverse proxy and Authelia for authentication/authorization.</p> <p>No matter how hard I try, I can&#39;t seem to be able to use an Authelia user to authenticate with my Docker Registry. The `docker login registry.mydomain.com` seems to work just fine. However, whenever I try to push some Docker images, I get the error `during GET unexpected status code was returned: 200`.</p> <p>After trying a hundred different things and variations of nginx and registry configurations, I pretty much gave up.</p> <p>Does anyone have experience with this, or perhaps even a working configuration? Or perhaps a suggestion for an easier-to-set-up container registry... I don&#39;t want to resort to basic authentication specifically for the registry (which the docker registry supports just fine), but perhaps that&#39;s the best option?</p> </div><!-- SC_ON --> &#32; submitt

## "All in one solution"
 - [https://www.reddit.com/r/selfhosted/comments/1gu3hn0/all_in_one_solution](https://www.reddit.com/r/selfhosted/comments/1gu3hn0/all_in_one_solution)
 - RSS feed: $source
 - date published: 2024-11-18T12:23:21+00:00

<!-- SC_OFF --><div class="md"><p>I need your advice. Currently, I have several standalone solutions running in my apartment. Pi-hole and PiVPN are running on a Raspberry Pi 3, Home Assistant is on a Pi 4, and my cloud/NAS server is running on an old DiskStation 216+. I’d like to centralize everything more. Does it make sense, for example, to buy a Lenovo ThinkCentre and run everything on it? Maybe even replace the DS216+ with TrueNAS Scale. Does this plan make sense?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ironman139"> /u/ironman139 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu3hn0/all_in_one_solution/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu3hn0/all_in_one_solution/">[comments]</a></span>

## PSA: Update your Vaultwarden instance (again)
 - [https://www.reddit.com/r/selfhosted/comments/1gu3aep/psa_update_your_vaultwarden_instance_again](https://www.reddit.com/r/selfhosted/comments/1gu3aep/psa_update_your_vaultwarden_instance_again)
 - RSS feed: $source
 - date published: 2024-11-18T12:11:05+00:00

<!-- SC_OFF --><div class="md"><p>There were some more security issues fixed in 1.32.5</p> <blockquote> <p>This release further fixed some CVE Reports reported by a third party security auditor and we recommend everybody to update to the latest version as soon as possible. The contents of these reports will be disclosed publicly in the future.</p> </blockquote> <p><a href="https://github.com/dani-garcia/vaultwarden/releases/tag/1.32.5">https://github.com/dani-garcia/vaultwarden/releases/tag/1.32.5</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PeeK1e"> /u/PeeK1e </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu3aep/psa_update_your_vaultwarden_instance_again/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu3aep/psa_update_your_vaultwarden_instance_again/">[comments]</a></span>

## Self hosted IDE without Websockets?
 - [https://www.reddit.com/r/selfhosted/comments/1gu3a8s/self_hosted_ide_without_websockets](https://www.reddit.com/r/selfhosted/comments/1gu3a8s/self_hosted_ide_without_websockets)
 - RSS feed: $source
 - date published: 2024-11-18T12:10:48+00:00

<!-- SC_OFF --><div class="md"><p>Does anyone know of any self hosted IDEs that don&#39;t rely on websockets? I&#39;d like to develop remotely on a network which doesn&#39;t allow any websocket traffic. It&#39;s a shame because Code-Server works great on networks where websockets are ok.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/timgh101"> /u/timgh101 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu3a8s/self_hosted_ide_without_websockets/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu3a8s/self_hosted_ide_without_websockets/">[comments]</a></span>

## SearXNG or Whoogle for search engines?
 - [https://www.reddit.com/r/selfhosted/comments/1gu2dzm/searxng_or_whoogle_for_search_engines](https://www.reddit.com/r/selfhosted/comments/1gu2dzm/searxng_or_whoogle_for_search_engines)
 - RSS feed: $source
 - date published: 2024-11-18T11:11:44+00:00

<!-- SC_OFF --><div class="md"><p>Title</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/anonymoize"> /u/anonymoize </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu2dzm/searxng_or_whoogle_for_search_engines/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu2dzm/searxng_or_whoogle_for_search_engines/">[comments]</a></span>

## Accounting Software for one-man business
 - [https://www.reddit.com/r/selfhosted/comments/1gu1zt8/accounting_software_for_oneman_business](https://www.reddit.com/r/selfhosted/comments/1gu1zt8/accounting_software_for_oneman_business)
 - RSS feed: $source
 - date published: 2024-11-18T10:44:18+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve had a look online and all I can find is BigCapital - which doesn&#39;t offer much in terms of documentation.</p> <p>I&#39;m based in the UK and have constantly looked at Xero, Quickbooks and FreeAgent - however the monthly cost puts me off. My business is on-the-side and has relatively few overheads.</p> <p>I use Actual for my personal finances, but want to ideally keep business accounting software seperate.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tcoysh"> /u/tcoysh </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu1zt8/accounting_software_for_oneman_business/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu1zt8/accounting_software_for_oneman_business/">[comments]</a></span>

## Moving from VPS to Internal Home - Cloudflare Tunnels / NGINXPM?
 - [https://www.reddit.com/r/selfhosted/comments/1gu1zdl/moving_from_vps_to_internal_home_cloudflare](https://www.reddit.com/r/selfhosted/comments/1gu1zdl/moving_from_vps_to_internal_home_cloudflare)
 - RSS feed: $source
 - date published: 2024-11-18T10:43:22+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I need a little advice</p> <p>At the moment I have a VPS with docker on, works with nxingpm &amp; desec.io.</p> <p>I&#39;ve been building a small home server, and have it ready to connect (a couple of containers to begin with - freshrss/jellyfin/esprocrm/baikal).</p> <p>In terms of DNS/proxy, should I be looking at a plain nginxpm &amp; <a href="http://desec.io">desec.io</a> as I&#39;m currently using, or should I be looking at cloudflare tunnels + domain?</p> <p>Many thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PiratesOfTheArctic"> /u/PiratesOfTheArctic </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu1zdl/moving_from_vps_to_internal_home_cloudflare/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu1zdl/moving_from_vps_to_internal_home_cloudflare/">[comments]</a></span>

## docker on android?
 - [https://www.reddit.com/r/selfhosted/comments/1gu1yzi/docker_on_android](https://www.reddit.com/r/selfhosted/comments/1gu1yzi/docker_on_android)
 - RSS feed: $source
 - date published: 2024-11-18T10:42:30+00:00

<!-- SC_OFF --><div class="md"><p>Is it possible to run docker on android phone and maybe some kind of lazy load for battery saving?</p> <p>Or alternatively somehow run some application type web page solutions (normally would be docker containers) on phone? </p> <p>I am living with parents, i have Raspberry with docker, with ngnix I have made some things to reach it from outside network. But sometimes it decides to die networkingly and I cant reach it. So i think, maybe for some applications, like movie and tv series trackers, car millage and other stuff trackers, I could use phone?</p> <p>Yes, alternatively, I could just fix my server. But you know, why fix in 1h if I can overengineer things in 1 month.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lapiuslt"> /u/lapiuslt </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu1yzi/docker_on_android/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/

## 2 proxmox hosts, access 1st host data from 2nd host LXC container
 - [https://www.reddit.com/r/selfhosted/comments/1gu1kho/2_proxmox_hosts_access_1st_host_data_from_2nd](https://www.reddit.com/r/selfhosted/comments/1gu1kho/2_proxmox_hosts_access_1st_host_data_from_2nd)
 - RSS feed: $source
 - date published: 2024-11-18T10:12:54+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I currently have a Proxmox host, with a lot of storage, with my media library.</p> <p>I will receive a seconde machine, N100 mini PC, which will receive Proxmox as well, and I&#39;ll install Plex with LXC.</p> <p>I want Plex LXC container to be able to access /medialibrary of the second host. What&#39;s the best option ? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/carmelo42"> /u/carmelo42 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu1kho/2_proxmox_hosts_access_1st_host_data_from_2nd/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu1kho/2_proxmox_hosts_access_1st_host_data_from_2nd/">[comments]</a></span>

## My server went down along with the home of some innocent spiders when my mom took upon a spiderweb-hunting endeavor
 - [https://www.reddit.com/r/selfhosted/comments/1gu19ah/my_server_went_down_along_with_the_home_of_some](https://www.reddit.com/r/selfhosted/comments/1gu19ah/my_server_went_down_along_with_the_home_of_some)
 - RSS feed: $source
 - date published: 2024-11-18T09:49:27+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gu19ah/my_server_went_down_along_with_the_home_of_some/"> <img src="https://b.thumbs.redditmedia.com/4V1m9reH-8CqrYHIPXvwS97p9Dk8arDjPYMchOrxOEw.jpg" alt="My server went down along with the home of some innocent spiders when my mom took upon a spiderweb-hunting endeavor" title="My server went down along with the home of some innocent spiders when my mom took upon a spiderweb-hunting endeavor" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Problems with self-hosting:</p> <p>My self-hosted Raspberry Pi server saw a 9-hour+ downtime because my mom tried to clean up Spiderweb with a stick over very thin fiber optic cables and a lot of wires.</p> <p>I noticed the downtime from my university when it happened and called my mom to learn that the internet was not working. When I came back, I confronted my mom and learned about her spiderweb-hunting endeavor. I saw that a portion of my fiber optic cable was a little d

## Looking for a unified task inbox/dashboard
 - [https://www.reddit.com/r/selfhosted/comments/1gu0czd/looking_for_a_unified_task_inboxdashboard](https://www.reddit.com/r/selfhosted/comments/1gu0czd/looking_for_a_unified_task_inboxdashboard)
 - RSS feed: $source
 - date published: 2024-11-18T08:38:02+00:00

<!-- SC_OFF --><div class="md"><p>Does anyone know of a platform that can pull tasks from multiple different systems to display them in one unified dashboard? </p> <p>I work as a freelance developer and consultant. That means I am tied into at least four different companies task management systems. Two Asanas, a Jira board and a Gitlab board.<br/> Rather than have to go hunting through each system I was hoping something existed where I could display all of this in one single location. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BriefDirt"> /u/BriefDirt </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu0czd/looking_for_a_unified_task_inboxdashboard/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu0czd/looking_for_a_unified_task_inboxdashboard/">[comments]</a></span>

## Basic application hosting infra boilerplate?
 - [https://www.reddit.com/r/selfhosted/comments/1gu08kx/basic_application_hosting_infra_boilerplate](https://www.reddit.com/r/selfhosted/comments/1gu08kx/basic_application_hosting_infra_boilerplate)
 - RSS feed: $source
 - date published: 2024-11-18T08:28:10+00:00

<!-- SC_OFF --><div class="md"><p>Is there a self-hosted guide or boilerplate or like docker-compose that allows one to setup thier own server for hosting a SaaS with essentials like Observability, Monitoring, Security, etc.?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nummer31"> /u/nummer31 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu08kx/basic_application_hosting_infra_boilerplate/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gu08kx/basic_application_hosting_infra_boilerplate/">[comments]</a></span>

## Contabo Rant
 - [https://www.reddit.com/r/selfhosted/comments/1gu05bz/contabo_rant](https://www.reddit.com/r/selfhosted/comments/1gu05bz/contabo_rant)
 - RSS feed: $source
 - date published: 2024-11-18T08:21:04+00:00

<!-- SC_OFF --><div class="md"><p>I’ve been a loyal customer of Contabo for years, quick to defend them when others had issues. But after this latest experience, I’m done.</p> <p>Here’s what happened:</p> <p>Due to constant network disruptions caused by <strong>Contabo’s messy configuration</strong>, I was forced to temporarily switch from Linux to Windows on my VPS to troubleshoot and try to stabilize the connection. Let me be clear—this was a <strong>temporary solution</strong> until their network issues were sorted. I was actively working on reverting back to Linux once the problems were resolved.</p> <p>But instead of acknowledging the extenuating circumstances, Contabo <strong>suspended my instance</strong> for allegedly violating their terms by running Windows. They even <strong>disabled the Ethernet interface</strong>, making it impossible to recover my data through normal methods. What kind of customer service is this?</p> <p>I’m now locked out of five years’ worth of critica

## Immich on Raspberry Pi 3?
 - [https://www.reddit.com/r/selfhosted/comments/1gtynwq/immich_on_raspberry_pi_3](https://www.reddit.com/r/selfhosted/comments/1gtynwq/immich_on_raspberry_pi_3)
 - RSS feed: $source
 - date published: 2024-11-18T06:31:55+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I have a Raspberry Pi 3 laying around. I have recently configured as backup server with Syncthing and I am thinking about using it for photo backups (around 100GB of photos and videos) with Immich. </p> <p>Has anyone else tried running Immich on RPi 3? I am planning to run the face recognition AI container on my PC instead of RPi and that should reduce the performance overhead. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ferhansolo"> /u/ferhansolo </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtynwq/immich_on_raspberry_pi_3/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtynwq/immich_on_raspberry_pi_3/">[comments]</a></span>

## Proxmox fixing firewall bug for over a month?
 - [https://www.reddit.com/r/selfhosted/comments/1gtx94o/proxmox_fixing_firewall_bug_for_over_a_month](https://www.reddit.com/r/selfhosted/comments/1gtx94o/proxmox_fixing_firewall_bug_for_over_a_month)
 - RSS feed: $source
 - date published: 2024-11-18T05:03:23+00:00

<!-- SC_OFF --><div class="md"><p>Proxmox have a <a href="https://www.reddit.com/r/Proxmox/comments/1g9gn0z/do_not_rely_solely_on_proxmox_firewall_for_the/">strange firewall</a>, one that needs network to learn its rules first - so it starts network without a firewall, to then attempt to apply the rules, including its host zone rules.</p> <p>They have known about this since <a href="https://bugzilla.proxmox.com/show_bug.cgi?id=5759">early October</a>, but there&#39;s no sign of even candidate patches on the developer mailing list.</p> <p>Luckily, lots of people would have another firewall in front of Proxmox one, but is this something you would expect?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/esiy0676"> /u/esiy0676 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtx94o/proxmox_fixing_firewall_bug_for_over_a_month/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtx94o/proxmox_f

## Error on using RedLib for Reddit
 - [https://www.reddit.com/r/selfhosted/comments/1gtvug0/error_on_using_redlib_for_reddit](https://www.reddit.com/r/selfhosted/comments/1gtvug0/error_on_using_redlib_for_reddit)
 - RSS feed: $source
 - date published: 2024-11-18T03:43:32+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been using self-hosted RedLib (Docker Image: quay.io/redlib/redlib:latest) for browsing Reddit. Off late, I&#39;ve started getting a strange issue. Whenever I browse to RedLib, I get the following error message.</p> <h1>Failed to parse page JSON data: expected value at line 1 column 1 | <a href="/r/popular/hot">/r/popular/hot</a>.json?&amp;raw_json=1&amp;geo_filter=GLOBAL</h1> <p>If I do not get this message immediately, then I get it on clicking the Next Page button. Has anyone else faced this issue? If yes, have you been able to fix it?</p> <p>Thanks for your help in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ashj11"> /u/ashj11 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtvug0/error_on_using_redlib_for_reddit/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtvug0/error_on_using_redlib_for_reddit/">[comments]</a></span>

## Let's talk bookmarks across machines/browsers. Is that over and we use homepage/linkwarden instead?
 - [https://www.reddit.com/r/selfhosted/comments/1gtvj1b/lets_talk_bookmarks_across_machinesbrowsers_is](https://www.reddit.com/r/selfhosted/comments/1gtvj1b/lets_talk_bookmarks_across_machinesbrowsers_is)
 - RSS feed: $source
 - date published: 2024-11-18T03:26:04+00:00

<!-- SC_OFF --><div class="md"><p>Ive been struggling with this in my head the last few days and finally decided to put it down here to see what others think.</p> <p>Ive been and still am an apple guy, so most of my stuff syncs between devices pretty well, including in this case, bookmarks. </p> <p>But my needs have been changing lately, and have been frustrated with Safari on the Mac for a while and want to look at using Firefox. And in windows, Edge or Chrome (just works for me at work).</p> <p>In a perfect world, Id find a sync system that works for all of them, but that doesnt seem to be the case (that I can find). But then my mind went to using linkwarden instead and not worrying about any browser, just using it as homepage.</p> <p>So I thought I would ask the hive mind their thoughts. Ive not wrapped my head around Linkwarden yet, and its going to take a bit to get used to it, but maybe that where I should put my eggs?</p> <p>Or is there a magic bookmark syncing system that I c

## App to search the webb
 - [https://www.reddit.com/r/selfhosted/comments/1gtv463/app_to_search_the_webb](https://www.reddit.com/r/selfhosted/comments/1gtv463/app_to_search_the_webb)
 - RSS feed: $source
 - date published: 2024-11-18T03:03:33+00:00

<!-- SC_OFF --><div class="md"><p>Hi y&#39;all, I am not sure if something exists but I am wanting an application that could scrape google searches or specific websites for specific terms and flag when it comes up wiht a new hit. </p> <p>The use case is, there is a plot of land that I am hoping will go into development and I want to be able to monitor when something might show up online referencing this land for development reasons so I can get in early and not miss out on it. </p> <p>Does something like this exist? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Phorc3"> /u/Phorc3 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtv463/app_to_search_the_webb/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtv463/app_to_search_the_webb/">[comments]</a></span>

## Can I self host a mail server with my setup?
 - [https://www.reddit.com/r/selfhosted/comments/1gtuqxn/can_i_self_host_a_mail_server_with_my_setup](https://www.reddit.com/r/selfhosted/comments/1gtuqxn/can_i_self_host_a_mail_server_with_my_setup)
 - RSS feed: $source
 - date published: 2024-11-18T02:43:55+00:00

<!-- SC_OFF --><div class="md"><p>I would like to stop using the Gmail smtp server since it is starting to not be that great. Can I self host an smtp server and have the emails still go to Gmail and/or Whatsapp? I have many devices so email is preferred.</p> <p>I am being CGNAT with Starlink, however I already use Cloudflare tunnels with my own domain to host some stuff.</p> <p>use case for this is my UPS&#39;s and NVR. (Would be nice to use Whatsapp instead of Gmail for receiving snapshots from my NVR)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/_dark__mode_"> /u/_dark__mode_ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtuqxn/can_i_self_host_a_mail_server_with_my_setup/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtuqxn/can_i_self_host_a_mail_server_with_my_setup/">[comments]</a></span>

## The Unsung Heroes of Self-hosting: ChatGPT/Claude/etc.
 - [https://www.reddit.com/r/selfhosted/comments/1gtujkw/the_unsung_heroes_of_selfhosting_chatgptclaudeetc](https://www.reddit.com/r/selfhosted/comments/1gtujkw/the_unsung_heroes_of_selfhosting_chatgptclaudeetc)
 - RSS feed: $source
 - date published: 2024-11-18T02:33:03+00:00

<!-- SC_OFF --><div class="md"><p>(Cross-posted from <a href="/r/homelab">r/homelab</a>. If that is taboo, please feel free to remove. I love this community specifically and don&#39;t want to piss off the mods.)</p> <p>The Unsung Heroes of Homelabbing: ChatGPT/Claude/etc</p> <p>Here me out. Homelabbing has been (and mostly continues to be) the niche of IT geeks, FOSS hobbyists, and privacy purists. For the most part that is due to the technical hurdles one must overcome. And let&#39;s face it, most normies are NOT trained to be auto-didacts. </p> <p>I&#39;m a Product Manager. I live and breathe products and features and roadmaps and user personas and epics and stories. General rule of thumb for consumer grade applications: if your users need instructions, you failed. </p> <p>So it comes as no surprise that self hosting in general and homelabbing in particular continue to be the niche domain of motivated hobbyists.</p> <p>However, speaking from personal experience, the rise of the LLM

## homepage and qbittorrentvpn
 - [https://www.reddit.com/r/selfhosted/comments/1gtuexl/homepage_and_qbittorrentvpn](https://www.reddit.com/r/selfhosted/comments/1gtuexl/homepage_and_qbittorrentvpn)
 - RSS feed: $source
 - date published: 2024-11-18T02:26:12+00:00

<!-- SC_OFF --><div class="md"><p>Im trying to setup homepage but i&#39;m having issue with my qbittorrentvpn </p> <p>widget: type: qbittorrent url: <a href="http://10.0.0.134:8080">http://10.0.0.134:8080</a> username: username password: password</p> <p>this is the setup inside my services files then a i get this error</p> <p>API Error: JSON.parse: unexpected character at line 1 column 1 of the JSON data</p> <p>is there a setting inside qbittorrent i need to modify or is it because its qbittorrentvpn and the vpn is causing the issue.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/aboby86"> /u/aboby86 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtuexl/homepage_and_qbittorrentvpn/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtuexl/homepage_and_qbittorrentvpn/">[comments]</a></span>

