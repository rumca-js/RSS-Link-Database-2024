# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Cloudflare WAF whitelist IP dynamically
 - [https://www.reddit.com/r/selfhosted/comments/1h9tt1t/cloudflare_waf_whitelist_ip_dynamically](https://www.reddit.com/r/selfhosted/comments/1h9tt1t/cloudflare_waf_whitelist_ip_dynamically)
 - RSS feed: $source
 - date published: 2024-12-08T21:49:53+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>So I just wanted to share a personal experience on combo Domain Name + Cloudflare DNS/tunnel (zero tier) + Nginx proxy manager.</p> <p>Great solution and easy to implement. However, I noticed that my small server (HP Prodesk with Proxmox) was running too hot some days and had some power spikes (100W vs 30w at normal time). I didn&#39;t see anything wrong in the logs, so I restarted the server and waited one more day..Same issue.</p> <p>Then i watched the Cloudflare traffic and I understood where this was coming from. I got 1000+/day connections from bots and IPs all over the world. </p> <p>So I decided to go for Whitelist IP in WAF module. It works great for when i am at home , however I need to dynamically whitelist my Phone. By the way Idle power dropped as low as 7W with proxmox and 10 LCX containers.</p> <p>I have set a DDNS service + script to update my Home IP at Cloudflare DNS and it works great but I have no idea how can I do it fo

## Using Apple Business Manager to manage 15-20 iOS devices for home use
 - [https://www.reddit.com/r/selfhosted/comments/1h9t79a/using_apple_business_manager_to_manage_1520_ios](https://www.reddit.com/r/selfhosted/comments/1h9t79a/using_apple_business_manager_to_manage_1520_ios)
 - RSS feed: $source
 - date published: 2024-12-08T21:22:37+00:00

<!-- SC_OFF --><div class="md"><p>Hi - my parents have plenty of home automation and roughly 15 iPads that act as sole controllers for everything &quot;smart&quot;. I&#39;m the defacto IT manager for this.</p> <p>I was looking at setting up ABM to remotely manage these devices. I mainly want to remotely push software updates, but I just read up on kiosk mode so enabling that seems smart too.</p> <p>My questions:</p> <ol> <li><p>I was going to register for ABM as sole propritorship and apply for a DUNS number. AFAIK, this is zero cost and only poses a risk if I were to actually conduct business under the DUNS number. <strong>Is anyone else already doing this and can vouch for it?</strong> </p></li> <li><p>Is there an easier way to use ABM without presenting myself as as business entity? I realize ABM isn&#39;t built for home-use but I think it perfectly fits my use case.</p></li> </ol> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/agent-bagent"> /u

## Synology ABB Agent is problematic with firewall rules, what would you do?
 - [https://www.reddit.com/r/selfhosted/comments/1h9ssoj/synology_abb_agent_is_problematic_with_firewall](https://www.reddit.com/r/selfhosted/comments/1h9ssoj/synology_abb_agent_is_problematic_with_firewall)
 - RSS feed: $source
 - date published: 2024-12-08T21:04:36+00:00

<!-- SC_OFF --><div class="md"><p>I recently went down the rabbit hole of setting up more advanced Vlan and got most things figured out, apart from Synology Active backup for business ABB.</p> <p>Right now I have several vLans &amp; firewall for MGMT, storage, PCs, shared devices(printer/TV), IoT, CCTV etc, and several DMZ each contains single or a few VM of similar risk level.</p> <p>ABB has been a great centralized backup for all the PCs &amp; servers, but it uses agent-server setup where agent initiate the backup traffic. which create a big firewall challenge.</p> <p>I can think of 2 ways to tackle it, both have down sides</p> <p>Method1</p> <p>For all devices that can have multiple NIC, put ABB traffic on dedicated vLAN &amp; NIC preferably 10G. But that essentially defeats vLan isolation, i.e. my DMZ VMs can talk to each other across ABB vLAN</p> <p>To combat that, I have to create firewall on each host to lockdown VM in the ABB vLAN, but these firewall rules are scattered all o

## Self hosted webpages help
 - [https://www.reddit.com/r/selfhosted/comments/1h9r2v1/self_hosted_webpages_help](https://www.reddit.com/r/selfhosted/comments/1h9r2v1/self_hosted_webpages_help)
 - RSS feed: $source
 - date published: 2024-12-08T19:48:51+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I currently have a load of webpages hosted by my unraid server, (home assistant, Plex, Deluge, esphome.....) these all work internally via my web address and port number, as I have set up a DNS override. And also externally via the web address. Using no-ip</p> <p>I have other devices in my network with a different IP that I can also access internally via their IP address and externally with the web address and their associated port number. Is there a way to access these internally via the web address as I can&#39;t create multiple rules in DNS override </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Visual_Possession_96"> /u/Visual_Possession_96 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9r2v1/self_hosted_webpages_help/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9r2v1/self_hosted_webpages_help/">[comments]</a></span>

## Storage + Backups - Need your insights
 - [https://www.reddit.com/r/selfhosted/comments/1h9ql4t/storage_backups_need_your_insights](https://www.reddit.com/r/selfhosted/comments/1h9ql4t/storage_backups_need_your_insights)
 - RSS feed: $source
 - date published: 2024-12-08T19:26:37+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, </p> <p>I wanted your opinions and experiences on setting up my NAS and backup servers. I&#39;m especially interested in the &quot;why&quot; aspect of your replies.</p> <p>Here&#39;s the situation: </p> <p>I currently have 3 (identical) servers with each 4 hot-swap drive-bays. One of them is currently my NAS server on which I have 2 pools, each with 2 drives. One pool serves as multimedia storage, the other (was/is) Docker Swarm storage exposed via NFS.</p> <p>The more my Swarm grew the more issues I got with corrupt SQLite databases (even if there was only one instance running). Research tought me that NFS and SQLite or not very good friends, so I looked for an easy alternative and hit upon SeaweedFS.</p> <p>I have been proof-running SeaweedFS for a few months now and I&#39;m really happy with it. No more SQLite issues and everything loads really snappy, so I would like to replace my Docker pool on the NAS with SeaweedFS.</p> <p>Here a

## Spare PC laying around
 - [https://www.reddit.com/r/selfhosted/comments/1h9pvi9/spare_pc_laying_around](https://www.reddit.com/r/selfhosted/comments/1h9pvi9/spare_pc_laying_around)
 - RSS feed: $source
 - date published: 2024-12-08T18:55:51+00:00

<!-- SC_OFF --><div class="md"><p>I have a mini itx computer laying around after I moved back to a full atx computer case a few years ago. It still has the mobo, intel 4670k, 16gb ram, gtx 2060 and an ssd. </p> <p>I am not very well educated in what you can do with self hosting, so I&#39;m wondering if I can keep it and use it for some fun and useful self-hosted purposes? </p> <p>I use apple home for all my smart appliances, but I&#39;ve heard good things about home assistant. What could I do with a full Pc that I can&#39;t achieve with apple home + HomePod mini?</p> <p>I also have iCloud, but one annoyance is the limits for shared albums. </p> <p>I currently use Stremio with Torrentio for my 🏴‍☠️ streaming needs, but perhaps there are better options. Our downstairs TV doesn&#39;t have HDR so it&#39;s sometimes annoying scrolling through the results of sources to find the SDR version. Can I set up something like Plex which downloads all my favourite shows/films in a specified format?

## Scripts for Automated Encrypted PostgreSQL Backups in Proxmox CTs
 - [https://www.reddit.com/r/selfhosted/comments/1h9pk6i/scripts_for_automated_encrypted_postgresql](https://www.reddit.com/r/selfhosted/comments/1h9pk6i/scripts_for_automated_encrypted_postgresql)
 - RSS feed: $source
 - date published: 2024-12-08T18:41:55+00:00

<!-- SC_OFF --><div class="md"><p>Hello :) I&#39;ve created a set of scripts that automate encrypted PostgreSQL backups in Proxmox containers and securely transfer them to remote storage. Some features:</p> <ul> <li>Creates encrypted PostgreSQL backups within containers using OpenSSL and AES-256</li> <li>Transfers backups to remote storage using SFTP without storing credentials in containers</li> <li>Manages multiple backup tasks through config files</li> </ul> <p>Might be useful for self-hosters running PostgreSQL databases in Proxmox who need encrypted, automated backups. </p> <p><a href="https://codeberg.org/andrej/proxmox_backup_transfer_scripts">https://codeberg.org/andrej/proxmox_backup_transfer_scripts</a></p> <p>I use it to backup some of my self-hosted DBs to my local NAS and also send them off-site.</p> <p>Have a look and let me know what you think.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/schoeke"> /u/schoeke </a> <br/> <span><

## Does the setup order matter on a new proxmox server?
 - [https://www.reddit.com/r/selfhosted/comments/1h9pjxj/does_the_setup_order_matter_on_a_new_proxmox](https://www.reddit.com/r/selfhosted/comments/1h9pjxj/does_the_setup_order_matter_on_a_new_proxmox)
 - RSS feed: $source
 - date published: 2024-12-08T18:41:36+00:00

<!-- SC_OFF --><div class="md"><p>Have dabbled with cloud servers and pi, but am getting an N100 Nucbox to use at home with the following:</p> <ul> <li>Proxmox</li> <li>Jellyfin</li> <li>Immich</li> <li>Postgres</li> <li>VaultWarden</li> <li>Wireguard</li> <li>Adguard</li> <li>Bind9</li> <li>Maybe Nextcloud</li> </ul> <p>Will it be easier if I do this in a particular order?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DavesDogma"> /u/DavesDogma </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9pjxj/does_the_setup_order_matter_on_a_new_proxmox/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9pjxj/does_the_setup_order_matter_on_a_new_proxmox/">[comments]</a></span>

## How can I access Wallos out of local network?
 - [https://www.reddit.com/r/selfhosted/comments/1h9pjfy/how_can_i_access_wallos_out_of_local_network](https://www.reddit.com/r/selfhosted/comments/1h9pjfy/how_can_i_access_wallos_out_of_local_network)
 - RSS feed: $source
 - date published: 2024-12-08T18:41:02+00:00

<!-- SC_OFF --><div class="md"><p>I have installed Wallos via Docker on my NAS. I was able to set up everything via the local IP address. Now I don&#39;t know how to reach the site outside my network. I had some images installed by someone on Fiverr who also used Dynv6.com.</p> <p>Can anyone help me? I have also installed Portainer. I am still relatively new to this and am trying to familiarize myself with docker, portainer, images, containers, etc.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hoodflow"> /u/hoodflow </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9pjfy/how_can_i_access_wallos_out_of_local_network/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9pjfy/how_can_i_access_wallos_out_of_local_network/">[comments]</a></span>

## What are my options for taking control of my sports streaming?
 - [https://www.reddit.com/r/selfhosted/comments/1h9pcgb/what_are_my_options_for_taking_control_of_my](https://www.reddit.com/r/selfhosted/comments/1h9pcgb/what_are_my_options_for_taking_control_of_my)
 - RSS feed: $source
 - date published: 2024-12-08T18:32:38+00:00

<!-- SC_OFF --><div class="md"><p>I pay for various content services that include sports streaming. Some of these company&#39;s have paid developers to prevent pausing when I go to the bathroom because they want me to sit through commercials no matter what. As a result I also can&#39;t rewind good plays or fast forward as well.</p> <p>Are there any recording devices or self hosted apps I can deploy that will restore TIVO/DVR services to the content that is already being streamed into my home? Even better if it includes ad removal services. Am I thinking too small and theres a much better way of viewing sports on my TV?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/djlarrikin"> /u/djlarrikin </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9pcgb/what_are_my_options_for_taking_control_of_my/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9pcgb/what_are_my_options_for_taking_control_

## Please help a noob setting up webserver/fileserver
 - [https://www.reddit.com/r/selfhosted/comments/1h9p0tj/please_help_a_noob_setting_up_webserverfileserver](https://www.reddit.com/r/selfhosted/comments/1h9p0tj/please_help_a_noob_setting_up_webserverfileserver)
 - RSS feed: $source
 - date published: 2024-12-08T18:18:49+00:00

<!-- SC_OFF --><div class="md"><p>Hello.</p> <p>I need to set up a home computer that will work as a 24/7 public webserver for some web projects I&#39;ll be working in over the course of the next two years, and a local file server that I can use to dump files on it (backups, Unity projects, the usual). I also plan on adding a public media server in the future so I have access to all of my rips (this part is relevant, you&#39;ll see why soon) whenever I am.</p> <p>These are my options ATM: </p> <ul> <li>A modified <strong>Dell Optiplex 3050 SFF</strong> working as a living room computer. It has two hard drives: an M.2 and a SATA SSD, with the second SATA port being used by a BR burner that allows me to dump all of my discs (MakeMKV I love you). It also has 32GB I took out of my previous machine and a GT1030 for very light gaming - that is to say, Vampire Survivors, TBoI and Retroarch. It has Windows 10, which I&#39;d rather not replace on that machine, and it&#39;s plugged to a 4TB US

## Help, i need to upgrade my home lab infrastructure
 - [https://www.reddit.com/r/selfhosted/comments/1h9onbk/help_i_need_to_upgrade_my_home_lab_infrastructure](https://www.reddit.com/r/selfhosted/comments/1h9onbk/help_i_need_to_upgrade_my_home_lab_infrastructure)
 - RSS feed: $source
 - date published: 2024-12-08T18:02:34+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, currently my setup is this:</p> <ul> <li><strong>Motherboard:</strong> Topton NAS N5105</li> <li><strong>CPU:</strong> Intel Celeron N5105 Quad-core</li> <li><strong>RAM:</strong> 2x Crucial 16GB 3200MHz DDR4 SODIMM (maximum)</li> <li><strong>SSD:</strong> Silicon Power M.2 NVMe 256gb Gen3x4</li> <li><strong>HDD:</strong> 2x Seagate Exos X12 12TB (with mirror)</li> <li><strong>NETWORK:</strong> 4x Intel i225v/i226v 2.5Gigabit ETH</li> </ul> <p>runs Proxmox with Truenas Scale, Debian (only for runs Docker with a lots of containers) and a couple of LXCs. Since I also want to run 1-2 other OSes for other purposes.</p> <p>I feel the need to upgrade also because I have many containers turned off due to insufficient resources.</p> <p>I was thinking of using the current configuration still with proxmox where just Truenas Scale is running there (with disk passtrough of course) and flanking it with another server with a more powerful processor (I

## Hosting a game server on a cloud PC.
 - [https://www.reddit.com/r/selfhosted/comments/1h9nqwd/hosting_a_game_server_on_a_cloud_pc](https://www.reddit.com/r/selfhosted/comments/1h9nqwd/hosting_a_game_server_on_a_cloud_pc)
 - RSS feed: $source
 - date published: 2024-12-08T17:22:57+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, I would like to host my own dedicated server to play with a group of friends and I need it to be up 24/7. Previously, I used to simply rent from services such as g-portal where you can select from a predetermined list of games and configure your server via the browser-based UI. However, now I want to host a server for an older modded game which is not supported on any such platforms. Intially, I thought of just renting a cloud computer which allows you to access the windows deskptop, like Shadow PC, for example. However, it turns out this is against their TOS and they don&#39;t allow port forwarding. </p> <p>Is there a service which allows you to simply rent a remote computer with normal Windows 10 where you can download game files, enable port forwarding, and host your own server 24/7? I have zero coding knowledge and don&#39;t want to mess with complicated set ups. Basically I just need a normal computer that runs 24/7 and allows lo

## Personal library
 - [https://www.reddit.com/r/selfhosted/comments/1h9nagi/personal_library](https://www.reddit.com/r/selfhosted/comments/1h9nagi/personal_library)
 - RSS feed: $source
 - date published: 2024-12-08T17:02:41+00:00

<!-- SC_OFF --><div class="md"><p>Hi fellow readers, I recently updated my book library/book tracking app. I think of it more like an extension to Goodreads.<br/> <a href="https://github.com/yamesyung/SoloScribe">https://github.com/yamesyung/SoloScribe</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/casu-marzu"> /u/casu-marzu </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9nagi/personal_library/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9nagi/personal_library/">[comments]</a></span>

## How do I safely setup a home server without access to WireGuard or other VPNs?
 - [https://www.reddit.com/r/selfhosted/comments/1h9n1x1/how_do_i_safely_setup_a_home_server_without](https://www.reddit.com/r/selfhosted/comments/1h9n1x1/how_do_i_safely_setup_a_home_server_without)
 - RSS feed: $source
 - date published: 2024-12-08T16:52:16+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, I&#39;ve recently been reading more about self hosting and have thought about setting something up for myself at home using an old desktop PC. I&#39;m sort of new to self hosting and networking, but I have experience with programming, Linux and the basics of Docker. I&#39;m going to be setting up Ubuntu server on it as well as setting up a samba network share using an SSD I had lying around and an old external hard drive. I&#39;m also thinking about setting up AdGuard on it as well.</p> <p>This was my initial use case for it; to just mess around with docker and have a network share I can use in my house, but I&#39;ve been thinking of also setting up some services (probably also using docker) that I can access from anywhere. I own a domain and thought of setting up Filebrowser for remote access to my files, and maybe a dashboard like glance, among other things I&#39;m thinking of. While researching, I saw everyone recommending WireGuar

## Recommendation for headless linux distro for laptop
 - [https://www.reddit.com/r/selfhosted/comments/1h9mm76/recommendation_for_headless_linux_distro_for](https://www.reddit.com/r/selfhosted/comments/1h9mm76/recommendation_for_headless_linux_distro_for)
 - RSS feed: $source
 - date published: 2024-12-08T16:32:31+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m new to self hosting. I&#39;m looking to repurpose my old laptop into a home server and host some services.</p> <p>I need recommendation for a headless linux distro that is okay for a beginner on which I can run these services using docker.</p> <p>Services I want to run: - Jellyfin - service for filesharing for Windows devices and Android if possible with authentication - Torrent client - Some *arr services - service for file and image backup</p> <p>The laptop is a Dell 7567, i5-7300HQ, 8GB Ram (1 free slot available), 1050 ti, 256GB SSD, 1TB HDD. I will add an external 8TB drive via USB (Seagate Expansion)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/throwdiyd"> /u/throwdiyd </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9mm76/recommendation_for_headless_linux_distro_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9mm76/recommendati

## Paperless-NGX Email attachment parsing and security
 - [https://www.reddit.com/r/selfhosted/comments/1h9maos/paperlessngx_email_attachment_parsing_and_security](https://www.reddit.com/r/selfhosted/comments/1h9maos/paperlessngx_email_attachment_parsing_and_security)
 - RSS feed: $source
 - date published: 2024-12-08T16:18:26+00:00

<!-- SC_OFF --><div class="md"><p>Hey,</p> <p>i started to use paperless-NGX and i love it. The satisfaction of it learning over time to correctly sort and tag your documents is amazing. Logically i am now infected and want it also to ingest my mail inbox.</p> <p>But now as i am setting this up i noticed, that this might introduce a powerfull attack vector into my home network.</p> <p>There might exists some malware which exploits some part of the paperless parsing workflow like ocr or what ever happends in the backend which then could give an attacker access to important documents in a conveniently searchable database.</p> <p>It maybe a very specialised case, but knowing how popular paperless is it could be lucrative to do. And my be not that hard. You only need:</p> <ol> <li>Match some leaked userdatabase from a random site with usernames from commenters on paperless github or this subreddit</li> <li>Have an actual vulnerability at hand for the paperless backend</li> </ol> <p>So en

## A Gamified Productivity Manager for Tasks and Projects
 - [https://www.reddit.com/r/selfhosted/comments/1h9m9bk/a_gamified_productivity_manager_for_tasks_and](https://www.reddit.com/r/selfhosted/comments/1h9m9bk/a_gamified_productivity_manager_for_tasks_and)
 - RSS feed: $source
 - date published: 2024-12-08T16:16:44+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Relevant_Bird_7347"> /u/Relevant_Bird_7347 </a> <br/> <span><a href="https://smart-listapp.vercel.app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9m9bk/a_gamified_productivity_manager_for_tasks_and/">[comments]</a></span>

## My First HomeLab
 - [https://www.reddit.com/r/selfhosted/comments/1h9m4wm/my_first_homelab](https://www.reddit.com/r/selfhosted/comments/1h9m4wm/my_first_homelab)
 - RSS feed: $source
 - date published: 2024-12-08T16:11:20+00:00

<!-- SC_OFF --><div class="md"><p>Hi All, not sure if this should go here or on a different subreddit. New to homelab, but have self hosted a few things in the past. Giving this a shot.</p> <p>I have the following set so far but just want to get input from the community on what I should look at changing or adding.</p> <p>I am using ProxMox as the base for the HomeLab</p> <p>Server Specs: CPU: 2 x Intel Xeon E5-2697 v3 RAM: 256GB DDR4 ECC Memory Storage: 2 x 1TB SSD in Raid1 IP: 197.242.158.253 OS: ProxMox 8.3.1</p> <p>Software that will be running on VMs or CTs 1. pfSense or OPNSense - Main bridge between WAN and LAN for the VMs. 2. Home Assistant 3. Jellyfin 4. Lidarr 5. Radarr 6. Sonarr 7. Readarr 8. Nextcloud 9. qBittorrent 10. Prometheus 11. Grafana 12. Uptime Kuma 13. GitLab 14. BitWarden 15. Wireguard</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Belantro_001"> /u/Belantro_001 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted

## Simple To-Do-Solution for iOS?
 - [https://www.reddit.com/r/selfhosted/comments/1h9lvb9/simple_todosolution_for_ios](https://www.reddit.com/r/selfhosted/comments/1h9lvb9/simple_todosolution_for_ios)
 - RSS feed: $source
 - date published: 2024-12-08T15:59:21+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I have a pretty simple request, but I couldn&#39;t find what I was looking for here on Reddit.</p> <p>I&#39;m looking for a simple to-do list for IOS. I would like to have a possibility of an app to e.g. display the tasks as a widget.</p> <p>I already have Vikunja and Planka on the server, but I&#39;m missing a simple app, even if the PWA versions are nice.</p> <p>There seem to be apps for Android. Do you have a solution for IOS?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/datatest05"> /u/datatest05 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9lvb9/simple_todosolution_for_ios/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9lvb9/simple_todosolution_for_ios/">[comments]</a></span>

## How often do you update docker images for your selfhosted software?
 - [https://www.reddit.com/r/selfhosted/comments/1h9l5wc/how_often_do_you_update_docker_images_for_your](https://www.reddit.com/r/selfhosted/comments/1h9l5wc/how_often_do_you_update_docker_images_for_your)
 - RSS feed: $source
 - date published: 2024-12-08T15:26:35+00:00

<!-- SC_OFF --><div class="md"><p>When I first started self hosting, I used to update images instantly (based on GitHub release notifications), mostly because of my enthusiasm. But of late I have learnt that it&#39;s better to wait to update images (to allow time for bugs to be fixed etc.).</p> <p>I&#39;m wondering how often you update images for your self hosted software? Is once every month too infrequent or is once every week sufficient? Would love to hear some thoughts.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OkCommunication1427"> /u/OkCommunication1427 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9l5wc/how_often_do_you_update_docker_images_for_your/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9l5wc/how_often_do_you_update_docker_images_for_your/">[comments]</a></span>

## Weird note taking solution – How would you implement it ?
 - [https://www.reddit.com/r/selfhosted/comments/1h9l40u/weird_note_taking_solution_how_would_you](https://www.reddit.com/r/selfhosted/comments/1h9l40u/weird_note_taking_solution_how_would_you)
 - RSS feed: $source
 - date published: 2024-12-08T15:24:06+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, like many of you I have tried and changed many self hosted note taking solutions and kept jumping on the next shiny new thing when it came out. Among others I have tried:</p> <ul> <li>Joplin</li> <li>Memos</li> <li>AppFlowy</li> <li>Silverbullet</li> <li>Outline</li> <li>AnyType (love it but pain to sh)</li> <li>NextCloud notes/deck</li> </ul> <p>At this point I realised that what really matters to me are the following things:</p> <ul> <li>Accessible both online and offline</li> <li>Support for nvim e.g. obsidian.nvim (even if I don&#39;t actually use obsidian afterwards) on computer</li> <li>ability to read/make small changes on mobile</li> <li>support for some kind of linking between files</li> </ul> <p>Since I feel most comfortable with nvim now it seems to me that I can have a DB based approach and the files need to be readily accessible.</p> <p>I tried doing a combo of Silverbullet + obsidian.nvim where I used SB as a sync/read o

## Drive fully faulted or could it be the sata cable?
 - [https://www.reddit.com/r/selfhosted/comments/1h9ktnn/drive_fully_faulted_or_could_it_be_the_sata_cable](https://www.reddit.com/r/selfhosted/comments/1h9ktnn/drive_fully_faulted_or_could_it_be_the_sata_cable)
 - RSS feed: $source
 - date published: 2024-12-08T15:10:32+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1h9ktnn/drive_fully_faulted_or_could_it_be_the_sata_cable/"> <img src="https://b.thumbs.redditmedia.com/4eRahLz6C7fkI87DgRnUibxCuBH8wtDm8SmibygOTvA.jpg" alt="Drive fully faulted or could it be the sata cable?" title="Drive fully faulted or could it be the sata cable?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/6s5ssiai4n5e1.png?width=199&amp;format=png&amp;auto=webp&amp;s=9a8715d146f74e0c576b4f29ff3c98bfbd84dc0d">https://preview.redd.it/6s5ssiai4n5e1.png?width=199&amp;format=png&amp;auto=webp&amp;s=9a8715d146f74e0c576b4f29ff3c98bfbd84dc0d</a></p> <p>1 of the drives in my pool has been like this for a while now, from the GUI I already just re entered the drive once to see what it would do and few days after resilvering it would again have a lot of write errors and get marked as faulted. I&#39;ve not yet tried replugging the SATA cable yet, but would it ever be worth the try

## Just relase an docker food recipes application.
 - [https://www.reddit.com/r/selfhosted/comments/1h9kaxn/just_relase_an_docker_food_recipes_application](https://www.reddit.com/r/selfhosted/comments/1h9kaxn/just_relase_an_docker_food_recipes_application)
 - RSS feed: $source
 - date published: 2024-12-08T14:45:03+00:00

<!-- SC_OFF --><div class="md"><p>Hey 👋 I just relase an self hosted food recipes application in Github. It&#39;s container 3 containers FE, BE and Nginx it can be deployed with docker compose as also support and SSL connection.</p> <p>Take a look of the repo <a href="https://github.com/mikebgrep/fork.recipes">repo link</a> and the documentation and tell me what you thing. It will have option for link to recipe with the help of OpenAI but this should be done soon.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Affectionate-Dog-715"> /u/Affectionate-Dog-715 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9kaxn/just_relase_an_docker_food_recipes_application/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9kaxn/just_relase_an_docker_food_recipes_application/">[comments]</a></span>

## A self-hosted gallery tool with customization and export features
 - [https://www.reddit.com/r/selfhosted/comments/1h9jhwr/a_selfhosted_gallery_tool_with_customization_and](https://www.reddit.com/r/selfhosted/comments/1h9jhwr/a_selfhosted_gallery_tool_with_customization_and)
 - RSS feed: $source
 - date published: 2024-12-08T14:03:41+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1h9jhwr/a_selfhosted_gallery_tool_with_customization_and/"> <img src="https://b.thumbs.redditmedia.com/TLJNFG7Tkmsrt-G9GijPOPjiQRKffrA6YW2T-o_ukOk.jpg" alt="A self-hosted gallery tool with customization and export features" title="A self-hosted gallery tool with customization and export features" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/2vlqqtkjrm5e1.png?width=1233&amp;format=png&amp;auto=webp&amp;s=fb3973200a87a2f025a735410fa85502d2d0fa76">https://preview.redd.it/2vlqqtkjrm5e1.png?width=1233&amp;format=png&amp;auto=webp&amp;s=fb3973200a87a2f025a735410fa85502d2d0fa76</a></p> <p>Hi selfhosted community! 👋</p> <p>We’re the developers behind one of the popular WordPress gallery plugins, and we’re exploring the idea of creating a new version of the gallery specifically designed for self-hosted setups.</p> <p>Here’s the concept:</p> <ol> <li><strong>Customizable Gallery Edito

## Reboot and backup strategy using Proxmox Backup Server
 - [https://www.reddit.com/r/selfhosted/comments/1h9j674/reboot_and_backup_strategy_using_proxmox_backup](https://www.reddit.com/r/selfhosted/comments/1h9j674/reboot_and_backup_strategy_using_proxmox_backup)
 - RSS feed: $source
 - date published: 2024-12-08T13:46:24+00:00

<!-- SC_OFF --><div class="md"><p>Hello guys,</p> <p> </p> <p>I’ve been using Proxmox for 3 years now.</p> <p>All that time i’ve used a VM to rsync the data I wanted to backup.</p> <p>I very recently decided to invest in some new HDD an set up a Proxmox Backup Server VM in order to do proper back of VMs OS + data.</p> <p> </p> <p>I discovered that a full read of backed up partitions takes around 3 hours.</p> <p>When the VMs did not rebooot between backups the dirty bitmap is kept so the whole process is done in a few minutes.</p> <p> </p> <p>Since the beginning of my homelab journey the VMs are rebooted weekly using a script on Proxmox. That process ensures new kernels are loaded and security is up to date (they are all debian systems).</p> <p> </p> <p>As I want to avoid to stress the drives by making them read data for 3 hours straight every week, i’d like to reboot the VMs only when needed (mostly to apply security patches).</p> <p> </p> <p>I’ve read about to package « update-notif

## nextcloud lxc und qnap nas
 - [https://www.reddit.com/r/selfhosted/comments/1h9ig72/nextcloud_lxc_und_qnap_nas](https://www.reddit.com/r/selfhosted/comments/1h9ig72/nextcloud_lxc_und_qnap_nas)
 - RSS feed: $source
 - date published: 2024-12-08T13:05:22+00:00

<!-- SC_OFF --><div class="md"><p>Hallo Zusammen,</p> <p>ich habe Nextcloud auf einem Proxmox als lxc eingerichtet. Nun möchte ich, dass Nextcloud meine QNAP Nas als Speicher nutzt. Dazu habe auf der Nas einen eigenen Nutzer mit Speicher eingerichtet. Diesen habe ich dann in Proxmox (Datacenter -&gt; Storage) eingebunden und in der lxc als Ressoruce (Mountpoint /mnt/nas) angegeben.</p> <p>Im lxc ist nun /mnt/nas verfügbar. Nun weiß ich nicht weiter. Wie kann ich das als Speicherort für nextcloud nutzen?</p> <p>Vielen Dank</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Proper_Victory2957"> /u/Proper_Victory2957 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9ig72/nextcloud_lxc_und_qnap_nas/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9ig72/nextcloud_lxc_und_qnap_nas/">[comments]</a></span>

## Self-hosted website proxy
 - [https://www.reddit.com/r/selfhosted/comments/1h9ho02/selfhosted_website_proxy](https://www.reddit.com/r/selfhosted/comments/1h9ho02/selfhosted_website_proxy)
 - RSS feed: $source
 - date published: 2024-12-08T12:18:13+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I&#39;ve been looking for a self-hosted proxy solution similar to proxyium.com. Basically I&#39;d like to have a self-hosted website-based proxy on mydomain.com that shows a google page or a URL entry page (like proxyium) which then I can use to browse the internet and it acts as a proxy and hides my real IP.</p> <p>I know there are solutions like Squid proxy and Shadowsocks but they all require tinkering with proxy settings in your browser which I&#39;d like to avoid.</p> <p>I&#39;ve done some searching and seen a few posts asking for similar things but I haven&#39;t seen a satisfactory solution, so I thought I try my luck.</p> <p>edit: also aware of VNC based solutions but they suffer from low quality due to compression etc,.</p> <p>Thanks in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Gear_External"> /u/Gear_External </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/com

## SigNoz - A self-hosted and open source alternative to DataDog, NewRelic releases v0.60.0 with support for Infra monitoring
 - [https://www.reddit.com/r/selfhosted/comments/1h9hnt8/signoz_a_selfhosted_and_open_source_alternative](https://www.reddit.com/r/selfhosted/comments/1h9hnt8/signoz_a_selfhosted_and_open_source_alternative)
 - RSS feed: $source
 - date published: 2024-12-08T12:17:52+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1h9hnt8/signoz_a_selfhosted_and_open_source_alternative/"> <img src="https://b.thumbs.redditmedia.com/8BLVSi3gBo7TWq1yvCZqr6orf4Lvmf5ARclV9VbvJ3I.jpg" alt="SigNoz - A self-hosted and open source alternative to DataDog, NewRelic releases v0.60.0 with support for Infra monitoring" title="SigNoz - A self-hosted and open source alternative to DataDog, NewRelic releases v0.60.0 with support for Infra monitoring" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pranay01"> /u/pranay01 </a> <br/> <span><a href="https://signoz.io/docs/userguide/hostmetrics/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9hnt8/signoz_a_selfhosted_and_open_source_alternative/">[comments]</a></span> </td></tr></table>

## Ubuntu chroot on android
 - [https://www.reddit.com/r/selfhosted/comments/1h9h0f7/ubuntu_chroot_on_android](https://www.reddit.com/r/selfhosted/comments/1h9h0f7/ubuntu_chroot_on_android)
 - RSS feed: $source
 - date published: 2024-12-08T11:34:16+00:00

<!-- SC_OFF --><div class="md"><p>So, I have a samsung phone. For the sake of fun, I just setup Ubuntu chroot on it. Is there someway I could use it for something. I have already tried pihole. Is there anything else that I can do?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cyber5234"> /u/cyber5234 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9h0f7/ubuntu_chroot_on_android/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9h0f7/ubuntu_chroot_on_android/">[comments]</a></span>

## Any appetite for an ADB based Image sync tool/script?
 - [https://www.reddit.com/r/selfhosted/comments/1h9gw35/any_appetite_for_an_adb_based_image_sync](https://www.reddit.com/r/selfhosted/comments/1h9gw35/any_appetite_for_an_adb_based_image_sync)
 - RSS feed: $source
 - date published: 2024-12-08T11:26:08+00:00

<!-- SC_OFF --><div class="md"><p>Hi all</p> <p>I ve been tackling the topic of sync&#39;ing with my phone and with the dying of the (official) android app of syncthing I reevaluated my needs. </p> <p>Since I often have my phone connected to my PC (for scrcpy, etc), I figured I just write my own sync script that I can execute on demand, since my need is rarely instantaneous syncing. </p> <p>Having put a few hours into it, I was just curious if people here have a need for it too.</p> <p>It is not super well polished, but I could easily clean it up, make it available as a pure python script, or even consider giving it a simple web frontend (limited to your local machine) </p> <p>Here is what it does:</p> <ul> <li>Python script (currently based around Linux file systems, but could be made to work with Windows too)</li> <li>Uses Android Debugging Bridge (ADB) to get files from the phone</li> <li>Copies or Moves files in a (currently) one way sync</li> <li>hashes files (content, not names

## Is there no game save backup solution in the selfhosted realm ?
 - [https://www.reddit.com/r/selfhosted/comments/1h9gefs/is_there_no_game_save_backup_solution_in_the](https://www.reddit.com/r/selfhosted/comments/1h9gefs/is_there_no_game_save_backup_solution_in_the)
 - RSS feed: $source
 - date published: 2024-12-08T10:51:50+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I&#39;m posting today to ensure that..</p> <p>No one has yet built a self hostable app to automatically backup game saves (legit games <em>or not</em>) ?</p> <p>I think I understand the trouble that in order to automatize most of the work, the app should know most game save location (I think steam games have steamDB available) or at least be indicated by the user which folder is the game save one (cracked games for example usually have different game save folder depending on the &quot;publisher&quot;).</p> <p>Do you guys think it&#39;s an interesting idea to do ? Or do some of you have tried and found out it&#39;s just a pain in the ass to make ?</p> <p>For 2 years now I&#39;ve been a consumer of self host services and I&#39;d like to learn to build a full app, working backend as well as the web page that goes with it. So I&#39;d like to create something for the community but I do not know where to start, in order to have backups,

## Magazine Article Storage & Search?
 - [https://www.reddit.com/r/selfhosted/comments/1h9ge94/magazine_article_storage_search](https://www.reddit.com/r/selfhosted/comments/1h9ge94/magazine_article_storage_search)
 - RSS feed: $source
 - date published: 2024-12-08T10:51:29+00:00

<!-- SC_OFF --><div class="md"><p>I’m trying to find a good self hosted solution (or any good solution at this point) for storing, searching, reading, and if possible note taking on a collection of articles I’ve clipped from magazines and other sources over the years. Not quite books. Not quite published papers. I’m familiar with Paperless NGX and it doesn’t quite fit the use case. I am considering Calibre, Librum, I-Library and would welcome any other suggestions. Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kod4krome"> /u/kod4krome </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9ge94/magazine_article_storage_search/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9ge94/magazine_article_storage_search/">[comments]</a></span>

## I am stuck and chat gpt is too
 - [https://www.reddit.com/r/selfhosted/comments/1h9gd28/i_am_stuck_and_chat_gpt_is_too](https://www.reddit.com/r/selfhosted/comments/1h9gd28/i_am_stuck_and_chat_gpt_is_too)
 - RSS feed: $source
 - date published: 2024-12-08T10:49:06+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to run this command as a test to then run a app that does similar please help if anyone has any ideas all welcome </p> <p>edit: just a bit of an explanation on what is going on </p> <p>The <a href="http://server.py"><code>server.py</code></a> script defines a Flask web application to handle file uploads. It sets up a directory for storing uploaded files, checks that file extensions are allowed, and logs all actions for debugging. The <code>/upload</code> endpoint processes POST requests, validates the uploaded file, and saves it to the designated folder, returning a success or error response as needed. Logging is configured to capture details in <code>flask_debug.log</code>.</p> <p>The <code>flask_app.wsgi</code> script acts as the bridge between Apache and the Flask application. It sets up the Python environment by adding the Flask app’s directory to the Python path, logs the script’s execution for debugging, and imports the Flask app as

## Selfhosted second brain options?
 - [https://www.reddit.com/r/selfhosted/comments/1h9g0sa/selfhosted_second_brain_options](https://www.reddit.com/r/selfhosted/comments/1h9g0sa/selfhosted_second_brain_options)
 - RSS feed: $source
 - date published: 2024-12-08T10:24:13+00:00

<!-- SC_OFF --><div class="md"><p>Hi! </p> <p>TL;DR: I want an AI-enabled second brain for personal knowledge management and journaling. It should be as FOSS as possible. How would you go about this? And can I run it on a normal VPS without a GPU?</p> <p>Long version: I want to ditch Onenote and migrate to something else. Ideally selfhosted, but I&#39;d also be okay with Obsidian or something like it. Preferably, my new (selfhosted) solution works in all of these ways:</p> <p>a) while I&#39;m on a run, I can pull out my phone and say &quot;Remind me about X in an hour / when I&#39;m home&quot; and then it does that or at least creates that reminder for me in e.g. MS To Do</p> <p>b) I want to keep a journal. Ideally, I ramble incoherently at my phone every night and then get a human-readable prose edit of that in my notes. Ideally, my selfhosted AI companion can detect patterns in my thoughts that have so far escaped me (e.g. every time I visit friend X, I&#39;m a little sad / happier

## iOS app for freshrss
 - [https://www.reddit.com/r/selfhosted/comments/1h9fw9y/ios_app_for_freshrss](https://www.reddit.com/r/selfhosted/comments/1h9fw9y/ios_app_for_freshrss)
 - RSS feed: $source
 - date published: 2024-12-08T10:15:13+00:00

<!-- SC_OFF --><div class="md"><p>Are any good app that can connect to a self hosted freshrss? I tried NetNewsWire and heard good things about reeder and unread but I refuse to pay annual fee for such a software . I didn’t moved from Inoreader to pay the app So any good free or one time pay for iOS ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/amunhot3p"> /u/amunhot3p </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9fw9y/ios_app_for_freshrss/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9fw9y/ios_app_for_freshrss/">[comments]</a></span>

## Looking to a tool with an API, to manage a bunch of Ansible playbooks to execute on a NEW server via a GUI.
 - [https://www.reddit.com/r/selfhosted/comments/1h9fppq/looking_to_a_tool_with_an_api_to_manage_a_bunch](https://www.reddit.com/r/selfhosted/comments/1h9fppq/looking_to_a_tool_with_an_api_to_manage_a_bunch)
 - RSS feed: $source
 - date published: 2024-12-08T10:02:15+00:00

<!-- SC_OFF --><div class="md"><p>I provide installation services of a particular software with a couple of self-hosted applications, all nicely integrated together. Normally, this is a tedious task and I wrote a short guide on it last year, and couple of months it was tweeted by a fairly popular X user and suddenly I started getting a lot of enquiries.</p> <p>It&#39;s becoming difficult to manage the customers due to my busy schedule and I was thinking I could give them a self-serve system of some kind where they just enter the IP address of their server and add the generated generated SSH key given to them, make a payment, and then my system can run the playbook to install the services for them.</p> <p>I&#39;m not sure if this is something I can implement in Rundeck or AWX, or if there even other tools that can do this so I don&#39;t have to build a crappy one from scratch. Any suggestions?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/surve

## Set up DoH on chrome android to use my own adguard home server ?
 - [https://www.reddit.com/r/selfhosted/comments/1h9fig6/set_up_doh_on_chrome_android_to_use_my_own](https://www.reddit.com/r/selfhosted/comments/1h9fig6/set_up_doh_on_chrome_android_to_use_my_own)
 - RSS feed: $source
 - date published: 2024-12-08T09:47:52+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I installés an adguard home server recently on my lan.</p> <p>The goal was to block / limit ads when browning the web on my Android phone (when Im connected to my WiFi)</p> <p>Problem :</p> <p>My ISP router is pushing its own IPv6 DNS server (which bypass the ipv4 DNS server) and I cannot change it on the router settings. </p> <p>To complicate things, my Android phone does not let me change the primary IPv6 DNS server on my WiFi connection (I can change the ipv4 DNS server ONLY)</p> <p>Workaround : It seems that the android chrome browser allows to set up a DNS over Https server. That whould do the trick I think.</p> <p>Does someones here succesfully use that feature, in order to use its own adguard home server (as a DoH server) ?</p> <p>I did not try it because i need a valid ssl certificate with my own domain and I dont have time right now to test this solution.</p> <p>Thank you !</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="ht

## Looking to backup VMware to Tape backup solution need suggestions for software
 - [https://www.reddit.com/r/selfhosted/comments/1h9ff85/looking_to_backup_vmware_to_tape_backup_solution](https://www.reddit.com/r/selfhosted/comments/1h9ff85/looking_to_backup_vmware_to_tape_backup_solution)
 - RSS feed: $source
 - date published: 2024-12-08T09:41:15+00:00

<!-- SC_OFF --><div class="md"><p>One of my client current setup, they manage a VMware environment hosting around 20 virtual machines (VMs) used for various business-critical operations, such as: 1. A database server handling customer records. 2. A file server for internal documents. 3. Application servers running key tools for my team. With data usage growing steadily, we needed a cost-effective and secure solution for backing up these VMs, especially for long-term retention and disaster recovery. So we are currently looking to backup using Tape backup solution. I have shortlisted Vinchin backup solution it offer Tape backup. However, I am open for suggestions. </p> <p>If anyone is considering a similar setup or has implemented tape backups, I’m happy to know more details!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DigitalWorld90"> /u/DigitalWorld90 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9ff85/looking_to_b

## Codiad/Cloud9/PythonAnywhere Alternative
 - [https://www.reddit.com/r/selfhosted/comments/1h9f9iw/codiadcloud9pythonanywhere_alternative](https://www.reddit.com/r/selfhosted/comments/1h9f9iw/codiadcloud9pythonanywhere_alternative)
 - RSS feed: $source
 - date published: 2024-12-08T09:29:44+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m working on a project to run a load of Matrix bots within my own tailnet. To ease the administration of this I&#39;ve been looking into a self hosted version of PythonAnywhere, basically just an online python IDE. A lot of the ones i have found are no longer maintained. This confuses my because it either means the demand is no longer there, which i doubt is true, or there is now one overarching winner which all users migrated over to, which i am unable to find! Can anyone offer any insight/advice please?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Heavy_Peak659"> /u/Heavy_Peak659 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9f9iw/codiadcloud9pythonanywhere_alternative/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9f9iw/codiadcloud9pythonanywhere_alternative/">[comments]</a></span>

## Should I buy it?
 - [https://www.reddit.com/r/selfhosted/comments/1h9f5zp/should_i_buy_it](https://www.reddit.com/r/selfhosted/comments/1h9f5zp/should_i_buy_it)
 - RSS feed: $source
 - date published: 2024-12-08T09:22:41+00:00

<!-- SC_OFF --><div class="md"><p>I always used Mini PC-s and Raspberry Pis and I tought about upgrading my home setup so I checked local ads and found a Primergy RX1330 M2 server for 87€ (or 92$) only thing is missing is storage. Would it be a good buy?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/xdygtsm"> /u/xdygtsm </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9f5zp/should_i_buy_it/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9f5zp/should_i_buy_it/">[comments]</a></span>

## Requesting feedback on Stock Screener using LLMs with explainable SQL query and 350+ metrics (Hosted on Home Server)
 - [https://www.reddit.com/r/selfhosted/comments/1h9evvy/requesting_feedback_on_stock_screener_using_llms](https://www.reddit.com/r/selfhosted/comments/1h9evvy/requesting_feedback_on_stock_screener_using_llms)
 - RSS feed: $source
 - date published: 2024-12-08T09:02:00+00:00

<!-- SC_OFF --><div class="md"><p>I have been working LLM powered stock market screener which executes SQL queries against 1000+ companies database for stocks trading in US. Additionally it shows tables, charts, company insights page with most up-to-date stock market insights.</p> <p>The aim is to identify companies based on any metric combination and subsequently present an aggregate insights. You may ask questions like:</p> <ul> <li>Identify top 3 companies with an analyst price target high that exceeds the current stock price by more than 50%</li> <li>Top companies by revenues in e-commerce, They should be undervalued based on DCF.</li> <li>Companies with increasing net profits across last 3 quarters.</li> </ul> <p>Website link in comments</p> <p>&lt;&lt;Best Viewed on Laptop screen&gt;&gt;</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Medical-Mistake3128"> /u/Medical-Mistake3128 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted

## Node/express and MongoDB
 - [https://www.reddit.com/r/selfhosted/comments/1h9eeol/nodeexpress_and_mongodb](https://www.reddit.com/r/selfhosted/comments/1h9eeol/nodeexpress_and_mongodb)
 - RSS feed: $source
 - date published: 2024-12-08T08:26:41+00:00

<!-- SC_OFF --><div class="md"><p>Thinking of self hosting a node server running with mongodb all in docker on a vps.</p> <p>Also adding Prometheus and Grafanna for logging.</p> <p>Any done something similar I plan to write my own scripts to perform my own db backups ect. Anyone know if I can get away with a 2vm with 2gb ram vps to handle this? I want to run this to support my mobile app storage which I expect would not have much traffic at first but I’m doing a lot of caching and offline first to avoid it being db heavy on calls.</p> <p>I plan to do some load testing but nothing beats real world experience.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lamagy"> /u/lamagy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9eeol/nodeexpress_and_mongodb/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9eeol/nodeexpress_and_mongodb/">[comments]</a></span>

## Building a showroom website
 - [https://www.reddit.com/r/selfhosted/comments/1h9e9ew/building_a_showroom_website](https://www.reddit.com/r/selfhosted/comments/1h9e9ew/building_a_showroom_website)
 - RSS feed: $source
 - date published: 2024-12-08T08:16:00+00:00

<!-- SC_OFF --><div class="md"><p>I want to build a sort of &quot;showroom&quot; online where men can post anonymously pictures of other men (consensually ofc), into a sort of profile showcasing them. I&#39;d like it to have features like &quot;see a random ***&quot; where people just click and it brings them to a random profile, or even a &quot;*** of the day!&quot; thing. I guess it&#39;s a sort of gallery, but I only ever built self-hosted wordpress sites. I&#39;m not sure it&#39;s the best tool for this job.<br/> I remember a website where people can post intimate pictures of them, with some sort of timer and as long as people would add time on the timer, the picture would stay up. I think it&#39;s a feature I&#39;d like as well. </p> <p>Can anyone put me on the right track by suggesting a CMS or another self-hosted solution that can carry the project with as little hassle and headaches as possible?</p> <p>If another man would like to join in on the project, I would appreciate ha

## Best DL spotify playlist
 - [https://www.reddit.com/r/selfhosted/comments/1h9ddsj/best_dl_spotify_playlist](https://www.reddit.com/r/selfhosted/comments/1h9ddsj/best_dl_spotify_playlist)
 - RSS feed: $source
 - date published: 2024-12-08T07:11:46+00:00

<!-- SC_OFF --><div class="md"><p>Is there a service that uses spotify playlist &#39;t, downloads those on YouTube, organizers them in a folder structure for jellyfin -and- wraps it all in a playlist m3u file?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jeroenishere12"> /u/jeroenishere12 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9ddsj/best_dl_spotify_playlist/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9ddsj/best_dl_spotify_playlist/">[comments]</a></span>

## 2 instances of Adguard Home and Unbound
 - [https://www.reddit.com/r/selfhosted/comments/1h9cx86/2_instances_of_adguard_home_and_unbound](https://www.reddit.com/r/selfhosted/comments/1h9cx86/2_instances_of_adguard_home_and_unbound)
 - RSS feed: $source
 - date published: 2024-12-08T06:39:56+00:00

<!-- SC_OFF --><div class="md"><p>I have 2 servers, both running their own Adguard Home and Unbound as upstream.</p> <p>My question is whether I should only fill in the Unbound upstream IP from that specific server, or if I should also add the Unbound upstream IP from the other server?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mike_v_E"> /u/Mike_v_E </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9cx86/2_instances_of_adguard_home_and_unbound/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9cx86/2_instances_of_adguard_home_and_unbound/">[comments]</a></span>

## Traveling with the family
 - [https://www.reddit.com/r/selfhosted/comments/1h9bys2/traveling_with_the_family](https://www.reddit.com/r/selfhosted/comments/1h9bys2/traveling_with_the_family)
 - RSS feed: $source
 - date published: 2024-12-08T05:36:30+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1h9bys2/traveling_with_the_family/"> <img src="https://b.thumbs.redditmedia.com/r6AZbLpn4oqqj4Gdi9S9oTzuz3BvgTjrHgRZDBdL3bY.jpg" alt="Traveling with the family" title="Traveling with the family" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Watched a Network Chuck video a while back that I thought was cool. He built a travel router for all of the family&#39;s devices while traveling and took a swing at it. The concept is to have one device that allows for a dedicated VPN connection (I personally use NordVPN) for all devices while in the hotel. I also purchased a mini PC and upgraded with a 1TB M.2 for more storage. Its running Proxmox to add a set of VM servers. The first is a small NAS runing trueNAS and the second is a Jellyfin server so my kiddo can watch whatever she wants from home. I added a Ugreen usb power port to run everything from one plug. Pictures included for what was purchased to make it all w

## How to get lots of mails from gmail and archive locally?
 - [https://www.reddit.com/r/selfhosted/comments/1h9bptz/how_to_get_lots_of_mails_from_gmail_and_archive](https://www.reddit.com/r/selfhosted/comments/1h9bptz/how_to_get_lots_of_mails_from_gmail_and_archive)
 - RSS feed: $source
 - date published: 2024-12-08T05:21:01+00:00

<!-- SC_OFF --><div class="md"><p>For the lack of self-hosting power, I used to archive my emails from gmail as <code>*.eml</code> over the years. The folder currently holds about 120.000 Emails from 2001 to 2020. I upgraded my hardware and now I can start moving this archive to Dovecot (mailcow-dockerized) with <code>fts-flatcurve</code> (Full text Search).</p> <p><em>However</em>, my current problem - I seem to have missed a couple of folders on gmail, the ones that are automatically labelled (commercial, social, notification, forums). There&#39;s about 20k of mails before 2020 in these folders.</p> <p>I would like to: - download these as <code>*.eml</code> - remove from gmail</p> <p>What I usually did: - create a label on gmail, filter with <code>before:2020/01/01</code> - wait an hour until gmail has finished labelling all mails - open Thunderbird, export emails with the <a href="https://addons.thunderbird.net/en-us/thunderbird/addon/importexporttools-ng/">ImportExportTools NG Ex

## Kernel Firewall: Dynamic Adaptive Packet Filter Agent
 - [https://www.reddit.com/r/selfhosted/comments/1h9bcs8/kernel_firewall_dynamic_adaptive_packet_filter](https://www.reddit.com/r/selfhosted/comments/1h9bcs8/kernel_firewall_dynamic_adaptive_packet_filter)
 - RSS feed: $source
 - date published: 2024-12-08T04:59:26+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>We are building a lightweight kernel level firewall to effectively mitigate ddos, manage network congestion/latency. It works by throtlling packets per IP per second and also monitoring new connections and dropping if they are from bad actors. Also support ip blacklist, greylist and whitelist.</p> <p>This should be able to work with any existing firewall like pfsense, iptables running on a linux kernel (version &gt; 5.1).</p> <p>The current offerings are:</p> <p>- Dyanmic Adaptive Kernel level packet rate limiter. Prevent DDoS.</p> <p>- Seamlessly integrate with existing firewalls and IDS/IPS</p> <p>- Ensure operational efficieny</p> <p>- Create global IP Whitelist, Blacklist and GreyList.</p> <p>- Redirect packets to different IP/interface</p> <p>- Build network traffic optimizer</p> <p>- Build optimal network load balancer</p> <p>- Block Bots and other bad traffic</p> <p>- Avert Cyber Attacks Efficiently</p> <p>If you would like to discu

## Free Domain service provider for self-hosting?
 - [https://www.reddit.com/r/selfhosted/comments/1h9b3zi/free_domain_service_provider_for_selfhosting](https://www.reddit.com/r/selfhosted/comments/1h9b3zi/free_domain_service_provider_for_selfhosting)
 - RSS feed: $source
 - date published: 2024-12-08T04:44:33+00:00

<!-- SC_OFF --><div class="md"><p>I am somewhat of a newb. That being said, I am currently running my Jellyfin on a RPi-5. The apps involved in achieving this- Portainer, Jellyfin, Nginx Proxy Manager. I am using DuckDns for domain. Unfortunately, Chrome flags my url as dangerous. I am guessing because of DuckDns.</p> <p>I was wondering if there are any free alternative to achieving the domain situation? I know it is super cheap to get a domain but I just started and most of the time I am figuring things out. </p> <p>I do have a Hostgator account from which I did create a domain. Unfortunately, I don&#39;t know how I can set it up in Nginx Proxy Manager. Is there any way I can use my Hostgator domain with NPM?</p> <p>I would really appreciate some suggestions. Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/consig1iere"> /u/consig1iere </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9b3zi/free_domain_service_prov

## HELPPPPPP! i installed pihole and i lose internet to my server so i tried uninstalling it still no internet
 - [https://www.reddit.com/r/selfhosted/comments/1h9b0sn/helpppppp_i_installed_pihole_and_i_lose_internet](https://www.reddit.com/r/selfhosted/comments/1h9b0sn/helpppppp_i_installed_pihole_and_i_lose_internet)
 - RSS feed: $source
 - date published: 2024-12-08T04:39:06+00:00

<!-- SC_OFF --><div class="md"><p>so i just set up pi home on my server inside ubuntu server lxc on proxmox.</p> <p>i changed the DNS address on my router but it didn&#39;t worked so I added changed to DNS on my PC to test it, and same thing it didn t work again. so I generated a debug log and then I did see some queries but that was all. i also tried to get a debug token but it said &quot;There was an error uploading your debug log.&quot;</p> <p>so yeah I need helpppppppppp.</p> <p>Thank you for any suggestions</p> <p>oh and I just checked I lost internet to my server</p> <p>Update:- after all that I kinda panicked and uninstalled pihole using &quot;pihole uninstall&quot; I still don&#39;t have no internet on my server.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Agreeable_Middle_711"> /u/Agreeable_Middle_711 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9b0sn/helpppppp_i_installed_pihole_and_i_lose_internet/">[li

## What else should I add to complete the homelab?
 - [https://www.reddit.com/r/selfhosted/comments/1h99v5c/what_else_should_i_add_to_complete_the_homelab](https://www.reddit.com/r/selfhosted/comments/1h99v5c/what_else_should_i_add_to_complete_the_homelab)
 - RSS feed: $source
 - date published: 2024-12-08T03:32:27+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1h99v5c/what_else_should_i_add_to_complete_the_homelab/"> <img src="https://preview.redd.it/oj5j1l6coj5e1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=15a07702eb60c7856fa392b8fd2d01396b041dd8" alt="What else should I add to complete the homelab? " title="What else should I add to complete the homelab? " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Dell mini for my hypervisor (pve host). A watchguard firewall. Synology for back ups, and a Zyxel managed switch...also everything is on a battery back up. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/languidhands"> /u/languidhands </a> <br/> <span><a href="https://i.redd.it/oj5j1l6coj5e1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h99v5c/what_else_should_i_add_to_complete_the_homelab/">[comments]</a></span> </td></tr></table>

## Help
 - [https://www.reddit.com/r/selfhosted/comments/1h9983t/help](https://www.reddit.com/r/selfhosted/comments/1h9983t/help)
 - RSS feed: $source
 - date published: 2024-12-08T02:56:15+00:00

<!-- SC_OFF --><div class="md"><p>Can anyone help me find an open source self hosted CAD software (Computer Aided Dispatch)? ive been looking for an actual good one that fits my needs but i can&#39;t seem to find one that works for me. Ive tried the following: Resgrid SnailyCad v4 LibreDispatch I mostly found that Resgrid is really hard to set up and maintain without hosting it with a 3rd party, and SnailyCad is mostly meant for GTA V FiveM roleplay, and it works, but its meant for GTA V. im looking for one that i can have all the street names in my area, a map of the area/county im in, and one thats (obviously) open source and self hosted</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Low_Television_4498"> /u/Low_Television_4498 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9983t/help/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9983t/help/">[comments]</a></span>

## DNS(?) issue where I can't resolve paths from nginx proxy manager. Tips on how to debug?
 - [https://www.reddit.com/r/selfhosted/comments/1h993mh/dns_issue_where_i_cant_resolve_paths_from_nginx](https://www.reddit.com/r/selfhosted/comments/1h993mh/dns_issue_where_i_cant_resolve_paths_from_nginx)
 - RSS feed: $source
 - date published: 2024-12-08T02:49:22+00:00

<!-- SC_OFF --><div class="md"><p>Setting up my first home server and I now have several containers running successfully in docker containers using compose on a debian 12 server. After confirming everything basically worked I was psyched but remembering the port number of every service is obviously less than ideal so I wanted to setup a reverse proxy to simplify things by giving them names. After watching Wolfgang&#39;s Channel&#39;s guide to <a href="https://www.youtube.com/watch?v=qlcVx-k-02E">Quick and Easy Local SSL Certificates for Your Homelab</a> I figured I&#39;d go with the custom domain and nginx proxy manager setup he features there because it seemed really straightforward. So I did the following:</p> <ol> <li><p>I bought my domain with porkbun </p></li> <li><p>I switched my nameservers to cloudflare. </p></li> <li><p>I created a new <code>a</code> entry with <code>mydomain.tld</code> pointed towards <code>local.ip.of.my.server</code> and created an additional <code>cname<

## Weird situation. How to tell what is running at the root of my domain?
 - [https://www.reddit.com/r/selfhosted/comments/1h98qns/weird_situation_how_to_tell_what_is_running_at](https://www.reddit.com/r/selfhosted/comments/1h98qns/weird_situation_how_to_tell_what_is_running_at)
 - RSS feed: $source
 - date published: 2024-12-08T02:29:12+00:00

<!-- SC_OFF --><div class="md"><p>Ok, so this stems from me being inexperienced. </p> <p>I bought a domain from Cloudflare, mydomain.com. I have been using Cloudflare Tunnels, creating subdomains to access my internal services (service1.mydomain.com, etc). However, I don&#39;t believe I am running anything on the core domain (again, mydomain.com). But when accessing some of my subdomains today, I started getting Google&#39;s Dangerous Site, necessitating clicking through to see my services. They say my domain is phishing.</p> <p>What is STRANGE, is that when I go to mydomain.com -- which, again, I don&#39;t think I&#39;m running anything on -- there is an authentication dialog that pops up. When I plugged in the info I usually use for my services, I got a Not Authorized message. </p> <p>Now I am concerned that somehow, someone is camping on my domain, and ADDITIONALLY, that I just offered up my login credentials to them. Is this possible? I thought I knew what I was doing, but this i

## What Can I do to be more secure?
 - [https://www.reddit.com/r/selfhosted/comments/1h9869v/what_can_i_do_to_be_more_secure](https://www.reddit.com/r/selfhosted/comments/1h9869v/what_can_i_do_to_be_more_secure)
 - RSS feed: $source
 - date published: 2024-12-08T01:58:14+00:00

<!-- SC_OFF --><div class="md"><p>I self host some stuff, mostly just media and game servers </p> <p>a few things are exposed to the internet through nginx proxy manager handling ssl and have it proxied through cloudflare, and thats really it. How bad is that? what changes should I be making?</p> <p>Also, is it okay to have programs accessible IN network via just ports?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/HopeDoesStufff"> /u/HopeDoesStufff </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9869v/what_can_i_do_to_be_more_secure/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h9869v/what_can_i_do_to_be_more_secure/">[comments]</a></span>

## should i start selfhosting?
 - [https://www.reddit.com/r/selfhosted/comments/1h96d1j/should_i_start_selfhosting](https://www.reddit.com/r/selfhosted/comments/1h96d1j/should_i_start_selfhosting)
 - RSS feed: $source
 - date published: 2024-12-08T00:24:38+00:00

<!-- SC_OFF --><div class="md"><p>hello! i have a website hosted on AWS free tier. it&#39;s just a personal project, nothing huge. i have a few questions:</p> <p>-would a raspberry pi be suitable for selfhosting?</p> <p>-would it be significantly cheaper, in the long run, to buy a pi than host it on AWS?</p> <p>-how hard would it be to migrate my site?</p> <p>-are there any good tutorials on how to do this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/m1ndfuzzz"> /u/m1ndfuzzz </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h96d1j/should_i_start_selfhosting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h96d1j/should_i_start_selfhosting/">[comments]</a></span>

