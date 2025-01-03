# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Protecting Immich through Authentik & Crowdsec
 - [https://www.reddit.com/r/selfhosted/comments/1hjlcfw/protecting_immich_through_authentik_crowdsec](https://www.reddit.com/r/selfhosted/comments/1hjlcfw/protecting_immich_through_authentik_crowdsec)
 - RSS feed: $source
 - date published: 2024-12-21T22:53:50+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I hope you are keeping well. I&#39;ve learned a lot from you people this year and I want to say thank you and I hope you enjoy a safe and happy Christmas period.</p> <p>I have Immich behind Authentik and I want to serve Immich up via Cloudflare Tunnel so that family can access it. Is it necessary to put Crowdsec in front of Authentik, and/or is there something else I can use within my free Cloudflare account to achieve the same? Is there a good guide for Crowdsec + Authentik? </p> <p>Intent is to geo-restrict and generally bounce brute force or untested and IP addressese of bad reputation.</p> <p>Thanks everyone and have a great day.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/El_ratson"> /u/El_ratson </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjlcfw/protecting_immich_through_authentik_crowdsec/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/c

## Graylog extractor for Unifi Firewall
 - [https://www.reddit.com/r/selfhosted/comments/1hjl9y5/graylog_extractor_for_unifi_firewall](https://www.reddit.com/r/selfhosted/comments/1hjl9y5/graylog_extractor_for_unifi_firewall)
 - RSS feed: $source
 - date published: 2024-12-21T22:50:23+00:00

<!-- SC_OFF --><div class="md"><p>I just made this to help troubleshoot unifi firewall, sharing for anyone might need the same</p> <p>also found this website super helpful <a href="https://grokdebugger.com/">https://grokdebugger.com/</a></p> <p><code> { &quot;extractors&quot;: [ { &quot;title&quot;: &quot;Unifi Firewall&quot;, &quot;extractor_type&quot;: &quot;grok&quot;, &quot;converters&quot;: [], &quot;order&quot;: 0, &quot;cursor_strategy&quot;: &quot;copy&quot;, &quot;source_field&quot;: &quot;message&quot;, &quot;target_field&quot;: &quot;&quot;, &quot;extractor_config&quot;: { &quot;grok_pattern&quot;: &quot;%{HOSTNAME:hostname} \\[%{DATA:fw_id}\\] DESCR=\\\&quot;%{DATA:fw_name}\\\&quot; IN=(?:%{DATA:interface_in})? OUT=(?:%{DATA:interface_out})? MAC=(?:%{MAC:src_mac})?(?:\\:%{MAC:dst_mac})?(?:\\:%{DATA:mac_ext})? SRC=(?:%{IPV4:src_ip}|%{IPV6:src_ip}) DST=(?:%{IPV4:dst_ip}|%{IPV6:dst_ip})%{GREEDYDATA}PROTO=%{WORD:protocol}(?: SPT=%{INT:src_port})?(?: DPT=%{INT:dst_port})?&quot

## Ha proxy with Cloudflare proxy
 - [https://www.reddit.com/r/selfhosted/comments/1hjkx7i/ha_proxy_with_cloudflare_proxy](https://www.reddit.com/r/selfhosted/comments/1hjkx7i/ha_proxy_with_cloudflare_proxy)
 - RSS feed: $source
 - date published: 2024-12-21T22:32:35+00:00

<!-- SC_OFF --><div class="md"><p>I set up this <a href="https://forum.opnsense.org/index.php?topic=23339.0">haproxy</a> at my opnsesne home and I want to leverage opnsesne proxy instead of exposing my static ip. Does anyone have a guide or article?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ActAccording2288"> /u/ActAccording2288 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjkx7i/ha_proxy_with_cloudflare_proxy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjkx7i/ha_proxy_with_cloudflare_proxy/">[comments]</a></span>

## How to securely connect Portainer to Docker using Cloudflare Tunnels?
 - [https://www.reddit.com/r/selfhosted/comments/1hjkroh/how_to_securely_connect_portainer_to_docker_using](https://www.reddit.com/r/selfhosted/comments/1hjkroh/how_to_securely_connect_portainer_to_docker_using)
 - RSS feed: $source
 - date published: 2024-12-21T22:25:13+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I&#39;m a beginner working with Docker, Portainer, and Cloudflare.<br/> Here&#39;s my current setup and the problem I&#39;m trying to solve:</p> <p><strong>VPS Configuration</strong>:</p> <ul> <li>I rented a VPS from Hostinger and installed <strong>Ubuntu 24.04</strong>.</li> <li><p>Installed <strong>Docker</strong> and enabled TLS by modifying <code>/etc/docker/daemon.json</code>:</p> <p>{ &quot;tls&quot;: true, &quot;tlsverify&quot;: true, &quot;tlscacert&quot;: &quot;/etc/docker/certs.d/ca.pem&quot;, &quot;tlscert&quot;: &quot;/etc/docker/certs.d/cert.pem&quot;, &quot;tlskey&quot;: &quot;/etc/docker/certs.d/key.pem&quot;, &quot;hosts&quot;: [&quot;tcp://0.0.0.0:2376&quot;, &quot;unix:///var/run/docker.sock&quot;], &quot;live-restore&quot;: true }</p></li> </ul> <p><strong>Portainer Installation</strong>:</p> <ul> <li>I installed <strong>Portainer</strong> on Docker. It works perfectly without any issues.</li> </ul> <p><strong>C

## Caddy certs to local servers security
 - [https://www.reddit.com/r/selfhosted/comments/1hjkmq1/caddy_certs_to_local_servers_security](https://www.reddit.com/r/selfhosted/comments/1hjkmq1/caddy_certs_to_local_servers_security)
 - RSS feed: $source
 - date published: 2024-12-21T22:18:09+00:00

<!-- SC_OFF --><div class="md"><p>In my network I have services located on different machines. If I wanted to have a single caddy server to dish out certs to all of them, will the traffic be secure from caddy to the server/service or only from my browser to caddy? Think homeassistant on on VM, nextcloud on another one, some services combined onto a pi, etc. I&#39;d like to not have to put caddy on all the boxes and centralize this stuff.</p> <p>Thanks in advance! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mikedoth"> /u/mikedoth </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjkmq1/caddy_certs_to_local_servers_security/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjkmq1/caddy_certs_to_local_servers_security/">[comments]</a></span>

## How to mak Crowdsec work with Cloudflare Tunnel? (free plan)
 - [https://www.reddit.com/r/selfhosted/comments/1hjkby4/how_to_mak_crowdsec_work_with_cloudflare_tunnel](https://www.reddit.com/r/selfhosted/comments/1hjkby4/how_to_mak_crowdsec_work_with_cloudflare_tunnel)
 - RSS feed: $source
 - date published: 2024-12-21T22:03:20+00:00

<!-- SC_OFF --><div class="md"><p>I host multiple micro wordpress sites on my unraid server, within a linux vm running lemp stack, and using cloudflare tunnel, so no portforward and messing with cgnat.</p> <p>Later I installed crowdsec, added common http/nginx/wordpress attack scenario, and have it reading my nginx log, but I notice an issue I didn&#39;t knew beforehand, the crowdsec cloudflare bouncer requires a paid cloudflare account, and the cloudflare worker bouncer only limit to 1000 ips into kv storage, which seems to be too limiting to be effective at all?</p> <p>Then there&#39;s nginx bouncer which use the nginx lua engine plugin, but I don&#39;t know if the bouncer check are happen before or after my nginx set real ip from cf header, and I&#39;m also not sure if it&#39;s going to cause huge latency on accessing the backend of my wordpress, and will it use a lot of resources</p> <p>So now I&#39;m torn between the free cloudflare worker solution with limited block list, or th

## Experienced self-hoster, novice home-automator. Looking to deploy my very first home security system and I have no idea what to pick
 - [https://www.reddit.com/r/selfhosted/comments/1hjk3xk/experienced_selfhoster_novice_homeautomator](https://www.reddit.com/r/selfhosted/comments/1hjk3xk/experienced_selfhoster_novice_homeautomator)
 - RSS feed: $source
 - date published: 2024-12-21T21:52:29+00:00

<!-- SC_OFF --><div class="md"><p>My girlfriend just bought her first house, and is looking to set up a security system for it. As the resident techie, I&#39;ve been tasked with looking into researching and deploying a setup. I know these posts are pretty common but none of the options I&#39;ve come across so far look particularity attractive.</p> <p>Eventually, my goal is to build a homeserver/NAS for my GF to keep at her house, which could manage many home-automation things, which I naturally assumed would include the security system. I initially thought I would have more time to plan out a system, but she wants it deployed ASAP.</p> <p>The way I see it, there are two routes I can take. The &quot;all in one&quot; setups which are plug and play, but seem quite limited, or a totally DIY solution. </p> <p>The fully DIY solution seems more attractive to me, because</p> <ul> <li>Sounds fun</li> <li>Can more easily integrate with other solutions (home assistant, etc)</li> <li>Easily upgr

## Security, Yunohost, website hosting, etc. Advice/insight needed.
 - [https://www.reddit.com/r/selfhosted/comments/1hjk04d/security_yunohost_website_hosting_etc](https://www.reddit.com/r/selfhosted/comments/1hjk04d/security_yunohost_website_hosting_etc)
 - RSS feed: $source
 - date published: 2024-12-21T21:47:01+00:00

<!-- SC_OFF --><div class="md"><p>I don&#39;t have a big list of needs for a home server. I have a 6yr old Alienware gaming tower that was gifted to me, a fibre optic line at the location I want to install it, and no increase in my electric bill (flat fee monthly). I&#39;d like to put this to use for 1. hosting my website for my art portfolio and 2. creating something like a reddit style forum/bbs for other art friends/colleagues to have un-monitored private discussions. </p> <p>I&#39;ve been looking at yunohost because I really do not want to put in a long learning curve for this. I&#39;ve been lurking for a few months and the number of daily posts with tiny issues bringing servers down seems overwhelming. A lot of people here enjoy the behind the scenes tweaking too. I do NOT find joy in tweaking fiddly little settings to get it just right, and I don&#39;t take it as just SOP when shit randomly breaks and I lose a day sorting it out. Yunohost looks like it can handle doing these ta

## Hi, I created a CLI, that creates a commerce backend and dashboard, that can connect to any database, storage and compute (links in the comments)
 - [https://www.reddit.com/r/selfhosted/comments/1hji2me/hi_i_created_a_cli_that_creates_a_commerce](https://www.reddit.com/r/selfhosted/comments/1hji2me/hi_i_created_a_cli_that_creates_a_commerce)
 - RSS feed: $source
 - date published: 2024-12-21T20:11:39+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hji2me/hi_i_created_a_cli_that_creates_a_commerce/"> <img src="https://preview.redd.it/cisvxfmee98e1.gif?width=640&amp;crop=smart&amp;s=cb4c27289bbfd1a32f4c6f691bee4fe23da0be2e" alt="Hi, I created a CLI, that creates a commerce backend and dashboard, that can connect to any database, storage and compute (links in the comments)" title="Hi, I created a CLI, that creates a commerce backend and dashboard, that can connect to any database, storage and compute (links in the comments)" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hendrixstring"> /u/hendrixstring </a> <br/> <span><a href="https://i.redd.it/cisvxfmee98e1.gif">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hji2me/hi_i_created_a_cli_that_creates_a_commerce/">[comments]</a></span> </td></tr></table>

## ChatGPT saved my a** big time
 - [https://www.reddit.com/r/selfhosted/comments/1hjhroz/chatgpt_saved_my_a_big_time](https://www.reddit.com/r/selfhosted/comments/1hjhroz/chatgpt_saved_my_a_big_time)
 - RSS feed: $source
 - date published: 2024-12-21T19:57:25+00:00

<!-- SC_OFF --><div class="md"><p>Just wanted to share a little something, I now have gone through quite a few times. I’ve been selfhosting for some years now. In the early days it was mostly searching GitHub and various boards and Reddit for tips and tricks. Nowadays I have ChatGPT running whenever a problem occurs. Just one example of today.</p> <p>My dockerized Wordpress stack with mariadb was being unresponsive every other day. I could find any relevant logs with errors that could have been the reason. That said I „discussed“ my problem with ChatGPT and after some back and forth „we“ came to the conclusion, that my VPS was being targeted with brute force attacks on port 22. Sure I knew this was a thing, but did not have any countermeasures unplaced at the moment. After that I managed to deploy fail2ban which made the problem go away. In the process I even managed to upgrade a Postgres container that was totally unrelated, but also had many problems.</p> <p>TLDR: chatgpt is awesom

## NetLock RMM - The Open Source Remote Management & Monitoring Platform
 - [https://www.reddit.com/r/selfhosted/comments/1hjhm5m/netlock_rmm_the_open_source_remote_management](https://www.reddit.com/r/selfhosted/comments/1hjhm5m/netlock_rmm_the_open_source_remote_management)
 - RSS feed: $source
 - date published: 2024-12-21T19:49:58+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! 👋</p> <p>I&#39;m posting this on behalf of the project owner since he doesn&#39;t use Reddit. I&#39;m a huge fan of the project, and I want to help spread the word—it&#39;s still relatively unknown! 🚀</p> <p><strong>So, what’s this project about?</strong> 🤔<br/> RMM stands for <strong>Remote Monitoring &amp; Management</strong>. If you need to monitor servers and workstations no matter where they’re located, that’s exactly what <strong>NetLock RMM</strong> is for! 💻🌐 You can fully manage these devices remotely, scaling from just <strong>1 device to 50,000</strong>, depending on your server infrastructure. ⚙️</p> <p><strong>What makes NetLock RMM special?</strong><br/> 🔓 It’s a comprehensive <strong>Open-Source RMM solution</strong> for self-hosting, licensed under <strong>AGPLv3</strong>.<br/> 🌍 It supports <strong>multiple clients &amp; locations</strong>, <strong>multiple languages</strong>, and offers <strong>powerful features</stron

## Looking for inspiration: The most intuitive, clear and comprehensive settings UI's you've seen?
 - [https://www.reddit.com/r/selfhosted/comments/1hjhjf4/looking_for_inspiration_the_most_intuitive_clear](https://www.reddit.com/r/selfhosted/comments/1hjhjf4/looking_for_inspiration_the_most_intuitive_clear)
 - RSS feed: $source
 - date published: 2024-12-21T19:46:19+00:00

<!-- SC_OFF --><div class="md"><p>Primarily something opensource or freely available to click around and explore, but proprietary software is fine too.</p> <p>Basically I&#39;m looking for inspiration to make a settings UI for a selfhosted software I&#39;ve been making, <a href="https://github.com/9001/copyparty/">copyparty</a>. It&#39;s an alternative to web-based file managers / file-upload services such as filebrowser, hfs, dufs, pingvin-share, ... and I&#39;d say it&#39;s currently a strong choice for receiving uploads in particular, often several times faster than the alternatives.</p> <p>But configuration kinda sucks due to entirely being config-files, which is also poorly documented, and there&#39;s <a href="https://ocv.me/copyparty/helptext.html">around 400 options</a> just to make it worse. I&#39;ve long since realized that my documentation skills are in the negatives, so I was hoping to avoid that problem with a config-UI to make setup more intuitive. But while the main UI 

## invidious kodi plugin - limit dash to 1080p ?
 - [https://www.reddit.com/r/selfhosted/comments/1hjhi67/invidious_kodi_plugin_limit_dash_to_1080p](https://www.reddit.com/r/selfhosted/comments/1hjhi67/invidious_kodi_plugin_limit_dash_to_1080p)
 - RSS feed: $source
 - date published: 2024-12-21T19:44:40+00:00

<!-- SC_OFF --><div class="md"><p>just setup an invidious instance and after some fiddeling also got kodi addon to work. everything works and is great, except when i enable dash and videos do have 4k streams it defaults to 4k. Which I cant stream fluid. Disabling dash limits everything to 360p.</p> <p>There are no obvious settings in kodi addon, and settings in invidious dont have an effect on kodi addon.</p> <p>Any way to limit kodi invidious dash to 1080?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Agentum"> /u/Agentum </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjhi67/invidious_kodi_plugin_limit_dash_to_1080p/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjhi67/invidious_kodi_plugin_limit_dash_to_1080p/">[comments]</a></span>

## Introducing Isley - A Self-Hosted Cannabis Grow Journal for Home Growers
 - [https://www.reddit.com/r/selfhosted/comments/1hjhdms/introducing_isley_a_selfhosted_cannabis_grow](https://www.reddit.com/r/selfhosted/comments/1hjhdms/introducing_isley_a_selfhosted_cannabis_grow)
 - RSS feed: $source
 - date published: 2024-12-21T19:38:30+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hjhdms/introducing_isley_a_selfhosted_cannabis_grow/"> <img src="https://external-preview.redd.it/QXUyGWVUtAYTO3mD5UwT-itb2eQn8camtbFz4pVRo1s.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=76306686f1027b10b725a1375658649a50a73bf9" alt="Introducing Isley - A Self-Hosted Cannabis Grow Journal for Home Growers" title="Introducing Isley - A Self-Hosted Cannabis Grow Journal for Home Growers" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I&#39;ve been working on <strong>Isley</strong>, a self-hosted web app for cannabis home growers, and I wanted to share it to the community. Isley is designed to help growers manage their plants, track daily activities, and monitor environmental data.</p> <h1>What Isley Does:</h1> <ul> <li><strong>Plant Management:</strong> Add plants and log details like strain, growth stage, and important dates.</li> <li><strong>Activity Tracking:</strong> Record watering, feeding, height me

## NginX Proxy Ignore Dns resolution failure at startup
 - [https://www.reddit.com/r/selfhosted/comments/1hjh1o6/nginx_proxy_ignore_dns_resolution_failure_at](https://www.reddit.com/r/selfhosted/comments/1hjh1o6/nginx_proxy_ignore_dns_resolution_failure_at)
 - RSS feed: $source
 - date published: 2024-12-21T19:22:12+00:00

<!-- SC_OFF --><div class="md"><p>Hey, this seems to be a topic that has been discussed in various places before, but I’m still very unsatisfied with the proposed solutions.<br/> When you start your Nginx service (in my case, a Docker container), it attempts to resolve all DNS addresses to cache (I think) and validate them.<br/> If you want to proxy services that might not be running at startup, Nginx will fail. The two most popular workarounds seem to be:</p> <ul> <li>Setting the proxy pass address to a variable</li> <li>Somehow faking the DNS record (via the hosts file or a custom DNS resolver [I did not look into these])</li> </ul> <p>I got it to work in my case using the variable workaround, but I’m not particularly fond of it. Most discussions about this are 3+ years old, so I wanted to ask if there are any other/newer solutions to this problem.</p> <p>Any information is greatly appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/C

## Daily logs
 - [https://www.reddit.com/r/selfhosted/comments/1hjgwpr/daily_logs](https://www.reddit.com/r/selfhosted/comments/1hjgwpr/daily_logs)
 - RSS feed: $source
 - date published: 2024-12-21T19:15:51+00:00

<!-- SC_OFF --><div class="md"><p>Hey all. Long time reader, first time poster. </p> <p>I&#39;ve caught the self hosting bug in the last few years. I&#39;ve got a server running proxmox with true nas core, an Ubuntu docker stack for things like Plex, arrs and immicj and home assistant. Pihole, and other stuff some accesswd through cloudflare tunnels with entra id Auth where I can. </p> <p>Can anyone recommend a self hosted log tool for doing my daily work logs. Basically I am rushed off my feet most days and need to keep track of exactly what I do each day for insurance purposes and I absolutely hate writing up a daily log. I usually forgot or do it at the end of the week or even month and it&#39;s a pain.</p> <p>I used timular for a while which atleast tracks some time stuff with a wee cube and notes and can hook into the windows 11 pc to keep track of the programs I&#39;m using but I would love it if there was something that could just summarise everything I did on the pc in the da

## Host a short TTL Email server?
 - [https://www.reddit.com/r/selfhosted/comments/1hjgtu2/host_a_short_ttl_email_server](https://www.reddit.com/r/selfhosted/comments/1hjgtu2/host_a_short_ttl_email_server)
 - RSS feed: $source
 - date published: 2024-12-21T19:11:58+00:00

<!-- SC_OFF --><div class="md"><p>HI, im an apprentice at a large organisation, we use email on deck to quickly generate dispoable emails. </p> <p>We do fake applications to test out systems, we record the temp email address and also a token. </p> <p>But we keep running into problems due to it being a transatlantic server.</p> <p>Security should not be a problem as it will stay on the organisational side of the firewall and not have to connect to 80/443 internet etc. </p> <p>So in order to score a million points at work, help with my apprenticeship and also im studying CCNA. </p> <p>Is it possible and how can learn to host my own short TTL disposable email server. In the style of emailondeck.com?</p> <p>Thanks Guys </p> <p>Kyle</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Independent-Spot-448"> /u/Independent-Spot-448 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjgtu2/host_a_short_ttl_email_server/">[link]</a></spa

## Low powered (SBC?) with SATA options?
 - [https://www.reddit.com/r/selfhosted/comments/1hjgmex/low_powered_sbc_with_sata_options](https://www.reddit.com/r/selfhosted/comments/1hjgmex/low_powered_sbc_with_sata_options)
 - RSS feed: $source
 - date published: 2024-12-21T19:02:08+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I am looking for a low powered machine I can host at another house that would serve as an off-site backup. It will be kept in a closet, so my ideal device would be a SBC or small form factor. It must be able to support a SATA for the disk. Wifi would be really be highly preferred.</p> <p>More context: I have a spare 4TB disk that I would like to use to backup all files from my primary device. The primary runs ZFS. It will host some combination of proxmox and NextCloud.</p> <p>It need not be fast or powerful as long as it&#39;s &quot;usable&quot; - subjective, I know. And as usual, lower cost is preferred!</p> <p>Recommendations?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FarhanYusufzai"> /u/FarhanYusufzai </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjgmex/low_powered_sbc_with_sata_options/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/

## Notion Type Alternative? Need to setup Company Wiki.
 - [https://www.reddit.com/r/selfhosted/comments/1hjfnkr/notion_type_alternative_need_to_setup_company_wiki](https://www.reddit.com/r/selfhosted/comments/1hjfnkr/notion_type_alternative_need_to_setup_company_wiki)
 - RSS feed: $source
 - date published: 2024-12-21T18:17:14+00:00

<!-- SC_OFF --><div class="md"><p>Leaning into the self hosted options recently as I’m learning there are some incredible tools out there.</p> <p>Anyone have suggestions for a company wiki? Also, ideally, ability to have a page or 3 to send customers as part of an onboarding journey w/ videos + various white papers?</p> <p>Appreciate the guidance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BeardedClassic"> /u/BeardedClassic </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjfnkr/notion_type_alternative_need_to_setup_company_wiki/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjfnkr/notion_type_alternative_need_to_setup_company_wiki/">[comments]</a></span>

## What the point of DB for NPM
 - [https://www.reddit.com/r/selfhosted/comments/1hjff3j/what_the_point_of_db_for_npm](https://www.reddit.com/r/selfhosted/comments/1hjff3j/what_the_point_of_db_for_npm)
 - RSS feed: $source
 - date published: 2024-12-21T18:06:16+00:00

<!-- SC_OFF --><div class="md"><p>Upon reading the guide I want to just point out I ended up having to fully factory reset my NAS due to that fact quickly after setting up nginx on docker I could no longer access my webgui. </p> <p>Anyways I noticed from the compose file on npm (nginx proxy manager) you can either set it up with mariadb or without. What is the difference? The youtube guide I was going to follow used the DB but why?</p> <p>Also if I have tailscale on my system since I also notice nginxy proxy manger uses port 443 and 80 will this interfere with having tailscale on my system?</p> <p>The reason I ask is because tailscale shows on the compose file that its using nginx somehow. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Swiss_Meats"> /u/Swiss_Meats </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjff3j/what_the_point_of_db_for_npm/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhost

## [Help] OwnCloud Docker the jwt_secret has not been set properly
 - [https://www.reddit.com/r/selfhosted/comments/1hjey3o/help_owncloud_docker_the_jwt_secret_has_not_been](https://www.reddit.com/r/selfhosted/comments/1hjey3o/help_owncloud_docker_the_jwt_secret_has_not_been)
 - RSS feed: $source
 - date published: 2024-12-21T17:44:53+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hjey3o/help_owncloud_docker_the_jwt_secret_has_not_been/"> <img src="https://a.thumbs.redditmedia.com/xWuFVhuBjPGmwEfVhMpEz7_AVBAmL7eqhn4Lv08ii74.jpg" alt="[Help] OwnCloud Docker the jwt_secret has not been set properly" title="[Help] OwnCloud Docker the jwt_secret has not been set properly" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Following this tutorial <a href="https://helgeklein.com/blog/owncloud-infinite-scale-with-openid-connect-authentication-for-home-networks/">https://helgeklein.com/blog/owncloud-infinite-scale-with-openid-connect-authentication-for-home-networks/</a> I can’t access or properly run OCIS in docker environment. I uploaded the compose.yml and the .env file i used. And the error. Could someone point me to better tutorial or a fix? Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MKBUHD"> /u/MKBUHD </a> <br/> <span><a href="https://www.r

## A silly QuEsTiOn
 - [https://www.reddit.com/r/selfhosted/comments/1hjdzk1/a_silly_question](https://www.reddit.com/r/selfhosted/comments/1hjdzk1/a_silly_question)
 - RSS feed: $source
 - date published: 2024-12-21T17:00:41+00:00

<!-- SC_OFF --><div class="md"><p>i found about this project on github <a href="https://github.com/robinkarlberg/transfer.zip-web">https://github.com/robinkarlberg/transfer.zip-web</a> can i send files to people that are outside of the local network ? or do they have to be on same local network </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Neat_Delivery6162"> /u/Neat_Delivery6162 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjdzk1/a_silly_question/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjdzk1/a_silly_question/">[comments]</a></span>

## Open-source software for a self hosted drive
 - [https://www.reddit.com/r/selfhosted/comments/1hjdyh8/opensource_software_for_a_self_hosted_drive](https://www.reddit.com/r/selfhosted/comments/1hjdyh8/opensource_software_for_a_self_hosted_drive)
 - RSS feed: $source
 - date published: 2024-12-21T16:59:28+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I am looking for an open-source software that can manage files, photos and videos (stored in my own storage, I will probably buy a Synology NAS for that) and provides a web interface in the same way than Google Drive for example.</p> <p>I have already checked Seafile, but it is said that developers use questionable practices in their code and some features might be obsolete.</p> <p>Other softwares I can find are not opensource</p> <p>May I get some help please ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Beginning-Error-6970"> /u/Beginning-Error-6970 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjdyh8/opensource_software_for_a_self_hosted_drive/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjdyh8/opensource_software_for_a_self_hosted_drive/">[comments]</a></span>

## Status of self-hosted photo frame setups (webdav)
 - [https://www.reddit.com/r/selfhosted/comments/1hjd3u3/status_of_selfhosted_photo_frame_setups_webdav](https://www.reddit.com/r/selfhosted/comments/1hjd3u3/status_of_selfhosted_photo_frame_setups_webdav)
 - RSS feed: $source
 - date published: 2024-12-21T16:18:38+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve seen a lot of posts about supporting a self-hosted photo frame setup from a year or more ago, and I&#39;m wondering what the status is as we approach 2025. It looks like the best options so far are using an android tablet with WebDAV connection, or an RPI With some sort of display running fotoo.</p> <p>Has there been any additional progress in this front?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fraun_Pollen"> /u/Fraun_Pollen </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjd3u3/status_of_selfhosted_photo_frame_setups_webdav/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjd3u3/status_of_selfhosted_photo_frame_setups_webdav/">[comments]</a></span>

## Sourcing hard drives in Spain/Europe
 - [https://www.reddit.com/r/selfhosted/comments/1hjcl7z/sourcing_hard_drives_in_spaineurope](https://www.reddit.com/r/selfhosted/comments/1hjcl7z/sourcing_hard_drives_in_spaineurope)
 - RSS feed: $source
 - date published: 2024-12-21T15:53:58+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m in the process of repurposing my old PC into a server and have most of the hardware figured out, except for the storage aspect. Ideally, I want to start with a minimum of two drives for backups, but I&#39;m uncertain about what to expect beyond that. </p> <p>I&#39;m looking to spend a maximum of 200 EUR, which would allow for 6-10 TB drives, but I&#39;m unsure how this will impact future expandability, especially regarding RAID or ZRAID configurations. </p> <p>For the US, I&#39;m familiar with sites like ServerPartDeals, GoHardDrive, and shucks.top, but my search for similar sites or sellers in Europe, particularly Spain, has only led me to <a href="https://diskprices.com/">https://diskprices.com/</a>. </p> <p>Aside from that, it seems that &quot;professional&quot; eBay sellers are my only other option, but I&#39;m concerned about the potential risks involved with purchasing from them (although I assume I&#39;ll <em>probably be fine</em> from

## Create your own TV channels
 - [https://www.reddit.com/r/selfhosted/comments/1hjcb7c/create_your_own_tv_channels](https://www.reddit.com/r/selfhosted/comments/1hjcb7c/create_your_own_tv_channels)
 - RSS feed: $source
 - date published: 2024-12-21T15:40:19+00:00

<!-- SC_OFF --><div class="md"><p>Think ytch but on steriods 💪 <a href="https://FreeTvz.com">https://FreeTvz.com</a> </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/01princejon01"> /u/01princejon01 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjcb7c/create_your_own_tv_channels/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjcb7c/create_your_own_tv_channels/">[comments]</a></span>

## The Self-Hoster's Library
 - [https://www.reddit.com/r/selfhosted/comments/1hjc8vs/the_selfhosters_library](https://www.reddit.com/r/selfhosted/comments/1hjc8vs/the_selfhosters_library)
 - RSS feed: $source
 - date published: 2024-12-21T15:37:03+00:00

<!-- SC_OFF --><div class="md"><p>There have been a few posts recently on this sub from people who are getting started with self-hosting, which is brilliant. There are a bunch of things that you need to learn along the way. This community is supportive but sometimes you need to pick up a broader understanding than you can get from specific questions (and often a diversity of response).</p> <p>So fellow self-hosters: which books would you recommend to someone getting started? What is the book and what did you learn from it?</p> <p><em>Unix and Linux System Administration Handbook</em> <a href="https://archive.org/details/evi-nemeth-garth-snyder-trent-r.-hein-unix-and-linux-system-administration-handbook-4th-edition-2010/page/n41/mode/2up">Nemeth and Snyder</a> et al</p> <p>This taught me not just how to be a System Administrator but what a SysAdmin&#39;s function was and why. It explains how all the bits work without being patronising or stupidly complex. And it is so comprehensive. D

## Need help with docker compose - about to go mad
 - [https://www.reddit.com/r/selfhosted/comments/1hjc4ls/need_help_with_docker_compose_about_to_go_mad](https://www.reddit.com/r/selfhosted/comments/1hjc4ls/need_help_with_docker_compose_about_to_go_mad)
 - RSS feed: $source
 - date published: 2024-12-21T15:31:21+00:00

<!-- SC_OFF --><div class="md"><p>So I&#39;ve been tinkering with selfhosting some stuff via docker (compose). I got Tandoor working fine and had Homarr running for a short while, working fine. I tried setting up Caddy - didn&#39;t work - and now I&#39;m getting warnings even for Tandoor. Every time I spin Tandoor up or down via docker compose I get the following warnings: <code> ~$ docker compose down WARN[0000] The &quot;F9vVg7N9yMm8XN9gDYS&quot; variable is not set. Defaulting to a blank string. WARN[0000] The &quot;W&quot; variable is not set. Defaulting to a blank string. WARN[0000] The &quot;dy&quot; variable is not set. Defaulting to a blank string. WARN[0000] The &quot;F9vVg7N9yMm8XN9gDYS&quot; variable is not set. Defaulting to a blank string. WARN[0000] The &quot;W&quot; variable is not set. Defaulting to a blank string. WARN[0000] The &quot;dy&quot; variable is not set. Defaulting to a blank string. WARN[0000] The &quot;F9vVg7N9yMm8XN9gDYS&quot; variable is not set. Defaul

## Is there a reason to use Neon or any other hosted db?
 - [https://www.reddit.com/r/selfhosted/comments/1hjc14e/is_there_a_reason_to_use_neon_or_any_other_hosted](https://www.reddit.com/r/selfhosted/comments/1hjc14e/is_there_a_reason_to_use_neon_or_any_other_hosted)
 - RSS feed: $source
 - date published: 2024-12-21T15:26:35+00:00

<!-- SC_OFF --><div class="md"><p>I don&#39;t understand really,</p> <p>Does any of these services provide super features that running a postgres container on your vps won&#39;t?</p> <p>Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/waelnassaf"> /u/waelnassaf </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjc14e/is_there_a_reason_to_use_neon_or_any_other_hosted/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjc14e/is_there_a_reason_to_use_neon_or_any_other_hosted/">[comments]</a></span>

## P2P website
 - [https://www.reddit.com/r/selfhosted/comments/1hjbw97/p2p_website](https://www.reddit.com/r/selfhosted/comments/1hjbw97/p2p_website)
 - RSS feed: $source
 - date published: 2024-12-21T15:19:45+00:00

<!-- SC_OFF --><div class="md"><p>I love this website is there any other websites like it that I can self host <a href="https://p2pfileshare.com/">https://p2pfileshare.com/</a></p> <p>I have tried these toffeeshare pairdrop snapdrop blaze womewhole croc filepizza</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Neat_Delivery6162"> /u/Neat_Delivery6162 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjbw97/p2p_website/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjbw97/p2p_website/">[comments]</a></span>

## Self-Hosted Solution for Mail Composition Based on Selected Products
 - [https://www.reddit.com/r/selfhosted/comments/1hjbsej/selfhosted_solution_for_mail_composition_based_on](https://www.reddit.com/r/selfhosted/comments/1hjbsej/selfhosted_solution_for_mail_composition_based_on)
 - RSS feed: $source
 - date published: 2024-12-21T15:14:19+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a <strong>self-hosted solution</strong> that can help me streamline my workflow. Here&#39;s what I need:</p> <p>I often have to select specific products or options and then respond to inquiries by email. Each time, I need to check which options are possible for the selected product and compose an email with the relevant details. The issue is that I frequently write the same text repeatedly for different inquiries, which is time-consuming.</p> <p>Ideally, the solution should:</p> <ol> <li>Allow me to select products and associated options.</li> <li>Automatically generate predefined text snippets for the selected items.</li> <li>Provide an interface where I can review and adjust the text before sending.</li> </ol> <p>It’s essential that the solution is <strong>self-hosted</strong>, as I want full control over the data and functionality. Bonus points if it supports templates or has a user-friendly interface!</p> <p>Does anyone know o

## Geoblock in Traefik or Traefik+CF tunnels?
 - [https://www.reddit.com/r/selfhosted/comments/1hjbrzd/geoblock_in_traefik_or_traefikcf_tunnels](https://www.reddit.com/r/selfhosted/comments/1hjbrzd/geoblock_in_traefik_or_traefikcf_tunnels)
 - RSS feed: $source
 - date published: 2024-12-21T15:13:40+00:00

<!-- SC_OFF --><div class="md"><p>hello community!</p> <p>I am trying to improve security for my exposed services (VPS / docker containers / everything behind traefik). I host NocoDB, RocketChat, n8n, a few Wordpress instances just to play develop themes, vaultwarden and planning to add more).</p> <p>Soon I will getting one or two 1L pcs to add a few TB of storage for serving as my self-hosted file drive (MinIO, filestash or something else), perhaps even serving as storage for Immich (no experience with it yet).</p> <p>What&#39;s the most recommended approach by the experienced members?</p> <ol> <li>Adding geoblock plugin to traefik sounds like the lowest hanging fruit (I expect lots of tinkering hours to get it working but then it is mainly replicating to all containers),</li> <li>Or should I invest some time learning about CF tunnels? If so, do I still use traefik as reverse proxy with my domains (e.g. vault.domain.com) and then CF is another layer? or when CF tunnels are used ther

## Any recommendations for a self hosted QR code generator that I can host on my cpanel based hosting server?
 - [https://www.reddit.com/r/selfhosted/comments/1hjbqj8/any_recommendations_for_a_self_hosted_qr_code](https://www.reddit.com/r/selfhosted/comments/1hjbqj8/any_recommendations_for_a_self_hosted_qr_code)
 - RSS feed: $source
 - date published: 2024-12-21T15:11:36+00:00

<!-- SC_OFF --><div class="md"><p>I currently use <a href="http://goqr.me/api/">goqr.me/api/</a> to generate QR codes for the page URL that is currently opened in the browser. The display of QR is to help users share the link easily through their phones.</p> <p>I absolutely love this API for its simplicity; to give you an example this is the link get the QR,</p> <p><code>https://api.qrserver.com/v1/create-qr-code/?size=150x150&amp;data=[MY_PAGE_URL]</code></p> <p>I just replace <code>MY_PAGE_URL</code> with the current page link, add it to my IMG SRC attribute and voila I&#39;ve got the QR image.</p> <p>All is good generally but sometimes I&#39;ve noticed the service is down resulting in user complaints. Moreover, it doesn&#39;t feel right hogging their resources for free.</p> <p>So I am looking for similar programs that I can host on my own server and generate these QR&#39;s myself without having to worry about the said issue.</p> <p>Any suggestions?</p> </div><!-- SC_ON --> &#32; s

## docker - qbittorent - The bound address is already in use
 - [https://www.reddit.com/r/selfhosted/comments/1hjbo0b/docker_qbittorent_the_bound_address_is_already_in](https://www.reddit.com/r/selfhosted/comments/1hjbo0b/docker_qbittorent_the_bound_address_is_already_in)
 - RSS feed: $source
 - date published: 2024-12-21T15:08:05+00:00

<!-- SC_OFF --><div class="md"><p>Recently I deployed arr-stack (via portainer) running behind gluetun vpn. Everything works fine but until I need to either restart (or re-deploy) the stack or qBittorent container. Then qBittorent is not available due to error shown in logs:</p> <p>Recently I deployed arr-stack (via portainer) running behind gluetun vpn. Everything works fine but until I need to either restart (or re-deploy) the stack or qBittorent container. Then qBittorent is not available due to error shown in logs:</p> <pre><code>[custom-init] No custom files found, skipping... WebUI will be started shortly after internal preparations. Please wait... &quot;WebUI: Unable to bind to IP: , port: 8085. Reason: The bound address is already in use&quot; Unable to bind to IP: , port: 8085. Reason: The bound address is already in use ******** Information ******** To fix the error, you may need to edit the config file manually. Connection to 8085 port [tcp/*] succeeded! [ls.io-init] done.

## DynDNS Point to port 80.
 - [https://www.reddit.com/r/selfhosted/comments/1hjbe7p/dyndns_point_to_port_80](https://www.reddit.com/r/selfhosted/comments/1hjbe7p/dyndns_point_to_port_80)
 - RSS feed: $source
 - date published: 2024-12-21T14:54:11+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I want my adress <a href="http://www.adress.de">http://www.adress.de</a>, <a href="http://homeassistant.adress.de">http://homeassistant.adress.de</a>, <a href="http://api.adress.de">http://api.adress.de</a> to point to my local raspberry pi, port 80 (I resolve subdoamins using nginx). It instead shows the router interface, outside the home network nothing works. (MY router is fritz!box, germany). I have set up my dyndns and it must be working becuase it points to router, right? Im bought my domain at Strato. MyDYNDNS: PostURL: <a href="https://adress.de:password@dyndns.strato.com/nic/update?hostname=adress.de">https://adress.de:password@dyndns.strato.com/nic/update?hostname=adress.de</a> Doamin Name: <a href="http://adress.de">adress.de</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Feisty-Staff-662"> /u/Feisty-Staff-662 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjbe7p/d

## Downloading Spotify saves for classic iPod
 - [https://www.reddit.com/r/selfhosted/comments/1hjb9al/downloading_spotify_saves_for_classic_ipod](https://www.reddit.com/r/selfhosted/comments/1hjb9al/downloading_spotify_saves_for_classic_ipod)
 - RSS feed: $source
 - date published: 2024-12-21T14:47:24+00:00

<!-- SC_OFF --><div class="md"><p>I’m purchasing a 5th gen classic and realistically would like my entire Spotify saved songs as the music on the classic.</p> <p>I have over 4k saved songs currently in my, my saved Spotify playlist. That would take forever to download manually like I did in the days I actually used a iPod classic. </p> <p>Does a program exist that I can essentially clone this playlist and download I just can’t imagine how long it would take to do the old way. </p> <p>I’m not really knowledgeable about tech stuff so sorry if this is silly 😅</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lifeonmars111"> /u/lifeonmars111 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjb9al/downloading_spotify_saves_for_classic_ipod/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hjb9al/downloading_spotify_saves_for_classic_ipod/">[comments]</a></span>

## Synology: Read-only. Strategy for backing up & restoring data?
 - [https://www.reddit.com/r/selfhosted/comments/1hjak3y/synology_readonly_strategy_for_backing_up](https://www.reddit.com/r/selfhosted/comments/1hjak3y/synology_readonly_strategy_for_backing_up)
 - RSS feed: $source
 - date published: 2024-12-21T14:09:02+00:00

<!-- SC_OFF --><div class="md"><p>I have a Synology DS920+ which recently went into read-only mode. Not clear as to why, but Synology support believed it may have been faulty RAM, which I have replaced.</p> <p>The issue is I now have 10TB of data which is stuck in read-only mode. </p> <p>Tech support suggested backing up to an external source (either remotely or to another NAS), recreate my volume, then restoring the data.</p> <p><strong>I&#39;m looking for advice on the best strategy on how to do that.</strong></p> <p>Options I am considering:</p> <ol> <li> <strong>Offload to a cloud</strong> <ol> <li>Not sure of costs to temporarily offload 100TB to blob storage.</li> </ol></li> <li><strong>Backup to my 2nd Synology unit, DS220J (currently not in use)</strong> <ol> <li>Buy 2x 12 HDDs, which I am fine with doing, as I would like to use those in my DS920+ anyway.</li> </ol></li> </ol> <p>On my 920+ I have 4 drives: </p> <ol> <li>3.6TB</li> <li>3.6 TB</li> <li>9.1 TB</li> <li>9.1 TB</

## Gitlab install help
 - [https://www.reddit.com/r/selfhosted/comments/1hj9oi9/gitlab_install_help](https://www.reddit.com/r/selfhosted/comments/1hj9oi9/gitlab_install_help)
 - RSS feed: $source
 - date published: 2024-12-21T13:19:16+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I would like to deploy Gitlab in a k8s cluster but I see in the doc that we can&#39;t prod for stateful components. Is there a way to install Gitlab on the entire cluster?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dismal-Mud-5725"> /u/Dismal-Mud-5725 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj9oi9/gitlab_install_help/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj9oi9/gitlab_install_help/">[comments]</a></span>

## Looking for the best cloud drive for Duplicati
 - [https://www.reddit.com/r/selfhosted/comments/1hj9fih/looking_for_the_best_cloud_drive_for_duplicati](https://www.reddit.com/r/selfhosted/comments/1hj9fih/looking_for_the_best_cloud_drive_for_duplicati)
 - RSS feed: $source
 - date published: 2024-12-21T13:03:30+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I am looking for the best way to backup my self hosted server and all of its data with Duplicati. I need to choose a cloud drive or S3 service for this but there is so much options and I am getting lost.</p> <p>The service does not need to encrypt data as Duplicati does it itself before sending.</p> <p>I am looking for at least 1TB to not have to change for a few years. I am looking for both lifetime plans or annual subscriptions.</p> <p>Here is the options I have found :</p> <ol> <li>Internxt. 2TB lifetime for 180€. Webdav compatible. Looks like the best option so far.</li> <li>Koofr. 1TB lifetime for 120€. Integrated in Duplicati.</li> <li>ShadowDrive. 2TB for 50€/year. Webdav compatible.</li> <li>Kdrive. 2TB for 53chf/year. Webdav compatible.</li> <li>Leviia. 1TB for 64€/year. Webdav compatible.</li> <li>pCloud. 1TB lifetime for 400€.</li> <li>Icedrive. 2TB lifetime for 480€.</li> </ol> <p>I have looked into PrismDrive that looks like a

## Struggling with local domains, Caddy + AdGuard Home DNS
 - [https://www.reddit.com/r/selfhosted/comments/1hj8sbq/struggling_with_local_domains_caddy_adguard_home](https://www.reddit.com/r/selfhosted/comments/1hj8sbq/struggling_with_local_domains_caddy_adguard_home)
 - RSS feed: $source
 - date published: 2024-12-21T12:21:38+00:00

<!-- SC_OFF --><div class="md"><p>I have both Caddy and Adguard running on 192.168.2.15, my Sonarr instance is running on 192.168.2.50:8989</p> <p>Caddy config looks like this:</p> <pre><code>sonarr.local { reverse_proxy 192.168.2.50:8989 tls internal } </code></pre> <p>DNS rewrite in AdGuard is sonarr.local that points to <a href="http://192.168.2.15">192.168.2.15</a></p> <p>When I access the sonarr.local it just goes to a blank page without any content, how do I need to do this to set it up?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/POTTERMAN1"> /u/POTTERMAN1 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj8sbq/struggling_with_local_domains_caddy_adguard_home/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj8sbq/struggling_with_local_domains_caddy_adguard_home/">[comments]</a></span>

## Solution for All Tasks
 - [https://www.reddit.com/r/selfhosted/comments/1hj83m4/solution_for_all_tasks](https://www.reddit.com/r/selfhosted/comments/1hj83m4/solution_for_all_tasks)
 - RSS feed: $source
 - date published: 2024-12-21T11:34:13+00:00

<!-- SC_OFF --><div class="md"><p>Hello all. As the title states, I am looking for your suggestions on a solution where I can put the most basic to the most infrequent reminders/tasks in one location and be alerted when they need to be done.</p> <p>Such as: check HVAC filters monthly, trash every week, recycling bi-weekly, and so on.</p> <p>Thanks everyone!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Wiltify"> /u/Wiltify </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj83m4/solution_for_all_tasks/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj83m4/solution_for_all_tasks/">[comments]</a></span>

## Automatic updates
 - [https://www.reddit.com/r/selfhosted/comments/1hj80gf/automatic_updates](https://www.reddit.com/r/selfhosted/comments/1hj80gf/automatic_updates)
 - RSS feed: $source
 - date published: 2024-12-21T11:28:00+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys…so, I’ve taken a look at my notes for my self-hosted homelab and, well, there’s quite a few containers that will need updating…while I do like the idea of just getting notifications and update whenever I want to, I’d rather set up something like Watchtower to have them all update automatically. The thing I’m worried about though is that the last update to Watchtower was January…so, I’m kind of left wondering if there’s an alternative to it…</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MrPanda011"> /u/MrPanda011 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj80gf/automatic_updates/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj80gf/automatic_updates/">[comments]</a></span>

## Selfhosting audit and help needed for backup solution
 - [https://www.reddit.com/r/selfhosted/comments/1hj78hj/selfhosting_audit_and_help_needed_for_backup](https://www.reddit.com/r/selfhosted/comments/1hj78hj/selfhosting_audit_and_help_needed_for_backup)
 - RSS feed: $source
 - date published: 2024-12-21T10:30:33+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hj78hj/selfhosting_audit_and_help_needed_for_backup/"> <img src="https://b.thumbs.redditmedia.com/oGE5kUXFO8KtarTBSrQjOP_ka7_W3stCCLGKqMXY6Ws.jpg" alt="Selfhosting audit and help needed for backup solution" title="Selfhosting audit and help needed for backup solution" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/xbkejg4uh68e1.png?width=1890&amp;format=png&amp;auto=webp&amp;s=2b0fac014df8d5dbfcf09aff81f9af1bd180fe6b">https://preview.redd.it/xbkejg4uh68e1.png?width=1890&amp;format=png&amp;auto=webp&amp;s=2b0fac014df8d5dbfcf09aff81f9af1bd180fe6b</a></p> <p>I&#39;ve been homelabbing for a couple of years now and have built a setup that is sort of a Frankenstein that&#39;s appeared as I&#39;ve learnt.</p> <p>The one thing that is obvious is my lack of any backup solution across my rather messy setup.</p> <p>I&#39;d love some advice from any of you that&#39;s got more experience 

## How safe is it to host your own password manager with cloudflare tunnel for access?
 - [https://www.reddit.com/r/selfhosted/comments/1hj6zc0/how_safe_is_it_to_host_your_own_password_manager](https://www.reddit.com/r/selfhosted/comments/1hj6zc0/how_safe_is_it_to_host_your_own_password_manager)
 - RSS feed: $source
 - date published: 2024-12-21T10:11:19+00:00

<!-- SC_OFF --><div class="md"><p>How secure am I hosting my own password manager using cloudflare tunnel. I already host my own nextcloud over a tunnel. With geo restrictions and bot blocking but a password manager seems even more scary. But I also don&#39;t really want to use a VPN all the time especially for my cloud as it&#39;s something I want to be able to acces out of the box everywhere. What can I do and should?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Robotix_47"> /u/Robotix_47 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj6zc0/how_safe_is_it_to_host_your_own_password_manager/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj6zc0/how_safe_is_it_to_host_your_own_password_manager/">[comments]</a></span>

## a basic question?
 - [https://www.reddit.com/r/selfhosted/comments/1hj62kp/a_basic_question](https://www.reddit.com/r/selfhosted/comments/1hj62kp/a_basic_question)
 - RSS feed: $source
 - date published: 2024-12-21T09:00:47+00:00

<!-- SC_OFF --><div class="md"><p>i am new to servers stuff<br/> i was installing navidrome linux (not docker)<br/> <a href="https://www.navidrome.org/docs/installation/linux/#create-directory-structure">https://www.navidrome.org/docs/installation/linux/#create-directory-structure</a><br/> i understood that &lt;user&gt; means the user on the system<br/> but what does &lt;group&gt; mean<br/> can someone explain with example please...</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DependentAbroad661"> /u/DependentAbroad661 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj62kp/a_basic_question/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj62kp/a_basic_question/">[comments]</a></span>

## Enforce security for your web servers
 - [https://www.reddit.com/r/selfhosted/comments/1hj61ln/enforce_security_for_your_web_servers](https://www.reddit.com/r/selfhosted/comments/1hj61ln/enforce_security_for_your_web_servers)
 - RSS feed: $source
 - date published: 2024-12-21T08:58:48+00:00

<!-- SC_OFF --><div class="md"><p>Helo selfhosters, it&#39;s saturday! </p> <p>How to waste some time today? Let enforce a bit of security on your selfhosted web servers :)</p> <p>This because I started this simple GitHub project to let you generate (or download) OWASP and bad bots rules for most popular web servers like Nginx, Apache, Caddy, Traefik and HaProxy.</p> <p>You all welcome to enjoy and contribute to the project with your thoughts, feedbacks and PRs ;)</p> <h1>📌 Project Highlights</h1> <ul> <li><strong>🛡️ OWASP CRS Protection</strong> – Leverages OWASP Core Rule Set for web application firewall (WAF) defense.</li> <li><strong>🤖 Bad Bot Blocking</strong> – Blocks known malicious bots using public bot lists.</li> <li><strong>⚙️ Multi-Web Server Support</strong> – Generates WAF configs for <strong>Apache, Nginx, Caddy, Traefik, and HAProxy</strong>.</li> <li><strong>🔄 Automatic Updates</strong> – GitHub Actions fetch new rules <strong>daily</strong> and push updated configs.

## Booting an existing OS install from another drive with Proxmox
 - [https://www.reddit.com/r/selfhosted/comments/1hj5pb2/booting_an_existing_os_install_from_another_drive](https://www.reddit.com/r/selfhosted/comments/1hj5pb2/booting_an_existing_os_install_from_another_drive)
 - RSS feed: $source
 - date published: 2024-12-21T08:32:24+00:00

<!-- SC_OFF --><div class="md"><p>Hello, From my cursory research I&#39;ve found some old posts mentioning this is possible but I wanted to see if anyone knew of an updated method for doing this simply.</p> <p>My setup is as follows: 500gb SSD with Ubuntu, configured already with my homelab software (mostly docker) and my NAS utilizing a RAID 5 array of 3TB drives in the system.</p> <p>Additional 500gb SSD with a clean Proxmox install. </p> <p>I would like to ideally be able to always boot from the proxmox installation and run the Ubuntu disk through proxmox alongside other VMs. Of course with the condition that I can always decide to just unplug the proxmox disk and reboot solely on the Ubuntu drive.</p> <p>Thanks in advance for any advice. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Miserable-Twist8344"> /u/Miserable-Twist8344 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj5pb2/booting_an_existing_os_install_fro

## Is there any tunneling programs?
 - [https://www.reddit.com/r/selfhosted/comments/1hj5kjv/is_there_any_tunneling_programs](https://www.reddit.com/r/selfhosted/comments/1hj5kjv/is_there_any_tunneling_programs)
 - RSS feed: $source
 - date published: 2024-12-21T08:22:00+00:00

<!-- SC_OFF --><div class="md"><p>Well, I want to host my minecraft server, and I cant physically open my ports via router settiongs, because my provider is shitty, and i used ngrok, until they limited bandwidth to thec 1gb per month. I tried <a href="http://playit.gg">playit.gg</a>, but, i have ping around 400ms so its the issue. Also I dont have any possible vps solution, which is so annying, cuz my debit card is cant be approved by oracle or google free tier. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok_Bookkeeper3285"> /u/Ok_Bookkeeper3285 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj5kjv/is_there_any_tunneling_programs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj5kjv/is_there_any_tunneling_programs/">[comments]</a></span>

## Mail reception and emission
 - [https://www.reddit.com/r/selfhosted/comments/1hj5ffk/mail_reception_and_emission](https://www.reddit.com/r/selfhosted/comments/1hj5ffk/mail_reception_and_emission)
 - RSS feed: $source
 - date published: 2024-12-21T08:10:49+00:00

<!-- SC_OFF --><div class="md"><p>For inbound there seem to be free forwarding, but what about emission? I&#39;ve heard few services does it for free but idk the name of the service (like inbound=mail forwarding, outbound=?) and idk aswell who does it for free</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/xmmr"> /u/xmmr </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj5ffk/mail_reception_and_emission/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj5ffk/mail_reception_and_emission/">[comments]</a></span>

## New to self hosting and looking for tips and recommendations
 - [https://www.reddit.com/r/selfhosted/comments/1hj599w/new_to_self_hosting_and_looking_for_tips_and](https://www.reddit.com/r/selfhosted/comments/1hj599w/new_to_self_hosting_and_looking_for_tips_and)
 - RSS feed: $source
 - date published: 2024-12-21T07:58:29+00:00

<!-- SC_OFF --><div class="md"><p>So I have an old (read as no longer used) windows desktop that is just taking up space and I was thinking about turning it into a hosting machine if for no other reason then for the learning experience. What are some services/applications that are beginner friendly, free/affordable, and useful applications that I should consider giving a shot? Thank you for your time and have a happy holidays :)</p> <p>Specs: </p> <p>Win 11 Pro</p> <p>i5 9600k @ 3.7GHz</p> <p>GTX 1070</p> <p>32GB of 2666hz DDR4 ram</p> <p>1TB SATA HDD</p> <p>500GB SATA HDD</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dragin410"> /u/Dragin410 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj599w/new_to_self_hosting_and_looking_for_tips_and/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj599w/new_to_self_hosting_and_looking_for_tips_and/">[comments]</a></span>

## Symfonium dev response to critical review
 - [https://www.reddit.com/r/selfhosted/comments/1hj585n/symfonium_dev_response_to_critical_review](https://www.reddit.com/r/selfhosted/comments/1hj585n/symfonium_dev_response_to_critical_review)
 - RSS feed: $source
 - date published: 2024-12-21T07:56:07+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Jimbuscus"> /u/Jimbuscus </a> <br/> <span><a href="https://np.reddit.com/r/androidapps/comments/1hhz8qw/whats_your_favorite_underrated_app_that_you/m2yfbzs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj585n/symfonium_dev_response_to_critical_review/">[comments]</a></span>

## Saturday-morning cartoons
 - [https://www.reddit.com/r/selfhosted/comments/1hj51vk/saturdaymorning_cartoons](https://www.reddit.com/r/selfhosted/comments/1hj51vk/saturdaymorning_cartoons)
 - RSS feed: $source
 - date published: 2024-12-21T07:42:38+00:00

<!-- SC_OFF --><div class="md"><p>Had an idea this morning: a program (yeah, an app, sure) that connects to your Jellyfin (or Emby, I just use Jellyfish) instance and plays a few random episodes from selected shows for a few hours on weekends.</p> <p>This sounds very specific, but maybe anyone knows of an existing project that does this or something similar?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DMan1629"> /u/DMan1629 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj51vk/saturdaymorning_cartoons/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj51vk/saturdaymorning_cartoons/">[comments]</a></span>

## I am stuck with ssh tuneling
 - [https://www.reddit.com/r/selfhosted/comments/1hj4xwb/i_am_stuck_with_ssh_tuneling](https://www.reddit.com/r/selfhosted/comments/1hj4xwb/i_am_stuck_with_ssh_tuneling)
 - RSS feed: $source
 - date published: 2024-12-21T07:33:59+00:00

<!-- SC_OFF --><div class="md"><p>My setup: A old dvr and router both doesn&#39;t have any internet connection.</p> <p>dvr is connected to the router via Ethernet , my android device connected to router via wifi</p> <p>I don&#39;t have any desktop locally. (only an android device)</p> <p>a remote windows which I can ssh into and also rdp into it via phone</p> <p>Problem: dvr has a crap activex interface , only accessible via Internet explorer</p> <p>i am able to set a tunnel - by using on my android ssh -i /storage/emulated/0/Download/ssh_host_rsa_key.pub -R 8080:192.168.29.215:80 <a href="mailto:vaibhav@20.93.xxx.xx">vaibhav@20.93.xxx.xx</a></p> <p>after this I could login into the windows interface , and see the html + activex interface (Web login of dvr) when I try to login I get can&#39;t find device . </p> <p>any help would be appreciated </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ImpossibleTreat3533"> /u/ImpossibleTreat3533 </a> <br/

## Book Manager/Reader?
 - [https://www.reddit.com/r/selfhosted/comments/1hj4szd/book_managerreader](https://www.reddit.com/r/selfhosted/comments/1hj4szd/book_managerreader)
 - RSS feed: $source
 - date published: 2024-12-21T07:23:34+00:00

<!-- SC_OFF --><div class="md"><p>So I&#39;m looking for a alternative e-book library like Kindle, that&#39;ll allow me to read on different devices. I mainly read on my Phone, PC and Kindle. I have a collection of books, manga, and lightnovels some of which can only be read on my phone/pc as they are colored.</p> <p>Is there anything that can do :</p> <p>- Sync between devices</p> <p>- Have a reader/be able to connect to a reader like Moon+ Reader</p> <p>- Possible metadata editing? I have Calibre so it&#39;s fine even if this isn&#39;t availible</p> <p>I checked out some possible options and found Librum(Good, but no android app), Kavita(No android app, mainly for comics), Kodoo(looks really good, no android app)</p> <p>Is there any *free* methods through which I can accomplish this? I&#39;m new to self hosting, just made a Jellyfin server with Ubuntu, and am now looking for Books</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Leo_Expose"> /u

## For those who recommend Symfonium for Navidrome etc, please consider this exchange between the developer and a customer.
 - [https://www.reddit.com/r/selfhosted/comments/1hj484h/for_those_who_recommend_symfonium_for_navidrome](https://www.reddit.com/r/selfhosted/comments/1hj484h/for_those_who_recommend_symfonium_for_navidrome)
 - RSS feed: $source
 - date published: 2024-12-21T06:41:16+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Jimbuscus"> /u/Jimbuscus </a> <br/> <span><a href="https://np.reddit.com/r/androidapps/comments/1hhz8qw/whats_your_favorite_underrated_app_that_you/m33opcc/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj484h/for_those_who_recommend_symfonium_for_navidrome/">[comments]</a></span>

## I'm questioning my proxmox server hard drive set up. What do you think?
 - [https://www.reddit.com/r/selfhosted/comments/1hj3d8o/im_questioning_my_proxmox_server_hard_drive_set](https://www.reddit.com/r/selfhosted/comments/1hj3d8o/im_questioning_my_proxmox_server_hard_drive_set)
 - RSS feed: $source
 - date published: 2024-12-21T05:42:59+00:00

<!-- SC_OFF --><div class="md"><p>I bought a small desktop (HP Elite Mini 800 G9) with the intent of moving all my docker containers to this new server. I installed 96GB of memory in it and two 2TB NVMe drives. I put the drives in a ZFS mirror array, so I have 2TB of disk space.</p> <p>My main purpose for this server is for Docker. I created an Ubuntu VM and installed Docker. I gave this Docker VM 32GB of hard drive space. My old docker servers had less than 2GB of data so I thought 32GB of drive space would be more than enough. I failed to take into account the size of the Docker images. And I&#39;m running low on space in the 32GB virtual hard drive the Docker server is installed on.</p> <p>I also built a VM running Home Assistant. I had hoped to run the Proxmox VM images and the docker data volumes mounted on ZFS shares on a NAS. But when I tried that it was causing issues with SQLLite databases and other things (security, etc).</p> <p>My questions:</p> <p>1) What size hard drive 

## noob here so be mindful- have 1 tiny pc with i3 9th gen, 2 external hdd 4tb each, lot of free time. how do i start my jellyfin sonarr prawlarr radarr journey?
 - [https://www.reddit.com/r/selfhosted/comments/1hj2yac/noob_here_so_be_mindful_have_1_tiny_pc_with_i3](https://www.reddit.com/r/selfhosted/comments/1hj2yac/noob_here_so_be_mindful_have_1_tiny_pc_with_i3)
 - RSS feed: $source
 - date published: 2024-12-21T05:16:30+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Old-March-5273"> /u/Old-March-5273 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj2yac/noob_here_so_be_mindful_have_1_tiny_pc_with_i3/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj2yac/noob_here_so_be_mindful_have_1_tiny_pc_with_i3/">[comments]</a></span>

## That feeling when you get something to finally work! Thank you guys!
 - [https://www.reddit.com/r/selfhosted/comments/1hj2uht/that_feeling_when_you_get_something_to_finally](https://www.reddit.com/r/selfhosted/comments/1hj2uht/that_feeling_when_you_get_something_to_finally)
 - RSS feed: $source
 - date published: 2024-12-21T05:10:01+00:00

<!-- SC_OFF --><div class="md"><p>A few days ago i made a post venting my frustration when I wasn&#39;t able to get a few things working properly and just ended up breaking my server a few times. I got a ton of encouraging responses telling me to take some time off and that it was just growing pains from leaning how to self host.</p> <p>Today I decided to start with something I didn&#39;t think would break anything and that was connecting my UPS to my server, I&#39;ve had this rhing for 8 months and didn&#39;t even know it was a thing! I connected it and got NUT to recognize it (something I had failed miserably at) and to top it off i was able to set up a script to shut down my server safely if the battery gets too low and even cooler (to me) I set it up so that my server would email me any time it goes into battery mode, connected or shut down. How freaking cool! I hope to tackle Crowdsec next.. wish me luck!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.red

## Created a scanner server to keep old scanners useful
 - [https://www.reddit.com/r/selfhosted/comments/1hj1s1i/created_a_scanner_server_to_keep_old_scanners](https://www.reddit.com/r/selfhosted/comments/1hj1s1i/created_a_scanner_server_to_keep_old_scanners)
 - RSS feed: $source
 - date published: 2024-12-21T04:03:45+00:00

<!-- SC_OFF --><div class="md"><p>I have a SnapScan S1500 that I love but the driver support is slowly dying if not dead. However, it is supported by <a href="https://linux.die.net/man/1/scanadf">scanadf</a> in linux. To keep the scanner chugging I wrote up a basic server that can be deployed to a raspberry pi that gives a simple user interface to set scanning parameters and scan to the pi, a network share, etc. Also includes ocr support via <a href="https://github.com/ocrmypdf/OCRmyPDF">ocrmypdf</a> so text is searchable on scanned documents. Links below and comments, contributions, critiques, feature requests, etc welcome! </p> <p>Note that issues are already opened to add authentication and remove requirement to run as root in github. Very early stages for this project but hope to make it one of my contributions to the open source community.</p> <p><a href="https://github.com/nuvious/scanpi">ScanPi Github</a></p> <p><a href="https://www.youtube.com/watch?v=9Ftn02hEa44">Demo Video<

## Ikea Home built server rack
 - [https://www.reddit.com/r/selfhosted/comments/1hj0k8g/ikea_home_built_server_rack](https://www.reddit.com/r/selfhosted/comments/1hj0k8g/ikea_home_built_server_rack)
 - RSS feed: $source
 - date published: 2024-12-21T02:52:39+00:00

<!-- SC_OFF --><div class="md"><p>Hi Everyone,</p> <p>Wondering if anyone has any ikea based solutions for holding router/nuc based server/pi&#39;s/synology etc. </p> <p>At the moment my hardware is on the floor and badly needs a more appropriate solution.</p> <p>Yes - I know a simple table would be an improvement however I recall ages ago someone had converted a specific ikea furniture into a really cool looking rack. If anyone knows what I&#39;m referring to would love to know what options exist. Right now its a mess with wires everyone, 2 routers, one pi, a synology, a nuc etc...</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Maximum-Warning-4186"> /u/Maximum-Warning-4186 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj0k8g/ikea_home_built_server_rack/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hj0k8g/ikea_home_built_server_rack/">[comments]</a></span>

## Quality Selfhosting Guides
 - [https://www.reddit.com/r/selfhosted/comments/1hizgqm/quality_selfhosting_guides](https://www.reddit.com/r/selfhosted/comments/1hizgqm/quality_selfhosting_guides)
 - RSS feed: $source
 - date published: 2024-12-21T01:50:29+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hizgqm/quality_selfhosting_guides/"> <img src="https://b.thumbs.redditmedia.com/028wtmq-otOYQBfM6EAB9YbzzSpJ--NDD5SAQTh2q3s.jpg" alt="Quality Selfhosting Guides" title="Quality Selfhosting Guides" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/lx78xxebw38e1.png?width=3348&amp;format=png&amp;auto=webp&amp;s=3daabb5a98796f3c4b45e498c5caa92a0a3a4841">https://preview.redd.it/lx78xxebw38e1.png?width=3348&amp;format=png&amp;auto=webp&amp;s=3daabb5a98796f3c4b45e498c5caa92a0a3a4841</a></p> <p>I have added new Content to <a href="https://thinklessvps.com/resource-hub">https://thinklessvps.com/resource-hub</a> which i want to become a trusted place for quality (non AI inflated) resources about selfhosting, i would really appreciated anyone who would also like to contribute on this quest. </p> <p>I think guides about CI/CD and no-downtime deployment are missing what else?</p> <p>FYI <a 

## Port numbering advice
 - [https://www.reddit.com/r/selfhosted/comments/1hiytjw/port_numbering_advice](https://www.reddit.com/r/selfhosted/comments/1hiytjw/port_numbering_advice)
 - RSS feed: $source
 - date published: 2024-12-21T01:14:57+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m just wondering what port numbering scheme you guys use for all the services you host? I know there&#39;s some best practices out there, but to be honest I just use dates that are memorable to me for different services.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Forsaken_Rip208"> /u/Forsaken_Rip208 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hiytjw/port_numbering_advice/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hiytjw/port_numbering_advice/">[comments]</a></span>

