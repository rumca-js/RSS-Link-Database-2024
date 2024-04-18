# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Coturn help needed
 - [https://www.reddit.com/r/selfhosted/comments/1c6nwuj/coturn_help_needed](https://www.reddit.com/r/selfhosted/comments/1c6nwuj/coturn_help_needed)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T22:57:54+00:00

<!-- SC_OFF --><div class="md"><p>So I have been fighting with getting the matrix/synapse up and running in docker. I need to use a coturn setup to get voip working so I got it all setup on my VPS but I just can't seem to get the voip working. Currently when I test it, it does return that the coturn server is working but I just keep getting time out for voip connections. </p> <p>So does anyone know a good place to learn how to do this using docker and get it up and working with voip?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RiffyDivine2"> /u/RiffyDivine2 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6nwuj/coturn_help_needed/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6nwuj/coturn_help_needed/">[comments]</a></span>

## continuous deployment of docker compose sacks from git
 - [https://www.reddit.com/r/selfhosted/comments/1c6nowx/continuous_deployment_of_docker_compose_sacks](https://www.reddit.com/r/selfhosted/comments/1c6nowx/continuous_deployment_of_docker_compose_sacks)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T22:48:35+00:00

<!-- SC_OFF --><div class="md"><p>I have a git repo with subfolders per service containing the compose.yaml and .env files.</p> <p>Something like this:<br /> backbone/<br /> ├─ authentik/<br /> │ ├─ docker-compose.yaml<br /> │ ├─ .env<br /> other_stuff/<br /> ├─ immich/<br /> │ ├─ docker-compose.yaml<br /> │ ├─ .env</p> <p>I currently use Portainer Stacks with GitOps, but it's not great as it seems to only redeploy if the compose.yaml itself changed but not if values in the .env file changed.</p> <p>For example immich has the version set in the .env and changing the version would not result in an auto re-deploy by Portainer.</p> <p>Are there any ready made tools for that?</p> <p>It would have to:</p> <ul> <li>pull from a git server (gitea in my case)</li> <li>check for changes in comopse.yaml or .env files</li> <li>and re-deploy stacks with changes</li> </ul> <p>I looked a bit at jenkins, renovate and drone but from my understanding they are intended for <strong>building</strong> the 

## Proxmox or Ubuntu with Docker?
 - [https://www.reddit.com/r/selfhosted/comments/1c6mzts/proxmox_or_ubuntu_with_docker](https://www.reddit.com/r/selfhosted/comments/1c6mzts/proxmox_or_ubuntu_with_docker)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T22:19:10+00:00

<!-- SC_OFF --><div class="md"><p>I recently got an Intel NUC (11th Gen i7, 32 gigs RAM, 1TB NVMe, 4 Bay DAS) and I'm trying to decide on the best way to set it up. As of right now I plan to migrate my *arr stack from my desktop, qbittorrent, and my plex server. I'd also eventually like to move my Home Assistant and Pi-Hole off of their respective Pi's. I know running HAOS would need a VM so that's why I'm leaning a bit towards proxmox. The other option was run everything in docker containers except the HAOS which would be in a VM.</p> <p>Any recommendations?</p> <p>&#x200b;</p> <p>Edit: Forgot NGINX and Immich will be on there as well</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sweaty-Gopher"> /u/Sweaty-Gopher </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6mzts/proxmox_or_ubuntu_with_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6mzts/proxmox_or_ubuntu_with_docker/"

## What's your full music stack?
 - [https://www.reddit.com/r/selfhosted/comments/1c6mh66/whats_your_full_music_stack](https://www.reddit.com/r/selfhosted/comments/1c6mh66/whats_your_full_music_stack)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T21:58:10+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/RathdrumRain"> /u/RathdrumRain </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6mh66/whats_your_full_music_stack/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6mh66/whats_your_full_music_stack/">[comments]</a></span>

## bypassing DS-Lite
 - [https://www.reddit.com/r/selfhosted/comments/1c6lg0e/bypassing_dslite](https://www.reddit.com/r/selfhosted/comments/1c6lg0e/bypassing_dslite)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T21:15:08+00:00

<!-- SC_OFF --><div class="md"><p>How can I access my Plex on my smart TV outside my network without installing an extra app on it or the router that is outside my network? Basically, hosting something on my Synology NAS, where port 443 and 80 both are blocked by a service on my Synology NAS. The best would be if it was free, but a few dollars a month wont hurt either. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Time-Part9041"> /u/Time-Part9041 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6lg0e/bypassing_dslite/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6lg0e/bypassing_dslite/">[comments]</a></span>

## Attackers exploiting new critical OpenMetadata vulnerabilities on Kubernetes clusters | Microsoft Security Blog
 - [https://www.reddit.com/r/selfhosted/comments/1c6l5ke/attackers_exploiting_new_critical_openmetadata](https://www.reddit.com/r/selfhosted/comments/1c6l5ke/attackers_exploiting_new_critical_openmetadata)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T21:03:08+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c6l5ke/attackers_exploiting_new_critical_openmetadata/"> <img alt="Attackers exploiting new critical OpenMetadata vulnerabilities on Kubernetes clusters | Microsoft Security Blog" src="https://external-preview.redd.it/yGy8Gxd--ipcTPs8Eu6AGwnlj8SU0lvni0WMpJzPDIc.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=f81342d775e01f15f372084605d68247c0d6abe7" title="Attackers exploiting new critical OpenMetadata vulnerabilities on Kubernetes clusters | Microsoft Security Blog" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/redonculous"> /u/redonculous </a> <br /> <span><a href="https://www.microsoft.com/en-us/security/blog/2024/04/17/attackers-exploiting-new-critical-openmetadata-vulnerabilities-on-kubernetes-clusters/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6l5ke/attackers_exploiting_new_critical_openmetadata/">[comments]</a></span> </td></tr>

## Does .tv look stupid for a self-hosted e-mail?
 - [https://www.reddit.com/r/selfhosted/comments/1c6kijm/does_tv_look_stupid_for_a_selfhosted_email](https://www.reddit.com/r/selfhosted/comments/1c6kijm/does_tv_look_stupid_for_a_selfhosted_email)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T20:37:34+00:00

<!-- SC_OFF --><div class="md"><p>Does it look stupid to use a .tv domain for a personal email? My lastname is taken for the major domains such as .com, but .tv is available for my lastname and it would match my initials. An example (not my real name) would be [<a href="mailto:tyson@vaughn.tv">tyson@vaughn.tv</a>](mailto:<a href="mailto:tyson@vaughn.tv">tyson@vaughn.tv</a>)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Otherwise-Recover370"> /u/Otherwise-Recover370 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6kijm/does_tv_look_stupid_for_a_selfhosted_email/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6kijm/does_tv_look_stupid_for_a_selfhosted_email/">[comments]</a></span>

## New Docker Container: LSI Storage Authority (MegaRAID Storage Manager)
 - [https://www.reddit.com/r/selfhosted/comments/1c6jwig/new_docker_container_lsi_storage_authority](https://www.reddit.com/r/selfhosted/comments/1c6jwig/new_docker_container_lsi_storage_authority)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T20:13:05+00:00

<!-- SC_OFF --><div class="md"><p>Hello! I spent a bunch of time struggling with this software over the years so I've decided to Dockerize it and I'm sure that some of you here have had the same issue.</p> <p>If you have a MegaRAID hardware RAID card, you are able to manage it and setup alerts inside of your operating system using either the MegaRAID Storage Manager (MSM) or the newer LSI Storage Authority (LSI). LSA has all of the features of MSM but instead of running a local application for an interface, it uses a web UI. This web UI allows you to manage both local and remote systems such as checking on disks, configuring arrays, rebuilding arrays, and setting up email alerts.</p> <p>Now anyone that has install either of these softwares before knows that they are a minefield of out of date dependencies. <a href="https://hub.docker.com/repository/docker/mecjay12/lsa/general">Well here is your solution!</a>. All rolled up into one container for both standalone deployment and client/s

## Bigcapital - A self-hosted and open source alternative to Quickbooks releases v0.16.0
 - [https://www.reddit.com/r/selfhosted/comments/1c6jrhk/bigcapital_a_selfhosted_and_open_source](https://www.reddit.com/r/selfhosted/comments/1c6jrhk/bigcapital_a_selfhosted_and_open_source)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T20:07:31+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/AdInner8113"> /u/AdInner8113 </a> <br /> <span><a href="https://bigcapital.ly">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6jrhk/bigcapital_a_selfhosted_and_open_source/">[comments]</a></span>

## Reverse proxy questions from a new hoster.
 - [https://www.reddit.com/r/selfhosted/comments/1c6jhrb/reverse_proxy_questions_from_a_new_hoster](https://www.reddit.com/r/selfhosted/comments/1c6jhrb/reverse_proxy_questions_from_a_new_hoster)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T19:57:15+00:00

<!-- SC_OFF --><div class="md"><p>Hey all!<br /> I'm very new to the self hosting scene and sysadmin type stuff in general, so forgive me if this is a dumb set of questions.</p> <p>I currently have an unraid server one of my old computers that i wish to run git, jellyfin, a website, and other services on it in the future (It is already running jellyfish, i just wanted to get all of this set up before doing the rest). I do own a domain as well that i was going to use as entry points for these once the server is exposed to the internet.</p> <p>I have been looking into a reverse proxy to handle all of those as it seems like a cool project, but i have a few concerns that i have been struggling to find answers to in my research.</p> <ol> <li><p>I saw that reverse proxies require ports 80 and 443 forwarded to function correctly. Would this affect all of my network traffic? I live with 3 other people who use the network, 1 of which works remotely so i don't want to violate their privacy or a

## Bypassing Cgnat
 - [https://www.reddit.com/r/selfhosted/comments/1c6jerr/bypassing_cgnat](https://www.reddit.com/r/selfhosted/comments/1c6jerr/bypassing_cgnat)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T19:53:59+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys, so the problem is my ISP is using Cgnat, so I can't port forward, but I would like to access my Plex outside my network. The next problem is it can't be something using and app to connect to a VPN service or something like that because I am trying to do it as simple as possible and I am trying to access the Plex server on a smart TV. I've tried buying a domain + nginx proxy manager, but my Synology where my Plex and nginx proxy manager is located is blocking port 80 and 443 with something. I was also unsuccessful to add my Strato domain to nginx proxy manager. Any help would be appreciated. Also open to other methods, preferably free ones, so I can cancel my subscription to my domain.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/UmpireNo2077"> /u/UmpireNo2077 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6jerr/bypassing_cgnat/">[link]</a></span> &#32; <span><a href="https:/

## Sftp/ssh over Zerotier/tailscale is end to end encrypted?
 - [https://www.reddit.com/r/selfhosted/comments/1c6j14x/sftpssh_over_zerotiertailscale_is_end_to_end](https://www.reddit.com/r/selfhosted/comments/1c6j14x/sftpssh_over_zerotiertailscale_is_end_to_end)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T19:38:53+00:00

<!-- SC_OFF --><div class="md"><p>Please don't flag my post. It. Is related to selfhosting only.</p> <p>My understanding is SFTP/SSH encrypts it's traffic. When it is passed over Zerotier/Tailscale, my guess is those applications also again encrypt the at source and may be decrypts it at the time of handshake in the central node.</p> <p>So does that mean, the data is actually double encrypted 1 layer gets decrypted at the central node and reencrypted and then finally decrypted at destination client. Then the other layer gets decrypted by the SFTP/SSH client</p> <p>This sounds nicely protected with an addon of obscurity.</p> <p>Is my understanding completely BS?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dryEther"> /u/dryEther </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6j14x/sftpssh_over_zerotiertailscale_is_end_to_end/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6j14x/

## traefik+metallb external ip stuck at pending
 - [https://www.reddit.com/r/selfhosted/comments/1c6ik8t/traefikmetallb_external_ip_stuck_at_pending](https://www.reddit.com/r/selfhosted/comments/1c6ik8t/traefikmetallb_external_ip_stuck_at_pending)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T19:19:50+00:00

<!-- SC_OFF --><div class="md"><p>I am running a k3s cluster locally on ubuntu and have made a test deployment of traefik+metallb.</p> <p>Here is the link to the tutorial I am following: <a href="https://technotim.live/posts/kube-traefik-cert-manager-le/#traefik">https://technotim.live/posts/kube-traefik-cert-manager-le/#traefik</a></p> <p>Here's my folder struture:</p> <p><code> . ├── install.sh ├── metallb │ ├── metallb.yaml │ └── values.yaml └── traefik ├── dashboard │ ├── ingress.yaml │ ├── middleware.yaml │ └── secret-dashboard.yaml ├── default-headers.yaml └── values.yaml </code></p> <p>Here's what the the status of the services looks like after deployment:</p> <table><thead> <tr> <th>NAMESPACE</th> <th>NAME</th> <th>TYPE</th> <th>CLUSTER-IP</th> <th>EXTERNAL-IP</th> <th>PORT(S)</th> <th>AGE</th> <th>SELECTOR</th> </tr> </thead><tbody> <tr> <td>default</td> <td>kubernetes</td> <td>ClusterIP</td> <td>10.43.0.1</td> <td>none</td> <td>443/TCP</td> <td>70m</td> <td>none</td> </tr> <

## Backup for private Gmail Synology
 - [https://www.reddit.com/r/selfhosted/comments/1c6i398/backup_for_private_gmail_synology](https://www.reddit.com/r/selfhosted/comments/1c6i398/backup_for_private_gmail_synology)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T19:00:41+00:00

<!-- SC_OFF --><div class="md"><p>Hey, I want to backup my private gmail mails. If I am right there is no direct possibility for private accounts in Synology. But I found the solution over local Thunderbird and the local directory in Synology Drive. I also make a daily backup of Synology drive.</p> <p>Do I miss a thing or is it a good backup solution?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/datatest05"> /u/datatest05 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6i398/backup_for_private_gmail_synology/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6i398/backup_for_private_gmail_synology/">[comments]</a></span>

## Suggestions for OneDrive replacement
 - [https://www.reddit.com/r/selfhosted/comments/1c6hy9o/suggestions_for_onedrive_replacement](https://www.reddit.com/r/selfhosted/comments/1c6hy9o/suggestions_for_onedrive_replacement)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T18:55:10+00:00

<!-- SC_OFF --><div class="md"><p>I am currently running Proxmox for my home server and I would like to stop using Google Drive and OneDrive but I like the ability to sync files. One thing I would love is if I could do that same sync also on my android device. Is there any self hosted solutions that offer something similar?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/managard"> /u/managard </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6hy9o/suggestions_for_onedrive_replacement/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6hy9o/suggestions_for_onedrive_replacement/">[comments]</a></span>

## DNS leak with Gluetun in qBittorrent TrueNAS
 - [https://www.reddit.com/r/selfhosted/comments/1c6gmfg/dns_leak_with_gluetun_in_qbittorrent_truenas](https://www.reddit.com/r/selfhosted/comments/1c6gmfg/dns_leak_with_gluetun_in_qbittorrent_truenas)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T18:01:35+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c6gmfg/dns_leak_with_gluetun_in_qbittorrent_truenas/"> <img alt="DNS leak with Gluetun in qBittorrent TrueNAS" src="https://external-preview.redd.it/V5ut8rYvUFnJBD_FWTA2nL0w5K0I3mjoVI7sW12Pu5Y.jpg?width=108&amp;crop=smart&amp;auto=webp&amp;s=217a78b0368b0888654bee66dbcc6809f3f431ed" title="DNS leak with Gluetun in qBittorrent TrueNAS" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello, I hope I can figure this out with your help. The Gluetun sub is sadly quite small.</p> <p>I run Gluetun with the TrueCharts version of qBittorrent on TrueNAS. ProtonVPN is my VPN Provider and Wireguard is the Protocol.</p> <p>Generally the Tunnel works. When I use <a href="http://ipleak.net/">ipleak.net</a> and I use the torrent-test they provide it get's the IP address of my exit node Provided by ProtonVPN. However, a more extensive test like what <a href="https://www.doileak.com/classic.html">doileak.com/classic.html</a> Pr

## Morphos v0.3.0 is out!
 - [https://www.reddit.com/r/selfhosted/comments/1c6gd4k/morphos_v030_is_out](https://www.reddit.com/r/selfhosted/comments/1c6gd4k/morphos_v030_is_out)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T17:51:28+00:00

<!-- SC_OFF --><div class="md"><p>As the title says <a href="https://github.com/danvergara/morphos">Morphos v.0.3.0</a> is out!</p> <p>Remarkable changes:</p> <ul> <li>XLSX - CSV is now possible!</li> <li>Unipdf was removed in favor of <a href="http://github.com/gen2brain/go-fitz">go-fitz</a></li> </ul> <p>Go check it out!!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dany9126"> /u/dany9126 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6gd4k/morphos_v030_is_out/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6gd4k/morphos_v030_is_out/">[comments]</a></span>

## Minecraft Utilities - A simple and easy to use Minecraft API
 - [https://www.reddit.com/r/selfhosted/comments/1c6g8s9/minecraft_utilities_a_simple_and_easy_to_use](https://www.reddit.com/r/selfhosted/comments/1c6g8s9/minecraft_utilities_a_simple_and_easy_to_use)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T17:46:41+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/ImFascinatedMC"> /u/ImFascinatedMC </a> <br /> <span><a href="/r/opensource/comments/1c6g6tt/minecraft_utilities_a_simple_and_easy_to_use/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6g8s9/minecraft_utilities_a_simple_and_easy_to_use/">[comments]</a></span>

## Netdata Alternatives
 - [https://www.reddit.com/r/selfhosted/comments/1c6g4ph/netdata_alternatives](https://www.reddit.com/r/selfhosted/comments/1c6g4ph/netdata_alternatives)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T17:42:00+00:00

<!-- SC_OFF --><div class="md"><p>With Netdata changing its pricing I'm in need of somthing to monitor unRAID, raspi, debian and my windows machines around the home. Netdata was great due to its easy setup, I have looked at Grafana and whilst it looks impressive its a lot more complex then I need</p> <p>What would be the best free solutions. I only really use it to identify issues, peak usage and trouble shooting.</p> <p>Does anyone have any recommendations and and explanation.</p> <p>Thank you</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Unable_Split_1184"> /u/Unable_Split_1184 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6g4ph/netdata_alternatives/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6g4ph/netdata_alternatives/">[comments]</a></span>

## What devices work well as a Tailscale access point?
 - [https://www.reddit.com/r/selfhosted/comments/1c6ffp4/what_devices_work_well_as_a_tailscale_access_point](https://www.reddit.com/r/selfhosted/comments/1c6ffp4/what_devices_work_well_as_a_tailscale_access_point)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T17:14:18+00:00

<!-- SC_OFF --><div class="md"><p>I work remotely and occasionally do so while traveling. When I do, I connect to the hotel/BnB wifi on my phone, enable Tailscale with my home server as the exit node, and turn on my phone's wifi hotspot. My work laptop then connects to my phone's hotspot, and (afaik) my employer sees that I'm working from my home base.</p> <p>While this approach works well, it is not an ideal solution. Tailscale kills my battery, I can't use ethernet, if I leave with my phone my partner loses wifi, and most importantly I'm using my phone all day and could easily mess up the Tailscale connection by accident.</p> <p>So I'm wondering, what kind of devices are out there that could be used for this purpose? Ideally they would need to connect to a router via ethernet or wifi, funnel all traffic through a Tailscale exit node, and then distribute the network via a wifi hotspot or ethernet.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/

## Today I left the cloud.
 - [https://www.reddit.com/r/selfhosted/comments/1c6eicq/today_i_left_the_cloud](https://www.reddit.com/r/selfhosted/comments/1c6eicq/today_i_left_the_cloud)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T16:36:48+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c6eicq/today_i_left_the_cloud/"> <img alt="Today I left the cloud." src="https://b.thumbs.redditmedia.com/QgU7SJEmaspCQCuNPbfEfD7OXPAFf3sK3G43tBax0sw.jpg" title="Today I left the cloud." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/q3431l4u4984no"> /u/q3431l4u4984no </a> <br /> <span><a href="https://www.reddit.com/gallery/1c6eicq">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6eicq/today_i_left_the_cloud/">[comments]</a></span> </td></tr></table>

## Small Puzzle/Quiz Game to Selfhost
 - [https://www.reddit.com/r/selfhosted/comments/1c6do1h/small_puzzlequiz_game_to_selfhost](https://www.reddit.com/r/selfhosted/comments/1c6do1h/small_puzzlequiz_game_to_selfhost)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T16:03:59+00:00

<!-- SC_OFF --><div class="md"><p>Are there any selfhostable puzzle/quiz games which can be modified to adjust it for my own needs?</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Furki1907"> /u/Furki1907 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6do1h/small_puzzlequiz_game_to_selfhost/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6do1h/small_puzzlequiz_game_to_selfhost/">[comments]</a></span>

## Casting to a Pi 4
 - [https://www.reddit.com/r/selfhosted/comments/1c6dev1/casting_to_a_pi_4](https://www.reddit.com/r/selfhosted/comments/1c6dev1/casting_to_a_pi_4)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T15:54:22+00:00

<!-- SC_OFF --><div class="md"><p>Recently, the casting on my smart TV crapped out, and the casting options on my firestick are crap. I've played around with Kodi/Libreelec as an alternative to the firestick, but it seems like getting it to full functionality is more hassle than it's worth for me. I'd really like to get some form of casting/screen mirroring functional on my TV, but I'm having trouble finding the simplest way to do it with my Pi 4. I'm willing to have the Pi set up as a dedicated mirroring box—that's all I need it to do for now. If anyone has any insight into how I can go about this, please let me know!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RayJZ"> /u/RayJZ </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6dev1/casting_to_a_pi_4/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6dev1/casting_to_a_pi_4/">[comments]</a></span>

## JustDeploy Update: Simplifying Database Setup for Your Applications
 - [https://www.reddit.com/r/selfhosted/comments/1c6dbbs/justdeploy_update_simplifying_database_setup_for](https://www.reddit.com/r/selfhosted/comments/1c6dbbs/justdeploy_update_simplifying_database_setup_for)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T15:50:19+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I'm back with an update on JustDeploy, the open source project <a href="https://www.reddit.com/r/selfhosted/comments/1bb74gy/introducing_justdeploy_an_open_source_alternative/">I introduced a few weeks ago that aims to simplify the deployment process for developers</a>. In case you missed it, JustDeploy is an alternative to platforms like Vercel and Heroku, but with a focus on deploying Dockerfiles directly to your own server.</p> <p>Today, <a href="https://twitter.com/ChalopinClement/status/1780591503812813162">I'm excited to announce that JustDeploy now supports the creation and connection of database services for your application</a>. This means that you can easily create a database service from preconfigured options or from your own docker-compose config, and connect it to your application during deployment. This feature makes it even easier to deploy your application and manage its dependencies.</p> <p>JustDeploy handles th

## Best LLM for self hosting (AWS or Google Cloud) for data analysis
 - [https://www.reddit.com/r/selfhosted/comments/1c6bdnp/best_llm_for_self_hosting_aws_or_google_cloud_for](https://www.reddit.com/r/selfhosted/comments/1c6bdnp/best_llm_for_self_hosting_aws_or_google_cloud_for)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T14:31:00+00:00

<!-- SC_OFF --><div class="md"><p>I want to host my LLM to analyze customer sales data (e-commerce) and their Google Search Data. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/brentwpeterson"> /u/brentwpeterson </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6bdnp/best_llm_for_self_hosting_aws_or_google_cloud_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6bdnp/best_llm_for_self_hosting_aws_or_google_cloud_for/">[comments]</a></span>

## Vodafone Home Broadband for email
 - [https://www.reddit.com/r/selfhosted/comments/1c6antu/vodafone_home_broadband_for_email](https://www.reddit.com/r/selfhosted/comments/1c6antu/vodafone_home_broadband_for_email)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T14:01:37+00:00

<!-- SC_OFF --><div class="md"><p>Hello! I was just wondering if anyone had had experience with using Vodafone home broadband to host their email servers? I understand that you need a PTR record to have services like Gmail not flag you as spam, so I am wondering if anyone has managed to get this? I am trying to work towards that, but a bit difficult to understand any clear path on their forums. Thanks!!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/alicethefemme"> /u/alicethefemme </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6antu/vodafone_home_broadband_for_email/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6antu/vodafone_home_broadband_for_email/">[comments]</a></span>

## self-hosted like OneDrive - multiple users edit spreadsheets/docs
 - [https://www.reddit.com/r/selfhosted/comments/1c6akw0/selfhosted_like_onedrive_multiple_users_edit](https://www.reddit.com/r/selfhosted/comments/1c6akw0/selfhosted_like_onedrive_multiple_users_edit)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T13:58:32+00:00

<!-- SC_OFF --><div class="md"><p>The main thing I need to get off OneDrive is the ability to have docs that are edited by multiple people. After reading quite a bit, I've bought a Terramaster F4-424, plan to use Nextcloud. If someone could shove me a little further than that in the right direction would be greatly appreciated. Also very concerned about privacy and blocking all the appliances and cars and other malware in my house from phoning home and that sort of thing. </p> <p>I'm also about to put in a new router with OpenWRT if any ideas to integrate it all.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FHLudlow"> /u/FHLudlow </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6akw0/selfhosted_like_onedrive_multiple_users_edit/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6akw0/selfhosted_like_onedrive_multiple_users_edit/">[comments]</a></span>

## Kimai alternatives? Developer is an entitled Dbag
 - [https://www.reddit.com/r/selfhosted/comments/1c6ahpx/kimai_alternatives_developer_is_an_entitled_dbag](https://www.reddit.com/r/selfhosted/comments/1c6ahpx/kimai_alternatives_developer_is_an_entitled_dbag)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T13:54:38+00:00

<!-- SC_OFF --><div class="md"><p>I've used and interacted with many open-source self-hosted tools and the majority of it has been great. Some shoutouts go to Dan Brown with Bookstack and Alex from Immich who have both been absolutely fantastic to deal with in reporting bugs, feature requests and general troubleshooting. Massive props to Dan especially who's helped answer countless questions and scenarios across Youtube and GitHub.</p> <p>What I don't get is some devs who's main income comes from their SaaS products and are complete assholes everytime you open an issue, or feature request.I've recently transitioned a startup company I work for into using Kimai for time entry over quickbooks which is outdated feature lacking.</p> <p>Kimai itself has been mostly great, but everytime I have interacted with its developer Kevin Papst, aka kevinpapst (github), he's been an absolute asshat, firing shots, then closing issues/features. In my most recent interaction, I was trying to see if it w

## What apps do you use from music?
 - [https://www.reddit.com/r/selfhosted/comments/1c6afrf/what_apps_do_you_use_from_music](https://www.reddit.com/r/selfhosted/comments/1c6afrf/what_apps_do_you_use_from_music)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T13:52:15+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/RathdrumRain"> /u/RathdrumRain </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6afrf/what_apps_do_you_use_from_music/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c6afrf/what_apps_do_you_use_from_music/">[comments]</a></span>

## Syncing videos to super old ipad
 - [https://www.reddit.com/r/selfhosted/comments/1c69s4t/syncing_videos_to_super_old_ipad](https://www.reddit.com/r/selfhosted/comments/1c69s4t/syncing_videos_to_super_old_ipad)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T13:24:15+00:00

<!-- SC_OFF --><div class="md"><p>Hi y'all</p> <p>I have an ipad 4 which i'd like to use just to watch videos on. It's got a good screen and still decent battery life. It can't be upgraded beyond iOS 10 so the selection of apps is pretty limited, everything I would normally use (nextcloud, jellyfin, syncthing etc) needs iOS 12 or later basically.</p> <p>VLC works to play videos, but I'm struggling to find a way to transfer / sync videos from my collection</p> <p>Any ideas? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/schistosomnia"> /u/schistosomnia </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c69s4t/syncing_videos_to_super_old_ipad/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c69s4t/syncing_videos_to_super_old_ipad/">[comments]</a></span>

## Best way to store receipts
 - [https://www.reddit.com/r/selfhosted/comments/1c69qou/best_way_to_store_receipts](https://www.reddit.com/r/selfhosted/comments/1c69qou/best_way_to_store_receipts)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T13:22:31+00:00

<!-- SC_OFF --><div class="md"><p>I'm looking to store mainly medical receipts for personal HSA records reasons...is there any self-hosted app or organizing software that is made for storing/organizing receipts that people round here like?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/glibbertarian"> /u/glibbertarian </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c69qou/best_way_to_store_receipts/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c69qou/best_way_to_store_receipts/">[comments]</a></span>

## Apache Guacamole Docker Customisation
 - [https://www.reddit.com/r/selfhosted/comments/1c69diq/apache_guacamole_docker_customisation](https://www.reddit.com/r/selfhosted/comments/1c69diq/apache_guacamole_docker_customisation)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T13:07:04+00:00

<!-- SC_OFF --><div class="md"><p>Hi everybody.<br /> I have a guacamole instance running in docker and want to customize the login screen.<br /> I think doing it with .jar based theme would be the easiest for me ( <a href="https://github.com/Zer0CoolX/guacamole-customize-loginscreen-extension">https://github.com/Zer0CoolX/guacamole-customize-loginscreen-extension</a> ).</p> <p>But i am a beginner to docker containers and i am wondering how the hell i am getting this jar file onto the container.<br /> Docker is running on debian as an proxmox lxc container. Also running portainer on same instance.</p> <p>I appreciate every bit of help!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JD6530"> /u/JD6530 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c69diq/apache_guacamole_docker_customisation/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c69diq/apache_guacamole_docker_customisation

## I've moved from Plex/Plexamp to Jellyfin/Finamp, one of the main things I'm missing is popular tracks. Is there a way to get these with Jellyfin?
 - [https://www.reddit.com/r/selfhosted/comments/1c68h56/ive_moved_from_plexplexamp_to_jellyfinfinamp_one](https://www.reddit.com/r/selfhosted/comments/1c68h56/ive_moved_from_plexplexamp_to_jellyfinfinamp_one)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T12:24:14+00:00

<!-- SC_OFF --><div class="md"><p>In Plexamp there was a section with popular tracks for an artist and for an album (I think this comes from LastFM), is there any alternative that can replicate this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Zestyclose_Car1088"> /u/Zestyclose_Car1088 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c68h56/ive_moved_from_plexplexamp_to_jellyfinfinamp_one/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c68h56/ive_moved_from_plexplexamp_to_jellyfinfinamp_one/">[comments]</a></span>

## Podcast Catcher?
 - [https://www.reddit.com/r/selfhosted/comments/1c67z83/podcast_catcher](https://www.reddit.com/r/selfhosted/comments/1c67z83/podcast_catcher)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T11:58:49+00:00

<!-- SC_OFF --><div class="md"><p>What are people using for podcast catchers these days? I want to be able to input RSS feeds and point it at a folder, and then be able to look into that folder to see all the MP3s of episodes as they come out. Basically Sonarr but for podcasts.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RecursionIsRecursion"> /u/RecursionIsRecursion </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c67z83/podcast_catcher/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c67z83/podcast_catcher/">[comments]</a></span>

## A good self-hostable CMS (or DMS) for sharing datasets with the world?
 - [https://www.reddit.com/r/selfhosted/comments/1c67ys4/a_good_selfhostable_cms_or_dms_for_sharing](https://www.reddit.com/r/selfhosted/comments/1c67ys4/a_good_selfhostable_cms_or_dms_for_sharing)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T11:58:10+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys,</p> <p>Thought I would poll the sub to see if anybody has come across any projects or scripts that I've missed.</p> <p>I'm looking into setting up a website for sharing datasets and data visualisations with the world (at large). Open access data and all that perhaps with some bells and whistles like visualisations based on live datasets. Not that it matters (except perhaps for licensing) but a non-profit initiative. Think something like Kaggle minus the social network side of it.</p> <p>I've been looking through all the obvious choices and having a hard time finding something that's reasonably user-friendly. There's CKAN and DKAN (a Drupal add-on). Also the Invenio framework by CERN. And a few others that can be found with keyword searches. To generalise only a little, they're all big and rather complicated engines really intended for government use.</p> <p>I'm looking for something a lot more straighforward. On the backend, I'd like to creat

## Self Hosted DNS Server (using adguard home on Home Assistant) response time is slow, how to speed up?
 - [https://www.reddit.com/r/selfhosted/comments/1c67u6j/self_hosted_dns_server_using_adguard_home_on_home](https://www.reddit.com/r/selfhosted/comments/1c67u6j/self_hosted_dns_server_using_adguard_home_on_home)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T11:51:11+00:00

<!-- SC_OFF --><div class="md"><p>I've set up home assistant on an Odroid XU4 with Adguard Home acting as my dns server. I've noticed that the response time in ms is around 2000....How do I speed this up? All Router traffic goes through this on the 192.168.1.x DNS server address...</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/_pvnda"> /u/_pvnda </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c67u6j/self_hosted_dns_server_using_adguard_home_on_home/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c67u6j/self_hosted_dns_server_using_adguard_home_on_home/">[comments]</a></span>

## Self hosted PDF/document organizer with maybe OCR/searchability ?
 - [https://www.reddit.com/r/selfhosted/comments/1c671qu/self_hosted_pdfdocument_organizer_with_maybe](https://www.reddit.com/r/selfhosted/comments/1c671qu/self_hosted_pdfdocument_organizer_with_maybe)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T11:07:26+00:00

<!-- SC_OFF --><div class="md"><p>I already know Paperless, which didn't excite me a few years back. Now I find myself needing something like that again, for private/family use only, and I am wondering, anything you guys would recommend/warn against ?</p> <p>I am looking for something with a minimum feature set of:</p> <ul> <li>Upload, store, search, organize and download PDFs primarily but also .docx, .txt etc</li> <li>Something that can be used from mobile (reactive web interface is okay I guess)</li> <li>Something that supports minimal user/permission functionality so I can run it for my family without my aunt being able to download my employment contract</li> <li>Some at least basic local OCR that allows me to search PDFs/scans for context. Doesn't need to be fancy or perfect, but enough that I can search for documents with reasonable success</li> <li>Be secure enough that it can be internet facing</li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddi

## A quick meme, if I may
 - [https://www.reddit.com/r/selfhosted/comments/1c66u24/a_quick_meme_if_i_may](https://www.reddit.com/r/selfhosted/comments/1c66u24/a_quick_meme_if_i_may)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T10:55:13+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c66u24/a_quick_meme_if_i_may/"> <img alt="A quick meme, if I may" src="https://preview.redd.it/sxqegf12t0vc1.jpeg?width=320&amp;crop=smart&amp;auto=webp&amp;s=c557ca2b5b8cce57f7b13fb47fe628514774ef46" title="A quick meme, if I may" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/danielrosehill"> /u/danielrosehill </a> <br /> <span><a href="https://i.redd.it/sxqegf12t0vc1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c66u24/a_quick_meme_if_i_may/">[comments]</a></span> </td></tr></table>

## Pi.Alert is dead...💀 Long live NetAlert X 🚀
 - [https://www.reddit.com/r/selfhosted/comments/1c664ai/pialert_is_dead_long_live_netalert_x](https://www.reddit.com/r/selfhosted/comments/1c664ai/pialert_is_dead_long_live_netalert_x)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T10:10:25+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c664ai/pialert_is_dead_long_live_netalert_x/"> <img alt="Pi.Alert is dead...💀 Long live NetAlert X 🚀" src="https://external-preview.redd.it/MnqqnY46lUrDlwJEH3J_hBDF2tl1OTlgUBnHfjJc-2Y.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=610226a290551afc83b7dfaf10d33cde0b4530aa" title="Pi.Alert is dead...💀 Long live NetAlert X 🚀" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jokob"> /u/jokob </a> <br /> <span><a href="https://github.com/jokob-sk/NetAlertX/releases/tag/v24.4.17">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c664ai/pialert_is_dead_long_live_netalert_x/">[comments]</a></span> </td></tr></table>

## Has anyone setup Roundcube to use local folders only?
 - [https://www.reddit.com/r/selfhosted/comments/1c662ps/has_anyone_setup_roundcube_to_use_local_folders](https://www.reddit.com/r/selfhosted/comments/1c662ps/has_anyone_setup_roundcube_to_use_local_folders)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T10:07:39+00:00

<!-- SC_OFF --><div class="md"><p>After a similar post I made last year, querying email archiving - I'm still looking for a solution.</p> <p>I'm trying to setup a kind-of Thunderbird WebUI to store and search my archived emails. It'll be offline, so no need for fetch emails. I just want a WebUI that I can dump .emls into, then full text search.</p> <p>Spider Email Archiver looked great, but I'm not paying a yearly fee to just search my emails.</p> <p>I got Roundcube setup, but can't get past the need to authenticate to a mailserver.</p> <p>Is it possible to configure Roundcube in a &quot;local only&quot; mode?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FluffyMumbles"> /u/FluffyMumbles </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c662ps/has_anyone_setup_roundcube_to_use_local_folders/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c662ps/has_anyone_setup_roundcube_to_use_local

## Am I using Portainer correctly?
 - [https://www.reddit.com/r/selfhosted/comments/1c65xj1/am_i_using_portainer_correctly](https://www.reddit.com/r/selfhosted/comments/1c65xj1/am_i_using_portainer_correctly)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T09:58:44+00:00

<!-- SC_OFF --><div class="md"><p>So as I've moved along my magical selfhosted journey I've repurposed my old PC as a server.</p> <p>I've got Prox mox running on it, and I've been creating a new LXC to handle each of the docker services that I've been adding to the machine.</p> <p>I've been adding portainer to each LXC + whatever I actually want to be hosting.</p> <p>This is turning into a huge pain trying to maintain, is there a way I can get 1 or 2 instances of portainer to look after multiple LXC's? </p> <p>Or is there another way I should be doing this entirely? </p> <p>I'd got comfortable with using container manager on my synology for easily updating each docker and was hoping to do the same with portainer but logging in and out of each portainer instance is annoying. I must be doing something silly right?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Haliphone"> /u/Haliphone </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/

## Lightweight linux control panel to manage nginx/php sites
 - [https://www.reddit.com/r/selfhosted/comments/1c65r70/lightweight_linux_control_panel_to_manage](https://www.reddit.com/r/selfhosted/comments/1c65r70/lightweight_linux_control_panel_to_manage)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T09:46:14+00:00

<!-- SC_OFF --><div class="md"><p>I have been so far manually creating nginx/php-fpm configs for the sites I host. Is there a light weight control panel UI that can do the same stuff?</p> <ul> <li>Add/Edit nginx sites</li> <li>Choose individual php-fpm version for each site</li> </ul> <p>Tried Nginx Proxy Manager, but it only forwards/proxies to another server. It doesn't have PHP settings that I can specify.</p> <p>Also, cannot dockerize my apps.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/guydrukpa"> /u/guydrukpa </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c65r70/lightweight_linux_control_panel_to_manage/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c65r70/lightweight_linux_control_panel_to_manage/">[comments]</a></span>

## Pretty sure its not an issue, but wanted to check. Are Docker and LXC images potential tojans for XZ ?
 - [https://www.reddit.com/r/selfhosted/comments/1c654ms/pretty_sure_its_not_an_issue_but_wanted_to_check](https://www.reddit.com/r/selfhosted/comments/1c654ms/pretty_sure_its_not_an_issue_but_wanted_to_check)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T09:02:31+00:00

<!-- SC_OFF --><div class="md"><p>Fairly sure that they are not, as containers use the underlying OS. if the underlying OS has XZ then yes it would be a problem but if it doesn't they're safe...</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/senectus"> /u/senectus </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c654ms/pretty_sure_its_not_an_issue_but_wanted_to_check/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c654ms/pretty_sure_its_not_an_issue_but_wanted_to_check/">[comments]</a></span>

## Remote access to service in internal network. VPN?
 - [https://www.reddit.com/r/selfhosted/comments/1c64yac/remote_access_to_service_in_internal_network_vpn](https://www.reddit.com/r/selfhosted/comments/1c64yac/remote_access_to_service_in_internal_network_vpn)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T08:50:41+00:00

<!-- SC_OFF --><div class="md"><p>So here is the deal, I have a service in my internal network which I access through my internal reverse proxy (nginx) through a subdomain (service.internaldomain.lan). I would like to access this service from a remote server so it can report back some data. This server is not under my direct control but I have full SSH access to it.</p> <p>My first idea was to use a VPN, but that poses a threat because if the remote server was compromised a hacker could get access to the VPN keys and therefore have access to my internal network, which is a nono.</p> <p>I also dont want to expose the service to the web cause I dont want to create more subdomains than necessary in my public facing domain.</p> <p>The ideal solution is a VPN connection that can ONLY access the service that I want, so in case of a hacker getting access it would only be able to access this service and not my entire network.</p> <p>I have'nt used VPN much but I see they are very popular here

## Homepage - Catppuccin theme & 1700+ themed dashboard icons.
 - [https://www.reddit.com/r/selfhosted/comments/1c64y5b/homepage_catppuccin_theme_1700_themed_dashboard](https://www.reddit.com/r/selfhosted/comments/1c64y5b/homepage_catppuccin_theme_1700_themed_dashboard)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T08:50:26+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c64y5b/homepage_catppuccin_theme_1700_themed_dashboard/"> <img alt="Homepage - Catppuccin theme &amp; 1700+ themed dashboard icons." src="https://preview.redd.it/d48o8k0o60vc1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=af46f64c08c99c34e33355fad53c70934de6ae35" title="Homepage - Catppuccin theme &amp; 1700+ themed dashboard icons." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Jazkyr"> /u/Jazkyr </a> <br /> <span><a href="https://i.redd.it/d48o8k0o60vc1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c64y5b/homepage_catppuccin_theme_1700_themed_dashboard/">[comments]</a></span> </td></tr></table>

## How to use our non profit domain name instead of server ip for Cal and other apps?
 - [https://www.reddit.com/r/selfhosted/comments/1c64wnm/how_to_use_our_non_profit_domain_name_instead_of](https://www.reddit.com/r/selfhosted/comments/1c64wnm/how_to_use_our_non_profit_domain_name_instead_of)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T08:47:37+00:00

<!-- SC_OFF --><div class="md"><p>For Cal our calendar invite email is similar to <a href="http://24.54.32.54/mycalendar">http://24.54.32.54/mycalendar</a> which looks unprofessional and also scammy</p> <p>I know we can use a miniurl service but would prefer another option since we would have to do that for each volunteer that would have a booking link</p> <p>When a user makes an account on Cal they would get their booking link which would have the server IP in it, is there a way to just permanently change it in there, so our volunteers never look at our IP?</p> <p>If not, is there a free/ cheap way to cloak the IP that for Cal and other apps we have self hosted on our oracle server?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/xboxhaxorz"> /u/xboxhaxorz </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c64wnm/how_to_use_our_non_profit_domain_name_instead_of/">[link]</a></span> &#32; <span><a href="https://www.reddit.com

## My mail solution
 - [https://www.reddit.com/r/selfhosted/comments/1c64qov/my_mail_solution](https://www.reddit.com/r/selfhosted/comments/1c64qov/my_mail_solution)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T08:35:47+00:00

<!-- SC_OFF --><div class="md"><p>I'm trying to host my mail solution, bought a new domain name for my business, and am trying to control everything by creating my email using CyberPanel.<br /> I want to make the following emails:<br /> support, info, sales, no-replay, and some personal ones.</p> <p>What are the best ways to host this CyberPanel VPS, VDS, or web hosting?<br /> are there any better panels better than CyberPanel?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Glitch-spino"> /u/Glitch-spino </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c64qov/my_mail_solution/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c64qov/my_mail_solution/">[comments]</a></span>

## Ingress/Nginx does not forward client ip address
 - [https://www.reddit.com/r/selfhosted/comments/1c64fwl/ingressnginx_does_not_forward_client_ip_address](https://www.reddit.com/r/selfhosted/comments/1c64fwl/ingressnginx_does_not_forward_client_ip_address)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T08:14:13+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I use Nginx Ingress and forward the traffic to another Nginx proxy service.</p> <p>I have the following configuration in the Nginx proxy service:</p> <pre><code> ... http { ... server { listen 8080 default_server; server_name _; location / { real_ip_header X-Forwarded-For; proxy_set_header X-Real-IP $remote_addr; proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for; proxy_set_header X-Forwarded-Host $server_name; proxy_pass http://my-service:8000/; } ... } } </code></pre> <p>My problem is that the IP address of the client is not in the X-Forwarded-For header.</p> <p>When I read the header in a service behind the Nginx proxy service, it looks like this: '127.0.0.1, 10.2.2.37'. Where 10.2.2.37 is the internal IP of the Nginx Ingress Controller. I don't understand where the 127.0.0.1 comes from and the client IP is completely missing.</p> <p>Is my configuration of my Nginx Proxy Service wrong or do I perhaps need to set an annotation

## ISPConfig cluster help
 - [https://www.reddit.com/r/selfhosted/comments/1c63xwt/ispconfig_cluster_help](https://www.reddit.com/r/selfhosted/comments/1c63xwt/ispconfig_cluster_help)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T07:38:40+00:00

<!-- SC_OFF --><div class="md"><p>Hello!</p> <p>I've been running ISPConfig for a while now but never in a cluster. </p> <p>I need a cluster for failover and load balancing </p> <p>My setup is as follows: </p> <p>db0.domain.tld as cluster master, SQL host and panel interface</p> <p>isp0.domain.tld as first mail and web server</p> <p>isp1.domain.tld as second mail and web server, configured as a mirror for isp0</p> <p>db1.domain.tld as mariadb replication slave</p> <p>webfs.domain.tld with open media vault for NFS storage mounted at /var/www and /var/vmail on isp0 and isp1. Both servers have the network filesystem option enabled in the server's config.</p> <p>Now, I installed ispconfig on isp0, isp1 and db0. They see eachother and communications between them seems to work fine. I do have to mention I used the same SQL root password for all 3 in case it's relevant. (There is no external access to port 3306) </p> <p>I want to (manually) migrate the sites and emails from the old install (

## Opensource Alternative to Document360 or Archbee? [For Non-Technical Users]
 - [https://www.reddit.com/r/selfhosted/comments/1c63vk1/opensource_alternative_to_document360_or_archbee](https://www.reddit.com/r/selfhosted/comments/1c63vk1/opensource_alternative_to_document360_or_archbee)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T07:34:03+00:00

<!-- SC_OFF --><div class="md"><p>I'm a huge advocate of open-source software.</p> <p>I was looking for open-source (self-hosted) alternatives to Document360 or Archbee.</p> <p>Has anyone come across something similar?</p> <p>I've tried Docusaurus. It's great but a big no to non-tech people and the features are much less.</p> <p>PS: If something like this is nonexistent, I'm gonna build this since I'm a developer.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/harishd30"> /u/harishd30 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c63vk1/opensource_alternative_to_document360_or_archbee/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c63vk1/opensource_alternative_to_document360_or_archbee/">[comments]</a></span>

## Opensource Alternative to Document360 or Archbee? [For Non-Technical Users]
 - [https://www.reddit.com/r/selfhosted/comments/1c63vk8/opensource_alternative_to_document360_or_archbee](https://www.reddit.com/r/selfhosted/comments/1c63vk8/opensource_alternative_to_document360_or_archbee)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T07:34:03+00:00

<!-- SC_OFF --><div class="md"><p>I'm a huge advocate of open-source software.</p> <p>I was looking for open-source (self-hosted) alternatives to Document360 or Archbee.</p> <p>Has anyone come across something similar?</p> <p>I've tried Docusaurus. It's great but a big no to non-tech people and the features are much less.</p> <p>PS: If something like this is nonexistent, I'm gonna build this since I'm a developer.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/harishd30"> /u/harishd30 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c63vk8/opensource_alternative_to_document360_or_archbee/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c63vk8/opensource_alternative_to_document360_or_archbee/">[comments]</a></span>

## Tandoor not loading correctly
 - [https://www.reddit.com/r/selfhosted/comments/1c63qyd/tandoor_not_loading_correctly](https://www.reddit.com/r/selfhosted/comments/1c63qyd/tandoor_not_loading_correctly)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T07:25:27+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1c63qyd/tandoor_not_loading_correctly/"> <img alt="Tandoor not loading correctly" src="https://b.thumbs.redditmedia.com/EoIrBMYq69DGLnc463SHBJIdLyVNbEDAjGchs9lzzKU.jpg" title="Tandoor not loading correctly" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/k0tvdbhkrzuc1.png?width=1915&amp;format=png&amp;auto=webp&amp;s=130a8ac2fc110785a5a59b5dff3a164a3981babc">https://preview.redd.it/k0tvdbhkrzuc1.png?width=1915&amp;format=png&amp;auto=webp&amp;s=130a8ac2fc110785a5a59b5dff3a164a3981babc</a></p> <p>Hello,<br /> For some reason randomly after update Tandoor does not load correctly and is unfunctional. Django admin page is functional. Does anyone had the same issue? <a href="/u/vabene1111">u/vabene1111</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/trilis"> /u/trilis </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c

## How can I setting up VPS Tunnel for selected (docker) services
 - [https://www.reddit.com/r/selfhosted/comments/1c63p4m/how_can_i_setting_up_vps_tunnel_for_selected](https://www.reddit.com/r/selfhosted/comments/1c63p4m/how_can_i_setting_up_vps_tunnel_for_selected)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T07:22:03+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I'm seeking advice on how to utilize a VPS as a tunnel to safeguard my home IP from potential attacks, while allowing only specific services like Jellyfin, Jellyseer, Plex, and YoutubeDL to use this tunnel, except when accessed within the local network or via Tailscale. It should act like a cloudflare tunnel but with my VPS.</p> <p>My current train of thought involves establishing a VPN connection between my VPS and home, coupled with a reverse proxy. It's worth noting that I predominantly use Docker for my services.</p> <p>Thanks in advance for your help !</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Aromatic_Cap_8982"> /u/Aromatic_Cap_8982 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c63p4m/how_can_i_setting_up_vps_tunnel_for_selected/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c63p4m/how_can_i_setting_up_vps_tunnel_f

## What os should i use for my server
 - [https://www.reddit.com/r/selfhosted/comments/1c638m7/what_os_should_i_use_for_my_server](https://www.reddit.com/r/selfhosted/comments/1c638m7/what_os_should_i_use_for_my_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T06:51:44+00:00

<!-- SC_OFF --><div class="md"><p>Im thinking of using true nas scale for my servers to use it as a nas and for running other things on it aswell</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ogga6165"> /u/Ogga6165 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c638m7/what_os_should_i_use_for_my_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c638m7/what_os_should_i_use_for_my_server/">[comments]</a></span>

## Photo Management with Dynamic Albums
 - [https://www.reddit.com/r/selfhosted/comments/1c633yh/photo_management_with_dynamic_albums](https://www.reddit.com/r/selfhosted/comments/1c633yh/photo_management_with_dynamic_albums)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T06:43:18+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys,</p> <p>I know that there are probably hundreds of posts regarding Photo Management solutions, but I could not find anything that can suit my needs. Maybe you can help me with a solution I didn't find.</p> <p>I am looking for a self hosted managed solution for photos and videos that can do Dynamic Albums (create albums based on different criteria and automatically add photos to those albums once the criteria is met).</p> <p>Other features that I am looking for but are completely optional:</p> <ul> <li>Ability to share with other people (generate sharable links with possibility to download photos)</li> <li>Ability to auto-backup from mobile application</li> <li>OAuth (I'm using Traefik2 + Authelia)</li> </ul> <p>I currently have over 100k photos and videos and I use my own folder structure that I do not want to modify.</p> <p>I am currently using Synology Photos and Immich.</p> <ul> <li>Synology Photos is great for dynamic albums, but it is sl

## Thinking of Moving to Proxmox
 - [https://www.reddit.com/r/selfhosted/comments/1c62x2j/thinking_of_moving_to_proxmox](https://www.reddit.com/r/selfhosted/comments/1c62x2j/thinking_of_moving_to_proxmox)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T06:30:32+00:00

<!-- SC_OFF --><div class="md"><p>I m self hosting my home media server on OMV, using docker containers. I m thinking of migrating to proxmox. I have heard its bit tricky to configure HW Acceleration in jellyfin in proxmox. currently I have installed jellyfin directly as a service and using my GTX 1060 for HW acceleration. also I dont want to lose any media files during the migration.</p> <p>Have anyone moved from OMV to proxmox and being able to use GPU acceleration in Jellyfin. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/garyyyy98"> /u/garyyyy98 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c62x2j/thinking_of_moving_to_proxmox/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c62x2j/thinking_of_moving_to_proxmox/">[comments]</a></span>

## Board game inventory management system
 - [https://www.reddit.com/r/selfhosted/comments/1c62ih7/board_game_inventory_management_system](https://www.reddit.com/r/selfhosted/comments/1c62ih7/board_game_inventory_management_system)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T06:04:25+00:00

<!-- SC_OFF --><div class="md"><p>Hello,<br /> Before you start yelling &quot;BOARD GAME GEEK&quot;, hear me out. In addition with my own board game collection, I'm days away from releasing my own board/card game. I will get a lot of boxes and I will have to manage it. I know for sure that I will gift some of them to friends and press. And of course sell them. Is there a project where I can manage how many board game copies I have left? Additionally statistics on how many sold or/and gifted. Well gifted could be jus 0.00 (whatever currency). Maybe I just need some kind of market inventory manager? </p> <p>Thank you in advance, you guys are cool!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lapiuslt"> /u/lapiuslt </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c62ih7/board_game_inventory_management_system/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c62ih7/board_game_inventory_m

## Bare Metal VPS or Cloud Platform for Crucial Services
 - [https://www.reddit.com/r/selfhosted/comments/1c61o08/bare_metal_vps_or_cloud_platform_for_crucial](https://www.reddit.com/r/selfhosted/comments/1c61o08/bare_metal_vps_or_cloud_platform_for_crucial)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T05:12:54+00:00

<!-- SC_OFF --><div class="md"><p>I'm happy to self-host non critical services on my home server but I'm looking for an external option to host my critical services. I'm looking at either a bare metal VPS or a Cloud Service like Akamai (Linode) or DigitalOcean. My plan is just to setup Docker to run the services. Does anyone have an opinion of one option vs the other or any recommendations for a VPS or Cloud Service (or any other options). Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/fotster"> /u/fotster </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c61o08/bare_metal_vps_or_cloud_platform_for_crucial/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c61o08/bare_metal_vps_or_cloud_platform_for_crucial/">[comments]</a></span>

## Looking for a network performance monitor
 - [https://www.reddit.com/r/selfhosted/comments/1c60q2x/looking_for_a_network_performance_monitor](https://www.reddit.com/r/selfhosted/comments/1c60q2x/looking_for_a_network_performance_monitor)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T04:19:42+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a docker or some application that will allow me to monitor my internet connection.</p> <p>Mainly want to see a graph of historic ping time to a list of sites/ips, and speedtests.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Stralia1"> /u/Stralia1 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c60q2x/looking_for_a_network_performance_monitor/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c60q2x/looking_for_a_network_performance_monitor/">[comments]</a></span>

## How to configure NGINX as a reverse proxy for FireFly III
 - [https://www.reddit.com/r/selfhosted/comments/1c60hf3/how_to_configure_nginx_as_a_reverse_proxy_for](https://www.reddit.com/r/selfhosted/comments/1c60hf3/how_to_configure_nginx_as_a_reverse_proxy_for)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T04:05:47+00:00

<!-- SC_OFF --><div class="md"><p>I'm doing everything using Docker, even NGINX. </p> <p>My <code>docker-compose.yml</code> file:</p> <pre><code>version: '3.3' services: nginx: image: nginx:latest container_name: nginx restart: always volumes: - ./nginx.conf:/etc/nginx/nginx.conf:ro ports: - 80:80 networks: - firefly_iii depends_on: - firefly firefly: image: fireflyiii/core:latest hostname: firefly container_name: firefly_iii_core restart: always volumes: - firefly_iii_upload:/var/www/html/storage/upload env_file: .env networks: - firefly_iii depends_on: - db db: image: mariadb:lts hostname: db container_name: firefly_iii_db restart: always env_file: .db.env networks: - firefly_iii volumes: - firefly_iii_db:/var/lib/mysql cron: # # To make this work, set STATIC_CRON_TOKEN in your .env file or as an environment variable and replace REPLACEME below # The STATIC_CRON_TOKEN must be *exactly* 32 characters long # image: alpine restart: always container_name: firefly_iii_cron command: sh -c

## Looking for PDF OCR that retains formatting.
 - [https://www.reddit.com/r/selfhosted/comments/1c5x6qz/looking_for_pdf_ocr_that_retains_formatting](https://www.reddit.com/r/selfhosted/comments/1c5x6qz/looking_for_pdf_ocr_that_retains_formatting)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T01:20:22+00:00

<!-- SC_OFF --><div class="md"><p>I'm trying to properly OCR documents like this:</p> <p><a href="https://babel.hathitrust.org/cgi/pt?id=uc1.32106019740171&amp;view=1up&amp;seq=495">https://babel.hathitrust.org/cgi/pt?id=uc1.32106019740171&amp;view=1up&amp;seq=495</a></p> <p>These are Hansard for the New Zealand government in 1854. The official record of everything said in Parliament. They're not very well digitised, and I'm looking to change that.</p> <p>In documents like this, formatting is crucial. Indents tell you where new paragraphs are starting. All caps names tell you who has the floor to speak, while regular title case names tell you someone is interjecting.</p> <p>Centered+Capitalised text tells you where new agenda items start. Every bit of formatting is a data point on its own and will be essential for when I get to the next stage which is using AI to analyse and identify parts of the conversation. So I need to make sure that the OCR I do now doesn't lose any of that infor

## Self-Hosted AI/SearXNG API
 - [https://www.reddit.com/r/selfhosted/comments/1c5x0p2/selfhosted_aisearxng_api](https://www.reddit.com/r/selfhosted/comments/1c5x0p2/selfhosted_aisearxng_api)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T01:12:12+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, there was a project floating around called FreeAskInternet, which allowed users to query GPT 3.5 Web, along with sending web content to the AI from SearXNG. I took this app and downscaled it to just an API, along with re-engineering the code, to make it more readable, and useful for English readers.</p> <p><a href="https://github.com/jaypyles/FreeAskInternet-API">https://github.com/jaypyles/FreeAskInternet-API</a><br /> Here is the API, along with a Discord bot I made using it, all self-hosted and can even use your own Ollama instance.</p> <p><a href="https://github.com/jaypyles/PerplexiBot">https://github.com/jaypyles/PerplexiBot</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bluesanoo"> /u/bluesanoo </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c5x0p2/selfhosted_aisearxng_api/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c5

## Screwed up my ZFS and having a hard time finding resources on recovery
 - [https://www.reddit.com/r/selfhosted/comments/1c5wssa/screwed_up_my_zfs_and_having_a_hard_time_finding](https://www.reddit.com/r/selfhosted/comments/1c5wssa/screwed_up_my_zfs_and_having_a_hard_time_finding)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T01:01:42+00:00

<!-- SC_OFF --><div class="md"><p>So before total panic sets in and everybody starts chiming in on multi location data storage etc. this is a test server with no important data on it.. now thats out of the way I don't want to do a re-install and say yeah I did it, nope I want to learn something here. How can I restore a completly messed ZFS? The problem with youtube, google, reddit etc. is they all go zfs import &quot;pool&quot; and little elves come dancing in the door with your data again..<br /> My scenario is the following:<br /> TrueNAS with 8 disk, 2 vDevs called &quot;fourset&quot; (4x4tb disks) &amp; twoset(4x2tb disks), since I hardly had used the server and was building a new NAS I yanked out the 4x4tb before I started thinking, the new NAS is running fine thanks for asking.. </p> <p>So now I am left with the 4x2tb but have no idea which way to go, the &quot;zfs import &quot;twoset&quot; do not work, so where do I start? and yes ZFS recovery is a new field but what better wa

## What services do you put on dedicated devices?
 - [https://www.reddit.com/r/selfhosted/comments/1c5wsqt/what_services_do_you_put_on_dedicated_devices](https://www.reddit.com/r/selfhosted/comments/1c5wsqt/what_services_do_you_put_on_dedicated_devices)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T01:01:38+00:00

<!-- SC_OFF --><div class="md"><p>I currently have two mini PCs, 1 mid-sized PC, 1 full size tower, 1 Synology NAS, and 2x Raspberry Pi 4's.</p> <p>1 of my mini PCs is dedicated to Media. It runs Plex, Jellyfin, and Audiobookshelf. The other runs Network related stuff. dns/dhcp, homeassistant, and reverse proxy.</p> <p>The mid-sized PC is all about utility containers. Immich, *arrs etc...</p> <p>The full size PC manages video game dedicated server hosting.</p> <p>And the NAS I try to avoid putting anything on it, but I do use Synology Surveillance to manage my various camera footage storage.</p> <p>I'm not currently using the raspberry pi's for anything.</p> <p>The next phase of my journey will be setting up ubiquiti and a small dual NIC mini PC with pfsense. I might move my network related content to this mini PC, but I'm not sure if that's a good idea yet.</p> <p>Anyway, I'm curious how others distribute their services across their devices. If anyone's got any tips, I'd love to hear

## Dashy/ProxmoxHelper missing Config file
 - [https://www.reddit.com/r/selfhosted/comments/1c5wjhd/dashyproxmoxhelper_missing_config_file](https://www.reddit.com/r/selfhosted/comments/1c5wjhd/dashyproxmoxhelper_missing_config_file)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-17T00:49:32+00:00

<!-- SC_OFF --><div class="md"><p>A newbie question: I just installed Dashy the using tteck ProxMox helper script. Dashy is working fine but I cannot find the conf.yml in the container created by the ProxMox Script helper. When I go to the console and type LS, there are folders/files there. Thx</p> <p><a href="https://tteck.github.io/Proxmox/">https://tteck.github.io/Proxmox/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sbehta"> /u/sbehta </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1c5wjhd/dashyproxmoxhelper_missing_config_file/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1c5wjhd/dashyproxmoxhelper_missing_config_file/">[comments]</a></span>

