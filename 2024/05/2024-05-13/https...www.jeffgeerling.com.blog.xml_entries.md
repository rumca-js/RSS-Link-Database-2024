# Source:Jeff Geerling's Blog, URL:https://www.jeffgeerling.com/blog.xml, language:en

## Quick NVMe performance testing with fio
 - [https://www.jeffgeerling.com/blog/2024/quick-nvme-performance-testing-fio](https://www.jeffgeerling.com/blog/2024/quick-nvme-performance-testing-fio)
 - RSS feed: https://www.jeffgeerling.com/blog.xml
 - date published: 2024-05-13T20:55:45+00:00

<span class="field field--name-title field--type-string field--label-hidden">Quick NVMe performance testing with fio</span>

            <div class="clearfix text-formatted field field--name-body field--type-text-with-summary field--label-hidden field__item"><p>I've recently been debugging some NVMe / PCIe bus errors on a Raspberry Pi, and I wanted a quick way to test NVMe devices without needing to create a filesystem and use a tool like <code>iozone</code>. I don't care about benchmarks, I just want to quickly push the drive and read and write some data to it.</p>

<p><code>fio</code> is the tool for the job, and after a quick install <code>sudo apt install -y fio</code>, I create a configuration file named <code>nvme-read.fio</code>:</p>

<pre><code>[global]
name=nvme-seq-read
time_based
ramp_time=5
runtime=30
readwrite=read
bs=256k
ioengine=libaio
direct=1
numjobs=1
iodepth=32
group_reporting=1
[nvme0]
filename=/dev/nvme0n1
</code></pre>

<p>Then run it with:</p>

<pre><code>sudo 

## Import unsupported camera RAW files into Apple Photos
 - [https://www.jeffgeerling.com/blog/2024/import-unsupported-camera-raw-files-apple-photos](https://www.jeffgeerling.com/blog/2024/import-unsupported-camera-raw-files-apple-photos)
 - RSS feed: https://www.jeffgeerling.com/blog.xml
 - date published: 2024-05-13T02:59:58+00:00

<span class="field field--name-title field--type-string field--label-hidden">Import unsupported camera RAW files into Apple Photos</span>

            <div class="clearfix text-formatted field field--name-body field--type-text-with-summary field--label-hidden field__item"><p>Many years ago, I decided to <a href="https://www.jeffgeerling.com/blog/2017/i-made-switch-aperture-photos">migrate my photo library from Apple's now-defunct Aperture to Photos</a>, so I could take advantage of Apple's iCloud Photo Library (don't worry, I still have three full complete local backups, plus a separate cloud backup besides Apple's iCloud originals).</p>

<p>One pain point is RAW support. As camera manufacturers add new models, their proprietary RAW codecs are updated, and software vendors like Apple, Adobe, and Microsoft have to update photo editing tools to work with the new camera models.</p>

<p>I don't envy them this task, but as Photos was Apple's official successor to Aperture (a pale shadow to

