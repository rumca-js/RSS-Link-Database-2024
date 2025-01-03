# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Root on NVME, and LVG on external disks. How to use LVG on another machine or new root install?
 - [https://www.reddit.com/r/selfhosted/comments/1gycxu2/root_on_nvme_and_lvg_on_external_disks_how_to_use](https://www.reddit.com/r/selfhosted/comments/1gycxu2/root_on_nvme_and_lvg_on_external_disks_how_to_use)
 - RSS feed: $source
 - date published: 2024-11-23T23:26:08+00:00

<!-- SC_OFF --><div class="md"><p>So I&#39;ve got my selfhosted server with a 1tb nvme drive and mapped a large volume group of my external drives (42tb, i know i have a data hoarding problem). I use this for storing..... uhh.. um. lots of over the air (OTA) recordings from my Silicon Dust HD Homerun and some stuff from these things that end in *arr that require files from (waves arms towards the sky) &#39;the cloud&#39; that get downloaded and then pieced together on the nvme, and when done, moved to the LVG. Admittingly I&#39;m terrible at comprehending the ins and outs of Linux and rely on LOTS of google searches to help me figure out what i&#39;m doing. But it has benefitted me a lot, as most of what I do run in containers and a nice and neat docker-compose.yml. That being said, there&#39;s really no big loss for me to do a reformat on my nvme disk. So is it possible to do a clean install of ubuntu server on my nvme disk and have it recognize the already existing large volume gro

## DHCP Server with simple GUI
 - [https://www.reddit.com/r/selfhosted/comments/1gycuyk/dhcp_server_with_simple_gui](https://www.reddit.com/r/selfhosted/comments/1gycuyk/dhcp_server_with_simple_gui)
 - RSS feed: $source
 - date published: 2024-11-23T23:22:29+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m currently running a separate Adguard Home instance that just does DHPC.. and whilst it works fine, it&#39;s not perfect and running a full adguard home instane is a little over kill..</p> <p>My main requirement is to be able to easily manage DHCP reservations.... a simple list i can order by any column, edit etc..</p> <p>I&#39;ve tried Webmin but it doesn&#39;t display a list and i&#39;ve got no way to easily import my existing reservations..</p> <p>Does anyone have any suggestions?</p> <p>Edit : To clarify why i run a seperate instance for DHCP.. i have 2 other adguard home servers which are synced together. If one of those was my DHCP server i&#39;d have all sorts of issues with all of a sudden there being 2! (unless again.. someone can tell me how to avoid that!)</p> <p>Edit 2 : OK so i can configure AdGuardHomeSync to not sync DHCP settings.. so there&#39;s that.. BUT... is there an alternative gui?</p> </div><!-- SC_ON --> &#32; submitte

## How to Share a License Server Over VPN / Tunnel on windows?
 - [https://www.reddit.com/r/selfhosted/comments/1gycoqm/how_to_share_a_license_server_over_vpn_tunnel_on](https://www.reddit.com/r/selfhosted/comments/1gycoqm/how_to_share_a_license_server_over_vpn_tunnel_on)
 - RSS feed: $source
 - date published: 2024-11-23T23:14:46+00:00

<!-- SC_OFF --><div class="md"><p>I have a Windows VM that runs 24/7 and hosts a specific license server on <code>localhost:port</code>. My goal is to share access to this license server over a VPN. Here’s what I’ve tried and the constraints I’m facing:</p> <ol> <li><strong>Ngrok:</strong> Works for exposing the port but is open to everyone and doesn’t provide a safer static IP with the free tier.</li> <li><strong>Zerotier:</strong> Works well but has a 10-user limit, and I need support for more </li> </ol> <p>Nested virtualization is not enabled, so I cannot run Docker or WSL to host controllers like Headscale or Zerotier controller.</p> <p>I&#39;m open to using WireGuard or similar solutions to create a tunnel to my server but am unsure how to set it up or if they even fit my needs.</p> <p>Is there a way to self-host a VPN controller, or an alternative approach to achieve this securely and with minimal dependency on paid tiers or external services? Any guidance or suggestions would

## Free Self-Hosted Facebook Messenger Bot (No AI, Google Sheets Integration)
 - [https://www.reddit.com/r/selfhosted/comments/1gybmlv/free_selfhosted_facebook_messenger_bot_no_ai](https://www.reddit.com/r/selfhosted/comments/1gybmlv/free_selfhosted_facebook_messenger_bot_no_ai)
 - RSS feed: $source
 - date published: 2024-11-23T22:25:37+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I&#39;m looking for a free, self-hosted solution for a Facebook Messenger bot. I don&#39;t need any advanced AI features, just a simple bot that can send pre-written messages based on certain triggers or user input.</p> <p>Ideally, I&#39;d like to be able to integrate the bot with Google Sheets to store and retrieve information.</p> <p>Does anyone know of any options that fit this description? Any help or suggestions would be greatly appreciated.</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BugFun9706"> /u/BugFun9706 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gybmlv/free_selfhosted_facebook_messenger_bot_no_ai/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gybmlv/free_selfhosted_facebook_messenger_bot_no_ai/">[comments]</a></span>

## Selfhosted Docker Data Backup
 - [https://www.reddit.com/r/selfhosted/comments/1gybmjj/selfhosted_docker_data_backup](https://www.reddit.com/r/selfhosted/comments/1gybmjj/selfhosted_docker_data_backup)
 - RSS feed: $source
 - date published: 2024-11-23T22:25:33+00:00

<!-- SC_OFF --><div class="md"><p>Hi Everyone,</p> <p>Most of my dockers (Hoarder, Automatish, etc) have their DATA mounting point inside /var/lib/docker/volumes/xxxxx</p> <p>Is it enough to backup everything that is inside this /var/lib/docker/volumes/ every night and I will be good to go ?</p> <p>Thank you !</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mcgaleti"> /u/mcgaleti </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gybmjj/selfhosted_docker_data_backup/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gybmjj/selfhosted_docker_data_backup/">[comments]</a></span>

## Crowdsec for Overseer (with Traefik)
 - [https://www.reddit.com/r/selfhosted/comments/1gybjb6/crowdsec_for_overseer_with_traefik](https://www.reddit.com/r/selfhosted/comments/1gybjb6/crowdsec_for_overseer_with_traefik)
 - RSS feed: $source
 - date published: 2024-11-23T22:21:32+00:00

<!-- SC_OFF --><div class="md"><p>Ive got overseer setup via Traefik for external access.</p> <p>ive also got crowdsec working with Traefik, using the collections: crowdsecurity/traefik and crowdsecurity/http-cve</p> <p>Ive just seem they do a collection for overserr (<a href="https://app.crowdsec.net/hub/author/LePresidente/collections/overseerr">https://app.crowdsec.net/hub/author/LePresidente/collections/overseerr</a>) shall I set this up too or leave it with the collections I have?</p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bigup7"> /u/bigup7 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gybjb6/crowdsec_for_overseer_with_traefik/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gybjb6/crowdsec_for_overseer_with_traefik/">[comments]</a></span>

## How do I enable username:password in Postfix?
 - [https://www.reddit.com/r/selfhosted/comments/1gyb8gp/how_do_i_enable_usernamepassword_in_postfix](https://www.reddit.com/r/selfhosted/comments/1gyb8gp/how_do_i_enable_usernamepassword_in_postfix)
 - RSS feed: $source
 - date published: 2024-11-23T22:07:59+00:00

<!-- SC_OFF --><div class="md"><p>Hello!</p> <p>Earlier today I installed Postfix on my system, however I&#39;ve discovered that anyone from anywhere in the world can use my server to send emails, so I want to stop that by using username password authentication.</p> <p>I&#39;ve been looking all day online but I can&#39;t seem to find a solution that doesn&#39;t involve relays (I don&#39;t want to relay, I want to send from my server).</p> <p>Can anyone help? (Ubuntu 24.04)</p> <p>TIA</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Deve_roonie"> /u/Deve_roonie </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gyb8gp/how_do_i_enable_usernamepassword_in_postfix/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gyb8gp/how_do_i_enable_usernamepassword_in_postfix/">[comments]</a></span>

## CSS for homepage (dashboard)
 - [https://www.reddit.com/r/selfhosted/comments/1gya9aa/css_for_homepage_dashboard](https://www.reddit.com/r/selfhosted/comments/1gya9aa/css_for_homepage_dashboard)
 - RSS feed: $source
 - date published: 2024-11-23T21:23:37+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gya9aa/css_for_homepage_dashboard/"> <img src="https://b.thumbs.redditmedia.com/5bLEVuELGGjEBBOrFkD7EuxcoC40bIqOgYG5Rk4mPEM.jpg" alt="CSS for homepage (dashboard)" title="CSS for homepage (dashboard)" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Updated the custom.css for homepage to try and match the glance Catppuccin Frappe theme</p> <p>It was a lot of trial and error - no doubt there redundant code - it does work though :-)</p> <p><a href="https://preview.redd.it/6tyaa223yp2e1.png?width=1275&amp;format=png&amp;auto=webp&amp;s=374fb00ef18275ee78f3aaf219978af191bbc1e2">https://preview.redd.it/6tyaa223yp2e1.png?width=1275&amp;format=png&amp;auto=webp&amp;s=374fb00ef18275ee78f3aaf219978af191bbc1e2</a></p> <p><code>/* Root variables for custom colour palette */</code></p> <p><code>:root {</code></p> <p><code>/* Custom colour palette */</code></p> <p><code>--background-color: hsl(229, 19%, 23%); /* Main backg

## How can I keep track of my VPS's bandwidth usage?
 - [https://www.reddit.com/r/selfhosted/comments/1gya8u9/how_can_i_keep_track_of_my_vpss_bandwidth_usage](https://www.reddit.com/r/selfhosted/comments/1gya8u9/how_can_i_keep_track_of_my_vpss_bandwidth_usage)
 - RSS feed: $source
 - date published: 2024-11-23T21:23:04+00:00

<!-- SC_OFF --><div class="md"><p>I use a tiny VPS connected via wireguard to my homeserver to run a reverse proxy to serve Jellyfin to my friends. I managed to max out the bandwidth quota for the month and I want to make sure that was all the remote Jellyfin connections and not something else wasting bandwidth.</p> <p>To be clear I can see the bandwidth usage by amount in the VPS panel; I want to be able to track what processes/connections/whatever are using X amount of GB each day. Is there anything like that?</p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ambiance6462"> /u/ambiance6462 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gya8u9/how_can_i_keep_track_of_my_vpss_bandwidth_usage/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gya8u9/how_can_i_keep_track_of_my_vpss_bandwidth_usage/">[comments]</a></span>

## Cloudflare Tunnel, Port Forwarding or DDNS?
 - [https://www.reddit.com/r/selfhosted/comments/1gya7p0/cloudflare_tunnel_port_forwarding_or_ddns](https://www.reddit.com/r/selfhosted/comments/1gya7p0/cloudflare_tunnel_port_forwarding_or_ddns)
 - RSS feed: $source
 - date published: 2024-11-23T21:21:41+00:00

<!-- SC_OFF --><div class="md"><p>After finally upgrading my very basic &quot;homelab&quot; setup - running everything off a NAS - to now having a dedicated PC to run as much as possible self-hosted in Docker containers, I have finally begun delving into networking such as Nginx Proxy Manager and Pi-hole.</p> <p>I like to take my time crafting my perfect Docker environment, scrutinising every Compose.yaml and I&#39;m now at the point of connecting a GoDaddy domain I own (we&#39;ll call it... <strong>homelab.com</strong>) to many of my services in order to access them from outside my LAN, without having to constantly connect to <del>Tailscale</del> -insert VPN name here-.</p> <p>My thoughts are to use a subdomain such as <strong><em>portainer</em></strong><strong>.homelab.com</strong> or <strong>homelab.com/</strong><strong><em>portainer</em></strong> - I don&#39;t believe either would matter but keen to hear opinions on this! On second thought, it&#39;d be great to simply use <strong

## Taking advantage of ZFS for smarter Proxmox backups
 - [https://www.reddit.com/r/selfhosted/comments/1gya5qh/taking_advantage_of_zfs_for_smarter_proxmox](https://www.reddit.com/r/selfhosted/comments/1gya5qh/taking_advantage_of_zfs_for_smarter_proxmox)
 - RSS feed: $source
 - date published: 2024-11-23T21:19:22+00:00

<!-- SC_OFF --><div class="md"><p>Excellent <a href="https://blog.guillaumematheron.fr/2023/261/taking-advantage-of-zfs-for-smarter-proxmox-backups/">post from Guillaume Matheron</a> on backing up the smarter ZFS way.</p> <blockquote> <p>Let’s say we have a Proxmox cluster running ~30 VMs using ZFS as a storage backend. We want to backup each VM hourly to a remote server, and then replicate these backups to an offsite server.</p> <p>Proxmox Backup Server is nicely integrated into PVE’s web GUI, and can work with ZFS volumes. However, PBS is storage-agnostic, and as such it does not take advantage of snapshots and implements de-duplication using a chunk store indexed by checksum. This means that only the modified portions of a volume need to be transferred over the network to the backup server.</p> <p>However, the full volume must still be read from disk for each backup to compute the chunk hashes and determine whether they need to be copied. PVE is able to maintain an index of change

## encryption across the board
 - [https://www.reddit.com/r/selfhosted/comments/1gy9jdm/encryption_across_the_board](https://www.reddit.com/r/selfhosted/comments/1gy9jdm/encryption_across_the_board)
 - RSS feed: $source
 - date published: 2024-11-23T20:52:02+00:00

<!-- SC_OFF --><div class="md"><p>I have been trying to protect my data against theft with encryption at rest, but I have a lot of problems trying to do this. Let me explain my environment briefly, and go from there.</p> <p>I have TrueNAS w/ encryption pass-phrase, so I need to manually unlock it. I have a backup TrueNAS used with data replication that maintains locked state so the volumes are never unlocked here. This provides good security if the server is taken, as you need to manually unlock upon boot.</p> <p>I have a proxmox cluster with two nodes and one qdevice for quorum. This is where my problem lies. I love Proxmox and I love having fail-over here with a very simple infrastructure to maintain. It also does a great job of giving me an additional layer of backups as it handles backups so well.</p> <p>Everything in proxmox I consider unsafe as there is no encryption and any use of the TrueNAS for storage would result in storing access so it can access the NAS, so I know none o

## How can I stream videos from Google Photos using shared links?
 - [https://www.reddit.com/r/selfhosted/comments/1gy9601/how_can_i_stream_videos_from_google_photos_using](https://www.reddit.com/r/selfhosted/comments/1gy9601/how_can_i_stream_videos_from_google_photos_using)
 - RSS feed: $source
 - date published: 2024-11-23T20:35:13+00:00

<!-- SC_OFF --><div class="md"><p>I’m new to Jellyfin and would like to stream videos from my Google Photos account through Jellyfin because I find Google Photos frustrating to use. My question is: does Jellyfin support streaming shared links from Google Photos? If so, how can I set it up?</p> <p>Additionally, I have videos stored on my website (e.g., <code>https://example.com/video.mp4</code>) that I also want to stream through Jellyfin. Is it possible to add those links to Jellyfin and stream them without downloading the videos or using up storage space on my Jellyfin server?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CodeCracker_65"> /u/CodeCracker_65 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy9601/how_can_i_stream_videos_from_google_photos_using/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy9601/how_can_i_stream_videos_from_google_photos_using/">[comments]</a></sp

## Do you stop using the browser's native bookmark manager once you deploy a bookmark manager service?
 - [https://www.reddit.com/r/selfhosted/comments/1gy8h5f/do_you_stop_using_the_browsers_native_bookmark](https://www.reddit.com/r/selfhosted/comments/1gy8h5f/do_you_stop_using_the_browsers_native_bookmark)
 - RSS feed: $source
 - date published: 2024-11-23T20:04:31+00:00

<!-- SC_OFF --><div class="md"><p>Currently I&#39;m trying to incorporate bookmark synchrosation on ungoogled-chromium and use floccus+linkwarden. Floccus implements the bridge between ease of access of bookmark manager on the browser, and Linkwarden which provides archiving capability.</p> <p>The workflow on Cromite for Android still is disjointed as Chrome doesn&#39;t support extensions on Android.</p> <p>For users, who are using using selfhosted bookmark managers, do you eventually stop using built-in browser bookmark managers and use the app&#39;s browser extension to add new links?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/localhost-127"> /u/localhost-127 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy8h5f/do_you_stop_using_the_browsers_native_bookmark/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy8h5f/do_you_stop_using_the_browsers_native_bookmark/">[comments]</a><

## Migrating to rootless docker
 - [https://www.reddit.com/r/selfhosted/comments/1gy85am/migrating_to_rootless_docker](https://www.reddit.com/r/selfhosted/comments/1gy85am/migrating_to_rootless_docker)
 - RSS feed: $source
 - date published: 2024-11-23T19:49:40+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been running my docker containers as root because I didn&#39;t know better. I now do and wish to migrate my infrastructure to rootless docker. Since I want minimal downtime and headache: what issues am I likely to run into, and how can I best avoid them? (I do, for instance, have some services like Homepage and Portainer that need access to the docker socket, although I&#39;ve already proxied that using <a href="https://github.com/Tecnativa/docker-socket-proxy">docker socket proxy</a>).</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Routine_Librarian330"> /u/Routine_Librarian330 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy85am/migrating_to_rootless_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy85am/migrating_to_rootless_docker/">[comments]</a></span>

## Does anyone have Terms of Service?
 - [https://www.reddit.com/r/selfhosted/comments/1gy7pmp/does_anyone_have_terms_of_service](https://www.reddit.com/r/selfhosted/comments/1gy7pmp/does_anyone_have_terms_of_service)
 - RSS feed: $source
 - date published: 2024-11-23T19:30:28+00:00

<!-- SC_OFF --><div class="md"><p>Does anyone have some sort of &#39;Terms of Service&#39; or a &#39;Privacy Policy&#39; for publicly facing personal websites hosted in California?</p> <p>Currently I only have a few static webpages and a nextcloud instance publicly accessible through the internet. I&#39;m looking for a simple model for terms that&#39;s short, easy to read, limits any legal liability, and enforces my robots.txt file to prevent tech companies from using my content (blog text, images, etc) without prior written consent. I&#39;d also love to add a detailed privacy policy that&#39;s not vague and notes my logging practices and any external services I use. Any advice, suggestions, and templates are much appreciated!</p> <p>I know adding terms won&#39;t have any real impact on big tech, webcrawlers, bad actors, etc, but I still want to publicly note my dissent for such practices, and preserve my right to sue to whatever extent possible under California law. Even if it&#39;d

## Hostinger VPS 30mbps
 - [https://www.reddit.com/r/selfhosted/comments/1gy7njb/hostinger_vps_30mbps](https://www.reddit.com/r/selfhosted/comments/1gy7njb/hostinger_vps_30mbps)
 - RSS feed: $source
 - date published: 2024-11-23T19:27:55+00:00

<!-- SC_OFF --><div class="md"><p>I’m thinking of buying hostinger vps mostly kvm2. I’m just concerned with their speed 300mbps when other providers offer 1gbps. Is 300mbps slow?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Crypto_King99"> /u/Crypto_King99 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy7njb/hostinger_vps_30mbps/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy7njb/hostinger_vps_30mbps/">[comments]</a></span>

## Self-Hosting MUX Data for Analytics
 - [https://www.reddit.com/r/selfhosted/comments/1gy7aly/selfhosting_mux_data_for_analytics](https://www.reddit.com/r/selfhosted/comments/1gy7aly/selfhosting_mux_data_for_analytics)
 - RSS feed: $source
 - date published: 2024-11-23T19:12:26+00:00

<!-- SC_OFF --><div class="md"><p>I’m running a small SaaS and want to offload MUX data (free tier, 35-day retention) for long-term storage and analytics. My goal is to self-host or save locally (avoiding cloud costs) and later load the data into Google Data Studio for visualization. What’s the best way to achieve this? Looking for cost-effective and efficient solutions!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Forward_Tackle_6487"> /u/Forward_Tackle_6487 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy7aly/selfhosting_mux_data_for_analytics/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy7aly/selfhosting_mux_data_for_analytics/">[comments]</a></span>

## University project inspiration sought
 - [https://www.reddit.com/r/selfhosted/comments/1gy6ozm/university_project_inspiration_sought](https://www.reddit.com/r/selfhosted/comments/1gy6ozm/university_project_inspiration_sought)
 - RSS feed: $source
 - date published: 2024-11-23T18:46:33+00:00

<!-- SC_OFF --><div class="md"><p>May I pick your brains? I&#39;m looking for some ideas for my degree project, I&#39;m not very imaginative. I have my CCNA and I have a home lab setup, I&#39;m also doing web development with Typescript, React, FastAPI amongst others. I&#39;m thinking along the lines of creating a website with something network or home lab related, maybe something related to Docker possibly.</p> <p>Any and all ideas would be appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CantaloupeForty"> /u/CantaloupeForty </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy6ozm/university_project_inspiration_sought/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy6ozm/university_project_inspiration_sought/">[comments]</a></span>

## Selfhosted powerfull LLM anyone?
 - [https://www.reddit.com/r/selfhosted/comments/1gy6ejy/selfhosted_powerfull_llm_anyone](https://www.reddit.com/r/selfhosted/comments/1gy6ejy/selfhosted_powerfull_llm_anyone)
 - RSS feed: $source
 - date published: 2024-11-23T18:34:18+00:00

<!-- SC_OFF --><div class="md"><p>There are some open-source LLMs available, but some of them definitely aren&#39;t suitable for regular consumer-grade hardware. I’m wondering if anyone has had success self-hosting them especially from the hardware perspective?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Yarkm13"> /u/Yarkm13 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy6ejy/selfhosted_powerfull_llm_anyone/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy6ejy/selfhosted_powerfull_llm_anyone/">[comments]</a></span>

## Best Way to do Local DNS; separate domain?
 - [https://www.reddit.com/r/selfhosted/comments/1gy5k1x/best_way_to_do_local_dns_separate_domain](https://www.reddit.com/r/selfhosted/comments/1gy5k1x/best_way_to_do_local_dns_separate_domain)
 - RSS feed: $source
 - date published: 2024-11-23T17:57:59+00:00

<!-- SC_OFF --><div class="md"><p>So I’ve had local dns running and since I’m on iPhone/Mac I’m fighting to keep things in my tailnet running without getting constant (I’m on cloudflare) so cloudflare dns resolution failures. </p> <p>Is a better suggestion to just use two domains? </p> <p>One local. One Internet based?</p> <p>Foobaronline.com and foobarlocal.com?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bm_preston"> /u/bm_preston </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy5k1x/best_way_to_do_local_dns_separate_domain/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy5k1x/best_way_to_do_local_dns_separate_domain/">[comments]</a></span>

## Monitoring a Self-hosted HealthChecks.io instance
 - [https://www.reddit.com/r/selfhosted/comments/1gy5eh5/monitoring_a_selfhosted_healthchecksio_instance](https://www.reddit.com/r/selfhosted/comments/1gy5eh5/monitoring_a_selfhosted_healthchecksio_instance)
 - RSS feed: $source
 - date published: 2024-11-23T17:51:09+00:00

<!-- SC_OFF --><div class="md"><p>I recently started my self-hosting journey and installed HealthChecks using Portainer. I immediately realised that I would need to monitor it&#39;s uptime as well. It wasn&#39;t as simple as I had initially thought. I have documented the entire thing in this blog post.</p> <p><a href="https://blog.haideralipunjabi.com/posts/monitoring-self-hosted-healthchecks-io">https://blog.haideralipunjabi.com/posts/monitoring-self-hosted-healthchecks-io</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dJones176"> /u/dJones176 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy5eh5/monitoring_a_selfhosted_healthchecksio_instance/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy5eh5/monitoring_a_selfhosted_healthchecksio_instance/">[comments]</a></span>

## Weird problem with local DNS and can't fix it
 - [https://www.reddit.com/r/selfhosted/comments/1gy4we2/weird_problem_with_local_dns_and_cant_fix_it](https://www.reddit.com/r/selfhosted/comments/1gy4we2/weird_problem_with_local_dns_and_cant_fix_it)
 - RSS feed: $source
 - date published: 2024-11-23T17:29:06+00:00

<!-- SC_OFF --><div class="md"><p>I have a very strange problem with my local dns and I&#39;m really hoping someone has a suggestion. </p> <p>I have a local server running ubuntu with several docker containers. One of those containers is nginx proxy manager. I have my domain through cloudflare and obtained ssl certs with a dns challenge. In my router/firewall (brand is firewalla), I set custom dns to point my domain and subdomains directly to my server running npm. So far this has worked great.</p> <p>However, the second I add any dns records in cloudflare (A record or any cname), my local dns stops resolving. If I run dig <a href="http://domain.com">domain.com</a> @192.168.1.1 (my router), it correctly returns my npm server ip and that&#39;s where it should be sending traffic. I can even put a dns record in cloudflare pointing to google&#39;s ip address and I will still hit google if I point my browser towards my domain. It seems to be clearly bypassing my local dns somehow. If I go

## Beginner here- Need some advice for homelab
 - [https://www.reddit.com/r/selfhosted/comments/1gy4sdy/beginner_here_need_some_advice_for_homelab](https://www.reddit.com/r/selfhosted/comments/1gy4sdy/beginner_here_need_some_advice_for_homelab)
 - RSS feed: $source
 - date published: 2024-11-23T17:24:09+00:00

<!-- SC_OFF --><div class="md"><p>Beginner here. Currently running a RPi-4 for selfhosted apps (n8n, Homeassistant, Jellyfin). Although I am using several RPi&#39;s but I have to say that the RPi really struggles playing movies. That gave me the idea of investing in something a bit more powerful. My knowledge about self-hosted apps is limited so this is where I need your advice. </p> <p>I am aware more is better but what is the minimum RAM amount that would take care of 80% of selfhosted apps running together in one system for a beginner like myself? I have been running Dietpi on the RPi-4 8GB and I&#39;ve seen that N8n + Jellyfin barely reaches 1GB. I have thought of the Mack Mini M4 but after 16GB the price goes nuts. </p> <p>Second question- I am using Dietpi because it is light and it let&#39;s me install several selfhosted apps easily. Just yesterday I discovered Runtipi, which has a much better collection of apps and also easy to run. Is it a good choice for a beginner like mys

## Alternatives to Untappd?
 - [https://www.reddit.com/r/selfhosted/comments/1gy48f0/alternatives_to_untappd](https://www.reddit.com/r/selfhosted/comments/1gy48f0/alternatives_to_untappd)
 - RSS feed: $source
 - date published: 2024-11-23T17:00:28+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone I am looking for a selfhosted beer tracker, and making a list of the ones I like. Something like untappd.</p> <p>does anyone have a good docker container for this?</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ZionDaWolfo"> /u/ZionDaWolfo </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy48f0/alternatives_to_untappd/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy48f0/alternatives_to_untappd/">[comments]</a></span>

## My first home server
 - [https://www.reddit.com/r/selfhosted/comments/1gy3li7/my_first_home_server](https://www.reddit.com/r/selfhosted/comments/1gy3li7/my_first_home_server)
 - RSS feed: $source
 - date published: 2024-11-23T16:32:35+00:00

<!-- SC_OFF --><div class="md"><p>So im 16 and a i have some old parts from my old pc and i want to turn it in a home server what software should i use? I been taking a liking to rust but im really New to this so idk if i could make my own software for the home server to have some more fun Any though on this is appreciated</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PleasantAvocado7870"> /u/PleasantAvocado7870 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy3li7/my_first_home_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy3li7/my_first_home_server/">[comments]</a></span>

## Securely Expose your Homelab Services with Mutual TLS
 - [https://www.reddit.com/r/selfhosted/comments/1gy2z1h/securely_expose_your_homelab_services_with_mutual](https://www.reddit.com/r/selfhosted/comments/1gy2z1h/securely_expose_your_homelab_services_with_mutual)
 - RSS feed: $source
 - date published: 2024-11-23T16:05:33+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gy2z1h/securely_expose_your_homelab_services_with_mutual/"> <img src="https://b.thumbs.redditmedia.com/WGJwFgK8FKU1VTagGZ1K2YY-oIMK_bbzjVxXGjwMPVU.jpg" alt="Securely Expose your Homelab Services with Mutual TLS" title="Securely Expose your Homelab Services with Mutual TLS" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/adaszko"> /u/adaszko </a> <br/> <span><a href="https://www.apalrd.net/posts/2024/network_mtls/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy2z1h/securely_expose_your_homelab_services_with_mutual/">[comments]</a></span> </td></tr></table>

## Any 12$/Y VPS offers this Black Friday?
 - [https://www.reddit.com/r/selfhosted/comments/1gy2m5f/any_12y_vps_offers_this_black_friday](https://www.reddit.com/r/selfhosted/comments/1gy2m5f/any_12y_vps_offers_this_black_friday)
 - RSS feed: $source
 - date published: 2024-11-23T15:49:55+00:00

<!-- SC_OFF --><div class="md"><p>I’m looking for a VPS to deploy headscale and maybe setup a wiregaurd connection to my home to expose some services.</p> <p>My friends access jellyfin via tailscale from Ireland, Sweden, UK and India, so im looking for a VPS somewhere the proximity between all these locations are equal (dubai maybe idk) or in India</p> <p>This is my first time buying a VPS, im not even sure how much compute power i need for these. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/brightestsummer"> /u/brightestsummer </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy2m5f/any_12y_vps_offers_this_black_friday/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy2m5f/any_12y_vps_offers_this_black_friday/">[comments]</a></span>

## Plataforma de estudos caseira
 - [https://www.reddit.com/r/selfhosted/comments/1gy1qas/plataforma_de_estudos_caseira](https://www.reddit.com/r/selfhosted/comments/1gy1qas/plataforma_de_estudos_caseira)
 - RSS feed: $source
 - date published: 2024-11-23T15:10:46+00:00

<!-- SC_OFF --><div class="md"><p>Oi pessoal, novo usuário aqui e leigo no assunto.</p> <p>Eu tenho alguns cursos baixados em meu computador. Alguém conhece algum projeto de plataforma de estudos que eu possa usar em meu próprio PC ? A ideia não é usar de forma remota e apenas eu como usuário consumindo o conteúdo localmente, mapeando o diretório dos cursos.</p> <p>Procurei inclusive no Github, mas não consegui encontrar ou não soube pesquisar.<br/> Eu vi o Jellyfin e o Emby de forma superficial, mas pelo que eu percebi é mais voltado para consumo de filmes e séries. Não tem controle de avanço do curso e apenas consome mídia (vídeos).</p> <p>Agradeço se alguém puder me orientar.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mr_Gremlim"> /u/Mr_Gremlim </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy1qas/plataforma_de_estudos_caseira/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1

## Anyone run a local AI LLM in a VM?
 - [https://www.reddit.com/r/selfhosted/comments/1gy0yuu/anyone_run_a_local_ai_llm_in_a_vm](https://www.reddit.com/r/selfhosted/comments/1gy0yuu/anyone_run_a_local_ai_llm_in_a_vm)
 - RSS feed: $source
 - date published: 2024-11-23T14:35:33+00:00

<!-- SC_OFF --><div class="md"><p>Hello <a href="/r/selfhosted">r/selfhosted</a>!</p> <p>I have a server running Truenas-SCALE-24.04.1.1, and I&#39;m interested in using the server to run my own LLM with Ollama + Open WebUI on a Debian VM with access to Open WebUI from any pc on my local network.</p> <p>While researching for this project. I couldn&#39;t find anything on running this in a VM, and I&#39;d love to know your thoughts. Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/blackbirdproductions"> /u/blackbirdproductions </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy0yuu/anyone_run_a_local_ai_llm_in_a_vm/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy0yuu/anyone_run_a_local_ai_llm_in_a_vm/">[comments]</a></span>

## [Advice Needed] Beginner Sanity Check — Do I have a usecase for getting a NAS?
 - [https://www.reddit.com/r/selfhosted/comments/1gy0jst/advice_needed_beginner_sanity_check_do_i_have_a](https://www.reddit.com/r/selfhosted/comments/1gy0jst/advice_needed_beginner_sanity_check_do_i_have_a)
 - RSS feed: $source
 - date published: 2024-11-23T14:15:14+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ll get right to it — I&#39;m looking to get a Synology (or other!) NAS for my purposes, and I want to be sure I&#39;m being sane about this.</p> <p>I&#39;m a developer (currently a student in Uni, but will be graduating soon). I imagine I might make use of a NAS for: system backups, media storage, and running some docker containers for services like jellyfin or vaultwarden.</p> <p>My current backup strat is to a) full system back to a local HDD via Time Machine every week (I use a mac) and b) a more narrow backup to a Google Drive via restic/rclone every month. I want to also have time machine/other backups on the NAS, in case my local drive fails. I currently store media (movies, shows, books, etc) on a local hdd which I have with me. Passwords on bitwarden, etc. Might also want to use immich for photos (currently on Google photos).</p> <p>Now, I&#39;ll likely not be working in my hometown so — would it make sense to setup my NAS at my parent&

## Looking for kanban board with guest access
 - [https://www.reddit.com/r/selfhosted/comments/1gy0gwt/looking_for_kanban_board_with_guest_access](https://www.reddit.com/r/selfhosted/comments/1gy0gwt/looking_for_kanban_board_with_guest_access)
 - RSS feed: $source
 - date published: 2024-11-23T14:11:19+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone!</p> <p>I am currently looking for a self-hosted Kanban project management software. An important requirement here is that third parties must also be able to be invited to individual projects and only have to participate in these projects. Ideally, these guest users should be able to be invited by e-mail and then be given their own guest password with which they can then access the corresponding project.</p> <p>So far I have looked at Nextcloud Deck and Wekan. However, both do not provide guest access. So I wanted to gather your experiences. Maybe someone knows such a solution.</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/p211"> /u/p211 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy0gwt/looking_for_kanban_board_with_guest_access/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gy0gwt/looking_for_kanban_b

## Hit 760 Stars on My Open-Source Analytics Project. Thank You so Much.
 - [https://www.reddit.com/r/selfhosted/comments/1gxzx5z/hit_760_stars_on_my_opensource_analytics_project](https://www.reddit.com/r/selfhosted/comments/1gxzx5z/hit_760_stars_on_my_opensource_analytics_project)
 - RSS feed: $source
 - date published: 2024-11-23T13:44:12+00:00

<!-- SC_OFF --><div class="md"><p>Hey /selfhosted community!</p> <p>I&#39;m Antonio, Founder of Litlyx Analytics.</p> <p>It’s kind of crazy to think my project has reached 760 stars, thanks to you that are always supportive with me and my project.</p> <p>When I started, it was mostly just something I needed myself, but seeing so many people find value in it really feels like a big milestone to share.</p> <p>I&#39;ve taken so much from open-source over the years, so reaching this point is a important to me. I feels like I’m finally giving something back to the community that&#39;s helped me so much to become a developer.</p> <p>Litlyx is GDPR compliant ethical analytics tools. Track anonymous data with a cookie less approach that make it completely legal compliant. With it you can track web analytics and custom events (you can choose what to track). We inserted a wrapper of gpt that help non tech savvy people to querying data collected without using SQL. </p> <p>The Dashboard is compl

## Physical Book Library Tracker
 - [https://www.reddit.com/r/selfhosted/comments/1gxzry1/physical_book_library_tracker](https://www.reddit.com/r/selfhosted/comments/1gxzry1/physical_book_library_tracker)
 - RSS feed: $source
 - date published: 2024-11-23T13:36:40+00:00

<!-- SC_OFF --><div class="md"><p>Howdy All,</p> <p>I was wondering if there was a self hosted library app that would allow me to ingest ISBN numbers to keep track of all the books I own.</p> <p>Currently I use an android app called my library to ingest the isbns and then export them to a spread sheet. </p> <p>Being that I now have 2000 books it is kinda inconvenient to search in a spreadsheet.</p> <p>Let me know if something like this exists :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/WikoSiko"> /u/WikoSiko </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxzry1/physical_book_library_tracker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxzry1/physical_book_library_tracker/">[comments]</a></span>

## Time to change up my homelab?
 - [https://www.reddit.com/r/selfhosted/comments/1gxysrt/time_to_change_up_my_homelab](https://www.reddit.com/r/selfhosted/comments/1gxysrt/time_to_change_up_my_homelab)
 - RSS feed: $source
 - date published: 2024-11-23T12:43:09+00:00

<!-- SC_OFF --><div class="md"><p>So this is my setup atm. My skills are limited to simple problemsovling online and basic use of terminal and docker/docker compose. Rpi4 Home Assistant Rpi5 CasaOS with NPM, all the ARR&#39;s and download cients. PC - i5-4460,8GB RAM, 2x2TB mirror raid,(Just recieved 2x4TB Ironwolf to replace them). Software: TrueNAS Scale, Navidrome PC - i5-8600 - 32GB RAM - RTX3060 12GB Usage: Main stationary, when Im to lazy Connecting my ROG Laptop with slighty better performance. Software: Windows 11, Ollama, A1111(forge), OpenWebUI, Jellyfin, Alltalk TTS. I want to use this as a Linux computer but </p> <p>I am tempted to run a hypervisor on my i5-8600, freeing up a raspberry Pi or two. I feel like my setup has brought to much complexity. With ADHD and a bad working memory, this is not exacly optimal. Any suggestions?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ProcrastLife"> /u/ProcrastLife </a> <br/> <span><a href="ht

## Tails running as a Docker Container via Dockurr ?
 - [https://www.reddit.com/r/selfhosted/comments/1gxwyfp/tails_running_as_a_docker_container_via_dockurr](https://www.reddit.com/r/selfhosted/comments/1gxwyfp/tails_running_as_a_docker_container_via_dockurr)
 - RSS feed: $source
 - date published: 2024-11-23T10:45:07+00:00

<!-- SC_OFF --><div class="md"><p>Has anyone managed to run tails as a Docker Container?</p> <p>I&#39;m using Windows11 with <a href="https://github.com/dockur/windows">https://github.com/dockur/windows</a> </p> <p>it says, you can also run different iso&#39;s as well. So, i tried to make</p> <p>a docker-compose.yml but it ends in busybox and wont start the gui.</p> <p>So I really have a clue about Linux, but I was wondering if anyone has made it yet.</p> <p>Not necessary to reinvent the wheel...</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AssociationMean5078"> /u/AssociationMean5078 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxwyfp/tails_running_as_a_docker_container_via_dockurr/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxwyfp/tails_running_as_a_docker_container_via_dockurr/">[comments]</a></span>

## Selfhosted for A/V
 - [https://www.reddit.com/r/selfhosted/comments/1gxwwp8/selfhosted_for_av](https://www.reddit.com/r/selfhosted/comments/1gxwwp8/selfhosted_for_av)
 - RSS feed: $source
 - date published: 2024-11-23T10:41:40+00:00

<!-- SC_OFF --><div class="md"><p>Hi selfhosted!</p> <p>I&#39;m an amateur selfhoster, I&#39;ve built a server on debian at home for personal use with Plex and arrs and tailscale.</p> <p>Now I want to build a server for the company I work for self hosting a couple of services. I&#39;ve already setup wireguard for VPN service, mumble for impromptu intercom needs and Plex for running some videos on tvs.</p> <p>I&#39;m looking for ideas what else I could run that would benefit av company&#39;s needs. Also Plex doesn&#39;t really fit my needs, as I wanted something that would work as digital sinage that I could create playlists with mixed video photo content that would play indefinitely on Android tv client. Maybe somebody heard about such a service.</p> <p>TIA love this community </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mko1989"> /u/mko1989 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxwwp8/selfhosted_for_av/">[l

## Cron job selfhost
 - [https://www.reddit.com/r/selfhosted/comments/1gxwm7g/cron_job_selfhost](https://www.reddit.com/r/selfhosted/comments/1gxwm7g/cron_job_selfhost)
 - RSS feed: $source
 - date published: 2024-11-23T10:21:27+00:00

<!-- SC_OFF --><div class="md"><p>I have current setup on my stack - Java spring boot app - App deployed on kubernetes - Cron job on kubernetes</p> <p>My app exposing web APIs which will be called by Kubernetes Cron Job. </p> <p>Problem with current setup, I find it difficult to switch between maintenance mode. I need to suspend each of the jobs and the other SOP thing. Not to mention current setup is lack of observability. </p> <p>Any recommended self host out there that meet my requirements? - Deployable on Kubernetes - Had UI - Able to pause job execution on a given time, e.g 9AM-11AM - CRUD Cron Job - Support basic monitoring</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cbot59"> /u/cbot59 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxwm7g/cron_job_selfhost/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxwm7g/cron_job_selfhost/">[comments]</a></span>

## 📣 Jellyplist - sync playlists from Spotify to your Jellyfin instance
 - [https://www.reddit.com/r/selfhosted/comments/1gxwjo7/jellyplist_sync_playlists_from_spotify_to_your](https://www.reddit.com/r/selfhosted/comments/1gxwjo7/jellyplist_sync_playlists_from_spotify_to_your)
 - RSS feed: $source
 - date published: 2024-11-23T10:16:32+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gxwjo7/jellyplist_sync_playlists_from_spotify_to_your/"> <img src="https://external-preview.redd.it/-NX1wq780_d4fVXjKKC4-87oSeeEBIP4qtWeMGfFxYE.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=d0ff9f7c49b3f6fec1b2eb3517edec20ee7d55a4" alt="📣 Jellyplist - sync playlists from Spotify to your Jellyfin instance" title="📣 Jellyplist - sync playlists from Spotify to your Jellyfin instance" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/s7893odtlm2e1.jpg?width=804&amp;format=pjpg&amp;auto=webp&amp;s=71d421e98f93a6e1af93e5edbaa6d7992a27847c">https://preview.redd.it/s7893odtlm2e1.jpg?width=804&amp;format=pjpg&amp;auto=webp&amp;s=71d421e98f93a6e1af93e5edbaa6d7992a27847c</a></p> <p><strong>What is Jellyplist ?</strong></p> <p>It´s nothing fancy and new, think of it like a wrapper around existing tools and techniques.</p> <p>Jellyplist aims to be a companion app for your self-hosted Jell

## I finally finished documenting my home server setup. Spoiler, I used Wiki.js
 - [https://www.reddit.com/r/selfhosted/comments/1gxwaq0/i_finally_finished_documenting_my_home_server](https://www.reddit.com/r/selfhosted/comments/1gxwaq0/i_finally_finished_documenting_my_home_server)
 - RSS feed: $source
 - date published: 2024-11-23T09:59:29+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gxwaq0/i_finally_finished_documenting_my_home_server/"> <img src="https://b.thumbs.redditmedia.com/adJlJDH5ZEHK-RC1v2AOdLHpcEBTugxLeO7v0Ur2Lvw.jpg" alt="I finally finished documenting my home server setup. Spoiler, I used Wiki.js" title="I finally finished documenting my home server setup. Spoiler, I used Wiki.js" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>What I learned from this sub is:</p> <ul> <li>Backup, backup and backup</li> <li>Document everything you do</li> </ul> <p>I finally got to the documentation part and I am really happy with it. After some research I decided to use a self-hosted instance of <a href="https://js.wiki/">https://js.wiki/</a></p> <p>This is the end result:</p> <p><a href="https://preview.redd.it/exkmpkkhjm2e1.png?width=1832&amp;format=png&amp;auto=webp&amp;s=330698451ce6da5afa2c3c6a935ae88f91984924">https://preview.redd.it/exkmpkkhjm2e1.png?width=1832&amp;format=png&amp;auto=

## Selfhosted Kahoot alternative
 - [https://www.reddit.com/r/selfhosted/comments/1gxw9z9/selfhosted_kahoot_alternative](https://www.reddit.com/r/selfhosted/comments/1gxw9z9/selfhosted_kahoot_alternative)
 - RSS feed: $source
 - date published: 2024-11-23T09:58:02+00:00

<!-- SC_OFF --><div class="md"><p>I love Kahoot, the quiz platform. But the free versiin is too limited, while the paid version is too expensive (for my use case). Is there any self hosted alternative for this great platform?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dvandergeld"> /u/dvandergeld </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxw9z9/selfhosted_kahoot_alternative/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxw9z9/selfhosted_kahoot_alternative/">[comments]</a></span>

## I'm looking for feedback to improve self-hosted workflow
 - [https://www.reddit.com/r/selfhosted/comments/1gxvzw0/im_looking_for_feedback_to_improve_selfhosted](https://www.reddit.com/r/selfhosted/comments/1gxvzw0/im_looking_for_feedback_to_improve_selfhosted)
 - RSS feed: $source
 - date published: 2024-11-23T09:38:08+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gxvzw0/im_looking_for_feedback_to_improve_selfhosted/"> <img src="https://b.thumbs.redditmedia.com/DCw_TJqFyeA2lfdsb6qdvwENzX3es7qoDvKcqUSLz0M.jpg" alt="I'm looking for feedback to improve self-hosted workflow" title="I'm looking for feedback to improve self-hosted workflow" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi everyone, I am building a small self-hosted &#39;empire&#39; on a $9 VPS! Here&#39;s what I&#39;ve set up so far. </p> <p>I&#39;m stucking on figuring out auto-deployment with Gitea or Github. I also find myself have to manually create `.env` file on the very first deployment. </p> <p>Would love feedback on my workflow, could use some tips.</p> <p><a href="https://preview.redd.it/7xgjfmgvem2e1.png?width=2226&amp;format=png&amp;auto=webp&amp;s=3ad9473a83bf445a7f7f181a22b35974f1c589db">https://preview.redd.it/7xgjfmgvem2e1.png?width=2226&amp;format=png&amp;auto=webp&amp;s=3ad9473a83bf445a7f

## Subdomains with tailscale
 - [https://www.reddit.com/r/selfhosted/comments/1gxvtlr/subdomains_with_tailscale](https://www.reddit.com/r/selfhosted/comments/1gxvtlr/subdomains_with_tailscale)
 - RSS feed: $source
 - date published: 2024-11-23T09:25:29+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m just getting my server setup and so far, i have Caddy + Cloudflare working great with my public domain name. I can map subdomains to services and get SSL working. This is my Caddyfile:</p> <pre><code>{ debug admin :2019 log { output stdout format console level DEBUG } auto_https disable_redirects email cert@{$DEPLOY_DOMAIN}.com } {$DEPLOY_DOMAIN}, *.{$DEPLOY_DOMAIN} { tls { dns cloudflare {$CLOUDFLARE_TOKEN} } @actual host service1.{$DEPLOY_DOMAIN} handle @service1 { encode gzip zstd reverse_proxy service1 } handle { respond &quot;Hello!&quot; } } </code></pre> <p>Now I want to add another block using my tailscale magicDNS name and do the same subdomain routing there. But the problem is tailscale does not support subdomains.</p> <p>I could use paths like <code>domain.com/service1</code> and rewrite the Host header or something but i think this causes all kinds of problems. Hardcoded URLs break, websockets break and you have to fiddle with eve

## Benefits of a dedicated file server over ssh/sftp
 - [https://www.reddit.com/r/selfhosted/comments/1gxv9nv/benefits_of_a_dedicated_file_server_over_sshsftp](https://www.reddit.com/r/selfhosted/comments/1gxv9nv/benefits_of_a_dedicated_file_server_over_sshsftp)
 - RSS feed: $source
 - date published: 2024-11-23T08:45:17+00:00

<!-- SC_OFF --><div class="md"><p>I have been looking into various options for self hosted file servers and keep running into the same question. What benefit does something like seafile offer over normal ssh/sftp access? ssh is a must for server management, so I will always be able to sftp with no additional software. What would a file server application do that sftp doesn&#39;t??</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/fozid"> /u/fozid </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxv9nv/benefits_of_a_dedicated_file_server_over_sshsftp/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxv9nv/benefits_of_a_dedicated_file_server_over_sshsftp/">[comments]</a></span>

## Unbound: One particular domain returns SERVFAIL
 - [https://www.reddit.com/r/selfhosted/comments/1gxv4vz/unbound_one_particular_domain_returns_servfail](https://www.reddit.com/r/selfhosted/comments/1gxv4vz/unbound_one_particular_domain_returns_servfail)
 - RSS feed: $source
 - date published: 2024-11-23T08:35:32+00:00

<!-- SC_OFF --><div class="md"><p>It appears I have one domain that returns SERVFAIL. I&#39;ve been all over the internet, and I&#39;ve tried a large variety of things:</p> <ul> <li>Turned off DNSSEC</li> <li>Completely disabled firewall</li> <li>Tried to add domain to Unbound <code>insecure-domains:</code></li> <li>Ensured the time on the server is properly synced</li> <li>Ensured my Unbound instance is properly reading the <code>root.hints</code> file <ul> <li>Running Unbound in Recursive DNS mode</li> </ul></li> </ul> <p>Note: Running latest version Unbound in docker container. Also running Pihole, but I&#39;ve left that out of this post because the issue appears to be from Unbound, not Pihole.</p> <p>To make this more readable, I included logs and configs below in segments. I tried to keep it as short as possible. But with all the searching I&#39;ve done, nobody can diagnose these things without adequate info.</p> <p>I included: - Ping Test Results (from Server to Domain dns.oszx

## I am going on a trip for 2 months, need help in setting up access from outside my home
 - [https://www.reddit.com/r/selfhosted/comments/1gxukjm/i_am_going_on_a_trip_for_2_months_need_help_in](https://www.reddit.com/r/selfhosted/comments/1gxukjm/i_am_going_on_a_trip_for_2_months_need_help_in)
 - RSS feed: $source
 - date published: 2024-11-23T07:54:45+00:00

<!-- SC_OFF --><div class="md"><p>I have jellyfin and a music app on my home server. But I have not looked into setting up access from outside the home.</p> <p>I looked into my options and looks like I will have to set up a reverse proxy like nginx proxy manager or traefik or wireguard? IM still confused on what does what and the different things I need.</p> <p>But I want to ask what are the best ways to make sure my server is protected and no one hacks into it? Best practices sort of?</p> <p>And any help or resources on how to start setting these up would be appreciated </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Silencer306"> /u/Silencer306 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxukjm/i_am_going_on_a_trip_for_2_months_need_help_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxukjm/i_am_going_on_a_trip_for_2_months_need_help_in/">[comments]</a></span>

## Could someone make a titlecard for live tv ?
 - [https://www.reddit.com/r/selfhosted/comments/1gxufm1/could_someone_make_a_titlecard_for_live_tv](https://www.reddit.com/r/selfhosted/comments/1gxufm1/could_someone_make_a_titlecard_for_live_tv)
 - RSS feed: $source
 - date published: 2024-11-23T07:44:56+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gxufm1/could_someone_make_a_titlecard_for_live_tv/"> <img src="https://b.thumbs.redditmedia.com/bFdkHySc3yYDRrSNzs2xJCHH6gqvOgBMbp8zBM_Z7xE.jpg" alt="Could someone make a titlecard for live tv ?" title="Could someone make a titlecard for live tv ?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/p9oc8zbjvl2e1.png?width=2554&amp;format=png&amp;auto=webp&amp;s=4f9a6150b7c03914c3e0d2c8febaf0b1006b6ca2">https://preview.redd.it/p9oc8zbjvl2e1.png?width=2554&amp;format=png&amp;auto=webp&amp;s=4f9a6150b7c03914c3e0d2c8febaf0b1006b6ca2</a></p> <p>i was wondering if anyone who runs jellyfin was able to create a title card for live tv that matches the jellyfin theme?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/senpai-20"> /u/senpai-20 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxufm1/could_someone_make_a_titlecard_for

## Anyone using Safeline WAF?
 - [https://www.reddit.com/r/selfhosted/comments/1gxuezo/anyone_using_safeline_waf](https://www.reddit.com/r/selfhosted/comments/1gxuezo/anyone_using_safeline_waf)
 - RSS feed: $source
 - date published: 2024-11-23T07:43:42+00:00

<!-- SC_OFF --><div class="md"><p>Just found about <a href="https://github.com/chaitin/SafeLine">Safeline WAF</a> today. </p> <p>Seems pretty cool, and a good alternative to cloudflare&#39;s WAF, which has limited rule-set.</p> <p>I have spun a test instance up. </p> <p>For me, it could eventually replace my nginx proxy manager, once it allows custom locations and DNS Challenge for certs. (Currently only does HTTP-01)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/YankeeLimaVictor"> /u/YankeeLimaVictor </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxuezo/anyone_using_safeline_waf/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxuezo/anyone_using_safeline_waf/">[comments]</a></span>

## Strava alternative? Does it exist?
 - [https://www.reddit.com/r/selfhosted/comments/1gxuddx/strava_alternative_does_it_exist](https://www.reddit.com/r/selfhosted/comments/1gxuddx/strava_alternative_does_it_exist)
 - RSS feed: $source
 - date published: 2024-11-23T07:40:22+00:00

<!-- SC_OFF --><div class="md"><p>With the latest updates from Strava about ownership of data that is uploaded to their service, I&#39;m starting to consider self hosting my ride data.</p> <p>Is anyone aware of a self hosted alternative to Strava (obviously without the social aspects)? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/itsonlybarney"> /u/itsonlybarney </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxuddx/strava_alternative_does_it_exist/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxuddx/strava_alternative_does_it_exist/">[comments]</a></span>

## Self-hosted NTFY - how to send notification with message variable in Windows batch script, with curl command?
 - [https://www.reddit.com/r/selfhosted/comments/1gxszdl/selfhosted_ntfy_how_to_send_notification_with](https://www.reddit.com/r/selfhosted/comments/1gxszdl/selfhosted_ntfy_how_to_send_notification_with)
 - RSS feed: $source
 - date published: 2024-11-23T06:04:57+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gxszdl/selfhosted_ntfy_how_to_send_notification_with/"> <img src="https://b.thumbs.redditmedia.com/6WvO6sq5l2wLcK6pNCzjnRsgP8H1BIe4ZRo5Xc9-T5M.jpg" alt="Self-hosted NTFY - how to send notification with message variable in Windows batch script, with curl command?" title="Self-hosted NTFY - how to send notification with message variable in Windows batch script, with curl command?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I don&#39;t have problem using curl command in linux bash script; but the similar curl command inside Windows batch file produces message &quot;triggered&quot; instead of the real message. I don&#39;t know how to make it work...thanks in advance.</p> <p><a href="https://preview.redd.it/8uumyq61dl2e1.png?width=189&amp;format=png&amp;auto=webp&amp;s=7c06ed83354a074ab0600ad5aa7b6c191ed78d82">https://preview.redd.it/8uumyq61dl2e1.png?width=189&amp;format=png&amp;auto=webp&amp;s=7c06ed83354a0

## Proxmox VE popup nag removal, manually - v8.3 tested
 - [https://www.reddit.com/r/selfhosted/comments/1gxsgb5/proxmox_ve_popup_nag_removal_manually_v83_tested](https://www.reddit.com/r/selfhosted/comments/1gxsgb5/proxmox_ve_popup_nag_removal_manually_v83_tested)
 - RSS feed: $source
 - date published: 2024-11-23T05:31:18+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/esiy0676"> /u/esiy0676 </a> <br/> <span><a href="https://www.reddit.com/r/ProxmoxQA/comments/1gxru8s/nononsense_proxmox_ve_nag_removal_manually/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxsgb5/proxmox_ve_popup_nag_removal_manually_v83_tested/">[comments]</a></span>

## Top 3 BEST applications you've decided to self-host?
 - [https://www.reddit.com/r/selfhosted/comments/1gxs4ea/top_3_best_applications_youve_decided_to_selfhost](https://www.reddit.com/r/selfhosted/comments/1gxs4ea/top_3_best_applications_youve_decided_to_selfhost)
 - RSS feed: $source
 - date published: 2024-11-23T05:10:54+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/-ThatGingerKid-"> /u/-ThatGingerKid- </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxs4ea/top_3_best_applications_youve_decided_to_selfhost/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxs4ea/top_3_best_applications_youve_decided_to_selfhost/">[comments]</a></span>

## Personal Medical Record System
 - [https://www.reddit.com/r/selfhosted/comments/1gxs4bq/personal_medical_record_system](https://www.reddit.com/r/selfhosted/comments/1gxs4bq/personal_medical_record_system)
 - RSS feed: $source
 - date published: 2024-11-23T05:10:47+00:00

<!-- SC_OFF --><div class="md"><p>I am searching for a self-hosted electronic medical record system to store my medical history, including:</p> <ul> <li>Doctor visits</li> <li>Diagnostic reports</li> <li>Laboratory results</li> <li>Healthcare provider information</li> <li>Medical conditions</li> </ul> <p>I have evaluated Fasten Health and Mere Medical, but these platforms primarily focus on syncing health data from healthcare providers rather than supporting manual data entry. In my region, healthcare providers don&#39;t offer API access or digital health records integration. I took a look at ehr server and unable to bring up the application. </p> <p>Currently, I possess physical copies of my medical records. I need a portal that allows me to either:</p> <ol> <li>Scan and upload these documents, or</li> <li>Manually enter the data through forms in chronological order</li> </ol> <p>While I currently use Paperless-ngx for managing physical documents and Obsidian for basic medical notes

## Exploring No-Code and AI-Powered App Development – Introducing Need For Apps 🎉
 - [https://www.reddit.com/r/selfhosted/comments/1gxri1k/exploring_nocode_and_aipowered_app_development](https://www.reddit.com/r/selfhosted/comments/1gxri1k/exploring_nocode_and_aipowered_app_development)
 - RSS feed: $source
 - date published: 2024-11-23T04:34:41+00:00

<!-- SC_OFF --><div class="md"><p>Hey Everyone!</p> <p>I’m excited to introduce my new YouTube channel, <em>Need For Apps</em>. 🚀 This channel dives into the world of no-code tools, AI apps, and scalable app development—ideal for tech enthusiasts who are exploring self-hosted or alternative solutions to popular services.</p> <p>With a focus on tools like Bubble and automation through Make, I’ll be covering topics like:</p> <ul> <li>No-Code Development for Self-Hosted Apps</li> <li>Building Scalable MVPs</li> <li>AI-Driven App Customization</li> <li>Exploring Alternatives to Traditional Web Services</li> </ul> <p>For those interested in combining innovation with self-hosted solutions, I’d love for you to check it out. Here’s the link: <a href="https://youtu.be/2lnnrjlsfu0">https://youtu.be/2lnnrjlsfu0</a></p> <p>Looking forward to sharing ideas and insights with this amazing community!</p> <p>#NoCode #SelfHosted #AIApps #Automation</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a 

## Any alternatives to pocket that integrate with Kobo readers?
 - [https://www.reddit.com/r/selfhosted/comments/1gxr9a1/any_alternatives_to_pocket_that_integrate_with](https://www.reddit.com/r/selfhosted/comments/1gxr9a1/any_alternatives_to_pocket_that_integrate_with)
 - RSS feed: $source
 - date published: 2024-11-23T04:20:14+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a selfhosted alternative to pocket that will let me view saved bookmarks and articles that I can then view on my Kobo reader. Wallabag and linkwarden seem like the most basic options for bookmark storage but I&#39;m not sure if they can work on Kobo. </p> <p>Any help is much appreciated 👍🏼</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BAThomas311"> /u/BAThomas311 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxr9a1/any_alternatives_to_pocket_that_integrate_with/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxr9a1/any_alternatives_to_pocket_that_integrate_with/">[comments]</a></span>

## Network Topology and Security question
 - [https://www.reddit.com/r/selfhosted/comments/1gxqmkq/network_topology_and_security_question](https://www.reddit.com/r/selfhosted/comments/1gxqmkq/network_topology_and_security_question)
 - RSS feed: $source
 - date published: 2024-11-23T03:44:14+00:00

<!-- SC_OFF --><div class="md"><p>I currently have a media stack with Jellyfin and NGINX Proxy Manager hosted on a VM on subnet 192.168.1.0/24. It has been fine for the last year or so. My wife wanted to make a Wordpress site so I used the opportunity to learn about VLANs and created a subnet (192.168.255.0/24; VLAN 255) for “public services” with very restricted access to other networks. I’m thinking about moving Jellyfin and NPM to LXCs in the 255 subnet but it bugs me that I would have to create a firewall rule to allow access to my NAS in the trunk network. I feel like I could mitigate the risk but changing user permissions to the media share and making the user in the Jellyfin LXC a “nologin”. I’m soliciting feedback on how other people on this sub handle similar scenarios.</p> <p>P.S. Sorry for formatting, on mobile.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/HotDesireaux"> /u/HotDesireaux </a> <br/> <span><a href="https://www.reddit.

## How do you manager your applications?
 - [https://www.reddit.com/r/selfhosted/comments/1gxqhz2/how_do_you_manager_your_applications](https://www.reddit.com/r/selfhosted/comments/1gxqhz2/how_do_you_manager_your_applications)
 - RSS feed: $source
 - date published: 2024-11-23T03:37:07+00:00

<!-- SC_OFF --><div class="md"><p>My server setup is a OrangePi 3B where I&#39;ve installed DietPi OS.<br/> And I&#39;m using just docker to manager all my applications that I&#39;m hosting. </p> <p>Currently, I&#39;m using these:</p> <ul> <li>PiHole</li> <li>Firefly III</li> <li> Home Assistant</li> <li>Mosquitto Broker</li> </ul> <p>All these containers are running behind a nginx-proxy container.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lgr1206"> /u/lgr1206 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxqhz2/how_do_you_manager_your_applications/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxqhz2/how_do_you_manager_your_applications/">[comments]</a></span>

## Leaderboard
 - [https://www.reddit.com/r/selfhosted/comments/1gxplvg/leaderboard](https://www.reddit.com/r/selfhosted/comments/1gxplvg/leaderboard)
 - RSS feed: $source
 - date published: 2024-11-23T02:47:52+00:00

<!-- SC_OFF --><div class="md"><p>Hey yall Looking for a web-based (preferably self hosted) program to host a sales leaderboard. This is for a sales contest.</p> <p>Would like for the participants to be able to add sales and have them show up on leaderboard. What I&#39;ve tried:</p> <p>Knack: Users cannot delete records with knack so I didn&#39;t go with them. No option to use custom domain unless you pay extra. No option to self host. LeaderboardHQ: Unable to track dollar amount sold and its hard for users to add data. Open to any and all suggestions - open source/fre/ freemium preferred but am willing to pay for a program as well. Thank you in advance</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/caliinsuranceguy"> /u/caliinsuranceguy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxplvg/leaderboard/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxplvg/leaderboard/">[comments]<

## Jellyfin help
 - [https://www.reddit.com/r/selfhosted/comments/1gxpb90/jellyfin_help](https://www.reddit.com/r/selfhosted/comments/1gxpb90/jellyfin_help)
 - RSS feed: $source
 - date published: 2024-11-23T02:31:48+00:00

<!-- SC_OFF --><div class="md"><p>Hey y’all, I hope I’m asking this in the right place, I’ve been hosting a jellyfin server for the past like 8 months at this point and had some trouble at first setting it up but eventually got it working, i was using caddy to reverse proxy my ip and had the domain i was using set up on cloudflare with a dns proxy. I recently out of nowhere had it stop working, it seems to work when I localhost but I can’t figure out why it’s all of a sudden not working outside my network. I did run a apt update the other day and can’t recall if caddy changed how they had their Caddyfile or something but I’ve been trying to fix this for the last like 5 hours and now i’m just asking around, any knowledge on this kind of networking is appreciated. Thank you in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sp00d3rMan69"> /u/Sp00d3rMan69 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxpb90/jellyf

## Selfhost a DNS over https endpoint
 - [https://www.reddit.com/r/selfhosted/comments/1gxojrr/selfhost_a_dns_over_https_endpoint](https://www.reddit.com/r/selfhosted/comments/1gxojrr/selfhost_a_dns_over_https_endpoint)
 - RSS feed: $source
 - date published: 2024-11-23T01:51:44+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;m currently hosting DNS and DNS over tls using pfSense, but I would like to also host my own DNS over htttps (it should be another way to connect to my local DNS). It would be used only from the LAN.</p> <p>Does this exist? If so, what are you using?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ViKT0RY"> /u/ViKT0RY </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxojrr/selfhost_a_dns_over_https_endpoint/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxojrr/selfhost_a_dns_over_https_endpoint/">[comments]</a></span>

## Jellyfin Issue
 - [https://www.reddit.com/r/selfhosted/comments/1gxoduy/jellyfin_issue](https://www.reddit.com/r/selfhosted/comments/1gxoduy/jellyfin_issue)
 - RSS feed: $source
 - date published: 2024-11-23T01:43:35+00:00

<!-- SC_OFF --><div class="md"><p>I deleted some files from my library and literally cannot figure out how to remove the blank imaged episodes from Jellyfin. Literally any help is appreciated… And yes Jellyfin is able to delete other files.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BingoDaBongo"> /u/BingoDaBongo </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxoduy/jellyfin_issue/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxoduy/jellyfin_issue/">[comments]</a></span>

## Anyone looking for last stable (v8.2) Proxmox VE
 - [https://www.reddit.com/r/selfhosted/comments/1gxobsx/anyone_looking_for_last_stable_v82_proxmox_ve](https://www.reddit.com/r/selfhosted/comments/1gxobsx/anyone_looking_for_last_stable_v82_proxmox_ve)
 - RSS feed: $source
 - date published: 2024-11-23T01:40:41+00:00

<!-- SC_OFF --><div class="md"><p>If you hit an issue post v8.3 release, you can still download v8.2 ISO from here: <a href="https://enterprise.proxmox.com/iso/">https://enterprise.proxmox.com/iso/</a></p> <p>Note some fixed vulnerabilities since v8.2 though: <a href="https://pve.proxmox.com/wiki/Roadmap#Proxmox_VE_8.3">https://pve.proxmox.com/wiki/Roadmap#Proxmox_VE_8.3</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/esiy0676"> /u/esiy0676 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxobsx/anyone_looking_for_last_stable_v82_proxmox_ve/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxobsx/anyone_looking_for_last_stable_v82_proxmox_ve/">[comments]</a></span>

## Quick file transfer with high speeds and no size limit on files
 - [https://www.reddit.com/r/selfhosted/comments/1gxo8tk/quick_file_transfer_with_high_speeds_and_no_size](https://www.reddit.com/r/selfhosted/comments/1gxo8tk/quick_file_transfer_with_high_speeds_and_no_size)
 - RSS feed: $source
 - date published: 2024-11-23T01:36:23+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I work as video editor, and my job requires to send people chunky files. However, some filehostings i&#39;ve tried are very, very slow - we&#39;re talking about 2mb/s for a 50 gig file. So, can i somehow upload files without any limits?<br/> P.S. I can&#39;t seem to make pingvin-share, filebrowser or other server solutions to work because of my provider&#39;s dynamic ip and cgnat.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Crimonit"> /u/Crimonit </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxo8tk/quick_file_transfer_with_high_speeds_and_no_size/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxo8tk/quick_file_transfer_with_high_speeds_and_no_size/">[comments]</a></span>

## Ryzen 5000/7000 series vs EPYC for webhosting
 - [https://www.reddit.com/r/selfhosted/comments/1gxnx5i/ryzen_50007000_series_vs_epyc_for_webhosting](https://www.reddit.com/r/selfhosted/comments/1gxnx5i/ryzen_50007000_series_vs_epyc_for_webhosting)
 - RSS feed: $source
 - date published: 2024-11-23T01:20:07+00:00

<!-- SC_OFF --><div class="md"><p>Hello. I am going to host alot of websites as I make sites for clients and want to host them myself.</p> <p>I notice that the mainstream CPUs like the 7950x have like half the multi core performance vs 64 core EPYC 7713. Even against 9004, it does not seem like that the EPYC chip is a better deal. </p> <p>Is there something I am missing? Is this because these benches are with the 5.7ghz boost that would not work for 24/7 loads?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MapleComputers"> /u/MapleComputers </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxnx5i/ryzen_50007000_series_vs_epyc_for_webhosting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxnx5i/ryzen_50007000_series_vs_epyc_for_webhosting/">[comments]</a></span>

## GPS tracking for open sky mine
 - [https://www.reddit.com/r/selfhosted/comments/1gxn9qy/gps_tracking_for_open_sky_mine](https://www.reddit.com/r/selfhosted/comments/1gxn9qy/gps_tracking_for_open_sky_mine)
 - RSS feed: $source
 - date published: 2024-11-23T00:48:27+00:00

<!-- SC_OFF --><div class="md"><p>I am looking to build a self hosted solution. Remote mine. The mine uses a private cellular network. No internet access. Cellular trackers can be used, but the solution needs to send info to a local private IP server. </p> <p>Anyone knows of a solution that is either ready to deploy or configurable solutions that can assembled ? The trackers themselves have to fit tight specs, so far a few container trackers fit the bill, but will need to be programmed to send the position once or twice a day.</p> <p>Requirements are simple but firm. Client / server architecture in a closed environment. Solution has to be perpetual license, hosted locally. Offline maps ideal. GPX export is a great nice to have. Rugged LTE-m or NB-IoT Battery powered trackers that are easy to program to send info to the server. Otherwise I can figure out how to send the data as long as the server message format is well documented.</p> <p>Oh, and solution does not need to be free. As l

## Mailcord: Forward Emails to Discord with Ease (Self-Hosted, Docker-Ready)
 - [https://www.reddit.com/r/selfhosted/comments/1gxmnad/mailcord_forward_emails_to_discord_with_ease](https://www.reddit.com/r/selfhosted/comments/1gxmnad/mailcord_forward_emails_to_discord_with_ease)
 - RSS feed: $source
 - date published: 2024-11-23T00:18:34+00:00

<!-- SC_OFF --><div class="md"><p>First time doing a release, so bear with me.</p> <p>I built <strong>Mailcord</strong>, a simple tool to forward emails from an IMAP inbox (like Gmail) to Discord as rich embeds. It’s lightweight, self-hosted, and Docker-ready.</p> <p><strong>Key features</strong>:</p> <ul> <li>Works with IMAP (tested on Gmail).</li> <li>Supports custom domains via Cloudflare Email Routing.</li> <li>Optional user mapping for forwarding specific addresses to specific Discord users.</li> <li>Configurable polling interval and logging levels.</li> </ul> <p><strong>Known limitations</strong>:</p> <ul> <li>Poorly formatted emails will still look terrible in embeds.</li> <li>Relies on IMAP polling (it’s the protocol’s fault).</li> <li>Don’t connect it to a mailbox with 10K unread emails unless you <em>really</em> want to spam your Discord.</li> </ul> <p>Repo and docs: <a href="https://github.com/real-general-iroh/mailcord">GitHub</a><br/> Docker Hub: <a href="https://hub.doc

## My Plex Plan - Will this Work?
 - [https://www.reddit.com/r/selfhosted/comments/1gxmm1m/my_plex_plan_will_this_work](https://www.reddit.com/r/selfhosted/comments/1gxmm1m/my_plex_plan_will_this_work)
 - RSS feed: $source
 - date published: 2024-11-23T00:16:58+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, I&#39;m planning on overhauling my Plex media library for black friday. Right now, I&#39;m using a 2TB MyCloud Home storage device that has a Plex media server installed, but it&#39;s kind of.. bad. Constantly buffering and I&#39;ve reached the point where only a teeny bit of 2TB storage isn&#39;t enough for my needs. With that being said, I&#39;ve decided to go for a Healuck 4 Bay NAS MiniPC (N100 processor) on Amazon, currently 20% off.<br/> I&#39;ll be collecting many 4K <em>home</em> videos and I&#39;m considering looking into and learning about the &quot;arr&quot; applications, so I&#39;d like to be able to include this in my build. According to <a href="https://www.youtube.com/watch?v=yKTClZTfVOE">this Youtube video reviewing this product</a>, it includes OpenMediaVault as the base OS, which I think I&#39;d like to stick with. There won&#39;t be many users on this server, as it will only be shared with 2 or 3 family members and a coup

## Refurbished GPU
 - [https://www.reddit.com/r/selfhosted/comments/1gxmghc/refurbished_gpu](https://www.reddit.com/r/selfhosted/comments/1gxmghc/refurbished_gpu)
 - RSS feed: $source
 - date published: 2024-11-23T00:09:51+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gxmghc/refurbished_gpu/"> <img src="https://preview.redd.it/099o7amimj2e1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=66d11fa7f9a40169ed56e053860fdf8057e0bfa6" alt="Refurbished GPU" title="Refurbished GPU" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Is this ok for Plex/Jellyfin transcoding and frigate decoding?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Autoloose"> /u/Autoloose </a> <br/> <span><a href="https://i.redd.it/099o7amimj2e1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gxmghc/refurbished_gpu/">[comments]</a></span> </td></tr></table>

