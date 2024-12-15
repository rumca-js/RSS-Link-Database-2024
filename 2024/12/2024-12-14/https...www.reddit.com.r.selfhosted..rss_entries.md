# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Dockge development abandoned?
 - [https://www.reddit.com/r/selfhosted/comments/1hee1h6/dockge_development_abandoned](https://www.reddit.com/r/selfhosted/comments/1hee1h6/dockge_development_abandoned)
 - RSS feed: $source
 - date published: 2024-12-14T22:17:18+00:00

<!-- SC_OFF --><div class="md"><p>is the project abandoned? I do see some PRs merged by louislam but they were like 2-3 months ago. There are tons of PRs of bug fixes and features that I would like to see in dockge but there has been no update for like a long time now.</p> <p>the latest release on github was on Jan 21 2024</p> <p><a href="https://github.com/louislam/dockge/releases">https://github.com/louislam/dockge/releases</a></p> <p>and latest image from dockerhub was 2 months ago</p> <p><a href="https://hub.docker.com/r/louislam/dockge">https://hub.docker.com/r/louislam/dockge</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ExcitementTall794"> /u/ExcitementTall794 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hee1h6/dockge_development_abandoned/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hee1h6/dockge_development_abandoned/">[comments]</a></span>

## Easiest way to change IP Addresses for full *arr stack?
 - [https://www.reddit.com/r/selfhosted/comments/1hedz0v/easiest_way_to_change_ip_addresses_for_full_arr](https://www.reddit.com/r/selfhosted/comments/1hedz0v/easiest_way_to_change_ip_addresses_for_full_arr)
 - RSS feed: $source
 - date published: 2024-12-14T22:14:06+00:00

<!-- SC_OFF --><div class="md"><p>I have my *arrs running in docker containers and all the interconnections are done with IP Addresses.</p> <p>I want to setup a secondary server in a different location, but don&#39;t want to have to manually set everything up again. And because I&#39;m using tailscale to access them remotely, they both can&#39;t use the same subnet range.</p> <p>So what is the easiest way to change the IP addresses for all the *arrs?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RathdrumRip"> /u/RathdrumRip </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hedz0v/easiest_way_to_change_ip_addresses_for_full_arr/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hedz0v/easiest_way_to_change_ip_addresses_for_full_arr/">[comments]</a></span>

## Alternative photo server to Synology photo
 - [https://www.reddit.com/r/selfhosted/comments/1hedlfa/alternative_photo_server_to_synology_photo](https://www.reddit.com/r/selfhosted/comments/1hedlfa/alternative_photo_server_to_synology_photo)
 - RSS feed: $source
 - date published: 2024-12-14T21:56:34+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a media server with iOS/Android app that supports offline download automatically. I have phones and tablets with too much storage and I want to get all media downloaded automatically to the mobile app so I can have a faster mobile experience and an extra backup of the photos.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/homelab2946"> /u/homelab2946 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hedlfa/alternative_photo_server_to_synology_photo/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hedlfa/alternative_photo_server_to_synology_photo/">[comments]</a></span>

## Watchtower on docker socket proxy
 - [https://www.reddit.com/r/selfhosted/comments/1hed6lj/watchtower_on_docker_socket_proxy](https://www.reddit.com/r/selfhosted/comments/1hed6lj/watchtower_on_docker_socket_proxy)
 - RSS feed: $source
 - date published: 2024-12-14T21:37:28+00:00

<!-- SC_OFF --><div class="md"><p>I have recently added <a href="https://github.com/Tecnativa/docker-socket-proxy">docker socket proxy</a> to my setup to be able to control what parts of the socket containers can access. While I&#39;ve managed to get it running with most of my containers, Watchtower (which used to work fine) keeps acting up: it scans all containers, finds updates, but fails to apply them. I keep getting this error message via e-mail notification:</p> <p><code> Unable to update container &quot;&lt;container-name&gt;&quot;: Error response from daemon: &lt;html&gt;&lt;body&gt;&lt;h1&gt;403 Forbidden&lt;/h1&gt; Request forbidden by administrative rules. &lt;/body&gt;&lt;/html&gt;. Proceeding to next. </code></p> <p>I&#39;m not exactly sure where the problem lies, i.e. whether I have a (non-docker-related) permissions issue, or whether I have misconfigured the socket proxy and watchtower needs a permission I&#39;m not aware of. I am attaching my docker-compose.yml file an

## Dozzle v8.9.0 released -- added support for user scope filters
 - [https://www.reddit.com/r/selfhosted/comments/1hecm69/dozzle_v890_released_added_support_for_user_scope](https://www.reddit.com/r/selfhosted/comments/1hecm69/dozzle_v890_released_added_support_for_user_scope)
 - RSS feed: $source
 - date published: 2024-12-14T21:10:53+00:00

<!-- SC_OFF --><div class="md"><p>Hello! Creator of Dozzle here. Dozzle is a log viewer for Docker that supports remote agents, swarm mode and multiple hosts. </p> <p>A common ask has been to support user specific scope, which allows granular control over container filters per user. I have added this in v8.9. Documentation has been updated on <a href="https://dozzle.dev/guide/authentication#setting-specific-filters-for-users">auth help pages</a>. Here is an example: </p> <p><code>users:</code><br/> <code>admin: name: Admin</code><br/> <code>password: $2a$11$9ho4vY2LdJ/WBopFcsAS0uORC0x2vuFHQgT/yBqZyzclhHsoaIkzK</code><br/> <code>filter:</code> </p> <p><code>guest: name: Guest</code><br/> <code>password: $2a$11$9ho4vY2LdJ/WBopFcsAS0uORC0x2vuFHQgT/yBqZyzclhHsoaIkzK</code><br/> <code>filter: &quot;label=com.example.app&quot;</code></p> <p>Enjoy 🚀 And thank you for all the ❤️ from this community. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/amir2

## What is the best modern self hosted identity provider ? with typescript support.
 - [https://www.reddit.com/r/selfhosted/comments/1hebx8w/what_is_the_best_modern_self_hosted_identity](https://www.reddit.com/r/selfhosted/comments/1hebx8w/what_is_the_best_modern_self_hosted_identity)
 - RSS feed: $source
 - date published: 2024-12-14T20:38:47+00:00

<!-- SC_OFF --><div class="md"><p>I have seen these options but really need an opinion on that, share your experiences with them or if there is something better.</p> <p><strong>Authentik -</strong> <a href="https://goauthentik.io/">https://goauthentik.io/</a></p> <p><strong>Zitadel</strong> - <a href="https://zitadel.com/">https://zitadel.com/</a></p> <p><strong>Keycloak</strong> - <a href="https://www.keycloak.org/">https://www.keycloak.org/</a></p> <p><strong>FusionAuth</strong> - <a href="https://fusionauth.io/">https://fusionauth.io/</a></p> <p><strong>Authelia</strong> - <a href="https://www.authelia.com/">https://www.authelia.com/</a></p> <p>ORY - <a href="https://www.ory.sh/hydra/">https://www.ory.sh/hydra/</a></p> <p>Gluu - <a href="https://gluu.org/">https://gluu.org/</a></p> <p>Logto - <a href="https://docs.logto.io/introduction">https://docs.logto.io/introduction</a><br/> <strong>low :</strong></p> <p>Supertokens - <a href="https://supertokens.com">https://supertokens.com<

## Guide on Proxmox DHCP deployment for a single node
 - [https://www.reddit.com/r/selfhosted/comments/1healy6/guide_on_proxmox_dhcp_deployment_for_a_single_node](https://www.reddit.com/r/selfhosted/comments/1healy6/guide_on_proxmox_dhcp_deployment_for_a_single_node)
 - RSS feed: $source
 - date published: 2024-12-14T19:38:29+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/esiy0676"> /u/esiy0676 </a> <br/> <span><a href="https://www.reddit.com/r/ProxmoxQA/comments/1heakn5/dhcp_deployment_for_a_single_node/?utm_source=share&amp;utm_medium=web3x&amp;utm_name=web3xcss&amp;utm_term=1&amp;utm_content=share_button">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1healy6/guide_on_proxmox_dhcp_deployment_for_a_single_node/">[comments]</a></span>

## How to resolve TLD in LAN differently depending on whether you're connected to Tailscale
 - [https://www.reddit.com/r/selfhosted/comments/1heajlw/how_to_resolve_tld_in_lan_differently_depending](https://www.reddit.com/r/selfhosted/comments/1heajlw/how_to_resolve_tld_in_lan_differently_depending)
 - RSS feed: $source
 - date published: 2024-12-14T19:35:34+00:00

<!-- SC_OFF --><div class="md"><p>TL;DR: I want to use a single domain name to access my local services from both my LAN and Tailscale network, with optimal IP resolution based on the current network connection. </p> <p>Hi everyone,</p> <p>I have a machine on my LAN hosting a few services with Docker. That same machine also hosts AdGuard Home. On the same LAN, there&#39;s also a RaspberryPi hosting PiHole (I&#39;ll probably standardise on AGH but I&#39;m still testing both). Both machines have Tailscale installed.</p> <p>The services are accessible both from within my LAN using the LAN IP, and tailnet using the machine name.</p> <p>I would like to be able to access the services using a domain name (TLD) I own, both from within my LAN and over tailnet.</p> <p>I can already use the TLD from within my LAN, as I added an A record for the main machine on the DNS servers, and CNAME records for the services pointing to the main machine name.</p> <p>Now I would like to also use the TLD when 

## Newbie here, bought a domain using Google Workspace, now how do I access. I don't even know If I own the domain or not, should I use GoDaddy or any other registrar.
 - [https://www.reddit.com/r/selfhosted/comments/1he9p2o/newbie_here_bought_a_domain_using_google](https://www.reddit.com/r/selfhosted/comments/1he9p2o/newbie_here_bought_a_domain_using_google)
 - RSS feed: $source
 - date published: 2024-12-14T18:57:22+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1he9p2o/newbie_here_bought_a_domain_using_google/"> <img src="https://b.thumbs.redditmedia.com/dftboYEOqGS0ukTkzXw3t_PRBfMMSBtP-apcpbjvthU.jpg" alt="Newbie here, bought a domain using Google Workspace, now how do I access. I don't even know If I own the domain or not, should I use GoDaddy or any other registrar." title="Newbie here, bought a domain using Google Workspace, now how do I access. I don't even know If I own the domain or not, should I use GoDaddy or any other registrar." /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Same as title. Help out please. Wanted to buy domain for my fashion brand. </p> <p>It says &quot;Since 14 dec 2024 with Squarespace Domains&quot; but how do I access it or verify it?</p> <p>In my admin.google.com page it says &quot;Domain registration is pending&quot; and when I go for billing, here I see this page. Saying that I&#39;ve already bought the domain.</p> <p>When I do try 

## Automatically sorting and saving e-mail pdf attachments: Paperless-ngx?
 - [https://www.reddit.com/r/selfhosted/comments/1he9czl/automatically_sorting_and_saving_email_pdf](https://www.reddit.com/r/selfhosted/comments/1he9czl/automatically_sorting_and_saving_email_pdf)
 - RSS feed: $source
 - date published: 2024-12-14T18:41:44+00:00

<!-- SC_OFF --><div class="md"><p>Hello, we&#39;re a very small company and have an email address like &quot;<a href="mailto:invoice@company.tld">invoice@company.tld</a>&quot;. All our business partners send their invoices to that address. 99% of them are in pdf format. We manually save those pdfs to a directory structure on our NAS. That&#39;s tedious.</p> <p>I want to automate that. Ideally I want to save the pdfs to 2-3 different directories on our NAS. Is Paperless-ngx the right tool for the job? Or is there something else/better? I&#39;m not really planning on using the Paperless-ngx webinterface all that much.</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/extractedx"> /u/extractedx </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1he9czl/automatically_sorting_and_saving_email_pdf/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1he9czl/automatically_sorting_and_sav

## Restic -> Access is denied when trying to restore
 - [https://www.reddit.com/r/selfhosted/comments/1he8dsz/restic_access_is_denied_when_trying_to_restore](https://www.reddit.com/r/selfhosted/comments/1he8dsz/restic_access_is_denied_when_trying_to_restore)
 - RSS feed: $source
 - date published: 2024-12-14T17:56:20+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1he8dsz/restic_access_is_denied_when_trying_to_restore/"> <img src="https://a.thumbs.redditmedia.com/jF0o0eh_md5xPsFve-Iy3sw-3O6RpMMD33bAPgF0yS4.jpg" alt="Restic -&gt; Access is denied when trying to restore" title="Restic -&gt; Access is denied when trying to restore" /> </a> </td><td> <!-- SC_OFF --><div class="md"><pre><code>restic -r D:/testitout restore latest --target D:/testsnapshot enter password for repository: repository d758ddd3 opened (version 2, compression level auto) [0:00] 100.00% 2 / 2 index files loaded restoring snapshot ab0fe301 of [Z:\test_folder] at 2024-12-14 12:41:05.0818332 -0500 EST by GAMING_PC_KEV\mrkev@Gaming_PC_Kev to D:/testsnapshot ignoring error for \Z\test_folder\test.txt: UtimesNano: Access is denied. ignoring error for \Z\test_folder: UtimesNano: Access is denied. Summary: Restored 2 / 3 files/dirs (46 B / 46 B) in 0:00 Fatal: There were 2 errors </code></pre> <p>Please see abov

## Help installing crowdsec with existing NPM docker running
 - [https://www.reddit.com/r/selfhosted/comments/1he80oa/help_installing_crowdsec_with_existing_npm_docker](https://www.reddit.com/r/selfhosted/comments/1he80oa/help_installing_crowdsec_with_existing_npm_docker)
 - RSS feed: $source
 - date published: 2024-12-14T17:39:17+00:00

<!-- SC_OFF --><div class="md"><p>I am running the latest version of Ubuntu Server OS and I am running NPM through docker. All the documentation and videos I saw on installation install NPM and Crowdsec at the same time. Already having NPM set up is causing me confusion (still pretty new to all this). I asked ChatGPT and it just confused me more. </p> <p>Can someone help me or point me in the right direction so I can install Crowdsec and NPM bouncer?</p> <p>Thanks in advance. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/iamwhoiwasnow"> /u/iamwhoiwasnow </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1he80oa/help_installing_crowdsec_with_existing_npm_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1he80oa/help_installing_crowdsec_with_existing_npm_docker/">[comments]</a></span>

## Help me Selfhost - Google Photos (Immich)
 - [https://www.reddit.com/r/selfhosted/comments/1he7z0g/help_me_selfhost_google_photos_immich](https://www.reddit.com/r/selfhosted/comments/1he7z0g/help_me_selfhost_google_photos_immich)
 - RSS feed: $source
 - date published: 2024-12-14T17:37:11+00:00

<!-- SC_OFF --><div class="md"><p>Howdy All!</p> <p>I&#39;ve been using Immich for about a year now side-by-side with Google Photos, and I&#39;m looking to finally make the final move. I&#39;m looking some advice on best setups and OS/Software to use (see below).</p> <p>Hardware:<br/> - N100 Mini PC<br/> - 6x10TB HDD&#39;s<br/> - Lenovo IX4-300D NAS<br/> - 4 Bay DAS Box (JBOD via USB)</p> <p>I have more than 10, less than 20, TB of data right now. </p> <p>At the minute I was roughly planning on:</p> <p>- Installing TrueNAS Core on the Mini PC<br/> - Installing Immich on the TrueNAS Core<br/> - Attaching the DAS and running them in software RAID5</p> <p>I&#39;m aware that TrueNAS doesn&#39;t recommend USB attached devices, is this really a dealbreaker here? If so, any alternative suggestions?</p> <p>On the other side, I was planning on having the same RAID5 setup on the Lenovo, and using it as an off-site backup (in my garage which is detached). </p> <p>I also know RAID5 has generally

## Finally my 3-2-1 Backup is going to be ready!!!
 - [https://www.reddit.com/r/selfhosted/comments/1he7qro/finally_my_321_backup_is_going_to_be_ready](https://www.reddit.com/r/selfhosted/comments/1he7qro/finally_my_321_backup_is_going_to_be_ready)
 - RSS feed: $source
 - date published: 2024-12-14T17:26:16+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1he7qro/finally_my_321_backup_is_going_to_be_ready/"> <img src="https://a.thumbs.redditmedia.com/Y_ldpOjOf-UVZWoonxgEX714nAeeGOC0dkmU82zcUB0.jpg" alt="Finally my 3-2-1 Backup is going to be ready!!!" title="Finally my 3-2-1 Backup is going to be ready!!!" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I am very exited. I have been playing around with my Selfhosted apps for a year and finally setting up cloud storage for my Immich. I can sleep peacefully hereafter. </p> <p><a href="https://preview.redd.it/1dprmevclu6e1.png?width=2559&amp;format=png&amp;auto=webp&amp;s=1491412dbbd5f8858b2fb23910b27e47fd644668">https://preview.redd.it/1dprmevclu6e1.png?width=2559&amp;format=png&amp;auto=webp&amp;s=1491412dbbd5f8858b2fb23910b27e47fd644668</a></p> <p><a href="https://preview.redd.it/2w0mspz1mu6e1.png?width=1647&amp;format=png&amp;auto=webp&amp;s=350df966cf7b6cdd95a467eb45155fb146ab1fb2">https://preview.redd.it/2w0

## Logdy - terminal logs with web browser UI. v0.14 now with semantic filtering
 - [https://www.reddit.com/r/selfhosted/comments/1he7job/logdy_terminal_logs_with_web_browser_ui_v014_now](https://www.reddit.com/r/selfhosted/comments/1he7job/logdy_terminal_logs_with_web_browser_ui_v014_now)
 - RSS feed: $source
 - date published: 2024-12-14T17:16:54+00:00

<!-- SC_OFF --><div class="md"><p>Hi reddit, almost a year ago I started my first OSS project, yesterday I released a 14th major update!</p> <p><a href="https://github.com/logdyhq/logdy-core">Logdy</a> is a web-based platform designed to help developers monitor, track, and analyze application logs in real-time locally. Logdy is a single-binary that you add to your PATH so it&#39;s available just like any other tool: grep, awk, sed, jq. No installations, no deployments, no compilations. It works locally, so it&#39;s also secure.</p> <p>With the <a href="https://logdy.dev/blog/post/logdy-new-version-announcement-v014">latest release Logdy</a> has landed 2 significant features (among others).</p> <p>Semantic filtering - It uses Breser (<a href="https://breser.dev">https://breser.dev</a> - simple expression syntax for filtering structured data) to filter through logs.</p> <p>Timeframe picker - Allows you to limit log entries by time.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a h

## Good CDN
 - [https://www.reddit.com/r/selfhosted/comments/1he7ifz/good_cdn](https://www.reddit.com/r/selfhosted/comments/1he7ifz/good_cdn)
 - RSS feed: $source
 - date published: 2024-12-14T17:15:16+00:00

<!-- SC_OFF --><div class="md"><p>So, I have considered using cloudflare but I heard some terrible stories about then...</p> <p>I&#39;m looking for an honest CDN with simple PAYG pricing, must be under 0.01$/gb.</p> <p>Any recommendations?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LeftAssociation1119"> /u/LeftAssociation1119 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1he7ifz/good_cdn/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1he7ifz/good_cdn/">[comments]</a></span>

## Reverse Proxy Impact on Speed and ISP Bandwidth Usage?
 - [https://www.reddit.com/r/selfhosted/comments/1he75m1/reverse_proxy_impact_on_speed_and_isp_bandwidth](https://www.reddit.com/r/selfhosted/comments/1he75m1/reverse_proxy_impact_on_speed_and_isp_bandwidth)
 - RSS feed: $source
 - date published: 2024-12-14T16:59:02+00:00

<!-- SC_OFF --><div class="md"><p>Newbie thought/question.</p> <p>I finally got Reverse Proxy, Dynamic DNS, and https certificates figured out, using NGinx Proxy Manager and Duck DNS. The setup is working nicely, or seems to be. I can access my various servers and their services via subdomain URLs with https, whether at home or elsewhere.</p> <p>I got a warning from my ISP over bandwidth usage, which isn&#39;t surprising given some of the downloading I&#39;ve done over the past few weeks. It occurred to me though, how does this really work? Here&#39;s what I mean.</p> <p>Let&#39;s say I have an Emby server, which is accessible at home directly through it&#39;s local IP address. It&#39;s also with my setup accessible through the subdomain hosted on DuckDNS. If I&#39;m at home, and I access the server using the subdomain address, is my traffic going out of my home network, only to come back, thus impacting my bandwidth usage/speed? I could see if it is it&#39;s actually counting agains

## Software suggestions for Wedding (planning and day)
 - [https://www.reddit.com/r/selfhosted/comments/1he7572/software_suggestions_for_wedding_planning_and_day](https://www.reddit.com/r/selfhosted/comments/1he7572/software_suggestions_for_wedding_planning_and_day)
 - RSS feed: $source
 - date published: 2024-12-14T16:58:28+00:00

<!-- SC_OFF --><div class="md"><p>Hello all,</p> <p>I&#39;m getting married next year, and like any 20-something year old, I&#39;m trying to do it on the cheap! </p> <p>I figure one way to do that is to utilise my self-hosting abilities to host things like: - Save the date and Invites (nice websites, with a response form) - a photo portal to easily allow people to dump all photos from the day. - Song suggestions? - Wedding planning software - Other things I haven&#39;t thought of yet</p> <p>Before I dive deep into github repo&#39;s and Google searches, I figured I should ask this lovely community for suggestions and things maybe they used for their own weddings.</p> <p>Thanks! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Yummy_XD"> /u/Yummy_XD </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1he7572/software_suggestions_for_wedding_planning_and_day/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfho

## Proxmox als Homeserver für Nextcloud, Immich, Paperless…
 - [https://www.reddit.com/r/selfhosted/comments/1he717a/proxmox_als_homeserver_für_nextcloud_immich](https://www.reddit.com/r/selfhosted/comments/1he717a/proxmox_als_homeserver_für_nextcloud_immich)
 - RSS feed: $source
 - date published: 2024-12-14T16:53:03+00:00

<!-- SC_OFF --><div class="md"><p>Hey Leute,</p> <p>ich hab mir einen Terramaster F6-424 Max gekauft und will den als Homeserver einrichten. Aber ich will das Betriebssystem von Terramaster (TOS6) nicht nutzen, sondern direkt Proxmox drauf installieren. Jetzt steh ich da und weiß nicht genau, wie ich das am besten umsetze.</p> <p>Ich hab zwei 1TB NVMe-SSDs eingebaut, die ich im RAID1 laufen lassen will. Die sollen nur für Proxmox und die ganzen Dienste sein, die ich drauf installieren will. Für die Daten hab ich noch zwei 12TB-HDDs (ebenfalls RAID1), und darauf soll wirklich alles gespeichert werden, was ich so benutze.</p> <p>Mein Ziel ist, dass ich auf alle Daten zentral zugreifen kann – egal ob über Nextcloud, Immich, Plex oder sonst was. Alles soll auf den gleichen Datenbestand zugreifen, damit nix doppelt irgendwo landet. Ich stell mir vor, dass es einen Hauptordner namens “Daten” gibt, und darin dann Unterordner wie „Fotos“, „Videos“, „Musik“, „Dokumente“, „Backups“. Auf diese 

## Advice for file sharing services
 - [https://www.reddit.com/r/selfhosted/comments/1he6las/advice_for_file_sharing_services](https://www.reddit.com/r/selfhosted/comments/1he6las/advice_for_file_sharing_services)
 - RSS feed: $source
 - date published: 2024-12-14T16:32:11+00:00

<!-- SC_OFF --><div class="md"><p>Hello all,</p> <p>I’m just getting started with homelab with proxmox and one service I want to run is a simple NAS like service. </p> <p>So far I’ve tried NextCloud but it seems to bloated and full of features I’d never use. Next I tried OpenMediaVault, it was better but maybe I’m using it wrong? </p> <p>What I’m looking for is a simple to use service, where I can attach 2 usb hard drives to my mini pc, without the need of reformatting them, and use ACL, and create SMB/SFTP shares to use with my devices and Infuse on Apple TV.</p> <p>Is OMV my simplest option? Is there a good alternative?</p> <p>Thank you. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/countingonhearts"> /u/countingonhearts </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1he6las/advice_for_file_sharing_services/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1he6las/advice_for_file_s

## Question on KnownHost: Access WP site before moving domain DNS and Portainer question
 - [https://www.reddit.com/r/selfhosted/comments/1he5ywh/question_on_knownhost_access_wp_site_before](https://www.reddit.com/r/selfhosted/comments/1he5ywh/question_on_knownhost_access_wp_site_before)
 - RSS feed: $source
 - date published: 2024-12-14T16:02:49+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking into setting up a couple domains on KnownHost and want to verify a use case before I sign up for a VPS server. If I add a Wordpress deployment does it have to have a specific domain associated with it at creation time? Meaning could I setup a site in test mode where I could type something like https://specificip/wp...? I&#39;d like to verify the site is up and running before I migrate DNS from my legacy company. Also key to minimize downtime.</p> <p>Also curious if it would simplify things to use their admin console less and run portainer on the VPS where I could deploy a container for Nginx Proxy Mgr and containers for each of the wordpress sites. </p> <p>Appreciate any best practices here.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/djkoell"> /u/djkoell </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1he5ywh/question_on_knownhost_access_wp_site_before/">[link]</a></sp

## Made a free Chrome extension to increase productivity by building
 - [https://www.reddit.com/r/selfhosted/comments/1he5wha/made_a_free_chrome_extension_to_increase](https://www.reddit.com/r/selfhosted/comments/1he5wha/made_a_free_chrome_extension_to_increase)
 - RSS feed: $source
 - date published: 2024-12-14T16:00:00+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1he5wha/made_a_free_chrome_extension_to_increase/"> <img src="https://b.thumbs.redditmedia.com/McUFk1TY1QqKUEou75dBrhx08lw6jTdu6iWsuOvR2Bc.jpg" alt="Made a free Chrome extension to increase productivity by building" title="Made a free Chrome extension to increase productivity by building" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://i.redd.it/uflhlna57u6e1.gif">Quick and Short Preview</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/HikkiSummers"> /u/HikkiSummers </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1he5wha/made_a_free_chrome_extension_to_increase/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1he5wha/made_a_free_chrome_extension_to_increase/">[comments]</a></span> </td></tr></table>

## Backing up Immich using Restic (From windows right now)
 - [https://www.reddit.com/r/selfhosted/comments/1he4ym5/backing_up_immich_using_restic_from_windows_right](https://www.reddit.com/r/selfhosted/comments/1he4ym5/backing_up_immich_using_restic_from_windows_right)
 - RSS feed: $source
 - date published: 2024-12-14T15:14:58+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1he4ym5/backing_up_immich_using_restic_from_windows_right/"> <img src="https://a.thumbs.redditmedia.com/ZU6vEROICsklVZ6L_pMIHy4ZzmQ1ziWnBb1zlgzRI-4.jpg" alt="Backing up Immich using Restic (From windows right now)" title="Backing up Immich using Restic (From windows right now)" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>So in the future (very near future) I want to backup my immich repo using restic on a raspberry pi in a remote location.</p> <p>Currently this is not the case and I am glad I have not even tried because I am having a lot of trouble with restic as is. Restic I can tell is a good program the thing is im still so new into this backup world so it feels like a big hoop for me to pass right now. The thing is that it is incredibly crucial that I backup my data immediately. </p> <p>I have downloaded restic using scoop on my windows platform as I have a 1tb hdd that I want to begin using to backup 

## Seeking Advice: Remix + Supabase vs. Next.js + Supabase with Coolify
 - [https://www.reddit.com/r/selfhosted/comments/1he4lqo/seeking_advice_remix_supabase_vs_nextjs_supabase](https://www.reddit.com/r/selfhosted/comments/1he4lqo/seeking_advice_remix_supabase_vs_nextjs_supabase)
 - RSS feed: $source
 - date published: 2024-12-14T14:57:54+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I&#39;m considering integrating Coolify into my project and exploring which stack might be the best fit. I&#39;m currently debating between two options:</p> <ol> <li>Remix + Supabase</li> <li>Next.js + Supabase</li> </ol> <p>I noticed that Remix, along with React Router, offers Templates that include Docker support (see: <a href="https://github.com/remix-run/react-router-templates/tree/main">https://github.com/remix-run/react-router-templates/tree/main</a>). Has anyone here used Coolify with these combinations or any other self-hosting setups? I&#39;d appreciate your insights or recommendations based on your experiences!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/reditoro"> /u/reditoro </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1he4lqo/seeking_advice_remix_supabase_vs_nextjs_supabase/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhost

## Local Content Share
 - [https://www.reddit.com/r/selfhosted/comments/1he4iih/local_content_share](https://www.reddit.com/r/selfhosted/comments/1he4iih/local_content_share)
 - RSS feed: $source
 - date published: 2024-12-14T14:53:24+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1he4iih/local_content_share/"> <img src="https://external-preview.redd.it/lDY3rwXmo_oRosIRnb-ih57dKLp6nWPxKRgHNUflR5A.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=0bb22c8c6b587aa6b66f8e34e661f35d916e3b92" alt="Local Content Share" title="Local Content Share" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>sharing an app i wrote and use (recently updated and ported to go). comes in handy in my homelab for sharing files and text across devices in my network. intended for quick ui based sharing and snippet storage</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/import-base64"> /u/import-base64 </a> <br/> <span><a href="https://github.com/tanq16/local-content-share">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1he4iih/local_content_share/">[comments]</a></span> </td></tr></table>

## Mirotalk sfu producer transport failed problem
 - [https://www.reddit.com/r/selfhosted/comments/1he2e4x/mirotalk_sfu_producer_transport_failed_problem](https://www.reddit.com/r/selfhosted/comments/1he2e4x/mirotalk_sfu_producer_transport_failed_problem)
 - RSS feed: $source
 - date published: 2024-12-14T13:01:54+00:00

<!-- SC_OFF --><div class="md"><p>Hallo ich hoffe hier kann mir jemand helfen Wenn möglich auf Deutsch mein Englisch ist nicht so gut . Ich habe mirotalk auf Meinem Ubuntu Server installiert . Das Programm startet auch aber dann kommt eine Fehlermeldung &quot; transport failed problem&quot; ein Coturn server ist Installiert. Ich kann mirotalk aber irgendwie nicht konfigurieren ich weiß auch nicht wo. ich habe mir schon die Anleitung im Netz durchgelesen aber die scheint wohl veraltet zu sein. Ich weiß auch nicht welche Version von mir Mirotalk installiert ist </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Historical-Lie-7958"> /u/Historical-Lie-7958 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1he2e4x/mirotalk_sfu_producer_transport_failed_problem/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1he2e4x/mirotalk_sfu_producer_transport_failed_problem/">[comments]</a></span>

## Self-Hosted Mail Server to receive from Gmail and send via Gmail
 - [https://www.reddit.com/r/selfhosted/comments/1he17gn/selfhosted_mail_server_to_receive_from_gmail_and](https://www.reddit.com/r/selfhosted/comments/1he17gn/selfhosted_mail_server_to_receive_from_gmail_and)
 - RSS feed: $source
 - date published: 2024-12-14T11:42:38+00:00

<!-- SC_OFF --><div class="md"><p>Recently I tried to configure POSTFIX and DOVECOT to receive mail from Gmail and send it.</p> <p>I have this need for reasons of space, I have only emails and attached to them of a company, which does not want to change the way of working.</p> <p>(Please not enter into the merits of this, I have already tried) </p> <p>I wondered if it was possible to properly configure DOVECOT so that he downloaded the mail as a POP client and then was accessible from Thunderbird in IMAP by multiple clients.</p> <p>A bit as if I relocate the Gmail server.</p> <p>Thanks in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/EmanueleVR"> /u/EmanueleVR </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1he17gn/selfhosted_mail_server_to_receive_from_gmail_and/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1he17gn/selfhosted_mail_server_to_receive_from_gmail_and/">[comme

## Remote access in a secure manner
 - [https://www.reddit.com/r/selfhosted/comments/1he0fbu/remote_access_in_a_secure_manner](https://www.reddit.com/r/selfhosted/comments/1he0fbu/remote_access_in_a_secure_manner)
 - RSS feed: $source
 - date published: 2024-12-14T10:45:06+00:00

<!-- SC_OFF --><div class="md"><p>The goal is to access sealfhosted services from outside the network. The vpn service should run in a docker container and only give access to other docker containers, but not to the host network. What is the best way to accomplish this? I know about wireguard, headscale and netmaker, but I&#39;m not sure which option can do exactly this</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Affectionate-Lake733"> /u/Affectionate-Lake733 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1he0fbu/remote_access_in_a_secure_manner/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1he0fbu/remote_access_in_a_secure_manner/">[comments]</a></span>

## First time setting up a home server; "[ip] refused to connect" error.
 - [https://www.reddit.com/r/selfhosted/comments/1hdzvc0/first_time_setting_up_a_home_server_ip_refused_to](https://www.reddit.com/r/selfhosted/comments/1hdzvc0/first_time_setting_up_a_home_server_ip_refused_to)
 - RSS feed: $source
 - date published: 2024-12-14T10:02:36+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m having an issue setting up a server using Nginx. It works completely fine when I enter the local IP into my search bar, but my browser outputs &quot;[ip] refused to connect&quot; whenever I input the public IP. I checked to see if my server was receiving requests, and it wasn&#39;t. I assume it must be an issue with my router.. <em>maybe.</em> I&#39;m not too sure about what to do next; I&#39;ve been trying to get this to work for a couple days now.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Daxaroodles"> /u/Daxaroodles </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdzvc0/first_time_setting_up_a_home_server_ip_refused_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdzvc0/first_time_setting_up_a_home_server_ip_refused_to/">[comments]</a></span>

## Plex - QSV HW Transcoding works in native install not in docker
 - [https://www.reddit.com/r/selfhosted/comments/1hdzje4/plex_qsv_hw_transcoding_works_in_native_install](https://www.reddit.com/r/selfhosted/comments/1hdzje4/plex_qsv_hw_transcoding_works_in_native_install)
 - RSS feed: $source
 - date published: 2024-12-14T09:37:22+00:00

<!-- SC_OFF --><div class="md"><p>HW transcoding works perfectly in native install on Ubuntu 22.04, but not in docker (tried both official and linuxserver images)<br/> I can see the iGPU passed through in webui.<br/> When I try transcode, I see this error</p> <pre><code>[Req#1ae/Transcode] Codecs: hardware transcoding: testing API vaapi for device &#39;/dev/dri/renderD128&#39; (Intel Alder Lake-S GT1 [UHD Graphics 730]) [Req#1ae/Transcode] [FFMPEG] - Failed to initialise VAAPI connection: -1 (unknown libva error). [Req#1ae/Transcode] Codecs: hardware transcoding: opening hw device failed - probably not supported by this system, error: I/O error </code></pre> <p>Output of ls -li /dev/dri</p> <pre><code>709 drwxr-xr-x 2 root root 80 Dec 13 23:15 by-path 330 crw-rw----+ 1 root render 226, 0 Dec 13 23:15 card0 329 crw-rw----+ 1 root render 226, 128 Dec 13 23:15 renderD128 </code></pre> <p>Docker (lsio) logs</p> <pre><code>GID/UID ─────────────────────────────────────── User UID: 1000 Use

## Mac mini 2011 vs Raspberry 5
 - [https://www.reddit.com/r/selfhosted/comments/1hdz5af/mac_mini_2011_vs_raspberry_5](https://www.reddit.com/r/selfhosted/comments/1hdz5af/mac_mini_2011_vs_raspberry_5)
 - RSS feed: $source
 - date published: 2024-12-14T09:05:33+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>Currently I am using Mac mini 2011 i5 8gb for self hosting media server with external hdd and other smaller applications, every thing runs on ubuntu server. When machine loses power it is impossible to boot it back since it starts to boot loop. So the question is, is there any solution for this problem? Or if I buy raspberry 5 8gb version will it handle what Mac-mini does?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bayramgeldi"> /u/bayramgeldi </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdz5af/mac_mini_2011_vs_raspberry_5/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdz5af/mac_mini_2011_vs_raspberry_5/">[comments]</a></span>

## Recommend setup for german ebooks?
 - [https://www.reddit.com/r/selfhosted/comments/1hdz22z/recommend_setup_for_german_ebooks](https://www.reddit.com/r/selfhosted/comments/1hdz22z/recommend_setup_for_german_ebooks)
 - RSS feed: $source
 - date published: 2024-12-14T08:59:18+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>The Arrs offer really great solutions for movies and music and I am very satisfied. Only for eBooks, especially in German, I haven&#39;t really found what I&#39;m looking for. Readarr doesn&#39;t seem to be working at the moment and Openbooks is more for English. Have I overlooked any solutions?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/datatest05"> /u/datatest05 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdz22z/recommend_setup_for_german_ebooks/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdz22z/recommend_setup_for_german_ebooks/">[comments]</a></span>

## Proxmox 8.3 not booting
 - [https://www.reddit.com/r/selfhosted/comments/1hdymhi/proxmox_83_not_booting](https://www.reddit.com/r/selfhosted/comments/1hdymhi/proxmox_83_not_booting)
 - RSS feed: $source
 - date published: 2024-12-14T08:35:54+00:00

<!-- SC_OFF --><div class="md"><p>I have tried kernel 6.2,6.8,6.11. </p> <p>I am trying to install proxmox on Debian 12 because the proxmox installation wasn’t working. I am thinking 🤔 it has something to do with the kernel. </p> <p>My system specs </p> <p>Motherboard: gigabyte B450M DS3H CPU: AMD ryzen-5 2600 6 core Ram: crucial pro DDR4 32GB (2x16gb) Graphics card: MSI GT 710 2GD3-LP M.2: western digital blue 1TB</p> <p>Also what makes it even more weird is if I use an SSD instead it will boot into proxmox 8.3.1 kernel 6.8. This ssd is connected via sata </p> <p>Is it possible that it has something to do with the m.2 storage? Or the graphics card? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/1michaelbrown"> /u/1michaelbrown </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdymhi/proxmox_83_not_booting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdymhi/proxmox_83_not_booting/

## I present: Managarr - a TUI and CLI to manage your Servarr instances (Now with Sonarr support!)
 - [https://www.reddit.com/r/selfhosted/comments/1hdydob/i_present_managarr_a_tui_and_cli_to_manage_your](https://www.reddit.com/r/selfhosted/comments/1hdydob/i_present_managarr_a_tui_and_cli_to_manage_your)
 - RSS feed: $source
 - date published: 2024-12-14T08:18:02+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hdydob/i_present_managarr_a_tui_and_cli_to_manage_your/"> <img src="https://external-preview.redd.it/0EDOK_2t2wWWYiYSzCfUigz5wqWpW3d_yq3J7vro3AE.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=cfada6f9c1af63d8ee11b34a2056ce23ec128594" alt="I present: Managarr - a TUI and CLI to manage your Servarr instances (Now with Sonarr support!)" title="I present: Managarr - a TUI and CLI to manage your Servarr instances (Now with Sonarr support!)" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I was recently furloughed from work. So in between job applications and life, I decided to continue working on my side project. That said, I&#39;m very proud to announce the beta release of Managarr with Sonarr support!</p> <p>In short: <a href="https://github.com/Dark-Alex-17/managarr">Managarr is a TUI and CLI to help you manage your Servarr instances</a>.</p> <p>Thanks to everyone&#39;s feedback when I first announced the alp

## Reminder to protect your server as much as possible!
 - [https://www.reddit.com/r/selfhosted/comments/1hdvypw/reminder_to_protect_your_server_as_much_as](https://www.reddit.com/r/selfhosted/comments/1hdvypw/reminder_to_protect_your_server_as_much_as)
 - RSS feed: $source
 - date published: 2024-12-14T05:28:40+00:00

<!-- SC_OFF --><div class="md"><p>I am debating going with tailscape now to be honest. I am currently using fail2ban and only allow local ip&#39;s access. I am currently using pw&#39;s but will soon switch to keys instead. I tried using 2fa with Google Authenticator but when I set it up I couldn&#39;t log in using my ps not sure what I did wrong. I am currently locked out of one of my servers, its headless so I&#39;lll have to connect a monitor to it and remove 2fa until I can figure it out. I also have UFW enabled. Any other recommendations?</p> <p>Currently I use Nginx Proxy Manager, a 14 random digit pw and my personal domain to access my services remotely. I check my log files everyday through Portainer but that seems exhausting, is there a way I can automate that to get alerts for failed login attempts?</p> <p>I was checking my Audibookshelf that I had running for just 1 full day to see this shit. Thankfully they moved on and they were just trying to access random accounts but I

## Help a noob with setting a Home server
 - [https://www.reddit.com/r/selfhosted/comments/1hdve6z/help_a_noob_with_setting_a_home_server](https://www.reddit.com/r/selfhosted/comments/1hdve6z/help_a_noob_with_setting_a_home_server)
 - RSS feed: $source
 - date published: 2024-12-14T04:53:55+00:00

<!-- SC_OFF --><div class="md"><p>I am pretty new to the server thing and have absolutely 0 knowledge on what i am doing have watched a few videos on how to set it up and get going but i am still stuck on getting the web server installed, i tried both ubuntu and windows but couldn&#39;t figure it out can anyone help me with a detailed forum or any resources with setting up a server i found a <a href="https://youtu.be/72D3MvPk3Xs">video</a> with steps on how to go set it up but couldn&#39;t understand a few details on how to setup you own ip address and how to ssh, i am currently running a i5 4th gen cpu with 8 gigs of ram with around 256gb ssd and 2 tb hdd, would prefer the server to be over wireless since no proper working lan ports and hopefully a web server. Thanks for any resources.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/International-Plum51"> /u/International-Plum51 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comm

## Has anyone found a way to backup their TimeMachine drive to cloud?
 - [https://www.reddit.com/r/selfhosted/comments/1hdul90/has_anyone_found_a_way_to_backup_their](https://www.reddit.com/r/selfhosted/comments/1hdul90/has_anyone_found_a_way_to_backup_their)
 - RSS feed: $source
 - date published: 2024-12-14T04:05:01+00:00

<!-- SC_OFF --><div class="md"><p>After looking at other subs, this one seems like the most competent one for this sort of thing.</p> <p>I used to backup to a network drive. Now, I just use an external drive. </p> <p>But, I want to backup like 1TB to another spot without having to worry much about local data safety.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/HumanAtmosphere3785"> /u/HumanAtmosphere3785 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdul90/has_anyone_found_a_way_to_backup_their/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdul90/has_anyone_found_a_way_to_backup_their/">[comments]</a></span>

## it's not always DNS... sometimes it's DHCP! 😭
 - [https://www.reddit.com/r/selfhosted/comments/1hduiw7/its_not_always_dns_sometimes_its_dhcp](https://www.reddit.com/r/selfhosted/comments/1hduiw7/its_not_always_dns_sometimes_its_dhcp)
 - RSS feed: $source
 - date published: 2024-12-14T04:01:28+00:00

<!-- SC_OFF --><div class="md"><p>says the guy (me) who decided to tighten up security on my network&#39;s Pihole, which provides DNS and DHCP services for my home network, and did:</p> <p><code>ufw default deny incoming</code></p> <p>and also felt like a genius for remembering to do:</p> <p><code># for SSH</code><br/> <code>ufw allow 22/tcp</code><br/> <code>ufw allow 7822/tcp</code><br/> <code># for DNS server</code><br/> <code>ufw allow 53/tcp</code><br/> <code>ufw allow 53/udp</code><br/> <code>ufw allow 853/tcp</code><br/> <code># for Pihole web interface</code><br/> <code>ufw allow 80/tcp</code><br/> <code>ufw allow 443/tcp</code><br/> <code># for SMTP</code><br/> <code>ufw allow 587/tcp</code></p> <p>but forgot to do...</p> <p><code># for DHCP server</code><br/> <code>ufw allow 67/udp</code><br/> <code>ufw allow 68/udp</code></p> <p>and brought down our Plex, QBittorrent, tailscale, Postgres, Kafka, Zabbix, mqtt, plus my Docker/Portainer server for 36 hours and I only just now

## Audio book organizer
 - [https://www.reddit.com/r/selfhosted/comments/1hdtvpg/audio_book_organizer](https://www.reddit.com/r/selfhosted/comments/1hdtvpg/audio_book_organizer)
 - RSS feed: $source
 - date published: 2024-12-14T03:24:19+00:00

<!-- SC_OFF --><div class="md"><p>Does anyone have suggestions for a self hosted solution to automatically organize books based on file/folder names? If it also had an android app for downloading stuff to my phone that would be great.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/VorlMaldor"> /u/VorlMaldor </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdtvpg/audio_book_organizer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdtvpg/audio_book_organizer/">[comments]</a></span>

## Is there anything like Glances that can display resource usage over an interval of time?
 - [https://www.reddit.com/r/selfhosted/comments/1hdtpyl/is_there_anything_like_glances_that_can_display](https://www.reddit.com/r/selfhosted/comments/1hdtpyl/is_there_anything_like_glances_that_can_display)
 - RSS feed: $source
 - date published: 2024-12-14T03:15:10+00:00

<!-- SC_OFF --><div class="md"><p>Looking for something lightweight that can graph out CPU and RAM usage for my docker containers over time. I think something’s causing my system to go haywire every few hours and looking for a way to help me catch it in the act. </p> <p>I watched 15 minutes of a YouTube video on setting up a grafana/telegraf/influxdb stack before conceding that it was a bit out of my league and prob overkill for what I’m trying to achieve. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/edmonddantesofficial"> /u/edmonddantesofficial </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdtpyl/is_there_anything_like_glances_that_can_display/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdtpyl/is_there_anything_like_glances_that_can_display/">[comments]</a></span>

## dockerized nginx, django, next.js
 - [https://www.reddit.com/r/selfhosted/comments/1hdtj3r/dockerized_nginx_django_nextjs](https://www.reddit.com/r/selfhosted/comments/1hdtj3r/dockerized_nginx_django_nextjs)
 - RSS feed: $source
 - date published: 2024-12-14T03:04:28+00:00

<!-- SC_OFF --><div class="md"><p>when I didn’t have NGINX, I used to make direct API requests from Next.js to Django REST endpoints, but after adding NGINX, I started routing requests through NGINX, which also serves static and media files. Is this a good approach? If so, how can I restrict access to the API endpoints (example.com/api/) so they’re not publicly accessible (e.g., no direct access to the browsable API) while keeping everything functional in production? What’s the best practice for this setup?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tepa6aut"> /u/tepa6aut </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdtj3r/dockerized_nginx_django_nextjs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdtj3r/dockerized_nginx_django_nextjs/">[comments]</a></span>

## PortsInfo, simple GUI for netstat/ss to view active network ports
 - [https://www.reddit.com/r/selfhosted/comments/1hdt4au/portsinfo_simple_gui_for_netstatss_to_view_active](https://www.reddit.com/r/selfhosted/comments/1hdt4au/portsinfo_simple_gui_for_netstatss_to_view_active)
 - RSS feed: $source
 - date published: 2024-12-14T02:41:42+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys I just released <a href="https://github.com/mfat/ports-info">PortsInfo</a>. It a very simple and lightweight app that might come in handy for self-hosters. </p> <p>It lists all running servers (essentially it&#39;s a gui for netstat -plunt). You can quickly search through port numbers and process name using control+F keyboard shortcut. </p> <p>Hope you find useful and i welcome your feedback/thoughts. </p> <p>There are <a href="https://github.com/mfat/ports-info/releases">DEB and RPM</a> packages and hopefully I&#39;ll release a flatpak too when I finally figure out how it works :) </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/walterblackkk"> /u/walterblackkk </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdt4au/portsinfo_simple_gui_for_netstatss_to_view_active/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdt4au/portsinfo_simple_gui_f

## Smart Speaker with OpenAI
 - [https://www.reddit.com/r/selfhosted/comments/1hdswgq/smart_speaker_with_openai](https://www.reddit.com/r/selfhosted/comments/1hdswgq/smart_speaker_with_openai)
 - RSS feed: $source
 - date published: 2024-12-14T02:29:35+00:00

<!-- SC_OFF --><div class="md"><p>I assumed this would be simple but I can&#39;t seem to find any info on making my own Amazon Alexa clone but with OpenAI or CoPilot. Anybody know how to do this? I am thinking Raspberry Pi, but I want it to look good. Also it has to run all the time in kiosk mode like Alexa. Basically be 100% voice controlled.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MrStuff1Consultant"> /u/MrStuff1Consultant </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdswgq/smart_speaker_with_openai/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdswgq/smart_speaker_with_openai/">[comments]</a></span>

## Filecloud setup on vm
 - [https://www.reddit.com/r/selfhosted/comments/1hds8sv/filecloud_setup_on_vm](https://www.reddit.com/r/selfhosted/comments/1hds8sv/filecloud_setup_on_vm)
 - RSS feed: $source
 - date published: 2024-12-14T01:53:43+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hds8sv/filecloud_setup_on_vm/"> <img src="https://preview.redd.it/xraiquo60q6e1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=84f4019698daa3ecf40868b30467146de2be8cae" alt="Filecloud setup on vm" title="Filecloud setup on vm" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Ok so i have this weird issue after downloading the ova file from filecloud and everything is fine until im trying to enter the admin page and it’s just stuck at loading hours and nothing happens any fix for it ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AMV-RAD"> /u/AMV-RAD </a> <br/> <span><a href="https://i.redd.it/xraiquo60q6e1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hds8sv/filecloud_setup_on_vm/">[comments]</a></span> </td></tr></table>

## Open Source Inventory Management With Sub Parts
 - [https://www.reddit.com/r/selfhosted/comments/1hdrcg0/open_source_inventory_management_with_sub_parts](https://www.reddit.com/r/selfhosted/comments/1hdrcg0/open_source_inventory_management_with_sub_parts)
 - RSS feed: $source
 - date published: 2024-12-14T01:06:23+00:00

<!-- SC_OFF --><div class="md"><p>Can anyone recommend a self hosted open source inventory management solution that allows parts to be linked to main products?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Disastrous-Life9794"> /u/Disastrous-Life9794 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdrcg0/open_source_inventory_management_with_sub_parts/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hdrcg0/open_source_inventory_management_with_sub_parts/">[comments]</a></span>

## Is there a way to port forward Plex remote access through a Wireguard VPN?
 - [https://www.reddit.com/r/selfhosted/comments/1hdr6ng/is_there_a_way_to_port_forward_plex_remote_access](https://www.reddit.com/r/selfhosted/comments/1hdr6ng/is_there_a_way_to_port_forward_plex_remote_access)
 - RSS feed: $source
 - date published: 2024-12-14T00:58:09+00:00

<!-- SC_OFF --><div class="md"><p>Hosting Plex on a gaming PC until I get a NAS setup. Everything works great, except when I want to use WireGuard on the gaming PC. Right now I’m using policy based routing in PFsense to send my Gaming PC through the regular WAN gateway instead of my VPN gateway. As soon as I change that policy order so my gaming PC is routed through WG, no matter what I do I can’t seem to set up the direct remote access to work. </p> <p>In other words, 10.0.0.1 &lt; 32400 &lt; 12.12.12.123 (real IP) works.</p> <p>10.0.0.1 &lt;32400 &lt; 45.123.123.123 (VPN IP) does not.</p> <p>10.0.0.1 &lt;72629 (VPN P2P Port) &lt;45.123.123.123 does not.</p> <p>I have tried changing the port to whatever port my VPN server uses for P2P, but that doesn’t work either. Any help would be appreciated. TIA</p> <p>Edit: the VPN is through Proton, so I just have my whole connection tunneled through WG with the exception of my gaming PC. I would like to tunnel my gaming PC through WG as well,

