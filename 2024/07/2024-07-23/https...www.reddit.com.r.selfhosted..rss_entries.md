# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Distribution of Lets encrypt SSL certificatrs to multiple hosts?
 - [https://www.reddit.com/r/selfhosted/comments/1eam737/distribution_of_lets_encrypt_ssl_certificatrs_to](https://www.reddit.com/r/selfhosted/comments/1eam737/distribution_of_lets_encrypt_ssl_certificatrs_to)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T23:15:27+00:00

<!-- SC_OFF --><div class="md"><p>I'm setting up my current network to get SSL certs for services on different servers. All services are local network only, VPNs handle remote access. My problem, from my understanding, is I need a cert directly on the hardware for HomeAssistant (Zwave Smart Setup, possibly more for MQTT servers, I haven't gotten that far yet) and, at least at this point, pfSense (doesn't like reverse proxy I've heard). Creating a CA and using a self-signed cert is not feasible. </p> <p>Do I need to run processes for the different machines to get a cert, or does LetsEncrypt allow only one device connection, and so I need some sort of automated distribution system?</p> <p>I am going to use Cloudflare for DDNS, I have my domains there already. I'm also planning to have the VPNs managed on pfSense.</p> <p>Additionally, I also have two geographic locations. I'm hoping to make my system work like this:</p> <p><a href="http://a.example.com">a.example.com</a> (public (possibl

## Your own “icloud” backup alternative
 - [https://www.reddit.com/r/selfhosted/comments/1ealy2c/your_own_icloud_backup_alternative](https://www.reddit.com/r/selfhosted/comments/1ealy2c/your_own_icloud_backup_alternative)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T23:04:42+00:00

<!-- SC_OFF --><div class="md"><p>I'm curious if anyone has done or seen any good alternatives to &quot;backup to iCloud&quot;?</p> <p>I envision a super simple high quality alternative where you can have network attached harddrive/NAS for everyday people. A simple Shopify site selling a nice simple hardware you plugin to your router and you can save things to easy. It might even offer a sort of redundancy or distributed &quot;cloud&quot; service for a fee to have a copy off site encrypted either in their servers or other users drives.</p> <p>I imagine if you market that right you could do a simple business that would make boatloads of money if built for everyday apple like users.</p> <p>If you might want to help build it let me know.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Futurenathan"> /u/Futurenathan </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ealy2c/your_own_icloud_backup_alternative/">[link]</a></span> &

## I'm looking for backup solutions instead of BackupPC
 - [https://www.reddit.com/r/selfhosted/comments/1eakkoy/im_looking_for_backup_solutions_instead_of](https://www.reddit.com/r/selfhosted/comments/1eakkoy/im_looking_for_backup_solutions_instead_of)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T22:06:17+00:00

<!-- SC_OFF --><div class="md"><p>Hello.</p> <p>I am looking for a selhosted solution for backup of linux servers (mail and www).</p> <p>Assumptions:</p> <ul> <li><p>compression</p></li> <li><p>incremental and full backups</p></li> <li><p>web interface</p></li> <li><p>possibility to backup more than one machine on one server</p></li> </ul> <p>So far I have been using BackupPC and this solution worked great. However, I have been having problems with it for some time:</p> <ul> <li><p>it does not free up space after deleting old backups</p></li> <li><p>sometimes it only makes copies of directories skipping files</p></li> </ul> <p>I would appreciate if you could recommend me reasonable solutions that meet the objectives.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/josemcornynetoperek"> /u/josemcornynetoperek </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eakkoy/im_looking_for_backup_solutions_instead_of/">[link]</a></spa

## Docker Non Root Containers
 - [https://www.reddit.com/r/selfhosted/comments/1eajqaa/docker_non_root_containers](https://www.reddit.com/r/selfhosted/comments/1eajqaa/docker_non_root_containers)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T21:31:21+00:00

<!-- SC_OFF --><div class="md"><p>Hello all, I want to limit containers privileges throughout my environment, I am able to specify an user ID in docker compose for Grafana. Like so: user: “6001:6001” ( I adjusted the permissions on the volume mounts as well) </p> <p>The container starts and runs but when I enter the container shell and run “whoami” I get unknown UID 6001. </p> <p>The container is running as the grafana user on the system (6001) but will problems occur with other containers if whoami does not resolve?</p> <p>Is this to be expected or additional steps needed?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/react2724"> /u/react2724 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eajqaa/docker_non_root_containers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eajqaa/docker_non_root_containers/">[comments]</a></span>

## Veracrypt options
 - [https://www.reddit.com/r/selfhosted/comments/1eajc4m/veracrypt_options](https://www.reddit.com/r/selfhosted/comments/1eajc4m/veracrypt_options)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T21:15:20+00:00

<!-- SC_OFF --><div class="md"><p>I currently have a veracrypt container that I use to store some large super critically important client files. The container started out small but over the years has grown and it is becoming harder to manage. I have to mount this over network share currently which also adds some reliability and slowness to the mix. Is there any good self hosted file store that has trusted encryption to the degree of an encrypted container? Another nice thing for veracrypt is I currently have multiple copies of the container stored and backed up in several places to ensure its safety if my main server were to die, typical rule of three. I would need something with an easy or at the least robust backup path. I am considering making a dedicated instance of owncloud or something like that, that can handle serving the files but maintaining tight security on them when not being accessed. I hope this makes sense. Thank you for any suggestions ahead of time.</p> </div><!-- SC

## Scanner for paperless-ng
 - [https://www.reddit.com/r/selfhosted/comments/1eaingi/scanner_for_paperlessng](https://www.reddit.com/r/selfhosted/comments/1eaingi/scanner_for_paperlessng)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T20:48:03+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a scanner, to scan tons of paperwork. It will have a good automatic feed tray that doesn’t easily jam, and in automatic mode will scan both sides. It will save the scans on NAS using samba share or similar, and could do OCR or let that for paperless-ng. No forced cloud storage. </p> <p>Can you suggest a scanner for this use case? </p> <p>So far I have seen Brother ADS 1700W, ADS 1200, 940DW and Fujitsu ScanSnap iX1300. </p> <p>By the way, these scanners are as expensive as MFPs that do all 4 functions: scan, copy, print and fax. How come?</p> <p>Perhaps it’s better to get a multi function printer?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/chaplin2"> /u/chaplin2 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eaingi/scanner_for_paperlessng/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eaingi/scanner_for_paperlessng/">[comments

## Kodi with jellyfin/emby weird lag
 - [https://www.reddit.com/r/selfhosted/comments/1eai0bw/kodi_with_jellyfinemby_weird_lag](https://www.reddit.com/r/selfhosted/comments/1eai0bw/kodi_with_jellyfinemby_weird_lag)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T20:21:53+00:00

<!-- SC_OFF --><div class="md"><p>So I have tried this setup with both emby and jellyfin but I get the same behavior. So the setup is, </p> <p>On my Xbox Series X I run kodi. On kodi I run kodi for jellyfin or emby next Gen (both in add on mode) and I watch 4k remux movies that I have on a fairly slow, but should still be fast enough I guess , ssd (460 MB/S speed). The ssd is then connected via USB c to the laptop where I run jellyfin/emby. The communication between the laptop and router is wired, but wifi to Xbox </p> <p>When I watch a movie, it will work really well 99% of the movie but for every movie it will buffer between 1-3 times. Everytime it buffers the CPU is maxed out on the laptop by jellyfin /emby (only run one at a time). After a few seconds the CPU goes down and it plays again. </p> <p>I have also tried running emby plugin in native mode, so the Xbox goes straight to smb instead of jellyfin /kodi, but the same thing, it buffers the same and the smb process is instead ma

## SSL_ERROR_NO_CYPHER_OVERLAP on local domains w/ Cloudflare DNS
 - [https://www.reddit.com/r/selfhosted/comments/1eahygi/ssl_error_no_cypher_overlap_on_local_domains_w](https://www.reddit.com/r/selfhosted/comments/1eahygi/ssl_error_no_cypher_overlap_on_local_domains_w)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T20:19:47+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, </p> <p>Running into an issue - I have my local domains behind Nginx Proxy Manager w/ a Cloudflare DNS challenge. The first handful of domains worked fine, and continue to, but anything new added results in a SSL_ERROR_NO_CYPHER_OVERLAP error. Digging around, this seems to be &quot;expected&quot; as my local domain is some form of ${SERVICE}.local.domain.tld, and Cloudflare's Universal SSL does not cover that, and I would have to purchase their Advanced Cert Manager. </p> <p>Are any of you just paying the $10/mo for their ACM? What are you doing/using if not?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Marioawe"> /u/Marioawe </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eahygi/ssl_error_no_cypher_overlap_on_local_domains_w/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eahygi/ssl_error_no_cypher_overlap_on_local_domains_w/">[comments]<

## Wall Rack and home storage finally done
 - [https://www.reddit.com/r/selfhosted/comments/1eahejj/wall_rack_and_home_storage_finally_done](https://www.reddit.com/r/selfhosted/comments/1eahejj/wall_rack_and_home_storage_finally_done)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T19:58:07+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1eahejj/wall_rack_and_home_storage_finally_done/"> <img alt="Wall Rack and home storage finally done" src="https://b.thumbs.redditmedia.com/2JdvattdtkxgJty10TxPVm_R61Gk_raJJb0Csi0rS_w.jpg" title="Wall Rack and home storage finally done" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/o19xec2sobed1.jpg?width=1265&amp;format=pjpg&amp;auto=webp&amp;s=d41d7015eed2fa681b6c04355738df7795269bc9">Rack</a></p> <p>Finally done, happy with this setup :</p> <ul> <li>Router Omada TP-Link ER8411</li> <li>Switch Omada TP-L-Link SG2210XMP-M2</li> <li>3 x AP Omada TP-Link EP615-Wall</li> <li>ISP Router (bridged, seems to be a big ONT right now) Freebox Delta (10 Gbits / 700 Mbits)</li> <li>NAS (not on the pic), tower Lian Li PC-A17B with Mini ITX Topton N5105, 32 GB, 5 x 8 TB HDD, 2 x 512 GB NVME and 1 x 2 TB for array cache</li> </ul> <p>I'm very impressed by the Q/P of the Omada products, can 

## Selfhosting Mail server
 - [https://www.reddit.com/r/selfhosted/comments/1eah3b6/selfhosting_mail_server](https://www.reddit.com/r/selfhosted/comments/1eah3b6/selfhosting_mail_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T19:45:43+00:00

<!-- SC_OFF --><div class="md"><p>Hello I have Debian 11 server with dedicated public IP, and I want to host a mail server, I do not know what to use and how to set it up? Do you even recommend it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ImAxolotlik"> /u/ImAxolotlik </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eah3b6/selfhosting_mail_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eah3b6/selfhosting_mail_server/">[comments]</a></span>

## Your yearly reminder to perform a docker system prune
 - [https://www.reddit.com/r/selfhosted/comments/1eagm9c/your_yearly_reminder_to_perform_a_docker_system](https://www.reddit.com/r/selfhosted/comments/1eagm9c/your_yearly_reminder_to_perform_a_docker_system)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T19:26:44+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1eagm9c/your_yearly_reminder_to_perform_a_docker_system/"> <img alt="Your yearly reminder to perform a docker system prune" src="https://preview.redd.it/gefsdovrkbed1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=d238296d9c6bc73252b1c3208258789b8661635f" title="Your yearly reminder to perform a docker system prune" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nathan12581"> /u/nathan12581 </a> <br /> <span><a href="https://i.redd.it/gefsdovrkbed1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eagm9c/your_yearly_reminder_to_perform_a_docker_system/">[comments]</a></span> </td></tr></table>

## Our year-long journey to open-sourcing an access gateway
 - [https://www.reddit.com/r/selfhosted/comments/1eafm42/our_yearlong_journey_to_opensourcing_an_access](https://www.reddit.com/r/selfhosted/comments/1eafm42/our_yearlong_journey_to_opensourcing_an_access)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T18:46:34+00:00

<!-- SC_OFF --><div class="md"><p>This decision wasn't easy. We've spent the last year debating, planning, and frankly, worrying about this move. But ultimately, we believe it aligns with the values of transparency and community-driven development that we believe.</p> <p>We're still figuring out how this affects our business model, and to be honest, it's been challenging. But we're committed to making it work.</p> <p>Here's a brief overview of Hoop:</p> <ul> <li>It's an access gateway for remote connections</li> <li>Designed to be self-hosted</li> <li>Aims to simplify secure access to various services (SSH, RDP, web apps, databases)</li> </ul> <p>Our journey to open-source was gradual:</p> <ol> <li>We started with a free SaaS plan</li> <li>Then offered a free self-hosted option</li> <li>Moved to a free open-binary model</li> <li>And now, we've gone fully open-source</li> </ol> <p>I'm sharing this here because:</p> <ol> <li>We'd genuinely appreciate your thoughts and feedback</li> <li>

## Interested in locally installed AI text-to-image generators with the ability to feed a custom library of visual data to generate from that remains solely my property
 - [https://www.reddit.com/r/selfhosted/comments/1eaesf9/interested_in_locally_installed_ai_texttoimage](https://www.reddit.com/r/selfhosted/comments/1eaesf9/interested_in_locally_installed_ai_texttoimage)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T18:13:03+00:00

<!-- SC_OFF --><div class="md"><p>I was wondering if there's a free-for-commercial-use AI text-to-image generator that can be installed locally and/or operate offline that allows one to customize the AI's generations by uploading their own personal stock of photos and illustrations but that said user uploaded content is not added to the rest of the AI's data for everyone else to generate from? </p> <p>Let me know if thi is the wrong subreddit for this, I'm still a total noob to Reddit.</p> <p>More info that may elaborate on my question or may just be TL;DR: </p> <p>I'm an artist and I have a lot of my own hand-drawn and digitally drawn illustrations as well as my own (extensively large) stock of photographic images that I'd like to be able to upload as part of an AI Generator's library of visual information to draw from and generate unique images with, but I don't want what I upload to an AI to be stored in some cloud data bank and accessible for everyone else to generate content from

## Langfuse Docker Install: Self Hosted LangSmith Alternative
 - [https://www.reddit.com/r/selfhosted/comments/1eaehut/langfuse_docker_install_self_hosted_langsmith](https://www.reddit.com/r/selfhosted/comments/1eaehut/langfuse_docker_install_self_hosted_langsmith)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T18:00:59+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1eaehut/langfuse_docker_install_self_hosted_langsmith/"> <img alt="Langfuse Docker Install: Self Hosted LangSmith Alternative" src="https://external-preview.redd.it/sGNVQ0r2V8FypbiQ8IJG1-Ubq_1oKcNuNhc-vwzbYes.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=9b3f6bcc57f875592ccbce3920fc2a5b49620d89" title="Langfuse Docker Install: Self Hosted LangSmith Alternative" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>In case you want an analytics app for your LLM apps Langfuse can be easely installed with docker.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bitdoze"> /u/bitdoze </a> <br /> <span><a href="https://www.bitdoze.com/langfuse-docker-install/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eaehut/langfuse_docker_install_self_hosted_langsmith/">[comments]</a></span> </td></tr></table>

## Decrypt secrets through ArgoCD
 - [https://www.reddit.com/r/selfhosted/comments/1eaef5p/decrypt_secrets_through_argocd](https://www.reddit.com/r/selfhosted/comments/1eaef5p/decrypt_secrets_through_argocd)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T17:58:06+00:00

<!-- SC_OFF --><div class="md"><p>Hello all, I have a <a href="https://github.com/chaitanya2692/my-homelab">homelab </a>hosted on a k3s ubuntu server. I used to previously deploy all services to the htpc namespace using a couple of bash scripts: <a href="http://update-manifests.sh">update-manifests.sh</a> and <a href="https://github.com/chaitanya2692/my-homelab/blob/main/scripts/deploy.sh">deploy.sh</a>.</p> <p>I am right now trying to learn how to use ArgoCD to automate the deployment. The aim of <a href="https://github.com/chaitanya2692/my-homelab/pull/18">this PoC</a> is to have argocd in the argocd namespace and all other services in the htpc namespace. The PoC is supposed to deploy argocd and the htpc services in their respective namespaces.</p> <p>It was easy to decrypt secrets through a bash script before deploying. In ArgoCD, I have implemented a <a href="https://github.com/chaitanya2692/my-homelab/pull/18/files#diff-b8072acfd5d683b3d15ff44bc5ba4b438f7f1123d9e929897be7d977d1d1

## What are you using for centralized logging?
 - [https://www.reddit.com/r/selfhosted/comments/1eaeano/what_are_you_using_for_centralized_logging](https://www.reddit.com/r/selfhosted/comments/1eaeano/what_are_you_using_for_centralized_logging)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T17:53:01+00:00

<!-- SC_OFF --><div class="md"><p>One thing I have been behind on doing is setting up centralized logging on my network. I originally wanted to try Grafana &amp; Loki, but I never got much further than the initial setup. I know Splunk is super popular, but not sure how much the 500MB/day limit will be, now or in the future.</p> <p>I already have around 60 docker containers, as well as a few VMs and a proxmox cluster along with TrueNAS primary/backup.</p> <p>I was really interested in Loki due to how it claims to drastically reduce logging space despite keeping the important data.</p> <p>Is it even possible to get intelligent logging with alerts without paying a fortune for commercial licensing on a small setup?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MidnightProgrammer"> /u/MidnightProgrammer </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eaeano/what_are_you_using_for_centralized_logging/">[link]</a></span> &#32;

## One specific port cannot be opened
 - [https://www.reddit.com/r/selfhosted/comments/1eadhm0/one_specific_port_cannot_be_opened](https://www.reddit.com/r/selfhosted/comments/1eadhm0/one_specific_port_cannot_be_opened)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T17:20:17+00:00

<!-- SC_OFF --><div class="md"><p>I'm trying to host a server with voice chat on port 24454, </p> <p>I could open 25565 to the server and 25560 to a remote panel, </p> <p>but 24454 just refuses to open no matter what, double checked local IP and everything.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/stoppingcart"> /u/stoppingcart </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eadhm0/one_specific_port_cannot_be_opened/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eadhm0/one_specific_port_cannot_be_opened/">[comments]</a></span>

## Household server: Old-school or Kubernetes, opinions and discussion welcome
 - [https://www.reddit.com/r/selfhosted/comments/1ead7zt/household_server_oldschool_or_kubernetes_opinions](https://www.reddit.com/r/selfhosted/comments/1ead7zt/household_server_oldschool_or_kubernetes_opinions)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T17:09:27+00:00

<!-- SC_OFF --><div class="md"><p>Not sure if it belongs here, or on <a href="/r/homelab">r/homelab</a>, but want some opinions. Please ignore any interspersed rants, not sure how to collapse them on Reddit, and I apologise for the wall of text.</p> <p>I'm redoing my home server, to add some services to it:</p> <ul> <li>Plex, for the 5th(?) time</li> <li>Photo collection manager, Immich/PhotoPrism/similar</li> <li>Recipe manager (Still considering options)</li> <li>Paperless-ng</li> <li>Possibly a home budgeting app, if I can find one that can reliably pull South African bank records &lt;details&gt; &lt;summary&gt; Rant &lt;/summary&gt; SA Banks are special, they feel the international standards are fraud-prone, so only by providing your username and password to a third party app to imitate you, can you pull anything. &lt;/details&gt;</li> <li>Resilio Sync handled backups</li> <li>Mesh VPN / Zero Trust access</li> <li>Ejabberd / Matrix, household communications</li> <li>Elasticsearch 

## Using Authentik as reverse proxy?
 - [https://www.reddit.com/r/selfhosted/comments/1eacm4y/using_authentik_as_reverse_proxy](https://www.reddit.com/r/selfhosted/comments/1eacm4y/using_authentik_as_reverse_proxy)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T16:45:17+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>Currently I use adguard, nginx proxy manager, and authentik to provide authentication for my internal apps. It works great for the most part. DNS in adguard points to the nginxPM, which then has custom configuration to point to authentik. Authentik then has applications set up for proxy which send its down to the app itself. </p> <p>The issue im trying to solve (or create), is nginx proxy manager is taking about 20-30 minutes to completely spin up now. I have about 30 entries. Its persisted like this through multiple updates. I would like to use zoraxy but it doesnt support the custom configurations to send to authentik. </p> <p>It got me thinking if i could bypass nginxpm and send the traffic directly to authentik to act as the reverse proxy. Is that a function authentik can provide? It seems like it should but I havent been able to find anything explicitly showing that set up. If so, how would cert update through letsencrypt work? I im

## Seeking recommendations
 - [https://www.reddit.com/r/selfhosted/comments/1eabzvw/seeking_recommendations](https://www.reddit.com/r/selfhosted/comments/1eabzvw/seeking_recommendations)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T16:20:19+00:00

<!-- SC_OFF --><div class="md"><p>I have a seemingly simple problem, but the best way forward totally eludes me!</p> <p>At work, we use Survey Monkey as a method of having contractors agree terms. there are a number of pages with images and text, first page asks their name and the name of their contact at the company, all each person has to do at the bottom, is click &quot;I agree&quot; and it moves to the next section. At the end, they get a thank you message and it's done. While it sounds an elongated process, and a single document with an agreement sign off sounds easier, given the information they are agreeing too, the company wants to make sure people actually read and understand the agreement. </p> <p>The issue with this is that Survey Monkey has restricted numbers of users and it's not great at outputting the replies the way the staff need it to. </p> <p>So I had 2 trains of thought, as a hobbyist &quot;developer&quot; I'd setup something like LimeSurvey to handle it instead. I

## [REQUEST] Docs/text editor that persists directly to filesystem?
 - [https://www.reddit.com/r/selfhosted/comments/1eabxt3/request_docstext_editor_that_persists_directly_to](https://www.reddit.com/r/selfhosted/comments/1eabxt3/request_docstext_editor_that_persists_directly_to)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T16:17:58+00:00

<!-- SC_OFF --><div class="md"><p>Basically title.</p> <p>USE CASE: I’d like to view/edit a directory of plain text notes (Markdown) that lives on an SSH server, from my iPhone. Ideally, I may even like to give others to access/view some subset of these files. But they have to be plain text files (not DB records) because they get synced to my laptop, where I edit them (sometimes offline) in a regular text editor.</p> <p>ALTERNATIVES I’VE CONSIDERED:</p> <ul> <li><strong>an iOS text editor app with SFTP support (Textastic, GTW)</strong><br /> Might be fine, but I’d prefer FOSS</li> <li><strong>Obsidian for iOS</strong><br /> Only supports sync via icloud and Obsidian Sync; I am syncing with Syncthing</li> <li><strong>HedgeDoc, Etherpad</strong><br /> I’m under the impression these store docs as DB records; would love to be misinformed on this point</li> </ul> <p>Any leads would be greatly appreciated 🙇🙇🙇</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/

## cant find my mounted folder
 - [https://www.reddit.com/r/selfhosted/comments/1eab76h/cant_find_my_mounted_folder](https://www.reddit.com/r/selfhosted/comments/1eab76h/cant_find_my_mounted_folder)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T15:48:02+00:00

<!-- SC_OFF --><div class="md"><p>i am currently new to this, i have ubuntu server installed and i have mounted a drive with my media into /home/user/media but when i go and search that folder into jellyfin i cant find it. I have tried reinstalling jellyfin, mounting and unmounting the drive to other folders but nothing works.</p> <p>I would like some help</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Icebreaker081"> /u/Icebreaker081 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eab76h/cant_find_my_mounted_folder/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eab76h/cant_find_my_mounted_folder/">[comments]</a></span>

## BrinxAI DePIN Project
 - [https://www.reddit.com/r/selfhosted/comments/1eaalbq/brinxai_depin_project](https://www.reddit.com/r/selfhosted/comments/1eaalbq/brinxai_depin_project)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T15:24:18+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://x.com/BrinxAi_Labs/status/1815666980633882940">https://x.com/BrinxAi_Labs/status/1815666980633882940</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Icy-Ad-6399"> /u/Icy-Ad-6399 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1eaalbq/brinxai_depin_project/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1eaalbq/brinxai_depin_project/">[comments]</a></span>

## Current Favourite Read-It-Later app - Readeck
 - [https://www.reddit.com/r/selfhosted/comments/1ea8w8o/current_favourite_readitlater_app_readeck](https://www.reddit.com/r/selfhosted/comments/1ea8w8o/current_favourite_readitlater_app_readeck)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T14:14:20+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://readeck.org/en/">https://readeck.org/en/</a></p> <p>I know there are a ton of these kicking around and I never see anyone mention Readeck. I honestly love it. Over time, Wallabag just stopped working well for me and it probably took about a year before I stumbled on this one. Currently, I'm just waiting to see integration with some kind of app and oauth support, but the ebook export works for offline and oauth is at least on the roadmap.</p> <p>Just thought I'd give it a quick shout out - thanks to the devs!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/No_Ja"> /u/No_Ja </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea8w8o/current_favourite_readitlater_app_readeck/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea8w8o/current_favourite_readitlater_app_readeck/">[comments]</a></span>

## Cloudflare tunnels blocked by university?
 - [https://www.reddit.com/r/selfhosted/comments/1ea8j75/cloudflare_tunnels_blocked_by_university](https://www.reddit.com/r/selfhosted/comments/1ea8j75/cloudflare_tunnels_blocked_by_university)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T13:59:11+00:00

<!-- SC_OFF --><div class="md"><p>I just set this up recently to access nextcloud from outside my home. It works flawlessly until I arrive at work and connect to the university wifi. Nextcloud reports it cannot connect to server, and any subdomain URLs I set up with cloudflare, ie: <a href="http://homeassist.domain.com">homeassist.domain.com</a> forward to an akami url with university branding which says: &quot;The website you are trying to access either presents a security risk or is not allowed under your organization's acceptable use policy.&quot;</p> <p>If I use an https:// url then I get the firefox error page: </p> <h1>Secure Connection Failed</h1> <p>An error occurred during a connection to subdomain.domain.com. PR_END_OF_FILE_ERROR</p> <p>Error code: PR_END_OF_FILE_ERROR</p> <ul> <li>The page you are trying to view cannot be shown because the authenticity of the received data could not be verified.</li> <li>Please contact the website owners to inform them of this problem. Secu

## Wording change and clarification for purchasing Immich
 - [https://www.reddit.com/r/selfhosted/comments/1ea8iim/wording_change_and_clarification_for_purchasing](https://www.reddit.com/r/selfhosted/comments/1ea8iim/wording_change_and_clarification_for_purchasing)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T13:58:21+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ea8iim/wording_change_and_clarification_for_purchasing/"> <img alt="Wording change and clarification for purchasing Immich" src="https://b.thumbs.redditmedia.com/jNH5ouDFKrUdT-w6YnyRWGcld0YIqFjroacOaVp5Qvc.jpg" title="Wording change and clarification for purchasing Immich" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Announcement Thread <a href="https://github.com/immich-app/immich/discussions/11313">https://github.com/immich-app/immich/discussions/11313</a></p> <p>Hello everybody,</p> <p>Alex here! After the last announcement on a wording change in response to our mishap of using the words <code>licensed</code> and <code>unlicensed</code>, the team and I gave it a long hard thought over the weekend.</p> <p>I thought about it when I went to bed, I thought about it in my dream, I thought about it while doing the dishes. Taking into consideration all of your feedback and suggestions, and on behalf of the team

## Just got a Raspberry Pi 4 I want to use to selfhost personal stuff (blog, pictures, etc.)
 - [https://www.reddit.com/r/selfhosted/comments/1ea895u/just_got_a_raspberry_pi_4_i_want_to_use_to](https://www.reddit.com/r/selfhosted/comments/1ea895u/just_got_a_raspberry_pi_4_i_want_to_use_to)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T13:47:01+00:00

<!-- SC_OFF --><div class="md"><p>What approach do you recommend me to get started? I read about CasaOS and Umbrel, and appreciate the UI and app selection but I might still be limited in terms of app availability - for instance I could not host a personal blog there.</p> <p>Thank you for sharing your thoughts and experiences!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/checofox"> /u/checofox </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea895u/just_got_a_raspberry_pi_4_i_want_to_use_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea895u/just_got_a_raspberry_pi_4_i_want_to_use_to/">[comments]</a></span>

## Is there a list of open source software without limitations?
 - [https://www.reddit.com/r/selfhosted/comments/1ea86zp/is_there_a_list_of_open_source_software_without](https://www.reddit.com/r/selfhosted/comments/1ea86zp/is_there_a_list_of_open_source_software_without)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T13:44:15+00:00

<!-- SC_OFF --><div class="md"><p>I know there are lists such as <a href="https://github.com/awesome-selfhosted/awesome-selfhosted">awesome self-hosted</a> of software you can self-host and which is open source.</p> <p>However, many of those tools are in practice <strong>open core</strong> and place limits on the open-source/free variants.</p> <p>Are there any lists of open source, self-hostable tools which do not impose <em>any</em> limits on self-hosting for free?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dandydev"> /u/dandydev </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea86zp/is_there_a_list_of_open_source_software_without/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea86zp/is_there_a_list_of_open_source_software_without/">[comments]</a></span>

## Best way to watch our phone gallery pics and videos on smart TV?
 - [https://www.reddit.com/r/selfhosted/comments/1ea703v/best_way_to_watch_our_phone_gallery_pics_and](https://www.reddit.com/r/selfhosted/comments/1ea703v/best_way_to_watch_our_phone_gallery_pics_and)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T12:49:11+00:00

<!-- SC_OFF --><div class="md"><p>Hey all!</p> <p>Still a beginner but have managed to have a setup with proxmox and some SSD harddrives. Got Nextcloud lxc automatically uploading all our photos and videos taken from our phones in the family, to these SSD drives. We can check them out with the nextcloud app on our phones or PC.</p> <p>We'd like to watch them together infront of the TV as a family. What are your easy recommendations here? I've only heard about Jellyfin and Plex, but that's about it. Thankful for recommendations on how to do it in the easiest way!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nandeyanen83"> /u/nandeyanen83 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea703v/best_way_to_watch_our_phone_gallery_pics_and/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea703v/best_way_to_watch_our_phone_gallery_pics_and/">[comments]</a></span>

## Is A Celeron J1900 enough for 1080p transcodeing?
 - [https://www.reddit.com/r/selfhosted/comments/1ea5z3t/is_a_celeron_j1900_enough_for_1080p_transcodeing](https://www.reddit.com/r/selfhosted/comments/1ea5z3t/is_a_celeron_j1900_enough_for_1080p_transcodeing)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T11:56:50+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I'm planning to set up a small, low-power media server and could use some advice. I'm considering a 10ZiG 5800q series thin client for this purpose due to its compact size and low power consumption (and price). It comes with a Celeron J1900 processor (4 cores, 4 threads) and 4GB of RAM, and it supports QuickSync. I intend to use Jellyfin, and I'll be the only user. My media is mostly stored on a NAS, in H.264, H.265, and some AV1.</p> <p>Is the Celeron J1900 enough for transcoding a single 1080p stream without stuttering?</p> <p><a href="https://www.intel.com/content/www/us/en/products/sku/78867/intel-celeron-processor-j1900-2m-cache-up-to-2-42-ghz/specifications.html">https://www.intel.com/content/www/us/en/products/sku/78867/intel-celeron-processor-j1900-2m-cache-up-to-2-42-ghz/specifications.html</a></p> <p><a href="https://web.archive.org/web/20201111194524/https://www.10zig.com/application/files/9015/2044/6707/Final_5800q_Seri

## Noob question how to DDNS + reverse Proxy solution
 - [https://www.reddit.com/r/selfhosted/comments/1ea5wzp/noob_question_how_to_ddns_reverse_proxy_solution](https://www.reddit.com/r/selfhosted/comments/1ea5wzp/noob_question_how_to_ddns_reverse_proxy_solution)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T11:53:33+00:00

<!-- SC_OFF --><div class="md"><p>I am self-hosting on a clean Ubuntu 24.04 machine, almost everything is docker-compose files.<br /> After some research I understand that there is two main why to secure your server: revers proxy or VPN. </p> <p>I have an Asus router (AX-56U, Merlin firmware) that updates DDNS and I open ports to some of the services that I want to expose to the world (Immich / Jellfin / .. ).<br /> This setup is working fine without any issues, but I understand that externally open ports are a security risk. </p> <p>I tried to use the nginx proxy manager but had some difficulties. If I understand correctly the Asus DDNS is not supporting subdomain (I could be wrong here).<br /> I tried DuckDNS with nginx proxy manager but the connection was very slow and I feel like I've missed something. </p> <p>Now for the questions:<br /> 1. Could you please share what are you doing in your self-husting setup ?<br /> 2. Could I use my asus DDNS and a local DNS server like techneti

## Introducing Expedite Bridge - A simple encrypted file transfer utility for humans
 - [https://www.reddit.com/r/selfhosted/comments/1ea5fxd/introducing_expedite_bridge_a_simple_encrypted](https://www.reddit.com/r/selfhosted/comments/1ea5fxd/introducing_expedite_bridge_a_simple_encrypted)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T11:26:52+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ea5fxd/introducing_expedite_bridge_a_simple_encrypted/"> <img alt="Introducing Expedite Bridge - A simple encrypted file transfer utility for humans" src="https://b.thumbs.redditmedia.com/ImXdv7tYGyfmzQ59sRw-vAAIk5kyW-36VYVC8yxA8Vo.jpg" title="Introducing Expedite Bridge - A simple encrypted file transfer utility for humans" /> </a> </td><td> <!-- SC_OFF --><div class="md"><h1>What my project does</h1> <p><strong>Expedite Bridge</strong> is a GUI client for <strong>Expedite Service</strong>, a simple encrypted file transfer service (that I published <a href="https://www.reddit.com/r/selfhosted/comments/1dx7slo/introducing_expedite_a_simple_encrypted_file/?utm_source=share&amp;utm_medium=web3x&amp;utm_name=web3xcss&amp;utm_term=1&amp;utm_content=share_button">about</a> around a couple of weeks back). Written in <a href="https://pypi.org/project/PySide6/">PySide6</a>, the builds are provided for GNU/Linux distributi

## Mail archive from cloud accounts
 - [https://www.reddit.com/r/selfhosted/comments/1ea51e2/mail_archive_from_cloud_accounts](https://www.reddit.com/r/selfhosted/comments/1ea51e2/mail_archive_from_cloud_accounts)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T11:03:25+00:00

<!-- SC_OFF --><div class="md"><p>Hello, </p> <p>I was wondering what and how do you archive or keep a copy of your emails from cloud services eg. Gmail, Outlook etc. on your self hosting infrastructure.</p> <p>My thinking is to have automatically download the emails from those services while being able to access them if needed from that on-prem client/server.<br /> I was trying to do so with thunderbird but sometimes the emails are not downloaded fully either images or attachments (I think for attachment s there is an option ) but this I have to have a PC open.</p> <p>My NAS is Sinology and I think it has some type of mail client but have not tested it yet nor have searched further since I though to check what other options there are.</p> <p>Thank you<br /> L</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/leaflock7"> /u/leaflock7 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea51e2/mail_archive_from_cloud_accounts/">[

## I Built SERPChecking.com - a Free SERP Checker Tool
 - [https://www.reddit.com/r/selfhosted/comments/1ea4fb2/i_built_serpcheckingcom_a_free_serp_checker_tool](https://www.reddit.com/r/selfhosted/comments/1ea4fb2/i_built_serpcheckingcom_a_free_serp_checker_tool)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T10:26:50+00:00

<!-- SC_OFF --><div class="md"><p>I created SERP Checking to help analyze search engine results pages (SERPs) from over 230 countries. You can gain insights into Rich Results like Featured Snippets and visualize your potential SERP rankings across desktop and mobile devices. It's perfect for SEO professionals and businesses aiming to enhance their search visibility globally.</p> <p>Key features:</p> <ul> <li>Comprehensive SERP analysis for any keyword</li> <li>Multilingual support for precise local SEO insights</li> <li>Detailed breakdown of the top 100 search results</li> <li>Visualization of actual search results</li> </ul> <p>Try it out at <a href="http://serpchecking.com">serpchecking.com</a> and let me know what you think!</p> <p>And posted on, share me a vote:)</p> <p><a href="https://www.producthunt.com/posts/serp-checking">https://www.producthunt.com/posts/serp-checking</a></p> <p>🔍 Happy SERP checking</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.redd

## I’m looking for a peer to peer service that honestly might not be possible.
 - [https://www.reddit.com/r/selfhosted/comments/1ea48sh/im_looking_for_a_peer_to_peer_service_that](https://www.reddit.com/r/selfhosted/comments/1ea48sh/im_looking_for_a_peer_to_peer_service_that)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T10:15:17+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone. So, for the better part of a couple months now, I’ve been at a loss. My friend and I both have gigabit capable networks. Under the right conditions and on a fast enough server, downloading for either of us can be anywhere from 65 megabytes, too in some cases 125 or greater. But I think that’s with multiple parallel connections. As theoretically that wouldn’t make sense. Here’s my problem though. I do love cloud storage, don’t get me wrong. But there’s sometimes when I just want to send a very large file over to my friend without having to upload it to the cloud storage provider first, then making a link, and then sharing it. And then it’s up to the cloud provider to manage speed and throttling. And if the file is of a certain size, it will get really slow at a certain point. I’m looking for a solution that lets me locally host files. I prefer not to port forward, but tailscale and or wire guard will half the connection speed. So it’s eit

## GetHomepage Question
 - [https://www.reddit.com/r/selfhosted/comments/1ea3qja/gethomepage_question](https://www.reddit.com/r/selfhosted/comments/1ea3qja/gethomepage_question)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T09:42:58+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>Does anyone know if it is possible to run homepage on port 80? My goal is to run it without including the port number in the URL, using only the domain name.</p> <p>thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/localhostFR"> /u/localhostFR </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea3qja/gethomepage_question/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea3qja/gethomepage_question/">[comments]</a></span>

## LubeLogger Install
 - [https://www.reddit.com/r/selfhosted/comments/1ea3dbn/lubelogger_install](https://www.reddit.com/r/selfhosted/comments/1ea3dbn/lubelogger_install)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T09:17:48+00:00

<!-- SC_OFF --><div class="md"><p>Has someone installedl LubeLogger recently? I tried to pull the image but it gives me this error: No matching manifest for linux/arm/v7 in the manifest list entries.</p> <p>I've tried uploading the docker file to portainer but i get an error too.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/boogieman444"> /u/boogieman444 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea3dbn/lubelogger_install/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea3dbn/lubelogger_install/">[comments]</a></span>

## Self hosted Online Browser Games
 - [https://www.reddit.com/r/selfhosted/comments/1ea3963/self_hosted_online_browser_games](https://www.reddit.com/r/selfhosted/comments/1ea3963/self_hosted_online_browser_games)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T09:10:06+00:00

<!-- SC_OFF --><div class="md"><p>I'm looking for some fun self hosted Online Browser Games to host and play with friends. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/marcozrules"> /u/marcozrules </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea3963/self_hosted_online_browser_games/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea3963/self_hosted_online_browser_games/">[comments]</a></span>

## Best secure choice to start a self-hosting server on RaspberryPi5 easily
 - [https://www.reddit.com/r/selfhosted/comments/1ea37zb/best_secure_choice_to_start_a_selfhosting_server](https://www.reddit.com/r/selfhosted/comments/1ea37zb/best_secure_choice_to_start_a_selfhosting_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T09:07:52+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys, first post here. I have bought a Raspberry Pi 5 intended to be used as a self-hosting server for many things/services. And I'm kinda new to this all. I have read this past week for several resources, forums and subreddits about many options (you all probably know about): <a href="https://umbrel.com/umbrelos">UmbrelOS</a>, <a href="https://casaos.io/">CasaOS</a>, <a href="https://runtipi.io/">RunTiPi</a>, <a href="https://cosmos-cloud.io/">Cosmos</a>... all based on docker apps.</p> <p>I am not too concerned about security within the local network, but it is true that the more secure the better. My concern is mainly to have access outside the local network.</p> <p>I intend to have some services for local use (media servers, web stacks for web development, etc) and to have others that although I usually use them locally (nextcloud, owncloud, etc) from time to time are used outside my local network to share a link or a folder with friends or fam

## Photo evaluator / rate my photo?
 - [https://www.reddit.com/r/selfhosted/comments/1ea379k/photo_evaluator_rate_my_photo](https://www.reddit.com/r/selfhosted/comments/1ea379k/photo_evaluator_rate_my_photo)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T09:06:27+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a self hosted solution to rate my large photo library by AI. I currently use synology photos on my NAS, have checked out imich as an option (if it comes out of beta) and a few others.</p> <p>What I am looking for is a way to automate the star rating in photos by having a process running which evaluates photo quality using ai (lighting, focus, people with closed eyes, etc). I would use it's results to update the photos star rating and use that in my photo DAM tool of choice (currently synology photos). I know of cloud tools that rate photos, but I would prefer to host this myself.</p> <p>Ideas on what to use?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/brupgmding"> /u/brupgmding </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea379k/photo_evaluator_rate_my_photo/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea379k/photo_evaluato

## Paperless-ngx on Docker Desktop with Cloudflare Tunnel - CSRF Verification Failed (Error 403) and Email Pull Issues
 - [https://www.reddit.com/r/selfhosted/comments/1ea2cc5/paperlessngx_on_docker_desktop_with_cloudflare](https://www.reddit.com/r/selfhosted/comments/1ea2cc5/paperlessngx_on_docker_desktop_with_cloudflare)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T08:08:13+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I'm currently running Paperless-ngx on Docker Desktop installed on Windows, using the WSL2 engine. I've set up Paperless-ngx to run behind a Cloudflare tunnel. While I can access the website, I'm encountering a couple of issues:</p> <ol> <li>When I enter the username and password, I get an error 403 with a message saying &quot;CSRF verification failed.&quot;</li> <li>The email pull functionality is not working. Everything is set up but it's not pulling docs from my email.</li> </ol> <p>I've tried searching for solutions, but haven't had any luck so far. Has anyone encountered similar issues or have any suggestions on how to resolve these problems? Any help would be greatly appreciated!</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bigfootdoexist"> /u/bigfootdoexist </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea2cc5/paperlessngx_on_docker

## Alternative to Grafana+InfluxDB
 - [https://www.reddit.com/r/selfhosted/comments/1ea22jm/alternative_to_grafanainfluxdb](https://www.reddit.com/r/selfhosted/comments/1ea22jm/alternative_to_grafanainfluxdb)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T07:49:57+00:00

<!-- SC_OFF --><div class="md"><p>I would like to dith Grafana and Influxdb since it uses too much resources and the changes in the influx-syntax is a nightmare. </p> <p>What I would like to monitor: CPU usage of nodes, power usage of my TP-Link smart meters, some SNMP stuff and the most crucial part: which LXC/VM of my Proxmox host uses which resources (CPU, RAM, Bandwith). </p> <p>I would like to monitor several nodes and I would like to create my own &quot;dashboard&quot;. </p> <p>What would you recommend? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/niemand112233"> /u/niemand112233 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea22jm/alternative_to_grafanainfluxdb/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea22jm/alternative_to_grafanainfluxdb/">[comments]</a></span>

## Self-hosted Calendar with option to view statistics?
 - [https://www.reddit.com/r/selfhosted/comments/1ea20xr/selfhosted_calendar_with_option_to_view_statistics](https://www.reddit.com/r/selfhosted/comments/1ea20xr/selfhosted_calendar_with_option_to_view_statistics)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T07:46:52+00:00

<!-- SC_OFF --><div class="md"><p>I am currently using Synology Calendar and it works great. I made a plan now to also track my time spent. Initially, I went with Google Sheet (I know, I am not totally degoogled yet) but it becomes annoying as I needed to duplicate the events and managing in 2 places. </p> <p>All I want is a chart that show how much time I spent (according to my calendar) at work, sleep, activities, etc. I found that the Calendar app is way more appropriate to manage this, but I will write what is in my head here, so I can get another solution that can work without a dedicated app (I am thinking to pulling data in to display in Grafana or writing a script).</p> <p>My dream workflow is:</p> <ul> <li><p>Plan for a day with tasks. Each task has a &quot;tag&quot; or some way to categorize in the stat.</p></li> <li><p>End of day, I will correct the calendar with all the tasks and time I actually spent.</p></li> <li><p>As soon as a task is edited, the chart should adjust.</

## Captive portal solution with social sign in
 - [https://www.reddit.com/r/selfhosted/comments/1ea1v22/captive_portal_solution_with_social_sign_in](https://www.reddit.com/r/selfhosted/comments/1ea1v22/captive_portal_solution_with_social_sign_in)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T07:36:08+00:00

<!-- SC_OFF --><div class="md"><p>Hi Guys,</p> <p>I'm trying to find a package that's free/opensource that will allow me to set up a captive portal that supports social signin/vouchers/user-password logins.</p> <p>Preferably something that talks WISPr, but open to traditional portals.</p> <p>Anyone have some leads?</p> <p>This is for a favour for a friend who owns a small hotel, so looking to try save a bit of $ for him if i can - while helping sort his guest wifi situation.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/WraytheZ"> /u/WraytheZ </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea1v22/captive_portal_solution_with_social_sign_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea1v22/captive_portal_solution_with_social_sign_in/">[comments]</a></span>

## Docker application local host access it as https.
 - [https://www.reddit.com/r/selfhosted/comments/1ea0sbb/docker_application_local_host_access_it_as_https](https://www.reddit.com/r/selfhosted/comments/1ea0sbb/docker_application_local_host_access_it_as_https)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T06:25:18+00:00

<!-- SC_OFF --><div class="md"><p>Hello, </p> <p>I have an application running locally on docker.I access it localhost:port when I access it from my phone using my PC's ip I cannot access camera on that application because &quot;Camera access is only permitted in secure context. Use HTTPS or localhost rather than HTTP&quot;.</p> <p>What can I do?<br /> Thank you in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sdouze"> /u/Sdouze </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea0sbb/docker_application_local_host_access_it_as_https/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea0sbb/docker_application_local_host_access_it_as_https/">[comments]</a></span>

## Help Needed: Deluge Container Can't Connect to Gluetun VPN in Docker Setup
 - [https://www.reddit.com/r/selfhosted/comments/1ea0cw6/help_needed_deluge_container_cant_connect_to](https://www.reddit.com/r/selfhosted/comments/1ea0cw6/help_needed_deluge_container_cant_connect_to)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T05:57:25+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ea0cw6/help_needed_deluge_container_cant_connect_to/"> <img alt="Help Needed: Deluge Container Can't Connect to Gluetun VPN in Docker Setup" src="https://b.thumbs.redditmedia.com/xQuScK5ZHIDSmTlNlEX1mD3JJ6NHlBJW7LMbo-jRl2Q.jpg" title="Help Needed: Deluge Container Can't Connect to Gluetun VPN in Docker Setup" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey guys, im lost. I’m having trouble with my Docker setup where the deluge container cannot connect to the gluetun VPN container. I’m using Docker Compose to manage both containers, but despite being on the same network, deluge fails to communicate with gluetun and shows a “Unable to connect to daemon” error in the logs.</p> <p><a href="https://preview.redd.it/55otlrock7ed1.png?width=1099&amp;format=png&amp;auto=webp&amp;s=fb09e5aa826cb5b888c63abd8c2f709e3e16a111">https://preview.redd.it/55otlrock7ed1.png?width=1099&amp;format=png&amp;auto=webp&amp;s=fb09e5

## Mass domain monitoring and management
 - [https://www.reddit.com/r/selfhosted/comments/1ea00lk/mass_domain_monitoring_and_management](https://www.reddit.com/r/selfhosted/comments/1ea00lk/mass_domain_monitoring_and_management)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T05:35:38+00:00

<!-- SC_OFF --><div class="md"><p>I am searching for a domain monitoring software that allows to monitor (and maybe manage) hundreds of domains for a company. A lot of the domains are only registered/claimed to prevent fraud with them.</p> <p>The software is not required to do the actual work at the registrar (it would be really nice if it could do that, but it's not mandatory). Currently, multiple registars are used because not all of them support every TLD.</p> <p>The DNS zones of the most used domains is hosted by cloudflare. So some kind of cloudflare registration would be nice.</p> <p>If there is no self-hosted that can handle this, I would appreciate any suggetions for a SaaS provider.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/spigandromeda"> /u/spigandromeda </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ea00lk/mass_domain_monitoring_and_management/">[link]</a></span> &#32; <span><a href="https://www.reddit.

## is there a good self-hosted photo sharing program?
 - [https://www.reddit.com/r/selfhosted/comments/1e9yzff/is_there_a_good_selfhosted_photo_sharing_program](https://www.reddit.com/r/selfhosted/comments/1e9yzff/is_there_a_good_selfhosted_photo_sharing_program)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T04:31:53+00:00

<!-- SC_OFF --><div class="md"><p>I'm a photographer and I have a butt load of photos on my 2tb drive. I was wondering if there is a light-weight, ui friendly, android and windows/Linux program that let's me share photos between the two (android and computer). something similar like plex, where it's light and looks decent.</p> <p>requirements: -can't use docker because I'm a newbie and I don't wanna learn that stuff right now -can't use docker because it's too heavy for normal background use -can't use more than 200mb of ram -free</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/upsidedown_aifamgepj"> /u/upsidedown_aifamgepj </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e9yzff/is_there_a_good_selfhosted_photo_sharing_program/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e9yzff/is_there_a_good_selfhosted_photo_sharing_program/">[comments]</a></span>

## Little Help Required with KeepAlived config for AdguardHome Redundancy
 - [https://www.reddit.com/r/selfhosted/comments/1e9yvh0/little_help_required_with_keepalived_config_for](https://www.reddit.com/r/selfhosted/comments/1e9yvh0/little_help_required_with_keepalived_config_for)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T04:25:25+00:00

<!-- SC_OFF --><div class="md"><p>I wanna use Keepalived to ensure that when my AdguardHome (AGH1) Docker container which is on Docker Macvlan with IP 192.168.1.128 is not available when pinged, it should switch over to AdguardHome(AGH2) Docker container which is on Docker Macvlan with IP 192.168.1.130. </p> <p>Adguard Home(AGH1) with IP <a href="http://192.168.1.128">192.168.1.128</a> is on Host <a href="http://192.168.1.2">192.168.1.2</a> with interface br0.<br /> Adguard Home(AGH2) with IP <a href="http://192.168.1.130">192.168.1.130</a> is on Host <a href="http://192.168.1.3">192.168.1.3</a> with interface br0.</p> <p>I am a noob at keepalived. So I am able to figureout how to switch keepalived Virtual IP when host <a href="http://192.168.1.2">192.168.1.2</a> goes down to a backup, but I want it in a way that not only host but even when only the container <a href="http://192.168.1.128">192.168.1.128</a> is not reachable, it should switch over to backup.</p> </div><!-- SC_ON --> &#

## Anyone running seafile behing nginx proxy manager on docker
 - [https://www.reddit.com/r/selfhosted/comments/1e9yuqn/anyone_running_seafile_behing_nginx_proxy_manager](https://www.reddit.com/r/selfhosted/comments/1e9yuqn/anyone_running_seafile_behing_nginx_proxy_manager)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T04:24:15+00:00

<!-- SC_OFF --><div class="md"><p>hey all ,</p> <p>running into the CSRF issue but i have the &quot;CSRF_TRUSTED_ORIGINS=[’ https mydomain . com '] defined in env and its available as exported var to container .. apparently thats the way to fix it but doesnt work for me.</p> <p>cheers</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ZeusRahman"> /u/ZeusRahman </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e9yuqn/anyone_running_seafile_behing_nginx_proxy_manager/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e9yuqn/anyone_running_seafile_behing_nginx_proxy_manager/">[comments]</a></span>

## Secure access to an internal server without root
 - [https://www.reddit.com/r/selfhosted/comments/1e9yncg/secure_access_to_an_internal_server_without_root](https://www.reddit.com/r/selfhosted/comments/1e9yncg/secure_access_to_an_internal_server_without_root)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T04:12:31+00:00

<!-- SC_OFF --><div class="md"><p>TL;DR: We have an internal server A that can only be reached from within private network, but can access the internet (though no sudo privileges). For remote collaboration, we want to setup so that external machines B and C can also access A. </p> <p>Ideally, I am trying to setup such that only &quot;B and C&quot; can access A from the outside, without relying on third-party services. I am thinking of IP restrictions and key-based authentications. We do not have any spare server, so I try to make do with what I can on A that requires minimal efforts on B and C's sides.</p> <p>Methods that I have tried:</p> <ul> <li><p>ngrok: easy setup, usable, but slow connection (tested) and expose to third party -&gt; NG</p></li> <li><p>cloudflared: requires sudo on A -&gt; NG</p></li> <li><p>tailscale/headscale/wireguard: requires sudo on A -&gt; NG</p></li> <li><p><a href="https://github.com/fatedier/frp">frp</a>: I looked up a bit and seemed like reverse proxy w

## 2 Factor VPN with Unifi
 - [https://www.reddit.com/r/selfhosted/comments/1e9y6rf/2_factor_vpn_with_unifi](https://www.reddit.com/r/selfhosted/comments/1e9y6rf/2_factor_vpn_with_unifi)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T03:47:23+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I asked this questions over at <a href="/r/Ubiquiti">r/Ubiquiti</a> and never got any response. Hoping someone here might be able to help out? As with all my research i have still come up at a brick wall here.</p> <p>I have setup a Unifi Cloud Gateway Ultra with a Self-hosted Radius server and OpenVPN. The Open VPN is using the Radius Server users for connection and have a few questions which I have at this stage failed to find any answers to.</p> <p>All these questions are in context of using the Unifi Radius Server and VPN Host.</p> <p>Can you set up Wiregaurd to use the Radius server like OpenVPN?</p> <p>Is there a way to set up 2 Factor Authentication with the Radius server and or OpenVPN?</p> <p>At the moment it seems that when a user accesses the OpenVPN route it doesn't use the Radius Servers assignment rules to assign them to a V-lan.<br /> Some of my Radius user get assigned to a V-Lan which have restricted access to other devic

## Port 25 is blocked but I can receive emails.
 - [https://www.reddit.com/r/selfhosted/comments/1e9wxza/port_25_is_blocked_but_i_can_receive_emails](https://www.reddit.com/r/selfhosted/comments/1e9wxza/port_25_is_blocked_but_i_can_receive_emails)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T02:41:26+00:00

<!-- SC_OFF --><div class="md"><p>Oracle Free Tier port 25 is blocked but I can still receive emails from gmail and outlook. What is the deal? Am I receiving emails on port 465 or 587?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/whiteh4cker"> /u/whiteh4cker </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e9wxza/port_25_is_blocked_but_i_can_receive_emails/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e9wxza/port_25_is_blocked_but_i_can_receive_emails/">[comments]</a></span>

## Looking for help on self hosting a office suite for myself.
 - [https://www.reddit.com/r/selfhosted/comments/1e9wo23/looking_for_help_on_self_hosting_a_office_suite](https://www.reddit.com/r/selfhosted/comments/1e9wo23/looking_for_help_on_self_hosting_a_office_suite)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T02:28:01+00:00

<!-- SC_OFF --><div class="md"><p>The normal first paragraph speile incoming, i'm trying to de-googling myself as much as possible.</p> <p>Here is my setup, running Unraid and basically only familiar with installing dockers from the apps store from there.</p> <p>I've tried nextcloud and it's okay, it's pretty slow and I have a bunch of issues installing it, but eventually got it working, then I realized that ... It's way to heavy for my needs, all I want is basically the google suite of apps, so something like onlyoffice so I can edit my documents and sheets, those are the primary 2 big ones that I really need working.</p> <p>The issue is that I have had some insane problems trying to get onlyoffice to work. Followed every single step I've found, redone and rebuilt but I always get stuck on trying to connect the mysql-&gt;documents server-&gt;community server.</p> <p>So, i'm looking for alternatives OR! If someone is able to help me with this.<br /> I want it to be a really simple pag

## All Systems Down
 - [https://www.reddit.com/r/selfhosted/comments/1e9w5wz/all_systems_down](https://www.reddit.com/r/selfhosted/comments/1e9w5wz/all_systems_down)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T02:03:25+00:00

<!-- SC_OFF --><div class="md"><p>I've been halfway around the world from my servers. They ran fine for 11 days. Went offline last night. I don't get back for another 9 days. I feel so lost and disconnected. Help me.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/vkapadia"> /u/vkapadia </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e9w5wz/all_systems_down/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e9w5wz/all_systems_down/">[comments]</a></span>

## Noted.lol down. Hoping this is temporary?
 - [https://www.reddit.com/r/selfhosted/comments/1e9w0rz/notedlol_down_hoping_this_is_temporary](https://www.reddit.com/r/selfhosted/comments/1e9w0rz/notedlol_down_hoping_this_is_temporary)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T01:56:47+00:00

<!-- SC_OFF --><div class="md"><p>Just noticed that <a href="http://noted.lol">noted.lol</a> is down. Anyone know if this is just maintenance or something more serious?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sottey"> /u/sottey </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e9w0rz/notedlol_down_hoping_this_is_temporary/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e9w0rz/notedlol_down_hoping_this_is_temporary/">[comments]</a></span>

## Hosting download site for friends — ways to speed up download times?
 - [https://www.reddit.com/r/selfhosted/comments/1e9vtdo/hosting_download_site_for_friends_ways_to_speed](https://www.reddit.com/r/selfhosted/comments/1e9vtdo/hosting_download_site_for_friends_ways_to_speed)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T01:46:55+00:00

<!-- SC_OFF --><div class="md"><p>Hello, </p> <p>I'm hosting a website so I can easily share large downloads with my friends without having to go through the trouble of signing up for services, worrying about expiring links, etc. Unfortunately, the download speeds are slow — for reference, a 1.5 GB file takes about an hour to download.</p> <p>I'm hosting this on an old Thinkpad T420 with a HDD. Is bad hardware the bottleneck here? Would installing an SDD make a difference (I'm a total tech dilettante, so maybe that's a dumb question)? Thank you.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Visual-Patient-6691"> /u/Visual-Patient-6691 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e9vtdo/hosting_download_site_for_friends_ways_to_speed/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e9vtdo/hosting_download_site_for_friends_ways_to_speed/">[comments]</a></span>

## Would you use an automated authelia setup gui? (Photos for mockup representation)
 - [https://www.reddit.com/r/selfhosted/comments/1e9vr0c/would_you_use_an_automated_authelia_setup_gui](https://www.reddit.com/r/selfhosted/comments/1e9vr0c/would_you_use_an_automated_authelia_setup_gui)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T01:43:48+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1e9vr0c/would_you_use_an_automated_authelia_setup_gui/"> <img alt="Would you use an automated authelia setup gui? (Photos for mockup representation)" src="https://b.thumbs.redditmedia.com/OjxCY7UR1gH0yepmRLdaYpE75dOu1tOONeZ2AKKo3Lc.jpg" title="Would you use an automated authelia setup gui? (Photos for mockup representation)" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BelugaBilliam"> /u/BelugaBilliam </a> <br /> <span><a href="https://www.reddit.com/gallery/1e9vr0c">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e9vr0c/would_you_use_an_automated_authelia_setup_gui/">[comments]</a></span> </td></tr></table>

## Hosting Widevine L1 (DRM) Video
 - [https://www.reddit.com/r/selfhosted/comments/1e9tkis/hosting_widevine_l1_drm_video](https://www.reddit.com/r/selfhosted/comments/1e9tkis/hosting_widevine_l1_drm_video)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-23T00:00:36+00:00

<!-- SC_OFF --><div class="md"><p>Hey there!</p> <p>I am now using VDOCipher and their absurd prices, I didn't know self-hosting was an option.</p> <p>I am not talking about strictly self-hosting, AWS is enough.</p> <p>1) How do I get the keys? Widevine website is super vague and doesn't point anywhere for getting started, or am I missing something?</p> <p>2) How how do I encrypt the video? is it a one time thing (ergo S3 sufficient), or per-view encryption? GPT points me towards Shaka Packager, is it fine?</p> <p>3) How can I ensure it is L1 proper and doesn't fall back to some L1 without me knowing about it?</p> <p>Thanks a lot.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OriGumy"> /u/OriGumy </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e9tkis/hosting_widevine_l1_drm_video/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e9tkis/hosting_widevine_l1_drm_video/">[comments]</a></

