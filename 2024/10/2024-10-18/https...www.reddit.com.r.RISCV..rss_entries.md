# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Running CI/CD pipelines with RISC-V
 - [https://www.reddit.com/r/RISCV/comments/1g6hy5f/running_cicd_pipelines_with_riscv](https://www.reddit.com/r/RISCV/comments/1g6hy5f/running_cicd_pipelines_with_riscv)
 - RSS feed: $source
 - date published: 2024-10-18T13:22:47+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been building a site for hosting CI/CD runners powered by RISC-V architecture. I was in the need of it and noticed there wasn&#39;t one out there that was easy to setup.</p> <p>Here&#39;s the site:<br/> <a href="https://www.riscvrunners.com/">https://www.riscvrunners.com/</a></p> <p>For now it only supports Gitlab Runners, but I plan to add support for other platforms too!</p> <p>If you want to try it without paying, check out this Gitlab Project: <a href="https://gitlab.com/riscvrunners/runner-test">https://gitlab.com/riscvrunners/runner-test</a></p> <p>That project is open to the public, so you can push code and run CI pipelines to see if it works as you expect.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Plus_Technology_7569"> /u/Plus_Technology_7569 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1g6hy5f/running_cicd_pipelines_with_riscv/">[link]</a></span> &#32; <span><a href="

## SG2042 Newsletter (2024-10-18 #064)
 - [https://www.reddit.com/r/RISCV/comments/1g6cuwb/sg2042_newsletter_20241018_064](https://www.reddit.com/r/RISCV/comments/1g6cuwb/sg2042_newsletter_20241018_064)
 - RSS feed: $source
 - date published: 2024-10-18T07:57:33+00:00

<!-- SC_OFF --><div class="md"><h2>Editor&#39;s Note</h2> <p>Welcome to the sixty-fourth issue of the SG2042 Newsletter. In this issue, we bring you a series of news over Milk-V Duo. Hope you will enjoy this update.</p> <h2>Highlights</h2> <ul> <li><p>We sincerely appreciate biblioman09 for creating and sharing a wealth of tutorials related to Milk-V Duo on the YouTube platform. These valuable resources not only provide convenience for beginners and enthusiasts but also significantly contribute to the prosperity and development of the open-source community.</p> <p><a href="https://www.youtube.com/@biblioman09">Personal Homepage</a></p></li> </ul> <h2>Upstream</h2> <p>Most of the code is already open-source and can be obtained from repositories such as github.com/SOPHGO. The following are some useful repo resources:</p> <h3>Linux kernel</h3> <ul> <li><p>Sophgo Community work: <a href="https://github.com/sophgo/linux-riscv">https://github.com/sophgo/linux-riscv</a></p> <ul> <li>No commi

## RISC-V Allwinner D1H Baremetal with RT-Thread. LCD work, USB in progress.
 - [https://www.reddit.com/r/RISCV/comments/1g6cbb4/riscv_allwinner_d1h_baremetal_with_rtthread_lcd](https://www.reddit.com/r/RISCV/comments/1g6cbb4/riscv_allwinner_d1h_baremetal_with_rtthread_lcd)
 - RSS feed: $source
 - date published: 2024-10-18T07:14:04+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1g6cbb4/riscv_allwinner_d1h_baremetal_with_rtthread_lcd/"> <img src="https://b.thumbs.redditmedia.com/iZf5h5HNwCik-5CTRNtez_XtTc3X_3cEFPJ4Vwjc50k.jpg" alt="RISC-V Allwinner D1H Baremetal with RT-Thread. LCD work, USB in progress." title="RISC-V Allwinner D1H Baremetal with RT-Thread. LCD work, USB in progress." /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I successfully build and ran <a href="https://www.rt-thread.io/">RT-Thread</a> (a small embedded OS) on the Allwinner D1H.&lt;br&gt; Experimenting on <a href="https://www.clockworkpi.com/home-devterm">ClockworkPi DevTerm R-01</a> device and <a href="https://wiki.sipeed.com/hardware/en/lichee/RV/Dock.html">Sipeed Lichee RV</a> board. It may also work in uConsole R-01, but I didn&#39;t have uConsole. I would appreciate if someone could test it.</p> <p>The Allwinner D1H documentation is very limited regarding peripherals. However, if you enjoy braint

## Looks like Milk-V have many new products on the way
 - [https://www.reddit.com/r/RISCV/comments/1g69cyu/looks_like_milkv_have_many_new_products_on_the_way](https://www.reddit.com/r/RISCV/comments/1g69cyu/looks_like_milkv_have_many_new_products_on_the_way)
 - RSS feed: $source
 - date published: 2024-10-18T03:51:34+00:00

<!-- SC_OFF --><div class="md"><p>8 module cluster board: <a href="https://milkv.io/cluster-08">https://milkv.io/cluster-08</a></p> <p>So you could plug in 8 Megrez NX nodes/modules, for up to 159.6 TOPS@INT8 NPU. Or 8 Milk-V Jupiter NX nodes possibly for H264/H265 video encoding.</p> <p>It looks like the BMC (remote baseboard management console) is RISC-V along with the Interconnection (FSL1030M) 32Gbps bandwidth Layer 2 Ethernet switch chip. And the board appears to have support for SPF+ (Small Form Factor Pluggable Transceivers - 10GbE or higher at a guess) as well as Ethernet. Each Node Supports its own NVMe SSD Installation (probably on the bottom of the board)</p> <p>I would guess that it is probably compatible with the current Raspberry Pi compute modules as well. And I&#39;m guessing that they will also possibly target the Raspberry Pi 5 compute module once one is available. </p> <hr/> <p>Milk-V Jupiter NX module (Replace your Jetson NANO) <a href="https://milkv.io/jupiter-nx"

