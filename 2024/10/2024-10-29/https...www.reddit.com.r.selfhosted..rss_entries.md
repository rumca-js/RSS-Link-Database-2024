# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## I can't get my Docker Adguard-Dns server to handle other container requests correctly.
 - [https://www.reddit.com/r/selfhosted/comments/1gf8uoi/i_cant_get_my_docker_adguarddns_server_to_handle](https://www.reddit.com/r/selfhosted/comments/1gf8uoi/i_cant_get_my_docker_adguarddns_server_to_handle)
 - RSS feed: $source
 - date published: 2024-10-29T23:34:21+00:00

<!-- SC_OFF --><div class="md"><p>Here is my scenario:<br/> I have several containers on my server, including my local dns (adguard).<br/> I use my phone, pc or whatever and everything works fine. My adguard shows in the logs what ip made the resolve request and the device itself receives the resolved request. But if another containers makes a request....</p> <p>The logs show that the request comes from &quot;172.21.0.1&quot; which isn&#39;t true, as it is the ip of the adguard itself and ofc the requesting container can&#39;t receive the resolved domain back.</p> <p>I tried putting the containers in the same network, into the same compose file, both, setting the dns in the compose manually... it does not work. Every time I made a change I used nslookup to check if it works or not.</p> <p>Maybe important to mention. In my resolv.conf, the nameserver is set to &quot;192.168.178.x&quot;, yet when I do a nslookup in a container, it will use 127.0.0.x to approach the dns.</p> </div><!-- 

## Hosting a dedicated game server "the right way"
 - [https://www.reddit.com/r/selfhosted/comments/1gf73a9/hosting_a_dedicated_game_server_the_right_way](https://www.reddit.com/r/selfhosted/comments/1gf73a9/hosting_a_dedicated_game_server_the_right_way)
 - RSS feed: $source
 - date published: 2024-10-29T22:14:41+00:00

<!-- SC_OFF --><div class="md"><p>Hey! </p> <p>Put together my first own homeserver and I&#39;m having a blast learning more about networking aspects and Linux. </p> <p>And now with the Steam sale I got myself some shiny new games and was thinking: Why shouldn&#39;t I try and host a multiplayer server myself? </p> <p>Not because I have to, but because I want to. </p> <p>Although putting up a pihole with unbound as upstream dns, a reverse proxy with nginx so I can use domain names inside my own network with dyndns and lots of other smaller containers with docker, did also show me some limitations I will have to work around.</p> <p>So far everything is running inside (bridge mode) docker containers on a barebones Debian foundation. </p> <p>I know that I may want to look into setting up a windows or linux VM for the game server and then isolate it in an VLAN, although I&#39;m more than thankful for other recommendations. </p> <p>Thought about trying Ansible before, so the idea to just t

## All the best to tteck! Show the guy some love!
 - [https://www.reddit.com/r/selfhosted/comments/1gf6m22/all_the_best_to_tteck_show_the_guy_some_love](https://www.reddit.com/r/selfhosted/comments/1gf6m22/all_the_best_to_tteck_show_the_guy_some_love)
 - RSS feed: $source
 - date published: 2024-10-29T21:53:30+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gf6m22/all_the_best_to_tteck_show_the_guy_some_love/"> <img src="https://external-preview.redd.it/uCx3TQF0YkkG9iVrz4IndeU6j_c-w1PyK_SYa-5bnWs.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=878d2c9d42eda82336c0b2024c5cf2f2e498bcee" alt="All the best to tteck! Show the guy some love!" title="All the best to tteck! Show the guy some love!" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/_dakazze_"> /u/_dakazze_ </a> <br/> <span><a href="https://github.com/tteck/Proxmox/discussions/4009">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gf6m22/all_the_best_to_tteck_show_the_guy_some_love/">[comments]</a></span> </td></tr></table>

## .srv DNS entry vs nginx Stream
 - [https://www.reddit.com/r/selfhosted/comments/1gf6aig/srv_dns_entry_vs_nginx_stream](https://www.reddit.com/r/selfhosted/comments/1gf6aig/srv_dns_entry_vs_nginx_stream)
 - RSS feed: $source
 - date published: 2024-10-29T21:39:17+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I&#39;m planning to host a minecraft server. I see 2 options but am not sure which one is better.</p> <p>Option 1: .srv DNS entry and Port forwarding in router to my game server.</p> <p>Option 2: Port forwardind in router to my nginx reverse proxy and setting up a stream for game server port.</p> <p>Which one to choose? Which solution has better security? Does one solution have better performance?</p> <p>Greetings</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Least-Flatworm7361"> /u/Least-Flatworm7361 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gf6aig/srv_dns_entry_vs_nginx_stream/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gf6aig/srv_dns_entry_vs_nginx_stream/">[comments]</a></span>

## What OS to use for Simple Home Server?
 - [https://www.reddit.com/r/selfhosted/comments/1gf5yft/what_os_to_use_for_simple_home_server](https://www.reddit.com/r/selfhosted/comments/1gf5yft/what_os_to_use_for_simple_home_server)
 - RSS feed: $source
 - date published: 2024-10-29T21:24:41+00:00

<!-- SC_OFF --><div class="md"><p>I recently got a HP EliteDesk 800 G4 which I want to use for my home server.</p> <p>I will be running OpenVPN, Home Assistant and some sort of backup software for my family using something like FolderSync or Syncthing.</p> <p>I&#39;m not sure what Linux-based OS to go for.</p> <p>I heard Ubuntu/ Debian are good but I also keep hearing about Proxmox. Proxmox does seem quite complicated though and I&#39;m unsure if it will be worth the configuration for my use. I will still keep it as an option if it&#39;s worth it.</p> <p>If someone could please recommend me which Operating System to go for.</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Pretty_Volume1169"> /u/Pretty_Volume1169 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gf5yft/what_os_to_use_for_simple_home_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gf5yft/what_os_to_u

## Free VPS Comparison Platform
 - [https://www.reddit.com/r/selfhosted/comments/1gf5x9p/free_vps_comparison_platform](https://www.reddit.com/r/selfhosted/comments/1gf5x9p/free_vps_comparison_platform)
 - RSS feed: $source
 - date published: 2024-10-29T21:23:15+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve made <a href="http://thinklessvps.com">thinklessvps.com</a> a website that allows you to filter 2500+ individual VPS offers from hosting providers such as digitalocean, hetzner, linode, aws lightsail and more.</p> <p>I&#39;m grateful for any kind of feedback to improve the user experience, would also greatly appreciate contribution the <a href="http://thinklessvps.com/resource-hub">thinklessvps.com/resource-hub</a> would love to share more helpful articles about selfhosting on a vps there.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/noignorabimus"> /u/noignorabimus </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gf5x9p/free_vps_comparison_platform/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gf5x9p/free_vps_comparison_platform/">[comments]</a></span>

## Looking for Fast VPS
 - [https://www.reddit.com/r/selfhosted/comments/1gf5w76/looking_for_fast_vps](https://www.reddit.com/r/selfhosted/comments/1gf5w76/looking_for_fast_vps)
 - RSS feed: $source
 - date published: 2024-10-29T21:22:00+00:00

<!-- SC_OFF --><div class="md"><p>Hi<br/> I have used DOcean in the past and I find it very expensive.<br/> Then I jumped to IOzoom until they null-routed my ip (DDOS) and I left them for Linode since it provided DDOS protection.</p> <p>I have tried the 8 decicated core vps for $144 and I find it expensive . The 8 shared core vps ($96) has performance issues maybe because the low speed clock 2.0 ghz.<br/> I am also noticing my google metrics in pagespeed insights decline (ttfb).</p> <p><strong>Any of you guys can recommend a decent stable high clocked vps alternative?</strong><br/> I am considering Vultr, Oracle Cloud, IONOS... </p> <p>Other hosts that I have tried and don&#39;t like are: Ramnode, Upcloud, BuyVm, Kamatera.<br/> I use hetzner but for this particular site I can&#39;t use them.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ryanmile"> /u/ryanmile </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gf5w76/lookin

## Working on assignment for a internal only email service and I'm stumped
 - [https://www.reddit.com/r/selfhosted/comments/1gf5lnk/working_on_assignment_for_a_internal_only_email](https://www.reddit.com/r/selfhosted/comments/1gf5lnk/working_on_assignment_for_a_internal_only_email)
 - RSS feed: $source
 - date published: 2024-10-29T21:09:39+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m currently struggling with an assignment where I&#39;m using a virtualized windows server 2012 to create some sort of email service for my network. I originally started overcomplicating it and setting it up for externally, but that is beyond what I need. All I need to do is simply send an email from one PC to another in my network. It sounds like I could do it without any programs, and just what I have available, but I&#39;m not sure where to start. I have a DNS server running and had set it up for SMTP using IIS 6.0, but that is where I end up getting stumped.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JurbiasFate"> /u/JurbiasFate </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gf5lnk/working_on_assignment_for_a_internal_only_email/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gf5lnk/working_on_assignment_for_a_internal_only_email/">[c

## question about reverse proxy (nginx)
 - [https://www.reddit.com/r/selfhosted/comments/1gf5k3w/question_about_reverse_proxy_nginx](https://www.reddit.com/r/selfhosted/comments/1gf5k3w/question_about_reverse_proxy_nginx)
 - RSS feed: $source
 - date published: 2024-10-29T21:07:54+00:00

<!-- SC_OFF --><div class="md"><p>I have setup an nginx reverse proxy using <a href="https://github.com/NginxProxyManager/nginx-proxy-manager">this nginx image</a></p> <p>Everything works great, however the login page was still reachable under the ip-address of my vps and the port (which I have changed). </p> <p>So ive setup a proxy host from that port to a subdomain using https, but the port is still reachable under the domain, without ssl.</p> <p>I guess that is no good. What am I doing wrong and how can I fix this, or rather help me understand what is happening here. Firewall options dont change anything, probaply because the proxy overrides it?</p> <p>Help much appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/That1Unfortunate"> /u/That1Unfortunate </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gf5k3w/question_about_reverse_proxy_nginx/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfh

## Mailcow and Bitwarden self hosted
 - [https://www.reddit.com/r/selfhosted/comments/1gf5709/mailcow_and_bitwarden_self_hosted](https://www.reddit.com/r/selfhosted/comments/1gf5709/mailcow_and_bitwarden_self_hosted)
 - RSS feed: $source
 - date published: 2024-10-29T20:53:11+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gf5709/mailcow_and_bitwarden_self_hosted/"> <img src="https://preview.redd.it/ssny6xwjdrxd1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=7a7bbc493b0a4fc7a8e526ac14c97076b6680147" alt="Mailcow and Bitwarden self hosted " title="Mailcow and Bitwarden self hosted " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Is this specification enough for those two?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/anonuser-al"> /u/anonuser-al </a> <br/> <span><a href="https://i.redd.it/ssny6xwjdrxd1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gf5709/mailcow_and_bitwarden_self_hosted/">[comments]</a></span> </td></tr></table>

## Help!
 - [https://www.reddit.com/r/selfhosted/comments/1gf53ix/help](https://www.reddit.com/r/selfhosted/comments/1gf53ix/help)
 - RSS feed: $source
 - date published: 2024-10-29T20:49:07+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gf53ix/help/"> <img src="https://preview.redd.it/z0xt62otcrxd1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=ab93b188cc504798885e023d2616ceaa97c8180a" alt="Help!" title="Help!" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>What have I done wrong? My synology now no longer updates the apps and more of them are stopping. I&#39;ve used this guide: <a href="https://emby.media/community/index.php?/topic/103636-how-to-access-synology-nas-as-admin-or-superuser-using-winscp/">https://emby.media/community/index.php?/topic/103636-how-to-access-synology-nas-as-admin-or-superuser-using-winscp/</a> to try to edit files earlier and suspect its the fault. I&#39;m going mad trying to fix it!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kevman289"> /u/kevman289 </a> <br/> <span><a href="https://i.redd.it/z0xt62otcrxd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit

## Docmost v0.5: third-party embeds and more
 - [https://www.reddit.com/r/selfhosted/comments/1gf4u7f/docmost_v05_thirdparty_embeds_and_more](https://www.reddit.com/r/selfhosted/comments/1gf4u7f/docmost_v05_thirdparty_embeds_and_more)
 - RSS feed: $source
 - date published: 2024-10-29T20:38:10+00:00

<!-- SC_OFF --><div class="md"><p>Once again, for the uninitiated, Docmost is an open-source collaborative wiki and documentation software. It is an open-source alternative to the likes of Confluence and Notion.</p> <p>Docmost v0.5 comes with support for third-party embeds. You can now embed Loom videos and more.</p> <p><strong>Highlights from this release</strong></p> <ul> <li><p>Third-party embed support for:</p> <ul> <li>Airtable</li> <li>Loom</li> <li>YouTube</li> <li>Google Drive</li> <li>Figma</li> <li>Typeform</li> <li>Miro</li> <li>Vimeo</li> <li>Framer</li> </ul></li> <li><p>The sidebar page-tree has been improved to sync in real-time across collaborators</p></li> <li><p>Dark mode support for Drawio diagrams editor.</p></li> </ul> <p>Full release notes: <a href="https://github.com/docmost/docmost/releases/tag/v0.5.0">https://github.com/docmost/docmost/releases/tag/v0.5.0</a></p> <p>Website: <a href="https://docmost.com/">https://docmost.com</a><br/> Docs: <a href="https://do

## Are the common Docker Reverse Proxies safe to expose to the open internet?
 - [https://www.reddit.com/r/selfhosted/comments/1gf4cye/are_the_common_docker_reverse_proxies_safe_to](https://www.reddit.com/r/selfhosted/comments/1gf4cye/are_the_common_docker_reverse_proxies_safe_to)
 - RSS feed: $source
 - date published: 2024-10-29T20:18:00+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;m currently planing to expose a small subset of apps for myself to the open internet. </p> <p>I have to choose a Revers Proxy that does support PROXY PROTOCOL, see my <a href="https://www.reddit.com/r/selfhosted/comments/1g3psc1/docker_reverse_proxy_with_proxy_protocol_support/">last post</a>, therefore I have the following list of candidates, in order of subjective personal preference:</p> <ol> <li><a href="https://caddyserver.com/docs/">Caddy</a></li> <li><a href="https://doc.traefik.io/traefik/getting-started/install-traefik/">Traefik</a></li> <li><a href="https://docs.linuxserver.io/general/swag/">SWAG</a></li> <li>Plain NGINX</li> <li>Plain HAProxy</li> </ol> <p>So far I have tested NPM (before I knew I would need PROXY PROTOCOL support) and I have a working PoC for Caddy. </p> <p>I could be wrong, but I find it strange that I have to build a Dockerfile for Caddy to build the container so that I have the features I require; keyword Clo

## Apple Notes app formatting
 - [https://www.reddit.com/r/selfhosted/comments/1gf3bpw/apple_notes_app_formatting](https://www.reddit.com/r/selfhosted/comments/1gf3bpw/apple_notes_app_formatting)
 - RSS feed: $source
 - date published: 2024-10-29T19:34:47+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gf3bpw/apple_notes_app_formatting/"> <img src="https://b.thumbs.redditmedia.com/HX71JZjcY2FWweeFn8jW9Ca4chE9_B5ijHawka8k21g.jpg" alt="Apple Notes app formatting" title="Apple Notes app formatting" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Apple <a href="http://Notes.app">Notes.app</a> allows note formatting, image insertions, and a lot of other useful things when used with Apple iCloud and I like it, but none of those features are available with 3rd party WebDAV accounts like Google and others. Is it a completely different technology and <a href="http://Notes.app">Notes.app</a> just acts differently with iCloud services, or is there an available WebDAV extension with formatting support? I want to host a personal WebDAV server with that support or even code it, but I am unable to find any documentation about such an extension to WebDAV unfortunately. </p> <p><a href="https://preview.redd.it/9wkfdm4czqxd1

## Selfhosted Box / Inventory Management
 - [https://www.reddit.com/r/selfhosted/comments/1gf33c0/selfhosted_box_inventory_management](https://www.reddit.com/r/selfhosted/comments/1gf33c0/selfhosted_box_inventory_management)
 - RSS feed: $source
 - date published: 2024-10-29T19:25:14+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a self-hosted solution to manage the content of my inventory boxes.</p> <p>I&#39;ve already checked out multiple popular inventory management apps like Grocy, but they are either overkill and/or do not fulfill my requirements.</p> <p>I would really appreciate any ideas!</p> <p>All of my boxes are labeled with a unique number (e.g. &quot;21&quot;). It put stuff into them semi-random, means I try to keep similar stuff together but I also try to use all space in the boxes so some contain very different items. Right now I&#39;m using a single markdown file in which there&#39;s a heading for each box with bullet points for the items beneath. I sync this file with syncthing and it kinda works but I think there are better solutions.</p> <p>My requirements:</p> <ul> <li>1.) Needs to be FOSS.<br/></li> <li>2.) Data needs to be stored on my server.<br/></li> <li>3.) Support for multiple users.<br/></li> <li>4.) Offline support. Means I need

## Best SSH Tunnel
 - [https://www.reddit.com/r/selfhosted/comments/1gf2zg2/best_ssh_tunnel](https://www.reddit.com/r/selfhosted/comments/1gf2zg2/best_ssh_tunnel)
 - RSS feed: $source
 - date published: 2024-10-29T19:21:04+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I have frrom around 4-5 months a 3 node K3S cluster with various service on it. Most of them are only on my local VPN but for nextcloud I prefear to have it on internet in order to reach my storage everywhere without a VPN (I know is a risk but this is a different topic).</p> <p>Until now my ISP gave me a public ip, and I had no problem. Today I just installed from the same ISP the fiber and now I don&#39;t have the public ip anymore.</p> <p>The best solution is if ISP can give to me a public ip back, but this is still under investigation.</p> <p>For now as a workaround I switch on a small VM on hetzner with a reverse proxy, but this cost to me 5,43€ and is another things to mantain.</p> <p>Which other alternative I can use to have a tunnel and that maybe are easy-peasy to configure an mantain ? Free could be the top, but even paying it a couple of euros per months could be ok if I can have some kind of service with anti DDOS atta

## Note taking app for teams
 - [https://www.reddit.com/r/selfhosted/comments/1gf1wt8/note_taking_app_for_teams](https://www.reddit.com/r/selfhosted/comments/1gf1wt8/note_taking_app_for_teams)
 - RSS feed: $source
 - date published: 2024-10-29T18:36:40+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m searching a note taking for teams around 5-10 members. There are multiple teams, which should be able to share notes on demand which eachother. Scalability would be great. At the moment we are using Microsoft OneNote. But as we are shifting to a more infrastructure as code approach, we would like to be able to generate documentations with scripts. If something is missing, the docu could be manually adjusted. I know, the script could export some textfile and afterwards it could be imported to e.g. OneNote. But insert via script would be nice. Another great feature would be a webui, to share some general informations public. Private I&#39;ve already tried Joplin and logseq. But those don&#39;t seem to support multiple user. I like markdown, but we also have some less tech centric users. Also some included task management would be great. Is there something, which meets our needs? Today I&#39;ve found <a href="http://www.appflowy.io">www.appflowy

## Opinions regarding compensation or recognition as an open-source contributor.
 - [https://www.reddit.com/r/selfhosted/comments/1gf13cj/opinions_regarding_compensation_or_recognition_as](https://www.reddit.com/r/selfhosted/comments/1gf13cj/opinions_regarding_compensation_or_recognition_as)
 - RSS feed: $source
 - date published: 2024-10-29T18:03:00+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone! </p> <p>I&#39;m looking to understand some of the common challenges faced by open-source contributors when it comes to things like monetary compensation and recognition. As an open source developer, what does fairness and sustainability look like to you?</p> <p>For instance, if you contribute to an open source project, do you expect recognition or compensation? Or if given incentives would it make you more interested in contributing to open-source projects?</p> <p>Thanks for sharing your thoughts!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/shadeed20"> /u/shadeed20 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gf13cj/opinions_regarding_compensation_or_recognition_as/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gf13cj/opinions_regarding_compensation_or_recognition_as/">[comments]</a></span>

## Looking for a solution for a collaborative note-taking/worldbuilding service or stack for tabletop rpgs like Dungeons and Dragons focused on players' collected information
 - [https://www.reddit.com/r/selfhosted/comments/1gf12ar/looking_for_a_solution_for_a_collaborative](https://www.reddit.com/r/selfhosted/comments/1gf12ar/looking_for_a_solution_for_a_collaborative)
 - RSS feed: $source
 - date published: 2024-10-29T18:01:47+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a wiki or other collaborative notes app, essentially. We are years-deep in a very in-depth D&amp;D campaign and realizing that we need to get better organized as we approach our endgame. Right now, we all have separate notes that we&#39;ve kept, but I would like to merge them together into something more cohesive. Notion is a popular option, but I&#39;m looking for something self-hosted and less expensive for collaboration. Besides, I&#39;m not super familiar with Notion, but I don&#39;t believe it has all of the features I&#39;m looking for.</p> <p>It will be a process to collect our backlog of information, I&#39;m sure, but the initial ingest of new info needs to generally be easy to use, otherwise it won&#39;t get used. Our DM isn&#39;t the most tech savvy person, and he needs to be able to use it, too. That&#39;s why it should be focused on worldbuilding from the player perspective, not the storyteller. Some features can be more 

## Spooky Halloween sounds
 - [https://www.reddit.com/r/selfhosted/comments/1gf0njh/spooky_halloween_sounds](https://www.reddit.com/r/selfhosted/comments/1gf0njh/spooky_halloween_sounds)
 - RSS feed: $source
 - date published: 2024-10-29T17:45:09+00:00

<!-- SC_OFF --><div class="md"><p>Hi All, hoping someone has an easy idea.</p> <p>I want to play some spooky Halloween sounds when Frigate detects someone at my porch, like a manic laugh. </p> <p>My initial thoughts are to pop a Bluetooth speaker in the porch and use either my Android phone, Window or Mac laptop to then play the sound. I have also bought Tasker for Android but it looks like MQTT Client that I have seen older posts refer to doesn&#39;t exist anymore.</p> <p>I have Frigate setup with MQTT and Home Assistant, HA already turns the porch light on for 2 mins if there is someone on the drive at night, I thought if I could link the sound and light at the same time with some evil cackle it would work well.</p> <p>I could write something in C# but with only a few days to go I&#39;m not going to get the chance to brush up on my MQTT skills and work out how to play an MP3 in time.</p> <p>So I&#39;m looking for a hopefully free solution that I can use with either MQTT or HA to pl

## Is there a self-hosted speed reading tool?
 - [https://www.reddit.com/r/selfhosted/comments/1gezt05/is_there_a_selfhosted_speed_reading_tool](https://www.reddit.com/r/selfhosted/comments/1gezt05/is_there_a_selfhosted_speed_reading_tool)
 - RSS feed: $source
 - date published: 2024-10-29T17:09:51+00:00

<!-- SC_OFF --><div class="md"><p>I was a fan of <a href="https://spritz.com/">Spritzlet</a> and currently have <a href="https://chromewebstore.google.com/detail/stutter/fbapmaboedchhgjolcnpfgoanbfajchl">Stutter extension</a> in my browser, but I&#39;m aware that this may present some security questions as they&#39;re not self hosted.</p> <p>So I was wondering if there was that type of speed reading tool available to self-host?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/weeemrcb"> /u/weeemrcb </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gezt05/is_there_a_selfhosted_speed_reading_tool/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gezt05/is_there_a_selfhosted_speed_reading_tool/">[comments]</a></span>

## Best Hardware for a Self-Hosting Newbie?
 - [https://www.reddit.com/r/selfhosted/comments/1geznez/best_hardware_for_a_selfhosting_newbie](https://www.reddit.com/r/selfhosted/comments/1geznez/best_hardware_for_a_selfhosting_newbie)
 - RSS feed: $source
 - date published: 2024-10-29T17:03:29+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m new to self-hosting and need help selecting hardware that fits my requirements. My approach is to have a dedicated machine for hosting the DNS service (since there is considerable traffic on my LAN due to my family size) and to separate that service from the rest. Then, a more powerful server will host the other services like Git, VPN, FTP, etc. The setup would look like this:</p> <p>## Main Server</p> <p>### Software</p> <p>```All software is ran inside of Docker```</p> <p>#### Main Tools</p> <p>- **Nextcloud** - Google Drive Replacement</p> <p>- **Vaultwarden (Bitwarden)** - Password Manager</p> <p>- **Ghost** - Simple Blogging Platform</p> <p>- **Gitea** - Git Platform</p> <p>- **act_runner** - Gitea Actions Runner</p> <p>- **Renovate** - Dependency Updates</p> <p>- **Filebrowser** - A Simple Web File Browser</p> <p>#### Management</p> <p>- **Homepage** - A Simple Dashboard to keep everything organized. Complete with Docker Integration so 

## How To Create A NVIDIA H100 GPU Cloud Server To Run And Train AI, ML, And LLMs Apps On DigitalOcean
 - [https://www.reddit.com/r/selfhosted/comments/1gezl7s/how_to_create_a_nvidia_h100_gpu_cloud_server_to](https://www.reddit.com/r/selfhosted/comments/1gezl7s/how_to_create_a_nvidia_h100_gpu_cloud_server_to)
 - RSS feed: $source
 - date published: 2024-10-29T17:01:02+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gezl7s/how_to_create_a_nvidia_h100_gpu_cloud_server_to/"> <img src="https://external-preview.redd.it/pTSvnWvRw6FKNQaFMak-6-QA0jpDEOIcyrtVqlYgf-A.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=fe22e7a4dd0152f666d36abf7bf74b984065f6fd" alt="How To Create A NVIDIA H100 GPU Cloud Server To Run And Train AI, ML, And LLMs Apps On DigitalOcean" title="How To Create A NVIDIA H100 GPU Cloud Server To Run And Train AI, ML, And LLMs Apps On DigitalOcean" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/websplaining"> /u/websplaining </a> <br/> <span><a href="https://youtu.be/aDPUOzk443E">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gezl7s/how_to_create_a_nvidia_h100_gpu_cloud_server_to/">[comments]</a></span> </td></tr></table>

## How do websites like 12foot.io or internet archive render websites inside of a website
 - [https://www.reddit.com/r/selfhosted/comments/1geyxpy/how_do_websites_like_12footio_or_internet_archive](https://www.reddit.com/r/selfhosted/comments/1geyxpy/how_do_websites_like_12footio_or_internet_archive)
 - RSS feed: $source
 - date published: 2024-10-29T16:33:39+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to host a service which lets me go to <a href="http://www.mydomain.com/websiteIWant.com">www.mydomain.com/websiteIWant.com</a> and see it rendered. I want to do this as a way to block some WiFi restrictions. Having done some research the solution seems to be a reverse proxy? Is this correct? otherwise how would you recommend doing this? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FloppyMonkey07"> /u/FloppyMonkey07 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1geyxpy/how_do_websites_like_12footio_or_internet_archive/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1geyxpy/how_do_websites_like_12footio_or_internet_archive/">[comments]</a></span>

## How to do self-hosting for comicbooks like this?
 - [https://www.reddit.com/r/selfhosted/comments/1geyprb/how_to_do_selfhosting_for_comicbooks_like_this](https://www.reddit.com/r/selfhosted/comments/1geyprb/how_to_do_selfhosting_for_comicbooks_like_this)
 - RSS feed: $source
 - date published: 2024-10-29T16:24:47+00:00

<!-- SC_OFF --><div class="md"><p>I am complete new into self-hosting. I want something where I can store my books (comics) in my mac and can read from my ipad (both online and offline) to save my ipad space. I am using yacreader app on ipad (also exploring chunky reader). How to achieve my goal (and is this gonna be free or how much I may need?)</p> <p>Basically can I stream comicbooks from ipad like this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OilNo7863"> /u/OilNo7863 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1geyprb/how_to_do_selfhosting_for_comicbooks_like_this/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1geyprb/how_to_do_selfhosting_for_comicbooks_like_this/">[comments]</a></span>

## Omnivore.app is joining ElevenLabs. Users have until November 15th to export their data, after which it will be deleted
 - [https://www.reddit.com/r/selfhosted/comments/1geymmu/omnivoreapp_is_joining_elevenlabs_users_have](https://www.reddit.com/r/selfhosted/comments/1geymmu/omnivoreapp_is_joining_elevenlabs_users_have)
 - RSS feed: $source
 - date published: 2024-10-29T16:21:16+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1geymmu/omnivoreapp_is_joining_elevenlabs_users_have/"> <img src="https://external-preview.redd.it/4HhpaLe3GPfPPPEqeirdOXdkS0zvCZL3jUneFVkfy2U.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=f4682fd8dfc901b5247b89006170534e60588183" alt="Omnivore.app is joining ElevenLabs. Users have until November 15th to export their data, after which it will be deleted" title="Omnivore.app is joining ElevenLabs. Users have until November 15th to export their data, after which it will be deleted" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TheTwelveYearOld"> /u/TheTwelveYearOld </a> <br/> <span><a href="https://blog.omnivore.app/p/omnivore-is-joining-elevenlabs">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1geymmu/omnivoreapp_is_joining_elevenlabs_users_have/">[comments]</a></span> </td></tr></table>

## KoalaKeys - Create Portable Cheat Sheets
 - [https://www.reddit.com/r/selfhosted/comments/1geyalm/koalakeys_create_portable_cheat_sheets](https://www.reddit.com/r/selfhosted/comments/1geyalm/koalakeys_create_portable_cheat_sheets)
 - RSS feed: $source
 - date published: 2024-10-29T16:07:33+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>When I committed to using my mouse less, I looked for a tool to create custom keyboard cheat sheets but couldn’t find the right fit. So, I decided to built KoalaKeys. It generates stylish, customizable HTML cheat sheets you can use practically anywhere - locally or hosted.</p> <p>You can find the GitHub repo here: <a href="https://github.com/rtuszik/KoalaKeys">KoalaKeys</a></p> <p>I am also hosting a public instance here: <a href="https://rtuszik.github.io/KoalaKeys-Collection/">KoalaKeys Demo</a></p> <p>Looking forward to your feedback!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rtuszik"> /u/rtuszik </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1geyalm/koalakeys_create_portable_cheat_sheets/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1geyalm/koalakeys_create_portable_cheat_sheets/">[comments]</a></span>

## Need help with postfix + dovecot
 - [https://www.reddit.com/r/selfhosted/comments/1gey3h7/need_help_with_postfix_dovecot](https://www.reddit.com/r/selfhosted/comments/1gey3h7/need_help_with_postfix_dovecot)
 - RSS feed: $source
 - date published: 2024-10-29T15:59:37+00:00

<!-- SC_OFF --><div class="md"><p>First of all I just want to clarify that yes, there are out of the box services like iredmail, docker mail server, mailcow etc. and Yes i could use them. but I just want to try to learn to setup myself first so that even in future if I use something like iredmail or mailcow or something, at least i&#39;d know whats going on under the hood and i am not just sitting duck if something goes wrong. Now thats cleared,<br/> So for past few days, I&#39;ve been trying to setup postfix + dovecot in my server and I have almost got it working as well. I am able to send and receive mails.. i am able to get <a href="http://mail-tester.com">mail-tester.com</a> score of 9/10.<br/> so this is what i need help with.<br/> 1. I tried to setup postgres with postfix. I have created the db, added virtual alias map, virtual domain map and virtual mailbox map in /etc/postfix/main.conf file. i just need help making sure its integrated properly.<br/> 2. in mail-tester i am loo

## How to do automated encrypted off-site backups
 - [https://www.reddit.com/r/selfhosted/comments/1gexyyn/how_to_do_automated_encrypted_offsite_backups](https://www.reddit.com/r/selfhosted/comments/1gexyyn/how_to_do_automated_encrypted_offsite_backups)
 - RSS feed: $source
 - date published: 2024-10-29T15:54:24+00:00

<!-- SC_OFF --><div class="md"><p>My brother and I are hoping to backup each other&#39;s Unraid SMB shares with important things like documents, pictures, etc and are looking for options. He suggested we simply use NextCloud and point to the shares we want to backup. While this sounds fine, I&#39;m hoping to add some kind of encryption so that he can&#39;t go poking around my files (and vice-versa).</p> <p>I&#39;ve been reading about the E2EE app on NextCloud and I think that&#39;s what I&#39;m looking for, but I&#39;m not sure. Essentially, I&#39;m hoping for a complete hands-off approach where I tell NextCloud (or another backup solution) which SMB shares to backup, and those get automatically backed up and updated to my brother&#39;s server in an encrypted manner. So whenever I add a picture to Immich or a document to Paperless for example, NextCloud will automatically detect this (within a reasonable delay) and add just that new information to the off-site backup without having t

## Hosting suggestions
 - [https://www.reddit.com/r/selfhosted/comments/1gexqhh/hosting_suggestions](https://www.reddit.com/r/selfhosted/comments/1gexqhh/hosting_suggestions)
 - RSS feed: $source
 - date published: 2024-10-29T15:44:29+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m going to be renting a dedicated server for modded minecraft game servers, and thought I could use it for self hosting as well, as a newbie, what would be recommended applications to start with self hosting? If it&#39;s docker based, what experience level does thr application target? I&#39;m very new to docker and still learning the basics, to the point I&#39;m excited when I get anything working on it. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sure_Internet8507"> /u/Sure_Internet8507 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gexqhh/hosting_suggestions/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gexqhh/hosting_suggestions/">[comments]</a></span>

## ChartDB - open-source database diagram visualization tool
 - [https://www.reddit.com/r/selfhosted/comments/1gexgh2/chartdb_opensource_database_diagram_visualization](https://www.reddit.com/r/selfhosted/comments/1gexgh2/chartdb_opensource_database_diagram_visualization)
 - RSS feed: $source
 - date published: 2024-10-29T15:32:39+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I’m one of the creators of ChartDB.</p> <p>I built ChartDB to simplify database design and visualization. I’d love to get feedback from the self-hosted community and would also welcome any contribution!</p> <p>This database diagram tool is similar to traditional ones you can find: dbeaver, dbdiagram, drawsql, etc.</p> <p><a href="https://github.com/chartdb/chartdb">https://github.com/chartdb/chartdb</a></p> <p><strong>Key Features:</strong></p> <ul> <li>Instant schema import with just one query.</li> <li>AI-powered export to generate DDL scripts for easy database migration.</li> <li>Supports multiple database types: PostgreSQL, MySQL, SQLite, Mssql, ClickHouse and more.</li> <li>Customizable ER diagrams to visualize your database structure.</li> <li>Fully open-source and easy to self-host.</li> </ul> <p><strong>Tech Stack:</strong></p> <ul> <li>React + TypeScript</li> <li>Vite</li> <li>ReactFlow</li> <li>Shadcn-ui</li> <li>Dexie.js</li> </ul>

## DuckDNS issues recently?
 - [https://www.reddit.com/r/selfhosted/comments/1gex9hs/duckdns_issues_recently](https://www.reddit.com/r/selfhosted/comments/1gex9hs/duckdns_issues_recently)
 - RSS feed: $source
 - date published: 2024-10-29T15:24:29+00:00

<!-- SC_OFF --><div class="md"><p>Has anybody had issues with DuckDNS recently? I am using it for my home assistant and half the time it doesnt work. Are there any free alternatives? I dont want to pay for a domain.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JMS1717"> /u/JMS1717 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gex9hs/duckdns_issues_recently/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gex9hs/duckdns_issues_recently/">[comments]</a></span>

## Synology Active Insight causes ~10% of CPU constantly
 - [https://www.reddit.com/r/selfhosted/comments/1gewm5a/synology_active_insight_causes_10_of_cpu](https://www.reddit.com/r/selfhosted/comments/1gewm5a/synology_active_insight_causes_10_of_cpu)
 - RSS feed: $source
 - date published: 2024-10-29T14:56:58+00:00

<!-- SC_OFF --><div class="md"><p>Just FYI for those who use a Synology as their NAS. If you disable Active Insight you get around 10% CPU on the NAS back. I tested this on two different Synologys. <a href="https://michaelspost.com/synology-cpu.png">My CPU graph after disabling Active Insight</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/billysmusic"> /u/billysmusic </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gewm5a/synology_active_insight_causes_10_of_cpu/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gewm5a/synology_active_insight_causes_10_of_cpu/">[comments]</a></span>

## Introducing Many Notes: a markdown note taking app
 - [https://www.reddit.com/r/selfhosted/comments/1gewfjv/introducing_many_notes_a_markdown_note_taking_app](https://www.reddit.com/r/selfhosted/comments/1gewfjv/introducing_many_notes_a_markdown_note_taking_app)
 - RSS feed: $source
 - date published: 2024-10-29T14:48:53+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gewfjv/introducing_many_notes_a_markdown_note_taking_app/"> <img src="https://external-preview.redd.it/gxHBGqcQuPWsJVj2noTLgGMMzfoOwslvyiIMhSy4C44.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=4ab7383b7b09284b05e47d9108e5b46cc17542a9" alt="Introducing Many Notes: a markdown note taking app" title="Introducing Many Notes: a markdown note taking app" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/6q2cglluipxd1.png?width=2022&amp;format=png&amp;auto=webp&amp;s=e6c08695d80a2a2e51f0d328c50f8796bbf801c1">https://preview.redd.it/6q2cglluipxd1.png?width=2022&amp;format=png&amp;auto=webp&amp;s=e6c08695d80a2a2e51f0d328c50f8796bbf801c1</a></p> <p>I have been using Obsidian with Syncthing to organize my notes for a while. Although the app itself is great, relying on a second application for syncing across all my devices never completely satisfied me. As a result, I decided to create m

## Netcup experience
 - [https://www.reddit.com/r/selfhosted/comments/1gew7x3/netcup_experience](https://www.reddit.com/r/selfhosted/comments/1gew7x3/netcup_experience)
 - RSS feed: $source
 - date published: 2024-10-29T14:39:38+00:00

<!-- SC_OFF --><div class="md"><p>Hey everybody!</p> <p>Just wanted to put out into this subreddit my current experience with netcup (netcup.eu) and a cautionary tale about their customer support, as I&#39;ve experienced it today.</p> <p>This is one of those stories that, if not for this one customer service experience, I would 100% back netcup for any and everyone who would ask me for VPS recommendation in europe - as I&#39;ve done so in the past.</p> <p>Here&#39;s the tale. This morning my VPS was shut down due to an abuse report. As per their email, it reads as:</p> <blockquote> <p>Your server v2XXXXXXXX has performed an attack on one or multiple other servers on the internet. Thereby considerable network ressources have been used and parts of our network have been severely affected. Therefore, your server has been disabled.<br/> For the necessary maintenance and analysis work we can start your system into our rescue system, if you wish. Your server will then be started with a min

## Telegram bot that notifies you of new GitHub releases
 - [https://www.reddit.com/r/selfhosted/comments/1gevxaa/telegram_bot_that_notifies_you_of_new_github](https://www.reddit.com/r/selfhosted/comments/1gevxaa/telegram_bot_that_notifies_you_of_new_github)
 - RSS feed: $source
 - date published: 2024-10-29T14:26:33+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I create simple Telegram bot (@janisreleasebot) that monitors the releases of given GitHub repos, sending messages upon a new release.</p> <p><strong>Features</strong></p> <ul> <li>Easy subscription to repo by owner/name, GitHub/PyPI/npm URL or uploading requirements.txt or package.json file</li> <li>Rich markdown formatting for release note</li> <li>Auto subscription to starred repos</li> <li>Ready for self-hosting, has docker image</li> <li>Work locally, without white IP and domain name</li> <li>Open-source - code availabale at GitHub (<a href="https://github.com/JanisV/release-bot">https://github.com/JanisV/release-bot</a>)</li> </ul> <p><strong>Plans</strong></p> <ul> <li>Subscription to DockerHub, PyPI releases</li> <li>E-mail, Discord</li> <li>Your idea</li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JanisVt"> /u/JanisVt </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gev

## Would this be a safe setup?
 - [https://www.reddit.com/r/selfhosted/comments/1gevviq/would_this_be_a_safe_setup](https://www.reddit.com/r/selfhosted/comments/1gevviq/would_this_be_a_safe_setup)
 - RSS feed: $source
 - date published: 2024-10-29T14:24:26+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I have a VPS at my disposal now, and I&#39;m sick of tailscale honestly, so what I have in mind is putting wireguard on the vps, connecting it to my server (port forwarding isn&#39;t allowed in my home network) and routing the requests coming to the vps to the home server based on the subdomain. For this I&#39;d expose the wireguard port and ports 80 and 443 on the VPS, and only 80 and 443 on the home server. The services all require authentication as well. My question is, since I don&#39;t really trust this VPS provider, will they be able to read the traffic going through wireguard? And is there any big step I&#39;m missing when it comes to securing the server. SSH is of course key only as well on both, I&#39;m also not sure if I should put the reverse proxy on the VPS, which would force me to open up the ports on the docker services or if I should put the proxy on the home server itself.The second setup sure sounds safer to me but I don&#39

## My plans
 - [https://www.reddit.com/r/selfhosted/comments/1gev65y/my_plans](https://www.reddit.com/r/selfhosted/comments/1gev65y/my_plans)
 - RSS feed: $source
 - date published: 2024-10-29T13:53:58+00:00

<!-- SC_OFF --><div class="md"><p>Lenovo Mini 1 network Stack ADGUARDHOME Wireguard Tailscale Unbound Rustdesk NPM</p> <p>Lenovo Mini 2 file stack Nextcloud Immich</p> <p>This is what I&#39;m laying out for my self hosted home setup any thoughts</p> <p>Everything running Ubuntu Server with docker I&#39;m thinking of bringing the Networkstack online firsr</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/HorrorFiend66"> /u/HorrorFiend66 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gev65y/my_plans/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gev65y/my_plans/">[comments]</a></span>

## Getting logged out of my services
 - [https://www.reddit.com/r/selfhosted/comments/1geuiss/getting_logged_out_of_my_services](https://www.reddit.com/r/selfhosted/comments/1geuiss/getting_logged_out_of_my_services)
 - RSS feed: $source
 - date published: 2024-10-29T13:23:47+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys, I am selfhosting for a while now. Currently encounter irritating issue. </p> <p>I have a VPS with closed firewall and running docker for some services. I connect via tailscale to the http webUI&#39;s</p> <p>I recently added:<br/> - windmill<br/> - mimio </p> <p>Both of those services log me out after a while, can&#39;t really pinpoint what triggers it, mimio is worse then windmill. It happens in Chrome and Firefox. </p> <p>Any idea how to debug this or what is causing it? Haven&#39;t had this before. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/krimpenrik"> /u/krimpenrik </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1geuiss/getting_logged_out_of_my_services/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1geuiss/getting_logged_out_of_my_services/">[comments]</a></span>

## New to the game! (Quite) A lot of data, infrequent access remotely
 - [https://www.reddit.com/r/selfhosted/comments/1geu6gm/new_to_the_game_quite_a_lot_of_data_infrequent](https://www.reddit.com/r/selfhosted/comments/1geu6gm/new_to_the_game_quite_a_lot_of_data_infrequent)
 - RSS feed: $source
 - date published: 2024-10-29T13:07:37+00:00

<!-- SC_OFF --><div class="md"><p>Hey gurus! </p> <p>Disclaimer: I consider myself a very good Win user, a beginner in Linux but I&#39;ve played a bit with some distros for fun and a bit of programming. I know zero of networking or cloud solutions basically...</p> <p>Having said that, I work with quite a lot of data (around 4TB) that i currently store on 3 different HDD/SSD, 2 at home and 1 always with me. Yes I travel A LOT for work around the globe and I might (or most of the times might not) need some data from that HDD </p> <p>My initial idea was to create an S3 bucket on AWS and have the files stored there, with some infrequent access tier and pricing, but then, after replacing my latest laptop I got interested in self-hosting my drive at home</p> <p>Now, at home i have an old laptop and a desktop computer that basically I use for low-end gaiming and streaming netflix and co while in the bedroom. The desktop is plugged in with a Smart wall plug and I can turn it on via smartphon

## Encryption for Nextcloud on TrueNAS Scale
 - [https://www.reddit.com/r/selfhosted/comments/1geu5rb/encryption_for_nextcloud_on_truenas_scale](https://www.reddit.com/r/selfhosted/comments/1geu5rb/encryption_for_nextcloud_on_truenas_scale)
 - RSS feed: $source
 - date published: 2024-10-29T13:06:43+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1geu5rb/encryption_for_nextcloud_on_truenas_scale/"> <img src="https://b.thumbs.redditmedia.com/gRVwms4E_pb0r-v90LZKzApstTAghsw8KFDPCjIVqnM.jpg" alt="Encryption for Nextcloud on TrueNAS Scale" title="Encryption for Nextcloud on TrueNAS Scale" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I just finished setting up my Nextcloud server using a Cloudflare tunnel on TrueNAS Scale following these two tutorials (what a beautiful feeling to have my first own cloud server):</p> <ul> <li><a href="https://www.truenas.com/docs/scale/24.04/scaletutorials/apps/communityapps/installnextcloudmedia/">https://www.truenas.com/docs/scale/24.04/scaletutorials/apps/communityapps/installnextcloudmedia/</a></li> <li><a href="https://www.truenas.com/docs/truenasapps/appsecurity/cloudflaretunnel/">https://www.truenas.com/docs/truenasapps/appsecurity/cloudflaretunnel/</a></li> </ul> <p>However, I am a total noo

## What recommendations for Googe Maps Location?
 - [https://www.reddit.com/r/selfhosted/comments/1geu2h4/what_recommendations_for_googe_maps_location](https://www.reddit.com/r/selfhosted/comments/1geu2h4/what_recommendations_for_googe_maps_location)
 - RSS feed: $source
 - date published: 2024-10-29T13:02:35+00:00

<!-- SC_OFF --><div class="md"><p>Since Google has abolished the ability to determine the location or history via desktop, you are forced to use the app for this. Unfortunately, with Google I need a Google account to determine the location (despite location sharing) for more than one day - from a family member. Without a Google account, a family member has to manually share the location every day so that I can determine the location. And all this only via smartphone.</p> <p>What alternatives can you currently recommend to replace Google Maps Location? I know that Nextcloud has the option, but I want a lightweight and not a bloated Nextcloud just for that.</p> <p>Preferably where you can determine your location and see the history of where you have been. That&#39;s all I need.</p> <p>For Android, iOS must be there in any case. Uncomplicated (secure) self-hosted of course.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/uffno"> /u/uffno </a> <br/>

## Help with Accessing Subdomain from Outside My Network - Port Forwarding Issue?
 - [https://www.reddit.com/r/selfhosted/comments/1geu0b1/help_with_accessing_subdomain_from_outside_my](https://www.reddit.com/r/selfhosted/comments/1geu0b1/help_with_accessing_subdomain_from_outside_my)
 - RSS feed: $source
 - date published: 2024-10-29T12:59:53+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m having trouble with accessing a web service running on my home network from outside. I&#39;ve set up a domain, let&#39;s say example.com, and I want to send data to a subdomain, data.example.com, via a POST request from my computer.</p> <p>I&#39;ve set up port forwarding on my router to direct traffic to my network&#39;s public IP address. However, I can only send data and access this subdomain when I&#39;m on my own network. It&#39;s not working from external networks, even though the port is forwarded and the subdomain is configured to point to my public IP. Any idea why this might be happening?</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mammy0707"> /u/Mammy0707 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1geu0b1/help_with_accessing_subdomain_from_outside_my/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g

## Note app with AI integration?
 - [https://www.reddit.com/r/selfhosted/comments/1getg9o/note_app_with_ai_integration](https://www.reddit.com/r/selfhosted/comments/1getg9o/note_app_with_ai_integration)
 - RSS feed: $source
 - date published: 2024-10-29T12:32:23+00:00

<!-- SC_OFF --><div class="md"><p>Looking for a note taking app with OpenAI API integration or chatgpt etc. Eventually I would like to host my own instance of AI, but don&#39;t have the specs on the current server.</p> <p>Any suggestions?</p> <p>Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jamalstevens"> /u/jamalstevens </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1getg9o/note_app_with_ai_integration/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1getg9o/note_app_with_ai_integration/">[comments]</a></span>

## What are some reliable VPS provider with good price performance?
 - [https://www.reddit.com/r/selfhosted/comments/1get6d7/what_are_some_reliable_vps_provider_with_good](https://www.reddit.com/r/selfhosted/comments/1get6d7/what_are_some_reliable_vps_provider_with_good)
 - RSS feed: $source
 - date published: 2024-10-29T12:17:43+00:00

<!-- SC_OFF --><div class="md"><p>I used to have a free Oracle account where I run multiple small websites for myself, friends and family, and also running a few self hosted app like N8N, uptimekuma, and some php/python scripts. Now the account is terminated while I was away from home, and there&#39;s not even a prior warning...</p> <p>So I&#39;ve learn my lesson not to rely on anything that&#39;s given for free, so now I&#39;m looking for something else that is reliable, and will let me sleep sound without worrying my sites go down while I&#39;m sleeping, any recommendation?</p> <p>I&#39;m thinking about going straight to AWS Lightsail 4GB, which does have the best price for raw performance, but I guess no one beats the reliability of AWS?</p> <p>(I also like Hetzner, have used them in the past, while they offer much better value, it doesn&#39;t have the region I want, which means if I go with them I would have to endure ~200ms, which can be kinda annoying when working on my sites)<

## Distro
 - [https://www.reddit.com/r/selfhosted/comments/1get1t8/distro](https://www.reddit.com/r/selfhosted/comments/1get1t8/distro)
 - RSS feed: $source
 - date published: 2024-10-29T12:10:42+00:00

<!-- SC_OFF --><div class="md"><p>what is the best distro to install in a vps to use wireguard/openvpn nowadays?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/d678h"> /u/d678h </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1get1t8/distro/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1get1t8/distro/">[comments]</a></span>

## Power draw vs TDP - which setup to choose?
 - [https://www.reddit.com/r/selfhosted/comments/1ges6fk/power_draw_vs_tdp_which_setup_to_choose](https://www.reddit.com/r/selfhosted/comments/1ges6fk/power_draw_vs_tdp_which_setup_to_choose)
 - RSS feed: $source
 - date published: 2024-10-29T11:22:53+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys, i am trying to build a power efficient server. I have narrowed my options down to two board/cpu combinations. One is optimized for low TDP, using consumer parts. The other one would use second hand server parts and does not look at TDP.</p> <p><strong>Here are the build options:</strong></p> <ul> <li>Xeon E5-2687W v4 (165TDP) in X10DRH-CT</li> <li>R7 PRO 5750GE (35TDP) in MSI MAG B550 Tomahawk</li> </ul> <p><strong>Rest of the specs:</strong></p> <ul> <li>5x 4tb WD Red</li> <li>64 gb ECC ram</li> </ul> <p>I know that TDP ratings for consumer parts are highly misleading. Noctua has switched to NSRP because consumer cpu producers basically lie about TDP. Instead of TDP (maximum thermal output) they commonly list ADP (average) as the TDP, to the point that &quot;maximum TDP&quot; and &quot;average TDP&quot; have become common terms. I think it is safe to assume this would not be acceptable for direct-to-business parts. Next, TDP is about therma

## Need a tutorial for the complete Selfhostet LLM sphere
 - [https://www.reddit.com/r/selfhosted/comments/1ges1yk/need_a_tutorial_for_the_complete_selfhostet_llm](https://www.reddit.com/r/selfhosted/comments/1ges1yk/need_a_tutorial_for_the_complete_selfhostet_llm)
 - RSS feed: $source
 - date published: 2024-10-29T11:15:39+00:00

<!-- SC_OFF --><div class="md"><p>Is there any complete tutorial for this? I really consider to build up a homeserver, but I am really not sure which level I can expect with something like an nvidia 3060. Can I possibly reach somethinglike Chatgpt4, or it&#39;s not even in the same universe? :D I don&#39;t know. I am interested in Mistral, but I don&#39;t understand the different versions, or is LLama better? So a beginner tutorial would be really something nice.</p> <p>I already found many websites, but some are really outdated. Till now, I consider openlama or LocalAi with mistral or LLama. But I would like to know if it makes sense at all with a limited budget, or it&#39;s more useful to hold the chatgpt subscription.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/XextraneusX"> /u/XextraneusX </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ges1yk/need_a_tutorial_for_the_complete_selfhostet_llm/">[link]</a></span> &#32

## How to check if a container with a fixed version needs update?
 - [https://www.reddit.com/r/selfhosted/comments/1gerv3s/how_to_check_if_a_container_with_a_fixed_version](https://www.reddit.com/r/selfhosted/comments/1gerv3s/how_to_check_if_a_container_with_a_fixed_version)
 - RSS feed: $source
 - date published: 2024-10-29T11:03:36+00:00

<!-- SC_OFF --><div class="md"><p>I have quite a bunch of services running as docker containers. Many of them have dependent services that are containers fixed to a version (such as `postgres:15`, `redis:7`, `mariadb:lts`, `postgres:14-alpine`). So I have two questions:</p> <ol> <li>Many update apps and scripts (such as whatsupdocker or dockcheck) show updates for these. For example, what&#39;s up docker says `postgres:15` has an update to `17rc1-bullseye`. I think these are fixed for a reason and should not be updated. Am I correct on this assumption?</li> <li>Is there a way to check if these fixed versions are updated in the source compose file? It is not feasible to refetch and overwrite the file as all the custom changes will be lost. Is manually reading/diffing the source and the existing one the only option?</li> </ol> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/msoulforged"> /u/msoulforged </a> <br/> <span><a href="https://www.reddit.com/

## n8n Unlock 3 Pro features on self hosted version!
 - [https://www.reddit.com/r/selfhosted/comments/1gertri/n8n_unlock_3_pro_features_on_self_hosted_version](https://www.reddit.com/r/selfhosted/comments/1gertri/n8n_unlock_3_pro_features_on_self_hosted_version)
 - RSS feed: $source
 - date published: 2024-10-29T11:01:26+00:00

<!-- SC_OFF --><div class="md"><p>I came across a &quot;Time Limited Offer&quot; on n8n community edition (self hosted)</p> <ol> <li>Update to the latest version</li> <li>Settings &gt; Usage and plan &gt; click on the Unlock popup &gt; enter your email for your license key! (delivered to email)</li> </ol> <p>It Unlocks for life: &quot;Workflow history&quot;, &quot;Debug in editor&quot; and &quot;custom execution search&quot;</p> <p>Original Post: </p> <p><a href="https://www.reddit.com/r/n8n/comments/1gebud8/limited_time_claim_your_free_lifetime_n8n_license/">https://www.reddit.com/r/n8n/comments/1gebud8/limited_time_claim_your_free_lifetime_n8n_license/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/marvelOmy"> /u/marvelOmy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gertri/n8n_unlock_3_pro_features_on_self_hosted_version/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gert

## Metadata for collector editions
 - [https://www.reddit.com/r/selfhosted/comments/1gerhkq/metadata_for_collector_editions](https://www.reddit.com/r/selfhosted/comments/1gerhkq/metadata_for_collector_editions)
 - RSS feed: $source
 - date published: 2024-10-29T10:39:16+00:00

<!-- SC_OFF --><div class="md"><p>do you know of the existence of any service that provides metadata of collector editions of games? i would like to know the price of the edition at launch and what it contains. if there is a service that already does all these things even better</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Gjallarhorn__"> /u/Gjallarhorn__ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gerhkq/metadata_for_collector_editions/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gerhkq/metadata_for_collector_editions/">[comments]</a></span>

## Anyone using Podman play kube to self-host?
 - [https://www.reddit.com/r/selfhosted/comments/1gerc1d/anyone_using_podman_play_kube_to_selfhost](https://www.reddit.com/r/selfhosted/comments/1gerc1d/anyone_using_podman_play_kube_to_selfhost)
 - RSS feed: $source
 - date published: 2024-10-29T10:28:50+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m curious if anyone here is using Podman to self host their services and I want to share my experience.</p> <p>Personally, I&#39;m using <code>podman play kube</code> to launch my services. I have ~44 different pods running + all the other 44 infra containers deployed with them. I started with Podman 3.X and the development progress has been amazing. Although I understand that the <code>podman-kube-play</code> feature is more for a playground kind of scenario and not production but I found it to be quite convenient, for example, to deploy those service that need more than one container running like caches or DBs. Immich, Docmost, are some examples.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/contre95"> /u/contre95 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gerc1d/anyone_using_podman_play_kube_to_selfhost/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/self

## Simple and light server monitoring tool
 - [https://www.reddit.com/r/selfhosted/comments/1geqffz/simple_and_light_server_monitoring_tool](https://www.reddit.com/r/selfhosted/comments/1geqffz/simple_and_light_server_monitoring_tool)
 - RSS feed: $source
 - date published: 2024-10-29T09:24:20+00:00

<!-- SC_OFF --><div class="md"><p>Hello folks, I am looking for a simple (if possible already configured with the major variables) and light server monitoring tool for my small self-hosted set up. Preferably with Docker. Do you people have any advice ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Eirikr700"> /u/Eirikr700 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1geqffz/simple_and_light_server_monitoring_tool/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1geqffz/simple_and_light_server_monitoring_tool/">[comments]</a></span>

## Help setting up mini cluster for home
 - [https://www.reddit.com/r/selfhosted/comments/1gepxud/help_setting_up_mini_cluster_for_home](https://www.reddit.com/r/selfhosted/comments/1gepxud/help_setting_up_mini_cluster_for_home)
 - RSS feed: $source
 - date published: 2024-10-29T08:47:07+00:00

<!-- SC_OFF --><div class="md"><p>So i have 3 nodes and i want to setup simple cluster solution. I do not want to use a beast like kubernetes.</p> <p>I set up docker swarm and run services on three nodes. But i have questions as to how things should be setup for HA.</p> <p>I have running django project redis, celery and postgresql behind traefik. How should it be setup for failover how does it replicate stateful services on another node if one goes down?</p> <p>Could you briefly describe architecture of such cluster? I researched and found nomad. Would it be better then swarm to setup this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Spuxilet"> /u/Spuxilet </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gepxud/help_setting_up_mini_cluster_for_home/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gepxud/help_setting_up_mini_cluster_for_home/">[comments]</a></span>

## sv1sjp/NextCloudTalkAutomationBot: A powerful and flexible bot for sending system notifications through messages via Nextcloud Talk.
 - [https://www.reddit.com/r/selfhosted/comments/1gepw8l/sv1sjpnextcloudtalkautomationbot_a_powerful_and](https://www.reddit.com/r/selfhosted/comments/1gepw8l/sv1sjpnextcloudtalkautomationbot_a_powerful_and)
 - RSS feed: $source
 - date published: 2024-10-29T08:43:42+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gepw8l/sv1sjpnextcloudtalkautomationbot_a_powerful_and/"> <img src="https://external-preview.redd.it/lKmC6PF8Ck3PJS5cD56Z5YP68f1CDEdpN8b5Xn5OFpM.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=5cdeb01e3edc50518cf4eb0c3ad5dfa636d9227b" alt="sv1sjp/NextCloudTalkAutomationBot: A powerful and flexible bot for sending system notifications through messages via Nextcloud Talk." title="sv1sjp/NextCloudTalkAutomationBot: A powerful and flexible bot for sending system notifications through messages via Nextcloud Talk." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sv1sjp"> /u/sv1sjp </a> <br/> <span><a href="https://github.com/sv1sjp/NextCloudTalkAutomationBot">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gepw8l/sv1sjpnextcloudtalkautomationbot_a_powerful_and/">[comments]</a></span> </td></tr></table>

## Tunnel for Selfhosted App
 - [https://www.reddit.com/r/selfhosted/comments/1gep2ou/tunnel_for_selfhosted_app](https://www.reddit.com/r/selfhosted/comments/1gep2ou/tunnel_for_selfhosted_app)
 - RSS feed: $source
 - date published: 2024-10-29T07:38:28+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I want to know is there any way to access my Selfhosted apps from outside of the house using vanilla wireguard vpn? I can access my apps using tailscale, but using wireguard I can&#39;t access.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Kaziopu123"> /u/Kaziopu123 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gep2ou/tunnel_for_selfhosted_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gep2ou/tunnel_for_selfhosted_app/">[comments]</a></span>

## Advanced secure exposing
 - [https://www.reddit.com/r/selfhosted/comments/1geoq1u/advanced_secure_exposing](https://www.reddit.com/r/selfhosted/comments/1geoq1u/advanced_secure_exposing)
 - RSS feed: $source
 - date published: 2024-10-29T07:10:45+00:00

<!-- SC_OFF --><div class="md"><p>Hi</p> <p>I have a pretty big selfhosting stack, with Tailscale for the critical things etc.</p> <p>Currently I have nothing exposed publicly, own a Cloudflare domain and use nginxreverseproxy together with authentik to have everything behind sso or oauth.</p> <p>I plan on exposing some thing like grafana jellyfin, etc. and keep things like apache guacamole opnsense, proxmox behind VPN only.</p> <p>What would be the best/most secure way of having such a stack open to the public?</p> <p>NginxReverseProxy is running inside a LXC and Pihole as internal DNS as well.</p> <p>in theory opening/forwarding port 443 of nginxreverseproxy would be all, but I guess that won&#39;t be that safe?</p> <p>I tought about running fail2ban and crowsed, but should I run them as seperate LXC, is that even possible or in the same LXC as reverseproxy, preferably option 1.</p> <p>I&#39;ll definitely consider cloudflare side locking down for country specific and captchas, but 

## Free VPS for radio. Also Proxmox VPS?
 - [https://www.reddit.com/r/selfhosted/comments/1genw16/free_vps_for_radio_also_proxmox_vps](https://www.reddit.com/r/selfhosted/comments/1genw16/free_vps_for_radio_also_proxmox_vps)
 - RSS feed: $source
 - date published: 2024-10-29T06:05:50+00:00

<!-- SC_OFF --><div class="md"><p>I am wondering if anyone knows of a free VPS that is capable of hosting a Rdio Scanner and Icecast2 server, essentially internet radio. I am hosting a local police scanner server but I would like to host it on a VPS if it’s possible. As I am just testing things out I am looking for a free VPS that can handle it. If free isn’t an option then the lowest cost option would be appreciated. Idk if Oracle free would work for this use case or not. </p> <p>Also I am wondering if running Proxmox on a VPS is a thing? I am mainly wondering because it would be super convenient to backup to PBS and then be able to easily restore on any VPS. This seems much better than the backup service offered by host at a decent fee and I doubt restoring to another VPS would be as easy.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Agreeable_Repeat_568"> /u/Agreeable_Repeat_568 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted

## Exploring Serverless Solutions for Whisper V3 Turbo Integration
 - [https://www.reddit.com/r/selfhosted/comments/1genda5/exploring_serverless_solutions_for_whisper_v3](https://www.reddit.com/r/selfhosted/comments/1genda5/exploring_serverless_solutions_for_whisper_v3)
 - RSS feed: $source
 - date published: 2024-10-29T05:29:19+00:00

<!-- SC_OFF --><div class="md"><p>Currently, the serverless solution from Runpod meets my needs in terms of cost and features: <a href="https://github.com/runpod-workers/worker-faster_whisper">https://github.com/runpod-workers/worker-faster_whisper</a></p> <p>However, I&#39;m interested in using <a href="https://huggingface.co/openai/whisper-large-v3-turbo">https://huggingface.co/openai/whisper-large-v3-turbo</a> due to its reported speed.</p> <p>I&#39;m uncertain about how to set up and run Whisper V3 Turbo on Runpod’s serverless infrastructure. </p> <p>It seems we might need to wait until the upstream project <a href="https://github.com/SYSTRAN/faster-whisper/issues/1030">https://github.com/SYSTRAN/faster-whisper/issues/1030</a> is updated with Turbo and published on <a href="https://pypi.org/project/faster-whisper/">https://pypi.org/project/faster-whisper/</a>. </p> <p>Only then will this feature be available, and at that point, we could fork <a href="https://github.com/runpod-wor

## Need help with resolving remote error: tls: unrecognized name
 - [https://www.reddit.com/r/selfhosted/comments/1gen69l/need_help_with_resolving_remote_error_tls](https://www.reddit.com/r/selfhosted/comments/1gen69l/need_help_with_resolving_remote_error_tls)
 - RSS feed: $source
 - date published: 2024-10-29T05:16:03+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>setting up a Argo CD on my Kubernetes cluster locally. I followed these steps <a href="https://argo-cd.readthedocs.io/en/stable/getting_started/">https://argo-cd.readthedocs.io/en/stable/getting_started/</a> except creating my own certificate.</p> <p>Few days ago I was able to add a GitHub repository without any issues and connection to the repo was successful (with my login and personal access token since it&#39;s a private repo). I setup an application to auto deploy my nextjs web app and verified everything working fine.</p> <p>Since yesterday the repository status stays failed and I am not sure what happened. I couldn&#39;t connect to any repository, public or private. It keeps throwing same error - <code>remote error: tls: unrecognized name</code></p> <p>Right now, I even removed all resources from the cluster and reinstalled Argo to make sure if I messed up but I still face the issue.</p> <pre><code>❯ argocd repo add https://gith

## Self-hosted app stack
 - [https://www.reddit.com/r/selfhosted/comments/1gelulg/selfhosted_app_stack](https://www.reddit.com/r/selfhosted/comments/1gelulg/selfhosted_app_stack)
 - RSS feed: $source
 - date published: 2024-10-29T03:54:03+00:00

<!-- SC_OFF --><div class="md"><p>Ok, so the accomplishment of this stack should be abundantly apparent, but I’m building a self-hosted stack for my startup, and I’m planning on running Nginx as a reverse proxy, MeshCentral, Odoo, and Zammad as my app stack in Proxmox, with a separate PBS server for snapshot, VM and bare metal backups. Thing is, I’m new to the self-hosted open-source game so I just wanted to check here if I should be looking at different solutions, or if this is actually a good way to go. Doesn’t have to be the best, I just don’t want the worst. </p> <p>I have multiple years experience working with industry standard canned or off-the-shelf versions of these apps. They all suck and I hate paying them for minimized control and maximized marketing. Go away. </p> <p>Edit to add: Unrelated, but if anyone has a decent open-source alternative to Discord and/or MS Teams, me and my friends would appreciate it!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https:/

## Looking for an outage report solution
 - [https://www.reddit.com/r/selfhosted/comments/1gel21i/looking_for_an_outage_report_solution](https://www.reddit.com/r/selfhosted/comments/1gel21i/looking_for_an_outage_report_solution)
 - RSS feed: $source
 - date published: 2024-10-29T03:10:44+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a way to monitor services and hardware, with the ability to generate detailed monthly or quarterly reports. I have tried searching this sub and others looking for something like this, most just recommend kuma, but it doesn&#39;t have the reporting features i&#39;m looking for. Any ideas?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/XmaathimselfX"> /u/XmaathimselfX </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gel21i/looking_for_an_outage_report_solution/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gel21i/looking_for_an_outage_report_solution/">[comments]</a></span>

## How to tunnel ufw rules through nftables
 - [https://www.reddit.com/r/selfhosted/comments/1gek9ut/how_to_tunnel_ufw_rules_through_nftables](https://www.reddit.com/r/selfhosted/comments/1gek9ut/how_to_tunnel_ufw_rules_through_nftables)
 - RSS feed: $source
 - date published: 2024-10-29T02:28:57+00:00

<!-- SC_OFF --><div class="md"><p>Hello all, I&#39;m a total newbie regarding hosting and Linux. I&#39;m using a program called termius to connect to my ssh on VPSs. I authed only key login and changed my port to sth else rather than 22 already. My ufw is set to dent all incoming beside 2 ports and default all outgoing. Now, I&#39;m trying to use sshguard to block any intruders on ports 22 and my actual ssh port. However, I couldn&#39;t get ufw to use nftables for the rules. </p> <p>I&#39;m able to set everything up for iptables but I can&#39;t use that with ufw because if I don&#39;t allow iptables persistent, the rules are not there after a reboot. If I use that service, then I&#39;m unable to use ufw.</p> <p>My aim is to get ufw to connect to nftables so iptables doesn&#39;t give me any errors while setting up ssh guard. </p> <p>What am I doing wrong? Thank you in advance!</p> <p>PS: this is the <a href="https://linuxiac.com/how-to-secure-ssh-server-with-sshguard/">guide</a> I&#39

## hashtag search in memos never returns anything
 - [https://www.reddit.com/r/selfhosted/comments/1gek7yj/hashtag_search_in_memos_never_returns_anything](https://www.reddit.com/r/selfhosted/comments/1gek7yj/hashtag_search_in_memos_never_returns_anything)
 - RSS feed: $source
 - date published: 2024-10-29T02:26:17+00:00

<!-- SC_OFF --><div class="md"><p>Love the app. <a href="https://www.usememos.com/">https://www.usememos.com/</a> But none of my hash tags can be found later. If I search, it just shows a spinning wheel. I&#39;m using a separate hosted mysql instance, and everything appears to be working fine other than the search</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/activ8xp"> /u/activ8xp </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gek7yj/hashtag_search_in_memos_never_returns_anything/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gek7yj/hashtag_search_in_memos_never_returns_anything/">[comments]</a></span>

## Can't access Navidrome via Tailscale on TrueNAS Scale
 - [https://www.reddit.com/r/selfhosted/comments/1gejy4d/cant_access_navidrome_via_tailscale_on_truenas](https://www.reddit.com/r/selfhosted/comments/1gejy4d/cant_access_navidrome_via_tailscale_on_truenas)
 - RSS feed: $source
 - date published: 2024-10-29T02:12:16+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I have been troubleshooting for three days at this point. </p> <p>My TrueNAS has Navidrome and Tailscale on as containers. Tailscale is showing that the TrueNAS is up on its network, and I am able to access the GUI from a remote network (that is part of Tailscale). So TrueNAS is accepting connections from Tailscale-networked devices. However, when I enter the same IP address + the port number for Navidrome, I get various error messages (Firefox: &quot;Unable to connect, Firefox can’t establish a connection to the server at 100.x.x.x:xx&quot;). Navidrome is operational on my local network, but not Tailscale-connections.</p> <p>I think that the issue is in the Navidrome configuration, but I can&#39;t get that granular through the TrueNAS GUI. I have been poking around the CLI to try and find some config file for Navidrome to see if it&#39;s bound to a single IP, but I can&#39;t find anything of the sort. </p> <p>Can anyone tell me how th

## Self-hosted Vaultwarden instance setup with Cloudflare Tunnel gets a lot of public traffic..
 - [https://www.reddit.com/r/selfhosted/comments/1geiqgu/selfhosted_vaultwarden_instance_setup_with](https://www.reddit.com/r/selfhosted/comments/1geiqgu/selfhosted_vaultwarden_instance_setup_with)
 - RSS feed: $source
 - date published: 2024-10-29T01:12:18+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1geiqgu/selfhosted_vaultwarden_instance_setup_with/"> <img src="https://b.thumbs.redditmedia.com/xTK1eyjlHp5NAyMCEshcVyLsCI-gZoP3DRB08hTfGlY.jpg" alt="Self-hosted Vaultwarden instance setup with Cloudflare Tunnel gets a lot of public traffic.." title="Self-hosted Vaultwarden instance setup with Cloudflare Tunnel gets a lot of public traffic.." /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I am self-hosting my Vaultwarden instance and have it setup with a Cloudflare Tunnel so I can access it remotely, which of course means it is public facing.</p> <p>I get an uncomfortable amount of traffic to the domain name I have setup for it, at least for me:</p> <p><a href="https://preview.redd.it/pbmuy62xhlxd1.png?width=2448&amp;format=png&amp;auto=webp&amp;s=f2108a9831769e7466c4ee19dcd538dc293661ae">https://preview.redd.it/pbmuy62xhlxd1.png?width=2448&amp;format=png&amp;auto=webp&amp;s=f2108a9831769e7466c4ee19dcd538dc2

## Anyone know IPTables? I think ive locked myself out...
 - [https://www.reddit.com/r/selfhosted/comments/1geile0/anyone_know_iptables_i_think_ive_locked_myself_out](https://www.reddit.com/r/selfhosted/comments/1geile0/anyone_know_iptables_i_think_ive_locked_myself_out)
 - RSS feed: $source
 - date published: 2024-10-29T01:05:17+00:00

<!-- SC_OFF --><div class="md"><p>I am seeking the elders of selfhosted. I seem to have blocked my lan from accessing my server. One minute I&#39;m learning something new about systemctl sockets, and BAM! completely blocked. It may have something to do with <a href="https://medium.com/@kiankasad/start-docker-containers-on-demand-with-systemd-socket-activation-548f3b8d2514">this tutorial</a> I was following to start docker containers on demand, or my fail2ban container may have decided to ignore the ignoreips list. I&#39;m not completely sure. All I know is I can access my server remotely and on my <a href="http://10.0.0.0/8">10.0.0.0/8</a> range, but not on my <a href="http://192.168.0.0/16">192.168.0.0/16</a> (My LAN range). Here is what I have debugged so far: </p> <p>I ran tcpdump to confirm that traffic is correctly entering the VM hosting the server. I was able to confirm that its not something exterior. Here is a snippet of that inside the VM. </p> <p><code>listening on ens19, 

