# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Watchtower - Not Monitoring Only
 - [https://www.reddit.com/r/selfhosted/comments/1hmb7vu/watchtower_not_monitoring_only](https://www.reddit.com/r/selfhosted/comments/1hmb7vu/watchtower_not_monitoring_only)
 - RSS feed: $source
 - date published: 2024-12-25T23:05:35+00:00

<!-- SC_OFF --><div class="md"><p>title.</p> <p>Why is my Watchtower instance still updating my containers? I have it set to watch only but it&#39;s still auto updating my containers. I want it to only notify my of updates and leave it at that so I can update on my own time and monitor for breaking changes. Any suggestions?</p> <pre><code>services: watchtower: image: containrrr/watchtower container_name: watchtower environment: - TZ=Australia/Sydney - WATCHTOWER_MONITOR_ONLY=true - WATCHTOWER_INCLUDE_STOPPED=true - WATCHTOWER_INCLUDE_RESTARTING=true - WATCHTOWER_SCHEDULE=0 0 * * * * - WATCHTOWER_NOTIFICATIONS=shoutrrr - WATCHTOWER_NOTIFICATIONS_LEVEL=trace - WATCHTOWER_NOTIFICATION_URL=discord:// - WATCHTOWER_HTTP_API_UPDATE=false - WATCHTOWER_HTTP_API_METRICS=true - WATCHTOWER_HTTP_API_TOKEN=token - WATCHTOWER_HTTP_API_PERIODIC_POLLS=true ports: - 8090:8080 volumes: - /var/run/docker.sock:/var/run/docker.sock restart: unless-stopped networks: {} </code></pre> <p>I am able to use lab

## [Advice needed] Exposing my Minecraft server to the outside world
 - [https://www.reddit.com/r/selfhosted/comments/1hmawac/advice_needed_exposing_my_minecraft_server_to_the](https://www.reddit.com/r/selfhosted/comments/1hmawac/advice_needed_exposing_my_minecraft_server_to_the)
 - RSS feed: $source
 - date published: 2024-12-25T22:48:23+00:00

<!-- SC_OFF --><div class="md"><p>Hi! I&#39;ve been trying to expose a self-hosted Minecraft server for some time now. I&#39;ve tried using services like playit and ngrok. I just got myself a domain on namecheap I&#39;m planning to use on both the MC server and my future home server. I can&#39;t use any sorts of port forwarding on my router since I&#39;m stuck behind CGNAT, so I&#39;m dependent on tunneling instead. Is there any way to make my server publicly accessible without any additional software on the client side or paid service? I need both TCP (25565) and UDP (24454 for voice chat) ports and all of the services provide only the TCP. The game server is currently running on Windows.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mineplayerminer"> /u/Mineplayerminer </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hmawac/advice_needed_exposing_my_minecraft_server_to_the/">[link]</a></span> &#32; <span><a href="https

## Vpn traffic through proxy
 - [https://www.reddit.com/r/selfhosted/comments/1hmafgh/vpn_traffic_through_proxy](https://www.reddit.com/r/selfhosted/comments/1hmafgh/vpn_traffic_through_proxy)
 - RSS feed: $source
 - date published: 2024-12-25T22:22:13+00:00

<!-- SC_OFF --><div class="md"><p>I use Wireguard vpn to access everything on my home. I want to use burpsuite as a proxy to intercept some data when I am not home through my vpn. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/anonuser-al"> /u/anonuser-al </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hmafgh/vpn_traffic_through_proxy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hmafgh/vpn_traffic_through_proxy/">[comments]</a></span>

## What tool do you use to track network traffic in linux?
 - [https://www.reddit.com/r/selfhosted/comments/1hm9sft/what_tool_do_you_use_to_track_network_traffic_in](https://www.reddit.com/r/selfhosted/comments/1hm9sft/what_tool_do_you_use_to_track_network_traffic_in)
 - RSS feed: $source
 - date published: 2024-12-25T21:47:15+00:00

<!-- SC_OFF --><div class="md"><p>Using hetzner cloud and would like to be able to monitor network traffic to ensure I don&#39;t go over the included 20TB. maybe something that saves the logs i.e. MBs per Minute or something.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/juan_berger"> /u/juan_berger </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm9sft/what_tool_do_you_use_to_track_network_traffic_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm9sft/what_tool_do_you_use_to_track_network_traffic_in/">[comments]</a></span>

## Filebrowser 500 internal server error
 - [https://www.reddit.com/r/selfhosted/comments/1hm9npp/filebrowser_500_internal_server_error](https://www.reddit.com/r/selfhosted/comments/1hm9npp/filebrowser_500_internal_server_error)
 - RSS feed: $source
 - date published: 2024-12-25T21:39:53+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hm9npp/filebrowser_500_internal_server_error/"> <img src="https://preview.redd.it/9t8x9heud29e1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=931b0349d0c429d82b4772fafb10dd0583bc1c50" alt="Filebrowser 500 internal server error" title="Filebrowser 500 internal server error" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi! I&#39;ve had this problem since yesterday, and I can&#39;t solve it. So, I&#39;ve set up my Filebrowser config and I&#39;ve been using Filebrowser for a while and everything was working and all of a sudden this problem pops up &quot;Filebrowser 500 internal server error&quot;. So, how can I fix this problem for sure?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/richardsonoge"> /u/richardsonoge </a> <br/> <span><a href="https://i.redd.it/9t8x9heud29e1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm9npp

## Questions and no experience
 - [https://www.reddit.com/r/selfhosted/comments/1hm9b4r/questions_and_no_experience](https://www.reddit.com/r/selfhosted/comments/1hm9b4r/questions_and_no_experience)
 - RSS feed: $source
 - date published: 2024-12-25T21:20:48+00:00

<!-- SC_OFF --><div class="md"><p>I recently ordered my first mini PC, which I plan to set up as a server for various tasks. Since I’m new to this, everything will be a learning experience. My initial setup involves running Proxmox as the hypervisor, with a VM for Home Assistant and another VM hosting Docker and Docker Compose.</p> <p>Now, I have several questions related to reverse proxies, authentication, and Cloudflare tunnels.</p> <p>Domain and Reverse Proxy Setup</p> <p>My plan is to purchase a domain through Cloudflare and configure a reverse proxy to handle local HTTP-to-HTTPS conversions with valid SSL certificates. I’d also like to access my applications using a domain name rather than IP and port, with the format *.local.domain.xx for local access. Is this possible, and can it be achieved without opening any ports on my router?</p> <p>For remote access (e.g., to my Home Assistant server), I’m considering using a Cloudflare tunnel. Here’s where I need clarity:</p> <p>For the

## GUIDE: Importing and deploying a Kali Linux LXC on Proxmox 8.3.2
 - [https://www.reddit.com/r/selfhosted/comments/1hm91tw/guide_importing_and_deploying_a_kali_linux_lxc_on](https://www.reddit.com/r/selfhosted/comments/1hm91tw/guide_importing_and_deploying_a_kali_linux_lxc_on)
 - RSS feed: $source
 - date published: 2024-12-25T21:06:53+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/sacentral"> /u/sacentral </a> <br/> <span><a href="https://homelab.sacentral.info/posts/kali-linux-on-proxmox-8-3/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm91tw/guide_importing_and_deploying_a_kali_linux_lxc_on/">[comments]</a></span>

## Looking for a Filezilla-like that isn't terrible at handling large numbers of files
 - [https://www.reddit.com/r/selfhosted/comments/1hm8ltr/looking_for_a_filezillalike_that_isnt_terrible_at](https://www.reddit.com/r/selfhosted/comments/1hm8ltr/looking_for_a_filezillalike_that_isnt_terrible_at)
 - RSS feed: $source
 - date published: 2024-12-25T20:43:44+00:00

<!-- SC_OFF --><div class="md"><p>I use Filezilla for managing my website, and 90% of the time it&#39;s wonderful. But whenever I need to upload, download, or delete a large number of small files, it takes ridiculously long amounts of time; on the order of 1 second per file, making me wait minutes or hours before it&#39;s done.</p> <p>It&#39;s doing this because it only uses core ftp/sftp commands, which requires it to manipulate the files one at a time, incurring network overhead each time. But there are much less stupid ways to do this; it could zip all the files in advance, upload them as a single file, then dezip on the other machine. For deleting, it could ssh in and use rm -r.</p> <p>Is there an extension to Filezilla that gives it this functionality? Or is there another program that is just as simple and convenient as Filezilla in all other ways, but handles lots of small files in a more expedient manner?</p> <p>(For Mac.)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a h

## lurker: a selfhostable, read-only reddit client, christmas update!
 - [https://www.reddit.com/r/selfhosted/comments/1hm8j03/lurker_a_selfhostable_readonly_reddit_client](https://www.reddit.com/r/selfhosted/comments/1hm8j03/lurker_a_selfhostable_readonly_reddit_client)
 - RSS feed: $source
 - date published: 2024-12-25T20:39:32+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://github.com/oppiliappan/lurker/releases/tag/v0.1.1">https://github.com/oppiliappan/lurker/releases/tag/v0.1.1</a></p> <p>features:<br/> - show `edited` status of comments<br/> - add `open` link that links back to the big red site<br/> - add submission urls to posts<br/> - add post search, with text-based filters (use `subreddit:foo bar` to<br/> search for `bar` within `<a href="/r/foo">r/foo</a>`<br/> - implement back button in comments page: goes back to exact scroll<br/> position in previous page<br/> - add next/prev links in comment threads, to scroll directly to<br/> next/prev sibling comment </p> <p>fixes:<br/> - fix docker image several times<br/> - fix unsub button in subs page<br/> - avoid loopback address for docker compose</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Creative-Air2049"> /u/Creative-Air2049 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm8j03/

## automation : script and docker-compose scheduler, report, dashboard
 - [https://www.reddit.com/r/selfhosted/comments/1hm82k1/automation_script_and_dockercompose_scheduler](https://www.reddit.com/r/selfhosted/comments/1hm82k1/automation_script_and_dockercompose_scheduler)
 - RSS feed: $source
 - date published: 2024-12-25T20:14:31+00:00

<!-- SC_OFF --><div class="md"><p>Hi,<br/> Does anyone know about a tool to can start bash scripts and docker-compose on different linux (windows maybe too) hosts remotely, on demand or per schedule, collect the output/status and show the results in a dashboard, and possibly send emails on failure ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/KRS_33"> /u/KRS_33 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm82k1/automation_script_and_dockercompose_scheduler/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm82k1/automation_script_and_dockercompose_scheduler/">[comments]</a></span>

## Slink v1.3.0 is here 🎉 - Self-Hosted Image Sharing Service
 - [https://www.reddit.com/r/selfhosted/comments/1hm7xrt/slink_v130_is_here_selfhosted_image_sharing](https://www.reddit.com/r/selfhosted/comments/1hm7xrt/slink_v130_is_here_selfhosted_image_sharing)
 - RSS feed: $source
 - date published: 2024-12-25T20:07:35+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hm7xrt/slink_v130_is_here_selfhosted_image_sharing/"> <img src="https://external-preview.redd.it/jGG2ie1Nc8oieR1WDuQsgPj7c4CiviwSBYH5AF1r6Hc.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=b0a1f52e98da3d96b129382cd72d232acb4f17fe" alt="Slink v1.3.0 is here 🎉 - Self-Hosted Image Sharing Service " title="Slink v1.3.0 is here 🎉 - Self-Hosted Image Sharing Service " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Happy Holidays, <a href="/r/selfhosted">r/selfhosted</a>! It’s been a while since the last big release of <strong>Slink</strong>, and I’m super excited to share that <a href="https://github.com/andrii-kryvoviaz/slink/releases/tag/v1.3.0">v1.3.0</a> is finally here! Managed to find some time between a busy full-time job to work on updates that I hope you’ll like. </p> <p>GitHub Repo: <a href="https://github.com/andrii-kryvoviaz/slink">https://github.com/andrii-kryvoviaz/slink</a> </p> <h1>What’s New:</h1

## 🚀 Sharing My Docker Container for Streaming with OBS-Studio 🎥
 - [https://www.reddit.com/r/selfhosted/comments/1hm7lab/sharing_my_docker_container_for_streaming_with](https://www.reddit.com/r/selfhosted/comments/1hm7lab/sharing_my_docker_container_for_streaming_with)
 - RSS feed: $source
 - date published: 2024-12-25T19:49:29+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! 👋<br/> I&#39;ve created a Docker container to make using OBS-Studio for streaming and recording easier than ever. It comes pre-configured with all the essential plugins to save you time and ensure a smooth experience.</p> <h1>What&#39;s Inside?</h1> <p>✅ <strong>OBS-Studio</strong> (latest version).<br/> ✅ Popular plugins to extend functionality (e.g., Virtual Camera, NDI, Advanced Audio Capture, etc.).<br/> ✅ Optimized settings for stable performance.<br/> ✅ Easy integration with streaming platforms like Twitch, YouTube, Facebook, and more.</p> <h1>Why Docker?</h1> <p>💡 Docker ensures an isolated environment for OBS, avoiding conflicts with system libraries and guaranteeing stability, regardless of your OS.</p> <h1>How to Get Started?</h1> <ol> <li>Download the Docker container from my repository (link below).</li> <li>Launch the container with a single command.</li> <li>Customize OBS-Studio to your needs and start streaming!</li> </ol

## Docker best practice: "latest" tag vs. tag-pinning
 - [https://www.reddit.com/r/selfhosted/comments/1hm7evq/docker_best_practice_latest_tag_vs_tagpinning](https://www.reddit.com/r/selfhosted/comments/1hm7evq/docker_best_practice_latest_tag_vs_tagpinning)
 - RSS feed: $source
 - date published: 2024-12-25T19:39:56+00:00

<!-- SC_OFF --><div class="md"><p>I run most of my docker deployments on the &quot;latest&quot; tag, meaning: I have Watchtower update most of my containers as soon as there&#39;s a new release. Today is the first time I&#39;ve regretted this when a bad release took down my music server. I&#39;ve read people like to pin their docker deployments to a specific release tag for this very reason: it allows them to test updates first and then deploy once they find they&#39;re stable. I wonder, though, whether this does not open you up to security risks. After all, new versions may not just bring feature updates, but also fixes for software vulnerabilities.</p> <p>So my question to this sub is: is there a &quot;best practice&quot; here? Do you guys just wing it and auto-update like I have so far? Do you pin your containers to a known stable version? How often do you update manually, and what do your updating procedures look like?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="ht

## The Best christmas gift ever.
 - [https://www.reddit.com/r/selfhosted/comments/1hm7c27/the_best_christmas_gift_ever](https://www.reddit.com/r/selfhosted/comments/1hm7c27/the_best_christmas_gift_ever)
 - RSS feed: $source
 - date published: 2024-12-25T19:35:48+00:00

<!-- SC_OFF --><div class="md"><p>Well, my girlfriend asked me to have a personal instance of: lidarr, radarr, sonarr, overseerr, and even let me install wireguard on her Phone. </p> <p>1tb of anime in 2 weeks: i&#39;m so proud of her! I&#39;m trying to make her ditch prime video/netflix/et cetera, i feel like we are close. </p> <p>She even stayed silent on the last 16tb drive i bought. </p> <p>It&#39;s my (Our) personal christmas Carol. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rebislori"> /u/rebislori </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm7c27/the_best_christmas_gift_ever/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm7c27/the_best_christmas_gift_ever/">[comments]</a></span>

## Need affordable and easy to use client hardware to give elderly family member access to Jellyfin - please help!
 - [https://www.reddit.com/r/selfhosted/comments/1hm6gol/need_affordable_and_easy_to_use_client_hardware](https://www.reddit.com/r/selfhosted/comments/1hm6gol/need_affordable_and_easy_to_use_client_hardware)
 - RSS feed: $source
 - date published: 2024-12-25T18:50:27+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys!</p> <p>Today I learned that an ederly family member would love to watch some old shows and movies which are pretty hard to get on physical media.</p> <p>Since I still have some bandwidth available I thought I`d simply add a separate library to my server for them and set their TV up with the Jellyfin app but then I found out that there is no client for their TV. Sadly I dont know anything about these HDMI TV sticks and so I am having a hard time deciding on one that is easy to use.</p> <p><strong>Specs:</strong></p> <ul> <li>Plugs in to AV-receiver via HDMI</li> <li>Stick or box with WiFi (no mini PC/RasPi)</li> <li>Has a remote included (no keyboard + mouse navigation)</li> <li>Plays 1080p @ 35 Mbits</li> <li>Native H.264 maybe even H.265 @ 30 FPS</li> <li>Easy turn on and navigate</li> <li>Affordable (plz dont suggest hardware that is overkill for this purpose)</li> </ul> <p>We would really appreciate your help!</p> </div><!-- SC_ON --> &#

## Guacamole: "The version of guacamole-client is incompatible"
 - [https://www.reddit.com/r/selfhosted/comments/1hm628x/guacamole_the_version_of_guacamoleclient_is](https://www.reddit.com/r/selfhosted/comments/1hm628x/guacamole_the_version_of_guacamoleclient_is)
 - RSS feed: $source
 - date published: 2024-12-25T18:28:55+00:00

<!-- SC_OFF --><div class="md"><p>About a month ago, I inadvertently trashed my VM running Guacamole. It had been up for at least a year, maybe two. I&#39;ve been trying to rebuild it, using the <a href="https://adamtheautomator.com/apache-guacamole/">article I had in my notes</a> as how I did it in the first place, cross-referencing the official docs. It doesn&#39;t work. Just trying to get to the front page fails, with the following message in <code>syslog</code>:</p> <p><code>guacd[36987]: ERROR:#011Guacamole protocol violation. Perhaps the version of guacamole-client is incompatible with this version of guacd?</code></p> <p>No other log is particularly helpful. How it&#39;s set/things I&#39;ve tried:</p> <ul> <li>First attempt at OS is Ubuntu 24.10, but I&#39;ve since been trying 20.04.</li> <li>My first cut was Tomcat10, before I realized it had to be Tomcat9</li> <li>I&#39;ve downloaded Guacamole from the Apache site. I originally did version 1.5.5, the latest, but tried 1.4.0,

## DDOS Game-Server Protection
 - [https://www.reddit.com/r/selfhosted/comments/1hm5wm6/ddos_gameserver_protection](https://www.reddit.com/r/selfhosted/comments/1hm5wm6/ddos_gameserver_protection)
 - RSS feed: $source
 - date published: 2024-12-25T18:20:45+00:00

<!-- SC_OFF --><div class="md"><p>Here&#39;s your text, reformulated and corrected for clarity and grammar:</p> <p>Hi, I have a DDNS service hosted on No-IP, which points to my home IP (e.g., 1.1.1.1).</p> <p>I have two local machines: a Raspberry Pi 5 hosting three websites on the local IP 192.168.1.1, and another machine running a FiveM server on the local IP 192.168.1.2.</p> <p>I&#39;ve opened the necessary ports on my router, which allows me to connect to the FiveM server from anywhere, even using my.myddns.net. However, this exposes my real IP address to the internet, making me vulnerable to DDoS attacks.</p> <p>What solutions do I have to protect my server? I want to host the FiveM server securely, but since FiveM&#39;s CFX-Finder reveals the server&#39;s IP, I&#39;m concerned about security.</p> <p>I’ve considered using Cloudflare to secure my domain, but when I ping the domain, it still reveals my real IP, which is not protected. Can anyone suggest a solution to secure my set

## Seeking Self-Hosted Voice Assistant for Interview Practice with Active Dialogue Support
 - [https://www.reddit.com/r/selfhosted/comments/1hm5plo/seeking_selfhosted_voice_assistant_for_interview](https://www.reddit.com/r/selfhosted/comments/1hm5plo/seeking_selfhosted_voice_assistant_for_interview)
 - RSS feed: $source
 - date published: 2024-12-25T18:10:15+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a self-hosted solution similar to ChatGPT&#39;s Voice Assistant feature. The ideal system would allow me to upload the context of various interviews and practice in an active dialogue mode. It should ask me questions, let me answer, and ideally integrate with Ollama so I can run any compatible AI model. An offline or local PC program would be fine—no need for internet accessibility.</p> <p>Does such a program exist? Or are there tools I could adapt for this purpose? Would love recommendations!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Vegetable-Zone-1328"> /u/Vegetable-Zone-1328 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm5plo/seeking_selfhosted_voice_assistant_for_interview/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm5plo/seeking_selfhosted_voice_assistant_for_interview/">[comments]</a></span>

## Leantime on Kubernetes
 - [https://www.reddit.com/r/selfhosted/comments/1hm5mt6/leantime_on_kubernetes](https://www.reddit.com/r/selfhosted/comments/1hm5mt6/leantime_on_kubernetes)
 - RSS feed: $source
 - date published: 2024-12-25T18:06:06+00:00

<!-- SC_OFF --><div class="md"><p>Greetings all,</p> <p>Leantime.io is a great platform but there isn&#39;t much guidance on how to get it running on Kubernetes - a few out of date helm charts and some sample files exist that didn&#39;t get me too far.</p> <p>So I made my own </p> <p><a href="https://github.com/Salowais/leantime-kubernetes">https://github.com/Salowais/leantime-kubernetes</a></p> <p>I hope someone finds this useful.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SAlOwais"> /u/SAlOwais </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm5mt6/leantime_on_kubernetes/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm5mt6/leantime_on_kubernetes/">[comments]</a></span>

## Simplest UI for a Multi-Node Server Management with Automatic HTTPS?
 - [https://www.reddit.com/r/selfhosted/comments/1hm596m/simplest_ui_for_a_multinode_server_management](https://www.reddit.com/r/selfhosted/comments/1hm596m/simplest_ui_for_a_multinode_server_management)
 - RSS feed: $source
 - date published: 2024-12-25T17:47:07+00:00

<!-- SC_OFF --><div class="md"><p>I’m seeking advice on whether there’s a simpler toolset to achieve what I’m building. Ideally, I want a “set-it-and-forget-it” server configuration, with project management handled through a user-friendly UI afterward.</p> <p>Project Overview:</p> <ul> <li><p>The project involves running 50-100+ small servers, each pre-installed with the same Docker Compose but configured with slightly different input parameters (e.g., an input file uploaded to each server).</p></li> <li><p>I’m using Hetzner Cloud and adding all servers to a shared private network.</p></li> <li><p>Each server needs to be accessible via a subdomain structured like this:</p> <ul> <li><a href="https://subdomain.website.com/1/">https://subdomain.website.com/1/</a> -&gt; Port 8080 on Server #1</li> <li><a href="https://subdomain.website.com/2/">https://subdomain.website.com/2/</a> -&gt; Port 8080 on Server #2</li> <li><a href="https://subdomain.website.com/3/">https://subdomain.website.co

## Remote access and Jellyfin
 - [https://www.reddit.com/r/selfhosted/comments/1hm4mam/remote_access_and_jellyfin](https://www.reddit.com/r/selfhosted/comments/1hm4mam/remote_access_and_jellyfin)
 - RSS feed: $source
 - date published: 2024-12-25T17:13:32+00:00

<!-- SC_OFF --><div class="md"><p>I have recently gotten into this rabbit hole and turned my old pc into a homelab running debian. I&#39;ve configured it with samba, Jellyfin and access the shared drive through my windows laptop. It&#39;s working great and I intend to host my mern projects on the server as well. </p> <p>Anyways I was looking into remotely accessing Jellyfin and I looked into some options like port forwarding, wireguard/duckdns/pivpn, tailscale. I tried tailscale and it works decent enough. </p> <p>Now I access the shared drive from my laptop to transfer movies I legally obtained online but tailscale significantly affects my internet speed and the transfer takes a lot of time. Initially I tried subnetting so that I map the drive without changing the ip of the server and then using the tailscale ip but it still doesn&#39;t makes much difference. Are there better options than tailscale which doesn&#39;t affect the internet speed much, or maybe I&#39;m doing something wr

## Help updating Docker Redis please.
 - [https://www.reddit.com/r/selfhosted/comments/1hm4iyf/help_updating_docker_redis_please](https://www.reddit.com/r/selfhosted/comments/1hm4iyf/help_updating_docker_redis_please)
 - RSS feed: $source
 - date published: 2024-12-25T17:08:37+00:00

<!-- SC_OFF --><div class="md"><p>I got an alert from DIUN that there is a docker redis update. I noticed that Immich uses redis also. I asked ChatGPT how to properly update it and it said to delete immich redis first. I just wanted to check with ya&#39;ll is that the right thing to do? Will it not affect Immich? The last time tI want to do is break Immich in anyway. Thanks in advace. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/iamwhoiwasnow"> /u/iamwhoiwasnow </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm4iyf/help_updating_docker_redis_please/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm4iyf/help_updating_docker_redis_please/">[comments]</a></span>

## Wanted to share my homelab setup
 - [https://www.reddit.com/r/selfhosted/comments/1hm4a4o/wanted_to_share_my_homelab_setup](https://www.reddit.com/r/selfhosted/comments/1hm4a4o/wanted_to_share_my_homelab_setup)
 - RSS feed: $source
 - date published: 2024-12-25T16:56:10+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hm4a4o/wanted_to_share_my_homelab_setup/"> <img src="https://external-preview.redd.it/S0wx8zrLjWUmi0zPxyKehHCi5obVbS2_LGmSviw8hdA.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=775310569f58e5ae9a4ac893f777e152225f5889" alt="Wanted to share my homelab setup" title="Wanted to share my homelab setup" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello <a href="/r/selfhosted">r/selfhosted</a>, it&#39;s my first reddit post after being part of this community since April 2024. I&#39;ve learned a lot thank to you.</p> <p>To manage the configuration of my laptop, I used Ansible, and so I did the same for my homelab infrastructure.</p> <p>I actually use an HP Proliant Microserver G8 as a Proxmox server: - 16Gb of RAM (the maximum amount of RAM) - 1 SSD on the optical bay for the OS - 2 HDD for the VM/CT storage with ZFS RAID1</p> <p>I also have an HP Proliant Microserver N54L as a Proxmox Backup server - 4Gb of RA

## Zoraxy | Anyone toyed with it?
 - [https://www.reddit.com/r/selfhosted/comments/1hm3dy4/zoraxy_anyone_toyed_with_it](https://www.reddit.com/r/selfhosted/comments/1hm3dy4/zoraxy_anyone_toyed_with_it)
 - RSS feed: $source
 - date published: 2024-12-25T16:07:55+00:00

<!-- SC_OFF --><div class="md"><p>Was curious if anyone has played around with Zoraxy Reverse Proxy? </p> <p>I&#39;ve been testing it for last 48 hours on and off and it seems pretty stable and has some really good features as well as most things you would expect. Just curious if I am missing anything or anyone has a bit more extended experience with it that can shed light on some things they ran into. </p> <p>What drew me to it orignially was its non dependency on Docker with ability to run as a standalone instance in Linux which makes it potentially a good case for leveraging it as a reverse proxy for non docker services within your infrastructure. </p> <p>In my case, I have an isolated management network full of management related systems or management interfaces such as Portainer, VMware, Unifi UDM, iDRAC, and other security control management. What I am currently testing is Zoraxy sitting in a &quot;landing zone&quot; on a small /30 network to act as reverse proxy strictly for m

## UPDATE: This past year, I grew obsessed with self-hosting. What's missing from my setup?
 - [https://www.reddit.com/r/selfhosted/comments/1hm3bfe/update_this_past_year_i_grew_obsessed_with](https://www.reddit.com/r/selfhosted/comments/1hm3bfe/update_this_past_year_i_grew_obsessed_with)
 - RSS feed: $source
 - date published: 2024-12-25T16:04:02+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hm3bfe/update_this_past_year_i_grew_obsessed_with/"> <img src="https://b.thumbs.redditmedia.com/CvBCy0ZeEouoOd_wHEFEnFEyQfzmqRWrC2Sqfaq2FHI.jpg" alt="UPDATE: This past year, I grew obsessed with self-hosting. What's missing from my setup? " title="UPDATE: This past year, I grew obsessed with self-hosting. What's missing from my setup? " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/yp6wsj9vp09e1.png?width=2020&amp;format=png&amp;auto=webp&amp;s=7984334f6513210db6e479ae7069cd53b5776076">https://preview.redd.it/yp6wsj9vp09e1.png?width=2020&amp;format=png&amp;auto=webp&amp;s=7984334f6513210db6e479ae7069cd53b5776076</a></p> <p><a href="https://preview.redd.it/lzyh6i9vp09e1.png?width=1986&amp;format=png&amp;auto=webp&amp;s=b51f648a74d001fc1ca19c1d64340c8890f7c42e">https://preview.redd.it/lzyh6i9vp09e1.png?width=1986&amp;format=png&amp;auto=webp&amp;s=b51f648a74d001fc1ca19c1d64340

## Trouble connecting to Jellyfin server through DUMAOS
 - [https://www.reddit.com/r/selfhosted/comments/1hm33r1/trouble_connecting_to_jellyfin_server_through](https://www.reddit.com/r/selfhosted/comments/1hm33r1/trouble_connecting_to_jellyfin_server_through)
 - RSS feed: $source
 - date published: 2024-12-25T15:52:26+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I have spent many hours attempting to make this setup work.<br/> I have a Jellyfin server running on a Linux Mint PC in my home, and I am using an XR1000 Nighthawk as a router. I have opened all 4 ports required for JF to operate on DumaOS via port forwarding (1900 8920 8096 and 7359), and the pc is visible in clients such as VLC as being a media server, but never loads anything when clicked on and cannot be found when trying to connect via jellyfin client on my phone.<br/> Everything is connected via wifi. I feel I am missing something basic and critical, but cannot figure this out.<br/> Thanks for your time.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/flakeboss"> /u/flakeboss </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm33r1/trouble_connecting_to_jellyfin_server_through/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm33r1/trouble_con

## Simple documentation service?
 - [https://www.reddit.com/r/selfhosted/comments/1hm33ah/simple_documentation_service](https://www.reddit.com/r/selfhosted/comments/1hm33ah/simple_documentation_service)
 - RSS feed: $source
 - date published: 2024-12-25T15:51:45+00:00

<!-- SC_OFF --><div class="md"><p>Hello. Can someone sugggest a super simple documentation service, where I can login, edit markdown, then save it and for public users it loads just documentation page?</p> <p>Think of X service, but some users might need additional guidance or troubleshooting steps, so some super simple &quot;single-page&quot; (or several pages) documentation page would be great.</p> <p>Mediawiki is seem a bit overkill - ideally just a single Docker container with sqlite.</p> <p>Does anything like this exist? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CumInsideMeDaddyCum"> /u/CumInsideMeDaddyCum </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm33ah/simple_documentation_service/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm33ah/simple_documentation_service/">[comments]</a></span>

## Software for teacher to manage books?
 - [https://www.reddit.com/r/selfhosted/comments/1hm240x/software_for_teacher_to_manage_books](https://www.reddit.com/r/selfhosted/comments/1hm240x/software_for_teacher_to_manage_books)
 - RSS feed: $source
 - date published: 2024-12-25T14:55:50+00:00

<!-- SC_OFF --><div class="md"><p>The wife is a teacher and has a library of physical books in her classroom.</p> <p>Anything I can host for her that let&#39;s her inventory/catalog her books? Ideally using the camera on the phone.</p> <p>With this catalog I&#39;m hoping it will help her keep track of books in a series or by author she might be missing.</p> <p>Tracking check out and in by her students would be a nice feature as well.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/iamofnohelp"> /u/iamofnohelp </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm240x/software_for_teacher_to_manage_books/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm240x/software_for_teacher_to_manage_books/">[comments]</a></span>

## Am I using Traefik the "right way"?
 - [https://www.reddit.com/r/selfhosted/comments/1hm1lth/am_i_using_traefik_the_right_way](https://www.reddit.com/r/selfhosted/comments/1hm1lth/am_i_using_traefik_the_right_way)
 - RSS feed: $source
 - date published: 2024-12-25T14:24:40+00:00

<!-- SC_OFF --><div class="md"><p>I just switched from Nginx Proxy Manager to Traefik, a probably completely unnecessary move, except for my own DevOps learning I suppose.</p> <p>Using npm, I would manually configure every ip address and port to a subdomain and domain, whether it be in a docker container or not (like the Home Assistant OS running on a raspberry pi).</p> <p>In Traefik, I don&#39;t have to manually configure anything that&#39;s a docker container anymore (except putting labels on them). I&#39;m not sure what the best approach is for non docker web applications, but I have been using the files Provider option and manually putting them into a dynamic-configuration.yml file. Is this the only or &quot;optimal&quot; (subjective, I know) way to do it, or is there something better?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ottovonbizmarkie"> /u/ottovonbizmarkie </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/

## Homepage Dashboard
 - [https://www.reddit.com/r/selfhosted/comments/1hm1a5f/homepage_dashboard](https://www.reddit.com/r/selfhosted/comments/1hm1a5f/homepage_dashboard)
 - RSS feed: $source
 - date published: 2024-12-25T14:03:48+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hm1a5f/homepage_dashboard/"> <img src="https://b.thumbs.redditmedia.com/xL4G9swl9-0gDoBZipaYQTqE_Y636LNYDib4UY5X3bM.jpg" alt="Homepage Dashboard" title="Homepage Dashboard" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Finally took the time to build a dashboard and ready to share. Let me know what y&#39;all think. Merry Christmas.</p> <p><a href="https://preview.redd.it/esq44e90409e1.png?width=3516&amp;format=png&amp;auto=webp&amp;s=6a9bf614f9a0caba0a7521be67e2ee7fbc2e4aa6">https://preview.redd.it/esq44e90409e1.png?width=3516&amp;format=png&amp;auto=webp&amp;s=6a9bf614f9a0caba0a7521be67e2ee7fbc2e4aa6</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FrankFixedIT"> /u/FrankFixedIT </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm1a5f/homepage_dashboard/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm1a5

## Offline Playlist (Android) for Jellyfin Music Library
 - [https://www.reddit.com/r/selfhosted/comments/1hm14k5/offline_playlist_android_for_jellyfin_music](https://www.reddit.com/r/selfhosted/comments/1hm14k5/offline_playlist_android_for_jellyfin_music)
 - RSS feed: $source
 - date published: 2024-12-25T13:54:15+00:00

<!-- SC_OFF --><div class="md"><p>Hello friends - first of all, apologies for posting this maybe it has already been answered in the past but for some reason, I am not able to find the answer despite searching. Probably my lack of searching skills.</p> <p>Anyways,</p> <p>I have a Jellyfin server running on windows and also Jellyplist to download music from Spotify playlist.</p> <p>I want to know if there is a good free android app to download the selected playlists from my server and then play music offline (android auto support).</p> <p>Thanks and apologies if repeated question. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Financial-Print-4638"> /u/Financial-Print-4638 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm14k5/offline_playlist_android_for_jellyfin_music/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hm14k5/offline_playlist_android_for_jellyfin_music/">[comments]</a

## The Azuracast on Windows via Docker plunge - do it
 - [https://www.reddit.com/r/selfhosted/comments/1hm0nie/the_azuracast_on_windows_via_docker_plunge_do_it](https://www.reddit.com/r/selfhosted/comments/1hm0nie/the_azuracast_on_windows_via_docker_plunge_do_it)
 - RSS feed: $source
 - date published: 2024-12-25T13:23:20+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m a Windows PC and that means I&#39;m scared of many things in the real world. That&#39;s kind of a joke - Linux and command line interfaces do intimidate me even when there are step by step procedures on websites; the warm blanket feel of the Ctrl+Z saftynet in windowed applications cannot be over stated. But I wanted to host a random playlist that wasn&#39;t strictly on IceCast or some equal.</p> <p>Azuracast seemed to tick all the boxes but requires Docker (new to me) and Ubuntu (very alien to me) as Windows installations or else paid options exist and this is just a hobby station, so paying for squat is out the window. I&#39;m a voice actor and want to use Entertainment-as-Resume so folks have examples to listen to. I thought that was a clever use of the service but the steps involved made me a coward.</p> <p>So this post is for other Windows milk-fed users (even if you don&#39;t admit it out loud). You can do it. If self-hosting a playlist

## Manager for my collections
 - [https://www.reddit.com/r/selfhosted/comments/1hlzyt5/manager_for_my_collections](https://www.reddit.com/r/selfhosted/comments/1hlzyt5/manager_for_my_collections)
 - RSS feed: $source
 - date published: 2024-12-25T12:35:11+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I am trying to find a self-hostable collection manager. Basically I have quite a few hobbies and just stuff in general that I would like to organize.</p> <p>I tried Memento on Android and I really liked it. Basically the perfect solution, but it requires monthly subscription to have it synced between devices and get other features... and even then there are bugs with pictures and their offline handling. I refuse to pay that much for glorified database for my stuff.</p> <p>I tried Homebox and Koillection, too.<br/> Homebox sucks if you depend on custom fields as you will need to remake them each time per new item.<br/> Koillection is quite good, but I struggled with categorizing - you can make categories, but they are non-clickable and basically useless. You need to use tags and they get cluttered really quickly.</p> <p>Again, Memento was awesome. You could restrict and tweak each field and it&#39;s values. I had like main category, then

## GitHub template that lets you create a dynamic GitHub Page containing all the RSS/Atom articles you follow, updated every hour (See readme for details)
 - [https://www.reddit.com/r/selfhosted/comments/1hlzthk/github_template_that_lets_you_create_a_dynamic](https://www.reddit.com/r/selfhosted/comments/1hlzthk/github_template_that_lets_you_create_a_dynamic)
 - RSS feed: $source
 - date published: 2024-12-25T12:24:01+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hlzthk/github_template_that_lets_you_create_a_dynamic/"> <img src="https://external-preview.redd.it/o6PaaTH7-jsQRUEz27PwB5vk7yDO9KoV8gWAt8fcmLU.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=aab3a04747947e3ce6a230791cb3957c579a8dd9" alt="GitHub template that lets you create a dynamic GitHub Page containing all the RSS/Atom articles you follow, updated every hour (See readme for details)" title="GitHub template that lets you create a dynamic GitHub Page containing all the RSS/Atom articles you follow, updated every hour (See readme for details)" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/exaroth"> /u/exaroth </a> <br/> <span><a href="https://github.com/exaroth/liveboat-github-runner">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlzthk/github_template_that_lets_you_create_a_dynamic/">[comments]</a></span> </td></tr></table>

## Introducing RepoFlow: Free Self-Hosted Package Management Made Simple
 - [https://www.reddit.com/r/selfhosted/comments/1hlz3c7/introducing_repoflow_free_selfhosted_package](https://www.reddit.com/r/selfhosted/comments/1hlz3c7/introducing_repoflow_free_selfhosted_package)
 - RSS feed: $source
 - date published: 2024-12-25T11:27:19+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hlz3c7/introducing_repoflow_free_selfhosted_package/"> <img src="https://b.thumbs.redditmedia.com/5ZMCj1pMhEILJdrMg7mfh_xNbUftn--MC8LPBw95eeE.jpg" alt="Introducing RepoFlow: Free Self-Hosted Package Management Made Simple" title="Introducing RepoFlow: Free Self-Hosted Package Management Made Simple" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><strong>Website</strong>: <a href="https://www.repoflow.io">RepoFlow</a><br/> Docs: <a href="https://docs.repoflow.io">RepoFlow Docs</a></p> <p>Hello everyone </p> <p>I’m excited to officially introduce RepoFlow, a user-friendly and powerful self-hosted package management platform designed to simplify repository management and package hosting. </p> <p>About a month ago, I posted on this subreddit <a href="https://www.reddit.com/r/selfhosted/comments/1gyz7hs/how_would_you_limit_free_selfhosting_for">link</a>, asking for advice on how to handle free self-hosting for pe

## Sharint igpu between windows vm and jellyfin lxc in proxmox
 - [https://www.reddit.com/r/selfhosted/comments/1hlyuid/sharint_igpu_between_windows_vm_and_jellyfin_lxc](https://www.reddit.com/r/selfhosted/comments/1hlyuid/sharint_igpu_between_windows_vm_and_jellyfin_lxc)
 - RSS feed: $source
 - date published: 2024-12-25T11:07:51+00:00

<!-- SC_OFF --><div class="md"><p>Is it possible? I already have the GPU being passthrough to windows vm, but would like my jellyin lxc to use it as well, but not sure if sharing is possible.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/angelflames1337"> /u/angelflames1337 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlyuid/sharint_igpu_between_windows_vm_and_jellyfin_lxc/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlyuid/sharint_igpu_between_windows_vm_and_jellyfin_lxc/">[comments]</a></span>

## Nginx explain to use vaultwarden.
 - [https://www.reddit.com/r/selfhosted/comments/1hlys98/nginx_explain_to_use_vaultwarden](https://www.reddit.com/r/selfhosted/comments/1hlys98/nginx_explain_to_use_vaultwarden)
 - RSS feed: $source
 - date published: 2024-12-25T11:03:00+00:00

<!-- SC_OFF --><div class="md"><p>I am not an expert so please understand..I am still learning. I have setup a modest homelab running a 2 node proxmox setup.I have a few lxcs and VMs running.I am looking at using vaultwarden but it requires nginx..I was looking at using duckdns as a free option.Can someone please explain the benefits of Nginx..</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FlanSwimming5118"> /u/FlanSwimming5118 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlys98/nginx_explain_to_use_vaultwarden/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlys98/nginx_explain_to_use_vaultwarden/">[comments]</a></span>

## What is your selfhosted discover in 2024?
 - [https://www.reddit.com/r/selfhosted/comments/1hlyjv3/what_is_your_selfhosted_discover_in_2024](https://www.reddit.com/r/selfhosted/comments/1hlyjv3/what_is_your_selfhosted_discover_in_2024)
 - RSS feed: $source
 - date published: 2024-12-25T10:44:45+00:00

<!-- SC_OFF --><div class="md"><p>Hello and Merry Christmas to everyone! </p> <p>The 2024 is ending..What self hosted tool you discover and loved during 2024? </p> <p>Maybe is there some new “software for life”? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Elemis89"> /u/Elemis89 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlyjv3/what_is_your_selfhosted_discover_in_2024/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlyjv3/what_is_your_selfhosted_discover_in_2024/">[comments]</a></span>

## Self hosted code server for collaboration
 - [https://www.reddit.com/r/selfhosted/comments/1hly981/self_hosted_code_server_for_collaboration](https://www.reddit.com/r/selfhosted/comments/1hly981/self_hosted_code_server_for_collaboration)
 - RSS feed: $source
 - date published: 2024-12-25T10:20:52+00:00

<!-- SC_OFF --><div class="md"><p>I looked online for options for running a code server similar to google collab. It would run Jupyter and similar and would allow people collaborating on programming or teaching each other. It would have a process similar to Overleaf or Google Docs: you see someone’s cursor and can both type and compile. </p> <p>There is JupyterHub, but it doesn’t seem to have been used much. There VSCode server with an extension for Live Code. There is also a docker container Code Server in Linuxserver.io that is alternative to vscode.</p> <p>Does anyone know the best option? </p> <p>Is it VsCode server? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/chaplin2"> /u/chaplin2 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hly981/self_hosted_code_server_for_collaboration/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hly981/self_hosted_code_server_for_collaboration/"

## asset server: what do I need?
 - [https://www.reddit.com/r/selfhosted/comments/1hly7vi/asset_server_what_do_i_need](https://www.reddit.com/r/selfhosted/comments/1hly7vi/asset_server_what_do_i_need)
 - RSS feed: $source
 - date published: 2024-12-25T10:17:47+00:00

<!-- SC_OFF --><div class="md"><p>hey</p> <p>i want to spin up a simple asset server so that my services can load background images etc from the server instead of having to upload various images to each and everyone</p> <p>a) am I overcomplocating things? probably yes, but does it have a downside?</p> <p>b) what software/service do I need to run to make the assets available? a Webserver? which one do you recommend for someone who hasn&#39;t worked with Webservers yet? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/IacovHall"> /u/IacovHall </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hly7vi/asset_server_what_do_i_need/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hly7vi/asset_server_what_do_i_need/">[comments]</a></span>

## Backup OMV for automatic provisionning
 - [https://www.reddit.com/r/selfhosted/comments/1hly6ts/backup_omv_for_automatic_provisionning](https://www.reddit.com/r/selfhosted/comments/1hly6ts/backup_omv_for_automatic_provisionning)
 - RSS feed: $source
 - date published: 2024-12-25T10:15:24+00:00

<!-- SC_OFF --><div class="md"><p>I have installed OMV a couple of weeks ago and start to populate it with shared folders, users, docker services, etc.</p> <p>I would like to create a backup of all of this that would enable re-deploying the whole infrastructure automatically in case of failure or migration to a different machine.</p> <p>I touched very briefly to ansible which enable idempotent setup. Is this something that you do ?</p> <p>For those who are interested about easy deployment of your OMV system, how do you do ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gabriel_jav"> /u/gabriel_jav </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hly6ts/backup_omv_for_automatic_provisionning/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hly6ts/backup_omv_for_automatic_provisionning/">[comments]</a></span>

## I'm considering between this AI prebuilt and Tinybox for coding? Need reviews
 - [https://www.reddit.com/r/selfhosted/comments/1hlxtmk/im_considering_between_this_ai_prebuilt_and](https://www.reddit.com/r/selfhosted/comments/1hlxtmk/im_considering_between_this_ai_prebuilt_and)
 - RSS feed: $source
 - date published: 2024-12-25T09:46:15+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hlxtmk/im_considering_between_this_ai_prebuilt_and/"> <img src="https://external-preview.redd.it/y7rRybt5gg1JX_27bVbOwzreW82fhiLiVEnWJJ_91oc.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=348a5f362a3874b7284e9746684ae64ba611dfab" alt="I'm considering between this AI prebuilt and Tinybox for coding? Need reviews" title="I'm considering between this AI prebuilt and Tinybox for coding? Need reviews" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/truongtongquanghuy"> /u/truongtongquanghuy </a> <br/> <span><a href="https://www.autonomous.ai/anon-ai/anon-ai-on-premise">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlxtmk/im_considering_between_this_ai_prebuilt_and/">[comments]</a></span> </td></tr></table>

## Drop has dropped: Beta Release!
 - [https://www.reddit.com/r/selfhosted/comments/1hlx7i5/drop_has_dropped_beta_release](https://www.reddit.com/r/selfhosted/comments/1hlx7i5/drop_has_dropped_beta_release)
 - RSS feed: $source
 - date published: 2024-12-25T08:56:26+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hlx7i5/drop_has_dropped_beta_release/"> <img src="https://b.thumbs.redditmedia.com/1-EOkWz75BY3dpB1CKLaTjkmELNtiAiNfo-MSHcf74k.jpg" alt=" Drop has dropped: Beta Release!" title=" Drop has dropped: Beta Release!" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>(now we all know why I picked that name lmao)</p> <p>I&#39;m the lead developer, and we&#39;re so excited to present Drop, the game distribution platform, as an open beta!</p> <p>What is Drop? Drop is an open-source, self-hosted game distribution platform. It&#39;s designed offer all the same features of a platform like Steam.</p> <p>Currently things are in very early stages, but we something that we&#39;re happy to say at least <em>works</em>. As this is a first release, I&#39;m expecting a lot of bugs and issues to come up.</p> <p>Specifically, here&#39;s what you can expect from this beta release:</p> <ul> <li>Drop instance library management, includi

## Has anyone used Snapcast as a Sonos replacement? Curious if people's experiences with this are generally positive.
 - [https://www.reddit.com/r/selfhosted/comments/1hlwwfj/has_anyone_used_snapcast_as_a_sonos_replacement](https://www.reddit.com/r/selfhosted/comments/1hlwwfj/has_anyone_used_snapcast_as_a_sonos_replacement)
 - RSS feed: $source
 - date published: 2024-12-25T08:30:27+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hlwwfj/has_anyone_used_snapcast_as_a_sonos_replacement/"> <img src="https://external-preview.redd.it/5_Ptkxdh48ibLcyRuoNac4pMD6RixnL2SeL_Pa7kldM.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=c3280bae334c40e8e4d51aa907895c796987e798" alt="Has anyone used Snapcast as a Sonos replacement? Curious if people's experiences with this are generally positive." title="Has anyone used Snapcast as a Sonos replacement? Curious if people's experiences with this are generally positive." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/notabot-i-promise"> /u/notabot-i-promise </a> <br/> <span><a href="https://github.com/badaix/snapcast">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlwwfj/has_anyone_used_snapcast_as_a_sonos_replacement/">[comments]</a></span> </td></tr></table>

## PdfDing - Now with editing functionalities
 - [https://www.reddit.com/r/selfhosted/comments/1hlwsti/pdfding_now_with_editing_functionalities](https://www.reddit.com/r/selfhosted/comments/1hlwsti/pdfding_now_with_editing_functionalities)
 - RSS feed: $source
 - date published: 2024-12-25T08:22:04+00:00

<!-- SC_OFF --><div class="md"><p>Hi <a href="/r/selfhosted">r/selfhosted</a>,</p> <p>I am the developer of PdfDing. As this feature was requested quite often I wanted to inform you that it is now possible to edit PDFs by adding annotations, highlighting and drawings. You can find the repo <a href="https://github.com/mrmn2/PdfDing">here</a>.</p> <p>I also got the feedback that organizing PDFs with simple tags does not work for many people. It is now possible to organize PDFs with multi-level tags. I hope this will improve the user experience.</p> <p>If you like PdfDing I would be really happy over a star on <a href="https://github.com/mrmn2/PdfDing">GitHub</a>. As the project is open source, if anyone wants to contribute you are welcome to do so!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mindless-View-3071"> /u/Mindless-View-3071 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlwsti/pdfding_now_with_editing_functio

## VPS Reverse Proxy vs Cloudflare
 - [https://www.reddit.com/r/selfhosted/comments/1hlvuf5/vps_reverse_proxy_vs_cloudflare](https://www.reddit.com/r/selfhosted/comments/1hlvuf5/vps_reverse_proxy_vs_cloudflare)
 - RSS feed: $source
 - date published: 2024-12-25T07:06:07+00:00

<!-- SC_OFF --><div class="md"><p>Let me start by saying I have been using a VPS for 5 years as a reverse proxy. I am looking into cloudflared tunnels. I can&#39;t find information on whether the tunnel cloudflare uses is encrypted. I would like to hide the traffic from my ISP. I do not care that cloudflare would see it. I have seen I need a origin cert but I am not sure at all how to implement it.</p> <p>My lab is as this. A bunch of VMs, each vm is tunneled to the vps by wireguard and vps uses ssl cert for https.</p> <p>I would like to basically have an encrypted tunnel between the origin server and cloudflare. But setting up cloudflare I am can figure out how to tell if the tunnel is encrypted. If not how to do achieve encryption so I can hid prying eyes.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Rich_Explanation_675"> /u/Rich_Explanation_675 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlvuf5/vps_reverse_prox

## Introducing NeatShift: Effortless File Organization with Symbolic Link Support
 - [https://www.reddit.com/r/selfhosted/comments/1hluml1/introducing_neatshift_effortless_file](https://www.reddit.com/r/selfhosted/comments/1hluml1/introducing_neatshift_effortless_file)
 - RSS feed: $source
 - date published: 2024-12-25T05:35:05+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hluml1/introducing_neatshift_effortless_file/"> <img src="https://external-preview.redd.it/GblJi-XOLVx4n1Wy8FHnl0Zv_W9Ex3hL9MYY-rSBfhU.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=458e73766e4d8fa21dc630c50ddc579ded2cf7e1" alt="Introducing NeatShift: Effortless File Organization with Symbolic Link Support" title="Introducing NeatShift: Effortless File Organization with Symbolic Link Support" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Project - NeatShift</p> <p>🚀 Overview</p> <p>NeatShift is a cutting-edge application designed to revolutionize file organization on Windows by leveraging the power of symbolic links. It empowers users to effortlessly relocate files and folders to more organized locations while ensuring their original accessibility remains intact—no broken apps, no disruptions.</p> <p>🎯 Key Features</p> <ol> <li><p>Seamless File Relocation: Move files or folders anywhere without breaking r

## Best self-hosted 2FA server
 - [https://www.reddit.com/r/selfhosted/comments/1hlts6m/best_selfhosted_2fa_server](https://www.reddit.com/r/selfhosted/comments/1hlts6m/best_selfhosted_2fa_server)
 - RSS feed: $source
 - date published: 2024-12-25T04:36:17+00:00

<!-- SC_OFF --><div class="md"><p>Hello <a href="/r/selfhosted">/r/selfhosted</a> </p> <p>I&#39;d like to know what is the recommended solution to have an encrypted at rest, self-hosted 2FA server which is usable from both phones and computers.</p> <p>In a few words, a Google Authenticator alternative where I can bring my own server.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ambroiseur"> /u/Ambroiseur </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlts6m/best_selfhosted_2fa_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlts6m/best_selfhosted_2fa_server/">[comments]</a></span>

## What's up with Bitnami's docker images?
 - [https://www.reddit.com/r/selfhosted/comments/1hlt4zr/whats_up_with_bitnamis_docker_images](https://www.reddit.com/r/selfhosted/comments/1hlt4zr/whats_up_with_bitnamis_docker_images)
 - RSS feed: $source
 - date published: 2024-12-25T03:50:33+00:00

<!-- SC_OFF --><div class="md"><p>I have seen a few projects where they use Bitnami&#39;s docker images when an official one already exists. What incentive does a project maintainer have to use Bitnami&#39;s images?</p> <p>For example, the MongoDB image used in RocketChat&#39;s compose file is <a href="http://docker.io/bitnami/mongodb">docker.io/bitnami/mongodb</a> and I&#39;m wondering why. I mean why intentionally use something that has telemetry going to someone else? Does Bitnami pay them something?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kudikarasavasa"> /u/kudikarasavasa </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlt4zr/whats_up_with_bitnamis_docker_images/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlt4zr/whats_up_with_bitnamis_docker_images/">[comments]</a></span>

## What's the choice of Slack clones for a self-hoster?
 - [https://www.reddit.com/r/selfhosted/comments/1hlso6t/whats_the_choice_of_slack_clones_for_a_selfhoster](https://www.reddit.com/r/selfhosted/comments/1hlso6t/whats_the_choice_of_slack_clones_for_a_selfhoster)
 - RSS feed: $source
 - date published: 2024-12-25T03:17:39+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m an independent software developer and contractor, so I need to communicate with clients, and sometimes freelancers. Having a chat system makes everything convenient. I have been using Mattermost and it was working fine until now but now I have a better understanding of what I need. One reason why I like Mattermost is that it already integrates well with Gitlab, so that&#39;s great.</p> <p>Sometimes a customer might have a preference for their own chat system but I still want to stay in Mattermost itself. Recently someone added to me to their Microsoft Teams chat and I checked if a Teams integration is available, and it is. However, the license of the plugin says it can only be used with Mattermost Enterprise, so this was offputting.</p> <p>Since then I was considering about writing a custom plugin and even wondered whether something else exists with similar features and integrations, so I have been exploring.</p> <p>Rockat Chat and Zulip also

## Bare Metal or Proxmox for homelab?
 - [https://www.reddit.com/r/selfhosted/comments/1hlpx4b/bare_metal_or_proxmox_for_homelab](https://www.reddit.com/r/selfhosted/comments/1hlpx4b/bare_metal_or_proxmox_for_homelab)
 - RSS feed: $source
 - date published: 2024-12-25T00:17:45+00:00

<!-- SC_OFF --><div class="md"><p>I have been really newbie to self hosting. At present I am running ubuntu 24.02 (bare metal) on my home server. I am using docker compose to run all my services as a container. But I really wanna switch to a more highly available path. Maybe soon in a month once I know exactly what I want to do??</p> <p>Although, being a newbie I have genuine doubts over shall I go the Proxmox way? And also I am confused about are we supposed to have Proxmox installed on the main host and then create vms on each and then use docker to run the services on them? So a single host machine rocking proxmox.. and maybe we have two vms running on top of it with one maybe having all media stuff and other having productivity ones?</p> <p>And what to do in case of having multiple machines? K3s? And in that case how are we supposed to keep the OS? </p> <p>I know k3s might be an overkill, but I wanna try all this stuff just for learning purpose, and when once done I would rollbac

## Can't seem to get Wireguard working
 - [https://www.reddit.com/r/selfhosted/comments/1hlpr15/cant_seem_to_get_wireguard_working](https://www.reddit.com/r/selfhosted/comments/1hlpr15/cant_seem_to_get_wireguard_working)
 - RSS feed: $source
 - date published: 2024-12-25T00:07:11+00:00

<!-- SC_OFF --><div class="md"><p>Just got my first R pi for my home server (Pi 5 8gb, ethernet, 240gb ssd)</p> <p>Got almost everything working and able to login using web interfaces. (pihole, home Assistant)</p> <p>I&#39;m a noob here, and I have no idea where I&#39;m wrong</p> <p>Installed using the Pivpn command<br/> Forwarded port 51820 UDP on my router<br/> Pi is on a static ip outside the DHCP Range<br/> I&#39;m able to add clients, but i get no internet and i cant log into the web interface.</p> <p>any help would be greatly appreciated</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/spranks21"> /u/spranks21 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlpr15/cant_seem_to_get_wireguard_working/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlpr15/cant_seem_to_get_wireguard_working/">[comments]</a></span>

