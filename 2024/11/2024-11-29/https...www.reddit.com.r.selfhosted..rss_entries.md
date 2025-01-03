# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Struggling with Local SSL Reverse Proxy Setup on Caddy and AdGuard Home
 - [https://www.reddit.com/r/selfhosted/comments/1h2ydx3/struggling_with_local_ssl_reverse_proxy_setup_on](https://www.reddit.com/r/selfhosted/comments/1h2ydx3/struggling_with_local_ssl_reverse_proxy_setup_on)
 - RSS feed: $source
 - date published: 2024-11-29T23:04:37+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I’m trying to configure my services under a local domain with an SSL certificate.<br/> I’d like the following:</p> <p><a href="https://192.168.178.161:8006/">https://192.168.178.161:8006/</a> to be accessible via <a href="https://proxmox.home/">https://proxmox.home/</a><br/> <a href="https://192.168.178.203:8096/">https://192.168.178.203:8096/</a> to be accessible via <a href="https://jellyfin.home/">https://jellyfin.home/</a></p> <p>And so on.</p> <p>Currently, I’ve set up AdGuard Home, and on the router, I’ve configured the primary IPv4 and IPv6 DNS to AdGuard, and the secondary IPv4 and IPv6 DNS to Google&#39;s (since the server is not always on).</p> <p>Now, I’m trying to figure out how to use Caddy, but I’m struggling, probably due to gaps in my knowledge (I’m not a sysadmin and I’m not very experienced with networking).</p> <p>This is what I have in my Caddyfile:</p> <pre><code>jellyfin.local { reverse_proxy https://192.168.178.203

## FYI if you're looking for external selfhosting service: tons of Black Friday sales going on
 - [https://www.reddit.com/r/selfhosted/comments/1h2y1ul/fyi_if_youre_looking_for_external_selfhosting](https://www.reddit.com/r/selfhosted/comments/1h2y1ul/fyi_if_youre_looking_for_external_selfhosting)
 - RSS feed: $source
 - date published: 2024-11-29T22:48:24+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1h2y1ul/fyi_if_youre_looking_for_external_selfhosting/"> <img src="https://external-preview.redd.it/GL_dWk71ZRF0u7sy7ee2HnnRqCNOrPUdAzL3Un4Yal8.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=bb2afc0fcf97e86e018b7cabde1fd21d69993a98" alt="FYI if you're looking for external selfhosting service: tons of Black Friday sales going on" title="FYI if you're looking for external selfhosting service: tons of Black Friday sales going on" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tgp1994"> /u/tgp1994 </a> <br/> <span><a href="https://lowendbox.com/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2y1ul/fyi_if_youre_looking_for_external_selfhosting/">[comments]</a></span> </td></tr></table>

## Do you find yourself overengineering your life?
 - [https://www.reddit.com/r/selfhosted/comments/1h2xohb/do_you_find_yourself_overengineering_your_life](https://www.reddit.com/r/selfhosted/comments/1h2xohb/do_you_find_yourself_overengineering_your_life)
 - RSS feed: $source
 - date published: 2024-11-29T22:30:31+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ll start by saying: I love this hobby. I love having control of my data and being able to customize things however I like. </p> <p>There are so many things I want to do to ultimately own all of my information on my server, but some of the things I go to setup feel like I&#39;m putting so much effort in to get them to work, maintain them, etc, that it&#39;s not worth the effort at that point and I feel like I&#39;m overengineering things that <em>should</em> be simple. </p> <p>A few examples: </p> <ul> <li>I want to keep track of all my budgeting locally, so I&#39;ve setup Actual Budget with SimpleFIN to connect my Canadian banks, but I can&#39;t for the life of me get it to consistently sync for more than a few days without the sync becoming broken (SimpleFIN constantly needs me to auth each bank again) </li> <li>I want to track the time I spend on projects (as I find myself losing track often). I used Toggl Track in the past but this past week

## Hardware recommendation
 - [https://www.reddit.com/r/selfhosted/comments/1h2xl05/hardware_recommendation](https://www.reddit.com/r/selfhosted/comments/1h2xl05/hardware_recommendation)
 - RSS feed: $source
 - date published: 2024-11-29T22:25:59+00:00

<!-- SC_OFF --><div class="md"><p>Hello!</p> <p>I am looking to upgrade my main server for containers and VMs and I need some hardware suggestions.</p> <p>I am looking to run Proxmox on it.<br/> I plan to have a Debian VM that has all the docker containers that I plan to run (currently around 60 containers, using 10-15GB RAM) and enough resources to have some Windows, Linux, VMs for testing or other projects, containers, etc.</p> <p>So for components I think I want:</p> <p>PSU: Something with enough power for the system, preferably Platinum, I have my eyes on a Super Flower Leadex 7 Pro 850W (I hope would be enough)</p> <p>Case: I would like for it to not be to big if possible, but I accept Fractal Design 7 or Antec Flux Pro</p> <p>Motherboard: Something AM5? or should I go Intel? I think one 500GB SSD for Proxmox and another with 2-4TB would be enough for VMs. I do not plan to overclock, so I do not need the features from X870E motherboards(Wi-Fi 7, USB4). I will be fine with A seri

## What do you use to store metrics?
 - [https://www.reddit.com/r/selfhosted/comments/1h2x9i1/what_do_you_use_to_store_metrics](https://www.reddit.com/r/selfhosted/comments/1h2x9i1/what_do_you_use_to_store_metrics)
 - RSS feed: $source
 - date published: 2024-11-29T22:11:02+00:00

<!-- SC_OFF --><div class="md"><p>Currently I have Telegraf, InfluxDB (v1.8), and Grafana. InfluxDB is mostly used to store system metrics (CPU, memory etc.), some container metrics, and some data imported from HomeAssistant. Everything is collected by Telegraf. v1.8 is quite outdated, and I&#39;ve been thinking about upgrading it to v3 (or whatever is the latest version). Migrating to v3 will require me exporting/importing data, they also changed the query language IIRC. So I also had this idea to try something else instead of Influx. What do you use? Are there better alternatives?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/amniotic505"> /u/amniotic505 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2x9i1/what_do_you_use_to_store_metrics/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2x9i1/what_do_you_use_to_store_metrics/">[comments]</a></span>

## Booking/Appointment app when two providers are required per appointment
 - [https://www.reddit.com/r/selfhosted/comments/1h2x8xa/bookingappointment_app_when_two_providers_are](https://www.reddit.com/r/selfhosted/comments/1h2x8xa/bookingappointment_app_when_two_providers_are)
 - RSS feed: $source
 - date published: 2024-11-29T22:10:18+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m part of a volunteer group that goes two-at-a-time to one-time visits with our customers. This is similar, but different in an important way from what most booking software is built for. </p> <p>Ideally, some volunteers would be able to connect their Google or icloud calendars and select times they are available (minus times their personal calendar shows they are not available), and others would manually enter their availability. Our customers would see a list of times that at least two of the volunteer team is available and would be able to select a time. The system would send all three people appointments and reminders.</p> <p>Aside from needing two providers, this is what all booking software does. So far, we need a human to align the three schedules and it&#39;s a taxing job for a volunteer. I would think that two providers isn&#39;t uncommon: a dentist and a hygienist, a nurse and a doctor, but in those cases, those are jobs with more reg

## Best self hosted Blog?
 - [https://www.reddit.com/r/selfhosted/comments/1h2x1hy/best_self_hosted_blog](https://www.reddit.com/r/selfhosted/comments/1h2x1hy/best_self_hosted_blog)
 - RSS feed: $source
 - date published: 2024-11-29T22:00:50+00:00

<!-- SC_OFF --><div class="md"><p>Should be simple minimalistic, look pretty and work with markdown files. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Admirable-Country-29"> /u/Admirable-Country-29 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2x1hy/best_self_hosted_blog/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2x1hy/best_self_hosted_blog/">[comments]</a></span>

## Stream HDMI to Fire Stick
 - [https://www.reddit.com/r/selfhosted/comments/1h2x09q/stream_hdmi_to_fire_stick](https://www.reddit.com/r/selfhosted/comments/1h2x09q/stream_hdmi_to_fire_stick)
 - RSS feed: $source
 - date published: 2024-11-29T21:59:23+00:00

<!-- SC_OFF --><div class="md"><p>In a cost cutting exercise we’re ditching our “mini boxes” from our satellite provider. We’re paying £10 a month for them and I only really use it for watching the odd Eagles game in bed. It had me thinking though, given the main box has a remote interface, can I just split the HDMI and stream it upstairs somehow. Then I remembered I have a spare Avermedia Live with hdmi pass through. This is where you all fit in. I have a Raspberry Pi behind my TV already running Cloudlfared and Zigbee2MQTT. Can I plug the avermedia into that and transmit the HDMI signal to the fire stick plugged into my bedroom TV? If so, what’s the best way? It would also be cool to be able to watch this over Tailscale when we’re out of the house.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Nikorag90"> /u/Nikorag90 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2x09q/stream_hdmi_to_fire_stick/">[link]</a></span> 

## Best practice for homelab vlan & security?
 - [https://www.reddit.com/r/selfhosted/comments/1h2wl51/best_practice_for_homelab_vlan_security](https://www.reddit.com/r/selfhosted/comments/1h2wl51/best_practice_for_homelab_vlan_security)
 - RSS feed: $source
 - date published: 2024-11-29T21:39:46+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1h2wl51/best_practice_for_homelab_vlan_security/"> <img src="https://b.thumbs.redditmedia.com/U6dAA_ibPtsWC8V7_jIIJpQS3ozu5MwcTEXlRlsQvlg.jpg" alt="Best practice for homelab vlan &amp; security?" title="Best practice for homelab vlan &amp; security?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>vlan trunk/tagging &amp; firewall rules are very simple concept to grasp, but simple base rules can create a very complex and confusing systems. </p> <p>I use to have very simple vlan setup but find myself confused while trying to do a more complex and secure setup. Hoping to get some help on directions.</p> <p>Attached below is an overview what I have implemented so far, all based on unifi network gear and proxmox. </p> <p>I got the idea and have wired and tagged dedicated cables for external &amp; local traffic. and put my rev-proxy in vlan ext0, but run into following confusion all around the red color lines</p> <

## Need assistance with mailcow
 - [https://www.reddit.com/r/selfhosted/comments/1h2wjri/need_assistance_with_mailcow](https://www.reddit.com/r/selfhosted/comments/1h2wjri/need_assistance_with_mailcow)
 - RSS feed: $source
 - date published: 2024-11-29T21:37:58+00:00

<!-- SC_OFF --><div class="md"><p>Has anyone set up mailcow on aws? Having some issues with rdns, and others. Not sure if i should move out completely and go to hertzner. I have a specific automation in mind, and would love some input. Goal is cold outreach, with deliverability in mind, so eventually dedicated ips in mind, warmed up ofc. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dramakq"> /u/dramakq </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2wjri/need_assistance_with_mailcow/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2wjri/need_assistance_with_mailcow/">[comments]</a></span>

## Homeserver/Retro Gaming console (beginner)
 - [https://www.reddit.com/r/selfhosted/comments/1h2wg3n/homeserverretro_gaming_console_beginner](https://www.reddit.com/r/selfhosted/comments/1h2wg3n/homeserverretro_gaming_console_beginner)
 - RSS feed: $source
 - date published: 2024-11-29T21:33:24+00:00

<!-- SC_OFF --><div class="md"><p>sry for AI text</p> <p>I recently built a new PC, but I can&#39;t part with my old one, so I want to repurpose it as a basic home server. It doesn&#39;t need to run all the time—just enough to free up some space on my phone (photos, vids and randome files). But I also want to use it for retro gaming on my TV.</p> <p>I don&#39;t want to just connect the PC to the TV via HDMI and call it a day. That would be too easy. I want a seamless experience where I don&#39;t need a mouse, keyboard, or see Windows booting up the emulator.</p> <p>I&#39;m thinking of using Wake-on-LAN to avoid keeping the PC running 24/7. My plan is to send a basic command from my phone to power up the PC and launch the emulator (or just the pc without opening emulator just to send some files or whatever), and then turn on the TV afterward. I want the experience to feel seamless.</p> <p>Would this setup work as I imagine?</p> <p>Additionally, while I could connect the PC to the TV v

## Should I put an HTTPS proxy in front of my web server to simplify dealing with certs?
 - [https://www.reddit.com/r/selfhosted/comments/1h2vhh2/should_i_put_an_https_proxy_in_front_of_my_web](https://www.reddit.com/r/selfhosted/comments/1h2vhh2/should_i_put_an_https_proxy_in_front_of_my_web)
 - RSS feed: $source
 - date published: 2024-11-29T20:49:09+00:00

<!-- SC_OFF --><div class="md"><p>I have a web server facing the Internet hosted on a Digital Ocean droplet. It works great, but I try to avoid making changes directly in production, so I change the &quot;staging&quot; system first, and then redeploy. Every time I re-deploy, I have to deal with certbot and letsencrypt to re-create certificates. This slows down the deployment process and, frankly, is annoying.</p> <p>I am thinking of introducing a simple HTTPS gateway that would work similar to API Gateway in AWS: face the Internet, handle the certs and redirect the traffic to the internal web server using plain old HTTP.</p> <p>Is it a good idea? Bad idea? What should I use for the proxy? My web server is Apache, but I am open to use nginx or other solution for the proxy.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Character-Extent-436"> /u/Character-Extent-436 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2vhh2/sh

## lurker: selfhostable, read-only reddit client
 - [https://www.reddit.com/r/selfhosted/comments/1h2uwcl/lurker_selfhostable_readonly_reddit_client](https://www.reddit.com/r/selfhosted/comments/1h2uwcl/lurker_selfhostable_readonly_reddit_client)
 - RSS feed: $source
 - date published: 2024-11-29T20:22:24+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1h2uwcl/lurker_selfhostable_readonly_reddit_client/"> <img src="https://external-preview.redd.it/yPpPXw3YqKx8gWySJzmsDn1hO3zvL-1t-rB37BSThVE.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=06df0ccd0eafe9ca3d00e553ebd525985eefa990" alt="lurker: selfhostable, read-only reddit client" title="lurker: selfhostable, read-only reddit client" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Creative-Air2049"> /u/Creative-Air2049 </a> <br/> <span><a href="https://github.com/oppiliappan/lurker">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2uwcl/lurker_selfhostable_readonly_reddit_client/">[comments]</a></span> </td></tr></table>

## self hosted or storage vps
 - [https://www.reddit.com/r/selfhosted/comments/1h2u5e1/self_hosted_or_storage_vps](https://www.reddit.com/r/selfhosted/comments/1h2u5e1/self_hosted_or_storage_vps)
 - RSS feed: $source
 - date published: 2024-11-29T19:48:21+00:00

<!-- SC_OFF --><div class="md"><p>Hello,<br/> I am into self hosting for years (then moved some to saas to avoid managing thats a different story)</p> <p>but recently i got into jellyfin etc media world and my wife absolutely loving the comfort of it.</p> <p>i already have 1tb dedi and now planning to get a 5tb vps on deals.</p> <p>i am really wondering, whether i should get a vps or just selfhost everything at home?</p> <p>i have a pc which runs almost 24x7 at home and i am comfortable with docker and all (doing for years on linux but no so hard on windows too imo)</p> <p>so what do you guys suggest?</p> <p>we mostly use it to watch movies at home using chromecast (so far didn&#39;t give my jellyfin details to any friends so mostly watching from home only)</p> <p>please advice.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Either-Nobody-3962"> /u/Either-Nobody-3962 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2u5e1

## Remote Gaming
 - [https://www.reddit.com/r/selfhosted/comments/1h2tvte/remote_gaming](https://www.reddit.com/r/selfhosted/comments/1h2tvte/remote_gaming)
 - RSS feed: $source
 - date published: 2024-11-29T19:36:23+00:00

<!-- SC_OFF --><div class="md"><p>Looking for a way to remotely access my desktop while also playing some occasional games that are graphic intensive. I&#39;ve been looking into Sunshine/Moonlight for this. Is this the best recommendation or do you have better options for specifically the gaming piece?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PhaseDirect4273"> /u/PhaseDirect4273 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2tvte/remote_gaming/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2tvte/remote_gaming/">[comments]</a></span>

## Homebox v0.016.0 Released
 - [https://www.reddit.com/r/selfhosted/comments/1h2tqs3/homebox_v00160_released](https://www.reddit.com/r/selfhosted/comments/1h2tqs3/homebox_v00160_released)
 - RSS feed: $source
 - date published: 2024-11-29T19:30:11+00:00

<!-- SC_OFF --><div class="md"><h1>Homebox V0.16.0 released!</h1> <p><a href="https://homebox.software/">Homebox </a>is proud to announce the release of version 0.16.0 !</p> <p><strong>But first, what is Homebox?</strong></p> <p>Homebox is the inventory and organization system built for the Home User! With a focus on simplicity and ease of use. Homebox is the perfect solution for your home inventory, organization, and management needs.</p> <p><strong>About the update</strong></p> <p>We have officially released v0.16.0 and at the same time are making progress towards v1 (stable). This release is mostly bug fixes, more translation support, and some general improvements. As always, we continue to accept new languages and translations on our <a href="https://translate.sysadminsmedia.com">weblate instance</a> if you&#39;re interested in contributing.</p> <p>On the v1 side you can keep up to date on Github via the vnext branch (we added PostgreSQL support, and are currently working on supp

## Port forwarding service question
 - [https://www.reddit.com/r/selfhosted/comments/1h2ss2k/port_forwarding_service_question](https://www.reddit.com/r/selfhosted/comments/1h2ss2k/port_forwarding_service_question)
 - RSS feed: $source
 - date published: 2024-11-29T18:48:48+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I&#39;d liie to open my home webserver to the public, aka do some port forwarding. But this will not protect my ip from being seen and will leave me vulnerable to ddos attacks. I have heard about services which receive requests and then route data to you and the other way around.</p> <p>This way it will also not be your own public ip but rather one of that service.</p> <p>What are some services that offer this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Healthy_Ease_3842"> /u/Healthy_Ease_3842 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2ss2k/port_forwarding_service_question/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2ss2k/port_forwarding_service_question/">[comments]</a></span>

## The ideal cloud? (self-hosted)
 - [https://www.reddit.com/r/selfhosted/comments/1h2s433/the_ideal_cloud_selfhosted](https://www.reddit.com/r/selfhosted/comments/1h2s433/the_ideal_cloud_selfhosted)
 - RSS feed: $source
 - date published: 2024-11-29T18:19:58+00:00

<!-- SC_OFF --><div class="md"><p>Hello Community,</p> <p>I&#39;m currently planning my home lab, which I&#39;m going to set up after Christmas. As I have lost confidence in non-self-hosted storage solutions, I am looking for a suitable alternative that fulfills the following criteria:</p> <p>-self-hosted<br/> -encrypted<br/> -secure<br/> -(mobile apps)<br/> -webdav<br/> -lightweight<br/> -(with web interface)<br/> -with possibility to share via link<br/> -with possibility to upload via link</p> <p>The first thing that comes to mind is of course Nextcloud - I&#39;ve just read a lot and experienced myself that Nextcloud is quite slow and sluggish. Seafile is supposed to be good, but the web interface there is pretty old-fashioned and the backup is probably quite difficult in the event of a crash. A simple backup strategy would be great...</p> <p>I know that these are quite a lot of requirements... But I haven&#39;t really found the &#39;ideal&#39; cloud for me yet...</p> <p>What do yo

## Die ideale Cloud (selfhosted)
 - [https://www.reddit.com/r/selfhosted/comments/1h2s0c7/die_ideale_cloud_selfhosted](https://www.reddit.com/r/selfhosted/comments/1h2s0c7/die_ideale_cloud_selfhosted)
 - RSS feed: $source
 - date published: 2024-11-29T18:15:31+00:00

<!-- SC_OFF --><div class="md"><p>Hallo Community,</p> <p>ich bin gerade am planen meines Homelabs, welches ich mir nach Weihnachten aufbauen werde. Da ich das Vertrauen in nicht selbstgehostete Speicherlösungen mittlerweile stark verloren habe, suche ich nach einer geeigneten Alternative, welche folgende Kriterien erfüllt:</p> <p>-selbsthostbar<br/> -verschlüsselt<br/> -sicher<br/> -(mobile apps)<br/> -webdav<br/> -leichtgewichtig<br/> -(mit weboberfläche)<br/> -mit möglichkeit zum teilen per link<br/> -mit möglichkeit zum hochladen per link</p> <p>Als erstes kommt mir da natürlich Nextcloud in den Sinn - ich habe nur sehr viel gelesen und selbst erlebt, dass Nextcloud ziemlich träge und langsam ist. Seafile soll gut sein, jedoch ist das Webinterface dort ziemlich altbacken und außerdem ist wohl das Backup im Falle eines Crashes recht schwierig. Eine einfache Backup Strategie wäre super...</p> <p>Ich weiß, dass das ziemlich viele Anforderungen sind.. So richtig habe ich die &#39;ide

## Looking for a customer support/ ticketing system that can integrate with AI/LLMs
 - [https://www.reddit.com/r/selfhosted/comments/1h2rd91/looking_for_a_customer_support_ticketing_system](https://www.reddit.com/r/selfhosted/comments/1h2rd91/looking_for_a_customer_support_ticketing_system)
 - RSS feed: $source
 - date published: 2024-11-29T17:47:57+00:00

<!-- SC_OFF --><div class="md"><p>Hello, </p> <p>I am searching for an open source self-hostable customer support/ticketing system for my company. I am wondering if a tool exists where tickets can be created from multiple sources (n8n, email) and some rules/logic can be setup to allow AI and LLMs to process the messages and act on some of them + leave the rest for human review</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pravictor"> /u/pravictor </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2rd91/looking_for_a_customer_support_ticketing_system/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2rd91/looking_for_a_customer_support_ticketing_system/">[comments]</a></span>

## Created A Self Hosted Bookmark Manager
 - [https://www.reddit.com/r/selfhosted/comments/1h2qv9g/created_a_self_hosted_bookmark_manager](https://www.reddit.com/r/selfhosted/comments/1h2qv9g/created_a_self_hosted_bookmark_manager)
 - RSS feed: $source
 - date published: 2024-11-29T17:26:15+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1h2qv9g/created_a_self_hosted_bookmark_manager/"> <img src="https://external-preview.redd.it/QbB5EYn_hc3e2wtvqTLPqwfL7AOL7jj5-woaJpszIPM.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=8891406f003f56ff40d526b838b9f30e023820d6" alt="Created A Self Hosted Bookmark Manager" title="Created A Self Hosted Bookmark Manager" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello all,</p> <p>I have created a self-hosted bookmark management built with Ruby on Rails and Vue.js.</p> <p>Which Supports Automatic thumbnails for links with <a href="http://www.linkpreview.net">www.linkpreview.net</a></p> <p>You can share feedback or let me know if you want specific features built into it.</p> <p>Data is saved into PostgreSQL Database, you can add your already setup postgres or you can use official docker image <a href="https://hub.docker.com/_/postgres">https://hub.docker.com/_/postgres</a> or setup manually and provide host a

## Foss field management software
 - [https://www.reddit.com/r/selfhosted/comments/1h2qts5/foss_field_management_software](https://www.reddit.com/r/selfhosted/comments/1h2qts5/foss_field_management_software)
 - RSS feed: $source
 - date published: 2024-11-29T17:24:27+00:00

<!-- SC_OFF --><div class="md"><p>Does it exist? I want to try something for a friend that has a cleaning business, he just got his first employee. I come across jobber, housecall pro, ..</p> <p>Been looking but don&#39;t find anything close. Anybody got some clues? Maybe I should be looking at project management software?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/loogojoost"> /u/loogojoost </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2qts5/foss_field_management_software/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2qts5/foss_field_management_software/">[comments]</a></span>

## A couple BIG questions before setting up a media server
 - [https://www.reddit.com/r/selfhosted/comments/1h2qbjk/a_couple_big_questions_before_setting_up_a_media](https://www.reddit.com/r/selfhosted/comments/1h2qbjk/a_couple_big_questions_before_setting_up_a_media)
 - RSS feed: $source
 - date published: 2024-11-29T17:02:36+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;m looking into self hosting a media library. There are a few things I want to achieve and am interested in y&#39;all&#39;s opinions. </p> <p>I want to accomplish two things:<br/> Host a video/music library for all of the movies/music I own that I can share with family (5 households total).<br/> Host home videos/photos for my parents so they can access on any device.</p> <p>I was looking at the differences between Plex and Jellyfin. I was really gravitating toward Jellyfin but it doesn&#39;t appear to be able to host photos. I would prefer not to go with another app just for photos because I think that will confuse my parents. Plex can host photos, but users seem to be really unhappy with recent changes to the app. What do you think?</p> <p>In either of these apps, can I set profiles and passwords to keep the family photos separate and to set up a kids profile and keep them away from the adult movies?</p> <p>Lastly, might be a stupid questio

## Has Anyone Worked with Facebook API for Events Post-Pandemic? Looking for Guidance!
 - [https://www.reddit.com/r/selfhosted/comments/1h2p1tj/has_anyone_worked_with_facebook_api_for_events](https://www.reddit.com/r/selfhosted/comments/1h2p1tj/has_anyone_worked_with_facebook_api_for_events)
 - RSS feed: $source
 - date published: 2024-11-29T16:06:16+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I’m a developer working on a Rails app that integrates events, and I’m looking for some help or insights from anyone who’s had experience with Facebook’s API, particularly for events.</p> <p>It seems like Facebook restricted a lot of API access during the pandemic, and it hasn’t really opened back up for public use since. My goal is to: 1. Parse Facebook events to create corresponding events on my Rails app. 2. Allow users to create events on my app and have those populate directly into Facebook under their profiles or pages.</p> <p>From my research, the current state of Facebook’s API seems pretty restrictive when it comes to event data. I’m curious if anyone here has had success working with Facebook events recently, found any workarounds, or navigated similar challenges.</p> <p>Are there any strategies or alternative methods you’d recommend for parsing event data or syncing events with Facebook? I’d really appreciate hearing your ex

## What and how many devices are in your HA?
 - [https://www.reddit.com/r/selfhosted/comments/1h2oxuw/what_and_how_many_devices_are_in_your_ha](https://www.reddit.com/r/selfhosted/comments/1h2oxuw/what_and_how_many_devices_are_in_your_ha)
 - RSS feed: $source
 - date published: 2024-11-29T16:01:31+00:00

<!-- SC_OFF --><div class="md"><p>I noticed, lots of people has hosted home assistant. What kind of devices are you managing using that. Are you actively opening home assistant? More clear how you are utilizing home assistant?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/munir131"> /u/munir131 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2oxuw/what_and_how_many_devices_are_in_your_ha/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2oxuw/what_and_how_many_devices_are_in_your_ha/">[comments]</a></span>

## Raspberry pi 5 or old PC?
 - [https://www.reddit.com/r/selfhosted/comments/1h2owlj/raspberry_pi_5_or_old_pc](https://www.reddit.com/r/selfhosted/comments/1h2owlj/raspberry_pi_5_or_old_pc)
 - RSS feed: $source
 - date published: 2024-11-29T16:00:07+00:00

<!-- SC_OFF --><div class="md"><p>I recently got into self hosting and having a personal server, but just locally on WSL and I now have to actually get a server. my question was: pi 5 (8gb ram) or an old PC?</p> <p>I&#39;ll install debian server on it and run multiple docker containers like: * home assistant * nginx proxy manager * 2 discord bots (150mb ram max each) * possibly a private minecraft server with panel * nextcloud * glances * other miscellaneous apis (very low usage when idle) ^ I&#39;ll probably add more stuff time to time</p> <p>Now. I know all this can run on a pi 5 except for the mc server, I&#39;ve heard Minecraft on pi 5 is not the best idea.</p> <p>My number one concern is energy consumption. I know the pi is built to use less energy than normal PC&#39;s, but I&#39;m not sure with the purchase for both performance and the fact that it&#39;s not upgradable. unlike normal PC&#39;s if you want to upgrade a pi you&#39;d have to buy the entire pi again (if a better ver

## I Built a Simple Tool to Generate HTML Bookmark Files for Linkwarden!
 - [https://www.reddit.com/r/selfhosted/comments/1h2ol2a/i_built_a_simple_tool_to_generate_html_bookmark](https://www.reddit.com/r/selfhosted/comments/1h2ol2a/i_built_a_simple_tool_to_generate_html_bookmark)
 - RSS feed: $source
 - date published: 2024-11-29T15:45:16+00:00

<!-- SC_OFF --><div class="md"><p>Just paste a list of URLs or CSV (comma, space, or newline-separated), and it converts them into an HTML Bookmark File (Netscape format), ready for Linkwarden or any browser. Quick, simple, and hassle-free! <a href="https://minmaxd.com/html-bookmark-file-generator">Try it here</a> . Have ideas or feature requests? Let me know—I’d love to improve it! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dinweldik"> /u/dinweldik </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2ol2a/i_built_a_simple_tool_to_generate_html_bookmark/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2ol2a/i_built_a_simple_tool_to_generate_html_bookmark/">[comments]</a></span>

## How can i let only certain users or groups use ldap?
 - [https://www.reddit.com/r/selfhosted/comments/1h2o72o/how_can_i_let_only_certain_users_or_groups_use](https://www.reddit.com/r/selfhosted/comments/1h2o72o/how_can_i_let_only_certain_users_or_groups_use)
 - RSS feed: $source
 - date published: 2024-11-29T15:27:01+00:00

<!-- SC_OFF --><div class="md"><p>Hallo</p> <p>Say i have different groups of users such as employees and clients and i only want employees to be able to use the ldap service to login, whereabout do i set this up?<br/> thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/future_lard"> /u/future_lard </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2o72o/how_can_i_let_only_certain_users_or_groups_use/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2o72o/how_can_i_let_only_certain_users_or_groups_use/">[comments]</a></span>

## Raspberry Pi 5 Jellyfin on Docker Lags When Streaming 4K
 - [https://www.reddit.com/r/selfhosted/comments/1h2o4zi/raspberry_pi_5_jellyfin_on_docker_lags_when](https://www.reddit.com/r/selfhosted/comments/1h2o4zi/raspberry_pi_5_jellyfin_on_docker_lags_when)
 - RSS feed: $source
 - date published: 2024-11-29T15:24:18+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,<br/> I’m running Jellyfin in a Docker container on a Raspberry Pi 5 and having trouble with 4K video streaming. The videos I’m trying to stream are large files (10-20GB), and they lag a lot, with constant buffering. I also noticed that the CPU usage shoots up to 90% or more when streaming, which I guess is part of the issue.</p> <p>I’m new to video streaming optimization, so I’m not sure where to start. Should I enable transcoding to make things smoother, or will that just add more load to the CPU? Are there any other ways to improve performance?</p> <p>For context, I’m using the Arr stack to download videos, and I’m not sure if my setup is good enough to handle 4K. Any advice or tips would be a huge help. Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/YPO_007"> /u/YPO_007 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2o4zi/raspberry_pi_5_jellyfin_on_docker_lags_w

## The Proxmox cluster probe
 - [https://www.reddit.com/r/selfhosted/comments/1h2nqd5/the_proxmox_cluster_probe](https://www.reddit.com/r/selfhosted/comments/1h2nqd5/the_proxmox_cluster_probe)
 - RSS feed: $source
 - date published: 2024-11-29T15:05:08+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/esiy0676"> /u/esiy0676 </a> <br/> <span><a href="https://www.reddit.com/r/ProxmoxQA/comments/1h2m3dv/the_proxmox_cluster_probe/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2nqd5/the_proxmox_cluster_probe/">[comments]</a></span>

## Booked lives on
 - [https://www.reddit.com/r/selfhosted/comments/1h2nplw/booked_lives_on](https://www.reddit.com/r/selfhosted/comments/1h2nplw/booked_lives_on)
 - RSS feed: $source
 - date published: 2024-11-29T15:04:06+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1h2nplw/booked_lives_on/"> <img src="https://external-preview.redd.it/PITkz5_XJk1K927dVDtDwY4uxUL3fHO5ktmx289lvaI.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=6b42efe22edbc6b8a8d4fb7cac298f80588b0de8" alt="Booked lives on" title="Booked lives on" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>For my sports club, I’m using the self hosted, open source version of Booked Scheduler. With this system, people can make reservations for sources, mostly meeting rooms.</p> <p>Since a few years, the open source version of Booked (formerly PHPScheduleIt) is discontinued. Therefor, I was glad to hear that someone (or group) has forked it. It now lives on as Librebooking.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dvandergeld"> /u/dvandergeld </a> <br/> <span><a href="https://github.com/LibreBooking/app">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhost

## Orbsmart R82
 - [https://www.reddit.com/r/selfhosted/comments/1h2mge3/orbsmart_r82](https://www.reddit.com/r/selfhosted/comments/1h2mge3/orbsmart_r82)
 - RSS feed: $source
 - date published: 2024-11-29T14:03:41+00:00

<!-- SC_OFF --><div class="md"><p>Alright ladies and gentlemen of this wonderful subreddit.</p> <p>As you are probably going to notice, while reading this post, I am mildly excited. For a while now I&#39;ve been looking for a device to replace my horrible smart TV&#39;s streaming and media capabilities (srsly, fuck smart TVs, I&#39;d rather buy dumb monitors but here we are...). After reading through many threads, doing lots of comparisons etc etc I&#39;ve settled for a device that is recommended <strong>nowhere</strong>.</p> <p>Yes, you heard that right, a device that hasn&#39;t been recommended anywhere and which I just so happened to stumple upon during the black friday deals this week. It&#39;s the Orbsmart R82 (specifically this device: <a href="https://www.orbsmart.de/en/produkte/orbsmart-r82/">https://www.orbsmart.de/en/produkte/orbsmart-r82/</a>)</p> <p>It&#39;s an android TV box by a German company that supports <em>all</em> modern audio and video codecs (including AV1) and 

## font.delivery - A webfont download service
 - [https://www.reddit.com/r/selfhosted/comments/1h2mbz4/fontdelivery_a_webfont_download_service](https://www.reddit.com/r/selfhosted/comments/1h2mbz4/fontdelivery_a_webfont_download_service)
 - RSS feed: $source
 - date published: 2024-11-29T13:57:39+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone!</p> <p>I built a webfont download service that let&#39;s you download and self-host any font available on Google fonts: <a href="https://font.delivery/">https://font.delivery/</a></p> <p>The source code is available at <a href="https://github.com/sfhorg/font.delivery">https://github.com/sfhorg/font.delivery</a> and there&#39;s also a CLI available on the GitHub releases page.</p> <p>Hope it will be useful for someone!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/alyxell"> /u/alyxell </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2mbz4/fontdelivery_a_webfont_download_service/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2mbz4/fontdelivery_a_webfont_download_service/">[comments]</a></span>

## Steam Game Proxy to handle DDoS
 - [https://www.reddit.com/r/selfhosted/comments/1h2m78w/steam_game_proxy_to_handle_ddos](https://www.reddit.com/r/selfhosted/comments/1h2m78w/steam_game_proxy_to_handle_ddos)
 - RSS feed: $source
 - date published: 2024-11-29T13:50:34+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been paying a little over 100 a month for a dedicated game server that also hosts my website and bots.</p> <p>I&#39;m purchasing parts to build a second computer at my house, but my concern in disgruntled players DDoSing the server. My server is open to the public, so network security is gunna need to be a thing.</p> <p>I was wondering how I would route traffic through a proxy somehow to mask my ip. Maybe cloudflare or something? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Neat-Consequence-247"> /u/Neat-Consequence-247 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2m78w/steam_game_proxy_to_handle_ddos/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2m78w/steam_game_proxy_to_handle_ddos/">[comments]</a></span>

## Looking for a simple, self-hosted charting tool with a REST API
 - [https://www.reddit.com/r/selfhosted/comments/1h2leg3/looking_for_a_simple_selfhosted_charting_tool](https://www.reddit.com/r/selfhosted/comments/1h2leg3/looking_for_a_simple_selfhosted_charting_tool)
 - RSS feed: $source
 - date published: 2024-11-29T13:07:16+00:00

<!-- SC_OFF --><div class="md"><p>I want a simple self-hosted charting tool with a simple API to update data. It doesn&#39;t have to have integration to connect to data sources, I just want simple endpoints I can use to update my time series data. Example usage would be:</p> <ol> <li><strong>Create a chart:</strong> A command-line tool (or equivalent) lets me create a chart (e.g., <code>cmdTool create livingRoomTemp</code>). Or from the UI.</li> <li><strong>Update data via REST API:</strong> I&#39;d send POST requests (e.g., <strong>POST</strong> <code>/charts/{chartId}/data</code><strong>:</strong> To update the data for an existing chart. </li> <li><strong>Automatic updates and visualization:</strong> The tool automatically updates the chart with the new data and displays it on a dashboard.</li> </ol> <p>I would like to use this as a central dashboard to collect and visualize various data I&#39;m collecting or tracking.</p> <p>In other words, it takes care of receiving the data via

## This Week in Self-Hosted (29 November 2024)
 - [https://www.reddit.com/r/selfhosted/comments/1h2l9xd/this_week_in_selfhosted_29_november_2024](https://www.reddit.com/r/selfhosted/comments/1h2l9xd/this_week_in_selfhosted_29_november_2024)
 - RSS feed: $source
 - date published: 2024-11-29T13:00:28+00:00

<!-- SC_OFF --><div class="md"><p>Happy Friday, <a href="/r/selfhosted">r/selfhosted</a>! Linked below is the latest edition of <em>This Week in Self-Hosted</em>, a weekly newsletter recap of the latest activity in self-hosted software.</p> <p>This week&#39;s content includes new Raspberry Pi hardware, .io domain speculation, notable software updates and launches, and a spotlight on <a href="https://readeck.org/?ref=selfh.st">Readeck</a> - a self-hosted read later and bookmarking app.</p> <p>I&#39;m also joined by guest co-host Daniel Brendel, the developer of <a href="https://github.com/danielbrendel/hortusfox-web">HortusFox</a>, in this week&#39;s YouTube and podcast recap.</p> <p>Thanks, and as usual, feel free to reach out with feedback!</p> <hr/> <p><a href="https://selfh.st/newsletter/2024-11-29/?ref=reddit">Newsletter</a> | <a href="https://youtu.be/sHzCiRmYMd8">Watch on YouTube</a> | <a href="https://rss.com/podcasts/theselfhostcast/1776840">Listen via Podcast</a></p> </div><

## have some websites that i host in local network - easier way than access through <ip.adress>:port?
 - [https://www.reddit.com/r/selfhosted/comments/1h2l6oh/have_some_websites_that_i_host_in_local_network](https://www.reddit.com/r/selfhosted/comments/1h2l6oh/have_some_websites_that_i_host_in_local_network)
 - RSS feed: $source
 - date published: 2024-11-29T12:55:11+00:00

<!-- SC_OFF --><div class="md"><p>Hey, selfhosting noob here.</p> <p>I made some small websites for different things (like a dart tourney, minecraft blackboard, todo lists etc) and i am hosting these via 192.168.x.xxx:port (8080, 5000 etc)</p> <p>For me, accessing the sites is easy, its just my mom and friends that have some problems.</p> <p>what would be a easy way to display the websites in my local network?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mynotell"> /u/mynotell </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2l6oh/have_some_websites_that_i_host_in_local_network/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2l6oh/have_some_websites_that_i_host_in_local_network/">[comments]</a></span>

## How would you setup these disks for a home server?
 - [https://www.reddit.com/r/selfhosted/comments/1h2l15e/how_would_you_setup_these_disks_for_a_home_server](https://www.reddit.com/r/selfhosted/comments/1h2l15e/how_would_you_setup_these_disks_for_a_home_server)
 - RSS feed: $source
 - date published: 2024-11-29T12:46:07+00:00

<!-- SC_OFF --><div class="md"><p>i currently have 4x16TB in mdraid with XFS. Just added another 2 16TB i first thought to have like a mirrored/zfs-raidz1 for backups on the main disks.</p> <p>Eitherway im going to reinstall the server and can redo the whole disk layouts, but incertain how i should do with all the disks in a configuration.</p> <p>I already have an off-site backup at hetzner that i backup with borgbackup that is running every night.</p> <p>is it &quot;overkill&quot; to dedicate 2 disks to a seperate server internal backup as a local backup, or should i just incorporate all 6 disks in a z2 raid instead?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FuriousRageSE"> /u/FuriousRageSE </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2l15e/how_would_you_setup_these_disks_for_a_home_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2l15e/how_would_you_setup_these_dis

## Dawarich 0.18.1: November Monthly Update
 - [https://www.reddit.com/r/selfhosted/comments/1h2l0xe/dawarich_0181_november_monthly_update](https://www.reddit.com/r/selfhosted/comments/1h2l0xe/dawarich_0181_november_monthly_update)
 - RSS feed: $source
 - date published: 2024-11-29T12:45:45+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1h2l0xe/dawarich_0181_november_monthly_update/"> <img src="https://external-preview.redd.it/r0oIadYSDEyVMvow54y0YHI_BoZHHswfk12J77C8yqs.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=14149bdbf9ae2240f86a2ed1a294e6236bbbd131" alt="Dawarich 0.18.1: November Monthly Update" title="Dawarich 0.18.1: November Monthly Update" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello there, good people of <a href="/r/selfhosted">r/selfhosted</a>! Another month came to an end, and I&#39;m here again to bring you the most recent news about <a href="https://github.com/Freika/dawarich">Dawarich</a>, your favorite Google Location History alternative, self-hostable.</p> <p>November turned out to be pretty good for Dawarich since I had a lot more free time on my hands, being laid off in mid-October. So, let&#39;s get to the update!</p> <h1>The Immich Photos</h1> <p>What? Yes! Dawarich now can not only get geodata from the phot

## Nginx Proxy Manager not redirecting to service
 - [https://www.reddit.com/r/selfhosted/comments/1h2kf1p/nginx_proxy_manager_not_redirecting_to_service](https://www.reddit.com/r/selfhosted/comments/1h2kf1p/nginx_proxy_manager_not_redirecting_to_service)
 - RSS feed: $source
 - date published: 2024-11-29T12:09:43+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1h2kf1p/nginx_proxy_manager_not_redirecting_to_service/"> <img src="https://b.thumbs.redditmedia.com/DhbJpQjmaRulIihxLGyvBgImAYJrMaB71e65aPuWHCQ.jpg" alt="Nginx Proxy Manager not redirecting to service" title="Nginx Proxy Manager not redirecting to service" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi all!</p> <p>As many others I am having issues with setting Nginx Proxy Manager and looking for some help after fighting with this for several days.</p> <p>I have a service running at <a href="http://192.168.0.106">192.168.0.106</a> at port 8000 that I can access via via the IP address from any computer in the network. However, when trying to access it via NPM, it is unable to access it:</p> <p>Directly typing the IP+port from another computer:</p> <p><a href="https://preview.redd.it/goywuh4lxt3e1.png?width=587&amp;format=png&amp;auto=webp&amp;s=0c190e1e09169a95cf5cc76fd24ac0fa3a8a086a">https://preview.redd.

## Self-hosted File-Sharing/Anonfiles alternative
 - [https://www.reddit.com/r/selfhosted/comments/1h2k8os/selfhosted_filesharinganonfiles_alternative](https://www.reddit.com/r/selfhosted/comments/1h2k8os/selfhosted_filesharinganonfiles_alternative)
 - RSS feed: $source
 - date published: 2024-11-29T11:58:53+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1h2k8os/selfhosted_filesharinganonfiles_alternative/"> <img src="https://external-preview.redd.it/rH01S3pHygW0v8s-sM0vQTIH1oTMcoYptT1SwWrIEBc.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=1b79a577cdacd9dbf75ee911b60529e74463b9f2" alt="Self-hosted File-Sharing/Anonfiles alternative" title="Self-hosted File-Sharing/Anonfiles alternative" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>After AnonFiles shut down due to the overwhelming abuse, I struggled to find a good alternative for file sharing. Existing websites didn&#39;t meet my needs, were buggy or were filled with ads, so I made QuickDrop, a self-hosted app that lets you upload files without an account, generate download links, and manage file availability. It also offers optional password protection and file encryption on the password-protected files to ensure privacy even to the one hosting the app.</p> <p>It is still a work in progress. I&#39;m plann

## Questions about Tailscale
 - [https://www.reddit.com/r/selfhosted/comments/1h2k0ht/questions_about_tailscale](https://www.reddit.com/r/selfhosted/comments/1h2k0ht/questions_about_tailscale)
 - RSS feed: $source
 - date published: 2024-11-29T11:43:13+00:00

<!-- SC_OFF --><div class="md"><p>Firstly, I have two devices on the same LAN both advertising routes and acting as exit nodes, in the logs I see this message:</p> <p><code>Some peers are advertising routes but --accept-routes is false</code></p> <p>It&#39;s working in its current state but what are the implications of accepting routes?</p> <p>Secondaly, I’m using Homepage with a Tailscale widget, but the API key expires every 90 days, requiring me to regenerate it. Is there a way to bypass this limitation?</p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Zestyclose_Car1088"> /u/Zestyclose_Car1088 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2k0ht/questions_about_tailscale/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2k0ht/questions_about_tailscale/">[comments]</a></span>

## Advice on storage. Clustered, or NAS/DAS?
 - [https://www.reddit.com/r/selfhosted/comments/1h2k03r/advice_on_storage_clustered_or_nasdas](https://www.reddit.com/r/selfhosted/comments/1h2k03r/advice_on_storage_clustered_or_nasdas)
 - RSS feed: $source
 - date published: 2024-11-29T11:42:28+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for the best way to share storage between nodes and looking for advice especially with it being black friday. </p> <p>I currently have 5 nodes but one is a wildcard. </p> <p>3x Lenovo m920Q 64GB RAM, 2TB NVM-e in the office<br/> 1x Lenovo m710Q 64GB RAM, 1TB NVM-e at home<br/> 1x Dell server with 8TB HDD RAID 0 (I know) in a different country with OK internet but not great (around 50Mb down) </p> <p>I also have a handful (6 I think) of raspberry pi 4 or 5 which are currently only running as Tailscale exit nodes. </p> <p>The Lenovos will have a 1TB HDD inside as soon as a friend gives me the drives, but they&#39;ll be old so not sure how long they&#39;ll last. </p> <p>I want to host apps that need around 20GB RAM/500GB disk, plus MySQL slaves taking currently around 500GB (but only for backups so they don&#39;t need to be amazingly fast storage). </p> <p>On top of that I&#39;m looking to pull in probably 2TB of backups from S3, maybe 4

## Using APOD as background in homepage
 - [https://www.reddit.com/r/selfhosted/comments/1h2jn3k/using_apod_as_background_in_homepage](https://www.reddit.com/r/selfhosted/comments/1h2jn3k/using_apod_as_background_in_homepage)
 - RSS feed: $source
 - date published: 2024-11-29T11:17:43+00:00

<!-- SC_OFF --><div class="md"><p>Hi Selfhosters!</p> <p>So I wanted to start playing arround with my dashboard collecting all my selfhosted items and some widgets and I&#39;ve decided to use homepage for this purpose. Naturally as things always do, it got a bit more complicated from the start.</p> <p>What I&#39;d love to have is NASA&#39;s astronomy picture of the day used as a background image but naturally updated on a daily basis. </p> <p>I&#39;ve found multiple ways of doing this, even got to creating a docker within my Unraid setup which gives me the APOD whenever I want but I can&#39;t manage to save the image to one jpg file in my NAS so it can be used as background across multiple services (so not even just homepage but potentially also others if they support blurring of cards etc etc , like homeassistant for example).</p> <p>This is a way to do it in powershell but I don&#39;t think it&#39;s what I want - I&#39;d rather just have it stored locally instead and potentially do

## What are your thoughts on Campfire?
 - [https://www.reddit.com/r/selfhosted/comments/1h2j6rk/what_are_your_thoughts_on_campfire](https://www.reddit.com/r/selfhosted/comments/1h2j6rk/what_are_your_thoughts_on_campfire)
 - RSS feed: $source
 - date published: 2024-11-29T10:45:57+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m starting to research what group chat app to host and I&#39;d like to get your opinion on Campfire and how it you think it compares to other group chat systems (e.g the <a href="http://Matrix.org">Matrix.org</a> stuff).</p> <p>To those unfamiliar, Campfire is a self-hostable group chat app <a href="https://once.com/campfire">https://once.com/campfire</a> . </p> <p>From the official website, it has the following characteristics:</p> <ul> <li>it costs 300$ which are paid once for a lifetime license for 1 domain</li> <li>supported from a real company which a good reputation</li> <li>provides all the privacy/control benefits of self hosting - all the data is stored and managed locally</li> <li>has mobile apps, PWA and bot support</li> <li>don&#39;t think it has support for video and audio calls</li> </ul> <p>For me personally, what I do care about is maturity of code, feature completeness and security. I don&#39;t care about federation and/or conn

## Streamsphere: yt-dlp front end and media library!
 - [https://www.reddit.com/r/selfhosted/comments/1h2iwsu/streamsphere_ytdlp_front_end_and_media_library](https://www.reddit.com/r/selfhosted/comments/1h2iwsu/streamsphere_ytdlp_front_end_and_media_library)
 - RSS feed: $source
 - date published: 2024-11-29T10:25:50+00:00

<!-- SC_OFF --><div class="md"><p>Hi Guys!</p> <p>I&#39;ve developed a web-app Streamsphere which helps download from yt-dlp and manages/server your media; it&#39;s fully self-hostable. Its super easy to setup with docker compose which is available on github!</p> <p>Features</p> <p>📺 Download Channels from supported domains<br/> 📼 Downlad &amp; update playlists from supported domains<br/> 📽️ Download Videos from supported domains<br/> 🔍 Search and play videos by title<br/> 👾 UI to navigate your media library<br/> 📥 Download media content that has been added to streamsphere through browser<br/> ✨ View tags, categories, size of media files and other details for the downloaded content<br/> 🎴 Light &amp; Dark theme support</p> <p>The technology stack is Angular + Golang. The effort is to have as low resource utilization as possible. <a href="https://github.com/rs-anantmishra/streamsphere">https://github.com/rs-anantmishra/streamsphere</a></p> <p>I&#39;ve published a pre-release v0.1.11, 

## Hosting SHlink
 - [https://www.reddit.com/r/selfhosted/comments/1h2iuaj/hosting_shlink](https://www.reddit.com/r/selfhosted/comments/1h2iuaj/hosting_shlink)
 - RSS feed: $source
 - date published: 2024-11-29T10:20:48+00:00

<!-- SC_OFF --><div class="md"><p>Hello! Im trying to selfhost shlink on shlink.dnlweijers.nl. the GUI is accessible but shlink container keeps restarting so I cant connect. Im hosting it on my 192.168.2.175 server, using npm to put it on shlink.dnlweijers.nl (http://shlink-web-client:80). Im using my dns server to put it on the .dnlweijers.nl zone and using cloudflare tunnel to tunnel it, but thats not important. My docker-compose.yml is: <a href="https://bin.dnlweijers.nl/upload/e5lWRd">https://bin.dnlweijers.nl/upload/e5lWRd</a>.</p> <p>My shlink log is <a href="https://bin.dnlweijers.nl/upload/b257Pa">https://bin.dnlweijers.nl/upload/b257Pa</a>, logs from web-client and database look correctly.</p> <p>Db: <a href="https://bin.dnlweijers.nl/upload/e0OYGd">https://bin.dnlweijers.nl/upload/e0OYGd</a></p> <p>Client: <a href="https://bin.dnlweijers.nl/upload/aKxonb">https://bin.dnlweijers.nl/upload/aKxonb</a></p> <p>does anyone have a idea?</p> </div><!-- SC_ON --> &#32; submitted by 

## Looking for a Simple Order Management App for Small Businesses - Any Recommendations?
 - [https://www.reddit.com/r/selfhosted/comments/1h2ispb/looking_for_a_simple_order_management_app_for](https://www.reddit.com/r/selfhosted/comments/1h2ispb/looking_for_a_simple_order_management_app_for)
 - RSS feed: $source
 - date published: 2024-11-29T10:17:37+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I’m a software developer, and my sister runs a small business where most of her orders come through WhatsApp DMs (less than 100 orders per month). Right now, she’s using an Excel sheet to track everything – customer names, addresses, order details, etc.</p> <p>I’m looking for a <strong>simple app</strong> that can help manage orders like:</p> <ul> <li>Sorting orders by product, date, or status.</li> <li>Keeping track of shipment status.</li> <li>Storing customer info in an easy-to-use way.</li> </ul> <p>The app would need to be <strong>very simple</strong>, so anyone – even someone in their 40s or 50s who runs an Instagram store – could use it without any issues.</p> <p>As a developer, I’m thinking about creating an app like this for small business owners. Something <strong>easy to use</strong> and focused on managing social media orders and shipping.</p> <p><strong>Do you think this is a good idea?</strong> Or is there already an app 

## Web analytics you can actually self host
 - [https://www.reddit.com/r/selfhosted/comments/1h2imd9/web_analytics_you_can_actually_self_host](https://www.reddit.com/r/selfhosted/comments/1h2imd9/web_analytics_you_can_actually_self_host)
 - RSS feed: $source
 - date published: 2024-11-29T10:04:35+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone. I had a very (very) hard time self-hosting web analytics (Umami, Fathom, Plausible) due to their complicated setups. They tend to have many services + Clickhouse all working together and very little incentive to make it easy to self host since they sell managed hosting. </p> <p>So I decided to create an open-source, simple web analytics platform that&#39;s actually easy to self host using Django and SQLite. Check it out here: <a href="https://github.com/HermanMartinus/bearlytics">https://github.com/HermanMartinus/bearlytics</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Herman_Martinus"> /u/Herman_Martinus </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2imd9/web_analytics_you_can_actually_self_host/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2imd9/web_analytics_you_can_actually_self_host/">[comments]</a></span>

## Discovering AI for Domain Names: Have You Tried It?
 - [https://www.reddit.com/r/selfhosted/comments/1h2i3km/discovering_ai_for_domain_names_have_you_tried_it](https://www.reddit.com/r/selfhosted/comments/1h2i3km/discovering_ai_for_domain_names_have_you_tried_it)
 - RSS feed: $source
 - date published: 2024-11-29T09:26:16+00:00

<!-- SC_OFF --><div class="md"><p>[ Removed by Reddit on account of violating the <a href="/help/contentpolicy">content policy</a>. ]</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/georgecristian12"> /u/georgecristian12 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2i3km/discovering_ai_for_domain_names_have_you_tried_it/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2i3km/discovering_ai_for_domain_names_have_you_tried_it/">[comments]</a></span>

## Selfhosted solution for tracking vehicle data
 - [https://www.reddit.com/r/selfhosted/comments/1h2i20m/selfhosted_solution_for_tracking_vehicle_data](https://www.reddit.com/r/selfhosted/comments/1h2i20m/selfhosted_solution_for_tracking_vehicle_data)
 - RSS feed: $source
 - date published: 2024-11-29T09:23:15+00:00

<!-- SC_OFF --><div class="md"><p>Hi, </p> <p>Does someone know if some solution for tracking vehicle maintenance info exists? All manual since I have an old car that doesn&#39;t connect to anything.</p> <p>But something that could track for example oil changes, work done on the car, refills, etc, maybe with a nic-ish UI would be appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Enewan"> /u/Enewan </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2i20m/selfhosted_solution_for_tracking_vehicle_data/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2i20m/selfhosted_solution_for_tracking_vehicle_data/">[comments]</a></span>

## Ente self-hosted - Machine Learning & People across devices
 - [https://www.reddit.com/r/selfhosted/comments/1h2hywp/ente_selfhosted_machine_learning_people_across](https://www.reddit.com/r/selfhosted/comments/1h2hywp/ente_selfhosted_machine_learning_people_across)
 - RSS feed: $source
 - date published: 2024-11-29T09:17:08+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I already tried to get some feedback on the enteio feed, but without any success...<br/> Here is my original Post:<br/> <a href="https://www.reddit.com/r/enteio/comments/1h0yyhr/ente_selfhosted_machine_learning_people_across/">https://www.reddit.com/r/enteio/comments/1h0yyhr/ente_selfhosted_machine_learning_people_across/</a></p> <p>TL;DR: I have installed the self-hosted docker version of ente, and also have external access via Cloudflare and NPM (Nginx Proxy Manager).</p> <p>This is working well so far, and my primary device to upload pictures is my Pixel Phone.</p> <p>I can also authenticate on other devices, and I have the App installed on my android tablet, as well as my Mac and Linux laptop.</p> <p>Bidirectional sync (upload/download) is working as expected.</p> <p>Machine Learning and People recognition is not working as I would expect and I was wondering if these features are actually available on a self-hosted instance, or if I

## Running docker desktop looking for advice
 - [https://www.reddit.com/r/selfhosted/comments/1h2hw36/running_docker_desktop_looking_for_advice](https://www.reddit.com/r/selfhosted/comments/1h2hw36/running_docker_desktop_looking_for_advice)
 - RSS feed: $source
 - date published: 2024-11-29T09:11:32+00:00

<!-- SC_OFF --><div class="md"><p>Okay so I&#39;ve recently switched industries and have a bit more free time on my hands. Having run a plex server since 2012 or so I decided to see if and what ways I could improve upon it. I&#39;ve always been the family tech guy but have always just told them in the end I am just decent at using Google. Spending alot of my time on the plex sub reddit over the years I&#39;d often seen people post about docker and containers and it sounds foreign and not being too familiar with Linux I pretty much never looked into it much.</p> <p>I&#39;ve always run my plex server on windows. With the advent of chat gpt I&#39;ve been using it a ton to help me write html code for some fun personal projects. At first I made a custom dashboard to monitor status of my services and a few websites. The new o1 model is pretty powerful and can whip stuff together pretty easily. So I decided I&#39;d give it try to help me setup my server using docker. Although I copy and pas

## Is there an easier way to renew certificates?
 - [https://www.reddit.com/r/selfhosted/comments/1h2hu9d/is_there_an_easier_way_to_renew_certificates](https://www.reddit.com/r/selfhosted/comments/1h2hu9d/is_there_an_easier_way_to_renew_certificates)
 - RSS feed: $source
 - date published: 2024-11-29T09:07:51+00:00

<!-- SC_OFF --><div class="md"><p>Currently hosting a few sites using cloudflare tunnel. Gotta tell you, setting it up on Kubuntu OS really did it for me since I had no idea how difficult it was moving from a Win OS. </p> <p>I set it up a month or two ago and never touched it. Now i got the below email;</p> <p>Let&#39;s Encrypt certificate expiration notice for domain “Mydomain.com”</p> <p>Hello,</p> <p>Your certificate (or certificates) for the names listed below will expire in 19 days (on 2024-11-29). Please make sure to renew your certificate before then, or visitors to your web site will encounter errors.</p> <p>We recommend renewing certificates automatically when they have a third of their total lifetime left. For Let&#39;s Encrypt&#39;s current 90-day certificates, that means renewing 30 days before expiration.</p> <p>My concern is, how do I renew this? Is there an easy way to do this for a beginner like myself? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https

## Local Domains and Certificates
 - [https://www.reddit.com/r/selfhosted/comments/1h2h7hx/local_domains_and_certificates](https://www.reddit.com/r/selfhosted/comments/1h2h7hx/local_domains_and_certificates)
 - RSS feed: $source
 - date published: 2024-11-29T08:21:45+00:00

<!-- SC_OFF --><div class="md"><p>Hello to everyone</p> <p>I don’t expose any of my services to internet. I’m using Nginx Proxy Manager for getting Let’s Encrypt certificates for my domain through DNS 01 challenge just for 2 services. Nextcloud (because, without https, iOS will refuse to sync Contacts-Calendars) and Vaultwarden.</p> <p>I don’t want to continue paying for domain for just two services. I’ve tried duckdns but there were a lot of times that duckdns was down. </p> <p>I want to use the most simple way of getting https for these two services with local domain. As I understand, I’m gonna use pihole for the local domain and something like caddy for getting the self signed certificates that I will use on all my devices. What is the most easy way (no time at all with work and family) to do this? And how often will the certificates expire? </p> <p>Thank you very much for your help. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Substantia

## Pre-built script or docker container to put server behind HTTPS and retrieve a Let’s Encrypt cert
 - [https://www.reddit.com/r/selfhosted/comments/1h2g2bs/prebuilt_script_or_docker_container_to_put_server](https://www.reddit.com/r/selfhosted/comments/1h2g2bs/prebuilt_script_or_docker_container_to_put_server)
 - RSS feed: $source
 - date published: 2024-11-29T07:00:19+00:00

<!-- SC_OFF --><div class="md"><p>I’m self-hosting a server for development at <code>0.0.0.0:80</code> and I’m going to set up nginx with a Let’s Encrypt certificate to secure it. I’ve done it before a few times but I really don’t feel like re-looking-up all the packages and commands I need. I’m sure this is done thousands and thousands of times, so there a script online that handles this for you? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dannyfrfr"> /u/dannyfrfr </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2g2bs/prebuilt_script_or_docker_container_to_put_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2g2bs/prebuilt_script_or_docker_container_to_put_server/">[comments]</a></span>

## Mini pc with one SSD
 - [https://www.reddit.com/r/selfhosted/comments/1h2fzo7/mini_pc_with_one_ssd](https://www.reddit.com/r/selfhosted/comments/1h2fzo7/mini_pc_with_one_ssd)
 - RSS feed: $source
 - date published: 2024-11-29T06:55:18+00:00

<!-- SC_OFF --><div class="md"><p>I have a gmktec kb3 lying around, I planning of buying a 1tb sata SSD to dip my toes in DIY NAS. What software should I use, that thing doesn&#39;t have LAN port 💀</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tibodak"> /u/tibodak </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2fzo7/mini_pc_with_one_ssd/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2fzo7/mini_pc_with_one_ssd/">[comments]</a></span>

## Mac Mini M4 or Arc A580 for Jellyfin?
 - [https://www.reddit.com/r/selfhosted/comments/1h2frd5/mac_mini_m4_or_arc_a580_for_jellyfin](https://www.reddit.com/r/selfhosted/comments/1h2frd5/mac_mini_m4_or_arc_a580_for_jellyfin)
 - RSS feed: $source
 - date published: 2024-11-29T06:39:22+00:00

<!-- SC_OFF --><div class="md"><p>I already have the Mac mini M4. End of the thread.</p> <p>No, but seriously, I was doing some more research and searching... would it be safer to run a server with the Arc A580 (with 5800x3D) on Jellyfin, or should I stick with the Mac mini M4?</p> <p>I was learning more about Proxmox, and heard that MacOS isn&#39;t the best for *arr stacks and such due to architecture and Docker itself -- unless I&#39;m just reading wrong; because I thought Docker would virtualize that? Unless it&#39;s using Rosetta.</p> <p>Anyways, with that said, I was just wondering if I could like... use *arr stack on my 5800x3D NAS setup, and then just have Jellyfin running on my Mac. Would that be possible? I understand how different VMs and containers work with like Proxmox, but not sure how different computers would work.</p> <p>Or is it all file based and can I just sync them [*arrs] anyways regardless of where they&#39;re at?</p> </div><!-- SC_ON --> &#32; submitted by &#3

## Tactical RMM: It isn't free (I have no one to blame but myself), also its sketchy. Alternatives?
 - [https://www.reddit.com/r/selfhosted/comments/1h2eb36/tactical_rmm_it_isnt_free_i_have_no_one_to_blame](https://www.reddit.com/r/selfhosted/comments/1h2eb36/tactical_rmm_it_isnt_free_i_have_no_one_to_blame)
 - RSS feed: $source
 - date published: 2024-11-29T05:07:59+00:00

<!-- SC_OFF --><div class="md"><p>Yeah I guess fuck me for not reading the documentation before deploying it.</p> <p>Tactical RMM markets itself as a free RMM but I&#39;d argue that is misleading, at best. To deploy the Linux agent they &quot;need&quot;to be code signed (can&#39;t I just deploy it unsigned?) . That costs Tactical money, which I get, no such thing as a free lunch. So to cover those costs Tactical requires you to be a sponsor at the low, low price of <em>$660 a year</em>. $960 if I want reporting, which, like, duh.</p> <p>Add to that, their codebase isn&#39;t fully open source on Github, and therefore can&#39;t be forked. To make matters worse, it did, at one point, (allegedly) include a crypto miner</p> <pre><code>wget https://files.tacticalrmm.io/winagent-v1.98.61.exe innoextract -d out winagent-v1.98.61.exe binwalk -e tacticalrmm.exe strings 5A6B6C | grep &#39;Monero&#39; # (or open up the file in a text editor) </code></pre> <p>So, <a href="/r/selfhosted">/r/selfho

## Reusable Polling Form for Voting on Game Selection
 - [https://www.reddit.com/r/selfhosted/comments/1h2dnpl/reusable_polling_form_for_voting_on_game_selection](https://www.reddit.com/r/selfhosted/comments/1h2dnpl/reusable_polling_form_for_voting_on_game_selection)
 - RSS feed: $source
 - date published: 2024-11-29T04:28:49+00:00

<!-- SC_OFF --><div class="md"><p>I have a board game night weekly with friends. We have a lot of games, so we vote on games each week. Each person gets 3 votes, and the winning game is what we play. The game options are always the same X games. Each week its a new vote, but the form is the same. We obviously needs to be able to see the winning results in a &quot;live poll&quot; format, as often someone will vote for a game and thats what everyone else votes for as well &quot;oh yeah, we would like to play that&quot;.</p> <p>I looked all over selfhosted, and most of the solutions out there are too complex, or aimed at event management with scheduling, etc.</p> <p>Anyone know of a self hosted app to solve this need? Basically sping up[ a new copy of a voting form weekly, send to people to gather votes, see results, then abandon it.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Imburr"> /u/Imburr </a> <br/> <span><a href="https://www.reddit.com/

## Gluetun vs Qbittorrent-vpn
 - [https://www.reddit.com/r/selfhosted/comments/1h2d9bu/gluetun_vs_qbittorrentvpn](https://www.reddit.com/r/selfhosted/comments/1h2d9bu/gluetun_vs_qbittorrentvpn)
 - RSS feed: $source
 - date published: 2024-11-29T04:04:26+00:00

<!-- SC_OFF --><div class="md"><p>Is there any benefit to using the qbittorrent-vpn instead of using the normal qbittorrent container and running it behind a gluetun container?</p> <p>I&#39;m asking specifically because, while also running prowlarr, i&#39;d like to be able to select which indexers connect through the vpn, since apparently some indexers give you trouble for connecting to them through a VPN, but since my ISP blocks some of them i&#39;d appreciate having the ability to route those through a VPN.</p> <p>Edit: Apparently using a VPN can also give you some trouble with metadata?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DominusMindweaver"> /u/DominusMindweaver </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2d9bu/gluetun_vs_qbittorrentvpn/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2d9bu/gluetun_vs_qbittorrentvpn/">[comments]</a></span>

## Good File Sharing for my personal use
 - [https://www.reddit.com/r/selfhosted/comments/1h2cfe0/good_file_sharing_for_my_personal_use](https://www.reddit.com/r/selfhosted/comments/1h2cfe0/good_file_sharing_for_my_personal_use)
 - RSS feed: $source
 - date published: 2024-11-29T03:13:56+00:00

<!-- SC_OFF --><div class="md"><p>I have NAS and I want to use it as a more modern file sharing. I don’t really like Nextcloud I want something lightweight similar with dropbox maybe</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/anonuser-al"> /u/anonuser-al </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2cfe0/good_file_sharing_for_my_personal_use/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h2cfe0/good_file_sharing_for_my_personal_use/">[comments]</a></span>

## Subdomain beside Domain for email
 - [https://www.reddit.com/r/selfhosted/comments/1h29uvb/subdomain_beside_domain_for_email](https://www.reddit.com/r/selfhosted/comments/1h29uvb/subdomain_beside_domain_for_email)
 - RSS feed: $source
 - date published: 2024-11-29T00:44:17+00:00

<!-- SC_OFF --><div class="md"><p>When using a sub-domain as an email account, it won&#39;t conflict with the main domain. I ask because I want the two to be treated separately.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/One_Scholar1355"> /u/One_Scholar1355 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1h29uvb/subdomain_beside_domain_for_email/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1h29uvb/subdomain_beside_domain_for_email/">[comments]</a></span>

## Help with Crowdsec
 - [https://www.reddit.com/r/selfhosted/comments/1h29ung/help_with_crowdsec](https://www.reddit.com/r/selfhosted/comments/1h29ung/help_with_crowdsec)
 - RSS feed: $source
 - date published: 2024-11-29T00:43:56+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1h29ung/help_with_crowdsec/"> <img src="https://b.thumbs.redditmedia.com/xoz5CHF_qqi4kSx2cslmEPvKJ8-32yOsCy2zMLPnpMY.jpg" alt="Help with Crowdsec" title="Help with Crowdsec" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>My nginx logs are not showing even though I added it.</p> <p><code>sparky@sparkyubuntu:/etc/crowdsec$ sudo cscli metrics show engine</code></p> <p><a href="https://preview.redd.it/etl88iz6mq3e1.png?width=1870&amp;format=png&amp;auto=webp&amp;s=511046d199e992eb2a791dc8f21e9c88a2367131">https://preview.redd.it/etl88iz6mq3e1.png?width=1870&amp;format=png&amp;auto=webp&amp;s=511046d199e992eb2a791dc8f21e9c88a2367131</a></p> <p>my acquis.yaml file is</p> <p><a href="https://preview.redd.it/erj20foamq3e1.png?width=1000&amp;format=png&amp;auto=webp&amp;s=1fff2d9a6d1fc1356376f25c416f99c32537958c">https://preview.redd.it/erj20foamq3e1.png?width=1000&amp;format=png&amp;auto=webp&amp;s=1fff2d9a6d1fc13563

## I found my favorite subreddit
 - [https://www.reddit.com/r/selfhosted/comments/1h29bfz/i_found_my_favorite_subreddit](https://www.reddit.com/r/selfhosted/comments/1h29bfz/i_found_my_favorite_subreddit)
 - RSS feed: $source
 - date published: 2024-11-29T00:13:17+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been following this subreddit for a while and finally decided to share my setup. I usually get my hands on free hardware, so here’s what I’m working with:</p> <h1>Hardware:</h1> <ul> <li><strong>HPE Server</strong> running Proxmox.</li> <li><strong>Debian VM</strong> (with Webmin access) for Docker.</li> <li><strong>Home Assistant LXC</strong>.</li> <li><strong>2x 8-bay NAS devices</strong>: <ul> <li><strong>NAS 1</strong>: Proxmox network storage, Docker containers, Veeam backup repo, and media backups.</li> <li><strong>NAS 2</strong>: Media storage and Docker container backups (synced nightly via rsync).</li> </ul></li> </ul> <h1>Docker Containers:</h1> <ul> <li><strong>Twingate connector</strong></li> <li><strong>Glances</strong></li> <li><strong>Portainer</strong></li> <li><strong>AdGuard DNS filtering</strong> (great for blocking mobile game ads!)</li> <li><strong>Nginx Reverse Proxy Manager</strong> <ul> <li>Love the interface for enab

