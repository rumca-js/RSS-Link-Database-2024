# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## We need memes!
 - [https://www.reddit.com/r/RISCV/comments/1hjjdvq/we_need_memes](https://www.reddit.com/r/RISCV/comments/1hjjdvq/we_need_memes)
 - RSS feed: $source
 - date published: 2024-12-21T21:16:24+00:00

<!-- SC_OFF --><div class="md"><p>RISC-V and the industry in general doesn&#39;t have enough shit posting! How can we change this situation?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/indolering"> /u/indolering </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1hjjdvq/we_need_memes/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1hjjdvq/we_need_memes/">[comments]</a></span>

## Good analysis of the trial.
 - [https://www.reddit.com/r/RISCV/comments/1hjifv9/good_analysis_of_the_trial](https://www.reddit.com/r/RISCV/comments/1hjifv9/good_analysis_of_the_trial)
 - RSS feed: $source
 - date published: 2024-12-21T20:30:01+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1hjifv9/good_analysis_of_the_trial/"> <img src="https://a.thumbs.redditmedia.com/r7njh4yZo0ueWCUB2l-96qZc58lpXIHbGPurFFZPwq0.jpg" alt="Good analysis of the trial." title="Good analysis of the trial." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/indolering"> /u/indolering </a> <br/> <span><a href="https://www.tantraanalyst.com/ta/qualcomm-vs-arm-trial-day-5-qualcomm-wins/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1hjifv9/good_analysis_of_the_trial/">[comments]</a></span> </td></tr></table>

## Running an M-mode RV32 C-program on QEMU
 - [https://www.reddit.com/r/RISCV/comments/1hjbxyd/running_an_mmode_rv32_cprogram_on_qemu](https://www.reddit.com/r/RISCV/comments/1hjbxyd/running_an_mmode_rv32_cprogram_on_qemu)
 - RSS feed: $source
 - date published: 2024-12-21T15:22:12+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to run a simple program on QEMU. Somehow, the existing guides I am aware of do not really target this specific scenario.</p> <p>The toolchain I am using was built from the riscv-gnu-toolchain repository.</p> <p>riscv_bios.c:</p> <pre><code>#define UART0_TX_ADDR 0x10000000 void print_uart0(const char *s) { while (*s != &#39;\0&#39;) { *((volatile char *)UART0_TX_ADDR) = *s; // Send character to UART s++; } } void _start() { // Entry point for the program print_uart0(&quot;Hello, RISC-V BIOS!\n&quot;); while (1) { // Infinite loop to keep the program running } } </code></pre> <p>Build:</p> <pre><code>riscv32-unknown-elf-gcc -g -nostdlib -march=rv32imac -mabi=ilp32 -Ttext=0x80000000 -o riscv_bios.elf riscv_bios.c riscv32-unknown-elf-objcopy -O binary riscv_bios.elf riscv_bios.bin </code></pre> <p>Run:</p> <pre><code>qemu-system-riscv32 -machine virt -nographic -s -S -bios riscv_bios.bin </code></pre> <p>Debugging:</p> <pre><code>riscv32-unkn

## Issue with systemd-boot
 - [https://www.reddit.com/r/RISCV/comments/1hjbdvp/issue_with_systemdboot](https://www.reddit.com/r/RISCV/comments/1hjbdvp/issue_with_systemdboot)
 - RSS feed: $source
 - date published: 2024-12-21T14:53:41+00:00

<!-- SC_OFF --><div class="md"><p>So I am starting on my journey with riscv with my deepcomputing x framework machine, I want to boot their mostly <a href="https://github.com/DC-DeepComputing/DC-linux">mainline kernel</a> instead of the <a href="https://github.com/DC-DeepComputing/fml13v01-linux">vendored kernel</a> that it comes pre-installed with.</p> <p>So I made my own boot media with archlinuxriscv and systemd-boot, however systemd-boot seems to be an issue, even tried chainloading it with grub from the original image, but it gives me <code>error: unknown error</code> which is not very useful. I decided to try grub, and that does seem to work.</p> <p>Is it a known issue with systemd-boot on riscv? Or an issue with the firmware?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Owndampu"> /u/Owndampu </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1hjbdvp/issue_with_systemdboot/">[link]</a></span> &#32; <span><a href="https:/

## Are the highlighted paths in this micro-architecture feedback paths?
 - [https://www.reddit.com/r/RISCV/comments/1hj7a28/are_the_highlighted_paths_in_this](https://www.reddit.com/r/RISCV/comments/1hj7a28/are_the_highlighted_paths_in_this)
 - RSS feed: $source
 - date published: 2024-12-21T10:33:54+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1hj7a28/are_the_highlighted_paths_in_this/"> <img src="https://preview.redd.it/dwlycglcj68e1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=2df4e45bf89bea77fda658c3c3249a7bdbe2595a" alt="Are the highlighted paths in this micro-architecture feedback paths? " title="Are the highlighted paths in this micro-architecture feedback paths? " /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ambitious_Window_378"> /u/Ambitious_Window_378 </a> <br/> <span><a href="https://i.redd.it/dwlycglcj68e1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1hj7a28/are_the_highlighted_paths_in_this/">[comments]</a></span> </td></tr></table>

## Framework for Designing Pipelined/OoO Processors?
 - [https://www.reddit.com/r/RISCV/comments/1hj4ovc/framework_for_designing_pipelinedooo_processors](https://www.reddit.com/r/RISCV/comments/1hj4ovc/framework_for_designing_pipelinedooo_processors)
 - RSS feed: $source
 - date published: 2024-12-21T07:15:02+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking at trying my hand of designing my own RISC-V core cores in RTL. I&#39;ve seen when people design their own CPU cores online, they use software frameworks to be able to view the contents of the CPU/memory, as well as see how data flows through the pipeline. Does anyone know how this sort of visualization/debugging is done/how it communicates to the RTL running on a simulator or through an FPGA? What are popular/widely used software packages for this? I&#39;ve only ever built very rudimentary single cycle processors so I&#39;m just trying to get an idea for what software is used for developing and debugging more advanced core designs. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/itisyeetime"> /u/itisyeetime </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1hj4ovc/framework_for_designing_pipelinedooo_processors/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RI

## Arm lawsuit ends in mistrial with Qualcomm securing key win
 - [https://www.reddit.com/r/RISCV/comments/1hj4j0e/arm_lawsuit_ends_in_mistrial_with_qualcomm](https://www.reddit.com/r/RISCV/comments/1hj4j0e/arm_lawsuit_ends_in_mistrial_with_qualcomm)
 - RSS feed: $source
 - date published: 2024-12-21T07:02:40+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1hj4j0e/arm_lawsuit_ends_in_mistrial_with_qualcomm/"> <img src="https://external-preview.redd.it/QXFV-GKVY71dJDRBAsHDHdIitjUWr_GU-efyBH_HGow.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=be8f50bcae3ffaa4274eb2c6b62f2c6a2338a5e7" alt="Arm lawsuit ends in mistrial with Qualcomm securing key win" title="Arm lawsuit ends in mistrial with Qualcomm securing key win" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/indolering"> /u/indolering </a> <br/> <span><a href="https://www.cnbc.com/2024/12/20/arm-lawsuit-ends-in-mistrial-with-qualcomm-securing-key-win.html">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1hj4j0e/arm_lawsuit_ends_in_mistrial_with_qualcomm/">[comments]</a></span> </td></tr></table>

