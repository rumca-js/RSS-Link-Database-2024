# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## AdGuard Home and Pihole Together?
 - [https://www.reddit.com/r/selfhosted/comments/1ewgnt1/adguard_home_and_pihole_together](https://www.reddit.com/r/selfhosted/comments/1ewgnt1/adguard_home_and_pihole_together)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T23:34:01+00:00

<!-- SC_OFF --><div class="md"><p>Hi All,</p> <p>I want to have valid SSL certificates for my local services and believe that I can set this up using nginx, a domain name, and pihole. </p> <p>As part of this I have now setup Pihole with Unbound in Docker. I also have an OPNSense router that seems to use Unbound by default. </p> <p>I'm wondering what the most robust solution would be for my needs in terms of DNS and would love to get your feedback. Two options I am considering:</p> <ol> <li><p>Use my OPNSense DHCP to point clients to Pihole and Unbound in Docker. Then have AdGuard Home and Unbound installed on my OPNSense upstream to that. Reason being that I can benefit from two different ad blocking lists from the different services which surely are not identical? I expect there would be some performance hit/latency from this chained approach, but if it's not too big I like the added protection this could offer. Another downside is that there are more things that can break and need d

## Thoughts on my first homelab setup plan
 - [https://www.reddit.com/r/selfhosted/comments/1ewg8n8/thoughts_on_my_first_homelab_setup_plan](https://www.reddit.com/r/selfhosted/comments/1ewg8n8/thoughts_on_my_first_homelab_setup_plan)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T23:14:14+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>Finally about to take the plunge into building a small homelab for myself. I managed to grab a server recently that I have kitted out hardware wise to what I think is passable.</p> <p>What I have:</p> <ul> <li>PowerEdge T430 <ul> <li>Xeon CPU E5-2630 v3 2.40GHz</li> <li>64GB (4x16 in quad channel) DDR4-2400 ECC server memory</li> <li>2.5&quot; Samsung Evo SSD (for OS)</li> <li>3x <a href="https://m.media-amazon.com/images/I/513TZZrdXRL._AC_UF894,1000_QL80_.jpg">2.0TB WD Red</a> (RAID 5)</li> <li>5x <a href="https://serverdiskdrives.com/cdn/shop/products/3C46W.jpg?v=1696385922">1.0TB Dell</a> (RAID 5 or 6, unsure which to go with)</li> </ul></li> </ul> <p>For OS, I am planning on running Proxmox server to run various VMs for different purposes (original, right?). Right now I have a few 'wants' for VMs:</p> <ol> <li>TrueNAS - File storage for my network</li> <li>Navidrome/Jellyfin host - Looking to host my music so I can access inte

## Domain name not working in some situations
 - [https://www.reddit.com/r/selfhosted/comments/1ewg055/domain_name_not_working_in_some_situations](https://www.reddit.com/r/selfhosted/comments/1ewg055/domain_name_not_working_in_some_situations)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T23:03:37+00:00

<!-- SC_OFF --><div class="md"><p>i can't access my new website through my domain on some devices/browsers, it throws a <code>NS_ERROR_UNKNOWN_HOST</code> error. the domain should be set up correctly though.</p> <p>here's all the important details i can think of. i've highlighted some important stuff, mostly things that seem to come up as solutions first when i look this up.</p> <ul> <li>the domain <strong>has an AAAA record</strong> pointing to my static ipv6 (ds-lite, so no ipv4) <ul> <li>i have given it time to propagate, and dnschecker is all green</li> <li>nslookup and ping both return the correct ipv6</li> </ul></li> <li><strong>i can access the server if i put the exact same ipv6 into my address bar</strong>, on all devices (ie the server is working correctly and is listening on the appropriate ports, and is accessible through the internet)</li> <li>in <code>about:networking#dns</code> on firefox, and the equivalent page on chrome, <strong>i can see both the domain and the corr

## Self Hosting a OneNote type application
 - [https://www.reddit.com/r/selfhosted/comments/1ewemei/self_hosting_a_onenote_type_application](https://www.reddit.com/r/selfhosted/comments/1ewemei/self_hosting_a_onenote_type_application)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T22:05:17+00:00

<!-- SC_OFF --><div class="md"><p>Morning all, </p> <p>I have been trying to find a good alternative for OneNote that I would be able to host on my Home Lab, if you know of anything please let me know. </p> <p>I am slowly removing Microsoft and Google products from my usage and moving to my own hosted applications. </p> <p>Thanks in advanced. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FusionOz"> /u/FusionOz </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ewemei/self_hosting_a_onenote_type_application/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ewemei/self_hosting_a_onenote_type_application/">[comments]</a></span>

## My ISP dropped its SMTP server. What are my options ?
 - [https://www.reddit.com/r/selfhosted/comments/1ewejsw/my_isp_dropped_its_smtp_server_what_are_my_options](https://www.reddit.com/r/selfhosted/comments/1ewejsw/my_isp_dropped_its_smtp_server_what_are_my_options)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T22:02:21+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>My self hosted webserver requires to be able to send emails to my users using my custom domain. I have set a Mailu server with SMTP/IMAP on my server.</p> <p>My ISP blocks outbout ports for emails, so I can't directly use my SMTP server to send emails. I have to use a relayhost.</p> <p>My ISP, until a week ago, provided its SMTP server for everyone with a subscription to access. I could use that as a relayhost.</p> <p>But now, they completely dropped it. So I need to find another way. I was thinking of using another SMTP server provided by another email provider, but I am unsure about what is required for it to be compatible, and what provider to choose. My server sends very few email but I still need to be sure that they won't be blocked as spam or rate limited. Which provider do you recommend ?</p> <p>Apart from the option of another SMTP provider, is there another solution I didn't think of to send emails from my Mailu server ?</p> <p>Th

## qBittorrent Port Update
 - [https://www.reddit.com/r/selfhosted/comments/1ewc6h4/qbittorrent_port_update](https://www.reddit.com/r/selfhosted/comments/1ewc6h4/qbittorrent_port_update)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T20:26:20+00:00

<!-- SC_OFF --><div class="md"><p>I've added an update to my qBittorrent port update script. It now supports fetching container_id (id in the form of name or id) from the config file to start and stop it.</p> <p><a href="https://github.com/royborgen/qbt_port_update">https://github.com/royborgen/qbt_port_update</a></p> <p>About the script:<br /> This is a Python script designed to automate the integration between Gluetun and qBittorrent Docker containers. The script fetches the forward port number from the Gluetun container's config location and updates the qBittorrent container's configuration to use this port. It stops and starts the qBittorrent container as well.</p> <p>I use this script alongside a cron job to execute daily, ensuring that the Gluetun forward port is updated post any Watchtower-initiated container updates and restarts and server reboots.</p> <p>Here is a con job example</p> <pre><code>15 * * * * /usr/bin/python3 /home/user/scripts/qbt_port_update/qbt_port_update.py 

## Web content filter.
 - [https://www.reddit.com/r/selfhosted/comments/1ewbnzk/web_content_filter](https://www.reddit.com/r/selfhosted/comments/1ewbnzk/web_content_filter)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T20:06:28+00:00

<!-- SC_OFF --><div class="md"><pre><code>Is there a web content filter, such as NXFilter, but which requires login when the user starts browsing? I have a situation with a client where a private institution wants to open up the internet to people but wants each person to have their own user, both to define blocking levels and to generate specific reports on certain users. As the idea is for users to be able to use their own devices, we can even talk about installing client software on the equipment, but it would have to exist in the AppStore and PlayStore, for example, to be practical. Thanks in advance. </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/queiroz-rogerio"> /u/queiroz-rogerio </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ewbnzk/web_content_filter/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ewbnzk/web_content_filter/">[comments]</a></span>

## Apps for accessing and sharing to SMB Shares from Android?
 - [https://www.reddit.com/r/selfhosted/comments/1ewbfxf/apps_for_accessing_and_sharing_to_smb_shares_from](https://www.reddit.com/r/selfhosted/comments/1ewbfxf/apps_for_accessing_and_sharing_to_smb_shares_from)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T19:57:52+00:00

<!-- SC_OFF --><div class="md"><p>Hello fellow self hosters!</p> <p>I have recently started setting up my own NAS using Ubuntu Server for most flexibility.</p> <p>The final step to get my family to adopt the new System is an Android App for easy access to the server.</p> <p>The App should:<br /> - Allow browsing the NAS' Files<br /> - Allow Uploads with the Share Function in other apps<br /> - Not collect any personal data etc</p> <p>If the App requires a Backend it would ideally be a docker container.<br /> I also have SMB Shares set up already that could be used if there is a good client out there.</p> <p>Thanks for your help in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Velyn_"> /u/Velyn_ </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ewbfxf/apps_for_accessing_and_sharing_to_smb_shares_from/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ewbfxf/apps_for_accessing_an

## Docker converged host vs multiple based on service?
 - [https://www.reddit.com/r/selfhosted/comments/1ewbf6e/docker_converged_host_vs_multiple_based_on_service](https://www.reddit.com/r/selfhosted/comments/1ewbf6e/docker_converged_host_vs_multiple_based_on_service)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T19:56:58+00:00

<!-- SC_OFF --><div class="md"><p>Right now, I have proxmox cluster of a few mini pcs. For my self hosting needs, I run a few VMs, couple of single app LXCs for various reasons, and then my 50 some odd docker containers are spread over 5 LXCs on multiple hosts. I’ve got them split into : - media servers/manipulators (Audiobookshelf, kavita, etc) - other apps (bookstack, draw io, etc) - monitoring - control (semaphore, iot stuff, ldap, etc) - VPN stuff</p> <p>Everything in its own app folder with its own docker compose a la dockge recommended format. I originally did this such that if I need to take down a host for some reason, rather than migrating, I could just live without one set of services or the other for a moment without taking everything down. Swarm and k8s are on my to-learn list, but I’m not there yet unfortunately. VPN host mainly because my old setup included a static VPN tunnel at the router level, so easy just to add that ip to the alias.</p> <p>While I’ve automated as m

## Looking for Recommendations: Email Service Provider for Sending/Receiving Emails
 - [https://www.reddit.com/r/selfhosted/comments/1ewb62h/looking_for_recommendations_email_service](https://www.reddit.com/r/selfhosted/comments/1ewb62h/looking_for_recommendations_email_service)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T19:46:42+00:00

<!-- SC_OFF --><div class="md"><p>Hey folks, </p> <p>I’m in the process of setting up email functionality for my project and could use some advice on choosing the right email service provider. </p> <p>My current use case is fairly simple, but I want to future-proof my setup: </p> <p><strong>Current Use Case:</strong> </p> <ul> <li><strong>Sending:</strong> <ul> <li>Registration confirmation emails </li> <li>Password reset links </li> <li>Occasional promotional/informational emails </li> </ul></li> <li><strong>Receiving:</strong> <ul> <li>No heavy incoming email operations, but I’d like to set up a basic receiving system.</li> </ul></li> </ul> <p><strong>Requirements:</strong> </p> <ul> <li><strong>Cost:</strong> The project currently has no paying users, so keeping costs low is a priority. </li> <li><strong>Deliverability:</strong> Ensuring emails don’t end up in spam is crucial. </li> <li><strong>Complexity:</strong> I have a dev background, so I’m okay with a more complex setup if i

## Matrix server lag but only on certain devices
 - [https://www.reddit.com/r/selfhosted/comments/1ewak5m/matrix_server_lag_but_only_on_certain_devices](https://www.reddit.com/r/selfhosted/comments/1ewak5m/matrix_server_lag_but_only_on_certain_devices)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T19:22:09+00:00

<!-- SC_OFF --><div class="md"><p>a few months ago I started hosting a matrix server using the element client and it has been running very well so far. however, seemingly overnight, messages and videos have been loading extremely slowly/not at all. this is only happening on certain devices (pcs), and everything loads snappily on mobile with the same accounts. as far as I can tell the issue is not server related, is this a known matrix bug?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SmiteLover696969_2"> /u/SmiteLover696969_2 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ewak5m/matrix_server_lag_but_only_on_certain_devices/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ewak5m/matrix_server_lag_but_only_on_certain_devices/">[comments]</a></span>

## Plex alternative for self hosted photo slideshow on TV using Roku or Onn TV Box with photo duration settings
 - [https://www.reddit.com/r/selfhosted/comments/1ewaju1/plex_alternative_for_self_hosted_photo_slideshow](https://www.reddit.com/r/selfhosted/comments/1ewaju1/plex_alternative_for_self_hosted_photo_slideshow)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T19:21:48+00:00

<!-- SC_OFF --><div class="md"><p>I have thousands of photos on my PC. I have a Plex server and have been able to stream those photos as a slideshow on TVs in my house using Roku and Onn TV Box. The only lack of functionality I’m missing is to extend the duration each photo in the slideshow. I’ve searched and searched but cannot find an alternative. Any and all advice is greatly appreciated! Why is this so hard?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/umyninja"> /u/umyninja </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ewaju1/plex_alternative_for_self_hosted_photo_slideshow/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ewaju1/plex_alternative_for_self_hosted_photo_slideshow/">[comments]</a></span>

## Suggestion for video editing hosting
 - [https://www.reddit.com/r/selfhosted/comments/1ewaaat/suggestion_for_video_editing_hosting](https://www.reddit.com/r/selfhosted/comments/1ewaaat/suggestion_for_video_editing_hosting)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T19:11:22+00:00

<!-- SC_OFF --><div class="md"><p>I have my home-server(desktop tower) running truenas scale which has smb share. My main workflow is to host the video files in the nas so that my editor can access it. Now I am hiring a new editor to streamline my video output. My need is that I want to share the timelines with both of them. One can start working on trimming the videos and handoff to other editors to make post processing. After that he can handoff to me for final changes. Is there a video editing server that I can use?</p> <p>Thank you in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Independent_Bear_465"> /u/Independent_Bear_465 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ewaaat/suggestion_for_video_editing_hosting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ewaaat/suggestion_for_video_editing_hosting/">[comments]</a></span>

## My Server
 - [https://www.reddit.com/r/selfhosted/comments/1ewa8q0/my_server](https://www.reddit.com/r/selfhosted/comments/1ewa8q0/my_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T19:09:34+00:00

<!-- SC_OFF --><div class="md"><p>These are the self hosted apps I have installed to satisfy my need to be indepent from proprietary services:</p> <ol> <li>Nextcloud - Calendar, Contacts, Chat, Notes, onlyoffice document server, and photos.</li> <li>Vaultwarden - password manager</li> <li>Audiobookshelf- podcasts and audiobooks</li> <li>Navidrome - Music server</li> <li>Jellyfin - Media server</li> </ol> <p>That's all really use. What are yours?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/offlineyourlife24"> /u/offlineyourlife24 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ewa8q0/my_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ewa8q0/my_server/">[comments]</a></span>

## self made "app" for cameras
 - [https://www.reddit.com/r/selfhosted/comments/1ew9yka/self_made_app_for_cameras](https://www.reddit.com/r/selfhosted/comments/1ew9yka/self_made_app_for_cameras)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T18:58:28+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>Short question, would it be possible to write your own &quot;app&quot; in (python pref.) or any other way to connect to live stream of my security camera?</p> <p>Lets say i buy 10 random cameras from temu, and each of them require their own app witch is a pain, any way to connect to them directly without changing between 10 android apps?</p> <p>do share source if any.</p> <p>thank you in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/darkdummo19"> /u/darkdummo19 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew9yka/self_made_app_for_cameras/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew9yka/self_made_app_for_cameras/">[comments]</a></span>

## is Tigris pricing fair?
 - [https://www.reddit.com/r/selfhosted/comments/1ew9xio/is_tigris_pricing_fair](https://www.reddit.com/r/selfhosted/comments/1ew9xio/is_tigris_pricing_fair)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T18:57:18+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://www.tigrisdata.com/docs/pricing/">https://www.tigrisdata.com/docs/pricing/</a> </p> <p>i want to use it on <a href="http://fly.io">fly.io</a> because of the integration.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Spiritual_Sprite"> /u/Spiritual_Sprite </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew9xio/is_tigris_pricing_fair/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew9xio/is_tigris_pricing_fair/">[comments]</a></span>

## Log aggregation service?
 - [https://www.reddit.com/r/selfhosted/comments/1ew9niv/log_aggregation_service](https://www.reddit.com/r/selfhosted/comments/1ew9niv/log_aggregation_service)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T18:46:05+00:00

<!-- SC_OFF --><div class="md"><p>Looking for a service I can run that I can POST or MQTT logs into.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tehjrow"> /u/tehjrow </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew9niv/log_aggregation_service/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew9niv/log_aggregation_service/">[comments]</a></span>

## Service: KoalaBot, turn-key, GPL, self-hosted DiscordBot
 - [https://www.reddit.com/r/selfhosted/comments/1ew9e33/service_koalabot_turnkey_gpl_selfhosted_discordbot](https://www.reddit.com/r/selfhosted/comments/1ew9e33/service_koalabot_turnkey_gpl_selfhosted_discordbot)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T18:35:29+00:00

<!-- SC_OFF --><div class="md"><p>Do you want a simple, turn key Discord bot to tell the weather, post reddit links, integrate with chatGPT for questions, images, summaries, and other fun features for you and your friends' Discord server? Do you wanna host it yourself so you don't have to trust some random bot that could be do who knows what without having to learn to write your own?</p> <p>Well, I open sourced/expanded the bot we use on our server so others can give it a go too! It even comes as a Docker image, no programming experience necessary. All you need to do is give it the .env file with your API keys (for whatever features you want to use) and off you go, self hosted bot with AI integration and other fun features. Adding slash commands is easy too, but you will need programming experience to do that.</p> <p>Bot with documentation is here: <a href="https://github.com/AssKoala/koalabot">https://github.com/AssKoala/koalabot</a></p> <p>Docker here: <a href="https://hub.docker.co

## Can I use 2 mail servers with one domain
 - [https://www.reddit.com/r/selfhosted/comments/1ew9ays/can_i_use_2_mail_servers_with_one_domain](https://www.reddit.com/r/selfhosted/comments/1ew9ays/can_i_use_2_mail_servers_with_one_domain)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T18:32:04+00:00

<!-- SC_OFF --><div class="md"><p>I have a domain e.g <a href="https://mydomain.com">mydomain.com</a> and I use proton mail to host my email, however for my self hosted applications, if I need to send notification emails I'm not able to send them because proton mail doesnt support smtp credentials. Is it possible to run mailcow on my server to send emails from my<a href="https://domain.com">domain.com</a> and also allow ProtonMail to work?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/borkode"> /u/borkode </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew9ays/can_i_use_2_mail_servers_with_one_domain/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew9ays/can_i_use_2_mail_servers_with_one_domain/">[comments]</a></span>

## Can’t access Overseerr
 - [https://www.reddit.com/r/selfhosted/comments/1ew8mby/cant_access_overseerr](https://www.reddit.com/r/selfhosted/comments/1ew8mby/cant_access_overseerr)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T18:04:35+00:00

<!-- SC_OFF --><div class="md"><p>I can’t seem to figure what’s happened to my setup and while I’m technically inclined this is a bit out of my scope. I have docker desktop running overseerr and nginx proxy manager. I have duckdns setup with my subdomain to access overseerr through my external ip. Yesterday everything worked fine even through multiple system restarts. Today I cannot access it from the duckdns link or directly from the external ip and port. I tried changing my port forwarding settings, restarting the docker containers and force updating duckdns to no avail. Npm shows both my domains as online and I can access overseerr from my internal or local host address. What could have changed? Can anyone point me in a direction to troubleshoot? Docker is my weakest ability and all I can say for sure is that I get a 502 bad gateway message when using my duckdns address. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DaisyAge12"> /u/DaisyAge

## How the hell do i intsall Komga on Windows
 - [https://www.reddit.com/r/selfhosted/comments/1ew83dq/how_the_hell_do_i_intsall_komga_on_windows](https://www.reddit.com/r/selfhosted/comments/1ew83dq/how_the_hell_do_i_intsall_komga_on_windows)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T17:43:29+00:00

<!-- SC_OFF --><div class="md"><p>I have been trying for 2 days and nothing works, it's confusing AF and I don't know what half of the words in their page are or mean</p> <p>Someone please give me a detailed tutorial or something PLEASE</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/No_Meet4295"> /u/No_Meet4295 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew83dq/how_the_hell_do_i_intsall_komga_on_windows/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew83dq/how_the_hell_do_i_intsall_komga_on_windows/">[comments]</a></span>

## New Email Server - Gmail Spam
 - [https://www.reddit.com/r/selfhosted/comments/1ew82xt/new_email_server_gmail_spam](https://www.reddit.com/r/selfhosted/comments/1ew82xt/new_email_server_gmail_spam)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T17:43:00+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ew82xt/new_email_server_gmail_spam/"> <img alt="New Email Server - Gmail Spam" src="https://b.thumbs.redditmedia.com/x61Ouu0DpUIrlLxUbNj1SY7bEcmrQKjHW_gDGnBpaKM.jpg" title="New Email Server - Gmail Spam" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I spun up a new email server and it looks like my DNS records are set up properly but gmail keeps marking my emails as spam. Any ideas of how you would diagnose this issue?</p> <p><a href="https://preview.redd.it/a6sq7bprqnjd1.png?width=1588&amp;format=png&amp;auto=webp&amp;s=fed945010ac5e563abca755ed32904cbc6ba3bd8">https://preview.redd.it/a6sq7bprqnjd1.png?width=1588&amp;format=png&amp;auto=webp&amp;s=fed945010ac5e563abca755ed32904cbc6ba3bd8</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dlev47"> /u/Dlev47 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew82xt/new_email_server_gmail_spam/">[li

## Remotely agent HIDE interactions
 - [https://www.reddit.com/r/selfhosted/comments/1ew7uia/remotely_agent_hide_interactions](https://www.reddit.com/r/selfhosted/comments/1ew7uia/remotely_agent_hide_interactions)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T17:33:16+00:00

<!-- SC_OFF --><div class="md"><p>Hi, do you know how I can hide interactions during a remote connection with a user in <a href="https://github.com/immense/Remotely">https://github.com/immense/Remotely</a> (Remotely). The thing is that after connecting the desktop remotely, the Assistance window appears with the active session. How can I hide it? The process that opens this window is Remotely_Desktop.exe . I tried to hide the entire GUI window using python. Unfortunately, without success even with administrator privileges. how can I hide all windows in the Remotely_Desktop.exe process. System: Windows 10/Windows 11</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Substantial-Kale8905"> /u/Substantial-Kale8905 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew7uia/remotely_agent_hide_interactions/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew7uia/remotely_agent_hide_interactions/">

## Self hosted app for trading journal?
 - [https://www.reddit.com/r/selfhosted/comments/1ew7lgt/self_hosted_app_for_trading_journal](https://www.reddit.com/r/selfhosted/comments/1ew7lgt/self_hosted_app_for_trading_journal)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T17:23:25+00:00

<!-- SC_OFF --><div class="md"><p>Is there any open source app where I can input my trade history and the calendar can show my trading performance or any other data analytic?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/neaja"> /u/neaja </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew7lgt/self_hosted_app_for_trading_journal/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew7lgt/self_hosted_app_for_trading_journal/">[comments]</a></span>

## Let's Encrypt + DNS challenge - alternative to Namecheap's DNS?
 - [https://www.reddit.com/r/selfhosted/comments/1ew7ckq/lets_encrypt_dns_challenge_alternative_to](https://www.reddit.com/r/selfhosted/comments/1ew7ckq/lets_encrypt_dns_challenge_alternative_to)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T17:13:20+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I currently have my domains through Namecheap. They offer DNS and that has worked fine for my use cases for years</p> <p>Now, I want to deploy SSL certs for my local network. I would like to do it via DNS challenge and an API so I don't have to open anything for it. </p> <p>Now, the problem is that it looks like Namecheap's API has limitations (and requirements, but assuming I can get these). </p> <p>Now, my question to everyone is, what dns provider do you use? I will not be transferring the domain, but I'd be happy to change nameservers and handle DNS at the new provider.</p> <p>Looks like CloudFlare is an option, but I'd personally like to keep it out of it. If that is the best solution, I will do it though. </p> <p>Any recommendations?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mrcaptncrunch"> /u/mrcaptncrunch </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e

## .arr stack
 - [https://www.reddit.com/r/selfhosted/comments/1ew77e1/arr_stack](https://www.reddit.com/r/selfhosted/comments/1ew77e1/arr_stack)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T17:07:23+00:00

<!-- SC_OFF --><div class="md"><p>I`ve seen a lot of people posting they`re .arr stack and i want to share mine, <a href="https://github.com/PedroBuffon/mediarr">LINK</a>, i have a install script too that checks and install docker if needed, pulls the repo, modify permissions if needed, change the .env accordingly to user definition and set Host:container volumes.</p> <p>Any improvements suggestions just put them in the comments.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pedrobuffon"> /u/pedrobuffon </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew77e1/arr_stack/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew77e1/arr_stack/">[comments]</a></span>

## Tailscale On unRAID - How To Access Docker Apps Directly?
 - [https://www.reddit.com/r/selfhosted/comments/1ew6so8/tailscale_on_unraid_how_to_access_docker_apps](https://www.reddit.com/r/selfhosted/comments/1ew6so8/tailscale_on_unraid_how_to_access_docker_apps)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T16:51:18+00:00

<!-- SC_OFF --><div class="md"><p>I have Tailscale setup. I can access my unRAID gui remotely. But what if I want to access JUST Obsidian without using the unRAID gui to get there? How do I set this up?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/no_more_secrets"> /u/no_more_secrets </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew6so8/tailscale_on_unraid_how_to_access_docker_apps/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew6so8/tailscale_on_unraid_how_to_access_docker_apps/">[comments]</a></span>

## Something like gitlab, but better?
 - [https://www.reddit.com/r/selfhosted/comments/1ew6qro/something_like_gitlab_but_better](https://www.reddit.com/r/selfhosted/comments/1ew6qro/something_like_gitlab_but_better)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T16:49:15+00:00

<!-- SC_OFF --><div class="md"><p>The selfhosted version is way too overengineered for me. It fills the disk, crashes repeatedly, uses way too much memory, and it annoyed me that you can't turn off password complexity - the IP address is only available on a private IP over a VPN, let me turn it off. </p> <p>It's the only docker image (well, multiple) I have problems with. </p> <p>All of these problems, and I'm not even using it - no repos yet, it's on my todo list.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/williambobbins"> /u/williambobbins </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew6qro/something_like_gitlab_but_better/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew6qro/something_like_gitlab_but_better/">[comments]</a></span>

## Discord channel(s) for self-hosting enthusiasts??
 - [https://www.reddit.com/r/selfhosted/comments/1ew6jk3/discord_channels_for_selfhosting_enthusiasts](https://www.reddit.com/r/selfhosted/comments/1ew6jk3/discord_channels_for_selfhosting_enthusiasts)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T16:41:11+00:00

<!-- SC_OFF --><div class="md"><p>Hello guys, I was wondering if there was anydiscord channel where a person can join and create awareness around their self-hosting solution, and/or know about other’s solutions.</p> <p>Please leave the links for joining, if there are any.</p> <p>Thanks a lot! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Litlyx"> /u/Litlyx </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew6jk3/discord_channels_for_selfhosting_enthusiasts/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew6jk3/discord_channels_for_selfhosting_enthusiasts/">[comments]</a></span>

## Questions about hosting Seafile, Immich, Paperless-ngx and Nginx/Traefik
 - [https://www.reddit.com/r/selfhosted/comments/1ew6iq1/questions_about_hosting_seafile_immich](https://www.reddit.com/r/selfhosted/comments/1ew6iq1/questions_about_hosting_seafile_immich)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T16:40:15+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I’m a selfhosting noob at the moment and i’m trying to make the best of it. I have an spare nuc that is hosting Proxmox and i have an external hdd attached to it where i want all my NAS data to be stored on it. I know this is not best practice and not ideal. But the nuc only stores 1 nvme ssd and 1 SATA (while i’m writing this i remember that the sata port is still available so maybe the extern hdd will be the backup location) and so i cant use raid 1 for example.</p> <p>Anyway. I have setup the following in a LXC container in Proxmox and its working*</p> <p>- Firefly III</p> <p>- Bookstack</p> <p>- Adguard</p> <p>*working as Firefly III was a hell to configure because everything went wrong &gt;&lt;</p> <p>Also i have a 2 VM's running:</p> <p>- HomeAssistentOS</p> <p>- Seafile</p> <p> </p> <p>And ofcourse the wishlist:</p> <p>- Tandoori Recipt</p> <p>- Pihole (instead of Adguard)</p> <p>- Syncthing (i have read alot about it and i understan

## Issues with Authentik and Immich
 - [https://www.reddit.com/r/selfhosted/comments/1ew63bv/issues_with_authentik_and_immich](https://www.reddit.com/r/selfhosted/comments/1ew63bv/issues_with_authentik_and_immich)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T16:23:07+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ew63bv/issues_with_authentik_and_immich/"> <img alt="Issues with Authentik and Immich" src="https://external-preview.redd.it/q5A9zVI8_D78q8aKZAi3GLy1BGFnawuUORSzBLisls0.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=a64fd74da5707ca731f27c7a69f7d20fe8938923" title="Issues with Authentik and Immich" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I followed this guide to install authentik (<a href="https://docs.goauthentik.io/docs/installation/docker-compose">https://docs.goauthentik.io/docs/installation/docker-compose</a>) and followed this (<a href="https://docs.goauthentik.io/integrations/services/immich/">https://docs.goauthentik.io/integrations/services/immich/</a>) to make authentik my SSO for immich. However I am stuck as I am not able to get a OpenID Configuration Issuer as it just shows a dash in the field. I'm not sure why it's doing that as the second guide says I should have one over there. I've li

## Need help starting
 - [https://www.reddit.com/r/selfhosted/comments/1ew5v4m/need_help_starting](https://www.reddit.com/r/selfhosted/comments/1ew5v4m/need_help_starting)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T16:14:06+00:00

<!-- SC_OFF --><div class="md"><p>Sorry for spelling errors, english is not my first language</p> <p>So, I am trying to build a single server (just a pc, that I say will be my home server). I know something. Currently I'm studying IT, but more of the programming side of things, I know a bit of networking too, but not much. I daily drive arch linux btw (sorry I had to [first time saying it fr]) so I am familiar with cli's and how the non gui part of computing works.</p> <p>First I would like to get some advice for my hardware:</p> <ul> <li><a href="https://www.gigabyte.com/Motherboard/B550M-DS3H-AC-rev-14#kf">B550M DS3H AC motherboard</a></li> <li>ryzen 5 5600G/3 1200 (I don't know if I will be upgrading my current pc processor, so I will use the one I have)</li> <li>8 TB hdd</li> <li>256 GB M.2 ssd</li> <li>32+ GB of RAM <ul> <li>I need advice here. Should I buy more? (again, using old ram and morherboard since I am replacing it with something that has AM5 socket and slots for DDR5 RA

## Jellyfin - subtitles delay
 - [https://www.reddit.com/r/selfhosted/comments/1ew5qpm/jellyfin_subtitles_delay](https://www.reddit.com/r/selfhosted/comments/1ew5qpm/jellyfin_subtitles_delay)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T16:09:19+00:00

<!-- SC_OFF --><div class="md"><p>Jellyfin works flawlessly overall, but somehow EVERY movie or series I play, either with subtitles already added, or subtitles I add via Jellyfin OpenSubtitles plugin, they are either delayed or hasted. Any reason? It's quite intimidating to be finding right subtitle delay for every movie I play, sometimes it's 2 seconds, sometimes 20, and sometimes changes through whole movie. Playing same exact movie file in VLC on PC or any other machine, doesn't seem to be a problem, so I guess it's Jellyfin that &quot;screws&quot; with subtitles. </p> <p>Any ideas? Thanks for help.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Longjumping-Wait-989"> /u/Longjumping-Wait-989 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew5qpm/jellyfin_subtitles_delay/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew5qpm/jellyfin_subtitles_delay/">[comments]</a></span>

## Is let's encrypt a self-hosted alternative to Digicert?
 - [https://www.reddit.com/r/selfhosted/comments/1ew57e5/is_lets_encrypt_a_selfhosted_alternative_to](https://www.reddit.com/r/selfhosted/comments/1ew57e5/is_lets_encrypt_a_selfhosted_alternative_to)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T15:48:12+00:00

<!-- SC_OFF --><div class="md"><p>Are there any downsides to using one vs the other?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/notdoreen"> /u/notdoreen </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew57e5/is_lets_encrypt_a_selfhosted_alternative_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew57e5/is_lets_encrypt_a_selfhosted_alternative_to/">[comments]</a></span>

## [Launch] Exciting Update: Simplified Data Interaction in WhoDB!
 - [https://www.reddit.com/r/selfhosted/comments/1ew4xr9/launch_exciting_update_simplified_data](https://www.reddit.com/r/selfhosted/comments/1ew4xr9/launch_exciting_update_simplified_data)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T15:37:43+00:00

<!-- SC_OFF --><div class="md"><p>Hey <a href="/r/selfhosted">r/selfhosted</a>,</p> <p>Following up on our previous post where we introduced <a href="https://www.reddit.com/r/selfhosted/comments/1do9t6y/launch_introducing_whodb_the_nextgeneration/">WhoDB</a>, we're excited to announce a significant new feature we've been working on—chat-based data interaction.</p> <h1>What’s New?</h1> <p>We've integrated a feature that allows for natural language querying and management of your datas. This update is designed to make it easier for non-technical users to interact with complex datasets and for advanced users to perform quick queries without writing SQL.</p> <h1>Why This Matters</h1> <p>We’ve received incredible feedback from this community, which has driven us to keep improving WhoDB. Our goal with this new functionality is to lower the barrier to effective data management, making it accessible to everyone while maintaining the robust control that power users need.</p> <h1>Why We Chose L

## Plex is ..... a collection creator !
 - [https://www.reddit.com/r/selfhosted/comments/1ew4keq/plex_is_a_collection_creator](https://www.reddit.com/r/selfhosted/comments/1ew4keq/plex_is_a_collection_creator)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T15:23:13+00:00

<!-- SC_OFF --><div class="md"><p>Hey !</p> <p>I wanted to share a project I've been working on for the past month. As a novice developer, I decided to challenge myself and create something that could enhance our Plex experience. The result is Plexis, a tool that automates the creation of themed movie collections and provides intelligent movie recommendations.</p> <p>The Genesis: It all started when I realized how time-consuming it was to manually create themed collections in Plex. I thought, &quot;Wouldn't it be cool if there was a tool that could do this automatically?&quot; That's when I decided to dive in and create one myself, despite my limited coding experience.</p> <p>What I Learned: Over the course of a month, I immersed myself in various technologies:</p> <ul> <li>Docker for containerization</li> <li>Flask for the backend</li> <li>JavaScript for the frontend</li> <li>Integration with Plex and Radarr APIs</li> <li>Working with AI for movie recommendations (using Groq)</li> </

## Reconya-AI - Network presence and reconnaissance scanner web application
 - [https://www.reddit.com/r/selfhosted/comments/1ew4h92/reconyaai_network_presence_and_reconnaissance](https://www.reddit.com/r/selfhosted/comments/1ew4h92/reconyaai_network_presence_and_reconnaissance)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T15:19:44+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ew4h92/reconyaai_network_presence_and_reconnaissance/"> <img alt="Reconya-AI - Network presence and reconnaissance scanner web application " src="https://b.thumbs.redditmedia.com/CReZLJ_7MMy52Jhq9rMEkL076okCoufMXUGW2VqwYbQ.jpg" title="Reconya-AI - Network presence and reconnaissance scanner web application " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/omf3q5e9ymjd1.png?width=1840&amp;format=png&amp;auto=webp&amp;s=76b40106a229003e2f8ef21c9846ca719846abe2">main dashboard</a></p> <p><a href="https://preview.redd.it/lmxma0el1njd1.png?width=819&amp;format=png&amp;auto=webp&amp;s=652fc92b7c4f8623d2c5df48d2d5f0063273e9ee">device info</a></p> <p>Hey all!</p> <p>Some time ago, I had this idea: I wanted to create a well performing network scanner that I could easily install on a portable device (e.g. a Raspberry Pi) and plug it on any network. The system would automatically detect t

## Looking for a simple, dockerised, static file server with HTTP Basic authentication
 - [https://www.reddit.com/r/selfhosted/comments/1ew4fyr/looking_for_a_simple_dockerised_static_file](https://www.reddit.com/r/selfhosted/comments/1ew4fyr/looking_for_a_simple_dockerised_static_file)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T15:18:14+00:00

<!-- SC_OFF --><div class="md"><p>Hi. Im trying to find a selfhosted server suitable for serving files for MDM to use. It should have static links to files, HTTP basic authentication but other than that be fairly secure. Any ideas? I have found some nice candidates but they dont offer HTTP authentication</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dinth"> /u/Dinth </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew4fyr/looking_for_a_simple_dockerised_static_file/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew4fyr/looking_for_a_simple_dockerised_static_file/">[comments]</a></span>

## Announcing local development support for Appwrite's Functions
 - [https://www.reddit.com/r/selfhosted/comments/1ew4cow/announcing_local_development_support_for](https://www.reddit.com/r/selfhosted/comments/1ew4cow/announcing_local_development_support_for)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T15:14:29+00:00

<!-- SC_OFF --><div class="md"><p>Hey Redditors, this is Eldad from the Appwrite team. This is the first day of <a href="https://appwrite.io/init">Appwrite Init</a> and we're excited to announce new support for local development of <a href="https://appwrite.io/docs/products/functions">Appwrite Functions</a>. </p> <p>Appwrite Functions are Appwrite serverless compute service just like AWS lambda that allow you run your code in the cloud (or self host it) and extend your Appwrite backend functionality. </p> <p>With the new addition of local development, you can now run Appwrite functions right on your machine, making your workflow faster and more cost-effective, including coding, testing, and debugging.</p> <p>It’s very common to have two separate Appwrite projects: one for your production application and one for the staging environment. In your staging, you can safely apply your deployment changes to ensure stability after your latest changes.</p> <p>Whether you work alone or in a team

## NextCloud Question
 - [https://www.reddit.com/r/selfhosted/comments/1ew4c0a/nextcloud_question](https://www.reddit.com/r/selfhosted/comments/1ew4c0a/nextcloud_question)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T15:13:42+00:00

<!-- SC_OFF --><div class="md"><p>Simple question; how do I or can I even install NC without Port Forward using Docker.</p> <p>Tried AIO with Reverse Proxy and kept saying I needed access to port 443.</p> <p>Tried without the Proxy and even with Skip Domain Validation but then no luck and it’s in a constant restart.</p> <p>My setup is Proxmox, with OpnSense, and I have Caddy installed. </p> <p>Right now I’m testing the Linux Server variant but can’t seem to change the SqlLite db.</p> <p>Also I’ve noted that the pics look kinda washed out unprocessed on NC, vs iPhone.</p> <p>Any guidance would be appreciated. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Thick-Maintenance274"> /u/Thick-Maintenance274 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew4c0a/nextcloud_question/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew4c0a/nextcloud_question/">[comments]</a></span>

## Traefik - Trigger Configuration Reload
 - [https://www.reddit.com/r/selfhosted/comments/1ew40qm/traefik_trigger_configuration_reload](https://www.reddit.com/r/selfhosted/comments/1ew40qm/traefik_trigger_configuration_reload)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T15:01:15+00:00

<!-- SC_OFF --><div class="md"><p>I'm currently hosting my Traefik configuration in docker on an NFS bind mount, which apparently doesn't support detecting configuration changes via fsnotify that Traefik uses. I'd like to be able to add a button to my Homepage that would trigger Traefik to reload it's configuration. Unfortunately, I think the only way to do this is to either restart the Traefik container, or use docker exec to send a SIGHUP to the container.</p> <p>Does anyone have any ideas on how either of these could be accomplished?</p> <p>Edit: I'm thinking maybe Portainer API might be a good way to do this, and then using Homepage Custom API widget.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fragglesnot"> /u/Fragglesnot </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew40qm/traefik_trigger_configuration_reload/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew40qm/traefik_

## Cloudpanel Apache issue
 - [https://www.reddit.com/r/selfhosted/comments/1ew3ry0/cloudpanel_apache_issue](https://www.reddit.com/r/selfhosted/comments/1ew3ry0/cloudpanel_apache_issue)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T14:51:08+00:00

<!-- SC_OFF --><div class="md"><p>I moved away from a previous hosting, and I am now running Cloudpanel on a Hetzner server and all is groovy. Only problem I have at the moment is I use <a href="http://Sendy.co">Sendy.co</a> and I'm moving it over to the new server. Previously it was using Apache and it was fine. Cloudpanel uses Nginx and it freaks out on here.</p> <p>A couple of questions I have is:</p> <ul> <li>I have tried to tweak the settings so it would work with Nginx but it's not working, has anyone managed to get this or something similar working?</li> <li>I messaged the creator of Sendy and just got a simple &quot;use Apache&quot; :/ So does that mean Nginx is a definite no no?</li> <li>I don't think I can add Apache to Cloudpanel so is there a way I can install Apache on my server separately and install it like that?</li> <li>Tied myself in knots trying to sort this out and lost a weekend. </li> </ul> <p>Anyone have any advice, please do share. Thank you</p> </div><!-- SC_O

## Why did I not use a wiki application from the beginning
 - [https://www.reddit.com/r/selfhosted/comments/1ew3n1e/why_did_i_not_use_a_wiki_application_from_the](https://www.reddit.com/r/selfhosted/comments/1ew3n1e/why_did_i_not_use_a_wiki_application_from_the)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T14:45:21+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ew3n1e/why_did_i_not_use_a_wiki_application_from_the/"> <img alt="Why did I not use a wiki application from the beginning " src="https://a.thumbs.redditmedia.com/_fgcGjWo0LgiDQfas-XKTpVrAOOUjk-H0BTvUlP-5M4.jpg" title="Why did I not use a wiki application from the beginning " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I began my self hosting journey 1 year ago. Fast forward to now...1 ms-01 with proxmox contains 22 Ixc and 5 VMs. One rs1221 with 2x8tb and 2x18 tb. Almost 80 running containers. Nights of testing stuff out, installing, troubleshootings, having fun. WHY did I just now decided to install a wiki container, bookstack. I will never remember all I did haha.</p> <p>So now my new project is to write wikis.</p> <p>Wish me luck 🍀 </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Parking-Cow4107"> /u/Parking-Cow4107 </a> <br /> <span><a href="https://www.reddit.com

## Gauging the interest of a Jellyfin eReader (and possibly audiobook) client
 - [https://www.reddit.com/r/selfhosted/comments/1ew30fn/gauging_the_interest_of_a_jellyfin_ereader_and](https://www.reddit.com/r/selfhosted/comments/1ew30fn/gauging_the_interest_of_a_jellyfin_ereader_and)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T14:19:41+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I have noticed lately the lack of a good Jellyfin eReader client. I find the integration in the official Jellyfin app unusable for my standards, (no offense to the devs) and have not found a good iOS client that supports ebooks yet. Hence, I have decided to look into making one. I don’t have experience making apps, so it will definitely be a learning curve, but as it is something myself and my wife would use almost every day, I think it would be worth the time put in.</p> <p>That being said, is this something you would be interested in? Furthermore, if you have any guidance of where to start, I would love some tips or tricks if you have any to offer. I have looked into builder.io since I have less coding experience, and also into Expo. If you have any other jumping-off-point recommendations I would most definitely be interested.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CalebWest02"> /u/CalebWest02 

## WebRadio with Controls?
 - [https://www.reddit.com/r/selfhosted/comments/1ew2ogg/webradio_with_controls](https://www.reddit.com/r/selfhosted/comments/1ew2ogg/webradio_with_controls)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T14:05:25+00:00

<!-- SC_OFF --><div class="md"><p>Looking to self-host a web-radio, live broadcasting, and at certain times join in and talk, overlaying what's played, changing the playlist etc.</p> <p>Something like OBS-Studio, for radios.</p> <p>Btw how does music work? Can you play whatever with no commerical use? I'm in Italy is not like Snoop Dogg or M'n'm's would come get me??</p> <p>Regards.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Aliwnityy"> /u/Aliwnityy </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew2ogg/webradio_with_controls/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew2ogg/webradio_with_controls/">[comments]</a></span>

## Need a no B.S. assessment on hardware vs usage
 - [https://www.reddit.com/r/selfhosted/comments/1ew1zb4/need_a_no_bs_assessment_on_hardware_vs_usage](https://www.reddit.com/r/selfhosted/comments/1ew1zb4/need_a_no_bs_assessment_on_hardware_vs_usage)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T13:36:11+00:00

<!-- SC_OFF --><div class="md"><p>I have a server with contabo, it is absolutely insufferable. Even SSH is slow. We're not talking a 500ms delay, we're talking 3-4 second delay.</p> <p>8 cores, 24gb memory, 6GB swap space, Ubuntu 22.04.1</p> <p>I have the following installs (all docker containers). I'll do a little grouping here to keep the list shorter.</p> <ul> <li>Docker + Traefik + Portainer</li> <li>Authentik</li> <li>PHP, MariaDB, Phpmyadmin, Nginx</li> <li>Gitea, PostgreSQL, Elastic Search (1GB assigned), Redis</li> <li>Dockge (self-hosted docker compose.yaml stack-oriented manager)</li> <li>Dozzle</li> <li>Syncthing</li> <li>NextCloud</li> <li>Linkwarden</li> <li>Opengist</li> <li>Vaultwarden</li> </ul> <p>&#x200b;</p> <p>Does this sound like a ridiculous amount of containers to be running on the hardware I have? I didn't think the list above is terribly bad. Not to the point where I should be suffering the performance degradation I'm experiencing.</p> <p>When I check memory u

## Home webhosting?
 - [https://www.reddit.com/r/selfhosted/comments/1ew1uo0/home_webhosting](https://www.reddit.com/r/selfhosted/comments/1ew1uo0/home_webhosting)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T13:30:32+00:00

<!-- SC_OFF --><div class="md"><p>My SSL cert expires soon along side with my hosting provider. The cost for this year is roughly 800$ between hosting and certs.</p> <p>I pay for a designated IP already. I’m now considering purchasing a server, installing proxmox, moving my hosting on prem in my home and using something like pfsense or firewalla with kemp for load balancing. </p> <p>Since I have to spend 800$ regardless. Does anyone have suggestions and advice on the best way to lay this out? </p> <p>Router -&gt; Firewall -&gt; Load Balancer -&gt; proxmox. </p> <p>I planned to setup cloudflare to redirect to my ip and only open a single port. I know I can create free wild card certs using cloudflare and letsencrypt which I plan to do.</p> <p>Why is this a bad route? What can I improve? What servers do you all suggest to host 90+ domains? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/wrmps"> /u/wrmps </a> <br /> <span><a href="https://www.reddi

## Confused if authentik is the right fit for me
 - [https://www.reddit.com/r/selfhosted/comments/1ew174x/confused_if_authentik_is_the_right_fit_for_me](https://www.reddit.com/r/selfhosted/comments/1ew174x/confused_if_authentik_is_the_right_fit_for_me)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T13:01:39+00:00

<!-- SC_OFF --><div class="md"><p>I have taken an interest to trying out Authentik, however I had a few questions. I want to protect my jellyfin, nextcloud and immich instances to name a few. If I protect them using Authentik, does that mean that I bypass the login screen that already exists on my services or do I need reenter the credentials? Because if it doesn't bypass those login screens then it wouldn't be a right fit for me as I'd like it to work similarly to how Okta does where I login via Okta once it logs me into everything that uses it.</p> <p>If someone could help clarify I'd really appreciate it :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/borkode"> /u/borkode </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew174x/confused_if_authentik_is_the_right_fit_for_me/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew174x/confused_if_authentik_is_the_right_fit_for_me/">[comm

## Best Pandora Alternative
 - [https://www.reddit.com/r/selfhosted/comments/1ew16do/best_pandora_alternative](https://www.reddit.com/r/selfhosted/comments/1ew16do/best_pandora_alternative)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T13:00:50+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a great Pandora alternative. I currently run Jellyfin for my video streaming and know that it does a decent job for music libraries as well, however, the biggest feature that I need to replicate is Pandora's radio function. My wife couldn't get on-board with Spotify until they l launched their stations feature/app... then torpedoed it almost instantly. I know that Jellyfin can be a great Spotify replacement for myself, but my wife won't ditch Pandora until there's something with a comparable radio feature where she can effortlessly build a quality station based on a song, artists or genre.</p> <p>I've done a bit of reading and have seen that Funkwhale has a &quot;radio&quot; feature, but I can't find much info on how good it does and their site makes it sound more like a simple playlist feature that will only auto-build based on &quot;favorites&quot;, &quot;Random&quot;, &quot;Recently Added&quot; and &quot;Less listened&quot;, but no

## nginx manage via GUI
 - [https://www.reddit.com/r/selfhosted/comments/1ew0ra3/nginx_manage_via_gui](https://www.reddit.com/r/selfhosted/comments/1ew0ra3/nginx_manage_via_gui)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T12:41:46+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>Looking for some nice web GUI to manage nginx configuration (and letsencrypt certs at the same time).</p> <p>I've found nginx proxy manager which looks very promising for me, but I also serve a few &quot;static&quot; websites on the same host, and as far as I know, it's not possible to configure this.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/_Fisz_"> /u/_Fisz_ </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew0ra3/nginx_manage_via_gui/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ew0ra3/nginx_manage_via_gui/">[comments]</a></span>

## Introducing MQTT Web Interface: A Lightweight, Open-Source Tool for Real-Time MQTT Visualization
 - [https://www.reddit.com/r/selfhosted/comments/1ew0m8y/introducing_mqtt_web_interface_a_lightweight](https://www.reddit.com/r/selfhosted/comments/1ew0m8y/introducing_mqtt_web_interface_a_lightweight)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T12:35:03+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I'm excited to share a project I've been working on: MQTT Web Interface, a lightweight, open-source tool for real-time MQTT message flow visualization.</p> <p><strong>Key features:</strong></p> <p>• Web-based for easy access</p> <p>• Real-time topic hierarchy visualization</p> <p>• Interactive network graph</p> <p>• Publish messages directly from the UI</p> <p>• One-command Docker deployment</p> <p><strong>What makes it different:</strong></p> <p>While there are feature-rich alternatives out there, MQTT Web Interface aims to be your go-to tool for rapid MQTT debugging and monitoring. It's perfect when you need immediate insights without installing desktop apps or setting up complex systems.</p> <p><strong>Getting started is as simple as:</strong></p> <p><code>docker pull terdia07/mqttui:v1.0.0</code></p> <p><code>docker run -p 5000:5000 terdia07/mqttui:v1.0.0</code></p> <p>GitHub repo: <a href="https://github.com/terdia/mqttui">ht

## Making Unraid Server with Docker & Plex Publicly Accessible (Dual Stack, No Static IPv4, 2.5 Gbit/s Home Network)
 - [https://www.reddit.com/r/selfhosted/comments/1evzjfh/making_unraid_server_with_docker_plex_publicly](https://www.reddit.com/r/selfhosted/comments/1evzjfh/making_unraid_server_with_docker_plex_publicly)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T11:39:32+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I need some help with configuring my Unraid server. Here’s the situation:</p> <p><strong>Setup:</strong></p> <ul> <li>My server is running Unraid, and I have several Docker containers that I want to make publicly accessible for my family members.</li> <li>Additionally, I have Plex running on the server, which I want to make available outside my home network. However, within the home network, Plex should still work via a direct connection.</li> <li>I have a Dual Stack internet connection (as far as I know, it's not DS-Lite) without a static IPv4 address.</li> <li>My home network is fully equipped with 2.5 Gbit/s components.</li> <li>My internet connection provides 1 Gbit/s upload and 500 Mbit/s download speeds.</li> <li>I’m using a Fritzbox 5590 router that supports WireGuard.</li> </ul> <p><strong>Available Resources:</strong></p> <ul> <li>I have a domain through Squarespace.</li> <li>I'm willing to get a VPS if necessary.</li> <li

## Advice for recipe management, shopping, and (home) stock control?
 - [https://www.reddit.com/r/selfhosted/comments/1evzj4l/advice_for_recipe_management_shopping_and_home](https://www.reddit.com/r/selfhosted/comments/1evzj4l/advice_for_recipe_management_shopping_and_home)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T11:39:05+00:00

<!-- SC_OFF --><div class="md"><p>For the last year or so I've been happily using Mealie, and a shopping list app on my phone; these are two entirely separate and unconnected apps. But I've just become aware of such apps as Grocy, which seems to be a stock manager (&quot;How many jars of pickled artichoke hearts do I have&quot;) as well as a shopping list, and a recipe management tool, all integrated. The trouble of course is that it's a very slow task entering all your cupboard items, from asafoetida to Zinfandel, and managing the various units: those that you buy in, and those that you cook with. (I buy rice in kilograms, but use it in metric cups.) So it will be a considerable effort getting it all up and running. Also, as far as I know, Grocy does not as yet have a recipe web-scraper; you have to enter all recipes manually.</p> <p>So before I go ahead, I just wonder if people have found that Grocy really is as good as it seems to be, or whether I'd be better off putting my efforts

## Docker-based site proxy with an administrative panel
 - [https://www.reddit.com/r/selfhosted/comments/1evzgyl/dockerbased_site_proxy_with_an_administrative](https://www.reddit.com/r/selfhosted/comments/1evzgyl/dockerbased_site_proxy_with_an_administrative)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T11:35:36+00:00

<!-- SC_OFF --><div class="md"><p>I'm looking for a docker-based proxy server, one with an administration panel permitting easy set up and configuration of hosts.</p> <p>Some additional requirements:</p> <ul> <li>LetsEncrypt support</li> <li>LDAP/AD support for authenticating to the admin panel</li> <li>(optional) support for NTLM authentication for proxied hosts</li> </ul> <p>I know <code>ngnix</code>, as a proxy, has NTLM support only in its paid version. I saw some open projects for creating a custom NTLM module for it, but to be honest I never managed to get it working. In the end it's &quot;nice to have&quot; but not a strict requirement.</p> <p>Generally, had I not needed LDAP/AD support, I'd go for <code>nginx-proxy-manager</code>, but it doesn't support LDAP/AD for the admin panel access.</p> <p>Is there anything else that I could use perhaps?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Shaamaan"> /u/Shaamaan </a> <br /> <span><a href

## Syncing Obsidian on Android
 - [https://www.reddit.com/r/selfhosted/comments/1evzbh5/syncing_obsidian_on_android](https://www.reddit.com/r/selfhosted/comments/1evzbh5/syncing_obsidian_on_android)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T11:26:42+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I have a Mac Mini server at home, and I’m desperately trying to sync my Obsidian vaults (2) across all my devices (Mac laptop, Windows, and Android). I’ve been using Nextcloud, but it suddenly stopped working on my mobile phone (it doesn’t &quot;always keep on this device&quot;), so it’s no longer functional. Trying to force the download/sync results in &quot;unexpected errors.&quot;</p> <p>Do you have any suggestions for managing this? I used to use Syncthing, but it didn’t work perfectly either.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Infralpes"> /u/Infralpes </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1evzbh5/syncing_obsidian_on_android/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1evzbh5/syncing_obsidian_on_android/">[comments]</a></span>

## Open Source DBaaS
 - [https://www.reddit.com/r/selfhosted/comments/1evz3e4/open_source_dbaas](https://www.reddit.com/r/selfhosted/comments/1evz3e4/open_source_dbaas)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T11:13:19+00:00

<!-- SC_OFF --><div class="md"><p>Is there an open-source app that I can self-host that lets me quickly create a database in a web UI and has an API? Integrated backups would also be nice. I'm looking for something like NeonDB or PlanetScale, just self-hosted.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Awkward-Plate7826"> /u/Awkward-Plate7826 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1evz3e4/open_source_dbaas/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1evz3e4/open_source_dbaas/">[comments]</a></span>

## PXE boot for android or something else? For remote management?
 - [https://www.reddit.com/r/selfhosted/comments/1evyyqv/pxe_boot_for_android_or_something_else_for_remote](https://www.reddit.com/r/selfhosted/comments/1evyyqv/pxe_boot_for_android_or_something_else_for_remote)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T11:05:43+00:00

<!-- SC_OFF --><div class="md"><p>I'm currently using a few of the Lenovo ThinkSmart View as my tablet dashboard, based on a few helpful threads explaining how to get it running LineageOS.</p> <p>I am finding that I routinely want to try adding one app or another to different tablets to try out different services and integrations.</p> <p>Since the tablets are on a no-internet vlan, and LineageOS seems to block downloads from non-https sites, serving apk files would actually require dramatically re-organizing my network segmentation, which I'm not yet prepared to do. </p> <p>Once the apps are installed, setting or changing all of the android sysyem settings and app settings is challenging, as there are a lot of ip addresses and usernames and passwords.</p> <p>Is there some other option which would let me establish a parent configuration on Proxmox, with slight brances for each device (e.g., different hostnames, usernames, and passowrds) and push it out to all of them as clients?</p> </

## Search difference between Jellyfin- and Marlin search, implemented into the new Streamyfin app
 - [https://www.reddit.com/r/selfhosted/comments/1evyyis/search_difference_between_jellyfin_and_marlin](https://www.reddit.com/r/selfhosted/comments/1evyyis/search_difference_between_jellyfin_and_marlin)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T11:05:19+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1evyyis/search_difference_between_jellyfin_and_marlin/"> <img alt="Search difference between Jellyfin- and Marlin search, implemented into the new Streamyfin app" src="https://b.thumbs.redditmedia.com/GGblIUwjOc0NLYgTZLyqw0QFnT1mFwrCiAGRdPE6lyc.jpg" title="Search difference between Jellyfin- and Marlin search, implemented into the new Streamyfin app" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/masterinthecage"> /u/masterinthecage </a> <br /> <span><a href="https://www.reddit.com/gallery/1evyyis">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1evyyis/search_difference_between_jellyfin_and_marlin/">[comments]</a></span> </td></tr></table>

## Digitizing Family Photos
 - [https://www.reddit.com/r/selfhosted/comments/1evyenv/digitizing_family_photos](https://www.reddit.com/r/selfhosted/comments/1evyenv/digitizing_family_photos)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T10:30:59+00:00

<!-- SC_OFF --><div class="md"><p>I have three large boxes and a few shopping bags of old family photos sitting in the floor of my office. I’m looking to set up and efficient way to scan and storage, what I think, is 1000s of photos. I run a NAS at home with plenty of storage. Generally, I’m looking to:</p> <ol> <li>Be able to quickly scan photos, possibly a device with an input tray for automatic feeding</li> <li>Have the scanner send the photos to a network storage location</li> <li>Use something like Immich to do facial recognition, album creation and the like. </li> </ol> <p>Since this stack spans hardware and software, I’m open to any and all suggestions. I’m not sure what scanner to buy (willing to spend some money if it means making the job easier) and how to build an assembly line-type process once it’s all set up. I’m hoping to get help from family members to run the line so no one person goes insane from manually scanning and storing each picture individually. </p> <p>TIA!</

## Blog idea - The self-hosting journey
 - [https://www.reddit.com/r/selfhosted/comments/1evycye/blog_idea_the_selfhosting_journey](https://www.reddit.com/r/selfhosted/comments/1evycye/blog_idea_the_selfhosting_journey)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T10:27:51+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone!</p> <p>I'm a network security engineer with a passion for web design and I've been exploring the self-hosting world for about a year and a half.</p> <p>Now I came up with the idea of starting a blog where we can share things we’ve discovered or troubleshooted during our services installations. The goal is to create a place where we can document our experiences, which could be helpful for us in the future and for others who might run into similar issues.</p> <p>I haven’t started the blog yet, so I’m looking for people interested in collaborating as editors. It’s all just for fun! If anyone's interested, drop a comment or send me a message.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/elcolo_"> /u/elcolo_ </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1evycye/blog_idea_the_selfhosting_journey/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comme

## Turning Self-Hosted into a business? Thoughts?
 - [https://www.reddit.com/r/selfhosted/comments/1evya2a/turning_selfhosted_into_a_business_thoughts](https://www.reddit.com/r/selfhosted/comments/1evya2a/turning_selfhosted_into_a_business_thoughts)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T10:22:36+00:00

<!-- SC_OFF --><div class="md"><p>Hi! Just like most of us, I have a passion for self-hosted. I think it's so powerful and I love the concept selfcloud hosting. I'm seriously considering turning my passion into a business.</p> <p>There are probably many people out there who arn't as technical or willing to jump into that side of things. Are any of you doing this? Would you mind sharing your thoughts? Triumphs and Tribulations?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/GregThePHotographer"> /u/GregThePHotographer </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1evya2a/turning_selfhosted_into_a_business_thoughts/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1evya2a/turning_selfhosted_into_a_business_thoughts/">[comments]</a></span>

## Had my first scare on a self-hosted service - random bots using my Gitea instance
 - [https://www.reddit.com/r/selfhosted/comments/1evxtru/had_my_first_scare_on_a_selfhosted_service_random](https://www.reddit.com/r/selfhosted/comments/1evxtru/had_my_first_scare_on_a_selfhosted_service_random)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T09:53:32+00:00

<!-- SC_OFF --><div class="md"><p>So I have a publicly accessible Gitea instance. I use it for my own code as I don't want every silly thing I try to end up on my Github account. I have been using it for a couple of years. I don't use the GUI all that much, just pushing and pulling from command line.</p> <p>So yesterday I logged in to see some code in an old repository I hadn't touched in a while. And what do I see, there are tons of random repositories with mostly sexually explicit names. So I go to the users list and find the same thing, tons of users with sexually explicit usernames. </p> <p>At first I thought my instance had been hacked. But then I saw I still had admin access. Turns out some bot discovered my instance and had been creating users and repos as the instance allowed signups. Most of the repos were empty, but one of them had a random file running into multiple GBs. </p> <p>Needless to say, I promptly started deleting all the repos (as I can't delete users without dele

## Small search engine/indexer
 - [https://www.reddit.com/r/selfhosted/comments/1evxk16/small_search_engineindexer](https://www.reddit.com/r/selfhosted/comments/1evxk16/small_search_engineindexer)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T09:34:33+00:00

<!-- SC_OFF --><div class="md"><p>Looking for something along these lines I add a couple of websites, it should index them and let me search through them, I haven't found anything like this</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fantastic-Schedule92"> /u/Fantastic-Schedule92 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1evxk16/small_search_engineindexer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1evxk16/small_search_engineindexer/">[comments]</a></span>

## Could need some help to decide which zfs layout would be the best for my usecase
 - [https://www.reddit.com/r/selfhosted/comments/1evx0c5/could_need_some_help_to_decide_which_zfs_layout](https://www.reddit.com/r/selfhosted/comments/1evx0c5/could_need_some_help_to_decide_which_zfs_layout)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T08:55:45+00:00

<!-- SC_OFF --><div class="md"><p>Hey folks,</p> <p>hope you could help me decide:</p> <p>Hardware: Truenas Scale with 8 4TB Seagate Ironwolf NAS HDDs</p> <p>Usecase: 1 - 2 VMs with deticated gamingserver (Valheim), a hand full Dockercontainer with nginx hosting static websites, Nextcloud for storing files (mostly video an pictures)</p> <p>Problem: i can not figure out what layout would be the best. Do I need the write IOPS of 4 2-way Mirros or should I go with 2 4-way RAIDZ1 or should I go with 1 8-way RAIDZ1</p> <p>I dont need much redudency because all realy important files are backuped offside.</p> <p>Hope for some experiences. :-)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Stallion_2021"> /u/Stallion_2021 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1evx0c5/could_need_some_help_to_decide_which_zfs_layout/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1evx0c5/could_need_so

## Multilanguage chat
 - [https://www.reddit.com/r/selfhosted/comments/1evwxbw/multilanguage_chat](https://www.reddit.com/r/selfhosted/comments/1evwxbw/multilanguage_chat)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T08:49:52+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I'm looking for a multilanguage chat with a very easy bot. What do you suggest me? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Elemis89"> /u/Elemis89 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1evwxbw/multilanguage_chat/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1evwxbw/multilanguage_chat/">[comments]</a></span>

## Betanin / Beets setup for good tags AND seeding?
 - [https://www.reddit.com/r/selfhosted/comments/1evwwsg/betanin_beets_setup_for_good_tags_and_seeding](https://www.reddit.com/r/selfhosted/comments/1evwwsg/betanin_beets_setup_for_good_tags_and_seeding)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T08:48:45+00:00

<!-- SC_OFF --><div class="md"><p>HI everyone.</p> <p>Been using Navidrome + Betanin for a while since the tags and metadata management of betanin is really great.</p> <p>One thing that I was looking for, though, was for a way to avoid having to copy the files and, instead, hardlinking them. (since apparently I need to WRITE the files to modify tags)</p> <p>Have you found a setup that works for you with Betanin (beets)? Maybe there's a way to integrate it with lidarr?</p> <p>Let me know, thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/scionae"> /u/scionae </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1evwwsg/betanin_beets_setup_for_good_tags_and_seeding/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1evwwsg/betanin_beets_setup_for_good_tags_and_seeding/">[comments]</a></span>

## What backup solution do you use for backing up your servers and devices in your network?
 - [https://www.reddit.com/r/selfhosted/comments/1evw863/what_backup_solution_do_you_use_for_backing_up](https://www.reddit.com/r/selfhosted/comments/1evw863/what_backup_solution_do_you_use_for_backing_up)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T08:00:06+00:00

<!-- SC_OFF --><div class="md"><p>Hello</p> <p>I am looking for a backup solution for backing up my Proxmox Server, Raspberry Pis, Windows and Linux machines.</p> <p>I would prefer something like snapshots, being able to restore ie my Proxmox server to a specific date and time</p> <p>Any suggestions?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/leonheartx1988"> /u/leonheartx1988 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1evw863/what_backup_solution_do_you_use_for_backing_up/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1evw863/what_backup_solution_do_you_use_for_backing_up/">[comments]</a></span>

## Which service would you like a floccus integration for?
 - [https://www.reddit.com/r/selfhosted/comments/1evvyl9/which_service_would_you_like_a_floccus](https://www.reddit.com/r/selfhosted/comments/1evvyl9/which_service_would_you_like_a_floccus)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T07:40:21+00:00

<!-- SC_OFF --><div class="md"><p>Floccus can sync native browser bookmarks. Current sync backends are Nextcloud Bookmarks, WebDAV, Git and Google Drive. Is there any service you would like to sync native browser bookmarks to instead?</p> <p>So far people have requested support for S3 and OneDrive </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/zoontechnicon"> /u/zoontechnicon </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1evvyl9/which_service_would_you_like_a_floccus/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1evvyl9/which_service_would_you_like_a_floccus/">[comments]</a></span>

## SonoBus vs Snapcast?
 - [https://www.reddit.com/r/selfhosted/comments/1evvteb/sonobus_vs_snapcast](https://www.reddit.com/r/selfhosted/comments/1evvteb/sonobus_vs_snapcast)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T07:29:54+00:00

<!-- SC_OFF --><div class="md"><p>Both appear to solve a similar problem - sending audio through network with very low latency. However I haven't been able to find an article that compares the two.</p> <p>Does anyone have experiences with both and could share their insights on which fits what use case better?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kalsan15"> /u/kalsan15 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1evvteb/sonobus_vs_snapcast/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1evvteb/sonobus_vs_snapcast/">[comments]</a></span>

## Emails encryption at rest on OpenBSD using dovecot and GPG
 - [https://www.reddit.com/r/selfhosted/comments/1evvphx/emails_encryption_at_rest_on_openbsd_using](https://www.reddit.com/r/selfhosted/comments/1evvphx/emails_encryption_at_rest_on_openbsd_using)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T07:22:02+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/the_solene"> /u/the_solene </a> <br /> <span><a href="https://dataswamp.org/~solene/2024-08-14-automatic-emails-gpg-encryption-at-rest.html">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1evvphx/emails_encryption_at_rest_on_openbsd_using/">[comments]</a></span>

## Why do you feel self-hosted Nextcloud is a letdown?
 - [https://www.reddit.com/r/selfhosted/comments/1evvai0/why_do_you_feel_selfhosted_nextcloud_is_a_letdown](https://www.reddit.com/r/selfhosted/comments/1evvai0/why_do_you_feel_selfhosted_nextcloud_is_a_letdown)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T06:52:52+00:00

<!-- SC_OFF --><div class="md"><p>As a followup to the recent &quot;Self-host success/letdown&quot; series of threads, I'm really intrigued an interested to find out why there's such a big disappointment in Nextcloud here. </p> <p>It seemed to me that the two biggest issues in the &quot;letdown&quot; thread were lack of speed/snappiness and bloat. </p> <p>Are you guys basically only interested in the file sharing aspect of Nextcloud (I noticed some people stating they switched to Syncthing) and the groupware/collab stuff is bloat to you?</p> <p>I've been self-hosting Owncloud/Nextcloud since the first stable Owncloud version and at this point in time, NC scratches my most pressing itches, namely for a portable file share, calendar, notes and Kanban-style deck app. I use it every day and my unraid-hosted Nextcloud VM doesn't feel unsnappy to me, either. That's why I'm a little surprised to read the quite overwhelming negative sentiment in the thread.</p> </div><!-- SC_ON --> &#32; subm

## Help required in setting up Spliit (Splitwise alternative)
 - [https://www.reddit.com/r/selfhosted/comments/1evuu63/help_required_in_setting_up_spliit_splitwise](https://www.reddit.com/r/selfhosted/comments/1evuu63/help_required_in_setting_up_spliit_splitwise)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T06:20:41+00:00

<!-- SC_OFF --><div class="md"><p>I can't, for the life of me, figure out how to get this up and running. Why are some docker configs so difficult to understand and get them running? I have a fair understanding of spinning up a container but this app is doing my head in. Any help would be appreciated.</p> <p><a href="https://github.com/spliit-app">https://github.com/spliit-app</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Macho-Benjo"> /u/Macho-Benjo </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1evuu63/help_required_in_setting_up_spliit_splitwise/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1evuu63/help_required_in_setting_up_spliit_splitwise/">[comments]</a></span>

## Recommended Remote Connection Server - Rust Desk?
 - [https://www.reddit.com/r/selfhosted/comments/1evu4rm/recommended_remote_connection_server_rust_desk](https://www.reddit.com/r/selfhosted/comments/1evu4rm/recommended_remote_connection_server_rust_desk)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T05:34:52+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I want to self host a remote connection server, similar to TeamViewer. Has anyone had any experience with Rust Desk? If so, what do you think of it? I'm interested in throwing it in a docker container. </p> <p>Is there any other remote software that could be self hosted? </p> <p>Thanks, </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Rick-0-Shay"> /u/Rick-0-Shay </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1evu4rm/recommended_remote_connection_server_rust_desk/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1evu4rm/recommended_remote_connection_server_rust_desk/">[comments]</a></span>

## What self-hosted service has been the biggest success for you?
 - [https://www.reddit.com/r/selfhosted/comments/1evu2du/what_selfhosted_service_has_been_the_biggest](https://www.reddit.com/r/selfhosted/comments/1evu2du/what_selfhosted_service_has_been_the_biggest)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T05:30:34+00:00

<!-- SC_OFF --><div class="md"><p>In contrast to the post asking about disappointing software, what software, popular or otherwise, did you expect to be average but turned out to be the biggest success?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Stefanoverse"> /u/Stefanoverse </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1evu2du/what_selfhosted_service_has_been_the_biggest/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1evu2du/what_selfhosted_service_has_been_the_biggest/">[comments]</a></span>

## taking the plunge w/ proxmox, caddy, plex: any advice?
 - [https://www.reddit.com/r/selfhosted/comments/1evssz5/taking_the_plunge_w_proxmox_caddy_plex_any_advice](https://www.reddit.com/r/selfhosted/comments/1evssz5/taking_the_plunge_w_proxmox_caddy_plex_any_advice)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T04:11:29+00:00

<!-- SC_OFF --><div class="md"><p>Hoping for a little advice before I start a bigger habit. </p> <p>I'm about to turn my dedicated plex box into a larger homelab with proxmox. (I can't really affect the router.) For security and convenience I'm planning on using tailscale+caddy+cloudflare to do the thing where you use a custom domain to share services in your tailnet. Then set up a plex lxc and expand out from there (home assistant, etc). I have 2 concerns for which I'd like a little advice if possible, please.</p> <ol> <li><p>I'd specifically like the plex client on my roku and nvidia shield to use the local network, I'd like plex to still work for it's intended purpose even if the internet is down on the block. I've read different things about achieving this and I'm not sure what the current best way to do that is, or even if I have to do anything specific for that at all?</p></li> <li><p>I'm a little fearful about security for myself and anybody I might share the local network with

## Plausible vs PostHog
 - [https://www.reddit.com/r/selfhosted/comments/1evrocv/plausible_vs_posthog](https://www.reddit.com/r/selfhosted/comments/1evrocv/plausible_vs_posthog)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T03:09:42+00:00

<!-- SC_OFF --><div class="md"><p>Which is better for self-hosted web/product analytics?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JakeRedditYesterday"> /u/JakeRedditYesterday </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1evrocv/plausible_vs_posthog/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1evrocv/plausible_vs_posthog/">[comments]</a></span>

## The modern state of self-hosting
 - [https://www.reddit.com/r/selfhosted/comments/1evrcdf/the_modern_state_of_selfhosting](https://www.reddit.com/r/selfhosted/comments/1evrcdf/the_modern_state_of_selfhosting)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T02:52:53+00:00

<!-- SC_OFF --><div class="md"><p>A long time ago I ran Linux systems that I hosted all kinds of things on (my own web server, e-mail server, etc.). I don't really do that anymore (primarily because residential ISPs block a lot of incoming ports now) but I would like to get back in to hosting some of my own services. I'm running unRAID.</p> <p>It looks like what's done now is to set up a reverse proxy like Nginx on a VPS and then have a VPN tunnel back to my unRAID server to whatever service Ngnix is reverse proxying. So I'll basically have something like <a href="http://minecraft.mydomain.com">minecraft.mydomain.com</a> (for a Minecraft server) that points to an IP address on the VPS. Nginix on the VPS will send the traffic for that back to my unRAID box through probably Wireguard, and things will go back and forth through that tunnel. Do I have that right?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Jon_Hanson"> /u/Jon_Hanson </a> <br /> <s

## Troubleshooting a Node on Cloud VS
 - [https://www.reddit.com/r/selfhosted/comments/1evqqjz/troubleshooting_a_node_on_cloud_vs](https://www.reddit.com/r/selfhosted/comments/1evqqjz/troubleshooting_a_node_on_cloud_vs)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T02:21:38+00:00

<!-- SC_OFF --><div class="md"><p>Firstly, I want to start off with I had been getting help on the official sub for this app but I think the person helping me took my ineptitude to grasp what they were explaining as me being a dick and has ghosted me for a couple days.</p> <p>I'm having issues mapping my FileFlows node. The server is running amazingly but I want to add a node on my Oracle Cloud instance because when I transcode movies it really takes a lot out of my home server. </p> <p>SERVER:</p> <pre><code>podman run -d \ -p 19200:5000 \ -e TZ=America/New_York \ -v /home/{user}/Server/configs/fileflows/temp:/temp \ -v /home/{user}/Server/configs/fileflows/appdata:/app/Data \ -v /home/{user}/Server/configs/fileflows/logs:/app/Logs \ -v /home/{user}/Server/configs/fileflows/config:/config \ -v /home/{user}/Server/Mounts:/data \ --name=fileflows \ --restart=unless-stopped \ --label &quot;io.containers.autoupdate=registry&quot; \ docker.io/revenz/fileflows </code></pre> <p>NODE:</p> <p

## How do you manage LXCs and apps installed on it?
 - [https://www.reddit.com/r/selfhosted/comments/1evqnfj/how_do_you_manage_lxcs_and_apps_installed_on_it](https://www.reddit.com/r/selfhosted/comments/1evqnfj/how_do_you_manage_lxcs_and_apps_installed_on_it)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T02:17:11+00:00

<!-- SC_OFF --><div class="md"><p>I have been seeing recommendations to use LXC on proxmox which is fine.. But I am wondering how do you manage like today what I am doing is</p> <p>I have a VM(s) where I use docker compose files for diff services along with portainer I am running. Open portainer and look at logs, cmd line etc. Also if needed, I can open the application directly from there. </p> <p>What would be same way with multiple LXCs. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/youmeiknow"> /u/youmeiknow </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1evqnfj/how_do_you_manage_lxcs_and_apps_installed_on_it/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1evqnfj/how_do_you_manage_lxcs_and_apps_installed_on_it/">[comments]</a></span>

## Is PostgreSQL recommended for Linkding?
 - [https://www.reddit.com/r/selfhosted/comments/1evpyag/is_postgresql_recommended_for_linkding](https://www.reddit.com/r/selfhosted/comments/1evpyag/is_postgresql_recommended_for_linkding)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T01:42:17+00:00

<!-- SC_OFF --><div class="md"><p>Just wondering if anyone is using PostgreSQL for their Linkding setup? If so, is there a big performance difference?</p> <p>I went down the path of trying Linkwarden and Linkding. I ended up choosing Linkding (<strong>latest-plus</strong> version) and I am super happy with it. It just seems cleaner and lighter than Linkwarden. No disrespect to Linkwarden, it's just a personal preference, not so much a logical preference.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Timely_Anteater_9330"> /u/Timely_Anteater_9330 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1evpyag/is_postgresql_recommended_for_linkding/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1evpyag/is_postgresql_recommended_for_linkding/">[comments]</a></span>

## What's your current/recommended routing setup?
 - [https://www.reddit.com/r/selfhosted/comments/1evpv6u/whats_your_currentrecommended_routing_setup](https://www.reddit.com/r/selfhosted/comments/1evpv6u/whats_your_currentrecommended_routing_setup)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-19T01:37:51+00:00

<!-- SC_OFF --><div class="md"><p>Hi, guys.</p> <p>I'm clearly too new to selfhosting. I feel a strong need to use a router, firewall, and set up my network properly (like a designated SSID for IoT without internet access). But I have no idea where to start. So instead of asking for custom advise, I'd like to know about your network setups:</p> <p><strong>Do you have a physical router? Which model (or which features are key)?</strong></p> <p><strong>Do you have a service (selfhosted) router instead?</strong></p> <p><strong>If you have both, how do they coexist properly?</strong></p> <p>I know I'm shooting in the dark but I just want to learn a bit more about proper basic networking for a small homelab and would appreciate your feedback to point me in the right direction.</p> <p>Thank you all!</p> <p><strong>Background</strong>: I have Proxmox doing most of the work (different services), some old laptops with Ubuntu Server or as HTPC, a few cameras and other IoT.</p> </div><!-- SC_ON -

