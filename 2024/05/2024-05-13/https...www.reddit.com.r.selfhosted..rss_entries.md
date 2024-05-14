# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Need to decide on cpu model
 - [https://www.reddit.com/r/selfhosted/comments/1crby4k/need_to_decide_on_cpu_model](https://www.reddit.com/r/selfhosted/comments/1crby4k/need_to_decide_on_cpu_model)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T22:08:45+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I am in the process of building my first server. I currently use a raspberry pi running homeassistant (with mqtt and zigbee2mqtt). I have done some research and the apps I am interested in are:</p> <ul> <li>Next cloud (To replace google drive)</li> <li>Immich (To replace google photos)</li> <li>Jellyfin (To stream content to my smart tv)</li> <li>Home assistant (with mqtt and zigbee2mqtt)</li> </ul> <p>I am able to buy some mini pc (like <strong>~HP EliteDesk~</strong> <strong>800 G3</strong> and Lenovo Thinkpad M710q). Those machines can have one m.2 and one 2.5 sata (I have 1tb of each and in reality my need are about 500GB for photos and files), so the limited slots is not a problem for me I think (at least for now).</p> <p>The mini pcs have 2 ram slots, I will be populating one with an 8gb stick. My main concern is the cpu model:</p> <ul> <li><strong>i3-6100T</strong></li> <li><strong>i3-7100T</strong></li> <li><strong>i3-8100T</strong></li

## Proxy Portainer through Traefik
 - [https://www.reddit.com/r/selfhosted/comments/1crakgt/proxy_portainer_through_traefik](https://www.reddit.com/r/selfhosted/comments/1crakgt/proxy_portainer_through_traefik)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T21:10:37+00:00

<!-- SC_OFF --><div class="md"><p>Im having some issues setting up Portainer to proxy through Traefik. </p> <p>Here is my Portainer `docker compose` file. </p> <p>```</p> <p>services:</p> <p>portainer:</p> <p>image: portainer/portainer-ce:latest</p> <p>container_name: portainer</p> <p>restart: unless-stopped</p> <p>security_opt:</p> <ul> <li>no-new-privileges:true</li> </ul> <p>networks:</p> <ul> <li>proxy</li> </ul> <p>volumes:</p> <ul> <li><p>/etc/localtime:/etc/localtime:ro</p></li> <li><p>/var/run/docker.sock:/var/run/docker.sock:ro</p></li> <li><p>/opt/portainer/data:/data</p></li> </ul> <p>labels:</p> <ul> <li><p>&quot;traefik.enable=true&quot;</p></li> <li><p>&quot;traefik.http.routers.portainer.entrypoints=http&quot;</p></li> <li><p>&quot;traefik.http.routers.portainer.rule=Host(`portainer.lab.mydomain.com)&quot;</p></li> <li><p>&quot;traefik.http.routers.portainer.tls=true&quot;</p></li> <li><p>&quot;traefik.http.services.portainer.loadbalancer.server.port=9000&quot;</p></li>

## Self-Hosting DNS
 - [https://www.reddit.com/r/selfhosted/comments/1cra8jd/selfhosting_dns](https://www.reddit.com/r/selfhosted/comments/1cra8jd/selfhosting_dns)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T20:57:09+00:00

<!-- SC_OFF --><div class="md"><p>I've seen a lot of threads related to various issues when self-hosting, a lot of them seem to be related to or directly caused by DNS.</p> <p>A few years back, I started transitioning all my domains to pointing to my own DNS servers, all hosted at various Cloud providers like DigitalO, Ultra, Linode, etc...</p> <p>On each provider I created a template &quot;very basic&quot; Debian instance and locked things down and am running isc-bind and, so far, have had the following results:</p> <ul> <li>things just work</li> <li>when they don't work it's something I did and can fix it. </li> <li>can be fun with other tools in the cloud and for cloud connectivity (ie:headscale) and other things. </li> </ul> <p>Questions I have: - what dangers should I be aware of? In all honesty, I consider myself pretty 'seasoned', but I would also be daft to ignore the fact that I don't know everything, and gaps appear every day in what we all think we know anyway. - what might

## Help with free, self hosted minecraft server via Pterodactyl/Docker on Ubuntu Desktop?
 - [https://www.reddit.com/r/selfhosted/comments/1cr9hbn/help_with_free_self_hosted_minecraft_server_via](https://www.reddit.com/r/selfhosted/comments/1cr9hbn/help_with_free_self_hosted_minecraft_server_via)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T20:26:24+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone. I have been trying to set up a minecraft server entirely for free and self hosted with Pterodactyl panel/Docker on Ubuntu 22.04 but to no avail. The process just isnt beginner friendly at all and no matter how many times I go over the documentation from Pterodactly I just cant make it to work. Youtube is scarce with content on this subject, I watched Techno Tim, SoulStriker, Synthetic Everything and quite a few others, they arent strictly following the documentation and I find it hard to follow since the knowledge gap is so wide and all of them are using their own methods. Is there anyone out there who managed to 'dumb it down' for newbies? The whole process, from how OS affects commands to turning on the server once you create it (after you shut down the pc).</p> <p>(I also saw that Ubuntu released 24.04 version a week ago and that Pterodactyl began transfering to Pelican Panel since a few days ago too, when they announced their offic

## Help with build
 - [https://www.reddit.com/r/selfhosted/comments/1cr8jpb/help_with_build](https://www.reddit.com/r/selfhosted/comments/1cr8jpb/help_with_build)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T19:49:09+00:00

<!-- SC_OFF --><div class="md"><p>Hey,</p> <p>I'm just getting started with a home lab.</p> <p>I currently have a RPI 5 8GB, I would like to self host the following:</p> <p>Jellyfin<br /> Applications (Discord bots, PostgreSQL etc)<br /> Some home automation</p> <p>What would you recommend build wise (something other than RPI 5? if so what?)?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AshamedFuel"> /u/AshamedFuel </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cr8jpb/help_with_build/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cr8jpb/help_with_build/">[comments]</a></span>

## Double Reverse Proxy to Container Apps
 - [https://www.reddit.com/r/selfhosted/comments/1cr8a2l/double_reverse_proxy_to_container_apps](https://www.reddit.com/r/selfhosted/comments/1cr8a2l/double_reverse_proxy_to_container_apps)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T19:38:27+00:00

<!-- SC_OFF --><div class="md"><p>Okay, I know this is hairy and I'm sure it's a configuration blocking my success. </p> <p>Ultimately I want to access containerised applications on Coolify on a host behind my home router Coolify is configured to use Caddy as a proxy. I want to use subdomains such as <a href="http://wordpress.example.com">wordpress.example.com</a> and route those requests through my maze to the service configured on Coolify. I have a domain pointed at a DO Droplet running NPM and there's a host configured to forward traffic from NPM to the host with Coolify (caddy). </p> <p>Fundamentally here's the flow;</p> <p>Digitalocean Droplet (tailscale)<br /> ---&gt; nginx-proxy-manager<br /> ---&gt; Home Server (tailscale)<br /> ---&gt; Caddy Reverse Proxy<br /> ---&gt; Containerised Application on Coolify</p> <p>I appreciate that I could put Coolify (or any other container orchestration tech) on a droplet and point my domain at my droplet and things would be simpler but, wher

## How to make the playback smooth in Plex or Jellyfin?
 - [https://www.reddit.com/r/selfhosted/comments/1cr7wsy/how_to_make_the_playback_smooth_in_plex_or](https://www.reddit.com/r/selfhosted/comments/1cr7wsy/how_to_make_the_playback_smooth_in_plex_or)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T19:23:43+00:00

<!-- SC_OFF --><div class="md"><p>When I play a movie and go back and forth, it can take a couple of seconds for the plex to buffer and continue at the new location. The 30s back or forth can be particularly annoying. Is this a bandwidth issue, or hardware in the server?</p> <p>Using phone app remotely over the internet. No plex pass, no hardware transcoding.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/chaplin2"> /u/chaplin2 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cr7wsy/how_to_make_the_playback_smooth_in_plex_or/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cr7wsy/how_to_make_the_playback_smooth_in_plex_or/">[comments]</a></span>

## Building Self-hosted
 - [https://www.reddit.com/r/selfhosted/comments/1cr6r4q/building_selfhosted](https://www.reddit.com/r/selfhosted/comments/1cr6r4q/building_selfhosted)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T18:37:35+00:00

<!-- SC_OFF --><div class="md"><p>For the devs out there that have released a self-hosting tool, did you find a tutorial or any instructions for for how to do a release? Like mainly for containerizing the software?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TechyRyan33"> /u/TechyRyan33 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cr6r4q/building_selfhosted/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cr6r4q/building_selfhosted/">[comments]</a></span>

## Running services for only home use (no remote access) - Security risk?
 - [https://www.reddit.com/r/selfhosted/comments/1cr6bs1/running_services_for_only_home_use_no_remote](https://www.reddit.com/r/selfhosted/comments/1cr6bs1/running_services_for_only_home_use_no_remote)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T18:20:20+00:00

<!-- SC_OFF --><div class="md"><p>Noob question here - I am getting into self-hosting and am wondering: at what point does it start to introduce more security risks than the average internet user would incur?</p> <p>Right now I am running a pi-hole, with unbound DNS. On the same machine I'm running a recipe manager (Tandoor) that is only accessible to me when I am on my home network. From what I know about private IP addresses and NAT, my services are no different than my printer, but I would like to know if I'm wrong.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/r58_"> /u/r58_ </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cr6bs1/running_services_for_only_home_use_no_remote/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cr6bs1/running_services_for_only_home_use_no_remote/">[comments]</a></span>

## Authentik over Okta
 - [https://www.reddit.com/r/selfhosted/comments/1cr5e1c/authentik_over_okta](https://www.reddit.com/r/selfhosted/comments/1cr5e1c/authentik_over_okta)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T17:42:41+00:00

<!-- SC_OFF --><div class="md"><p>I work in a startup, I’m going to propose Authentik to replace current Okta setup we have around 2000 employee base using google suite for what it does and some other tools configured as apps from Okta dashboard.</p> <p>What questions or strong blockers I should be expecting, I just want to be ready to answer that and I want to advocate to use selfhhpated FOSS over paid SaaSs if it’s all worth though.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cyber-guru"> /u/cyber-guru </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cr5e1c/authentik_over_okta/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cr5e1c/authentik_over_okta/">[comments]</a></span>

## My Brief Experience with Hetzner: Perhaps a Few Words of Caution?
 - [https://www.reddit.com/r/selfhosted/comments/1cr53ui/my_brief_experience_with_hetzner_perhaps_a_few](https://www.reddit.com/r/selfhosted/comments/1cr53ui/my_brief_experience_with_hetzner_perhaps_a_few)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T17:31:19+00:00

<!-- SC_OFF --><div class="md"><p>I recently attempted to become a customer at Hetzner, but my experience was cut short (about four days). This review may not be extensive, but I hope it provides some insights for those considering Hetzner.</p> <ol> <li>When Hetzner says, &quot;We have decided to deactivate your account,&quot; they mean it quite literally. Once deactivated, I could not even log in. Their system reported &quot;invalid credentials.&quot; It's unclear whether this deactivation also terminates any associated hosting or other services, but if it does, it can be particularly problematic if you don’t have backups stored elsewhere. <strong>Never have any backups with your current host, always have them elsewhere.</strong></li> <li>Don't create an account there on a Friday, unless it's early in the morning, since their account verification team only works Monday to Friday. Also keep in mind the time zone.</li> <li>Don't create an account their using a VPN? I didn't but apparen

## Help using my PC build to share apps with colleagues.
 - [https://www.reddit.com/r/selfhosted/comments/1cr3k7g/help_using_my_pc_build_to_share_apps_with](https://www.reddit.com/r/selfhosted/comments/1cr3k7g/help_using_my_pc_build_to_share_apps_with)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T16:28:18+00:00

<!-- SC_OFF --><div class="md"><p>I've got a AMD Threadripper build 64gb ram, RTX4090, that I use at work for 3D rendering (mostly unreal engine). I want to start self hosting apps (Ai tools) for the team to use (we've got a few up and running on various computers here) so everyone can use the 4090 when they need to crunch a bunch of stuff at once. Basically want to have the apps as high-availability as possible. I don't use the PC that often and when I do I could suspend those services for the time. </p> <p>Main question is best way to host them so that they each get GPU access but in a background kind of way. The PC is rarely rebooted. </p> <p>My initial thought is Docker desktop, which I believe will allow the GPU support in most recent versions. I also thought about making it a Linux machine and running Windows as a VM inside that when needed or if possible linux sharing the GPU with the windows VM. </p> <p>Just curious if anything better than these comes to mind.</p> </div><!-- S

## Unpleasant experience with Netcup
 - [https://www.reddit.com/r/selfhosted/comments/1cr2ksg/unpleasant_experience_with_netcup](https://www.reddit.com/r/selfhosted/comments/1cr2ksg/unpleasant_experience_with_netcup)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T15:47:56+00:00

<!-- SC_OFF --><div class="md"><p>Has anyone using Netcup experienced a delay after ordering a vServer, where the server isn't readily available? They told me to wait a few days, which is quite different from other providers.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/boosterhq"> /u/boosterhq </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cr2ksg/unpleasant_experience_with_netcup/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cr2ksg/unpleasant_experience_with_netcup/">[comments]</a></span>

## Evaluating My Planned Build for Homelab, GameServer & Plex—Input Wanted!
 - [https://www.reddit.com/r/selfhosted/comments/1cr1wm2/evaluating_my_planned_build_for_homelab](https://www.reddit.com/r/selfhosted/comments/1cr1wm2/evaluating_my_planned_build_for_homelab)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T15:20:07+00:00

<!-- SC_OFF --><div class="md"><p>I'm in the process of upgrading from my current setup and need some advice on my planned build. I currently have a Synology NAS, which has served me well, but I've outgrown its capabilities. I'm planning to pass it down to my wife and move on to something more robust. Here is my proposed server build and would appreciate your insights on the components I've selected.</p> <p><a href="https://newegg.io/98ef8d0">https://newegg.io/98ef8d0</a></p> <p><strong>Here's what I'm aiming to include in my new setup:</strong></p> <ol> <li><strong>Homelab Environment</strong>: <ul> <li><strong>Tools</strong>: GNS3, Containerlab, EveNG</li> <li><strong>Purpose</strong>: To enhance my network simulation and virtualization capabilities.</li> </ul></li> <li><strong>Game Server Hosting</strong>: <ul> <li><strong>Games</strong>: ARK, V RISING, 7 Days to Die, Satisfactory, etc.</li> <li><strong>Goal</strong>: Reliable and responsive hosting for multiplayer gaming with frie

## Need help securing my homelab
 - [https://www.reddit.com/r/selfhosted/comments/1cr1k9y/need_help_securing_my_homelab](https://www.reddit.com/r/selfhosted/comments/1cr1k9y/need_help_securing_my_homelab)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T15:05:39+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I've recently begun to selfhost things on an old laptop I had. My setup is basically :</p> <p>Internet &lt;-&gt; vps server with nginx rp &lt;-&gt; home server through tailscale</p> <p>The internet vps connection is https and the tailscale between the vos and the home server is http.</p> <p>The thing is I want to secure it at least a bit but I've no knowledge on how to do it. </p> <p>I'll prefer to expose every service I use and don't use a vpn.</p> <p>If you could give me some advice on where to start or at least where to look at I'll be thankful !</p> <p>Have a nice day !</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Nailec_07"> /u/Nailec_07 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cr1k9y/need_help_securing_my_homelab/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cr1k9y/need_help_securing_my_homelab/">[comments]</a></span>

## Public availability of your homeserver
 - [https://www.reddit.com/r/selfhosted/comments/1cr1ipy/public_availability_of_your_homeserver](https://www.reddit.com/r/selfhosted/comments/1cr1ipy/public_availability_of_your_homeserver)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T15:03:43+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I just wanted to share some thoughts with you. I'm curious in your view on this.</p> <p>Like most of you here, I'm hosting a small homeserver for (mostly myself, and maybe some relatives. I'm not a big fan on port-forward on my home-router. So I'm curious: <strong>how did you secure your public available services? Can I improve anything without lowering the ease-of-use for my family?</strong></p> <p>I'm hosting Jellyfin for myself, the spouse and the kids.<br /> Im hosting Sonarr, Radarr and Heimdall for myself.<br /> Later I would want to add my Portainer, qBittorrent / SabNZBd and maybe even a SSH-option.</p> <p>There are no portforwards configured, everything is available through a cloudflared-docker container. On top of that I'm excluding all requests outside of my country on my Cloudflare Dashboard. I've the feeling on missing some extra security. Everything is password protected, but I didn't configure any type of MFA yet.</p> </div><!--

## Any hosting control panel that available inside docker?
 - [https://www.reddit.com/r/selfhosted/comments/1cr18y7/any_hosting_control_panel_that_available_inside](https://www.reddit.com/r/selfhosted/comments/1cr18y7/any_hosting_control_panel_that_available_inside)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T14:52:19+00:00

<!-- SC_OFF --><div class="md"><p>Do you know any?</p> <p>Do you use personally?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FutureLife777"> /u/FutureLife777 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cr18y7/any_hosting_control_panel_that_available_inside/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cr18y7/any_hosting_control_panel_that_available_inside/">[comments]</a></span>

## Mini PC questions for a Jellyfin setup
 - [https://www.reddit.com/r/selfhosted/comments/1cr0rqa/mini_pc_questions_for_a_jellyfin_setup](https://www.reddit.com/r/selfhosted/comments/1cr0rqa/mini_pc_questions_for_a_jellyfin_setup)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T14:31:40+00:00

<!-- SC_OFF --><div class="md"><p>Hope everyone is having a great day.</p> <p>Title is pretty self explanatory. Currently I'm running my homelab out of an old laptop (i7 4th gen, SSD and 16gb RAM) which is fine honestly but I might want to access my media via a VPN in the future and that will require transcoding for sure as my upload speeds are bad.</p> <p>I'm looking for mini pc suggestions that can handle transcoding 4K 10 bit(12 bit if possible?) streams, up to 3 streams at a time.</p> <p>Majority of the lenovo/dell mini pc's I find online are 7th gen i5 processor ones, which I understand is favorable for transcoding. But I also see some newer gen processors like 10 or 11 (still with Intel UHD 630 GPUs). The newer ones cost significantly more.(1.5x - 2x) I wanna buy 3 to build a HA Proxmox cluster so added cost will triple.</p> <p>Question is would I be getting a better performance for that extra amount of money?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://ww

## Password manager with "Save All Entered Data" function
 - [https://www.reddit.com/r/selfhosted/comments/1cqzwci/password_manager_with_save_all_entered_data](https://www.reddit.com/r/selfhosted/comments/1cqzwci/password_manager_with_save_all_entered_data)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T13:54:43+00:00

<!-- SC_OFF --><div class="md"><p>Do you know any?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/6-1j"> /u/6-1j </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqzwci/password_manager_with_save_all_entered_data/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqzwci/password_manager_with_save_all_entered_data/">[comments]</a></span>

## OneUptime uses Kubernetes and Ceph to de-cloud and save 70%+ in cloud costs.
 - [https://www.reddit.com/r/selfhosted/comments/1cqyxnl/oneuptime_uses_kubernetes_and_ceph_to_decloud_and](https://www.reddit.com/r/selfhosted/comments/1cqyxnl/oneuptime_uses_kubernetes_and_ceph_to_decloud_and)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T13:10:27+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://ubuntu.com/engage/oneuptime-cost-savings-case-study">https://ubuntu.com/engage/oneuptime-cost-savings-case-study</a> </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OuPeaNut"> /u/OuPeaNut </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqyxnl/oneuptime_uses_kubernetes_and_ceph_to_decloud_and/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqyxnl/oneuptime_uses_kubernetes_and_ceph_to_decloud_and/">[comments]</a></span>

## Hardware choices for a Nuke 'n Pave of a lightweight Pi4 setup?
 - [https://www.reddit.com/r/selfhosted/comments/1cqyv96/hardware_choices_for_a_nuke_n_pave_of_a](https://www.reddit.com/r/selfhosted/comments/1cqyv96/hardware_choices_for_a_nuke_n_pave_of_a)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T13:07:20+00:00

<!-- SC_OFF --><div class="md"><p><strong>tl;dr</strong> Proxmox on a mini-PC is what I want for light home automation and data backup right?</p> <p>For a year or so I have been tooling around with low end consumer grade hardware and a Pi4.</p> <p>My Pi4's SSD has failed, so I have an opportunity rebuild, including hardware.</p> <p>On the one Pi4 I predominantly run:</p> <ul> <li>Home Assistant - but the hard way, HA Core in a Python Venv, not the supervised version with addons (I want to change this);</li> <li>Octoprint with a camera connected;</li> <li>Frigate (one camera for wildlife detection);</li> <li>Wire-Pod (a server for an Anki Vector robot);</li> <li>Various standalone tools that compliment Home Assistant and are available as addons to HA if I use a supervised version (Z2M, MQTT, ESPHome, Certbot, etc).</li> </ul> <p>My existing hardware is:</p> <ul> <li>Pi4 booting off 240GB Sandisk SSD;</li> <li>2x 4TB HDDs in a raid 1 configuration (in Amazon-special powered USB caddy) f

## Data transfer and conversion
 - [https://www.reddit.com/r/selfhosted/comments/1cqyjrj/data_transfer_and_conversion](https://www.reddit.com/r/selfhosted/comments/1cqyjrj/data_transfer_and_conversion)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T12:51:52+00:00

<!-- SC_OFF --><div class="md"><p>Many years ago I've found a website of an open source software that allow to define different sites, protocols (smb share, ftp, SFTP, web api, ...) and data formats (sql tables, CSV files, JSON data, ...) and define data transfer rules and conversions between them. I can't remember it's name... Do you know such a software?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Diesis73"> /u/Diesis73 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqyjrj/data_transfer_and_conversion/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqyjrj/data_transfer_and_conversion/">[comments]</a></span>

## Need Help with Docker Compose for Self-Hosted PHP CRM System with HTTPS
 - [https://www.reddit.com/r/selfhosted/comments/1cqxsnj/need_help_with_docker_compose_for_selfhosted_php](https://www.reddit.com/r/selfhosted/comments/1cqxsnj/need_help_with_docker_compose_for_selfhosted_php)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T12:13:36+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, </p> <p>I'm looking for assistance in setting up a Docker Compose configuration that can host my self-hosted PHP CRM system with HTTPS support. I've tried different compose files and configurations, but I haven't been able to get it to work properly. </p> <p>I would greatly appreciate if someone could provide me with a working Docker Compose file or guide me through the process of configuring my setup to host my PHP CRM system securely with HTTPS. </p> <p>Here's some additional information about my setup:<br /> - The CRM system is built using PHP 8.1 and PHP extentions<br /> - I want to host it on my own server<br /> - HTTPS support is crucial but its not nessesary to have a valid ssl certificate im working via Cloudflare tunnels </p> <p>If you have any experience with Docker Compose and hosting PHP applications with HTTPS, please share your insights or point me in the right direction. I've been struggling with this for a while, and I'

## Selfhisted solution for hotel TV
 - [https://www.reddit.com/r/selfhosted/comments/1cqx4ej/selfhisted_solution_for_hotel_tv](https://www.reddit.com/r/selfhosted/comments/1cqx4ej/selfhisted_solution_for_hotel_tv)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T11:37:30+00:00

<!-- SC_OFF --><div class="md"><p>Hello, anyone know is there's some project like management system for hotel tv? Regards.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/skweresp"> /u/skweresp </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqx4ej/selfhisted_solution_for_hotel_tv/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqx4ej/selfhisted_solution_for_hotel_tv/">[comments]</a></span>

## Anything better than Truenas Scale for docker?
 - [https://www.reddit.com/r/selfhosted/comments/1cqwfjw/anything_better_than_truenas_scale_for_docker](https://www.reddit.com/r/selfhosted/comments/1cqwfjw/anything_better_than_truenas_scale_for_docker)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T10:56:55+00:00

<!-- SC_OFF --><div class="md"><p>I have a server running Truenas Scale that I use for storage and running truecharts apps. It works, but I'm getting frustrated with the lack of configurability for docker containers.</p> <p>I want full access to configure my apps with docker files like normal, and to learn how to use docker the usual way, not filtered through truenas.</p> <p>My first instinct is to boot into Ubuntu server from a USB, try to mount my zfs pool and if everything looks good to install it on my boot drive, but I don't know if that's a good idea or if there are better options. </p> <p>Any advice appreciated! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/theoryandpraxis"> /u/theoryandpraxis </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqwfjw/anything_better_than_truenas_scale_for_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqwfjw/anything_better_than_truena

## Creating a video website from youtube video's
 - [https://www.reddit.com/r/selfhosted/comments/1cqw9uk/creating_a_video_website_from_youtube_videos](https://www.reddit.com/r/selfhosted/comments/1cqw9uk/creating_a_video_website_from_youtube_videos)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T10:47:19+00:00

<!-- SC_OFF --><div class="md"><p>Hi i am stuck with figuring out how to automate Downloading video's from youtube and then linking it to my wordpress website to use as a file rather then the Youtube embeded. So far i am using it through a Google sheet API but this only makes it so that it is still connected to youtube. </p> <p>Any ideas or tools that can help me with this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ZiggyMaster123"> /u/ZiggyMaster123 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqw9uk/creating_a_video_website_from_youtube_videos/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqw9uk/creating_a_video_website_from_youtube_videos/">[comments]</a></span>

## Private Email Server (from online service) to Sync with Gmail
 - [https://www.reddit.com/r/selfhosted/comments/1cqvtjb/private_email_server_from_online_service_to_sync](https://www.reddit.com/r/selfhosted/comments/1cqvtjb/private_email_server_from_online_service_to_sync)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T10:18:35+00:00

<!-- SC_OFF --><div class="md"><p>I dont have much view of the technical possibility and difficulties it might face.</p> <p>However I was looking for expert advice and possible steps if I am able to procure a private email domain and server and have it sync automatically with my Gmail or Outlook. It would need to have the possibility of synching with older POP3/SMTP devices.</p> <p>I am asking since I have an old Sony Clie UX50 and I was wondering if the preloaded email client would work with the current generation email services. It is surely expected to face some issues. So as alternate I can setup my own email server and sync clie with it.</p> <p>Does the idea sounds sensible.</p> <p>Here is brief view on Clie mail application.</p> <p><a href="https://www.sonyclie.org/manuals/NX60-70-70V/CLIE_application_manual/03_mai/mai_00230.html">https://www.sonyclie.org/manuals/NX60-70-70V/CLIE_application_manual/03_mai/mai_00230.html</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a hr

## Hosting 10 low-traffic websites, what server size should I use?
 - [https://www.reddit.com/r/selfhosted/comments/1cqvhiw/hosting_10_lowtraffic_websites_what_server_size](https://www.reddit.com/r/selfhosted/comments/1cqvhiw/hosting_10_lowtraffic_websites_what_server_size)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T09:56:15+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, </p> <p>Complete rookie question here. </p> <p>I have a Digital Ocean VPS server through Cloudways with 1GB RAM and 25GB disk space. The data currently look like this:</p> <p>-10 websites - Mixture of service based and e-commerce WordPress websites. Max traffic is 50 visits per site per day</p> <p>- RAM usage - 50%</p> <p>- CPU usage - 40%</p> <p>- Disk usage - 95%</p> <p>I'm looking to scale some of these project and will need to upgrade. </p> <p>Cloudways recommends a 4GB server with 2 cores and 80GB SSD. There are also options for a 2GB server but I want to go with whatever makes sense.</p> <p>&#x200b;</p> <p>TIA</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/No_Frosting363"> /u/No_Frosting363 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqvhiw/hosting_10_lowtraffic_websites_what_server_size/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/commen

## Outdoor Audio Streamer
 - [https://www.reddit.com/r/selfhosted/comments/1cqv3ac/outdoor_audio_streamer](https://www.reddit.com/r/selfhosted/comments/1cqv3ac/outdoor_audio_streamer)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T09:28:13+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>Not totally sure if this is the right subreddit, however, i guess ESP32 dac's are an option so in some way, it is related to selfhosted ;) </p> <p>When we renovated our house, we did not pull speaker wire to our outdoor seating area. However, now we seem to be wanting to have 2 speakers there. I can provide power and ethernet to that place so that won't be an issue. Now I am searching for some sort of active speakers but this seems very very limited. Spotify connect/wifi would be a big plus, not preferring bluetooth. I guess if they have an aux, i could go for some sort of esp32 or rasperrypi with a DAC? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/zierbeek"> /u/zierbeek </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqv3ac/outdoor_audio_streamer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqv3ac/outdoor_audio_streamer/">[comm

## Searching for a true replacement for Focalboard
 - [https://www.reddit.com/r/selfhosted/comments/1cqudgh/searching_for_a_true_replacement_for_focalboard](https://www.reddit.com/r/selfhosted/comments/1cqudgh/searching_for_a_true_replacement_for_focalboard)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T08:34:49+00:00

<!-- SC_OFF --><div class="md"><p>I need a task management application for keeping track of things to do in my life (concert, shows, places to eat) and I'd like to group all these tasks by a custom property in a kanban board. Focalboard is indeed the perfect match for this use case as its kanban board made by just grouping tasks for a particular property. The actual killer feature is the ability of switching the grouping with a single click, suppose that the tasks have the 'category' and 'city' property, I can easily switch from a board where all columns are categories to one where all columns are cities. This is great to organize freely my tasks.<br /> However Focalboard went officially community supported, but actually it seems that the project is dead an there aren't any valid forks so far.</p> <p>I also tried the solutions proposed <a href="https://www.reddit.com/r/selfhosted/comments/1avl023/looking_to_ditch_focalboard_kanban_board_can/">in this thread</a>, but they all seem to l

## Need help creating an SSL certificate with acme.sh for PrivateBin using Apache2 as a reverse proxy
 - [https://www.reddit.com/r/selfhosted/comments/1cqtssf/need_help_creating_an_ssl_certificate_with_acmesh](https://www.reddit.com/r/selfhosted/comments/1cqtssf/need_help_creating_an_ssl_certificate_with_acmesh)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T07:52:12+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I'm new to the world of SSL and Apache2 and I need some help on creating an SSL certificate for the webapp PrivateBin. Here is my current setup :</p> <ul> <li>Domain and subdomains point to <code>linuxfront</code>, which acts as a reverse proxy with Apache2</li> <li>On <code>linuxfront</code> I've created a configuration file for PrivateBin inside <code>/etc/apache2/sites-available/privatebin.domain.conf</code> to handle the redirection to <code>linuxback</code> server (the one containing www files of privatebin)</li> <li>On <code>linuxback</code> I also have an Apache configuration in /<code>etc/apache2/sites-available/privatebin.domain.conf</code> which use a self-made certificate who has been created using the following command : <code>openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout privatebin.domain.key -out privatebin.domain.crt</code> </li> </ul> <p>Here are my 2 apache configuration : </p> <p><a href="https://

## Mailcow leaks email aliases?
 - [https://www.reddit.com/r/selfhosted/comments/1cqt9of/mailcow_leaks_email_aliases](https://www.reddit.com/r/selfhosted/comments/1cqt9of/mailcow_leaks_email_aliases)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T07:13:41+00:00

<!-- SC_OFF --><div class="md"><p>About two weeks ago I received a huge spam wave, which in itself wasn't a problem the spam mails were all rejected by rspamd. Now the strange part is, the receiving addresses were all real aliases I use ... Now I am absolutely clueless as to how anyone could get those addresses, I only use them for single services like oracle@ or veeam@.</p> <p>Could this be a configuration issue on my side? A friend suggested it might be done by smtp enumeration.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Malaclypse5"> /u/Malaclypse5 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqt9of/mailcow_leaks_email_aliases/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqt9of/mailcow_leaks_email_aliases/">[comments]</a></span>

## Crowdsec users - are you still using fbonalair bouncer for traefik?
 - [https://www.reddit.com/r/selfhosted/comments/1cqss0h/crowdsec_users_are_you_still_using_fbonalair](https://www.reddit.com/r/selfhosted/comments/1cqss0h/crowdsec_users_are_you_still_using_fbonalair)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T06:39:48+00:00

<!-- SC_OFF --><div class="md"><p>fbonalair crowdsec traefik bouncer repo: <a href="https://github.com/fbonalair/traefik-crowdsec-bouncer">https://github.com/fbonalair/traefik-crowdsec-bouncer</a></p> <p>This has not received updates in 2 years. Is everyone still using it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/roasted_watermelon"> /u/roasted_watermelon </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqss0h/crowdsec_users_are_you_still_using_fbonalair/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqss0h/crowdsec_users_are_you_still_using_fbonalair/">[comments]</a></span>

## How to backup to contabo object storage using Duplicati?
 - [https://www.reddit.com/r/selfhosted/comments/1cqrs78/how_to_backup_to_contabo_object_storage_using](https://www.reddit.com/r/selfhosted/comments/1cqrs78/how_to_backup_to_contabo_object_storage_using)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T05:33:05+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I'm trying to set up backups with Contabo's S3-compatible object storage but I keep running into connection errors. Despite choosing the S3 option and correctly entering the bucket name and access keys, I can't seem to get it to work. I've tried various approaches and even used AI for guidance, but nothing has resolved the issue.</p> <p>Has anyone here successfully configured backups with Contabo Object Storage? I'm at my wits' end (which is evidently not much) and would really appreciate any help or guidance on how to troubleshoot this.</p> <p>Thanks in advance</p> <p>EDIT: The server I am trying to backup is windows.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/x-aish-a-12"> /u/x-aish-a-12 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqrs78/how_to_backup_to_contabo_object_storage_using/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted

## Standard Linux vs "NAS" OS'es
 - [https://www.reddit.com/r/selfhosted/comments/1cqqo1e/standard_linux_vs_nas_oses](https://www.reddit.com/r/selfhosted/comments/1cqqo1e/standard_linux_vs_nas_oses)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T04:24:07+00:00

<!-- SC_OFF --><div class="md"><p>I'm trying to educate myself a little more about the different options when it comes to building and maintaining my home server (relative newbie here) </p> <p>The setup I have right now is just a Debian install and manually setup a ZFS pool with a couple drives connected and mounted to the root for my main storage and usage.</p> <p>My question is really what are the differences between these options I always see like UNRAID or FreeNAS compared to just the way I'm doing it now with a standard Debian install?</p> <p>Is there a benefit simply due to nicer UI and community? Is it generally less of a hassle to use certain ones? I distinctly remember having to jump through some hoops to setup some primitive email notification system for my pool health and things like that.</p> <p>I also occasionally run a few game servers for myself and friends off the system, so I sometimes use the server for some other service hosting as well, not 100% just a storage medi

## Flight tracker/location tracker
 - [https://www.reddit.com/r/selfhosted/comments/1cqqf3q/flight_trackerlocation_tracker](https://www.reddit.com/r/selfhosted/comments/1cqqf3q/flight_trackerlocation_tracker)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T04:08:58+00:00

<!-- SC_OFF --><div class="md"><p>Hi all</p> <p>I am getting into self hosting finally and loving it. Got a kid on the way and want to be able to have a map of the world that shows where I am (im a pilot so just using a location tracker of find my phone style won’t work as I want it to). </p> <p>My thought is using something like FlightAware and be able to track specific flights on a specific date to show where the plane is and then have the same map show which city I’m in between flights. </p> <p>Example being 1st fly London to Paris Stay in Paris 1st and 2nd 3rd fly Paris, Amsterdam, London </p> <p>Map would show location of plane in “real” time on 1st and 3rd then after flight on 1st and before flights on 3rd would show me in Paris. </p> <p>Has anyone done this very specific use case or know how it could be achieved? Any help would be greatly appreciate </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/floatingbumblebee66"> /u/floatingbumblebee

## Cal seflhosted cant invite users?
 - [https://www.reddit.com/r/selfhosted/comments/1cqn83f/cal_seflhosted_cant_invite_users](https://www.reddit.com/r/selfhosted/comments/1cqn83f/cal_seflhosted_cant_invite_users)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T01:16:21+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1cqn83f/cal_seflhosted_cant_invite_users/"> <img alt="Cal seflhosted cant invite users?" src="https://b.thumbs.redditmedia.com/PluwKv0jJNTkvU91CQBnCLOIDD_80hsycsgJcjE7eEU.jpg" title="Cal seflhosted cant invite users?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Just got this installed</p> <p>Went to invite some team members and im getting this in the users screen</p> <p>So selfhosted version is for a single user?</p> <p>&#x200b;</p> <p><a href="https://preview.redd.it/l3ehca1sg30d1.jpg?width=3804&amp;format=pjpg&amp;auto=webp&amp;s=5690d2e6f8e5f24cebcbf38a3ee0889b9e7872a8">https://preview.redd.it/l3ehca1sg30d1.jpg?width=3804&amp;format=pjpg&amp;auto=webp&amp;s=5690d2e6f8e5f24cebcbf38a3ee0889b9e7872a8</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/xboxhaxorz"> /u/xboxhaxorz </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cqn83f/cal_seflhost

## In light of all the homepage dashboard posts, I figured I would post mine
 - [https://www.reddit.com/r/selfhosted/comments/1cqn2qi/in_light_of_all_the_homepage_dashboard_posts_i](https://www.reddit.com/r/selfhosted/comments/1cqn2qi/in_light_of_all_the_homepage_dashboard_posts_i)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-05-13T01:08:29+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1cqn2qi/in_light_of_all_the_homepage_dashboard_posts_i/"> <img alt="In light of all the homepage dashboard posts, I figured I would post mine" src="https://b.thumbs.redditmedia.com/b-lAozg642fawC2ALpCySglQxQWF6jeUchp7o2NBneU.jpg" title="In light of all the homepage dashboard posts, I figured I would post mine" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Ive got a number of ideas for layouts and apps to try from others on here so here is mine</p> <p>still going back and forth on colour icons vs si-icons</p> <p><a href="https://preview.redd.it/th7q8j80g30d1.png?width=1111&amp;format=png&amp;auto=webp&amp;s=28d228dc1d5936b11718e14f7d8f7bc606808498">https://preview.redd.it/th7q8j80g30d1.png?width=1111&amp;format=png&amp;auto=webp&amp;s=28d228dc1d5936b11718e14f7d8f7bc606808498</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/duke_seb"> /u/duke_seb </a> <br /> <span><a hr

