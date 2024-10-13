# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## RISC-V cycle accurate simulators for evaluating specific microarchitecture potential improvements
 - [https://www.reddit.com/r/RISCV/comments/1g2515u/riscv_cycle_accurate_simulators_for_evaluating](https://www.reddit.com/r/RISCV/comments/1g2515u/riscv_cycle_accurate_simulators_for_evaluating)
 - RSS feed: $source
 - date published: 2024-10-12T17:20:39+00:00

<!-- SC_OFF --><div class="md"><p>I am currently doing my master&#39;s thesis about trying to see if a 3-1 ALU makes sense in RISC-V. The main idea is to see if an ALU that has a CSA + CLA for 3 operand operations is capable of executing 2 instructions that are dependant in one cycle for multiple issue machines ( so if ADD x1, x1, x2, ADD x4, x3, x1 do in one cycle x4 = x1 + x2 + x3 ) </p> <p>My first stage is to try to evaluate if this makes sense. As you can imagine, I am quite new and lost with this so any suggestion is super welcome and appreciated. However, my plan is to get a cycle accurate simulator where I am capable of running different benchmarks, with the ability to do the hardware changes and check performance with vs without the proposed improvement. The requirements for these simulators are that the simulation is quite accurate (instruction tracing would not me enough) and that target CPU to simulate is superscalar. The ability to do changes to the core easily and having

## Misc: Experiments generating RV64 code, with custom extensions.
 - [https://www.reddit.com/r/RISCV/comments/1g1xebk/misc_experiments_generating_rv64_code_with_custom](https://www.reddit.com/r/RISCV/comments/1g1xebk/misc_experiments_generating_rv64_code_with_custom)
 - RSS feed: $source
 - date published: 2024-10-12T10:41:08+00:00

<!-- SC_OFF --><div class="md"><p>I don&#39;t know if this will go over well, or poorly (possibly area for worry here).</p> <p>Some general context: * I have my own compiler, which natively supports a custom ISA, but recently has also gained RV64 support, mostly assumes RV64G as a starting point. * I have my own CPU core (written in Verilog), which supports both my own ISA and RV64GC. * Support for the C extension is more recent and experimental. * Thus far, RV64 support is mostly limited to the user-level ISA for now.</p> <p>I had initially added RV64 support: * More or less, RV64 was fairly close to a subset of my own ISA; * It could be supported mostly by having an alternate instruction decoder; * GCC can target it; * It seemed like GCC&#39;s good/mature code-generation could maybe give it an edge.</p> <p>Once I got RV64G code into a form that could be run on top of my custom OS, performance was a bit weak. GCC is clever, but there are a few weak points within the limits of RV64G t

## uLisp - A Lisp compiler to RISC-V written in Lisp
 - [https://www.reddit.com/r/RISCV/comments/1g1r54c/ulisp_a_lisp_compiler_to_riscv_written_in_lisp](https://www.reddit.com/r/RISCV/comments/1g1r54c/ulisp_a_lisp_compiler_to_riscv_written_in_lisp)
 - RSS feed: $source
 - date published: 2024-10-12T03:12:21+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/brucehoult"> /u/brucehoult </a> <br/> <span><a href="http://www.ulisp.com/show?4Y20">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1g1r54c/ulisp_a_lisp_compiler_to_riscv_written_in_lisp/">[comments]</a></span>

