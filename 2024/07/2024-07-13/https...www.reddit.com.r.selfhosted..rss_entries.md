# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## How do you manage sensitive information in your environment?
 - [https://www.reddit.com/r/selfhosted/comments/1e2mt81/how_do_you_manage_sensitive_information_in_your](https://www.reddit.com/r/selfhosted/comments/1e2mt81/how_do_you_manage_sensitive_information_in_your)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T22:35:25+00:00

<!-- SC_OFF --><div class="md"><p>Context: I'm creating my entire environment via Docker compose, and a lot of data like passwords and emails are directly in the files.</p> <p>I'm a weekend programmer, I understand how to use .env files, but when it comes to a whole stack of personal applications, How do you deal with &quot;confidential&quot; information, such as passwords, etc., imagine that the use of this is not public, but if I want to share a compose with a friend, I have to be careful not to send it a password.</p> <p>Yes, I know that passwords have to be unique, but let's face it, do you have 300 passwords for the 300 services you use in your life? There's always that old childhood password that may not be in the most important services, but it's half of what I used at the beginning of the internet </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ogiordane"> /u/ogiordane </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/commen

## VPN Server Hosting or VPN Remote Connection ?
 - [https://www.reddit.com/r/selfhosted/comments/1e2mp6c/vpn_server_hosting_or_vpn_remote_connection](https://www.reddit.com/r/selfhosted/comments/1e2mp6c/vpn_server_hosting_or_vpn_remote_connection)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T22:30:35+00:00

<!-- SC_OFF --><div class="md"><p>I wasn't sure how to properly title my post. So in my Homelab LAN I have Proxmox VE OS Desktop and it's hosting Docker LXC running with a handful of containers.</p> <p>I installed qbittorent in my Docker LXC and it works great, I am looking at installing/configuring qbittorent connection in a VPN kill-switch mode. Now this is the dilema I am having, the VPN solutions that I am seeing revolve around me hosting a VPN Server in my Homelab LAN anr connecting through that.</p> <p>My issue with that, is that wouldn't that geographically expose my IP address, even if it's through the VPN? I was always under the impression that VPNs should be physically remote from where you're actually connecting from?</p> <p>Maybe, I am wrong in my understanding or lacking in knowledge of security and VPN architecture.</p> <p>As an FYI, far as me accessing my Homelab LAN remotely, I already do it via my Synology RT2600AC Router VPN Plus App, however this is really only for 

## How to UDP tunnel for a Minecraft server for free
 - [https://www.reddit.com/r/selfhosted/comments/1e2m83e/how_to_udp_tunnel_for_a_minecraft_server_for_free](https://www.reddit.com/r/selfhosted/comments/1e2m83e/how_to_udp_tunnel_for_a_minecraft_server_for_free)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T22:09:51+00:00

<!-- SC_OFF --><div class="md"><p>I was trying to make a Minecraft server accessible for all my friends to join. For those on Java, I used ngrok to make a TCP tunnel, which worked perfectly. However, for those on bedrock, I have to use udp. I found that ngrok doesn't seem to support udp tunneling. What should I use for this? Would frp or rathole work for this application? Thank you to anyone who helps me out!</p> <p>Edit: I should have also mentioned that as the UDP tunnel will be used for PlayStation users, it needs to be done through something that doesn't require them to download anything.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Paravel-"> /u/Paravel- </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2m83e/how_to_udp_tunnel_for_a_minecraft_server_for_free/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2m83e/how_to_udp_tunnel_for_a_minecraft_server_for_free/">[comments]</a

## Options for home cameras
 - [https://www.reddit.com/r/selfhosted/comments/1e2liwm/options_for_home_cameras](https://www.reddit.com/r/selfhosted/comments/1e2liwm/options_for_home_cameras)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T21:38:43+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I am looking to possibly change my current home camera setup as we aren’t able to get a certain feature we want which I will explain.</p> <p>We currently have Google cameras in the home which we have liked due to the general ease of use for viewing outside of the home. We recently bought a Reolink camera to test out because the Google camera was cutting out at night when we were using it as a baby monitor. The Reolink has worked great for that case and stays open through the night. Recently, we had another addition to the family and are wanting to have multiple cameras which output audio from both cameras at the same time. The Reolink has the option to select but not outputting both audios. </p> <p>I am quite a bit tech savvy but haven’t fully stepped into doing any self hosting although I have been lurking on this sub for a while. I am wondering if Home Assistant or something similar could do what I want. I have a raspberry pi 

## CalDAV/CardDAV with SSO
 - [https://www.reddit.com/r/selfhosted/comments/1e2l12s/caldavcarddav_with_sso](https://www.reddit.com/r/selfhosted/comments/1e2l12s/caldavcarddav_with_sso)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T21:16:34+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone!</p> <p>Ive been running Nextcloud/owncloud for almost 10 years and I am pretty happy with it overall. In the last few years quite a lot of people are relying on this service and it turns out CalDAV and CardDAV are the most important ones. That is why I would like to pull those Services out of my nextcloud stack and provide them via a specialised solution. The Idea is: Nextcloud maintainance should not impact those critical services.</p> <p>This is why I am looking for a standalone pice of software, that provides CalDAV/CardDAV. I would also like to have some form of SSO. preferably not LDAP.</p> <p>I found Baikal, which does not seem to have SSO at all and Radicale which has a LDAP plugin. </p> <p>I amhappy about any recommendation I can get.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MarcSN311"> /u/MarcSN311 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2l12s/cald

## What are you using to remote into your home network to support your selfhosted environment when away from home
 - [https://www.reddit.com/r/selfhosted/comments/1e2k14g/what_are_you_using_to_remote_into_your_home](https://www.reddit.com/r/selfhosted/comments/1e2k14g/what_are_you_using_to_remote_into_your_home)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T20:31:23+00:00

<!-- SC_OFF --><div class="md"><p>I've been fighting with this off and on and now I'm ready to take the plunge, but I'm still not finding any really good solutions that offer what I need. I have a simple network and set of devices and I just want to be able to connect to them, check the health, do some support when on business trips to fix things for the wife and that sort of stuff. In some cases I'd like to be able to restart systems.</p> <p>So what are you using to support this capability ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/isitallfromchina"> /u/isitallfromchina </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2k14g/what_are_you_using_to_remote_into_your_home/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2k14g/what_are_you_using_to_remote_into_your_home/">[comments]</a></span>

## Community based SmartDNS?
 - [https://www.reddit.com/r/selfhosted/comments/1e2jmz6/community_based_smartdns](https://www.reddit.com/r/selfhosted/comments/1e2jmz6/community_based_smartdns)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T20:13:52+00:00

<!-- SC_OFF --><div class="md"><p>Hey folks did you know about one?</p> <p><a href="https://www.reddit.com/r/SmartDNS/s/Jzg86EiPNH">https://www.reddit.com/r/SmartDNS/s/Jzg86EiPNH</a></p> <p>Thx</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mc-doubleyou"> /u/mc-doubleyou </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2jmz6/community_based_smartdns/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2jmz6/community_based_smartdns/">[comments]</a></span>

## Seperate Backup Jobs
 - [https://www.reddit.com/r/selfhosted/comments/1e2ihe5/seperate_backup_jobs](https://www.reddit.com/r/selfhosted/comments/1e2ihe5/seperate_backup_jobs)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T19:22:33+00:00

<!-- SC_OFF --><div class="md"><p>Hello there! I backup all my services with Duplicati and send it to my hetzner storage over SFTP. Everything fine so far. After a little redesign of my Immich backup logic, I had the idea to separate the Backup jobs of immich and in general. One for the Data folder and the docker config files and one job for the Database. Is it a good Idea to separate these things? How are you doing it? One job per Services or like my Idea with multiple jobs per service? I hope you understand what I mean. Thank you for your help.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SheepyTrevor2"> /u/SheepyTrevor2 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2ihe5/seperate_backup_jobs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2ihe5/seperate_backup_jobs/">[comments]</a></span>

## Managing my kids android devices
 - [https://www.reddit.com/r/selfhosted/comments/1e2i7b3/managing_my_kids_android_devices](https://www.reddit.com/r/selfhosted/comments/1e2i7b3/managing_my_kids_android_devices)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T19:10:16+00:00

<!-- SC_OFF --><div class="md"><p>Managing android devices for family members</p> <p>I have two kids who just got their first tablets (android). </p> <p>I'm also a sysadmin and a homelabber so I'd love to bring some of that into the mix. </p> <p>Is there a better way to manage my kids devices than the default family link by Google? Preferably something open source and self hosted. </p> <p>I'm thinking tailscale, squid, and pihole to manage browsing and get rid of ads. Nextcloud for file backups. But that doesn't address device management. I'd like to be able to install apps remotely which I don't see a way to do with family link. </p> <p>Someone who's in the same boat and has a overly complicated and over engineered solution to this &quot;problem&quot;? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/_Old_Greg"> /u/_Old_Greg </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2i7b3/managing_my_kids_android_devices/">[link]<

## Plex Docker Container
 - [https://www.reddit.com/r/selfhosted/comments/1e2hiz1/plex_docker_container](https://www.reddit.com/r/selfhosted/comments/1e2hiz1/plex_docker_container)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T18:41:14+00:00

<!-- SC_OFF --><div class="md"><p>I was running my Plex container on an old mini PC running Ubuntu and it recently died. I was able to grab the original docker compose file and Library folder from the old hard drive and transfer it over to the new system, which is running Fedora server. </p> <p>I modified the docker-compose.yaml for the new IP addresses and mappings for the drives, so that part is correct, the problem though is that now I get nothing on the default port 32400 on the localhost. I've tried explicitly mapping this port inside the compose file, but still don't see anything. </p> <p>Am I missing something?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/elder242"> /u/elder242 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2hiz1/plex_docker_container/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2hiz1/plex_docker_container/">[comments]</a></span>

## Windows XP remote gaming
 - [https://www.reddit.com/r/selfhosted/comments/1e2hdfp/windows_xp_remote_gaming](https://www.reddit.com/r/selfhosted/comments/1e2hdfp/windows_xp_remote_gaming)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T18:34:36+00:00

<!-- SC_OFF --><div class="md"><p>For reasons, I want to setup a windows XP vm to RDP into and play old school games remotely, and offer this to friends with access to my vpn.</p> <p>I have a legit XP Home license and &quot;hacked&quot; it, following some guide to be a professional version so I could use RDP, as it was basically impossible to setup VNC or similar on this old software being XP home.</p> <p>Now I can remote in and even play (less demanding) games, but audio is choppy and the only possible solution I've found was to edit some group policies through gpedit.msc, which is missing on my install, as it's actually XP Home and gpedit.msc only comes with professional. And all guides on getting gpedit in other ways are so old, that none of the download links in those are working anymore.</p> <p>Now I'm wondering, what would be the best workaround. I was thinking about these and would like to hear how you got this sort of thing working smoothly for yourself.</p> <ol> <li>get a cop

## I love Bookstack
 - [https://www.reddit.com/r/selfhosted/comments/1e2hbyw/i_love_bookstack](https://www.reddit.com/r/selfhosted/comments/1e2hbyw/i_love_bookstack)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T18:32:42+00:00

<!-- SC_OFF --><div class="md"><p>Coming from alternative &quot;documentation&quot; tools like Confluence, Wiki(anything), text files, pieces of paper, smoke signals, whiteboards, and others... I need to share that I love Bookstack.</p> <p>I already knew I would, but now that I'm actually using it properly, for myself (my own IT biz) to write documentation, I need to share that it's awesome and I love it.</p> <p>I have it connected to my (Samba) AD environment for central auth, it pulls my user avatar in (glee), and is quite zippy!</p> <p>Most recently I spent far too much time writing the documentation for joining a PVE Node to an existing cluster for one of my clients environments. I spent so much time because I wanted to write seriously incredible documentation (internal in this case, not for the client to see).</p> <p>So many sane conveniences, I honestly am spoiling some nice surprises if I tell you too much.</p> <p>Anyways, it's super easy to spin up, whether it's in a VM, or do

## Issue with an insecure internal API call
 - [https://www.reddit.com/r/selfhosted/comments/1e2grsq/issue_with_an_insecure_internal_api_call](https://www.reddit.com/r/selfhosted/comments/1e2grsq/issue_with_an_insecure_internal_api_call)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T18:07:46+00:00

<!-- SC_OFF --><div class="md"><p>I created a web app for a research project that I’ve been working on. I decided to host the app in Docker on my home server and used Caddy as both the web server and a reverse proxy for TLS. In addition, the web app makes a POST request to a Python server, also running in a Docker container. My issue is that the Python server is not behind a reverse proxy, and my web browser is blocking the API call for “insecure content.” Is there anything I can do, maybe with Docker networking, to keep the Python server internal?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FatalFlare21"> /u/FatalFlare21 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2grsq/issue_with_an_insecure_internal_api_call/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2grsq/issue_with_an_insecure_internal_api_call/">[comments]</a></span>

## Zyxel Nebula Cloud alternative
 - [https://www.reddit.com/r/selfhosted/comments/1e2gkjt/zyxel_nebula_cloud_alternative](https://www.reddit.com/r/selfhosted/comments/1e2gkjt/zyxel_nebula_cloud_alternative)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T17:59:23+00:00

<!-- SC_OFF --><div class="md"><p>As of today I only need one AP (Zyxel NWA130BE) for our apartment. But soon we will move in the house and I don’t feel like managing multiple AP. Since I only know Zyxels Nebula Cloud for managing multiple of their AP I wanted to ask if anybody knows a selfhosted alternative to their cloud? bBefore I buy more AP of Zyxel or make the switch to Unifi or Omada. Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/reap_colonie"> /u/reap_colonie </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2gkjt/zyxel_nebula_cloud_alternative/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2gkjt/zyxel_nebula_cloud_alternative/">[comments]</a></span>

## Help with my Home Server and IPv4 support
 - [https://www.reddit.com/r/selfhosted/comments/1e2gad0/help_with_my_home_server_and_ipv4_support](https://www.reddit.com/r/selfhosted/comments/1e2gad0/help_with_my_home_server_and_ipv4_support)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T17:47:02+00:00

<!-- SC_OFF --><div class="md"><p>Good evening guys, I need help with the following problem. I have a Home Server where I host several services, the problem is that my internet provider doesn't provide public IPv4, only ipv6, I'm doing new deployments and I'm going to need IPv4, because some integrations I'm going to do only support IPv4. I thought about taking out a business plan from my provider to have access to ipv4, but the price is very expensive. I also thought about renting an ec2 or perhaps an instance of lightsail, but if I were to get one with the same settings as my home server, it would cost almost 300 euros a month. I thought about taking the most basic instance of lightsail which provides me with a public IPv4 and using it to redirect the requests that arrive on it to my Home Server, but I was afraid because the most basic instance has a very low configuration. Do you have any recommendations? I'm new to self-hosting.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a

## Self hosting for Gmail/google
 - [https://www.reddit.com/r/selfhosted/comments/1e2fqnt/self_hosting_for_gmailgoogle](https://www.reddit.com/r/selfhosted/comments/1e2fqnt/self_hosting_for_gmailgoogle)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T17:23:23+00:00

<!-- SC_OFF --><div class="md"><p>I, like probably most people, have started getting warnings from Gmail and other Google services that I am at 90% usage of my free space. It's quite obvious they've changed something to now try and sell more space instead of automatically deleting unimportant things. I've kicked this can down the road several months and can continue to do so by manually deleting what I don't need but this has also given me the push to start self hosting instead of relying on these free (soon to be paid) cloud storage options. </p> <p>Is there a way for me to ease into this self hosting? Starting with Gmail? Is it possible to point Gmail at a home server? </p> <p>I have a technology background so I don't, yet, need help with getting that setup. What u do need help with is understanding how to point these different services at my self hosted server. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/soggyGreyDuck"> /u/soggyGreyDuck <

## Streaming audio: Recommendations
 - [https://www.reddit.com/r/selfhosted/comments/1e2fkrv/streaming_audio_recommendations](https://www.reddit.com/r/selfhosted/comments/1e2fkrv/streaming_audio_recommendations)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T17:16:18+00:00

<!-- SC_OFF --><div class="md"><p>Hey all,</p> <p>As the title says, I’m looking for suggestions on what software I could (preferably) self host that will allow we to stream audio. Wouldn’t be opposed to running it on my Windows PC either to be honest with ya. Just need a way to stream it to a custom URL. </p> <p>I’m already running a few docker instances with services available via my custom domain, with nginx proxy manager, so I understand that part of it, it’s just choosing which service to use to stream the music. </p> <p>The audio source will be a mix of local files, &amp; on occasion maybe Spotify and the audio would be running 24/7, and my intent is to just ‘tune into’ <a href="https://mymusic.mydomain.com%E2%80%99">https://mymusic.mydomain.com’</a> and I’m able to hear it. </p> <p>I don’t even need audio info (song title, artist) or microphone input either. </p> <p>There has to be something out there to allow me to do this simply, maybe not even running on docker/self hosted a

## Komga will not synchronize with cdisplayex
 - [https://www.reddit.com/r/selfhosted/comments/1e2feum/komga_will_not_synchronize_with_cdisplayex](https://www.reddit.com/r/selfhosted/comments/1e2feum/komga_will_not_synchronize_with_cdisplayex)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T17:09:20+00:00

<!-- SC_OFF --><div class="md"><p>Set up komga, inputted details into the app, and it simply starts synchronisation before saying &quot;synchronisation failed&quot;. What am I doing wrong? The IP address, username, port, and password is all correct. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Puzzleheaded-Slip514"> /u/Puzzleheaded-Slip514 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2feum/komga_will_not_synchronize_with_cdisplayex/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2feum/komga_will_not_synchronize_with_cdisplayex/">[comments]</a></span>

## Questioning my Network Architecture and Reverse Proxies
 - [https://www.reddit.com/r/selfhosted/comments/1e2f39x/questioning_my_network_architecture_and_reverse](https://www.reddit.com/r/selfhosted/comments/1e2f39x/questioning_my_network_architecture_and_reverse)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T16:55:51+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1e2f39x/questioning_my_network_architecture_and_reverse/"> <img alt="Questioning my Network Architecture and Reverse Proxies" src="https://b.thumbs.redditmedia.com/Xwyt1Hnt8TdeisC-VyKjYhmTGr4wbN8bk2J5562pYvs.jpg" title="Questioning my Network Architecture and Reverse Proxies" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>After dragging my feet for a long time I've finally taken the first steps toward SSL on my local network with Caddy, and its making me question some earlier decisions about vlans and DNS and stuff. Hoping for some feedback and ideas from the community here and those with more experience. Maybe this can also help some folks who haven't gotten as far as me yet. </p> <p><strong>Objectives:</strong></p> <p>I want to run servics as locally as possible, with reasonable segmentation. I.e., devices with cameras inside the house (vacuums, tablets for homeassistant dashboards, and actual POE cameras) s

## Any (good) open source project management apps like Asana/Teamwork?
 - [https://www.reddit.com/r/selfhosted/comments/1e2ekmk/any_good_open_source_project_management_apps_like](https://www.reddit.com/r/selfhosted/comments/1e2ekmk/any_good_open_source_project_management_apps_like)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T16:33:42+00:00

<!-- SC_OFF --><div class="md"><p>I tried OpenProject but there are a lot of features that require an enterprise license. OnlyOffice Projects doesn’t have enough features. </p> <p>Focalboard by Mattermost looks pretty good but they discontinued support in 2023 and it Dorans appear anyone has picked up development. </p> <p>We have used Teamwork but it’s falling behind and I hate Asana.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dcpanthersfan"> /u/dcpanthersfan </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2ekmk/any_good_open_source_project_management_apps_like/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2ekmk/any_good_open_source_project_management_apps_like/">[comments]</a></span>

## Self Hosted library with annotations capability
 - [https://www.reddit.com/r/selfhosted/comments/1e2eabq/self_hosted_library_with_annotations_capability](https://www.reddit.com/r/selfhosted/comments/1e2eabq/self_hosted_library_with_annotations_capability)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T16:21:09+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I'm searching for a self-hosted library with a web interface that includes annotation/highlighting features. While I don't need the most feature-rich library, I'm primarily looking for a visual bookshelf and reader. I handle all backend management with Calibre, so a simple yet effective web interface is what I need.</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/fav0109"> /u/fav0109 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2eabq/self_hosted_library_with_annotations_capability/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e2eabq/self_hosted_library_with_annotations_capability/">[comments]</a></span>

## Do mail servers verify authenticity of MX records before emailing you?
 - [https://www.reddit.com/r/selfhosted/comments/1e2dtr6/do_mail_servers_verify_authenticity_of_mx_records](https://www.reddit.com/r/selfhosted/comments/1e2dtr6/do_mail_servers_verify_authenticity_of_mx_records)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T16:01:24+00:00

<!-- SC_OFF --><div class="md"><p>I have been thinking about having my own domain to receive emails with Gmail or Proton. As I understand it, a lot of mail servers don't use DNSsec to check the authenticity of the MX record before trying to deliver emails addressed to my domain, so I was hoping there should be a different mechanism for doing the same, in the same vein as HTTPS helps even if the DNS response was spoofed.</p> <p>When looking I see that there are often mentions of SPF, DKIM, DMARC, MTLS, DANE, TLSA, and the like. Some of these help verify a sender and others help verify the identity of a mail server and most of these are dependent on the integrity of the DNS response, but what I need to know is, if there is a way for the sending mail server to actually verify that the receiving mail server is authorized to receive mail on behalf of the domain in case the DNS response was spoofed? If it is possible, is it in widespread use yet? If not, this is worrisome, but then how do p

## How to fix an internal IP always changing?
 - [https://www.reddit.com/r/selfhosted/comments/1e2bgi0/how_to_fix_an_internal_ip_always_changing](https://www.reddit.com/r/selfhosted/comments/1e2bgi0/how_to_fix_an_internal_ip_always_changing)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T14:16:49+00:00

<!-- SC_OFF --><div class="md"><p>I have a server with a static IP address which hosts almost everything except Ollama because the GPU is on my main machine.</p> <p>I sometimes have to use a hard physical switch to change between two different outgoing networks due to the country I am living in requiring a VPN to access the western internet.</p> <p>With that in mind, how can I keep a hostname with which my server can always contact my dynamically changing IP address on the GPU machine? If I can make a hostname available I can do that. Otherwise how do I update OpenWebUI and other containers dynamically with the new address when it changes? I am a software engineer so developing some kind of service on the main server isn't out of the question.</p> <p>My current thoughts are maybe making a service which I call periodically to update the IP in /etc/hosts for the hostname I use instead of an IP address?</p> <p>I need to update the endpoint in OpenWebUI and AnythingLLM somehow while they 

## How to make RAID system in debian server?
 - [https://www.reddit.com/r/selfhosted/comments/1e2b6ol/how_to_make_raid_system_in_debian_server](https://www.reddit.com/r/selfhosted/comments/1e2b6ol/how_to_make_raid_system_in_debian_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T14:04:21+00:00

<!-- SC_OFF --><div class="md"><p>Hey I'm kind of a newbie getting my feet wet. I've setup a plex and jellyfin server and I'm using Wireguard to access it outside of my local network. All on an old PC running debian server through docker containers. I've bought 4x6TB of hard drives to have more storage available for more things on my server and create an Immich/Nextcloud setup.<br /> Until now, I've been running everything off of 2 drives, one boot SSD and one 2TB hard drive. I want to know, how I can setup data redundancy in my server for the 4 new drives, without having to scrap my whole server and install some NAS operating system. I am aware of ProxMox being able to do this, but do I install ProxMox as a docker container? Can the RAID Pools/Partitions ProxMox makes be visible to Plex, Jellyfin, Immich, Nextcloud if the ProxMox is in its own container? Is there a guide on how I can set this all up? </p> <p>Also, I know I shouldn't be running a NAS ans a hosting server on the same d

## Trying to connect multiple applications to my NAS, but can't ever seem to get it to work properly
 - [https://www.reddit.com/r/selfhosted/comments/1e2a3c8/trying_to_connect_multiple_applications_to_my_nas](https://www.reddit.com/r/selfhosted/comments/1e2a3c8/trying_to_connect_multiple_applications_to_my_nas)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T13:11:07+00:00

<!-- SC_OFF --><div class="md"><p>Hello!</p> <p>I am working on my homelab, and I need some advice. I have recently been working on setting up your typical homelab applications, Jellyfin, Nextcloud, etc. I have successfully been able to get these applications up and running using Docker, but I have one problem that keeps occuring: I can't connect them to my NAS (Open Media Vault)</p> <p>Or well, it's not that simple. I have been able to connect it, but only by setting &quot;no_root_squash&quot; in NFS, which, as far as I understand, is bad security practice. I am fone with running either CIFS/SMB or NFS, but I can't find any easy way to do so securely. What I seem to run into each time is the application not being able to run chmod/chown</p> <p>My question is: How do you guys set this up, and do you have any tips for someone who is fairly new to setting up network volumes in Docker Compose?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ejo2001"

## Should I consider self-hosting Gitlea/Gitlab instead of Github?
 - [https://www.reddit.com/r/selfhosted/comments/1e29j53/should_i_consider_selfhosting_gitleagitlab](https://www.reddit.com/r/selfhosted/comments/1e29j53/should_i_consider_selfhosting_gitleagitlab)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T12:43:05+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I have been moving much of the cloud infrastructure of my software agency (6 people currently, hopefully more in the future) to a self hosted VPS. But I was thinking whether it makes sense for us to move our private repositories away from Github as well. Github does put many organization features behind a paywall. So I guess it makes sense to self host ourselves, since it will be much cheaper for us.</p> <ol> <li>Is there any big disadvantage in self-hosting that might over-weigh the benefit mentioned above?</li> <li>Between self-hosting Gitea and Gitlab, what would you recommend? I have given both a brief try and both look very capable, but want to hear from people who have a longer experience with them.</li> <li>Any other tips or suggestions?</li> </ol> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Red-Eye-Soul"> /u/Red-Eye-Soul </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e29j53/s

## Markup - but for the family
 - [https://www.reddit.com/r/selfhosted/comments/1e28ygh/markup_but_for_the_family](https://www.reddit.com/r/selfhosted/comments/1e28ygh/markup_but_for_the_family)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T12:11:54+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1e28ygh/markup_but_for_the_family/"> <img alt="Markup - but for the family" src="https://b.thumbs.redditmedia.com/BOoC_5fjljcNCfXBpqmi9VzylvBXQFJII6mS4ZIWRUU.jpg" title="Markup - but for the family" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I realize there are some markup options out there but all I am looking for is this:</p> <ol> <li>My wife sends me the url to a pizza joint</li> <li>I decide what I want and highlight/share it with her. </li> <li>She gets the message. This can literally be anything. Screenshot. Text I selected. URL with my highlight. Anything - just as long as it is easily discernable.</li> <li>My selections/url are saved for me (I wanna know what I ordered this time ... next time!)</li> </ol> <p>Ultimately, I am looking to make life easier for the whole family but some of the options out there are overkill for what I want. I am not a marketer looking to provide feedback.</p> <p>Any tho

## Help with a multi-purpose scoreboard / leaderboard site for a group of friends?
 - [https://www.reddit.com/r/selfhosted/comments/1e28o7b/help_with_a_multipurpose_scoreboard_leaderboard](https://www.reddit.com/r/selfhosted/comments/1e28o7b/help_with_a_multipurpose_scoreboard_leaderboard)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T11:56:19+00:00

<!-- SC_OFF --><div class="md"><p>TL;DR - I am looking for a simple way to host a site / app which has a number of pre-defined and customisable leaderboards for a group of friends (stat-nerds) to keep track of their weekly shenanigans.</p> <p>With context:</p> <p>Each week, myself and 5 of my (40 something) friends try to meet up on a Wednesday, <em>we do that strategically to break up the working week... I cannot recommend it enough...</em> Anyway, so we are all young at heart and like to play games. We regularly visit the driving range, and then head back to someone's house and play cards with a few beers, sometimes it's boardgames or darts or anything. Importantly, we run a weekly quiz through WhatsApp. This quiz has a leaderboard and there's only one question each week, the winner will set the quiz for the following Wednesday. The question can be as elaborate as the setter wants it to be but the leaderboard is consistent, a bunch of names and their scores, updated once a week.</p>

## Radarr & Sonarr over multiple volumes
 - [https://www.reddit.com/r/selfhosted/comments/1e28npp/radarr_sonarr_over_multiple_volumes](https://www.reddit.com/r/selfhosted/comments/1e28npp/radarr_sonarr_over_multiple_volumes)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T11:55:30+00:00

<!-- SC_OFF --><div class="md"><p>Hi all. </p> <p>I’m running sonarr and radarrr with multiple instances for 1080p and 4K on a synology nas. My hardrove has filled up and I bought another 10tb but when I added the drive it turns out my initial selection when I diary’s set up the nas probably wasn’t the best choice, and now my best option to expand is to have 2x 10gb volumes. </p> <p>Can I set up radarr and sonarr effectively to use 2 separate volumes for media storage? I figured I could just keep the current library and set a new root folder for saving any new titles to fill the second drive separately instead of putting more in the first?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/wythefucknotzoidberg"> /u/wythefucknotzoidberg </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e28npp/radarr_sonarr_over_multiple_volumes/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e28npp/radarr_

## My Homepage dashboard
 - [https://www.reddit.com/r/selfhosted/comments/1e284gq/my_homepage_dashboard](https://www.reddit.com/r/selfhosted/comments/1e284gq/my_homepage_dashboard)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T11:23:16+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1e284gq/my_homepage_dashboard/"> <img alt="My Homepage dashboard" src="https://preview.redd.it/tcuhvewat9cd1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=ce29e9b491cc05929b2c62c928f4daaf19e11193" title="My Homepage dashboard" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Stef_DP"> /u/Stef_DP </a> <br /> <span><a href="https://i.redd.it/tcuhvewat9cd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e284gq/my_homepage_dashboard/">[comments]</a></span> </td></tr></table>

## Introducing PdfDing
 - [https://www.reddit.com/r/selfhosted/comments/1e27v4o/introducing_pdfding](https://www.reddit.com/r/selfhosted/comments/1e27v4o/introducing_pdfding)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T11:07:18+00:00

<!-- SC_OFF --><div class="md"><p>Hi <a href="/r/selfhosted">r/selfhosted</a>,</p> <p>I am happy to present you <strong>PdfDing</strong> 0.1.0. You can find the repo <a href="https://codeberg.org/mrmn/PdfDing">here</a>. I would be really happy if you would find the time to check it out.</p> <p>PdfDing is a browser based PDF viewer that you can host yourself. It's designed be to be minimal, fast, and easy to set up using Docker.</p> <p>PdfDing was created because I was searching for a selfhostable browser based PDF viewer. However, the existing solution were (at least for my use case) too heavy and feature rich. Thus, I focused on making PDfDing a &quot;simple&quot; with a focus on a single thing: viewing PDFs. This is also why you won't find any fancy AI or OCR in this project.</p> <p>The name is a combination of PDF and <em>ding</em>. Ding is the German word for thing. Thus, PdfDing is a thing for your PDFs. The name and the design of PdfDing are inspired by <a href="https://github.c

## Self hosting is too hard
 - [https://www.reddit.com/r/selfhosted/comments/1e274w2/self_hosting_is_too_hard](https://www.reddit.com/r/selfhosted/comments/1e274w2/self_hosting_is_too_hard)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T10:20:35+00:00

<!-- SC_OFF --><div class="md"><p>Our society has a problem, that is solved by self hosting: people depend on digital services in the cloud that store a lot of data about them. It is a problem that this data is hosted by third-party entities that people are required to trust, but really, they shouldn't.</p> <p>I find this to be a very big issue. Not for me, as I self host my most critical stuff, or rely on entities that I consider worthy of trust. But for virtually everyone I know. None of them could self-host. It's just too hard.</p> <p>I don't suppose I need to substantiate the &quot;self-hosting is hard&quot; bit. But I will edit the post and add it here if you ask.</p> <p>This is an issue that has been on my mind for a year, and that I haven't found a good applicable solution for. How can the Jones get privacy? Are 99% of the population captive of Big Data?</p> <p>The two obvious solutions aren't easy:</p> <ol> <li>Make self-hosting easy</li> <li>Get Mozilla* to bring the cloud to

## PCIe 4 x16 to m2 card?
 - [https://www.reddit.com/r/selfhosted/comments/1e26miq/pcie_4_x16_to_m2_card](https://www.reddit.com/r/selfhosted/comments/1e26miq/pcie_4_x16_to_m2_card)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T09:46:48+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I have a HP Pro SFF 400 G9 Desktop DDR4. I got a free pcie 4 16x and I'm wondering if you know any good cars where I can add 2-4 m2 storage? It need to be low profile as the chassi are not so high. It's deep but not high.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rstolpe"> /u/rstolpe </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e26miq/pcie_4_x16_to_m2_card/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e26miq/pcie_4_x16_to_m2_card/">[comments]</a></span>

## I'm struggling with mail server installation and need help.
 - [https://www.reddit.com/r/selfhosted/comments/1e26d6q/im_struggling_with_mail_server_installation_and](https://www.reddit.com/r/selfhosted/comments/1e26d6q/im_struggling_with_mail_server_installation_and)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T09:29:08+00:00

<!-- SC_OFF --><div class="md"><p>I've been trying to install Postfix and Mailutils for 3 days, using multiple tutorials from the internet, but none of them worked. I can't send emails, and the log always shows 'Network is unreachable'.</p> <p>I really need some guidance.</p> <p>My questions:</p> <ul> <li>To send emails from my server with my domain, what do I need? From what I know, we need Postfix, Mailutils, firewall rules, and DNS settings.</li> </ul> <p>Is there anything I missed?</p> <ul> <li>How should I configure this file: <code>/etc/postfix/main.cf</code>?</li> </ul> <p>Specifically, how should I set 'mydestination'? And should 'myhostname' have 'mail.' before my domain?</p> <h2></h2> <p>About the DNS, most tutorials I read never told me this. I found out when trying to solve the issues. My question is: without setting up DNS for the mail server, can I at least send emails to Gmail? (For troubleshooting, I want to know the where the issues actually are)</p> <h2></h2> <p>It's

## Photos - a long shot
 - [https://www.reddit.com/r/selfhosted/comments/1e25nwt/photos_a_long_shot](https://www.reddit.com/r/selfhosted/comments/1e25nwt/photos_a_long_shot)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T08:41:44+00:00

<!-- SC_OFF --><div class="md"><p>I was watching one of Louis Rossmann's vids recently, was a few weeks ago and I have a piss poor memory so can't remember which one. He was rambling about something and giving options, just in a rant mode, of replacing software from big tech. He mentioned Google Photos and said replace with Photos. </p> <p>Unfortunately as this was a rant, he didn't go into details. Does anyone know what app he was talking about? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/steviefaux"> /u/steviefaux </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e25nwt/photos_a_long_shot/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e25nwt/photos_a_long_shot/">[comments]</a></span>

## Best way to transfer nextcloud n immich to new laptop
 - [https://www.reddit.com/r/selfhosted/comments/1e25m5d/best_way_to_transfer_nextcloud_n_immich_to_new](https://www.reddit.com/r/selfhosted/comments/1e25m5d/best_way_to_transfer_nextcloud_n_immich_to_new)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T08:38:25+00:00

<!-- SC_OFF --><div class="md"><p>Current laptop has win 10 + docker. Nextcloud n immich date is about 700gb ( majority immich photos). Would be shifting to newer laptop with ubuntu mate. Whats the best possible way to transfer the data so that the system is up and running asap?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/amgschnappi"> /u/amgschnappi </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e25m5d/best_way_to_transfer_nextcloud_n_immich_to_new/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e25m5d/best_way_to_transfer_nextcloud_n_immich_to_new/">[comments]</a></span>

## Wifi Connection Going Nuts over Adguard DNS
 - [https://www.reddit.com/r/selfhosted/comments/1e25lwk/wifi_connection_going_nuts_over_adguard_dns](https://www.reddit.com/r/selfhosted/comments/1e25lwk/wifi_connection_going_nuts_over_adguard_dns)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T08:37:57+00:00

<!-- SC_OFF --><div class="md"><p>i have recently bought a raspberry pi and set it up as a small home server for me to play with and get my hands dirty. the first thing that i wanted to self host is a dns server so i set up adguard on to my raspberry pi home server and gave the raspberry pi a local static ip of 192.168.2.155 using my home router settings</p> <p>i then set my router's dns server to be 192.168.2.155 (my raspberry pi home server) so everything goes through my raspberry pi home server. for quite some time everything has been working ok and ads and tracking things are getting blocked and logged in adguard but recently it just stopped working properly.</p> <p>one day things suddenly were not working. when i access a website, somtimes </p> <ul> <li><p>the connection times out (i dont know why this happens)</p></li> <li><p>dns probe issue</p> <ul> <li>i understand this might be from my adguard not working properly BUT when i set my router's dns server to default, and locally 

## Gluetun and OpenwebUI
 - [https://www.reddit.com/r/selfhosted/comments/1e242yj/gluetun_and_openwebui](https://www.reddit.com/r/selfhosted/comments/1e242yj/gluetun_and_openwebui)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T06:55:50+00:00

<!-- SC_OFF --><div class="md"><p>Has anyone managed to connect OpenwebUI via Gluetun? I am in a location where openai APIs no longer work and I want to access them through a VPN. I've managed to connect other containers successfully via Gluetun (change the network to container and then select Gluetun, and pass the ports of the container to the Gluetun container) but am struggling with OpenwebUI. everytime I deploy, I get this error: conflicting options: custom host-to-IP mapping and the network mode</p> <p>Any help would be appreciated. thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dsahai"> /u/dsahai </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e242yj/gluetun_and_openwebui/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e242yj/gluetun_and_openwebui/">[comments]</a></span>

## Local Distributed SQL DB
 - [https://www.reddit.com/r/selfhosted/comments/1e23y7h/local_distributed_sql_db](https://www.reddit.com/r/selfhosted/comments/1e23y7h/local_distributed_sql_db)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T06:47:07+00:00

<!-- SC_OFF --><div class="md"><p>I currently run my “production” db which is MySQL 8 inside of a docker container which is stored locally on my NAS. </p> <p>So I have a little redundancy from the RAID. </p> <p>As my applications have grown in popularity, my data has become more important to me. I have recently acquired access to a second internet connection off site where I can host a second set of servers and load balance between the two. </p> <p>I’ve got the web side of the distributed services worked out, but I’m not sure about the best route for data redundancy and high availability. </p> <p>My ideal solution was a master to master MySQL setup over a VPN. I tried this and it wasn’t very reliable. The tables got out of sync somehow and ended up corrupting one of the DBs.</p> <p>So onto the real question, do you have any recommendations for a reliable SQL based, self hosted, distributed/high availability compatible database?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href

## A place to discuss jellyfin software on Reddit
 - [https://www.reddit.com/r/selfhosted/comments/1e22dbw/a_place_to_discuss_jellyfin_software_on_reddit](https://www.reddit.com/r/selfhosted/comments/1e22dbw/a_place_to_discuss_jellyfin_software_on_reddit)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T05:07:45+00:00

<!-- SC_OFF --><div class="md"><p>Since the other sub is shutdown and doesn't appear to be opening anytime soon, i though it would be nice to have a sub dedicated to doing so. Have fun and be respectful </p> <p><a href="/r/jellyfinn">/r/jellyfinn</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/skeleto_r"> /u/skeleto_r </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e22dbw/a_place_to_discuss_jellyfin_software_on_reddit/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e22dbw/a_place_to_discuss_jellyfin_software_on_reddit/">[comments]</a></span>

## When the server updates test your patience... But don't worry, EsteemHost can handle it for you!
 - [https://www.reddit.com/r/selfhosted/comments/1e21rfv/when_the_server_updates_test_your_patience_but](https://www.reddit.com/r/selfhosted/comments/1e21rfv/when_the_server_updates_test_your_patience_but)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T04:31:49+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1e21rfv/when_the_server_updates_test_your_patience_but/"> <img alt="When the server updates test your patience... But don't worry, EsteemHost can handle it for you! " src="https://preview.redd.it/3p8kbuc0s7cd1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=3350a4e3ab6edc4ccda87d5e02dfeaae5a0c1ad6" title="When the server updates test your patience... But don't worry, EsteemHost can handle it for you! " /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/esteemhostJaipur1"> /u/esteemhostJaipur1 </a> <br /> <span><a href="https://i.redd.it/3p8kbuc0s7cd1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e21rfv/when_the_server_updates_test_your_patience_but/">[comments]</a></span> </td></tr></table>

## Use coolify with caprover?
 - [https://www.reddit.com/r/selfhosted/comments/1e21eel/use_coolify_with_caprover](https://www.reddit.com/r/selfhosted/comments/1e21eel/use_coolify_with_caprover)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T04:11:00+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I've spent thr past couple of days setting up Caprover on my vps. I really like the single click apps, which I have used to setup Nextcloud, Penpot and others on my server. Now I was thinking about moving my sites hosted on Cloudflare Pages to my server as well. They are all mostly Svetelkit and Nextjs 'serverless' sites. While its possible to use Caprover for it, I don't really like the DX of connecting it with private Git repositories. I found coolify as a nice looking alternative for my needs.</p> <p>I have a couple of questions 1. Is it even a good idea to host a Nextjs site meant for serverless on VPS? What are the pros and cons compared to using Vercel, Netlify or Cloudflare. 2. Is it possible to use coolify with Caprover? 3. If they are not compatible, will Coolify support single click apps like Caprover? Will I be able to easily setup Nextcloud and Penpot etc with it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.r

## Immich-love it but need a backup
 - [https://www.reddit.com/r/selfhosted/comments/1e20tj3/immichlove_it_but_need_a_backup](https://www.reddit.com/r/selfhosted/comments/1e20tj3/immichlove_it_but_need_a_backup)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T03:39:27+00:00

<!-- SC_OFF --><div class="md"><p>So, just set up Immich. Brand new and it’s awesome. Just what I was looking for even though I was on the verge of paying for a service. With 35k photos going back more than 10 years it’s been kind of a mess. Anyway, I did it through the portainer script and now I’m getting alerts to update. No slick way to update. Backups seem tricky. Anyone know of a good guide or YT tutorial?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Patient-Tech"> /u/Patient-Tech </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e20tj3/immichlove_it_but_need_a_backup/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e20tj3/immichlove_it_but_need_a_backup/">[comments]</a></span>

## CGNAT options
 - [https://www.reddit.com/r/selfhosted/comments/1e1xgih/cgnat_options](https://www.reddit.com/r/selfhosted/comments/1e1xgih/cgnat_options)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T00:44:57+00:00

<!-- SC_OFF --><div class="md"><p>I currently have Tailscale and Cloudflare Tunnels set up to bust through my CGNAT. These get a lot of gripe because they’re not truly 100% self-hosted and thus vulnerable to snooping. The only alternative I have seen is renting a VPS and setting up wireguard to the VPS.</p> <p>Wouldn’t a VPS also be vulnerable to snooping? Seems like two sides of the same coin to me.</p> <p>My ISP doesn’t offer ipv6. I don’t have access to another server/connection. </p> <p>Is there any other truly 100% selfhosted way to get past CGNAT?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sevenlayercookie5"> /u/sevenlayercookie5 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e1xgih/cgnat_options/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e1xgih/cgnat_options/">[comments]</a></span>

## Is there way to keep deleted media's trace or log for future downloading with radarr /sonarr ??
 - [https://www.reddit.com/r/selfhosted/comments/1e1xgia/is_there_way_to_keep_deleted_medias_trace_or_log](https://www.reddit.com/r/selfhosted/comments/1e1xgia/is_there_way_to_keep_deleted_medias_trace_or_log)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T00:44:57+00:00

<!-- SC_OFF --><div class="md"><p>Yea i know Who wants to delete media !!! I have a small server and it used by my family and friends. Its almost full now, most of the media they don't even end up watching. which is waste of storage. </p> <p>I don't want to fully delete them, at least i want to keep track of what watched before or if i want to watch it again i can just download it again easily </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/itshardtopicka_name_"> /u/itshardtopicka_name_ </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e1xgia/is_there_way_to_keep_deleted_medias_trace_or_log/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e1xgia/is_there_way_to_keep_deleted_medias_trace_or_log/">[comments]</a></span>

## DNS Rewrites not working on mobile apps
 - [https://www.reddit.com/r/selfhosted/comments/1e1x7ac/dns_rewrites_not_working_on_mobile_apps](https://www.reddit.com/r/selfhosted/comments/1e1x7ac/dns_rewrites_not_working_on_mobile_apps)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T00:32:14+00:00

<!-- SC_OFF --><div class="md"><p>I got a reverse proxy working for my domain and JellyFin and PhotoPrism.</p> <p>I got DNS rewrites now working with AGH on my web browsers on my Pixel 7 Pro, Roommates iPhone and my Windows PC (I had to set static DNS on my phone and PC, router DNS was overwritten I guess)</p> <p>When I try to use my jellyfin.mydomain.com in the JellyFin app it says it can't unable to reach server. Still needs my local IP on local network.(Works fine on web browser with cellular off)</p> <p>Am I missing something or not understanding reverse proxies and DNS rewrites.</p> <p>My goal is one domain for my mobile apps so i don't have to switch servers each time. Really my photo app is this the biggest issue.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Kill3rAce"> /u/Kill3rAce </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e1x7ac/dns_rewrites_not_working_on_mobile_apps/">[link]</a></span> &#32; <span><a h

## Self hosting from zimaboard
 - [https://www.reddit.com/r/selfhosted/comments/1e1x398/self_hosting_from_zimaboard](https://www.reddit.com/r/selfhosted/comments/1e1x398/self_hosting_from_zimaboard)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-13T00:26:57+00:00

<!-- SC_OFF --><div class="md"><p>I just got my zimaboard and it's straightforward to setup a cloud and self storage but how do I start pointing things to my personal cloud instead of their default locations? Is it possible to essentially unhook Google drive and point that to my personal server? What's the best option for this? </p> <p>I don't need a step by step or anything like that but I feel like I don't even have the right terms to start googling how to do this on my own. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/soggyGreyDuck"> /u/soggyGreyDuck </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e1x398/self_hosting_from_zimaboard/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e1x398/self_hosting_from_zimaboard/">[comments]</a></span>

