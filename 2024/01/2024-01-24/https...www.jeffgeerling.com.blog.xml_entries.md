# Source:Jeff Geerling's Blog, URL:https://www.jeffgeerling.com/blog.xml, language:en

## Mounting an ext4 linux USB drive on macOS in 2024
 - [https://www.jeffgeerling.com/blog/2024/mounting-ext4-linux-usb-drive-on-macos-2024](https://www.jeffgeerling.com/blog/2024/mounting-ext4-linux-usb-drive-on-macos-2024)
 - RSS feed: https://www.jeffgeerling.com/blog.xml
 - date published: 2024-01-24T16:28:22+00:00

<span class="field field--name-title field--type-string field--label-hidden">Mounting an ext4 linux USB drive on macOS in 2024</span>

            <div class="clearfix text-formatted field field--name-body field--type-text-with-summary field--label-hidden field__item"><p>I recently pulled a SATA hard drive out of a Linux box that I wanted to grab some files off of. I only had my Mac on hand, and I had a USB 3.0 to SATA hard drive adapter at the ready.</p>

<p>But when I plugged in the hard drive, macOS said it couldn't recognize the disk.</p>

<p><img alt="Disk unreadable by macOS" class="insert-image" height="auto" src="https://www.jeffgeerling.com/sites/default/files/images/disk-unreadable-mac.jpeg" width="500" /></p>

<p>Makes sense, because macOS includes support for Apple's filesystems, not Linux (or even NTFS, Windows' preferred filesystem). There are commercial solutions you can buy, like Paragon Software's <a href="https://www.paragon-drivers.com/en/extfsmac/">extFS f

