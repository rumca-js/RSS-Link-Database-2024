# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Are there any boards I should keep an eye out for?
 - [https://www.reddit.com/r/RISCV/comments/1ga9j77/are_there_any_boards_i_should_keep_an_eye_out_for](https://www.reddit.com/r/RISCV/comments/1ga9j77/are_there_any_boards_i_should_keep_an_eye_out_for)
 - RSS feed: $source
 - date published: 2024-10-23T12:39:12+00:00

<!-- SC_OFF --><div class="md"><p>I want a RISC-V board that&#39;s &#39;credit card sized&#39; and not an ITX board, for under $500. I don&#39;t have any specific requirements since I&#39;m just going to screw around with it, but I&#39;d prefer 2GB+ of ram. A pi zero form factor would be nice but not important.</p> <p>The only RISC-V hardware I have is the Mango Pi. Its neat but takes 10 minutes to boot with ZFS installed (don&#39;t ask xD)</p> <p>So far I got; Banana Pi and Orange Pi launched RISC-V boards recently. Milk-V announced a bunch of boards including &#39;competitors&#39; to the Nvidia Jetsons. Lichee Pi had a recent launch as well.</p> <p>Any other board / manufacturer I should know about?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Party_9001"> /u/Party_9001 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1ga9j77/are_there_any_boards_i_should_keep_an_eye_out_for/">[link]</a></span> &#32; <span><a href="https://w

## Eswin EIC7700X, am I not seeing something
 - [https://www.reddit.com/r/RISCV/comments/1ga85kk/eswin_eic7700x_am_i_not_seeing_something](https://www.reddit.com/r/RISCV/comments/1ga85kk/eswin_eic7700x_am_i_not_seeing_something)
 - RSS feed: $source
 - date published: 2024-10-23T11:26:55+00:00

<!-- SC_OFF --><div class="md"><p>I was looking at <a href="https://github.com/ThomasKaiser/sbc-bench">sbc-bench</a> and noticed that there was a result for one unnamed Eswin EIC7700X on the list of machines that were tested (Sorted-Results.md). But it was not exactly where I would have expected to see it on the list, compared to other RISC-V machines.</p> <table><thead> <tr> <th align="left">Device / details</th> <th align="left">Clockspeed</th> <th align="left">Kernel</th> <th align="left">Distro</th> <th align="left">7-zip multi</th> <th align="left">7-zip single</th> <th align="left">AES</th> <th align="left">memcpy</th> <th align="left">memset</th> </tr> </thead><tbody> <tr> <td align="left">Milk-V Pioneer(SG2042)</td> <td align="left">2000 MHz</td> <td align="left">6.1</td> <td align="left">Kinetic riscv64</td> <td align="left">59820</td> <td align="left">1622</td> <td align="left">43500</td> <td align="left">3620</td> <td align="left">4760</td> </tr> <tr> <td align="left">Milk-

## When will GCC emit `tail` pseudo instruction?
 - [https://www.reddit.com/r/RISCV/comments/1ga4z27/when_will_gcc_emit_tail_pseudo_instruction](https://www.reddit.com/r/RISCV/comments/1ga4z27/when_will_gcc_emit_tail_pseudo_instruction)
 - RSS feed: $source
 - date published: 2024-10-23T07:48:00+00:00

<!-- SC_OFF --><div class="md"><p>In what scenario will GCC emit <code>tail</code> pseudo instruction?</p> <p>I tried the tail recursion case, but GCC still gave me <code>call tail_call_function</code> with <code>-foptimize-sibling-calls</code>.</p> <p>``` juhan@debian:/tmp/tail-code$ cat test.c // C program to illustrate Tail Call Optimisation</p> <p>int tail_call_function(int x) { if (x == 0) return 0; return tail_call_function(x - 1); // Tail call }</p> <p>int main(){</p> <pre><code> int result = tail_call_function(5); return 0; </code></pre> <p>} juhan@debian:/tmp/tail-code$ riscv64-elf-gcc -foptimize-sibling-calls -S test.c juhan@debian:/tmp/tail-code$ cat test.s .file &quot;test.c&quot; .option nopic .attribute arch, &quot;rv64i2p1_m2p0_a2p1_f2p2_d2p2_c2p0_zicsr2p0_zifencei2p0&quot; .attribute unaligned_access, 0 .attribute stack_align, 16 .text .align 1 .globl tail_call_function .type tail_call_function, @function tail_call_function: addi sp,sp,-32 sd ra,24(sp) sd s0,16(sp) add

## Using CVA6-SDK to boot Linux
 - [https://www.reddit.com/r/RISCV/comments/1ga22so/using_cva6sdk_to_boot_linux](https://www.reddit.com/r/RISCV/comments/1ga22so/using_cva6sdk_to_boot_linux)
 - RSS feed: $source
 - date published: 2024-10-23T04:29:37+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to boot Linux using CVA6 SDK <a href="https://github.com/openhwgroup/cva6-sdk">https://github.com/openhwgroup/cva6-sdk</a></p> <p>What I am doing different is setting FW_TEXT_START=0x800000000 in OPENSBI so my whole monolithic OPENSBI+LINUX image is mapped to this address onwards. My software emulator DRAM is set to this addr. But what I am seeing that my system gets stuck randomly while booting up Linux. </p> <p>What I want to know is that Linux when set to this address, can it cause some issues to Page Tables entries that it creates or any config in Linux which I should modify.</p> <p>Any pointers regarding this will be helpful.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok-Sector-1538"> /u/Ok-Sector-1538 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1ga22so/using_cva6sdk_to_boot_linux/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1ga22so/u

## DeepComputing and Andes Technology Partner to Develop the World’s First RISC-V AI PC with 7nm QiLai SoC, Featuring Ubuntu Desktop
 - [https://www.reddit.com/r/RISCV/comments/1g9znnp/deepcomputing_and_andes_technology_partner_to](https://www.reddit.com/r/RISCV/comments/1g9znnp/deepcomputing_and_andes_technology_partner_to)
 - RSS feed: $source
 - date published: 2024-10-23T02:15:09+00:00

<!-- SC_OFF --><div class="md"><p>The Andes QiLai SoC contains 2 Andes RISC-V processors: a high-performance quad-core AX45MP cluster and an NX27V vector processor. The AX45MP superscalar multicore is optimized for Linux-based applications by configuring a 2MB Level-2 cache and a Memory Management Unit (MMU). The NX27V vector processor, with a 512-bit vector length and data path width, is specifically designed to handle AI workloads efficiently. Running at up to 2.2 GHz (AX45MP) and 1.5 GHz (NX27V), the QiLai SoC delivers high performance while maintaining low power consumption of approximately 5W at full speed. A configuration of the AX45MP is used in the Renesas RZ/Five MPU while two instances of the NX27V help construct the PE’s (Processing Elements) in the 8×8 PE array of the Meta Training and Inference Accelerator (MTIA).</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sdongles"> /u/sdongles </a> <br/> <span><a href="https://www.andestech.co

## SEGGER's Ozone offers enhanced debugging with RISC-V Semihosting
 - [https://www.reddit.com/r/RISCV/comments/1g9zh1j/seggers_ozone_offers_enhanced_debugging_with](https://www.reddit.com/r/RISCV/comments/1g9zh1j/seggers_ozone_offers_enhanced_debugging_with)
 - RSS feed: $source
 - date published: 2024-10-23T02:05:32+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1g9zh1j/seggers_ozone_offers_enhanced_debugging_with/"> <img src="https://external-preview.redd.it/XI5ErwSSy2G-oH3ljK5QqPCokDDolzjGJdZ73eoZJ3Y.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=0627896c078ca9dcbcbccf2715a2c13ee0e76609" alt="SEGGER's Ozone offers enhanced debugging with RISC-V Semihosting" title="SEGGER's Ozone offers enhanced debugging with RISC-V Semihosting" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sdongles"> /u/sdongles </a> <br/> <span><a href="https://www.segger.com/news/pr-241015-ozone-riscv-semihosting/?mtm_kwd=semihosting">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1g9zh1j/seggers_ozone_offers_enhanced_debugging_with/">[comments]</a></span> </td></tr></table>

## What is the most powerful general-purpose riscv64 machine a normal person can buy today? (Capable of running Linux)
 - [https://www.reddit.com/r/RISCV/comments/1g9yvlo/what_is_the_most_powerful_generalpurpose_riscv64](https://www.reddit.com/r/RISCV/comments/1g9yvlo/what_is_the_most_powerful_generalpurpose_riscv64)
 - RSS feed: $source
 - date published: 2024-10-23T01:35:06+00:00

<!-- SC_OFF --><div class="md"><p>See title. I&#39;d like to start trying out Linux on Risc-V but for some reason I haven&#39;t been able to find a straight answer to this question.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/brennanvincent1989"> /u/brennanvincent1989 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1g9yvlo/what_is_the_most_powerful_generalpurpose_riscv64/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1g9yvlo/what_is_the_most_powerful_generalpurpose_riscv64/">[comments]</a></span>

## Arm to Cancel Qualcomm Chip Design License in Escalation of Feud
 - [https://www.reddit.com/r/RISCV/comments/1g9ytix/arm_to_cancel_qualcomm_chip_design_license_in](https://www.reddit.com/r/RISCV/comments/1g9ytix/arm_to_cancel_qualcomm_chip_design_license_in)
 - RSS feed: $source
 - date published: 2024-10-23T01:32:08+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1g9ytix/arm_to_cancel_qualcomm_chip_design_license_in/"> <img src="https://external-preview.redd.it/0PIn4MOasWckcoGLxRqOux7nMhPtGuxYVqnSJUKY3Hs.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=497cda773af91baeb5a2801d0fd076498c5aa0d1" alt="Arm to Cancel Qualcomm Chip Design License in Escalation of Feud" title="Arm to Cancel Qualcomm Chip Design License in Escalation of Feud" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/brucehoult"> /u/brucehoult </a> <br/> <span><a href="https://www.bloomberg.com/news/articles/2024-10-23/arm-to-cancel-qualcomm-chip-design-license-in-escalation-of-feud">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1g9ytix/arm_to_cancel_qualcomm_chip_design_license_in/">[comments]</a></span> </td></tr></table>

