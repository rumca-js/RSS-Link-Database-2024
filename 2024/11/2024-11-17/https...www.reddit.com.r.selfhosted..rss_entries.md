# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Redirecterr: Advanced request filtering for Overseerr
 - [https://www.reddit.com/r/selfhosted/comments/1gtr0wd/redirecterr_advanced_request_filtering_for](https://www.reddit.com/r/selfhosted/comments/1gtr0wd/redirecterr_advanced_request_filtering_for)
 - RSS feed: $source
 - date published: 2024-11-17T23:38:07+00:00

<!-- SC_OFF --><div class="md"><p>For the Overseerr users here - just sharing an app I made that might make it a lot smarter:<br/> <a href="https://github.com/varthe/Redirecterr">https://github.com/varthe/Redirecterr</a></p> <p>Redirecterr runs each request through a set of filters and determines where to send it. You can filter based on <strong>any media information available in Overseerr</strong>, including the requester&#39;s username or email. It also supports routing requests to multiple *arr instances simultaneously. It works similarly to Petio&#39;s filters, just without the GUI.</p> <p>Examples of what you can do with the filters:</p> <ul> <li>Send anime to <code>sonarr_anime</code>, and everything else to <code>sonarr</code>.</li> <li>Send kids movies to <code>radarr_kids</code>, anime movies to <code>radarr_anime</code>, and the rest to <code>radarr</code>.</li> <li>Direct requests made by specific users to <code>radarr_remux</code>, while sending others to both <code>radar

## Immich hardware acceleration - Deploying using docker-compose (through Dockage)
 - [https://www.reddit.com/r/selfhosted/comments/1gtqutf/immich_hardware_acceleration_deploying_using](https://www.reddit.com/r/selfhosted/comments/1gtqutf/immich_hardware_acceleration_deploying_using)
 - RSS feed: $source
 - date published: 2024-11-17T23:29:54+00:00

<!-- SC_OFF --><div class="md"><p>I have used the tteck script for Dockge that now comes with immich - <a href="https://community-scripts.github.io/ProxmoxVE/scripts?id=dockge">https://community-scripts.github.io/ProxmoxVE/scripts?id=dockge</a></p> <p>Everything seems to work as intended except for the transcoding part. I do have a 8th gen i5 that supports QuickSync and would like to use it. </p> <p>In my docker-compose (which is the same as the official docker-compose on immich.app), I do see the section on </p> <pre><code>name: immich services: immich-server: container_name: immich_server image: ghcr.io/immich-app/immich-server:${IMMICH_VERSION:-release} # extends: # file: hwaccel.transcoding.yml # service: cpu # set to one of [nvenc, quicksync, rkmpp, vaapi, vaapi-wsl] for accelerated transcoding volumes: # Do not edit the next line. If you want to change the media storage location on your system, edit the value of UPLOAD_LOCATION in the .env file - ${UPLOAD_LOCATION}:/usr/src/app

## How to transform a folder of audio files to a podcast rss feed?
 - [https://www.reddit.com/r/selfhosted/comments/1gtqjpg/how_to_transform_a_folder_of_audio_files_to_a](https://www.reddit.com/r/selfhosted/comments/1gtqjpg/how_to_transform_a_folder_of_audio_files_to_a)
 - RSS feed: $source
 - date published: 2024-11-17T23:15:14+00:00

<!-- SC_OFF --><div class="md"><p>I have already figured out how to use yt-dlp to create a script that checks certain YouTube channels and download the latest YouTube videos, is there a way to create an RSS feed from those folders that I can use in my podcast app of choice?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mashic"> /u/Mashic </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtqjpg/how_to_transform_a_folder_of_audio_files_to_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtqjpg/how_to_transform_a_folder_of_audio_files_to_a/">[comments]</a></span>

## Selfhosting a voice assistant...?
 - [https://www.reddit.com/r/selfhosted/comments/1gtq9z1/selfhosting_a_voice_assistant](https://www.reddit.com/r/selfhosted/comments/1gtq9z1/selfhosting_a_voice_assistant)
 - RSS feed: $source
 - date published: 2024-11-17T23:02:36+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/IngwiePhoenix"> /u/IngwiePhoenix </a> <br/> <span><a href="https://www.reddit.com/r/LocalLLaMA/comments/1gtq9h6/so_whatever_happened_to_voice_assistants/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtq9z1/selfhosting_a_voice_assistant/">[comments]</a></span>

## Storing photos directly from iPhone to home server
 - [https://www.reddit.com/r/selfhosted/comments/1gtpn7u/storing_photos_directly_from_iphone_to_home_server](https://www.reddit.com/r/selfhosted/comments/1gtpn7u/storing_photos_directly_from_iphone_to_home_server)
 - RSS feed: $source
 - date published: 2024-11-17T22:33:21+00:00

<!-- SC_OFF --><div class="md"><p>My homeserver / lab is a Lenovo thinkCentre from a few years ago. </p> <p>It has 500gb of storage (HDD) and running windows 11 home. </p> <p>I can remote into it from my mac. </p> <p>I currently pay ~$3 a month to apple for 50GB of iCloud storage. </p> <p>I bought the thinkcentre so I can learn more about self hosting. Whether it be storing things myself or learning more about networking. </p> <p>Any suggestions of an ideally free app / method to upload all my iPhone&#39;s photos to my &#39;server&#39; ?<br/> I&#39;d like it to auto update too. Essentially if I delete a picture or video on my iPhone it will delete it on the server too. </p> <p>I saw someone mention ICloudPD. Any good? Other suggestions?<br/> Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/NicoRulli"> /u/NicoRulli </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtpn7u/storing_photos_directly_from_iphone_to_home_ser

## Arr apps competing for the same port when using Gluetun
 - [https://www.reddit.com/r/selfhosted/comments/1gtp803/arr_apps_competing_for_the_same_port_when_using](https://www.reddit.com/r/selfhosted/comments/1gtp803/arr_apps_competing_for_the_same_port_when_using)
 - RSS feed: $source
 - date published: 2024-11-17T22:14:09+00:00

<!-- SC_OFF --><div class="md"><p>Within a docker stack, I&#39;m trying to get Gluetun working for Arr apps. After getting Gluetun &amp; QBittorent working, I started adding apps one a time into the compose file. Prowlarr added and it worked. However, adding Sonarr next created an issue. Prowlarr and Sonarr started fighting over port 9696. It&#39;s random which one gets if first and then the second one fails thinking that it too should use 9696. I can only log into whichever one wins the port war.</p> <p>For instance, if Sonarr grabs it first, the major terminal error =<br/> <code>prowlarr | [Fatal] ConsoleApp: Failed to bind to address http://[::]:9696: address already in use</code></p> <p>I can post the entire compose file, if needed, but here are what I think are the relevant parts to save some scrolling. Thank you very much if you can explain what I&#39;m missing. First section is under Gluetun:<br/> (Note: I added the WEBUI_PORT= nnnn out of desperation but it wasn&#39;t in samp

## Project management
 - [https://www.reddit.com/r/selfhosted/comments/1gtp4cd/project_management](https://www.reddit.com/r/selfhosted/comments/1gtp4cd/project_management)
 - RSS feed: $source
 - date published: 2024-11-17T22:09:45+00:00

<!-- SC_OFF --><div class="md"><p>I am in the (never-ending) process of building a homelab. I do have quite some stuff running already, but nothing production-ready as I never finish anything! Everytime I get stuck on something or I find another idea, I start on something else... So now I&#39;m looking for a good, powerful project management app that I can selfhost. Adding ideas, make to do&#39;s, add priorities, keep track of what to do for what,... What are you all using for this?</p> <p>For years I thought I would remember everything. Lately I have to admit that by thinking this, I&#39;m not doing myself a favour...</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Bart2800"> /u/Bart2800 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtp4cd/project_management/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtp4cd/project_management/">[comments]</a></span>

## Matrix Synapse - confused about where to put the .well-known file
 - [https://www.reddit.com/r/selfhosted/comments/1gtol9y/matrix_synapse_confused_about_where_to_put_the](https://www.reddit.com/r/selfhosted/comments/1gtol9y/matrix_synapse_confused_about_where_to_put_the)
 - RSS feed: $source
 - date published: 2024-11-17T21:46:26+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I looked through some old posts and started following this <a href="https://theselfhostingblog.com/posts/self-hosting-your-own-matrix-server-on-a-raspberry-pi/">tutorial from TheSelfHostingBlog.com</a> for setting up a Federated Matrix Synapse server. Other searches are pretty opaque, although I am still learning, so much of this part is a bit above my head.</p> <p>Things went very, very smooth until I hit this part in the last quarter of the tutorial:</p> <p>&quot;We also need to add a <code>.well-known</code> file. This will allow us to Federate our server and use our base domain as our identity.&quot;</p> <p>It gives clear instruction as to what needs to be in the .well-known file, but not where it goes. I&#39;ve tried putting it in /etc/nginx/sites-available/ where the matrix.example.com file is, but no dice. Also tried appending it to the end of the matrix.example.com file, but I get an error as soon as I run certbot again.</p> <p>

## Vaultwarden High Availability options
 - [https://www.reddit.com/r/selfhosted/comments/1gtoj0g/vaultwarden_high_availability_options](https://www.reddit.com/r/selfhosted/comments/1gtoj0g/vaultwarden_high_availability_options)
 - RSS feed: $source
 - date published: 2024-11-17T21:43:40+00:00

<!-- SC_OFF --><div class="md"><p>I got VaultWarden setup, but I want to setup a backup node at my offsite incase the primary goes down for whatever reason. Either being server maintenance, power outage, or what not. I did some playing around, and I appears if I mirror the whole Vaultwarden docker directory containing the DB, server config, and everything else. It syncs just find and will just need to login to the other server when the primary goes down. Does this sound right? Is there any issues that may cause? I don’t use any other special functions other than TOTP and password storage. I don’t use notifications from the app or anything like that. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RealJoshLee0"> /u/RealJoshLee0 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtoj0g/vaultwarden_high_availability_options/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtoj0g/vaultwarde

## Newsbridge: get news from foreign RSS feeds translated, summarized, and spoken to you daily.
 - [https://www.reddit.com/r/selfhosted/comments/1gtoenc/newsbridge_get_news_from_foreign_rss_feeds](https://www.reddit.com/r/selfhosted/comments/1gtoenc/newsbridge_get_news_from_foreign_rss_feeds)
 - RSS feed: $source
 - date published: 2024-11-17T21:38:15+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been listening to Google Assistant&#39;s daily news briefings for more than 6 months now, but I always felt like the selection of sources was very limited. So, I made Newsbridge.</p> <p><a href="https://github.com/AshkanArabim/newsbridge">Newsbridge</a> is a self-hosted website that summarizes, translates, and reads the most recent news from the user&#39;s RSS feeds. Now you can listen to Congolese or Kazakh news every morning with minimal effort! (assuming you can find the right RSS feeds)</p> <p>It uses Llama as the LLM and Coqui for TTS, so everything runs locally. Just make sure you have a decent GPU on your machine!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AshkanArabim"> /u/AshkanArabim </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtoenc/newsbridge_get_news_from_foreign_rss_feeds/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/

## Can't connect to Minecraft server running on WSL2
 - [https://www.reddit.com/r/selfhosted/comments/1gtoalz/cant_connect_to_minecraft_server_running_on_wsl2](https://www.reddit.com/r/selfhosted/comments/1gtoalz/cant_connect_to_minecraft_server_running_on_wsl2)
 - RSS feed: $source
 - date published: 2024-11-17T21:33:16+00:00

<!-- SC_OFF --><div class="md"><p>It&#39;s not ideal I know but I&#39;m trying to develop a custom server software for bedrock and I cant seem to connect to that running on WSL either. I&#39;ve tried Mirrored mode and Nat mode and neither worked, I&#39;ve trued localhost/127.0.0.1 and other IPs but still no luck. There was a similar post on here but everyone said to host on windows but im trying to develop for linux as well so that wont work.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MisledWater79"> /u/MisledWater79 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtoalz/cant_connect_to_minecraft_server_running_on_wsl2/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtoalz/cant_connect_to_minecraft_server_running_on_wsl2/">[comments]</a></span>

## Best solution to download YouTube video's as audio?
 - [https://www.reddit.com/r/selfhosted/comments/1gto2qt/best_solution_to_download_youtube_videos_as_audio](https://www.reddit.com/r/selfhosted/comments/1gto2qt/best_solution_to_download_youtube_videos_as_audio)
 - RSS feed: $source
 - date published: 2024-11-17T21:23:56+00:00

<!-- SC_OFF --><div class="md"><p>I regularly listen to live sets on YT and I have used TubeArchivist to grab some of these as video files, great for when I am on my laptop.</p> <p>However, I would also like to grab these live Yt sets, so I can listen to them in the car.</p> <p>Is anyone already doing this or knows how to best achieve this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AluminiumHoedje"> /u/AluminiumHoedje </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gto2qt/best_solution_to_download_youtube_videos_as_audio/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gto2qt/best_solution_to_download_youtube_videos_as_audio/">[comments]</a></span>

## Searchable Recipe Database
 - [https://www.reddit.com/r/selfhosted/comments/1gto17c/searchable_recipe_database](https://www.reddit.com/r/selfhosted/comments/1gto17c/searchable_recipe_database)
 - RSS feed: $source
 - date published: 2024-11-17T21:22:03+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/ShagohodEnjoyer"> /u/ShagohodEnjoyer </a> <br/> <span><a href="https://hari.recipes/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gto17c/searchable_recipe_database/">[comments]</a></span>

## Non recoverable faliure on brand new radarr container.
 - [https://www.reddit.com/r/selfhosted/comments/1gtn69p/non_recoverable_faliure_on_brand_new_radarr](https://www.reddit.com/r/selfhosted/comments/1gtn69p/non_recoverable_faliure_on_brand_new_radarr)
 - RSS feed: $source
 - date published: 2024-11-17T20:44:31+00:00

<!-- SC_OFF --><div class="md"><p>Hi</p> <p>I have Proxmox set up. it runs truenas for storage and ubuntu for containers. I have truenas smb mounted on one of ubuntu directory for all the container data and all other files. I had some permission issue earlier which I resolved and I got plex running. However now when I try to run sonarr or radar I am getting the following in the logs.</p> <p>any help is much appreciated.</p> <pre><code> ██╗ ███████╗██╗ ██████╗ ██║ ██╔════╝██║██╔═══██╗ ██║ ███████╗██║██║ ██║ ██║ ╚════██║██║██║ ██║ ███████╗███████║██║╚██████╔╝ ╚══════╝╚══════╝╚═╝ ╚═════╝ Brought to you by linuxserver.io ─────────────────────────────────────── To support the app dev(s) visit: Radarr: https://opencollective.com/radarr To support LSIO projects visit: https://www.linuxserver.io/donate/ ─────────────────────────────────────── GID/UID ─────────────────────────────────────── User UID: 1000 User GID: 1000 ─────────────────────────────────────── Linuxserver.io version: 5.14.0.93

## Why do I end up at router admin page when trying to access external IP?
 - [https://www.reddit.com/r/selfhosted/comments/1gtmhil/why_do_i_end_up_at_router_admin_page_when_trying](https://www.reddit.com/r/selfhosted/comments/1gtmhil/why_do_i_end_up_at_router_admin_page_when_trying)
 - RSS feed: $source
 - date published: 2024-11-17T20:13:48+00:00

<!-- SC_OFF --><div class="md"><p>I have been self hosting from home for several years. After a move a couple of years ago, I ended up with a fiber router provided by the ISP. With this came an issue I didn&#39;t encounter before, and until now I have been ignoring it. But now I&#39;m looking for a solution.</p> <p>The issue is that I cannot reach my services from my home network if I use the public IP. For some reason I end up at the fiber router instead on the internal IP. If I do this outside my home network then everything works. </p> <p>So far I have worked around this by just overriding DNS locally. But I don&#39;t really want to run a DNS server or have to deal with config on all devices to get this to work. Are there other options? </p> <p>Ideally I want it to work even for things like a Chromecast with hard coded Google DNS.</p> <p>I&#39;m thinking that there should be some setting in the router for things like this but I haven&#39;t managed to find it. If this what hairpinn

## Windows Backup solution which just works
 - [https://www.reddit.com/r/selfhosted/comments/1gtmg8j/windows_backup_solution_which_just_works](https://www.reddit.com/r/selfhosted/comments/1gtmg8j/windows_backup_solution_which_just_works)
 - RSS feed: $source
 - date published: 2024-11-17T20:12:13+00:00

<!-- SC_OFF --><div class="md"><p>Hello, selfhosted community. I&#39;m trying to find a windows backup client which, once configured, works in the background without EVER even mentioning that exists on the computer. </p> <p>- As we are in &quot;selfhosted&quot;, it must allow backup to my own server. Ideally over ssh/ssftp or via webdav/https. Any other protocol is also OK if the server-side part can run on linux. </p> <p>- Allows to backup the whole PC and correctly ignores system/temporary files.</p> <p>- Is relatively good at managing network usage (doesn&#39;t re-transmit the whole 200GB without reason).</p> <p>- Most importantly: it&#39;s stealthy. Recovers gracefully from pc going to sleep and starting up on a completely different network. It can be configured to auto-update itself without ever asking the user about it. </p> <p>- It doesn&#39;t have to be free/open source. I&#39;m ready to pay up to 50$ per year for a 3-client licence as long as it&#39;s from a company not base

## Troubleshooting constant 100% CPU utilization bursts on VPS
 - [https://www.reddit.com/r/selfhosted/comments/1gtltcx/troubleshooting_constant_100_cpu_utilization](https://www.reddit.com/r/selfhosted/comments/1gtltcx/troubleshooting_constant_100_cpu_utilization)
 - RSS feed: $source
 - date published: 2024-11-17T19:44:25+00:00

<!-- SC_OFF --><div class="md"><p>I have a django web app with nginx, postgres, gunicorn all containerized running on the same VPS on a Linode 2GB plan. Google Analytics and Cloudflare is showing ~6k active unique users in a month and the CPU utilization constantly hits 100% throughout the day and I&#39;m not sure what it is. Looking at htop and docker stats, the CPU utilization is not constant at 100%. It bursts from 1%, 40-70% and then 100% within seconds. I also monitored the access log live and most of the traffic seems like it&#39;s from crawler bots. Do I need a larger server?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/throwaway08642135135"> /u/throwaway08642135135 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtltcx/troubleshooting_constant_100_cpu_utilization/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtltcx/troubleshooting_constant_100_cpu_utilization/">[comments

## PBX on Single Board Computer
 - [https://www.reddit.com/r/selfhosted/comments/1gtl320/pbx_on_single_board_computer](https://www.reddit.com/r/selfhosted/comments/1gtl320/pbx_on_single_board_computer)
 - RSS feed: $source
 - date published: 2024-11-17T19:12:10+00:00

<!-- SC_OFF --><div class="md"><p>I have a single incoming POTS line that I&#39;d like to connect to my Raspberry PI and use software like Asterix to enable some simple features like voice-mail to email and perhaps some sort of menu system. Additional future features like using a SIP client so I can remotely make / receive calls from my land line would be kind of fun to play with too.</p> <p>Where I&#39;m stuck is connecting the RJ11 line to the PI. Ideally it would be some sort of USB device with an RJ11 plug on one end and USB on the other that would be Linux supported (Raspian) and some sort of magic Gruffy Dust to make it all work in between.</p> <p>In my various reading / searching, I&#39;ve seen some people use a &quot;voice modem&quot; for this purpose, but a lot seem to use an Analog to Telephone Adapter that acts as a network device.</p> <p>I could connect some sort of gizmo like the Grandstream HT801 to my router and land line but that would mean fishing the land-line cable

## Looking for Advice: Best Hardware Upgrade for My Server
 - [https://www.reddit.com/r/selfhosted/comments/1gtkx6w/looking_for_advice_best_hardware_upgrade_for_my](https://www.reddit.com/r/selfhosted/comments/1gtkx6w/looking_for_advice_best_hardware_upgrade_for_my)
 - RSS feed: $source
 - date published: 2024-11-17T19:05:05+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’m planning to upgrade my server setup and wanted to ask for your advice on the best hardware path to take. Here’s my current setup:</p> <p><strong>Current Setup:</strong></p> <ul> <li><strong>CPU:</strong> Intel E3-1231 v3</li> <li><strong>GPU:</strong> GeForce 1050Ti</li> <li><strong>RAM:</strong> 32GB</li> </ul> <p><strong>Running Proxmox with Two VMs:</strong></p> <ol> <li><strong>TrueNAS:</strong> 2 Cores, 6GB RAM (2x14TB Mirror)</li> <li><strong>Ubuntu 24.04:</strong> 6 Cores, 22GB RAM</li> </ol> <p>This leaves 4GB for the Proxmox main OS.</p> <p><strong>Usage:</strong><br/> I mainly use the server for Plex, Nextcloud, and game servers (e.g., Minecraft modpacks, Enshrouded). Recently, I’ve noticed that 6 cores aren’t sufficient to run Enshrouded stably, prompting me to consider an upgrade.</p> <p><strong>Planned Upgrade:</strong></p> <ul> <li><strong>CPU:</strong> Ryzen 5 5600G 125€</li> <li><strong>Motherboard:</strong> AS

## Public IP changing
 - [https://www.reddit.com/r/selfhosted/comments/1gtkj8x/public_ip_changing](https://www.reddit.com/r/selfhosted/comments/1gtkj8x/public_ip_changing)
 - RSS feed: $source
 - date published: 2024-11-17T18:48:19+00:00

<!-- SC_OFF --><div class="md"><p>Every time my router restarts, a new public ip is assigned.</p> <p>Is there a way to have the system not update? I connect to Jellyfin via Cloudflare.</p> <p>Thanks </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/coldhandsss"> /u/coldhandsss </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtkj8x/public_ip_changing/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtkj8x/public_ip_changing/">[comments]</a></span>

## Searxng in Portainer
 - [https://www.reddit.com/r/selfhosted/comments/1gtk44p/searxng_in_portainer](https://www.reddit.com/r/selfhosted/comments/1gtk44p/searxng_in_portainer)
 - RSS feed: $source
 - date published: 2024-11-17T18:29:54+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>is anybody running <a href="https://github.com/searxng/searxng-docker">searxng</a> via Portainer?</p> <p>I can&#39;t get it running via stacks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ThorstenDoernbach"> /u/ThorstenDoernbach </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtk44p/searxng_in_portainer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtk44p/searxng_in_portainer/">[comments]</a></span>

## Self Hosted Voice Memo Service?
 - [https://www.reddit.com/r/selfhosted/comments/1gtk0l9/self_hosted_voice_memo_service](https://www.reddit.com/r/selfhosted/comments/1gtk0l9/self_hosted_voice_memo_service)
 - RSS feed: $source
 - date published: 2024-11-17T18:25:30+00:00

<!-- SC_OFF --><div class="md"><p>I was wondering if anyone knew of a voice memo service I could run in a WebUI. I just would like them to be stored locally on my server and be able to access them later.</p> <p>Transcription would be a huge plus but not necessary. Does this exist? I&#39;ve done a lot of googling and haven&#39;t come across much.</p> <p>I&#39;ve found a few very cool note taking/organizing projects that I&#39;ll probably be installing regardless of wether I can find what I&#39;m looking for but figured I&#39;d ask here.</p> <p>If you could point me in the right direction that would be amazing.</p> <p>Edit: Docker and open source preferred.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jcsomerville"> /u/jcsomerville </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtk0l9/self_hosted_voice_memo_service/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtk0l9/self_hosted_

## CF, NPM and iCloud Private Relay warnings
 - [https://www.reddit.com/r/selfhosted/comments/1gtk073/cf_npm_and_icloud_private_relay_warnings](https://www.reddit.com/r/selfhosted/comments/1gtk073/cf_npm_and_icloud_private_relay_warnings)
 - RSS feed: $source
 - date published: 2024-11-17T18:25:02+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I&#39;m using NPM with a domain on Cloudflare to access my services only locally with https and a structure like service.domain.tld.</p> <p>Cloudflare DNS configuration has an A record pointed to my internal NPM instance IP address and a CNAME * record NOT proxied by CF (grey icon).</p> <p>Everything works as a charm, except that many services (strangely, not all) give, every time I load or reload the webpage, an iCloud Private Relay warning stating that connection is not private and that it cannot hide my IP to the destination server. Mind that I&#39;m not talking about an https error per se, but an iCloud warning page. </p> <p>It&#39;s becoming VERY annoying having to click on &quot;continue&quot; each time. I DON&#39;T want to turn off iCloud PR too. AFAIK, you cannot fully disable iPR for a specific domain or website, only once but at the next page load it&#39;s up again with its warning page.</p> <p>Is there anything I can do to b

## How to set up a "spoofed" local proxy/VPN?
 - [https://www.reddit.com/r/selfhosted/comments/1gtjo4k/how_to_set_up_a_spoofed_local_proxyvpn](https://www.reddit.com/r/selfhosted/comments/1gtjo4k/how_to_set_up_a_spoofed_local_proxyvpn)
 - RSS feed: $source
 - date published: 2024-11-17T18:10:23+00:00

<!-- SC_OFF --><div class="md"><p>Hi! Let me know if this isn&#39;t the right place to ask this question, though at a first glance this sub gives more useful advice than Privacy or Netsec.</p> <p>First, use case. I&#39;m an academic working on sensitive topics. My colleague was doing online research on, uhm, crisis groups. Despite using TOR, they ended up getting interrogated by intelligence agents, but they were ultimately able to explain themselves. My research area is a little less serious, but the things I&#39;d have to access would still definitely get me flagged. I&#39;ve got enough stress in my life that getting a knock on my door, even if I know I&#39;ve done nothing wrong, would wreck me mentally. I guess bypassing region lock or free download limits would be a bonus.</p> <p>Second, my understanding of the current privacy/security realities. TOR clearly isn&#39;t enough. Basic proxies also don&#39;t accomplish much. Basic spoofing only works for sending, not receiving data. 

## Looking for a good http requests/responses dashboard
 - [https://www.reddit.com/r/selfhosted/comments/1gtjnyv/looking_for_a_good_http_requestsresponses](https://www.reddit.com/r/selfhosted/comments/1gtjnyv/looking_for_a_good_http_requestsresponses)
 - RSS feed: $source
 - date published: 2024-11-17T18:10:12+00:00

<!-- SC_OFF --><div class="md"><p>In my golang script i have an array of http requets and their responses (the format have doesn&#39;t matter) i&#39;m looking for some software that i can import these requests/responses into and be able to do the following 1- see a tree like file structure (like Burp Suite&#39;s target tab or postman collections viewer on the left side) where i can click a directories name for example and hide all the files/directories under that directory 2- search through all the requests/resposnes (hopefully using regex) and highlight the string i searched for in the tab showing reqeust/response 3- (optional really) manipulate a request some how in the dashboard and send the request again and see the response</p> <p>since i have everything in my golang script, i can export them in any json format for any toool, i&#39;m just looking for the right one</p> <p>options i&#39;ve looked at: 1- exporting all the responses/requests to files/directories and use a tui file m

## Full automation of Proxmox LXC/VMs and related dockers
 - [https://www.reddit.com/r/selfhosted/comments/1gtj75c/full_automation_of_proxmox_lxcvms_and_related](https://www.reddit.com/r/selfhosted/comments/1gtj75c/full_automation_of_proxmox_lxcvms_and_related)
 - RSS feed: $source
 - date published: 2024-11-17T17:50:10+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I have a proxmox node with 5 LXCs and 1 VM inside. I am thinking of a way to automate everything: 1. both the deployment of LXC/VMs 2. both the installation of docker inside the LXCs and the deployment of the containers.</p> <p>I would like it to be all 1-click. E.g. downloading something from a git repo starts a pipeline that first deploys the machines then installs docker and then starts the containers. Some ultra automated stuff</p> <p>Ideas? Experiences?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/abbondanzio"> /u/abbondanzio </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtj75c/full_automation_of_proxmox_lxcvms_and_related/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtj75c/full_automation_of_proxmox_lxcvms_and_related/">[comments]</a></span>

## Residential Dedicated IP - Turkey/Ukraine
 - [https://www.reddit.com/r/selfhosted/comments/1gtizhy/residential_dedicated_ip_turkeyukraine](https://www.reddit.com/r/selfhosted/comments/1gtizhy/residential_dedicated_ip_turkeyukraine)
 - RSS feed: $source
 - date published: 2024-11-17T17:40:50+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a place that offers a residential dedicated IP for turkey or ukraine to be able to have the same IP address when joining a game. I need this so I can then change my account location to one of these locations. Whats the best one to do as it seems no major VPN provider has turkey or ukraine</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Latter-Bluejay-5199"> /u/Latter-Bluejay-5199 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtizhy/residential_dedicated_ip_turkeyukraine/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtizhy/residential_dedicated_ip_turkeyukraine/">[comments]</a></span>

## VPN
 - [https://www.reddit.com/r/selfhosted/comments/1gtisyi/vpn](https://www.reddit.com/r/selfhosted/comments/1gtisyi/vpn)
 - RSS feed: $source
 - date published: 2024-11-17T17:32:42+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve using Tailscale to access my network but sometimes I have been getting an error message regarding the relay and noticed the speed is slower while accessing my network. How can I setup a personal VPN with Open VPN or a similar app? Currently using Truenas Scale and usually use the pre loaded apps since didn&#39;t have the time to learn about docker or virtual machines. Thanks for any help and sorry if this question was answered before.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RommelDav"> /u/RommelDav </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtisyi/vpn/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtisyi/vpn/">[comments]</a></span>

## Bypassing cgnat with wireguard & traefik
 - [https://www.reddit.com/r/selfhosted/comments/1gths1s/bypassing_cgnat_with_wireguard_traefik](https://www.reddit.com/r/selfhosted/comments/1gths1s/bypassing_cgnat_with_wireguard_traefik)
 - RSS feed: $source
 - date published: 2024-11-17T16:49:15+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I&#39;m another victm of ipv4 exhaustion, my isp has cgnat and they don&#39;t allow me to buy static ip...</p> <p>I bought a server(it hasn&#39;t came to me yet but I&#39;m preparing for it) and I want to host some of my contenerized docker apps on it. I know that there are a lot of guides about self hosting, but I couldn&#39;t find one that fits my use case. </p> <p>I have a friend that has static ip and I thought that I can use that, I have: </p> <ul> <li>raspberry pi that will run traefik and wireguard server</li> <li>my server, that will run proxmox, wireguard, docker kubernetes, rancher....</li> <li>my PC that will be an admin for everything</li> </ul> <p>I&#39;m currently trying to follow a couple of articles on bypassing cgnat and self hosting but to be honest I&#39;m scarred to modify them too much, but I know that they probably won&#39;t work if I modify them.<br/> My current goals are:</p> <ul> <li>set up wireguard on raspberry pi</l

## Advice needed on migrating multiple WordPress sites from Plesk server manager and AWS EC2 to Synology NAS
 - [https://www.reddit.com/r/selfhosted/comments/1gthn5m/advice_needed_on_migrating_multiple_wordpress](https://www.reddit.com/r/selfhosted/comments/1gthn5m/advice_needed_on_migrating_multiple_wordpress)
 - RSS feed: $source
 - date published: 2024-11-17T16:43:22+00:00

<!-- SC_OFF --><div class="md"><p>So, I am currently running 5 Word Press websites, they have very little traffic and I do not mind the risk of any downtime occurred from selfhosting. My current setup works really well, Plesk is great for server management with WP-Toolkit and the Cloudfare DNS plugin, but although fairly small, I cannot justify the cost for such little traffic.</p> <p>I am spending on average £53 per month with Plesk licensing (£21) and AWS fees (£32). Also, earlier this year I built my own DIY Unraid server, so now my Synology DS918+ has been pretty much sitting gathering dust and underutilised with only Surveillance Station running (only using 1-4% CPU and 5% RAM of 16GB).</p> <p>Now I do not think there is any selfhosted service that does what Plesk or WP-Toolkit does and I am wondering what direction I should take to tackle this without exposing any ports on my home network. I have experience using docker compose and Cloudfare tunnels to expose services and wonde

## Need Repl.it like selfhosted browser IDE
 - [https://www.reddit.com/r/selfhosted/comments/1gthmya/need_replit_like_selfhosted_browser_ide](https://www.reddit.com/r/selfhosted/comments/1gthmya/need_replit_like_selfhosted_browser_ide)
 - RSS feed: $source
 - date published: 2024-11-17T16:43:07+00:00

<!-- SC_OFF --><div class="md"><p>Hello, due to the recent changes in term of price of <a href="http://repl.it">repl.it</a> . I want to self-host an alternative capable of similar things (especially web and C# programming with Mono).</p> <p>If there is any service like what I am looking for, please let me know.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/yazzqlf"> /u/yazzqlf </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gthmya/need_replit_like_selfhosted_browser_ide/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gthmya/need_replit_like_selfhosted_browser_ide/">[comments]</a></span>

## Best tool to scrape flight prices
 - [https://www.reddit.com/r/selfhosted/comments/1gthluy/best_tool_to_scrape_flight_prices](https://www.reddit.com/r/selfhosted/comments/1gthluy/best_tool_to_scrape_flight_prices)
 - RSS feed: $source
 - date published: 2024-11-17T16:41:50+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys. I am looking for a few specific flight prices on Skyscanner. Now my thought was that I could automate that with some kind of web scraping tool, and give me notifications on price drops. </p> <p>Preferably I would like a neat UI or at least a tool with simple to understand code (not really a coder when it gets a bit more advanced)</p> <p>Does not necessarily be selfhosted, but I definitely prefer it.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dennis_Eiscreme"> /u/Dennis_Eiscreme </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gthluy/best_tool_to_scrape_flight_prices/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gthluy/best_tool_to_scrape_flight_prices/">[comments]</a></span>

## Manage and listen to podcasts
 - [https://www.reddit.com/r/selfhosted/comments/1gth883/manage_and_listen_to_podcasts](https://www.reddit.com/r/selfhosted/comments/1gth883/manage_and_listen_to_podcasts)
 - RSS feed: $source
 - date published: 2024-11-17T16:25:26+00:00

<!-- SC_OFF --><div class="md"><p>Good morning.</p> <p>Currently, through <strong>flexget</strong>, I download a few podcasts that I like to listen to more calmly or that last longer than the usual 10 minutes.</p> <p>So, I would like to be able to listen to them from anywhere through <strong>AntennaPod</strong> (mobile).</p> <p>Right now, I can do this, but in an unsafe way, where I first create an rss (<strong>genRSS</strong>) of the directories that contain the podcasts and then both the feed and the directories are exposed to the internet through <strong>webdav</strong>.</p> <p>I have tried both <strong>podgrab</strong> and <strong>podfetch</strong>, but with neither of the 2 I get what I want, that it manages the podcasts, that it creates a feed for me and then I can listen to them from AntennaPod.</p> <p>I also tried <strong>audiobookshelf</strong>, but from what I saw, you can only make a feed of a single chapter and not of an entire directory with all the podcasts I have.</p> 

## PiHole when available
 - [https://www.reddit.com/r/selfhosted/comments/1gth0f1/pihole_when_available](https://www.reddit.com/r/selfhosted/comments/1gth0f1/pihole_when_available)
 - RSS feed: $source
 - date published: 2024-11-17T16:16:02+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I am kind of new to self-hosting stuff and in need of some help regarding pi-hole. For the record, I currently have PiHole, Plex, Netdata, CasaOS, Organizr, Crafty self-hosted (still trying out new stuff)</p> <p>The question is, can I set-up my router to use pi-hole when it is available and use any other DNS when it&#39;s not? The issue is that sometimes I need to shut-down the server and I want the router to continue working even if the pi-hole is down. I assume it really depends on the router itself, but just asking if it&#39;s possible in general.</p> <p>Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/seekingadvice331"> /u/seekingadvice331 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gth0f1/pihole_when_available/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gth0f1/pihole_when_available/">[comments]</a></span>

## I'm searching for a self-hosted, multi-site landing pages/blog CMS
 - [https://www.reddit.com/r/selfhosted/comments/1gtgx68/im_searching_for_a_selfhosted_multisite_landing](https://www.reddit.com/r/selfhosted/comments/1gtgx68/im_searching_for_a_selfhosted_multisite_landing)
 - RSS feed: $source
 - date published: 2024-11-17T16:12:05+00:00

<!-- SC_OFF --><div class="md"><p>Hello everybody,</p> <p>I&#39;m writing searching for help to host on my home server a CMS that can manage multiple small blogs/landing pages for my own personal projects.</p> <p>I&#39;ve spent the past 2 months (literally) trying to do this through a combination of Astro and any CMS that could work with it, without any success. Now, I&#39;m searching for alternatives.</p> <p>I&#39;m searching for something that: </p> <ul> <li>is self-hosted;</li> <li>can manage multiple sites/blogs from the same CMS; </li> <li>can generate landing pages that have this kind of look&amp;feel = <a href="https://astrowind.vercel.app/">https://astrowind.vercel.app/</a></li> <li>from the CMS, I can both create new articles/pages and edit the text and images appearing in the static section of the site. </li> </ul> <p>Astro + any CMS apparently is too technical for me, and I&#39;m this close to go back to Wordpress and I really would like to avoid it. </p> <p>Please, help!<

## Configuring Wireguard
 - [https://www.reddit.com/r/selfhosted/comments/1gtghus/configuring_wireguard](https://www.reddit.com/r/selfhosted/comments/1gtghus/configuring_wireguard)
 - RSS feed: $source
 - date published: 2024-11-17T15:52:59+00:00

<!-- SC_OFF --><div class="md"><p>Hi Everyone,<br/> I have a problem in playing on internet with a friend at an old games when one of them need to be the server: we don&#39;t have a pubblic ip.</p> <p>Now for my homelab server (I have a k3s cluster selfhosted in my home) I solved the problem of the public IP with a VM on hetzner with public IP AND an SSH Tunnel.</p> <p>My idea is to use this VM with public ip also as a server for Wireguard. So that both my and my friend connect to the VPN, have a VPN IP, and then use them to play the game.</p> <p>This idea can work for you? If yes, where can I find an howto to configure this ?</p> <p>Because I install wireguard on the server (ubuntu server 24.01) and on one client (windows 11), but I&#39;m a bit confusing on how I need to configure both server and client.</p> <p>I also would like to create on my side the configuration file for all the client and then only to share it to my friend (or maybe to multiple friends). This because the game 

## WAF Configuration problem
 - [https://www.reddit.com/r/selfhosted/comments/1gtg60a/waf_configuration_problem](https://www.reddit.com/r/selfhosted/comments/1gtg60a/waf_configuration_problem)
 - RSS feed: $source
 - date published: 2024-11-17T15:38:11+00:00

<!-- SC_OFF --><div class="md"><p>To explain to you I have a waf that redirect the traffic to backend servers, all the dns records are binded to it and I want to limit access to multiple web apps runing in backend servers throught containers, the problem I faced while using iptables to restrict the traffic to the backend containers to be only accessible by the waf I&#39;am very confused on which rules to write is it the input or docker user or both of them and when I do write both of them the apps are still accessible when writting trought the IP of the backend server.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/IceAdept2813"> /u/IceAdept2813 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtg60a/waf_configuration_problem/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtg60a/waf_configuration_problem/">[comments]</a></span>

## File System Structure for Self Hosted Applications
 - [https://www.reddit.com/r/selfhosted/comments/1gtg5yp/file_system_structure_for_self_hosted_applications](https://www.reddit.com/r/selfhosted/comments/1gtg5yp/file_system_structure_for_self_hosted_applications)
 - RSS feed: $source
 - date published: 2024-11-17T15:38:07+00:00

<!-- SC_OFF --><div class="md"><p>Let&#39;s say <em>hypothetically</em> someone was working on a file storage application, think Nextcloud but leaner, not purely file storage, but collaboration and all. How much do you guys value having the system mimic the folders and file structure on the filesystem itself. Let me elaborate.</p> <p>Currently, all the tree logic for the files is in the database, this is what Nextcloud and other apps do as well. But instead of also maintaining the correct tree on the filesystem we just store it in our own rigid way (like Immich does). The benefits of this are numerous. </p> <p>- Performs better? Untested really but I&#39;m fairly certain the normalized one would do better with more files<br/> - More reliable since we don&#39;t have to deal with conflicting file naming restrictions from multiple different client machines running different OS&#39;s<br/> - Allows us to easily support multiple backends. Can simply replace the filepath with an S3 link for

## No sleep for Linux on a MacBook
 - [https://www.reddit.com/r/selfhosted/comments/1gtg2ca/no_sleep_for_linux_on_a_macbook](https://www.reddit.com/r/selfhosted/comments/1gtg2ca/no_sleep_for_linux_on_a_macbook)
 - RSS feed: $source
 - date published: 2024-11-17T15:33:26+00:00

<!-- SC_OFF --><div class="md"><p>I’m trying to repurpose an old MacBook as a server, but no matter what I do it sleeps when I close the lid. </p> <p>Currently running Mint (dual booted beside MacOS), with Xfce desktop - open to changing distro if necessary, but ideally Debian flavoured. </p> <p>I have tried setting System Settings &gt; Power Options &gt; On Charger &gt; “Desired action when closing the lid” to “do nothing”, but still a couple of minutes after closing the lid it stops responding to network traffic. </p> <p>Any tips for making laptops behave? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ServoSloth"> /u/ServoSloth </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtg2ca/no_sleep_for_linux_on_a_macbook/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtg2ca/no_sleep_for_linux_on_a_macbook/">[comments]</a></span>

## Streaming Netflix to Localhost
 - [https://www.reddit.com/r/selfhosted/comments/1gtfefw/streaming_netflix_to_localhost](https://www.reddit.com/r/selfhosted/comments/1gtfefw/streaming_netflix_to_localhost)
 - RSS feed: $source
 - date published: 2024-11-17T15:02:39+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m aware of the typical arrstack + Jellyfin/Plex setup for personal streaming, and I&#39;m using it too. However, I have a specific question:</p> <p><strong>Can I stream Netflix to a localhost address?</strong></p> <p>Here&#39;s the issue: my wife&#39;s work laptop blocks sites like Netflix, YouTube, Spotify, etc., but it doesn’t block localhost pages (e.g., 192.168.x.x). Installing Kodi (or similar software) on her work laptop isn’t an option, and I know there used to be a Netflix plugin for Kodi. I thought about running a simple Windows/Debian VM with a browser for Netflix, but that doesn&#39;t feels right.</p> <p>Any better ideas or solutions? Also, let me know if there’s another community to crosspost?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gargdada"> /u/gargdada </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtfefw/streaming_netflix_to_localhost/">[link]</a></span> &#3

## Memos, alternative of Rewind. A Privacy-Focused Passive Recording Project.
 - [https://www.reddit.com/r/selfhosted/comments/1gteydp/memos_alternative_of_rewind_a_privacyfocused](https://www.reddit.com/r/selfhosted/comments/1gteydp/memos_alternative_of_rewind_a_privacyfocused)
 - RSS feed: $source
 - date published: 2024-11-17T14:40:52+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gteydp/memos_alternative_of_rewind_a_privacyfocused/"> <img src="https://external-preview.redd.it/agKhLPOmle0MbZW8_htLobYr3763qVIN_cM-nGh604I.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=e64514abbe6b4d56996b8b6b443c7c41e0f97062" alt="Memos, alternative of Rewind. A Privacy-Focused Passive Recording Project." title="Memos, alternative of Rewind. A Privacy-Focused Passive Recording Project." /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I&#39;m excited to introduce you to <a href="https://github.com/arkohut/memos">Memos</a>, a new project designed for those who value privacy and data control. Memos is a passive recording tool that automatically captures screen content, builds intelligent indices, and provides a user-friendly web interface for retrieving historical records.</p> <p>Unlike other similar projects, Memos gives you complete control over your data, avoiding the need to send it to untrusted data 

## Synching an album between Apple and google
 - [https://www.reddit.com/r/selfhosted/comments/1gtexxq/synching_an_album_between_apple_and_google](https://www.reddit.com/r/selfhosted/comments/1gtexxq/synching_an_album_between_apple_and_google)
 - RSS feed: $source
 - date published: 2024-11-17T14:40:14+00:00

<!-- SC_OFF --><div class="md"><p>Hey friends. Ok so here&#39;s the situation: I&#39;m an Apple user. My partner is an android user. </p> <p>We just had a baby, and we&#39;d like to sync a baby photos album together somehow. </p> <p>I have a full k8s cluster so I have a ton of options on what I can do. But I don&#39;t really want to overcomplicate it. I&#39;m happy on Apple photos. </p> <p>Ideally just some kind of sync tool (even if it&#39;s just a cronjob type solution)</p> <p>What I&#39;m thinking: I have a share in my unraid set up. Then some kind of tool that can maintain a local album on my phone synced with that share, and then an equal app on my partners Samsung device. </p> <p>I feel like this exists but I&#39;m sleeping like an hour or two at a go rn so not so brain. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/4kidsinatrenchcoat"> /u/4kidsinatrenchcoat </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtexxq/

## Host .txt file and load from python script
 - [https://www.reddit.com/r/selfhosted/comments/1gtd8q1/host_txt_file_and_load_from_python_script](https://www.reddit.com/r/selfhosted/comments/1gtd8q1/host_txt_file_and_load_from_python_script)
 - RSS feed: $source
 - date published: 2024-11-17T13:11:45+00:00

<!-- SC_OFF --><div class="md"><p>First of all, I hope this is allowed here, since I have no idea where to go with this.</p> <p>Second of all, I&#39;m not even sure if I&#39;m asking the right questions, since I&#39;m new to HTML.</p> <p>As a surprise, I made a python script and I want to host it to a webpage so I can generate a qr code. On the webpage, there should be the script, as if it were a python interpreter, but not editable. In the script, I want to refer to a .txt file that will be printed after they click &#39;run&#39;. (As well as other text, but thats just stored in the code). </p> <p>How do I host this script and the html locally? Do they have to be on different ports? What do I do???</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/throwaway3058201842"> /u/throwaway3058201842 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtd8q1/host_txt_file_and_load_from_python_script/">[link]</a></span> &#32; <span><a hr

## Need to host a node js server online
 - [https://www.reddit.com/r/selfhosted/comments/1gtd3ie/need_to_host_a_node_js_server_online](https://www.reddit.com/r/selfhosted/comments/1gtd3ie/need_to_host_a_node_js_server_online)
 - RSS feed: $source
 - date published: 2024-11-17T13:03:30+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, I have a node js server which I need to host online. I don&#39;t really want to buy a domain name. I was using ngrok for development on the free tier. Is it possible to use ngrok even for production without down time? I don&#39;t mind restarting the server once a day if there&#39;s any limit. I couldn&#39;t find any such limits mentioned in their documentation or pricing page. Do you guys have any idea?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cyber5234"> /u/cyber5234 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtd3ie/need_to_host_a_node_js_server_online/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtd3ie/need_to_host_a_node_js_server_online/">[comments]</a></span>

## Searching for a Multimedia Portainer Stack with VPN Integration
 - [https://www.reddit.com/r/selfhosted/comments/1gtd0zn/searching_for_a_multimedia_portainer_stack_with](https://www.reddit.com/r/selfhosted/comments/1gtd0zn/searching_for_a_multimedia_portainer_stack_with)
 - RSS feed: $source
 - date published: 2024-11-17T12:59:48+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a functional Portainer stack setup that includes all the multimedia containers I need under one network, specifically: Sonarr, Radarr, Bazarr, Lidarr, Prowlarr, qBittorrent, Jellyfin (and eventually Readarr and Mylar3). Additionally, I use a VPN with Windscribe, will I be able to integrate it with this setup?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/wa_00"> /u/wa_00 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtd0zn/searching_for_a_multimedia_portainer_stack_with/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtd0zn/searching_for_a_multimedia_portainer_stack_with/">[comments]</a></span>

## Using Caddy on LAN behind CGNAT
 - [https://www.reddit.com/r/selfhosted/comments/1gtchvf/using_caddy_on_lan_behind_cgnat](https://www.reddit.com/r/selfhosted/comments/1gtchvf/using_caddy_on_lan_behind_cgnat)
 - RSS feed: $source
 - date published: 2024-11-17T12:28:00+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I&#39;m trying to use get hostname and https access to self-hosted services on my LAN, which is behind a CGNAT. I have OPNSense and have tried Caddy plugin on it.</p> <p>Motivation for this is for my family to be able to access Jellyfin, Immich, etc. seamlessly whether they are on LAN or outside. I currently use Cloudflare tunnels to access (e.g. <a href="https://immich.mydomain.com">https://immich.mydomain.com</a>). But Cloudflare retricts the bandwidth such that big videos will never upload properly. So I want access to Immich via the same address and https to reach my server on LAN without ever reaching Cloudflare tunnels.</p> <p>I tried configuring a DNS override and Caddy on OPNSense to reverse proxy <a href="https://immich.mydomain.com">https://immich.mydomain.com</a> to the server on LAN. But it does not seem to work due to the CGNAT. I can&#39;t create a A record that points to the OPNSense machine as it does not have an a

## What can I replace this with?
 - [https://www.reddit.com/r/selfhosted/comments/1gtc1dv/what_can_i_replace_this_with](https://www.reddit.com/r/selfhosted/comments/1gtc1dv/what_can_i_replace_this_with)
 - RSS feed: $source
 - date published: 2024-11-17T11:58:30+00:00

<!-- SC_OFF --><div class="md"><p>I’m looking at moving away from windows machine. </p> <p>Most of my stuff now is docker hosted on an Ubuntu machine. </p> <p>I have a couple services left that I’d like to replace if there is a decent alternative out there. Ideally docker based. </p> <p>First - </p> <p>My Active Directory server. I no longer need a directory server but it is hosting my DNS for internal name resolution. </p> <p>Is there a docker service out there, ideally with a web gui for management that can host as my internal dns? Not a deal breaker but would be great if it could support replication to another copy in another container so I can have two dns servers in sync. </p> <p>Second - </p> <p>CA. I have a windows CA that I use for all my internal services to create my certificates and then upload these to my NGINX proxy manager container for my internal services so I can have https internally and not get certificate warnings. The root cert is then distributed to all my devic

## Another "What should I host" question but with a slight twist
 - [https://www.reddit.com/r/selfhosted/comments/1gtbgmr/another_what_should_i_host_question_but_with_a](https://www.reddit.com/r/selfhosted/comments/1gtbgmr/another_what_should_i_host_question_but_with_a)
 - RSS feed: $source
 - date published: 2024-11-17T11:18:44+00:00

<!-- SC_OFF --><div class="md"><p>I have a number of self hosted things going on - I&#39;m not new to looking at awesomeselfhosted of searching this subreddit. However I have two machines with GPUs in them - an i5 PC running Ubuntu which currently runs Immich and a QNAP TS873A which runs Plex.</p> <p>When I&#39;m not uploading photos or watching something that needs transcoding these GPUs sit idle. So I&#39;m looking for something else I can do with the GPUs while they&#39;re idle.</p> <p>I also have another machine that runs Frigate with a TPU and I have no interest in crypto mining, just to rule those out. </p> <p>So my question - is anyone running a preferably dockerised service that uses a GPU in an interesting way or do I just have to settle for transcoding and identifying cats?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/stetho"> /u/stetho </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtbgmr/another_what_shoul

## How can I access my home server remotely?
 - [https://www.reddit.com/r/selfhosted/comments/1gtb1q6/how_can_i_access_my_home_server_remotely](https://www.reddit.com/r/selfhosted/comments/1gtb1q6/how_can_i_access_my_home_server_remotely)
 - RSS feed: $source
 - date published: 2024-11-17T10:48:43+00:00

<!-- SC_OFF --><div class="md"><p>I am setting up an old computer I have as a home lab I’m planning on using proxmox, </p> <p>Services: </p> <p>Plex Minecraft Server Remote File Storage</p> <p>My question is how do I go about setting up remote access to these services? If it makes a difference currently my network is setup with ATT fiber some specifics on how to configure their modem to work with my needs would be great.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/browndude4"> /u/browndude4 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtb1q6/how_can_i_access_my_home_server_remotely/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtb1q6/how_can_i_access_my_home_server_remotely/">[comments]</a></span>

## Stashapp generated files
 - [https://www.reddit.com/r/selfhosted/comments/1gtawss/stashapp_generated_files](https://www.reddit.com/r/selfhosted/comments/1gtawss/stashapp_generated_files)
 - RSS feed: $source
 - date published: 2024-11-17T10:38:12+00:00

<!-- SC_OFF --><div class="md"><p>Hi! First of all, thank you☺️ I have a question regarding the generating proccess.</p> <p>I started with a stashserver at home, where my generated content was about 2.5 gb, for all my files. I then moved on to hosting my server from a seedbox, but when I generated my conted this time, I get a folder size abou 159 gb😬 And as far as I see, the settings look the same. Also the generated files in the screenshot folder, are mostly mp4, not webp, like in my first server🤔</p> <p>Any help would be appreciated! I just want my scenes to preview the video when my mouse is over it, and scene scrubbing, thats it. But when the preview files are almost the same as the original files, something must be off😅</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Born_Refrigerator340"> /u/Born_Refrigerator340 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtawss/stashapp_generated_files/">[link]</a></span> &#32;

## How secure is Traffic Routing into another VPS?
 - [https://www.reddit.com/r/selfhosted/comments/1gtaqec/how_secure_is_traffic_routing_into_another_vps](https://www.reddit.com/r/selfhosted/comments/1gtaqec/how_secure_is_traffic_routing_into_another_vps)
 - RSS feed: $source
 - date published: 2024-11-17T10:24:54+00:00

<!-- SC_OFF --><div class="md"><p>Got myself a server but I cant Port forward anything because I dont have access to the Router, I searched a method what would best work for my case because I dont want just friends accessing my server lets say i want a official gaming Server</p> <p>Could I just Route the Traffic going to a official vps through ssh tunnel and open the Ports from there? And how secure is that?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ChaosKiller1258"> /u/ChaosKiller1258 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtaqec/how_secure_is_traffic_routing_into_another_vps/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gtaqec/how_secure_is_traffic_routing_into_another_vps/">[comments]</a></span>

## TailScale and VPN issues
 - [https://www.reddit.com/r/selfhosted/comments/1gtan4x/tailscale_and_vpn_issues](https://www.reddit.com/r/selfhosted/comments/1gtan4x/tailscale_and_vpn_issues)
 - RSS feed: $source
 - date published: 2024-11-17T10:18:09+00:00

<!-- SC_OFF --><div class="md"><p>Hi there! I hope this is the right place for this. I am running an optiplex micro on windows 11 for my own Plex server. I initially ran a VPN on everything but then plex remote access stopped working so I used the split tunnelling feature to exclude plex which worked fine. However now I want remote access to the arrs from wherever I am so I thought I’d use TailScale which seemed like a good solution. When the VPN is off, it works perfect. However when the VPN is on, it doesn’t work. I’ve tried excluding TailScale but it doesn’t seem to work like Plex, and when I try to use route through vpn, Jackett doesn’t work so either way it ends up broken. None of these are in dockers (I know I know) due to lack of knowledge, so I am wondering how I could get TailScale to work. One of my ideas was run just TailScale in docker desktop to try and avoid the vpn? Any advice would be greatly appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="http

## Most reliable commandline way to stream videos to YouTube?
 - [https://www.reddit.com/r/selfhosted/comments/1gtalbd/most_reliable_commandline_way_to_stream_videos_to](https://www.reddit.com/r/selfhosted/comments/1gtalbd/most_reliable_commandline_way_to_stream_videos_to)
 - RSS feed: $source
 - date published: 2024-11-17T10:14:28+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to stream a playlist of videos to YouTube from server OS. I tried ffmpeg and medianmx with ffmpeg with the command:</p> <p><code>bash ffmpeg \ -stream_loop -1 -re -i playlist.txt \ -fflags +igndts \ -c:a aac -ac 2 -b:a 128k -ar 44100 \ -c:v libx264 -preset ultrafast -b:v 6M -maxrate 6M -bufsize 12M \ -r 30 -g 60 \ -f flv -flvflags no_duration_filesize -rtmp_buffer 3000 \ -restart_with_keyframe 1 -attempt_recovery 1 -recovery_wait_time 2 \ rtemp://server.com/stream-key </code></p> <p>the stream starts sometimes and sometimes not, I have to stop ffmpeg and restart until it&#39;s catched, usually it happens one time. However my biggest problem is that the stream stops after a couple of hours, it&#39;s not reliable for long term. Is there anything I can do to make it reliable? Maybe use another server?</p> <p>And I&#39;ve tried <code>-f fifo -fifo_format flv</code> but it doesn&#39;t work.</p> </div><!-- SC_ON --> &#32; submitted by &#32; 

## Best online cloud to save backups?
 - [https://www.reddit.com/r/selfhosted/comments/1gta5xn/best_online_cloud_to_save_backups](https://www.reddit.com/r/selfhosted/comments/1gta5xn/best_online_cloud_to_save_backups)
 - RSS feed: $source
 - date published: 2024-11-17T09:43:19+00:00

<!-- SC_OFF --><div class="md"><p>I am adopting the 3-2-1 backup strategy and would like to save all my photos in an encrypted manner on an online cloud, but one that is not overly expensive and is reliable.</p> <p>What do you guys use?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/abbondanzio"> /u/abbondanzio </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gta5xn/best_online_cloud_to_save_backups/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gta5xn/best_online_cloud_to_save_backups/">[comments]</a></span>

## Streamsphere
 - [https://www.reddit.com/r/selfhosted/comments/1gt9kog/streamsphere](https://www.reddit.com/r/selfhosted/comments/1gt9kog/streamsphere)
 - RSS feed: $source
 - date published: 2024-11-17T08:58:21+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gt9kog/streamsphere/"> <img src="https://external-preview.redd.it/qQx_wXXHsH3sFUdZbGQ2fZfhRd_eHuTIAqGi32V3HtI.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=d2e3063955f12d0be6bf790591e522a0705b4834" alt="Streamsphere" title="Streamsphere" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello everyone!</p> <p>I&#39;m the developer of Streamsphere, a download manager, fully self-hostable.</p> <p>It uses yt-dlp as downloader.</p> <p>The technology stack is Angular + Golang. The effort is to have as low resource utilization as possible.</p> <p><a href="https://github.com/rs-anantmishra/streamsphere">https://github.com/rs-anantmishra/streamsphere</a></p> <p>I&#39;d like to have the feedback of this awesome community on the first pre-release of this self-hosted application.</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/am_streamsphere"> /u/am_streamsphere </

## Need inspiration
 - [https://www.reddit.com/r/selfhosted/comments/1gt93ip/need_inspiration](https://www.reddit.com/r/selfhosted/comments/1gt93ip/need_inspiration)
 - RSS feed: $source
 - date published: 2024-11-17T08:21:54+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>So I have an HP Elitedesk 800 G4 with an i5-8500, 16GB DDR4 ram and 256GB SSD M.2 storage, I also have a 2TB external SSD laying around I could use for it.</p> <p>This used to be my main server, recently I built a new server which runs all my current services, so I need ideas for what I could use my old Elitedesk for! </p> <p>My main server currently runs a bunch of different services:</p> <p>- AdGuard Home<br/> - Glances<br/> - Gluetun<br/> - MySpeed<br/> - Plex<br/> - Tautulli<br/> - Qbit<br/> - Overseerr<br/> - Arr*<br/> - MeTube<br/> - Cockpit<br/> - Scrutiny<br/> - WatchTower<br/> - Portainer<br/> - NextCloud</p> <p>I&#39;m contemplating installing something like proxmox on the Elitedesk to play around with VMs, but I&#39;m open to suggestions on what it could be used for, it would be sad for it to just collect dust.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Adventurous-Ant6731"> /u/Adve

## SSL Errors when Accessing Cloudflare Sites through Wireguard VPN
 - [https://www.reddit.com/r/selfhosted/comments/1gt8nwi/ssl_errors_when_accessing_cloudflare_sites](https://www.reddit.com/r/selfhosted/comments/1gt8nwi/ssl_errors_when_accessing_cloudflare_sites)
 - RSS feed: $source
 - date published: 2024-11-17T07:50:20+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m running Pi-hole, PiVPN, and Unbound on an ARM Compute Instance from Oracle Cloud. My client is a Windows machine behind CGNAT. When connected to PiVPN, I&#39;m experiencing issues accessing websites that are hosted behind Cloudflare (e.g., <a href="https://chatgpt.com/">ChatGPT</a>, <a href="https://claude.ai/">Claude AI</a>, <a href="https://www.pluralsight.com/">Pluralsight</a>). On Chromium-based browsers, these websites return either <code>ERR_SSL_PROTOCOL_ERROR</code> or <code>ERR_QUIC_PROTOCOL_ERROR</code>. On Firefox and its forks, the same websites return <code>SSL_ERROR_RX_MALFORMED_SERVER_HELLO</code>.</p> <p>In my attempt to diagnose the root cause of this issue, I uninstalled Pi-hole, PiVPN, and Unbound completely. Then I used <a href="https://github.com/Nyr/wireguard-install">wireguard-install</a> to create a Wireguard server. After connecting to the server, I tried to access those websites, but they all returned the same error. 

## Hows my homepage?
 - [https://www.reddit.com/r/selfhosted/comments/1gt85nn/hows_my_homepage](https://www.reddit.com/r/selfhosted/comments/1gt85nn/hows_my_homepage)
 - RSS feed: $source
 - date published: 2024-11-17T07:13:22+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gt85nn/hows_my_homepage/"> <img src="https://preview.redd.it/zzu3t2slwe1e1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=600eaa0115f2c9d048c97dfba4f8d837967c4ab9" alt="Hows my homepage?" title="Hows my homepage?" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/VizeKarma"> /u/VizeKarma </a> <br/> <span><a href="https://i.redd.it/zzu3t2slwe1e1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gt85nn/hows_my_homepage/">[comments]</a></span> </td></tr></table>

## Community Discussion Project
 - [https://www.reddit.com/r/selfhosted/comments/1gt7rht/community_discussion_project](https://www.reddit.com/r/selfhosted/comments/1gt7rht/community_discussion_project)
 - RSS feed: $source
 - date published: 2024-11-17T06:45:32+00:00

<!-- SC_OFF --><div class="md"><p>I hope this is the right place and the right audience. Reading a <a href="https://www.reddit.com/r/selfhosted/comments/1gow9jb/launched_my_side_project_on_a_selfhosted_m1_mac/">recent post</a> has inspired me to take this challenge on myself. Especially the user comments on how OP the hardware was. The following is the project.</p> <p>For a long time I have wanted to setup an interactive community site for professionals as a sister siite to <a href="https://community.f5.com/">https://community.f5.com/</a> which is run on the khoros community platform with centralised sso authentication. Originally was planning to leverage with web interface of <a href="http://discord.com/app">discord.com/app</a> as it is accessible from anywhere in the world without having to load any software. However some serious limitations around how it can be utilised have been preventing me from doing so. So that brings me to my project. </p> <p>Step 1.<br/> Deploy an interacti

## Where are you hosting your 500Gb+ photos?
 - [https://www.reddit.com/r/selfhosted/comments/1gt7apu/where_are_you_hosting_your_500gb_photos](https://www.reddit.com/r/selfhosted/comments/1gt7apu/where_are_you_hosting_your_500gb_photos)
 - RSS feed: $source
 - date published: 2024-11-17T06:12:35+00:00

<!-- SC_OFF --><div class="md"><p>This started as an experiment and I&#39;ve been happily using my old laptop to host Nextcloud and sync my photos. Now the risk of losing it is giving me a bit of anxiety. What is the best option to put this in the cloud? All 1TB SSDs cost me a bomb. I&#39;ve seen Hetzner, Hosting.de, etc but all are costly. Please suggest a way I can have all this data on the cloud or may be another safe place. Btw, I do backup the data on external HDD using borg. Thank you.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/prinkpan"> /u/prinkpan </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gt7apu/where_are_you_hosting_your_500gb_photos/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gt7apu/where_are_you_hosting_your_500gb_photos/">[comments]</a></span>

## Docker shlink and Web client
 - [https://www.reddit.com/r/selfhosted/comments/1gt5g4c/docker_shlink_and_web_client](https://www.reddit.com/r/selfhosted/comments/1gt5g4c/docker_shlink_and_web_client)
 - RSS feed: $source
 - date published: 2024-11-17T04:16:57+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve set up shlink, everything works 100% correct, the creation and access of the short links works from WAN, and LAN, </p> <p>I cannot access the shlink server using the Web app from outside the LAN or WAN, been 1-2 days, and my guess is that it is not supposed to be access from WAN since it doesn&#39;t have a password.</p> <p>from LAN I can access the server using the IP:port and domain <a href="http://example.com">example.com</a></p> <p>From WAN or outside LAN, I cannot access the server</p> <p>Can some one confirm, I couldn&#39;t find documentation.</p> <pre><code>services: shlink: image: shlinkio/shlink:stable container_name: shlink restart: always environment: - DEFAULT_DOMAIN=mio.tuyo.com - IS_HTTPS_ENABLED=true - GEOLITE_LICENSE_KEY= - INITIAL_API_KEY= - DB_DRIVER=maria - DB_USER= - DB_NAME= - DB_PASSWORD= - DB_HOST= - MULTI_SEGMENT_SLUGS_ENABLED=true - SHORT_URL_TRAILING_SLASH=true depends_on: - database ports: - 8097:8080 database: imag

## Is there something I can do in Jitsi Meet so that every URL is not a Meeting Room?
 - [https://www.reddit.com/r/selfhosted/comments/1gt57va/is_there_something_i_can_do_in_jitsi_meet_so_that](https://www.reddit.com/r/selfhosted/comments/1gt57va/is_there_something_i_can_do_in_jitsi_meet_so_that)
 - RSS feed: $source
 - date published: 2024-11-17T04:03:23+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m using a self-hosted instance of Jitsi Meet. For starting a meeting as a host, I&#39;m using authorization via Prosody and then I let anyone with the link join, but if you go to any Jitsi URL, it&#39;s technically a Meeting Room which I find really weird. At present what I do is have nginx return a 404 on the other pages but it&#39;s a pain to edit the config every time.</p> <p>I also dislike the randomly generated meeting names like BubbleteaSippingLizard and would&#39;ve just preferred a randomly-generated string like how Zoom does.</p> <p>I&#39;m adding the meeting to my Caldav calendar also manually which would&#39;ve been nice if I could&#39;ve done directly from Jitsi but this isn&#39;t very high priority for now.</p> <p>Is any of this configurable or will I have to fork it myself? I was thinking I can&#39;t be the only one feeling this annoyance so maybe a fork already exists?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="h

## Scraperr v1.0.3 - Asked for Features
 - [https://www.reddit.com/r/selfhosted/comments/1gt4b07/scraperr_v103_asked_for_features](https://www.reddit.com/r/selfhosted/comments/1gt4b07/scraperr_v103_asked_for_features)
 - RSS feed: $source
 - date published: 2024-11-17T03:10:50+00:00

<!-- SC_OFF --><div class="md"><p>Finally got a few things worthy of posting about added to Scraperr, the self-hosted webscraper.</p> <ol> <li>Removal of dependency of reverse proxy, which a lot of people didn&#39;t like</li> <li>Ability to proxy requests through a list of comma separated proxies</li> <li>Ability to do actions like click on a button or type something into an input field</li> </ol> <p>Coming soon:<br/> - Flaresolverr support<br/> - Removal of MongoDB dependency (Switching to SQLite)<br/> - UI Overhaul?</p> <p><a href="https://github.com/jaypyles/Scraperr">https://github.com/jaypyles/Scraperr</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bluesanoo"> /u/bluesanoo </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gt4b07/scraperr_v103_asked_for_features/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gt4b07/scraperr_v103_asked_for_features/">[comments]</a></span>

## [Question] Automated dead man’s switch
 - [https://www.reddit.com/r/selfhosted/comments/1gt3jg2/question_automated_dead_mans_switch](https://www.reddit.com/r/selfhosted/comments/1gt3jg2/question_automated_dead_mans_switch)
 - RSS feed: $source
 - date published: 2024-11-17T02:28:37+00:00

<!-- SC_OFF --><div class="md"><p>Since we don’t have peacemakers that connect to WiFi (yet), how would <em>you</em> check if you are alive?</p> <p>I’ve been thinking on building a DMS but I know I’ll forget to check in eventually, so I wanted to automate this step</p> <p>I would probably ping google maps current location, maybe ping my phone (rarely it goes 24h without battery) or even check last activity online </p> <p>Now I’m curious, what would you check regularly to see if you are alive?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nicosbank"> /u/nicosbank </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gt3jg2/question_automated_dead_mans_switch/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gt3jg2/question_automated_dead_mans_switch/">[comments]</a></span>

## Get Smb shares over the internet
 - [https://www.reddit.com/r/selfhosted/comments/1gt38jm/get_smb_shares_over_the_internet](https://www.reddit.com/r/selfhosted/comments/1gt38jm/get_smb_shares_over_the_internet)
 - RSS feed: $source
 - date published: 2024-11-17T02:12:09+00:00

<!-- SC_OFF --><div class="md"><p>i have two 2TB drives running in raid 1 on my server. i was using it for photos and some miscellaneous storage but i also wanted to store school notes on it (pdf&#39;s and word documents). until now ive used tailscale to connect to it when im out and about. the only issue is my school wifi blocks tailscale and i have a 5GB limit on my mobile hotspot that i save for very specific scenarios. i do have Cloudflare tunnels setup and i do use them for things like metube, immich, and glances. i also know that port forwarding it is an awful idea. my only workaround so far has been to run file explorer and then run that through Cloudflare tunnels (since it uses a web gui) but the only issue with that is i cant directly interact with it on my latop(ex double clicking a pdf to open it). i know there is an option for smb in zero trust networks. i just have tried and failed at using it.</p> <p>side note i also need some help getting ssh over zero trust since curr

## confused- where to start
 - [https://www.reddit.com/r/selfhosted/comments/1gt2me1/confused_where_to_start](https://www.reddit.com/r/selfhosted/comments/1gt2me1/confused_where_to_start)
 - RSS feed: $source
 - date published: 2024-11-17T01:39:17+00:00

<!-- SC_OFF --><div class="md"><p>Hi gang, I am looking at all this post with lots of different gadgets and self hosted server/things(cause i don’t even know what it does - it on this nice stand and stuff). Currently I have Synology NAS and rasp pi zero and i am running some basic dockers like Arr’s , adguard home etc! </p> <p>I want to build a good setup now and see if i can improve anywhere.. not sure where to start.. looking for a guide or somewhere to start so that i can also have really cool setup which not only looks cool but does wonders!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sure-Bullfrog9776"> /u/Sure-Bullfrog9776 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gt2me1/confused_where_to_start/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gt2me1/confused_where_to_start/">[comments]</a></span>

## Verifying the security of my self-hosting setup
 - [https://www.reddit.com/r/selfhosted/comments/1gt2bc9/verifying_the_security_of_my_selfhosting_setup](https://www.reddit.com/r/selfhosted/comments/1gt2bc9/verifying_the_security_of_my_selfhosting_setup)
 - RSS feed: $source
 - date published: 2024-11-17T01:23:17+00:00

<!-- SC_OFF --><div class="md"><p>Hey yall,</p> <p>Been getting started on my self-hosting journey and am having a great time. So far, I have a Always-Free OCI VM (a 4 vCPU, 24GB ubuntu 24.04) instance, and am self-hosting the following on my personal domain:</p> <ul> <li><p>13ft</p></li> <li><p>Linkwarden</p></li> <li><p>Actual</p></li> <li><p>Immich</p></li> <li><p>have the Datadog agent with their OCI integration to monitor everything about my infra there. </p></li> </ul> <p>Everything is working great and loving how it&#39;s all been free.</p> <p>I&#39;m a bit rusty in terms of my networking, and wanted to ensure my setup is as secure as can be, especially as I&#39;m exposing these services to the open internet, although the apps are login-walled (i.e. you can go to `linkwarden.my-domain.tld` for example and be greeted with the login page).</p> <h2>Setup</h2> <h3>In OCI</h3> <ul> <li>In the Security List of the VCN that my instance is in, I have the following rules:</li> </ul> <t

## Unable to Access Reverse Proxy Via Windows (Edge, Brave)
 - [https://www.reddit.com/r/selfhosted/comments/1gt13xw/unable_to_access_reverse_proxy_via_windows_edge](https://www.reddit.com/r/selfhosted/comments/1gt13xw/unable_to_access_reverse_proxy_via_windows_edge)
 - RSS feed: $source
 - date published: 2024-11-17T00:22:37+00:00

<!-- SC_OFF --><div class="md"><p>Background: I have several docker containers running on my Synology DS1821+ which is, in turn, on my Tailscale tailnet. I have an NGINX Proxy Manager (NPM) container as a Tailscale sidecar, and a domain at Cloudflare pointed to the NPM tailnet IP address. With this configuration, I use NPM as a reverse proxy to access the rest of my containers at <a href="https://container.mydomain.net">https://container.mydomain.net</a> with SSL and HSTS provided by NPM.</p> <p>On all of my Apple devices, I haven&#39;t had any issues accessing the containers via the domain name (<a href="https://container.mydomain.net">https://container.mydomain.net</a>) on multiple browsers (Safari, Brave, Orion); however, with Windows 11, I can&#39;t access these domains via browser (either via Edge or Brave) or pinging/tracert (via a command prompt). I <em>can</em> access them via the MagicDNS name of my Synology followed by the port number (e.g., http://nas:3550)</p> <p>I&#39;ve

## Can Jellyfin display shows and movies that I don't have like Plex does?
 - [https://www.reddit.com/r/selfhosted/comments/1gt13ns/can_jellyfin_display_shows_and_movies_that_i_dont](https://www.reddit.com/r/selfhosted/comments/1gt13ns/can_jellyfin_display_shows_and_movies_that_i_dont)
 - RSS feed: $source
 - date published: 2024-11-17T00:22:12+00:00

<!-- SC_OFF --><div class="md"><p>I wanted to post this in Jellyfin subreddit, but it&#39;s locked so I am posting it here. Basically, Plex can show all the movies and TV shows an actor was part of regardless of whether we have the media on our device or not. Can Jellyfin also do the same? I am not sure if it can and if yes, then how to turn it on? On Jellyfin, when I open any cast member, I can only see the shows and movies that the actor was part of for the media that I own only. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ProfessorS11"> /u/ProfessorS11 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gt13ns/can_jellyfin_display_shows_and_movies_that_i_dont/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gt13ns/can_jellyfin_display_shows_and_movies_that_i_dont/">[comments]</a></span>

