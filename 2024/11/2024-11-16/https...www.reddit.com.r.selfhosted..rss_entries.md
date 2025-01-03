# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## FDE (LUKS) - Proxmox vs. Docker, nested virtualization, VPS, root-server...
 - [https://www.reddit.com/r/selfhosted/comments/1gt055l/fde_luks_proxmox_vs_docker_nested_virtualization](https://www.reddit.com/r/selfhosted/comments/1gt055l/fde_luks_proxmox_vs_docker_nested_virtualization)
 - RSS feed: $source
 - date published: 2024-11-16T23:35:11+00:00

<!-- SC_OFF --><div class="md"><p>I have been using FDE on my computers for as long as I can remember. That is the first and most important thing for me. Also on my smartphone (LineageOS).</p> <p>I have been practicing with Proxmox (Proxmos OS) on my server at home for some time now and all in all I like Proxmox very much compared to Docker.</p> <p>Now I&#39;m thinking about whether and how to realize an FDE. With Proxmox I would have to throw away Proxmox OS and replace it with Debian to use LUKS during Debian installation and then on Debian Proxmox.</p> <p>Or Ubuntu (I prefer Ubuntu) with LUKS and Docker on top?</p> <p>The thing is this: I want to rent server and move my services to them, e.g. Memos, Traccar, Synapse, Nextcloud. Probably nothing more. So no VMs. Nothing big, few users. Now I have read that some providers do not offer nested virtualization in order to be able to use Proxmox without any problems. Had Netcup in my sights. But I don&#39;t know if this is related to the

## Best ways to use AI?
 - [https://www.reddit.com/r/selfhosted/comments/1gt00vu/best_ways_to_use_ai](https://www.reddit.com/r/selfhosted/comments/1gt00vu/best_ways_to_use_ai)
 - RSS feed: $source
 - date published: 2024-11-16T23:29:35+00:00

<!-- SC_OFF --><div class="md"><p>selfhosting involves a lot managing and organizing your data.</p> <p>What are the best tools that use AI to help you with this? It could be used for -</p> <ul> <li>renaming files based on content, e.g. <a href="https://github.com/ozgrozer/ai-renamer">https://github.com/ozgrozer/ai-renamer</a></li> <li>using AI to classify data, organize into folders, add tags etc</li> <li>detect and remove duplicates not just based on binary match or hash match, but AI analysis</li> <li>summarizing documents/videos</li> <li>optimizing (e.g. clean html), converting to other formats</li> <li>finding relationships within data</li> <li>traditional uses that have been around for a long time e.g. face detection, photo tagging/similarity etc</li> </ul> <p>There are probably many more uses, I see videos of people talking about using AI agents to do all kinds of stuff. </p> <p>e.g. I have a lot of documents in html/mhtml/pdf etc saved from all over the web, social media etc -

## Careful of backscatter with forwardemail
 - [https://www.reddit.com/r/selfhosted/comments/1gszz0l/careful_of_backscatter_with_forwardemail](https://www.reddit.com/r/selfhosted/comments/1gszz0l/careful_of_backscatter_with_forwardemail)
 - RSS feed: $source
 - date published: 2024-11-16T23:27:02+00:00

<!-- SC_OFF --><div class="md"><p><em>Disclaimer: Email forwarding is indeed part of my self-host and de-googling efforts.</em></p> <p>Just wanted to share an awful customer service experience I had with forwardemail. Ended up switching over to mailwip out of desperation.</p> <p>tldr; If you&#39;re currently hosting with forwardmail, be sure to check and see if you&#39;re on the backscatter blacklist and if certain providers are refusing to send email to you.</p> <p>You can also simply put in any of their mx DNS names in mxtoolbox to check: <a href="https://mxtoolbox.com/emailhealth/mx1.forwardemail.net/">https://mxtoolbox.com/emailhealth/mx1.forwardemail.net/</a></p> <p>(As of this post, they&#39;ve been on it for quite a few months now. <a href="https://www.reddit.com/r/selfhosted/comments/1c1bzll/aws_route52_forwardemailnet_some_senders_emails/">Maybe this is related?</a> It sure sounds familiar!)</p> <p>You can also check with the backscatter database directly: <a href="http://ww

## unable to change directory owner in ubuntu
 - [https://www.reddit.com/r/selfhosted/comments/1gszu05/unable_to_change_directory_owner_in_ubuntu](https://www.reddit.com/r/selfhosted/comments/1gszu05/unable_to_change_directory_owner_in_ubuntu)
 - RSS feed: $source
 - date published: 2024-11-16T23:20:18+00:00

<!-- SC_OFF --><div class="md"><p>Hi </p> <p>I have a proxmox setup. I have a truenas machine for storage and a ubuntu server for docker. I have the truenas smb mounted in a directory on ubuntu but this directory is owned by root. I dont know maybe because it a mount point i am noob so yeah. I got running plex on docker with its files in that mounted directory but because its owned by root cant really write so yeah i keep getting error in logs saying &quot;terminating with uncaught exception of type boost::filesystem::filesystem_error: boost::filesystem::create_directories: Permission denied [system:13]: &quot;/config/Library/Application Support/Plex Media Server/Cache&quot;, &quot;/config/Library/Application Support/Plex Media Server&quot;&quot; I am guessing its because of the permissions.</p> <p>so i have tried using chmod to change permmissions and i have even used chown to change the owner of the directory but the command does run without an error however when i check the owner 

## Living without a mobile phone... Self hosted VoIP
 - [https://www.reddit.com/r/selfhosted/comments/1gszh3i/living_without_a_mobile_phone_self_hosted_voip](https://www.reddit.com/r/selfhosted/comments/1gszh3i/living_without_a_mobile_phone_self_hosted_voip)
 - RSS feed: $source
 - date published: 2024-11-16T23:02:46+00:00

<!-- SC_OFF --><div class="md"><p>So my cell carrier finally retired an awesome plan that I had been on for years which was costing AUD $12/month and with respects to my usage patterns was effectively unlimited. Now the cheapest plan is over double. That got me thinking about how in reality I hardly use my mobile (as a telephone) since it is basically just a portable mini computer.</p> <p>I already have a free SIP phone service bundled with my ISP internet connection. </p> <p>As I see it, there are a couple of issues;</p> <p>Handset: I already own my handset outright and can easily get a cheep data only SIM for when I am not in WiFi range.</p> <p>Calls: Would need to run a SIP handset/PBX that connects to my ISP SIP server. I have Bria on my phone currently and have found that works well.</p> <p>Voicemail: Would probably need a SIP PBX function on one or more of my servers for this.</p> <p>Messaging: WhatsApp, iMessage, SMS - Do any of these work without a mobile number to be tied ba

## Anyone selfhosting Documenso with Dokploy here?
 - [https://www.reddit.com/r/selfhosted/comments/1gsy1d9/anyone_selfhosting_documenso_with_dokploy_here](https://www.reddit.com/r/selfhosted/comments/1gsy1d9/anyone_selfhosting_documenso_with_dokploy_here)
 - RSS feed: $source
 - date published: 2024-11-16T21:54:41+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I&#39;m new to this and currently trying to deploy Documenso using Dokploy with raw and .env (not using the Dokploy Documenso template since it&#39;s outdated). Everything seems to work well except for one issue: when signing up, the verification email doesn&#39;t get sent. However, I was able to receive the password reset email when testing that feature.</p> <p>The logs show the following: </p> <p><code>Submitting job to endpoint: -http://duco-doc-eahdx5-3d33bc-167-71-39-42.traefik.me/api/jobs/send.signup.confirmation.email/cm3kid5if0000qf2135ev3zg0</code> </p> <p>But nothing happens after that.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/altingrc"> /u/altingrc </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsy1d9/anyone_selfhosting_documenso_with_dokploy_here/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsy1d9/anyone_selfhostin

## ControlD \ SmartDNS but selfhosted
 - [https://www.reddit.com/r/selfhosted/comments/1gsxxul/controld_smartdns_but_selfhosted](https://www.reddit.com/r/selfhosted/comments/1gsxxul/controld_smartdns_but_selfhosted)
 - RSS feed: $source
 - date published: 2024-11-16T21:49:52+00:00

<!-- SC_OFF --><div class="md"><p>is there any project that allows you to <strong>redirect</strong> any domain name, service or app, entire TLD, or all browsing activity via transparent proxies. masks the end-user IP address from the destination.</p> <p>NOT A VPN(!!!)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sea-Share9578"> /u/Sea-Share9578 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsxxul/controld_smartdns_but_selfhosted/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsxxul/controld_smartdns_but_selfhosted/">[comments]</a></span>

## Hardware setup puzzler?
 - [https://www.reddit.com/r/selfhosted/comments/1gsxn3y/hardware_setup_puzzler](https://www.reddit.com/r/selfhosted/comments/1gsxn3y/hardware_setup_puzzler)
 - RSS feed: $source
 - date published: 2024-11-16T21:35:42+00:00

<!-- SC_OFF --><div class="md"><p>I have an HP G3 tower with a 7th gen i7 - great for a Plex server. I’ve built it out and it’s working great - however when I bought it i thought it had capacity for at least four drives and it doesn’t. </p> <p>Can anyone recommend a solution to run a minimum of a 4 3.5in hard drive raid setup outside the main case? Preferably DIY but if thats not an option… seriously considered just running the power and sata outside the case but I’m not sure that’s the right move </p> <p>What do you think?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/stirrednotshaken01"> /u/stirrednotshaken01 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsxn3y/hardware_setup_puzzler/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsxn3y/hardware_setup_puzzler/">[comments]</a></span>

## binhex-qbittorrentvpn and privado vpn - issue with password
 - [https://www.reddit.com/r/selfhosted/comments/1gsxmys/binhexqbittorrentvpn_and_privado_vpn_issue_with](https://www.reddit.com/r/selfhosted/comments/1gsxmys/binhexqbittorrentvpn_and_privado_vpn_issue_with)
 - RSS feed: $source
 - date published: 2024-11-16T21:35:30+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to get the binhex-qbittorrentvpn docker image up and running. For reasons, I have privado vpn for free through a bundle with some other services, so I was trying to get that up and running as my vpn provider on the docker image. However, I keep getting &#39;auth failed&#39; in the logs.</p> <ul> <li>I have checked that I can connect through the normal privado vpn client (so yes, I remember my password)</li> <li>I have downloaded a .ovpn file from the privado vpn site and the docker image is able to find that just fine (in config/openvpn)</li> </ul> <p>I am fairly certain that the issue is the following: The binhex docker image explicitly recommends to have no special characters in the VPN password. However, the privado vpn enforces that you must have at least one special character in the password. Hence, I can&#39;t change the password on the connection to something without special chars in it. The binhex doc indicates that special chars 

## The Proxmox Corosync Fallacy
 - [https://www.reddit.com/r/selfhosted/comments/1gsx76a/the_proxmox_corosync_fallacy](https://www.reddit.com/r/selfhosted/comments/1gsx76a/the_proxmox_corosync_fallacy)
 - RSS feed: $source
 - date published: 2024-11-16T21:15:05+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/esiy0676"> /u/esiy0676 </a> <br/> <span><a href="https://www.reddit.com/r/Proxmox/comments/1gsujv1/the_proxmox_corosync_fallacy/?utm_source=share&amp;utm_medium=web3x&amp;utm_name=web3xcss&amp;utm_term=1&amp;utm_content=share_button">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsx76a/the_proxmox_corosync_fallacy/">[comments]</a></span>

## Selfhost panel without dns / mail?
 - [https://www.reddit.com/r/selfhosted/comments/1gswzpf/selfhost_panel_without_dns_mail](https://www.reddit.com/r/selfhosted/comments/1gswzpf/selfhost_panel_without_dns_mail)
 - RSS feed: $source
 - date published: 2024-11-16T21:05:29+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>&#39;m looking for something similar to CPW but without DNS and MAIL functions.</p> <p>I use external DNS and mail servers...</p> <p>Is there an interesting alternative?</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/adiif1"> /u/adiif1 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gswzpf/selfhost_panel_without_dns_mail/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gswzpf/selfhost_panel_without_dns_mail/">[comments]</a></span>

## How to restart a docker container remotely?
 - [https://www.reddit.com/r/selfhosted/comments/1gswpp5/how_to_restart_a_docker_container_remotely](https://www.reddit.com/r/selfhosted/comments/1gswpp5/how_to_restart_a_docker_container_remotely)
 - RSS feed: $source
 - date published: 2024-11-16T20:52:19+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys,</p> <p>I&#39;m having some trouble with WireGuard running on my Raspberry Pi 4. It works well most of the time, but occasionally it stops working without any error messages in the logs.</p> <p>The only solution I&#39;ve found is to simply restart the container. Unfortunately, when this happens, I&#39;m usually not home and can&#39;t access my local network to perform the restart.</p> <p>That&#39;s why I&#39;m looking for a way to remotely restart the container. I was considering creating a Telegram bot for this purpose. I found this project on GitHub: <a href="https://github.com/satishsverma/dockerSDK_telegeram_python">https://github.com/satishsverma/dockerSDK_telegeram_python</a></p> <p>However, I&#39;m unsure if this is a safe project to use and if there might be other options available.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Plastic-Address-4882"> /u/Plastic-Address-4882 </a> <br/> <span><a 

## Alternative to Been
 - [https://www.reddit.com/r/selfhosted/comments/1gswosb/alternative_to_been](https://www.reddit.com/r/selfhosted/comments/1gswosb/alternative_to_been)
 - RSS feed: $source
 - date published: 2024-11-16T20:51:09+00:00

<!-- SC_OFF --><div class="md"><p>Is there alternstive to Been app, where tou can track which countries I and my SO have visited?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lapiuslt"> /u/lapiuslt </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gswosb/alternative_to_been/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gswosb/alternative_to_been/">[comments]</a></span>

## Any good alternatives to a samba server with the same functionality but better performance?
 - [https://www.reddit.com/r/selfhosted/comments/1gswmej/any_good_alternatives_to_a_samba_server_with_the](https://www.reddit.com/r/selfhosted/comments/1gswmej/any_good_alternatives_to_a_samba_server_with_the)
 - RSS feed: $source
 - date published: 2024-11-16T20:48:00+00:00

<!-- SC_OFF --><div class="md"><p>Im using samba on my raspberry pi 4 to transfer most of the time small files from my laptop. I noticed that the speeds arent great the mounted volume that is used is on an external ssd are there any optimasations i can do to the existing setup or should i look for alternatives? I know the pi isnt the most powerfull for this </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Giannis_Dor"> /u/Giannis_Dor </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gswmej/any_good_alternatives_to_a_samba_server_with_the/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gswmej/any_good_alternatives_to_a_samba_server_with_the/">[comments]</a></span>

## I'm gonna screw it all up. Well, sort-of but not exactly a disaster.
 - [https://www.reddit.com/r/selfhosted/comments/1gsuzsu/im_gonna_screw_it_all_up_well_sortof_but_not](https://www.reddit.com/r/selfhosted/comments/1gsuzsu/im_gonna_screw_it_all_up_well_sortof_but_not)
 - RSS feed: $source
 - date published: 2024-11-16T19:31:48+00:00

<!-- SC_OFF --><div class="md"><p>I have a MiniPC at home on which I run docker containers for the applications I need. Each application has backups, so all good here. I&#39;m behind my ISP&#39;s CGNAT, so I have a VPS on which I run nginx and have it forward everything back to my home server via Wireguard. I have backups of my nginx config, so this is also fine.</p> <p>So this is how things were for a while. Then I started adding more applications like Asterisk on-premise, which meant I had to do port forwarding from the VPS to my home address. I started maintaining a backup of my firewalld zones as well. Then I added ZNC as an IRC bouncer on the VPS itself. Over time I forgot what all I did on the VPS. There&#39;s firewall rules, there&#39;s modified systemd services (eg. I modify a service to run after another service has started), and I no longer have a track of everything due to my bad habit of doing everything directly on the server itself.</p> <p>At the specific moment, I foun

## How to: redirect the PiHole DNS Block to a meaningful page via nginx reverse proxy.
 - [https://www.reddit.com/r/selfhosted/comments/1gsuskp/how_to_redirect_the_pihole_dns_block_to_a](https://www.reddit.com/r/selfhosted/comments/1gsuskp/how_to_redirect_the_pihole_dns_block_to_a)
 - RSS feed: $source
 - date published: 2024-11-16T19:22:41+00:00

<!-- SC_OFF --><div class="md"><p>Respected Self-Hosted community,<br/> No matter what I do, I can&#39;t figure this one out. I want to be able to redirect the users on my network to a better page with the ability of asking me to open the URL. I can&#39;t figure the pihole to nginx redirection.<br/> Here is the setup:<br/> Pihole: <a href="http://10.0.1.53">10.0.1.53</a><br/> Nginx Docker: <a href="http://10.0.1.101:40080">10.0.1.101:40080</a><br/> I have below code:<br/> <code>&lt;!DOCTYPE html&gt;</code></p> <p><code>&lt;html&gt;</code></p> <p><code>&lt;head&gt;</code></p> <p><code>&lt;title&gt;Blocked by Office Admin&lt;/title&gt;</code></p> <p><code>&lt;style&gt;</code></p> <p><code>body { font-family: Arial, sans-serif; text-align: center; margin-top: 50px; }</code></p> <p><code>button { padding: 10px 20px; font-size: 16px; cursor: pointer; }</code></p> <p><code>&lt;/style&gt;</code></p> <p><code>&lt;/head&gt;</code></p> <p><code>&lt;body&gt;</code></p> <p><code>&lt;h1&gt;This S

## Fully customizable and extendable self-hosted open source video conferencing
 - [https://www.reddit.com/r/selfhosted/comments/1gsun55/fully_customizable_and_extendable_selfhosted_open](https://www.reddit.com/r/selfhosted/comments/1gsun55/fully_customizable_and_extendable_selfhosted_open)
 - RSS feed: $source
 - date published: 2024-11-16T19:15:47+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;m looking for a self-hosted open source video conferencing library for node.js. It should be fully customizable/extendable because I want to for example add plugin with whiteboard that meet all my needs (like excalidraw) and instead using simple chat with basic features, I want to use my own chat component that for example allows Latex as well (I&#39;m using react). I started to search and Big Blue Button looks very interesting as it is dedicated for educational purposes and I&#39;m wondering whether there are other alternatives (I heard about jitsi) and whether BBB and these alternatives are custimizable in the way I described. I would really appreciate every feedback! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/degel12345"> /u/degel12345 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsun55/fully_customizable_and_extendable_selfhosted_open/">[link]</a></span> &#32; <span

## Is there any kind of hosted music discovery like the playlists Spotify makes for similar music/artists?
 - [https://www.reddit.com/r/selfhosted/comments/1gsuk1y/is_there_any_kind_of_hosted_music_discovery_like](https://www.reddit.com/r/selfhosted/comments/1gsuk1y/is_there_any_kind_of_hosted_music_discovery_like)
 - RSS feed: $source
 - date published: 2024-11-16T19:12:00+00:00

<!-- SC_OFF --><div class="md"><p>About the only reason I still have Spotify is because it&#39;s the only way for me to really find new music and artists similar to my tastes. Is there any type of self hosted solution for this? It doesn&#39;t necessarily need to be able to download anything automatically, I just want recommendations and discovery.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tge101"> /u/tge101 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsuk1y/is_there_any_kind_of_hosted_music_discovery_like/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsuk1y/is_there_any_kind_of_hosted_music_discovery_like/">[comments]</a></span>

## THE Reverse Proxy (secure)
 - [https://www.reddit.com/r/selfhosted/comments/1gsuhxe/the_reverse_proxy_secure](https://www.reddit.com/r/selfhosted/comments/1gsuhxe/the_reverse_proxy_secure)
 - RSS feed: $source
 - date published: 2024-11-16T19:09:22+00:00

<!-- SC_OFF --><div class="md"><p>Hello there,</p> <p>I&#39;m trying to find THE self hosted Reverse Proxy Server. I guess, I&#39;m tried them all. </p> <p>For now I&#39;m running swag and everything work. Okay. But...</p> <p>First of all, I&#39;m running a Synology DS 920+ with roundabout 40 Container, a Proxmox on a Mini-PC with about 10 LXC and 2 Raspberrys. I don&#39;t want to cut Port 443 and 80 from the Synology. My FritzBox could of course send the ports to another IP. </p> <p>My Intention is, running a RP on one of the Rapsberrys. I really love traefik, because it can run Containers on demand. That is nice I guess. </p> <p>The biggest Problem is, that running traefik on one &quot;server&quot; can&#39;t see the other Instances. Like a swarm (thats what it called I guess). So the RP-Thing worked with a dynamic.yml, with SSL and everthing. BasicAuth worked, CrowdSec worked. </p> <p>Which RP are you using? Is it secure? </p> <p>VPN isn&#39;t a option, because I want to put some s

## Deciding on how to host Website, Email, and some other stuff
 - [https://www.reddit.com/r/selfhosted/comments/1gstwvj/deciding_on_how_to_host_website_email_and_some](https://www.reddit.com/r/selfhosted/comments/1gstwvj/deciding_on_how_to_host_website_email_and_some)
 - RSS feed: $source
 - date published: 2024-11-16T18:43:32+00:00

<!-- SC_OFF --><div class="md"><p>Long story short.</p> <p>I&#39;ve purchased my dream domain, and I&#39;m looking to host the following things:</p> <ul> <li>Small static personal website</li> <li>Email Server so I can send and receive from my domain</li> <li>Not a thing immediately, but maybe later I&#39;d like to host stuff like game servers, home automation or Cloud Storage, private wikis, and other small apps and projects</li> </ul> <p>I have got a beginners experience with Linux, SSH, etc, in the sense that I can work my way through some tutorials and, with some guidance, achieve simple goals like setting up a CMS in Docker and so on, but I wouldn&#39;t say I exactly understand every implication or have deep knowledge of what the architecture is like, especially moving into security.</p> <p>As I see it, the options I have are:</p> <ul> <li>Hosting on a spare machine at home (bad, expensive, and a really big security issue)</li> <li>Hosting on a VPS / Dedicated Server (difference

## m4b-maker - A bash script that automates the creation of M4B audiobooks from various audio formats, such as MP3, WAV, and FLAC, with flexible options for organizing chapters.
 - [https://www.reddit.com/r/selfhosted/comments/1gstup7/m4bmaker_a_bash_script_that_automates_the](https://www.reddit.com/r/selfhosted/comments/1gstup7/m4bmaker_a_bash_script_that_automates_the)
 - RSS feed: $source
 - date published: 2024-11-16T18:40:48+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://github.com/weak-head/m4b-maker">https://github.com/weak-head/m4b-maker</a></p> <p>This script automates the creation of an M4B audiobook from various audio formats, such as MP3, WAV, and FLAC, with flexible options for organizing chapters.</p> <p>By default, chapters are created from individual files in the specified directory. However, using the <code>--chapters-from-dirs</code> flag, each subdirectory becomes a single chapter, combining all audio files within it.</p> <p>Chapter titles are generated from metadata, directory names, or filenames, preserving the original order for a consistent audiobook structure.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/weak-head"> /u/weak-head </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gstup7/m4bmaker_a_bash_script_that_automates_the/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gstup7/

## How long should ffmpeg take to burn subtitles
 - [https://www.reddit.com/r/selfhosted/comments/1gstdsm/how_long_should_ffmpeg_take_to_burn_subtitles](https://www.reddit.com/r/selfhosted/comments/1gstdsm/how_long_should_ffmpeg_take_to_burn_subtitles)
 - RSS feed: $source
 - date published: 2024-11-16T18:19:47+00:00

<!-- SC_OFF --><div class="md"><p>I’m trying to burn subtitles for I don’t use a lot of resources for my players. But I don’t want to change any video quality. I have a lot of movies and I want to calculate how much time I need</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/anonuser-al"> /u/anonuser-al </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gstdsm/how_long_should_ffmpeg_take_to_burn_subtitles/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gstdsm/how_long_should_ffmpeg_take_to_burn_subtitles/">[comments]</a></span>

## Signal Proxy Sever?
 - [https://www.reddit.com/r/selfhosted/comments/1gstd13/signal_proxy_sever](https://www.reddit.com/r/selfhosted/comments/1gstd13/signal_proxy_sever)
 - RSS feed: $source
 - date published: 2024-11-16T18:18:48+00:00

<!-- SC_OFF --><div class="md"><p>Is there any simple docker compose file to host proxy for signal, which would work behind ReverseProxy?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/d4p8f22f"> /u/d4p8f22f </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gstd13/signal_proxy_sever/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gstd13/signal_proxy_sever/">[comments]</a></span>

## monitarr - A simple Sonarr/Radarr download monitor
 - [https://www.reddit.com/r/selfhosted/comments/1gst4rd/monitarr_a_simple_sonarrradarr_download_monitor](https://www.reddit.com/r/selfhosted/comments/1gst4rd/monitarr_a_simple_sonarrradarr_download_monitor)
 - RSS feed: $source
 - date published: 2024-11-16T18:08:05+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gst4rd/monitarr_a_simple_sonarrradarr_download_monitor/"> <img src="https://external-preview.redd.it/AFGOWUn-5qQk6qNHfk-AVHX7kqr3518LBeaBQHLH3as.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=665e34d316b3d4a7401f16cbc33f3c8d5b4ce518" alt="monitarr - A simple Sonarr/Radarr download monitor" title="monitarr - A simple Sonarr/Radarr download monitor" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I wanted a simple way for other users who made requests using Overseerr/Jellyseerr to see the download progress of their requests without giving them access to the Sonarr/Radarr web interface, or asking me for updates. So here it is, monitarr:</p> <p><a href="https://preview.redd.it/t8o7077b0b1e1.png?width=1523&amp;format=png&amp;auto=webp&amp;s=7fe220d5500c45ab440df4ba9ba6d98b9cfefd43">https://preview.redd.it/t8o7077b0b1e1.png?width=1523&amp;format=png&amp;auto=webp&amp;s=7fe220d5500c45ab440df4ba9ba6d98b9cfefd43</a>

## Opinions on upgrading out of RAID 1
 - [https://www.reddit.com/r/selfhosted/comments/1gssdbe/opinions_on_upgrading_out_of_raid_1](https://www.reddit.com/r/selfhosted/comments/1gssdbe/opinions_on_upgrading_out_of_raid_1)
 - RSS feed: $source
 - date published: 2024-11-16T17:33:40+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gssdbe/opinions_on_upgrading_out_of_raid_1/"> <img src="https://b.thumbs.redditmedia.com/pGAVjJXVGcfU3QkcTStDN8AVMjDLjSVcDA9niSSngtQ.jpg" alt="Opinions on upgrading out of RAID 1" title="Opinions on upgrading out of RAID 1" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I currently use a master pool of data for my Plex media (Movies, Music, TV), full desktop backups, eBooks, and pretty much all of my files since I was a teenager on a 14tb RAID 1 setup (2x 14tb drives, in a OWC Raid Enclosure). I am using a Mac as my main host for this RAID. </p> <p><a href="https://preview.redd.it/0rs7cunfta1e1.png?width=1659&amp;format=png&amp;auto=webp&amp;s=ef22a83125bbdea5335d5dd00f9deb5736e661e6">https://preview.redd.it/0rs7cunfta1e1.png?width=1659&amp;format=png&amp;auto=webp&amp;s=ef22a83125bbdea5335d5dd00f9deb5736e661e6</a></p> <p>I still have plenty of space to work with, but I am wondering is it would be worth it t

## Any Dashboard recommendations for my home server ?
 - [https://www.reddit.com/r/selfhosted/comments/1gsrlex/any_dashboard_recommendations_for_my_home_server](https://www.reddit.com/r/selfhosted/comments/1gsrlex/any_dashboard_recommendations_for_my_home_server)
 - RSS feed: $source
 - date published: 2024-11-16T16:58:56+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/No_Classic_4588"> /u/No_Classic_4588 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsrlex/any_dashboard_recommendations_for_my_home_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsrlex/any_dashboard_recommendations_for_my_home_server/">[comments]</a></span>

## Is Tailscale with Mullvad exit nodes too good to be true?
 - [https://www.reddit.com/r/selfhosted/comments/1gsq9pi/is_tailscale_with_mullvad_exit_nodes_too_good_to](https://www.reddit.com/r/selfhosted/comments/1gsq9pi/is_tailscale_with_mullvad_exit_nodes_too_good_to)
 - RSS feed: $source
 - date published: 2024-11-16T15:58:19+00:00

<!-- SC_OFF --><div class="md"><p>So I just recently had my internet shut down by my ISP for copyrighted torrents (darn grandma requesting Season 5 of Yellowstone, I just couldn&#39;t resist her. I knew that recent of a release was gonna have someone spying on the torrents. I typically only torrent older material most of the time and I don&#39;t have any trouble with that.) so I figured that it was beyond time that I buckle down, be a man, and do the right thing ... figure out how to route all my torrent traffic through a VPN provider that could shield my ISP and I from any spies trying to report my IP address for torrenting.</p> <p>With that in mind, I just recently set up my Tailscale account set up with a Mullvad exit node and I almost can not believe how easy it was compared to the guides I had read through for setting up gluetun as an exit node. I feel like I am missing something here - is it really this easy to set up and does it actually work as intended if I set it up this wa

## How to add reverse proxy with oidc auth?
 - [https://www.reddit.com/r/selfhosted/comments/1gspzqw/how_to_add_reverse_proxy_with_oidc_auth](https://www.reddit.com/r/selfhosted/comments/1gspzqw/how_to_add_reverse_proxy_with_oidc_auth)
 - RSS feed: $source
 - date published: 2024-11-16T15:45:25+00:00

<!-- SC_OFF --><div class="md"><p>Hi all! I have a bunch of self hosted services accessible through cloudflared tunnel. While cloudflared auth capabilities are awesome, I would like to use one passcode for bunch of services instead of standard apps auth (bypass built-in apps auth altogether).</p> <p>I tried to setup oidc + oauth2-proxy + traefik with no success - maybe I’m just too dumb for this.</p> <p>Is there any simple all-in-one solution for this? Or maybe some other <em>simple</em> approach?</p> <p>Security is not a priority - it’s handled well by cloudflare + my services are not publicly available (dashboard through cloudflare and other apps using vpn). Main goal is convenience and usability.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Arioh002"> /u/Arioh002 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gspzqw/how_to_add_reverse_proxy_with_oidc_auth/">[link]</a></span> &#32; <span><a href="https://www.reddit.

## Anything for emulators?
 - [https://www.reddit.com/r/selfhosted/comments/1gsp0vh/anything_for_emulators](https://www.reddit.com/r/selfhosted/comments/1gsp0vh/anything_for_emulators)
 - RSS feed: $source
 - date published: 2024-11-16T14:59:35+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>Currently looking for a way to be able to host my emulators from my server. I saw many form of emulation software like retropie, retroarch, retrobat, emulationstation but all of these are made to be installed on a dedicated machine (well can be also shared with a pc itself, but I mean you install it on the computer you will play from). My idea is to be able to play my emulation game from anything.</p> <p>I know emulatorjs exist, I tried it many time and it&#39;s even installed on docker of my server but it&#39;s not working very good. Audio is crappy and it crash often.</p> <p>I don&#39;t think it exist what I&#39;m looking for though.</p> <p>Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nodiaque"> /u/nodiaque </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsp0vh/anything_for_emulators/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/s

## Which machine to use for immich and jellyfin
 - [https://www.reddit.com/r/selfhosted/comments/1gso72w/which_machine_to_use_for_immich_and_jellyfin](https://www.reddit.com/r/selfhosted/comments/1gso72w/which_machine_to_use_for_immich_and_jellyfin)
 - RSS feed: $source
 - date published: 2024-11-16T14:17:26+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>At the moment I&#39;m hosting my jellyfin instance on my laptop and I love it. However I have a big collection of music DVD that I would like to digitalize and move on jellyfin.</p> <p>I also would like to get out from Google photo and host immich as well.</p> <p>I&#39;m looking for a dedicated machine to handle both of this scenario. I was considering a Zima board with 2 4tb SSD.to have in raid for backup.</p> <p>I would like to use docker for this.</p> <p>Do you have any suggestion? </p> <p>Great thanks :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Worldly-Ad-7149"> /u/Worldly-Ad-7149 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gso72w/which_machine_to_use_for_immich_and_jellyfin/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gso72w/which_machine_to_use_for_immich_and_jellyfin/">[comments]</a></span>

## Weird wireguard behavior - connection unstable
 - [https://www.reddit.com/r/selfhosted/comments/1gso3dl/weird_wireguard_behavior_connection_unstable](https://www.reddit.com/r/selfhosted/comments/1gso3dl/weird_wireguard_behavior_connection_unstable)
 - RSS feed: $source
 - date published: 2024-11-16T14:12:01+00:00

<!-- SC_OFF --><div class="md"><p>I’m stuck with a wireguard problem which I really cannot wrap my head around. I have 4 devices:</p> <ol> <li>My Phone → Android with WG-Tunnel App</li> <li>My Laptop → Fedora 41 with GNOME</li> <li>My Server → wg-easy in a docker container</li> <li>Another Server → router wireguard tunnel feature</li> </ol> <p>I want to connect my phone and laptop to my home network. I set up wg-easy on my home server, enabled port forwarding at the router and created two clients in the web config. I scan the first one with my phone, put it on cellular to get out of my home network and enable the tunnel. Works perfectly fine, I can access all my local services as if I’m in my network directly.</p> <p>Great! Now I continue with the laptop. Download the config file, add it to the GNOME Network/VPN section via the auto import from file feature and enable it. Seems to work. The wg-easy web GUI shows activity which very quickly drops to 0 in and out. Note: The laptop is c

## Trackly - A web app for tracking Jellyfin music artist releases (Update v1.1.0)
 - [https://www.reddit.com/r/selfhosted/comments/1gsnbo3/trackly_a_web_app_for_tracking_jellyfin_music](https://www.reddit.com/r/selfhosted/comments/1gsnbo3/trackly_a_web_app_for_tracking_jellyfin_music)
 - RSS feed: $source
 - date published: 2024-11-16T13:31:35+00:00

<!-- SC_OFF --><div class="md"><h1>TRACKLY - VERSION 1.1.0</h1> <p><a href="https://github.com/7eventy7/trackly">https://github.com/7eventy7/trackly</a></p> <p>Trackly is a web app that helps you track music artist releases from your Jellyfin library. This update brings some major improvements that many of you have been asking for.</p> <p><strong>What&#39;s New in 1.1.0:</strong></p> <p><strong><em>- Brand New Multi-Page Interface</em></strong> - Added a brand new web UI with a sleek modern look</p> <p><strong><em>- Backend Improvements</em></strong> - Reworked the core architecture for better stability and performance</p> <p><strong><em>- Flexible Integrations</em></strong> - Discord notifications are now optional and can be toggle with a container variable.</p> <p><strong><em>- Fresh Look</em></strong> - Updated app icon with a modern design that better matches the new interface</p> <p><em>&gt; Plus the usual bug fixes and dependency updates to keep everything running smoothly.</em

## Self hosted everything
 - [https://www.reddit.com/r/selfhosted/comments/1gsmujr/self_hosted_everything](https://www.reddit.com/r/selfhosted/comments/1gsmujr/self_hosted_everything)
 - RSS feed: $source
 - date published: 2024-11-16T13:05:12+00:00

<!-- SC_OFF --><div class="md"><p>Since I set up a Plex and arr server I&#39;ve been self-hosting a lot more stuff like immich and home Assistant. </p> <p>Me and the wife have been trying to get better control over our lives, so I&#39;ve been considering how instead of using the Google solutions self-hosting like a calendar app and a note-taking app and other things that tie together like you can make a grocery list for a specific grocery run and then add the note to an event on a calendar for grocery run. Stuff like that. </p> <p>Is there any good multi-purpose calendar/notaking/etc self-hosted apps? If you all get what I mean, wasn&#39;t really sure how to word this.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dylon0107"> /u/dylon0107 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsmujr/self_hosted_everything/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsmujr/self_hosted_

## What are some things to host as a beginner? (pihole, minecraft and home asssistent already installed)
 - [https://www.reddit.com/r/selfhosted/comments/1gsmro6/what_are_some_things_to_host_as_a_beginner_pihole](https://www.reddit.com/r/selfhosted/comments/1gsmro6/what_are_some_things_to_host_as_a_beginner_pihole)
 - RSS feed: $source
 - date published: 2024-11-16T13:00:46+00:00

<!-- SC_OFF --><div class="md"><p>I want to get into the world of selfhosting.</p> <p>Bought a NUC with 16g of ram and already set up pihole, minecraftserver and home assistent.</p> <p>But there are so MANY services you could self host...sooo what are some nice recommendations?</p> <p>Thought about calibre web for my ebooks and maybe mextcloud, but apart from that, i dont know where to start. I dont have many movies or music, so thats crossed out.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mynotell"> /u/mynotell </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsmro6/what_are_some_things_to_host_as_a_beginner_pihole/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsmro6/what_are_some_things_to_host_as_a_beginner_pihole/">[comments]</a></span>

## Invidious Limited to Max 1080p
 - [https://www.reddit.com/r/selfhosted/comments/1gsm532/invidious_limited_to_max_1080p](https://www.reddit.com/r/selfhosted/comments/1gsm532/invidious_limited_to_max_1080p)
 - RSS feed: $source
 - date published: 2024-11-16T12:21:20+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve setup and Invdious instance through Docker and have dash set. I&#39;ve tried setting multiple different options in settings, auto, best, 1440p, 2160p, 4320p but no matter what I select, videos are limited to 1080p max.</p> <p>I&#39;ve also tried multiple different browsers. Chrome, Firefox, Edge all with and without js enabled I still do not get any further options beyond 1080p despite the videos I am testing on being 1440p and up. I&#39;m not sure why, as far as I can tell through the documentation and multiple GitHub reports, setting dash should allow me to view videos at higher than 1080p.</p> <p>Edit: I&#39;ve tried with other Invidious instances on the GitHub page and none of them have anything above 1080p either.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ReclusiveEagle"> /u/ReclusiveEagle </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsm532/invidious_limited_to_max_

## Redirect loop Apache behind Reverse Proxy
 - [https://www.reddit.com/r/selfhosted/comments/1gskh05/redirect_loop_apache_behind_reverse_proxy](https://www.reddit.com/r/selfhosted/comments/1gskh05/redirect_loop_apache_behind_reverse_proxy)
 - RSS feed: $source
 - date published: 2024-11-16T10:22:03+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I am trying to self host an application based on Code Igniter. The default .htaccess the developer provided is this inside /www/public_html/.htaccess (now .htaccess_)</p> <p><code>RewriteEngine on</code></p> <p><code>RewriteBase /</code></p> <p><code># Allow access to PHP scripts in all directories</code></p> <p><code># Ensure HTTPS</code></p> <p><code>RewriteCond %{HTTPS} !=on</code></p> <p><code>RewriteRule ^ https://%{HTTP_HOST}%{REQUEST_URI} [L,R=301]</code></p> <p><code># Serve existing files or directories directly</code></p> <p><code>RewriteCond %{REQUEST_FILENAME} -f [OR]</code></p> <p><code>RewriteCond %{REQUEST_FILENAME} -d</code></p> <p><code>RewriteRule ^ - [L]</code></p> <p><code># Allow access to other file types</code></p> <p><code># Fallback to index.php</code></p> <p><code>RewriteRule ^([^.]+)$ /index.php?node=$1 [QSA,L]</code></p> <p>with this .htaccess, the website doesn&#39;t even open since it&#39;s stuck in a redir

## Jellyfin gets wrong data for certain TV show. Manually entered MovieDB id but it didn't change.
 - [https://www.reddit.com/r/selfhosted/comments/1gsjns9/jellyfin_gets_wrong_data_for_certain_tv_show](https://www.reddit.com/r/selfhosted/comments/1gsjns9/jellyfin_gets_wrong_data_for_certain_tv_show)
 - RSS feed: $source
 - date published: 2024-11-16T09:19:35+00:00

<!-- SC_OFF --><div class="md"><p>The show in question is The Life and Times of Tim (MovieDB: <a href="https://www.themoviedb.org/tv/5921-the-life-times-of-tim">https://www.themoviedb.org/tv/5921-the-life-times-of-tim</a>) so the id is 5921 right?</p> <p>I entered that and when I tried to metadata refresh it said &quot;Refresh Queued.&quot; Couldn&#39;t find the queue or anything about it refreshing within my system so I &quot;End Task&quot; Jellyfin in Task Manager and started it up again. The show info/posters/background is still wrong. Help?</p> <p>I&#39;ve entered 6 other shows so far and everything&#39;s been fine, it&#39;s just this one. Yes, I followed the Documentation guide for naming.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TheRadHatter9"> /u/TheRadHatter9 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsjns9/jellyfin_gets_wrong_data_for_certain_tv_show/">[link]</a></span> &#32; <span><a href="https://w

## An unbelievable RCE and there will be no fix. Just buy a new one.
 - [https://www.reddit.com/r/selfhosted/comments/1gsj65y/an_unbelievable_rce_and_there_will_be_no_fix_just](https://www.reddit.com/r/selfhosted/comments/1gsj65y/an_unbelievable_rce_and_there_will_be_no_fix_just)
 - RSS feed: $source
 - date published: 2024-11-16T08:41:49+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gsj65y/an_unbelievable_rce_and_there_will_be_no_fix_just/"> <img src="https://external-preview.redd.it/iY4sHaq0RpaiNuZV6ramx7GBN8HGmteRPzltwlb7MI0.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=13cbd14d1af78cf2a2f34747964a6bca0308970a" alt="An unbelievable RCE and there will be no fix. Just buy a new one. " title="An unbelievable RCE and there will be no fix. Just buy a new one. " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Nas should not be exposed to internet anyway, but just a reminder to be careful. And DLink should address this exploit, eol or not, if you ask me. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/msoulforged"> /u/msoulforged </a> <br/> <span><a href="https://youtu.be/-vpGswuYVg8?si=9iRVlYcmZ7UTvLQb">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsj65y/an_unbelievable_rce_and_there_will_be_no_fix_just/">[com

## Mail Server for Internal Emails?
 - [https://www.reddit.com/r/selfhosted/comments/1gsitn5/mail_server_for_internal_emails](https://www.reddit.com/r/selfhosted/comments/1gsitn5/mail_server_for_internal_emails)
 - RSS feed: $source
 - date published: 2024-11-16T08:14:49+00:00

<!-- SC_OFF --><div class="md"><p>As you know for some self hosted services you need to provide SMTP information so that the service can reset passwords and communicate other information.</p> <p>I&#39;m currently using a free SMTP service, but I am wondering whether it would be interesting to self host email for the purpose of managing these emails.</p> <p>I know it&#39;s not a practical option to self host <em>real</em> email addresses due to spam issues, domain authority etc.</p> <p>Has anyone else done this? Any pros / cons? Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/chastimty"> /u/chastimty </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsitn5/mail_server_for_internal_emails/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsitn5/mail_server_for_internal_emails/">[comments]</a></span>

## Is my website secure
 - [https://www.reddit.com/r/selfhosted/comments/1gsimc2/is_my_website_secure](https://www.reddit.com/r/selfhosted/comments/1gsimc2/is_my_website_secure)
 - RSS feed: $source
 - date published: 2024-11-16T08:00:28+00:00

<!-- SC_OFF --><div class="md"><p>Hello i programmed a website for my community, first i build a subreddit, but it is very big geworden,</p> <p>and then i make more communities on other platforms</p> <p>and i have bestellt this domain <a href="http://katzenkommando.de">katzenkommando.de</a> with HTTPS,</p> <p>first i want to now if you can steuer my router at http</p> <p>Sry, I come from Germany.</p> <p>Can someone pantest, but no hacking!!! only pentest</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dream_Byte_Studios"> /u/Dream_Byte_Studios </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsimc2/is_my_website_secure/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsimc2/is_my_website_secure/">[comments]</a></span>

## Just bought a domain. Scared to open services to the public. Am I covering everything?
 - [https://www.reddit.com/r/selfhosted/comments/1gsg9kt/just_bought_a_domain_scared_to_open_services_to](https://www.reddit.com/r/selfhosted/comments/1gsg9kt/just_bought_a_domain_scared_to_open_services_to)
 - RSS feed: $source
 - date published: 2024-11-16T05:23:00+00:00

<!-- SC_OFF --><div class="md"><p>Hello all,</p> <p>I am currently in college, studying data science. I also am big into self hosting and data hoarding. I have a few services running such as jellyfin, immich, etc. Everything runs in docker containers using compose files. I recently bought a domain to make accessing my wireguard VPN easier for my grandmother. I used to just have the public ip as the endpoint, but now have a domain that I configured to forward to my public ip. </p> <p>Now that I have a domain though, I thought it would be a nice opportunity to learn about hosting web apps. Im trying to make a dashboard about my projects that I could put on my resume. My server is located at my parents house, so the endpoint will be their router. There are no VLANS or anything, but only ports 22 and wireguard are open. SSH is protected by key pair auth. Here&#39;s where I&#39;m starting to get scared:</p> <p>I don&#39;t know enough about security to be confident I&#39;m covering everyth

## Can someone tell me about an app that can access the camera, audio, video, and screen of an Android phone, and is also free?
 - [https://www.reddit.com/r/selfhosted/comments/1gsezp2/can_someone_tell_me_about_an_app_that_can_access](https://www.reddit.com/r/selfhosted/comments/1gsezp2/can_someone_tell_me_about_an_app_that_can_access)
 - RSS feed: $source
 - date published: 2024-11-16T04:01:12+00:00

<!-- SC_OFF --><div class="md"><p>Please share me some name.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/wolf-wit-brain"> /u/wolf-wit-brain </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsezp2/can_someone_tell_me_about_an_app_that_can_access/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsezp2/can_someone_tell_me_about_an_app_that_can_access/">[comments]</a></span>

## Streamsphere
 - [https://www.reddit.com/r/selfhosted/comments/1gsej1d/streamsphere](https://www.reddit.com/r/selfhosted/comments/1gsej1d/streamsphere)
 - RSS feed: $source
 - date published: 2024-11-16T03:34:23+00:00

<!-- SC_OFF --><div class="md"><p>Hello to all,</p> <p>I am an independent developer, and I&#39;ve made a front end to yt-dlp (although I intend to extend its functionality a lot more).</p> <p>Here it is -<br/> <a href="https://github.com/rs-anantmishra/streamsphere/">https://github.com/rs-anantmishra/streamsphere/</a></p> <p>This is an initial release, just to get it out and get some feedback on it before I spend more time on it. Many more features and performance and stability improvements will be made in the coming months!</p> <p>Please let me know if you like it! :-)</p> <p>Thanks!</p> <p>Reddit Community: <a href="https://www.reddit.com/r/StreamsphereApp/">https://www.reddit.com/r/StreamsphereApp/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Zestyclose-Bed8882"> /u/Zestyclose-Bed8882 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsej1d/streamsphere/">[link]</a></span> &#32; <span><a href="https://www.reddit.

## NFS and vLan security
 - [https://www.reddit.com/r/selfhosted/comments/1gse6bo/nfs_and_vlan_security](https://www.reddit.com/r/selfhosted/comments/1gse6bo/nfs_and_vlan_security)
 - RSS feed: $source
 - date published: 2024-11-16T03:14:59+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve always used vlans for IoT and CCTV, but recently starting to getting in a bit deeper to separate external and internal traffic. There&#39;s quite a bit learning but all straight forward until NFS.</p> <p>So I have next cloud running in a VM on external vLan, but I had the actual file storage mounted via NFS from NAS which is on management vLan.</p> <p>The reason I had the files externally mounted is that in case of VM diester crash, at least I can access the files easily rather than trying to fix the VM or trying to mount vm-disk file.</p> <p>But this NFS creates a glaring security hole in theory.</p> <p>There would be many ways patching that, but I&#39;m not sure what most people would consider best approach. In my case, the next cloud is used by family and friends, on internet but not advertised</p> <p>I can think of following</p> <ul> <li>scrap the external file storage idea</li> <li>route NFS traffic via firewall, but no idea performance

## Is there any self hosted solution to get notifications from deals website when new deal gets posted ?
 - [https://www.reddit.com/r/selfhosted/comments/1gsczis/is_there_any_self_hosted_solution_to_get](https://www.reddit.com/r/selfhosted/comments/1gsczis/is_there_any_self_hosted_solution_to_get)
 - RSS feed: $source
 - date published: 2024-11-16T02:08:06+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a self host solution where I can get notified whenever new deal gets posted under specific section on website. I was looking at ntfy but it takes me to changedetection.io which is a paid solution. Sorry I am all new to this and came up with this idea if it’s possible. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dsandhu90"> /u/dsandhu90 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsczis/is_there_any_self_hosted_solution_to_get/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsczis/is_there_any_self_hosted_solution_to_get/">[comments]</a></span>

## Could a VPS run a self-hosted ChatGPT/LLM?
 - [https://www.reddit.com/r/selfhosted/comments/1gscjho/could_a_vps_run_a_selfhosted_chatgptllm](https://www.reddit.com/r/selfhosted/comments/1gscjho/could_a_vps_run_a_selfhosted_chatgptllm)
 - RSS feed: $source
 - date published: 2024-11-16T01:44:36+00:00

<!-- SC_OFF --><div class="md"><p>Apologies for what I am sure is an incredibly basic question but I&#39;ve seen loads of open source and self-hostable LLMs and generative Ai options. Do they all require a robust system and GPU or are there any that could reasonably run on a VPS of some kind? If so, what would be the minimum specs for a usable level of performance</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/elroypaisley"> /u/elroypaisley </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gscjho/could_a_vps_run_a_selfhosted_chatgptllm/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gscjho/could_a_vps_run_a_selfhosted_chatgptllm/">[comments]</a></span>

## HDD vs SSD suggestion
 - [https://www.reddit.com/r/selfhosted/comments/1gsauns/hdd_vs_ssd_suggestion](https://www.reddit.com/r/selfhosted/comments/1gsauns/hdd_vs_ssd_suggestion)
 - RSS feed: $source
 - date published: 2024-11-16T00:16:24+00:00

<!-- SC_OFF --><div class="md"><p>I have HP Prodesk 600 G4 SFF. Currently have three 2.5 SSD.</p> <ul> <li>2.5&quot; 256GB Boot</li> <li>2.5&quot; 4TB SSD - Main storage</li> <li>2.5&quot; 240GB Backup</li> <li>2.5&quot; 240GB HDD - This is from old laptop. Not in use</li> </ul> <p>I also do backups on my two external HDD.</p> <ul> <li>1TB External HDD</li> <li>4TB External HDD - Currently failing. So I can&#39;t relay on this on a long run</li> </ul> <p>I am thinking to buy another drive and confused which path to choose from:</p> <ul> <li>Buy 10TB 3.5&quot; NAS Drive ~ $190 <ul> <li>My configuration would be <ul> <li>2.5&quot; 256GB SSD for Ubuntu</li> <li>4TB 2.5&quot; for storage</li> <li>10TB HDD as backup</li> </ul></li> </ul></li> <li>4TB NVME SSD ~ $228 <ul> <li>My configuration would be <ul> <li>2.5&quot; 256GB SSD for Ubuntu</li> <li>4TB NVME for storage</li> <li>4TB 2.5&quot; as backup</li> </ul></li> </ul></li> <li>1TB NVME SSD ~ $60 <ul> <li>My configuration would be <ul

## SearXNG over TailScale — weekend project
 - [https://www.reddit.com/r/selfhosted/comments/1gsamzk/searxng_over_tailscale_weekend_project](https://www.reddit.com/r/selfhosted/comments/1gsamzk/searxng_over_tailscale_weekend_project)
 - RSS feed: $source
 - date published: 2024-11-16T00:05:47+00:00

<!-- SC_OFF --><div class="md"><p>For those with Tailscale, this gem just came out today. </p> <p>Found my weekend project: </p> <p><a href="https://youtu.be/cg9d87PuanE?si=y8SrRwgu02xsCfCF">https://youtu.be/cg9d87PuanE?si=y8SrRwgu02xsCfCF</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Wasted-Friendship"> /u/Wasted-Friendship </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsamzk/searxng_over_tailscale_weekend_project/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsamzk/searxng_over_tailscale_weekend_project/">[comments]</a></span>

