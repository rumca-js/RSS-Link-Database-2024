# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Assistance with Glances WebUI
 - [https://www.reddit.com/r/selfhosted/comments/1f19m88/assistance_with_glances_webui](https://www.reddit.com/r/selfhosted/comments/1f19m88/assistance_with_glances_webui)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T23:09:16+00:00

<!-- SC_OFF --><div class="md"><p>Good evening,</p> <p>This morning I came across Glances (thanks to Dashy). I had it setup in a container and everything ran perfect. I decided that instead of doing a container, I'd prefer it as a service. I deleted the container, installed it and setup the service. After reboot the first thing i checked was glances in terminal and it started as expected. Now, my issue is that the WebUI is blank. when I ran <code>glances -w :</code></p> <pre><code>Glances Web User Interface started on Error: Can not ran Glances Web server ([Errno 98] Address already in use) http://0.0.0.0:61208/ </code></pre> <p>I was able to do the WebUI before when it was in the container and I tried clearing the cache.</p> <pre><code>sudo lsof -i -P-n |grep LISTEN glances 1207 root 4u IPv4 4828 0t0 TCP 127.0.0.1:61209 (LISTEN) glances 1208 root 4u IPv4 24660 0t0 TCP *:61208 (LISTEN) </code></pre> <p>Does anyone have a suggesion as to what i need to do to get the WebUI view again?</

## Internet Traffic Monitoring Software
 - [https://www.reddit.com/r/selfhosted/comments/1f19jjf/internet_traffic_monitoring_software](https://www.reddit.com/r/selfhosted/comments/1f19jjf/internet_traffic_monitoring_software)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T23:05:33+00:00

<!-- SC_OFF --><div class="md"><p>I currently have the UDM-PRO and I like how it shows your interent traffic and your usage at certain times, but the problem is I need something that shows more than 24 hour usage. What is out there that can show Internet usage at a given time, what dwvice, &amp; what for?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BigFlubba"> /u/BigFlubba </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1f19jjf/internet_traffic_monitoring_software/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1f19jjf/internet_traffic_monitoring_software/">[comments]</a></span>

## DNS provider with per domain API key
 - [https://www.reddit.com/r/selfhosted/comments/1f18g6g/dns_provider_with_per_domain_api_key](https://www.reddit.com/r/selfhosted/comments/1f18g6g/dns_provider_with_per_domain_api_key)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T22:14:29+00:00

<!-- SC_OFF --><div class="md"><p>hello!</p> <p>Currently playing with let's encrypt certificate, I would like to improve security of my current stack by generating a API key on a per domain/subdomain basis. I'm currently using DNS-01 challenge, on Dynu DNS hoster.</p> <p>Use case:</p> <p>I have 2 containerized apps, with certbot/Lego in both: - media.domain.net - homepage.domain.net</p> <p>Currently having one (and same) API key on Dynu in both containers, that generates a certificate for each domain.</p> <p>As both are using the same API key, if media.domain.net got compromised, it can modify the DNS entries that might impact homepage.domain.net security </p> <p>What I'm looking for is a DNS service that allow me to generate: - APIKEY_1, that can only modify media.domain.net entries. - APIKEY_2, that can only modify homepage.domain.net entries.</p> <p>Do you know any service that allows this kind of use case? I tried deSec but it doesn't have the feature.</p> <p>thanks!</p> <p>PS: I

## Run Grist with simple username+password
 - [https://www.reddit.com/r/selfhosted/comments/1f17owz/run_grist_with_simple_usernamepassword](https://www.reddit.com/r/selfhosted/comments/1f17owz/run_grist_with_simple_usernamepassword)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T21:40:16+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to get Grist (using Docker and Traefik v3) installed, and it's asking me for authentication providers and whatnot. All I want is to be able to just login with a username and password, I don't want to link it with Google login or whatever it wants me to do. The only way I found to do this was to use the <a href="https://github.com/gristlabs/grist-omnibus">Omnibus image</a> which comes with pre-installed Traefik, but I already have my own Traefik installation.</p> <p>Is there any way to get it working with a simple username/password combo, without doing whatever the hell this OpenID/OIDC nonsense is? I just want to be able to make some tables, this is not going to store CIA secrets or anything.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/StarsInTears"> /u/StarsInTears </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1f17owz/run_grist_with_simple_usernamepassword/">[link]</a></

## What is good self-hosted software that allows me to manage HTML webpages from a Dashboard?
 - [https://www.reddit.com/r/selfhosted/comments/1f16iy6/what_is_good_selfhosted_software_that_allows_me](https://www.reddit.com/r/selfhosted/comments/1f16iy6/what_is_good_selfhosted_software_that_allows_me)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T20:49:31+00:00

<!-- SC_OFF --><div class="md"><p>Mainly the title here, but ideally I want something where I can go into the dashboard (web interface) and upload HTML files and they would appear on the website as a specific directory.</p> <p>Thank you <a href="/r/selfhosted">r/selfhosted</a> members!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Living-Phrase-9459"> /u/Living-Phrase-9459 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1f16iy6/what_is_good_selfhosted_software_that_allows_me/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1f16iy6/what_is_good_selfhosted_software_that_allows_me/">[comments]</a></span>

## Cheap way to play media off of SMB shares on a dumb TV?
 - [https://www.reddit.com/r/selfhosted/comments/1f15swr/cheap_way_to_play_media_off_of_smb_shares_on_a](https://www.reddit.com/r/selfhosted/comments/1f15swr/cheap_way_to_play_media_off_of_smb_shares_on_a)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T20:18:43+00:00

<!-- SC_OFF --><div class="md"><p>Is there anything cheaper than an apple TV that can easily (and with a good UI) play files off of SMB shares?</p> <p>My friend has a NAS, and wants to play TV shows / movies on her TVs. The NAS is not very powerful, so hosting plex / jellyfin with transcoding would probably not work.</p> <p>I personally, at home, play media off of my NAS using an apple TV with infuse player.</p> <p>Is there something that can do that, but cheaper than an apple TV? Ideally something off the shelf, not a mini PC you'll have to set up etc.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/youRFate"> /u/youRFate </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1f15swr/cheap_way_to_play_media_off_of_smb_shares_on_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1f15swr/cheap_way_to_play_media_off_of_smb_shares_on_a/">[comments]</a></span>

## How to manage duplicated artists and albums with MusicBrainz Picard?
 - [https://www.reddit.com/r/selfhosted/comments/1f13sa7/how_to_manage_duplicated_artists_and_albums_with](https://www.reddit.com/r/selfhosted/comments/1f13sa7/how_to_manage_duplicated_artists_and_albums_with)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T18:52:09+00:00

<!-- SC_OFF --><div class="md"><p>I have a moderately large music library (~20K songs) that I want to self-host using navidrome, maybe even Jellyfin if it picks up the media OK.</p> <p>I have my Library copied over to my homeserver (its backed up on my desktop) and let Picard try and tag all of the music. For the most part, it did a really good job. However, some issues slipped past me when I was doing a sanity check before writing the tags.</p> <ul> <li> Albums are listed multiple, multiple times. My entire music library is structured `Artist_name/Album_name/track.mp3`, yet MusicBrainzs is consistently splitting up the Album folder into multiple releases. For example, I'll have one &quot;version&quot; with 9/10 tracks, and another version of the same album with 1/10 tracks. How can I force them to merge into the same release?</li> <li>The distinction between Artist and &quot;Album Artist&quot; seems to have been removed. In `cmus`, I can browse my original collection by Album Artist,

## Looking for a self-hosted "TV channel" solution with the ability to also output to Twitch channel.
 - [https://www.reddit.com/r/selfhosted/comments/1f13pf3/looking_for_a_selfhosted_tv_channel_solution_with](https://www.reddit.com/r/selfhosted/comments/1f13pf3/looking_for_a_selfhosted_tv_channel_solution_with)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T18:48:44+00:00

<!-- SC_OFF --><div class="md"><p>Hello! I am looking for a self-hosted solution that shuffles videos stored in my hard-drive and streams them to a Twitch channel and display dynamic &quot;now playing&quot; text on top of the video. </p> <p>Some bonus features that would be ideal but not necessary would be using YouTube as a media source in order to not need to have every video stored on the hard-drive, the ability to have a web TV guide with a schedule of when and what's going to play the following days and the ability to stream closed captions to Twitch.</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Antonaros"> /u/Antonaros </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1f13pf3/looking_for_a_selfhosted_tv_channel_solution_with/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1f13pf3/looking_for_a_selfhosted_tv_channel_solution_with/">[comments]</a></span>

## Looking for search and index software
 - [https://www.reddit.com/r/selfhosted/comments/1f12w9j/looking_for_search_and_index_software](https://www.reddit.com/r/selfhosted/comments/1f12w9j/looking_for_search_and_index_software)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T18:14:07+00:00

<!-- SC_OFF --><div class="md"><p>For a small national non-profit, I'm looking for an FOSS project that can index and search through PDF's.</p> <p>They have an archive of their magazine, going back to the 1980s. They contain a lot of information. But we're unable to quickly answer questions of which the answer was one time in a magazine.</p> <p>Anybody any ideas? Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Own_Size172"> /u/Own_Size172 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1f12w9j/looking_for_search_and_index_software/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1f12w9j/looking_for_search_and_index_software/">[comments]</a></span>

## Overcrawlrr - Automated movie requests to Overseerr
 - [https://www.reddit.com/r/selfhosted/comments/1f12umk/overcrawlrr_automated_movie_requests_to_overseerr](https://www.reddit.com/r/selfhosted/comments/1f12umk/overcrawlrr_automated_movie_requests_to_overseerr)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T18:12:14+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I love Overseerr and I've been using it a lot. But I wanted something to regularly search for movie I may like, event when I'm not actively searching. This provides surprises when I see a movie I'm not expecting on my media players.</p> <p>So I wrote a small tool called <a href="https://github.com/psyko-gh/overcrawlrr">Overcrawlrr</a>, and I've been using it for almost a year now. And I thought I would give back to the community and share it.</p> <p>Basically, it goes through the trending/popular/upcoming list of Overseer on a regular basis and evaluate each movie against the filtering rules you defined. For instance:</p> <pre><code>rules: - name: Reject less wanted genres whenMatch: - genre: - animation - romance action: reject - name: New great movies whenMatch: - age: less than 1 years - score: above 7 action: accept </code></pre> <p>Repo: <a href="https://github.com/psyko-gh/overcrawlrr">https://github.com/psyko-gh/overcrawlrr</a></p

## My own Movie Sites Bookmark Page
 - [https://www.reddit.com/r/selfhosted/comments/1f1218n/my_own_movie_sites_bookmark_page](https://www.reddit.com/r/selfhosted/comments/1f1218n/my_own_movie_sites_bookmark_page)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T17:38:03+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I wanted to share a recent project I've been working on. I’ve redesigned my bookmark page, which I use mainly for sites related to downloading and streaming movies. The old design was functional but not very user-friendly, as it required a lot of scrolling and didn’t include a convenient way to navigate between sections. You can check out the old design here: <a href="https://i.imgur.com/s1CipB3.png">https://i.imgur.com/s1CipB3.png</a>.</p> <p>I’ve since created a new version that includes a bottom floating menu for mobile users, making it easier to navigate to different sections without excessive scrolling. Here are the links to the updated design:</p> <ul> <li>Desktop View: <a href="https://i.imgur.com/Rw2OW9G.png">https://i.imgur.com/Rw2OW9G.png</a></li> <li>Mobile View: <a href="https://i.imgur.com/rIrBrBu.mp4">https://i.imgur.com/rIrBrBu.mp4</a></li> </ul> <p>The updated site is live and available for public use at <a href=

## I see a lot of questions on how to best play back self-hosted media - so I wrote a guide
 - [https://www.reddit.com/r/selfhosted/comments/1f11b08/i_see_a_lot_of_questions_on_how_to_best_play_back](https://www.reddit.com/r/selfhosted/comments/1f11b08/i_see_a_lot_of_questions_on_how_to_best_play_back)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T17:07:41+00:00

<!-- SC_OFF --><div class="md"><h1><a href="https://github.com/Schaka/media-client-guide">Media Client - a guide to local media playback</a></h1> <p>I've seen a lot of questions in all corners of the internet on how to best play back your self-hosted media. These usually revolve around on what client to use. Most people don't feel like spending $200+ on a Shield to not even get P7 FEL.</p> <p>When it comes to what player to recommend to your users for direct play, the discussion is often a similar one. I know for a fact, most of my users aren't willing to spend that much on a device, but I also don't want to transcode everything. I think we all know how hard it is to direct your users to direct play. I personally think it's important to have full sound support, even if you're on an older AVR that can't do DV.</p> <p>So this is my solution. I build my own image for a cheap (&lt;$30) modern Android base media player that allows dual boot on eMMC based on CoreELEC/Kodi and provide a guid

## Does ngrok not work in CasaOS
 - [https://www.reddit.com/r/selfhosted/comments/1f10ox0/does_ngrok_not_work_in_casaos](https://www.reddit.com/r/selfhosted/comments/1f10ox0/does_ngrok_not_work_in_casaos)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T16:41:53+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to setup ngrok using the terminal of CasaOS for my minecraft server. I've tried many tutorials on youtube and here on reddit but none seems to work. So does ngrok just not work in CasaOS? I am a newb to this thing hope someone can help.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Leworsky"> /u/Leworsky </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1f10ox0/does_ngrok_not_work_in_casaos/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1f10ox0/does_ngrok_not_work_in_casaos/">[comments]</a></span>

## Google authenticator alternative
 - [https://www.reddit.com/r/selfhosted/comments/1f10hgm/google_authenticator_alternative](https://www.reddit.com/r/selfhosted/comments/1f10hgm/google_authenticator_alternative)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T16:33:07+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I'm looking for a selfhosted alternative to Google authenticator. As I have quite a lot sites configured on authenticator having a simple migration path from Google authenticator would be a huge plus for me. Do you have any suggestions about the solution and the migration path? Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Alone-Entrepreneur24"> /u/Alone-Entrepreneur24 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1f10hgm/google_authenticator_alternative/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1f10hgm/google_authenticator_alternative/">[comments]</a></span>

## Database of working Enterprise-class servers and HDDs/SSDs?
 - [https://www.reddit.com/r/selfhosted/comments/1f10c8p/database_of_working_enterpriseclass_servers_and](https://www.reddit.com/r/selfhosted/comments/1f10c8p/database_of_working_enterpriseclass_servers_and)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T16:26:56+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I nearly made an expensive mistake of buying some 7TB SAS SSDs for use in my Dell R720, and the built-in RAID card didn't like them.<br /> Luckily I had a spare R620 lying around with a slightly different RAID card and it looks like it will accept them.</p> <p>Do you know if anyone has a DB or wiki list of hardware and working drives?</p> <p>It would be good to have a reference as it's not obvious sometimes what drives will work with particular drives, especially as documentation normally is old and doesn't take account of newer drive sizes as they come out.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MrFlibble1980"> /u/MrFlibble1980 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1f10c8p/database_of_working_enterpriseclass_servers_and/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1f10c8p/database_of_working_enterpriseclass_se

## Building my own NAS - sanity check requested amd okay?
 - [https://www.reddit.com/r/selfhosted/comments/1f106qh/building_my_own_nas_sanity_check_requested_amd](https://www.reddit.com/r/selfhosted/comments/1f106qh/building_my_own_nas_sanity_check_requested_amd)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T16:20:26+00:00

<!-- SC_OFF --><div class="md"><p>I'm going to build my own NAS, in the beginning it will have Plex media server, and emulator JS service, so I'll need to have Docker capabilities and VPN via wire guard from what I've seen from this form seems like a reasonable option. I'll also have it running a few of my personal projects, but I don't expect these to take too much. I have two small webserver projects where the only requests come from me, we're talking less than 100 requests a week traffic wise, practically insignificant. I'm looking more at retro games, gba, snes. I don't expect to run ps5 quality graphics from this device.</p> <p>I know with video transcoding intel normally reigns supreme with Plex, but the modern 13 and 14 gen worries me. Has anyone ran a modern amd cpu, did it require a discrete gpu if not using intel? I'd love to sneak by without a dedicated gpu, and I'm okay with 1080p content so I won't be killed on the transcoding. Does going this route with AMD seem at all r

## Game Database/Collection Manager
 - [https://www.reddit.com/r/selfhosted/comments/1f1017d/game_databasecollection_manager](https://www.reddit.com/r/selfhosted/comments/1f1017d/game_databasecollection_manager)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T16:14:00+00:00

<!-- SC_OFF --><div class="md"><p>Could someone point me in the right direction for a self hosted game database/collection manager. Basically, I have a bunch of ROMS and I want to find a better way than just using a set of folder on my NAS.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Buttery_97"> /u/Buttery_97 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1f1017d/game_databasecollection_manager/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1f1017d/game_databasecollection_manager/">[comments]</a></span>

## Looking for Advice on Sending Emails from Linux Scripts Without a Mail Server
 - [https://www.reddit.com/r/selfhosted/comments/1f0z7at/looking_for_advice_on_sending_emails_from_linux](https://www.reddit.com/r/selfhosted/comments/1f0z7at/looking_for_advice_on_sending_emails_from_linux)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T15:38:36+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>For an upcoming project, I need to run Bash scripts on Linux servers that will generate daily reports. These reports need to be sent via email to a Gmail address (e.g., [<a href="mailto:contract@gmail.com">contract@gmail.com</a>]()).</p> <p>I’d like to avoid setting up a full mail server. My goal is to send emails only from a local domain (domain.lan) to <a href="http://Gmail.com">Gmail.com</a>, <a href="http://Outlook.com">Outlook.com</a>, <a href="http://yahoo.fr">yahoo.fr</a> ... ect .... without needing to receive any emails.</p> <p>I’ve looked into solutions like Postfix with an SMTP relay, but I’m not comfortable with having to store an account in plaintext in my configuration files. If necessary, I might consider purchasing a domain from OVH, creating a dedicated email address, and configuring that account for sending emails.</p> <p>Do you have any suggestions or alternative solutions for achieving this? If you think setting

## Automatic fallback for self-hosted websites?
 - [https://www.reddit.com/r/selfhosted/comments/1f0yzb3/automatic_fallback_for_selfhosted_websites](https://www.reddit.com/r/selfhosted/comments/1f0yzb3/automatic_fallback_for_selfhosted_websites)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T15:28:47+00:00

<!-- SC_OFF --><div class="md"><p>I self-host several websites, some of which I consider “mission critical” but really, I don’t want any of them to ever be offline. I’ll soon be traveling extensively and, while I have purchased a small laptop to serve as my mobile homelab, If I’m on a plane, it will be on the plane with me, so all my sites will be down. I don’t ever want to go back to paying for hosting; that (for me) is part of the point of self-hosting. Ideally, I’d like to setup something that automatically redirects traffic to another server if my server is down. (I use Cloudflare; do they offer anything like that?) If I can’t do that, then my secondary preference would be free hosting (e.g. github) - but some of my sites are blogs (Mostly Ghost but 1 Grav) and I don’t think that’s supported on Github Pages. And even for my static sites, I don’t want to rewrite them using markdown or (god forbid) Hugo, etc.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.red

## Yunohost- godsend or ‘meh’?
 - [https://www.reddit.com/r/selfhosted/comments/1f0yecn/yunohost_godsend_or_meh](https://www.reddit.com/r/selfhosted/comments/1f0yecn/yunohost_godsend_or_meh)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T15:03:42+00:00

<!-- SC_OFF --><div class="md"><p>I’ll be candid - almost every step in my homelab journey has been much more difficult/challenging/frustrating than it should have been. YouTube videos make everything look so easy but nearly every time I try to follow some simple, step-by-step procedure, something goes haywire along the way (some button or link is no longer there because something has changed since the video was published 6 months ago - or some error message that the YouTuber didn’t get but I did) and before I know it I’m knee-deep in googling and troubleshooting and asking for help on github, forums, here, etc. Almost every new container/service I try to setup results in me banging my head on the wall and saying, “This shouldn’t be this hard.” (I’m curious- does anyone else share this viewpoint/experience? Or are you lucky enough to have smooth sailing all or most of the time?)</p> <p>Anyway, I’ve learned to document the hell out of everything I do (I use Dokuwiki which happens to be

## How I setup a FOSS alternative to Google Maps timeline using Home Assistant and Grafana
 - [https://www.reddit.com/r/selfhosted/comments/1f0ycz1/how_i_setup_a_foss_alternative_to_google_maps](https://www.reddit.com/r/selfhosted/comments/1f0ycz1/how_i_setup_a_foss_alternative_to_google_maps)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T15:02:05+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1f0ycz1/how_i_setup_a_foss_alternative_to_google_maps/"> <img alt="How I setup a FOSS alternative to Google Maps timeline using Home Assistant and Grafana" src="https://preview.redd.it/1v4q4f1ertkd1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=69c21afb3490258c0e142d103e7dfd6621debf99" title="How I setup a FOSS alternative to Google Maps timeline using Home Assistant and Grafana" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/akjohn99"> /u/akjohn99 </a> <br /> <span><a href="https://i.redd.it/1v4q4f1ertkd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1f0ycz1/how_i_setup_a_foss_alternative_to_google_maps/">[comments]</a></span> </td></tr></table>

## Ollama server: Triple AMD GPU Upgrade
 - [https://www.reddit.com/r/selfhosted/comments/1f0xszf/ollama_server_triple_amd_gpu_upgrade](https://www.reddit.com/r/selfhosted/comments/1f0xszf/ollama_server_triple_amd_gpu_upgrade)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T14:37:42+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1f0xszf/ollama_server_triple_amd_gpu_upgrade/"> <img alt="Ollama server: Triple AMD GPU Upgrade" src="https://b.thumbs.redditmedia.com/vgn9m8LLq5nJLqj06VoQlolQCW1PU_AOnzG8Era8jDA.jpg" title="Ollama server: Triple AMD GPU Upgrade" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I recently upgraded my server build to support running Ollama. I added three accelerators to my system: two AMD MI100 accelerators and one AMD MI60. I initially configured two MI100 GPUs, but later required a third GPU to enable support for larger context windows with LLaMA 3.1. I reused my current motherboard, CPU, and RAM to keep additional hardware costs down. I'm now running LLaMA 3.1:70b-instruct-q6 with around 9 tokens per second (TPS).</p> <p><a href="https://preview.redd.it/75x2n4jgntkd1.jpg?width=4032&amp;format=pjpg&amp;auto=webp&amp;s=63bccf2ca50fdd2a3805358936752f4d3752dd71">https://preview.redd.it/75x2n4jgntkd1.jpg?width=4032

## phone backup with privacy for users
 - [https://www.reddit.com/r/selfhosted/comments/1f0xg4w/phone_backup_with_privacy_for_users](https://www.reddit.com/r/selfhosted/comments/1f0xg4w/phone_backup_with_privacy_for_users)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T14:21:53+00:00

<!-- SC_OFF --><div class="md"><p>I would like to use Nextcloud or another self-hosted service that allows me to automatically back up photos from my phone, both for me and my girlfriend. However, I would like it to offer privacy so that each user has their own folder, and only the owner of that folder can access it. Or the owner should be able to set a password in order that not even the root to not be able to access it. Is there such an application? Or can this be done with Nextcloud?</p> <p>P.S. For those who might comment off-topic, this isn't about hiding anything, but about peace of mind, ensuring that another user only has access to what you want them to access.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dull_Course_9076"> /u/Dull_Course_9076 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1f0xg4w/phone_backup_with_privacy_for_users/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/co

## pihole or nginxpm not adding http
 - [https://www.reddit.com/r/selfhosted/comments/1f0xb2m/pihole_or_nginxpm_not_adding_http](https://www.reddit.com/r/selfhosted/comments/1f0xb2m/pihole_or_nginxpm_not_adding_http)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T14:15:19+00:00

<!-- SC_OFF --><div class="md"><p>Hi.<br /> I have set up pihole and nginxpm so i can use my own internal addresses like doku.home.net.<br /> And it works except for one thing. And i dont know if its pihole, nginx or me beeing stupid, most likely the last one.<br /> But when i type out the address in any browser it does a search instead of opening the page. i have to manually add http:// in front to get it to work.<br /> And this is only for the internal addresses. Any external address i try works.</p> <p>There is nothing in the pihole query log for whatever internal address i try to access until i manually add http.</p> <p>Anyone seen this before? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tinyjello"> /u/tinyjello </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1f0xb2m/pihole_or_nginxpm_not_adding_http/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1f0xb2m/pihole_or_nginxpm_not

## Ready to build my first custom NAS
 - [https://www.reddit.com/r/selfhosted/comments/1f0wrnz/ready_to_build_my_first_custom_nas](https://www.reddit.com/r/selfhosted/comments/1f0wrnz/ready_to_build_my_first_custom_nas)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T13:49:52+00:00

<!-- SC_OFF --><div class="md"><p>Hello All,</p> <p>I have a Synology DS224+ that houses 2 x 18TB drives that I use for Radarr, Sonarr, and Plex. These apps all run in docker containers on my DS224+. I have about 6TB left on this NAS, but I have already purchased the components for a new custom NAS that I'd like to build.</p> <p>My new custom NAS contains the following components (all parts have been purchased and received):</p> <p>Chassis: Fractol Node 804<br /> Motherboard: ASRock B760M PRO RS/D4 (with separate Wifi internal adapter)<br /> CPU: Intel Core i3-14100 (integrated graphics)<br /> Memory: Corsair 2 x 16GB DDR4 3200MHz<br /> Raid Controller: LSI 9201-8i SAS PCI E Expander Card + SATA breakout cables<br /> Power Supply: Thermaltake Smart Series 500w PSU<br /> Storage: 2 x 18TB drive (currently in Synology NAS) and 1 additional 18TB drive I purchased from serverpartdeals</p> <p>I haven't started my physical build yet, but I've been researching how I'd like to set up the soft

## Accreditation/Badge System for Sports/Conferences
 - [https://www.reddit.com/r/selfhosted/comments/1f0w0kq/accreditationbadge_system_for_sportsconferences](https://www.reddit.com/r/selfhosted/comments/1f0w0kq/accreditationbadge_system_for_sportsconferences)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T13:12:15+00:00

<!-- SC_OFF --><div class="md"><p>Has anyone come across a accreditation/badge system for sports and/or conferences?</p> <p>Ideal with some customization with logos, access codes, sizes, participant's photo, etc.</p> <p>Participant data uploaded by CSV or directly in system.</p> <p>Indico (<a href="https://getindico.io/">https://getindico.io/</a>) has some of the above but no ability to print with the participants' photo.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rparker3-14"> /u/rparker3-14 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1f0w0kq/accreditationbadge_system_for_sportsconferences/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1f0w0kq/accreditationbadge_system_for_sportsconferences/">[comments]</a></span>

## Looking for NAS Recommendations RAID 5
 - [https://www.reddit.com/r/selfhosted/comments/1f0vlx1/looking_for_nas_recommendations_raid_5](https://www.reddit.com/r/selfhosted/comments/1f0vlx1/looking_for_nas_recommendations_raid_5)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T12:51:06+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I'm looking for a NAS that would best suit my needs. I'm not very knowledgeable when it comes to NAS devices, so I could really use some guidance.</p> <p>Currently, I have a home lab with a Proxmox server that runs a VM (Arr Suite) connected to a Plex VM (with GPU passthrough), some Docker projects, and a VM with OpenMediaVault with USB passthrough for all the data. All of this runs on the Proxmox server, and I’d like to store the data on a dedicated hardware NAS.</p> <p>My main objective is to separate the devices in case my primary server experiences a failure or a cyberattack, so the NAS remains unaffected. I’m also considering energy consumption as an important factor in my decision.</p> <p>I'm not looking for used equipment. For the sake of easier maintenance and peace of mind, I’m leaning towards pre-built NAS solutions.</p> <p>I’m looking for something that can handle the load in terms of network, CPU, and RAM, with RAID 5 (

## Selfhosted YouTube (Redirect all YouTube traffic)
 - [https://www.reddit.com/r/selfhosted/comments/1f0v5ra/selfhosted_youtube_redirect_all_youtube_traffic](https://www.reddit.com/r/selfhosted/comments/1f0v5ra/selfhosted_youtube_redirect_all_youtube_traffic)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T12:26:33+00:00

<!-- SC_OFF --><div class="md"><p>Hi, </p> <p>Currently working on de-Google my life. Made some great progress, now it time for YouTube. </p> <p>Already using NewPipe for years. However it only works on android When I am following tutorials online it often contains links to YouTube and it's YouTube.com website. So I did setup a selfhosted YouTube frontend (Invidious). Now I want to redirect all YouTube links to the selfhosted version. </p> <p>So that YouTube links like: <a href="https://youtube.com/watch?v=GrLpdfhTwLg">https://youtube.com/watch?v=GrLpdfhTwLg</a></p> <p>Get redirected to my ownselfhosted version, for example: <a href="https://yewtu.be/watch?v=GrLpdfhTwLg">https://yewtu.be/watch?v=GrLpdfhTwLg</a> (This is a hosted instance of Invidious just as example).</p> <p>What would be the best option to do this? Preferably network wide. I do have adguard home running. </p> <p>I was thinking about overwriting the YouTube.com domain with my own ip. Then create a website just with a 

## Minecraft bedrock server alternatives
 - [https://www.reddit.com/r/selfhosted/comments/1f0usqr/minecraft_bedrock_server_alternatives](https://www.reddit.com/r/selfhosted/comments/1f0usqr/minecraft_bedrock_server_alternatives)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T12:05:33+00:00

<!-- SC_OFF --><div class="md"><p>Currently using the excellent ITZG Minecraft bedrock container image to host a bedrock server.</p> <p>But as it uses the official Mojang server so logging is extremely limited - just join and leave messages (nothing ITZG could do about that, it's an upstream 'issue')</p> <p>Question is what are the alternative options? Ideally with better logging or plugins support for instance?</p> <p>Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Gravel_Sandwich"> /u/Gravel_Sandwich </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1f0usqr/minecraft_bedrock_server_alternatives/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1f0usqr/minecraft_bedrock_server_alternatives/">[comments]</a></span>

## [gently remainder] put a fan near your usb disks during summer, it really help
 - [https://www.reddit.com/r/selfhosted/comments/1f0sgqm/gently_remainder_put_a_fan_near_your_usb_disks](https://www.reddit.com/r/selfhosted/comments/1f0sgqm/gently_remainder_put_a_fan_near_your_usb_disks)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T09:27:30+00:00

<!-- SC_OFF --><div class="md"><p>Hi again, :)</p> <p>here is hot, home temp reachs 40 °C and disks temp is around 65 °C. Just bought and put a usb fan 140mm x 140mm very near my disks and the temp moves from 65 to 46 °C at the lowest speed!!!</p> <p>Lesson learned: keep disks fresh using a simple usb fan.</p> <p>Byeeeeeeeeee</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/wireless82"> /u/wireless82 </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1f0sgqm/gently_remainder_put_a_fan_near_your_usb_disks/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1f0sgqm/gently_remainder_put_a_fan_near_your_usb_disks/">[comments]</a></span>

## Is the Linksys WRT1900AC still worth it for $25 in 2024?
 - [https://www.reddit.com/r/selfhosted/comments/1f0m938/is_the_linksys_wrt1900ac_still_worth_it_for_25_in](https://www.reddit.com/r/selfhosted/comments/1f0m938/is_the_linksys_wrt1900ac_still_worth_it_for_25_in)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T02:35:36+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1f0m938/is_the_linksys_wrt1900ac_still_worth_it_for_25_in/"> <img alt="Is the Linksys WRT1900AC still worth it for $25 in 2024?" src="https://preview.redd.it/7wll599h2qkd1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=980c1c51a18589c33160489d14f8bf7bbcd2e59c" title="Is the Linksys WRT1900AC still worth it for $25 in 2024?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I came across a deal for a Linksys WRT1900AC Wi-Fi router for $25. Given that it’s an older model, I’m wondering if it’s still a good buy in 2024. Here are some quick specs:</p> <p>Dual-band: 2.4 GHz and 5 GHz Speed: Up to 1.9 Gbps Processor: 1.2 GHz dual-core RAM: 256 MB Ports: 4 Gigabit Ethernet, 1 USB 3.0, 1 eSATA/USB 2.0 combo How does it hold up in terms of performance, range, and reliability compared to more recent routers? Are there any specific issues I should be aware of?</p> <p>Thanks in advance for your insigh

## Use Github as a Bash Script Repo and only use one link for all your scripts!
 - [https://www.reddit.com/r/selfhosted/comments/1f0m8l3/use_github_as_a_bash_script_repo_and_only_use_one](https://www.reddit.com/r/selfhosted/comments/1f0m8l3/use_github_as_a_bash_script_repo_and_only_use_one)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T02:34:49+00:00

<!-- SC_OFF --><div class="md"><p>Hey fellow scripters!</p> <p>If you're anything like me, you’ve probably got a ton of bash scripts lying around that do all sorts of things—some automate tasks, some pull down data, all kinds of stuff. But let's be real, keeping track of all those scripts can get messy fast, especially when managing a lot of VMs.</p> <p>After one too many &quot;where the hell is that script&quot; moments when bootstrapping a new VM, I decided to figure out an easy way to put all my scripts in a repo and use just one script to index and run them. It’s basically a one-stop shop for any of my past scripts. Just one link to remember, and you can access all your scripts, neatly organized and ready to go.</p> <p>Here is the link:</p> <h1><a href="https://github.com/pitterpatter22/Script-Repo">Bash Master Script Repo</a></h1> <p><em>\</em> also available at* <a href="https://scripts.pitterpatter.io"><em>https://scripts.pitterpatter.io</em></a></p> <h1>What’s in the box?</h1>

## Secure Access Help
 - [https://www.reddit.com/r/selfhosted/comments/1f0jh70/secure_access_help](https://www.reddit.com/r/selfhosted/comments/1f0jh70/secure_access_help)
 - RSS feed: https://www.reddit.com/r/selfhosted/.rss
 - date published: 2024-08-25T00:08:21+00:00

<!-- SC_OFF --><div class="md"><p>I had a specific scenario I was hoping I could get some general advice for. I need to remote in to multiple computers, different days, different random PCs and run a script that connects to a server I have hosted internally, the script needs to connect just one time update and it’s done. What would be the easiest way to quickly create a tunnel or other way to be in and out in just a couple minutes max. I have successfully used Tailscale and it works, I was more interested in a way that would be faster without installing an App (Tailscale).</p> <p>Thank you for any help or ideas!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dreammerr"> /u/dreammerr </a> <br /> <span><a href="https://www.reddit.com/r/selfhosted/comments/1f0jh70/secure_access_help/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1f0jh70/secure_access_help/">[comments]</a></span>

