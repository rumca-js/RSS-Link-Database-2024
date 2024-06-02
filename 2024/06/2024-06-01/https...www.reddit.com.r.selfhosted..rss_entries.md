# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## I’m trying to expose a L2TP-accessed network via Wireguard and Docker compose
 - [https://www.reddit.com/r/selfhosted/comments/1d5z3ok/im_trying_to_expose_a_l2tpaccessed_network_via](https://www.reddit.com/r/selfhosted/comments/1d5z3ok/im_trying_to_expose_a_l2tpaccessed_network_via)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T22:51:53+00:00

<!-- SC_OFF --><div class="md"><p>I'm trying to expose a L2TP accessed network via WireGuard and docker compose</p> <p>Hi all,</p> <p>I'm connecting to a work clients network using a L2TP VPN connection but I would like to expose it via Wireguard for convenience (and iOS support) sake.</p> <p>Basically Wireguard -&gt; L2TP -&gt; work client LAN</p> <p>Here is my docker-compose so far: ```yaml services: l2tp-vpn-client: image: r0hm1/l2tp-vpn-client:latest container_name: l2tp-vpn-client privileged: true cap_add: - NET_ADMIN networks: - bridge-vpn ports: - 51821:51820/udp volumes: - /lib/modules:/lib/modules:ro environment: - VPN_SERVER_IPV4=WORK_CLIENT_IP - VPN_PSK=SECRET - VPN_USERNAME=USER - VPN_PASSWORD=PASS - LAN=10.16.16.0/24 restart: unless-stopped</p> <p>wireguard: image: lscr.io/linuxserver/wireguard:latest container_name: l2tp-vpn-client-wireguard cap_add: - NET_ADMIN - SYS_MODULE network_mode: container:l2tp-vpn-client environment: - PUID=1000 - PGID=1000 - SERVERURL=MY_IP - 

## How to remote access homelab with WireGuard + local DNS names?
 - [https://www.reddit.com/r/selfhosted/comments/1d5ybqa/how_to_remote_access_homelab_with_wireguard_local](https://www.reddit.com/r/selfhosted/comments/1d5ybqa/how_to_remote_access_homelab_with_wireguard_local)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T22:14:15+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I'm quite new to self hosting and have been messing with Docker and running self-hosted media services. I don't have a dedicated machine yet for running everything, so for now the services are run on a Docker container in WSL2 (not really an issue).</p> <p>I've been using Tailscale to access my media remotely, which has been working fine, but want to migrate to WireGuard so I can setup subdomains for each service, use names instead of ip addresses (Tailscale only lets you use &quot;machine&quot; names with MagicDNS) + supposedly better performance. </p> <p>I was looking into buying a domain name for cheap but if I pointed it at my home ip that would raise security concerns. Is there a way I can use local domains that I can access from outside my network while using a VPN? </p> <p>Edit: Would it be possible to point a domain name towards my Tailscale ip's? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ep

## Matrix Homeserver Issues
 - [https://www.reddit.com/r/selfhosted/comments/1d5xaiy/matrix_homeserver_issues](https://www.reddit.com/r/selfhosted/comments/1d5xaiy/matrix_homeserver_issues)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T21:26:19+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1d5xaiy/matrix_homeserver_issues/"> <img alt="Matrix Homeserver Issues" src="https://b.thumbs.redditmedia.com/mdtzTI08EWWu2w13tImsKm-nFDhcioM4GEF4HCR16BQ.jpg" title="Matrix Homeserver Issues" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/q2nvmdh5214d1.png?width=1027&amp;format=png&amp;auto=webp&amp;s=a107e51e93138c1db31d0b5a07457dee9415615d">https://preview.redd.it/q2nvmdh5214d1.png?width=1027&amp;format=png&amp;auto=webp&amp;s=a107e51e93138c1db31d0b5a07457dee9415615d</a></p> <p>I want to see if anyone has had issues like this. I have the matrix installed. Working and showing me the page when I visit my URL.</p> <p>When I try to connect via element, I get this error: Can't connect to homeserver - please check your connectivity, ensure your <a href="https://chat.mysite.com">homeserver's SSL certificate</a> is trusted, and that a browser extension is not blocking requests.</p> <

## Third time failing at exposing self hosted services
 - [https://www.reddit.com/r/selfhosted/comments/1d5wwyh/third_time_failing_at_exposing_self_hosted](https://www.reddit.com/r/selfhosted/comments/1d5wwyh/third_time_failing_at_exposing_self_hosted)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T21:08:39+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I'm coming here defeated for the third time by my own limits. I am a jr web dev but networks have always been my weakness. Over the last year I tried deploying some self hosted services with a domain name in order to access them over the internet without always having to rely on wireguard, so i can also share them with family.</p> <p>I purchased a domain name on porkbun and followed tutorials on how to move the DNS to cloudflare and use the tunnels, but failed. Then last week I followed a Raid Owl tutorial on how to use <a href="https://www.youtube.com/watch?%20v=2fA6u9eahNw&amp;pp=ygUWcmFpZCBvd2wgcmV2ZXJzZSBwcm94eQ%3D%3D">link here</a> on how to make my own private tunnel with Tailscale.</p> <p>Now i am facing 2 issues:</p> <ul> <li><p>It only works if i set my DNS records as &quot;DNS only&quot; while leaving them as &quot;Proxied&quot; wont work (timeout request)</p></li> <li><p>I tested (using DNS only) setting my A name test.myowndomain.xyz t

## I'm confused, it is correct to have a single Proxmox server to handle NAS, Immich and Plex?
 - [https://www.reddit.com/r/selfhosted/comments/1d5w9mp/im_confused_it_is_correct_to_have_a_single](https://www.reddit.com/r/selfhosted/comments/1d5w9mp/im_confused_it_is_correct_to_have_a_single)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T20:38:05+00:00

<!-- SC_OFF --><div class="md"><p>Hi Everyone, first post on this sub. I'm a developer, but newbie into this awesome world.<br /> In the past 2 months I started experiencing Proxmox on a very old laptop (i3-3110M, 4GB ram) and I studied a lot of things (related to power efficiency) in order to build my personal home server. I'm planning to buy everything I need, but I still can't find (or understand) some things.</p> <p>In short my main goals are:</p> <ul> <li>Nas for storage</li> <li>Immich or alternatives for memories</li> <li>Media server, with hardware transcoding when necessary </li> <li>Virtual images usage (I'm planning to run a VM with Windows for work-related stuff, so I can use it when I'm at my parents house throught Wireguard. I'm also planning to use them to play with some linux distros).</li> <li>Docker installed somewhere (now it's on a Debian lxc container on Proxmox)</li> </ul> <p>My questions are:</p> <ol> <li>It is correct to use one single phisical server with Prox

## Recently graduated as a CS major and all of my applications keep getting rejected so I started solo developing a roguelite instead
 - [https://www.reddit.com/r/selfhosted/comments/1d5w03k/recently_graduated_as_a_cs_major_and_all_of_my](https://www.reddit.com/r/selfhosted/comments/1d5w03k/recently_graduated_as_a_cs_major_and_all_of_my)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T20:25:29+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1d5w03k/recently_graduated_as_a_cs_major_and_all_of_my/"> <img alt="Recently graduated as a CS major and all of my applications keep getting rejected so I started solo developing a roguelite instead" src="https://external-preview.redd.it/d_Xr81yYkwll92xkFdUrZ2a5G0zWgDfkwpHOFTqOx0I.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=54f8d52dba1c7d82cbc11764e942696bf3a2e6cd" title="Recently graduated as a CS major and all of my applications keep getting rejected so I started solo developing a roguelite instead" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Vortexile"> /u/Vortexile </a> <br /> <span><a href="https://store.steampowered.com/app/2266780/Ascendant/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5w03k/recently_graduated_as_a_cs_major_and_all_of_my/">[comments]</a></span> </td></tr></table>

## Self-Hosted Docker Diary Container
 - [https://www.reddit.com/r/selfhosted/comments/1d5vpeh/selfhosted_docker_diary_container](https://www.reddit.com/r/selfhosted/comments/1d5vpeh/selfhosted_docker_diary_container)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T20:11:21+00:00

<!-- SC_OFF --><div class="md"><p>Hi all!</p> <p>I'm currently running unRAID on my home server and am looking for a self-hosted diary/journal app which I can also use on my mobile, either via an app or simple web UI - After searching I found the following but had many difficulties installing it via a VM and am unsure how to via Docker:<br /> <a href="https://github.com/inoda/journal">https://github.com/inoda/journal</a></p> <p>If anyone has any alternatives/similar applications please let me know! </p> <p>Thanks!<br /> Kian</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kianwalters05"> /u/kianwalters05 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5vpeh/selfhosted_docker_diary_container/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5vpeh/selfhosted_docker_diary_container/">[comments]</a></span>

## Home dashboard
 - [https://www.reddit.com/r/selfhosted/comments/1d5vcry/home_dashboard](https://www.reddit.com/r/selfhosted/comments/1d5vcry/home_dashboard)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T19:56:02+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1d5vcry/home_dashboard/"> <img alt="Home dashboard" src="https://preview.redd.it/2wjih2hmm04d1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=bfedba9f8b06d48da27a76d36635b3f77d0cdf93" title="Home dashboard" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>First time posting here. Please delete if it’s not appropriate. Here is my home automation/information dashboard. All javascript, css and html. The data sits on an old laptop that runs a web server &amp; CORS server. Various api calls fetch the data. There are a lot of touch functions too, that reveal things you cannot see in the picture. It will show all cameras, control all lights, show daily/hourly forecasts, let us know if school busses are cancelled in the winter and even feed up a ‘dad joke’ upon request! It has been a work in progress for about 5 years. Hopefully this is the right crowd to appreciate it haha. Happy to answer any questions. </p> </div>

## IMMICH
 - [https://www.reddit.com/r/selfhosted/comments/1d5v9v4/immich](https://www.reddit.com/r/selfhosted/comments/1d5v9v4/immich)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T19:52:30+00:00

<!-- SC_OFF --><div class="md"><p>Hello all,</p> <p>New question here…looking to setup IMMICH as moving away from Google Photos and this self hosted option appears to be a good solution. </p> <p>Buying a mini pc to run Linux and IMMICH. Got my head round how to setup (I think). </p> <p>What other things do I need to consider please? Worried I take the plunge and get completely lost ha!</p> <p>Remote access with VPN. </p> <p>Do I need to install any protection? </p> <p>Good with tech but brand new to this self hosted stuff so trying to learn before I dive head first as the Mrs will get annoyed when I spend weeks or days with no progress!</p> <p>Many thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/adzg91"> /u/adzg91 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5v9v4/immich/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5v9v4/immich/">[comments]</a></span>

## Is there an alternative self-hosting application for Goodreads?
 - [https://www.reddit.com/r/selfhosted/comments/1d5v22c/is_there_an_alternative_selfhosting_application](https://www.reddit.com/r/selfhosted/comments/1d5v22c/is_there_an_alternative_selfhosting_application)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T19:42:48+00:00

<!-- SC_OFF --><div class="md"><p>I need an app to track the books/comics/manga I read. I don’t want the app to be overloaded with additional tracking options like movies/shows. Something similar to Goodreads with a simple UI. </p> <p>Preferably with an iOS app or PWA</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Michaelscarn69-"> /u/Michaelscarn69- </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5v22c/is_there_an_alternative_selfhosting_application/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5v22c/is_there_an_alternative_selfhosting_application/">[comments]</a></span>

## How do I get automatic updates on Debian?
 - [https://www.reddit.com/r/selfhosted/comments/1d5v1e1/how_do_i_get_automatic_updates_on_debian](https://www.reddit.com/r/selfhosted/comments/1d5v1e1/how_do_i_get_automatic_updates_on_debian)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T19:41:54+00:00

<!-- SC_OFF --><div class="md"><p>How often should I be checking for updates... I'm thinking once a week at 3am, how can I set this up?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RathdrumRain"> /u/RathdrumRain </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5v1e1/how_do_i_get_automatic_updates_on_debian/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5v1e1/how_do_i_get_automatic_updates_on_debian/">[comments]</a></span>

## I wrote a book about self-hosting for a small group of friends/family
 - [https://www.reddit.com/r/selfhosted/comments/1d5uzhz/i_wrote_a_book_about_selfhosting_for_a_small](https://www.reddit.com/r/selfhosted/comments/1d5uzhz/i_wrote_a_book_about_selfhosting_for_a_small)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T19:39:36+00:00

<!-- SC_OFF --><div class="md"><p>I just released an ebook for learning how to self-host services (on your own bare metal server or VM). I'm proud of it; please check it out.<br /> If you're not yet self-hosting or looking to adjust your self-hosting setup, you might find it useful.</p> <p><a href="https://selfhostbook.com/news/2024/05/ebook-release/">https://selfhostbook.com/news/2024/05/ebook-release/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/meonkeys"> /u/meonkeys </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5uzhz/i_wrote_a_book_about_selfhosting_for_a_small/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5uzhz/i_wrote_a_book_about_selfhosting_for_a_small/">[comments]</a></span>

## In Leantime, what's the difference between goals and milestones?
 - [https://www.reddit.com/r/selfhosted/comments/1d5uy7q/in_leantime_whats_the_difference_between_goals](https://www.reddit.com/r/selfhosted/comments/1d5uy7q/in_leantime_whats_the_difference_between_goals)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T19:37:56+00:00

<!-- SC_OFF --><div class="md"><p>I'm finding it a little hard to get my head around the interface, it seems a little convoluted. What's the difference between the goals and the milestones? I always think of milestones as goals.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mean_Actuator3911"> /u/Mean_Actuator3911 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5uy7q/in_leantime_whats_the_difference_between_goals/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5uy7q/in_leantime_whats_the_difference_between_goals/">[comments]</a></span>

## Reverst - Self-Hosted Reverse Tunnels (like Ngrok) with HTTP/3 and QUIC
 - [https://www.reddit.com/r/selfhosted/comments/1d5uqi5/reverst_selfhosted_reverse_tunnels_like_ngrok](https://www.reddit.com/r/selfhosted/comments/1d5uqi5/reverst_selfhosted_reverse_tunnels_like_ngrok)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T19:27:49+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1d5uqi5/reverst_selfhosted_reverse_tunnels_like_ngrok/"> <img alt="Reverst - Self-Hosted Reverse Tunnels (like Ngrok) with HTTP/3 and QUIC" src="https://external-preview.redd.it/DwkvXOyNkOKkkfvsz-zijgyE8QqBzjfZBn0moIefZ1w.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=8e5b9de804aa5c2ddb479898700e78a913a2c246" title="Reverst - Self-Hosted Reverse Tunnels (like Ngrok) with HTTP/3 and QUIC" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bullcitydev"> /u/bullcitydev </a> <br /> <span><a href="https://github.com/flipt-io/reverst">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5uqi5/reverst_selfhosted_reverse_tunnels_like_ngrok/">[comments]</a></span> </td></tr></table>

## Soccer and lacrosse game footage
 - [https://www.reddit.com/r/selfhosted/comments/1d5uojk/soccer_and_lacrosse_game_footage](https://www.reddit.com/r/selfhosted/comments/1d5uojk/soccer_and_lacrosse_game_footage)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T19:25:11+00:00

<!-- SC_OFF --><div class="md"><p>Is there anything similar to hudl in the self hosted space. Something that us parents can upload footage of our kids games and make highlight clips with? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TenuredKarma1"> /u/TenuredKarma1 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5uojk/soccer_and_lacrosse_game_footage/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5uojk/soccer_and_lacrosse_game_footage/">[comments]</a></span>

## Got my first IT job cause this sub
 - [https://www.reddit.com/r/selfhosted/comments/1d5tgf0/got_my_first_it_job_cause_this_sub](https://www.reddit.com/r/selfhosted/comments/1d5tgf0/got_my_first_it_job_cause_this_sub)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T18:29:29+00:00

<!-- SC_OFF --><div class="md"><p>I got into self hosting back in 2016 cause I was tired of having to pay for Netflix, Hulu just to watch 1 thing on that platform. Found Plex and found out how to download movies/TV shows.</p> <p>Then manually searching for content became a pain. So I automated the process with my Arr stack.</p> <p>Then in 2020 I found network chuck who introduced me to docker with his portainer video. Along with the basics of Linux &amp; Networking.</p> <p>Fast forward 4 years now (24 now) I have a whole homelab infrastructure. 2 proxmox nodes, TrueNas, AWX, Cloud machines, authentik, probably 45 Virtual machines in total all for different services. 7 domains and countless subdomains, CI/CD for Git repos, etc. If it's open source and can be installed in a homelab, ive probably tried it.</p> <p>Anyway, before this I didn't know anything about Linux/tech. Was working a sales job. But this has became an addiction lol. I fully credit this subreddit for showing me what's a

## How do I get started
 - [https://www.reddit.com/r/selfhosted/comments/1d5sqhb/how_do_i_get_started](https://www.reddit.com/r/selfhosted/comments/1d5sqhb/how_do_i_get_started)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T17:57:06+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I’m fairly new to self hosting but have some basic experience with working in linux and extremely basic understanding of networking. I’ve only really worked with raspberry pis before.</p> <p>My long term goal is to have a home server that can do 3 things: secure storage (I want to move away from google drive), photo gallery viewer/syncer (I want to move away from google photos), and password storage (moving away from google passwords). I’ve been researching different tools to do this but I’m kind of lost as to where to start (Nextcloud, syncthing, bitwarden, photoprism). </p> <p>From what I understand, to access my server from outside my wifi I’d need some kind of VPN or wireguard+open port. I’m leaning toward wireguard since I want to store and access sensitive data and don’t mind opening a port on my router (which I will do on a virtual LAN to protect my other devices). </p> <p>This is a long term project but I figured the first place t

## Photo sharing platform - PhotoPrism or Immich
 - [https://www.reddit.com/r/selfhosted/comments/1d5s8g4/photo_sharing_platform_photoprism_or_immich](https://www.reddit.com/r/selfhosted/comments/1d5s8g4/photo_sharing_platform_photoprism_or_immich)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T17:33:51+00:00

<!-- SC_OFF --><div class="md"><p>I have a use case to share photos with my family and friends on something that isn't called Google Photos (or <em>any</em> social media). Google Photos is actually great for this since it allows comments and easy sharing, but I'm done with Google now. </p> <p>Which of those (or any others) should I look at? I don't need <em>any</em> backup as I do that via other workflows. I only need something that lets me securely share links to albums of photos with people. If they need to sign up, I ... guess I can work out how to get my computer-phobic father in, but it would be nice if I can just share anonymous links. </p> <p>Looking at Immich, I also have to say: it does seem <em>very</em> popular and well-supported, but is under incredibly heavy development and just about to transfer to a new owner. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kribensis"> /u/kribensis </a> <br /> <span><a href="https://www.reddit.com

## Cloud Providers and storage
 - [https://www.reddit.com/r/selfhosted/comments/1d5s2xh/cloud_providers_and_storage](https://www.reddit.com/r/selfhosted/comments/1d5s2xh/cloud_providers_and_storage)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T17:26:34+00:00

<!-- SC_OFF --><div class="md"><p>Hello there,</p> <p>Since my current cloud server will be decommissioned I'm taking the time to review my options. If I continue on the cloud server road one thing I'm trying to figure out is storage. My current server has 2TB storage. I don't use all of it but let's say that 1TB would be a good thing between videos and photos. Now, finding 1TB built in is usually quite rare. So I was thinking let's get a Hetzner VPS for instance and a 1TB storage box to put the videos and photos there and have them read by Jellyfin hosted on the VPS.</p> <p>Question is, how do you &quot;connect&quot; the two usually. I'm not accustomed to those cloud storage, how do you mount them on the server. Does it even make sense what I'm describing or would it be a stupid setup ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Erwyn"> /u/Erwyn </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5s2xh/cloud_providers_

## tillywork (opensource work management) is now on Docker Hub
 - [https://www.reddit.com/r/selfhosted/comments/1d5qkng/tillywork_opensource_work_management_is_now_on](https://www.reddit.com/r/selfhosted/comments/1d5qkng/tillywork_opensource_work_management_is_now_on)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T16:16:42+00:00

<!-- SC_OFF --><div class="md"><p>We released our image on Docker Hub today to make it easier for you to play around with our application (if you're hosting it for production, we recommend docker compose).</p> <p>You can find instructions how to get setup in <a href="https://docs.tilly.work/getting-started/using-tillywork#docker-hub">our docs</a>.</p> <p>We also added our board view, enabled creating views for your lists, and you can now drag tasks around to order them or change their stage!</p> <p>Over the coming days we'll be making it possible for you to invite team members to enable collaboration, as we work towards moving from an MVP with 2 pages to an actually usable product.</p> <p>For more information, check out <a href="https://tilly.work">our website</a> or checkout the <a href="https://github.com/tillywork/tillywork">GitHub repo</a>.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/moshizzlelol"> /u/moshizzlelol </a> <br /> <span><a hre

## Domain, dynamic ip and wireguard
 - [https://www.reddit.com/r/selfhosted/comments/1d5qaxu/domain_dynamic_ip_and_wireguard](https://www.reddit.com/r/selfhosted/comments/1d5qaxu/domain_dynamic_ip_and_wireguard)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T16:04:22+00:00

<!-- SC_OFF --><div class="md"><p>Hi. I bought cheap domain (via Cloudflare). I don't know how to use it. I have a dynamic IP, so I use duckdns.org.</p> <p>I accessed my services via IMMICH.MYDUCKDNSDOMAIN.duckdns.org. Now I am using Wireguard, so I use internal ip:port.</p> <p>My question is. How can I open HTTP and HTTPS ports again, and using my services like IMMICH.MYNEWDOMAIN.COM.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gett13"> /u/gett13 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5qaxu/domain_dynamic_ip_and_wireguard/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5qaxu/domain_dynamic_ip_and_wireguard/">[comments]</a></span>

## iSCSI on Openmediavault
 - [https://www.reddit.com/r/selfhosted/comments/1d5pjpl/iscsi_on_openmediavault](https://www.reddit.com/r/selfhosted/comments/1d5pjpl/iscsi_on_openmediavault)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T15:30:19+00:00

<!-- SC_OFF --><div class="md"><p>So i am trying to use iSCSI in openmediavault and from what i have seen you need to install openmediavault-iscsitarget but i can't find an apt repo, and when using dpkg i can't find the depends either. I don't care if we use something else and i can make a new drive from my proxmox but would like not too as i already have a 200GB for system and a bit more + 1000GB for SMB/iSCSI</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ZealousidealHawk3856"> /u/ZealousidealHawk3856 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5pjpl/iscsi_on_openmediavault/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5pjpl/iscsi_on_openmediavault/">[comments]</a></span>

## VyOS Home Router Beginner question
 - [https://www.reddit.com/r/selfhosted/comments/1d5p8vk/vyos_home_router_beginner_question](https://www.reddit.com/r/selfhosted/comments/1d5p8vk/vyos_home_router_beginner_question)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T15:16:29+00:00

<!-- SC_OFF --><div class="md"><p>Beginner Questions</p> <p>Hi y’all, </p> <p>I’m a bit confused right now as to what hardware I will need to implement a vyos router with a vpn in my network. </p> <p>I currently have a frontier ISP’s modem connected to frontiers Eero mesh system.</p> <p>I have access to a desktop currently installed with vyos 1.5 This desktop has a single Ethernet port.</p> <p>Now, where does vyos server fit in physically? Do I run Ethernet from the isp modem to my desktop and then run another cable back out to the eero for WiFi? (In which case I would need another Ethernet port or a network switch?)</p> <p>Do I need to get my own modem or my own wireless access point to be secure?</p> <p>Any help is appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Gloomy-Effecty"> /u/Gloomy-Effecty </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5p8vk/vyos_home_router_beginner_question/">[link]</a></span> &#

## should i move my personal https services to http on vpn instead?
 - [https://www.reddit.com/r/selfhosted/comments/1d5p60e/should_i_move_my_personal_https_services_to_http](https://www.reddit.com/r/selfhosted/comments/1d5p60e/should_i_move_my_personal_https_services_to_http)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T15:12:57+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I have a few services that are exposed publicly on https. Some are shared with my partner (e.g. jellyfin), but most are strictly for myself (e.g. grafana). All these are subdomains of my domain, with subdomain names that can't easily be guess by humans.</p> <p>I'm in the process of starting to more widely use VPN for my devices and I was thinking, should I move away from https for all my strictly personal services, and serve them via http behind VPN instead?</p> <p>How about ssh, should I stick to exposed ssh, or use ssh behind VPN?</p> <p>Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/comma_girl"> /u/comma_girl </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5p60e/should_i_move_my_personal_https_services_to_http/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5p60e/should_i_move_my_personal_https_services_to_http/">[comments]</a></spa

## Can you use Linux Variables inside Configs like the /etc/samba/smb.conf?
 - [https://www.reddit.com/r/selfhosted/comments/1d5oyjz/can_you_use_linux_variables_inside_configs_like](https://www.reddit.com/r/selfhosted/comments/1d5oyjz/can_you_use_linux_variables_inside_configs_like)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T15:03:33+00:00

<!-- SC_OFF --><div class="md"><p>Pretty much the title, could i do sth like this</p> <p>/etc/samba/smb.conf</p> <p><code>[data]</code><br /> <code>comment = A Fileshare</code><br /> <code>path = /data</code><br /> <code>guest ok = no</code><br /> <code>read only = yes</code><br /> <code>browseable = no</code><br /> <code>valid users = @$HOSTNAME-R @$HOSTNAME-RW</code><br /> <code>invalid users =</code> <br /> <code>read list =</code> <br /> <code>write list = @$HOSTNAME-RW</code></p> <p>The idea would be to automatically create these groups later via LDAP and this would avoid needing to change the config file for each machine.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Pommes254"> /u/Pommes254 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5oyjz/can_you_use_linux_variables_inside_configs_like/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5oyjz/can_you_use_linux_variables_i

## Port forwarding and proxying ACME-DNS
 - [https://www.reddit.com/r/selfhosted/comments/1d5ohdl/port_forwarding_and_proxying_acmedns](https://www.reddit.com/r/selfhosted/comments/1d5ohdl/port_forwarding_and_proxying_acmedns)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T14:41:45+00:00

<!-- SC_OFF --><div class="md"><p>Background:<br /> I want to locally host JOOHOI's acme-dns to do DNS-01 challenges for Let's Encrypt wildcard certs. Using the internet available service is possible, but discouraged in the readme that's posted with the GitHub repo. Also, selfhosting. </p> <p>I'm migrating/upgrading an existing NGINX setup that I don't want to upgrade. It's just cleaner that way. I'm moving from NGINX running on (very little) metal (RPI 4B 2GB.) I'm moving to either NGINX-UI or NPM. My external DNS provider and registrar does not offer a DNS-01 API. I'm strongly averse to switching providers and moving my domains. So, that leads to wanting to do wildcard certs from Let's Encrypt. NGINX-UI (theoretically) can handle the client side of DNS-01 challenges using JOOHOI's acme-dns. I have a static IPv4 IP from my ISP. All my stuff is currently behind an EdgeRouter. </p> <p>Questions:<br /> - I think I should be forwarding port 53 from my router to acme-dns. Is this correct?

## Self Hosted version of FilePass?
 - [https://www.reddit.com/r/selfhosted/comments/1d5nc2w/self_hosted_version_of_filepass](https://www.reddit.com/r/selfhosted/comments/1d5nc2w/self_hosted_version_of_filepass)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T13:45:53+00:00

<!-- SC_OFF --><div class="md"><p>I'm an audio engineer and I am always having to share audio files with clients for them to preview for approval / feedback. Currently I share the project output folder with them via Synology's FileStation but I don't love that experience for the clients (It's slow and just doesn't work well from what I've heard and seen myself).</p> <p>I came across some apps like FilePass and Mixup[.]audio that seem to have a nice workflow. Has anyone come across any Self-Hosted apps that can provide a similar experience where I can allow clients to access their music in an organized way and they can stream or download different versions? I don't really care about paywalls or preventing downloads.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/The_Nimaj"> /u/The_Nimaj </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5nc2w/self_hosted_version_of_filepass/">[link]</a></span> &#32; <span><a href="https://w

## Services outside my home network
 - [https://www.reddit.com/r/selfhosted/comments/1d5n4rj/services_outside_my_home_network](https://www.reddit.com/r/selfhosted/comments/1d5n4rj/services_outside_my_home_network)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T13:35:32+00:00

<!-- SC_OFF --><div class="md"><p>I want to connect to my self-hosted services from outside. I bought a domain on cloud flare (it's not hosted probably as I can't open it) and want to bind it to Nginx Proxy Reverse. However, it doesn't let me go there actually. What should I actually do?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AngelOfDeath6-9"> /u/AngelOfDeath6-9 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5n4rj/services_outside_my_home_network/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5n4rj/services_outside_my_home_network/">[comments]</a></span>

## Help Needed: qBittorrent and Gluetun Docker Setup - Connected Peers but No Upload
 - [https://www.reddit.com/r/selfhosted/comments/1d5n04l/help_needed_qbittorrent_and_gluetun_docker_setup](https://www.reddit.com/r/selfhosted/comments/1d5n04l/help_needed_qbittorrent_and_gluetun_docker_setup)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T13:28:47+00:00

<!-- SC_OFF --><div class="md"><p>I'm having trouble with my qBittorrent setup when using Gluetun as a VPN in Docker. My torrents show connected peers, but there's no upload activity. Below are my current configurations and the steps I've taken so far. Any help or suggestions would be greatly appreciated!</p> <h1>Docker Compose Configuration</h1> <pre><code>version: &quot;3&quot; services: gluetun: image: qmcgaw/gluetun container_name: gluetun cap_add: - NET_ADMIN ports: - 8080:8080 # qbit - 6881:6881 # qbit - 6881:6881/udp # qbit environment: - VPN_SERVICE_PROVIDER=protonvpn - OPENVPN_USER=xxx+pmp - OPENVPN_PASSWORD=xxx - SERVER_COUNTRIES=xxx - VPN_PORT_FORWARDING=on --- # services: qbittorrent: image: container_name: qbittorrent network_mode: &quot;container:gluetun&quot; environment: - PUID=996 - PGID=100 - TZ=Etc/UTC - WEBUI_PORT=8080 volumes: - /xxx/qbit:/config - /xxx/data:/data restart: unless-stoppedhttps://hub.docker.com/r/linuxserver/qbittorrentlscr.io/linuxserver/qbittorren

## TV and Movie Tracker with Jellyfin integration?
 - [https://www.reddit.com/r/selfhosted/comments/1d5mx2e/tv_and_movie_tracker_with_jellyfin_integration](https://www.reddit.com/r/selfhosted/comments/1d5mx2e/tv_and_movie_tracker_with_jellyfin_integration)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T13:24:22+00:00

<!-- SC_OFF --><div class="md"><p>I know there are a few options but which cover this the best:</p> <ul> <li>Nice UI</li> <li>Track what was watched</li> <li>Abilty to browse items that are already in Library</li> <li>Option to rate each</li> <li>Keep a list of the top ranking </li> <li>Each user has a profile via Jellyfin</li> </ul> <p>Something like Serializd and Letterboxd but self hosted?</p> <p>TIA</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RathdrumRain"> /u/RathdrumRain </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5mx2e/tv_and_movie_tracker_with_jellyfin_integration/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5mx2e/tv_and_movie_tracker_with_jellyfin_integration/">[comments]</a></span>

## Nextcloud docker guides
 - [https://www.reddit.com/r/selfhosted/comments/1d5mhbo/nextcloud_docker_guides](https://www.reddit.com/r/selfhosted/comments/1d5mhbo/nextcloud_docker_guides)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T13:01:36+00:00

<!-- SC_OFF --><div class="md"><p>Does anyone know of a decent setup guide for Nextcloud on docker? I'm running a reverse proxy through Traefik and couldn't quite fathom how this is supposed to work when looking through their own documentation. The settings to use an alternative storage location were a bit confusing as well.</p> <p>I had a look <a href="https://www.smarthomebeginner.com/traefik-docker-nextcloud/">at this</a> one but the guide seems to tie you into this guys bespoke configuration where you need to pay money to access some paywalled elements.</p> <p>Should I even bother with it and just use other individual selfhosted apps to achieve the same things? I like the idea of an AIO but maybe it has become too bloated and complicated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Smittyuk"> /u/Smittyuk </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5mhbo/nextcloud_docker_guides/">[link]</a></span> &#32; <span>

## Cloudflare domain & privacy: Use built-in security features or go firewall-route?
 - [https://www.reddit.com/r/selfhosted/comments/1d5lve6/cloudflare_domain_privacy_use_builtin_security](https://www.reddit.com/r/selfhosted/comments/1d5lve6/cloudflare_domain_privacy_use_builtin_security)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T12:27:04+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I bought a domain on cloudflare so I can put some of my self-hosted services on the internet. I run NGINX Proxy Manager on my Proxmox machine, have the Cloudflare certificates setup, works so far.</p> <p>Of course, the reason I'm self-hosting is for increased privacy and security, among other benefits. Now I'm wondering: By using some of Cloudflares built-in security features, am I giving up on privacy?</p> <p>I don't use Cloudflare-Tunnel. But I do use things like geo-blocking rules and DDoS-protection, as well as their HTTPS-Certificates for my subdomains. I know there are ongoing discussions here about Cloudflare and how much of your traffic they can see. I want to limit this as much as possible.</p> <p>I could turn everything off in the Cloudflare dashboard and instead use an OPNsense router/firewall, but having tried it, I find it quite challenging. Alternatively, I'm looking at the Unifi Cloud Gateway Ultra, as I already have a U6+ ac

## Exposing OIDC - Web Login?
 - [https://www.reddit.com/r/selfhosted/comments/1d5l2vk/exposing_oidc_web_login](https://www.reddit.com/r/selfhosted/comments/1d5l2vk/exposing_oidc_web_login)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T11:40:15+00:00

<!-- SC_OFF --><div class="md"><p>I've successfully managed to get a web based login to immich instance using my self hosted Keycloak OIDC.</p> <p>So I have exposed my immich server at <a href="http://photos.mydomain.org">photos.mydomain.org</a> which I am fine with. But for OIDC authentication to work I also have to expose <a href="http://keycloak.mydomain.org">keycloak.mydomain.org</a> which I wasn't necessarily wanting to do.</p> <p>These are both hosted via cloudflare tunnels for IP masking so I'm not toooooo worried, but I wanted to see if this is best practice, or have I implemented it incorrectly?</p> <p>Going to the keycloak domain via web just shows &quot;Loading Admin UI&quot; and times out.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ErraticLitmus"> /u/ErraticLitmus </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5l2vk/exposing_oidc_web_login/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/

## How to make git through SSH work without sacrificing the possibility of SSH into Docker?
 - [https://www.reddit.com/r/selfhosted/comments/1d5l2e5/how_to_make_git_through_ssh_work_without](https://www.reddit.com/r/selfhosted/comments/1d5l2e5/how_to_make_git_through_ssh_work_without)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T11:39:19+00:00

<!-- SC_OFF --><div class="md"><p>So I have a stack that consists of the following:</p> <ul> <li>Sophos XG Home firewall as a router running on bare metal</li> <li>AdGuard Home as a DNS server running as LXC</li> <li>Nginx Proxy Manager as reverse proxy running on Docker</li> <li>Gitea as git server running on Docker</li> </ul> <p>I cannot really get it to work the way that I want it to, that is:</p> <ul> <li>ability to access the web UI of Gitea through domain name (e.g. <a href="https://git.example.com">https://git.example.com</a>)</li> <li>ability to check out from git using HTTPS (e.g. <a href="https://git.example.com">https://git.example.com</a>)</li> <li>ability to check out from git using SSH (e.g. [<a href="mailto:git@git.example.com">git@git.example.com</a>](mailto:<a href="mailto:git@git.example.com">git@git.example.com</a>))</li> <li>ability to SSH into docker (e.g. <a href="mailto:root@192.168.0.10">root@192.168.0.10</a>)</li> <li>ability to reverse proxy to other services

## Issues with Rclone and Immich
 - [https://www.reddit.com/r/selfhosted/comments/1d5l2ah/issues_with_rclone_and_immich](https://www.reddit.com/r/selfhosted/comments/1d5l2ah/issues_with_rclone_and_immich)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T11:39:08+00:00

<!-- SC_OFF --><div class="md"><p>So basically I have rclone mount setup using this docker container (<a href="https://hub.docker.com/r/wiserain/rclone/tags">https://hub.docker.com/r/wiserain/rclone/tags</a>) however I'm having issues with immich because when my system restarts, the immich container starts earlier than my Rclone container causing immich to get confused when it cant find my mount and as a result store on my internal storage instead of my remote storage.</p> <p>What could I do to be able to fix this issue as I keep on uploading files to my local storage instead of my remote storage. Also, the reason why I setup Rclone using docker is because I couldn't make Rclone start at boot using systemd no matter what I did hence had to use docker. Any help would be appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/borkode"> /u/borkode </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5l2ah/issues_with_rclone

## Getting started
 - [https://www.reddit.com/r/selfhosted/comments/1d5kvjr/getting_started](https://www.reddit.com/r/selfhosted/comments/1d5kvjr/getting_started)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T11:27:10+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>For a while now i have a need to own my own stuff mode independently. I'm fond of making tech work for me, loved it to have the lights turn on and off when i get home etc. </p> <p>I'm 43, behind the development of new things like hypervisors and how those things hook into each other with redundancy etc etc. But, i'm trying my best. got some things running'ish. But it wasnt working as intended. I'm aiming for a 3-2-1 setup. </p> <p>What i have might not be optimal, but i hope its fine enough to start with.<br /> I have a HP Prodesk 600 G2 Mini, i5 core, 32 gb memory, 256gb ssd and a 2tb nvme drive.</p> <p>What i would like to achieve:<br /> A proxmox setup, with multiple drives (mirrored for redundancy). Running:<br /> Truenas for storage/NAS functions.<br /> VM's to host my local media (plex/jellyfin, i have not decided), photo-backup, home-assistant).<br /> I'm not a power-users. I'm fine with 1gb networking, read/write speeds are nice,

## Raspberry Pi 5 as a primary immich and jellyfin server
 - [https://www.reddit.com/r/selfhosted/comments/1d5k4iq/raspberry_pi_5_as_a_primary_immich_and_jellyfin](https://www.reddit.com/r/selfhosted/comments/1d5k4iq/raspberry_pi_5_as_a_primary_immich_and_jellyfin)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T10:35:37+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I am looking to setup a immich and jellyfin server, I am considering a Raspberry Pi 5 and an nvme hat. </p> <p>My main requirements is for it to be silent and power efficient. That it is quite widely available, cheap(ish) and relatively plug and play, is an added <em>nice to have</em>.</p> <p>Some of my concerns are that the rpi 5 is advised to be actively cooled and whether it suffices in terms of performance (I don't think that there will be more than 3 concurrent light users: my bar is &quot;I won't hate myself for using it&quot; - as opposed to my experiments with jellyfin on a raspberry pi 3). </p> <p>Does anyone have any experience/thoughts that they could share?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/stringlesskite"> /u/stringlesskite </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5k4iq/raspberry_pi_5_as_a_primary_immich_and_jellyfin/">[link]</a></span> &#

## Docker Security with Macvlan and Bridge Networking
 - [https://www.reddit.com/r/selfhosted/comments/1d5j9v4/docker_security_with_macvlan_and_bridge_networking](https://www.reddit.com/r/selfhosted/comments/1d5j9v4/docker_security_with_macvlan_and_bridge_networking)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T09:33:24+00:00

<!-- SC_OFF --><div class="md"><p>I'm transitioning services from LXCs and VMs to Docker (because of ease of deployment and migration), and I've encountered some security challenges due to the multiple VLANs in my environment. I have about 20 VLANs.</p> <p>Using bridge networks in Docker is quite secure, as each container is isolated. However, I prefer to filter my services through my main firewall using Suricata. Suricata operates based on IP addresses, so if one container gets infected and starts DDoSing the outside world, Suricata will block that host. Because containers in bridge mode share the same host IP, Suricata will block all containers, making all services unavailable.</p> <p>To mitigate this, I considered using Macvlan networks. The problem is that Docker does not support external DHCP, meaning I have to assign static IPs to each container. Additionally, I must assign static IPs in my firewall (as dummy entries to track consumed IPs), which means double the work. There wer

## Git commands (clone, push) hang with GitLab CE
 - [https://www.reddit.com/r/selfhosted/comments/1d5iomr/git_commands_clone_push_hang_with_gitlab_ce](https://www.reddit.com/r/selfhosted/comments/1d5iomr/git_commands_clone_push_hang_with_gitlab_ce)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T08:49:34+00:00

<!-- SC_OFF --><div class="md"><p>I've been troubleshooting this for a few days now so I hope one of you can help me T_T. Here's my docker-compose.yml file for gitlab</p> <pre><code>services: gitlab: image: gitlab/gitlab-ce:latest hostname: 'localhost' environment: GITLAB_OMNIBUS_CONFIG: | external_url 'http://localhost' gitlab_rails['gitlab_shell_ssh_port'] = 2224 ports: - '2224:22' volumes: - gitlab-config:/etc/gitlab - gitlab-logs:/var/log/gitlab - gitlab-data:/var/opt/gitlab - type: tmpfs target: /dev/shm tmpfs: size: 4294967296 # 4 GiB networks: - gitlab-network - reverse-proxy-network networks: gitlab-network: reverse-proxy-network: external: true </code></pre> <p>It's behind a Caddy reverse-proxy (in Docker, too). Here's the Caddyfile:</p> <pre><code>localhost { reverse_proxy gitlab:80 } </code></pre> <p>When I run &quot;GIT_TRACE=1 GIT_CURL_VERBOSE=1 git clone git@localhost:2224/dakeiz/home-services.git&quot; here are the logs:</p> <pre><code>Cloning into 'home-services'... 10

## Proxmox on Hetzner Dedicated - Need help with networking
 - [https://www.reddit.com/r/selfhosted/comments/1d5hqpd/proxmox_on_hetzner_dedicated_need_help_with](https://www.reddit.com/r/selfhosted/comments/1d5hqpd/proxmox_on_hetzner_dedicated_need_help_with)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T07:40:27+00:00

<!-- SC_OFF --><div class="md"><p>So, I got a Hetzner dedicated server a few months ago and so far, I have been running my services on bare metal. Recently, I decided to try and install Proxmox on it to keep everything organized in their separate VMs and more importantly, make backups easier for me.</p> <p>I learned how to install Proxmox last week and got everything up and running on my tiny home lab without many issues.</p> <p>Now, the Hetzner server only comes with a single IP address, and the way Proxmox works (based on my understanding), it assigns a new IP address to each VM or LXC. This wasn't an issue when I was tinkering with it on my home lab locally however, I'm unable to replicate the network configuration on the Hetzner Server.</p> <p>I followed <a href="https://www.youtube.com/watch?v=zMVhl9GtX_0">this tutorial</a> on YouTube to configure the network setup. So, following this tutorial should essentially give new local IP addresses (192.168.x.x) to my VMs and LXCs and it 

## Getting recipes into mealie?
 - [https://www.reddit.com/r/selfhosted/comments/1d5hntx/getting_recipes_into_mealie](https://www.reddit.com/r/selfhosted/comments/1d5hntx/getting_recipes_into_mealie)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T07:34:27+00:00

<!-- SC_OFF --><div class="md"><p>For those of you that use tools like mealie and tandor for your recipe management. Do you have a particular tool or workflow for getting recipe from paper / cards / cook books into mealie?</p> <p>Best i have so far is using the ocr from my phone to take pictures and extract the text but it's not a great set up. </p> <p>Any advice?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/harperthomas"> /u/harperthomas </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5hntx/getting_recipes_into_mealie/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5hntx/getting_recipes_into_mealie/">[comments]</a></span>

## Host local mp4 and stream to iOS client
 - [https://www.reddit.com/r/selfhosted/comments/1d5h9y1/host_local_mp4_and_stream_to_ios_client](https://www.reddit.com/r/selfhosted/comments/1d5h9y1/host_local_mp4_and_stream_to_ios_client)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T07:07:04+00:00

<!-- SC_OFF --><div class="md"><p>Is it possible to stream MP4 files from my server to an iOS client? I am asking this because I want to have a minimal selection of YouTube videos that my child can watch. What would be the best set up on my server and on my iPhone?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jeroenishere12"> /u/jeroenishere12 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5h9y1/host_local_mp4_and_stream_to_ios_client/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5h9y1/host_local_mp4_and_stream_to_ios_client/">[comments]</a></span>

## Where do featurettes go in Plex?
 - [https://www.reddit.com/r/selfhosted/comments/1d5gvu2/where_do_featurettes_go_in_plex](https://www.reddit.com/r/selfhosted/comments/1d5gvu2/where_do_featurettes_go_in_plex)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T06:40:01+00:00

<!-- SC_OFF --><div class="md"><p>If I download a movie, for example, Civil War from 2024. It shows up perfectly on Plex, but I check the actual download and it is 1 movie for 2GB and then a separate folder with featurettes and I wonder where that shows on Plex? </p> <p>Because I have it in the same folder.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Burlewood"> /u/Burlewood </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5gvu2/where_do_featurettes_go_in_plex/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5gvu2/where_do_featurettes_go_in_plex/">[comments]</a></span>

## IPv6 hosting resources?
 - [https://www.reddit.com/r/selfhosted/comments/1d5gkhd/ipv6_hosting_resources](https://www.reddit.com/r/selfhosted/comments/1d5gkhd/ipv6_hosting_resources)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T06:18:53+00:00

<!-- SC_OFF --><div class="md"><p>My ISP has finally finished their network upgrade to IPv6, got my local network devices getting g their addresses and was wondering if anyone had some good resources/documentation on adding IPv6 to my self-hosted stuff, DNS, domains etc…</p> <p>As I understand it, the v6 goes directly to device so firewalls and the like are gonna need to be extra careful, so basically I’m looking for a “checklist” of things to setup and configure to make sure that I don’t open the wider network up inadvertently.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/xionuk"> /u/xionuk </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5gkhd/ipv6_hosting_resources/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5gkhd/ipv6_hosting_resources/">[comments]</a></span>

## Suggestions on what to mess around with
 - [https://www.reddit.com/r/selfhosted/comments/1d5erf7/suggestions_on_what_to_mess_around_with](https://www.reddit.com/r/selfhosted/comments/1d5erf7/suggestions_on_what_to_mess_around_with)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T04:24:15+00:00

<!-- SC_OFF --><div class="md"><p>I currently have a physical server that I've been working on as a side project. I used to host some game servers, but haven't been feeling like playing much lately so currently I have a ubuntu computer running Nextcloud and cloudflared exclusively with </p> <p>CPU: Xeon E5-2680 V4</p> <p>GPU: Nvidia Quadro K2200</p> <p>RAM: 64gb 61.5 remaining after nextcloud/cloudflared/ubuntu</p> <p>STORAGE: 500gb SSD + 2 terabyte hdd.</p> <p>Feels like a true waste of potential lol.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/EtherealSpoon"> /u/EtherealSpoon </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5erf7/suggestions_on_what_to_mess_around_with/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5erf7/suggestions_on_what_to_mess_around_with/">[comments]</a></span>

## Anyone know of a selfhosted rest-api mail server?
 - [https://www.reddit.com/r/selfhosted/comments/1d5dlb1/anyone_know_of_a_selfhosted_restapi_mail_server](https://www.reddit.com/r/selfhosted/comments/1d5dlb1/anyone_know_of_a_selfhosted_restapi_mail_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T03:17:15+00:00

<!-- SC_OFF --><div class="md"><p>Anyone know of any selfhosted restapi mailservers, something like resend? Have VPS and don't mind dealing with DKMS and usual mail goodies for sending, but i'd like to be able to use it via rest instead of pop. </p> <p>Super bonus points if you know one with a decent UI/UX</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lordpuddingcup"> /u/lordpuddingcup </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5dlb1/anyone_know_of_a_selfhosted_restapi_mail_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5dlb1/anyone_know_of_a_selfhosted_restapi_mail_server/">[comments]</a></span>

## Regarding Backups
 - [https://www.reddit.com/r/selfhosted/comments/1d5ctzx/regarding_backups](https://www.reddit.com/r/selfhosted/comments/1d5ctzx/regarding_backups)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T02:34:04+00:00

<!-- SC_OFF --><div class="md"><p>Recently I have seen many posts asking about backups and best self hosted software to backup docker/full machines, then mostly file level backups get recommended for backing up files to another location.<br /> For me, this is not a backup, rather a file sync ...</p> <p>I don't think this is the right approach to backups and data security.</p> <p>Unfortunately for baremetal Linux machines there are not many backup methods that can do what most Windows backup solutions can with VSS writer on Windows (server).</p> <p>So what is a better fit solution for Linux? I have been using Veeam agent for Linux for about two years now (basically since the release of the Linux agent) and it has been a absolute delight.</p> <p>I had to recover several deleted files from my backups and once recover a full machine, everything worked absolutely flawlessly.</p> <p>The agent is basically a Kernel module which can take snapshots and backup your machine in the background.<br

## Received free ReadyNAS Ultra 4. Looking for direction?
 - [https://www.reddit.com/r/selfhosted/comments/1d5cglo/received_free_readynas_ultra_4_looking_for](https://www.reddit.com/r/selfhosted/comments/1d5cglo/received_free_readynas_ultra_4_looking_for)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T02:13:04+00:00

<!-- SC_OFF --><div class="md"><p>Total noob here. </p> <p>I recently received a free ReadyNAS ultra 4 with 4 2TB hard drives. I know this is somewhat dated hardware, but I’m wondering if it will serve my needs for hosting a Postgres Database and a web-scraping app.</p> <p>Can anyone refer me where to begin my research? Will a container suffice? Or should I look into a VM. Can i stick a container on a VM? </p> <p>No idea where to get started. Can anyone point me in the right direction?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/suitupyo"> /u/suitupyo </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5cglo/received_free_readynas_ultra_4_looking_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5cglo/received_free_readynas_ultra_4_looking_for/">[comments]</a></span>

## Synology's Built-in Reverse Proxy. Am I doing it wrong?
 - [https://www.reddit.com/r/selfhosted/comments/1d5bvg5/synologys_builtin_reverse_proxy_am_i_doing_it](https://www.reddit.com/r/selfhosted/comments/1d5bvg5/synologys_builtin_reverse_proxy_am_i_doing_it)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T01:40:32+00:00

<!-- SC_OFF --><div class="md"><p>I own a Synology NAS that I use for storage only. I also have a NUC where I run all my containers. I currently access some of those containers outside home by using Synology's Reverse Proxy but not directly. Instead, I'm running a virtual DSM (Synology's OS) within my NAS and on said DSM, I have my reverse proxy set up. Why this approach? On my router I'm forwarding that virtual DSM's port. Am I overdoing things? Can I just manage everything on my NAS instead? Which option is safer? Thank you I'm advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/5197799"> /u/5197799 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5bvg5/synologys_builtin_reverse_proxy_am_i_doing_it/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5bvg5/synologys_builtin_reverse_proxy_am_i_doing_it/">[comments]</a></span>

## Stream Music - iOS Navidrome App - Album organisation ?
 - [https://www.reddit.com/r/selfhosted/comments/1d5bkod/stream_music_ios_navidrome_app_album_organisation](https://www.reddit.com/r/selfhosted/comments/1d5bkod/stream_music_ios_navidrome_app_album_organisation)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T01:24:28+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1d5bkod/stream_music_ios_navidrome_app_album_organisation/"> <img alt="Stream Music - iOS Navidrome App - Album organisation ?" src="https://a.thumbs.redditmedia.com/657WalFU2z_MXRzoilhf0kKwIyaQbpFCLO_p9pFZLD8.jpg" title="Stream Music - iOS Navidrome App - Album organisation ?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I have been trying alsorts of different client apps on iOS trying to find the perfect fit for the app on my iPhone.</p> <p>So far my top 3 are: - Stream Music - Amperfy - Manet</p> <p>Stream Music is miles ahead though I think. I love the UI. It's got tonnes of good features like scanning the liked songs on launch and downloading new tracks.</p> <p>It definitely needs Siri integration though, which it doesn't have at all. that is one thing I don't like compared to Amperfy which has amazing Siri integration. Hopefully that comes soon.</p> <p>I would also love if there was an album art icon b

## Travel Media Server
 - [https://www.reddit.com/r/selfhosted/comments/1d5bkf7/travel_media_server](https://www.reddit.com/r/selfhosted/comments/1d5bkf7/travel_media_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T01:24:02+00:00

<!-- SC_OFF --><div class="md"><p>I'm looking for suggestions on how to make a portable media server that has the capability to connect individually and stream to 5 tablets. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/selacius"> /u/selacius </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5bkf7/travel_media_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1d5bkf7/travel_media_server/">[comments]</a></span>

## Is this a reasonable approach to sharing smb folders to docker?
 - [https://www.reddit.com/r/selfhosted/comments/1d5b1ih/is_this_a_reasonable_approach_to_sharing_smb](https://www.reddit.com/r/selfhosted/comments/1d5b1ih/is_this_a_reasonable_approach_to_sharing_smb)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T00:55:47+00:00

<!-- SC_OFF --><div class="md"><p>I am sure there are better ways, and I couldn't finangle it thru skill or experience or knowledge.</p> <p>So this is what I did, after much much trial and error, mostly error.</p> <p>I shared the folder from my windows 10 pc, to the bare metal of the Raspberry Pi where I do all my self hosting.</p> <p>And i got that to work.</p> <p>Because adding a CIFS share to Portainer requires the windows password, which I have no idea what it is, since I only use local accounts.</p> <p>The tricky part for me, and I still do not got, was attaching that bare metal share to the portainer/docker volumes, and then adding those volumes to the needed containers.</p> <p>There is no tool or way to get my windows password without resetting it, and there is no way I will ever do that.</p> <p>So I have to have a way to share the volumes without doing that.</p> <p>I have tried vigorously using nirsoft's password viewer and it can not find any passwords.</p> <p>Although I prob

## Routing individual VM traffic through Wireguard - Help Needed
 - [https://www.reddit.com/r/selfhosted/comments/1d5b102/routing_individual_vm_traffic_through_wireguard](https://www.reddit.com/r/selfhosted/comments/1d5b102/routing_individual_vm_traffic_through_wireguard)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T00:55:04+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1d5b102/routing_individual_vm_traffic_through_wireguard/"> <img alt="Routing individual VM traffic through Wireguard - Help Needed" src="https://b.thumbs.redditmedia.com/T-lGkWjmXDcAJ7AdFg53pl5kln09n6XwFvLGew926Qo.jpg" title="Routing individual VM traffic through Wireguard - Help Needed" /> </a> </td><td> <!-- SC_OFF --><div class="md"><h1>TL;DR:</h1> <blockquote> <p>I essentially want the game server Proxmox VM's traffic to be &quot;masked&quot; by the AWS Lightsail VPS's IP address through Wireguard, and for other services in separate VM's to be able to reliably use the unmasked public IPv4 address provided by my ISP. The idea was to create an isolated VM that any and everything I deploy on it would be masked by the VPS's IP address through a Wireguard tunnel. Allowing players/friends/family to connect to the game server through the AWS VPS's IP address, hiding my own public IP address.</p> </blockquote> <p>As th

## issues with Viewtube AIO docker image?
 - [https://www.reddit.com/r/selfhosted/comments/1d5b0ua/issues_with_viewtube_aio_docker_image](https://www.reddit.com/r/selfhosted/comments/1d5b0ua/issues_with_viewtube_aio_docker_image)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-06-01T00:54:50+00:00

<!-- SC_OFF --><div class="md"><p>I'm having issues getting the viewtube AIO working, and I'm not sure whats going on.</p> <p>If I enter the container in interactive mode and manually start the services, this is what I get:</p> <hr /> <p>296:M 28 May 2024 19:36:00.044 * Ready to accept connections [ViewTube] Info 5/28/2024, 7:36:02 PM Starting with single node [ViewTube] Info 5/28/2024, 7:36:02 PM Loaded configuration from /data/config.json [ViewTube] Info 5/28/2024, 7:40:56 PM [NestFactory] Starting Nest application... [ViewTube] Info 5/28/2024, 7:40:56 PM [InstanceLoader] MongooseModule dependencies initialized [ViewTube] Info 5/28/2024, 7:40:56 PM [InstanceLoader] JwtModule dependencies initialized [ViewTube] Info 5/28/2024, 7:40:56 PM [InstanceLoader] ConfigHostModule dependencies initialized [ViewTube] Info 5/28/2024, 7:40:56 PM [InstanceLoader] NuxtModule dependencies initialized [ViewTube] Info 5/28/2024, 7:40:56 PM [InstanceLoader] DiscoveryModule dependencies initialized [Vie

