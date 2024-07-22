# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## SSL certificates on LAN webservers
 - [https://www.reddit.com/r/selfhosted/comments/1e8znhc/ssl_certificates_on_lan_webservers](https://www.reddit.com/r/selfhosted/comments/1e8znhc/ssl_certificates_on_lan_webservers)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T23:23:18+00:00

<!-- SC_OFF --><div class="md"><p>I want to get rid of the &quot;your connection is not private&quot; error message. I have an AD domain with some nginx and apache webservers that I'd like to secure with SSL. Nothing is exposed to the outside, all traffic is on LAN.</p> <p>What is the best way to do this? Setup Active Directory Certificate Services? Self-sign certificates and trust via Group Policy? Any help would be greatly appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/especiallylime"> /u/especiallylime </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8znhc/ssl_certificates_on_lan_webservers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8znhc/ssl_certificates_on_lan_webservers/">[comments]</a></span>

## Questions about Nginx Proxy Manager
 - [https://www.reddit.com/r/selfhosted/comments/1e8x8go/questions_about_nginx_proxy_manager](https://www.reddit.com/r/selfhosted/comments/1e8x8go/questions_about_nginx_proxy_manager)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T21:33:29+00:00

<!-- SC_OFF --><div class="md"><p>If there's a better place to ask can you point me to the right direction. Thanks. </p> <p>I'm currently running 2 laptops both on Ubuntu Server OS. One is running Jellyfin bare metal proxied through nginx and the second is running nextcloud bare metal proxied through apache2 but since server one is already using port 443 I have to access nextcloud by going to nextcloud.mydomain.com:8080</p> <p>I watched a video about nginx proxy manager and I'm not sure if I understood right hence why I'm here but it said that you should install npm thought docker but then you have to run nextcloud through docker as well and I'm assuming Jellyfin would be the same. Here's the thing I want to keep both Jellyfin and nextcloud bare metal since it's the only way I've had the most success. It's it possible? </p> <p>Thanks in advance. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/iamwhoiwasnow"> /u/iamwhoiwasnow </a> <br /> <span><a

## Which way should I implement my scalable self-hosted WP installation with Swarm?
 - [https://www.reddit.com/r/selfhosted/comments/1e8wun3/which_way_should_i_implement_my_scalable](https://www.reddit.com/r/selfhosted/comments/1e8wun3/which_way_should_i_implement_my_scalable)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T21:16:15+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1e8wun3/which_way_should_i_implement_my_scalable/"> <img alt="Which way should I implement my scalable self-hosted WP installation with Swarm?" src="https://b.thumbs.redditmedia.com/B-ZBCXTuSNzI_lRCGCa70g1vJoFxWWIf50NQ1e_wn1E.jpg" title="Which way should I implement my scalable self-hosted WP installation with Swarm?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi! I'm currently setting up my self-hosted high availability WP installation to learn more about Docker Swarm and scaling services. Now I'm at a crossroad with 2 ways to implement and would like to hear your opinion.</p> <p>There would be about 3-5 swarm manager nodes and some amount of worker nodes. Manager nodes would host the reverse proxy and be the server users connect to. The reverse proxy would be a <code>mode: global</code> meaning there would be 1 per manager node. Worker containers could scale indefinetely.</p> <p>Option 1: Docker services

## What would you do?
 - [https://www.reddit.com/r/selfhosted/comments/1e8wryq/what_would_you_do](https://www.reddit.com/r/selfhosted/comments/1e8wryq/what_would_you_do)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T21:12:58+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://youtube.com/shorts/QDMsLb2etIU?si=jNpcFZP8mTvarIoC">https://youtube.com/shorts/QDMsLb2etIU?si=jNpcFZP8mTvarIoC</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Striking_Course9007"> /u/Striking_Course9007 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8wryq/what_would_you_do/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8wryq/what_would_you_do/">[comments]</a></span>

## Too many redirects
 - [https://www.reddit.com/r/selfhosted/comments/1e8w8gm/too_many_redirects](https://www.reddit.com/r/selfhosted/comments/1e8w8gm/too_many_redirects)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T20:49:09+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>i'm having trouble running the combo nextcloud, mariaDB and the reverse-proxy SWAG as docker containers inside unraid at home. </p> <p>Everything seems to work fine inside my network, so there are no technical issues with nextcloud and mariaDB, but when going live using swag, the browser quits with '<strong>error: too many redirects</strong>'. When checking the URL in <a href="http://redirect-checker.org">redirect-checker.org</a> a quick check of my site produces a hell lot of '<strong>301 moved permanently</strong>'. </p> <p>As <a href="https://developers.cloudflare.com/ssl/troubleshooting/too-many-redirects/">https://developers.cloudflare.com/ssl/troubleshooting/too-many-redirects/</a> states, this might be caused by SSL misconfigurations. To get this off my checklist, i need to know, how to delete an SSL certificate on a swag instance running on a docker in unraid. </p> <ul> <li>Does anyone know where this file is located exactly? </li> 

## Nextcloud necessary when you have NAS+VPN
 - [https://www.reddit.com/r/selfhosted/comments/1e8tucq/nextcloud_necessary_when_you_have_nasvpn](https://www.reddit.com/r/selfhosted/comments/1e8tucq/nextcloud_necessary_when_you_have_nasvpn)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T19:05:17+00:00

<!-- SC_OFF --><div class="md"><p>Can someone help me understand the purpose of Nextcloud if you have a NAS with a VPN? Can you access your files either way? Is it redundant to have both?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TaCoDoS2"> /u/TaCoDoS2 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8tucq/nextcloud_necessary_when_you_have_nasvpn/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8tucq/nextcloud_necessary_when_you_have_nasvpn/">[comments]</a></span>

## Manage LDAP
 - [https://www.reddit.com/r/selfhosted/comments/1e8tgnj/manage_ldap](https://www.reddit.com/r/selfhosted/comments/1e8tgnj/manage_ldap)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T18:49:02+00:00

<!-- SC_OFF --><div class="md"><p>I've seen a new rash of &quot;should I use an individual database per service or a single database per network&quot; &amp; personally I tried the shared database and prefer one per service. But all this got me thinking about LDAP.</p> <p>The whole idea with LDAP is that it's unified, so the one per service doesn't work the same way it does for databases....unless they can be kept in sync.</p> <p>I'm curious how those of you who use LDAP handle this aspect of it. Is it firewalled off on a VLAN? Do you gave a local instance?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Psychological_Try559"> /u/Psychological_Try559 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8tgnj/manage_ldap/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8tgnj/manage_ldap/">[comments]</a></span>

## Making progress with my Dashboard using Homepage, still need some arrangements.
 - [https://www.reddit.com/r/selfhosted/comments/1e8t7ds/making_progress_with_my_dashboard_using_homepage](https://www.reddit.com/r/selfhosted/comments/1e8t7ds/making_progress_with_my_dashboard_using_homepage)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T18:37:45+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1e8t7ds/making_progress_with_my_dashboard_using_homepage/"> <img alt="Making progress with my Dashboard using Homepage, still need some arrangements." src="https://b.thumbs.redditmedia.com/xuh3NBhoS42J9fL-swPHtbkl1uJ9HeIB6mO2XRL_krQ.jpg" title="Making progress with my Dashboard using Homepage, still need some arrangements." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/giorivpad"> /u/giorivpad </a> <br /> <span><a href="https://www.reddit.com/gallery/1e8t7ds">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8t7ds/making_progress_with_my_dashboard_using_homepage/">[comments]</a></span> </td></tr></table>

## Email Proxy Recommendations
 - [https://www.reddit.com/r/selfhosted/comments/1e8sjnb/email_proxy_recommendations](https://www.reddit.com/r/selfhosted/comments/1e8sjnb/email_proxy_recommendations)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T18:09:59+00:00

<!-- SC_OFF --><div class="md"><p>Hi. I’m looking for a self hosted solution for offloading a paid email account. I only have 50Mb of space, and unfortunately I cannot change that, but I really need to keep the address. Could someone recommend me a solution where my homelab server would download all emails from an IMAP account and delete them from there? And maybe forward all emails I send, to have a complete utility and only use one address? </p> <p>Thanks a lot! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Successful_Ad7206"> /u/Successful_Ad7206 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8sjnb/email_proxy_recommendations/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8sjnb/email_proxy_recommendations/">[comments]</a></span>

## Cheapest way to make a website? (domain/email/web builder)
 - [https://www.reddit.com/r/selfhosted/comments/1e8s79v/cheapest_way_to_make_a_website_domainemailweb](https://www.reddit.com/r/selfhosted/comments/1e8s79v/cheapest_way_to_make_a_website_domainemailweb)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T17:56:22+00:00

<!-- SC_OFF --><div class="md"><p>Hello!! I am an artist who is looking to expand beyond twitter commissions and i would love to have a website with a newsletter.<br /> Im looking into options right now, and i was wondering if anyone here knows what the best combination of cheap domain + a business email + website builder is?</p> <p>Im currently using carrd (free) for my site. i could upgrade to pro for $19/year, buy a domain and connect it to carrd and get a business email to use Sender (generous free plan) to start a newsletter, im missing a few puzzle pieces, or if anyone knows a better way to do this please let me know! thank you :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fair_Prize2787"> /u/Fair_Prize2787 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8s79v/cheapest_way_to_make_a_website_domainemailweb/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8s79v/cheapest_way

## Update to Self-Hosted Webscraper "Scraperr"
 - [https://www.reddit.com/r/selfhosted/comments/1e8ryua/update_to_selfhosted_webscraper_scraperr](https://www.reddit.com/r/selfhosted/comments/1e8ryua/update_to_selfhosted_webscraper_scraperr)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T17:46:00+00:00

<!-- SC_OFF --><div class="md"><p>I have added a large amount of requested features to the self-hosted webscraper &quot;Scraperr&quot;. In this new update, I have added:</p> <ul> <li>Multi-page scraping (within same domain of original link)</li> <li>Custom JSON headers (will override headers of request with entered headers in JSON format)</li> <li>Queuing system, with separation of scraper and API, for interacting with previous jobs and logs while scraping jobs run</li> <li>UI updates</li> <li>View container logs inside of the Web UI via the &quot;View Logs&quot; page</li> </ul> <p>The multi page scraping system will take longer, simply because there are more links to scrape, and there will most likely be lots of bugs in this, please fill out an issue if you encounter one.</p> <p><a href="https://github.com/jaypyles/Scraperr">https://github.com/jaypyles/Scraperr</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bluesanoo"> /u/bluesanoo </a> <br

## Anyone self hosting with T-Mobile home Internet gateway as an ISP?
 - [https://www.reddit.com/r/selfhosted/comments/1e8rhl7/anyone_self_hosting_with_tmobile_home_internet](https://www.reddit.com/r/selfhosted/comments/1e8rhl7/anyone_self_hosting_with_tmobile_home_internet)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T17:24:42+00:00

<!-- SC_OFF --><div class="md"><p>I really love the monthly price but because it's so locked down I feel like I'm unable to do any personal projects. I'm wondering if anyone else is using T-Mobile as a home Internet provider and also self hosting. Id love to find out there's just some setting or passthrough I need to enable but I fear it's simply not possible with the way T-Mobile configures their gnet? </p> <p>My current frustration is trying to setup a home server. I'm trying to setup a zimaboard and the initial setup goes as expected but the app store doesn't have Internet access, I can't check for updates and I don't have an IP address when I check from command line. </p> <p>The instructions for it are to basically plug and play to get to the app store so something must be wrong. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/soggyGreyDuck"> /u/soggyGreyDuck </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8rhl7/any

## I am creating "My Own Web Services" to make self-hosting reliable cloud systems as well as applications installation and app development easier for everybody.
 - [https://www.reddit.com/r/selfhosted/comments/1e8qrjh/i_am_creating_my_own_web_services_to_make](https://www.reddit.com/r/selfhosted/comments/1e8qrjh/i_am_creating_my_own_web_services_to_make)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T16:52:49+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone!</p> <p>I am creating an open-source project that aims to fix many of the difficulties of self-hosting, making it easier for everyone to reliably self-host their online presence, E-Mail, website, password manager, media library and much more.</p> <p>There are many projects that have similar goals, but none of them do fit my requirements for various reasons.</p> <p>One of the reasons is that most of these projects rely on docker-compose running on a single machine that can break at any time. Even if you like to put your Sysadmin hat on and love to troubleshoot boot drive failures and other stuff in your free time, the day will come that you are on vacation or otherwise busy and your system breaks, shutting down your whole IT infrastructure that you and others may rely on, if you are treating your self-hosted system as anything other than an experimental home-lab. </p> <p>Inspired by [<a href="/u/geerlingguy">u/geerlingguy</a>](), [<a href="

## Open source budget manager (Budget5S), container-ready, ReactJS/NodeJS/MongoDB
 - [https://www.reddit.com/r/selfhosted/comments/1e8q86r/open_source_budget_manager_budget5s](https://www.reddit.com/r/selfhosted/comments/1e8q86r/open_source_budget_manager_budget5s)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T16:28:35+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1e8q86r/open_source_budget_manager_budget5s/"> <img alt="Open source budget manager (Budget5S), container-ready, ReactJS/NodeJS/MongoDB" src="https://b.thumbs.redditmedia.com/mKQCBgXbjLoJ0aUlctND-qw5PAD0lcDc5kx0prjp9WA.jpg" title="Open source budget manager (Budget5S), container-ready, ReactJS/NodeJS/MongoDB" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/mia3zkaafwdd1.png?width=2235&amp;format=png&amp;auto=webp&amp;s=bc3d215eaf3bf2cc53f73ee271ea3c25e4a62958">Budget5S</a></p> <p><strong>Hello !</strong></p> <p>I've been following the reddit for 2 years, to build my homelab and I'd like to thank the community for their precious advice! I'm just a silent redditor but today I'm creating this post to present you a project, which was made first to meet my needs in terms of ergonomics or functionality, the project is in alpha completely open-source, container-ready, and the pride of 

## Windows local manga and audio book hosting help
 - [https://www.reddit.com/r/selfhosted/comments/1e8pvoi/windows_local_manga_and_audio_book_hosting_help](https://www.reddit.com/r/selfhosted/comments/1e8pvoi/windows_local_manga_and_audio_book_hosting_help)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T16:13:05+00:00

<!-- SC_OFF --><div class="md"><p>My server is using windows and I access it all from my iphone. I have plex which is running great so far.</p> <p>Im looking for something to host on my local server for audio books and manga/manhwa. Id like to download from a gui the manga that I want and get updates on new chapters. I currently have kativa downloaded and the interface is great, but im completely oblivious to its setup and how to download manga for it or access it from my phone.</p> <p>Audio books im not sure on at all, ive got audible currently and that interface is great. If theres something similar to that and can be hosted and accessed outside the house it would be a win!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kevinchronicles"> /u/kevinchronicles </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8pvoi/windows_local_manga_and_audio_book_hosting_help/">[link]</a></span> &#32; <span><a href="https://www.reddit.co

## Offline-only note taking application with PDF (or similar) export functionality.
 - [https://www.reddit.com/r/selfhosted/comments/1e8pqbw/offlineonly_note_taking_application_with_pdf_or](https://www.reddit.com/r/selfhosted/comments/1e8pqbw/offlineonly_note_taking_application_with_pdf_or)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T16:06:31+00:00

<!-- SC_OFF --><div class="md"><p>I'm looking for a note taking application I can host locally (obviously) with no network or cloud functionality - not interested in my notes being stored anywhere other than my network. I would also like to be able to export the notes to another file type for backup.</p> <p>Solutions I've looked at:</p> <p>Obsidian - Concerned about the Sync function. Does the free version connect to their servers in any way?</p> <p>Trilium - Active development ceased. Export to PDF seems to be printing the page to PDF rather than an actual export function?</p> <p>Outline - I know it has a cloud component, is the self-hosted version completely isolated from this? Other than that, I don't hear this one talked about as much.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SuperRobotPimpJesus"> /u/SuperRobotPimpJesus </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8pqbw/offlineonly_note_taking_application_w

## XMPP transport
 - [https://www.reddit.com/r/selfhosted/comments/1e8pc01/xmpp_transport](https://www.reddit.com/r/selfhosted/comments/1e8pc01/xmpp_transport)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T15:49:31+00:00

<!-- SC_OFF --><div class="md"><p>Hello, for privacy reasons I am quite reluctant to using such instant messaging apps as Whatsapp. So I have set up my own XMPP/Jabber server to communicate with my family. Now I am considering opening myself (a little) to the outside world with the help of XMPP transport Slidge.</p> <p>Has anyone of you any experience with it, setting it up, using it ? I have given a look at the documentation but it is quite minimal and I hardly understand how to have it to work. I would set it up with Docker, on the same Docker network as my Jabber install. I am interested in Telegram and Whatsapp transports.</p> <p>Any one of you might be of help ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Eirikr700"> /u/Eirikr700 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8pc01/xmpp_transport/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8pc01/xmpp_transport/">[comm

## Scan/index documents
 - [https://www.reddit.com/r/selfhosted/comments/1e8oxsx/scanindex_documents](https://www.reddit.com/r/selfhosted/comments/1e8oxsx/scanindex_documents)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T15:31:43+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I'm looking for something to host that can enable documents (probably PDFs) held in a CIFS share, to be ingested, then OCR or similar to be used to detect keywords and other metadata that could be then used to store the PDF permanently with the ability to search/display in categories. An example would be that I might store my electricity bills and bank statements in pdf format, hand side want the application to provide a way to store each in their own specific electricity bill and bank statements folder with the ability to search by date for instance. Has anybody got any suggestions please, based on experience? I've looked in the past things like paperless-ngx. For some reason I couldn't figure out how to properly get it up and running. For info in case this affects any suggestions, I currently run a multi-node Proxmox VM environment on HP DLP360p hardware with NFS to 2x custom storage servers (TrueNAS Scale) with plenty of space. I already have v

## Sata cable connector for mini pc
 - [https://www.reddit.com/r/selfhosted/comments/1e8ox35/sata_cable_connector_for_mini_pc](https://www.reddit.com/r/selfhosted/comments/1e8ox35/sata_cable_connector_for_mini_pc)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T15:30:48+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1e8ox35/sata_cable_connector_for_mini_pc/"> <img alt="Sata cable connector for mini pc" src="https://preview.redd.it/gi80smrv4wdd1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=4f87e3bd9e7d92aafba4b1d9560a18e7e4e95391" title="Sata cable connector for mini pc" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>So i have a mini pc and i want to upgrade it with an ssd its the GB-BRi5H-8250 (rev. 1.0)(<a href="https://www.gigabyte.com/Mini-PcBarebone/GB-BRi5H-8250-rev-10#ov">https://www.gigabyte.com/Mini-PcBarebone/GB-BRi5H-8250-rev-10#ov</a>)</p> <p>On the site it says it can be upgrade with either a ssd or a hdd. This mini pc does not have the standard sata port and will need something i think is a sata ribbon cable. My question is where can i Get it. I live in Europe and i find stuff like ASUS P1412CEA/X415EA HDD FFC 0,5 mm L101-kabel but it is a spare part for laptops notebook series so what cable and where sh

## Selfhosted Database between multiple services
 - [https://www.reddit.com/r/selfhosted/comments/1e8ogmp/selfhosted_database_between_multiple_services](https://www.reddit.com/r/selfhosted/comments/1e8ogmp/selfhosted_database_between_multiple_services)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T15:10:22+00:00

<!-- SC_OFF --><div class="md"><p>I have been selfhosting a lot of stuff using Docker composes, but generally they are quite &quot;self contained&quot;.</p> <p>I want to understand best practices when it comes to Databases, and how I can share a database service between other services, as an example:</p> <p>Scrutiny, Tandoor, Mealie and Romm. </p> <p>From what I can tell, both Tandoor and Mealie use Postgres, while the other two use different Database options (MariaDb and InfluxDb?).</p> <p>Can Tandoor and Mealie both use the same Postgres container and volume?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/frasderp"> /u/frasderp </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8ogmp/selfhosted_database_between_multiple_services/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8ogmp/selfhosted_database_between_multiple_services/">[comments]</a></span>

## Is there any free subdomain websites that allow connect to Google sites verification?
 - [https://www.reddit.com/r/selfhosted/comments/1e8nzmr/is_there_any_free_subdomain_websites_that_allow](https://www.reddit.com/r/selfhosted/comments/1e8nzmr/is_there_any_free_subdomain_websites_that_allow)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T14:49:08+00:00

<!-- SC_OFF --><div class="md"><p>I've tried noip and duck dns and none of them allow me to input the dns that Google gives me.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Far-Veterinarian-208"> /u/Far-Veterinarian-208 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8nzmr/is_there_any_free_subdomain_websites_that_allow/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8nzmr/is_there_any_free_subdomain_websites_that_allow/">[comments]</a></span>

## "Smart Money" Idle Tapping Game Alpha Version
 - [https://www.reddit.com/r/selfhosted/comments/1e8nyuz/smart_money_idle_tapping_game_alpha_version](https://www.reddit.com/r/selfhosted/comments/1e8nyuz/smart_money_idle_tapping_game_alpha_version)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T14:48:11+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1e8nyuz/smart_money_idle_tapping_game_alpha_version/"> <img alt="&quot;Smart Money&quot; Idle Tapping Game Alpha Version" src="https://b.thumbs.redditmedia.com/77wW1kKKwODXh2y_5NWA5CeYckXWY1Qjxgyrzba8itk.jpg" title="&quot;Smart Money&quot; Idle Tapping Game Alpha Version" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey!</p> <p>I currently help out some friends with their just released selfhosted Alpha version of their Idle game. I hope it´s ok to post it here. It´s somewhat similar to Hamster Kombat, only with far less budget but with a real human designer and a really cool, motivating story and a lot of features planed for the Beta, e.g. blockchain connection, AI-based business incidents that make the game experience unique to each single player and some other blockchain related feats. The current version is just a first playable &quot;Hello&quot; to the world. It´s build with Unity and Firebase database i

## Reverse Proxies
 - [https://www.reddit.com/r/selfhosted/comments/1e8nqw7/reverse_proxies](https://www.reddit.com/r/selfhosted/comments/1e8nqw7/reverse_proxies)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T14:38:00+00:00

<!-- SC_OFF --><div class="md"><p>What reverse proxy is everyone here using ? I had been using Nginx Proxy Manager but after reading they could fall behind on updates moved over to traefik and after some fits and starts last night got it running. Still learning it, was just curious what everyone else is doing. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Friendly_Ground_51"> /u/Friendly_Ground_51 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8nqw7/reverse_proxies/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8nqw7/reverse_proxies/">[comments]</a></span>

## Started Self Hosted setup (NAS+docker) - suggestions for remote access use cases?
 - [https://www.reddit.com/r/selfhosted/comments/1e8nftw/started_self_hosted_setup_nasdocker_suggestions](https://www.reddit.com/r/selfhosted/comments/1e8nftw/started_self_hosted_setup_nasdocker_suggestions)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T14:23:20+00:00

<!-- SC_OFF --><div class="md"><p>I am just getting started with Self Hosting my development / internal tooling. I have a few specific use cases that I'm currently road blocked on for making this work 100% for me. What does everyone use for being able to access Data / Remote Desktop / SSH / internal web apps , that is self hosted and usable from laptop / phone (if possible)</p> <p>Setup:<br /> NAS:</p> <ul> <li>vaultwarden<br /></li> <li>portainer (runs all my containers)<br /></li> <li>AdGuard<br /></li> <li>Overseer<br /></li> <li>radarr / sonarr / etc<br /></li> <li>watchtower<br /></li> <li>nzbget<br /></li> <li><p>cloudflared (CF tunnel client to serve Overseer for friends and family)</p></li> <li><p>postgresql </p></li> <li><p>mongodb </p></li> <li><p>37 ish custom containers (development project work)</p></li> </ul> <p>Public Exposure:<br /> - Overseer - CF Tunnel<br /> - Portainer - CF Tunnel ( this scares me but needed to try and test remotely)</p> <p>Use Case 1:</p> <p>I am 

## How you use the 3-2-1 backup method
 - [https://www.reddit.com/r/selfhosted/comments/1e8mzbh/how_you_use_the_321_backup_method](https://www.reddit.com/r/selfhosted/comments/1e8mzbh/how_you_use_the_321_backup_method)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T14:00:47+00:00

<!-- SC_OFF --><div class="md"><p>I’m curious how everyone handles their backups. 3 copies. 2 media types. 1 offsite. I have my main NAS that mirrors itself to an offsite backup which then takes snapshots of the mirrored data at certain times. (Just for ease of mind). For my third copy of the data, I plug in an external drive to my local NAS and then run a script that creates an archive of the data on the nas over to the external drive. this is the only part that i don't have automated and plugging and unplugging a drive when I do this is getting a little old. What do you guys use for all your backup and how is it setup? I will still most likely copy backups to the offline external drive, when I get the 3rd backup media automated just to have an offline, no internet, copy, but that would then become less often. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RealJoshLee0"> /u/RealJoshLee0 </a> <br /> <span><a href="https://www.reddit.com/r/selfh

## Photo Viewer/App for *very private* photos
 - [https://www.reddit.com/r/selfhosted/comments/1e8m93r/photo_viewerapp_for_very_private_photos](https://www.reddit.com/r/selfhosted/comments/1e8m93r/photo_viewerapp_for_very_private_photos)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T13:24:11+00:00

<!-- SC_OFF --><div class="md"><p>My spouse and I would like to start taking and sharing some very private photos between ourselves, of us, if you know what I mean. We already utilize Synology photos for our regular family stuff, but I’d like to use a different app for these in order to maintain separation, so they aren’t accidentally exposed when showing someone family photos. Obviously these will be in a separate encrypted share on the Synology NAS. What’s a good self hosted service/app to view them? Photo Prism, something else? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Signal_Inside3436"> /u/Signal_Inside3436 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8m93r/photo_viewerapp_for_very_private_photos/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8m93r/photo_viewerapp_for_very_private_photos/">[comments]</a></span>

## P100 GPU - keep or not?
 - [https://www.reddit.com/r/selfhosted/comments/1e8lkno/p100_gpu_keep_or_not](https://www.reddit.com/r/selfhosted/comments/1e8lkno/p100_gpu_keep_or_not)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T12:48:48+00:00

<!-- SC_OFF --><div class="md"><p>I've got my hand on HP Proliant Gen9 with 2x Nvidia Tesla P100 GPUs (16GB vRAM) - it will arrive within few days.</p> <p>Purpose is to play with using (not training) AI models (ollama + open webUI etc) </p> <p>I want to play with it, maybe code automation agents, funny tools, etc. Just to learn and share with friends.</p> <p>Are this P100 any good? Or better to not waste my time to try to run stuff on them - sell them and buy single used RTX 4070 12GB (and maybe later next one)?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MsWadera"> /u/MsWadera </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8lkno/p100_gpu_keep_or_not/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8lkno/p100_gpu_keep_or_not/">[comments]</a></span>

## Managing YouTube subscriptions via GitHub and Miniflux
 - [https://www.reddit.com/r/selfhosted/comments/1e8kgmb/managing_youtube_subscriptions_via_github_and](https://www.reddit.com/r/selfhosted/comments/1e8kgmb/managing_youtube_subscriptions_via_github_and)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T11:44:54+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1e8kgmb/managing_youtube_subscriptions_via_github_and/"> <img alt="Managing YouTube subscriptions via GitHub and Miniflux" src="https://external-preview.redd.it/GvywykUg9xDflgo10ANLxAd5rB4yM9GP1J9kStZmHjY.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=7cb4f5d8f3ad422e4ef1163a33bce8101bda8ce5" title="Managing YouTube subscriptions via GitHub and Miniflux" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mpcjuq23"> /u/mpcjuq23 </a> <br /> <span><a href="https://revcd.com/managing-youtube-subscriptions-via-github-miniflux">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8kgmb/managing_youtube_subscriptions_via_github_and/">[comments]</a></span> </td></tr></table>

## selfhosted youth camp registration and data management software
 - [https://www.reddit.com/r/selfhosted/comments/1e8kepp/selfhosted_youth_camp_registration_and_data](https://www.reddit.com/r/selfhosted/comments/1e8kepp/selfhosted_youth_camp_registration_and_data)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T11:41:35+00:00

<!-- SC_OFF --><div class="md"><p>Every year my wife organizes a camp for children through a voluntary organization. For this I am looking for a self-hosted software that can do the following:</p> <ol> <li>Registration form</li> </ol> <ul> <li>individual fields and text</li> </ul> <ol> <li>Address list of parents</li> <li>E-mail distribution list / list of parents</li> <li>Participant list of children with special features</li> </ol> <ul> <li>Gender</li> <li>age</li> <li>Allergies</li> <li>Medication</li> <li>Ability to swim</li> <li>Food specialties (vegan, gluten-free, ...)</li> </ul> <p>It would be great if you could confirm or reject registrations manually, and if this is also visible. A todo list would also be great, as well as a task distribution of the supervisors. It's all about registration, data management and organization.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pendenz"> /u/pendenz </a> <br /> <span><a href="https://www.reddit

## Need advice on what service to host for showing pictures and videos on my family members' phone from my NAS
 - [https://www.reddit.com/r/selfhosted/comments/1e8jgyo/need_advice_on_what_service_to_host_for_showing](https://www.reddit.com/r/selfhosted/comments/1e8jgyo/need_advice_on_what_service_to_host_for_showing)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T10:40:58+00:00

<!-- SC_OFF --><div class="md"><p>I have a NAS with pictures and videos. I would like my family members to access them in a way that is user friendly (until now I made them install a SMB client app, but it's not too easy to use nor very secure from outside the LAN). Bonus would be facial recognition. </p> <p>So the options are as always Immich, Photoprism and Nextcloud memories, but afaik they all need media to be imported (copied) in their database, and cannot read directly from the NAS' folders. Did I understand correctly? What would you suggest me to do?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/NatSpaghettiAgency"> /u/NatSpaghettiAgency </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8jgyo/need_advice_on_what_service_to_host_for_showing/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8jgyo/need_advice_on_what_service_to_host_for_showing/">[comments]</a></span>

## Apache or Nginx?
 - [https://www.reddit.com/r/selfhosted/comments/1e8iv48/apache_or_nginx](https://www.reddit.com/r/selfhosted/comments/1e8iv48/apache_or_nginx)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T09:58:02+00:00

<!-- SC_OFF --><div class="md"><p>I'm, rebuilding my homelab and have come to my webserver currently running Apache but I want opnions on which one should I go for. </p> <p>my main use case is serving 10 websites of which have 4 have video streams and file downloads. traffic is about 20 to 30 people. 4 sites about 10k per day. I'll also being running another instace as a reverse proxy/load balancer</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ScatletDevil25"> /u/ScatletDevil25 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8iv48/apache_or_nginx/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8iv48/apache_or_nginx/">[comments]</a></span>

## Advice/Suggestions for Noob
 - [https://www.reddit.com/r/selfhosted/comments/1e8imao/advicesuggestions_for_noob](https://www.reddit.com/r/selfhosted/comments/1e8imao/advicesuggestions_for_noob)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T09:39:36+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I just bought my first server earlier this month, (VPS from Digital Ocean) that's running Debian and I'm in the process of learning everything backend. For context, I have 11+ years of front end experience, but absolutely no experience working backend and little experience with Linux. I've used it before, but very seldomly. </p> <p>I'm using the server for a bit of everything, currently have a node server (for node.js) and an Apache server for my websites. I have ufw installed and enabled, trying to figure out fail2ban still. I have it setup for SSH authentications (I think) and I also have a vncserver installed, I have XFCE4 GUI installed for easier navigation. My end goal is to get into developing tools for front end developers that don't have access to a backend or just simply don't want to learn it.</p> <p>My concern is, since I'm entirely new to this I barely know what I'm doing. After very thorough research, I've gotten everything wor

## New in Selfhosting Game
 - [https://www.reddit.com/r/selfhosted/comments/1e8ifpe/new_in_selfhosting_game](https://www.reddit.com/r/selfhosted/comments/1e8ifpe/new_in_selfhosting_game)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T09:25:56+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, </p> <p>I'm new to the game and just starting out with self-hosting. I want to give up my M365 infrastructure and just run everything at home. I have a small Proxmoxx server with a virtualized OPNsense, a Raspberry PI 4 that I turned into an openmediavault, another Pi and my MacBook that I virtualize with. PiHole has also been rolled out. What did you start with or continue with, somehow I'm lacking ideas right now. Do you have any input for me? Oh yes, I have Vaultwarden Password Manager. </p> <p>Thank you in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Select-Peanut549"> /u/Select-Peanut549 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8ifpe/new_in_selfhosting_game/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8ifpe/new_in_selfhosting_game/">[comments]</a></span>

## Free 6-Month of RepoFlow – Cloud Now, Self-Hosted in a Week!
 - [https://www.reddit.com/r/selfhosted/comments/1e8hoj0/free_6month_of_repoflow_cloud_now_selfhosted_in_a](https://www.reddit.com/r/selfhosted/comments/1e8hoj0/free_6month_of_repoflow_cloud_now_selfhosted_in_a)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T08:29:43+00:00

<!-- SC_OFF --><div class="md"><p>Hi Guys!</p> <p>After years of dealing with package management solutions like Artifactory and Nexus, I found myself unsatisfied with their complexity and lack of user-friendliness. So, I decided to embark on a journey to create something better: RepoFlow.</p> <p>What's RepoFlow?</p> <p>RepoFlow is an easy-to-use package management platform designed to be a simpler, more intuitive alternative to existing solutions. Whether you're managing npm, PyPI, Maven, NuGet, Docker packages, or even Go modules and Helm charts, RepoFlow aims to make the process straightforward and efficient.</p> <p>Why Choose RepoFlow?</p> <ul> <li>Simple and Great User Experience: RepoFlow is designed with simplicity and ease of use in mind, making it accessible for everyone from beginners to experts.</li> <li>Package Validation on Upload: Ensure the integrity and reliability of your packages with our robust validation process during uploads.</li> <li>Enhanced Search: Our powerful

## Truenas and Nextcloud on Proxmox
 - [https://www.reddit.com/r/selfhosted/comments/1e8gawy/truenas_and_nextcloud_on_proxmox](https://www.reddit.com/r/selfhosted/comments/1e8gawy/truenas_and_nextcloud_on_proxmox)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T06:52:06+00:00

<!-- SC_OFF --><div class="md"><p>Currently working on replacing a dual NUC with ESX and a 8 bay QNAP NAS for one big homelab server.</p> <p>The new server will be running Proxmox, mainly for the lab VM's.<br /> Proxmox runs from a sSATA controller. VM's will be stored on a dual NVME setup. </p> <p>Of course I still need NAS functionality, so I want to run Truenas in a VM with PCIe passthrough of the (second) builtin SATA controller (using ZFS).</p> <p>So far so good and quite straightforward.</p> <p>Next, for the userdata.<br /> Mainly for easy file sync (Qsync alternative) and mobile support I want to run Nextcloud.</p> <p>Since Truenas stopped supporting TrueCharts (May 30, 2024) running Nextcloud inside Truenas cannot be done (and might aswell be a bad idea anyway).</p> <p>Installing Nextcloud in LXC is easy and works very nice.<br /> But I'm struggling with the location of the userdata. </p> <p>I would like to have all data inside Truenas (using the passthrough SATA Controller wi

## A/B experimentation framework
 - [https://www.reddit.com/r/selfhosted/comments/1e8g2g8/ab_experimentation_framework](https://www.reddit.com/r/selfhosted/comments/1e8g2g8/ab_experimentation_framework)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T06:35:45+00:00

<!-- SC_OFF --><div class="md"><p>What are some of the latest recommended self-hosted open source A/B experimentation framework?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/spsneo"> /u/spsneo </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8g2g8/ab_experimentation_framework/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8g2g8/ab_experimentation_framework/">[comments]</a></span>

## Power efficient system build for managing servers and also daily usage
 - [https://www.reddit.com/r/selfhosted/comments/1e8ftvp/power_efficient_system_build_for_managing_servers](https://www.reddit.com/r/selfhosted/comments/1e8ftvp/power_efficient_system_build_for_managing_servers)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T06:20:05+00:00

<!-- SC_OFF --><div class="md"><p>Hey redditors, I'm running a xpenology nas on my old pc running i5 7400 and also running proxmox on n100 mini pc(which i planned to transfer jellyfin from xpenology), i also owned a gaming pc with ryzen 5 5600 and rtx 2060s, Currently if i want to manage servers or even just browsing internet, i have to use my gaming pc which consumes lot of electricity,i recorded around 90w plus in normal usage. </p> <p>My question is what system is power efficient just for daily normal usage and managing servers(through browser)... I already own kvm which so i can switch between gaming pc and suggested system... </p> <p>Edit: i don't mind if it's old system, in fact i preferred used due to low cost in used market, as long as its power efficient, something like celeron, as long as it should be good enough for normal browsing... Thank you </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/noname9412"> /u/noname9412 </a> <br /> <spa

## I made a one-page comprehensive dashboard using Fitbit API, influxdb, and Grafana. Code and setup instructions are available in the comments.
 - [https://www.reddit.com/r/selfhosted/comments/1e8fi68/i_made_a_onepage_comprehensive_dashboard_using](https://www.reddit.com/r/selfhosted/comments/1e8fi68/i_made_a_onepage_comprehensive_dashboard_using)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T05:58:40+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1e8fi68/i_made_a_onepage_comprehensive_dashboard_using/"> <img alt="I made a one-page comprehensive dashboard using Fitbit API, influxdb, and Grafana. Code and setup instructions are available in the comments." src="https://preview.redd.it/ox9nyqknatdd1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=feb0e2f5a616feed91225308e4e3097ae251aa3c" title="I made a one-page comprehensive dashboard using Fitbit API, influxdb, and Grafana. Code and setup instructions are available in the comments." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/arpandesign"> /u/arpandesign </a> <br /> <span><a href="https://i.redd.it/ox9nyqknatdd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8fi68/i_made_a_onepage_comprehensive_dashboard_using/">[comments]</a></span> </td></tr></table>

## Self hosted watch together movies
 - [https://www.reddit.com/r/selfhosted/comments/1e8f3a8/self_hosted_watch_together_movies](https://www.reddit.com/r/selfhosted/comments/1e8f3a8/self_hosted_watch_together_movies)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T05:30:53+00:00

<!-- SC_OFF --><div class="md"><p>My friend and I have been using Plex to 'watch together' when it comes to movies, TV show's, etc. He has all the same video files that I do (in fact I transfer them to his server) but there's no easy way to watch together. Plex has this feature and we like it because you can pause when you want to go get snacks, or there's some interruption, etc. But 'watch together' in Plex is buggy, at best. We've had to make sure we're running the same version of Plex (he's running Plex on Windows, I'm running Plex on Linux) and double check all of our settings just to get it to work. And even then it's hit or miss sometimes. He's got a connection that should allow 10mb upstream, and I've got a DSL connection that should allow the same. But we still run into issues sometimes.</p> <p>Is there anything better? Say for example we want to stream the same 4k movie. We both have the file, we just need some way to 'sync' what we are watching. And have the ability to pause

## selfhost code-server, but can not get https working
 - [https://www.reddit.com/r/selfhosted/comments/1e8eoop/selfhost_codeserver_but_can_not_get_https_working](https://www.reddit.com/r/selfhosted/comments/1e8eoop/selfhost_codeserver_but_can_not_get_https_working)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T05:04:47+00:00

<!-- SC_OFF --><div class="md"><p>HI folks, need some help here?</p> <p>so i have a ubuntu server, installed code-server through official script, running fine on port 7001, i have pi-hole dns point example and <a href="http://example.com">example.com</a> to server ip, so i can access code-server through example:7001, when i am away from home, i can access through tailscale (tailscale magic dns point example to the ubuntu server too).</p> <p>Now i try to set up https for code-server, so i followed this <a href="https://medium.com/@elysiumceleste/setting-up-a-secure-self-signed-ssl-certificate-for-code-server-on-ios-13-and-macos-10-15-294a1437cc4c">tutorial</a> to generate cert and key and systemctl restart code-server, but when i load it through <a href="http://example.com:7001">example.com:7001</a>, the browser still complains, i &quot;proceed anyway&quot; but there is still issue opening, for example, .ipynb file, &quot;error: Could not register service worker: SecurityError: Failed 

## Extremely barebones issue/feature/ticket tracker
 - [https://www.reddit.com/r/selfhosted/comments/1e8dpyy/extremely_barebones_issuefeatureticket_tracker](https://www.reddit.com/r/selfhosted/comments/1e8dpyy/extremely_barebones_issuefeatureticket_tracker)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T04:04:17+00:00

<!-- SC_OFF --><div class="md"><p>Anyone know of a barebones issue/ticket system? No fancy UI or backend. Just plain HTML.</p> <p>Edit: Also note that it should be able to work as a public facing service.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bbb23sucks"> /u/bbb23sucks </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8dpyy/extremely_barebones_issuefeatureticket_tracker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8dpyy/extremely_barebones_issuefeatureticket_tracker/">[comments]</a></span>

## What is your preferred streaming device?
 - [https://www.reddit.com/r/selfhosted/comments/1e8dcpl/what_is_your_preferred_streaming_device](https://www.reddit.com/r/selfhosted/comments/1e8dcpl/what_is_your_preferred_streaming_device)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T03:42:10+00:00

<!-- SC_OFF --><div class="md"><p>Those of you who watch content(self-hosted or otherwise), what's your preferred device?</p> <p><a href="https://www.reddit.com/poll/1e8dcpl">View Poll</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/notdoreen"> /u/notdoreen </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8dcpl/what_is_your_preferred_streaming_device/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8dcpl/what_is_your_preferred_streaming_device/">[comments]</a></span>

## Rebuilt my homelab... fun :)
 - [https://www.reddit.com/r/selfhosted/comments/1e8cuyk/rebuilt_my_homelab_fun](https://www.reddit.com/r/selfhosted/comments/1e8cuyk/rebuilt_my_homelab_fun)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T03:12:59+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1e8cuyk/rebuilt_my_homelab_fun/"> <img alt="Rebuilt my homelab... fun :)" src="https://b.thumbs.redditmedia.com/aSFQreAKej-Ru2Yk_JRTjh6iMTfAeMFNBLEGyHSpbEo.jpg" title="Rebuilt my homelab... fun :)" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>So, finally got around to rebuilding my homelab after my old Mac Mini VMware Host decided it was time to stop working..</p> <p>I went with a HP Z440 Pro Workstation with 14 Xeon Cores (28 Logical CPU's), 64GB RAM, and 1TB SSD... will upgrade it with a 2TB NVMe and likely add some extra RAM, as its a little sluggish with all these VMs. Proxmox v8 is running on it, and then an array of Container Platforms (Docker and Kubernetes)... why you ask? So i can play with Portainer managing them all... </p> <p>Proxmox takes a while to get used to when you have spent 20 years working with VMware, but hey, its close enough.</p> <p>Forgot how much I love messing with this stuff.</p> 

## Sms gateway
 - [https://www.reddit.com/r/selfhosted/comments/1e8cp9n/sms_gateway](https://www.reddit.com/r/selfhosted/comments/1e8cp9n/sms_gateway)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T03:03:51+00:00

<!-- SC_OFF --><div class="md"><p>Im trying to setup a sms gateway that has smpp. Im using a service that sends alerts via sms. But i need a provider for this. But id rather setup my own gateway for the provider to connect to me.</p> <p>Ive looked around and see a few. But im unsure if what im wanting to do can be done?</p> <p>Looks like i can get a modem and a sim card to proceed?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/brad2388"> /u/brad2388 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8cp9n/sms_gateway/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8cp9n/sms_gateway/">[comments]</a></span>

## I purchased a new VPS with Ubuntu 24.04, can I use YUNOHOST and another self hosting service like Cloudron or Easypanel?
 - [https://www.reddit.com/r/selfhosted/comments/1e8bu4r/i_purchased_a_new_vps_with_ubuntu_2404_can_i_use](https://www.reddit.com/r/selfhosted/comments/1e8bu4r/i_purchased_a_new_vps_with_ubuntu_2404_can_i_use)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T02:15:49+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone!</p> <p>I have 1 VPS already I been using for a year using just YUNOHOST but I purchased another separate VPS with just a Ubuntu server currently self hosting with Easypanel.</p> <p>Since the new VPS has Ubuntu server on it, can I install YUNOHOST along side of Easypanel? </p> <p>Easypanel is like a docker type container while YUNOHOST is completely different, not sure if they will conflict or possibly use the same resources. Anybody done this or currently doing this please share with me your experience's, do's and dont's or it can not simply be done.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/xkingxkaosx"> /u/xkingxkaosx </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8bu4r/i_purchased_a_new_vps_with_ubuntu_2404_can_i_use/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8bu4r/i_purchased_a_new_vps_with_ubuntu_2404_can_i_use/">[c

## Repurpose old gaming PC to NAS/Home-Server
 - [https://www.reddit.com/r/selfhosted/comments/1e8bdfl/repurpose_old_gaming_pc_to_nashomeserver](https://www.reddit.com/r/selfhosted/comments/1e8bdfl/repurpose_old_gaming_pc_to_nashomeserver)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T01:50:08+00:00

<!-- SC_OFF --><div class="md"><p>I currently have a AsRock X570 Taichi MB. 8 sata ports, 3 nvme slots, 3 pci-e </p> <p>So it seems to be loaded with options I can use to upgrade. Better Ethernet 2.5/10gb and so on.</p> <p>My issue is currently running a 3800X + 5700xt</p> <p>My idle is around 100~ even with power savings mode(windows)and p-state = 2 high setting on my board.</p> <p>I was thinking of grabbing a 5700G w/ on board gpu. No quick sync but still 8c/16t be plenty for my starting home-server/NAS needs(JellyFin/HA/etc)Goal is just to be more power efficient.</p> <p>Does this sound like good plan? Any suggestions?</p> <p>Think I'm gonna get a dedicated nas case gotta be a ATX (any suggestions be nice) </p> <p>keep meshify C case for next gaming PC upgrade(since no room for HDD drives). Most likely take 5700xt with it for now.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Kill3rAce"> /u/Kill3rAce </a> <br /> <span><a href="https://www.re

## Not sure how to continue setting up reverse proxy for Minecraft server
 - [https://www.reddit.com/r/selfhosted/comments/1e8bamm/not_sure_how_to_continue_setting_up_reverse_proxy](https://www.reddit.com/r/selfhosted/comments/1e8bamm/not_sure_how_to_continue_setting_up_reverse_proxy)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T01:45:35+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1e8bamm/not_sure_how_to_continue_setting_up_reverse_proxy/"> <img alt="Not sure how to continue setting up reverse proxy for Minecraft server" src="https://b.thumbs.redditmedia.com/GsUBHGY0XGbqg9D6-qfUU09_04gpNm0Hc0dOe69qwQs.jpg" title="Not sure how to continue setting up reverse proxy for Minecraft server" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I've been trying to set up a reverse proxy for my minecraft server which would take in requests from &quot;mc.infernope.org&quot; and forward them to my server's instance. I'm not actually doing this to use the domain though, it's just because Xfinity only allows you to port forward listed devices rather than just choosing an IP, so I cant port forward the ip of my proxmox instance and instead have to forward a standalone proxy server.</p> <p>I did follow a tutorial in which they used an AWS instance with nginx to proxy. I am doing something similar, but I have

## Logitech Media Server is now known as Lyrion?
 - [https://www.reddit.com/r/selfhosted/comments/1e8b4v4/logitech_media_server_is_now_known_as_lyrion](https://www.reddit.com/r/selfhosted/comments/1e8b4v4/logitech_media_server_is_now_known_as_lyrion)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-07-21T01:36:43+00:00

<!-- SC_OFF --><div class="md"><p>Did I miss the announcement? I use this on a regular basis and at first glance it looks like nothing more then a name change. I'm just curious if anyone caught anything I may have missed.</p> <p><a href="https://lyrion.org/">https://lyrion.org/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LDerJim"> /u/LDerJim </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8b4v4/logitech_media_server_is_now_known_as_lyrion/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1e8b4v4/logitech_media_server_is_now_known_as_lyrion/">[comments]</a></span>

