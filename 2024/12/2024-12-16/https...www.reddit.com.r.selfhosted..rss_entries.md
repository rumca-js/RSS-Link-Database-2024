# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## [Open-Source] SSH Browser !
 - [https://www.reddit.com/r/selfhosted/comments/1hfx7zn/opensource_ssh_browser](https://www.reddit.com/r/selfhosted/comments/1hfx7zn/opensource_ssh_browser)
 - RSS feed: $source
 - date published: 2024-12-16T23:47:03+00:00

<!-- SC_OFF --><div class="md"><p>Hey!</p> <p>I&#39;ve developed a cross-platform <a href="https://github.com/0xb-s/ssh-browser">SSH desktop application</a> that simplifies connecting to SSH servers without relying on the command line.</p> <p>I&#39;d love to hear your feedback and suggestions for future improvements!<br/> Contributions are always welcome.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok_Inevitable_3392"> /u/Ok_Inevitable_3392 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfx7zn/opensource_ssh_browser/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfx7zn/opensource_ssh_browser/">[comments]</a></span>

## Proxmox VE - no subscription popup nag removal, scripted
 - [https://www.reddit.com/r/selfhosted/comments/1hfwia8/proxmox_ve_no_subscription_popup_nag_removal](https://www.reddit.com/r/selfhosted/comments/1hfwia8/proxmox_ve_no_subscription_popup_nag_removal)
 - RSS feed: $source
 - date published: 2024-12-16T23:13:34+00:00

<!-- SC_OFF --><div class="md"><blockquote> <p>X-posted from <a href="/r/ProxmoxQA">r/ProxmoxQA</a> Originally published at: <a href="https://free-pmx.github.io/">https://free-pmx.github.io/</a></p> </blockquote> <hr/> <p>This is a follow-up on the method of manual removal of the no-subscription popup, since the component is being repeatedly rebuilt due to active GUI development.</p> <p>The script is simplistic, makes use of <em>Perl</em> (which is part of PVE stack) and follows the exact same steps for the predictable and safe outcome as the manual method did. Unlike other scripts available, it <em>does NOT risk partial matches of other (unintended) parts of code in the future</em> and their inadvertent removal, it also contains the exact copy of the <em>JavaScript</em> to be seen in context.</p> <h2>Script</h2> <pre><code>#!/usr/bin/perl -pi.bak use strict; use warnings; # original my $o = quotemeta &lt;&lt; &#39;EOF&#39;; checked_command: function(orig_cmd) { Proxmox.Utils.API2Req

## Optimizing My Setup on a K3s Cluster with Ceph Storage
 - [https://www.reddit.com/r/selfhosted/comments/1hfvu4k/optimizing_my_setup_on_a_k3s_cluster_with_ceph](https://www.reddit.com/r/selfhosted/comments/1hfvu4k/optimizing_my_setup_on_a_k3s_cluster_with_ceph)
 - RSS feed: $source
 - date published: 2024-12-16T22:43:39+00:00

<!-- SC_OFF --><div class="md"><p><strong>Context:</strong> I currently have a K3s cluster deployed across two main nodes with a third node acting solely as a HA node. The two main nodes each have NVMe drives and also serve as the primary storage nodes. The third node is purely for high availability and does not handle workloads. The nodes are connected over a different internet network using Tailscale.</p> <p>My goal is to run a few lightweight services like Nextcloud, Vaultwarden, and some other small apps for personal use. This setup is used by a small group of people (3-4 users).</p> <p><strong>Problem:</strong> To manage storage, I have deployed Rook Ceph on this cluster, and while the read speeds are excellent (~14.6 Gb/s), the write speeds are significantly slower, averaging about 100 MB/s. Here are some relevant details:</p> <ol> <li>Network: <ul> <li>Nodes are connected via Tailscale over a 1 Gbps internet connection.</li> <li>Latency between nodes is around 13-14ms.</li> </

## How to Use Nginx to Allow Public Access to an Embedded Grafana Panel While Blocking the Rest
 - [https://www.reddit.com/r/selfhosted/comments/1hfvsbr/how_to_use_nginx_to_allow_public_access_to_an](https://www.reddit.com/r/selfhosted/comments/1hfvsbr/how_to_use_nginx_to_allow_public_access_to_an)
 - RSS feed: $source
 - date published: 2024-12-16T22:41:25+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’m running Grafana on my server, and I want to embed a specific panel from Grafana on a public-facing website. However, I want to block access to the rest of my Grafana instance, ensuring only that one embedded panel is accessible from the public internet.</p> <p>I&#39;m using Nginx as a reverse proxy. I’ve tried a few configurations but haven’t found a secure solution yet.</p> <p>What I’m looking for:</p> <p>How to configure Nginx to allow access to a specific Grafana panel URL while blocking all other Grafana routes.</p> <p>Best practices for securing the Grafana instance while keeping the embedded panel public.</p> <p>Any advice or example Nginx configurations would be greatly appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tech_Dauwt"> /u/tech_Dauwt </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfvsbr/how_to_use_nginx_to_allow_public_access_to_an/">

## USFF NAS/Homelab
 - [https://www.reddit.com/r/selfhosted/comments/1hfvq30/usff_nashomelab](https://www.reddit.com/r/selfhosted/comments/1hfvq30/usff_nashomelab)
 - RSS feed: $source
 - date published: 2024-12-16T22:38:37+00:00

<!-- SC_OFF --><div class="md"><p>I’ve recently picked up a used USFF PC on eBay with the intention of using it as a petit home server and NAS. It’s a HP ProDesk 600 G4 i5 8500T. </p> <p>I’m aware it’s probably not the best core for a NAS but I’m keen to make it work, with the main ambition being to use as little power as possible and to save some money. It will primarily serve as a CCTV NVR and NAS for audio project file storage.</p> <p>I’m hoping to get some advice on the best option for connecting storage to the USFF. I’d like around 16Tb of storage so an array of 3.5” HDDs was my plan. I’d love to rack mount the whole thing at some stage too. </p> <p>The USFF has a few IO options, a couple of M2 slots, USB 3.2 and a HP flexio port which could be populated with 2.5GbE or even Thunderbolt3 if I can find the card online. I was going to use the onboard sata SSD as a boot drive. </p> <p>The options I am considering:</p> <p>1 - M2 to 5x SATA controller - connected to an array of HDDs i

## Home lab issue
 - [https://www.reddit.com/r/selfhosted/comments/1hfvkpj/home_lab_issue](https://www.reddit.com/r/selfhosted/comments/1hfvkpj/home_lab_issue)
 - RSS feed: $source
 - date published: 2024-12-16T22:32:09+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, I have an issue with my setup of my home lab.</p> <p>I have ubuntu server and docker In docker i have ngnix proxy server and pihole Pihole is working fine Ngnix do not resolve services that are in the home network on a windows pc.</p> <p>Maybe i configured something wrong?</p> <p>If is more complex I will extend and edit the post.</p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dc_stuff"> /u/dc_stuff </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfvkpj/home_lab_issue/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfvkpj/home_lab_issue/">[comments]</a></span>

## Best practice to have a stable IPv6 in Ubuntu VM?
 - [https://www.reddit.com/r/selfhosted/comments/1hfvf2s/best_practice_to_have_a_stable_ipv6_in_ubuntu_vm](https://www.reddit.com/r/selfhosted/comments/1hfvf2s/best_practice_to_have_a_stable_ipv6_in_ubuntu_vm)
 - RSS feed: $source
 - date published: 2024-12-16T22:25:10+00:00

<!-- SC_OFF --><div class="md"><p>Pushing along my hosting on IPv6 Journey and found myself at bit of cross road, so putting it out there hoping to hear what community thinks</p> <p>I found the following ways to have stable IPv6 via netplan in ubtuntu</p> <ol> <li><strong>EUI64</strong></li> </ol> <p>Set <code>accept-ra: true</code> to use EUI-64 to generate stable IPv6 from MAC</p> <p>I also found <code>ipv6-address-generation: stable</code> and <code>ipv6-address-generation: eui64</code> which might help encoforcwe eui64 but they seem to be for different versions of networkd or netplan, this nitty gritty is beyond my current knowledge.</p> <p>But EUI64 essentially exposes the MAC address, although its a randomized one for VM</p> <p>I&#39;m not sure if there&#39;s any security concerns with exposing MAC</p> <ol> <li> <code>addresses:[]</code> property</li> </ol> <p>Allows manually assigning whatever addresses within the prefix,</p> <p>But this goes again the 1st principle as mention

## webserver security upgrades
 - [https://www.reddit.com/r/selfhosted/comments/1hfuybp/webserver_security_upgrades](https://www.reddit.com/r/selfhosted/comments/1hfuybp/webserver_security_upgrades)
 - RSS feed: $source
 - date published: 2024-12-16T22:04:53+00:00

<!-- SC_OFF --><div class="md"><p>Hello,<br/> I have a dell optiplex 7000 running as my webserver. Ports 80 and 443 are exposed on the fritzbox. And is use docker containers to run nginx, mariadband certbot. I also installed ufw and only allowed ports 80,443 and 22. I also got fail2ban for DDOS and bruteforce attacks on my host machine. To connect to the server via an other network i use wireguard VPN. How can i make the server more secure?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Motor-Cover-1760"> /u/Motor-Cover-1760 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfuybp/webserver_security_upgrades/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfuybp/webserver_security_upgrades/">[comments]</a></span>

## Need help with fusionpbx inbound caller id lookup
 - [https://www.reddit.com/r/selfhosted/comments/1hfuv7b/need_help_with_fusionpbx_inbound_caller_id_lookup](https://www.reddit.com/r/selfhosted/comments/1hfuv7b/need_help_with_fusionpbx_inbound_caller_id_lookup)
 - RSS feed: $source
 - date published: 2024-12-16T22:01:14+00:00

<!-- SC_OFF --><div class="md"><p>Hello,<br/> I&#39;m new to voip, and I tried implementing caller id lookup in contacts following this tutorial:<br/> <a href="https://www.pbxforums.com/threads/caller-id-lookup-cidlookup-from-contacts.20/">https://www.pbxforums.com/threads/caller-id-lookup-cidlookup-from-contacts.20/</a><br/> first problem I came across was</p> <blockquote> <p>Now navigate to Advanced &gt; XML Editor &gt; autoload_configs &gt; cidlookup.conf.xml and modify existing lines with these:</p> </blockquote> <p>This option seems to be no longer available. So i used</p> <p><code>find / -name cidlookup.conf.xml</code></p> <p>to find right file. It resulted in these files:</p> <p><code>/var/www/fusionpbx/app/switch/resources/conf/autoload_configs/cidlookup.conf.xml</code></p> <p><code>/usr/src/freeswitch-1.10.12/src/mod/applications/mod_cidlookup/conf/autoload_configs/cidlookup.conf.xml</code></p> <p><code>/usr/src/freeswitch-1.10.12/conf/vanilla/autoload_configs/cidlookup.conf

## I want simple self hosted syncthing server and maybe some other use cases.
 - [https://www.reddit.com/r/selfhosted/comments/1hfu0l6/i_want_simple_self_hosted_syncthing_server_and](https://www.reddit.com/r/selfhosted/comments/1hfu0l6/i_want_simple_self_hosted_syncthing_server_and)
 - RSS feed: $source
 - date published: 2024-12-16T21:25:36+00:00

<!-- SC_OFF --><div class="md"><p>So, the idea of having home server is bothering me for quite long... Now I finally made a decision, that I want to do that. But, I have 2 problems : 1. Limited money, around 60$ 2. Limited sources of tech</p> <p>I am from Russia, so no ebay, Amazon etc. People here are charging WAY TOO MUCH money for things like Intel nuc&#39;s or thin clients. Or if price is nice, shipping is too expensive or too long.</p> <p>Mainly I need server for syncthing, maybe little nas. !It has to be small! What can I do? Use SBC? The price of a RPI4 is 40$ on marketplace. Do I need to use it or there are some better alternatives for that price?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/self-o-eater"> /u/self-o-eater </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfu0l6/i_want_simple_self_hosted_syncthing_server_and/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfu

## How to improve a slow Wireguard connection between cities?
 - [https://www.reddit.com/r/selfhosted/comments/1hftu1r/how_to_improve_a_slow_wireguard_connection](https://www.reddit.com/r/selfhosted/comments/1hftu1r/how_to_improve_a_slow_wireguard_connection)
 - RSS feed: $source
 - date published: 2024-12-16T21:17:51+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m hosting a Wireguard VPN on my local network, and I have Google Fiber as my ISP with a 1 gbps up/down plan. I have family members connecting to it from two different cities, with one about 90 miles away and the other about 150 miles away.</p> <p>From within my city, my connection on the VPN is very fast, usually only a touch slower than the connection not on the VPN. People outside of my city, however, have a <em>much</em> slower connection, sometimes only in the 5-10 mpbs range despite have much faster speeds off the VPN. This persists across a number of speed tests, including a self-hosted Librespeed one. When I visited family, I experienced the same thing on my devices.</p> <p>Does anyone have any ideas about what is going on? Is there anything I can do on my end to improve this? Or is this just luck of the draw that the connection is poor?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Static_Unit"> 

## Need help for a home server! Noobie here
 - [https://www.reddit.com/r/selfhosted/comments/1hftefl/need_help_for_a_home_server_noobie_here](https://www.reddit.com/r/selfhosted/comments/1hftefl/need_help_for_a_home_server_noobie_here)
 - RSS feed: $source
 - date published: 2024-12-16T20:59:45+00:00

<!-- SC_OFF --><div class="md"><p>Good day! </p> <p>I hope everyone is well! I wanted to have a small little mini PC/Server into my network system to start hosting my own Bitcoin node. Run BTC pay server and other stuff like media etc... This will only be for learning purposed I do not want a Raspberry pie because of few reasons:</p> <p>First in Australia it&#39;s expensive a 8GB Pi 5 is about 170 bucks then you need 2Tb and mostly I will actually need 16GB of ram and not 8GB which will make the pie cost me around 400/500 Bucks. </p> <p>So Umbrel does have a little home server for 600 Aud or 382 USD with the spec I think I need?:</p> <p><a href="https://umbrel.com/umbrel-home">https://umbrel.com/umbrel-home</a></p> <p>I saw a post a year ago saying that umbrel was terrible as it was way over priced but seem like in Australia we do not have much choices of a already built mini pc/servers. </p> <p>Would anyone recommend me something better? Thank you :)</p> </div><!-- SC_ON --> &#32; s

## Web proxy search engine like CroxyProxy
 - [https://www.reddit.com/r/selfhosted/comments/1hft7jq/web_proxy_search_engine_like_croxyproxy](https://www.reddit.com/r/selfhosted/comments/1hft7jq/web_proxy_search_engine_like_croxyproxy)
 - RSS feed: $source
 - date published: 2024-12-16T20:51:43+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, I&#39;m looking for a way to host this kind of service myself: <a href="https://www.croxyproxy.com/">https://www.croxyproxy.com/</a> The goal is to have a proxy within a web page to allow me to go to the sites I want without installing anything on the computer I&#39;m using.</p> <p>Thanks in advance</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/flodes80"> /u/flodes80 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hft7jq/web_proxy_search_engine_like_croxyproxy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hft7jq/web_proxy_search_engine_like_croxyproxy/">[comments]</a></span>

## VPS to VM Forwarding via Tailscale, help needed.
 - [https://www.reddit.com/r/selfhosted/comments/1hfs3np/vps_to_vm_forwarding_via_tailscale_help_needed](https://www.reddit.com/r/selfhosted/comments/1hfs3np/vps_to_vm_forwarding_via_tailscale_help_needed)
 - RSS feed: $source
 - date published: 2024-12-16T20:04:19+00:00

<!-- SC_OFF --><div class="md"><p>Hello! I&#39;m fairly inexperienced with networking, but eager to learn.</p> <p>I am hosting several services that I am trying to expose services listening on 0.0.0.0: ports. Unfortunately, I am having issues getting the to respond to external traffic.</p> <p>Here&#39;s my setup.</p> <p>VM (ubuntu, 24.10) running dockerized game servers via AMP. I have connected my VM to a VPS via Tailscale and can ping across the tunnel to local IP and port, so that part seems correct. Running Tshark on both the VPS and VM reveal that while external inbound traffic will hit my VPS, it is not passing through to the VM. I have tried using port streaming via Nginx Proxy Manager to no avail. I have ensured that ipv4 fowarding is uncommented and ufw on both the VM and the VPS have been disabled during testing.</p> <p>I have previously seen suggestion of advertising <a href="http://192.168.1.0/24">192.168.1.0/24</a> of my VM to the tailnet, but when I advertise, accept, a

## Looking for browser based Gimp/Photoshop alternative
 - [https://www.reddit.com/r/selfhosted/comments/1hfs09a/looking_for_browser_based_gimpphotoshop](https://www.reddit.com/r/selfhosted/comments/1hfs09a/looking_for_browser_based_gimpphotoshop)
 - RSS feed: $source
 - date published: 2024-12-16T20:00:34+00:00

<!-- SC_OFF --><div class="md"><p>Are there any good open source alternatives that work solely in the browser you can self host?</p> <p>I am fine with something simpler with less features just for some quick edits here and there.</p> <p>All I could find using search is people scraping Photopea.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MaruluVR"> /u/MaruluVR </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfs09a/looking_for_browser_based_gimpphotoshop/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfs09a/looking_for_browser_based_gimpphotoshop/">[comments]</a></span>

## Homepage - sitemonitor of tailscale network machines return errors
 - [https://www.reddit.com/r/selfhosted/comments/1hfrwhx/homepage_sitemonitor_of_tailscale_network](https://www.reddit.com/r/selfhosted/comments/1hfrwhx/homepage_sitemonitor_of_tailscale_network)
 - RSS feed: $source
 - date published: 2024-12-16T19:56:07+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hfrwhx/homepage_sitemonitor_of_tailscale_network/"> <img src="https://preview.redd.it/7ljwfah4n97e1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=8a8d8ca1d2cf8e9ee6a3c9308c59e8cc874520ac" alt="Homepage - sitemonitor of tailscale network machines return errors" title="Homepage - sitemonitor of tailscale network machines return errors" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey all, i have two proxmox remote instances with several services. Homepage shows error on ping to them. Well its obvious because homepage docker container return error on ping command. Docker container doesnt know anything about tailscale</p> <p>If i click on them to follow they surely work from firefox.</p> <p>How can i make it work to show the pings to remote servers,</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SeaworthinessIcy1448"> /u/SeaworthinessIcy1448 </a> <br/> <span><a href=

## Switching to All-Flash Drives Made Me Fall in Love with My NAS Again
 - [https://www.reddit.com/r/selfhosted/comments/1hfrep4/switching_to_allflash_drives_made_me_fall_in_love](https://www.reddit.com/r/selfhosted/comments/1hfrep4/switching_to_allflash_drives_made_me_fall_in_love)
 - RSS feed: $source
 - date published: 2024-12-16T19:34:57+00:00

<!-- SC_OFF --><div class="md"><p>I used to have a 6-bay NAS with six 10TB HDDs, mainly for storing media files and everyday backups. Since I love watching HD movies, the drives were often running at full speed. The noise was too much to handle—the constant humming of the fans and the clicking of the hard drives were quite annoying, especially at night. Sometimes, it even disrupted my sleep.I finally had enough and decided to explore all-flash NAS setups. After some research, I got a Ugreen DXP480T. I popped in four 2TB SSDs and set them up in RAID 5, giving me about 6TB of usable space. Sure, that’s less storage than before, but I restructured my storage strategy, trimming down my movie library and keeping only what I actually <a href="http://use.Now">use.Now</a>, this all-flash setup is nearly silent. No more fan noise or clicking drives. It has really improved things, especially at night when I need peace and quiet.For now, 6TB is more than enough for my needs, and I hope that SSD

## Help finding a sub-$100 PoE turret camera with light with no app/cloud needed
 - [https://www.reddit.com/r/selfhosted/comments/1hfrazj/help_finding_a_sub100_poe_turret_camera_with](https://www.reddit.com/r/selfhosted/comments/1hfrazj/help_finding_a_sub100_poe_turret_camera_with)
 - RSS feed: $source
 - date published: 2024-12-16T19:30:43+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a straightforward security camera for my home, but every marketplace is flooded with products that have unnecessary features. All I need is a PoE camera that streams video over the network—no apps, no cloud storage (if it&#39;s optional that&#39;s fine). I also want it to have an automatic floodlight for better visibility at night. Does anyone know if a camera like this still exists, or has the market moved entirely to app-dependent systems?</p> <p>Thanks! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/UrLilBrudder"> /u/UrLilBrudder </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfrazj/help_finding_a_sub100_poe_turret_camera_with/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfrazj/help_finding_a_sub100_poe_turret_camera_with/">[comments]</a></span>

## Dedicated self-hosting device recommendations
 - [https://www.reddit.com/r/selfhosted/comments/1hfr2ln/dedicated_selfhosting_device_recommendations](https://www.reddit.com/r/selfhosted/comments/1hfr2ln/dedicated_selfhosting_device_recommendations)
 - RSS feed: $source
 - date published: 2024-12-16T19:21:00+00:00

<!-- SC_OFF --><div class="md"><p>Greetings!</p> <p>I recently got into self hosting and im loving it! (for the most part haha). The reason I say for the most part is because I got started on my Synology, which is fine for the most part. But the amount of ports required by it for its own products creates network configuration issues so im looking to move towards a dedicated bare bones linux machine for self hosting.</p> <p>My plan is to create a home lab network and stick the dedicated device on it then run all my virtualizations off that while using the NAS for its original purpose - storage haha.</p> <p>I also wouldn&#39;t mind being able to do virtualizations with different linux distributions either.</p> <p>Im wondering if anyone has recommendations for dedicated devices for this? Also, I know the old saying &quot;the best one is the one that works&quot; haha. But I have some extra disposable income laying around that wouldn&#39;t mind investing into something a little more robus

## What is the best way to isolate apps/scripts in Linux?
 - [https://www.reddit.com/r/selfhosted/comments/1hfqq46/what_is_the_best_way_to_isolate_appsscripts_in](https://www.reddit.com/r/selfhosted/comments/1hfqq46/what_is_the_best_way_to_isolate_appsscripts_in)
 - RSS feed: $source
 - date published: 2024-12-16T19:06:26+00:00

<!-- SC_OFF --><div class="md"><p>I am self hosting and doing some app development, what is the best way of isolating them just like docker but am able to start/stop/restart, control amount of cpu, ram, disk, and most importantly restrict bandwidth and traffic usage. As far as I am aware that docker cannot control network usage.</p> <p>Any solutions? Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tonyliu_cloud"> /u/tonyliu_cloud </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfqq46/what_is_the_best_way_to_isolate_appsscripts_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfqq46/what_is_the_best_way_to_isolate_appsscripts_in/">[comments]</a></span>

## Mobile clients
 - [https://www.reddit.com/r/selfhosted/comments/1hfqeb0/mobile_clients](https://www.reddit.com/r/selfhosted/comments/1hfqeb0/mobile_clients)
 - RSS feed: $source
 - date published: 2024-12-16T18:53:16+00:00

<!-- SC_OFF --><div class="md"><p>I have been interested in setting up nextcloud but hesitating due to a few uncertainties: 1. I would like photos to be automatically backed upl 2. I need a photo app on my android and wife&#39;s iOS to view backed up photos. Needs to be easy to search/find photos 3. Facial recognition so I can sort by person would be great</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dry-Violinist197"> /u/Dry-Violinist197 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfqeb0/mobile_clients/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfqeb0/mobile_clients/">[comments]</a></span>

## [OpenSource] Auto-VPN - Self-hosted WireGuard VPN server manager for temporary secure connections
 - [https://www.reddit.com/r/selfhosted/comments/1hfqa4c/opensource_autovpn_selfhosted_wireguard_vpn](https://www.reddit.com/r/selfhosted/comments/1hfqa4c/opensource_autovpn_selfhosted_wireguard_vpn)
 - RSS feed: $source
 - date published: 2024-12-16T18:48:31+00:00

<!-- SC_OFF --><div class="md"><p>Like many of you, I value privacy and independence from subscription services. I found myself frequently needing temporary VPN servers for various tasks but didn&#39;t want to pay for commercial VPN services or deal with manual server setup each time.</p> <p>So I built Auto-VPN - a self-hosted tool that lets you spin up and manage your own WireGuard VPN servers on-demand. You only pay for the actual VPS usage (Vultr/Linode), and servers are automatically destroyed after inactivity.</p> <p><strong>Key points:</strong></p> <ul> <li>Full control over your VPN infrastructure</li> <li>No subscription fees - pay only for VPS time you actually use</li> <li>Simple Docker deployment</li> <li>PostgreSQL for data persistence</li> <li>Automated WireGuard setup</li> <li>Clean web UI for server management</li> </ul> <p><strong>Tech stack:</strong></p> <ul> <li>WireGuard</li> <li>Pulumi for infrastructure management</li> <li>Streamlit for web interface</li> <li>Doc

## Is it possible to get client IPs from remote connections when behind CGNat / using IPv6?
 - [https://www.reddit.com/r/selfhosted/comments/1hfq6yi/is_it_possible_to_get_client_ips_from_remote](https://www.reddit.com/r/selfhosted/comments/1hfq6yi/is_it_possible_to_get_client_ips_from_remote)
 - RSS feed: $source
 - date published: 2024-12-16T18:44:54+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve <a href="https://community.traefik.io/t/unable-to-get-real-ip-of-clients-for-my-setup-cf-cgnat-ipv6/25565">already asked on the Traefik community forums</a>, but I thought I might as well ask here too, hopefully someone will be able to help me accomplish this seemingly impossible task</p> <p><strong>Remote connections</strong> - in my setup - happen, afaict, like this:</p> <p>Client -&gt; CF for DNS with IPv6 of my Homeserver -&gt; Router forwarding ports 80&amp;443 to my Homeserver (Unraid) -&gt; Traefik (Docker) with Ports in Host mode</p> <p><strong>Local connections</strong> take the shortcut of using my servers local IPv4 address thanks to AdGuard Home.</p> <p>Using the <code>traefik/whoami</code> container I&#39;m able to correctly get the client IPs of my local devices, for remote connection it always shows the Docker DNS IP (<code>172.17.0.1</code>)</p> <p><strong>Note:</strong> code snippets are shortened to the important parts, the

## Self hosted forms tool Baserow and NocoDB
 - [https://www.reddit.com/r/selfhosted/comments/1hfq2d6/self_hosted_forms_tool_baserow_and_nocodb](https://www.reddit.com/r/selfhosted/comments/1hfq2d6/self_hosted_forms_tool_baserow_and_nocodb)
 - RSS feed: $source
 - date published: 2024-12-16T18:39:30+00:00

<!-- SC_OFF --><div class="md"><p>I have been checking out Baserow and NocoDB as self hosted form tools. I ended up thinking Baserow is going to be my jotform replacement but I went to add a second user today and its telling me I need a license for that. Am I missing something here? All I want is something that will allow me to make a survey form with conditional routes, file upload and the ability to resume the form if not completed and the ability to have accounts for my boss and a few coworkers. Is there maybe a better solution for this that I have not found. Self hosted is greatly preferred but we have a short form that we pay way too much to jotform for it makes no sense. Thank you all for your help.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Squanchy2112"> /u/Squanchy2112 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfq2d6/self_hosted_forms_tool_baserow_and_nocodb/">[link]</a></span> &#32; <span><a href="htt

## How should hdd and ssd storage be configured for lan cache?
 - [https://www.reddit.com/r/selfhosted/comments/1hfq0ek/how_should_hdd_and_ssd_storage_be_configured_for](https://www.reddit.com/r/selfhosted/comments/1hfq0ek/how_should_hdd_and_ssd_storage_be_configured_for)
 - RSS feed: $source
 - date published: 2024-12-16T18:37:08+00:00

<!-- SC_OFF --><div class="md"><p>Hi all!</p> <p>Within a few weeks i will be hosting a lan party for 20 a 30 peeps! I&#39;ve already been hosting servers ain&#39;t my main concern.</p> <p>My setup is very simple a 4 port nic on the server so each nic to a dedicated switch for a table. (Aka 4gb/s full throughput to the server)</p> <p>Server hardware: Ryzen 7 5700x 64gb ram</p> <p>Drives reserved for lan cache: 2* 1tb sata ssd 2* 8tb hdds</p> <p>Lan cache popped onto my radar and It looks great thing to add for a faster local download.</p> <p>My questions: - how much storage does lan cache use for 20 peeps? (Yes I know you can preload data) - in what configuration does the drives need to meet the storage and speed demand?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sebasdt"> /u/sebasdt </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfq0ek/how_should_hdd_and_ssd_storage_be_configured_for/">[link]</a></span> &#32; <span

## Security/firewall on internal network?
 - [https://www.reddit.com/r/selfhosted/comments/1hfpzna/securityfirewall_on_internal_network](https://www.reddit.com/r/selfhosted/comments/1hfpzna/securityfirewall_on_internal_network)
 - RSS feed: $source
 - date published: 2024-12-16T18:36:15+00:00

<!-- SC_OFF --><div class="md"><p>What are you all doing to keep your server secure from threats on your internal network? I had a bit of a lightbulb moment today where I realized that the biggest security hole in my current setup would be a scenario where one of my kids inadvertently installs some malicious code/software on a computer attached to my home network. Or maybe one of their friends connects to wifi with a compromised device.</p> <p>Right now my setup is very simple, all devices are on the same subnet, including a Linux server running multiple services via docker. I use tailscale or wireguard for external access to the network, and I only have two ports open externally (Plex and a Minecraft server). But internally everything is open - any device connected to the internal LAN has access to the server.</p> <p>What should I do to tighten up my security? I looked into setting up a firewall on the Linux machine, but it seems like a huge headache to get that working properly wit

## I also want to show my PhoneServer
 - [https://www.reddit.com/r/selfhosted/comments/1hfoziz/i_also_want_to_show_my_phoneserver](https://www.reddit.com/r/selfhosted/comments/1hfoziz/i_also_want_to_show_my_phoneserver)
 - RSS feed: $source
 - date published: 2024-12-16T17:54:33+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hfoziz/i_also_want_to_show_my_phoneserver/"> <img src="https://preview.redd.it/s26ys6af197e1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=db8913eaca2c5763ccd1ca01d1c0f2a6537b235a" alt="I also want to show my PhoneServer" title="I also want to show my PhoneServer" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dadnothere"> /u/dadnothere </a> <br/> <span><a href="https://i.redd.it/s26ys6af197e1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfoziz/i_also_want_to_show_my_phoneserver/">[comments]</a></span> </td></tr></table>

## Problem in selfhosting newbie
 - [https://www.reddit.com/r/selfhosted/comments/1hfoz69/problem_in_selfhosting_newbie](https://www.reddit.com/r/selfhosted/comments/1hfoz69/problem_in_selfhosting_newbie)
 - RSS feed: $source
 - date published: 2024-12-16T17:54:09+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I have an old PC and I wanted to use it as a server hosting few DVDs and personal images.<br/> It&#39;s a Linux Mint machine (dual boot) and I instaled Immich and Jellyfin in a docker container. My goal would be to just power on the machine and have all my devices in the local network be able to see movies and images.</p> <p>At first the containers were configured to start automatically but:</p> <ol> <li>Immich : seems that the docker container starts too fast and the data is empty;</li> <li>Jellyfin : I put all my media in a large HD visible from windows and linux but movies can&#39;t start because the pc doesn&#39;t automatically mount the drive;</li> </ol> <p>If I login, stop all containers, mount drive and start all cointainers all works fine. Both Immich and Jellyfin.</p> <p>So I tried to write a batch file .sh to mount the drive and start the containers but I had to do a &quot;sudo mount&quot; and seems I can&#39;t do this action 

## PSA: check your Synology recycle bin configs
 - [https://www.reddit.com/r/selfhosted/comments/1hfortu/psa_check_your_synology_recycle_bin_configs](https://www.reddit.com/r/selfhosted/comments/1hfortu/psa_check_your_synology_recycle_bin_configs)
 - RSS feed: $source
 - date published: 2024-12-16T17:45:45+00:00

<!-- SC_OFF --><div class="md"><p>Had the recycle bin enabled for a couple folders, including Proxmox backup and Docker swarm data backup from my CEPH pool. Just cleared 12.5 TB, over 30% of that storage pool. Needless to say the recycle bins have been disabled for those folders. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/doctorowlsound"> /u/doctorowlsound </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfortu/psa_check_your_synology_recycle_bin_configs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfortu/psa_check_your_synology_recycle_bin_configs/">[comments]</a></span>

## Seeking Open Source or Free Tools for AI-Based Content Automation (blogging, news-writing)
 - [https://www.reddit.com/r/selfhosted/comments/1hfo2sx/seeking_open_source_or_free_tools_for_aibased](https://www.reddit.com/r/selfhosted/comments/1hfo2sx/seeking_open_source_or_free_tools_for_aibased)
 - RSS feed: $source
 - date published: 2024-12-16T17:16:35+00:00

<!-- SC_OFF --><div class="md"><p>Are there any solutions, whether open-source self-hosted or proprietary, free or paid (but preferably free, haha), that would allow for the automation of blogging or a website on WordPress posting or, for example, a Telegram channel posting using neural networks (like ChatGPT or perhaps even self-hosted Llama)? </p> <p>Such solutions, that can automate rewriting of materials from user-specified sources and automatic post creation?</p> <p>I&#39;ve seen some websites that look very much like they were written by neural networks. Some even seem not to bother with manual curation of materials. What solutions are they using for these tasks?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/wallofbytes"> /u/wallofbytes </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfo2sx/seeking_open_source_or_free_tools_for_aibased/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/co

## Nginx Proxy Manager (NPM) Just stopped working
 - [https://www.reddit.com/r/selfhosted/comments/1hfnjoo/nginx_proxy_manager_npm_just_stopped_working](https://www.reddit.com/r/selfhosted/comments/1hfnjoo/nginx_proxy_manager_npm_just_stopped_working)
 - RSS feed: $source
 - date published: 2024-12-16T16:54:22+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone!</p> <p>I have a home server setup with proxmox as my hypervisor and a ubuntu server VM that has most of the workload</p> <p>In the ubuntu VM I have portainer as the container manager and I have several services running.</p> <p>I have a domain and the DNS is managed through CloudFare</p> <p>I had several dubdomains proxied with NPM, and everything was working fine, but suddenly I woke up today and nothing works, I recieve a 502 response from cloudfare when triying to acces the services through the domain.</p> <p>Locally using the VM ip with the service port everything works</p> <p>It just that NPM stopped working for no reason.</p> <p>Ive read online some similar posts and problems that are quite old, still tried some of the &quot;solutions&quot; but nothing has worked for mi.</p> <p>As a last resort I read someone that just had to reinstall PROXMOX, which is a last case scenario for me.</p> <p>More details:</p> <ol> <li><p>From within t

## Web Based Alternative to Gucamole that does RDP and Has its Shit Together?
 - [https://www.reddit.com/r/selfhosted/comments/1hfmxlc/web_based_alternative_to_gucamole_that_does_rdp](https://www.reddit.com/r/selfhosted/comments/1hfmxlc/web_based_alternative_to_gucamole_that_does_rdp)
 - RSS feed: $source
 - date published: 2024-12-16T16:27:33+00:00

<!-- SC_OFF --><div class="md"><p>I have been using Guacamole for a while now but there are a number of issues that keep on annoying me, namely shared clipboard support breaking in Firefox recently (yes, <code>dom.events.testing.asyncClipboard</code> is set to <code>true</code>). Bonus points if it actually supports GPU accelerated VNC connections on Linux using the client&#39;s GPU not the guest&#39;s (which Gucamole doesn&#39;t do well).</p> <p>Background:</p> <p>I use Proxmox to manage a bunch of Linux &amp; Windows Test VMs for Software Development. Proxmox&#39; console is awful for Windows clients (Proxmox is awful for Windows in general, but that&#39;s a KVM/Qemu issue namely around nested virtualization) and if I could just use those I&#39;d set up all of my templates to. If someone knows a good unified Proxmox solution I&#39;d be all in on that.</p> <p>idk if there&#39;s value in x-posting to other subs. I will post this one other place but did not want to spam all of the Vir

## Putting Nginx Proxy Manager Admin Console behind Authentik?
 - [https://www.reddit.com/r/selfhosted/comments/1hfldxq/putting_nginx_proxy_manager_admin_console_behind](https://www.reddit.com/r/selfhosted/comments/1hfldxq/putting_nginx_proxy_manager_admin_console_behind)
 - RSS feed: $source
 - date published: 2024-12-16T15:18:59+00:00

<!-- SC_OFF --><div class="md"><p>Has anyone here put the admin console (usually port 81) for nginx proxy manager itself behind Authentik? How did you go about it? Also, is doing this overkill/stupid?</p> <p>I&#39;m also new to using authentication, and I&#39;m wondering if it would be useful for pages that would normally get a 404 response to instead get the authentik sign in page. That way, it might be harder to figure out what urls are legitimate and which ones aren&#39;t?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ottovonbizmarkie"> /u/ottovonbizmarkie </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfldxq/putting_nginx_proxy_manager_admin_console_behind/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfldxq/putting_nginx_proxy_manager_admin_console_behind/">[comments]</a></span>

## Web based video player recommendation
 - [https://www.reddit.com/r/selfhosted/comments/1hfl17z/web_based_video_player_recommendation](https://www.reddit.com/r/selfhosted/comments/1hfl17z/web_based_video_player_recommendation)
 - RSS feed: $source
 - date published: 2024-12-16T15:02:37+00:00

<!-- SC_OFF --><div class="md"><p>Long time reader, first time poster here. I&#39;m wondering if any of you have any recommendations for the following scenario:</p> <p>I have a bunch of home videos that I want to make available for viewing. The solution would preferably be a web page/storage bucket with built-in video player so users (read: family) can log in an play their videos.</p> <p>I&#39;ve tried NextCloudPi, which does the trick but doesn&#39;t include thumbnails or video preview. Also, it seems like overkill for a fairly simple idea, with all the options that are built-in. I&#39;ve also spun up a JellyFin container, as I use it for regular media streaming, but this doesn&#39;t have the option to add videos straight from the interface, so it would require an upload to a separate location.</p> <p>Requirements:</p> <ul> <li>Web login</li> <li>Option to upload video directly in web interface</li> <li>Files preferably stored in an encrypted volume</li> <li>Preferably available as 

## Self-hosting Quake III Arena securely with https
 - [https://www.reddit.com/r/selfhosted/comments/1hfks0u/selfhosting_quake_iii_arena_securely_with_https](https://www.reddit.com/r/selfhosted/comments/1hfks0u/selfhosting_quake_iii_arena_securely_with_https)
 - RSS feed: $source
 - date published: 2024-12-16T14:51:19+00:00

<!-- SC_OFF --><div class="md"><p>Just wanted to share that I&#39;m working on a simple recipe for self-hosting Quake III Arena JS securely with http2. The formula uses docker + <a href="https://kamal-deploy.org/">kamal</a> for a simple one-command deploy to a server - either one you own or a cloud VM. (kamal nicely takes care of the reverse proxy)</p> <p>At present: only single player / multiplayer with bots is available. You can try out the <a href="https://kamal-quake.xyz/">current running instance here</a>, press escape to enter the menu to play either available modes.</p> <p>Working on the final piece: successfully routing the secure socket wss through the proxy.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/neonwatty"> /u/neonwatty </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfks0u/selfhosting_quake_iii_arena_securely_with_https/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comme

## Solution for keeping track of my team? See long text.
 - [https://www.reddit.com/r/selfhosted/comments/1hfkrsn/solution_for_keeping_track_of_my_team_see_long](https://www.reddit.com/r/selfhosted/comments/1hfkrsn/solution_for_keeping_track_of_my_team_see_long)
 - RSS feed: $source
 - date published: 2024-12-16T14:51:01+00:00

<!-- SC_OFF --><div class="md"><p>Right now we have a working (albeit messy) solution for tracking our techs location and last-updated time. I would like a cleaner and possibly more professional looking way to track this information. Any ideas? I&#39;ll answer any questions I can for clarification. Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/humanHamster"> /u/humanHamster </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfkrsn/solution_for_keeping_track_of_my_team_see_long/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfkrsn/solution_for_keeping_track_of_my_team_see_long/">[comments]</a></span>

## Self hosting
 - [https://www.reddit.com/r/selfhosted/comments/1hfkpuq/self_hosting](https://www.reddit.com/r/selfhosted/comments/1hfkpuq/self_hosting)
 - RSS feed: $source
 - date published: 2024-12-16T14:48:32+00:00

<!-- SC_OFF --><div class="md"><p>So I have this old laptop that i don’t use anymore. I wanted to know how can I turn it into a server that I can host my websites and databases for those websites. Its a cheaper way then paying cloud services like aws or azure and stuff. Now I have never built one and I am complete noob when it comes to it. I saw online some videos but they were mostly home servers and not what i was looking for. Any suggestions? Youtube videos? Or a person to help I would appreciate it a lot</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FidanAG"> /u/FidanAG </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfkpuq/self_hosting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfkpuq/self_hosting/">[comments]</a></span>

## Video File Storage
 - [https://www.reddit.com/r/selfhosted/comments/1hfknpt/video_file_storage](https://www.reddit.com/r/selfhosted/comments/1hfknpt/video_file_storage)
 - RSS feed: $source
 - date published: 2024-12-16T14:45:43+00:00

<!-- SC_OFF --><div class="md"><p>Is TrueNas the best option to store my files? Also liking the future possibility of a Hex OS install for external server backups</p> <p>I have a large number of video files I would like to store with some redundancy. Vid files are currently only locally and externally backed up no cloud</p> <p>Video files are all dashcam footage from various vacations, pushing about 2TB at the moment, plus finished edited timelapses that I am slowly getting posted to Youtube.</p> <p>Currently using Davinci Resolve to edit them if thats of any relevance</p> <p>I also am looking to store all our personal photos on a Immich install to replace our current local solution of external hard drives, these are also on Google Photos as my cloud backup, and on external drives at a friends for offsite backup.</p> <p>I also have a Home Assistant install I would ideally port over to the system running all of this</p> <p>Is there a better solution? What would good best practice be</

## How to Move Discord Bot from Replit to Self Hosted in Docker
 - [https://www.reddit.com/r/selfhosted/comments/1hfjvqm/how_to_move_discord_bot_from_replit_to_self](https://www.reddit.com/r/selfhosted/comments/1hfjvqm/how_to_move_discord_bot_from_replit_to_self)
 - RSS feed: $source
 - date published: 2024-12-16T14:08:38+00:00

<!-- SC_OFF --><div class="md"><p>I am running a discord bot written in Node.js on Replit, but apparently you can no longer keep it awake 24/7. Im wondering if this bot couple be dockerized and self hosted. </p> <p>I&#39;m new to this, and not really sure where to start. I was hoping someone could give me a general outline of the steps required to bring this in house. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bamfcoco1"> /u/bamfcoco1 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfjvqm/how_to_move_discord_bot_from_replit_to_self/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfjvqm/how_to_move_discord_bot_from_replit_to_self/">[comments]</a></span>

## Need opinion
 - [https://www.reddit.com/r/selfhosted/comments/1hfjpx2/need_opinion](https://www.reddit.com/r/selfhosted/comments/1hfjpx2/need_opinion)
 - RSS feed: $source
 - date published: 2024-12-16T14:01:01+00:00

<!-- SC_OFF --><div class="md"><p>So I got a pc for 95usd with the specs</p> <p>R5 3400G 16GB DDR4 3200MHz Ram MSI B450 DS3H Cooler Master 550W PSU No storage or gpu</p> <p>(I got a 1060 amp lying around and can plug it in. Should I?)</p> <p>I need help setting up a basic home server.</p> <p>I want to run this pc all the time so need help with power optimization too.</p> <p>I intend to run Plex/Jellyfin Minecraft server (Both modded and vanilla for like 5 players) Host websites (Suggestions on what else can be done with this build would be nice)</p> <p>Questions 1. Is it a good deal at 95usd? 2. How should I setup the home server? What is and what are the steps? I saw a few youtube videos suggesting proxmox and a few saying Debian. 3. What are some power optimization tips?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/folylolyboyz"> /u/folylolyboyz </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfjpx2/need_opinion/">[l

## Storecraft.app is a self-hosted commerce-as-code platform (self-hosted shopify)
 - [https://www.reddit.com/r/selfhosted/comments/1hfjo66/storecraftapp_is_a_selfhosted_commerceascode](https://www.reddit.com/r/selfhosted/comments/1hfjo66/storecraftapp_is_a_selfhosted_commerceascode)
 - RSS feed: $source
 - date published: 2024-12-16T13:58:46+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hfjo66/storecraftapp_is_a_selfhosted_commerceascode/"> <img src="https://b.thumbs.redditmedia.com/V23kzCrMudAO_V4rC5kIhC_9JcOyAUU0v80UHknhSNI.jpg" alt="Storecraft.app is a self-hosted commerce-as-code platform (self-hosted shopify)" title="Storecraft.app is a self-hosted commerce-as-code platform (self-hosted shopify)" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hendrixstring"> /u/hendrixstring </a> <br/> <span><a href="https://www.reddit.com/gallery/1hfjo66">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfjo66/storecraftapp_is_a_selfhosted_commerceascode/">[comments]</a></span> </td></tr></table>

## Storecraft is a self-hosted open-source commerce-as-code platform
 - [https://www.reddit.com/r/selfhosted/comments/1hfjn0j/storecraft_is_a_selfhosted_opensource](https://www.reddit.com/r/selfhosted/comments/1hfjn0j/storecraft_is_a_selfhosted_opensource)
 - RSS feed: $source
 - date published: 2024-12-16T13:57:08+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/hendrixstring"> /u/hendrixstring </a> <br/> <span><a href="https://storecraft.app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfjn0j/storecraft_is_a_selfhosted_opensource/">[comments]</a></span>

## Storecraft is a self-hosted commerce-as-code solution and backend
 - [https://www.reddit.com/r/selfhosted/comments/1hfjktr/storecraft_is_a_selfhosted_commerceascode](https://www.reddit.com/r/selfhosted/comments/1hfjktr/storecraft_is_a_selfhosted_commerceascode)
 - RSS feed: $source
 - date published: 2024-12-16T13:54:04+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hfjktr/storecraft_is_a_selfhosted_commerceascode/"> <img src="https://b.thumbs.redditmedia.com/qNWU-bIn8vYdUcpFpyAOEz8xve-CVg41RSgQTgU5HHQ.jpg" alt="Storecraft is a self-hosted commerce-as-code solution and backend" title="Storecraft is a self-hosted commerce-as-code solution and backend" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi 👋, <code>Storecraft</code> is a next generation Commerce As Code javascript backend.</p> <p>⭐ run on any javascript <a href="https://storecraft.app/docs/backend/platforms/node">platform</a> (deno, bun, node, workers, aws-lambda, google-functions), serverless / serverful</p> <p>⭐ connect to any <a href="https://storecraft.app/docs/backend/databases/sqlite">database</a> (mongo, sqlite, postgres, mysql, neon, turso, d1, planetscale). </p> <p>⭐ use <a href="https://storecraft.app/docs/backend/storage/s3">storage</a> (local, r2, s3 compatible, google and more)</p> <p>⭐ It is <a h

## Self hosted Strava statistics
 - [https://www.reddit.com/r/selfhosted/comments/1hfjjtf/self_hosted_strava_statistics](https://www.reddit.com/r/selfhosted/comments/1hfjjtf/self_hosted_strava_statistics)
 - RSS feed: $source
 - date published: 2024-12-16T13:52:39+00:00

<!-- SC_OFF --><div class="md"><p>I created a Docker image to generate your own Strava statistics pages. I didn&#39;t want to pay for a premium account, so I created extended statistics myself.</p> <ul> <li>Example: <a href="https://strava-statistics.robiningelbrecht.be">https://strava-statistics.robiningelbrecht.be</a></li> <li>Installation instructions: <a href="https://github.com/robiningelbrecht/strava-statistics">https://github.com/robiningelbrecht/strava-statistics</a></li> </ul> <p>I provided a simple docker compose example in the readme.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/frogfuhrer"> /u/frogfuhrer </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfjjtf/self_hosted_strava_statistics/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfjjtf/self_hosted_strava_statistics/">[comments]</a></span>

## Jellyfin Hevc 10bit
 - [https://www.reddit.com/r/selfhosted/comments/1hfiotz/jellyfin_hevc_10bit](https://www.reddit.com/r/selfhosted/comments/1hfiotz/jellyfin_hevc_10bit)
 - RSS feed: $source
 - date published: 2024-12-16T13:07:51+00:00

<!-- SC_OFF --><div class="md"><p>Using an N100 windows mini pc. Original file is hevc 10bit. On firefox jellyfin a 4k h264 is transcoded which stutters On the jellyfin media app, it direct plays but stutters 10x more.</p> <p>Any ideas for solving either? I.e. adding hevc10bit support to firefox/ resolving the direct pkay stutter</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Proper_Albatross2926"> /u/Proper_Albatross2926 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfiotz/jellyfin_hevc_10bit/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfiotz/jellyfin_hevc_10bit/">[comments]</a></span>

## PVE Post Install script not working with 8.3.1
 - [https://www.reddit.com/r/selfhosted/comments/1hfifzn/pve_post_install_script_not_working_with_831](https://www.reddit.com/r/selfhosted/comments/1hfifzn/pve_post_install_script_not_working_with_831)
 - RSS feed: $source
 - date published: 2024-12-16T12:54:38+00:00

<!-- SC_OFF --><div class="md"><p>The PVE Post Install script <a href="https://community-scripts.github.io/ProxmoxVE/scripts?id=post-pve-install">Proxmox VE Helper-Scripts</a> doesn&#39;t seem to work with 8.3.1, as it still says &quot;No Proxmox VE repository enabled&quot; after rebooting. </p> <p>I updated all three of my machines last week, and one of them says &quot;Proxmox VE updates Non production-ready repository enabled!&quot; but I&#39;m not sure if I ran the script on that, or if it just kept working after I updated.</p> <p>I checked the /etc/apt/sources.list on all three machines, and I noticed that on the one with the working repository it had <a href="http://ftp.debian.org/debian">http://ftp.debian.org/debian</a> and the others had <a href="http://deb.debian.org/debian">http://deb.debian.org/debian</a>, so I tried changing that and rebooting but that hasn&#39;t made any difference.</p> <p>I tried adding </p> <pre><code>deb http://download.proxmox.com/debian/pve bookworm 

## Firefly-Pico v1.5 released
 - [https://www.reddit.com/r/selfhosted/comments/1hfho9p/fireflypico_v15_released](https://www.reddit.com/r/selfhosted/comments/1hfho9p/fireflypico_v15_released)
 - RSS feed: $source
 - date published: 2024-12-16T12:07:25+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone!</p> <p><strong>Firefly-Pico</strong> is a Firefly III companion web app, which is optimised for mobile and focuses on making expense tracking fast.</p> <p>Some of the highlights of this release:</p> <ul> <li>faster app startup (6x less data transfered via smaller build + brotli compression)</li> <li>configurable starting page</li> <li>scroll to validation errors</li> <li>better dashboard navigation and a lot of UI improvements</li> </ul> <p>Full changelog on Github: <a href="https://github.com/cioraneanu/firefly-pico/releases/tag/1.5.0">1.5.0</a></p> <p>Suggestions for new features are always welcomed.</p> <p>Happy expense tracking! 😇</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cioraneanumihai"> /u/cioraneanumihai </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfho9p/fireflypico_v15_released/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/com

## 5 Low-Cost Business Ideas with HUGE Profits in 2025!
 - [https://www.reddit.com/r/selfhosted/comments/1hfhfz5/5_lowcost_business_ideas_with_huge_profits_in_2025](https://www.reddit.com/r/selfhosted/comments/1hfhfz5/5_lowcost_business_ideas_with_huge_profits_in_2025)
 - RSS feed: $source
 - date published: 2024-12-16T11:53:31+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hfhfz5/5_lowcost_business_ideas_with_huge_profits_in_2025/"> <img src="https://external-preview.redd.it/3k8LerI5HAI4EWYQflAk3tRFUxMbnB7mheZY5427phY.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=d1411632ba35b73b48af06081625941e08113c9e" alt="5 Low-Cost Business Ideas with HUGE Profits in 2025!" title="5 Low-Cost Business Ideas with HUGE Profits in 2025!" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Outrageous_Row8249"> /u/Outrageous_Row8249 </a> <br/> <span><a href="https://youtu.be/tHqAAAvVXjI?si=JiQREmODXJMqPsFb">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfhfz5/5_lowcost_business_ideas_with_huge_profits_in_2025/">[comments]</a></span> </td></tr></table>

## Looking for selfhosted Sports Management Platform
 - [https://www.reddit.com/r/selfhosted/comments/1hfh6g5/looking_for_selfhosted_sports_management_platform](https://www.reddit.com/r/selfhosted/comments/1hfh6g5/looking_for_selfhosted_sports_management_platform)
 - RSS feed: $source
 - date published: 2024-12-16T11:35:43+00:00

<!-- SC_OFF --><div class="md"><p>Hello</p> <p>I am looking for a Sports Management Platform solution that very similar to <a href="http://simplycompete.com">simplycomplete</a> platform</p> <p>simplycomplete have massive tools and features but i only want very small tools and features such as:-</p> <ul> <li><p>registration form have option to add and remove and make conditions to some fields show up or not </p> <p>-Example : <a href="https://worldtkd.simplycompete.com/signUp">https://worldtkd.simplycompete.com/signUp</a></p></li> <li><p>Make roles like, Athlete, coach, referee etc..</p></li> <li><p>Make events so Athlete, coaches, referee can participate</p> <p>-Example : <a href="https://worldtkd.simplycompete.com/events">https://worldtkd.simplycompete.com/events</a></p></li> <li><p>make Athlete participate to those events based on specific condition like age, weight, belt degree etc..</p></li> </ul> <p>Regards</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.r

## How do I reverse proxy a php subpath to a subdomain please?
 - [https://www.reddit.com/r/selfhosted/comments/1hfghgc/how_do_i_reverse_proxy_a_php_subpath_to_a](https://www.reddit.com/r/selfhosted/comments/1hfghgc/how_do_i_reverse_proxy_a_php_subpath_to_a)
 - RSS feed: $source
 - date published: 2024-12-16T10:47:11+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I am new to homelabbing so I will try explain as best I can.</p> <p>I have MyBB sitting in the htdocs folder of Xampp, which I access from <code>192.168.5.201/forum</code></p> <p>I would like to reverse proxy this to <code>forum.web.xyz</code>However It&#39;s proving difficult.</p> <p>Currently my Caddy config looks like this:</p> <pre><code>forum.web.xyz { handle_path /* { reverse_proxy 192.168.5.201/forum } } </code></pre> <p>Going to forum.web.xyz returns <code>Bad gateway Error code 502</code> </p> <p>Any help would be appreciated :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/GhastlyIsMe"> /u/GhastlyIsMe </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfghgc/how_do_i_reverse_proxy_a_php_subpath_to_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfghgc/how_do_i_reverse_proxy_a_php_subpath_to_a/">[comments]</a></span>

## Puzzled and a little disgruntled...
 - [https://www.reddit.com/r/selfhosted/comments/1hffe0e/puzzled_and_a_little_disgruntled](https://www.reddit.com/r/selfhosted/comments/1hffe0e/puzzled_and_a_little_disgruntled)
 - RSS feed: $source
 - date published: 2024-12-16T09:23:41+00:00

<!-- SC_OFF --><div class="md"><p>I have an old Nas that can&#39;t be upgraded/refreshed and the time has come to replace it so I put some new disks in a spare PC and set off into the world of self hosting and home servers.</p> <p>3 disks in all, 1 system and 2 setup as Raid1.</p> <p>As the fundamental use is a Nas I started off with TrueNas Scale but it seemed determined to confuse and frustrate me. Support isn&#39;t great and the YT videos are not the best so that was quickly removed.</p> <p>I then setup Ubuntu Server 24.04 with Casaos and Cockpit a combination I was able to get up and running, it took a little time but the information I needed was readily available.</p> <p>Now I&#39;m getting to the troublesome areas, areas that might exist only because I lack familiarity with the system or may be real.</p> <p>CasaOS file manager.</p> <p>I would like to be able to see my old Nas and copy my files from it.</p> <p>Mounting my Raid.</p> <p>I mounted it in /mnt as it will be shared bu

## Children's school homepage portal
 - [https://www.reddit.com/r/selfhosted/comments/1hffajr/childrens_school_homepage_portal](https://www.reddit.com/r/selfhosted/comments/1hffajr/childrens_school_homepage_portal)
 - RSS feed: $source
 - date published: 2024-12-16T09:15:56+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I was wondering if anyone uses or has advice on this please.</p> <p>I want to host a page that will tell my kids what the school timetable for the day is, and if possible homework (satchel one I believe) etc.</p> <p>The school has a week a and week b timetable which would need to be flipped each week.</p> <p>Preferably displayed on an android tablet, Web browser would be fine.</p> <p>It would be nice if it had a morning checklist (make bed, tidy room, etc) and if I could put on there what the evening meal would be etc.</p> <p>If a current homepage app already does this, a config would be appreciated Because I don&#39;t know how to program in any of those apps how to do a daily timetable that changes on a weekly basis.</p> <p>Cheers Tia.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/simonmcnair"> /u/simonmcnair </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hffajr/childrens_school_h

## Experiences with Self-Hosted Novu? Looking for Real-World Feedback on Multi-Channel Notifications
 - [https://www.reddit.com/r/selfhosted/comments/1hff1h4/experiences_with_selfhosted_novu_looking_for](https://www.reddit.com/r/selfhosted/comments/1hff1h4/experiences_with_selfhosted_novu_looking_for)
 - RSS feed: $source
 - date published: 2024-12-16T08:56:39+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m considering self-hosting Novu (<a href="https://github.com/novuhq/novu">https://github.com/novuhq/novu</a>) and would love to hear from anyone who&#39;s currently running it in production or has experimented with it. </p> <p>My use case:<br/> I&#39;m building a monitoring system for our homelab/self-hosted services where I need to:<br/> - Send immediate SMS alerts for critical system failures<br/> - Deliver daily digest emails summarizing system health<br/> - Show in-app notifications for less urgent updates (like successful backups, updates available, etc.)<br/> - Allow users to set their notification preferences per channel </p> <p>Specifically, I&#39;m interested in:<br/> - Your deployment setup (Docker, k8s, bare metal?)<br/> - Resource usage and performance at scale<br/> - Any gotchas or pain points you&#39;ve encountered<br/> - Integration experiences with other self-hosted services<br/> - How reliable you&#39;ve found it for critical n

## best document and picture manager with OCR so i can search keywords
 - [https://www.reddit.com/r/selfhosted/comments/1hfeywz/best_document_and_picture_manager_with_ocr_so_i](https://www.reddit.com/r/selfhosted/comments/1hfeywz/best_document_and_picture_manager_with_ocr_so_i)
 - RSS feed: $source
 - date published: 2024-12-16T08:50:52+00:00

<!-- SC_OFF --><div class="md"><p>like the title says, what is your best setup for this ? nextcloud with doc search, paperlessNGX or something else? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/2samedru"> /u/2samedru </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfeywz/best_document_and_picture_manager_with_ocr_so_i/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfeywz/best_document_and_picture_manager_with_ocr_so_i/">[comments]</a></span>

## backup-manager does not backs up some tables
 - [https://www.reddit.com/r/selfhosted/comments/1hfepuf/backupmanager_does_not_backs_up_some_tables](https://www.reddit.com/r/selfhosted/comments/1hfepuf/backupmanager_does_not_backs_up_some_tables)
 - RSS feed: $source
 - date published: 2024-12-16T08:30:48+00:00

<!-- SC_OFF --><div class="md"><p>Hi !</p> <p>It&#39;s been several years I&#39;m using the backup-manager script to backup my mysql databases. This morning I&#39;ve discovered that some tables within my databases are not backuped. No error, no warning.</p> <p>Any idea what would cause this behaviour, any alternative to recomend ?</p> <p>Thanks !</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kenaddams42"> /u/kenaddams42 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfepuf/backupmanager_does_not_backs_up_some_tables/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfepuf/backupmanager_does_not_backs_up_some_tables/">[comments]</a></span>

## Question about email providers because I'm not sure I'm finding what I am looking for
 - [https://www.reddit.com/r/selfhosted/comments/1hfen0t/question_about_email_providers_because_im_not](https://www.reddit.com/r/selfhosted/comments/1hfen0t/question_about_email_providers_because_im_not)
 - RSS feed: $source
 - date published: 2024-12-16T08:24:29+00:00

<!-- SC_OFF --><div class="md"><p>My current hosting providers allows me to just manage email addresses per domain. So I just go in and setup the domain (obviously I have to coordinate the DNS setup), and add addresses to it as needed:</p> <ul> <li>domain1.com <ul> <li>- <a href="mailto:user1@domain1.com">user1@domain1.com</a></li> </ul></li> <li>domain2.com <ul> <li>- <a href="mailto:user1@domain2.com">user1@domain2.com</a></li> <li>- <a href="mailto:user2@domain2.com">user2@domain2.com</a></li> <li>- <a href="mailto:user3@domain2.com">user3@domain2.com</a></li> </ul></li> </ul> <p>Each of those addresses is it&#39;s own individual login. So whether I am using IMAP, POP, or the webconsole I login with the email address as the username and what password. Unless I&#39;m misunderstanding how it works, that doesn&#39;t seem to be how Fastmail works, so they seem to be a non-starter for me. I&#39;m experimenting with mailbox.org at the moment. </p> <p>Can anyone share any recommendations

## A full-fledged terminal chat with Google AI (Gemini) generative models
 - [https://www.reddit.com/r/selfhosted/comments/1hfeece/a_fullfledged_terminal_chat_with_google_ai_gemini](https://www.reddit.com/r/selfhosted/comments/1hfeece/a_fullfledged_terminal_chat_with_google_ai_gemini)
 - RSS feed: $source
 - date published: 2024-12-16T08:05:56+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hfeece/a_fullfledged_terminal_chat_with_google_ai_gemini/"> <img src="https://external-preview.redd.it/fB91_p17Jedx7r3pXfl-EGspwPZ9nWhJ4bIJNSVPGPM.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=1b91db2ff89e8e7ed66c3bf400d5d741a5877d81" alt="A full-fledged terminal chat with Google AI (Gemini) generative models" title="A full-fledged terminal chat with Google AI (Gemini) generative models" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/petaoctet"> /u/petaoctet </a> <br/> <span><a href="https://github.com/reugn/gemini-cli">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfeece/a_fullfledged_terminal_chat_with_google_ai_gemini/">[comments]</a></span> </td></tr></table>

## Is that good for mine simple server ?
 - [https://www.reddit.com/r/selfhosted/comments/1hfec4h/is_that_good_for_mine_simple_server](https://www.reddit.com/r/selfhosted/comments/1hfec4h/is_that_good_for_mine_simple_server)
 - RSS feed: $source
 - date published: 2024-12-16T08:01:20+00:00

<!-- SC_OFF --><div class="md"><p>I have old, useless smartphone - Techno Camon 19. Characteristics: 5000 mAh, 6-8GB RAM, Helio G96, 128GB Internal, Mali-G57 MC2</p> <p>More: <a href="https://m.gsmarena.com/tecno_camon_19_pro-11618.php">https://m.gsmarena.com/tecno_camon_19_pro-11618.php</a></p> <p>Maybe, it&#39;s good to root it and try to overclock and &quot;upgrade it&quot; adding a fan. I&#39;m currently living in Ukraine where is blackouts for like a 4 hours in a day and 0-3 hours at night (living in Zakarpatta&#39; where no big blackouts). I wanna setup smth like termux, arch chroot, minecraft server maybe and web server. I currently have another PC, not including my own: 8GB DDR3 RAM, Phenom II Black Edition, GT 630 with custom fan, Arch Linux, but it eating too much power for it capabilities.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Lines25"> /u/Lines25 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfec4h

## Help with building Cloud at home for my friend
 - [https://www.reddit.com/r/selfhosted/comments/1hfe562/help_with_building_cloud_at_home_for_my_friend](https://www.reddit.com/r/selfhosted/comments/1hfe562/help_with_building_cloud_at_home_for_my_friend)
 - RSS feed: $source
 - date published: 2024-12-16T07:46:49+00:00

<!-- SC_OFF --><div class="md"><p>So I’m in Thailand right now and I friend of mine has an older Android and a windows laptop. She doesn’t like Google cloud, so I recommended her to host it by herself at home and I can help her. </p> <p>How can I make sure her home network will be fine when accessing from outside? Buy a domain, set up a vpn to then connect home? </p> <p>Which hardware can emulate same experience as with Google photos? </p> <p>What do you think of a budget is necessary to build it? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Exotic-Appearance562"> /u/Exotic-Appearance562 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfe562/help_with_building_cloud_at_home_for_my_friend/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfe562/help_with_building_cloud_at_home_for_my_friend/">[comments]</a></span>

## Kavita vs Ubooquity vs Calibre
 - [https://www.reddit.com/r/selfhosted/comments/1hfdxfp/kavita_vs_ubooquity_vs_calibre](https://www.reddit.com/r/selfhosted/comments/1hfdxfp/kavita_vs_ubooquity_vs_calibre)
 - RSS feed: $source
 - date published: 2024-12-16T07:30:18+00:00

<!-- SC_OFF --><div class="md"><p>Which one do you use to host your eBooks and what clientside software / apps do you use to access the server?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/anonymoize"> /u/anonymoize </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfdxfp/kavita_vs_ubooquity_vs_calibre/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfdxfp/kavita_vs_ubooquity_vs_calibre/">[comments]</a></span>

## Retrieving Network and Console logs from 20 PCs in near realtime
 - [https://www.reddit.com/r/selfhosted/comments/1hfdq7n/retrieving_network_and_console_logs_from_20_pcs](https://www.reddit.com/r/selfhosted/comments/1hfdq7n/retrieving_network_and_console_logs_from_20_pcs)
 - RSS feed: $source
 - date published: 2024-12-16T07:14:42+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>we have 200 Windows PCs where our staff is using Chrome. Whenever something goes wrong, the vendor is asking for Console and Network logs from Chrome. This takes a lot of effort, plus in many instances, the problem by then is gone. Is there some open source solution that would allow us to &quot;stream&quot; Chrome console and network logs to some central location? </p> <p>I see some are suggesting Graylog <a href="https://www.reddit.com/r/graylog/comments/twa55d/best_log_management_system_solution/">here</a> . We are looking for something open source, and I am unsure if it can get Console and Network logs on its own. Is Graylog the better option for this?</p> <p>I am also wondering if there is a way to do it without installing something on our client PCs? Perhaps something via AD? Or some Chrome setting? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/StarAvenger"> /u/StarAvenger </a> <br/> <span><a 

## I need a self-hosted archive solution
 - [https://www.reddit.com/r/selfhosted/comments/1hfb92m/i_need_a_selfhosted_archive_solution](https://www.reddit.com/r/selfhosted/comments/1hfb92m/i_need_a_selfhosted_archive_solution)
 - RSS feed: $source
 - date published: 2024-12-16T04:34:27+00:00

<!-- SC_OFF --><div class="md"><p>What you guys using mostly?</p> <p>I looked at archive box and it looks like a pain to use, currently using linkwarden but it’s not the best and feels bogged down. Any better alternative? Mostly similar to archive box but better?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/H-encore"> /u/H-encore </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfb92m/i_need_a_selfhosted_archive_solution/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hfb92m/i_need_a_selfhosted_archive_solution/">[comments]</a></span>

## I finally built my own server!
 - [https://www.reddit.com/r/selfhosted/comments/1hf96ot/i_finally_built_my_own_server](https://www.reddit.com/r/selfhosted/comments/1hf96ot/i_finally_built_my_own_server)
 - RSS feed: $source
 - date published: 2024-12-16T02:38:18+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been wanting to build my own server for a few years but never could.</p> <p>My first server was a Plex + Storage simple refurbished mini-PC + DAS</p> <p>MiniPC:<br/> <a href="https://www.amazon.com/gp/product/B08PMSYGKH/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&amp;psc=1">https://www.amazon.com/gp/product/B08PMSYGKH/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&amp;psc=1</a></p> <p>QNAP DAS with 12TB storage: <a href="https://www.amazon.com/gp/product/B07S7XSS6P/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&amp;psc=1">https://www.amazon.com/gp/product/B07S7XSS6P/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&amp;psc=1</a></p> <p>It ran well and fine for a year that I had it, never had any issues with it. I always read all about the weak and flaky USB connection but never had any issues like that.<br/> It&#39;s not like I was moving it around that much.</p> <p>The problem I kept facing was the slow data transfer speeds and the lack of upgradability.<br/> 

## 🚀 Dynamic Notification System: Open Source Notification Scheduler in Go! 🌟 [Looking for Contributors]
 - [https://www.reddit.com/r/selfhosted/comments/1hf91v8/dynamic_notification_system_open_source](https://www.reddit.com/r/selfhosted/comments/1hf91v8/dynamic_notification_system_open_source)
 - RSS feed: $source
 - date published: 2024-12-16T02:31:13+00:00

<!-- SC_OFF --><div class="md"><p>Hi Redditors! 👋</p> <p>I’m excited to share my latest open-source project, <strong>Dynamic Notification System</strong>! 🎉</p> <p>This is a <strong>Go-based extensible notification scheduler</strong> that supports multiple channels, including:</p> <ul> <li>📨 <strong>Slack</strong></li> <li>🔔 <strong>Discord</strong></li> <li>📩 <strong>Telegram</strong></li> <li>📧 <strong>SMTP</strong></li> <li>🖥️ <strong>Webhooks</strong></li> <li>And many more!</li> </ul> <p>With dynamic plugin support, the system allows you to add new notification channels effortlessly. It’s designed for cross-platform compatibility (Linux, macOS, Windows) and supports <strong>Go 1.23+</strong>.</p> <h1>Why Contribute?</h1> <p>✅ Learn and improve your skills in <strong>Go</strong> and dynamic plugin systems.<br/> ✅ Work on cross-platform builds for Linux, macOS, and Windows.<br/> ✅ Be part of a growing open-source project and build your portfolio.<br/> ✅ Help the community by addin

## What should I do if my backup runs out
 - [https://www.reddit.com/r/selfhosted/comments/1hf8r58/what_should_i_do_if_my_backup_runs_out](https://www.reddit.com/r/selfhosted/comments/1hf8r58/what_should_i_do_if_my_backup_runs_out)
 - RSS feed: $source
 - date published: 2024-12-16T02:15:29+00:00

<!-- SC_OFF --><div class="md"><p>As dum as this maybe, I am not rich. For this topic I want to ask if I had a 2TB SSD or HD (doesn&#39;t matter), and I backed my data specifically right now I am using restic which essentially creates snapshots of your data. </p> <p>In any case the reason I had to mention that because if I was not using snapshots then I think it would not matter about my next question.</p> <p>Lets say I fully take up 2TB (currently only at 50gb) but need to think about this. But lets say I take all 2TB some day what would I realistically have to do? Do I then have to buy lets say a 4TB HD and drag and drop everything over to the 2TB storage? </p> <p>My idea would be simply to upload it to the cloud in the mean time and then buy a bigger drive &gt; redownload it back to my drive (4TB) in this case. </p> <p>Please let me know some suggestion...</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Swiss_Meats"> /u/Swiss_Meats </a> <br/>

## Using External Storage & Accessing Them As One Drive
 - [https://www.reddit.com/r/selfhosted/comments/1hf8cdg/using_external_storage_accessing_them_as_one_drive](https://www.reddit.com/r/selfhosted/comments/1hf8cdg/using_external_storage_accessing_them_as_one_drive)
 - RSS feed: $source
 - date published: 2024-12-16T01:54:18+00:00

<!-- SC_OFF --><div class="md"><p>I found a selfhosted program that will do just this. It&#39;s called Alist and can be found at <a href="https://github.com/AlistGo/alist">https://github.com/AlistGo/alist</a>. Yes, I know, external storage options are not &#39;self hosted&#39;, however, having a 20gb (in the case of Mega) dump box is handy to me. </p> <p>Have fun!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Wild_Magician_4508"> /u/Wild_Magician_4508 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hf8cdg/using_external_storage_accessing_them_as_one_drive/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hf8cdg/using_external_storage_accessing_them_as_one_drive/">[comments]</a></span>

## How much more secure can I get ?
 - [https://www.reddit.com/r/selfhosted/comments/1hf6pgd/how_much_more_secure_can_i_get](https://www.reddit.com/r/selfhosted/comments/1hf6pgd/how_much_more_secure_can_i_get)
 - RSS feed: $source
 - date published: 2024-12-16T00:30:50+00:00

<!-- SC_OFF --><div class="md"><p>For context so far I&#39;ve used Tailscale for everyone to have remote access to my Jellyfin instance and Jellyfin only. No ports are open on my network basically. </p> <p>Everything else I host is behind local http and I can only access those things. </p> <p>I have my Jellyfin+Jellyseer instances forwarded through Traefik for https so my friends can access it via https using my domain name. (This could potentially be changed to just use the tailnet address I guess) </p> <p>I have Crowdsec installed on my Jellyfin instance (still not properly setup just yet) </p> <p>Jellyfin + Jellyseer is really the only &quot;public&quot; thing I host. Everything thing else like *arrstack etc are just http only and I can only access. </p> <p>I&#39;m always looking into new things to host and security is probably something that you can never have enough of but, just wondering I guess how much more secure I can make my setup, or if anything more is really needed I gu

