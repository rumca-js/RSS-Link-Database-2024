# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Proxmox Datacenter Manager
 - [https://www.reddit.com/r/selfhosted/comments/1hi6dly/proxmox_datacenter_manager](https://www.reddit.com/r/selfhosted/comments/1hi6dly/proxmox_datacenter_manager)
 - RSS feed: $source
 - date published: 2024-12-19T23:35:54+00:00

<!-- SC_OFF --><div class="md"><p>Can&#39;t see anything when search in reference to this but I thought it was worth mentioning: <a href="https://pve.proxmox.com/wiki/Proxmox_Datacenter_Manager_Roadmap">https://pve.proxmox.com/wiki/Proxmox_Datacenter_Manager_Roadmap</a></p> <p>Looks like we will be able to manage multiple hosts without the clustering headache.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/agent-squirrel"> /u/agent-squirrel </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi6dly/proxmox_datacenter_manager/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi6dly/proxmox_datacenter_manager/">[comments]</a></span>

## dumbproxy - simple, scriptable, secure forward proxy server
 - [https://www.reddit.com/r/selfhosted/comments/1hi6a26/dumbproxy_simple_scriptable_secure_forward_proxy](https://www.reddit.com/r/selfhosted/comments/1hi6a26/dumbproxy_simple_scriptable_secure_forward_proxy)
 - RSS feed: $source
 - date published: 2024-12-19T23:31:05+00:00

<!-- SC_OFF --><div class="md"><p>Let me present <a href="https://github.com/SenseUnit/dumbproxy?tab=readme-ov-file#dumbproxy">dumbproxy</a> project, a nice HTTPS proxy to selfhost. It was already announced on reddit and elsewhere couple of years ago, but it grew bigger since then.</p> <p>Back then we had just HTTP(S) forward proxy with automatic cert management and basic auth functions. But today a lot has changed.</p> <p>New features developed recently:</p> <ul> <li>HMAC-based basic auth - useful to provide authentication to a fleet of proxy servers without need for them to contact central authority each time to verify credentials.</li> <li>Optional DNS cache.</li> <li>Per-user bandwidth limits.</li> <li>Scripting with JS: <ul> <li>Access filters - allows complex request filtering. Usecases may vary from just complex ACL thing to implementation of something like adblockers.</li> <li>Dynamic upstream proxy selection - there is also a lot of interesting usecases varying from simplest

## Project ideas
 - [https://www.reddit.com/r/selfhosted/comments/1hi5l1a/project_ideas](https://www.reddit.com/r/selfhosted/comments/1hi5l1a/project_ideas)
 - RSS feed: $source
 - date published: 2024-12-19T22:57:15+00:00

<!-- SC_OFF --><div class="md"><p>Hello <a href="/r/selfhosted">r/selfhosted</a>. I&#39;m a part of this community for around 3 years now (though I joined it pretty recently). I thought I might give a try creating my own selfhosted software but I can&#39;t think of anything. I played around privately with Python and Flask for some time now, and I think I&#39;m capable of creating something that will be actually useful for someone. So my question is: <strong>is there any specific selfhosted software that you want to have but there just isn&#39;t one yet, or it&#39;s not right for you?</strong></p> <p>I want to create a project that I can actually develop and update for more than a couple days (best if it would be months or even years if i&#39;ll have time for that long), and it shouldn&#39;t be something as complex as Nextcloud or Gitea/Forgejo (at least in the beginning), probably something more like Uptime Kuma or a metasearch engine.</p> <p>I&#39;m looking forward to your ideas! </

## What is the current state of Matter/Thread for self hosted?
 - [https://www.reddit.com/r/selfhosted/comments/1hi5i0z/what_is_the_current_state_of_matterthread_for](https://www.reddit.com/r/selfhosted/comments/1hi5i0z/what_is_the_current_state_of_matterthread_for)
 - RSS feed: $source
 - date published: 2024-12-19T22:53:22+00:00

<!-- SC_OFF --><div class="md"><p>Hi Everyone,</p> <p>Just wondering what the general consensus was here for using Matter. As someone that uses Zigbee2MQTT/NodeRed/Home Assistant is my self hosted move into Matter and Thread to just use Home Assistant. </p> <p>From my reading Matter and Thread are pretty tightly integrated so no need any more for MQTT. </p> <p>I just see a lot of posts (in other subreddits) about just using Google/Amazon/Apple for Matter devices. Being keen on self hosting and not reliant on cloud I would love your opinions on all things Matter self hosted</p> <p>PS. Worst names to search on. Every time I try and do a bit of research I get results like &quot;It doesn&#39;t matter what you say in this thread I think....&quot; or some combination of something that doesn&#39;t matter or a reddit thread</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/alexinthis"> /u/alexinthis </a> <br/> <span><a href="https://www.reddit.com/r/selfh

## Anyone using Kamal + Next.js + Prisma?
 - [https://www.reddit.com/r/selfhosted/comments/1hi4hri/anyone_using_kamal_nextjs_prisma](https://www.reddit.com/r/selfhosted/comments/1hi4hri/anyone_using_kamal_nextjs_prisma)
 - RSS feed: $source
 - date published: 2024-12-19T22:07:25+00:00

<!-- SC_OFF --><div class="md"><p>I spent a day on this... for some prisma can&#39;t reach database</p> <p>Running docker logs &lt;container-id&gt; I get</p> <pre><code>Can&#39;t reach database server at `45.88.76.97:5432` Please make sure your database server is running at `45.88.76.97:5432`. at async n.revalidate (.next/server/app/page.js:3:6168) at async (.next/server/chunks/107.js:1:7462) at async b (.next/server/app/page.js:3:1885) { clientVersion: &#39;6.1.0&#39;, errorCode: undefined, digest: &#39;2951717194&#39; } </code></pre> <p>I have both next.js and postgres running on the same VPS each with its own container</p> <p>When I deploy the app all is good and the app is running, but at runtime when I ask for a query or revalidate some tag all pages that require prisma go 500 Internal Server Error.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/waelnassaf"> /u/waelnassaf </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/commen

## Tailscale on Workstations
 - [https://www.reddit.com/r/selfhosted/comments/1hi4cef/tailscale_on_workstations](https://www.reddit.com/r/selfhosted/comments/1hi4cef/tailscale_on_workstations)
 - RSS feed: $source
 - date published: 2024-12-19T22:00:57+00:00

<!-- SC_OFF --><div class="md"><p>For everyone one recommends Tailscale, what are your recommendations for incorporating it into company owned workstations without admin access? I’m on it all day every day. I like to be able to listen to my podcasts and audiobooks in Audiobookshelf. Maybe even use Overseer every once in awhile is a coworker recommends a show or a movie. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PutridLikeness"> /u/PutridLikeness </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi4cef/tailscale_on_workstations/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi4cef/tailscale_on_workstations/">[comments]</a></span>

## CalDAV ical/ics online calendar sync
 - [https://www.reddit.com/r/selfhosted/comments/1hi3mg6/caldav_icalics_online_calendar_sync](https://www.reddit.com/r/selfhosted/comments/1hi3mg6/caldav_icalics_online_calendar_sync)
 - RSS feed: $source
 - date published: 2024-12-19T21:28:43+00:00

<!-- SC_OFF --><div class="md"><p>Maybe I don&#39;t fully understand how CalDAV works but I was hoping I could get recommendations on a dockerized client that can periodically synchronize ical/ics based online calendars. I currently have radical running as my server. </p> <p>Thanks! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/wetzel402"> /u/wetzel402 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi3mg6/caldav_icalics_online_calendar_sync/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi3mg6/caldav_icalics_online_calendar_sync/">[comments]</a></span>

## Nextcloud "desync" old files on purpose?
 - [https://www.reddit.com/r/selfhosted/comments/1hi3fte/nextcloud_desync_old_files_on_purpose](https://www.reddit.com/r/selfhosted/comments/1hi3fte/nextcloud_desync_old_files_on_purpose)
 - RSS feed: $source
 - date published: 2024-12-19T21:20:41+00:00

<!-- SC_OFF --><div class="md"><p>Hey all,</p> <p>Is there a feature in Nextcloud where you can &quot;desync&quot; old files in a existing synced folder?</p> <p>Let me explain, Lets say you have a server with more storage than your pc.<br/> How would you set it up in such a way that when a storage limit is reached on the client side, that it will delete long unused files from the client and not sync those files to the client again?</p> <p>Or should this all be done manually?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Blunt_Member"> /u/Blunt_Member </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi3fte/nextcloud_desync_old_files_on_purpose/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi3fte/nextcloud_desync_old_files_on_purpose/">[comments]</a></span>

## Self Hosted Time Series Database?
 - [https://www.reddit.com/r/selfhosted/comments/1hi3f6x/self_hosted_time_series_database](https://www.reddit.com/r/selfhosted/comments/1hi3f6x/self_hosted_time_series_database)
 - RSS feed: $source
 - date published: 2024-12-19T21:19:56+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m currently using Azure Data Explorer for some Game Telemetry services, which is nice because it integrates with our serverless backend etc. but simply having the dev tier of cluster on costs $111/mo, without any data in it. </p> <p>Are there any recommendations for time-series databases with decent visualization tools?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RoidsDev"> /u/RoidsDev </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi3f6x/self_hosted_time_series_database/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi3f6x/self_hosted_time_series_database/">[comments]</a></span>

## Automatic music import with betanin + slskd
 - [https://www.reddit.com/r/selfhosted/comments/1hi33sn/automatic_music_import_with_betanin_slskd](https://www.reddit.com/r/selfhosted/comments/1hi33sn/automatic_music_import_with_betanin_slskd)
 - RSS feed: $source
 - date published: 2024-12-19T21:05:53+00:00

<!-- SC_OFF --><div class="md"><p>I have made <a href="https://gist.github.com/pbogre/80656086586c1523c892b7086e3eee4a">a very simple script</a> that connects <a href="https://github.com/slskd/slskd/">slskd</a> (soulseek client) with <a href="https://github.com/sentriz/betanin">betanin</a> (beets frontend), thanks to slskd&#39;s recent update that enables custom scripts on completed downloads.</p> <p>This script makes it so that whenever you finish download a directory of files (which can be an album, collection, compilation, ... whatever from soulseek), a request is automatically sent to betanin to make an attempt to import the new folder.</p> <p>I hope this can be useful to some people :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Camminatore"> /u/Camminatore </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi33sn/automatic_music_import_with_betanin_slskd/">[link]</a></span> &#32; <span><a href="https://www.reddit.c

## Mini PC for Home Server
 - [https://www.reddit.com/r/selfhosted/comments/1hi2f5b/mini_pc_for_home_server](https://www.reddit.com/r/selfhosted/comments/1hi2f5b/mini_pc_for_home_server)
 - RSS feed: $source
 - date published: 2024-12-19T20:35:56+00:00

<!-- SC_OFF --><div class="md"><p>Hi I&#39;m thinking of buying a Mini PC as my Home Server. I was looking into the Dell OptiPlex 3050 Mini(Intel Core i7-6700T 16GB RAM 240GB SSD), but I&#39;m not sure of it. Do you recommend this pc or do you know of any other mini PC that&#39;s better. I would be using it with Ubuntu Server, Docker, Hosting Websites with NGINX for local use, grafana, pi hole, ...</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tech_Dauwt"> /u/tech_Dauwt </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi2f5b/mini_pc_for_home_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi2f5b/mini_pc_for_home_server/">[comments]</a></span>

## Storyteller is on PikaPods!
 - [https://www.reddit.com/r/selfhosted/comments/1hi248t/storyteller_is_on_pikapods](https://www.reddit.com/r/selfhosted/comments/1hi248t/storyteller_is_on_pikapods)
 - RSS feed: $source
 - date published: 2024-12-19T20:22:20+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/scrollin_thru"> /u/scrollin_thru </a> <br/> <span><a href="https://smoores.dev/post/storyteller_is_on_pikapods/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi248t/storyteller_is_on_pikapods/">[comments]</a></span>

## Jellyseerr
 - [https://www.reddit.com/r/selfhosted/comments/1hi1r6t/jellyseerr](https://www.reddit.com/r/selfhosted/comments/1hi1r6t/jellyseerr)
 - RSS feed: $source
 - date published: 2024-12-19T20:06:01+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hi1r6t/jellyseerr/"> <img src="https://b.thumbs.redditmedia.com/y8uY1PUNCe2JpaThSaJg-K83IlFbvIXg8NORNFH61tg.jpg" alt="Jellyseerr" title="Jellyseerr" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Trying to setup Jellyseerr with my Jellyfin server but unable to continue, I never setup an email and currently using Truenas Scale</p> <p><a href="https://preview.redd.it/61sqrkpj3v7e1.png?width=778&amp;format=png&amp;auto=webp&amp;s=9514c18045f4c5763436c2f35509c800fd2f7f6a">https://preview.redd.it/61sqrkpj3v7e1.png?width=778&amp;format=png&amp;auto=webp&amp;s=9514c18045f4c5763436c2f35509c800fd2f7f6a</a></p> <p><a href="https://preview.redd.it/pirsuukl3v7e1.png?width=290&amp;format=png&amp;auto=webp&amp;s=4a4c03bb8d6faf4d12a3abe2f9dc5fe711a66480">This is my Jellyfin IP</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RommelDav"> /u/RommelDav </a> <br/> <span><a href="https:

## Self-hosting a global web application using Nextjs on Hetzner
 - [https://www.reddit.com/r/selfhosted/comments/1hi1izn/selfhosting_a_global_web_application_using_nextjs](https://www.reddit.com/r/selfhosted/comments/1hi1izn/selfhosting_a_global_web_application_using_nextjs)
 - RSS feed: $source
 - date published: 2024-12-19T19:55:55+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone! I&#39;m planning to self-host a web application that needs to serve users globally, and I&#39;m considering using Hetzner as my hosting provider with a Nextjs stack. I know Hetzner is popular in the self-hosting community for its great price-to-performance ratio, but I have some concerns about latency for users in different regions.</p> <p>I&#39;d love to hear from anyone who has experience running globally-accessed applications on Hetzner:</p> <ul> <li>What kind of latency are you seeing between different regions (especially Asia-Pacific and Americas)?</li> <li>Are you using any specific strategies to optimize global access (like Cloudflare in front, multiple VPS instances, etc.)?</li> <li>Would you recommend this setup for a production application with global reach, around 2 million montly traffic or should I be looking at other solutions?</li> </ul> <p>For context, I&#39;m trying to balance cost-effectiveness with reasonable performan

## Anyone know of a self-hosted hunting and tracking solution as an alternative to something like "huntstand"?
 - [https://www.reddit.com/r/selfhosted/comments/1hi1c6m/anyone_know_of_a_selfhosted_hunting_and_tracking](https://www.reddit.com/r/selfhosted/comments/1hi1c6m/anyone_know_of_a_selfhosted_hunting_and_tracking)
 - RSS feed: $source
 - date published: 2024-12-19T19:47:32+00:00

<!-- SC_OFF --><div class="md"><p>This is for a family member who wants to track weather, time and deer sightings (on a map).</p> <p>It would be an alternative to something like <a href="https://www.huntstand.com/huntstand-app/">huntstand</a>.</p> <p>Thank you :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/denogginizer"> /u/denogginizer </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi1c6m/anyone_know_of_a_selfhosted_hunting_and_tracking/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi1c6m/anyone_know_of_a_selfhosted_hunting_and_tracking/">[comments]</a></span>

## Mealie Easy URL Import/Share (Android App)
 - [https://www.reddit.com/r/selfhosted/comments/1hi15in/mealie_easy_url_importshare_android_app](https://www.reddit.com/r/selfhosted/comments/1hi15in/mealie_easy_url_importshare_android_app)
 - RSS feed: $source
 - date published: 2024-12-19T19:39:23+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hi15in/mealie_easy_url_importshare_android_app/"> <img src="https://external-preview.redd.it/8E4GEbJsCFVD_5IbCU3t4GhVAzkaEsZK08oR2Mn4Jm4.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=26bf6055600bcb435c12b2de94c30b793042e8d0" alt="Mealie Easy URL Import/Share (Android App)" title="Mealie Easy URL Import/Share (Android App)" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sean_999"> /u/sean_999 </a> <br/> <span><a href="https://github.com/Sean-on-Git/mealie-android-share/releases/tag/v0.0.1-alpha">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi15in/mealie_easy_url_importshare_android_app/">[comments]</a></span> </td></tr></table>

## Best Web Interfaces for Self-Hosting Email in 2024?
 - [https://www.reddit.com/r/selfhosted/comments/1hi0wq2/best_web_interfaces_for_selfhosting_email_in_2024](https://www.reddit.com/r/selfhosted/comments/1hi0wq2/best_web_interfaces_for_selfhosting_email_in_2024)
 - RSS feed: $source
 - date published: 2024-12-19T19:28:24+00:00

<!-- SC_OFF --><div class="md"><p>I’m thinking about returning to self-hosting email and need advice on the current options for web interfaces. One of the main reasons I enjoy using GMail or ProtonMail is its polished, user-friendly web UI. Are SoGo and Roundcube still the go-to choices? Both are functional, but they feel outdated compared to modern hosted solutions. Are there any better or up-and-coming options I should look into?</p> <p>Also, Microsoft Exchange Server caught my attention as a potential solution. The web interface is solid, and I’d still have full control over my data. But is Exchange Server 2019 really the latest release? Has Microsoft essentially abandoned updates for self-hosted setups like this?</p> <p>I understand the challenges of self-hosting email (SPF, DKIM, DMARC, whitelists/blacklists, etc.), but I’m already experienced with managing those aspects, so I’d prefer to focus this discussion on the web interface side.</p> <p>Looking forward to hearing your tho

## Docker Host on SSD vs Synology SSD Share for Volumes
 - [https://www.reddit.com/r/selfhosted/comments/1hi008t/docker_host_on_ssd_vs_synology_ssd_share_for](https://www.reddit.com/r/selfhosted/comments/1hi008t/docker_host_on_ssd_vs_synology_ssd_share_for)
 - RSS feed: $source
 - date published: 2024-12-19T18:49:46+00:00

<!-- SC_OFF --><div class="md"><p>I have a small mini pc which has mirrored 1TB SSD internal drives, and this is where I store my Docker compose files and volume data.</p> <p>I have the ability to install a NVME SSD into my Synology, and present that as shared storage.</p> <p>Any advantage to moving my docker stuff there to shared storage on SSD versus keeping it local on SSD? The one thought that comes to mind is Tdarr cache directory would be faster than hosting it on my spinning shared storage.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Imburr"> /u/Imburr </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi008t/docker_host_on_ssd_vs_synology_ssd_share_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hi008t/docker_host_on_ssd_vs_synology_ssd_share_for/">[comments]</a></span>

## Running PVE and TrueNAS in respective nvmes
 - [https://www.reddit.com/r/selfhosted/comments/1hhz6t5/running_pve_and_truenas_in_respective_nvmes](https://www.reddit.com/r/selfhosted/comments/1hhz6t5/running_pve_and_truenas_in_respective_nvmes)
 - RSS feed: $source
 - date published: 2024-12-19T18:14:31+00:00

<!-- SC_OFF --><div class="md"><p>I just got a WTR Pro Ryzen and it have space for 3 nvmes.</p> <p>So I was thinking of running mirror proxmox on 2 nvmes and 1 truenas scale on 1 nvme. Letting the truenas scale taking care of HDD. </p> <p>Is there any caveats with this setup?</p> <p>I was thinking if this setup is better than running truenas as virtualized host in proxmox.</p> <p>Any tips?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AI-Got-You"> /u/AI-Got-You </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhz6t5/running_pve_and_truenas_in_respective_nvmes/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhz6t5/running_pve_and_truenas_in_respective_nvmes/">[comments]</a></span>

## Does the strength of the password for my development machine matter if I have servers on the same network?
 - [https://www.reddit.com/r/selfhosted/comments/1hhz35w/does_the_strength_of_the_password_for_my](https://www.reddit.com/r/selfhosted/comments/1hhz35w/does_the_strength_of_the_password_for_my)
 - RSS feed: $source
 - date published: 2024-12-19T18:10:11+00:00

<!-- SC_OFF --><div class="md"><p>For context, I have about 30 self-hosted applications. On another computer on the same LAN, I do development.</p> <p>I don&#39;t have SSH enabled and and I don&#39;t expect anybody else to use my computer, so does my user&#39;s password strength make any difference?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/floofcode"> /u/floofcode </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhz35w/does_the_strength_of_the_password_for_my/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhz35w/does_the_strength_of_the_password_for_my/">[comments]</a></span>

## What is the benefit of static IPs for servers? And what is a server?
 - [https://www.reddit.com/r/selfhosted/comments/1hhy6aj/what_is_the_benefit_of_static_ips_for_servers_and](https://www.reddit.com/r/selfhosted/comments/1hhy6aj/what_is_the_benefit_of_static_ips_for_servers_and)
 - RSS feed: $source
 - date published: 2024-12-19T17:31:27+00:00

<!-- SC_OFF --><div class="md"><p>I have noticed lots of folks deploy everything possible and statically assign IPs on every piece that is a &quot;server&quot;. And e.g. IoT equipment, are they servers too?</p> <p>I have always struggled with this idea as there&#39;s a good risk of that forgotten Raspberry Pi in the basement ending up with an IP conflict. Also hard to move equipment into a different network segment headless.</p> <p>With IPv6 this creates one more obstacle where would otherwise be fairly self-contained setup based on RA and SLAAC which can flexibly take on new (or multiple) prefixes as ISPs come and go, it instead becomes a chore to maintain.</p> <p>How would you &quot;sell&quot; me a static IP, i.e. statically configured in each gear itself? What&#39;s the criteria for you?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/esiy0676"> /u/esiy0676 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhy6aj/what_is

## Filebrowser installation issue
 - [https://www.reddit.com/r/selfhosted/comments/1hhxomn/filebrowser_installation_issue](https://www.reddit.com/r/selfhosted/comments/1hhxomn/filebrowser_installation_issue)
 - RSS feed: $source
 - date published: 2024-12-19T17:10:28+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys, while searching reddit for help installing filebrowser I cam across some chat on the subject in this group, so hoping you guys can help me.</p> <p>I&#39;m trying to install filebrowser on windows 10, no docker. I&#39;m not a programmer but I have used windows terminal before a few times. I used the code provided on the filebrowser install page, which says</p> <p>iwr -useb <a href="https://raw.githubusercontent.com/filebrowser/get/master/get.ps1">https://raw.githubusercontent.com/filebrowser/get/master/get.ps1</a> | iex filebrowser -r /path/to/your/files</p> <p>After running wt as admin I successfully got filebrowser installed, but with the second line, I put </p> <p>filebrowser -r /I:/Shared </p> <p>And it says filebrowser is not recognized as a cmdlet, function etc</p> <p>So, what can/should I do?</p> <p>I haven&#39;t used docker before so this seemed easier.</p> <p>Also, if there&#39;s an easier solution to remotely drop or upload larger f

## Setting up nginx proxy manager
 - [https://www.reddit.com/r/selfhosted/comments/1hhw63q/setting_up_nginx_proxy_manager](https://www.reddit.com/r/selfhosted/comments/1hhw63q/setting_up_nginx_proxy_manager)
 - RSS feed: $source
 - date published: 2024-12-19T16:04:53+00:00

<!-- SC_OFF --><div class="md"><p>I have a domain purchased from go daddy and i setup ngnix proxy manager, I am able to login to the port and manage it. I also went to duckdns and set that up. I then went to my godaddy dns setting and added a CNAME with www and the duckdns url with ttl 1/2 hr</p> <p>Went back to ngnix click add a new proxy host with my godaddy domain that I purchased for example <a href="http://www.exampledomain.com">www.exampledomain.com</a> </p> <p>Scheme http</p> <p>Forward Hostname / IP &gt; <a href="http://exampledomain.com">exampledomain.com</a> &gt; port 2283</p> <p>Added websockets Support but also removed websocket suppport</p> <p>Cant login though what am I doing wrong?</p> <p><a href="https://preview.redd.it/poilhsjzvt7e1.png?width=357&amp;format=png&amp;auto=webp&amp;s=5bb18d1b81e2f3919eb73f1a483fbf04bffe531e">https://preview.redd.it/poilhsjzvt7e1.png?width=357&amp;format=png&amp;auto=webp&amp;s=5bb18d1b81e2f3919eb73f1a483fbf04bffe531e</a></p> <p>Also god

## Is there a game similar to Fractured/Legend of Aria/wild terra 2 that I can selhost
 - [https://www.reddit.com/r/selfhosted/comments/1hhvzux/is_there_a_game_similar_to_fracturedlegend_of](https://www.reddit.com/r/selfhosted/comments/1hhvzux/is_there_a_game_similar_to_fracturedlegend_of)
 - RSS feed: $source
 - date published: 2024-12-19T15:57:27+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hhvzux/is_there_a_game_similar_to_fracturedlegend_of/"> <img src="https://b.thumbs.redditmedia.com/3NNzkKqxPnieupv-n6EazYj7ywSqVEjOGnWmj_3vINU.jpg" alt="Is there a game similar to Fractured/Legend of Aria/wild terra 2 that I can selhost " title="Is there a game similar to Fractured/Legend of Aria/wild terra 2 that I can selhost " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Is there a game similar to Fractured online/Legend of Aria/Wild terra 2 that I can host on my machine and play with my community? 20/30 players (medieval)</p> <p>that gives this feeling of MMORPG progression, sandbox, farming, housing, etc.</p> <p>Does anyone have any tips or recommendations?</p> <p><a href="https://preview.redd.it/0rodgfg7vt7e1.jpg?width=1080&amp;format=pjpg&amp;auto=webp&amp;s=0ca482f608f6fe2f90d631a0c8c83a36e445e20f">https://preview.redd.it/0rodgfg7vt7e1.jpg?width=1080&amp;format=pjpg&amp;auto=webp&amp;s=0ca482f608f6

## What’s the best option for a Home Server in 2024? (NS + mixed storage)
 - [https://www.reddit.com/r/selfhosted/comments/1hhvocs/whats_the_best_option_for_a_home_server_in_2024](https://www.reddit.com/r/selfhosted/comments/1hhvocs/whats_the_best_option_for_a_home_server_in_2024)
 - RSS feed: $source
 - date published: 2024-12-19T15:42:54+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I’m planning to build a Home Server and would love your input on the best setup available today.</p> <p>My main goals are: 1. Using it primarily as Network Storage (NS), but I also want it to be flexible for other uses (e.g., multimedia, backups, and some containerized applications). 2. Taking full advantage of NVMe drives, as I already have several and love their speed. I also want to include SATA drives for mass storage.</p> <p>I’ve been looking into cases like Jonsbo, which seem well-designed and support multiple drives, but I’m unsure what motherboard would be the best choice. I’m looking for something modern, fast, and with solid NVMe support. Energy efficiency would be nice, but it’s not a dealbreaker.</p> <p>Ideally, I’d like to keep the budget around 300 euros or slightly above for the core components (motherboard, CPU, and RAM). Are there any recommendations for motherboards, processors, or even alternatives to Jonsbo cases that

## Phone and server stop seeing each other around the same time everyday
 - [https://www.reddit.com/r/selfhosted/comments/1hhvhmm/phone_and_server_stop_seeing_each_other_around](https://www.reddit.com/r/selfhosted/comments/1hhvhmm/phone_and_server_stop_seeing_each_other_around)
 - RSS feed: $source
 - date published: 2024-12-19T15:34:13+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hhvhmm/phone_and_server_stop_seeing_each_other_around/"> <img src="https://b.thumbs.redditmedia.com/8RfvB8KqUwnKFXROuNXBKWWeh6tR0jXLuyG1wDrSP8g.jpg" alt="Phone and server stop seeing each other around the same time everyday" title="Phone and server stop seeing each other around the same time everyday" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I have a Debian server running on a laptop connected through wifi, I set up the `/etc/network/interfaces` to have a static ip like so:<br/> ```<br/> # The primary network interface</p> <p>auto wlp2s0</p> <p>iface wlp2s0 inet static</p> <p>wpa-ssid ***</p> <p>wpa-psk ***</p> <p>address <a href="http://192.168.100.254">192.168.100.254</a></p> <p>netmask <a href="http://255.255.255.0">255.255.255.0</a></p> <p>gateway <a href="http://192.168.100.1">192.168.100.1</a><br/> ```<br/> Also in my router i set a DHCP reservation for the ip like so:</p> <p><a href="https://pre

## phone contract / device management software
 - [https://www.reddit.com/r/selfhosted/comments/1hhuf4e/phone_contract_device_management_software](https://www.reddit.com/r/selfhosted/comments/1hhuf4e/phone_contract_device_management_software)
 - RSS feed: $source
 - date published: 2024-12-19T14:45:15+00:00

<!-- SC_OFF --><div class="md"><p>Any recommendations for a software that we can use to manage / have an overview over our smartphone contracts?</p> <p>We have mobile contracts with phone numbers and seperate contracts for devices. They are not linked (a user X can have number Y but phone Z - number Y is not linked to phone Z).</p> <p>So i need a software (selfhosted / free?) where i can create phone number contracts and can link them to an actual user and maybe have a histroy about the past users) - also it should be able to create devices and add them to users and / or have the ability to archive them if needed (send back to provider).</p> <p>Hopefully you can understand what i´m searching for... :-)</p> <p>Best regards!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AnnualAggravating747"> /u/AnnualAggravating747 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhuf4e/phone_contract_device_management_software/">[link]</

## Mealie Quick Add Firefox Extension
 - [https://www.reddit.com/r/selfhosted/comments/1hhtuzp/mealie_quick_add_firefox_extension](https://www.reddit.com/r/selfhosted/comments/1hhtuzp/mealie_quick_add_firefox_extension)
 - RSS feed: $source
 - date published: 2024-12-19T14:17:56+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hhtuzp/mealie_quick_add_firefox_extension/"> <img src="https://external-preview.redd.it/tRB7R24W6LHK8hDC6Q4LjYmJHTrv1MiZmKtfI-AMmTs.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=8f2779d53424c72b91d42a149ad1f9e6cbb66f47" alt="Mealie Quick Add Firefox Extension" title="Mealie Quick Add Firefox Extension" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sean_999"> /u/sean_999 </a> <br/> <span><a href="https://addons.mozilla.org/en-US/firefox/addon/mealie-context-menu/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhtuzp/mealie_quick_add_firefox_extension/">[comments]</a></span> </td></tr></table>

## Just found a Top-Rated Web-Based Linux Server Management Tool. 1Panel features an intuitive web interface that seamlessly integrates server management and monitoring, container management, database administration, website management, system backup and restoration, and more.
 - [https://www.reddit.com/r/selfhosted/comments/1hht5s6/just_found_a_toprated_webbased_linux_server](https://www.reddit.com/r/selfhosted/comments/1hht5s6/just_found_a_toprated_webbased_linux_server)
 - RSS feed: $source
 - date published: 2024-12-19T13:43:01+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hht5s6/just_found_a_toprated_webbased_linux_server/"> <img src="https://external-preview.redd.it/24iV6kGx9PG2ypMaFEUovEcqEBtnorMScp7LY7ZcT8k.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=816c3ea87817a3d42b0a53cee097c42259ec2c6e" alt="Just found a Top-Rated Web-Based Linux Server Management Tool. 1Panel features an intuitive web interface that seamlessly integrates server management and monitoring, container management, database administration, website management, system backup and restoration, and more." title="Just found a Top-Rated Web-Based Linux Server Management Tool. 1Panel features an intuitive web interface that seamlessly integrates server management and monitoring, container management, database administration, website management, system backup and restoration, and more." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Careless_Corgi_7164"> /u/Careless_Corgi_7164 </a> 

## Need help setting up Caddy
 - [https://www.reddit.com/r/selfhosted/comments/1hhsyvk/need_help_setting_up_caddy](https://www.reddit.com/r/selfhosted/comments/1hhsyvk/need_help_setting_up_caddy)
 - RSS feed: $source
 - date published: 2024-12-19T13:32:49+00:00

<!-- SC_OFF --><div class="md"><p>I purchased a domain, and I ended up installed caddy, which will never do again unless I have a very good guide because I ended up not being able to login into to my server, not even sure what I did.</p> <p>But essentially I host my own immich server but I want to point caddy to my server so I can have others login in. I use tailscale so I dont really need it but like if I had friends, family...etc they can easily login or I can share photos.</p> <p>Does anyone have a easy to follow guide for caddy? I have docker installed on my nas if this even helps although I doubt it, a domain, and I used duckdns in order to ensure my ip is always up to date.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Swiss_Meats"> /u/Swiss_Meats </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhsyvk/need_help_setting_up_caddy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1

## Want to build the server which serves well
 - [https://www.reddit.com/r/selfhosted/comments/1hhsimz/want_to_build_the_server_which_serves_well](https://www.reddit.com/r/selfhosted/comments/1hhsimz/want_to_build_the_server_which_serves_well)
 - RSS feed: $source
 - date published: 2024-12-19T13:08:14+00:00

<!-- SC_OFF --><div class="md"><p>I have an old PC with i7 3770 12GB DDR3 RAM, 256GB SSD, 320GB HDD, AND 2TB HDD. I want to make it useful for my company as it&#39;s nature is Ecommerce export (in india) and shipments are sent via FedEx, naturally we have to deal with Many documents of Invoices and their awbs, FedEx sends Courier shipping bill of each AWB via mail (with it&#39;s AwB number) i want to have the facility to auto download them everyday without deleting copies from mail id, and save them with invoice number (the invocie number is in this format SCV-123/2023-24) without duplication, and I may need any document at anytime. So universal search is must for me. Also I want inbuilt pdf merger so I don&#39;t have to rely on other stuffs, I have files of companies spread across my system and my Google drive which due to human memory is difficulty to remember what is where. </p> <p>Currently I am using paid google drive but it lacks many of these things.</p> <p>I usually save invo

## Caddy L4 config help
 - [https://www.reddit.com/r/selfhosted/comments/1hhsfb6/caddy_l4_config_help](https://www.reddit.com/r/selfhosted/comments/1hhsfb6/caddy_l4_config_help)
 - RSS feed: $source
 - date published: 2024-12-19T13:03:03+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hhsfb6/caddy_l4_config_help/"> <img src="https://b.thumbs.redditmedia.com/oM5h-dVNiUc6Qz8pHS9kByQH0c2jPqRgSa3Hp6D9THE.jpg" alt="Caddy L4 config help" title="Caddy L4 config help" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello!</p> <p>I&#39;m very new to Linux, reverse proxies, and CADDY with CADDY L4 addon but I got it working.</p> <p>I&#39;m stumped on how to setup the caddy file for L4 routing using a reverse proxy, I cant seem to get a config to work.</p> <p>I have a game server that I&#39;m trying to run but I am unable to find it on the browser of the games I run. I am very familiar with running the games itself with port forwarding but I decided its best to just stick with a reverse proxy for security purposes and future expansion.</p> <p>My current setup looks like this</p> <p>[Home server]==={Tailscale}===[Reverse proxy Ubuntu server]-----[[[Internet]]]</p> <p>I do have a domain with a temporar

## Introducing Notificox - self-contained, dependency-free notification sender
 - [https://www.reddit.com/r/selfhosted/comments/1hhrvl5/introducing_notificox_selfcontained](https://www.reddit.com/r/selfhosted/comments/1hhrvl5/introducing_notificox_selfcontained)
 - RSS feed: $source
 - date published: 2024-12-19T12:31:25+00:00

<!-- SC_OFF --><div class="md"><p>Hello, selfhosters!</p> <p>I am writing a powerful notification server, called <a href="https://www.reddit.com/r/selfhosted/comments/1gzf2l0/">Notifico</a>, but deploying a full-blown server solution seems to be overkill in many cases. So I&#39;ve decided to make a companion app, that can send notifications locally, using just a single command.</p> <p>So, Notificox was born.</p> <p>Features:</p> <ul> <li>Email, Slack, Telegram, Gotify, <a href="http://ntfy.sh">ntfy.sh</a> support</li> <li>No dependencies required. Just a single binary.</li> <li>Attachment support.</li> <li>Powerful templating engine: just pass a JSON context, and you&#39;ll get you a beautiful message.</li> <li>Written in 🦀 Rust.</li> </ul> <h1>Examples:</h1> <p>Sending a Telegram message to me:</p> <pre><code>notificox send &quot;telegram:TOKEN&quot; &quot;telegram:111579711&quot; -c &quot;{body: &#39;my notification body&#39;}&quot; </code></pre> <p>Sending a Slack message with a P

## Interested in Building My Own Phone Server – Looking for Tips & Resources!
 - [https://www.reddit.com/r/selfhosted/comments/1hhrn4c/interested_in_building_my_own_phone_server](https://www.reddit.com/r/selfhosted/comments/1hhrn4c/interested_in_building_my_own_phone_server)
 - RSS feed: $source
 - date published: 2024-12-19T12:17:12+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hhrn4c/interested_in_building_my_own_phone_server/"> <img src="https://b.thumbs.redditmedia.com/GY-RzdH1H1tn0PRizsHkE-PZEjNGX840YVYjNVBqWSA.jpg" alt=" Interested in Building My Own Phone Server – Looking for Tips &amp; Resources!" title=" Interested in Building My Own Phone Server – Looking for Tips &amp; Resources!" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi everyone!</p> <p>I recently came across some posts about phone servers, and I think it’s such a cool idea! I have a few old phones lying around, and I’d love to try building a phone server for myself. However, I have no previous experience with self-hosting, so I’m hoping you all can point me in the right direction.</p> <p>I’m particularly curious about:</p> <ul> <li><strong>What operating system would be best ?</strong></li> <li><strong>What are some fun things I can do?</strong></li> <li><strong>Any tutorials, guides, or resources to build from

## My setup using Terraform and Kubernetes
 - [https://www.reddit.com/r/selfhosted/comments/1hhrbeg/my_setup_using_terraform_and_kubernetes](https://www.reddit.com/r/selfhosted/comments/1hhrbeg/my_setup_using_terraform_and_kubernetes)
 - RSS feed: $source
 - date published: 2024-12-19T11:57:13+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hhrbeg/my_setup_using_terraform_and_kubernetes/"> <img src="https://external-preview.redd.it/rU6KnnwjrLwv7BazZ9Jbcxaod_2v0kawqRPm6GIGBKg.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=f983a50c5154b026d292cdd9b8542ea9b3d6dc59" alt="My setup using Terraform and Kubernetes" title="My setup using Terraform and Kubernetes" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>&gt; TL;DR: Homelab infrastructure with Terraform and K8S <a href="https://github.com/cfstcyr/homelab-v3">https://github.com/cfstcyr/homelab-v3</a></p> <p>I&#39;ve recently started my journey to transition all my setup from Docker Compose to Terraform and Kubernetes. I felt I was limited by only using Docker Compose for everything external, so I wanted to try to make something a little more robust.</p> <p>Here is what I manage to do:</p> <ul> <li><strong>One-click setup</strong>: Everything in my setup -- application deployment, DNS records, tunn

## Alternative to Bolt AI ( All AI models in one app )
 - [https://www.reddit.com/r/selfhosted/comments/1hhqd08/alternative_to_bolt_ai_all_ai_models_in_one_app](https://www.reddit.com/r/selfhosted/comments/1hhqd08/alternative_to_bolt_ai_all_ai_models_in_one_app)
 - RSS feed: $source
 - date published: 2024-12-19T10:51:55+00:00

<!-- SC_OFF --><div class="md"><p>I like the <a href="https://www.chatbotslist.com/chatbots/boltai">Bolt AI</a> app, but I don&#39;t have a Mac, and it&#39;s only available for Mac users. I need it because it helps switch between top AI services and local models, all from a single native app.</p> <p>I have Ubuntu &amp; Windows</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gary_king_001"> /u/gary_king_001 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhqd08/alternative_to_bolt_ai_all_ai_models_in_one_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhqd08/alternative_to_bolt_ai_all_ai_models_in_one_app/">[comments]</a></span>

## Host firewall (firewalld / ufw / fail2ban) vs Network firewall (pfsense) for web hosting a single VM ?
 - [https://www.reddit.com/r/selfhosted/comments/1hhpzm2/host_firewall_firewalld_ufw_fail2ban_vs_network](https://www.reddit.com/r/selfhosted/comments/1hhpzm2/host_firewall_firewalld_ufw_fail2ban_vs_network)
 - RSS feed: $source
 - date published: 2024-12-19T10:25:31+00:00

<!-- SC_OFF --><div class="md"><p>Hello</p> <p>I have a single Debian VM which I intend to use as web server and open it to the world.</p> <p>I already have a reverse proxy in front of my web services but I think I need to secure it a bit more before opening port 443 on my ISP router.</p> <p>For now I just configured <em>simples</em> rules on the proxmox firewall (which is stateful firewall) : </p> <p>- outbound connection initiated from that VM are ONLY allowed to Internet (but are blocked if going to my own IPv4/IPv6 LAN)</p> <p>- inbound connection initated outside that VM are allowed from INTERNET and from my own LAN to the VM</p> <p>So its very minimal.</p> <p>I could install a pfsense VM in front of it, but I think its a bit overkill for just one VM. Is there a simpler solution ? </p> <p>Like using the Debian Firewalld instead of a dedicated network firewall ? would that be enough ?</p> <p>My criteria are :</p> <p>- I would like to block connection from other countries except m

## Calibre-Web OPDS - Need Help
 - [https://www.reddit.com/r/selfhosted/comments/1hhp4t3/calibreweb_opds_need_help](https://www.reddit.com/r/selfhosted/comments/1hhp4t3/calibreweb_opds_need_help)
 - RSS feed: $source
 - date published: 2024-12-19T09:21:58+00:00

<!-- SC_OFF --><div class="md"><p>Hello I need your help with empty OPDS !</p> <p>I installed Calibre-Web using a helperscript on my proxmox in an lxc: <a href="https://community-scripts.github.io/ProxmoxVE/scripts?id=calibre-web">https://community-scripts.github.io/ProxmoxVE/scripts?id=calibre-web</a></p> <p>I set it up in a way that the LXC is on my nvme boot disk but the library / books are saved on my zfs pool. I ensured that permission are properly set-up and after testing I am able to upload books to the application using the upload button and read them. The current issue I am having is using the OPDS. I am able to access it using myip/opds and the credentials but I doesnt show any ebooks. I had a look at the text using the browser and it shows no book entries - I also tested it with my iphone and my kindle koreader and again i can connect but it says no books available.</p> <p>To test if it has anything to do with my zfs pool and permission I reverted it and let everything hap

## Worker Pooling — a new way of running CPU-intensive JavaScript workloads
 - [https://www.reddit.com/r/selfhosted/comments/1hhp0n4/worker_pooling_a_new_way_of_running_cpuintensive](https://www.reddit.com/r/selfhosted/comments/1hhp0n4/worker_pooling_a_new_way_of_running_cpuintensive)
 - RSS feed: $source
 - date published: 2024-12-19T09:13:19+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hhp0n4/worker_pooling_a_new_way_of_running_cpuintensive/"> <img src="https://external-preview.redd.it/0D80oXeWde4WqpU6G9nDP7CzOe_EdnrsvxJba19yhkY.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=ec8899f1c31891946809488cc0ac37f0ff0692a4" alt="Worker Pooling — a new way of running CPU-intensive JavaScript workloads" title="Worker Pooling — a new way of running CPU-intensive JavaScript workloads" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/machete127"> /u/machete127 </a> <br/> <span><a href="https://encore.dev/blog/worker-pooling">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhp0n4/worker_pooling_a_new_way_of_running_cpuintensive/">[comments]</a></span> </td></tr></table>

## Smarter Subdomain and SSL Setup with Nginx: A Hands-On Guide
 - [https://www.reddit.com/r/selfhosted/comments/1hho3bm/smarter_subdomain_and_ssl_setup_with_nginx_a](https://www.reddit.com/r/selfhosted/comments/1hho3bm/smarter_subdomain_and_ssl_setup_with_nginx_a)
 - RSS feed: $source
 - date published: 2024-12-19T08:03:14+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hho3bm/smarter_subdomain_and_ssl_setup_with_nginx_a/"> <img src="https://external-preview.redd.it/MWcsWMODInmce-e-1ByngZByTFjjZygI6TOIXMi7JN0.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=3ac11171d6875a9d589b24eb50f37981167b96e9" alt="Smarter Subdomain and SSL Setup with Nginx: A Hands-On Guide" title="Smarter Subdomain and SSL Setup with Nginx: A Hands-On Guide" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/chicagojango"> /u/chicagojango </a> <br/> <span><a href="https://geekist.co/smarter-defaults-for-subdomains-and-ssl">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hho3bm/smarter_subdomain_and_ssl_setup_with_nginx_a/">[comments]</a></span> </td></tr></table>

## I built an AI-powered Database Management Tool, Free and Open-Source
 - [https://www.reddit.com/r/selfhosted/comments/1hhnv3z/i_built_an_aipowered_database_management_tool](https://www.reddit.com/r/selfhosted/comments/1hhnv3z/i_built_an_aipowered_database_management_tool)
 - RSS feed: $source
 - date published: 2024-12-19T07:46:50+00:00

<!-- SC_OFF --><div class="md"><p>Hi community,</p> <p>A year ago, I open-sourced <strong>Chat2DB</strong>, an AI-powered database management tool designed to make database management smarter and more efficient. While it’s not a brand-new project, this is my first time sharing it publicly in a community like this. I’ve mostly been developing it on my own and haven’t received much direct feedback from users on its features, so I’m really hoping to get your input and suggestions to improve it.</p> <p>Here are the key features:</p> <ul> <li><strong>Natural Language to SQL</strong>: You can generate SQL queries directly from natural language. Just describe what you need, and Chat2DB will write the SQL for you—no need to know the syntax.</li> <li><strong>Smart SQL Editor</strong>: Chat2DB includes an intelligent SQL editor with syntax highlighting, auto-completion, and error marking. It supports over 24 databases like MySQL, PostgreSQL, SQLite, and more.</li> <li><strong>Data Analysis and

## migrate between dashboard solutions?
 - [https://www.reddit.com/r/selfhosted/comments/1hhnc8h/migrate_between_dashboard_solutions](https://www.reddit.com/r/selfhosted/comments/1hhnc8h/migrate_between_dashboard_solutions)
 - RSS feed: $source
 - date published: 2024-12-19T07:08:42+00:00

<!-- SC_OFF --><div class="md"><p>Hi there,</p> <p>i&#39;m using heimdall, but i want to change to another dashboard solution. I&#39;m missing something like dashys easy &quot;just start typing&quot; filtering.</p> <p>unfortunately i did not find a way to migrate from heimdall to dashy and i don&#39;T want do rebuild it manually.</p> <p>Are there any dashboards, that allow importing data from other dashboards?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Flimsy-Mortgage-7284"> /u/Flimsy-Mortgage-7284 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhnc8h/migrate_between_dashboard_solutions/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhnc8h/migrate_between_dashboard_solutions/">[comments]</a></span>

## I am gonna attempt to install Crowdsec to work with NPM, advice please.
 - [https://www.reddit.com/r/selfhosted/comments/1hhmql5/i_am_gonna_attempt_to_install_crowdsec_to_work](https://www.reddit.com/r/selfhosted/comments/1hhmql5/i_am_gonna_attempt_to_install_crowdsec_to_work)
 - RSS feed: $source
 - date published: 2024-12-19T06:27:25+00:00

<!-- SC_OFF --><div class="md"><p>I am running the latest version of Ubuntu Server OS and I installed Nginx Proxy Manager with Dockcer compose. I tried installing Crowsec before only to end up messing up my NPM configuration. Something about the bouncer not starting or connecting. I used ChatGPT only last time but before I attempt again today I wanted to ask ya&#39;ll see if you could give me any advice or point me in the right direction. </p> <p>Thanks in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/iamwhoiwasnow"> /u/iamwhoiwasnow </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhmql5/i_am_gonna_attempt_to_install_crowdsec_to_work/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhmql5/i_am_gonna_attempt_to_install_crowdsec_to_work/">[comments]</a></span>

## Pretty confused, suspect ISP is messing with inbound traffic
 - [https://www.reddit.com/r/selfhosted/comments/1hhlpq9/pretty_confused_suspect_isp_is_messing_with](https://www.reddit.com/r/selfhosted/comments/1hhlpq9/pretty_confused_suspect_isp_is_messing_with)
 - RSS feed: $source
 - date published: 2024-12-19T05:23:10+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to make servers at home accessible from the outside world. I&#39;m using a DDNS service.</p> <p>Going back to &quot;basics,&quot; I set up an Apache web server. It partially works, but something very strange is happening.</p> <p>Here&#39;s what I find:</p> <ul> <li>I can serve http traffic on port 80 just fine</li> <li>I can also serve https traffic on port 80 just fine (I&#39;m using a let&#39;s encrypt cert)</li> <li>But I can&#39;t serve http or https traffic on port 443 (chrome always shows ERR_EMPTY_RESPONSE, and Apache access.log doesn&#39;t see the request at all!)</li> </ul> <p>According to <a href="https://www.canyouseeme.org/">https://www.canyouseeme.org/</a> , it can &quot;see&quot; the services on both 80 and 443 (when running).</p> <p>So I&#39;m baffled. Could it be that my ISP is somehow blocking 443 but not 80? Is there any way to verify this?</p> <p>Edit: If I pick a random port (1234), I can serve http or https traffic

## Jellyfin and HD HomeRun TS Recordings
 - [https://www.reddit.com/r/selfhosted/comments/1hhli5b/jellyfin_and_hd_homerun_ts_recordings](https://www.reddit.com/r/selfhosted/comments/1hhli5b/jellyfin_and_hd_homerun_ts_recordings)
 - RSS feed: $source
 - date published: 2024-12-19T05:10:55+00:00

<!-- SC_OFF --><div class="md"><p>Sorry, not real sure where to share my question since Jellyfin Reddit is read only…</p> <p>I have an issue: it’s me, probably, truth be told🤣. Looking for help and have googled for days now and can’t seem to get terminology right, I guess?</p> <p>When I use Jellyfin to record OTA tv with the and the HD HomeRun the OTA TV records fine but Jellyfin saves the video recording as a TS file type. TS file type seems to not play well anywhere and causes issues. </p> <p>How can I get Jellyfin to save the HD HomeRun recordings in a different file type/format(not TS)? What video file format would be best to be shared on iPhones or most compatible in general? Is there a way I can get Jellyfin to automatically convert the recording once it’s done? What other options do I have or what could I search for so that Google could help me out if nothing else?</p> <p>Just not sure what to do or what I need to do but the TS file type is problematic. </p> </div><!-- SC_ON -

## Tailscale reverse proxy
 - [https://www.reddit.com/r/selfhosted/comments/1hhl3zb/tailscale_reverse_proxy](https://www.reddit.com/r/selfhosted/comments/1hhl3zb/tailscale_reverse_proxy)
 - RSS feed: $source
 - date published: 2024-12-19T04:47:39+00:00

<!-- SC_OFF --><div class="md"><p>I know it has been asked a few times but solutions I saw across does not work in my case (maybe my understanding on dns resolving is still not good). so I want to breakdown my current setup</p> <p>- 1 raspi running pi-hole</p> <p>- 1 server running almost anything (has pihole too) and nginx proxy manager</p> <p>my npm docker compose (not sure if dns option is needed, that is IP of my raspi)</p> <p>I have ssl cert generated from letsencrypt inside npm for my domain.</p> <p>when I registered `&lt;tailscale ip&gt;:&lt;port&gt;` on my npm, it can&#39;t resolved the domain name.</p> <p>I&#39;m fine with re-config my npm but not sure *which part*. I need some help</p> <p>[EDIT]: SOLVED<br/> turns out I need to add records on Local DNS on my Pihole dashboard</p> <pre><code>version: &#39;3.8&#39; services: app: image: &#39;jc21/nginx-proxy-manager:latest&#39; restart: unless-stopped ports: # These ports are in format &lt;host-port&gt;:&lt;container-port&gt; 

## Clipboard sharing between Android and Linux devices
 - [https://www.reddit.com/r/selfhosted/comments/1hhkoay/clipboard_sharing_between_android_and_linux](https://www.reddit.com/r/selfhosted/comments/1hhkoay/clipboard_sharing_between_android_and_linux)
 - RSS feed: $source
 - date published: 2024-12-19T04:22:11+00:00

<!-- SC_OFF --><div class="md"><p>I use <strong>Tailscale</strong> to send and receive files between my Linux laptops and Android devices. I&#39;m now looking for a tool or method to share clipboard content directly. Specifically, I want to copy text on my Android device and send it to my Linux laptop without needing to save the text as a file on the Android device first.</p> <p>Does such a tool exist, and if so, what would you recommend?</p> <p>P.S. I though PrivateBin would solve this but apparently not.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/i8ad8"> /u/i8ad8 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhkoay/clipboard_sharing_between_android_and_linux/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhkoay/clipboard_sharing_between_android_and_linux/">[comments]</a></span>

## SelfHosted Email server as a service
 - [https://www.reddit.com/r/selfhosted/comments/1hhjekk/selfhosted_email_server_as_a_service](https://www.reddit.com/r/selfhosted/comments/1hhjekk/selfhosted_email_server_as_a_service)
 - RSS feed: $source
 - date published: 2024-12-19T03:11:20+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>Long-time reader, a first-time poster here. I’m seeking recommendations for a reliable email server solution that I can self-host for multiple clients. Ideally, I need something modern, stable, and compatible with S3 for email storage. It doesn’t necessarily need a web client—it can be just the engine.</p> <p>Here’s what I’ve explored so far:</p> <ul> <li><strong>Mailcow</strong>: Fantastic system overall, but it lacks native support for S3. While I’ve tried workarounds like <code>s3fs</code> and <code>rclone</code>, they don&#39;t feel stable enough for a production environment.</li> <li><strong>Stalwart</strong>: Also a great option with S3 integration, but it has some limitations unless you&#39;re on an enterprise license. I’ve also run into issues when connecting it to mail clients.</li> </ul> <p>So, here I am, asking this awesome community: are there any other systems I might have missed that check these boxes?</p> <p>Than

## Any open-source self-host Whatsapp Business API that allow multi agent to reply using single account
 - [https://www.reddit.com/r/selfhosted/comments/1hhj6f5/any_opensource_selfhost_whatsapp_business_api](https://www.reddit.com/r/selfhosted/comments/1hhj6f5/any_opensource_selfhost_whatsapp_business_api)
 - RSS feed: $source
 - date published: 2024-12-19T02:59:14+00:00

<!-- SC_OFF --><div class="md"><p>i would like to find an open source that allow multi-agents to reply clients using single Whatsapp account.</p> <p>its best that it can also showing who replying to who. Appreciate to any suggestion or solution. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/howardchin92"> /u/howardchin92 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhj6f5/any_opensource_selfhost_whatsapp_business_api/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhj6f5/any_opensource_selfhost_whatsapp_business_api/">[comments]</a></span>

## Tool for describing videos using LLMs to make search and video management easier
 - [https://www.reddit.com/r/selfhosted/comments/1hhisl2/tool_for_describing_videos_using_llms_to_make](https://www.reddit.com/r/selfhosted/comments/1hhisl2/tool_for_describing_videos_using_llms_to_make)
 - RSS feed: $source
 - date published: 2024-12-19T02:39:07+00:00

<!-- SC_OFF --><div class="md"><p>I was looking for a way to automatically describe my family videos so they&#39;re easier to find and couldn&#39;t find anything so I made one that leverages open source LLMs.<br/> <a href="https://github.com/byjlw/video-analyzer">https://github.com/byjlw/video-analyzer</a></p> <p>Still a work in progress but it&#39;s working ok for right now for my use cases. Will refine the prompts over time so the output is better for search.</p> <p>The easiest way to get using it is actually by getting a key from <a href="http://openrouter.ai">openrouter.ai</a> and then run the following commands, specifying your key.</p> <pre><code>git clone https://github.com/byjlw/video-analyzer.git cd video-analyzer pip install -e . video-analyzer myvideo.MOV --openrouter-key mykey </code></pre> <p>If you don&#39;t have ffmpeg installed you need to install that first, I included instructions in the readme. </p> <p>If you want to run everything 100% locally just download ollama

## What’s everyone using for Security Camera setups?
 - [https://www.reddit.com/r/selfhosted/comments/1hhipkj/whats_everyone_using_for_security_camera_setups](https://www.reddit.com/r/selfhosted/comments/1hhipkj/whats_everyone_using_for_security_camera_setups)
 - RSS feed: $source
 - date published: 2024-12-19T02:34:42+00:00

<!-- SC_OFF --><div class="md"><p>We rent and recently had someone try to break into our cars. Got permission from the landlord to mount some cameras to help protect our stuff. </p> <p>What’s everyone doing for Camera and footage storage solutions? I was going to go Ubiquiti because I have a UDM Pro, but the wireless camera doesn’t appear to be battery powered. </p> <p>Main requirement is wireless cameras that are battery powered and outdoor suitable. Also want to be able to self host the storage and monitoring of the cameras if possible. Most of the major camera brands and subscriptions seem sketchy to me. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Clean-Gain1962"> /u/Clean-Gain1962 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhipkj/whats_everyone_using_for_security_camera_setups/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhipkj/whats_everyone_using_for_security_camer

## Wireguard port forwarding not working
 - [https://www.reddit.com/r/selfhosted/comments/1hhhjeo/wireguard_port_forwarding_not_working](https://www.reddit.com/r/selfhosted/comments/1hhhjeo/wireguard_port_forwarding_not_working)
 - RSS feed: $source
 - date published: 2024-12-19T01:33:44+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, I have a proxmox server with a wireguard container. I created a tunnel and a peer. All seems to work while I am in my home network, but when i use any other network, just stops working. I have port forwarded the listening port (51820) as UDP with the correct ip address. I have tried disabling the proxmox firewall, same problem persists. Any fix?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Qobyl"> /u/Qobyl </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhhjeo/wireguard_port_forwarding_not_working/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhhjeo/wireguard_port_forwarding_not_working/">[comments]</a></span>

## Might be dumb question but here it goes
 - [https://www.reddit.com/r/selfhosted/comments/1hhgddp/might_be_dumb_question_but_here_it_goes](https://www.reddit.com/r/selfhosted/comments/1hhgddp/might_be_dumb_question_but_here_it_goes)
 - RSS feed: $source
 - date published: 2024-12-19T00:35:04+00:00

<!-- SC_OFF --><div class="md"><p>I am an amateur when it comes to computer programming and networking but I wanted to put together a website where I can post whatever I want, but I also wanted to self host my email. Can I have my website named <a href="http://www.whatever.com">www.whatever.com</a> and then would my email server be linked to the same domain? Or would it work a different way? Any good YouTube videos to watch to explain this process or books please let me know</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/effivancy"> /u/effivancy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhgddp/might_be_dumb_question_but_here_it_goes/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhgddp/might_be_dumb_question_but_here_it_goes/">[comments]</a></span>

## Best reader app with editing features
 - [https://www.reddit.com/r/selfhosted/comments/1hhfs97/best_reader_app_with_editing_features](https://www.reddit.com/r/selfhosted/comments/1hhfs97/best_reader_app_with_editing_features)
 - RSS feed: $source
 - date published: 2024-12-19T00:07:30+00:00

<!-- SC_OFF --><div class="md"><p>Currently using Google Play Books and it works well for epub, but not as well for pdfs. I tried audiobookshelf, however I can&#39;t annotate/highlight with that. </p> <p>Any recommendations for a self hosted reader (pdf, mobi, epub, etc.) that I can highlight/annotate and it saves where I left off with cross device support?</p> <p>Appreciate any insight. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/endust9"> /u/endust9 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhfs97/best_reader_app_with_editing_features/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hhfs97/best_reader_app_with_editing_features/">[comments]</a></span>

## Jellyfin, bind, ipv4 and ipv6
 - [https://www.reddit.com/r/selfhosted/comments/1hhfmp2/jellyfin_bind_ipv4_and_ipv6](https://www.reddit.com/r/selfhosted/comments/1hhfmp2/jellyfin_bind_ipv4_and_ipv6)
 - RSS feed: $source
 - date published: 2024-12-19T00:00:24+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I have set up a Jellyfin server in the following way:</p> <ul> <li>a local debian server is running Jellyfin in Docker</li> <li>On the same machine, I have set up a bind server as a master for domain name xxx.yyy <ul> <li>I have configured the master zone with jellyfin IN A XX.XX.XX.XX (I could have used a CNAME instead).</li> <li>No AAAA entries</li> <li>the only option about ipv6 is listen-on-v6 { any; };</li> <li>dig jellyfin.xxx.yyy gives me my public IPV4 address</li> </ul></li> <li>I am using apache as a proxy, using the following configuration: <a href="https://jellyfin.org/docs/general/networking/apache/">https://jellyfin.org/docs/general/networking/apache/</a></li> <li>I ran certbox to get a certificate.</li> <li>I have an Asus router behind my box: <ul> <li>It manages DHCP.</li> <li>It gives the IPV4 address of my local server as DNS server.</li> <li>It manages IPV6 as &quot;static&quot;</li> <li>I have defined two Next hops o

