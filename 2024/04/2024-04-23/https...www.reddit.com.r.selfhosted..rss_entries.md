# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Caddy Question Regarding 5 Digit Port #s
 - [https://www.reddit.com/r/selfhosted/comments/1cbj233/caddy_question_regarding_5_digit_port_s](https://www.reddit.com/r/selfhosted/comments/1cbj233/caddy_question_regarding_5_digit_port_s)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T23:13:00+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I have been setting up caddy and five digit port does not seem to work in the Caddyfile. I am receiving &quot;HTTP ERROR 502&quot; when using it. Four digit ports seem to cause no issues. I am using Docker, how would you use caddy with a 5 digit port?</p> <p>The first two below work, but the third does not. Thanks in advance!</p> <p><a href="http://jellyfin.myurl.com">jellyfin.myurl.com</a> {</p> <p>reverse_proxy jellyfin:8096</p> <p>}</p> <p><a href="http://jellyseerr.myurl.com">jellyseerr.myurl.com</a> {</p> <p>reverse_proxy jellyseerr:5055</p> <p>}</p> <p><a href="http://radarr.myurl.com">radarr.myurl.com</a> {</p> <p>reverse_proxy radarr:32778</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dontlickthatlol"> /u/dontlickthatlol </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cbj233/caddy_question_regarding_5_digit_port_s/">[link]</a></span> &#32; <span><a href="https://www.redd

## Any advice for Jellyfin + Nextcloud docker connection?
 - [https://www.reddit.com/r/selfhosted/comments/1cbhigr/any_advice_for_jellyfin_nextcloud_docker](https://www.reddit.com/r/selfhosted/comments/1cbhigr/any_advice_for_jellyfin_nextcloud_docker)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T22:07:53+00:00

<!-- SC_OFF --><div class="md"><p>Hi, admittedly I am a noobie to Linux, self hosting, and docker, so I was able to get things working, but I'm certain my methods were not the best and I am hoping to get some advice on my situation.</p> <p>Problem: Have a nextcloud docker stack with mariadb as backend. Trying to make a jellyfin docker container and let it detect the &quot;Songs&quot; folder in my nextcloud folders.</p> <p>What I did to my Jellyfin docker compose file:</p> <pre><code>- type: bind source: /mnt/HDD1/Nextcloud/data/admin/files/Documents/Music/Songs target: /media </code></pre> <p>And this is how I configured my nextcloud:</p> <pre><code>volumes: - /DOCUMENTS/nextcloud/html:/var/www/html - /DOCUMENTS/nextcloud/config:/var/www/html/config - /mnt/HDD1/Nextcloud/data:/var/www/html/data </code></pre> <p>So as you can see, I have a HDD storage named HDD1 and it's where the nextcloud files are all stored. And inside the files I have some more folders before I get to the &quot;So

## Schedule availability / coverage app
 - [https://www.reddit.com/r/selfhosted/comments/1cbg2s7/schedule_availability_coverage_app](https://www.reddit.com/r/selfhosted/comments/1cbg2s7/schedule_availability_coverage_app)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T21:11:04+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I'm looking for an open source, self-hosted, web based solution that enables me to plan and coordinate volunteer availability on an hour-by-hour basis, over the course of multiple days.</p> <p>I need a system that will help me ensure two people are present at all times, but more people present are acceptable. </p> <p>This is possible in Google Sheets but it's ugly. My hope is there a more elegant crowd sourced, de-centralized approach that lets people enter their own availability without me having to orchestrate it for them.</p> <p>This is mostly intended for BSA (Boy Scouts) planning campouts and community service events, but could be used for a bunch of purposes. </p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nuttervm"> /u/nuttervm </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cbg2s7/schedule_availability_coverage_app/">[link]</a></span> &#32; <span><a 

## What's your next purchase?
 - [https://www.reddit.com/r/selfhosted/comments/1cbfw30/whats_your_next_purchase](https://www.reddit.com/r/selfhosted/comments/1cbfw30/whats_your_next_purchase)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T21:03:46+00:00

<!-- SC_OFF --><div class="md"><p>Mine is an e-book reader, so any recommendations send them my way...</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RathdrumRain"> /u/RathdrumRain </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cbfw30/whats_your_next_purchase/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cbfw30/whats_your_next_purchase/">[comments]</a></span>

## Rebuilding my server. I've seen self-hosted specialized OSes. Are any worth considering over plain Debian?
 - [https://www.reddit.com/r/selfhosted/comments/1cbey65/rebuilding_my_server_ive_seen_selfhosted](https://www.reddit.com/r/selfhosted/comments/1cbey65/rebuilding_my_server_ive_seen_selfhosted)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T20:25:53+00:00

<!-- SC_OFF --><div class="md"><p>Are any better? I already know Debian, is there an advantage to the switch?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Bill_Buttersr"> /u/Bill_Buttersr </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cbey65/rebuilding_my_server_ive_seen_selfhosted/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cbey65/rebuilding_my_server_ive_seen_selfhosted/">[comments]</a></span>

## Are there Overseerr/Jellyseerr alternatives built for Lidarr or Readarr?
 - [https://www.reddit.com/r/selfhosted/comments/1cbdue4/are_there_overseerrjellyseerr_alternatives_built](https://www.reddit.com/r/selfhosted/comments/1cbdue4/are_there_overseerrjellyseerr_alternatives_built)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T19:42:37+00:00

<!-- SC_OFF --><div class="md"><p>I’m sure there might be Discord bots built for requesting to those services but an actual service with a web UI and recommendations would be nice.</p> <p>Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nothingveryobvious"> /u/nothingveryobvious </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cbdue4/are_there_overseerrjellyseerr_alternatives_built/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cbdue4/are_there_overseerrjellyseerr_alternatives_built/">[comments]</a></span>

## Using NPM internally with split DNS on single NAS docker host
 - [https://www.reddit.com/r/selfhosted/comments/1cbde3v/using_npm_internally_with_split_dns_on_single_nas](https://www.reddit.com/r/selfhosted/comments/1cbde3v/using_npm_internally_with_split_dns_on_single_nas)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T19:24:44+00:00

<!-- SC_OFF --><div class="md"><p>I've been reading this SR for some time and got a lot of inspiration, however, now I face some practical issues in my own setup where I can't put my head around on my own.</p> <p>My whole selfhosted setup is running on one Synology NAS (DS920+) in the form of docker containers managed primarily in a GitOps setup with Portainer. For a long time I ran all services in bridged mode and accessed them simply with &lt;NAS hostname&gt;:&lt;Port&gt;.</p> <p>For making some services available externally, I configured an NPM instance on Docker in bridged mode using other ports than 80/443 internally as both are occupied by the NAS FW. All ran fine.</p> <p>No I want to finally make also my internal services accessible with a FQDN and a split DNS setup with my external name. So, now I need NPM to run on ports 80/443 internally and also it should be able to identify internal vs. external requests. Therefore, I configured NPM to use a MACVLAN as the &quot;Host&quot;

## Left Debian 12 for Unraid?
 - [https://www.reddit.com/r/selfhosted/comments/1cbcyqv/left_debian_12_for_unraid](https://www.reddit.com/r/selfhosted/comments/1cbcyqv/left_debian_12_for_unraid)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T19:07:26+00:00

<!-- SC_OFF --><div class="md"><p>I don't want to start holly wars here, but I'm just wondering are there some advantages to make me start using Unraid. If you don't pay attention to free (Debian) vs paid (Unraid). I left OMV for pure Debian, because I want to have full control over my servers, and want to learn.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gett13"> /u/gett13 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cbcyqv/left_debian_12_for_unraid/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cbcyqv/left_debian_12_for_unraid/">[comments]</a></span>

## Best photo backup solution to Windows Server - PhotoSync?
 - [https://www.reddit.com/r/selfhosted/comments/1cbcfvv/best_photo_backup_solution_to_windows_server](https://www.reddit.com/r/selfhosted/comments/1cbcfvv/best_photo_backup_solution_to_windows_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T18:46:31+00:00

<!-- SC_OFF --><div class="md"><p>Been using Amazon Photos for years but frustrated they have now removed the Sync feature from the Windows application so can't sync photos to my Windows Server.</p> <p>Hoping to use PhotoSync autotransfer, but wondering what the best way to set that up to my server is. I'd like it to work away from home but am concerned by the security implications - I've tested WebDAV and SMB and both work, but I'm wondering which is better from a security standpoint, or is FTP the way to go? My server already hosts a couple websites but I have no other external access setup currently.</p> <p>Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OlXondof"> /u/OlXondof </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cbcfvv/best_photo_backup_solution_to_windows_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cbcfvv/best_photo_backup_solution_to_windows_server

## Self hosted cloud computing platform
 - [https://www.reddit.com/r/selfhosted/comments/1cbc5fl/self_hosted_cloud_computing_platform](https://www.reddit.com/r/selfhosted/comments/1cbc5fl/self_hosted_cloud_computing_platform)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T18:35:00+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1cbc5fl/self_hosted_cloud_computing_platform/"> <img alt="Self hosted cloud computing platform" src="https://external-preview.redd.it/zfjZT1kY0A_KpGlBTLnRGgILfPNDvXiWWwKwYwf-_TM.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=8a96c8c59b23f069225b97c073464e7d963a8d91" title="Self hosted cloud computing platform" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/web3samy"> /u/web3samy </a> <br /> <span><a href="https://github.com/taubyte/tau">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cbc5fl/self_hosted_cloud_computing_platform/">[comments]</a></span> </td></tr></table>

## How is Riverside.fm compare to other podcast recording platforms like Zoom and Squadcast?
 - [https://www.reddit.com/r/selfhosted/comments/1cba9b6/how_is_riversidefm_compare_to_other_podcast](https://www.reddit.com/r/selfhosted/comments/1cba9b6/how_is_riversidefm_compare_to_other_podcast)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T17:19:26+00:00

<!-- SC_OFF --><div class="md"><p>I'm looking for a platform to record my podcast interviews, and I'm considering Riverside.fm. But I'm also familiar with Zoom and Squadcast. How does Riverside stack up against these other options?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Diligent_Eye1248"> /u/Diligent_Eye1248 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cba9b6/how_is_riversidefm_compare_to_other_podcast/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cba9b6/how_is_riversidefm_compare_to_other_podcast/">[comments]</a></span>

## How to make a BI tool run with docker-compose?
 - [https://www.reddit.com/r/selfhosted/comments/1cb9va2/how_to_make_a_bi_tool_run_with_dockercompose](https://www.reddit.com/r/selfhosted/comments/1cb9va2/how_to_make_a_bi_tool_run_with_dockercompose)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T17:03:49+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I have a pipeline and i want to be able to display that data for a personal project.<br /> I just want it present for the duration of the container.</p> <p>Ideally i would like something with a docker image that allows importing a UI that i exported previously but with the values from a database.</p> <p>I used Looker Studio which is online but I would love to make something self contained except the cloud infra that i provision using Terraform.</p> <p>I looked into Grafana, Metabase, Redash, Superset and many others.<br /> Metabase says that serialization is a Pro feature. Now I don't know if there is some option using it for free as I am not planning of serving different IPs at once.</p> <p>I just need to specify a config with an empty dashboard, triggers and filters and let the data fill it.<br /> I think I could do all tha with Grafana but aside from the high learning curve the results are not the modern minimalistic bling recruiters 

## ampcast.app - a web based music player inspired by Winamp
 - [https://www.reddit.com/r/selfhosted/comments/1cb9iq7/ampcastapp_a_web_based_music_player_inspired_by](https://www.reddit.com/r/selfhosted/comments/1cb9iq7/ampcastapp_a_web_based_music_player_inspired_by)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T16:50:03+00:00

<!-- SC_OFF --><div class="md"><h1><a href="https://ampcast.app/">https://ampcast.app/</a></h1> <p><strong>DESKTOP ONLY</strong></p> <h2>Features</h2> <ul> <li>Supports Plex, Jellyfin, Emby, Navidrome and Subsonic</li> <li>Additional support for Apple Music, TIDAL (via Plex), YouTube and Spotify</li> <li>Built-in visualizers: Milkdrop (Butterchurn) and others</li> <li>Scrobbling for last.fm and ListenBrainz</li> <li>Playback from last.fm and ListenBrainz</li> </ul> <h2>Web app</h2> <p>Available at <a href="https://ampcast.app">https://ampcast.app</a></p> <h2>Downloadable app</h2> <p>Download from <a href="https://github.com/rekkyrosso/ampcast/releases">https://github.com/rekkyrosso/ampcast/releases</a></p> <h2>Self-hosting</h2> <p><a href="https://github.com/rekkyrosso/ampcast?tab=readme-ov-file#self-hosting">https://github.com/rekkyrosso/ampcast?tab=readme-ov-file#self-hosting</a></p> <hr /> <p><a href="/r/ampcast">/r/ampcast</a> for help and support. Feedback very welcome!</p> </div

## One big docker-compose file, or multiple smaller files?
 - [https://www.reddit.com/r/selfhosted/comments/1cb7jhg/one_big_dockercompose_file_or_multiple_smaller](https://www.reddit.com/r/selfhosted/comments/1cb7jhg/one_big_dockercompose_file_or_multiple_smaller)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T15:31:08+00:00

<!-- SC_OFF --><div class="md"><p>I currently have all of my containers defined in a single docker-compose.yaml file. This is convenient because it's a single place to hold all of my configuration, but I've wondered if there are advantages to splitting configuration out to multiple files.</p> <p>What are others using to manage composition?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TwinHaelix"> /u/TwinHaelix </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cb7jhg/one_big_dockercompose_file_or_multiple_smaller/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cb7jhg/one_big_dockercompose_file_or_multiple_smaller/">[comments]</a></span>

## Have You Received A Data Breach Notice Letter From One of These Companies?
 - [https://www.reddit.com/r/selfhosted/comments/1cb7de2/have_you_received_a_data_breach_notice_letter](https://www.reddit.com/r/selfhosted/comments/1cb7de2/have_you_received_a_data_breach_notice_letter)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T15:23:56+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1cb7de2/have_you_received_a_data_breach_notice_letter/"> <img alt="Have You Received A Data Breach Notice Letter From One of These Companies?" src="https://external-preview.redd.it/lItO5N3a8mSV6wH3T6fcw-ZIxDLIbKrDWpreXa5HGYA.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=c571e2190b5856b02e523f1fede7026c7da1e5ac" title="Have You Received A Data Breach Notice Letter From One of These Companies?" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Glum_Maximum_4418"> /u/Glum_Maximum_4418 </a> <br /> <span><a href="https://openclassaction.com/investigations/hot-data-breaches.php">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cb7de2/have_you_received_a_data_breach_notice_letter/">[comments]</a></span> </td></tr></table>

## After years of random outages, I finally set up some uptime monitors using Elasticsearch/Kibana Synthetic Monitors. Last night it notified me of a Plex outage which I was able to quickly resolve.
 - [https://www.reddit.com/r/selfhosted/comments/1cb6rf3/after_years_of_random_outages_i_finally_set_up](https://www.reddit.com/r/selfhosted/comments/1cb6rf3/after_years_of_random_outages_i_finally_set_up)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T14:58:39+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1cb6rf3/after_years_of_random_outages_i_finally_set_up/"> <img alt="After years of random outages, I finally set up some uptime monitors using Elasticsearch/Kibana Synthetic Monitors. Last night it notified me of a Plex outage which I was able to quickly resolve." src="https://b.thumbs.redditmedia.com/NoqRx7ZBzyLBJkw-PP1V3XOr5qs_xBWw4-F38sWg-ys.jpg" title="After years of random outages, I finally set up some uptime monitors using Elasticsearch/Kibana Synthetic Monitors. Last night it notified me of a Plex outage which I was able to quickly resolve." /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/8vmf8q9ls8wc1.png?width=1174&amp;format=png&amp;auto=webp&amp;s=465bee1be562fc9e4f940265de4cc10a6b7301b1">https://preview.redd.it/8vmf8q9ls8wc1.png?width=1174&amp;format=png&amp;auto=webp&amp;s=465bee1be562fc9e4f940265de4cc10a6b7301b1</a></p> <p>Because I am cheap, I have Kibana write a

## Pihole DNS
 - [https://www.reddit.com/r/selfhosted/comments/1cb5qi8/pihole_dns](https://www.reddit.com/r/selfhosted/comments/1cb5qi8/pihole_dns)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T14:14:52+00:00

<!-- SC_OFF --><div class="md"><p>So I'm using pihole as dns server and my router handles dhcp. If I ain't wrong, when I stop the pihole container, all the devices/apps connected to my home network shouldn't be access the internet. This is how it should be and it works as expected but...</p> <p>....in some cases, meta apps like instagram, whatsapp or chrome browser or Huawei devices, apple devices, etc., are still able to connect to internet by using their own dns server bypassing ours. In chrome desktop browser or in iphone, there's an option of disabling auto-dns but even when it's off, they still use their own dns server.</p> <p>One way to force them to use is by making pihole as the dhcp as well as dns server. But in some cases this also gets bypassed. Any thoughts on this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/quanta777"> /u/quanta777 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cb5qi8/pihole_dns/">[link

## Deployment providers for self-hostable software packages - a few options
 - [https://www.reddit.com/r/selfhosted/comments/1cb5gd3/deployment_providers_for_selfhostable_software](https://www.reddit.com/r/selfhosted/comments/1cb5gd3/deployment_providers_for_selfhostable_software)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T14:03:03+00:00

<!-- SC_OFF --><div class="md"><p>I've been doing quite a bit of research lately into the best and most cost-effective ways of getting a few particular software packages running on some infrastructure.</p> <p>I've noticed that there are a few companies that specialise in getting scripts running on hosting (this is where they bifurcate a bit: some allow users to truly &quot;bring their own server&quot; others limit to you to whoever they want to hook in with).</p> <p>Note: I have no associations whatsoever with any of these providers. I'm just interested in getting some stuff running and while I'm much more inclined to go the DIY approach on AWS/GCP etc .... I see the utility in these, especially when you want to test out a bunch of options.</p> <p>This will likely be a very partial list but ... perhaps enough to point to directions:</p> <p><strong>Restack:</strong></p> <p>Restack was the first such provider that I discovered by repetitively Googling &quot;how to host Apache Superset?&

## Gaming laptop as home server
 - [https://www.reddit.com/r/selfhosted/comments/1cb4spj/gaming_laptop_as_home_server](https://www.reddit.com/r/selfhosted/comments/1cb4spj/gaming_laptop_as_home_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T13:34:58+00:00

<!-- SC_OFF --><div class="md"><p>I’ve got this old Asus TUF gaming laptop that I want to repurpose. My main goal is to boost my DevOps skills—working with tools like Kubernetes, Git, Jenkins, and CICD—while also setting it up as a home server. It’s still running well, but it does tend to overheat. Could anyone recommend a lightweight OS that supports most applications? I’m also looking to cut down on electricity usage. Are there effective methods to manage its uptime and downtime, like having it online only from 11 AM to 2 AM daily, but also able to boot on demand? Also, any tips on setting up a cooling system for this? Does anyone have a similar setup?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/andicom"> /u/andicom </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cb4spj/gaming_laptop_as_home_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cb4spj/gaming_laptop_as_home_ser

## Disk help - xfs formatted USB not readable?
 - [https://www.reddit.com/r/selfhosted/comments/1cb43y3/disk_help_xfs_formatted_usb_not_readable](https://www.reddit.com/r/selfhosted/comments/1cb43y3/disk_help_xfs_formatted_usb_not_readable)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T13:04:20+00:00

<!-- SC_OFF --><div class="md"><p>I ran Unraid for many months and backed up files to a USB disk. I'm pretty sure the disk was formatted as xfs (and when I run df -h -T it confirms).</p> <p>I took down my Unraid server and moved everything to Proxmox and would like to retrieve the files from the USB disk.</p> <p>My MacOS computer doesn't recognize the disk at all.</p> <p>If I pass the disk through to an OpenMediaVault VM running on Proxmox, it can see that it is 40% full but it does not list any files.</p> <p>I'm sorta at the end of what I know to try. Any suggestions?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Gqsmoothster"> /u/Gqsmoothster </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cb43y3/disk_help_xfs_formatted_usb_not_readable/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cb43y3/disk_help_xfs_formatted_usb_not_readable/">[comments]</a></span>

## Immich + Swag on Unraid
 - [https://www.reddit.com/r/selfhosted/comments/1cb3ael/immich_swag_on_unraid](https://www.reddit.com/r/selfhosted/comments/1cb3ael/immich_swag_on_unraid)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T12:25:27+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys,</p> <p>I've recently given Immich another go after a 6 months hiatus, and I'm loving it: everything is working properly and I'm setting it up for the rest of the family.</p> <p>That said, I'd like to make it play nice with my SWAG setup. I'm currently running immich and swag as docker containers on an unraid machine. Immich was setup via the compose plugin.</p> <p>SWAG has a dockersocker and a cloudflare auto dns containers associated with it, and is running on its own docker network (docker-network). That said, I can't seem to correctly configure the Immich nginx conf file.</p> <p>The compose and env files I'm using for Immich are as follows:</p> <pre><code># # WARNING: Make sure to use the docker-compose.yml of the current release: # # # # The compose file on main may not be compatible with the latest release. # name: immich services: immich-server: container_name: immich_server image: command: ['start.sh', 'immich'] volumes: - ${LIBRARY_LO

## Love logseq but I want it web hosted, alternative?
 - [https://www.reddit.com/r/selfhosted/comments/1cb2uk8/love_logseq_but_i_want_it_web_hosted_alternative](https://www.reddit.com/r/selfhosted/comments/1cb2uk8/love_logseq_but_i_want_it_web_hosted_alternative)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T12:03:22+00:00

<!-- SC_OFF --><div class="md"><p>I love logseq</p> <p>I would also like to have my graph available via a self hosted web app</p> <p>Does anyone have a solution for logseq, if not for logseq, is there a drop in replacement that I can selfhost with comparable features?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ithakaa"> /u/ithakaa </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cb2uk8/love_logseq_but_i_want_it_web_hosted_alternative/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cb2uk8/love_logseq_but_i_want_it_web_hosted_alternative/">[comments]</a></span>

## How do you access your self-hosted books to your Kindle?
 - [https://www.reddit.com/r/selfhosted/comments/1cb1kw8/how_do_you_access_your_selfhosted_books_to_your](https://www.reddit.com/r/selfhosted/comments/1cb1kw8/how_do_you_access_your_selfhosted_books_to_your)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T10:54:29+00:00

<!-- SC_OFF --><div class="md"><p>For audiobooks, I found an app called plappa (thanks dev for this awesome app) but I’d like to know how do you access your books library through your kindle or from your phone? Recently I have taken a liking to comics and badly want to finish invincible ever since S03 final. I did setup a self hosting library on the pc but is there an easier way for me to access the books on kindle? How do I automate this process? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Michaelscarn69-"> /u/Michaelscarn69- </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cb1kw8/how_do_you_access_your_selfhosted_books_to_your/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cb1kw8/how_do_you_access_your_selfhosted_books_to_your/">[comments]</a></span>

## Hardware Recommendations?
 - [https://www.reddit.com/r/selfhosted/comments/1cb1jfu/hardware_recommendations](https://www.reddit.com/r/selfhosted/comments/1cb1jfu/hardware_recommendations)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T10:52:00+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I'm on a budget of &lt;£150 and I'm looking to purchase my first server.</p> <p>The server will be used for hosting games servers for myself and 3-4 others to play games like Valheim, Palworld, Minecraft etc on. We will be doing a lot of building, so I guess It will need a reasonable amount of Ram.</p> <p>Does anybody have recommendations on what I should shop around for?</p> <p>Thanks,</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Olog-Guy"> /u/Olog-Guy </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cb1jfu/hardware_recommendations/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cb1jfu/hardware_recommendations/">[comments]</a></span>

## Hosted offsite monitor/jump server.
 - [https://www.reddit.com/r/selfhosted/comments/1cb1ec8/hosted_offsite_monitorjump_server](https://www.reddit.com/r/selfhosted/comments/1cb1ec8/hosted_offsite_monitorjump_server)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T10:43:16+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I realise this is sacrilege, but I'm looking for suggestions for a decent VPS or similar host to effectively run a remote Pi offsite from home. I don't have the luxury of being able to set up a Pi at a family members house.</p> <p>I run all of my network locally using Wireguard/Tailscale to jump in. However sometimes if something goes down with my ISP it would be nice to have a health check monitor, git mirror and potentially a VPN offsite. What are the most ethical/cost effective VPS hosts for this kind of thing. </p> <p>Bonus question, what else do you run on your offsite server?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ChapteristOllie"> /u/ChapteristOllie </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cb1ec8/hosted_offsite_monitorjump_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cb1ec8/hosted_offsite_monitorjump_server/">

## What's your set up and what do you host?
 - [https://www.reddit.com/r/selfhosted/comments/1cb0zcq/whats_your_set_up_and_what_do_you_host](https://www.reddit.com/r/selfhosted/comments/1cb0zcq/whats_your_set_up_and_what_do_you_host)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T10:16:14+00:00

<!-- SC_OFF --><div class="md"><p>Well, let's share what do you guys have. I'll start.</p> <p>Since me and my wife are trying to save some money for a house, we still live with my parents, so I don't have fancy set up. Its Raspberry pi 4, with lite OS and docker.<br /> Containers in docker (No particular order, just trying to remember):</p> <ul> <li><a href="https://www.portainer.io">Portainer</a></li> <li><a href="https://github.com/linuxserver/docker-plex">Plex</a></li> <li><a href="https://jellyfin.org">Jellyfin</a></li> <li><a href="https://github.com/bonukai/MediaTracker?tab=readme-ov-file">MediaTracker</a></li> <li><a href="https://www.freshrss.org">FreshRss</a></li> <li><a href="https://transmissionbt.com">Transmission</a></li> <li><a href="https://nginxproxymanager.com">Nginx proxy manager</a></li> <li><a href="https://github.com/filebrowser/filebrowser">Filebrowser</a></li> <li><a href="https://github.com/alexta69/metube">Metube</a></li> <li><a href="https://github.com/jmbann

## Encrypted P2P Chat
 - [https://www.reddit.com/r/selfhosted/comments/1cayzoe/encrypted_p2p_chat](https://www.reddit.com/r/selfhosted/comments/1cayzoe/encrypted_p2p_chat)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T07:58:43+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1cayzoe/encrypted_p2p_chat/"> <img alt="Encrypted P2P Chat" src="https://external-preview.redd.it/c_E7X2WIigmckQbUmlbQ_DSCYLtWXrmuxs0-cgZPD7c.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=7d6471d604869cde6be1190ce0499789df9de8a9" title="Encrypted P2P Chat" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Accurate-Screen8774"> /u/Accurate-Screen8774 </a> <br /> <span><a href="https://github.com/positive-intentions/chat">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cayzoe/encrypted_p2p_chat/">[comments]</a></span> </td></tr></table>

## How do you address SSRF issues in your internal LAN-based services?
 - [https://www.reddit.com/r/selfhosted/comments/1cayt6o/how_do_you_address_ssrf_issues_in_your_internal](https://www.reddit.com/r/selfhosted/comments/1cayt6o/how_do_you_address_ssrf_issues_in_your_internal)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T07:45:46+00:00

<!-- SC_OFF --><div class="md"><p>I have a specific scenario that's impacting me, but I feel this could be an issue on a larger scale.</p> <p>My issue: I'm using Audiobookshelf as an audiobook/podcast streamer. Myself and a trusted friend are the only people with access to ABS (it requires a VPN to access it from outside my LAN). I also have a few &quot;podcast&quot; feeds that I generate autonomously that are hosted on a simple nginx web server on the LAN. I want ABS to subscribe to these feeds to allow access to their contents. Both ABS and the nginx server are hosted behind Traefik with LetsEncrypt enabled.</p> <p>The problem is that ABS added an SSRF (<a href="https://portswigger.net/web-security/ssrf">server-side request forgery</a>) filter due to being given a CVE. Therefore, the current versions of the app outright block you from adding any podcast that is hosted on an internal IP address. The package the author of ABS used doesn't seem to offer any configuration (i.e. no way t

## How to password protect a VPN tunnel?
 - [https://www.reddit.com/r/selfhosted/comments/1caxpjw/how_to_password_protect_a_vpn_tunnel](https://www.reddit.com/r/selfhosted/comments/1caxpjw/how_to_password_protect_a_vpn_tunnel)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T06:31:45+00:00

<!-- SC_OFF --><div class="md"><p>2 pieces to the puzzle:</p> <ol> <li>Remote machine (i.e. a laptop that you bring with you on a trip to Disney World) [<strong>Remote</strong>]</li> <li>Home server sitting behind a router [<strong>Home</strong>]</li> </ol> <p>With a wireguard tunnel, remote looks and behaves like it's connected to the home network, regardless of its physical location. </p> <p><strong>But I'd like to accomplish one more piece:</strong> Password protect the wireguard tunnel. <em>I have a particular security need for a password protected tunnel beyond Remote being generally password protected (i.e. need a password to log into a user on the Remote machine).</em> </p> <p>I have an intermediary VPS that I can use to control the tunnel if that is helpful. </p> <p>&#x200b;</p> <p>&#x200b;</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Comprokit"> /u/Comprokit </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1caxp

## is chibisafe file uploader a good option ?
 - [https://www.reddit.com/r/selfhosted/comments/1cax5go/is_chibisafe_file_uploader_a_good_option](https://www.reddit.com/r/selfhosted/comments/1cax5go/is_chibisafe_file_uploader_a_good_option)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T05:54:24+00:00

<!-- SC_OFF --><div class="md"><p>I am running this <a href="https://github.com/chibisafe/chibisafe">chibisafe</a> a file uploader similar to imgur but for we can upload other files as well. It works well but I wish to use the most effecient and effective uploader that will make my life easier.</p> <p>They have iOS shortcut support, ShareX extension and Browser extension which is good, I was thinking if there are any similar selfhosted apps that have similar third party support. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/r4nchy"> /u/r4nchy </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1cax5go/is_chibisafe_file_uploader_a_good_option/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1cax5go/is_chibisafe_file_uploader_a_good_option/">[comments]</a></span>

## Trouble Setting up Radarr and Sonarr on Docker Desktop on Ubuntu Desktop
 - [https://www.reddit.com/r/selfhosted/comments/1cavzby/trouble_setting_up_radarr_and_sonarr_on_docker](https://www.reddit.com/r/selfhosted/comments/1cavzby/trouble_setting_up_radarr_and_sonarr_on_docker)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T04:43:24+00:00

<!-- SC_OFF --><div class="md"><p>First time posting here and first real time using Linux. I've been switching my setup over from Windows 10 to Ubuntu Desktop the past few days and had an issue come up with both Sonarr and Radarr.</p> <p>When I got to add a root folder to either one of the them I get an error like this</p> <ul> <li>Folder '/media/14TB_HDD_Array/Tv Shows/' is not writable by user 'abc'</li> </ul> <p>I have made sure that the drive is owned by my user and group and that they both have &quot;Create and Delete&quot; permissions. I have also made sure that PUID and PGID are set properly.</p> <p>Any help with this would be greatly appreciated!</p> <p>Contents of compose file</p> <pre><code>--- services: prowlarr: image: lscr.io/linuxserver/prowlarr:latest container_name: prowlarr environment: - PUID=1000 - PGID=1000 - TZ=Etc/UTC volumes: - ./prowlarr/data:/config ports: - 9696:9696 restart: always sonarr: image: lscr.io/linuxserver/sonarr:latest container_name: sonarr envir

## Migrating From CasaOS to Something Better
 - [https://www.reddit.com/r/selfhosted/comments/1cav1p5/migrating_from_casaos_to_something_better](https://www.reddit.com/r/selfhosted/comments/1cav1p5/migrating_from_casaos_to_something_better)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T03:51:23+00:00

<!-- SC_OFF --><div class="md"><p>Hi all! This is my first post here, and as a 4-day newcomer, I hope I can explain myself well.</p> <p>I'm new to self-hosting, and I'm tinkering with a Shuttle DS57U with 12GB Ram and 512gb SSD as a home server. I started with CasaOS since it seemed so easy, and I set up Jellyfin and some *rr services. But I need Miniflux and Ghost but couldn't manage to install them with CasaOS. For Miniflux, I can easily install it with docker compose in Portainer. But CasaOS sees it as a legacy app and wants to convert it, so it breaks it. If I leave it as it is, it just looks ugly on the dashboard.</p> <p>I was thinking about migrating to Cosmos Cloud, but I don't know if it will be OK with app installed in Portainer. And my second thought was OMV with Portainer and Homarr to make it as easy as CasaOS. Since I'm extremely new to this, I want your suggestions.</p> <p>Also, I wonder if I can save my current Docker containers, so I don't have to deal with all those J

## Debian local DNS will not work. Any thoughts/help?
 - [https://www.reddit.com/r/selfhosted/comments/1caua0b/debian_local_dns_will_not_work_any_thoughtshelp](https://www.reddit.com/r/selfhosted/comments/1caua0b/debian_local_dns_will_not_work_any_thoughtshelp)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T03:11:00+00:00

<!-- SC_OFF --><div class="md"><p>Appreciate any help out there. Usually can figure this type of things out but google has failed me so far. It had worked previously and I'm unsure when things went wrong. I can make it work by adding forwarders to the named.conf.options file but that shouldn't be needed. bind9 (named) running locally and accesible (can telnet to port 53 locally no issues)</p> <p>I have a secondary setup that works fine but when comparing things, don't see any differences so far. syslog doesn't seem to show much that i've seen as useful. Appreciate any thoughts.</p> <p>Example below :</p> <p>root@control:/etc/bind# nslookup</p> <p>&gt; server 127.0.0.1 Default server: 127.0.0.1</p> <p>Address: 127.0.0.1#53</p> <p>&gt; <a href="http://www.google.com">www.google.com</a></p> <p>Server: 127.0.0.1</p> <p>Address: 127.0.0.1#53</p> <p>** server can't find <a href="http://www.google.com:">www.google.com:</a> SERVFAIL</p> <p>&#x200b;</p> </div><!-- SC_ON --> &#32; submitted by 

## Introducing Fractal HomeServer
 - [https://www.reddit.com/r/selfhosted/comments/1catzwg/introducing_fractal_homeserver](https://www.reddit.com/r/selfhosted/comments/1catzwg/introducing_fractal_homeserver)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T02:58:04+00:00

<!-- SC_OFF --><div class="md"><p>TL;DR watch the Fractal HomeServer video overview: <a href="https://www.loom.com/share/9b36cece24bb4d20b43326dbfb1aa46b?sid=e8a0d1bf-3644-4fae-96a2-e74352ff2a4e">Fractal HomeServer Overview</a></p> <p>Hey everybody!</p> <p>My name is Mo, the founder of <a href="https://www.youtube.com/watch?v=e41Y9wvPh2k">Fractal Networks</a> and the creator of the <a href="https://github.com/fractalnetworksco/selfhosted-gateway">selfhosted-gateway</a>.</p> <p>I started Fractal Networks in February 2021 as a public benefit corporation with the goal of making self-hosting more accessible and survivable.</p> <p>Today, I'd like to share what I believe the future of self-hosting will look like from a capability and accessibility perspective. I call this vision for self-hosting the &quot;Fractal Network&quot; architecture.</p> <p>I'll start by defining some goals:</p> <ol> <li>Very easy to get started, 1-click or handful of CLI commands to get up and running (done)</li> <l

## Help with keeping some services privates and public
 - [https://www.reddit.com/r/selfhosted/comments/1catc2w/help_with_keeping_some_services_privates_and](https://www.reddit.com/r/selfhosted/comments/1catc2w/help_with_keeping_some_services_privates_and)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T02:24:53+00:00

<!-- SC_OFF --><div class="md"><p>Let’s say I have a domain mydomain.com, and I have a couple of services deployed on my proxmox server. I want to be able to access some of those services like home assistant, NAS, etc. securely, I know this can be done using a VPN of Tailscale. But I also want to publish other services like a web page or vaultwarden and no need the vpn to access these services. And most importantly for all those services I want to access them using subdomains like homeassistan.mydomain.com, vaultwarden.mydomain.com. </p> <p>I have been reading and watching tutorials but I cannot get my head around this, all of these can be done using Tailscale or do I need something else, what is the right configuration for a setup like this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dalja97"> /u/Dalja97 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1catc2w/help_with_keeping_some_services_privates_and/">[link]</a><

## Should I go for this?
 - [https://www.reddit.com/r/selfhosted/comments/1caszd2/should_i_go_for_this](https://www.reddit.com/r/selfhosted/comments/1caszd2/should_i_go_for_this)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T02:08:19+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1caszd2/should_i_go_for_this/"> <img alt="Should I go for this?" src="https://b.thumbs.redditmedia.com/gjq2o1rxy1TWlTntli52oDddJuTlbWdPXKbYL1x3zzk.jpg" title="Should I go for this?" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/somanii"> /u/somanii </a> <br /> <span><a href="https://www.reddit.com/gallery/1caszd2">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1caszd2/should_i_go_for_this/">[comments]</a></span> </td></tr></table>

## Bedrock Minecraft server hosting
 - [https://www.reddit.com/r/selfhosted/comments/1cartk8/bedrock_minecraft_server_hosting](https://www.reddit.com/r/selfhosted/comments/1cartk8/bedrock_minecraft_server_hosting)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T01:12:52+00:00

<!-- SC_OFF --><div class="md"><p>Hi :)</p> <p>i am very clueless when it comes to this so i do apologise if i'm asking stupid questions.</p> <p>I'm looking into starting a server for me and my friend to play. <strong>i have a laptop that i don't use anymore and i was wondering if it would be possible for me to host a server on that laptop and play on my PC?</strong></p> <p>I've only ever hosted a java server before and that was on the same device i was playing on, from the research ive done minecraft puts no limits on how many devices you can have your account on but limits it to 1 device for online play. </p> <p>I am aware that multiplayer is really easy on bedrock but we have very conflicting schedules at the moment so organising a time to play is pretty difficult. i also know that realms is an option but the limit on render distance makes playing it quite frustrating to play lol. </p> <p>Thank you for any help!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www

## Is self hosting immich worth it ?
 - [https://www.reddit.com/r/selfhosted/comments/1carhwq/is_self_hosting_immich_worth_it](https://www.reddit.com/r/selfhosted/comments/1carhwq/is_self_hosting_immich_worth_it)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-04-23T00:57:51+00:00

<!-- SC_OFF --><div class="md"><p>Considering the bitrot and harddisk failure, is there a common practice to self host immich and still reliable for long term usage?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/One_Force_5681"> /u/One_Force_5681 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1carhwq/is_self_hosting_immich_worth_it/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1carhwq/is_self_hosting_immich_worth_it/">[comments]</a></span>

