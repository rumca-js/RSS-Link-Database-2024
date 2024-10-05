# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Introducing Scriberr - Self-hosted AI Transcription
 - [https://www.reddit.com/r/selfhosted/comments/1fwcgvr/introducing_scriberr_selfhosted_ai_transcription](https://www.reddit.com/r/selfhosted/comments/1fwcgvr/introducing_scriberr_selfhosted_ai_transcription)
 - RSS feed: $source
 - date published: 2024-10-04T23:06:58+00:00

<!-- SC_OFF --><div class="md"><h2>Intro</h2> <p>Scriberr is a self-hostable AI audio transcription app. Scriberr uses the open-source <a href="https://github.com/openai/whisper">Whisper</a> models from OpenAI, to transcribe audio files locally on your hardware. It uses the <a href="https://github.com/ggerganov/whisper.cpp">Whisper.cpp</a> high-performance inference engine for OpenAI&#39;s Whisper. Scriberr also allows you to summarize transcripts using OpenAI&#39;s ChatGPT API, with your own custom prompts. Scriberr is and will always be open source. Checkout the repository <a href="https://github.com/rishikanthc/Scriberr">here</a></p> <h2>Why</h2> <p>I recently started using Plaud Note and found it to be very productive to take notes in audio and have them transcribed, summarized and exported into my notes. The problem was Plaud has a subscription model for Whisper transcription that got expensive quickly. I couldn&#39;t justify paying so much when the model is open-sourced. Hence I

## Wireguard Mesh - Help :'(
 - [https://www.reddit.com/r/selfhosted/comments/1fwcc7m/wireguard_mesh_help](https://www.reddit.com/r/selfhosted/comments/1fwcc7m/wireguard_mesh_help)
 - RSS feed: $source
 - date published: 2024-10-04T23:00:47+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been contemplating switching away from tailscale to a pure wireguard set up..</p> <p>I&#39;ve been playing with WG-MESHCONF (<a href="https://github.com/k4yt3x/wg-meshconf">https://github.com/k4yt3x/wg-meshconf</a>) which is great.. and as a result i have config files that enable my 3 sites to talk to each other... </p> <p>The step I&#39;m missing is how to integrate my laptop into the mix..</p> <p>I need a config that will allow me to connect into the mesh and let me access all 3 sites.. but without my laptop having to have an endpoint address.. as well.. it wont have an exposed entry point wherever I am... (does that make sense?)</p> <p>If i add in an entry for my laptop with a made up endpoint.. then the everything fails to connect... (obviously)...</p> <p>To use their own image and inject my laptop : <a href="http://share.d4nm3d.co.uk/u/N95fSK.png">http://share.d4nm3d.co.uk/u/N95fSK.png</a></p> <p>Do i just generate all the configs... and

## Uptime-Kuma and ntfy on Same Host and Non-Standard Ports
 - [https://www.reddit.com/r/selfhosted/comments/1fwbkz1/uptimekuma_and_ntfy_on_same_host_and_nonstandard](https://www.reddit.com/r/selfhosted/comments/1fwbkz1/uptimekuma_and_ntfy_on_same_host_and_nonstandard)
 - RSS feed: $source
 - date published: 2024-10-04T22:24:26+00:00

<!-- SC_OFF --><div class="md"><p>The title is a great summary of what I&#39;m trying to get at here. I have -- on a single host -- both ntfy and Uptime-Kuma containers running, one of each. Both are using non-standard external ports (though I doubt it matters at all for the Uptime-Kuma container). When I try to set up ntfy notification alert rule, it tells me that it fails, and often gives an &quot;ETIMEOUT&quot; log. Can anyone help with this?</p> <p>As a tangential question, I searched for but couldn&#39;t find anything related to increasing the log verbosity of the default Uptime-Kuma container. I&#39;d really appreciate a pointer there, too.</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Senkyou"> /u/Senkyou </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fwbkz1/uptimekuma_and_ntfy_on_same_host_and_nonstandard/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fwbkz1

## Any good and cheap hosting providers you recommend?
 - [https://www.reddit.com/r/selfhosted/comments/1fwaphq/any_good_and_cheap_hosting_providers_you_recommend](https://www.reddit.com/r/selfhosted/comments/1fwaphq/any_good_and_cheap_hosting_providers_you_recommend)
 - RSS feed: $source
 - date published: 2024-10-04T21:44:42+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! I&#39;m in the process of setting up a website for my insurance agency, and I’m looking for some hosting recommendations. I want something affordable but reliable, with good performance and support. I’ve looked into a few options like Hostinger, but I’m curious to hear your experiences or suggestions for other providers. I also think digital ocean may be a good option as well but I don&#39;t want to regret any purchases. </p> <p>Also** I don&#39;t plan on coding the site myself, i plan on using wordpress cms. </p> <p>Here’s what I’m looking for:</p> <ul> <li>Cost-effective plans</li> <li>Ability to handle a small-to-medium-sized business website</li> <li>WordPress compatibility</li> <li>Free SSL and email setup would be great</li> <li>Ideally, something that allows for easy scalability if the site grows</li> </ul> <p>Any thoughts or recommendations on what might work best for me? Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitte

## Seeking Advice: Setting Up a Hybrid Environment to Run Linux and Windows Jobs Concurrently on a Single Machine
 - [https://www.reddit.com/r/selfhosted/comments/1fwa078/seeking_advice_setting_up_a_hybrid_environment_to](https://www.reddit.com/r/selfhosted/comments/1fwa078/seeking_advice_setting_up_a_hybrid_environment_to)
 - RSS feed: $source
 - date published: 2024-10-04T21:13:56+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I’ve currently been tasked with setting up a hybrid environment on my single machine to run both Linux and Windows jobs concurrently as Github self hosted runners, and I would love some advice or pointers from this community.</p> <p>My Setup Plan:</p> <pre><code>• Docker Desktop with WSL2 to run Linux containers within a Windows host • Or alternatively, using Proxmox (or another virtualization platform) to set up both nodes (Linux and Windows) running simultaneously • Kubernetes to manage and orchestrate these jobs • GitHub Action Runner Controller to handle the job executions </code></pre> <p>This is what I’ve come to after only a my primitive understanding and a little bit of research. I’d love for someone who’s faced this problem before to help me out or advise me on what I could do. </p> <p>I have full access to the machine and I can utilise it however I want. The specs for the machine are: 12th Gen Core i7 64GB RAM 2TB SSD </

## Best financial institutions to receive card payments.
 - [https://www.reddit.com/r/selfhosted/comments/1fw99fa/best_financial_institutions_to_receive_card](https://www.reddit.com/r/selfhosted/comments/1fw99fa/best_financial_institutions_to_receive_card)
 - RSS feed: $source
 - date published: 2024-10-04T20:41:29+00:00

<!-- SC_OFF --><div class="md"><p>Hi, there!</p> <p>I am a small business. I find Stripe debit card payments extremely expensive. So, I would like to ask you if you can suggest me other systems to receive my card payments for my business and I would like that their fees are extremely minimal or if possible that these fees do not exist? Are there others that will charge me less than Stripe please?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/richardsonoge"> /u/richardsonoge </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw99fa/best_financial_institutions_to_receive_card/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw99fa/best_financial_institutions_to_receive_card/">[comments]</a></span>

## Github Pages with forgejo and dns name
 - [https://www.reddit.com/r/selfhosted/comments/1fw8ri0/github_pages_with_forgejo_and_dns_name](https://www.reddit.com/r/selfhosted/comments/1fw8ri0/github_pages_with_forgejo_and_dns_name)
 - RSS feed: $source
 - date published: 2024-10-04T20:19:26+00:00

<!-- SC_OFF --><div class="md"><p>I have been using github pages to host articles using Jekyll.</p> <p>Now that I have forgejo, I am searching for a way to get the same behavior: On push publish the markdown content as a new article in my blog.</p> <p>I have forgejo behind an nginx reverse proxy. I plan to use the same reverse proxy for my personal Jekyll blog.</p> <p>I am thinking of writing the pipeline by hand. Before starting I wanted to know if someone has another way then implementing from scratch.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/D4kzy"> /u/D4kzy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw8ri0/github_pages_with_forgejo_and_dns_name/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw8ri0/github_pages_with_forgejo_and_dns_name/">[comments]</a></span>

## Local URLs don't work on Android, but work on Linux
 - [https://www.reddit.com/r/selfhosted/comments/1fw8rih/local_urls_dont_work_on_android_but_work_on_linux](https://www.reddit.com/r/selfhosted/comments/1fw8rih/local_urls_dont_work_on_android_but_work_on_linux)
 - RSS feed: $source
 - date published: 2024-10-04T20:19:26+00:00

<!-- SC_OFF --><div class="md"><h1>TL;DR:</h1> <p>Android devices in my household cannot resolve URLs pointing to my LAN, although desktop machines can.</p> <h1>My setup</h1> <p>On the LAN, I want to access services running on my homeserver through nice URLs, not through IPs and port numbers. For instance, instead of accessing my Jellyfin instance through 192.168.178.100:8096, I want to type jellyfin.mylan.duckdns.org. Also, I want to encrypt any traffic to and from those services with valid SSL certs (not self-signed ones). This is what I&#39;ve done to implement this:</p> <ol> <li>Registered a dynDNS subdomain (mylan.duckdns.org) that points to a <em>local</em> IP (192.168.178.100), not my router&#39;s external IP.</li> <li>Set up an instance of nginx proxy manager that is listening on ports 80 and 443 of that very IP.</li> <li>(Using npm) Registered a wildcard SSL certificate for *.mylan.duckdns.org.</li> <li>Set up proxy rules to redirect traffic for (e.g.) jellyfin.mylan.duckdns.

## selfhosted printshop or manufacturing job workflow tracker
 - [https://www.reddit.com/r/selfhosted/comments/1fw8n0o/selfhosted_printshop_or_manufacturing_job](https://www.reddit.com/r/selfhosted/comments/1fw8n0o/selfhosted_printshop_or_manufacturing_job)
 - RSS feed: $source
 - date published: 2024-10-04T20:13:52+00:00

<!-- SC_OFF --><div class="md"><p>is anyone aware of a selfhosted printshop or manufacturing job workflow tracker I&#39;m trying to find something but not having much luck</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ill-Wishbone-4240"> /u/Ill-Wishbone-4240 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw8n0o/selfhosted_printshop_or_manufacturing_job/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw8n0o/selfhosted_printshop_or_manufacturing_job/">[comments]</a></span>

## ZeroTier and exposing services
 - [https://www.reddit.com/r/selfhosted/comments/1fw7wb8/zerotier_and_exposing_services](https://www.reddit.com/r/selfhosted/comments/1fw7wb8/zerotier_and_exposing_services)
 - RSS feed: $source
 - date published: 2024-10-04T19:41:37+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fw7wb8/zerotier_and_exposing_services/"> <img src="https://b.thumbs.redditmedia.com/6_G13gkLUK8cSj8yr4ysIsEZ5G-ADyj-VTAtre7pJyc.jpg" alt="ZeroTier and exposing services" title="ZeroTier and exposing services" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>i want to host some gaming servers for my friends and myself, but i algo want to have external access to other servives running on my server since i do some programming and mobile development. i dont want my friends to have access to things like Portainer and Adminer, so i separeted 2 instances of ZeroTier like this.</p> <p>Black: private zone<br/> Red: public zone<br/> green: internal zone</p> <p>ZeroTier has a version for linux, docker, windows and mobile, that is why i&#39;m thinking on using it. </p> <p>Is this a good layout? what can i do better?</p> <p><a href="https://preview.redd.it/iiz4g82qkssd1.png?width=622&amp;format=png&amp;auto=webp&amp;s=3f3ad

## Wiki like database
 - [https://www.reddit.com/r/selfhosted/comments/1fw7v84/wiki_like_database](https://www.reddit.com/r/selfhosted/comments/1fw7v84/wiki_like_database)
 - RSS feed: $source
 - date published: 2024-10-04T19:40:21+00:00

<!-- SC_OFF --><div class="md"><p>Hello! I&#39;m starting to gather everything to set up my server, but I need help pinpointing a software. The goal is to have something self hosted that will work as a database for a ttrpgs setting. This would have all the rules, world info, etc. Some things I would like to have: - user permissions on a page level, so that I can unlock information as it&#39;s learned on a group, or individual level. - a place to create tickets for things to be added or edited - templates - comment sections on pages - ability for my players to upload notes. </p> <p>Most wikis have almost all of this, but I&#39;m having a hard time finding one with the user permissions. Any thoughts?</p> <p>Editing to add, I was looking at obsidian.md, but I couldn&#39;t find an easy way to host it in a way that I wanted. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/celtictempestwaves"> /u/celtictempestwaves </a> <br/> <span><a href="https://ww

## Gaming + homeserver AIO. (Proxmox)
 - [https://www.reddit.com/r/selfhosted/comments/1fw7qqh/gaming_homeserver_aio_proxmox](https://www.reddit.com/r/selfhosted/comments/1fw7qqh/gaming_homeserver_aio_proxmox)
 - RSS feed: $source
 - date published: 2024-10-04T19:34:46+00:00

<!-- SC_OFF --><div class="md"><p>Hello guys! Hope you&#39;re all great. </p> <p>I have a question!</p> <p>Its possible to game and host a gaming machine on the same RIG?</p> <p>Using proxmox and passing the GPU? </p> <p>THX</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/not_reninja_"> /u/not_reninja_ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw7qqh/gaming_homeserver_aio_proxmox/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw7qqh/gaming_homeserver_aio_proxmox/">[comments]</a></span>

## I finally finished my Homepage Dashboard setup.
 - [https://www.reddit.com/r/selfhosted/comments/1fw67hm/i_finally_finished_my_homepage_dashboard_setup](https://www.reddit.com/r/selfhosted/comments/1fw67hm/i_finally_finished_my_homepage_dashboard_setup)
 - RSS feed: $source
 - date published: 2024-10-04T18:29:05+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fw67hm/i_finally_finished_my_homepage_dashboard_setup/"> <img src="https://preview.redd.it/t59jiih19ssd1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=4dfeddba2b1cc0ba64332a5216f5307b2a84a83a" alt="I finally finished my Homepage Dashboard setup." title="I finally finished my Homepage Dashboard setup." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Flip1900"> /u/Flip1900 </a> <br/> <span><a href="https://i.redd.it/t59jiih19ssd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw67hm/i_finally_finished_my_homepage_dashboard_setup/">[comments]</a></span> </td></tr></table>

## Came back from vacation and now I can’t access any of my local servers through Firefox
 - [https://www.reddit.com/r/selfhosted/comments/1fw5wxe/came_back_from_vacation_and_now_i_cant_access_any](https://www.reddit.com/r/selfhosted/comments/1fw5wxe/came_back_from_vacation_and_now_i_cant_access_any)
 - RSS feed: $source
 - date published: 2024-10-04T18:16:28+00:00

<!-- SC_OFF --><div class="md"><p>Not sure what’s happening here, but resorting to this community because I can’t find what I thought would be a simple answer on google. I can’t access any of my local servers on Firefox, but I can through Safari. Not sure what happened, but if anyone knows what to do here would appreciate the help. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/edmonddantesofficial"> /u/edmonddantesofficial </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw5wxe/came_back_from_vacation_and_now_i_cant_access_any/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw5wxe/came_back_from_vacation_and_now_i_cant_access_any/">[comments]</a></span>

## CasaOS without a certificate
 - [https://www.reddit.com/r/selfhosted/comments/1fw5jlv/casaos_without_a_certificate](https://www.reddit.com/r/selfhosted/comments/1fw5jlv/casaos_without_a_certificate)
 - RSS feed: $source
 - date published: 2024-10-04T18:01:03+00:00

<!-- SC_OFF --><div class="md"><p>I have been running a jellyfin media server for over a year now. I recently realized I wanted to be able to remotely view and monitor some things from a nice dashboard, and came across CasaOS. I installed it and a few programs with the dashboard interface but have now run into the issue that my main domain, let&#39;s call it `example.com` is secure and has a certificate, however, `example.com:81` does not have a certificate, and that&#39;s the port that CasaOS is being served on.</p> <p>How can I apply the certificate to the port being used by CasaOS? I am using certbot (letsencrypt) and nginx for the certificate to the main domain, and that seems to have worked properly. I am unsure how to proceed with this, any help would be greatly appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AStrangeCharacter"> /u/AStrangeCharacter </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw5jlv/

## Personal Information Removal Tracker Service
 - [https://www.reddit.com/r/selfhosted/comments/1fw5itb/personal_information_removal_tracker_service](https://www.reddit.com/r/selfhosted/comments/1fw5itb/personal_information_removal_tracker_service)
 - RSS feed: $source
 - date published: 2024-10-04T18:00:14+00:00

<!-- SC_OFF --><div class="md"><p>Hi fellow selfhosters,</p> <p>I&#39;m wondering if anyone knows of a self-hosted or FOSS solution for tracking <a href="https://www.pcmag.com/picks/the-best-personal-data-removal-services">personal information removal</a> requests? I did a quick search but didn&#39;t find anything, so I thought I&#39;d ask here.</p> <p>If there isn’t a FOSS/self-hosted alternative to the paid services out there, would anyone be interested in brainstorming how we could get one started?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tigrayt2"> /u/tigrayt2 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw5itb/personal_information_removal_tracker_service/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw5itb/personal_information_removal_tracker_service/">[comments]</a></span>

## Best Co-Location Facility Near San Fernando Valley
 - [https://www.reddit.com/r/selfhosted/comments/1fw5036/best_colocation_facility_near_san_fernando_valley](https://www.reddit.com/r/selfhosted/comments/1fw5036/best_colocation_facility_near_san_fernando_valley)
 - RSS feed: $source
 - date published: 2024-10-04T17:38:04+00:00

<!-- SC_OFF --><div class="md"><p>A lot of fellow SelfHosters here admit they selfhosted for data ownership and privacy.</p> <p>I intend to deploy my own Ethereum full node using the Reth (Rust Ethereum) software at a colocation facility.</p> <p>I think its better if the full node runs on my own hardware. The real reason why I want to do colocation instead</p> <p>of a VPS is so I can check up on the facility and interview the people that manage the facility in-person.</p> <p>That&#39;s important to check if you can trust them with your hardware. I leave near the San Fernando Valley</p> <p>area. What colocation facilities would you recommend? I have heard of <a href="http://365main.com">365main.com</a> as well as Equinix?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/fosres"> /u/fosres </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw5036/best_colocation_facility_near_san_fernando_valley/">[link]</a></span> &#32; <span><

## Lower resolution/disk for movies/series in Jellyfin/Sonarr/Radart
 - [https://www.reddit.com/r/selfhosted/comments/1fw4nzh/lower_resolutiondisk_for_moviesseries_in](https://www.reddit.com/r/selfhosted/comments/1fw4nzh/lower_resolutiondisk_for_moviesseries_in)
 - RSS feed: $source
 - date published: 2024-10-04T17:23:36+00:00

<!-- SC_OFF --><div class="md"><p>My disk is filling up. Some movies or episodes fills up like 1-5 GB per hour flog playtime.</p> <p>Wondering if there is a easy automatic way to lower the resolution and disk usage of these to spare the disk.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hackermarks"> /u/hackermarks </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw4nzh/lower_resolutiondisk_for_moviesseries_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw4nzh/lower_resolutiondisk_for_moviesseries_in/">[comments]</a></span>

## Cryptreboot 3.0.1 Released with Native ZFS Encryption Support
 - [https://www.reddit.com/r/selfhosted/comments/1fw4jqt/cryptreboot_301_released_with_native_zfs](https://www.reddit.com/r/selfhosted/comments/1fw4jqt/cryptreboot_301_released_with_native_zfs)
 - RSS feed: $source
 - date published: 2024-10-04T17:18:28+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve released a new version of cryptreboot, an MIT-licensed, drop-in reboot replacement for disk-encrypted Linux systems.</p> <p>The tool prompts for the passphrase before reboot, while the system is still fully operational and remotely accessible. This contrasts with a standard reboot, where the passphrase must be entered during early system initialization, often without network access.</p> <p>This version adds support for native ZFS encryption with a LUKS keystore (as implemented in Ubuntu) and continues to support classic, plain-LUKS encryption.</p> <p>No configuration is required—simply install the tool and use &quot;cryptreboot&quot; instead of &quot;reboot.&quot; It also integrates smoothly with Dropbear-enabled initramfs configurations, allowing cryptreboot to function as usual. For standard reboots or system power-ons, the disk can be unlocked remotely via SSH.</p> <p>To install on Ubuntu and display usage:</p> <pre><code>sudo apt install 

## Alternative to Harvest Time Tracker?
 - [https://www.reddit.com/r/selfhosted/comments/1fw3z9c/alternative_to_harvest_time_tracker](https://www.reddit.com/r/selfhosted/comments/1fw3z9c/alternative_to_harvest_time_tracker)
 - RSS feed: $source
 - date published: 2024-10-04T16:54:34+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve seen Kimai and even ledger but they&#39;re both a little more overhead than the basic timetracking I use. I use timers for multiple clients and multiple projects, and at the end of the month I use reports grouped by client to invoice. </p> <p>It has a mac status bar widget that lets me start a timer and stop it, or add in eg. 20 minutes. That&#39;s pretty much all I use. </p> <p>If I need to login to something and start a timer I&#39;ll forget. Is there anything like this out there?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/williambobbins"> /u/williambobbins </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw3z9c/alternative_to_harvest_time_tracker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw3z9c/alternative_to_harvest_time_tracker/">[comments]</a></span>

## Options for streaming RTSP to YouTube
 - [https://www.reddit.com/r/selfhosted/comments/1fw32l7/options_for_streaming_rtsp_to_youtube](https://www.reddit.com/r/selfhosted/comments/1fw32l7/options_for_streaming_rtsp_to_youtube)
 - RSS feed: $source
 - date published: 2024-10-04T16:16:35+00:00

<!-- SC_OFF --><div class="md"><p>I have been looking for better solutions to stream more than 13 RTSP camera feeds to YouTube with a png overlay, either RTMP or HLS. Currently using OBS, which is working ok, just a very complicated setup to automate at this scale. Right now I am the point of needing to upgrade to a different server, since I am restrained by a proprietary PSU and the age of the platform. I am also restrained by limitations of OBS not quite fitting this use case in terms of resource usage. As much as I&#39;ve fine-tuned what I can, the scene rendering is my biggest issue with OBS. Even with multiple GPUs, the scene rendering will use the primary, while you can select which one to encode. At this point I&#39;ve found ways around it, but it raises other issues.</p> <p>I have used WOWZA in the past, but now the pricing ($195/month) doesn&#39;t make sense for my use case. It does scale much better, but setup and things like image overlays are much more complicated than say

## Question About SSL and DNS-01
 - [https://www.reddit.com/r/selfhosted/comments/1fw31oz/question_about_ssl_and_dns01](https://www.reddit.com/r/selfhosted/comments/1fw31oz/question_about_ssl_and_dns01)
 - RSS feed: $source
 - date published: 2024-10-04T16:15:34+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I have a question about requesting SSL certificates using the DNS-01 challenge method. My current DNS provider, from whom I purchased the domain, does not offer an API. Can I switch to a different DNS provider, like Cloudflare, which I believe supports an API? If so, can I then use NPM to request a wildcard SSL certificate using the DNS-01 challenge?</p> <p>Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/madloggan"> /u/madloggan </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw31oz/question_about_ssl_and_dns01/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw31oz/question_about_ssl_and_dns01/">[comments]</a></span>

## Is it possible to self host DDNS for a reolink system that only gives me NO-IP and DynDNS options (but I can define the server)?
 - [https://www.reddit.com/r/selfhosted/comments/1fw3142/is_it_possible_to_self_host_ddns_for_a_reolink](https://www.reddit.com/r/selfhosted/comments/1fw3142/is_it_possible_to_self_host_ddns_for_a_reolink)
 - RSS feed: $source
 - date published: 2024-10-04T16:14:53+00:00

<!-- SC_OFF --><div class="md"><p>I have a couple of Linux boxes hosted separately that have static IPs that I&#39;m hoping to use to manage the DDNS. The Reolink system is currently using NO-IP, but I see that I can specify the server. I&#39;m getting annoyed by having the re-confirm it every month, so I&#39;m wondering if there is any software that allows me to run my own DDNS using either the NO-IP or DynDNS APIs?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lindymad"> /u/lindymad </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw3142/is_it_possible_to_self_host_ddns_for_a_reolink/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw3142/is_it_possible_to_self_host_ddns_for_a_reolink/">[comments]</a></span>

## Optimize Homeserver
 - [https://www.reddit.com/r/selfhosted/comments/1fw2x4x/optimize_homeserver](https://www.reddit.com/r/selfhosted/comments/1fw2x4x/optimize_homeserver)
 - RSS feed: $source
 - date published: 2024-10-04T16:10:22+00:00

<!-- SC_OFF --><div class="md"><p>Hey Guys, </p> <p>I recently set up my homeserver and I&#39;m quite proud of it. I&#39;m using fedora Server and Podman containers throguh docker-compose, which is greatly efficient but my Containers are all on my BTRFS 1c3 Ironwolf 4tb HDD, which makes them work all the time. I have built this all on an amd 2600x (will upgrade someday to 5900x) and an rx 6600 (for LLM and Jellyfin).</p> <p>My Container list contains Jellyfin, Nextcloud, Ollama/WebUI, Home Assistant (for my RPi Data in InfluxDB of my solar power), Caddy with a Caddyfile for my Domain, Pi-Hole (Will switch to Adguard) and some other little projects.</p> <p>As said, my HDDs work 24/7, the draw lays between 40 to 70 W in idle and loading times, especially for the first requests to my AI (Mistral Nemo 12b q4, Qwen 2.5 7b) are really bad until its all loaded up fully.</p> <p>Now I&#39;m wondering, on this server are of course some very precious files to me like my CV and certificates, that

## Homepage.dev header config
 - [https://www.reddit.com/r/selfhosted/comments/1fw2qjh/homepagedev_header_config](https://www.reddit.com/r/selfhosted/comments/1fw2qjh/homepagedev_header_config)
 - RSS feed: $source
 - date published: 2024-10-04T16:02:47+00:00

<!-- SC_OFF --><div class="md"><p>Does anyone know how to get rid of the search bar and the time in the header? can i also see the computer resources of another server on my network in the header? the docs arent really clear for header config</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/shareef946"> /u/shareef946 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw2qjh/homepagedev_header_config/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw2qjh/homepagedev_header_config/">[comments]</a></span>

## Self-hosted RTMP proxy?
 - [https://www.reddit.com/r/selfhosted/comments/1fw2bmr/selfhosted_rtmp_proxy](https://www.reddit.com/r/selfhosted/comments/1fw2bmr/selfhosted_rtmp_proxy)
 - RSS feed: $source
 - date published: 2024-10-04T15:45:28+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a solution that will allow me to broadcast via RTMP to a server, and then that server will send it to YouTube, Twitch or PeerTube via RTMP.</p> <p>I know that there are services that allow you to stream for free on YouTube and Twitch, but I don&#39;t think any of them allow RTMP for free, and only PeerTube supports it.</p> <p>For the price they want for RTMP support, I have a month or even two of hosting under PeerTube.</p> <p>The only one I could find was nginx-rtmp-module <a href="https://github.com/arut/nginx-rtmp-module">https://github.com/arut/nginx-rtmp-module</a></p> <p>And a ready-made docker <a href="https://hub.docker.com/r/kukielka/nginx-rtmp-ffmpeg/">https://hub.docker.com/r/kukielka/nginx-rtmp-ffmpeg/</a></p> <p>Over the years, nothing newer or better has come out, I don&#39;t know?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FormProfessional2616"> /u/FormProfessional2616 </a>

## Is there a self-hosted recipe sharing software?
 - [https://www.reddit.com/r/selfhosted/comments/1fw1od9/is_there_a_selfhosted_recipe_sharing_software](https://www.reddit.com/r/selfhosted/comments/1fw1od9/is_there_a_selfhosted_recipe_sharing_software)
 - RSS feed: $source
 - date published: 2024-10-04T15:18:11+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a way to share my recipes with others on my own server. I&#39;ve looked at a lot of the options on the Self Hosted Awesome site and they all seem to be tailored to household use, not publication.</p> <p>I&#39;d really like any recommendations for this. I guess worst case I could use Wordpress, but I&#39;m hoping that there&#39;s something a bit better out there.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/vertybird"> /u/vertybird </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw1od9/is_there_a_selfhosted_recipe_sharing_software/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw1od9/is_there_a_selfhosted_recipe_sharing_software/">[comments]</a></span>

## Local DNS resolver for haproxy?
 - [https://www.reddit.com/r/selfhosted/comments/1fw13b2/local_dns_resolver_for_haproxy](https://www.reddit.com/r/selfhosted/comments/1fw13b2/local_dns_resolver_for_haproxy)
 - RSS feed: $source
 - date published: 2024-10-04T14:54:02+00:00

<!-- SC_OFF --><div class="md"><p>My aim is to be able to cover my whole network with ssl certificates with haproxy + lets encrypt and I habe been trying to set this up for a long time without having success. </p> <p>Please bear with me and allow me to ask this perhaps stupid question. I have done my reading and a LOT of research about domain records but I&#39;m still unsure where to point a wildcard record for certificates using haproxy on pfsense. Mostly because of the firewall configuration and fear to expose anything to the public. </p> <p>I guest I&#39;m not sure if I should input the IP local DNS resolver of pfsense for this wildcard and for local only access. For obvious reasons I don&#39;t want to expose anything to the public and this is why I really need some advice here for this. Thanks. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Great-Question-1567"> /u/Great-Question-1567 </a> <br/> <span><a href="https://www.reddit.com/r/selfh

## Any guides on how to set up a Jellyfin server, a NextCloud server, a NAS, and a Minecraft server all on one machine?
 - [https://www.reddit.com/r/selfhosted/comments/1fw0p24/any_guides_on_how_to_set_up_a_jellyfin_server_a](https://www.reddit.com/r/selfhosted/comments/1fw0p24/any_guides_on_how_to_set_up_a_jellyfin_server_a)
 - RSS feed: $source
 - date published: 2024-10-04T14:37:20+00:00

<!-- SC_OFF --><div class="md"><p>This is probably a really frequently asked question, so PLEASE link another post answering it (if there is one). I couldn&#39;t find any, although it may just be Reddit search or DuckDuckGo.</p> <p>Server specs: i7700 32GB DDR4 RAM 1tb NVME 8tb HDD.</p> <p>That&#39;s it, thanks so much in advance! Also, if I&#39;m fundamentally misunderstanding something about how all this stuff works, please correct me.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Comfortable_Good8860"> /u/Comfortable_Good8860 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw0p24/any_guides_on_how_to_set_up_a_jellyfin_server_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fw0p24/any_guides_on_how_to_set_up_a_jellyfin_server_a/">[comments]</a></span>

## Creating a amazing SaaS for Indiehackers, Open Source, allow Self-host and seeking for more feedback
 - [https://www.reddit.com/r/selfhosted/comments/1fw0mn4/creating_a_amazing_saas_for_indiehackers_open](https://www.reddit.com/r/selfhosted/comments/1fw0mn4/creating_a_amazing_saas_for_indiehackers_open)
 - RSS feed: $source
 - date published: 2024-10-04T14:34:22+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fw0mn4/creating_a_amazing_saas_for_indiehackers_open/"> <img src="https://external-preview.redd.it/gyvHe7txrhgPTU6Pi_gwfWx2yuDvr8LDDo-rLEUOyuo.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=691e60888c423609443f650a2676f412d2cc378a" alt="Creating a amazing SaaS for Indiehackers, Open Source, allow Self-host and seeking for more feedback" title="Creating a amazing SaaS for Indiehackers, Open Source, allow Self-host and seeking for more feedback" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>As an indiehacker, I know what an indiehacker needs.</p> <p>So I created Tianji</p> <p><a href="https://preview.redd.it/stdfig1v4rsd1.png?width=2572&amp;format=png&amp;auto=webp&amp;s=7d1aa4e01cf8b5ef94092f02541daa943770a1d9">https://preview.redd.it/stdfig1v4rsd1.png?width=2572&amp;format=png&amp;auto=webp&amp;s=7d1aa4e01cf8b5ef94092f02541daa943770a1d9</a></p> <p><a href="https://tianji.msgbyte.com/">https://tianji.msgbyt

## nginx reverse proxy + DDNS + port forwarding (on rounter/modem) + SSL + ufw-docker
 - [https://www.reddit.com/r/selfhosted/comments/1fw04ra/nginx_reverse_proxy_ddns_port_forwarding_on](https://www.reddit.com/r/selfhosted/comments/1fw04ra/nginx_reverse_proxy_ddns_port_forwarding_on)
 - RSS feed: $source
 - date published: 2024-10-04T14:12:31+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m not sure what part I did wrong. But I can&#39;t access my WEKAN(snap) and MEMOS(docker)</p> <p>I&#39;m completely a newbie, studied biotech and has no coding background.</p> <p>illustrated site names for memos and wekan are <a href="http://memos.XXXXX.com"><em>memos.XXXXX.com</em></a> and <a href="http://wekan.XXXXX.com"><em>wekan.XXXXX.com</em></a></p> <p>What I Did</p> <h1>Nginx</h1> <ul> <li>put all configs in /etc/nginx/sites-available/default</li> <li>in that default file I configured</li> </ul> <p>:80 --&gt; return 301 https --&gt; :443 --&gt; got all ssl certs keys from let&#39;s encrypt and well configured and certs keys of each site in their own folders --&gt; proxy_pass memos http://localhost:5230 and wekan http://localhost:3001</p> <p>* I used literally &quot;localhost&quot; in the proxy_pass since I&#39;m not sure if it should be my <em>external IP/domain</em> or <em>my internal IP</em></p> <p>Note that I tried different expression

## Best way to make Paperless NGX und Nextcloud securely available for not technically affine people
 - [https://www.reddit.com/r/selfhosted/comments/1fvysqm/best_way_to_make_paperless_ngx_und_nextcloud](https://www.reddit.com/r/selfhosted/comments/1fvysqm/best_way_to_make_paperless_ngx_und_nextcloud)
 - RSS feed: $source
 - date published: 2024-10-04T13:11:46+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I need to make Paperless NGX and Nextcloud available for some not technically affine people (parents ;) ) to make some tax documents etc. available.</p> <p>As these are some sensitive documents (e.g. contracts, etc.) the access should be as secure as possible. However, I cannot use WireGuard (they wouldn&#39;t want any additional software to be installed on their PC).</p> <p>Also, I would like to use the same credentials for Nextcloud and Paperless NGX, so I&#39;m thinking to use something like Authentik.</p> <p>Any recommendations?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Simplixt"> /u/Simplixt </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvysqm/best_way_to_make_paperless_ngx_und_nextcloud/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvysqm/best_way_to_make_paperless_ngx_und_nextcloud/">[comments]</a></span>

## Universal Link for self hosted services
 - [https://www.reddit.com/r/selfhosted/comments/1fvyd1f/universal_link_for_self_hosted_services](https://www.reddit.com/r/selfhosted/comments/1fvyd1f/universal_link_for_self_hosted_services)
 - RSS feed: $source
 - date published: 2024-10-04T12:50:28+00:00

<!-- SC_OFF --><div class="md"><p>A few weeks ago I presented my self hosted recipe management app “FlavorMate”. Since then I implemented a few new functions and the next one I want to address is deep linking. I know how to set up “universal links” or “app links” for a static url but with self hosting everyone has a different url.</p> <p>I could host a little page that does nothing but opening the app or redirecting to the self hosted web app if the app is not installed on the device. The downsides are that I can possibly see your requests (although turning off logging would be fixing this) and it would be dependent on my service. If I shut this page, down deep linking would be broken.</p> <p>Maybe someone here had the same problem and can explain how they did it.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Chip3211"> /u/Chip3211 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvyd1f/universal_link_for_self_hosted_serv

## Sounds stupid but I’m looking for a 3.5“ HDD USB case - without any buttons
 - [https://www.reddit.com/r/selfhosted/comments/1fvxqn3/sounds_stupid_but_im_looking_for_a_35_hdd_usb](https://www.reddit.com/r/selfhosted/comments/1fvxqn3/sounds_stupid_but_im_looking_for_a_35_hdd_usb)
 - RSS feed: $source
 - date published: 2024-10-04T12:17:34+00:00

<!-- SC_OFF --><div class="md"><p>Hi, As the title says I’m looking for a good and inexpensive case for my new 3.5“ HDD. I can only use USB A 3.0 von my Intel NUC.</p> <p>I ordered 4 different cases on Amazon but all had those buttons to turn on the drive. So when the server needs to restart, I always need to turn on the HDD manually. This is really annoying.</p> <p>Do you guys have an recommendation?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Jannomag"> /u/Jannomag </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvxqn3/sounds_stupid_but_im_looking_for_a_35_hdd_usb/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvxqn3/sounds_stupid_but_im_looking_for_a_35_hdd_usb/">[comments]</a></span>

## This Week in Self-Hosted (4 October 2024)
 - [https://www.reddit.com/r/selfhosted/comments/1fvxbsg/this_week_in_selfhosted_4_october_2024](https://www.reddit.com/r/selfhosted/comments/1fvxbsg/this_week_in_selfhosted_4_october_2024)
 - RSS feed: $source
 - date published: 2024-10-04T11:55:17+00:00

<!-- SC_OFF --><div class="md"><p>Happy Friday, <a href="/r/selfhosted">r/selfhosted</a>! Linked below is the latest edition of <em>This Week in Self-Hosted</em>, a weekly newsletter recap of the latest activity in self-hosted software.</p> <p>This week covers beta releases for <a href="https://blog.thunderbird.net/2024/09/help-us-test-the-thunderbird-for-android-beta/?ref=selfh.st">Thunderbird mobile</a> and <a href="https://borgbackup.readthedocs.io/en/2.0.0b11/changes.html?ref=selfh.st#version-2-0-0b11-2024-09-26">Borg Backup rclone support</a>, new software launches (many generated by this community!), <a href="https://selfh.st/apps">directory additions</a>, and a spotlight on <a href="https://github.com/fredrikburmester/streamyfin?ref=selfh.st">Streamyfin</a> - a simple and user-friendly mobile Jellyfin client with a ton of features.</p> <hr/> <p><a href="https://selfh.st/newsletter/2024-10-04/?ref=reddit">This Week in Self-Hosted (10 October 2024)</a></p> </div><!-- SC_ON --> &#

## compose-backupdate 1.0 🐳 - Simple tool for creating scheduled backups, and performing (backed-up) manual updates on Docker compose stacks
 - [https://www.reddit.com/r/selfhosted/comments/1fvx3ry/composebackupdate_10_simple_tool_for_creating](https://www.reddit.com/r/selfhosted/comments/1fvx3ry/composebackupdate_10_simple_tool_for_creating)
 - RSS feed: $source
 - date published: 2024-10-04T11:42:44+00:00

<!-- SC_OFF --><div class="md"><p>Repo: <a href="https://github.com/hazzuk/compose-backupdate">https://github.com/hazzuk/compose-backupdate</a></p> <h1>Problems with Docker backups</h1> <p>I currently run my Docker containers inside a virtual machine, and whilst I do create daily backups. I&#39;m only creating a backup of the entire VM. Which I&#39;ve never been fully satisfied with for two reasons:</p> <ol> <li>Any time I would need to restore a single Docker container, I would have to restore all of them at once.</li> <li>I&#39;ve often thought it would be best practice to try and make backups of my containers before I apply updates to them. As that is the most likely time that something goes wrong.</li> </ol> <p>During my search for a solution I found this <a href="https://www.reddit.com/r/selfhosted/comments/18k1scz/backup_software_for_docker_volumes_and_bind_mounts/">Reddit post</a>. Which shared some similar grievances with the tools I had so far found.</p> <ul> <li><strong>Stan

## Cheap vGPU solution
 - [https://www.reddit.com/r/selfhosted/comments/1fvwz8d/cheap_vgpu_solution](https://www.reddit.com/r/selfhosted/comments/1fvwz8d/cheap_vgpu_solution)
 - RSS feed: $source
 - date published: 2024-10-04T11:35:06+00:00

<!-- SC_OFF --><div class="md"><p>Is there a cheap way to do virtual GPUs? I hear Intel GPUs have virtualization features on the enterprise version, and that you might be able to flash a consumer model to the enterprise/server BIOS. I also hear there is something you can do with some NVIDIA cards.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/inevitabledeath3"> /u/inevitabledeath3 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvwz8d/cheap_vgpu_solution/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvwz8d/cheap_vgpu_solution/">[comments]</a></span>

## Require help with cloudflare tunnel
 - [https://www.reddit.com/r/selfhosted/comments/1fvwyyv/require_help_with_cloudflare_tunnel](https://www.reddit.com/r/selfhosted/comments/1fvwyyv/require_help_with_cloudflare_tunnel)
 - RSS feed: $source
 - date published: 2024-10-04T11:34:40+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fvwyyv/require_help_with_cloudflare_tunnel/"> <img src="https://b.thumbs.redditmedia.com/2hC4OZwqH95a7WFefcWK-q7b23qtZGIZmwnwBY9ZSZQ.jpg" alt="Require help with cloudflare tunnel" title="Require help with cloudflare tunnel" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/artj4lf27qsd1.png?width=1582&amp;format=png&amp;auto=webp&amp;s=411015fe4aec8f905bcae4c36346a375a9228ebc">https://preview.redd.it/artj4lf27qsd1.png?width=1582&amp;format=png&amp;auto=webp&amp;s=411015fe4aec8f905bcae4c36346a375a9228ebc</a></p> <p><a href="https://preview.redd.it/yc7jg5r27qsd1.png?width=1043&amp;format=png&amp;auto=webp&amp;s=0ba7fe26cb810676fae38c51ce0ac6df37de198a">https://preview.redd.it/yc7jg5r27qsd1.png?width=1043&amp;format=png&amp;auto=webp&amp;s=0ba7fe26cb810676fae38c51ce0ac6df37de198a</a></p> <p><a href="https://preview.redd.it/jjwcj7d37qsd1.png?width=294&amp;format=png&amp;auto=webp&amp

## Keep up with tech
 - [https://www.reddit.com/r/selfhosted/comments/1fvw9w8/keep_up_with_tech](https://www.reddit.com/r/selfhosted/comments/1fvw9w8/keep_up_with_tech)
 - RSS feed: $source
 - date published: 2024-10-04T10:51:52+00:00

<!-- SC_OFF --><div class="md"><p>Hi how do you guys keep up with the latest tech news and stufff?</p> <p>I&#39;m generall interested in news surrounding everything in IT.</p> <p>I&#39;ve heard good stuff about TL;DR newsletter, but after having it for one moth plus, it feels to me like it&#39;s just featuring openai EVERY day, then some apple sprinkled here and there and elon/spacex, it feels like just those topics are written about. Id love a newsletter that has some varieting content, like occasionally covering things like cybersecurity....</p> <p>Thanks for any suggestions and your opinion on tldr newsletter</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dapper-Inspector-675"> /u/Dapper-Inspector-675 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvw9w8/keep_up_with_tech/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvw9w8/keep_up_with_tech/">[comments]</a></span>

## A question for me as a newbie for making a personal home server with Ubuntu Server LTS
 - [https://www.reddit.com/r/selfhosted/comments/1fvvu96/a_question_for_me_as_a_newbie_for_making_a](https://www.reddit.com/r/selfhosted/comments/1fvvu96/a_question_for_me_as_a_newbie_for_making_a)
 - RSS feed: $source
 - date published: 2024-10-04T10:22:33+00:00

<!-- SC_OFF --><div class="md"><p>I was planning to repurpose an old PC at home as a gateway itself also dhcp, hosting with apache2, Git (Gitea/Forgejo), FTP, SSH, and DNS (bind9). Sort of like a multipurpose server that didn&#39;t connected to the outside internet for saving my projects as an NAS with more functions.</p> <p>But I often broke the installation at the end, I planned to use Debian before but because it&#39;s requiring package mirror and stuffs, I move to Ubuntu Server LTS latest. But the problem is: I don&#39;t know to host Gitea/Forgejo on the subdomain. My main domain is kai(.)net, but even the domain don&#39;t work at all. So I must access to the homepage with the IP which is inconvenient for me, I think I also messed up the configurations with bind9. </p> <p>This is my first time on making a home server on Linux, so I need the guidances from the experienced ones here. I just want to use Linux as the server because of SSH and some utilities that are not exist on Micro

## Spotify self hosted alternative with media suggestion
 - [https://www.reddit.com/r/selfhosted/comments/1fvvi08/spotify_self_hosted_alternative_with_media](https://www.reddit.com/r/selfhosted/comments/1fvvi08/spotify_self_hosted_alternative_with_media)
 - RSS feed: $source
 - date published: 2024-10-04T09:58:57+00:00

<!-- SC_OFF --><div class="md"><p>Hi, i know im beating a dead horse but i know jack sh*t about this stuff when it comes to music. Im looking for a self hosted spotify like Navidrome (in conjuction with lidarr im guessing), but i need it to have a media suggester like spotify does and a way to import my listening preferences from spotify. Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Klevixhani"> /u/Klevixhani </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvvi08/spotify_self_hosted_alternative_with_media/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvvi08/spotify_self_hosted_alternative_with_media/">[comments]</a></span>

## The safe way to make Portainer Internet accessib
 - [https://www.reddit.com/r/selfhosted/comments/1fvutt4/the_safe_way_to_make_portainer_internet_accessib](https://www.reddit.com/r/selfhosted/comments/1fvutt4/the_safe_way_to_make_portainer_internet_accessib)
 - RSS feed: $source
 - date published: 2024-10-04T09:08:23+00:00

<!-- SC_OFF --><div class="md"><p>A colleague just wrote this blog on accessing Portainer with BrowZer, our &#39;clientless&#39; endpoint for OpenZiti, the open source zero trust network project we both work on. I believe Portainer is used a lot in this sub so I hope some people find it interesting.</p> <p>TL:DR; it explains why Portainer is an exceptionally privileged piece of software, it introduces some solutions to access it today - port forwarding, IP whitelisting, VPNs, and proxies - as well as the drawbacks for each. It then introduces BrowZer and demonstrates how easy it is to use with Portainer, and the benefits which are achieved including no need to expose ports or mess with port forwarding, ACLs, install VPNs, and that it works from any device with a browser. </p> <p>In a nutshell, BrowZer provides a public SaaS app experience (no need to load client, mess with DNS, just log into your IdP) while the end application stays in a completely private network with no inbound port

## DHH just released a Kamal 2.0 YT video
 - [https://www.reddit.com/r/selfhosted/comments/1fvu3ri/dhh_just_released_a_kamal_20_yt_video](https://www.reddit.com/r/selfhosted/comments/1fvu3ri/dhh_just_released_a_kamal_20_yt_video)
 - RSS feed: $source
 - date published: 2024-10-04T08:12:14+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://world.hey.com/dhh/kamal-2-thou-need-not-paas-c9e8bd53">https://world.hey.com/dhh/kamal-2-thou-need-not-paas-c9e8bd53</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CheapCamera1579"> /u/CheapCamera1579 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvu3ri/dhh_just_released_a_kamal_20_yt_video/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvu3ri/dhh_just_released_a_kamal_20_yt_video/">[comments]</a></span>

## Mealie client setup
 - [https://www.reddit.com/r/selfhosted/comments/1fvtyur/mealie_client_setup](https://www.reddit.com/r/selfhosted/comments/1fvtyur/mealie_client_setup)
 - RSS feed: $source
 - date published: 2024-10-04T08:01:27+00:00

<!-- SC_OFF --><div class="md"><p>I am thinking of building an ios client for mealie. However, how should I set the connection process? Is it possible to let people login to mealie to ask for a handshake with this client, just like with Google stuff? Or should I ask users to fill in both their hosted url plus bearer token? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jeroenishere12"> /u/jeroenishere12 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvtyur/mealie_client_setup/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvtyur/mealie_client_setup/">[comments]</a></span>

## Where to start?
 - [https://www.reddit.com/r/selfhosted/comments/1fvtb04/where_to_start](https://www.reddit.com/r/selfhosted/comments/1fvtb04/where_to_start)
 - RSS feed: $source
 - date published: 2024-10-04T07:09:15+00:00

<!-- SC_OFF --><div class="md"><p>Backstory. This morning, someone tried to break into my home, so I would like to install security cameras. My questions start here: for some time, I have been thinking about making a home server that would have sensors (for smoke, or maybe something else), and if possible, functionalities for data storing and sharing on a local network, maybe also music streaming, etc. And now I would like to add CCTV functionality to all that. Is that possible to do on one server, which OS to use?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Used-Championship666"> /u/Used-Championship666 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvtb04/where_to_start/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvtb04/where_to_start/">[comments]</a></span>

## Recommendations- For a web based (simple)To Do List system?
 - [https://www.reddit.com/r/selfhosted/comments/1fvt3yg/recommendations_for_a_web_based_simpleto_do_list](https://www.reddit.com/r/selfhosted/comments/1fvt3yg/recommendations_for_a_web_based_simpleto_do_list)
 - RSS feed: $source
 - date published: 2024-10-04T06:54:40+00:00

<!-- SC_OFF --><div class="md"><p>Can any recommend a simple html / web based to do list system. Ideally that can run as an lxc/ct in proxmox.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ByteSmith17"> /u/ByteSmith17 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvt3yg/recommendations_for_a_web_based_simpleto_do_list/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvt3yg/recommendations_for_a_web_based_simpleto_do_list/">[comments]</a></span>

## Any way to guarantee continued control of a domain name?
 - [https://www.reddit.com/r/selfhosted/comments/1fvsqay/any_way_to_guarantee_continued_control_of_a](https://www.reddit.com/r/selfhosted/comments/1fvsqay/any_way_to_guarantee_continued_control_of_a)
 - RSS feed: $source
 - date published: 2024-10-04T06:26:33+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m registering a domain name to use for an email address and want to factor everything to avoid getting locked out of my account. I&#39;m taking into consideration the domain registrar deleting the domain, or terminating my account (I&#39;m not doing anything suspicious but I want to account for that possibility).<br/> Is it possible to register a domain directly with the registry to cut out the registrar? The TLD I want is controlled by CentralNIC in this case.<br/> Am I being overly paranoid? How do others handle this? If something happens to the domain name, for some services it can be a huge pain in the ass to change the email address away from one that&#39;s not working anymore. I&#39;m trying to avoid that.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/yawara25"> /u/yawara25 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvsqay/any_way_to_guarantee_continued_control_of_a/">[l

## ArsTechnica:Thousands of Linux systems infected by stealthy malware since 2021 (perfctl)
 - [https://www.reddit.com/r/selfhosted/comments/1fvrpve/arstechnicathousands_of_linux_systems_infected_by](https://www.reddit.com/r/selfhosted/comments/1fvrpve/arstechnicathousands_of_linux_systems_infected_by)
 - RSS feed: $source
 - date published: 2024-10-04T05:15:04+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://arstechnica.com/security/2024/10/persistent-stealthy-linux-malware-has-infected-thousands-since-2021/">https://arstechnica.com/security/2024/10/persistent-stealthy-linux-malware-has-infected-thousands-since-2021/</a></p> <p><em>The ability to remain installed and undetected makes Perfctl hard to fight.</em> ~ Dan Goodin – 4 Oct 2024 00:42</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/speculatrix"> /u/speculatrix </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvrpve/arstechnicathousands_of_linux_systems_infected_by/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvrpve/arstechnicathousands_of_linux_systems_infected_by/">[comments]</a></span>

## Recommendations to replace Google Voice and ObiHai?
 - [https://www.reddit.com/r/selfhosted/comments/1fvrk7j/recommendations_to_replace_google_voice_and_obihai](https://www.reddit.com/r/selfhosted/comments/1fvrk7j/recommendations_to_replace_google_voice_and_obihai)
 - RSS feed: $source
 - date published: 2024-10-04T05:04:12+00:00

<!-- SC_OFF --><div class="md"><p>(Hope this is OK to post here, as it&#39;s not necessarily self-hosting...)</p> <p>Just wondering if there are recommendations for what to switch to?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jerrobertson"> /u/jerrobertson </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvrk7j/recommendations_to_replace_google_voice_and_obihai/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvrk7j/recommendations_to_replace_google_voice_and_obihai/">[comments]</a></span>

## I made a simple self-hosted subscriptions costs tracker in less than 30 minutes !
 - [https://www.reddit.com/r/selfhosted/comments/1fvqrlr/i_made_a_simple_selfhosted_subscriptions_costs](https://www.reddit.com/r/selfhosted/comments/1fvqrlr/i_made_a_simple_selfhosted_subscriptions_costs)
 - RSS feed: $source
 - date published: 2024-10-04T04:14:02+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fvqrlr/i_made_a_simple_selfhosted_subscriptions_costs/"> <img src="https://preview.redd.it/f6raxvef0osd1.gif?width=640&amp;crop=smart&amp;s=ea605d4be60bc536201a3d48637f43c5607b4785" alt="I made a simple self-hosted subscriptions costs tracker in less than 30 minutes ! " title="I made a simple self-hosted subscriptions costs tracker in less than 30 minutes ! " /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Available-Advice-294"> /u/Available-Advice-294 </a> <br/> <span><a href="https://i.redd.it/f6raxvef0osd1.gif">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvqrlr/i_made_a_simple_selfhosted_subscriptions_costs/">[comments]</a></span> </td></tr></table>

## I feel like I’m so close with Authentik + Traefik + CloudFlare tunnels but I need help on the home stretch
 - [https://www.reddit.com/r/selfhosted/comments/1fvqb0v/i_feel_like_im_so_close_with_authentik_traefik](https://www.reddit.com/r/selfhosted/comments/1fvqb0v/i_feel_like_im_so_close_with_authentik_traefik)
 - RSS feed: $source
 - date published: 2024-10-04T03:47:01+00:00

<!-- SC_OFF --><div class="md"><p>i have been working on adding Authentik to my Traefik reverse proxy, and i feel like i am about 98% of the way there. i am just not sure what else try to grasp this last 2%! </p> <p>Here’s where im at: CloudFlare: CNAME record for domain.com pointed to cf tunnel CNAME record for *.domain.com pointed to domain.com</p> <p>Tunnel is on my docker subnet with sonarr and radarr.</p> <p>Authentic: Sonarr and Radarr have the same forwardauth configs. And I have an app set up for the Unraid GUi.</p> <p>Traefik: works as expected without Authentik. Gets CloudFlare certs. Picks up tags. I started with the Unraid gui, and set it up as an external router, with middleware for Authentik. Works. For sonarr and radarr, I tried to use tags, but could not get them to work. So I tried setting up external routers with Authentik middlewares manually as I did with the Unraid gui, and sonarr works. But I get “not found” page for radarr. </p> <p>I’d be happy to share any of m

## Any FOSS self hosted project management software available
 - [https://www.reddit.com/r/selfhosted/comments/1fvq8dx/any_foss_self_hosted_project_management_software](https://www.reddit.com/r/selfhosted/comments/1fvq8dx/any_foss_self_hosted_project_management_software)
 - RSS feed: $source
 - date published: 2024-10-04T03:42:45+00:00

<!-- SC_OFF --><div class="md"><p>Hi, is there any free and/or Open Source &#39;project management&#39; software that you can self host (optional). I&#39;m in the vfx industry. I think I want something similar to autodesk shotgrid (shotgun previously, now flow or something)</p> <p>Thanks 🙏</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Technical_Flow_1562"> /u/Technical_Flow_1562 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvq8dx/any_foss_self_hosted_project_management_software/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvq8dx/any_foss_self_hosted_project_management_software/">[comments]</a></span>

## Recommendations and advice for using the Oracle free VPS?
 - [https://www.reddit.com/r/selfhosted/comments/1fvpjew/recommendations_and_advice_for_using_the_oracle](https://www.reddit.com/r/selfhosted/comments/1fvpjew/recommendations_and_advice_for_using_the_oracle)
 - RSS feed: $source
 - date published: 2024-10-04T03:03:01+00:00

<!-- SC_OFF --><div class="md"><p>I got the &quot;Always-Free&quot; Oracle VPS (ARM, 4 cores, 24gb of RAM) and upgraded my account to Pay-As-You-Go so they don&#39;t delete it. (If I had to take a guess it&#39;s probably not the best option, but I can&#39;t afford a homeserver.)</p> <p>I have a bunch of questions since I&#39;ve never self-hosted anything outside of game servers. And on this Oracle VPS, I hosted a Minecraft server using Pterodactyl but that&#39;s it.</p> <ol> <li><p>Is the above an acceptable setup at all for hosting stuff? Is there any disclaimers I should know?</p></li> <li><p>What would you recommend I run on it, and <em>how</em>* should I do it? This is what I have my mind on:<br/> =Privacy-focused stuff like a Matrix server for chatting with friends (although having screen-sharing and voice calls is a necessity and I&#39;m not sure if it has that)<br/> =Completely replacing Google Drive (I have photos, docs and sheets there, and a few other miscellaneous files) =I

## Shout out for hands down, the best android app for selfhosting (at least with ubuntu & docker) I have found.
 - [https://www.reddit.com/r/selfhosted/comments/1fvo0p8/shout_out_for_hands_down_the_best_android_app_for](https://www.reddit.com/r/selfhosted/comments/1fvo0p8/shout_out_for_hands_down_the_best_android_app_for)
 - RSS feed: $source
 - date published: 2024-10-04T01:41:29+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://github.com/deskangel/DaRemote">https://github.com/deskangel/DaRemote</a></p> <p>This is THE best fucking ssh/monitoring/docker monitoring/dashboard app I have found yet. Individual Cores stats, docker container controls and stats, ssh, system overview, storage overview including mounted subsystems/drives/raid. </p> <p>I 1p0% recommend it any chance I get and purchased pro. </p> <p>To the maker/team:</p> <p>You are amazing. Thank you.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LegendofDad-ALynk404"> /u/LegendofDad-ALynk404 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvo0p8/shout_out_for_hands_down_the_best_android_app_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fvo0p8/shout_out_for_hands_down_the_best_android_app_for/">[comments]</a></span>

## Device: /dev/sdb [SAT], 1 Offline uncorrectable sectors
 - [https://www.reddit.com/r/selfhosted/comments/1fvmo6o/device_devsdb_sat_1_offline_uncorrectable_sectors](https://www.reddit.com/r/selfhosted/comments/1fvmo6o/device_devsdb_sat_1_offline_uncorrectable_sectors)
 - RSS feed: $source
 - date published: 2024-10-04T00:31:43+00:00

<!-- SC_OFF --><div class="md"><p>I received an email from SMART saying the below:</p> <pre><code>Device: /dev/sdb [SAT], 1 Offline uncorrectable sectors Device info: WDC WD2000FYYZ-xx, S/N:xxx, WWN:xx, FW:01.01K02, 2.00 TB For details see host&#39;s SYSLOG. You can also use the smartctl utility for further investigation. Another message will be sent in 24 hours if the problem persists. </code></pre> <p>/var/log/syslog has this:</p> <pre><code>grep -i smart syslog|grep -v Temperature 2024-10-03T12:37:36.533488-04:00 servidor smartd[825]: Device: /dev/sdb [SAT], 1 Currently unreadable (pending) sectors 2024-10-03T12:37:36.581307-04:00 servidor smartd[825]: Sending warning via /usr/share/smartmontools/smartd-runner to root ... 2024-10-03T12:37:36.744119-04:00 servidor smartd[825]: Warning via /usr/share/smartmontools/smartd-runner to root: successful 2024-10-03T13:07:37.001303-04:00 servidor smartd[825]: Device: /dev/sdb [SAT], 1 Currently unreadable (pending) sectors 2024-10-03T13:37:3

## Small form computer recommendations.
 - [https://www.reddit.com/r/selfhosted/comments/1fvmjan/small_form_computer_recommendations](https://www.reddit.com/r/selfhosted/comments/1fvmjan/small_form_computer_recommendations)
 - RSS feed: $source
 - date published: 2024-10-04T00:25:01+00:00

<!-- SC_OFF --><div class="md"><p>I know this isn&#39;t just a self hosted question here but having been a member here and got lots of advise on hardware I thought I&#39;d ask ..and you guys also seem to like the intel nuc and other mini pc&#39;s for hosting.</p> <p>I&#39;m wanting to replace my old Asus I7 laptop with a newer intel nuc I5/7 or maybe AMD mini pc. While I don&#39;t game I do need something that has some decent power for word processing and office work, compiling software and running a few vm/s via linux kvm and docker. Additionally, I watch HD streams and lots of youtube etc and often have lots of tabs open in the browser for research. A good video card (GPU) that has great native linux support is a must as the one thing I hated about my laptop is it had a nvidia card that broke often due to kernel updates. Does Intel or AMD have better native ..as in the main line kernel support for their gpu? </p> <p>Are there any NUC&#39;S or other small mini pc&#39;s that you guys 

