# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Cloud File Server with SMB access?
 - [https://www.reddit.com/r/selfhosted/comments/1glb5sa/cloud_file_server_with_smb_access](https://www.reddit.com/r/selfhosted/comments/1glb5sa/cloud_file_server_with_smb_access)
 - RSS feed: $source
 - date published: 2024-11-06T22:32:37+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m sorry in advance - English is not my first language, so I&#39;m trying my best to explain myself.</p> <p><strong>TL;DR: While at home, i want to access my shares via SMB but also to be able to access same files though anywhere on internet. Any software suggestions?</strong></p> <p>So long story short, i had my first self-built NAS for quite a few years. It was nothing special yet very small, some old 4-core Intel Atom with 4 GB DDR2 and 2x 1 TB HDDs in RAID-1. It was running Ubuntu Server, RAID was built using mdadm, there were also qBittorrent, PLEX and a simple web server running my &quot;business card&quot;.</p> <p>Last year i bought some hardware to build a &quot;proper&quot; NAS - Node 304, ITX mb w/ i3 9100T and 16 GB of DDR4 RAM, 2x 2TB Ironwolf&#39;s (ST2000VN004). Also took a Samsung 980 250GB from my older PC as my boot drive, additional 2.5 WD Blue 500 GB SSD for VMs and containers and 1x 1TB HDD from the previous NAS to back up th

## Subdomain for free newbie questions
 - [https://www.reddit.com/r/selfhosted/comments/1glajob/subdomain_for_free_newbie_questions](https://www.reddit.com/r/selfhosted/comments/1glajob/subdomain_for_free_newbie_questions)
 - RSS feed: $source
 - date published: 2024-11-06T22:05:54+00:00

<!-- SC_OFF --><div class="md"><p>I am new to the whole DNS / reverse proxy coolness, so please help me out.</p> <p>I have a dynamic dns service via my router interface which allows me to access services via port forwarding. It’s messy as not all do https etc.</p> <p>What is the most idiot proof and free way to get something like:</p> <p><a href="https://service1.mydomain.somefreednsdomain.org">https://service1.mydomain.somefreednsdomain.org</a> -&gt; lanip1:port</p> <p><a href="https://service2.mydomain.somefreedns.org">https://service2.mydomain.somefreedns.org</a> -&gt; lanip2:port</p> <p>And with ssl and automatic cert renewal?</p> <p>I am not ready yet to commit to a monthly subscription for such services, I would like to see how it actually works for access from multiple platforms before.</p> <p>Specific use case would be jellyfin https on browser but also platform clients from both lan (so lan ip https access) and web (eg my android phone when commuting).</p> <p>I have looked a

## Load-Balancer / Reverse Proxy for self-hosted services
 - [https://www.reddit.com/r/selfhosted/comments/1glae8x/loadbalancer_reverse_proxy_for_selfhosted_services](https://www.reddit.com/r/selfhosted/comments/1glae8x/loadbalancer_reverse_proxy_for_selfhosted_services)
 - RSS feed: $source
 - date published: 2024-11-06T21:59:33+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I manage multiple self-hosted services across various instances, including Docker hosts and a k3s cluster. To simplify access, I’ve started consolidating these into a single entry point for all services. Currently, I use a cloud-based Layer 4 load balancer to distribute traffic across three backend nodes, each running Traefik and Consul. These Consul instances are clustered with both the k3s and Docker hosts, with all nodes connected through Tailscale. Traefik leverages Consul as its service discovery backend.</p> <p>While everything is working well, I’m encountering a challenge: I want to create a highly available setup with three independent Traefik instances across my nodes, but handling the <code>acme.json</code> file is problematic. Previously, in Traefik 1.x, <code>acme.json</code> could be stored in Consul’s key-value store, but in the newer versions, this feature is now behind a paywall. If it were available, it would s

## Remote Proxy Generator: Video proxy transcoding on another computer
 - [https://www.reddit.com/r/selfhosted/comments/1gl9uci/remote_proxy_generator_video_proxy_transcoding_on](https://www.reddit.com/r/selfhosted/comments/1gl9uci/remote_proxy_generator_video_proxy_transcoding_on)
 - RSS feed: $source
 - date published: 2024-11-06T21:36:15+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gl9uci/remote_proxy_generator_video_proxy_transcoding_on/"> <img src="https://external-preview.redd.it/xMwWF8cG6cYWJ71CC955I313wDyeSXceXyT9NxzqAtw.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=f3353aeec9a56663418ac3bf6ae0c9454da4f18c" alt="Remote Proxy Generator: Video proxy transcoding on another computer" title="Remote Proxy Generator: Video proxy transcoding on another computer" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/perecastor"> /u/perecastor </a> <br/> <span><a href="https://fractale.itch.io/remote-proxy-generator">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gl9uci/remote_proxy_generator_video_proxy_transcoding_on/">[comments]</a></span> </td></tr></table>

## Jellyfin external latency issue
 - [https://www.reddit.com/r/selfhosted/comments/1gl7kdf/jellyfin_external_latency_issue](https://www.reddit.com/r/selfhosted/comments/1gl7kdf/jellyfin_external_latency_issue)
 - RSS feed: $source
 - date published: 2024-11-06T20:00:22+00:00

<!-- SC_OFF --><div class="md"><p>I’m fairly new to self-hosting and have set up a Proxmox server with 128GB of RAM and an A6000 GPU (which I got for free). I know this setup might be overkill for a media server, but I’ve configured GPU passthrough for the LXC container running Jellyfin, which handles all my media services.</p> <p><strong>Internal Streaming Works Fine, But External Streaming Has Issues</strong></p> <p>When I stream movies or TV shows inside my home, everything works perfectly no issues with buffering or latency. However, my brother has been experiencing occasional latency when streaming, despite having a 1Gbps internet connection, while I have a 600/600 fiber connection. He says the lag happens sporadically, and when it does, it gets bad.</p> <p>Additionally, I set up a thin client PC I got from work for my father-in-law. He has the same 600/600 connection, but he can only stream content at 720p or lower without constant buffering, the PC itself uses a Intel HD Graph

## Best way to attach 4+ HDDs on my Raspberry Pi 4B?
 - [https://www.reddit.com/r/selfhosted/comments/1gl7bxn/best_way_to_attach_4_hdds_on_my_raspberry_pi_4b](https://www.reddit.com/r/selfhosted/comments/1gl7bxn/best_way_to_attach_4_hdds_on_my_raspberry_pi_4b)
 - RSS feed: $source
 - date published: 2024-11-06T19:51:09+00:00

<!-- SC_OFF --><div class="md"><p>I have a Raspberry Pi 4B that I use as a media server and I have 4 HDDs and 1 SSD with USB connection to attach, but the Pi only have 2 3.0 usb ports and when I connect more than 1 device, none of them works.</p> <p>I&#39;m searching for powered USB Hubs like Anker and Atolla, but dunno if this will work. </p> <p>Can anyone help me with that? Is there a better way to do that? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Bycce"> /u/Bycce </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gl7bxn/best_way_to_attach_4_hdds_on_my_raspberry_pi_4b/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gl7bxn/best_way_to_attach_4_hdds_on_my_raspberry_pi_4b/">[comments]</a></span>

## Alternative to Raspberry Pi 2 model B
 - [https://www.reddit.com/r/selfhosted/comments/1gl75t2/alternative_to_raspberry_pi_2_model_b](https://www.reddit.com/r/selfhosted/comments/1gl75t2/alternative_to_raspberry_pi_2_model_b)
 - RSS feed: $source
 - date published: 2024-11-06T19:44:02+00:00

<!-- SC_OFF --><div class="md"><p>Hello!</p> <p>I&#39;ve portainer running or RPi as you know it&#39;s the ravages of time are already taking their toll. I need something new especially something on 64 bit architecture.</p> <p>I was thinking about HP T620 or something like that that consumes pretty small amount of energy but is powerful than the RPi. Or do you have any other suggestions?</p> <p>I would like to run portainer, mealie, jellyfin, sonarr, radarr, uptime kuma and home assistant on it.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ConnectionTasty1197"> /u/ConnectionTasty1197 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gl75t2/alternative_to_raspberry_pi_2_model_b/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gl75t2/alternative_to_raspberry_pi_2_model_b/">[comments]</a></span>

## hosting question with the arrs and the fins
 - [https://www.reddit.com/r/selfhosted/comments/1gl6dl0/hosting_question_with_the_arrs_and_the_fins](https://www.reddit.com/r/selfhosted/comments/1gl6dl0/hosting_question_with_the_arrs_and_the_fins)
 - RSS feed: $source
 - date published: 2024-11-06T19:11:00+00:00

<!-- SC_OFF --><div class="md"><p>I see a bunch of different methods but my question is if i host the arr software on my admin server and the jellyfin and jellyseer software on my family server will there be any issues? my setup is a 5 server prox cluster 1gig lan and all my libraries are ran on a TrueNAS baremetal server. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/theannihilator"> /u/theannihilator </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gl6dl0/hosting_question_with_the_arrs_and_the_fins/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gl6dl0/hosting_question_with_the_arrs_and_the_fins/">[comments]</a></span>

## Simple, well designed, invoicing software?
 - [https://www.reddit.com/r/selfhosted/comments/1gl5zyi/simple_well_designed_invoicing_software](https://www.reddit.com/r/selfhosted/comments/1gl5zyi/simple_well_designed_invoicing_software)
 - RSS feed: $source
 - date published: 2024-11-06T18:55:21+00:00

<!-- SC_OFF --><div class="md"><p>I’m trying to move off Freshbooks at my small creative dev studio. Their UX is great, it&#39;s really polished. But they’ve hiked the price twice in recent years, and now it’s $360 a year, and we don&#39;t need any of the advanced features like email reminders, paypal/stripe integration etc. Just a regular invoice creation, simple recurring invoices, and functional incremental invoice number.</p> <p>But I&#39;m shocked! There’s no straightforward, well-designed, self-hostable invoicing software out there. Or I couldn&#39;t find one. In a market full of bloated, overpriced tools, nobody’s built something simple that small companies can use without being charged per client.</p> <p>Should I make one?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Momciloo"> /u/Momciloo </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gl5zyi/simple_well_designed_invoicing_software/">[link]</a></span> &#32; <s

## Sending a notification when my public IP address is renewed
 - [https://www.reddit.com/r/selfhosted/comments/1gl4t7o/sending_a_notification_when_my_public_ip_address](https://www.reddit.com/r/selfhosted/comments/1gl4t7o/sending_a_notification_when_my_public_ip_address)
 - RSS feed: $source
 - date published: 2024-11-06T18:05:48+00:00

<!-- SC_OFF --><div class="md"><p>Hi, my ip chages every 12 hours and i want to keep track of last time it changed. im currently using:<a href="https://github.com/favonia/cloudflare-ddns">cloudflare-ddns</a> It seems to have shoutrrr integration to send a notification to my gorify which seems perfect for me. But i dont know how to use it. Any suggestions?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rgmelkor"> /u/rgmelkor </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gl4t7o/sending_a_notification_when_my_public_ip_address/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gl4t7o/sending_a_notification_when_my_public_ip_address/">[comments]</a></span>

## Youtube channel mirror/cloning
 - [https://www.reddit.com/r/selfhosted/comments/1gl4isj/youtube_channel_mirrorcloning](https://www.reddit.com/r/selfhosted/comments/1gl4isj/youtube_channel_mirrorcloning)
 - RSS feed: $source
 - date published: 2024-11-06T17:54:11+00:00

<!-- SC_OFF --><div class="md"><p>Hi!</p> <p>I&#39;ve been looking for a self hosted / VPS-hosted solution to keep an online, **publicly accessible** mirror of my YouTube channel. Any idea how to do it? I&#39;d like it to be &quot;in-sync&quot; with my YouTube video posting.</p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Aromatic-Clerk134"> /u/Aromatic-Clerk134 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gl4isj/youtube_channel_mirrorcloning/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gl4isj/youtube_channel_mirrorcloning/">[comments]</a></span>

## I made a simple note-taking app inspired by "One Big Text File" with seamless webpage archiving
 - [https://www.reddit.com/r/selfhosted/comments/1gl3sqh/i_made_a_simple_notetaking_app_inspired_by_one](https://www.reddit.com/r/selfhosted/comments/1gl3sqh/i_made_a_simple_notetaking_app_inspired_by_one)
 - RSS feed: $source
 - date published: 2024-11-06T17:23:34+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gl3sqh/i_made_a_simple_notetaking_app_inspired_by_one/"> <img src="https://external-preview.redd.it/u5ANAvG9x-vBINtNlm9z39higoPDgkU-k5iBVFEbk_0.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=920853d2abe2ca97da414da62c06f69400d96e03" alt="I made a simple note-taking app inspired by &quot;One Big Text File&quot; with seamless webpage archiving" title="I made a simple note-taking app inspired by &quot;One Big Text File&quot; with seamless webpage archiving" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/freetonik"> /u/freetonik </a> <br/> <span><a href="https://github.com/freetonik/textpod">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gl3sqh/i_made_a_simple_notetaking_app_inspired_by_one/">[comments]</a></span> </td></tr></table>

## Do I really need a home server?
 - [https://www.reddit.com/r/selfhosted/comments/1gl2mc4/do_i_really_need_a_home_server](https://www.reddit.com/r/selfhosted/comments/1gl2mc4/do_i_really_need_a_home_server)
 - RSS feed: $source
 - date published: 2024-11-06T16:34:25+00:00

<!-- SC_OFF --><div class="md"><p>Hi all. So far I&#39;ve been using a free VPS instance for some small flask/python projects and just a playground basically for random docker containers. But now I want to deal with some private data like backing up Bitwarden, contacts, firefly-iii and a samba server for the two computers we use at home and do automatic backups. Plus Home Assistant potentially for 4-5 ZigBee devices I want to buy.</p> <p>Do I really need a home server 24/7?</p> <p>I was all excited until I thought I can just run web-apps &quot;on demand&quot;. But can&#39;t think of alternatives for these:</p> <ul> <li>Home Assistant. I could just connect the few ZigBee devices with a ZigBee bridge.</li> <li>Storage and backups. It would be nice to have a shared drive between the two that I can backup overnight. Can I run scheduled backups without a server that trigger only when the computer is on?</li> </ul> <p>I have a laptop with a broken screen but with a mSATA and a SSD that wou

## Looking for a hostable P2P file sharing service
 - [https://www.reddit.com/r/selfhosted/comments/1gl1nq0/looking_for_a_hostable_p2p_file_sharing_service](https://www.reddit.com/r/selfhosted/comments/1gl1nq0/looking_for_a_hostable_p2p_file_sharing_service)
 - RSS feed: $source
 - date published: 2024-11-06T15:53:16+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a way to share files between devices that have various firewall restrictions in a temporary fashion, any recommendations? Specifically, here is what I&#39;m looking for:</p> <ul> <li><strong>Self-hosted (obviously):</strong> It&#39;s just generally a better, snappier experience when you have your own resources.</li> <li><strong>No WebTorrent or requirements beyond HTTP/HTTPS access for users:</strong> Many of my users have networks that are heavily restricted or behind NAT, so everything should be possible over a standard web connection.</li> <li><strong>WebUI:</strong> For the sake of convenience, it would be nice to not have to download a client to use this tool.</li> <li><strong>No file storage on the server itself:</strong> The server should simply act as a relay to send the files from one client to another. This is not only to preserve privacy, but also so that I don&#39;t have to worry about files clogging up my storage on t

## Looking for an alternative to youtubedl-material: download from any site and multi user support
 - [https://www.reddit.com/r/selfhosted/comments/1gl0yhn/looking_for_an_alternative_to_youtubedlmaterial](https://www.reddit.com/r/selfhosted/comments/1gl0yhn/looking_for_an_alternative_to_youtubedlmaterial)
 - RSS feed: $source
 - date published: 2024-11-06T15:22:16+00:00

<!-- SC_OFF --><div class="md"><p>Hi!</p> <p>As the title says, I am looking for an alternative to youtubedl-material, due to the fact that the projects seems no longer supported and/or developed.</p> <p>What I need is:</p> <ul> <li>download ideally from any website supported by yt-dlp backend</li> <li>multi user support, where each user manages its own media</li> </ul> <p>Can you suggest me something? Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Head_Artichoke"> /u/Head_Artichoke </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gl0yhn/looking_for_an_alternative_to_youtubedlmaterial/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gl0yhn/looking_for_an_alternative_to_youtubedlmaterial/">[comments]</a></span>

## So whats the best way to run a reverse proxy?
 - [https://www.reddit.com/r/selfhosted/comments/1gl0mmf/so_whats_the_best_way_to_run_a_reverse_proxy](https://www.reddit.com/r/selfhosted/comments/1gl0mmf/so_whats_the_best_way_to_run_a_reverse_proxy)
 - RSS feed: $source
 - date published: 2024-11-06T15:07:53+00:00

<!-- SC_OFF --><div class="md"><p>Been self hosting for a couple years and have seen the discussion of running a reverse proxy for exposing self hosted systems but never really understood the best way to do so. lately ive had some more interest in possibly getting one running so what is the best way to do so?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/carminehk"> /u/carminehk </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gl0mmf/so_whats_the_best_way_to_run_a_reverse_proxy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gl0mmf/so_whats_the_best_way_to_run_a_reverse_proxy/">[comments]</a></span>

## Self hosted diff tool with web sockets?
 - [https://www.reddit.com/r/selfhosted/comments/1gkztm6/self_hosted_diff_tool_with_web_sockets](https://www.reddit.com/r/selfhosted/comments/1gkztm6/self_hosted_diff_tool_with_web_sockets)
 - RSS feed: $source
 - date published: 2024-11-06T14:31:24+00:00

<!-- SC_OFF --><div class="md"><p>Is there such a thing that allows two people on different computers to enter text and then have a diff run live highlighting the differences that&#39;s self hosted? TBF I don&#39;t even know if there&#39;s such a thing that&#39;s not self hosted!</p> <p>Cheers. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nickweb"> /u/nickweb </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkztm6/self_hosted_diff_tool_with_web_sockets/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkztm6/self_hosted_diff_tool_with_web_sockets/">[comments]</a></span>

## Stop traffic from going through OpenVPN
 - [https://www.reddit.com/r/selfhosted/comments/1gkzq78/stop_traffic_from_going_through_openvpn](https://www.reddit.com/r/selfhosted/comments/1gkzq78/stop_traffic_from_going_through_openvpn)
 - RSS feed: $source
 - date published: 2024-11-06T14:26:53+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve set up OpenVPN server, and when I connect to it, my public IP address changes to that of the OpenVPN node, and Internet slows down significantly. </p> <p>My server config is: ``` port [REDACTED] proto udp dev tun</p> <h1>user nobody</h1> <h1>group nobody</h1> <p>persist-key persist-tun keepalive 10 120 topology subnet server 10.8.0.0 255.255.255.0 ifconfig-pool-persist ipp.txt</p> <h1>push &quot;dhcp-option DNS [REDACTED]&quot;</h1> <h1>push &quot;dhcp-option DOMAIN internal&quot;</h1> <h1>push &quot;redirect-gateway def1 bypass-dhcp&quot;</h1> <h1>push &quot;route 10.8.0.0 255.255.255.255&quot;</h1> <p>dh none ecdh-curve [REDACTED] tls-crypt tls-crypt.key crl-verify crl.pem ca ca.crt cert server<em>[REDACTED].crt key server</em>[REDACTED].key auth SHA256 cipher [REDACTED] ncp-ciphers [REDACTED] tls-server tls-version-min 1.2 tls-cipher [REDACTED] client-config-dir /etc/openvpn/ccd status /var/log/openvpn/status.log verb 3 ```</p> <p>And my 

## My selfhosted services (for now)
 - [https://www.reddit.com/r/selfhosted/comments/1gkzok5/my_selfhosted_services_for_now](https://www.reddit.com/r/selfhosted/comments/1gkzok5/my_selfhosted_services_for_now)
 - RSS feed: $source
 - date published: 2024-11-06T14:24:47+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gkzok5/my_selfhosted_services_for_now/"> <img src="https://b.thumbs.redditmedia.com/WS5tz8Wiaa1DxeVKBCi8sPtnY3k1cRJWQxlY5JO00lw.jpg" alt="My selfhosted services (for now)" title="My selfhosted services (for now)" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi all, this is my humble dashboard, created with homepage. For now I am happy with it. The majority of the services are hosted on a mini PC with an N100, some of them are for the moment on a RPi4B.</p> <p>Does someone know why the NPM widget does not return the correct number of enabled/disabled proxies? The API works since the total one is correct.</p> <p><a href="https://preview.redd.it/9ox6jx7mjazd1.png?width=1045&amp;format=png&amp;auto=webp&amp;s=2c63d3103e1c189f3bd825e55e3799be14e8e68f">https://preview.redd.it/9ox6jx7mjazd1.png?width=1045&amp;format=png&amp;auto=webp&amp;s=2c63d3103e1c189f3bd825e55e3799be14e8e68f</a></p> </div><!-- SC_ON --> &#32

## Debian vs NAS OS for a "container Box"?
 - [https://www.reddit.com/r/selfhosted/comments/1gkzgrg/debian_vs_nas_os_for_a_container_box](https://www.reddit.com/r/selfhosted/comments/1gkzgrg/debian_vs_nas_os_for_a_container_box)
 - RSS feed: $source
 - date published: 2024-11-06T14:15:09+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m getting a NUC to take over &quot;Server Duties&quot; from my Synology NAS and am unsure on the OS i should go with. It&#39;ll primarily be used for Nextcloud and a bunch of other Services for a single or two Users (audiobookshelf, immich, Homeautomation). I like Debian as a Server OS a lot and am sure it can do everything i need it too. But TrueNAS or Unraid might be a bit &quot;easier&quot; to set up. The Machine will not be pulling NAS Duties (for now). Storage will stay on the Synology NAS.</p> <p>So, what would you do? Debian and do it manually, or run some preconfigure NAS OS?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/domsch1988"> /u/domsch1988 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkzgrg/debian_vs_nas_os_for_a_container_box/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkzgrg/debian_vs_nas_os_for_a_container_box/">[com

## Beelink EQ12 or EQ13?
 - [https://www.reddit.com/r/selfhosted/comments/1gkz9zi/beelink_eq12_or_eq13](https://www.reddit.com/r/selfhosted/comments/1gkz9zi/beelink_eq12_or_eq13)
 - RSS feed: $source
 - date published: 2024-11-06T14:06:13+00:00

<!-- SC_OFF --><div class="md"><p>Hey folks,</p> <p>I&#39;m looking to upgrade my self-hosted setup while keeping power consumption low, so I&#39;m considering a mini PC. My plan is to offload most of the Docker containers currently running on my NAS (Synology DS224+) to free up more resources. I might also spin up a few VMs. Since I&#39;m running Plex, I need a CPU that supports hardware transcoding, and I&#39;ve been eyeing the N100 and N200 CPUs.</p> <p>I saw that Beelink has the EQ12 (N100, DDR5) and EQ13 (N200, DDR4) at similar price points. Any thoughts on which one would be better for my needs? Would the DDR5 make a bigger difference than the CPU? I&#39;m thinking about future-proofing, so having the possibility to add a decent amount of RAM is definitely a plus which makes me lean towards DDR5.</p> <p>Anything I am missing?</p> <p>Alternatively, are there any other mini PCs under $300/€300 that you&#39;d recommend for better performance without pushing up the power consumptio

## homepage layout question about columns and rows. Please help me
 - [https://www.reddit.com/r/selfhosted/comments/1gkz88q/homepage_layout_question_about_columns_and_rows](https://www.reddit.com/r/selfhosted/comments/1gkz88q/homepage_layout_question_about_columns_and_rows)
 - RSS feed: $source
 - date published: 2024-11-06T14:03:51+00:00

<!-- SC_OFF --><div class="md"><p>Hello</p> <p>I have made my first gethomepage/homepage homelab dashboard, just for fun. and i wonder if it is possible to populate bookmarks from 2 categories into one column? so lets say i have 3 columns. and the last one is filled with my bookmarks. is it possible to populate a 2nd bookmark category into that specific column under the other one?</p> <p>please help me out. i have studied the docs. but i cant find anything.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Odd_Astronomer_9279"> /u/Odd_Astronomer_9279 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkz88q/homepage_layout_question_about_columns_and_rows/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkz88q/homepage_layout_question_about_columns_and_rows/">[comments]</a></span>

## Postbaby - a localStorage-based sticky-note app with intuitive keybindings, and desktop/mobile support.
 - [https://www.reddit.com/r/selfhosted/comments/1gkyzky/postbaby_a_localstoragebased_stickynote_app_with](https://www.reddit.com/r/selfhosted/comments/1gkyzky/postbaby_a_localstoragebased_stickynote_app_with)
 - RSS feed: $source
 - date published: 2024-11-06T13:52:42+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gkyzky/postbaby_a_localstoragebased_stickynote_app_with/"> <img src="https://external-preview.redd.it/wuGd_gRQdx23FBz1fSPaF2ulZcNv0CfWaHVPuz2_AWM.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=a58b037e9be765918330b7aead1cb1e568603058" alt="Postbaby - a localStorage-based sticky-note app with intuitive keybindings, and desktop/mobile support." title="Postbaby - a localStorage-based sticky-note app with intuitive keybindings, and desktop/mobile support." /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>a lightweight, hassle-free alternative to traditional sticky notes, ideal for those who need to organize, rearrange, and color-code notes seamlessly. This has been my daily-driver, as I have switched over from using OneNote, to this, as it&#39;s been a much better tool to brainstorm ideas, and get a gestalt view of my projects. 😄</p> <p>Future Plans:</p> <p>- implement OAuth for cloud storage on the prod version

## Cloudflared tunnel quic not working bridge network
 - [https://www.reddit.com/r/selfhosted/comments/1gky2bg/cloudflared_tunnel_quic_not_working_bridge_network](https://www.reddit.com/r/selfhosted/comments/1gky2bg/cloudflared_tunnel_quic_not_working_bridge_network)
 - RSS feed: $source
 - date published: 2024-11-06T13:07:06+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,<br/> quick help if possible from you guys, I&#39;ve cloudflared tunnel up to my zero trust network<br/> I&#39;m using quick protocol<br/> it is not connecting and fallback to HTTP<br/> when I created the container to be on the host network, it worked with no problems.</p> <p>may I know why? and how can I make it work while on bridge network</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Amour86"> /u/Amour86 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gky2bg/cloudflared_tunnel_quic_not_working_bridge_network/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gky2bg/cloudflared_tunnel_quic_not_working_bridge_network/">[comments]</a></span>

## Any good "meetups" in NYC?/North NJ?
 - [https://www.reddit.com/r/selfhosted/comments/1gkxqjq/any_good_meetups_in_nycnorth_nj](https://www.reddit.com/r/selfhosted/comments/1gkxqjq/any_good_meetups_in_nycnorth_nj)
 - RSS feed: $source
 - date published: 2024-11-06T12:50:03+00:00

<!-- SC_OFF --><div class="md"><p>I haven&#39;t checked <a href="http://meetup.com">meetup.com</a> yet, but maybe you folks already have some that you like. </p> <p>Thanks so much </p> <p>Joe</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/virgoworx"> /u/virgoworx </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkxqjq/any_good_meetups_in_nycnorth_nj/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkxqjq/any_good_meetups_in_nycnorth_nj/">[comments]</a></span>

## Self hosted data gathering
 - [https://www.reddit.com/r/selfhosted/comments/1gkw1hp/self_hosted_data_gathering](https://www.reddit.com/r/selfhosted/comments/1gkw1hp/self_hosted_data_gathering)
 - RSS feed: $source
 - date published: 2024-11-06T11:09:05+00:00

<!-- SC_OFF --><div class="md"><p>I’m looking for a tool similar to SuperMetrics, Weld or Tableau that’s self hosted.</p> <p>Ideally need to combine some of the following databases: Microsoft Dynamics CRM Google Analytics Social Media marketing stats Sage</p> <p>We tend to use PowerBI for reporting but can be flexible. </p> <p>Does anything exist?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tcoysh"> /u/tcoysh </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkw1hp/self_hosted_data_gathering/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkw1hp/self_hosted_data_gathering/">[comments]</a></span>

## DuckDNS problems
 - [https://www.reddit.com/r/selfhosted/comments/1gkvewr/duckdns_problems](https://www.reddit.com/r/selfhosted/comments/1gkvewr/duckdns_problems)
 - RSS feed: $source
 - date published: 2024-11-06T10:24:57+00:00

<!-- SC_OFF --><div class="md"><p>Is anyone else also lately having issues with DuckDNS? It seems like the DNS does not resolve my IP until I do not do a few requests towards the endpoints.</p> <p>I just started using DuckDNS a few weeks ago. Is there anyone who is using it for a longer time period and has good experience with it? Or do you guys prefer any other DynDNS providers?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mordax777"> /u/mordax777 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkvewr/duckdns_problems/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkvewr/duckdns_problems/">[comments]</a></span>

## Do you rely on Proxmox Firewall?
 - [https://www.reddit.com/r/selfhosted/comments/1gkv9wh/do_you_rely_on_proxmox_firewall](https://www.reddit.com/r/selfhosted/comments/1gkv9wh/do_you_rely_on_proxmox_firewall)
 - RSS feed: $source
 - date published: 2024-11-06T10:14:51+00:00

<!-- SC_OFF --><div class="md"><p>IF YOU DO NOT even use Proxmox stack, please do NOT vote.</p> <p>NOTE If you use e.g. an external firewall appliance, but ALSO use the built-in one of a Proxmox host, then you do <em>NOT</em> <em>rely</em> on Proxmox Firewall, or you only rely on it partially.</p> <p><a href="https://www.reddit.com/poll/1gkv9wh">View Poll</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/esiy0676"> /u/esiy0676 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkv9wh/do_you_rely_on_proxmox_firewall/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkv9wh/do_you_rely_on_proxmox_firewall/">[comments]</a></span>

## Strapi Template on Microtica Updated to Version 5
 - [https://www.reddit.com/r/selfhosted/comments/1gkv423/strapi_template_on_microtica_updated_to_version_5](https://www.reddit.com/r/selfhosted/comments/1gkv423/strapi_template_on_microtica_updated_to_version_5)
 - RSS feed: $source
 - date published: 2024-11-06T10:02:39+00:00

<!-- SC_OFF --><div class="md"><p>Hi Strapi enthusiasts! Just a heads up that Microtica has released version 5 (5.2.0) of their Strapi Template. This update is aimed at making Strapi easier to scale and monitor with new integration features and a faster deployment process. Here are a few highlights:</p> <ul> <li>Strapi 5 upgrade with more customization options.</li> <li>Integrated monitoring and scaling support through Microtica.</li> <li>Streamlined deployment to improve automation and observability.</li> </ul> <p>For those managing content-heavy projects with Strapi, it could be worth <a href="https://docs.microtica.com/changelog#AonBH">checking out</a> how these updates support easier scaling and performance monitoring.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/a-s-micro"> /u/a-s-micro </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkv423/strapi_template_on_microtica_updated_to_version_5/">[link]</a></span> &#32

## Discover a self-hosted alternative to Confluence: Live XWiki demo!
 - [https://www.reddit.com/r/selfhosted/comments/1gkuu6v/discover_a_selfhosted_alternative_to_confluence](https://www.reddit.com/r/selfhosted/comments/1gkuu6v/discover_a_selfhosted_alternative_to_confluence)
 - RSS feed: $source
 - date published: 2024-11-06T09:42:31+00:00

<!-- SC_OFF --><div class="md"><p>If you’re exploring self-hosted alternatives to Confluence or just want more control and flexibility over your wiki setup, you won’t want to miss this. We’re hosting a <strong>free live webinar</strong> on <strong>November 28, 2024, at 16:00 CET</strong> to show you how <a href="/r/XWiki">r/XWiki</a> can make your migration simple and efficient.</p> <h1>What’s in it for you?</h1> <ul> <li>Step-by-step guidance on migrating from Confluence to a fully self-hosted XWiki setup—no lost data, no broken links.</li> <li>See XWiki in action: We’ll do a <strong>live demo</strong> so you can understand how it handles real-world migration challenges.</li> <li>Hear success stories from others who’ve taken the leap and improved their collaboration with XWiki’s flexibility.</li> <li>We’ll wrap up with a <strong>Q&amp;A session</strong> to answer your questions about self-hosting XWiki or anything technical.</li> </ul> <p>Whether you’re tired of relying on proprieta

## don't know if self-hosting LLMs is worth the trade-off for security
 - [https://www.reddit.com/r/selfhosted/comments/1gkuu69/dont_know_if_selfhosting_llms_is_worth_the](https://www.reddit.com/r/selfhosted/comments/1gkuu69/dont_know_if_selfhosting_llms_is_worth_the)
 - RSS feed: $source
 - date published: 2024-11-06T09:42:29+00:00

<!-- SC_OFF --><div class="md"><p>Im trying to self-host a chatbot as everyone says it&#39;s way more secure, but no one talks about the downside</p> <p>I&#39;m not a coding whiz, so I thought it&#39;d be a fun project… big mistake, the costs are piling up and I&#39;m spending way too much time googling every little issue. I&#39;m using Llama and need to borrow my friend&#39;s GPU just to test it out.</p> <p>Anyone else been through this? Any good resources for noobs like me, or maybe a chatgpt alternative to end this nightmare? :)) </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Thomasnn"> /u/Thomasnn </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkuu69/dont_know_if_selfhosting_llms_is_worth_the/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkuu69/dont_know_if_selfhosting_llms_is_worth_the/">[comments]</a></span>

## Share documents with clients
 - [https://www.reddit.com/r/selfhosted/comments/1gktviq/share_documents_with_clients](https://www.reddit.com/r/selfhosted/comments/1gktviq/share_documents_with_clients)
 - RSS feed: $source
 - date published: 2024-11-06T08:31:09+00:00

<!-- SC_OFF --><div class="md"><p>I have a friend that is an accountant and constantly needs customers to share documents with him.</p> <p>He asked me if there is a tool that: He creates a folder for each customer on his environment/service/server where the customer could upload files into it.</p> <p>I thought about Nextcloud but it is offers so much more where could possibly confuse the non tech customers.</p> <p>Any ideas of a simple tool for that simple task only?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OscarCY"> /u/OscarCY </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gktviq/share_documents_with_clients/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gktviq/share_documents_with_clients/">[comments]</a></span>

## Netcup NAT?
 - [https://www.reddit.com/r/selfhosted/comments/1gkslto/netcup_nat](https://www.reddit.com/r/selfhosted/comments/1gkslto/netcup_nat)
 - RSS feed: $source
 - date published: 2024-11-06T07:02:16+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a vps provider and went with netcup (can&#39;t afford hetzner verification) </p> <p>Gonna set up a coturn server so I wanna be certain that a netcup vps will not have NAT</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Super_Effective1203"> /u/Super_Effective1203 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkslto/netcup_nat/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkslto/netcup_nat/">[comments]</a></span>

## Is a VPS a good option for hosting game servers?
 - [https://www.reddit.com/r/selfhosted/comments/1gksghk/is_a_vps_a_good_option_for_hosting_game_servers](https://www.reddit.com/r/selfhosted/comments/1gksghk/is_a_vps_a_good_option_for_hosting_game_servers)
 - RSS feed: $source
 - date published: 2024-11-06T06:52:44+00:00

<!-- SC_OFF --><div class="md"><p>I want to set up a game server and noticed VPS providers like <a href="https://www.ssdnodes.com/">SSD Nodes</a> offer high specs. Anyone tried using VPS for gaming servers, and how’s the performance?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok_Satisfaction503"> /u/Ok_Satisfaction503 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gksghk/is_a_vps_a_good_option_for_hosting_game_servers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gksghk/is_a_vps_a_good_option_for_hosting_game_servers/">[comments]</a></span>

## Can't access domain on wifi using CF tunnels
 - [https://www.reddit.com/r/selfhosted/comments/1gkqfbd/cant_access_domain_on_wifi_using_cf_tunnels](https://www.reddit.com/r/selfhosted/comments/1gkqfbd/cant_access_domain_on_wifi_using_cf_tunnels)
 - RSS feed: $source
 - date published: 2024-11-06T04:42:32+00:00

<!-- SC_OFF --><div class="md"><p>I was using HAProxy to have some access to servers outside the network. I chose to use cloudflare tunnels instead. It worked fine for a couple of days and now I cannot access my domain inside my network. This only happens on Wi-Fi though. I use Unify APs and can&#39;t see any issues there. If I go to cellular it connects immediately. I don&#39;t have private relay or a vpn on.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Shades228"> /u/Shades228 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkqfbd/cant_access_domain_on_wifi_using_cf_tunnels/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkqfbd/cant_access_domain_on_wifi_using_cf_tunnels/">[comments]</a></span>

## Proxmox nodes and fail overs
 - [https://www.reddit.com/r/selfhosted/comments/1gkoh80/proxmox_nodes_and_fail_overs](https://www.reddit.com/r/selfhosted/comments/1gkoh80/proxmox_nodes_and_fail_overs)
 - RSS feed: $source
 - date published: 2024-11-06T02:48:01+00:00

<!-- SC_OFF --><div class="md"><p>Been experimenting getting my machines on prox. Ox nodes nas/opnsense/Linux box&#39;s etc, in order to have everything managed by proxmox. </p> <p>Do you all have everything sitting on nodes? Curre tly my opnsense is standalone but having it run on proxmox, is assumed better because of snagshops making it easier to restore? </p> <p>Do you have a fail over system with your nodes? </p> <p>How do YOU personally bundle your nodes, several vms per node? Any methodology you feel is better or one machine per node, woth several vms? Or some other mix? Just getting ideas to better set up, so I cananage it better</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Trueleo1"> /u/Trueleo1 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkoh80/proxmox_nodes_and_fail_overs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkoh80/proxmox_nodes_and_fail_overs/">[comments]

## Most easiest stuff to host?
 - [https://www.reddit.com/r/selfhosted/comments/1gkobyz/most_easiest_stuff_to_host](https://www.reddit.com/r/selfhosted/comments/1gkobyz/most_easiest_stuff_to_host)
 - RSS feed: $source
 - date published: 2024-11-06T02:39:40+00:00

<!-- SC_OFF --><div class="md"><p>I have been trying for 2 days to get Matrix Synapse (LXC container in Proxmox) running as a server on my old PC. Besides with Caddy-LXC Container. Unfortunately without success.</p> <p>Then I tried Owntracks. Without success.</p> <p>What is the easiest selfhosting project to try?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/uffno"> /u/uffno </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkobyz/most_easiest_stuff_to_host/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkobyz/most_easiest_stuff_to_host/">[comments]</a></span>

## OPNsense or PFsense
 - [https://www.reddit.com/r/selfhosted/comments/1gknvt9/opnsense_or_pfsense](https://www.reddit.com/r/selfhosted/comments/1gknvt9/opnsense_or_pfsense)
 - RSS feed: $source
 - date published: 2024-11-06T02:14:34+00:00

<!-- SC_OFF --><div class="md"><p>im new to this self hosted stuff and iwant to run my own router, but i dont know what to use. opnsense, pfsense or openwrt. all i need is that it support fiber cause my isp uses fiber, adblocking, and port forward. i also want to run it on proxmox, is it good?</p> <p>appreciate all comment, Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Miclao"> /u/Miclao </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gknvt9/opnsense_or_pfsense/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gknvt9/opnsense_or_pfsense/">[comments]</a></span>

## Fail2Ban not properly working
 - [https://www.reddit.com/r/selfhosted/comments/1gknvof/fail2ban_not_properly_working](https://www.reddit.com/r/selfhosted/comments/1gknvof/fail2ban_not_properly_working)
 - RSS feed: $source
 - date published: 2024-11-06T02:14:22+00:00

<!-- SC_OFF --><div class="md"><p>I am using LinuxServers Swag instance as my reverse proxy on my Unraid machine. I am working on setting up Fail2Ban which is built into the Swag instance. I am testing this using my Vaultwarden container. I am able to see in the logs that Fail2Ban is banning the IP address in the logs, however, I am still able to access the website on the same IP address. It&#39;s clearly not getting properly blocked in Swag. Does anyone have any ideas?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/vesuvious911"> /u/vesuvious911 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gknvof/fail2ban_not_properly_working/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gknvof/fail2ban_not_properly_working/">[comments]</a></span>

## Has anyone gotten Bazarr to notify self-hosted Zulip?
 - [https://www.reddit.com/r/selfhosted/comments/1gkmczv/has_anyone_gotten_bazarr_to_notify_selfhosted](https://www.reddit.com/r/selfhosted/comments/1gkmczv/has_anyone_gotten_bazarr_to_notify_selfhosted)
 - RSS feed: $source
 - date published: 2024-11-06T00:53:41+00:00

<!-- SC_OFF --><div class="md"><p>I self-host Zulip. I&#39;ve tried a Slack url and a Slack compatible url using the Slack dropdown in Bazarr, and tried to build a Zulip url using the Zulip dropdown in Bazarr. I don&#39;t believe this latter supports topics in the webhook, which are required now in Zulip but perhaps once were not required.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/yroyathon"> /u/yroyathon </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkmczv/has_anyone_gotten_bazarr_to_notify_selfhosted/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gkmczv/has_anyone_gotten_bazarr_to_notify_selfhosted/">[comments]</a></span>

## Home Lab 2024 HA Options
 - [https://www.reddit.com/r/selfhosted/comments/1gklrle/home_lab_2024_ha_options](https://www.reddit.com/r/selfhosted/comments/1gklrle/home_lab_2024_ha_options)
 - RSS feed: $source
 - date published: 2024-11-06T00:24:00+00:00

<!-- SC_OFF --><div class="md"><p>Hey Guys,</p> <p>&#x200B;</p> <p>What are you doing in your environment to make it HA? How do you guys setup so you can loose a VM or two and things stay up.</p> <p>Are you running Kubernetes, Docker Swarm, Proxmox HA? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/xXAzazelXx1"> /u/xXAzazelXx1 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gklrle/home_lab_2024_ha_options/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gklrle/home_lab_2024_ha_options/">[comments]</a></span>

## Enough specs for the services I want to run
 - [https://www.reddit.com/r/selfhosted/comments/1gklr6c/enough_specs_for_the_services_i_want_to_run](https://www.reddit.com/r/selfhosted/comments/1gklr6c/enough_specs_for_the_services_i_want_to_run)
 - RSS feed: $source
 - date published: 2024-11-06T00:23:26+00:00

<!-- SC_OFF --><div class="md"><p>My machine is a chinese F2M mini machine, specs:<br/> Intel Core Ultra5 125H 14 cores 18 threads processor.<br/> Intel ARC igpu<br/> 16b ddr5, plannig to install 32gb.<br/> OS is Ubuntu headless install aon a 500gb ssd, second drive is samsunbg 990 pro 2tb for temporary storage. Will backup to external drive later,<br/> It has a 1gb ethernet.</p> <p>I have an usb powered 5gb spinnig rust, powered usb 8tb spinning rust and a powered usb 18tb spinning rust.</p> <p>My services I use are Jellyfin (for transcoding) and Deluge on bare metal. Immich, Nexcloud and Home Assistant are on docker.</p> <p>For home assistant I want to record 4 4k survaillenca camera stream at the same time on, which will be saved on the samsung 990 pro.</p> <p>After a few day Is will run a script to move the footage to multiple of the usb drives.</p> <p>Is it specced enough?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BusyAsshole"> /u/Bus

