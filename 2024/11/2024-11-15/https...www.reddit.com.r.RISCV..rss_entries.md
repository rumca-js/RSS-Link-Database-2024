# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Help me correct my code plssssssss
 - [https://www.reddit.com/r/RISCV/comments/1gs8vzk/help_me_correct_my_code_plssssssss](https://www.reddit.com/r/RISCV/comments/1gs8vzk/help_me_correct_my_code_plssssssss)
 - RSS feed: $source
 - date published: 2024-11-15T22:42:53+00:00

<!-- SC_OFF --><div class="md"><p>ADDI x12, x10, 4(x11)</p> <p>ADD x13, X0, x10</p> <p>SVPC x5, 1</p> <p>LD x14, x10</p> <p>LD x15, x13</p> <p>SVPC x6, 4</p> <p>SUB x17, x14, x15</p> <p>BRN x6</p> <p>ADD x13, X0, x10</p> <p>INC x10, x10, 4</p> <p>SUB x16, x10, x12</p> <p>BRN x5</p> <p>LD x19, x13</p> <p>NOP</p> <p>MAX = max {a1, a2, a3, ..., an-1, an}<br/> code to find maximum<br/> svpc is save program counter</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/UsefulVariation5508"> /u/UsefulVariation5508 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1gs8vzk/help_me_correct_my_code_plssssssss/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1gs8vzk/help_me_correct_my_code_plssssssss/">[comments]</a></span>

## SG2044 score on geekbench
 - [https://www.reddit.com/r/RISCV/comments/1gs16ca/sg2044_score_on_geekbench](https://www.reddit.com/r/RISCV/comments/1gs16ca/sg2044_score_on_geekbench)
 - RSS feed: $source
 - date published: 2024-11-15T17:07:29+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://browser.geekbench.com/v6/cpu/8661173">https://browser.geekbench.com/v6/cpu/8661173</a></p> <p>It&#39;s great to see the full extension list and that they also added support for the bitmanipulation instructions.</p> <p>Here is the comparison with the SG2042: <a href="https://browser.geekbench.com/v6/cpu/compare/8661173?baseline=8318305">https://browser.geekbench.com/v6/cpu/compare/8661173?baseline=8318305</a></p> <p>The ST performance is the same, which shows that geekbench doesn&#39;t use any of the new extensions.</p> <p>The MT performance has huge 3-4x improvements for some of the benchmarks, and smaller ones for others.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/camel-cdr-"> /u/camel-cdr- </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1gs16ca/sg2044_score_on_geekbench/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1gs16ca/sg2044_score_

## Need Help with Implementing Memory Ordering and Memory-Mapped Control Registers in a 5-Stage RISC-V Pipeline
 - [https://www.reddit.com/r/RISCV/comments/1gruoyp/need_help_with_implementing_memory_ordering_and](https://www.reddit.com/r/RISCV/comments/1gruoyp/need_help_with_implementing_memory_ordering_and)
 - RSS feed: $source
 - date published: 2024-11-15T11:55:34+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys,I&#39;m currently working on implementing memory ordering instructions in a 5-stage RISC-V pipeline. I’m trying to understand how memory-mapped control registers can observe or control access to memory in this context.</p> <p>Specifically, I’m interested in:</p> <p>How these control registers handle or respond to different stages of memory access.</p> <p>Any recommended techniques or best practices for ensuring memory ordering while integrating these registers.</p> <p>Challenges others have faced with similar implementations.</p> <p>Any insights or advice on handling memory-mapped control registers for enforcing memory ordering would be greatly appreciated. Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kinzahahah"> /u/kinzahahah </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1gruoyp/need_help_with_implementing_memory_ordering_and/">[link]</a></span> &#32; <span><a href="https

## Is Each thread has a own PC value in multithreading Program?
 - [https://www.reddit.com/r/RISCV/comments/1grqbbi/is_each_thread_has_a_own_pc_value_in](https://www.reddit.com/r/RISCV/comments/1grqbbi/is_each_thread_has_a_own_pc_value_in)
 - RSS feed: $source
 - date published: 2024-11-15T06:34:47+00:00

<!-- SC_OFF --><div class="md"><p>HI, Im currently working on a Hard ware for Data Race detect</p> <p>So I track each instructions and made history table for race detect.</p> <p>I made C program for Intended data race and Track instructions by PC value</p> <p>but regardless of data race I cant track multi thread.</p> <p>So my question is <strong>&quot;Is Each thread has a own PC value in multithreading Program?&quot;</strong></p> <p>for eg</p> <p>if thread A and B attempt to use </p> <p><strong>&quot;108ac:</strong> <strong>8141a783</strong> <strong>lw</strong> <strong>a5,-2028(gp) # 1209c &lt;gBadInt&gt;/ &quot;</strong> </p> <p>at the same time </p> <p>is PC value is different? </p> <p>l mean</p> <p>A&#39;s PC=108ac</p> <p>B&#39;s PC =108ab </p> <p>like this </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LingonberryOk5517"> /u/LingonberryOk5517 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1grqbbi/is_each_thread_has_a_own

## Can anyone explain how IMSIC handles MSI interrupt I am new to riscv architeture?
 - [https://www.reddit.com/r/RISCV/comments/1grpvei/can_anyone_explain_how_imsic_handles_msi](https://www.reddit.com/r/RISCV/comments/1grpvei/can_anyone_explain_how_imsic_handles_msi)
 - RSS feed: $source
 - date published: 2024-11-15T06:05:31+00:00

<!-- SC_OFF --><div class="md"><p>I have some data to send a struct containing addresses and IDs can IMSIC help me if I can send messages if not why not. also what kind of messages I can send. are there any good explainable resources to read about it</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Lucky_Mousse_8097"> /u/Lucky_Mousse_8097 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1grpvei/can_anyone_explain_how_imsic_handles_msi/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1grpvei/can_anyone_explain_how_imsic_handles_msi/">[comments]</a></span>

## Public review for standard extensions Zilsd & Zclsd: load/store register pair in RV32
 - [https://www.reddit.com/r/RISCV/comments/1grn4tn/public_review_for_standard_extensions_zilsd_zclsd](https://www.reddit.com/r/RISCV/comments/1grn4tn/public_review_for_standard_extensions_zilsd_zclsd)
 - RSS feed: $source
 - date published: 2024-11-15T03:24:20+00:00

<!-- SC_OFF --><div class="md"><p>TLDR: enables the usual RV64 encodings for <code>ld</code>, <code>sd</code>, <code>c.ld</code>, <code>c.sd</code>, <code>c.ldsp</code>, <code>c.sdsp</code> in RV32, loading or storing an even/odd register pair.</p> <p><a href="https://github.com/riscv/riscv-zilsd/releases/download/v1.0-rc1/riscv-zilsd-v1.0-rc1.pdf">https://github.com/riscv/riscv-zilsd/releases/download/v1.0-rc1/riscv-zilsd-v1.0-rc1.pdf</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/brucehoult"> /u/brucehoult </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1grn4tn/public_review_for_standard_extensions_zilsd_zclsd/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1grn4tn/public_review_for_standard_extensions_zilsd_zclsd/">[comments]</a></span>

