# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Does the SpacemiT K1/M1 have the zihintpause extension?
 - [https://www.reddit.com/r/RISCV/comments/1go1e9i/does_the_spacemit_k1m1_have_the_zihintpause](https://www.reddit.com/r/RISCV/comments/1go1e9i/does_the_spacemit_k1m1_have_the_zihintpause)
 - RSS feed: $source
 - date published: 2024-11-10T14:06:51+00:00

<!-- SC_OFF --><div class="md"><p>I found this post, but I don&#39;t know how to interpret it. Does the SpacemiT K1/M1 have the zihintpause extension?</p> <p><a href="https://lists.llvm.org/pipermail/cfe-commits/Week-of-Mon-20240603/585553.html">https://lists.llvm.org/pipermail/cfe-commits/Week-of-Mon-20240603/585553.html</a></p> <p>Now for some context. I saw a post on Bluesky that said that you can&#39;t run DuckDB in a RISC-V container. <a href="https://bsky.app/profile/carlopi.bsky.social/post/3lagvftq6di2y">https://bsky.app/profile/carlopi.bsky.social/post/3lagvftq6di2y</a></p> <p>So I thought, let&#39;s try to build DuckDB. <a href="https://duckdb.org/docs/dev/building/build_instructions.html">https://duckdb.org/docs/dev/building/build_instructions.html</a></p> <p>First I was struggling with the 10 threads that got spawned, and that is way too much for my 4GB RAM. I took 6 of the 8 cores offline, started the build and brought them back online. Now I see at the bottom of the pag

## Open Source Hardware RISC-V ESP32-P4-DevKit
 - [https://www.reddit.com/r/RISCV/comments/1gnw7b7/open_source_hardware_riscv_esp32p4devkit](https://www.reddit.com/r/RISCV/comments/1gnw7b7/open_source_hardware_riscv_esp32p4devkit)
 - RSS feed: $source
 - date published: 2024-11-10T08:31:50+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1gnw7b7/open_source_hardware_riscv_esp32p4devkit/"> <img src="https://external-preview.redd.it/nvRqqCrrXVYtPBVYqFSniCeANScu3RrQUMfmyJqpaIE.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=5d4b29c151c6e844c15aa8ccd9acf386e7f9428a" alt="Open Source Hardware RISC-V ESP32-P4-DevKit" title="Open Source Hardware RISC-V ESP32-P4-DevKit" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/fullgrid"> /u/fullgrid </a> <br/> <span><a href="https://olimex.wordpress.com/2024/11/08/the-new-open-source-hardware-dual-core-risc-v-esp32-p4-devkit-prototypes-are-alive/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1gnw7b7/open_source_hardware_riscv_esp32p4devkit/">[comments]</a></span> </td></tr></table>

## Code Review Request for Single Cycle RV32I and 5-Stage Pipeline Hazards
 - [https://www.reddit.com/r/RISCV/comments/1gnsmkv/code_review_request_for_single_cycle_rv32i_and](https://www.reddit.com/r/RISCV/comments/1gnsmkv/code_review_request_for_single_cycle_rv32i_and)
 - RSS feed: $source
 - date published: 2024-11-10T04:31:24+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I recently completed my implementation of a single-cycle RV32I core, and I’d really appreciate it if anyone with experience could take a look at my code. I’m looking for any suggestions or improvements to help optimize or clean up the design.</p> <p>Here’s the GitHub link to my project: <a href="https://github.com/TheRA1A/RISCV32I">RISCV32I GitHub Repository</a>.</p> <p>I&#39;m currently working on a 5-stage pipelined version, but I’m having some trouble managing hazards correctly. Any advice or resources on handling data and control hazards effectively in a pipelined RISC-V core would be really helpful.</p> <p>Thank you for your time and any guidance you can provide!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Minimum_Marsupial238"> /u/Minimum_Marsupial238 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1gnsmkv/code_review_request_for_single_cycle_rv32i_and/">[link]</a>

