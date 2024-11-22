# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## The better way to run your Proxmox backups off ZFS
 - [https://www.reddit.com/r/selfhosted/comments/1gwtaa0/the_better_way_to_run_your_proxmox_backups_off_zfs](https://www.reddit.com/r/selfhosted/comments/1gwtaa0/the_better_way_to_run_your_proxmox_backups_off_zfs)
 - RSS feed: $source
 - date published: 2024-11-21T23:14:28+00:00

<!-- SC_OFF --><div class="md"><blockquote> <p>Proxmox Backup Server is nicely integrated into PVE’s web GUI, and can work with ZFS volumes. However, PBS is storage-agnostic, and as such it does not take advantage of snapshots and implements de-duplication using a chunk store indexed by checksum. This means that only the modified portions of a volume need to be transferred over the network to the backup server. </p> </blockquote> <p>The rest on <a href="https://www.reddit.com/r/ProxmoxQA/comments/1gwq4k9/taking_advantage_of_zfs_for_smarter_proxmox/">r/ProxmoxQA</a>.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/esiy0676"> /u/esiy0676 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwtaa0/the_better_way_to_run_your_proxmox_backups_off_zfs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwtaa0/the_better_way_to_run_your_proxmox_backups_off_zfs/">[comments]</a></span>

## r170 Can't Repurpose or Retire
 - [https://www.reddit.com/r/selfhosted/comments/1gwrtkx/r170_cant_repurpose_or_retire](https://www.reddit.com/r/selfhosted/comments/1gwrtkx/r170_cant_repurpose_or_retire)
 - RSS feed: $source
 - date published: 2024-11-21T22:10:02+00:00

<!-- SC_OFF --><div class="md"><p>As I understand it, I should be able to wipe this device using the Lifecycle Controller. I have it enabled and can get into it, but when I navigate into Hardware Diagnostics, several options are grayed out including Delete Configuration and Reset Defaults. I haven&#39;t been able to find a solution online or mucking around in the BIOS, so hoping someone here can help. Has anyone run into this before?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ThisGuyCanFlying"> /u/ThisGuyCanFlying </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwrtkx/r170_cant_repurpose_or_retire/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwrtkx/r170_cant_repurpose_or_retire/">[comments]</a></span>

## Do you use VPS over home server? Preferred VPS provider?
 - [https://www.reddit.com/r/selfhosted/comments/1gwrkky/do_you_use_vps_over_home_server_preferred_vps](https://www.reddit.com/r/selfhosted/comments/1gwrkky/do_you_use_vps_over_home_server_preferred_vps)
 - RSS feed: $source
 - date published: 2024-11-21T21:59:30+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking to move away from my dependency on Google and Microsoft services (for cloud storage, image storage, productivity apps, etc). I&#39;m in the process of building a home server, but I&#39;m looking at other options to start learning until I can afford everything.</p> <p>Previously, I was investigating cloud computing costs as an alternative to well established cloud platforms. It was very quickly made clear to me that was not a cost efficient route by any stretch. However, I have recently discovered many actually prefer to use a VPS over a home server, as a more economic and reliable self-hosting option.</p> <p>I&#39;m in the Western United states, I&#39;d like 1TB of storage and I&#39;d like to prioritize cost, latency, and upload/download speeds, and in that order. I was first recommended Contabo. Looks like decent speeds and great cost, but the reviews look abysmal. I was then recommended Hetzner - latency may not be great as I&#39;m 

## Self-hosted alternative to mail-tester
 - [https://www.reddit.com/r/selfhosted/comments/1gwri4q/selfhosted_alternative_to_mailtester](https://www.reddit.com/r/selfhosted/comments/1gwri4q/selfhosted_alternative_to_mailtester)
 - RSS feed: $source
 - date published: 2024-11-21T21:56:30+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone!</p> <p>I found myself using mail-tester a lot recently, so I made a self-hosted alternative that can be used without limitations. Maybe you also want to use something like that service or want to know how it could work, so I released it on my Github. I was just curious about how that tool could work, and after lots of investigation and testing, I came up with this. </p> <p><a href="https://github.com/ortegavidaljl/x-ray">https://github.com/ortegavidaljl/x-ray</a></p> <p>I know by far it&#39;s not perfect and it can be improved a lot, but this is my try, and also my first Python project. I can asure you the script was x100 times uglier and scarier before I uploaded it to Github. I just wanted to share it with you all, because I also wanted to have something like this some time ago (but I couldn&#39;t find anything).</p> <p>It works as a Postfix after queue content filter. I also bundle in the repo a script called &quot;install.sh&quot;

## Guides for setting up hetzner as a tunnel for jellyfin?
 - [https://www.reddit.com/r/selfhosted/comments/1gwrhhz/guides_for_setting_up_hetzner_as_a_tunnel_for](https://www.reddit.com/r/selfhosted/comments/1gwrhhz/guides_for_setting_up_hetzner_as_a_tunnel_for)
 - RSS feed: $source
 - date published: 2024-11-21T21:55:46+00:00

<!-- SC_OFF --><div class="md"><p>Ive been getting mixed information from a lot of different sources to settle on a setup for my jellyfin server.. Based on advice from multiple people I settled on continuing to selfhost jellyfin locally, and purchase a micro VPS to act as a middleman to expose the server to my domain.</p> <p>I have a working hetzner instance running, jellyfin running, and Im just confused on how or what I should use to connect them.</p> <p>I tried using wireguard but for some reason the one on hetzner was acting up and refused to allow me to login to the web UI (It would say I successfully logged in, would refresh, and ask for a login again... It never once allowed me to access the wireguard terminal), and I couldnt find any guides on how to set this up over the command line for what I wanted to do.</p> <p>Really could use some advice here.. Should I use something other then wireguard? Can someone link a guide of sorts for attaching this to jellyfin on my end? Im jus

## Choosing a NAS for a Plex Media Server – Need Transcoding Advice for Apple Devices (3 Streams)
 - [https://www.reddit.com/r/selfhosted/comments/1gwqovh/choosing_a_nas_for_a_plex_media_server_need](https://www.reddit.com/r/selfhosted/comments/1gwqovh/choosing_a_nas_for_a_plex_media_server_need)
 - RSS feed: $source
 - date published: 2024-11-21T21:21:46+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’m a beginner in the world of NAS and media servers, and I’m looking for advice on choosing the right setup for my needs. Here’s what I’m working with:</p> <ul> <li><strong>Primary use:</strong> Setting up a Plex media server that can handle <strong>3 simultaneous streams</strong>.</li> <li><strong>Devices:</strong> The media will mostly be played on Apple devices (Apple TV, iPhones, Macs). I believe this might require transcoding in some cases, especially since the server will be at my parents’ house, and I’ll access it remotely.</li> <li><strong>Software:</strong> I plan to use the <em>ARR suite (Radarr, Sonarr, Jackett, etc.)</em> for automation, so the NAS should handle this without hiccups.</li> </ul> <p>I’ve narrowed down my options to a <strong>Synology DS423+</strong> and a <strong>DS920+</strong>, but I’m still exploring whether a <strong>mini-PC</strong> might offer better performance and value (even though it seems mor

## About to start my journey, what are some things you wish you did differently at the start?
 - [https://www.reddit.com/r/selfhosted/comments/1gwqmjm/about_to_start_my_journey_what_are_some_things](https://www.reddit.com/r/selfhosted/comments/1gwqmjm/about_to_start_my_journey_what_are_some_things)
 - RSS feed: $source
 - date published: 2024-11-21T21:19:04+00:00

<!-- SC_OFF --><div class="md"><p>Today I&#39;m picking up some parts from FB marketplace and Best Buy to put together a budget PC for my first self hosted experience. </p> <p>Any tips or advice that you wish could tell the past you? I&#39;m hoping to learn from your advice and issues you may have had when you started out. It could be OS related, container, software, or documentation of your setup. </p> <p>I&#39;m excited to do the research and learn about the various options there are out there.</p> <p>My experience so far with somewhat related software or techniques:</p> <p>I&#39;ve worked with Linux quite a bit and I&#39;d say I&#39;m comfortable, but still get confused with it. I utilized Docker Desktop on Windows to build a Splunk Enterprise, but ran into weird Sudo related issues. I have used Podman a lot for the same thing, but was actually successful in building the Enterprise. Streamio with real-debrid. Seedboxes, torrenting. Just started my journey in the last month with de

## Car repair and inventory history
 - [https://www.reddit.com/r/selfhosted/comments/1gwpblp/car_repair_and_inventory_history](https://www.reddit.com/r/selfhosted/comments/1gwpblp/car_repair_and_inventory_history)
 - RSS feed: $source
 - date published: 2024-11-21T20:24:41+00:00

<!-- SC_OFF --><div class="md"><p>Hello, </p> <p>I am seeking assistance in finding software than can allow me to help keep track of automotive repair at a used car lot.</p> <p>Basically looking for</p> <p>-Self hosted of course</p> <p>-Inventory for all the cars</p> <p>-Ability to create a work order for an inventory item</p> <p>-Ability to open an inventory item and see all work orders on that item</p> <p>Would be nice if it can have a way to put costs in as well but not needed, no invoicing functions are needed, and would like it to support allowing 3 people to be connected to it at the same time.</p> <p>I have searched the group and google trying a few like hammond and odoo, among others I have already forgotten. I am fine with a linux or windows software, prefer free if possible </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Delicious_Hornet_989"> /u/Delicious_Hornet_989 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/commen

## Need help with "docking-station" from github
 - [https://www.reddit.com/r/selfhosted/comments/1gwosge/need_help_with_dockingstation_from_github](https://www.reddit.com/r/selfhosted/comments/1gwosge/need_help_with_dockingstation_from_github)
 - RSS feed: $source
 - date published: 2024-11-21T20:03:07+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://github.com/LooLzzz/docking-station">https://github.com/LooLzzz/docking-station</a></p> <p>I think the app is great! but I&#39;m having trouble installing it. The web interface can be called up, but I only see a window with: &quot;*but nobody came. &quot; but I have 17 activ container.</p> <p>My docker compose yaml:</p> <p>```services: docking-station: image: loolzzz/docking-station restart: unless-stopped ports: - 3000:3000 volumes: - /home/dockervolumes/dockingstation/Data/config:/config - /home/dockervolumes/dockingstation/Data:/data - /home/dockervolumes/dockingstation/Data/logs:/logs - /var/run/docker.sock:/var/run/docker.sock - /etc/localtime:/etc/localtime:ro - /home/dockervolumes:/home/dockervolumes networks: {}</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Thunderace77"> /u/Thunderace77 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwosge/need_help_with_dockin

## Can someone help me with/link me a guide to set up nextcloud on debain 12 that's simple to understand and do?
 - [https://www.reddit.com/r/selfhosted/comments/1gwof28/can_someone_help_me_withlink_me_a_guide_to_set_up](https://www.reddit.com/r/selfhosted/comments/1gwof28/can_someone_help_me_withlink_me_a_guide_to_set_up)
 - RSS feed: $source
 - date published: 2024-11-21T19:48:03+00:00

<!-- SC_OFF --><div class="md"><p>Does anyone know of a simple and easy to understand way of setting up nextcloud on Debian? I tried so many tutorials last night but I got random errors all throughout that I don&#39;t have screenshots of so I want to start over. I just don&#39;t know how to do it and really need some help or a link to a simple to understand guide that doesn&#39;t take a whole day to do.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Lucky-Tower-1528"> /u/Lucky-Tower-1528 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwof28/can_someone_help_me_withlink_me_a_guide_to_set_up/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwof28/can_someone_help_me_withlink_me_a_guide_to_set_up/">[comments]</a></span>

## The Proxmox use of Corosync explained
 - [https://www.reddit.com/r/selfhosted/comments/1gwnze9/the_proxmox_use_of_corosync_explained](https://www.reddit.com/r/selfhosted/comments/1gwnze9/the_proxmox_use_of_corosync_explained)
 - RSS feed: $source
 - date published: 2024-11-21T19:29:57+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/esiy0676"> /u/esiy0676 </a> <br/> <span><a href="https://www.reddit.com/r/ProxmoxQA/comments/1gwnwys/the_proxmox_corosync_fallacy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwnze9/the_proxmox_use_of_corosync_explained/">[comments]</a></span>

## How to Export and Index My Spotify Library for Self-Hosted Streaming?
 - [https://www.reddit.com/r/selfhosted/comments/1gwmz0l/how_to_export_and_index_my_spotify_library_for](https://www.reddit.com/r/selfhosted/comments/1gwmz0l/how_to_export_and_index_my_spotify_library_for)
 - RSS feed: $source
 - date published: 2024-11-21T18:49:34+00:00

<!-- SC_OFF --><div class="md"><p>Hi there,</p> <p>I recently set up Navidrome with Lidarr on my server. Since I have all the songs I like and playlists, etc., on Spotify, is there a solution that exports all the songs and indexes them properly? Alternatively, would Lidarr be able to index my Spotify library if I just add the songs to the Lidarr library?</p> <p>A lot of the songs I listen to aren’t really on torrent index sites, so could this solution also actively sync my Spotify library to Navidrome in case I add new songs to my Spotify library?</p> <p>I haven’t really found anything that fits my needs. I might just write a small Python script to do all this for me, but I wanted to see if something like this already exists.</p> <p>Thanks in advance for your help!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rpgyumyum"> /u/rpgyumyum </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwmz0l/how_to_export_and_index_my_spot

## Selfhosted notetaking alternative Evernote
 - [https://www.reddit.com/r/selfhosted/comments/1gwmnl5/selfhosted_notetaking_alternative_evernote](https://www.reddit.com/r/selfhosted/comments/1gwmnl5/selfhosted_notetaking_alternative_evernote)
 - RSS feed: $source
 - date published: 2024-11-21T18:37:44+00:00

<!-- SC_OFF --><div class="md"><p>Hi everybody. I am from Russia. A long time I had been using Evernote for notetaking and there are more than thousand notes devided by folders (like Books, Learning, Sport and so other). But once Evernote introduced restrictions (only 2 devices in free plan), in addition from 2022 impossible to pay it (because of sanctions). So I started to use Notion; I liked it, cool note taking app, but- thank to sanctions- 2 month ago Notion doesnt let use it from Russia. And now I am thinking about self hosted note taking app. What I need: 0) free self hosted!! 1) folders/directories structure like in Evernote/Notion; left sidebar with folders and list of notes in them, right content of choosed note (maybe by using themes) 2) possility of import my notes databases/backups from Evernote and Notion 3) web interface/client absolutely necessary + mobile apps desirable but not necessary 4) I absolutely dislike idea of syncting database between all devices and so I do

## Introducing yet another immich proxy: Proxy for Immich
 - [https://www.reddit.com/r/selfhosted/comments/1gwmlal/introducing_yet_another_immich_proxy_proxy_for](https://www.reddit.com/r/selfhosted/comments/1gwmlal/introducing_yet_another_immich_proxy_proxy_for)
 - RSS feed: $source
 - date published: 2024-11-21T18:35:13+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been using Immich for not too long and really liking it. Accessing it through VPN worked fine but the need for sharing albums and photos to family and friends quickly arose. I wanted a secure enough way to expose immich publicly without exposing the whole API and also without giving up on the immich feature-full web UI.</p> <p><a href="https://github.com/tomleb/proxy-for-immich/">Proxy for Immich</a> is a proxy that you can expose to the public so you can share albums/photos to friends, etc. </p> <p>It allows a subset of the immich API to pass through (only read-only operations, only those necessary for displaying the album / photos sharing pages). It also contains a stripped-down version of immich&#39;s web UI so you get pretty much the same UI as you&#39;re used to (minus ability to upload, change description, etc, again read-only).</p> <p><strong>Features</strong></p> <ul> <li>📥 Download photos individually or whole albums</li> <li> 🚫 Upl

## Virtualization environments and K8s
 - [https://www.reddit.com/r/selfhosted/comments/1gwm3pn/virtualization_environments_and_k8s](https://www.reddit.com/r/selfhosted/comments/1gwm3pn/virtualization_environments_and_k8s)
 - RSS feed: $source
 - date published: 2024-11-21T18:15:58+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, I&#39;m building a home cluster and want to figure out a decent way of setting things up.</p> <p>At first, I installed Proxmox. Then I noticed that there&#39;s no first-party Terraform module and the main third-party one only supports a very small subset of what&#39;s available. There is better Ansible support, but I would much rather avoid that if possible for reasons that really belong in a bigger discussion in a different thread.</p> <p>Now, I&#39;m looking at Incus. It seems to accomplish many of the same things as Proxmox and it has thorough Terraform support. It doesn&#39;t have a pre-packaged ISO for installation, so now I have to choose the linux distro.</p> <p>A few years ago, it&#39;d be CentOS. Now, Fedora? I also like what I&#39;ve read about NixOS.</p> <p>Finally, I&#39;m wondering if there&#39;s even a point to including this layer in my solution since I&#39;ll be running K8s (K3s, really) anyway. Traditional wisdom has be

## Adding a file to an existing docker container from outside the container with a cron job
 - [https://www.reddit.com/r/selfhosted/comments/1gwm14v/adding_a_file_to_an_existing_docker_container](https://www.reddit.com/r/selfhosted/comments/1gwm14v/adding_a_file_to_an_existing_docker_container)
 - RSS feed: $source
 - date published: 2024-11-21T18:13:10+00:00

<!-- SC_OFF --><div class="md"><p>Docker newb here so apologies in advance. I have a ttrss server in a container and I&#39;d like to create a new file the container can access using a cron job from the docker parent. Ideally this would be a file the ttrss server can access like any other RSS feed. If I had a second server I&#39;d just host it there, but right now this is my only public server.</p> <p>There&#39;s a site whose RSS feed is blocked with a 403 forbidden error from within the container, but if I grab it with wget without entering the container it works (using a random user agent in both cases). </p> <p>Thanks in advance for any advice!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/radi0raheem"> /u/radi0raheem </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwm14v/adding_a_file_to_an_existing_docker_container/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwm14v/adding_a

## What do I need for custom URLs with my new NetBird setup? DNS server? Reverse Proxy?
 - [https://www.reddit.com/r/selfhosted/comments/1gwlagw/what_do_i_need_for_custom_urls_with_my_new](https://www.reddit.com/r/selfhosted/comments/1gwlagw/what_do_i_need_for_custom_urls_with_my_new)
 - RSS feed: $source
 - date published: 2024-11-21T17:44:38+00:00

<!-- SC_OFF --><div class="md"><p>I was previously using Cloudflare tunnels but decided to move away from it to keep my data peer-to-peer. With the old setup I had two locations and would use subdomain addresses, (with purchased public domain name), to reach my services (“frigate.location1.com”, “haos.location2.com”, etc.). This was all handled by the Cloudflare Tunnel config.</p> <p>Now with NetBird (which seems great, BTW), all my URLs are “frigate-location1.netbird.selfhosted” etc.</p> <p>What’s the best approach to continue using my purchased domain name, and get my links back to looking like they used to? I watched a video on setting a Bind DNS name server, but also see a lot talk about NGNIX/Traefik reverse proxy. Which is optimal, or something else entirely?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hoffsta"> /u/hoffsta </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwlagw/what_do_i_need_for_custom_urls_with

## What is your solution for a remote backup ?
 - [https://www.reddit.com/r/selfhosted/comments/1gwkz21/what_is_your_solution_for_a_remote_backup](https://www.reddit.com/r/selfhosted/comments/1gwkz21/what_is_your_solution_for_a_remote_backup)
 - RSS feed: $source
 - date published: 2024-11-21T17:32:40+00:00

<!-- SC_OFF --><div class="md"><p>I currently use an HDD as my primary storage drive for Immich, Seafile, and system backups. Every night, I perform a 1:1 backup of this drive to another HDD. This secondary drive is housed in a separate external casing but is still located in the same room and attached to the same system.</p> <p>A friend recently offered to host one of my drives as a remote backup in exchange for me hosting one of theirs. I’d like to automate this remote backup process to run nightly while ensuring that all files are encrypted so that no one else can access the data on these drives.</p> <p>I’m considering scripting a process to encrypt the files first and then use something like <code>rsync</code> to transfer them once I have access to the remote drive via SMB or another protocol. However, I’m unsure how efficient or practical this approach would be.</p> <p>My goal is to move away from services like iCloud and Google Drive, but I’m concerned about the risk of losing 

## Font Compare v1.4 released
 - [https://www.reddit.com/r/selfhosted/comments/1gwkusb/font_compare_v14_released](https://www.reddit.com/r/selfhosted/comments/1gwkusb/font_compare_v14_released)
 - RSS feed: $source
 - date published: 2024-11-21T17:28:12+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://github.com/markrai/fontcompare">https://github.com/markrai/fontcompare</a></p> <p>Added features: </p> <p>- Color pickers for background + fonts.<br/> - Drag &amp; Drop functionality to add fonts.<br/> - Font-size unit drop-down.<br/> - Font size range-slider added. </p> <p>I feel a little silly announcing this, as my app is fairly <em>trivial</em> (but has received <em>love</em>, nonetheless) - and a feature<br/> update, is a feature update. So, tagging this as a &quot;Release.&quot; </p> <p>Shout-out to the contributors: </p> <p><a href="https://github.com/oleole39">https://github.com/oleole39</a> (adding features)<br/> <a href="https://github.com/Itz-Agasta">https://github.com/Itz-Agasta</a> (help with Docker)</p> <p>❤️ to the <a href="/r/selfhosted">r/selfhosted</a> community!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/markraidc"> /u/markraidc </a> <br/> <span><a href="https://www.reddi

## Out of mind with Overleaf
 - [https://www.reddit.com/r/selfhosted/comments/1gwkt5t/out_of_mind_with_overleaf](https://www.reddit.com/r/selfhosted/comments/1gwkt5t/out_of_mind_with_overleaf)
 - RSS feed: $source
 - date published: 2024-11-21T17:26:26+00:00

<!-- SC_OFF --><div class="md"><p>Hi, please someone can help me with that? I&#39;m out of mind.</p> <p>I follow this guide: <a href="https://shihabkhan1.github.io/overleaf/stepbystep.html">https://shihabkhan1.github.io/overleaf/stepbystep.html</a></p> <p>I successful create the four container, but im not able to react <a href="http://localhost/launchpad">http://localhost/launchpad</a> . </p> <p>I recive this with Mongo: WARNING: MongoDB 5.0+ requires a CPU with AVX support, and your current system does not appear to have that! I also try to use Portainer, but it doesn&#39;t help</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Strong-Tune6738"> /u/Strong-Tune6738 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwkt5t/out_of_mind_with_overleaf/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwkt5t/out_of_mind_with_overleaf/">[comments]</a></span>

## Having issues with nginx proxy manager
 - [https://www.reddit.com/r/selfhosted/comments/1gwkgtu/having_issues_with_nginx_proxy_manager](https://www.reddit.com/r/selfhosted/comments/1gwkgtu/having_issues_with_nginx_proxy_manager)
 - RSS feed: $source
 - date published: 2024-11-21T17:13:11+00:00

<!-- SC_OFF --><div class="md"><p>I saw <a href="https://old.reddit.com/r/selfhosted/comments/1gvk0ju/https_on_local_network/">this post</a> on here yesterday and in it someone suggested <a href="https://www.youtube.com/watch?v=qlcVx-k-02E">this</a> YouTube video to set nginx proxy manager.</p> <p>I have tried following it and I thought I had things configured correctly, but when I go to my domain name in the browser, I just get a message saying &quot;We&#39;re having trouble finding this site&quot;</p> <p>I&#39;m completely new to this and have no idea what I&#39;ve messed up.</p> <p>My domain is set up in Cloudflare not DuckDNS like the tutorial video, so at this point I&#39;m kind of stuck on getting this to work.</p> <p>I don&#39;t even know what information to provide that would be helpful in getting this working.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/unabatedshagie"> /u/unabatedshagie </a> <br/> <span><a href="https://www.reddit.

## Advice for reliable storage setup?
 - [https://www.reddit.com/r/selfhosted/comments/1gwkb15/advice_for_reliable_storage_setup](https://www.reddit.com/r/selfhosted/comments/1gwkb15/advice_for_reliable_storage_setup)
 - RSS feed: $source
 - date published: 2024-11-21T17:07:11+00:00

<!-- SC_OFF --><div class="md"><p>Long story short I repurposed my thinkpad t495 as a home server using Ubuntu server and docker just for fun, but recently I start from scratch using Proxmox with some LXCs from the helper scripts and want to take this more seriously. </p> <p>I’m running mainly the servarr stack, jellyfin and paperless, everything using a shared mount point from the host as storage but since I’m planning moving a lot of important document to paperless I’m guessing </p> <p>what is the best way to setup my storage? I’m concerned about something failed and I lost all my data</p> <p>I don’t have budget for any fancy external NAS or something like that (I just have my thinkpad with its 512 SSD) but I have an external 1Tb drive where I could put some backups. </p> <p>Current setup</p> <ul> <li>Thinkpad T495 with ryzen 7 PRO 3700U, 16Gb of ram and 512SSD</li> <li>Proxmox 8.2.7 with default config (100Gb for local storage, 374Gb for local-lvm storage)</li> <li>one shared fold

## Webapp for Rsync
 - [https://www.reddit.com/r/selfhosted/comments/1gwjdc9/webapp_for_rsync](https://www.reddit.com/r/selfhosted/comments/1gwjdc9/webapp_for_rsync)
 - RSS feed: $source
 - date published: 2024-11-21T16:30:10+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gwjdc9/webapp_for_rsync/"> <img src="https://external-preview.redd.it/aQXGsqubssy9H_np5NCrCOa5SplxvoSuEHOu2jw1wNo.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=d12ae8e8dcb78f58609bdae7db6f6e4605051ba5" alt="Webapp for Rsync" title="Webapp for Rsync" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Is there an actual alternative of Websync? The repo i found is Archived sinced 6 years and i don‘t want to Spin up something Like this old.</p> <p>The idea is indeed pretty nice and i love the Interface and how easy it is to manage rsync jobs</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/drjay3108"> /u/drjay3108 </a> <br/> <span><a href="https://github.com/furier/websync">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwjdc9/webapp_for_rsync/">[comments]</a></span> </td></tr></table>

## Obsidian Livesync on a Pi 3B - a short foray into self-hosting.
 - [https://www.reddit.com/r/selfhosted/comments/1gwiamj/obsidian_livesync_on_a_pi_3b_a_short_foray_into](https://www.reddit.com/r/selfhosted/comments/1gwiamj/obsidian_livesync_on_a_pi_3b_a_short_foray_into)
 - RSS feed: $source
 - date published: 2024-11-21T15:18:47+00:00

<!-- SC_OFF --><div class="md"><p>[If you want just the guide bit, skip to the end.]</p> <hr/> <p>Hey all, I&#39;m a novice at self hosting anything, and wanted to share a quick detour I had for getting Livesync working. I decided to start with a simple project - get a CouchDB instance on a Pi 3B+ running Raspbian bullseye to be used for Livesync. The Pi itself was just used as a Pihole machine, so I figured it would be a good idea to make it a bit more productive. I found <a href="https://www.reddit.com/r/CouchDB/comments/7fmeod/couchdb_performance_on_raspberry_pi/dsacrpn/">this couchdb performance test</a> for the pi 3 a while back on db operations and it seemed acceptable for something that only writes a few times per minute at most. </p> <p>The primary issue was that official couchdb packages aren&#39;t available on older armhf Pi&#39;s, and I couldn&#39;t find any recently updated prebuilt packages. I then stumbled across <a href="https://hub.docker.com/r/karasevm/couchdb">a doc

## First release of Broadcastarr
 - [https://www.reddit.com/r/selfhosted/comments/1gwhup0/first_release_of_broadcastarr](https://www.reddit.com/r/selfhosted/comments/1gwhup0/first_release_of_broadcastarr)
 - RSS feed: $source
 - date published: 2024-11-21T14:42:27+00:00

<!-- SC_OFF --><div class="md"><p>Hello !</p> <p>I&#39;m happy to publish the first public release of Broadcastarr.<br/> This project aims to provide access to web broadcasts (such as sport streamings for instance) through a Jellyfin server.<br/> It provides a Discord bot to perform basic actions, indexing is also published on Discord and Matrix channels.</p> <p>JSON descriptions of the indexers are not provided on the repository, but you can ask me for the ones I have already implemented, or ask me for some help if the documentation is not clear enough.</p> <p>This project has been in development since summer 2023 and took a lot of time to get to this point.<br/> Starting from a simple script to grab url links, it now works as a full service running in background.</p> <p>Everything is available here: <a href="https://github.com/Billos/Broadcastarr">https://github.com/Billos/Broadcastarr</a></p> <p>Don&#39;t hesitate to ask questions, report bugs or suggest improvements.</p> </div><!

## Best OS for Docker server and maybe hosting some VMs
 - [https://www.reddit.com/r/selfhosted/comments/1gwhkyg/best_os_for_docker_server_and_maybe_hosting_some](https://www.reddit.com/r/selfhosted/comments/1gwhkyg/best_os_for_docker_server_and_maybe_hosting_some)
 - RSS feed: $source
 - date published: 2024-11-21T14:30:16+00:00

<!-- SC_OFF --><div class="md"><p>I just purchased a 1L PC to replace my current Docker server (Synology NAS). I mostly host all my services via Docker. But I do plan on trying out some VMs for more remote desktop type stuff not for hosting services.</p> <p>The 1L PC is a HP Elite Mini G9. I will be adding 2 SSDs for redundant OS disks. And I will be utilizing my Synology NAS for storage. So the 1L PC doesn&#39;t need crazy amounts of storage and I will not be using it like a NAS.</p> <p>Which OS should I use as the basis of the 1L PC? I like the idea of the easy nature of TrueNAS as a base OS, so I can set up shares and permissions easily. But do VMs run well under TrueNAS? Is there another OS I should consider as the basis of this mainly Docker server with some VMs?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/shadowjig"> /u/shadowjig </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwhkyg/best_os_for_docker_server_an

## Help needed for Traefik + wg-easy setup. I'm loosing my mind
 - [https://www.reddit.com/r/selfhosted/comments/1gwhiip/help_needed_for_traefik_wgeasy_setup_im_loosing](https://www.reddit.com/r/selfhosted/comments/1gwhiip/help_needed_for_traefik_wgeasy_setup_im_loosing)
 - RSS feed: $source
 - date published: 2024-11-21T14:27:08+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gwhiip/help_needed_for_traefik_wgeasy_setup_im_loosing/"> <img src="https://b.thumbs.redditmedia.com/kTXSFAZ1MTyDVN_KDKm_awJGRmD4lpphr6uWemagplQ.jpg" alt="Help needed for Traefik + wg-easy setup. I'm loosing my mind" title="Help needed for Traefik + wg-easy setup. I'm loosing my mind" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I some self hosted services running in docker containers. They are all on the same server (with static ip).</p> <p>I was able to configure Traefik (also in a container with Docker Compose) as a reverse proxy with a self-signed certificate in my local network. This was surprisingly easy to do.</p> <p>Now I want to expose these self hosted services to the internet so I can access them everywhere, but only via a VPN tunnel (WG Easy). What I have done so far:</p> <ul> <li>Configured my router to forward ports 80, 443 and 51820</li> <li>Changed the DNS A record of my domain to point to 

## Transcoding ARC vs Tesla P4
 - [https://www.reddit.com/r/selfhosted/comments/1gwhh1r/transcoding_arc_vs_tesla_p4](https://www.reddit.com/r/selfhosted/comments/1gwhh1r/transcoding_arc_vs_tesla_p4)
 - RSS feed: $source
 - date published: 2024-11-21T14:25:10+00:00

<!-- SC_OFF --><div class="md"><p>Is it time for me to move on from my Tesla P4, everyone seems to be getting arc cards?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Squanchy2112"> /u/Squanchy2112 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwhh1r/transcoding_arc_vs_tesla_p4/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwhh1r/transcoding_arc_vs_tesla_p4/">[comments]</a></span>

## Any way to get a digest for academic papers ?
 - [https://www.reddit.com/r/selfhosted/comments/1gwh6yt/any_way_to_get_a_digest_for_academic_papers](https://www.reddit.com/r/selfhosted/comments/1gwh6yt/any_way_to_get_a_digest_for_academic_papers)
 - RSS feed: $source
 - date published: 2024-11-21T14:12:13+00:00

<!-- SC_OFF --><div class="md"><p>Hello all,</p> <p>I&#39;ve recently set up alerts on google scholar for new papers coming out. Google scholar only works for one search engine (google scholar), can only notify you by email, and the emails they send aren&#39;t that informative etc etc. I can&#39;t help but think there must be better self hosted solutions. No luck finding one so far though, do you know of any ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Gueleric"> /u/Gueleric </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwh6yt/any_way_to_get_a_digest_for_academic_papers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwh6yt/any_way_to_get_a_digest_for_academic_papers/">[comments]</a></span>

## Leantime 3.3 released! Open Source Project Management for Non-Project Managers
 - [https://www.reddit.com/r/selfhosted/comments/1gwgx49/leantime_33_released_open_source_project](https://www.reddit.com/r/selfhosted/comments/1gwgx49/leantime_33_released_open_source_project)
 - RSS feed: $source
 - date published: 2024-11-21T13:59:55+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gwgx49/leantime_33_released_open_source_project/"> <img src="https://external-preview.redd.it/Cj9k1bF-X-mrboWCEtyJCzc5xT1k-uQ-Hec3RiTBdqE.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=e85c184f61bb1a76bc5d0f460b7c8afbe33f224a" alt="Leantime 3.3 released! Open Source Project Management for Non-Project Managers" title="Leantime 3.3 released! Open Source Project Management for Non-Project Managers" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/intheleantime"> /u/intheleantime </a> <br/> <span><a href="https://github.com/Leantime/leantime">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwgx49/leantime_33_released_open_source_project/">[comments]</a></span> </td></tr></table>

## Has anyone used Innernet to connect to their server to a dedicated client?
 - [https://www.reddit.com/r/selfhosted/comments/1gwgwft/has_anyone_used_innernet_to_connect_to_their](https://www.reddit.com/r/selfhosted/comments/1gwgwft/has_anyone_used_innernet_to_connect_to_their)
 - RSS feed: $source
 - date published: 2024-11-21T13:58:58+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to turn a laptop into portable access for my server with remote desktop, both with rocky linux. Nordvpn meshnet works but there&#39;s more latency than expected so it&#39;s probably taking an inefficient route. I&#39;m trying Headscale and Innernet but I&#39;m having issues getting Innernet to pair correctly. Has anyone used Innernet to know if it&#39;s good?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/probablyblocked"> /u/probablyblocked </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwgwft/has_anyone_used_innernet_to_connect_to_their/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwgwft/has_anyone_used_innernet_to_connect_to_their/">[comments]</a></span>

## How do y‘all deploy your services ?
 - [https://www.reddit.com/r/selfhosted/comments/1gwg3p8/how_do_yall_deploy_your_services](https://www.reddit.com/r/selfhosted/comments/1gwg3p8/how_do_yall_deploy_your_services)
 - RSS feed: $source
 - date published: 2024-11-21T13:20:39+00:00

<!-- SC_OFF --><div class="md"><p>For something like 20+ services, are you already using something like k3s? Docker-compose? Portainer ? proxmox vms? What is the reasoning behind it ? Cheers! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pepelele91"> /u/pepelele91 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwg3p8/how_do_yall_deploy_your_services/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwg3p8/how_do_yall_deploy_your_services/">[comments]</a></span>

## Self-Hosting Guide to Alternatives: Pocket, Omnivore (Bookmark / Read Later)
 - [https://www.reddit.com/r/selfhosted/comments/1gwfn9b/selfhosting_guide_to_alternatives_pocket_omnivore](https://www.reddit.com/r/selfhosted/comments/1gwfn9b/selfhosting_guide_to_alternatives_pocket_omnivore)
 - RSS feed: $source
 - date published: 2024-11-21T12:57:22+00:00

<!-- SC_OFF --><div class="md"><p>Hey, <a href="/r/selfhosted">r/selfhosted</a>! In light of the <a href="https://blog.omnivore.app/p/omnivore-is-joining-elevenlabs">recent Omnivore news</a>, it felt like an appropriate time to post a brief overview of the fantastic landscape of self-hosted bookmark and read later applications. </p> <p>As usual, I&#39;d recommending exploring every option on the list and finding the one that is best suited to your needs. Feel free to reach out with feedback or if I missed anything!</p> <hr/> <p><a href="https://selfh.st/alternatives/read-later/">Self-Hosting Guide to Alternatives - Pocket, Omnivore (selfh.st)</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/shol-ly"> /u/shol-ly </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwfn9b/selfhosting_guide_to_alternatives_pocket_omnivore/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwfn9b/selfhosting_

## Proxmox: be warned if a zfs pool is degraded
 - [https://www.reddit.com/r/selfhosted/comments/1gwfhqi/proxmox_be_warned_if_a_zfs_pool_is_degraded](https://www.reddit.com/r/selfhosted/comments/1gwfhqi/proxmox_be_warned_if_a_zfs_pool_is_degraded)
 - RSS feed: $source
 - date published: 2024-11-21T12:49:03+00:00

<!-- SC_OFF --><div class="md"><p>How are you triggered when a zfs pool is degraded ? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/carmelo42"> /u/carmelo42 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwfhqi/proxmox_be_warned_if_a_zfs_pool_is_degraded/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwfhqi/proxmox_be_warned_if_a_zfs_pool_is_degraded/">[comments]</a></span>

## HAProxy not forwarding the real IP
 - [https://www.reddit.com/r/selfhosted/comments/1gwenc4/haproxy_not_forwarding_the_real_ip](https://www.reddit.com/r/selfhosted/comments/1gwenc4/haproxy_not_forwarding_the_real_ip)
 - RSS feed: $source
 - date published: 2024-11-21T12:02:23+00:00

<!-- SC_OFF --><div class="md"><p>I was configuring HAProxy and got it working. The issue that I have is the backend servers see the client IP as the IP of the HAProxy server instead of the clients&#39; addresses.</p> <p>On both frontend and backend, I have the <code>option forwardfor</code>, <code>http-request set-header X-Forwarded-For %[src]</code>.</p> <p>According to the documentation, those options should be enough to forward the real IP, but it doesn&#39;t behaving as intended. </p> <p>My HAProxy version is 1.8.27 on Rocky Linux.</p> <p>Any ideas that I could try?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/KaleidoscopeNo9726"> /u/KaleidoscopeNo9726 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwenc4/haproxy_not_forwarding_the_real_ip/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwenc4/haproxy_not_forwarding_the_real_ip/">[comments]</a></span>

## Seeking guidance on properly exposing home server services
 - [https://www.reddit.com/r/selfhosted/comments/1gweii7/seeking_guidance_on_properly_exposing_home_server](https://www.reddit.com/r/selfhosted/comments/1gweii7/seeking_guidance_on_properly_exposing_home_server)
 - RSS feed: $source
 - date published: 2024-11-21T11:55:09+00:00

<!-- SC_OFF --><div class="md"><p>Hi there, last week I got a Beelink which I intend to use as a home server. Now, I&#39;m a novice at networking and still can&#39;t wrap my head around some things. I bought a domain from CloudFlare and I also set up Traefik to renew certs. I also want to setup Adguard Home on the same device (I managed to get this running by itself, but not with Traefik). My router is capable to point the DNS to this device where Adguard would run. </p> <p>Now, my question is how to properly config Traefik/Adguard so that (on my home network) I can access:<br/> - adguard homepage at something like adguard.&lt;domain&gt;</p> <p>- traefik homepage at traefik.&lt;domain&gt;</p> <p>- any future service I might run (media server with Jellyfin or a MC server for example)</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Balssh"> /u/Balssh </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1

## DIY NAS biuld
 - [https://www.reddit.com/r/selfhosted/comments/1gwe94j/diy_nas_biuld](https://www.reddit.com/r/selfhosted/comments/1gwe94j/diy_nas_biuld)
 - RSS feed: $source
 - date published: 2024-11-21T11:38:46+00:00

<!-- SC_OFF --><div class="md"><p>Good day everyone, I am new here so forgive me any flaws of that discussion. I decided to post here sinc my close friend showed me this place which I am thankfull to him. That it when it comes to a wor of inteoduction.</p> <p>Going straight to the point I started to think about my own home sort of nas device, sort of because beside using it as a home cloud storage I planned to use it as a part of a home surveillance system, somewhere here I saw a screenshot with a pihole installed which interest me too, video streaming probably and in the end may be it would be used a little for virtualization. </p> <p>I use widely known motto, pay onece cry once. That is why I picked parts listed below. Well, not only because of that but I found myself at different forums etc. where those have been mentioned and I found them suitable for my build BUT as always, I could be wrong couldn&#39;t I? X) and here I wanted to ask you for your thoughts about this build. Thank

## What serviccess are ok to host only through wifi?
 - [https://www.reddit.com/r/selfhosted/comments/1gwclj6/what_serviccess_are_ok_to_host_only_through_wifi](https://www.reddit.com/r/selfhosted/comments/1gwclj6/what_serviccess_are_ok_to_host_only_through_wifi)
 - RSS feed: $source
 - date published: 2024-11-21T09:44:20+00:00

<!-- SC_OFF --><div class="md"><p>Before you start hating me wait. I have some UMAX laptop with Intel Pentium G4400 3.3GHz 4 Gb RAM and 64 Gb of ssd storage and I&#39;d like to use it for something, it is currently running ubuntu server and I don&#39;t know how could I utilize something that I cannot plug into the network by cable (it literarlly doesn&#39;t have ethernet port)</p> <p>Any recommendations what to do with this piece of hardware? </p> <p>I&#39;d like to use it in my homelab (Now one desktop and one laptop both with proxmox installed) somehow, it sits in my closet for more than a year and I have no other use for it now, maybe I&#39;d use it just as client for media streaming (with non wifi TV) but this can be done using raspberry or I could just plug hdmi in my daily drive laptop, that I use for school note taking mainly and sometimes for development.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gun3kter_cz"> /u/gun3kter_cz </a> <

## Looking for a Lightweight Self-Hosted Automatic YouTube Downloader – TubeSync Feels Bloated
 - [https://www.reddit.com/r/selfhosted/comments/1gwcikw/looking_for_a_lightweight_selfhosted_automatic](https://www.reddit.com/r/selfhosted/comments/1gwcikw/looking_for_a_lightweight_selfhosted_automatic)
 - RSS feed: $source
 - date published: 2024-11-21T09:38:06+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a specific self-hosted service or application that allows me to manage a list of YouTube channels with individual configurations. The ideal tool should:</p> <ul> <li>Poll YT API or listen to the RSS feeds of the specified YouTube channels.</li> <li>Automatically download new videos as soon as they&#39;re released to a predefined folder.</li> <li>Save metadata (thumbnails, descriptions, etc.) so I can view them in Jellyfin.</li> <li>Have a minimalistic UI, or even no UI at all, I&#39;m comfortable modifying config files manually.</li> </ul> <p>I tried TubeSync but really didn&#39;t like it at all. Building a custom solution sounds like a fun weekend project, but before I dive in, I wanted to check if there are any existing self-hosted services apart from TubeSync that can accomplish this.</p> <p>Does anyone know of a tool that fits these requirements?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com

## New to SelfHosting
 - [https://www.reddit.com/r/selfhosted/comments/1gwbzpd/new_to_selfhosting](https://www.reddit.com/r/selfhosted/comments/1gwbzpd/new_to_selfhosting)
 - RSS feed: $source
 - date published: 2024-11-21T08:58:39+00:00

<!-- SC_OFF --><div class="md"><p>I am a newbie to self hosting and with only having my NAS for a few days I am looking at different ways to use it. What are some must have self hosted apps? What are some fun ones you have found? Or even some noob friendly ones that will help me learn more about self hosting? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Disastrous-Donut5540"> /u/Disastrous-Donut5540 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwbzpd/new_to_selfhosting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwbzpd/new_to_selfhosting/">[comments]</a></span>

## Can lightweight LLM runs in low end environment?
 - [https://www.reddit.com/r/selfhosted/comments/1gwbyjw/can_lightweight_llm_runs_in_low_end_environment](https://www.reddit.com/r/selfhosted/comments/1gwbyjw/can_lightweight_llm_runs_in_low_end_environment)
 - RSS feed: $source
 - date published: 2024-11-21T08:56:23+00:00

<!-- SC_OFF --><div class="md"><p>Just thought I would ask this before I try it out because it&#39;s going to be a lot of work because I&#39;m not familiar with python. </p> <p>Can lightweight LLM like Phi-3.5-mini-instruct in huggingface or other very run in low spec environment e.g 1GB ram, 1 core cpu and no GPU? Or is there anything that can run in absolute minimum environment like that?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Chillseashells"> /u/Chillseashells </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwbyjw/can_lightweight_llm_runs_in_low_end_environment/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwbyjw/can_lightweight_llm_runs_in_low_end_environment/">[comments]</a></span>

## Which disk to pick for diy server (cctv + nas)
 - [https://www.reddit.com/r/selfhosted/comments/1gwbr0n/which_disk_to_pick_for_diy_server_cctv_nas](https://www.reddit.com/r/selfhosted/comments/1gwbr0n/which_disk_to_pick_for_diy_server_cctv_nas)
 - RSS feed: $source
 - date published: 2024-11-21T08:40:09+00:00

<!-- SC_OFF --><div class="md"><p>Hi</p> <p>I have a n100 &#39;nas&#39; with 2x3.5 hdd slots.</p> <p>I want to use it for cctv (need 2-4tb for that, 4 cameras) and nas (plex + maybe next cloud).</p> <p>I don&#39;t need backup - if I loose cctv data, it is ok, plex data also, and next cloud I will backup to onedrive.</p> <p>I am wondering if I should pick skyhawk/wd purple for cctv, and ironwolf/wd red for nas-like purposes, or would it be better to just buy 6-8TB skyhawk and use it for both purposes to have room for upgrade in the future?</p> <p>What would you pick and why?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Piocze"> /u/Piocze </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwbr0n/which_disk_to_pick_for_diy_server_cctv_nas/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwbr0n/which_disk_to_pick_for_diy_server_cctv_nas/">[comments]</a></span>

## ToDo app selfhosted with (push)notifications
 - [https://www.reddit.com/r/selfhosted/comments/1gwbdsm/todo_app_selfhosted_with_pushnotifications](https://www.reddit.com/r/selfhosted/comments/1gwbdsm/todo_app_selfhosted_with_pushnotifications)
 - RSS feed: $source
 - date published: 2024-11-21T08:11:56+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, </p> <p>I have been searching a bit for a kind of a todo app with the support for notifications to orginaize my Family.<br/> Currently I am running <strong>vikunja,</strong> which is really great but does not support push notification.... and deadlines get missed.</p> <p>I assume from posts I read that cal.dav would be potentially the better option for my purpose and to run this as calender and intergrate it for example with google etc. to get notofications there... but well I am happy for any Input or idea on this . </p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/macjex"> /u/macjex </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwbdsm/todo_app_selfhosted_with_pushnotifications/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwbdsm/todo_app_selfhosted_with_pushnotifications/">[comments]</a></span>

## Secure Docker-WebApp with Coolify
 - [https://www.reddit.com/r/selfhosted/comments/1gwbdqu/secure_dockerwebapp_with_coolify](https://www.reddit.com/r/selfhosted/comments/1gwbdqu/secure_dockerwebapp_with_coolify)
 - RSS feed: $source
 - date published: 2024-11-21T08:11:51+00:00

<!-- SC_OFF --><div class="md"><p>Hi, is there any easy way to secure my dockerized WebApp in coolify with a https login formular?</p> <p>Ive seen that it´s possible to use Authentik with the internal Treafik proxy manager, but is there something easier or a good manual for my requirements?</p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Domep"> /u/Domep </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwbdqu/secure_dockerwebapp_with_coolify/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gwbdqu/secure_dockerwebapp_with_coolify/">[comments]</a></span>

## Help! Grafana Synthetic Monitoring Plugin cannot find datasources
 - [https://www.reddit.com/r/selfhosted/comments/1gwb1cg/help_grafana_synthetic_monitoring_plugin_cannot](https://www.reddit.com/r/selfhosted/comments/1gwb1cg/help_grafana_synthetic_monitoring_plugin_cannot)
 - RSS feed: $source
 - date published: 2024-11-21T07:46:28+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gwb1cg/help_grafana_synthetic_monitoring_plugin_cannot/"> <img src="https://b.thumbs.redditmedia.com/Y-aaCMEQuFIg_3Wqo7RgaU6FWk3oJ6Wh2S4hHxEQl7k.jpg" alt="Help! Grafana Synthetic Monitoring Plugin cannot find datasources" title="Help! Grafana Synthetic Monitoring Plugin cannot find datasources" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/4smnk502m72e1.png?width=1463&amp;format=png&amp;auto=webp&amp;s=ef1261aa3d6399cad16c0c828af527adb657f7f3">https://preview.redd.it/4smnk502m72e1.png?width=1463&amp;format=png&amp;auto=webp&amp;s=ef1261aa3d6399cad16c0c828af527adb657f7f3</a></p> <p><a href="https://preview.redd.it/eb5mj1t2m72e1.png?width=757&amp;format=png&amp;auto=webp&amp;s=27921bc2fd16a6a835aaca7c2ce14ae42871770e">https://preview.redd.it/eb5mj1t2m72e1.png?width=757&amp;format=png&amp;auto=webp&amp;s=27921bc2fd16a6a835aaca7c2ce14ae42871770e</a></p> <p><a href="https://previ

## The Ultimate Dashboard ?
 - [https://www.reddit.com/r/selfhosted/comments/1gwas7w/the_ultimate_dashboard](https://www.reddit.com/r/selfhosted/comments/1gwas7w/the_ultimate_dashboard)
 - RSS feed: $source
 - date published: 2024-11-21T07:27:31+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gwas7w/the_ultimate_dashboard/"> <img src="https://preview.redd.it/xu4b0d2si72e1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=e566d4ba53d2a070afd097246d79c25ad14d76af" alt="The Ultimate Dashboard ?" title="The Ultimate Dashboard ?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I came across the video online where they showed live dashboard where it showed all push/pull on GitHub in their HQ building. </p> <p>Has anyone tried such a thing ? This could show local / external traffic of our server and it looks super cool. Check the link below for video </p> <p><a href="https://x.com/calder_white/status/1811203592067662192">https://x.com/calder_white/status/1811203592067662192</a></p> <p><a href="https://x.com/ChiefScientist/status/1747511724977344979">https://x.com/ChiefScientist/status/1747511724977344979</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/KnowledgeH

## Selfhosting email with SMTP relay, advices?
 - [https://www.reddit.com/r/selfhosted/comments/1gw9yz7/selfhosting_email_with_smtp_relay_advices](https://www.reddit.com/r/selfhosted/comments/1gw9yz7/selfhosting_email_with_smtp_relay_advices)
 - RSS feed: $source
 - date published: 2024-11-21T06:32:29+00:00

<!-- SC_OFF --><div class="md"><p>I understand the complexity of having a functional email is hard and many people often advice against self hosting this part, but still I want to give it a try before giving up.</p> <p>The main motive is to get rid of google as much as possible, regain control of my privacy and my data as much as possible.</p> <p>I rarely send out email at all, I&#39;d say less than 100 a month, I&#39;m not using email for business communication anyway, it&#39;s mostly for receiving account info, receipts, etc. And I surely don&#39;t send any sketchy email as well, if anytime I need to send email it&#39;s mostly to inquiry about some stuff.</p> <p>So with that usage I&#39;m thinking I could get by of using SMTP relay to handle the email sending, and handle the incoming email on my own, so probably just a cheap vps running mailcow or mail-in-a-box then use a cheap relay like amazon ses.</p> <p>Is this a workable idea or am I missing out something?</p> </div><!-- SC_ON

## NextCloud on Ubuntu server
 - [https://www.reddit.com/r/selfhosted/comments/1gw9jex/nextcloud_on_ubuntu_server](https://www.reddit.com/r/selfhosted/comments/1gw9jex/nextcloud_on_ubuntu_server)
 - RSS feed: $source
 - date published: 2024-11-21T06:04:22+00:00

<!-- SC_OFF --><div class="md"><p>I had a old spare laptop where I installed Ubuntu and NextCloud.</p> <p>NextCloud installation is successful and I can run it locally on server. Problem is in accessing it via internet (WAN)</p> <p>I have squarespace domain already and I was planning to create subdomain for nextcloud. But I do not know how to proceed. I tried following setup:</p> <ol> <li><p>Add DNS record in squarespace (route subdomain to my public IP address)</p></li> <li><p>Enable port forwarding in my router setting (Origin port 80, Destination: Port 443 on Server IP)</p></li> <li><p>manually add certificate using _acme-challenge (Let&#39;s encrypt) and it was successful.</p></li> </ol> <p>After this, when I put URL from my local PC (under LAN), URL redirects me to residential gateway and when URL is tried from WAN, it says unable to reach server. Can you help setting it up? Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/WorldSu

## SearXNG hosted on raspi, need help setting it up
 - [https://www.reddit.com/r/selfhosted/comments/1gw8eus/searxng_hosted_on_raspi_need_help_setting_it_up](https://www.reddit.com/r/selfhosted/comments/1gw8eus/searxng_hosted_on_raspi_need_help_setting_it_up)
 - RSS feed: $source
 - date published: 2024-11-21T04:57:06+00:00

<!-- SC_OFF --><div class="md"><p>so im trying to host SearXNG on a raspberry pi i have running on my local network, i am exttremely new to linux and networking in general, so if you need anything, ask. I used the tutorial at <a href="https://dmpop.xyz/article.php?id=2024-10-10_searxng-self-hosted-instance">dmpop.xyz</a>, that is pretty much all i did, i also used an IP address rather than a url, but im not sure weather that will affect anything. If you need any other information, just ask</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bobasah"> /u/bobasah </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gw8eus/searxng_hosted_on_raspi_need_help_setting_it_up/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gw8eus/searxng_hosted_on_raspi_need_help_setting_it_up/">[comments]</a></span>

## can someone point me to a tutorial to setup postfix/dovecot with SMTP auth and virtual mailboxes?
 - [https://www.reddit.com/r/selfhosted/comments/1gw8e9d/can_someone_point_me_to_a_tutorial_to_setup](https://www.reddit.com/r/selfhosted/comments/1gw8e9d/can_someone_point_me_to_a_tutorial_to_setup)
 - RSS feed: $source
 - date published: 2024-11-21T04:56:09+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m having a hell of a hard time trying to get a basic mail server to work,the syntax of config files has greatly changed since the last time I did it and it&#39;s just being a royal pain. none of the tutorials I&#39;ve found, and even chatgpt has helped. I&#39;m on Devuan 5. </p> <p>All I want is to be able to setup virtual mailboxes, and also use SMTP authentication so that I don&#39;t need to keep whitelisting my home IP in order to send mail, I just want it to require authentication, and of course open relay being off, except for authenticated users, and I want it to use the same credentials as the pop access. </p> <p>I also want all of this to be encrypted so that passwords are never sent in clear text. </p> <p>Ideally I&#39;d also like to be able to use letsencrypt certs but it seems postfix/dovecot want .pem files and I get .cer files from letsencrypt so worse case scenario self signed is fine as it&#39;s only me using it anyway unless the

## Help configuring reverse proxy for local access
 - [https://www.reddit.com/r/selfhosted/comments/1gw89sg/help_configuring_reverse_proxy_for_local_access](https://www.reddit.com/r/selfhosted/comments/1gw89sg/help_configuring_reverse_proxy_for_local_access)
 - RSS feed: $source
 - date published: 2024-11-21T04:48:51+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to set up a reverse proxy on my internal network to simplify naming configuration for clients. Right now what I have looks like:</p> <p><a href="http://server1.example.com:443">server1.example.com:443</a> = server (TrueNas Scale) management interface</p> <p><a href="http://server1.example.com:1234">server1.example.com:1234</a> = a service in docker on server 1</p> <p><a href="http://server1.example.com:5678">server1.example.com:5678</a> = another service in docker on server 1</p> <p>....</p> <p><a href="http://frigate.example.com:5000">frigate.example.com:5000</a> = frigate service running on docker</p> <p><a href="http://frigate.example.com:9443">frigate.example.com:9443</a> = portainer</p> <p><a href="http://proxmox1.example.com:8006">proxmox1.example.com:8006</a> = proxmox management interface</p> <p><a href="http://router.example.com:443">router.example.com:443</a> = opnsense service on proxmox1 (lxc or vm)</p> <p><a href="http://f

## Guide: How to hide the nagging banners - Gitlab Edition
 - [https://www.reddit.com/r/selfhosted/comments/1gw7uz6/guide_how_to_hide_the_nagging_banners_gitlab](https://www.reddit.com/r/selfhosted/comments/1gw7uz6/guide_how_to_hide_the_nagging_banners_gitlab)
 - RSS feed: $source
 - date published: 2024-11-21T04:25:44+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gw7uz6/guide_how_to_hide_the_nagging_banners_gitlab/"> <img src="https://b.thumbs.redditmedia.com/tKwQVDO1f7lhxSuKSvmiDyPsdI5s4n2JTyraJT86dqM.jpg" alt="Guide: How to hide the nagging banners - Gitlab Edition" title="Guide: How to hide the nagging banners - Gitlab Edition" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>This is broken down into 2 parts. How I go about identifying what needs to be hidden, and how to actually hide them. I&#39;ll use Gitlab as an example.</p> <p>At the time, I chose the Enterprise version instead of Community (serves me right) thinking I <em>might</em> want some premium feature way ahead in the future and I don&#39;t want potential migration headaches, but because it kept annoying me again and again to start a trial of the Ultimate version, I decided not to.</p> <p>If you go into your repository settings, you will see a banner like this:</p> <p><a href="https://preview.redd.it/os

## Stalwart
 - [https://www.reddit.com/r/selfhosted/comments/1gw7p1j/stalwart](https://www.reddit.com/r/selfhosted/comments/1gw7p1j/stalwart)
 - RSS feed: $source
 - date published: 2024-11-21T04:16:37+00:00

<!-- SC_OFF --><div class="md"><p>I’m looking for detailed step by step instructions on installing &amp; setting up Stalwart as I can’t seem to get it right. BONUS would be a YouTube video… </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Redacted911"> /u/Redacted911 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gw7p1j/stalwart/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gw7p1j/stalwart/">[comments]</a></span>

## Let's Encrypt SSL Certificates Guide
 - [https://www.reddit.com/r/selfhosted/comments/1gw6vx9/lets_encrypt_ssl_certificates_guide](https://www.reddit.com/r/selfhosted/comments/1gw6vx9/lets_encrypt_ssl_certificates_guide)
 - RSS feed: $source
 - date published: 2024-11-21T03:33:40+00:00

<!-- SC_OFF --><div class="md"><p>There was a recent post asking for guidance on this topic and I wanted to share my experience, so that it might help those who are lost on this topic.</p> <p>If you are self-hosting an application, such as <a href="https://github.com/AdguardTeam/AdGuardHome">AdGuard Home</a>, then you will undoubtedly find yourself encountering a browser warning about the application being unsafe and requiring you to bypass the warning before continuing. This is particularly noticeable when you want to access your application via HTTPS instead of HTTP. The point is that any application with access to traffic on your LAN&#39;s subnet will be able to access unencrypted traffic. To avoid this issue and secure your self-hosted application, you ultimately want a trusted certificate being presented to your browser when navigating to the application.</p> <ul> <li>Purchase a domain name - I use <a href="https://www.namecheap.com">Namecheap</a>, but any registrar should be fi

## A Git based Notes app for Android with Markdown support and more! - It's also FOSS (fr this time)
 - [https://www.reddit.com/r/selfhosted/comments/1gw6k9e/a_git_based_notes_app_for_android_with_markdown](https://www.reddit.com/r/selfhosted/comments/1gw6k9e/a_git_based_notes_app_for_android_with_markdown)
 - RSS feed: $source
 - date published: 2024-11-21T03:17:00+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone!</p> <p><strong>CALL FOR CONTRIBUTORS</strong></p> <p>I have been working on a Markdown based, git synced notes app for android. Skipping any bs, here are the features that u can explore rn (albeit without polish):</p> <ul> <li><p>Git based syncing (clone over https, pull, add (staging and unstaging), commit and push implemented)</p></li> <li><p>Allowing storage of repositories on external storage (fr this time)</p></li> <li><p>Markdown rendering supported, opening files in other apps supported using intent framework</p></li> <li><p>Multiple repos supported by default</p></li> <li><p>MIT license, no hidden subscription/donations... its FOSS (fr this time).</p></li> </ul> <p>Here&#39;s what I have planned for the near future (if there is demand):</p> <ul> <li><p>Customizing the way markdown looks and feels, from font to its color, size, weight, style, etc.</p></li> <li><p>A polished ui with pretty animations.</p></li> <li><p>Support for

## Invidious on LG WebOS?
 - [https://www.reddit.com/r/selfhosted/comments/1gw6772/invidious_on_lg_webos](https://www.reddit.com/r/selfhosted/comments/1gw6772/invidious_on_lg_webos)
 - RSS feed: $source
 - date published: 2024-11-21T02:58:42+00:00

<!-- SC_OFF --><div class="md"><p>Title says it all; is there any app or the like which allows you to use invidious (or similar) on LG WebOS? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CaptianCrypto"> /u/CaptianCrypto </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gw6772/invidious_on_lg_webos/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gw6772/invidious_on_lg_webos/">[comments]</a></span>

## Best GPU for jellyfin
 - [https://www.reddit.com/r/selfhosted/comments/1gw676e/best_gpu_for_jellyfin](https://www.reddit.com/r/selfhosted/comments/1gw676e/best_gpu_for_jellyfin)
 - RSS feed: $source
 - date published: 2024-11-21T02:58:41+00:00

<!-- SC_OFF --><div class="md"><p>long story short I have a NAS that acts as a torrent server (z97mobo based) and another networked device that has a strong GPU that I use as a proxmox compute server/stuff</p> <p>but I feel like idling a 3090 is overkill</p> <p>is there any sub 100$ GPU that you can recommend that can do 4K-h.264/h265 streaming for 2-4 clients and is power efficient?</p> <p>also is it a good idea to have that jellyfin server on a i3-4130 if the GPU does the heavy lifting and there is already a Zpool and an nginx attached to it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/randoomkiller"> /u/randoomkiller </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gw676e/best_gpu_for_jellyfin/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gw676e/best_gpu_for_jellyfin/">[comments]</a></span>

## Why your non-HA Proxmox node might reboot anyways with no warning and how to prevent it
 - [https://www.reddit.com/r/selfhosted/comments/1gw5ipw/why_your_nonha_proxmox_node_might_reboot_anyways](https://www.reddit.com/r/selfhosted/comments/1gw5ipw/why_your_nonha_proxmox_node_might_reboot_anyways)
 - RSS feed: $source
 - date published: 2024-11-21T02:25:07+00:00

<!-- SC_OFF --><div class="md"><p>NOTE: This post was auto-removed from <a href="/r/Proxmox">r/Proxmox</a>. All CLI examples tested with PVE 8.2.</p> <p>The original title of this post is inspired by the very statement of &quot;[watchdogs] are like a loaded gun&quot; from <a href="https://pve.proxmox.com/wiki/High_Availability">Proxmox wiki</a>. Proxmox include one such tool on every single node anyway. There&#39;s further misinformation, including on official forums, when watchdogs are &quot;disarmed&quot; and it is thus impossible to e.g. isolate genuine non-software related reboots. Active bugs in HA stack might get your node auto-reboot with no indication in the GUI. The CLI part is undocumented as is reliably disabling HA - which is the topic here.</p> <p>Also available as <a href="https://gist.github.com/free-pmx/a67fc0b09f5fa5ddb14f0576c5b72d2b">GH gist</a>.</p> <hr/> <h1>The Proxmox time bomb - always ticking</h1> <p>Auto-reboots are often associated with <em>High Availabilit

## Ideas on unifying files and notes
 - [https://www.reddit.com/r/selfhosted/comments/1gw5fau/ideas_on_unifying_files_and_notes](https://www.reddit.com/r/selfhosted/comments/1gw5fau/ideas_on_unifying_files_and_notes)
 - RSS feed: $source
 - date published: 2024-11-21T02:20:37+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I’m self-hosting all my files (e.g., PDFs, screenshots) on Nextcloud (NC) and using Joplin for managing notes. I’ve noticed it’s more convenient to maintain a consistent structure between NC’s folders and Joplin’s notebooks.</p> <p>For example, let’s say I have a folder in NC like &quot;Financial/Tax/2024&quot; (where &quot;Tax&quot; is a subfolder of &quot;Financial&quot;, and &quot;2024&quot; is a subfolder of &quot;Tax&quot;) to store tax-related files for 2024 (e.g. W2s, 1099s, etc). To mirror this, I’ll create a &quot;Financial&quot; notebook in Joplin, with a &quot;Tax&quot; sub-notebook that contains a &quot;2024&quot; note for tracking related details or filing information.</p> <p>However, keeping these structures aligned between NC and Joplin is cumbersome. Ideally, there would be a single tool to handle both files and notes seamlessly. But here’s where I run into issues:</p> <ol> <li>Using Joplin for everything: <ul> <li>While Jo

## Name server vs IP address
 - [https://www.reddit.com/r/selfhosted/comments/1gw55ff/name_server_vs_ip_address](https://www.reddit.com/r/selfhosted/comments/1gw55ff/name_server_vs_ip_address)
 - RSS feed: $source
 - date published: 2024-11-21T02:07:28+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gw55ff/name_server_vs_ip_address/"> <img src="https://preview.redd.it/nsa5pueox52e1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=a2b4c6cdde02470d06add03c7ae7a53de6e275ae" alt="Name server vs IP address " title="Name server vs IP address " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I feel daft asking this because I did it all years back and I used to be a networks administrator.</p> <p>Form is from .co.za registrar...</p> <p>If I&#39;m hosting from home with a fixed IP, do I set my primnsfqdn to my home IP? Or would that be the domain name and the IP goes into primnsip? Or both just my IP?</p> <p>So, essentially, .co.za will be the nameserver pointing to my home IP and thats all.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Glum-Membership-9517"> /u/Glum-Membership-9517 </a> <br/> <span><a href="https://i.redd.it/nsa5pueox52e1.png">[link]</a></span> &#32; <spa

## Trying to reduce my self hosted overhead I created
 - [https://www.reddit.com/r/selfhosted/comments/1gw4sw4/trying_to_reduce_my_self_hosted_overhead_i_created](https://www.reddit.com/r/selfhosted/comments/1gw4sw4/trying_to_reduce_my_self_hosted_overhead_i_created)
 - RSS feed: $source
 - date published: 2024-11-21T01:51:11+00:00

<!-- SC_OFF --><div class="md"><p>So as the title suggests I&#39;m trying to reduce the overhead of my self hosted environment more specifically with my containers I&#39;m running. Currently my setup is all over the place, I have full blown rancher cluster, docker compose based containers running on various LXC and Virtual machines, portainer and individual just docker run containers I&#39;m not even keeping track of at this point. I don&#39;t have the time to manage and remember all the places I did &quot;things&quot; as much as I used to.</p> <p>I want to start fresh with a new service and use the freed up resources from my previous deployments to set something new. I&#39;ve been debating of just doing a virtual machine instance running either Cosmos Cloud (<a href="https://github.com/azukaar/Cosmos-Server">Link</a>) or a CasaOS. I&#39;m really liking Cosmos via the demo and I&#39;m just curious if anyone had any feedback between the two serivces?</p> </div><!-- SC_ON --> &#32; sub

## DNS: Where is Cloudflare coming from (Pihole + Unbound)
 - [https://www.reddit.com/r/selfhosted/comments/1gw4ptb/dns_where_is_cloudflare_coming_from_pihole_unbound](https://www.reddit.com/r/selfhosted/comments/1gw4ptb/dns_where_is_cloudflare_coming_from_pihole_unbound)
 - RSS feed: $source
 - date published: 2024-11-21T01:47:17+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gw4ptb/dns_where_is_cloudflare_coming_from_pihole_unbound/"> <img src="https://b.thumbs.redditmedia.com/WTWiGOKdK-lC2L3QU_AFwLx8Ye01VtYMlN-AEQhRb5Y.jpg" alt="DNS: Where is Cloudflare coming from (Pihole + Unbound)" title="DNS: Where is Cloudflare coming from (Pihole + Unbound)" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Running Pihole + Unbound. Have a rather weird issue.</p> <p>If I log into my VPS server and go to the url:</p> <ul> <li><a href="https://test.nextdns.io/">https://test.nextdns.io/</a></li> </ul> <p>It shows that my resolver of Cloudflare:</p> <pre><code>{ &quot;status&quot;: &quot;unconfigured&quot;, &quot;resolver&quot;: &quot;172.71.145.237&quot;, &quot;ecs&quot;: &quot;0.0.0.0/24/0&quot;, } </code></pre> <p>&#x200B;</p> <p>If I go to:</p> <ul> <li><a href="https://www.dnsleaktest.com/">https://www.dnsleaktest.com/</a></li> </ul> <p>It shows that Cloudflare is my DNS:</p> <ul> <li>172.7

## Kudos to NAS! It really helps our team store & share company files more efficiently
 - [https://www.reddit.com/r/selfhosted/comments/1gw4kho/kudos_to_nas_it_really_helps_our_team_store_share](https://www.reddit.com/r/selfhosted/comments/1gw4kho/kudos_to_nas_it_really_helps_our_team_store_share)
 - RSS feed: $source
 - date published: 2024-11-21T01:40:10+00:00

<!-- SC_OFF --><div class="md"><p>Our small team was always running into storage issues across different devices, especially with large video files, so we got ourselves a NAS setup. A few things we’ve found helpful so far:</p> <ol> <li><p>Great for everything in one place.</p></li> <li><p>The upload speeds make it easy to handle larger files/images/media assets.</p></li> <li><p>Can sync files across everyone&#39;s devices</p></li> <li><p>No monthly cloud fees needed.</p></li> <li><p>Reliable access, even when working remotely.</p></li> </ol> <p>Would like to know if anyone else been using this kinds of setups and any idea how to make the most of it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bestboiijacob"> /u/bestboiijacob </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gw4kho/kudos_to_nas_it_really_helps_our_team_store_share/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gw4k

## Retrom v0.4 Released - Fullscreen mode w/ initial gamepad support
 - [https://www.reddit.com/r/selfhosted/comments/1gw3e8m/retrom_v04_released_fullscreen_mode_w_initial](https://www.reddit.com/r/selfhosted/comments/1gw3e8m/retrom_v04_released_fullscreen_mode_w_initial)
 - RSS feed: $source
 - date published: 2024-11-21T00:46:03+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gw3e8m/retrom_v04_released_fullscreen_mode_w_initial/"> <img src="https://external-preview.redd.it/Wtlj7YCBfn7lSD4TpKDhiby3VO9cYaV_FsC1UqJt24E.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=c12761f97fa66d4745b586fe3b3f6c0791bb0a92" alt="Retrom v0.4 Released - Fullscreen mode w/ initial gamepad support" title="Retrom v0.4 Released - Fullscreen mode w/ initial gamepad support" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey all, I&#39;m here to update everyone on Retrom&#39;s most recent major release! Since last time there are two major changes to note:</p> <ol> <li>Fullscreen mode! Now Retrom is easily used in couch gaming environments and feels great on handhelds! <ol> <li>Initial gamepad support should properly render glyphs for just about any XBox controllers and/or DualShock controllers. There are bound to be some missing pieces here, so please reach out to report faulty/missing controller mappings 

