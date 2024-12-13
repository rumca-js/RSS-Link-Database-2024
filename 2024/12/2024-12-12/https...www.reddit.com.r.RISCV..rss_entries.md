# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Identifying which RISC-V extensions a given code may benefit from
 - [https://www.reddit.com/r/RISCV/comments/1hct6a2/identifying_which_riscv_extensions_a_given_code](https://www.reddit.com/r/RISCV/comments/1hct6a2/identifying_which_riscv_extensions_a_given_code)
 - RSS feed: $source
 - date published: 2024-12-12T19:30:58+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone.</p> <p>This may be a niche question but I&#39;m curious if there&#39;s any solution for it. Suppose I have a code involving specific operations (say, for example, matrix multiplication), and that it is not expected to change much over time. I wish to identify and buy a platform that implements just the bare minimum extensions required by the code.</p> <p>My question is: <strong>given a code, is there any tool that tells me which extensions does my platform need to implement?</strong></p> <p>Do RISC-V compilers give this kind of information? Also, I understand this is a nuanced question; e.g., I understand that, even if your platform doesn&#39;t have a given extension, you still can &quot;trap-and-emulate&quot; some of the non-implemented operations (at the cost of performance). Anyways, any sort of feedback will be appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/traquitanas"> /u/traquit

## request for hardware vendors
 - [https://www.reddit.com/r/RISCV/comments/1hceqj0/request_for_hardware_vendors](https://www.reddit.com/r/RISCV/comments/1hceqj0/request_for_hardware_vendors)
 - RSS feed: $source
 - date published: 2024-12-12T06:07:57+00:00

<!-- SC_OFF --><div class="md"><p>Please include the make and model of Ethernet controller(s) in your SoC or board (e.g., Synopsys DWC Ethernet QoS IP version 4.10 (GMAC)) in its documentation. We really need programming documentation, such as device register definitions; if possible, include a URL of such documentation.</p> <p>Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/geoff-collyer"> /u/geoff-collyer </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1hceqj0/request_for_hardware_vendors/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1hceqj0/request_for_hardware_vendors/">[comments]</a></span>

## Struggling with benchmarking. Help needed
 - [https://www.reddit.com/r/RISCV/comments/1hccn54/struggling_with_benchmarking_help_needed](https://www.reddit.com/r/RISCV/comments/1hccn54/struggling_with_benchmarking_help_needed)
 - RSS feed: $source
 - date published: 2024-12-12T04:00:55+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, in my last post, I mentioned that I am interested in benchmarking my custom RV32I core, however I am a complete novice in this. Right now, I just have my SystemVerilog files (core modules) and no access to any hardware. The core runs at around 120 MHz. I would like to try out Dhrystone benchmark and Fibonacci sequence benchmark as well. I have already installed riscv32-gnu-toolchain on my host linux system. </p> <p>My questions are:</p> <ol> <li><p>Since I do not have access to hardware, do I need to install QEMU or any other simulator?</p></li> <li><p>Does making minor changes in the Makefile suffice? In some repositories, I have seen &quot;syscalls.c&quot; and &quot;link.ld&quot; scripts. Do I need these to run the benchmarks? </p></li> </ol> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/riffsandtrills"> /u/riffsandtrills </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1hccn54/strugglin

