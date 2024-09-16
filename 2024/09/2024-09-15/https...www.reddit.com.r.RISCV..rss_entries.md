# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## RISC-V Big-endian: which hardware supports it?
 - [https://www.reddit.com/r/RISCV/comments/1fhpu2j/riscv_bigendian_which_hardware_supports_it](https://www.reddit.com/r/RISCV/comments/1fhpu2j/riscv_bigendian_which_hardware_supports_it)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-09-15T23:02:55+00:00

<!-- SC_OFF --><div class="md"><p>GCC docs mentions `riscv64be` as a supported CPU: <a href="https://gcc.gnu.org/install/configure.html">https://gcc.gnu.org/install/configure.html</a> </p> <p>Does anyone know what actual hardware supports it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/arjuna93"> /u/arjuna93 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1fhpu2j/riscv_bigendian_which_hardware_supports_it/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fhpu2j/riscv_bigendian_which_hardware_supports_it/">[comments]</a></span>

## Q about branding: RISC-V logo on processors
 - [https://www.reddit.com/r/RISCV/comments/1fhin6r/q_about_branding_riscv_logo_on_processors](https://www.reddit.com/r/RISCV/comments/1fhin6r/q_about_branding_riscv_logo_on_processors)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-09-15T17:54:10+00:00

<!-- SC_OFF --><div class="md"><p>why there is risc-v logo on most pictures of risc-v processors, while other ISA processors have their manufacturer logo (Intel, AMD, Qualcomm, Apple etc.)? is it just the CG representation and the actual processors don&#39;t actually have risc-v logo on them?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kantzkasper"> /u/kantzkasper </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1fhin6r/q_about_branding_riscv_logo_on_processors/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fhin6r/q_about_branding_riscv_logo_on_processors/">[comments]</a></span>

## Has my logic improved?
 - [https://www.reddit.com/r/RISCV/comments/1fh7dzo/has_my_logic_improved](https://www.reddit.com/r/RISCV/comments/1fh7dzo/has_my_logic_improved)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-09-15T07:56:00+00:00

<!-- SC_OFF --><div class="md"><p>I design this core primarily as a fun side project. I have made another post some months ago when I made a first version of the core, which you can find <a href="https://www.reddit.com/r/FPGA/comments/1bmnm91/made_a_programmable_riscv32i_core_in_verilog/">here</a>. </p> <p>This time, I post seeking advice. Has my logic improved at all ? What can I do to further reduce LUT utilization? What is good, and what is bad at the current state of the project? The latest version is at branch testing.</p> <p><a href="https://github.com/AgamemnonasKyriazis/PYGMY-V32I/tree/testing">PYGMY</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Faulty-LogicGate"> /u/Faulty-LogicGate </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1fh7dzo/has_my_logic_improved/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fh7dzo/has_my_logic_improved/">[comments]</a></span>

## Clarification on VMSEQ Instruction Behavior
 - [https://www.reddit.com/r/RISCV/comments/1fh4ccf/clarification_on_vmseq_instruction_behavior](https://www.reddit.com/r/RISCV/comments/1fh4ccf/clarification_on_vmseq_instruction_behavior)
 - RSS feed: https://www.reddit.com/r/RISCV/.rss
 - date published: 2024-09-15T04:27:39+00:00

<!-- SC_OFF --><div class="md"><p>I am working with the vmseq.vv instruction and would like to confirm if my understanding is correct. Here&#39;s the scenario:</p> <p>Vectors:</p> <p>v10 = (10, 20, 32, 12)</p> <p>v15 = (10, 36, 11, 12)</p> <p>v30 = (62, 99, 68, 61)</p> <p>Applying the instruction:</p> <p>vmseq.vv v30, v10, v15</p> <p>According to the vmseq instruction, the comparison produces a mask (1001) indicating that the first and last elements of v10 and v15 are equal. Based on this mask, the updated values of v30 should be:</p> <p>v30 = (10, 99, 68, 12)</p> <p>Could you please confirm if this result is correct?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok-Cranberry-9010"> /u/Ok-Cranberry-9010 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1fh4ccf/clarification_on_vmseq_instruction_behavior/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1fh4ccf/clarification_on_vmseq_instruction_beh

