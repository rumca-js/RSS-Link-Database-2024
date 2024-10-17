# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## running pi-hole and vpn on ssd
 - [https://www.reddit.com/r/selfhosted/comments/1g5dhyh/running_pihole_and_vpn_on_ssd](https://www.reddit.com/r/selfhosted/comments/1g5dhyh/running_pihole_and_vpn_on_ssd)
 - RSS feed: $source
 - date published: 2024-10-16T23:44:26+00:00

<!-- SC_OFF --><div class="md"><p>I have another computer that im thinking of deploying with an 250gb ssd just to run tailscale, pi-hole, adguardhome (for fun), and technitium (also for fun). my question is would it be worth it to install proxmox and put those vms on there or keep my current cluster setup where they are running on a 1tb hdd. both machines are the exact same with ram and processor type. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/theannihilator"> /u/theannihilator </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5dhyh/running_pihole_and_vpn_on_ssd/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5dhyh/running_pihole_and_vpn_on_ssd/">[comments]</a></span>

## Handling local and public domain
 - [https://www.reddit.com/r/selfhosted/comments/1g5d8v4/handling_local_and_public_domain](https://www.reddit.com/r/selfhosted/comments/1g5d8v4/handling_local_and_public_domain)
 - RSS feed: $source
 - date published: 2024-10-16T23:31:48+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I&#39;m setting up my base services for my self-hosted setup, including reverse proxy and authentication service (setting up Traefik and Authentik). </p> <p>My initial plan was to have a local domain (e.g. `mylocalserver.home`) and later on a public domain (e.g eltaanguy.com), which I don&#39;t have </p> <p>Handling that for Traefik is not an issue, I can set up multiple routers for a same service, and I think it&#39;s a neat way to have services routable only if I join from local (by setting only one router with the local domain rule).</p> <p>But when configuring Authentik, handling two domains like this seem to be a burden, because I would need to setup double applications, double outposts, etc... because of redirection URLs to setup.<br/> I feel that I will face this kind of double domains issues in other services and other setups, so I&#39;m reconsidering the plan but having a kind of separation through local/public domains seem usef

## I want to make one SSD on my main PC accessible to everyone in my network
 - [https://www.reddit.com/r/selfhosted/comments/1g5cedb/i_want_to_make_one_ssd_on_my_main_pc_accessible](https://www.reddit.com/r/selfhosted/comments/1g5cedb/i_want_to_make_one_ssd_on_my_main_pc_accessible)
 - RSS feed: $source
 - date published: 2024-10-16T22:50:10+00:00

<!-- SC_OFF --><div class="md"><p>My main PC is running Ubuntu 24.04 LTS, I do basically everything on this PC, but I want to self-host some files on a separate SSD that I currently have installed on this machine but have nothing on it, it&#39;s not even partitioned yet. I&#39;m really new to self-hosting (UmbrelOS through a VM was my first contact), and I just want a simple and reliable solution to host my files, like a Google Drive but locally.</p> <p>I have tested options like NextCloud, but it is so complicated to change the file storage location and it appears to use a lot of resources, I don&#39;t know if I can install it directly on my separate SSD (preferably using a method like installing it with snap, which auto-installs everything), if I can do that, I&#39;ll be using NextCloud, but if possible I just want something like Syncthing, but with the ability to access the files like a cloud on any device, without syncing locally, such as phones, laptops, tablets and even on my TV

## Tasks.md 2.5.3
 - [https://www.reddit.com/r/selfhosted/comments/1g5byoc/tasksmd_253](https://www.reddit.com/r/selfhosted/comments/1g5byoc/tasksmd_253)
 - RSS feed: $source
 - date published: 2024-10-16T22:29:28+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g5byoc/tasksmd_253/"> <img src="https://b.thumbs.redditmedia.com/bVHp3L4lM9etDxXJXY9aUgGrs8ppjDXFM3t_2DTxYeU.jpg" alt="Tasks.md 2.5.3" title="Tasks.md 2.5.3" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey guys, version 2.5.3 of <a href="https://github.com/BaldissaraMatheus/Tasks.md">Tasks.md</a> just got released! The latest relase is actually pretty small, as I focused a lot on resolving technical debt, fixing visual inconsistencies and improving &quot;under the hood&quot; stuff. Which I will continue to do a little bit more before the next release.</p> <p><a href="https://preview.redd.it/lt1i66z647vd1.png?width=1020&amp;format=png&amp;auto=webp&amp;s=b16938ec29ee4886a27f8983e00e521304fa1aef">https://preview.redd.it/lt1i66z647vd1.png?width=1020&amp;format=png&amp;auto=webp&amp;s=b16938ec29ee4886a27f8983e00e521304fa1aef</a></p> <p><a href="https://github.com/BaldissaraMatheus/Tasks.md">Tasks.md</a> is a s

## mTLS, cloudflare, tailscale and home lab on internet.
 - [https://www.reddit.com/r/selfhosted/comments/1g5bqqv/mtls_cloudflare_tailscale_and_home_lab_on_internet](https://www.reddit.com/r/selfhosted/comments/1g5bqqv/mtls_cloudflare_tailscale_and_home_lab_on_internet)
 - RSS feed: $source
 - date published: 2024-10-16T22:19:04+00:00

<!-- SC_OFF --><div class="md"><p>I would like to hear from security folks if this approach looks safe or not. </p> <p>I have a domain name and at my home I am running a PC with nginx reverse proxy providing bunch of services. Right now, I can access all these services via tailscale running on the reverse proxy machine from my phone. </p> <p>Often times, I work in area where WiFi is only available and the WiFi is blocking tailscale due to policies. I cannot switch to cellular and access home resources.<br/> I have Oracle free VPS and I was thinking that I run the nginx with mTLS enabled on the VPS and then VPS connects to my home PC via tailscale and provide me access to all the resources. </p> <p>This way, I will eliminate the need for VPN on the phone to remotely access the resources. Also, the domain is on Cloudflare so I was thinking of enabling the proxy IP on VPS IP address so that I get some protection from DDOS. </p> <p>I wanted to know from experts if this is a safe option as

## Vewing iOS/Android in Web browser
 - [https://www.reddit.com/r/selfhosted/comments/1g5bmxp/vewing_iosandroid_in_web_browser](https://www.reddit.com/r/selfhosted/comments/1g5bmxp/vewing_iosandroid_in_web_browser)
 - RSS feed: $source
 - date published: 2024-10-16T22:14:08+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m not sure I have the right search string syntax, so hopefully someone has a better idea.</p> <p>What I&#39;m after is the ability to host something, and probably deliver via web browser, to see what an iOS or Android version looks like (ideally various versions as they&#39;re always changing the menu layout etc) to avoid having multiple devices and/or taking screenshots. Bonus points if you can actually install an app and see it, but not necessary. Not something like Phone Link where you connect to an actual mobile.</p> <p>Seems hard to find this tho...</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/GremlinNZ"> /u/GremlinNZ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5bmxp/vewing_iosandroid_in_web_browser/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5bmxp/vewing_iosandroid_in_web_browser/">[comments]</a></span>

## Jellyfin basics
 - [https://www.reddit.com/r/selfhosted/comments/1g5bkwb/jellyfin_basics](https://www.reddit.com/r/selfhosted/comments/1g5bkwb/jellyfin_basics)
 - RSS feed: $source
 - date published: 2024-10-16T22:11:36+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! Just stepping into the door of self hosting and wanted to set up Jellyfin. I was just gifted my girlfriends old laptop (i7-5500, 16 gb of ram, and a 500 gb hdd). I’ve been doing a bit of research and was curious if that was a good enough rig to run it off of? Also, I’ve read Ubuntu is the most ideal OS, so I’m installing that now onto that laptop. </p> <p>Some more questions:</p> <ol> <li>Does the computer have to be on when I want to watch on say my main computer or my phone?</li> <li>If I wanted say 20 movies and 10 shows would I need more then 500 gb of storage? Jellyfin would be the only thing on that computer.</li> <li>Could I run jellyfin on older hardware? Say from an i3-i5? Or is it best to stick with the newest one I can?</li> </ol> <p>Thanks everyone!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ActivityBackground11"> /u/ActivityBackground11 </a> <br/> <span><a href="https://www.reddit.

## Authentication Server with Passkeys
 - [https://www.reddit.com/r/selfhosted/comments/1g5bg9s/authentication_server_with_passkeys](https://www.reddit.com/r/selfhosted/comments/1g5bg9s/authentication_server_with_passkeys)
 - RSS feed: $source
 - date published: 2024-10-16T22:05:42+00:00

<!-- SC_OFF --><div class="md"><p>Hello Everyone,</p> <p>For the past couple weeks, I am working on a simple authentication server to secure homelab / self hosted apps. The idea behind it is a post <a href="https://www.reddit.com/r/selfhosted/comments/1f7fith/passkeys/">here</a> , basically to rely on passkeys as the main authentication method. With that in mind, introducing: <a href="https://dirathea.github.io/pasolo/">Pasolo</a></p> <p>Pasolo is a simple single user authentication server using passkeys. Pasolo need to runs alongside load balancer like Caddy, Traefik with forward_auth / external auth enabled. The main focus of Pasolo is for those who want to add security layer on top of their setup with passkeys.</p> <p>It&#39;s very early, and I am looking for your feedback about the project. Thank you</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/East-Home-7362"> /u/East-Home-7362 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted

## Set up router so all WiFi connections are automatically tunnled through Wireguard.
 - [https://www.reddit.com/r/selfhosted/comments/1g5bbac/set_up_router_so_all_wifi_connections_are](https://www.reddit.com/r/selfhosted/comments/1g5bbac/set_up_router_so_all_wifi_connections_are)
 - RSS feed: $source
 - date published: 2024-10-16T21:59:25+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, </p> <p>I am hosting a pivpn wireguard server on my raspberry pi4b and I want to configure my router (Linksys EA 6350) to have all the WiFi connections go through my wireguard server. How do I do this? I looked up how to and the results I got were how to set up DD-WRT to be wireguard server. </p> <p>The problem is I have a dynamic IP address that changes maybe 3-6 times a year. I already talked with my ISP and they won&#39;t give me a static IP. I am working on a bash script that automatically up dates my public IP on my setupVARs.conf on my rasbery pi so that I just need to update my clients when my public IP changes to get around this problem. </p> <p>1) Is it possible for DD-WRT to be a client of my wireguard server so that all WiFi connections are tunnled through wireguard?</p> <p>2) If so, will my ufw firewall (also on my raspberry pi) rules be applied to these WiFi connections? </p> <p>Any guidance and insight would be appreciated.</p> <

## Floor Plan / Map Builder
 - [https://www.reddit.com/r/selfhosted/comments/1g5amd5/floor_plan_map_builder](https://www.reddit.com/r/selfhosted/comments/1g5amd5/floor_plan_map_builder)
 - RSS feed: $source
 - date published: 2024-10-16T21:28:06+00:00

<!-- SC_OFF --><div class="md"><p>Any self hosted solutions for an app that lets you create floor plans or blueprints? Would like it to be web-accessible.</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OliDouche"> /u/OliDouche </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5amd5/floor_plan_map_builder/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5amd5/floor_plan_map_builder/">[comments]</a></span>

## Need some help with my setup
 - [https://www.reddit.com/r/selfhosted/comments/1g5al3z/need_some_help_with_my_setup](https://www.reddit.com/r/selfhosted/comments/1g5al3z/need_some_help_with_my_setup)
 - RSS feed: $source
 - date published: 2024-10-16T21:26:34+00:00

<!-- SC_OFF --><div class="md"><p>I am pretty new to everything in self hosted trying learn my way around, but stuck on making some decisions on how I want to set things up.</p> <p>Here’s what I have:</p> <p>Intel i7 6700k Processor (repurposing an old gaming pc) Nvidia GTX 970 32 GB DDR4 Ram 4 X 16TB Seagate Ironwolf Pro Drives 1 X Samsung 970 Evo m.2 NVME 500gb 1 X Samsung 870 Evo SSD 1TB </p> <p>What I would like to do is set up the arr stack either via portainer or proxmox or a mix?</p> <p>Setup Plex for external and local access Setup Arr stack to be able to handle requests for content via sonarr and radarr </p> <p>Id like to set this up to also use Sabnzbd to connect to Usenet providers </p> <p>The 16TB drives should be used as a single drive 48TB not to concerned about losing data but if there’s a nice and easy way to make the drive expandable or recoverable if a drive fails that would be nice </p> <p>That’s basically it for media</p> <p>I would also like the functionality to s

## Update: Scriberr now does speaker diarization
 - [https://www.reddit.com/r/selfhosted/comments/1g5aedq/update_scriberr_now_does_speaker_diarization](https://www.reddit.com/r/selfhosted/comments/1g5aedq/update_scriberr_now_does_speaker_diarization)
 - RSS feed: $source
 - date published: 2024-10-16T21:18:22+00:00

<!-- SC_OFF --><div class="md"><p>Last week, I announced the release of Scriberr, a self-hostable AI audio transcription app. Today, I’m excited to announce v0.2.0 which adds speaker diarization and a bunch of other enhancements. </p> <h2>What’s new</h2> <ul> <li>automatic speaker diarization (experimental)</li> <li>Enhanced reactivity (app now provides visual feedback for all actions)</li> <li>Fixed all reactivity issues (no more having to refresh constantly)</li> <li>CRUD operations on records and templates</li> <li>Double click title to edit, right click list to delete</li> <li>UI/UX tweaks</li> </ul> <p>Going forward I’m working on adding some nice enhancements and features, some of which are listed below:</p> <ul> <li>Add choices for speaker matching algorithms to improve diarization</li> <li>Hardware setup wizard to compile whisper optimized for your hardware</li> <li>Support for multiple languages</li> <li>Subtitle generation</li> <li>YouTube integration to auto transcribe YouT

## Help with migrating away from YunoHost
 - [https://www.reddit.com/r/selfhosted/comments/1g59b1r/help_with_migrating_away_from_yunohost](https://www.reddit.com/r/selfhosted/comments/1g59b1r/help_with_migrating_away_from_yunohost)
 - RSS feed: $source
 - date published: 2024-10-16T20:32:42+00:00

<!-- SC_OFF --><div class="md"><p>Hi, more and more I am considering switching from YunoHost to something else - I believe it&#39;s time to enter a world of Docker/Podman and YH does not really support containers. On one hand I quite like the level of integration (automated backups, updates, user management, cert renewals, e-mail, firewall..) on the other hand, the applications in the repository get broken or outdated, I get random DNS errors and the interface is a bit aging too.</p> <p>Anyone could suggest a good replacement? TIA.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Revolutionary_Gur583"> /u/Revolutionary_Gur583 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g59b1r/help_with_migrating_away_from_yunohost/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g59b1r/help_with_migrating_away_from_yunohost/">[comments]</a></span>

## My home server is on a Mac, how can I manage it remotely?
 - [https://www.reddit.com/r/selfhosted/comments/1g57u85/my_home_server_is_on_a_mac_how_can_i_manage_it](https://www.reddit.com/r/selfhosted/comments/1g57u85/my_home_server_is_on_a_mac_how_can_i_manage_it)
 - RSS feed: $source
 - date published: 2024-10-16T19:29:20+00:00

<!-- SC_OFF --><div class="md"><p>At home, I use the screen sharing Mac app to manage it. But outside of the network, what do I need to access it and manage it remotely?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/not-bilbo-baggings"> /u/not-bilbo-baggings </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g57u85/my_home_server_is_on_a_mac_how_can_i_manage_it/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g57u85/my_home_server_is_on_a_mac_how_can_i_manage_it/">[comments]</a></span>

## I had allocated 100 GB in proxmox vm but it shows up as 50 GB. Sending lsblk and bpytop
 - [https://www.reddit.com/r/selfhosted/comments/1g578ws/i_had_allocated_100_gb_in_proxmox_vm_but_it_shows](https://www.reddit.com/r/selfhosted/comments/1g578ws/i_had_allocated_100_gb_in_proxmox_vm_but_it_shows)
 - RSS feed: $source
 - date published: 2024-10-16T19:03:22+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g578ws/i_had_allocated_100_gb_in_proxmox_vm_but_it_shows/"> <img src="https://b.thumbs.redditmedia.com/6mXEvzQ4YONAZQ-gkfcNAYE8WWoleQGBxi8Ht3lMiPs.jpg" alt="I had allocated 100 GB in proxmox vm but it shows up as 50 GB. Sending lsblk and bpytop" title="I had allocated 100 GB in proxmox vm but it shows up as 50 GB. Sending lsblk and bpytop" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I created a vm in proxmox to run samba. I had allocated 100 GB to the VM but it shows up as 49 GB. Below is the screenshot from Bpytop and output from lsblk.</p> <p><a href="https://preview.redd.it/bo72fa0n16vd1.png?width=491&amp;format=png&amp;auto=webp&amp;s=20560c52f67359a8bf4e990deddb8d270a313136">https://preview.redd.it/bo72fa0n16vd1.png?width=491&amp;format=png&amp;auto=webp&amp;s=20560c52f67359a8bf4e990deddb8d270a313136</a></p> <p><code>NAME MAJ:MIN RM SIZE RO TYPE MOUNTPOINTS</code></p> <p><code>sda 8:0 0 100G 0 disk</c

## Prevention of "disk full" situation
 - [https://www.reddit.com/r/selfhosted/comments/1g5764f/prevention_of_disk_full_situation](https://www.reddit.com/r/selfhosted/comments/1g5764f/prevention_of_disk_full_situation)
 - RSS feed: $source
 - date published: 2024-10-16T19:00:15+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>So, zero free space might crash a Linux VPS and in a worst case scenario make data unrecoverable, unless the VPS provider offers a recovery console.</p> <p>How do people normally avoid this scenario if there is something that can fill the disk, such as a file sharing thing or a downloader thing?</p> <p>My instinct from Linux use would be to have a / volume strictly for the system and a bigger /home for everything else so that if there is zero free space on /home I can still log in. However, I&#39;d need to keep the / rather large for the updates, and besides this means I can&#39;t really use a standard image.</p> <p>Quotas can be useless if services work as more than one user and group.</p> <p>So, what&#39;s the thing to do here?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ramendik"> /u/ramendik </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5764f/prevention_of_disk_ful

## Traefik/Authentik on it's own hardware or just keep on unraid
 - [https://www.reddit.com/r/selfhosted/comments/1g56s57/traefikauthentik_on_its_own_hardware_or_just_keep](https://www.reddit.com/r/selfhosted/comments/1g56s57/traefikauthentik_on_its_own_hardware_or_just_keep)
 - RSS feed: $source
 - date published: 2024-10-16T18:44:03+00:00

<!-- SC_OFF --><div class="md"><p>Currently have Nginx Proxy Manager and Authentik running on my unraid server, but I wanted to give Traefik 3 a try so I installed it on a raspberry Pi that I wasn&#39;t using for anything and still have Authentik running on my unraid server. I&#39;m thinking about getting a low power mini PC to install Ubuntu onto and run Traefik and Authentik on that as an entry point into my services. At this point, it&#39;s just a project for me to work on, everything is working just fine so I need something to do lol. Is there any advantage to this or does it really matter? Anything else I could add to this new system to keep separate from my unraid server if it&#39;s worth doing?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/McXcelsior"> /u/McXcelsior </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g56s57/traefikauthentik_on_its_own_hardware_or_just_keep/">[link]</a></span> &#32; <span><a href="http

## Restic docker compose help
 - [https://www.reddit.com/r/selfhosted/comments/1g56pwn/restic_docker_compose_help](https://www.reddit.com/r/selfhosted/comments/1g56pwn/restic_docker_compose_help)
 - RSS feed: $source
 - date published: 2024-10-16T18:41:17+00:00

<!-- SC_OFF --><div class="md"><p>Hi can anyone help me get started? I&#39;m trying to build the Restic docker compose but I don&#39;t understand some things.</p> <p><code>services:</code></p> <p><code>restic:</code></p> <p><code>container_name: restic</code></p> <p><code>image: lobaro/restic-backup-docker:latest</code></p> <p><code>hostname: dockervm</code></p> <p><code>privileged: true</code></p> <p><code>volumes:</code></p> <p><code>- /home/docker/esphome/data:/data/esphome:ro</code></p> <p><code>environment:</code></p> <p><code>- RESTIC_REPOSITORY=/home/docker/test1:/storage/path</code></p> <p><code>- RESTIC_PASSWORD=XXX</code></p> <p><code>- BACKUP_CRON=0 22 * * 0</code></p> <p><code>- CHECK_CRON=0 22 * * 3</code></p> <p><code>- RESTIC_FORGET_ARGS=--prune --keep-last 4</code></p> <p><code>restart: always</code></p> <p>I need to mount a volume for the files I want to backup right? so for instance my Esphome app store its files on /home/docker/esphome/data<br/> so I need to mount t

## Introducing Watchwolf: My AI-Powered Server Management App
 - [https://www.reddit.com/r/selfhosted/comments/1g55tqw/introducing_watchwolf_my_aipowered_server](https://www.reddit.com/r/selfhosted/comments/1g55tqw/introducing_watchwolf_my_aipowered_server)
 - RSS feed: $source
 - date published: 2024-10-16T18:03:19+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I wanted to share a project I&#39;ve been working on that might be helpful for fellow self-hosters. It&#39;s called <strong>Watchwolf</strong>, an AI-enhanced app designed to make server management effortless.</p> <p><strong>Background:</strong></p> <p>This app started as a hobby project to help me manage my own servers. Over time, it evolved into a full-fledged product, and I&#39;m excited (and a bit nervous) to share it with you all. This is actually the first app I&#39;ve ever developed!</p> <p><strong>Key Features:</strong></p> <ul> <li><strong>AI Server Assistant:</strong> Leverage advanced AI capabilities to manage and troubleshoot your servers effortlessly. Get intelligent suggestions and optimize server performance with AI-driven insights.</li> <li><strong>Server Monitoring:</strong> Keep a real-time eye on your servers&#39; health with customizable metrics capture modes. Monitor performance metrics, uptime, and resource u

## Wikis (Dokuwiki,Wikijs,etc) for Shop Floor SOP's
 - [https://www.reddit.com/r/selfhosted/comments/1g5582k/wikis_dokuwikiwikijsetc_for_shop_floor_sops](https://www.reddit.com/r/selfhosted/comments/1g5582k/wikis_dokuwikiwikijsetc_for_shop_floor_sops)
 - RSS feed: $source
 - date published: 2024-10-16T17:38:26+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I work in the rail industry and I was wondering if DokuWiki (or any wiki in general) would be a good match for what I have in mind.<br/> Today we basically use Power Point with the Standard Work images on it, every operation has its own page. I like the idea of using wikis so that I can concentrate the Power Point images and many other information from other sources into a single webpage.</p> <p>With that, I&#39;d like to ask:</p> <p>Is there a PDF reader plugin that can be used with DokuWiki of will I have to create several different pages for each image? (I know, sounds dumb but I&#39;m completely knew to the wiki world)</p> <p>Is there a plugin that would enable me to log operation times so that could benchmark my process? Something like a Start/Stop button on each operation maybe. From there I could go into dashboards and have an intricate view from my department.</p> <p>I&#39;ve been searching for wiki templates that deal with the &q

## My dormitory setup
 - [https://www.reddit.com/r/selfhosted/comments/1g54cv2/my_dormitory_setup](https://www.reddit.com/r/selfhosted/comments/1g54cv2/my_dormitory_setup)
 - RSS feed: $source
 - date published: 2024-10-16T17:02:11+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g54cv2/my_dormitory_setup/"> <img src="https://b.thumbs.redditmedia.com/E6vM40JLMdpiwN4kO4Ms_USNCeTFz4_LCjTb2elJ2jo.jpg" alt="My dormitory setup " title="My dormitory setup " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>The white router in the picture is my roommate&#39;s router, link through my ASUS AP, after some routing table tweak, we can transfer files and share media library each other. My router also handles his dns requests.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/WMK9651"> /u/WMK9651 </a> <br/> <span><a href="https://www.reddit.com/gallery/1g54cv2">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g54cv2/my_dormitory_setup/">[comments]</a></span> </td></tr></table>

## Something to send my phone a notification every 10 minutes?
 - [https://www.reddit.com/r/selfhosted/comments/1g545dg/something_to_send_my_phone_a_notification_every](https://www.reddit.com/r/selfhosted/comments/1g545dg/something_to_send_my_phone_a_notification_every)
 - RSS feed: $source
 - date published: 2024-10-16T16:53:37+00:00

<!-- SC_OFF --><div class="md"><p>I need something to send me a notification every 10 minutes so I can be aware of the passage of time, but it can&#39;t be a calendar application because I need the notifications to be different. I want to be able to turn off the reminder notifications, but still hear all of my regular calendar notifications. </p> <p>I did read about <a href="http://ntfy.sh">ntfy.sh</a>, but I&#39;m wondering if someone here has seen something better. Ideally, I don&#39;t need to manually create hundreds of individual events, don&#39;t need to acknowledge the notifications, and have an easy way to pause the notifications.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FormFilter"> /u/FormFilter </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g545dg/something_to_send_my_phone_a_notification_every/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g545dg/something_to_send_

## Personal dormitory AIO setup
 - [https://www.reddit.com/r/selfhosted/comments/1g543pr/personal_dormitory_aio_setup](https://www.reddit.com/r/selfhosted/comments/1g543pr/personal_dormitory_aio_setup)
 - RSS feed: $source
 - date published: 2024-10-16T16:51:41+00:00

<!-- SC_OFF --><div class="md"><p>The white router in the picture 4 is my roommate&#39;s router, link through my ASUS AP, after some routing table tweak, we can transfer files and share media library each other. My router also handles his dns requests.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/WMK9651"> /u/WMK9651 </a> <br/> <span><a href="https://www.reddit.com/gallery/1g543pr">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g543pr/personal_dormitory_aio_setup/">[comments]</a></span>

## What's your preferred cooling method?
 - [https://www.reddit.com/r/selfhosted/comments/1g52y6e/whats_your_preferred_cooling_method](https://www.reddit.com/r/selfhosted/comments/1g52y6e/whats_your_preferred_cooling_method)
 - RSS feed: $source
 - date published: 2024-10-16T16:04:20+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g52y6e/whats_your_preferred_cooling_method/"> <img src="https://b.thumbs.redditmedia.com/dueEtprKm8kElpUv4w_ISsYOxguO-21MZC3PLHeEwQw.jpg" alt="What's your preferred cooling method?" title="What's your preferred cooling method?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Running couple of services in Docker for the past few days, and couldn&#39;t be happier with this fanless setup, temperatures been quite constant. I did stress test and temps went from 40c to 60c after 25 minutes which is really good. Right now, stays around 41-42c. Room temperature is 20C~ everyday</p> <p><a href="https://preview.redd.it/bd7wh0hp35vd1.png?width=561&amp;format=png&amp;auto=webp&amp;s=26f0b34ee48b581eaa00801a2f465eae6ed23e97">https://preview.redd.it/bd7wh0hp35vd1.png?width=561&amp;format=png&amp;auto=webp&amp;s=26f0b34ee48b581eaa00801a2f465eae6ed23e97</a></p> <p>Router also fanless and stays at around 40C currently, althoug

## Question about using Netbird in my home network
 - [https://www.reddit.com/r/selfhosted/comments/1g52x6g/question_about_using_netbird_in_my_home_network](https://www.reddit.com/r/selfhosted/comments/1g52x6g/question_about_using_netbird_in_my_home_network)
 - RSS feed: $source
 - date published: 2024-10-16T16:03:08+00:00

<!-- SC_OFF --><div class="md"><p>TLDR: If I use netbird, I can set it up to only allow http access to my reverse proxy in my flat home network and the only security risk is if someone breaks into the vpn somehow and then also manages to find RCE on one of my exposed services, as the vpn access policies prevent talking to other devices in my flat network?</p> <p>Hello everyone,</p> <p>I have been wanting to get away from hosted storage cloud providers and so on and have setup an old computer I have at home with ubuntu server.</p> <p>Now I have been pondering on how I would like to expose this machine to the outside world. My current problem is that I have a regular consumer fritzbox at home so I can not setup VLans with segmentation. As far as I know even when subnetting the fritzbox just resolves regardless.</p> <p>So segmenting the network currently would require me to get more hardware and use my fritzbox in modem only mode.</p> <p>Now I have heard that Netbird allows me to configu

## access zrok VPN on Android
 - [https://www.reddit.com/r/selfhosted/comments/1g52hgf/access_zrok_vpn_on_android](https://www.reddit.com/r/selfhosted/comments/1g52hgf/access_zrok_vpn_on_android)
 - RSS feed: $source
 - date published: 2024-10-16T15:45:02+00:00

<!-- SC_OFF --><div class="md"><p>is there a way to access zrok VPN share on Android?? I have a game server that needs multiple ports and I want to access that server on Android.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/temaxxx"> /u/temaxxx </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g52hgf/access_zrok_vpn_on_android/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g52hgf/access_zrok_vpn_on_android/">[comments]</a></span>

## Nextcloud on local network
 - [https://www.reddit.com/r/selfhosted/comments/1g513ik/nextcloud_on_local_network](https://www.reddit.com/r/selfhosted/comments/1g513ik/nextcloud_on_local_network)
 - RSS feed: $source
 - date published: 2024-10-16T14:45:31+00:00

<!-- SC_OFF --><div class="md"><p>Has someone been able to set up nextcloud without a domain? I want to use it locally, without exposing it. </p> <p>I&#39;ve been trying to do so for a week or so, with the docker aio image (all in one). I made a pihole Cname, vault.home.local-&gt;home.local, and I reverse proxyed it with Nginx.</p> <p>At first the domain checker docker wouldn&#39;t even start, don&#39;t know why, and when I got it working it just didn&#39;t want to accept the domain, with an error that was cutted on half, like if the error had an error.</p> <p>I&#39;ve tried so many things I don&#39;t even know where to continue now. Maybe it can&#39;t be done? Some help would be fantastic</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/_k4yn5"> /u/_k4yn5 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g513ik/nextcloud_on_local_network/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g

## [META] The duality of (selfhosting) man
 - [https://www.reddit.com/r/selfhosted/comments/1g4zwl3/meta_the_duality_of_selfhosting_man](https://www.reddit.com/r/selfhosted/comments/1g4zwl3/meta_the_duality_of_selfhosting_man)
 - RSS feed: $source
 - date published: 2024-10-16T13:52:40+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g4zwl3/meta_the_duality_of_selfhosting_man/"> <img src="https://external-preview.redd.it/HrLzsDxIWIwkQ_Bh5LxMxtq_OS7Ycg1dX6WYCEnvbmw.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=158f1aaa05ac9ecce90164c2a826f3d6df5a35a0" alt="[META] The duality of (selfhosting) man" title="[META] The duality of (selfhosting) man" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/laxweasel"> /u/laxweasel </a> <br/> <span><a href="https://imgur.com/a/n01w1m0">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4zwl3/meta_the_duality_of_selfhosting_man/">[comments]</a></span> </td></tr></table>

## My dashboard
 - [https://www.reddit.com/r/selfhosted/comments/1g4zg5x/my_dashboard](https://www.reddit.com/r/selfhosted/comments/1g4zg5x/my_dashboard)
 - RSS feed: $source
 - date published: 2024-10-16T13:31:22+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g4zg5x/my_dashboard/"> <img src="https://preview.redd.it/la08uc4ve4vd1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=3e59b8ab48976fa1c93c626470ea85737912bb8f" alt="My dashboard" title="My dashboard" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Spuxilet"> /u/Spuxilet </a> <br/> <span><a href="https://i.redd.it/la08uc4ve4vd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4zg5x/my_dashboard/">[comments]</a></span> </td></tr></table>

## AdventureLog v0.7.0 Update
 - [https://www.reddit.com/r/selfhosted/comments/1g4ywpe/adventurelog_v070_update](https://www.reddit.com/r/selfhosted/comments/1g4ywpe/adventurelog_v070_update)
 - RSS feed: $source
 - date published: 2024-10-16T13:05:29+00:00

<!-- SC_OFF --><div class="md"><p>Hi <a href="/r/selfhosted">r/selfhosted</a>,</p> <p>A few months ago, I announced the release of <strong>AdventureLog</strong>, a self-hostable travel tracker and trip planner. I’ve been blown away by the community’s interactions and the feedback I’ve received. Today, I’m excited to announce the release of <strong>version v0.7.0</strong>, which includes several major changes based on the requests from my initial post.</p> <p>You can check out the full changelog here: <a href="https://github.com/seanmorley15/AdventureLog/releases/tag/v0.7.0">https://github.com/seanmorley15/AdventureLog/releases/tag/v0.7.0</a></p> <p>Looking ahead, I’m currently working on some exciting features like:</p> <ul> <li>Support for multiple languages</li> <li>Integration with Immich to link albums to collections and fetch images from your library</li> <li>The ability to add adventures to multiple collections</li> <li>Adding AdventureLog to self-hosted app store platforms</li>

## [Looking for] Tool for creating aesthetically pleasing tables and diagrams for my Thesis
 - [https://www.reddit.com/r/selfhosted/comments/1g4ysy2/looking_for_tool_for_creating_aesthetically](https://www.reddit.com/r/selfhosted/comments/1g4ysy2/looking_for_tool_for_creating_aesthetically)
 - RSS feed: $source
 - date published: 2024-10-16T13:00:45+00:00

<!-- SC_OFF --><div class="md"><p>For my Thesis I have done a quantitative survey and want to report the results in a somewhat more beautiful way than the output I get from SPSS</p> <p>is there a tool that produces similiar results to <a href="http://flourish.com/">flourish.com</a>?<br/> Because of very weird formatting restrictions the free-tier is not enough to create the kinds of diagrams I want.<br/> I also tried Tableau and Jamovi but their tools don&#39;t seem to work with already finished analysis data and I really don&#39;t want to recreate what I did with SPSS in another software.<br/> There seem to be a lot of tools to create flow sharts.. but tools for Pie-, Bar-, Burstcharts etc. and simple tables seem to be somewhat rarer.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/NakedxCrusader"> /u/NakedxCrusader </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4ysy2/looking_for_tool_for_creating_aesthetically/">[link]

## My Homepage dashboard
 - [https://www.reddit.com/r/selfhosted/comments/1g4ynlw/my_homepage_dashboard](https://www.reddit.com/r/selfhosted/comments/1g4ynlw/my_homepage_dashboard)
 - RSS feed: $source
 - date published: 2024-10-16T12:53:48+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g4ynlw/my_homepage_dashboard/"> <img src="https://preview.redd.it/90rges2284vd1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=bbbb3a067c4184f590cf51db3b6fdbe05de6061f" alt="My Homepage dashboard" title="My Homepage dashboard" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/smplnmnml"> /u/smplnmnml </a> <br/> <span><a href="https://i.redd.it/90rges2284vd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4ynlw/my_homepage_dashboard/">[comments]</a></span> </td></tr></table>

## Hosting LLM on a work server (closed environment)
 - [https://www.reddit.com/r/selfhosted/comments/1g4yizj/hosting_llm_on_a_work_server_closed_environment](https://www.reddit.com/r/selfhosted/comments/1g4yizj/hosting_llm_on_a_work_server_closed_environment)
 - RSS feed: $source
 - date published: 2024-10-16T12:47:21+00:00

<!-- SC_OFF --><div class="md"><p>Hi all! I&#39;ve been looking around and reading some posts here and there trying to learn but not quite understanding everything.</p> <p>I&#39;m interested to host a LLM on a server at my work. The thing is that it has to be very secure and not send any inputs/data outside the LLM but it still should be reachable by employees through a VPN &amp; for example credentials.</p> <p>How can this be self-hosted and only reachable by few and yet have a common LLM that all of us can use?<br/> And about resources, what do you think is enough to use, talking about only using chatbots for summarizing data, documents, share things and code/scripts.</p> <p>And some LLM questions, if someone knows: is it possible to learn the LLM things that we put into the chat but at the same time keep it in our secured so any data doesn&#39;t leave the server?</p> <p>Any help or suggestions is appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.re

## nginx proxy manager is serving the subdomain but not the root doman. How to fix it. I did many things but coudln't
 - [https://www.reddit.com/r/selfhosted/comments/1g4xxvi/nginx_proxy_manager_is_serving_the_subdomain_but](https://www.reddit.com/r/selfhosted/comments/1g4xxvi/nginx_proxy_manager_is_serving_the_subdomain_but)
 - RSS feed: $source
 - date published: 2024-10-16T12:16:07+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g4xxvi/nginx_proxy_manager_is_serving_the_subdomain_but/"> <img src="https://b.thumbs.redditmedia.com/kqxphx_tMsDiDkFBzxMsr07oW2XOYAfNYbdgWcC7bOA.jpg" alt="nginx proxy manager is serving the subdomain but not the root doman. How to fix it. I did many things but coudln't " title="nginx proxy manager is serving the subdomain but not the root doman. How to fix it. I did many things but coudln't " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>example.domain -&gt; cloudflare (not proxied, just the dns) -&gt; ip address of VPS in EC2 instance</p> <p>in the EC2 the only thing I installed is docker and it it I&#39;ve some containers running</p> <p>root url: example.com -&gt; wordpress (do not work. says An error occurred during a connection to example.com:32768.) The screen shot below.</p> <p>subdomains: container.example.com -&gt; resolves container.example.com -&gt; resolves</p> <p>when I pointed containers to roo

## Has anyone used Kamal for deployments?
 - [https://www.reddit.com/r/selfhosted/comments/1g4x8zw/has_anyone_used_kamal_for_deployments](https://www.reddit.com/r/selfhosted/comments/1g4x8zw/has_anyone_used_kamal_for_deployments)
 - RSS feed: $source
 - date published: 2024-10-16T11:37:52+00:00

<!-- SC_OFF --><div class="md"><p>I just published a new video on deploying web applications using Kamal. Is anyone using it to deploy self-hosted applications? Would like to hear your feedback.</p> <p><a href="https://youtu.be/ImqznBAzr_k">https://youtu.be/ImqznBAzr_k</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/der_gopher"> /u/der_gopher </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4x8zw/has_anyone_used_kamal_for_deployments/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4x8zw/has_anyone_used_kamal_for_deployments/">[comments]</a></span>

## Syncing Music Library
 - [https://www.reddit.com/r/selfhosted/comments/1g4vpyr/syncing_music_library](https://www.reddit.com/r/selfhosted/comments/1g4vpyr/syncing_music_library)
 - RSS feed: $source
 - date published: 2024-10-16T09:58:53+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;m looking for a way to store many .mp3 files on a Linux server, and then be able to sync these mp3s over to Windows-based devices. I looked into Navidrome, but I would prefer a solution that allows file uploads via the web interface as well.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hwfire"> /u/hwfire </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4vpyr/syncing_music_library/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4vpyr/syncing_music_library/">[comments]</a></span>

## Help with Docker, Security, and Networking for my Home Server Project
 - [https://www.reddit.com/r/selfhosted/comments/1g4vbkb/help_with_docker_security_and_networking_for_my](https://www.reddit.com/r/selfhosted/comments/1g4vbkb/help_with_docker_security_and_networking_for_my)
 - RSS feed: $source
 - date published: 2024-10-16T09:29:17+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g4vbkb/help_with_docker_security_and_networking_for_my/"> <img src="https://a.thumbs.redditmedia.com/arRCAohBuEoDASj4FNDJrsFWOt2ImDeuUjToPWZAdU0.jpg" alt="Help with Docker, Security, and Networking for my Home Server Project" title="Help with Docker, Security, and Networking for my Home Server Project" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/a3fgnevx43vd1.png?width=709&amp;format=png&amp;auto=webp&amp;s=f6b714268ab10eafeff9e949990c83c6038e23e5">https://preview.redd.it/a3fgnevx43vd1.png?width=709&amp;format=png&amp;auto=webp&amp;s=f6b714268ab10eafeff9e949990c83c6038e23e5</a></p> <p>Hi, newbie here, started 2 months ago,</p> <p>I&#39;m setting up a home server with <strong>Docker containers</strong> on an <strong>Ubuntu Server</strong>, and I need some advice to make sure I&#39;m doing things the right way—both for efficiency and security.</p> <p>Here’s an overview of wha

## New Improved DIY Homelab Setup
 - [https://www.reddit.com/r/selfhosted/comments/1g4ukdy/new_improved_diy_homelab_setup](https://www.reddit.com/r/selfhosted/comments/1g4ukdy/new_improved_diy_homelab_setup)
 - RSS feed: $source
 - date published: 2024-10-16T08:31:34+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g4ukdy/new_improved_diy_homelab_setup/"> <img src="https://b.thumbs.redditmedia.com/7onyyw0qwWJJFLxmyXUTcLlEPWhUC8Q9odTpYfytj0M.jpg" alt="New Improved DIY Homelab Setup" title="New Improved DIY Homelab Setup" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/skewor"> /u/skewor </a> <br/> <span><a href="https://www.reddit.com/gallery/1g4ukdy">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4ukdy/new_improved_diy_homelab_setup/">[comments]</a></span> </td></tr></table>

## Hardware Recommendations for First Home Server
 - [https://www.reddit.com/r/selfhosted/comments/1g4u7qm/hardware_recommendations_for_first_home_server](https://www.reddit.com/r/selfhosted/comments/1g4u7qm/hardware_recommendations_for_first_home_server)
 - RSS feed: $source
 - date published: 2024-10-16T08:03:52+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys!</p> <p>I am finally pulling the degooglefy (de-subscription-fy?) trigger and hosting my own server at home. I would like your suggestions on the CPU and RAM. Here are my plans:</p> <p><strong>Usage -</strong> Ubuntu server running Docker containers (will not run VMs at all) for:</p> <ul> <li>Immich (replace Google Photos) - Daily (3 users)</li> <li>Nextcloud (replace Google Drive) - Daily (2 users)</li> <li>Plex (replace Netflix) - 4K stream (1 device, weekends only) and 4K to 1080P (3 devices at a time)</li> <li>Samba (NAS) - Daily (1 user)</li> </ul> <p><strong>Weekly Off-site Back-up PC (Office)</strong> - Existing Ryzen 7 1700X + 16GB ram + 2 x 2TB HDDs (ZFS mirror)</p> <p><strong>Main Server (Home)</strong> - Build a new one (existing AM4 motherboard, NVIDIA Quadro P400 and SSDs), Ubuntu server with 6 x 500GB SATA SSDs (ZFS Raid-Z2)</p> <p><strong>Question 1 - CPU Options</strong> - Do I go for more cores, higher speeds or something newe

## Immich v1.118.0 breaking change
 - [https://www.reddit.com/r/selfhosted/comments/1g4u61r/immich_v11180_breaking_change](https://www.reddit.com/r/selfhosted/comments/1g4u61r/immich_v11180_breaking_change)
 - RSS feed: $source
 - date published: 2024-10-16T08:00:19+00:00

<!-- SC_OFF --><div class="md"><p>Hello ! I didn&#39;t see a post about it this time so if you update to Immich &gt;= 1.118.0 don&#39;t forget to change the port in your docker-compose file for the immich-server container.</p> <p>From : </p> <pre><code>2283:3001 </code></pre> <p>To : </p> <pre><code>2283:2283 </code></pre> <p>It was enough for me but maybe you have more to do, check the release note that is more complete here : <a href="https://github.com/immich-app/immich/releases/tag/v1.118.0">https://github.com/immich-app/immich/releases/tag/v1.118.0</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/t_i_b"> /u/t_i_b </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4u61r/immich_v11180_breaking_change/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4u61r/immich_v11180_breaking_change/">[comments]</a></span>

## Alternative to Notion: nothing really worthwhile?
 - [https://www.reddit.com/r/selfhosted/comments/1g4twfy/alternative_to_notion_nothing_really_worthwhile](https://www.reddit.com/r/selfhosted/comments/1g4twfy/alternative_to_notion_nothing_really_worthwhile)
 - RSS feed: $source
 - date published: 2024-10-16T07:39:07+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, like many, I am looking for an alternative to Notion to manage my notes and documents locally, with multi-user management for collaborative work. I have tried many solutions, but there is still a problem. Recently, I tried Affine, which I installed in Docker. Surprise, the self-hosted version does not allow multi-users. In addition, for this, the data must be hosted on their cloud.</p> <p>If so, no. I also tested SiYuan, but its Chinese origin worries me, especially after seeing several messages in Chinese during my test. It&#39;s getting cold.</p> <p>As for Obsidian and others, they are good options for installing on a PC, but I&#39;m looking for a solution that can be accessed online through my own server.</p> <p>Do you have any suggestions, perhaps a promising solution that I haven&#39;t explored yet?</p> <p>Thanks in advance :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Amazing-Ranger01">

## nginx proxy manager: version 2.12 available but not listed on github - any details known?
 - [https://www.reddit.com/r/selfhosted/comments/1g4te6p/nginx_proxy_manager_version_212_available_but_not](https://www.reddit.com/r/selfhosted/comments/1g4te6p/nginx_proxy_manager_version_212_available_but_not)
 - RSS feed: $source
 - date published: 2024-10-16T07:00:18+00:00

<!-- SC_OFF --><div class="md"><p>hey</p> <p>on docker hub, there is already nginx proxy manager version 2.12 available - but when i was looking for the release notes on github,, there is still 2.11.3 listed as latest version</p> <p>does anyone know what changed with 2.12? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/IacovHall"> /u/IacovHall </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4te6p/nginx_proxy_manager_version_212_available_but_not/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4te6p/nginx_proxy_manager_version_212_available_but_not/">[comments]</a></span>

## Security Analysis of Vaultwarden and Keepass
 - [https://www.reddit.com/r/selfhosted/comments/1g4t9re/security_analysis_of_vaultwarden_and_keepass](https://www.reddit.com/r/selfhosted/comments/1g4t9re/security_analysis_of_vaultwarden_and_keepass)
 - RSS feed: $source
 - date published: 2024-10-16T06:50:49+00:00

<!-- SC_OFF --><div class="md"><p>In German, use DeepL or Google translate. </p> <p><a href="https://www.bsi.bund.de/DE/Service-Navi/Presse/Alle-Meldungen-News/Meldungen/Codeanalyse-KeePass-Vaultwarden_241014.html">https://www.bsi.bund.de/DE/Service-Navi/Presse/Alle-Meldungen-News/Meldungen/Codeanalyse-KeePass-Vaultwarden_241014.html</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lilolalu"> /u/lilolalu </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4t9re/security_analysis_of_vaultwarden_and_keepass/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4t9re/security_analysis_of_vaultwarden_and_keepass/">[comments]</a></span>

## AdGuard Home DHCP server
 - [https://www.reddit.com/r/selfhosted/comments/1g4t2pq/adguard_home_dhcp_server](https://www.reddit.com/r/selfhosted/comments/1g4t2pq/adguard_home_dhcp_server)
 - RSS feed: $source
 - date published: 2024-10-16T06:36:09+00:00

<!-- SC_OFF --><div class="md"><p>Hi! I have a raspberry pi 4, running AdGuard Home, connected to the router of my ISP provider. As the router doesn’t allow me to change the DNS, I deactivated its DHCP server to use the one from AdGuard Home instead. I configured a static IP on both eth0 and wlan0 interfaces using nmtui. I also use PiVPN to access my home network remotely. But every few minutes my devices lose the connection and then it comes back, etc. (being at home or away via the vpn). When I try to ssh the rpi, I regularly get a timeout or host down but I noticed that it happens only on the eth0 interface (the one used by the DHCP server) and not the wlan0. I tried to use the wlan0 interface for the DHCP server but I get the same behaviour. Any ideas? Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/alex-code"> /u/alex-code </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4t2pq/adguard_home_dhcp_server/">[link]<

## Simple slefhosted cloud solution
 - [https://www.reddit.com/r/selfhosted/comments/1g4svbl/simple_slefhosted_cloud_solution](https://www.reddit.com/r/selfhosted/comments/1g4svbl/simple_slefhosted_cloud_solution)
 - RSS feed: $source
 - date published: 2024-10-16T06:21:11+00:00

<!-- SC_OFF --><div class="md"><p>Hi all I&#39;m looking for a simple self hosted cloud. I tried nextcloud which is pretty cool, but honestly it&#39;s overkill for my needs.</p> <p>I just need somewhere to store my files that is accessible online and perhaps has a viewer/editor that I can use if I need to. Bonus would be if it has an android app, or some way to upload files from my phone.</p> <p>I&#39;m currently using Google drive, but I&#39;m looking to switch.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/masterzeng"> /u/masterzeng </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4svbl/simple_slefhosted_cloud_solution/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4svbl/simple_slefhosted_cloud_solution/">[comments]</a></span>

## Looking for SMS Marketing app that integrates with Twilio
 - [https://www.reddit.com/r/selfhosted/comments/1g4s4la/looking_for_sms_marketing_app_that_integrates](https://www.reddit.com/r/selfhosted/comments/1g4s4la/looking_for_sms_marketing_app_that_integrates)
 - RSS feed: $source
 - date published: 2024-10-16T05:28:35+00:00

<!-- SC_OFF --><div class="md"><p>Hey all- I am looking for a self-hosted tool that is similar to textmagic.com that will allow me to send mass SMS marketing, create lists, etc. while integrating directly with Twilio. Today I use Sendy to send e-mail marketing (which I integrate with Amazon) and I want something similar but for text messaging that allows me to integrate to my Twilio account API.</p> <p>Does something like this exist?</p> <p>Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/eagle101"> /u/eagle101 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4s4la/looking_for_sms_marketing_app_that_integrates/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4s4la/looking_for_sms_marketing_app_that_integrates/">[comments]</a></span>

## Unable to Access Flood, Transmission working fine
 - [https://www.reddit.com/r/selfhosted/comments/1g4s38e/unable_to_access_flood_transmission_working_fine](https://www.reddit.com/r/selfhosted/comments/1g4s38e/unable_to_access_flood_transmission_working_fine)
 - RSS feed: $source
 - date published: 2024-10-16T05:26:01+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I&#39;m hoping someone can help me with this. I recently set up Transmission-CLI on my Debian server to access the web interface remotely, using Tailscale.</p> <p>Transmission is working fine on port 9091, but I want to use <a href="https://github.com/jesec/flood">Flood </a>as the front end because of its cleaner UI. However, when I run <a href="https://github.com/jesec/flood">Flood </a>on port 3000, I can&#39;t access it from any other device on my local network. Using SSH port forwarding (e.g., <code>ssh user@server -L 3000:localhost:3000</code>), I can access the web interface without issues, which makes me think it&#39;s a firewall problem on my server. I’ve already added a rule in <a href="https://wiki.debian.org/Uncomplicated%20Firewall%20%28ufw%29">UFW </a>to allow access to port 3000, so I&#39;m at a bit of a loss as to why I am unable to access the web interface. From what I can see there is no configuration option within 

## QST, a free, complete, open source quiz/exam management system needs some testers!
 - [https://www.reddit.com/r/selfhosted/comments/1g4rtrv/qst_a_free_complete_open_source_quizexam](https://www.reddit.com/r/selfhosted/comments/1g4rtrv/qst_a_free_complete_open_source_quizexam)
 - RSS feed: $source
 - date published: 2024-10-16T05:08:52+00:00

<!-- SC_OFF --><div class="md"><p>QST is the most downloaded open source quiz/exam software at sourceforge.net and we ask the community if they could (over the next week) in their spare time go to qstonline.org and Try a Quiz (hopefully multiple times). - the demo is not phone friendly. </p> <p>We are attempting to give our users better guidance on scaling to large amounts of users and we want to see how our servers and our internet connection handle a heavy load.</p> <p>We are good with thousands of users taking the quiz at the same time.</p> <p>If you find that at times it is unresponsive, please send an email to [<a href="mailto:qstsupport@shaw.ca">qstsupport@shaw.ca</a>](mailto:<a href="mailto:qstsupport@shaw.ca">qstsupport@shaw.ca</a>) with &#39;Slow response&#39; in the subject line. </p> <p>Thank you for allowing us to Post this here. </p> <p>If we have overstepped any rules we understand if you delete this.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www

## Is it a good idea to use a domain that does not contain your name for personal and professional email?
 - [https://www.reddit.com/r/selfhosted/comments/1g4r4fv/is_it_a_good_idea_to_use_a_domain_that_does_not](https://www.reddit.com/r/selfhosted/comments/1g4r4fv/is_it_a_good_idea_to_use_a_domain_that_does_not)
 - RSS feed: $source
 - date published: 2024-10-16T04:23:34+00:00

<!-- SC_OFF --><div class="md"><p>I found a good .com domain name on GoDaddy that is for sale within my budget. I’m tempted to buy it for personal and professional email. However, the domain is not related to my real name or career at all. It’s just a nice, short, and generic english term. I want to go ahead with this but not sure it’s a good idea. What do you think?</p> <p>Updated: The domain is something like “itscool .com”. Memorable but not really professional.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/NiceNites"> /u/NiceNites </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4r4fv/is_it_a_good_idea_to_use_a_domain_that_does_not/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4r4fv/is_it_a_good_idea_to_use_a_domain_that_does_not/">[comments]</a></span>

## "Email for Everyone"
 - [https://www.reddit.com/r/selfhosted/comments/1g4qwm2/email_for_everyone](https://www.reddit.com/r/selfhosted/comments/1g4qwm2/email_for_everyone)
 - RSS feed: $source
 - date published: 2024-10-16T04:10:12+00:00

<!-- SC_OFF --><div class="md"><p>Hi! I have a custom domain and membership website. I would love to offer all my members their own personal email addresses that they can access when they sign up. So, for example, if my website is &quot;world.inc&quot; and &quot;Tommy Lee&quot; signs up, he gets his own <a href="mailto:tommylee@world.inc">tommylee@world.inc</a> address. If Jenny Baker signs up, she gets her own <a href="mailto:jennybaker@world.inc">jennybaker@world.inc</a> address. </p> <p>Is it possible to do this? I have read about MXRoute, Migadu, Cloudflare etc but am not sure if they actually do what I&#39;m talking about. </p> <p>Thanks! :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/austinmediamond"> /u/austinmediamond </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4qwm2/email_for_everyone/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4qwm2/email_for_everyone/">[commen

## I made a website to collect Docker Compose apps
 - [https://www.reddit.com/r/selfhosted/comments/1g4q9b4/i_made_a_website_to_collect_docker_compose_apps](https://www.reddit.com/r/selfhosted/comments/1g4q9b4/i_made_a_website_to_collect_docker_compose_apps)
 - RSS feed: $source
 - date published: 2024-10-16T03:32:31+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m a self-hoster for several years, and was an indie blogger who writes about how to run docker apps (like Noted.lol, Marius Hosting etc.). During the process, I found almost all docker compose apps are set up using these steps (in the point of view of blog article writing),<br/> 1. connect the host via SSH<br/> 2. install docker and docker-compose<br/> 3. make the directory and put in docker-compose.yml and .env file<br/> 4. docker-compose up -d<br/> 5. set up reverse proxy</p> <p>Then I figured why don&#39;t I just collect the docker-compose.yml files, the rest of the steps are pretty easy to complete. So I made this website using Nextra, what do you guys suggest me to do, I&#39;m adding all apps from <a href="http://LinuxServer.io">LinuxServer.io</a> recently.</p> <p><a href="https://awesome-docker-compose.com/">https://awesome-docker-compose.com/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Shawer

## In Immich, How to create new folder for every user to upload their respective photos ?
 - [https://www.reddit.com/r/selfhosted/comments/1g4q7cu/in_immich_how_to_create_new_folder_for_every_user](https://www.reddit.com/r/selfhosted/comments/1g4q7cu/in_immich_how_to_create_new_folder_for_every_user)
 - RSS feed: $source
 - date published: 2024-10-16T03:29:33+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/teja_nune8"> /u/teja_nune8 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4q7cu/in_immich_how_to_create_new_folder_for_every_user/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4q7cu/in_immich_how_to_create_new_folder_for_every_user/">[comments]</a></span>

## Looking for Self-Hosted Indoor Mapping Solutions (Like Google Street View or GoThru )
 - [https://www.reddit.com/r/selfhosted/comments/1g4pusp/looking_for_selfhosted_indoor_mapping_solutions](https://www.reddit.com/r/selfhosted/comments/1g4pusp/looking_for_selfhosted_indoor_mapping_solutions)
 - RSS feed: $source
 - date published: 2024-10-16T03:10:00+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone! I&#39;m looking to set up an indoor mapping system, similar to Google Street View, where people can easily search for and navigate to items or rooms. Does anyone know of any self-hosted tools or solutions for this? I&#39;d appreciate any suggestions or experiences!</p> <p>I checked out GoThru, which seems perfect solution, but it&#39;s not self-hosted and a bit pricey</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ubeyou"> /u/ubeyou </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4pusp/looking_for_selfhosted_indoor_mapping_solutions/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4pusp/looking_for_selfhosted_indoor_mapping_solutions/">[comments]</a></span>

## Self Hosted Tailscale Altnerative
 - [https://www.reddit.com/r/selfhosted/comments/1g4prll/self_hosted_tailscale_altnerative](https://www.reddit.com/r/selfhosted/comments/1g4prll/self_hosted_tailscale_altnerative)
 - RSS feed: $source
 - date published: 2024-10-16T03:05:06+00:00

<!-- SC_OFF --><div class="md"><p>I am in a double NAT situation currently (landlord controls router and mine is downstream of theirs) and am using Tailscale to host several game servers. Would it be possible for me to go the self hosted route with this? I know Headscale exists but it seems like I would need to be able to port forward to set up a coordination server to begin with, so if anyone has ever been in a similar situation what options do I have?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rhino_biome"> /u/rhino_biome </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4prll/self_hosted_tailscale_altnerative/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4prll/self_hosted_tailscale_altnerative/">[comments]</a></span>

## Self Hosted Overlay Network Alternatives
 - [https://www.reddit.com/r/selfhosted/comments/1g4ppyx/self_hosted_overlay_network_alternatives](https://www.reddit.com/r/selfhosted/comments/1g4ppyx/self_hosted_overlay_network_alternatives)
 - RSS feed: $source
 - date published: 2024-10-16T03:02:32+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been using Tailscale for a bit and its been great, but now I want to host my own overlay network. From what I understand you need a coordination server and then a protocol to replace Tailscale.<br/> 1. I am in a Double NAT situation is it possible for me to set up a coordination server(something like Headscale) still?</p> <ol> <li>After a coordination server is setup I have to manually setup wireguard correct?<br/></li> </ol> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rhino_biome"> /u/rhino_biome </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4ppyx/self_hosted_overlay_network_alternatives/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4ppyx/self_hosted_overlay_network_alternatives/">[comments]</a></span>

## Wireguard traefik
 - [https://www.reddit.com/r/selfhosted/comments/1g4p2gn/wireguard_traefik](https://www.reddit.com/r/selfhosted/comments/1g4p2gn/wireguard_traefik)
 - RSS feed: $source
 - date published: 2024-10-16T02:27:08+00:00

<!-- SC_OFF --><div class="md"><p>Would it make sense to host a reverse proxy on a VPS with a client connection over wireguard to the machine hosting services? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/GroundbreakingAd220"> /u/GroundbreakingAd220 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4p2gn/wireguard_traefik/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4p2gn/wireguard_traefik/">[comments]</a></span>

## Rate my closet setup
 - [https://www.reddit.com/r/selfhosted/comments/1g4ov8t/rate_my_closet_setup](https://www.reddit.com/r/selfhosted/comments/1g4ov8t/rate_my_closet_setup)
 - RSS feed: $source
 - date published: 2024-10-16T02:16:25+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g4ov8t/rate_my_closet_setup/"> <img src="https://preview.redd.it/e7wwohrf21vd1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=e4961e366825d89607691ad95b11633a3902818d" alt="Rate my closet setup" title="Rate my closet setup" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>It&#39;s hard to see everything but here&#39;s what I have</p> <p>Cyberpower Backup battery </p> <p>Arris Cable modem</p> <p>Dlink 16 port switch </p> <p>Asus rog router</p> <p>MinisForum Venus </p> <p>Lorex nvr</p> <p>HDHomeRun</p> <p>Ooma voip router</p> <p>OTA antenna splitter </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ghost_in_a_jar_c137"> /u/ghost_in_a_jar_c137 </a> <br/> <span><a href="https://i.redd.it/e7wwohrf21vd1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4ov8t/rate_my_closet_setup/">[comments]</a></span> </td></tr></table>

## HON95/prometheus-nut-exporter over VPN
 - [https://www.reddit.com/r/selfhosted/comments/1g4ole5/hon95prometheusnutexporter_over_vpn](https://www.reddit.com/r/selfhosted/comments/1g4ole5/hon95prometheusnutexporter_over_vpn)
 - RSS feed: $source
 - date published: 2024-10-16T02:02:29+00:00

<!-- SC_OFF --><div class="md"><p>Hey folks,</p> <p>Looking for a little help.</p> <p>I have 7 RPIs which are using NUT to monitor Eaton UPS&#39;s. NUT has been installed using docker and HON95&#39;s prometheus-nut-exporter. </p> <p>The RPI i am using is connected to the internet using a RAK2013 4G LTE hat. </p> <p><a href="https://www.iot-store.com.au/products/rak-raspberry-pi-4b-4gb-kit-lte">https://www.iot-store.com.au/products/rak-raspberry-pi-4b-4gb-kit-lte</a></p> <p>I have an AZURE server which i am hosting Grafana and wireguard on.</p> <p>Would anyone be able to point me in the right direction on how to set up Prometheus to send the metrics scraped from the UPS&#39;s to the Azure server over the wireguard tunnel. </p> <p>Thanks friends</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Far_Plastic_8460"> /u/Far_Plastic_8460 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4ole5/hon95prometheusnutexporter_over_vpn/">[l

## In the warm darkness of my server closet, old forgotten drives find no deliverance
 - [https://www.reddit.com/r/selfhosted/comments/1g4ok8p/in_the_warm_darkness_of_my_server_closet_old](https://www.reddit.com/r/selfhosted/comments/1g4ok8p/in_the_warm_darkness_of_my_server_closet_old)
 - RSS feed: $source
 - date published: 2024-10-16T02:00:57+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g4ok8p/in_the_warm_darkness_of_my_server_closet_old/"> <img src="https://preview.redd.it/n2hmkkwdz0vd1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=236a185e7700a78590b924632fdd2c597b877f75" alt="In the warm darkness of my server closet, old forgotten drives find no deliverance" title="In the warm darkness of my server closet, old forgotten drives find no deliverance" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Gooseheaded"> /u/Gooseheaded </a> <br/> <span><a href="https://i.redd.it/n2hmkkwdz0vd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g4ok8p/in_the_warm_darkness_of_my_server_closet_old/">[comments]</a></span> </td></tr></table>

