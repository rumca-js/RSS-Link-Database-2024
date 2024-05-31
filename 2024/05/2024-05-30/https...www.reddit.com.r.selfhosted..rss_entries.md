# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Tailscale and DNS?
 - [https://www.reddit.com/r/selfhosted/comments/1d4gq27/tailscale_and_dns](https://www.reddit.com/r/selfhosted/comments/1d4gq27/tailscale_and_dns)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T22:52:26+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, this ones been making my head hurt so I figured I'd ask. I have a domain name that I purchased thru namecheap. I've been dabbling with homelab stuff and self hosting some services (Examples: Kavita, Jellyfin, Glances, etc.) and have been mostly accessing everything via Tailscale so nothing is internet exposed. Playing around with the DNS records, I was able to attach my domain to the Tailscale IP of the machine I have acting as my server with an A record and I can navigate to different services in a web browser by typing &quot;my-domain.com:port&quot;. However, I am learning that the more services I add, the more I don't really want to memorize all the different ports I have in use. (Not that I don't but you know what I mean.) I for the life of me cannot figure out how to get subdomains working. For instance, how could i make something like &quot;jellyfin.my-domain.com&quot; to actually point to Jellyfin while within my Tailscale network?</p

## Self hosted D&D character manager
 - [https://www.reddit.com/r/selfhosted/comments/1d4gmia/self_hosted_dd_character_manager](https://www.reddit.com/r/selfhosted/comments/1d4gmia/self_hosted_dd_character_manager)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T22:47:49+00:00

<!-- SC_OFF --><div class="md"><p>Anyone found a good self hosted character manager for Dungeons and Dragons 5e?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/geniuscube"> /u/geniuscube </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d4gmia/self_hosted_dd_character_manager/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d4gmia/self_hosted_dd_character_manager/">[comments]</a></span>

## Is a public RTSP stream a stupid idea?
 - [https://www.reddit.com/r/selfhosted/comments/1d4gdn5/is_a_public_rtsp_stream_a_stupid_idea](https://www.reddit.com/r/selfhosted/comments/1d4gdn5/is_a_public_rtsp_stream_a_stupid_idea)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T22:36:35+00:00

<!-- SC_OFF --><div class="md"><p>I have a webcam connected to my server. It doesnt show anything I wouldn't wanna see anyone random. I have mediamtx setup to stream the cam using FFMPEG and RTSP through port 8554 on my LAN.</p> <p>Earlier this day i wanted to share this stream with some friends who don't (yet, or ever - because its annoying to THEM - not to me) have access to my wireguard VPN. This got me thinking if it would be a bad idea to open port 8554 to the WAN on my router for any reasons besides anyone viewing the stream who it wasnt inteded for (as im not worried about the latter).</p> <p>Are there exploits which could gain access to my server besides the RTSP stream if I'd open up port 8554 to WAN on my router? Or would opening port 8554 be rather safe like opening 25565 for minecraft? I dont't think my minecraft server did ever get hacked within the year its been running. I witnessed occasional connection attempts by non whitelisted persons but nothing else.</p> <p>TLDR: 

## Uptime monitor with warning state
 - [https://www.reddit.com/r/selfhosted/comments/1d4f73v/uptime_monitor_with_warning_state](https://www.reddit.com/r/selfhosted/comments/1d4f73v/uptime_monitor_with_warning_state)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T21:40:15+00:00

<!-- SC_OFF --><div class="md"><p>Is there an uptime monitor (self hosted or not) that supports more than two states? I'm looking for something that can show when a service is up but still needs my attention.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/vkapadia"> /u/vkapadia </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d4f73v/uptime_monitor_with_warning_state/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d4f73v/uptime_monitor_with_warning_state/">[comments]</a></span>

## DSLite network reverse VPN with reverse proxy sometimes works, sometimes not
 - [https://www.reddit.com/r/selfhosted/comments/1d4d2wa/dslite_network_reverse_vpn_with_reverse_proxy](https://www.reddit.com/r/selfhosted/comments/1d4d2wa/dslite_network_reverse_vpn_with_reverse_proxy)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T20:04:51+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys,</p> <p>So I switched my internet provider and instead of a dualstack with a dynamic ipv4 I only have a DS lite connection with a ipv6 now. Already before that I switched to a setup, where I have a external VPS server with a fixed IP running a reverse VPN with wireguard to my home network. This VPN forwards all the traffic to my local reverse proxy based on traefik. Traefik routes the requests to all my selfhosted apps running on my proxmox (jellyfin, immich, home assistant etc.). The reverse VPN based on wireguard runs on a alpine LXC container and traefik runs in a alpine LXC within docker. So far so good. This worked great with my dualstack / public ipv4 connection. With the DSLite connection it's not that easy</p> <p>All the subdomains I use for my applications point via an A entry to the ipv4 of the VPS and also via an AAAA to the ipv6 of the VPS. I forward all the ipv6 traffic to ipv4. </p> <p>Here is my WG config on the VPS:</p> <p>```<

## NAS Build Help
 - [https://www.reddit.com/r/selfhosted/comments/1d4cwi2/nas_build_help](https://www.reddit.com/r/selfhosted/comments/1d4cwi2/nas_build_help)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T19:57:35+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1d4cwi2/nas_build_help/"> <img alt="NAS Build Help" src="https://preview.redd.it/olcscxo2dm3d1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=53432a7cb5477fad2036d6839fa38c26dadf0fe8" title="NAS Build Help" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Looking to see where I can cut some costs on this build, and any input what I should change. All parts are in NZD from PBTech for reference. I'm thinking of running TrueNAS, and I'll run my Plex + *arr media stack directly on it with the Docker plugin.</p> <p>Is this super overkill?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Aggressive-Fan6460"> /u/Aggressive-Fan6460 </a> <br /> <span><a href="https://i.redd.it/olcscxo2dm3d1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d4cwi2/nas_build_help/">[comments]</a></span> </td></tr></table>

## How to best set up traefik for 40+ apps accross 3 VMs?
 - [https://www.reddit.com/r/selfhosted/comments/1d4cfgm/how_to_best_set_up_traefik_for_40_apps_accross_3](https://www.reddit.com/r/selfhosted/comments/1d4cfgm/how_to_best_set_up_traefik_for_40_apps_accross_3)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T19:36:31+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone. I am currently in the process of switching the reverse proxy in my home lab from nginx proxy manager to traefik. I have traefik fully up and running, I just need to convert all my container apps over to use the new scheme. Currently I am creating a new router and service for each app, then calling the same middleware in each router. It is currently working for me, it's just a bit of a hassle and has caused my config file to get rather lengthy. Does anyone have a better way to do this? Is it possible to attach multiple services to the same router?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Alucard2051"> /u/Alucard2051 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d4cfgm/how_to_best_set_up_traefik_for_40_apps_accross_3/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d4cfgm/how_to_best_set_up_traefik_for_40_apps_accross_3/">[comment

## Swiftwave V2 : Simple Lightweight Open Source solution to deploy and manage your applications on any VPS
 - [https://www.reddit.com/r/selfhosted/comments/1d4c6l4/swiftwave_v2_simple_lightweight_open_source](https://www.reddit.com/r/selfhosted/comments/1d4c6l4/swiftwave_v2_simple_lightweight_open_source)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T19:25:59+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1d4c6l4/swiftwave_v2_simple_lightweight_open_source/"> <img alt="Swiftwave V2 : Simple Lightweight Open Source solution to deploy and manage your applications on any VPS" src="https://a.thumbs.redditmedia.com/We68TlyeSbNl0B1nMOt9i4c5PL97-atMYWFF3z-WVf0.jpg" title="Swiftwave V2 : Simple Lightweight Open Source solution to deploy and manage your applications on any VPS" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/voie5r306m3d1.png?width=1920&amp;format=png&amp;auto=webp&amp;s=ff2699a40509cd01f8f8a2d3b9b51dbe4be0d0fb">https://preview.redd.it/voie5r306m3d1.png?width=1920&amp;format=png&amp;auto=webp&amp;s=ff2699a40509cd01f8f8a2d3b9b51dbe4be0d0fb</a></p> <p>Almost around 10mo ago, I have released beta version of Swiftwave in <a href="https://www.reddit.com/r/selfhosted/comments/15tn477/swiftwave_selfhosted_lightweight_paas_solution_to/">this post</a> . I got amazing responses and

## Cloudflare email routing + Brevo (sendinblue) for own domain email?
 - [https://www.reddit.com/r/selfhosted/comments/1d4bo4y/cloudflare_email_routing_brevo_sendinblue_for_own](https://www.reddit.com/r/selfhosted/comments/1d4bo4y/cloudflare_email_routing_brevo_sendinblue_for_own)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T19:04:09+00:00

<!-- SC_OFF --><div class="md"><p>Sad for me but yesterday I found <a href="https://skiff.com">https://skiff.com</a> ...sounds like a very good project, but the projects is dead now :(<br /> I am using the free zoho mail plan right now for my own domain email. But for me is better to have it directly in gmail (i know about the privacy, but I am still not ok to pay 10 eur per month to Proton :) )</p> <p>So is this option for cloudflare and sendinblue still OK and is it safe - is it possible to miss some emails somehow? Any chance emails send from sendinblue to be marked as spam?</p> <p>Thanks for your advices.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dika241"> /u/dika241 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d4bo4y/cloudflare_email_routing_brevo_sendinblue_for_own/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d4bo4y/cloudflare_email_routing_brevo_sendinblue_for_own/

## Why is Cozy Cloud not mentioned as an alternative to Nextcloud
 - [https://www.reddit.com/r/selfhosted/comments/1d4aq6f/why_is_cozy_cloud_not_mentioned_as_an_alternative](https://www.reddit.com/r/selfhosted/comments/1d4aq6f/why_is_cozy_cloud_not_mentioned_as_an_alternative)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T18:24:19+00:00

<!-- SC_OFF --><div class="md"><p>While I was researching alternatives to nextcloud I saw a few posts 4+ years old about using Cozy instead of Nextcloud after scrolling through a lot of SeaFile comments (what I use currently). It seems like a decent product if a bit sparse on documentation, so my question - why does nobody really mention it as an alternative, is there something I'm missing?</p> <p>I'm not associated with Cozy or any other projects mentioned above.</p> <p>EDIT: I did originally have to do some digging to find the site so it may be the obscurity of their selfhosted page -&gt; <a href="https://docs.cozy.io/en/tutorials/selfhosting/">https://docs.cozy.io/en/tutorials/selfhosting/</a> (their selfhosted guide)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Acid14"> /u/Acid14 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d4aq6f/why_is_cozy_cloud_not_mentioned_as_an_alternative/">[link]</a></span> &#32; <span>

## Self hosted pagespeed
 - [https://www.reddit.com/r/selfhosted/comments/1d49acg/self_hosted_pagespeed](https://www.reddit.com/r/selfhosted/comments/1d49acg/self_hosted_pagespeed)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T17:15:59+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>Does anyone know a good self hosted webpage tester? Something like <a href="http://gtmetrix.com">gtmetrix.com</a> or google pagespeed?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DutchTee86"> /u/DutchTee86 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d49acg/self_hosted_pagespeed/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d49acg/self_hosted_pagespeed/">[comments]</a></span>

## IPv6 Connectivity lost ?
 - [https://www.reddit.com/r/selfhosted/comments/1d498rc/ipv6_connectivity_lost](https://www.reddit.com/r/selfhosted/comments/1d498rc/ipv6_connectivity_lost)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T17:14:01+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1d498rc/ipv6_connectivity_lost/"> <img alt="IPv6 Connectivity lost ?" src="https://a.thumbs.redditmedia.com/yZEej9UKwWotp10qDndVcGlLgdLHSyEMivIoYdE5Da8.jpg" title="IPv6 Connectivity lost ?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>My ISP uses CGNAT for IPv4, but does give a /64 IPv6 address. I used this to access my selfhosted services outside my network through reverse proxy (Caddy), until recently all my services are suddenly not accessible outside my network.</p> <p>They are accessible inside my network through the reverse proxy (using Adguard DNS's custom mapping). </p> <p>I used some tools like <a href="https://port.tools/port-checker-ipv6/">https://port.tools/port-checker-ipv6/</a> to confirm portforwarding is working.</p> <p>I also tried traceroute in <a href="https://tools.keycdn.com/traceroute">https://tools.keycdn.com/traceroute</a></p> <p><a href="https://preview.redd.it/tnesp3nghl3d1.jpg?widt

## How to Monitor Intrusions and Docker Services?
 - [https://www.reddit.com/r/selfhosted/comments/1d494hh/how_to_monitor_intrusions_and_docker_services](https://www.reddit.com/r/selfhosted/comments/1d494hh/how_to_monitor_intrusions_and_docker_services)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T17:08:51+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I need some help with setting up monitoring for intrusions and my Docker services to check if my system has been compromised. Currently, I feel &quot;blind&quot; in this regard. Here's my setup:</p> <p>I have a mini-PC inside my house running a lot of Docker containers (Plex, Jellyseerr, Jellyfin, etc.), fail2ban, Tailscale, and Syncthing. To avoid exposing it directly, I use a VPS that is exposed with a Docker container NPM (ports 80 and 443) and communicates with my mini-PC via Wireguard. This VPS also has fail2ban, UFW (blocking everything IN and OUT except Docker; I couldn’t get the workaround to work, so I just expose personal containers with Wireguard’s IP), and NPM that listens for requests for my domain.</p> <p>The problem is, I don’t know how to look at the logs or what to look for.</p> <p>Is there a web interface that can help me monitor all of this? Any advice or recommendations would be greatly appreciated. Thanks!</p> 

## Issues when running Rclone to mount at boot
 - [https://www.reddit.com/r/selfhosted/comments/1d48sg8/issues_when_running_rclone_to_mount_at_boot](https://www.reddit.com/r/selfhosted/comments/1d48sg8/issues_when_running_rclone_to_mount_at_boot)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T16:54:31+00:00

<!-- SC_OFF --><div class="md"><p>I've been trying to get Rclone to mount at boot however I have been encountering some issues, I followed the guide from here (<a href="https://rclone.org/commands/rclone%5C_mount/">https://rclone.org/commands/rclone\_mount/</a>) under &quot;Rclone as Unix mount helper&quot;. I created a file in <code>/etc/systemd/system/mnt-data.mount</code>with the following contents:</p> <pre><code>[Unit] Description=Mount for /mnt/gringotts [Mount] Type=rclone What=gringotts: Where=/mnt/gringotts Options=rw,_netdev,allow_other,args2env,vfs-cache-mode=writes,config=/etc/rclone.conf,cache-dir=/var/rclone </code></pre> <p>After that I ran:</p> <p><code>sudo systemctl daemon-reload</code><br /> <code>sudo systemctl enable mnt-gringotts.mount --now</code></p> <p>after that it looks like my .mount script fails as I get the following in logs:</p> <pre><code>May 30 16:25:24 nimbus2000 sudo[2431]: ubuntu : TTY=pts/0 ; PWD=/mnt/gringotts ; USER=root ; COMMAND=/usr/bin/system

## Tried to setup my home media server for the first time. NOTHING FUCKING WORKS
 - [https://www.reddit.com/r/selfhosted/comments/1d48flz/tried_to_setup_my_home_media_server_for_the_first](https://www.reddit.com/r/selfhosted/comments/1d48flz/tried_to_setup_my_home_media_server_for_the_first)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T16:39:51+00:00

<!-- SC_OFF --><div class="md"><p>For years I've been seeing all the fuss on the internet about self hosted media servers and how good they are blah blah. </p> <p>I wanted to watch some movies on my tv and was tired of sticking usb drives into it. </p> <p>So this is how it turned out. </p> <ol> <li>Plex : </li> </ol> <p>Installed and setup. Only detected, 40% of the files. And no, there was no naming issues, it just told me that the files weren't there. </p> <p>When I tried to play whatever it could read, it was only able to play the most shittest file quality files like 720p and even in those the audio was messed up. Back in the days when I used to play videos in VLC, the dialogues were low and the action scenes were loud and Plex was doing the same thing, overall audio was low. When I played things locally on MPV, everything was perfect. So I uninstalled Plex. </p> <ol> <li>Jellyfin</li> </ol> <p>Hey maybe Plex wasn't for me. Let's try Jellyfin. Successfully installed, started the s

## Is it bad practice to manually set my DNS server on devices and leave the router as default?
 - [https://www.reddit.com/r/selfhosted/comments/1d477mi/is_it_bad_practice_to_manually_set_my_dns_server](https://www.reddit.com/r/selfhosted/comments/1d477mi/is_it_bad_practice_to_manually_set_my_dns_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T15:48:42+00:00

<!-- SC_OFF --><div class="md"><p>I do not trust my DNS server to be up full time - although I plan it to be, It is a lot of responsibility, especially when I live with other people in a smart house. </p> <p>My idea was to manually set my devices with which I wanted ad blocking and to use internal hostnames manually to my DNS server, and otherwise leave it to my routers default - for all my lights etc. </p> <p>However, I mentioned this to a colleague at work, and he said it is bad practise. Is it really? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sammeeeeeee"> /u/Sammeeeeeee </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d477mi/is_it_bad_practice_to_manually_set_my_dns_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d477mi/is_it_bad_practice_to_manually_set_my_dns_server/">[comments]</a></span>

## How Important is Autonomy in Managing Your Backups and Recovery?
 - [https://www.reddit.com/r/selfhosted/comments/1d46qn1/how_important_is_autonomy_in_managing_your](https://www.reddit.com/r/selfhosted/comments/1d46qn1/how_important_is_autonomy_in_managing_your)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T15:28:02+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I'm curious about how important autonomy is for you when it comes to managing backups and recovery. Whether you're hosting a website, running an email server, or using a server as a backup repository, having the ability to manage your own backups and recoveries can be a game-changer.</p> <p>Here are a few points to consider:</p> <ul> <li><strong>Ease of Use</strong>: How user-friendly are the current backup and recovery solutions you use? Do you find them intuitive, or do they require a steep learning curve?</li> <li><strong>Reliability</strong>: How confident are you in the reliability of your current backup solutions? Have you faced any issues with data loss or recovery failures?</li> <li><strong>Self-Service Options</strong>: Do you have the ability to initiate backups and recoveries on your own, or do you need to rely on support teams? How important is it for you to have these self-service options?</li> <li><strong>Support Loa

## Cloudflare DDNS + Caddy + Netbird Setup on Proxmox VM
 - [https://www.reddit.com/r/selfhosted/comments/1d46kqu/cloudflare_ddns_caddy_netbird_setup_on_proxmox_vm](https://www.reddit.com/r/selfhosted/comments/1d46kqu/cloudflare_ddns_caddy_netbird_setup_on_proxmox_vm)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T15:21:06+00:00

<!-- SC_OFF --><div class="md"><p>Does anyone have these all 3 of these up and running on a Proxmox VM? And if so, could you show/explain your setup?</p> <p>I am very new to self hosting and I'm trying to get these 3 things working on my server. I currently have a mini pc running Proxmox and have Ubuntu Server VM running docker with Cloudflare DDNS, Caddy, and Netbird. I also bought a domain name on Cloudflare and I think my first issue is starting with my DNS setup there. I've seen a bunch of videos with people setting up Netbird and Caddy with Cloudflare on with Linode VMs, but those aren't quite helping with my current issues. First question is should my domain name point to my local IP of the VM or my public IP? If public, how do I connect it to the local VM?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CoachGomm"> /u/CoachGomm </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d46kqu/cloudflare_ddns_caddy_netbird_set

## Need help with a second user for filebrowser
 - [https://www.reddit.com/r/selfhosted/comments/1d468wg/need_help_with_a_second_user_for_filebrowser](https://www.reddit.com/r/selfhosted/comments/1d468wg/need_help_with_a_second_user_for_filebrowser)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T15:07:02+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone!</p> <p>I have been selfhosting for well over a year now and it has been for my benefit only throughout this time. I've had a friend ask me if there's a way for her to have some space on the server so that she can use it as a little bit of extra space to store her pictures/code/etc without installing another app.</p> <p>So, I created a user for her on filebrowser and limited her to only one folder. However, when she tries to upload anything, she gets the error 403 Forbidden. I have been looking through documentation for this and it seems like this is coming from permissions to write for the new user. I'm not sure how I can fix it though.</p> <p>I would appreciate some insight on how I can restructure my filebrowser so that if anyone asks in the future for access, it'll be super easy for me to create a new account and give them access?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/umairshariff23">

## Do free TLDs still exist?
 - [https://www.reddit.com/r/selfhosted/comments/1d43nga/do_free_tlds_still_exist](https://www.reddit.com/r/selfhosted/comments/1d43nga/do_free_tlds_still_exist)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T13:09:04+00:00

<!-- SC_OFF --><div class="md"><p>I know there used to be .tk domains for free but they don't work anymore. I don't care how bad the TLD is I just want to mess around with some domain stuff like custom emails and subdomains and other stuff</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/HistoricalAccess9501"> /u/HistoricalAccess9501 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d43nga/do_free_tlds_still_exist/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d43nga/do_free_tlds_still_exist/">[comments]</a></span>

## CloudFlare Extortion
 - [https://www.reddit.com/r/selfhosted/comments/1d42l5a/cloudflare_extortion](https://www.reddit.com/r/selfhosted/comments/1d42l5a/cloudflare_extortion)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T12:14:11+00:00

<!-- SC_OFF --><div class="md"><p>I know noone here is an entreprise user but seeing stuff like this still gives me some feelings and really makes me rethink if cloudflare is the way to go....</p> <p><a href="https://youtu.be/8zj7ei5Egk8">https://youtu.be/8zj7ei5Egk8</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Pro_Driftz"> /u/Pro_Driftz </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d42l5a/cloudflare_extortion/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d42l5a/cloudflare_extortion/">[comments]</a></span>

## Need cheap google photos and alternatives for photo video backups.
 - [https://www.reddit.com/r/selfhosted/comments/1d42ggi/need_cheap_google_photos_and_alternatives_for](https://www.reddit.com/r/selfhosted/comments/1d42ggi/need_cheap_google_photos_and_alternatives_for)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T12:07:22+00:00

<!-- SC_OFF --><div class="md"><p>Hi there everyone.</p> <p>I need a google photos alternatives for my personal photos and videos. I've around 700 Gib of Data.</p> <p>I want to store the more recent data on a platform where I can access it from any where and the old ones should be archived and moved to some storage place like I've heard people saying wasabi is a good option.</p> <p>I thought of hosting my own next cloud instance on a mini pc in my home for the local stuff then I though I should first ask in here to get some ideas from you guys.</p> <p>I'm a student and almost have no budget.</p> <p>what would you guys recommend? I just want my photos and videos to be saved and if in case I loose my phone I can back them up from there, The platform should be secure no data leaks. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/just-ans"> /u/just-ans </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d42ggi/need_cheap_google_

## Wifi network LAN access?
 - [https://www.reddit.com/r/selfhosted/comments/1d41onr/wifi_network_lan_access](https://www.reddit.com/r/selfhosted/comments/1d41onr/wifi_network_lan_access)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T11:23:15+00:00

<!-- SC_OFF --><div class="md"><p>What's up with phone WiFi network access.</p> <p>Somehow phones not fully connect to a WiFi network when the underlying internet connection is not available.</p> <p>In this situation I cannot even access local self hosted servers in my local network.</p> <p>Is there a solution or different approach for this?</p> <p>Cause when I bootup a laptop and plugin a lan cable I can access all locally.</p> <p>So why WiFi doesn't connect as in Lan only mode without internet access?</p> <p>It seems my phones prevent connecting if no internet is available?</p> <p>Isnt that weird?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Miserable-Stranger99"> /u/Miserable-Stranger99 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d41onr/wifi_network_lan_access/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d41onr/wifi_network_lan_access/">[comments]</a></span>

## Matrix & Cloudflare from privacy perspective
 - [https://www.reddit.com/r/selfhosted/comments/1d4171p/matrix_cloudflare_from_privacy_perspective](https://www.reddit.com/r/selfhosted/comments/1d4171p/matrix_cloudflare_from_privacy_perspective)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T10:52:42+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, </p> <p>I am thinking of selfhosting Matrix. I'm not interested on federation, I just want to use it for me and my family (5 people). To make this work I can either open 80 and 443 ports and using Nginx or using Cloudflare tunnels. </p> <p>Even though I've searched about it, I couldn't find a definite answer about the privacy implications when using Cloudflare tunnels and Matrix. Do the Matrix data go on CF tunnel unencrypted? Since I can't use my own SSL on tunnels, how can I be sure that the data can't be seen on Cloudflare side</p> <p>Thanks for your answers</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Substantial_Age_4138"> /u/Substantial_Age_4138 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d4171p/matrix_cloudflare_from_privacy_perspective/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d4171p/matrix_cloudflare_from_privacy

## Cockpit integration for LDAP (or other Central User Management Solution)
 - [https://www.reddit.com/r/selfhosted/comments/1d40jot/cockpit_integration_for_ldap_or_other_central](https://www.reddit.com/r/selfhosted/comments/1d40jot/cockpit_integration_for_ldap_or_other_central)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T10:10:02+00:00

<!-- SC_OFF --><div class="md"><p>I am currently looking for a solution for an upcoming project that allows me to manage a LDAP (or similar Server) via Cockpit, can be basic, pretty much the only function in need is to assign / remove users from groups.</p> <p>The planned setup is to have one controller node (VM) and several worker nodes (LXC), the worker nodes run only basic samba server with the permissions tied to groups inside the smb.conf (valid users= and write user=) To avoid needing to create each user account on each worker, the idea was to run some kind of user management like ldap on the controller and sync all the users / groups that way accross all the workers.</p> <p>This is working so far, the users are created on the controller and therefore available on all workers and i am automatically creating groups for new workers (inside ldap each one has two, one for read only, one for read write, like nodename-rw and nodename-ro) i can assign also assign users to those groups 

## Where's the line at on this?
 - [https://www.reddit.com/r/selfhosted/comments/1d4086s/wheres_the_line_at_on_this](https://www.reddit.com/r/selfhosted/comments/1d4086s/wheres_the_line_at_on_this)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T09:48:37+00:00

<!-- SC_OFF --><div class="md"><blockquote> <p>16TB WD Red - $316</p> <p>16TB WD External - $280</p> <p>Dock or proper internal rig - $???</p> </blockquote> <p>Where do we draw the line on, I need a drive for Jellyfin but I use a mini PC on a table, not a server rack?</p> <p>My strategy for the last ten years has been two externals and swapping one when the other dies, doing upgrades in size as I go along.</p> <p>I did a ZFS setup over USB a few years ago and got tons of errors and ruined a drive or two, and since then have just been rsyncing the drives and monitoring them individually.</p> <p>But would I save more in the long run if I went to something proper and did reds? Does it even matter? It's just me and five other loners watching movies and playing Valheim.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Vanilla_PuddinFudge"> /u/Vanilla_PuddinFudge </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d4086s/wheres_the_

## Vaultwarden behind Cloudflare tunnel MFA?
 - [https://www.reddit.com/r/selfhosted/comments/1d3zqac/vaultwarden_behind_cloudflare_tunnel_mfa](https://www.reddit.com/r/selfhosted/comments/1d3zqac/vaultwarden_behind_cloudflare_tunnel_mfa)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T09:12:41+00:00

<!-- SC_OFF --><div class="md"><p>I currently use cloudflare tunnels on my hosted services, and for services that only I should be able to access, I've used the included 2fa. However, this prevents the bitwarden app from being able to talk with the server as it can't complete these checks.</p> <p>I've used service tokens before to allow Lunasea to bypass 2fa, but that was only possible because I was able to pass custom headers. Is there a way to achieve this on the bitwarden app or some other secure way of bypassing 2fa?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Terroractly"> /u/Terroractly </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3zqac/vaultwarden_behind_cloudflare_tunnel_mfa/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3zqac/vaultwarden_behind_cloudflare_tunnel_mfa/">[comments]</a></span>

## Error when installing Paperless-ngx in an encrypted folder (via Container Manager on a Synology DS224+)
 - [https://www.reddit.com/r/selfhosted/comments/1d3ysuy/error_when_installing_paperlessngx_in_an](https://www.reddit.com/r/selfhosted/comments/1d3ysuy/error_when_installing_paperlessngx_in_an)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T08:03:10+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone!</p> <p>I started playing around with Paperless-ngx (on my Synology NAS DS224+ using Container Manager) and I find so far that it is a fantastic tool!</p> <p>I originally installed it in my usual docker folder where all my other docker apps are located (/volume1/docker/paperlessngx). I created a DSM user (called Paperless) specifically for that software. And it was working perfectly fine.</p> <p>Now that I am ready to start using it with important documents, I decided it would be better to set up everything in an encrypted shared folder. Here is what I did:</p> <ul> <li>created a specific encrypted folder for it (volume1/Paperless)</li> <li>gave read/write permission to the Paperless user</li> <li>changed directories in the docker-compose file (you can find it <a href="https://pastebin.com/qxgTSJi8">here</a>)</li> <li>succesfully built the project in volume1/Paperless</li> </ul> <p>That's where I run into an error from Redis (you can fi

## What to do with an ubuntu server.?
 - [https://www.reddit.com/r/selfhosted/comments/1d3yjhu/what_to_do_with_an_ubuntu_server](https://www.reddit.com/r/selfhosted/comments/1d3yjhu/what_to_do_with_an_ubuntu_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T07:43:51+00:00

<!-- SC_OFF --><div class="md"><p>I have an ubuntu 24.04 LTS server.</p> <p>What are some services I can self-host on it?</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OptimalDidko"> /u/OptimalDidko </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3yjhu/what_to_do_with_an_ubuntu_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3yjhu/what_to_do_with_an_ubuntu_server/">[comments]</a></span>

## Newsticker-Kisok Software
 - [https://www.reddit.com/r/selfhosted/comments/1d3xfat/newstickerkisok_software](https://www.reddit.com/r/selfhosted/comments/1d3xfat/newstickerkisok_software)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T06:23:05+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I am looking for a software to display news on a display.<br /> Is there any software I can point to a news-site or rss feed which will display the news feed (maybe with picture) in a fullscreen kiosk-mode and switch the news every x seconds? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/r4tze"> /u/r4tze </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3xfat/newstickerkisok_software/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3xfat/newstickerkisok_software/">[comments]</a></span>

## Self hosted voip / phone system
 - [https://www.reddit.com/r/selfhosted/comments/1d3xc8x/self_hosted_voip_phone_system](https://www.reddit.com/r/selfhosted/comments/1d3xc8x/self_hosted_voip_phone_system)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T06:17:15+00:00

<!-- SC_OFF --><div class="md"><p>I got my friends as my clients and they want a voip phone system and is highly encouraging me host my own to get my business running.</p> <p>So question is. Which opensource systems should I use?</p> <p>I have not dived in to the topic yet quick search of sub says look into Asterisk.</p> <p>And also ages ago I saw 3CX was opensource.</p> <p>So what do you recommend and where do it start?</p> <p>Once testing from home is is successful I can move it to cloud for redundancy and high availability </p> <p>I do know I need to purchase a block of numbers from provider.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MaxStartup"> /u/MaxStartup </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3xc8x/self_hosted_voip_phone_system/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3xc8x/self_hosted_voip_phone_system/">[comments]</a></span>

## Services behind Traefik cannot be reached when connected to VPN
 - [https://www.reddit.com/r/selfhosted/comments/1d3x4y9/services_behind_traefik_cannot_be_reached_when](https://www.reddit.com/r/selfhosted/comments/1d3x4y9/services_behind_traefik_cannot_be_reached_when)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T06:03:16+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I just bought myself a cheap domain yesterday and after solving all issues that came up while linking it to my network I could finally access my services from inside the network and outside of it.</p> <p>Now I wanted to check if VPN is working properly and tried to access some resource that is only whitelisted for internal IPs. It is loading forever and eventually timing out.</p> <p>My public IP of my phone is the same as the networks one, which shows that the VPN is working fine. Also I am also able to access everything when using IPs, which tells me I am able to access resources.</p> <p>It cannot be a firewall rule (using OPNsense btw), since I would not be able to access resources through IP too in that case.</p> <p>Could this be related to NAT? Keep in mind it works when accessing resources from inside the network itself, just not when using the VPN</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddi

## Best way to migrate Debian 11 to another Debian 11?
 - [https://www.reddit.com/r/selfhosted/comments/1d3vy8f/best_way_to_migrate_debian_11_to_another_debian_11](https://www.reddit.com/r/selfhosted/comments/1d3vy8f/best_way_to_migrate_debian_11_to_another_debian_11)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T04:45:41+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I want to migrate my Debian 11 server to another server with same OS or in Recovery mode.</p> <p>There are certain users and ports that exist on the server that are under utilization, I want the configuration to remain intact.</p> <p>I can boot server to recovery mode. There is about 1-1.5TB of data.</p> <p>In Windows, I just use Veeam Windows Agent for Backup and it creates kind of a snapshot that when I move to the new server, I transfer and install the software again and then it extracts the files and configuration on a new drive. Then I can boot into it and delete the original windows that I used to restore the snapshot using the backup.</p> <p>Is there anything similar for Debian?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sonuyosrox"> /u/sonuyosrox </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3vy8f/best_way_to_migrate_debian_11_to_another_debian_11/">[link]</a

## Amberpro vs Nextcloud
 - [https://www.reddit.com/r/selfhosted/comments/1d3v306/amberpro_vs_nextcloud](https://www.reddit.com/r/selfhosted/comments/1d3v306/amberpro_vs_nextcloud)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T03:55:15+00:00

<!-- SC_OFF --><div class="md"><p>I am currently using nextcloud on old laptop. intel dual core with 8 GB RAM and SATA SSD. Happy with setup, as I have own domain too and can access data anywhere. I don’t have backup for the hard disk and was evaluating options with RAID1.</p> <p>During evaluation came up with this device which is practically selfhosting storage similar to nextcloud with AI support for images. it also allows to use docker for apps like nextcloud, wordpress, home assistant, plex… within the device . And It already supports raid 1.</p> <p>What are your thoughts on using this device where purchase of device is one time cost (250-550$) and no subscription that follow. But then get all benefits of self hosting. Hoping they handle selfhosting more professionally than I do. Are there more cheaper alternatives than this?</p> <p>What are ur thoughts on security and privacy of this device and their service? </p> <p>And i could probably repurpose old lappy for selfhosting other 

## How do I access my 192.168.xx.xxx through DNS internally without port forward ?
 - [https://www.reddit.com/r/selfhosted/comments/1d3uur2/how_do_i_access_my_192168xxxxx_through_dns](https://www.reddit.com/r/selfhosted/comments/1d3uur2/how_do_i_access_my_192168xxxxx_through_dns)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T03:41:57+00:00

<!-- SC_OFF --><div class="md"><p>I have not port forwarded and I have a number of services running on local host like localhost:192.168.xx.xxx so. Instead of port forwarding, I would like to have encrypted certificates with a DNS for all my internally run servers without any port forwarding or exposing my network to the internet. Is this doable?</p> <p>If yes, can someone point me to a guide YT/blog/article since I’m a noob?</p> <p>PS. I did use the search on the sub and did get multiple hits but I find those responses too advanced to my knowledge. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Michaelscarn69-"> /u/Michaelscarn69- </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3uur2/how_do_i_access_my_192168xxxxx_through_dns/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3uur2/how_do_i_access_my_192168xxxxx_through_dns/">[comments]</a></span>

## Ping reducing services - Is it possible to host your own?
 - [https://www.reddit.com/r/selfhosted/comments/1d3ut9e/ping_reducing_services_is_it_possible_to_host](https://www.reddit.com/r/selfhosted/comments/1d3ut9e/ping_reducing_services_is_it_possible_to_host)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T03:39:30+00:00

<!-- SC_OFF --><div class="md"><p>Here are a couple examples of ping reducing services<br /> <a href="https://www.exitlag.com/">https://www.exitlag.com/</a><br /> <a href="https://www.gearupbooster.com/support/how-does-it-work.html">https://www.gearupbooster.com/support/how-does-it-work.html</a></p> <p>Here is a rundown of how these services work, is there any opensource software to do this?</p> <p>&quot;Simply put, GearUP Game Booster avoids heavy-traffic routes and re-routes to a dedicated pathway.</p> <p>Imagine taking a helicopter to work instead of your daily commute -- the former is undoubtedly more efficient and stress-free!</p> <p> </p> <p><strong>Why can GearUP Booster reduce ping and packet loss, while my internet service provider cannot?</strong></p> <p> First, it's important to understand that the majority of users of your internet service provider mainly use it for downloading files, browsing websites, watching videos, and listening to music. These activities require high

## Wordpress alternatives
 - [https://www.reddit.com/r/selfhosted/comments/1d3toh7/wordpress_alternatives](https://www.reddit.com/r/selfhosted/comments/1d3toh7/wordpress_alternatives)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T02:38:37+00:00

<!-- SC_OFF --><div class="md"><p>After many years of selfhosting multiple Wordpress sites, I am sick of it. Wordpress has become bloated, cannot do anything without installing tons of plugins (therefore depending on many different 3rd parties support and maintenance) and themes are a jungle of hacks and &quot;pro&quot; versions that hijack the backend UI and do not clean up their data when deleted.</p> <p>What's the best modern alternative considering:</p> <ul> <li>AMP only (or php flat file)</li> <li>no command line needed, full GUI</li> <li>want to make single page product websites</li> <li>want to make weblogs</li> </ul> <p>Any help appreciated! Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hotdogsoup-nl"> /u/hotdogsoup-nl </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3toh7/wordpress_alternatives/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3toh7/wordpress_altern

## Selfhosted vpn for remote server management
 - [https://www.reddit.com/r/selfhosted/comments/1d3tmol/selfhosted_vpn_for_remote_server_management](https://www.reddit.com/r/selfhosted/comments/1d3tmol/selfhosted_vpn_for_remote_server_management)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T02:36:02+00:00

<!-- SC_OFF --><div class="md"><p>I'm not too tech savvy when it comes to network stuff (or even systems, I can't understand half of the terms used in this sub for that matter). I'm trying to figure out what vpn to use to remotely access my server for management/rustdesk/password managers. </p> <p>I've seen Tailscale, Wireguard, OpenVPN and Netbird mentioned a few times but need advice on them (or other options) based on ease of setup/management, how resource efficient they are, etc. </p> <p>Also was wondering if I could use MullvadBrowser with any of them.</p> <p>Sorry for another post on selfhosted vpn but I just needed some more advice, thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TriggeredTrigz"> /u/TriggeredTrigz </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3tmol/selfhosted_vpn_for_remote_server_management/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/

## Selfhosted site rtsp.me CORS issue.
 - [https://www.reddit.com/r/selfhosted/comments/1d3t7tw/selfhosted_site_rtspme_cors_issue](https://www.reddit.com/r/selfhosted/comments/1d3t7tw/selfhosted_site_rtspme_cors_issue)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T02:15:03+00:00

<!-- SC_OFF --><div class="md"><p>I am hosting a website application to let folks view and start a model train layout. Here is the <a href="https://docs.google.com/drawings/d/1450nhVa3VrGLMXpOVpon9Oo38jmvI_ZNxjLbBEnINT4/edit?usp=sharing">high-level design.</a> Everything seems to work fine on mobile browsers, but on desktop browsers, I am getting an error saying the frame is blocked from <a href="http://rtsp.me">rtsp.me</a> ( my transcoder to HLS) due to a host from RTSP different domain source. Check it out here and tell me what I am doing wrong. <a href="https://jarrodandrews.com/run-the-train/">https://jarrodandrews.com/run-the-train/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Beep_boop_beep_boo"> /u/Beep_boop_beep_boo </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3t7tw/selfhosted_site_rtspme_cors_issue/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3t7tw/selfhosted_

## Need Ideas for RPI 4B 8GB
 - [https://www.reddit.com/r/selfhosted/comments/1d3t3c7/need_ideas_for_rpi_4b_8gb](https://www.reddit.com/r/selfhosted/comments/1d3t3c7/need_ideas_for_rpi_4b_8gb)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T02:08:51+00:00

<!-- SC_OFF --><div class="md"><p>Hi Guys. Please give some ideas and thoughts for the things I can selfhost on a Raspberry Pi 4B 8GB RAM variant. </p> <p>Things I need.</p> <ol> <li>Jellyfin / Emby</li> <li>Immich</li> <li>Pinhole</li> </ol> <p>Does all the above works efficiently on a RPI?</p> <p>Your thoughts and ideas all welcome.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sea_Dish_2821"> /u/Sea_Dish_2821 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3t3c7/need_ideas_for_rpi_4b_8gb/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3t3c7/need_ideas_for_rpi_4b_8gb/">[comments]</a></span>

## Self hosted experiments and commands manager
 - [https://www.reddit.com/r/selfhosted/comments/1d3rocl/self_hosted_experiments_and_commands_manager](https://www.reddit.com/r/selfhosted/comments/1d3rocl/self_hosted_experiments_and_commands_manager)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T00:56:58+00:00

<!-- SC_OFF --><div class="md"><p>Is there a self hosted application that can manage experiments. </p> <p>The use case is to queue several command and store and visualize the output logs easily.</p> <p>I know I can make a bash script or a docker container for this. But a web ui where I can just enter the commands to be run would be nice.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mateus2k2"> /u/mateus2k2 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3rocl/self_hosted_experiments_and_commands_manager/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3rocl/self_hosted_experiments_and_commands_manager/">[comments]</a></span>

## I need help finding a selfhosted dashboarding solution that shows the status of many different cron jobs that generate data.
 - [https://www.reddit.com/r/selfhosted/comments/1d3rlja/i_need_help_finding_a_selfhosted_dashboarding](https://www.reddit.com/r/selfhosted/comments/1d3rlja/i_need_help_finding_a_selfhosted_dashboarding)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T00:52:57+00:00

<!-- SC_OFF --><div class="md"><p>Being able to identify what ran and didn't run, possibly seeing a color coded indicator for &quot;freshness&quot; of data. Part of my problem is that I dont know the proper words to describe and identify what I am looking for. I am running many different daily, hourly scripts that scrape data and I would like to have a simple dashboard of some kind to identify at a glance what is working, what is broken, and whats FUBAR. Because all of the scripts are mine I have the ability to add special logs, rest hooks, or heartbeats to fit whatever readymade solution that exists.</p> <p>Thank you for your help. I am really getting into the selfhosted life style and moving away from building everything to be its own dedicated Debian headless vm. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/The_Flo0r_is_Lava"> /u/The_Flo0r_is_Lava </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3rlja/i_need_help_f

## Server Monitoring App - Neoserver
 - [https://www.reddit.com/r/selfhosted/comments/1d3qqtc/server_monitoring_app_neoserver](https://www.reddit.com/r/selfhosted/comments/1d3qqtc/server_monitoring_app_neoserver)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T00:09:53+00:00

<!-- SC_OFF --><div class="md"><p>Anyone have any experience of this app? Looks fantastic and is getting recent updates </p> <p><a href="https://apps.apple.com/gb/app/neoserver-docker-ssh-sftp/id6448362669">https://apps.apple.com/gb/app/neoserver-docker-ssh-sftp/id6448362669</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/its_me_ritch"> /u/its_me_ritch </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3qqtc/server_monitoring_app_neoserver/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3qqtc/server_monitoring_app_neoserver/">[comments]</a></span>

## Custom DNS server redirecting to a domain?
 - [https://www.reddit.com/r/selfhosted/comments/1d3qjsi/custom_dns_server_redirecting_to_a_domain](https://www.reddit.com/r/selfhosted/comments/1d3qjsi/custom_dns_server_redirecting_to_a_domain)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-30T00:00:38+00:00

<!-- SC_OFF --><div class="md"><p>I am looking to self host a DNS based shim of sorts that will redirect all requests to (for instance) <a href="http://www.site.com">www.site.com</a> to <a href="http://www.othersite.com">www.othersite.com</a>. I’ve got an old DVD player that connects to online services but no longer works, and I’m looking to play around with that but the only way I can think to do that would be via DNS. Is this possible and if so, how would I go about it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/GroupNebula563"> /u/GroupNebula563 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3qjsi/custom_dns_server_redirecting_to_a_domain/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d3qjsi/custom_dns_server_redirecting_to_a_domain/">[comments]</a></span>

