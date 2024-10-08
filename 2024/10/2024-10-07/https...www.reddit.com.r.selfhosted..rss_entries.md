# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## PSA: Those using TrueNAS, your SMB (CIFS) shares are not encrypted by default and how to fix that
 - [https://www.reddit.com/r/selfhosted/comments/1fyl6li/psa_those_using_truenas_your_smb_cifs_shares_are](https://www.reddit.com/r/selfhosted/comments/1fyl6li/psa_those_using_truenas_your_smb_cifs_shares_are)
 - RSS feed: $source
 - date published: 2024-10-07T22:56:06+00:00

<!-- SC_OFF --><div class="md"><p>After testing with wireshark, I discovered while using ubuntu that all my SMB traffic was going unencrypted. If a malicious device were to get on your network, they&#39;d be able to capture everything in plain text. Not everyone will need/care about encrypting LAN traffic, but here&#39;s a guide on how to do it in case anyone wants to. I use TrueNAS scale so I only know how to force encryption on Scale, and not Core.</p> <p>1) Open the shell in TrueNAS Scale via menu System Settings &gt; Shell</p> <p>2) type the command &#39;sudo nano /etc/smb4.conf&#39;</p> <p>3) Add the following to the bottom of the smb4.conf file, under the [global] line, make sure you keep the same number of spaces as the other settings that are already there under [global]. For me, it was 4 spaces.</p> <p>4) Add this line, without quotes to smb4.conf: smb encrypt = required</p> <p>5) Save and exit by using the command ctrl+O, then ctrl+X</p> <p>6) restart the SMB service in the 

## Well, I was an idiot and left pi-hole exposed to the outside world
 - [https://www.reddit.com/r/selfhosted/comments/1fykl8t/well_i_was_an_idiot_and_left_pihole_exposed_to](https://www.reddit.com/r/selfhosted/comments/1fykl8t/well_i_was_an_idiot_and_left_pihole_exposed_to)
 - RSS feed: $source
 - date published: 2024-10-07T22:28:45+00:00

<!-- SC_OFF --><div class="md"><p>Hi! I&#39;m your local idiot who left Pi-hole exposed by accident.</p> <p>I&#39;m still very new to hosting a server.</p> <p>In fact, worse than just being exposed and noticing, it&#39;s been exposed for probably a few months now.</p> <p>I run all of my server networking through my VPN which gives me a public IPV4 (love ovpn.com). So it would have been accessed through the VPN network, and not my home network. I don&#39;t port forward anything on my home network and everything on the VPN network runs through a reverse proxy on ports 80 and 443</p> <p>I&#39;ve since closed it in my firewall.</p> <p>Questions:</p> <ul> <li><p>What can be done to mitigate any potential problems?</p></li> <li><p>How likely am I to personally suffer any issues?</p></li> <li><p>Am I going to Hell now?</p></li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SapphicRain"> /u/SapphicRain </a> <br/> <span><a href="https://www.reddit.com

## How to rescue Proxmox vm's configuration?
 - [https://www.reddit.com/r/selfhosted/comments/1fyjiiv/how_to_rescue_proxmox_vms_configuration](https://www.reddit.com/r/selfhosted/comments/1fyjiiv/how_to_rescue_proxmox_vms_configuration)
 - RSS feed: $source
 - date published: 2024-10-07T21:42:04+00:00

<!-- SC_OFF --><div class="md"><p>I haven&#39;t been able to access Proxmox since I installed nvidia drivers and I locked myself out of the console with fail2ban... I know.. So, I decided to rescue Proxmox with the debug mode. I was able to activate LVM and also mounted the root partition in /dev/pve-root but even after doing this process, boot lands on grub console..</p> <p>At this point I think I need to do a fresh reinstall. But, I am wondering if there&#39;s any possible way to move VM&#39;s configuration out of that disk to another one where proxmox is not installed? so that I can at least save the files and use them on a fresh install? I&#39;d appreciate your input or advice.</p> <p>Below are the steps I followed according to the documentation of Proxmox Wiki</p> <p>Recovering</p> <p>&quot;You can use Proxmox installation ISO in verison 5.4 or newer, and select debug mode. On the second prompt you&#39;ll have the full Linux tools, including LVM, ZFS, ..., available. If you exit 

## Rate/Suggestions of my Setup?
 - [https://www.reddit.com/r/selfhosted/comments/1fyjakh/ratesuggestions_of_my_setup](https://www.reddit.com/r/selfhosted/comments/1fyjakh/ratesuggestions_of_my_setup)
 - RSS feed: $source
 - date published: 2024-10-07T21:32:55+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fyjakh/ratesuggestions_of_my_setup/"> <img src="https://preview.redd.it/19v84qjkketd1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=d66ff6b9b214a35ddedbd005d755b8a91211bdcf" alt="Rate/Suggestions of my Setup?" title="Rate/Suggestions of my Setup?" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Big_Presentation9502"> /u/Big_Presentation9502 </a> <br/> <span><a href="https://i.redd.it/19v84qjkketd1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fyjakh/ratesuggestions_of_my_setup/">[comments]</a></span> </td></tr></table>

## Update of TrueNAS for Jellyfin
 - [https://www.reddit.com/r/selfhosted/comments/1fyj1q8/update_of_truenas_for_jellyfin](https://www.reddit.com/r/selfhosted/comments/1fyj1q8/update_of_truenas_for_jellyfin)
 - RSS feed: $source
 - date published: 2024-10-07T21:22:42+00:00

<!-- SC_OFF --><div class="md"><p>Hello!</p> <p>Noob here, so I hope I dont produce a lot of face palms. And if I do - I hope they dont hurt :D</p> <p>So, I get the notification that I have to update my TrueNAS or otherwise after the next Update I wont be able to run Jellyfin anymore. If I go to System -&gt; Update, it states that my TrueNAS SCALE Bluefin 22.12 Legacy reached &quot;end of life&quot;.</p> <p>I suppose I have to update... but to what, would be the question. What is the smoothest, Noob-friendliest choice I can make? (Cobia? Dragonfish? ElectricEel?) And should I make a separate backup? Atm I have two separete stripe partitions, one is my drive for Jellyfin and the other is basically a (manual) Backup. Both are shared via SMB.</p> <p>Thanks for any advice!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Slow_Pay_7171"> /u/Slow_Pay_7171 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fyj1q8/update_of_truenas_fo

## Best Setup for Running AMP on TrueNAS Scale: Docker vs. VM for Game Server Management?
 - [https://www.reddit.com/r/selfhosted/comments/1fyj0tz/best_setup_for_running_amp_on_truenas_scale](https://www.reddit.com/r/selfhosted/comments/1fyj0tz/best_setup_for_running_amp_on_truenas_scale)
 - RSS feed: $source
 - date published: 2024-10-07T21:21:40+00:00

<!-- SC_OFF --><div class="md"><p>With the TrueNAS Scale Electric Eel stable release approaching, I’m exploring the possibility of running AMP (Application Management Panel) entirely in a Docker container. I’ve found a Dockerized version of AMP, but I’m uncertain if it will work seamlessly on TrueNAS Scale. Specifically, I’m considering running the AMP Controller on my Windows laptop to handle the web server while using the Docker integration on my TrueNAS server to act as the target for AMP. This would allow AMP to generate and manage game server instances in Docker on TrueNAS.</p> <p>Alternatively, I could install a Linux VM on TrueNAS Scale and run AMP there, but I’m concerned about the potential performance penalty. Could anyone advise on the best approach, and whether running AMP in Docker on TrueNAS would be more efficient than using a VM or if I should just run a Minecraft server directly using docker?</p> <p>What is the performance impact of running a VM with AMP running conta

## Self hosted Webmailer
 - [https://www.reddit.com/r/selfhosted/comments/1fyizfi/self_hosted_webmailer](https://www.reddit.com/r/selfhosted/comments/1fyizfi/self_hosted_webmailer)
 - RSS feed: $source
 - date published: 2024-10-07T21:20:04+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys, I got an interesting issue which I can&#39;t quite grasp due to my lack of experience with Mail clients, mail servers etc. </p> <p>I work in an NGO which uses one of the many small hoster to host their domain and email. </p> <p>The web interface for the webmailer of this hoster is terrible and lacks some basic features. </p> <p>My plan now was to host a web-based mailer for all of the people involved to use, I got some servers running with enough capacity to run this, which are public, secure and used for my work.</p> <p>Spinning up a VM for this is not an issue.</p> <p>Now to the interesting question, the tools need to handle shared mailboxes, currently archived by sharing a password, a little more better, as well as personalized mails. Ideally with the same credentials to the new program. </p> <p>Have you guys any idea which tool to use? </p> <p>Edit: spelling, formatting </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://w

## What are you using to managed keys and credentials?
 - [https://www.reddit.com/r/selfhosted/comments/1fyixc0/what_are_you_using_to_managed_keys_and_credentials](https://www.reddit.com/r/selfhosted/comments/1fyixc0/what_are_you_using_to_managed_keys_and_credentials)
 - RSS feed: $source
 - date published: 2024-10-07T21:17:37+00:00

<!-- SC_OFF --><div class="md"><p>I have a bunch of small apps and services and I want to keep keys for external services somewhere in my system. At the moment I’m using 1Password cli but tbh it’s a bit of a pain in the arse.</p> <p>Been considering using Vault, but looking for good local solutions.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/temporaryuser1000"> /u/temporaryuser1000 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fyixc0/what_are_you_using_to_managed_keys_and_credentials/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fyixc0/what_are_you_using_to_managed_keys_and_credentials/">[comments]</a></span>

## Connection of 2 Home Server in different homes/locations
 - [https://www.reddit.com/r/selfhosted/comments/1fygzyy/connection_of_2_home_server_in_different](https://www.reddit.com/r/selfhosted/comments/1fygzyy/connection_of_2_home_server_in_different)
 - RSS feed: $source
 - date published: 2024-10-07T19:58:26+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys,</p> <p>I have actually 2 homes where I have a NAS in the first home and bought a mini pc for the 2nd home.</p> <p>Is there a possibility to connect somehow the 2 server together? I realized how much faster the mini pc is, since it uses also a ssd and has a much faster CPU. The NAS is really perfect for hosting and saving my data (paperless, Immich, etc.) but since I saw how good Home Assistant is performing on the mini pc, I thought about connecting somehow both server (NAS as VPN Server, Mini PC as client) and controller my IoT devices at the first home with the mini pc at the 2nd home. </p> <p>Is this idea trash or is something like that feasible?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/fitim92"> /u/fitim92 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fygzyy/connection_of_2_home_server_in_different/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/sel

## Webite hosted through Cloudflared tunnel not showing images
 - [https://www.reddit.com/r/selfhosted/comments/1fygs3r/webite_hosted_through_cloudflared_tunnel_not](https://www.reddit.com/r/selfhosted/comments/1fygs3r/webite_hosted_through_cloudflared_tunnel_not)
 - RSS feed: $source
 - date published: 2024-10-07T19:49:22+00:00

<!-- SC_OFF --><div class="md"><p>I hosted a wordpress website on a raspberry pi using cloudflared tunnels but when I try to access the website, images don&#39;t show up (they show up perfectly fine on my local network). I did not face this issue while hosting a django website. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dark_AvengerX"> /u/Dark_AvengerX </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fygs3r/webite_hosted_through_cloudflared_tunnel_not/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fygs3r/webite_hosted_through_cloudflared_tunnel_not/">[comments]</a></span>

## Need Vaultwarden recommendation for backups.
 - [https://www.reddit.com/r/selfhosted/comments/1fyg5u6/need_vaultwarden_recommendation_for_backups](https://www.reddit.com/r/selfhosted/comments/1fyg5u6/need_vaultwarden_recommendation_for_backups)
 - RSS feed: $source
 - date published: 2024-10-07T19:23:33+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fyg5u6/need_vaultwarden_recommendation_for_backups/"> <img src="https://external-preview.redd.it/9EKkYuUINeqKsk8YAz_fwS6kOF45_JdHoNF5-lXL_Kw.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=e8bc54a48a5960635aa3ba289e1458bad4ca0cdc" alt="Need Vaultwarden recommendation for backups. " title="Need Vaultwarden recommendation for backups. " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello, </p> <p>If you need more info or context, let me know, i am currently in the planning &quot;phase&quot;, i have got Vaultwarden up and running as a test, and i&#39;d like to know more about the backup solutions. I have looked into <a href="https://github.com/Bruceforce/vaultwarden-backup">Bruceforce/Vaultwarden-backup</a> and <a href="https://github.com/davidnemec/bitwarden-to-keepass">Bitwarden-to-keepass</a>, if there are other solutions, inform me. </p> <p>I plan on moving from google drive shared KeePass over to bitwarde

## Trying to send mail from multiple services behind a reverse proxy
 - [https://www.reddit.com/r/selfhosted/comments/1fyfc43/trying_to_send_mail_from_multiple_services_behind](https://www.reddit.com/r/selfhosted/comments/1fyfc43/trying_to_send_mail_from_multiple_services_behind)
 - RSS feed: $source
 - date published: 2024-10-07T18:49:50+00:00

<!-- SC_OFF --><div class="md"><p>I really don&#39;t know how to Google this.</p> <p>I have a few services behind an nginx reverse proxy and I want them to be able to send email. I have Zoho mail and the SMTP and I was able to get one service set up using Streams in NPM but I don&#39;t know where to go from here for multiple services.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/wolfej4"> /u/wolfej4 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fyfc43/trying_to_send_mail_from_multiple_services_behind/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fyfc43/trying_to_send_mail_from_multiple_services_behind/">[comments]</a></span>

## Using a .app domain for local network
 - [https://www.reddit.com/r/selfhosted/comments/1fyf4cs/using_a_app_domain_for_local_network](https://www.reddit.com/r/selfhosted/comments/1fyf4cs/using_a_app_domain_for_local_network)
 - RSS feed: $source
 - date published: 2024-10-07T18:41:00+00:00

<!-- SC_OFF --><div class="md"><p>Could it make sense to use a .app domain for a local network if other TLDs with my desired name are taken? Would there be any limitations specifically related to this TLD that should be considered?</p> <p>For context, I have another domain I use externally for email, but I’d like to have a separate one to be used internally.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/VoyagingRedditor"> /u/VoyagingRedditor </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fyf4cs/using_a_app_domain_for_local_network/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fyf4cs/using_a_app_domain_for_local_network/">[comments]</a></span>

## Dedicated game server public ip
 - [https://www.reddit.com/r/selfhosted/comments/1fyewxb/dedicated_game_server_public_ip](https://www.reddit.com/r/selfhosted/comments/1fyewxb/dedicated_game_server_public_ip)
 - RSS feed: $source
 - date published: 2024-10-07T18:32:23+00:00

<!-- SC_OFF --><div class="md"><p>Hello, today i am running my server through a vpn with dedicated ip and port forward function. It works but add to much to latency. </p> <p>I am thinking stop Using the vpn and port forward in my router, my isp provider dont have static ip but i have public ip. So was wondering if anyone knows if i can set a static ip on my dedicated pc or maybe get so my players connect to a domain name whether the ip change or not?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Tobbeyninesix"> /u/Tobbeyninesix </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fyewxb/dedicated_game_server_public_ip/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fyewxb/dedicated_game_server_public_ip/">[comments]</a></span>

## How to create self hosted siyuan to enable sync between devices in the app
 - [https://www.reddit.com/r/selfhosted/comments/1fyepza/how_to_create_self_hosted_siyuan_to_enable_sync](https://www.reddit.com/r/selfhosted/comments/1fyepza/how_to_create_self_hosted_siyuan_to_enable_sync)
 - RSS feed: $source
 - date published: 2024-10-07T18:24:30+00:00

<!-- SC_OFF --><div class="md"><p>Siyuan is app that looks like notion but open source and works offline. The only issue is that to enable sync feature you have to pay $64 which is a lot in EGP. So I read that I can self host it and enable sync, My Question is how?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Haleem97"> /u/Haleem97 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fyepza/how_to_create_self_hosted_siyuan_to_enable_sync/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fyepza/how_to_create_self_hosted_siyuan_to_enable_sync/">[comments]</a></span>

## Safely sharing services WAN
 - [https://www.reddit.com/r/selfhosted/comments/1fye6um/safely_sharing_services_wan](https://www.reddit.com/r/selfhosted/comments/1fye6um/safely_sharing_services_wan)
 - RSS feed: $source
 - date published: 2024-10-07T18:02:40+00:00

<!-- SC_OFF --><div class="md"><p>What am I missing… looking for some guidance. Right now I have an unraid server up and running, mainly storing and serving media. I have set up a Tailscale network as a way to access my services outside of my LAN (love this btw)..</p> <p>How do I host, or share, say audiobookshelf library with a friend. Recently I’ve tried to set them up as a user with Tailscale, and a third party app (plappa)but could not get that working.. I’m thinking I need to host or point my server to a domain or webpage, then create an account for them with audiobookshelf, and hand them the proper domain name? Do I need nginx? Cloudflare? Traffik???</p> <p>Idk… I just feel like in missing a piece here. What exactly is this process called. Is it ‘self-hosting’ the audiobookshelf app? </p> <p>I just want to make sure I go about this properly and securely too… don’t want to just dive in a start port forwarding without understanding what needs to be done.</p> <p>Thanks for the help

## What services are you willing to pay for?
 - [https://www.reddit.com/r/selfhosted/comments/1fye6q6/what_services_are_you_willing_to_pay_for](https://www.reddit.com/r/selfhosted/comments/1fye6q6/what_services_are_you_willing_to_pay_for)
 - RSS feed: $source
 - date published: 2024-10-07T18:02:33+00:00

<!-- SC_OFF --><div class="md"><p>Just curious for all of the selfhosters, what services/programs are you willing to pay for (if any) Whether is a subscription or one time payment.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Philthyzz"> /u/Philthyzz </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fye6q6/what_services_are_you_willing_to_pay_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fye6q6/what_services_are_you_willing_to_pay_for/">[comments]</a></span>

## Is an N100 overkill for the setup I am planning? Any recommendations for a newbie?
 - [https://www.reddit.com/r/selfhosted/comments/1fye54i/is_an_n100_overkill_for_the_setup_i_am_planning](https://www.reddit.com/r/selfhosted/comments/1fye54i/is_an_n100_overkill_for_the_setup_i_am_planning)
 - RSS feed: $source
 - date published: 2024-10-07T18:00:52+00:00

<!-- SC_OFF --><div class="md"><p>i am currently using a raspberry pi 3b+ as my server running the following - arr downloader, dns, file server (2 hard drives) and note taking. for quite some time now it has been okay, but since the raspberry pi 3b+ only uses usb 2.0 the transfer speed are very very VERY slow. i dont mind the transfer speed being slow since i mainly just store backups that i do not access. i rarely store something that i access often. </p> <p>recently i had the time and itch again to look at selfhosting such as new things to self host and new hardware. one of the things that i immediately read are about the n100 cpus and immediately got curious with all the fuzz around n100 cpus being very efficient while being relatively powerful.</p> <p>i have also read about other singe board computers that are cheap and can more or less rival the raspberry pi interms of specs. i also got interested by the products of libre computer, specifically the Libre Computer Renegade ROC-RK3

## I suspect one of my selfhosted services gave away my data to a third-party
 - [https://www.reddit.com/r/selfhosted/comments/1fye2k5/i_suspect_one_of_my_selfhosted_services_gave_away](https://www.reddit.com/r/selfhosted/comments/1fye2k5/i_suspect_one_of_my_selfhosted_services_gave_away)
 - RSS feed: $source
 - date published: 2024-10-07T17:58:10+00:00

<!-- SC_OFF --><div class="md"><p>I host all my services locally on a server, behind a reverse proxy, using a domain, let&#39;s say blub.xyz. They are mostly accessible only from within the network. Others are publicly available via CF tunnels.</p> <p>So, whenever a service has some sort of user email, etc I use <a href="mailto:username@blub.xyz">username@blub.xyz</a> when creating new users.</p> <p>blub.xyz has also valid MX entries, that point to fastmail, since I&#39;ve configured my printer to send scanned documents to that domain. The printer is on a restricted VLAN and can only communicate over the SMTP port with the internet.</p> <p>However, yesterday I received an email from snapchat to <a href="mailto:gh-567433@blub.xyz">gh-567433@blub.xyz</a>! it seems they&#39;ve exploited a catch-all alias that is otherwise NOWHERE publicly available. I also never used that email on any of my services.</p> <p>Is it valid to suspect a service in doing this, or is this just a common scheme t

## Is this configuration possible (he asked naively)?
 - [https://www.reddit.com/r/selfhosted/comments/1fydnsr/is_this_configuration_possible_he_asked_naively](https://www.reddit.com/r/selfhosted/comments/1fydnsr/is_this_configuration_possible_he_asked_naively)
 - RSS feed: $source
 - date published: 2024-10-07T17:41:22+00:00

<!-- SC_OFF --><div class="md"><ol> <li>Register domain with InterServer which is nice and local to me (I&#39;m in NY, they&#39;re in NJ);</li> <li>Set up Cloudflare to point DNS records to the right place(s);</li> <li>As I can&#39;t get a fixed IP address from my ISP, use Cloudflare&#39;s API with a script to turn on DynDNS;</li> <li>Install RHEL 9 on an inexpensive bare-metal home server and use a Cloudflare tunnel to permit access to my website;;</li> <li>Take advantage of Cloudfare&#39;s protection against DDOS attacks;</li> <li>(Sleep soundly at night.)</li> </ol> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/KryptonSurvivor"> /u/KryptonSurvivor </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fydnsr/is_this_configuration_possible_he_asked_naively/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fydnsr/is_this_configuration_possible_he_asked_naively/">[comments]</a></span>

## Mini PC specs - recommendations?
 - [https://www.reddit.com/r/selfhosted/comments/1fycabn/mini_pc_specs_recommendations](https://www.reddit.com/r/selfhosted/comments/1fycabn/mini_pc_specs_recommendations)
 - RSS feed: $source
 - date published: 2024-10-07T16:44:47+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a pc to self host some containers. I currently run a rpi4 and Synology with about 15+ docker containers between them. I&#39;d like to run Frigate but I&#39;m not sure the rpi or Synology will handle it. I already have a dedicated NVR, I mostly just want person and object detection from my 8 4k cameras.</p> <p>I am thinking about getting a pc to run proxmox. Mostly just to run frigate, but I&#39;d likely move all the containers away from the Synology and RPI to the PC too. What kinds of specs should I consider? I know you can get some USFF units pretty cheap, but how old should I go on the processor?</p> <p>I would prefer a low energy consumption unit. </p> <p>I&#39;m currently running: Home assistant Mqtt Zigbee2mqtt Portainer Nodered Jellyfin Go2rtc Esphome Syncthing Firefly Mealie Monica Paperless ngx Photo prism Scanservjs Pihole Uptime kuma</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/djch

## In need of an easy setup cloud system on windows server
 - [https://www.reddit.com/r/selfhosted/comments/1fybxrk/in_need_of_an_easy_setup_cloud_system_on_windows](https://www.reddit.com/r/selfhosted/comments/1fybxrk/in_need_of_an_easy_setup_cloud_system_on_windows)
 - RSS feed: $source
 - date published: 2024-10-07T16:30:18+00:00

<!-- SC_OFF --><div class="md"><p>In need of an easy clound to setup on windows server (curently used for plex) i want to store pictures and videos with easy access to files with phone over internet i dont mind paying if needed. I know linux is better but i know nothing about linux im a noob at servers.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OnlyShowel4U"> /u/OnlyShowel4U </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fybxrk/in_need_of_an_easy_setup_cloud_system_on_windows/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fybxrk/in_need_of_an_easy_setup_cloud_system_on_windows/">[comments]</a></span>

## Need some help with nginx in Docker
 - [https://www.reddit.com/r/selfhosted/comments/1fybx1z/need_some_help_with_nginx_in_docker](https://www.reddit.com/r/selfhosted/comments/1fybx1z/need_some_help_with_nginx_in_docker)
 - RSS feed: $source
 - date published: 2024-10-07T16:29:33+00:00

<!-- SC_OFF --><div class="md"><p>Hey there,</p> <p>First time trying to setup a web server / reverse proxy in order for Tandoor (the recipe manager) to work. And I CANNOT for the life of me get it working.</p> <p>I only want a very simple solution where traffic on port a specific high port (let&#39;s say 12345) will . I am NOT looking for SSL via let&#39;s encrypt or anything like that right now - I just want the traffic to work.</p> <p>I&#39;ve followed these instructions: <a href="https://docs.tandoor.dev/install/docker/#plain">Docker - Tandoor Recipes</a></p> <p>I&#39;ve literally set it up exactly as the &quot;plain&quot; config, except I open 12345 instead of 80 (I&#39;ve tried with 80 and get the same issue as below).</p> <p>The nginx config looks like this:</p> <pre><code>server { listen 80; server_name recipes.myrealdomain.com; } </code></pre> <p>If I configure the ports on the Tandoor container itself, and set the inner port to 8080 (that&#39;s what it listens on) everything

## What do you host for friends and family? Looking for inspo
 - [https://www.reddit.com/r/selfhosted/comments/1fybe6s/what_do_you_host_for_friends_and_family_looking](https://www.reddit.com/r/selfhosted/comments/1fybe6s/what_do_you_host_for_friends_and_family_looking)
 - RSS feed: $source
 - date published: 2024-10-07T16:07:51+00:00

<!-- SC_OFF --><div class="md"><p>A home server seems like a great idea for anyone technically inclined to deepen their knowledge while helping others, but I’m not seeing many valuable use cases outside of enterprise.</p> <p>About a year ago I bought a bunch of PC parts thinking I was going to become a networking whiz with a DIY router, HTPC, and a dedicated Plex server running nothing but Arch.</p> <p>After going off into the deep end I learned that I’m fine learning and troubleshooting for hours on end only if it will save time in the future and have a positive impact on others.</p> <p>Since then I have paired it all down to a simple 60TB Truenas Server with Nextcloud and Plex. (DMM, RD and Jdownloader2 for acquisitions) But even then, the UI for both makes it difficult for people to make the switch completely.</p> <p>It makes me wonder now…</p> <p>What am I missing?</p> <p>Are there any services you host other than Plex and Nextcloud that your friends/family can&#39;t live without?

## Software for synchronizing smb folders
 - [https://www.reddit.com/r/selfhosted/comments/1fyaksy/software_for_synchronizing_smb_folders](https://www.reddit.com/r/selfhosted/comments/1fyaksy/software_for_synchronizing_smb_folders)
 - RSS feed: $source
 - date published: 2024-10-07T15:34:48+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I probably come here to create my first post asking for help from you, who have helped a lot with my research and doubts, but this time I can&#39;t find a solution to what I want in old posts.</p> <p>I have several servers and services hosted at home and have only recently started to pay attention to backups.</p> <p>I have 3 locations to store my backups, one on my main unraid server, one on the synology server (server set up just for backups) and the last one on a hetzner storage box (also just for backups). </p> <p>I need your help because I&#39;m looking for a self-hosted solution, preferably, that allows me to keep these 3 folders (I use smb shares in all 3) synchronized. </p> <p>I preferred a solution that had some interface and not command lines</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/polkapwen"> /u/polkapwen </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fyaksy/softw

## how would i host my own email dervice
 - [https://www.reddit.com/r/selfhosted/comments/1fya1h7/how_would_i_host_my_own_email_dervice](https://www.reddit.com/r/selfhosted/comments/1fya1h7/how_would_i_host_my_own_email_dervice)
 - RSS feed: $source
 - date published: 2024-10-07T15:12:28+00:00

<!-- SC_OFF --><div class="md"><p>I already have an email server running on a debian server with postfix. What im asking now is how can i make it a service where people can create an account, hopefully invite only. Does anyone have any idea of where i should look to get some documentation to make this possible? I do not want to use docker btw.</p> <p>If you need any more info ask pls</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SortIndependent6682"> /u/SortIndependent6682 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fya1h7/how_would_i_host_my_own_email_dervice/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fya1h7/how_would_i_host_my_own_email_dervice/">[comments]</a></span>

## Any way for Caddy to start/stop docker containers?
 - [https://www.reddit.com/r/selfhosted/comments/1fy9yt4/any_way_for_caddy_to_startstop_docker_containers](https://www.reddit.com/r/selfhosted/comments/1fy9yt4/any_way_for_caddy_to_startstop_docker_containers)
 - RSS feed: $source
 - date published: 2024-10-07T15:09:23+00:00

<!-- SC_OFF --><div class="md"><p>I have an AI stack in Portainer accessible on <a href="http://ai.example.com">ai.example.com</a> and the goal is to have it stop after being inactive for so long but then if I visit <a href="http://ai.example.com">ai.example.com</a> for the stack to start again. Is Caddy capable of something like this, or what would be the best approach?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bod09"> /u/bod09 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy9yt4/any_way_for_caddy_to_startstop_docker_containers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy9yt4/any_way_for_caddy_to_startstop_docker_containers/">[comments]</a></span>

## What are your top 3 things that you self host now?
 - [https://www.reddit.com/r/selfhosted/comments/1fy9ydr/what_are_your_top_3_things_that_you_self_host_now](https://www.reddit.com/r/selfhosted/comments/1fy9ydr/what_are_your_top_3_things_that_you_self_host_now)
 - RSS feed: $source
 - date published: 2024-10-07T15:08:52+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Mike_v_E"> /u/Mike_v_E </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy9ydr/what_are_your_top_3_things_that_you_self_host_now/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy9ydr/what_are_your_top_3_things_that_you_self_host_now/">[comments]</a></span>

## Favorite way to store knowledge?
 - [https://www.reddit.com/r/selfhosted/comments/1fy9hf6/favorite_way_to_store_knowledge](https://www.reddit.com/r/selfhosted/comments/1fy9hf6/favorite_way_to_store_knowledge)
 - RSS feed: $source
 - date published: 2024-10-07T14:49:31+00:00

<!-- SC_OFF --><div class="md"><p>As I&#39;m building up my home lab I&#39;m starting to host a large number of services with an equally large number of requirements, scripts, etc to keep them running.</p> <p>I just installed trilium because I thought it might be good for that kind of work, but its less wiki and more notes (yes it can do a lot with scripting inside of it, but the process is slower than a modern wiki like confluence).</p> <p>What is everyone using to keep track of what is going on in their home lab?</p> <ul> <li>What are you using for flowcharts?</li> <li>What are you using as a knowledge base / wiki?</li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dust-cell"> /u/dust-cell </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy9hf6/favorite_way_to_store_knowledge/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy9hf6/favorite_way_to_store_knowledge/">[comments]</a></

## Kamal 2: Getting Started From Zero — A simple, lightweight Docker deployment tool.
 - [https://www.reddit.com/r/selfhosted/comments/1fy95en/kamal_2_getting_started_from_zero_a_simple](https://www.reddit.com/r/selfhosted/comments/1fy95en/kamal_2_getting_started_from_zero_a_simple)
 - RSS feed: $source
 - date published: 2024-10-07T14:35:23+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fy95en/kamal_2_getting_started_from_zero_a_simple/"> <img src="https://external-preview.redd.it/wa1uuSr5U-MqAtHxV9DuNRnch5eqMH6P0PiJa38kXWs.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=a2be69e65a04b413f8b6920a524926aa4d3c0fbe" alt="Kamal 2: Getting Started From Zero — A simple, lightweight Docker deployment tool." title="Kamal 2: Getting Started From Zero — A simple, lightweight Docker deployment tool." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ptuladhar3"> /u/ptuladhar3 </a> <br/> <span><a href="https://medium.com/@ptuladhar3/kamal-2-getting-started-from-zero-b3f0795a29e9">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy95en/kamal_2_getting_started_from_zero_a_simple/">[comments]</a></span> </td></tr></table>

## Web based PDF library/viewer? Kinda like Plex for books
 - [https://www.reddit.com/r/selfhosted/comments/1fy8yrb/web_based_pdf_libraryviewer_kinda_like_plex_for](https://www.reddit.com/r/selfhosted/comments/1fy8yrb/web_based_pdf_libraryviewer_kinda_like_plex_for)
 - RSS feed: $source
 - date published: 2024-10-07T14:27:32+00:00

<!-- SC_OFF --><div class="md"><p>Basically the title. </p> <p>I have Sonarr and Radarr setup to auto download TV shows and movies respectively, I can browse this library and watch it with something like Plex.</p> <p>What&#39;s the equivalent of Plex for ebooks/PDFs?</p> <p>I&#39;ve recently installed Readarr into my *arr stack and I&#39;m struggling to figure out what&#39;s the best client (web-based) to be able to consume the stuff that Readarr downloads. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/feo_ZA"> /u/feo_ZA </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy8yrb/web_based_pdf_libraryviewer_kinda_like_plex_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy8yrb/web_based_pdf_libraryviewer_kinda_like_plex_for/">[comments]</a></span>

## Accessing websevers by name with different ports
 - [https://www.reddit.com/r/selfhosted/comments/1fy8xc2/accessing_websevers_by_name_with_different_ports](https://www.reddit.com/r/selfhosted/comments/1fy8xc2/accessing_websevers_by_name_with_different_ports)
 - RSS feed: $source
 - date published: 2024-10-07T14:25:48+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys!</p> <p>I&#39;m currently setting up a system that allows easy access to my servers through a browser, using only their hostnames. The infrastructure consists of several web servers running in separate LXC containers on a Proxmox host, as well as a Raspberry Pi that runs <strong>Gokrazy</strong>.</p> <p>To handle DNS resolution across this network, I’ve created an LXC container dedicated to running <strong>dnsmasq</strong> as the DNS server.</p> <p>The goal is to simplify navigation by typing just the hostname (e.g., <code>cam.brun0.lan</code>) in the browser, without needing to remember or enter specific IPs or port numbers.</p> <p>This is my dnsmasq.conf content</p> <pre><code>root@dnsmasq:~# grep -v -e &quot;^#&quot; -e &quot;^$&quot; /etc/dnsmasq.conf domain-needed bogus-priv no-resolv local=/brun0.lan/ expand-hosts domain=brun0.lan server=8.8.8.8 </code></pre> <p>Then I added the following to /etc/hosts</p> <pre><code>192.168.30.3 proxmox

## How can i secure my home server as a beginner?
 - [https://www.reddit.com/r/selfhosted/comments/1fy8v9x/how_can_i_secure_my_home_server_as_a_beginner](https://www.reddit.com/r/selfhosted/comments/1fy8v9x/how_can_i_secure_my_home_server_as_a_beginner)
 - RSS feed: $source
 - date published: 2024-10-07T14:23:17+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve recently installed ubuntu on an old computer and i port forwarded two ports (one for ssh on a random high number public port and one for deluge web-ui docker container). I&#39;ve also connected my public ip to duckdns to access my server remotely more easily. Now, i haven&#39;t done anything other than these things i&#39;ve mentioned and the only thing that i know i could do is setup Fail2ban. What other procedures can i take to make my server more secure?</p> <p>Edit: thanks, I highly appreciate your advice guys and I just closed my ssh port before making any changes. Now I just need to understand what you&#39;re telling me to do because I&#39;m reading tool names I have never heard about. Sorry I&#39;m still learning</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/s1r-william"> /u/s1r-william </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy8v9x/how_can_i_secure_my_home_server_

## octopod: A UI for Docker Registries
 - [https://www.reddit.com/r/selfhosted/comments/1fy8fe2/octopod_a_ui_for_docker_registries](https://www.reddit.com/r/selfhosted/comments/1fy8fe2/octopod_a_ui_for_docker_registries)
 - RSS feed: $source
 - date published: 2024-10-07T14:04:08+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fy8fe2/octopod_a_ui_for_docker_registries/"> <img src="https://external-preview.redd.it/BmAu75tWzpfSlCIlhgIraPZvbJ-EauPzUXBU3x4os1Y.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=f4c4f7592c7aa54d819f744c6553738b14ccba67" alt="octopod: A UI for Docker Registries" title="octopod: A UI for Docker Registries" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jogai-san"> /u/jogai-san </a> <br/> <span><a href="https://github.com/frectonz/octopod">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy8fe2/octopod_a_ui_for_docker_registries/">[comments]</a></span> </td></tr></table>

## Looking for a Self-Hosted App to Track Appliances & Other Product Info
 - [https://www.reddit.com/r/selfhosted/comments/1fy8f2g/looking_for_a_selfhosted_app_to_track_appliances](https://www.reddit.com/r/selfhosted/comments/1fy8f2g/looking_for_a_selfhosted_app_to_track_appliances)
 - RSS feed: $source
 - date published: 2024-10-07T14:03:44+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a self-hosted solution that allows me to keep track of household appliances and products. Ideally, I&#39;d like to catalog things like purchase date, warranty info, model numbers, serial numbers, manuals (digitized PDFs), and maintenance schedules. The goal is to have everything in one place to make troubleshooting easier and keep track of the lifespan and care of these items. Paperless-ngx and/or spreadsheets are on the table as potential options, but I would love to know if a purpose-built self-hosted solution may already exist.</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/heroicjunk"> /u/heroicjunk </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy8f2g/looking_for_a_selfhosted_app_to_track_appliances/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy8f2g/looking_for_a_selfhosted_app_to_track_applianc

## Father and son activity
 - [https://www.reddit.com/r/selfhosted/comments/1fy88sy/father_and_son_activity](https://www.reddit.com/r/selfhosted/comments/1fy88sy/father_and_son_activity)
 - RSS feed: $source
 - date published: 2024-10-07T13:56:29+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fy88sy/father_and_son_activity/"> <img src="https://preview.redd.it/1b1eogj5bctd1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=47e827701a012a38191d1b8aaa68cddc521c3b5e" alt="Father and son activity" title="Father and son activity" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Just wanted to share a happy moment I&#39;m having. </p> <p>My dad and I are building an unraid server, for now I&#39;m still showing him a lot of stuff, but I know my knowledge will be surpassed by his in a while. For now I&#39;m just appreciating the fact that I can teach him something for a while! Rog strix z790e 12900k - arctic liquid freezer III 420mm 64gb ddr5 4 x 8tb ironwolf pro, incl. Dual parity 2 x 1tb sn850x pool Tripp lite 1500av ups</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SergeJeante"> /u/SergeJeante </a> <br/> <span><a href="https://i.redd.it/1b1eogj5bctd1.jpeg">[link]</

## I just successfully set up my matrix server, does it matter if TLS for TURN is not enabled ?
 - [https://www.reddit.com/r/selfhosted/comments/1fy7hdf/i_just_successfully_set_up_my_matrix_server_does](https://www.reddit.com/r/selfhosted/comments/1fy7hdf/i_just_successfully_set_up_my_matrix_server_does)
 - RSS feed: $source
 - date published: 2024-10-07T13:22:09+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I recently set up a matrix server and it seems to be working just fine (messages <strong>and</strong> calls are good) but just one little thing is bugging my mind.</p> <p>I did not set up TLS for my eturnal TURN server, is it an important thing or should I just forget it instead of spending a few hours to get it up and running well ?</p> <p>Thanks for any answers !</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Daitan_"> /u/Daitan_ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy7hdf/i_just_successfully_set_up_my_matrix_server_does/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy7hdf/i_just_successfully_set_up_my_matrix_server_does/">[comments]</a></span>

## Looking for Self-Hosted Task Management and Bug Reporting System with SSO Support
 - [https://www.reddit.com/r/selfhosted/comments/1fy7gma/looking_for_selfhosted_task_management_and_bug](https://www.reddit.com/r/selfhosted/comments/1fy7gma/looking_for_selfhosted_task_management_and_bug)
 - RSS feed: $source
 - date published: 2024-10-07T13:21:09+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I&#39;m looking for suggestions for a self-hosted system that can handle several tasks for my homelab. I know this topic has been asked about a lot before, but I’m feeling a bit overwhelmed by all the options out there. I would really appreciate personal experiences from other Reddit users.</p> <p>Ideally, I need a solution that includes:</p> <ol> <li><strong>Task Management</strong>: A way to create and manage to-do lists for my various projects. This would be primarily for anything related to my homelab. It would be nice if I could have a different &#39;workspace&#39; or something like that for personal life projects (not related to my homelab at all).</li> <li><strong>Bug Reporting/Ticketing System</strong>: A feature that allows my users to submit bug reports, suggestions, or feature requests related to my services.</li> <li><strong>Web UI</strong>: The entire system should run in a web interface. I want my users to access ever

## Service Unavailable
 - [https://www.reddit.com/r/selfhosted/comments/1fy7863/service_unavailable](https://www.reddit.com/r/selfhosted/comments/1fy7863/service_unavailable)
 - RSS feed: $source
 - date published: 2024-10-07T13:09:53+00:00

<!-- SC_OFF --><div class="md"><p>I have an addy instance running on my home server. I used docker compose for this. I also use purelymail as a relay. I was able to register, received a confirmation email and activated my account. I created an alias and if I send emails to it, they are not forwarded.</p> <p>This is an email with confirmation code when registering on Atlassian:</p> <pre><code>NOQUEUE: reject: RCPT from mta-174-81-103.atlassian.com.sparkpostmail.com[192.174.81.103]: 554 5.7.1 Service unavailable; Client host [192.174.81.103] blocked using dul.dnsbl.sorbs.net; from=&lt;noreply+f821d2edfec1f55ca4925830b8464deb4aa653f7d3dc84aa6f9f11af@id.atlassian.com&gt; to=&lt;my_alias@example.com&gt; proto=ESMTP helo=&lt;mta-174-81-103.atlassian.com.sparkpostmail.com&gt; </code></pre> <p>And this one is sent from my personal email to the alias:</p> <pre><code>NOQUEUE: reject: RCPT from qs51p00im-qukt01071501.me.com[17.57.155.4]: 554 5.7.1 Service unavailable; Client host [17.57.155.4] b

## TP-Link Switch - Web Portal intermittent web request failures
 - [https://www.reddit.com/r/selfhosted/comments/1fy6x2a/tplink_switch_web_portal_intermittent_web_request](https://www.reddit.com/r/selfhosted/comments/1fy6x2a/tplink_switch_web_portal_intermittent_web_request)
 - RSS feed: $source
 - date published: 2024-10-07T12:55:10+00:00

<!-- SC_OFF --><div class="md"><p>Hello there.</p> <p>I own a 10-Port Gigabit Easy Smart Switch with 8-Port PoE+ (TL-SG1210MPE). I plugged it in directly into my router. When I access the web interface via HTTP, random pages and page sections just fail to load. Sometimes, it&#39;s the first page after login, and sometimes, it&#39;s the fourth or fifth page. It&#39;s never the same page. It&#39;s the same across multiple browsers. It has been doing that since I set up my whole network, and I don&#39;t get it. Sometimes, it&#39;s happening more often than some other time. I&#39;ve never seen this happening before.</p> <p>Here&#39;s 2 screenshots: <a href="https://ibb.co/TqvkPST">https://ibb.co/TqvkPST</a> and <a href="https://ibb.co/t8yCL1L">https://ibb.co/t8yCL1L</a></p> <p>Has this ever happened to anyone before?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fit_Increase2967"> /u/Fit_Increase2967 </a> <br/> <span><a href="https://www.reddit.com

## Minimal Debian install
 - [https://www.reddit.com/r/selfhosted/comments/1fy6gvi/minimal_debian_install](https://www.reddit.com/r/selfhosted/comments/1fy6gvi/minimal_debian_install)
 - RSS feed: $source
 - date published: 2024-10-07T12:32:10+00:00

<!-- SC_OFF --><div class="md"><p>I installed Debian last night and I found it so filled with crap (games and such). I am running on an old NUC wannabe. Is there a good guide for installing with only what I actually need to run services?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/itsmebrian"> /u/itsmebrian </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy6gvi/minimal_debian_install/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy6gvi/minimal_debian_install/">[comments]</a></span>

## How to configure DNS and port forwarding for accessing services via a VPN
 - [https://www.reddit.com/r/selfhosted/comments/1fy6g10/how_to_configure_dns_and_port_forwarding_for](https://www.reddit.com/r/selfhosted/comments/1fy6g10/how_to_configure_dns_and_port_forwarding_for)
 - RSS feed: $source
 - date published: 2024-10-07T12:30:57+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m running Yunohost on a Rasbperry Pi at home. I currently have this open to the internet in a pretty standard way:</p> <ul> <li>I have a domain name (bought on Namecheap) pointing at my home IP address</li> <li>I have dynamic DNS set up to update my DNS records if/when my IP changes</li> <li>I&#39;m forwarding ports 80, 443, and 1000 (what I set SSH to) from router to my Raspberry Pi</li> </ul> <p>This was fine to get started, but now I&#39;m worrying about security and would like to introduce a VPN into the mix. I have some questions on where to start:</p> <ul> <li><p>how does DNS work with a VPN? Basically, how do I make it so that once I have a client connected to my VPN, requests to <code>example.com/service</code> or <code>service.example.com</code> still work as expected? Would this be done with local DNS? If so, my guess is that I&#39;ll keep whatever port that&#39;s needed by the VPN open, then disable the other forwarded ports. Then, if

## Moving out, want to have a home server, new to this
 - [https://www.reddit.com/r/selfhosted/comments/1fy6bru/moving_out_want_to_have_a_home_server_new_to_this](https://www.reddit.com/r/selfhosted/comments/1fy6bru/moving_out_want_to_have_a_home_server_new_to_this)
 - RSS feed: $source
 - date published: 2024-10-07T12:24:47+00:00

<!-- SC_OFF --><div class="md"><p>So, I hope this is the right place for this kind of questions, as I&#39;m new here.<br/> I will try to provide all neede info, tall me if I&#39;m missing something<br/> I&#39;m a programmer/software engineer, I have backround in this kind of things but not alot.<br/> As i&#39;m moving out, I want to have a home server that will:<br/> serve media:<br/> * my own cloud storage, kinda like google photos, and access them via web<br/> * movies and tv, stream to tv app and web/app to pc. downloaded, and easly intergrated with some torrent client/backend. maybe serve the torrent ui over home network? (as it wont have a screen)<br/> serve my code project: mostly simple http, but exposed to the www and secured (can I limit incoming requests to spesific MAC address at the os/firewall level?<br/> Also, would like hardware recomendations </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Far-Competition8200"> /u/Far-Competition

## Accessing multiple self hosted apps in local network with specific URLs?
 - [https://www.reddit.com/r/selfhosted/comments/1fy5jvv/accessing_multiple_self_hosted_apps_in_local](https://www.reddit.com/r/selfhosted/comments/1fy5jvv/accessing_multiple_self_hosted_apps_in_local)
 - RSS feed: $source
 - date published: 2024-10-07T11:42:10+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve got a bunch of selfhosted apps running on a server. I&#39;m using Docker Compose to handle what&#39;s running on which port, and Traefik to open some of these apps to the Internet through a reverse proxy and a public URL.</p> <p>However, I&#39;ve got a bunch of apps I only want to access when I&#39;m on my WiFi or locally (Owntone, smart house apps, etc...) and while I can access them just fine with &quot;http://[local_server_ip]:[app_port]&quot;, I&#39;d like to be able to write something like &quot;owntone.local&quot; in my browser instead.</p> <p>I&#39;ve got PiHole running that I can use as a local DNS to do the redirecting to my server, but I can&#39;t seem to manage the reverse proxy-ing and only get 404 errors.</p> <p>Would anyone know of a solution? Proper configuration, or maybe an entirely different way of doing that?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FreikonVonAthanor"> /u/Freiko

## SimpleLogin one-script deployment in Docker
 - [https://www.reddit.com/r/selfhosted/comments/1fy5a04/simplelogin_onescript_deployment_in_docker](https://www.reddit.com/r/selfhosted/comments/1fy5a04/simplelogin_onescript_deployment_in_docker)
 - RSS feed: $source
 - date published: 2024-10-07T11:25:32+00:00

<!-- SC_OFF --><div class="md"><p>I found this to be a bit of a pain to get running so I put together a build.sh script that brings the whole stack up. You just need to add an SSL proxy to it (I didn&#39;t add this because everyone has their own implementation). </p> <p>The only thing I&#39;ve noticed not working (so far) is that quarantined emails aren&#39;t saved (the links give a 404) but it&#39;s probably something in the config. </p> <p>Anyway, this was useful to me and I would have been happy to find it a couple of weeks ago, so here&#39;s to the community: </p> <p><a href="https://github.com/jdlawrie/simplelogin-docker">https://github.com/jdlawrie/simplelogin-docker</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/doolittledoolate"> /u/doolittledoolate </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy5a04/simplelogin_onescript_deployment_in_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r

## Running multiple apps on a single server with Kamal 2
 - [https://www.reddit.com/r/selfhosted/comments/1fy4w6y/running_multiple_apps_on_a_single_server_with](https://www.reddit.com/r/selfhosted/comments/1fy4w6y/running_multiple_apps_on_a_single_server_with)
 - RSS feed: $source
 - date published: 2024-10-07T11:01:45+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fy4w6y/running_multiple_apps_on_a_single_server_with/"> <img src="https://external-preview.redd.it/cDQNRHXWExfxalbwpa7cQBFOuIOwywuKxDC--8Nt3fA.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=e7bb780c34d18242342ea109461202665bf718cd" alt="Running multiple apps on a single server with Kamal 2" title="Running multiple apps on a single server with Kamal 2" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/strzibny"> /u/strzibny </a> <br/> <span><a href="https://nts.strzibny.name/multiple-apps-single-server-kamal-2/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy4w6y/running_multiple_apps_on_a_single_server_with/">[comments]</a></span> </td></tr></table>

## Komodo 🦎 - Open source container / stack management - v1.15 Release - Log in with your OIDC provider - Compose file editor improved
 - [https://www.reddit.com/r/selfhosted/comments/1fy4s4v/komodo_open_source_container_stack_management](https://www.reddit.com/r/selfhosted/comments/1fy4s4v/komodo_open_source_container_stack_management)
 - RSS feed: $source
 - date published: 2024-10-07T10:54:51+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys,</p> <p>It&#39;s been awesome to hear your suggestions for Komodo. So far we have completed:</p> <ul> <li>Renamed the project from Monitor to Komodo</li> <li>Use self hosted git providers / docker registries like Gitea -- v1.12 ✅</li> <li>Deploy docker compose via the Stack resource -- v1.13 ✅</li> <li>Manage docker networks / images / volumes -- v1.14 ✅ </li> <li><strong>Log in with self hosted OIDC providers -- v1.15 ✅</strong> -- <a href="https://github.com/mbecker20/komodo/releases/tag/v1.15.0">Release Notes</a></li> </ul> <p>There&#39;s a lot of other improvements in this release as well. For example, the compose file editor has been improved for a VSCode like experience using <a href="https://microsoft.github.io/monaco-editor/">monaco-editor</a>. You can also edit and deploy compose files already on your server. And Environments Variables you configure on Komodo will keep all the commented out parts you put in them.</p> <p>Check out the

## SSO and reverse proxy with 100% Synology apps
 - [https://www.reddit.com/r/selfhosted/comments/1fy4o9c/sso_and_reverse_proxy_with_100_synology_apps](https://www.reddit.com/r/selfhosted/comments/1fy4o9c/sso_and_reverse_proxy_with_100_synology_apps)
 - RSS feed: $source
 - date published: 2024-10-07T10:47:35+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I&#39;m trying to simplify my home server to let other &quot;less-tech&quot; users start to manage it too. Until now I was doing reverse proxy with Swag, services in Docker, and LDAP authentication (I&#39;ve tried Authelia, but just for a short time. No particular problem with it).</p> <p>Now I see a way to simplify this, and I&#39;m looking for tutorials and advices to start.</p> <p>Synology DSM (I&#39;m under 7.2) has a native reverse proxy (Login Portal) and can do SSO (local or with C2 Identity) and then serve access through SAML of OIDC to docker services. I can even convert my Synology LDAP server to C2 Identity Edge server, so I can localy duplicate my directory in case of internet shutdown.</p> <p>So can I simply use those Synology apps to manage the authentication ?<br/> Can every entry of the Login Portal be &quot;behind&quot; the SSO portal ?</p> <p>Thanks for your help.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="

## Public video archive solutions
 - [https://www.reddit.com/r/selfhosted/comments/1fy4h0b/public_video_archive_solutions](https://www.reddit.com/r/selfhosted/comments/1fy4h0b/public_video_archive_solutions)
 - RSS feed: $source
 - date published: 2024-10-07T10:33:37+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,<br/> do you have any recommendations for selfhosted video archives? We have a number of videos from live concert recordings that we would like to make available through our website. Instead of embedding YouTube or PeerTube videos, we would like to offer streaming the videos on our website from our video archive.<br/> So, ideally, there&#39;d be some sort of CMS where we are able to upload videos and add some metadata, and then be able to stream those videos on the frontend.<br/> Happy about any hints!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kallnasty"> /u/kallnasty </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy4h0b/public_video_archive_solutions/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy4h0b/public_video_archive_solutions/">[comments]</a></span>

## Ghostfolio database installed with database 16, but system upgraded to 17
 - [https://www.reddit.com/r/selfhosted/comments/1fy44d9/ghostfolio_database_installed_with_database_16](https://www.reddit.com/r/selfhosted/comments/1fy44d9/ghostfolio_database_installed_with_database_16)
 - RSS feed: $source
 - date published: 2024-10-07T10:08:32+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fy44d9/ghostfolio_database_installed_with_database_16/"> <img src="https://b.thumbs.redditmedia.com/8Uhgq8pbBud1qNZB4hYRJaESNJZktojjFF8O5THBbEs.jpg" alt="Ghostfolio database installed with database 16, but system upgraded to 17" title="Ghostfolio database installed with database 16, but system upgraded to 17" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Dear all, </p> <p>I have Ghostfolio installed on my Synology NAS, and have been happy with it. I have had Watchtower installed, and it has upgraded it lately, and now i doesnt work. I tried to reroll back to a former version from my HyperBackup, but didnt do the trick. </p> <p>It says it was installed with PostSQL 16, and now the database it running 17, and therefor doesnt work. Any suggestions on how to get it to work. Would be sad to loose my history from Ghostfolio :/</p> <p><a href="https://preview.redd.it/nuyfgkde6btd1.png?width=2160&amp;format=png&amp;

## Proxmox server layout
 - [https://www.reddit.com/r/selfhosted/comments/1fy3ht5/proxmox_server_layout](https://www.reddit.com/r/selfhosted/comments/1fy3ht5/proxmox_server_layout)
 - RSS feed: $source
 - date published: 2024-10-07T09:21:58+00:00

<!-- SC_OFF --><div class="md"><p>Hi, as my serwer was working flawlessly I decided to redo it completely. Because why not... </p> <p>So, I used to have unraid with container, wireguard and 2 wms. </p> <p>I decided to add proxmox on top of that: </p> <ol> <li>VM with home asisstant.</li> <li>VM with Windows 11.</li> <li>VM with debian for all containers.</li> <li>VM with Unraid as NAS. </li> </ol> <p>Some of the containers would need access to unraid storage, but I should be able to figure it out.</p> <p>Question I have: Wireguard docker - not sure if I should have separate vm for it or run it together with other containers? Client only to connect to server hosted on VPS (access to containers and home assistant vm only). What&#39;s the best approach?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mrhinix"> /u/mrhinix </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy3ht5/proxmox_server_layout/">[link]</a></span> &#32; <sp

## Zabbix with an easy gui ios
 - [https://www.reddit.com/r/selfhosted/comments/1fy3hbx/zabbix_with_an_easy_gui_ios](https://www.reddit.com/r/selfhosted/comments/1fy3hbx/zabbix_with_an_easy_gui_ios)
 - RSS feed: $source
 - date published: 2024-10-07T09:20:56+00:00

<!-- SC_OFF --><div class="md"><p>So im running zabbix wirh grafana, is there any good app to monitor some stuff through zabbix? Doesn’t have to be grafana. But something simple that work with ios? Grafana in the web browser isn’t perfect.</p> <p>I know zabbix apps exist but i want something simple that mostly shows graphs.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Oblec"> /u/Oblec </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy3hbx/zabbix_with_an_easy_gui_ios/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy3hbx/zabbix_with_an_easy_gui_ios/">[comments]</a></span>

## Media and streaming service (Apple tv 4k DIY version)
 - [https://www.reddit.com/r/selfhosted/comments/1fy2sn8/media_and_streaming_service_apple_tv_4k_diy](https://www.reddit.com/r/selfhosted/comments/1fy2sn8/media_and_streaming_service_apple_tv_4k_diy)
 - RSS feed: $source
 - date published: 2024-10-07T08:27:44+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, LG OLED 2018 owner here. I really enjoy webOS but the last update really slowed down things so I was thinking about getting a self-hosted system which could connect both to my media and to streaming services. Would be awesome if I could use the LG remote.</p> <p>I already have a 24/7 on nuc connected to my tv via HDMI. I there a software solution that can achieve this? I knew PLEX but I don&#39;t like the centralized login and it cannot directly play streaming content.</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/robinoob"> /u/robinoob </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy2sn8/media_and_streaming_service_apple_tv_4k_diy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy2sn8/media_and_streaming_service_apple_tv_4k_diy/">[comments]</a></span>

## Issues setting up Pterodactyl Wings
 - [https://www.reddit.com/r/selfhosted/comments/1fy1lfv/issues_setting_up_pterodactyl_wings](https://www.reddit.com/r/selfhosted/comments/1fy1lfv/issues_setting_up_pterodactyl_wings)
 - RSS feed: $source
 - date published: 2024-10-07T06:55:36+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>A week ago, I was asking around here what was recommended for me to host a minecraft server managing self-hosting service. The main issue here was that the Minecraft server was going to be on a different device from my self-hosted server, one with more power to support enough players (an old laptop).</p> <p>But when I finished setting up the Prerodactyl Panel, I started looking at the Wings documentation only to find that it was NOT supported on Windows. But I remembered I could use WSL2 and get it to work (I&#39;m not sure about that, should be possible); networking at windows has always been the main problem so I tried to avoid any issues and use the host network for the wings container.</p> <p>Here&#39;s the log from the Wings container (sorry, the format got screw up along the way):</p> <pre><code>INFO: [Oct 7 00:30:37.435] writing log files to disk path=/var/log/pterodactyl/wings.log ____ __ Pterodactyl ____//_______ _______ ______ \_\

## is it fair to compare Syncthing to Immich even though Syncthing is only for Syncing?
 - [https://www.reddit.com/r/selfhosted/comments/1fy16s6/is_it_fair_to_compare_syncthing_to_immich_even](https://www.reddit.com/r/selfhosted/comments/1fy16s6/is_it_fair_to_compare_syncthing_to_immich_even)
 - RSS feed: $source
 - date published: 2024-10-07T06:25:17+00:00

<!-- SC_OFF --><div class="md"><p>or can they work symbiotically in some odd way?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cdoublejj"> /u/cdoublejj </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy16s6/is_it_fair_to_compare_syncthing_to_immich_even/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy16s6/is_it_fair_to_compare_syncthing_to_immich_even/">[comments]</a></span>

## Pydio Cells Community Thoughts
 - [https://www.reddit.com/r/selfhosted/comments/1fy0yga/pydio_cells_community_thoughts](https://www.reddit.com/r/selfhosted/comments/1fy0yga/pydio_cells_community_thoughts)
 - RSS feed: $source
 - date published: 2024-10-07T06:08:19+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1fy0yga/pydio_cells_community_thoughts/"> <img src="https://b.thumbs.redditmedia.com/1qh-t_M3wPsGRjFE6ukjx_xvEnuEYabzRifvTwLIgBA.jpg" alt="Pydio Cells Community Thoughts" title="Pydio Cells Community Thoughts" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I am testing Nextcloud alternatives and I have setup Pydio Cells. So far this seems like the perfect Nextcloud replacement. I have not run into something that does not meet my needs yet EXCEPT when I upload a file it seems to be obfuscating the files, I really like how Nextcloud did not do anything to my files, this really saved my bacon when Nextcloud would be totally screwed up I could still access the files and open them easily with their standard name. Does anyone know if there is a way to get Pydio to at the least keep the file names the same. I am hoping all it does is change the name and remove the extension of any uploaded files and of course make th

## Drop: an upcoming open-source Steam alternative (and a poll)
 - [https://www.reddit.com/r/selfhosted/comments/1fy0lts/drop_an_upcoming_opensource_steam_alternative_and](https://www.reddit.com/r/selfhosted/comments/1fy0lts/drop_an_upcoming_opensource_steam_alternative_and)
 - RSS feed: $source
 - date published: 2024-10-07T05:43:35+00:00

<!-- SC_OFF --><div class="md"><p>Hey there self hosters!</p> <p>I&#39;m working on something called Drop. It&#39;s supposed to be an open source Steam alternative/DRM-free game distribution platform, and a &#39;competitor&#39; to <a href="https://gamevau.lt/">GameVault</a>. Currently, while it&#39;s in early stages, I&#39;m working on it over on my personal <a href="https://lab.deepcore.dev/drop-oss">GitLab</a>, but once it&#39;s in a releasable state, I&#39;ll move it over to GitHub and set it up for contributions.</p> <p>For those interested, Drop has quite a number of features being worked on:</p> <ul> <li>Desktop apps for both Linux &amp; Windows (and maybe Mac, if I can get one to test with)</li> <li>First-class support for Linux/Proton</li> <li>Online multiplayer APIs &amp; social features (maybe even a re-implementation of the Steamworks API)</li> <li>Beautiful and modern web interface for both users &amp; admins</li> </ul> <p>And now for the poll. I&#39;m deciding how games s

## Chat solution to implement in the app
 - [https://www.reddit.com/r/selfhosted/comments/1fy08cs/chat_solution_to_implement_in_the_app](https://www.reddit.com/r/selfhosted/comments/1fy08cs/chat_solution_to_implement_in_the_app)
 - RSS feed: $source
 - date published: 2024-10-07T05:17:13+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a chat solution (1:1, group) to implement in an application. Do you know of any ready-made options that I can purchase with the source code?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Visual_Effort5561"> /u/Visual_Effort5561 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy08cs/chat_solution_to_implement_in_the_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy08cs/chat_solution_to_implement_in_the_app/">[comments]</a></span>

## Better host than plex
 - [https://www.reddit.com/r/selfhosted/comments/1fy05h5/better_host_than_plex](https://www.reddit.com/r/selfhosted/comments/1fy05h5/better_host_than_plex)
 - RSS feed: $source
 - date published: 2024-10-07T05:11:47+00:00

<!-- SC_OFF --><div class="md"><p>I’m looking for a better host for my media, I enjoy plex but I find it very irritating that I have to follow their particular naming conventions for media, I don’t have the time or rename thousands of files, does anyone know of a host that doesn’t restrict based on naming conventions and lets me choose my own library image as well?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Big-Consideration337"> /u/Big-Consideration337 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy05h5/better_host_than_plex/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fy05h5/better_host_than_plex/">[comments]</a></span>

## Backup suggestions
 - [https://www.reddit.com/r/selfhosted/comments/1fxzl1p/backup_suggestions](https://www.reddit.com/r/selfhosted/comments/1fxzl1p/backup_suggestions)
 - RSS feed: $source
 - date published: 2024-10-07T04:34:36+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for ideas to setup backups for my home setup. Currently it consists of:</p> <ul> <li>2 proxmox hosts with several VM and containers</li> <li>About 4 windows desktops</li> <li>1 computer about to be built with linux</li> <li>2 QNAP NAS, where I have plans to make 1 an offsite storage semi nearby</li> </ul> <p>I can see the sense of using PBS for all the Proxmox hosts, but after ways to get the rest done. My current thinking is the final storage location will be the NAS, duplicate local and offsite. </p> <p>Can people confirm if I have missed anything, and suggestions welcome for how to backup the Proxmox hosts themselves and the other physical machines. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mr_Evil_Sir"> /u/Mr_Evil_Sir </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fxzl1p/backup_suggestions/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhos

## Issue with Ansible making a Proxmox LXC - IPv6?!
 - [https://www.reddit.com/r/selfhosted/comments/1fxyynq/issue_with_ansible_making_a_proxmox_lxc_ipv6](https://www.reddit.com/r/selfhosted/comments/1fxyynq/issue_with_ansible_making_a_proxmox_lxc_ipv6)
 - RSS feed: $source
 - date published: 2024-10-07T03:56:03+00:00

<!-- SC_OFF --><div class="md"><p>See Playbook below. The issue seems to be with &quot;netif.&quot; I have used various variations of netif. I&#39;ll post a few below. They all generate the same error: </p> <blockquote> <p>An exception occurred during task execution. To see the full traceback, use -vvv. The error was: ValueError: Invalid IPv6 URL</p> <p>fatal: [localhost]: FAILED! =&gt; {&quot;changed&quot;: false, &quot;msg&quot;: &quot;Invalid IPv6 URL&quot;}</p> </blockquote> <pre><code>--- - name: Create and manage LXC containers on Proxmox hosts: localhost gather_facts: false become: false vars_prompt: - name: lxc_name prompt: &quot;Please enter the desired name for the LXC container&quot; private: no # Visible input for container name - name: proxmox_lxc_root_password prompt: &quot;Please enter the root password for the LXC container&quot; private: yes # Hidden input for password - name: proxmox_lxc_root_password_confirm prompt: &quot;Please confirm the root password for the LXC

## Seeking reommendation on options for Postgres and MongoDB
 - [https://www.reddit.com/r/selfhosted/comments/1fxxwya/seeking_reommendation_on_options_for_postgres_and](https://www.reddit.com/r/selfhosted/comments/1fxxwya/seeking_reommendation_on_options_for_postgres_and)
 - RSS feed: $source
 - date published: 2024-10-07T02:56:33+00:00

<!-- SC_OFF --><div class="md"><p>Hello Self Hosters,</p> <p>I am seeking for recommendation on how best to host a Postgres and MongoDB. I am looking to ingest some csv, json type financial data. </p> <p>I have used Postgres and Mysql as dependent containers while hosting nextcloud etc. but this time I am looking to host these two databases for multiple projects and data from different type of sources. </p> <p>A thought crossed my mind to leverage one of those online cloud offerings, but I am looking to see if self hosting is a better option. I have a proxmox setup with daily backups configured.</p> <p>Looking for your suggestions and experiences on what approach might be better. Do it as docker or LXC or VM or just go with Cloud service. </p> <p>Thank you! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Gujjubhai2019"> /u/Gujjubhai2019 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fxxwya/seeking_reommendation_on_option

## Best, private DDNS?
 - [https://www.reddit.com/r/selfhosted/comments/1fxw9vh/best_private_ddns](https://www.reddit.com/r/selfhosted/comments/1fxw9vh/best_private_ddns)
 - RSS feed: $source
 - date published: 2024-10-07T01:29:18+00:00

<!-- SC_OFF --><div class="md"><p>My IP changes frequently and am looking to see if there&#39;s a privacy respecting DDNS option? I don&#39;t mind using my IP to VPN in but just need to know what it is when I&#39;m not home and need to VPN in.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Useful-Resident78"> /u/Useful-Resident78 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fxw9vh/best_private_ddns/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fxw9vh/best_private_ddns/">[comments]</a></span>

## Bolt.new: AI-Powered Full-Stack Web Development in the Browser
 - [https://www.reddit.com/r/selfhosted/comments/1fxvnra/boltnew_aipowered_fullstack_web_development_in](https://www.reddit.com/r/selfhosted/comments/1fxvnra/boltnew_aipowered_fullstack_web_development_in)
 - RSS feed: $source
 - date published: 2024-10-07T00:57:01+00:00

<!-- SC_OFF --><div class="md"><p>🚀 Just launched a Selfhosted (Dockerized Version) of Bolt AI: [<a href="https://hub.docker.com/r/mickysharam/bolt-ai">https://hub.docker.com/r/mickysharam/bolt-ai</a>)<br/> <a href="http://bolt.new/">Bolt.new</a> is an AI-powered, full-stack web development agent that lets you code, run, edit, and deploy apps—all directly from your browser without local setup!<br/> With cutting-edge AI and seamless integration of StackBlitz’s WebContainers, it offers a unique development experience.<br/> Here&#39;s what makes it stand out:-<br/> 🛠️ Full-Stack in the Browser: Run npm tools, Node.js servers, interact with APIs, and deploy—all from chat.-<br/> ⚙️ AI + Environment Control: The AI doesn’t just suggest code; it manages your entire development environment!Whether you&#39;re a developer or just curious, this open-source project is for you.<br/> Want to build your own AI-powered dev tools?[<a href="https://github.com/stackblitz/bolt.new%5C">https://github.com/

## Easiest way to access my Jellyfin server remotely without a static IP?
 - [https://www.reddit.com/r/selfhosted/comments/1fxvm69/easiest_way_to_access_my_jellyfin_server_remotely](https://www.reddit.com/r/selfhosted/comments/1fxvm69/easiest_way_to_access_my_jellyfin_server_remotely)
 - RSS feed: $source
 - date published: 2024-10-07T00:54:39+00:00

<!-- SC_OFF --><div class="md"><p>As the title suggests - networking has never been my strongest point but I&#39;m trying to figure it out slowly!</p> <p>I&#39;m looking for the easiest way to access my Jellyfin and Immich remotely but I don&#39;t have a static IP. So far I&#39;ve been managing by just using the direct IP/forwarded port but from what I&#39;ve been reading setting up either a cloudflare tunnel or tailscale would be the easiest way - what&#39;s the best &quot;idiot proof&quot; guide I can use, or any better alternatives? I already have a couple of domain names I can use.</p> <p>Thanks in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/argentsquest"> /u/argentsquest </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fxvm69/easiest_way_to_access_my_jellyfin_server_remotely/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fxvm69/easiest_way_to_access_my_jellyfin_serve

## Will emails downloaded via mbsync be transferable to a new server?
 - [https://www.reddit.com/r/selfhosted/comments/1fxvg6w/will_emails_downloaded_via_mbsync_be_transferable](https://www.reddit.com/r/selfhosted/comments/1fxvg6w/will_emails_downloaded_via_mbsync_be_transferable)
 - RSS feed: $source
 - date published: 2024-10-07T00:45:56+00:00

<!-- SC_OFF --><div class="md"><p>Hi! I&#39;m currently using Fastmail, and while I wouldn&#39;t say it&#39;s a bad service, it’s a bit too expensive for my budget. I’m looking for an affordable provider that supports IMAP. I don&#39;t care about encryption. I just want a simple service where I can use my own domain name. I noticed that PurelyMail is affordable.</p> <p>I use &quot;mbsync&quot; on Linux to download all my emails from the server. Given this, does anyone know if I can upload all my old emails to a new email provider in the future using mbsync? I use Emacs with Mu4e for reading my emails, something similar to mutt.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/zoliky"> /u/zoliky </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1fxvg6w/will_emails_downloaded_via_mbsync_be_transferable/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1fxvg6w/will_emails_downloaded_via_mbsync_

## Clipboard Feature Not Working in Self-Hosted Kasm (LXC on Proxmox)
 - [https://www.reddit.com/r/selfhosted/comments/1fxv5fw/clipboard_feature_not_working_in_selfhosted_kasm](https://www.reddit.com/r/selfhosted/comments/1fxv5fw/clipboard_feature_not_working_in_selfhosted_kasm)
 - RSS feed: $source
 - date published: 2024-10-07T00:30:26+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I’ve been using Kasm for a while now, and I have to say it’s one of the best self-hosted applications I’ve come across. I recently set it up on an LXC container within Proxmox, and overall it’s been a great experience. However, I’m facing an issue with the clipboard feature—it’s not working as expected.</p> <p>I’m using Chrome and Brave as recommended in the <a href="https://www.kasmweb.com/docs/latest/user_guide/control_panel.html#clipboard">Kasm documentation</a>, but I still can’t get the clipboard functionality to work. I’m accessing Kasm on my MacBook and trying to copy-paste between my Mac and the Kasm environment, but it’s just not happening.</p> <p>Has anyone else experienced this issue? Any ideas on how to fix it or troubleshoot further?</p> <p>Appreciate any help or pointers!</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/youmeiknow"> /u/youmeiknow </a> <br/> <span><

## Clipboard Feature Not Working in Self-Hosted Kasm (LXC on Proxmox)
 - [https://www.reddit.com/r/selfhosted/comments/1fxv58a/clipboard_feature_not_working_in_selfhosted_kasm](https://www.reddit.com/r/selfhosted/comments/1fxv58a/clipboard_feature_not_working_in_selfhosted_kasm)
 - RSS feed: $source
 - date published: 2024-10-07T00:30:10+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I’ve been using Kasm for a while now, and I have to say it’s one of the best self-hosted applications I’ve come across. I recently set it up on an LXC container within Proxmox, and overall it’s been a great experience. However, I’m facing an issue with the clipboard feature—it’s not working as expected.</p> <p>I’m using Chrome and Brave as recommended in the <a href="https://www.kasmweb.com/docs/latest/user_guide/control_panel.html#clipboard">Kasm documentation</a>, but I still can’t get the clipboard functionality to work. I’m accessing Kasm on my MacBook and trying to copy-paste between my Mac and the Kasm environment, but it’s just not happening.</p> <p>Has anyone else experienced this issue? Any ideas on how to fix it or troubleshoot further?</p> <p>Appreciate any help or pointers!</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/youmeiknow"> /u/youmeiknow </a> <br/> <span><

