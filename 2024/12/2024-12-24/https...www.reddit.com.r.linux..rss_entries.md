# Source:Linux, GNU/Linux, free software..., URL:https://www.reddit.com/r/linux/.rss, language:en

## Rust Drama, Russian Kernel Maintainers & Other Top Linux Kernel Happenings Of 2024
 - [https://www.reddit.com/r/linux/comments/1hlo8h6/rust_drama_russian_kernel_maintainers_other_top](https://www.reddit.com/r/linux/comments/1hlo8h6/rust_drama_russian_kernel_maintainers_other_top)
 - RSS feed: $source
 - date published: 2024-12-24T22:39:42+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/gabriel_3"> /u/gabriel_3 </a> <br/> <span><a href="https://www.phoronix.com/news/Top-Linux-Kernel-News-2024">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux/comments/1hlo8h6/rust_drama_russian_kernel_maintainers_other_top/">[comments]</a></span>

## When your AMD GPU crash with entire OS/Desktop session - amdgpu: ring gfx timeout - its fine and it is expected behavior
 - [https://www.reddit.com/r/linux/comments/1hlmn5x/when_your_amd_gpu_crash_with_entire_osdesktop](https://www.reddit.com/r/linux/comments/1hlmn5x/when_your_amd_gpu_crash_with_entire_osdesktop)
 - RSS feed: $source
 - date published: 2024-12-24T21:12:23+00:00

<!-- SC_OFF --><div class="md"><p><strong>Situation:</strong></p> <p>Basically any game that use OpenGL crash amdgpu driver in 10-20 mins. (100%)</p> <p>Vulkan games - that crash amdgpu - is not driver bug - it is game bug.</p> <p><a href="https://gitlab.freedesktop.org/mesa/mesa/-/issues/12329">https://gitlab.freedesktop.org/mesa/mesa/-/issues/12329</a></p> <blockquote> <p>Vulkan behavior can easily hang the GPU, which is exactly what seems to happen from the dmesg you posted. You could argue that hang recovery should be more robust (and I&#39;d agree), but this is what the situation is like right now.</p> </blockquote> <p><strong>Basically</strong> - if you lost entire desktop session when you watch youtube and your PC/session reboot/reload because amdgpu ring timeout - this is fine - expected behavior.</p> <p>👍</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/S48GS"> /u/S48GS </a> <br/> <span><a href="https://www.reddit.com/r/linux/comments/1h

## OpenOffice: Multiple unfixed security holes, over a year old
 - [https://www.reddit.com/r/linux/comments/1hlles1/openoffice_multiple_unfixed_security_holes_over_a](https://www.reddit.com/r/linux/comments/1hlles1/openoffice_multiple_unfixed_security_holes_over_a)
 - RSS feed: $source
 - date published: 2024-12-24T20:06:31+00:00

<!-- SC_OFF --><div class="md"><p>Hi all. Apache OpenOffice still describes itself as the &quot;leading open source office suite&quot; but in the latest <a href="https://www.apache.org/foundation/records/minutes/2024/board_minutes_2024_11_20.txt">Apache Foundation Board Report</a> the Security Team says it has:</p> <blockquote> <p>openoffice (Health amber): Three issues in OpenOffice over 365 days old and a number of other open issues not fully triaged.</p> </blockquote> <p>There has been no point update for over a year, no new committers since 2022, and no major release since 2014. Now that the Apache Software Foundation is serving tens of thousands of users vulnerable software, maybe it&#39;s time for the FOSS community to contact them and ask them to finally put it in the Attic?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/themikeosguy"> /u/themikeosguy </a> <br/> <span><a href="https://www.reddit.com/r/linux/comments/1hlles1/openoffice_mu

## Tools I made at work that might help some sysadmin peeps/homelabbers
 - [https://www.reddit.com/r/linux/comments/1hlgczd/tools_i_made_at_work_that_might_help_some](https://www.reddit.com/r/linux/comments/1hlgczd/tools_i_made_at_work_that_might_help_some)
 - RSS feed: $source
 - date published: 2024-12-24T15:56:01+00:00

<!-- SC_OFF --><div class="md"><p>I won&#39;t lie to you all and say I&#39;m some kind of w1zard_h4x0r I&#39;m not, I work for a severely underfunded and understaffed government department, and I&#39;ve had to get creative with my time.<br/> These are some tools I made in my spare time to make managing my Tailscale network (which uses Ansible Pull for updates/versioning ) a little faster/easier to manage.</p> <p>I&#39;m not going to claim these are perfect at all, but I&#39;ve always been of the opinion that something should just work and that all the trimmings aren&#39;t really important.</p> <p>Hope this helps some people, and if you want to change anything, don&#39;t complain, just do, fork it, make your own, I don&#39;t care at all.</p> <p>First on the list is <strong>PingPanel</strong>, it&#39;s a TUI based Uptime Manager, our networks team uses PRTG to monitor all our kit, but I absolutely hate the process of adding devices to it, so this just let&#39;s you put an ansible inven

## Xubuntu 24.04 - a real bad experience - seems we are going backwards
 - [https://www.reddit.com/r/linux/comments/1hlgbeb/xubuntu_2404_a_real_bad_experience_seems_we_are](https://www.reddit.com/r/linux/comments/1hlgbeb/xubuntu_2404_a_real_bad_experience_seems_we_are)
 - RSS feed: $source
 - date published: 2024-12-24T15:53:55+00:00

<!-- SC_OFF --><div class="md"><p>For the past years I was using Linux (Xubuntu) as my primary and only OS on my laptop and personal computer. I loved it and it was much better than the Windows alternative. Due to some malfunction (which I will write in a different post because it was annoying too) I formatted my computer and decided to install the latest Xubuntu 24.04 (I had 22.04 before). And boy, should I tell you: I am so disappointed. Not only we didn&#39;t make a step forward, i<strong>t looks like we have made two steps backwards.</strong></p> <p>First of all, I am a Linux USER, not a Linux geek, hacker or low level professional Linux guy. I use Linux because it allows me to do my job. And to do it better and easier. I was always a Linux advocate and convinced the people around me to give it a try. The non hassle drivers support. The none sales gimmicks. The real easy way of installing software. Just do &quot;sudo apt-get install 7zip&quot; and boom, you have 7zip installed on

## crenametoix - a Linux bulk file renamer with a macro ecosystem, including index macros, regular expressions, Python expressions, and reverse geocoding.
 - [https://www.reddit.com/r/linux/comments/1hlfnwd/crenametoix_a_linux_bulk_file_renamer_with_a](https://www.reddit.com/r/linux/comments/1hlfnwd/crenametoix_a_linux_bulk_file_renamer_with_a)
 - RSS feed: $source
 - date published: 2024-12-24T15:21:11+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://i.redd.it/g3id8ug1dt8e1.gif">crenametoix</a></p> <p>crenametoix is the &quot;console-only version&quot; of RenameToIX, designed for those who prefer minimalism without sacrificing functionality. No Gtk dependencies, just a &quot;powerful macro ecosystem&quot; for streamlined file renaming in Linux.</p> <h1>Project Page:</h1> <ul> <li><a href="https://www.devtoix.com/en/projects/renametoix">https://www.devtoix.com/en/projects/renametoix</a></li> <li><a href="https://github.com/a-bentofreire/renametoix">https://github.com/a-bentofreire/renametoix</a></li> </ul> <h1>Key Features:</h1> <p>🔹 &quot;Macros for efficiency&quot;:</p> <ul> <li>Counter, file datetime, and extension macros.</li> <li>Regular expressions.</li> <li>Regex-based function macros like <code>lower</code>, <code>upper</code>, <code>capitalize</code>, and <code>title</code>.</li> </ul> <p>🔹 &quot;Advanced capabilities&quot;:</p> <ul> <li>Python lambda expressions for cust

## The Hardest Thing: Building and Running the UNIX Kernel from Original Sources
 - [https://www.reddit.com/r/linux/comments/1hleu44/the_hardest_thing_building_and_running_the_unix](https://www.reddit.com/r/linux/comments/1hleu44/the_hardest_thing_building_and_running_the_unix)
 - RSS feed: $source
 - date published: 2024-12-24T14:38:57+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/MatchingTurret"> /u/MatchingTurret </a> <br/> <span><a href="https://youtu.be/IBFeM-sa2YY?si=cHvlegpLysNyZslw">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux/comments/1hleu44/the_hardest_thing_building_and_running_the_unix/">[comments]</a></span>

## can somebody help me ?
 - [https://www.reddit.com/r/linux/comments/1hldu5i/can_somebody_help_me](https://www.reddit.com/r/linux/comments/1hldu5i/can_somebody_help_me)
 - RSS feed: $source
 - date published: 2024-12-24T13:45:16+00:00

<!-- SC_OFF --><div class="md"><p>since i switch to linux i got in love whit it, everything that i could discover back in that time i discovered. everything seemed to connects to other things and thats how i learned a bunch of things. but now, it looks like i cant find anything that i dont know, it seems so boring now and i honestly dont know what to do. i know that i dont discovered anything but i cant find something</p> <p>sorry for the text, i am still learning english </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/GaySelvagem"> /u/GaySelvagem </a> <br/> <span><a href="https://www.reddit.com/r/linux/comments/1hldu5i/can_somebody_help_me/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux/comments/1hldu5i/can_somebody_help_me/">[comments]</a></span>

## Quest 3 + VD in Win11 VM or Dual Boot?
 - [https://www.reddit.com/r/linux/comments/1hldqri/quest_3_vd_in_win11_vm_or_dual_boot](https://www.reddit.com/r/linux/comments/1hldqri/quest_3_vd_in_win11_vm_or_dual_boot)
 - RSS feed: $source
 - date published: 2024-12-24T13:40:00+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>As far as I know I need Windows for VR with my Quest 3 due to the need for the Windows Meta app. Maybe if I was willing to ditch Virtual Desktop I could use the Q3 with Steam VR without the Meta app? I don&#39;t know. VD is too great to not use it though so that&#39;s out of the question. So...</p> <p>Can Win11 be run in a VM with less than a five percent loss in performance? Or is a dual boot setup a no-brainer.</p> <p>I&#39;ve a pretty decent ASUS ROG Strix laptop with an 12th Gen i9 and an 8 GB 3070 Ti.</p> <p>Note that, as an alternative to switching to Linux for non-gaming I&#39;m also considering &quot;de-bloating,&quot; Win11 or using a pared down Install ISO of it. I actually really like its GUI but do NOT like its spyware &quot;features,&quot; and less secure, uh, security.</p> <p>Along with debloating all sorts of other things can be done to significantly reduce the number of background processes - including that pesky 

## duolicious is a open source website for dating and finding friends.
 - [https://www.reddit.com/r/linux/comments/1hlcr7u/duolicious_is_a_open_source_website_for_dating](https://www.reddit.com/r/linux/comments/1hlcr7u/duolicious_is_a_open_source_website_for_dating)
 - RSS feed: $source
 - date published: 2024-12-24T12:41:34+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/wiki_me"> /u/wiki_me </a> <br/> <span><a href="https://duolicious.app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux/comments/1hlcr7u/duolicious_is_a_open_source_website_for_dating/">[comments]</a></span>

## TidesDB - Open Source High-Performance Storage Engine (KV Store) v0.5.0 BETA Release
 - [https://www.reddit.com/r/linux/comments/1hlcn3n/tidesdb_open_source_highperformance_storage](https://www.reddit.com/r/linux/comments/1hlcn3n/tidesdb_open_source_highperformance_storage)
 - RSS feed: $source
 - date published: 2024-12-24T12:33:55+00:00

<!-- SC_OFF --><div class="md"><p>Hello, my fellow Linux users! I and others have been working on an open-source storage engine called TidesDB for a couple of months now, and we are at v0.5.0b, which is a fairly big milestone for me—halfway to TidesDB 1. TidesDB is an LSM(log structured merge) tree-based storage engine designed from the ground up to be simple, fast, and efficient.</p> <p><strong>Here are some features!</strong></p> <ul> <li> <strong>ACID</strong> transactions are atomic, consistent, isolated, and durable. Transactions are tied to their respective column family.</li> <li> <strong>Concurrent</strong> multiple threads can read and write to the storage engine. Column families use a read-write lock thus allowing multiple readers and a single writer per column family. Transactions on commit block other threads from reading or writing to the column family until the transaction is completed. A transaction is thread safe.</li> <li> <strong>Column Families</strong> store data 

## Poor windows
 - [https://www.reddit.com/r/linux/comments/1hl9wbz/poor_windows](https://www.reddit.com/r/linux/comments/1hl9wbz/poor_windows)
 - RSS feed: $source
 - date published: 2024-12-24T09:14:20+00:00

<!-- SC_OFF --><div class="md"><p>I’ve logged in to my windows machine after like a month and boy, I am happy that I moved to Linux for quite a while. Windows is just so slow, the updates screaming to be updated, the antivirus saying it’s gonna be expired in a few days bla bla bla. And my laptop fan going on at high speed because all I am running is windows 11 idle without anything else open. Windows 11 is so slow. But am proud Linux user ;)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Poltu_Ray"> /u/Poltu_Ray </a> <br/> <span><a href="https://www.reddit.com/r/linux/comments/1hl9wbz/poor_windows/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux/comments/1hl9wbz/poor_windows/">[comments]</a></span>

## Por qué no puedo usar iwconfig en debian 12 en terminal tengo instalado wireless-tools?
 - [https://www.reddit.com/r/linux/comments/1hl5jnc/por_qué_no_puedo_usar_iwconfig_en_debian_12_en](https://www.reddit.com/r/linux/comments/1hl5jnc/por_qué_no_puedo_usar_iwconfig_en_debian_12_en)
 - RSS feed: $source
 - date published: 2024-12-24T04:15:59+00:00

<!-- SC_OFF --><div class="md"><p>Necesito usar iwconfig y me dice comando no encontrado, ¿por qué? y tengo instalado wireless-tools en su versión más reciente. Gracias.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Elegant-Reveal9101"> /u/Elegant-Reveal9101 </a> <br/> <span><a href="https://www.reddit.com/r/linux/comments/1hl5jnc/por_qué_no_puedo_usar_iwconfig_en_debian_12_en/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux/comments/1hl5jnc/por_qué_no_puedo_usar_iwconfig_en_debian_12_en/">[comments]</a></span>

## How to install the OS??
 - [https://www.reddit.com/r/linux/comments/1hl33rj/how_to_install_the_os](https://www.reddit.com/r/linux/comments/1hl33rj/how_to_install_the_os)
 - RSS feed: $source
 - date published: 2024-12-24T01:55:01+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/ReadSea4545"> /u/ReadSea4545 </a> <br/> <span><a href="https://i.redd.it/dx2tebyedp8e1.gif">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux/comments/1hl33rj/how_to_install_the_os/">[comments]</a></span>

## This Linux-kernel-RCU bug fought well .....Stolen from Paul McKenney's share on another channel......insightful
 - [https://www.reddit.com/r/linux/comments/1hl2u2n/this_linuxkernelrcu_bug_fought_well_stolen_from](https://www.reddit.com/r/linux/comments/1hl2u2n/this_linuxkernelrcu_bug_fought_well_stolen_from)
 - RSS feed: $source
 - date published: 2024-12-24T01:40:05+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/unixbhaskar"> /u/unixbhaskar </a> <br/> <span><a href="https://people.kernel.org/8q9a9dt4q3">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux/comments/1hl2u2n/this_linuxkernelrcu_bug_fought_well_stolen_from/">[comments]</a></span>

