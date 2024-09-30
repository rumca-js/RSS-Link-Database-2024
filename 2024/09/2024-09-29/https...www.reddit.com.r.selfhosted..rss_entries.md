# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Need help to expose my website to the Internet
 - [https://www.reddit.com/r/selfhosted/comments/1fshoo8/need_help_to_expose_my_website_to_the_internet](https://www.reddit.com/r/selfhosted/comments/1fshoo8/need_help_to_expose_my_website_to_the_internet)
 - RSS feed: $source
 - date published: 2024-09-29T23:22:45+00:00

<!-- SC_OFF --><div class="md"><p>Hey Folks,</p> <p>Today, I encountered an unexpected issue with what I thought would be a simple task: exposing a website to the internet. I could really use some help.</p> <p>The setup isn’t too complex. My ISP&#39;s router forwards incoming traffic from port 8188 to port 443 on my Raspberry Pi (I couldn’t use external ports 80 or 443 because those are reserved for the router). On my Raspberry Pi, I’m running a Traefik container, which serves as a reverse proxy for several services like Pi-hole, Vaultwarden, etc. These services are configured with <code>Host(&quot;subdomain&quot;)</code> rules in their respective Docker Compose files. For this particular website, the service is an Nginx container that holds the website’s content, using <code>Host(&quot;www.domain.com&quot;) || Host(&quot;domain.com&quot;)</code> as its routing rule. When I access the site through my internal network by setting a DNS record in Pi-hole, everything works perfectly.</p> 

## Need help with vps
 - [https://www.reddit.com/r/selfhosted/comments/1fshjiv/need_help_with_vps](https://www.reddit.com/r/selfhosted/comments/1fshjiv/need_help_with_vps)
 - RSS feed: $source
 - date published: 2024-09-29T23:15:42+00:00

<!-- SC_OFF --><div class="md"><p>So I’m using kamatera VPs and using this macro, whenever I switch to main desktop or close my monitor the macro stops working can someone help me fix this</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Pristine-Ride4617"> /u/Pristine-Ride4617 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fshjiv/need_help_with_vps/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fshjiv/need_help_with_vps/">[comments]</a></span>

## Questions about security and exposing services
 - [https://www.reddit.com/r/selfhosted/comments/1fshbc1/questions_about_security_and_exposing_services](https://www.reddit.com/r/selfhosted/comments/1fshbc1/questions_about_security_and_exposing_services)
 - RSS feed: $source
 - date published: 2024-09-29T23:04:12+00:00

<!-- SC_OFF --><div class="md"><p>I currently expose 2 services. I have Cloudflare pointing my domain to my public IP with its proxy option enabled. I expose port 443 only and traffic goes to my DMZ. In there I have those two services, along with Nginx Proxy Manager as well as fail2ban. Admittedly I do still need to fully test my security, and was going to check out Kali Linux to see how it could help. Additionally, I&#39;m looking into adding Authentik.</p> <p>I&#39;ve done my best to harden my firewall as well and ensure that the DMZ has no access to the rest of my network. </p> <p>Are these measures enough? I know I could use CF tunnels, along with its auth option, which would mitigate a lot of this stuff. But ultimately I like the idea of handling this stuff myself to learn and not having my data pass through CF. Thx!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gjunk1e"> /u/gjunk1e </a> <br/> <span><a href="https://www.reddit.com/r/selfho

## Minecraft server hosted on other local devices
 - [https://www.reddit.com/r/selfhosted/comments/1fseuce/minecraft_server_hosted_on_other_local_devices](https://www.reddit.com/r/selfhosted/comments/1fseuce/minecraft_server_hosted_on_other_local_devices)
 - RSS feed: $source
 - date published: 2024-09-29T21:09:01+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ll try to explain myself, I&#39;m getting started in this world of self-hosting, I already have some basic services up-and-running as Plex, Pi-hole, Ngix, Qbittorrent, etc. I&#39;m trying to use a self-host minecraft server manager on my docker server (I was looking at Crafty but sugesttions are welcome!)</p> <p>My question here is: Can I use another local server (an old laptop) to host the minecraft server and still be able to control it from my self-hosted app (hosted on a different device)? Both are in the same LAN, but wanted to ask if it&#39;s possible.</p> <p>Also, I&#39;m looking for a way to expose the minecraft server trough tunneling like ngrok/cloudflare zero trust, can this be done from a self-hosted app even if it&#39;s on a different device? Or is it better to configure the tunnel on the actual device where the minecraft server is hosted?</p> <p>P.S. Will be hosting java modded version, if it helps :)</p> </div><!-- SC_ON --> &#32;

## Tailscale SSL certificates with custom DNS and subdomains
 - [https://www.reddit.com/r/selfhosted/comments/1fsenoo/tailscale_ssl_certificates_with_custom_dns_and](https://www.reddit.com/r/selfhosted/comments/1fsenoo/tailscale_ssl_certificates_with_custom_dns_and)
 - RSS feed: $source
 - date published: 2024-09-29T21:00:55+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I&#39;m quite new to tailscale and self-hosting. I&#39;ve set up a custom DNS (using technitium) so I can use subdomains to serve different services. I&#39;ve configured this DNS on my tailscale account and I&#39;m able to access these services on the subdomains. However, I can&#39;t seem to use <code>tailscale cert</code> to get SSL certificates for those subdomains. Is that not possible?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CuriousBot42"> /u/CuriousBot42 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fsenoo/tailscale_ssl_certificates_with_custom_dns_and/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fsenoo/tailscale_ssl_certificates_with_custom_dns_and/">[comments]</a></span>

## Minecraft server can't connect to auth servers while Wireguard is running
 - [https://www.reddit.com/r/selfhosted/comments/1fsdzlf/minecraft_server_cant_connect_to_auth_servers](https://www.reddit.com/r/selfhosted/comments/1fsdzlf/minecraft_server_cant_connect_to_auth_servers)
 - RSS feed: $source
 - date published: 2024-09-29T20:31:12+00:00

<!-- SC_OFF --><div class="md"><p>I just set up a reverse proxy with wireguard using <a href="https://github.com/mochman/Bypass_CGNAT">this script</a> on an oracle free tier VPS. I have the Minecraft server running, and can successfully ping the game server inside my game client via the VPS&#39;s address. However, whenever the tunnel is running, the Minecraft server can&#39;t connect to Yggdrasil (the Minecraft account authentication servers). Do y&#39;all know why this would happen and how to fix it? When I turn off the tunnel it can connect to the auth servers just fine.</p> <p>Currently, the only port being sent over the tunnel is Minecraft&#39;s TCP port, 25565. The VPS itself is only open to the ports for SSH, Wireguard, and Minecraft (all on TCP).</p> <p>I experimented with sending ports 443 and 80 over the tunnel, but then the VPS itself started behaving wacky and the tunnel stopped working altogether. I think it is probably unrelated to sending those ports, but I&#39;m not gon

## Firefly Data Importer with Docker Compose and Caddy
 - [https://www.reddit.com/r/selfhosted/comments/1fsdimf/firefly_data_importer_with_docker_compose_and](https://www.reddit.com/r/selfhosted/comments/1fsdimf/firefly_data_importer_with_docker_compose_and)
 - RSS feed: $source
 - date published: 2024-09-29T20:10:51+00:00

<!-- SC_OFF --><div class="md"><p>Does anyone have any experience with installing the Firefly III Data Importer with Docker Compose and Caddy? I&#39;ve followed the instructions from the documentation (<a href="https://docs.firefly-iii.org/how-to/data-importer/installation/docker/">Using Docker - Firefly III documentation (firefly-iii.org)</a>) but I&#39;m getting a 502 error. Firefly works fine but the data importer doesn&#39;t.</p> <p>I have already set <code>FIREFLY_III_URL</code> in <code>.importer.env</code> to <code>http://&lt;firefly container name&gt;:8080</code></p> <p>and<code>VANITY_URL</code> in <code>.importer.env</code> to <a href="http://localhost"><code>http://localhost</code></a></p> <p>my caddy is the standard:</p> <p><code>importer.{$MY_DOMAIN} {</code></p> <p><code>reverse_proxy firefly_iii_importer:8081</code></p> <p><code>}</code></p> <p>I&#39;m out of ideas of where it breaks :(</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/us

## Do you use any online database backup service?
 - [https://www.reddit.com/r/selfhosted/comments/1fsdflr/do_you_use_any_online_database_backup_service](https://www.reddit.com/r/selfhosted/comments/1fsdflr/do_you_use_any_online_database_backup_service)
 - RSS feed: $source
 - date published: 2024-09-29T20:07:12+00:00

<!-- SC_OFF --><div class="md"><p>Web server, or Vps can crash anytime. How do you backup your database?</p> <p>Do you use any database backup tool: - self hosted, or any tool in laptop/pc? or - online database backup tool?</p> <p>I am thinking to create a database backup tool, for daily database backup. My target is small sites, like, personal website, personal bolg site, small e-commerce, etc.</p> <p>Will you pay for this daily auto backup?</p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Lopsided-Juggernaut1"> /u/Lopsided-Juggernaut1 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fsdflr/do_you_use_any_online_database_backup_service/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fsdflr/do_you_use_any_online_database_backup_service/">[comments]</a></span>

## Starting my first home lab - want a good foundation.
 - [https://www.reddit.com/r/selfhosted/comments/1fscmer/starting_my_first_home_lab_want_a_good_foundation](https://www.reddit.com/r/selfhosted/comments/1fscmer/starting_my_first_home_lab_want_a_good_foundation)
 - RSS feed: $source
 - date published: 2024-09-29T19:31:59+00:00

<!-- SC_OFF --><div class="md"><p><strong>Here&#39;s my general plan, I would be interested to get input or see how others manage their home lab.</strong></p> <ol> <li>I regularly feel like I&#39;ve tarnished my host OS and reinstall with updated build scripts. To prevent doing this to my &quot;server&quot; I plan to keep docker services in categorized VM&#39;s and minimally effect the host.</li> <li>This is part of a two year long bailout from &quot;big tech&quot; services due to identify theft... I enjoy and value configuring proper security/privacy configs.</li> </ol> <p><strong>Host/server:</strong></p> <p>Gaming laptop with pop-os *familiar interface, enables me to physically interact if lost in the CLI.</p> <p><strong>Redundancy:</strong></p> <p>Data will be on Host PC, Rsync copied to external HD, that HD will be cloned and stored off site occasionally.</p> <p><strong>Access:</strong></p> <ul> <li>Server will have VPN or SSH in for management.</li> <li>Homarr (or similar) dashb

## Looking for a way to transfer up to 1tb of data through the cloud.
 - [https://www.reddit.com/r/selfhosted/comments/1fsbdji/looking_for_a_way_to_transfer_up_to_1tb_of_data](https://www.reddit.com/r/selfhosted/comments/1fsbdji/looking_for_a_way_to_transfer_up_to_1tb_of_data)
 - RSS feed: $source
 - date published: 2024-09-29T18:38:52+00:00

<!-- SC_OFF --><div class="md"><p>I’m starting a small business for data processing. I have a few customers that use me regularly for their data processing, this is really just a side gig then any thing else. The data they collect is huge, sometimes 500mb per file and sometimes theirs hundreds or thousands of files depending on the project. Until now I have been meeting them in person where they give me a hard drive with all the data then I return that hard drive after everything is processed. What would be much better is if there was a cloud service out there that could handle this much data, they would upload it, I would down load it and eventually upload finished products. Any ideas? I assume this much storage would cost a lot and I could figure a way to work that into my service price. Thanks! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Objective_Reality232"> /u/Objective_Reality232 </a> <br/> <span><a href="https://www.reddit.com/r/self

## Is there a free ELN that can be installed on Windows/without Docker?
 - [https://www.reddit.com/r/selfhosted/comments/1fsb4nf/is_there_a_free_eln_that_can_be_installed_on](https://www.reddit.com/r/selfhosted/comments/1fsb4nf/is_there_a_free_eln_that_can_be_installed_on)
 - RSS feed: $source
 - date published: 2024-09-29T18:28:07+00:00

<!-- SC_OFF --><div class="md"><p>I stumbled across eLabFTW and SciNote, but it seems like both of them require Docker to run on Windows. This is a problem for me; my server is a mini PC with 8GB RAM, Docker simply uses too much RAM for me to be constantly running it. </p> <p>I&#39;m looking for an ELN that I can install on my Windows 11 machine without Docker. any tips would be appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Heavy_Bridge_7449"> /u/Heavy_Bridge_7449 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fsb4nf/is_there_a_free_eln_that_can_be_installed_on/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fsb4nf/is_there_a_free_eln_that_can_be_installed_on/">[comments]</a></span>

## Any free MDM for a non-profit?
 - [https://www.reddit.com/r/selfhosted/comments/1fsayed/any_free_mdm_for_a_nonprofit](https://www.reddit.com/r/selfhosted/comments/1fsayed/any_free_mdm_for_a_nonprofit)
 - RSS feed: $source
 - date published: 2024-09-29T18:20:29+00:00

<!-- SC_OFF --><div class="md"><p>We have a NPO with about 80 users and we need to use MDM to control device &amp; user access to system settings, apply some GPOs, they are all windows devices and some are android, but we are mainly focusing on windows devices</p> <p>I&#39;ve searched for some of the most popular like Action1, Comodo one (Itarian), ManageEngine they are very generous up to 100 devices and 25 for Manage Engine, but unfortunately they are only RMM and doesn&#39;t allow locking down system settings and applying GPOs, are there any alternatives that work for us?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AhmedBarayez"> /u/AhmedBarayez </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fsayed/any_free_mdm_for_a_nonprofit/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fsayed/any_free_mdm_for_a_nonprofit/">[comments]</a></span>

## What tools do you use to ensure that your firewall rules are up and running all the time?
 - [https://www.reddit.com/r/selfhosted/comments/1fsaqfg/what_tools_do_you_use_to_ensure_that_your](https://www.reddit.com/r/selfhosted/comments/1fsaqfg/what_tools_do_you_use_to_ensure_that_your)
 - RSS feed: $source
 - date published: 2024-09-29T18:11:09+00:00

<!-- SC_OFF --><div class="md"><p>I don&#39;t know whether it&#39;s a wish or something like this exists. But say you have a server where all connections have the firewall rule DROP, except for a few others, like ssh TCP 22, VPN UDP 1194, etc. Mistakes happen, and some times more ports are open due to a configuration mistake, but it&#39;s important to notice.</p> <p>Is there a tool that will keep hammering the server with connection attempts on random ports, and then if it finds something other than the ports I specify open, it would notify me somehow?</p> <p>Quite frankly I was thinking I should write my own tool for this... part of me is sure that such tools exist.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TheQuantumPhysicist"> /u/TheQuantumPhysicist </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fsaqfg/what_tools_do_you_use_to_ensure_that_your/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/self

## Best alternative to YunoHost, specifically for users hosting behind CG-NAT via a proxy VPS
 - [https://www.reddit.com/r/selfhosted/comments/1fsam0u/best_alternative_to_yunohost_specifically_for](https://www.reddit.com/r/selfhosted/comments/1fsam0u/best_alternative_to_yunohost_specifically_for)
 - RSS feed: $source
 - date published: 2024-09-29T18:05:47+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone! I&#39;ve been using YunoHost for years already, but I&#39;m starting to get interested on switching to a system based on Docker, due to the fact that YunoHost depends on the latest stable version of Debian, and transitioning between one version and the next can sometimes takes upwards of a year, making applications slowly lose support during the transition. I would jump straight away to a barebones Docker-Compose setup, but I have several technical problems with that that prevent me from doing the jump directly.</p> <ol> <li>Because of availability issues in my area, and the storage rental cost of hosting everything on a VPS, I&#39;m currently forced to use a double-tier system instead. My main server is hosted at home, but because it&#39;s stuck behind CG-NAT (not even dynamic IP), I also need to rent the simplest VPS I can find solely to connect my home server to the open Internet, via Wireguard.</li> <li>The vast majority of Docker 

## Mail Backup
 - [https://www.reddit.com/r/selfhosted/comments/1fsai59/mail_backup](https://www.reddit.com/r/selfhosted/comments/1fsai59/mail_backup)
 - RSS feed: $source
 - date published: 2024-09-29T18:01:20+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I am currently looking for a simple way to back up and/or archive my mailboxes.</p> <p>Is there a free tool for this?</p> <p>Bonus points for:</p> <p>• Scheduled backup jobs</p> <p>• Runnable as a container</p> <p>• Integration with monitoring (it would be enough if a script could be triggered after execution)</p> <p>I work with macOS, but I would like to run the tool on a server so that the whole process is fully automated. Any suggestions?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bwljohannes"> /u/bwljohannes </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fsai59/mail_backup/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fsai59/mail_backup/">[comments]</a></span>

## Tailscale or alternative program usage
 - [https://www.reddit.com/r/selfhosted/comments/1fsa5xp/tailscale_or_alternative_program_usage](https://www.reddit.com/r/selfhosted/comments/1fsa5xp/tailscale_or_alternative_program_usage)
 - RSS feed: $source
 - date published: 2024-09-29T17:47:00+00:00

<!-- SC_OFF --><div class="md"><p>I am needing clarity. For my network to access npm and portainer, I should use something tailescale if I need remote access (normally I just remote into a seperate computer on my home network then access what I need). For things like jellyfin and my recipe server those are ok going through my domain. Is this correct? The issue is I have 2 other family members that will be accessing some of the sites and having to remember to connect to another program before accessing my domain would be problematic. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/theannihilator"> /u/theannihilator </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fsa5xp/tailscale_or_alternative_program_usage/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fsa5xp/tailscale_or_alternative_program_usage/">[comments]</a></span>

## Nextcloud behind NGINX Proxy
 - [https://www.reddit.com/r/selfhosted/comments/1fs9x08/nextcloud_behind_nginx_proxy](https://www.reddit.com/r/selfhosted/comments/1fs9x08/nextcloud_behind_nginx_proxy)
 - RSS feed: $source
 - date published: 2024-09-29T17:36:34+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’m completely new to the game and currently experimenting with Docker after previously installing everything bare-metal. Now I’m facing the following issue:</p> <p>I deployed a Debian VM on my Proxmox that currently runs Nginx Proxy Manager, Nextcloud, and AdGuard as containers. The VM has 12GB RAM and 4 CPU cores. As soon as I enable the SSL certificate on Nginx Proxy, along with Websocket and cache, the container becomes extremely slow, and almost nothing works anymore.</p> <p>Does anyone have an idea what might be causing this or how I could improve it? The setup is not in production yet.</p> <p>Deployed via docker-compose.</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OilPuzzleheaded5267"> /u/OilPuzzleheaded5267 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs9x08/nextcloud_behind_nginx_proxy/">[link]</a></span> &#32; <span><a href="ht

## Some love for Glance app.
 - [https://www.reddit.com/r/selfhosted/comments/1fs9rz0/some_love_for_glance_app](https://www.reddit.com/r/selfhosted/comments/1fs9rz0/some_love_for_glance_app)
 - RSS feed: $source
 - date published: 2024-09-29T17:30:41+00:00

<!-- SC_OFF --><div class="md"><p>Sometime back, the <a href="https://github.com/glanceapp/glance">Glance</a> app was announced <a href="https://www.reddit.com/r/selfhosted/comments/1cenjeu/glance_a_minimal_dashboard_that_puts_all_the/">here</a>. </p> <p>I have been loving it. I still use <a href="https://gethomepage.dev/">Homepage</a> for my internal dashboard, but for a quick &quot;What&#39;s going on in the world&quot; portal, I love Glance. </p> <p>Tell me what you think: <a href="https://meatmutts.com">meatmutts.com</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Big_Statistician2566"> /u/Big_Statistician2566 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs9rz0/some_love_for_glance_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs9rz0/some_love_for_glance_app/">[comments]</a></span>

## I made a small program to monitor your home IP and send an email to yourself when it changes.
 - [https://www.reddit.com/r/selfhosted/comments/1fs9inz/i_made_a_small_program_to_monitor_your_home_ip](https://www.reddit.com/r/selfhosted/comments/1fs9inz/i_made_a_small_program_to_monitor_your_home_ip)
 - RSS feed: $source
 - date published: 2024-09-29T17:19:43+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://github.com/TheDonSaysNah/checkhomeIP">https://github.com/TheDonSaysNah/checkhomeIP</a></p> <p>As the title says, a program to monitor your home IP and alert you if it changes due to your ISP. Great for people who don&#39;t have DDNS.</p> <p>I only use a Wireguard tunnel to get into my home server so knowing when the IP is changed is a must. So I made this. I hope it proves useful for people.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LiterallyNoPoint"> /u/LiterallyNoPoint </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs9inz/i_made_a_small_program_to_monitor_your_home_ip/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs9inz/i_made_a_small_program_to_monitor_your_home_ip/">[comments]</a></span>

## Anyone self hosting overleaf?
 - [https://www.reddit.com/r/selfhosted/comments/1fs9hvy/anyone_self_hosting_overleaf](https://www.reddit.com/r/selfhosted/comments/1fs9hvy/anyone_self_hosting_overleaf)
 - RSS feed: $source
 - date published: 2024-09-29T17:18:48+00:00

<!-- SC_OFF --><div class="md"><p>Overleaf is a LaTeX document editor. It’s great for collaboration. </p> <p>There is a hosted version, but it could also be self hosted. It looks like complicated though. Even docker compose is apparently not enough for reliable maintenance. </p> <p>Has anyone self hosted overleaf? How difficult is it?</p> <p>I don’t want to waste time.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/chaplin2"> /u/chaplin2 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs9hvy/anyone_self_hosting_overleaf/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs9hvy/anyone_self_hosting_overleaf/">[comments]</a></span>

## Self-Hosting a Container Registry
 - [https://www.reddit.com/r/selfhosted/comments/1fs9a8t/selfhosting_a_container_registry](https://www.reddit.com/r/selfhosted/comments/1fs9a8t/selfhosting_a_container_registry)
 - RSS feed: $source
 - date published: 2024-09-29T17:09:24+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fs9a8t/selfhosting_a_container_registry/"> <img src="https://external-preview.redd.it/b35-5R61_egecVTbogFz5df266Fk9oUKjp_2ybGhHeA.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=f9f3776e5f20bf3b353fb759aff0f6fe08bc0318" alt="Self-Hosting a Container Registry" title="Self-Hosting a Container Registry" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/der_gopher"> /u/der_gopher </a> <br/> <span><a href="https://www.youtube.com/watch?v=TGLfQZ9qRaI">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs9a8t/selfhosting_a_container_registry/">[comments]</a></span> </td></tr></table>

## how to give a Vmware static ip adree
 - [https://www.reddit.com/r/selfhosted/comments/1fs8ev8/how_to_give_a_vmware_static_ip_adree](https://www.reddit.com/r/selfhosted/comments/1fs8ev8/how_to_give_a_vmware_static_ip_adree)
 - RSS feed: $source
 - date published: 2024-09-29T16:31:11+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fs8ev8/how_to_give_a_vmware_static_ip_adree/"> <img src="https://a.thumbs.redditmedia.com/rhZGLIOYxf9j9oidFkIpD_R-yojhSYRC4zRDtn8KZr8.jpg" alt="how to give a Vmware static ip adree" title="how to give a Vmware static ip adree" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/2qye4ci4yrrd1.png?width=1041&amp;format=png&amp;auto=webp&amp;s=a7b9a12f0c35ec2957250aa168fe8b96cb711737">https://preview.redd.it/2qye4ci4yrrd1.png?width=1041&amp;format=png&amp;auto=webp&amp;s=a7b9a12f0c35ec2957250aa168fe8b96cb711737</a></p> <p>I want to to set up a mail server in my vm but it look ike it necessary to have an ip you can edit its ptr record . so my question if there any service offere ip adress could I linked to my vmware and I have acces to it </p> <p>note : priority for free ways . I know I have to invest to make but Im not enough confident to trust in my project that come to my mind in mi

## Outline (wiki), cloudflare, and oauth
 - [https://www.reddit.com/r/selfhosted/comments/1fs86zb/outline_wiki_cloudflare_and_oauth](https://www.reddit.com/r/selfhosted/comments/1fs86zb/outline_wiki_cloudflare_and_oauth)
 - RSS feed: $source
 - date published: 2024-09-29T16:21:34+00:00

<!-- SC_OFF --><div class="md"><p>X posted on <a href="/r/cloudflare">r/cloudflare</a></p> <p>I’m about at my wits end trying to install this (getoutline; outline/outline on GitHub). I have followed every tutorial available and continue to have issues and it all comes to setting the app up behind cloudlflare tunnels.</p> <p>I will admit, I am a complete newb who throws docker compose into portainer and prays it works but I have spent probably at least 24+ hours troubleshooting and doing endless research on how to get it to work. My issue is my lack of understanding surrounding how to allow Cloudflare tunnel to interact with an app that requires 3rd party authentication setup. I attempted to follow the guide on cloudflare to set up keycloak but at the end of the day after setting everything up, in Keycloak and cloudflare, my auth endpoint for keycloak “does not exist” even though it is what’s on the xml config…</p> <p>So many tutorials use caddy or ngnix or traefik. I don’t understand 

## Accessing zfs in a docker container
 - [https://www.reddit.com/r/selfhosted/comments/1fs7qfh/accessing_zfs_in_a_docker_container](https://www.reddit.com/r/selfhosted/comments/1fs7qfh/accessing_zfs_in_a_docker_container)
 - RSS feed: $source
 - date published: 2024-09-29T16:01:50+00:00

<!-- SC_OFF --><div class="md"><p>I am new to self hosting . I have proxmox running two vms 1. Truenas 2.debian server for docker containers I am running audio bookshelf as a docker container in debian vm . Whether i can use truenas zfs for volume for storing audiobooks for accessing in audiobook shelf</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Savings_Problem_7982"> /u/Savings_Problem_7982 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs7qfh/accessing_zfs_in_a_docker_container/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs7qfh/accessing_zfs_in_a_docker_container/">[comments]</a></span>

## Self-signed ssl certificate for local network
 - [https://www.reddit.com/r/selfhosted/comments/1fs7iw2/selfsigned_ssl_certificate_for_local_network](https://www.reddit.com/r/selfhosted/comments/1fs7iw2/selfsigned_ssl_certificate_for_local_network)
 - RSS feed: $source
 - date published: 2024-09-29T15:53:03+00:00

<!-- SC_OFF --><div class="md"><p>I want to create and upload ssl certificates to the servers I use for my local network (nextcloud, vaultwarden). I want to use these certificates with NPM.</p> <p>The local network will not be open to the outside in any way. I will connect from outside with VPN. I have seen solutions such as let&#39;s encrypt and duckdns, but I want to use the <a href="http://home.network">home.network</a> domain as the domain.</p> <p>I created a few certificates and uploaded them to npm, but it didn&#39;t work. How can I do it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/berkin88"> /u/berkin88 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs7iw2/selfsigned_ssl_certificate_for_local_network/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs7iw2/selfsigned_ssl_certificate_for_local_network/">[comments]</a></span>

## Accessing local domains with public TLD
 - [https://www.reddit.com/r/selfhosted/comments/1fs6yd3/accessing_local_domains_with_public_tld](https://www.reddit.com/r/selfhosted/comments/1fs6yd3/accessing_local_domains_with_public_tld)
 - RSS feed: $source
 - date published: 2024-09-29T15:28:28+00:00

<!-- SC_OFF --><div class="md"><p>Hi im trying to host two public facing domains with a TLD but also use that same tld for internal local services. These services i want to be able to type (ad.mydomain.com) while on the internal without access to the public </p> <p>I am currently using NPM, Adguard home and cloudflare.<br/> I am able to access my public domains fine with certs<br/> if i add the local site to nginx i understand it tries to push it to the public<br/> my adgaurd dns rewrites always say SSL cert name not recognized<br/> im also using DoH/DoT </p> <blockquote> <p>Adguard upstreams </p> </blockquote> <ul> <li><a href="https://dns.cloudflare.com/dns-query">https://dns.cloudflare.com/dns-query</a><br/> tls://one.one.one.one<br/> <a href="https://dns.google/dns-query">https://dns.google/dns-query</a><br/> <a href="https://dns.quad9.net/dns-query">https://dns.quad9.net/dns-query</a><br/> tls://dns.quad9.net<br/> 2620:fe::fe<br/> 2606:4700:4700::1112<br/> 1.1.1.1<br/> 9.9.9.9<br

## Watchtower alternative that doen't need 'latest' tag
 - [https://www.reddit.com/r/selfhosted/comments/1fs6i44/watchtower_alternative_that_doent_need_latest_tag](https://www.reddit.com/r/selfhosted/comments/1fs6i44/watchtower_alternative_that_doent_need_latest_tag)
 - RSS feed: $source
 - date published: 2024-09-29T15:08:40+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone!!</p> <p>We have the excellent <a href="https://containrrr.dev/watchtower/">Watchtower</a>, that keeps monitoring the BASE image of the containers and can update they to the latest version OR act as a monitor and send a notification if an update is available. And as said in docs, to verify the updates, watchtower needs to pull the new image to our local registry AND monitor the image that the container was previous launched. So, to effectively monitor the updates, you need to always use the tag &#39;latest&#39;, because if you set the image tag as a fixed one, never an update will hit it.</p> <p>But imagine a scenario where a blackout happened and your UPS just died. When the energy comes back again, and all your containers start boot again, they will try to use the local registry in search for the &quot;latest&quot; image, right? But if watchtower pulled the last one from registry, when the container start it will use the updated one, 

## Having issues with setting up SSL certificates using Nginx Proxy Manager?
 - [https://www.reddit.com/r/selfhosted/comments/1fs6fz9/having_issues_with_setting_up_ssl_certificates](https://www.reddit.com/r/selfhosted/comments/1fs6fz9/having_issues_with_setting_up_ssl_certificates)
 - RSS feed: $source
 - date published: 2024-09-29T15:05:57+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I setup a jellyfin server and allowed it remote access through jellyfin&#39;s settings. I can access my server from outside my network using the public IP and can access it using my local IP inside my network. I found out my router does not allow hair pinning or NAT loopback which means I can&#39;t access my public IP while in my network.</p> <p>I followed this guide: <a href="https://notthebe.ee/blog/easy-ssl-in-homelab-dns01/">https://notthebe.ee/blog/easy-ssl-in-homelab-dns01/</a> but I instead of using the local IP in duckdns I used my public IP.</p> <p>When I try adding an SSL certificate I get this error:</p> <pre><code>CommandError: Saving debug log to /tmp/letsencrypt-log/letsencrypt.log Some challenges have failed. Ask for help or search for solutions at https://community.letsencrypt.org. See the logfile /tmp/letsencrypt-log/letsencrypt.log or re-run Certbot with -v for more details. at /app/lib/utils.js:16:13 at ChildProcess.ex

## Introducing Elysian, a tool to back up your regularly used bookmarks from the bookmarks toolbar of your browser to your home lab.
 - [https://www.reddit.com/r/selfhosted/comments/1fs670a/introducing_elysian_a_tool_to_back_up_your](https://www.reddit.com/r/selfhosted/comments/1fs670a/introducing_elysian_a_tool_to_back_up_your)
 - RSS feed: $source
 - date published: 2024-09-29T14:54:58+00:00

<!-- SC_OFF --><div class="md"><p>Elysian Link: <a href="https://github.com/Aadityajoshi151/Elysian">https://github.com/Aadityajoshi151/Elysian</a></p> <p>Elysian Extension Link: <a href="https://github.com/Aadityajoshi151/Elysian-Extension">https://github.com/Aadityajoshi151/Elysian-Extension</a></p> <h3>How is it different from other similar services?</h3> <p>There are numerous other selfhosted services for bookmark management like Linkding, Linkwarden etc.</p> <p>Elysian is not an archival tool. It is primarily focused on backing up the bookmarks that reside in your browser&#39;s bookmarks bar and are used regularly.</p> <p>Elysian comes with a browser extension which allows you to Import/Export bookmarks to your home lab. Once successfully connected to your home lab, and bookmarks exported, any operation you perform on your Browser&#39;s bookmarks (Create, Re-order, Update, Delete) will be automatically updated on the server side as well.</p> <h3>Why use Elysian if I can sign in b

## What can I host better on a xeon e5 2680v4 than an intel n 100?
 - [https://www.reddit.com/r/selfhosted/comments/1fs5sy5/what_can_i_host_better_on_a_xeon_e5_2680v4_than](https://www.reddit.com/r/selfhosted/comments/1fs5sy5/what_can_i_host_better_on_a_xeon_e5_2680v4_than)
 - RSS feed: $source
 - date published: 2024-09-29T14:37:31+00:00

<!-- SC_OFF --><div class="md"><p>Mini PC N100 16gb ddr4 512gb sad</p> <p>Planning to get: Xeon e5-2680v4 32gb ram 2x 10TB hdds (more in the future)</p> <p>I already have a PC case and power supply from my old PC which I don’t use, both from MSI and in 10/10 quality I currently host a discord bot and a few game servers on the n100 mini pc, but it is slow in multi core tasks in a few modded games that support parallelism. I plan to make the xeon pc a nas as the old pc case is large and has a lot of room for multiple HDDs.</p> <p>So yeah, what can I host on the xeon to make a purchase worth it? I’m a software developer as well and want to host websites in the future too.</p> <p>I’m a little bit tight on money so that’s why I was thinking about the xeon. I think it has a nice starting price at 130€ (without HDDs)</p> <p>Edit: I will use proxmox if I get the xeon kit. I run ubuntu server on the mini pc and pterodactyl to run my bots and game servers.</p> </div><!-- SC_ON --> &#32; submitt

## Is there a reliable and cheap IP SSL certificates?
 - [https://www.reddit.com/r/selfhosted/comments/1fs5sem/is_there_a_reliable_and_cheap_ip_ssl_certificates](https://www.reddit.com/r/selfhosted/comments/1fs5sem/is_there_a_reliable_and_cheap_ip_ssl_certificates)
 - RSS feed: $source
 - date published: 2024-09-29T14:36:47+00:00

<!-- SC_OFF --><div class="md"><p>Any recommendations for IP SSL certificates? It should support IP instead of domain name.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/wavwetizc"> /u/wavwetizc </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs5sem/is_there_a_reliable_and_cheap_ip_ssl_certificates/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs5sem/is_there_a_reliable_and_cheap_ip_ssl_certificates/">[comments]</a></span>

## Help and advice a complete beginner to set up
 - [https://www.reddit.com/r/selfhosted/comments/1fs5qe7/help_and_advice_a_complete_beginner_to_set_up](https://www.reddit.com/r/selfhosted/comments/1fs5qe7/help_and_advice_a_complete_beginner_to_set_up)
 - RSS feed: $source
 - date published: 2024-09-29T14:34:06+00:00

<!-- SC_OFF --><div class="md"><p>Hi, i just joined this sub. I am a complete beginner noobs and zero experience in self hosting. </p> <p>My hardware :<br/> Intel i5-10400f (6c/12t)<br/> H410m Asus Prime<br/> RX 560 4gb Sapphire.<br/> 1 x 256GB 2.5 Sata SSD<br/> 3 x 1TB HDD</p> <p>i also have windows Pc for gaming and a laptop with intel celeron running MX Linux. </p> <p>Proposed usage. </p> <ol> <li>Use linux on the machine for learning and coding and daily driver and downloading.<br/></li> <li>Git and/or gitea. Can be accessed from any of my device on local network.<br/></li> <li>NAS. i can access downloaded files from any device.<br/></li> <li>Jellyfin.<br/></li> <li>website server for learning/ practicing. web and web app development.<br/></li> </ol> <p>I have zero experience in self hosting. I have tried jellyfin on windows as it is much easier to set up and getting it to detect the directory on my HDD. Currently using Linux Mint for daily driver except gaming, i will turn on my 

## [Question] Opinions About My Setup Security
 - [https://www.reddit.com/r/selfhosted/comments/1fs5kbi/question_opinions_about_my_setup_security](https://www.reddit.com/r/selfhosted/comments/1fs5kbi/question_opinions_about_my_setup_security)
 - RSS feed: $source
 - date published: 2024-09-29T14:26:20+00:00

<!-- SC_OFF --><div class="md"><p>Hello Everyone,</p> <p>I am new to Self-hosting for “small home use case” and want to ask about your experience to see if my setup is good or I need to change something.</p> <p>My setup:</p> <p>The web services like (Immich, Nextcloud, AdGaurd, Plex, .. etc .. ) are running on docker on a mini pc used as Home server. To access this web services I bought a domain and by using cloudflare I added subdomains (A record) then set it up using Nginx reverse proxy (subdomains = ip:port) with SSL (let’s encrypt) + and Tailscale VPN. I am not exposing any ports to internet, that’s why I can only access the web services by running Tailscale on the end-devices while using homeserver as exit node. Is this setup secure enough? Should I do something else? What you think about Cloudflare Tunnel? Is it better, so I can access the services without the need to run Tailscale vpn? Or what else I should/ca do?</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitt

## How to store & transfer files on a local remote disk in the same network? (my homeserver is 64 GB)
 - [https://www.reddit.com/r/selfhosted/comments/1fs56zz/how_to_store_transfer_files_on_a_local_remote](https://www.reddit.com/r/selfhosted/comments/1fs56zz/how_to_store_transfer_files_on_a_local_remote)
 - RSS feed: $source
 - date published: 2024-09-29T14:09:08+00:00

<!-- SC_OFF --><div class="md"><p>I have Raspberry Pi 5 for some apps like vaultwarden etc. however, i want to set up file cloud server like Immich or nextcloud.</p> <p>The problem is that i could not set it up, im don&#39;t know these networking things that good. (beginner at self hosting, this is all for hobby and i dont wanna pay for icloud).</p> <p>My setup is:</p> <ul> <li>At home theres a windows 11 pc with 2 TB storage.<br/></li> <li>Raspberry Pi 5 (64 GB)</li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/HasanJ996"> /u/HasanJ996 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs56zz/how_to_store_transfer_files_on_a_local_remote/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs56zz/how_to_store_transfer_files_on_a_local_remote/">[comments]</a></span>

## Can't open a port on my PC
 - [https://www.reddit.com/r/selfhosted/comments/1fs4zy2/cant_open_a_port_on_my_pc](https://www.reddit.com/r/selfhosted/comments/1fs4zy2/cant_open_a_port_on_my_pc)
 - RSS feed: $source
 - date published: 2024-09-29T14:00:15+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys!<br/> I wanted to open a certain port on my pc (25565) for self hosting a MC server, I just found this page and I haven&#39;t been on reddit for a while but this problem is driving me crazy.<br/> I used all methods to open a port, I added a rule on my router for this port, I tried to open the port both through Windows Firewall and windows console (cmd). I even tried to open this port with help of uTorrent (weird method but Im desperate to this point).<br/> All these methods and I still can&#39;t get any confirmation on any Port checker website that my port is open. Though when Im trying to check port in cmd I still can&#39;t find any confirmation that the port is open so I can&#39;t even understand what&#39;s the cause: my pc or the router. I also tried to open other ports (other than 25565), even used my second laptop but still no success...<br/> If you have any ideas how to fix this please help((</p> <p>My system is Windows 11, the router i

## Plesk migration problem
 - [https://www.reddit.com/r/selfhosted/comments/1fs4qq4/plesk_migration_problem](https://www.reddit.com/r/selfhosted/comments/1fs4qq4/plesk_migration_problem)
 - RSS feed: $source
 - date published: 2024-09-29T13:47:28+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>My Plesk migration is stuck at the beginning, so I close the migration screen until I wait for the end of the stop process. When I try to restart the migration, I get the error message &quot;Migration for the specified source server was already started. Please either continue this migration or finish it before you can start another one for the same source server.&quot; There are no processes panel-migrator-rsync.exe and terminate them. Both servers was rebooted but not fixed.</p> <p>Source server: win 2012 R2</p> <p>Plesk Obsidian Web Pro Edition Versiyon 18.0.56</p> <p>Destination Server: Windows Server 2022</p> <p>Plesk Obsidian Version 18.0.64</p> <p>How can I resolve this issue?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/emreozcan"> /u/emreozcan </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs4qq4/plesk_migration_problem/">[link]</a></span> &#32; <span><a href="htt

## Traefik Expose Only Certain Services when Connected to VPN
 - [https://www.reddit.com/r/selfhosted/comments/1fs3uru/traefik_expose_only_certain_services_when](https://www.reddit.com/r/selfhosted/comments/1fs3uru/traefik_expose_only_certain_services_when)
 - RSS feed: $source
 - date published: 2024-09-29T13:02:47+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I am setting up some new services for work, I have setup Traefik and Netbird on a VPS and exposed them - everything works very well, however, I have a few more services, lets say I want to expose homarr - but only do so when a user is connected to net bird, how can I limit exposure to homarr to only be redirected when connected via net bird? I am assuming I will need 2 Traefik containers?</p> <p>In addition, I would like to do the same for external services using the dynamic configuration file for Traefik, would this be achievable? Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/axoltlittle"> /u/axoltlittle </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs3uru/traefik_expose_only_certain_services_when/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs3uru/traefik_expose_only_certain_services_when/">[comments]</a></span>

## Looking for selfhosted Mailserver with suppport for idp and CalDav
 - [https://www.reddit.com/r/selfhosted/comments/1fs3t78/looking_for_selfhosted_mailserver_with_suppport](https://www.reddit.com/r/selfhosted/comments/1fs3t78/looking_for_selfhosted_mailserver_with_suppport)
 - RSS feed: $source
 - date published: 2024-09-29T13:00:45+00:00

<!-- SC_OFF --><div class="md"><p>Hi folks</p> <p>I&#39;m currently using Plesk with Plesk Premium Email which is based on Kolab.<br/> I&#39;m planning to migrate away from my vps and selfhost the mail service.</p> <p>I had planned to use mailcow but it seems that mailcow at the moment does not support authentication via SAML or oauth2 (OpenID Connect).</p> <p>I&#39;ve done some research and I couldn&#39;t find another mail server with the features I&#39;m looking for.</p> <p>Baiscally I want an E-Mail Server with support for external idp and CalDav.<br/> The calendars should be shareable, like known from Exchange.<br/> With Plesk Premium Mail, I had to create a Shared Calendar and gave all users access to it, which is also fine.</p> <p>At the moment, I&#39;m thinking about to use the nightly build of mailcow eventhough it is not my favouriced option but with the lack of other options it seems the only way to go.</p> <p>Do you know other e-mail solutions providing the needed functiona

## Does API access bypass authentication services?
 - [https://www.reddit.com/r/selfhosted/comments/1fs3ppu/does_api_access_bypass_authentication_services](https://www.reddit.com/r/selfhosted/comments/1fs3ppu/does_api_access_bypass_authentication_services)
 - RSS feed: $source
 - date published: 2024-09-29T12:55:44+00:00

<!-- SC_OFF --><div class="md"><p>So, title a little wonky, but if I install a RP authentication (authelia/authentik) does the API system still work or do I have to point it to the IP address vs the RP DNS name I have running for it. </p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bpreston683"> /u/bpreston683 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs3ppu/does_api_access_bypass_authentication_services/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs3ppu/does_api_access_bypass_authentication_services/">[comments]</a></span>

## How to host many low traffic services on the web
 - [https://www.reddit.com/r/selfhosted/comments/1fs3glu/how_to_host_many_low_traffic_services_on_the_web](https://www.reddit.com/r/selfhosted/comments/1fs3glu/how_to_host_many_low_traffic_services_on_the_web)
 - RSS feed: $source
 - date published: 2024-09-29T12:42:22+00:00

<!-- SC_OFF --><div class="md"><p>So I&#39;m a software engineer but I handle the website infra for my company. Admittedly I&#39;m very behind of the current state of hosting methods / web based hosting. I rented a managed dedicated server with plesk, thinking that it would be enough and in the meantime I would have the flexibility to host anything I would need. I don&#39;t have access to ssh since it&#39;s a managed but not customizable service. We got a few service needs (website, next cloud, custom php etc...) but low traffic. </p> <p>Turns out I got stuck in the situation where: I need managed services because I need the web facing server to be updated and secure; managed servers using plesk allow to easily host lamp web apps but as I soon I have so install multiple low traffic web apps I start needing nginx, docker, laravel, node etc... and these are kind of locked by the panel. Not to mention that I&#39;d like to host some small asp.net core apps and I got told that it would be 

## Newbie - Set up Immich and Jellyfin on VPS to use custom domain
 - [https://www.reddit.com/r/selfhosted/comments/1fs30ec/newbie_set_up_immich_and_jellyfin_on_vps_to_use](https://www.reddit.com/r/selfhosted/comments/1fs30ec/newbie_set_up_immich_and_jellyfin_on_vps_to_use)
 - RSS feed: $source
 - date published: 2024-09-29T12:16:21+00:00

<!-- SC_OFF --><div class="md"><p>I set up a VPS with a 5TB Storage Box and deployed Jellyfin and Immich on it. I followed this tutorial through everything: <a href="https://youtu.be/37eh6D-XDvQ?si=riEPS-D4DpIEtch8">https://youtu.be/37eh6D-XDvQ?si=riEPS-D4DpIEtch8</a> and it used a duckdns domain and set jellyfin and immich up to use that address. I would like to use a custom one that I bought from porkbun but have no clue how as the tutorial made it way easy to use the duckdns domain, all I had to do is paste my domain and the token they gave me. If someone could help me out and explain some things along the way, that would be much appreciated. Also, my VPS uses traefik to route the traffic through duckdns (sorry if this is wrong nomenclature), I know as much.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Derio_ai"> /u/Derio_ai </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs30ec/newbie_set_up_immich_and_jellyfin_on_v

## What's your backup strategy? 3/2/1/1
 - [https://www.reddit.com/r/selfhosted/comments/1fs2wqo/whats_your_backup_strategy_3211](https://www.reddit.com/r/selfhosted/comments/1fs2wqo/whats_your_backup_strategy_3211)
 - RSS feed: $source
 - date published: 2024-09-29T12:10:25+00:00

<!-- SC_OFF --><div class="md"><p>Hi All,</p> <p>Curious at what people are doing for self hosting backups, as part of my home lab I was intending on a proxmox 3 node cluster using ceph, I&#39;m curious if this would ever cover the first part of a 3/2/1 or 3/2/1/1 strategy.</p> <p>3 = 1 The original data (Node 1), 2 Data Copy #1 (Node 2), 3 Data Copy #2 (Node 3)<br/> 2 = 1 Media Type (Backup Server Storage Pool), 2 Media Type #2 (LTO Tape Archive / Hot Swapped 2.5&quot; SSD)<br/> 1 = Offsite copy (Backblaze/LTO Tape Archive/Hot Swapped 2.5&quot; SSD)<br/> 1 = Offline copy (LTO Tape Archive /Hot Swapped 2.5&quot; SSD)</p> <p>Interested to hear thoughts, experiences.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tja1980"> /u/tja1980 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs2wqo/whats_your_backup_strategy_3211/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs2wqo/whats_your_b

## Backup Solution at Home
 - [https://www.reddit.com/r/selfhosted/comments/1fs24ew/backup_solution_at_home](https://www.reddit.com/r/selfhosted/comments/1fs24ew/backup_solution_at_home)
 - RSS feed: $source
 - date published: 2024-09-29T11:21:24+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I have a server hosted at Strato, which I want to Backup to a NAS connected to a Raspberry Pi in my home network. I don&#39;t want to expose the home network to the Internet. Are there some nice self hosted backup tools, that can make a backup of my server to my home network periodically?</p> <p>Thanks in advance 🫶</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Hans-Adolf"> /u/Hans-Adolf </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs24ew/backup_solution_at_home/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs24ew/backup_solution_at_home/">[comments]</a></span>

## Nextcloud behind Nginx Proxy
 - [https://www.reddit.com/r/selfhosted/comments/1fs23bx/nextcloud_behind_nginx_proxy](https://www.reddit.com/r/selfhosted/comments/1fs23bx/nextcloud_behind_nginx_proxy)
 - RSS feed: $source
 - date published: 2024-09-29T11:19:23+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’m completely new to the game and currently experimenting with Docker after previously installing everything bare-metal. Now I’m facing the following issue:</p> <p>I deployed a Debian VM on my Proxmox that currently runs Nginx Proxy Manager, Nextcloud, and AdGuard as containers. The VM has 12GB RAM and 4 CPU cores. As soon as I enable the SSL certificate on Nginx Proxy, along with Websocket and cache, the container becomes extremely slow, and almost nothing works anymore.</p> <p>Does anyone have an idea what might be causing this or how I could improve it? The setup is not in production yet.</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OilPuzzleheaded5267"> /u/OilPuzzleheaded5267 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs23bx/nextcloud_behind_nginx_proxy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/co

## Installs not working on rpi 4
 - [https://www.reddit.com/r/selfhosted/comments/1fs1zgr/installs_not_working_on_rpi_4](https://www.reddit.com/r/selfhosted/comments/1fs1zgr/installs_not_working_on_rpi_4)
 - RSS feed: $source
 - date published: 2024-09-29T11:12:02+00:00

<!-- SC_OFF --><div class="md"><p>regardless of what I try to install on my rpi 4 it gets this error including updating it I have also tried reinstalling the os but that did not help</p> <p>and yes I do have a internet connection that works because I have conected to my rpi 4 via remote ssh</p> <p>how do I fix this any help appreciate</p> <p>udo apt install python3-pip</p> <p>Reading package lists... Done</p> <p>Building dependency tree... Done</p> <p>Reading state information... Done</p> <p>The following additional packages will be installed:</p> <p> javascript-common libexpat1-dev libjs-jquery libjs-sphinxdoc libjs-underscore libpython3-dev libpython3.11-dev python3-dev python3-setuptools python3-wheel python3.11-dev zlib1g-dev</p> <p>Suggested packages:</p> <p> python-setuptools-doc</p> <p>The following NEW packages will be installed:</p> <p> javascript-common libexpat1-dev libjs-jquery libjs-sphinxdoc libjs-underscore libpython3-dev libpython3.11-dev python3-dev python3-pip python

## Question for Tandoor users
 - [https://www.reddit.com/r/selfhosted/comments/1fs1y2y/question_for_tandoor_users](https://www.reddit.com/r/selfhosted/comments/1fs1y2y/question_for_tandoor_users)
 - RSS feed: $source
 - date published: 2024-09-29T11:09:30+00:00

<!-- SC_OFF --><div class="md"><p>My partner and I are starting to use Tandoor, which is so far great.</p> <p>One thing I can&#39;t figure out though is how I share the meal plan by default.</p> <p>Each time I add an entry I have to manually tell it to share with my partner so they can see it and vice versa.</p> <p>If we are members of the same &quot;space&quot; wouldn&#39;t that suggest the meal plan should be automatically shared?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/elliottmarter"> /u/elliottmarter </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs1y2y/question_for_tandoor_users/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs1y2y/question_for_tandoor_users/">[comments]</a></span>

## What are some handy tools I can host and expose to the internet
 - [https://www.reddit.com/r/selfhosted/comments/1fs1jif/what_are_some_handy_tools_i_can_host_and_expose](https://www.reddit.com/r/selfhosted/comments/1fs1jif/what_are_some_handy_tools_i_can_host_and_expose)
 - RSS feed: $source
 - date published: 2024-09-29T10:42:02+00:00

<!-- SC_OFF --><div class="md"><p>I am putting together a few containers and exposing them via Cloudflare and home page to make a kind of externally available toolbox, mainly for use by my colleagues.</p> <p>So far I&#39;ve got</p> <ul> <li>Starling PDF</li> <li>IT Tools</li> <li>Excalidraw</li> <li>Web Check</li> </ul> <p>I did want a container that lets me upload and edit powershell scripts but public users can only read and download...I tried VS Code but couldn&#39;t get the permissions how I wanted it, please recommend if you can.</p> <p>And any other handy tools you can recommend?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/elliottmarter"> /u/elliottmarter </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs1jif/what_are_some_handy_tools_i_can_host_and_expose/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs1jif/what_are_some_handy_tools_i_can_host_and_expose/">[comments]</a><

## Recommended guides for hardening a VPS/computer in the public network?
 - [https://www.reddit.com/r/selfhosted/comments/1fs1dqi/recommended_guides_for_hardening_a_vpscomputer_in](https://www.reddit.com/r/selfhosted/comments/1fs1dqi/recommended_guides_for_hardening_a_vpscomputer_in)
 - RSS feed: $source
 - date published: 2024-09-29T10:30:36+00:00

<!-- SC_OFF --><div class="md"><p>Hello guys!</p> <p>I just got into the self host thing this year about april and it&#39;s quite nice (immich, jellyfin, to name some) but I&#39;m running them on my nas with a custom OS on it and I&#39;m running everything by using tailscale. The reason is, that I&#39;m too afraid to do something wrong and expose my private data out in the internet without knowing it.</p> <p>Nevertheless I&#39;m curious how it works so I&#39;m planning on renting a VPS for some time and play around with it because I assume that it&#39;s a neat skill to be able to host a service in public anytime I want. So I&#39;d like to ask you: How did you learn to harden your VPS/server which is exposed in public? I&#39;m aware of some things like <code>fail2ban</code>, <code>SELinux</code>, revers proxy, <code>ufw</code>, set a limited amount of time for login retries etc. but I&#39;m always unsure: &quot;Is that enough what I&#39;m doing? Am I overseeing something?&quot;. Are th

## Calibre web automated with unraid working?
 - [https://www.reddit.com/r/selfhosted/comments/1fs16tr/calibre_web_automated_with_unraid_working](https://www.reddit.com/r/selfhosted/comments/1fs16tr/calibre_web_automated_with_unraid_working)
 - RSS feed: $source
 - date published: 2024-09-29T10:17:03+00:00

<!-- SC_OFF --><div class="md"><p>Has anyone managed to get this working with unraid?</p> <p>I am using the image from CA and it installs fine but I cannot access the web ui. I have tried this with linking to a previous calibre library db. And then when this didn&#39;t work with a fresh install linking to empty folders (the docs say that it can seg everything up)</p> <p>This also didn&#39;t work with the webui.</p> <p>Any ideas or tips? Have I misunderstood? Do I need a new calibre library set up first?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nicesliceoice"> /u/nicesliceoice </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs16tr/calibre_web_automated_with_unraid_working/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs16tr/calibre_web_automated_with_unraid_working/">[comments]</a></span>

## Transferring a self-hosted microblogging platform
 - [https://www.reddit.com/r/selfhosted/comments/1fs15bx/transferring_a_selfhosted_microblogging_platform](https://www.reddit.com/r/selfhosted/comments/1fs15bx/transferring_a_selfhosted_microblogging_platform)
 - RSS feed: $source
 - date published: 2024-09-29T10:13:57+00:00

<!-- SC_OFF --><div class="md"><p>So I haven&#39;t started building the self-hosted micrblogging (like mastodon). </p> <p>But since I will use old computer to make a home lab, I am wondering if there comes a day I have to move everything to a new (and maybe) dedicated server, Can all my data and registration info, etc, easily transferred to the new server?</p> <p>Like my mastodon account will still be there and can be logged in using the same credential.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok_Opposite753"> /u/Ok_Opposite753 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs15bx/transferring_a_selfhosted_microblogging_platform/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs15bx/transferring_a_selfhosted_microblogging_platform/">[comments]</a></span>

## PiGallery2 Dockerised Video Transcoding/Indexing Issue
 - [https://www.reddit.com/r/selfhosted/comments/1fs0xdi/pigallery2_dockerised_video_transcodingindexing](https://www.reddit.com/r/selfhosted/comments/1fs0xdi/pigallery2_dockerised_video_transcodingindexing)
 - RSS feed: $source
 - date published: 2024-09-29T09:58:26+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fs0xdi/pigallery2_dockerised_video_transcodingindexing/"> <img src="https://b.thumbs.redditmedia.com/nQXwPRDhpbKaAeJneDnyjIR4_sEt95orQsdcb5Qr17k.jpg" alt="PiGallery2 Dockerised Video Transcoding/Indexing Issue" title="PiGallery2 Dockerised Video Transcoding/Indexing Issue" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey all,</p> <p>Anyone familiar with PiGallery2 (<a href="https://bpatrik.github.io/pigallery2/">https://bpatrik.github.io/pigallery2/</a>) directory based self-hosted photo gallery? Its a great webapp for viewing photos based on your own folder structure, and works well, however I have one major issue I&#39;m not sure how to resolve (and not sure how to contact the developer).</p> <p>You can set the app to transcode certain file formats, and not transcode others (if I&#39;m reading the documentation right)</p> <p><a href="https://preview.redd.it/qukqc4iw0qrd1.png?width=1535&amp;format=png&amp;

## Are those specs enough?
 - [https://www.reddit.com/r/selfhosted/comments/1fs0plt/are_those_specs_enough](https://www.reddit.com/r/selfhosted/comments/1fs0plt/are_those_specs_enough)
 - RSS feed: $source
 - date published: 2024-09-29T09:42:02+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fs0plt/are_those_specs_enough/"> <img src="https://preview.redd.it/sba66irgyprd1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=036520c791f10e0f5eefd6086b204f2fd9f498ce" alt="Are those specs enough?" title="Are those specs enough?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Here is a quotation I got for a self hosted home server. I&#39;m going run the following stuffs on this server,</p> <blockquote> <p>Jellyfin (Audio only, mostly lossless) 3 discord bots (personal) Adguard Home And a network file manager (I didn&#39;t decided which one to use yet. Suggest me some.) Cloudflare Tunnels for exposing to internet (for now).</p> </blockquote> <p>Do u think it&#39;s enough to process all those stuffs? Don&#39;t worry about the storage, I&#39;ll upgrade it later.</p> <p>If additional information needed, feel free to ask 🙂</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/c

## Multiple wordpress instances each require its onw nginx or not?
 - [https://www.reddit.com/r/selfhosted/comments/1fs0pbc/multiple_wordpress_instances_each_require_its_onw](https://www.reddit.com/r/selfhosted/comments/1fs0pbc/multiple_wordpress_instances_each_require_its_onw)
 - RSS feed: $source
 - date published: 2024-09-29T09:41:23+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m hosting a few WordPress instances and currently, they&#39;re behind NPM (nginx proxy manager) and everything is in Docker. I use docker-compose where I use the bitnami/wordpress-nginx image. If I understand correctly this image includes the WordPress itself plus a lightweight nginx that is booted up to serve the WordPress. Now my question is if I had 10 websites using that image, I assume that means I&#39;d have 10 Nginx instances running, each serving its respective WordPress. Would that be heavier in resource usage and should I instead have one nginx that serves all the WordPress sites and I only have the official WordPress image used within my docker-compose.yml configs?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/daredevlil"> /u/daredevlil </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs0pbc/multiple_wordpress_instances_each_require_its_onw/">[link]</a></span> &#32; <span

## Tailscale vs WG-easy
 - [https://www.reddit.com/r/selfhosted/comments/1fs0nis/tailscale_vs_wgeasy](https://www.reddit.com/r/selfhosted/comments/1fs0nis/tailscale_vs_wgeasy)
 - RSS feed: $source
 - date published: 2024-09-29T09:37:23+00:00

<!-- SC_OFF --><div class="md"><p>Currently I&#39;m hosting a wireguard container using WG-easy which is really simple, fast and I can access my local network via this container. Now I read a lot of people in this forum that are suggesting to use Tailscale and the advantage to me would be that it has a mesh network so if my containers goes down one of the other servers in my network could continue to work and I would still be able to access my local network from a remote location. </p> <p>This all seemed very promising but I see some disadvantages as well. </p> <ol> <li><p>The public keys are managed by an external company (Tailscale.com) which means in theory they could swap a key without you noticing (Who is constantly checking their listed public keys) and act as a men in the middle?</p></li> <li><p>If you don&#39;t open the correct ports (Which is not in the docker compose examples) everything will connect through a relay server managed by the company (Tailscale.com) which means b

## Is the built-in authentication in the *arr suite safe enough when exposed to the internet ?
 - [https://www.reddit.com/r/selfhosted/comments/1fs0f17/is_the_builtin_authentication_in_the_arr_suite](https://www.reddit.com/r/selfhosted/comments/1fs0f17/is_the_builtin_authentication_in_the_arr_suite)
 - RSS feed: $source
 - date published: 2024-09-29T09:18:56+00:00

<!-- SC_OFF --><div class="md"><p>I was wondering what the consensus is regarding using the built-in authentication of the *arr apps when exposed to the internet using a reverse proxy ? </p> <p>If not, any suggestion to improve the security without resorting to a VPN ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ValouMazMaz"> /u/ValouMazMaz </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs0f17/is_the_builtin_authentication_in_the_arr_suite/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fs0f17/is_the_builtin_authentication_in_the_arr_suite/">[comments]</a></span>

## What services should I rent a VPS from Digital Ocean for?
 - [https://www.reddit.com/r/selfhosted/comments/1fs03gq/what_services_should_i_rent_a_vps_from_digital](https://www.reddit.com/r/selfhosted/comments/1fs03gq/what_services_should_i_rent_a_vps_from_digital)
 - RSS feed: $source
 - date published: 2024-09-29T08:54:32+00:00

<!-- SC_OFF --><div class="md"><p>tl:dr; What can I host on Digital Ocean VPS that will help me, and how does a self-hosted or VPS hosted VPN node help me?</p> <p>as the question above states:</p> <p>Right now without getting too deep into the stacks:</p> <p>I have pfsense + haproxy + acme certificates for all my docker services. All the usual stuff.</p> <p>I ran into an issue where teamviewer, my old reliable platform, keeps locking me out claiming I&#39;m using their software for a commercial purpose, when really I&#39;m just connecting into linux vms.</p> <p>So I got fed up and looked into alternative solutions, and I came across Rustdesk. Within a few hours I had everything back up and running.</p> <p>The advantage of TeamViewer is that it was my all in one backup solution that could go through firewalls. Locally I prefer Parsec, but that doesn&#39;t work as a linux host, and barely as a mac host. Rustdesk could provide a potential solution, however I can&#39;t access it outside o

## Selfhosted alternative to Asana or something BETTER
 - [https://www.reddit.com/r/selfhosted/comments/1frzzme/selfhosted_alternative_to_asana_or_something](https://www.reddit.com/r/selfhosted/comments/1frzzme/selfhosted_alternative_to_asana_or_something)
 - RSS feed: $source
 - date published: 2024-09-29T08:46:18+00:00

<!-- SC_OFF --><div class="md"><p>How do you guys manage all your personal projects? Not as an employee or in an organization perspective. I tried Taiga.io which is really good compared to everything I found online but I find it a bit complicated and the UI settings is filled with too much information, some of which I don’t even understand. </p> <p>Main purpose for me is to use this as a personal project management tool to track and work on my goals. If there is a mobile app to compensate the option then I’m even willing to pay for it. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Michaelscarn69-"> /u/Michaelscarn69- </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1frzzme/selfhosted_alternative_to_asana_or_something/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1frzzme/selfhosted_alternative_to_asana_or_something/">[comments]</a></span>

## I am looking for a sbc that has hardware cryptography acceleration (chacha & rsa-256 or better) and is less than $50.
 - [https://www.reddit.com/r/selfhosted/comments/1frzu7a/i_am_looking_for_a_sbc_that_has_hardware](https://www.reddit.com/r/selfhosted/comments/1frzu7a/i_am_looking_for_a_sbc_that_has_hardware)
 - RSS feed: $source
 - date published: 2024-09-29T08:34:28+00:00

<!-- SC_OFF --><div class="md"><p>Obviously more memory and more cores is a plus as well. Prefer 100% opensource with good support.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/frankoz95967943"> /u/frankoz95967943 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1frzu7a/i_am_looking_for_a_sbc_that_has_hardware/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1frzu7a/i_am_looking_for_a_sbc_that_has_hardware/">[comments]</a></span>

## How to Install PhotoPrism and Full Walkthrough for Beginners (2024)
 - [https://www.reddit.com/r/selfhosted/comments/1fryugm/how_to_install_photoprism_and_full_walkthrough](https://www.reddit.com/r/selfhosted/comments/1fryugm/how_to_install_photoprism_and_full_walkthrough)
 - RSS feed: $source
 - date published: 2024-09-29T07:20:38+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fryugm/how_to_install_photoprism_and_full_walkthrough/"> <img src="https://external-preview.redd.it/WAXJqBz6wmkwi6FZVAchvzDAMiLKQgPe4BVR67Rv_3Q.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=7ab592e1ab83e70a82d323339d5e257b3b53fa7e" alt="How to Install PhotoPrism and Full Walkthrough for Beginners (2024)" title="How to Install PhotoPrism and Full Walkthrough for Beginners (2024)" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DevilsDesigns"> /u/DevilsDesigns </a> <br/> <span><a href="https://www.youtube.com/watch?v=qHNsHwieMrE">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fryugm/how_to_install_photoprism_and_full_walkthrough/">[comments]</a></span> </td></tr></table>

## Homepage widgets/services for remote servers via tailscale?
 - [https://www.reddit.com/r/selfhosted/comments/1frxora/homepage_widgetsservices_for_remote_servers_via](https://www.reddit.com/r/selfhosted/comments/1frxora/homepage_widgetsservices_for_remote_servers_via)
 - RSS feed: $source
 - date published: 2024-09-29T05:58:12+00:00

<!-- SC_OFF --><div class="md"><p>Has anyone managed to run Homepage widgets for services on remote servers accessed via tailscale?</p> <p>I&#39;ve tried tailscale&#39;s docker setup with home by adding &quot;network_mode: service:homepage&quot; and, while that connects my homepage to tailscale, I no longer can directly access homepage without also running tailscale. I&#39;d like to be able to locally access homepage without needing to be online via tailscale.</p> <p>Anyone have anything similar working for them?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/boobajoob"> /u/boobajoob </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1frxora/homepage_widgetsservices_for_remote_servers_via/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1frxora/homepage_widgetsservices_for_remote_servers_via/">[comments]</a></span>

## Need Help with a problem Self-Hosting Websites. 2 Domains on Cloudpanel VMs, Nginx Proxy Manager, Cloudflare. Second Domain gets 502 error
 - [https://www.reddit.com/r/selfhosted/comments/1frwz4r/need_help_with_a_problem_selfhosting_websites_2](https://www.reddit.com/r/selfhosted/comments/1frwz4r/need_help_with_a_problem_selfhosting_websites_2)
 - RSS feed: $source
 - date published: 2024-09-29T05:08:45+00:00

<!-- SC_OFF --><div class="md"><p>I have set up a home server that runs Proxmox. Proxmox is hosting a VM that runs Nginx Proxy Manager in Docker Desktop. I have Cloudpanel installed in another VM. I have 2 domain names registered with Cloudflare (which are pointed to the NPM Server), and Cloudflare is issuing SSL Certificates. I followed a video tutorial and was able to get a WordPress site up and running pretty easily. The 1st Domain name reaches that site as expected. I tried to set up a second website using Drupal, using the exact same procedure. But when I go to that site(using the 2nd Domain name), I get a 502 error. I have tried many ideas of what might be wrong, even recreating the site on a separate Cloud Panel instance, but for some reason, I can&#39;t get NPM to forward the 2nd Domain to the 2nd site. Anyone have a similar setup that could provide assistance? I don&#39;t know NGINX or Cloudpanel very well, I&#39;m just trying to learn it, but I suspect I need to do something

## Help creating VM on cockpit-project
 - [https://www.reddit.com/r/selfhosted/comments/1frw9z9/help_creating_vm_on_cockpitproject](https://www.reddit.com/r/selfhosted/comments/1frw9z9/help_creating_vm_on_cockpitproject)
 - RSS feed: $source
 - date published: 2024-09-29T04:23:16+00:00

<!-- SC_OFF --><div class="md"><p>I have been scouring the web for hours trying to find the solution for this. I am trying to create a VM on a storage pool I created, but it always gives this same error no matter what I do. Please help me!!</p> <pre><code>Creation of VM VM_1 failed ERROR unsupported configuration: storage type &#39;dir&#39; requires use of storage format &#39;fat&#39; Domain installation does not appear to have been successful. If it was, you can restart your domain by running: virsh --connect qemu:///system start VM_1 otherwise, please restart your installation. </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Downtown-Lettuce-736"> /u/Downtown-Lettuce-736 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1frw9z9/help_creating_vm_on_cockpitproject/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1frw9z9/help_creating_vm_on_cockpitproject/">[comments]</a></span>

## My Homelab, September 2024 (TrueNAS, Proxmox, Tailscale, a 2014 Mac Mini, and more)
 - [https://www.reddit.com/r/selfhosted/comments/1frvnlr/my_homelab_september_2024_truenas_proxmox](https://www.reddit.com/r/selfhosted/comments/1frvnlr/my_homelab_september_2024_truenas_proxmox)
 - RSS feed: $source
 - date published: 2024-09-29T03:45:00+00:00

<!-- SC_OFF --><div class="md"><p>Hi folks, I wrote up a summary of my homelab as of September 2024: <a href="https://alexklibisz.com/2024/09/27/homelab-september-2024">https://alexklibisz.com/2024/09/27/homelab-september-2024</a></p> <p>After ~10 years of homelabing and self-hosting, I think my setup has mostly converged to one that&#39;s a good balance of useful, maintainable, and affordable. If anyone takes the time to read, I&#39;d be happy and curious to hear questions, feedback, tips, etc.!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/elastiknn"> /u/elastiknn </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1frvnlr/my_homelab_september_2024_truenas_proxmox/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1frvnlr/my_homelab_september_2024_truenas_proxmox/">[comments]</a></span>

## Open Source Cursor AI Alternative
 - [https://www.reddit.com/r/selfhosted/comments/1frvkxk/open_source_cursor_ai_alternative](https://www.reddit.com/r/selfhosted/comments/1frvkxk/open_source_cursor_ai_alternative)
 - RSS feed: $source
 - date published: 2024-09-29T03:40:32+00:00

<!-- SC_OFF --><div class="md"><p>Been using this for quite few days. Good experience so far and it supports Local LLM&#39;s as well.</p> <p>Link: <a href="https://github.com/trypear/pearai-app">https://github.com/trypear/pearai-app</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Uiqueblhats"> /u/Uiqueblhats </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1frvkxk/open_source_cursor_ai_alternative/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1frvkxk/open_source_cursor_ai_alternative/">[comments]</a></span>

## My current homelab setup (constructive criticism of the diagram would be appreciated)
 - [https://www.reddit.com/r/selfhosted/comments/1frv4gl/my_current_homelab_setup_constructive_criticism](https://www.reddit.com/r/selfhosted/comments/1frv4gl/my_current_homelab_setup_constructive_criticism)
 - RSS feed: $source
 - date published: 2024-09-29T03:13:21+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1frv4gl/my_current_homelab_setup_constructive_criticism/"> <img src="https://preview.redd.it/mux9bweq0ord1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=c6358f84fc0e08200b5cdf7165ab28f26280fb3b" alt="My current homelab setup (constructive criticism of the diagram would be appreciated)" title="My current homelab setup (constructive criticism of the diagram would be appreciated)" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Neither_Adeptness579"> /u/Neither_Adeptness579 </a> <br/> <span><a href="https://i.redd.it/mux9bweq0ord1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1frv4gl/my_current_homelab_setup_constructive_criticism/">[comments]</a></span> </td></tr></table>

## Wanting to host a single HTML page online using Android tablet with cellular data as a server
 - [https://www.reddit.com/r/selfhosted/comments/1fru5ds/wanting_to_host_a_single_html_page_online_using](https://www.reddit.com/r/selfhosted/comments/1fru5ds/wanting_to_host_a_single_html_page_online_using)
 - RSS feed: $source
 - date published: 2024-09-29T02:17:00+00:00

<!-- SC_OFF --><div class="md"><p>Partly I just want to see if it&#39;s possible, but I also really like the idea of hosting my own websites especially if I can do it with some of the unused devices I have sitting idly by. I currently live in a converted bus and get the majority of my electricity from solar, but even for my current use this is sometimes not sufficient. This is why I opted not to use my HP desktop pc as a server and chose to go with a Samsung Galaxy tablet. </p> <p>I first went to ChatGPT to find out, first, if it&#39;s possible to to use an Android tablet as a web server, and, if so, how do I do it? The bot assured me that it is indeed possible, and recommended that I install an app called Termux for setting up a server on the device. Straight out of the gate I was having problems with permissions and maybe half of the commands ChatGPT was giving me failed due to permission errors.</p> <p>The more I looked into it, the more it looked like I was going to have to root t

## Trouble creating bind mount?
 - [https://www.reddit.com/r/selfhosted/comments/1fru0rj/trouble_creating_bind_mount](https://www.reddit.com/r/selfhosted/comments/1fru0rj/trouble_creating_bind_mount)
 - RSS feed: $source
 - date published: 2024-09-29T02:10:04+00:00

<!-- SC_OFF --><div class="md"><p>It&#39;s nodejs docker container i made. I tried creating that same bind mount on postgres and busybox containers and it worked. My container has /public folder and i mount /public folder, but shouldnt that host /public folder just overwrite the one in the container? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Delvisreddit"> /u/Delvisreddit </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fru0rj/trouble_creating_bind_mount/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fru0rj/trouble_creating_bind_mount/">[comments]</a></span>

## EasyDocker - Auto Installer & Management for Docker based privacy apps (Linux Terminal)
 - [https://www.reddit.com/r/selfhosted/comments/1frtl6o/easydocker_auto_installer_management_for_docker](https://www.reddit.com/r/selfhosted/comments/1frtl6o/easydocker_auto_installer_management_for_docker)
 - RSS feed: $source
 - date published: 2024-09-29T01:46:00+00:00

<!-- SC_OFF --><div class="md"><p>Hey fellow self hosters!</p> <p>I&#39;ve decided put this project out the the public in hopes that people will find it useful and also for it to evolve!</p> <p>My main goal was to setup privacy based open source platforms for my own personal use to take back control of my online data and I love to automate things so it has evolved into a full platform for managing docker applications. </p> <p>I wanted to make something myself that worked in the way I was familiar with which was using an old fashioned Linux terminal. Before starting I was unaware of other platforms similar, and I felt compelled to create this even if there are others doing similar things.</p> <p>I was inspired by the YouTuber : <a href="https://www.youtube.com/c/AwesomeOpenSource">AwesomeOpenSource</a> who showcases and shows the setup process for lots of Open Source applications available on the internet.</p> <p>I found that AwesomeOpenSource also created a <a href="https://wiki.opens

## LAN-wide access to docker services
 - [https://www.reddit.com/r/selfhosted/comments/1frthzr/lanwide_access_to_docker_services](https://www.reddit.com/r/selfhosted/comments/1frthzr/lanwide_access_to_docker_services)
 - RSS feed: $source
 - date published: 2024-09-29T01:40:59+00:00

<!-- SC_OFF --><div class="md"><h1>Question:</h1> <h1>How are y&#39;all exposing a docker service from one pc too another locally?</h1> <h1>--------------------------------------------------------------------------------------</h1> <p><strong>I just want any PC on my local network access a docker compose web gui.</strong></p> <p><em>I am &quot;lost in the sauce&quot; at this point, days of docs, videos, VM lab tests. This is me simplifying the question, admitting defeat, and asking the experts lol.</em></p> <p><em>Learned a lot on the way, just not getting this simple task done.</em></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PossibleCulture4329"> /u/PossibleCulture4329 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1frthzr/lanwide_access_to_docker_services/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1frthzr/lanwide_access_to_docker_services/">[comments]</a></span>

## FOSS or Self hosted Interior Design?
 - [https://www.reddit.com/r/selfhosted/comments/1frt6sp/foss_or_self_hosted_interior_design](https://www.reddit.com/r/selfhosted/comments/1frt6sp/foss_or_self_hosted_interior_design)
 - RSS feed: $source
 - date published: 2024-09-29T01:23:09+00:00

<!-- SC_OFF --><div class="md"><p>For basic and community design of a street there is <a href="https://github.com/streetmix/streetmix/">StreetMix</a> but I can&#39;t seem to find something similar for Interior Design.</p> <p>Is there any equivalent that is FOSS or self-hostable? If not, what is the next best thing? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jacobburrell"> /u/jacobburrell </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1frt6sp/foss_or_self_hosted_interior_design/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1frt6sp/foss_or_self_hosted_interior_design/">[comments]</a></span>

## self-hosted photo app with photo filtering
 - [https://www.reddit.com/r/selfhosted/comments/1frszih/selfhosted_photo_app_with_photo_filtering](https://www.reddit.com/r/selfhosted/comments/1frszih/selfhosted_photo_app_with_photo_filtering)
 - RSS feed: $source
 - date published: 2024-09-29T01:12:03+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I recently switched from iPhone to Android and I don&#39;t like the Google Photos application, so I took on the task of looking for an application that is hosted on my own server to manage my photo library. I loved the MacOS application for photos because it had a function that I used a lot, creating an album where all the photos that were not in any album would be placed, which allowed me to organize my photo library. I tried several applications such as: PhotoPrism, lychee, Photoview etc. None have this function. Do you know any application that has this function? Greetings</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CyberBorder"> /u/CyberBorder </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1frszih/selfhosted_photo_app_with_photo_filtering/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1frszih/selfhosted_photo_app_with_photo_filtering/">

## Socket.io, Websockets, Nginx Proxy Manager
 - [https://www.reddit.com/r/selfhosted/comments/1frsxjr/socketio_websockets_nginx_proxy_manager](https://www.reddit.com/r/selfhosted/comments/1frsxjr/socketio_websockets_nginx_proxy_manager)
 - RSS feed: $source
 - date published: 2024-09-29T01:09:02+00:00

<!-- SC_OFF --><div class="md"><p>Seriously guys, have anyone managed to get Websockets or Socket.io working behind Nginx Proxy Manager?</p> <p>For a few years I have this problem, I have tried many configs and it just won&#39;t work.</p> <p>Socket.io is working locally, but when on the domain proxied by NPM it just won&#39;t work.</p> <p>It either throws &quot;WebSocket is closed before the connection is established.&quot;</p> <p>Or simply a &quot;failed&quot; error.</p> <p>Any tips?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PTwolfy"> /u/PTwolfy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1frsxjr/socketio_websockets_nginx_proxy_manager/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1frsxjr/socketio_websockets_nginx_proxy_manager/">[comments]</a></span>

## radarr + nzb360
 - [https://www.reddit.com/r/selfhosted/comments/1frsecb/radarr_nzb360](https://www.reddit.com/r/selfhosted/comments/1frsecb/radarr_nzb360)
 - RSS feed: $source
 - date published: 2024-09-29T00:39:35+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I use the combo jackette/radaar/nzb360 or lunasea combo. I&#39;d like to find my Indexer&#39;s list of the latest release. I know that in radar as well as nzb there are suggestions and proposals for films, but that does not correspond to what I am looking for.</p> <p>thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lstflg"> /u/lstflg </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1frsecb/radarr_nzb360/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1frsecb/radarr_nzb360/">[comments]</a></span>

