# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Offsite Backup Recomendation
 - [https://www.reddit.com/r/selfhosted/comments/1fn5wxg/offsite_backup_recomendation](https://www.reddit.com/r/selfhosted/comments/1fn5wxg/offsite_backup_recomendation)
 - RSS feed: $source
 - date published: 2024-09-22T22:49:03+00:00

<!-- SC_OFF --><div class="md"><p>At our primary home I am running an Unraid server and I want to figure out a simple way to do offsite backups at a second property. Primary home has 1gb fiber, Secondary location has 200mb fiber. Secondary location right now only has an older 6th gen i3 Intel NUC with 8gb ram running proxmox and is currently only running one VM, home assistant hassos.</p> <p>I am not in IT, just an enthusiast, so what is the easiest way to back up critical data at second location? Is there some docker with a gui you would recommend? Could I get away with a usb hard drive enclosure at second location since I don’t have a full blown NAS there?</p> <p>Any suggestions are greatly appreciated!</p> <p>Dan</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/seaverd"> /u/seaverd </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fn5wxg/offsite_backup_recomendation/">[link]</a></span> &#32; <span><a href="https://www.redd

## Help Choosing GPU & Storage for 24/7 Server Build
 - [https://www.reddit.com/r/selfhosted/comments/1fn3xd6/help_choosing_gpu_storage_for_247_server_build](https://www.reddit.com/r/selfhosted/comments/1fn3xd6/help_choosing_gpu_storage_for_247_server_build)
 - RSS feed: $source
 - date published: 2024-09-22T21:17:44+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, I’m building a server that will run 24/7, and need recommendations for a GPU and storage.</p> <p>GPU:<br/> - Needs to be power-efficient.<br/> - Must handle transcoding for media (Jellyfin/Plex).<br/> - Should also support running LLM models (Ollama, Phi, Mistral, Gemma).</p> <p>Storage:<br/> - Boot storage: 480GB (looking for something reliable, durable, and power-efficient).<br/> - App storage: 2TB (same criteria as boot storage).</p> <p>I’m also open to using refurbished parts if they fit the build.</p> <p>Current Build:<br/> CPU: AMD EPYC 7352<br/> Motherboard: Supermicro H12SSL-i<br/> RAM: Samsung DDR4 ECC RDIMM 32GB (4x, 128GB total)<br/> Boot Storage: ?? (2x)<br/> App Storage: ?? (2x)<br/> Data Storage: Seagate Exos X18 16TB HDD (4x)<br/> Power Supply: Seasonic PRIME TX-750 750W<br/> GPU: ??<br/> NIC: Intel X710-DA2<br/> HBA: LSI 9500-8i<br/> Case: Fractal Design Define 7 XL<br/> CPU Cooler: Noctua NH-U14S TR4-SP3<br/> Case Fans: 

## Anyone use lower end intel “H” motherboards?
 - [https://www.reddit.com/r/selfhosted/comments/1fn3iwz/anyone_use_lower_end_intel_h_motherboards](https://www.reddit.com/r/selfhosted/comments/1fn3iwz/anyone_use_lower_end_intel_h_motherboards)
 - RSS feed: $source
 - date published: 2024-09-22T21:00:08+00:00

<!-- SC_OFF --><div class="md"><p>I currently have a “Z” board that I’m hosting on. From my understanding, it has more PCIe lanes and tons more features overall. I’m wanting to go to an ITX board, but they are pretty expensive. Realistically I wouldn’t have more than 4-6 drives plugged in. Does anyone have any issues with PCIe availability or IOMMU with proxmox on these cheaper boards?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TXAGZ16"> /u/TXAGZ16 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fn3iwz/anyone_use_lower_end_intel_h_motherboards/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fn3iwz/anyone_use_lower_end_intel_h_motherboards/">[comments]</a></span>

## What is everyone using for EBook management
 - [https://www.reddit.com/r/selfhosted/comments/1fn2ev1/what_is_everyone_using_for_ebook_management](https://www.reddit.com/r/selfhosted/comments/1fn2ev1/what_is_everyone_using_for_ebook_management)
 - RSS feed: $source
 - date published: 2024-09-22T20:11:53+00:00

<!-- SC_OFF --><div class="md"><p>Hey Everyone,</p> <p>Just wondering what everyone is using for managing their EBooks. I have a bunch in PDF and I wanted to get a feel for what everyone is using. I am currently using Calibre on my Personal machine but I want something network accessible like Jellyfin but for eBooks. Any reccomendation/personal preferences?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RockisLife"> /u/RockisLife </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fn2ev1/what_is_everyone_using_for_ebook_management/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fn2ev1/what_is_everyone_using_for_ebook_management/">[comments]</a></span>

## Struggling to set up vps
 - [https://www.reddit.com/r/selfhosted/comments/1fn1nje/struggling_to_set_up_vps](https://www.reddit.com/r/selfhosted/comments/1fn1nje/struggling_to_set_up_vps)
 - RSS feed: $source
 - date published: 2024-09-22T19:39:30+00:00

<!-- SC_OFF --><div class="md"><p>Hey all. To preface this, I&#39;m a beginner, bought a hetzner vps to play around with, self host some apps and my websites. The initial plan was to harden the server by closing down ports, using tailscale and runtipi to host apps easily from a dashboard for my own network of devices. </p> <p>I would also like to integrate it with Caddy to host my own websites exposable to the internet. As far as I understand, both runtipi and Caddy have reverse proxies, and runtipi seems to do it with docker. My understanding is that reverse proxies are what I need to be able to host multiple servers in one computer?</p> <p>So I need the vps to be able to:</p> <ol> <li><p>Easily set up self hosted applications so I don&#39;t waste much time playing with configs.</p></li> <li><p>Host servers both inside the tailscale network and some exposed to the internet.</p></li> <li><p>Be secure as much as possible.</p></li> </ol> <p>So far, I&#39;ve managed to harden it by closi

## tailscale nfs synology help
 - [https://www.reddit.com/r/selfhosted/comments/1fn0z31/tailscale_nfs_synology_help](https://www.reddit.com/r/selfhosted/comments/1fn0z31/tailscale_nfs_synology_help)
 - RSS feed: $source
 - date published: 2024-09-22T19:10:03+00:00

<!-- SC_OFF --><div class="md"><p>I have tailscale running on my remote web host and also on my synology at home. I want to mount a filesystem via nfs from my synolog to my remote web host system via nfs.</p> <p>I configured my nfs on the synology with `*` as the client IP and all works well. I want to lock it down some but when I tried to configure it with actual IP of the remote host, or tailscale ip, or synology IP, or all 3 with and without the subnet, I am getting permission denied.</p> <p>I looked at the logs and `showmount -a` from my synology when the filesystem was mounted and it showed that the folder was mounted via the synology&#39;s IP address</p> <p>What should be set for the client ip instead of `*` ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jlim0930"> /u/jlim0930 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fn0z31/tailscale_nfs_synology_help/">[link]</a></span> &#32; <span><a href="https://www.red

## auto-mcs v2.2.1 - Telepath, Docker, and headless
 - [https://www.reddit.com/r/selfhosted/comments/1fn0fq2/automcs_v221_telepath_docker_and_headless](https://www.reddit.com/r/selfhosted/comments/1fn0fq2/automcs_v221_telepath_docker_and_headless)
 - RSS feed: $source
 - date published: 2024-09-22T18:46:56+00:00

<!-- SC_OFF --><div class="md"><h1>Welcome to auto-mcs v2.2.1!</h1> <p>Hello there, I am the developer of auto-mcs and wish to share my Minecraft server manager with the self-hosted community once again! I want to take a moment to thank everyone for the wealth of support on my initial post - I&#39;m extremely grateful for both the love and criticism!</p> <p>If you haven&#39;t seen the original post, here&#39;s a brief summary of our vision:</p> <p>auto-mcs provides a simple and easy-to-digest experience for those who want to play Minecraft with their friends without the hassle of server installation &amp; maintenance.</p> <h1>Some notable features include:</h1> <ul> <li>Create/import any Paper, Fabric, Forge, CraftBukkit, Spigot, or Vanilla server in <a href="https://www.auto-mcs.com/guides/getting-started">less than a minute</a></li> <li>Install most modpacks in 3 clicks</li> <li><a href="https://www.auto-mcs.com/guides/amscript">Built-in scripting engine and IDE for writing custom p

## Self Hosted applications that can use a phone app?
 - [https://www.reddit.com/r/selfhosted/comments/1fmzo2t/self_hosted_applications_that_can_use_a_phone_app](https://www.reddit.com/r/selfhosted/comments/1fmzo2t/self_hosted_applications_that_can_use_a_phone_app)
 - RSS feed: $source
 - date published: 2024-09-22T18:14:05+00:00

<!-- SC_OFF --><div class="md"><p>What self hosted applications besides Bitwarden and Synology applications can also be connected to an app on your phone?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DearFly6441"> /u/DearFly6441 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmzo2t/self_hosted_applications_that_can_use_a_phone_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmzo2t/self_hosted_applications_that_can_use_a_phone_app/">[comments]</a></span>

## Proxmox its the best?
 - [https://www.reddit.com/r/selfhosted/comments/1fmxrb2/proxmox_its_the_best](https://www.reddit.com/r/selfhosted/comments/1fmxrb2/proxmox_its_the_best)
 - RSS feed: $source
 - date published: 2024-09-22T16:49:36+00:00

<!-- SC_OFF --><div class="md"><p>Helly guys! </p> <p>I&#39;m a complete newbie about selfhosting, and after a research, i still have some doubts, so i hope you guys can help me!</p> <p>I like to study cybersec, do CTF and so on, and nowadays, i run kali inside a VM on my personal PC. Also, i want to host a server with a lot of other services like; Jellyfin, PiHole, 2Fa, WireGuard, Minecraft and other games servers and get rid of cloud services.</p> <p>So...</p> <p>Its possible to run Kali Linux inside a home server? I&#39;ve read about Proxmox, and i liked the idea, BUT...</p> <p>I dont know if i can do ALL of that with Proxmox. I know i can create a lot of VMs inside of the Proxmox, but i dont know if its the best choice. </p> <p>My fear is; using a type 2 HyperV, gives me a lot of headache, so i need to run a type 1 HyperV = Proxmox.</p> <p>And last but not least; i wanted the fancy dashboards hahahah! So its possible, also, if i created a Proxmox VMs with Ubuntu and dockerized eve

## The best setup for code and compile from outside home?
 - [https://www.reddit.com/r/selfhosted/comments/1fmxp5w/the_best_setup_for_code_and_compile_from_outside](https://www.reddit.com/r/selfhosted/comments/1fmxp5w/the_best_setup_for_code_and_compile_from_outside)
 - RSS feed: $source
 - date published: 2024-09-22T16:46:59+00:00

<!-- SC_OFF --><div class="md"><p>if not the &quot;best&quot; setup at least a setup?</p> <p>A lot of time im out of home, and i have time to code. </p> <p>Can you share your approach? (i use PROXMOX as server)</p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/9acca9"> /u/9acca9 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmxp5w/the_best_setup_for_code_and_compile_from_outside/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmxp5w/the_best_setup_for_code_and_compile_from_outside/">[comments]</a></span>

## Does the M2 SSD speed matter?
 - [https://www.reddit.com/r/selfhosted/comments/1fmx9mq/does_the_m2_ssd_speed_matter](https://www.reddit.com/r/selfhosted/comments/1fmx9mq/does_the_m2_ssd_speed_matter)
 - RSS feed: $source
 - date published: 2024-09-22T16:28:17+00:00

<!-- SC_OFF --><div class="md"><p>When considering the use of an M.2 SSD with speeds of 3500 MB/s versus 7450 MB/s for a home server, will I really notice the difference? I have all my Docker folders with the compose files on a hard drive mounted to the system, so the only thing on the M.2 will be the Ubuntu Server OS itself.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/IAlwaysSayMadonna"> /u/IAlwaysSayMadonna </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmx9mq/does_the_m2_ssd_speed_matter/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmx9mq/does_the_m2_ssd_speed_matter/">[comments]</a></span>

## Prediction of copilot worked on code-server, but not copilot chat.
 - [https://www.reddit.com/r/selfhosted/comments/1fmx883/prediction_of_copilot_worked_on_codeserver_but](https://www.reddit.com/r/selfhosted/comments/1fmx883/prediction_of_copilot_worked_on_codeserver_but)
 - RSS feed: $source
 - date published: 2024-09-22T16:26:30+00:00

<!-- SC_OFF --><div class="md"><p>This is a crosspost, link: <a href="https://www.reddit.com/r/vscode/comments/1fmx6q1/prediction_of_copilot_worked_on_codeserver_but/">https://www.reddit.com/r/vscode/comments/1fmx6q1/prediction_of_copilot_worked_on_codeserver_but/</a></p> <p>I&#39;ve manually installed the GitHub copilot and GitHub copilot chat and I&#39;ve managed to make the prediction work but not the chat function.</p> <p>Any method to make the chat also work?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mother_Construction2"> /u/Mother_Construction2 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmx883/prediction_of_copilot_worked_on_codeserver_but/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmx883/prediction_of_copilot_worked_on_codeserver_but/">[comments]</a></span>

## VPN or per app authentication?
 - [https://www.reddit.com/r/selfhosted/comments/1fmw5oe/vpn_or_per_app_authentication](https://www.reddit.com/r/selfhosted/comments/1fmw5oe/vpn_or_per_app_authentication)
 - RSS feed: $source
 - date published: 2024-09-22T15:39:05+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I&#39;m new to self-hosting and I have a question I&#39;d like to clarify.</p> <p>My goal is to run several applications (Immich, Actual-Budget, NextCloud, *arr suite, etc.) on my home server so that I can access them both from within my LAN and externally.</p> <p>I&#39;m using a Debian system with Docker, behind a residential FTTH modem/router, and I&#39;ve got an FQDN set up via DuckDNS. Right now I have blocked on my server any port from outside LAN except 443, managed by the reverse proxy (Caddy), and it accepts any connection from inside the LAN.</p> <p>From what I understand, I have two options:</p> <ol> <li><p>Expose each app externally via reverse proxy, making it accessible through the FQDN and the reverse proxy, leaning on the per app authentication. Example: mysite.duckdns.org/app1/</p></li> <li><p>Use a VPN and act as if I&#39;m always inside the LAN. Example: 192.168.1.35:5678</p></li> </ol> <p>Is that correct?</p> <p>

## Setting up OPNsense as Router for LXC Containers & Virtual Machines
 - [https://www.reddit.com/r/selfhosted/comments/1fmvgo8/setting_up_opnsense_as_router_for_lxc_containers](https://www.reddit.com/r/selfhosted/comments/1fmvgo8/setting_up_opnsense_as_router_for_lxc_containers)
 - RSS feed: $source
 - date published: 2024-09-22T15:08:17+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fmvgo8/setting_up_opnsense_as_router_for_lxc_containers/"> <img src="https://b.thumbs.redditmedia.com/VO6K04W9a1rukdUD90tB6PZ5vK7orRENivWuGGVAc8g.jpg" alt="Setting up OPNsense as Router for LXC Containers &amp; Virtual Machines" title="Setting up OPNsense as Router for LXC Containers &amp; Virtual Machines" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Does somebody have any tutorial for setting up an OPNsense/Pfsense as a router for all containers/vms created in proxmox?<br/> I want to do this in order to isolate the vms from my home network and also get a static ip from an external server using OPNsense VPN function .</p> <p>I attached my current configuration below.<br/> I tried creating a new vmbr1 in network tab and install OPNsense but when I create a vm and try to access the OPNsense GUI it only works if vmbr0 is linked as a network device to that machine. If I only use vmbr1 I can&#39;t access the OP

## Apache - reverse proxy and webserver at the same time ?
 - [https://www.reddit.com/r/selfhosted/comments/1fmuz9k/apache_reverse_proxy_and_webserver_at_the_same](https://www.reddit.com/r/selfhosted/comments/1fmuz9k/apache_reverse_proxy_and_webserver_at_the_same)
 - RSS feed: $source
 - date published: 2024-09-22T14:47:09+00:00

<!-- SC_OFF --><div class="md"><p>I hope this is the right place to ask, if not, could you point me to the correspending subreddit ? </p> <p>So I got the following situation:<br/> I installed apache on a my own server sitting in my house, hosting mediawiki and a forum (or will be soon) as well as some other minor things.<br/> Now I want to replace Mediawiki with Wiki.js, however wiki.js has an integrated web server and is listening on port 3000. </p> <p>Now since I am self-hosting and don&#39;t want my public IP out there, I am using Cloudflare. And Cloudflare doesn&#39;t allow me to address specific ports, but always routs to 80 and 443.</p> <p>How would I need to set up Apache to route <a href="http://www.mydomain.com">www.mydomain.com</a> to /www/, forum.mydomain.com to /www/forum/ etc and wiki.mydomain.com to localhost:3000 ?<br/> Would redirecting the last subdomain to localhost:3000, assuming wiki.js is on the same server, work to serve that website ?</p> </div><!-- SC_ON --> &#

## File access anywhere from phone
 - [https://www.reddit.com/r/selfhosted/comments/1fmuh1j/file_access_anywhere_from_phone](https://www.reddit.com/r/selfhosted/comments/1fmuh1j/file_access_anywhere_from_phone)
 - RSS feed: $source
 - date published: 2024-09-22T14:24:22+00:00

<!-- SC_OFF --><div class="md"><p>I want to have access to a single folder on my server from my phone at all times (assuming I have service). It will be to upload files from my phone to my paperless intake folder.</p> <p>Any recommendations? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/happyjackassiam"> /u/happyjackassiam </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmuh1j/file_access_anywhere_from_phone/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmuh1j/file_access_anywhere_from_phone/">[comments]</a></span>

## Self-hosting hobbyists, how would you describe your hobby to non-technical people?
 - [https://www.reddit.com/r/selfhosted/comments/1fmucdv/selfhosting_hobbyists_how_would_you_describe_your](https://www.reddit.com/r/selfhosted/comments/1fmucdv/selfhosting_hobbyists_how_would_you_describe_your)
 - RSS feed: $source
 - date published: 2024-09-22T14:18:25+00:00

<!-- SC_OFF --><div class="md"><p>I consider self-hosting one of my biggest hobbies (I run a cluster with hundreds of containers including things like wekan, photoprism, n8n, firefly iii, and so on), but I find it hard to explain what I&#39;m doing or why I&#39;m doing it, especially to non-technical people.</p> <p>I usually go the privacy route, talking about the evils of big tech and the power of controlling your own data, but that feels very political for a hobby. </p> <p>How do you usually talk about it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gaussian_distro"> /u/gaussian_distro </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmucdv/selfhosting_hobbyists_how_would_you_describe_your/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmucdv/selfhosting_hobbyists_how_would_you_describe_your/">[comments]</a></span>

## Cheap solution to be able to turn a server on remotely (while on vacations)?
 - [https://www.reddit.com/r/selfhosted/comments/1fmu7f1/cheap_solution_to_be_able_to_turn_a_server_on](https://www.reddit.com/r/selfhosted/comments/1fmu7f1/cheap_solution_to_be_able_to_turn_a_server_on)
 - RSS feed: $source
 - date published: 2024-09-22T14:12:11+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, so I was wondering what could be a solution to blackouts at home where my server runs 24/7 and being on vacations. It’s bit critical to keep it on all times but I want to be able to turn it back on. </p> <p>Sometime ago I was suggested an old android phone to convert it into another server. The phone has a battery and would be plugging in all the time. I guess it’s not very safe to be “charging” the phone for hours and days but I guess for 1-2 weeks during the vacations it could be fine. </p> <p>Is there any other solution to this? What other device I could use? But please don’t suggest backup batteries. I want something subtle. </p> <p>In case of an android phone I assume I just install some Linux emulation and Wireguard to be able to WOL the main server. Is that right?</p> <p>Thank you </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/chicocheco"> /u/chicocheco </a> <br/> <span><a href="https://www.red

## What do you use for your notifications/activity monitor?
 - [https://www.reddit.com/r/selfhosted/comments/1fmtv6g/what_do_you_use_for_your_notificationsactivity](https://www.reddit.com/r/selfhosted/comments/1fmtv6g/what_do_you_use_for_your_notificationsactivity)
 - RSS feed: $source
 - date published: 2024-09-22T13:56:33+00:00

<!-- SC_OFF --><div class="md"><p>I like to have some kind of notification feed for things happening on my server cluster whether it be for site monitoring, service events or errors. </p> <p>I recently moved to Discord because the notifications were a bit more permanent than some of the other push services and it doesn&#39;t clog up my email inbox. The self hosted inside me though doesn&#39;t like relying too much on a service like Discord or Telegram. </p> <p>What do you use to keep tabs on what&#39;s going on?,</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ChapteristOllie"> /u/ChapteristOllie </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmtv6g/what_do_you_use_for_your_notificationsactivity/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmtv6g/what_do_you_use_for_your_notificationsactivity/">[comments]</a></span>

## Audio recordings iOS sync with selfhosted
 - [https://www.reddit.com/r/selfhosted/comments/1fmtaht/audio_recordings_ios_sync_with_selfhosted](https://www.reddit.com/r/selfhosted/comments/1fmtaht/audio_recordings_ios_sync_with_selfhosted)
 - RSS feed: $source
 - date published: 2024-09-22T13:29:16+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;d like to have a voice recorder app on iOS, I&#39;d pay for it.</p> <p>There reason why I put this in selfhosted is because I will not use any publicly hosted cloud solutions but I need to have automated sync to my server. It needs to work with a selfhosted solution in order to sync the files automatically.</p> <p>Currently I&#39;m using seafile which is a nice app, but for audio file sync it&#39;s no fit, or is it? Yet all those voice recorder apps I tried only offer like the DropBox or iCloud backends. What I will also not consider is Nextcloud/owncloud because this is totally overkill for my purpose.</p> <p>Any ideas?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/junialter"> /u/junialter </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmtaht/audio_recordings_ios_sync_with_selfhosted/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmtaht/aud

## Where to mount fonts in the drawio container?
 - [https://www.reddit.com/r/selfhosted/comments/1fmt2a5/where_to_mount_fonts_in_the_drawio_container](https://www.reddit.com/r/selfhosted/comments/1fmt2a5/where_to_mount_fonts_in_the_drawio_container)
 - RSS feed: $source
 - date published: 2024-09-22T13:17:52+00:00

<!-- SC_OFF --><div class="md"><p>Hey, all the docs talk about mounting font directories for the plantuml and image-exporter containers, but I don&#39;t see any information about mount font directories on the drawio container itself.</p> <p>Aren&#39;t you supposed to do that or something? Maybe I&#39;m missing something though. How do you guys make sure you always have the fonts available that you want to use?</p> <p>(Crossposting this from <a href="/r/drawio">r/drawio</a>, since I&#39;m not getting any input there, and I assume there will be at least some people in this subreddit who also use drawio)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/wzzrd"> /u/wzzrd </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmt2a5/where_to_mount_fonts_in_the_drawio_container/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmt2a5/where_to_mount_fonts_in_the_drawio_container/">[comments]</a></span>

## Secrets manager for securing keys / passwords used in automated backup scripts?
 - [https://www.reddit.com/r/selfhosted/comments/1fmsxgz/secrets_manager_for_securing_keys_passwords_used](https://www.reddit.com/r/selfhosted/comments/1fmsxgz/secrets_manager_for_securing_keys_passwords_used)
 - RSS feed: $source
 - date published: 2024-09-22T13:11:08+00:00

<!-- SC_OFF --><div class="md"><p>I currently have a synology NAS which uses task scheduler to run a script which backups up the NAS using restic. As part of this automated script, I have the backblaze API keys and the Restic repository password stored in plaintext files on the NAS.</p> <p>I&#39;m basically looking for a secure way to store the password of a restic repository (and blacblaze keys) in order to perform automatic backups that would prevent an attacker (that gets access to the NAS) from recovering the password or backblaze keys?</p> <p>The script also needs to be fully automatic, so it can&#39;t be a solution which relies on me manually authenticating the backups for example.</p> <p>Ideally, the secrets manager would check if the key is being requested at the correct time (when the script is scheduled to run), and then only approve the request if the key is called at the exact time the script runs. Basically some sort of time-based access control?</p> <p>What would be the 

## Any self hosted alternative for Genially?
 - [https://www.reddit.com/r/selfhosted/comments/1fmspml/any_self_hosted_alternative_for_genially](https://www.reddit.com/r/selfhosted/comments/1fmspml/any_self_hosted_alternative_for_genially)
 - RSS feed: $source
 - date published: 2024-09-22T13:00:19+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fmspml/any_self_hosted_alternative_for_genially/"> <img src="https://external-preview.redd.it/w2fipTTOae7PWSaSssUcoVKiQfyCBeITexTdCXpOQi4.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=64fc04d1e434d60f7290c15f2c9e9d360b8b623b" alt="Any self hosted alternative for Genially?" title="Any self hosted alternative for Genially?" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AlbertoAru"> /u/AlbertoAru </a> <br/> <span><a href="https://view.genially.com/610832cf0d78a50d7c5fa2f2/presentation-1-introduccion-a-genially">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmspml/any_self_hosted_alternative_for_genially/">[comments]</a></span> </td></tr></table>

## 🆕 Cosmos 0.16 (FINALLY) - All in one secure Reverse-proxy, container manager with app store, integrated VPN, authentication provider, and Monitoring, now with Multilingual support, completely reworked VPN, mDNS, and many improvements
 - [https://www.reddit.com/r/selfhosted/comments/1fms79e/cosmos_016_finally_all_in_one_secure_reverseproxy](https://www.reddit.com/r/selfhosted/comments/1fms79e/cosmos_016_finally_all_in_one_secure_reverseproxy)
 - RSS feed: $source
 - date published: 2024-09-22T12:32:51+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fms79e/cosmos_016_finally_all_in_one_secure_reverseproxy/"> <img src="https://external-preview.redd.it/p1pukzE8k2_DI4BTq48DOThvyaCnA9lVcKrwTJrvGzQ.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=0492f47a5224abd4767a353b71e9235a95738c85" alt="🆕 Cosmos 0.16 (FINALLY) - All in one secure Reverse-proxy, container manager with app store, integrated VPN, authentication provider, and Monitoring, now with Multilingual support, completely reworked VPN, mDNS, and many improvements " title="🆕 Cosmos 0.16 (FINALLY) - All in one secure Reverse-proxy, container manager with app store, integrated VPN, authentication provider, and Monitoring, now with Multilingual support, completely reworked VPN, mDNS, and many improvements " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>link: <a href="https://github.com/azukaar/Cosmos-Server/">https://github.com/azukaar/Cosmos-Server/</a></p> <p>Wow, what a trip! 6 months ago I started w

## Selfhost local copy of emails
 - [https://www.reddit.com/r/selfhosted/comments/1fmqaki/selfhost_local_copy_of_emails](https://www.reddit.com/r/selfhosted/comments/1fmqaki/selfhost_local_copy_of_emails)
 - RSS feed: $source
 - date published: 2024-09-22T10:37:15+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I need some advice on how to selfhost emails, to be slightly more independent from the tech giants.</p> <p>I already have a home server, with a Docker Compose stack (Dockge + Traefik with ACME certificate and reverse proxy set on my domain). And I currently use a Google Workspace account with my domain name for everything Gmail and daily backups on Drive.</p> <p>The idea is to keep the Google Workspace working for the emails, as everything is perfectly set (SPF, DKIM, DMARC) and I did custom email routing to have a catch-all email on the one user inbox.</p> <p>But I want to set a local email inbox that will get a copy of every emails received in Gmail (by manually retrieving all the mails as they come via POP3 or IMAP and leaving the Gmail copy of the email intact, I guess).</p> <p>And then use Nextcloud Mail webclient to connect to my local inbox, and to use Google SMTP-Relay for send emails. If a copy of sent email can be copied to the

## cheapest way to get video output over the network
 - [https://www.reddit.com/r/selfhosted/comments/1fmq6wk/cheapest_way_to_get_video_output_over_the_network](https://www.reddit.com/r/selfhosted/comments/1fmq6wk/cheapest_way_to_get_video_output_over_the_network)
 - RSS feed: $source
 - date published: 2024-09-22T10:30:34+00:00

<!-- SC_OFF --><div class="md"><p>I want to run my old pc as a server and want to get video ouput over the network. I know i can use some terminal software to connect to linux but i also need to be able to go into the bios without always moving the PC to my room, connecting it to a monitor just because i want to do sth. in the bios or reinstall an os etc..</p> <p>So i need to be able to get image and also be able to make inputs. I know vnc but i dont have an intel vpro or amd pro cpu, i have an i5-4590, so i can&#39;t access bios with that. if there is any workaround without buying a whole new Server with a pro cpu it would be nice. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Shindikat"> /u/Shindikat </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmq6wk/cheapest_way_to_get_video_output_over_the_network/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmq6wk/cheapest_way_to_get_vi

## Anything to add to a Caddyfile for simple Homeserver ?
 - [https://www.reddit.com/r/selfhosted/comments/1fmoy6x/anything_to_add_to_a_caddyfile_for_simple](https://www.reddit.com/r/selfhosted/comments/1fmoy6x/anything_to_add_to_a_caddyfile_for_simple)
 - RSS feed: $source
 - date published: 2024-09-22T09:02:28+00:00

<!-- SC_OFF --><div class="md"><p>So I&#39;m having a fairly simple setup for exposing a few of my services when needed, it looks like that :</p> <p><a href="http://y.x.com"><code>y.x.com</code></a> <code>{</code></p> <p><code>reverse_proxy :8096</code></p> <p><code>}</code></p> <p>The one thing I&#39;m wondering is, am I missing something on not adding some <code>encode xxzip</code> or anything of that kind when defining my reverse proxies ?</p> <p>Is it really useful or is it just good practice that I should put as soon as possible ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Daitan_"> /u/Daitan_ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmoy6x/anything_to_add_to_a_caddyfile_for_simple/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmoy6x/anything_to_add_to_a_caddyfile_for_simple/">[comments]</a></span>

## Automatic install of dotfiles and tools
 - [https://www.reddit.com/r/selfhosted/comments/1fmohuy/automatic_install_of_dotfiles_and_tools](https://www.reddit.com/r/selfhosted/comments/1fmohuy/automatic_install_of_dotfiles_and_tools)
 - RSS feed: $source
 - date published: 2024-09-22T08:29:09+00:00

<!-- SC_OFF --><div class="md"><p>Hello folks</p> <p>I find myself using SSH (and such) quite a lot</p> <p>However, my personal computer has quite some dotfiles and tools (zsh, tmux, nvim, command aliases, maybe some future nix config files, etc…) which I became habitued to and that improve my productivity and ergonomy </p> <p>What&#39;s the best ways to make them to be automatically installed and mounted on the remote ?</p> <p>I am thinking about two options : temporary or permanent (installed on a different userspace which is optionally deleted at logout, updated with the new tools and dotfiles at every login)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/The-Malix"> /u/The-Malix </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmohuy/automatic_install_of_dotfiles_and_tools/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmohuy/automatic_install_of_dotfiles_and_tools/">[comments]</

## Self hosted email... well, not really
 - [https://www.reddit.com/r/selfhosted/comments/1fmoenw/self_hosted_email_well_not_really](https://www.reddit.com/r/selfhosted/comments/1fmoenw/self_hosted_email_well_not_really)
 - RSS feed: $source
 - date published: 2024-09-22T08:22:22+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I was having a Google Suite for Education account with loads of storage, big G then lately decided to reduce the storage to 10GB only and my mail box alone was already bigger than that. Right now, I have backed up old email using Thunderbird, but I am less than happy with the solution because it is on one given machine, but also, Thunderbird is EOL.</p> <p>I quickly passed through the consideration of having my own server as it gives me quite a headache between the required uptime so that I do not miss any email, but also, the black-list management that can become really pain in the rear.</p> <p>So what I would like to achieve now would be the following :</p> <ul> <li>a &quot;mail&quot; server with all emails stored on it</li> <li>this server is accessible through a webmail, even better if there is an Android app</li> <li>This server connects to Google, Outlook and all my other email addresses to download the emails from there.</li> <li>Thi

## What does redis actually do? (embarrassing question)
 - [https://www.reddit.com/r/selfhosted/comments/1fmod6a/what_does_redis_actually_do_embarrassing_question](https://www.reddit.com/r/selfhosted/comments/1fmod6a/what_does_redis_actually_do_embarrassing_question)
 - RSS feed: $source
 - date published: 2024-09-22T08:19:24+00:00

<!-- SC_OFF --><div class="md"><p>Many of my self-hosted apps run a db (mariadb etc) AND redis. I read the docs of redis, but still not sure in plain English what it actually does, and why it is indispensable. Could someone please explain in plain English, what is redis for, especially when used with another db? Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/maltokyo"> /u/maltokyo </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmod6a/what_does_redis_actually_do_embarrassing_question/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmod6a/what_does_redis_actually_do_embarrassing_question/">[comments]</a></span>

## Home-Server: Automating my Local Home Server Setup with Docker & Docker Compose! 🖥️📦🚀
 - [https://www.reddit.com/r/selfhosted/comments/1fmoai0/homeserver_automating_my_local_home_server_setup](https://www.reddit.com/r/selfhosted/comments/1fmoai0/homeserver_automating_my_local_home_server_setup)
 - RSS feed: $source
 - date published: 2024-09-22T08:13:41+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fmoai0/homeserver_automating_my_local_home_server_setup/"> <img src="https://b.thumbs.redditmedia.com/IMQ4A5zIIfPJJKyje729TE67PD6SdXA1nv1KeGTaccc.jpg" alt="Home-Server: Automating my Local Home Server Setup with Docker &amp; Docker Compose! 🖥️📦🚀" title="Home-Server: Automating my Local Home Server Setup with Docker &amp; Docker Compose! 🖥️📦🚀" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/mumn8cnplbqd1.png?width=1920&amp;format=png&amp;auto=webp&amp;s=59c064e74682e2c8515639ae6b1c4d8737359581">https://preview.redd.it/mumn8cnplbqd1.png?width=1920&amp;format=png&amp;auto=webp&amp;s=59c064e74682e2c8515639ae6b1c4d8737359581</a></p> <p>Hey everyone! 👋</p> <p>I’m excited to introduce **Home-Server**, a project I’ve been developing that automates the setup and management of my **local** home server using **Docker** and **Docker Compose**. From media servers like Plex and Jellyfin to d

## Verizon Fios Router Redirects port 80 to network settings despite port forwarding rule
 - [https://www.reddit.com/r/selfhosted/comments/1fmn4kv/verizon_fios_router_redirects_port_80_to_network](https://www.reddit.com/r/selfhosted/comments/1fmn4kv/verizon_fios_router_redirects_port_80_to_network)
 - RSS feed: $source
 - date published: 2024-09-22T06:48:05+00:00

<!-- SC_OFF --><div class="md"><p>Port 80 (idem for 443) is redirected to fios websettings. I figure this must be because i have remote access enabled but I ticked what i thought would disable it in the settings and that didn&#39;t do anything. I can sort of use port 81 for my http site but it&#39;s a pain. I also want to not have my network settings open to the internet. How can I close ports 80/443 for the router and forward then to my server. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JoeMamaSex420"> /u/JoeMamaSex420 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmn4kv/verizon_fios_router_redirects_port_80_to_network/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmn4kv/verizon_fios_router_redirects_port_80_to_network/">[comments]</a></span>

## How to run PFSense + Wireguard + Plex server running off a VPN with direct connection?
 - [https://www.reddit.com/r/selfhosted/comments/1fmn45l/how_to_run_pfsense_wireguard_plex_server_running](https://www.reddit.com/r/selfhosted/comments/1fmn45l/how_to_run_pfsense_wireguard_plex_server_running)
 - RSS feed: $source
 - date published: 2024-09-22T06:47:14+00:00

<!-- SC_OFF --><div class="md"><p>I’ve been handling this issue for about a week, and I haven’t been able to figure it out - so forgive my ignorance if it seems like an easy fix. Right now I’m running a VPN tunnel on PFSense on every device on my network (WAN &amp; LAN) EXCEPT my Plex server. This Plex server just so happens to be my PC, because I haven’t gotten around to getting a dedicated box. Since it’s my workstation, I prefer to run a VPN, the only issue is, as soon as my public IP changes on the Plex remote connection setting, no matter what I do works to give my clients a direct connection. I understand this is because there’s no way I can open a port on the VPN tunnel to allow Plex to run connections through it. I moved on to trying to figure out how to split tunnel all of my network traffic on the PC IP EXCEPT Plex through the VPN, but couldn’t get that to work either (I don’t know if it’s possible). I have not tried running my Plex server in a VM, so I don’t know if that’s 

## Subscription KB
 - [https://www.reddit.com/r/selfhosted/comments/1fmldak/subscription_kb](https://www.reddit.com/r/selfhosted/comments/1fmldak/subscription_kb)
 - RSS feed: $source
 - date published: 2024-09-22T04:47:35+00:00

<!-- SC_OFF --><div class="md"><p>I’m looking for a solution, where I can offer a subscription knowledge base doesn’t have to be self hosted. I would offer monthly / annual subscriptions to access the KB something that I could integrate with PayPal or Stripe. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OccasionTurbulent377"> /u/OccasionTurbulent377 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmldak/subscription_kb/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmldak/subscription_kb/">[comments]</a></span>

## Virtual Machine host
 - [https://www.reddit.com/r/selfhosted/comments/1fmjy56/virtual_machine_host](https://www.reddit.com/r/selfhosted/comments/1fmjy56/virtual_machine_host)
 - RSS feed: $source
 - date published: 2024-09-22T03:18:35+00:00

<!-- SC_OFF --><div class="md"><p>Hello. My laptop is doo doo. </p> <p>I&#39;d like a VPS that I can deploy a VM on, and do stuff on HackTheBox, and TryHackMe. </p> <p>I&#39;m looking for budget friendly, but so far I&#39;ve ruled out Linode, Vultr, and DigitalOcean. </p> <p>Please recommend me some you might know of, or have used for the same purpose. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Even-Study3817"> /u/Even-Study3817 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmjy56/virtual_machine_host/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmjy56/virtual_machine_host/">[comments]</a></span>

## Mealie Docker Compose lost data
 - [https://www.reddit.com/r/selfhosted/comments/1fmjfkx/mealie_docker_compose_lost_data](https://www.reddit.com/r/selfhosted/comments/1fmjfkx/mealie_docker_compose_lost_data)
 - RSS feed: $source
 - date published: 2024-09-22T02:48:43+00:00

<!-- SC_OFF --><div class="md"><p>So I am using this docker compose:</p> <p>services:</p> <p>mealie:</p> <p>image: <a href="http://ghcr.io/mealie-recipes/mealie:latest">ghcr.io/mealie-recipes/mealie:latest</a></p> <p>container_name: mealie</p> <p>restart: always</p> <p>ports:</p> <ul> <li>&quot;9925:9000&quot; #</li> </ul> <p>deploy:</p> <p>resources:</p> <p>limits:</p> <p>memory: 1000M #</p> <p>volumes:</p> <ul> <li>mealie-data:/app/data/</li> </ul> <p>environment:</p> <h1>Set Backend ENV Variables Here</h1> <p>ALLOW_SIGNUP: false</p> <p>PUID: 1000</p> <p>PGID: 1000</p> <p>TZ: America/Chicago</p> <p>MAX_WORKERS: 1</p> <p>WEB_CONCURRENCY: 1</p> <p>BASE_URL: <a href="https://redacted/">https://redacted</a></p> <p>SMTP_HOST: smtpredacted</p> <p>SMTP_PORT: 465</p> <p>SMTP_FROM_NAME: Mealie</p> <p>SMTP_AUTH_STRATEGY: SSL</p> <p>SMTP_FROM_EMAIL: notification@redacted</p> <p>SMTP_USER: notification@sredeacted</p> <p>SMTP_PASSWORD: jredecard</p> <p>OPENAI_BASE_URL:</p> <p>OPENAI_API_KEY: red

## Using Wireguard and Pterodacyl
 - [https://www.reddit.com/r/selfhosted/comments/1fmj7dy/using_wireguard_and_pterodacyl](https://www.reddit.com/r/selfhosted/comments/1fmj7dy/using_wireguard_and_pterodacyl)
 - RSS feed: $source
 - date published: 2024-09-22T02:35:17+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fmj7dy/using_wireguard_and_pterodacyl/"> <img src="https://b.thumbs.redditmedia.com/qgyQkFs89-5xPyQtIP8nS19IcbkoOtXjRjagFDiYTSA.jpg" alt="Using Wireguard and Pterodacyl" title="Using Wireguard and Pterodacyl" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Has anyone got pterodactyl and wireguard working and there self hosted servers, I only get it when using wireguard and wireguard is set up right because I can start a Minecraft server”any game server,” from the desktop and it works but when I try in pterodactyl I get these weird errors. I think it might have to do with docker or the panel trying to use the default network interface instead of wireguard?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Wakeisbest"> /u/Wakeisbest </a> <br/> <span><a href="https://www.reddit.com/gallery/1fmj7dy">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comm

## VPS or Socks5 Proxy?
 - [https://www.reddit.com/r/selfhosted/comments/1fmiw0p/vps_or_socks5_proxy](https://www.reddit.com/r/selfhosted/comments/1fmiw0p/vps_or_socks5_proxy)
 - RSS feed: $source
 - date published: 2024-09-22T02:17:00+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I am doing a remote job which requires my location to be in the UK. I am currently in the UK but I like to travel as well. I am thinking to continue my job work while being in europe, like a digital nomad. So what should be the ideal way to keep doing it without risking getting location traced. Socks5 proxy or a vps of UK? Please suggest</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Kind-Operation-2339"> /u/Kind-Operation-2339 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmiw0p/vps_or_socks5_proxy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmiw0p/vps_or_socks5_proxy/">[comments]</a></span>

## is https://nic.us.kg Legit?
 - [https://www.reddit.com/r/selfhosted/comments/1fmilxx/is_httpsnicuskg_legit](https://www.reddit.com/r/selfhosted/comments/1fmilxx/is_httpsnicuskg_legit)
 - RSS feed: $source
 - date published: 2024-09-22T02:01:18+00:00

<!-- SC_OFF --><div class="md"><p>Someone posted <a href="https://nic.us.kg/">https://nic.us.kg/</a> offer free domains that works with Cloudflare tunnel. Is this legit?</p> <p>Their way of KYC verification is , I need to star their repository in Github, I have post my email , user name publicly as Issue, then their automated script will approve my account. This sounds fishy to post my email open to the world. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ExceptionOccurred"> /u/ExceptionOccurred </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmilxx/is_httpsnicuskg_legit/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fmilxx/is_httpsnicuskg_legit/">[comments]</a></span>

