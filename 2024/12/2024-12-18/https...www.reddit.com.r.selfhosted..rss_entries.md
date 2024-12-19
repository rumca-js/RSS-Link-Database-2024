# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Question about Linux and Windows compatiblilty / Homelab
 - [https://www.reddit.com/r/selfhosted/comments/1hhfk30/question_about_linux_and_windows_compatiblilty](https://www.reddit.com/r/selfhosted/comments/1hhfk30/question_about_linux_and_windows_compatiblilty)
 - RSS feed: $source
 - date published: 2024-12-18T23:56:55+00:00

<!-- SC_OFF --><div class="md"><p>Hey folks! <strong>(TL:DR at the end)</strong></p> <p>currently im running a windows server install on my homelab but i want it to be some kind of linux because of docker not working properly on win server for me. Also all those &quot;mandatory&quot; windows features eating up my precious workpower just makes me mad.</p> <p><em>Use case of my server:</em><br/> - Using it to transfer files from one PC to another over the server and within the same network.<br/> (could transfer direktly but sometime i want a backup in my server so its 2birds with one stone that way..)</p> <p>- Having JDownloader running at all times and extractring stuff into predefined directories to open on my main PC (Windows PC)</p> <p>- Running a Virtual Tabletop Service (FoundryVTT) to play DnD</p> <p>- Tinkering with stuff (mainly id like to use Docker but the GUI just does not work properly on win server) / i am jealeous of all u guys with homer and homepage frontpages xcc</p> 

## Weather app and Chore app in Docker
 - [https://www.reddit.com/r/selfhosted/comments/1hhfjpg/weather_app_and_chore_app_in_docker](https://www.reddit.com/r/selfhosted/comments/1hhfjpg/weather_app_and_chore_app_in_docker)
 - RSS feed: $source
 - date published: 2024-12-18T23:56:24+00:00

<!-- SC_OFF --><div class="md"><p>Hi there</p> <p>I&#39;m looking for 2 apps that I can run in docker. The first is a chore app. Something that I can use to track and delegate chores with notifications (preferably Gotify). Secondly, Im looking for a weather app, specifically something with alerts or notifications for predicted weather events (rain, heavy wind etc.). The notifications for the weather app can be with Gotify or Pushover. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PsycoStea"> /u/PsycoStea </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhfjpg/weather_app_and_chore_app_in_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhfjpg/weather_app_and_chore_app_in_docker/">[comments]</a></span>

## MiniPC recommendations
 - [https://www.reddit.com/r/selfhosted/comments/1hhf6bc/minipc_recommendations](https://www.reddit.com/r/selfhosted/comments/1hhf6bc/minipc_recommendations)
 - RSS feed: $source
 - date published: 2024-12-18T23:38:17+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I&#39;m a complete beginner looking to buy a mini pc, mainly to host game servers, storage system, media streaming and some BE projects.</p> <p>What mini PC would you recommend for a beginner like me? I&#39;m looking for something with good performance, with a reasonable price point (under €500) and low power consumption.</p> <p>The one i was considering was Minisforum HM90 but i have no clue if its good or not.</p> <p>Thanks in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/helloimedm"> /u/helloimedm </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhf6bc/minipc_recommendations/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhf6bc/minipc_recommendations/">[comments]</a></span>

## Docker Images of Web Version of MongoDB Compass to manage your MongoDB
 - [https://www.reddit.com/r/selfhosted/comments/1hhepm2/docker_images_of_web_version_of_mongodb_compass](https://www.reddit.com/r/selfhosted/comments/1hhepm2/docker_images_of_web_version_of_mongodb_compass)
 - RSS feed: $source
 - date published: 2024-12-18T23:16:13+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hhepm2/docker_images_of_web_version_of_mongodb_compass/"> <img src="https://b.thumbs.redditmedia.com/tLGQg9JCD41Hiqyka6oiSiu4ce7Btgqrpv0ISfcmLjw.jpg" alt="Docker Images of Web Version of MongoDB Compass to manage your MongoDB" title="Docker Images of Web Version of MongoDB Compass to manage your MongoDB" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I would like to share docker images of MongoDB Compass I have built recently. Normally MongoDB Compass is a Desktop App based on Electron. With some tweaks to the original compass-web <a href="https://www.npmjs.com/package/@mongodb-js/compass-web">https://www.npmjs.com/package/@mongodb-js/compass-web</a>, I managed to port MongoDB Compass to Web that can facilitate mongodb management on selfhosted servers. </p> <p>You can simply start you mongodb compass container via </p> <pre><code>docker run -it --rm -p 8080:8080 haohanyang/compass-web </code></pre

## Need advice on Docker networking setup with Caddy reverse proxy and Squid outbound filtering
 - [https://www.reddit.com/r/selfhosted/comments/1hhdu6w/need_advice_on_docker_networking_setup_with_caddy](https://www.reddit.com/r/selfhosted/comments/1hhdu6w/need_advice_on_docker_networking_setup_with_caddy)
 - RSS feed: $source
 - date published: 2024-12-18T22:36:07+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m setting up a home server with various services (Gitea, Jupyter, etc.). I have a Caddy reverse proxy that is concerned with inbound connections. I have a Squid forward proxy that is concerned with outbound connections.</p> <p>docker-compose.yaml ``` caddy: networks: - public_network - private_network ports: - &quot;3001-3008:3001-3008&quot; # go to various services</p> <p>squid: networks: - public_network - private_network ports: - &quot;3128:3128&quot;</p> <p>jupyter: networks: - private_network</p> <p>networks: public_network: name: public_network private_network: name: private_network internal: true</p> <p>```</p> <p>relevant squid config ```</p> <h1>DNS Configuration</h1> <p>dns_nameservers 8.8.8.8 1.1.1.1 dns_v4_first on dns_timeout 10 seconds dns_retries 10</p> <h1>Network ACLs</h1> <p>acl localnet src 192.168.100.0/24 192.168.200.0/24 acl Safe_ports port 80 443</p> <h1>Domain Allowlisting</h1> <p>acl allowed_domains dstdomain .github.co

## Self hosted image generation frontend with multi user support
 - [https://www.reddit.com/r/selfhosted/comments/1hhdq4z/self_hosted_image_generation_frontend_with_multi](https://www.reddit.com/r/selfhosted/comments/1hhdq4z/self_hosted_image_generation_frontend_with_multi)
 - RSS feed: $source
 - date published: 2024-12-18T22:31:00+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been playing around with flux and comfy-ui lately and now some of my friends want in on the action. The problem is that comfy-ui doesent support user accounts which isn&#39;t great for privacy. I&#39;m basically looking for an open web ui equivalent but for image generation, preferably with OIDC Support. Does anyone know such a platform?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dl-lZ"> /u/Dl-lZ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhdq4z/self_hosted_image_generation_frontend_with_multi/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhdq4z/self_hosted_image_generation_frontend_with_multi/">[comments]</a></span>

## macOS Brew install of Headless Transmission, On and Off Working Only Sometimes
 - [https://www.reddit.com/r/selfhosted/comments/1hhcsj9/macos_brew_install_of_headless_transmission_on](https://www.reddit.com/r/selfhosted/comments/1hhcsj9/macos_brew_install_of_headless_transmission_on)
 - RSS feed: $source
 - date published: 2024-12-18T21:50:22+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://gist.github.com/jpillora/d1d3263c67e7977d2620">https://gist.github.com/jpillora/d1d3263c67e7977d2620</a></p> <p>Have a strange problem, I followed this guide and whenever I reboot macOS Sequoia it will run Web UI sometimes, other times it will not. Or it will try to load and spin for a few minutes, load, or not load at all. Sometimes a reboot fixes it, sometimes it does not. Or it will work fine for a few hours, I check on it later without rebooting, and it runs into this same issue.</p> <p>Any ideas?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/avidrunner84"> /u/avidrunner84 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhcsj9/macos_brew_install_of_headless_transmission_on/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhcsj9/macos_brew_install_of_headless_transmission_on/">[comments]</a></span>

## Convert EPS to SVG?
 - [https://www.reddit.com/r/selfhosted/comments/1hhcr9s/convert_eps_to_svg](https://www.reddit.com/r/selfhosted/comments/1hhcr9s/convert_eps_to_svg)
 - RSS feed: $source
 - date published: 2024-12-18T21:48:47+00:00

<!-- SC_OFF --><div class="md"><p>Does anybody of self-hosted software I could use to convert EPS files into SVG files? Something like <a href="https://cloudconvert.com/eps-to-svg">CloudConvert</a>.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/theReasonableMan"> /u/theReasonableMan </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhcr9s/convert_eps_to_svg/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhcr9s/convert_eps_to_svg/">[comments]</a></span>

## Any Screen Studio free alternative for Windows?
 - [https://www.reddit.com/r/selfhosted/comments/1hhb8qa/any_screen_studio_free_alternative_for_windows](https://www.reddit.com/r/selfhosted/comments/1hhb8qa/any_screen_studio_free_alternative_for_windows)
 - RSS feed: $source
 - date published: 2024-12-18T20:43:06+00:00

<!-- SC_OFF --><div class="md"><p>Is there an opensource screen recording app with zoom features like Screen Studio? which works on Windows or UNIX?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dyeusyt"> /u/dyeusyt </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhb8qa/any_screen_studio_free_alternative_for_windows/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhb8qa/any_screen_studio_free_alternative_for_windows/">[comments]</a></span>

## How to delist IP from Spamhaus?
 - [https://www.reddit.com/r/selfhosted/comments/1hhb770/how_to_delist_ip_from_spamhaus](https://www.reddit.com/r/selfhosted/comments/1hhb770/how_to_delist_ip_from_spamhaus)
 - RSS feed: $source
 - date published: 2024-12-18T20:41:18+00:00

<!-- SC_OFF --><div class="md"><p>I have a server hosted in DigitalOcean that I try to use as Bluesky PDS. One of the Bluesky requirements is to validate the account by sending the verification email, thing is my server IP is blacklisted in Spamhaus and this doesn’t work. I use Resend so I don’t have a email server but to delist my IP I need to provide email assigned to the domain lol. Here is the Spamhaus email I’ve receive on my Gmail: </p> <p>This ticket was submitted using a disposable or freemail address. To ensure that we can help you, please use an email address that can be easily associated with the mail server on the IP you want to remove, and submit another request. </p> <p>How on earth I can delist this IP now?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/zygazorg"> /u/zygazorg </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhb770/how_to_delist_ip_from_spamhaus/">[link]</a></span> &#32; <span><a href="https

## game server help needed (attempting to expose a mc server without port forwarding)
 - [https://www.reddit.com/r/selfhosted/comments/1hhaxbk/game_server_help_needed_attempting_to_expose_a_mc](https://www.reddit.com/r/selfhosted/comments/1hhaxbk/game_server_help_needed_attempting_to_expose_a_mc)
 - RSS feed: $source
 - date published: 2024-12-18T20:29:12+00:00

<!-- SC_OFF --><div class="md"><p>so for the past couple years ive been running a home server for me and a few friends. one of the things ive been running was an mc server but since my parents dont want to port forward on the router ive been looking at options. what ive been using is playit which works decently well but as some lag. i tried using ngrok but i didnt enjoy the fact that it isnt a permanent ip and im not willing to pay 10-15 dollars a month. what ive been wondering is could i host my own reverse tunnel (i think its called?) and i started looking into something called nginx. more specifically nginx proxy manager (thank you people that gave it web ui) im not exactly sure if thats the right place to look. and if it isnt. does anybody have a better idea or alternative? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Wispy5678"> /u/Wispy5678 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhaxbk/game_server_help_

## Home Network
 - [https://www.reddit.com/r/selfhosted/comments/1hhaq5r/home_network](https://www.reddit.com/r/selfhosted/comments/1hhaq5r/home_network)
 - RSS feed: $source
 - date published: 2024-12-18T20:20:24+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>To start, I don&#39;t know much about this stuff so please go easy on me. I want to develop a home network and I have listed my goals on what I want to accomplish, I am just not sure how to do that.</p> <p><strong>Current Setup</strong></p> <p>TP-Link Deco AXE5400 Tri-Band WiFi 6E Mesh System(Deco XE75) - 3 of these.</p> <p>Netgear CM1000V2</p> <p><strong>Goals</strong></p> <p>I want to purchase a mini desktop to use with my docking station - I work from home and my work computer is locked down - and I also want to be able to use it as a hard drive for storage of pictures and videos (more info below).</p> <p>NO MORE ADS. I am sick of ads especially on youtube.</p> <p>I want to purchase a security system and have the video stored on the mini desktop but I want to access it with my cell phone (I have the blink security cameras and I am sick of paying to use their cloud system).</p> <p>I want to have my photos/videos backed up to th

## Reordering phone numbers in my contacts (synced today on a self-hosted Nextcloud/Carddav platform)
 - [https://www.reddit.com/r/selfhosted/comments/1hhak4d/reordering_phone_numbers_in_my_contacts_synced](https://www.reddit.com/r/selfhosted/comments/1hhak4d/reordering_phone_numbers_in_my_contacts_synced)
 - RSS feed: $source
 - date published: 2024-12-18T20:12:56+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I have been searching for a long time (doing some research, testing, giving up for months, starting again...) for a solution to my &quot;problem&quot;.</p> <p>I just want an app (android) or software (windows/linux) that can manage contacts with one of the MUST HAVE feature is to be able to reorder phone numbers easily (if the contact has multiple phones).</p> <p>It can be a very small application that ONLY does this, because otherwise all other contact applications or even Outlook can manage contacts quite well. This is the only feature I have never seen (even after searching for a long time).</p> <p>Hoping for swarm intelligence and good tips :)</p> <p>Thank you all</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Botaniquiche"> /u/Botaniquiche </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhak4d/reordering_phone_numbers_in_my_contacts_synced/">[link]</a></span> 

## Did you tried the YunoHost solution for (almost) non-technical users? [Not Affiliate]
 - [https://www.reddit.com/r/selfhosted/comments/1hh8t64/did_you_tried_the_yunohost_solution_for_almost](https://www.reddit.com/r/selfhosted/comments/1hh8t64/did_you_tried_the_yunohost_solution_for_almost)
 - RSS feed: $source
 - date published: 2024-12-18T18:58:18+00:00

<!-- SC_OFF --><div class="md"><p>A few months ago I thought and asked about a solution for non-technical users to host multiple existing SelfHosted services:</p> <p><a href="https://www.reddit.com/r/selfhosted/comments/1fswyyl/selfhosted_as_a_desktop_application_idea/">https://www.reddit.com/r/selfhosted/comments/1fswyyl/selfhosted_as_a_desktop_application_idea/</a></p> <p>Now I found the YunoHost system which looks AMAZING.</p> <p>But I&#39;m a technical user, I deploy my service on Docker and include volumes for backups (with rClone) and init scripts to the DB and so on.</p> <p>I&#39;m asking my friends to try the system, but meanwhile, I&#39;m asking if someone from our community has experience with the system and wants to share.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/baruchiro"> /u/baruchiro </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hh8t64/did_you_tried_the_yunohost_solution_for_almost/">[link]</a></sp

## Did you tried the YunoHost solution for (almost) non-technical users? [Not Affiliate]
 - [https://www.reddit.com/r/selfhosted/comments/1hh8oub/did_you_tried_the_yunohost_solution_for_almost](https://www.reddit.com/r/selfhosted/comments/1hh8oub/did_you_tried_the_yunohost_solution_for_almost)
 - RSS feed: $source
 - date published: 2024-12-18T18:53:09+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/baruchiro"> /u/baruchiro </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hh8oub/did_you_tried_the_yunohost_solution_for_almost/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hh8oub/did_you_tried_the_yunohost_solution_for_almost/">[comments]</a></span>

## Cloudflare Phishing Block
 - [https://www.reddit.com/r/selfhosted/comments/1hh8ah4/cloudflare_phishing_block](https://www.reddit.com/r/selfhosted/comments/1hh8ah4/cloudflare_phishing_block)
 - RSS feed: $source
 - date published: 2024-12-18T18:36:01+00:00

<!-- SC_OFF --><div class="md"><p>My website got blocked somehow for phishing in the Cloudflare backend. I think it was probably one of the WordPress plugins that was abandoned or something and created a security issue. Not entirely sure, but my site is just a basic landing page and info; there is no store or anything like that.</p> <p>When I went into Cloudflare to figure out how to fix it, they allowed me to ask for a review, but nothing has happened now for a couple months.</p> <p>Anyone have this kind of experience and know what I should do?</p> <p>TIA</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/molotovPopsicle"> /u/molotovPopsicle </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hh8ah4/cloudflare_phishing_block/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hh8ah4/cloudflare_phishing_block/">[comments]</a></span>

## [Update] Abbey: self-hosted AI interface for workspaces, documents, and videos now with SearXNG compatibility and yaml configuration for local models
 - [https://www.reddit.com/r/selfhosted/comments/1hh83ou/update_abbey_selfhosted_ai_interface_for](https://www.reddit.com/r/selfhosted/comments/1hh83ou/update_abbey_selfhosted_ai_interface_for)
 - RSS feed: $source
 - date published: 2024-12-18T18:28:02+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hh83ou/update_abbey_selfhosted_ai_interface_for/"> <img src="https://external-preview.redd.it/0RCqUIgxhZYbIObpgoKrowx9TqOuFatd_juaqC_f5Ho.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=c5ce6b7e48c7f60b61414672e115e32c5067531c" alt="[Update] Abbey: self-hosted AI interface for workspaces, documents, and videos now with SearXNG compatibility and yaml configuration for local models" title="[Update] Abbey: self-hosted AI interface for workspaces, documents, and videos now with SearXNG compatibility and yaml configuration for local models" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gkamer8"> /u/gkamer8 </a> <br/> <span><a href="https://github.com/US-Artificial-Intelligence/abbey">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hh83ou/update_abbey_selfhosted_ai_interface_for/">[comments]</a></span> </td></tr></table>

## HP Prodesk i5-12500 vs Dell Optiplex Micro i5-13500T
 - [https://www.reddit.com/r/selfhosted/comments/1hh7cdp/hp_prodesk_i512500_vs_dell_optiplex_micro_i513500t](https://www.reddit.com/r/selfhosted/comments/1hh7cdp/hp_prodesk_i512500_vs_dell_optiplex_micro_i513500t)
 - RSS feed: $source
 - date published: 2024-12-18T17:55:19+00:00

<!-- SC_OFF --><div class="md"><p>I would like to hear your opinion on a possible piece of hardware to purchase for my home lab. I&#39;m not sure if I&#39;ll be able to buy it yet, because these things are very expensive here in Brazil, but here we go.</p> <p><strong>Option 1:</strong> HP Prodesk 400 G9 Sff (not micro), i5-12500 Processor, 8Gb DDR4, 1TB pcie nvme SSD;</p> <p><strong>Option 2:</strong> Dell Optiplex Micro, i5 13500t, 8gb ram ddr4, 256gb ssd.</p> <p>They are practically the same price and the performance of the two processors seemed very similar in most things according to the research I did, but the i5-13500T has 14 Physical cores and 20 Threads, while the i5-12500 has 6/12.</p> <p>Today I use a Raspberry Pi 4/8Gb, with Debian and I run HomeAssistant, Adguard Home, Vaultwarden, node-red, etc. via docker, and I have no problems with this hardware.</p> <p>However, I would like to use Immich with ML for family photos, maybe something from the *Arr stack, plex for videos 

## taking a GO at self hosted secret sharing
 - [https://www.reddit.com/r/selfhosted/comments/1hh6zwl/taking_a_go_at_self_hosted_secret_sharing](https://www.reddit.com/r/selfhosted/comments/1hh6zwl/taking_a_go_at_self_hosted_secret_sharing)
 - RSS feed: $source
 - date published: 2024-12-18T17:40:19+00:00

<!-- SC_OFF --><div class="md"><p>Hello <a href="/r/selfhosted">/r/selfhosted</a> ! </p> <p>I just finished building GopherDrop, a self-hostable tool inspired by Bitwarden Send. It&#39;s a secure REST API and UI for sharing one-time secrets and files. Built with Go for the backend and Vue.js with Vuetify for the frontend.</p> <p>You can check it out here: <a href="https://github.com/kek-Sec/GopherDrop">Github Link</a></p> <p>Would love to hear your thoughts and suggestions since this is my first open source project.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mparigas"> /u/Mparigas </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hh6zwl/taking_a_go_at_self_hosted_secret_sharing/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hh6zwl/taking_a_go_at_self_hosted_secret_sharing/">[comments]</a></span>

## Help needed connecting Android phone with Windows 10 web server
 - [https://www.reddit.com/r/selfhosted/comments/1hh68f1/help_needed_connecting_android_phone_with_windows](https://www.reddit.com/r/selfhosted/comments/1hh68f1/help_needed_connecting_android_phone_with_windows)
 - RSS feed: $source
 - date published: 2024-12-18T17:07:21+00:00

<!-- SC_OFF --><div class="md"><p>Hi. I have an Android phone that uses Chrome as its browser. I&#39;m trying to use it to locally view web pages that I built using VS Code from a Windows 10 laptop. VS Code is running the Live Server extension and is serving pages on port 5500.</p> <p>When I go to my computer&#39;s local IP address and port 5500 on my phone, Chrome shows &quot;This site can&#39;t be reached&quot; and then it shows the PC&#39;s local IP address and port 5500 and says its unreachable, followed by &quot;ERR_ADDRESS_UNREACHABLE&quot;.</p> <p>On the PC itself, browsing using the local IP address or using <a href="http://127.0.0.1:5500">127.0.0.1:5500</a> both work. I tried disabling Windows Defender&#39;s firewall, but it had no effect. I also added an inbound rule there which allows traffic on port 5500. The other security programs that I have are Avira Phantom VPN and Malwarebytes.</p> <p>Does anyone have any insights that could help me? My goal is to be able to view we

## unbound and Google push notifications
 - [https://www.reddit.com/r/selfhosted/comments/1hh65ae/unbound_and_google_push_notifications](https://www.reddit.com/r/selfhosted/comments/1hh65ae/unbound_and_google_push_notifications)
 - RSS feed: $source
 - date published: 2024-12-18T17:03:36+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I use Wireguard and unbound. All my Wireguard clients use the unbound DNS server that is running on my Wireguard central node.</p> <p>Things were working perfectly, and recently for some reason I decided to fiddle with the config and remove some <code>local-data</code> and <code>local-data-ptr</code> values which I though were unnecessary (because after all I don&#39;t have that many devices and I know the IPs by heart). It took me a while to realise that it seems like without those lines, Google push notifications were not working anymore.</p> <p>What could be the reason why these local name resolution lines in <code>unbound.conf</code> would cause Google notifications to fail?</p> <p>Thank you.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/paranoid-alkaloid"> /u/paranoid-alkaloid </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hh65ae/unbound_and_google_push_notifications/">[link]<

## Help automating ticket amount extraction into a custom field in Paperless-ngx
 - [https://www.reddit.com/r/selfhosted/comments/1hh5qv8/help_automating_ticket_amount_extraction_into_a](https://www.reddit.com/r/selfhosted/comments/1hh5qv8/help_automating_ticket_amount_extraction_into_a)
 - RSS feed: $source
 - date published: 2024-12-18T16:46:27+00:00

<!-- SC_OFF --><div class="md"><p>Hello Paperless-ngx community,<br/> I would like to automate the extraction of ticket amounts when a document of type <strong>&quot;Tickets&quot;</strong> is detected. My goal is to extract the amount from the OCR content of the document and store it in a <strong>custom field</strong> called <strong>&quot;Montant du ticket&quot;</strong> (Ticket Amount).</p> <p>I already have a post-process hook script to perform this extraction, but I’m still facing challenges getting the data properly added to the custom field.</p> <p>Has anyone implemented a similar workflow or could offer advice on how to achieve this? Thank you in advance for your help!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ManyWitness4490"> /u/ManyWitness4490 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hh5qv8/help_automating_ticket_amount_extraction_into_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com

## Back up emails from GMail/Outlook/Proton
 - [https://www.reddit.com/r/selfhosted/comments/1hh565s/back_up_emails_from_gmailoutlookproton](https://www.reddit.com/r/selfhosted/comments/1hh565s/back_up_emails_from_gmailoutlookproton)
 - RSS feed: $source
 - date published: 2024-12-18T16:21:02+00:00

<!-- SC_OFF --><div class="md"><p>I recently got a notification about running out of email storage and being prompted to upgrade. Since I’m trying to de-Google my life and have a home NAS, I started researching Synology MailPlus. I came across this Synology Knowledge Center article: <a href="https://kb.synology.com/en-us/DSM/tutorial/How_should_I_receive_external_email_messages_via_MailPlus">How do I back up emails from Gmail or Outlook.com to Synology MailPlus? - Synology Knowledge Center</a>.</p> <p>This got me thinking about the whole “if it’s free, you’re the product” debate. Google/Outlook (and to a lesser extent, ProtonMail) don’t need 20 years of my emails. I don’t need them—except for the occasional nostalgia trip when I like to reflect and reminisce. Sure, I could delete them, but I prefer to keep them locally since I already have a 3-2-1 backup strategy at home.</p> <p>Two questions for the community:</p> <p>Has anyone transitioned to Synology MailPlus or a similar setup? H

## Is this Dell 3020m any good for a NAS and/or home server?
 - [https://www.reddit.com/r/selfhosted/comments/1hh4pb4/is_this_dell_3020m_any_good_for_a_nas_andor_home](https://www.reddit.com/r/selfhosted/comments/1hh4pb4/is_this_dell_3020m_any_good_for_a_nas_andor_home)
 - RSS feed: $source
 - date published: 2024-12-18T16:00:21+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hh4pb4/is_this_dell_3020m_any_good_for_a_nas_andor_home/"> <img src="https://b.thumbs.redditmedia.com/bLOHjm9LKcCgHVEd7IhUCgHO6Ut95qGKhBYRde-hi4Y.jpg" alt="Is this Dell 3020m any good for a NAS and/or home server?" title="Is this Dell 3020m any good for a NAS and/or home server?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Specs are in portuguese but pretty understandable.</p> <p>Is this good for a NAS? Or would be better as a media server? I currently have a raspberry pi as my home lab and I want to upgrade, I would like a NAS and a faster media server. Could I buy 1 machine for both or should be separate? Would this PC fit any of my needs?</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/NorthBat2171"> /u/NorthBat2171 </a> <br/> <span><a href="https://www.reddit.com/gallery/1hh4pb4">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfh

## Storecraft CLI can generate a self hosted javascript commerce backend
 - [https://www.reddit.com/r/selfhosted/comments/1hh4a37/storecraft_cli_can_generate_a_self_hosted](https://www.reddit.com/r/selfhosted/comments/1hh4a37/storecraft_cli_can_generate_a_self_hosted)
 - RSS feed: $source
 - date published: 2024-12-18T15:41:21+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hh4a37/storecraft_cli_can_generate_a_self_hosted/"> <img src="https://b.thumbs.redditmedia.com/4_8z2wQtUrNYh__jTsxzDjro-Bu4QdHUDQQm8uu9YqU.jpg" alt="Storecraft CLI can generate a self hosted javascript commerce backend " title="Storecraft CLI can generate a self hosted javascript commerce backend " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Here is the video</p> <p><a href="https://youtu.be/Io_-lOrY8V4">storecraft cli</a></p> <p><a href="https://preview.redd.it/1la9er3hnm7e1.png?width=2544&amp;format=png&amp;auto=webp&amp;s=6e72aed5faaa8cbb00b3bd55df47eac205c86f8f">https://preview.redd.it/1la9er3hnm7e1.png?width=2544&amp;format=png&amp;auto=webp&amp;s=6e72aed5faaa8cbb00b3bd55df47eac205c86f8f</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hendrixstring"> /u/hendrixstring </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hh4a37/storecraft_cl

## Upload station for digital camera upload workflow with SD and Compact Flash cards
 - [https://www.reddit.com/r/selfhosted/comments/1hh3znq/upload_station_for_digital_camera_upload_workflow](https://www.reddit.com/r/selfhosted/comments/1hh3znq/upload_station_for_digital_camera_upload_workflow)
 - RSS feed: $source
 - date published: 2024-12-18T15:28:14+00:00

<!-- SC_OFF --><div class="md"><p>Over the holidays I&#39;m looking to see if I can solve a workflow problem. <strong>Is there any kind of OSS software that&#39;ll let me turn a PC or RPi5 w/SSD into an automatic upload station?</strong> I&#39;m prepared to buy/find hardware to solve this problem and write code, if needed.</p> <p>When I take photos of our kids, I want to be able to make these available as quickly as possible, but I use Lightroom for editing. That means I have a serial workflow that goes: import, cull, edit (optional), export, and upload. The real job to be done is to import and upload the JPEGs so that my wife can get those quickly. I still want to go through my process on my own time in parallel for long-term curation of the photos.</p> <p>I think my ideal solution would:</p> <ol> <li>Let me stick one or more cards in the reader and hit go.</li> <li>Copy the photos to the local SSD and tell me to remove the cards.</li> <li>Do the following tasks (serially or in para

## nginx proxy + it-tools returns empty body
 - [https://www.reddit.com/r/selfhosted/comments/1hh3oib/nginx_proxy_ittools_returns_empty_body](https://www.reddit.com/r/selfhosted/comments/1hh3oib/nginx_proxy_ittools_returns_empty_body)
 - RSS feed: $source
 - date published: 2024-12-18T15:13:20+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m using a nginx as a reverse proxy for my applications and when tring to route it-tools the favcon returns fine but the page is totaly blank.</p> <ul> <li><strong>it-tools logs:</strong> <ul> <li><a href="http://172.18.0.4">172.18.0.4</a> - - [18/Dec/2024:14:54:32 +0000] &quot;GET / HTTP/1.1&quot; 200 2787 &quot;-&quot; &quot;Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36&quot; &quot;&quot;</li> <li><a href="http://172.18.0.4">172.18.0.4</a> - - [18/Dec/2024:14:54:33 +0000] &quot;GET /favicon.ico HTTP/1.1&quot; 200 15086 &quot;http:///ittools/&quot; &quot;Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36&quot; &quot;&quot;</li> </ul></li> </ul> <p><strong>nginx location config:</strong><br/> <code>listen 80;</code><br/> <code>listen [::]:80;</code><br/> <code>location /ittools/ {</code><br/> <code>proxy_pass</code> <a h

## Unknown question.
 - [https://www.reddit.com/r/selfhosted/comments/1hh3mqo/unknown_question](https://www.reddit.com/r/selfhosted/comments/1hh3mqo/unknown_question)
 - RSS feed: $source
 - date published: 2024-12-18T15:11:04+00:00

<!-- SC_OFF --><div class="md"><p>Hi Guys,</p> <p>I&#39;m trying to do something, I don&#39;t know if it makes sense, but I&#39;m asking anyways.</p> <p>I want all users on one segment in my network to be able to access my dashboard *still wrapping my head around how this works* using a one word browser entry. so if I typed in &quot;Azkaban&quot; on my browser, my wife and I basically can get all our shared services.</p> <p>Does this make sense? Or am I just thinking about something impossible?</p> <p>Thanking you in advance, R.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rahimin3d"> /u/rahimin3d </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hh3mqo/unknown_question/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hh3mqo/unknown_question/">[comments]</a></span>

## Rate my plans for Backup
 - [https://www.reddit.com/r/selfhosted/comments/1hh39bt/rate_my_plans_for_backup](https://www.reddit.com/r/selfhosted/comments/1hh39bt/rate_my_plans_for_backup)
 - RSS feed: $source
 - date published: 2024-12-18T14:53:39+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I am currently planning to set up a backup for my home server. About the server: It&#39;s an old tower PC, running proxmox. Has a piHole, nextcloud, immich and homeasistant running on it. I&#39;d love to get some feedback on my thoughts.</p> <p>For my data (Nextcloud and immich) I am planning to upgrade to 2 TB of storage for both services. Since I don&#39;t have any slots left I might need to connect an external drive via usb. Might that be a problem? If so why?</p> <p>My Idea for a backup solution is FritzNAS. I thought of buying a icyBox 2Bay Raid with 2x 2 TB WD RED NAS HDDs from Amazon and hooking it to my Fritzbox. This would be a share on my network to which I will upload my backups.</p> <p>Configuration would be raid 1 for the backup. Data (Nextcloud and immich) would be backed up separately from their hostmachines</p> <p>I know that a good backup follows the 3-2-1 rule, but I am kind of cheap, so I don&#39;t want to pay for clou

## Self Hosted DynDNS Server?
 - [https://www.reddit.com/r/selfhosted/comments/1hh32sz/self_hosted_dyndns_server](https://www.reddit.com/r/selfhosted/comments/1hh32sz/self_hosted_dyndns_server)
 - RSS feed: $source
 - date published: 2024-12-18T14:45:03+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a DDNS server that I can host on my own Ubuntu server. Can you recommend a software solution?</p> <p>So far, I have only found this Phython-based solution: <a href="https://github.com/SFTtech/sftdyn">https://github.com/SFTtech/sftdyn</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LaireTM"> /u/LaireTM </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hh32sz/self_hosted_dyndns_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hh32sz/self_hosted_dyndns_server/">[comments]</a></span>

## Migrate docker containers from LXC to a VM
 - [https://www.reddit.com/r/selfhosted/comments/1hh1hw6/migrate_docker_containers_from_lxc_to_a_vm](https://www.reddit.com/r/selfhosted/comments/1hh1hw6/migrate_docker_containers_from_lxc_to_a_vm)
 - RSS feed: $source
 - date published: 2024-12-18T13:24:06+00:00

<!-- SC_OFF --><div class="md"><p>Long time ago when I was only a newbie in the selfhost world I deployed on my Proxmox a Docker LXC using tteck scripts.</p> <p>Now after long time I feel the need to move all the containers deployed (more than 40) on a VM.</p> <p>I tried digging on the web but I cant get an easy method to do so without losing all the setup and data.</p> <p>Anyone can help me figuring out how to do that?</p> <p>Thanks in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/icenoir"> /u/icenoir </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hh1hw6/migrate_docker_containers_from_lxc_to_a_vm/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hh1hw6/migrate_docker_containers_from_lxc_to_a_vm/">[comments]</a></span>

## Simple photo gallery apps - functionality somewhere between PiGallery2 and PhotoPrism?
 - [https://www.reddit.com/r/selfhosted/comments/1hh0ze3/simple_photo_gallery_apps_functionality_somewhere](https://www.reddit.com/r/selfhosted/comments/1hh0ze3/simple_photo_gallery_apps_functionality_somewhere)
 - RSS feed: $source
 - date published: 2024-12-18T12:56:11+00:00

<!-- SC_OFF --><div class="md"><p>Any recommendations for simple / minimal photo gallery apps, with basic metadata editing functionality?</p> <p>I am looking for something to organise and view my photos, and perform minor metadata edits like rotating or renaming files (or maybe even moving between folders). I generally organise my photos by folder/directories within other parent folders - I don&#39;t often use custom albums (it would be a nice to have feature, but it&#39;s not strictly required). I take pictures on a digital camera and film SLR so I am usually dealing with a few dozen pics at a time - organising, rotating and then just flicking through them occasionally. I am also just backing up photos received from family/friends and other images I&#39;ve collected over the years.</p> <p>I usually copy the photos to my PC, copy to my Ubuntu server which is attached as a SMB share, and then point the self-hosted app to that &#39;photos&#39; parent folder, grouped by camera, date/eve

## [Guide] MeTube — Self-hosted YouTube downloader
 - [https://www.reddit.com/r/selfhosted/comments/1hh0w0f/guide_metube_selfhosted_youtube_downloader](https://www.reddit.com/r/selfhosted/comments/1hh0w0f/guide_metube_selfhosted_youtube_downloader)
 - RSS feed: $source
 - date published: 2024-12-18T12:50:47+00:00

<!-- SC_OFF --><div class="md"><p>Hey all!</p> <p>A recent addition to my homelab is MeTube, a self-hosted YouTube downloader with a sleek and simple web interface.</p> <p>I&#39;ve been using it for a while now and decided to write a quick guide on how to set it up.</p> <p>Blog: <a href="https://akashrajpurohit.com/blog/metube-selfhosted-youtube-downloader-with-a-sleek-web-interface/?ref=reddit">https://akashrajpurohit.com/blog/metube-selfhosted-youtube-downloader-with-a-sleek-web-interface/</a></p> <p>While MeTube primarily specifies that its focused on YouTube, since it uses yt-dlp, it can be used to download videos from 1000+ other platforms as well.</p> <p>Give it a try yourself and see how it works for you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Developer_Akash"> /u/Developer_Akash </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hh0w0f/guide_metube_selfhosted_youtube_downloader/">[link]</a></span> &#32; <spa

## Input/Output error on ubuntu server
 - [https://www.reddit.com/r/selfhosted/comments/1hh0ud4/inputoutput_error_on_ubuntu_server](https://www.reddit.com/r/selfhosted/comments/1hh0ud4/inputoutput_error_on_ubuntu_server)
 - RSS feed: $source
 - date published: 2024-12-18T12:48:16+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hh0ud4/inputoutput_error_on_ubuntu_server/"> <img src="https://b.thumbs.redditmedia.com/w0pHNPzKVmWdGqfe-tDT7Ca6nF1Rk7P-JcAUV7WDusI.jpg" alt="Input/Output error on ubuntu server" title="Input/Output error on ubuntu server" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I was setting up a frigate/homeassistant setup with ubuntu server and docker, The current setup was an i3 w/ 1050ti and an HDD. It was working fine for a few days until I couldn&#39;t ssh into it and then checking the monitor output gave an Input/Output error (I&#39;ve attached a screenshot).</p> <p>I replaced the hdd to an ssd thinking that the hdd must be toast, however after getting it all setup the issue came back after a few days.</p> <p>I&#39;m currently bummed as to what could be the issue, also I noticed that the first time issue came I was able to reboot back into ubuntu however lately when the issue comes I cannot boot back into the 

## Local server via cloud instance reverse proxy over wireguard
 - [https://www.reddit.com/r/selfhosted/comments/1hh0rme/local_server_via_cloud_instance_reverse_proxy](https://www.reddit.com/r/selfhosted/comments/1hh0rme/local_server_via_cloud_instance_reverse_proxy)
 - RSS feed: $source
 - date published: 2024-12-18T12:43:49+00:00

<!-- SC_OFF --><div class="md"><p>I am using wireguard to access my local resources when away from home but I as curious as to it&#39;s viability for serving local resources to the world wide web via a cloud instance reverse proxy. I&#39;m curious how secure a set up like this is and what the main concerns are and how to mitigate them. </p> <p>For now I only really used to quickly demo a project I have been working on to a friend which relied on some of my other resources on my lan.</p> <hr/> <p>The set up was as follows:</p> <ul> <li>Wireguard Server running locally</li> <li>Tiny Cloud Instance from cloud provider <ul> <li>Running nginx</li> <li>Set up as wireguard client</li> </ul></li> </ul> <p>/etc/wireguard/wg0.conf ```ini [Interface] PrivateKey = &lt;private_key_value&gt; Address = &lt;wg_adapter_ip&gt; DNS = &lt;wg_server_ip&gt;</p> <p>[Peer] PublicKey = &lt;public_key_value&gt; AllowedIPs = &lt;allowed_ip_cidr&gt; Endpoint = &lt;home_external_ip&gt;:51820 PersistantKeepAliveV

## Solution for internal sandwich ordering and payment system
 - [https://www.reddit.com/r/selfhosted/comments/1hh0j93/solution_for_internal_sandwich_ordering_and](https://www.reddit.com/r/selfhosted/comments/1hh0j93/solution_for_internal_sandwich_ordering_and)
 - RSS feed: $source
 - date published: 2024-12-18T12:29:52+00:00

<!-- SC_OFF --><div class="md"><p>TL;DR an open-source app to create an internal system for ordering sandwiches from an external shop, with instant payment processing on the company account (independent of the shop).</p> <p>Our company doesn&#39;t have an on-site restaurant, so many colleagues visit a nearby sandwich shop. However, going there, ordering, and payment can take time.</p> <p>We can call in advance, but asking for individual sandwiches and manual collection of payments from colleagues can be time-consuming.</p> <p>I want to deploy an in-house app that allows colleagues to:</p> <ol> <li>Browse and order sandwiches with toppings and sauces (mirroring the external shop&#39;s menu).</li> <li>Pay for their orders on our company account (or a dedicated account).</li> <li>Validate payments instantly, with a tolerance for minor payment processing delays.</li> </ol> <p>I would then order all sandwich, go pay and collect them at noon and bring them back.</p> <p>I&#39;ve explored Ta

## Handle backup on k8s selfhosted Vaultwarden
 - [https://www.reddit.com/r/selfhosted/comments/1hgzjye/handle_backup_on_k8s_selfhosted_vaultwarden](https://www.reddit.com/r/selfhosted/comments/1hgzjye/handle_backup_on_k8s_selfhosted_vaultwarden)
 - RSS feed: $source
 - date published: 2024-12-18T11:25:22+00:00

<!-- SC_OFF --><div class="md"><p>Hello, </p> <p>I was wondering how folks around handle automatic backup for Vaultwarden.<br/> Basically on my deployment I&#39;ve the data stored into a PVC on a NFS share, I&#39;ve done manually backups over the PVC through a job that also encrypt the backup file and later is stored into a veracrypt container <em>(I guess all data there is encrypted anyway but not sure how easy would be to decrypted in case the backup file its compromised)</em>.</p> <p>What are the approach people is following to preserve the data in case of disaster ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/neulon"> /u/neulon </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgzjye/handle_backup_on_k8s_selfhosted_vaultwarden/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgzjye/handle_backup_on_k8s_selfhosted_vaultwarden/">[comments]</a></span>

## Ok so they're not phones, but here's my setup
 - [https://www.reddit.com/r/selfhosted/comments/1hgzfjx/ok_so_theyre_not_phones_but_heres_my_setup](https://www.reddit.com/r/selfhosted/comments/1hgzfjx/ok_so_theyre_not_phones_but_heres_my_setup)
 - RSS feed: $source
 - date published: 2024-12-18T11:15:53+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hgzfjx/ok_so_theyre_not_phones_but_heres_my_setup/"> <img src="https://b.thumbs.redditmedia.com/EOSUtVmYgYPpa3xptUTffTuOucfD77NRW4EGlJ9XPgk.jpg" alt="Ok so they're not phones, but here's my setup" title="Ok so they're not phones, but here's my setup" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/axcil8wdbl7e1.jpg?width=4032&amp;format=pjpg&amp;auto=webp&amp;s=330b59b2818d46738a1614ec8f3c007b3a187e4e">https://preview.redd.it/axcil8wdbl7e1.jpg?width=4032&amp;format=pjpg&amp;auto=webp&amp;s=330b59b2818d46738a1614ec8f3c007b3a187e4e</a></p> <p>Two Dell Latitude 5400 laptops. Both acquired cheap from ebay due to having broken screens and other damage. Batteries removed too. Both 8th-Gen i5, Debian 12, 12GB RAM. They&#39;re underneath the worktop in my office, right in the corner.</p> <p>Top one is running our family Better-Minecraft server (MC Java but with around 200 Mods, includ

## Selfhosted Docker Infrastructure
 - [https://www.reddit.com/r/selfhosted/comments/1hgzcc4/selfhosted_docker_infrastructure](https://www.reddit.com/r/selfhosted/comments/1hgzcc4/selfhosted_docker_infrastructure)
 - RSS feed: $source
 - date published: 2024-12-18T11:09:24+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>it&#39;s my first time selfhosting applications which are exposed to the internet. Before, i used a VPN to connect to my home-network and use the services which were hosted on an Raspberry Pi - that worked great.</p> <p>I rented a VPS and want to host a application there. My plan was to set up my infrastructure with docker-compose because i was impressed how fast i was able to get back running my home lab after the microSD of the Pi died:</p> <p>nginx, <a href="http://asp.net">asp.net</a> webpage, postgreSQL, service monitoring (and also external monitoring for host availability)</p> <p>In my home network i used portainer to manage the containers, but after a quick checkup i found out that it is not recommended to expose portainer to the internet - and that makes perfect sense.</p> <p>Is there another way to easily manage the containers without always connecting via ssh?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://ww

## Local Radio Stations - Passthrough
 - [https://www.reddit.com/r/selfhosted/comments/1hgyygp/local_radio_stations_passthrough](https://www.reddit.com/r/selfhosted/comments/1hgyygp/local_radio_stations_passthrough)
 - RSS feed: $source
 - date published: 2024-12-18T10:41:22+00:00

<!-- SC_OFF --><div class="md"><p>Not sure if this is possible or if this is even the best place to post</p> <p>I am out of the area hiking/camping from time to time on a weekend which usually means I miss my local teams radio commentary what I would like to do is pass the radio commentary through my server to my phone or something similar. I dont think I can use an online radio as the commentary is only available over FM </p> <p>Ive seen this device on amazon but not sure if its something that would help the cause <a href="https://www.amazon.co.uk/RTL2832U-Digital-Receiver-Recording-Playback/dp/B0CTHRBF1C">https://www.amazon.co.uk/RTL2832U-Digital-Receiver-Recording-Playback/dp/B0CTHRBF1C</a></p> <p>Any help would be greatly appreciated </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/B1G0Z"> /u/B1G0Z </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgyygp/local_radio_stations_passthrough/">[link]</a></span> &#32; <span><

## Aide pour automatiser l'extraction du montant des tickets vers un champ personnalisé dans Paperless-ngx
 - [https://www.reddit.com/r/selfhosted/comments/1hgytru/aide_pour_automatiser_lextraction_du_montant_des](https://www.reddit.com/r/selfhosted/comments/1hgytru/aide_pour_automatiser_lextraction_du_montant_des)
 - RSS feed: $source
 - date published: 2024-12-18T10:31:20+00:00

<!-- SC_OFF --><div class="md"><p>Bonjour à tous !<br/> Je souhaiterais automatiser l&#39;extraction des montants des tickets lorsqu&#39;un document de type <strong>&quot;Tickets&quot;</strong> est détecté. Mon objectif est que le montant soit extrait du contenu OCR du document et stocké dans un <strong>champ personnalisé</strong> nommé <strong>&quot;Montant du ticket&quot;</strong>.</p> <p>J&#39;ai déjà un script en post-process hook pour effectuer cette extraction, mais je rencontre encore des difficultés pour que les données soient correctement ajoutées au champ personnalisé.</p> <p>Est-ce que quelqu&#39;un a déjà implémenté ce genre de workflow ou aurait des conseils pour m&#39;aider à y parvenir ? Merci d&#39;avance pour votre aide !</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ManyWitness4490"> /u/ManyWitness4490 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgytru/aide_pour_automatiser_lextraction_du_montant_d

## Homelab as Code: Packer + Terraform + Ansible
 - [https://www.reddit.com/r/selfhosted/comments/1hgy4in/homelab_as_code_packer_terraform_ansible](https://www.reddit.com/r/selfhosted/comments/1hgy4in/homelab_as_code_packer_terraform_ansible)
 - RSS feed: $source
 - date published: 2024-12-18T09:36:22+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hgy4in/homelab_as_code_packer_terraform_ansible/"> <img src="https://b.thumbs.redditmedia.com/M409hZiCt5cIGsqPlmZz-VnGFhYaZo0UxCatZUhcqVk.jpg" alt="Homelab as Code: Packer + Terraform + Ansible" title="Homelab as Code: Packer + Terraform + Ansible" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey folks,</p> <p>Recently, I started getting serious about automation for my homelab. I’d played around with <strong>Ansible</strong> before, but this time I wanted to go further and try out <strong>Packer</strong> and <strong>Terraform</strong>. After a few days of messing around, I finally got a basic setup working and decided to document it:</p> <p>Blog:</p> <p><a href="https://merox.dev/blog/homelab-as-code/">https://merox.dev/blog/homelab-as-code/</a></p> <p>Github:</p> <p><a href="https://github.com/mer0x/homelab-as-code">https://github.com/mer0x/homelab-as-code</a></p> <p>Here’s what I did:</p> <ol> <li><stron

## Welcome to seedit where you can selfhost your own community
 - [https://www.reddit.com/r/selfhosted/comments/1hgxp3y/welcome_to_seedit_where_you_can_selfhost_your_own](https://www.reddit.com/r/selfhosted/comments/1hgxp3y/welcome_to_seedit_where_you_can_selfhost_your_own)
 - RSS feed: $source
 - date published: 2024-12-18T09:01:44+00:00

<!-- SC_OFF --><div class="md"><p>We&#39;ve taken steps to remove all of the trolls and toxic content. Seedit is now a friendly and welcoming place. Its easy to make your community, you can make one about p/tech or p/selfhosting. You can also use it for archiving purposes that no one can take down. The possibilities are limitless. It only takes a button click. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Content_Link_2084"> /u/Content_Link_2084 </a> <br/> <span><a href="https://seedit.app">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgxp3y/welcome_to_seedit_where_you_can_selfhost_your_own/">[comments]</a></span>

## My dashboard! It's funny not long ago i was running plex and nothing else on windows. I'm obsessed and cannot stop tinkering, i love it.
 - [https://www.reddit.com/r/selfhosted/comments/1hgxf2i/my_dashboard_its_funny_not_long_ago_i_was_running](https://www.reddit.com/r/selfhosted/comments/1hgxf2i/my_dashboard_its_funny_not_long_ago_i_was_running)
 - RSS feed: $source
 - date published: 2024-12-18T08:39:33+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hgxf2i/my_dashboard_its_funny_not_long_ago_i_was_running/"> <img src="https://preview.redd.it/2bqb3upzjk7e1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=efdb4de0eb4107bf044d4edfbf175e56d64c4b16" alt="My dashboard! It's funny not long ago i was running plex and nothing else on windows. I'm obsessed and cannot stop tinkering, i love it." title="My dashboard! It's funny not long ago i was running plex and nothing else on windows. I'm obsessed and cannot stop tinkering, i love it." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pdxmichael"> /u/pdxmichael </a> <br/> <span><a href="https://i.redd.it/2bqb3upzjk7e1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgxf2i/my_dashboard_its_funny_not_long_ago_i_was_running/">[comments]</a></span> </td></tr></table>

## Self hosted status software
 - [https://www.reddit.com/r/selfhosted/comments/1hgx9bj/self_hosted_status_software](https://www.reddit.com/r/selfhosted/comments/1hgx9bj/self_hosted_status_software)
 - RSS feed: $source
 - date published: 2024-12-18T08:26:16+00:00

<!-- SC_OFF --><div class="md"><p>Anyone know of a good self hosted &quot;on office/ out of office&quot; status software? Just something to indicate to others in the office that you are available, not available, not there, etc. Any ideas? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nobodylikesemail"> /u/nobodylikesemail </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgx9bj/self_hosted_status_software/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgx9bj/self_hosted_status_software/">[comments]</a></span>

## Good selfhosted push notifications
 - [https://www.reddit.com/r/selfhosted/comments/1hgwxww/good_selfhosted_push_notifications](https://www.reddit.com/r/selfhosted/comments/1hgwxww/good_selfhosted_push_notifications)
 - RSS feed: $source
 - date published: 2024-12-18T08:01:50+00:00

<!-- SC_OFF --><div class="md"><p>I tried ntfy and igotify but I didn’t like the way how they work. Anything like a proper push notification. iOS ecosystem. </p> <p>I want to get notifications about my servers event. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/anonuser-al"> /u/anonuser-al </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgwxww/good_selfhosted_push_notifications/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgwxww/good_selfhosted_push_notifications/">[comments]</a></span>

## Lightweight Music Server with Edit Features?
 - [https://www.reddit.com/r/selfhosted/comments/1hgvhcq/lightweight_music_server_with_edit_features](https://www.reddit.com/r/selfhosted/comments/1hgvhcq/lightweight_music_server_with_edit_features)
 - RSS feed: $source
 - date published: 2024-12-18T06:16:24+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been using Navidrome for a few days, and while it&#39;s great, the biggest issue for me is that it&#39;s completely read-only. I’d like to be able to delete tracks, edit metadata, and do other basic stuff. It doesn&#39;t need to be Subsonic-compliant—I just want something lightweight with Android and desktop clients.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rantob"> /u/rantob </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgvhcq/lightweight_music_server_with_edit_features/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgvhcq/lightweight_music_server_with_edit_features/">[comments]</a></span>

## I made an sms-gateway for sending sms for free and open-sourced it
 - [https://www.reddit.com/r/selfhosted/comments/1hgvebm/i_made_an_smsgateway_for_sending_sms_for_free_and](https://www.reddit.com/r/selfhosted/comments/1hgvebm/i_made_an_smsgateway_for_sending_sms_for_free_and)
 - RSS feed: $source
 - date published: 2024-12-18T06:10:41+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hgvebm/i_made_an_smsgateway_for_sending_sms_for_free_and/"> <img src="https://b.thumbs.redditmedia.com/5N4Ffu1IY7NiYSmqmLSeQXs1lmDcl7rGAHf-ba0qVvw.jpg" alt="I made an sms-gateway for sending sms for free and open-sourced it" title="I made an sms-gateway for sending sms for free and open-sourced it" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I built <a href="https://textbee.dev/">textbee.dev</a>, an open-source and free SMS gateway based on Android.</p> <p>Here are the key features:</p> <ul> <li><strong>SMS Sending</strong>: Whether it&#39;s two-factor authentication (2FA), one-time passwords (OTPs), alerts, CRM integration, e-commerce delivery notifications, or any other use case your app requires, <a href="http://textbee.dev/">textbee.dev</a> enables you to send SMS directly from its dashboard or via its API.</li> <li><strong>Batch SMS</strong>: Use the API to send bulk SMS messages efficiently, making 

## Does downloading videos with yt-dlp count as ingress or egress traffic on a GCP server?
 - [https://www.reddit.com/r/selfhosted/comments/1hgupzm/does_downloading_videos_with_ytdlp_count_as](https://www.reddit.com/r/selfhosted/comments/1hgupzm/does_downloading_videos_with_ytdlp_count_as)
 - RSS feed: $source
 - date published: 2024-12-18T05:27:06+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’m running a VPS on Google Cloud Platform, and I’ve been using yt-dlp to download videos directly to my server. I’m trying to better understand how this activity is categorized in terms of GCP’s traffic policies:</p> <p><strong>Does this count as ingress (incoming) traffic to my server or egress (outgoing) traffic from it?</strong></p> <p>I know GCP typically charges for egress traffic, so I want to be sure I’m not unintentionally racking up charges.</p> <p>For context, I’m only downloading videos from external sources (like YouTube) directly to my GCP server. I haven’t yet transferred the files to another location.</p> <p>I’ve already asked various AI models, but they gave me different answers: ChatGPT and Claude said it’s inbound traffic, while Google’s Gemini said it’s outbound traffic. I’m really confused about this.</p> <p>Thanks for any insights! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit

## How to add OTP 2FA to Cloudflare tunnel
 - [https://www.reddit.com/r/selfhosted/comments/1hgum19/how_to_add_otp_2fa_to_cloudflare_tunnel](https://www.reddit.com/r/selfhosted/comments/1hgum19/how_to_add_otp_2fa_to_cloudflare_tunnel)
 - RSS feed: $source
 - date published: 2024-12-18T05:19:50+00:00

<!-- SC_OFF --><div class="md"><p>Hi, maybe this is a frequently asked question but could not find anything on any post.</p> <p>So I have a small server with some services up-and-running, most of those services are local. I have reverse proxy to access them using my domain, but there are two services that I wanted to access from the web. So I used zero trust tunnel from Cloudflare, it&#39;s a good tool but I&#39;ve always been skeptical about security, so I added some rules. I put email OTP in each of my exposed services but you&#39;d only get the code if your email is in the whitelist. And it has worked great so far, but I&#39;m getting kind of tired about it. So i started looking for a way to add TOTP to it.</p> <p>I&#39;m not sure if Cloudflare supports this natively, these exposed services are used by only 4 people. So I&#39;ll just need to generate a QR for each and they&#39;ll be able to use any authenticator they&#39;d like (Authy, Google Authenticator, Microsoft Authenticator

## Is this powerful enough?
 - [https://www.reddit.com/r/selfhosted/comments/1hgtatf/is_this_powerful_enough](https://www.reddit.com/r/selfhosted/comments/1hgtatf/is_this_powerful_enough)
 - RSS feed: $source
 - date published: 2024-12-18T04:02:59+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hgtatf/is_this_powerful_enough/"> <img src="https://b.thumbs.redditmedia.com/8vbUPX-tZDFleMmZIfXm1bGBBrO1zHFNNO9xeL2EBwU.jpg" alt="Is this powerful enough?" title="Is this powerful enough?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Planning to use for a modded Minecraft server for up to 10 friends at a time and cloud gaming not at the same time </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nick_ninj"> /u/nick_ninj </a> <br/> <span><a href="https://www.reddit.com/gallery/1hgtatf">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgtatf/is_this_powerful_enough/">[comments]</a></span> </td></tr></table>

## WordOps vs EasyEngine
 - [https://www.reddit.com/r/selfhosted/comments/1hgt9hj/wordops_vs_easyengine](https://www.reddit.com/r/selfhosted/comments/1hgt9hj/wordops_vs_easyengine)
 - RSS feed: $source
 - date published: 2024-12-18T04:01:07+00:00

<!-- SC_OFF --><div class="md"><p>I have been looking into hosting WordPress websites using Google Cloud for hosting, and Cloudflare as a CDN. While I have used EasyEngine in the past, WordOps seems to be preforming better. I just can&#39;t tell which one is better over all, or if there is another solution out there. I want something relatively easy, but I want it to be good. All of the resources I have found for these two are at least 2 years old, and I wanted to see if you guys had a different perspective.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CarlRosenthal"> /u/CarlRosenthal </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgt9hj/wordops_vs_easyengine/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgt9hj/wordops_vs_easyengine/">[comments]</a></span>

## The Future of Work: How Open Source Tools are Reshaping Enterprise Project Management
 - [https://www.reddit.com/r/selfhosted/comments/1hgt3xk/the_future_of_work_how_open_source_tools_are](https://www.reddit.com/r/selfhosted/comments/1hgt3xk/the_future_of_work_how_open_source_tools_are)
 - RSS feed: $source
 - date published: 2024-12-18T03:52:47+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hgt3xk/the_future_of_work_how_open_source_tools_are/"> <img src="https://b.thumbs.redditmedia.com/EvQQYIMttFgoqxSpVOr27LrBHjB91ltFTMsysgNeOLA.jpg" alt="The Future of Work: How Open Source Tools are Reshaping Enterprise Project Management" title="The Future of Work: How Open Source Tools are Reshaping Enterprise Project Management" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>The way we work has changed dramatically over the past decade. Remote collaboration, increasing costs, and the demand for agility are pushing businesses to rethink their project management strategies. While proprietary tools like Jira and Asana have dominated for years, <strong>open-source project management tools</strong> are rising as a cost-effective, flexible, and innovative alternative.</p> <p>Tools like <strong>WorkLenz OpenSource</strong> are at the forefront, empowering organizations to tailor project management to their unique

## I Built a Free and Open-Source CORS Proxy – Check it Out!
 - [https://www.reddit.com/r/selfhosted/comments/1hgrh3n/i_built_a_free_and_opensource_cors_proxy_check_it](https://www.reddit.com/r/selfhosted/comments/1hgrh3n/i_built_a_free_and_opensource_cors_proxy_check_it)
 - RSS feed: $source
 - date published: 2024-12-18T02:23:08+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! 👋</p> <p>I just wanted to share something I&#39;ve been working on: <a href="https://cors.lol/"><strong>CORS.lol</strong></a> – a free-to-use, open-source CORS proxy.</p> <p>If you’ve ever run into those frustrating “CORS” errors while working on your web projects, you know how annoying they can be. That’s why I created this simple tool to help developers bypass those pesky restrictions while staying lightweight and easy to use.</p> <h1>Features:</h1> <ul> <li>🚀 <strong>Free to use</strong> (no hidden fees or signups).</li> <li>📜 <strong>Open-source</strong> – so you can check out the code, contribute, or even self-host it.</li> <li>🌐 Works right out of the box for testing APIs, fetching resources, and more.</li> </ul> <p>You can give it a try at <a href="https://cors.lol/"><strong>https://cors.lol/</strong></a>. I’d love to hear your thoughts, feedback, or suggestions to make it better! Feel free to check out the repo or let me know ho

## Using KeePassXC instead of Vaultwarden
 - [https://www.reddit.com/r/selfhosted/comments/1hgqnd5/using_keepassxc_instead_of_vaultwarden](https://www.reddit.com/r/selfhosted/comments/1hgqnd5/using_keepassxc_instead_of_vaultwarden)
 - RSS feed: $source
 - date published: 2024-12-18T01:40:08+00:00

<!-- SC_OFF --><div class="md"><p>I rely on the tried-and-true <strong>KeePassXC</strong> for managing my passwords. Although I gave <strong>Vaultwarden</strong> a shot, I decided that KeePassXC better suits my needs. My encrypted password database file is stored on my main laptop and also synced with my <strong>Nextcloud server</strong>. To keep everything up-to-date, I’ve set up a <strong>cronjob</strong> that syncs the database file from my laptop to Nextcloud every 4 hours [using rclone].</p> <p>For backups, I include the database file in my <strong>dotfiles</strong>, which is synced across two private <strong>Git repositories</strong> [one in GitLab, the other in BitBucket] whenever I commit and push changes. This ensures the same updates are reflected on my secondary laptop as well. On mobile, I use the <strong>KeePassDX</strong> app for Android, which allows me to conveniently import the database file from Nextcloud.</p> <p>When I&#39;m away from my homelab, I rely on <strong>

## ZeroTier First Timer questions
 - [https://www.reddit.com/r/selfhosted/comments/1hgqltw/zerotier_first_timer_questions](https://www.reddit.com/r/selfhosted/comments/1hgqltw/zerotier_first_timer_questions)
 - RSS feed: $source
 - date published: 2024-12-18T01:37:56+00:00

<!-- SC_OFF --><div class="md"><p>Firstly let me start by saying, am I dumb to think I was going to be able to connect through the tunnel using my local IP address (192.168.0.200) lol. </p> <p>Anyway, thats my first question - its kind of painful to type in this ugly IP addy that ZeroTier assigns. What are my options?</p> <p>Second question, I don&#39;t really want to turn on UPnP and would prefer to assign ZeroTier a specific Port but how ? I dont see a setting for that in the client -- is this even an option?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/joshhazel1"> /u/joshhazel1 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgqltw/zerotier_first_timer_questions/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgqltw/zerotier_first_timer_questions/">[comments]</a></span>

## How to scale up from my first Server
 - [https://www.reddit.com/r/selfhosted/comments/1hgpwai/how_to_scale_up_from_my_first_server](https://www.reddit.com/r/selfhosted/comments/1hgpwai/how_to_scale_up_from_my_first_server)
 - RSS feed: $source
 - date published: 2024-12-18T01:01:52+00:00

<!-- SC_OFF --><div class="md"><p>Hello!</p> <p>I was able to snag a Dell Optiplex 7010 running a i7-3770 with 16gb of DDR2 Ram for free!</p> <p>I currently have a 120gb SSD running Ubuntu and soon will be installing a 4TB Seagate Ironwolf 4TB HDD. I have been messing around with it and was able to naviagte my way through Samba and Plex. I would like to turn this into a NAS so I can back up important documents such as SSN cards, Birth Certificates, contracts, other important documents. While running a NAS, to also store my DVDs in my collection (I have compressed movies and shows to ~5gb or less using MakeMKV and HandBrake) and play them from any device in my house using Plex. Lastly, I would also like to run some virtual desktops such as Windows 11 and other Linux Distros for work. I would like to learn how to be a Linux Admin and potentially a Windows Admin. So having something like that at home to learn on would be nice. Nice to have but not needed, but maybe run a minecraft serve

## Tailscale Vs Netbird. And go!
 - [https://www.reddit.com/r/selfhosted/comments/1hgpjiy/tailscale_vs_netbird_and_go](https://www.reddit.com/r/selfhosted/comments/1hgpjiy/tailscale_vs_netbird_and_go)
 - RSS feed: $source
 - date published: 2024-12-18T00:44:12+00:00

<!-- SC_OFF --><div class="md"><p>Personally, I use netbird because of the SSO and no limit on users. Not to mention being in control of the main server is a nice touch.</p> <p>Tell me your reasons for picking one over the other!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Srslywtfnoob92"> /u/Srslywtfnoob92 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgpjiy/tailscale_vs_netbird_and_go/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgpjiy/tailscale_vs_netbird_and_go/">[comments]</a></span>

## Self-Hosted Music App
 - [https://www.reddit.com/r/selfhosted/comments/1hgp4z7/selfhosted_music_app](https://www.reddit.com/r/selfhosted/comments/1hgp4z7/selfhosted_music_app)
 - RSS feed: $source
 - date published: 2024-12-18T00:23:45+00:00

<!-- SC_OFF --><div class="md"><p>I have a home server running Proxmox &gt; TrueNas &gt; Jellyfin. I&#39;m added my music collection to Jellyfin. However, while it does exactly what I need on the movie playback experience front, the music playback side of things is a bit lackluster imo. My biggest complaint is that it generally lack DLNA/UpNp capabilities, and I&#39;m not overly fond of the presentation.</p> <p>I&#39;m looking for an app that runs both on android and on windows desktop. I&#39;ve tried Symphonium, which I find great, but they don&#39;t have a desktop app. In practice, given that I playback from multiple laptops, I&#39;d have to maintain playlists accross multiple services ( e.g. Symphonium, Jellyfin, FooBar) Or just use Jellyfin and live without some features.</p> <p>I was wondering if there was a better solution out there? I&#39;ve tried Plex, but I&#39;m facing an issue where the app can see my server but views it as offline. </p> </div><!-- SC_ON --> &#32; submitte

## Stupid question but I'm curious
 - [https://www.reddit.com/r/selfhosted/comments/1hgow6n/stupid_question_but_im_curious](https://www.reddit.com/r/selfhosted/comments/1hgow6n/stupid_question_but_im_curious)
 - RSS feed: $source
 - date published: 2024-12-18T00:11:56+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to set up homepage and when I use the run command that they gave on the website it says that port is already taken, can I change the 3000 port to something different or will in not work then? If I can&#39;t is there a easy solution to fix this issue?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Nategames64"> /u/Nategames64 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgow6n/stupid_question_but_im_curious/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hgow6n/stupid_question_but_im_curious/">[comments]</a></span>

