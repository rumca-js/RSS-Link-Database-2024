# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Hardening Minecraft instance
 - [https://www.reddit.com/r/selfhosted/comments/1fatopn/hardening_minecraft_instance](https://www.reddit.com/r/selfhosted/comments/1fatopn/hardening_minecraft_instance)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T23:52:11+00:00

<!-- SC_OFF --><div class="md"><p>Hello - looking for a sanity check on how I have a self hosted Minecraft instance for my kids and their cousins. </p> <p>Little paranoid about exposing the service to the public internet. I have performed the following to secure the instance. What keeps me up at night is that everything I have in place is there to protect against a compromised instance (i.e., reactive mitigation), not prevent compromise. Any suggestions beyond what’s already in place? </p> <ul> <li>Running on an up to date Ubuntu 24.04 LTS virtual machine</li> <li>VM is in a DMZ VLAN with no access to other VLANs (and no other hosts exist in that VLAN)</li> <li>DMZ VLAN does not have internet access (i.e., prevent egress of C2 channels)</li> <li>Firewall only accepts US geo inbound connections</li> <li>Minecraft service operating on a non standard, high UDP port</li> <li>OS user with sudo privs to admin host, unique pw</li> <li>OS user with no privs, unique pw, runs the Minecraft serv

## Clace - Application Server with support for scaling down to zero
 - [https://www.reddit.com/r/selfhosted/comments/1fat2hw/clace_application_server_with_support_for_scaling](https://www.reddit.com/r/selfhosted/comments/1fat2hw/clace_application_server_with_support_for_scaling)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T23:22:44+00:00

<!-- SC_OFF --><div class="md"><p>I have been building the open source project <a href="https://github.com/claceio/clace">Clace</a>. Clace is an application server that builds and deploys containers, allowing it to manage webapps in any language/framework.</p> <p>In comparison with Nginx Unix and other application servers, Clace has the advantage of being able to work with any application, without requiring any dependency or packaging changes. Clace provides a blue-green staged deployment model for apps. Not just code changes, even configuration changes are staged and can be verified before being made live.</p> <p>Clace is not a PaaS solution, it does not support deploying databases and other auxiliary services. It does share the fact that it manages containers with PaaS solutions. Clace is different in that it builds its own reverse proxy, instead of depending on Traefik/Nginx. This allows Clace to implement features like shutting down idle apps and adding app level OAuth authenticat

## Do any of y’all hook into home triggers with your hosting setup? If so anyone bootstrap from that?
 - [https://www.reddit.com/r/selfhosted/comments/1fat0ai/do_any_of_yall_hook_into_home_triggers_with_your](https://www.reddit.com/r/selfhosted/comments/1fat0ai/do_any_of_yall_hook_into_home_triggers_with_your)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T23:19:51+00:00

<!-- SC_OFF --><div class="md"><p>After many years of hosting stuff in cloud providers, I want to move the cloud to my home, and maybe help others do the same. </p> <p>To that end I’m looking to setup a system that bootstraps itself to a service running in a container like nix or docker. That seems like well-trodden territory on this sub, but of course additional advice would be welcome. </p> <p>The part I’m not so sure about is that I’d like to trigger the bootstrap from some proximal user input via NFC, BLE, or tapping into one of the home automation providers. Is anyone doing, or has done anything like that?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CurvatureTensor"> /u/CurvatureTensor </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fat0ai/do_any_of_yall_hook_into_home_triggers_with_your/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fat0ai/do_any_of_yall_hook_into_home_trig

## Anyone using a "menu" webpage for indexing your locally hosted apps?
 - [https://www.reddit.com/r/selfhosted/comments/1fasgb9/anyone_using_a_menu_webpage_for_indexing_your](https://www.reddit.com/r/selfhosted/comments/1fasgb9/anyone_using_a_menu_webpage_for_indexing_your)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T22:54:13+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve got a few self hosted apps (Emby, etc) that have specific URL&#39;s for each.. I&#39;d like an easy to use dashboard (not sure of a better name) of sorts that can have links to each of the services that are hosted. </p> <p>I&#39;ve tried homepage and looked at homarr and others and am not quite fond of them for one reason or another .. I really just want glorified links and yeah I could build my own from scratch, but am wondering if there&#39;s something out there already in a docker container I could make use of? </p> <p>I don&#39;t really need metrics or anything like most dashboard apps do.. </p> <p>ps. this will be used behind a VPN (not exposed to the internet at large)</p> <p>thoughts?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Impressive-Pin-4129"> /u/Impressive-Pin-4129 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fasgb9/anyone_using_a_menu_webpage_for_indexing_you

## Air Live Drive On a UTM Virtual Machine? ( Windows 11 )
 - [https://www.reddit.com/r/selfhosted/comments/1fas2ez/air_live_drive_on_a_utm_virtual_machine_windows_11](https://www.reddit.com/r/selfhosted/comments/1fas2ez/air_live_drive_on_a_utm_virtual_machine_windows_11)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T22:36:10+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to get Air Live Drive to work on my Virtual Machine. I am getting an error that says it is having an error connecting mega and that it cannot connect the Dokan driver </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ComprehensiveFuel234"> /u/ComprehensiveFuel234 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fas2ez/air_live_drive_on_a_utm_virtual_machine_windows_11/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fas2ez/air_live_drive_on_a_utm_virtual_machine_windows_11/">[comments]</a></span>

## I'm lost and need your help... ParsonLabs Music
 - [https://www.reddit.com/r/selfhosted/comments/1faqvwi/im_lost_and_need_your_help_parsonlabs_music](https://www.reddit.com/r/selfhosted/comments/1faqvwi/im_lost_and_need_your_help_parsonlabs_music)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T21:43:23+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1faqvwi/im_lost_and_need_your_help_parsonlabs_music/"> <img src="https://external-preview.redd.it/gYyMaiwsIkl5zk0wjCxkMcHS9cVHKJqQSBNJPa3OIqQ.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=4ba19e124314bc38c93eedac224430e3fbf9d9cb" alt="I'm lost and need your help... ParsonLabs Music" title="I'm lost and need your help... ParsonLabs Music" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>For the past months, I have been searching for a good self hosted music streaming service, but my impression was that some of them were outdated and others didn&#39;t have some nice haves that I would like in a music app, like I was using YouTube Music or Spotify but self hosted.</p> <p>I then decided, like any &quot;normal&quot; person, to create my own, but it became increasingly clear that I simply don&#39;t know what I am doing in terms of quality assurance and making sure it was familiar (or at least similar) to what we kn

## Redis: Send logs to stdout
 - [https://www.reddit.com/r/selfhosted/comments/1faqpom/redis_send_logs_to_stdout](https://www.reddit.com/r/selfhosted/comments/1faqpom/redis_send_logs_to_stdout)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T21:35:41+00:00

<!-- SC_OFF --><div class="md"><p>This is going to be a very basic question, but how can I set Redis to send logs to stdout.</p> <p>Currently, I get zero logs from Redis (alphine).</p> <p>I&#39;ve looked for logs in portainer, as well as <code>docker logs redis</code> and both are blank.</p> <p>I&#39;ve even ensured in my redis.conf that I have the logfile value empty / set to &quot;&quot;. According to numerous docs, if that value is empty, it should be sending logs to stdout, but as I said, not even the docker logs command is working.</p> <p>When I run the command, it just prompts me to enter my next command.</p> <p>The only time I get logs to show is if I remove the volume:</p> <p><code> volumes: - ./redis/redis.conf:/usr/local/etc/redis/redis.conf </code></p> <p>Then the only log I get is: <code> Fatal error, can&#39;t open config file &#39;/usr/local/etc/redis/redis.conf&#39;: No such file or directory </code></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www

## Self-hosted "white pages" for a town.
 - [https://www.reddit.com/r/selfhosted/comments/1faqofr/selfhosted_white_pages_for_a_town](https://www.reddit.com/r/selfhosted/comments/1faqofr/selfhosted_white_pages_for_a_town)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T21:34:09+00:00

<!-- SC_OFF --><div class="md"><p>Since phonebooks are dead (assuming any existing ones are for landlines only and online search is a shitshow), what would be the best way for a town to self-host their own directory of phone numbers?</p> <p><a href="https://www.reddit.com/r/selfhosted/comments/tnn7ak/looking_for_a_personal_crm/">This post</a> was interesting when looking at it as a &quot;personal CRM.&quot;</p> <p>Is that the best way of looking at something like this for a small town? I&#39;ve tried SuiteCRM before and it&#39;s heavy-duty. Baserow a little heavy too. I&#39;m intrigued by the mention of logseq.</p> <p>Any recommendations? Thanks and have a good weekend!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Losconquistadores"> /u/Losconquistadores </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1faqofr/selfhosted_white_pages_for_a_town/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/co

## SiPeed say they'll open source NanoKVM firmware if repo gets 2K ⭐
 - [https://www.reddit.com/r/selfhosted/comments/1faqdsn/sipeed_say_theyll_open_source_nanokvm_firmware_if](https://www.reddit.com/r/selfhosted/comments/1faqdsn/sipeed_say_theyll_open_source_nanokvm_firmware_if)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T21:21:08+00:00

<!-- SC_OFF --><div class="md"><p>Go star ⭐ <a href="https://github.com/sipeed/NanoKVM">https://github.com/sipeed/NanoKVM</a></p> <p><strong>Details</strong>: <a href="https://github.com/sipeed/NanoKVM/issues/1#issuecomment-2334652686">https://github.com/sipeed/NanoKVM/issues/1#issuecomment-2334652686</a> </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/automatepete"> /u/automatepete </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1faqdsn/sipeed_say_theyll_open_source_nanokvm_firmware_if/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1faqdsn/sipeed_say_theyll_open_source_nanokvm_firmware_if/">[comments]</a></span>

## Looking for the better of the document apps
 - [https://www.reddit.com/r/selfhosted/comments/1faqafp/looking_for_the_better_of_the_document_apps](https://www.reddit.com/r/selfhosted/comments/1faqafp/looking_for_the_better_of_the_document_apps)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T21:17:05+00:00

<!-- SC_OFF --><div class="md"><p>Looking to de-googlefy my docments, </p> <p>Is there word doc, excel sheet, pdf server/manager to use to replace Google doc for create docs or opening them. Or even notes. What pros and cons are there to them and is there a way to access it off site? That&#39;s not a opening up my ip address</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Trueleo1"> /u/Trueleo1 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1faqafp/looking_for_the_better_of_the_document_apps/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1faqafp/looking_for_the_better_of_the_document_apps/">[comments]</a></span>

## Add module to Nginx Plesk Ubuntu
 - [https://www.reddit.com/r/selfhosted/comments/1faq8f4/add_module_to_nginx_plesk_ubuntu](https://www.reddit.com/r/selfhosted/comments/1faq8f4/add_module_to_nginx_plesk_ubuntu)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T21:14:41+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>For a little project i&#39;m trying to setup plesk with an Nginx reverse proxy on a vps that hosts a multitude of things.</p> <p>Remote desktop to Linux vps&#39;s &amp; windows vps&#39;s.</p> <p>Minecraft servers and a whole bunch of other game servers.</p> <p>I (after trail and error) became aware of the limitations of the Nginx installation that comes with Plesk due to it missing the stream module and it being a requirement to redirect other protocols.</p> <p>Now i thought it would be easy to just add the module but i&#39;ve ran into a brick wall.</p> <p>What i tried was:</p> <p>run:</p> <p><code>apt install libnginx-mod-stream</code> on the plesk server which semi worked however in the plesk UI i lose the Additional nginx directives making as it seems to just overwrite the whole nginx installation.</p> <p>Lastly i tried:</p> <p>copying the ngx_stream_module.so from an other installation to the plesk module location at &quot;/usr/shar

## Help Fix My Docker Mistake - Incorrect Volume Mount
 - [https://www.reddit.com/r/selfhosted/comments/1faq4ga/help_fix_my_docker_mistake_incorrect_volume_mount](https://www.reddit.com/r/selfhosted/comments/1faq4ga/help_fix_my_docker_mistake_incorrect_volume_mount)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T21:09:51+00:00

<!-- SC_OFF --><div class="md"><p>I have had Paperless ngx running as a container for way over a year now and love it however I&#39;ve just noticed that I haven&#39;t properly mounted the volumes for the &#39;db&#39; and &#39;broker&#39; part of the container.</p> <p>i have the following folder structure:</p> <p>--volume1<br/> ----docker<br/> -------paperless<br/> -----------webserver<br/> -----------broker<br/> -----------db</p> <p>however it seems like the broker and db mounts have been configured incorrectly.</p> <p>Extract of the relevant parts of the docker-compose file:</p> <pre><code> broker: container_name: paperless-broker volumes: - redisdata:/data db: container_name: paperless-db volumes: - pgdata:/var/lib/postgresql/data webserver: volumes: - /volume1/docker/paperless/data:/usr/src/paperless/data - /volume1/docker/paperless/media:/usr/src/paperless/media - /volume1/docker/paperless/export:/usr/src/paperless/export - /volume1/docker/paperless/consume:/usr/src/paperless/cons

## Best DDoS Protected VPS Hosting for GRE into Home-Network
 - [https://www.reddit.com/r/selfhosted/comments/1faq4em/best_ddos_protected_vps_hosting_for_gre_into](https://www.reddit.com/r/selfhosted/comments/1faq4em/best_ddos_protected_vps_hosting_for_gre_into)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T21:09:48+00:00

<!-- SC_OFF --><div class="md"><p>I need a US-Central VPS that is DDoS Protected to create a GRE tunnel into my home network, I need additional ips for my server rack, I&#39;m trying to setup my own Xeon units, but ddos protected ips is a must, please provide some assistance if possible.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Leading_Pumpkin_2559"> /u/Leading_Pumpkin_2559 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1faq4em/best_ddos_protected_vps_hosting_for_gre_into/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1faq4em/best_ddos_protected_vps_hosting_for_gre_into/">[comments]</a></span>

## YaCy - Worth it or not?
 - [https://www.reddit.com/r/selfhosted/comments/1fapiu7/yacy_worth_it_or_not](https://www.reddit.com/r/selfhosted/comments/1fapiu7/yacy_worth_it_or_not)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T20:44:18+00:00

<!-- SC_OFF --><div class="md"><p>So there&#39;s this decentralized search engine called <a href="https://yacy.net">YaCy</a>. The appeal is that unlike SearXNG it is a search engine and provides uncensored search results, unlike big tech engines or stuff based on them.</p> <p>How bad is it compared to google &amp; stuff? Are there any [better] alternatives?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kvas_"> /u/kvas_ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fapiu7/yacy_worth_it_or_not/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fapiu7/yacy_worth_it_or_not/">[comments]</a></span>

## Hosting express/MERN stack on 2 € a month VPS
 - [https://www.reddit.com/r/selfhosted/comments/1fapex9/hosting_expressmern_stack_on_2_a_month_vps](https://www.reddit.com/r/selfhosted/comments/1fapex9/hosting_expressmern_stack_on_2_a_month_vps)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T20:39:44+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I want to host MERN stack apps on IONOS Vps Linux Xs tier with 1gb of ram and 1 vCpu I&#39;m gonna use it to host a MERN stack app, and if possible I might want to also do things like Dokku Is it sufficient for my purpose? And, are there any better alternatives (no annual billing ones please, max 3 months billing) (And if it matters, I&#39;m probably gonna use Docker)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Hektor_Gaming"> /u/Hektor_Gaming </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fapex9/hosting_expressmern_stack_on_2_a_month_vps/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fapex9/hosting_expressmern_stack_on_2_a_month_vps/">[comments]</a></span>

## I can only access one email in Roundcube
 - [https://www.reddit.com/r/selfhosted/comments/1faog8k/i_can_only_access_one_email_in_roundcube](https://www.reddit.com/r/selfhosted/comments/1faog8k/i_can_only_access_one_email_in_roundcube)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T19:59:41+00:00

<!-- SC_OFF --><div class="md"><p>All of a sudden I&#39;m having issues with my emails.</p> <p>I access my domain emails via Roundcube. The one email address - no problem. Opens on computer (I use Chrome). The other email address doesn&#39;t open, when trying I get the message: </p> <p>This page isn’t working</p> <p><strong>webmail.(website).co</strong>.za redirected you too many times.</p> <ul> <li><a href="https://support.google.com/chrome?p=rl_error&amp;hl=en-US">Try deleting your cookies</a>.</li> </ul> <p>ERR_TOO_MANY_REDIRECTS</p> <p>Both emails can be accessed on my Android phone.</p> <p>This is driving me up the wall - I want to access my emails on my computer too.</p> <p>Don&#39;t know if this is relevant, but my OS is Peppermint, not Windows.</p> <p>Please help!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Lakataleadolma"> /u/Lakataleadolma </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1faog8k/i_can_only_acce

## How do software like teamviewer and chrome remote desktop allow you to access your PC remotely without setting up a port forward ?
 - [https://www.reddit.com/r/selfhosted/comments/1faobge/how_do_software_like_teamviewer_and_chrome_remote](https://www.reddit.com/r/selfhosted/comments/1faobge/how_do_software_like_teamviewer_and_chrome_remote)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T19:54:10+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Sea_Copy8488"> /u/Sea_Copy8488 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1faobge/how_do_software_like_teamviewer_and_chrome_remote/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1faobge/how_do_software_like_teamviewer_and_chrome_remote/">[comments]</a></span>

## How do I create a login for a site hosted in docker behind NPM?
 - [https://www.reddit.com/r/selfhosted/comments/1fan4e5/how_do_i_create_a_login_for_a_site_hosted_in](https://www.reddit.com/r/selfhosted/comments/1fan4e5/how_do_i_create_a_login_for_a_site_hosted_in)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T19:03:45+00:00

<!-- SC_OFF --><div class="md"><p>I have a docker stack with firefox running in it connected to my VPN. It doesn&#39;t have a built in login. How would I add a login page so I can expose it to the internet and keep strangers out? </p> <p>Thanks for the help!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TwoDogDad"> /u/TwoDogDad </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fan4e5/how_do_i_create_a_login_for_a_site_hosted_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fan4e5/how_do_i_create_a_login_for_a_site_hosted_in/">[comments]</a></span>

## Help needed, unreachable service
 - [https://www.reddit.com/r/selfhosted/comments/1famzyd/help_needed_unreachable_service](https://www.reddit.com/r/selfhosted/comments/1famzyd/help_needed_unreachable_service)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T18:58:47+00:00

<!-- SC_OFF --><div class="md"><p>I use a WiFi extender to ensure my server gets sweet sweet bandwidth, today the extender stopped working (connects but no internet) so I decided to connect my server to the main WiFi. Gone into the router, assigned a static IP address as you would.</p> <p>I can ping the server, replies with good stats and I thought all is well. Alas, I cannot reach my services anymore, for example:</p> <p>I can ping the server IP on 192.168.1.80 but cannot reach Dashy on 192.168.1.80:12345.</p> <p>However, I can reach Dashy through Tailscale on 10.10.20.30:12345 (obviously not real IP, but you get the point).</p> <p>I don&#39;t know where to start troubleshooting, anyone experienced something similar willing to share ideas or someone with a possible solution? Help</p> <p>Info: running Docker on Windows 10, Docker not the issue as I can&#39;t reach jellyfin which is it&#39;s own installation via exe.</p> <p>I had access to the apps prior to the network switch, I am usi

## self-hosted alternative to untappd and vivino
 - [https://www.reddit.com/r/selfhosted/comments/1famwvz/selfhosted_alternative_to_untappd_and_vivino](https://www.reddit.com/r/selfhosted/comments/1famwvz/selfhosted_alternative_to_untappd_and_vivino)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T18:55:04+00:00

<!-- SC_OFF --><div class="md"><p>hello. i was looking for some alternatives to untappd and vivino but i can&#39;t find something that are close. is there something like those app in self-hosted land?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dull_Course_9076"> /u/Dull_Course_9076 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1famwvz/selfhosted_alternative_to_untappd_and_vivino/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1famwvz/selfhosted_alternative_to_untappd_and_vivino/">[comments]</a></span>

## Is there a local video management solution for body camera footage?
 - [https://www.reddit.com/r/selfhosted/comments/1famvt4/is_there_a_local_video_management_solution_for](https://www.reddit.com/r/selfhosted/comments/1famvt4/is_there_a_local_video_management_solution_for)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T18:53:51+00:00

<!-- SC_OFF --><div class="md"><p>I run a non-profit in Ontario, Canada and one of the primary activities we do is outreach work with people living homeless in the community. </p> <p>After a few encounters and much internal discussion, we decided to deploy body worn cameras for all staff and volunteers doing outreach. This is to protect everyone including the people we work with and all video collected is treated as confidential. Luckily, we were provided 4 d-series cameras from Reveal Media. Unfortunately they couldn’t provide the video management software which is totally understandable. </p> <p>I am looking for a self hosted solution to manage all the video and ideally do some sort of ai analytics like transcription. That way we can flag any issues and avoid manual review. Being able to effectively manage video collected would be tremendously helpful. I was thinking of using NVR software though I know that’ll be an uphill battle. </p> <p>I’ve also looked into cloud solutions but wi

## Back up question
 - [https://www.reddit.com/r/selfhosted/comments/1falcen/back_up_question](https://www.reddit.com/r/selfhosted/comments/1falcen/back_up_question)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T17:48:28+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I have a UGREEN NAS with 40 TB of data running raid. I plan on doing a back up of it and now my question is how do I do another physical hard drive back up? Sorry I’m new to storing large data. Do I just get an external hard drive reader and store it there or should I get another NAS to store it? Would love to know how you guys do it and what your thoughts! Thank you</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/linbeg"> /u/linbeg </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1falcen/back_up_question/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1falcen/back_up_question/">[comments]</a></span>

## This goes out to all the open and closeted Plex shills out there. Happy Friday!
 - [https://www.reddit.com/r/selfhosted/comments/1fakrng/this_goes_out_to_all_the_open_and_closeted_plex](https://www.reddit.com/r/selfhosted/comments/1fakrng/this_goes_out_to_all_the_open_and_closeted_plex)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T17:24:09+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fakrng/this_goes_out_to_all_the_open_and_closeted_plex/"> <img src="https://preview.redd.it/n8ah0u8v38nd1.jpeg?width=320&amp;crop=smart&amp;auto=webp&amp;s=29fcc8159705ab58a080fcc440be64167a39caf8" alt="This goes out to all the open and closeted Plex shills out there. Happy Friday!" title="This goes out to all the open and closeted Plex shills out there. Happy Friday!" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cloudswithflaire"> /u/cloudswithflaire </a> <br/> <span><a href="https://i.redd.it/n8ah0u8v38nd1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fakrng/this_goes_out_to_all_the_open_and_closeted_plex/">[comments]</a></span> </td></tr></table>

## What options are there for online shared document editting?
 - [https://www.reddit.com/r/selfhosted/comments/1fak4aw/what_options_are_there_for_online_shared_document](https://www.reddit.com/r/selfhosted/comments/1fak4aw/what_options_are_there_for_online_shared_document)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T16:56:36+00:00

<!-- SC_OFF --><div class="md"><p>Myself and my partner currently make heavy use of Google&#39;s suite of Docs, Sheets, and Slides for working together (e.g., editting together in realtime). I&#39;d like to look into trading in Google Drive for a self hosted solution, but this aspect of drive is one that I haven&#39;t landed on a good answer.</p> <p>I know Nextcloud has an answer, but due to a variety of shortcomings (it gets posted frequently so I wont reiterate), I am attempting to avoid Nextcloud if possible.</p> <p>Synology I think also has some options, but I am not sure if their hardware is required for that (I am not using their hardware atm).</p> <p>I see Seafile mentioned as an alternative to Nextcloud, but appears to be more for read access and upload/download instead of edits.</p> <p>Anyone have a setup they can suggest? Or does Google not have many rivals in this specific use case?</p> <p>Thanks!</p> <p><em>(Apologies if wrong flair)</em></p> </div><!-- SC_ON --> &#32; sub

## Paperless(-NG(X)) on QNAP
 - [https://www.reddit.com/r/selfhosted/comments/1fajvym/paperlessngx_on_qnap](https://www.reddit.com/r/selfhosted/comments/1fajvym/paperlessngx_on_qnap)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T16:46:44+00:00

<!-- SC_OFF --><div class="md"><p>Hi! Has anyone managed to run Paperless (or Paperless-NG or NGX) on a QNAP TS-364 or similar (Intel Celeron based, compatible with Docker)? If so, which Docker image did you use that has all the Paperless functions? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BarajasFernando"> /u/BarajasFernando </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fajvym/paperlessngx_on_qnap/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fajvym/paperlessngx_on_qnap/">[comments]</a></span>

## Any luck in contacting Domain.com customer support?
 - [https://www.reddit.com/r/selfhosted/comments/1fajtiu/any_luck_in_contacting_domaincom_customer_support](https://www.reddit.com/r/selfhosted/comments/1fajtiu/any_luck_in_contacting_domaincom_customer_support)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T16:43:52+00:00

<!-- SC_OFF --><div class="md"><p>I purchased a domain and mistakenly entered the wrong email to set up my account. I&#39;ve attempted their listed phone number, which is no longer in service, and their chat function is unfortunately disabled. Thus far, I have no way of accessing my domain space and am out of ideas for resolving this. </p> <p>Any suggestions? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/trickycurrents"> /u/trickycurrents </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fajtiu/any_luck_in_contacting_domaincom_customer_support/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fajtiu/any_luck_in_contacting_domaincom_customer_support/">[comments]</a></span>

## Explain to an idiot (me) how to remote boot and control a PC
 - [https://www.reddit.com/r/selfhosted/comments/1fajkrh/explain_to_an_idiot_me_how_to_remote_boot_and](https://www.reddit.com/r/selfhosted/comments/1fajkrh/explain_to_an_idiot_me_how_to_remote_boot_and)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T16:33:46+00:00

<!-- SC_OFF --><div class="md"><p>So yep i wanna play games and all outside of home like at my father&#39;s home but let&#39;s be real buying a gaming pc just to play games occasionally is not worth it. Soo i wanna know what do i need to setup (and maybe buy for the booting part) to use my PC remotely. I also wanna know the limits of remote control, the internet connexion required for a 1080p 144hz screen, the PC hardware required on the reciever part to manage that and what happens if i don&#39;t have enough internet speed to recieve all of the 144 frames per second (like does it still work just at less frames per second or does it do wierd stuff like mixing images and creating &quot;colorful pixel cry for help&quot;)</p> <p>By the way i&#39;m an absolute newbie in that topic so explain to me like i&#39;m a newborn, retarded, or both</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/APOI_"> /u/APOI_ </a> <br/> <span><a href="https://www.reddit.com

## GPU Passthrough on a Hetzner Dedicated Server
 - [https://www.reddit.com/r/selfhosted/comments/1faip4t/gpu_passthrough_on_a_hetzner_dedicated_server](https://www.reddit.com/r/selfhosted/comments/1faip4t/gpu_passthrough_on_a_hetzner_dedicated_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T15:57:45+00:00

<!-- SC_OFF --><div class="md"><p>Not sure if this is the place to ask but I have a Hetzner EX44 with:</p> <ul> <li>Intel® Core™ i5-13500</li> <li>64 GB DDR4</li> <li>2 x 512 GB (Gen4)</li> </ul> <p>and I want to have around 10 android virtual machines running with gpu being passed through.</p> <p>(my plan is to run roblox on the vm&#39;s, don&#39;t ask why :))</p> <p>I&#39;ve tried: </p> <ul> <li>SR-IOV which I&#39;ve gotten nowhere with it but I&#39;ll try again</li> <li>(I know this sounds stupid) Making a singular Windows VM with the gpu passed through and then using an app like MuMu Player to have android running but trying to boot windows with the gpu host passthrough being a black screen.</li> <li>Installed Proxmox but couldn&#39;t get networking running since Hetzner only provides you with 1 IP, probably do-able but regardless of networking the GPU didn&#39;t get passed through</li> </ul> <p>Any Ideas or suggestions are open, I know this might not be classified as &quot;self h

## Looking for a editable pastebin which does not support multiple files. A single user, unencrypted, bulletin board which takes the user to the same file.
 - [https://www.reddit.com/r/selfhosted/comments/1faimre/looking_for_a_editable_pastebin_which_does_not](https://www.reddit.com/r/selfhosted/comments/1faimre/looking_for_a_editable_pastebin_which_does_not)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T15:54:53+00:00

<!-- SC_OFF --><div class="md"><p>I essentially want it to work like Google Docs works (minus any type of authentication) A notepad which is accessible only on my intranet. Something that works like <a href="https://pasteepad.com/">https://pasteepad.com/</a> but is open-source, and can be self-hosted.</p> <p>From the looks of it, I might have to code this myself?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/markraidc"> /u/markraidc </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1faimre/looking_for_a_editable_pastebin_which_does_not/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1faimre/looking_for_a_editable_pastebin_which_does_not/">[comments]</a></span>

## How to get an SSL certificate without exposing the firewall IP?
 - [https://www.reddit.com/r/selfhosted/comments/1fai6zm/how_to_get_an_ssl_certificate_without_exposing](https://www.reddit.com/r/selfhosted/comments/1fai6zm/how_to_get_an_ssl_certificate_without_exposing)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T15:36:25+00:00

<!-- SC_OFF --><div class="md"><p>Hello<br/> I’m looking to obtain an SSL certificate without exposing my firewall’s IP address. For example, I have the domain example.com, and I need to use a wildcard certificate to secure subdomains like proxmox.example.com for internal use. However, I don’t want anyone to be able to discover the IP address behind the domain. Is there a way to achieve this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/madloggan"> /u/madloggan </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fai6zm/how_to_get_an_ssl_certificate_without_exposing/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fai6zm/how_to_get_an_ssl_certificate_without_exposing/">[comments]</a></span>

## Monitoring and Analytics Tool
 - [https://www.reddit.com/r/selfhosted/comments/1fai187/monitoring_and_analytics_tool](https://www.reddit.com/r/selfhosted/comments/1fai187/monitoring_and_analytics_tool)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T15:29:47+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, looking for a monitoring/analytics tool similar to datadog. Anyone used or seen an oss/selfhosted alternative and can recommend said tool? Links etc. Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TraditionalExit3"> /u/TraditionalExit3 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fai187/monitoring_and_analytics_tool/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fai187/monitoring_and_analytics_tool/">[comments]</a></span>

## Best cloud service for self-hosted VPN?
 - [https://www.reddit.com/r/selfhosted/comments/1fahi9e/best_cloud_service_for_selfhosted_vpn](https://www.reddit.com/r/selfhosted/comments/1fahi9e/best_cloud_service_for_selfhosted_vpn)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T15:08:08+00:00

<!-- SC_OFF --><div class="md"><p>I don&#39;t have problem with logs or id verification. It has to be in the US.</p> <p>I read Oracle has a free tier, but some don&#39;t like Oracle and say sometimes they shut down the free server with no reason. Also, I&#39;m not sure if VPN is against Oracle terms.</p> <p>What about digital ocean, aws, etc?</p> <p>I wouldn&#39;t mind paying if there&#39;s a good reason.</p> <p>I&#39;m interested in a company whose IP range has good reputation. I would prefer to avoid a company who is know for having clients that abuse the service, and have their IPs flagged or black listed.</p> <p>Can you browse porn sites with a self-hosted VPN or is it against their terms? Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rockWithYouMichael"> /u/rockWithYouMichael </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fahi9e/best_cloud_service_for_selfhosted_vpn/">[link]</a></span> &#32; <span><a href="h

## Is there a way to automatically rip music from streaming services like Deezer using something like Lidarr?
 - [https://www.reddit.com/r/selfhosted/comments/1fagvcb/is_there_a_way_to_automatically_rip_music_from](https://www.reddit.com/r/selfhosted/comments/1fagvcb/is_there_a_way_to_automatically_rip_music_from)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T14:42:02+00:00

<!-- SC_OFF --><div class="md"><p>I want to automatically download new music from certain artists, but a lot of those artists are quite unpopular and have no torrents for their music, so Lidarr can&#39;t download them. In those cases I&#39;ve found that ripping from Deezer or other streaming services works the best, but I want to automate that since it&#39;s a lot of work doing it manually</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pipipupumees"> /u/pipipupumees </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fagvcb/is_there_a_way_to_automatically_rip_music_from/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fagvcb/is_there_a_way_to_automatically_rip_music_from/">[comments]</a></span>

## Feedback Needed: Will My Server Setup Work with the Programs I’m Using?
 - [https://www.reddit.com/r/selfhosted/comments/1fagop8/feedback_needed_will_my_server_setup_work_with](https://www.reddit.com/r/selfhosted/comments/1fagop8/feedback_needed_will_my_server_setup_work_with)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T14:34:21+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’m setting up a small server and would love some feedback on whether my setup will work as intended. Here’s what I’m planning:</p> <p>Hardware: - Raspberry Pi 5 (4GB RAM)</p> <p>Software: - Webmail: Roundcube - XMPP Server: Prosody - XMPP Web Client: Converse.js</p> <p>Operating System: - Raspbian</p> <p>Additional: - External Storage: 500GB USB hard drive - Display: WaveShare V4</p> <p>I want to run a webmail server and an XMPP chat service, with Converse.js as the web client for XMPP. I’m also considering adding Tor for privacy, to anonymize traffic and potentially access services via a .onion address.</p> <p>Will this setup handle 5-10 users overall? It&#39;s for me and a few friends. Is there anything I should be aware of or adjust? Any advice or suggestions are welcome!</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Uncover3d"> /u/Uncover3d </a> <br/> <span><a 

## Any kind souls willing to propose a software stack to satisfy my self-hosting desires? - an overwhelmed noob
 - [https://www.reddit.com/r/selfhosted/comments/1fagjyb/any_kind_souls_willing_to_propose_a_software](https://www.reddit.com/r/selfhosted/comments/1fagjyb/any_kind_souls_willing_to_propose_a_software)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T14:28:42+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m a noob looking to set up my first home server. I was hoping someone could propose a software stack that is flexible/extensible and can do some of the following:</p> <ol> <li>(Priority HIGH) Image backup and viewing (android phone)</li> <li>(Priority HIGH) data storage (for datasets from work and hobby projects, books, retrogaming save file backup; ideally accessible from android devices and other pcs, and ideally with autosyncing)</li> <li>(Priority MID) windows instance (so I can repurpose the windows partition on my laptop. it doesnt need to be performant, just run a couple windows-only programs that i use on occasion)</li> <li>(Priority LOW) web hosting (for personal website and blog)</li> <li>(Priority LOW) Allow for implementing RAID or some kind of redundancy in the future</li> </ol> <p>From a week of perusing, it seems proxmox is very popular to &quot;make one computer many computer&quot;, and allows for easy back up and restore. So may

## migrating away from telegram: xmpp software choice
 - [https://www.reddit.com/r/selfhosted/comments/1fagff1/migrating_away_from_telegram_xmpp_software_choice](https://www.reddit.com/r/selfhosted/comments/1fagff1/migrating_away_from_telegram_xmpp_software_choice)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T14:23:05+00:00

<!-- SC_OFF --><div class="md"><p>So, as Telegram will <a href="https://www.theverge.com/2024/9/5/24237254/telegram-pavel-durov-arrest-private-chats-moderation-policy-change">start moderating private chats</a> me and my friends started thinking about moving away from it, and setting up our own XMPP server. Which servers (linux) and clients (windows, linux, android) would be the best combo to cover the same feature set as telegram has? (maybe skipping things like stories, but stickers get used prominently within our group).<br/> I&#39;ve also been considering Matrix, but <a href="https://hackea.org/notas/matrix.html">this</a> sounds pretty bad and honestly I&#39;ve got no idea how valid this is. I definitely don&#39;t want to feed anyone my and my friend&#39;s data. Opinions on this, and other protocols that fit the criteria are very welcome. Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/akryl9296"> /u/akryl9296 </a> <br/> <span><a hr

## Best Self Hosted AI Agents?
 - [https://www.reddit.com/r/selfhosted/comments/1fag5vn/best_self_hosted_ai_agents](https://www.reddit.com/r/selfhosted/comments/1fag5vn/best_self_hosted_ai_agents)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T14:11:18+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I&#39;ve been toying with AI Automation agents like:</p> <ol> <li>N8N&#39;s ChatGPT API</li> <li>AutoGPT</li> <li>ZeroAgent</li> </ol> <p>Anyone have any even better any agents? Ideally something that you install on docker and pop in an OpenAI API key or even use locally with ollama or something?</p> <p>Ideally something that can run code or terminal commands or maybe even SSH</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/odaman8213"> /u/odaman8213 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fag5vn/best_self_hosted_ai_agents/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fag5vn/best_self_hosted_ai_agents/">[comments]</a></span>

## It's nice when it works
 - [https://www.reddit.com/r/selfhosted/comments/1fafrmp/its_nice_when_it_works](https://www.reddit.com/r/selfhosted/comments/1fafrmp/its_nice_when_it_works)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T13:54:09+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fafrmp/its_nice_when_it_works/"> <img src="https://b.thumbs.redditmedia.com/pR8ok5rPNdaonLOoYvg_P7-aLnzGPC3L3nGhDpj4Z3M.jpg" alt="It's nice when it works" title="It's nice when it works" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>iGPU passthrough on proxmox LXC.<br/> A lot of hours tinkering and testing before it worked and continues working after reboots. </p> <p><a href="https://preview.redd.it/5yk0ww2517nd1.png?width=1613&amp;format=png&amp;auto=webp&amp;s=0d01f7c9fb68e44ac10a7c6815f9104b4877d2ce">https://preview.redd.it/5yk0ww2517nd1.png?width=1613&amp;format=png&amp;auto=webp&amp;s=0d01f7c9fb68e44ac10a7c6815f9104b4877d2ce</a></p> <p>Been good for a couple of weeks.<br/> Time now to get on and <del>break</del> install something else.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/weeemrcb"> /u/weeemrcb </a> <br/> <span><a href="https://www.reddit.com/r/selfhoste

## Is there an app to sort and display photos?
 - [https://www.reddit.com/r/selfhosted/comments/1fafoq3/is_there_an_app_to_sort_and_display_photos](https://www.reddit.com/r/selfhosted/comments/1fafoq3/is_there_an_app_to_sort_and_display_photos)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T13:50:29+00:00

<!-- SC_OFF --><div class="md"><p>A bit of context. </p> <p>My mother has tons of photos of when we were young and takes loads when we go on holiday. At the end, she always gives them to me and I take them off the camera and put them on a shared folder on my NAS.</p> <p>The problem I have is that she doesn&#39;t use a computer and only has an android phone. The inbuilt file Explorer is terrible.</p> <p>Is there an app that I can host that automatically makes albums from folders in a shared drive and let&#39;s you easily browse them with a user friendly GUI? </p> <p>I&#39;m interested in others experience and uses of similar apps if you have them.</p> <p>It can be a webpage but if there is a partner phone app, that would be good.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/conrat4567"> /u/conrat4567 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fafoq3/is_there_an_app_to_sort_and_display_photos/">[link]</a></span> &#32

## Best self hosted library for ebooks, scientific journals, and all kinds of documents
 - [https://www.reddit.com/r/selfhosted/comments/1fafl3w/best_self_hosted_library_for_ebooks_scientific](https://www.reddit.com/r/selfhosted/comments/1fafl3w/best_self_hosted_library_for_ebooks_scientific)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T13:46:01+00:00

<!-- SC_OFF --><div class="md"><p>I need a system with really good categorisation and tagging, like calibre cuz I store lots of documents that are not books, like scientific journal entries, or manuals, tutorials etc. I need something you can you can manage completely online.I don&#39;t like calibre-server cuz you can&#39;t update it properly online, like edit tags, titles etc. Need to be able to really describe the documents, and be able to find the right one when needed. </p> <p>I heard about kativa, jellyfin, and a few others but never tried them. I have NextCloud on my VPS if that makes it any easier. </p> <p>Any suggestions? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/alchemizt33"> /u/alchemizt33 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fafl3w/best_self_hosted_library_for_ebooks_scientific/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fafl3w/best_self_hosted_library

## Announcing Richy 1.0.0 - selfhosted investing portfolio manager
 - [https://www.reddit.com/r/selfhosted/comments/1fafiiy/announcing_richy_100_selfhosted_investing](https://www.reddit.com/r/selfhosted/comments/1fafiiy/announcing_richy_100_selfhosted_investing)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T13:42:46+00:00

<!-- SC_OFF --><div class="md"><p>I <a href="https://old.reddit.com/r/selfhosted/comments/18ttbj0/announcing_richy_selfhosted_investing_portfolio/">announced</a> Richy a while ago and since that the app matured enough to be 1.0.0. After ~8 years of development the time has come and here we go - 1.0.0.</p> <p>Obligatory info:</p> <p>What is Richy (short version)</p> <p>Application that helps you to manage your investing portfolio. Supports stock and crypto market. Selfhosted.</p> <p>What Richy is (longer version)</p> <ul> <li>a (passive) portfolio manager</li> <li>market news hub</li> <li>a tool that aggregates information that helps you form ideas</li> <li>much better than your excel sheets</li> <li>quite documented</li> </ul> <p>What Richy is not</p> <ul> <li>an investing platform like RobinHood</li> <li>an app that gives you investing advice</li> <li>a trading bot</li> <li>a smart app with some kind of AI that tries to predict market</li> </ul> <p>Resources:</p> <ul> <li><a href="ht

## Three years in, I couldn't be happier.
 - [https://www.reddit.com/r/selfhosted/comments/1faf7au/three_years_in_i_couldnt_be_happier](https://www.reddit.com/r/selfhosted/comments/1faf7au/three_years_in_i_couldnt_be_happier)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T13:28:58+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1faf7au/three_years_in_i_couldnt_be_happier/"> <img src="https://preview.redd.it/8t1bf4mwx6nd1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=18ea9b19f042bbfbd9dd5e39643e64b0b27bb8ca" alt="Three years in, I couldn't be happier." title="Three years in, I couldn't be happier." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Savancik"> /u/Savancik </a> <br/> <span><a href="https://i.redd.it/8t1bf4mwx6nd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1faf7au/three_years_in_i_couldnt_be_happier/">[comments]</a></span> </td></tr></table>

## Jellyfin on Synology
 - [https://www.reddit.com/r/selfhosted/comments/1faf5b7/jellyfin_on_synology](https://www.reddit.com/r/selfhosted/comments/1faf5b7/jellyfin_on_synology)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T13:26:25+00:00

<!-- SC_OFF --><div class="md"><p>Every now and then, the permissions for the jellyfin system users get deleted. (Sc-jellyfin, sc-ffmpeg). Is there a way to lock these down?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sjashe"> /u/sjashe </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1faf5b7/jellyfin_on_synology/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1faf5b7/jellyfin_on_synology/">[comments]</a></span>

## I created yet another open-source self-hosted dashboard page
 - [https://www.reddit.com/r/selfhosted/comments/1faeur3/i_created_yet_another_opensource_selfhosted](https://www.reddit.com/r/selfhosted/comments/1faeur3/i_created_yet_another_opensource_selfhosted)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T13:12:42+00:00

<!-- SC_OFF --><div class="md"><p>I created <a href="https://github.com/sdabhi23/frontporch">FrontPorch</a>, yet another open-source, configurable and self-hosted dashboard page. I did not want to have to setup a full blown monitoring stack and go back and forth with it right now. The aim was simple: to be able to monitor basic stats of my servers and have some widgets.</p> <p>I will probably add support for getting data through Grafana as well soon. I am also planning to add some docker related realtime dashboards as well!</p> <p>Suggestions, feedback &amp; feature requests are welcome!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SouthRouge"> /u/SouthRouge </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1faeur3/i_created_yet_another_opensource_selfhosted/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1faeur3/i_created_yet_another_opensource_selfhosted/">[comments]</a></span>

## VPN questions
 - [https://www.reddit.com/r/selfhosted/comments/1fadr8f/vpn_questions](https://www.reddit.com/r/selfhosted/comments/1fadr8f/vpn_questions)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T12:18:59+00:00

<!-- SC_OFF --><div class="md"><p>I am doing some research into VPNs and wanted to start playing with them on my setup. Luckily enough my home setup is not behind a cgnat and my ip never changes. (Not a big deal if it does just experimenting for now). So plan on hosting it locally and not in a vps. I guess the one caveat is I am running pfsense behind my ISPs router but I think that should be easy enough to work around. </p> <p>I am a bit confused about the different offerings, headscale/tailscale and wireguard. </p> <p>From reading it looks like tailscale is a mesh p2p system? I wanted to setup something where I could access my full network when connected to the vpn. Also wanted to route all my traffic through the vpn and out through the home network when connected. Would wireguard be able to accomplish this? Any more resources to read up would be appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Arksz"> /u/Arksz </a> <br/> <span><a h

## This Week in Self-Hosted (6 September 2024)
 - [https://www.reddit.com/r/selfhosted/comments/1fadbrd/this_week_in_selfhosted_6_september_2024](https://www.reddit.com/r/selfhosted/comments/1fadbrd/this_week_in_selfhosted_6_september_2024)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T11:56:57+00:00

<!-- SC_OFF --><div class="md"><p>Happy Friday, <a href="/r/selfhosted">r/selfhosted</a>! Linked below is the latest edition of <em>This Week in Self-Hosted</em>, a weekly newsletter recap of the latest activity in self-hosted software.</p> <p>This week&#39;s features include include a ton of new software launches (26!), milestone v1.0 updates for two existing pieces of software, a spotlight on <a href="https://github.com/Mozzo1000/booklogr?ref=selfh.st">BookLogr</a> - a web app for managing and tracking personal reading libraries and statistics, and more!</p> <p>As usual, feel free to reach out with questions or comments about the newsletter. Thanks!</p> <hr/> <p><a href="https://selfh.st/newsletter/2024-09-06/?ref=reddit">This Week in Self-Hosted (6 September 2024)</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/shol-ly"> /u/shol-ly </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fadbrd/this_week_in_selfhosted_6_sept

## What host do you guys use to host Ollama (or another one)?
 - [https://www.reddit.com/r/selfhosted/comments/1fad6s2/what_host_do_you_guys_use_to_host_ollama_or](https://www.reddit.com/r/selfhosted/comments/1fad6s2/what_host_do_you_guys_use_to_host_ollama_or)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T11:49:31+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been trying to host Ollama for a while now, to use the chat as a search engine (searching for things on Google is very difficult these days), and for code assistance. The problem is that the energy costs ended up not being worth it, I&#39;m using a lot of energy for this, using CPU (totally inefficient). About 40 dollars per month of energy, for something that is very slow and inefficient (I&#39;m Brazilian, expensive energy, old hardware).</p> <p>Right now I&#39;m using Litellm to proxy with OpenAI, but I&#39;m very concerned about privacy, mainly because I&#39;m very interested in implementing it in my company (if we use Copilot, I&#39;ll spend more than 500 dollars per month for the whole team).</p> <p>Has anyone of you already hosted this type of server on a VPS? What type of VPS should I look for? Is there one specialized in AI that has a low cost?</p> <p>There are many questions, so any advice is very welcome.</p> </div><!-- SC_ON --> &

## How do I know if my vpn connection is working in unraid?
 - [https://www.reddit.com/r/selfhosted/comments/1facyau/how_do_i_know_if_my_vpn_connection_is_working_in](https://www.reddit.com/r/selfhosted/comments/1facyau/how_do_i_know_if_my_vpn_connection_is_working_in)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T11:36:32+00:00

<!-- SC_OFF --><div class="md"><p>The setup was rather easy, I made a new connection via config file from proton. I also can turn it on but I get no verification which makes me uneasy. </p> <p>I thought about installing Firefox or something where I have a web gui, use my vpn as network for it and google „what’s my ip“. But that feels wrong. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OwnZookeepergame6413"> /u/OwnZookeepergame6413 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1facyau/how_do_i_know_if_my_vpn_connection_is_working_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1facyau/how_do_i_know_if_my_vpn_connection_is_working_in/">[comments]</a></span>

## Is there a global management tool to update all my Linux machines at once?
 - [https://www.reddit.com/r/selfhosted/comments/1facnkw/is_there_a_global_management_tool_to_update_all](https://www.reddit.com/r/selfhosted/comments/1facnkw/is_there_a_global_management_tool_to_update_all)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T11:19:24+00:00

<!-- SC_OFF --><div class="md"><p>As the title says I have 5 old laptops in my home, all running Linux Server. I want to be able to update and upgrade all of them over one interface. I have all of them managed with a Portainer docker instance and the agents, but i could not find anything about updating the host machine in Portainer. Is there a possibility to do so?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MoreneLp"> /u/MoreneLp </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1facnkw/is_there_a_global_management_tool_to_update_all/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1facnkw/is_there_a_global_management_tool_to_update_all/">[comments]</a></span>

## Which other apps can make *rr apps better?
 - [https://www.reddit.com/r/selfhosted/comments/1facgzf/which_other_apps_can_make_rr_apps_better](https://www.reddit.com/r/selfhosted/comments/1facgzf/which_other_apps_can_make_rr_apps_better)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T11:08:48+00:00

<!-- SC_OFF --><div class="md"><p>Hello!</p> <p>I have setup a docker container in which I self host the following apps: - lidarr - radarr - sonarr - prowlarr - qBitTorrent - flaresolverr - jackett - bazarr - jellyfin - readarr - whisparr</p> <p>Which other app whether it is an arr or not will make the experience better?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/leonheartx1988"> /u/leonheartx1988 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1facgzf/which_other_apps_can_make_rr_apps_better/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1facgzf/which_other_apps_can_make_rr_apps_better/">[comments]</a></span>

## i cannot find any backup apps on my docker
 - [https://www.reddit.com/r/selfhosted/comments/1fac8uu/i_cannot_find_any_backup_apps_on_my_docker](https://www.reddit.com/r/selfhosted/comments/1fac8uu/i_cannot_find_any_backup_apps_on_my_docker)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T10:55:28+00:00

<!-- SC_OFF --><div class="md"><p>i tried urbackup but its shows client as offline after 1 hibernate or while (i not sure but i guess exactly 1 hibernate)</p> <p>i tried backuppc but its not backupping my files after i start backup (does nothing)</p> <p>i need backup apps for my file backup and partition bakup (both)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/furllamm"> /u/furllamm </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fac8uu/i_cannot_find_any_backup_apps_on_my_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fac8uu/i_cannot_find_any_backup_apps_on_my_docker/">[comments]</a></span>

## Why is Jellyfin using almost 12% of RAM even when no one is watching?
 - [https://www.reddit.com/r/selfhosted/comments/1fabnzt/why_is_jellyfin_using_almost_12_of_ram_even_when](https://www.reddit.com/r/selfhosted/comments/1fabnzt/why_is_jellyfin_using_almost_12_of_ram_even_when)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T10:17:31+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fabnzt/why_is_jellyfin_using_almost_12_of_ram_even_when/"> <img src="https://preview.redd.it/39jaevztz5nd1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=836bf11449e65f5b21494dcc5e96c16e24b9ec71" alt="Why is Jellyfin using almost 12% of RAM even when no one is watching?" title="Why is Jellyfin using almost 12% of RAM even when no one is watching?" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ale16011"> /u/ale16011 </a> <br/> <span><a href="https://i.redd.it/39jaevztz5nd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fabnzt/why_is_jellyfin_using_almost_12_of_ram_even_when/">[comments]</a></span> </td></tr></table>

## Is this legit?
 - [https://www.reddit.com/r/selfhosted/comments/1fabkzg/is_this_legit](https://www.reddit.com/r/selfhosted/comments/1fabkzg/is_this_legit)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T10:11:43+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fabkzg/is_this_legit/"> <img src="https://preview.redd.it/2l9n1fmsy5nd1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=9e9f5bb75e9e8d535991b35c3b4c7f8430ab6c19" alt="Is this legit?" title="Is this legit?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I need gpu for ai/cloud gaming server, and buying two of these could solve all of my problems. Buy, I literrarly cannot afford to get scamed... It is from China, so I dont know...</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gun3kter_cz"> /u/gun3kter_cz </a> <br/> <span><a href="https://i.redd.it/2l9n1fmsy5nd1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fabkzg/is_this_legit/">[comments]</a></span> </td></tr></table>

## Seeking advice on redesigning infrastructure for mid-sized company (100 employees, 6 sites)
 - [https://www.reddit.com/r/selfhosted/comments/1fabakx/seeking_advice_on_redesigning_infrastructure_for](https://www.reddit.com/r/selfhosted/comments/1fabakx/seeking_advice_on_redesigning_infrastructure_for)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T09:52:09+00:00

<!-- SC_OFF --><div class="md"><p>Hey <a href="/r/selfhosted">r/selfhosted</a>,</p> <p>I&#39;m a Linux newbie looking to redesign our company&#39;s infrastructure and could use some guidance. We&#39;re a mid-sized company with about 100 employees spread across 6 sites (5-30 people per site).</p> <p><strong>Current setup:</strong></p> <ul> <li>HCI (Nutanix Servers): Main cluster at one site, ROBOs at 3 sites</li> <li>Small VMware servers at 2 sites</li> <li>Windows-centric environment (clients, servers, AAD, DFS, print/file servers, GPOs)</li> <li>Fortinet firewalls</li> <li>Synology NAS at each site for backups, with main site NAS as additional backup</li> </ul> <p>The infrastructure has grown complex over the years, and our servers are now 6 years old. We&#39;re considering a complete overhaul.<strong>Proposed changes (based on advice from another sysadmin):</strong></p> <ul> <li>Switch to Nextcloud from Windows file server</li> <li>Implement active-passive setup with only 2 servers 

## How to set up NPM for Bar Assistant
 - [https://www.reddit.com/r/selfhosted/comments/1faamyn/how_to_set_up_npm_for_bar_assistant](https://www.reddit.com/r/selfhosted/comments/1faamyn/how_to_set_up_npm_for_bar_assistant)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T09:03:21+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;ve been trying to set up Bar Assistant/Salt Rim, and am quite stuck on how I can expose it through NGINX Proxy Manager.<br/> I found <a href="https://www.reddit.com/r/selfhosted/comments/1awjed2/bar_assistantsaltrim_with_nginx_proxy_manager/">this post here</a> where another user was stuck on the same part as I am, but alas, no answers were to be found (although they were successful).</p> <p>Currently, I am able to get Bar Assistant running locally (only) by following the offical instructions, but I can&#39;t expose it through NPM at all.</p> <p>Basically, I&#39;d like to skip the NGINX webserver that <a href="https://docs.barassistant.app/setup/">the Bar Assistant setup</a> suggests including and just use my existing NPM container that I use for everything else. But I can&#39;t seem to get the right settings in my docker compose/NPM to connect it all together. Any ideas would be greatly appreciated!</p> </div><!-- SC_ON --> &#32; submitted 

## Is it possible to add Nextcloud calendar to Homepage as widget?
 - [https://www.reddit.com/r/selfhosted/comments/1faa8s1/is_it_possible_to_add_nextcloud_calendar_to](https://www.reddit.com/r/selfhosted/comments/1faa8s1/is_it_possible_to_add_nextcloud_calendar_to)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T08:34:29+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Longjumping-Wait-989"> /u/Longjumping-Wait-989 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1faa8s1/is_it_possible_to_add_nextcloud_calendar_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1faa8s1/is_it_possible_to_add_nextcloud_calendar_to/">[comments]</a></span>

## Application catalog
 - [https://www.reddit.com/r/selfhosted/comments/1fa9iil/application_catalog](https://www.reddit.com/r/selfhosted/comments/1fa9iil/application_catalog)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T07:38:14+00:00

<!-- SC_OFF --><div class="md"><p>Hi there,</p> <p>I am working for quite a big company in IT, and we have a lot of applications that have been onboarded into the company. Now we are looking for a centralized “Application Catalog” that lists all the applications that are assessed by infosec and DPO. </p> <p>Does anyone have a couple of ideas regarding this? It doesn&#39;t have to be open source but would be nice since we can fine tune it ourselves. </p> <p>Love to see your ideas. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JohnMieremet"> /u/JohnMieremet </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fa9iil/application_catalog/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fa9iil/application_catalog/">[comments]</a></span>

## Delivery Executive Rate Card System
 - [https://www.reddit.com/r/selfhosted/comments/1fa9en5/delivery_executive_rate_card_system](https://www.reddit.com/r/selfhosted/comments/1fa9en5/delivery_executive_rate_card_system)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T07:30:02+00:00

<!-- SC_OFF --><div class="md"><p>Hi Redditors,</p> <p>I am looking for a solution that will help me define and model rate card that get assigned to delivery executives on ground. Delivery executives are folks who pick the order and delivery it to the customer.</p> <p>Rate cards can contain :</p> <ul> <li>Per order pay</li> <li>Kilometer-wise pay</li> <li>Peak hours extra pay.</li> <li>Attendance.</li> <li>order delay delivery penalty.</li> </ul> <p>And then review and run cases against this model and see the expected earning per Delivery Executives and final expense for organization.</p> <p>Thank you.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mob_lord"> /u/mob_lord </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fa9en5/delivery_executive_rate_card_system/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fa9en5/delivery_executive_rate_card_system/">[comments]</a></span>

## Cloudflare too slow
 - [https://www.reddit.com/r/selfhosted/comments/1fa9dd9/cloudflare_too_slow](https://www.reddit.com/r/selfhosted/comments/1fa9dd9/cloudflare_too_slow)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T07:27:21+00:00

<!-- SC_OFF --><div class="md"><p>As the title suggests, I find the connection through Cloudflare too slow when serving my movie collection. I host my collection on Jellyfin on my home server. I use Nginx Proxy Manager to manage the internet traffic. Cloudflare is my DNS provider, and as far as I understand, it also handles the SSL certificate.In my home network, the video content loads instantly. Even over a VPN, the content is available within 2 seconds.However, I want to avoid using a VPN in the future since I want to access my server from devices where I can&#39;t make administrative changes.I only have basic IT knowledge, but from what I&#39;ve read, the missing piece is caching or using a CDN. I know that Cloudflare is reluctant to cache mp4 files, or it only does so for private use. Do I need to integrate an external CDN provider here? If so, how do I configure it in combination with Nginx Proxy Manager and Cloudflare? If not, how do I properly set up caching?I don’t want to ca

## How to reduce memory footprint of uptimekuma?
 - [https://www.reddit.com/r/selfhosted/comments/1fa9256/how_to_reduce_memory_footprint_of_uptimekuma](https://www.reddit.com/r/selfhosted/comments/1fa9256/how_to_reduce_memory_footprint_of_uptimekuma)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T07:04:37+00:00

<!-- SC_OFF --><div class="md"><p>I have been running uptimekuma for free on fly.io for more than a year and it has been working great without any downtime.</p> <p>The free instance in fly.io has 256mb of memory which was more than enough until the last update.</p> <p>After the latest update the memory usage frequently goes above 256 mb and the app crashes.</p> <p>What changes in the config I could do to reduce the memory footprint?</p> <p>I don&#39;t think that the number of monitors is the problem as same number of monitors been running fine for more than a year. I assume some additional features added recently is causing the problem. but I cannot pinpoint any.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sevlonbhoi1"> /u/sevlonbhoi1 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fa9256/how_to_reduce_memory_footprint_of_uptimekuma/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1

## Immich backup
 - [https://www.reddit.com/r/selfhosted/comments/1fa8yvv/immich_backup](https://www.reddit.com/r/selfhosted/comments/1fa8yvv/immich_backup)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T06:58:47+00:00

<!-- SC_OFF --><div class="md"><p>I have a question about backup, I have read that it is recommended to backup the database using pg_dumpall. </p> <p>I back up all my containers by using bash crontab at 3am to stop all containers, perform a tar backup and then start all containers again. And I&#39;ve never had a problem with any database. Will there be any problem with immich?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/fubero___"> /u/fubero___ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fa8yvv/immich_backup/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fa8yvv/immich_backup/">[comments]</a></span>

## Has anyone self hosted NetBird? Seeking help
 - [https://www.reddit.com/r/selfhosted/comments/1fa805w/has_anyone_self_hosted_netbird_seeking_help](https://www.reddit.com/r/selfhosted/comments/1fa805w/has_anyone_self_hosted_netbird_seeking_help)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T05:53:17+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, </p> <p>I am trying to self host netbird using Zitadel script &amp; getting stuck at - </p> <p><code>Waiting for Zitadel to become ready . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

## Docker Compose Anywhere: Simplify Your Production Deployments with Docker Compose
 - [https://www.reddit.com/r/selfhosted/comments/1fa68zf/docker_compose_anywhere_simplify_your_production](https://www.reddit.com/r/selfhosted/comments/1fa68zf/docker_compose_anywhere_simplify_your_production)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T04:05:59+00:00

<!-- SC_OFF --><div class="md"><p>Hey devs! 👋 Check out <a href="https://github.com/hadijaveed/docker-compose-anywhere">Docker Compose Anywhere</a>, a project I&#39;ve been working on to streamline app deployments.</p> <h1>What is it?</h1> <p>A template for hosting apps on a single server/VM using Docker Compose, with zero-downtime deployments and GitHub Actions integration.</p> <h1>Key Features:</h1> <ul> <li>One-click server setup</li> <li>Zero-downtime continuous deployment</li> <li>Easy secrets management</li> <li>Automated SSL setup</li> </ul> <p>Perfect for apps that can run on a single server without complex K8s or cloud setups.</p> <p>Thoughts? Questions? Let me know!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Any-Policy9813"> /u/Any-Policy9813 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fa68zf/docker_compose_anywhere_simplify_your_production/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/

## Fail2Ban not banning ip’s from Jellyfin
 - [https://www.reddit.com/r/selfhosted/comments/1fa5m16/fail2ban_not_banning_ips_from_jellyfin](https://www.reddit.com/r/selfhosted/comments/1fa5m16/fail2ban_not_banning_ips_from_jellyfin)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T03:31:28+00:00

<!-- SC_OFF --><div class="md"><p>Hi selfhosted, </p> <p>I’m currently running OMV on an old desktop and I am running Jellyfin in portainer with fail2ban installed directly onto operating system. Currently I have the server connected to a Tailscale tailnet and Jellyfin set up so that it can only be connected to by my local network and my tailnet (I.e. I don’t have it exposed to the internet through reverse proxies or tunnels). Followed jellyfin’s documentation for setting up the jail and filters but upon trying to connect via one of my tailnet clients and trying to force a ban, the ip was never banned. Can somebody help me with this? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Kenseimain9"> /u/Kenseimain9 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fa5m16/fail2ban_not_banning_ips_from_jellyfin/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fa5m16/fail2ban_not_banning_ips_fro

## looking for a suitable control panel - either free or paid
 - [https://www.reddit.com/r/selfhosted/comments/1fa5fzw/looking_for_a_suitable_control_panel_either_free](https://www.reddit.com/r/selfhosted/comments/1fa5fzw/looking_for_a_suitable_control_panel_either_free)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T03:22:26+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>Im looking for a suitable control panel - either free or paid - to host a single website along with about 500 mailboxes under my domain. A key requirement is the ability to pay with cryptocurrency. Could anyone recommend a solution?</p> <p>I found ISPmanager, which is affordable and supports cryptocurrency payments. </p> <p>Unfortunately, Plesk and DirectAdmin do not accept cryptocurrency. </p> <p>On the free side, I saw recommendations for HestiaCP, KeyHelp and Webmin.</p> <p>My priorities are:</p> <ul> <li><p>Reliable backup options: fear of screwing up...</p></li> <li><p>Stable mail server: since that is the main need.</p></li> <li><p>Secure: cannot be accessed in any way by using bugs or malware or we will lose hundreds bucks.</p></li> </ul> <p>Any suggestions would be greatly appreciated -- Thank you! &lt;3</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/guexofficial"> /u/guexofficial 

## Self-hosted SMTP server
 - [https://www.reddit.com/r/selfhosted/comments/1fa5d3c/selfhosted_smtp_server](https://www.reddit.com/r/selfhosted/comments/1fa5d3c/selfhosted_smtp_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T03:18:03+00:00

<!-- SC_OFF --><div class="md"><p>Hi!<br/> I need to setup SMTP server on a Ubuntu server so that it can handle huge volumes of emails. I&#39;m a DevOps engineer but I don&#39;t have a background in mail department. </p> <p>I tried researching on how to set it up but haven&#39;t found a good documentation, blogs or anything related.<br/> So far I tried setting up postfix, sasl, setup mx-records, spf, dkim and _dmarc. At first I tried sending test mail to my gmail and it landed in my inbox, but when I tried to reply I got error saying user doesn&#39;t exists and it was obvious as I didn&#39;t setup any user account. </p> <p>When I tried to setup a User account it didn&#39;t authenticate and after long hour of try, everything just messed up.<br/> Now, I want to set it up from scratch. </p> <p>Any help would be appreciated.<br/> Thank you in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Poesximah"> /u/Poesximah </a> <br/> <span><a href="h

## Is there a way to get intro skipping on a Plex server without Plex Pass?
 - [https://www.reddit.com/r/selfhosted/comments/1fa5cnl/is_there_a_way_to_get_intro_skipping_on_a_plex](https://www.reddit.com/r/selfhosted/comments/1fa5cnl/is_there_a_way_to_get_intro_skipping_on_a_plex)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T03:17:20+00:00

<!-- SC_OFF --><div class="md"><p>Paying a subscription service for features kind of defeats the purpose of self-hosting my media server. It seems the general consensus is &quot;Just get a lifetime pass when it goes on sale lol&quot; but the thing is that I don&#39;t care how much it costs. I don&#39;t want it. Especially after a year of controversies involving software no longer honoring &quot;lifetime&quot; subscriptions out of nowhere (ie. &quot;Filmora Wondershare&quot;).</p> <p>Jellyfin has the feature but the frontend looks like it was made by the backend designers, and half the fun is that this is pretty much a personal Netflix, as opposed to what looks a lot like a Media Player app that comes with the TV.</p> <p>Is there some other way to do intro skipping in Plex on my content?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok_Rough_1866"> /u/Ok_Rough_1866 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fa5cnl/is

## Obsidian sync with Gitea
 - [https://www.reddit.com/r/selfhosted/comments/1fa40te/obsidian_sync_with_gitea](https://www.reddit.com/r/selfhosted/comments/1fa40te/obsidian_sync_with_gitea)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T02:08:55+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>Deployed Gitea with docker. Logged in and creataed repository.</p> <p>And Obsidian (Windows platform), installed &quot;Git&quot;.</p> <p>Then press Ctrl + P, selected &quot;Git Clone&quot;, entered URL.</p> <p>In neet step &quot;folder&quot;, what&#39;s should be ?</p> <p>Since couldn&#39;t create folder in Git repository.</p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mailliwal"> /u/mailliwal </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fa40te/obsidian_sync_with_gitea/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fa40te/obsidian_sync_with_gitea/">[comments]</a></span>

## Selfhosted forums
 - [https://www.reddit.com/r/selfhosted/comments/1fa3bcr/selfhosted_forums](https://www.reddit.com/r/selfhosted/comments/1fa3bcr/selfhosted_forums)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T01:32:34+00:00

<!-- SC_OFF --><div class="md"><p>Hello there guys! Does <a href="/r/selfhosted">r/selfhosted</a> have a forum outisde of reddit? Discord. I would reallike an alternative ro interacting with the community but not in reddit. So thank you in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RampagingAddict"> /u/RampagingAddict </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fa3bcr/selfhosted_forums/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fa3bcr/selfhosted_forums/">[comments]</a></span>

## Let's Encrypt ACME for wildcard subdomain *.local.domain.dev?
 - [https://www.reddit.com/r/selfhosted/comments/1fa3ap4/lets_encrypt_acme_for_wildcard_subdomain](https://www.reddit.com/r/selfhosted/comments/1fa3ap4/lets_encrypt_acme_for_wildcard_subdomain)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T01:31:37+00:00

<!-- SC_OFF --><div class="md"><p>I am running cert-manager on kubernetes in my homelab trying to generate valid certs. I have a *.local.domain.dev for local dns resolution and my *.domain.dev for public services. If I run just the *.domain.dev for a certificate request it validates just fine, this won&#39;t work for *.local.domain.dev (I believe the wildcard only applies for that one level) so I try to add it to the Certificate request as this:</p> <pre><code>kind: Certificate ... spec: commonName: &#39;*.domain.dev&#39; dnsNames: - &#39;*.domain.dev&#39; - &#39;*.local.domain.dev&#39; </code></pre> <p>I go to the acme-v02.api.letsencrypt.org/acme/authz-v3/ site and see that &quot;*.domain.dev&quot; once again validates but not the other. I see the .txt record show up in cloudflare as &quot;_acme-challenge.local&quot; however, so it should work. I also ran a dig TXT command for &quot;_acme-challenge.local.domain.dev&quot; and it returns the challenge just fine. </p> <p>I can&#39;t fi

## Ibi
 - [https://www.reddit.com/r/selfhosted/comments/1fa2mfq/ibi](https://www.reddit.com/r/selfhosted/comments/1fa2mfq/ibi)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-09-06T00:57:39+00:00

<!-- SC_OFF --><div class="md"><p>Good evening Reddit community, I could really use your help. My wife and I are crushed and a bit side swiped. I just learned that Ibi is no longer supported, and we have tons of photos of our baby. </p> <p>I found the email warning us of the discontinued support starting August 31st. Unfortunately, that is an old email I rarely check. </p> <p>Is there anything I can do to extract these photos of the Ibi? Is the physical hard drive dockable somehow? I would rather try a non-intrusive way first before I start hacking away to the individual chips - but if that is where this leads me then so be it. I’ve done it already with a Microsoft device. We have precious photos on this thing and really need to get them off.</p> <p>Your help and guidance is very much appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Deadphans"> /u/Deadphans </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fa2mfq

