# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## RISC-V web server docker image ~ 5MB
 - [https://www.reddit.com/r/RISCV/comments/1ezm74r/riscv_web_server_docker_image_5mb](https://www.reddit.com/r/RISCV/comments/1ezm74r/riscv_web_server_docker_image_5mb)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-08-23T19:58:49+00:00

<!-- SC_OFF --><div class="md"><p>docker pull amp24/amp_riscv:latest<br /> ....&quot;This Docker image provides a simple and lightweight web server using a RISC-V architecture with BusyBox, a minimal Linux environment..&quot; </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/geev03"> /u/geev03 </a> <br /> <span><a href="https://www.reddit.com/r/RISCV/comments/1ezm74r/riscv_web_server_docker_image_5mb/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1ezm74r/riscv_web_server_docker_image_5mb/">[comments]</a></span>

## Pioneer 1 complete system for sale.
 - [https://www.reddit.com/r/RISCV/comments/1eziba8/pioneer_1_complete_system_for_sale](https://www.reddit.com/r/RISCV/comments/1eziba8/pioneer_1_complete_system_for_sale)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-08-23T17:16:43+00:00

<!-- SC_OFF --><div class="md"><p>If this isn't permitted, I'll e-Bay it and post the link, but we're taking offers (via PM). </p> <p>My manager doesn't want this and neither does anyone on our team (including me). </p> <p>Item: <a href="https://milkv.io/pioneer">https://milkv.io/pioneer</a></p> <p>Many of you saw my &quot;building an HPC&quot; post, but after we tested this against our infrastructure's benchmarks, it's not going to work so we're not going to develop for Risc-V right now.</p> <p>I'll ship globally, but I'd heavily prefer someone in the USA to buy this. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Bitwise_Gamgee"> /u/Bitwise_Gamgee </a> <br /> <span><a href="https://www.reddit.com/r/RISCV/comments/1eziba8/pioneer_1_complete_system_for_sale/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1eziba8/pioneer_1_complete_system_for_sale/">[comments]</a></span>

## Dubhe-70 ?
 - [https://www.reddit.com/r/RISCV/comments/1ezc1kx/dubhe70](https://www.reddit.com/r/RISCV/comments/1ezc1kx/dubhe70)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-08-23T12:56:09+00:00

<!-- SC_OFF --><div class="md"><p>The Dubhe-70 is not listed on the <a href="https://www.starfivetech.com/en/site/riscv-core-ip">StarFive website</a> (yet).</p> <p>Until there is physical hardware that you can hold in your hand and powerup, assume that the below is speculative at best (A FPGA is different than a production ready CPU on a board).</p> <p>I was browsing around StarFive's github account when I noticed this to boot their FPGA prototypes: <a href="https://github.com/starfive-tech/u-boot/tree/dubhe_fpga_dev_v2023.10/arch/riscv/dts">https://github.com/starfive-tech/u-boot/tree/dubhe_fpga_dev_v2023.10/arch/riscv/dts</a></p> <p>The interesting files, for me, were updated 3 months ago: <a href="https://github.com/starfive-tech/u-boot/blob/dubhe_fpga_dev_v2023.10/arch/riscv/dts/dubhe70-cpus.dtsi#L34-L39">dubhe70-cpus.dtsi</a>, <a href="https://github.com/starfive-tech/u-boot/blob/dubhe_fpga_dev_v2023.10/arch/riscv/dts/dubhe80-cpus.dtsi#L34-L39">dubhe80-cpus.dtsi</a> and <a href="

## EIC7700x Eval Board.
 - [https://www.reddit.com/r/RISCV/comments/1ezbzfb/eic7700x_eval_board](https://www.reddit.com/r/RISCV/comments/1ezbzfb/eic7700x_eval_board)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-08-23T12:53:20+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1ezbzfb/eic7700x_eval_board/"> <img alt="EIC7700x Eval Board. " src="https://preview.redd.it/u0w3ce1vuekd1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=b61d32009b1f668b6b08d29148ec7e867b4819e5" title="EIC7700x Eval Board. " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Just received the eswin EIC7700x eval board and thought I’d share my very preliminary impressions:</p> <p>It’s running a Debian distribution, rock-os, based on Debian SID. Full desktop environment out of the box and GPU acceleration via a IMGTEK AXM-8-256 GPU which is the high end of Imagination’s GPU Range. So far the desktop is very responsive and snappy. Firefox easily plays 1080p YouTube videos (I can’t test higher with the monitor it’s hooked up to) </p> <p>This board comes with 16Gb DDR5 running at 6400m/t which is pretty impressive. </p> <p>The SOC is clocked at 1.4Ghz, but can go up to 1.8Ghz. </p> <p>I ran <a href="https://github.com/T

## Performance of misaligned loads
 - [https://www.reddit.com/r/RISCV/comments/1ezbyr4/performance_of_misaligned_loads](https://www.reddit.com/r/RISCV/comments/1ezbyr4/performance_of_misaligned_loads)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-08-23T12:52:26+00:00

<!-- SC_OFF --><div class="md"><p>Here is a simple piece of code which performs unaligned load of a 64 bit integer: <a href="https://rust.godbolt.org/z/bM5rG6zds">https://rust.godbolt.org/z/bM5rG6zds</a> It compiles down to 22 interdependent instructions (i.e. there is not much opportunity for CPU to execute them in parallel) and puts a fair bit of register pressure! It becomes even worse when we try to load big-endian integers (without the zbkb extension): <a href="https://rust.godbolt.org/z/TndWTK3zh">https://rust.godbolt.org/z/TndWTK3zh</a> (an unfortunately common occurrence in cryptographic code)</p> <p>The LD instruction theoretically allows unaligned loads, but the reference is disappointingly vague about it. Behavior can range from full hardware support, followed by extremely slow emulation (IIUC slower than execution of the 22 instructions), and end with fatal trap, so portable code simply can not rely on it.</p> <p>There is the Zicclsm extension, but the profiles spec is aga

## Garbled header file when compiling TyrQuake on the Banana Pi F3 with Bianbu
 - [https://www.reddit.com/r/RISCV/comments/1ez9124/garbled_header_file_when_compiling_tyrquake_on](https://www.reddit.com/r/RISCV/comments/1ez9124/garbled_header_file_when_compiling_tyrquake_on)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-08-23T10:09:22+00:00

<!-- SC_OFF --><div class="md"><p>Anyone encountered any problems with header files, when compiling with gcc 13 on Bianbu OS? Or perhaps it's just a problem with TyrQuake?</p> <p>The header file is generated in a garbled state (text encoding problem?).</p> <p>This is a short snippet of the header file:</p> <p>\89\50\4E\47\80</p> <p>I'm testing some things I have done before on the VF2.</p> <p>I tried compiling TyrQuake, as described here: <a href="https://www.reddit.com/r/VisionFive/comments/114t8hx/playing_tyrquake_on_the_visionfive_2/">https://www.reddit.com/r/VisionFive/comments/114t8hx/playing_tyrquake_on_the_visionfive_2/</a></p> <p>Only difference is that the git repository seems to be gone, but you can download the source directly from the website.</p> <p>Compilation failed, because the header file tyrquake_icon_128.h doesn't get properly generated. I tried again on my Lichee Console, and there it compiles without problems. I copied the header file from my Lichee Console to the

