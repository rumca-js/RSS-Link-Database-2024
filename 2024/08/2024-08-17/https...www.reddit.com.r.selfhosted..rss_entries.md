# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## OS+software recommendations for NVR+NAS Linux system
 - [https://www.reddit.com/r/selfhosted/comments/1euutu6/ossoftware_recommendations_for_nvrnas_linux_system](https://www.reddit.com/r/selfhosted/comments/1euutu6/ossoftware_recommendations_for_nvrnas_linux_system)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T23:12:55+00:00

<!-- SC_OFF --><div class="md"><p>Hey all,<br /> I have an NVR (network video recorder) which just died so I replaced with a newer unit. It's become evident the new unit won't allow me to do what I want and after following through many possible options, I've come to the conclusion that I should probably just use an old PC with Linux to do this job using something like Frigate.</p> <p>I've also been getting pain from my QNAP 2-bay NAS (TS-231K) and it seems like this is the perfect opportunity to make a combined NVR and NAS.</p> <p>My network is relatively simple. NAS access would only need to be LAN-based (no WWW access). Windows support is essential, though it would be nice if Macs could access the NAS drive array (RAID-1) as well. Files stored are project files, rather than streaming media.</p> <p>Can anyone point me in the right direction for how to get started on this project? I'm not a Linux guy, but I have been using PCs since the C64 and MS-DOS 6 so I'm not afraid of CLI as lon

## I built a free, open-source, locally hosted tool to find relevant Reddit posts for your product
 - [https://www.reddit.com/r/selfhosted/comments/1eutath/i_built_a_free_opensource_locally_hosted_tool_to](https://www.reddit.com/r/selfhosted/comments/1eutath/i_built_a_free_opensource_locally_hosted_tool_to)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T22:02:56+00:00

<!-- SC_OFF --><div class="md"><p>The open-source tool indexes Reddit posts based on their content, making it easy to find relevant discussions. Mark example posts and get notified about new similar ones to engage with potential customers.</p> <p>See the app and walkthrough here 👉 <a href="https://github.com/8ta4/reddit">https://github.com/8ta4/reddit</a></p> <p>The backend is built using these great open-source components:</p> <ul> <li><p><a href="https://huggingface.co/sentence-transformers/all-mpnet-base-v2">all-mpnet-base-v2</a>: A model for producing text embeddings</p></li> <li><p><a href="https://github.com/UKPLab/sentence-transformers">sentence-transformers</a>: A Python library for text embeddings</p></li> <li><p><a href="https://github.com/clj-python/libpython-clj">libpython-clj</a>: A library for calling Python from Clojure</p></li> <li><p><a href="https://github.com/cachix/devenv">devenv</a>: A development environment tool</p></li> </ul> <p>After seeing how well <a href="h

## Jellyfin VPS encrypted and remote storage
 - [https://www.reddit.com/r/selfhosted/comments/1eur010/jellyfin_vps_encrypted_and_remote_storage](https://www.reddit.com/r/selfhosted/comments/1eur010/jellyfin_vps_encrypted_and_remote_storage)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T20:20:25+00:00

<!-- SC_OFF --><div class="md"><p>This is more of simple questions then needing exact details but I’ll start with the easier one. </p> <ol> <li><p>I’ve seen some cheap low storage VPSs and was wondering if I ran an encrypted folder on it would the host system be able to see all my Linux ISOs? The VPS would have auto decrypt employed so the folder would be accessible to the VPS at all times. </p></li> <li><p>There are some low vCPU servers that have high storage and high transfer rates that are affordable, would I be able to mount that to my Jellyfin VPS and have decent Linux ISO storage? An initial delay is not a problem as long as it works smoothly. </p></li> </ol> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DustyFlapp"> /u/DustyFlapp </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eur010/jellyfin_vps_encrypted_and_remote_storage/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eur01

## DNS external vs DNS local what are you doing?
 - [https://www.reddit.com/r/selfhosted/comments/1euqm9d/dns_external_vs_dns_local_what_are_you_doing](https://www.reddit.com/r/selfhosted/comments/1euqm9d/dns_external_vs_dns_local_what_are_you_doing)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T20:03:22+00:00

<!-- SC_OFF --><div class="md"><p>For your self-hosted services, how are you handling external DNS vs local DNS?</p> <p>I have a registered domain with Cloudflare as my DNS server. I am running DDNS to update my IP address to my IP address from my ISP. This server (running DDNS client) is also my firewall and my reverse proxy server. From someone coming from outside my local network, this, I believe, is fairly standard.</p> <p>What I don't see discussed much is how traffic flow works when coming from your local LAN.</p> <p>In my case, I have run a BIND/named server for years. Mostly as a recursive caching server with all outbound requests going through stubby (for DoH), but I also use it for my internal LAN network, my Kubernetes network, and also (and maybe the wrong thing to do) a local DNS server for my domain whose IP is hosted on Cloudflare.</p> <p>The thinking is why would I want my local network clients to resolve the domain address from Cloudflare, and then hit the IP address 

## Linkwarden help
 - [https://www.reddit.com/r/selfhosted/comments/1eupn48/linkwarden_help](https://www.reddit.com/r/selfhosted/comments/1eupn48/linkwarden_help)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T19:19:31+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1eupn48/linkwarden_help/"> <img alt="Linkwarden help" src="https://preview.redd.it/lupy5ptay9jd1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=5f5a776143c9eee064817750358688cfdb271136" title="Linkwarden help" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I just installed linkwarden and I'm running into an issue where there are no thumbnails for the bookmarks. Is this normal or am I missing something. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fireman86336"> /u/Fireman86336 </a> <br /> <span><a href="https://i.redd.it/lupy5ptay9jd1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eupn48/linkwarden_help/">[comments]</a></span> </td></tr></table>

## Roadtrip planning. Anyone know of a self hosted solution that fits the bill?
 - [https://www.reddit.com/r/selfhosted/comments/1euphov/roadtrip_planning_anyone_know_of_a_self_hosted](https://www.reddit.com/r/selfhosted/comments/1euphov/roadtrip_planning_anyone_know_of_a_self_hosted)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T19:12:48+00:00

<!-- SC_OFF --><div class="md"><p>I'm planning a road trip for a fairly large group of friends. Rather than trying to send a load of links/keep everything on a spreadsheet is there a self hosted app than can assist in the planning? That way I can just host it and give them the link. It would be even better if anyone I give the link to could add potential activities to the tiles etc. I guess some sort of pintrest-esque tile based or squarespace style editable website that can be broken down in to days. Something that has tiles that can have links to google maps routes, activities, hotels etc which can be broken down in to headings and made to look nice!</p> <p>I could just throw something together in HTML to host, but my design skills peaked in the mid 2000's, so it'd probably look like an old geocities page! Plus it would take longer than just throwing in to a speadsheet.</p> <p>I appreciate this is quite a niche use case, but I was wondering if I could adapt something else (maybe som

## Telegram Bot to Add/Delete Users in Emby, Jellyfin, & Jellyseer
 - [https://www.reddit.com/r/selfhosted/comments/1eupdc5/telegram_bot_to_adddelete_users_in_emby_jellyfin](https://www.reddit.com/r/selfhosted/comments/1eupdc5/telegram_bot_to_adddelete_users_in_emby_jellyfin)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T19:07:36+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1eupdc5/telegram_bot_to_adddelete_users_in_emby_jellyfin/"> <img alt="Telegram Bot to Add/Delete Users in Emby, Jellyfin, &amp; Jellyseer" src="https://b.thumbs.redditmedia.com/bV-5Bf9r3DcQs0MBkj4qqZbwVeMTNMKLgCKk3G7h73w.jpg" title="Telegram Bot to Add/Delete Users in Emby, Jellyfin, &amp; Jellyseer" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey selfhosted community,</p> <p>I'm excited to share a project I've been working on for myself, thought of sharing it here.</p> <p>A Telegram bot that automates user management across Emby, Jellyfin, and Jellyseerr!</p> <h1>📙 Features</h1> <ul> <li><strong>Add Users</strong>: Easily create users across Emby, Jellyfin, and Jellyseerr with a single command.</li> <li><strong>Delete Users</strong>: Remove users from all three platforms effortlessly.</li> <li><strong>Bulk Add/Delete</strong>: Add or delete multiple users at once.</li> <li><strong>Password Management</stro

## Test website for ssh server hardening
 - [https://www.reddit.com/r/selfhosted/comments/1euoiwq/test_website_for_ssh_server_hardening](https://www.reddit.com/r/selfhosted/comments/1euoiwq/test_website_for_ssh_server_hardening)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T18:30:22+00:00

<!-- SC_OFF --><div class="md"><p>A while ago a colleague tested my ssh server on my vps. The result wasn’t very good. I did some steps to improve hardening (<a href="https://docs.vultr.com/how-to-harden-server-ssh-access-using-advanced-openssh-features">https://docs.vultr.com/how-to-harden-server-ssh-access-using-advanced-openssh-features</a>). He tested it with a website that scans the port and then gives a rating. However, I can’t find this site. Which can you recommend?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/peterge98"> /u/peterge98 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1euoiwq/test_website_for_ssh_server_hardening/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1euoiwq/test_website_for_ssh_server_hardening/">[comments]</a></span>

## Just moved my site to GitHub!
 - [https://www.reddit.com/r/selfhosted/comments/1euo8pj/just_moved_my_site_to_github](https://www.reddit.com/r/selfhosted/comments/1euo8pj/just_moved_my_site_to_github)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T18:17:25+00:00

<!-- SC_OFF --><div class="md"><p>After having HostGator raise its prices, then lower the storage capacity of my site pushing me into the $31 a month pricing tier from the $8 a month I was paying, I started to look for alternatives. Found out GitHub actually can host a site with the limitation that the site can not be dynamic. I have just got it up a running and it is very responsive, better than HostGator in my opinion. i would suggestthis to anyone lookg for a cheap hosting alternative. I trust Github to stay around a lot more than these other smaller companies as they are owned by Microsoft.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jay662"> /u/jay662 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1euo8pj/just_moved_my_site_to_github/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1euo8pj/just_moved_my_site_to_github/">[comments]</a></span>

## Multi-user music server
 - [https://www.reddit.com/r/selfhosted/comments/1eumfr4/multiuser_music_server](https://www.reddit.com/r/selfhosted/comments/1eumfr4/multiuser_music_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T16:57:58+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for something that I'm not sure exists. I want to become a music hoarder, and I'd like to invite my friends to join me in this venture, however I want an app that will facilitate this the way I want.</p> <p>So I want to essentially host my own Spotify, in which I would have a giant collection of music from multiple users, and be able to browse/search through all of the music and add other people's music to my &quot;library&quot;, ideally using an app with a good looking UI. I wanted to use an app like Symfonium which I understand is popular, however I don't know if this sort of thing is supported.</p> <p>Does something like this exist?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/HonestRepairSTL"> /u/HonestRepairSTL </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eumfr4/multiuser_music_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comm

## Multi-user music server
 - [https://www.reddit.com/r/selfhosted/comments/1eumerz/multiuser_music_server](https://www.reddit.com/r/selfhosted/comments/1eumerz/multiuser_music_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T16:56:47+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for something that I'm not sure exists. I want to become a music hoarder, and I'd like to invite my friends to join me in this venture, however I want an app that will facilitate this the way I want.</p> <p>So I want to essentially host my own Spotify, in which I would have a giant collection of music from multiple users, and be able to browse/search through all of the music and add other people's music to my &quot;library&quot;, ideally using an app with a good looking UI. I wanted to use an app like Symfonium which I understand is popular, however I don't know if this sort of thing is supported.</p> <p>Does something like this exist?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/HonestRepairSTL"> /u/HonestRepairSTL </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eumerz/multiuser_music_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comm

## Mixing Proxmox and Synology for HA containers.
 - [https://www.reddit.com/r/selfhosted/comments/1eulh3y/mixing_proxmox_and_synology_for_ha_containers](https://www.reddit.com/r/selfhosted/comments/1eulh3y/mixing_proxmox_and_synology_for_ha_containers)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T16:16:26+00:00

<!-- SC_OFF --><div class="md"><p>Hi there, I have some containers running on a Proxmox mini PC, as I also have a Synology running other containers like Jellyfin, I'm wondering if I could set up any kind of redundancy for critical containers like Nginx, maybe with docker swarm. Anyone went that route ? Any suggestions? Thanks </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/powermi"> /u/powermi </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eulh3y/mixing_proxmox_and_synology_for_ha_containers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eulh3y/mixing_proxmox_and_synology_for_ha_containers/">[comments]</a></span>

## FoneTool - iPhone backups
 - [https://www.reddit.com/r/selfhosted/comments/1eul9xu/fonetool_iphone_backups](https://www.reddit.com/r/selfhosted/comments/1eul9xu/fonetool_iphone_backups)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T16:07:54+00:00

<!-- SC_OFF --><div class="md"><p>has anyone used this? is it leget? <a href="https://www.fonetool.com/?_di_c=ZGV2X2lkX2UxNjgzMjU3LWEzZDMtNDVhMy04YTJlLWNmNjYzNGU0MWYxZg==">FoneTool</a></p> <p>I was close to purchasing iMazing until i learned their license model which is bogus. Looking for automated backups over wifi to home server running windows. Not opposed to paying for something legit, I don't have time to blow learning, trouble shooting, and supporting a bunch of open source stuff.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Yaybicycles"> /u/Yaybicycles </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eul9xu/fonetool_iphone_backups/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eul9xu/fonetool_iphone_backups/">[comments]</a></span>

## Jellyfin can't access share on LXC!
 - [https://www.reddit.com/r/selfhosted/comments/1eujsqc/jellyfin_cant_access_share_on_lxc](https://www.reddit.com/r/selfhosted/comments/1eujsqc/jellyfin_cant_access_share_on_lxc)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T15:03:12+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1eujsqc/jellyfin_cant_access_share_on_lxc/"> <img alt="Jellyfin can't access share on LXC!" src="https://b.thumbs.redditmedia.com/G2A6EM0r0d3peVAxA3-j71O7AFd6nUde7CpTVBiKiLQ.jpg" title="Jellyfin can't access share on LXC!" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I have set up an NFS share on my a LXC on proxmox. The LXC itself can access all the files on the share. I have setup jellyfin using docker compose but jellyfin can't access the files of the NFS shares.</p> <p><a href="https://preview.redd.it/nbs963ejo8jd1.png?width=1147&amp;format=png&amp;auto=webp&amp;s=071fdc4c85574560dea52f348b5a0ede3f8ba86a">https://preview.redd.it/nbs963ejo8jd1.png?width=1147&amp;format=png&amp;auto=webp&amp;s=071fdc4c85574560dea52f348b5a0ede3f8ba86a</a></p> <p><code>docker-compose.yml</code>Content:</p> <pre><code>services: jellyfin: image: jellyfin/jellyfin container_name: jellyfin group_add: - '107' environment: - TZ=Eu

## Self Hosted applications like ScribeHow
 - [https://www.reddit.com/r/selfhosted/comments/1eujlt6/self_hosted_applications_like_scribehow](https://www.reddit.com/r/selfhosted/comments/1eujlt6/self_hosted_applications_like_scribehow)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T14:54:43+00:00

<!-- SC_OFF --><div class="md"><p>Hey all, I am finding I love scribe, I am not capable of paying 24.99 a month though for it. Is there an app I’m not finding throughout the searches that does basically what scribehow does that I can self host? </p> <p>Thanks!!!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/chrisl154"> /u/chrisl154 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eujlt6/self_hosted_applications_like_scribehow/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eujlt6/self_hosted_applications_like_scribehow/">[comments]</a></span>

## FREE SOFTWARE to create resume based on job description
 - [https://www.reddit.com/r/selfhosted/comments/1euivg8/free_software_to_create_resume_based_on_job](https://www.reddit.com/r/selfhosted/comments/1euivg8/free_software_to_create_resume_based_on_job)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T14:21:21+00:00

<!-- SC_OFF --><div class="md"><h1>Introducing Resume_Builder_AIHawk🚀</h1> <p>Are you tired of spending hours perfecting your resume for every job application? Say hello to <strong>Resume_Builder_AIHawk</strong>, a powerful Python tool designed to make creating visually stunning resumes fast and effortless!</p> <h2>🛠️ Features:</h2> <ul> <li><strong>Interactive Command-Line Interface:</strong> Navigate through options and prompts with ease using our user-friendly CLI.</li> <li><strong>Dynamic Style Management:</strong> Select from a variety of pre-defined resume styles to match your preference.</li> <li><strong>Job Description Integration:</strong> Automatically customize your resume based on a job URL, ensuring it aligns perfectly with the job requirements and skills.</li> </ul> <h2>📈 Why Use Resume_Builder_AIHawk?</h2> <ul> <li><strong>Save Time:</strong> Quickly generate resumes tailored to specific job descriptions.</li> <li><strong>Increase Your Chances:</strong> A resume that ma

## Introducing GiftManager
 - [https://www.reddit.com/r/selfhosted/comments/1euhv3s/introducing_giftmanager](https://www.reddit.com/r/selfhosted/comments/1euhv3s/introducing_giftmanager)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T13:34:39+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone! </p> <p>Here is GiftManager, a project I've been working on since October 2023.</p> <p>It's my first project I publish, I'm open to critics.</p> <p>GiftManager is designed to make managing gift ideas for family and friends both effortless and enjoyable. Here are the key features that make it a nice tool:</p> <ul> <li><strong>Prevent Duplicate Gifts</strong>: Mark items as bought to ensure no one buys the same gift twice.</li> <li><strong>Add Links</strong>: Easily add links to show exactly what you want, so there's no guesswork.</li> <li><strong>Collaborative Lists</strong>: Contribute to others' gift lists if you have great ideas for them.</li> <li><strong>Email Alerts</strong>: Receive notifications if an item you’ve bought gets removed, keeping you in the loop.</li> <li><strong>No Spoilers</strong>: When viewing your own list, you won’t see what others have bought or added, preserving the surprise.</li> </ul> <p>I initially made it 

## Question for the Homepage User´s: Is there a way to show my external IP on my homepage?
 - [https://www.reddit.com/r/selfhosted/comments/1eugmm1/question_for_the_homepage_users_is_there_a_way_to](https://www.reddit.com/r/selfhosted/comments/1eugmm1/question_for_the_homepage_users_is_there_a_way_to)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T12:33:28+00:00

<!-- SC_OFF --><div class="md"><p>Hey, I was just setting up my homepage and was wondering if there´s a way to show my external IP? </p> <p>Like in the greetings or something like that?</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PaulTankerfahrer"> /u/PaulTankerfahrer </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eugmm1/question_for_the_homepage_users_is_there_a_way_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eugmm1/question_for_the_homepage_users_is_there_a_way_to/">[comments]</a></span>

## object storage like wasabi for CCTV footage...
 - [https://www.reddit.com/r/selfhosted/comments/1eug2yp/object_storage_like_wasabi_for_cctv_footage](https://www.reddit.com/r/selfhosted/comments/1eug2yp/object_storage_like_wasabi_for_cctv_footage)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T12:04:20+00:00

<!-- SC_OFF --><div class="md"><p>Any suggestions into cloud solutions for object storage from my CCTV cameras?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/barnez29"> /u/barnez29 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eug2yp/object_storage_like_wasabi_for_cctv_footage/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eug2yp/object_storage_like_wasabi_for_cctv_footage/">[comments]</a></span>

## Password delivery service
 - [https://www.reddit.com/r/selfhosted/comments/1eufto1/password_delivery_service](https://www.reddit.com/r/selfhosted/comments/1eufto1/password_delivery_service)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T11:49:27+00:00

<!-- SC_OFF --><div class="md"><p>Hello friends,</p> <p>I am currently searching for a password delivery tool, such as <a href="https://passflow.de">https://passflow.de</a> but selfhosted. Does anyone of you know such thing?</p> <p>Many thanks, and happy selfhosting :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Educational-Force-65"> /u/Educational-Force-65 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eufto1/password_delivery_service/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eufto1/password_delivery_service/">[comments]</a></span>

## Which is the best Meal Planner App?
 - [https://www.reddit.com/r/selfhosted/comments/1euf8rx/which_is_the_best_meal_planner_app](https://www.reddit.com/r/selfhosted/comments/1euf8rx/which_is_the_best_meal_planner_app)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T11:13:42+00:00

<!-- SC_OFF --><div class="md"><p>Features</p> <ul> <li>Calendar</li> <li>Recipe</li> <li>Shopping List</li> <li>Notification</li> <li>Best UX on Mobile</li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Top_Concern8607"> /u/Top_Concern8607 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1euf8rx/which_is_the_best_meal_planner_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1euf8rx/which_is_the_best_meal_planner_app/">[comments]</a></span>

## Best Self Hosted Chat Server
 - [https://www.reddit.com/r/selfhosted/comments/1eue3sq/best_self_hosted_chat_server](https://www.reddit.com/r/selfhosted/comments/1eue3sq/best_self_hosted_chat_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T09:57:03+00:00

<!-- SC_OFF --><div class="md"><p>Hi, pretty much the title</p> <p>We have an organization of +25 people. I need to create a chat server like slack. It should be lightweight. What are your suggestions? I have matrix, mattermost, rocketchat and chatwood in my mind but I dont know which one to choose, or choose anyhting else.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PuzzleheadedGold3069"> /u/PuzzleheadedGold3069 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eue3sq/best_self_hosted_chat_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eue3sq/best_self_hosted_chat_server/">[comments]</a></span>

## Seeing a lot of people using Technitium for dns based ad blocking. Are there any benchmarks available?
 - [https://www.reddit.com/r/selfhosted/comments/1eu5vae/seeing_a_lot_of_people_using_technitium_for_dns](https://www.reddit.com/r/selfhosted/comments/1eu5vae/seeing_a_lot_of_people_using_technitium_for_dns)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-17T01:30:09+00:00

<!-- SC_OFF --><div class="md"><p>I'm looking into technitium to handle dns ad blocking plus maybe as a recursive resolver. I'm pretty attached to blocky + unbound, but seeing the mentions in a recent thread had me curious. That said, I haven't seen anything about the latency or any other performance metrics. What are peoples' experiences with this?</p> <p>Edit: I decided on Blocky based on this benchmark here: <a href="https://www.youtube.com/watch?v=rfBh2VVOVZA">https://www.youtube.com/watch?v=rfBh2VVOVZA</a>. It shows latency significantly lower than with pihole or adguard.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MonkAndCanatella"> /u/MonkAndCanatella </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eu5vae/seeing_a_lot_of_people_using_technitium_for_dns/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eu5vae/seeing_a_lot_of_people_using_technitium_for_dns/">[comments]</a></s

