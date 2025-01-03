# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Video conferencing again. Here's what I have tried, suggestions?
 - [https://www.reddit.com/r/selfhosted/comments/1gp5hpc/video_conferencing_again_heres_what_i_have_tried](https://www.reddit.com/r/selfhosted/comments/1gp5hpc/video_conferencing_again_heres_what_i_have_tried)
 - RSS feed: $source
 - date published: 2024-11-11T22:41:29+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a video conferencing application which I can fully self host for meetings.</p> <p>I have tried so far Jitsi and Mirotalk:</p> <ul> <li>Jitsi had way too much going on in the backend for the simple application we needed (it runs a whole XMPP server and all sorts of stuff) and was quite unreliable in our experience.</li> <li>Mirotalk works well with coturn, but the mobile experience is, unfortunately, disaterous. The UI doesn&#39;t fit the display properly, exiting menus... doesn&#39;t, menu options get hidden and full screen is buggy.</li> </ul> <p>Ideally we want something in between the two. Simple like Mirotalk, easy to use (preferrably with a native mobile app) like Jitsi.</p> <p>Any suggestions would be greatly appreciated. I will answer any questions as edits+reply</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DevelopedLogic"> /u/DevelopedLogic </a> <br/> <span><a href="https://www.red

## VPN in a docker container via linuxserver/wireguard
 - [https://www.reddit.com/r/selfhosted/comments/1gp41pc/vpn_in_a_docker_container_via_linuxserverwireguard](https://www.reddit.com/r/selfhosted/comments/1gp41pc/vpn_in_a_docker_container_via_linuxserverwireguard)
 - RSS feed: $source
 - date published: 2024-11-11T21:40:58+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone I have been running a container on my old laptop with like a system wide vpn. Now I want to add another container and I would prefer not to have its traffic go via the VPN server.</p> <p>I found this image <a href="https://github.com/linuxserver/docker-wireguard">linuxserver/wireguard</a>, and seems like I managed to get it working, I wanted to ask if anyone can notice anything I did wrong or if there is something I need to worry about.</p> <p>I started the wireguard container with this command</p> <pre><code>docker run -v &#39;/home/omistaja/Documents/wireguard configs&#39;:/config/wg_confs/ -d --cap-add=NET_ADMIN --sysctl=&quot;net.ipv4.conf.all.src_valid_mark=1&quot; -p 51920:51820/udp --name=wireguard linuxserver/wireguard </code></pre> <p>then confirmed it works via running a test container which just gets the country from ip using ipv4.am.i.mullvad.net</p> <pre><code>omistaja@Hoppuli:~/Desktop/python$ docker run test Finland omista

## Ngrok problem
 - [https://www.reddit.com/r/selfhosted/comments/1gp3o4q/ngrok_problem](https://www.reddit.com/r/selfhosted/comments/1gp3o4q/ngrok_problem)
 - RSS feed: $source
 - date published: 2024-11-11T21:25:35+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gp3o4q/ngrok_problem/"> <img src="https://a.thumbs.redditmedia.com/_Tq7YAJ0vchIBqanw1hzucvYxxNiQrXJTj5Y3DIkdl0.jpg" alt="Ngrok problem" title="Ngrok problem" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/idxcghdqac0e1.png?width=1918&amp;format=png&amp;auto=webp&amp;s=66d95b38baeccd9d384499c6ff029330192b3588">https://preview.redd.it/idxcghdqac0e1.png?width=1918&amp;format=png&amp;auto=webp&amp;s=66d95b38baeccd9d384499c6ff029330192b3588</a></p> <p>Hello, I am trying to use ngrok for my fastapi endpoint, and the endpoint is working fine. However I just find it weird that the ngrok links are connected but not working. I tried it on desktop and laptop, different browsers to no avail. Then I tried opening it on my phone through messenger and somehow I was able to access it, I am just so confused as to why is it working and I dont know how to make it work as an endpoint in the desk

## What criteria do you use to evaluate open-source self-hosted projects? Thoughts on a standardized rating approach?
 - [https://www.reddit.com/r/selfhosted/comments/1gp3dbz/what_criteria_do_you_use_to_evaluate_opensource](https://www.reddit.com/r/selfhosted/comments/1gp3dbz/what_criteria_do_you_use_to_evaluate_opensource)
 - RSS feed: $source
 - date published: 2024-11-11T21:13:21+00:00

<!-- SC_OFF --><div class="md"><p>Hey <a href="/r/selfhosted">r/selfhosted</a> community,</p> <p>I’m curious to know what criteria you all use when evaluating open-source projects for self-hosting. With so many options out there, each offering different pros and cons, it’d be helpful to have a more standardized way to assess and compare them.</p> <p>Beyond basics like security and community activity, what other aspects matter most to you? </p> <p>For example:</p> <ul> <li><strong>Documentation quality</strong>: Does it include clear setup guides and troubleshooting?</li> <li><strong>Resource usage</strong>: How heavy or light is it on hardware?</li> <li><strong>Update frequency</strong>: Is it actively maintained and regularly improved?</li> <li><strong>Modularity</strong>: Does it support easy customization and integrations?</li> </ul> <p>I’m also wondering if any of you see value in a shared rating system or comparison framework for evaluating these projects—something that could gi

## ByteStash v1.4.0 - Self Hosted Code Snippet Manager
 - [https://www.reddit.com/r/selfhosted/comments/1gp2x1y/bytestash_v140_self_hosted_code_snippet_manager](https://www.reddit.com/r/selfhosted/comments/1gp2x1y/bytestash_v140_self_hosted_code_snippet_manager)
 - RSS feed: $source
 - date published: 2024-11-11T20:54:59+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gp2x1y/bytestash_v140_self_hosted_code_snippet_manager/"> <img src="https://external-preview.redd.it/jNCHqUEx3Sl1nyeAdqsGGwzipgD16GJ_oDKxiJ4ck7c.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=449cd2b1b058e610f50fa9926f50c25044f7610f" alt="ByteStash v1.4.0 - Self Hosted Code Snippet Manager" title="ByteStash v1.4.0 - Self Hosted Code Snippet Manager" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi!</p> <p><a href="https://github.com/jordan-dalby/ByteStash">ByteStash </a>version 1.4.0 was just released. This is a hobby project of mine that I&#39;ve been working on for a couple of months now, it&#39;s a code snippet manager.</p> <p><a href="https://www.reddit.com/r/selfhosted/comments/1gb1ail/selfhosted_code_snippet_manager/">Original Reddit Post</a></p> <p>Changes (v1.2.0 -&gt; v1.4.0):</p> <ul> <li>Basic authentication <ul> <li>Specify <code>AUTH_USERNAME=username</code>, <code>AUTH_PASSWORD=password</cod

## Authorizing git operations [clone,pull,push] via web browser
 - [https://www.reddit.com/r/selfhosted/comments/1gp2tvy/authorizing_git_operations_clonepullpush_via_web](https://www.reddit.com/r/selfhosted/comments/1gp2tvy/authorizing_git_operations_clonepullpush_via_web)
 - RSS feed: $source
 - date published: 2024-11-11T20:51:19+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gp2tvy/authorizing_git_operations_clonepullpush_via_web/"> <img src="https://b.thumbs.redditmedia.com/TDZbsnjeU-Jqwe9guS5yQ9mx-3C-3x_y25sHAfA39Ok.jpg" alt="Authorizing git operations [clone,pull,push] via web browser " title="Authorizing git operations [clone,pull,push] via web browser " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello everyone!</p> <p>Ive been using gitea for over 2 years now and im loving it. Lately i have a &quot;unique&quot; problem with it and i want some input.</p> <p>When i first installed gitea , for cloning , pulling etc repositories on my local macine i had to input in the cli my username follwed by the password. Then , one day i was prompted by the following screen , went to authorise and ...viola ! it was cloning . i dont know what did i do diferently what time but since it wroks like this in my windows macine.</p> <p>I went to clone a repo at my linux laptop but it prompted 

## Wishlist item - Kapowarr, but for magazines
 - [https://www.reddit.com/r/selfhosted/comments/1gp2tkl/wishlist_item_kapowarr_but_for_magazines](https://www.reddit.com/r/selfhosted/comments/1gp2tkl/wishlist_item_kapowarr_but_for_magazines)
 - RSS feed: $source
 - date published: 2024-11-11T20:50:58+00:00

<!-- SC_OFF --><div class="md"><p>I recently revisited <a href="https://noted.lol/kapowarr/">Kapowarr</a> which seems to have come a long way since I first looked at it last year and it reminded me that I wished there was something similar for magazines, as my wife reads all the fashion mags (vogue etc)</p> <p>The reason I mentioned Kapowarr rather than one of the other *arrs is that it uses a single and relatively stable comic repo for downloading rather than usenet etc (although there&#39;s talk of eventually including that), and so I was wondering if similar can be done with a single, dependable magazine repo.</p> <p>I totally lack any of skills required to do something like this, but I wish it existed. Have there been any developments on that front I&#39;m unaware of?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CrispyBegs"> /u/CrispyBegs </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gp2tkl/wishlist_item_kapowarr

## Which dedicated hosting provider do you prefer to use, and what do you like most about it?
 - [https://www.reddit.com/r/selfhosted/comments/1gp2sjg/which_dedicated_hosting_provider_do_you_prefer_to](https://www.reddit.com/r/selfhosted/comments/1gp2sjg/which_dedicated_hosting_provider_do_you_prefer_to)
 - RSS feed: $source
 - date published: 2024-11-11T20:49:48+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Shaerif"> /u/Shaerif </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gp2sjg/which_dedicated_hosting_provider_do_you_prefer_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gp2sjg/which_dedicated_hosting_provider_do_you_prefer_to/">[comments]</a></span>

## Network UPS Tools in a Proxmox LXC
 - [https://www.reddit.com/r/selfhosted/comments/1gp2rau/network_ups_tools_in_a_proxmox_lxc](https://www.reddit.com/r/selfhosted/comments/1gp2rau/network_ups_tools_in_a_proxmox_lxc)
 - RSS feed: $source
 - date published: 2024-11-11T20:48:24+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I have NUT running in a Proxmox LXC, passing through the USB where the UPS (APC 900) is connected to. The setup has a primary and secondary (Master and Slave).</p> <p>The LXC runs the server, a client is on my NAS. My NAS is configured to shutdown after 15 minutes and does this perfectly.</p> <p>The proxmox server, should only shutdown after about 45 min (still testing with the amount of minutes) but leave the UPS alone (don&#39;t shutoff the UPS). I&#39;ve managed shutting down the host from the LXC by using the following SSH command in the Cli:</p> <pre><code>ssh -i /root/.ssh/20241109_NUT -p 9430 -o StrictHostKeyChecking=no root@192.168.x.xx -t &#39;/sbin/shutdown -h +0&#39; </code></pre> <p>Also, to shut-up the beeper, I used successfully the following command through the Cli:</p> <pre><code>upscmd -u upsuser -p &lt;password&gt; apc900@192.168.x.xx beeper.mute </code></pre> <p>I&#39;ve put these commands into the upssched-cmd file,

## Help with internal IP:Port>Hostname configuration
 - [https://www.reddit.com/r/selfhosted/comments/1gp2gi2/help_with_internal_ipporthostname_configuration](https://www.reddit.com/r/selfhosted/comments/1gp2gi2/help_with_internal_ipporthostname_configuration)
 - RSS feed: $source
 - date published: 2024-11-11T20:36:19+00:00

<!-- SC_OFF --><div class="md"><p>Hey all, hopefully some network boffin can help a newbie out here. Honestly totally out of my depth.</p> <p>I&#39;m trying to setup all my internal services to convert their IP:Port or Hostname.Home.Arpa:Port to just Hosthame.Home.Arpa, or even just Hostname. So far, Technitium is working wonderfully with DNS A registries for Hostname.Home.Arpa:Port resolution, but for the life of me I can&#39;t figure out NGINX or DNS</p> <p>I&#39;ve got a &quot;home.arpa&quot; file in /etc/nginx/sites-available/ symlinked over to /sites-enabled/, with the following in it so far:</p> <pre><code>server { listen 80; server_name nginx.home.arpa; location / { proxy_set_header X-Forwarded-Host $host; proxy_set_header X-Forwarded-Server $host; proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for; proxy_pass http://192.168.0.XXX/; } } </code></pre> <p>So in theory I should just copy that block and edit it with the correct Hostname and IP:Port for each and every serv

## Which OS/Service do I need to run for the most long term stable solution?
 - [https://www.reddit.com/r/selfhosted/comments/1gp24jw/which_osservice_do_i_need_to_run_for_the_most](https://www.reddit.com/r/selfhosted/comments/1gp24jw/which_osservice_do_i_need_to_run_for_the_most)
 - RSS feed: $source
 - date published: 2024-11-11T20:23:24+00:00

<!-- SC_OFF --><div class="md"><p>I have bought an Intel NUC with 2TB and 16GB RAM. I want to set this up for use as my self hosted server. It needs to do the following things:</p> <ul> <li>Bitcoin Node</li> <li>Lightning Node</li> <li>Dropbox alternative</li> <li>Apple Music alternative</li> <li>Netflix alternative</li> <li>Adblocker for my network</li> <li>VPN</li> <li>Home Assistant</li> <li>BTCPay Server</li> <li>CoinJoin server</li> </ul> <p>That is the current plan. But in the future probably more stuff will join. All in all, it will be used for a lot of stuff. I have also got a NAS for my backups, so that is not something I have to do with this server. </p> <p>But what OS do I need to use for this?</p> <ul> <li>Start9?</li> <li>Umbrel?</li> <li>CasaOS?</li> </ul> <p>It seems like Umbrel or Start9 is the most logical thing when I search on Google, but apparently for the long run and / or security wise it\s not the best to use Umbrel for example. But I am not sure what the best 

## AutoKitteh - Self-hosted Durable Automation Platform for Developers
 - [https://www.reddit.com/r/selfhosted/comments/1gp1ji4/autokitteh_selfhosted_durable_automation_platform](https://www.reddit.com/r/selfhosted/comments/1gp1ji4/autokitteh_selfhosted_durable_automation_platform)
 - RSS feed: $source
 - date published: 2024-11-11T20:00:26+00:00

<!-- SC_OFF --><div class="md"><p>Links: <a href="https://github.com/autokitteh/autokitteh">GitHub</a>, <a href="https://github.com/autokitteh/kittehub">examples</a></p> <p><a href="http://www.autokitteh.com/">AutoKitteh</a> is an automation platform specifically designed for Python developers. </p> <p>It&#39;s like &quot;<strong>Zapier for developers</strong>&quot; enabling you to build limitless automations with just a few lines of code, add your own applications and execute reliable long-running workflows (AKA durable worklows).</p> <p><strong>Target audience</strong>: Professionals and citizen developers familiar with Python that build personal projects or enterprise solutions. It is designed for:</p> <ul> <li>ChatOps, DevOps, IT and MLOps automation</li> <li>Personal and office workflows</li> </ul> <p>Integrations: Gmail, Sheets, Calendar, Twilio, OpenAI, Jira, Confluence, Github, Slack and many more</p> <p><strong>Comparison to other tools</strong></p> <p>AutoKitteh is an integ

## I'm thinking of self web-hosting. Any advice?
 - [https://www.reddit.com/r/selfhosted/comments/1gp1cvv/im_thinking_of_self_webhosting_any_advice](https://www.reddit.com/r/selfhosted/comments/1gp1cvv/im_thinking_of_self_webhosting_any_advice)
 - RSS feed: $source
 - date published: 2024-11-11T19:52:55+00:00

<!-- SC_OFF --><div class="md"><p>I hate subsciptions. So I allways chose free web-hosting providers. Their limitations have caught up to me and I&#39;m now thinking of self-hosting. Any advice?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Successful_Raise121"> /u/Successful_Raise121 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gp1cvv/im_thinking_of_self_webhosting_any_advice/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gp1cvv/im_thinking_of_self_webhosting_any_advice/">[comments]</a></span>

## I finished parts 2 and 3 of my blog series on protecting your self hosted services with Fedora CoreOS + reverse proxy (nginx/swag)
 - [https://www.reddit.com/r/selfhosted/comments/1gp11zv/i_finished_parts_2_and_3_of_my_blog_series_on](https://www.reddit.com/r/selfhosted/comments/1gp11zv/i_finished_parts_2_and_3_of_my_blog_series_on)
 - RSS feed: $source
 - date published: 2024-11-11T19:40:34+00:00

<!-- SC_OFF --><div class="md"><h1>I&#39;m writing a series of articles on protecting homelab services with a reverse proxy (swag) hosted on Fedora CoreOS.</h1> <p>I wrote <a href="https://bytemycache.com/posts/protect-your-services-with-an-immutable-reverse-proxy-fail2ban-and-cloudflare-part-1/">Part 1</a> a few months ago, and I&#39;ve just recently finished <a href="https://bytemycache.com/posts/protect-your-services-with-an-immutable-reverse-proxy-fail2ban-and-cloudflare-part-2/">Part 2</a> and <a href="https://bytemycache.com/posts/protect-your-services-with-an-immutable-reverse-proxy-fail2ban-and-cloudflare-part-3/">Part 3</a></p> <p>Hopefully folks find this helpful, or we can inspire some useful discussion! I would love some &quot;peer review&quot; if anyone wants to have a discussion on the concepts and techniques presented in the articles and if anyone has any suggestions or feedback!</p> <p>Some discussion was had on the previous entry <a href="https://bytemycache.com/post

## Need help finding a m.2 compatible drive
 - [https://www.reddit.com/r/selfhosted/comments/1gp11vs/need_help_finding_a_m2_compatible_drive](https://www.reddit.com/r/selfhosted/comments/1gp11vs/need_help_finding_a_m2_compatible_drive)
 - RSS feed: $source
 - date published: 2024-11-11T19:40:25+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gp11vs/need_help_finding_a_m2_compatible_drive/"> <img src="https://b.thumbs.redditmedia.com/6o0dPYVysb-Bp6f6r9uLQhEUxiChLurKLqvhMSsgN7E.jpg" alt="Need help finding a m.2 compatible drive" title="Need help finding a m.2 compatible drive" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi,</p> <p>Bought a Lenovo V520 (10NK0023UK). I thought I wanted a 2230 like the one in the picture but the motherboard interface is different (second picture). Can you help me understand what do I need to buy?</p> <p>Thank you.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Top_Run_4086"> /u/Top_Run_4086 </a> <br/> <span><a href="https://www.reddit.com/gallery/1gp11vs">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gp11vs/need_help_finding_a_m2_compatible_drive/">[comments]</a></span> </td></tr></table>

## Access my private stuff via WireGuard while connected to a VPN service (NordVPN)
 - [https://www.reddit.com/r/selfhosted/comments/1gp0xwa/access_my_private_stuff_via_wireguard_while](https://www.reddit.com/r/selfhosted/comments/1gp0xwa/access_my_private_stuff_via_wireguard_while)
 - RSS feed: $source
 - date published: 2024-11-11T19:35:45+00:00

<!-- SC_OFF --><div class="md"><pre><code>I am a longtime NordVPN customer, along the years it saved me in getting safely connected to open WiFi networks in hotels, conferences, etc. Now I would like to access my home-hosted services, mainly Nextcloud and a few more things. After having read threads over threads, it seems that WireGuard is the way to go. The only problem: on Android you can only have one VPN enabled at any given time (well, it&#39;s not entirely true; with certain Android distros and using separate user profiles, but it&#39;s out of scope here). That would mean that I am either connected to my WireGuard server, with a WireGuard client, or to NordVPN (which AFAIK uses also WireGuard nowadays). What I would like is to have my droid running with NordVPN, *and* having also a WireGuard connected to my private DMZ to access my stuff. I&#39;ve read something about a similar setup in this subreddit, but I didn&#39;t catch exactly if it can be achieved, and how. Care to give 

## Docker networking when one container uses a VPN
 - [https://www.reddit.com/r/selfhosted/comments/1gp0wd6/docker_networking_when_one_container_uses_a_vpn](https://www.reddit.com/r/selfhosted/comments/1gp0wd6/docker_networking_when_one_container_uses_a_vpn)
 - RSS feed: $source
 - date published: 2024-11-11T19:34:00+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been trying to troubleshoot getting my qbittorrent container properly set up with cross-seed and qbit_manage, but I want to start from scratch to get it right.</p> <h3>The current setup</h3> <p>My compose.yml runs:</p> <ol> <li>qBittorrent, using <a href="https://hotio.dev/containers/qbittorrent/">hotio&#39;s image</a> to funnel those connections to my VPN provider via wireguard</li> <li>cross-seed</li> <li>qbitmanage</li> </ol> <p>stripped down yml:</p> <pre><code>services: qbittorrent: image: ghcr.io/hotio/qbittorrent:release-5.0.1 ports: - &quot;8080:8080&quot; environment: - VPN_ENABLED=true - VPN_LAN_NETWORK=192.168.68.0/24 - VPN_CONF=wg0 - PRIVOXY_ENABLED=false cap_add: - NET_ADMIN sysctls: - net.ipv4.conf.all.src_valid_mark=1 - net.ipv6.conf.all.disable_ipv6=1 qbitmanage: image: ghcr.io/stuffanthings/qbit_manage:develop depends_on: - qbittorrent cross-seed: image: crossseed/cross-seed ports: - &quot;2468:2468&quot; depends_on: - qbitt

## Gaming VM Significantly Underperforming
 - [https://www.reddit.com/r/selfhosted/comments/1gp0kra/gaming_vm_significantly_underperforming](https://www.reddit.com/r/selfhosted/comments/1gp0kra/gaming_vm_significantly_underperforming)
 - RSS feed: $source
 - date published: 2024-11-11T19:20:54+00:00

<!-- SC_OFF --><div class="md"><p>I know that the first round of advice is going to be &quot;don&#39;t use VMs for gaming,&quot; but I&#39;ve got a real use case for it and in an ideal world I&#39;d like it to work. This isn&#39;t a post on the merits of using a VM for gaming, but a question to see if there&#39;s anything I&#39;m overlooking.</p> <p>This is my setup:<br/> Dell T630 PowerEdge<br/> Xeon 1650 v4 (3.5ghz) [Note, previously I had a 2687w v4 but switched to see if it was a CPU limitation]<br/> 128gb 2400 RAM<br/> AMD 7900xtx<br/> 16tb Hardware RAID 10 w/ 730p PERC controller (8x4tb sas drives)<br/> 1tb SSD via PCI Adapter (moved games to here in case there was an issue of r / w speeds)</p> <p>I&#39;ve tried both an Ubuntu and a Windows desktop. It was a pain in the ass to get PCI passthrough for the GPU working (due to some oddities with the PowerEdge) but managed to get it working. I&#39;ve done two different methods of passthrough, both blacklisting and having vfio bound

## Is it acceptable to use your main gaming PC as a server?
 - [https://www.reddit.com/r/selfhosted/comments/1gp0bqx/is_it_acceptable_to_use_your_main_gaming_pc_as_a](https://www.reddit.com/r/selfhosted/comments/1gp0bqx/is_it_acceptable_to_use_your_main_gaming_pc_as_a)
 - RSS feed: $source
 - date published: 2024-11-11T19:10:53+00:00

<!-- SC_OFF --><div class="md"><p>Dont lynch me but currently i dont have the money to build another system. So just to learn and try things out i setup Jellyfin and a few other things on my PC as a temporary test, but honestly its working great and i havent experienced any problems so i was thinking of just letting it be this way for the forseeable future. My specs are: 7700XT, 7600X, 32GB DDR5 RAM. I havent really experienced performance loss even while gaming and streaming 4k media from it(only me and 3 others have acess) so are there any other things that i should pay attention to? I assume a benefit of a dedicated server would be power efficiency, which my gaming pc obviously isnt build for, would that alone make it worth it to build a seperate system? I also dont have any subscriptions im replacing besides onedrive wich is just 20€ a year so i cant really justify it that way lol i already wasnt paying for netflix or other clouds</p> </div><!-- SC_ON --> &#32; submitted by &#32;

## Proxmox VE: The improved SSH with hidden regressions (updated)
 - [https://www.reddit.com/r/selfhosted/comments/1gozxgj/proxmox_ve_the_improved_ssh_with_hidden](https://www.reddit.com/r/selfhosted/comments/1gozxgj/proxmox_ve_the_improved_ssh_with_hidden)
 - RSS feed: $source
 - date published: 2024-11-11T18:54:56+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/esiy0676"> /u/esiy0676 </a> <br/> <span><a href="https://www.reddit.com/r/Proxmox/comments/1go7y5d/the_improved_ssh_with_hidden_regressions">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gozxgj/proxmox_ve_the_improved_ssh_with_hidden/">[comments]</a></span>

## Self-hosted SCIM servers?
 - [https://www.reddit.com/r/selfhosted/comments/1goyumz/selfhosted_scim_servers](https://www.reddit.com/r/selfhosted/comments/1goyumz/selfhosted_scim_servers)
 - RSS feed: $source
 - date published: 2024-11-11T18:12:04+00:00

<!-- SC_OFF --><div class="md"><p>As a SaaS developer, I&#39;m trying to offer enterprise SSO + SCIM for businesses who are asking for it.</p> <p>I know WorkOS does it extremely smoothly, however I simply cannot afford $250 per month per client for this feature. WorkOS makes sense if your client pays you $10k per month, it doesn&#39;t for $500 per month.</p> <p>What other options are there? For SSO, I can do self-hosted ZITADEL, but it doesn&#39;t support SCIM yet.</p> <p>Just recently, I&#39;ve found <a href="https://github.com/boxyhq/jackson">https://github.com/boxyhq/jackson</a>. Would this work?</p> <p>Also, how do you combine multiple systems? For example SAML jackson only offers enterprise SSO products, so you still need to have something like ZITADEL for the B2C use case, like password login or login with Google.</p> <p>I mean at the end of the day, you want the a single session handling code in your app, no matter if your user is coming from ZITADEL or SAML jackson. How do yo

## Oracle Cloud is actually free?
 - [https://www.reddit.com/r/selfhosted/comments/1gox9in/oracle_cloud_is_actually_free](https://www.reddit.com/r/selfhosted/comments/1gox9in/oracle_cloud_is_actually_free)
 - RSS feed: $source
 - date published: 2024-11-11T17:09:02+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gox9in/oracle_cloud_is_actually_free/"> <img src="https://b.thumbs.redditmedia.com/X_WS1vB1kuF1C8oEaxlZIMBk3IpeqQ7Y5pp6yidO0-k.jpg" alt="Oracle Cloud is actually free?" title="Oracle Cloud is actually free?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/zky8ib0b1b0e1.png?width=1239&amp;format=png&amp;auto=webp&amp;s=0f5eca8711c5cd3ec64a521ef8999bcaced92354">https://preview.redd.it/zky8ib0b1b0e1.png?width=1239&amp;format=png&amp;auto=webp&amp;s=0f5eca8711c5cd3ec64a521ef8999bcaced92354</a></p> <p>I&#39;m making a Always Free instance, but i see this value in the right. Am i going to be charged this value?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/The_Mullet_boy"> /u/The_Mullet_boy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gox9in/oracle_cloud_is_actually_free/">[link]</a></span> &#32; <span><a href="http

## Has anyone deployed Nextcloud to a Kubernetes cluster?
 - [https://www.reddit.com/r/selfhosted/comments/1gox7zl/has_anyone_deployed_nextcloud_to_a_kubernetes](https://www.reddit.com/r/selfhosted/comments/1gox7zl/has_anyone_deployed_nextcloud_to_a_kubernetes)
 - RSS feed: $source
 - date published: 2024-11-11T17:07:23+00:00

<!-- SC_OFF --><div class="md"><p>I have a Nextcloud container deployed into my Kubernetes cluster, but before I start moving anything to it, I want to make sure everything is properly backed up and recoverable. I have a NAS with two disks as my primary storage location and want to use the second disk as recovery.</p> <p>What was your process to backup your PV data, keys, database, etc? What would that recovery process look like?</p> <p>Right now I think either rsync or velero may work, but I’m still trying to think through how that recovery process would go.</p> <p>Thanks for any insight!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/juicyP3inchfloppy"> /u/juicyP3inchfloppy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gox7zl/has_anyone_deployed_nextcloud_to_a_kubernetes/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gox7zl/has_anyone_deployed_nextcloud_to_a_kubernetes/">[comme

## Launched my side project on a self-hosted M1 Mac Mini - Here's what happened when hundreds of users showed up
 - [https://www.reddit.com/r/selfhosted/comments/1gow9jb/launched_my_side_project_on_a_selfhosted_m1_mac](https://www.reddit.com/r/selfhosted/comments/1gow9jb/launched_my_side_project_on_a_selfhosted_m1_mac)
 - RSS feed: $source
 - date published: 2024-11-11T16:29:32+00:00

<!-- SC_OFF --><div class="md"><p>Everyone talks about how easy it is to spin up cloud instances for new projects, but I wanted to try something different. I bought an M1 Mac Mini on Facebook Marketplace for $250, set it up as a home server, and launched my project last week.</p> <p>Figured you all might be interested in some real-world performance data:</p> <ul> <li>First 48 hours: ~3k sessions from users across US, Europe, Australia, and even a user in Cambodia added some listings</li> <li>CPU stayed under 10% the whole time (M1 chip is seriously impressive)</li> <li>Memory usage remained stable</li> <li>Monthly costs: about $2 in electricity</li> </ul> <p>Nothing fancy in the setup:</p> <ul> <li>M1 Mac Mini</li> <li>Everything runs in Docker containers</li> <li>nginx reverse proxy X CloudFlare dynamic DNS</li> <li>Regular backups to external drives</li> </ul> <p>Yeah, there are trade-offs (home internet isn&#39;t AWS global infrastructure), but for a bootstrapped project that need

## Current best Airtable alternative?
 - [https://www.reddit.com/r/selfhosted/comments/1gow2gp/current_best_airtable_alternative](https://www.reddit.com/r/selfhosted/comments/1gow2gp/current_best_airtable_alternative)
 - RSS feed: $source
 - date published: 2024-11-11T16:21:23+00:00

<!-- SC_OFF --><div class="md"><p>Hey!<br/> I looked at NoCodb and Baserow. I can&#39;t decide which is the best in terms of features.<br/> Which one do you think has the most longterm potential?<br/> Also a big problem is that I don&#39;t find the basic &quot;Expand the table&quot; when pasting lot of rows from Excel.<br/> Maybe there are better options to replace Airtable?<br/> Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/WillWillHey"> /u/WillWillHey </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gow2gp/current_best_airtable_alternative/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gow2gp/current_best_airtable_alternative/">[comments]</a></span>

## Nginx for non-docker-ized servers
 - [https://www.reddit.com/r/selfhosted/comments/1govm56/nginx_for_nondockerized_servers](https://www.reddit.com/r/selfhosted/comments/1govm56/nginx_for_nondockerized_servers)
 - RSS feed: $source
 - date published: 2024-11-11T16:02:29+00:00

<!-- SC_OFF --><div class="md"><p>I have successfully confivered the SSL certificate and gotten Nginx successfully linked to other instances within the same Docker instance. I am using PiHole as my DNS, so internal controller. However, when I try to set up this PiHole or even my Unifi controller, Proxmox, or other non-docker-ized servers, it errors out. </p> <p>What I am missing?</p> <p>I have read some articles that say to download the certificate from Nginx that you&#39;ve created and then upload to the server. However, some of them, like PiHole won&#39;t even open up. Is there a guide I can use? </p> <p>Thanks in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Wasted-Friendship"> /u/Wasted-Friendship </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1govm56/nginx_for_nondockerized_servers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1govm56/nginx_for_nondockerized_servers/

## How should I think about the capabilities of Remote Desktop access clients when comparing browser-based clients, open source clients, and proprietary clients?
 - [https://www.reddit.com/r/selfhosted/comments/1govctl/how_should_i_think_about_the_capabilities_of](https://www.reddit.com/r/selfhosted/comments/1govctl/how_should_i_think_about_the_capabilities_of)
 - RSS feed: $source
 - date published: 2024-11-11T15:51:51+00:00

<!-- SC_OFF --><div class="md"><p>I’m forming a mental model of Remote Desktop access client options. As I understand it, the three main categories are browser-based clients, open source clients, and proprietary clients.</p> <p>In trying many out, my headspace is as follows:</p> <ul> <li>Proprietary clients are the most capable by far and can achieve an experience that rivals a local machine.</li> <li>Open source clients work, but all have tradeoffs that must be considered. None are as well built out as the leading proprietary clients.</li> <li> Browser-based clients can be thought of as similar to the open source client category in terms of capabilities, but additional constraints are now imposed by the browser type (i.e. Chromium browsers may have features that non-Chromium do not)</li> </ul> <p>Is that a fair mental model? What assumptions might I have that are incorrect?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nonredditaccount"> /u/n

## Rustpad.. OSS rust based fast live document editing tool(https://github.com/ekzhang/rustpad)
 - [https://www.reddit.com/r/selfhosted/comments/1govavl/rustpad_oss_rust_based_fast_live_document_editing](https://www.reddit.com/r/selfhosted/comments/1govavl/rustpad_oss_rust_based_fast_live_document_editing)
 - RSS feed: $source
 - date published: 2024-11-11T15:49:35+00:00

<!-- SC_OFF --><div class="md"><p>Rust Pad.. seems super useful..</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cattykatrina"> /u/cattykatrina </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1govavl/rustpad_oss_rust_based_fast_live_document_editing/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1govavl/rustpad_oss_rust_based_fast_live_document_editing/">[comments]</a></span>

## Using a ROG phone as server thanks to the laptop charging feature
 - [https://www.reddit.com/r/selfhosted/comments/1gouzl9/using_a_rog_phone_as_server_thanks_to_the_laptop](https://www.reddit.com/r/selfhosted/comments/1gouzl9/using_a_rog_phone_as_server_thanks_to_the_laptop)
 - RSS feed: $source
 - date published: 2024-11-11T15:36:08+00:00

<!-- SC_OFF --><div class="md"><p>I wonder if someone did that since they can take energy straight from the source instead of passing via the battery (like laptops). Smartphone without this feature turned into server means extra wear on battery or a battery tweak. If you did it, what do you host there? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/F041"> /u/F041 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gouzl9/using_a_rog_phone_as_server_thanks_to_the_laptop/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gouzl9/using_a_rog_phone_as_server_thanks_to_the_laptop/">[comments]</a></span>

## What raspberry pi as dns server
 - [https://www.reddit.com/r/selfhosted/comments/1gouf8p/what_raspberry_pi_as_dns_server](https://www.reddit.com/r/selfhosted/comments/1gouf8p/what_raspberry_pi_as_dns_server)
 - RSS feed: $source
 - date published: 2024-11-11T15:12:30+00:00

<!-- SC_OFF --><div class="md"><p>I would like to have a self-hosted dns server (probably pi-hole + ubound) but not running on my actual server. I would like to have dedicated hardware for it. I thought about a raspberry-pi but I don&#39;t know which one, 4 or 5? 2gb or more? I just want something with low power cumsuption and capable to last several year.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/webflo-dev"> /u/webflo-dev </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gouf8p/what_raspberry_pi_as_dns_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gouf8p/what_raspberry_pi_as_dns_server/">[comments]</a></span>

## Stepping into selfhosted?
 - [https://www.reddit.com/r/selfhosted/comments/1gou187/stepping_into_selfhosted](https://www.reddit.com/r/selfhosted/comments/1gou187/stepping_into_selfhosted)
 - RSS feed: $source
 - date published: 2024-11-11T14:55:41+00:00

<!-- SC_OFF --><div class="md"><p>So I got my hands on two mini PCs with the following specs. </p> <ol> <li>Lenovo M720q - i5-9500T with 32GB ram. </li> <li>HP Pro desk G4 500 - i5-9500T with 16GB ram. </li> </ol> <p>I was thinking of doing something with these while they are just laying around about the house. I planned to build a NAS with one of them to also double as a media player, but being a mini PC, there is no place to connect the 16TB HDDs. </p> <p>I looked a bit into doing some Home Assistant stuff, but I feel like the PC is overkill. So I would like the community&#39;s help with pointing me into the right direction. Maybe I can just use one PC for multiple stuff, like home assistant and other things, but I am not sure what other things are and how I can go about it. </p> <p>There&#39;s that, and thanks all.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/qwertyuiop1158"> /u/qwertyuiop1158 </a> <br/> <span><a href="https://www.reddit.c

## Advice needed: publicly accessible self hosted data solutions?
 - [https://www.reddit.com/r/selfhosted/comments/1goty4d/advice_needed_publicly_accessible_self_hosted](https://www.reddit.com/r/selfhosted/comments/1goty4d/advice_needed_publicly_accessible_self_hosted)
 - RSS feed: $source
 - date published: 2024-11-11T14:51:53+00:00

<!-- SC_OFF --><div class="md"><p>Hello all! What I&#39;d like to do is pretty simple: I have a dedicated computer acting as a file/document storage server. I&#39;d like to make the files/data it holds accessible to the public. Is there an open-source solution that will let me self host a data server and make it read-only/download-only available to groups of people <strong>without</strong> each individual needing login creds or similar?</p> <p>Thanks in advance; all productive/constructive input is welcome!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PortCityBlitz"> /u/PortCityBlitz </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1goty4d/advice_needed_publicly_accessible_self_hosted/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1goty4d/advice_needed_publicly_accessible_self_hosted/">[comments]</a></span>

## Dawarich October 2024 Update
 - [https://www.reddit.com/r/selfhosted/comments/1gotstt/dawarich_october_2024_update](https://www.reddit.com/r/selfhosted/comments/1gotstt/dawarich_october_2024_update)
 - RSS feed: $source
 - date published: 2024-11-11T14:45:15+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Freika"> /u/Freika </a> <br/> <span><a href="https://dawarich.app/blog/october-2024-monthly-update">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gotstt/dawarich_october_2024_update/">[comments]</a></span>

## Things to do with an old laptop
 - [https://www.reddit.com/r/selfhosted/comments/1gosooo/things_to_do_with_an_old_laptop](https://www.reddit.com/r/selfhosted/comments/1gosooo/things_to_do_with_an_old_laptop)
 - RSS feed: $source
 - date published: 2024-11-11T13:53:40+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to rack my brain on things I could selfhost on an old laptop i have. It runs arch at the moment, but everything useful (jellyfin, jackett, ollama, etc) is already hosted on my main PC. I honestly can&#39;t think of anything it could be useful for (other than batocera, but even then it struggles on later games) but it feels crappy to let it go to waste. Help me out please :3 Specs AMD A6-6310 with AMD Radeon R4 Graphics (4) @ 1.80 GHz 5GB Ram 1TB HDD</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/chamwichwastaken"> /u/chamwichwastaken </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gosooo/things_to_do_with_an_old_laptop/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gosooo/things_to_do_with_an_old_laptop/">[comments]</a></span>

## Running My First Containers!
 - [https://www.reddit.com/r/selfhosted/comments/1gosk4m/running_my_first_containers](https://www.reddit.com/r/selfhosted/comments/1gosk4m/running_my_first_containers)
 - RSS feed: $source
 - date published: 2024-11-11T13:47:29+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! 😊</p> <p>I&#39;m a homelab beginner and just recently got my first Docker containers up and running. It’s been a bit challenging, but I’m learning a lot and finding it really exciting! Here’s a list of the containers I currently have running:</p> <ul> <li><strong>adguard</strong> – For DNS and ad-blocking</li> <li><strong>jellyfin</strong> – To stream my media content</li> <li><strong>npm (Nginx Proxy Manager)</strong> – To manage my services through a web interface</li> <li><strong>stirlingpdf</strong> – A simple PDF server</li> <li><strong>portainer</strong> – To manage my containers</li> <li><strong>smokeping</strong> – For network monitoring and latency checks</li> <li><strong>unifi-controller</strong> – To manage my UniFi devices</li> <li><strong>uptimekuma</strong> – For uptime monitoring of my services</li> <li><strong>vaultwarden</strong> – My self-hosted password manager</li> <li><strong>watchyourlan</strong> – Network monitori

## Odroid H4 died in less than 2 months
 - [https://www.reddit.com/r/selfhosted/comments/1gosjvl/odroid_h4_died_in_less_than_2_months](https://www.reddit.com/r/selfhosted/comments/1gosjvl/odroid_h4_died_in_less_than_2_months)
 - RSS feed: $source
 - date published: 2024-11-11T13:47:11+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gosjvl/odroid_h4_died_in_less_than_2_months/"> <img src="https://b.thumbs.redditmedia.com/w0G-DImBDSNNDD2tsdCcIMIBGnHSKzgLz2hGYR5saCw.jpg" alt="Odroid H4 died in less than 2 months" title="Odroid H4 died in less than 2 months" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Less than 2 months ago I switched from HP DL 380G9 server to Odroid H4. I run regular stack of servARR apps, torrent client, indexers, few databases(pg, timescale) used mainly for my 9-5, and for NAS</p> <p>Odroid has a way to connect 4 SATA drives + 1 NVME at the bottom. I went straightforward way - moved my ZFS stack from old server to new. I&#39;m using Kingston DC450 drives and its been rock solid for last few years</p> <p>These 2 months this PC was working really well and I like performance aspect along with size and portability(I even took it with me on vacation to have all my content with me) and I&#39;m really disappointed its not 

## First home server - what to explore and learn next?
 - [https://www.reddit.com/r/selfhosted/comments/1gosd2h/first_home_server_what_to_explore_and_learn_next](https://www.reddit.com/r/selfhosted/comments/1gosd2h/first_home_server_what_to_explore_and_learn_next)
 - RSS feed: $source
 - date published: 2024-11-11T13:37:40+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I&#39;ve recently inherited a desktop that&#39;s ~8 years old and decided to try my hand at making a home lab! So far I&#39;ve installed Proxmox and added the following using the proxmox community scripts:</p> <ul> <li>Openmediavault to make a NAS and share data via smb</li> <li>these tools in LXCs: heimdall, jellyfin, bookstack, vikujna, myspeed, pialert, and runtipi</li> <li>in runtipi I&#39;ve played around with: openbooks, searxng, whoogle, wallos</li> <li>separately I&#39;ve had pi-hole and pivpn running for years on a Pi 4</li> </ul> <p>Machine specs</p> <ul> <li>CPU: Intel i7-7700K</li> <li>Motherboard: ASRock Z270M Extreme4</li> <li>GPU: NVIDIA GeForce RTX 2080 Ti</li> <li>RAM: 64 GB DDR4</li> <li>Drives: Samsung 970 EVO Plus 500 GB (OS) and Samsung 960 PRO 2 TB (network share)</li> </ul> <p>Immediate future plans:</p> <ul> <li>I have 2x WD 4 TB drives that will be the main network share once I buy some SATA and power cables. </l

## DOCMOST Email Configuration not working - PLEASE HELP!!
 - [https://www.reddit.com/r/selfhosted/comments/1gos0bs/docmost_email_configuration_not_working_please](https://www.reddit.com/r/selfhosted/comments/1gos0bs/docmost_email_configuration_not_working_please)
 - RSS feed: $source
 - date published: 2024-11-11T13:20:01+00:00

<!-- SC_OFF --><div class="md"><p>I have set up DocMost and it seems to work fine, except the email setup, which should be really straight forward. But here it is not working. Can anyone please check if its working, and if yes, please give me a hint whats wrong in my setup. Thanks</p> <p>so here are my settings which work in other docker apps. </p> <p>i´ve added those into the <strong>environment</strong> setting of my yaml file</p> <p><code>MAIL_DRIVER: smtp</code><br/> <code>SMTP_HOST:</code> <a href="http://smtp.gmail.com"><code>smtp.gmail.com</code></a><br/> <code>SMTP_PORT: 587</code><br/> <code>SMTP_USERNAME:</code> [<code>myemail@gmail.com</code>](mailto:<a href="mailto:myemail@gmail.com">myemail@gmail.com</a>)<br/> <code>SMTP_PASSWORD: mysecretpasswordwhichworks</code><br/> <code>SMTP_SECURE: false</code><br/> <code>MAIL_FROM_ADDRESS:</code> [<code>myemail@gmail.com</code>](mailto:<a href="mailto:myemail@gmail.com">myemail@gmail.com</a>)<br/> <code>MAIL_FROM_NAME: DOCMOST Sup

## How to easily convert video files (mp4) to audio files?
 - [https://www.reddit.com/r/selfhosted/comments/1goq6s3/how_to_easily_convert_video_files_mp4_to_audio](https://www.reddit.com/r/selfhosted/comments/1goq6s3/how_to_easily_convert_video_files_mp4_to_audio)
 - RSS feed: $source
 - date published: 2024-11-11T11:35:40+00:00

<!-- SC_OFF --><div class="md"><p>I have a collection of videos of artists performing their sets. Sometimes it&#39;s nice to show these on the TV, but in the car a video file is more of a hassle. So I would like to setup some workflow to (semi)automatically convert these videos files into audio files.</p> <p>Is anyone here doing this? If so, do you have tips?</p> <p>(I have an Unraid server running which can perform these tasks)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AluminiumHoedje"> /u/AluminiumHoedje </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1goq6s3/how_to_easily_convert_video_files_mp4_to_audio/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1goq6s3/how_to_easily_convert_video_files_mp4_to_audio/">[comments]</a></span>

## A Personal NotebookLM and Perplexity-like AI Assistant with privacy.
 - [https://www.reddit.com/r/selfhosted/comments/1goq4df/a_personal_notebooklm_and_perplexitylike_ai](https://www.reddit.com/r/selfhosted/comments/1goq4df/a_personal_notebooklm_and_perplexitylike_ai)
 - RSS feed: $source
 - date published: 2024-11-11T11:31:02+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone for the last month or two I have been trying to build a hybrid of NotebookLM and Perplexity with better integration with browsers as well. </p> <p>So here is my little attempt to make something.</p> <p>SurfSense : </p> <p>While tools like NotebookLM and Perplexity are impressive and highly effective for conducting research on any topic, imagine having both at your disposal with complete privacy control. That&#39;s exactly what SurfSense offers. With SurfSense, you can create your own knowledge base for research, similar to NotebookLM, or easily research the web just like Perplexity. SurfSense also includes an effective cross-browser extension to directly save dynamic content bookmarks, such as social media chats, calendar invites, important emails, tutorials, recipes, and more to your SurfSense knowledge base. Now, you’ll never forget anything and can easily research everything.</p> <p>Bugs are to be expected but I hope you guys give it a

## Medication Assistant - MedAssist
 - [https://www.reddit.com/r/selfhosted/comments/1gopx8h/medication_assistant_medassist](https://www.reddit.com/r/selfhosted/comments/1gopx8h/medication_assistant_medassist)
 - RSS feed: $source
 - date published: 2024-11-11T11:18:09+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gopx8h/medication_assistant_medassist/"> <img src="https://external-preview.redd.it/wTCeDev8D68Xd_kn0Ps2grj9tWpJTszFYr0lYQYntUo.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=33279852d68abc1125ffa11004a953dcf7dbb9d9" alt="Medication Assistant - MedAssist" title="Medication Assistant - MedAssist" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello lovely people,</p> <p>I&#39;m enjoying this sub a lot, I have learnt many things and got my server up and running with decent amount of useful services. It wouldn&#39;t be possible without all the help I got here and it&#39;s time to give back something from myself. Maybe one of you will host this app, hopefully.</p> <p><strong>MedAssist</strong> is a simple Node.js application made with love to help my partner manage their daily medications. It makes it easy to keep track of medication inventory and reorder on time by sending reminders. If you&#39;re unsure whet

## HTTP basic authentication for Webtop container bypassed
 - [https://www.reddit.com/r/selfhosted/comments/1gopdlj/http_basic_authentication_for_webtop_container](https://www.reddit.com/r/selfhosted/comments/1gopdlj/http_basic_authentication_for_webtop_container)
 - RSS feed: $source
 - date published: 2024-11-11T10:41:18+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I have set up a <a href="https://docs.linuxserver.io/images/docker-webtop/">Webtop</a> container with Podman. Here is the anonymised configuration of the container.</p> <pre><code>[Container] ContainerName=webtop Image=lscr.io/linuxserver/webtop:latest Volume=/path:/config:z Environment=CUSTOM_USER=&lt;user&gt; Environment=PASSWORD=&lt;password&gt; AutoUpdate=registry Label=traefik.enable=true Label=traefik.http.routers.webtop.rule=Host(`example.com`) Label=traefik.http.routers.webtop.entrypoints=websecure Label=traefik.http.routers.webtop.tls.certresolver=landsacpe Label=traefik.http.services.webtop.loadbalancer.server.scheme=http Label=traefik.http.services.webtop.loadbalancer.server.port=3000 [Install] WantedBy=default.target </code></pre> <p>It is supposed to prompt a basic authentication dialog when I access <code>example.com</code>. The weird thing is that once I have logged in, it will never ask for password again even if I clear the site 

## Which iOS Apps for selfhosted services?
 - [https://www.reddit.com/r/selfhosted/comments/1gopa9v/which_ios_apps_for_selfhosted_services](https://www.reddit.com/r/selfhosted/comments/1gopa9v/which_ios_apps_for_selfhosted_services)
 - RSS feed: $source
 - date published: 2024-11-11T10:34:22+00:00

<!-- SC_OFF --><div class="md"><p>Can someone recommend me some good iOS apps for selfhosted services? </p> <p>for example Nextcloud with podcast manager etc., for proxmox and so on.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/niemand112233"> /u/niemand112233 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gopa9v/which_ios_apps_for_selfhosted_services/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gopa9v/which_ios_apps_for_selfhosted_services/">[comments]</a></span>

## Help me to choose between this mini pc
 - [https://www.reddit.com/r/selfhosted/comments/1gop8vy/help_me_to_choose_between_this_mini_pc](https://www.reddit.com/r/selfhosted/comments/1gop8vy/help_me_to_choose_between_this_mini_pc)
 - RSS feed: $source
 - date published: 2024-11-11T10:31:38+00:00

<!-- SC_OFF --><div class="md"><p>I would like to set up a selfhost environment with unraid, immich and nextcloud. I have seen these two solutions:</p> <ul> <li>Beelink Mini PC EQR5</li> <li>Beelink EQR6 Mini PC</li> </ul> <p>The eqr5 version has 32 gig of ddr4 ram</p> <p>The eqr6 version has 24 gig</p> <p>What interests me most is that they are silent and these models seem to be.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ShirtFit2732"> /u/ShirtFit2732 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gop8vy/help_me_to_choose_between_this_mini_pc/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gop8vy/help_me_to_choose_between_this_mini_pc/">[comments]</a></span>

## Blinko - A nice AI-Enhanced Notes app
 - [https://www.reddit.com/r/selfhosted/comments/1gop6xf/blinko_a_nice_aienhanced_notes_app](https://www.reddit.com/r/selfhosted/comments/1gop6xf/blinko_a_nice_aienhanced_notes_app)
 - RSS feed: $source
 - date published: 2024-11-11T10:27:42+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gop6xf/blinko_a_nice_aienhanced_notes_app/"> <img src="https://external-preview.redd.it/3swk6cH7lHysnohaEeIgbP8C-M41C5kxCVIHzKXy2Jo.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=aa2d2901bb7eecb43c0fc4edf9d3a32ef0e5d214" alt="Blinko - A nice AI-Enhanced Notes app" title="Blinko - A nice AI-Enhanced Notes app" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>This young project impressed me with its simplicity and exceptionally smooth user experience.🥰</p> <p><a href="https://preview.redd.it/8dsfg2ck190e1.png?width=1566&amp;format=png&amp;auto=webp&amp;s=d71299a473729f4fe3d402518d0274378c330138">https://preview.redd.it/8dsfg2ck190e1.png?width=1566&amp;format=png&amp;auto=webp&amp;s=d71299a473729f4fe3d402518d0274378c330138</a></p> <p><a href="https://github.com/blinko-space/blinko">https://github.com/blinko-space/blinko</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/J

## Llama 3.1 405B vs. GPT-4o
 - [https://www.reddit.com/r/selfhosted/comments/1goo426/llama_31_405b_vs_gpt4o](https://www.reddit.com/r/selfhosted/comments/1goo426/llama_31_405b_vs_gpt4o)
 - RSS feed: $source
 - date published: 2024-11-11T09:07:28+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1goo426/llama_31_405b_vs_gpt4o/"> <img src="https://a.thumbs.redditmedia.com/SHHlWFR5wm9RgWrrZn5h2xrW1R5s6zukjjSAkGgorO8.jpg" alt="Llama 3.1 405B vs. GPT-4o" title="Llama 3.1 405B vs. GPT-4o" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey everyone! I’ve been reading up on Llama 3.1 405B and GPT-4o, and here’s a quick rundown on how they stack up:</p> <ul> <li><strong>General Performance</strong>: GPT-4o generally leads in reasoning and coding tasks, delivering more accurate results in areas like code generation. In a recent study, Llama-3.1–405B and GPT-4o were compared across five scenarios: mathematics, code generation, tool invocation, JSON information extraction, and creative writing. While Llama 3.1 405B is the strongest open-source model available, it falls just slightly short of GPT-4o in overall performance.</li> <li><strong>Multilingual Capabilities</strong>: Llama 3.1 405B shines in multilingual

## PlikShare: my take on self-hosted file sharing platform
 - [https://www.reddit.com/r/selfhosted/comments/1goo3k0/plikshare_my_take_on_selfhosted_file_sharing](https://www.reddit.com/r/selfhosted/comments/1goo3k0/plikshare_my_take_on_selfhosted_file_sharing)
 - RSS feed: $source
 - date published: 2024-11-11T09:06:28+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys, </p> <p>I&#39;ve recently finished working on an MVP of a self-hosted app called PlikShare. It&#39;s an application that allows you to store and share your files with the outside world. Kind of like Dropbox, but much simpler and obviously: self-hosted.</p> <p>I decided to build it because working with Dropbox in the past, I faced some issues that annoyed me, and I wanted to build something to scratch my own itch - so to speak.</p> <p>I used to work on an online courses platform, which involved working with video materials that I needed to share with people who would then take it, process it, do some post-production, and send it back to me. And I noticed that it was unexpectedly... cumbersome. I wanted to give each person access to their own folder so they could upload videos there, but without seeing what else was there - or only seeing the stuff they uploaded. And I couldn&#39;t do it. The sharing options in most software I found works in o

## DOCMOST the first header is very laggy and not responsive enough
 - [https://www.reddit.com/r/selfhosted/comments/1gonvbz/docmost_the_first_header_is_very_laggy_and_not](https://www.reddit.com/r/selfhosted/comments/1gonvbz/docmost_the_first_header_is_very_laggy_and_not)
 - RSS feed: $source
 - date published: 2024-11-11T08:49:26+00:00

<!-- SC_OFF --><div class="md"><p>yesterday i installed docmost for my project documentations<br/> it was a bit frustrating to install, but it works now as a docker image on my nas.</p> <p>when creating a new page the header is responds so slow to my typing, that it is nearly not possible to write a single word without messing it up completely. it probably has to do with the autosave function, which seems to kick in every 5 seconds or so. then the link of the site changes too. when typing in exactly this moment, the text gets screwed up</p> <p>is there anything i can change in the variables to make this thing a bit more responsive?</p> <p>as far as i tested it out, this problem is only when typing into the first header.</p> <p>best wishes.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Odd_Astronomer_9279"> /u/Odd_Astronomer_9279 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gonvbz/docmost_the_first_header_is_very_lagg

## Best cloud option for media storage
 - [https://www.reddit.com/r/selfhosted/comments/1gons0o/best_cloud_option_for_media_storage](https://www.reddit.com/r/selfhosted/comments/1gons0o/best_cloud_option_for_media_storage)
 - RSS feed: $source
 - date published: 2024-11-11T08:42:19+00:00

<!-- SC_OFF --><div class="md"><p>I need to build a cloud storage system accessible from anywhere. It&#39;s my first build, so I would prefer something easy to install. I am refurbishing an old computer rocking an Intel i7-3770(non-K) and 2 TB of SATA storage. I need to be able to upload any kind of File Format on it.</p> <p>PS: I don&#39;t know how to use Linux</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mr_nieN"> /u/Mr_nieN </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gons0o/best_cloud_option_for_media_storage/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gons0o/best_cloud_option_for_media_storage/">[comments]</a></span>

## restic+rclone backup and restore
 - [https://www.reddit.com/r/selfhosted/comments/1gonhsl/resticrclone_backup_and_restore](https://www.reddit.com/r/selfhosted/comments/1gonhsl/resticrclone_backup_and_restore)
 - RSS feed: $source
 - date published: 2024-11-11T08:20:29+00:00

<!-- SC_OFF --><div class="md"><p>I have all my compose and config files backed up to the cloud with restic and rclone. So, lets say I suffer a catastrophic failure. I go to rebuild and all of my files are encrypted on google drive. How do I access my rclone remote if the config is encrypted in the cloud?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/a_40oz_of_Mickeys"> /u/a_40oz_of_Mickeys </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gonhsl/resticrclone_backup_and_restore/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gonhsl/resticrclone_backup_and_restore/">[comments]</a></span>

## 4 bay NAS
 - [https://www.reddit.com/r/selfhosted/comments/1goneez/4_bay_nas](https://www.reddit.com/r/selfhosted/comments/1goneez/4_bay_nas)
 - RSS feed: $source
 - date published: 2024-11-11T08:13:24+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone.</p> <p>Curious, what would you guys recommand for a 4 bay NAS ?</p> <p>I&#39;ve been looking at used Synology and the 4 bay ones still under warranty/not EOL are expensive. My only criteria is.. noise.</p> <p>Making this thread for ideas before spending that kind of money :).</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/thms0"> /u/thms0 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1goneez/4_bay_nas/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1goneez/4_bay_nas/">[comments]</a></span>

## Feedback for a new type of self-hostable service
 - [https://www.reddit.com/r/selfhosted/comments/1gon54l/feedback_for_a_new_type_of_selfhostable_service](https://www.reddit.com/r/selfhosted/comments/1gon54l/feedback_for_a_new_type_of_selfhostable_service)
 - RSS feed: $source
 - date published: 2024-11-11T07:54:12+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I hope this question doesn&#39;t break the rules. From what I&#39;ve seen on here most services people self host are for media, backups, or homelab-related</p> <p>What I&#39;m curious about is the interest in self-hosted software for an individual&#39;s privacy, specifically data removal from data brokers or a company someone no longer wants to be signed up for.</p> <p>They&#39;re a couple cloud-based companies that do the aforementioned like SayMine or Optery. They connect to your email inbox and show you your digital footprint, allowing you to &quot;clean&quot; it up or reclaim your data</p> <p>But giving access to your inbox to a third party in order to gain more privacy seems redundant. A self-hosted solution that connects to your email inbox using your own API key would be ideal, no?</p> <p>But is software like this even something people would bother to self-host? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit

## Docker and Composer doubt
 - [https://www.reddit.com/r/selfhosted/comments/1gomtwo/docker_and_composer_doubt](https://www.reddit.com/r/selfhosted/comments/1gomtwo/docker_and_composer_doubt)
 - RSS feed: $source
 - date published: 2024-11-11T07:31:14+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone. I am new to this self hosting thing. The reason I thought I could get into this is I took a class on some analytics There we discussed Docker and container. So I was like what the hell. FYI I have engineering degree in mechanics &amp; electronics .</p> <p>My question is simple after self hosting a service or application in the docker should I restart the container every single time I restart my computer to start the application or I can directly open it by typing port number in the Browser. How do I restart the container in Linux, as there is no desktop shortcut for Docker. </p> <p>I know it a messy question. help me understand please.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/koujay"> /u/koujay </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gomtwo/docker_and_composer_doubt/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gomtwo

## Good Local Pastebin which search?
 - [https://www.reddit.com/r/selfhosted/comments/1gom9sp/good_local_pastebin_which_search](https://www.reddit.com/r/selfhosted/comments/1gom9sp/good_local_pastebin_which_search)
 - RSS feed: $source
 - date published: 2024-11-11T06:52:33+00:00

<!-- SC_OFF --><div class="md"><p>I tried using microbin and it&#39;s alright but I don&#39;t like the no search query&#39;s and random names.<br/> I also can&#39;t understand why you can&#39;t have no editing or deleting without password without it not then showing up on the public list.</p> <p>I also tried privatebin but you need to setup https which requires a domain</p> <p>BTW I ment with instead of which but now it&#39;s too late to change the title soooo yeah.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ItsHotdogFred"> /u/ItsHotdogFred </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gom9sp/good_local_pastebin_which_search/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gom9sp/good_local_pastebin_which_search/">[comments]</a></span>

## Any free alternative to TSPlus?
 - [https://www.reddit.com/r/selfhosted/comments/1golufi/any_free_alternative_to_tsplus](https://www.reddit.com/r/selfhosted/comments/1golufi/any_free_alternative_to_tsplus)
 - RSS feed: $source
 - date published: 2024-11-11T06:23:35+00:00

<!-- SC_OFF --><div class="md"><p>I have been using TS Plus for quite sometime and now want to switch to something free that I can self host.</p> <p>My requirements are as follows:</p> <ul> <li>To be deployed on windows server OS</li> <li>Bind windows programs to users (users can only view the apps they have been granted permissions for)</li> <li>Multiple users can access the programs simultaneously via web portal ( via HTML5, because windows only allows 2 RDP connections for free)</li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Aggravating_Ad_3462"> /u/Aggravating_Ad_3462 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1golufi/any_free_alternative_to_tsplus/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1golufi/any_free_alternative_to_tsplus/">[comments]</a></span>

## K3s - Upgrade from raspberry pis
 - [https://www.reddit.com/r/selfhosted/comments/1gols04/k3s_upgrade_from_raspberry_pis](https://www.reddit.com/r/selfhosted/comments/1gols04/k3s_upgrade_from_raspberry_pis)
 - RSS feed: $source
 - date published: 2024-11-11T06:19:12+00:00

<!-- SC_OFF --><div class="md"><p>Hi there,</p> <p>i&#39;ve been rocking four Raspberry Pi 4&#39;s with 8GB RAM as my Kubernetes Homelab with some services. Services that need more power e.g. Jellyfin, Immich oder Paperless are currently hosted on a seperate Optiplex with an i5-8500 with Docker.</p> <p>Lately I&#39;ve been thinking to abandon the raspberry pi 4s and go with some i5-8500t, i5-8500 or i5-9500 computers to host RKE2 on them.</p> <p>Since i&#39;m located in germany it would cost arount 160€ per node.<br/> i5-8400t with 32 Gig RAM for 160€ (m720q tiny ussf), i5-8500t with 16 Gig RAM for 170€ (m920q tiny ussf) or i5-9500 with 16 Gig RAM for 160€ (m920s sff).</p> <p>Which of theses variants would you take into consideration to host an K3S (maybe even RKE2) cluster at home, in regards to power consumption and powr overall? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Nalgfar"> /u/Nalgfar </a> <br/> <span><a href="https://www.reddit.

## Help finding a monitoring system
 - [https://www.reddit.com/r/selfhosted/comments/1gola8o/help_finding_a_monitoring_system](https://www.reddit.com/r/selfhosted/comments/1gola8o/help_finding_a_monitoring_system)
 - RSS feed: $source
 - date published: 2024-11-11T05:49:05+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;ve been looking for a simple agent/server monitoring system that fits my particular bill. I want the agent to monitor the return of several APIs, commands, etc and send the data to the main server that will send me alerts. There won&#39;t be any direct access between agent and server so the data has to be pushed through API via internet or something similar. </p> <p>What I&#39;ve tried:<br/> * check_mk: it&#39;s kind of a freemium experience plus push is paid.<br/> * zabbix: used it for years but configuring is a pain<br/> * grafana+prometheus+whatever: overkill </p> <p>Also couldn&#39;t find anything like this on the awesome-selfhosted repos, some help here please.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/alphardww"> /u/alphardww </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gola8o/help_finding_a_monitoring_system/">[link]</a></span> &#32; <span><a href="https://www.re

## Self-Hosted Email Server
 - [https://www.reddit.com/r/selfhosted/comments/1gojq7a/selfhosted_email_server](https://www.reddit.com/r/selfhosted/comments/1gojq7a/selfhosted_email_server)
 - RSS feed: $source
 - date published: 2024-11-11T04:17:41+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I am transitioning about 40 domains with emails (primarily mailing lists) for my fraternity and I need recommendations for mail servers with a GUI. I have technical knowledge to set up everything but I will be giving access to each of the 40 domain (chapter) admins to manage their own mailing lists with me being the master admin and a GUI would make everyone&#39;s life easier.</p> <p>For context, we currently use mailman on our old server but we&#39;re moving hosts for websites and email. mailman is great for managing but wondering if there&#39;s other options to consider</p> <p>Ideal situation is:<br/> - An MTA included<br/> - Ability to manage mailing lists and designate admins to each domain<br/> - GUI interface<br/> - Free</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/_MrMartian96"> /u/_MrMartian96 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gojq7a/

## URL for Minecraft server
 - [https://www.reddit.com/r/selfhosted/comments/1gojd1v/url_for_minecraft_server](https://www.reddit.com/r/selfhosted/comments/1gojd1v/url_for_minecraft_server)
 - RSS feed: $source
 - date published: 2024-11-11T03:57:02+00:00

<!-- SC_OFF --><div class="md"><p>So, let me start by saying that I know so little about this that I&#39;m not even sure what I&#39;m wanting to do is possible or sensible. So, apologies if this has been asked and answered before, but i&#39;m so clueless about this that I don&#39;t even know what to search for.</p> <p>Anyway, I have set up a Minecraft server in docker that we can access on our home network. Happy days. My kids wanted to let their mates access the server and access it themselves outside of the home network. I have set up a VPS on my router to forward the port and that also works. </p> <p>I do not however have a static ip. so even though i have successfully set up the port forwarding for the server when my public ip changes my daughter is potentially going to be fielding calls from her friends to get the new IP. So, is there a way to assign a URL to my network so that when my ip changes the server is still accessible? I tried setting up Cloudflare, but i <em>very</em> 

## Self hosted secrets manager
 - [https://www.reddit.com/r/selfhosted/comments/1goj5yi/self_hosted_secrets_manager](https://www.reddit.com/r/selfhosted/comments/1goj5yi/self_hosted_secrets_manager)
 - RSS feed: $source
 - date published: 2024-11-11T03:45:47+00:00

<!-- SC_OFF --><div class="md"><p>What is everyone using as a secrets manager for api keys? does anyone have experience with infisical <a href="https://infisical.com/docs/self-hosting/overview">https://infisical.com/docs/self-hosting/overview</a>, and can recommend it? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Bulbasaur2015"> /u/Bulbasaur2015 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1goj5yi/self_hosted_secrets_manager/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1goj5yi/self_hosted_secrets_manager/">[comments]</a></span>

## Can VPS be used as data middleman for data stored on NAS, seedbox, other cloud storage locations?
 - [https://www.reddit.com/r/selfhosted/comments/1goirdy/can_vps_be_used_as_data_middleman_for_data_stored](https://www.reddit.com/r/selfhosted/comments/1goirdy/can_vps_be_used_as_data_middleman_for_data_stored)
 - RSS feed: $source
 - date published: 2024-11-11T03:23:16+00:00

<!-- SC_OFF --><div class="md"><p><strong>Can this be done?</strong> </p> <p>As the post title explains, I am imagining using a VPS as a central hub for files and data but then have the data located in various places locally or in the cloud that make the most sense for what it is and how it would be used. However I doni&#39;t want to have to remember exactly where everything is and connect or sync with each of those things specifically if I don&#39;t have to. It also seems that syncing everything in multiple places is also inefficient use of storage (if not needed for performance) and may be more prone to errors and corruption. </p> <p><strong>What I would like to do...</strong></p> <p>What I am imagining is that I could use any device (personal computer, phone, tablet, work computer, etc) and &quot;ask&quot; or browse some App/service on the VPS for specific files or data. The App/service would know where things live and connect the device to the source somehow, ideally seemlessly. 

## Plex server and some containers
 - [https://www.reddit.com/r/selfhosted/comments/1goiaka/plex_server_and_some_containers](https://www.reddit.com/r/selfhosted/comments/1goiaka/plex_server_and_some_containers)
 - RSS feed: $source
 - date published: 2024-11-11T02:58:06+00:00

<!-- SC_OFF --><div class="md"><p>Looking to setup a new Plex server that will have an external drive attached. Want to be able to handle a few 4k transcodes with subtitle. Also planning on running a handful of containers including Home Assistant and AdGuard. I&#39;m thinking going down the used/refurb mini PC route. Will be running Linux.</p> <p>For CPU I&#39;m thinking i5-8500 or i5-10500 with 16gb ram and USB 3 for external media. Does this seem reasonable? Seeing this on ebay for $140-200. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/zildjianfan"> /u/zildjianfan </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1goiaka/plex_server_and_some_containers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1goiaka/plex_server_and_some_containers/">[comments]</a></span>

## Traveling from US to China, access to my VPN
 - [https://www.reddit.com/r/selfhosted/comments/1goi66v/traveling_from_us_to_china_access_to_my_vpn](https://www.reddit.com/r/selfhosted/comments/1goi66v/traveling_from_us_to_china_access_to_my_vpn)
 - RSS feed: $source
 - date published: 2024-11-11T02:51:27+00:00

<!-- SC_OFF --><div class="md"><p>I have OpenVPN setup, hosted on my PFsense box. I use FreeDNS (afraid.org) for DNS A-record forwarding so I now have a hostname instead of IP, should it change.</p> <p>I know China has the great firewall, so I&#39;m wondering if I can still access my home network, mostly for watching my cameras / security. As of now I have a .com domain, if I picked a .cn (which <a href="http://afraid.org">afraid.org</a> does offer), would that help at all? </p> <p>Is there any kind of obfuscation methods I could try, or use some 3rd party proxy service?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/technobrendo"> /u/technobrendo </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1goi66v/traveling_from_us_to_china_access_to_my_vpn/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1goi66v/traveling_from_us_to_china_access_to_my_vpn/">[comments]</a></span>

## Any free Fremius alternative
 - [https://www.reddit.com/r/selfhosted/comments/1gog561/any_free_fremius_alternative](https://www.reddit.com/r/selfhosted/comments/1gog561/any_free_fremius_alternative)
 - RSS feed: $source
 - date published: 2024-11-11T01:05:19+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I wonder if it exists any free open source selfhosted alternative to freemius ?</p> <p>Could be awesome to integrate with WordPress plugin. The only one I found is LicenseBox but isn’t free.</p> <p>Thanks a lot</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/The-Little-Tinkerer"> /u/The-Little-Tinkerer </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gog561/any_free_fremius_alternative/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gog561/any_free_fremius_alternative/">[comments]</a></span>

## Adding space for storage
 - [https://www.reddit.com/r/selfhosted/comments/1gog264/adding_space_for_storage](https://www.reddit.com/r/selfhosted/comments/1gog264/adding_space_for_storage)
 - RSS feed: $source
 - date published: 2024-11-11T01:01:06+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gog264/adding_space_for_storage/"> <img src="https://b.thumbs.redditmedia.com/rYsrZ7EFCcDFDhiQ7jyY69ibILM5-ZXv_DxNRwOzVog.jpg" alt="Adding space for storage " title="Adding space for storage " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>How can i add more space for a couple of HDD&#39;s 3.5 without sacrificing the cd reader?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/vaquishaProdigy"> /u/vaquishaProdigy </a> <br/> <span><a href="https://www.reddit.com/gallery/1gog264">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gog264/adding_space_for_storage/">[comments]</a></span> </td></tr></table>

## Cloudflare Domain/NginX --> Jellyfin syncplay only works when all clients use the cf domain
 - [https://www.reddit.com/r/selfhosted/comments/1gofwbx/cloudflare_domainnginx_jellyfin_syncplay_only](https://www.reddit.com/r/selfhosted/comments/1gofwbx/cloudflare_domainnginx_jellyfin_syncplay_only)
 - RSS feed: $source
 - date published: 2024-11-11T00:52:59+00:00

<!-- SC_OFF --><div class="md"><p>Looks like it is finally my time to ask a question after participating here for quite some time ^^</p> <p><strong>I currently have an issue with jellyfin and syncplay:</strong></p> <p>Using the local jellyfin IP on my webOS TV works fine, except for syncplay. Syncplay only works when all clients in the session connect via my cloudflare domain jelly.domain.x which NginX (websockets configured according to jellyfin docs) redirects to the local jellyfin IP. I tried setting up a hostname in my openWRT router (jelly.local pointing to NginX) and added that to my jelly.domain.x redirect in NginX. This lets me access jellyfin but syncplay still does not work for whatever reason.</p> <p>Disabling the cf proxy, disabling &quot;force SSL&quot; in NginX and letting the other client connect via http:// too does not help either.</p> <p>I would just stick to the external domain for my local WebOS TV but my upload bandwidth is a limiting factor and so I would prefer

## PSA: Update Vaultwarden as soon as possible
 - [https://www.reddit.com/r/selfhosted/comments/1gof9y4/psa_update_vaultwarden_as_soon_as_possible](https://www.reddit.com/r/selfhosted/comments/1gof9y4/psa_update_vaultwarden_as_soon_as_possible)
 - RSS feed: $source
 - date published: 2024-11-11T00:21:58+00:00

<!-- SC_OFF --><div class="md"><p>Update to the latest version (<a href="https://github.com/dani-garcia/vaultwarden/releases/tag/1.32.4">1.32.4</a>) as soon as possible:</p> <blockquote> <p>This release has fixed some CVE Reports reported by a third party security auditor and we recommend everybody to update to the latest version as soon as possible. The contents of these reports will be disclosed publicly in the future.</p> </blockquote> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/-rch-"> /u/-rch- </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gof9y4/psa_update_vaultwarden_as_soon_as_possible/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gof9y4/psa_update_vaultwarden_as_soon_as_possible/">[comments]</a></span>

