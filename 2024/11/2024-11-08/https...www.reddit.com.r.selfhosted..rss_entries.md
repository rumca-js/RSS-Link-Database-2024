# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Switching from Kopia to … Borg?
 - [https://www.reddit.com/r/selfhosted/comments/1gmw6kj/switching_from_kopia_to_borg](https://www.reddit.com/r/selfhosted/comments/1gmw6kj/switching_from_kopia_to_borg)
 - RSS feed: $source
 - date published: 2024-11-08T23:23:09+00:00

<!-- SC_OFF --><div class="md"><p>Setup Kopia on my NAS. Went to read from the replicated backup and couldn’t get in. Busy reading bug reports, solutions, etc. get about 20 minutes in and say to myself: “If it’s this fragile, it’s not a good backup”. Main repository is okay, it’s the offsite that’s borked. </p> <p>So now I’m looking at Borg and wondering the same thing. Dedupe, compression, all of that’s great till I can’t get to my files. How’s the stability and durability of Borg for those that use it? Any alternate suggestions? </p> <p>(Yes, I know this topic comes up often. I’m specifically looking for experiences from users on resiliency)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rob_allshouse"> /u/rob_allshouse </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmw6kj/switching_from_kopia_to_borg/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmw6kj/switching_from_kopia_to_

## Big samba transfer saturate local network
 - [https://www.reddit.com/r/selfhosted/comments/1gmw4fi/big_samba_transfer_saturate_local_network](https://www.reddit.com/r/selfhosted/comments/1gmw4fi/big_samba_transfer_saturate_local_network)
 - RSS feed: $source
 - date published: 2024-11-08T23:20:26+00:00

<!-- SC_OFF --><div class="md"><p>I have a computer that i use to self host a samba server using docker. </p> <p>I havent used it that much to make huge file transfers but yesterday I did just that (a transfer of around 100GB) and i noticed that the whole home internet couldn&#39;t load a single page until I paused the transfer, even though the speed was 10MB/s at most. </p> <p>How is this possible? My Docker configuration of the Samba server looks like this btw.</p> <p><code>yml services: samba: image: ghcr.io/servercontainers/samba restart: unless-stopped network_mode: host container_name: samba environment: SAMBA_GLOBAL_CONFIG_socket_SPACE_options: &quot;TCP_NODELAY IPTOS_LOWDELAY&quot; SAMBA_GLOBAL_CONFIG_write_SPACE_cache_SPACE_size: 2097152 SAMBA_GLOBAL_CONFIG_min_SPACE_receivefile_SPACE_size: 16384 SAMBA_GLOBAL_CONFIG_getwd_SPACE_cache: &quot;yes&quot; SAMBA_GLOBAL_CONFIG_read_SPACE_raw: &quot;yes&quot; SAMBA_GLOBAL_CONFIG_write_SPACE_raw: &quot;yes&quot; SAMBA_GLOBAL_CONFIG_f

## Is Reddit going to remain the primary space for this community?
 - [https://www.reddit.com/r/selfhosted/comments/1gmv76n/is_reddit_going_to_remain_the_primary_space_for](https://www.reddit.com/r/selfhosted/comments/1gmv76n/is_reddit_going_to_remain_the_primary_space_for)
 - RSS feed: $source
 - date published: 2024-11-08T22:38:11+00:00

<!-- SC_OFF --><div class="md"><p>I personally hate that 3rd party reddit apps no longer exist. Yes you can patch old ones but they don&#39;t get updates anymore and yes Infinity exists but it&#39;s missing things from sync that I used to love.</p> <p>I would love to move away from reddit but it&#39;s hard when this is where the base of my favorite communities still exists.</p> <p>Lemmy has its own selfhosted community with a pretty large user count but I don&#39;t want to be checking both places all the time. </p> <p>I just want to discuss this as a community and see how others feel.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/shakinthetip"> /u/shakinthetip </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmv76n/is_reddit_going_to_remain_the_primary_space_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmv76n/is_reddit_going_to_remain_the_primary_space_for/">[comments]</a></s

## Help with Nextcloud deployment
 - [https://www.reddit.com/r/selfhosted/comments/1gmv5j7/help_with_nextcloud_deployment](https://www.reddit.com/r/selfhosted/comments/1gmv5j7/help_with_nextcloud_deployment)
 - RSS feed: $source
 - date published: 2024-11-08T22:36:08+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gmv5j7/help_with_nextcloud_deployment/"> <img src="https://preview.redd.it/93wbfyc19rzd1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=bc1617dee1709a4d872c75ae86eb99764dddf372" alt="Help with Nextcloud deployment" title="Help with Nextcloud deployment" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I have a docker host running Nextcloud and nginx proxy manager. I have dns configured in cloudflare. I can hit the sign on page in a web browser but the native app gives me a 301 error. Any help? Another thing too that may be a symptom. Is when signing in through the browser I need to refresh after I login or else it just spins like it’s logging in. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ccnaman"> /u/ccnaman </a> <br/> <span><a href="https://i.redd.it/93wbfyc19rzd1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmv5j7/

## Jotform Alternative
 - [https://www.reddit.com/r/selfhosted/comments/1gmuqax/jotform_alternative](https://www.reddit.com/r/selfhosted/comments/1gmuqax/jotform_alternative)
 - RSS feed: $source
 - date published: 2024-11-08T22:17:22+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a good jotform alternative, I would prefer something free and it does not have to be self hosted but it would be much better if it can be. Thank you ahead for any suggestions.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Squanchy2112"> /u/Squanchy2112 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmuqax/jotform_alternative/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmuqax/jotform_alternative/">[comments]</a></span>

## Managing updates for my whole situation has gotten too difficult--looking for advice dealing with docker-compose files in lxc containers (under Proxmox)
 - [https://www.reddit.com/r/selfhosted/comments/1gmta6x/managing_updates_for_my_whole_situation_has](https://www.reddit.com/r/selfhosted/comments/1gmta6x/managing_updates_for_my_whole_situation_has)
 - RSS feed: $source
 - date published: 2024-11-08T21:13:55+00:00

<!-- SC_OFF --><div class="md"><p>Hokay so thanks to all of you constantly posting cool things to play with, I have a Proxmox host, with 24 containers and 3 VMs.</p> <p>They&#39;re all running Debian, and about half of them have Docker Compose. Laid out something like this:</p> <p>prox.hostname (Proxmox Host)</p> <p>├── calibre.hostname (Debian LXC)</p> <p>│ ├── ~/calibre/</p> <p>│ │ └── docker-compose.yml</p> <p>│ └── ~/calibre-web/</p> <p>│ └── docker-compose.yml</p> <p>├── paperless.hostname (Debian LXC)</p> <p>│ └── ~/paperless/</p> <p>│ ├── docker-compose.yml</p> <p>│ └── docker-compose.env</p> <pre><code>└── immich.hostname (Debian VM) └── ~/immich-app └── docker-compose.yml </code></pre> <p>I just spent the morning updating everything, and it was a big pain with a bunch of repetition:</p> <p>ssh prox.hostname apt get update &amp;&amp; apt get dist-upgrade -y ssh calibre.hostname apt get update &amp;&amp; apt get dist-upgrade -y cd ~/calibre docker-compose down &amp;&amp; docke

## SSO and ACL authelia or authentik
 - [https://www.reddit.com/r/selfhosted/comments/1gmsqtr/sso_and_acl_authelia_or_authentik](https://www.reddit.com/r/selfhosted/comments/1gmsqtr/sso_and_acl_authelia_or_authentik)
 - RSS feed: $source
 - date published: 2024-11-08T20:50:49+00:00

<!-- SC_OFF --><div class="md"><p>Currently i am choosing which one to setup. Could not get authentik to work it throws some python module missing error. But noticed that it&#39;s HUGE compared to authelia. Wanted to try authelia but i have some questions.</p> <p>Can both of these have some kind of ACL? For example some user or some group can not access some service and others can. Currently i am using traefik whitelists to do this and i have 2 wireguard vpns for this to work. One admin one for limited clients. </p> <p>Second is i notice using authentik you can define middlewares for different users for traefik and then just assign it to service to have ACL, but i saw in authelia you have some container names inside configuration file which sadly must be static and can&#39;t be configured using docker labels. Is this correct or is there a way to somehow configure ACLs using authelia using docker labels? I just do not want to have to configure things in 2 places in compose files and i

## Swetrix v3.3.0 - selfhosted and cookieless Google Analytics / Plausible alternative
 - [https://www.reddit.com/r/selfhosted/comments/1gms49h/swetrix_v330_selfhosted_and_cookieless_google](https://www.reddit.com/r/selfhosted/comments/1gms49h/swetrix_v330_selfhosted_and_cookieless_google)
 - RSS feed: $source
 - date published: 2024-11-08T20:23:56+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gms49h/swetrix_v330_selfhosted_and_cookieless_google/"> <img src="https://external-preview.redd.it/cjFc_b6WOugHepTL6AVAoMNXgl1cMoIN1LjQ_doJILg.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=b349fa123fafcbc1aa1f95fd9a467483fce86fab" alt="Swetrix v3.3.0 - selfhosted and cookieless Google Analytics / Plausible alternative" title="Swetrix v3.3.0 - selfhosted and cookieless Google Analytics / Plausible alternative" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>A new version of Swetrix has just been released and this time the focus has been on bug fixes, stability improvements and some new features too!</p> <p>First of all, what is Swetrix? Swetrix is an open source, cookie-less alternative to Google Analytics and Plausible. It provides not only detailed traffic analysis, but also site speed monitoring, simple error tracking, funnels, session overview - all while respecting your users&#39

## BashNVR awesome surveillance (or any) camera stream recorder for home server (linux)
 - [https://www.reddit.com/r/selfhosted/comments/1gmrnjl/bashnvr_awesome_surveillance_or_any_camera_stream](https://www.reddit.com/r/selfhosted/comments/1gmrnjl/bashnvr_awesome_surveillance_or_any_camera_stream)
 - RSS feed: $source
 - date published: 2024-11-08T20:03:52+00:00

<!-- SC_OFF --><div class="md"><p>Hi, i had pain just to find an open and free software to record my surveillance camera streams, i found not working bloated NVR software like zoneminder or not working ones camera.ui, etc.<br/> Then i found <a href="https://github.com/filippofinke/BashNVR">BashNVR</a>.</p> <p>Yes, its a bash script so doesn&#39;t need any dependency except linux with bash :D<br/> Just download the package from git, config as written, and records any streams (even multiple cameras) to the set folder (to mkv files), if the camera is capable to stream on rtsp (most if not all do). Its just works, lightweight, simple.</p> <p>I don&#39;t know why it isn&#39;t more popular, but i find this the easiest way to record surveillance camera streams at home</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/disconnect0414"> /u/disconnect0414 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmrnjl/bashnvr_awesome_surveilla

## UPS Battery Failure/Problems Survey
 - [https://www.reddit.com/r/selfhosted/comments/1gmr9yj/ups_battery_failureproblems_survey](https://www.reddit.com/r/selfhosted/comments/1gmr9yj/ups_battery_failureproblems_survey)
 - RSS feed: $source
 - date published: 2024-11-08T19:47:37+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I&#39;m surveying a school project on UPS battery failure. If you have a few minutes, I would appreciate your input. You may have seen this survey posted several weeks ago, we took in your input and made the necessary adjustments. You can access the survey here:</p> <p><a href="https://docs.google.com/forms/d/1TyxR-J1DWCCMTytMMeU1nVuYMXxzm-dtpD4rrW0jDGQ/edit">https://docs.google.com/forms/d/1TyxR-J1DWCCMTytMMeU1nVuYMXxzm-dtpD4rrW0jDGQ/edit</a></p> <p>Thank you for your time!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/VizeKarma"> /u/VizeKarma </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmr9yj/ups_battery_failureproblems_survey/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmr9yj/ups_battery_failureproblems_survey/">[comments]</a></span>

## Beginner Self-Hosted Journey
 - [https://www.reddit.com/r/selfhosted/comments/1gmquvb/beginner_selfhosted_journey](https://www.reddit.com/r/selfhosted/comments/1gmquvb/beginner_selfhosted_journey)
 - RSS feed: $source
 - date published: 2024-11-08T19:29:23+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gmquvb/beginner_selfhosted_journey/"> <img src="https://b.thumbs.redditmedia.com/h3dLpl_S9szAk9s4hk9hi1ZDjQPTCFC4tpY3lrSnGiE.jpg" alt="Beginner Self-Hosted Journey" title="Beginner Self-Hosted Journey" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/f07zwbf6dqzd1.jpg?width=623&amp;format=pjpg&amp;auto=webp&amp;s=e6053f988d6f2546d96d24c5fdddc80b060c3fa8">https://preview.redd.it/f07zwbf6dqzd1.jpg?width=623&amp;format=pjpg&amp;auto=webp&amp;s=e6053f988d6f2546d96d24c5fdddc80b060c3fa8</a></p> <p>Hello everyone, i have managed to gather some insights recently (mainly figuring out authentik) and wanted some welcomed criticism. It is fairly simple and i am not qualified to speak about this stuff but have no one that can question my setup so here it is:</p> <p>There is one path left for old Laptops nearing their demise take. Praise Debian headless! With cloudflare tunnels i set up a qu

## zrok Office Hours -- Performance Management (Part 1)
 - [https://www.reddit.com/r/selfhosted/comments/1gmqkbr/zrok_office_hours_performance_management_part_1](https://www.reddit.com/r/selfhosted/comments/1gmqkbr/zrok_office_hours_performance_management_part_1)
 - RSS feed: $source
 - date published: 2024-11-08T19:16:34+00:00

<!-- SC_OFF --><div class="md"><p>Starting a new thread of zrok Office Hours videos might be useful to anyone who self-hosts their own zrok instance...</p> <p>Doing some hacking on the brand new &quot;canary&quot; framework in zrok. This new framework will be used to monitor performance and reliability in the production zrok envrionment, and will also offer nice end-to-end functional correctness tests for developers and devops teams that want to validate their zrok instance.</p> <p>It&#39;s my usual style, where I wait until I&#39;m completely beat on a Friday afternoon, and I just launch into hacking on something... hopefully it&#39;s entertaining in some way! I personally enjoy watching other developers doing real-world work, so, maybe you&#39;ll enjoy this!</p> <p><a href="https://www.youtube.com/watch?v=-SDOwnVE7LE">https://www.youtube.com/watch?v=-SDOwnVE7LE</a></p> <p>For anyone new... zrok is a network and filesystem sharing platform built on top of a next-generation zero-trus

## How to properly expose services?
 - [https://www.reddit.com/r/selfhosted/comments/1gmqjko/how_to_properly_expose_services](https://www.reddit.com/r/selfhosted/comments/1gmqjko/how_to_properly_expose_services)
 - RSS feed: $source
 - date published: 2024-11-08T19:15:37+00:00

<!-- SC_OFF --><div class="md"><p>Hello my tinfoil hat friends. I have a Homeserver where I host various services for myself (Nextcloud, Immich, etc.). Currently, I have everything only accessible in my wireguard VPN via dyndns. Now since I want to give access also to my family and don&#39;t want to have the hassle of connecting every device to my wireguard VPN (I also have a problem where I have to reconnect to it daily despite the keepalives and I just want it to work for them), I thought about properly exposing my services to the world.</p> <p>My current take would be to wrap everything in Authentik (together with a reverse proxy and letsencrypt). Is that enough security (when using proper passwords)? I don&#39;t really want to spend any extra money on a VPS for tunneling, or is that dumb?</p> <p>I&#39;m open for suggestions regarding the architecture. Thank you in advance :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/crazyklatsch"> /u/c

## Building a dashboard - what to choose?
 - [https://www.reddit.com/r/selfhosted/comments/1gmpv4e/building_a_dashboard_what_to_choose](https://www.reddit.com/r/selfhosted/comments/1gmpv4e/building_a_dashboard_what_to_choose)
 - RSS feed: $source
 - date published: 2024-11-08T18:46:50+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m planning to build a dashboard for work as a fun project to hopefully learn even more. I want to build a dashboard that shows metrics from Klaviyo and our webshop - like generated income from campaigns in Klaviyo and today&#39;s sales from the webshop. I want to host this on my own server, but I&#39;m in search of some advice/recommendations how to go about this? Have any of you made something similar? If so, how did you choose to do it?</p> <p>I&#39;m a novice at coding, but I think it would be a fun little project. I&#39;m not scared of trying things out and get in over my head. I might even not be able to pull it of but then I at least tried and hopefully learned something along the way.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mickey_Beast"> /u/Mickey_Beast </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmpv4e/building_a_dashboard_what_to_choose/">[link]</a></span> &#32

## Game Dev Asset management software?
 - [https://www.reddit.com/r/selfhosted/comments/1gmod55/game_dev_asset_management_software](https://www.reddit.com/r/selfhosted/comments/1gmod55/game_dev_asset_management_software)
 - RSS feed: $source
 - date published: 2024-11-08T17:43:35+00:00

<!-- SC_OFF --><div class="md"><p>Hello! I&#39;m looking for some kind of file management software that I can run on my debian server (preferably docker). </p> <p>It&#39;s hard to search for apps in this field. I&#39;ve looked around a little and found inventory management and pdf management apps but not any storage for game dev/bigger assets. Found Teedy, which could work for my case but before I go ahead and spend time trying to get that set up I&#39;m wondering if anyone knows if anything &quot;better&quot;?</p> <p>Main thing is for it to archive and manage all my local game dev assets I&#39;ve bought over the years. No need in team or git/scm functionality, this is just for me to be able to organize my ever-growing lib.</p> <p>All and any help is appreciated 🙏</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BACONGUDEN"> /u/BACONGUDEN </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmod55/game_dev_asset_management_soft

## Rate my Netflix replacement
 - [https://www.reddit.com/r/selfhosted/comments/1gmo1aa/rate_my_netflix_replacement](https://www.reddit.com/r/selfhosted/comments/1gmo1aa/rate_my_netflix_replacement)
 - RSS feed: $source
 - date published: 2024-11-08T17:30:11+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gmo1aa/rate_my_netflix_replacement/"> <img src="https://b.thumbs.redditmedia.com/x1IBziTC4pwgI1DlbbCh3VUNGJo6PbPk850WpbkWtbI.jpg" alt="Rate my Netflix replacement" title="Rate my Netflix replacement" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/u5i6fowlfpzd1.png?width=775&amp;format=png&amp;auto=webp&amp;s=00a9d3ea88dd2e5f9f02f99241f47d63ebf2377a">https://preview.redd.it/u5i6fowlfpzd1.png?width=775&amp;format=png&amp;auto=webp&amp;s=00a9d3ea88dd2e5f9f02f99241f47d63ebf2377a</a></p> <p>I have been tinkering around for over half a year now trying to create a viable alternative to paid streaming services and I think it&#39;s finally in a usable state</p> <ul> <li>Server is behind a CGNAT so I use cloudflare tunnels for applications and tailscale for ssh</li> <li>Rclone automatically syncs the 2tb library to E5 onedrive so I can just have a 500gb hard drive in there</li> <li>Rad

## GPG Key server
 - [https://www.reddit.com/r/selfhosted/comments/1gmni0e/gpg_key_server](https://www.reddit.com/r/selfhosted/comments/1gmni0e/gpg_key_server)
 - RSS feed: $source
 - date published: 2024-11-08T17:07:56+00:00

<!-- SC_OFF --><div class="md"><p>Hi Everyone,<br/> I would like to setup a GPG Key Server. Something like this:<br/> <a href="https://keyserver.ubuntu.com/">https://keyserver.ubuntu.com/</a></p> <p>But &quot;private&quot; for my friend. </p> <p>Is there any &quot;easy-to-setup&quot; app that I can deploy on my k3s cluster to do this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Neptune1987"> /u/Neptune1987 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmni0e/gpg_key_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmni0e/gpg_key_server/">[comments]</a></span>

## Hosting SMTP
 - [https://www.reddit.com/r/selfhosted/comments/1gmmzlg/hosting_smtp](https://www.reddit.com/r/selfhosted/comments/1gmmzlg/hosting_smtp)
 - RSS feed: $source
 - date published: 2024-11-08T16:46:45+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, I was wondering what some good options for hosting an SMTP server is. It&#39;s for really low usage, so if it wouldnt cost too much that would be great.</p> <p>Thanks in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Friendlywareee"> /u/Friendlywareee </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmmzlg/hosting_smtp/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmmzlg/hosting_smtp/">[comments]</a></span>

## any recipe managers that can auto translate recipes with whisper/openai?
 - [https://www.reddit.com/r/selfhosted/comments/1gmlqds/any_recipe_managers_that_can_auto_translate](https://www.reddit.com/r/selfhosted/comments/1gmlqds/any_recipe_managers_that_can_auto_translate)
 - RSS feed: $source
 - date published: 2024-11-08T15:54:11+00:00

<!-- SC_OFF --><div class="md"><p>i have searched but can&#39;t find anything</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dyonizius"> /u/Dyonizius </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmlqds/any_recipe_managers_that_can_auto_translate/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmlqds/any_recipe_managers_that_can_auto_translate/">[comments]</a></span>

## Pet tracker
 - [https://www.reddit.com/r/selfhosted/comments/1gmlnes/pet_tracker](https://www.reddit.com/r/selfhosted/comments/1gmlnes/pet_tracker)
 - RSS feed: $source
 - date published: 2024-11-08T15:50:38+00:00

<!-- SC_OFF --><div class="md"><p>Any good pet tracker which can be selfhosted for free and is easy to connect with other pet tracker devices (gps pet collar)?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/goliat4"> /u/goliat4 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmlnes/pet_tracker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmlnes/pet_tracker/">[comments]</a></span>

## A free, open source, locally hosted search engine for all your memes (new updates!)
 - [https://www.reddit.com/r/selfhosted/comments/1gml8cb/a_free_open_source_locally_hosted_search_engine](https://www.reddit.com/r/selfhosted/comments/1gml8cb/a_free_open_source_locally_hosted_search_engine)
 - RSS feed: $source
 - date published: 2024-11-08T15:32:17+00:00

<!-- SC_OFF --><div class="md"><p>A while back I released version 1 of [a locally servable meme search engine](<a href="https://www.reddit.com/r/selfhosted/comments/1e3x6l0/i%5C_built%5C_a%5C_free%5C_open%5C_source%5C_locally%5C_hosted%5C_search/">https://www.reddit.com/r/selfhosted/comments/1e3x6l0/i\_built\_a\_free\_open\_source\_locally\_hosted\_search/</a>).</p> <p>A new version is now available that includes many requested features from that original post!</p> <p>Find it here 👉 <a href="https://github.com/neonwatty/meme_search">https://github.com/neonwatty/meme_search</a></p> <p>Both the original &quot;standard&quot; and new &quot;pro&quot; versions are free + open source + installable via docker!</p> <p>Addittional features rolling out with this new &quot;pro&quot; version include:</p> <ol> <li><strong>Auto-Generate Meme Descriptions:</strong> Target specific memes for auto-description generation (instead of applying to your entire directory).</li> <li><strong>Manual Meme Descr

## Best Linux Distro For Low Resource VPS
 - [https://www.reddit.com/r/selfhosted/comments/1gml4u1/best_linux_distro_for_low_resource_vps](https://www.reddit.com/r/selfhosted/comments/1gml4u1/best_linux_distro_for_low_resource_vps)
 - RSS feed: $source
 - date published: 2024-11-08T15:28:08+00:00

<!-- SC_OFF --><div class="md"><p>Hello, anyone can suggest me a Good Linux Based Distro for 1core CPU, 2GB Ram, 25GB SSD Storage, i wanna use only postfix,dovecot,openlitespeed,php,mariadb,techtenium dns,openvpn,nextcloud,etc! without any panel like webuzo,cpanel,aapanel,etc! personally i like debian &amp; almalinux or rockylinux, but i am confused whice should be best for me debian or almalinux &amp; rockylinux with stable performance cause i Don&#39;t like downtime without major issues., o wann up my server 24/7/365 Note: this server is not for production! only for my some perosnal site host &amp; experiment + self hosted mail server, dns server, vps server etc.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Adventurous-Web-451"> /u/Adventurous-Web-451 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gml4u1/best_linux_distro_for_low_resource_vps/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhost

## Best 10TB backup system under $500? (beginner)
 - [https://www.reddit.com/r/selfhosted/comments/1gmku85/best_10tb_backup_system_under_500_beginner](https://www.reddit.com/r/selfhosted/comments/1gmku85/best_10tb_backup_system_under_500_beginner)
 - RSS feed: $source
 - date published: 2024-11-08T15:15:21+00:00

<!-- SC_OFF --><div class="md"><p>Hello. I am a film student and I need to store around 10-15TB of video files safely for a longer period of time, let&#39;s say 5 years or so. What would the best backup options be? I heard there are NAS systems, should I look into those? Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/thecasual552"> /u/thecasual552 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmku85/best_10tb_backup_system_under_500_beginner/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmku85/best_10tb_backup_system_under_500_beginner/">[comments]</a></span>

## Proxmox VE - Backup Cluster config (pmxcfs) - /etc/pve
 - [https://www.reddit.com/r/selfhosted/comments/1gmkjpz/proxmox_ve_backup_cluster_config_pmxcfs_etcpve](https://www.reddit.com/r/selfhosted/comments/1gmkjpz/proxmox_ve_backup_cluster_config_pmxcfs_etcpve)
 - RSS feed: $source
 - date published: 2024-11-08T15:02:26+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/esiy0676"> /u/esiy0676 </a> <br/> <span><a href="https://www.reddit.com/r/Proxmox/comments/1ghrvqn/proxmox_ve_backup_cluster_config_pmxcfs_etcpve/?utm_source=share&amp;utm_medium=web3x&amp;utm_name=web3xcss&amp;utm_term=1&amp;utm_content=share_button">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmkjpz/proxmox_ve_backup_cluster_config_pmxcfs_etcpve/">[comments]</a></span>

## GPU vs CPU Transcoding
 - [https://www.reddit.com/r/selfhosted/comments/1gmkgep/gpu_vs_cpu_transcoding](https://www.reddit.com/r/selfhosted/comments/1gmkgep/gpu_vs_cpu_transcoding)
 - RSS feed: $source
 - date published: 2024-11-08T14:58:41+00:00

<!-- SC_OFF --><div class="md"><p>Since i started a server for my movies and series with an old computer i started to wonder, whats the best for trasncoding? GPU or just the CPU? Since i have a lot of low res videos and a 4k compatible TV i just want to have the best quality as posibile, but i dont know if i have to buy a GPU to get the best of my humble setup.</p> <p>Specs:</p> <p>MB: Asrock h110m-hdv r3.0<br/> CPU: Pentium G4500 Dual core 3.50 GHz<br/> RAM: 16 GB Dual Channel DDr4<br/> PSU: Generic<br/> Case: Generic<br/> SSD: Kingston A400 480 GB<br/> HDD: A lot of 2TBs</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/vaquishaProdigy"> /u/vaquishaProdigy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmkgep/gpu_vs_cpu_transcoding/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmkgep/gpu_vs_cpu_transcoding/">[comments]</a></span>

## How to arr's access indexers?
 - [https://www.reddit.com/r/selfhosted/comments/1gmk3k3/how_to_arrs_access_indexers](https://www.reddit.com/r/selfhosted/comments/1gmk3k3/how_to_arrs_access_indexers)
 - RSS feed: $source
 - date published: 2024-11-08T14:43:05+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve found plenty of information about how the downloader (i.e. SABNzb) accesses the provider over SSL, so you&#39;re probably fine without a VPN. But do the arr&#39;s (Radarr/Sonarr) access the API for indexers over SSL? I haven&#39;t seen any settings for that and don&#39;t really understand how it works. I assume that because the API address is HTTPS that it does use SSL, but I&#39;m not sure. Thanks for any info!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bourbondoc"> /u/bourbondoc </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmk3k3/how_to_arrs_access_indexers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmk3k3/how_to_arrs_access_indexers/">[comments]</a></span>

## Announcement: TSDProxy 0.6.0
 - [https://www.reddit.com/r/selfhosted/comments/1gmjfiy/announcement_tsdproxy_060](https://www.reddit.com/r/selfhosted/comments/1gmjfiy/announcement_tsdproxy_060)
 - RSS feed: $source
 - date published: 2024-11-08T14:12:29+00:00

<!-- SC_OFF --><div class="md"><p>TsDProxy simplifies the process of securely exposing Docker containers to your <strong>Tailscale</strong> network by automatically creating Tailscale machines for each tagged container. This allows services to be accessible via unique, secure URLs without the need for complex configurations or additional Tailscale containers.</p> <p>What&#39;s new?</p> <ul> <li>Optional Authkey for each service (this way you can add tags for a container).</li> <li>Optional Authkey File for each service ( if you don&#39;t want to use keys in docker-compose)</li> <li>add HTTP redirect (<a href="http://service.funny-name.ts.net">http://service.funny-name.ts.net</a> will be redirectes to <a href="https://service.funny-name.ts.net">https://service.funny-name.ts.net</a>)</li> </ul> <p><a href="https://almeidapaulopt.github.io/tsdproxy/">https://almeidapaulopt.github.io/tsdproxy/</a></p> <p><a href="https://github.com/almeidapaulopt/tsdproxy">https://github.com/almeidapaulo

## IO200 Open-source galley alternative
 - [https://www.reddit.com/r/selfhosted/comments/1gmio75/io200_opensource_galley_alternative](https://www.reddit.com/r/selfhosted/comments/1gmio75/io200_opensource_galley_alternative)
 - RSS feed: $source
 - date published: 2024-11-08T13:35:59+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I am an amateur photographer and I currently use Hugo with <a href="https://nicokaiser.github.io/hugo-theme-gallery/">this theme</a> to self-host my portfolio. However, I find it quite painful to manage the files I upload, and I would really like a dashboard where I can manage my photos.</p> <p>I stumbled across IO200, which seems to be perfect for my needs:</p> <p>- The rendered gallery has a great, very simple design (similar to the theme I already use, e.g. <a href="https://www.theme-demo.io200.com/?theme=minimal">https://www.theme-demo.io200.com/?theme=minimal</a>)</p> <p>- It has an easy-to-use admin interface to manage albums, tags and photos.</p> <p>I searched for an open-source alternative (I already looked at awesome-selfhosted list), but they either are pretty ugly, or not made for a gallery but more for photo sharing (like Immich).</p> <p>I&#39;m also open if anyone has a suggestion for an easy workflow with Hugo, but curren

## Whats the least idle Power consumption Server i could get?
 - [https://www.reddit.com/r/selfhosted/comments/1gmigaa/whats_the_least_idle_power_consumption_server_i](https://www.reddit.com/r/selfhosted/comments/1gmigaa/whats_the_least_idle_power_consumption_server_i)
 - RSS feed: $source
 - date published: 2024-11-08T13:25:23+00:00

<!-- SC_OFF --><div class="md"><p>I just want to have a Server for Adguard Home and Jellyfin. I dont use transcoding in Jellyfin as i Always use Handbrake on my PC to encode it to the right Format for Directplay, which means it uses basically only resources to send the original file to the Client.</p> <p>N100 would probably be enough, but they dont have enough space for multiple SSDs. So what could i get with lets say space for 5x2,5&quot; Sata SSDs? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Shindikat"> /u/Shindikat </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmigaa/whats_the_least_idle_power_consumption_server_i/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmigaa/whats_the_least_idle_power_consumption_server_i/">[comments]</a></span>

## This Week in Self-Hosted (8 November 2024)
 - [https://www.reddit.com/r/selfhosted/comments/1gmhs97/this_week_in_selfhosted_8_november_2024](https://www.reddit.com/r/selfhosted/comments/1gmhs97/this_week_in_selfhosted_8_november_2024)
 - RSS feed: $source
 - date published: 2024-11-08T12:51:43+00:00

<!-- SC_OFF --><div class="md"><p>Happy Friday, <a href="/r/selfhosted">r/selfhosted</a>! Linked below is the latest edition of <em>This Week in Self-Hosted</em>, a weekly newsletter recap of the latest activity in self-hosted software.</p> <p>This week&#39;s content includes recognition of Home Assistant&#39;s accomplishments as an open-source project in GitHub&#39;s annual Octoverse report, notable software updates and launches, and a spotlight on <a href="https://github.com/benjaminjonard/koillection?ref=selfh.st">Koillection</a> - a self-hosted physical collection tracking platform.</p> <p>For those who&#39;d like to watch on YouTube or listen to the episode via podcast, I&#39;m joined this week by YouTuber <a href="https://www.youtube.com/@DBTechYT">DB Tech</a> (<a href="/u/davidnburgess34">/u/davidnburgess34</a>).</p> <p>Thanks, and as usual, feel free to reach out with feedback!</p> <hr/> <p><a href="https://selfh.st/newsletter/2024-11-08/?ref=reddit">Newsletter</a> | <a href=

## Plex/Emby/Jelyfin
 - [https://www.reddit.com/r/selfhosted/comments/1gmhrhv/plexembyjelyfin](https://www.reddit.com/r/selfhosted/comments/1gmhrhv/plexembyjelyfin)
 - RSS feed: $source
 - date published: 2024-11-08T12:50:37+00:00

<!-- SC_OFF --><div class="md"><p>I have all three setup on the same hardware - They are run on unraid and from Dockers</p> <p>They all have the same access to the same hardware and the same files on the same drives - So there should be little to no variables in the hardware side of things</p> <p>Plex has been in use the longest - but i have had the emby and jellyfin dockers running for a few years now too! </p> <p>Around the house I use chromecasts, Roku, Android TV Apps and windows devices </p> <p>Plex appears way less stable now - Todays example - playing a movie to a chromcast, plex was stuttering and even hanging when i tried to manually change from original to a lower quality setting - emby just played no issues! </p> <p>Is this a common thing now?<br/> I posted here for a more broad answer rather than the <a href="/r/emby">r/emby</a> or <a href="/r/PleX">r/PleX</a> Subs</p> <p>The dockers I use are Embys own and Linxservers plex docker</p> </div><!-- SC_ON --> &#32; submitted 

## Seafile (or alternatives) for 32-bit ARM
 - [https://www.reddit.com/r/selfhosted/comments/1gmhip5/seafile_or_alternatives_for_32bit_arm](https://www.reddit.com/r/selfhosted/comments/1gmhip5/seafile_or_alternatives_for_32bit_arm)
 - RSS feed: $source
 - date published: 2024-11-08T12:37:24+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to self-host a cloud instance to store files on my Orange Pi One and access them later from my other devices. Seafile got my attention as a light solution, but I have trouble running the latest versions of it. What can I do to make it work or should I consider any other alternatives?</p> <p>Please do not suggest NextCloud, it&#39;s too OP for my needs.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/alexavil"> /u/alexavil </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmhip5/seafile_or_alternatives_for_32bit_arm/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmhip5/seafile_or_alternatives_for_32bit_arm/">[comments]</a></span>

## Reverse Proxy- Bad request...Caddy > Nextcloud
 - [https://www.reddit.com/r/selfhosted/comments/1gmh1er/reverse_proxy_bad_requestcaddy_nextcloud](https://www.reddit.com/r/selfhosted/comments/1gmh1er/reverse_proxy_bad_requestcaddy_nextcloud)
 - RSS feed: $source
 - date published: 2024-11-08T12:10:02+00:00

<!-- SC_OFF --><div class="md"><p>Getting the 400 Bad request speaking &quot;HTTP to SSL-enabled port instead use HTTPS&quot;.</p> <p>I have spent hours trying to figure out where it is going wrog I really cant make any progress. Someone who knows Caddy and Nextcloud please point me in the right direction. I am beyond frustrated.</p> <p>I have a domain eg &#39;domain.com&#39; and I have CNAME records for &#39;jellyfin&#39; and &#39;nextcloud&#39;</p> <p>Caddy local IP - <a href="http://192.168.150.10">192.168.150.10</a></p> <p>/etc/caddy/Caddyfile:</p> <pre><code>domain.com { root * /usr/share/caddy file_server } nextcloud.domain.com { reverse_proxy 192.168.150.20:443 } jellyfin.domain.com { reverse_proxy 192.168.150.30:8096 } </code></pre> <p>When I go to <a href="http://domain.com">domain.com</a> I see the caddy test page as expected, when I go to <a href="http://jellyfin.domain.com">jellyfin.domain.com</a> that also works as expected where I can log into my jellyfin server.</p> <p

## What's the roadmap for efficient and low-cost AI processors?
 - [https://www.reddit.com/r/selfhosted/comments/1gmgv8z/whats_the_roadmap_for_efficient_and_lowcost_ai](https://www.reddit.com/r/selfhosted/comments/1gmgv8z/whats_the_roadmap_for_efficient_and_lowcost_ai)
 - RSS feed: $source
 - date published: 2024-11-08T12:00:08+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;d like to try some local AI stuff, but buying a GPU and stuffing it into my 2U case doesn&#39;t seem like a good decision (cost is too high, power consumption is too high, space inside the case is limited).</p> <p>For Frigate I use the Coral TPU and it&#39;s amazing for it&#39;s cost, size and power efficiency.</p> <p>Are we going to get AI specific processors that cost less than a comparable (in term of AI workforce) GPU? Something like a beefed up Coral TPU that can run LLMs or generative AI like Stable Diffusion?</p> <p>Sidenote: is there a metric to understand the AI capabilities of a device? Like <code>&quot;how much X does a nVidia 2070 have? Does it have more X than an Apple M4?&quot;</code> What is X? Are there benchmarks to measure it? Do we have a public repository with these standardized benchmarks?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dreadino"> /u/Dreadino </a> <br/> <span><a href="

## Running a Foundry VTT Server locally and opening it to the internet without a static ip
 - [https://www.reddit.com/r/selfhosted/comments/1gmgshe/running_a_foundry_vtt_server_locally_and_opening](https://www.reddit.com/r/selfhosted/comments/1gmgshe/running_a_foundry_vtt_server_locally_and_opening)
 - RSS feed: $source
 - date published: 2024-11-08T11:55:05+00:00

<!-- SC_OFF --><div class="md"><p>Hello fellow self-hosters. I have been slaving my nights away trying to get the foundryVTT nodejs server to be accessible from the web using a domain I have. But since my isp doesn&#39;t allow static ip&#39;s, I have no clear way to use my domain to connect to my server. I am running the server on a raspberry pi 5 (8GB) with raspberry headless os running on it. I have no problem connecting to the local server via <a href="http://192.168.1.34:30000">192.168.1.34:30000</a> (local IP port 30000) I have port forwarded(I think) the required ports. I did try caddy reverse proxy (I was using this guide: <a href="https://foundryvtt.wiki/en/setup/linux-installation">https://foundryvtt.wiki/en/setup/linux-installation</a> ). I tried a DuckDNS domain and a bought domain (from a turkish website <a href="https://www.isimtescil.net/">https://www.isimtescil.net/</a> ). Neither worked/ I couldn&#39;t set it up properly. I could use something like ngrok or localtunne

## Is there a self-hosted version similar to the Today Budget iOS apps?
 - [https://www.reddit.com/r/selfhosted/comments/1gmgj51/is_there_a_selfhosted_version_similar_to_the](https://www.reddit.com/r/selfhosted/comments/1gmgj51/is_there_a_selfhosted_version_similar_to_the)
 - RSS feed: $source
 - date published: 2024-11-08T11:38:04+00:00

<!-- SC_OFF --><div class="md"><p>The basic idea is that per day you are given a maximum expenditure from the total amount of money set for the period.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/boosterhq"> /u/boosterhq </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmgj51/is_there_a_selfhosted_version_similar_to_the/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmgj51/is_there_a_selfhosted_version_similar_to_the/">[comments]</a></span>

## wanderer v0.10.0 - a self-hosted GPS track database
 - [https://www.reddit.com/r/selfhosted/comments/1gmgb42/wanderer_v0100_a_selfhosted_gps_track_database](https://www.reddit.com/r/selfhosted/comments/1gmgb42/wanderer_v0100_a_selfhosted_gps_track_database)
 - RSS feed: $source
 - date published: 2024-11-08T11:23:23+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gmgb42/wanderer_v0100_a_selfhosted_gps_track_database/"> <img src="https://b.thumbs.redditmedia.com/UjCk5QK52P1tg0ijEe07HUoLK2Nq9kAgKbx8EixUkrk.jpg" alt="wanderer v0.10.0 - a self-hosted GPS track database" title="wanderer v0.10.0 - a self-hosted GPS track database" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>wanderer recently celebrated it’s 10th anniversary. Well, as far as minor versions go at least.</p> <p>First and foremost: What is wanderer?<br/> wanderer is a self-hosted GPS track database. You can upload your recorded GPS tracks or create new ones and add various metadata to build an easily searchable catalogue. Think of it as a fully FOSS alternative to sites like alltrails, komoot or strava.</p> <p>Next: Thank you for almost 1.2k stars on <a href="https://github.com/Flomp/wanderer">GitHub</a>. It’s a great motivation to see how well-received wanderer is.</p> <p>By far the mo

## Does any Here using .xyz 1.111b domains for Personal Blog use?
 - [https://www.reddit.com/r/selfhosted/comments/1gmfnhk/does_any_here_using_xyz_1111b_domains_for](https://www.reddit.com/r/selfhosted/comments/1gmfnhk/does_any_here_using_xyz_1111b_domains_for)
 - RSS feed: $source
 - date published: 2024-11-08T10:39:30+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys i want to Know about this i want to purchase a Domain for cheap i came to know that 1.111b domain are $0.99/yr so i want to use it For My Personal Blog. Anyone are using? Any Sample Websites? Please </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/razorimpact"> /u/razorimpact </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmfnhk/does_any_here_using_xyz_1111b_domains_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmfnhk/does_any_here_using_xyz_1111b_domains_for/">[comments]</a></span>

## Is there any interest in a self hosted Health aggregator app?
 - [https://www.reddit.com/r/selfhosted/comments/1gmfmur/is_there_any_interest_in_a_self_hosted_health](https://www.reddit.com/r/selfhosted/comments/1gmfmur/is_there_any_interest_in_a_self_hosted_health)
 - RSS feed: $source
 - date published: 2024-11-08T10:38:14+00:00

<!-- SC_OFF --><div class="md"><p>I recently switched my smartwatch to Gadgetbridge, scales to OpenScale, and nutrition tracker to Waistline etc for privacy reasons and not sending my health data to online servers. However unlike the stock apps (Fitbit, Renpho, LoseIt respectively) these apps do not talk to each other or really any other service. I do miss the aggregation of something like Google Fit where all the data is in one app.</p> <p>There are some excellent self hosted apps like workout-tracker, Endurian, FitTrackee etc that do a great job of displaying .gpx files but not much else. And there exist apps like &quot;OpenScale to Health Connect&quot; which help sync some of the local data into Health Connect on your phone, and HCGateway that converts Health Connect into an API that webapps can use, but there&#39;s no actual webapp to receive this data: I&#39;ve come to the conclusion I need to make one.</p> <p>My main idea is to sync your phone&#39;s Health Comnect to your serve

## How to deal with apps when using Zero trust, Authelia etc
 - [https://www.reddit.com/r/selfhosted/comments/1gmfi2l/how_to_deal_with_apps_when_using_zero_trust](https://www.reddit.com/r/selfhosted/comments/1gmfi2l/how_to_deal_with_apps_when_using_zero_trust)
 - RSS feed: $source
 - date published: 2024-11-08T10:28:54+00:00

<!-- SC_OFF --><div class="md"><p>Hi!</p> <p>I have just started with self-hosting stuff and I&#39;m using CF tunnels right now to be able to access my stuff outside my own network. Some of these stuff have android apps where you just write your url and everything works, the issue comes when you want to use security measures like Zero trust or Authelia. When I activate these the apps stops working.</p> <p>Maybe this question is per app but maybe there is an overall solution. Should I just skip using extra authentication or is there another solution?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/techquestions1234"> /u/techquestions1234 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmfi2l/how_to_deal_with_apps_when_using_zero_trust/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmfi2l/how_to_deal_with_apps_when_using_zero_trust/">[comments]</a></span>

## Alternatives to Nextcloud Calendars?
 - [https://www.reddit.com/r/selfhosted/comments/1gmffv7/alternatives_to_nextcloud_calendars](https://www.reddit.com/r/selfhosted/comments/1gmffv7/alternatives_to_nextcloud_calendars)
 - RSS feed: $source
 - date published: 2024-11-08T10:24:07+00:00

<!-- SC_OFF --><div class="md"><p>I started using Nextcloud a long time ago and found it especially helpful in my degoogling process. These days the only thing I really still use it for are calendars, which seems overkill now.</p> <p>Are there any other good calendaring services we can selfhost these days? Allowing for accounts, sharing, pulling from google cal feeds etc?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/slvrbckt"> /u/slvrbckt </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmffv7/alternatives_to_nextcloud_calendars/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmffv7/alternatives_to_nextcloud_calendars/">[comments]</a></span>

## Offsite remote storage for backups... OS and software.
 - [https://www.reddit.com/r/selfhosted/comments/1gmeqno/offsite_remote_storage_for_backups_os_and_software](https://www.reddit.com/r/selfhosted/comments/1gmeqno/offsite_remote_storage_for_backups_os_and_software)
 - RSS feed: $source
 - date published: 2024-11-08T09:30:56+00:00

<!-- SC_OFF --><div class="md"><p>Hey hosters, I&#39;m working on getting some offsite storage setup for backups. First some context:</p> <ul> <li>I live in AUS</li> <li>Parents live in the US</li> <li>Have roughly 8tb to backup - this is growing at a pretty steady (and quick) pace</li> <li>already have 1 backup on site</li> <li>will not have regular physical access to the remote system, but mildly tech literate parents will</li> <li>network/internet speed on either end isn&#39;t an issue</li> </ul> <p>I&#39;m looking to setup a remote system that uses rsync (my preferred tool for data backups) to make updates to a backup disk connected to a rpi at my parents place in the US. Getting into their network might be an issue but WG should be sufficient to bridge that, although something that allows for a service like tailscale to run as well for backup remote access/repairs would be preferable if possible.</p> <p>Wondering what success others have had with different systems/utilities. I&#

## Regarding Netbird Peer advertising routes, dont get new peers automatic
 - [https://www.reddit.com/r/selfhosted/comments/1gmeq2o/regarding_netbird_peer_advertising_routes_dont](https://www.reddit.com/r/selfhosted/comments/1gmeq2o/regarding_netbird_peer_advertising_routes_dont)
 - RSS feed: $source
 - date published: 2024-11-08T09:29:41+00:00

<!-- SC_OFF --><div class="md"><p>I have a Selfhosted Netbird Installation. My Problem is that I have a connected peer that advertises routes and it works fine. But when a new client or peer joins, the peer that advertises routes does not get the new peers automatic and therefore cant communicate with them. I have to make a Netbird down and then Netbird up, then it finds the new peer.</p> <p>So its the Peers count: 2/5 Connected that dont count up to for example 2/6 when a new client gets added. I have to restart the netbird.</p> <p>Are there a command to call or why does it not find it itself?</p> <p>----------------------------------</p> <p>OS: linux/amd64</p> <p>Daemon version: 0.31.0</p> <p>CLI version: 0.31.0</p> <p>Management: Connected to <a href="https://netbirdvpn.domain.com/">https://netbirdvpn.domain.com:443</a></p> <p>Signal: Connected to <a href="https://netbirdvpn.domain.com/">https://netbirdvpn.domain.com:443</a></p> <p>Relays:</p> <p>[stun:netbirdvpn.domain.com:3478] 

## file uploading app/project with resumable uploads and no account required?
 - [https://www.reddit.com/r/selfhosted/comments/1gme9z9/file_uploading_appproject_with_resumable_uploads](https://www.reddit.com/r/selfhosted/comments/1gme9z9/file_uploading_appproject_with_resumable_uploads)
 - RSS feed: $source
 - date published: 2024-11-08T08:55:23+00:00

<!-- SC_OFF --><div class="md"><p>I want teammates&#39; parents to easily be able to upload soccer game recording clips they may have of my kid to a self hosted app. I tried OneDrive (consumer/MS account version) since I already pay for it, but that requires the parent to have an MS/OneDrive account. Is there an self hosted app/project that is web based, can resume uploads and does not require an uploader to have an account (i.e., if they have the link, they can edit/create/upload)?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/seenliving"> /u/seenliving </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gme9z9/file_uploading_appproject_with_resumable_uploads/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gme9z9/file_uploading_appproject_with_resumable_uploads/">[comments]</a></span>

## N100 alternatives.
 - [https://www.reddit.com/r/selfhosted/comments/1gmdv6t/n100_alternatives](https://www.reddit.com/r/selfhosted/comments/1gmdv6t/n100_alternatives)
 - RSS feed: $source
 - date published: 2024-11-08T08:23:39+00:00

<!-- SC_OFF --><div class="md"><p>Want to &quot;persuade&quot; my kid to actually learn something by setting up small server for him.<br/> (also totally not for my self) </p> <p>Want to host there some simple game servers, something like GameValut, maybe jellyfin. </p> <p>Never did this so well it will be small learning curve for me. </p> <p>Because of that i am wondering what hardware to go for.<br/> Have some spare SSD laying around and 2x DDR5 4200 16gb that would be shame not to use. </p> <p>I am bit afraid that N100 would have issues with potentially all of this running ... or not ???<br/> It is better ask before buying and then seeing it is not enough. </p> <p>My old T620 (4 core) is not enough for even minecraft server , unless running something like paperMC. </p> <p>So the question is what do you propose, preferably passive cooled and reasonable power use. It can be a huge brick, don&#39;t care to much for a size.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="htt

## What's on Your Wishlist this Black Friday?
 - [https://www.reddit.com/r/selfhosted/comments/1gmdpnc/whats_on_your_wishlist_this_black_friday](https://www.reddit.com/r/selfhosted/comments/1gmdpnc/whats_on_your_wishlist_this_black_friday)
 - RSS feed: $source
 - date published: 2024-11-08T08:12:08+00:00

<!-- SC_OFF --><div class="md"><p>Hello self-hosters, Black Friday and Cyber Monday are just around the corner!</p> <p>What self-hosted services or software licenses are you hoping to score deals on?</p> <p>Are there any lifetime licenses or subscription services that you&#39;re waiting for a discount on?</p> <p>Let&#39;s discuss and explore new gems!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/GameOffNodes"> /u/GameOffNodes </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmdpnc/whats_on_your_wishlist_this_black_friday/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmdpnc/whats_on_your_wishlist_this_black_friday/">[comments]</a></span>

## How do I *actually* put something online?
 - [https://www.reddit.com/r/selfhosted/comments/1gmdolg/how_do_i_actually_put_something_online](https://www.reddit.com/r/selfhosted/comments/1gmdolg/how_do_i_actually_put_something_online)
 - RSS feed: $source
 - date published: 2024-11-08T08:09:54+00:00

<!-- SC_OFF --><div class="md"><p>Hopefully this is the right subreddit to ask this, it looked like the more relevant one; I&#39;m still a beginner on many sides of it, and have never put any website online. Of course I don&#39;t want anything professional yet, I&#39;m currently just creating some fun stuff to share with people I know, so I don&#39;t care about extra adds and options... I just wanted to put something online for easier browsing. I tried GitHub but it keeps giving issues, I also heard DuckDNS is a good idea, but... How does the whole thing work? How do I put some files online for good?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/EducationalTreacle71"> /u/EducationalTreacle71 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmdolg/how_do_i_actually_put_something_online/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmdolg/how_do_i_actually_put_something_online/">[co

## Netcup Discount Code Collection
 - [https://www.reddit.com/r/selfhosted/comments/1gmcbf2/netcup_discount_code_collection](https://www.reddit.com/r/selfhosted/comments/1gmcbf2/netcup_discount_code_collection)
 - RSS feed: $source
 - date published: 2024-11-08T06:29:58+00:00

<!-- SC_OFF --><div class="md"><p>I noticed that many MJJ don’t know that netcup has discount codes. Most people only know about a 5 EUR discount code (but this 5 EUR code only waives the setup fee, and since our RS and VPS already have no setup fee, it essentially provides no real discount).</p> <p>There are also some MJJ who see others sharing discount codes, but when they try to use them, they find that they don’t work (this is because each discount code can only be used once).</p> <p>So, I launched a website where MJJ can easily find netcup discount codes for those who have trouble finding them.</p> <p><a href="https://netcup.gifts/#request-form">https://netcup.gifts/#request-form</a></p> <p><strong>Discount Code Usage Notes:</strong></p> <ol> <li>Discount codes are not limited to new users; existing users can also use them.</li> <li>If you want to purchase RS1000, there&#39;s no need to buy a new RS1000. Simply go to the discount code redemption page, redeem the discount code fo

## So many negative Nextcloud posts...
 - [https://www.reddit.com/r/selfhosted/comments/1gmc16j/so_many_negative_nextcloud_posts](https://www.reddit.com/r/selfhosted/comments/1gmc16j/so_many_negative_nextcloud_posts)
 - RSS feed: $source
 - date published: 2024-11-08T06:11:07+00:00

<!-- SC_OFF --><div class="md"><p>I think I&#39;ve seen a dozen of those recently: can&#39;t install, can&#39;t configure, can&#39;t update...</p> <p>I installed Nextcloud on my VPS in 2017 by using (an earlier version) of <a href="https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mariadb-php-lamp-stack-debian9">this</a> guide first to install LAMP stack on Debian 7, followed by another guide for installing Nextcloud on DigitalOcean that I can&#39;t find now (the current one uses snap, I didn&#39;t, I just wgetted tar.gz).</p> <p>It took like 2 days to configure and has been working flawlessly since, through all the Nextcloud upgrades, Debian upgrades and moving VPS from DigitalOcean to OVH via rsync at one point.</p> <p>Personally, I can&#39;t help but feel this is the case of docker-related enshittification, because most people complain about some arcane docker compose things that I don&#39;t even understand because I&#39;m too old.</p> </div><!-- SC_ON -

## Has anyone gotten filestash working with onlyoffice behind Nginx Proxy Manager?
 - [https://www.reddit.com/r/selfhosted/comments/1gmbvyf/has_anyone_gotten_filestash_working_with](https://www.reddit.com/r/selfhosted/comments/1gmbvyf/has_anyone_gotten_filestash_working_with)
 - RSS feed: $source
 - date published: 2024-11-08T06:01:39+00:00

<!-- SC_OFF --><div class="md"><p>Filestash works great and connects fine to onlyoffice on http connection, but when I put them behind nginx proxy manager with my letsencrypt SSL cert, filestash no longer connects when I try to open a word doc. It simply says <code>[error] Can&#39;t reach the onlyoffice server</code>. I&#39;m running it with podman and I&#39;m using nginx webdav as a backend in a separate podman container (<a href="https://github.com/dgraziotin/docker-nginx-webdav-nononsense">https://github.com/dgraziotin/docker-nginx-webdav-nononsense</a>)</p> <p>The filestash logs shows this:</p> <pre><code>2024/11/08 05:45:24 HTTP 404 GET 0.1ms /web-apps/apps/api/documents/api.js 2024/11/08 05:46:39 HTTP 304 GET 4.0ms /api/files/ls?path=%2FBinder%20Material%2F 2024/11/08 05:46:44 HTTP 304 GET 1.3ms /api/files/ls?path=%2F 2024/11/08 05:46:46 HTTP 200 GET 0.9ms /api/files/ls?path=%2FBMI%20HCI%2F 2024/11/08 05:46:51 HTTP 200 GET 1390.7ms /api/onlyoffice/iframe?path=/BMI%20HCI/HCI%20P

## Mac mini vs mini pc
 - [https://www.reddit.com/r/selfhosted/comments/1gmbe32/mac_mini_vs_mini_pc](https://www.reddit.com/r/selfhosted/comments/1gmbe32/mac_mini_vs_mini_pc)
 - RSS feed: $source
 - date published: 2024-11-08T05:30:21+00:00

<!-- SC_OFF --><div class="md"><p>Hi! I want to set up my first server; I really need it to have my entertainment center with Emby.</p> <p>I’m considering either buying a Mac mini (2014) or a mini PC. I’m quite familiar with both operating systems, so I can adapt to the best option. The question is, which one is better for me in terms of power consumption?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok_Office543"> /u/Ok_Office543 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmbe32/mac_mini_vs_mini_pc/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gmbe32/mac_mini_vs_mini_pc/">[comments]</a></span>

## I'm writing some personal library management software, anyone want to suggest features?
 - [https://www.reddit.com/r/selfhosted/comments/1gm9r1a/im_writing_some_personal_library_management](https://www.reddit.com/r/selfhosted/comments/1gm9r1a/im_writing_some_personal_library_management)
 - RSS feed: $source
 - date published: 2024-11-08T03:55:38+00:00

<!-- SC_OFF --><div class="md"><p>Problem: The number of physical books I have is becoming cumbersome to manage. I live in Asia, my home is probably the size of some of your hallways. So... stacked bins, not bookshelves. Not super convenient to physically search for books if you have more than 100 or so.</p> <p>I looked at Koha / Evergreen OpenBiblio. I installed Koha. It works OK, but it doesn&#39;t handle content discovery very well -- it helps you find something if you already know the author / title / etc. Also the memory footprint (~4GB) is quite large!</p> <p>It&#39;s not too hard for me to just build something myself that fits in some 100MB of memory on my sever and has the features I want. I was thinking:</p> <ol> <li>Books have titles, authors, genres, summary, cover art, ISBN, and their physical location (a bin number or bookshelf). Also ownership (true/false) and withdrawal status (true/false). No need for the massive amount of data held in MARC records or whatever. No nee

## Proxmox - write 1M, get 2.8G in amplified write (POLL)
 - [https://www.reddit.com/r/selfhosted/comments/1gm9q5c/proxmox_write_1m_get_28g_in_amplified_write_poll](https://www.reddit.com/r/selfhosted/comments/1gm9q5c/proxmox_write_1m_get_28g_in_amplified_write_poll)
 - RSS feed: $source
 - date published: 2024-11-08T03:54:20+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/esiy0676"> /u/esiy0676 </a> <br/> <span><a href="https://www.reddit.com/r/homelab/comments/1glrgz3/proxmox_write_1m_get_28g_in_amplified_write/?utm_source=share&amp;utm_medium=web3x&amp;utm_name=web3xcss&amp;utm_term=1&amp;utm_content=share_button">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gm9q5c/proxmox_write_1m_get_28g_in_amplified_write_poll/">[comments]</a></span>

## How do I route to my internal network via subdomain?
 - [https://www.reddit.com/r/selfhosted/comments/1gm86hl/how_do_i_route_to_my_internal_network_via](https://www.reddit.com/r/selfhosted/comments/1gm86hl/how_do_i_route_to_my_internal_network_via)
 - RSS feed: $source
 - date published: 2024-11-08T02:32:37+00:00

<!-- SC_OFF --><div class="md"><p>I’m looking to set up a domain such that when I am home the url routes to the local address and when I’m away goes through my external dns. </p> <p>What I currently have: a domain, caddy set up with reverse proxy to Cloudflare with dns pointing to a Tailscale address. </p> <p>I am running Linux with caddy and Tailscale set up on the host along with a variety of docker containers.</p> <p>My goal is when I enter the url jellyfin.mydomain.com if I am home I want to route it to the local address of say 192.168.0.1:8096 and when I am connected to Tailscale away from home I want it to route through Cloudflare. Essentially when I&#39;m home I don&#39;t want to run it through Tailscale since I&#39;m local. </p> <p>I have the external part working but can’t figure out how to route it internally. Would I need a local dns server to accomplish this?</p> <p>Would really appreciate some help. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.

## Questions on my potential setup
 - [https://www.reddit.com/r/selfhosted/comments/1gm7ycj/questions_on_my_potential_setup](https://www.reddit.com/r/selfhosted/comments/1gm7ycj/questions_on_my_potential_setup)
 - RSS feed: $source
 - date published: 2024-11-08T02:21:03+00:00

<!-- SC_OFF --><div class="md"><p>Hi all!</p> <p>I started my selfhosting journey by running webservers off of raspberry pis and old desktop computers. Mostly basic websites, blogs or game servers. I have a Digital Ocean droplet that I used to use for everything after moving away from the pis. Lately I&#39;ve fired up a couple separate instances in oracle cloud (currently within free limits) and have been migrating some of my stuff over there. I currently have one for running my FoundryVTT servers, one I&#39;m using for developing a web app and one I just provisioned to test out NextCloud. I&#39;m currently paying for 100GB of Google One, but I&#39;ve been pretty much perpetually out of space on it. I&#39;d rather not pay for a higher tier of Google One, and I&#39;d also really like to bring everything back under my own control. </p> <p>What I&#39;m thinking I would really like to do is set up 3 separate servers/NAS devices, one at home, one at my parents&#39; and one at my in-laws&#

## Homebox alternative now that it is dead??
 - [https://www.reddit.com/r/selfhosted/comments/1gm6ei0/homebox_alternative_now_that_it_is_dead](https://www.reddit.com/r/selfhosted/comments/1gm6ei0/homebox_alternative_now_that_it_is_dead)
 - RSS feed: $source
 - date published: 2024-11-08T01:02:33+00:00

<!-- SC_OFF --><div class="md"><p>Is there an alternative to homebox now that it is no longer being worked on?</p> <p>I just found it and love it however I am getting errors when trying to view pdf&#39;s I have uploaded to it. </p> <p>I love that i can add all my information. I just installed a new water heater and was able to log all the information and upload receipts and manuals.</p> <p>The great thing about homebox is I can upload multiple pdf&#39;s for a single item.<br/> I didn&#39;t see that option when trying to use Grocy.</p> <p>Unfortunately homebox is no longer being developed so I was hoping to find something similar. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Hukai572"> /u/Hukai572 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gm6ei0/homebox_alternative_now_that_it_is_dead/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gm6ei0/homebox_alternative_now_that_it_is_d

## Need Help Setting Up a Self-Hosted AI Chatbot for Document Querying
 - [https://www.reddit.com/r/selfhosted/comments/1gm68a1/need_help_setting_up_a_selfhosted_ai_chatbot_for](https://www.reddit.com/r/selfhosted/comments/1gm68a1/need_help_setting_up_a_selfhosted_ai_chatbot_for)
 - RSS feed: $source
 - date published: 2024-11-08T00:54:05+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I’m hoping to get some guidance on setting up a self-hosted AI chatbot that can reference a directory of files—mainly PDFs, text files, and markdown. My goal is to be able to load it up with documentation and other resources and then ask the chatbot specific questions, like a personal lab assistant.</p> <p>I’m comfortable with Docker and Linux servers, so I’m ready to dive into the setup. I’ve looked into various options but haven’t quite found a clear path for building something like this. I think Ollama might be involved, but I’d appreciate any advice on how to approach this project or suggestions on tools and configurations to consider.</p> <p>Thanks for any pointers!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Pi_ofthe_Beholder"> /u/Pi_ofthe_Beholder </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gm68a1/need_help_setting_up_a_selfhosted_ai_chatbot_for/">[link

## Finally got a reverse proxy and DNS Record setup I like
 - [https://www.reddit.com/r/selfhosted/comments/1gm5ri8/finally_got_a_reverse_proxy_and_dns_record_setup](https://www.reddit.com/r/selfhosted/comments/1gm5ri8/finally_got_a_reverse_proxy_and_dns_record_setup)
 - RSS feed: $source
 - date published: 2024-11-08T00:31:34+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been self hosting about a year and in that time I&#39;ve used synology&#39;s built in reverse proxy, caddy on a Raspberri Pi, Caddy in Docker etc, and now with a recent server consolidation project I&#39;ve finally moved to Caddy + Unbound DNS running on my OPNSense Firewall.</p> <p>The way I&#39;ve got it set up is now that my domain (let&#39;s say example.com) is registered with cloudflare. OPNSense uses Dynamic DNS to keep my public IP updated with cloudflare for all my public facing apps. So Cloudflare has an A Record pointing to my IP (lets say 100.100.100.100) for all my apps, such as jellyfin.example.com, git.example.com, etc.</p> <p>Then in OPNSense, ports 80 and 443 are forwarded to the firewall itself, which then intercepts the requests into built in Caddy and serves the correct local IP and port based on the domain name requested. So jellyfin.example.com goes to 10.0.0.10:8096 for example, and git.example.com goes to 10.0.0.11:300

## what happened to MovieMatch?
 - [https://www.reddit.com/r/selfhosted/comments/1gm5ipv/what_happened_to_moviematch](https://www.reddit.com/r/selfhosted/comments/1gm5ipv/what_happened_to_moviematch)
 - RSS feed: $source
 - date published: 2024-11-08T00:20:00+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://github.com/LukeChannings/moviematch">MovieMatch</a> was a great idea. a kind of tinder interface that you &amp; your users swipe right &amp; left on content to find things you all agree would be good to watch.</p> <p>seems to have been abandoned though. did anyone fork it, or is there a similar idea?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CrispyBegs"> /u/CrispyBegs </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gm5ipv/what_happened_to_moviematch/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gm5ipv/what_happened_to_moviematch/">[comments]</a></span>

