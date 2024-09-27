# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Is it self to host my web-apps on pi to be accessed by anyone on the internet?
 - [https://www.reddit.com/r/selfhosted/comments/1fq8i0p/is_it_self_to_host_my_webapps_on_pi_to_be](https://www.reddit.com/r/selfhosted/comments/1fq8i0p/is_it_self_to_host_my_webapps_on_pi_to_be)
 - RSS feed: $source
 - date published: 2024-09-26T22:12:56+00:00

<!-- SC_OFF --><div class="md"><p>I have a pi, I have hosted my web apps on the pi. Things I have done to keep it safe.</p> <ol> <li><p>Cloudflare tunnel, with zero trust policies, and only specific geo location allowed.</p></li> <li><p>Running all the apps in docker containers, and running them as least privileged user possible.</p></li> <li><p>Surfshark VPN.</p></li> <li><p>Restricted ufw rules,</p></li> <li><p>Allow incoming ssh in a subnet, RDP, and internet connection from router.</p></li> <li><p>Allow outgoing to router with specific ports for internet connectivity, and port of VPN.</p></li> </ol> <p>Is this safe, or can any hacker still get into my network and take it down?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fun-Individual-2428"> /u/Fun-Individual-2428 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq8i0p/is_it_self_to_host_my_webapps_on_pi_to_be/">[link]</a></span> &#32; <span><a href="https://www.red

## Is there any benefit in putting services behind login barriers like Authelia if they already provide a login form?
 - [https://www.reddit.com/r/selfhosted/comments/1fq7jl2/is_there_any_benefit_in_putting_services_behind](https://www.reddit.com/r/selfhosted/comments/1fq7jl2/is_there_any_benefit_in_putting_services_behind)
 - RSS feed: $source
 - date published: 2024-09-26T21:30:32+00:00

<!-- SC_OFF --><div class="md"><p>Hello hosters!</p> <p>I am moving from a local network self-hosted system into a publicly exposed one for a limited group of services. They&#39;re going to be a single-user scenario (only me).</p> <p>Now, when in public, being protected will become crucial and I am planning this carefully. In particular:</p> <ul> <li>I am using SWAG reverse proxy. In LAN it only does reverse proxy. Now I am pairing it with Authelia so that every proxied service will force a login (same credentials for all services, which is nice for my setup). Also 2FA available, cool.</li> <li>Some services have already a login mechanism (healthchecks, nextcloud to name a couple). Some also offer already 2FA.</li> <li>Most of the these login-equipped services won&#39;t let you bypass the login mechanism. The might &quot;remember you&quot;, but that&#39;s another story.</li> </ul> <p>Now my question is:</p> <ol> <li>would you selectively apply Authelia only to some services?</li> <li>

## How do I install a vpn server / wireguard (or other) with a nginx proxy manager and cloudflare-DDNS on proxmox?
 - [https://www.reddit.com/r/selfhosted/comments/1fq6z4o/how_do_i_install_a_vpn_server_wireguard_or_other](https://www.reddit.com/r/selfhosted/comments/1fq6z4o/how_do_i_install_a_vpn_server_wireguard_or_other)
 - RSS feed: $source
 - date published: 2024-09-26T21:05:57+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve installed WireGuard and Nginx Proxy Manager using the ttecks helper script on my Proxmox host. Additionally, I set up the Cloudflare DDNS updater (<a href="https://github.com/K0p1-Git/cloudflare-ddns-updater">https://github.com/K0p1-Git/cloudflare-ddns-updater</a>) and pointed it to my domain. I also created a CNAME record for vpn.domain.com. However, I&#39;m having trouble getting it to work. I&#39;m new to Proxmox and still in the process of learning how everything fits together.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sea-Finding6147"> /u/Sea-Finding6147 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq6z4o/how_do_i_install_a_vpn_server_wireguard_or_other/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq6z4o/how_do_i_install_a_vpn_server_wireguard_or_other/">[comments]</a></span>

## What is the best practice for email setup?
 - [https://www.reddit.com/r/selfhosted/comments/1fq6ofp/what_is_the_best_practice_for_email_setup](https://www.reddit.com/r/selfhosted/comments/1fq6ofp/what_is_the_best_practice_for_email_setup)
 - RSS feed: $source
 - date published: 2024-09-26T20:53:26+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>As a CS student, I&#39;m working on streamlining my personal tech setup. I&#39;ve already self-hosted a Vaultwarden instance and set up a domain for it. Now, I&#39;m looking to improve my email management.</p> <p>Currently, I have a mix of Gmail, Proton Mail, SimpleLogin aliases, and a work email. This feels overwhelming as I need to check multiple inboxes.</p> <p>I&#39;m curious about your strategies for:</p> <ul> <li><strong>Email Organization:</strong> How do you categorize emails based on their purpose (e.g., gaming, services, finances)? I&#39;ve been using aliases for different categories.</li> <li><strong>Email Management Tools:</strong> What software do you recommend for managing multiple email accounts from different providers? I&#39;m looking for a solution that can handle at least two main accounts (personal and work).</li> </ul> <p>Overall I would be happy hearing about your setups :D</p> </div><!-- SC_ON --> &#32; submi

## Calibre/Kavita
 - [https://www.reddit.com/r/selfhosted/comments/1fq4tlr/calibrekavita](https://www.reddit.com/r/selfhosted/comments/1fq4tlr/calibrekavita)
 - RSS feed: $source
 - date published: 2024-09-26T19:34:14+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m still somewhat of a noob at this setup, but is there a simpler way of organizing books and I&#39;ve just missed it?</p> <p>All of the books seem to just be vomited out, is there a way to make things more tidy? Like grouping by author, folders, etc? Having books that are in a series automatically sorted that way?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/elder242"> /u/elder242 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq4tlr/calibrekavita/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq4tlr/calibrekavita/">[comments]</a></span>

## Need some smart answers towards some questions concerning VPN, gluetun, Qbittorrent
 - [https://www.reddit.com/r/selfhosted/comments/1fq4kqs/need_some_smart_answers_towards_some_questions](https://www.reddit.com/r/selfhosted/comments/1fq4kqs/need_some_smart_answers_towards_some_questions)
 - RSS feed: $source
 - date published: 2024-09-26T19:23:50+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fq4kqs/need_some_smart_answers_towards_some_questions/"> <img src="https://b.thumbs.redditmedia.com/uuRHtk7XoNZoiaLiqkvP0_ERxfB8uoTHOPTvI7AoSAc.jpg" alt="Need some smart answers towards some questions concerning VPN, gluetun, Qbittorrent" title="Need some smart answers towards some questions concerning VPN, gluetun, Qbittorrent" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I have some questions concerning slow speeds in Qbit with my current setup and was hoping for a smart person to help me out:</p> <p>My setup is a Odroid H4 with a Intel Core i3-N305 with 32GB RAM. I have Open Media Vault running on a 64gb MMC and a 1TB data SSD. I sit on a 1Gbit fiber connection.</p> <p>I Installed Docker and created a script for:<br/> Gluetun: qmcgaw/gluetun<br/> Qbittorrent: <a href="http://lscr.io/linuxserver/qbittorrent:latest">lscr.io/linuxserver/qbittorrent:latest</a><br/> - with the Port setting Mod DOCKER_MODS=ghc

## Bookstack Azure/O365 login
 - [https://www.reddit.com/r/selfhosted/comments/1fq4dp4/bookstack_azureo365_login](https://www.reddit.com/r/selfhosted/comments/1fq4dp4/bookstack_azureo365_login)
 - RSS feed: $source
 - date published: 2024-09-26T19:15:30+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fq4dp4/bookstack_azureo365_login/"> <img src="https://b.thumbs.redditmedia.com/LxnEk5kO7FH7BkL-t5ohqviwrk_DEMPKP_uVzmIrkCc.jpg" alt="Bookstack Azure/O365 login" title="Bookstack Azure/O365 login" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I added the azure login stuff per bookstack documentation but im stuck at this point:</p> <p><a href="https://preview.redd.it/vskrqk51e7rd1.png?width=719&amp;format=png&amp;auto=webp&amp;s=a774226304953948c83aa202f8bc1ef2a2a15b98">https://preview.redd.it/vskrqk51e7rd1.png?width=719&amp;format=png&amp;auto=webp&amp;s=a774226304953948c83aa202f8bc1ef2a2a15b98</a></p> <p>It all seems to be working but I need to populate this on each user, I have no idea what is supposed to go here. Thank you for any help! Also I wanted to be sure, my office all uses O365 and we are logged in to the office suite, outlook etc. I am hoping this will allow my users when logged in already to O365

## Best no frills email host
 - [https://www.reddit.com/r/selfhosted/comments/1fq3wz9/best_no_frills_email_host](https://www.reddit.com/r/selfhosted/comments/1fq3wz9/best_no_frills_email_host)
 - RSS feed: $source
 - date published: 2024-09-26T18:56:05+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys!</p> <p>I own my own business and I want to set up a <a href="mailto:myname@companyname.com">myname@companyname.com</a> email, I&#39;ve tried using Google Workspace but it was two much bells and whistles for me.</p> <p>I will be directing it&#39;s mail to my personal and will be sending the emails from my personal using that alias setting. So I literally just want an custom email, no administrative settings or anything fancy.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DamianCPH"> /u/DamianCPH </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq3wz9/best_no_frills_email_host/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq3wz9/best_no_frills_email_host/">[comments]</a></span>

## A cheap VPS to host a VPN
 - [https://www.reddit.com/r/selfhosted/comments/1fq3r2i/a_cheap_vps_to_host_a_vpn](https://www.reddit.com/r/selfhosted/comments/1fq3r2i/a_cheap_vps_to_host_a_vpn)
 - RSS feed: $source
 - date published: 2024-09-26T18:49:04+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I looked on Google and Reddit, but all results are pretty old. Do you guys knows some cheap VPS to host a VPN to do torrent ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/truefrenchg"> /u/truefrenchg </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq3r2i/a_cheap_vps_to_host_a_vpn/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq3r2i/a_cheap_vps_to_host_a_vpn/">[comments]</a></span>

## Immich , google photos, iOS photos organize and album, syncing photos.
 - [https://www.reddit.com/r/selfhosted/comments/1fq3odh/immich_google_photos_ios_photos_organize_and](https://www.reddit.com/r/selfhosted/comments/1fq3odh/immich_google_photos_ios_photos_organize_and)
 - RSS feed: $source
 - date published: 2024-09-26T18:45:59+00:00

<!-- SC_OFF --><div class="md"><p>I stumbled on a serious issue and worry about it.</p> <p>Like example: You have a group of friends: 4+</p> <p>All have phone with different apps, iphones, android Even window phones etc </p> <p>Some have icloud or google one.</p> <p>Let&#39;s say in future I can copy full SD card of all phones to a Nas. Not the data that requires root or hidden.</p> <p>Let&#39;s say a folder name phones Folder says friend1 friend2 Al have own rights so friends cannot see each other data.</p> <p>But I read that files can lose or don&#39;t have meta data. So how can you ever remember which files belong to when?</p> <p>Like if I want to have Greece 2018 with photos dedicated to it. How can I arrange this and do you guys not have these issues?</p> <p>Imagine 700gb of photos in a folder. First of all I think the filesystem not like that but there must be some auto organization for this right? This seems a hugr tasks.</p> <p>Then often photos are spit over separated data fo

## Looking for to do/one person project management suggestions
 - [https://www.reddit.com/r/selfhosted/comments/1fq2z1t/looking_for_to_doone_person_project_management](https://www.reddit.com/r/selfhosted/comments/1fq2z1t/looking_for_to_doone_person_project_management)
 - RSS feed: $source
 - date published: 2024-09-26T18:15:45+00:00

<!-- SC_OFF --><div class="md"><p>I now have so much going on (new job plus grad school) that I need a better way to keep track of it. I’d like to run it on my home server, so I can access it from multiple devices, and a web interface would be a plus so I don’t have to install software on my work laptop.</p> <p>I’d like something with lightweight project management, and a calendar view so I have a way to keep track of due dates. I like kanban and would try planka but for the lack of calendar view. Any suggestions?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/salliesdad"> /u/salliesdad </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq2z1t/looking_for_to_doone_person_project_management/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq2z1t/looking_for_to_doone_person_project_management/">[comments]</a></span>

## File recovery in Samba?
 - [https://www.reddit.com/r/selfhosted/comments/1fq2xab/file_recovery_in_samba](https://www.reddit.com/r/selfhosted/comments/1fq2xab/file_recovery_in_samba)
 - RSS feed: $source
 - date published: 2024-09-26T18:13:40+00:00

<!-- SC_OFF --><div class="md"><p>I am in the process of migrating from nextcloud to samba. I am happy with the result, as the transfer speed is much faster in my case, however after nextcloud I still lack the recycle bin feature - any accidentally deleted file on the network disk is gone forever.</p> <p>Of course, it&#39;s not hard to find many solutions like vfs_recycle, rsnapshot or borg, however they all share the problem that there is no quick and easy way to quickly recover a file on the client without digging inside the server.</p> <p>Are there any workarounds? Perhaps something similar to nextcloud web gui?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Affectionate-Lake733"> /u/Affectionate-Lake733 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq2xab/file_recovery_in_samba/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq2xab/file_recovery_in_samba/">[comments]</a></span>

## Searching for local ip camera with onvif
 - [https://www.reddit.com/r/selfhosted/comments/1fq1nox/searching_for_local_ip_camera_with_onvif](https://www.reddit.com/r/selfhosted/comments/1fq1nox/searching_for_local_ip_camera_with_onvif)
 - RSS feed: $source
 - date published: 2024-09-26T17:21:43+00:00

<!-- SC_OFF --><div class="md"><p>Hi!</p> <p>I&#39;m searching for an ip camera. Most ip cameras I found have their own dedicated app, but I don&#39;t want my cameras to connect to some foreign server. I have my own synology nas server at home and I&#39;d like to connect my ip cameras to this nas server. I still would like to setup a live feed, but through my nas server (I have remote access to it). If my research is correct, I need it to support onvif. Is that setup possible? Can you recommend me any brands?</p> <p>Edit: Forgot to mention, but I wanted to set one of the cameras about 20m from home, so I hope for some WLAN solutions.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Qbsoon110"> /u/Qbsoon110 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq1nox/searching_for_local_ip_camera_with_onvif/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq1nox/searching_for_local_ip_camera_w

## Self-hosted photo storage vs iCloud Photos for Apple devices
 - [https://www.reddit.com/r/selfhosted/comments/1fq1cwl/selfhosted_photo_storage_vs_icloud_photos_for](https://www.reddit.com/r/selfhosted/comments/1fq1cwl/selfhosted_photo_storage_vs_icloud_photos_for)
 - RSS feed: $source
 - date published: 2024-09-26T17:09:28+00:00

<!-- SC_OFF --><div class="md"><p>I’ve heard of and looked up plenty of ways to store photos on NAS devices and locally, but most of them seem to be very focused on one user. I’m planning on getting married in the next 6 months, and I’d like to nail down a solution for photo storage and device backups that works for both myself and my fiancée long term. Both of us use mostly Apple devices (with a little bit of Linux on my end and Windows on hers), so the ideal option would be seamless on iOS and macOS.</p> <p>iCloud works well for this and is by far the easiest option, but not having my data accessible locally and having a permanent subscription to pay for is a bit annoying. I have a DAS connected to a Mac Mini that works well, but I’m unsure if that’s the best option for something like this long term. I suppose the advantage is I can move an Apple Photos library to the DAS, but I’m not sure if it can be made accessible from an iPhone too. I’m also considering something like a Synolog

## Old game PC or buy a server [Sepcs and info included]
 - [https://www.reddit.com/r/selfhosted/comments/1fq16kw/old_game_pc_or_buy_a_server_sepcs_and_info](https://www.reddit.com/r/selfhosted/comments/1fq16kw/old_game_pc_or_buy_a_server_sepcs_and_info)
 - RSS feed: $source
 - date published: 2024-09-26T17:02:01+00:00

<!-- SC_OFF --><div class="md"><p>I have a leftover game PC that I use now as a server sort of.... I wanna restart and build my server stuff in a better way. I thought of selling the PC but it seems like a waste with the amout I could get for it if I sell it. So I am on the fence about selling it. Should I keep using the PC or just sell it and just buy a server?</p> <p>Havent been in the &quot;PC world&quot; for a while now so hoping for advice.</p> <p>things a wanna do</p> <ul> <li>run couple VM&#39;s</li> <li>Media/jelly (books, pics, movies etc.)</li> <li>some game servers for my family</li> <li>general file storage</li> <li>future self host projects</li> </ul> <p>PC specs: (runs windows 11 now)<br/> - I9 9900K<br/> - GTX 2080 TRIO<br/> - 16 GB RAM 32000 HZm<br/> - 9TB HDD storage<br/> - 1 TB SSD storage</p> <p>Need more storage already.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/exparsioz2"> /u/exparsioz2 </a> <br/> <span><a href="https:

## Netbird help with split tunneling
 - [https://www.reddit.com/r/selfhosted/comments/1fq13jb/netbird_help_with_split_tunneling](https://www.reddit.com/r/selfhosted/comments/1fq13jb/netbird_help_with_split_tunneling)
 - RSS feed: $source
 - date published: 2024-09-26T16:58:43+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I’m testing out the Netbird app on my Android phone ( lets call NB1) and have set up my Linux machine (NB2) as an exit node to connect to services within my LAN. Here’s what I’m trying to achieve:</p> <ul> <li>I want to route traffic to a specific internal service (e.g., <a href="http://service.example.com"><code>service.example.com</code></a>, hosted on a LAN ) through my Linux machine (NB2) as the exit node.</li> <li>For all other traffic (e.g., reddit.com), I want to bypass the exit node and go directly through the device’s internet connection (using split tunneling?).</li> </ul> <p>Additionally, I’m running Pi-hole as my local DNS server on my LAN, and I’ve configured Netbird DNS to use the Pi-hole IP as the DNS server for all devices connected to the Netbird network.</p> <p>I’m having trouble finding an option to set specific routes or enable split tunneling. Has anyone else set up a similar configuration or have any tips for

## Google Workspace App Password no longer working
 - [https://www.reddit.com/r/selfhosted/comments/1fq0zsc/google_workspace_app_password_no_longer_working](https://www.reddit.com/r/selfhosted/comments/1fq0zsc/google_workspace_app_password_no_longer_working)
 - RSS feed: $source
 - date published: 2024-09-26T16:54:09+00:00

<!-- SC_OFF --><div class="md"><p>Does anyone have any suggested solutions as Google is turning off App Passwords for workspace accounts. I can either use something like mailgun or find and configure an SMTP relay service. Anything I am missing or suggestions. If you are running into similar and just want to vent I am ok with that too. Lets be upset together.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dominionman"> /u/dominionman </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq0zsc/google_workspace_app_password_no_longer_working/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq0zsc/google_workspace_app_password_no_longer_working/">[comments]</a></span>

## FreshRSS with Full Text View
 - [https://www.reddit.com/r/selfhosted/comments/1fq0z19/freshrss_with_full_text_view](https://www.reddit.com/r/selfhosted/comments/1fq0z19/freshrss_with_full_text_view)
 - RSS feed: $source
 - date published: 2024-09-26T16:53:14+00:00

<!-- SC_OFF --><div class="md"><p>I just setup FreshRSS and want to be able to see the full artice in FreshRSS. Right now it only shows a small part of the article. Is there maybe an exstension or another way?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Space_v2"> /u/Space_v2 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq0z19/freshrss_with_full_text_view/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fq0z19/freshrss_with_full_text_view/">[comments]</a></span>

## Issues while running GOW
 - [https://www.reddit.com/r/selfhosted/comments/1fpzykl/issues_while_running_gow](https://www.reddit.com/r/selfhosted/comments/1fpzykl/issues_while_running_gow)
 - RSS feed: $source
 - date published: 2024-09-26T16:10:30+00:00

<!-- SC_OFF --><div class="md"><p>After Connecting using Moonlight client </p> <p>1)Sometimes while starting steam , the display freezes and need to close and reconnect to steam from moonlight.</p> <p>2)In steam setup , wired connection is failing and internet access is not available.</p> <p>Please help</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/EntertainmentKey1261"> /u/EntertainmentKey1261 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpzykl/issues_while_running_gow/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpzykl/issues_while_running_gow/">[comments]</a></span>

## VPS website with Cloudflare but still accesible through raw IP. Is it insecure? How to fix?
 - [https://www.reddit.com/r/selfhosted/comments/1fpzl0d/vps_website_with_cloudflare_but_still_accesible](https://www.reddit.com/r/selfhosted/comments/1fpzl0d/vps_website_with_cloudflare_but_still_accesible)
 - RSS feed: $source
 - date published: 2024-09-26T15:54:59+00:00

<!-- SC_OFF --><div class="md"><p>So basically I got a VPS serving a website and Cloudflare in front of it. However, when I enter the raw IP, it still serves me the website too.</p> <p>Is this insecure? I guess it should be because this is bypassing Cloudflare right?</p> <p>How can I fix this? This is my config file</p> <pre><code>events {} http { gzip on; gzip_min_length 1000; gzip_types text/plain text/css application/json application/javascript text/xml application/xml application/xml+rss text/javascript; gzip_vary on; gzip_proxied any; gzip_disable &quot;msie6&quot;; server_tokens off; charset utf-8; server { listen 80; server_name mydomain.com www.mydomain.com; return 301 https://$host$request_uri; } server { listen 443 ssl; server_name mydomain.com www.mydomain.com; ssl_certificate /etc/letsencrypt/live/mydomain.com/fullchain.pem; ssl_certificate_key /etc/letsencrypt/live/mydomain.com/privkey.pem; location / { proxy_pass http://app:8080; proxy_set_header Host $host; proxy_set_he

## Old windows desktop as a server
 - [https://www.reddit.com/r/selfhosted/comments/1fpzcda/old_windows_desktop_as_a_server](https://www.reddit.com/r/selfhosted/comments/1fpzcda/old_windows_desktop_as_a_server)
 - RSS feed: $source
 - date published: 2024-09-26T15:44:47+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fpzcda/old_windows_desktop_as_a_server/"> <img src="https://b.thumbs.redditmedia.com/dNliOyMH8RnSCjNsone7XNbce86IP4_WXL_K1KOUn9U.jpg" alt="Old windows desktop as a server" title="Old windows desktop as a server" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>So before I jump into a serious sever, I want to try it out on my old desktop. I am wondering if the capacity is enough. It will probably host some fediverse apps, blogging and for cloud storage only. </p> <p>I&#39;m thinking to run unbuntu.</p> <p><a href="https://preview.redd.it/yxn1k7r3c6rd1.png?width=343&amp;format=png&amp;auto=webp&amp;s=bf7571f0a13f65913089e15a3723d9d8cda282ac">https://preview.redd.it/yxn1k7r3c6rd1.png?width=343&amp;format=png&amp;auto=webp&amp;s=bf7571f0a13f65913089e15a3723d9d8cda282ac</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok_Opposite753"> /u/Ok_Opposite753 </a> <br/> <span><a hr

## Sharing of Cookbook Databases?
 - [https://www.reddit.com/r/selfhosted/comments/1fpz30s/sharing_of_cookbook_databases](https://www.reddit.com/r/selfhosted/comments/1fpz30s/sharing_of_cookbook_databases)
 - RSS feed: $source
 - date published: 2024-09-26T15:33:53+00:00

<!-- SC_OFF --><div class="md"><p>Hi All, </p> <p>So, I know this is a bit of weird discussion for this page, but I thought since people on this sub would know what I was talking about this was a better place to start then <a href="/r/Cooking">r/Cooking</a> or similar. </p> <p>I recently migrated from Mealie to Tandoor Recipes, and that got me to thinking...is there a place where people share their recipe backups? Importing 10s or 100s of recipes would be awesome instead of everyone building an individual collection one at a time. </p> <p>Thanks! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/khantroll1"> /u/khantroll1 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpz30s/sharing_of_cookbook_databases/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpz30s/sharing_of_cookbook_databases/">[comments]</a></span>

## PyPDFForm - A Python PDF Form Library
 - [https://www.reddit.com/r/selfhosted/comments/1fpy6rj/pypdfform_a_python_pdf_form_library](https://www.reddit.com/r/selfhosted/comments/1fpy6rj/pypdfform_a_python_pdf_form_library)
 - RSS feed: $source
 - date published: 2024-09-26T14:56:54+00:00

<!-- SC_OFF --><div class="md"><p>Hello folks! Earlier this year I shared an open source project I have been working on for four years at a couple other subs and got some very positive feedbacks so I&#39;d love to share it here too. It is a Python library that specializes in processing PDF forms, with the most outstanding feature being programmatically filling a PDF form by simply feeding a Python dictionary.</p> <p>I used to work at a startup company with Python as our backend stack. We were constantly given paper documents by our clients that we needed to generate into PDFs. We were doing it using reportlab scripts and I quickly found the process tedious and time consuming for more complex PDFs.</p> <p>This is where the idea of this project came from. Instead of writing lengthy and unmaintainable reportlab scripts to generate PDFs, you can just turn any paper document into a PDF form template and PyPDFForm can fill it easily.</p> <p>Ever since the last time I shared it, I made some 

## I'm looking for a selhosted application that we could use in our team to sell privately soccer shoes of our kids. It would be for the club where parents can offer old soccer clothes. I've searched the internet for any available docker but could not find anything.
 - [https://www.reddit.com/r/selfhosted/comments/1fpxux9/im_looking_for_a_selhosted_application_that_we](https://www.reddit.com/r/selfhosted/comments/1fpxux9/im_looking_for_a_selhosted_application_that_we)
 - RSS feed: $source
 - date published: 2024-09-26T14:42:43+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/BraKo80"> /u/BraKo80 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpxux9/im_looking_for_a_selhosted_application_that_we/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpxux9/im_looking_for_a_selhosted_application_that_we/">[comments]</a></span>

## How do they refurbish drives?
 - [https://www.reddit.com/r/selfhosted/comments/1fpxlj8/how_do_they_refurbish_drives](https://www.reddit.com/r/selfhosted/comments/1fpxlj8/how_do_they_refurbish_drives)
 - RSS feed: $source
 - date published: 2024-09-26T14:31:20+00:00

<!-- SC_OFF --><div class="md"><p>i&#39;ve bought a refurbished drive for a fraction of the cost of a new unit and checking with crystaldisk i&#39;ve seen it&#39;s basically new. the exterior has a slight dent but according to the s.m.a.r.t it&#39;s as good as the ones i got brand new and used for a year. </p> <p>i&#39;ve checked a couple videos and seen some people also got a brand new drive when buying refurbished (according to SMART). some say the manufacturer can reset the SMART but wouldn&#39;t that still show bad sectors and such again?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/iCujoDeSotta"> /u/iCujoDeSotta </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpxlj8/how_do_they_refurbish_drives/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpxlj8/how_do_they_refurbish_drives/">[comments]</a></span>

## I uninstalled and reinstalled python on my debian server and now my password looks incorrect when I connect to it via ssh, help
 - [https://www.reddit.com/r/selfhosted/comments/1fpxb5t/i_uninstalled_and_reinstalled_python_on_my_debian](https://www.reddit.com/r/selfhosted/comments/1fpxb5t/i_uninstalled_and_reinstalled_python_on_my_debian)
 - RSS feed: $source
 - date published: 2024-09-26T14:18:40+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>Backstory : tried to install ansible-matrix-docker-deploy mutliples times, failed multiples times for a few hours, wanted then to throw it up and give up on it, started uninstalling everything related to the project. </p> <p>Eventually uninstalled python in order to reinstall it thinking it would clean all the pip/pipx programs, it didn&#39;t. And after rebooting, I am away from home, trying to connect via ssh and all I get is : &quot;Permission denied, try again.&quot;</p> <p>Is there a known fix ? (if this is even a known issue :/ )</p> <p>All I remember is apt removing python3 python-something packages and then just resintalling python3, then I restarted and didn&#39;t touch it until today. It is maybe important to say that everything is running fine (all docker images), only ssh looks like i&#39;ts been broken in some way.</p> <p>Thanks for any help</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.c

## OCIS compose file
 - [https://www.reddit.com/r/selfhosted/comments/1fpwi95/ocis_compose_file](https://www.reddit.com/r/selfhosted/comments/1fpwi95/ocis_compose_file)
 - RSS feed: $source
 - date published: 2024-09-26T13:43:01+00:00

<!-- SC_OFF --><div class="md"><p>Anyone have a working docker compose file for OCIS? I don&#39;t need ldap or traefik, I would like to have the ability to open office docs. Thanks for any help.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Squanchy2112"> /u/Squanchy2112 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpwi95/ocis_compose_file/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpwi95/ocis_compose_file/">[comments]</a></span>

## Route all traffic through a VPS?
 - [https://www.reddit.com/r/selfhosted/comments/1fpwhb9/route_all_traffic_through_a_vps](https://www.reddit.com/r/selfhosted/comments/1fpwhb9/route_all_traffic_through_a_vps)
 - RSS feed: $source
 - date published: 2024-09-26T13:41:46+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I am in a pickle, one of my proxmox servers is stranded - it has access to full gigabit up and down but resides on a network that I have absolutely no control over. So no port opening, no nothing (and there&#39;s no &quot;asking nicely for access - the guy is a control freak as a way to make the owners pay up for his expertise)</p> <p>I now have to figure out a way to route quite a few bandwidth-heavy services straight to that isolated server.</p> <p>My brain tells me &quot;use a VPS and route through a VPN&quot; - but as we all know nothing is simple, even more so when we&#39;re talking about networking, there&#39;ll always be that one &quot;small detail&quot;</p> <p>As such I thought that I&#39;d first hit the subredit for advice. How would you guys do it ? Tailscale isn&#39;t an option given the load - a paid VPS as a router is <sup>^</sup></p> <p>Many thanks in advance ;)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a 

## file sharing help
 - [https://www.reddit.com/r/selfhosted/comments/1fpwfxx/file_sharing_help](https://www.reddit.com/r/selfhosted/comments/1fpwfxx/file_sharing_help)
 - RSS feed: $source
 - date published: 2024-09-26T13:40:02+00:00

<!-- SC_OFF --><div class="md"><p>For a jellyfin server (running in a proxmox mesh) should i use truenas in hyper-v or windows share be ok?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/theannihilator"> /u/theannihilator </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpwfxx/file_sharing_help/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpwfxx/file_sharing_help/">[comments]</a></span>

## What do you think is the most middle of the road setup?
 - [https://www.reddit.com/r/selfhosted/comments/1fpw82v/what_do_you_think_is_the_most_middle_of_the_road](https://www.reddit.com/r/selfhosted/comments/1fpw82v/what_do_you_think_is_the_most_middle_of_the_road)
 - RSS feed: $source
 - date published: 2024-09-26T13:29:47+00:00

<!-- SC_OFF --><div class="md"><p>Here&#39;s my take:</p> <ul> <li>SFF (Small Form Factor) PC</li> <li>DAS (Direct Attached Storage) for storage</li> <li>Docker running on Debian <ul> <li>Tailscale for remote access</li> <li>AudiobookShelf for books</li> <li>Jellyfin for audio/video</li> <li>Immich for photos</li> <li>*arr suite for automation</li> </ul></li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Zestyclose_Car1088"> /u/Zestyclose_Car1088 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpw82v/what_do_you_think_is_the_most_middle_of_the_road/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpw82v/what_do_you_think_is_the_most_middle_of_the_road/">[comments]</a></span>

## AI generated subtitles in multiple languages
 - [https://www.reddit.com/r/selfhosted/comments/1fpw1tk/ai_generated_subtitles_in_multiple_languages](https://www.reddit.com/r/selfhosted/comments/1fpw1tk/ai_generated_subtitles_in_multiple_languages)
 - RSS feed: $source
 - date published: 2024-09-26T13:21:39+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>Just trying my luck here. I&#39;d tried several options but failed missarable multiple times. I&#39;m looking for a selfhosted solution and I can&#39;t imagine to be the only one on the entire internet who is looking for this.</p> <p>My case: I&#39;m selfhosting some media (Sonarr, Radarr, Jellyfin and so on) for myself. After using almost every streaming service available in my country there are still some movies and series I would like to watch. But, that is not the issue. The series (mostly older) are from times there were no embedded subtitles in mkv-files and therefore im using several subtitle-platforms to download srt-files. Not all that succesfull. I&#39;m currently downloading out-of-sync (in-correctable), incomplete or just wrong subtitles.</p> <p>I&#39;m looking for a tool (probable AI, like Whisper) that can generate audio-to-text (srt)-files, so i can load them in Jellyfin, when playing video. This would be even better if t

## Fresh install nginx-proxy-manager with portainer doesn't work
 - [https://www.reddit.com/r/selfhosted/comments/1fpv8dt/fresh_install_nginxproxymanager_with_portainer](https://www.reddit.com/r/selfhosted/comments/1fpv8dt/fresh_install_nginxproxymanager_with_portainer)
 - RSS feed: $source
 - date published: 2024-09-26T12:42:05+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I&#39;m a mobila application developer and I&#39;ve been using appwrite which is a BAAS for my applications together with portainer. Appwrite was using traefik and portainer honestly IDK what is using but I was in need to host other websites and subdomains for different purposes. I found that nginx proxy manager has a very nice UI and handles the certificate through letsencrypt which is nice.</p> <p>The problem is, I&#39;ve tried to install nginx proxy manager and portainer using this <a href="https://docs.portainer.io/advanced/reverse-proxy/nginx">tutorial</a></p> <p>Everything went smooth, the problem is that I get the following error whenever I&#39;m trying to access port 81, or default address, either domain, local ip, public ip etc.</p> <p>The error is:</p> <p><strong>nginx.1 | 2024/09/26 12:26:04 [error] 31#31: *1226 cannot load certificate &quot;data:&quot;: PEM_read_bio_X509_AUX() failed (SSL: error:0480006C:PEM routines::no star

## What are your pain points using Coolify/CapRover/Dockploy?
 - [https://www.reddit.com/r/selfhosted/comments/1fpv20v/what_are_your_pain_points_using](https://www.reddit.com/r/selfhosted/comments/1fpv20v/what_are_your_pain_points_using)
 - RSS feed: $source
 - date published: 2024-09-26T12:33:01+00:00

<!-- SC_OFF --><div class="md"><p>Hi there,</p> <p>Lots of us are using one or another tool to deploy our services (or self-host some for our personal needs).</p> <ul> <li>Have you noticed any performance issues, especially when dealing with larger applications or high traffic?</li> <li>How well does [Coolify/CapRover/Dockploy] handle scaling your applications up or down as needed?</li> <li>Do you find the platform&#39;s interface or configuration options overly complex or difficult to use?</li> <li>Are there any specific features you wish were included in [Coolify/CapRover/Dockploy]?</li> <li>How has your experience been with the platform&#39;s community support or official documentation?</li> </ul> <p>Please share your thoughts and experiences. Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bohdan-shulha"> /u/bohdan-shulha </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpv20v/what_are_your_pain_points_using/

## Containerize Dotnet
 - [https://www.reddit.com/r/selfhosted/comments/1fpv00w/containerize_dotnet](https://www.reddit.com/r/selfhosted/comments/1fpv00w/containerize_dotnet)
 - RSS feed: $source
 - date published: 2024-09-26T12:30:14+00:00

<!-- SC_OFF --><div class="md"><p>Good morning everyone!</p> <p>I was wondering if there is a way to containerize Dotnet so I can build C# apps through it. I am aware of the standard Dotnet compose file, but im kind of looking for maybe a webui to build it, if that makes sense. Please let me know if there is something out there.</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Editz7"> /u/Editz7 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpv00w/containerize_dotnet/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpv00w/containerize_dotnet/">[comments]</a></span>

## Tailscale routed through Gluetun vpn is very slow
 - [https://www.reddit.com/r/selfhosted/comments/1fpux66/tailscale_routed_through_gluetun_vpn_is_very_slow](https://www.reddit.com/r/selfhosted/comments/1fpux66/tailscale_routed_through_gluetun_vpn_is_very_slow)
 - RSS feed: $source
 - date published: 2024-09-26T12:26:06+00:00

<!-- SC_OFF --><div class="md"><p>Here is a <a href="https://imgur.com/a/qEf188S">diagram</a> I&#39;ve made to the best of my abilities<br/> TL;DR: Tailscale container (exit node) routes its traffic through a Gluetun vpn container, but when using the exit node, bandwidth towards the internet is extremely slow ( less than 5MBps ).</p> <p>Gluetun is configured to use a TorGuard VPN server with wireguard, with the entire wg config provided directly by the Torguard config generator (I tried using OpenVPN but the results were even worse), this is my wg0.conf:</p> <pre><code>[Interface] PrivateKey = {private key} ListenPort = 54297 MTU = 1390 DNS = 1.1.1.1 Address = 10.XX.XX.XXX/24 [Peer] PublicKey = {public key} AllowedIPs = 0.0.0.0/0 Endpoint = {endpoint ip}:1443 PersistentKeepalive = 25 </code></pre> <p>And this is my compose file:</p> <pre><code>version: &quot;3&quot; services: gluetun-tailscale: image: qmcgaw/gluetun cap_add: - NET_ADMIN environment: - VPN_SERVICE_PROVIDER=custom - VPN

## 2024 Self-Host User Survey (selfh.st)
 - [https://www.reddit.com/r/selfhosted/comments/1fpufsc/2024_selfhost_user_survey_selfhst](https://www.reddit.com/r/selfhosted/comments/1fpufsc/2024_selfhost_user_survey_selfhst)
 - RSS feed: $source
 - date published: 2024-09-26T12:00:24+00:00

<!-- SC_OFF --><div class="md"><p>Hey, <a href="/r/selfhosted">r/selfhosted</a>!</p> <p>Building on the tradition I started <a href="https://selfh.st/survey/2023-results/">last year</a>, I&#39;ve launched the 2024 Self-Host User Survey to capture self-hosted habits, preferences, and behaviors across several different question categories.</p> <p><a href="https://selfh.st/survey/2024/">2024 Self-Host User Survey</a></p> <p>I&#39;m appreciative of the feedback I received from this community last year and have made some changes and improvements based on it. Notably, I&#39;ve switched to the self-hosted form builder HeyForm, which easily allows me to capture values for &#39;Other&#39; responses when I&#39;m unable to list all possible values. (Disclaimer: The HeyForm team is also sponsoring this year&#39;s survey, but this did not influence my decision to switch to their platform.)</p> <p>I&#39;m more than happy to take additional feedback for next year&#39;s survey (feel free to post belo

## SSD Nodes
 - [https://www.reddit.com/r/selfhosted/comments/1fpu6uy/ssd_nodes](https://www.reddit.com/r/selfhosted/comments/1fpu6uy/ssd_nodes)
 - RSS feed: $source
 - date published: 2024-09-26T11:46:15+00:00

<!-- SC_OFF --><div class="md"><p>Anyone here using SSD nodes? Howd the experience?</p> <p><a href="https://www.ssdnodes.com/">https://www.ssdnodes.com/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Disastrous-Ad-5003"> /u/Disastrous-Ad-5003 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpu6uy/ssd_nodes/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpu6uy/ssd_nodes/">[comments]</a></span>

## Best Indexer for eBooks/Audiobooks?
 - [https://www.reddit.com/r/selfhosted/comments/1fptu6n/best_indexer_for_ebooksaudiobooks](https://www.reddit.com/r/selfhosted/comments/1fptu6n/best_indexer_for_ebooksaudiobooks)
 - RSS feed: $source
 - date published: 2024-09-26T11:25:23+00:00

<!-- SC_OFF --><div class="md"><p>Title. I&#39;ve been checking stuff out but what I&#39;ve got currently for Usenet isn&#39;t so great for it. What files are available fail more frequently than most others. They&#39;re great for video, but that&#39;s it, apparently.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Senkyou"> /u/Senkyou </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fptu6n/best_indexer_for_ebooksaudiobooks/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fptu6n/best_indexer_for_ebooksaudiobooks/">[comments]</a></span>

## Best solution for docker container notifications
 - [https://www.reddit.com/r/selfhosted/comments/1fptssk/best_solution_for_docker_container_notifications](https://www.reddit.com/r/selfhosted/comments/1fptssk/best_solution_for_docker_container_notifications)
 - RSS feed: $source
 - date published: 2024-09-26T11:22:56+00:00

<!-- SC_OFF --><div class="md"><p>Is anyone doing anything in regards to your docker containers sending you notifications for certain events?</p> <p>I have a few important containers that I&#39;d like to get notified about if a restart occurs. But the options seem to be limited.</p> <p>I run Portainer, and apparently Portainer has no email notification feature.</p> <p>I guess the other option would be to modify every image I need to use, and have it automatically install sendmail into the container and then maybe run it from the container itself? But migrating simple images over to a Dockerfile would be a pain if it&#39;s more than just a few.</p> <p>I took a look at the Dozzle but someone requested this feature and the developers said that Dozzle is more focused on live logs, and are only monitoring when the UI is open.</p> <p>Anyone have any ideas behind the best way to implement this? Unless I&#39;m just missing the golden gem somewhere, it really seems like monitoring docker itsel

## Trying to access Jellyfin via Nginx
 - [https://www.reddit.com/r/selfhosted/comments/1fptsr0/trying_to_access_jellyfin_via_nginx](https://www.reddit.com/r/selfhosted/comments/1fptsr0/trying_to_access_jellyfin_via_nginx)
 - RSS feed: $source
 - date published: 2024-09-26T11:22:51+00:00

<!-- SC_OFF --><div class="md"><p>I have a Jellyfin server and I would like to be able to access it with a URL instead of having to connect my VPN everytime I want to watch something outside of the house. </p> <p>I have my personal domain, with an A record to jellyfin; so the URL <a href="https://jellyfin.mydomain.co.uk">https://jellyfin.mydomain.co.uk</a> exists and Nginx can forward to http://internalip:8096</p> <p>This works outside of my network but it shows a screen asking to select a server and I can&#39;t get passed it, because the computer it not on my home network. </p> <p>Is there a way to automatically go to the login screen for my jellyfin server?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sway_RL"> /u/Sway_RL </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fptsr0/trying_to_access_jellyfin_via_nginx/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fptsr0/trying_to_acce

## How to set up a torrent client for remote access on my home server?
 - [https://www.reddit.com/r/selfhosted/comments/1fpt11z/how_to_set_up_a_torrent_client_for_remote_access](https://www.reddit.com/r/selfhosted/comments/1fpt11z/how_to_set_up_a_torrent_client_for_remote_access)
 - RSS feed: $source
 - date published: 2024-09-26T10:32:17+00:00

<!-- SC_OFF --><div class="md"><p>Not quite sure if this is the place to ask but I couldn&#39;t think of anywhere else that was an active sub. If you know a better place to post this, tell me so.</p> <p>Im just getting into the whole self hosting thing, and I wanted to get my torrents off my main computer and onto an old laptop im using as a server. I just wanted some client that i can manage with a TUI over SSH or remotely with a WebUI.<br/> I looked around on the internet and it seems that everyone recommends either rTorrent or Transmission. I couldnt find any up to date info on how to actually configure rTorrent and I cant figure it out on my own because its set up via a config file. So I decided to use transmission because of its WebUI, should be simple enough. However the documentation is 16 years!!! out of date and i cant find more than just screenshots of the GTK UI being used to start a WebUI. This is a headless server, so thats not an option, and simply running &quot;transmis

## Create an running a forum with automatic translation
 - [https://www.reddit.com/r/selfhosted/comments/1fpssqc/create_an_running_a_forum_with_automatic](https://www.reddit.com/r/selfhosted/comments/1fpssqc/create_an_running_a_forum_with_automatic)
 - RSS feed: $source
 - date published: 2024-09-26T10:16:34+00:00

<!-- SC_OFF --><div class="md"><p>Hi Guys,</p> <p>first of all: Thank you so much for all your threads and help where I (as a noob in IT) learned so much and decided to start my own homelab just because of the Reddit community!</p> <p>I am thinking about to start and host forum with with automatic translations, were people from different countries can connect to coordinate animal rescues and sharing their information about collaborations with compannies etc for getting steady inflows for their kennels etc.</p> <p>I would appreciate if you would give me some hints / advices if you have any ideas which open source app could be the best and which cheap or free translation tool could be a good fit.</p> <p>German, English and Spanish would be enough for the first months...</p> <p>Thanks a lot for any ideas! I am a It noob and just start hosting a personal website (Cloudpanel), storage (Nextcloud), with cloudflared connections on Ubuntu. So you can imagine how little I know at the moment.</

## For those who use Cloudflare
 - [https://www.reddit.com/r/selfhosted/comments/1fps0e5/for_those_who_use_cloudflare](https://www.reddit.com/r/selfhosted/comments/1fps0e5/for_those_who_use_cloudflare)
 - RSS feed: $source
 - date published: 2024-09-26T09:19:41+00:00

<!-- SC_OFF --><div class="md"><h1>Cloudflare Zones Settings Automation</h1> <p>Hello flared users :)</p> <p>For those who match use cases like:</p> <ul> <li>not using terraform</li> <li>using dnscontrol then still no terraform</li> <li>hate terraform or dont want to use it to manage cloudflare resources</li> </ul> <p>... but still want a simple way to manage zone settings for multiple domains/zones..</p> <p>I built a simple project to let you automatically manage and deploy zone settings across multiple zones by using GitHub Actions (or any other CI/CD capable tool) named Flared:</p> <h1>Core Features</h1> <ul> <li><strong>Multi-Domain Support</strong>: Manage multiple Cloudflare zones/domains from a single configuration file.</li> <li><strong>Default Configurations</strong>: Define default settings that apply to all zones, with the ability to override them for specific domains.</li> <li><strong>Customization</strong>: Tailor settings like SSL/TLS versions, HTTP/3, Rocket Loader, Bro

## Paperless - Support
 - [https://www.reddit.com/r/selfhosted/comments/1fpr8yw/paperless_support](https://www.reddit.com/r/selfhosted/comments/1fpr8yw/paperless_support)
 - RSS feed: $source
 - date published: 2024-09-26T08:19:04+00:00

<!-- SC_OFF --><div class="md"><p>Good Morning,<br/> I am looking for a company that provides support for Paperless NGX, preferably an Italian one. Do you know of any?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Separate_Progress158"> /u/Separate_Progress158 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpr8yw/paperless_support/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpr8yw/paperless_support/">[comments]</a></span>

## Install custom plugins on jgraph/drawio
 - [https://www.reddit.com/r/selfhosted/comments/1fpqrjp/install_custom_plugins_on_jgraphdrawio](https://www.reddit.com/r/selfhosted/comments/1fpqrjp/install_custom_plugins_on_jgraphdrawio)
 - RSS feed: $source
 - date published: 2024-09-26T07:40:57+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,<br/> has anyone managed to install custom plugins on their <a href="http://Draw.io">Draw.io</a> instance? I have copied my .js plugin to /usr/local/tomcat/webapps/draw/plugins, but it doesn&#39;t show up in the plugin list.<br/> Best Regards, Shahram</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sh4hr4m"> /u/sh4hr4m </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpqrjp/install_custom_plugins_on_jgraphdrawio/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpqrjp/install_custom_plugins_on_jgraphdrawio/">[comments]</a></span>

## accessing services hosted on macos using vpn server
 - [https://www.reddit.com/r/selfhosted/comments/1fpqr6t/accessing_services_hosted_on_macos_using_vpn](https://www.reddit.com/r/selfhosted/comments/1fpqr6t/accessing_services_hosted_on_macos_using_vpn)
 - RSS feed: $source
 - date published: 2024-09-26T07:40:09+00:00

<!-- SC_OFF --><div class="md"><p>I have a wireguard server running in pi, and a macos running ollama in the same network. I am trying to access the services in macos but using wireguard vpn client from outside of the network, but those services in macos aren&#39;t accessible for some reason.</p> <p>However other services running on different servers are accessible.</p> <p>Is there some configuration I am missing ??</p> <p>does services like Continuity, Homebridge (Remote) work using vpn tunneling ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/r4nchy"> /u/r4nchy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpqr6t/accessing_services_hosted_on_macos_using_vpn/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpqr6t/accessing_services_hosted_on_macos_using_vpn/">[comments]</a></span>

## Easiest way to have GPU passthrough?
 - [https://www.reddit.com/r/selfhosted/comments/1fpqqjz/easiest_way_to_have_gpu_passthrough](https://www.reddit.com/r/selfhosted/comments/1fpqqjz/easiest_way_to_have_gpu_passthrough)
 - RSS feed: $source
 - date published: 2024-09-26T07:38:49+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fpqqjz/easiest_way_to_have_gpu_passthrough/"> <img src="https://a.thumbs.redditmedia.com/7CJ5HHCw37CzAERYUd5CgGeMJdVYdThcZBRrnnpJq-4.jpg" alt="Easiest way to have GPU passthrough?" title="Easiest way to have GPU passthrough?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Please rank the following strategies from 1 (most difficult) to 5 (easiest):</p> <ul> <li>VMware</li> <li>Proxmox</li> <li>EasgyGPU (I tried without a Windows VM and failed)</li> <li>WSL2. 5 for me, it required like 3 clicks: </li> </ul> <p><a href="https://preview.redd.it/zxlelbo204rd1.png?width=767&amp;format=png&amp;auto=webp&amp;s=28682d626a4e2ef3d9fd1004fd220685333d139b">https://preview.redd.it/zxlelbo204rd1.png?width=767&amp;format=png&amp;auto=webp&amp;s=28682d626a4e2ef3d9fd1004fd220685333d139b</a></p> <ul> <li>unRaid </li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/F041"> /u/F041 </a> <br

## Transcription of interview to memoirs
 - [https://www.reddit.com/r/selfhosted/comments/1fpqik7/transcription_of_interview_to_memoirs](https://www.reddit.com/r/selfhosted/comments/1fpqik7/transcription_of_interview_to_memoirs)
 - RSS feed: $source
 - date published: 2024-09-26T07:21:57+00:00

<!-- SC_OFF --><div class="md"><p>I have a large block of text transcribed from an interview that I&#39;d like turned into memoirs</p> <p>Does anyone know of a self hosted LLM that can do it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ithakaa"> /u/ithakaa </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpqik7/transcription_of_interview_to_memoirs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpqik7/transcription_of_interview_to_memoirs/">[comments]</a></span>

## Web and Android app to catalogue movies, shows, music
 - [https://www.reddit.com/r/selfhosted/comments/1fpqaye/web_and_android_app_to_catalogue_movies_shows](https://www.reddit.com/r/selfhosted/comments/1fpqaye/web_and_android_app_to_catalogue_movies_shows)
 - RSS feed: $source
 - date published: 2024-09-26T07:05:43+00:00

<!-- SC_OFF --><div class="md"><p>Do you know any web app to catalogue films and TV shows, and maybe more like music, books and games?</p> <p>It would be great with an integration with IMDB. I would also need to specify where the title is stored, like on which disk. Better if it has an Android app too.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/IndependentThink1590"> /u/IndependentThink1590 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpqaye/web_and_android_app_to_catalogue_movies_shows/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpqaye/web_and_android_app_to_catalogue_movies_shows/">[comments]</a></span>

## Raspberry or alternative for business
 - [https://www.reddit.com/r/selfhosted/comments/1fpphcw/raspberry_or_alternative_for_business](https://www.reddit.com/r/selfhosted/comments/1fpphcw/raspberry_or_alternative_for_business)
 - RSS feed: $source
 - date published: 2024-09-26T06:04:56+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I&#39;m a dev for a starting company and we want to launch a website with some backend computation, nothing too heavy but it&#39;s more than simple html page delivery. It would be for a few thousands user, a million at most per month. It is ok to self host on one or more raspberry pi ? I know you can&#39;t answer precisely without more information but is there a limit I will face in term of performance for connection or CPU ? Which one first </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/NoahZhyte"> /u/NoahZhyte </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpphcw/raspberry_or_alternative_for_business/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpphcw/raspberry_or_alternative_for_business/">[comments]</a></span>

## NextCloud vs SFTPGo for WebDAV for fast Obsidian Remotely Save syncing
 - [https://www.reddit.com/r/selfhosted/comments/1fpph6p/nextcloud_vs_sftpgo_for_webdav_for_fast_obsidian](https://www.reddit.com/r/selfhosted/comments/1fpph6p/nextcloud_vs_sftpgo_for_webdav_for_fast_obsidian)
 - RSS feed: $source
 - date published: 2024-09-26T06:04:38+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m currently using NextCloud&#39;s WebDAV and it takes about 30 seconds to sync using the Remotely Save plugin. For reference, I have ~200 tiny files in my vault so far, will definitely have much more in the future.</p> <p>I read from a recent post here that NC is very slow (I&#39;m using the NC AIO running on a RPi4b with 4GB of RAM without any plugins) so maybe someone else here is using a different Obsidian Remotely Save service and has better luck with the sync speeds? MinIO maybe? SFTPGo? I like using NC because I can edit my notes using the NC notes web interface and it&#39;ll automatically sync back to Obsidian later.</p> <p>Alternatively, are there ways for me to speed up the sync while still using NC? I can move the docker container to another server (i5 6200 with 12GB of RAM) but it&#39;s running Windows so WSL will need to be involved. Would that slow things down? </p> <p>ps: The internet speed on the RPi is a bit faster than the windo

## What's the simplest authentication server that supports traefik forward auth?
 - [https://www.reddit.com/r/selfhosted/comments/1fpojzy/whats_the_simplest_authentication_server_that](https://www.reddit.com/r/selfhosted/comments/1fpojzy/whats_the_simplest_authentication_server_that)
 - RSS feed: $source
 - date published: 2024-09-26T05:01:03+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been trying to find a good and simple authentication server for my apps that has a nice looking UI but nothing satisfies me. Authelia is config based and their login screen is trash, it looks like a 2015 login screen, authentik is good but it requires a billion services to run (worker, redis, db, dash), keycloack seems good but with their example I couldn&#39;t even log in (it was saying it can&#39;t store the cookie but every other service can) and every other app is just too complex to work with traefik. So is there a tiny authentication server that requires just a container (and db if needed) and has a decent UI?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/steveiliop56"> /u/steveiliop56 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpojzy/whats_the_simplest_authentication_server_that/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fp

## Help me configure?
 - [https://www.reddit.com/r/selfhosted/comments/1fpntvg/help_me_configure](https://www.reddit.com/r/selfhosted/comments/1fpntvg/help_me_configure)
 - RSS feed: $source
 - date published: 2024-09-26T04:15:10+00:00

<!-- SC_OFF --><div class="md"><p>I have a home lab server running on my local network with Nginx Proxy Manager installed. I also have an Ubuntu server hosted on a Proxmox setup, and I’ve configured Cloudflare to point to it. However, I keep running into a &quot;can&#39;t reach this page&quot; error. I’ve been struggling with this for days and can’t seem to get it to work. My goal is to use the domain I purchased to access my home lab services from remote locations. Could anyone help me figure out what I’m doing wrong or possibly PM me to assist via Zoom or Teams?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Over-Arugula3320"> /u/Over-Arugula3320 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpntvg/help_me_configure/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpntvg/help_me_configure/">[comments]</a></span>

## Help setting up Pihole and Nginx Proxy Manager
 - [https://www.reddit.com/r/selfhosted/comments/1fpnthl/help_setting_up_pihole_and_nginx_proxy_manager](https://www.reddit.com/r/selfhosted/comments/1fpnthl/help_setting_up_pihole_and_nginx_proxy_manager)
 - RSS feed: $source
 - date published: 2024-09-26T04:14:31+00:00

<!-- SC_OFF --><div class="md"><p>Hello all,</p> <p>I wanted to set up local DNS and a reverse proxy so I could access the services I host via a URL instead of an IP. Notably, I want to do this only on my home network (i.e. no router port-forwarding or WAN exposure). I have Pihole successfully installed and set as my router&#39;s DNS server, but I&#39;m having issues getting it to work with NPM.</p> <p>My desired flow is:</p> <p>vm.homelab.com -&gt; NPM (192.168.50.168) -&gt; Proxmox (192.168.50.110:8006)</p> <p>I have an A record in Pihole set to send the domain vm.homelab.com to NPM at 192.168.50.168. Then, I have an NPM proxy host set up to redirect vm.homelab.com to 192.168.50.110:8006.</p> <p>Previously, I would get to the Nginx congratulations page instead of the proper redirect to Proxmox, but after trying to reinstall to fix that, I now get <code>ERR_SSL_UNRECOGNIZED_NAME_ALERT</code>. How can I fix this without port forwarding or using an external DNS?</p> </div><!-- SC_ON --

## Free Cloud Hosting with PHP symlink enabled?
 - [https://www.reddit.com/r/selfhosted/comments/1fpns17/free_cloud_hosting_with_php_symlink_enabled](https://www.reddit.com/r/selfhosted/comments/1fpns17/free_cloud_hosting_with_php_symlink_enabled)
 - RSS feed: $source
 - date published: 2024-09-26T04:12:21+00:00

<!-- SC_OFF --><div class="md"><p>Is there any reputable free web-hosting with php symlink enabled??<br/> I have a project I need to publish, but I am kind of dead broke, so even $5 is alot. Self-hosting is not an option due to my ISP.</p> <p>Any recommendations are appreciated ! :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok_Chair_8742"> /u/Ok_Chair_8742 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpns17/free_cloud_hosting_with_php_symlink_enabled/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpns17/free_cloud_hosting_with_php_symlink_enabled/">[comments]</a></span>

## E 101 out now
 - [https://www.reddit.com/r/selfhosted/comments/1fpnqm1/e_101_out_now](https://www.reddit.com/r/selfhosted/comments/1fpnqm1/e_101_out_now)
 - RSS feed: $source
 - date published: 2024-09-26T04:10:06+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fpnqm1/e_101_out_now/"> <img src="https://external-preview.redd.it/0JBx6-VihfoP7hIim3zN4os4SGjEarrVmV9l__UzEl4.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=920ce5e62cf3e5da7020b5f685f3fa5045eebcb4" alt="E 101 out now " title="E 101 out now " /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kmdestefanopodcast"> /u/kmdestefanopodcast </a> <br/> <span><a href="https://youtu.be/Je7r7KJ-0QA?feature=shared">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpnqm1/e_101_out_now/">[comments]</a></span> </td></tr></table>

## Benefit for spreading across nodes?
 - [https://www.reddit.com/r/selfhosted/comments/1fpnoee/benefit_for_spreading_across_nodes](https://www.reddit.com/r/selfhosted/comments/1fpnoee/benefit_for_spreading_across_nodes)
 - RSS feed: $source
 - date published: 2024-09-26T04:06:22+00:00

<!-- SC_OFF --><div class="md"><p>been enjoying learning proxmox for a home server, running a couple of linux vms running<br/> HA, AdGuard, some seperate docker stacks spread across 2-3 vms, but is there a real benefit at the home level to use several nodes over just one node having all the vms? at the enterprise level here is plenty of reason to do it, but is there a stretch of benefit to be had by doing it on just stuff at home?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Trueleo1"> /u/Trueleo1 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpnoee/benefit_for_spreading_across_nodes/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpnoee/benefit_for_spreading_across_nodes/">[comments]</a></span>

## Tips on Mattermost installation?
 - [https://www.reddit.com/r/selfhosted/comments/1fpnlon/tips_on_mattermost_installation](https://www.reddit.com/r/selfhosted/comments/1fpnlon/tips_on_mattermost_installation)
 - RSS feed: $source
 - date published: 2024-09-26T04:01:51+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to install Mattermost on a homelab for a few of my friends and I to use. I&#39;ve tried using the official install docs for a Docker install, but it didn&#39;t work. Any tips? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/doveeable"> /u/doveeable </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpnlon/tips_on_mattermost_installation/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpnlon/tips_on_mattermost_installation/">[comments]</a></span>

## To Azure or not to Azure?
 - [https://www.reddit.com/r/selfhosted/comments/1fpm0nm/to_azure_or_not_to_azure](https://www.reddit.com/r/selfhosted/comments/1fpm0nm/to_azure_or_not_to_azure)
 - RSS feed: $source
 - date published: 2024-09-26T02:31:55+00:00

<!-- SC_OFF --><div class="md"><p>Hey all, wondering what experience other people have. TL;DR: time to upgrade my home lab which is currently a Lenovo mini pc 16gb core i5 gen 4 running esxi and some vms + 14TB nas</p> <p>At work we&#39;re slowly moving to Azure so wont hurt to practice but the costs worries me (or the lack of knowing it in advance) For my 3 main usages which are a Windows vm 8gb, ubuntu hosting dockers 8gb and the 14tb storage..... What am i really looking at? With the food appetite will sure come and i might spin more. Am i gonna wake up to a 500usd monthly bill? For 1000usd I can get the latest NUC it&#39;s just not making sense why the cloud is so popular!</p> <p>Thanks for any eye opening advice </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/makore256"> /u/makore256 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpm0nm/to_azure_or_not_to_azure/">[link]</a></span> &#32; <span><a href="https://www.re

## FileCloud in Docker/Docker Compose
 - [https://www.reddit.com/r/selfhosted/comments/1fplyx5/filecloud_in_dockerdocker_compose](https://www.reddit.com/r/selfhosted/comments/1fplyx5/filecloud_in_dockerdocker_compose)
 - RSS feed: $source
 - date published: 2024-09-26T02:29:26+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fplyx5/filecloud_in_dockerdocker_compose/"> <img src="https://b.thumbs.redditmedia.com/Ysk62HmAjqBgGWH1yMcdoQQuKaUKdT4M0xDW5u3d-dM.jpg" alt="FileCloud in Docker/Docker Compose" title="FileCloud in Docker/Docker Compose" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I am trying to get FileCloud running in docker or docker compose, I am attached my configs here. I can get either of these to run but neither yield a working instance, the compose file lets me get the login page but I get a &quot;storage not ready&quot; error and cannot continue to login, this method seems to create the needed dependencies and all, the docker run template creates a container that loads but does not generate any logs, does not generate any files in the paths. Thanks for any assistance here.</p> <p><a href="https://preview.redd.it/dtcglf2ee2rd1.png?width=1601&amp;format=png&amp;auto=webp&amp;s=b114aa1150a50e722d75dcdf52c2b60e1eb777a

## Easiest Incremental Backup Solution Through Docker?
 - [https://www.reddit.com/r/selfhosted/comments/1fplwcj/easiest_incremental_backup_solution_through_docker](https://www.reddit.com/r/selfhosted/comments/1fplwcj/easiest_incremental_backup_solution_through_docker)
 - RSS feed: $source
 - date published: 2024-09-26T02:25:33+00:00

<!-- SC_OFF --><div class="md"><p>I have a few folders than I&#39;d like backed up from my server, namely my photos from Immich, my Docker compose yml files, data from all my containers, and files imported into PaperlessNGX. Overall it&#39;s about 300GB worth of stuff.</p> <p>All of these have their own defined directories, so at least that part of it is straightforward.</p> <p>I also have an unlimited Google Drive share thanks to my university.</p> <p>Currently, I use Kopia to make the incremental backups and then RSync to get them into Google Drive. What I realized this past week is that, if Kopia decides it doesn&#39;t feel like working anymore, my data is in a completely unusable state in custom file formats that only Kopia can read properly.</p> <p>Does anyone know of a better way to achieve the same thing?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sure-Temperature"> /u/Sure-Temperature </a> <br/> <span><a href="https://www.reddit.com/

## Just lost 24tb of media
 - [https://www.reddit.com/r/selfhosted/comments/1fplu8v/just_lost_24tb_of_media](https://www.reddit.com/r/selfhosted/comments/1fplu8v/just_lost_24tb_of_media)
 - RSS feed: $source
 - date published: 2024-09-26T02:22:21+00:00

<!-- SC_OFF --><div class="md"><p>Had a power outage at my house that killed my z pool. Seems like everything else is up and running, but years of obtaining media has now gone to waste. Not sure if I will start over or not</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Alucard2051"> /u/Alucard2051 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fplu8v/just_lost_24tb_of_media/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fplu8v/just_lost_24tb_of_media/">[comments]</a></span>

## I need help setting up Docker to connect to my NAS’s network share and write files/media to it
 - [https://www.reddit.com/r/selfhosted/comments/1fpkqj3/i_need_help_setting_up_docker_to_connect_to_my](https://www.reddit.com/r/selfhosted/comments/1fpkqj3/i_need_help_setting_up_docker_to_connect_to_my)
 - RSS feed: $source
 - date published: 2024-09-26T01:24:44+00:00

<!-- SC_OFF --><div class="md"><p>I have two machines: one running bare metal TrueNAS Scale and another running Proxmox with a Debian virtual machine that’s running Docker and DockGE. I&#39;m trying to get everything set up so my ARR Suite and torrent client (with VPN) store media on the network share, but I&#39;m having a lot of issues following different instructions. Could use some help!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ConfusedHomelabber"> /u/ConfusedHomelabber </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpkqj3/i_need_help_setting_up_docker_to_connect_to_my/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpkqj3/i_need_help_setting_up_docker_to_connect_to_my/">[comments]</a></span>

## Anyone know how to get invidious working again?
 - [https://www.reddit.com/r/selfhosted/comments/1fpk0dg/anyone_know_how_to_get_invidious_working_again](https://www.reddit.com/r/selfhosted/comments/1fpk0dg/anyone_know_how_to_get_invidious_working_again)
 - RSS feed: $source
 - date published: 2024-09-26T00:46:38+00:00

<!-- SC_OFF --><div class="md"><p>I heard YouTube was at it again messing it up somehow. Now even my local self-hosted instance is not working properly. It sees the videos but can&#39;t open many of them. Claims they are of &quot;unsupported format&quot; or &quot;server error&quot;. The second is definitely false as I can download them just fine with yt-dlp using my invidious instance url. Most I have done these own come out of yt-dlp as .webm videos but I don&#39;t know if that is what format they were originally.</p> <p>My guess is that they are somehow whitelisting what is pulling the videos but in that case it shouldn&#39;t have gotten to my instance. They don&#39;t seem to have poisoned the format, at least not badly enough that yt-dlp couldn&#39;t handle it.</p> <p>Is there a work-around? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/s3r3ng"> /u/s3r3ng </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fpk0dg/anyone_

## Securing my homelab hosting Minecraft... and plenty more
 - [https://www.reddit.com/r/selfhosted/comments/1fpj340/securing_my_homelab_hosting_minecraft_and_plenty](https://www.reddit.com/r/selfhosted/comments/1fpj340/securing_my_homelab_hosting_minecraft_and_plenty)
 - RSS feed: $source
 - date published: 2024-09-26T00:00:03+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve setup an Unraid server about 2-1/2 years ago. On this server I host a bunch of stuff, mostly for personal use and backups -- but I also host a Minecraft server, and I am pointing at it from a dynamic DNS. </p> <p>Recently I&#39;ve become aware my router has started to drop packets because of SYN attacks. I get about 450 attacks per day, mostly around the same TLDs - but that&#39;s neither here nor there. I do use Cloudflare for free, and I have custom rules trying to bllock these attacks, but somehow it&#39;s not helping. </p> <p>So I&#39;d like to find out if there is a way to add some kind of security to that DNS... I&#39;m sure there&#39;s a way for thos using the dyndns to reverse-lookup the IP it&#39;s pointing at, but somehow I have a feeling it&#39;s this big bot network sending SYN attacks. So there&#39;s somethign that automated that reverse lookup, and now it&#39;s following me. So I&#39;m looking for a way to prevent anyone from us

