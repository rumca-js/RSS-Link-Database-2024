# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Recent trouble accessing NGINX proxies over LAN.
 - [https://www.reddit.com/r/selfhosted/comments/1c0ydro/recent_trouble_accessing_nginx_proxies_over_lan](https://www.reddit.com/r/selfhosted/comments/1c0ydro/recent_trouble_accessing_nginx_proxies_over_lan)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T22:19:09+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, hoping to get some help on recent trouble I've been having accessing my addresses set up in NGINX proxy manager over LAN. </p> <p>I initially set up NPM and a few docker containers (authelia, homepage, uptime-kuma, guacamole etc) and had them all getting accessed both over LAN and external networks by accessing the *.domain.duckdns.org addresses. All I did was forward my ports for NPM and it worked both internally and externally! Woohoo</p> <p>However after I wanted to install Immich and get all my photos off Google, it all started to go a bit haywire. I think cause I was trying to download 250GB of photos all at once my connection crapped itself. After that I wasnt able to access any of my apps through NPM at all. </p> <p>So I decided to uninstall NPM completely and start again. All my docker containers where still accessible from the internal IP and port number. However after I set the addresses back up I am only able to access them on an ex

## Jellyfin reverse proxy via nginx - works internally, not externally
 - [https://www.reddit.com/r/selfhosted/comments/1c0y9c8/jellyfin_reverse_proxy_via_nginx_works_internally](https://www.reddit.com/r/selfhosted/comments/1c0y9c8/jellyfin_reverse_proxy_via_nginx_works_internally)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T22:14:00+00:00

<!-- SC_OFF --><div class="md"><p>I have a domain, we'll call it mydomain.com, which I own. I've got a Jellyfin server (jellyfin.mydomain.com) set up on a Debian server, as well as an nginx proxy (proxy.mydomain.com) set up on an Alpine server. I use the mydomain.com domain internally and externally. Internally, stream.mydomain.com points directly to proxy.mydomain.com and everything works fine. Externally, stream.mydomain.com points to my static IP that belongs to my router. Traffic on 443 is forwarded from the router to proxy.mydomain.com's internal IP. This proxy has other aliases that work fine. Everything is using Let's Encrypt certs happily. However, if I use the Android app externally, it fails to connect. Strangely, in the browser, I do get redirected from <a href="https://stream.mydomain.com">https://stream.mydomain.com</a> to <a href="https://stream.mydomain.com/web/index.html#!/selectserver.html">https://stream.mydomain.com/web/index.html#!/selectserver.html</a> , but it ju

## Advice on configuring storage server
 - [https://www.reddit.com/r/selfhosted/comments/1c0xoa2/advice_on_configuring_storage_server](https://www.reddit.com/r/selfhosted/comments/1c0xoa2/advice_on_configuring_storage_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T21:50:23+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone!</p> <p>I’m optimizing my server setup by separating storage from compute tasks and introducing redundancy with RAIDZ. I plan to use the following specs for a dedicated storage server:</p> <ul> <li>Motherboard: ASRock N3700M</li> <li>CPU: Intel N3700</li> <li>RAM: 8GB (2x 4GB Kingston HyperX)</li> </ul> <p>I’ll likely purchase high-capacity HDDs for TrueNAS Scale to store non-speed-critical files, while keeping a few high-speed storage options on my main server with backups on this storage server.</p> <p>The motherboard’s limitation is its 2 SATA ports and minimal PCIe slots (1 x16 and 2 x1). I'm considering adding two PCIe x1 SATA cards and using the x16 slot for SSD/NVMe storage expansion. The SSDs would be used for storing the OS and potentially cache.</p> <p><strong>Questions</strong>:</p> <ol> <li>Is this setup practical?</li> <li>Should I add SSD cache?</li> <li>Any potential pitfalls or tips?</li> </ol> <p>Thanks for your help!</p> 

## Remote alternative to Kodi + Addons (Trakt Sync)
 - [https://www.reddit.com/r/selfhosted/comments/1c0wcxj/remote_alternative_to_kodi_addons_trakt_sync](https://www.reddit.com/r/selfhosted/comments/1c0wcxj/remote_alternative_to_kodi_addons_trakt_sync)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T20:56:35+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I'm running Kodi + Seren + Fen on a rp5 with HDMI to my TV and I love it.</p> <p>I want like a similar experience to it, but I haven't found a solution I like yet even though I looked through this and other subreddits.</p> <p>I tried this, but its not really it.</p> <p><a href="https://github.com/itsToggle/plex_debrid">https://github.com/itsToggle/plex_debrid</a></p> <p>Also tried this, but it also has no trakt sync.<br /> <a href="https://github.com/debridmediamanager/zurg-testing">https://github.com/debridmediamanager/zurg-testing</a></p> <p>&#x200b;</p> <p>I want to run it on my home Proxmox Server.</p> <p>Features I want:</p> <p>- Netflix like Interface (like Kodi with Arctic Horizon Skin provides)</p> <p>- Sync for Trakt watchlists, progress and maybe other lists</p> <p>- maybe compatiblity with an android app (doesnt have to be on play store if there are better solutions elsewhere)</p> <p>&#x200b;</p> <p>If I'm wrong and there are alr

## Ask for advice on some solution to manage users for several services
 - [https://www.reddit.com/r/selfhosted/comments/1c0wbn9/ask_for_advice_on_some_solution_to_manage_users](https://www.reddit.com/r/selfhosted/comments/1c0wbn9/ask_for_advice_on_some_solution_to_manage_users)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T20:55:06+00:00

<!-- SC_OFF --><div class="md"><p>Hello!</p> <h2>Preamble</h2> <p>I have a server where my small team works on some TTS-related projects. We have the following services:</p> <ul> <li>Nextcloud (for sharing files and uploading some training data);</li> <li>Gitea (for self-hosted source code storage and version control);</li> <li>MailCow (because we cannot use public email services sometimes);</li> <li>Regular Linux environment (because some tasks are not covered by automatic scripts and need to be done via command line).</li> </ul> <p>Also on another server we have some VPN solution because sometimes we need some kind of a local network to test some code which communicates between computers only in a local network.</p> <p>Of course all these services have no public registration process and I add every new account by hand.</p> <p>Recently one of us has left the team and two other guys have joined. Just imagine how it was to add their accounts for every service.</p> <h2>The main question

## Do you know of a self hosted bookmark search engine (like Historious)
 - [https://www.reddit.com/r/selfhosted/comments/1c0w3eh/do_you_know_of_a_self_hosted_bookmark_search](https://www.reddit.com/r/selfhosted/comments/1c0w3eh/do_you_know_of_a_self_hosted_bookmark_search)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T20:45:26+00:00

<!-- SC_OFF --><div class="md"><p>Do you know of a self-hosted version of something like <a href="https://historio.us">Historious</a>? Basically, a browser extension and simple API to save content to my own private search engine. It caches the full page as well, supports tags, and the browser extension uploads the page HTML (useful when the content is behind a paywall). If content is not uploaded, the server will crawl and capture the URL. I integrate it with my browser so it is a search engine from my address bar.</p> <p>It is the most useful tool I use ever day. I have no problem paying for it now. But I want to eventually move to something where I control and own the data.</p> <p>I plan to use Omnivore in tandem, but what I really need is that Google-like search. Any recommendations would be appreciated</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/charmingsum"> /u/charmingsum </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/co

## Would opnsense on a raspberry pi allow time based device blocking?
 - [https://www.reddit.com/r/selfhosted/comments/1c0vbdl/would_opnsense_on_a_raspberry_pi_allow_time_based](https://www.reddit.com/r/selfhosted/comments/1c0vbdl/would_opnsense_on_a_raspberry_pi_allow_time_based)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T20:13:56+00:00

<!-- SC_OFF --><div class="md"><p>I already have AdGuard home running in docker on a raspberry pi.</p> <p>I’m looking to block internet access for specific devices (google home devices) at set times of the day. Mainly so I can prevent my son with special needs (and apparently needs less sleep than me) from playing the theme from Ducktails before 5am on full volume from my google home speakers. My current solution has been to remove all smartspeakers… but I’d really like them back in use (just not at 5am).</p> <p>Is opnsense suitable for this or should I look to a different tool that I can run in docker on the pi?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/8bitMark"> /u/8bitMark </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0vbdl/would_opnsense_on_a_raspberry_pi_allow_time_based/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0vbdl/would_opnsense_on_a_raspberry_pi_allow_time_

## SearXNG behind Nginx Reverse Proxy
 - [https://www.reddit.com/r/selfhosted/comments/1c0uvny/searxng_behind_nginx_reverse_proxy](https://www.reddit.com/r/selfhosted/comments/1c0uvny/searxng_behind_nginx_reverse_proxy)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T19:56:46+00:00

<!-- SC_OFF --><div class="md"><p>I have a Nginx Reverse Proxy. I am targeting the server that has the SearXNG docker installed on it. I am using a base install. Here is the compose: <a href="https://pastebin.com/1e1MCsFb">https://pastebin.com/1e1MCsFb</a><br /> Is there a special custom setting I need in my Reverse Proxy? I searched the world of Google and found a link wanting me to use the nginx setup? Any ideas? </p> <p>&#x200b;</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/randomadhdman"> /u/randomadhdman </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0uvny/searxng_behind_nginx_reverse_proxy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0uvny/searxng_behind_nginx_reverse_proxy/">[comments]</a></span>

## Jellyfin adding unwanted artists?
 - [https://www.reddit.com/r/selfhosted/comments/1c0uf0o/jellyfin_adding_unwanted_artists](https://www.reddit.com/r/selfhosted/comments/1c0uf0o/jellyfin_adding_unwanted_artists)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T19:38:18+00:00

<!-- SC_OFF --><div class="md"><p>If this isn't allowed, please remove the post. The Jellyfin sub is locked, I didn't know where to go.</p> <p>I've given Jellyfin access to the music library I've painstakingly edited all of the Metadata for, only for it to add a few artists because they were featured on an album or a singular song. I don't want these artists to have their own tiles in my music library. I want to pretend theyve never existed. I have the entire discography of every artist, so it adding the featured artists totally throws off the &quot;complete&quot; vibe I'm going for. Please help. I've tried:</p> <p>Removing them from the songs' metadata in Jellyfin (they don't exist on the files' metadata)</p> <p>Deleting the random artists' folders in the \ProgramData\Jellyfin\Server\metadata folder</p> <p>Updating, scanning, and replacing all metadata</p> <p>Crying</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/J_Zolozabal"> /u/J_Zolozabal </a

## Wireless AP with Multi-SSID. pfSense is disregarding the VLAN tag
 - [https://www.reddit.com/r/selfhosted/comments/1c0u131/wireless_ap_with_multissid_pfsense_is](https://www.reddit.com/r/selfhosted/comments/1c0u131/wireless_ap_with_multissid_pfsense_is)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T19:22:34+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c0u131/wireless_ap_with_multissid_pfsense_is/"> <img alt="Wireless AP with Multi-SSID. pfSense is disregarding the VLAN tag" src="https://b.thumbs.redditmedia.com/Qni_bVQ1e9iT5I-3bjRv7PR90751MAFj57XISUpTPLk.jpg" title="Wireless AP with Multi-SSID. pfSense is disregarding the VLAN tag" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I'm not sure if the issue is with the access point or pfSense but.....</p> <p>I've had this working for the past year. But when I was trying to get Wireguard up and running, I did something that corrupted pfSense. I ended up needing to rebuild pfSense. When I did so, I had to reset the access point (TP-Link WA-901N). Then I configured three SSIDs with the appropriate VLAN tags.</p> <p>For some reason, the devices that are connected to the IoT network are still ending up in the LAN network (<a href="https://10.1.1.0/24">10.1.1.0/24</a>) instead of the IoT network.</p> <p>I've been fi

## Tụi cộng con, tay cầm xiaomi, chê đồ mỹ, yêu nước, lên tiktok cầm dt trung quốc đòi đảo online!
 - [https://www.reddit.com/r/selfhosted/comments/1c0t291/tụi_cộng_con_tay_cầm_xiaomi_chê_đồ_mỹ_yêu_nước](https://www.reddit.com/r/selfhosted/comments/1c0t291/tụi_cộng_con_tay_cầm_xiaomi_chê_đồ_mỹ_yêu_nước)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T18:43:10+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Square_Return_1284"> /u/Square_Return_1284 </a> <br /> <span><a href="/r/TroChuyenLinhTinh/comments/1c0gv7w/tụi_cộng_con_tay_cầm_xiaomi_chê_đồ_mỹ_yêu_nước/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0t291/tụi_cộng_con_tay_cầm_xiaomi_chê_đồ_mỹ_yêu_nước/">[comments]</a></span>

## VM software on top of an existing ubuntu
 - [https://www.reddit.com/r/selfhosted/comments/1c0swes/vm_software_on_top_of_an_existing_ubuntu](https://www.reddit.com/r/selfhosted/comments/1c0swes/vm_software_on_top_of_an_existing_ubuntu)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T18:36:46+00:00

<!-- SC_OFF --><div class="md"><p>Hey all this is a quick one.</p> <p>I have a server running a set of games. For a specific game, I need a windows machine.</p> <p>I don't want to buy another server for it and I can't wipe the existing game servers or stop them during the procedure.</p> <p>&#x200b;</p> <p>I'm thinking on installing vmware on the ubuntu and spinning up a windows VM inside. Is there any other software out there that would be recommended for this that I may be missing?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/naxhh"> /u/naxhh </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0swes/vm_software_on_top_of_an_existing_ubuntu/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0swes/vm_software_on_top_of_an_existing_ubuntu/">[comments]</a></span>

## ownCloud Infinite Scale on Raspberry 3+
 - [https://www.reddit.com/r/selfhosted/comments/1c0svtz/owncloud_infinite_scale_on_raspberry_3](https://www.reddit.com/r/selfhosted/comments/1c0svtz/owncloud_infinite_scale_on_raspberry_3)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T18:36:08+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c0svtz/owncloud_infinite_scale_on_raspberry_3/"> <img alt="ownCloud Infinite Scale on Raspberry 3+" src="https://external-preview.redd.it/Q_Dp1euxYUv76Ac5H45-Svyd2eGXDTyAzW8WU5dRYsQ.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=3a8329147f5f9fa2d7d13405dc67a5972496c940" title="ownCloud Infinite Scale on Raspberry 3+" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello, </p> <p>I'm actually trying to install ownCloud Inifinite Scale on my Raspberry 3+ following the official guide ( <a href="https://owncloud.com/news/howto-owncloud-infinite-scale-on-a-raspberry-pi/">https://owncloud.com/news/howto-owncloud-infinite-scale-on-a-raspberry-pi/</a>) </p> <p>I do exactly all they said but I'm blocked cause I get the error : <code>./ocis-4.0.7-linux-arm: 1: cannot open a: No such file</code></p> <p>&#x200b;</p> <p><a href="https://preview.redd.it/599d45qy4ptc1.png?width=834&amp;format=png&amp;auto=webp&amp;s=0b470f

## Don’t use Domain .com like me ugh
 - [https://www.reddit.com/r/selfhosted/comments/1c0sl5e/dont_use_domain_com_like_me_ugh](https://www.reddit.com/r/selfhosted/comments/1c0sl5e/dont_use_domain_com_like_me_ugh)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T18:24:09+00:00

<!-- SC_OFF --><div class="md"><p>I didn’t purchase their privacy protection, I have always used google domains but now that they’ve switched to square space I wasn’t sure I wanted to do that. Big mistake! 100s of spam calls over the past few days. I changed my phone number on my account and I’m hoping this helps.</p> <p>Any recommendations on who to register with when my 60 days are up?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dockside_gal"> /u/Dockside_gal </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0sl5e/dont_use_domain_com_like_me_ugh/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0sl5e/dont_use_domain_com_like_me_ugh/">[comments]</a></span>

## Better way to mount remote storage
 - [https://www.reddit.com/r/selfhosted/comments/1c0s5zu/better_way_to_mount_remote_storage](https://www.reddit.com/r/selfhosted/comments/1c0s5zu/better_way_to_mount_remote_storage)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T18:07:07+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c0s5zu/better_way_to_mount_remote_storage/"> <img alt="Better way to mount remote storage" src="https://b.thumbs.redditmedia.com/kpG8uke4ZEBy-ly917wLIFmPLur9sZuhb4aV2KgPzxs.jpg" title="Better way to mount remote storage" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi,</p> <p>below I have my basic (very basic) server structure. I was wondering if there is a better method to mount the remote storage to the VPS for better streaming performance. </p> <p>Navidrome running perfectly smooth even when streaming uncompressed .flac. But Audiobookshelf an Jellyfin can take quite some time to get the stream started. Once it's running, it's all fine (no buffering) as long as I don't want to skip ahead.</p> <p>The audio books are m4a I get from YouTube and .m4b converted from audible .aax files. The movies and tv shows are .mp4 and .mkv with some very old .avi (does anyone even use that anymore?) in all kinds of bit rat

## You speak french, want to set up Immich ?
 - [https://www.reddit.com/r/selfhosted/comments/1c0rhyh/you_speak_french_want_to_set_up_immich](https://www.reddit.com/r/selfhosted/comments/1c0rhyh/you_speak_french_want_to_set_up_immich)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T17:39:29+00:00

<!-- SC_OFF --><div class="md"><p>Give a look at <a href="https://www.k-sper.fr/index.php/2024/04/01/une-galerie-photo-immich/">https://www.k-sper.fr/index.php/2024/04/01/une-galerie-photo-immich/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Eirikr700"> /u/Eirikr700 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0rhyh/you_speak_french_want_to_set_up_immich/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0rhyh/you_speak_french_want_to_set_up_immich/">[comments]</a></span>

## Can't properly use Proxmox + Docker, need help fixing errors and loss of service
 - [https://www.reddit.com/r/selfhosted/comments/1c0r4bv/cant_properly_use_proxmox_docker_need_help_fixing](https://www.reddit.com/r/selfhosted/comments/1c0r4bv/cant_properly_use_proxmox_docker_need_help_fixing)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T17:23:34+00:00

<!-- SC_OFF --><div class="md"><p>Hey everybody, total noob here (and also, my first post - love the community!)</p> <p>I've set up proxmox + docker and a few containers.</p> <p>There are some issues that I wish I'd solve, but also understand:</p> <p>- I try to connect through ssh to the docker machine, and I get Connection refused. I was able at one point to ssh to it, but that ability disappeared.</p> <p>I can only connect to the terminal through &gt;_ Console in proxmox window (browser), which has some problems, like not being able to scroll up.</p> <p>- When (re)starting the docker machine, I get the following errors/warnings:</p> <pre><code>overlayfs: missing 'lowerdir' . . cloud-init[1215]: (...) cc_final_message.py[WARNING]: Used fallback datasource </code></pre> <p>And then the prompt simply doesn't appear. I have to CTRL+C and then relog to be able to use the shell.</p> <p>- I run Heimdall + Portainer and Whoogle, Seafile and Plex. Heimdall is on port 80. Sometimes, the servi

## My monitoring dashboard in Homarr
 - [https://www.reddit.com/r/selfhosted/comments/1c0qp0i/my_monitoring_dashboard_in_homarr](https://www.reddit.com/r/selfhosted/comments/1c0qp0i/my_monitoring_dashboard_in_homarr)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T17:05:59+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c0qp0i/my_monitoring_dashboard_in_homarr/"> <img alt="My monitoring dashboard in Homarr" src="https://preview.redd.it/od9ss44lkotc1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=ad55506c0809b1ad09882abbdffcacd67fcde784" title="My monitoring dashboard in Homarr" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lljdu77_-bvd"> /u/lljdu77_-bvd </a> <br /> <span><a href="https://i.redd.it/od9ss44lkotc1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0qp0i/my_monitoring_dashboard_in_homarr/">[comments]</a></span> </td></tr></table>

## Cloudflare Zero trust extremely slow or shows timeout error
 - [https://www.reddit.com/r/selfhosted/comments/1c0qd7f/cloudflare_zero_trust_extremely_slow_or_shows](https://www.reddit.com/r/selfhosted/comments/1c0qd7f/cloudflare_zero_trust_extremely_slow_or_shows)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T16:52:41+00:00

<!-- SC_OFF --><div class="md"><p>I set up a webserver to run on a raspberry pi (dietpi) and set up cloudflare tunnels to point my domain name to it, it was working fine until a week ago. But now its either extremely slow to load or shows a timeout error. I can access the website perfectly fine through tailscale funnel, its fast and reliable. htop shows hardly 3% cpu and 200mb RAM usage. Is it some payment related/free tier issue ? any way to fix?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dark_AvengerX"> /u/Dark_AvengerX </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0qd7f/cloudflare_zero_trust_extremely_slow_or_shows/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0qd7f/cloudflare_zero_trust_extremely_slow_or_shows/">[comments]</a></span>

## A know-nothing ignoramus self-hosting a website safely?
 - [https://www.reddit.com/r/selfhosted/comments/1c0qcsv/a_knownothing_ignoramus_selfhosting_a_website](https://www.reddit.com/r/selfhosted/comments/1c0qcsv/a_knownothing_ignoramus_selfhosting_a_website)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T16:52:14+00:00

<!-- SC_OFF --><div class="md"><p>I expose quite a few services to the internet via cloudflare tunnels, but they're ridiculously locked down so only me and 1 or 2 other people can actually reach them.</p> <p>One thing I haven't done is host a publicly accessible site from home that <em>anyone</em> can reach, and the trouble is that the little i know about this whole game is self-taught, cobbled together from tutorials and youtube. Since I have zero IT training or experience, I don't know what I don't know.. which leads me to be very risk-averse when it comes to security. Despite this, I have a spare Pi 4 2GB sitting around doing nothing, so I wanted to chuck Ghost on it and run a site from home.</p> <p>My idea was this. My home network is an orbi, which allows a guest LAN to be created. I was sceptical of the network isolation, but I joined it and ran a couple of different network scanners and I've never been able to detect any of the devices that live on my main network, so there's s

## Shoutout for Restic and Kopia as backup solutions!
 - [https://www.reddit.com/r/selfhosted/comments/1c0pj9r/shoutout_for_restic_and_kopia_as_backup_solutions](https://www.reddit.com/r/selfhosted/comments/1c0pj9r/shoutout_for_restic_and_kopia_as_backup_solutions)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T16:18:40+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>&#x200b;</p> <p>I was using Duplicati as backup solution for my NAS for the past year. However, when I tried to recover files, it sometimes worked and sometimes didn't. On my NAS I didn't have a loss of data or anything similar, I just tried to test if a recovery would work.</p> <p>&#x200b;</p> <p>It gave me quite a headache that Duplicati is struggling with the recovering of data. I mean when really something happens you want to have a reliable backup to recover from, no? When you google for that, you also read quite some horrific cases.</p> <p>&#x200b;</p> <p>So I needed a new backup solution. After researching quite a lot, I ended up with restic, borgbackup and kopia. Borg didn't work an my NAS, but I also liked it the least, so I focused on Restic and Kopia. At the beginning I was a little hesitant as they are more CLI tools.</p> <p>But the documentation is really good (especially Restic) and once they are set up, hell these

## How to control PC music playback remotely?
 - [https://www.reddit.com/r/selfhosted/comments/1c0oyk4/how_to_control_pc_music_playback_remotely](https://www.reddit.com/r/selfhosted/comments/1c0oyk4/how_to_control_pc_music_playback_remotely)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T15:54:44+00:00

<!-- SC_OFF --><div class="md"><p>I need some (simple) solution to control PC media playback locally using my phone or Home Assistant.</p> <p>Previously I had my Spotify account connected to Home Assistant and it worked great. I could control the music easily with Android, HASS and I could create HASS automations to e.g. stop the music when I changed my TV source. No more surprises when someone (me) forgets to pause the music, switches between apps and returns to PC output.</p> <p>Now I decided to switch Spotify to Navidrome/Jellyfin. Symfonium works amazingly on Android and offers so much more options than Spotify. Problem is with my Windows setup. I use Sonixd as client but it doesn't have any remote control properties that I'm aware of. Feishin does offer some web based remote control server, but it is not yet as mature as Sonixd and I didn't find any easy way to add it to HASS. I also enabled that &quot;Enable 'Play to' DLNA feature&quot; on my Jellyfin server but that didn't allo

## container cannot ping host
 - [https://www.reddit.com/r/selfhosted/comments/1c0otum/container_cannot_ping_host](https://www.reddit.com/r/selfhosted/comments/1c0otum/container_cannot_ping_host)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T15:49:07+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c0otum/container_cannot_ping_host/"> <img alt="container cannot ping host" src="https://b.thumbs.redditmedia.com/ENqg66vzy4FDhBcZ_6Rl8auRQt62cLzxzSUz3z3wDpI.jpg" title="container cannot ping host" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>i have raspi4B with ubuntu server 22.04LTS, i create ipvlan l3 network name &quot;asgard&quot; with subnet <a href="https://192.168.0.0">192.168.0.0</a> with parent int (eth0) and create a container with ip of <a href="https://192.168.0.5">192.168.0.5</a>, but container does not show gateway ip and cannot ping eth0 ip. I tried to add route but it not permitted. How do i solve this? I even cannot create two network (ipvlan) with same parent int (eth0) bcs its show its already have another network with same int?</p> <p><a href="https://preview.redd.it/dvmtoiijbotc1.png?width=865&amp;format=png&amp;auto=webp&amp;s=4aa94e8d42dd89cf144971e87acd503914e87b85">https://preview.r

## Sync Nextcloud to Calendly? Or setup iCal?
 - [https://www.reddit.com/r/selfhosted/comments/1c0os33/sync_nextcloud_to_calendly_or_setup_ical](https://www.reddit.com/r/selfhosted/comments/1c0os33/sync_nextcloud_to_calendly_or_setup_ical)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T15:46:59+00:00

<!-- SC_OFF --><div class="md"><p>I migrated my calendar to a self hosted nextcloud instance on my homelab with a VPN I use back to my house. I also run a side business where I use calendly for people to book meetings with me. </p> <p>I don't currently have a good way to securely host iCal and have it sync to my lab nextcloud calendars. Also it looks like iCal still isn't great with calDAV.</p> <p>The other thought I have had is to have a local script pull my nextcloud calendar info, turn it into a free/busy .ics and somehow sync that to google calendar (so my events aren't synced to google calendar but my availability is), then I could sync Calendly with google calendar so people don't book meetings for times I'm not available. </p> <p>Has anyone accomplished this before? Any tips/ ideas?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Safe-Preparation-674"> /u/Safe-Preparation-674 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/c

## Update on the dashboard I'm developing (will be open sourced soon!)
 - [https://www.reddit.com/r/selfhosted/comments/1c0omqx/update_on_the_dashboard_im_developing_will_be](https://www.reddit.com/r/selfhosted/comments/1c0omqx/update_on_the_dashboard_im_developing_will_be)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T15:40:54+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c0omqx/update_on_the_dashboard_im_developing_will_be/"> <img alt="Update on the dashboard I'm developing (will be open sourced soon!)" src="https://a.thumbs.redditmedia.com/cQI8G6yz-xqeFK7EjtVkMW4Xg_kv33iLyV_xFeEH254.jpg" title="Update on the dashboard I'm developing (will be open sourced soon!)" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>It's been two months since I previously posted about <a href="https://www.reddit.com/r/selfhosted/comments/1alazj2/">the dashboard I'm working on</a>. I was hoping I'd be able to release it sooner but some of the features took longer than expected. Namely:</p> <ul> <li>Being able to configure everything via a single yaml file, similar to homepage</li> <li>Adding support for multiple pages, you can have however many widgets in whatever order you like on each page</li> <li>Making everything responsive so the dashboard is usable on mobile devices</li> <li>Allowing for color

## My custom start page for Chrome.
 - [https://www.reddit.com/r/selfhosted/comments/1c0omoz/my_custom_start_page_for_chrome](https://www.reddit.com/r/selfhosted/comments/1c0omoz/my_custom_start_page_for_chrome)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T15:40:51+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c0omoz/my_custom_start_page_for_chrome/"> <img alt="My custom start page for Chrome." src="https://preview.redd.it/evyip1lj9otc1.gif?width=640&amp;crop=smart&amp;s=41a33576d404fe2415d8ac5876101b7848a1d3bc" title="My custom start page for Chrome." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/boxoft_sh"> /u/boxoft_sh </a> <br /> <span><a href="https://i.redd.it/evyip1lj9otc1.gif">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0omoz/my_custom_start_page_for_chrome/">[comments]</a></span> </td></tr></table>

## adding ansible to homelab
 - [https://www.reddit.com/r/selfhosted/comments/1c0ojhn/adding_ansible_to_homelab](https://www.reddit.com/r/selfhosted/comments/1c0ojhn/adding_ansible_to_homelab)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T15:36:56+00:00

<!-- SC_OFF --><div class="md"><p>I am looking to learn more about using Ansible to manage configurations in my homelab. I would like to start out on the right foot and thus I am asking for opinions on where to install and run it from. I have Windows and mac laptops/desktops, raspberrypi 3b on pi OS dedicated to adguard, an Openmediavault NAS (debian) that I use to run dockerized apps from, A TrueNAS NAS that I use for storage and a few apps, a Proxmox system that I run VM for pfsense and a couple LXC apps. I have a spare mini-PC that I planned on using as a discardable client to test ansible against till I have confidence I will not break everything :) I am most familiar with Windows, then linux and then macos. </p> <p>I was thinking I should use a dockerized install of ansible tower as it seems to be able to add gui functionality as well as all of the commandline features, plus dockerized apps are easy for me to move around if I want to recreate the system it happens to be running o

## CGNAT + Unraid + Plex + website
 - [https://www.reddit.com/r/selfhosted/comments/1c0o8yj/cgnat_unraid_plex_website](https://www.reddit.com/r/selfhosted/comments/1c0o8yj/cgnat_unraid_plex_website)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T15:24:39+00:00

<!-- SC_OFF --><div class="md"><p>This is not the first post on the topic, but I have read most of the previous ones and still not quite sure about my approach here. I have fiber connection but my ISP insists on CGNAT for all customers so I'm SOL on getting out of that, which then brings me to find a solution to this. </p> <p>I run Plex for myself and have two more properties in different locations and I want these to be able to access my Plex-server, hosted as a docker container on my Unraid server. I also have homeassistant and a website that I wish to expose. </p> <p>First I tried was Cloudflare tunnel but since my domain name is not supported by them, the concept fell apart a bit (they need you to move the domain to them for this to work) so now I'm looking at Tailscale.</p> <p>What I don't understand is how I can expose individual services, if all traffic will be routed through TS so that I will be hit with a bandwidth consumption bill at the end of watching a bunch of movies off

## Navidrome server on Nvidia Shield?
 - [https://www.reddit.com/r/selfhosted/comments/1c0ntth/navidrome_server_on_nvidia_shield](https://www.reddit.com/r/selfhosted/comments/1c0ntth/navidrome_server_on_nvidia_shield)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T15:06:58+00:00

<!-- SC_OFF --><div class="md"><p>I would like to setup navidrome to quit my Spotify subscription and stream my music collection. My audio files are stored on a Synology NAS at home. </p> <p>My synology is a DS213+ that unfortunately does not support Docker to install navidrome directly on it 🤕</p> <p>The only other decente device I have at home that is pretty much always turned on is Nvidia Shield. I was then wondering if it is possible to install docker/navidrome or navidrome server without Docker on the Shield and configure it to 1) use synology as music source and 2) configure my home network to access navidrome when on-the-go using navidrome app on my smartphone. Do you think it is possible? Any help much appreciated 🙏 thank you</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AnotherRedditUsr"> /u/AnotherRedditUsr </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0ntth/navidrome_server_on_nvidia_shield/">[link]</a></s

## Announcing Medusa 2.0
 - [https://www.reddit.com/r/selfhosted/comments/1c0nfwk/announcing_medusa_20](https://www.reddit.com/r/selfhosted/comments/1c0nfwk/announcing_medusa_20)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T14:50:37+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I'm Nick, one of the founders of the open-source project MedusaJS (<a href="https://github.com/medusajs/medusa">repo</a>).</p> <p>We just announced the biggest product update to date with <a href="https://medusajs.com/recap/">Medusa 2.0</a>, which will be a step-change for our ecommerce platform.</p> <p>With the release, we'll ship a lot of things:</p> <ul> <li>Redesigned Admin dashboard</li> <li>New commerce features and modules</li> <li>A fully modularized architecture</li> <li>A built-in server framework for customizations</li> </ul> <p><strong>Building a server framework for customizations</strong></p> <p>While all of the additions mean a lot to us, the built-in server framework is probably one of the biggest differences from what you'll have seen in traditional ecommerce platforms.</p> <p>With Medusa 2.0, we modularize all of our commerce functionality into 17 independent services for cart, payment, orders, customers, authentication, and a

## LocalAI 2.12: AIO Images improvements, Swagger API, OpenVINO, and more!
 - [https://www.reddit.com/r/selfhosted/comments/1c0nei0/localai_212_aio_images_improvements_swagger_api](https://www.reddit.com/r/selfhosted/comments/1c0nei0/localai_212_aio_images_improvements_swagger_api)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T14:48:57+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c0nei0/localai_212_aio_images_improvements_swagger_api/"> <img alt="LocalAI 2.12: AIO Images improvements, Swagger API, OpenVINO, and more!" src="https://a.thumbs.redditmedia.com/IcOHy6P7fdi7T-kcJNCQP4yluYxeZku4SAoOyfC7Qu8.jpg" title="LocalAI 2.12: AIO Images improvements, Swagger API, OpenVINO, and more!" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey <a href="/r/selfhosted">/r/selfhosted</a> community!</p> <p>I’m excited to share with you all the latest release from the <strong>LocalAI</strong> project: v2.12.3! You can read the changelog here: <a href="https://github.com/mudler/LocalAI/releases/tag/v2.12.3">https://github.com/mudler/LocalAI/releases/tag/v2.12.3</a></p> <p>This version builds on the incredible foundation of v2.11.0, bringing even more features and improvements tailored for the self-hosting community. Whether you’re a seasoned developer, a hobbyist, or somewhere in between, there’s somet

## How important is DRAM on an SSD for servers?
 - [https://www.reddit.com/r/selfhosted/comments/1c0nado/how_important_is_dram_on_an_ssd_for_servers](https://www.reddit.com/r/selfhosted/comments/1c0nado/how_important_is_dram_on_an_ssd_for_servers)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T14:44:00+00:00

<!-- SC_OFF --><div class="md"><p>What are your thoughts? Is getting DRAM critical for a web or game server or would you be comfortable with non-DRAM?</p> <p><a href="https://www.reddit.com/poll/1c0nado">View Poll</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/-entei-"> /u/-entei- </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0nado/how_important_is_dram_on_an_ssd_for_servers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0nado/how_important_is_dram_on_an_ssd_for_servers/">[comments]</a></span>

## Speedtest drops speed every three hours. Why?
 - [https://www.reddit.com/r/selfhosted/comments/1c0mt9m/speedtest_drops_speed_every_three_hours_why](https://www.reddit.com/r/selfhosted/comments/1c0mt9m/speedtest_drops_speed_every_three_hours_why)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T14:22:45+00:00

<!-- SC_OFF --><div class="md"><p>I recently deployed speedtest tracker. The one by whitaker. </p> <p>Epic software for monitoring. Set up was super easy. Works like a charm. Love the container.</p> <p>But after setting it up, I noticed my speedtest results show that my wifi speeds fail every three hours. Or the container fails every 3 hours. I think it is the latter. And probably has to do with my cron set up(@hourly). </p> <p>I really don't know why this is happening. Like I also know the speedtest failed. As seen in the bottom screenshot.</p> <p><a href="https://preview.redd.it/f2zhnd03vntc1.png?width=1917&amp;format=png&amp;auto=webp&amp;s=6f4e828a6d551b5060fb4f8baf3f2e98b1d9eddc">All those dips are at an equal interval of 3 hours.</a></p> <p>&#x200b;</p> <p><a href="https://preview.redd.it/31jzvjtdvntc1.png?width=943&amp;format=png&amp;auto=webp&amp;s=02d86276d94ccaadff29571b3bea88eba629ed7d">All most all those red ones match with the above drops. </a></p> <p>But the question rem

## Speedtest drops speed every three hours. Why?
 - [https://www.reddit.com/r/selfhosted/comments/1c0mt9f/speedtest_drops_speed_every_three_hours_why](https://www.reddit.com/r/selfhosted/comments/1c0mt9f/speedtest_drops_speed_every_three_hours_why)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T14:22:44+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c0mt9f/speedtest_drops_speed_every_three_hours_why/"> <img alt="Speedtest drops speed every three hours. Why?" src="https://a.thumbs.redditmedia.com/fpdHHEeTPOUr7VCBHPTbGW-GkMYvUzE-opqBr6kGbh4.jpg" title="Speedtest drops speed every three hours. Why?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I recently deployed speedtest tracker. The one by whitaker. </p> <p>Epic software for monitoring. Set up was super easy. Works like a charm. Love the container.</p> <p>But after setting it up, I noticed my speedtest results show that my wifi speeds fail every three hours. Or the container fails every 3 hours. I think it is the latter. And probably has to do with my cron set up(@hourly). </p> <p>I really don't know why this is happening. Like I also know the speedtest failed. As seen in the bottom screenshot.</p> <p><a href="https://preview.redd.it/f2zhnd03vntc1.png?width=1917&amp;format=png&amp;auto=webp&amp;s=6f4e8

## Whats the best router for home and self hosting use?
 - [https://www.reddit.com/r/selfhosted/comments/1c0mn9j/whats_the_best_router_for_home_and_self_hosting](https://www.reddit.com/r/selfhosted/comments/1c0mn9j/whats_the_best_router_for_home_and_self_hosting)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T14:15:16+00:00

<!-- SC_OFF --><div class="md"><p>I'm currently using a Telstra Netgear V7610 for my home WiFi and hosting a small website. However, it's been quite buggy lately, especially with port forwarding not working properly. So, I've decided to get a new router.</p> <p>I plan to use the new router for web hosting, general home use (such as streaming and browsing on my phone), and hopefully setting up a VPN soon. Since I'm more knowledgeable in software than hardware, I'm wondering what the best router would be for these purposes. Any advice?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/InsideElectrical479"> /u/InsideElectrical479 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0mn9j/whats_the_best_router_for_home_and_self_hosting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0mn9j/whats_the_best_router_for_home_and_self_hosting/">[comments]</a></span>

## Nextcloud VS NAS
 - [https://www.reddit.com/r/selfhosted/comments/1c0mboj/nextcloud_vs_nas](https://www.reddit.com/r/selfhosted/comments/1c0mboj/nextcloud_vs_nas)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T14:01:20+00:00

<!-- SC_OFF --><div class="md"><p>Whats your thoughts on Nextcloud VS NAS, both serves the same functionality.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/littleblack11111"> /u/littleblack11111 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0mboj/nextcloud_vs_nas/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0mboj/nextcloud_vs_nas/">[comments]</a></span>

## Best Website Builder Reddit Users Recommend?
 - [https://www.reddit.com/r/selfhosted/comments/1c0mbfl/best_website_builder_reddit_users_recommend](https://www.reddit.com/r/selfhosted/comments/1c0mbfl/best_website_builder_reddit_users_recommend)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T14:01:07+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/whowannawut"> /u/whowannawut </a> <br /> <span><a href="/r/WebsiteBuilder/comments/1c0m0ky/best_website_builder_reddit_users_recommend/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0mbfl/best_website_builder_reddit_users_recommend/">[comments]</a></span>

## Nice/modern directory indexer?
 - [https://www.reddit.com/r/selfhosted/comments/1c0m9pt/nicemodern_directory_indexer](https://www.reddit.com/r/selfhosted/comments/1c0m9pt/nicemodern_directory_indexer)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T13:59:16+00:00

<!-- SC_OFF --><div class="md"><p>I want something that is like nginx with directory listing on. But it look too ugly and sometimes vuln. Is there anything nice looking and is read-only and lightweight?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/littleblack11111"> /u/littleblack11111 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0m9pt/nicemodern_directory_indexer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0m9pt/nicemodern_directory_indexer/">[comments]</a></span>

## Proton and Standard Notes are joining forces
 - [https://www.reddit.com/r/selfhosted/comments/1c0lzpg/proton_and_standard_notes_are_joining_forces](https://www.reddit.com/r/selfhosted/comments/1c0lzpg/proton_and_standard_notes_are_joining_forces)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T13:46:51+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c0lzpg/proton_and_standard_notes_are_joining_forces/"> <img alt="Proton and Standard Notes are joining forces" src="https://external-preview.redd.it/TXgN-td30DUXdizVf9SDM3tu4PpCvYurys4_L8o1oC4.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=43cb5ea58a132ae5a0b04172aa91b9b550d26009" title="Proton and Standard Notes are joining forces" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/daniele2010"> /u/daniele2010 </a> <br /> <span><a href="https://proton.me/blog/proton-standard-notes-join-forces">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0lzpg/proton_and_standard_notes_are_joining_forces/">[comments]</a></span> </td></tr></table>

## Home media center/server – Kodi? Jellyfin? Both?
 - [https://www.reddit.com/r/selfhosted/comments/1c0lw6x/home_media_centerserver_kodi_jellyfin_both](https://www.reddit.com/r/selfhosted/comments/1c0lw6x/home_media_centerserver_kodi_jellyfin_both)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T13:42:24+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, </p> <p>I’m looking to cut the cord on various streaming video services and just have a home media center. I’d primarily like to have something that would function easily to watch movies/TV, listen to music, and look at photos on the screen in our living room, but also be able to access content from phones, tablets, etc. </p> <p>I have a dumb TV, and was thinking about getting something like this and adding some storage to be a home media server: <a href="https://www.newegg.com/p/N82E16883461211?Item=9SIADFMJ4D9984">https://www.newegg.com/p/N82E16883461211?Item=9SIADFMJ4D9984</a> Was thinking to install linux as OS, Jellyfin to host, and hook the computer directly to the TV’s HDMI input, with Kodi as the main interface to play media. </p> <p>Would that work? Or can I play media locally with Jellyfin?</p> <p>Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jpc27699"> /u/jpc27699 </a> <br /> 

## Need help making lists on Mailtrain!
 - [https://www.reddit.com/r/selfhosted/comments/1c0llw2/need_help_making_lists_on_mailtrain](https://www.reddit.com/r/selfhosted/comments/1c0llw2/need_help_making_lists_on_mailtrain)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T13:29:08+00:00

<!-- SC_OFF --><div class="md"><p>Hi, my org uses Mailtrain. I need some help with making Lists on it.</p> <p>There is no info online. Is there anyone here proficient or decent with Mailtrain, that could help me?</p> <p>Cheers.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/huge_seal"> /u/huge_seal </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0llw2/need_help_making_lists_on_mailtrain/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0llw2/need_help_making_lists_on_mailtrain/">[comments]</a></span>

## Self-hosted, declarative NAS
 - [https://www.reddit.com/r/selfhosted/comments/1c0l7oz/selfhosted_declarative_nas](https://www.reddit.com/r/selfhosted/comments/1c0l7oz/selfhosted_declarative_nas)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T13:10:22+00:00

<!-- SC_OFF --><div class="md"><p>Ok, I give up, and I'll appeal to the collective wisdom...<br /> <strong>The problem</strong>: I'm trying to find a way to automatically deploy a NAS solution to homelab (one node Proxmox host with a HBA card bearing 8 8000Gb SSDs). I hope someone in this community might have a solution which could fit my requirements.</p> <p><strong>The constraints</strong>:</p> <ul> <li>I'm a Cloud engineer by trade, so I want to make it purely declarative (Terraform for deployment + Ansible for configuration management); (some) GUIs are great but way to imperative to my taste</li> <li>A <code>cloud-init</code>-compatible solution, as it greatly simplifies the bootstrap of VMs/LXC containers (eg. setting up user/SSH keys/Tailscale configuration)</li> <li>Based on cloud images (as opposed to ISO installations which need manual intervention). <code>.img</code> or <code>qcow2</code> images + <code>cloud-init</code> bootstrap is a match made in heaven</li> <li>ZFS compa

## Finally updated and got Homepage dashboard set up
 - [https://www.reddit.com/r/selfhosted/comments/1c0kmkm/finally_updated_and_got_homepage_dashboard_set_up](https://www.reddit.com/r/selfhosted/comments/1c0kmkm/finally_updated_and_got_homepage_dashboard_set_up)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T12:41:24+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c0kmkm/finally_updated_and_got_homepage_dashboard_set_up/"> <img alt="Finally updated and got Homepage dashboard set up" src="https://b.thumbs.redditmedia.com/3ihdY4lJSuKP5kWJ62xBcDpvF-h1FxrOT9lSP_jUVQw.jpg" title="Finally updated and got Homepage dashboard set up" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Started my self-hosted journey with a simple <em>dashy</em> dashboard, was not the nicest looking but did the job. Heard about <a href="https://gethomepage.dev/latest/"><em>gethomepage.dev</em></a> on this subreddit, so decided to give it a go! </p> <p>Over time I suspect I will turn off some of the widgets, but for now its serving me well until I finish adding a final few self-hosted apps 🤞 </p> <p><a href="https://preview.redd.it/qttoli2santc1.png?width=1772&amp;format=png&amp;auto=webp&amp;s=f1641c6db4e9ab2a07761757cb922b43ddb2632d">https://preview.redd.it/qttoli2santc1.png?width=1772&amp;format=png

## Best ios app to upload and view photo/videos on a ftp server?
 - [https://www.reddit.com/r/selfhosted/comments/1c0klrl/best_ios_app_to_upload_and_view_photovideos_on_a](https://www.reddit.com/r/selfhosted/comments/1c0klrl/best_ios_app_to_upload_and_view_photovideos_on_a)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T12:40:19+00:00

<!-- SC_OFF --><div class="md"><p>Hello! </p> <p>Do you guys recommend any good apps for iOS to upload and view photos on a ftp-server?</p> <p>I have found photosync but dont really work to see what you have uploaded or view photos from the ftp-server. </p> <p>Thank you!</p> <p>(Some family members dont want to use Google Photos and iCloud due to privacy reasons).</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/raynoralpha123"> /u/raynoralpha123 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0klrl/best_ios_app_to_upload_and_view_photovideos_on_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0klrl/best_ios_app_to_upload_and_view_photovideos_on_a/">[comments]</a></span>

## Decrypt Partition over SSH | Rocky Linux
 - [https://www.reddit.com/r/selfhosted/comments/1c0kgvu/decrypt_partition_over_ssh_rocky_linux](https://www.reddit.com/r/selfhosted/comments/1c0kgvu/decrypt_partition_over_ssh_rocky_linux)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T12:33:27+00:00

<!-- SC_OFF --><div class="md"><p>Hey,</p> <p>i was wondering how i could create a seperate partition in the rocky linux setup that i could unlock after connecting to the server with ssh. That means the encryption cannot happen on boot because otherwise ssh would not be loaded as it's stuck on the password prompt.</p> <p>Can i just select custom partition, create a encrypted luks2 named /encrypted-data and thats it? How would i stop that from being prompted on boot?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Innocent__Rain"> /u/Innocent__Rain </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0kgvu/decrypt_partition_over_ssh_rocky_linux/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0kgvu/decrypt_partition_over_ssh_rocky_linux/">[comments]</a></span>

## Advice needed for personal project I'm thinking of making available for selfhosting
 - [https://www.reddit.com/r/selfhosted/comments/1c0kdm6/advice_needed_for_personal_project_im_thinking_of](https://www.reddit.com/r/selfhosted/comments/1c0kdm6/advice_needed_for_personal_project_im_thinking_of)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T12:28:52+00:00

<!-- SC_OFF --><div class="md"><p>I have an app which is primarily an API for generating invoices with payment links. The user calls my api with their invoice data, and it returns a PDF invoice with a payment link for their customer. </p> <p>You can see it here: <a href="https://invoicingapi.com">https://invoicingapi.com</a>.</p> <p>I launched it recently and got lots of positive comments and registrations, but I also had a few users who mentioned that an invoicing app lends well to self hosting. I never initially thought to make this available for self hosting but now I've been putting a lot of thought into it. I would like to get some advice from the community here however since you're all a lot more aware of the self hosting landscape than I am.</p> <p>Firstly, does a self hosted application need to be open source? Or is it not necessary but preferable? One app that comes to mind is FusionAuth which has a self hosted option, but the app is closed source still. I'm actually using Fu

## A simple Remote Monitoring and Management solution for home
 - [https://www.reddit.com/r/selfhosted/comments/1c0jt9q/a_simple_remote_monitoring_and_management](https://www.reddit.com/r/selfhosted/comments/1c0jt9q/a_simple_remote_monitoring_and_management)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T11:59:59+00:00

<!-- SC_OFF --><div class="md"><p>Hello, folks! </p> <p>I'm looking for advice regarding simple selfhosted RMM solution for home that can be launched in a docker container, say, on Synology.<br /> Long story short: there are around 5 family laptops and PCs with Windows, also a couple of Macs (MBP and iMac), located in various places, that I would like to monitor, install/update/uninstall some software (<strong>chocolatey</strong>/<strong>brew</strong> repos are good enough here) without giving admin rights to local user, and optionally sometimes connect to their Desktop interactively (with question to local user, similar to TeamViewer).<br /> Yes, I saw <strong>Tactical RMM</strong> — it looks good for some small business, but overkill for home (also limited Mac support).<br /> Also I saw <strong>Action1</strong> (which is not selfhosted btw) — also looks good, but I'm <strong>a bit</strong> <em>concerned</em> about some random cloud that have unrestricted access to my PC (and kinda o

## Weathermap for Observium alternatives
 - [https://www.reddit.com/r/selfhosted/comments/1c0jsih/weathermap_for_observium_alternatives](https://www.reddit.com/r/selfhosted/comments/1c0jsih/weathermap_for_observium_alternatives)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T11:58:45+00:00

<!-- SC_OFF --><div class="md"><p>Hi everybody,</p> <p>I just tried to &quot;install&quot; Weathermap into Observium, using one of the fork that you can find on GitHub.<br /> The real problem is that my current prod VM with Observium, is using php8, which is not compatible with Weathermap. </p> <p>So here's the question: does anybody know something that can be integrated into Observium and does the same function like Weathermap (in simple words, a Weathermap alternative)? </p> <p>Thanks for the reply</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Daaaaav26"> /u/Daaaaav26 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0jsih/weathermap_for_observium_alternatives/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0jsih/weathermap_for_observium_alternatives/">[comments]</a></span>

## Website Proxies VPN and a Newb
 - [https://www.reddit.com/r/selfhosted/comments/1c0jrmt/website_proxies_vpn_and_a_newb](https://www.reddit.com/r/selfhosted/comments/1c0jrmt/website_proxies_vpn_and_a_newb)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T11:57:16+00:00

<!-- SC_OFF --><div class="md"><p>I am considering building my own website and really don't want to use GD so I found another host and am putting the pieces together hopefully with the intent of using WordPress.org</p> <p>I'm tripped up on understanding how Proxies work vs VPN though and honestly just wanna throw up a few barriers between my personal address, info, and the host/info to the registry. What's the easiest way to do this? Are you using the proxy to develop the site or putting the proxy IP in somewhere at time of sign up with the host or is it easier to just use a VPN or a 3rd party company like the one GD uses? </p> <p>I honestly never imagined I'd be this far down the rabbit hole in comparing things when last week I pretty much had a cookie cutter website finished but at this point I'd rather at least know and understand how these parts work then decide on the best option. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Alchemist002

## The question is about ports
 - [https://www.reddit.com/r/selfhosted/comments/1c0jqdd/the_question_is_about_ports](https://www.reddit.com/r/selfhosted/comments/1c0jqdd/the_question_is_about_ports)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T11:55:07+00:00

<!-- SC_OFF --><div class="md"><p>The question is, if plex and qnap can connect to a computer/server from an external network with closed ports, why can’t you do the same with the web server and ports 80,443 via cloudflare</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/fly_israel"> /u/fly_israel </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0jqdd/the_question_is_about_ports/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0jqdd/the_question_is_about_ports/">[comments]</a></span>

## What do you think or feel is better? Or which do you prefer and why?
 - [https://www.reddit.com/r/selfhosted/comments/1c0jlyk/what_do_you_think_or_feel_is_better_or_which_do](https://www.reddit.com/r/selfhosted/comments/1c0jlyk/what_do_you_think_or_feel_is_better_or_which_do)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T11:48:03+00:00

<!-- SC_OFF --><div class="md"><p>As the title implies, sorry if this breaks any rules.</p> <p><a href="https://www.reddit.com/poll/1c0jlyk">View Poll</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TheBlackTrashBag"> /u/TheBlackTrashBag </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0jlyk/what_do_you_think_or_feel_is_better_or_which_do/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0jlyk/what_do_you_think_or_feel_is_better_or_which_do/">[comments]</a></span>

## Guide for self hosting using podman and quadlets
 - [https://www.reddit.com/r/selfhosted/comments/1c0j9t5/guide_for_self_hosting_using_podman_and_quadlets](https://www.reddit.com/r/selfhosted/comments/1c0j9t5/guide_for_self_hosting_using_podman_and_quadlets)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T11:28:31+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c0j9t5/guide_for_self_hosting_using_podman_and_quadlets/"> <img alt="Guide for self hosting using podman and quadlets" src="https://external-preview.redd.it/GlW4JxvABDZxMJucabxn4Rjw9ek1PNTkObs30Btztnc.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=526f3ddb56743e833fcdaeb2912c174622830bf6" title="Guide for self hosting using podman and quadlets" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I wrote a guide for self hosting using podman and quadlets for anyone who is interested. This is the first time I wrote a guide for anything so any feedback or any other suggestions are welcome and appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Professional-Jump375"> /u/Professional-Jump375 </a> <br /> <span><a href="https://github.com/GaviniSumanth/Self-Hosting-Guide">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0j9t5/guide_for

## paperless-ngx add barcode data to document content
 - [https://www.reddit.com/r/selfhosted/comments/1c0ir2q/paperlessngx_add_barcode_data_to_document_content](https://www.reddit.com/r/selfhosted/comments/1c0ir2q/paperlessngx_add_barcode_data_to_document_content)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T10:56:48+00:00

<!-- SC_OFF --><div class="md"><p>Is it possible to append data recognized from barcodes on the document to the document content?</p> <p>I got barcode scanning up and running, but I couldn't find a way to add the barcode data to the content.</p> <p>I have some documents with barcodes containing HUB3 (payment) data. I would like to use RestAPI to get the documents and retrieve that payment data so I could automate payments.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/IndependenceAlone976"> /u/IndependenceAlone976 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0ir2q/paperlessngx_add_barcode_data_to_document_content/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0ir2q/paperlessngx_add_barcode_data_to_document_content/">[comments]</a></span>

## I want to build a cloud - where do I start?
 - [https://www.reddit.com/r/selfhosted/comments/1c0ijhs/i_want_to_build_a_cloud_where_do_i_start](https://www.reddit.com/r/selfhosted/comments/1c0ijhs/i_want_to_build_a_cloud_where_do_i_start)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T10:43:04+00:00

<!-- SC_OFF --><div class="md"><p>Hello gang</p> <p>So I want to build my own cloud. It'll be made up of three Raspi 5s with an a 4 GB SSD attached to each one. One will be at my home and the other two at my parents and in-laws house respectively. I want them to all connect to my Wireguard server, so there is no need to publicly expose anything. The goal is primarily to host a file server and Immich for pictures. Maybe more later. My initial thought was just to set up the one at my home and have the other two only running Syncthing to basically mirror the content of the attached drive (because that back up is the number one priority). However, should that first Pi go down I couldn't access the files if I were to be on the go (but they wouldn't be lost). Now I'm not familiar with K3s (but willing to learn) but I think that that could be a solution? My vision would be to just have one domain/IP to access Immich for example and whichever Pi is online would answer and they'd all have the 

## Any opinions on SiYuan (an apparently very good Notion alternative)
 - [https://www.reddit.com/r/selfhosted/comments/1c0i2lq/any_opinions_on_siyuan_an_apparently_very_good](https://www.reddit.com/r/selfhosted/comments/1c0i2lq/any_opinions_on_siyuan_an_apparently_very_good)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T10:12:18+00:00

<!-- SC_OFF --><div class="md"><p>Pretty much the title. GitHub link <a href="https://github.com/siyuan-note/siyuan">here</a>.</p> <p>This seems awesome if there is no catch. I've been looking for something like this for a while, to use a self-hosted knowledge base, but there's so few opinions about it online that I don't know what to think. Pretty much one of those &quot;too good to be true&quot; situations.</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Plut0nianPluto"> /u/Plut0nianPluto </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0i2lq/any_opinions_on_siyuan_an_apparently_very_good/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0i2lq/any_opinions_on_siyuan_an_apparently_very_good/">[comments]</a></span>

## Opensourcing Jellybox code, cross platform client for Jellyfin
 - [https://www.reddit.com/r/selfhosted/comments/1c0hjpz/opensourcing_jellybox_code_cross_platform_client](https://www.reddit.com/r/selfhosted/comments/1c0hjpz/opensourcing_jellybox_code_cross_platform_client)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T09:36:21+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c0hjpz/opensourcing_jellybox_code_cross_platform_client/"> <img alt="Opensourcing Jellybox code, cross platform client for Jellyfin" src="https://external-preview.redd.it/dFlU0imkjvTgmglrU_qv01d1VndxLWPK3LNttdBUNxU.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=a401726bd20958f3aeac5e5ef7d5dc458872a915" title="Opensourcing Jellybox code, cross platform client for Jellyfin" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>&#x200b;</p> <p><a href="https://preview.redd.it/swfewq5agmtc1.png?width=8640&amp;format=png&amp;auto=webp&amp;s=676b0c5b1b0f86369101446a3f3bf9045da0d839">https://preview.redd.it/swfewq5agmtc1.png?width=8640&amp;format=png&amp;auto=webp&amp;s=676b0c5b1b0f86369101446a3f3bf9045da0d839</a></p> <p>Hey folks, some time ago I posted about my own approach to jelylfin client. My main goal was to get native apps for iOS/macOS. At the time of posting I wasn't ready to open sources due to some tech debt,

## Container started (unhealthy) for Homepage dashboard
 - [https://www.reddit.com/r/selfhosted/comments/1c0hjo3/container_started_unhealthy_for_homepage_dashboard](https://www.reddit.com/r/selfhosted/comments/1c0hjo3/container_started_unhealthy_for_homepage_dashboard)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T09:36:12+00:00

<!-- SC_OFF --><div class="md"><p>I can't connect to Homepage dashboard. <code>docker container ls -a</code> shows either unhealthy or exited</p> <p>My docker-compose.yml:</p> <pre><code>--- # version: &quot;3.3&quot; services: homepage: image: ghcr.io/gethomepage/homepage:latest container_name: homepage ports: - 3100:3000 volumes: - /srv/appdata/homepage/config:/app/config # Make sure your local config directory exists - /var/run/docker.sock:/var/run/docker.sock # (optional) For docker integrations, see alternative methods environment: - PUID=1001 - PGID=1001 - TZ=Europe/Berlin </code></pre> <p>Any help, please?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gett13"> /u/gett13 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0hjo3/container_started_unhealthy_for_homepage_dashboard/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0hjo3/container_started_unhealthy_for_homepage_dashbo

## What nodes would you buy for a local k8s cluster?
 - [https://www.reddit.com/r/selfhosted/comments/1c0hcki/what_nodes_would_you_buy_for_a_local_k8s_cluster](https://www.reddit.com/r/selfhosted/comments/1c0hcki/what_nodes_would_you_buy_for_a_local_k8s_cluster)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T09:21:59+00:00

<!-- SC_OFF --><div class="md"><p>Thinking of investing in some self hosted goodies, and as a big fan of K8s I'd like to run my own cluster, however I have nothing to deploy it to right now.</p> <p>It'd be used for hosting various applications, homeassistant, pihole, VPN, and also potentially some side projects CI/CD and test environments.</p> <p>What would you be choosing as the nodes? RPis? Something else?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/iwouldlikethings"> /u/iwouldlikethings </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0hcki/what_nodes_would_you_buy_for_a_local_k8s_cluster/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0hcki/what_nodes_would_you_buy_for_a_local_k8s_cluster/">[comments]</a></span>

## Advice for ZFS users
 - [https://www.reddit.com/r/selfhosted/comments/1c0gwsz/advice_for_zfs_users](https://www.reddit.com/r/selfhosted/comments/1c0gwsz/advice_for_zfs_users)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T08:49:48+00:00

<!-- SC_OFF --><div class="md"><p>So, I have my server setup with everything in ZFS. Even the boot partition. </p> <p>Some months ago I changed some setting (I think it was dnodesize) and I forgot about it. Well, yesterday my home lost power and the server restarted. Unfortunately, <strong>this setting is incompatible with GRUB and my server cannot boot</strong>. Now I need to wait two weeks until I can go there (server is in my parents house) and fix it 🥲</p> <p>TLDR: Be careful when playing with ZFS settings of partitions booted by GRUB. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jormaig"> /u/jormaig </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0gwsz/advice_for_zfs_users/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0gwsz/advice_for_zfs_users/">[comments]</a></span>

## self-hosted "quantified self"/workout/habit tracking?
 - [https://www.reddit.com/r/selfhosted/comments/1c0g1bv/selfhosted_quantified_selfworkouthabit_tracking](https://www.reddit.com/r/selfhosted/comments/1c0g1bv/selfhosted_quantified_selfworkouthabit_tracking)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T07:45:18+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I'm looking for a self-hosted project to do some self-development/self-investigation. The ideal software would:</p> <p>- help track and graph custom things like exercise, mood, habits, time</p> <p>- support multiple users</p> <p>- work both on web and mobile (or at least like navidrome, that has a web access that can be saved as an app through mobile browser)</p> <p>- be supported by casaos (ideal, but optional)</p> <p>So far I checked:</p> <p>- track and graph (nope, android only, I need centralized storage for multidevice access)</p> <p>- habitica (nice gamification, no dice on mood tracking)</p> <p>- ryot (couldn't figure out how to track moods in there, nor how to graph things nicely)</p> <p>- home assistant (pain in the ass to set up and no multi-user)</p> <p>Any recommendations?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/drgitgud"> /u/drgitgud </a> <br /> <span><a href="https://www.reddit.co

## Self-hosted Safety-Control-System?
 - [https://www.reddit.com/r/selfhosted/comments/1c0g0gu/selfhosted_safetycontrolsystem](https://www.reddit.com/r/selfhosted/comments/1c0g0gu/selfhosted_safetycontrolsystem)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T07:43:39+00:00

<!-- SC_OFF --><div class="md"><p>Hi</p> <p>I run a small food factory and we currently have a HACCP food safety system in place. In order to improve the system, I am thinking to upgrade it to FSSC22000.</p> <p>As part of that, we obviously have to update and then continuously maintain our process descriptions, keep records of measured KPIs, etc.</p> <p>Currently we just have a bunch of Word documents, organized in a directory structure. However, that seems quite archaic and I wonder if there is some sort of open source software that can support the various tasks? I tried to search online, but I haven't even come across many paid solutions, yet alone a FOSS.</p> <p>One thing that would already help is a good and simple system that allows to keep the process descriptions in a version controlled state, showing all changes made, with basic access rights.</p> <p>The company is quite small, with around 20 employees, so a basic solution would already go a long way. </p> <p>Thanks in advance

## Authentik issue with k8s ingress
 - [https://www.reddit.com/r/selfhosted/comments/1c0fq9y/authentik_issue_with_k8s_ingress](https://www.reddit.com/r/selfhosted/comments/1c0fq9y/authentik_issue_with_k8s_ingress)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T07:23:44+00:00

<!-- SC_OFF --><div class="md"><p>Bit of a newbie to Authentik...</p> <p>I have setup authentik on docker and can successfully proxypass to other docker containers with full authentication, however I also run some services on kubernetes with an ingress controller doing URL matching, all attempts to place authentication in front of these get a &quot;service not found&quot;, which suggest the URI-request is not getting passed correctly to the ingress controller. All my public services are sitting behind an nginx-proxy-manager instance, so that's the provider I'm using, Is there any adjustments to the proxypass (NPM) config, or do I need to provide a 2nd authentik install on the kubernetes itself (via helm)?????</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/geeky217"> /u/geeky217 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0fq9y/authentik_issue_with_k8s_ingress/">[link]</a></span> &#32; <span><a href="https://www.redd

## Service to list and tracks tools usage (real one, not digital one) shared between people
 - [https://www.reddit.com/r/selfhosted/comments/1c0fcip/service_to_list_and_tracks_tools_usage_real_one](https://www.reddit.com/r/selfhosted/comments/1c0fcip/service_to_list_and_tracks_tools_usage_real_one)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T06:57:50+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>We all have a drill at home. But it works on average 4 minutes per year. So why not share it with neighbors, friends or colleagues?<br /> I am therefore looking for a service which would allow several users to register the tools they own (with various informations attached such as the last time the battery was changed, or who have paid the last fix and the cost), and allow everyone to follow on a calendar the borrowing of the tools. </p> <p>Do you know if something like this already exists as self-hosted open source? </p> <p>Best regards (from france, sorry for the automatic translation ;-)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PiMaVie"> /u/PiMaVie </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0fcip/service_to_list_and_tracks_tools_usage_real_one/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0fcip/service_to_list_and_tracks

## a self hosted secrets sharing service
 - [https://www.reddit.com/r/selfhosted/comments/1c0fbpm/a_self_hosted_secrets_sharing_service](https://www.reddit.com/r/selfhosted/comments/1c0fbpm/a_self_hosted_secrets_sharing_service)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T06:56:14+00:00

<!-- SC_OFF --><div class="md"><p>Hi <a href="/r/selfhosted">/r/selfhosted</a>,</p> <p>Currently self hosting VaultWarden (Open source implementation of the Bitwarden server API) and for security reasons (good practices in self hosting a password manager) I like to keep it behind a firewall only to be accessed by myself and my family through Headscale (Open source implementation of the Tailscale server API) and I'm wondering if there is a way to send and receive secrets from outside (perhaps a separate self hosted service) that would allow me to share and take secrets in from others in a secure fashion without having to expose my password manager outside to the public internet.</p> <p>&#x200b;</p> <p>Much appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ollivierre"> /u/ollivierre </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0fbpm/a_self_hosted_secrets_sharing_service/">[link]</a></span> &#32; <span><a href

## Self-Hosted Alternatives to Popular Services
 - [https://www.reddit.com/r/selfhosted/.rss](https://www.reddit.com/r/selfhosted/.rss)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T06:41:36.962393+00:00

A place to share, discuss, discover, assist with, gain assistance for, and critique self-hosted alternatives to our favorite web apps, web services, and online tools.

## Y
 - [https://www.reddit.com/r/selfhosted/comments/1c0f0eh/y](https://www.reddit.com/r/selfhosted/comments/1c0f0eh/y)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T06:34:50+00:00

<!-- SC_OFF --><div class="md"><p>T</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Responsible-Main-456"> /u/Responsible-Main-456 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0f0eh/y/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0f0eh/y/">[comments]</a></span>

## Plattform to manage Media files (Images, Videos,...) with tags for multiple users
 - [https://www.reddit.com/r/selfhosted/comments/1c0ez2y/plattform_to_manage_media_files_images_videos](https://www.reddit.com/r/selfhosted/comments/1c0ez2y/plattform_to_manage_media_files_images_videos)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T06:32:21+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>i am looking for a free (or &quot;cheap&quot;) self-hosted software to manage massive amounts of images, videos and other media data for internal use to manage all our product media and make them available company wide.</p> <p><strong>Currently we have</strong></p> <ul> <li>normal windows folder structure with 14.000+ folders</li> <li>including more than 200.000+ files (mostly images and videos, but also pdfs etc)</li> <li>1,5+ TB data and growing</li> </ul> <p><strong>Basically what i need is:</strong></p> <ul> <li>tagging / catagorize images</li> <li>download media files</li> <li>global search</li> <li>different user rights (read-only / download, edit, etc)</li> <li>self-hosted</li> <li>My idea is, to keep the current folder structure and just have a browser-based software indexing all these files.</li> </ul> <p>For my personal use, I used to use Adobe Lightroom with its tagging, categoriy feature, which is basically exactly wha

## What can I do with a router that I cannot do with say Pi-Hole or Adguard?
 - [https://www.reddit.com/r/selfhosted/comments/1c0exwf/what_can_i_do_with_a_router_that_i_cannot_do_with](https://www.reddit.com/r/selfhosted/comments/1c0exwf/what_can_i_do_with_a_router_that_i_cannot_do_with)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T06:30:24+00:00

<!-- SC_OFF --><div class="md"><p>As the title suggests, does having a self hosted router, say PfSense, give me any additional level of control that a Pi-Hole or an Adguard does not?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Youm_a"> /u/Youm_a </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0exwf/what_can_i_do_with_a_router_that_i_cannot_do_with/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0exwf/what_can_i_do_with_a_router_that_i_cannot_do_with/">[comments]</a></span>

## How much does it typically cost to self host a free software?
 - [https://www.reddit.com/r/selfhosted/comments/1c0e4qp/how_much_does_it_typically_cost_to_self_host_a](https://www.reddit.com/r/selfhosted/comments/1c0e4qp/how_much_does_it_typically_cost_to_self_host_a)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T05:39:50+00:00

<!-- SC_OFF --><div class="md"><p>I know that there is probably no &quot;typical&quot;, but self hosting has always baffled me. </p> <p>On one hand, the license is free. But on the other hand you have to pay for the servers. Most likely, your single tenant hosting is hardly utilized, so the cost per request / record / anything is likely to be higher than what the hosted solution costs for the company that builds it. </p> <p>Anyway, from your experience, given a small tenant, how much would it cost to host a free docker and some db. Appreciate any insights.</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FairStatistician3192"> /u/FairStatistician3192 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0e4qp/how_much_does_it_typically_cost_to_self_host_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0e4qp/how_much_does_it_typically_cost_to_self_host_a/">[comments]</a></s

## Is my backup strategy secure? Help needed
 - [https://www.reddit.com/r/selfhosted/comments/1c0dsjl/is_my_backup_strategy_secure_help_needed](https://www.reddit.com/r/selfhosted/comments/1c0dsjl/is_my_backup_strategy_secure_help_needed)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T05:19:02+00:00

<!-- SC_OFF --><div class="md"><p>I'm running a few docker compose services on my home server, along with all my family photos, and I'm looking at how to back this data up.</p> <p>I currently have two drives: a 512GiB SSD, and a 4TiB HDD, and I'm looking to add another 4TiB HDD.</p> <p>My idea was to have a 4TiB HDD as a repository for Kopia, which would take regular backups of all the valuable data on the first two drives, and then use Rclone to copy those backups to the cloud. Would this work? Is there a single piece of software that can provide both a web UI and local+cloud backups?</p> <p>If you have any better ideas I'd be very grateful. Also, I've seen Duplicati, Restic, and BorgBackup mentioned - how do these compare to Kopia? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/_Sworld_"> /u/_Sworld_ </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0dsjl/is_my_backup_strategy_secure_help_needed/">[link]</a></span> &#3

## Why such fancy homepages? Lazy and minimalist is good enough for me.
 - [https://www.reddit.com/r/selfhosted/comments/1c0dnyi/why_such_fancy_homepages_lazy_and_minimalist_is](https://www.reddit.com/r/selfhosted/comments/1c0dnyi/why_such_fancy_homepages_lazy_and_minimalist_is)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T05:11:43+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c0dnyi/why_such_fancy_homepages_lazy_and_minimalist_is/"> <img alt="Why such fancy homepages? Lazy and minimalist is good enough for me." src="https://preview.redd.it/w4zio3995ltc1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=c78db81f16e1ff85fbfadd50783b934d2d379b73" title="Why such fancy homepages? Lazy and minimalist is good enough for me." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sweaty-Gopher"> /u/Sweaty-Gopher </a> <br /> <span><a href="https://i.redd.it/w4zio3995ltc1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0dnyi/why_such_fancy_homepages_lazy_and_minimalist_is/">[comments]</a></span> </td></tr></table>

## Self host blog or code?
 - [https://www.reddit.com/r/selfhosted/comments/1c0dc7a/self_host_blog_or_code](https://www.reddit.com/r/selfhosted/comments/1c0dc7a/self_host_blog_or_code)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T04:52:32+00:00

<!-- SC_OFF --><div class="md"><p>I recently came across this blog <a href="https://akashrajpurohit.com/blog/ansible-infrastructure-as-a-code-for-building-up-my-homelab/?ref=reddit">https://akashrajpurohit.com/blog/ansible-infrastructure-as-a-code-for-building-up-my-homelab/?ref=reddit</a>. The page looks amazing, is that coded his self or is there anything I can use to do such thing and articles as wells</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/littleblack11111"> /u/littleblack11111 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0dc7a/self_host_blog_or_code/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0dc7a/self_host_blog_or_code/">[comments]</a></span>

## Komga media server errors after restarting my windows PC
 - [https://www.reddit.com/r/selfhosted/comments/1c0cwgj/komga_media_server_errors_after_restarting_my](https://www.reddit.com/r/selfhosted/comments/1c0cwgj/komga_media_server_errors_after_restarting_my)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T04:27:19+00:00

<!-- SC_OFF --><div class="md"><p>Noob here. I use my windows 10 PC to host comics and books with Komga media server. I installed it through windows store. it worked fine until I had to turn off my PC. once I restarted, Komga disappears from the tray and I can't access. need help</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nandy000032467"> /u/nandy000032467 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0cwgj/komga_media_server_errors_after_restarting_my/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0cwgj/komga_media_server_errors_after_restarting_my/">[comments]</a></span>

## Need help setting up budget NAS with Router on Old hardware.
 - [https://www.reddit.com/r/selfhosted/comments/1c0c6ri/need_help_setting_up_budget_nas_with_router_on](https://www.reddit.com/r/selfhosted/comments/1c0c6ri/need_help_setting_up_budget_nas_with_router_on)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T03:48:24+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/sharath_babu"> /u/sharath_babu </a> <br /> <span><a href="/r/homelab/comments/1bzwwwv/need_help_setting_up_budget_nas_with_router/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0c6ri/need_help_setting_up_budget_nas_with_router_on/">[comments]</a></span>

## Need help with webscrapper
 - [https://www.reddit.com/r/selfhosted/comments/1c0bs4h/need_help_with_webscrapper](https://www.reddit.com/r/selfhosted/comments/1c0bs4h/need_help_with_webscrapper)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T03:27:26+00:00

<!-- SC_OFF --><div class="md"><p>I am working on writing a python script for a web scrapper that will scrap provided domain for specific keywords and store result once scrapping is completed. I've used b4s ,requests. I am fairly new to python. Challenges facing: 1. Script is Too slow 2. Not user friendly 3. Do not crawl all the endpoint so less efficiency.</p> <p>Do you know any repo that will help me or do something similar stuff?? TIA.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Consistent-Time-6086"> /u/Consistent-Time-6086 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0bs4h/need_help_with_webscrapper/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c0bs4h/need_help_with_webscrapper/">[comments]</a></span>

## what can i use for save short texts (like notes) with title?
 - [https://www.reddit.com/r/selfhosted/comments/1c096x2/what_can_i_use_for_save_short_texts_like_notes](https://www.reddit.com/r/selfhosted/comments/1c096x2/what_can_i_use_for_save_short_texts_like_notes)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T01:20:47+00:00

<!-- SC_OFF --><div class="md"><p>HI.</p> <p>I just install microbin, thinking that this was what i want. But, nop, because i need to make little notes, for later read them (like some to-do for example), and in microbin you cant put them a title (like a reference) then i have to open every note to see what i wrote.</p> <p>So, what would be a good app to serve?</p> <p>Thanks!</p> <p>EDIT: i would like that the &quot;note/post&quot; autodestroy after some x time, a week or whatever.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/9acca9"> /u/9acca9 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c096x2/what_can_i_use_for_save_short_texts_like_notes/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c096x2/what_can_i_use_for_save_short_texts_like_notes/">[comments]</a></span>

## What does good documentation look like?
 - [https://www.reddit.com/r/selfhosted/comments/1c08eur/what_does_good_documentation_look_like](https://www.reddit.com/r/selfhosted/comments/1c08eur/what_does_good_documentation_look_like)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T00:44:30+00:00

<!-- SC_OFF --><div class="md"><p>I don't work in software at all and the only documentation I've had to write is for my own home server, on my home server. I'd like to just see some examples of what good documentation looks like to help me format my documents. Can anyone post examples?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/burger4d"> /u/burger4d </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c08eur/what_does_good_documentation_look_like/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c08eur/what_does_good_documentation_look_like/">[comments]</a></span>

## How did you get here?
 - [https://www.reddit.com/r/selfhosted/comments/1c07gko/how_did_you_get_here](https://www.reddit.com/r/selfhosted/comments/1c07gko/how_did_you_get_here)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-10T00:01:02+00:00

<!-- SC_OFF --><div class="md"><p>For myself. I was using arch for a very long time and got a sphere computer so I wanted to host a Minecraft server on it. It’s only been a Minecraft server for like 2years then I joined this sub and know stuff like vaultwarden, WireGuard etc😂</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/littleblack11111"> /u/littleblack11111 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c07gko/how_did_you_get_here/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c07gko/how_did_you_get_here/">[comments]</a></span>

