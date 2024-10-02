# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Issue with file uploads (Autumn) on self-hosted Revolt on Windows 11 using Docker
 - [https://www.reddit.com/r/selfhosted/comments/1fu2xp2/issue_with_file_uploads_autumn_on_selfhosted](https://www.reddit.com/r/selfhosted/comments/1fu2xp2/issue_with_file_uploads_autumn_on_selfhosted)
 - RSS feed: $source
 - date published: 2024-10-01T23:58:53+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,<br/> This is one of my first Reddit posts, so I hope I’m doing this right! I’m trying to self-host Revolt following the <a href="https://github.com/revoltchat/self-hosted/">official </a>repo on my Windows 11 machine using Docker.</p> <p>Everything works fine except for file uploads (Autumn endpoint). I followed the guide step by step and tried several solutions, but after hours of debugging, I still can’t figure out what’s wrong.</p> <p>If anyone has experience with this or any advice, I’d be super grateful. I’ve been stuck for hours, and this feels like my last option. I&#39;m also open to jumping on a Discord or Revolt call if you&#39;d prefer to troubleshoot together in real-time. </p> <p>Thanks so much in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MirkoHubTV"> /u/MirkoHubTV </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fu2xp2/issue_with_file_uploads_autumn

## piped self-hosting with traefik
 - [https://www.reddit.com/r/selfhosted/comments/1fu2vrk/piped_selfhosting_with_traefik](https://www.reddit.com/r/selfhosted/comments/1fu2vrk/piped_selfhosting_with_traefik)
 - RSS feed: $source
 - date published: 2024-10-01T23:56:09+00:00

<!-- SC_OFF --><div class="md"><p>I need help getting piped to work with traefik, according to their <a href="https://github.com/TeamPiped/Documentation/blob/main/content/docs/self-hosting/index.md">documentation</a> the below should work. Traefik works with other services, just none of them have multiple host names or use another nginx container.</p> <pre><code>labels: - &quot;traefik.enable=true&quot; - &quot;traefik.http.routers.piped.rule=Host(`piped.tld`) || Host(`pipedapi.tld`) || Host(`pipedproxy.tld`)&quot; - &quot;traefik.http.routers.piped.entrypoints=https&quot; </code></pre> <p>I&#39;ve changed the tlds in the labels, and changed the entrypoint to https.</p> <p>here&#39;s my traefik.config - cert resolver section</p> <pre><code>api: dashboard: true debug: true entryPoints: http: address: &quot;:80&quot; http: redirections: entryPoint: to: https scheme: https https: address: &quot;:443&quot; serversTransport: insecureSkipVerify: true providers: docker: endpoint: &quot;unix:

## Expose service being Nordlynx
 - [https://www.reddit.com/r/selfhosted/comments/1fu2alg/expose_service_being_nordlynx](https://www.reddit.com/r/selfhosted/comments/1fu2alg/expose_service_being_nordlynx)
 - RSS feed: $source
 - date published: 2024-10-01T23:27:50+00:00

<!-- SC_OFF --><div class="md"><p>So plain and simple no matter what allowed_ips or net_local i setup i can&#39;t seem to access a service (chrome docker) that&#39;s behind a vpn. If i use 0.0.0.0/1 in allowed ips i can access the container behind nordlynx but there&#39;s no internet. If i remove that from compose file the host only can access the service but it&#39;s properly running behind the vpn. I&#39;m not sure what configuration I&#39;m not setting up properly. Any suggestions appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CLEcoder4life"> /u/CLEcoder4life </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fu2alg/expose_service_being_nordlynx/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fu2alg/expose_service_being_nordlynx/">[comments]</a></span>

## First time self hosting
 - [https://www.reddit.com/r/selfhosted/comments/1fu20za/first_time_self_hosting](https://www.reddit.com/r/selfhosted/comments/1fu20za/first_time_self_hosting)
 - RSS feed: $source
 - date published: 2024-10-01T23:15:03+00:00

<!-- SC_OFF --><div class="md"><p>I recently acquired a ThinkCentre M900 and I would like to start self-hosting, but I&#39;m unsure where to begin. I&#39;m interested in setting up a Proxmox server for hosting services like Nextcloud and running virtual machines. I need guidance on how to set up the server, exposing it to the internet, and ensure security.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ImFirulais"> /u/ImFirulais </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fu20za/first_time_self_hosting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fu20za/first_time_self_hosting/">[comments]</a></span>

## ldapAuth for Traefik
 - [https://www.reddit.com/r/selfhosted/comments/1fu0t5d/ldapauth_for_traefik](https://www.reddit.com/r/selfhosted/comments/1fu0t5d/ldapauth_for_traefik)
 - RSS feed: $source
 - date published: 2024-10-01T22:19:21+00:00

<!-- SC_OFF --><div class="md"><p>has anyone configured and got this working offline without reaching out to internet for plugin files?</p> <p>using dockerfile, compose, </p> <p><a href="https://plugins.traefik.io/plugins/628c9eb7ffc0cd18356a979c/ldap-auth">https://plugins.traefik.io/plugins/628c9eb7ffc0cd18356a979c/ldap-auth</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/networkguy87"> /u/networkguy87 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fu0t5d/ldapauth_for_traefik/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fu0t5d/ldapauth_for_traefik/">[comments]</a></span>

## Recommendations for me?
 - [https://www.reddit.com/r/selfhosted/comments/1fu0iji/recommendations_for_me](https://www.reddit.com/r/selfhosted/comments/1fu0iji/recommendations_for_me)
 - RSS feed: $source
 - date published: 2024-10-01T22:06:11+00:00

<!-- SC_OFF --><div class="md"><p>Hi all apologies if these questions have been asked but I’m looking for the following:</p> <ul> <li><p>home server to backup all my files and photos </p></li> <li><p>cross platform </p></li> <li><p>accessible from different OSs and away from the home </p></li> <li><p>affordable 😂 Say 200 USD upfront </p></li> <li><p>want 2/3 back ups of everything </p></li> <li><p>secure </p></li> <li><p>energy efficient machine </p></li> <li><p>easy set up and minimal / 0 maintenance </p></li> <li><p>I have less than 1TB of stuff to back up probably closer to 300gb so not a lot at all</p></li> <li><p>something that doesn’t require crazy fast internet </p></li> </ul> <p>is what I’m looking for feasible or am I asking for too much. </p> <p>any suggestions help advice or pointing in the right redirection would be greatly appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Difficult_Patient413"> /u/Difficult_Patient413 </a>

## How are you self hosting your blog ?
 - [https://www.reddit.com/r/selfhosted/comments/1fu0ga6/how_are_you_self_hosting_your_blog](https://www.reddit.com/r/selfhosted/comments/1fu0ga6/how_are_you_self_hosting_your_blog)
 - RSS feed: $source
 - date published: 2024-10-01T22:03:24+00:00

<!-- SC_OFF --><div class="md"><p>Hello, ive recently attempted to self host a blog, by the research i think hugo is a good fit, i want a static site.<br/> I want to run it on docker, but as soon as i try and add themes to it, everything breaks, anyone have a tutorial i can follow using Hugo with Docker utilizing themes?</p> <p>I´ll be open to other suggestions but my basic requirements are:</p> <ul> <li> Static (easy to write code in MarkDown) </li> <li>Docker (easy to spin up via docker-compose) </li> <li>Themes (it has to look pretty right?) </li> <li>Bonus: if it supports comments in the blog</li> </ul> <p>And please do share your blogs i want to see what the community has.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Luis15pt"> /u/Luis15pt </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fu0ga6/how_are_you_self_hosting_your_blog/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1f

## Problems with port 443 on localhost while configuring Pterodactyl
 - [https://www.reddit.com/r/selfhosted/comments/1ftzt7v/problems_with_port_443_on_localhost_while](https://www.reddit.com/r/selfhosted/comments/1ftzt7v/problems_with_port_443_on_localhost_while)
 - RSS feed: $source
 - date published: 2024-10-01T21:35:45+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m having some problems with the port 443 on localhost. I&#39;ve just created the docker with pterodactyl and I can acces to http:// localhost and login, but, when I try to enter to some options like managing databases, locations, nodes... it redirects me to https:// localhost and it doesn&#39;t load:<br/> <code>This site can’t be reached</code></p> <p><code>localhost unexpectedly closed the connection.</code></p> <p><code>Try:</code></p> <p><code>Checking the connection</code></p> <p><code>Checking the proxy and the firewall</code></p> <p><code>ERR_CONNECTION_CLOSED</code></p> <p>I think the problem is that there is something on my computer (yes im doing it on a computer, I still don&#39;t have a server) that is using the port 443, but I don&#39;t know what it is.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Crafty_Clock_8502"> /u/Crafty_Clock_8502 </a> <br/> <span><a href="https://www.reddit.com/r/selfh

## Content added by Sonarr or Radarr shows up twice on Emby
 - [https://www.reddit.com/r/selfhosted/comments/1ftzha8/content_added_by_sonarr_or_radarr_shows_up_twice](https://www.reddit.com/r/selfhosted/comments/1ftzha8/content_added_by_sonarr_or_radarr_shows_up_twice)
 - RSS feed: $source
 - date published: 2024-10-01T21:21:16+00:00

<!-- SC_OFF --><div class="md"><p>So I setup these services and works nicely. But when I request a movie through Ombi and it’s passed through all the channels and downloaded, it shows up on Emby twice. I checked the both movies on emby and it’s essentially the same thing. </p> <p>Download client initially downloads to</p> <p>/location/to/media.mkv</p> <p>But then there is another folder created about 8 minutes later in following format</p> <p>/location/to/media2024/media.mkv</p> <p>I can’t figure out why this happens. I tried checking the media management on Radarr, tried unticking the “symbolic links”, tried unticking “rename the movie” setting but nothing helped. Any ideas? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/robot2243"> /u/robot2243 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftzha8/content_added_by_sonarr_or_radarr_shows_up_twice/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhos

## Minimum Specs for MailCow
 - [https://www.reddit.com/r/selfhosted/comments/1ftzbak/minimum_specs_for_mailcow](https://www.reddit.com/r/selfhosted/comments/1ftzbak/minimum_specs_for_mailcow)
 - RSS feed: $source
 - date published: 2024-10-01T21:14:28+00:00

<!-- SC_OFF --><div class="md"><p>I was playing around with MailCow on Google Cloud 1Ram 1cpu and it seems that it doesn’t work very well. </p> <p>I will consider using Hetzner</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/anonuser-al"> /u/anonuser-al </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftzbak/minimum_specs_for_mailcow/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftzbak/minimum_specs_for_mailcow/">[comments]</a></span>

## Firefly iii - Personal & business finance use- important ques
 - [https://www.reddit.com/r/selfhosted/comments/1ftz2yf/firefly_iii_personal_business_finance_use](https://www.reddit.com/r/selfhosted/comments/1ftz2yf/firefly_iii_personal_business_finance_use)
 - RSS feed: $source
 - date published: 2024-10-01T21:04:32+00:00

<!-- SC_OFF --><div class="md"><p>Hi- coming from quicken and was considering Gnucash, then read issues about its inability to &quot;mass-change&quot; transactions in register view and &quot;recategorize or mass-change&quot; Payee field etc., hence considering Firefly III. Sorry for the slightly long&#39;ish post but thought clarification below could help not just me but countless others in same boat:</p> <p> </p> <ol> <li>I&#39;m zero in coding! but somehow struggled and installed firefly using docker (Win 10 PC) but then got really worried (!) as it started asking for running codes for basic work and then I didn&#39;t know where was my data files were being saved :) - so where can I learn basics about it- about where my files are, how is access controlled to them. I hope it&#39;s just 1 big file (like quicken) that I need to backup for bad times! And finally, is that file (operable in emergency and convertible to say OFX) just in case firefly is unreachable ;).</li> </ol> <p> </p> <

## cheap service for hosting app sometimes
 - [https://www.reddit.com/r/selfhosted/comments/1ftytcf/cheap_service_for_hosting_app_sometimes](https://www.reddit.com/r/selfhosted/comments/1ftytcf/cheap_service_for_hosting_app_sometimes)
 - RSS feed: $source
 - date published: 2024-10-01T20:53:17+00:00

<!-- SC_OFF --><div class="md"><p>i need a small server to host my game server, is there a good services with good pricing?<br/> requirements 1 cpu, 1 gb ram, up to 25gb disk space<br/> up time will be i think something like 60 hrs \ month<br/> found service with pricing of 4$/month </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Solaris5000"> /u/Solaris5000 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftytcf/cheap_service_for_hosting_app_sometimes/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftytcf/cheap_service_for_hosting_app_sometimes/">[comments]</a></span>

## I've grown sick of WebUntis not sending Push notifications, so I did it myself. You can too!
 - [https://www.reddit.com/r/selfhosted/comments/1fty771/ive_grown_sick_of_webuntis_not_sending_push](https://www.reddit.com/r/selfhosted/comments/1fty771/ive_grown_sick_of_webuntis_not_sending_push)
 - RSS feed: $source
 - date published: 2024-10-01T20:27:42+00:00

<!-- SC_OFF --><div class="md"><p>One thing that has been bugging me about <a href="https://webuntis.com">WebUntis</a> (Which is an exceptional platform for managing schools) is that students don&#39;t get push notifications for changed periods.</p> <p>Thats why I created <a href="https://github.com/maxbossing/webuntisnotifier">WebUntisNotifier</a>, A selfhostable docker container to send yourself notifications when something in your timetable changes!</p> <p>It&#39;s extremely easy to set up: It&#39;s just acontainer and a config file, and it will periodically check for changes in your timetable and notify you about them.</p> <p>It&#39;s still in active development and I&#39;m currently working on new features (like multiple users per container) and it would really help me out if you&#39;d check it out!</p> <p><a href="https://github.com/maxbossing/WebUntisNotifier">https://github.com/maxbossing/WebUntisNotifier</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://w

## Why do you use proxmox?
 - [https://www.reddit.com/r/selfhosted/comments/1ftxtbd/why_do_you_use_proxmox](https://www.reddit.com/r/selfhosted/comments/1ftxtbd/why_do_you_use_proxmox)
 - RSS feed: $source
 - date published: 2024-10-01T20:11:40+00:00

<!-- SC_OFF --><div class="md"><p>Hello <strong>everyone</strong>! </p> <p>I am approaching the world of self-hosting,but I have to many of you using proxmox,why?</p> <p>Why don&#39;t you use ubuntu server and use docker?</p> <p>I have installed Proxmox and am <strong>testing</strong> a few things (although due to my hard drive I have a high IO delay). </p> <p>If I don&#39;t want to use proxmox, other solutions?</p> <p>thanks to everyone!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Debate7112"> /u/Debate7112 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftxtbd/why_do_you_use_proxmox/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftxtbd/why_do_you_use_proxmox/">[comments]</a></span>

## What is your eBook kindle workflow?
 - [https://www.reddit.com/r/selfhosted/comments/1ftxlob/what_is_your_ebook_kindle_workflow](https://www.reddit.com/r/selfhosted/comments/1ftxlob/what_is_your_ebook_kindle_workflow)
 - RSS feed: $source
 - date published: 2024-10-01T20:03:04+00:00

<!-- SC_OFF --><div class="md"><p>I want to simplify my workflow to a single point for my end users (a couple family members). </p> <p>Current flow:</p> <p>Add/discover books- goodreads.com they add anything they want to their bookshelf. </p> <p>Download- readarr watches their bookshelves on goodreads and downloads anything they add. </p> <p>eBook viewer/send to kindle- audio bookshelf. It has the nice option of sending to email and they could read the book on the web app if they want. </p> <p>What I’d like to do is have both the add/discover and viewer/send to kindle be the same application. That way it’s a one stop shop and not two websites to swap between. </p> <p>Any ideas?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ZealousidealEntry870"> /u/ZealousidealEntry870 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftxlob/what_is_your_ebook_kindle_workflow/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/

## Which media server software has free GPU acceleration?
 - [https://www.reddit.com/r/selfhosted/comments/1ftws7z/which_media_server_software_has_free_gpu](https://www.reddit.com/r/selfhosted/comments/1ftws7z/which_media_server_software_has_free_gpu)
 - RSS feed: $source
 - date published: 2024-10-01T19:29:45+00:00

<!-- SC_OFF --><div class="md"><p>Emby does not so it is time for me to move on.</p> <p>Plex does not, either.</p> <p>I am unsure about Jellyfin?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ebridgewater"> /u/ebridgewater </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftws7z/which_media_server_software_has_free_gpu/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftws7z/which_media_server_software_has_free_gpu/">[comments]</a></span>

## Recommended OS for New Server Build
 - [https://www.reddit.com/r/selfhosted/comments/1ftw68r/recommended_os_for_new_server_build](https://www.reddit.com/r/selfhosted/comments/1ftw68r/recommended_os_for_new_server_build)
 - RSS feed: $source
 - date published: 2024-10-01T19:04:53+00:00

<!-- SC_OFF --><div class="md"><p>Hey there. I&#39;m currently running unRAID on a media server in my home, but I&#39;m frustrated by the performance sometimes. In particular, I&#39;ve really been bummed out by the read/write performance (to the point that I have to reboot to get syncs to perform better, etc.). I have some cache drives set up and Dockers, etc. live on an SSD. I have spinning disks for storage.</p> <p>I have used FreeNAS in the past, and even spun up TrueNAS Scale for a little while. Felt like a real learning curve, though I really like ZFS for a lot of reasons (unRAID doesn&#39;t do that natively). I can use ZFS with Ubuntu, etc., and even set up a server with Ubuntu but went back to unRAID for ease of use (it&#39;s pretty slick, but not as performant).</p> <p>If I build another server (possible soon), I&#39;m wondering what people&#39;s thoughts on OS choice are. I&#39;m not afraid to get my hands dirty, and I&#39;m not really very knowledgeable about things, but I c

## Do yall give back to the community?
 - [https://www.reddit.com/r/selfhosted/comments/1ftw4qw/do_yall_give_back_to_the_community](https://www.reddit.com/r/selfhosted/comments/1ftw4qw/do_yall_give_back_to_the_community)
 - RSS feed: $source
 - date published: 2024-10-01T19:03:12+00:00

<!-- SC_OFF --><div class="md"><p>I was trying to think of ways to give back to the community for providing all of these wonderful pieces of software. I give financially when I am able to, but I understand that’s not for everyone (or even myself at times). What are other ways we can give back? This is me spit balling:</p> <p>Give feedback on GitHub (bugs, features you’d like to see, steps setting it up)</p> <p>Help with the code base (side question - what language is best to know to help out?)</p> <p>Help others on Reddit, FB Pages, Forums, etc</p> <p>Share what software you use so it can get more exposure </p> <p>What are y’all’s thoughts?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TXAGZ16"> /u/TXAGZ16 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftw4qw/do_yall_give_back_to_the_community/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftw4qw/do_yall_give_back_to_the_community

## PSA: Update Nvidia Container Toolkit Soon!
 - [https://www.reddit.com/r/selfhosted/comments/1ftvryz/psa_update_nvidia_container_toolkit_soon](https://www.reddit.com/r/selfhosted/comments/1ftvryz/psa_update_nvidia_container_toolkit_soon)
 - RSS feed: $source
 - date published: 2024-10-01T18:49:27+00:00

<!-- SC_OFF --><div class="md"><p>Version 1.16.2 fixes some security issues with NVIDIA Container Toolkit 1.16.1 and earlier, and GPU Operator 24.6.1 and older:</p> <ul> <li><a href="https://nvidia.custhelp.com/app/answers/detail/a_id/5582">NVIDIA CVE-2024-0132</a></li> <li><a href="https://nvidia.custhelp.com/app/answers/detail/a_id/5582">NVIDIA CVE-2024-0133</a></li> </ul> <p>release notes: <a href="https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/release-notes.html">https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/release-notes.html</a></p> <blockquote> <p>Article: <a href="https://www.bleepingcomputer.com/news/security/critical-flaw-in-nvidia-container-toolkit-allows-full-host-takeover/">https://www.bleepingcomputer.com/news/security/critical-flaw-in-nvidia-container-toolkit-allows-full-host-takeover/</a> </p> </blockquote> <p>&quot;Technical details for the exploiting the security issue remain private for now, to give impacted organ

## Those of you who self host media services; how do you find new stuff to watch?
 - [https://www.reddit.com/r/selfhosted/comments/1ftvnbi/those_of_you_who_self_host_media_services_how_do](https://www.reddit.com/r/selfhosted/comments/1ftvnbi/those_of_you_who_self_host_media_services_how_do)
 - RSS feed: $source
 - date published: 2024-10-01T18:44:11+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m contemplating rolling out jellyfin or plex. How do you find new shows and titles you want to add to your media collections? Please note I&#39;m emphatically NOT asking where to get the actual media.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/scor_butus"> /u/scor_butus </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftvnbi/those_of_you_who_self_host_media_services_how_do/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftvnbi/those_of_you_who_self_host_media_services_how_do/">[comments]</a></span>

## Security on Tailscale+Cloudflare Tunnel
 - [https://www.reddit.com/r/selfhosted/comments/1ftum6m/security_on_tailscalecloudflare_tunnel](https://www.reddit.com/r/selfhosted/comments/1ftum6m/security_on_tailscalecloudflare_tunnel)
 - RSS feed: $source
 - date published: 2024-10-01T18:01:46+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,<br/> I just repurposed a laptop to be a samba, qbittorrent, foundryvtt and jellyfin client.<br/> For personal uses samba/qbittorrent etc., tailscale is fine. However for FoundryVTT i managed to make cloudflare tunnels and plan to also do the same to my jellyfin instance.<br/> I am running debian headless. As a beginner, i am not sure of safety, and i think cloudflare protects the tunnels? Any help for a self hosting newbie?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DefNot_A_Reddit_User"> /u/DefNot_A_Reddit_User </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftum6m/security_on_tailscalecloudflare_tunnel/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftum6m/security_on_tailscalecloudflare_tunnel/">[comments]</a></span>

## Hi, hardware recommendation
 - [https://www.reddit.com/r/selfhosted/comments/1fttuw2/hi_hardware_recommendation](https://www.reddit.com/r/selfhosted/comments/1fttuw2/hi_hardware_recommendation)
 - RSS feed: $source
 - date published: 2024-10-01T17:30:58+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys! New to this beautiful world but quiet comfortable with windows and linux</p> <p>I&#39;m sure you have the answer...</p> <p>I want to run a jellyfik server (netflix+prime+Disney... that shit is becoming expensive), and a cloud for all my personal (family) photo and videos </p> <p>The whole thing should be backup itself and have quiet expandable capability (I can start with 10tb but sure I&#39;ll need to expand in the future..)</p> <p>What platform do you suggest as cost effective solution?</p> <p>Thx a lot</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/skakrew"> /u/skakrew </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fttuw2/hi_hardware_recommendation/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fttuw2/hi_hardware_recommendation/">[comments]</a></span>

## Cloudflare Zero Trust Question
 - [https://www.reddit.com/r/selfhosted/comments/1fttlzy/cloudflare_zero_trust_question](https://www.reddit.com/r/selfhosted/comments/1fttlzy/cloudflare_zero_trust_question)
 - RSS feed: $source
 - date published: 2024-10-01T17:21:01+00:00

<!-- SC_OFF --><div class="md"><p>Has anyone successfully created an app in zero trust that is </p> <p>*.domain.com</p> <p>So effectively all your exposed services are automatically included.</p> <p>Mine seems to cause an endless loop when loading the access page.</p> <p>I have set the cookies same site setting to lax but it hasn&#39;t helped.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/elliottmarter"> /u/elliottmarter </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fttlzy/cloudflare_zero_trust_question/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fttlzy/cloudflare_zero_trust_question/">[comments]</a></span>

## Setting Up My Homelab!
 - [https://www.reddit.com/r/selfhosted/comments/1ftt6et/setting_up_my_homelab](https://www.reddit.com/r/selfhosted/comments/1ftt6et/setting_up_my_homelab)
 - RSS feed: $source
 - date published: 2024-10-01T17:03:21+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ftt6et/setting_up_my_homelab/"> <img src="https://b.thumbs.redditmedia.com/n6VatNy2hpsE1KkofJ8KJaXmOs3sQpzEmbFo05D8RGU.jpg" alt="Setting Up My Homelab!" title="Setting Up My Homelab!" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I&#39;m ready to build my homelab and am considering using a mini PC to host it. Would love to hear some suggestions from the community!</p> <p><a href="https://preview.redd.it/8eegile0f6sd1.png?width=844&amp;format=png&amp;auto=webp&amp;s=1971bfe7d1e3fe64b2fdb188ec3db1fd3c554c6b">https://preview.redd.it/8eegile0f6sd1.png?width=844&amp;format=png&amp;auto=webp&amp;s=1971bfe7d1e3fe64b2fdb188ec3db1fd3c554c6b</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/crotjorse"> /u/crotjorse </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftt6et/setting_up_my_homelab/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/

## Does switching from AGH to Technitium make sense for my use case?
 - [https://www.reddit.com/r/selfhosted/comments/1ftt1lo/does_switching_from_agh_to_technitium_make_sense](https://www.reddit.com/r/selfhosted/comments/1ftt1lo/does_switching_from_agh_to_technitium_make_sense)
 - RSS feed: $source
 - date published: 2024-10-01T16:58:08+00:00

<!-- SC_OFF --><div class="md"><p>So for context I currently have AdGuard Home running in an LXC on a Proxmox server. My router is configured to use it for DNS, and it uses ControlD as an upstream which in theory catches whatever it misses and is great performance wise. The only reason I&#39;m using it is to block ads - there&#39;s no local DNS record for my homelab or anything. I&#39;ve been debating setting up Technitium instead for a while since it gets recommended a lot, but I genuinely don&#39;t know if there&#39;s any benefit. Can someone walk me through the key advantages of Technitium over AGH and help me figure out whether they&#39;re applicable to this setup?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ACEDT"> /u/ACEDT </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftt1lo/does_switching_from_agh_to_technitium_make_sense/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ft

## Cheaper dynamic DNS with owned domain name options?
 - [https://www.reddit.com/r/selfhosted/comments/1fts2pp/cheaper_dynamic_dns_with_owned_domain_name_options](https://www.reddit.com/r/selfhosted/comments/1fts2pp/cheaper_dynamic_dns_with_owned_domain_name_options)
 - RSS feed: $source
 - date published: 2024-10-01T16:18:56+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone.</p> <p>I am currently using an ISP that is offering a fairly cheap static IP option (~$5/mo) which I am using. I have two owned domains which I am hosting in my own server and having that static IP is important for easy outside access.</p> <p>Unfortunately, this ISP isn&#39;t offering the speeds I would like to have. Some competitors (that are active in my area) do, but they do not offer static IPs unless you purchase a &quot;business&quot; package which is double or triple the price bundling in things I have zero interest for.</p> <p>I&#39;m therefore considering some sort of dynamic DNS solution that would allow me to connect my own domain (e.g. xyz.com) to my dynamic IP. The only one I&#39;ve found so far that reliably does that is no-ip.com, but they charge $15 per month for 50 hostnames, which I have no use for. I&#39;ll pay it if I have to (still cheaper than the ISP business crap), but thought I&#39;d ask you fine people first for

## Reverse Proxy multiple VMs
 - [https://www.reddit.com/r/selfhosted/comments/1ftryhq/reverse_proxy_multiple_vms](https://www.reddit.com/r/selfhosted/comments/1ftryhq/reverse_proxy_multiple_vms)
 - RSS feed: $source
 - date published: 2024-10-01T16:13:45+00:00

<!-- SC_OFF --><div class="md"><p>Just a sanity check. </p> <p>I would like to have a mixed pool of docker services some accessible publically and others are accessible only from home network. I own one domain. I know that it best practice to forward ports to a DMZ network where my reverse proxy Traefik resides. All other services are on a separate VLAN. </p> <p>What is the most practical way to connect to proxy my services: - Reverse proxy dispatcher to VMs with their own reverse proxy. Ideal but difficult to setup and troubleshoot - docker swarm: not sure of workable accrss vlans if I allow the needs ports accross VMs. - use separate domains for external and internal services, but I don&#39;t want to manage multiple domains. The easiest to setup. -use one reverse proxy and allow services:port for each internal service but it is too many rules to create on my *sense firewall</p> <p>Happy to hear your input. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddi

## Looking for Contributors for The0dinProject
 - [https://www.reddit.com/r/selfhosted/comments/1ftrij0/looking_for_contributors_for_the0dinproject](https://www.reddit.com/r/selfhosted/comments/1ftrij0/looking_for_contributors_for_the0dinproject)
 - RSS feed: $source
 - date published: 2024-10-01T15:55:08+00:00

<!-- SC_OFF --><div class="md"><p>Hey! We’re working on 0din, a decentralized, federated file hosting platform, and we could really use some help from fellow open-source enthusiasts.</p> <p><strong>Right now, we’re in the alpha stage, so there’s a lot of room to contribute and make an impact. What We Need:</strong></p> <ul> <li>Backend devs who know Flask and PostgreSQL—especially if you’ve played around with distributed systems.</li> <li>Frontend devs who can make our UI suck less.</li> <li>Someone who knows docker to help us get this thing running smoothly in containers.</li> <li>Security geeks who want to lock things down and keep the platform solid.</li> <li>Anyone who loves writing docs and can explain things clearly (we’re not good at this).</li> </ul> <p><strong>Why You Should Join:</strong></p> <p>We’re a small team figuring things out as we go. If you’re into learning and building something cool without all the formalities, come hang out! You’ll get hands-on experience with s

## vps to server
 - [https://www.reddit.com/r/selfhosted/comments/1ftrb5c/vps_to_server](https://www.reddit.com/r/selfhosted/comments/1ftrb5c/vps_to_server)
 - RSS feed: $source
 - date published: 2024-10-01T15:46:30+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,<br/> i am currently in the process of re configuring how i access my server. currently i have HTTP and HTTPS port open in my router that are directed at a raspberry, from here i run a reverse proxy to my other servers. Now i have found a really cheap VPS and now want to use tunnels so i don&#39;t have open ports in my home router.</p> <p>I don&#39;t know where to start and what the best practices are for tunneling. It should support ftp, ssh (to multiple different machines), HTTP and HTTPS</p> <p>for reverse proxy i am using nginx-proxy-manager</p> <p>If anyone could give some advice it would be really appreciated!!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kajvans"> /u/kajvans </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftrb5c/vps_to_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftrb5c/vps_to_server/">[comments]</a></s

## Why doesn't Firefly allow another day as the start of the month?
 - [https://www.reddit.com/r/selfhosted/comments/1ftr8n9/why_doesnt_firefly_allow_another_day_as_the_start](https://www.reddit.com/r/selfhosted/comments/1ftr8n9/why_doesnt_firefly_allow_another_day_as_the_start)
 - RSS feed: $source
 - date published: 2024-10-01T15:43:37+00:00

<!-- SC_OFF --><div class="md"><p>From their <a href="https://docs.firefly-iii.org/explanation/more-information/what-its-not/#changing-the-monthly-cycle-to-another-day-of-the-month">Missing Features Page</a>:</p> <blockquote> <p><strong>Changing the monthly cycle to another day of the month.</strong></p> <p>A month goes from the 1st to the last day of the month. You can&#39;t tell Firefly III to go from the 23rd to the 22nd of the next month.</p> </blockquote> <p>I don&#39;t understand what design choices or limitations could apply. This is kind of a deal breaker for me because my monthly income arrives before the start of the next month.<br/> I&#39;d very much like to understand why this is.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Explorerfriend"> /u/Explorerfriend </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftr8n9/why_doesnt_firefly_allow_another_day_as_the_start/">[link]</a></span> &#32; <span><a href="https

## Google Photos self hosted alternative - daily/weekly pic montage from 1-2-5 years ago on this date
 - [https://www.reddit.com/r/selfhosted/comments/1ftqp70/google_photos_self_hosted_alternative_dailyweekly](https://www.reddit.com/r/selfhosted/comments/1ftqp70/google_photos_self_hosted_alternative_dailyweekly)
 - RSS feed: $source
 - date published: 2024-10-01T15:21:02+00:00

<!-- SC_OFF --><div class="md"><p>Since google stopped providing unlimited picture upload, I&#39;m missing the feature when it showed me pictures every morning what we did 1-2-3-5 years ago on this day or week.</p> <p>2 years ago I started searching and testing selfhosted picture uploaders with no luck. I use dropbox to upload pictures to my server and I have a nice 1tb+ pictures folders about my family, and I really really want to see how the children looked like 2-5 years ago. :)<br/> Anyone knows a program I can selfhost in docker and has an ANDROID app to show montages and pictures randomly in the morning?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Merwenus"> /u/Merwenus </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftqp70/google_photos_self_hosted_alternative_dailyweekly/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftqp70/google_photos_self_hosted_alternative_dailyweekl

## Not so wild, sefl hosted email?
 - [https://www.reddit.com/r/selfhosted/comments/1ftq8ao/not_so_wild_sefl_hosted_email](https://www.reddit.com/r/selfhosted/comments/1ftq8ao/not_so_wild_sefl_hosted_email)
 - RSS feed: $source
 - date published: 2024-10-01T15:01:24+00:00

<!-- SC_OFF --><div class="md"><p>Has anyone tinkered with the idea of self-hosting an entirely local email server entirely over a mesh network (nebula, tailscale etc)?</p> <p>I&#39;m waiting for project work to be approved and started thinking about the concept.</p> <p>Self-host an email server and only make it available over a mesh network like nebula or tailscale. I have no desire to make it internet routable or internet usable but more of a fun &quot;offline&quot; email for friends, family, fellow nerds etc. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/isThisRight--"> /u/isThisRight-- </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftq8ao/not_so_wild_sefl_hosted_email/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftq8ao/not_so_wild_sefl_hosted_email/">[comments]</a></span>

## De-googling, can I keep Google Workspace SSO on a custom domain for free?
 - [https://www.reddit.com/r/selfhosted/comments/1ftq538/degoogling_can_i_keep_google_workspace_sso_on_a](https://www.reddit.com/r/selfhosted/comments/1ftq538/degoogling_can_i_keep_google_workspace_sso_on_a)
 - RSS feed: $source
 - date published: 2024-10-01T14:57:43+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been paying for Google Workspace long enough that the price has tripled (still not much, but still). Occasionally I used it for outbound SMTP, but otherwise it&#39;s just for Google SSO. </p> <p>I know this might not be the best place to ask but I can&#39;t quite figure it out - is this something I can keep/get without paying? I mostly use it for SSO for eg. tailscale and to login to Google Sheets someone else provided.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/williambobbins"> /u/williambobbins </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftq538/degoogling_can_i_keep_google_workspace_sso_on_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftq538/degoogling_can_i_keep_google_workspace_sso_on_a/">[comments]</a></span>

## HP T640 or Dell Wyse 5070 for Home Server?
 - [https://www.reddit.com/r/selfhosted/comments/1ftplbw/hp_t640_or_dell_wyse_5070_for_home_server](https://www.reddit.com/r/selfhosted/comments/1ftplbw/hp_t640_or_dell_wyse_5070_for_home_server)
 - RSS feed: $source
 - date published: 2024-10-01T14:34:15+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I recently had a Raspberry Pi 4 running several services like Homebridge, Syncthing, AdGuard, etc., but when I tried installing Plex, the Pi gave out. Now I’m searching for a replacement, and I’ve found two thin clients that caught my eye: the HP T640 and the Dell Wyse 5070.</p> <p>I plan to run services like the ones I mentioned above and explore more like setting up a NAS, Paperless, and Jelifin. Both options are around €50 (though the HP is a bit more expensive but goes on sale often). The Dell doesn’t come with RAM or an SSD, while the HP has 8GB of RAM but no SSD. I have a spare 256GB NVMe SSD, so if I don’t upgrade the RAM, the HP would be cheaper if I can snag it on sale.</p> <p>I’ve read that the HP might be a bit more powerful, but my biggest concern is noise. I absolutely need something that won’t hum or whine. I’ve seen a few comments about the HP making some kind of high-pitched noise, but I’m not sure how common that 

## I built a API for deploying, destroying Kubernetes Clusters using KinD.
 - [https://www.reddit.com/r/selfhosted/comments/1ftpgsf/i_built_a_api_for_deploying_destroying_kubernetes](https://www.reddit.com/r/selfhosted/comments/1ftpgsf/i_built_a_api_for_deploying_destroying_kubernetes)
 - RSS feed: $source
 - date published: 2024-10-01T14:29:04+00:00

<!-- SC_OFF --><div class="md"><p><strong>KindlyAPI</strong> is a Flask-based API server designed to simplify the process of deploying, managing, and destroying Kubernetes clusters using KinD.</p> <p>I have a cabinet with 6 Intel NUC nodes that is responsible for hosting my Kubernetes Cluster, which I refer to as my production setup. And recently I won a bid on a HP Elitedesk, which is now my dev environment.</p> <p>I got curious and wanted a way to on-demand provision ephemeral kubernetes clusters with kind. Sure, its already so easy to provision them as you only need Docker and Kind to be installed. But I wanted a way to have a docker host (the HP node) being responsible for provisioning these nodes from API requests during CI builds.</p> <p>So I built a small python wrapper that mounts the docker socket to the flask container, and provisions/destroys clusters on API calls. It also scans the node for available ports so that the API server has a unique port. It then exposes an endpoi

## Fastest/lowest latency way to remote to desktop PC away from home? (for music production)
 - [https://www.reddit.com/r/selfhosted/comments/1ftpa3y/fastestlowest_latency_way_to_remote_to_desktop_pc](https://www.reddit.com/r/selfhosted/comments/1ftpa3y/fastestlowest_latency_way_to_remote_to_desktop_pc)
 - RSS feed: $source
 - date published: 2024-10-01T14:21:02+00:00

<!-- SC_OFF --><div class="md"><p>My laptop (T480s) doesn&#39;t seem to cut it for Ableton, so I want a way to use Ableton from my laptop by remoting to my desktop. What would be the fastest way do to this, with the lowest possible audio/video/input latency and atleast 192kbps MP3 equivalent audio? Considering using Sunshine/Moonlight with Tailscale and Headscale (installed on local network). </p> <p>Thanks for any suggestions. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OkCharity7285"> /u/OkCharity7285 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftpa3y/fastestlowest_latency_way_to_remote_to_desktop_pc/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftpa3y/fastestlowest_latency_way_to_remote_to_desktop_pc/">[comments]</a></span>

## i need windows VPS. Please NO Shill/Ad replies
 - [https://www.reddit.com/r/selfhosted/comments/1ftozt3/i_need_windows_vps_please_no_shillad_replies](https://www.reddit.com/r/selfhosted/comments/1ftozt3/i_need_windows_vps_please_no_shillad_replies)
 - RSS feed: $source
 - date published: 2024-10-01T14:08:22+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ftozt3/i_need_windows_vps_please_no_shillad_replies/"> <img src="https://b.thumbs.redditmedia.com/fY7YURviZLfKhTDXbyzPqgfs5a7Q-5U4bP7ZWoc0Crc.jpg" alt="i need windows VPS. Please NO Shill/Ad replies" title="i need windows VPS. Please NO Shill/Ad replies" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>hey i am looking for a windows VPS</p> <p>all reddit results i find via google are full asf with ads/shills.... i tried now already 5 fucking hosters and they suck</p> <p><a href="https://preview.redd.it/vjfxpdxbj5sd1.png?width=506&amp;format=png&amp;auto=webp&amp;s=4d3b10350229529359f8c23a1969d89896b9f341">https://preview.redd.it/vjfxpdxbj5sd1.png?width=506&amp;format=png&amp;auto=webp&amp;s=4d3b10350229529359f8c23a1969d89896b9f341</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pizzavegano"> /u/pizzavegano </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/c

## Fasten Health - Oct 2024 - Techstars, OneMedical, Quest Diagnostics and a deep dive into Information Blocking rules!
 - [https://www.reddit.com/r/selfhosted/comments/1ftngie/fasten_health_oct_2024_techstars_onemedical_quest](https://www.reddit.com/r/selfhosted/comments/1ftngie/fasten_health_oct_2024_techstars_onemedical_quest)
 - RSS feed: $source
 - date published: 2024-10-01T12:59:06+00:00

<!-- SC_OFF --><div class="md"><p>Hey Reddit!</p> <p>It’s been a couple of months since my last update, so let me reintroduce myself.</p> <p>My name is Jason Kulatunga, founder of <a href="https://www.fastenhealth.com">Fasten Health</a>, an <a href="https://github.com/fastenhealth/fasten-onprem/">offline/self-hosted personal health record (PHR)</a> app that allows individuals and their families to automatically import medical records from over 35,000 health systems across the US.</p> <p>A lot has changed over the past couple of months, and I’m excited to share some of our biggest updates:</p> <h2>Support for OneMedical</h2> <ul> <li>One of our top requested integrations, <a href="https://www.onemedical.com/">One Medical</a> (now part of Amazon), is live!</li> <li>Available on both our <a href="https://apps.microsoft.com/detail/Fasten%20Health/9PL8CZV1NRFP?launch=true&amp;mode=full">Windows</a> and <a href="https://apps.apple.com/us/app/fasten-health/id6471036301">macOS</a> apps, as we

## Shopware CE Mailserver (in or on Proxmox)
 - [https://www.reddit.com/r/selfhosted/comments/1ftng4y/shopware_ce_mailserver_in_or_on_proxmox](https://www.reddit.com/r/selfhosted/comments/1ftng4y/shopware_ce_mailserver_in_or_on_proxmox)
 - RSS feed: $source
 - date published: 2024-10-01T12:58:31+00:00

<!-- SC_OFF --><div class="md"><p>Hi Guys,</p> <p>I need your help again because the search Tool give out too much information and I don&#39;t know what&#39;s fits my needs the best.</p> <p>I need a mailserver for my wifes little Onlineshop (domain bought at godaddy and MS 365 available), here the edge data:</p> <p>OS: Ubuntu Mate 24.04 running on Proxmox node </p> <p>VPN: Proxmox Wireguard Lx (not configured yet, only needed if I have to provide ports for in-/outgoing mails)</p> <p>Apps installed: - Cloudpanel (with Shopware 6 CE and Nextcloud as websites) -&gt; Shop is already running and access is possible - Cloudflared (form. Argo Tunnel) - Docker + Portainer - Tailscale (for SSH entry)</p> <p>Installed also Webmin, but Sendmail setup is overwhelming me at the moment, so I am looking for an easier solution.</p> <p>I found different solutions: - Sendmail config via CLI or via GUI (Webmin) - Proxmox ISO for Mail Gateway as a standalone node - Proxmox Lx Container (but I am too stupi

## Some type of simple project management for home use?
 - [https://www.reddit.com/r/selfhosted/comments/1ftn5ca/some_type_of_simple_project_management_for_home](https://www.reddit.com/r/selfhosted/comments/1ftn5ca/some_type_of_simple_project_management_for_home)
 - RSS feed: $source
 - date published: 2024-10-01T12:43:40+00:00

<!-- SC_OFF --><div class="md"><p>Kind of a specific ask and maybe niche, but are there any type of project management apps more geared towards homeowners? Or does anyone have any advice on what they use? I have trouble keeping track of multiple different projects in our house and who I&#39;ve already called for what, or what I&#39;ve already done. I just want something where I can pull up (kitchen floor) and see what I&#39;ve already done and called, plus what I bought and where I put it. Stupid stuff I used to be able to handle but with kids, who knows how long until I get back to it. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tge101"> /u/tge101 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftn5ca/some_type_of_simple_project_management_for_home/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftn5ca/some_type_of_simple_project_management_for_home/">[comments]</a></span>

## Host OwnTracks on a Raspberry Pi?
 - [https://www.reddit.com/r/selfhosted/comments/1ftmph3/host_owntracks_on_a_raspberry_pi](https://www.reddit.com/r/selfhosted/comments/1ftmph3/host_owntracks_on_a_raspberry_pi)
 - RSS feed: $source
 - date published: 2024-10-01T12:20:50+00:00

<!-- SC_OFF --><div class="md"><p>Hello all,</p> <p>I want to host OwnTracks on a Raspberry Pi 3b+ to share the location of my Pixel running GrapheneOS with others. The Pi is already running Pi-hole Unbound, and Pi VPN.</p> <p>Would it be possible to also run OwnTracks on this Pi? If so, do you have any tips for the setup?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Komplexkonjugiert"> /u/Komplexkonjugiert </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftmph3/host_owntracks_on_a_raspberry_pi/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftmph3/host_owntracks_on_a_raspberry_pi/">[comments]</a></span>

## Self hosted email server recommendations?
 - [https://www.reddit.com/r/selfhosted/comments/1ftmneb/self_hosted_email_server_recommendations](https://www.reddit.com/r/selfhosted/comments/1ftmneb/self_hosted_email_server_recommendations)
 - RSS feed: $source
 - date published: 2024-10-01T12:17:43+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys, I am looking for a self hosted email server, I am building an application that will send out roughly 10k emails per day, I have looked into many email providers and they are all way too expensive ($400+ per month) even if I find something cheap enough it won&#39;t scale well because the emails are sent to free users too (some with attachments which makes it insanely expensive)</p> <p>I have some reservations about self hosting this, I need a way to handle spam filters so my emails don&#39;t end up in spam, my understanding is that most email providers will handle that, I also need it to be performant, the emails are all sent out at once (similar to a newsletter) I am ok if it takes an hour or so to complete but not more than that, keeping in mind that 10k is what it&#39;s at now but it could easily reach 25k or more in the next couple of months so I will need something scalable</p> <p>Regarding spam, I don&#39;t need the service to handle eve

## Self host Ollama
 - [https://www.reddit.com/r/selfhosted/comments/1ftmjng/self_host_ollama](https://www.reddit.com/r/selfhosted/comments/1ftmjng/self_host_ollama)
 - RSS feed: $source
 - date published: 2024-10-01T12:12:00+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys! I have an 8GB RAM Macbook Air M2 chip. I intend to self host an LLM for use as a personal AI assistant. I already have a UI in mind for it and am actively building it. But the bottleneck is the AI model. I downloaded Ollama and installed some of the smaller models. Turns out 8GB RAM is barely enough. Can you recommend me something with more RAM that can run an LLM since I can&#39;t upgrade the RAM on my Mac? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Partnergoku"> /u/Partnergoku </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftmjng/self_host_ollama/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftmjng/self_host_ollama/">[comments]</a></span>

## Radicale Calendar with git hook
 - [https://www.reddit.com/r/selfhosted/comments/1ftlzkv/radicale_calendar_with_git_hook](https://www.reddit.com/r/selfhosted/comments/1ftlzkv/radicale_calendar_with_git_hook)
 - RSS feed: $source
 - date published: 2024-10-01T11:41:23+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m testing Radicale since I&#39;m using an entire Nextcloud AIO installation just for the calendar. </p> <p>I could not find an explanation how to use the git hook in the wiki. (<a href="https://github.com/tomsquest/docker-radicale">dockIer</a>) Is someone using it?</p> <pre><code>[ERROR] An exception occurred during PUT request on &#39;/admin/70113e15-0ee5-0c25-fc6c-41f95b32c3bf/c3aac03ba2e45f341bc599f48c0470c88a8f9883.ics&#39;: Command &#39;([ -d .git ] || git init) &amp;&amp; git add -A &amp;&amp; (git diff --cached --quiet || git commit -m &quot;Changes by \&quot;Anonymous\&quot;&quot;)&#39; returned non-zero exit status 128.[ERROR] An exception occurred during PUT request on &#39;/admin/70113e15-0ee5-0c25-fc6c-41f95b32c3bf/c3aac03ba2e45f341bc599f48c0470c88a8f9883.ics&#39;: Command &#39;([ -d .git ] || git init) &amp;&amp; git add -A &amp;&amp; (git diff --cached --quiet || git commit -m &quot;Changes by \&quot;Anonymous\&quot;&quot;)&#39; re

## Simplest way to host a wiki with multi-user
 - [https://www.reddit.com/r/selfhosted/comments/1ftlu1d/simplest_way_to_host_a_wiki_with_multiuser](https://www.reddit.com/r/selfhosted/comments/1ftlu1d/simplest_way_to_host_a_wiki_with_multiuser)
 - RSS feed: $source
 - date published: 2024-10-01T11:32:20+00:00

<!-- SC_OFF --><div class="md"><p>I want to make a college project and create a wiki-like webserver for multiple colaborators. Does anyone knows what is the simplest alternative for making a self-hosted wiki that displays like the following:</p> <p><a href="http://npl.wiki/view/welcome-visitors/view/growing-regions#:%7E:text=Welcome%20to%20this%20Federated%20Wiki%20site.%20From%20this%20page%20you">NPL - New Pattern Language</a></p> <p><a href="https://notes.andymatuschak.org/About_these_notes">Andy Notes</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/vitruviodesertor"> /u/vitruviodesertor </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftlu1d/simplest_way_to_host_a_wiki_with_multiuser/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftlu1d/simplest_way_to_host_a_wiki_with_multiuser/">[comments]</a></span>

## Cloudflare, Traefik 2, Letsancrypt and issues accessing second subdomain
 - [https://www.reddit.com/r/selfhosted/comments/1ftljeg/cloudflare_traefik_2_letsancrypt_and_issues](https://www.reddit.com/r/selfhosted/comments/1ftljeg/cloudflare_traefik_2_letsancrypt_and_issues)
 - RSS feed: $source
 - date published: 2024-10-01T11:14:42+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>For about 3 weeks now (when I came back from vacation) I have had the problem that I can no longer access my internally hosted services. Ok, at least not from my Windows 11 PC or Macbook. Interestingly, it works on the iPhone.</p> <p>Internal = <a href="http://service.private.domain.de">service.private.domain.de</a></p> <p>External = <a href="http://service.domain.de">service.domain.de</a></p> <p>The setup is unchanged and has been running this way for a year without any problems.</p> <p>Error message ERR_QUIC_PROTOCOL_ERROR</p> <p>I have not found a solution on the Internet. Many approaches, but nothing has led to success so far.</p> <p>I keep reading that you have to subscribe to Cloudflare&#39;s “Advanced Certificate Manager”?</p> <p>My setup (please don&#39;t stone me, but I&#39;m not a professional and have familiarized myself with it on my own):</p> <p>docker-compose.yaml from traefik 2 and socket-proxy</p> <pre><code>vers

## Global and local env variables for docker compose?
 - [https://www.reddit.com/r/selfhosted/comments/1ftlesr/global_and_local_env_variables_for_docker_compose](https://www.reddit.com/r/selfhosted/comments/1ftlesr/global_and_local_env_variables_for_docker_compose)
 - RSS feed: $source
 - date published: 2024-10-01T11:06:47+00:00

<!-- SC_OFF --><div class="md"><p>What are the &#39;best practices&#39; for setting up docker composes for a selfhosted stack. More specifically I am wondering how others set environment variables? My current setup is the following:</p> <pre><code>.env /docker_app1/ ---- .env ---- docker-compose.yml /docker_app2/ ---- .env ---- docker-compose.yml ... </code></pre> <p>The idea is that the .env file that exist in the root folder contains general settings, ports and paths. Unfortunately docker compose only takes environment variables from .env in the folder in the folder the docker compose command is run from, as far as I understand. (Initially I thought you could specify .env files in the docker-compose.yml as </p> <pre><code>enf_file: - .env - ./../.env </code></pre> <p>but this only feeds the variables into the actual docker container.</p> <p>So my current setup is to have a global env file, which I then merge with the app_specific env files, using a python script. However, this just 

## How much RAM do you have? And how much are you currently using?
 - [https://www.reddit.com/r/selfhosted/comments/1ftkh9b/how_much_ram_do_you_have_and_how_much_are_you](https://www.reddit.com/r/selfhosted/comments/1ftkh9b/how_much_ram_do_you_have_and_how_much_are_you)
 - RSS feed: $source
 - date published: 2024-10-01T10:05:12+00:00

<!-- SC_OFF --><div class="md"><ul> <li>Ram: 16GB</li> <li>Usage: ~7GB</li> <li>Swap: 8GB</li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Zestyclose_Car1088"> /u/Zestyclose_Car1088 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftkh9b/how_much_ram_do_you_have_and_how_much_are_you/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftkh9b/how_much_ram_do_you_have_and_how_much_are_you/">[comments]</a></span>

## CapCut removed free subtitles in videos: which way to self host a similar service?
 - [https://www.reddit.com/r/selfhosted/comments/1ftk7og/capcut_removed_free_subtitles_in_videos_which_way](https://www.reddit.com/r/selfhosted/comments/1ftk7og/capcut_removed_free_subtitles_in_videos_which_way)
 - RSS feed: $source
 - date published: 2024-10-01T09:46:04+00:00

<!-- SC_OFF --><div class="md"><p>I tried <a href="http://Veed.io">Veed.io</a> but I don&#39;t want to pay, I prefer to put the W and hardware. </p> <p>Whisper allows just to create subtitles, it doesn&#39;t put them in the video. </p> <p>I&#39;d also like multilanguage compatibility</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/F041"> /u/F041 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftk7og/capcut_removed_free_subtitles_in_videos_which_way/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftk7og/capcut_removed_free_subtitles_in_videos_which_way/">[comments]</a></span>

## Cloudflare mTLS relay via Nginx
 - [https://www.reddit.com/r/selfhosted/comments/1ftk1oy/cloudflare_mtls_relay_via_nginx](https://www.reddit.com/r/selfhosted/comments/1ftk1oy/cloudflare_mtls_relay_via_nginx)
 - RSS feed: $source
 - date published: 2024-10-01T09:34:00+00:00

<!-- SC_OFF --><div class="md"><p>I want to have mTLS and Cloudflare WAF.</p> <p>I already configured Nginx to get mTLS. However because cloudflare does not have the client certificate I get an error when proxying the traffic.</p> <p>Is there a way, to make Cloudflare just ask for a client certificate then forward that client certificate ?</p> <p>PS: I know there is a client certficate in Cloudflare dashboard. But it is between the client and Cloudflare server. I am looking for a forward of client certificate so that mTLS is configured on Nginx level without losing WAF.</p> <p>PS: THis is to protect my selfhosted trilium btw</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/D4kzy"> /u/D4kzy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftk1oy/cloudflare_mtls_relay_via_nginx/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftk1oy/cloudflare_mtls_relay_via_nginx/">[comments]</a></span>

## Looking for an easy self-hosting storage option
 - [https://www.reddit.com/r/selfhosted/comments/1ftjtor/looking_for_an_easy_selfhosting_storage_option](https://www.reddit.com/r/selfhosted/comments/1ftjtor/looking_for_an_easy_selfhosting_storage_option)
 - RSS feed: $source
 - date published: 2024-10-01T09:17:23+00:00

<!-- SC_OFF --><div class="md"><p>Title.</p> <p>I don&#39;t have access to a server and am doing stuff from my own PC, all I&#39;m looking for is a way to transfer larger files from one person to another, My girlfriend is wanting to do some youtube editing for me and I&#39;m trying to find out how to give her the files but I can&#39;t without paying for something like google drive or whatever else.</p> <p>is there a free self hosted alternative thats relatively easy to install and they can access out of my network?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Altruistic-Fly1779"> /u/Altruistic-Fly1779 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftjtor/looking_for_an_easy_selfhosting_storage_option/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftjtor/looking_for_an_easy_selfhosting_storage_option/">[comments]</a></span>

## Video Jukebox
 - [https://www.reddit.com/r/selfhosted/comments/1ftjl0j/video_jukebox](https://www.reddit.com/r/selfhosted/comments/1ftjl0j/video_jukebox)
 - RSS feed: $source
 - date published: 2024-10-01T08:59:34+00:00

<!-- SC_OFF --><div class="md"><p>I’m looking to set up some kind of touchscreen video jukebox for my son’s bedroom. He’s autistic and has a few specific music videos that he enjoys watching and listening to, so I’d like something to host on my server where I can just download videos from YouTube and add them to his screen for him to put on whenever he wants. </p> <p>He’s familiar with navigating YouTube so if there’s something that closely resembles their front end but only shows the content that I add to it, that would be perfect. </p> <p>Can anyone recommend something please?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sizeofanoceansize"> /u/sizeofanoceansize </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftjl0j/video_jukebox/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftjl0j/video_jukebox/">[comments]</a></span>

## Syncthing Noob question about the encryption
 - [https://www.reddit.com/r/selfhosted/comments/1ftj0dm/syncthing_noob_question_about_the_encryption](https://www.reddit.com/r/selfhosted/comments/1ftj0dm/syncthing_noob_question_about_the_encryption)
 - RSS feed: $source
 - date published: 2024-10-01T08:15:28+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone </p> <p>In a couple months I&#39;ll be having my overseas move. I want to backup my NAS in full before the move, in case it gets damaged.</p> <p>I&#39;m looking into renting a VPS and using Syncthing to backup up my data. I did test it out a bit and I saw I can encrypt the data on the target.</p> <p>It the case of my NAS or my disks breaking, how would I get thet data back ? Would the password or the encryption key be enough ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JohnBeePowel"> /u/JohnBeePowel </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftj0dm/syncthing_noob_question_about_the_encryption/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftj0dm/syncthing_noob_question_about_the_encryption/">[comments]</a></span>

## Bulk SMS with Dynamic URLs failing
 - [https://www.reddit.com/r/selfhosted/comments/1ftikbc/bulk_sms_with_dynamic_urls_failing](https://www.reddit.com/r/selfhosted/comments/1ftikbc/bulk_sms_with_dynamic_urls_failing)
 - RSS feed: $source
 - date published: 2024-10-01T07:41:43+00:00

<!-- SC_OFF --><div class="md"><p>We&#39;re encountering problems with our bulk SMS campaigns due to recent changes i found <a href="https://www.trai.gov.in/sites/default/files/PR_No.67of2024.pdf">here</a> in the TRAI guidelines, which now require specific headers in dynamic URLs for compliance.</p> <p>I’ve explored services like Rebrandly, TinyURL, and Ow. ly, but none of them seem to support adding custom headers to short links, which is critical for avoiding our messages being flagged as spam.</p> <p>Does anyone know of a service or workaround that allows the creation of short URLs with custom headers to meet the TRAI regulations? Any suggestions would be greatly appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hopeless_sam"> /u/hopeless_sam </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftikbc/bulk_sms_with_dynamic_urls_failing/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/co

## I don't understand how people use a single VPS for production?
 - [https://www.reddit.com/r/selfhosted/comments/1fti75b/i_dont_understand_how_people_use_a_single_vps_for](https://www.reddit.com/r/selfhosted/comments/1fti75b/i_dont_understand_how_people_use_a_single_vps_for)
 - RSS feed: $source
 - date published: 2024-10-01T07:13:44+00:00

<!-- SC_OFF --><div class="md"><p>Dockerized my monolith web app. And was looking into self hosting, but...it seems that its not possible to have a simple production server setup. Let me explain.</p> <p>So seems that the barebones setup is cheap $5 VPS with docker container. Do people really go into production with that? But there are so many things missing from a robust production grade setup imo.</p> <ul> <li>DB Hosting, do you have a Postgres container on the same VPS? Setting up database backups? High availability?</li> <li>What about Ddos protection? Rate limiting?</li> <li>Auto scaling? Reverse proxy with multiple VPS based on CPU load.</li> <li>Logging, Alerts and Monitoring?</li> <li>Media storage? Object storage.</li> </ul> <p>I was also looking at PaaS self host options like: Dokku, Dokploy, Coolify, Caprover, etc.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/GloopBloopan"> /u/GloopBloopan </a> <br/> <span><a href="https://www.reddit

## Local-first, Rust-Based, Cross-Platform Personalized AI (think Rewind AI & Microsoft Recall Alternative)
 - [https://www.reddit.com/r/selfhosted/comments/1fti3s7/localfirst_rustbased_crossplatform_personalized](https://www.reddit.com/r/selfhosted/comments/1fti3s7/localfirst_rustbased_crossplatform_personalized)
 - RSS feed: $source
 - date published: 2024-10-01T07:06:49+00:00

<!-- SC_OFF --><div class="md"><p>Link: <a href="https://github.com/mediar-ai/screenpipe">https://github.com/mediar-ai/screenpipe</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/chris-tn"> /u/chris-tn </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fti3s7/localfirst_rustbased_crossplatform_personalized/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fti3s7/localfirst_rustbased_crossplatform_personalized/">[comments]</a></span>

## Stream TV card on local network
 - [https://www.reddit.com/r/selfhosted/comments/1fthpen/stream_tv_card_on_local_network](https://www.reddit.com/r/selfhosted/comments/1fthpen/stream_tv_card_on_local_network)
 - RSS feed: $source
 - date published: 2024-10-01T06:37:47+00:00

<!-- SC_OFF --><div class="md"><p>I have usb tv card, I see its chip is well supported on Linux, I need additional software to pack it into container, either Docker or LXC, and run it inside Proxmox. It should expose TV card video device as network stream that I can watch on VLC on Android phone. How to do it, what streaming server to use, or even better, is there already preconfigured container that I can use?</p> <p>This is the tv card id:</p> <p><code> Bus 001 Device 006: ID 15f4:0131 HanfTek Astrometa DVB-T/T2/C FM &amp; DAB receiver [RTL2832P] </code></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AdhesivenessExact597"> /u/AdhesivenessExact597 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fthpen/stream_tv_card_on_local_network/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fthpen/stream_tv_card_on_local_network/">[comments]</a></span>

## Contract Management
 - [https://www.reddit.com/r/selfhosted/comments/1ftgspf/contract_management](https://www.reddit.com/r/selfhosted/comments/1ftgspf/contract_management)
 - RSS feed: $source
 - date published: 2024-10-01T05:35:20+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ftgspf/contract_management/"> <img src="https://b.thumbs.redditmedia.com/uug-EiGA_VHCRWQTdxQV908cOyUheldt8GcmQ8f2_iU.jpg" alt="Contract Management" title="Contract Management" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I am looking for a contract management system similar to volders. With remaining term and reminder to cancel. Does anyone here have any ideas on how I can implement this?</p> <p><a href="https://preview.redd.it/h5nh4x4f03sd1.png?width=795&amp;format=png&amp;auto=webp&amp;s=b7333eba3e581aff93b0772c7b1b36bc77d9a040">https://preview.redd.it/h5nh4x4f03sd1.png?width=795&amp;format=png&amp;auto=webp&amp;s=b7333eba3e581aff93b0772c7b1b36bc77d9a040</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/trissi87"> /u/trissi87 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftgspf/contract_management/">[link]</a></span> &#32; <span><a href="h

## Keep or Delete Idea (Immich Add on)
 - [https://www.reddit.com/r/selfhosted/comments/1ftgesr/keep_or_delete_idea_immich_add_on](https://www.reddit.com/r/selfhosted/comments/1ftgesr/keep_or_delete_idea_immich_add_on)
 - RSS feed: $source
 - date published: 2024-10-01T05:10:34+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ftgesr/keep_or_delete_idea_immich_add_on/"> <img src="https://b.thumbs.redditmedia.com/rFMWyW_-VeNoCf0TvTLaasYyj_CGaiVJCxtRS7GYfrU.jpg" alt="Keep or Delete Idea (Immich Add on)" title="Keep or Delete Idea (Immich Add on)" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>So I don&#39;t know if someone already did this idea in Immich so since I am learning React Native I thought of something to do while bored. I thought its cool so I wanted to share hoping you guys find it cool also. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hinzwifi"> /u/hinzwifi </a> <br/> <span><a href="https://www.reddit.com/gallery/1ftgesr">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftgesr/keep_or_delete_idea_immich_add_on/">[comments]</a></span> </td></tr></table>

## Whats the best todo list with constant notifications/reminders until I clear/mark off the reminder?
 - [https://www.reddit.com/r/selfhosted/comments/1ftgd6w/whats_the_best_todo_list_with_constant](https://www.reddit.com/r/selfhosted/comments/1ftgd6w/whats_the_best_todo_list_with_constant)
 - RSS feed: $source
 - date published: 2024-10-01T05:07:48+00:00

<!-- SC_OFF --><div class="md"><p>I was adding events on google calendar, but google doesn’t even have this feature of constantly reminded of a task/event until you clear/mark off that task is done. Does anyone know of a a todo list, calendar or notes app that can do this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/fumpleshitzkits"> /u/fumpleshitzkits </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftgd6w/whats_the_best_todo_list_with_constant/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftgd6w/whats_the_best_todo_list_with_constant/">[comments]</a></span>

## How to setup secure remote connection for my computer?
 - [https://www.reddit.com/r/selfhosted/comments/1ftg8ij/how_to_setup_secure_remote_connection_for_my](https://www.reddit.com/r/selfhosted/comments/1ftg8ij/how_to_setup_secure_remote_connection_for_my)
 - RSS feed: $source
 - date published: 2024-10-01T05:00:17+00:00

<!-- SC_OFF --><div class="md"><p>I was using port-forwarding for a while, which was very unsafe but I want to switch to a more secure remote method. </p> <p>I can&#39;t set up a VPN on my router as it doesn&#39;t support it and I don&#39;t want to use a raspberry pi</p> <p>The issue is I am using 2 OS, linux and windows, and I want to keep using RDP for windows and I want to be able to use SSH for my linux machine.</p> <p>Is there any good solution out there that I can setup. I have seen some ideas of using a VPS where I setup AWS but am unsure how to go about doing it.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Arkhaya"> /u/Arkhaya </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftg8ij/how_to_setup_secure_remote_connection_for_my/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftg8ij/how_to_setup_secure_remote_connection_for_my/">[comments]</a></span>

## Selfhosting and hamachi questions for a minecraft server
 - [https://www.reddit.com/r/selfhosted/comments/1ftfmh5/selfhosting_and_hamachi_questions_for_a_minecraft](https://www.reddit.com/r/selfhosted/comments/1ftfmh5/selfhosting_and_hamachi_questions_for_a_minecraft)
 - RSS feed: $source
 - date published: 2024-10-01T04:22:37+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m not that tech savvy, so pardon me for what it may be some dumb questions.</p> <p><strong>Hamachi questions</strong></p> <p>This server would be only for me and my friend, one i trust a lot and i know in real life so any problems coming from them is not a issue (like they seeing my IP with Hamachi)</p> <p>I saw some discussion about Hamachi being insecure for the host being really exposed when somebody connects to their system. But if i only share it with my friend and not publicly nothing wrong should come from it right? </p> <p><strong>Selhosting questions</strong></p> <p>(Same friend server)</p> <p>Thought Hamachi sounds easy, i really want to try to self host, is sounds like a fun way to learn, and i think i know how to do it (or at least where to look for a tutorial) but what i don&#39;t get/understand is the actual connotations of the risk being mentioned in the several posts.</p> <p>What i learned from reading from this community is that

## The best WHMCS open-source
 - [https://www.reddit.com/r/selfhosted/comments/1fte8lg/the_best_whmcs_opensource](https://www.reddit.com/r/selfhosted/comments/1fte8lg/the_best_whmcs_opensource)
 - RSS feed: $source
 - date published: 2024-10-01T03:05:46+00:00

<!-- SC_OFF --><div class="md"><p>I’m looking into</p> <p>• <strong>Kill Bill</strong></p> <p>• <strong>Blesta</strong></p> <p>• <strong>FOSSBilling</strong></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/anonuser-al"> /u/anonuser-al </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fte8lg/the_best_whmcs_opensource/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fte8lg/the_best_whmcs_opensource/">[comments]</a></span>

## Email Domain Hosting
 - [https://www.reddit.com/r/selfhosted/comments/1ftdwft/email_domain_hosting](https://www.reddit.com/r/selfhosted/comments/1ftdwft/email_domain_hosting)
 - RSS feed: $source
 - date published: 2024-10-01T02:47:46+00:00

<!-- SC_OFF --><div class="md"><p>I am about to cut the cord and move off of cable. I am looking for a domain host on the cheap that will allow for a different MX host. I am thinking of SmartMail for the email.</p> <p>I only need a max of 5 addresses for family, and I don&#39;t really care about an actual website that much, but will probably just do a quick splash page. Just a domain name and the emails. </p> <p>Thanks for the input! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MaelstromFL"> /u/MaelstromFL </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftdwft/email_domain_hosting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftdwft/email_domain_hosting/">[comments]</a></span>

## This may be a dumb question to ask here
 - [https://www.reddit.com/r/selfhosted/comments/1ftdtcm/this_may_be_a_dumb_question_to_ask_here](https://www.reddit.com/r/selfhosted/comments/1ftdtcm/this_may_be_a_dumb_question_to_ask_here)
 - RSS feed: $source
 - date published: 2024-10-01T02:43:06+00:00

<!-- SC_OFF --><div class="md"><p>This isn&#39;t exactly pertaining to anything self-hosted but I&#39;m not quite sure what the issue is and since the majority of self hosters eventually do what I&#39;m doing, I thought that maybe someone could point me in the right direction as to where to go to properly troubleshoot.</p> <p>I just got a brand new hard drive today. When I try and format it, I get an error in Ubuntu that says Error Creating Partition Message recipient disconnected from message bus without replying (g-dbus-error-quark, 4). Now, this isn&#39;t the first formatting. I formatted it successfully to test and make sure it&#39;s working about 3 hours ago (ish). Was working great so then I wanted to clone my old drive. When I started cloning my other drive, all my drives unmounted themselves. Because it was cloning when doing so, I deleted the partial cloned drive and was going to just format and manually copy the files but I keep getting this message now and I can&#39;t forma

## Open Source CRM with document management?
 - [https://www.reddit.com/r/selfhosted/comments/1ftcce5/open_source_crm_with_document_management](https://www.reddit.com/r/selfhosted/comments/1ftcce5/open_source_crm_with_document_management)
 - RSS feed: $source
 - date published: 2024-10-01T01:28:15+00:00

<!-- SC_OFF --><div class="md"><p>There are so many open source CRM&#39;s out there... </p> <p>Does anyone happen to know of an open source self-hosted CRM that can:</p> <ul> <li><p>Track family relationships between contacts</p></li> <li><p>Has integrated document management</p></li> <li><p>(optional) Integrated task and time tracking?</p></li> <li><p>(optional) Invoicing</p></li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rulysteve"> /u/rulysteve </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftcce5/open_source_crm_with_document_management/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftcce5/open_source_crm_with_document_management/">[comments]</a></span>

## how can i use reverse proxy to turn ws:// to wss://
 - [https://www.reddit.com/r/selfhosted/comments/1ftc78a/how_can_i_use_reverse_proxy_to_turn_ws_to_wss](https://www.reddit.com/r/selfhosted/comments/1ftc78a/how_can_i_use_reverse_proxy_to_turn_ws_to_wss)
 - RSS feed: $source
 - date published: 2024-10-01T01:20:51+00:00

<!-- SC_OFF --><div class="md"><p>hello, i have recently started a project that requires the use of web sockets, now this was going great untill i realized that i needed to use a secure WebSocket (wss://) link when my WebSocket server was not using wss://, it was using plain ol ws://, i have always had horrible luck when it comes to stuff like nginx and googling did not help. is there any way i could take a local port that is running a ws:// server and turn that into a wss:// server running on a different port.</p> <p>P.S. sorry for the horrible wording, its late for me and i am running on caffeine, willpower, and days of no sleep 👍</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cryptoEnegma"> /u/cryptoEnegma </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftc78a/how_can_i_use_reverse_proxy_to_turn_ws_to_wss/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftc78a/how_can_i_use_reverse

## Best open-source organization-oriented email server?
 - [https://www.reddit.com/r/selfhosted/comments/1ftbz0g/best_opensource_organizationoriented_email_server](https://www.reddit.com/r/selfhosted/comments/1ftbz0g/best_opensource_organizationoriented_email_server)
 - RSS feed: $source
 - date published: 2024-10-01T01:09:32+00:00

<!-- SC_OFF --><div class="md"><p>Hi. I run a school <a href="https://tsaweb.org">TSA</a> team and we currently use Zoho mail. The issue is we are at capacity with users on the free tier and we want to add more users. We have always thought it would be best to do it self-hosted, but email servers can be a pain to set up. We have the following requirements:</p> <ul> <li>Many users</li> <li>Admin reports including inbound and outbound traffic (not necessarily email contents, though that would be preferred)</li> <li>Multiple email aliases per user</li> <li>Modern webmail interface</li> <li>Spam protection</li> <li>Available to use with external apps</li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Champe21"> /u/Champe21 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftbz0g/best_opensource_organizationoriented_email_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftbz0g/best

## Looking for Web Content Filter from 2005-2006 with unique interface
 - [https://www.reddit.com/r/selfhosted/comments/1ftat1m/looking_for_web_content_filter_from_20052006_with](https://www.reddit.com/r/selfhosted/comments/1ftat1m/looking_for_web_content_filter_from_20052006_with)
 - RSS feed: $source
 - date published: 2024-10-01T00:11:57+00:00

<!-- SC_OFF --><div class="md"><p>This may be a long shot, but I wanted to ask in case someone can help me find this. Back in 2005-2006, I was the IT Manager for a public library in the Midwest. While there I needed to replace the web content filter the library used for the children&#39;s department and a few other public computers. I may have also needed to replace the firewall, but I am not 100% certain on that. What I do remember is running a virtual machine for the web filtering and it had an interface that kind of looked like a server rack with different systems. I kind of feel like it was also our firewall, but I am not 100% sure on that part. I am thinking it must have been open source, or possibly freeware, because I had limited funds. I remember it being really easy to configure and it did a great job on the content filtering. I am trying to find it to potentially use at home for some testing stuff and playing around. Any help is greatly appreciated!</p> <ul> <li>LinuxAndCoff

## Is there an app directory where I can get docker files etc?
 - [https://www.reddit.com/r/selfhosted/comments/1ftaqxe/is_there_an_app_directory_where_i_can_get_docker](https://www.reddit.com/r/selfhosted/comments/1ftaqxe/is_there_an_app_directory_where_i_can_get_docker)
 - RSS feed: $source
 - date published: 2024-10-01T00:09:14+00:00

<!-- SC_OFF --><div class="md"><p>I like the app stores in Unraid/CasaOS etc, they are essentially just web stores with docker compose files and some extra config.</p> <p>But it makes it easy to browse and discover new apps you didn&#39;t know about. </p> <p>is there something like this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ECrispy"> /u/ECrispy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftaqxe/is_there_an_app_directory_where_i_can_get_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ftaqxe/is_there_an_app_directory_where_i_can_get_docker/">[comments]</a></span>

