# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Fever RSS stopped working. What are my alternatives?
 - [https://www.reddit.com/r/selfhosted/comments/1gm348y/fever_rss_stopped_working_what_are_my_alternatives](https://www.reddit.com/r/selfhosted/comments/1gm348y/fever_rss_stopped_working_what_are_my_alternatives)
 - RSS feed: $source
 - date published: 2024-11-07T22:30:56+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gm348y/fever_rss_stopped_working_what_are_my_alternatives/"> <img src="https://preview.redd.it/ql6u5m373kzd1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=1825ae24721bb05b2527de9ff852720164ad99fd" alt="Fever RSS stopped working. What are my alternatives?" title="Fever RSS stopped working. What are my alternatives?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello all,</p> <p>I bought a license for Fever RSS over a decade ago when Google Reader bit the dust. I installed it on my domain (I pay for shared web hosting) used it frequently.</p> <p>I noticed a few months ago that it stopped working. When I now visit my RSS page, I get the following generic error message: &quot;Uh-oh. Fever encountered the following error(s).&quot; (I hope the screenshot I added is visible.)</p> <p>Is there any way to fix this so I can get it working again?</p> <p>If not, are there any similar RSS tools out there I can upload

## Docker: how to create a limited ip-range for every bridge network created?
 - [https://www.reddit.com/r/selfhosted/comments/1gm2ya0/docker_how_to_create_a_limited_iprange_for_every](https://www.reddit.com/r/selfhosted/comments/1gm2ya0/docker_how_to_create_a_limited_iprange_for_every)
 - RSS feed: $source
 - date published: 2024-11-07T22:23:32+00:00

<!-- SC_OFF --><div class="md"><p>Hi everybody. I self-host all my apps using docker (it&#39;s all set via Ansible, but it doesn&#39;t matter much with this issue). Each service/app has its own dedicated network in order to increase isolation, even for single-container roles/services, with the exception of *arr apps, which share the same. The Swag reverse proxy joins all of those networks. So far, so good.</p> <p>This is a typical Ansible task</p> <pre><code>- name: Create a docker network community.docker.docker_network: name: arr_network connected: - &quot;{{ swag_container_name }}&quot; appends: true </code></pre> <p>What I don&#39;t like is the fact that networks have a huge ip-range if we consider that sometimes are just for a couple of required containers/ips. I know that I can fully specify the network definition, passing the network and the mask. However, I don&#39;t want to hard-code in the task definition a specific network range. I only would like to force the ip-range (to

## Endurain v0.5.0 - Fitness activity tracker that you can self host
 - [https://www.reddit.com/r/selfhosted/comments/1gm2cdv/endurain_v050_fitness_activity_tracker_that_you](https://www.reddit.com/r/selfhosted/comments/1gm2cdv/endurain_v050_fitness_activity_tracker_that_you)
 - RSS feed: $source
 - date published: 2024-11-07T21:57:18+00:00

<!-- SC_OFF --><div class="md"><p>Hello its me again talking about Endurain, a fitness activity tracker that you can self host. A new version is out and here are some highlights:</p> <ul> <li>Added support for .fit files</li> <li>New health zone starting with the capability of logging weight</li> <li>Files used to import activities are now stored in a specific processed folder</li> <li>Toast logic now uses Notivue</li> </ul> <p><a href="https://github.com/jonasoreland/runnerup/pull/1193">RunnerUp</a> now supports Endurain activity import directly from Android devices.<br/> For iOS still no news.</p> <p>For the next version(s) I will focus on more or less in order:</p> <ul> <li>Garmin Connect integration</li> <li>Add some additional Strava functionality</li> <li>BMI in the new health zone</li> <li>Auth sessions storage for better control</li> <li>Simplified Docker images</li> <li>Gear components tracking</li> <li>Live tracking support</li> </ul> <p>I also created a GitHub <a href="htt

## How should I setup my VPS? I want some kind of VPN/tunnelling/reverse proxy
 - [https://www.reddit.com/r/selfhosted/comments/1gm0sfu/how_should_i_setup_my_vps_i_want_some_kind_of](https://www.reddit.com/r/selfhosted/comments/1gm0sfu/how_should_i_setup_my_vps_i_want_some_kind_of)
 - RSS feed: $source
 - date published: 2024-11-07T20:52:03+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone. I want to see what is the popular way nowadays to setup a VPS just for networking.</p> <p>As all of my servers are behind CGNAT, I decided to rent a VPS so I can get a public static IP to use. The VPS only has 1 core and 1gb of ram, but from what I&#39;ve read here it seems to be enough for my purpose, and I&#39;m trying to save as much as possible.</p> <p>There are a few things I want to do on this machine:</p> <ul> <li>Have a VPN so that I can access some blocked service in my office&#39;s wifi network. I&#39;ve talked to IT and they do allows VPN but they block games for some reason, and I don&#39;t want to rely on my Proton VPN free account. I&#39;ll probably use this VPN to access my local service too to replace Zerotier. Bonus point if I can have a DNS server to block ads in my VPN</li> <li>Setup either tunnels or reverse proxy with vpn so that I can share some of my services to other people without the need of VPN. I have my own d

## Alternative to Cloudinary
 - [https://www.reddit.com/r/selfhosted/comments/1glzv4m/alternative_to_cloudinary](https://www.reddit.com/r/selfhosted/comments/1glzv4m/alternative_to_cloudinary)
 - RSS feed: $source
 - date published: 2024-11-07T20:12:34+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I learned to use Cloudinary as an asset manager (1GB, 99% images, 1% videos)with a ruby on rails app. It works well, but I&#39;ve reached the limit of the free plan. I won&#39;t pay $99/month for a side-project app, and I don&#39;t use 99% of its functionality.</p> <p>What is your solution (self-hosted ideally) to deliver assets and potentially resize them by creating variants?</p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/fuckingsurfslave"> /u/fuckingsurfslave </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1glzv4m/alternative_to_cloudinary/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1glzv4m/alternative_to_cloudinary/">[comments]</a></span>

## Why do people remove ports when using reverse proxy? Security concerns?
 - [https://www.reddit.com/r/selfhosted/comments/1glzro4/why_do_people_remove_ports_when_using_reverse](https://www.reddit.com/r/selfhosted/comments/1glzro4/why_do_people_remove_ports_when_using_reverse)
 - RSS feed: $source
 - date published: 2024-11-07T20:08:26+00:00

<!-- SC_OFF --><div class="md"><p>I recently set up a reverse proxy (NPM) with Authentik and I&#39;m trying to learn more about security and configurations. I&#39;m not port forwarding (with the one exception of plex), but I am using a cloudflare tunnel for a couple of other services.</p> <p>I&#39;ve read that some people will entirely remove the ports reference from their compose files and put containers onto a bridge network shared with the reverse proxy.. Then in the reverse proxy you would use the container name and container port (not the host port). This would also make the containers inaccessible from typing http(s)://ipaddress:port.</p> <p>My question is why would you want to do this? My understanding is that the ipaddress:port would only be accessible on my LAN anyway. I often access containers that way when I&#39;m tinkering with NPM and/or have to take NPM down for one reason or another. Is it a security issue to keep containers accessible through the ipaddress:port as a f

## Has anyone purchased IceHrmPro?
 - [https://www.reddit.com/r/selfhosted/comments/1glzmb4/has_anyone_purchased_icehrmpro](https://www.reddit.com/r/selfhosted/comments/1glzmb4/has_anyone_purchased_icehrmpro)
 - RSS feed: $source
 - date published: 2024-11-07T20:02:21+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a self-hosted HR management system that supports vacations, time tracking and recruitment. I recently came accross <a href="http://IceHrm.com">IceHrm.com</a> and tested the SaaS 45 day trial. It looks like a good fit, but I want to self-host. They offer the self-hosted software as well, but the price is a bit high for me.</p> <p>Just wanted to check if anyone have experience with self-hosted IceHrmPro? Can you recommend a cheaper alternative to IceHrmPro?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Upbeat-Computer4557"> /u/Upbeat-Computer4557 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1glzmb4/has_anyone_purchased_icehrmpro/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1glzmb4/has_anyone_purchased_icehrmpro/">[comments]</a></span>

## Looping for PDF text édition
 - [https://www.reddit.com/r/selfhosted/comments/1glyc65/looping_for_pdf_text_édition](https://www.reddit.com/r/selfhosted/comments/1glyc65/looping_for_pdf_text_édition)
 - RSS feed: $source
 - date published: 2024-11-07T19:08:55+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I am looking for a self hosted tools that will allow me to edit text on a PDF file, like it is possible in Adobe Acrobat or uPDF. </p> <p>*looking in the title… damn autocorrect…</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/carmelo42"> /u/carmelo42 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1glyc65/looping_for_pdf_text_édition/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1glyc65/looping_for_pdf_text_édition/">[comments]</a></span>

## What docker host DDNS Web GUI you guys using?
 - [https://www.reddit.com/r/selfhosted/comments/1gly3ky/what_docker_host_ddns_web_gui_you_guys_using](https://www.reddit.com/r/selfhosted/comments/1gly3ky/what_docker_host_ddns_web_gui_you_guys_using)
 - RSS feed: $source
 - date published: 2024-11-07T18:59:08+00:00

<!-- SC_OFF --><div class="md"><p>I know this is a weird case, normally most people in this sub using some kind json-base or shell script to manage there ddns record.</p> <p>Because I like try new selfhost service and if I decide to host it I&#39;ll add a new sub-domain to share service for my friend.</p> <p>I just lazy to edit those json every time, if I can just type an `abc-sub.domain.xxx` in Web-GUI let it just auto add an new cloudflare record and keep DNS fresh every time my home IP change, that will best.</p> <p>Is there any recommend?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ArmFire1911"> /u/ArmFire1911 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gly3ky/what_docker_host_ddns_web_gui_you_guys_using/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gly3ky/what_docker_host_ddns_web_gui_you_guys_using/">[comments]</a></span>

## Wake-on-LAN stops working after complete power loss (and subsequent restore of power)
 - [https://www.reddit.com/r/selfhosted/comments/1glwo7a/wakeonlan_stops_working_after_complete_power_loss](https://www.reddit.com/r/selfhosted/comments/1glwo7a/wakeonlan_stops_working_after_complete_power_loss)
 - RSS feed: $source
 - date published: 2024-11-07T17:59:40+00:00

<!-- SC_OFF --><div class="md"><p>Currently, I can shut down my PC using the shutdown option (or by using shutdown commands) and I can turn it on afterwards using the Wake-On-LAN feature. However, if I lose power completely, the computer does not turn on again unless I physically push the button (obviously, after power is restored). Is this a Wake-On-LAN limitation or is it a misconfiguration on my part?</p> <p>Notes:</p> <ul> <li>I&#39;m already using a UPS but I routinely lose power for hours and I would like a solution that works after complete power loss and not just for intermittent power loss.</li> <li>I already know about KVMs but I want to see if I can make this work with the hardware I have before spending hundreds of dollars.</li> </ul> <p>My theory is that Wake On LAN requires my computer to be in a standby state with enough power supplied to the network card and this is not automatically possible after power returns. I always need to turn on the PC manually one time until

## Official v0.1 Release of SWE-Kit, an open-source toolkit for building AI-powered coding agents.
 - [https://www.reddit.com/r/selfhosted/comments/1glwamx/official_v01_release_of_swekit_an_opensource](https://www.reddit.com/r/selfhosted/comments/1glwamx/official_v01_release_of_swekit_an_opensource)
 - RSS feed: $source
 - date published: 2024-11-07T17:44:05+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I built SWE-Kit, an LLM toolkit, which makes building agents specialised in coding like Devin very easy.</p> <p>I noticed a typical pattern while building local agents: creating and perfecting LLM tools to interact with a system or codebase was repeated and time-consuming. We built a layer that simplifies building agents that can interact with code, file system, git, and shell and allows you to quickly solve various coding agent use cases.</p> <p>Aren’t there open coding agents already? Well, yes, but most folks would want to solve their specific use case like a large refactor, and current coding agents aren’t customisable to your particular use case or aren’t meant to be moulded to different workflows.</p> <p>particular</p> <p>The idea is to provide a library of tools to build software engineering agents with a few lines of code in the agentic framework of your choice.</p> <p>We have solved the following complex parts for everyo

## Wake on lan/shutdown based on swarm load?
 - [https://www.reddit.com/r/selfhosted/comments/1glw4jy/wake_on_lanshutdown_based_on_swarm_load](https://www.reddit.com/r/selfhosted/comments/1glw4jy/wake_on_lanshutdown_based_on_swarm_load)
 - RSS feed: $source
 - date published: 2024-11-07T17:37:05+00:00

<!-- SC_OFF --><div class="md"><p>Hi, is there some tool to dynamically start/stop hosts in my swarm depending on the load in the pool? Would be cool to save some energy. Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/m1212e"> /u/m1212e </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1glw4jy/wake_on_lanshutdown_based_on_swarm_load/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1glw4jy/wake_on_lanshutdown_based_on_swarm_load/">[comments]</a></span>

## [Help] MediaStack all set up, but I get an infinite redirect when i try to visit my hosted website.
 - [https://www.reddit.com/r/selfhosted/comments/1glvga2/help_mediastack_all_set_up_but_i_get_an_infinite](https://www.reddit.com/r/selfhosted/comments/1glvga2/help_mediastack_all_set_up_but_i_get_an_infinite)
 - RSS feed: $source
 - date published: 2024-11-07T17:09:01+00:00

<!-- SC_OFF --><div class="md"><p>I followed the <a href="https://mediastack.guide/">MediaStack guide</a> to get MediaStack set up on my Synology NAS, but i can&#39;t access my services. I have a domain purchased from CloudFlare all set up, but when i visit the URL, i get an infinite redirect back to itself. So the device is reachable through the internet, but it just never lands on the page.</p> <p>Is there some part i missed? I was following the pages on <a href="https://mediastack.guide/remote/dns/">remote access</a> but they kinda fall apart near the end because the guide is still in development, i think.</p> <p>I&#39;m using the configuration for all of the services to use Gluetun for VPN, if that&#39;s important information.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/fappaf"> /u/fappaf </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1glvga2/help_mediastack_all_set_up_but_i_get_an_infinite/">[link]</a></span> &#3

## What is a smarter way to get secure remote VPN access to home network
 - [https://www.reddit.com/r/selfhosted/comments/1gluztv/what_is_a_smarter_way_to_get_secure_remote_vpn](https://www.reddit.com/r/selfhosted/comments/1gluztv/what_is_a_smarter_way_to_get_secure_remote_vpn)
 - RSS feed: $source
 - date published: 2024-11-07T16:50:04+00:00

<!-- SC_OFF --><div class="md"><p>I am starting to doubt the approach I am using to get secure access to my home network. I feel that there is probably a smarter way to do things... At the moment I use a hub and spoke wireguard topology (with a VPS as the hub). My home network connects to the VPS and maintains an open wireguard tunnel. My personal devices (when away from home) establish their own tunnel to the hub and with AllowedIPs and a custom DNS server I get seamless access to my home network. The concern I have is that the VPS has quite a few public facing services running on it and if it was ever hacked the attacker would have direct access to my home network. Also, not all of my internal services use TLS so if an attacker breached the hub they could always sit and watch as the traffic decrypts from tunnel to tunnel. I thought about nested tunnelling (<a href="https://www.procustodibus.com/blog/2021/12/wireguard-e2ee-hub-and-spoke/">https://www.procustodibus.com/blog/2021/12/w

## Need Help Getting Plex Hardware Transcoding with Intel Quick Sync to Work in Kubernetes
 - [https://www.reddit.com/r/selfhosted/comments/1glu40a/need_help_getting_plex_hardware_transcoding_with](https://www.reddit.com/r/selfhosted/comments/1glu40a/need_help_getting_plex_hardware_transcoding_with)
 - RSS feed: $source
 - date published: 2024-11-07T16:13:03+00:00

<!-- SC_OFF --><div class="md"><p>Hi <a href="/r/selfhosted">r/selfhosted</a> </p> <p>I&#39;m unable to get Plex hardware transcoding working with intel quick sync inside my k3s kubernetes cluster. (Signs of issue: CPU is loaded, intel_gpu_top doesn&#39;t show activity when playing video, hw suffix missing in Plex dashboard at the video) </p> <p>My IGPU of my CPU is the only GPU in my machien I don&#39;t have external nvidia or amd gpu. </p> <p>I am running k3s in docker-compose with the following configuration: </p> <p><code>version: &#39;3&#39;</code><br/> <code>services:</code><br/> <code>k3s:</code><br/> <code>image: rancher/k3s:v1.31.0-k3s1</code><br/> <code>restart: always</code><br/> <code>hostname: homelab</code><br/> <code>container_name: k3s</code><br/> <code>network_mode: host</code><br/> <code>command: server --advertise-address</code> <a href="http://192.168.1.3"><code>192.168.1.3</code></a> <code>--disable=traefik</code><br/> <code>tmpfs:</code><br/> <code>- /run</code>

## Barematel Ubuntu Server vs Promox for a development server
 - [https://www.reddit.com/r/selfhosted/comments/1gltwiq/barematel_ubuntu_server_vs_promox_for_a](https://www.reddit.com/r/selfhosted/comments/1gltwiq/barematel_ubuntu_server_vs_promox_for_a)
 - RSS feed: $source
 - date published: 2024-11-07T16:04:10+00:00

<!-- SC_OFF --><div class="md"><p>Hello!</p> <p>I am a developer with some basic knowledge of networking and the Linux ecosystem. I’m working on a few projects and want to set up a home server on my old laptop (16GB RAM, 4-core processor). Here are the options I’m considering:</p> <ol> <li><strong>Install Ubuntu Server, then Docker</strong>: With this approach, I can run all the applications within Docker containers. However, this would mean my development projects and home server applications would be on the same server. This might be a simpler setup.</li> <li><strong>Install Proxmox and create multiple VMs</strong>: This option would allow me to create separate VMs for different purposes, which would offer benefits like backups and isolated environments. However, I’m unsure how complex it would be to set this up.</li> </ol> <p>My plan is to open this server to the public so my friends can use some of the applications. I’m okay with setting up Proxmox and doing it properly, but how 

## David Heinemeier-Hansson of hey.com: Self-hosting saves us millions (it's still in rented datacenter space, but their own metal)
 - [https://www.reddit.com/r/selfhosted/comments/1glt0ic/david_heinemeierhansson_of_heycom_selfhosting](https://www.reddit.com/r/selfhosted/comments/1glt0ic/david_heinemeierhansson_of_heycom_selfhosting)
 - RSS feed: $source
 - date published: 2024-11-07T15:26:58+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1glt0ic/david_heinemeierhansson_of_heycom_selfhosting/"> <img src="https://external-preview.redd.it/vNjExzUhT4--o3Y2GJ4DH4lqDoP4vQxJv5EIsMyOO2g.jpg?width=216&amp;crop=smart&amp;auto=webp&amp;s=88d00c06625edb80a79f9e9b3b2fa2815ca97ad2" alt="David Heinemeier-Hansson of hey.com: Self-hosting saves us millions (it's still in rented datacenter space, but their own metal)" title="David Heinemeier-Hansson of hey.com: Self-hosting saves us millions (it's still in rented datacenter space, but their own metal)" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CrimsonNorseman"> /u/CrimsonNorseman </a> <br/> <span><a href="https://world.hey.com/dhh/our-cloud-exit-savings-will-now-top-ten-million-over-five-years-c7d9b5bd">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1glt0ic/david_heinemeierhansson_of_heycom_selfhosting/">[comments]</a></span> </td></tr></tab

## Anyone using Keycloak? How is it?
 - [https://www.reddit.com/r/selfhosted/comments/1gls7wf/anyone_using_keycloak_how_is_it](https://www.reddit.com/r/selfhosted/comments/1gls7wf/anyone_using_keycloak_how_is_it)
 - RSS feed: $source
 - date published: 2024-11-07T14:52:01+00:00

<!-- SC_OFF --><div class="md"><p>Long story short, I&#39;m looking for an IAM solution to manage my lab&#39;s login. So, I want to know if any of you&#39;re using Keycloak and how do you feel with it.</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PrinnRinz"> /u/PrinnRinz </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gls7wf/anyone_using_keycloak_how_is_it/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gls7wf/anyone_using_keycloak_how_is_it/">[comments]</a></span>

## Weight and Body Fat Dashboard
 - [https://www.reddit.com/r/selfhosted/comments/1glre40/weight_and_body_fat_dashboard](https://www.reddit.com/r/selfhosted/comments/1glre40/weight_and_body_fat_dashboard)
 - RSS feed: $source
 - date published: 2024-11-07T14:14:45+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, We have a Fitbit Aria2 in our house. We love the scale but hate the app. Is there any way to visualize weight and body fat in a useful way using a self hosted solution? Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/relativisticcobalt"> /u/relativisticcobalt </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1glre40/weight_and_body_fat_dashboard/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1glre40/weight_and_body_fat_dashboard/">[comments]</a></span>

## Which VPS for a self-hosted Coolify instance?
 - [https://www.reddit.com/r/selfhosted/comments/1glqumz/which_vps_for_a_selfhosted_coolify_instance](https://www.reddit.com/r/selfhosted/comments/1glqumz/which_vps_for_a_selfhosted_coolify_instance)
 - RSS feed: $source
 - date published: 2024-11-07T13:49:14+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I am an indie dev looking to deploy my next SaaS, built with NextJS, to an affordable VPS, with horizontal scaling capabilities (e.g. load balancing between servers) for future expansion. Also, I&#39;ve heard good things about the Coolify deployment dashboard, so will probably be going with this.</p> <p>My user-base is generally all from the UK and therefore I am seeing if anyone has had any good experiences with VPS&#39;s from UK providers, or with UK data-centre locations. Alternatively, any VPS&#39;s located close to the UK with good latency would also work.</p> <p>Thanks 👍</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/wol_dev"> /u/wol_dev </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1glqumz/which_vps_for_a_selfhosted_coolify_instance/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1glqumz/which_vps_for_a_selfhosted_coolify_

## Will the Acemagic S1 meet my needs?
 - [https://www.reddit.com/r/selfhosted/comments/1glq8o7/will_the_acemagic_s1_meet_my_needs](https://www.reddit.com/r/selfhosted/comments/1glq8o7/will_the_acemagic_s1_meet_my_needs)
 - RSS feed: $source
 - date published: 2024-11-07T13:19:27+00:00

<!-- SC_OFF --><div class="md"><p>I plan to run Plex and a Terraria server on it.</p> <p>CPU: N97 (up to 3.6 GHz)</p> <p>Storage: 512GB M.2 SSD</p> <p>RAM: 16GB DDR4</p> <p>Networking: WiFi6 &amp; BT5.2 &amp; Dual Gigabit LAN</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Cold_Aaron45"> /u/Cold_Aaron45 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1glq8o7/will_the_acemagic_s1_meet_my_needs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1glq8o7/will_the_acemagic_s1_meet_my_needs/">[comments]</a></span>

## Any selfhostable f1 games telemetry server?
 - [https://www.reddit.com/r/selfhosted/comments/1glptcn/any_selfhostable_f1_games_telemetry_server](https://www.reddit.com/r/selfhosted/comments/1glptcn/any_selfhostable_f1_games_telemetry_server)
 - RSS feed: $source
 - date published: 2024-11-07T12:57:55+00:00

<!-- SC_OFF --><div class="md"><p>Hello there!</p> <p>As the title says. I have a bunch of selfhosted services and now I started to play racing games. I discovered the udp metrics feature and it would really nice if I could selfhost a service that collects that data and present it in a webswebsite or something like that.</p> <p>Do you know any open soursource selhostabke solution for this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hazukun"> /u/hazukun </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1glptcn/any_selfhostable_f1_games_telemetry_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1glptcn/any_selfhostable_f1_games_telemetry_server/">[comments]</a></span>

## No luck with Apache Guacamole Docker when Public Host Key (Base64) is specified
 - [https://www.reddit.com/r/selfhosted/comments/1glp4ik/no_luck_with_apache_guacamole_docker_when_public](https://www.reddit.com/r/selfhosted/comments/1glp4ik/no_luck_with_apache_guacamole_docker_when_public)
 - RSS feed: $source
 - date published: 2024-11-07T12:19:54+00:00

<!-- SC_OFF --><div class="md"><p>Recently I as trying to setup a Guacamole server so I can access my resources via SSH. I used Docker Compose provided by this repo <a href="https://github.com/boschkundendienst/guacamole-docker-compose">https://github.com/boschkundendienst/guacamole-docker-compose</a></p> <p>My services are hosted on VPSs at the moment and to fully secure my self in that situation I want to use host verification.</p> <p>I&#39;ve generated a separate key and copied a pubkey to the destination machine. The SSH connection from the host itself works fine. The connection through Guacamole without specifying Public Host Key (Base64) works fine. But when I copy a b64 string of my pubkey to this field and try to connect, I see the following error:</p> <pre><code>guacd\_compose | guacd\[52\]: INFO: Auth key successfully imported. guacd\_compose | guacd\[52\]: ERROR: Host key not found for x.x.x.x guacd\_compose | guacd\[52\]: ERROR: Host key did not match any provided known h

## Backup/Restore Options
 - [https://www.reddit.com/r/selfhosted/comments/1glou8e/backuprestore_options](https://www.reddit.com/r/selfhosted/comments/1glou8e/backuprestore_options)
 - RSS feed: $source
 - date published: 2024-11-07T12:03:43+00:00

<!-- SC_OFF --><div class="md"><p>With a lot of help from this community I have built out a very useful self hosted environment. I’m running two computers: 1.) an older Intel NUC with a lot of USB storage attached that functions as a media and *arr server 2.) a raspberry pi that functions as a pi-hole and Nginx reverse proxy</p> <p>As I’ve come to rely heavily on this setup, I’m looking on suggestions for backup, to be specific though I’m looking for backup options that would lead to the easiest possible restoration path. I’m very comfortable in *nix and rsync for many different types of data backups but I think what I reallly need here is something like dd or clonezilla, neither of which I’m familiar with. Basically if, either of these boxes go down, I’d like to just swap in another drive/ssd with a recent backup and power back up and get back up and running. </p> <p>Any good/easy models for this? Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.c

## defguard 1.0 with real-time WireGuard clients configuration sync is here!
 - [https://www.reddit.com/r/selfhosted/comments/1glol69/defguard_10_with_realtime_wireguard_clients](https://www.reddit.com/r/selfhosted/comments/1glol69/defguard_10_with_realtime_wireguard_clients)
 - RSS feed: $source
 - date published: 2024-11-07T11:48:29+00:00

<!-- SC_OFF --><div class="md"><p>Hi Selfhosted!</p> <p>I&#39;m very excited to share that our Open Source versatile access management solution with <a href="https://docs.defguard.net/admin-and-features/wireguard/multi-factor-authentication-mfa-2fa/architecture">real WireGuard 2FA/MFA</a> - <a href="https://defguard.net">defguard</a> (<a href="https://github.com/defguard/defguard">https://github.com/defguard/defguard</a>) has reached a major milestone 1.0 🎉with exciting features that may interest you:</p> <p>💥 <a href="https://docs.defguard.net/enterprise/automatic-real-time-desktop-client-configuration">Real time &amp; automatic sync for client configurations!</a> First WireGuard client to support this feature!</p> <p>🔐 <a href="https://docs.defguard.net/enterprise/external-openid-providers">External OIDC</a> (Google/Microsoft/Custom) to login or create a defguard account.</p> <p>❤️ New <a href="https://github.com/DefGuard/deployment/tree/main/charts">Kubernetes HELM charts</a> (tha

## Stock trading journal like tradingvue?
 - [https://www.reddit.com/r/selfhosted/comments/1gln041/stock_trading_journal_like_tradingvue](https://www.reddit.com/r/selfhosted/comments/1gln041/stock_trading_journal_like_tradingvue)
 - RSS feed: $source
 - date published: 2024-11-07T09:57:49+00:00

<!-- SC_OFF --><div class="md"><p>Anyone know of a self hosted solution similar to something like tradingvue (not tradingview) that allows you to import trades and get details on performance per day?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MidnightProgrammer"> /u/MidnightProgrammer </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gln041/stock_trading_journal_like_tradingvue/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gln041/stock_trading_journal_like_tradingvue/">[comments]</a></span>

## Should we expect good VPS sales offers for Black Friday 2024 ?
 - [https://www.reddit.com/r/selfhosted/comments/1glmw6j/should_we_expect_good_vps_sales_offers_for_black](https://www.reddit.com/r/selfhosted/comments/1glmw6j/should_we_expect_good_vps_sales_offers_for_black)
 - RSS feed: $source
 - date published: 2024-11-07T09:49:12+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I am new to VPS &quot;business&quot; but I am wondering whether we should expect good VPS sales offers/discounts for Black Friday 2024 (hence, waiting so far) ; or no, if usually there is nothing interesting on the VPS field during BF !</p> <p>Thank you everyone !</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/johndoudou"> /u/johndoudou </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1glmw6j/should_we_expect_good_vps_sales_offers_for_black/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1glmw6j/should_we_expect_good_vps_sales_offers_for_black/">[comments]</a></span>

## I could use some advice in how to start selfhosting...
 - [https://www.reddit.com/r/selfhosted/comments/1glmocs/i_could_use_some_advice_in_how_to_start](https://www.reddit.com/r/selfhosted/comments/1glmocs/i_could_use_some_advice_in_how_to_start)
 - RSS feed: $source
 - date published: 2024-11-07T09:32:15+00:00

<!-- SC_OFF --><div class="md"><p>Hi there! </p> <p>To give you some context.<br/> I am currently working on some static websites for some friends of mine. As I am planning on becoming a web developer.<br/> And its been going great! I have developed some pretty nice looking (I think). Static websites that have been received quite well!</p> <p>But problem is.. Some clients or ideas require the use of a backend. I get that. I have been practicing my Node skills and have succesfully managed to create some working and &quot;real life&quot; applicable apps.</p> <p>This I&#39;ve managed with the use of Youtube tutorials and lots of googling. Problem is.. Most youtube tutorials or guidance that is aimed towards beginners. Uses cloud-based solutions such as Netlify, MongoDB, Supabase, Firebase and so on.</p> <p>These tools are great and I am really glad they exist. But sadly they are not feasible or at least not sustainable for my current position.</p> <p>I live in a country where online pur

## What are you using Paperless NGX and PDF Stirling for?
 - [https://www.reddit.com/r/selfhosted/comments/1glmg1k/what_are_you_using_paperless_ngx_and_pdf_stirling](https://www.reddit.com/r/selfhosted/comments/1glmg1k/what_are_you_using_paperless_ngx_and_pdf_stirling)
 - RSS feed: $source
 - date published: 2024-11-07T09:14:11+00:00

<!-- SC_OFF --><div class="md"><p>I understand the use case of Paperless when you need to scan a lot of invoices, but who has that many invoices and actually wants to make the effort to scan everything? I just pile them up and put them in a folder once every few months. Same with post from authorities or similar. What is your use case that would convince me to use it? </p> <p>Same with PDF Stirling, what are you using it for that justifies the constant usage of cpu and ram just for rotating, cropping PDF files and other trivial actions? I just use PDF24 for the random occasion where I really need it. Runs locally and on demand when I need it. Why do you guys need it? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Kahz3l"> /u/Kahz3l </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1glmg1k/what_are_you_using_paperless_ngx_and_pdf_stirling/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/

## Oracle Forge Server says No
 - [https://www.reddit.com/r/selfhosted/comments/1glmes2/oracle_forge_server_says_no](https://www.reddit.com/r/selfhosted/comments/1glmes2/oracle_forge_server_says_no)
 - RSS feed: $source
 - date published: 2024-11-07T09:11:28+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1glmes2/oracle_forge_server_says_no/"> <img src="https://external-preview.redd.it/b34nqSzsLIL7III7mASXfOrgAxMnTzrf8LgXnd8cCvY.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=e95dcaa84a87ab56c8e87478db3d71724a3b26ea" alt="Oracle Forge Server says No" title="Oracle Forge Server says No" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>So I followed this guide on how to set up a forge server on an Oracle thing. <a href="https://www.youtube.com/watch?v=RyC-m725uTs&amp;t=794s">How to setup free 24/7 forge modded minecraft server on oracle cloud</a></p> <p>And it worked pretty well I got everything in like this:</p> <p><a href="https://preview.redd.it/glcyrbov3gzd1.png?width=467&amp;format=png&amp;auto=webp&amp;s=946060a51f9c970627b528f309a7869a0794ed82">https://preview.redd.it/glcyrbov3gzd1.png?width=467&amp;format=png&amp;auto=webp&amp;s=946060a51f9c970627b528f309a7869a0794ed82</a></p> <p>I&#39;m using putty to ac

## Homepage Dashboard: Control API & Scheduler?
 - [https://www.reddit.com/r/selfhosted/comments/1gllybm/homepage_dashboard_control_api_scheduler](https://www.reddit.com/r/selfhosted/comments/1gllybm/homepage_dashboard_control_api_scheduler)
 - RSS feed: $source
 - date published: 2024-11-07T08:35:27+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m narrowing down my search for a home/family dashboard (for mostly basic stuff like weather, calendar, transit departures, photos), and am leaning towards using <a href="https://gethomepage.dev/">Homepage</a>, as I feel it&#39;s one of the most flexible options out there, and is extensible in case I want to create my own widgets. I am aware that it&#39;s more targeted at a tech dashboards, but clearly that&#39;s not it&#39;s only use case. </p> <p>However, one feature it does not appear to have is a way to: (a) remotely trigger visibility of things (e.g., triggering the active/visible dashboard, showing a specific dashboard tab, opening/closing specific widgets), or (b) scheduling these types of actions...for example, at 7:00am every morning, switch to the &quot;morning&quot; dashboard, and at 7:00pm, switch to the &quot;get kids ready for bed&quot; dashboard. Similarly, I might want to trigger a switch to a given dashboard based on external ev

## Self-hosted exchange server for calendar, to-do, organization ONLY - no email
 - [https://www.reddit.com/r/selfhosted/comments/1glln7v/selfhosted_exchange_server_for_calendar_todo](https://www.reddit.com/r/selfhosted/comments/1glln7v/selfhosted_exchange_server_for_calendar_todo)
 - RSS feed: $source
 - date published: 2024-11-07T08:11:28+00:00

<!-- SC_OFF --><div class="md"><p>As the title states</p> <p>I really enjoy self-hosting my whole life, all of my data, pictures, passwords, media, you name it.</p> <p>I also have some retro devices that I want to start using as my daily drivers. I would love to boot into Windows XP and use Outlook to manage my schedule and to-do list. Then sync that with my Palm Pilot and Windows CE devices to carry throughout the day.</p> <p>I&#39;m not interested in self-hosting email just because I know how painful it is.</p> <p>So I am wondering if anyone has self-hosted an Exchange server - either a Microsoft server or a FOSS clone - for use with old versions of Outlook.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/randylush"> /u/randylush </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1glln7v/selfhosted_exchange_server_for_calendar_todo/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1glln7v

## Looking for a self hosted Form builder for output to PDF
 - [https://www.reddit.com/r/selfhosted/comments/1gllle3/looking_for_a_self_hosted_form_builder_for_output](https://www.reddit.com/r/selfhosted/comments/1gllle3/looking_for_a_self_hosted_form_builder_for_output)
 - RSS feed: $source
 - date published: 2024-11-07T08:07:33+00:00

<!-- SC_OFF --><div class="md"><p>Basically, I’m looking for a form building process that I can self host at home and can travel to a site then via a Mobile fill out a form and not lose it in the mess.</p> <p>Basic quote form.</p> <p>Pencil and paper gets lost too often. </p> <p>I’ve tried a spreadsheet and I find that it was getting corrupted.</p> <p>Many thanks in advance. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dean1969cox"> /u/dean1969cox </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gllle3/looking_for_a_self_hosted_form_builder_for_output/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gllle3/looking_for_a_self_hosted_form_builder_for_output/">[comments]</a></span>

## Will a gpu resurrect potato pc trying to run jellyfin ?
 - [https://www.reddit.com/r/selfhosted/comments/1gllhn2/will_a_gpu_resurrect_potato_pc_trying_to_run](https://www.reddit.com/r/selfhosted/comments/1gllhn2/will_a_gpu_resurrect_potato_pc_trying_to_run)
 - RSS feed: $source
 - date published: 2024-11-07T08:00:22+00:00

<!-- SC_OFF --><div class="md"><p>Hello! I have recently dug out my really old Fujitsu Esprimo E7935 which has a Core 2 Quad 9550 and it uses the intel GMA 4500 integraded graohics. I installed ubuntu server with casa os and jellyfin and Tried streaming a 1080p movie and it stops every 5 seconds and the cpu spikes up to 100% my question is if I get something like a Quadro P400 will it help resurrect the dinosaur or ai am better off buying a mini pc with a newer processor? (I do not care about power consumption because it will be turned on only when streaming movies and tv shows)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AzSumMarto"> /u/AzSumMarto </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gllhn2/will_a_gpu_resurrect_potato_pc_trying_to_run/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gllhn2/will_a_gpu_resurrect_potato_pc_trying_to_run/">[comments]</a></span>

## Proxmox remote connection errors
 - [https://www.reddit.com/r/selfhosted/comments/1gll3r2/proxmox_remote_connection_errors](https://www.reddit.com/r/selfhosted/comments/1gll3r2/proxmox_remote_connection_errors)
 - RSS feed: $source
 - date published: 2024-11-07T07:30:38+00:00

<!-- SC_OFF --><div class="md"><p>Hi, i&#39;m new to proxmox and have installed it and some Containers in it on my homeserver. I now have the issue, that when I try to connect from outside my home network via VPN Connection (fritzbox with build in vpn), that I can reach the proxmox host and the containers only with my iphone vpn connection. On my windows machine i can reach the ip of my fritzbox and the web-gui but not the proxmox host or containers. Do you have any advice, what I could do to reach all IP&#39;s? Thank you in advance for your time and advice.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/HSVMG7"> /u/HSVMG7 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gll3r2/proxmox_remote_connection_errors/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gll3r2/proxmox_remote_connection_errors/">[comments]</a></span>

## Recommend Storage Servers for own CDN
 - [https://www.reddit.com/r/selfhosted/comments/1gll1li/recommend_storage_servers_for_own_cdn](https://www.reddit.com/r/selfhosted/comments/1gll1li/recommend_storage_servers_for_own_cdn)
 - RSS feed: $source
 - date published: 2024-11-07T07:26:12+00:00

<!-- SC_OFF --><div class="md"><p>A project I am working on will utilize its own CDN. This will be for files of up to 10GB in size. I need a fairly priced VPS/VDS/DS that offer at least 1gbit connection, either unmetered or with dozens of TB per month, 4 vCPU, at least 4GB ram, at least 2TB of disk space. Since it is a CDN, I need more than one location.</p> <p>The problem is that each GB of disk space seems to be worth its weight in gold, even though it is 2024 and hardware is cheap AF. Traffic is also often capped at laughable levels. Which makes finding good offers that more problematic. Since I am a techie, i cannot overlook the price point for what is being offered. My eyes cannot roll that far back.</p> <p>So far I came to Contabo and their Storage VPS 3 with 6 vCPU, 12GB RAM, 2.4TB storage, 600Mbit/32TB/m at $14. So I&#39;d go for more weaker instances than fewer beefier ones(ie. 10 instances give me 24TB of storage and 320TB traffic at $140/m). They also cover all locations I

## Hosting documents that people can view but can not download?
 - [https://www.reddit.com/r/selfhosted/comments/1glktwp/hosting_documents_that_people_can_view_but_can](https://www.reddit.com/r/selfhosted/comments/1glktwp/hosting_documents_that_people_can_view_but_can)
 - RSS feed: $source
 - date published: 2024-11-07T07:09:53+00:00

<!-- SC_OFF --><div class="md"><p>Got a strange ask, if it can be done.</p> <p>A way to share documents with users that they can view but they can not download them. At least not without effort well beyond average user. Screenshots are ok if they want to go through that.</p> <p>Thought that maybe papereless would have an option for that, so I spin it up for the first time but nope. Viewing straight pdf and easy download button there.</p> <p>And with that I am out of ideas.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Do_TheEvolution"> /u/Do_TheEvolution </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1glktwp/hosting_documents_that_people_can_view_but_can/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1glktwp/hosting_documents_that_people_can_view_but_can/">[comments]</a></span>

## Intel Arc A310 - transcoding GPU - initial impressions
 - [https://www.reddit.com/r/selfhosted/comments/1glk1o3/intel_arc_a310_transcoding_gpu_initial_impressions](https://www.reddit.com/r/selfhosted/comments/1glk1o3/intel_arc_a310_transcoding_gpu_initial_impressions)
 - RSS feed: $source
 - date published: 2024-11-07T06:14:55+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve have a M2000 and K2200 in my server, and while I like having nVidia for various AI playgrounds, I&#39;m not paying for anything modern (tens of thousands of $$) nor is my server a modern beast, just an old R730xd I bought cheap.</p> <p>However, this means a high bitrate, well encoded, 4k video is going to struggle. I saw someone mention the idea of Intel GPUs on a comment here, so I took a look at what their Arc lines have. For $99, I can get a &lt;50W GPU with all the modern codecs supported (AV1, etc). So instead of a beast of a GPU, I saw it as a Jellyfin specific transcoder that&#39;s cheap.</p> <p>My experience so far:</p> <ul> <li>Had to upgrade to Ubuntu 24.04 -- couldn&#39;t get the driver stack fully operational in 22.04 (even though it says it&#39;s supported by that kernel)</li> <li>Jellyfin setup was a breeze</li> <li>Multiple &quot;normal&quot; streams are no problem. A high bitrate 4k stream that I couldn&#39;t CPU transcode, c

## Play a YouTube Playlist as Sound on Google Nest
 - [https://www.reddit.com/r/selfhosted/comments/1glimgo/play_a_youtube_playlist_as_sound_on_google_nest](https://www.reddit.com/r/selfhosted/comments/1glimgo/play_a_youtube_playlist_as_sound_on_google_nest)
 - RSS feed: $source
 - date published: 2024-11-07T04:46:18+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a self-hosted way to play a YouTube Playlist, audio only, in my Google Nest Mini.</p> <p>That device is already connected to HomeAssistant and I&#39;m already hosting a Jellyfin service.</p> <p>I can think about two directions:</p> <ol> <li>Stream the playlist directly from YouTube, but does this will support random/picking from the playlist?</li> <li>Auto-Download, a service that will auto download any sound added to the playlist to a dedicated library that will be consumed by another simple HomeAssistant integration that know to play local files.</li> </ol> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/baruchiro"> /u/baruchiro </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1glimgo/play_a_youtube_playlist_as_sound_on_google_nest/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1glimgo/play_a_youtube_playlist_as_sound_on_google_nest/"

## 🚀 ClipCascade v1.0.0 Release: macOS Support Now Available!
 - [https://www.reddit.com/r/selfhosted/comments/1gli9o8/clipcascade_v100_release_macos_support_now](https://www.reddit.com/r/selfhosted/comments/1gli9o8/clipcascade_v100_release_macos_support_now)
 - RSS feed: $source
 - date published: 2024-11-07T04:25:42+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1gli9o8/clipcascade_v100_release_macos_support_now/"> <img src="https://external-preview.redd.it/GS-H4P69pgjxXv9FCBlKuG2JaUnASMX3akdZKSUuKQk.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=2082da638c728041c3cf7a249145fd84bba272f7" alt="🚀 ClipCascade v1.0.0 Release: macOS Support Now Available!" title="🚀 ClipCascade v1.0.0 Release: macOS Support Now Available!" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>ClipCascade v1.0.0 is officially live, bringing full macOS support alongside other major updates. This milestone release ensures seamless, secure clipboard synchronization across all major platforms: <strong>Windows, macOS, Linux, and Android</strong>.</p> <p>👉 GitHub repo: <a href="https://github.com/Sathvik-Rao/ClipCascade">ClipCascade GitHub</a></p> <p><a href="https://preview.redd.it/tt8oyb18pezd1.png?width=707&amp;format=png&amp;auto=webp&amp;s=f6d70d62b29162a58aa233d4d4350c9924046985">https://preview

## I built an RSS feed builder with Bun🥖 and Hono🔥 (link in comments)
 - [https://www.reddit.com/r/selfhosted/comments/1glhwnr/i_built_an_rss_feed_builder_with_bun_and_hono](https://www.reddit.com/r/selfhosted/comments/1glhwnr/i_built_an_rss_feed_builder_with_bun_and_hono)
 - RSS feed: $source
 - date published: 2024-11-07T04:05:12+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1glhwnr/i_built_an_rss_feed_builder_with_bun_and_hono/"> <img src="https://b.thumbs.redditmedia.com/Pizfs6VtC3Woiamr5I5wtQ1g9aDyudmjSIrM3cFt8mg.jpg" alt="I built an RSS feed builder with Bun🥖 and Hono🔥 (link in comments)" title="I built an RSS feed builder with Bun🥖 and Hono🔥 (link in comments)" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tbosk"> /u/tbosk </a> <br/> <span><a href="https://www.reddit.com/gallery/1glhwnr">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1glhwnr/i_built_an_rss_feed_builder_with_bun_and_hono/">[comments]</a></span> </td></tr></table>

## Investbrain is a self hosted stock investment portfolio tracker
 - [https://www.reddit.com/r/selfhosted/comments/1glh4d2/investbrain_is_a_self_hosted_stock_investment](https://www.reddit.com/r/selfhosted/comments/1glh4d2/investbrain_is_a_self_hosted_stock_investment)
 - RSS feed: $source
 - date published: 2024-11-07T03:21:02+00:00

<!-- SC_OFF --><div class="md"><p>Howdy <a href="/r/selfhosted">/r/selfhosted</a>, </p> <p>After Google Finance <a href="https://www.howtogeek.com/297651/what-does-it-mean-when-a-company-sherlocks-an-app/">sherlocked</a> its portfolio tracker features, I began piecing together various iterations of a personal investment tracker. This tracker project began several years ago as a basic spreadsheet, which then grew to several hundred lines of custom macros, and ultimately became a PHP application. Earlier this year, I committed to packaging my tracker up to share with the self-hosted community.</p> <p>Today, I&#39;m happy to share v1 of Investbrain. </p> <p>It has multiple market data providers, but uses Yahoo Finance out of the box (no configuration required to get started).</p> <p>The typical user of Investbrain has multiple investment portfolios across multiple brokerages. However, with the addition of the &quot;chat with your portfolio&quot; AI feature, I can easily see folks starti

## Homepage breaks after I edit the config and resetting it doesn't fix it
 - [https://www.reddit.com/r/selfhosted/comments/1glfxrg/homepage_breaks_after_i_edit_the_config_and](https://www.reddit.com/r/selfhosted/comments/1glfxrg/homepage_breaks_after_i_edit_the_config_and)
 - RSS feed: $source
 - date published: 2024-11-07T02:18:07+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m using tteck&#39;s Homepage LXC script and when I test it with the default config the page loads fine, and the refresh button in the lower right corner works, but after I edit settings.yaml it breaks and shows API errors, and changing that file back doesn&#39;t get it working again.</p> <p>I was going to use this config as a starting point to help me work out how to create my own <a href="https://drive.google.com/file/d/1BzCyqMREi2aEQj6DVIMIAFVbEGKya02o/view">https://drive.google.com/file/d/1BzCyqMREi2aEQj6DVIMIAFVbEGKya02o/view</a> and I can edit settings.yaml to add the first bit</p> <p><code>title: sienna/Homepage</code><br/> <code>language: en</code><br/> <code>theme: dark</code><br/> <code>color: zinc</code><br/> <code>target: _self</code><br/> <code>headerStyle: boxed</code><br/> <code>statusStyle: &quot;dot&quot;</code><br/> <code>hideVersion: true</code><br/> <code>disableCollapse: true</code></p> <p>and it still works, but if I then a

## Official v1.0.0 Release of Scraperr, the self-hosted webscraperr
 - [https://www.reddit.com/r/selfhosted/comments/1glf06d/official_v100_release_of_scraperr_the_selfhosted](https://www.reddit.com/r/selfhosted/comments/1glf06d/official_v100_release_of_scraperr_the_selfhosted)
 - RSS feed: $source
 - date published: 2024-11-07T01:30:57+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1glf06d/official_v100_release_of_scraperr_the_selfhosted/"> <img src="https://external-preview.redd.it/B7EINpAYvBJKt7etKBy6bwBW4i22lBge2UfJmV3V3Aw.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=6342f57422bdde4bb069a3908e190e979bde36be" alt="Official v1.0.0 Release of Scraperr, the self-hosted webscraperr" title="Official v1.0.0 Release of Scraperr, the self-hosted webscraperr" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello everyone, just letting you guys know that I have published the first release of Scraperr, my self-hosted webscraper. If you have seen this project before, thats awesome, if not let me tell you about it. </p> <p>This is a fully functional webscraper, created with Next.js and Python, which allows easy scraping of webpages using xpaths. It has a decoupled frontend and backend, which means that you can spin the API up by itself, and submit jobs to it for your own project.</p> <p>Please 

## NFS options
 - [https://www.reddit.com/r/selfhosted/comments/1gleybq/nfs_options](https://www.reddit.com/r/selfhosted/comments/1gleybq/nfs_options)
 - RSS feed: $source
 - date published: 2024-11-07T01:28:27+00:00

<!-- SC_OFF --><div class="md"><p>I recently switched over to k3s and having never used Kubernetes before, I found myself having to make a decision on persistent storage. I attempted to use longhorn for rwx pv’s for things like Immich. I quickly found out (not sure if it was my fault) that losing data was easily possible. Using another computer, I switched to NFS and have been using that just fine but storage is now a problem. I currently have 3 nodes for k3s, 3cp and 3 workers in each, all on identical trigkey minis computers inside Proxmox. With my original longhorn plan, I added a 2tb drive to each computer, along side the 500g m.2 it came with. My nfs computer is a m700 tiny a 500g ssd. What would be the best way to add additional storage so I don’t quickly run out when I start adding media to Immich or other services? Woulda NAS be better or would it be better to set up 3 nfs clients in another vm on the 3 k3s nodes? I don’t really know enough yet to make a good decision and wou

## beginners guide to reverse proxy + tailscale + local dns?
 - [https://www.reddit.com/r/selfhosted/comments/1gle0lx/beginners_guide_to_reverse_proxy_tailscale_local](https://www.reddit.com/r/selfhosted/comments/1gle0lx/beginners_guide_to_reverse_proxy_tailscale_local)
 - RSS feed: $source
 - date published: 2024-11-07T00:42:56+00:00

<!-- SC_OFF --><div class="md"><p>I have been trying to setup NGINX + tailscale + adguard home but for the life of me I cannot find a good beginners tutorial. literally cannot understand much at all and this is my first time using proxmox and linux in general. I have been using ttecks helper script and don&#39;t know what to do after that. anyone have any guides or beginner friend steps? I really don&#39;t care which reverse proxy it is aswell as I just want to get this working</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/HamburgerOnAStick"> /u/HamburgerOnAStick </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gle0lx/beginners_guide_to_reverse_proxy_tailscale_local/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gle0lx/beginners_guide_to_reverse_proxy_tailscale_local/">[comments]</a></span>

## Looking for a self hosted log solution
 - [https://www.reddit.com/r/selfhosted/comments/1gldrle/looking_for_a_self_hosted_log_solution](https://www.reddit.com/r/selfhosted/comments/1gldrle/looking_for_a_self_hosted_log_solution)
 - RSS feed: $source
 - date published: 2024-11-07T00:31:09+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a centralized self hosted solution for all my homelab services. From router logs to docker, syslog, access and AWS services. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/D3imOs8910"> /u/D3imOs8910 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1gldrle/looking_for_a_self_hosted_log_solution/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1gldrle/looking_for_a_self_hosted_log_solution/">[comments]</a></span>

