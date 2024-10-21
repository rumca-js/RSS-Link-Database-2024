# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Redirect docker container traffic with iptables
 - [https://www.reddit.com/r/selfhosted/comments/1g8by0z/redirect_docker_container_traffic_with_iptables](https://www.reddit.com/r/selfhosted/comments/1g8by0z/redirect_docker_container_traffic_with_iptables)
 - RSS feed: $source
 - date published: 2024-10-20T23:19:36+00:00

<!-- SC_OFF --><div class="md"><p>basically I&#39;m trying to route all my server&#39;s tcp traffic through a transparent proxy. The following works on the host:</p> <p><code>sudo iptables -t nat -A OUTPUT -p tcp -m owner ! --uid-owner root -j REDIRECT --to-port 1080</code></p> <p>However this does not affect my docker containers. I read that docker skips all the chains after PREROUTING so here&#39;s what I tried so far to get it to work inside docker:</p> <p><code>sudo iptables -t nat -A PREROUTING -p tcp -j REDIRECT --to-port 1080</code></p> <p>And that seems to do something, but all my requests inside a container result in a <code>connection refused</code> error. What am I doing wrong? Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Bizsel"> /u/Bizsel </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g8by0z/redirect_docker_container_traffic_with_iptables/">[link]</a></span> &#32; <span><a href="https://www.reddit.

## Need Help Setting Up a Private VPN Network with Netmaker, Docker, and HTTPS Access
 - [https://www.reddit.com/r/selfhosted/comments/1g8bkto/need_help_setting_up_a_private_vpn_network_with](https://www.reddit.com/r/selfhosted/comments/1g8bkto/need_help_setting_up_a_private_vpn_network_with)
 - RSS feed: $source
 - date published: 2024-10-20T23:01:28+00:00

<!-- SC_OFF --><div class="md"><p><strong>Hi everyone,</strong></p> <p>I’m looking to set up a private network using <strong>Netmaker</strong> that only I can access through a VPN tunnel, enabling me to connect to my websites securely. I’m coming from using Cloudflare tunneling, and I’m finding this new setup quite challenging.</p> <p><strong>What I Want to Achieve</strong>:</p> <ul> <li><strong>Private Network</strong>: Establish a VPN tunnel with Netmaker that ensures only I can access my private resources.</li> <li><strong>Access to Websites</strong>: Connect to my websites, which are running in <strong>Docker containers</strong>, through this VPN.</li> <li><strong>Added Security</strong>: Enable HTTPS for my websites to ensure secure communication.</li> </ul> <p><strong>Current Knowledge</strong>:</p> <ul> <li>I have some experience with Cloudflare tunneling and <strong>docker compose</strong> to an extent, but I’m relatively new to VPNs and web server configurations.</li> </ul> <

## Rport Docker Image
 - [https://www.reddit.com/r/selfhosted/comments/1g8bb2g/rport_docker_image](https://www.reddit.com/r/selfhosted/comments/1g8bb2g/rport_docker_image)
 - RSS feed: $source
 - date published: 2024-10-20T22:48:33+00:00

<!-- SC_OFF --><div class="md"><p>Does any body know if there is the official Rport docker image ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/princesaharan"> /u/princesaharan </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g8bb2g/rport_docker_image/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g8bb2g/rport_docker_image/">[comments]</a></span>

## Server credentials not working, cannot log in via Windows 11 computer
 - [https://www.reddit.com/r/selfhosted/comments/1g8av40/server_credentials_not_working_cannot_log_in_via](https://www.reddit.com/r/selfhosted/comments/1g8av40/server_credentials_not_working_cannot_log_in_via)
 - RSS feed: $source
 - date published: 2024-10-20T22:27:06+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g8av40/server_credentials_not_working_cannot_log_in_via/"> <img src="https://a.thumbs.redditmedia.com/b8y_iwrRXCrUc52yAOnF9XUCYnoHj1FYIialo4kdzj4.jpg" alt="Server credentials not working, cannot log in via Windows 11 computer" title="Server credentials not working, cannot log in via Windows 11 computer" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/h52tt0dulzvd1.png?width=1125&amp;format=png&amp;auto=webp&amp;s=ddb56df7e42461fa27b14b5d272fe83d4cb575c0">https://preview.redd.it/h52tt0dulzvd1.png?width=1125&amp;format=png&amp;auto=webp&amp;s=ddb56df7e42461fa27b14b5d272fe83d4cb575c0</a></p> <p>I have tried using the username &amp; password combo for the server, as well as my Microsoft login credentials for the laptop I&#39;m using to attempt to connect to the server. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/intoabagel"> /u/intoabagel

## Alguém conhece alguma solução Open Source, que faça cache de vídeos, youtube, netflix. ....
 - [https://www.reddit.com/r/selfhosted/comments/1g8asy7/alguém_conhece_alguma_solução_open_source_que](https://www.reddit.com/r/selfhosted/comments/1g8asy7/alguém_conhece_alguma_solução_open_source_que)
 - RSS feed: $source
 - date published: 2024-10-20T22:24:11+00:00

<!-- SC_OFF --><div class="md"><p>Gostaria de montar um servidor em minha casa para fazer cache de vídeos do youtube, netflix ... Alguem conhece alguma solução Open Source que que possa montar em raspberry pi</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TurnMammoth7998"> /u/TurnMammoth7998 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g8asy7/alguém_conhece_alguma_solução_open_source_que/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g8asy7/alguém_conhece_alguma_solução_open_source_que/">[comments]</a></span>

## Configuring both IP and Subdomain on DNS to overcome the +100MB upload limit on Cloudflare tunnels
 - [https://www.reddit.com/r/selfhosted/comments/1g8arfr/configuring_both_ip_and_subdomain_on_dns_to](https://www.reddit.com/r/selfhosted/comments/1g8arfr/configuring_both_ip_and_subdomain_on_dns_to)
 - RSS feed: $source
 - date published: 2024-10-20T22:22:09+00:00

<!-- SC_OFF --><div class="md"><p>I have a server hosted at home on a Mac Mini, sitting behind a Tailscale IP, with all my different Docker apps linked to subdomains via Cloudflare Zero Trust Tunnels.</p> <p>My question is about the CNAME configuration I need to assign to my Immich Tailscale IP in order to seamlessly upload files larger than 100MB when I am physically at home, without requiring any additional steps.</p> <p>I’ve seen discussions about this online but haven’t been able to implement it successfully. Immich is already linked to a subdomain, <a href="http://album.mydomain.com">album.mydomain.com</a>, via DNS, but how can I configure the DNS to also route through the Tailscale IP, so I don’t need to sign out of the Immich iOS app and log in with the IP when I’m home to be able to upload beyond 100MB?</p> <p>I would appreciate clear and accessible comments for an average selfhosting guy who is not a programmer, Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a hre

## If you hoard video games and aren’t selfhosting GameVault yet, you’re missing out!
 - [https://www.reddit.com/r/selfhosted/comments/1g8aby2/if_you_hoard_video_games_and_arent_selfhosting](https://www.reddit.com/r/selfhosted/comments/1g8aby2/if_you_hoard_video_games_and_arent_selfhosting)
 - RSS feed: $source
 - date published: 2024-10-20T22:02:00+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>it’s me again, one of the two developers behind <em><a href="https://gamevau.lt">GameVault</a></em>, a self-hosted gaming platform similar to how Plex/Jellyfin is for your movies and series, but for your game collection. If you&#39;ve hoarded a bunch of games over the years, this app is going to be your best friend. Think of it as your own personal Steam, hosted on your own server.</p> <p>If you haven’t heard of <em>GameVault</em> yet, you can check it out <a href="https://gamevau.lt">here</a> and get started within 5 minutes—seriously, it’s a game changer.</p> <p>For those who already know <em>GameVault</em>, or its old name <em>He-Who-Must-Not-Be-Named</em>, <strong>we are excited to tell you we just launched a major update</strong>. I’m talking a massive overhaul—so much so, that we could’ve rebuilt the whole thing from scratch. Here’s the big news: <strong>We’re no longer relying on RAWG or Google Images for game metadata.</st

## Help understanding SSL certs
 - [https://www.reddit.com/r/selfhosted/comments/1g89uap/help_understanding_ssl_certs](https://www.reddit.com/r/selfhosted/comments/1g89uap/help_understanding_ssl_certs)
 - RSS feed: $source
 - date published: 2024-10-20T21:40:04+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been trying to set up my homelab with a new dell poweredge server, and I&#39;m having a difficult time understanding how SSL/TLS works in my situation.</p> <p>There&#39;s a hardware management (idrac) web interface that I access locally (192.168.1.120). Trying to use the virtual console returns an error that the cert could not be validated.</p> <p>I&#39;ve also attempted to deploy XenOrchestra via <a href="https://vates.tech/deploy/">their online appliace</a> and I get an HTTPS error telling me I need to trust the self signed certificate for that IP. </p> <p>I&#39;ve attempted to create my own certs using openSSL with some sucess - the webpage now says it is secure, and references the non-mozilla cert I uploaded. However, I still get the same invalid/untrusted errors like above.</p> <h2></h2> <p>I guess my main issue is that I don&#39;t understand SSL thoroughly enough to effectively troubleshoot my problem. I could set up a domain pointing t

## Ideas to do with old hardware
 - [https://www.reddit.com/r/selfhosted/comments/1g88swx/ideas_to_do_with_old_hardware](https://www.reddit.com/r/selfhosted/comments/1g88swx/ideas_to_do_with_old_hardware)
 - RSS feed: $source
 - date published: 2024-10-20T20:53:49+00:00

<!-- SC_OFF --><div class="md"><p>Hi! I have some old hardware laying around that i literallt have no idea what to do with it. I already have a server and a couple of RPi for some self hosted stuff.</p> <p>This is what I have: - Laptop dell L521X with broken keyboard - NUC intel fully functjonal - 2 RPI 2 and 1 RPi3</p> <p>Some ideas i have: - Sell everything as spare parts and make some money - connect it all together and learn how to work with kubernets - fix the laptop and use it as spare laptop.</p> <p>Any other ideas?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/My-Name-is-42"> /u/My-Name-is-42 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g88swx/ideas_to_do_with_old_hardware/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g88swx/ideas_to_do_with_old_hardware/">[comments]</a></span>

## Homepage and Mealie/Immich APIs
 - [https://www.reddit.com/r/selfhosted/comments/1g88rrr/homepage_and_mealieimmich_apis](https://www.reddit.com/r/selfhosted/comments/1g88rrr/homepage_and_mealieimmich_apis)
 - RSS feed: $source
 - date published: 2024-10-20T20:52:22+00:00

<!-- SC_OFF --><div class="md"><p>Just wanted to make sure it wasn&#39;t my own configuration, but the latest update to homepage appears to have broken the widgest (API) for Mealie and Immich.</p> <p>I know the API endpoints for Immich has changed and homepage will likely fix that downt he road, but I didn&#39;t see anything for Mealie. </p> <p>Anyone else&#39;s widget not working for Mealie?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JQuonDo"> /u/JQuonDo </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g88rrr/homepage_and_mealieimmich_apis/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g88rrr/homepage_and_mealieimmich_apis/">[comments]</a></span>

## KAM Ruleset for SpamAssassin - Any Experiences?
 - [https://www.reddit.com/r/selfhosted/comments/1g88nde/kam_ruleset_for_spamassassin_any_experiences](https://www.reddit.com/r/selfhosted/comments/1g88nde/kam_ruleset_for_spamassassin_any_experiences)
 - RSS feed: $source
 - date published: 2024-10-20T20:47:07+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone! I&#39;m curious if anyone here has experience with the KAM Ruleset for SpamAssassin. Is it still actively maintained? Does it perform as expected in detecting spam? I&#39;d love to hear your thoughts and experiences!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Entire-Leadership911"> /u/Entire-Leadership911 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g88nde/kam_ruleset_for_spamassassin_any_experiences/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g88nde/kam_ruleset_for_spamassassin_any_experiences/">[comments]</a></span>

## Creating a personal video server
 - [https://www.reddit.com/r/selfhosted/comments/1g888e3/creating_a_personal_video_server](https://www.reddit.com/r/selfhosted/comments/1g888e3/creating_a_personal_video_server)
 - RSS feed: $source
 - date published: 2024-10-20T20:28:52+00:00

<!-- SC_OFF --><div class="md"><p>I have a bunch of movies and would like to use Jellyfin with Hetzner. To store my movies, I was thinking of using Hetzner’s storage box.</p> <p>I had a couple of questions around this: 1. Is Hetzner storage box encrypted by default? 2. If not, then should I encrypt my movies and could that be served via Jellyfin?</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rds1701"> /u/rds1701 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g888e3/creating_a_personal_video_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g888e3/creating_a_personal_video_server/">[comments]</a></span>

## Chain Traverser: Self-Host Your Ethereum Explorer 🛠️
 - [https://www.reddit.com/r/selfhosted/comments/1g8848s/chain_traverser_selfhost_your_ethereum_explorer](https://www.reddit.com/r/selfhosted/comments/1g8848s/chain_traverser_selfhost_your_ethereum_explorer)
 - RSS feed: $source
 - date published: 2024-10-20T20:23:41+00:00

<!-- SC_OFF --><div class="md"><p>Hi there!</p> <p>I wanted to share <strong>Chain Traverser</strong>, a project I built for exploring the Ethereum blockchain on your own setup. It indexes the blockchain in memory and offers an API to visualize transaction relationships and find paths between addresses.</p> <p>🔍 <a href="https://dictynna.com/">Demo</a><br/> 📂 <a href="https://github.com/guzun-corp/chain-traverser">GitHub</a></p> <p><strong>Features:</strong></p> <ul> <li><strong>In-Memory Indexing</strong> for fast data access</li> <li><strong>Graph Traversal</strong> to see how addresses connect</li> <li><strong>Path Finding</strong> between any two Ethereum addresses</li> <li><strong>Local Node Support</strong> (works with geth, lighthouse)</li> <li><strong>Easy Docker Compose</strong> setup</li> </ul> <p>Feel free to check it out, try hosting it yourself, and let me know what you think! Open to feedback and contributions.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="h

## Self hosted servers
 - [https://www.reddit.com/r/selfhosted/comments/1g87y1b/self_hosted_servers](https://www.reddit.com/r/selfhosted/comments/1g87y1b/self_hosted_servers)
 - RSS feed: $source
 - date published: 2024-10-20T20:16:14+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I’m very new to programming and learning about servers and I was looking into setting up a little home server with raspberry pi4. For now I was just planning on having a small music service running on said server and storing files in it. But I was wondering what are the benefits of setting up a home server, how would you write code into it and how would you set it up. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Downhill_From_Here87"> /u/Downhill_From_Here87 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g87y1b/self_hosted_servers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g87y1b/self_hosted_servers/">[comments]</a></span>

## PSA: Official Syncthing Android app will be discontinued in December
 - [https://www.reddit.com/r/selfhosted/comments/1g86vxj/psa_official_syncthing_android_app_will_be](https://www.reddit.com/r/selfhosted/comments/1g86vxj/psa_official_syncthing_android_app_will_be)
 - RSS feed: $source
 - date published: 2024-10-20T19:30:33+00:00

<!-- SC_OFF --><div class="md"><p>Syncthing dev will discontinue the official app in December:</p> <ul> <li><a href="https://forum.syncthing.net/t/discontinuing-syncthing-android/23002">https://forum.syncthing.net/t/discontinuing-syncthing-android/23002</a></li> </ul> <p>This is due to the fact the app doesn&#39;t use the Android storage API and the developer does not want to rewrite the whole daemon just for Android.</p> <p>Also note that Catfriend will close their Google Play account and Syncthing-fork will only be available on F-Droid:</p> <ul> <li><a href="https://github.com/Catfriend1/syncthing-android">https://github.com/Catfriend1/syncthing-android</a></li> </ul> <p>&quot;Planning to close my Google Play Developer Account&quot;</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/suprjami"> /u/suprjami </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g86vxj/psa_official_syncthing_android_app_will_be/">[link]</a></span> &#

## Plex Docker Container No longer working
 - [https://www.reddit.com/r/selfhosted/comments/1g8640v/plex_docker_container_no_longer_working](https://www.reddit.com/r/selfhosted/comments/1g8640v/plex_docker_container_no_longer_working)
 - RSS feed: $source
 - date published: 2024-10-20T18:57:23+00:00

<!-- SC_OFF --><div class="md"><p>So, suddenly my Plex docker container is just no longer working. docker ps shows that the container is running, but there is no activity on port 32400, and if I try to stop or restart the container, I just end up waiting forever, nothing happens. I&#39;ve tried killing the PID for the container, pruning the images and containers, and rebuilding, but that put me right back where I started. Any ideas?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/elder242"> /u/elder242 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g8640v/plex_docker_container_no_longer_working/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g8640v/plex_docker_container_no_longer_working/">[comments]</a></span>

## Voice assistant SIP client?
 - [https://www.reddit.com/r/selfhosted/comments/1g85nt6/voice_assistant_sip_client](https://www.reddit.com/r/selfhosted/comments/1g85nt6/voice_assistant_sip_client)
 - RSS feed: $source
 - date published: 2024-10-20T18:38:08+00:00

<!-- SC_OFF --><div class="md"><p>Working on something and want to know if anyone&#39;s already started on something like this rather than trying to reinvent the wheel.</p> <p>I&#39;ve currently got a self hosted PBX that I&#39;m using with some old Mitel SIP phones around the house as an intercom (opening a speaker in my kids rooms to say &quot;get up&quot; or &quot;dinner time&quot;). </p> <p>I got rid of the google home/nest stuff a while ago, but I do miss having the google assistant to ask it quick things like measure conversions or a quick fact check (eg &quot;what&#39;s the population of Vancouver&quot;) without having to grab a phone or having voice conversations monitored all the time. </p> <p>So far I haven&#39;t set up a self hosted voice assistant but as I&#39;m starting to look into it I&#39;m hoping that one of them maybe already has this kind of functionality built in, or if not might be configurable/hackable enough that I could make a module/handler for it in python or

## [SCROLL ME!] ELI5 VIRTUAL NETWORK ON PVE : OpenWRT Reacts Differently If Called From Outside The Proxmox Server /VS/ From a LXC on the Same Network Bridge.
 - [https://www.reddit.com/r/selfhosted/comments/1g85iu8/scroll_me_eli5_virtual_network_on_pve_openwrt](https://www.reddit.com/r/selfhosted/comments/1g85iu8/scroll_me_eli5_virtual_network_on_pve_openwrt)
 - RSS feed: $source
 - date published: 2024-10-20T18:32:21+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g85iu8/scroll_me_eli5_virtual_network_on_pve_openwrt/"> <img src="https://b.thumbs.redditmedia.com/Gbm5NpnTtN4AWOdXhRJWziJnFGi2FtXJQKhJTp9xlew.jpg" alt="[SCROLL ME!] ELI5 VIRTUAL NETWORK ON PVE : OpenWRT Reacts Differently If Called From Outside The Proxmox Server /VS/ From a LXC on the Same Network Bridge." title="[SCROLL ME!] ELI5 VIRTUAL NETWORK ON PVE : OpenWRT Reacts Differently If Called From Outside The Proxmox Server /VS/ From a LXC on the Same Network Bridge." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TGriffures"> /u/TGriffures </a> <br/> <span><a href="https://www.reddit.com/gallery/1g85iu8">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g85iu8/scroll_me_eli5_virtual_network_on_pve_openwrt/">[comments]</a></span> </td></tr></table>

## Time available to respond to complaints raised against your domain
 - [https://www.reddit.com/r/selfhosted/comments/1g84vl6/time_available_to_respond_to_complaints_raised](https://www.reddit.com/r/selfhosted/comments/1g84vl6/time_available_to_respond_to_complaints_raised)
 - RSS feed: $source
 - date published: 2024-10-20T18:05:00+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve registered a .uk domain, and understand that Nominet, the .uk registry is somewhat decent and they give you a login to manage some aspects of your domain independent of the registrar.</p> <p>I have a concern that is not exclusive to .uk domains. Nominet gives me 15 days to respond if a complaint is raised against my domain (either over a trademark, or as a scamming attempt), which may not be enough if I&#39;m &#39;device fasting&#39; for several weeks, but I can live with that.</p> <p>I&#39;m also confident that I can prove it&#39;s not an abusive registration since the domain is based on my name and it&#39;s only used for email. The real problem is if for whatever reason, I fail to receive the email that Nominet sends me, in which case there is a risk of the domain being taken away from me if the complainant pays and requests for a &#39;summary decision&#39;.</p> <p>Now, luckily, Nominet also has a section that displays complaints received o

## HTTPS using Caddy V2 with domain from FreeDNS without port forwarding
 - [https://www.reddit.com/r/selfhosted/comments/1g846uh/https_using_caddy_v2_with_domain_from_freedns](https://www.reddit.com/r/selfhosted/comments/1g846uh/https_using_caddy_v2_with_domain_from_freedns)
 - RSS feed: $source
 - date published: 2024-10-20T17:35:32+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m newbie to self hosting, so unsure if trying to acheive over the top. I&#39;m setting up a server (on SBC) with DietPi, have managed to buiilt Immich and Seafile service using docker and can access on local network with IP and port. For learning, I have create a free subdomain on FreeDNS.afraid.org. My ultimate objective to allow family members access the apps through internet like <a href="https://sub-domain.example.com/immich">https://sub-domain.example.com/immich</a> or <a href="https://sub-domain.example.com/seafile">https://sub-domain.example.com/seafile</a> via browser or through android app. </p> <p>I have read many Caddy tutorials/posts for HTTPS using DNS-01 challenge but most uses Cloudflare. In my situation, Cloudflare isn&#39;t option as only allows root domain and cannot work with sub-domain like the one from FreeDNS. I&#39;m the customer of someone&#39;s domain on FreeeDNS and not the owner.</p> <p>Caddy can obtain TLS certificate

## FileBrowser
 - [https://www.reddit.com/r/selfhosted/comments/1g83vzm/filebrowser](https://www.reddit.com/r/selfhosted/comments/1g83vzm/filebrowser)
 - RSS feed: $source
 - date published: 2024-10-20T17:22:18+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g83vzm/filebrowser/"> <img src="https://external-preview.redd.it/4tPoseYvVk_DiQRH-clfRFLejS_sZmV2Y_bF77RQbRg.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=52c2c314997566a69490207ad235f61b8e4aad9e" alt="FileBrowser" title="FileBrowser" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I needed filebrowser app to organize my files and folders in my homelab. I chose this service <a href="https://hub.docker.com/r/filebrowser/filebrowser">https://hub.docker.com/r/filebrowser/filebrowser</a></p> <p>For the life of me i can not find out how to run ANY terminal command inside it&#39;s terminal. Or even how to clear the terminal. Could you please assist me about this? How do i allow commands?</p> <p><a href="https://preview.redd.it/j7h8mk3q3yvd1.png?width=1919&amp;format=png&amp;auto=webp&amp;s=a3f4a398c059b6f28429911dd57ddbbef69e1e62">https://preview.redd.it/j7h8mk3q3yvd1.png?width=1919&amp;format=png&amp;auto=webp&a

## is there a windows software to download and run selfhosted apps only
 - [https://www.reddit.com/r/selfhosted/comments/1g835wf/is_there_a_windows_software_to_download_and_run](https://www.reddit.com/r/selfhosted/comments/1g835wf/is_there_a_windows_software_to_download_and_run)
 - RSS feed: $source
 - date published: 2024-10-20T16:50:47+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/furllamm"> /u/furllamm </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g835wf/is_there_a_windows_software_to_download_and_run/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g835wf/is_there_a_windows_software_to_download_and_run/">[comments]</a></span>

## Recommendation for game download cache host
 - [https://www.reddit.com/r/selfhosted/comments/1g82sk5/recommendation_for_game_download_cache_host](https://www.reddit.com/r/selfhosted/comments/1g82sk5/recommendation_for_game_download_cache_host)
 - RSS feed: $source
 - date published: 2024-10-20T16:34:54+00:00

<!-- SC_OFF --><div class="md"><p>As the title mentioned, i need a steam game downloader. Explanation: I&#39;m a 30yrsold guy who doesn&#39;t have much time to play game nowadays but i still do play for 1hr or 2 every few day once before getting tired and eventually get to bed. Sometime i also do play with friends(over Internet), sometime when i open my pc to play game, the game needs updating, if it&#39;s just 1 or 2 gb, i don&#39;t mind but downloading update file itself gets until 19gb, and getting higher day by day especially AAA games... So i need a host that could download game updates into the server even when my pc is shut down, and push those updates to my pc steam when i wanted to play... Few things to note: 1) I got 300mbps down fiber, but i feel like 1gbps network speed would be better and i could play games faster. 2) owned a xpenology running few dockers and media server,so i could make use of it to download game updates. 3) I just need the host to download specific game

## Homelab Power Consumption
 - [https://www.reddit.com/r/selfhosted/comments/1g826yf/homelab_power_consumption](https://www.reddit.com/r/selfhosted/comments/1g826yf/homelab_power_consumption)
 - RSS feed: $source
 - date published: 2024-10-20T16:09:00+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g826yf/homelab_power_consumption/"> <img src="https://preview.redd.it/2b3twudnqxvd1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=fc0bc156d45f9313239329c82f6ba52c5637d221" alt="Homelab Power Consumption" title="Homelab Power Consumption" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I&#39;m having trouble finding a normal power consumption scale for a homelab. So I&#39;m putting mine here, and don&#39;t hesitate to give us yours so we can compare and find ways to improve.</p> <p>I currently have a home-made nas and a small Lenovo computer with Proxmox on it.</p> <p>I currently consume 1.6kWh per day.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Horlogrium"> /u/Horlogrium </a> <br/> <span><a href="https://i.redd.it/2b3twudnqxvd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g826yf/homelab_power_consump

## Simple image for nginx + acme.sh
 - [https://www.reddit.com/r/selfhosted/comments/1g821y4/simple_image_for_nginx_acmesh](https://www.reddit.com/r/selfhosted/comments/1g821y4/simple_image_for_nginx_acmesh)
 - RSS feed: $source
 - date published: 2024-10-20T16:03:04+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for small container which combines nginx unprivileged and acme.sh so that nginx is reloaded whenever the certs get renewed. I don&#39;t need any graphical interface or so. For now I used nginx-proxy with dockergen but it exposes the docker socket which I don&#39;t want to do.</p> <p>Any recommendations?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Cilenco"> /u/Cilenco </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g821y4/simple_image_for_nginx_acmesh/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g821y4/simple_image_for_nginx_acmesh/">[comments]</a></span>

## Is it possible to use a DNS challenge for an owned public domain, but use an entirely different domain locally?
 - [https://www.reddit.com/r/selfhosted/comments/1g81zsm/is_it_possible_to_use_a_dns_challenge_for_an](https://www.reddit.com/r/selfhosted/comments/1g81zsm/is_it_possible_to_use_a_dns_challenge_for_an)
 - RSS feed: $source
 - date published: 2024-10-20T16:00:46+00:00

<!-- SC_OFF --><div class="md"><p>What I&#39;m trying to do:</p> <p>Theoretically, let&#39;s say I own the domain &quot;mydomain.com&quot;, however, I don&#39;t want to use that domain internally on my home network. I want to use a simpler domain like &quot;home.lan&quot;. Is it possible to use a DNS challenge with something like Traefik for one domain, use a DNS rewrite for that domain, and still be able to use that tls certificate for local https? I&#39;m picturing this would look like either: </p> <ol> <li>A record in cloudflare that points to my local domain</li> <li>A setting in Traefik that verifies the dns separately from the proxy domain</li> <li>A traefik setting that proxies the local domain to the public domain while maintaining the cert.</li> <li>A setting in my DNS server like Adguard that rewrites the domain, but somehow retains the cert.</li> </ol> <p>My other 2 options are -- </p> <ol> <li>mkcert</li> <li>Suck it up and use the public domain locally with a loopback.</l

## How to set up Nginx Proxy Manager with podman?
 - [https://www.reddit.com/r/selfhosted/comments/1g81hxr/how_to_set_up_nginx_proxy_manager_with_podman](https://www.reddit.com/r/selfhosted/comments/1g81hxr/how_to_set_up_nginx_proxy_manager_with_podman)
 - RSS feed: $source
 - date published: 2024-10-20T15:38:46+00:00

<!-- SC_OFF --><div class="md"><p>Trying to get some services from docker to podman, but Nginx Proxy Manager simply won&#39;t spin. I tried using the official doccumentation for docker, but that&#39;s all I got:</p> <pre><code>[Container] Image=jc21/nginx-proxy-manager:latest Volume=./data:/data:z Volume=./letsencrypt:/etc/letsencrypt:z PublishPort=80:80 PublishPort=81:81 PublishPort=443:443 [Service] Restart=always [Install] WantedBy=default.target </code></pre> <p>Any advice from someone who successfully did that?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jaizoncarlos"> /u/jaizoncarlos </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g81hxr/how_to_set_up_nginx_proxy_manager_with_podman/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g81hxr/how_to_set_up_nginx_proxy_manager_with_podman/">[comments]</a></span>

## Having a second separate domain pointed to same nginx proxy manager
 - [https://www.reddit.com/r/selfhosted/comments/1g813of/having_a_second_separate_domain_pointed_to_same](https://www.reddit.com/r/selfhosted/comments/1g813of/having_a_second_separate_domain_pointed_to_same)
 - RSS feed: $source
 - date published: 2024-10-20T15:20:41+00:00

<!-- SC_OFF --><div class="md"><p>Saw the other guy praising caddy, meanwhile I&#39;ve been stuck here trying to troubleshoot this lol. I purchased a domain quite a while ago just so I can make my home server public so friends and family can access it too more easily. Domain name is (not really) swazz.world. I have a bunch of public services like watch.swazz.world or ollama.swazz.world and those all work great.</p> <p>I wanted to host an image hosting service for sharex and the like so I can have those automatically upload to my server instead of imgur or whatever. Everything works great! images.swazz.world works fine! But that&#39;s too long of a URL. So I purchased sw.world and made the subdomain i.sw.world. I&#39;ve got it set up through cloudflare and nginx proxy manager.</p> <p>Cloudflare is set up the exact same way as swazz.world. Same A Record pointing to my IP, same wildcard CNAME pointing to swazz.world. DNS only on both entries. Just like swazz.world.</p> <p>NGINX Proxy man

## Concerns Raised Over Bitwarden Moving Further Away From Open-Source
 - [https://www.reddit.com/r/selfhosted/comments/1g811sd/concerns_raised_over_bitwarden_moving_further](https://www.reddit.com/r/selfhosted/comments/1g811sd/concerns_raised_over_bitwarden_moving_further)
 - RSS feed: $source
 - date published: 2024-10-20T15:18:21+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g811sd/concerns_raised_over_bitwarden_moving_further/"> <img src="https://external-preview.redd.it/3kV-1YNLhjGcw8MjTxCQt-6HfxoQ8ILRxCzAKuNQSjE.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=901d1546a06203226452e3b5f0152e57c75f8a22" alt="Concerns Raised Over Bitwarden Moving Further Away From Open-Source" title="Concerns Raised Over Bitwarden Moving Further Away From Open-Source" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/777fer"> /u/777fer </a> <br/> <span><a href="https://www.phoronix.com/news/Bitwarden-Open-Source-Concerns">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g811sd/concerns_raised_over_bitwarden_moving_further/">[comments]</a></span> </td></tr></table>

## Need some help to expose docker apps (nginx,swag?)
 - [https://www.reddit.com/r/selfhosted/comments/1g80iey/need_some_help_to_expose_docker_apps_nginxswag](https://www.reddit.com/r/selfhosted/comments/1g80iey/need_some_help_to_expose_docker_apps_nginxswag)
 - RSS feed: $source
 - date published: 2024-10-20T14:54:24+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>need some help with my setup. Am i thinking about this right?</p> <p>I have a PC running OMV and docker compose working, and i want to be able access <strong>Immich</strong>, <strong>Jellyfin</strong>, and <strong>NextCloud</strong> externally (by two phones mostly).</p> <p>I also have a domain name bought on <a href="http://hostinger.com">hostinger.com</a>, that i used on my other PC running <strong>Home Assistant</strong>. Previously i used Cloudflare tunnel for HA, and everything was perfect, but now as i understand, i can&#39;t use Cloudflare for Jellyfin and Immich. So i was thinking about going the nginx route. And i want to be able to reuse the same domain name with subdomains, as in jellyfin.mydomain.com, immich.mydomain.com, homeassistant.mydomain.com . I have a dynamic external IP. So I have found this guide, that i was going to follow initially:</p> <p><a href="https://www.reddit.com/r/selfhosted/comments/146c2yd/guide_f

## Kopia is brilliant
 - [https://www.reddit.com/r/selfhosted/comments/1g80czc/kopia_is_brilliant](https://www.reddit.com/r/selfhosted/comments/1g80czc/kopia_is_brilliant)
 - RSS feed: $source
 - date published: 2024-10-20T14:47:30+00:00

<!-- SC_OFF --><div class="md"><p>After much deliberation and help from reditters, I took the plunge into Kopia as the backup software and backblaze b2 as providers of choice for file-backups on ~30VMs. This is to supplement my data (which is already backed up at both file and block level to zfs system, local disks, and also via zfs send/receive to a cloud provider). </p> <p>I wanted to share the journey in the hopes that others may find it beneficial:</p> <ol> <li><p>Installed Kopia on one of the simpler VMs (ansible controller) to build familiarity.</p></li> <li><p>Created native b2 buckets, Kopia repository in those bucket, played with Kopia CLI commands.</p></li> <li><p>Server side encryption is great, but not revealing encryption keys to a cloud provider is better. Rinse and repeat above with S3 buckets in b2. Awesome.</p></li> <li><p><code>compression=on</code> supercharges uploads, tweak storage retention policies etc to formulate the basic policy set which may work for me.</p>

## Tool for migrating from Keep to Memos
 - [https://www.reddit.com/r/selfhosted/comments/1g8080j/tool_for_migrating_from_keep_to_memos](https://www.reddit.com/r/selfhosted/comments/1g8080j/tool_for_migrating_from_keep_to_memos)
 - RSS feed: $source
 - date published: 2024-10-20T14:41:06+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I have created a script to move your data from Google Keep to the <a href="https://github.com/usememos/memos">self hosted memos alternative</a>.</p> <p><a href="https://github.com/MatthieuTinnes/move-keep-to-memos">https://github.com/MatthieuTinnes/move-keep-to-memos</a></p> <p>Any feedback are appreciated ! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Matthieu42"> /u/Matthieu42 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g8080j/tool_for_migrating_from_keep_to_memos/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g8080j/tool_for_migrating_from_keep_to_memos/">[comments]</a></span>

## Alternatives to brevo/mailchimp
 - [https://www.reddit.com/r/selfhosted/comments/1g7zz6n/alternatives_to_brevomailchimp](https://www.reddit.com/r/selfhosted/comments/1g7zz6n/alternatives_to_brevomailchimp)
 - RSS feed: $source
 - date published: 2024-10-20T14:29:36+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for some self-hosting alternatives to brevo/mailchimp. I&#39;ve already found <a href="https://listmonk.app/">ListMonk </a>and <a href="https://www.keila.io/">Keila</a>. Keila seems cool. </p> <p>I&#39;m courios if you know some other tools like these. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/saramon"> /u/saramon </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7zz6n/alternatives_to_brevomailchimp/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7zz6n/alternatives_to_brevomailchimp/">[comments]</a></span>

## Explo – Spotify's 'Discover Weekly' for Self-Hosted Music Systems v0.6.0
 - [https://www.reddit.com/r/selfhosted/comments/1g7yz45/explo_spotifys_discover_weekly_for_selfhosted](https://www.reddit.com/r/selfhosted/comments/1g7yz45/explo_spotifys_discover_weekly_for_selfhosted)
 - RSS feed: $source
 - date published: 2024-10-20T13:41:59+00:00

<!-- SC_OFF --><div class="md"><p>Hello!</p> <p>A while back, I shared <a href="https://github.com/LumePart/Explo">Explo – an alternative to Spotify&#39;s &quot;Discover Weekly&quot;</a> that automates music discovery. Originally it only supported Subsonic compatible systems, due to requests, I have recently released support for Jellyfin (from v0.6.0) and Music Player Daemon (from v0.5.0).</p> <p>What does Explo do?</p> <p>Explo downloads recommended tracks based on your listening history, using ListenBrainz for recommendations and YouTube for downloads. It&#39;s designed to be a &quot;set it and forget it&quot; solution with everything packed into a single Go binary.</p> <p>You can check it out <a href="https://github.com/LumePart/Explo">HERE!</a></p> <p>Feel free to ask questions and leave feedback and/or suggestions.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LumePart"> /u/LumePart </a> <br/> <span><a href="https://www.reddit.com/r/selfho

## Self-hosting multiple services with https (via let's encrypt)
 - [https://www.reddit.com/r/selfhosted/comments/1g7yxgg/selfhosting_multiple_services_with_https_via_lets](https://www.reddit.com/r/selfhosted/comments/1g7yxgg/selfhosting_multiple_services_with_https_via_lets)
 - RSS feed: $source
 - date published: 2024-10-20T13:39:41+00:00

<!-- SC_OFF --><div class="md"><p>Hello self-hosting community!<br/> I&#39;d like to ask for your help/advice.</p> <p>For the past 5 years I&#39;ve been self-hosting only one service (Nextcloud).<br/> But recently, I&#39;ve decided to start hosting more.</p> <p>The problem is, essentially, getting reliable free subdomains.</p> <p>I&#39;ll detail below, but for those who don&#39;t want to real all the details, my question(s) is:</p> <p>What do you guys use for domains with your multiple services?<br/> - do you use a paid domain/service that allows you to add as many subdomains as you want? If so, is it worth the cost?<br/> - do you use a free domain/service that allows you to add as many subdomains as you want? If so, how reliable is it?<br/> - do you access them only from your local network and don&#39;t need HTTPS?</p> <p>Details:<br/> I&#39;ve tried the following approaches:</p> <ol> <li><p>Port forwarding for each service<br/> I quickly found out that this approach won&#39;t work b

## Creating a proxysite for squid
 - [https://www.reddit.com/r/selfhosted/comments/1g7yspu/creating_a_proxysite_for_squid](https://www.reddit.com/r/selfhosted/comments/1g7yspu/creating_a_proxysite_for_squid)
 - RSS feed: $source
 - date published: 2024-10-20T13:33:01+00:00

<!-- SC_OFF --><div class="md"><p>I have configured squid and it works well with the FoxyProxy extension for browsers. I want to use it to proxy the request from the browser on my phone(chromium). The only approach that came to my mind is to create a proxy site like <a href="https://proxyium.com/">https://proxyium.com/</a> which can then proxy the request through my squid server. I tried looking around and the only things I could get were admin panels for squid. I have no clue how to achieve this</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/joel_122002"> /u/joel_122002 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7yspu/creating_a_proxysite_for_squid/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7yspu/creating_a_proxysite_for_squid/">[comments]</a></span>

## Selfhost SMTP
 - [https://www.reddit.com/r/selfhosted/comments/1g7y19u/selfhost_smtp](https://www.reddit.com/r/selfhosted/comments/1g7y19u/selfhost_smtp)
 - RSS feed: $source
 - date published: 2024-10-20T12:54:15+00:00

<!-- SC_OFF --><div class="md"><p>Yes, another idiot who wants to selfhost mail. However, I have experience self hosting mail. I have run an Exim server with DirectAdmin for 15 years and Postfix for 5 years. I decided to stop self hosting mail because I can’t keep up with filtering spam. Self hosting premium spam filters would be quite expensive and I choose to migrate all mails to Office365. I also use the Calendar and contact options a lot. </p> <p>I am quite satisfied with it, but I also send a lot of automated mails via systems I host myself. Up to 1000 a day. I created a separate account for this in Office365. But I don’t like it that I use one account for about 10-20 different applications. </p> <p>I don’t want to go with another company for sending mail. I would either like to stay with Microsoft or selfhost a Postfix server just for sending mails. I would then setup different accounts for each application with a very long password. I also set limits per account. (A printer wou

## Beginner in self hosting looking for advice on hardware upgrades, setup.
 - [https://www.reddit.com/r/selfhosted/comments/1g7xzql/beginner_in_self_hosting_looking_for_advice_on](https://www.reddit.com/r/selfhosted/comments/1g7xzql/beginner_in_self_hosting_looking_for_advice_on)
 - RSS feed: $source
 - date published: 2024-10-20T12:52:05+00:00

<!-- SC_OFF --><div class="md"><p>I have recently purchased “new to me” hardware, a Dell Optiplex 7090 i7 10700. 256GB Nvme. 1 16GB ram module. I’m looking for upgrade advice so I don’t overspend or purchase more than I need before I start install. </p> <p>I’ve run Ubuntu server with docker containers for a few years now on an older computer but I would like to expand on that with a computer that is a bit faster and more power.</p> <p>Ideally my goals are:</p> <p>Use the Dell setup optimally to run my docker containers, next cloud, media server Plex. Smart home Home Assistant, etc. I’m looking at buying another 256 Nvme for raid 1 and a 1 tb ssd. </p> <p>Instead of creating more ewaste use the older Gateway SX2110-EW25 pc with an E1 chip to use as storage maybe with Truenas? There aren’t many sata ports but two 8 TB drives is likely all I’ll need for backup photos etc. maybe it is too long in the tooth to be useful even for that. </p> <p>Also looking at different projects in the futur

## MonoTor: A Self-Hosted, Open-Source Monitoring Application
 - [https://www.reddit.com/r/selfhosted/comments/1g7xxaf/monotor_a_selfhosted_opensource_monitoring](https://www.reddit.com/r/selfhosted/comments/1g7xxaf/monotor_a_selfhosted_opensource_monitoring)
 - RSS feed: $source
 - date published: 2024-10-20T12:48:18+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone</p> <p>I’ve created a self-hosted, open-source application for monitoring and progress tracking. Initially, it was designed as a fitness tracker, but over time, it evolved into a more dynamic tool that allows users to track any type of data they want. You can use it for fitness, learning, work, or any other data-tracking needs where numbers can be used as measurements.</p> <p>Features:</p> <ul> <li>Role-based authorization</li> <li>Generic data display: <ul> <li>Chart</li> <li>Desired value reached</li> <li>Mode</li> <li>Avarage</li> <li>Min / Max</li> </ul></li> <li>Calendar</li> <li>Table</li> <li>Admin / Settings panel</li> <li>Light / Dark theme</li> <li>Mobile application (as a PWA)</li> <li>Data backup (coming soon)</li> </ul> <p>The application is currently ready to use, and you can install it from the <a href="https://github.com/KostaD02/monotor">GitHub repository</a> to run locally.</p> <p>I’m planning to add Docker support but

## Open Source Alternatives to Jetadmin for Self-Hosting on Docker
 - [https://www.reddit.com/r/selfhosted/comments/1g7xb3m/open_source_alternatives_to_jetadmin_for](https://www.reddit.com/r/selfhosted/comments/1g7xb3m/open_source_alternatives_to_jetadmin_for)
 - RSS feed: $source
 - date published: 2024-10-20T12:12:56+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I&#39;m fairly new to the self-hosting world, and I&#39;m currently exploring ways to build an internal tool/back office for a web application (uses Firebase). I recently came across <a href="https://www.jetadmin.io/">Jetadmin</a>, which is a no-code tool that easily connects to services like Firebase and allows for the creation of quite powerful and sometimes complex back-office systems.</p> <p>However, I’m looking for open-source alternatives that I can self-host on Docker. My main goal is to have something that provides a similar functionality (connecting to databases (Firebase !) or APIs, no-code/low-code interface) but which can be hosted on my own infrastructure.</p> <p>Does anyone know of any tools like this that fit the bill? I’d appreciate any recommendations or guidance—especially if there’s something obvious I’m missing!</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.red

## Acces outside my local network for only 2of the 15 docker containers.
 - [https://www.reddit.com/r/selfhosted/comments/1g7x8jj/acces_outside_my_local_network_for_only_2of_the](https://www.reddit.com/r/selfhosted/comments/1g7x8jj/acces_outside_my_local_network_for_only_2of_the)
 - RSS feed: $source
 - date published: 2024-10-20T12:08:48+00:00

<!-- SC_OFF --><div class="md"><p>Howdy</p> <p>I would like to acces my mealie, plex outside my local network. What guide should i follow. Prefer so secure possible. Running it on debian</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/snijboon"> /u/snijboon </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7x8jj/acces_outside_my_local_network_for_only_2of_the/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7x8jj/acces_outside_my_local_network_for_only_2of_the/">[comments]</a></span>

## I was given the task by a family member to create an online shop for merchandise for a local football team, I have never done that, so should I write my own webpage and backend or are there services out there that let you create these shops from templates or are there open source tools out there?
 - [https://www.reddit.com/r/selfhosted/comments/1g7wuh0/i_was_given_the_task_by_a_family_member_to_create](https://www.reddit.com/r/selfhosted/comments/1g7wuh0/i_was_given_the_task_by_a_family_member_to_create)
 - RSS feed: $source
 - date published: 2024-10-20T11:46:09+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/ChaosCrafter908"> /u/ChaosCrafter908 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7wuh0/i_was_given_the_task_by_a_family_member_to_create/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7wuh0/i_was_given_the_task_by_a_family_member_to_create/">[comments]</a></span>

## Vaultwarden Stats For Homepage?
 - [https://www.reddit.com/r/selfhosted/comments/1g7wg12/vaultwarden_stats_for_homepage](https://www.reddit.com/r/selfhosted/comments/1g7wg12/vaultwarden_stats_for_homepage)
 - RSS feed: $source
 - date published: 2024-10-20T11:19:30+00:00

<!-- SC_OFF --><div class="md"><p>There was a post a while ago about a separate docker image that would get stats from a hosted Vaultwarden instance and allow them to be displayed on homepage.</p> <p>Does any remember it and point me in the right direction. I have been searching for ages and can&#39;t find it any more.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/root-node"> /u/root-node </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7wg12/vaultwarden_stats_for_homepage/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7wg12/vaultwarden_stats_for_homepage/">[comments]</a></span>

## What’s happening with popular software and open source
 - [https://www.reddit.com/r/selfhosted/comments/1g7w9wx/whats_happening_with_popular_software_and_open](https://www.reddit.com/r/selfhosted/comments/1g7w9wx/whats_happening_with_popular_software_and_open)
 - RSS feed: $source
 - date published: 2024-10-20T11:08:13+00:00

<!-- SC_OFF --><div class="md"><p>Today, I just seen post abt Bitwarden and docker no longer open source. Why is this? Is this all caused by the wp drama? Or what is happening that I don’t know</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/littleblack11111"> /u/littleblack11111 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7w9wx/whats_happening_with_popular_software_and_open/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7w9wx/whats_happening_with_popular_software_and_open/">[comments]</a></span>

## Desktop version 2024.10.0 is no longer free doftware
 - [https://www.reddit.com/r/selfhosted/comments/1g7w6vo/desktop_version_2024100_is_no_longer_free_doftware](https://www.reddit.com/r/selfhosted/comments/1g7w6vo/desktop_version_2024100_is_no_longer_free_doftware)
 - RSS feed: $source
 - date published: 2024-10-20T11:02:23+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g7w6vo/desktop_version_2024100_is_no_longer_free_doftware/"> <img src="https://external-preview.redd.it/13FeHN4_4A_4oXWdiYDBRSaBTEwbbe588_v6ni4S0xc.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=0c797e54bd36763c42b8049d1428e573e74108d5" alt="Desktop version 2024.10.0 is no longer free doftware" title="Desktop version 2024.10.0 is no longer free doftware" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/anturk"> /u/anturk </a> <br/> <span><a href="https://github.com/bitwarden/clients/issues/11611">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7w6vo/desktop_version_2024100_is_no_longer_free_doftware/">[comments]</a></span> </td></tr></table>

## Is self hosting docker container servers on a home network via cloudflare considered safe?
 - [https://www.reddit.com/r/selfhosted/comments/1g7w1qt/is_self_hosting_docker_container_servers_on_a](https://www.reddit.com/r/selfhosted/comments/1g7w1qt/is_self_hosting_docker_container_servers_on_a)
 - RSS feed: $source
 - date published: 2024-10-20T10:53:06+00:00

<!-- SC_OFF --><div class="md"><p>Title sums it up, I have Plex, LLama, and a couple other sites up and running all of which except for one are ran through a docker container. I’ve closed every possible port other than the ones I need for web access. I got setup with cloudflare and now have a URL to redirect the web to my home server. Is this safe? And if not, are there any ways I can safely manage this without an extensive background in networking? My sites are running on HTTP, however, there’s no sensitive information being sent over the servers themselves. (I had a weird issue with trying to get certifications for HTTPS and just gave up). I hope I explained this simply, just a new guy trying to do the right thing. </p> <p>Thanks in advance for your help.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Prestigious-Way7758"> /u/Prestigious-Way7758 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7w1qt/is_self_hosting_dock

## Desktop version 2024.10.0 is no longer free software
 - [https://www.reddit.com/r/selfhosted/comments/1g7vuyh/desktop_version_2024100_is_no_longer_free_software](https://www.reddit.com/r/selfhosted/comments/1g7vuyh/desktop_version_2024100_is_no_longer_free_software)
 - RSS feed: $source
 - date published: 2024-10-20T10:39:42+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g7vuyh/desktop_version_2024100_is_no_longer_free_software/"> <img src="https://external-preview.redd.it/13FeHN4_4A_4oXWdiYDBRSaBTEwbbe588_v6ni4S0xc.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=0c797e54bd36763c42b8049d1428e573e74108d5" alt="Desktop version 2024.10.0 is no longer free software" title="Desktop version 2024.10.0 is no longer free software" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>What does that mean for vaultwarden?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sugardaddy_satan"> /u/Sugardaddy_satan </a> <br/> <span><a href="https://github.com/bitwarden/clients/issues/11611">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7vuyh/desktop_version_2024100_is_no_longer_free_software/">[comments]</a></span> </td></tr></table>

## Costs for NAS Setup
 - [https://www.reddit.com/r/selfhosted/comments/1g7vd0u/costs_for_nas_setup](https://www.reddit.com/r/selfhosted/comments/1g7vd0u/costs_for_nas_setup)
 - RSS feed: $source
 - date published: 2024-10-20T10:03:28+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys I am planning to create a NAS with about 4-6 TB storage as a start. How much do I have to save up for a reliable setup? I also need to plan for backups, which probably costs extra to fulfill the 3-2-1 rule.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Lucian1000"> /u/Lucian1000 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7vd0u/costs_for_nas_setup/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7vd0u/costs_for_nas_setup/">[comments]</a></span>

## Host a Pterodactyl pannel without having to reveal my IP ?
 - [https://www.reddit.com/r/selfhosted/comments/1g7v8c5/host_a_pterodactyl_pannel_without_having_to](https://www.reddit.com/r/selfhosted/comments/1g7v8c5/host_a_pterodactyl_pannel_without_having_to)
 - RSS feed: $source
 - date published: 2024-10-20T09:53:56+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I want to host a Pterodactyl panel at home to host Minecraft servers and/or Discord bots. However, I don&#39;t want my IP to be visible to users connecting to it.</p> <p>Is it possible to install it through Cloudflare or something like that?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/EliasLPSaumon"> /u/EliasLPSaumon </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7v8c5/host_a_pterodactyl_pannel_without_having_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7v8c5/host_a_pterodactyl_pannel_without_having_to/">[comments]</a></span>

## CapRover & Mistral.rs - "'mistralrs-server' requires a subcommand but one was not provided"
 - [https://www.reddit.com/r/selfhosted/comments/1g7uvwe/caprover_mistralrs_mistralrsserver_requires_a](https://www.reddit.com/r/selfhosted/comments/1g7uvwe/caprover_mistralrs_mistralrsserver_requires_a)
 - RSS feed: $source
 - date published: 2024-10-20T09:27:48+00:00

<!-- SC_OFF --><div class="md"><p>Hiya, started out with CapRover and liking it so far. Some minor issues and problems, but basically working.</p> <p>Now, I want to serve an API endpoint for <a href="https://github.com/EricLBuehler/mistral.rs">mistral.rs</a>, to serve a language model. Thus, I built the repo with deployment method 3. </p> <p>But it loops through errors, even though I am not trying to access it in any way:</p> <pre><code>2024-10-20T09:24:46.751634842Z error: &#39;mistralrs-server&#39; requires a subcommand but one was not provided 2024-10-20T09:24:46.751656675Z [subcommands: toml, plain, x-lora, lora, gguf, x-lora-gguf, lora-gguf, ggml, x-lora-ggml, lora-ggml, vision-plain, diffusion-plain, help] 2024-10-20T09:24:46.751658758Z 2024-10-20T09:24:46.751659925Z Usage: mistralrs-server [OPTIONS] &lt;COMMAND&gt; 2024-10-20T09:24:46.751661217Z 2024-10-20T09:24:46.751662175Z For more information, try &#39;--help&#39;. </code></pre> <p>What am I doing wrong? A lot I guess, but 

## Hosting NetBird Coordination Server and Homeassistant
 - [https://www.reddit.com/r/selfhosted/comments/1g7unas/hosting_netbird_coordination_server_and](https://www.reddit.com/r/selfhosted/comments/1g7unas/hosting_netbird_coordination_server_and)
 - RSS feed: $source
 - date published: 2024-10-20T09:09:29+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I‘m currently trying to selfhost NetBird on my raspberry pi 4 to connect to my peers at home. Meanwhile I use the same device to host a homeassistant instance with docker.</p> <p>NetBird needs a wide range of UDP ports open (49152-65535) which intersect some of the ports used by homeassistant.</p> <p>Are there any special risks with these intersecting UDP ports and are there counter-measurements to take in order to harden the setup? </p> <p>As I understand the NetBird Udp connections are secured but what about HA?</p> <p>I read that the udp port range for NetBird is configurable, however, I did not find any official information for HA ports and as I understand some of them are randomly assigned for traffic between smart devices.</p> <p>Thanks in advance for your help! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kinguuusama"> /u/kinguuusama </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/com

## Please help me with my media server
 - [https://www.reddit.com/r/selfhosted/comments/1g7uktm/please_help_me_with_my_media_server](https://www.reddit.com/r/selfhosted/comments/1g7uktm/please_help_me_with_my_media_server)
 - RSS feed: $source
 - date published: 2024-10-20T09:04:09+00:00

<!-- SC_OFF --><div class="md"><p>Help me set up my media server chain</p> <p>I mostly play 4K/HDR Remux movies so there is quite a bit of power needed. 1Gbps speeds across the board, all streaming happens within LAN. </p> <p>My current setup:</p> <p>Synology DS218+ Play to store data Nvidia Shield running Plex Server and used as a media player. I have an external SSD plugged in to the shield where the server stores Plex metadata etc.</p> <p>Now I have a Lenovo ThinClient running my other server stuff (HA, Arrstack etc) which has 8gb of DDR4 RAM, an NVME SSD and an Intel i5 6500T.</p> <p>During the last year my Plex server on the Shield became pretty sluggish, super slow to scan and add media. Also sometimes it flat out refuses to play heavy files or even crashes the entire Shield to the point of rebooting (sometimes even during playback).</p> <p>My question is: </p> <ul> <li>Would I notice a performance uplift if I move the Plex Server to my thinclient which has more compute power? <

## is my home server killing hard drives?
 - [https://www.reddit.com/r/selfhosted/comments/1g7ujtt/is_my_home_server_killing_hard_drives](https://www.reddit.com/r/selfhosted/comments/1g7ujtt/is_my_home_server_killing_hard_drives)
 - RSS feed: $source
 - date published: 2024-10-20T09:02:02+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g7ujtt/is_my_home_server_killing_hard_drives/"> <img src="https://b.thumbs.redditmedia.com/uLuiKVhfbDv9IdSeZF6UkMsgpzzyqqsQQ9yoPNWOclo.jpg" alt="is my home server killing hard drives?" title="is my home server killing hard drives?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>i didn&#39;t have the original mounting hardware for this pc, some knock off that doesn&#39;t fit perfectly tho.<br/> i can feel the case vibrating when the drives are spinning; i read somewhere that it might cause drive failure. </p> <p>i&#39;ve checked the SMART data and the raw value for read error rate almost doubled in just a few hours (i turn the server off at night since i&#39;m the only one using it and i still haven&#39;t connected the ups i bought) </p> <p>smart data attached below.</p> <p><a href="https://preview.redd.it/3cw0rk5klvvd1.png?width=900&amp;format=png&amp;auto=webp&amp;s=b4c1f41c5a8ff9bf47b3372f79ba69a88dd97438">

## Open Source alternative to Termius iOS?
 - [https://www.reddit.com/r/selfhosted/comments/1g7txva/open_source_alternative_to_termius_ios](https://www.reddit.com/r/selfhosted/comments/1g7txva/open_source_alternative_to_termius_ios)
 - RSS feed: $source
 - date published: 2024-10-20T08:14:13+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/brightestsummer"> /u/brightestsummer </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7txva/open_source_alternative_to_termius_ios/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7txva/open_source_alternative_to_termius_ios/">[comments]</a></span>

## Flaresolverr lite replacement for Jackett
 - [https://www.reddit.com/r/selfhosted/comments/1g7tnlp/flaresolverr_lite_replacement_for_jackett](https://www.reddit.com/r/selfhosted/comments/1g7tnlp/flaresolverr_lite_replacement_for_jackett)
 - RSS feed: $source
 - date published: 2024-10-20T07:52:41+00:00

<!-- SC_OFF --><div class="md"><p>Flaresolverr don&#39;t work anymore for some of my torrent website. So I rewrite a little this tool to make it compatible with Jackett, feel free to try it 😊:</p> <p><a href="https://github.com/nlevee/CloudflareBypassForScraping">https://github.com/nlevee/CloudflareBypassForScraping</a> </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Illustrious_Comb_216"> /u/Illustrious_Comb_216 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7tnlp/flaresolverr_lite_replacement_for_jackett/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7tnlp/flaresolverr_lite_replacement_for_jackett/">[comments]</a></span>

## Transferring Certificates and CSRs From VM Root CA
 - [https://www.reddit.com/r/selfhosted/comments/1g7thj2/transferring_certificates_and_csrs_from_vm_root_ca](https://www.reddit.com/r/selfhosted/comments/1g7thj2/transferring_certificates_and_csrs_from_vm_root_ca)
 - RSS feed: $source
 - date published: 2024-10-20T07:39:26+00:00

<!-- SC_OFF --><div class="md"><p>I want to store my root CA in an offline VM without a network adapter. How do I transfer CSR and Certificates? Turn off all but Root CA and Intermediate CA VMs, add a network card, transfer via SSH and be done with it? I don&#39;t really want to go down the HSM route because at home, I don&#39;t have other people to worry about messing with the root CA. Or is there a better way?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Jastibute"> /u/Jastibute </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7thj2/transferring_certificates_and_csrs_from_vm_root_ca/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7thj2/transferring_certificates_and_csrs_from_vm_root_ca/">[comments]</a></span>

## What do you recommend for a cheap dedicated server for x265 encoding?
 - [https://www.reddit.com/r/selfhosted/comments/1g7tbvp/what_do_you_recommend_for_a_cheap_dedicated](https://www.reddit.com/r/selfhosted/comments/1g7tbvp/what_do_you_recommend_for_a_cheap_dedicated)
 - RSS feed: $source
 - date published: 2024-10-20T07:27:09+00:00

<!-- SC_OFF --><div class="md"><p>I cut costs and built a server at home, but my life has been a pain since then because managing it takes up all my time. I&#39;m willing to build another server if I can automate the process, such as having torrent files automatically download and then converting them to x265 using HandBrake (with either GPU or CPU for fast processing). How can I set up this automation? What do you recommend for a server, CPUs, or GPUs?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rezaro2"> /u/rezaro2 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7tbvp/what_do_you_recommend_for_a_cheap_dedicated/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7tbvp/what_do_you_recommend_for_a_cheap_dedicated/">[comments]</a></span>

## PSA: Open Source AI tool ScreenPipe harvests your data without your permission
 - [https://www.reddit.com/r/selfhosted/comments/1g7srjm/psa_open_source_ai_tool_screenpipe_harvests_your](https://www.reddit.com/r/selfhosted/comments/1g7srjm/psa_open_source_ai_tool_screenpipe_harvests_your)
 - RSS feed: $source
 - date published: 2024-10-20T06:45:57+00:00

<!-- SC_OFF --><div class="md"><p>If you star the repo, they will harvest your email and add you to marketing lists without your permission</p> <p><a href="https://github.com/mediar-ai/screenpipe/issues/405">https://github.com/mediar-ai/screenpipe/issues/405</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SnooTangerines6956"> /u/SnooTangerines6956 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7srjm/psa_open_source_ai_tool_screenpipe_harvests_your/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7srjm/psa_open_source_ai_tool_screenpipe_harvests_your/">[comments]</a></span>

## Selfhosting on a minipc
 - [https://www.reddit.com/r/selfhosted/comments/1g7soik/selfhosting_on_a_minipc](https://www.reddit.com/r/selfhosted/comments/1g7soik/selfhosting_on_a_minipc)
 - RSS feed: $source
 - date published: 2024-10-20T06:39:49+00:00

<!-- SC_OFF --><div class="md"><p>Hey. All of you who are hosting on a minipc with an APU, do you and can you passthrough the GPU? For a while i was using proxmox with couple of VMs. One for windows (just running game server) and couple for different self hosted apps. I had trouble with Jellyfin as it didn’t allow me to transcode. So I switched it all up and now am using Windows 11, with docker, portainer and jellyfin with all the arr’s. What’s the best practice? Windows seems to work fine but i really want a bit more freedom and for my selfhosted stuff not to clash in a single OS.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Rouziys"> /u/Rouziys </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7soik/selfhosting_on_a_minipc/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7soik/selfhosting_on_a_minipc/">[comments]</a></span>

## Simple NAS without Docker etc.
 - [https://www.reddit.com/r/selfhosted/comments/1g7sdxz/simple_nas_without_docker_etc](https://www.reddit.com/r/selfhosted/comments/1g7sdxz/simple_nas_without_docker_etc)
 - RSS feed: $source
 - date published: 2024-10-20T06:17:40+00:00

<!-- SC_OFF --><div class="md"><p>My current NAS is a bit outdated (Synology DS213j) and all services have already been moved to a home server running a Lenovo m920q (16 GB). </p> <p>So I need a separate very basic 2 Bay NAS (assuming that I cannot add external HDDs to the Lenovo). Budget would be 200 Euros as I can get a basic QNAP or Synology for this price. Any recommendations besides these obvious off-the-shelf solutions.</p> <p>Edit: I&#39;d like to setup RAID 1 for the two drives. Are there any downsides on attaching the drives simply via USB (except for accidentally pulling the cable).</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Super-Dot5910"> /u/Super-Dot5910 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7sdxz/simple_nas_without_docker_etc/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7sdxz/simple_nas_without_docker_etc/">[comments]</a></span>

## Email hosting
 - [https://www.reddit.com/r/selfhosted/comments/1g7rz0f/email_hosting](https://www.reddit.com/r/selfhosted/comments/1g7rz0f/email_hosting)
 - RSS feed: $source
 - date published: 2024-10-20T05:47:31+00:00

<!-- SC_OFF --><div class="md"><p>I have migrated my websites from Bluehost Wordpress to a self-managed VPS on Linode using Hestia.</p> <p>Unfortunately Linode does not allow adding an email server. My email is still with Bluehist, but it is expesive.</p> <p>What options do I have? - Way to host email server on Linode? - Alternative imap email provider?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/danderzei"> /u/danderzei </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7rz0f/email_hosting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7rz0f/email_hosting/">[comments]</a></span>

## Using restic to backup linux
 - [https://www.reddit.com/r/selfhosted/comments/1g7qwnu/using_restic_to_backup_linux](https://www.reddit.com/r/selfhosted/comments/1g7qwnu/using_restic_to_backup_linux)
 - RSS feed: $source
 - date published: 2024-10-20T04:33:25+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g7qwnu/using_restic_to_backup_linux/"> <img src="https://preview.redd.it/mcwuee1jauvd1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=dcd3d3dd6d36e429a865b01429213751d50b7b66" alt="Using restic to backup linux" title="Using restic to backup linux" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/No_Departure_1878"> /u/No_Departure_1878 </a> <br/> <span><a href="https://i.redd.it/mcwuee1jauvd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7qwnu/using_restic_to_backup_linux/">[comments]</a></span> </td></tr></table>

## Caddy is magic. Change my mind
 - [https://www.reddit.com/r/selfhosted/comments/1g7pfd3/caddy_is_magic_change_my_mind](https://www.reddit.com/r/selfhosted/comments/1g7pfd3/caddy_is_magic_change_my_mind)
 - RSS feed: $source
 - date published: 2024-10-20T03:01:12+00:00

<!-- SC_OFF --><div class="md"><p>In a past life I worked a little with NGINGX, not a sysadmin but I checked configs periodically and if i remember correctly it was a pretty standard Json file format. Not hard, but a little bit of a learning curve. </p> <p>Today i took the plunge to setup Caddy to finally have ssl setup for all my internally hosted services. Caddy is like &quot;Yo, just tell me what you want and I&#39;ll do it.&quot; Then it did it. Now I have every service with its own cert on my Synology NAS. </p> <p>Thanks everyone who told people to use a reverse proxy for every service that they wanted to enable https. You guided me to finally do this. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FilterUrCoffee"> /u/FilterUrCoffee </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7pfd3/caddy_is_magic_change_my_mind/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7pfd3/caddy_i

## Update multiple Cloudflare subdomains- Clouldflare DDNS
 - [https://www.reddit.com/r/selfhosted/comments/1g7p8ie/update_multiple_cloudflare_subdomains_clouldflare](https://www.reddit.com/r/selfhosted/comments/1g7p8ie/update_multiple_cloudflare_subdomains_clouldflare)
 - RSS feed: $source
 - date published: 2024-10-20T02:49:51+00:00

<!-- SC_OFF --><div class="md"><p>SO I recently installed the Cloudflare-DDNS docker on my unRAID server and was dissapointed to learn it can only update a domain or subdomain. I&#39;m currently running 4 subdomains and need a way to update the IPs on all of them.</p> <p>I&#39;ve been doing some googling and I see mention of somehow accomplishing this with CNAMES, but I don&#39;t understand how since you can&#39;t direct a single CNAME to multiple subdomains. </p> <p>Can someone ELI5 for me on how to user CNAMES to accomplish what I&#39;m trying to do?</p> <p>Thanks in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AHoss75"> /u/AHoss75 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7p8ie/update_multiple_cloudflare_subdomains_clouldflare/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7p8ie/update_multiple_cloudflare_subdomains_clouldflare/">[comments]</a></span>

## Picture viewer from different folders with diashow function and preview?
 - [https://www.reddit.com/r/selfhosted/comments/1g7oqfo/picture_viewer_from_different_folders_with](https://www.reddit.com/r/selfhosted/comments/1g7oqfo/picture_viewer_from_different_folders_with)
 - RSS feed: $source
 - date published: 2024-10-20T02:19:46+00:00

<!-- SC_OFF --><div class="md"><p>I search for a picture viewer that shows my galleries from many folders. I need to select a folder and start the diashow. But only the content from that folder. And I need a preview for every folder that shows the first 1–3 pictures in it. It would be great if I also had the option to switch between diashow and manual swipe.</p> <p>What can I self-host that fits my requirements?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Raners96"> /u/Raners96 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7oqfo/picture_viewer_from_different_folders_with/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g7oqfo/picture_viewer_from_different_folders_with/">[comments]</a></span>

## Looking for a self-hosted alternative to Mapstr
 - [https://www.reddit.com/r/selfhosted/comments/1g7nzd6/looking_for_a_selfhosted_alternative_to_mapstr](https://www.reddit.com/r/selfhosted/comments/1g7nzd6/looking_for_a_selfhosted_alternative_to_mapstr)
 - RSS feed: $source
 - date published: 2024-10-20T01:37:09+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://en.mapstr.com/">Mapstr</a> is an app and web app to save, organize, and share locations on a map by categories (using tags). It&#39;s much more useful that Google Maps to store and share cool spots in different categories like restaurants, bars, coffees, parks, etc. </p> <p>Unfortunately Mapstr recently switched to a freemium subscription model in which one needs to pay to save more than 300 addresses and access other features. I was already ambivalent about saving all this information in a closed source proprietary database, but this was the last straw for me.</p> <p>What would be the best open source / self-hosted alternative to Mapstr? Does it even exist? I&#39;m not just talking about map/navigation apps, but something to save and tag locations by categories, with a nice interface to easily filter addresses by tags. I couldn&#39;t find anything close to that but maybe this community has some suggestions!</p> </div><!-- SC_ON --> &

