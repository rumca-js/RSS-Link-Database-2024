# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## searching for link gate, link collection
 - [https://www.reddit.com/r/selfhosted/comments/1hloepc/searching_for_link_gate_link_collection](https://www.reddit.com/r/selfhosted/comments/1hloepc/searching_for_link_gate_link_collection)
 - RSS feed: $source
 - date published: 2024-12-24T22:49:27+00:00

<!-- SC_OFF --><div class="md"><p>Im searching for an app similar to the service hypeddit, it allowes to create smart links and a gate similar to linktree or linkstack. I tried linkstack however i find it tedious that for every link collection i create i must create a profile. would be great if i can just create multiple path with its own link collection without having to create seperate profiles.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cube303"> /u/cube303 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hloepc/searching_for_link_gate_link_collection/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hloepc/searching_for_link_gate_link_collection/">[comments]</a></span>

## Have you ever let something mess with your pride in self-hosting?
 - [https://www.reddit.com/r/selfhosted/comments/1hlo5kb/have_you_ever_let_something_mess_with_your_pride](https://www.reddit.com/r/selfhosted/comments/1hlo5kb/have_you_ever_let_something_mess_with_your_pride)
 - RSS feed: $source
 - date published: 2024-12-24T22:35:09+00:00

<!-- SC_OFF --><div class="md"><p>I recently set up and deployed an app called Babybuddy for our new baby. It was helpful at the beginning, and I thought it would be great for my family.</p> <p>However, a friend of my wife suggested trying a paid app called Napper, which has more features than Babybuddy. At first, I was hesitant to pay for the annual subscription because I want to avoid extra costs and make the most of my own resources. To be honest, this situation affected my pride in self-hosting.</p> <p>I felt frustrated and wondered why my wife didn’t see the effort I put into Babybuddy. Then I realized something important: not every issue is worth fighting over. Just because I find an app useful doesn&#39;t mean it meets our family&#39;s needs, and that’s okay. Self-hosting is a hobby for me, but it may not matter to everyone else.</p> <p>This experience taught me to focus on what works best for our family instead of just what interests me. It&#39;s fine to enjoy setting up syst

## JellyFin on FireTV won't connect to server (2024-12)
 - [https://www.reddit.com/r/selfhosted/comments/1hlo2va/jellyfin_on_firetv_wont_connect_to_server_202412](https://www.reddit.com/r/selfhosted/comments/1hlo2va/jellyfin_on_firetv_wont_connect_to_server_202412)
 - RSS feed: $source
 - date published: 2024-12-24T22:31:06+00:00

<!-- SC_OFF --><div class="md"><p>Like others here, the official JellyFin app on my Fire TV recently stopped being able to connect to the JellyFin server. Specifically, from the Welcome to JellyFin screen on my FireTV, the Discovered servers box finds the server but when I select it and press OK, the error at the bottom reads: </p> <blockquote> <p><em>Unable to connect to server, tried the following addresses:</em> <a href="https://192.168.1.103:8096"><em>https://192.168.1.103:8096</em></a> <em>Unable to connect</em> <a href="http://192.169.1.103:8096"><em>http://192.169.1.103:8096</em></a> <em>Server uses version 10.9.10 which is not supported.</em></p> </blockquote> <p>Interestingly, when I use a FireTV browser and visit <a href="http://192.169.1.103:8096"><em>http://192.169.1.103:8096</em></a>, I am able to login and play videos. So I assume that means there is something about the app that isn&#39;t working with the Jellyfin server?</p> <p>Things I tried:</p> <ol> <li>Uninstalled 

## Self hosted simple file share?
 - [https://www.reddit.com/r/selfhosted/comments/1hlnjmj/self_hosted_simple_file_share](https://www.reddit.com/r/selfhosted/comments/1hlnjmj/self_hosted_simple_file_share)
 - RSS feed: $source
 - date published: 2024-12-24T22:01:32+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m fairly new to self hosting so I don&#39;t know if there&#39;s an obvious answer.</p> <p>I would like a file sharing webpage that you can create a link and anyone that has that link can download the associated files. </p> <p>No security other than you must have the link. And I&#39;d like the ability to expire links after so long. Anyone can upload and create a link, etc.</p> <p>Have any of you come across something like that which is self hostable?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DemandTheOxfordComma"> /u/DemandTheOxfordComma </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlnjmj/self_hosted_simple_file_share/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlnjmj/self_hosted_simple_file_share/">[comments]</a></span>

## Podman's "rootlessport" listening on 443, preventing reverse proxy deployment
 - [https://www.reddit.com/r/selfhosted/comments/1hln8yp/podmans_rootlessport_listening_on_443_preventing](https://www.reddit.com/r/selfhosted/comments/1hln8yp/podmans_rootlessport_listening_on_443_preventing)
 - RSS feed: $source
 - date published: 2024-12-24T21:45:31+00:00

<!-- SC_OFF --><div class="md"><p>I am running <a href="https://github.com/containers/podman/blob/main/docs/tutorials/rootless_tutorial.md">Podman rootless</a> containers on Debian 12. In general, this setup works well.</p> <p>Right now I&#39;m attempting to deploy a reverse proxy (Caddy) which will listen on 80/443, but Podman tells me 443 is already in use. <code>sudo ss -tulpn</code> shows me</p> <p><code>log tcp LISTEN 0 4096 *:443 *:* users:((&quot;rootlessport&quot;,pid=1424343,fd=15)) </code></p> <p>If I kill Podman&#39;s rootlessport process, container networking goes down. Do I need to route traffic from 443 to a different (unprivileged) port with a firewall?</p> <p>[Podman 4.3.1, Debian 12.2.0-14]</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bearflyingbolt"> /u/bearflyingbolt </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hln8yp/podmans_rootlessport_listening_on_443_preventing/">[link]</a></span> &#32; <span

## Image classification and hosting
 - [https://www.reddit.com/r/selfhosted/comments/1hlmjyi/image_classification_and_hosting](https://www.reddit.com/r/selfhosted/comments/1hlmjyi/image_classification_and_hosting)
 - RSS feed: $source
 - date published: 2024-12-24T21:07:36+00:00

<!-- SC_OFF --><div class="md"><p>Hi!</p> <p>Doing data inventory, and as it turns out, when I have 500TB with data, it&#39;s kinda a mess all around. Gotten most things in place to classify and categorize most data, and even host most on my home network, wohoo!</p> <p>Now, images, these monsters will forever be the bane of my existence. I got tens of thousands of images, intermixed private images and misc stuffs grabbed from the internet over the past 20 years and change.</p> <p>Last time I stumbled upon a stash of images, I just kinda shrugged, concluded that it was impossible to handle, and moved on to deal with something else, but that was in 2016, it&#39;s now 2024 and the world is quite different, so thought there may be some AI workflow that could assist me.</p> <p>I have some programming experience, so can probably figure out how to cook up something myself if I only know a model to use to classify things. A fair number of pictures are nsfw as well, something that most AI won

## Why did certain IP flagged as trojan for syncthing? Though they have been flagged by malware bytes, the sync worked as expected.
 - [https://www.reddit.com/r/selfhosted/comments/1hllukb/why_did_certain_ip_flagged_as_trojan_for](https://www.reddit.com/r/selfhosted/comments/1hllukb/why_did_certain_ip_flagged_as_trojan_for)
 - RSS feed: $source
 - date published: 2024-12-24T20:29:59+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hllukb/why_did_certain_ip_flagged_as_trojan_for/"> <img src="https://external-preview.redd.it/8q06nAnDb2kbQYvvLF7gQx2jVMKCvDIHpH1SfmiWbcw.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=700f95b7c5961ac43fdaf3318bf2cb1d83c70f3c" alt="Why did certain IP flagged as trojan for syncthing? Though they have been flagged by malware bytes, the sync worked as expected." title="Why did certain IP flagged as trojan for syncthing? Though they have been flagged by malware bytes, the sync worked as expected." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/whats_you_doing"> /u/whats_you_doing </a> <br/> <span><a href="https://www.imgur.com/a/S3WdNqR">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hllukb/why_did_certain_ip_flagged_as_trojan_for/">[comments]</a></span> </td></tr></table>

## VM Disk Structure to avoid overloading OS filesystem
 - [https://www.reddit.com/r/selfhosted/comments/1hlls5f/vm_disk_structure_to_avoid_overloading_os](https://www.reddit.com/r/selfhosted/comments/1hlls5f/vm_disk_structure_to_avoid_overloading_os)
 - RSS feed: $source
 - date published: 2024-12-24T20:26:18+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve run into the issue where the size of the docker folder grows too large due to temp/cache for some dockers, or just docker folder growing too large in general.</p> <p>Wondering how selfhosted users structure their VMs. New virtual disks? Mount NFS storage from Proxmox host? etc.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AuthorYess"> /u/AuthorYess </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlls5f/vm_disk_structure_to_avoid_overloading_os/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlls5f/vm_disk_structure_to_avoid_overloading_os/">[comments]</a></span>

## What is this IP belongs to? Why did malware bytes blocked and flagged it as trojan? However the sync worked as expected.
 - [https://www.reddit.com/r/selfhosted/comments/1hllo5m/what_is_this_ip_belongs_to_why_did_malware_bytes](https://www.reddit.com/r/selfhosted/comments/1hllo5m/what_is_this_ip_belongs_to_why_did_malware_bytes)
 - RSS feed: $source
 - date published: 2024-12-24T20:20:13+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hllo5m/what_is_this_ip_belongs_to_why_did_malware_bytes/"> <img src="https://external-preview.redd.it/GvThCbpEM-AxrlMVwwFaUt9RASnpquNdT4CwGwTdw78.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=be1f5e412986a7c4dd8243e7c932b1ec922814a4" alt="What is this IP belongs to? Why did malware bytes blocked and flagged it as trojan? However the sync worked as expected." title="What is this IP belongs to? Why did malware bytes blocked and flagged it as trojan? However the sync worked as expected." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/whats_you_doing"> /u/whats_you_doing </a> <br/> <span><a href="https://www.imgur.com/a/8PpUwpU">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hllo5m/what_is_this_ip_belongs_to_why_did_malware_bytes/">[comments]</a></span> </td></tr></table>

## Subdomain redirection in Caddy
 - [https://www.reddit.com/r/selfhosted/comments/1hllmvs/subdomain_redirection_in_caddy](https://www.reddit.com/r/selfhosted/comments/1hllmvs/subdomain_redirection_in_caddy)
 - RSS feed: $source
 - date published: 2024-12-24T20:18:18+00:00

<!-- SC_OFF --><div class="md"><p>hey everyone,</p> <p>i&#39;m dealing with an issue in Caddy where I would like to have a subdomain for applications running on different ports. <strong>Everything works fine</strong> but the issue is when I set a subdomain, it redirects me to the main domain:port (eg.: <a href="http://sub.example.com">sub.example.com</a> -&gt; example.com:8080). What I want is to stay on the subdomain itself (sub.example.com), without it redirecting me to the main domain:port (exmaple.com:8080). I want the traffic to remain on the subdomain without changing to the domain:port.</p> <p><strong>I&#39;m just curious</strong> if this method is possible with Caddy, and if so how it can be achieved or if it&#39;s not possible. That&#39;s basically what I&#39;m trying to figure out.</p> <p>Hopefully i explained myself well, but I want to once again clarify that the redirection from the subdomain to the port (reverse proxy) works just fine. Here&#39;s the config: <code> sub.e

## Podcast solutions?
 - [https://www.reddit.com/r/selfhosted/comments/1hllmlg/podcast_solutions](https://www.reddit.com/r/selfhosted/comments/1hllmlg/podcast_solutions)
 - RSS feed: $source
 - date published: 2024-12-24T20:17:51+00:00

<!-- SC_OFF --><div class="md"><p>So I&#39;ve been bouncing around on a few platforms/apps to find something that suits our needs, and beginning to wonder if maybe downloading/self hosting of podcasts I&#39;m interested in may be the best way forward</p> <p>What I am trying to find is a solution that:</p> <p>1) has a full set of playlist features, bonus points for smart playlists so I can setup some rules and have the playlist populated based on recent episodes and so on that match my filter</p> <p>2) multi-user support</p> <p>3) unified browser and app so that I can build playlists etc on my pc and listen on my phone (a PWA approach over a true dedicated app is fine as well)</p> <p>4) extra bonus points if it supports OAUTH2 an/or other SSO options</p> <p>Currently I&#39;m using Audiobookshelf but the playlist features are incredibly rudimentary and looking to improve on that if possible</p> <p>Open to experimenting with whatever really, this is one of those projects with a primary 

## Pinchflat and Jellyfin: Thumbnails and Metadata
 - [https://www.reddit.com/r/selfhosted/comments/1hll3k4/pinchflat_and_jellyfin_thumbnails_and_metadata](https://www.reddit.com/r/selfhosted/comments/1hll3k4/pinchflat_and_jellyfin_thumbnails_and_metadata)
 - RSS feed: $source
 - date published: 2024-12-24T19:50:36+00:00

<!-- SC_OFF --><div class="md"><p>I just set up Pinchflat, and it seems to be the first Youtube Downloader that works for me. I&#39;m trying to tie up a few loose ends:</p> <p>I can&#39;t seem to figure out how to get channel images to show up in Jellyfin. I&#39;m talking about the banner image that shows up on a YT channel. In the same vein, it would be nice to have the channel description show up in Jellyfin. I can see the channel description in Pinchflat, but not sure how to get it into Jellyfin.</p> <p>I&#39;m also wondering how to not have episodes show up in &#39;seasons&#39;. It&#39;d be nice to just click on the channel and see all the videos.</p> <p>I read about NFO files for Jellyfin, but I couldn&#39;t get it working immediately (so gave up to circle around), also I don&#39;t really wantoto create NFO files for each channel.</p> <p>Overall it seems like a great program. I&#39;m going to post some feature requests on the GitHub after getting answer here, and I also plan on 

## Opensource RMS (Rental Management System)
 - [https://www.reddit.com/r/selfhosted/comments/1hljx8q/opensource_rms_rental_management_system](https://www.reddit.com/r/selfhosted/comments/1hljx8q/opensource_rms_rental_management_system)
 - RSS feed: $source
 - date published: 2024-12-24T18:50:16+00:00

<!-- SC_OFF --><div class="md"><p>Hello</p> <p>I&#39;m looking for an opensource alternative to the following:<br/> These software are rental management system specifically for equipment rentals.<br/> I&#39;ve looked at ERPNext as an alternative but their inventory management is for products and not for rentals, it would be nice to include invoicing and other stuff as well but that is optional.</p> <p>Any thoughts or comments would help.<br/> Thanks in advanced.</p> <ul> <li>Hiretrack</li> <li>Current RMS</li> <li>Flex GTS</li> <li>HireHop</li> <li>Rentman</li> <li>Point of Rental</li> <li>R2</li> <li>RentalWorks</li> <li>Intellievent</li> <li>Flex</li> <li>booqable</li> <li>EZ RentOut</li> <li>Rentopian</li> <li>FocalPoint</li> <li>easyjob 6</li> <li>Rentmaster</li> <li>Rental360</li> <li>InTempo Core</li> <li>Party Rental Studio</li> <li>Event Rental Systems</li> <li>Alert Rental (SaaS)</li> <li>ARM Automated Rental Management</li> <li>iPoint Solutions</li> <li>Rental Point</li> <l

## DDNS Question regarding Cloudflare.
 - [https://www.reddit.com/r/selfhosted/comments/1hliy8t/ddns_question_regarding_cloudflare](https://www.reddit.com/r/selfhosted/comments/1hliy8t/ddns_question_regarding_cloudflare)
 - RSS feed: $source
 - date published: 2024-12-24T18:02:51+00:00

<!-- SC_OFF --><div class="md"><p>Hi Guys</p> <p>Got a quick question, I new so please go easy :) I have setup NPM with Cloudflare, I&#39;m using a A record for my domain pointing to NPM and Cname for Sub-Domains. I am using DNS challenge and just want to keep everything local for now. Everything is setup and working fine! I would just like to know since I don&#39;t have a Static IP what will happen if it changes? Will Cloudflare auto update or what do I need to do?</p> <p>Thanks in advance..</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Splitonious"> /u/Splitonious </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hliy8t/ddns_question_regarding_cloudflare/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hliy8t/ddns_question_regarding_cloudflare/">[comments]</a></span>

## I am searching for a status-monitoring software with agents
 - [https://www.reddit.com/r/selfhosted/comments/1hliwaj/i_am_searching_for_a_statusmonitoring_software](https://www.reddit.com/r/selfhosted/comments/1hliwaj/i_am_searching_for_a_statusmonitoring_software)
 - RSS feed: $source
 - date published: 2024-12-24T18:00:24+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>In the past I&#39;ve monitored internal stuff by having an UptimeKuma running via Docker on a small Debian Server which has access to my Tailscale Network, but I now came to a point where I have to monitor a Paperless and Traefik on a family members NAS which are 1) private and 2) outside of my Tailnet. For that I would like to move in with my Status Monitoring to a solution which supports some kind of &quot;agents&quot; or similar, like agents in Portainer for example.</p> <p>I thought of having something like a main instance of my status monitoring which holds all monitors, sends notifications, and hosts a simple status page. And then be able to register agents on remote machines in a container, which gets provided with an api key and a main instance URL or something, and report the monitor data to the main machine.</p> <p>I searched for a while and came across Zabbix and CheckMK, but they seem kind of complicated.<br/> I&#39;d like to h

## Run command at reboot / shutdown
 - [https://www.reddit.com/r/selfhosted/comments/1hlhlyv/run_command_at_reboot_shutdown](https://www.reddit.com/r/selfhosted/comments/1hlhlyv/run_command_at_reboot_shutdown)
 - RSS feed: $source
 - date published: 2024-12-24T16:58:36+00:00

<!-- SC_OFF --><div class="md"><p>Hello y&#39;all</p> <p>So I am having the regular problem of running a script or a command at reboot/shutdown with Debian. I would like to list the active docker compose directories, that is (as simple as that)</p> <p>docker compose ls --quiet</p> <p>I have tried setting up a service as follows</p> <pre><code>[Unit] Description=Grab docker compose list DefaultDependencies=no Before=reboot.target shutdown.target [Service] Type=oneshot RemainAfterExit=true ExecStop=/home/eric/startup/compose-inventory.sh TimeoutStartSec=0 [Install] WantedBy=reboot.target shutdown.target </code></pre> <p>I have tried many variants such as with ExecStart instead of ExecStop, ... Nothing seems to work. Any clue how I should handle that ? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Eirikr700"> /u/Eirikr700 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlhlyv/run_command_at_reboot_shutdown/">[link]</a></s

## What else to host?
 - [https://www.reddit.com/r/selfhosted/comments/1hlhfwp/what_else_to_host](https://www.reddit.com/r/selfhosted/comments/1hlhfwp/what_else_to_host)
 - RSS feed: $source
 - date published: 2024-12-24T16:50:05+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I currently have the following that I self host, all internal:</p> <p>OPNSense Bare metal</p> <p>Proxmox - 3 nodes</p> <ol> <li>Technitium Primary and secondary DNS</li> <li>Plane - project management tool</li> <li>Immich - using ZFS raid 10</li> <li>Dashy - 2 instances. One for me and one for my SO</li> <li>Test-DNS (for testing, of course)</li> <li>Caddy reverse proxy - with SSL termination</li> </ol> <p>I’m kind of lost on what to do next. </p> <p>I’m building up on having Prometheus and Grafana for network monitoring. </p> <p>Also, who do you use for cloud backup so I can start my journey on 3-2-1 backup. </p> <p>I have 96GB of RAM for my proxmox cluster. I forgot how many CPUs. </p> <p>In your own opinion, would you put hcp vault in a container or put it in your own central system? I want to grab my keys with a powershell script so it would be easier. </p> <p>Maybe it’s time that I learn ansible too. Too many things to think 

## Strip Win11 bloat from VM
 - [https://www.reddit.com/r/selfhosted/comments/1hlh7c6/strip_win11_bloat_from_vm](https://www.reddit.com/r/selfhosted/comments/1hlh7c6/strip_win11_bloat_from_vm)
 - RSS feed: $source
 - date published: 2024-12-24T16:38:18+00:00

<!-- SC_OFF --><div class="md"><p>Edit: I did do some reading on this, but found conflicting or inconclusive results apart from the debloat script.</p> <p>Hopefully this is the place for this post. If not, I&#39;m certain y&#39;all will let me know.</p> <p>I&#39;m trying to optimize a Win11 VM on Proxmox, mostly for the environment to run a few things I can&#39;t on Linux, for example some particular CNC software, Steam, some other odds and ends. I also want the VM to not know it&#39;s a VM.</p> <p>Computer I&#39;m running Proxmox on is not really beefy right now, only 8G ram, will be replaced soon(ish). Regardless of the host&#39;s power, I really want the Win11VM to be as stripped as possible with everything still functional. I used Chris Titus&#39; debloat script and went hard on it, even some of the not-recommended options. For those who aren&#39;t aware of it, it strips bloat, telemetry, monitoring, ads, and nags. VM still functions fine. I&#39;ve uninstalled as many pointless a

## Spending time with others, a chore?
 - [https://www.reddit.com/r/selfhosted/comments/1hlh0vm/spending_time_with_others_a_chore](https://www.reddit.com/r/selfhosted/comments/1hlh0vm/spending_time_with_others_a_chore)
 - RSS feed: $source
 - date published: 2024-12-24T16:29:20+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys,</p> <p>So far I&#39;ve been quite happy with what I&#39;ve achieved with self hosting, the fact that things actually work and are relatively well secured also pleases me.</p> <p>But of course, here and there sometimes something goes wrong, and there&#39;s a bug to fix, another problem to solve... </p> <p>This often happens when I&#39;m the least expecting. For example, when I went a bit more far with my family to spend some time together, or enjoying some time with friends. This then makes me more stressed when I should be enjoying the trip.</p> <p>And, because I spend so much time messing and tweaking with servers, sometimes I feel like it&#39;s a shore to dedicate time with others, because It&#39;s something I have to do, for my mind&#39;s sake and for others sake. </p> <p>It&#39;s like, the duty to enjoy your time with others, opposed to, actually enjoying your time with others without any worry whatsoever.</p> <p>Have you guys felt some

## I have made a telnet interface how do i host it for free(publicly)??
 - [https://www.reddit.com/r/selfhosted/comments/1hlghfo/i_have_made_a_telnet_interface_how_do_i_host_it](https://www.reddit.com/r/selfhosted/comments/1hlghfo/i_have_made_a_telnet_interface_how_do_i_host_it)
 - RSS feed: $source
 - date published: 2024-12-24T16:02:07+00:00

<!-- SC_OFF --><div class="md"><p>i have an esp32 and i&#39;ve made a port on it that hosts a tui interface for managing my home devices</p> <p>is it possible to use that port and make a reverse proxy to it or something</p> <p>some service that routes all the packets to that port </p> <p>note it&#39;s a telnet port so it&#39;s tcp</p> <p>also i can&#39;t port forward as my ISP is F**king incompetitive af</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Glittering_Boot_3612"> /u/Glittering_Boot_3612 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlghfo/i_have_made_a_telnet_interface_how_do_i_host_it/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlghfo/i_have_made_a_telnet_interface_how_do_i_host_it/">[comments]</a></span>

## wallabag documentation had a full refresh just before Christmas
 - [https://www.reddit.com/r/selfhosted/comments/1hlftom/wallabag_documentation_had_a_full_refresh_just](https://www.reddit.com/r/selfhosted/comments/1hlftom/wallabag_documentation_had_a_full_refresh_just)
 - RSS feed: $source
 - date published: 2024-12-24T15:29:10+00:00

<!-- SC_OFF --><div class="md"><p>Hello community,</p> <p>As a heavy self-hoster and as a core developer of wallabag (<em>self-hosted read-it-later app</em>), I wanted to share with you that we&#39;ve made a complete refresh of the project documentation and it&#39;s available here: <a href="https://doc.wallabag.org/">https://doc.wallabag.org/</a></p> <p>Happy self-hosting :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kdecherf"> /u/kdecherf </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlftom/wallabag_documentation_had_a_full_refresh_just/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlftom/wallabag_documentation_had_a_full_refresh_just/">[comments]</a></span>

## Ganymede v4.0 Release
 - [https://www.reddit.com/r/selfhosted/comments/1hlez2p/ganymede_v40_release](https://www.reddit.com/r/selfhosted/comments/1hlez2p/ganymede_v40_release)
 - RSS feed: $source
 - date published: 2024-12-24T14:46:22+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hlez2p/ganymede_v40_release/"> <img src="https://external-preview.redd.it/fzHHYCtDgxtxE6AYu_TjdSq3M9r5x3pZXvguN-dJg3c.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=d00280590ff97ad7c60c814b41bcc7e8335f7060" alt="Ganymede v4.0 Release" title="Ganymede v4.0 Release" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Ganymede is a Twitch VOD and live stream archiving platform. It includes advanced channel watching functionality to ensure your favorite streamer&#39;s content is preserved. The number one goal of Ganymede is to archive streams in a way that will outlive the application itself, this means friendly file formats and names.</p> <p>Github: <a href="https://github.com/Zibbp/ganymede">https://github.com/Zibbp/ganymede</a></p> <p>v4.0 release notes: <a href="https://github.com/Zibbp/ganymede/releases/tag/v4.0.0">https://github.com/Zibbp/ganymede/releases/tag/v4.0.0</a></p> <p>The v4.0 release reduced the nu

## Audio quality focuesd teamspeak alternative?
 - [https://www.reddit.com/r/selfhosted/comments/1hlempf/audio_quality_focuesd_teamspeak_alternative](https://www.reddit.com/r/selfhosted/comments/1hlempf/audio_quality_focuesd_teamspeak_alternative)
 - RSS feed: $source
 - date published: 2024-12-24T14:27:57+00:00

<!-- SC_OFF --><div class="md"><p>I use teamspeak for 99% of my time, but lacking web interface would be a hard time asking my friend to download and config there mic (turning off the auto leveling or enable reduces echos..). </p> <p>What I truly can&#39;t leave teamspeak is its audio quality. I genuinely put a music bot in my teamspeak to listen to music with my friends. I know discord can do that also, but yknow I have paid all my money to my own server &lt;3. </p> <p>I have checked Revolt. But I don&#39;t see any quality option in there official website. I have checked Matrix but also the quality is not that great for listening music. </p> <p>TL;DR, high quality, dual audio channel, has web interface, teamspeak alternative. </p> <p>Soryy I have seem a lots of posts that ask about teamspeak alternatives but I didn&#39;t found anyone that mention audio quality though...Yeah nothing fancy is needed. If this is already solved, my apologised.</p> </div><!-- SC_ON --> &#32; submitted by

## Using My Old Laptop as a Home Server for Plex/Jellyfin & Photo Storage
 - [https://www.reddit.com/r/selfhosted/comments/1hlecgj/using_my_old_laptop_as_a_home_server_for](https://www.reddit.com/r/selfhosted/comments/1hlecgj/using_my_old_laptop_as_a_home_server_for)
 - RSS feed: $source
 - date published: 2024-12-24T14:12:44+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I’m turning my old laptop into a home server and could use some advice. I’ve already installed Ubuntu on it and set up OpenSSH to control it from my main laptop. I’m also installing CasaOS to make managing everything easier.</p> <p>The plan is to: 1. Use Plex or Jellyfin to stream movies and shows. 2. Set it up as a place to store and access my phone’s photos and videos, like my own Google Drive.</p> <p>Here’s where I need help: 1. Which is better for a basic media server setup—Plex or Jellyfin? Any tips to keep it running smoothly on an older laptop? 2. For photo/video storage, I’ve heard about things like Nextcloud or Seafile. Are they good for auto-backing up photos from my phone? How easy are they to set up? 3. Any general tips for getting the most out of this setup? Stuff like performance tweaks or things to watch out for?</p> <p>If anyone’s done something like this, I’d love to hear how it worked out for you. Thanks in adva

## Is it bad to expose some ports to public for rustdesk?
 - [https://www.reddit.com/r/selfhosted/comments/1hleb36/is_it_bad_to_expose_some_ports_to_public_for](https://www.reddit.com/r/selfhosted/comments/1hleb36/is_it_bad_to_expose_some_ports_to_public_for)
 - RSS feed: $source
 - date published: 2024-12-24T14:10:42+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I am fairly new to the self hosting world and I would like to get your opinions. First thing first I wanted to host a screen sharing application so that I can reach my server even if I am not home. I used deployed the server on docker but it requires some exceptions to be made in port configuration. So, I created exceptions in my ufw config for those and then added port forwarding through my router. They are tcp/udp ports. I isolated my mini pc server in the home network as well.</p> <p>I tried to use cloudflare tunnel but it seems I can’t do this unless I’m on enterprise plan or smth </p> <p>Things work but I’m not sure how secure it is. Can someone advise me?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Amazing_Cell4641"> /u/Amazing_Cell4641 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hleb36/is_it_bad_to_expose_some_ports_to_public_for/">[link]</a></span> &#32; <spa

## Roundcube export
 - [https://www.reddit.com/r/selfhosted/comments/1hle8bk/roundcube_export](https://www.reddit.com/r/selfhosted/comments/1hle8bk/roundcube_export)
 - RSS feed: $source
 - date published: 2024-12-24T14:06:26+00:00

<!-- SC_OFF --><div class="md"><p>Somebody set me up a Roundcube a few years back and having fought with it for a few years, I’m finally moving to a Microsoft business license.</p> <p>As far as I can see, I can only export emails individually from Roundcube and have THOUSANDS 😭. Does anyone know of a way to do this in bulk? TIA!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Patchasaur"> /u/Patchasaur </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hle8bk/roundcube_export/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hle8bk/roundcube_export/">[comments]</a></span>

## homepage proxmox "Unexpected end of JSON input"
 - [https://www.reddit.com/r/selfhosted/comments/1hle5xc/homepage_proxmox_unexpected_end_of_json_input](https://www.reddit.com/r/selfhosted/comments/1hle5xc/homepage_proxmox_unexpected_end_of_json_input)
 - RSS feed: $source
 - date published: 2024-12-24T14:02:54+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hle5xc/homepage_proxmox_unexpected_end_of_json_input/"> <img src="https://b.thumbs.redditmedia.com/sFeBYaTFv6k4iV2ZfQRtqluUESo1bs77g6GeY8ROgos.jpg" alt="homepage proxmox &quot;Unexpected end of JSON input&quot;" title="homepage proxmox &quot;Unexpected end of JSON input&quot;" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>hey guys,</p> <p>can you help me to solve this issue.<br/> i got this error by using proxmox widget in homepage:</p> <p><a href="https://preview.redd.it/tc9bm22nys8e1.png?width=559&amp;format=png&amp;auto=webp&amp;s=074bbf419cf3172b9081436ce9a3703b2e87fabe">https://preview.redd.it/tc9bm22nys8e1.png?width=559&amp;format=png&amp;auto=webp&amp;s=074bbf419cf3172b9081436ce9a3703b2e87fabe</a></p> <p>Using this in services.yaml:</p> <pre><code>- internal Hosts: - proximoxi: description: Proxmox PVE href: https://192.168.1.1:8006/ icon: https://192.168.1.1:8006/pve2/images/logo-128.png ping: 192.1

## What can be a complete stack to replace Spotify ?
 - [https://www.reddit.com/r/selfhosted/comments/1hle5w4/what_can_be_a_complete_stack_to_replace_spotify](https://www.reddit.com/r/selfhosted/comments/1hle5w4/what_can_be_a_complete_stack_to_replace_spotify)
 - RSS feed: $source
 - date published: 2024-12-24T14:02:51+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,<br/> I want to replace as many closed-source services as possible with open-source alternatives, and now I’m tackling Spotify. I’m looking for a complete stack to replicate Spotify’s key features, and I’d love your guidance.</p> <p>Here’s what I need:</p> <ol> <li><strong>Search and Play</strong>: A search bar where I can quickly type the name of a song or artist, then play it or add it to a playlist—all from a single interface. (I assume it should need to download, maybe it should download from youtube using ytdl ?)</li> <li><strong>Compatibility</strong>: <ul> <li>It must work on iOS.</li> <li>CarPlay compatibility is essential.</li> <li>Siri integration would be a dream feature.</li> <li>If possible, docker (compose)</li> </ul></li> <li><strong>Recommendations</strong>: A way to discover new music or get recommendations, so I don’t end up listening to the same songs all the time.</li> <li><strong>New releases</strong>: A feature to tr

## Does higher CPU usage cause lower component life?
 - [https://www.reddit.com/r/selfhosted/comments/1hle41x/does_higher_cpu_usage_cause_lower_component_life](https://www.reddit.com/r/selfhosted/comments/1hle41x/does_higher_cpu_usage_cause_lower_component_life)
 - RSS feed: $source
 - date published: 2024-12-24T14:00:36+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m new to self hosting but not to hosting webservices. At my organization I host a bunch , but we have essentially unlimited resources compared to my homelab. If I need a new setup, I can spin up 2-3 commodity desktops at work and load share between them, if one goes down I shrug and make a new one. So far we&#39;ve only ever lost one out of like 50, but at home I have...exactly one commodity desktop. In fact, it&#39;s worse than that - it&#39;s an 8 year old mini computer. I&#39;ve put a ton of stuff on it, just playing around, and I notice that my CPU load is always about 1.25/8, and one of the CPUs is always doing *something* to put its utilization above 20%, even when I am doing nothing on the server except for looking at my utilization. </p> <p>My homelab setup won&#39;t change any time soon, so right now everything relies on this one extremely nervous little computer. I&#39;m wondering if there is some kind of obvious rules about utilizati

## Whats everyone using to host private LLM and ai image generation?
 - [https://www.reddit.com/r/selfhosted/comments/1hle3wu/whats_everyone_using_to_host_private_llm_and_ai](https://www.reddit.com/r/selfhosted/comments/1hle3wu/whats_everyone_using_to_host_private_llm_and_ai)
 - RSS feed: $source
 - date published: 2024-12-24T14:00:26+00:00

<!-- SC_OFF --><div class="md"><p>Local home server hosted llm and image generation doesnt look viable for me as I would have to get a new external GPU and connect to my home server and the cost of gpus is high especially with a external gpu enclosure and ideally I would be able to access outside of my home network and would love it to scale with new improved LLM, image and video generation as models improve. I want to be able to use LLM for my own notes and files as well as use it for coding support and idea generation. For image and video creation I would like high quality image output without the restrictions of these online sources. I&#39;ve started looking at runpod but thought there would be others with experience and advice over here...any thoughts suggestions and cost effective solution ideas would be greatly appreciatd. I would be looking to use openwebui as the access frontend. It would also be great for future use cases if I could deploy other connected workflow capabiliti

## DB services
 - [https://www.reddit.com/r/selfhosted/comments/1hle283/db_services](https://www.reddit.com/r/selfhosted/comments/1hle283/db_services)
 - RSS feed: $source
 - date published: 2024-12-24T13:57:57+00:00

<!-- SC_OFF --><div class="md"><p>Hello all,</p> <p>wondering best practices. I&#39;m planning on running services with DB back end. I am curious on best practices for setup. Should the DB be married to the same container/vm of service requesting or centralize the DB to singular instance for all services to request and attach to?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/calamaricornhole"> /u/calamaricornhole </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hle283/db_services/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hle283/db_services/">[comments]</a></span>

## TUI/CLI portainer/dockge alternative
 - [https://www.reddit.com/r/selfhosted/comments/1hldh5l/tuicli_portainerdockge_alternative](https://www.reddit.com/r/selfhosted/comments/1hldh5l/tuicli_portainerdockge_alternative)
 - RSS feed: $source
 - date published: 2024-12-24T13:24:42+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys, so I&#39;m in search of a docker manager in TUI/CLI that have a docker-compose editor like portainer/dockge, but all that i found is only container/images managers. At them moment i&#39;m managing my docker compose files in Vs Code via ssh, but i want something in the VM and not via SSH.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pedrobuffon"> /u/pedrobuffon </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hldh5l/tuicli_portainerdockge_alternative/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hldh5l/tuicli_portainerdockge_alternative/">[comments]</a></span>

## Recognize mp3 files AI driven
 - [https://www.reddit.com/r/selfhosted/comments/1hld5z3/recognize_mp3_files_ai_driven](https://www.reddit.com/r/selfhosted/comments/1hld5z3/recognize_mp3_files_ai_driven)
 - RSS feed: $source
 - date published: 2024-12-24T13:06:52+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, </p> <p>don&#39;t know why I&#39;ve decided to put order in a directory where I have several files MP3, that I don&#39;t know.</p> <p>Apart MusicBrainz, does anybody knows any good selfhosted, AI-driven app, that can put some order in this mess?</p> <p>:)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/leon_1027"> /u/leon_1027 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hld5z3/recognize_mp3_files_ai_driven/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hld5z3/recognize_mp3_files_ai_driven/">[comments]</a></span>

## Audio book stack
 - [https://www.reddit.com/r/selfhosted/comments/1hld2p7/audio_book_stack](https://www.reddit.com/r/selfhosted/comments/1hld2p7/audio_book_stack)
 - RSS feed: $source
 - date published: 2024-12-24T13:01:36+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, I am currently looking for a way to search and read audiobooks. For information I am a fan of my current stack on the film / series side; I use Plex (PlexPass), sonarr, radarr, prowlarr and overseerr. Do you have any suggestions for me? Would the Plexamp app allow me to read audiobooks on iOS ? On the other hand I would like a reading application allowing to turn off / stop automatically after X minutes defined before reading compatible with iOS. Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/flodes80"> /u/flodes80 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hld2p7/audio_book_stack/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hld2p7/audio_book_stack/">[comments]</a></span>

## Proxmox VE repositories, apt, apt-get, upgrade, full-upgrade, dist-upgrade, pveupgrade
 - [https://www.reddit.com/r/selfhosted/comments/1hlcns9/proxmox_ve_repositories_apt_aptget_upgrade](https://www.reddit.com/r/selfhosted/comments/1hlcns9/proxmox_ve_repositories_apt_aptget_upgrade)
 - RSS feed: $source
 - date published: 2024-12-24T12:35:14+00:00

<!-- SC_OFF --><div class="md"><blockquote> <p>X-posted from <a href="/r/ProxmoxQA">r/ProxmoxQA</a> Originally published at: <a href="https://free-pmx.github.io/guides/apt-update">https://free-pmx.github.io/guides/apt-update</a></p> </blockquote> <hr/> <p>Proxmox VE ships preset with software package repositories <a href="https://pve.proxmox.com/wiki/Package_Repositories#_repositories_in_proxmox_ve"><sup>1</sup></a> access to which is <em>subject to subscription</em>. Unless you have one, this would leave you without upgrades. Rather than following the elaborate manual editing of files <a href="https://pve.proxmox.com/wiki/Package_Repositories#sysadmin_no_subscription_repo"><sup>2</sup></a> after every new install, you can achieve the same with the following:</p> <h2>No-subscription repositories</h2> <pre><code>source /etc/os-release rm /etc/apt/sources.list.d/* cat &gt; /etc/apt/sources.list.d/pve.list &lt;&lt;&lt; &quot;deb http://download.proxmox.com/debian/pve $VERSION_CODENAME p

## Mattermost/RocketChat (self-hosted) don't work without cloud account
 - [https://www.reddit.com/r/selfhosted/comments/1hlc7q6/mattermostrocketchat_selfhosted_dont_work_without](https://www.reddit.com/r/selfhosted/comments/1hlc7q6/mattermostrocketchat_selfhosted_dont_work_without)
 - RSS feed: $source
 - date published: 2024-12-24T12:04:24+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I&#39;m trying to install a secure voice chat on my Linux server to speak with my wife using end-to-end encryption.</p> <p>I&#39;ve tried Rocket.Chat and Mattermost, but they both require creating a cloud account after the Docker installation is complete!</p> <p>Of course, I can&#39;t rely on any solution that requires the cloud, how can I be sure it will not block me once or act as a man-in-the-middle? I need a truly self-hosted solution.</p> <p>What other app could I use for this? Or do you know how to bypass such requirements for the apps listed above?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/yaaaaaaz"> /u/yaaaaaaz </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlc7q6/mattermostrocketchat_selfhosted_dont_work_without/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlc7q6/mattermostrocketchat_selfhosted_dont_work_without/">[c

## A secure remote desktop & terminal solution using Guacamole + Cloudflare Tunnel
 - [https://www.reddit.com/r/selfhosted/comments/1hlc2cq/a_secure_remote_desktop_terminal_solution_using](https://www.reddit.com/r/selfhosted/comments/1hlc2cq/a_secure_remote_desktop_terminal_solution_using)
 - RSS feed: $source
 - date published: 2024-12-24T11:54:18+00:00

<!-- SC_OFF --><div class="md"><h1>Hey everyone! 👋 I wanted to share a project I&#39;ve been working on that makes remote access to Ubuntu simple and secure.</h1> <h1>What it does:</h1> <ul> <li>Access Ubuntu desktop through your browser (using Guacamole)</li> <li>Web-based terminal access (using TTYD)</li> <li>Everything tunneled through Cloudflare (no exposed ports!)</li> <li>Works on mobile devices too</li> </ul> <h1>Key Features:</h1> <ul> <li>🔒 No open ports needed</li> <li>🌐 Just needs a web browser</li> <li>📱 Mobile-friendly</li> <li>🔑 Separate auth for GUI/terminal</li> <li>🚀 Fast connection through Cloudflare&#39;s network</li> </ul> <h1>Tech Stack:</h1> <ul> <li>Apache Guacamole</li> <li>VNC (x11vnc + Xvfb)</li> <li>TTYD for terminal</li> <li>Cloudflare Tunnel</li> <li>XFCE Desktop</li> </ul> <h1>Check it out --&gt;</h1> <p><a href="https://github.com/prakash-aryan/guacamole-cloudflare-tunnel.git">guacamole-cloudflare-tunnel</a></p> <h1>Please make sure to leave a ⭐</h1> </

## what appened to dockge?
 - [https://www.reddit.com/r/selfhosted/comments/1hlbpr2/what_appened_to_dockge](https://www.reddit.com/r/selfhosted/comments/1hlbpr2/what_appened_to_dockge)
 - RSS feed: $source
 - date published: 2024-12-24T11:29:05+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, when it first appeared here I immidiately stared to use dockge, and it still works great to manage multiple docker instances on different lxcs on my proxmox server, but is it me or it wasn&#39;t updated for a while now?<br/> Do anyone know what&#39;s happening or did I miss some info about it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Major-Dragonfruit-72"> /u/Major-Dragonfruit-72 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlbpr2/what_appened_to_dockge/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hlbpr2/what_appened_to_dockge/">[comments]</a></span>

## Reverse proxy on Synology DSM 7.2 accessible with tailnet ip
 - [https://www.reddit.com/r/selfhosted/comments/1hlaz2j/reverse_proxy_on_synology_dsm_72_accessible_with](https://www.reddit.com/r/selfhosted/comments/1hlaz2j/reverse_proxy_on_synology_dsm_72_accessible_with)
 - RSS feed: $source
 - date published: 2024-12-24T10:34:44+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>Im running into issues with the default port allocation of ports 80 and 443 on DSM 7.2.</p> <p>I have several dockerised services running on my Synology NAS at home, which I’d like to access via URLs like paperless.home.example.com, whenever connected to my tailnet.</p> <p>On Cloudflare I’ve configured part of my domain (*.home.example.com) to point to the Synology ip within my tailnet, where I have nginx proxy manager (NPM) listening on ports 40443 and 40080.</p> <p>My issue is that with DSM 7.2, I can no longer have NPM listening on ports 80 and 443 (hence the 40XXX ports). There’s some solutions that I see:</p> <ol> <li>Do some Synology voodoo magic by override Synology’s allocation of the ports through ssh, like this post: <a href="https://www.reddit.com/r/synology/comments/ahs3xh/prevent_dsm_listening_on_port_80443/">https://www.reddit.com/r/synology/comments/ahs3xh/prevent_dsm_listening_on_port_80443/</a></li> <li>Run the NPM on 

## [Question] Owncloud OCIS Missing or Invalid config error fix?
 - [https://www.reddit.com/r/selfhosted/comments/1hlafny/question_owncloud_ocis_missing_or_invalid_config](https://www.reddit.com/r/selfhosted/comments/1hlafny/question_owncloud_ocis_missing_or_invalid_config)
 - RSS feed: $source
 - date published: 2024-12-24T09:55:00+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hlafny/question_owncloud_ocis_missing_or_invalid_config/"> <img src="https://b.thumbs.redditmedia.com/UBaVhO33SgGXUfkByJ-_k0sDZTkoq4yq_JwpNjlcJRY.jpg" alt="[Question] Owncloud OCIS Missing or Invalid config error fix? " title="[Question] Owncloud OCIS Missing or Invalid config error fix? " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I followed the official documentation of the OCIS but I can&#39;t access the webUl page, by visiting the OCIS URL (https://ip:9200) cause the config.json is missing, any fix? I am using docker compose to deploy it. After running the first initial command to create the ocis.yaml including the admin pass etc.., I specified the Volumes as the second pic, that&#39;s what I understood from the docs.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MKBUHD"> /u/MKBUHD </a> <br/> <span><a href="https://www.reddit.com/gallery/1hlafny">[link]</a></s

## intercept internet traffic - LAN
 - [https://www.reddit.com/r/selfhosted/comments/1hla37w/intercept_internet_traffic_lan](https://www.reddit.com/r/selfhosted/comments/1hla37w/intercept_internet_traffic_lan)
 - RSS feed: $source
 - date published: 2024-12-24T09:29:16+00:00

<!-- SC_OFF --><div class="md"><p>Hi</p> <p>I suspect that a certain device in the LAN network is uploading/downloading a lot of data, since my Internet is completely down at certain times (it just freezes). I use Adguard Home and I see spikes there too. I would like to find out which device this is and what exactly it does to or from the Internet.</p> <p>Unfortunately I can&#39;t do this with Adguard itself, I see the spike but can&#39;t filter on those moments and I also can&#39;t see what it does exactly in terms of data.</p> <p>Is it possible to intercept internet traffic, with devices that use the same LAN network? something I can host myself?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Character_Big8879"> /u/Character_Big8879 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hla37w/intercept_internet_traffic_lan/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hla37w/intercept

## Advice - stick with Google or move entirely to Nextcloud/Immich etc?
 - [https://www.reddit.com/r/selfhosted/comments/1hl9r46/advice_stick_with_google_or_move_entirely_to](https://www.reddit.com/r/selfhosted/comments/1hl9r46/advice_stick_with_google_or_move_entirely_to)
 - RSS feed: $source
 - date published: 2024-12-24T09:02:50+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>As per title, I currently have a 10TB plan with Google which is paid for by work as I traditionally have used Google photos/drive for work purposes almost exclusively.</p> <p>I also have a 50TB server on which I have Nextcloud installed in a docker container. I also have Immich for photo storage which works great - no issue here beyond the lack of fun features that Google has rolled out in recent years.</p> <p>I think my question is how did you guys find the transition from Google/Dropbox etc to Nextcloud/equivalent?</p> <p>One issue I am having is the work IT guy was born in I think 1873, and so anything that isn’t Microsoft circa 2012, he believes is witchcraft. Therefore I have been having some issues with the firewall blocking my reverse proxy (nginx) to my server. Is this a certificates issue? I have realised that I have the same issue with WireGuard as well, on the work network, and also some public networks - say 20% of the time

## Small docker-compose only log manager / browser with minimal WebUI to replace Synology Log Server
 - [https://www.reddit.com/r/selfhosted/comments/1hl9bk0/small_dockercompose_only_log_manager_browser_with](https://www.reddit.com/r/selfhosted/comments/1hl9bk0/small_dockercompose_only_log_manager_browser_with)
 - RSS feed: $source
 - date published: 2024-12-24T08:29:48+00:00

<!-- SC_OFF --><div class="md"><p>As in title. </p> <p>I have already looked into Loki, ELK, Greylog but all of them seem to have a lot of config requirements. </p> <p>I am looking for something easier / less complicated - like DSM Log Server.</p> <p>Any recommendations?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/stefanoitaliano_pl"> /u/stefanoitaliano_pl </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hl9bk0/small_dockercompose_only_log_manager_browser_with/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hl9bk0/small_dockercompose_only_log_manager_browser_with/">[comments]</a></span>

## Connect ubuntu server to gateway
 - [https://www.reddit.com/r/selfhosted/comments/1hl8suk/connect_ubuntu_server_to_gateway](https://www.reddit.com/r/selfhosted/comments/1hl8suk/connect_ubuntu_server_to_gateway)
 - RSS feed: $source
 - date published: 2024-12-24T07:50:59+00:00

<!-- SC_OFF --><div class="md"><p>I have a Jellyfin server working on Ubuntu Server 24.04.1. I want to port forward it, however my AT&amp;T router does not list it on the device list. I believe this is something that needs to be configured with iptables, but all web searches return results on how to make the server itself a gateway, not how to connect it to the gateway. I have also tried entering the IP directly into the router panel, and it did not work. Any help would be appreciated!</p> <p>I have port forwarded this exact laptop with other installs, all Fedora Server 41</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Tight-Ad7783"> /u/Tight-Ad7783 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hl8suk/connect_ubuntu_server_to_gateway/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hl8suk/connect_ubuntu_server_to_gateway/">[comments]</a></span>

## Two VPSs at the same time
 - [https://www.reddit.com/r/selfhosted/comments/1hl8aq3/two_vpss_at_the_same_time](https://www.reddit.com/r/selfhosted/comments/1hl8aq3/two_vpss_at_the_same_time)
 - RSS feed: $source
 - date published: 2024-12-24T07:15:01+00:00

<!-- SC_OFF --><div class="md"><p>Hi there,</p> <p>I am looking for a solution which involves the following requirements: - the use of Proxmox LXC or VMs - &quot;force&quot; some LXC/VMs to connect to a wireguard tunnel (such as BitWarden, NextCloud non-exposed services) - &quot;force&quot; some other LXC/VMs to connect to a VPN service (such as Mullvad) to hide my personal IP (the *arr suite and some torrenting)</p> <p>I was thinking about a solution which comprehends two light VPSs (one for &quot;hidden&quot; services with custom Wireguard certificates, the other which connects to Mullvad) and use them as proxies of each Proxmox LXC/VM.</p> <p>Does anyone have better ideas (and possibly the execution steps)?</p> <p>Thank you everyone.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jj_dummy"> /u/jj_dummy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hl8aq3/two_vpss_at_the_same_time/">[link]</a></span> &#32; <span><a h

## VPN server on windows
 - [https://www.reddit.com/r/selfhosted/comments/1hl7mxx/vpn_server_on_windows](https://www.reddit.com/r/selfhosted/comments/1hl7mxx/vpn_server_on_windows)
 - RSS feed: $source
 - date published: 2024-12-24T06:29:25+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I&#39;m looking for recommendations on a VPN server that I can install on my Windows system. I need it to be compatible with my Android devices and other Windows systems. </p> <p>The main thing I&#39;m looking for is simplicity in setup and clear instructions, as I&#39;m not very tech-savvy. If you have suggestions or experiences with any particular VPN server software, I&#39;d greatly appreciate it!</p> <p>Thanks in advance for your help!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/disp06"> /u/disp06 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hl7mxx/vpn_server_on_windows/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hl7mxx/vpn_server_on_windows/">[comments]</a></span>

## How to install docspell?
 - [https://www.reddit.com/r/selfhosted/comments/1hl73d7/how_to_install_docspell](https://www.reddit.com/r/selfhosted/comments/1hl73d7/how_to_install_docspell)
 - RSS feed: $source
 - date published: 2024-12-24T05:52:40+00:00

<!-- SC_OFF --><div class="md"><p>I tried docker compose but after installing the container comes as unhealthy, and it refuses to connect? Can anyone who is already using it guide me how to properly install it in portainer or zimaos?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/helloworldilove69"> /u/helloworldilove69 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hl73d7/how_to_install_docspell/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hl73d7/how_to_install_docspell/">[comments]</a></span>

## 🚀 Automating My Hugo Deployments
 - [https://www.reddit.com/r/selfhosted/comments/1hl6wuw/automating_my_hugo_deployments](https://www.reddit.com/r/selfhosted/comments/1hl6wuw/automating_my_hugo_deployments)
 - RSS feed: $source
 - date published: 2024-12-24T05:41:08+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve written a new blog post outlining how to automate the deployment of my (Hugo-based) blog to a development server using a combination of GitHub Actions, CloudPanel, Cloudflare Tunnel, and Tailscale. </p> <p>My headless Ubuntu server is securely connected via Tailscale, enabling private networking. CloudPanel efficiently manages my web server and applications. Cloudflare Tunnel secures web services without opening inbound ports. Finally, GitHub Actions automates the build and deployment process.</p> <p>By integrating these tools, I&#39;ve streamlined my deployment process, ensuring that my blog updates automatically whenever changes are pushed to my repository. You can read more details in the blog post here: <a href="https://blog.desigeek.com/post/2024/12/automating-hugo-deployments/">https://blog.desigeek.com/post/2024/12/automating-hugo-deployments/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/a

## Local and over-the-internet access to home network
 - [https://www.reddit.com/r/selfhosted/comments/1hl6huy/local_and_overtheinternet_access_to_home_network](https://www.reddit.com/r/selfhosted/comments/1hl6huy/local_and_overtheinternet_access_to_home_network)
 - RSS feed: $source
 - date published: 2024-12-24T05:14:43+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been trying to expose my locally hosted services behind my domain locally and over-the-internet. I plan to use <a href="http://xyz.local.mydomain.com"><code>xyz.local.mydomain.com</code></a> and <a href="http://xyz.mydomain.com"><code>xyz.mydomain.com</code></a> when accessing it from the local network and over-the-internet respectively.</p> <p>I have all the applications running in the Docker containers on a Ubuntu host. I&#39;m using Nginx Proxy Manager (NPM) for reverse proxying the application to the respective domains. </p> <p>I use CloudFlare as my DNS provider for returning the local IP of my Ubuntu host on which Nginx listens on port 80 and 443. This works well for accessing the application locally.</p> <p>However, for accessing them over-the-internet, I am trying to use Tailscale. The problem is, for Nginx to work with Tailscale in the Docker network, I need Nginx and Tailscale to share the network. This doesn&#39;t allow Nginx to l

## 🚀 ClipCascade v1.3.x Released – Elevate Your Clipboard Sync Experience!
 - [https://www.reddit.com/r/selfhosted/comments/1hl61gz/clipcascade_v13x_released_elevate_your_clipboard](https://www.reddit.com/r/selfhosted/comments/1hl61gz/clipcascade_v13x_released_elevate_your_clipboard)
 - RSS feed: $source
 - date published: 2024-12-24T04:46:58+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hl61gz/clipcascade_v13x_released_elevate_your_clipboard/"> <img src="https://external-preview.redd.it/J-sPgRQKSmlrw0oqZjGmoP6zRXlG6D9KLt1ko-j2qS8.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=6058247090b028c572ba078e557a439d756d2204" alt="🚀 ClipCascade v1.3.x Released – Elevate Your Clipboard Sync Experience!" title="🚀 ClipCascade v1.3.x Released – Elevate Your Clipboard Sync Experience!" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey Redditors! 👋</p> <p>I&#39;m thrilled to share that <strong>ClipCascade</strong> has just dropped <strong>version 1.3.x</strong>, bringing significant enhancements to your clipboard synchronization experience.</p> <p>🌟 What&#39;s New?</p> <ul> <li><strong>Image and File Support:</strong> Effortlessly sync <strong>images and files</strong> across <strong>Windows, macOS, Linux,</strong> and <strong>Android</strong> devices.</li> <li><strong>Linux (GUI/CLI) Enhancements:</st

## No longer able to connect via SSH away from Home
 - [https://www.reddit.com/r/selfhosted/comments/1hl5wuh/no_longer_able_to_connect_via_ssh_away_from_home](https://www.reddit.com/r/selfhosted/comments/1hl5wuh/no_longer_able_to_connect_via_ssh_away_from_home)
 - RSS feed: $source
 - date published: 2024-12-24T04:38:58+00:00

<!-- SC_OFF --><div class="md"><p>I have an IOS which I downloaded tailscale on. I also have tailscale running on my nas on my docker which I used docker compose I would like to be able to ssh into my nas away from home using my ios with an app called termius. I use to be able to but once I switched from portainer to docker compose it messed everything up and im pretty sure i used the same type of .yml file</p> <pre><code>services: tailscale: image: tailscale/tailscale:latest container_name: tailscale privileged: true network_mode: &quot;host&quot; # Required for Tailscale to access network interfaces environment: - TS_AUTHKEY= # Replace with a valid auth key from Tailscale admin - TS_ROUTES=192.168.50.0/24 # Advertise a subnet for Tailscale access - TS_SOCKET=/var/lib/tailscale/tailscaled.sock # Specify the socket location # - TS_EXTRA_ARGS=--netfilter-mode=off # Adjust as needed for additional functionality - TS_STATE_DIR=/var/lib/tailscale # Required for persistent state # Optiona

## Continuous Deployment to LAN server
 - [https://www.reddit.com/r/selfhosted/comments/1hl5gz5/continuous_deployment_to_lan_server](https://www.reddit.com/r/selfhosted/comments/1hl5gz5/continuous_deployment_to_lan_server)
 - RSS feed: $source
 - date published: 2024-12-24T04:11:29+00:00

<!-- SC_OFF --><div class="md"><p>I run a couple of public services, some of them on self-hosted servers in my LAN.</p> <p>For the ones that are hosted on a VPS it&#39;s easy to set up CD using Github Actions and SSH keys.</p> <p>For the ones that are self-hosted, I have the repositories on Github but since my server is in my LAN, it&#39;s not clear to me what workflow I should use.</p> <p>The options I&#39;m considering are:</p> <ul> <li>Github CD to LAN server via SSH ports forwarded on the router.</li> <li>Hosting the repository on a self-hosted Gitlab server, making CD to LAN server straightforward, but introducing significant completely to the stack.</li> <li>Abandoning CD and deploying manually.</li> </ul> <p>There are pros and cons to each approach and I&#39;m curious about other setups.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/thekashifmalik"> /u/thekashifmalik </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments

## Easy-Translate: Automated Subtitle Translator Using LLMs and NMT
 - [https://www.reddit.com/r/selfhosted/comments/1hl5ewa/easytranslate_automated_subtitle_translator_using](https://www.reddit.com/r/selfhosted/comments/1hl5ewa/easytranslate_automated_subtitle_translator_using)
 - RSS feed: $source
 - date published: 2024-12-24T04:08:04+00:00

<!-- SC_OFF --><div class="md"><p>Hey <a href="/r/selfhosted">r/selfhosted</a>!</p> <p>I’m excited to share <strong>Easy-Translate</strong>, a project that brings the power of large language models (<strong>LLMs</strong>) and neural machine translation (<strong>NMT</strong>) to subtitle translation.</p> <h1>What Is Easy-Translate?</h1> <p>Easy-Translate is a translation server and CLI designed to handle <code>.srt</code> subtitle files. The translate server supports AI providers like:</p> <ul> <li><strong>OpenAI</strong></li> <li><strong>Amazon Bedrock</strong> (llama models)</li> <li>Any OpenAI-compatible server (e.g., LiteLLM).</li> </ul> <p>The CLI is built to work seamlessly with EasyNMT or any other translation server that supports the EasyNMT API (like the server from Easy-Translate itself).</p> <h1>Key Features</h1> <ul> <li><strong>Server for Translation</strong>: Run your own translation server with an EasyNMT-compatible API.</li> <li><strong>Automatic Language Detection</st

## I want to start self-hosting.
 - [https://www.reddit.com/r/selfhosted/comments/1hl4ktf/i_want_to_start_selfhosting](https://www.reddit.com/r/selfhosted/comments/1hl4ktf/i_want_to_start_selfhosting)
 - RSS feed: $source
 - date published: 2024-12-24T03:18:43+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I want to start self-hosting certain things like media apps, calendar, cloud, dns, etc.</p> <p>I&#39;ve been reading what options there are in terms of software and am already familiar with some of the programs I&#39;ll be using. What I need help with is hardware needed and security. I&#39;m thinking of setting it up with my old laptop and getting a NAS.</p> <p>I&#39;d be gratefull if you could point me in the direction of where can I learn about doing it without leaving my network exposed, and things like would I need a separate router, what to do preemptively in case of power outages, etc.</p> <p>Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AHuilenM1996"> /u/AHuilenM1996 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hl4ktf/i_want_to_start_selfhosting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hl4ktf/i_want_to_start_selfh

## SCP dropping connection even when SSH works normally
 - [https://www.reddit.com/r/selfhosted/comments/1hl4evt/scp_dropping_connection_even_when_ssh_works](https://www.reddit.com/r/selfhosted/comments/1hl4evt/scp_dropping_connection_even_when_ssh_works)
 - RSS feed: $source
 - date published: 2024-12-24T03:09:13+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m setting up a Jellyfin instance on my laptop running Ubuntu Server <code>Ubuntu 24.04.1</code>. I am trying to use <code>scp</code> from my Windows 10 desktop (git bash) to transfer the files. However I consistently get a <code>lost connection</code> error during file transfer (not instant, part of the file transfers before dropping connection). I am currently trying to transfer a <code>3.22 GB</code> file using pubkey authentication, though all files fail at some point using both pubkey and password authentication.</p> <p>With smaller files (tested with ~2 GB file), it will eventually transfer after a few attempts, but it&#39;s up to chance. I need to be able to transfer many large files.</p> <p>I am able to open and maintain an ssh connection with no issue, it never drops connection. My internet connection is perfectly stable. Why might this be happening, and how might I fix this? Any help would be appreciated!</p> </div><!-- SC_ON --> &#32;

## Hotspot Shield VPN ending their support for routers — can I use a network bridge to route traffic from docker apps? If so, how?
 - [https://www.reddit.com/r/selfhosted/comments/1hl4c0o/hotspot_shield_vpn_ending_their_support_for](https://www.reddit.com/r/selfhosted/comments/1hl4c0o/hotspot_shield_vpn_ending_their_support_for)
 - RSS feed: $source
 - date published: 2024-12-24T03:04:36+00:00

<!-- SC_OFF --><div class="md"><p>Title. I got an email that says my VPN provider, Hotspot Shield, is ending their support for router installs, which includes OpenVPN credentials, at the end of the year. </p> <p>This means the applications I have that require a VPN connection will no longer be able to use it. They suggest using the desktop or mobile apps, but my connection is currently being router through docker clients that use ovpn. </p> <p>I use hotspot shield because access is provided at no extra cost through my password manager (Dashlane). I know I can just suck it up and pay for another VPN provider, but there’s got to be a way I can spin up a VM with the client installed and pass specific containers’ traffic through it, right? All the search terms I’m currently trying aren’t that useful because the suggestion is to just use ovpn. Believe me, I would if I could.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mitchsurp"> /u/mitchsurp </a

## 1 day after aiming for 100% uptime for 1 year
 - [https://www.reddit.com/r/selfhosted/comments/1hl3slu/1_day_after_aiming_for_100_uptime_for_1_year](https://www.reddit.com/r/selfhosted/comments/1hl3slu/1_day_after_aiming_for_100_uptime_for_1_year)
 - RSS feed: $source
 - date published: 2024-12-24T02:34:01+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hl3slu/1_day_after_aiming_for_100_uptime_for_1_year/"> <img src="https://preview.redd.it/d3tqm7whkp8e1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=5a3cd435b03f65ba65a0b18e67bbc24ca2781147" alt="1 day after aiming for 100% uptime for 1 year " title="1 day after aiming for 100% uptime for 1 year " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>So the worst happened, a brief power outage because of a family member (haven&#39;t had city one in over 5 years) and because it was so brief that raspberry Pi the server is running on did not reboot properly. </p> <p>So let&#39;s hope 2025 goes better.</p> <p>Currently I&#39;m just running a bit of a test, can a web server (along with some other basic services like this uptime Kuma) run uninterrupted on a raspberry pi. I tried using USB boot but found it to be so slow, it seams to be because the USB controller overheats and throttles, I have even found fast micro 

## Repair tracking program for mechanic
 - [https://www.reddit.com/r/selfhosted/comments/1hl1yc4/repair_tracking_program_for_mechanic](https://www.reddit.com/r/selfhosted/comments/1hl1yc4/repair_tracking_program_for_mechanic)
 - RSS feed: $source
 - date published: 2024-12-24T00:52:38+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a solution for a mechanic that I can host on my own server and that allows the mechanic to create tickets for each repair, that allows adding notes (public and internal if possible) about the repair process and attaching images and that allows customers to see the status of their repairs without having to be registered</p> <p>I&#39;ve been trying different ticket management programs but I can&#39;t find any that fit my needs</p> <p>I hope you know about a solution that can help me, I have a proxmox infrastructure so I can host any type of software</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mesteve123"> /u/mesteve123 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hl1yc4/repair_tracking_program_for_mechanic/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hl1yc4/repair_tracking_program_for_mechanic/">[comments]</a></span>

## Markdown context from Repos, Web, or Youtube
 - [https://www.reddit.com/r/selfhosted/comments/1hl1uy8/markdown_context_from_repos_web_or_youtube](https://www.reddit.com/r/selfhosted/comments/1hl1uy8/markdown_context_from_repos_web_or_youtube)
 - RSS feed: $source
 - date published: 2024-12-24T00:47:49+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hl1uy8/markdown_context_from_repos_web_or_youtube/"> <img src="https://external-preview.redd.it/JmX6FYaVE1ViLrLGC7vBIQB-Pu6KO2xIL24B6rQubPk.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=652246dd916c93a402cc216f74f2279c68749382" alt="Markdown context from Repos, Web, or Youtube" title="Markdown context from Repos, Web, or Youtube" /> </a> </td><td> <!-- SC_OFF --><div class="md"><blockquote> <p>Not really something you can &quot;host&quot; but can be very useful for working with AI as well as those who like data hoarding :)</p> </blockquote> <p>I&#39;ve been writing <a href="https://github.com/tanq16/ai-context">this tool</a> and updated with another feature today. It is a simple binary you can use on CLI to create markdown context from github repos or local code directories or transcript of youtube videos or store a webpage as markdown with local copy of images. </p> <p>everything is stored in a single directo

## Astroluma v1.0.1 Update: New Features & Enhancements!
 - [https://www.reddit.com/r/selfhosted/comments/1hl10ju/astroluma_v101_update_new_features_enhancements](https://www.reddit.com/r/selfhosted/comments/1hl10ju/astroluma_v101_update_new_features_enhancements)
 - RSS feed: $source
 - date published: 2024-12-24T00:03:20+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone!</p> <p>I’m excited to announce the release of <strong>Astroluma v1.0.1</strong>! This update brings a host of new features, bug fixes, and improvements.</p> <h1>What is Astroluma:</h1> <p>Astroluma is a feature-rich, productivity oriented, user-friendly dashboard designed to help you manage multiple aspects of your daily tasks and services. Built with flexibility in mind, it allows you to control various features like task management, device monitoring, app integration, and real-time weather updates, all from a single platform. With its responsive design and dynamic configuration options, Astroluma offers a unique blend of customization, usability, and productivity.</p> <p>Here&#39;s a changelog of what&#39;s new:</p> <h1>Enhancements &amp; Fixes:</h1> <p><strong>Stream Hub:</strong></p> <ul> <li>Resolved mixed content issues – now streaming over SSL is functioning as expected.</li> </ul> <p><strong>TOTP:</strong></p> <ul> <li>Double-cl

