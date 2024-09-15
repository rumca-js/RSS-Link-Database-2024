# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Docker Compose - Nginx Proxy Manager (NPM) HA MariaDB Galera Cluster
 - [https://www.reddit.com/r/selfhosted/comments/1fgzgd9/docker_compose_nginx_proxy_manager_npm_ha_mariadb](https://www.reddit.com/r/selfhosted/comments/1fgzgd9/docker_compose_nginx_proxy_manager_npm_ha_mariadb)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T23:52:03+00:00

<!-- SC_OFF --><div class="md"><p>I wanted to see if anyone has configured and setup a HA NPM on docker. I have 3 docker hosts and I wanted to add redundancy to NPM since it&#39;s a crucial part of the network. Right now I have a script that basically clears out the secondary and tertiary node data and then copies over the data from the primary node. Not the best solution but works for now since I don&#39;t add new entries very often to NPM. </p> <p>To learn more about databases and clustering in general I was trying to see if I could get NPM to work with MariaDB and then have HA configured with a galera cluster. The plan is to open the the syncing ports on the host machines while restricting the client port (3306) to internal. Then let the databases sync with each other while restricting the client port to their local NPM container/local docker network. </p> <p>I guess my main questions are: how should I setup the galera cluster within docker? I found information of setting up the ga

## Privately signed certs and Apple devices?
 - [https://www.reddit.com/r/selfhosted/comments/1fgza6v/privately_signed_certs_and_apple_devices](https://www.reddit.com/r/selfhosted/comments/1fgza6v/privately_signed_certs_and_apple_devices)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T23:43:21+00:00

<!-- SC_OFF --><div class="md"><p>I run an IMAP server with a SSL certificate signed by my private CA.</p> <p>I added the CA to the iPhone and set it as trusted.</p> <p>Yet, the mail app prompts me saying the SSL server certificate isn’t trustworthy. Once in a blue moon I can click “trust” and then all is well. Host name matches a Subject Alternative Name field.</p> <p>But on other setups it just refuses to go further.</p> <p>Is there a magic trick to make such work on apple devices? Don’t they respect the Subject Alternative Name fields like all other devices?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Toiling-Donkey"> /u/Toiling-Donkey </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgza6v/privately_signed_certs_and_apple_devices/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgza6v/privately_signed_certs_and_apple_devices/">[comments]</a></span>

## Best option to get access to vaultwarden externally.
 - [https://www.reddit.com/r/selfhosted/comments/1fgywom/best_option_to_get_access_to_vaultwarden](https://www.reddit.com/r/selfhosted/comments/1fgywom/best_option_to_get_access_to_vaultwarden)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T23:24:33+00:00

<!-- SC_OFF --><div class="md"><p>I’m trying to get access to vaultwarden and potentially other internal services when I’m not at home. What is the best solution for this? I’m running proxmox with nginx proxy manager to create actual urls and get SSL. I’ve considered tailscale and wireguard and have also tried to set up a cloud flare tunnel with no success. (I was trying to tunnel to nginx and couldn’t get that working, haven’t tried with individual services yet.)</p> <p>Happy to provide any further information about my homelab.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/smoochii"> /u/smoochii </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgywom/best_option_to_get_access_to_vaultwarden/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgywom/best_option_to_get_access_to_vaultwarden/">[comments]</a></span>

## My updated dashboard
 - [https://www.reddit.com/r/selfhosted/comments/1fgynlv/my_updated_dashboard](https://www.reddit.com/r/selfhosted/comments/1fgynlv/my_updated_dashboard)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T23:12:12+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fgynlv/my_updated_dashboard/"> <img src="https://b.thumbs.redditmedia.com/vBPFIe5_-KNnspkn48ZhwjIlpvw-ysdNdj48Jn8Cp3E.jpg" alt="My updated dashboard" title="My updated dashboard" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Damn i`m loving using <a href="https://heimdall.site/">Heimdall</a>.</p> <p><a href="https://preview.redd.it/f4q4wlu8xuod1.png?width=1916&amp;format=png&amp;auto=webp&amp;s=dbffafbda9d1328e33b55b95ea114dbbfd04cff0">https://preview.redd.it/f4q4wlu8xuod1.png?width=1916&amp;format=png&amp;auto=webp&amp;s=dbffafbda9d1328e33b55b95ea114dbbfd04cff0</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pedrobuffon"> /u/pedrobuffon </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgynlv/my_updated_dashboard/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgynlv/my_updated_dashboard/">[comments]</a><

## Pihole + Unbound DNS Name
 - [https://www.reddit.com/r/selfhosted/comments/1fgydkp/pihole_unbound_dns_name](https://www.reddit.com/r/selfhosted/comments/1fgydkp/pihole_unbound_dns_name)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T22:58:56+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fgydkp/pihole_unbound_dns_name/"> <img src="https://b.thumbs.redditmedia.com/uSFXjBnM0lOdJXmHvrAPnH709waPueyeAa5M8h5MEgU.jpg" alt="Pihole + Unbound DNS Name" title="Pihole + Unbound DNS Name" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>For anyone using Unbound with Pihole.</p> <p>I&#39;ve ran pihole for a long time. Recently I&#39;ve decided to add Unbound to my mix, and currently, it&#39;s working fine as a recursive DNS.</p> <p>Did numerous leak tests, and my actual server comes up as the only hop.</p> <p>The question however, is related to the &quot;naming scheme&quot; that Pihole uses when the DNS server appears in the logs.</p> <p>I have two DNS servers:</p> <ul> <li><a href="https://10.10.10.10">10.10.10.10</a> (Primary)</li> <li><a href="https://10.10.8.8">10.10.8.8</a> (Secondary)</li> </ul> <p>When I look in Pihole, I see the DNS listed as <code>10.10.10.10#53</code></p> <p>&#x200B;</p> <p><a href

## CloudFlare Tunnels To NPM with mTLS
 - [https://www.reddit.com/r/selfhosted/comments/1fgxux3/cloudflare_tunnels_to_npm_with_mtls](https://www.reddit.com/r/selfhosted/comments/1fgxux3/cloudflare_tunnels_to_npm_with_mtls)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T22:34:10+00:00

<!-- SC_OFF --><div class="md"><p>Hey Everyone,</p> <p>Since the topic of mTLS is all the rave on this sub at the moment I have decided to try it for myself.<br/> I was still hoping to use the CF for the WAF rules with bots and Geoblocking but I cant get mTLS to work, i get &quot;421 Misdirected Request&quot;</p> <p>CF --&gt; NPM --&gt; Host - Works OK<br/> LAN --&gt; NPM + mTSL --&gt; Host Works OK</p> <p>CF --&gt;NPM + mTSL --&gt; Host &quot;421 Misdirected Request&quot;|</p> <p>Do I need to enable something in the CF settings?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/xXAzazelXx1"> /u/xXAzazelXx1 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgxux3/cloudflare_tunnels_to_npm_with_mtls/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgxux3/cloudflare_tunnels_to_npm_with_mtls/">[comments]</a></span>

## Considering a VPS for Self-Hosting Due to ISP Restrictions — Need Advice on Setup, Security, and Bandwidth Concerns
 - [https://www.reddit.com/r/selfhosted/comments/1fgxsax/considering_a_vps_for_selfhosting_due_to_isp](https://www.reddit.com/r/selfhosted/comments/1fgxsax/considering_a_vps_for_selfhosting_due_to_isp)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T22:30:49+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,<br/> <em>(TL;DR at the end)</em></p> <p>I&#39;m looking for some advice and recommendations on self-hosting a variety of services (Plex, Home Assistant, Node-RED, etc.), but facing a common challenge: my ISP blocks ports 80 and 443, which limits my options for exposing these services to the internet. After doing some research, I’ve found two potential solutions:</p> <ol> <li><strong>Cloudflared Tunnels</strong>: <ul> <li><strong>Video Streaming Issues</strong>: I’ve heard Cloudflare Tunnels may block or throttle video streaming services like Plex, which concerns me as I use it for remote access.</li> <li><strong>Scalability</strong>: It doesn’t seem like an ideal long-term solution for hosting multiple apps, especially with services that require higher bandwidth or more direct control over the network.</li> </ul></li> <li><strong>VPS with Traffic Redirect to Home Server</strong>: This option seems like the better choice. I can use a VPS 

## Need a favour - can you access this file?
 - [https://www.reddit.com/r/selfhosted/comments/1fgwmf6/need_a_favour_can_you_access_this_file](https://www.reddit.com/r/selfhosted/comments/1fgwmf6/need_a_favour_can_you_access_this_file)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T21:36:58+00:00

<!-- SC_OFF --><div class="md"><p>I´m trying to use Pingvin share on my NAS. I thought I set it up good but someone was not able to get access my link. Could you please let me know if you can acess this link? <a href="http://100.108.73.51:20000/share/test">http://100.108.73.51:20000/share/test</a></p> <p>Thank you</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Glass-Energy9043"> /u/Glass-Energy9043 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgwmf6/need_a_favour_can_you_access_this_file/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgwmf6/need_a_favour_can_you_access_this_file/">[comments]</a></span>

## Lingarr 0.8.3 A simple user-friendly app to translate subtitles
 - [https://www.reddit.com/r/selfhosted/comments/1fgwcir/lingarr_083_a_simple_userfriendly_app_to](https://www.reddit.com/r/selfhosted/comments/1fgwcir/lingarr_083_a_simple_userfriendly_app_to)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T21:24:33+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fgwcir/lingarr_083_a_simple_userfriendly_app_to/"> <img src="https://a.thumbs.redditmedia.com/21UCbo3X9TxuXBkYmVHlRlg5gtYNseT1-pMpHapDQQ8.jpg" alt="Lingarr 0.8.3 A simple user-friendly app to translate subtitles" title="Lingarr 0.8.3 A simple user-friendly app to translate subtitles" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>After the positive reception of my app, I decided to rebuild Lingarr into a more robust setup using .NET and Vue.js.</p> <p>As I live in a multilingual household, it’s hard to find certain subtitles. I’ve experimented with running a local AI instance and used the latest OpenAI API extensively, but unfortunately, they tended to distort the text, return empty responses, and require multiple very slow and expensive API calls to complete. Eventually, I decided to go with a machine translation API called <a href="https://libretranslate.com/">LibreTranslate</a>. This seems to be the most s

## Any good photo hosting software that supports jxl and Windows?
 - [https://www.reddit.com/r/selfhosted/comments/1fgwbk2/any_good_photo_hosting_software_that_supports_jxl](https://www.reddit.com/r/selfhosted/comments/1fgwbk2/any_good_photo_hosting_software_that_supports_jxl)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T21:23:21+00:00

<!-- SC_OFF --><div class="md"><p>I’d prefer to have a solution that doesn’t create giant preview files, and can do all the transcoding on my pc on demand if needed- but preferably just works out of the box with formats such as jxl. I can do Docker and whatnot if needed. Any help appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/WAFFLED_II"> /u/WAFFLED_II </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgwbk2/any_good_photo_hosting_software_that_supports_jxl/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgwbk2/any_good_photo_hosting_software_that_supports_jxl/">[comments]</a></span>

## For all the jellyfin users here: how do I solve a false duplicate issue?
 - [https://www.reddit.com/r/selfhosted/comments/1fgw58t/for_all_the_jellyfin_users_here_how_do_i_solve_a](https://www.reddit.com/r/selfhosted/comments/1fgw58t/for_all_the_jellyfin_users_here_how_do_i_solve_a)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T21:15:28+00:00

<!-- SC_OFF --><div class="md"><p>I added house md as a series to my jellyfin server (ran inside a docker container) eveverything&#39;s fine except season 5 ep 1 and 2 are called broken part 1 and broken part 2. And jellyfin merges them into one filename (broken) and ignores part 2 completely. Moreover, all the episodes&#39; names are offset. Each name belongs to the next episode. Description and metadata included, as well as the episode counting. How do I solve this? I looked around in the library and told it to prefer embedded titles over filenames, rescanned the entire data, activated the automatic metadata refresher. Nothing so far </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/blackmoi"> /u/blackmoi </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgw58t/for_all_the_jellyfin_users_here_how_do_i_solve_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgw58t/for_all_the_jellyfin_u

## i deployed nextjs on hetzner using kamal
 - [https://www.reddit.com/r/selfhosted/comments/1fgvty7/i_deployed_nextjs_on_hetzner_using_kamal](https://www.reddit.com/r/selfhosted/comments/1fgvty7/i_deployed_nextjs_on_hetzner_using_kamal)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T21:01:09+00:00

<!-- SC_OFF --><div class="md"><p>hi everyone,</p> <p>i spent the whole saturday building a planner-journal <a href="http://eskdule.com">eskdule.com</a> and deployed it on hetzner using kamal. i used cloudflare for https and other services. however, i encountered problems with google oauth. for some reason, cloudflare prevented the redirect, and i always got a 403 error.</p> <p>what are you using for ssl on vps and next.js deployments? someone mentioned coolify a while back.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Commercial_Ear_6989"> /u/Commercial_Ear_6989 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgvty7/i_deployed_nextjs_on_hetzner_using_kamal/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgvty7/i_deployed_nextjs_on_hetzner_using_kamal/">[comments]</a></span>

## Which Cloud Web Hosting is Better: Hostinger "Level 4" or Hetzner "Cloud Startup"?
 - [https://www.reddit.com/r/selfhosted/comments/1fgvkco/which_cloud_web_hosting_is_better_hostinger_level](https://www.reddit.com/r/selfhosted/comments/1fgvkco/which_cloud_web_hosting_is_better_hostinger_level)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T20:49:44+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I&#39;m trying to decide between Hostinger&#39;s &quot;Level 4&quot; plan and Hetzner&#39;s &quot;Cloud Startup&quot; plan for cloud web hosting. I&#39;ve read several negative reviews about Hostinger, but they seem to offer more features for the price compared to Hostinger. Now, I&#39;m stuck and can&#39;t decide which one to go for.</p> <p>Has anyone used either of these services? What’s your experience, and which one would you recommend? </p> <p>Thanks in advance for your opinions and advice! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/egzeq"> /u/egzeq </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgvkco/which_cloud_web_hosting_is_better_hostinger_level/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgvkco/which_cloud_web_hosting_is_better_hostinger_level/">[comments]</a></span>

## Nextcloud domain check self-signed certificate error
 - [https://www.reddit.com/r/selfhosted/comments/1fgva7q/nextcloud_domain_check_selfsigned_certificate](https://www.reddit.com/r/selfhosted/comments/1fgva7q/nextcloud_domain_check_selfsigned_certificate)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T20:33:21+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fgva7q/nextcloud_domain_check_selfsigned_certificate/"> <img src="https://b.thumbs.redditmedia.com/7PlfGY8ehh6cCzkZDj7LqfYWoqvitXaAwx9_iWuJHAc.jpg" alt="Nextcloud domain check self-signed certificate error" title="Nextcloud domain check self-signed certificate error" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I&#39;ve been trying to run nextcloud on my ubuntu 22.04 pc with Nginx proxy manager and while setting up nextcloud I got an error at the domain check saying:<br/> Domain does not point to this server or the reverse proxy is not configured correctly. See the mastercontainer logs for more details. (&#39;sudo docker logs -f nextcloud-aio-mastercontainer&#39;)</p> <p>so I checked the logs and saw this:</p> <p><a href="https://preview.redd.it/93v66hmv4uod1.png?width=1347&amp;format=png&amp;auto=webp&amp;s=0e98214d387b30e0b85c6bbaa9d9f0abb5e61076">https://preview.redd.it/93v66hmv4uod1.png?width=1347&amp;f

## [Help] Game server issues. Pterodactyl, NPM, VPS Tailscale
 - [https://www.reddit.com/r/selfhosted/comments/1fgv2ur/help_game_server_issues_pterodactyl_npm_vps](https://www.reddit.com/r/selfhosted/comments/1fgv2ur/help_game_server_issues_pterodactyl_npm_vps)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T20:22:10+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I am having a heck of a time using my Valheim server. I can join and immediately the data stops being received on the server.</p> <p>I am using pterodactyl server manager self hosted routed with tailscale to a vps using nginx reverse proxy manager.</p> <p>I have minecraft working and it does not do this.</p> <p>Some stuff I&#39;ve done</p> <p>Established a p2p connection with tailscale no derp servers.</p> <p>Have all ports 2456-2458 TCP &amp; UDP forwarded on vps </p> <p>Have the streams pointing to the pterodactyl server with those ports and expecting incoming ports 2456-2458 with tcp and udp forwarding on.</p> <p>I have also installed some networking mods to no luck.</p> <p>Not sure where to go as I have no problem with minecraft whatsoever.</p> <p>I also have added the ports in the nginx docker compose and udp as well. </p> <p>Any advice would be great.</p> <p>I also have a domain name with a a record for the server. But connecting to both 

## Web based web browser
 - [https://www.reddit.com/r/selfhosted/comments/1fguwk2/web_based_web_browser](https://www.reddit.com/r/selfhosted/comments/1fguwk2/web_based_web_browser)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T20:14:29+00:00

<!-- SC_OFF --><div class="md"><p>Does anyone know if there is an easy to host web browser that uses native web technologies? </p> <p>I&#39;m looking for something like <a href="https://github.com/BrowserBox/BrowserBox?tab=readme-ov-file">BrowserBox</a> that could be easily deployed with a docker compose file.</p> <p>I&#39;ve tried hosting Firefox (in particular the image from <a href="https://docs.linuxserver.io/images/docker-firefox/">linuxserver.io</a>, and while they work ok, they are quite laggy, especially on a poor Internet connection. I&#39;ve also tried Neko but I either don&#39;t understand it well enough or am configuring something wrong.</p> <p>Anyone know of any other options out there?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/root42_"> /u/root42_ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fguwk2/web_based_web_browser/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comm

## Authelia/Authethik + Google OAuth +TOTP
 - [https://www.reddit.com/r/selfhosted/comments/1fgurlj/autheliaauthethik_google_oauth_totp](https://www.reddit.com/r/selfhosted/comments/1fgurlj/autheliaauthethik_google_oauth_totp)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T20:08:05+00:00

<!-- SC_OFF --><div class="md"><p>Hello Everyone, </p> <p>I am new to self host community. I am working on to set up code-server with traefik as reverse proxy and portainer to manage it. </p> <p>I am thinking of adding a layer of authentication and authorization. But there are certain requirement. I want google oauth with totp. Is there a way to achieve it. I am using a VPS of 4 CPU and 6 GB of ram. I want something of light so that my code-server could work properly. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Strange_n00b"> /u/Strange_n00b </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgurlj/autheliaauthethik_google_oauth_totp/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgurlj/autheliaauthethik_google_oauth_totp/">[comments]</a></span>

## Does One desire to ShelfHost ever stop
 - [https://www.reddit.com/r/selfhosted/comments/1fgt08a/does_one_desire_to_shelfhost_ever_stop](https://www.reddit.com/r/selfhosted/comments/1fgt08a/does_one_desire_to_shelfhost_ever_stop)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T18:50:54+00:00

<!-- SC_OFF --><div class="md"><p>Does the desire to shelfhost StopSerious question, Has anyone simply just got the bare need meet and stopped or does everyone continue to ask . Could i selfhost it and continue to search for apps, containers, etc. Just me lol ok. I dont think i enjoy the stuff i have already before trying look for another solution lol just me again. Got it</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok_Award_2793"> /u/Ok_Award_2793 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgt08a/does_one_desire_to_shelfhost_ever_stop/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgt08a/does_one_desire_to_shelfhost_ever_stop/">[comments]</a></span>

## Is building a cloud-agnostic architecture worth the effort for small-scale projects?
 - [https://www.reddit.com/r/selfhosted/comments/1fgsriw/is_building_a_cloudagnostic_architecture_worth](https://www.reddit.com/r/selfhosted/comments/1fgsriw/is_building_a_cloudagnostic_architecture_worth)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T18:31:46+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m debating whether it&#39;s worth investing time and effort into building a cloud-agnostic software architecture, or if the cost and complexity aren&#39;t justified. I&#39;m planning to launch several small projects, some of which may scale over time, while others may not.</p> <p>The idea is to avoid being tightly coupled to a specific cloud provider by designing a decoupled architecture that allows for easy migration between services like AWS, Hetzner, and others based on needs and cost. This would involve clean architectures, minimal dependencies on provider-specific services, etc.</p> <p>Has anyone here evaluated or worked with cloud-agnostic setups? Does the flexibility of easily moving between cloud providers outweigh the complexity and potential performance trade-offs? Or is it more practical to just go all-in with something like AWS, taking advantage of the strong integration between their services? I&#39;d love to hear about your experie

## Survey 2024 - Home Server OS for a Master's thesis
 - [https://www.reddit.com/r/selfhosted/comments/1fgspwt/survey_2024_home_server_os_for_a_masters_thesis](https://www.reddit.com/r/selfhosted/comments/1fgspwt/survey_2024_home_server_os_for_a_masters_thesis)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T18:29:46+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I&#39;m currently working on my Master’s thesis in Business Informatics, and I’m researching operating systems for home servers. My study aims to evaluate how well an operating system meets the various needs of home server users, including data storage, media servers, virtualization, and more.</p> <p>I’ve created a short survey (just 3-5 minutes) to gather insights users like yourselves. Your responses will be invaluable in helping me better understand the practical applications.</p> <p>All answers are anonymous and will be used solely for academic purposes. I would greatly appreciate your participation and feedback.</p> <p>Thanks so much for your time and input!</p> <p>Here is the link (please delete the space before the dot): soscisurvey .de/heimserver2024/</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/UnraidFollower"> /u/UnraidFollower </a> <br/> <span><a href="https://www.reddit.com/r/s

## Delay or Restart Stack if volumes are not yet available.
 - [https://www.reddit.com/r/selfhosted/comments/1fgsncy/delay_or_restart_stack_if_volumes_are_not_yet](https://www.reddit.com/r/selfhosted/comments/1fgsncy/delay_or_restart_stack_if_volumes_are_not_yet)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T18:26:48+00:00

<!-- SC_OFF --><div class="md"><p>Is there a way to wait for the Volumes to be mounted first before creating/starting the stack, similar to depends_on?</p> <p>Volumes: disk1, disk2, disk3 are CIFS</p> <p>Here is my compose:</p> <pre><code>--- networks: servaarr: external: true name: servaarr volumes: disk1: name: disk1 disk2: name: disk2 disk3: name: disk3 jellyfin: name: jellyfin services: jellyfin: image: lscr.io/linuxserver/jellyfin:latest container_name: jellyfin environment: - PUID=${PUID} - PGID=${PGID} - TZ=${TZ} volumes: - disk1:/disk1:ro - disk2:/disk2:ro - disk3:/disk3:ro - jellyfin:/config restart: unless-stopped devices: - &quot;/dev/dri:/dev/dri&quot; - &quot;/dev/snd:/dev/snd&quot; networks: servaarr: ipv4_address: 172.19.0.11 ports: - 8096:8096 </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tonitz4493"> /u/tonitz4493 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgsncy/delay_or_restart_stack_if_

## My First Go Project - Pulsarego: A Simple Server Monitoring Tool with Telegram Alerts
 - [https://www.reddit.com/r/selfhosted/comments/1fgs652/my_first_go_project_pulsarego_a_simple_server](https://www.reddit.com/r/selfhosted/comments/1fgs652/my_first_go_project_pulsarego_a_simple_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T18:05:42+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fgs652/my_first_go_project_pulsarego_a_simple_server/"> <img src="https://external-preview.redd.it/DTiF69rU7oElZa-v-9EalMBzbUAsbYyPRF6KcrIvaOc.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=0626a1486c889eface7d28302e0444d402f7d2d5" alt="My First Go Project - Pulsarego: A Simple Server Monitoring Tool with Telegram Alerts" title="My First Go Project - Pulsarego: A Simple Server Monitoring Tool with Telegram Alerts" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey everyone! 😅</p> <p>I recently ran into an issue that I think many of you may have faced: some websites or servers stop responding for various reasons. It was becoming a headache to figure out what was going wrong and when it happened.</p> <p>I tried some solutions like <strong>Grafana</strong></p> <p>So, what did I do? I decided to write my own solution! 📟</p> <p>Introducing <strong>Pulsargo</strong> - a simple tool I built with <strong>Go</strong

## Help with Netbird in a Docker Container
 - [https://www.reddit.com/r/selfhosted/comments/1fgrney/help_with_netbird_in_a_docker_container](https://www.reddit.com/r/selfhosted/comments/1fgrney/help_with_netbird_in_a_docker_container)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T17:42:28+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fgrney/help_with_netbird_in_a_docker_container/"> <img src="https://b.thumbs.redditmedia.com/HJIfBqZ2DNCMS87iSZmMaVIonSatNI7ANFamjNDjtck.jpg" alt="Help with Netbird in a Docker Container" title="Help with Netbird in a Docker Container" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I am trying to set up Netbird. I have some services (e.g., calibre-web, paperless-ngx) for which I have Docker containers. I have created peers for my desktop, my laptop, my iphone, and docker. I was thinking that the next step is to get my Docker containers to talk to the docker netbird as a routing peer, so that inbound traffic (me -- when I&#39;m not on my local home Wi-Fi) gets routed to the right Docker container and can access the service. I was thinking of it something like the below diagram (from Netbird&#39;s own docs) where the right-side private network are the multiple Docker containers that connect to the Netbird docke

## Installing OKD on proxmox
 - [https://www.reddit.com/r/selfhosted/comments/1fgrgre/installing_okd_on_proxmox](https://www.reddit.com/r/selfhosted/comments/1fgrgre/installing_okd_on_proxmox)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T17:33:51+00:00

<!-- SC_OFF --><div class="md"><p>Hello :) In my work, I have an openshift cluster, I wanted to install a single node okd to play around and test some stuff I&#39;m not able to do at work due to beurocracies. Has anyone installed single node OKD into proxmox? I have followed the documentation here: <a href="https://docs.okd.io/4.16/installing/installing_sno/install-sno-preparing-to-install-sno.html">https://docs.okd.io/4.16/installing/installing_sno/install-sno-preparing-to-install-sno.html</a></p> <p>I have openwrt as my router, and I have configured its dnsmasq to point apps.domain.com to the vm IP and hostname set by dns. </p> <p>I&#39;m having an issue with certificates and it seems the install isn&#39;t proceeding because of that, I can&#39;t seem to get it working past that.</p> <p>Has anyone installed okd on their servers? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ddrjm"> /u/ddrjm </a> <br/> <span><a href="https://www.reddit.com/r/s

## Looking for an open-source solution for tracking account and insurance data?
 - [https://www.reddit.com/r/selfhosted/comments/1fgr3kz/looking_for_an_opensource_solution_for_tracking](https://www.reddit.com/r/selfhosted/comments/1fgr3kz/looking_for_an_opensource_solution_for_tracking)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T17:17:36+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone!</p> <p>I’ve already built a Django-based platform for tracking our stock portfolios, including live stock prices, charts, and other features. Now, before I extend the platform to track all of our account information (bank accounts, depot data) and insurance details (pension insurance, other insurances), I’m wondering:</p> <p>Is there already an open-source solution that handles these things?</p> <p>I’d rather not reinvent the wheel if something robust and secure already exists. Any recommendations would be greatly appreciated!</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TimTimmaeh"> /u/TimTimmaeh </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgr3kz/looking_for_an_opensource_solution_for_tracking/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgr3kz/looking_for_an_opensource_solution_for_tracking/">[comment

## Recommendations, please - polished individual apps to replace NextCloud piece by piece
 - [https://www.reddit.com/r/selfhosted/comments/1fgquwo/recommendations_please_polished_individual_apps](https://www.reddit.com/r/selfhosted/comments/1fgquwo/recommendations_please_polished_individual_apps)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T17:05:52+00:00

<!-- SC_OFF --><div class="md"><p>Finally got NextCloud setup up and I’m SO disappointed that I was actually motivated to post a rant about it in <a href="/r/NextCloud">r/NextCloud</a>.</p> <p>The promise of NextCloud - getting all my data under my control without the spying eyes of Google… my Contcts and Calendar… Office apps… replacing Dropbox with cloud storage and file sharing that <strong><em>I</em></strong> control, replacing Evernote (one of my most used apps) with something that doesn’t cost way too much (and tries to strongarm me into paying by gradually reducing the functionality and capacity that I had grown used to)… and several more services - this was what got me into self-hosting in the first place. But NextCloud broke my heart and now I need an alternative.</p> <p>It occurs to me that I can create a “My Cloud” group in Dashy (LOVE Dashy!) and place icons in it for individual services that are polished and relatively bug free. Then, because I use mobile apps much more t

## Cheap server motherboard with BMC?
 - [https://www.reddit.com/r/selfhosted/comments/1fgqor4/cheap_server_motherboard_with_bmc](https://www.reddit.com/r/selfhosted/comments/1fgqor4/cheap_server_motherboard_with_bmc)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T16:58:30+00:00

<!-- SC_OFF --><div class="md"><p>Do any of you know a cheap motherboard for servers with a BMC with web interface for remote administration? I&#39;m looking for remote desktop and the ability to upload and install ISOs directly from the web interface. Something like the AsRock Rack motherboards have.</p> <p>Everywhere I look they are ridiculously expensive. Maybe there&#39;s a older one that&#39;s commonly sold second hand from retired servers?</p> <p>Any advice is greatly appreciated</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Drunken_Sheep_69"> /u/Drunken_Sheep_69 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgqor4/cheap_server_motherboard_with_bmc/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgqor4/cheap_server_motherboard_with_bmc/">[comments]</a></span>

## Household Budget / Finance
 - [https://www.reddit.com/r/selfhosted/comments/1fgqi12/household_budget_finance](https://www.reddit.com/r/selfhosted/comments/1fgqi12/household_budget_finance)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T16:50:08+00:00

<!-- SC_OFF --><div class="md"><p>Looking for a self-hosted budget/finance app to manage household expenses. Does anyone have any suggestions? The only one i seem to find when searching is Firefly III.<br/> It looks interesting. Can anyone comment on it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bonervz"> /u/bonervz </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgqi12/household_budget_finance/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgqi12/household_budget_finance/">[comments]</a></span>

## Access my server with same URL both internally and externally
 - [https://www.reddit.com/r/selfhosted/comments/1fgqahg/access_my_server_with_same_url_both_internally](https://www.reddit.com/r/selfhosted/comments/1fgqahg/access_my_server_with_same_url_both_internally)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T16:40:49+00:00

<!-- SC_OFF --><div class="md"><p>I have Nginx Proxy manager and Adguard DNS. I access my docker apps as app.servername.local.</p> <p>Now. with Tailscale, it works as servername:port only. But how do I make it to work as app.servername.local i.e. the same way I access internally.</p> <p>I tried playing around with Magic DNS and NameServers settings. But I couldn&#39;t make it to work the way I expect.</p> <p>Is this even possible?</p> <p>P.S: I have domain and cloudflare setup. But as Cloudflare TOS is against using Jellyfin, I thought of using Tailscale to access my Jellyfin externally. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ExceptionOccurred"> /u/ExceptionOccurred </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgqahg/access_my_server_with_same_url_both_internally/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgqahg/access_my_server_with_same_url_both_internally/">[comme

## How to access qBitTorrent through cloudflare tunnel?
 - [https://www.reddit.com/r/selfhosted/comments/1fgpobj/how_to_access_qbittorrent_through_cloudflare](https://www.reddit.com/r/selfhosted/comments/1fgpobj/how_to_access_qbittorrent_through_cloudflare)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T16:13:27+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fgpobj/how_to_access_qbittorrent_through_cloudflare/"> <img src="https://b.thumbs.redditmedia.com/BoQcnyiinjpFTrUhpCw5zrKegHAu_GuPKiZnXByaSYc.jpg" alt="How to access qBitTorrent through cloudflare tunnel?" title="How to access qBitTorrent through cloudflare tunnel?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/8hrk9589usod1.png?width=2304&amp;format=png&amp;auto=webp&amp;s=0555d518ed66db21575d19378fbb392e8f81ec15">https://preview.redd.it/8hrk9589usod1.png?width=2304&amp;format=png&amp;auto=webp&amp;s=0555d518ed66db21575d19378fbb392e8f81ec15</a></p> <p>when I try to access qBitTorrent through the cloudflare tunnel it appears the unauthorized message as shown in the image above, but if local access works, why?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/technomanceer"> /u/technomanceer </a> <br/> <span><a href="https://www.reddit.com/

## Docker-Webtop: Web based Linux environment
 - [https://www.reddit.com/r/selfhosted/comments/1fgpnck/dockerwebtop_web_based_linux_environment](https://www.reddit.com/r/selfhosted/comments/1fgpnck/dockerwebtop_web_based_linux_environment)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T16:12:16+00:00

<!-- SC_OFF --><div class="md"><p>Here&#39;s another project I self-host to give folks access to a Linux environment for playing around in. I like that it streams audio and the video playback is pretty smooth.</p> <p><a href="https://github.com/linuxserver/docker-webtop">https://github.com/linuxserver/docker-webtop</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Slow_Wafer3174"> /u/Slow_Wafer3174 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgpnck/dockerwebtop_web_based_linux_environment/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgpnck/dockerwebtop_web_based_linux_environment/">[comments]</a></span>

## Web gui for Streamrip ?
 - [https://www.reddit.com/r/selfhosted/comments/1fgp2yi/web_gui_for_streamrip](https://www.reddit.com/r/selfhosted/comments/1fgp2yi/web_gui_for_streamrip)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T15:47:22+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I wanted to know if you know or use any kind of remote gui for downloading albums via Streamrip ?</p> <p>I really want to have all the music I like In the best quality but it&#39;s kind of not practical to ssh as soon as I think of a new track/album.</p> <p>I searched for programs online but found nothing so maybe you guys know better than me, have a nice day !</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Daitan_"> /u/Daitan_ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgp2yi/web_gui_for_streamrip/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgp2yi/web_gui_for_streamrip/">[comments]</a></span>

## 50GB HTML won’t open
 - [https://www.reddit.com/r/selfhosted/comments/1fgp27s/50gb_html_wont_open](https://www.reddit.com/r/selfhosted/comments/1fgp27s/50gb_html_wont_open)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T15:46:28+00:00

<!-- SC_OFF --><div class="md"><p>So i’ve got a 50gb chat backup with a loved one and it’s in a HTML format, anytime i try to open it, it crashes my web browser (firefox) and renders it useless, is there a way of converting it to maybe pdf and having a purposeful app open it for viewing? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Bitter-Limit-5759"> /u/Bitter-Limit-5759 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgp27s/50gb_html_wont_open/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgp27s/50gb_html_wont_open/">[comments]</a></span>

## torrenting without paid vpn (kind of)
 - [https://www.reddit.com/r/selfhosted/comments/1fgofa4/torrenting_without_paid_vpn_kind_of](https://www.reddit.com/r/selfhosted/comments/1fgofa4/torrenting_without_paid_vpn_kind_of)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T15:18:05+00:00

<!-- SC_OFF --><div class="md"><p>I just gpt-ed this code and I&#39;m planning to use it for torrenting.</p> <ul> <li><p>I&#39;m setting up ProtonVPN with OpenVPN on my server(with GUI).</p></li> <li><p>Running the script by providing the magnet link as input in YouKnowWhat colab notebook.</p></li> <li><p>Using cron to automate moving the MP4 files to the Jellyfin-hosted folder.</p></li> </ul> <p>how is this........? Is this safe since the ip expose is YouKnowWhat&#39;s and using a vpn as an extra protection</p> <p>code cells:</p> <pre><code>!python -m pip install --upgrade pip setuptools wheel !python -m pip install lbry-libtorrent !apt install python3-libtorrent import libtorrent as lt # Create a libtorrent session and set it to listen on ports 6881 to 6891 ses = lt.session() ses.listen_on(6881, 6891) downloads = [] params = {&quot;save_path&quot;: &quot;/content/m&quot;} # Infinite loop to accept magnet links from the user # If the user types &#39;exit&#39;, the loop breaks and no 

## Best self-hosted AI model/service for technical writing?
 - [https://www.reddit.com/r/selfhosted/comments/1fgnbo5/best_selfhosted_ai_modelservice_for_technical](https://www.reddit.com/r/selfhosted/comments/1fgnbo5/best_selfhosted_ai_modelservice_for_technical)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T14:28:40+00:00

<!-- SC_OFF --><div class="md"><p>I recently bought a used workstation off ebay for a home server and was pleasantly surprised to find it came with an RTX 2060 12gb (along with 14-core Xeon processor and 80gb RAM). I&#39;d love to be able to run my own LLM that I can train using existing documents and related prompts/instructions. I&#39;d like to be able to directly import PDFs but they could be OCR&#39;d and copy pasted in if necessary. I&#39;ve tooled around with LM Studio and some 7b models and was not very impressed but I was running it on less capable hardware and wasn&#39;t really trying to optimize it. Any suggestions on what to look into or consider?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/leadbread"> /u/leadbread </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgnbo5/best_selfhosted_ai_modelservice_for_technical/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgnbo5/b

## Multiple Vocals in Synchronized Lyrics
 - [https://www.reddit.com/r/selfhosted/comments/1fgn12b/multiple_vocals_in_synchronized_lyrics](https://www.reddit.com/r/selfhosted/comments/1fgn12b/multiple_vocals_in_synchronized_lyrics)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T14:14:51+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fgn12b/multiple_vocals_in_synchronized_lyrics/"> <img src="https://a.thumbs.redditmedia.com/0pQODB6eAVzeLE8O5BEZNYzia4fE5d1Ha9fbomhTrB8.jpg" alt="Multiple Vocals in Synchronized Lyrics" title="Multiple Vocals in Synchronized Lyrics" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I&#39;m really looking foward to properly store (and show) multiple vocals lines in a song when they are sung simultaneously, like it happens on Apple Music, for example.<br/> Does id3v2 or .lrc files support this?</p> <p><a href="https://preview.redd.it/l0isxhdq9sod1.png?width=1843&amp;format=png&amp;auto=webp&amp;s=80aa98a5ab1d1eed5a01334dd5bf5f38dd46c8ad">https://preview.redd.it/l0isxhdq9sod1.png?width=1843&amp;format=png&amp;auto=webp&amp;s=80aa98a5ab1d1eed5a01334dd5bf5f38dd46c8ad</a></p> <p><em>Image: Apple Music&#39;s multi-line lyrics feature, where the background vocals are shown as a smaller text line</em></p> </div><!-- SC_O

## Getting started with a proliant micro server.
 - [https://www.reddit.com/r/selfhosted/comments/1fgmyjg/getting_started_with_a_proliant_micro_server](https://www.reddit.com/r/selfhosted/comments/1fgmyjg/getting_started_with_a_proliant_micro_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T14:11:29+00:00

<!-- SC_OFF --><div class="md"><p>Is it a good idea to start with a proliant microserver? How much RAM is good, and how much is better? What processors should I am for? I know that everything depends on the workload and all that, but my primary use case would be, proxmox, with 2-3 vms, one of the vms will have to manage the docker containers.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/New_Speaker9998"> /u/New_Speaker9998 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgmyjg/getting_started_with_a_proliant_micro_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgmyjg/getting_started_with_a_proliant_micro_server/">[comments]</a></span>

## VPN protocols or obfuscation methods for China and Iran
 - [https://www.reddit.com/r/selfhosted/comments/1fgm446/vpn_protocols_or_obfuscation_methods_for_china](https://www.reddit.com/r/selfhosted/comments/1fgm446/vpn_protocols_or_obfuscation_methods_for_china)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T13:30:31+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a vpn protocol or obfuscation method that now in 2024 works in countries with DPI.</p> <p>I&#39;ve heard wiregaurd does not work in China and Iran, and don&#39;t have any news if OpenVPN+obfsproxy works or not.</p> <p>I want to know which protocol or obfuscation method actually works in these countries, and how can I learn to implement it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Neither-Copy-8508"> /u/Neither-Copy-8508 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgm446/vpn_protocols_or_obfuscation_methods_for_china/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgm446/vpn_protocols_or_obfuscation_methods_for_china/">[comments]</a></span>

## How do I use nginxproxy AND use internally?
 - [https://www.reddit.com/r/selfhosted/comments/1fglh98/how_do_i_use_nginxproxy_and_use_internally](https://www.reddit.com/r/selfhosted/comments/1fglh98/how_do_i_use_nginxproxy_and_use_internally)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T12:59:38+00:00

<!-- SC_OFF --><div class="md"><p>Good day all,</p> <p>I am just getting going with some self hosted stuff, and it&#39;s going quite well. I am playing with Immich for some photo storage currently, and I am loving it. Got nginxproxymanager all setup too.</p> <p>So, I have <a href="http://pics.domain.com">pics.domain.com</a> setup in proxy with lets encrypt and works exactly how I need it to me. But im running into issue where if Im inside my network (via wifi) and I have Immich setup to use <a href="http://pics.domain.com">pics.domain.com</a> it won&#39;t work. More specifically, if I go to <a href="https://pics.domain.com">https://pics.domain.com</a> it comes up with my opnsense router interface. So I know this has something to do with DNS of some sort, as its trying to got out, but its in at the same time.</p> <p>How do I make that part work like I want it to?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jdlnewborn"> /u/jdlnewborn </a> <br/>

## Opinions: I currently host a busy website (mysql, elastic, php) and a mailserver (dockermailserver), all containerised, on dedicated tin running in Hetzner, and fronted by traefik with crowdsec keeping an eye on baddies. What's your view on risk?
 - [https://www.reddit.com/r/selfhosted/comments/1fgk1jd/opinions_i_currently_host_a_busy_website_mysql](https://www.reddit.com/r/selfhosted/comments/1fgk1jd/opinions_i_currently_host_a_busy_website_mysql)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T11:36:44+00:00

<!-- SC_OFF --><div class="md"><p>I know in an ideal world I should split off data and mail onto two different servers. Very aware of what good looks like. </p> <p>My challenge is cost. It&#39;s a community website which does not make a huge amount of cash so splitting it all will go from breaking even to a cost. </p> <p>Should I strive for perfect or is good-enough good enough? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CrappyTan69"> /u/CrappyTan69 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgk1jd/opinions_i_currently_host_a_busy_website_mysql/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgk1jd/opinions_i_currently_host_a_busy_website_mysql/">[comments]</a></span>

## Looking for tips to become completely self hosted.
 - [https://www.reddit.com/r/selfhosted/comments/1fgjj73/looking_for_tips_to_become_completely_self_hosted](https://www.reddit.com/r/selfhosted/comments/1fgjj73/looking_for_tips_to_become_completely_self_hosted)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T10:58:48+00:00

<!-- SC_OFF --><div class="md"><p>As with many many threads in here, I know. I am looking for some advice as to what type of products to look into in order to becoming completely self sufficient. If the internet goes out, my system stays in order, is the end goal. Like everyone here I’m sure.</p> <p>My setup Running a custom NAS using Unraid. N5105 mobo. Jonah n4 case.. 16gb ram, and a 25tb array. </p> <p>Before I got into the whole self hosted world, I was already pretty setup with smart lights all around the house. Though this is currently a cocktail of different systems, that I mainly use Alexa to manage. Routines and groups, are generally managed in the Alexa app. I have a bunch of Hue lights and quite a few Govees, with the odd Wiz, IKEA or switchbot bulb/strip thrown in there.</p> <p>I run HA from a VM on my unraid, which seems to expose most if not all my smart lights, which is good. </p> <p>However, I would like to explore how to take things a little further and have more cont

## Tonight I set up my Homepage. Would love to discuss ^^
 - [https://www.reddit.com/r/selfhosted/comments/1fgjd9v/tonight_i_set_up_my_homepage_would_love_to_discuss](https://www.reddit.com/r/selfhosted/comments/1fgjd9v/tonight_i_set_up_my_homepage_would_love_to_discuss)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T10:47:13+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fgjd9v/tonight_i_set_up_my_homepage_would_love_to_discuss/"> <img src="https://preview.redd.it/50uc1e6f8rod1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=9c43667eb5dec3ac8e631027141d8d72118dbf89" alt="Tonight I set up my Homepage. Would love to discuss ^^" title="Tonight I set up my Homepage. Would love to discuss ^^" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>This is everything I&#39;m currently hosting. It&#39;s still very work in progress, but I&#39;m happy about it!</p> <p>For the dashboard, I&#39;m running <a href="https://gethomepage.dev/latest/">Homepage</a> with a tiny bit of custom CSS.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TadeasJun"> /u/TadeasJun </a> <br/> <span><a href="https://i.redd.it/50uc1e6f8rod1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgjd9v/tonight_i_set_up_my_homepage_would_love_to_d

## Remote Print Server
 - [https://www.reddit.com/r/selfhosted/comments/1fgjd56/remote_print_server](https://www.reddit.com/r/selfhosted/comments/1fgjd56/remote_print_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T10:46:58+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I want to host a print server on a RPI Zero 2W using cups and there are great tutorials on it already but I can&#39;t seem to anything related to a remote print server. Is there any way that I can possibly use something like a cloudflare tunnel to use my printer over the internet using a sub domain, as my ISP has put me behind a NAT and there&#39;s no option for me to get a static IP and no port forwarding option. </p> <p>I can use tailscale and setup the PI as an exit node but don&#39;t really wanna connect to a VPN just to print something. Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/xicor2205"> /u/xicor2205 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgjd56/remote_print_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgjd56/remote_print_server/">[comments]</a></span>

## Solving IP conflict with VPN
 - [https://www.reddit.com/r/selfhosted/comments/1fgismp/solving_ip_conflict_with_vpn](https://www.reddit.com/r/selfhosted/comments/1fgismp/solving_ip_conflict_with_vpn)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T10:05:06+00:00

<!-- SC_OFF --><div class="md"><p>I have a self-hosted VPN at home (PiVPN/WireGuard). When I connect to a different router and activate the VPN, I cannot access my services I host at home. The problem is that both routers use the same 192.168.1.x range.</p> <p>I use Nginx Proxy Manager with my own domain (&quot;A&quot; record pointing to internal address 192. ...) to access the services. I don&#39;t want (can&#39;t) change the settings on the new/old router, and I would prefer to avoid changing the device&#39;s settings (as the device is owned by someone who doesn&#39;t understand much about VPNs).</p> <p>What solutions do I have, so I can continue using my services locally on my network and also through the VPN with the IP conflict? A link to an article would be very appreciated, but I can also search it myself.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MxxPuig"> /u/MxxPuig </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comm

## Analytics on phone grafana
 - [https://www.reddit.com/r/selfhosted/comments/1fgiq0v/analytics_on_phone_grafana](https://www.reddit.com/r/selfhosted/comments/1fgiq0v/analytics_on_phone_grafana)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T10:00:15+00:00

<!-- SC_OFF --><div class="md"><p>So im using Zabbix and its doing great, grafana is really what i watch graphs and for quick analysis of everything. </p> <p>I have some stuff i like to see through my phone. Grafana works okay on iOS through web browser. But i feel like there should be something better out there? Zabbix app isn’t really showing everything. Any suggestions?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Oblec"> /u/Oblec </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgiq0v/analytics_on_phone_grafana/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgiq0v/analytics_on_phone_grafana/">[comments]</a></span>

## Yet another post on specs
 - [https://www.reddit.com/r/selfhosted/comments/1fgii0q/yet_another_post_on_specs](https://www.reddit.com/r/selfhosted/comments/1fgii0q/yet_another_post_on_specs)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T09:43:27+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I would like to build my home server but I don&#39;t know how to choose the MB, CPU, PSU, RAM, storage (with RAID).<br/> The services I would like to host are:</p> <ul> <li>SearxNG</li> <li>Calibre</li> <li>Gitea</li> <li>XMPP server (as ejabberd)</li> <li>Mail</li> <li>nextcloud</li> <li>wireguard</li> </ul> <p>So nothing that individually needs high performances. I am especially requiring names and brands for all these pieces but more the methodology I should use to make the best choice to optimize the performances, the cost and the energy consumption of this build. Thanks in advance for your answers and your help :D </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Rhylx"> /u/Rhylx </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgii0q/yet_another_post_on_specs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgii0q/yet_another_po

## Self host an analytics dashboard that simplifies developers lives.
 - [https://www.reddit.com/r/selfhosted/comments/1fgi2vd/self_host_an_analytics_dashboard_that_simplifies](https://www.reddit.com/r/selfhosted/comments/1fgi2vd/self_host_an_analytics_dashboard_that_simplifies)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T09:10:18+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I’m Antonio, CEO at Litlyx.</p> <p>I’m in love with this community because it is filled with people who help each other without expecting anything in return. You all truly embody the spirit of open-source. So, I want to start this post with a big THANK YOU to everyone in this community. You guys are amazing!</p> <p>About a month ago, I shared a post here, and it seemed like everyone resonated with our passion for developing tools that help developers.</p> <p>The FOSS community has given me so much on my journey to becoming a developer, so we decided to give back by creating a project that is completely open-source and, most importantly, <a href="https://github.com/Litlyx/litlyx">self-hostable</a>.</p> <p>I&#39;m talking about <strong>Litlyx</strong>!</p> <p>Litlyx is a developer-friendly analytics tool that offers you tremendous freedom when it comes to tracking data on your website or web apps. It works seamlessly with just a few lines of code, r

## Homepage + NPM = 502 Bad Gateway
 - [https://www.reddit.com/r/selfhosted/comments/1fgi24j/homepage_npm_502_bad_gateway](https://www.reddit.com/r/selfhosted/comments/1fgi24j/homepage_npm_502_bad_gateway)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T09:08:45+00:00

<!-- SC_OFF --><div class="md"><p>I just installed Homepage via docker-compose but I am unable to get it working behind Nginx Proxy Manager. I have a private domain all set up and ~20 services running in my home network all working with SSL and local subdomains. But whatever I configure in NPM and Homepage&#39;s settings.yaml (are the `base` and `starturl` settings even relevant in my case?), I always end up with a 502 error.</p> <p>Also, I seem unable to find documentation on Homepage and proxies, maybe because homepage is a very generic term ... any tips? I start getting frustrated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/juekr"> /u/juekr </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgi24j/homepage_npm_502_bad_gateway/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgi24j/homepage_npm_502_bad_gateway/">[comments]</a></span>

## Authentik logos not showing on dashboard
 - [https://www.reddit.com/r/selfhosted/comments/1fghici/authentik_logos_not_showing_on_dashboard](https://www.reddit.com/r/selfhosted/comments/1fghici/authentik_logos_not_showing_on_dashboard)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T08:27:35+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fghici/authentik_logos_not_showing_on_dashboard/"> <img src="https://b.thumbs.redditmedia.com/tOjSYAC8v97gcQzqgXhntDZXrFc1CRhM2HaAgi955ag.jpg" alt="Authentik logos not showing on dashboard" title="Authentik logos not showing on dashboard" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi all, </p> <p>Recently setup authentik and routing all my services through it now. </p> <p>Wanted to check if anyone have the same issues as I do. When I add in logos for my apps, I can see them in the &quot;configure&quot; application page (see screenshot) but when it&#39;s in my main dashboard screen it shows as the first letter of my application. This is driving my OCD a little crazy. </p> <p>Not sure if anyone has the same issues I do and solutions on how to resolve it? </p> <p><a href="https://preview.redd.it/btmratsfjqod1.png?width=564&amp;format=png&amp;auto=webp&amp;s=1bcda5e6dcb4a5a7a8aad6879d7bdf084065a15e">https://p

## Seeking Advice: Security and Network Access for N8N etc. (Localhost)
 - [https://www.reddit.com/r/selfhosted/comments/1fghhry/seeking_advice_security_and_network_access_for](https://www.reddit.com/r/selfhosted/comments/1fghhry/seeking_advice_security_and_network_access_for)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T08:26:23+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, </p> <p>I&#39;m relatively new to self-hosting and have been experimenting with running some tools on my Mac while connected to my home WiFi. I&#39;m using applications like Baserow and NocoDB, which run in the browser. While these are fine locally, I&#39;m curious about potential network concerns, especially since some of these tools connect to external APIs, like N8N.</p> <ol> <li><strong>Security on Localhost</strong>: Even though I&#39;m running everything on localhost, I&#39;m concerned about network security since these tools connect to external APIs. What precautions should I take to ensure my setup remains secure?</li> <li><strong>Network Isolation</strong>: Given that I&#39;m just on my home WiFi, how isolated is my setup really? Are there steps I should take to further isolate or secure my environment?</li> <li><strong>Beginner-Friendly Advice</strong>: As a newbie, a lot of the information I find online is geared towards set

## Will this be enaugh?
 - [https://www.reddit.com/r/selfhosted/comments/1fggvz5/will_this_be_enaugh](https://www.reddit.com/r/selfhosted/comments/1fggvz5/will_this_be_enaugh)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T07:39:52+00:00

<!-- SC_OFF --><div class="md"><p>So I want to boild a server (repurpouse some second hand pc) and I found this for $350 at local marketplace</p> <p>i3-12100 16 GB RAM (gonna add up to 32-64 if needed) RX 6400 (4GB) (I theoreticly could get gtx 1050 insted in it) 256 GB m.2 ssd And 1 TB hdd (gonna put 3 3/4 TB drives in, for raid2)</p> <p>But I have the problem that I don&#39;t know if it has any pcie slots left free for me to use...</p> <p>What I wat to run on it: Virtualized TrueNas (i need to pass the drives to it, so I need pcie connection) NextCloud Jellyfin server Git server Some databases Game servers (Minecraft, cs, etc.) Some sound streaming solution Reverse proxy Vpn server</p> <p>Can I run all of these servicces on this pc, or should I keep looking?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gun3kter_cz"> /u/gun3kter_cz </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fggvz5/will_this_be_enaugh/">[link]</a><

## Self hosted chat app with PWA push notifications
 - [https://www.reddit.com/r/selfhosted/comments/1fggt3i/self_hosted_chat_app_with_pwa_push_notifications](https://www.reddit.com/r/selfhosted/comments/1fggt3i/self_hosted_chat_app_with_pwa_push_notifications)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T07:33:59+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to find a chat solution to self host in my home network for family. Anything that’s similar to whatsapp, slack, discord, etc would work. Just need to be able to send DMs, create groups, upload media, etc. My top requirement is to be able to add the web app PWA to home screen and receive push notifications. </p> <p>I tried rocket chat but push notifications only work in desktop chrome. Push notifications don’t work in ios safari when added to home screen (PWA). I don’t want to use their cloud push gateway for push notifications. I don’t want any data to leave my network. </p> <p>I looked through ONCE Campfire and it looks like it has everything I am looking for including ios PWA push notifications. But it’s not OSS. </p> <p>Are there other OSS solutions out there that I should try?</p> <p>Requirements:</p> <ul> <li>DMs</li> <li>Groups/Channels</li> <li>Share images, videos, etc</li> <li>PWA that supports iOS push notifications</li> <li>Good

## My selfhosted journey
 - [https://www.reddit.com/r/selfhosted/comments/1fgghxo/my_selfhosted_journey](https://www.reddit.com/r/selfhosted/comments/1fgghxo/my_selfhosted_journey)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T07:09:31+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m currently running an Ubuntu server 24.04 LTS with a Hyper-V vm running on top of Windows 10. What I like about this setup is that it is running on conventional hardware and provides some basic services that I wanted to make. I already have a few users.</p> <ul> <li>Podman rootless<br/></li> <li>Systemd running the Podman Quadlet (containers)<br/></li> <li>Wg easy for Wireguard VPN management<br/></li> <li>Forgejo - Forge, Gitea fork<br/></li> <li>Forgejo actions - Github style actions provides automation for deploying to other services<br/></li> <li>Nginx proxy manager - Provides SSL certificates and have added a wildcard without issues for intranet HTTPS support. Is able to route to https any main route to any port<br/></li> <li>Inadyn - To set up the Dynamic IP/domain to be able to connect through a nice real FQDN domain name.<br/></li> <li>Only open ports to UDP Wireguard port on the server router<br/></li> <li>Dnsmasq, you can configure DN

## My homepage
 - [https://www.reddit.com/r/selfhosted/comments/1fgg5yz/my_homepage](https://www.reddit.com/r/selfhosted/comments/1fgg5yz/my_homepage)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T06:46:49+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fgg5yz/my_homepage/"> <img src="https://preview.redd.it/n5gmpfgi1qod1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=42625d0a2eb50b17cdddc2b0a832e570d4d5bddf" alt="My homepage" title="My homepage" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Gel0_F"> /u/Gel0_F </a> <br/> <span><a href="https://i.redd.it/n5gmpfgi1qod1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgg5yz/my_homepage/">[comments]</a></span> </td></tr></table>

## Hosting data from 4 computers
 - [https://www.reddit.com/r/selfhosted/comments/1fgf2h1/hosting_data_from_4_computers](https://www.reddit.com/r/selfhosted/comments/1fgf2h1/hosting_data_from_4_computers)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T05:30:18+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, I hot a gig for handling data across 4 computers for a client. He has his data in form of documents snd videos on 4 different computers and wants a system in place for compiling them all. He also mentioned for videos he wants to use mega or YouTube and also has an HP server I&#39;m assuming he has windows installed in his systems. He has no technical expertise but i guess wants a secure system in place Any suggestions on how to do this and how much time would it actually take I have 0 experience in this but I’m guessing he wants to self host so that’s why I’m posting here Thanks in advance</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Waaun_waaunwakawaaun"> /u/Waaun_waaunwakawaaun </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgf2h1/hosting_data_from_4_computers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgf2h1/hosting_data_from_4_c

## Can't figure out how load balancer is not overwhelmed
 - [https://www.reddit.com/r/selfhosted/comments/1fgey1g/cant_figure_out_how_load_balancer_is_not](https://www.reddit.com/r/selfhosted/comments/1fgey1g/cant_figure_out_how_load_balancer_is_not)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T05:22:44+00:00

<!-- SC_OFF --><div class="md"><p>let say you have 1 million requests / sec, you use reverse proxy to round robin the requests into 4 different servers, that works.</p> <p>in the end, a reverse proxy is still a software and can be overwhelmed by the amount of request, how does one deal with this?</p> <p>the only 2 solution I heard is dns round robin and sophisticated method to route the same ip address into 2 different location like what google does. The former won&#39;t work because client will cache the dns request, the latter can only be done by having access to the physical network infrastructure. </p> <p>Can anyone explain? thx.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Chillseashells"> /u/Chillseashells </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgey1g/cant_figure_out_how_load_balancer_is_not/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgey1g/cant_figure_out_how_l

## A BlackHat Self-Hosted Homelab (project)
 - [https://www.reddit.com/r/selfhosted/comments/1fgett2/a_blackhat_selfhosted_homelab_project](https://www.reddit.com/r/selfhosted/comments/1fgett2/a_blackhat_selfhosted_homelab_project)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T05:13:57+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, my project idea is to make exactly what the title describes. A BlackHat Self-Hosted homelab would and should include privacy, security, encryption, OPSEC/Anonymization and more but all armed to the teeth. Please share your ideas of what I can include into this project, I would to see what we come up with. Feel free to ask any questions too!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/xilentbangg"> /u/xilentbangg </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgett2/a_blackhat_selfhosted_homelab_project/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgett2/a_blackhat_selfhosted_homelab_project/">[comments]</a></span>

## Question about Leantime
 - [https://www.reddit.com/r/selfhosted/comments/1fgejbw/question_about_leantime](https://www.reddit.com/r/selfhosted/comments/1fgejbw/question_about_leantime)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T04:55:58+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m sorry to hijack this sub on a specific app, but Leantime doesn&#39;t have a discord or reddit page of its own. </p> <p>I&#39;ve tested Leantime docker container on a VM and its very promising. </p> <p>I am leading a small non-profit and I am looking to use Leantime for free. </p> <p>While it is clear that Whiteboard is a premium function, I was wondering if there are other limitations? </p> <p>Does the 150 to-dos still apply to the self hosted version? Will completed cards count?</p> <p>Again, I&#39;m sorry for hijacking this sub.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cof666"> /u/cof666 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgejbw/question_about_leantime/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgejbw/question_about_leantime/">[comments]</a></span>

## Anyone of you grabbed these Mac Pro with 96GB of RAM?
 - [https://www.reddit.com/r/selfhosted/comments/1fge3cj/anyone_of_you_grabbed_these_mac_pro_with_96gb_of](https://www.reddit.com/r/selfhosted/comments/1fge3cj/anyone_of_you_grabbed_these_mac_pro_with_96gb_of)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T04:28:51+00:00

<!-- SC_OFF --><div class="md"><p>I don’t know if you guys have seen but bunch of Facebook 2019 Mac Pro’s are going for less than $1700. </p> <p>Mind you these are the last Intel CPU powered Mac Pros meaning we can use these with Windows , Linux, and MacOS natively.</p> <p>I grabbed one with 96GB for like $1500. Can go up to 1.5TB of RAM</p> <p>My question here is I want to use this with 100s of docker containers for my own servers what OS should I use to host it that uses the least resources?</p> <p>Thank you </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/KnowledgeHot2022"> /u/KnowledgeHot2022 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fge3cj/anyone_of_you_grabbed_these_mac_pro_with_96gb_of/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fge3cj/anyone_of_you_grabbed_these_mac_pro_with_96gb_of/">[comments]</a></span>

## Best way to view movies/series?
 - [https://www.reddit.com/r/selfhosted/comments/1fgdvsr/best_way_to_view_moviesseries](https://www.reddit.com/r/selfhosted/comments/1fgdvsr/best_way_to_view_moviesseries)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T04:16:21+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m a sucker for a clean and good looking ui... What&#39;s the best way to view my hosted movies and series? I&#39;m on Chromecast with Google tv, but I&#39;m open to change to something similar if I need to, matter of fact I&#39;m already looking into the Nvidia shield. But I&#39;m turning to you, if you have ideas for me I&#39;m all ears! </p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SergeJeante"> /u/SergeJeante </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgdvsr/best_way_to_view_moviesseries/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgdvsr/best_way_to_view_moviesseries/">[comments]</a></span>

## A BlackHat North Korean Hacker's Self-Hosted Homelab
 - [https://www.reddit.com/r/selfhosted/comments/1fgduqo/a_blackhat_north_korean_hackers_selfhosted_homelab](https://www.reddit.com/r/selfhosted/comments/1fgduqo/a_blackhat_north_korean_hackers_selfhosted_homelab)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T04:14:38+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, this is my first contribution to this subreddit and to reddit as a whole and I wanted to make it special and relatively unique. (Warning this is a LONG post). For the next few months to a year I want to make A BlackHat North Korean Hacker&#39;s Self-Hosted Homelab. The game plan is to eventually sell it to someone who is very passionate about it. I&#39;m coordinating this project in 7 parts:</p> <ul> <li>brainstorm (gathering ideas from everyone on what the homelab includes)</li> <li>agenda (have everything planned out ready to go on step 3)</li> <li>blueprint (a layout to what parts and components I need to complete the project as well as a visual representation of what it would look like and what software it&#39;s constructed of)</li> <li>build (self-explanatory)</li> <li>setup (self-explanatory)</li> <li>troubleshoot (self-explanatory)</li> <li>sell (self-explanatory)</li> <li>What I need from everyone now is to flood the comments with id

## anything similar to localtunnel / loophole.site for websocket protocol?
 - [https://www.reddit.com/r/selfhosted/comments/1fgaesa/anything_similar_to_localtunnel_loopholesite_for](https://www.reddit.com/r/selfhosted/comments/1fgaesa/anything_similar_to_localtunnel_loopholesite_for)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T00:57:38+00:00

<!-- SC_OFF --><div class="md"><p>im working on a project that i initially thought would be easy, but got stumped when i needed to host something that uses the websocket ws:// protocol. i have yet to find al alternative to localtunnel/loophole/playit that supports this protocol. if anyone knows anything similar that supports the websocket protocol please tell me</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cryptoEnegma"> /u/cryptoEnegma </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgaesa/anything_similar_to_localtunnel_loopholesite_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fgaesa/anything_similar_to_localtunnel_loopholesite_for/">[comments]</a></span>

## What's your/the best solution for internal+external DNS resolution with SSL?
 - [https://www.reddit.com/r/selfhosted/comments/1fga53n/whats_yourthe_best_solution_for_internalexternal](https://www.reddit.com/r/selfhosted/comments/1fga53n/whats_yourthe_best_solution_for_internalexternal)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T00:44:07+00:00

<!-- SC_OFF --><div class="md"><p>The question might not be the clearest, so let me reiterate it with the problem statement.</p> <p>I have a number of services running on my local network. Due to certain reasons (mainly Google&#39;s fault), I need SSL to a few of them, most importantly to Home Assistant, without going outside my network (or even letting the local services know my external IP). I also have a number of services that require external access, such as my Matrix (Synapse) server.</p> <p>I would like to put all of these onto the same proxy to handle SSL wrapping, and also to avoid having to remember IP addresses. I also have my own FQDN which I&#39;d like to use both internally and externally.</p> <p>So, a few scenarios to describe this:</p> <ul> <li>I&#39;m on my home WiFi, in my local network range, and want to access homeassistant.my.fqdn - my internal DNS server points this request to my proxy server&#39;s internal IP, which proxies 10.0.0.homeassistant with SSL.</li> <l

## VPS choice fatigue
 - [https://www.reddit.com/r/selfhosted/comments/1fg9ww0/vps_choice_fatigue](https://www.reddit.com/r/selfhosted/comments/1fg9ww0/vps_choice_fatigue)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-14T00:32:34+00:00

<!-- SC_OFF --><div class="md"><p>I really want to get started with a VPS but feel like there’s too much choice. </p> <p>My usual flow is: pick one, start doing some research, get excited to start using it, then start getting put off by all the negative reviews on subreddits about the service being shut down, poor customer experience, hiking up prices etc. So I move on to the next…</p> <p>Examples of this being hostinger, oracle cloud and hetzner</p> <p>Anyone else experience this?</p> <p>I’m looking for something for £10 or less per month where I can a handful of services and a db. </p> <p>I wonder whether I’m either missing something, need to up my budget, or need to just pick one and accept that it may be a crap experience</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/data15cool"> /u/data15cool </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fg9ww0/vps_choice_fatigue/">[link]</a></span> &#32; <span><a href="https://ww

