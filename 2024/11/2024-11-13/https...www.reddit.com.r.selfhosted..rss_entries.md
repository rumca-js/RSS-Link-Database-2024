# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## 3960x and MSI TRX40 MOBO detecting all of my RAM sticks, but only giving me half of my RAM
 - [https://www.reddit.com/r/selfhosted/comments/1gqq866/3960x_and_msi_trx40_mobo_detecting_all_of_my_ram](https://www.reddit.com/r/selfhosted/comments/1gqq866/3960x_and_msi_trx40_mobo_detecting_all_of_my_ram)
 - RSS feed: $source
 - date published: 2024-11-13T23:00:55+00:00

<!-- SC_OFF --><div class="md"><p>Right, this is a shot in the dark as I&#39;m now at the end of my wits. I&#39;ve recently put together a &quot;new&quot; system out of some parts I&#39;ve acquired, ordered myself 256gb of Kingston 3200 DDR4 and installed it in an MSI TRX40 10g plus. The problem I&#39;m having is that even in BIOS, the full system RAM caps out at 128gb, despite the BIOS correctly identifying the make and model of each RAM stick in <strong>all 8 slots</strong>. </p> <p>Steps I&#39;ve taken so far:</p> <ul> <li>Revert BIOS settings to defaults, which puts all of the RAM at 2400 </li> <li>Activate XMP</li> <li>set default RAM profile to 3200, which resulted in needing to do a CMOS reset</li> <li>Updated the BIOS to the latest version</li> <li>Reseated my RAM</li> <li>Reconnected all of my power cables etc.</li> </ul> <p>I have successfully got Proxmox running on the machine, which also only recognises 128gb of total RAM. This has, however, allowed me to get an output fr

## TTeck has passed away
 - [https://www.reddit.com/r/selfhosted/comments/1gqpo70/tteck_has_passed_away](https://www.reddit.com/r/selfhosted/comments/1gqpo70/tteck_has_passed_away)
 - RSS feed: $source
 - date published: 2024-11-13T22:36:29+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gqpo70/tteck_has_passed_away/"> <img src="https://external-preview.redd.it/3K1NI77qCuC_3qg-qd_8_il6__MvAlnM_Dtoo_s9m1E.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=9f8f9e099f9cc72cc7d44b1fa659cfbe3df91970" alt="TTeck has passed away" title="TTeck has passed away" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/-eschguy-"> /u/-eschguy- </a> <br/> <span><a href="https://github.com/community-scripts/ProxmoxVE/discussions/237">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqpo70/tteck_has_passed_away/">[comments]</a></span> </td></tr></table>

## Gunicorn process using 293.7% of cpu?
 - [https://www.reddit.com/r/selfhosted/comments/1gqosmw/gunicorn_process_using_2937_of_cpu](https://www.reddit.com/r/selfhosted/comments/1gqosmw/gunicorn_process_using_2937_of_cpu)
 - RSS feed: $source
 - date published: 2024-11-13T21:58:01+00:00

<!-- SC_OFF --><div class="md"><p>I have no idea where to begin, and when i try to find where this is coming from it says the directory cannot be found.</p> <p>Anyone have any ideas where to start with fixing this? Would it be dangerous to sudo kill it?</p> <p>Below is a selection of process that seem to be running, including the unknown &#39;Gunicorn&#39; taking 293% cpu:</p> <pre><code>Tasks: 273 total, 1 running, 272 sleeping, 0 stopped, 0 zombie %Cpu(s): 88.9 us, 7.7 sy, 0.0 ni, 0.1 id, 0.0 wa, 0.0 hi, 3.4 si, 0.0 st MiB Mem : 7733.5 total, 335.3 free, 4355.2 used, 4766.5 buff/cache MiB Swap: 4096.0 total, 1822.2 free, 2273.8 used. 3378.4 avail Mem PID USER PR NI VIRT RES SHR S %CPU %MEM TIME+ COMMAND 1268998 root 20 0 3236844 367044 7680 S 293.7 4.6 11d+23h gunicorn 1001716 root 20 0 12.3g 204876 23080 S 66.1 2.6 74,48 immich 55731 dnsmasq 20 0 1048504 127124 1152 S 33.9 1.6 39,36 redis-server 1680 jonny 20 0 471988 3968 2688 S 1.7 0.1 45:01.94 gvfs-udisks2-vo 1 root 20 0 23608 

## Refactor the HomeLab: do I proxmox it or nah?
 - [https://www.reddit.com/r/selfhosted/comments/1gqnj0i/refactor_the_homelab_do_i_proxmox_it_or_nah](https://www.reddit.com/r/selfhosted/comments/1gqnj0i/refactor_the_homelab_do_i_proxmox_it_or_nah)
 - RSS feed: $source
 - date published: 2024-11-13T21:04:17+00:00

<!-- SC_OFF --><div class="md"><p>Originally posted this in the wrong communtiy <a href="/r/homelab">r/homelab</a>, so I&#39;m repenting and posting here. </p> <p>Currently refactoring my home lab. Currently coming from a NAS with TrueNAS and a conglomeration of old computers running Ubuntu Server. My TrueNAS machine could probably survive another year or two, but I think she&#39;s ready to croak.</p> <p>I want to consolidate, reduce the amount of old machines. I got a new HP tower with 64 GB of RAM and I bought a GPU (sweet deal on an NVidia 3070 ti) to go with it for some upcoming ML projects. I&#39;m feeling a bit overwhelmed by all the options for refactoring.</p> <p>Here&#39;s what I am considering (open to more options):</p> <ol> <li>Proxmox on bare metal running TrueNAS, Ubuntu Server, and Ubuntu Desktop</li> <li>Proxmox on baremetal, using Cockpit for storage management, Ubuntu Server, and Ubuntu desktop (I have never used Cockpit)</li> <li>TrueNAS on bare metal, running Ubun

## Opening ports : how to
 - [https://www.reddit.com/r/selfhosted/comments/1gqncr5/opening_ports_how_to](https://www.reddit.com/r/selfhosted/comments/1gqncr5/opening_ports_how_to)
 - RSS feed: $source
 - date published: 2024-11-13T20:57:10+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m a non-technical, self-taught, enthusiast. </p> <p>I have a few VPS instances with Oracle. I self host some websites, erp and accounting programs for my small business, and am now exploring docker +portainer.</p> <p>I do not fully understand the concept of ports, how to map them and how to deploy containers or stacks on portainer. </p> <p>I&#39;ve managed deploying baserow.io successfully but was sort of a fluke. I&#39;d like to deploy odoo and plex but not sure how to get the ports aligned. </p> <p>Also, how do I add a custom domain to my deployed containers?</p> <p>Thankful for any advice!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/amerhabib"> /u/amerhabib </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqncr5/opening_ports_how_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqncr5/opening_ports_how_to/">[comments]</a></span>

## Ways to test my abilities
 - [https://www.reddit.com/r/selfhosted/comments/1gqn9q8/ways_to_test_my_abilities](https://www.reddit.com/r/selfhosted/comments/1gqn9q8/ways_to_test_my_abilities)
 - RSS feed: $source
 - date published: 2024-11-13T20:53:33+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, recently I’ve come to a point where I’m not entirely sure where to go in my homelab. I know there’s a plethora of things to do, but I guess I just don’t have any direction?</p> <p>Main server: Homarr Radarr Sonarr Audiobookshelf Readarr Mylarr Prowlarr Requestrr Immich Linkwarden Portainer Nextcloud Jellyseerer Qbit Jellyfin</p> <p>Dell r620: Proxmox Qbit Filebrowser </p> <p>Pi3: Octoprint</p> <p>Is like to make a career in IT so if there’s anything I can use these for to learn good skills, I’d much appreciate it. I’d also just like some fun stuff to run if possible. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ImaginaryRaccoon2106"> /u/ImaginaryRaccoon2106 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqn9q8/ways_to_test_my_abilities/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqn9q8/ways_to_test_my_abilities/">[comments]</a><

## Any self hostable service for archiving SMS messages from an Android device?
 - [https://www.reddit.com/r/selfhosted/comments/1gqlx8d/any_self_hostable_service_for_archiving_sms](https://www.reddit.com/r/selfhosted/comments/1gqlx8d/any_self_hostable_service_for_archiving_sms)
 - RSS feed: $source
 - date published: 2024-11-13T19:57:15+00:00

<!-- SC_OFF --><div class="md"><p>I don&#39;t need to send SMS from a server. I would just like to back up my phone to a server and then be able to read them back in some way later. Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Starboy_bape"> /u/Starboy_bape </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqlx8d/any_self_hostable_service_for_archiving_sms/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqlx8d/any_self_hostable_service_for_archiving_sms/">[comments]</a></span>

## K3S is awsome for your HomeServer(s) I used to use docker in a single node use last weekend i was bored and thought it was time to upgrade some stuff.. k3s is just dope + you can use longhorn in rancher do make everything persistent without any issues.. awsome stuff working!
 - [https://www.reddit.com/r/selfhosted/comments/1gqkq8y/k3s_is_awsome_for_your_homeservers_i_used_to_use](https://www.reddit.com/r/selfhosted/comments/1gqkq8y/k3s_is_awsome_for_your_homeservers_i_used_to_use)
 - RSS feed: $source
 - date published: 2024-11-13T19:07:10+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gqkq8y/k3s_is_awsome_for_your_homeservers_i_used_to_use/"> <img src="https://preview.redd.it/2khmaa11wp0e1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=1f52d5d73226c961102cd208fed31ec083af3c52" alt="K3S is awsome for your HomeServer(s) I used to use docker in a single node use last weekend i was bored and thought it was time to upgrade some stuff.. k3s is just dope + you can use longhorn in rancher do make everything persistent without any issues.. awsome stuff working! " title="K3S is awsome for your HomeServer(s) I used to use docker in a single node use last weekend i was bored and thought it was time to upgrade some stuff.. k3s is just dope + you can use longhorn in rancher do make everything persistent without any issues.. awsome stuff working! " /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Accomplished-Tip-227"> /u/Accomplished-Tip-227 </a> <br/> <span><a href="https:/

## Selfhosted virtual museum for a web browser?
 - [https://www.reddit.com/r/selfhosted/comments/1gqkoy8/selfhosted_virtual_museum_for_a_web_browser](https://www.reddit.com/r/selfhosted/comments/1gqkoy8/selfhosted_virtual_museum_for_a_web_browser)
 - RSS feed: $source
 - date published: 2024-11-13T19:05:42+00:00

<!-- SC_OFF --><div class="md"><p>I want to display some pictures, videos, and music within a virtual museum that users can walk around in and inspect using their browser. I want this to be selfhosted because I want to keep it private for only friends and family. Are there any open source projects out there that do something like this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Weak_Education_1778"> /u/Weak_Education_1778 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqkoy8/selfhosted_virtual_museum_for_a_web_browser/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqkoy8/selfhosted_virtual_museum_for_a_web_browser/">[comments]</a></span>

## Is there a selfhosted music manager with good analysis features?
 - [https://www.reddit.com/r/selfhosted/comments/1gqkljn/is_there_a_selfhosted_music_manager_with_good](https://www.reddit.com/r/selfhosted/comments/1gqkljn/is_there_a_selfhosted_music_manager_with_good)
 - RSS feed: $source
 - date published: 2024-11-13T19:01:53+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, I&#39;m a DJ, so I have a giant amount of tracks in all file formats under the sun. It is really hard to catalogue those by hand. Is there some software that can automatically tag them by genre, energy, ideally with tags? There are lots of desktop programs but pretty much all of them are lackluster at best, especially when recognizing really niche genres or adding metadata. </p> <p>I have a pretty nice homelab already so having all my music WITH this extra information available via some sort of web app would be immensely helpful.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mediocreAsuka"> /u/mediocreAsuka </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqkljn/is_there_a_selfhosted_music_manager_with_good/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqkljn/is_there_a_selfhosted_music_manager_with_good/">[comments]</a></span>

## Girl Scout Cookie Inventory Tracker
 - [https://www.reddit.com/r/selfhosted/comments/1gqjt0a/girl_scout_cookie_inventory_tracker](https://www.reddit.com/r/selfhosted/comments/1gqjt0a/girl_scout_cookie_inventory_tracker)
 - RSS feed: $source
 - date published: 2024-11-13T18:29:13+00:00

<!-- SC_OFF --><div class="md"><p>My daughters both sell Girl Scout cookies. (Yeah yeah it’s a total scam I have heard it all)</p> <p>I want to spin up a docker container with an inventory management tool on it. I am looking at Grocy right now and maybe inventree. Anyone have any other ideas. </p> <p>I have to manage inventory for multiple kids besides my own (basically the troop my wife leads) and sometimes prices are divergent between flavors (SKUs). </p> <p>Want to be able to use a hand scanner for counting and stuff.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/oklahomasooner55"> /u/oklahomasooner55 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqjt0a/girl_scout_cookie_inventory_tracker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqjt0a/girl_scout_cookie_inventory_tracker/">[comments]</a></span>

## Efficient Dotfile Management with MYD: Track, Upload, and Sync Dotfiles Easily
 - [https://www.reddit.com/r/selfhosted/comments/1gqiq7z/efficient_dotfile_management_with_myd_track](https://www.reddit.com/r/selfhosted/comments/1gqiq7z/efficient_dotfile_management_with_myd_track)
 - RSS feed: $source
 - date published: 2024-11-13T17:45:05+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gqiq7z/efficient_dotfile_management_with_myd_track/"> <img src="https://external-preview.redd.it/7vq4GRfBZJHhP0nCY2cl9hqfGcZ12jNoa7JJsJ7yQK8.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=de0147a150063db1d8dbf98dc1b09c94947af57c" alt="Efficient Dotfile Management with MYD: Track, Upload, and Sync Dotfiles Easily" title="Efficient Dotfile Management with MYD: Track, Upload, and Sync Dotfiles Easily" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://i.redd.it/wfryfdxmhp0e1.gif">https://i.redd.it/wfryfdxmhp0e1.gif</a></p> <p>MYD is a CLI tool designed for managing your dotfiles efficiently. It lets you track, update, and sync your dotfiles across systems by integrating with a GitHub repository.</p> <p>You can later install these dotfiles at their position using `myd install`</p> <p>Github Link : <a href="https://github.com/wraient/myd">https://github.com/wraient/myd</a></p> </div><!-- SC_ON --> 

## Faimly album
 - [https://www.reddit.com/r/selfhosted/comments/1gqhx7k/faimly_album](https://www.reddit.com/r/selfhosted/comments/1gqhx7k/faimly_album)
 - RSS feed: $source
 - date published: 2024-11-13T17:12:25+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, </p> <p>With the occasional phone replacement, I&#39;ve had to backup two storages in the family. I used two gmail accounts and now they are almost full.</p> <p>I used to have an HDD in the past for this, but it broke and we lost the data.</p> <p>Can anyone suggest a solution that is NOT cloud based, and that is reliable?</p> <p>I don&#39;t want to pay monthly for cloud storage and world much rather spend that money on a home solution. </p> <p>Mini NAS, a shit ton of DVDs? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ProfessionalMatter99"> /u/ProfessionalMatter99 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqhx7k/faimly_album/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqhx7k/faimly_album/">[comments]</a></span>

## Is there a self hosted customizable newsletter?
 - [https://www.reddit.com/r/selfhosted/comments/1gqhesg/is_there_a_self_hosted_customizable_newsletter](https://www.reddit.com/r/selfhosted/comments/1gqhesg/is_there_a_self_hosted_customizable_newsletter)
 - RSS feed: $source
 - date published: 2024-11-13T16:51:21+00:00

<!-- SC_OFF --><div class="md"><p>I used to like getting my daily newsletter email from the newspaper, but with the state of things I need to read that less. Ideally I&#39;d like to receive a customized newsletter hosted locally. Maybe local temperature and weather forecast, news scrapped from a local RSS feed, maybe shared announcements that apply to me and my family, and maybe even things like a report of energy use scrapped from the local utility website. Also things like the number of parking passes we have. Calendar info (like today is trash day.)</p> <p>Anyway, does anything like this exist? And ideally can it be self hosted as I would no ads, tracking or what have you?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Optimus_sRex"> /u/Optimus_sRex </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqhesg/is_there_a_self_hosted_customizable_newsletter/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/sel

## Tunnelmole 100 kb limit
 - [https://www.reddit.com/r/selfhosted/comments/1gqh7e2/tunnelmole_100_kb_limit](https://www.reddit.com/r/selfhosted/comments/1gqh7e2/tunnelmole_100_kb_limit)
 - RSS feed: $source
 - date published: 2024-11-13T16:42:40+00:00

<!-- SC_OFF --><div class="md"><p>Hello, recently I have been trying tunnelmole and have noticed that it limits upload to only below 100kb even though it is specified in the backend that it has a maximum of 5mb, I deduced this because locally it was working but the link from tunnelmole generates the error 413 content too large, is there a possible workaround this? The file I am trying to upload are not really big just alot.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/brudda65"> /u/brudda65 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqh7e2/tunnelmole_100_kb_limit/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqh7e2/tunnelmole_100_kb_limit/">[comments]</a></span>

## Moving behing a CGNAT, what to do to keep my server accesible?
 - [https://www.reddit.com/r/selfhosted/comments/1gqh6w4/moving_behing_a_cgnat_what_to_do_to_keep_my](https://www.reddit.com/r/selfhosted/comments/1gqh6w4/moving_behing_a_cgnat_what_to_do_to_keep_my)
 - RSS feed: $source
 - date published: 2024-11-13T16:42:03+00:00

<!-- SC_OFF --><div class="md"><p>My family is moving to a new home, and with that comes change of ISP. All ISPs available there demand eye-watering amounts of money for a public IPv4 (~45 USD per year at least) and I failed in convincing rest of my family it&#39;s worth it for side projects, and so we&#39;ll stick with a cheaper CGNAT option. More precisely, it&#39;s DS-Lite (native IPv6 and CGNAT-ted IPv4), as far as I know.</p> <p>Now I still don&#39;t want to lose all my stuff like Wireguard server or similar, so what options do I have? I don&#39;t want to pay for anything because then it&#39;d be easier to just get the public IP, so only free stuff. I was looking around ZeroTier, Tailscale, Cloudflare, <a href="http://playit.gg">playit.gg</a> and LocaltoNet, but so far haven&#39;t decided. Or would it be easier to just try to convince rest of my family that the money would be worth it?</p> <p>All I truly need is some way to get a Wireguard connection (or similar VPN) up from out

## Wireguard and docker
 - [https://www.reddit.com/r/selfhosted/comments/1gqgibw/wireguard_and_docker](https://www.reddit.com/r/selfhosted/comments/1gqgibw/wireguard_and_docker)
 - RSS feed: $source
 - date published: 2024-11-13T16:13:54+00:00

<!-- SC_OFF --><div class="md"><p>I started planning the following configuration and wonder if it even is a decent solution. </p> <p>I am currently running a low resource VPS (Headless Debian) with static IP that hosts the following docker containers: Kuma, NTFY, Nginx, Wireguard server (containerized). And at home I am running a decently powerful server (also headless Debian) with containers that include NexcloudAIO, NginX, Joplin, Homarr, StrilingPDF, and many others. </p> <p>My goal is to connect my laptop, home server, and VPS under the same tunnel so that all 3 devices can communicate seamlessly with their assigned IPs. This would allow me to have a solid layer of security thanks to Wireguard for SSH, SFTP, backups with Duplicati/Rsync... </p> <p>An example I hope to achieve is:</p> <p>https:/homarr.domain.tld&gt; nginx (VPS)&gt; wireguard container&gt; home server&gt; homarr container.</p> <p>At this stage I am trying to set up a Wireguard container as a peer on my home server.

## My WIP Homepage
 - [https://www.reddit.com/r/selfhosted/comments/1gqgeps/my_wip_homepage](https://www.reddit.com/r/selfhosted/comments/1gqgeps/my_wip_homepage)
 - RSS feed: $source
 - date published: 2024-11-13T16:09:42+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gqgeps/my_wip_homepage/"> <img src="https://a.thumbs.redditmedia.com/brqgbeUXmcsscQvbblz_Sj9-u5DRAT-LFIeKgMDdGq4.jpg" alt="My WIP Homepage" title="My WIP Homepage" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I think everybody around here is familiar with the GetHomepage project by now. Here’s my version of it with a little custom css for a neat highlight when you hover over each card (see the second image as a gif). </p> <p>There’s always more to add. Up next is an iframe implementation of grafana for some realtime charts. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/completelyreal"> /u/completelyreal </a> <br/> <span><a href="https://www.reddit.com/gallery/1gqgeps">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqgeps/my_wip_homepage/">[comments]</a></span> </td></tr></table>

## Home assistant and media server setup advice
 - [https://www.reddit.com/r/selfhosted/comments/1gqgdvc/home_assistant_and_media_server_setup_advice](https://www.reddit.com/r/selfhosted/comments/1gqgdvc/home_assistant_and_media_server_setup_advice)
 - RSS feed: $source
 - date published: 2024-11-13T16:08:45+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, </p> <p>I’m looking for advice on how to set up a self-hosted system that meets my needs in a way that’s simple, efficient, and easy to maintain. </p> <p>My primary goals are running Home assistant and media server services: </p> <p>- Home Assistant </p> <p>- Jellyfin</p> <p>- Arr suite: Radarr, Sonarr, Prowlarr </p> <p>- A torrent client </p> <p>Both the torrent client and all the services in the ARR Suite should operate through a VPN for privacy. I’d like everything to run smoothly with minimal lag and prefer a setup that is easy to maintain. </p> <p>I’m considering options for hardware and installation. Should I get a small server or mini PC and use a virtualized environment like Proxmox or Docker? Would it make more sense to run Home Assistant OS on dedicated hardware, and a separate one for the other services or is there a better way to integrate all these services? I’m open to purchasing additional hardware but want to avoid overco

## Need help setting up my home server. I installed Debian, but I'm not sure how to proceed best. I tried finding tutorials but I cannot find anything good.
 - [https://www.reddit.com/r/selfhosted/comments/1gqfkge/need_help_setting_up_my_home_server_i_installed](https://www.reddit.com/r/selfhosted/comments/1gqfkge/need_help_setting_up_my_home_server_i_installed)
 - RSS feed: $source
 - date published: 2024-11-13T15:34:06+00:00

<!-- SC_OFF --><div class="md"><p>I want to setup a home server that has all sorts of things. I posted a topic a couple of days ago and decided that Debian in combination with Docker was the best setup. But I&#39;m not sure how to proceed. I installed Debian, and now I&#39;m looking at the GNOME screen. </p> <ul> <li>Bitcoin Node</li> <li>Lightning Node</li> <li>VPN access from outside</li> <li>Home assistant</li> <li>Netflix alternative (movies save + stream to phone/laptop)</li> <li>Spotify alternative (music save + stream to phone)</li> <li>Dropbox alternative (save local instead of at dropbox)</li> <li>Adblocker for my network</li> <li>Home Assistant</li> <li>BTCPay Server</li> <li>CoinJoin server</li> </ul> <p>Is it just best to install all these apart in Docker, but how is that a bit easy for a noob like me?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RonaldoRonny"> /u/RonaldoRonny </a> <br/> <span><a href="https://www.reddit.com/r/sel

## VPS security concern?
 - [https://www.reddit.com/r/selfhosted/comments/1gqfhul/vps_security_concern](https://www.reddit.com/r/selfhosted/comments/1gqfhul/vps_security_concern)
 - RSS feed: $source
 - date published: 2024-11-13T15:30:56+00:00

<!-- SC_OFF --><div class="md"><p>So I self host all the services we use and don&#39;t expect anything to change. My question is for those who also have a VPS backup.</p> <p>Are you concerned about the security of your VPS? What do you do to mitigate the risks?</p> <p>We had some recent extended down time which was nothing terrible outside of some minor annoyances but it made me wonder if I&#39;m better off with a 1 core 2GB VPS to host the most critical services, such as bitwarden.</p> <p>But then the thought of storing my personal password db online doesn&#39;t feel right at all. Sure I can be hacked but the probability of someone targeting an average Joe like me is pretty low. Compare that to the welknown VPS providers - I&#39;m sure they are actively being targeted, if not hacked already.</p> <p>Am I paranoid?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/testdasi"> /u/testdasi </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/

## Support for kubernetes gateway-api service discovery in homepage dashboard
 - [https://www.reddit.com/r/selfhosted/comments/1gqfg1p/support_for_kubernetes_gatewayapi_service](https://www.reddit.com/r/selfhosted/comments/1gqfg1p/support_for_kubernetes_gatewayapi_service)
 - RSS feed: $source
 - date published: 2024-11-13T15:28:53+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys,</p> <p>I recently made <a href="https://github.com/gethomepage/homepage/pull/4289#issue-2655076291">a PR</a> to Homepage that was rejected due to lack of support.</p> <p>If you want to get service discovery for kubernetes gateway-api in Homepage, please upvote this feature request <a href="https://github.com/gethomepage/homepage/discussions/4021#discussion-7220249">https://github.com/gethomepage/homepage/discussions/4021#discussion-7220249</a>.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/isleepbad"> /u/isleepbad </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqfg1p/support_for_kubernetes_gatewayapi_service/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqfg1p/support_for_kubernetes_gatewayapi_service/">[comments]</a></span>

## My first time running a Distributed File System cluster and it's a real game changer
 - [https://www.reddit.com/r/selfhosted/comments/1gqfegi/my_first_time_running_a_distributed_file_system](https://www.reddit.com/r/selfhosted/comments/1gqfegi/my_first_time_running_a_distributed_file_system)
 - RSS feed: $source
 - date published: 2024-11-13T15:26:57+00:00

<!-- SC_OFF --><div class="md"><p>Scheduling and clustering has been a thing for a long time now. There&#39;s solutions like docker swarm, nomad and the massive k8s to schedule containers on multiple nodes. 2 years ago I was still manually provisioning and setting up services outside of docker and giving all my servers cute names. But I wanted to up my game and go with a more &quot;cattle not pets&quot; solution. And oh boy, it sent me down a huge rabbit hole to get there but I finally did.</p> <p>So 2 years ago I set out to create a setup which I want to call the &quot;I don&#39;t care where it is&quot; setup. It has the following goals:</p> <ol> <li>Provision and extend a server cluster without manual intervention (for this, I used Ansible and wrote about 50+ ansible roles)</li> <li>Automatic HTTP and HTTPS routing, and SSL (for this, I used Consul and a custom script to generate nginx configs, and another script to generate certs using consul data)</li> <li>Schedule a docker conta

## Can filebrowser be configured to use LDAP authentication?
 - [https://www.reddit.com/r/selfhosted/comments/1gqeqsh/can_filebrowser_be_configured_to_use_ldap](https://www.reddit.com/r/selfhosted/comments/1gqeqsh/can_filebrowser_be_configured_to_use_ldap)
 - RSS feed: $source
 - date published: 2024-11-13T14:58:19+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve found conflicting information on this. The official documents don&#39;t seem to mention it, and I&#39;ve been beating my had against it for a week now. Can FileBrowser be configured to use a local LDAP container for auth?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PorcupineWarriorGod"> /u/PorcupineWarriorGod </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqeqsh/can_filebrowser_be_configured_to_use_ldap/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqeqsh/can_filebrowser_be_configured_to_use_ldap/">[comments]</a></span>

## Tools to create a new identity. (Looking for suggestions)
 - [https://www.reddit.com/r/selfhosted/comments/1gqeirr/tools_to_create_a_new_identity_looking_for](https://www.reddit.com/r/selfhosted/comments/1gqeirr/tools_to_create_a_new_identity_looking_for)
 - RSS feed: $source
 - date published: 2024-11-13T14:48:08+00:00

<!-- SC_OFF --><div class="md"><p>Apologies if this isn&#39;t the right sub, I&#39;m just curious how self-hosters would approach my use-case.</p> <p>I do music on the side, and a large part of music these days is networking. That being said, I&#39;m a completely faceless musician and want to keep it that way. The ideal scenario is complete isolation from my other profiles/socials on phone and computer. This is needed these days to be truly faceless as social media will use ALL of the data on you to recommend your aliases to friends / family which I do not want. </p> <p>I played around with this idea a while back, I put a custom ROM on an old android phone and linked up to a VPN but once I started making social profiles and signing into things I started getting banned since I (understandably) looked like a bot.</p> <p>I have a Proxmox server set up which would let me set up a VM on a VPN but I&#39;d probably just run into the same issues..</p> <p>Any advice on how I might achieve a t

## Open Source Project Workflow / Task Management Tools with different user permission and workflow automation?
 - [https://www.reddit.com/r/selfhosted/comments/1gqdi6z/open_source_project_workflow_task_management](https://www.reddit.com/r/selfhosted/comments/1gqdi6z/open_source_project_workflow_task_management)
 - RSS feed: $source
 - date published: 2024-11-13T14:00:14+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I have been looking for a workflow / task management tools that have a built in user management. Ideally would like to have the following features:</p> <ul> <li>Built-in user management with different level of permission settings</li> <li>Integration with some common business platform like Xero, Slack etc</li> <li>Integration with Digital asset management, can be as simple as Google Drive etc.</li> <li>Easy to change, flow type of custom workflow definition.</li> <li>Ease of use for general users</li> </ul> <p>I have read through some open source project management tools which focus more on project management overall but not workflow management or automation. Workflow systems, on the other hand, seems to be more on task automation but no user management.</p> <p>Just want to check if there&#39;s something out there before I re-invent the wheel! Thank you.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/qu

## I want to test my nextcloud server with a lot of people for a school project.
 - [https://www.reddit.com/r/selfhosted/comments/1gqdewe/i_want_to_test_my_nextcloud_server_with_a_lot_of](https://www.reddit.com/r/selfhosted/comments/1gqdewe/i_want_to_test_my_nextcloud_server_with_a_lot_of)
 - RSS feed: $source
 - date published: 2024-11-13T13:55:37+00:00

<!-- SC_OFF --><div class="md"><p>So, I have to get people to complete this form in order to study its responses for a school project. The thing is that I used nextcloud forms, and I want to push it to its limits to see if my setup is well built and public proof.</p> <p><a href="https://cloud.tomasps.com/apps/forms/s/wMD2MwKBrtoAdiT8Yrz7LAee">https://cloud.tomasps.com/apps/forms/s/wMD2MwKBrtoAdiT8Yrz7LAee</a> (The form is in Spanish, but ig you can translate it using your browser)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Tresillo_Crack"> /u/Tresillo_Crack </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqdewe/i_want_to_test_my_nextcloud_server_with_a_lot_of/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqdewe/i_want_to_test_my_nextcloud_server_with_a_lot_of/">[comments]</a></span>

## Temporary Backup
 - [https://www.reddit.com/r/selfhosted/comments/1gqdbpt/temporary_backup](https://www.reddit.com/r/selfhosted/comments/1gqdbpt/temporary_backup)
 - RSS feed: $source
 - date published: 2024-11-13T13:51:06+00:00

<!-- SC_OFF --><div class="md"><p>I have about 16Tb of data I&#39;d like to backup to a cloud server for temporary storage when I remove a JBOD collection of 2Tb and 4Tb drives to replace them with two 14Tb Drives. This is basically media files I have on my server and these drives are getting old and I&#39;m running out of room on my CoveCube Drive Pool.</p> <p>I&#39;m looking for suggestions on a decently priced location to store this data for a week or two while I reconfigure this computer. I&#39;m also interested in the methodology/best practice for accomplishing this task.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Spiritual_Till5585"> /u/Spiritual_Till5585 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqdbpt/temporary_backup/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqdbpt/temporary_backup/">[comments]</a></span>

## cleanuperr - your input is needed!
 - [https://www.reddit.com/r/selfhosted/comments/1gqcxht/cleanuperr_your_input_is_needed](https://www.reddit.com/r/selfhosted/comments/1gqcxht/cleanuperr_your_input_is_needed)
 - RSS feed: $source
 - date published: 2024-11-13T13:31:17+00:00

<!-- SC_OFF --><div class="md"><p>Recently I&#39;ve made <a href="https://www.reddit.com/r/sonarr/comments/1gob7ph/malicious_torrent_cleanup_tool/">a post</a> about a simple tool to help us dodge malicious torrents.</p> <p>I am currently working on extending this tool to support Radarr, but I&#39;m also looking into supporting other download clients, other than qBittorrent. This is where I need your input so I can understand what the community needs.</p> <p>I&#39;ve created a very small survey (9 questions) and I would appreciate if you took the time to answer the questions:</p> <p><a href="https://s.surveyplanet.com/2kcorpy0">https://s.surveyplanet.com/2kcorpy0</a></p> <p>Unfortunately I can&#39;t post a survey on Sonarr&#39;s reddit, so I&#39;m trying it here.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Flaminel"> /u/Flaminel </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqcxht/cleanuperr_your_input_is_needed/">[l

## Baserow 1.29: PostgreSQL, GitLab, GitHub and Jira data syncs, AI field updates, workspace export and import, shared data sources, and filtering, sorting, and searching for published apps, and more! — Open Source Airtable Alternative
 - [https://www.reddit.com/r/selfhosted/comments/1gqcuci/baserow_129_postgresql_gitlab_github_and_jira](https://www.reddit.com/r/selfhosted/comments/1gqcuci/baserow_129_postgresql_gitlab_github_and_jira)
 - RSS feed: $source
 - date published: 2024-11-13T13:26:59+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gqcuci/baserow_129_postgresql_gitlab_github_and_jira/"> <img src="https://external-preview.redd.it/NotNvoHZIKkV35Vo5_PthdOTs6Uig3uv4WNSAGD9QsQ.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=f6af4475511a696c84ba88ae9b669dfbc64881eb" alt="Baserow 1.29: PostgreSQL, GitLab, GitHub and Jira data syncs, AI field updates, workspace export and import, shared data sources, and filtering, sorting, and searching for published apps, and more! — Open Source Airtable Alternative" title="Baserow 1.29: PostgreSQL, GitLab, GitHub and Jira data syncs, AI field updates, workspace export and import, shared data sources, and filtering, sorting, and searching for published apps, and more! — Open Source Airtable Alternative" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>This release brings exciting new features to Baserow, including data sync integrations with Jira, GitLab, GitHub, and PostgreSQL for seamless data updates acros

## Web services protection with firewall
 - [https://www.reddit.com/r/selfhosted/comments/1gqcoe9/web_services_protection_with_firewall](https://www.reddit.com/r/selfhosted/comments/1gqcoe9/web_services_protection_with_firewall)
 - RSS feed: $source
 - date published: 2024-11-13T13:18:42+00:00

<!-- SC_OFF --><div class="md"><p>Hi Reddit, noob here.</p> <p>I bet these questions get asked alot, yet I didn&#39;t found the answers I&#39;m looking for. I&#39;m running an homelab with 20+ services. Since a month or so, I&#39;m hosting Plex totally open. It&#39;s accessible with an domain I bought on Cloudflare, and my public ip:port. NPM is doing the proxy work. </p> <p>I&#39;m at the point I want to open more services (Home Assistant to be exact). Now the itching starts of not being secure enough. I can reach all my services if needed to outside through Tailscale. This so I can do some maintaining while on the road. I need to have Plex &amp; HA more open (not through a VPN) for easy access for my family members. They&#39;re streaming media from their home etc. </p> <p>For now I think the best thing to do is lock up my firewall. Only in &amp; out what we need to. What would be the best approach?</p> <p>I have an xperiabox V10 as my router (us dutchies with KPN know what I&#39;m 

## Sick of overpaying for AWS
 - [https://www.reddit.com/r/selfhosted/comments/1gqc9b4/sick_of_overpaying_for_aws](https://www.reddit.com/r/selfhosted/comments/1gqc9b4/sick_of_overpaying_for_aws)
 - RSS feed: $source
 - date published: 2024-11-13T12:57:07+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gqc9b4/sick_of_overpaying_for_aws/"> <img src="https://preview.redd.it/hifni8ea2o0e1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=b558f6bf8b246fcf33ecd95b59d2e65da2d712ba" alt="Sick of overpaying for AWS" title="Sick of overpaying for AWS" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I have a few domains with low traffic, and I have it all in one instance of the cheapest, smallest AWS instances, but with storage, traffic and load balancer I end up paying a lot of money every month.</p> <p>So as I move to upgrade my main PC, I&#39;ll take my previous PC and turn it into my self hosted environment. I already have static IP with a solid ISP, and I&#39;m buying a new PC anyways, so why not.</p> <p>I have some very specific needs, so this is what I&#39;m doing:</p> <p>The PC on the left is my physics simulation machine. Not part of the setup. </p> <p>The one in the middle is my old PC. It now has Windows 1

## Recommendation for hardware and software for homelab replacement/extension
 - [https://www.reddit.com/r/selfhosted/comments/1gqb808/recommendation_for_hardware_and_software_for](https://www.reddit.com/r/selfhosted/comments/1gqb808/recommendation_for_hardware_and_software_for)
 - RSS feed: $source
 - date published: 2024-11-13T11:56:45+00:00

<!-- SC_OFF --><div class="md"><p>Currently, I am starting to get more into self hosting staff to learn something and automate/replace some on cloud solutions. For now I have Raspberry pi 5 and optionally old PC (spec and info at the end).</p> <p>What I want to use it for:</p> <ul> <li>NAS</li> <li>repository (both Perforce and git)</li> <li>home assist</li> <li>Uptime Kuma</li> <li>Proxmox</li> <li>Plex or alternatives</li> <li>Storage for Unreal Engine Assets</li> <li>Managing knowledge/notes/wiki/documentation - still looking for alternatives to Notion</li> <li>Sharing outside my network (like demo of my game or sth)</li> <li>&lt;optional for now&gt; hosting game servers like valheim</li> <li>Automation (but this will be done via homeassist)</li> <li>Managing materials for video tutorials (storage only - I have PC to do montage etc.)</li> <li>Preload like a steam as far I remember - I have a PC which I don&#39;t want to leave it for a night but with current network speed (not opti

## Seeking Self-Hosted AI Image Manipulation Solutions
 - [https://www.reddit.com/r/selfhosted/comments/1gqb2f3/seeking_selfhosted_ai_image_manipulation_solutions](https://www.reddit.com/r/selfhosted/comments/1gqb2f3/seeking_selfhosted_ai_image_manipulation_solutions)
 - RSS feed: $source
 - date published: 2024-11-13T11:46:45+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a self-hosted solution that utilizes my server’s GPU for AI image manipulation tasks, specifically watermark removal, upscaling, and outpainting. I would prefer a simple, user-friendly option that can serve as an API for my use case (send an image and receive the processed result). A UI is also acceptable if it’s easy to use.</p> <p>So far, I’ve come across Invoke AI, Forge UI, and Stable Diffusion UI, but they seem quite complicated and require extensive configuration. If anyone knows of straightforward Docker containers or any easy-to-install options for these AI image tasks, I would greatly appreciate any recommendations.</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Turbcool"> /u/Turbcool </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqb2f3/seeking_selfhosted_ai_image_manipulation_solutions/">[link]</a></span> &#32; <span><a href="http

## Rocky Linux9, moving file from VM home drive to datadrive on attached data disk - azure VM
 - [https://www.reddit.com/r/selfhosted/comments/1gqan39/rocky_linux9_moving_file_from_vm_home_drive_to](https://www.reddit.com/r/selfhosted/comments/1gqan39/rocky_linux9_moving_file_from_vm_home_drive_to)
 - RSS feed: $source
 - date published: 2024-11-13T11:19:01+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, </p> <p>I have got a VM which I have attached a disk and mounted the disk, verified it,</p> <p>following <a href="https://learn.microsoft.com/en-us/azure/virtual-machines/linux/attach-disk-portal">https://learn.microsoft.com/en-us/azure/virtual-machines/linux/attach-disk-portal</a> </p> <p>all seems good till I run below code to move my files from VM home directory to datadrive. it says &quot; cant access - mnt/datadrive:no such file or directory ...</p> <p>not sure what I am doing wrong, </p> <p>any help/ advice appreciated</p> <p>thanks </p> <pre><code>mv /home/mysuer/* /mnt/datadrive </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/InternationalPea3378"> /u/InternationalPea3378 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqan39/rocky_linux9_moving_file_from_vm_home_drive_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqan3

## Trackly - An open-source discord notifier for new music releases from your local library of music artists. | 1.0.0 Release
 - [https://www.reddit.com/r/selfhosted/comments/1gqa9pb/trackly_an_opensource_discord_notifier_for_new](https://www.reddit.com/r/selfhosted/comments/1gqa9pb/trackly_an_opensource_discord_notifier_for_new)
 - RSS feed: $source
 - date published: 2024-11-13T10:53:58+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/obolikus"> /u/obolikus </a> <br/> <span><a href="https://github.com/7eventy7/trackly">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gqa9pb/trackly_an_opensource_discord_notifier_for_new/">[comments]</a></span>

## Self Hosted Threat Hunting: Build Your Own Security Lab with Security Onion
 - [https://www.reddit.com/r/selfhosted/comments/1gq9pac/self_hosted_threat_hunting_build_your_own](https://www.reddit.com/r/selfhosted/comments/1gq9pac/self_hosted_threat_hunting_build_your_own)
 - RSS feed: $source
 - date published: 2024-11-13T10:12:26+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gq9pac/self_hosted_threat_hunting_build_your_own/"> <img src="https://external-preview.redd.it/iXRpXum7NcOIrFCIQ0tSP0cv8f3ZlNJYL9ep3_WrEYc.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=3f805869f7dbf8deedcf775196f82612c1ede774" alt="Self Hosted Threat Hunting: Build Your Own Security Lab with Security Onion" title="Self Hosted Threat Hunting: Build Your Own Security Lab with Security Onion" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lawrencesystems"> /u/lawrencesystems </a> <br/> <span><a href="https://youtu.be/k22Pt19OTdo">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gq9pac/self_hosted_threat_hunting_build_your_own/">[comments]</a></span> </td></tr></table>

## Looking for reverse proxy help
 - [https://www.reddit.com/r/selfhosted/comments/1gq9a8i/looking_for_reverse_proxy_help](https://www.reddit.com/r/selfhosted/comments/1gq9a8i/looking_for_reverse_proxy_help)
 - RSS feed: $source
 - date published: 2024-11-13T09:41:42+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I have an average gaming PC I want to make it my self hosted server. I primarily want the following containers running 24/7:</p> <p>n8n Ollama (wish to expose the endpoint on the internet) Open webui Next cloud Bitwarden Kasm workspaces</p> <p>My internet is a pppoe connection with and ID password and on reading about the ISP, it appeared that they don’t simply allow port forwarding so I’ve purchased a Pinggy.io subscription for 1 port tunnelling. </p> <p>I want to make full use of this tunnel using nginx reverse proxy and host the above services either in subdomains or in the path (path preferred)</p> <p>Whenever I try setting up with paths, it does not work easily (for e.g. n8n was on the home and open web was on /chat, however /chat keeps triggering n8n) and I am quite noob with docker compose. I have also tried asking Claude but i think I am unable to identify what’s the problem. </p> <p>Any suggestions on how can I make full use of that o

## Genesis of cybersecurity
 - [https://www.reddit.com/r/selfhosted/comments/1gq8sg4/genesis_of_cybersecurity](https://www.reddit.com/r/selfhosted/comments/1gq8sg4/genesis_of_cybersecurity)
 - RSS feed: $source
 - date published: 2024-11-13T09:03:16+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gq8sg4/genesis_of_cybersecurity/"> <img src="https://preview.redd.it/h4clu5h3wm0e1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=11be3fc63e1878e97420bc55dec23d97a3eaf33c" alt="Genesis of cybersecurity" title="Genesis of cybersecurity" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/reddit_lanre"> /u/reddit_lanre </a> <br/> <span><a href="https://i.redd.it/h4clu5h3wm0e1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gq8sg4/genesis_of_cybersecurity/">[comments]</a></span> </td></tr></table>

## Free Unix Shell Accounts :)
 - [https://www.reddit.com/r/selfhosted/comments/1gq8o22/free_unix_shell_accounts](https://www.reddit.com/r/selfhosted/comments/1gq8o22/free_unix_shell_accounts)
 - RSS feed: $source
 - date published: 2024-11-13T08:53:35+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I recently launched a Free Shell Service where beginners can get acquainted with the Linux command line and learn the basics, while experienced users can take advantage of all the features the shell offers, such as IRC, IM, chat clients, compilers, script interpreters, web hosting, etc. This is a personal project of mine, focused on installing and configuring Linux and other OSes, with plans to add BSD/Solaris later. I invite everyone interested to register and join — everyone is welcome without exception. Please don&#39;t judge harshly for this post; it&#39;s not an advertisement, and no profit is being made. <a href="https://efn.lt">Here</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/e1z0"> /u/e1z0 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gq8o22/free_unix_shell_accounts/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gq8o22/free_

## Self Hosted Media Catalogue?
 - [https://www.reddit.com/r/selfhosted/comments/1gq8lef/self_hosted_media_catalogue](https://www.reddit.com/r/selfhosted/comments/1gq8lef/self_hosted_media_catalogue)
 - RSS feed: $source
 - date published: 2024-11-13T08:47:30+00:00

<!-- SC_OFF --><div class="md"><p>Is there an all in one, self hosted, database for media such as books, CDs, Games and DVDs / Blurays?</p> <p>To often, I walk in to a game shop and buy retro games, only to already have them in my collection. Its the same with books, I collect manga and I can never remember what volume I am up to, so when I am at book stores, I tend to spend ages trying to remember. </p> <p>I know there are apps but, A: where is the fun in that, B: they all seem to be separate services that need accounts. I just want to be able to switch on my VPN, load up a web page or app and quickly check. No faff</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/conrat4567"> /u/conrat4567 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gq8lef/self_hosted_media_catalogue/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gq8lef/self_hosted_media_catalogue/">[comments]</a></span>

## Ending up with more compute and RAM than I need?
 - [https://www.reddit.com/r/selfhosted/comments/1gq8d56/ending_up_with_more_compute_and_ram_than_i_need](https://www.reddit.com/r/selfhosted/comments/1gq8d56/ending_up_with_more_compute_and_ram_than_i_need)
 - RSS feed: $source
 - date published: 2024-11-13T08:28:52+00:00

<!-- SC_OFF --><div class="md"><p>I bought my first mini computer (2 1TB ssds &amp; 64gb RAM) and turned it into a VM host with proxmox and am running public webservers, data scrapers, database and home media stuff like Jellyfin / NextCloud / Immich etc.</p> <p>I&#39;m quickly running out of hard disk space and deleting movies to make room for databases that keep growing. I have access to two more mini PCs, one of which is pretty beefy with new top of the line graphics cards etc.</p> <p>But I&#39;m realizing now, I barely use all of my first one&#39;s CPU/RAM and while I could use some more, not really. What I definitely will need is a NAS or more storage.</p> <p>Is this a common issue to hit? I guess my options are:</p> <p>1) Upgrade existing mini PC 2x 1TB SSD -&gt; 2x 2TB SSD ~$200<br/> 2) Hookup another mini PC with 2x 2TB SSD ~$200, but this is maybe a lot more extra energy/noise etc.<br/> 3) Buy a NAS ~$500-$1k ? </p> <p>Any opinions on these options? Somehow I didn&#39;t forse

## docker container networking
 - [https://www.reddit.com/r/selfhosted/comments/1gq8cyh/docker_container_networking](https://www.reddit.com/r/selfhosted/comments/1gq8cyh/docker_container_networking)
 - RSS feed: $source
 - date published: 2024-11-13T08:28:28+00:00

<!-- SC_OFF --><div class="md"><p>i recently started to manage my docker as previously i just used ips and port for usecase. but now i hopped on to the nginx proxy manager as a noobie. but i am now struggling to setup. i initially used docker as my host network but still it is a mess as i use CF as my ssl and dns provider and so requires me a interent connection. so i gaved chance to pihole but got to know to use local dns i need it to be my dhcp server so now moving my docker network to maclan and then to pihole dhcp. but still its a mess as ssl doesnt work for many of the sites ( i still have CF as ssl via lets encrypt and just points the wildcard of CF to the individual ip via pihole ). </p> <p>so now i am questioning is there a way i can have ssl + domain ( possibly local domain so i dont need to rely on internet ) + web ui ( i am not a cli geek so prefer web ui ). to get a good optimize navigation. </p> <p>( also some info which may be useless i use CF tunnel for external exposu

## How do I access my home network devices via Zerotier with a domain name?
 - [https://www.reddit.com/r/selfhosted/comments/1gq79gs/how_do_i_access_my_home_network_devices_via](https://www.reddit.com/r/selfhosted/comments/1gq79gs/how_do_i_access_my_home_network_devices_via)
 - RSS feed: $source
 - date published: 2024-11-13T07:06:17+00:00

<!-- SC_OFF --><div class="md"><p>I have a NAS at home plus couple more devices, all connected to Zerotier. For a while now I&#39;ve just been using cloudflare to point the dns to these zerotier IPs directly with a DNS A record (eg NAS.mydomain.com &gt; 192.168.198.x) so I can connect without remembering the IP. </p> <p>This has been working fine but have just realised that not all DNS servers are able to resolve these host names. I&#39;m on holiday currently and any subdomain that&#39;s pointed to a zerotier IP doesn&#39;t resolve when I&#39;m using public WiFi or the apartment WiFi. </p> <p>I can connect directly if I use the IP, so I know the zerotier network is connected and working, but I just can&#39;t access them via my subdomains. </p> <p>What options should I research to make this simple thing work? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/shikabane"> /u/shikabane </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/com

## What do you do with your VPS?
 - [https://www.reddit.com/r/selfhosted/comments/1gq7314/what_do_you_do_with_your_vps](https://www.reddit.com/r/selfhosted/comments/1gq7314/what_do_you_do_with_your_vps)
 - RSS feed: $source
 - date published: 2024-11-13T06:53:45+00:00

<!-- SC_OFF --><div class="md"><p>Hey all! I&#39;m curious—what do you guys use your VPS for?</p> <p>I’ve been experimenting with mine for a while, and it’s turned into a bit of a playground for different projects. Here are a few things I&#39;ve done:</p> <ul> <li><strong>Hosting Personal Websites and Blogs</strong> - I’ve set up a couple of lightweight sites with Nginx and WordPress. It’s a great way to practice managing my own stack and playing with new themes and plugins.</li> <li><strong>VPN and Proxy Server</strong> - I set up a VPN to secure my connection when I&#39;m on public Wi-Fi. It’s super convenient, and I feel safer using my own VPN vs. public ones.</li> <li><strong>Game Servers</strong> - Tried running a Minecraft server on it for friends, which was a blast. It’s great if you want to have some control over plugins and mods without relying on public servers.</li> <li><strong>Data Backup and Sync</strong> - I use my VPS as a backup location with rsync. Works like a charm

## Open-source tool for cloud security - free and self-hosted
 - [https://www.reddit.com/r/selfhosted/comments/1gq6kus/opensource_tool_for_cloud_security_free_and](https://www.reddit.com/r/selfhosted/comments/1gq6kus/opensource_tool_for_cloud_security_free_and)
 - RSS feed: $source
 - date published: 2024-11-13T06:18:51+00:00

<!-- SC_OFF --><div class="md"><p>Hey folks! I built Guard, a free, open-source tool designed for cloud security that’s fully self-hosted. It scans your AWS cloud environment for misconfigurations in services like IAM, EC2, S3, etc., and offers LLM-based remedies for any issues it finds.</p> <p>If you&#39;re handling cloud security and want something self-hosted, feel free to check it out and let me know if it’s helpful!</p> <p>Demo video: <a href="https://x.com/ShehbajDhillon/status/1854649730250440773">Here’s a quick walkthrough</a><br/> GitHub repo: <a href="https://github.com/guard-dev/guard">https://github.com/guard-dev/guard</a><br/> Website: <a href="https://guard.dev">guard.dev</a></p> <p>Would love to hear any feedback, ideas, or feature requests!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ShehbajDhillon"> /u/ShehbajDhillon </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gq6kus/opensource_tool_for_cloud_secu

## Homer Dashboard - Ping function partially working on Firefox not Edge
 - [https://www.reddit.com/r/selfhosted/comments/1gq5m03/homer_dashboard_ping_function_partially_working](https://www.reddit.com/r/selfhosted/comments/1gq5m03/homer_dashboard_ping_function_partially_working)
 - RSS feed: $source
 - date published: 2024-11-13T05:17:21+00:00

<!-- SC_OFF --><div class="md"><p>I’m having trouble with the ping functionality with the Homer dashboard and was hoping someone here could help me understand what’s going on a little better.</p> <p>My Setup: I’m running a local only ubuntu server using docker containers for my services. All services are using bridge networks with some containers having their own network bridge and others sharing a network. I am not running a reverse proxy.</p> <p>I’ve just activated the Ping service on the Homer dashboard for each service and I’m getting some very confusing results.</p> <p>Ping is setup with the default HEAD method. Using Microsoft Edge all my services are showing as offline, checking for errors it is the standard CORS related issue. That makes sense, however, when I use Firefox some of the services show as online and I don’t see any CORS errors. Perhaps that’s just because I’m not looking in the right place with Firefox’s web console window though. But why would some of the service

## archivebox and Pocket
 - [https://www.reddit.com/r/selfhosted/comments/1gq4qxq/archivebox_and_pocket](https://www.reddit.com/r/selfhosted/comments/1gq4qxq/archivebox_and_pocket)
 - RSS feed: $source
 - date published: 2024-11-13T04:26:36+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to find some documentation or help getting my archivebox (running in docker) to pull saved pages from Pocket. Can someone please point me in the right direction?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Vorpel-Bunny"> /u/Vorpel-Bunny </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gq4qxq/archivebox_and_pocket/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gq4qxq/archivebox_and_pocket/">[comments]</a></span>

## News Aggregator - Filter Keywords
 - [https://www.reddit.com/r/selfhosted/comments/1gq42or/news_aggregator_filter_keywords](https://www.reddit.com/r/selfhosted/comments/1gq42or/news_aggregator_filter_keywords)
 - RSS feed: $source
 - date published: 2024-11-13T03:48:40+00:00

<!-- SC_OFF --><div class="md"><p>Been searching for a while and haven&#39;t quite been able to pin anything down. As the title says, looking for a News Aggregator where I can filter keywords. Some things I just don&#39;t want to see (eg. Kardashian). Any suggestions would be most appreciated! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/EskelGorov"> /u/EskelGorov </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gq42or/news_aggregator_filter_keywords/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gq42or/news_aggregator_filter_keywords/">[comments]</a></span>

## Crowdsec with Cloudflare Proxy
 - [https://www.reddit.com/r/selfhosted/comments/1gq4285/crowdsec_with_cloudflare_proxy](https://www.reddit.com/r/selfhosted/comments/1gq4285/crowdsec_with_cloudflare_proxy)
 - RSS feed: $source
 - date published: 2024-11-13T03:47:59+00:00

<!-- SC_OFF --><div class="md"><p>I have implemented crowdsec, with some specific collections like vaultwarden, ssh and nginx, and a firewall bouncer. It works(worked) fine. I recently moved my DNS to cloudflare, and started using their proxy functionality. Does it make sense to still have crowdsec enabled? My guess is that any decisions (such as blocking an IP due to wrong credentials in vaultwarden) will simply block one of cloudflares IPs, right? Should I disable the specific collections and just leave the default crowdsec ones then? Completely disable it? Leave it? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/YankeeLimaVictor"> /u/YankeeLimaVictor </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gq4285/crowdsec_with_cloudflare_proxy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gq4285/crowdsec_with_cloudflare_proxy/">[comments]</a></span>

## From four to five 9s of uptime by migrating from Heroku to a custom EKS setup
 - [https://www.reddit.com/r/selfhosted/comments/1gq3u6n/from_four_to_five_9s_of_uptime_by_migrating_from](https://www.reddit.com/r/selfhosted/comments/1gq3u6n/from_four_to_five_9s_of_uptime_by_migrating_from)
 - RSS feed: $source
 - date published: 2024-11-13T03:35:42+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gq3u6n/from_four_to_five_9s_of_uptime_by_migrating_from/"> <img src="https://external-preview.redd.it/No98F54KrB-zXNPPjSQZ4FKXhKyNPWcWN28Jw_Vp2-s.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=b925dfb41a43a6b7d6a670e9d5edf4680ad57df0" alt="From four to five 9s of uptime by migrating from Heroku to a custom EKS setup" title="From four to five 9s of uptime by migrating from Heroku to a custom EKS setup" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Smooth-Loquat-4954"> /u/Smooth-Loquat-4954 </a> <br/> <span><a href="https://workos.com/blog/from-four-to-five-9s-of-uptime-by-migrating-to-kubernetes">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gq3u6n/from_four_to_five_9s_of_uptime_by_migrating_from/">[comments]</a></span> </td></tr></table>

## Cloudflare tunnel alternative? Want to use the right tools for the job.
 - [https://www.reddit.com/r/selfhosted/comments/1gq3pdr/cloudflare_tunnel_alternative_want_to_use_the](https://www.reddit.com/r/selfhosted/comments/1gq3pdr/cloudflare_tunnel_alternative_want_to_use_the)
 - RSS feed: $source
 - date published: 2024-11-13T03:28:41+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gq3pdr/cloudflare_tunnel_alternative_want_to_use_the/"> <img src="https://preview.redd.it/c7wxkp8k8l0e1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=ef1b693b02223d8befa53955d940fc8f0b25c685" alt="Cloudflare tunnel alternative? Want to use the right tools for the job." title="Cloudflare tunnel alternative? Want to use the right tools for the job." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AmbienJoe"> /u/AmbienJoe </a> <br/> <span><a href="https://i.redd.it/c7wxkp8k8l0e1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gq3pdr/cloudflare_tunnel_alternative_want_to_use_the/">[comments]</a></span> </td></tr></table>

## Debian vs FreeBSD vs OpenBSD for servers
 - [https://www.reddit.com/r/selfhosted/comments/1gq3ikr/debian_vs_freebsd_vs_openbsd_for_servers](https://www.reddit.com/r/selfhosted/comments/1gq3ikr/debian_vs_freebsd_vs_openbsd_for_servers)
 - RSS feed: $source
 - date published: 2024-11-13T03:18:37+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I use Debian for both desktop and server use. The distro was chosen specifically because I value stability over new features, as I prefer spending little time and effort on maintenance beyond running updates once a week. I have a VPS hosting small websites and internet-facing applications for personal use, and a Pi for torrenting. Recently, I became interested in switching from Debian to FreeBSD or OpenBSD for my servers, because I read that they adhere more to the Unix philosophy, thus apparently simpler and more consistent than Linux distros. I also read the file system they use (ZFS) is somehow better. Beyond those, I&#39;m not sure of any meaningful advantages of switching for my use case. I&#39;m also torn between FreeBSD (probably has more support/features) and OpenBSD (probably has better security). What do you guys think? Sorry if it&#39;s a loaded question; I&#39;m just a self-hosting amateur 🙏.</p> </div><!-- SC_ON --> &#32; submitted b

## Nginx timing out requests to local Synapse server
 - [https://www.reddit.com/r/selfhosted/comments/1gq2x7p/nginx_timing_out_requests_to_local_synapse_server](https://www.reddit.com/r/selfhosted/comments/1gq2x7p/nginx_timing_out_requests_to_local_synapse_server)
 - RSS feed: $source
 - date published: 2024-11-13T02:48:23+00:00

<!-- SC_OFF --><div class="md"><p>I set up a Synapse server, and put it behind a Nginx reverse proxy, which in turn is behind Cloudflare(not sure if this is relevant) The configurations are as follows:<br/> homeserver.yaml:</p> <p><code>pid_file: &quot;/var/run/matrix-synapse.pid&quot;</code></p> <p><code>listeners:</code></p> <p><code>- port: 8008</code></p> <p><code>tls: false</code></p> <p><code>type: http</code></p> <p><code>x_forwarded: true</code></p> <p><code>bind_addresses: [&#39;::&#39;, &#39;0.0.0.0&#39;]</code></p> <p><code>resources:</code></p> <p><code>- names: [client, federation]</code></p> <p><code>compress: false</code></p> <p><code>database:</code></p> <p><code>name: psycopg2</code></p> <p><code>args:</code></p> <p><code>user: synapse_user</code></p> <p><code>password: password_here</code></p> <p><code>database: synapse</code></p> <p><code>host: localhost</code></p> <p><code>cp_min: 5</code></p> <p><code>cp_max: 10</code></p> <p><code>log_config: &quot;/etc/matrix-s

## How to cost-efficiently receive 1 million emails a day.
 - [https://www.reddit.com/r/selfhosted/comments/1gq2isi/how_to_costefficiently_receive_1_million_emails_a](https://www.reddit.com/r/selfhosted/comments/1gq2isi/how_to_costefficiently_receive_1_million_emails_a)
 - RSS feed: $source
 - date published: 2024-11-13T02:27:56+00:00

<!-- SC_OFF --><div class="md"><p>As the title says I need to receive ~1 million (and maybe more in the future) emails a day. I then will need to trigger scripts to process these emails. (I can&#39;t read that fast). I am presently using SES for this, but that has turned out to be quite pricy ($100 a day). It seems like I can host my own email server, and most of the pitfalls of doing that are related to <strong>sending</strong> emails, which I don&#39;t need to do.</p> <p>I have done some reading and it seems like there are many email servers (developed in various decades) which offer a variety of features, most of which I don&#39;t seem to need. It&#39;s unclear what kinds of volume these applications can handle, and what kind of resources they would need.</p> <p>Any advice or recommendations are welcome. I&#39;m happy to give more details on my requirements if needed.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MidgetDufus"> /u/MidgetDufu

## Best coding AI to host on an "okay" computer ? (RX6650XT, 16GB DDR4, 11400F)
 - [https://www.reddit.com/r/selfhosted/comments/1gq2gzo/best_coding_ai_to_host_on_an_okay_computer](https://www.reddit.com/r/selfhosted/comments/1gq2gzo/best_coding_ai_to_host_on_an_okay_computer)
 - RSS feed: $source
 - date published: 2024-11-13T02:25:19+00:00

<!-- SC_OFF --><div class="md"><p>Hello ! I&#39;m looking for an AI i could use on my PC for coding small projects mostly in Python. Do you guys have any suggestions ? Thank you.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CancerousGTFO"> /u/CancerousGTFO </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gq2gzo/best_coding_ai_to_host_on_an_okay_computer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gq2gzo/best_coding_ai_to_host_on_an_okay_computer/">[comments]</a></span>

## Automated Weather Report for Self-Hosted Radio Station
 - [https://www.reddit.com/r/selfhosted/comments/1gq1c3j/automated_weather_report_for_selfhosted_radio](https://www.reddit.com/r/selfhosted/comments/1gq1c3j/automated_weather_report_for_selfhosted_radio)
 - RSS feed: $source
 - date published: 2024-11-13T01:28:38+00:00

<!-- SC_OFF --><div class="md"><p>I host an internet radio station for my local town on my server using azuracast. In order to have minimal maintenance but stay relevant and useful, I wrote a script that takes the API from <a href="http://weather.com">weather.com</a> and creates a weather report for my local area. Feel free to check it out and let me know what you think!</p> <p>Radio Station (Fair warning. I love christmas, so it&#39;s christmas music in the morning and evening right now):</p> <p><a href="https://mvrc.intellidwell.net">https://mvrc.intellidwell.net</a></p> <p>Weather Report Script:</p> <p><a href="https://github.com/TannerNelson16/radio_weather_report">https://github.com/TannerNelson16/radio_weather_report</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Tanner234567"> /u/Tanner234567 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gq1c3j/automated_weather_report_for_selfhosted_radio/">[link]</a></span

## Is there a self hosted DNS server (but the part that answer DNS requests)
 - [https://www.reddit.com/r/selfhosted/comments/1gq0ylt/is_there_a_self_hosted_dns_server_but_the_part](https://www.reddit.com/r/selfhosted/comments/1gq0ylt/is_there_a_self_hosted_dns_server_but_the_part)
 - RSS feed: $source
 - date published: 2024-11-13T01:10:04+00:00

<!-- SC_OFF --><div class="md"><p>Hi there,</p> <p>I&#39;m not sure if the title is explicit enough..<br/> <em>(Edit: Sorry English is not my native language and I just noticed - and now cannot modify - that the &#39;but&#39; might mean &#39;except&#39;, while actually I wanted to say &#39;only&#39;)</em></p> <p>So there&#39;s the DNS server whose job is to resolve domain names (like a router, the ISP, Google 8.8.8.8, Cloudflare 1.1.1.1, pihole, etc.) And there&#39;s the part that actually answer (the registrar DNS server, or e.g. Cloudflare like lloyd.ns.cloudflare.com), right? This is that second one I mean in the title. (BTW, is there a more specific name describing that part?)</p> <p>Often, when I register a domain name I&#39;m immediately editing the DNS field to point to the one from Cloudflare, then in the Cloudflare UI I can edit my domains DNS records as I want (usually way more fast than the registrar ones).</p> <p>So is there some kind of self hosted server I can use and w

## NginxProxyManager + Cloudflare + LAN Access
 - [https://www.reddit.com/r/selfhosted/comments/1gpzo9t/nginxproxymanager_cloudflare_lan_access](https://www.reddit.com/r/selfhosted/comments/1gpzo9t/nginxproxymanager_cloudflare_lan_access)
 - RSS feed: $source
 - date published: 2024-11-13T00:09:53+00:00

<!-- SC_OFF --><div class="md"><p>So i&#39;ve been scratching my head with this issue for a few months.. I cant seem to figure out whats going on. </p> <p>So I have NginxProxyManager working fine, and I use Cloudflare with it. All my apps seem to work fine externally and internally to my network (ie. sonarr.mydomain.com connects fine externally and internally). </p> <p>I tried setting up Plex and Immich, but had to disable the Cloudflare proxy (Plex will violate the ToS and Immich buffers a ton due to a 100mb limitation). As soon as I disable the proxy I cant access my domains from within my network for whatever reason...</p> <p>I have opnsense (unbound DNS) and adguard running. I tried to use a DNS rewrite in adguard and the host/domain override in unbound but both did not work... I moved my NPM to a new ip address (since ports cant be specified for DNS) and set it to port 80/443 hoping thats all that was required.. but i still cant seem to get it to work.</p> <p>What am I missing? 

