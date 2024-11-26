# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Vaultwarden Security Concerns
 - [https://www.reddit.com/r/selfhosted/comments/1gzwqol/vaultwarden_security_concerns](https://www.reddit.com/r/selfhosted/comments/1gzwqol/vaultwarden_security_concerns)
 - RSS feed: $source
 - date published: 2024-11-25T23:02:10+00:00

<!-- SC_OFF --><div class="md"><p>I want to rent a vps and install vaultwarden in it. If I use it with domain and ssl certificate, can the vps company see my saved passwords?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Brilliant_Baseball79"> /u/Brilliant_Baseball79 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzwqol/vaultwarden_security_concerns/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzwqol/vaultwarden_security_concerns/">[comments]</a></span>

## All containers behind traefik with no internet access
 - [https://www.reddit.com/r/selfhosted/comments/1gzwp6d/all_containers_behind_traefik_with_no_internet](https://www.reddit.com/r/selfhosted/comments/1gzwp6d/all_containers_behind_traefik_with_no_internet)
 - RSS feed: $source
 - date published: 2024-11-25T23:00:35+00:00

<!-- SC_OFF --><div class="md"><p>Hi reddit. I have set up traefik with a few containers behind it. Everything works great! I want to block all containers other than traefik to access the Internet. How can I achieve it?</p> <p>I tried adding: </p> <pre><code>networks: proxy_internal: internal: true </code></pre> <p>to all of those (created with --internal) and only:</p> <pre><code>networks: proxy_internal: internal: true proxy: external: true </code></pre> <p>to traefik. With this configuration, I can reach only traefik. The others are &quot;gateway timeout&quot; issue.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Loud-Professional205"> /u/Loud-Professional205 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzwp6d/all_containers_behind_traefik_with_no_internet/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzwp6d/all_containers_behind_traefik_with_no_internet/">[comments]</a></sp

## Help troubleshoot Cloudflare tunnels
 - [https://www.reddit.com/r/selfhosted/comments/1gzwl1v/help_troubleshoot_cloudflare_tunnels](https://www.reddit.com/r/selfhosted/comments/1gzwl1v/help_troubleshoot_cloudflare_tunnels)
 - RSS feed: $source
 - date published: 2024-11-25T22:55:36+00:00

<!-- SC_OFF --><div class="md"><p>Hello! </p> <p>I recently built a home server with Proxmox intended for homelab and practical use with Nextcloud and Plex. The computer itself is an ITX build with the capacity of six 3.5 inch drives, and is overall amazing. </p> <p>The problem I am currently facing is Cloudflare tunneling to my Nextcloud LXC on Proxmox. I have installed and connected the Cloudflared LXC on my home server to a Cloudflare tunnel, and the tunnel has the status &quot;healthy&quot; but I cannot (even though the connection is healthy and is routed to the correct internal Cloudflared IP-address) access Nextcloud through my domain.</p> <p>Things to keep in mind is that I am within a CGNAT without a public IP-adress (This could be the problem)</p> <p>What I on the other hand think is wierd is that the tunnel has the status HEALTHY and can infact find the precise local IP of the Cloudflared LXC. </p> <p>This issue may or may not be solveable at all, but I just wanted to reach

## Planning to expose Immich to the Internet - any warnings, lessons learned, etc.?
 - [https://www.reddit.com/r/selfhosted/comments/1gzw1mq/planning_to_expose_immich_to_the_internet_any](https://www.reddit.com/r/selfhosted/comments/1gzw1mq/planning_to_expose_immich_to_the_internet_any)
 - RSS feed: $source
 - date published: 2024-11-25T22:32:47+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been using Immich for some time and it&#39;s perfect for my use case, which is basically replacing Google Photos. All devices in the immediate family are tied into the home network using some combination of Wireguard and Tailscale, so our content can be synced and accessed from anywhere securely through a tunnel.</p> <p>The one Google Photos feature I&#39;m missing is sharing photos by link to anonymous users, which Immich of course can do, but it requires exposing Immich to the internet. My one rule up to this point has been to never expose anything to the Internet except the VPN, as it&#39;s pen-tested, hardened, designed to be exposed to the internet.</p> <p>My Immich instance is segregated from the rest of the network, and it&#39;s containerized on the machine it runs on, so I&#39;m not too worried about potential attacks escaping it. That said, I am worried about attackers accessing Immich directly, because it contains photos of my fami

## Another DDNS Question
 - [https://www.reddit.com/r/selfhosted/comments/1gzuqfm/another_ddns_question](https://www.reddit.com/r/selfhosted/comments/1gzuqfm/another_ddns_question)
 - RSS feed: $source
 - date published: 2024-11-25T21:39:30+00:00

<!-- SC_OFF --><div class="md"><p>Hi All</p> <p>Im installed Qdm12 DDNS Updater (<a href="https://github.com/qdm12/ddns-updater">https://github.com/qdm12/ddns-updater</a>) via the binary files (Go method) and and so far everything is working,</p> <p>I do have 2 questions though:</p> <p>1-Do i need to add a cron job to the run to run automatically?</p> <p>The website says it updates every 5 minutes but unless my ip has changed, I&#39;ve got no other way to test this!!</p> <p>2-Cant seem to get the webui to run.</p> <p>I&#39;ve open my port on my router (8000) and pointed to my server but no dice</p> <p>*Update looks like another program is using port 8000, is there a chance i can change the port on this script?</p> <p>**Linux noob here, so please be patient with me as i&#39;ll hoping someone can offer any advise please?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sound2006"> /u/Sound2006 </a> <br/> <span><a href="https://www.reddit.com/r/self

## What minipc for selfhosting?
 - [https://www.reddit.com/r/selfhosted/comments/1gztrd5/what_minipc_for_selfhosting](https://www.reddit.com/r/selfhosted/comments/1gztrd5/what_minipc_for_selfhosting)
 - RSS feed: $source
 - date published: 2024-11-25T21:00:51+00:00

<!-- SC_OFF --><div class="md"><p>Planning to run about 30-40 docker containers, from *arr to Jellyfin, Nextcloud, Subgen, Home Assistant and some others. Should support HW transcoding (Intel chip?).</p> <p>Which ones would you recommend? Budget up to €500 ish. The bigger the Black Friday deal the better :-)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rbb1029"> /u/rbb1029 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gztrd5/what_minipc_for_selfhosting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gztrd5/what_minipc_for_selfhosting/">[comments]</a></span>

## Can't get authelia to work
 - [https://www.reddit.com/r/selfhosted/comments/1gztf0i/cant_get_authelia_to_work](https://www.reddit.com/r/selfhosted/comments/1gztf0i/cant_get_authelia_to_work)
 - RSS feed: $source
 - date published: 2024-11-25T20:47:26+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gztf0i/cant_get_authelia_to_work/"> <img src="https://b.thumbs.redditmedia.com/SX6NaQngeCsFPJGQ7hiKiaYSFOsSgu1G_b2Vu3AtY8I.jpg" alt="Can't get authelia to work" title="Can't get authelia to work" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I&#39;m new to traefik and authelia. I managed to configure reverse proxy via traefik for some services, guacamole for external access, any many other services routed internally using local dns added in pihole. </p> <p>I wanted to configure two factor authentication to guacamole using authelia. Yes I know that I can configure MFA in guacamole itself, it is done and it works fine - I just want to test authelia for future purposes, If I will need another auth layer for app that doesn&#39;t support MFA natevily. </p> <p>So I followed few YT tutorials and github repos and managed to create these configs (all secrets are replaced, all IPs and FQDNs are not real

## Need help resetting filestash admin password
 - [https://www.reddit.com/r/selfhosted/comments/1gztepp/need_help_resetting_filestash_admin_password](https://www.reddit.com/r/selfhosted/comments/1gztepp/need_help_resetting_filestash_admin_password)
 - RSS feed: $source
 - date published: 2024-11-25T20:47:06+00:00

<!-- SC_OFF --><div class="md"><p>I have filestash installed with Docker and running on linux ubuntu server and I&#39;ve initially setted up a wrong admin instance password and couldn&#39;t find any documentation to reset it.<br/> I&#39;m pretty new to Docker but i&#39;ve tried to uninstall the image and reinstalling it nothing changes. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fluffy-Capital-1576"> /u/Fluffy-Capital-1576 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gztepp/need_help_resetting_filestash_admin_password/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gztepp/need_help_resetting_filestash_admin_password/">[comments]</a></span>

## Guidance on converting personal project over to a self-hosted application (Shared wish lists)
 - [https://www.reddit.com/r/selfhosted/comments/1gztasa/guidance_on_converting_personal_project_over_to_a](https://www.reddit.com/r/selfhosted/comments/1gztasa/guidance_on_converting_personal_project_over_to_a)
 - RSS feed: $source
 - date published: 2024-11-25T20:42:41+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gztasa/guidance_on_converting_personal_project_over_to_a/"> <img src="https://a.thumbs.redditmedia.com/JQeMgC7UraimT8NzU4QAO1Z8a67GEJC20UAYw41q2q0.jpg" alt="Guidance on converting personal project over to a self-hosted application (Shared wish lists)" title="Guidance on converting personal project over to a self-hosted application (Shared wish lists)" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><strong>TLDR: Does anyone have any recommended resources / model projects I should look at if I want to convert an existing NextJS + Supabase Postgres web app over to something self-contained / self-hostable?</strong></p> <p>A while back, I had some time on my hands so I decided to whip together a site that my extended family could use to edit and share wish lists (e.g. birthday, holidays, etc) with each other. It started simple and it has slowly grown to include things like URL scraping, viewing and editing permis

## Self-hostable Auth solution for AI agents: connect AI apps with external SaaS tools like HubSpot, Zendesk, and Gmail—in just minutes.
 - [https://www.reddit.com/r/selfhosted/comments/1gzsxsd/selfhostable_auth_solution_for_ai_agents_connect](https://www.reddit.com/r/selfhosted/comments/1gzsxsd/selfhostable_auth_solution_for_ai_agents_connect)
 - RSS feed: $source
 - date published: 2024-11-25T20:28:10+00:00

<!-- SC_OFF --><div class="md"><p>I have been building AI apps for a while, and the only time I struggled was when it involved managing auth flows for external apps like HubSpot, MS Suite, Google apps, etc. Handling multiple auth mechanisms for different apps in my AI workflows was always a pain.</p> <p>Also, we felt that traditional IPaaS solutions weren’t good enough for agentic use cases as you need another layer for tool calling. Optimizing APIs for function calling for so many apps was a nightmare. Many developers we talked to shared similar feelings while building AI workflows.</p> <p>So, we created AgentAuth, a complete auth solution optimized for AI use cases. It handles complex authentication mechanisms like OAuth, API Key, Basic, etc, so you can integrate as many apps as possible.</p> <p>You can connect multiple services like Gmail, Zendesk, and Slack to your AI agents in a few lines of code. AgentAuth will handle the authorization flows on your user&#39;s behalf. If you wo

## How do these illegal streaming sites work? I don't understand
 - [https://www.reddit.com/r/selfhosted/comments/1gzs9p1/how_do_these_illegal_streaming_sites_work_i_dont](https://www.reddit.com/r/selfhosted/comments/1gzs9p1/how_do_these_illegal_streaming_sites_work_i_dont)
 - RSS feed: $source
 - date published: 2024-11-25T20:01:25+00:00

<!-- SC_OFF --><div class="md"><p>I mean, I host my own media through Jellyfin so I understand the basics, but these sites must be streaming huge amounts of content to thousands (millions?) of users. Do they rent VPS? Why don&#39;t those VPS then take them down? If the VPS service is in a dodgy country, why don&#39;t our ISPs just block those IPs? If they keep changing IP, ok fine, but how do they afford to pay for this traffic? Ads? I don&#39;t ever see ads (please tell me if they exist, I wouldn&#39;t know due to adblockers) but even if they do exist, why are companies okay with their adverts appearing on unlicensed streams? </p> <p>Furthermore, where are these people getting the actual sites? Each streaming site is different, and they pretty much all look presentable and intuitive. Do they have their own web designers? If not, where are they downloading these frameworks? I (like most of you) am an infrastructure guy, and I don&#39;t understand web design, so sorry if I&#39;m being

## Service for comparing running container versions against latest image version?
 - [https://www.reddit.com/r/selfhosted/comments/1gzs3di/service_for_comparing_running_container_versions](https://www.reddit.com/r/selfhosted/comments/1gzs3di/service_for_comparing_running_container_versions)
 - RSS feed: $source
 - date published: 2024-11-25T19:54:33+00:00

<!-- SC_OFF --><div class="md"><p>I recall watching a YouTube video about a year ago, where the host was talking about a service that tracked container versions and alerted you if there was a new version available. It was a SaaS tool that you pointed at your git repo containing your Docker compose files, and it captured the version number of the image you&#39;re pulling and compared against the most recent version of the source image, and sent you an email whenever new images were available. </p> <p>I can&#39;t for the life of me find that video or remember what the service was called. Does anyone happen to know?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CincyTriGuy"> /u/CincyTriGuy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzs3di/service_for_comparing_running_container_versions/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzs3di/service_for_comparing_running_container

## Check my WireGuard installer script with port forwarding support. (Also probably compatible with most VPS types.)
 - [https://www.reddit.com/r/selfhosted/comments/1gzs3d1/check_my_wireguard_installer_script_with_port](https://www.reddit.com/r/selfhosted/comments/1gzs3d1/check_my_wireguard_installer_script_with_port)
 - RSS feed: $source
 - date published: 2024-11-25T19:54:32+00:00

<!-- SC_OFF --><div class="md"><p>Hello selfhost subreddit, I am the developer of this WG installer project:</p> <p><a href="https://github.com/xiahualiu/wg_gaming_installer">https://github.com/xiahualiu/wg_gaming_installer</a></p> <p>Usage is pretty straight forward. Install WG on a server with public IP and it lets you create peers with selected port(s) forwarded to the server IP. You don&#39;t need to have nftables/iptables knowledge to use it.</p> <p>I think it may be helpful for those who want to bypass NAT or firewall restrictions on the local network. You can also use it to host public Minecraft servers from LAN, host video streaming service from LAN, etc.</p> <p>Run it, choose which ports you want to expose, then get the peer conf and use it on your local machine WG client. That&#39;s all you need!</p> <p>Leave a star if you like it! If you have any questions (like it doesn&#39;t work), just open an issue ticket there.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href

## Should I keep my server in a cupboard underneath the boiler or in the attic (UK)?
 - [https://www.reddit.com/r/selfhosted/comments/1gzqvjm/should_i_keep_my_server_in_a_cupboard_underneath](https://www.reddit.com/r/selfhosted/comments/1gzqvjm/should_i_keep_my_server_in_a_cupboard_underneath)
 - RSS feed: $source
 - date published: 2024-11-25T19:05:30+00:00

<!-- SC_OFF --><div class="md"><p>For a few baby related reasons, I’m having to move my current home server. The two options that I can go due to power, space and ethernet connectivity are either under the boiler, but I’m slightly concerned about the risk of water or heat, or in the attic where we have plenty of space, but worried about extreme temperatures here in the UK in either summer or winter.</p> <p>My server is basically a standard desktop ATX run about 20 services.</p> <p>Any advice?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tcoysh"> /u/tcoysh </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzqvjm/should_i_keep_my_server_in_a_cupboard_underneath/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzqvjm/should_i_keep_my_server_in_a_cupboard_underneath/">[comments]</a></span>

## Mini server as a remote backup server?
 - [https://www.reddit.com/r/selfhosted/comments/1gzq723/mini_server_as_a_remote_backup_server](https://www.reddit.com/r/selfhosted/comments/1gzq723/mini_server_as_a_remote_backup_server)
 - RSS feed: $source
 - date published: 2024-11-25T18:38:12+00:00

<!-- SC_OFF --><div class="md"><p>3-2-1, so I got my local backup server, and I wanna put another one at my parents&#39;.</p> <p>I wanna get something small, something that can fit a single hard drive or even a mini PC with 1-2 ssds(?)</p> <p>I&#39;ll run truenas scale, and probably attach a PIKVM with it so I won&#39;t need to go over for maintenance.</p> <p>It also needs to be low power since I don&#39;t wanna make my parents pay for it&#39;s electricity...</p> <p>Any suggestions? It really doesn&#39;t need to be fancy.</p> <p>Maybe this? <a href="https://cwwk.net/products/new-12th-gen-firewall-mini-pc-intel-i3-n305-n100-soft-router-2x10g-sfp-2xi226-v-2-5g-nvme-2xhd-ddr5-minipc-nas-server">https://cwwk.net/products/new-12th-gen-firewall-mini-pc-intel-i3-n305-n100-soft-router-2x10g-sfp-2xi226-v-2-5g-nvme-2xhd-ddr5-minipc-nas-server</a></p> <p>I have 2 of those for proxmox/opnsense and they&#39;re great, but idk if there&#39;s a slot for another SSD so maybe something else will be mo

## Self hosted smart music player
 - [https://www.reddit.com/r/selfhosted/comments/1gzpz5w/self_hosted_smart_music_player](https://www.reddit.com/r/selfhosted/comments/1gzpz5w/self_hosted_smart_music_player)
 - RSS feed: $source
 - date published: 2024-11-25T18:29:25+00:00

<!-- SC_OFF --><div class="md"><p>First, I realize there&#39;s a page often linked that has a summary of self hosted music options however I wasn&#39;t able to find what I was looking for, hence this post. </p> <p>I want to host a player that works like Pandora, that means it can play my collection on moods or genre (but beyond id3 tags).</p> <p>Is there anything like this that exists already? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/electric_machinery"> /u/electric_machinery </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzpz5w/self_hosted_smart_music_player/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzpz5w/self_hosted_smart_music_player/">[comments]</a></span>

## Enclosed just hit 700 stars on GitHub!
 - [https://www.reddit.com/r/selfhosted/comments/1gzpo3x/enclosed_just_hit_700_stars_on_github](https://www.reddit.com/r/selfhosted/comments/1gzpo3x/enclosed_just_hit_700_stars_on_github)
 - RSS feed: $source
 - date published: 2024-11-25T18:17:34+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone!</p> <p>Just want to thank you all for the amazing support Enclosed has received. We just hit 700 stars on GitHub! </p> <p>The feedbacks I received when I first posted the project here was invaluable, and motivated me to keep working on this side project. I&#39;m really grateful for the contributions, suggestions, and kind words from the community, it feels great to make something that people find useful and enjoy using!</p> <p>For those who don&#39;t know, Enclosed is a minimalistic web app designed for sending private and secure notes. All notes are end-to-end encrypted, with a zero knowledge storage layer and many configurable security options (password, expiration time, self-destruction after reading). It&#39;s easily self-hostable and has a CLI for creating notes from the terminal</p> <p>More information: - Live Instance: <a href="https://enclosed.cc/">enclosed.cc</a> - GitHub: <a href="https://github.com/CorentinTh/enclosed">github

## Self Hosted Image and File Shareing with NAS as Storage
 - [https://www.reddit.com/r/selfhosted/comments/1gzpd6q/self_hosted_image_and_file_shareing_with_nas_as](https://www.reddit.com/r/selfhosted/comments/1gzpd6q/self_hosted_image_and_file_shareing_with_nas_as)
 - RSS feed: $source
 - date published: 2024-11-25T18:05:08+00:00

<!-- SC_OFF --><div class="md"><p>I have been thinking about an application I can deploy as a Docker server on my network. It would have a simple and clean web UI to browse the files on my NAS. In addition to that, I would like it to have an option to share the files via a link like OneDrive and Co. This could be done by exposing the service to the internet via the firewall, but this might seem insecure or some might not be able to do so.</p> <p>So I thought I could build a &quot;cloud&quot; service that would act as a proxy but not store any files. In detail, the private instance would connect to the cloud version, and this would then enable sharing with anyone via a link.</p> <p>No data would be stored in the cloud! It would be more of a peer-to-peer thing and no ports would need to be opened as the local instance deployed to docker would Initiative the connection to the public Service.</p> <p>Would this be worth building? Do you guys have a need for something like this, or is ther

## I want to expose some services for collaborating with others. Need help to build on strong foundations.
 - [https://www.reddit.com/r/selfhosted/comments/1gzoheb/i_want_to_expose_some_services_for_collaborating](https://www.reddit.com/r/selfhosted/comments/1gzoheb/i_want_to_expose_some_services_for_collaborating)
 - RSS feed: $source
 - date published: 2024-11-25T17:31:15+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gzoheb/i_want_to_expose_some_services_for_collaborating/"> <img src="https://b.thumbs.redditmedia.com/TOrgYw6T5hTPV1TnHor2Tt0F5gOiTUj086UJRrsN4cA.jpg" alt="I want to expose some services for collaborating with others. Need help to build on strong foundations." title="I want to expose some services for collaborating with others. Need help to build on strong foundations." /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/z7lh46h9233e1.png?width=2446&amp;format=png&amp;auto=webp&amp;s=2916aeea1887604e68aee5a9fb6c621c1244307b">https://preview.redd.it/z7lh46h9233e1.png?width=2446&amp;format=png&amp;auto=webp&amp;s=2916aeea1887604e68aee5a9fb6c621c1244307b</a></p> <p>I have a client who needs some PDF guides made. I&#39;ve used Scribus for the first 2 guides but the process is tedious and the content I&#39;m receiving is a mess of .doc, .txt and .pdf files.</p> <p>I&#39;ve experimented

## Network and access..help
 - [https://www.reddit.com/r/selfhosted/comments/1gznyek/network_and_accesshelp](https://www.reddit.com/r/selfhosted/comments/1gznyek/network_and_accesshelp)
 - RSS feed: $source
 - date published: 2024-11-25T17:10:55+00:00

<!-- SC_OFF --><div class="md"><p>Hi long time listener first time caller... I used to have a little nuc server, couple of USB drives worked great...then it died. </p> <p>Now I decided to build a proper server but I&#39;m lost on some of the Networking and access. </p> <p>I have a single host with 4 VMs each server handles specific needs -vm1 *arr stack, vm2 Plex and books, vm3 cookbook,notes etc, vm4 manages everything. On my 2nd host My truenas scale handles my 100tb storage and shares to my network. </p> <p>My thought was to do it like this : Cloudflare tunnel in on vm1 with VPN out. Cloudflare tunnel in on vm2. Vm3/4 connect to vm2 and share the same inbound tunnel. But not sure on sharing outbound as each VM has services that I will want acess remotely. I own a domain hosted at cloudflare but I&#39;m not sure how to set all this up securely for my family. </p> <p>I just learned you can&#39;t stream Plex thru a cloudflare tunnel so I&#39;m kinda screwed I think. I am not sure how

## What's a self hostable app that's not got a proprietary equivalent
 - [https://www.reddit.com/r/selfhosted/comments/1gznjak/whats_a_self_hostable_app_thats_not_got_a](https://www.reddit.com/r/selfhosted/comments/1gznjak/whats_a_self_hostable_app_thats_not_got_a)
 - RSS feed: $source
 - date published: 2024-11-25T16:54:54+00:00

<!-- SC_OFF --><div class="md"><p>Most self hosted apps are developed as alternatives to cloud hosted apps (for example, uptime kuma was developed as an alternative to uptime robot. What&#39;s a self hosted app that has no cloud hosted equivalent?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/EnoughConcentrate897"> /u/EnoughConcentrate897 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gznjak/whats_a_self_hostable_app_thats_not_got_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gznjak/whats_a_self_hostable_app_thats_not_got_a/">[comments]</a></span>

## CANNOT log into Authentik
 - [https://www.reddit.com/r/selfhosted/comments/1gzn6r9/cannot_log_into_authentik](https://www.reddit.com/r/selfhosted/comments/1gzn6r9/cannot_log_into_authentik)
 - RSS feed: $source
 - date published: 2024-11-25T16:41:09+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to spin up Authentik for the first time with docker compose, which I&#39;m fairly new to. I can get it up and running, but I can&#39;t login the the web ui. When typing in the default user akadmin, I am prompted to put in a password rather than creating one. I&#39;ve tried &quot;authentik&quot; as the password and leaving it blank. I&#39;ve tried entering the shell of the container and changing the user details that way, but any authentik command I try is unavailable! I&#39;ve tried changing which image I&#39;m using for the server, from using specific release tags to just latest. I&#39;ve tried completely removing the container, all created volumes and databases, everything, and rebuilding. Still nothing. Ive tried doing that same thing but on a different host on my network, still nothing. I&#39;ve asked AI and searched through forums and the github issues for the official repo. Still, NOTHING WORKS.</p> <p>My only lead is an issue I&

## App for streaming all family photos and videos
 - [https://www.reddit.com/r/selfhosted/comments/1gzn0et/app_for_streaming_all_family_photos_and_videos](https://www.reddit.com/r/selfhosted/comments/1gzn0et/app_for_streaming_all_family_photos_and_videos)
 - RSS feed: $source
 - date published: 2024-11-25T16:33:57+00:00

<!-- SC_OFF --><div class="md"><p>I am in the process of digitizing all of my family&#39;s old photos and videos. I&#39;d like to put them on a server with a media delivery service that will cater well to both photo and video with ease of usability for my grandparents. I want the photos and videos to be accessible from our phones, computers, and smart TVs. I&#39;m thinking something that&#39;s kinda a cross between Immich and Jellyfin. I realize, at the end of the day, to meet my specific needs and wants i may have to build my own app, but is there anything like this out there?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/-ThatGingerKid-"> /u/-ThatGingerKid- </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzn0et/app_for_streaming_all_family_photos_and_videos/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzn0et/app_for_streaming_all_family_photos_and_videos/">[comments]</a></span>

## How big websites servers are designed for high availability and scalability?
 - [https://www.reddit.com/r/selfhosted/comments/1gzmv68/how_big_websites_servers_are_designed_for_high](https://www.reddit.com/r/selfhosted/comments/1gzmv68/how_big_websites_servers_are_designed_for_high)
 - RSS feed: $source
 - date published: 2024-11-25T16:28:10+00:00

<!-- SC_OFF --><div class="md"><p>Say you start a website from home and it starts taking off ! How would you expand a website for instance across multiple nodes ? For instance say a website like eBay. How do they keep on expanding and adding servers ? What&#39;s the architecture behind it ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/amiroosh"> /u/amiroosh </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzmv68/how_big_websites_servers_are_designed_for_high/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzmv68/how_big_websites_servers_are_designed_for_high/">[comments]</a></span>

## How to configure a Wireguard tunnel to use my internal DNS server?
 - [https://www.reddit.com/r/selfhosted/comments/1gzme78/how_to_configure_a_wireguard_tunnel_to_use_my](https://www.reddit.com/r/selfhosted/comments/1gzme78/how_to_configure_a_wireguard_tunnel_to_use_my)
 - RSS feed: $source
 - date published: 2024-11-25T16:09:19+00:00

<!-- SC_OFF --><div class="md"><p>I have a Unifi Dream Machine Pro which I&#39;ve just recently configured Wireguard on, and installed the client on my Mac. </p> <p>My homelab&#39;s domain name is a public domain that&#39;s registered on CloudFlare with some services published. I also have an internal DNS server which hosts the same domain name and additional services published, so when I&#39;m at home I resolve to internal addresses and when I&#39;m away I resolve via CloudFlare.</p> <p>My Wireguard tunnel is using public DNS. Can I configure it so my specific domain resolves over the tunnel to my internal DNS server, and all other domains resolve to public DNS servers?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CincyTriGuy"> /u/CincyTriGuy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzme78/how_to_configure_a_wireguard_tunnel_to_use_my/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/

## OMV for Backup Server?
 - [https://www.reddit.com/r/selfhosted/comments/1gzme13/omv_for_backup_server](https://www.reddit.com/r/selfhosted/comments/1gzme13/omv_for_backup_server)
 - RSS feed: $source
 - date published: 2024-11-25T16:09:08+00:00

<!-- SC_OFF --><div class="md"><p>I have a Terramaster F2-223 on the way that I plan to use just for storing backups from various places. </p> <p>I&#39;m not going to use the including OS, but what should I use? Unraid and Truenas seem overkill for this use case. Is OpenMediaVault generally recommended in the community? I&#39;ve never even looked at it for more than a minute. </p> <p>SFTP and Webdav are what I need more than anything. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/xt0r"> /u/xt0r </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzme13/omv_for_backup_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzme13/omv_for_backup_server/">[comments]</a></span>

## Selfhosting mangas and ebooks
 - [https://www.reddit.com/r/selfhosted/comments/1gzlxjs/selfhosting_mangas_and_ebooks](https://www.reddit.com/r/selfhosted/comments/1gzlxjs/selfhosting_mangas_and_ebooks)
 - RSS feed: $source
 - date published: 2024-11-25T15:50:10+00:00

<!-- SC_OFF --><div class="md"><p>Greetings all,</p> <p>I have been running my own debian server for a while now (hosting immich, emby, manyfold and various others) and I would like to expand into ebooks / manga / comics.</p> <p>I saw a bunch of different options, but I am a bit confused which one would suit better my needs.</p> <p>I would like to host all my books on a NAS, with a dedicated shared folder. And hopefully being able to access them through an android app on my phone (and web browser on my PC).</p> <p>What would be your recommandations ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Herlock"> /u/Herlock </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzlxjs/selfhosting_mangas_and_ebooks/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzlxjs/selfhosting_mangas_and_ebooks/">[comments]</a></span>

## What's better Akaunting, Frappe Books, or GnuCash?
 - [https://www.reddit.com/r/selfhosted/comments/1gzlrpg/whats_better_akaunting_frappe_books_or_gnucash](https://www.reddit.com/r/selfhosted/comments/1gzlrpg/whats_better_akaunting_frappe_books_or_gnucash)
 - RSS feed: $source
 - date published: 2024-11-25T15:43:07+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m a starting a SaaS business on my own and I just need to be able to: - import Stripe transactions, - have them automatically categorized as income, accounts receivable, expenses - match bank transactions with Stripe - be able to generate Income Statements at the end of the year which I can use to file taxes</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/daninus14"> /u/daninus14 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzlrpg/whats_better_akaunting_frappe_books_or_gnucash/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzlrpg/whats_better_akaunting_frappe_books_or_gnucash/">[comments]</a></span>

## What's your process for gathering family photos from several devices and messaging services?
 - [https://www.reddit.com/r/selfhosted/comments/1gzlf3e/whats_your_process_for_gathering_family_photos](https://www.reddit.com/r/selfhosted/comments/1gzlf3e/whats_your_process_for_gathering_family_photos)
 - RSS feed: $source
 - date published: 2024-11-25T15:28:28+00:00

<!-- SC_OFF --><div class="md"><p>Like most people I&#39;m a few years behind on making a yearly physical family photo book. I&#39;ve noticed that our kids really like leafing through the ones that I have made, so I want to put in place a less cumbersome process for gathering all relevant photos and filtering out the 100 best ones.</p> <p>I&#39;m currently using iOS and Apple Photos (no iCloud storage, just local backups using TimeMachine).</p> <p>Two difficulties:<br/> - getting pictures from my wife&#39;s phone (also iOS, Apple Photos)<br/> - gathering pictures sent via Whatsapp / iOS Messages</p> <p>Ideally, I&#39;d like to have an easy or even automatic system in place where I can easily pull in photos that my wife took as well as photos from mine and her Whatsapp / Messages for the last 365 days. Perhaps put them in a shared photo database after weeding out the many irrelevant images (stupid stuff that should just auto delete itself like pictures that you take at a store).</p> <

## Self hosting Down sides
 - [https://www.reddit.com/r/selfhosted/comments/1gzlb3s/self_hosting_down_sides](https://www.reddit.com/r/selfhosted/comments/1gzlb3s/self_hosting_down_sides)
 - RSS feed: $source
 - date published: 2024-11-25T15:23:46+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m reading through the posts here and trying to learn myself to move in this direction in the distant future.</p> <p>But I&#39;m seeing posts that, to me, read like creating a home lab and self hosting opens up the door for cyber attacks and creates vulnerabilities that otherwise would be of no concern.</p> <p>I feel like the more I look into this the more it seems like I need multiple cyber certificates to set one up, from coding to hardware to front end/back end support and some electrical engineering. </p> <p>As a regular guy just looking to get into all this, what are some of the down sides to self hosting? </p> <p>Or maybe another way to frame it, what are some things/issues/concerns that aren&#39;t inherently obvious to someone with no background in any of this who wants to join the club? </p> <p>TIA</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Atmosphere_Eater"> /u/Atmosphere_Eater </a> <br/> <spa

## Truenas or Debian with a ZFS Pool? Help Me Decide
 - [https://www.reddit.com/r/selfhosted/comments/1gzkrw1/truenas_or_debian_with_a_zfs_pool_help_me_decide](https://www.reddit.com/r/selfhosted/comments/1gzkrw1/truenas_or_debian_with_a_zfs_pool_help_me_decide)
 - RSS feed: $source
 - date published: 2024-11-25T15:00:45+00:00

<!-- SC_OFF --><div class="md"><p>Currently setting up my home server and I&#39;ve come to a fork in the road. I had originally thought I would run Truenas and then run docker containers on top of it. Amongst many other things I&#39;d like to run Jellyfin with GPU passthrough and several apps behind Gluetun. The thought was that Truenas would provide a lot of functionality for free and then I&#39;d build on top of that. Lately though I&#39;m second guessing that and thinking of just running Debian and setting up everything by hand. Are there things I might be missing/failing to consider as to pros and cons between the two options? What would the people of reddit do?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nsap"> /u/nsap </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzkrw1/truenas_or_debian_with_a_zfs_pool_help_me_decide/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzkrw1

## Strange behavior when accessing sites in homelab via NPM (Nginx Proxy Manager)
 - [https://www.reddit.com/r/selfhosted/comments/1gzjq9k/strange_behavior_when_accessing_sites_in_homelab](https://www.reddit.com/r/selfhosted/comments/1gzjq9k/strange_behavior_when_accessing_sites_in_homelab)
 - RSS feed: $source
 - date published: 2024-11-25T14:13:21+00:00

<!-- SC_OFF --><div class="md"><p>Hello knowledgeable homelab crowd! I encounter some strange behavior in my homelab... I hope you can point me in the right direction where to look.</p> <p>I run most of my services off Docker on my Unraid machine using the host IP address plus a port. In order to have readable URLs I run a simple NPM (Nginx Proxy Manager) container alongside.</p> <p>However, there is one thing that is strange whcih happens with the Unraid Dashboard and the Zigbee2MQTT dashboard. When accessing via IP:port all is fine. But when accessing via host name set in NPM the page loads but misses details. For example, in the Unraid Dashboard the list of array devices is empty; in Z2M only the table headers are loaded but all the devices details are missing.</p> <p>I checked in different browsers on different devices, deleted all cookies and cache data, disbaled all extensions, and tried with and without using a certificate (http same result as https).</p> <p>Anyone got an idea

## Locked out of Proxmox Cluster
 - [https://www.reddit.com/r/selfhosted/comments/1gzjk4y/locked_out_of_proxmox_cluster](https://www.reddit.com/r/selfhosted/comments/1gzjk4y/locked_out_of_proxmox_cluster)
 - RSS feed: $source
 - date published: 2024-11-25T14:05:21+00:00

<!-- SC_OFF --><div class="md"><p>I have 2 nodes that I have combined into a Proxmox cluster. I set up username and password on both before I connected them together. Since I partially route Proxmox out to the internet, I then activated 2FA on my main node.</p> <p>Now the main node is switched off for maintenance and I can&#39;t log in anymore because the backup node also needs 2FA to log in but not the one I set up on the main node. Backup codes do not work either. How do I fix this and how do I avoid this in the future?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Penner4242"> /u/Penner4242 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzjk4y/locked_out_of_proxmox_cluster/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzjk4y/locked_out_of_proxmox_cluster/">[comments]</a></span>

## The Twingate, Tailscale and Netbird Question
 - [https://www.reddit.com/r/selfhosted/comments/1gzj4fo/the_twingate_tailscale_and_netbird_question](https://www.reddit.com/r/selfhosted/comments/1gzj4fo/the_twingate_tailscale_and_netbird_question)
 - RSS feed: $source
 - date published: 2024-11-25T13:44:13+00:00

<!-- SC_OFF --><div class="md"><p>Hello together, </p> <p>i know i&#39;m a bit late, but i was happy all the time with wireguard. I have the Plugin in my OPNsense Router, create tunnel + peer, send it on my client and it works fine. </p> <p>With that - i never looked out to other solutions :D</p> <p>But now i found the 3 Solutions Twingate, Tailscale and Netbird. </p> <p>All 3 are Free but i&#39;m an IT Guy and want to play in my homelab - also i think about a solution to add all my customers to one &quot;System&quot; and host it by mself (netbird). </p> <p>I know netbird is fully selfhosted - i just need a VPN and can&#39;t host the Coordinator in my own network because i need the ports 80 and 443 for my reverse proxy. Also its a bit overwhelming with his own Identity provider and all that stuff.. can i connect this somehow with my local authentik server? </p> <p>Same for Tailscale - here i can use Headscale - but its a 3rd party connector. </p> <p>Twingate is a complete closed solu

## Nginx server receives malicious requests. Should I be worried?
 - [https://www.reddit.com/r/selfhosted/comments/1gzj0r9/nginx_server_receives_malicious_requests_should_i](https://www.reddit.com/r/selfhosted/comments/1gzj0r9/nginx_server_receives_malicious_requests_should_i)
 - RSS feed: $source
 - date published: 2024-11-25T13:39:10+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gzj0r9/nginx_server_receives_malicious_requests_should_i/"> <img src="https://a.thumbs.redditmedia.com/HNcnEdRbxCoGsLWeR2HasFqebj8wc7EyCPLLJX8sDk0.jpg" alt="Nginx server receives malicious requests. Should I be worried?" title="Nginx server receives malicious requests. Should I be worried?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I recently set up an nginx webserver.</p> <p>Now I discovered in the logs that there were many requests not related to my server. I suppose those are some sort of sniffing attempts.</p> <p><a href="https://preview.redd.it/xwgen1iow13e1.jpg?width=1920&amp;format=pjpg&amp;auto=webp&amp;s=4fbaf876e86703443beffb73a28bdc3fa32e2b6e">nginx log</a></p> <p>Should I be worried about this or is it common? Should I take any measures against it and if yes, which ones would be appropriate?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Meister_der_Ma

## Consume downloaded course in platform LMS style
 - [https://www.reddit.com/r/selfhosted/comments/1gzigzr/consume_downloaded_course_in_platform_lms_style](https://www.reddit.com/r/selfhosted/comments/1gzigzr/consume_downloaded_course_in_platform_lms_style)
 - RSS feed: $source
 - date published: 2024-11-25T13:11:21+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys, I&#39;m new here!</p> <p>I have some courses downloaded and organized on my computer and I would like to watch these courses through some self-hosted platform (localhost) on my own computer in the LMS style. I will not watch the course remotely. It will only be on my own computer.</p> <p>Doing some research I saw that there are some solutions where it is possible to create courses and watch them in the way I mentioned (wordpress plugins, moodle and some projects I saw on GitHub).</p> <p>The problem is that these projects and solutions I found are very time-consuming because I need to configure the course by mapping the videos one by one, creating the modules and classes one by one.</p> <p>I would like, if there is one, a GitHub project or a solution where I just map the folder directory where the course is stored on my computer and it already structures the course on the platform (Jellyfin and Emby style). I saw that these last two are more 

## Handy README guide for newer projects / developers
 - [https://www.reddit.com/r/selfhosted/comments/1gzigiz/handy_readme_guide_for_newer_projects_developers](https://www.reddit.com/r/selfhosted/comments/1gzigiz/handy_readme_guide_for_newer_projects_developers)
 - RSS feed: $source
 - date published: 2024-11-25T13:10:39+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gzigiz/handy_readme_guide_for_newer_projects_developers/"> <img src="https://external-preview.redd.it/bNEObvG_oAgqT83iZGoQR_vadb3Py6xbVh_Xy6vwEdM.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=5c64fed39b903cd1fa409d9d3eba74edd912de28" alt="Handy README guide for newer projects / developers" title="Handy README guide for newer projects / developers" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tehsuck"> /u/tehsuck </a> <br/> <span><a href="https://www.makeareadme.com">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzigiz/handy_readme_guide_for_newer_projects_developers/">[comments]</a></span> </td></tr></table>

## Deploying to remote servers with Docker ?
 - [https://www.reddit.com/r/selfhosted/comments/1gzhnr8/deploying_to_remote_servers_with_docker](https://www.reddit.com/r/selfhosted/comments/1gzhnr8/deploying_to_remote_servers_with_docker)
 - RSS feed: $source
 - date published: 2024-11-25T12:26:04+00:00

<!-- SC_OFF --><div class="md"><p>Can anyone tell me, at a high level, what the workflow is for managing and deploying containerised apps to remote VPS from my laptop ?</p> <p>Can i do this from docker desktop, once docker is installed on the remote servers ?</p> <p>is this a good way to fly ?</p> <p>i&#39;ve been playing with portainer, but that runs on its own server anyway.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/softwarebuyer2015"> /u/softwarebuyer2015 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzhnr8/deploying_to_remote_servers_with_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzhnr8/deploying_to_remote_servers_with_docker/">[comments]</a></span>

## Expand VPS storage with homelab storage.
 - [https://www.reddit.com/r/selfhosted/comments/1gzgw48/expand_vps_storage_with_homelab_storage](https://www.reddit.com/r/selfhosted/comments/1gzgw48/expand_vps_storage_with_homelab_storage)
 - RSS feed: $source
 - date published: 2024-11-25T11:39:34+00:00

<!-- SC_OFF --><div class="md"><p>I have a homelab as well as a small VPS and I was wondering if realistically I could use my homelab&#39;s hard drives to extend my VPS&#39;s storage by connecting my VPS to my home network via wireguard and then just using a NFS like SMB?</p> <p>I&#39;ve got two use cases in mind:</p> <ol> <li><p>Hosting a small website on the VPS and hosting the DB on my home server.</p></li> <li><p>Hosting jellyfin on my VPS and storing the media files on my home server.</p></li> </ol> <p>I have a feeling that for the DB it will work find but not for the media files, my upload speed is not very fast at around 40Mbps.</p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/smokingRooster_"> /u/smokingRooster_ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzgw48/expand_vps_storage_with_homelab_storage/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzgw48/exp

## VPS providers that accept visa debit cards?
 - [https://www.reddit.com/r/selfhosted/comments/1gzg9cl/vps_providers_that_accept_visa_debit_cards](https://www.reddit.com/r/selfhosted/comments/1gzg9cl/vps_providers_that_accept_visa_debit_cards)
 - RSS feed: $source
 - date published: 2024-11-25T10:57:01+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;m from a third world country(Bangladesh) and I&#39;ve been wanting to buy a VPS hosting with my visa debit card, I bought my domain from cloudflare with the same card but my debit card isn&#39;t being accepted in interserver, linode, digitalocean. interserver and linode blocked my account after adding the card. Any solution? or suggest some providers that I can buy from. Thank you.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/theforbiddenkingdom"> /u/theforbiddenkingdom </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzg9cl/vps_providers_that_accept_visa_debit_cards/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzg9cl/vps_providers_that_accept_visa_debit_cards/">[comments]</a></span>

## Introducing Chevereto v4.2: now with user-generated tags
 - [https://www.reddit.com/r/selfhosted/comments/1gzg4d8/introducing_chevereto_v42_now_with_usergenerated](https://www.reddit.com/r/selfhosted/comments/1gzg4d8/introducing_chevereto_v42_now_with_usergenerated)
 - RSS feed: $source
 - date published: 2024-11-25T10:47:04+00:00

<!-- SC_OFF --><div class="md"><p>Hello, self-hosters. I&#39;m Rodolfo Berrios, an indie developer from Chile.</p> <p>Since 2007, I&#39;ve been pouring my heart into creating Chevereto, a media-sharing platform that allows anyone to build their own media-sharing website. Think of it as a self-hosted alternative to Imgur or Flickr, designed for massive online collections. Services like ImgBB and many others have grown on Chevereto&#39;s foundation.</p> <p>Chevereto is entirely self-funded. I handle development while my wife manages marketing. Together, as a small but passionate team, we strive to bring you something truly special.</p> <p>Today, I&#39;m thrilled to share our latest release: <strong>Chevereto v4.2</strong>. This update introduces <strong>user-generated tags</strong>, a powerful new way to classify and organize your media. We&#39;re also adding support for <strong>AVIF</strong>, improving storage handling, introducing more configurable limits, enhancing session managemen

## Create my own music jukebox
 - [https://www.reddit.com/r/selfhosted/comments/1gzg3hl/create_my_own_music_jukebox](https://www.reddit.com/r/selfhosted/comments/1gzg3hl/create_my_own_music_jukebox)
 - RSS feed: $source
 - date published: 2024-11-25T10:45:21+00:00

<!-- SC_OFF --><div class="md"><p>Hey,</p> <p>I decided to host my music files on my local network, but howwww boyyy I wasn&#39;t prepared for what was about to happen.</p> <p>here&#39;s the idea :</p> <p>I have an old laptop (Asus X543M) that I want to use as a server (because it had a 1To HDD, a (weak) battery for, like, an UPS function), on this server I would want to have all of my music files (MP3, Flac, AAC, ...) stored. The main goal is to have an app and/or webapp to act like a remote to choose which file/album/artist I want to play AND have the audio output on the laptop, where an USB audio DAC is connected, like a &quot;Jukebox&quot; function. If possible it would be great if the files could also be played on the remote device itself.</p> <p>I tried Jellyfin but it didn&#39;t had a &quot;Jukebox&quot; function, the only way to do this is to have a jellyfin app installed on the server (I tried, but I didn&#39;t achieve to install jellyfin media player or jellyamp on Kubuntu 

## How do you use KASM?
 - [https://www.reddit.com/r/selfhosted/comments/1gzfsnu/how_do_you_use_kasm](https://www.reddit.com/r/selfhosted/comments/1gzfsnu/how_do_you_use_kasm)
 - RSS feed: $source
 - date published: 2024-11-25T10:23:39+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve always thought KASM looked really cool but never got into using it.</p> <p>Is you use it, how do you take advantage of it?</p> <p>As far as I understand it, it is like a docker container in that nothing is saved. I assume you setup a template to what is installed.</p> <p>How do you handle things like password manager and network connections? If I wanted to use this as a workstation for example.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MidnightProgrammer"> /u/MidnightProgrammer </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzfsnu/how_do_you_use_kasm/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzfsnu/how_do_you_use_kasm/">[comments]</a></span>

## Alternative TeamViewer selfhosted?
 - [https://www.reddit.com/r/selfhosted/comments/1gzf826/alternative_teamviewer_selfhosted](https://www.reddit.com/r/selfhosted/comments/1gzf826/alternative_teamviewer_selfhosted)
 - RSS feed: $source
 - date published: 2024-11-25T09:41:59+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>is there some teamviewer alternative but selfhosted?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Elemis89"> /u/Elemis89 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzf826/alternative_teamviewer_selfhosted/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzf826/alternative_teamviewer_selfhosted/">[comments]</a></span>

## Install firewall like opnsense at home or use a proxy for apps?
 - [https://www.reddit.com/r/selfhosted/comments/1gzf5jh/install_firewall_like_opnsense_at_home_or_use_a](https://www.reddit.com/r/selfhosted/comments/1gzf5jh/install_firewall_like_opnsense_at_home_or_use_a)
 - RSS feed: $source
 - date published: 2024-11-25T09:36:34+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been coming back to this dilemma multiple times, as I started my selfhoting and degoogle journey for myself and my family, I figured it&#39;s inevitable some of the apps I must make it publicly accessible.</p> <p>For example I do not like the idea of having to connect to tailscale/vpn everytime I need to access some file or do some auto backup with nextcloud or immich.</p> <p>So I have 2 main way to make the app publicly accessible, port forward on my router and setup ddns for my apps, OR rent a cheap vps and use it as a proxy.</p> <p>Currently I&#39;m using a cheap VPS, I point my domain dns to the vps, then on my vps I use nginx proxy protocol to forward the packet to my local server via wireguard tunnel, which I have swag installed and terminate ssl. So there&#39;s no termination of ssl on the vps, less risk if the vps is compromised.</p> <p>Downside of this is, one more point of failure, one more vps to manage, bandwidth quota limit, mon

## Notifico – Open-Source notification server with Email & Slack support, written in Rust
 - [https://www.reddit.com/r/selfhosted/comments/1gzf2l0/notifico_opensource_notification_server_with](https://www.reddit.com/r/selfhosted/comments/1gzf2l0/notifico_opensource_notification_server_with)
 - RSS feed: $source
 - date published: 2024-11-25T09:30:16+00:00

<!-- SC_OFF --><div class="md"><p>I have built an open source notification server, that supports Email, SMS (SMPP), Slack, Telegram, WhatsApp Business. It is called Notifico.</p> <p>I have worked in a bunch of tech companies, and in each of them there was a half-baked, in-house built notification server for sending emails and other notifications. So, I&#39;ve collected the requirements, processed them and written the implementation in Rust!</p> <p>The idea is simple: You send <code>event_id</code> and <code>context</code> (JSON object), and it loads the template, renders it with variables from the context, sends it to the recipient.</p> <p>Features:</p> <ul> <li>No-code configuration. No knowledge of JS or other language is required.</li> <li>The templates can be edited without the need of backend developers.</li> <li>HA configuration with AMQP 1.0 support (e.g., RabbitMQ). Every component scales horizontally.</li> <li>Powerful templating language (it uses minijinja internally: <a hr

## Plan to create a new app on NAS-related software. What Features Do You Want in a New NAS Software?
 - [https://www.reddit.com/r/selfhosted/comments/1gzelhy/plan_to_create_a_new_app_on_nasrelated_software](https://www.reddit.com/r/selfhosted/comments/1gzelhy/plan_to_create_a_new_app_on_nasrelated_software)
 - RSS feed: $source
 - date published: 2024-11-25T08:53:57+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone! 👋 Our team is exploring the idea of developing a new NAS software, and we&#39;d love to hear your thoughts.<br/> What features or improvements are you looking for in NAS solutions today?</p> <ul> <li>Is there something your current setup lacks?</li> <li>Any frustrations with existing software?</li> <li>Features you wish were more user-friendly?</li> </ul> <p>We&#39;re open to all suggestions, whether for home use, data hoarding, or business setups. Let&#39;s create something that truly meets the community&#39;s needs!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mialululu"> /u/mialululu </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzelhy/plan_to_create_a_new_app_on_nasrelated_software/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzelhy/plan_to_create_a_new_app_on_nasrelated_software/">[comments]</a></span>

## Base M4 Mac Mini as NVR and Livestream server for 35 cameras
 - [https://www.reddit.com/r/selfhosted/comments/1gzegve/base_m4_mac_mini_as_nvr_and_livestream_server_for](https://www.reddit.com/r/selfhosted/comments/1gzegve/base_m4_mac_mini_as_nvr_and_livestream_server_for)
 - RSS feed: $source
 - date published: 2024-11-25T08:44:00+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m thinking about using a base M4 Mac Mini (10 core CPU, 16gb RAM, 256GB SSD, Gigabit ethernet) as an NVR and a live stream server for 35 Hikvision cameras. Each camera has a resolution of 2MP with H.265+ encoding. I&#39;m also planning to write custom software to live stream the camera feeds over the internet. I expect to have 20 simultaneous live stream clients (one feed per client) at a given time.</p> <p>The camera recordings will be saved to external SSDs connected via thunderbolt. I suppose there are NVR software that support this on Mac.</p> <p>Do you think the base M4 Mac Mini can handle this workload? Any issues I need to consider?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cephtahrioh"> /u/cephtahrioh </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzegve/base_m4_mac_mini_as_nvr_and_livestream_server_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r

## How do I use infinityfree with termux to host a shimmie2 imageboard?
 - [https://www.reddit.com/r/selfhosted/comments/1gze62f/how_do_i_use_infinityfree_with_termux_to_host_a](https://www.reddit.com/r/selfhosted/comments/1gze62f/how_do_i_use_infinityfree_with_termux_to_host_a)
 - RSS feed: $source
 - date published: 2024-11-25T08:21:31+00:00

<!-- SC_OFF --><div class="md"><p>I want to use something like cron to automate updating the site dynamicly and mirror it to the ftp server. Any help? Also some more info, I am on android and my only known solution is termux.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Marioplays18"> /u/Marioplays18 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gze62f/how_do_i_use_infinityfree_with_termux_to_host_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gze62f/how_do_i_use_infinityfree_with_termux_to_host_a/">[comments]</a></span>

## Some questions about my Authentik setup
 - [https://www.reddit.com/r/selfhosted/comments/1gzdva3/some_questions_about_my_authentik_setup](https://www.reddit.com/r/selfhosted/comments/1gzdva3/some_questions_about_my_authentik_setup)
 - RSS feed: $source
 - date published: 2024-11-25T07:59:38+00:00

<!-- SC_OFF --><div class="md"><p>Last couple of days I have been migrating my Authelia setup over to Authenik.</p> <p>So far I have it setup as so...</p> <p>Apps like Radarr/Sonarr have authentication in the app turned OFF and are setup as a proxy provider in Authentik. NPM forwards you to Authentik which upon successful login sends you straight in to Radarr. I believe this is the only method since the *arr apps dont support OIDC.</p> <p>Apps like Paperless and Tandoor I have (struggled) setup as full OIDC and I have linked my local login with the social accounts, I found documentation a bit spotty. Tandoor was a real pain, Paperless was slightly easier. Once things are ironed out I might do a full write up and post it here for future travellers.</p> <p>One thing I would like to know is how can I force Paperless and Tandoor authentication through Authentik?</p> <p>Currently if I go to <a href="http://paperless.mydomain.com">paperless.mydomain.com</a> I have the option of either loca

## Laptop + DAS for Jellyfin?
 - [https://www.reddit.com/r/selfhosted/comments/1gzc971/laptop_das_for_jellyfin](https://www.reddit.com/r/selfhosted/comments/1gzc971/laptop_das_for_jellyfin)
 - RSS feed: $source
 - date published: 2024-11-25T06:07:35+00:00

<!-- SC_OFF --><div class="md"><p>DAS, not NAS. I found someone selling one near where I live for cheap. There&#39;s usually only one, maybe two people using the JF server at a time. Nothing else much is running on the server. </p> <p>I&#39;m currently running JF on a laptop with hard drives attached to it. I need more storage, but I&#39;m too broke for a proper NAS (also I read that JF doesn&#39;t work well with NASes anyway). As I understand, a DAS just takes hard drives and turns it into one giant storage device. It seems to be what I need.</p> <p>Is this setup advisable? I believe the brand of the DAS I found is Orico. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/vardonir"> /u/vardonir </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzc971/laptop_das_for_jellyfin/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzc971/laptop_das_for_jellyfin/">[comments]</a></span>

## Gluetun ExpressVPN Config help
 - [https://www.reddit.com/r/selfhosted/comments/1gzbkea/gluetun_expressvpn_config_help](https://www.reddit.com/r/selfhosted/comments/1gzbkea/gluetun_expressvpn_config_help)
 - RSS feed: $source
 - date published: 2024-11-25T05:24:10+00:00

<!-- SC_OFF --><div class="md"><p>I am relatively new to composing and stacking docker containers together and I want to setup a Prowlarr, ubittorrent, Sonarr and Radarr service to load anime into my media server. However, I want to set up a vpn network and I believe Gluetun might be the best service for me to choose and I already have an Express VPN subscription. The problem comes from understanding the configuration for it and I cannot seem to see any resources that explain it so that I can understand. I get to the open vpn user and password and I get confused thinking if I have to setup express vpn through their accounts or is there another way to configure the container. I will take any help or resources, I want to build the service one container at a time instead of a stack so that I understand it better.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bowserko"> /u/bowserko </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comm

## Vaultwarden Mobile App Connection Issue on LAN (Self-Hosted, Not Exposed to Internet)
 - [https://www.reddit.com/r/selfhosted/comments/1gzbeuh/vaultwarden_mobile_app_connection_issue_on_lan](https://www.reddit.com/r/selfhosted/comments/1gzbeuh/vaultwarden_mobile_app_connection_issue_on_lan)
 - RSS feed: $source
 - date published: 2024-11-25T05:14:52+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to set up Vaultwarden on my mobile device. Currently, I have Vaultwarden installed on my TrueNAS Scale OS. I am able to log into Vaultwarden via the Firefox extension on my desktop, but I cannot log in via the Bitwarden mobile app when connected to my local network.</p> <p>I do not want to expose Vaultwarden to the public internet. My goal is to sync my passwords when connected to the LAN, and when I&#39;m off the network, I want the Bitwarden mobile app to have read-only access until I reconnect to the LAN.</p> <p>However, for some reason, the Bitwarden mobile app keeps failing to sign in, showing a connection error. I’ve entered my self-hosted private IP: <a href="https://192.168.86.26:30032">https://192.168.86.26:30032</a>, which works fine on my PC through Firefox, but it doesn’t work on my mobile device—even though both devices are connected to the same LAN.</p> <p>Does anyone know how to fix this issue on mobile?</p> </div><!-- SC_O

## Proxmox LXC containers need no passwords
 - [https://www.reddit.com/r/selfhosted/comments/1gzar4l/proxmox_lxc_containers_need_no_passwords](https://www.reddit.com/r/selfhosted/comments/1gzar4l/proxmox_lxc_containers_need_no_passwords)
 - RSS feed: $source
 - date published: 2024-11-25T04:35:52+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/esiy0676"> /u/esiy0676 </a> <br/> <span><a href="https://www.reddit.com/r/ProxmoxQA/comments/1gzalwf/passwordless_lxc_container_login/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gzar4l/proxmox_lxc_containers_need_no_passwords/">[comments]</a></span>

## Symlinks in Nextcloud snap install.
 - [https://www.reddit.com/r/selfhosted/comments/1gza8xj/symlinks_in_nextcloud_snap_install](https://www.reddit.com/r/selfhosted/comments/1gza8xj/symlinks_in_nextcloud_snap_install)
 - RSS feed: $source
 - date published: 2024-11-25T04:06:02+00:00

<!-- SC_OFF --><div class="md"><p>I have a File share setup on Linux at /share/main and wanted Nextcloud to access via mobile or web easily. So. I installed Nextcloud on snap. Comes to find out, I can’t add /share/main as external storage and can only add files in /mint or /media or via FTP/SFTP. Since I have it installed via snap directly on the server the share is on, adding the directory via SFTP just creates more latency and extra hops. I created a symlink to /share/main from /mnt/nas but Nextcloud doesn’t follow or recognize them. I found an article about how to enable them in config.php by setting &#39;localstorage.allowsymlinks&#39; =&gt; true but that doesn’t seem to apply. Does anyone know how to allow symbolic links, or point /mnt/nas to /share/main in a way that will circumvent this? Yes, I know the risks. This is an internal only application and no WAN access. </p> <p>If not, is there anything wrong with creating a permanent directory in /mnt or /media that I can move fil

## X-Post: New in Proxmox 8.3: How to Import an OVA from the Proxmox Web UI
 - [https://www.reddit.com/r/selfhosted/comments/1gz9474/xpost_new_in_proxmox_83_how_to_import_an_ova_from](https://www.reddit.com/r/selfhosted/comments/1gz9474/xpost_new_in_proxmox_83_how_to_import_an_ova_from)
 - RSS feed: $source
 - date published: 2024-11-25T03:04:11+00:00

<!-- SC_OFF --><div class="md"><p>Crosspost from some other subreddits because I think it might help some people:</p> <p>In the most recent release of Proxmox VE 8.3.0, they <a href="https://forum.proxmox.com/threads/proxmox-ve-8-3-released.157793/">added the ability to import an OVA from the Web UI</a>. I tested it out and found some issues with some OVAs, very likely virtual hardware incompatibilities and wrote up a blog post on how to enable the feature and some potential remedies in case others might have the issue.</p> <p><a href="https://homelab.sacentral.info/posts/import-ova-on-proxmox-8_3/">https://homelab.sacentral.info/posts/import-ova-on-proxmox-8_3/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sacentral"> /u/sacentral </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gz9474/xpost_new_in_proxmox_83_how_to_import_an_ova_from/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comme

## Recommended Open Source SELFHOSTED YouTube Alternatives in 2024
 - [https://www.reddit.com/r/selfhosted/comments/1gz8i4u/recommended_open_source_selfhosted_youtube](https://www.reddit.com/r/selfhosted/comments/1gz8i4u/recommended_open_source_selfhosted_youtube)
 - RSS feed: $source
 - date published: 2024-11-25T02:31:16+00:00

<!-- SC_OFF --><div class="md"><p>Was curious if there are any recommended SELFHOSTED Open Source YouTube alternatives in 2024.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/craftbot"> /u/craftbot </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gz8i4u/recommended_open_source_selfhosted_youtube/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gz8i4u/recommended_open_source_selfhosted_youtube/">[comments]</a></span>

## Offline video correction/upscaler
 - [https://www.reddit.com/r/selfhosted/comments/1gz5uf0/offline_video_correctionupscaler](https://www.reddit.com/r/selfhosted/comments/1gz5uf0/offline_video_correctionupscaler)
 - RSS feed: $source
 - date published: 2024-11-25T00:19:29+00:00

<!-- SC_OFF --><div class="md"><p>I have some videos from film in the 90s, they are very dim and low res, I am looking for an offline tool that can do some work on these. I can use gpu acceleration on my server or if there are any recommedations for a standalone windows software I would be interested as well. Something that I can run on a server in docker etc is even better. Thanks for recommendations.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Squanchy2112"> /u/Squanchy2112 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gz5uf0/offline_video_correctionupscaler/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gz5uf0/offline_video_correctionupscaler/">[comments]</a></span>

## Virtualization or containerization for a home server?
 - [https://www.reddit.com/r/selfhosted/comments/1gz5oyn/virtualization_or_containerization_for_a_home](https://www.reddit.com/r/selfhosted/comments/1gz5oyn/virtualization_or_containerization_for_a_home)
 - RSS feed: $source
 - date published: 2024-11-25T00:12:14+00:00

<!-- SC_OFF --><div class="md"><p>I have a home server with proxmox VMs and LXCs for various services. Currently only unifi controller, pihole, uptime kuma, and home assistant, but there are other services I&#39;d like to set up soon. </p> <p>Some of the services are available as docker containers, so I&#39;ve been playing around and learning docker in a Ubuntu VM. Now I am wondering if my existing services should all be docker containers on a single VM or remain as individual VM/LXC. Which is the more common or preferred usage? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/greatluck"> /u/greatluck </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gz5oyn/virtualization_or_containerization_for_a_home/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gz5oyn/virtualization_or_containerization_for_a_home/">[comments]</a></span>

## Local Encrypted File Share like WeTransfer
 - [https://www.reddit.com/r/selfhosted/comments/1gz5igx/local_encrypted_file_share_like_wetransfer](https://www.reddit.com/r/selfhosted/comments/1gz5igx/local_encrypted_file_share_like_wetransfer)
 - RSS feed: $source
 - date published: 2024-11-25T00:03:28+00:00

<!-- SC_OFF --><div class="md"><p>Looking for some suggestions.</p> <p>Wanting to create a local and encrypted file share server that can send files to our business customers with expiring links that are password protected. </p> <p>Where do I begin? </p> <p>Happy to purchase a small server with some SSDs that can host the program locally on site. (If that’s even an option or possible) </p> <p>With some guidance and direction I will be able to set this up myself. Thanks. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jadesigns"> /u/jadesigns </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gz5igx/local_encrypted_file_share_like_wetransfer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gz5igx/local_encrypted_file_share_like_wetransfer/">[comments]</a></span>

## Recommendations: Open-source, self-hosted library for <stuff> and <things>
 - [https://www.reddit.com/r/selfhosted/comments/1gz5hjw/recommendations_opensource_selfhosted_library_for](https://www.reddit.com/r/selfhosted/comments/1gz5hjw/recommendations_opensource_selfhosted_library_for)
 - RSS feed: $source
 - date published: 2024-11-25T00:02:14+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m part of a small photo/video production studio. Ten artists, lots of equipment. We specialize in video production, but we also have a lot of gear and a huge space so we also rent/loan out the space and gear when we can. </p> <p>We&#39;re looking for an open-source solution that will let us treat all of the equipment almost like a library. We have everything from workstations and network hardware to lights, stands, cameras, mics.... There&#39;s probably at least $3M worth of equipment in the space. We want to keep track of it all, keep track of who has what, watch all of our licenses, and maybe possibly be able to create lifespan reports. That last thing is not a deal-breaker. </p> <p>I&#39;ve been looking at Snipe-IT, which looks great but cumbersome. I&#39;ve also been looking at Koha which I think could also do a great job. </p> <p>One requirement is that we need solid mobile access, either via a mobile app or a very very good browser render

