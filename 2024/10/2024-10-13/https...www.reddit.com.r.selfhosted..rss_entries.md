# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## traefik and portainer and other applications afterwards.
 - [https://www.reddit.com/r/selfhosted/comments/1g32xnj/traefik_and_portainer_and_other_applications](https://www.reddit.com/r/selfhosted/comments/1g32xnj/traefik_and_portainer_and_other_applications)
 - RSS feed: $source
 - date published: 2024-10-13T23:38:24+00:00

<!-- SC_OFF --><div class="md"><p>So I followed somewhat of techonoTim&#39;s video on Traefik 3 install. However all this is installed on a VPS in the cloud.</p> <p>I have a DNS configured through cloudflare. I can access my Traefik dashboard perfectly fine. I already had portainer installed prior to Traefik. how do I make it&#39;s dashboard run through traefik and my DNS? I can and have been able to reach my portainer install just fine using the ip address and it works https, but I want it to resolve to the DNS url instead.</p> <p>I&#39;m sorry, I&#39;m so confused on how to add applications for Traefik all the tutorials have traefik installing with portainer or whatever app i&#39;m looking at, but I don&#39;t want an additional install of traefik, seems silly to have that, can&#39;t the one install work for everything?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/randomBullets"> /u/randomBullets </a> <br/> <span><a href="https://www.reddit.c

## Multi user Auth over subdomains in k8s
 - [https://www.reddit.com/r/selfhosted/comments/1g32s8j/multi_user_auth_over_subdomains_in_k8s](https://www.reddit.com/r/selfhosted/comments/1g32s8j/multi_user_auth_over_subdomains_in_k8s)
 - RSS feed: $source
 - date published: 2024-10-13T23:30:40+00:00

<!-- SC_OFF --><div class="md"><p>I have a k8s cluster I&#39;m using to host and learn things around.<br/> Cluster is using cilium as network, accessible from a domain name (lets call it domain.com)<br/> Multiple apps are hosted now (heimdall, immich, siyuan, grafana, etc.) each with an ingress listening at {app}.domain.com<br/> Some apps support multiple users (like immich) while others only have a master password (like siyuan). However I want to have some form of multiple user authentication/authorization to allow\deny access.</p> <p>An easy example is: if a user tries to access any {app}.dom.com they will first be redirected to <a href="http://auth.dom.com">auth.dom.com</a>, be required to login, and based on the user rights they could be allowed to access {app1}.dom.com but not {app2}.dom.com regardless if app1 or app2 support user login or not, so kind of network level access I think?</p> <p>Ideally something that integrates with Azure AD, but it&#39;s fine if it&#39;s a separate

## What are you using for storage?
 - [https://www.reddit.com/r/selfhosted/comments/1g32noh/what_are_you_using_for_storage](https://www.reddit.com/r/selfhosted/comments/1g32noh/what_are_you_using_for_storage)
 - RSS feed: $source
 - date published: 2024-10-13T23:23:58+00:00

<!-- SC_OFF --><div class="md"><p>So my QNAP died this weekend and while I have backups on external drives, I have nothing to run my services from. It had 9 bays 5 3.5” 18tb HDDs and 4 4tb SSDs that my Proxmox nodes connect to over NFS. </p> <p>I would prefer to go with something like TruNas, but am not sure what hardware I should go with. Any tips? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ooo0000ooo"> /u/ooo0000ooo </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g32noh/what_are_you_using_for_storage/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g32noh/what_are_you_using_for_storage/">[comments]</a></span>

## Avoid at Domain.com AT ALL COSTS - Terrible Customer Service, Time Wasted, and Ongoing Domain Transfer Nightmare
 - [https://www.reddit.com/r/selfhosted/comments/1g329a3/avoid_at_domaincom_at_all_costs_terrible_customer](https://www.reddit.com/r/selfhosted/comments/1g329a3/avoid_at_domaincom_at_all_costs_terrible_customer)
 - RSS feed: $source
 - date published: 2024-10-13T23:03:35+00:00

<!-- SC_OFF --><div class="md"><p>I have never encountered such an appalling experience with any service provider as I have with Domain.com. What began as a simple WordPress installation issue has spiraled into a complete disaster. Over the past few weeks, I’ve faced repeated cancellations of services—including my hosting, domain, and Google Workspace—without my authorization. No one from Domain.com has been able to explain how or why this happened, and every attempt to resolve the situation has only made things worse.</p> <p>I initially contacted their support team about a WordPress installation issue, but the situation quickly escalated. My hosting was canceled and refunded without my request, and when I logged in to manage my domain, both my domain and Google Workspace had disappeared from my account. When I followed up with support to find out what happened, they told me my domain had been transferred to Network Solutions—again, without my authorization. After reaching out to Netw

## New and Interested in Starting a Homeserver
 - [https://www.reddit.com/r/selfhosted/comments/1g326t2/new_and_interested_in_starting_a_homeserver](https://www.reddit.com/r/selfhosted/comments/1g326t2/new_and_interested_in_starting_a_homeserver)
 - RSS feed: $source
 - date published: 2024-10-13T23:00:24+00:00

<!-- SC_OFF --><div class="md"><p>I have one extra PC and would like to be able to selfhost the various nextcloud services, an ente photo gallery, webdav for some sync, possibly a website to document my learning and eventually showcase a portfolio, </p> <p>I believe the setup will involve/require:</p> <p>(I&#39;ve been experimenting and watching many, many YouTube videos. So, please excuse any misunderstandings I have about what I may need. I want to learn and improve! :D )</p> <p>1.) Pi-Hole - I will get a separate raspberry pi if necessary. (Is it possible to run this effectively on the same PC as everything else?), </p> <p>2.) nginx reverse proxy - I will have access to port forwarding, so this won&#39;t be a workaround for that. But it seems to be necessary, or a great utility. I admittedly need to take more time to understand nginx. </p> <p>3.) traefik - for local network domains instead of having to use an IP to access any of the various web interfaces, like nextcloud</p> <p>4.)

## Best way to move domain and email from one host to two different hosts
 - [https://www.reddit.com/r/selfhosted/comments/1g31pm9/best_way_to_move_domain_and_email_from_one_host](https://www.reddit.com/r/selfhosted/comments/1g31pm9/best_way_to_move_domain_and_email_from_one_host)
 - RSS feed: $source
 - date published: 2024-10-13T22:35:52+00:00

<!-- SC_OFF --><div class="md"><p>I hope my question fits well in this subreddit. I’m planning to move both my domain and email, which are currently with the same registrar, <a href="http://Gandi.net">Gandi.net</a> (due to their new ownership and regular price hikes without client notification). My plan is to move my domain to Cloudflare (as my DNS records are already on their platform after setting up Zero Trust with my home server) and my email to ProtonMail. However, I’m unsure whether to transfer the email or the domain first.</p> <p>If anyone has tips or recommendations for making this transition as smooth as possible, I’d appreciate it, since this is my main professional email and I want to avoid any issues.</p> <p>Thanks in advance and have a great day!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/wa_00"> /u/wa_00 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g31pm9/best_way_to_move_domain_and_email_from_one_ho

## offline management for multi language ebook library
 - [https://www.reddit.com/r/selfhosted/comments/1g31due/offline_management_for_multi_language_ebook](https://www.reddit.com/r/selfhosted/comments/1g31due/offline_management_for_multi_language_ebook)
 - RSS feed: $source
 - date published: 2024-10-13T22:19:19+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for an ebook management software capable of handling ebooks in various formats such as .epub, .azw, .pdf, and .mobi, and managing content in multiple languages like Russian, English, Arabic, and Japanese. The software should also allow books to be organized into user-defined categories. It is important that the software is web-based and accessible via a web browser. It should automatically add metadata, have no limitations on the amount of data that can be managed, including no character limit for book titles, and offer a search function.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Prudent_Impact7692"> /u/Prudent_Impact7692 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g31due/offline_management_for_multi_language_ebook/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g31due/offline_management_for_multi_language_ebook/">[comments]</a>

## Seeking Docker container to encrypt specific folders
 - [https://www.reddit.com/r/selfhosted/comments/1g30ch9/seeking_docker_container_to_encrypt_specific](https://www.reddit.com/r/selfhosted/comments/1g30ch9/seeking_docker_container_to_encrypt_specific)
 - RSS feed: $source
 - date published: 2024-10-13T21:29:36+00:00

<!-- SC_OFF --><div class="md"><p>Good afternoon</p> <p>I&#39;m looking to see if a container exists out there that could let me encrypt/decrypt some of my personal files on my NAS as needed (preferably with a GUI component).</p> <p>All my search engine inquiries keep turning up information on encrypting docker containers themselves or docker secrets which doesn&#39;t suit my needs.</p> <p>Currently I&#39;m just zipping important folders into password protected archives but I feel I could be doing this more efficiently.</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Testpilot1988"> /u/Testpilot1988 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g30ch9/seeking_docker_container_to_encrypt_specific/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g30ch9/seeking_docker_container_to_encrypt_specific/">[comments]</a></span>

## Need some advise for internal routing to work with external routing
 - [https://www.reddit.com/r/selfhosted/comments/1g306xj/need_some_advise_for_internal_routing_to_work](https://www.reddit.com/r/selfhosted/comments/1g306xj/need_some_advise_for_internal_routing_to_work)
 - RSS feed: $source
 - date published: 2024-10-13T21:22:22+00:00

<!-- SC_OFF --><div class="md"><p>I like many of you, self host a lot of docker containers, some of which are externally available. For my external, everything goes into a cloud VPS that uses Traefik to route the traffic either to the appropriate VPS (for anything I didn&#39;t want to go offline when doing stuff on my server) or my home server through a tailscale VPN. Externally everything works great! </p> <p>Now my issue, if possible and without a lot of with, would like to find the best solution for internal. I have a Ubuiqiti setup and it has some DNS functionality but I think I may need to use a third party docker or on a pi but not sure what solution. Also would I need to setup another reverse proxy for internal traffic only so that I don&#39;t have to remember IP and port? I totally time myself just calling the services externally exposed by the external URL because it&#39;s just easier to remember than trying to use the internal address. </p> <p>I would love to hear what solut

## outlook smtp ended
 - [https://www.reddit.com/r/selfhosted/comments/1g303oy/outlook_smtp_ended](https://www.reddit.com/r/selfhosted/comments/1g303oy/outlook_smtp_ended)
 - RSS feed: $source
 - date published: 2024-10-13T21:18:08+00:00

<!-- SC_OFF --><div class="md"><p>Goodnight,</p> <p>On September 16th, Microsoft ended SMTP on free accounts and only on Office365.</p> <p>It turns out that I have several email alerts/notifications, pfsense, ups, bitwarden, nvr, which stopped working because I was using a hotmail email.</p> <p>Do you know of any email services with SMTP that are free? I&#39;ve tried <a href="http://mail.com">mail.com</a>, yahoo, 126 and they don&#39;t use SMTP anymore.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Little-Ad-2713"> /u/Little-Ad-2713 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g303oy/outlook_smtp_ended/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g303oy/outlook_smtp_ended/">[comments]</a></span>

## Really loved the "Tube Archivist" one (5 obscure self-hosted services worth checking out)
 - [https://www.reddit.com/r/selfhosted/comments/1g2zf5t/really_loved_the_tube_archivist_one_5_obscure](https://www.reddit.com/r/selfhosted/comments/1g2zf5t/really_loved_the_tube_archivist_one_5_obscure)
 - RSS feed: $source
 - date published: 2024-10-13T20:46:50+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g2zf5t/really_loved_the_tube_archivist_one_5_obscure/"> <img src="https://external-preview.redd.it/DofOOT_sRN7svluCHOXuAZ40HrGDtsEi7W9kIKbU9ok.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=1cb3a2ab97a55901f4e909cf363a08dd5b15be3e" alt="Really loved the &quot;Tube Archivist&quot; one (5 obscure self-hosted services worth checking out)" title="Really loved the &quot;Tube Archivist&quot; one (5 obscure self-hosted services worth checking out)" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SuckMyPenisReddit"> /u/SuckMyPenisReddit </a> <br/> <span><a href="https://www.xda-developers.com/obscure-self-hosted-services/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2zf5t/really_loved_the_tube_archivist_one_5_obscure/">[comments]</a></span> </td></tr></table>

## [OC] dockcheck v0.5.0 - Automated (selective) updates of docker containers, some notification rework and new additions lately!
 - [https://www.reddit.com/r/selfhosted/comments/1g2zarg/oc_dockcheck_v050_automated_selective_updates_of](https://www.reddit.com/r/selfhosted/comments/1g2zarg/oc_dockcheck_v050_automated_selective_updates_of)
 - RSS feed: $source
 - date published: 2024-10-13T20:41:06+00:00

<!-- SC_OFF --><div class="md"><p>Greetings folks, I&#39;ve posted before but almost 10 months passed now. Nothing huge happened since then but a bunch of tweaks and additions. </p> <p>10 months ago I had just released the feature of sending notifications on available updates. Many templates have been contributed/suggested and currently these are supported: - Synology <a href="https://www.synology.com/en-global/dsm">DSM</a> - Email with <a href="https://wiki.debian.org/msmtp">mSMTP</a> (or deprecated alternative <a href="https://wiki.debian.org/sSMTP">sSMTP</a>) - Apprise (with it&#39;s <a href="https://github.com/caronc/apprise#supported-notifications">multitude</a> of notifications) - <a href="https://ntfy.sh/">ntfy.sh</a> - HTTP-based pub-sub notifications. - <a href="https://gotify.net/">Gotify</a> - a simple server for sending and receiving messages. - <a href="https://www.pushbullet.com/">Pushbullet</a> - connecting different devices with cross-platform features. - <a href="http

## RAM upgrade help
 - [https://www.reddit.com/r/selfhosted/comments/1g2y9vm/ram_upgrade_help](https://www.reddit.com/r/selfhosted/comments/1g2y9vm/ram_upgrade_help)
 - RSS feed: $source
 - date published: 2024-10-13T19:55:23+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g2y9vm/ram_upgrade_help/"> <img src="https://b.thumbs.redditmedia.com/kv479Kdnl0lL4-DP4GiqIvDMXVFlmIq9NII2EgRJ3bo.jpg" alt="RAM upgrade help" title="RAM upgrade help" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I got a lenovo 910s with an i5 7700t and 8gb ram. I found a listing on a second hand sute and i&#39;m unsure if those sticks would work. I was also unable to find any info from lenovo about the motherboard or matching ram. If they will not work, what should look for in terms of specs?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/WEEDIKONNINJA"> /u/WEEDIKONNINJA </a> <br/> <span><a href="https://www.reddit.com/gallery/1g2y9vm">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2y9vm/ram_upgrade_help/">[comments]</a></span> </td></tr></table>

## Good tunnel for minecraft server
 - [https://www.reddit.com/r/selfhosted/comments/1g2wydj/good_tunnel_for_minecraft_server](https://www.reddit.com/r/selfhosted/comments/1g2wydj/good_tunnel_for_minecraft_server)
 - RSS feed: $source
 - date published: 2024-10-13T18:58:15+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g2wydj/good_tunnel_for_minecraft_server/"> <img src="https://b.thumbs.redditmedia.com/ZItuLT2cewJMzbqN8vC6CEg86y8zfmeC2hqZ-DRW4RQ.jpg" alt="Good tunnel for minecraft server" title="Good tunnel for minecraft server" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I have a main server with a high(er) amount of ram, and a server with a small amount of ram, exposed to the internet. The first one is not exposed. What is a server software that i can use to jump the servers. I have used playit, but i want a alternative, that i have a remote server hosting. server 2 is where the clients connect.</p> <p><a href="https://preview.redd.it/01l26gziokud1.png?width=960&amp;format=png&amp;auto=webp&amp;s=e3b8077c5471e618f0e12ab7f2fe6ec6b3b81a5e">Drawing</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Impossible_Turn_8541"> /u/Impossible_Turn_8541 </a> <br/> <span><a href="https://www

## Which hardware for self hosted cloud for micro-services
 - [https://www.reddit.com/r/selfhosted/comments/1g2wtxm/which_hardware_for_self_hosted_cloud_for](https://www.reddit.com/r/selfhosted/comments/1g2wtxm/which_hardware_for_self_hosted_cloud_for)
 - RSS feed: $source
 - date published: 2024-10-13T18:52:52+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m planning on developing an app that needs to have a shared blob storage (will probably use garage) and a service for authentication with a web service that contains the logic for my app and will access the blob storage. This is just a side project, don&#39;t need a high amount of storage but I want it to be &quot;scalable&quot; and reliable in case I get more traffic over the months/years. I am new to self hosting, already tinkered with own cloud on my raspberry but it was used only by myself. For the hardware, I don&#39;t know what to go for, will a raspberry pi 5 with 8go support a high traffic ? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DalkEvo"> /u/DalkEvo </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2wtxm/which_hardware_for_self_hosted_cloud_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2wtxm/which_hardware_for_self_hoste

## Looking for advice on creating multiple self-hosted email addresses
 - [https://www.reddit.com/r/selfhosted/comments/1g2w4sy/looking_for_advice_on_creating_multiple](https://www.reddit.com/r/selfhosted/comments/1g2w4sy/looking_for_advice_on_creating_multiple)
 - RSS feed: $source
 - date published: 2024-10-13T18:22:10+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I&#39;m looking to set up a bunch of email addresses, mainly for receiving emails (not necessarily for sending). I’d prefer a self-hosted solution but I’m not sure which provider would be the best and most affordable. I&#39;ve looked into options like Hostinger and Hetzner, but I’m still undecided.</p> <p>Any recommendations on the best and cheapest way to go about this? Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jiins5"> /u/jiins5 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2w4sy/looking_for_advice_on_creating_multiple/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2w4sy/looking_for_advice_on_creating_multiple/">[comments]</a></span>

## Looking for NAS setup recommendations
 - [https://www.reddit.com/r/selfhosted/comments/1g2vd5d/looking_for_nas_setup_recommendations](https://www.reddit.com/r/selfhosted/comments/1g2vd5d/looking_for_nas_setup_recommendations)
 - RSS feed: $source
 - date published: 2024-10-13T17:48:09+00:00

<!-- SC_OFF --><div class="md"><p>Self-hosting Noob here. I have storage and PC parts that I have accumulated over the past couple of years after being pissed off at Google for discontinuing unlimited photo storage. So far, I have the following and want to build a family NAS with this wishlist: 1. Photo hosting service 2. File hosting and indexing service, hopefully able to connect to an open LLM mode 3. Local web service</p> <p>I have following parts: 1. Integrated SSD 240gb 2. 2.5&quot; external SSD 256gb 3. 2x 10TB 3.5&quot; HDD 4. 1x 4 TB NAS hard drive</p> <p>I have the motherboard, PSU, RAM, and the rest of the parts required to build a PC (from a used PC I bought that was used for something similar)</p> <p>What operating system and RAID setup would you recommend to build a system with this? I am a bit confused here because I don&#39;t have a symmetrical hardware configuration. So, I am at a loss for what RAID configuration I should use, etc. I also have an older GPU I could sip

## Self Hosting for Family Usage - scope / dead man switch for important docs.
 - [https://www.reddit.com/r/selfhosted/comments/1g2uh66/self_hosting_for_family_usage_scope_dead_man](https://www.reddit.com/r/selfhosted/comments/1g2uh66/self_hosting_for_family_usage_scope_dead_man)
 - RSS feed: $source
 - date published: 2024-10-13T17:09:03+00:00

<!-- SC_OFF --><div class="md"><p>After my recent bitwarden/vaultwarden &quot;what if&quot; moment - </p> <p>I&#39;m re-thinking scope and reasons for self hosting various services.</p> <p>Primarily the three biggest reasons for me are:</p> <ul> <li>cost(financial),</li> <li>privacy.</li> <li>hobby / education / &quot;fun&quot;</li> </ul> <p>I need to have a clear strategy so my family can continue to access data if I&#39;m incapacitated that does not compromise general privacy until that time.</p> <p>Anyone have any thoughts that result in simple non-technical and ideally near seamless &quot;business continuity&quot; for family - mainly cloud storage of important documents and password manager. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ydrol"> /u/ydrol </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2uh66/self_hosting_for_family_usage_scope_dead_man/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r

## Unbound & Adguard caching not working
 - [https://www.reddit.com/r/selfhosted/comments/1g2twkr/unbound_adguard_caching_not_working](https://www.reddit.com/r/selfhosted/comments/1g2twkr/unbound_adguard_caching_not_working)
 - RSS feed: $source
 - date published: 2024-10-13T16:43:45+00:00

<!-- SC_OFF --><div class="md"><p>I have Adguard Home running on my Unraid server. I just added Unbound and think it doesn&#39;t work properly. I do have internet, ad blocking is working and Unbound ip is set as the upstream in Adguard... but I don&#39;t think the querries are caching.</p> <p>The container already created the unbound.conf file, but the a-records, forward-records and srv-records config files were missing. I copy/pasted those <a href="https://github.com/MatthewVance/unbound-docker/tree/master/1.10.1">from here</a>. Do I need to change anything within these files or should they work as is?</p> <p>When starting up Unbound I get <a href="https://www.reddit.com/u/Mike_v_E/s/oy2eKEJfle">the following error logs</a></p> <p>When using dig I get the following:</p> <p>; &lt;&lt;&gt;&gt; DiG 9.16.42 &lt;&lt;&gt;&gt; microsoft.com @192.168.1.58 ;; global options: +cmd ;; connection timed out; no servers could be reached</p> <p>This happens when I use both my Adguard or Unbound ip 

## How to make a home proxy setup?
 - [https://www.reddit.com/r/selfhosted/comments/1g2tq1y/how_to_make_a_home_proxy_setup](https://www.reddit.com/r/selfhosted/comments/1g2tq1y/how_to_make_a_home_proxy_setup)
 - RSS feed: $source
 - date published: 2024-10-13T16:35:52+00:00

<!-- SC_OFF --><div class="md"><p>I want my computer to have zero access to anything on the internet, and only have internet access through a browser using my second computer as a proxy.</p> <p>I&#39;ve seen this once in the past and want to do this now in my setup.</p> <p>I appreciate any help!</p> <p>Keep in mind, i&#39;m not a programmer, but I can understand the basics!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/frappekaikoulouri"> /u/frappekaikoulouri </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2tq1y/how_to_make_a_home_proxy_setup/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2tq1y/how_to_make_a_home_proxy_setup/">[comments]</a></span>

## Minecraft server behind VPS with multiple IPV4's for multiple servers
 - [https://www.reddit.com/r/selfhosted/comments/1g2tlnx/minecraft_server_behind_vps_with_multiple_ipv4s](https://www.reddit.com/r/selfhosted/comments/1g2tlnx/minecraft_server_behind_vps_with_multiple_ipv4s)
 - RSS feed: $source
 - date published: 2024-10-13T16:30:43+00:00

<!-- SC_OFF --><div class="md"><p>Currently I have a VPS through OVHcloud that my current minecraft server runs through. This is just for me and some friends. The reason I do it like this is because I have starlink, so I have CGNAT. I got it all working by using tailscale to connect my Ubuntu VM running Pelican Panel that hosts my server to the Ubuntu VPS I have rented out. It currently only has one IPV4. I&#39;d like to run a modded forge server as well using 25565 so people don&#39;t have to type in a port. I can order as many IPV4&#39;s as I&#39;d like. It used NGINX proxy manager as well. I&#39;ve never had to setup a server with multiple IPs like this before, so if I order another IP, I&#39;m not quite sure where I&#39;d start with configuring it to keep them seperated. I want both servers to run at the same time. The link below is how I have NGINX setup in another post I made before. Any idea how I&#39;d configure NGINX to use one of the 2 IPs for one server, then use the other 

## Anyone use MusicBrainz-Picard?
 - [https://www.reddit.com/r/selfhosted/comments/1g2the6/anyone_use_musicbrainzpicard](https://www.reddit.com/r/selfhosted/comments/1g2the6/anyone_use_musicbrainzpicard)
 - RSS feed: $source
 - date published: 2024-10-13T16:25:35+00:00

<!-- SC_OFF --><div class="md"><p>So I have a music collection that I have toted around for about 20yrs. I&#39;ve never organized it very well and now I have tons of album directories that have half an album and then another one with the other half. Lots of duplicate tracks and so on. A total of ~5300 albums. </p> <p>I spun up <a href="https://hub.docker.com/r/mikenye/picard">Picard</a> in a docker and am attempting to use this to clean this up but after following a couple guides the test albums I (think at least) saved them back to the cluster area. BUT now the files are simply gone... I&#39;m v confused. </p> <p>Any thorough guides that y&#39;all have used? Any other tools I should be looking at to fix my folder structures?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/airclay"> /u/airclay </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2the6/anyone_use_musicbrainzpicard/">[link]</a></span> &#32; <span><a href="https:

## Unbound - disabling prefetch for domain forward zone (override)?
 - [https://www.reddit.com/r/selfhosted/comments/1g2t3zx/unbound_disabling_prefetch_for_domain_forward](https://www.reddit.com/r/selfhosted/comments/1g2t3zx/unbound_disabling_prefetch_for_domain_forward)
 - RSS feed: $source
 - date published: 2024-10-13T16:09:13+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>Simple question that I cannot ascertain reading the unbound docs -</p> <p>If I have</p> <p><code>prefetch: yes</code></p> <p>in my <code>/var/unbound/unbound.conf</code></p> <p>Can I then add <code>prefetch: no</code></p> <p>Scoped to a specific forward zone, like below:</p> <pre><code>forward-zone: name: &quot;internal&quot; forward-addr: 192.168.5.10 prefetch: no </code></pre> <p>Or is this configuration not currently supported?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kingofbutter69"> /u/kingofbutter69 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2t3zx/unbound_disabling_prefetch_for_domain_forward/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2t3zx/unbound_disabling_prefetch_for_domain_forward/">[comments]</a></span>

## Keycloak alternatives with good NodeJS libs?
 - [https://www.reddit.com/r/selfhosted/comments/1g2rvf3/keycloak_alternatives_with_good_nodejs_libs](https://www.reddit.com/r/selfhosted/comments/1g2rvf3/keycloak_alternatives_with_good_nodejs_libs)
 - RSS feed: $source
 - date published: 2024-10-13T15:14:17+00:00

<!-- SC_OFF --><div class="md"><p>Getting really pissed and annoyed at Keycloak.</p> <h2>Things I like</h2> <ul> <li>only dependency is PG.</li> </ul> <h2>Things annoying me:</h2> <ul> <li>stupid defaults: Access token lifetime 1 minute?? This royally bit me recently when trying to integrate with a lib that did automatic token refresh.</li> <li><a href="https://www.keycloak.org/2023/03/adapter-deprecation-update.html">They depreciated the NodeJS adapter, said they will offer an alternative but still haven&#39;t</a>.</li> <li>Confusing nomenclature. When you create a client there is a big checkbox &quot;allow authentication&quot;. What the fuck does that even mean in the context of OIDC/OAuth2. If its OFF, you can STILL AUTHENTICATE. Its just a public client without a secret. That verbiage makes no sense to someone who knows the spec very well. </li> </ul> <p>I have heard of:</p> <ul> <li>authentik - 4 containers... yuck</li> <li>zitadel</li> <li>Authelia</li> </ul> <p>One main thing I

## Unbound + Adguard questions
 - [https://www.reddit.com/r/selfhosted/comments/1g2rrp2/unbound_adguard_questions](https://www.reddit.com/r/selfhosted/comments/1g2rrp2/unbound_adguard_questions)
 - RSS feed: $source
 - date published: 2024-10-13T15:09:33+00:00

<!-- SC_OFF --><div class="md"><p>I have Adguard Home running on my Unraid server. I just added Unbound and think I got it to work, but I have a couple of questions:</p> <ul> <li><p>The container already created the unbound.conf file, but the a-records, forward-records and srv-records config files were missing. I copy/pasted those <a href="https://github.com/MatthewVance/unbound-docker/tree/master/1.10.1">from here</a>. Do I need to change anything within these files or should they work as is?</p></li> <li><p>Adguard runs on 192.168.1.55 and Unbound runs on 192.168.1.58. The Unbound container ports are 53 but the host ports are 5335. In Adguard I can only use 192.168.1.58:53 as upstream dns server, and not 192.168.1.58:5335. Is this how it is supposed to be? I thought I had to use :5335...</p></li> <li><p>On dnsleaktest.com I still see Cloudflare underneath ISP. Should that still be visible? I thought that wouldn&#39;t be the case anymore with Unbound. I assume it is still using a tls

## Looking for Smtp provider
 - [https://www.reddit.com/r/selfhosted/comments/1g2qte2/looking_for_smtp_provider](https://www.reddit.com/r/selfhosted/comments/1g2qte2/looking_for_smtp_provider)
 - RSS feed: $source
 - date published: 2024-10-13T14:25:36+00:00

<!-- SC_OFF --><div class="md"><p>What SMTP provider do you recommend for secure and reliable notifications?</p> <p>I’m looking for an SMTP provider to handle notifications from my Synology NAS, Vaultwarden (for email notifications), and possibly other services in the future. Security is a priority, so I’d like a provider with strong encryption and privacy policies. (If available)</p> <p>Reliability of email delivery is also important, ideally a provider with a good reputation, where their IPs aren’t frequently flagged as spam. Any recommendations on pricing, ease of setup, and medium- to long-term use?</p> <p>Bonus if i can start with a free plan. 😌</p> <p>Thanks</p> <p>Edit: vaultwarden will be used my friends and family and I understand i need smtp for emails etc</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ThisIsAThrowAway926"> /u/ThisIsAThrowAway926 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2qte2/looking_for

## Rate my setup - again
 - [https://www.reddit.com/r/selfhosted/comments/1g2qraw/rate_my_setup_again](https://www.reddit.com/r/selfhosted/comments/1g2qraw/rate_my_setup_again)
 - RSS feed: $source
 - date published: 2024-10-13T14:22:56+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g2qraw/rate_my_setup_again/"> <img src="https://preview.redd.it/kdiqigxb9jud1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=579f847ff61bfacfb7e27d75d1d43e3e3713caa6" alt="Rate my setup - again" title="Rate my setup - again" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jersey_illuminati"> /u/jersey_illuminati </a> <br/> <span><a href="https://i.redd.it/kdiqigxb9jud1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2qraw/rate_my_setup_again/">[comments]</a></span> </td></tr></table>

## Videoconferencing system for ederly parents
 - [https://www.reddit.com/r/selfhosted/comments/1g2q6tf/videoconferencing_system_for_ederly_parents](https://www.reddit.com/r/selfhosted/comments/1g2q6tf/videoconferencing_system_for_ederly_parents)
 - RSS feed: $source
 - date published: 2024-10-13T13:56:30+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’d like to set up a videoconferencing system at my parents&#39; house. I travel a lot, and I&#39;d like to not only talk to them over the phone, but also allow them to see me. They are elderly and have no knowledge of technology, so I would need to remotely control all elements of the system. Ideally, my image would be displayed on their TV, and there shouldn’t be any devices cluttering the living room (like a microphone). They usually sit about 2.5 meters from the TV.</p> <p>From my end, I can use any technology, but I would need to be able to make the video call from either my computer (a Mac) or my mobile phone (an Android). My parents have a good internet connection, but they can only switch the TV to HDMI1 since, as I mentioned, they are not very tech-savvy. I have some ideas, like setting up a PC on their TV, but I’d love to hear suggestions on the best software and hardware for this setup.</p> <p>Thank you so much, any help

## A lot of people have been showing off their grafana dashboard so here's the one I made in quarantine
 - [https://www.reddit.com/r/selfhosted/comments/1g2pj9s/a_lot_of_people_have_been_showing_off_their](https://www.reddit.com/r/selfhosted/comments/1g2pj9s/a_lot_of_people_have_been_showing_off_their)
 - RSS feed: $source
 - date published: 2024-10-13T13:21:55+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g2pj9s/a_lot_of_people_have_been_showing_off_their/"> <img src="https://preview.redd.it/nmpphi8alet41.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=220c7f06e05d609a0dcabe25a5b3778be49a332b" alt="A lot of people have been showing off their grafana dashboard so here's the one I made in quarantine" title="A lot of people have been showing off their grafana dashboard so here's the one I made in quarantine" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cloovesscrand"> /u/cloovesscrand </a> <br/> <span><a href="https://i.redd.it/nmpphi8alet41.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2pj9s/a_lot_of_people_have_been_showing_off_their/">[comments]</a></span> </td></tr></table>

## Regularly sync Google Photos & self-hosted photos solution?
 - [https://www.reddit.com/r/selfhosted/comments/1g2p262/regularly_sync_google_photos_selfhosted_photos](https://www.reddit.com/r/selfhosted/comments/1g2p262/regularly_sync_google_photos_selfhosted_photos)
 - RSS feed: $source
 - date published: 2024-10-13T12:57:10+00:00

<!-- SC_OFF --><div class="md"><p>While I do eventually want to get to a fully self-hosted solution, there&#39;s variety of reasons I can&#39;t give up on Google Photos just yet -- convenience, lack of features, easy sharing with friends, but most importantly lack of trust in my own self-hosting skill-set &amp; not having setup a 321 backup.</p> <p>I do have [Nextcloud AIO](<a href="https://github.com/nextcloud/all-in-one">https://github.com/nextcloud/all-in-one</a>) + [Memories](<a href="https://apps.nextcloud.com/apps/memories">https://apps.nextcloud.com/apps/memories</a>) along with autosync set up at home and everything is stable &amp; works well. It does lack some convenience features but they&#39;re manageable. </p> <p>More importantly I&#39;ve this habit of taking too many photos in trips, and then deleting more than half based on expressions, angles etc. But due to this parallel Nextcloud and Google Photos set up, my phone auto-syncs with both services separately. And when I c

## Should I set up a VPN for my Linux server?
 - [https://www.reddit.com/r/selfhosted/comments/1g2oov8/should_i_set_up_a_vpn_for_my_linux_server](https://www.reddit.com/r/selfhosted/comments/1g2oov8/should_i_set_up_a_vpn_for_my_linux_server)
 - RSS feed: $source
 - date published: 2024-10-13T12:36:52+00:00

<!-- SC_OFF --><div class="md"><p>Not sure if my understanding is correct. </p> <p>I have asked ChatGPT a bunch questions and it recommended to have a VPN for my server.</p> <p>I do have a commercial VPN for my typical desktop and phone. So I’m thinking to also install that in my Linux, but not sure if it makes senses and can be done. My needs and set-up are listed below.</p> <p>My server purpose (and sure I will need to access these services from external network)<br/> -data access: Syncthing obsidian vault<br/> -data access: family Memos, Wekan<br/> -data access: cloud storage<br/> -Fediverse: mastodon or misskey<br/> -Fediverse: writefreely<br/> -Fediverse: pixelfed<br/> -potential: vpn host for my desktop and phone form time to time</p> <p>Security set-up (proposal)<br/> -NAT (tailscale or cloudflare tunnel)<br/> -Nginx reverse proxy (not sure if this would work together with NAT?)<br/> -typical UFW firewall and fail2ban<br/> -VPN for my server??</p> <p>My specific questions<br/> 

## Docker Swarm stacks and 'DevOps' approach
 - [https://www.reddit.com/r/selfhosted/comments/1g2ok3g/docker_swarm_stacks_and_devops_approach](https://www.reddit.com/r/selfhosted/comments/1g2ok3g/docker_swarm_stacks_and_devops_approach)
 - RSS feed: $source
 - date published: 2024-10-13T12:29:20+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m in the process of rebuilding my Docker Swarm cluster. In the current one, I ssh to one of the nodes and have a clone of my config git repo on the machine itself, and then up each docker stack there from the interactive shell. It&#39;s clunky. </p> <p>I want something a bit more DevOps (not a fan of the term, but here we are) this time around: as I&#39;ve done all the server configuration via Ansible. All the compose files will be stored in my git repo. I use Mend Renovate to notify me when there are updated image tags, and will be using diun or watchtower to notify when there are updated images. </p> <p>Thoughts I&#39;ve had are: - Portainer - using the git integration - GitHub Actions - deploy the agent across the cluster and have an action workflow file for each stack so I can deploy on demand with the click of a button in GitHub - ansible module &#39;community.docker.docker_stack&#39; - keep it all in ansible and update the stacks with Ansi

## I made a S3 Drag & Drop Uploader with all the details and guide to securely use S3 buckets. Drop your ideas to what I can add more to make it better!
 - [https://www.reddit.com/r/selfhosted/comments/1g2o9qc/i_made_a_s3_drag_drop_uploader_with_all_the](https://www.reddit.com/r/selfhosted/comments/1g2o9qc/i_made_a_s3_drag_drop_uploader_with_all_the)
 - RSS feed: $source
 - date published: 2024-10-13T12:12:40+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! I built S3oosh a couple of months ago, a sleek drag-and-drop uploader for S3 Buckets<br/> Core Features:</p> <ul> <li>Drag-and-drop file uploads to S3 (super easy!).</li> <li>Real-time progress tracking. 📊</li> <li>Full support for images, PDFs, videos, audio, and more! 🎥🎵</li> <li>Customisable limits for file size, type, and count.</li> <li>And of course, seamless error handling + cancel option!</li> </ul> <p>Security built in: Presigned URLs, S3 Bucket policies, and IAM controls. You’re covered.</p> <p>All the details on how to set up correctly is in github repo description.</p> <p>Looking for some serious suggestions here. What killer features would you love to see in a tool like this?Maybe:</p> <p>Making it as a File Manager to integrate with backends like <a href="http://convex.dev">convex.dev</a> and supabase would help?</p> <p>Mainly why i did this was for a personal project and as i myself had a hard time looking around for corre

## Book Recommendations
 - [https://www.reddit.com/r/selfhosted/comments/1g2o1qi/book_recommendations](https://www.reddit.com/r/selfhosted/comments/1g2o1qi/book_recommendations)
 - RSS feed: $source
 - date published: 2024-10-13T11:59:19+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>can anyone recommend a good book or tutorial that explains server management? The goal is to learn how to run a remote dedicated server with Docker and a reverse proxy. The usual things like mail server, media server etc. but also game servers for Satisfactory or Minecraft should be hosted in Docker or something similar and can be reached via a reverse proxy over a domain. Preferably something that is not too complicated and explained step by step, because I am a very impatient teacher and the different time zones don&#39;t make it any easier.</p> <p>Many thanks in advance</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LargeLettuce2606"> /u/LargeLettuce2606 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2o1qi/book_recommendations/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2o1qi/book_recommendations/">[comments]</a></span>

## I am looking for free tools or a combination of tools that would allow me to create 3D characters
 - [https://www.reddit.com/r/selfhosted/comments/1g2nor1/i_am_looking_for_free_tools_or_a_combination_of](https://www.reddit.com/r/selfhosted/comments/1g2nor1/i_am_looking_for_free_tools_or_a_combination_of)
 - RSS feed: $source
 - date published: 2024-10-13T11:36:22+00:00

<!-- SC_OFF --><div class="md"><p>I have been searching for some time for a way that would enable me to create 3D characters that I can work with in Blender. It doesn&#39;t have to be perfect but should give me a base for 3D human characters, including clothes.</p> <p>Do you know of a way or a combination of tools that would allow me to do such a thing? No need for animation, just the character.</p> <p>Thank you very much.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/umen"> /u/umen </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2nor1/i_am_looking_for_free_tools_or_a_combination_of/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2nor1/i_am_looking_for_free_tools_or_a_combination_of/">[comments]</a></span>

## iPhone to NAS (0-click)
 - [https://www.reddit.com/r/selfhosted/comments/1g2noni/iphone_to_nas_0click](https://www.reddit.com/r/selfhosted/comments/1g2noni/iphone_to_nas_0click)
 - RSS feed: $source
 - date published: 2024-10-13T11:36:11+00:00

<!-- SC_OFF --><div class="md"><p>Hi all. My wife has an iPhone and has literally 25000 pics on it. Instead of paying for Apple iCloud storage, what can I use to have the photos automatically backup to my NAS? Here&#39;s the caveat, she is bad with tech so what I don&#39;t want is something where she has to initiate the transfer every time she adds new pictures. Is there anything like this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/uncmnsense"> /u/uncmnsense </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2noni/iphone_to_nas_0click/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2noni/iphone_to_nas_0click/">[comments]</a></span>

## Invoice - Payments tracking
 - [https://www.reddit.com/r/selfhosted/comments/1g2lmm5/invoice_payments_tracking](https://www.reddit.com/r/selfhosted/comments/1g2lmm5/invoice_payments_tracking)
 - RSS feed: $source
 - date published: 2024-10-13T09:07:22+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a self hosted solution to keep track of what I charge my clients and how much they owe me.</p> <p>I already have an external invoicing system, so my main requirement is the tracking of charges and payments. I have tested some invoicing software (like InvoiceNinja and Dolibarr) but I don&#39;t like that they are so Invoice centered.</p> <p>My main complaint is around the payments. I have to go to a specific invoice and change it to &quot;Payed&quot;. If the client payed for 2-3 invoices I have to manual go and select each one and set it to payed. Even worse when they pay an amount that it doesn&#39;t corresponds to the exact amount of the invoices, some times they underpay and some times (rarely) they overpay for next invoices.</p> <p>For all these I have to manually go and select the invoices that I want to have as payed/or calculate the amount left for the invoice.</p> <p>Spreadsheets is the easy solution, to track a very small numbe

## need help searching for free http domain/subdomain sites (not afraid.org)
 - [https://www.reddit.com/r/selfhosted/comments/1g2lkh8/need_help_searching_for_free_http_domainsubdomain](https://www.reddit.com/r/selfhosted/comments/1g2lkh8/need_help_searching_for_free_http_domainsubdomain)
 - RSS feed: $source
 - date published: 2024-10-13T09:02:43+00:00

<!-- SC_OFF --><div class="md"><p>hey guys, i&#39;m making an mc ripoff for my ipod touch 2g, it&#39;s on iOS 3.1.3 and since i dont have a mac to use xcode, i can only use html sites. i&#39;ve compiled a scratch project with mobile features like: a single button, and more. even with certificates and with custom proxies, safari is unable to open https sites, so i need a little bit of help searching for a free alternative to <a href="http://afraid.org">afraid.org</a>, mostly because i&#39;m a minor in argentina. i can&#39;t afford anything that is a one-time purchase. thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AmadeoOOFDeReddit"> /u/AmadeoOOFDeReddit </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2lkh8/need_help_searching_for_free_http_domainsubdomain/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2lkh8/need_help_searching_for_free_http_domainsubdomain/">[co

## Thoughts on alternatives to Oracle's Dyn service?
 - [https://www.reddit.com/r/selfhosted/comments/1g2lht6/thoughts_on_alternatives_to_oracles_dyn_service](https://www.reddit.com/r/selfhosted/comments/1g2lht6/thoughts_on_alternatives_to_oracles_dyn_service)
 - RSS feed: $source
 - date published: 2024-10-13T08:57:26+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve long been using Oracle&#39;s Dyn service and back to the times when it was free. It is a little expensive now for something which was previously free and I&#39;m aware of there being alternatives out there which are fraction of the cost, or even free. </p> <p>Can anyone recommend an alternative? My use case is for bunch of servers in cloud and where their IP addresses don&#39;t tend to change either. I do it as it is far easier to manage with hostname than IP and if it did happen to be changed for any reason, I could go update the IP. </p> <p>I have seen DynU and that appears to have a Free Tier and up to a point. Can anyone recommend them for the DDNS service?</p> <p>I have a lot of PiVPN instances to update if I do happen to move over, NAS as well. I see that many devices support Dyn out of the box but unsure on these. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/phoenix_73"> /u/phoenix_73 </a> <br

## Rate my setup
 - [https://www.reddit.com/r/selfhosted/comments/1g2lgm8/rate_my_setup](https://www.reddit.com/r/selfhosted/comments/1g2lgm8/rate_my_setup)
 - RSS feed: $source
 - date published: 2024-10-13T08:54:51+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g2lgm8/rate_my_setup/"> <img src="https://a.thumbs.redditmedia.com/2KB4u0OEB4M3LRP_h6Cla9tl8ibpJY1GlrszQHiOW58.jpg" alt="Rate my setup" title="Rate my setup" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jersey_illuminati"> /u/jersey_illuminati </a> <br/> <span><a href="https://www.reddit.com/gallery/1g2lgm8">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2lgm8/rate_my_setup/">[comments]</a></span> </td></tr></table>

## How to benchmark my self hosted supabase?
 - [https://www.reddit.com/r/selfhosted/comments/1g2lbcy/how_to_benchmark_my_self_hosted_supabase](https://www.reddit.com/r/selfhosted/comments/1g2lbcy/how_to_benchmark_my_self_hosted_supabase)
 - RSS feed: $source
 - date published: 2024-10-13T08:43:18+00:00

<!-- SC_OFF --><div class="md"><p>I want to test how much insert / update can my server handle per seconds. I want to create exam / something like Google form / moodle where users answer and time left get recorded server side. I am thinking about 100k rows per seconds. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/yokowasis2"> /u/yokowasis2 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2lbcy/how_to_benchmark_my_self_hosted_supabase/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2lbcy/how_to_benchmark_my_self_hosted_supabase/">[comments]</a></span>

## Hyperthreading Issue on Home Server
 - [https://www.reddit.com/r/selfhosted/comments/1g2l3xq/hyperthreading_issue_on_home_server](https://www.reddit.com/r/selfhosted/comments/1g2l3xq/hyperthreading_issue_on_home_server)
 - RSS feed: $source
 - date published: 2024-10-13T08:27:27+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g2l3xq/hyperthreading_issue_on_home_server/"> <img src="https://b.thumbs.redditmedia.com/8pDvuiUuqBd9iZnHgiL6k3Hs7XhxCJuy5hTy750DMYs.jpg" alt="Hyperthreading Issue on Home Server" title="Hyperthreading Issue on Home Server" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi team, I&#39;m just wondering if anyone would have a clue what is going on. Basically, I&#39;ve built a dual CPU home server. I&#39;m really happy with the performance, however only when hyperthreading is disabled. When I enable hyperthreading to make full use of my 72 logical processors, the server is so laggy and barely usable when under load (I run a bunch of Android Emulators - LDPlayer to be specific). I really would prefer to be able to use my server with HT enabled as my CPU usage drops right down to 19%-25% when HT is enabled, without HT enabled my CPU sits at around 80%.</p> <p>Could anyone shed some light on what I could attempt to

## What's the best VPN for everyday use?
 - [https://www.reddit.com/r/selfhosted/comments/1g2l2ws/whats_the_best_vpn_for_everyday_use](https://www.reddit.com/r/selfhosted/comments/1g2l2ws/whats_the_best_vpn_for_everyday_use)
 - RSS feed: $source
 - date published: 2024-10-13T08:25:31+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a reliable VPN for daily use. It should be secure, easy to use, and offer good speed. Any recommendations?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Lottie_Fearn"> /u/Lottie_Fearn </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2l2ws/whats_the_best_vpn_for_everyday_use/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2l2ws/whats_the_best_vpn_for_everyday_use/">[comments]</a></span>

## Any music servers AND players with WebUI with ability to sync certain songs and playlists to device storage (iOS) for offline play?
 - [https://www.reddit.com/r/selfhosted/comments/1g2ko90/any_music_servers_and_players_with_webui_with](https://www.reddit.com/r/selfhosted/comments/1g2ko90/any_music_servers_and_players_with_webui_with)
 - RSS feed: $source
 - date published: 2024-10-13T07:54:37+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for Spotify-style self-hosted music server with web UI player that allows to sync certain songs and playlists to device storage (iOS) for offline playback for when I am on airplane, subway, or inside a building with no reception and wifi.</p> <p>So, I guess it would either have to have its own iOS client or be compatible with a 3rd party client that can sync said server via some sort of open API).</p> <p>Does anything like that exist?</p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/QuirkyPanda007"> /u/QuirkyPanda007 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2ko90/any_music_servers_and_players_with_webui_with/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2ko90/any_music_servers_and_players_with_webui_with/">[comments]</a></span>

## Opensource personal knowledge base
 - [https://www.reddit.com/r/selfhosted/comments/1g2knwh/opensource_personal_knowledge_base](https://www.reddit.com/r/selfhosted/comments/1g2knwh/opensource_personal_knowledge_base)
 - RSS feed: $source
 - date published: 2024-10-13T07:53:51+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a way to generate and maintain a personal knowledge base similar to these websites. </p> <p>Ideally, I want to directly edit the view shown on the websites without too much coding. </p> <p><a href="https://docusaurus.io/docs">https://docusaurus.io/docs</a><br/> <a href="https://joplinapp.org/help/">https://joplinapp.org/help/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Miyakuzi-K"> /u/Miyakuzi-K </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2knwh/opensource_personal_knowledge_base/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2knwh/opensource_personal_knowledge_base/">[comments]</a></span>

## Gui for docker
 - [https://www.reddit.com/r/selfhosted/comments/1g2k7ly/gui_for_docker](https://www.reddit.com/r/selfhosted/comments/1g2k7ly/gui_for_docker)
 - RSS feed: $source
 - date published: 2024-10-13T07:20:09+00:00

<!-- SC_OFF --><div class="md"><p>I want to do more stuff in docker, but I think I&#39;m still at the stage where gui help will be good.</p> <p>My intention is to setup a decent hw instance and host all docker instances there, including using docker network to host them acting as their own different subnet.</p> <p>So far I have no idea if I should be looking at docker desktop, podman, portainer, yacht, something I haven&#39;t come across yet. I&#39;m a tiny bit useful in Linux but extremely rusty.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mr_Evil_Sir"> /u/Mr_Evil_Sir </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2k7ly/gui_for_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2k7ly/gui_for_docker/">[comments]</a></span>

## NAS System Build
 - [https://www.reddit.com/r/selfhosted/comments/1g2jnwh/nas_system_build](https://www.reddit.com/r/selfhosted/comments/1g2jnwh/nas_system_build)
 - RSS feed: $source
 - date published: 2024-10-13T06:38:58+00:00

<!-- SC_OFF --><div class="md"><p>Hello Team! I am new to the idea of a NAS and thought maybe you all could help. I have looked at the obvious (syntology) and thought that I could probably build one of those myself, but don&#39;t know where to start. I am merely hoping to back up video files from my computer to start some redundancy, then pull them back to my computer if I ever need to use them. It looks like it would be much cheaper, but does anybody know a good place to find a list of parts for something like this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dirtbag9"> /u/Dirtbag9 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2jnwh/nas_system_build/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2jnwh/nas_system_build/">[comments]</a></span>

## Ethical and transparent thread about Public API / SSO features
 - [https://www.reddit.com/r/selfhosted/comments/1g2jb9r/ethical_and_transparent_thread_about_public_api](https://www.reddit.com/r/selfhosted/comments/1g2jb9r/ethical_and_transparent_thread_about_public_api)
 - RSS feed: $source
 - date published: 2024-10-13T06:12:20+00:00

<!-- SC_OFF --><div class="md"><p>I am the owner of <a href="https://postiz.com">Postiz</a>, an open-source social media scheduling tool (not a half-baked software but a fully featured one that, compared to all the big players)</p> <p>I want to build Postiz to bring people as much value as possible.</p> <p>So far: <strong>6.44k downloads for the docker</strong> 🤯</p> <p>Pretty insane.</p> <p>Postiz is a self-funded social media scheduling tool and my <strong>main job</strong> (currently generating $388 per month from the hosted cloud.)</p> <p>Of course, this is not enough money to run a sustainable business that allows me to maintain and work on it 24/7.</p> <p>I have invested more than $10k until today (for the dashboard design and main website design)</p> <p>I was approached by some companies for support and social features like the Public API and SSO.</p> <p>That&#39;s a good place for monetization and a feature many self-hosters want.</p> <p>So many people asked it in <a href="htt

## Specific All-In-One Backup Solution?
 - [https://www.reddit.com/r/selfhosted/comments/1g2icbt/specific_allinone_backup_solution](https://www.reddit.com/r/selfhosted/comments/1g2icbt/specific_allinone_backup_solution)
 - RSS feed: $source
 - date published: 2024-10-13T05:03:26+00:00

<!-- SC_OFF --><div class="md"><p>Hey all.</p> <p>The server OS is Unraid.</p> <p>I&#39;ve been running around the web for the last few hours trying to find a solution for my needs, and so far I don&#39;t think I&#39;ve seen anything that will do exactly what I&#39;m hoping to do.</p> <p>Here is what I&#39;m hoping to find, a backup solution that can do the following:</p> <ol> <li>Image physical machines</li> <li>Back up files from physical machines</li> <li>Compress said images and file backups</li> <li>Back up SQL databases on the host machine, and remote machines (Mainly Postgresql and MariaDB running in docker containers)</li> <li>Back up docker container app data folders on the host machine, and remote machines</li> <li>Have a web-UI</li> <li>Have clients for the physical machines</li> <li>Back up VM&#39;s (image and files)</li> </ol> <p>I am currently using UrBackup for personal use, but I would like something to do all the above. Unless I&#39;m misreading the docs for UrBackup,

## Need help with Cloudflare Tunnel on Linux (Kubuntu) - Bad Gateway Error (502)
 - [https://www.reddit.com/r/selfhosted/comments/1g2hy5u/need_help_with_cloudflare_tunnel_on_linux_kubuntu](https://www.reddit.com/r/selfhosted/comments/1g2hy5u/need_help_with_cloudflare_tunnel_on_linux_kubuntu)
 - RSS feed: $source
 - date published: 2024-10-13T04:37:53+00:00

<!-- SC_OFF --><div class="md"><p>I’m running Kubuntu and hosting Ollama and Open WebUI on Docker. I want to access the web interfaces of these GUIs from outside my network, and instead of going the port forwarding route, I figured I’d set up Cloudflare Tunnel.</p> <p>I set up the tunnel via Docker, and everything seems to be in place (I have a subdomain and all), but I keep getting a “host error” (502 Bad Gateway). This is the same issue I run into even when trying to set up Cloudflare Tunnel for other servers I’m hosting.</p> <p>The thing is, I had all of this working just fine when I was on Windows, so I’m running into this for the first time since switching to Linux. I’m wondering if there are some specific tweaks or configurations I need to do differently on Linux to get these servers working through Cloudflare Tunnel?</p> <p>Would really appreciate any advice or pointers on this! Thanks in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com

## Is My API-Based IP Whitelisting Approach Secure Enough for External Access?
 - [https://www.reddit.com/r/selfhosted/comments/1g2ht5c/is_my_apibased_ip_whitelisting_approach_secure](https://www.reddit.com/r/selfhosted/comments/1g2ht5c/is_my_apibased_ip_whitelisting_approach_secure)
 - RSS feed: $source
 - date published: 2024-10-13T04:28:49+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, </p> <p>I’m seeking advice specifically on whether the API-based IP whitelisting I’ve implemented through Nginx is a reasonable solution to secure my home lab and self-hosted services. I’m not a high-profile individual, but I want to ensure my setup offers a good balance between security and convenience.</p> <p>My goal is to allow easy access for trusted users (including myself) while blocking unauthorized access. I prefer not to use a VPN for remote access due to compatibility issues with some devices, so this IP whitelisting method seemed like a viable alternative.</p> <hr/> <h3>API-Based IP Whitelisting Details</h3> <ul> <li><p><strong>Access Control Mechanism:</strong> </p> <ul> <li>By default, <strong>Nginx is configured with <code>deny all</code></strong> to block all external IPs.</li> <li>Authorized users (like myself) can <strong>whitelist their IP temporarily</strong> using a simple API:<br/> <code>https://whitelist.domain.com/?

## Can't access my site, or generate a cert using letsencrypt
 - [https://www.reddit.com/r/selfhosted/comments/1g2hrxi/cant_access_my_site_or_generate_a_cert_using](https://www.reddit.com/r/selfhosted/comments/1g2hrxi/cant_access_my_site_or_generate_a_cert_using)
 - RSS feed: $source
 - date published: 2024-10-13T04:26:29+00:00

<!-- SC_OFF --><div class="md"><p>I host a small apache server using ubuntu server latest version. when my SSL cert came up to renew, it killed my site completely as it kept going to the site using Https. i tried searching google to no avail. so I had nothing to lose so I reinstalled the whole ubuntu and set everything up as far as apache. if i type <a href="http://site.com">site.com</a> or use http:// it iwll redirect to https. if i use <a href="http://www.site.com">www.site.com</a> it&#39;ll work just fine. i went and installed certbot/letsencrypt but it fails to get a cert and i am assuming when it trys to go to <a href="http://site.com">http://site.com</a> it gets redirected to https:// and fails. i have nothing set in any of the config files to make it use https. site works fine using www when tested on my phone. Not sure what to do here. any ideas?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/fizd0g"> /u/fizd0g </a> <br/> <span><a href="

## Roast/Assist my homelab
 - [https://www.reddit.com/r/selfhosted/comments/1g2hk51/roastassist_my_homelab](https://www.reddit.com/r/selfhosted/comments/1g2hk51/roastassist_my_homelab)
 - RSS feed: $source
 - date published: 2024-10-13T04:12:19+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g2hk51/roastassist_my_homelab/"> <img src="https://b.thumbs.redditmedia.com/LIK_RGKnZ88ai6QY6DgtTxPsCp9Lne-8ZqcZ4w8GD3k.jpg" alt="Roast/Assist my homelab" title="Roast/Assist my homelab" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>After 2 years of messing around with self hosting, I ended up in this janky setup which works, but I know I&#39;m not using the best of my resources.</p> <p>If anyone could help better my setup, that would be splendid!</p> <p><a href="https://preview.redd.it/ic6q1t1y7gud1.png?width=1303&amp;format=png&amp;auto=webp&amp;s=7130dddb34fa1139011d6255d232657206893e12">https://preview.redd.it/ic6q1t1y7gud1.png?width=1303&amp;format=png&amp;auto=webp&amp;s=7130dddb34fa1139011d6255d232657206893e12</a></p> <p>Current Setup:</p> <ul> <li><p>My arr stack downloads directly to an external hard drive, which then is copied to my Gateway PC via Syncthing.</p></li> <li><p>Proxmox gets backed up o

## How do I turn off bitwarden auto fill pop up?
 - [https://www.reddit.com/r/selfhosted/comments/1g2gx98/how_do_i_turn_off_bitwarden_auto_fill_pop_up](https://www.reddit.com/r/selfhosted/comments/1g2gx98/how_do_i_turn_off_bitwarden_auto_fill_pop_up)
 - RSS feed: $source
 - date published: 2024-10-13T03:32:53+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve rebooted my pc I&#39;ve reinstalled the extension. </p> <p>Whenever I click on a username or password field, bitwarden pops up with auto fill. </p> <p>It didn&#39;t used to do that and I don&#39;t want it to. It&#39;s popping up on random fields. I&#39;m trying to filter for an ip address on a palo alto firewall and the auto fill box keeps popping up. It&#39;s annoying. </p> <p>I went on settings &gt; autofill. I tried every setting but It still keeps popping up. If I need autofill I use the keyboard shortcut. I don&#39;t need a menu to pop up. </p> <p>I&#39;m using vaultwarden.</p> <p>&nbsp;</p> <p>Maybe its just a Firefox thing. I tried it on Chrome and it&#39;s not popping up. No matter what setting I choose on Firefox it still pops up.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Legitimate_Sun_5930"> /u/Legitimate_Sun_5930 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2

## What is Selfhosting - Linux Prepper ep.1
 - [https://www.reddit.com/r/selfhosted/comments/1g2gf1k/what_is_selfhosting_linux_prepper_ep1](https://www.reddit.com/r/selfhosted/comments/1g2gf1k/what_is_selfhosting_linux_prepper_ep1)
 - RSS feed: $source
 - date published: 2024-10-13T03:02:12+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/msic"> /u/msic </a> <br/> <span><a href="https://podcast.james.network/@linuxprepper/episodes/what-is-selfhosting">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2gf1k/what_is_selfhosting_linux_prepper_ep1/">[comments]</a></span>

## How do you name Tailscale tags and manage ACLs?
 - [https://www.reddit.com/r/selfhosted/comments/1g2g7ej/how_do_you_name_tailscale_tags_and_manage_acls](https://www.reddit.com/r/selfhosted/comments/1g2g7ej/how_do_you_name_tailscale_tags_and_manage_acls)
 - RSS feed: $source
 - date published: 2024-10-13T02:49:24+00:00

<!-- SC_OFF --><div class="md"><p>I have several small nodes across various cloud providers and continents, including my home basement and Raspberry Pis in the attic. Each serves a specific purpose, and they&#39;re all connected via Tailscale. Currently, their hostnames follow a simple template: &quot;$cloudprovider-$serialnumber.&quot;</p> <p>I&#39;m considering using Tailscale tags to apply fine-tuned ACLs and auth keys for future nodes, instead of signing in via Tailscale URLs. Do you use tags? If so, how do you organize your nodes with them?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/localhost-127"> /u/localhost-127 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2g7ej/how_do_you_name_tailscale_tags_and_manage_acls/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2g7ej/how_do_you_name_tailscale_tags_and_manage_acls/">[comments]</a></span>

## VPS router / reverse proxy keeping original IP
 - [https://www.reddit.com/r/selfhosted/comments/1g2fx8s/vps_router_reverse_proxy_keeping_original_ip](https://www.reddit.com/r/selfhosted/comments/1g2fx8s/vps_router_reverse_proxy_keeping_original_ip)
 - RSS feed: $source
 - date published: 2024-10-13T02:32:52+00:00

<!-- SC_OFF --><div class="md"><p>Looking for some info / direction. I want to set up a router on a VPS with a public facing IP, and forward traffic selectively based on port/origin/etc over a vpn to internal endpoints. That’s relatively simple, and if I wanted I could do it just with what is baked into the Linux kernel. </p> <p>The rub is that I’m trying to do it while retaining record of the original requester IP address for analysis on the internal server. Is there a relatively easy way / software that will do that? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Formal_Departure5388"> /u/Formal_Departure5388 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2fx8s/vps_router_reverse_proxy_keeping_original_ip/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2fx8s/vps_router_reverse_proxy_keeping_original_ip/">[comments]</a></span>

## How can I access my device gui remotely for live stream
 - [https://www.reddit.com/r/selfhosted/comments/1g2dbot/how_can_i_access_my_device_gui_remotely_for_live](https://www.reddit.com/r/selfhosted/comments/1g2dbot/how_can_i_access_my_device_gui_remotely_for_live)
 - RSS feed: $source
 - date published: 2024-10-13T00:03:27+00:00

<!-- SC_OFF --><div class="md"><p>I am traveling out of the country and my VPN cannot pass the streaming site geoblock. I am using the same device I use in the house but I would like to try remoting in to the house network and open my house computer for the actual stream. This is hoping that this overcomes the VPN detection and the stream will be smooth enough. Happy to also hear alternatives. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/riak00"> /u/riak00 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2dbot/how_can_i_access_my_device_gui_remotely_for_live/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g2dbot/how_can_i_access_my_device_gui_remotely_for_live/">[comments]</a></span>

