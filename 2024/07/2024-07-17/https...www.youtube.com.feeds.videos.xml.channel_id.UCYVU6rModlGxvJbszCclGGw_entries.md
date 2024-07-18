# Source:Rob Braxman Tech, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCYVU6rModlGxvJbszCclGGw, language:en

## This One Step Could SAVE Your Private Data From Windows (Dual Boot Tutorial)
 - [https://www.youtube.com/watch?v=4VKoG0dKCOk](https://www.youtube.com/watch?v=4VKoG0dKCOk)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCYVU6rModlGxvJbszCclGGw
 - date published: 2024-07-17T16:00:05+00:00

The threats have changed and we have to change as well. Now the privacy risk is from AI enabled device scanning (Client Side Scanning). We know today that using Linux and Open Sourced Operating systems like De-Googled OS's will protect us from this. However, we cannot transition immediately. While there's time, we can migrate to the correct and safe platforms. In the meantime we need to prepare for this transition by being able to shift away from Windows, and MacOS.

The solution is Dual Boot. And wean our private activities away from Windows keylogging and screenshots and such madness.

On MacOS/Apple Silicon, you can dual boot with Asahi Linux.

EXTRA TIPS ON LINUX:
1.  The best way to handle NTFS in dual boot is to mount the NTFS drive to your Documents folder. This way it is easily accessible. For example, make  Windows folder in it. Then...

2. Auto mount the NTFS by making an entry in /etc/fstab as shown in this example below

UUID="partitionid" /home/"user"/Documents/Windows nt

