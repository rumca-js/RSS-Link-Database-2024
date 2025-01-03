# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Fast reverse proxy (frp)
 - [https://www.reddit.com/r/selfhosted/comments/1gsa2ew/fast_reverse_proxy_frp](https://www.reddit.com/r/selfhosted/comments/1gsa2ew/fast_reverse_proxy_frp)
 - RSS feed: $source
 - date published: 2024-11-15T23:37:52+00:00

<!-- SC_OFF --><div class="md"><p>Do many or any of you use this? As an almost complete beginner I’m way out of my depth trying to set it up. Wondering if anyone knows of a good guide/video for this, or some advice?</p> <p><a href="https://github.com/fatedier/frp">https://github.com/fatedier/frp</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JMunkyis-very-chunky"> /u/JMunkyis-very-chunky </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsa2ew/fast_reverse_proxy_frp/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gsa2ew/fast_reverse_proxy_frp/">[comments]</a></span>

## Looking for security suggestions when exposing services to public internet (as well as other general suggestions)
 - [https://www.reddit.com/r/selfhosted/comments/1gs9jtx/looking_for_security_suggestions_when_exposing](https://www.reddit.com/r/selfhosted/comments/1gs9jtx/looking_for_security_suggestions_when_exposing)
 - RSS feed: $source
 - date published: 2024-11-15T23:13:33+00:00

<!-- SC_OFF --><div class="md"><p>Let me preface this by saying I&#39;m a self-hosting noob.</p> <p>I&#39;ve been kicking around the idea of getting a used mini PC to install Linux on and use as a home server. A few potential projects/use cases I have come up with are:</p> <ul> <li>Dockerized Minecraft server</li> <li>K8s Cluster hosting a small personal website or dashboard</li> <li>Plex Server</li> </ul> <p>I&#39;m not super familiar with virtualization, but I planned on either a QEMU/KVM or Proxmox setup with at least 2 VMs for the above applications.</p> <p>Considering that at the very least the Minecraft server would be exposed to the internet, I had a few questions:</p> <ul> <li>What type of hardware should I be looking at for a DMZ server? <ul> <li>Would another mini PC suffice, if so, what specs? (I can imagine I would need something heftier if I was trying to access my Plex server from outside my home)</li> </ul></li> <li>What security features should I set up on the DMZ ser

## Need help with disk partitioning and sharing
 - [https://www.reddit.com/r/selfhosted/comments/1gs8pic/need_help_with_disk_partitioning_and_sharing](https://www.reddit.com/r/selfhosted/comments/1gs8pic/need_help_with_disk_partitioning_and_sharing)
 - RSS feed: $source
 - date published: 2024-11-15T22:34:27+00:00

<!-- SC_OFF --><div class="md"><p>So, today i received my brand new WD Red 4TB for my brand new home server and i&#39;m trying to use it the best way possible.</p> <p>My idea for the server is having a bunch of everyday use containers with immich, paperless, vaultwarden, maybe nextcloud and whatever comes up, and have some vm&#39;s to practice ethical hacking (i&#39;ve already managed to create an isolated network to put vulnerable machines).</p> <p>So right now i have a 500GB SSD and the new 4TB HDD, the SSD is the default PVE partitioning with a 499GB LVM partition. And i was thinking of partitioning the HDD into a 1TB LVM (for VMs and LXCs) and a 3TB Directory partition. The idea is to have this last partition as a shared space for all of my everyday containers as i would like to have all of the data centralized for ease of backing up and access from diferent services (as long as it&#39;s compatible, probably quite difficult).</p> <p>So my question is first, is this a good idea? O

## Terraform Module to Run a KinD Kubernetes Cluster Locally
 - [https://www.reddit.com/r/selfhosted/comments/1gs87vs/terraform_module_to_run_a_kind_kubernetes_cluster](https://www.reddit.com/r/selfhosted/comments/1gs87vs/terraform_module_to_run_a_kind_kubernetes_cluster)
 - RSS feed: $source
 - date published: 2024-11-15T22:12:20+00:00

<!-- SC_OFF --><div class="md"><p>I run my &quot;production&quot; kubernetes cluster on my Intel NUCs and when I develop locally I deploy my workloads to my local kubernetes cluster using kind. </p> <p>Since I use Terraform for almost everything and I wanted something easy to deploy a kind cluster using Terraform, so I created this Terraform Module:</p> <p><a href="https://github.com/ruanbekker/terraform-kubernetes-kind-module">https://github.com/ruanbekker/terraform-kubernetes-kind-module</a> </p> <p>Usage is as simple as:</p> <p>```hcl<br/> module &quot;kind-module&quot; {<br/> source = &quot;ruanbekker/kind-module/kubernetes&quot;<br/> version = &quot;1.0.0&quot;<br/> workers = 3<br/> }<br/> ```</p> <p>Sure you can argue that the kind cli is easy enough already but for me having everything in terraform is quite nice.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rbekker87"> /u/rbekker87 </a> <br/> <span><a href="https://www.reddit.com/r/sel

## Cloudflare WAF not working with nginx
 - [https://www.reddit.com/r/selfhosted/comments/1gs86hx/cloudflare_waf_not_working_with_nginx](https://www.reddit.com/r/selfhosted/comments/1gs86hx/cloudflare_waf_not_working_with_nginx)
 - RSS feed: $source
 - date published: 2024-11-15T22:10:33+00:00

<!-- SC_OFF --><div class="md"><p>Hi! I just switched my set up from caddy over to nginx and I like it a lot better. The only issue I have noticed is that my WAF rules in cloudflare are being ignored with nginx. I have a tunnel set up for home assistant which is respecting the rules properly, but all of my apps running through nginx are bypassing them.</p> <p>Does anyone know what the issue could be and what a possible fix is?</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Turkeyrice"> /u/Turkeyrice </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs86hx/cloudflare_waf_not_working_with_nginx/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs86hx/cloudflare_waf_not_working_with_nginx/">[comments]</a></span>

## Monitoring tool
 - [https://www.reddit.com/r/selfhosted/comments/1gs82c0/monitoring_tool](https://www.reddit.com/r/selfhosted/comments/1gs82c0/monitoring_tool)
 - RSS feed: $source
 - date published: 2024-11-15T22:05:16+00:00

<!-- SC_OFF --><div class="md"><p>Hi, i currently used Homarr on my truenas however im looking for a monitoring tool who can be implemented by iframe on Homarr.</p> <p>I tried Netdata (full redirection) Dashdot (error on it) Glances (too complicated to setup)</p> <p>I also tried to iframe my truenas dashboard but with scale, iframe is blocked....</p> <p>So if someone have a tool who can fit with my demand :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok_You_1314"> /u/Ok_You_1314 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs82c0/monitoring_tool/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs82c0/monitoring_tool/">[comments]</a></span>

## Docker Swarm and standalone hosts now in Dozzle
 - [https://www.reddit.com/r/selfhosted/comments/1gs80s1/docker_swarm_and_standalone_hosts_now_in_dozzle](https://www.reddit.com/r/selfhosted/comments/1gs80s1/docker_swarm_and_standalone_hosts_now_in_dozzle)
 - RSS feed: $source
 - date published: 2024-11-15T22:03:20+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gs80s1/docker_swarm_and_standalone_hosts_now_in_dozzle/"> <img src="https://preview.redd.it/mailja7i151e1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=caf10907d5d6810517e1155e1f4c8aedd5644a04" alt="Docker Swarm and standalone hosts now in Dozzle" title="Docker Swarm and standalone hosts now in Dozzle" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mitchplze"> /u/mitchplze </a> <br/> <span><a href="https://i.redd.it/mailja7i151e1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs80s1/docker_swarm_and_standalone_hosts_now_in_dozzle/">[comments]</a></span> </td></tr></table>

## Open WebUI on Kubernetes with ArgoCD/Helm & Aider AI Assistant with OpenRouter
 - [https://www.reddit.com/r/selfhosted/comments/1gs7q5z/open_webui_on_kubernetes_with_argocdhelm_aider_ai](https://www.reddit.com/r/selfhosted/comments/1gs7q5z/open_webui_on_kubernetes_with_argocdhelm_aider_ai)
 - RSS feed: $source
 - date published: 2024-11-15T21:50:25+00:00

<!-- SC_OFF --><div class="md"><p>Learn more about replacing a fixed price ChatGPT subscription with your own, self hosted Open WebUI on Kubernetes with either pure Helm or ArgoCD with Helm. Also, learn about setting up Aider as your local, terminal based AI coding assistant. If you want to add Ollama as your local model API, the same configuration applies, you just need to configure the already deployed Open WebUI.</p> <p>The two guides in the series explain about deploying and connecting everything with OpenRouter for accessing any model its API supports, through a single, unified endpoint, which makes it great as you can control which model to use in different tasks, making it more cost efficient.</p> <p>Post 1:</p> <p><a href="https://kubito.dev/posts/deploy-open-webui-kubernetes-argocd-helm-openrouter/">https://kubito.dev/posts/deploy-open-webui-kubernetes-argocd-helm-openrouter/</a></p> <p>Post 2:</p> <p><a href="https://kubito.dev/posts/ai-assistant-aider-openrouter/">https://

## A modern, open-source alternative to cloud-managed databases.
 - [https://www.reddit.com/r/selfhosted/comments/1gs7l2r/a_modern_opensource_alternative_to_cloudmanaged](https://www.reddit.com/r/selfhosted/comments/1gs7l2r/a_modern_opensource_alternative_to_cloudmanaged)
 - RSS feed: $source
 - date published: 2024-11-15T21:44:25+00:00

<!-- SC_OFF --><div class="md"><p><strong>postgresql_cluster</strong> is an open-source solution for deploying high-availability PostgreSQL clusters across multiple cloud providers or on-premise. Unlike managed cloud databases, this tool is self-hosted but fully automated, offering cost transparency, better control over resources, and advanced features like AI-based search (pgvector), time-series data (TimescaleDB), geospatial data (PostGIS), and more. Designed for reliability, it includes automated failover, backup, and restoration — no Docker or Kubernetes needed. </p> <p>With a focus on simplicity, rapid deployment, and vendor independence, it gives developers the flexibility to build on their terms, not the cloud provider’s.</p> <p>Get started in minutes and experience the power of full control over your PostgreSQL infrastructure — no lock-in, no compromises.</p> <p><a href="https://postgresql-cluster.org">https://postgresql-cluster.org</a> </p> </div><!-- SC_ON --> &#32; submitt

## Did any of you *stop* self-hosting your media? How has it gone?
 - [https://www.reddit.com/r/selfhosted/comments/1gs7kpr/did_any_of_you_stop_selfhosting_your_media_how](https://www.reddit.com/r/selfhosted/comments/1gs7kpr/did_any_of_you_stop_selfhosting_your_media_how)
 - RSS feed: $source
 - date published: 2024-11-15T21:43:59+00:00

<!-- SC_OFF --><div class="md"><p>I just had a HDD start dying on me. Thankfully, I&#39;ve got parity with Snapraid so it isn&#39;t a problem, but it&#39;s started making me think about going down the real debrid path. Anybody do this and prefer it? I don&#39;t know if I&#39;m sold on not having everything more local.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sockrocker"> /u/sockrocker </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs7kpr/did_any_of_you_stop_selfhosting_your_media_how/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs7kpr/did_any_of_you_stop_selfhosting_your_media_how/">[comments]</a></span>

## How to self-host Plausible Analytics with Kamal
 - [https://www.reddit.com/r/selfhosted/comments/1gs7an8/how_to_selfhost_plausible_analytics_with_kamal](https://www.reddit.com/r/selfhosted/comments/1gs7an8/how_to_selfhost_plausible_analytics_with_kamal)
 - RSS feed: $source
 - date published: 2024-11-15T21:31:50+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gs7an8/how_to_selfhost_plausible_analytics_with_kamal/"> <img src="https://external-preview.redd.it/JM3l6uZZxpJqZ25sEQK1jd3CxGtS3nVzYgzhpc9v8Fs.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=2c68fc5e470719906b28122315df516378f70b87" alt="How to self-host Plausible Analytics with Kamal" title="How to self-host Plausible Analytics with Kamal" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kyrylo"> /u/kyrylo </a> <br/> <span><a href="https://kyrylo.org/kamal/2024/10/29/how-to-self-host-plausible-analytics-with-kamal.html">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs7an8/how_to_selfhost_plausible_analytics_with_kamal/">[comments]</a></span> </td></tr></table>

## Network Diagram Software
 - [https://www.reddit.com/r/selfhosted/comments/1gs6ws4/network_diagram_software](https://www.reddit.com/r/selfhosted/comments/1gs6ws4/network_diagram_software)
 - RSS feed: $source
 - date published: 2024-11-15T21:14:36+00:00

<!-- SC_OFF --><div class="md"><p>What diagram software are most people using today if they wanted to draw out their network? Ive been using draw.io through my nextcloud instance but want to see what else is out there and popular</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DekaTrron"> /u/DekaTrron </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs6ws4/network_diagram_software/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs6ws4/network_diagram_software/">[comments]</a></span>

## BrowserBox
 - [https://www.reddit.com/r/selfhosted/comments/1gs5edm/browserbox](https://www.reddit.com/r/selfhosted/comments/1gs5edm/browserbox)
 - RSS feed: $source
 - date published: 2024-11-15T20:07:12+00:00

<!-- SC_OFF --><div class="md"><p>Has anyone ever installed BrowserBox locally? I been trying to get it to work but no matter what I do it&#39;s not working. I tried it on almalinux, ubuntu and debian, both the docker image and manual bash installation but it never works. Manual installation says something about no licence (isnt it free?) And docker gives error SSL_ERROR_SYSCALL. Any help to get this thing going would be much appreciated. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bobaloooo"> /u/bobaloooo </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs5edm/browserbox/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs5edm/browserbox/">[comments]</a></span>

## [HELP WANTED] Wordpress in docker + reverse proxy
 - [https://www.reddit.com/r/selfhosted/comments/1gs4gzh/help_wanted_wordpress_in_docker_reverse_proxy](https://www.reddit.com/r/selfhosted/comments/1gs4gzh/help_wanted_wordpress_in_docker_reverse_proxy)
 - RSS feed: $source
 - date published: 2024-11-15T19:26:44+00:00

<!-- SC_OFF --><div class="md"><p>Hi there.<br/> Im having an issue where when i try to point my domain to my public IP and then create a reverse proxy to the port that Wordpress is running on then I&#39;m redirected to <a href="https://mydomain.com:port">https://mydomain.com:port</a> when I enter <a href="https://mydomain.com">https://mydomain.com</a><br/> I cant figure out why this is happening. Any and all help is highly appreciated</p> <p>Setup:<br/> CasaOS (BigBear)<br/> Wordpress running in a docker container - docker network: Bridge<br/> Caddy running in a docker container - docker network: Bridge</p> <p>Caddy config</p> <p><a href="https://pastebin.com/815UtmxU">https://pastebin.com/815UtmxU</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Holiday-Advance-7524"> /u/Holiday-Advance-7524 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs4gzh/help_wanted_wordpress_in_docker_reverse_proxy/">[link]</a></span> &#32; 

## How do you balance between managing the community version of your product, versus the paid offering?
 - [https://www.reddit.com/r/selfhosted/comments/1gs43bl/how_do_you_balance_between_managing_the_community](https://www.reddit.com/r/selfhosted/comments/1gs43bl/how_do_you_balance_between_managing_the_community)
 - RSS feed: $source
 - date published: 2024-11-15T19:10:09+00:00

<!-- SC_OFF --><div class="md"><p>MongoDB, Elastic, RHEL, Kubernetes, GitLab, MySQL, PostgreSQL, Grafana, Redis, Jenkins... the list is literally never ending - all started off as completely &quot;open-source,&quot; but of course - people have to eat.</p> <p>I&#39;m super new to this, and just beginning to explore the challenges (emotional, ethical, various constraints) of giving back to the community, while still finding a way to monetize in the future.</p> <p>Of course, making your idea completely open-source can often take your product light-years, ahead of where it would be, as opposed to going solo - but again, what do I know? 😅I don&#39;t have nearly the user-base to comment on this.</p> <p>But, I would love to hear from some of the more seasoned members of <a href="/r/selfhosted">r/selfhosted</a>. </p> <p>Love you guys for all your great support over the years! One of the smartest, and most helpful communities on Reddit!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a hre

## How are you automating your music?
 - [https://www.reddit.com/r/selfhosted/comments/1gs3wcv/how_are_you_automating_your_music](https://www.reddit.com/r/selfhosted/comments/1gs3wcv/how_are_you_automating_your_music)
 - RSS feed: $source
 - date published: 2024-11-15T19:02:18+00:00

<!-- SC_OFF --><div class="md"><p>Trying to get into music, self-hosting. Currently, using Plex and lidarr which is hooked up to my media indexes. But I still find myself having to manually add/download the majority of my music. Is there some better indexes people are using for music. Or something that also helps streamline the automation, like overseerr but for music?</p> <p>Much appreciated </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/M05final"> /u/M05final </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs3wcv/how_are_you_automating_your_music/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs3wcv/how_are_you_automating_your_music/">[comments]</a></span>

## Switching from Google Workspace
 - [https://www.reddit.com/r/selfhosted/comments/1gs2yzg/switching_from_google_workspace](https://www.reddit.com/r/selfhosted/comments/1gs2yzg/switching_from_google_workspace)
 - RSS feed: $source
 - date published: 2024-11-15T18:22:43+00:00

<!-- SC_OFF --><div class="md"><p>Im switching from Google Workspace to self hosted.</p> <p>So far I have found: - Nextcloud for Google Drive - Mailcow for Google Mail - Immich for Google Photos - Vaultwarden for Google Vault</p> <p>Still searching for the following: - Google Meet alternative - Google Forms - Google Chat - Google Calendar - Google Contacts - Google Docs Signatures</p> <p>What are my options?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hackermarks"> /u/hackermarks </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs2yzg/switching_from_google_workspace/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs2yzg/switching_from_google_workspace/">[comments]</a></span>

## Cannot access docker container over https with traefik/tailscale
 - [https://www.reddit.com/r/selfhosted/comments/1gs2nmw/cannot_access_docker_container_over_https_with](https://www.reddit.com/r/selfhosted/comments/1gs2nmw/cannot_access_docker_container_over_https_with)
 - RSS feed: $source
 - date published: 2024-11-15T18:09:23+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve played around with enabling https in Tailscale, and tried to set up Traefik for it. However, I get a DNS error when trying to access any service I enable with https over tailscale. Below is my compose file for Traefik</p> <pre><code>version: &quot;3&quot; services: reverse-proxy: image: traefik:v3.1 restart: unless-stopped ports: # The HTTP port - 80:80 - 443:443 - 8082:8080 volumes: # So that Traefik can listen to the Docker events - /var/run/docker.sock:/var/run/docker.sock - ./traefik.yaml:/traefik.yaml:ro labels: - traefik.http.routers.traefik.rule=Host(`traefik.XXXX.ts.net`) - traefik.http.routers.traefik.entrypoints=websecure - traefik.http.routers.traefik.tls=true networks: - media_network networks: &quot;&quot;: {} media_network: external: true </code></pre> <p>This is my traefik.yaml:</p> <pre><code>entryPoints: web: address: &quot;:80&quot; # HTTP websecure: address: &quot;:443&quot; # HTTPS providers: docker: endpoint: &quot;unix:

## LubeLogger app but for everyday tasks, alternative ?
 - [https://www.reddit.com/r/selfhosted/comments/1gs27c2/lubelogger_app_but_for_everyday_tasks_alternative](https://www.reddit.com/r/selfhosted/comments/1gs27c2/lubelogger_app_but_for_everyday_tasks_alternative)
 - RSS feed: $source
 - date published: 2024-11-15T17:50:49+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for an app like LubeLogger but for everyday tasks, where you have recurring reminders, a list of supplies, etc....</p> <p>Do you have any suggestions? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DamsDev"> /u/DamsDev </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs27c2/lubelogger_app_but_for_everyday_tasks_alternative/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs27c2/lubelogger_app_but_for_everyday_tasks_alternative/">[comments]</a></span>

## Is there a way for CIFS/SMB shares to contain symlinks/shortcuts that work on both Windows and Linux clients?
 - [https://www.reddit.com/r/selfhosted/comments/1gs25k6/is_there_a_way_for_cifssmb_shares_to_contain](https://www.reddit.com/r/selfhosted/comments/1gs25k6/is_there_a_way_for_cifssmb_shares_to_contain)
 - RSS feed: $source
 - date published: 2024-11-15T17:48:43+00:00

<!-- SC_OFF --><div class="md"><p>Ok so for some context, I have an OMV based NAS on my Proxmox server, and on it I store, among other things, my photos. I let Immich handle the folder organization, but I want the &quot;Photos&quot; folder in my personal SMB/CIFS share to essentially be a portal to the subfolder with the actual media within Immich&#39;s &quot;upload folder&quot; so that it can look like a regular &quot;here&#39;s where my photos are&quot; directory without all the clunkiness of containing the entire Immich base directory. It really should be read-only (from the perspective of clients on the share) because Immich doesn&#39;t enjoy being messed with, but if that&#39;s not easy to accomplish I could also just be careful to not set software up to write to it. I use both Windows and Linux clients, and can&#39;t figure out a way to make Linux-native symlinks work, so I would appreciate some help figuring out what configuration is needed to enable that. What I want is basic

## Server with I9 13900K
 - [https://www.reddit.com/r/selfhosted/comments/1gs22h1/server_with_i9_13900k](https://www.reddit.com/r/selfhosted/comments/1gs22h1/server_with_i9_13900k)
 - RSS feed: $source
 - date published: 2024-11-15T17:45:12+00:00

<!-- SC_OFF --><div class="md"><p>I’m looking to build a server for just hosting a Minecraft and Ark like that with a small group of friends I already have the I9 13900K would it be a good server CPU or should I turn it into a editing machine instead and buy a cheaper cpu? What specs should I shoot for?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/luke64697532256"> /u/luke64697532256 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs22h1/server_with_i9_13900k/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs22h1/server_with_i9_13900k/">[comments]</a></span>

## Rack Mounted Dumb JBOD / Sata passthrough?
 - [https://www.reddit.com/r/selfhosted/comments/1gs1po1/rack_mounted_dumb_jbod_sata_passthrough](https://www.reddit.com/r/selfhosted/comments/1gs1po1/rack_mounted_dumb_jbod_sata_passthrough)
 - RSS feed: $source
 - date published: 2024-11-15T17:30:13+00:00

<!-- SC_OFF --><div class="md"><p>I feel like something like this must exist, but I&#39;ve been unable to find anything.</p> <p>There&#39;s a number of external drives I use for some server stuff. Currently, theyre all stacked on a shelf.</p> <p>I&#39;d like to have them more organized, what I&#39;m specifically looking for is a dumb JBOD sort of thing, where each drive mounts in and is passed through to a sata port on the back. No power, no compute, just a dumb box that can hold drives and pass the sata round back.</p> <p>Anyone know of such a thing?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LinuxIsFree"> /u/LinuxIsFree </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs1po1/rack_mounted_dumb_jbod_sata_passthrough/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs1po1/rack_mounted_dumb_jbod_sata_passthrough/">[comments]</a></span>

## Calling Santa?
 - [https://www.reddit.com/r/selfhosted/comments/1gs1p9x/calling_santa](https://www.reddit.com/r/selfhosted/comments/1gs1p9x/calling_santa)
 - RSS feed: $source
 - date published: 2024-11-15T17:29:47+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been on the lookout for some (possibly AI) software to take some Santa calls for my niece and nephews. I&#39;m pretty well versed in VoIP, but not so much with PBX. Any suggestions for some sort of software that could be interactive for the kids? Possibly analyze their questions and reply back? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ill-Physics1990"> /u/Ill-Physics1990 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs1p9x/calling_santa/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs1p9x/calling_santa/">[comments]</a></span>

## Underscore in nginx location notation
 - [https://www.reddit.com/r/selfhosted/comments/1gs1fmf/underscore_in_nginx_location_notation](https://www.reddit.com/r/selfhosted/comments/1gs1fmf/underscore_in_nginx_location_notation)
 - RSS feed: $source
 - date published: 2024-11-15T17:18:28+00:00

<!-- SC_OFF --><div class="md"><p>I accidentally discovered that if my nginx config file contains a location noted as, say, <code>location /git_shenanigans/ {}</code> or <code>location /backend_test1 {}</code> and I try to reach URL <a href="http://mydomainname.org/git/"><code>mydomainname.org/git/</code></a> or <a href="http://mydomainname.org/backend/"><code>mydomainname.org/backend/</code></a>, browser shows the main page of my site.</p> <p>Why does it happen? Is it documented?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ErlingSigurdson"> /u/ErlingSigurdson </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs1fmf/underscore_in_nginx_location_notation/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs1fmf/underscore_in_nginx_location_notation/">[comments]</a></span>

## Homepage and glance project merge 🤔
 - [https://www.reddit.com/r/selfhosted/comments/1gs0xv2/homepage_and_glance_project_merge](https://www.reddit.com/r/selfhosted/comments/1gs0xv2/homepage_and_glance_project_merge)
 - RSS feed: $source
 - date published: 2024-11-15T16:58:05+00:00

<!-- SC_OFF --><div class="md"><p>I found a post here where someone was repoting that is using Homepage inside og Glance as iframe and it makes me thinking of:<br/> Am I crazy or a merge from <a href="https://gethomepage.dev/">Homepage</a> and <a href="https://github.com/glanceapp/glance">Glance</a> project will create a dashbord killer?<br/> Hey both developers, let&#39;s talk about it, please!! 🙏🏽</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/edersong"> /u/edersong </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs0xv2/homepage_and_glance_project_merge/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs0xv2/homepage_and_glance_project_merge/">[comments]</a></span>

## Has anyone worked with Gigamon?
 - [https://www.reddit.com/r/selfhosted/comments/1gs0tuy/has_anyone_worked_with_gigamon](https://www.reddit.com/r/selfhosted/comments/1gs0tuy/has_anyone_worked_with_gigamon)
 - RSS feed: $source
 - date published: 2024-11-15T16:53:14+00:00

<!-- SC_OFF --><div class="md"><p>I want to utilize an older Gigamon that I purchased years ago. Gigamon has a (fairly) good reputation for their products - at least, their older stuff. I&#39;ve got 2 different models - GigaVUE-MP, and its newer &#39;cousin&#39;, GigaVUE-420. The GigaVUE-MP is a backup sniffer for the GigaVUE-420. Both sniffing devices are wiped and virgin configuration.</p> <p>I&#39;ve acquired what little documentation I could for both models. The documentation is good so long as your are already familiar with Gigamon products; HOWEVER, I&#39;ve scoured the Internet for some basic examples that I can use to sniff network traffic inline. I&#39;ve got the 1 Gbit Ethernet (RJ45) and SFP cards, along with redundant PSUs (they scream if you don&#39;t have two, and to turn off the alarm is something I&#39;d rather not do considering how &#39;dirty&#39; our power is out here.</p> <p>My question to the group is - does anyone have either a few samples on how to configure th

## ParseDMARC-dockerized Help
 - [https://www.reddit.com/r/selfhosted/comments/1gs0pc3/parsedmarcdockerized_help](https://www.reddit.com/r/selfhosted/comments/1gs0pc3/parsedmarcdockerized_help)
 - RSS feed: $source
 - date published: 2024-11-15T16:47:51+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I am trying to test out ParseDMARC and have followed this Github project to set it up:</p> <p><a href="https://github.com/patschi/parsedmarc-dockerized">GitHub - patschi/parsedmarc-dockerized: Dockerized self-initializing parsedmarc docker stack for lazy people</a></p> <p>I get everything stood up, containers are all running. I can pull the DMARC reports into ElasticSearch from an IMAP mailbox. However, nothing shows up in the Kibana dashboards. I get this error message:</p> <p>Error encountered while loading saved dashboard: Could not locate that dashboard</p> <p>Has anyone run into this? Am I missing something?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bradgnarr"> /u/bradgnarr </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs0pc3/parsedmarcdockerized_help/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs0pc3/parsedmarcdockeriz

## Media Cleaner for Jellyfin Issues
 - [https://www.reddit.com/r/selfhosted/comments/1gs0le7/media_cleaner_for_jellyfin_issues](https://www.reddit.com/r/selfhosted/comments/1gs0le7/media_cleaner_for_jellyfin_issues)
 - RSS feed: $source
 - date published: 2024-11-15T16:43:15+00:00

<!-- SC_OFF --><div class="md"><p>Have been running Jellyfin for a few years now and started using the Media Cleaner plugin a few months ago. It works as expected but in the log I&#39;m getting a lot of messages that state a movie was ignored because the movie was played BEFORE the added date, so it&#39;s not removing those titles even though the filter matches because the specified users have watched it. </p> <p>I have the setting Use Date Scanned into Library set, but there&#39;s a mismatch somewhere.</p> <p>Does anyone know how to resolve this? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MSP2MSP"> /u/MSP2MSP </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs0le7/media_cleaner_for_jellyfin_issues/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs0le7/media_cleaner_for_jellyfin_issues/">[comments]</a></span>

## Switch from Photoprism to Immich?
 - [https://www.reddit.com/r/selfhosted/comments/1gs05uz/switch_from_photoprism_to_immich](https://www.reddit.com/r/selfhosted/comments/1gs05uz/switch_from_photoprism_to_immich)
 - RSS feed: $source
 - date published: 2024-11-15T16:24:48+00:00

<!-- SC_OFF --><div class="md"><p>Hi there!</p> <p>I have been using Photoprism for some time to have the images from my Nextcloud in a separate UI (Photoprism accesses a photos folder in the Nextcloud).</p> <p>And... let&#39;s put it this way, photoprism has its flaws. I just found out about Immich through reddit and thought I&#39;d ask:</p> <p>Why should I switch from Photoprism to Immich? What are the benefits?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Milandro42"> /u/Milandro42 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs05uz/switch_from_photoprism_to_immich/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gs05uz/switch_from_photoprism_to_immich/">[comments]</a></span>

## Has anyone experienced their WordPress instance attempting to scan local network?
 - [https://www.reddit.com/r/selfhosted/comments/1grzegy/has_anyone_experienced_their_wordpress_instance](https://www.reddit.com/r/selfhosted/comments/1grzegy/has_anyone_experienced_their_wordpress_instance)
 - RSS feed: $source
 - date published: 2024-11-15T15:52:15+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1grzegy/has_anyone_experienced_their_wordpress_instance/"> <img src="https://b.thumbs.redditmedia.com/65XWNAkNzpxGV6NM_2u-2M2ydFY8U7gTB11PBngDv0I.jpg" alt="Has anyone experienced their WordPress instance attempting to scan local network?" title="Has anyone experienced their WordPress instance attempting to scan local network?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Just like the title states. I woke up this morning to see that three of the WordPress instances on my Proxmox environment have been blocked by my firewall.</p> <p>This happened after the WordPress instances were updated to 6.7</p> <p>EDIT: Here&#39;s a description of the threat from the route</p> <p><a href="https://preview.redd.it/lixv699yb31e1.png?width=2244&amp;format=png&amp;auto=webp&amp;s=ee49d9a1430114ef4aa5c71548aa6800887a330a">screenshot</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LilM

## OPNsense Web Interface Accessible, But Not Through a Switch – VLAN Issue?
 - [https://www.reddit.com/r/selfhosted/comments/1grz20q/opnsense_web_interface_accessible_but_not_through](https://www.reddit.com/r/selfhosted/comments/1grz20q/opnsense_web_interface_accessible_but_not_through)
 - RSS feed: $source
 - date published: 2024-11-15T15:37:01+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! I’m setting up an OPNsense firewall and ran into an issue with accessing the web interface when connected over a managed switch. I&#39;ve added my current VLAN setup in the pic below (in case it helps). </p> <p>Current situation:</p> <ul> <li>When I connect my laptop <strong>directly</strong> to the LAN port of the OPNsense machine, I can access the web interface just fine.</li> <li>When I connect the LAN port of the OPNsense machine to port 1 and my laptop to port 2, the laptop does not appear to receive an IP by the DHCP server and I&#39;m unable to access the web-interface.</li> </ul> <p>I suspect it might be a VLAN misconfiguration, but I&#39;m not entirely sure how to proceed. Any advice on troubleshooting steps to make this work?</p> <p>Thanks in advance for any help!</p> <p><a href="https://preview.redd.it/1ny5vtlp231e1.png?width=773&amp;format=png&amp;auto=webp&amp;s=c89a61b4cfc6b216b61589ce9cd265c8df36d52d">My Current VLAN conf

## Coral Talk for comments?
 - [https://www.reddit.com/r/selfhosted/comments/1grydaj/coral_talk_for_comments](https://www.reddit.com/r/selfhosted/comments/1grydaj/coral_talk_for_comments)
 - RSS feed: $source
 - date published: 2024-11-15T15:06:09+00:00

<!-- SC_OFF --><div class="md"><p>I have a news blog that sees about 50-100k sessions a month. I was initially thinking to try Commento but it seems the project has been dead some years now. I also looked at Hyvor but didn&#39;t want to pay $40 a month just for comments (not sure if I would ever see enough value being returned). </p> <p>I came across the self hosted version of Coral Talk <a href="https://github.com/coralproject/talk">https://github.com/coralproject/talk</a> has anyone tried this with good results? </p> <p>Also, given that I plan to self host, what are the implications in terms of GDPR? </p> <p>At the moment, my site is hosted on Rocket.net (managed Wordpress hosting with Enterprise CF protection and what not) as I don&#39;t have an in house community. People just read and go, with most of the community being on social media channels and via my email newsletter. Given that my host isn&#39;t flexible to host non-WP projects, what might be my best avenue to set up Coral

## Perplexideez - Self-hosted AI-powered search with SSO, multi-user support, shareable links, and more.
 - [https://www.reddit.com/r/selfhosted/comments/1grxyi5/perplexideez_selfhosted_aipowered_search_with_sso](https://www.reddit.com/r/selfhosted/comments/1grxyi5/perplexideez_selfhosted_aipowered_search_with_sso)
 - RSS feed: $source
 - date published: 2024-11-15T14:47:24+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1grxyi5/perplexideez_selfhosted_aipowered_search_with_sso/"> <img src="https://external-preview.redd.it/z9wQOPXvWb_uaIYOiqMMw1jXD9QZRhnJbvYo4QDtB84.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=c5acf72cac648e84b71a7e32ce3fa77ee4cb8481" alt="Perplexideez - Self-hosted AI-powered search with SSO, multi-user support, shareable links, and more." title="Perplexideez - Self-hosted AI-powered search with SSO, multi-user support, shareable links, and more." /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/9n42w53mu21e1.png?width=1814&amp;format=png&amp;auto=webp&amp;s=7efd054428293313babc8e31d40b0f5d6344afe4">A screenshot of the app in action.</a></p> <h1>Intro</h1> <p>Hey everyone! I just released an early version of my newest side project and I thought it could be useful to someone who isn&#39;t me as well.</p> <h1>What is this?</h1> <p>It&#39;s a Perplexity clone that uses Ollama 

## Help needed - OnlyOffice Docker Swarm
 - [https://www.reddit.com/r/selfhosted/comments/1grxdjf/help_needed_onlyoffice_docker_swarm](https://www.reddit.com/r/selfhosted/comments/1grxdjf/help_needed_onlyoffice_docker_swarm)
 - RSS feed: $source
 - date published: 2024-11-15T14:19:21+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1grxdjf/help_needed_onlyoffice_docker_swarm/"> <img src="https://b.thumbs.redditmedia.com/Uhl3Lo1Fhw26CZa8d8p6S01iWrY2PctuWC4MXJpedRo.jpg" alt="Help needed - OnlyOffice Docker Swarm" title="Help needed - OnlyOffice Docker Swarm" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi everyone, </p> <p>I recently started using TrueNAS and there is only one container that is causing me headaches: OnlyOffice.</p> <p>I was curious on how Docker Swarm works and spin up Ubuntu Servers and started playing with it. I currently use CouchDB for Obsidian, Nginx, FileRun, and some other minor applications. I have the same user in my TrueNAS and my servers, same UID and GID in the 1000:1000 user group. Ownership is for the 1000 user, I have mapall user and group set to &quot;user&quot; and &quot;wheel&quot;. Usually, when I was having problems, adding a &#39;user: &quot;1000:1000&quot;&#39; in my docker compose would fix permis

## Libation (Audible ripper) experiences?
 - [https://www.reddit.com/r/selfhosted/comments/1grx4y0/libation_audible_ripper_experiences](https://www.reddit.com/r/selfhosted/comments/1grx4y0/libation_audible_ripper_experiences)
 - RSS feed: $source
 - date published: 2024-11-15T14:07:41+00:00

<!-- SC_OFF --><div class="md"><p>Before I subscribe to Audible for a month and rip every audiobook I&#39;ll ever listen to, I&#39;d like to know if anyone has used <a href="https://github.com/rmcrackan/Libation">this app</a> and how well it works.</p> <p>Is it quick? Any issues playing the files with AudioBookShelf? Anything else I should know?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/xt0r"> /u/xt0r </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1grx4y0/libation_audible_ripper_experiences/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1grx4y0/libation_audible_ripper_experiences/">[comments]</a></span>

## Recommendation on Mini PC
 - [https://www.reddit.com/r/selfhosted/comments/1grwr8g/recommendation_on_mini_pc](https://www.reddit.com/r/selfhosted/comments/1grwr8g/recommendation_on_mini_pc)
 - RSS feed: $source
 - date published: 2024-11-15T13:48:54+00:00

<!-- SC_OFF --><div class="md"><p>Hi there,<br/> getting into selfhosting and want to purchase a <strong>mini PC</strong> with at least 1TB of SSD space.</p> <p>What I need to do is to run:</p> <ul> <li><strong>Immich</strong> (around 500GB of photos)</li> <li><strong>Jellyfin</strong></li> <li>And a bunch of other smaller stuff</li> </ul> <p>While researching I&#39;ve understood that, for what I need to do, my decision is between an <strong>Intel NUC</strong> or a <strong>Beelink</strong>.</p> <p>Budget I have is 200/400£.</p> <p>For now the best I&#39;ve found so far would be <a href="https://www.amazon.co.uk/Beelink-Lake-N100-Processor-Computer-MINI-S12/dp/B0BZGPTLPG">this Beelink</a>, then add 1TB of SSD with something like <a href="https://www.amazon.co.uk/Samsung-980-PRO-PCIe-NVMe/dp/B08GLX7TNT">this</a>.</p> <p>What are your thoughts / what would you recommend getting?<br/> And is it worth to wait for Black Friday deals on websites like Amazon? </p> </div><!-- SC_ON --> &#32; 

## NVR Access Software
 - [https://www.reddit.com/r/selfhosted/comments/1grwhnz/nvr_access_software](https://www.reddit.com/r/selfhosted/comments/1grwhnz/nvr_access_software)
 - RSS feed: $source
 - date published: 2024-11-15T13:36:02+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for software that will allow me to connect to several NVR&#39;s at once. I am not looking for NVR software. Currently we use World Eye Cam NVR&#39;s and SmartPSS to view them. They say SmartPSS is being discontinued and replaced with SmartPSS Lite, which doesn&#39;t offer as many features as we are accustomed to. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/leasecard"> /u/leasecard </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1grwhnz/nvr_access_software/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1grwhnz/nvr_access_software/">[comments]</a></span>

## This Week in Self-Hosted (15 November 2024)
 - [https://www.reddit.com/r/selfhosted/comments/1grvmdm/this_week_in_selfhosted_15_november_2024](https://www.reddit.com/r/selfhosted/comments/1grvmdm/this_week_in_selfhosted_15_november_2024)
 - RSS feed: $source
 - date published: 2024-11-15T12:49:49+00:00

<!-- SC_OFF --><div class="md"><p>Happy Friday, <a href="/r/selfhosted">r/selfhosted</a>! Linked below is the latest edition of <em>This Week in Self-Hosted</em>, a weekly newsletter recap of the latest activity in self-hosted software.</p> <p>This week&#39;s content includes significant updates to a well-known Photoshop alternative, notable software updates and launches, and a spotlight on <a href="https://github.com/jordan-dalby/ByteStash?ref=selfh.st">ByteStash</a> - a code snippet storage platform.</p> <p>Thanks, and as usual, feel free to reach out with feedback!</p> <hr/> <p><a href="https://selfh.st/newsletter/2024-11-15/?ref=reddit">Newsletter</a> | <a href="https://youtu.be/Dbh_y5oevXs">Watch on YouTube</a> | <a href="https://rss.com/podcasts/theselfhostcast/1755558?ref=selfh.st">Listen via Podcast</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/shol-ly"> /u/shol-ly </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comme

## Ping reboot
 - [https://www.reddit.com/r/selfhosted/comments/1grvhps/ping_reboot](https://www.reddit.com/r/selfhosted/comments/1grvhps/ping_reboot)
 - RSS feed: $source
 - date published: 2024-11-15T12:42:18+00:00

<!-- SC_OFF --><div class="md"><p>Hey all. Maybe there is somebody out there that is in same position and can use this cli tool</p> <p>Wrote a little cli app in GO that pings a target, and if not responding restart the OS: <a href="https://github.com/dabump/pingreboot">https://github.com/dabump/pingreboot</a></p> <p>I have an arch linux machine for all my self hosted containers in my garage that on occasion loses connectivity with hard wired router. I would then need to run to garage and restart. Linux is not the cause as I have tried multiple distros over the year.</p> <p>I&#39;ve not bothered to implement the windows part, so feel free to raise MR OR raise MR for general improvement</p> <p>For that one person who might use it, hope it serves well</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dabump"> /u/dabump </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1grvhps/ping_reboot/">[link]</a></span> &#32; <span><a href="h

## Starting My Self-Hosting Journey with a Homelab: Looking for Advice on Networking, PXE, and Racks.
 - [https://www.reddit.com/r/selfhosted/comments/1gru5ry/starting_my_selfhosting_journey_with_a_homelab](https://www.reddit.com/r/selfhosted/comments/1gru5ry/starting_my_selfhosting_journey_with_a_homelab)
 - RSS feed: $source
 - date published: 2024-11-15T11:20:42+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I&#39;m diving into the world of self-hosting and setting up a homelab, and I&#39;d love some advice from this amazing community! I’m fairly proficient with containers and Linux/Unix, but my networking experience is limited to end-user troubleshooting. I’ve spent the last few days researching the best options for my network gateway, access points, and a new NAS system, and I’ve sketched out a setup plan. Since this is also a bit of a hobby, I want everything to look nice and tidy in a rack with a glass door.</p> <p>Here’s my planned setup: <a href="https://i.imgur.com/ZPXTX9f.jpeg">https://i.imgur.com/ZPXTX9f.jpeg</a></p> <p>I do have a few questions and would really appreciate your input:</p> <ul> <li><p>Bare Metal Access for Servers</p> <ul> <li>I want to avoid using only Proxmox for VM provisioning—I’d like to install OSes directly on servers and manage containers on bare metal too. Is PXE the right solution for this?</li> <li>

## Your Complete Open Source Virtualization Guide For Getting Started With XCP-ng & Xen Orchestra
 - [https://www.reddit.com/r/selfhosted/comments/1grswla/your_complete_open_source_virtualization_guide](https://www.reddit.com/r/selfhosted/comments/1grswla/your_complete_open_source_virtualization_guide)
 - RSS feed: $source
 - date published: 2024-11-15T09:48:57+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1grswla/your_complete_open_source_virtualization_guide/"> <img src="https://external-preview.redd.it/Arr4qZY9KzMsfa-hgS1aPC-DpdK5JBXLTy4uYEJQPRU.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=50d418091983a905da35fff01b2320db9b37f45a" alt="Your Complete Open Source Virtualization Guide For Getting Started With XCP-ng &amp; Xen Orchestra" title="Your Complete Open Source Virtualization Guide For Getting Started With XCP-ng &amp; Xen Orchestra" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lawrencesystems"> /u/lawrencesystems </a> <br/> <span><a href="https://youtu.be/2wMmSm_ZeZ4?si=w9qpebcdygwdMEYI">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1grswla/your_complete_open_source_virtualization_guide/">[comments]</a></span> </td></tr></table>

## Looking for a Website Monitoring Tool with Alerts, Reporting, and HTML Keyword Checks
 - [https://www.reddit.com/r/selfhosted/comments/1grsoym/looking_for_a_website_monitoring_tool_with_alerts](https://www.reddit.com/r/selfhosted/comments/1grsoym/looking_for_a_website_monitoring_tool_with_alerts)
 - RSS feed: $source
 - date published: 2024-11-15T09:32:04+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a tool to monitor whether a website is up and send an alert if it&#39;s down. The tool should meet the following criteria:</p> <ol> <li><strong>Basic Uptime Monitoring</strong>: Ability to check if the website is online.</li> <li><strong>Detailed Reporting</strong>: Include metrics like response time and historical uptime data.</li> <li><strong>Custom Content Verification</strong>: Not just check HTTP status codes but also verify if specific keywords or elements exist in the HTML response.</li> <li><strong>Alerting System</strong>: Send alerts (via email, webhook etc...) when the site goes down or fails keyword checks.</li> </ol> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FancyDiePancy"> /u/FancyDiePancy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1grsoym/looking_for_a_website_monitoring_tool_with_alerts/">[link]</a></span> &#32; <span><a href="https://www.reddit.c

## What are some tools you'd love to see self-hosted, but currently lack decent open-source or self-hostable alternatives?
 - [https://www.reddit.com/r/selfhosted/comments/1grsovx/what_are_some_tools_youd_love_to_see_selfhosted](https://www.reddit.com/r/selfhosted/comments/1grsovx/what_are_some_tools_youd_love_to_see_selfhosted)
 - RSS feed: $source
 - date published: 2024-11-15T09:31:54+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/ParticularPumpkin933"> /u/ParticularPumpkin933 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1grsovx/what_are_some_tools_youd_love_to_see_selfhosted/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1grsovx/what_are_some_tools_youd_love_to_see_selfhosted/">[comments]</a></span>

## OpenSSL SSL Cert Error "unable to get local issuer certificate"
 - [https://www.reddit.com/r/selfhosted/comments/1grsiax/openssl_ssl_cert_error_unable_to_get_local_issuer](https://www.reddit.com/r/selfhosted/comments/1grsiax/openssl_ssl_cert_error_unable_to_get_local_issuer)
 - RSS feed: $source
 - date published: 2024-11-15T09:17:20+00:00

<!-- SC_OFF --><div class="md"><p>Runninb Ubuntu 22.04 LTS.</p> <p>Was trying out my SSL cert tonight using openssl. For the most part, everything seems to be working fine, but I noticed an error.</p> <p>``` CONNECTED(000011D4) depth=1 C = US, O = Let&#39;s Encrypt, CN = E5</p> <p>verify error:num=20:unable to get local issuer certificate</p> <p>verify return:1 depth=0 CN = domain.com</p> <h2>verify return:1</h2> <p>Certificate chain 0 s:CN = domain.com i:C = US, O = Let&#39;s Encrypt, CN = E5 a:PKEY: id-ecPublicKey, 256 (bit); sigalg: ecdsa-with-SHA384 v:NotBefore: Sep 20 14:17:22 2024 GMT; NotAfter: Dec 18 14:17:21 2024 GMT 1 s:C = US, O = Let&#39;s Encrypt, CN = E5 i:C = US, O = Internet Security Research Group, CN = ISRG Root X1 a:PKEY: id-ecPublicKey, 384 (bit); sigalg: RSA-SHA256 v:NotBefore: Mar 13 00:00:00 2024 GMT; NotAfter: Mar 12 23:59:59 2027 GMT ```</p> <p>The error in particular is:</p> <p><code> verify error:num=20:unable to get local issuer certificate </code></p> <p>

## Trying to come out of Apple Ecosystem - Looking for Self-Hosted iPhone Backup Solution
 - [https://www.reddit.com/r/selfhosted/comments/1grsgmq/trying_to_come_out_of_apple_ecosystem_looking_for](https://www.reddit.com/r/selfhosted/comments/1grsgmq/trying_to_come_out_of_apple_ecosystem_looking_for)
 - RSS feed: $source
 - date published: 2024-11-15T09:13:43+00:00

<!-- SC_OFF --><div class="md"><h2>Current Setup</h2> <ul> <li><strong>Hardware</strong>: Debian on Dell Hardware running headless</li> <li><strong>Reverse Proxy</strong>: Caddy</li> </ul> <h2>Currently Self-Hosting (docker containers)</h2> <ul> <li><strong>Storage/Media</strong>: Nextcloud, Immich, Plex</li> <li><strong>Passwords</strong>: Vaultwarden</li> <li><strong>DNS Ad Block</strong>: Technitium</li> <li><strong>Documents</strong>: Paperless-NGX</li> <li><strong>Audio</strong>: Audiobookshelf, Libation</li> </ul> <h2>The Challenge</h2> <p>I&#39;ve successfully migrated most of my services away from big tech companies as part of my journey toward digital privacy.</p> <p>However, I&#39;m still tied to a 50GB iCloud subscription solely because my iPhone backup (mostly Messages) is around 9GB. Since iPhones can wirelessly backup to Macs, I&#39;m curious if anyone has worked on reverse engineering this protocol for a self-hosted solution?</p> <p>I&#39;d be interested in contributin

## New Application (immich-share-proxy): Expose Immich shares safely with the public
 - [https://www.reddit.com/r/selfhosted/comments/1grs47a/new_application_immichshareproxy_expose_immich](https://www.reddit.com/r/selfhosted/comments/1grs47a/new_application_immichshareproxy_expose_immich)
 - RSS feed: $source
 - date published: 2024-11-15T08:47:57+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1grs47a/new_application_immichshareproxy_expose_immich/"> <img src="https://external-preview.redd.it/aM0GC_rIlgkRYDbSqX3FB8Mvl8bn-feIWwzM2pI-_24.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=501d17c56889a36cdade1fced15c9546262ef401" alt="New Application (immich-share-proxy): Expose Immich shares safely with the public" title="New Application (immich-share-proxy): Expose Immich shares safely with the public" /> </a> </td><td> <!-- SC_OFF --><div class="md"><h1>TL;DR</h1> <p><strong>Source:</strong> <a href="https://github.com/11notes/docker-immich-share-proxy">11notes/immich-share-proxy</a><br/> <strong>Target audience:</strong> <em>people who want to share their albums publicly without exposing Immich itself</em><br/> <strong>Skill level required:</strong> <em>low - medium</em><br/> <strong>Problem solved:</strong> <em>securely share Immich shared links</em><br/> <strong>IDGAF factor:</strong> 2/10</p> <h1>SCRE

## Synology NAS and Nginx Proxy Manager for Home Domain and local use only.
 - [https://www.reddit.com/r/selfhosted/comments/1grs2m9/synology_nas_and_nginx_proxy_manager_for_home](https://www.reddit.com/r/selfhosted/comments/1grs2m9/synology_nas_and_nginx_proxy_manager_for_home)
 - RSS feed: $source
 - date published: 2024-11-15T08:44:32+00:00

<!-- SC_OFF --><div class="md"><p>hello friends. </p> <p>I am new to the homelab selfhosted paradise. its a great area to experiment. </p> <p>so i installed many docker containers, all of them use different ports and after some time it gets really a bit messy with all the numbers. so i wanted to clean things up a bit. </p> <p>Its just for INTERNAL USE! i only want to connect to my homelab via the Synology VPN, so i dont want to open up any services to the internet! the local domain just needs to work for my homelab use. </p> <p>first i used PIHOLE to add an A NAME RECORD domain to the Synology NAS - lets call it HOMELAB. then i made CNAME subdomains for the services. NAS.HOMELAB, PI.HOMELAB, PORTAINER.HOMELAB,... </p> <p>and then in combination with the Synology Proxy Manager i configured those subdomains and forwarded them to the different services by forwarding the port. and this works great as long as the system is connected to the internet.</p> <p>But when i block the Synology fr

## Unable to signup for SMTP2GO
 - [https://www.reddit.com/r/selfhosted/comments/1grs2mf/unable_to_signup_for_smtp2go](https://www.reddit.com/r/selfhosted/comments/1grs2mf/unable_to_signup_for_smtp2go)
 - RSS feed: $source
 - date published: 2024-11-15T08:44:32+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I know it&#39;s not exactly related to self-hosting, but email and smtp2go are often talked about here so I figure someone might have related experience.</p> <p>I got a .org domain from cloudflare yesterday and I wanted to set-up something like mailcow locally with smtp2go as a relay so I don&#39;t have to worry too much about my email getting delivered. The issue is that when I try to sign up on the free plan I get &quot;Error code 6 - Service unavailable.&quot;</p> <p>I tried reaching out to support but the response was &quot;As part of new account creation, our system performs several automated checks. If any of these checks fails for whatever reason, the system returns an error code 6 - service unavailable. The specific cause of failure is not disclosed, unfortunately.&quot;, which doesn&#39;t help much, and then they prompted me to look for another smtp provider..</p> <p>Has anyone experienced this and were you able to sign up, or should 

## Needhelp with blocked indexers in prowlarr
 - [https://www.reddit.com/r/selfhosted/comments/1grrz80/needhelp_with_blocked_indexers_in_prowlarr](https://www.reddit.com/r/selfhosted/comments/1grrz80/needhelp_with_blocked_indexers_in_prowlarr)
 - RSS feed: $source
 - date published: 2024-11-15T08:36:59+00:00

<!-- SC_OFF --><div class="md"><p>Windows No docker</p> <p>Some indexers in prowlarr are giving this DNS....IPv6 error, they&#39;re just basically blocked in my country from the little research that I did. Some suggestions that I came across was to use a VPN and a socs5 proxy on qbit then connect prowlarr onto it. </p> <p>But I live in a 3rd world where torrentting without a VPN isn&#39;t really a concern. And I don&#39;t want to spend money on something just to make these 3-5 failing indexers work.</p> <p>Any suggestion is appreciated. Also I&#39;m using a backup pc at the moment, it doesnt support virtualization.</p> <p>TIA!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BadongkaDonk"> /u/BadongkaDonk </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1grrz80/needhelp_with_blocked_indexers_in_prowlarr/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1grrz80/needhelp_with_blocked_indexer

## Anyone interested in a domain?
 - [https://www.reddit.com/r/selfhosted/comments/1grqyf3/anyone_interested_in_a_domain](https://www.reddit.com/r/selfhosted/comments/1grqyf3/anyone_interested_in_a_domain)
 - RSS feed: $source
 - date published: 2024-11-15T07:20:44+00:00

<!-- SC_OFF --><div class="md"><p>Looking to sell my domain “poisonhosting.com” local ISP didn’t offer the upload speed I needed. Been holding on to it for a little while. Sorry if this isn’t allowed! Thanks :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Will_Smyth"> /u/Will_Smyth </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1grqyf3/anyone_interested_in_a_domain/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1grqyf3/anyone_interested_in_a_domain/">[comments]</a></span>

## Why Immich over Photoprism?
 - [https://www.reddit.com/r/selfhosted/comments/1grql5f/why_immich_over_photoprism](https://www.reddit.com/r/selfhosted/comments/1grql5f/why_immich_over_photoprism)
 - RSS feed: $source
 - date published: 2024-11-15T06:54:17+00:00

<!-- SC_OFF --><div class="md"><p>I’ve noticed how much more popular immich is on this subreddit when compared to photoprism. I’ve personally never used immich, but have been hosting photo prism for a few years now.</p> <p>When I was comparing both in the past, I remember immich lacking a few features, so I decided to go with photoprism. That being said, it looks like I might be missing something here.</p> <p>Do you use immich for managing and storing your photos? Why did you choose immich over photoprism?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pfassina"> /u/pfassina </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1grql5f/why_immich_over_photoprism/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1grql5f/why_immich_over_photoprism/">[comments]</a></span>

## caddy set up
 - [https://www.reddit.com/r/selfhosted/comments/1grpefn/caddy_set_up](https://www.reddit.com/r/selfhosted/comments/1grpefn/caddy_set_up)
 - RSS feed: $source
 - date published: 2024-11-15T05:35:37+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1grpefn/caddy_set_up/"> <img src="https://a.thumbs.redditmedia.com/vLHKKOEcnVq5k-6LrQaX7NiisibveSC2g12-nd5ITF8.jpg" alt="caddy set up" title="caddy set up" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello, I&#39;m trying to get Tailscale set up with caddy in unraid. I&#39;m using immich as the test case for the reverse proxy. Been using chatgpt and Claude for about 2 weeks trying to troubleshoot things but feel I&#39;m just going in circles. Whenever I go to the domain I&#39;ve set up for immich it just pulls up the unraid GUI in http. I&#39;ve attached screenshots on for cloudflare, the caddy container and the caddy logs unraid shows.</p> <p>This is the YouTube tutorial I was trying to follow, <a href="https://youtu.be/Vt4PDUXB%5C_fg?si=cUmoXjIFIIUyFXWB">https://youtu.be/Vt4PDUXB\_fg?si=cUmoXjIFIIUyFXWB</a>. This is also the latest version of the caddy file Claude generated for me. Pretty new at all this

## Benefit of 2 Ethernet ports?
 - [https://www.reddit.com/r/selfhosted/comments/1grp2tu/benefit_of_2_ethernet_ports](https://www.reddit.com/r/selfhosted/comments/1grp2tu/benefit_of_2_ethernet_ports)
 - RSS feed: $source
 - date published: 2024-11-15T05:15:21+00:00

<!-- SC_OFF --><div class="md"><p>I just got the UGreen DXP4800 which has two Ethernet ports. What’s the benefit of it? Can I connect both ports to the same router the speed up the connection?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ETA_son"> /u/ETA_son </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1grp2tu/benefit_of_2_ethernet_ports/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1grp2tu/benefit_of_2_ethernet_ports/">[comments]</a></span>

## Thinking of Migrating My Personal Email to MXroute
 - [https://www.reddit.com/r/selfhosted/comments/1grp2qd/thinking_of_migrating_my_personal_email_to_mxroute](https://www.reddit.com/r/selfhosted/comments/1grp2qd/thinking_of_migrating_my_personal_email_to_mxroute)
 - RSS feed: $source
 - date published: 2024-11-15T05:15:13+00:00

<!-- SC_OFF --><div class="md"><p>Have been using protonmail over 7 years now, and I appreciate its E2E encryption for privacy. Although I understand that, theoretically, emails could be viewed as they pass through Proton’s servers before encryption, I feel reassured knowing my stored emails are protected. However, while E2E is great, it has its downsides, especially with content searching. To search email content, I need to enable &quot;search message content&quot; in the browser or protonmail app, which downloads and indexes all emails. This process, and the actual searching itself, can be slow, with results sometimes appearing in a random order.</p> <p>For my needs, strict E2E encryption isn’t essential, as I’m not particularly concerned about government surveillance. My primary goal is simply to avoid big companies (Gmail, Outlook, etc.) looking at my data, which was why I initially chose protonmail. Recently, I came across MXroute and am considering a switch, but I haven’t seen 

## Best OVH server for around 50-60$ a month?
 - [https://www.reddit.com/r/selfhosted/comments/1grmnu5/best_ovh_server_for_around_5060_a_month](https://www.reddit.com/r/selfhosted/comments/1grmnu5/best_ovh_server_for_around_5060_a_month)
 - RSS feed: $source
 - date published: 2024-11-15T02:58:48+00:00

<!-- SC_OFF --><div class="md"><p>Looking for a server that i can host off OVH for 50-60$ a month just to host a couple game servers for friends and use to mess around with from time to time.<br/> Was looking at the KS-GAME server that features an i7 7700k and 64GB of ram for about 50$ a month it seems like a good deal but is there anything that i am missing that might be a little bit better for the same price or just a bit more?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dunsparth"> /u/Dunsparth </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1grmnu5/best_ovh_server_for_around_5060_a_month/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1grmnu5/best_ovh_server_for_around_5060_a_month/">[comments]</a></span>

## MinIO hosters who push backup files offsite, how did you implement this?
 - [https://www.reddit.com/r/selfhosted/comments/1grmbgn/minio_hosters_who_push_backup_files_offsite_how](https://www.reddit.com/r/selfhosted/comments/1grmbgn/minio_hosters_who_push_backup_files_offsite_how)
 - RSS feed: $source
 - date published: 2024-11-15T02:40:49+00:00

<!-- SC_OFF --><div class="md"><p>The last time I looked into MinIO, there was an option to automatically transfer files to a remote S3 storage. However, I want to do some operations first (encrypt locally) before it&#39;s transferred to AWS. I did not find a specification for hooks or plugins which would&#39;ve been nice to have.</p> <p>It does have <a href="https://min.io/docs/minio/linux/administration/monitoring/bucket-notifications.html">Bucket Notification</a> which can fire events at the Bucket or Object level and I could trigger a webhook, and I guess it is probably gonna need queues to be able to handle multiple files coming in at the same time, so I&#39;m wondering how some of you implement encrypt-and-push pipelines like this, and whether something like this already exists before I reinvent the wheel.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/floofcode"> /u/floofcode </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/

## Looking for a photo library with folder structure browsing via the web app
 - [https://www.reddit.com/r/selfhosted/comments/1grm01c/looking_for_a_photo_library_with_folder_structure](https://www.reddit.com/r/selfhosted/comments/1grm01c/looking_for_a_photo_library_with_folder_structure)
 - RSS feed: $source
 - date published: 2024-11-15T02:24:00+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a self hosted photo library with folder structure like browser option in it&#39;s web app, user definable folder permissions, and the ability to access the folders via SMB without causing an issue.</p> <p>Synology photos shared space almost get&#39;s there, it has has the folder structure style, and I can do whatever I want via SMB without causing an issue. The two big issues:</p> <ol> <li> permissions control only goes 2 folder levels deep</li> <li>there&#39;s no way for end users to share or restrict access to their own folders on shared space since only users with &quot;full access&quot; not custom access, can set permissions control. </li> </ol> <p>I&#39;ve been looking at all the posts on the various popular options on here, but it&#39;s hard to really tell without trying a bunch of them out.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/transclimberbabe"> /u/transclimberbabe </a> <br/

## Need help buying an AI module.
 - [https://www.reddit.com/r/selfhosted/comments/1grlr7o/need_help_buying_an_ai_module](https://www.reddit.com/r/selfhosted/comments/1grlr7o/need_help_buying_an_ai_module)
 - RSS feed: $source
 - date published: 2024-11-15T02:11:11+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve recently deployed Immich on my Raspberry Pi 5 and am absolutely loving it! Now, I’d like to add an AI module, similar to what the Raspberry Pi AI Kit offers, alongside my NVMe storage. I was surprised to see there are actually options to make this possible!</p> <p>One product that caught my attention is Pimoroni&#39;s NVMe Base Duo for the Raspberry Pi 5, which should support both storage and an AI module. However, I&#39;m having trouble finding an M.2-based AI module available in the UK that would work with this setup.</p> <p>If anyone has recommendations or knows where I could find just the AI module, I’d really appreciate your help. Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Trebuchet56"> /u/Trebuchet56 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1grlr7o/need_help_buying_an_ai_module/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/s

## In-Flight Entertainment for Captive Portal
 - [https://www.reddit.com/r/selfhosted/comments/1grll3f/inflight_entertainment_for_captive_portal](https://www.reddit.com/r/selfhosted/comments/1grll3f/inflight_entertainment_for_captive_portal)
 - RSS feed: $source
 - date published: 2024-11-15T02:02:22+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m experimenting with a captive portal on my guest Wi-Fi network and I thought it might be fun to set up something like the airlines have, specifically something like Southwest where you log into their Wi-Fi and can watch movies and whatnot from your device. I did a bit of research and didn&#39;t see anything. A pre-made solution would be awesome, but I have a feeling that doesn&#39;t exist. Any suggestions would be great!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OkBet5823"> /u/OkBet5823 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1grll3f/inflight_entertainment_for_captive_portal/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1grll3f/inflight_entertainment_for_captive_portal/">[comments]</a></span>

## What awesome services am I missing?
 - [https://www.reddit.com/r/selfhosted/comments/1grlgai/what_awesome_services_am_i_missing](https://www.reddit.com/r/selfhosted/comments/1grlgai/what_awesome_services_am_i_missing)
 - RSS feed: $source
 - date published: 2024-11-15T01:55:26+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1grlgai/what_awesome_services_am_i_missing/"> <img src="https://b.thumbs.redditmedia.com/peAsdzBYSH53Sg8EpRWM739UZZKZSjgr9hB1zNiedHY.jpg" alt="What awesome services am I missing?" title="What awesome services am I missing?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/l5imwdz42z0e1.png?width=1908&amp;format=png&amp;auto=webp&amp;s=3d12ead890da7466d640aceb9da35542c173c3cb">https://preview.redd.it/l5imwdz42z0e1.png?width=1908&amp;format=png&amp;auto=webp&amp;s=3d12ead890da7466d640aceb9da35542c173c3cb</a></p> <p>Help my humble setup out (only a year in)! What great services am I missing out on? Everything runs on a single proxmox machine with the exception of the backup server (for obvious reasons). Also, I&#39;m not really a big media guy so I don&#39;t have a need for Plex or the arr&#39;s.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user

## Looking for name of an app - "self hosted steam"
 - [https://www.reddit.com/r/selfhosted/comments/1grkthl/looking_for_name_of_an_app_self_hosted_steam](https://www.reddit.com/r/selfhosted/comments/1grkthl/looking_for_name_of_an_app_self_hosted_steam)
 - RSS feed: $source
 - date published: 2024-11-15T01:23:06+00:00

<!-- SC_OFF --><div class="md"><p>A while back someone posted a project that was a self hosted steam type thing for DRM free installers. I remember that it had a somewhat vulgar name but then changed it to something else at the communities suggestion. Does anyone remember what the application was?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Bissquitt"> /u/Bissquitt </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1grkthl/looking_for_name_of_an_app_self_hosted_steam/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1grkthl/looking_for_name_of_an_app_self_hosted_steam/">[comments]</a></span>

## Securing apps with Cloudflared
 - [https://www.reddit.com/r/selfhosted/comments/1grjod3/securing_apps_with_cloudflared](https://www.reddit.com/r/selfhosted/comments/1grjod3/securing_apps_with_cloudflared)
 - RSS feed: $source
 - date published: 2024-11-15T00:26:14+00:00

<!-- SC_OFF --><div class="md"><p>Posting here to get opinions on how secure this server set up is </p> <p>I have Cloud Flared tunnels set up for 3 sub domains with https</p> <p><a href="https://chat.my-domain.net">https://chat.my-domain.net</a> (Mattermost)</p> <p><a href="https://kwix.my-domain.net">https://kwix.my-domain.net</a> (Kwix)</p> <p><a href="https://nextcloud.my-domain.net">https://nextcloud.my-domain.net</a> (Nextcloud) </p> <p>All hosted on one machine with 64 gb ram and 12 core processor. Each service is running in docker. The corresponding port is exposed on in Ubuntu firewall and on my home router. </p> <p>Other than the memory consumption of running 3 separate tunnels along with the apps, is there any other concerns with this set up? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/__jenkins"> /u/__jenkins </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1grjod3/securing_apps_with_cloudflared/">[link]</a>

## Any Windmill/Airflow users try Kestra?
 - [https://www.reddit.com/r/selfhosted/comments/1grjay7/any_windmillairflow_users_try_kestra](https://www.reddit.com/r/selfhosted/comments/1grjay7/any_windmillairflow_users_try_kestra)
 - RSS feed: $source
 - date published: 2024-11-15T00:08:16+00:00

<!-- SC_OFF --><div class="md"><p>I am currently using Windmill, and I&#39;ve heard a lot of good things about Kestra and was thinking about giving it a go.</p> <p>Has anyone used both and know how they compare?</p> <p>I am mostly using Windmill as an alternative to a lot of python/js cron scripts. No as much for the UI building.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MidnightProgrammer"> /u/MidnightProgrammer </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1grjay7/any_windmillairflow_users_try_kestra/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1grjay7/any_windmillairflow_users_try_kestra/">[comments]</a></span>

