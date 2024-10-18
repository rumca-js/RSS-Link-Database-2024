# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Infisical Agent + Portainer + Git = Stack deployments w. secure secrets?
 - [https://www.reddit.com/r/selfhosted/comments/1g62s1q/infisical_agent_portainer_git_stack_deployments_w](https://www.reddit.com/r/selfhosted/comments/1g62s1q/infisical_agent_portainer_git_stack_deployments_w)
 - RSS feed: $source
 - date published: 2024-10-17T22:06:48+00:00

<!-- SC_OFF --><div class="md"><p>At the moment, I&#39;m making heavy use of Portainer&#39;s built in environment variable functionality on stack deployment to manually populate secret env values associated with my stacks. That way I can avoid adding them to the .env files pushed to git (where I pull my compose spec&#39;s from). Not the best solution, and think its time to move to some kind of vault service which can pull secrets from at build time.</p> <p>I&#39;m reading over the doc&#39;s for Infisical which look like it could be workable. Though I want to check if anyone has tried to leverage the Infisical Agent for template generation (run under its own docker container), and then used the agent to push populated environment and config files to a bind volume, which is then referenced by the stacks using the env_file param/ compose spec? That seems to be the best option for those using Portainer to deploy stacks from git. But want to make sure I&#39;m thinking about it right.</p> <

## Security risks of self-hosted services with Tailscale but without additional security like fail2ban/crowdsec?
 - [https://www.reddit.com/r/selfhosted/comments/1g61rpp/security_risks_of_selfhosted_services_with](https://www.reddit.com/r/selfhosted/comments/1g61rpp/security_risks_of_selfhosted_services_with)
 - RSS feed: $source
 - date published: 2024-10-17T21:20:28+00:00

<!-- SC_OFF --><div class="md"><p>Hey <a href="/r/selfhosted">r/selfhosted</a>,</p> <p>I’m currently self-hosting a bunch of services at home and using Tailscale for access from my personal devices when I’m away. I haven’t implemented any additional security measures like fail2ban or crowdsec yet.</p> <p>My question is: What’s the actual risk of not having these extra security layers if I’m not exposing my services directly to the internet via port forwarding? I’m trying to understand if I’m leaving any significant vulnerabilities open or if the Tailscale setup is secure enough on its own.</p> <p>Would love to hear your thoughts and experiences. Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/3millionmax"> /u/3millionmax </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g61rpp/security_risks_of_selfhosted_services_with/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g61rpp/secur

## Does this 5000$ PC for LLM inference make sense?
 - [https://www.reddit.com/r/selfhosted/comments/1g610gh/does_this_5000_pc_for_llm_inference_make_sense](https://www.reddit.com/r/selfhosted/comments/1g610gh/does_this_5000_pc_for_llm_inference_make_sense)
 - RSS feed: $source
 - date published: 2024-10-17T20:47:39+00:00

<!-- SC_OFF --><div class="md"><ul> <li>AMD Ryzen 5 9600X - $279.00</li> <li>Corsair A115 - $89.99</li> <li>Gigabyte X870 EAGLE WIFI7 - $219.99</li> <li>G.Skill Ripjaws S5 64 GB - $147.99</li> <li>Kingston NV2 1 TB - $56.99</li> <li>2 x RTX 4090 <ul> <li>Gigabyte AERO OC GeForce RTX 4090 24 GB - $1949.99</li> <li>Gigabyte AERO OC GeForce RTX 4090 24 GB - $1949.99</li> </ul></li> <li>Corsair 4000D Airflow - $79.97</li> <li>SeaSonic VERTEX GX-1200 1200 W - $254.64</li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kimonk"> /u/kimonk </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g610gh/does_this_5000_pc_for_llm_inference_make_sense/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g610gh/does_this_5000_pc_for_llm_inference_make_sense/">[comments]</a></span>

## Y'all encrypting your servers? Reboot/SSH issues?
 - [https://www.reddit.com/r/selfhosted/comments/1g5zaxf/yall_encrypting_your_servers_rebootssh_issues](https://www.reddit.com/r/selfhosted/comments/1g5zaxf/yall_encrypting_your_servers_rebootssh_issues)
 - RSS feed: $source
 - date published: 2024-10-17T19:33:35+00:00

<!-- SC_OFF --><div class="md"><h1>Got a Ubuntu server on a laptop, reboot via SSH requires LUKS decryption before SSH starts up again. (remote lockout)</h1> <p>i.e. I need to physically open the laptop/server and type in the password and can&#39;t do much remote work as a result.</p> <h1>I see dropbear, usb keyfiles, etc as past solutions... what are y&#39;all doing?</h1> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PossibleCulture4329"> /u/PossibleCulture4329 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5zaxf/yall_encrypting_your_servers_rebootssh_issues/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5zaxf/yall_encrypting_your_servers_rebootssh_issues/">[comments]</a></span>

## Outbound MTA-STS validity checker
 - [https://www.reddit.com/r/selfhosted/comments/1g5yseb/outbound_mtasts_validity_checker](https://www.reddit.com/r/selfhosted/comments/1g5yseb/outbound_mtasts_validity_checker)
 - RSS feed: $source
 - date published: 2024-10-17T19:11:13+00:00

<!-- SC_OFF --><div class="md"><p>I find <a href="https://havedane.net/">https://havedane.net/</a> very useful for seeing if my mail server will prevent sending to mail servers with invalid SMTP DANE set up.</p> <p>Does anyone know of a similar service to check if my outbound MTA-STS validation is functioning correctly?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/slfyst"> /u/slfyst </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5yseb/outbound_mtasts_validity_checker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5yseb/outbound_mtasts_validity_checker/">[comments]</a></span>

## Server for managing/viewing large surveillance/NVR archive
 - [https://www.reddit.com/r/selfhosted/comments/1g5y5f1/server_for_managingviewing_large_surveillancenvr](https://www.reddit.com/r/selfhosted/comments/1g5y5f1/server_for_managingviewing_large_surveillancenvr)
 - RSS feed: $source
 - date published: 2024-10-17T18:44:27+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;m looking for recommendations for a media server that can handle a 2+TB collection of tens of thousands of video files. I have several years of archives from my NVR system (AgentDVR), from multiple cameras. The NVR interface gets bogged down if I don&#39;t archive older files to &quot;cold&quot; storage. I would like to be able to browse/play/delete video clips via a browser-based interface, with them organized by file date &amp; folder. I&#39;m looking for something that does thumbnailing and on-the-fly transcoding (files are all in mkv containers and a mix of H264/265 codecs). Tagging functionality would be nice. I tried Jellyfin and it bogged down my entire system; it also seems to be too much for web-based file managers like FileRun or Nextcloud. Availability of a Docker image is a plus.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/friendOfHeisenberg"> /u/friendOfHeisenberg </a> <br/> <span><a hr

## Yet Another Homepage Dashboard
 - [https://www.reddit.com/r/selfhosted/comments/1g5xciy/yet_another_homepage_dashboard](https://www.reddit.com/r/selfhosted/comments/1g5xciy/yet_another_homepage_dashboard)
 - RSS feed: $source
 - date published: 2024-10-17T18:09:47+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g5xciy/yet_another_homepage_dashboard/"> <img src="https://preview.redd.it/e17137qfxcvd1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=ae1f0cced7d8ac7f316367bbf41c466e21f2dcf5" alt="Yet Another Homepage Dashboard" title="Yet Another Homepage Dashboard" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RyanSetzer"> /u/RyanSetzer </a> <br/> <span><a href="https://i.redd.it/e17137qfxcvd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5xciy/yet_another_homepage_dashboard/">[comments]</a></span> </td></tr></table>

## Narrowlink to connect VM to the devices on home network?
 - [https://www.reddit.com/r/selfhosted/comments/1g5x6fw/narrowlink_to_connect_vm_to_the_devices_on_home](https://www.reddit.com/r/selfhosted/comments/1g5x6fw/narrowlink_to_connect_vm_to_the_devices_on_home)
 - RSS feed: $source
 - date published: 2024-10-17T18:02:18+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;d like to cast a browser tab from my Ubuntu VM to my TV, which has a Chromecast stick. The issue is that the VM is not on WiFi and does not have acecss to the Chromecast. From my cursory understanding of <a href="http://www.Narrowlink.com">Narrowlink</a>, it may be able to address this by allowing the VM access to devices on WiFi. Has anyone used it in this way?Is it possible?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rmalh"> /u/rmalh </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5x6fw/narrowlink_to_connect_vm_to_the_devices_on_home/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5x6fw/narrowlink_to_connect_vm_to_the_devices_on_home/">[comments]</a></span>

## Reverse proxy suggestions
 - [https://www.reddit.com/r/selfhosted/comments/1g5wx39/reverse_proxy_suggestions](https://www.reddit.com/r/selfhosted/comments/1g5wx39/reverse_proxy_suggestions)
 - RSS feed: $source
 - date published: 2024-10-17T17:51:29+00:00

<!-- SC_OFF --><div class="md"><p>Anyone know of a reverse proxy with a gui that is a vm? Dealing with docker outside of unraid is a non starter for me.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CaptainRan"> /u/CaptainRan </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5wx39/reverse_proxy_suggestions/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5wx39/reverse_proxy_suggestions/">[comments]</a></span>

## VPS + Tailscale + NPM vs Cloudflare Tunnels
 - [https://www.reddit.com/r/selfhosted/comments/1g5wa5f/vps_tailscale_npm_vs_cloudflare_tunnels](https://www.reddit.com/r/selfhosted/comments/1g5wa5f/vps_tailscale_npm_vs_cloudflare_tunnels)
 - RSS feed: $source
 - date published: 2024-10-17T17:24:07+00:00

<!-- SC_OFF --><div class="md"><p>I’m curious as to what you all use to access your internal apps. I currently use both VPS + Tailscale + NPM and Cloudflare Tunnels, just depending on the app. I am toying with the idea of getting rid of Cloudflare tunnels and just running everything through NPM.</p> <p>For some insight, as of right now, the only thing I have running through Cloudflare is Guacamole. My Minecraft servers and a few other services are going through NPM on the VPS.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lonemuffin05"> /u/lonemuffin05 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5wa5f/vps_tailscale_npm_vs_cloudflare_tunnels/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5wa5f/vps_tailscale_npm_vs_cloudflare_tunnels/">[comments]</a></span>

## Self hosting services that are not the typical ones.
 - [https://www.reddit.com/r/selfhosted/comments/1g5voeb/self_hosting_services_that_are_not_the_typical](https://www.reddit.com/r/selfhosted/comments/1g5voeb/self_hosting_services_that_are_not_the_typical)
 - RSS feed: $source
 - date published: 2024-10-17T16:59:01+00:00

<!-- SC_OFF --><div class="md"><p>Hello all. I already have some experience deploying self hosted apps. I’m getting to a point where I don’t have any more ideas. I have a raspberry pi and just got a mini pc with good specs. What are your suggestions for cool projects apart from what’s usually shared like:</p> <ul> <li>Media Server </li> <li>NAS</li> <li>Cloud</li> <li>Home Assistant </li> <li>Photo management </li> </ul> <p>I was also thinking of deploying something related to AI like video-to-text translators or replace ChatGPT (I’m not really sure how much resource intensive it is).</p> <p>I really like doing this kind of projects, but I’m feeling kind of lost. It seems that nothing is interesting me. Thanks </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/InformationScared966"> /u/InformationScared966 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5voeb/self_hosting_services_that_are_not_the_typical/">[link]</a></span

## Can someone explain the powerDNS stack?
 - [https://www.reddit.com/r/selfhosted/comments/1g5vmad/can_someone_explain_the_powerdns_stack](https://www.reddit.com/r/selfhosted/comments/1g5vmad/can_someone_explain_the_powerdns_stack)
 - RSS feed: $source
 - date published: 2024-10-17T16:56:34+00:00

<!-- SC_OFF --><div class="md"><p>I’m sorry if this is out of scope, but I can’t get a straight answer for this</p> <p>I was looking at the documentation of powerDNS and it got me confused on how and where to use authority, reflector and dnsdist</p> <p>If I’m building a dns server and want to do a master/slave structure, do I still need the dnsdist?</p> <p>I understand that each machine will need to run the authority (one as master the other as slave) and the reflector (one for each for fallback)</p> <p>But since I’ll have two ips, I’ll configure both on the device and I won’t need the dnsdist, right?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nicoskaralis"> /u/nicoskaralis </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5vmad/can_someone_explain_the_powerdns_stack/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5vmad/can_someone_explain_the_powerdns_stack/">[comments]</a></spa

## Gravwell's response to the Enshitification trend
 - [https://www.reddit.com/r/selfhosted/comments/1g5vkmq/gravwells_response_to_the_enshitification_trend](https://www.reddit.com/r/selfhosted/comments/1g5vkmq/gravwells_response_to_the_enshitification_trend)
 - RSS feed: $source
 - date published: 2024-10-17T16:54:36+00:00

<!-- SC_OFF --><div class="md"><p>Gravwell 5.6.0 was released today, and with this new version we are giving our take on the whole <a href="https://en.wikipedia.org/wiki/Enshittification">Enshitification</a> trend you see today: 2 new FREE licensing options.</p> <ul> <li>Option 1 is a completely contactless tier (just install and go) designed for homelab and non-commercial use.</li> <li>Option 2 is a new Advanced tier for businesses that ups the FREE ingest limits to 50GB/day.</li> <li>All this, plus the existing Community Edition license allowing 14GB/day remains unchanged.</li> </ul> <p>For more details on these new options, please check out the official blog post. <a href="https://www.gravwell.io/blog/gravwell-5.6.0-new-license-tiers">https://www.gravwell.io/blog/gravwell-5.6.0-new-license-tiers</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dctootall"> /u/Dctootall </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g

## Best Docker/Portainer monitoring app for iOS
 - [https://www.reddit.com/r/selfhosted/comments/1g5vbin/best_dockerportainer_monitoring_app_for_ios](https://www.reddit.com/r/selfhosted/comments/1g5vbin/best_dockerportainer_monitoring_app_for_ios)
 - RSS feed: $source
 - date published: 2024-10-17T16:43:58+00:00

<!-- SC_OFF --><div class="md"><p>There is a list of Docker / Portainer apps on OS that essentially do (almost) the same things, but it can be difficult to know which one is better. I’ve already used two: WhaleDeck, which is specifically for Docker and costs $30 for lifetime Pro access, and Yomo, which supports both Docker and Portainer for free (or $1/year to remove ads).</p> <p>I started wondering if there’s anything you can do with WhaleDeck that you can’t with Yomo, and the same goes for other similar apps. So, I’m curious to know which app you use and prefer on iOS to monitor Docker and Portainer.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/wa_00"> /u/wa_00 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5vbin/best_dockerportainer_monitoring_app_for_ios/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5vbin/best_dockerportainer_monitoring_app_for_ios/">[comments]</a></span>

## Looking for Affordable and Easy-to-Use Server Provider Recommendations
 - [https://www.reddit.com/r/selfhosted/comments/1g5va5m/looking_for_affordable_and_easytouse_server](https://www.reddit.com/r/selfhosted/comments/1g5va5m/looking_for_affordable_and_easytouse_server)
 - RSS feed: $source
 - date published: 2024-10-17T16:42:19+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, I’m looking for suggestions on reliable, affordable server providers that are easy to set up and manage. I’ll be running a task-based photo-sharing app, so performance and scalability are important, but I also need something that’s cost-effective. Any recommendations or experiences you can share?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Balaji_02"> /u/Balaji_02 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5va5m/looking_for_affordable_and_easytouse_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5va5m/looking_for_affordable_and_easytouse_server/">[comments]</a></span>

## My solar-powered and self-hosted website
 - [https://www.reddit.com/r/selfhosted/comments/1g5umne/my_solarpowered_and_selfhosted_website](https://www.reddit.com/r/selfhosted/comments/1g5umne/my_solarpowered_and_selfhosted_website)
 - RSS feed: $source
 - date published: 2024-10-17T16:14:13+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g5umne/my_solarpowered_and_selfhosted_website/"> <img src="https://external-preview.redd.it/ibXkqqRearTqQ79THUrY0f9nemDvsL2OhlLNtES32NQ.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=f647636d8ecde845fd1a5dd13659119e3c0875c2" alt="My solar-powered and self-hosted website" title="My solar-powered and self-hosted website" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sheshbabu"> /u/sheshbabu </a> <br/> <span><a href="https://dri.es/my-solar-powered-and-self-hosted-website">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5umne/my_solarpowered_and_selfhosted_website/">[comments]</a></span> </td></tr></table>

## How many domains do you have and for what use?
 - [https://www.reddit.com/r/selfhosted/comments/1g5uei3/how_many_domains_do_you_have_and_for_what_use](https://www.reddit.com/r/selfhosted/comments/1g5uei3/how_many_domains_do_you_have_and_for_what_use)
 - RSS feed: $source
 - date published: 2024-10-17T16:04:36+00:00

<!-- SC_OFF --><div class="md"><p>I currently have one for professional use but it secretly contains all my services via subdomain. Thinking of getting another for my services plus one for family.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sexpusa"> /u/sexpusa </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5uei3/how_many_domains_do_you_have_and_for_what_use/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5uei3/how_many_domains_do_you_have_and_for_what_use/">[comments]</a></span>

## Can’t configure k8s helm traefik with default configuration + MetalLb
 - [https://www.reddit.com/r/selfhosted/comments/1g5ud55/cant_configure_k8s_helm_traefik_with_default](https://www.reddit.com/r/selfhosted/comments/1g5ud55/cant_configure_k8s_helm_traefik_with_default)
 - RSS feed: $source
 - date published: 2024-10-17T16:03:02+00:00

<!-- SC_OFF --><div class="md"><p>I have left the same message on traefik forum but it appears some questions will remain unanswered. So, I hope dear selfhosted community will be able to shed a light on my current predicament. Trying alone grind k8s with reverse proxy, previously used with docker/compose but want something with better granular control.</p> <p>My goal is to use external ip assigned to traefik in my case <a href="http://192.168.0.200/">192.168.0.200</a> and connect to whoami service.</p> <p>My cluster setup:</p> <pre><code>Pod Template: Labels: app.kubernetes.io/instance=traefik-1729174917-traefik-system app.kubernetes.io/managed-by=Helm app.kubernetes.io/name=traefik helm.sh/chart=traefik-32.1.1 Annotations: prometheus.io/path: /metrics prometheus.io/port: 9100 prometheus.io/scrape: true Service Account: traefik-1729174917 Containers: traefik-1729174917: Image: docker.io/traefik:v3.1.6 Ports: 9100/TCP, 9000/TCP, 8000/TCP, 8443/TCP Host Ports: 0/TCP, 0/TCP, 0/TCP, 0/TCP

## Selfhosted sharing-solution?
 - [https://www.reddit.com/r/selfhosted/comments/1g5u9yh/selfhosted_sharingsolution](https://www.reddit.com/r/selfhosted/comments/1g5u9yh/selfhosted_sharingsolution)
 - RSS feed: $source
 - date published: 2024-10-17T15:59:36+00:00

<!-- SC_OFF --><div class="md"><p><em>I found nothing fitting with search engines so I&#39;m asking here:</em><br/> <strong>I wanted to have a solution to share things between the local network, like just text/links but also pictures and files.</strong></p> <p>I found <a href="https://github.com/localsend/localsend">LocalSend</a> which is great but I would like a selfhosted solution and wanted to see if there are any alternatives or better solutions.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Several_Spend_979"> /u/Several_Spend_979 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5u9yh/selfhosted_sharingsolution/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5u9yh/selfhosted_sharingsolution/">[comments]</a></span>

## CA for Homelab
 - [https://www.reddit.com/r/selfhosted/comments/1g5u6bx/ca_for_homelab](https://www.reddit.com/r/selfhosted/comments/1g5u6bx/ca_for_homelab)
 - RSS feed: $source
 - date published: 2024-10-17T15:55:15+00:00

<!-- SC_OFF --><div class="md"><p>Hello altogether,</p> <p>for my homelab I am planning to deploy a PKI or CA.</p> <p>I did install a Microsoft PKI before, but I don’t have a Domain or AD in my Lab environment. So I tend to use linux, but I never got into the whole Linux PKI topic.</p> <p>The plan is to sign certificates for internal use aswell as client certificates for a vpn tunnel via dyndns.</p> <p>I mostly read about OpenSSL, is this fitting for my purpose?</p> <p>Thanks in advance</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/esreveRProXy"> /u/esreveRProXy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5u6bx/ca_for_homelab/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5u6bx/ca_for_homelab/">[comments]</a></span>

## So most of my services are exposed to the internet... kinda
 - [https://www.reddit.com/r/selfhosted/comments/1g5u63h/so_most_of_my_services_are_exposed_to_the](https://www.reddit.com/r/selfhosted/comments/1g5u63h/so_most_of_my_services_are_exposed_to_the)
 - RSS feed: $source
 - date published: 2024-10-17T15:54:59+00:00

<!-- SC_OFF --><div class="md"><p>So my setup is obviously internal by default, but I use a lot externally, and most of services are exposed to the internet, but I have cloudflare in place to prevent against ddosing (as if anyone&#39;s gonna do that to me anyways) and most applications are just set to only allow access to certain IPS, such as places I go to regularly, and on top of all this everything is secured with authelia. None of my containers are directly exposed to my lan or wan, everything is via nginx proxy mananger. Any recommendations for what else I should do for security purposes?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Safe-Perspective-767"> /u/Safe-Perspective-767 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5u63h/so_most_of_my_services_are_exposed_to_the/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5u63h/so_most_of_my_services_are_exposed_to_the/">[comm

## Auto-notification of home power outage
 - [https://www.reddit.com/r/selfhosted/comments/1g5twnl/autonotification_of_home_power_outage](https://www.reddit.com/r/selfhosted/comments/1g5twnl/autonotification_of_home_power_outage)
 - RSS feed: $source
 - date published: 2024-10-17T15:43:47+00:00

<!-- SC_OFF --><div class="md"><p>I saw this post here and want to ask something similar: <a href="https://www.reddit.com/r/selfhosted/comments/16e8sz5/how_to_monitor_home_network_get_alerts_if/">https://www.reddit.com/r/selfhosted/comments/16e8sz5/how_to_monitor_home_network_get_alerts_if/</a></p> <p>I&#39;d like to be alerted if the power goes out at my house. My internet is reliable and so the internet going down most likely means the power is out, so I&#39;m willing to accept that assumption. Is there some way that my cellphone or other internet-connected device would be alerted, that my home internet is down? I&#39;m picturing something like a dead-man&#39;s switch: if internet goes offline, phone app pushes a notification saying it lost connection to home. Not sure if I&#39;d need to host anything at home or just setup a simple script or app on my phone that pings home and pushes an alert if the ping fails a few times.</p> <p>Sorry if this is not the right place to ask - any sug

## Set up a photo server to share trip photos with my friends. This was my software dev friend’s immediate response about security is he right?
 - [https://www.reddit.com/r/selfhosted/comments/1g5tbq6/set_up_a_photo_server_to_share_trip_photos_with](https://www.reddit.com/r/selfhosted/comments/1g5tbq6/set_up_a_photo_server_to_share_trip_photos_with)
 - RSS feed: $source
 - date published: 2024-10-17T15:18:12+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g5tbq6/set_up_a_photo_server_to_share_trip_photos_with/"> <img src="https://b.thumbs.redditmedia.com/cb-ABj_slg5NNgWgFI3UcnZTSxM8QmY1lLOsQnuIwhE.jpg" alt="Set up a photo server to share trip photos with my friends. This was my software dev friend’s immediate response about security is he right? " title="Set up a photo server to share trip photos with my friends. This was my software dev friend’s immediate response about security is he right? " /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok_Minimum6419"> /u/Ok_Minimum6419 </a> <br/> <span><a href="https://www.reddit.com/gallery/1g5tbq6">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5tbq6/set_up_a_photo_server_to_share_trip_photos_with/">[comments]</a></span> </td></tr></table>

## Anyone know a Self-Hosted Discord Frontend?
 - [https://www.reddit.com/r/selfhosted/comments/1g5t7j7/anyone_know_a_selfhosted_discord_frontend](https://www.reddit.com/r/selfhosted/comments/1g5t7j7/anyone_know_a_selfhosted_discord_frontend)
 - RSS feed: $source
 - date published: 2024-10-17T15:13:08+00:00

<!-- SC_OFF --><div class="md"><p>Not a backend/server. Just a self-hosted frontend website that connects to the Discord servers.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/VeygaX"> /u/VeygaX </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5t7j7/anyone_know_a_selfhosted_discord_frontend/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5t7j7/anyone_know_a_selfhosted_discord_frontend/">[comments]</a></span>

## pros/cons of NASs
 - [https://www.reddit.com/r/selfhosted/comments/1g5soc1/proscons_of_nass](https://www.reddit.com/r/selfhosted/comments/1g5soc1/proscons_of_nass)
 - RSS feed: $source
 - date published: 2024-10-17T14:50:21+00:00

<!-- SC_OFF --><div class="md"><p>If i mainly have a media server and care about more storage ultimately, what is the difference between using an old gaming rig for a server and filling it with (lets say 5~) HDDs, </p> <p>versus getting a synology NAS and using the same exact harddrives?</p> <p>whats the benefit/trade offs?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dragrimmar"> /u/dragrimmar </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5soc1/proscons_of_nass/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5soc1/proscons_of_nass/">[comments]</a></span>

## Advice for a USB NAS Enclosure for Cold Storage and Backups
 - [https://www.reddit.com/r/selfhosted/comments/1g5rok6/advice_for_a_usb_nas_enclosure_for_cold_storage](https://www.reddit.com/r/selfhosted/comments/1g5rok6/advice_for_a_usb_nas_enclosure_for_cold_storage)
 - RSS feed: $source
 - date published: 2024-10-17T14:06:01+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g5rok6/advice_for_a_usb_nas_enclosure_for_cold_storage/"> <img src="https://b.thumbs.redditmedia.com/xYjPs1IxTBYUWkoUSoPO9CdyraAc6z81UueDGHI-gPg.jpg" alt="Advice for a USB NAS Enclosure for Cold Storage and Backups" title="Advice for a USB NAS Enclosure for Cold Storage and Backups" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I already have a mini PC that I use as a server, and I&#39;m looking to add an enclosure similar to a NAS that can hold 3 or 4 HDDs. My goal is to set up some cold storage, so a simple USB 3 enclosure would be enough for me.</p> <p>I don&#39;t need the drives to run constantly. I prefer them to go into sleep mode when not in use, even if it means waiting 5 seconds for them to spin up before accessing my files (mainly vacation photos &amp; videos, pdf).</p> <p>I&#39;m thinking of using Nextcloud to access my folders remotely and to do weekly backups of my phone (I’m already using Synct

## Easiest Router/ OPnSense Alternative for VPN Gateway
 - [https://www.reddit.com/r/selfhosted/comments/1g5rlu9/easiest_router_opnsense_alternative_for_vpn](https://www.reddit.com/r/selfhosted/comments/1g5rlu9/easiest_router_opnsense_alternative_for_vpn)
 - RSS feed: $source
 - date published: 2024-10-17T14:02:31+00:00

<!-- SC_OFF --><div class="md"><p>Hey, so basiclly I&#39;m looking for an easy alternative for OPnSense which supports sending all LAN traffic through a VPN. I whould like to also Setup a failover, so when the connection to the first VPN drops, the second one automatically gets connected, so my Network stays online and anonymous. I tried to setup OPnSense and got IT working fine with one connection, but when I try to setup a failover everything stops working. And I cant seem to find any good Guides for stuff Like this. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PaulTankerfahrer"> /u/PaulTankerfahrer </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5rlu9/easiest_router_opnsense_alternative_for_vpn/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5rlu9/easiest_router_opnsense_alternative_for_vpn/">[comments]</a></span>

## Tunnel a NAS behind CGNAT
 - [https://www.reddit.com/r/selfhosted/comments/1g5rk4x/tunnel_a_nas_behind_cgnat](https://www.reddit.com/r/selfhosted/comments/1g5rk4x/tunnel_a_nas_behind_cgnat)
 - RSS feed: $source
 - date published: 2024-10-17T14:00:33+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to setup rathole tunnel via a VPS to circumvent my Internet&#39;s CG-NAT, and achieve port forwarding. My setup is as follows:</p> <p>VPS server: <code> services: rathole-server: restart: unless-stopped container_name: rathole-server image: archef2000/rathole environment: - &quot;ADDRESS=0.0.0.0:2333&quot; - &quot;DEFAULT_TOKEN=xxxxxxxxxxxxxxxx&quot; - &quot;SERVICE_NAME_1=nas_bt&quot; - &quot;SERVICE_ADDRESS_1=0.0.0.0:5000&quot; ports: - 2333:2333 - 5000:5000 </code></p> <p>NAS (behind NAT): ``` qbittorrent: image: lscr.io/linuxserver/qbittorrent:latest container_name: qbittorrent environment: - PUID=1000 - PGID=1000 - TZ=Australia/Sydney - WEBUI_PORT=8080 volumes: - /mnt/main/config/qbtorrent:/config - /mnt/main/media/torrents:/data/torrents:rw network_mode: &quot;service:rathole-client&quot; #ports: #- 8080:8080 # &lt;== ports cannot be defined, when I issue the above network mode! #- 5000:5000 #- 5000:5000/udp labels: - &quot;com.ce

## docker-php-startage 0.8.1: Better looking, dark mode, search support
 - [https://www.reddit.com/r/selfhosted/comments/1g5rgn5/dockerphpstartage_081_better_looking_dark_mode](https://www.reddit.com/r/selfhosted/comments/1g5rgn5/dockerphpstartage_081_better_looking_dark_mode)
 - RSS feed: $source
 - date published: 2024-10-17T13:56:04+00:00

<!-- SC_OFF --><div class="md"><h2>Intro</h2> <p><a href="https://www.reddit.com/r/selfhosted/comments/txs7qs/phpbased_startpage_i_created_to_monitor_my/">Two years ago</a>, I released the first iteration of my PHP-based selfhosted dashboard (still needs a better name 😅).</p> <p>Yesterday, I released an update that makes it a little easier on the eyes, as well as adding dark mode and search support. <a href="https://github.com/loganmarchione/docker-php-startpage/blob/master/FEATURES.md">Features include</a>:</p> <ul> <li>Dead-simple (no widgets, plugins, API, database, AI, etc...)</li> <li>JSON-based configuration file (mount it into the container)</li> <li>Custom user-includes for header links, footer, and CSS (mount it into the container)</li> <li>Dark mode</li> <li>Search support</li> <li>HTTP status checks</li> <li>Mobile-friendly via Bootstrap (included, no CDN dependency)</li> <li>Four different icon packs (included, no CDN dependency)</li> </ul> <h2>Screenshots</h2> <ul> <li><a

## I'm looking for an AI powered playlist generator for local music.
 - [https://www.reddit.com/r/selfhosted/comments/1g5r2bi/im_looking_for_an_ai_powered_playlist_generator](https://www.reddit.com/r/selfhosted/comments/1g5r2bi/im_looking_for_an_ai_powered_playlist_generator)
 - RSS feed: $source
 - date published: 2024-10-17T13:37:24+00:00

<!-- SC_OFF --><div class="md"><p>I like the idea of <a href="https://www.techhive.com/article/1921927/how-to-use-plex-ai-music-playlists.html">Sonic Sage</a> but it doesn&#39;t provide great results if you don&#39;t have a Tidal account. I want to find something to generate playlists locally using AI, preferably Ollama, does anyone know of something like that existing? I scoured <a href="https://github.com/awesome-selfhosted/awesome-selfhosted">Awesome-Selfhosted</a>, but came up empty.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/booradleysghost"> /u/booradleysghost </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5r2bi/im_looking_for_an_ai_powered_playlist_generator/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5r2bi/im_looking_for_an_ai_powered_playlist_generator/">[comments]</a></span>

## Inventory System
 - [https://www.reddit.com/r/selfhosted/comments/1g5q1y2/inventory_system](https://www.reddit.com/r/selfhosted/comments/1g5q1y2/inventory_system)
 - RSS feed: $source
 - date published: 2024-10-17T12:47:32+00:00

<!-- SC_OFF --><div class="md"><p>Hi! Since my little server is currently only used for ad blocking i figured there might be something it could help me with:</p> <p>I stash the packaging of everything i buy in the basement, be it for easier transport when moving or just warranty claims. Many of the smaller packages are in bigger boxes.</p> <p>Is there an app i could use as a inventory system? I was thinking about QR-Codes, generating those is not too hard. So i can add entries to a QR code and maybe even search both ways (with the QR-Code or with names)</p> <p>Does anybody have a tip for an app which can do this or something similar?</p> <p>I have junior sys-admin knowledge but i&#39;m too stupid to program lol </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Habitat97"> /u/Habitat97 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5q1y2/inventory_system/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/sel

## wireguard, STUN, creating complete mesh?
 - [https://www.reddit.com/r/selfhosted/comments/1g5pqo4/wireguard_stun_creating_complete_mesh](https://www.reddit.com/r/selfhosted/comments/1g5pqo4/wireguard_stun_creating_complete_mesh)
 - RSS feed: $source
 - date published: 2024-10-17T12:30:38+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to create complete point to point mesh with Wireguard.</p> <p>Currently I have wireguard set up and running with one peer being a VPS with public IP address and other 2 peers being behind (multiple) NATs. I have full connectivity, but everything goes through the VPS (which is on a different continent, so the communication is quite slow). Is my thinking correct that if I add the peers with endpoints observed on the VPS to the peers behind the NAT, they should eventually traverse the NAT if it&#39;s kind of NAT where it&#39;s possible? Because now I can&#39;t establish the communication and I&#39;m not sure If I&#39;m doing something wrong or it&#39;s just not possible</p> <p>P.S.: I know about tailscale, but I don&#39;t want to be dependent on a 3rd party service</p> <pre><code>VPS# wg interface: wg0 public key: aaaaaaaaaaaaaaaaaaaa= private key: (hidden) listening port: 51820 peer: bbbbbbbbbbbbbbbbbbb= endpoint: 12.34.56.78:61835 allowed i

## Anyone use a TV to organize themselves?
 - [https://www.reddit.com/r/selfhosted/comments/1g5one7/anyone_use_a_tv_to_organize_themselves](https://www.reddit.com/r/selfhosted/comments/1g5one7/anyone_use_a_tv_to_organize_themselves)
 - RSS feed: $source
 - date published: 2024-10-17T11:27:14+00:00

<!-- SC_OFF --><div class="md"><p>I got an extra 58&quot; TV and the most useful thing I could do with it is organizing my day and week. I&#39;m curious what solutions others have implemented to similar effect and how they did it. This would probably be an always on solution and I wouldn&#39;t want to connect a PC or laptop to it because of additional electrical costs. I only have the original pi that I could repurpose but that&#39;s a last resort unless it yields a really good result. Overall, I really would like to hear if anyone has used a TV to help organize themselves. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Khisanthax"> /u/Khisanthax </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5one7/anyone_use_a_tv_to_organize_themselves/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5one7/anyone_use_a_tv_to_organize_themselves/">[comments]</a></span>

## Dumbest way of streaming media and file storage
 - [https://www.reddit.com/r/selfhosted/comments/1g5oa9h/dumbest_way_of_streaming_media_and_file_storage](https://www.reddit.com/r/selfhosted/comments/1g5oa9h/dumbest_way_of_streaming_media_and_file_storage)
 - RSS feed: $source
 - date published: 2024-10-17T11:04:03+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, I need some help choosing what to get for my </p> <p>So, I have a not-so-old PC which I&#39;m not going to use that I want to convert to a home server. Things I want it to do are:</p> <ol> <li><p>let me download things from my parents&#39; house and then watch that media elsewhere (both alone in my travels and watch some shows together with my family (like streaming to Twitch and watching that Twitch channel))</p></li> <li><p>store things like I&#39;d store them in a Windows Explorer (no focus on AI, letting me create my own folders and structure unlike Google Drive which creates things by itself)</p></li> </ol> <p>I am pretty dumb when it comes to reading long texts as I dont have an attention span for it so I&#39;d like something really simple and if there&#39;s a need, I wouldn&#39;t mind paying for convenience.</p> <p>(Also, what are basic requirements for PC, like is an iGPU enough or should I add one, will 16gb ram do it and so o

## App to Download Videos of Websites
 - [https://www.reddit.com/r/selfhosted/comments/1g5o8x6/app_to_download_videos_of_websites](https://www.reddit.com/r/selfhosted/comments/1g5o8x6/app_to_download_videos_of_websites)
 - RSS feed: $source
 - date published: 2024-10-17T11:01:41+00:00

<!-- SC_OFF --><div class="md"><p>Hey,</p> <p>as the title says im looking for an app that i can self host to download Websites and their content, for example videos on that website ive been using archivebox on my raspberry 5 but sometimes it doesnt download the Videos and its an empty directoy in the browser. </p> <p>thanks in advance</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Lynxaa1337"> /u/Lynxaa1337 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5o8x6/app_to_download_videos_of_websites/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5o8x6/app_to_download_videos_of_websites/">[comments]</a></span>

## KASM Stand Alone with NPM and Authentik
 - [https://www.reddit.com/r/selfhosted/comments/1g5mzdd/kasm_stand_alone_with_npm_and_authentik](https://www.reddit.com/r/selfhosted/comments/1g5mzdd/kasm_stand_alone_with_npm_and_authentik)
 - RSS feed: $source
 - date published: 2024-10-17T09:34:28+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g5mzdd/kasm_stand_alone_with_npm_and_authentik/"> <img src="https://external-preview.redd.it/4tPoseYvVk_DiQRH-clfRFLejS_sZmV2Y_bF77RQbRg.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=52c2c314997566a69490207ad235f61b8e4aad9e" alt="KASM Stand Alone with NPM and Authentik" title="KASM Stand Alone with NPM and Authentik" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>KASM has the Docker Images of the GUI services they use with their &quot;Work Space&quot;. I am interested only in one of them: <a href="https://hub.docker.com/r/kasmweb/desktop">Desktop </a>but i suppose they all function more ore less the same. I made this Docker Compose to try and spin it up:</p> <pre><code>services: kasmweb: image: kasmweb/desktop:1.15.0-rolling-weekly container_name: kasmweb ports: - 6901:6901 stdin_open: true tty: true shm_size: &#39;2gb&#39; volumes: - /etc/localtime:/etc/localtime:ro - /etc/timezone:/etc/timezone:ro device

## Cloudflare Zerotrust
 - [https://www.reddit.com/r/selfhosted/comments/1g5malh/cloudflare_zerotrust](https://www.reddit.com/r/selfhosted/comments/1g5malh/cloudflare_zerotrust)
 - RSS feed: $source
 - date published: 2024-10-17T08:41:50+00:00

<!-- SC_OFF --><div class="md"><p>Just FYI for those who don&#39;t know, Cloudflare ZeroTrust is free to use.</p> <p>Use Nginx Proxy Manager and set cloudflare IPs as only IPs which can access services <a href="https://www.cloudflare.com/en-au/ips/">https://www.cloudflare.com/en-au/ips/</a></p> <p>Then only expose port 443.</p> <p>ZeroTrust allows for, well, as the name implies, zero trust access to applications. This can be via emailed OTP, IP ranges, IP geo location, etc. I configure mine to my IP geo location + email OTP.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dylsmurfz"> /u/Dylsmurfz </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5malh/cloudflare_zerotrust/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5malh/cloudflare_zerotrust/">[comments]</a></span>

## Are you selfhosting any CRM? How is it going so far?
 - [https://www.reddit.com/r/selfhosted/comments/1g5m483/are_you_selfhosting_any_crm_how_is_it_going_so_far](https://www.reddit.com/r/selfhosted/comments/1g5m483/are_you_selfhosting_any_crm_how_is_it_going_so_far)
 - RSS feed: $source
 - date published: 2024-10-17T08:27:35+00:00

<!-- SC_OFF --><div class="md"><p>I am evaluating options. I tried twenty, but unable to self host, and it is in beta. Posted on their discord yesterday, no response so far.<br/> Odoo seems good.<br/> Hearing good things about espoCRM.<br/> I am looking for something which allows me to import data through webhooks, api or something like that..</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/GrSrv"> /u/GrSrv </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5m483/are_you_selfhosting_any_crm_how_is_it_going_so_far/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5m483/are_you_selfhosting_any_crm_how_is_it_going_so_far/">[comments]</a></span>

## Remember to secure your dashboards!
 - [https://www.reddit.com/r/selfhosted/comments/1g5m01v/remember_to_secure_your_dashboards](https://www.reddit.com/r/selfhosted/comments/1g5m01v/remember_to_secure_your_dashboards)
 - RSS feed: $source
 - date published: 2024-10-17T08:18:11+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g5m01v/remember_to_secure_your_dashboards/"> <img src="https://b.thumbs.redditmedia.com/rRtIqFiobxOHyxgMPQXkQ-8vzfy6bVFhJQSpTPXZ5nA.jpg" alt="Remember to secure your dashboards!" title="Remember to secure your dashboards!" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/2wudx0saz9vd1.png?width=2283&amp;format=png&amp;auto=webp&amp;s=0af1b9b4c98d5282b5c153ae6fcab54433d214b7">https://preview.redd.it/2wudx0saz9vd1.png?width=2283&amp;format=png&amp;auto=webp&amp;s=0af1b9b4c98d5282b5c153ae6fcab54433d214b7</a></p> <p>This homepage with no login needed to edit took less than 5 minutes to find with basic tools. Remember to at least have a login page on all your pages! Even if it seems like something no ones ever gonna find it isn&#39;t worth the risk.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ObviouslyNotABurner"> /u/ObviouslyNotABurner </a>

## Voice-Pro: The best gradio web-ui for transcription, translation and text-to-speech
 - [https://www.reddit.com/r/selfhosted/comments/1g5ln7k/voicepro_the_best_gradio_webui_for_transcription](https://www.reddit.com/r/selfhosted/comments/1g5ln7k/voicepro_the_best_gradio_webui_for_transcription)
 - RSS feed: $source
 - date published: 2024-10-17T07:49:56+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g5ln7k/voicepro_the_best_gradio_webui_for_transcription/"> <img src="https://external-preview.redd.it/pKQ0J2LGQcs-3m4nBGn75no_gYyIedRRxD1JE929igY.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=ec84080bbf0751baebec61134de059f44bc37fa5" alt="Voice-Pro: The best gradio web-ui for transcription, translation and text-to-speech" title="Voice-Pro: The best gradio web-ui for transcription, translation and text-to-speech" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><strong>Voice-Pro is the best gradio web-ui for transcription, translation and text-to-speech.</strong> It can be easily installed with one click. Create a virtual environment using Miniconda, running completely separate from the Windows system (fully portable). Supports real-time transcription and translation, as well as batch mode.</p> <ul> <li><strong>YouTube Downloader</strong>: You can download YouTube videos and extract the audio (mp3, wav, flac)

## Docker: VPNs leaking IP
 - [https://www.reddit.com/r/selfhosted/comments/1g5lawu/docker_vpns_leaking_ip](https://www.reddit.com/r/selfhosted/comments/1g5lawu/docker_vpns_leaking_ip)
 - RSS feed: $source
 - date published: 2024-10-17T07:23:00+00:00

<!-- SC_OFF --><div class="md"><p>Hi,<br/> I&#39;m newly setting up a docker container environment and so far have set up all the services I need successfully. But the one thing that apparently doesn&#39;t work as intended is the VPN.</p> <p>I tried both <a href="https://hub.docker.com/r/qmcgaw/gluetun">qmcgaw/gluetun</a> (using wireguard) and <a href="https://github.com/ilteoood/docker-surfshark">lteoood/docker-surfshark</a> (using OVPN) but both seem to leak my actual IP at the beginning of the vpn container starting. This in itself shouldnt happen but isnt that much of a problem. The problem is that it means that it would also leak my IP in case the VPN connection drops for some reason.</p> <p>Below, I attached the docker-compose files and the logs I get from the vpntest container</p> <p>When I look at the logs of vpntest, it shows that it is able to connect using my non vpn-ed connection (censored one with exact location/ starting with 84.) before the VPN connection (non-censored 

## Network issues
 - [https://www.reddit.com/r/selfhosted/comments/1g5l99a/network_issues](https://www.reddit.com/r/selfhosted/comments/1g5l99a/network_issues)
 - RSS feed: $source
 - date published: 2024-10-17T07:19:33+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I have a strange issue, yesterday my power was off for 10 hours, longer than the UPS could cope with, so I powered down everything (router, Nas, raspberrypis etc) I have docker in swarm mode with 1 manager on a pi and 2 workers on the nas and a 2nd pi.</p> <p>The swarm controls the docker network so containers can see each other on the different hosts. </p> <p>When power came back I booted everything up and it seemed OK, but I quickly noticed that when I go to my domain, hosted in a linuxserver swag container from inside my network it times out. Using an external connection works fine.</p> <p>If I enable cloudflare proxy I can then access the sites fine from my LAN, but I don&#39;t want to do this for all the dns entries as some don&#39;t like cloudflare.</p> <p>The IP never changed, external or internal, I just can&#39;t figure out why I can&#39;t access my docker images using a fqdn anymore from the Lan but can from a wan connection.</p> <p>

## VLANs, DMZs, and exposing services. I have questions!
 - [https://www.reddit.com/r/selfhosted/comments/1g5k145/vlans_dmzs_and_exposing_services_i_have_questions](https://www.reddit.com/r/selfhosted/comments/1g5k145/vlans_dmzs_and_exposing_services_i_have_questions)
 - RSS feed: $source
 - date published: 2024-10-17T05:49:45+00:00

<!-- SC_OFF --><div class="md"><p>For a while now I&#39;ve been exposing a couple of services to the internet. The way I&#39;ve gone about this is by creating a DMZ and putting all external services in it. In this DMZ I have an Nginx Proxy Manager instance to handle the traffic. My router has a NAT rule forwarding port 443 traffic to NPM. NPM only has proxy entries for the handful of services I need externally. However, some &quot;companion&quot; services are also in there because I need them to talk to each other. Those don&#39;t have an NPM proxy entry. I don&#39;t know if this is a great way to do it, if you have feedback I&#39;d love to hear it.</p> <p>However, I&#39;ve recently heard that this could potentially be a problem because technically anything in the DMZ is &quot;exposed&quot;, even if a service is in there and has no NPM proxy entry. So the potential attack surface is as big as the number of services in the DMZ. Is this true?</p> <p>One approach I recently became aware 

## Please help me with discord bot using memgpt?
 - [https://www.reddit.com/r/selfhosted/comments/1g5jybw/please_help_me_with_discord_bot_using_memgpt](https://www.reddit.com/r/selfhosted/comments/1g5jybw/please_help_me_with_discord_bot_using_memgpt)
 - RSS feed: $source
 - date published: 2024-10-17T05:45:07+00:00

<!-- SC_OFF --><div class="md"><p>Not from coding background but need to avail the functionality, so trying to do something on my own blindly.</p> <p>I need to use this thing: <a href="https://memgpt.ai/">memgpt</a> for personal use. I learned that inside my laptop I can install it and use through CLI using my openai api key; but i need to access this memgpt from my android too, through a chat interface, without being dependent on my running laptop.</p> <p>Chatgpt told me this: to deploy memgpt on a server like fly.io or heroku, and also write an app in python which connects the memgpt with the bot.</p> <p>Please tell me how should I approach it, I&#39;m not trusting chatgpt on this because i dont understand anything of it, though I&#39;d try to take its help to spew some code and try my luck.</p> <p>Please help. Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/deathmachine111"> /u/deathmachine111 </a> <br/> <span><a href="https://www.redd

## Got into self hosting a week ago and set up jellyfin, immich, and seafile so far. This has been my main feeling
 - [https://www.reddit.com/r/selfhosted/comments/1g5jn31/got_into_self_hosting_a_week_ago_and_set_up](https://www.reddit.com/r/selfhosted/comments/1g5jn31/got_into_self_hosting_a_week_ago_and_set_up)
 - RSS feed: $source
 - date published: 2024-10-17T05:27:21+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1g5jn31/got_into_self_hosting_a_week_ago_and_set_up/"> <img src="https://preview.redd.it/zeo0vsn359vd1.png?width=320&amp;crop=smart&amp;auto=webp&amp;s=8d59bdb75a40e42756fbb5e779b43f024da9ff42" alt="Got into self hosting a week ago and set up jellyfin, immich, and seafile so far. This has been my main feeling" title="Got into self hosting a week ago and set up jellyfin, immich, and seafile so far. This has been my main feeling" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok_Minimum6419"> /u/Ok_Minimum6419 </a> <br/> <span><a href="https://i.redd.it/zeo0vsn359vd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5jn31/got_into_self_hosting_a_week_ago_and_set_up/">[comments]</a></span> </td></tr></table>

## Creating a solid 3-2-1
 - [https://www.reddit.com/r/selfhosted/comments/1g5jcrg/creating_a_solid_321](https://www.reddit.com/r/selfhosted/comments/1g5jcrg/creating_a_solid_321)
 - RSS feed: $source
 - date published: 2024-10-17T05:07:48+00:00

<!-- SC_OFF --><div class="md"><p>How have you done this (please be specific)? </p> <p>Part2: I am starting my voyage down the storage wormhole. I want to create a solid 3-2-1 setup. I’m trying to figure the best way to form it for my purposes (I edit videos and photos).</p> <p>I’m thinking a NAS system for cloud storage and usb hdd’s for backups stored off site. Would raid on the NAS crest that third copy of media? What would you recommend?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dirtbag9"> /u/Dirtbag9 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5jcrg/creating_a_solid_321/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5jcrg/creating_a_solid_321/">[comments]</a></span>

## Setting up SSL for Pi backend to Google Sites embed
 - [https://www.reddit.com/r/selfhosted/comments/1g5hpo0/setting_up_ssl_for_pi_backend_to_google_sites](https://www.reddit.com/r/selfhosted/comments/1g5hpo0/setting_up_ssl_for_pi_backend_to_google_sites)
 - RSS feed: $source
 - date published: 2024-10-17T03:26:45+00:00

<!-- SC_OFF --><div class="md"><p>I am working on an embed for a friend&#39;s Google Site that will accept a list of all the cards in a Magic the Gathering deck, fetch the relevant info about those cards, and use that to analyze the deck. I am currently storing this card information on a Raspberry Pi with a basic server app to provide the details of requested cards. At this point I&#39;ve figured out that I need to have this self-hosted API use https to have CORS requests go through from the site, but I&#39;m not entirely sure about the best way to set that up. </p> <p>The current idea I have is to get a separate domain for the API and use Let&#39;s Encrypt, but I thought I&#39;d run that by some people who knew what they were doing before I dropped money on it. Is there a better way to go about this? </p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rude_avocado"> /u/rude_avocado </a> <br/> <span><a href="https://www.reddit.com/r/s

## GPU recommendation
 - [https://www.reddit.com/r/selfhosted/comments/1g5hafj/gpu_recommendation](https://www.reddit.com/r/selfhosted/comments/1g5hafj/gpu_recommendation)
 - RSS feed: $source
 - date published: 2024-10-17T03:03:07+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’m working on an autonomous driving project using the CARLA simulator and need advice on choosing a GPU. My budget is around 600-800€. I’m considering a used RTX 3090 or a new RTX 4070 Ti, but I’m unsure if I should prioritize VRAM over raw power.</p> <p>Also, my university might provide server access, but I still need a GPU for local work. Should I invest more in a powerful GPU or rely on the servers for heavier tasks?</p> <p>Any advice or recommendations would be greatly appreciated! Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AlbertV999"> /u/AlbertV999 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5hafj/gpu_recommendation/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5hafj/gpu_recommendation/">[comments]</a></span>

## Allow a VLAN to access NAS IP Addr or put the NAS on a separate VLAN?
 - [https://www.reddit.com/r/selfhosted/comments/1g5h9dt/allow_a_vlan_to_access_nas_ip_addr_or_put_the_nas](https://www.reddit.com/r/selfhosted/comments/1g5h9dt/allow_a_vlan_to_access_nas_ip_addr_or_put_the_nas)
 - RSS feed: $source
 - date published: 2024-10-17T03:01:30+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I&#39;m the only one who accesses my home server so I put my pc, phone, NAS and server (which has services like jellyfin, navidrome, actual etc), on VLAN 10.</p> <p>All other family members&#39; devices are on VLAN 20.</p> <p>Smart TVs on VLAN 30, then I make a firewall rule on Mikrotik router allowing VLAN 30 to access jellyfin&#39;s ip address.</p> <p>Yesterday I need to share a big file on the NAS to my sister, so I put her laptop on VLAN 10 temporarily to be able to access the NAS, which was a hassle.</p> <p>So now I&#39;m thinking to share the NAS to VLAN 20. Which would be better:</p> <ul> <li>Make a firewall rule allowing VLAN 20 to access the NAS&#39; ip address, or</li> <li>Put the NAS on its own Vlan (say, VLAN 40), then make a firewall rule allowing VLAN 10 and 20 to access VLAN 40</li> </ul> <p>Or maybe any other ideas?</p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/deecoocoo

## Towards zrok 1.0 (zrok Office Hours)
 - [https://www.reddit.com/r/selfhosted/comments/1g5f8t6/towards_zrok_10_zrok_office_hours](https://www.reddit.com/r/selfhosted/comments/1g5f8t6/towards_zrok_10_zrok_office_hours)
 - RSS feed: $source
 - date published: 2024-10-17T01:13:52+00:00

<!-- SC_OFF --><div class="md"><p>Back with a new zrok Office Hours video...</p> <p>I usually try to give you guys a decent demonstration of the new features under development, but this office hours video has more hands-on work in it than some of the previous installments.</p> <p>Despite that, I think you guys are going to really appreciate some of the new features that are bubbling on the stove for the upcoming 1.0 release. The new zrok &quot;Agent&quot; is coming along nicely... that&#39;s primarily what I&#39;m working on with this video.</p> <p>In the 1.0 releases you&#39;ll be able to create and manage zrok shares without using the CLI. The new zrok Agent UI will give non-CLI users a nice point-and-click interface. Actively doing some work on that interface and demonstrating that new functionality in this latest video...</p> <p><a href="https://www.youtube.com/watch?v=eW2dGaUjwtM">https://www.youtube.com/watch?v=eW2dGaUjwtM</a></p> <p>(zrok is an open-source, self-hostable networ

## netbird mfa
 - [https://www.reddit.com/r/selfhosted/comments/1g5dxha/netbird_mfa](https://www.reddit.com/r/selfhosted/comments/1g5dxha/netbird_mfa)
 - RSS feed: $source
 - date published: 2024-10-17T00:05:57+00:00

<!-- SC_OFF --><div class="md"><p>I skipped the mfa setup during first login and can&#39;t seem to find anywhere to enable this in the dashboard, is this not possible if skipped initially? I would post in their subreddit but mods still haven&#39;t approved my request to post a couple days ago</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dry_Doctor_5658"> /u/Dry_Doctor_5658 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5dxha/netbird_mfa/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1g5dxha/netbird_mfa/">[comments]</a></span>

