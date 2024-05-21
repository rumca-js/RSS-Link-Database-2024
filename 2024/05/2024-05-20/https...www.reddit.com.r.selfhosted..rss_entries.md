# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## PodFetch and AntennaPod
 - [https://www.reddit.com/r/selfhosted/comments/1cwsao4/podfetch_and_antennapod](https://www.reddit.com/r/selfhosted/comments/1cwsao4/podfetch_and_antennapod)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T22:24:57+00:00

<!-- SC_OFF --><div class="md"><p>I've got Podfetch running successfully and AntennaPod reporting successful syncing. Even a full sync, which takes a minute or so, finishes successfully. </p> <p>However when I log onto the web ui it's all empty. Showing no subscriptions or recently listened to. </p> <p>Is the gpodder server seperate to the web ui?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/robsug"> /u/robsug </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwsao4/podfetch_and_antennapod/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwsao4/podfetch_and_antennapod/">[comments]</a></span>

## I'm a noob, how vulnerable am I?
 - [https://www.reddit.com/r/selfhosted/comments/1cws5pg/im_a_noob_how_vulnerable_am_i](https://www.reddit.com/r/selfhosted/comments/1cws5pg/im_a_noob_how_vulnerable_am_i)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T22:18:58+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, I'm relatively new at self hosting, but I would like to get better.</p> <p>I am currently running Unraid on my laptop as primary OS with about 20 Docker containers and one VM. None of my ports except Plex are exposed on the router and I am using Cloudflare Tunnel to &quot;expose&quot; the log in Unraid web page, Overseer and Immich for my family and friends through a purchased domain.</p> <p>My passwords for Unraid and Immich are fairly complex, and at least for Unraid I know there is bruteforce timeout. My understanding is Overseer should be fine, as anyone who connects to it needs to authorize with Plex and then will need to be given permission by me to request anything.</p> <p>How vulnerable is my server with this set-up, and how can I harden it? I'm wondering if MFA could be it, but it's a bit over my head, how to do it.</p> <p>I appreciate any and all input.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.redd

## Can't connect Komga to Cdisplayex
 - [https://www.reddit.com/r/selfhosted/comments/1cwrgjh/cant_connect_komga_to_cdisplayex](https://www.reddit.com/r/selfhosted/comments/1cwrgjh/cant_connect_komga_to_cdisplayex)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T21:49:13+00:00

<!-- SC_OFF --><div class="md"><p>I'm trying to read more comics, so I set up a Komga connected to Google Drive via Raidrive. Everything works on Komga's end, but when I try to connect it to Cdisplay, all I get is a communication error. It shows on Komga that it's attempting to connect but it says it has a &quot;Bad credentials&quot; any Idea to help fix this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/blazzeman"> /u/blazzeman </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwrgjh/cant_connect_komga_to_cdisplayex/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwrgjh/cant_connect_komga_to_cdisplayex/">[comments]</a></span>

## Reverse proxy is still far too much of a headache
 - [https://www.reddit.com/r/selfhosted/comments/1cwqgqg/reverse_proxy_is_still_far_too_much_of_a_headache](https://www.reddit.com/r/selfhosted/comments/1cwqgqg/reverse_proxy_is_still_far_too_much_of_a_headache)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T21:06:46+00:00

<!-- SC_OFF --><div class="md"><p>I know that thanks to webservers like Caddy, reverse proxy has become easier to implement. But the fact is that it's still too much of a pain in many areas.</p> <p>For example, if your ISP has locked you out in CGNAT hell, getting Caddy to work after generating a proper SSL certificate through Let's Encrypt or Zero SSL, is way too complex. Caddy has a DNS challenge module for those stuck with CGNAT, but it isn't integrated into the package and has to built from the source code.</p> <p>Even after getting it all to work, there's no guarantee that your preferred selfhosted software will actually work with reverse proxy (eg. Jellyfin, Paperless-ngx need some additional tweaks for reverse proxy to work and for all assets to load, so does almost every other selfhosted software).</p> <p>With Google Play Store implementing a policy whereby all transmission of data <em>has</em> to happen in encrypted format, connecting to things like, say a selfhosted Joplin s

## Any alternative to Dual WAN DNS failover apart from DDNS or DNS Load Balancing?
 - [https://www.reddit.com/r/selfhosted/comments/1cwpis8/any_alternative_to_dual_wan_dns_failover_apart](https://www.reddit.com/r/selfhosted/comments/1cwpis8/any_alternative_to_dual_wan_dns_failover_apart)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T20:27:28+00:00

<!-- SC_OFF --><div class="md"><p>I have 2 WAN with static IP for my homelab, and I found following method to setup failover but each has drawback, any better methods?</p> <p>DDNS will have a propagation lag, but it's free with Cloudflare. I find the lag can be a couple minutes, or half an hour. Not much help with aggressive TTL but actually to do with how TTL is respected.</p> <p>Use Cloudflare DNS Load balancing, it cost $5 for first 2 origin server, and $1 per million DNS requests. not bad but ideally trying to make it happen for free for home lab.</p> <p>Just leave 2x A records in DNS and hope for the best, trouble is my 2 WAN connection has drastically different speed, one is from mobile network so really meant for backup not sharing 50% of the load.</p> <p><strong>Does anyone know any other good solutions?</strong></p> <p>I've also come across ISP level of magic where they bind 2 WAN into a single IP, but that's out of reach for homelabbers</p> </div><!-- SC_ON --> &#32; submitt

## Using directory as rootfs
 - [https://www.reddit.com/r/selfhosted/comments/1cwpd3d/using_directory_as_rootfs](https://www.reddit.com/r/selfhosted/comments/1cwpd3d/using_directory_as_rootfs)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T20:21:02+00:00

<!-- SC_OFF --><div class="md"><p>I had a backup of my one LXC but i lost the vzdump but still have the LXC filesystem. The file system is in a directory in <code>/var/lib/vz/images/104/ct-104-fs</code> and I made the folder the rootfs of the LXC.</p> <p>When i try to start the LXC in proxmox i get<br /> <code>TASK ERROR: unable to parse volume filename 'ct-104-fs'</code></p> <p>Config file</p> <p><code>arch: amd64</code></p> <p><code>cores: 2</code></p> <p><code>features: nesting=1</code></p> <p><code>hostname: BRANDTCLEANWEB</code></p> <p><code>memory: 4096</code></p> <p><code>net0: name=eth0,bridge=vmbr0,ip=192.168.2.9/23,gw=192.168.2.1</code></p> <p><code>ostype: debian</code></p> <p><code>rootfs: local:104/ct-104-fs</code></p> <p><code>swap: 8192</code></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ZealousidealHawk3856"> /u/ZealousidealHawk3856 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwpd3d/using_directory_

## SW for Managing an association?
 - [https://www.reddit.com/r/selfhosted/comments/1cwoujn/sw_for_managing_an_association](https://www.reddit.com/r/selfhosted/comments/1cwoujn/sw_for_managing_an_association)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T20:00:15+00:00

<!-- SC_OFF --><div class="md"><p>Hej,</p> <p>I am looking for a free software to manage an (artist) association (German: Verein or e.V.).</p> <p>Looking for something like:</p> <ul> <li>Manage members (late fees, entries, exits)</li> <li>Locations (exhibitions)</li> <li>Contacts (Location owners, Artists, partners)</li> <li>Communication to members</li> <li>Communication to contacts</li> <li>Financial spending </li> <li>Press and partner management</li> <li>Timelines (Exhibitions)</li> <li>...</li> </ul> <p>I am aware of &quot;Wiso Mein Verein&quot; but that's closed software. Checked awesome self hosted with no success (I think).</p> <p>An ideas?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Morgennebel"> /u/Morgennebel </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwoujn/sw_for_managing_an_association/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwoujn/sw_for_managing_an_as

## Seeking a Solution for Personalized Email Invitations with Attached PDFs
 - [https://www.reddit.com/r/selfhosted/comments/1cwoopo/seeking_a_solution_for_personalized_email](https://www.reddit.com/r/selfhosted/comments/1cwoopo/seeking_a_solution_for_personalized_email)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T19:53:44+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a solution similar to the mail merge feature in MS Word. Recently, we started sending personalized invitations to our clients (NPO) – directly addressed to each individual. This method worked quite well in Word for sending simple text-based invitations. However, we now need an easy solution that can automatically generate a PDF for each recipient based on specific variables. - Like word, but with E-Mail text and multiple PDFs per mail (preferably with something to delay the send until then). I has to be able to connect to an exsisting SMTP server.</p> <p>The desired solution should be capable of including personalized email text and attaching multiple PDF (also personalized) documents to each email. We typically send these personalized invitations to about 50 recipients at a time.</p> <p>Does anyone have recommendations for solutions?<br /> Found only some alternatives that where all specialized towards newsletter or marketing...</p> 

## Paperless-ngx on unRAID - what did I do wrong?)
 - [https://www.reddit.com/r/selfhosted/comments/1cwmdak/paperlessngx_on_unraid_what_did_i_do_wrong](https://www.reddit.com/r/selfhosted/comments/1cwmdak/paperlessngx_on_unraid_what_did_i_do_wrong)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T18:18:40+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1cwmdak/paperlessngx_on_unraid_what_did_i_do_wrong/"> <img alt="Paperless-ngx on unRAID - what did I do wrong?)" src="https://external-preview.redd.it/YMPZTYosGtHGXv1uS9w78kPJEjf83SgwfzqnRn2z1ug.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=d7b0f3059faf83cc71a5c5ea692748e0630dc6bd" title="Paperless-ngx on unRAID - what did I do wrong?)" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I am using the <a href="http://ghcr.io/paperless-ngx/paperless-ngx">repository </a>from selfhosters and just a sqlite database. Everything was going great until I logged in recently and the placeholders for my documents were still showing up in the UI but instead of the thumbnail there was just a broken image icon and I think they're all gone. I looked in the docker paths as well as the host paths for media and data and they don't seem to be in the filesystem. I am intending to reinstall and use postgres 15 for the db but I am a

## Can't upload big files to filecloud
 - [https://www.reddit.com/r/selfhosted/comments/1cwm9ri/cant_upload_big_files_to_filecloud](https://www.reddit.com/r/selfhosted/comments/1cwm9ri/cant_upload_big_files_to_filecloud)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T18:14:32+00:00

<!-- SC_OFF --><div class="md"><p>I just finished setting up filecloud to replace onedrive, but I cant seem to figure our how to upload files any larger than 15gb. i changed my user quota to unlimited but it just seems to be capped at 15gb</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kool_kid1233"> /u/kool_kid1233 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwm9ri/cant_upload_big_files_to_filecloud/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwm9ri/cant_upload_big_files_to_filecloud/">[comments]</a></span>

## Docker volume
 - [https://www.reddit.com/r/selfhosted/comments/1cwlpde/docker_volume](https://www.reddit.com/r/selfhosted/comments/1cwlpde/docker_volume)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T17:51:18+00:00

<!-- SC_OFF --><div class="md"><p>In a docker compose file in the volume section, what determines if the volume(S) get mounted locally or as a docker volume? Some projects I am running the volume is local and some are a docker volume. I know both are actually local because you can navigate to it, local is the easiest to get to. Is it determined by the docker compose file? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/linuxmel"> /u/linuxmel </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwlpde/docker_volume/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwlpde/docker_volume/">[comments]</a></span>

## Is selfhosting for data privacy then using windows pointless?
 - [https://www.reddit.com/r/selfhosted/comments/1cwl2yg/is_selfhosting_for_data_privacy_then_using](https://www.reddit.com/r/selfhosted/comments/1cwl2yg/is_selfhosting_for_data_privacy_then_using)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T17:25:03+00:00

<!-- SC_OFF --><div class="md"><p>For instance I have shifted from onenote to trillium for my notes and research but I still mainly access it from my windows pc. I also use OneDrive as a third backup besides me NAS. Does this make moving away from onenote pointless privacy wise?</p> <p>I ask because selfhosted has pushed me to prefer FOSS for most applications but I still prefer windows for my PC.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sexpusa"> /u/sexpusa </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwl2yg/is_selfhosting_for_data_privacy_then_using/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwl2yg/is_selfhosting_for_data_privacy_then_using/">[comments]</a></span>

## Reverse Proxy for Minecraft and SCP SL
 - [https://www.reddit.com/r/selfhosted/comments/1cwkocn/reverse_proxy_for_minecraft_and_scp_sl](https://www.reddit.com/r/selfhosted/comments/1cwkocn/reverse_proxy_for_minecraft_and_scp_sl)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T17:08:14+00:00

<!-- SC_OFF --><div class="md"><p>I'm hosting some MC and SCP servers for friends, but I dont want to expose my own IP, is there any free proxy service that I can use for this or do I need to spend money on something?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Labradorabl3"> /u/Labradorabl3 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwkocn/reverse_proxy_for_minecraft_and_scp_sl/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwkocn/reverse_proxy_for_minecraft_and_scp_sl/">[comments]</a></span>

## Self-Hosted Email Builder with Drag&Drop
 - [https://www.reddit.com/r/selfhosted/comments/1cwk7fh/selfhosted_email_builder_with_dragdrop](https://www.reddit.com/r/selfhosted/comments/1cwk7fh/selfhosted_email_builder_with_dragdrop)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T16:48:34+00:00

<!-- SC_OFF --><div class="md"><p>We got a HTML template for our email templates programmed and one person suggested that they would use an own version of an Drag&amp;Drop email template builder so we could automatically create our own templates based on our own html. Does anyone know a simple Drag&amp;Drop builder where we can add our own blocks and own html? Paid or open-source ... doesnt matter. But if we can have &quot;on brand&quot; emails with our own builder, would be great.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/40056"> /u/40056 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwk7fh/selfhosted_email_builder_with_dragdrop/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwk7fh/selfhosted_email_builder_with_dragdrop/">[comments]</a></span>

## I messed up my *arr setup somehow.
 - [https://www.reddit.com/r/selfhosted/comments/1cwggbi/i_messed_up_my_arr_setup_somehow](https://www.reddit.com/r/selfhosted/comments/1cwggbi/i_messed_up_my_arr_setup_somehow)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T14:06:36+00:00

<!-- SC_OFF --><div class="md"><p>Following situation: I have a server with Radarr, sonarr, Prowlarr, jellyfin and qBittorent installed. Then I have a separate machine running FileFlows to transcode everything to HEVC. </p> <p>My Folder structure looks like this:</p> <pre><code>mnt └── data └── media ├── downloads ├── movies └── tv </code></pre> <p>qBittorent stores all torrent files in /mnt/data/media/downloads so I can seed them until at least a 1.0 ratio. Once the torrents are downloaded, radarr/sonarr <strong>COPY</strong> the downloaded files to /mnt/data/media/movies|tv. Afterwards FileFlows transcodes the Video files it finds in /mnt/data/media/movies and /mnt/data/media/tv to HEVC. Copying the files instead of creating hardlinks is important because I don't want to be a dick and leech torrents after they're done downloading, that's why I want the files in /mnt/data/media/downloads to be untouched by FileFlows. </p> <p>I set to two libraries in FileFlows. /mnt/data/media/movies

## Stable diffusion AI Home server
 - [https://www.reddit.com/r/selfhosted/comments/1cwetby/stable_diffusion_ai_home_server](https://www.reddit.com/r/selfhosted/comments/1cwetby/stable_diffusion_ai_home_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T12:51:13+00:00

<!-- SC_OFF --><div class="md"><p>Is there a cost effective... Read minimal cost... To run this at home? What would be the minimum requirements to run this at a &quot;workable&quot; level?</p> <p><a href="https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Containers">https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Containers</a> </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Zealousideal-One5210"> /u/Zealousideal-One5210 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwetby/stable_diffusion_ai_home_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwetby/stable_diffusion_ai_home_server/">[comments]</a></span>

## How do I route requests from one service to another using the external domain?
 - [https://www.reddit.com/r/selfhosted/comments/1cweswh/how_do_i_route_requests_from_one_service_to](https://www.reddit.com/r/selfhosted/comments/1cweswh/how_do_i_route_requests_from_one_service_to)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T12:50:35+00:00

<!-- SC_OFF --><div class="md"><p>I have gitea hosting my container images, and woodpecker acting as a CI to build the container images.</p> <p>Both of these services are behind cloudflare tunnels and resolved using a traefik reverse proxy.</p> <p>When woodpecker tries to upload the completed image to gitea, I get a 413 error (file too large), which is thrown by Cloudflare, as cloudflare tunnels limits the free tier to files 100mb or less.</p> <p>What I'd like to do is route requests for `git.domain.com` from `woodpecker.domain.com` to point to the traefik instance internal to the cluster so that the request can then be routed to gitea.</p> <p>What's the correct way to do this?</p> <p>Googling around shows:</p> <ul> <li>Edit coredns: I couldn't get this working. Rewriting the request domain seems to lose some metadata that traefik needs to resolve the request</li> <li>Create another dns service: Problematic as that service needs a static IP address.</li> </ul> </div><!-- SC_ON --> &#3

## Sharing My Self-Hosted PWAs: Tools for Everyday Use
 - [https://www.reddit.com/r/selfhosted/comments/1cweery/sharing_my_selfhosted_pwas_tools_for_everyday_use](https://www.reddit.com/r/selfhosted/comments/1cweery/sharing_my_selfhosted_pwas_tools_for_everyday_use)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T12:30:50+00:00

<!-- SC_OFF --><div class="md"><p>Hello selfhosted community,</p> <p>Over the years, I've built several basic PWAs to scratch my own itch, which I self-host on my server. I thought some of them might be useful to others, so here’s the list:</p> <ul> <li><a href="https://github.com/paulgreg/math-game"><strong>Math Games</strong></a>: A game to help my kids learn math.</li> <li><a href="https://github.com/paulgreg/weather"><strong>Weather</strong></a>: A basic weather app. You'll need to create a key from OpenWeatherMap.</li> <li><a href="https://github.com/paulgreg/timezones"><strong>Timezones</strong></a>: Displays time in different cities.</li> <li><a href="https://github.com/paulgreg/semi-persistent-chat"><strong>Semi-Persistent Chat</strong></a>: A simple chat where messages are removed after a few hours or days.</li> <li><a href="https://github.com/paulgreg/rsstodolist-node-server"><strong>RSS To-Read List</strong></a>: An URL-oriented to-read list based on an RSS XML feed, to be 

## selfh.st/apps Update: Visible/clickable tags, license details, URL properties for sharing views, and more icons
 - [https://www.reddit.com/r/selfhosted/comments/1cwe6el/selfhstapps_update_visibleclickable_tags_license](https://www.reddit.com/r/selfhosted/comments/1cwe6el/selfhstapps_update_visibleclickable_tags_license)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T12:18:47+00:00

<!-- SC_OFF --><div class="md"><p>Hey, <a href="/r/selfhosted">r/selfhosted</a>! I'm overwhelmed with the <a href="https://old.reddit.com/r/selfhosted/comments/1buqe6a/ive_published_a_browsable_repository_of/">positive feedback I received</a> from launching <a href="https://selfh.st/apps">selfh.st/apps</a> (a browsable directory of self-hosted software) last month and wanted to follow up on some of the changes I've made based on requests received when sharing it.</p> <p>In no particular order:</p> <ul> <li>App tiles now display clickable tags to easily find similar software without having to rely on the dropdown menus</li> <li>License details (if applicable) are now visible on each tile</li> <li>I've enabled URL properties for storing filters in the page's URL, which allow users to share specific views with others (see <a href="https://selfh.st/apps/?alternative=Google+Analytics">this pre-filtered view of Google Analytics alternatives</a> as an example)</li> <li>I intially committed t

## Good List of Self-Hosted Applications in the description for r/selfhosted.
 - [https://www.reddit.com/r/selfhosted/comments/1cwdnzq/good_list_of_selfhosted_applications_in_the](https://www.reddit.com/r/selfhosted/comments/1cwdnzq/good_list_of_selfhosted_applications_in_the)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T11:51:32+00:00

<!-- SC_OFF --><div class="md"><p>This is where I found StirlingPDF and other applications I self-host:</p> <p><a href="https://selfh.st/apps/">https://selfh.st/apps/</a> </p> <p>It is located under &quot;Useful Lists&quot; in the <a href="/r/selfhosted">r/selfhosted</a> description.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Slow_Wafer3174"> /u/Slow_Wafer3174 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwdnzq/good_list_of_selfhosted_applications_in_the/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwdnzq/good_list_of_selfhosted_applications_in_the/">[comments]</a></span>

## Upgrading my setup, should I leave OMV and move to TrueNAS, UnRAID, or...?
 - [https://www.reddit.com/r/selfhosted/comments/1cwcjde/upgrading_my_setup_should_i_leave_omv_and_move_to](https://www.reddit.com/r/selfhosted/comments/1cwcjde/upgrading_my_setup_should_i_leave_omv_and_move_to)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T10:45:08+00:00

<!-- SC_OFF --><div class="md"><p>Years ago I first dipped my toe into selfhosting with an Odroid HC2 (+6TB HDD) as a tiny home server. It was well supported by OMV, so that's what I went with. Since then things have slowly (at first, but then quickly) escalated, and I've now got a 3-node Proxmox VE cluster running running on a couple of tiny PCs and a thin client (plus the trusty Odroid serving as a backup target). </p> <p>As time went on, I went from selfhosting only Plex and the *arrs to a more diverse mix - including Immich, Paperless, Home Assistant, etc. My storage needs grew too, and I've cobbled together 28TB of storage (excluding backup/boot disks) from an 18TB drive, the original 6TB drive, and a 4TB drive, all managed by OMV in a VM. I'm using the mergerfs plugin to create a single shared storage pool, but my current drive configuration has no parity (all the important stuff is backed up locally and to B2 cloud storage though). Oh, and all the drives have ended up connected

## HortusFox v3.1 released! The helpful companion for plant parents
 - [https://www.reddit.com/r/selfhosted/comments/1cwbxcv/hortusfox_v31_released_the_helpful_companion_for](https://www.reddit.com/r/selfhosted/comments/1cwbxcv/hortusfox_v31_released_the_helpful_companion_for)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T10:05:54+00:00

<!-- SC_OFF --><div class="md"><p>Hey <a href="/r/selfhosted">r/selfhosted</a> </p> <p>We are pleased to announce that HortusFox v3.1 was just released!</p> <p>One of the major new features are custom plant attributes: You will now be able to add more attributes to the details table of your plants. This way you can even more specify various information that are particularly of interest of a specific plant. Datatypes are text, number (integer and float), boolean values and dates. You will also be able to toggle what default attributes shall be shown in the plant details.</p> <p>Another great new feature is the REST API: You can now manage some plant data via the REST API by using your generated API keys. Imagine you have something like sensors that are capable of performing API requests. They could then live update plant data of a specific plant.</p> <p>Here is the changelog of the key features:</p> <ul> <li>Manage custom plant attributes</li> <li>REST API feature</li> <li>Radiobuttons

## Looking for Alpha Testers 🚀
 - [https://www.reddit.com/r/selfhosted/comments/1cwbm5o/looking_for_alpha_testers](https://www.reddit.com/r/selfhosted/comments/1cwbm5o/looking_for_alpha_testers)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T09:45:29+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone!</p> <p>I’m thrilled to finally share something I’ve been working on for the past four months - <strong>RepoFlow</strong>! It’s a new repository management platform that’s super easy to use and designed to make your life simpler. Think of it as an alternative to existing repository management solutions, but with a fresh approach. While RepoFlow is intended to be self-hosted on launch, the current alpha is cloud-based.</p> <p><strong>So… Why RepoFlow?</strong></p> <p>• Clean and intuitive interface</p> <p>• Effortless repository management</p> <p>• Easy and fast package search</p> <p>• Supports npm, Maven, PyPI, NuGet, and Docker packages</p> <p>• Repository types: local, remote, virtual (allows for efficient management of your packages, combining local and remote repositories for a seamless experience)</p> <p><strong>Looking for Your Help:</strong></p> <p>I’m seeking alpha testers who have experience with existing repository management pl

## Is this server liable in 2024? Build date 2016
 - [https://www.reddit.com/r/selfhosted/comments/1cwbjxx/is_this_server_liable_in_2024_build_date_2016](https://www.reddit.com/r/selfhosted/comments/1cwbjxx/is_this_server_liable_in_2024_build_date_2016)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T09:41:18+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1cwbjxx/is_this_server_liable_in_2024_build_date_2016/"> <img alt="Is this server liable in 2024? Build date 2016" src="https://external-preview.redd.it/Io8H3lMokoEI1iKYj3Oh-i8HPgwZpQH_h0R78ejbFOM.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=eece39e8b560dd3dc2b6377ce2dbc036b2fd59cb" title="Is this server liable in 2024? Build date 2016" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Proximus88"> /u/Proximus88 </a> <br /> <span><a href="https://i.imgur.com/4OTYBTW.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwbjxx/is_this_server_liable_in_2024_build_date_2016/">[comments]</a></span> </td></tr></table>

## Jellyfin creates two files per episode
 - [https://www.reddit.com/r/selfhosted/comments/1cwbh2s/jellyfin_creates_two_files_per_episode](https://www.reddit.com/r/selfhosted/comments/1cwbh2s/jellyfin_creates_two_files_per_episode)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T09:35:37+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1cwbh2s/jellyfin_creates_two_files_per_episode/"> <img alt="Jellyfin creates two files per episode" src="https://b.thumbs.redditmedia.com/Br9zSNTo9gpdIKw_lbN66393S53hnh18N5g3Hqgrlis.jpg" title="Jellyfin creates two files per episode" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi, first of all, i know this is not <a href="/r/jellyfin">r/jellyfin</a><br /> But since the last update, all of my series creates a second file per existing file.<br /> Obviously those cant be played.<br /> I cant figure out why it behaves like this and would appreciate any tipps to solve the issue</p> <p><a href="https://preview.redd.it/c7t9qqqnwj1d1.png?width=337&amp;format=png&amp;auto=webp&amp;s=915a9d976dd6577e37e4ab1592bcede6617dc63c">https://preview.redd.it/c7t9qqqnwj1d1.png?width=337&amp;format=png&amp;auto=webp&amp;s=915a9d976dd6577e37e4ab1592bcede6617dc63c</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="http

## Discord Alternative with Audio Screen Share
 - [https://www.reddit.com/r/selfhosted/comments/1cwbddg/discord_alternative_with_audio_screen_share](https://www.reddit.com/r/selfhosted/comments/1cwbddg/discord_alternative_with_audio_screen_share)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T09:28:09+00:00

<!-- SC_OFF --><div class="md"><p>After recent developements with Discords stance on advertisement and privacy I am searching for an alternative that I can self-host for me and my friends.</p> <p>I know this question has been asked multiple times before but I have one requirement that I can't seem to find anywhere: I need screen sharing with audio (which also works on Linux).</p> <p>I have tried Matrix Synapse with Element, which supports screen sharing but not with audio and I have also tried Mattermost, which is the same. I realy liked Mattermost for it's similarities to Discord and how simple it was to set up but I realy need audio sharing for watching videos with my firends.</p> <p>Any suggestions are welcome!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/EducationalFalcon23"> /u/EducationalFalcon23 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwbddg/discord_alternative_with_audio_screen_share/">[link]</a></span>

## Archie, the Internet’s first search engine, is rescued and running
 - [https://www.reddit.com/r/selfhosted/comments/1cwb6if/archie_the_internets_first_search_engine_is](https://www.reddit.com/r/selfhosted/comments/1cwb6if/archie_the_internets_first_search_engine_is)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T09:14:21+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1cwb6if/archie_the_internets_first_search_engine_is/"> <img alt="Archie, the Internet’s first search engine, is rescued and running" src="https://external-preview.redd.it/BDBV-WGJ4JjqwlcFYipJUYWTbnsZw_todaUrtvdbzg8.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=acd7fbabcd356a529ca319a16111e6a668fc89cc" title="Archie, the Internet’s first search engine, is rescued and running" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Yutyo"> /u/Yutyo </a> <br /> <span><a href="https://arstechnica.com/gadgets/2024/05/archie-the-internets-first-search-engine-is-rescued-and-running/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwb6if/archie_the_internets_first_search_engine_is/">[comments]</a></span> </td></tr></table>

## what would you recommend if i were to locally host a game server but have public accessible endpoint so they can connect to it?
 - [https://www.reddit.com/r/selfhosted/comments/1cwauz4/what_would_you_recommend_if_i_were_to_locally](https://www.reddit.com/r/selfhosted/comments/1cwauz4/what_would_you_recommend_if_i_were_to_locally)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T08:50:42+00:00

<!-- SC_OFF --><div class="md"><p>according to what i research so far </p> <p>Option 1</p> <p>use dockdns, this would be nice, but what about reliability on TCP/UDP? anyone with input on this? or alternatives? is there one that i can self host on cloud that is like dockdns?</p> <p>Option 2</p> <p>use self hosted VPN. i don't have any specifics on this, but would like to get some recommendation for publicly accessible end points where i can just deploy in on aws or gcp</p> <p>the key is, i just need my game server to be self hosted locally and publicly accessible</p> <p>how about Reverse proxy?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Exact-Yesterday-992"> /u/Exact-Yesterday-992 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwauz4/what_would_you_recommend_if_i_were_to_locally/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cwauz4/what_would_you_recommend_if_i_were_to_locally/

## (Help) Newbie Server Machine; Game Servers, Virtualization, Etc.
 - [https://www.reddit.com/r/selfhosted/comments/1cwanob/help_newbie_server_machine_game_servers](https://www.reddit.com/r/selfhosted/comments/1cwanob/help_newbie_server_machine_game_servers)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T08:35:30+00:00

<!-- SC_OFF --><div class="md"><p>So, in a vie for assistance in figuring out the environment for current Server PC builders/users, currently looking for user input because its NICHE ENOUGH for it to be rather confusing when it comes to CPU choice, mainly. Knowing that renting servers over the course of around 8+ years I could have bought a killer machine to host most of my needs several times over. And bare metal/full machine rentals from NFO and the like usually are upwards of $100-200+ monthly which can add up to full machine in half a year, and the sunken cost of once you eventually let the service go...</p> <p><strong>Purposes/Intent:</strong></p> <ul> <li><em>Game Server Hosting (Multiple game servers of potential varying demands simultaneously)</em></li> <li><em>Using VM's to emulate partitions of Ubuntu; Mainly to host apps that would assist in running game communitys/server communities such as MatterMost, Taiga, etc (They have Ubuntu hosting options)</em></li> <li><em>(Case +

## Self-hosted bookmark management across Windows / iOS / Linux - any advice?
 - [https://www.reddit.com/r/selfhosted/comments/1cw9q8w/selfhosted_bookmark_management_across_windows_ios](https://www.reddit.com/r/selfhosted/comments/1cw9q8w/selfhosted_bookmark_management_across_windows_ios)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T07:27:01+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a way to have bookmarks synchronized across Windows Firefox / iOS Safari / Linux Firefox. </p> <p>I have looked over multiple solutions that fall short on different fronts: </p> <ul> <li>Firefox-sync-server requires me to have an account on external server</li> <li>iCloud bookmark sync service for Windows at some point stopped working altogether</li> <li>Linkwarden is an overkill with a cluttered interface</li> <li>Homepages: homarr, flame, dashy are not integrating with browsers (i.e. adding new bookmark requires clicking through their UI).<br /></li> </ul> <p>I am sure I must be missing something here. What I am looking for is a simple landing page (like bookmarks start page in Safari or Bookmark sidebar) that would integrate with browsers - or a service that would simply synchronize built-in bookmark databases across browsers.</p> <p>Any advice?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/

## Migrating to Linux
 - [https://www.reddit.com/r/selfhosted/comments/1cw98ry/migrating_to_linux](https://www.reddit.com/r/selfhosted/comments/1cw98ry/migrating_to_linux)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T06:52:48+00:00

<!-- SC_OFF --><div class="md"><p>I am currently using windows as the OS for my Media server and looking to switch to linux (if you have any recommendations about which distro I should go with, I would love to hear them), I use jellyfin, arr services, qbittorrent, caddy and duck dns.<br /> I need to transfer the configs of all of these to linux (and the media files if possible) and would like to know what is the best way to do it.<br /> Thank you for taking the time to help. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/shokoALT"> /u/shokoALT </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cw98ry/migrating_to_linux/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cw98ry/migrating_to_linux/">[comments]</a></span>

## Ticket system
 - [https://www.reddit.com/r/selfhosted/comments/1cw8zvo/ticket_system](https://www.reddit.com/r/selfhosted/comments/1cw8zvo/ticket_system)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T06:34:38+00:00

<!-- SC_OFF --><div class="md"><p>Any recommendations for selfhosted ticketing systems for interaction with customers?</p> <p>I know OSticket, but I think there are a ton more.. 🙂</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Equal_Dragonfly_7139"> /u/Equal_Dragonfly_7139 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cw8zvo/ticket_system/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cw8zvo/ticket_system/">[comments]</a></span>

## Gigabyte NUC
 - [https://www.reddit.com/r/selfhosted/comments/1cw82tq/gigabyte_nuc](https://www.reddit.com/r/selfhosted/comments/1cw82tq/gigabyte_nuc)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T05:31:40+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1cw82tq/gigabyte_nuc/"> <img alt="Gigabyte NUC" src="https://preview.redd.it/er1qn0zgpi1d1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=9a608fed475aa47f45326eebce2cd9c1ab8df6c8" title="Gigabyte NUC" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Is this worth to buy for Rs.8000/-. For self hosting jellyfin, immich, and pihome mainly. How will it perform and what are the things I need to check.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sea_Dish_2821"> /u/Sea_Dish_2821 </a> <br /> <span><a href="https://i.redd.it/er1qn0zgpi1d1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cw82tq/gigabyte_nuc/">[comments]</a></span> </td></tr></table>

## Wordpress and Caddy? - currently unable to provide secure connection
 - [https://www.reddit.com/r/selfhosted/comments/1cw6akc/wordpress_and_caddy_currently_unable_to_provide](https://www.reddit.com/r/selfhosted/comments/1cw6akc/wordpress_and_caddy_currently_unable_to_provide)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T03:41:15+00:00

<!-- SC_OFF --><div class="md"><p>I'm trying to install <a href="http://wordpress.org">wordpress.org</a>, using docker and docker compose, and with Caddy as my reverse proxy. There seem to be at least two github repos for this, <a href="https://github.com/svenakela/caddy-based-wordpress/tree/caddy-community-wiki-example">here (svenakela)</a> and <a href="https://github.com/andrewheiss/caddy-docker-compose-wp/tree/main">here (andrewheiss)</a>. They both say much the same thing, but with a few differences. Anyway, upshot of my work so far: can't access my site, with Chrome I get &quot;This site can’t provide a secure connection&quot;; on Firefox I get &quot;Secure Connection Failed&quot;. </p> <p>I've added WordPress in my<code>docker-compose.yml</code> file to my Caddy network, so that Caddy should see it. </p> <p>I already have MariaDB running for use with another container - can I use this one with a new (WordPress) database, or is it better to spin up a new MariaDB container simply 

## Migrating off Bitnami TinyTinyRSS instance
 - [https://www.reddit.com/r/selfhosted/comments/1cw63a4/migrating_off_bitnami_tinytinyrss_instance](https://www.reddit.com/r/selfhosted/comments/1cw63a4/migrating_off_bitnami_tinytinyrss_instance)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T03:29:42+00:00

<!-- SC_OFF --><div class="md"><p>I want to setup a new TinyTinyRSS instance on another OS (probably NixOS) because the Bitnami image I used on GCP free tier uses Debian Buster and is no longer supported.</p> <p>My only concerns are:</p> <ul> <li><p>filters</p></li> <li><p>read/unread status</p></li> <li><p>starred articles</p></li> </ul> <p>Does OPML export cover all these?</p> <p>I can find and copy the database too if I can figure out where is it :-D</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lostmsu"> /u/lostmsu </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cw63a4/migrating_off_bitnami_tinytinyrss_instance/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cw63a4/migrating_off_bitnami_tinytinyrss_instance/">[comments]</a></span>

## My experience with Kubernetes, as a selfhoster, so far.
 - [https://www.reddit.com/r/selfhosted/comments/1cw3x46/my_experience_with_kubernetes_as_a_selfhoster_so](https://www.reddit.com/r/selfhosted/comments/1cw3x46/my_experience_with_kubernetes_as_a_selfhoster_so)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T01:32:27+00:00

<!-- SC_OFF --><div class="md"><p>Late last year, I started an apprenticeship at a new company and I was excited to meet someone there with an equally or higher level of IT than myself - all the windows-maniacs excluded (because there is only so much excitement in a Domain Controller or Active Directory, honestly...). That employee explained and told me about all the services and things we use - one of them being Kubernetes, in the form of a cluster running OpenSuse's k3s.</p> <p>Well, hardly a month later, and they got fired for some reason and I had to learn <em>everything</em> on my own, from scratch, right then, right now and right there. F_ck.</p> <p>Months later, I have attempted to use k3s for selfhosting - trying to remove the tangled wires that is 30ish Docker Compose deployments running across three nodes. They worked - but getting a good reverse proxy setup involved creating a VPN that spans two instances of Caddy that share TLS and OSCP information through Redis and only u

## Homepage Calendar Help Needed
 - [https://www.reddit.com/r/selfhosted/comments/1cw2jde/homepage_calendar_help_needed](https://www.reddit.com/r/selfhosted/comments/1cw2jde/homepage_calendar_help_needed)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-20T00:19:16+00:00

<!-- SC_OFF --><div class="md"><p>I've been using the Homepage Docker container and recently discovered that it can be linked with the *arr suite. I'd like to add Sonarr and Radarr integrations. I've tried using the website, searching for solutions, and even asked ChatGPT, but I haven't been able to get it working.</p> <p>Could someone review my code and help me add the calendar to show upcoming shows and movies?</p> <pre><code>--- # For configuration options and examples, please see: # https://gethomepage.dev/en/configs/services - calendar: - agenda: widget: type: calendar firstDayInWeek: sunday view: monthly maxEvents: 10 showTime: true integrations: - type: sonarr service_group: Media service_name: Sonarr color: teal params: unmonitored: true - Media Management: - Radarr: icon: radarr.png href: http://192.168.4.2:7878 description: Movie Management container: radarr widget: type: radarr url: http://192.168.4.2:7878 key: (deleted) - Sonarr: icon: sonarr.png href: http://192.168.4.2:8

